# Comparing `tmp/fileio-wrapper-1.0.2.tar.gz` & `tmp/fileio-wrapper-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fileio-wrapper-1.0.2.tar", last modified: Sun Mar  5 15:41:15 2023, max compression
+gzip compressed data, was "fileio-wrapper-1.0.3.tar", last modified: Wed Jun 28 09:14:01 2023, max compression
```

## Comparing `fileio-wrapper-1.0.2.tar` & `fileio-wrapper-1.0.3.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-03-05 15:41:15.273285 fileio-wrapper-1.0.2/
--rw-rw-rw-   0        0        0     1086 2023-02-25 03:32:00.000000 fileio-wrapper-1.0.2/LICENSE
--rw-rw-rw-   0        0        0    15077 2023-03-05 15:41:15.274307 fileio-wrapper-1.0.2/PKG-INFO
--rw-rw-rw-   0        0        0    13423 2023-03-05 14:59:45.000000 fileio-wrapper-1.0.2/README.md
--rw-rw-rw-   0        0        0       82 2023-03-02 03:49:46.000000 fileio-wrapper-1.0.2/pyproject.toml
--rw-rw-rw-   0        0        0      975 2023-03-05 15:41:15.280327 fileio-wrapper-1.0.2/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-03-05 15:41:15.231231 fileio-wrapper-1.0.2/src/
-drwxrwxrwx   0        0        0        0 2023-03-05 15:41:15.246232 fileio-wrapper-1.0.2/src/fileio_wrapper/
--rw-rw-rw-   0        0        0       74 2023-03-03 02:09:20.000000 fileio-wrapper-1.0.2/src/fileio_wrapper/__init__.py
--rw-rw-rw-   0        0        0       21 2023-03-05 15:40:38.000000 fileio-wrapper-1.0.2/src/fileio_wrapper/__version__.py
--rw-rw-rw-   0        0        0    14779 2023-02-27 03:58:16.000000 fileio-wrapper-1.0.2/src/fileio_wrapper/fileio_wrapper.py
-drwxrwxrwx   0        0        0        0 2023-03-05 15:41:15.269293 fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/
--rw-rw-rw-   0        0        0    15077 2023-03-05 15:41:15.000000 fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      382 2023-03-05 15:41:15.000000 fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-03-05 15:41:15.000000 fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        9 2023-03-05 15:41:15.000000 fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/requires.txt
--rw-rw-rw-   0        0        0       15 2023-03-05 15:41:15.000000 fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/top_level.txt
-drwxrwxrwx   0        0        0        0 2023-03-05 15:41:15.271313 fileio-wrapper-1.0.2/tests/
--rw-rw-rw-   0        0        0     9803 2023-03-02 19:57:58.000000 fileio-wrapper-1.0.2/tests/test_fileio_wrapper.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:14:00.980000 fileio-wrapper-1.0.3/
+-rw-rw-rw-   0        0        0     1086 2023-06-28 09:06:28.000000 fileio-wrapper-1.0.3/LICENSE
+-rw-rw-rw-   0        0        0    15330 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/PKG-INFO
+-rw-rw-rw-   0        0        0    13676 2023-06-28 09:06:28.000000 fileio-wrapper-1.0.3/README.md
+-rw-rw-rw-   0        0        0       82 2023-06-28 09:06:28.000000 fileio-wrapper-1.0.3/pyproject.toml
+-rw-rw-rw-   0        0        0      975 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 09:14:01.000000 fileio-wrapper-1.0.3/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 09:14:01.010000 fileio-wrapper-1.0.3/src/fileio_wrapper/
+-rw-rw-rw-   0        0        0       74 2023-06-28 09:06:28.000000 fileio-wrapper-1.0.3/src/fileio_wrapper/__init__.py
+-rw-rw-rw-   0        0        0       21 2023-06-28 09:07:14.000000 fileio-wrapper-1.0.3/src/fileio_wrapper/__version__.py
+-rw-rw-rw-   0        0        0    14779 2023-06-28 09:06:28.000000 fileio-wrapper-1.0.3/src/fileio_wrapper/fileio_wrapper.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:14:01.030000 fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/
+-rw-rw-rw-   0        0        0    15330 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      382 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       15 2023-06-28 09:14:02.000000 fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 09:14:01.050000 fileio-wrapper-1.0.3/tests/
+-rw-rw-rw-   0        0        0     9803 2023-06-28 09:06:28.000000 fileio-wrapper-1.0.3/tests/test_fileio_wrapper.py
```

### Comparing `fileio-wrapper-1.0.2/LICENSE` & `fileio-wrapper-1.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `fileio-wrapper-1.0.2/PKG-INFO` & `fileio-wrapper-1.0.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 Metadata-Version: 2.1
 Name: fileio-wrapper
-Version: 1.0.2
+Version: 1.0.3
 Summary: Python wrapper for the online file sharing service file.io
 Home-page: https://github.com/Chumicat/fileio_wrapper
 Author: Chumicat
 Author-email: russell57260620@gmail.com
 License: MIT
 Keywords: API wrapper,upload,download,cloud storage,file.io,file-io
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.8
+Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 [![Python Test](https://github.com/chumicat/fileio_wrapper/actions/workflows/python-test.yml/badge.svg)](https://github.com/chumicat/fileio_wrapper/actions/workflows/python-test.yml)
-![PyPI - Downloads](https://img.shields.io/pypi/dm/fileio-wrapper)
-![GitHub](https://img.shields.io/github/license/chumicat/fileio_wrapper)
-![PyPI](https://img.shields.io/pypi/v/fileio-wrapper)
+[![PyPI - Downloads](https://img.shields.io/pypi/dm/fileio-wrapper)](https://pypistats.org/packages/fileio-wrapper)
+[![GitHub](https://img.shields.io/github/license/chumicat/fileio_wrapper)](LICENSE)
+[![PyPI](https://img.shields.io/pypi/v/fileio-wrapper)](https://pypi.org/project/fileio-wrapper/)
 
 # fileio-wrapper 
 This Python package is a wrapper for the file.io Restful API, allowing for easy 'uploading' and 'downloading' of files and retrieval of account information, such as storage usage and other relevant metrics.
 
 ## What is file.io?
 File.io is a cloud storage service that allows users to easily upload files, share them via links, and automatically delete them after download or within a set time period for added security. By default, the service is configured to delete files after they have been downloaded once.
  
@@ -64,16 +64,16 @@
 >    fileio = Fileio(fileio_api_key)
 >    ```
 
 ### Upload
 Uploading files to file.io is easy and can be done without authentication. However, if you authenticate with the service, you can manage your uploaded files and have access to greater storage capacity by purchasing a paid plan.
 > #### Upload Declaration: 
 > ```python
-> Fileio.upload(file, expires, max_downloads, auto_delete)
-> fileio.upload(file, expires, max_downloads, auto_delete)
+> Fileio.upload(file[, expires][, max_downloads][, auto_delete])
+> fileio.upload(file[, expires][, max_downloads][, auto_delete])
 > ```
 > #### Upload Parameter
 > | Parameter     | Description                                | Default Value | Free Account Limit |
 > |---------------|--------------------------------------------|---------------|--------------------|
 > | `file`        | The filepath of the file to upload         |               |                    |
 > | `expires`     | The expiration date of the uploaded file   | 14 days       | 1 year             |
 > | `max_downloads` | The maximum number of times the file can be downloaded | 1 | 1 |
@@ -113,16 +113,16 @@
 > link = resp['link']  # Link to file (not a direct link)
 > ```
 
 ### Download
 You can download the file from file.io without authentication. Notice that each file can only be downloaded once by default and will be automatically deleted afterwards, regardless of whether you authenticate or not. The maximum number of downloads allowed for a file is determined by the uploader, and can be increased with a paid account.
 > #### Download Declaration: 
 > ```python
-> Fileio.download(key, file)
-> fileio.download(key, file)
+> Fileio.download(key[, file])
+> fileio.download(key[, file])
 > ```
 > #### Download Parameter
 > | Parameter | Description                  | Default |
 > | --------- | ---------------------------- | ------- |
 > | `key`     | Identity of uploaded file    |         |
 > | `file`    | Filepath of file to download | `None`  |
 > 
@@ -153,15 +153,15 @@
 > name = resp['name']  # Filename of Downloaded file
 > ```
 
 ### List Files
 List File in an account. Authenticate is needed to call the method.
 > #### List Declaration: 
 > ```python
-> fileio.list(search, sort, offset, limit)
+> fileio.list([search][, sort][, offset][, limit])
 > ```
 > 
 > #### List Parameter
 > | Parameter     | Description                | Default |
 > | ------------- | -------------------------- | ------- |
 > | `search`      | Filter filename <br> (Can't search other field) | `None`  |
 > | `sort`        | Sort on specific field      | `None`  |
@@ -224,15 +224,16 @@
 > rate_limit = resp['rateLimit']  # Maximum number of API calls allowed per second
 > ```
 
 ### Update
 Update an uploaded file by providing its key and modifying its attributes, such as the expiration date, maximum number of downloads, or even the file itself associated with the key. Authenticate is needed to call the method.
 > #### Update Declaration: 
 > ```python
-> fileio.update(key, file, expires, max_downloads, auto_delete)
+> fileio.update(key[, file][, expires][, max_downloads][, auto_delete][, mode='replace_partial'])
+> fileio.update(key, file[, expires][, max_downloads][, auto_delete], mode='replace_all')
 > ```
 > #### Update Parameter
 > | Parameter     | Description                                | Default Value | Free Account Limit |
 > | ------------- | ------- | ------- | --- |
 > | `key` | Identity of uploaded file    |         |
 > | `file`        | The filepath of the file to upload         |               |                    |
 > | `expires`     | The expiration date of the uploaded file   | 14 days       | 1 year             |
```

### Comparing `fileio-wrapper-1.0.2/README.md` & `fileio-wrapper-1.0.3/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [![Python Test](https://github.com/chumicat/fileio_wrapper/actions/workflows/python-test.yml/badge.svg)](https://github.com/chumicat/fileio_wrapper/actions/workflows/python-test.yml)
-![PyPI - Downloads](https://img.shields.io/pypi/dm/fileio-wrapper)
-![GitHub](https://img.shields.io/github/license/chumicat/fileio_wrapper)
-![PyPI](https://img.shields.io/pypi/v/fileio-wrapper)
+[![PyPI - Downloads](https://img.shields.io/pypi/dm/fileio-wrapper)](https://pypistats.org/packages/fileio-wrapper)
+[![GitHub](https://img.shields.io/github/license/chumicat/fileio_wrapper)](LICENSE)
+[![PyPI](https://img.shields.io/pypi/v/fileio-wrapper)](https://pypi.org/project/fileio-wrapper/)
 
 # fileio-wrapper 
 This Python package is a wrapper for the file.io Restful API, allowing for easy 'uploading' and 'downloading' of files and retrieval of account information, such as storage usage and other relevant metrics.
 
 ## What is file.io?
 File.io is a cloud storage service that allows users to easily upload files, share them via links, and automatically delete them after download or within a set time period for added security. By default, the service is configured to delete files after they have been downloaded once.
  
@@ -48,16 +48,16 @@
 >    fileio = Fileio(fileio_api_key)
 >    ```
 
 ### Upload
 Uploading files to file.io is easy and can be done without authentication. However, if you authenticate with the service, you can manage your uploaded files and have access to greater storage capacity by purchasing a paid plan.
 > #### Upload Declaration: 
 > ```python
-> Fileio.upload(file, expires, max_downloads, auto_delete)
-> fileio.upload(file, expires, max_downloads, auto_delete)
+> Fileio.upload(file[, expires][, max_downloads][, auto_delete])
+> fileio.upload(file[, expires][, max_downloads][, auto_delete])
 > ```
 > #### Upload Parameter
 > | Parameter     | Description                                | Default Value | Free Account Limit |
 > |---------------|--------------------------------------------|---------------|--------------------|
 > | `file`        | The filepath of the file to upload         |               |                    |
 > | `expires`     | The expiration date of the uploaded file   | 14 days       | 1 year             |
 > | `max_downloads` | The maximum number of times the file can be downloaded | 1 | 1 |
@@ -97,16 +97,16 @@
 > link = resp['link']  # Link to file (not a direct link)
 > ```
 
 ### Download
 You can download the file from file.io without authentication. Notice that each file can only be downloaded once by default and will be automatically deleted afterwards, regardless of whether you authenticate or not. The maximum number of downloads allowed for a file is determined by the uploader, and can be increased with a paid account.
 > #### Download Declaration: 
 > ```python
-> Fileio.download(key, file)
-> fileio.download(key, file)
+> Fileio.download(key[, file])
+> fileio.download(key[, file])
 > ```
 > #### Download Parameter
 > | Parameter | Description                  | Default |
 > | --------- | ---------------------------- | ------- |
 > | `key`     | Identity of uploaded file    |         |
 > | `file`    | Filepath of file to download | `None`  |
 > 
@@ -137,15 +137,15 @@
 > name = resp['name']  # Filename of Downloaded file
 > ```
 
 ### List Files
 List File in an account. Authenticate is needed to call the method.
 > #### List Declaration: 
 > ```python
-> fileio.list(search, sort, offset, limit)
+> fileio.list([search][, sort][, offset][, limit])
 > ```
 > 
 > #### List Parameter
 > | Parameter     | Description                | Default |
 > | ------------- | -------------------------- | ------- |
 > | `search`      | Filter filename <br> (Can't search other field) | `None`  |
 > | `sort`        | Sort on specific field      | `None`  |
@@ -208,15 +208,16 @@
 > rate_limit = resp['rateLimit']  # Maximum number of API calls allowed per second
 > ```
 
 ### Update
 Update an uploaded file by providing its key and modifying its attributes, such as the expiration date, maximum number of downloads, or even the file itself associated with the key. Authenticate is needed to call the method.
 > #### Update Declaration: 
 > ```python
-> fileio.update(key, file, expires, max_downloads, auto_delete)
+> fileio.update(key[, file][, expires][, max_downloads][, auto_delete][, mode='replace_partial'])
+> fileio.update(key, file[, expires][, max_downloads][, auto_delete], mode='replace_all')
 > ```
 > #### Update Parameter
 > | Parameter     | Description                                | Default Value | Free Account Limit |
 > | ------------- | ------- | ------- | --- |
 > | `key` | Identity of uploaded file    |         |
 > | `file`        | The filepath of the file to upload         |               |                    |
 > | `expires`     | The expiration date of the uploaded file   | 14 days       | 1 year             |
```

### Comparing `fileio-wrapper-1.0.2/setup.cfg` & `fileio-wrapper-1.0.3/setup.cfg`

 * *Files 11% similar despite different names*

```diff
@@ -36,15 +36,15 @@
 00000230: 3a20 4f53 2049 6e64 6570 656e 6465 6e74  : OS Independent
 00000240: 0d0a 0d0a 5b6f 7074 696f 6e73 5d0d 0a69  ....[options]..i
 00000250: 6e63 6c75 6465 5f70 6163 6b61 6765 5f64  nclude_package_d
 00000260: 6174 6120 3d20 4661 6c73 650d 0a70 6163  ata = False..pac
 00000270: 6b61 6765 5f64 6972 203d 200d 0a09 3d73  kage_dir = ...=s
 00000280: 7263 0d0a 7061 636b 6167 6573 203d 2066  rc..packages = f
 00000290: 696e 643a 0d0a 7079 7468 6f6e 5f72 6571  ind:..python_req
-000002a0: 7569 7265 7320 3d20 3e3d 332e 380d 0a69  uires = >=3.8..i
+000002a0: 7569 7265 7320 3d20 3e3d 332e 360d 0a69  uires = >=3.6..i
 000002b0: 6e73 7461 6c6c 5f72 6571 7569 7265 7320  nstall_requires 
 000002c0: 3d20 0d0a 0972 6571 7565 7374 730d 0a74  = ...requests..t
 000002d0: 6573 7473 5f72 6571 7569 7265 203d 200d  ests_require = .
 000002e0: 0a09 7261 7465 6c69 6d69 740d 0a73 6574  ..ratelimit..set
 000002f0: 7570 5f72 6571 7569 7265 7320 3d20 0d0a  up_requires = ..
 00000300: 0973 6574 7570 746f 6f6c 7320 3e3d 2034  .setuptools >= 4
 00000310: 302e 382e 300d 0a09 7768 6565 6c0d 0a09  0.8.0...wheel...
```

### Comparing `fileio-wrapper-1.0.2/src/fileio_wrapper/fileio_wrapper.py` & `fileio-wrapper-1.0.3/src/fileio_wrapper/fileio_wrapper.py`

 * *Files identical despite different names*

### Comparing `fileio-wrapper-1.0.2/src/fileio_wrapper.egg-info/PKG-INFO` & `fileio-wrapper-1.0.3/src/fileio_wrapper.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 Metadata-Version: 2.1
 Name: fileio-wrapper
-Version: 1.0.2
+Version: 1.0.3
 Summary: Python wrapper for the online file sharing service file.io
 Home-page: https://github.com/Chumicat/fileio_wrapper
 Author: Chumicat
 Author-email: russell57260620@gmail.com
 License: MIT
 Keywords: API wrapper,upload,download,cloud storage,file.io,file-io
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.8
+Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 [![Python Test](https://github.com/chumicat/fileio_wrapper/actions/workflows/python-test.yml/badge.svg)](https://github.com/chumicat/fileio_wrapper/actions/workflows/python-test.yml)
-![PyPI - Downloads](https://img.shields.io/pypi/dm/fileio-wrapper)
-![GitHub](https://img.shields.io/github/license/chumicat/fileio_wrapper)
-![PyPI](https://img.shields.io/pypi/v/fileio-wrapper)
+[![PyPI - Downloads](https://img.shields.io/pypi/dm/fileio-wrapper)](https://pypistats.org/packages/fileio-wrapper)
+[![GitHub](https://img.shields.io/github/license/chumicat/fileio_wrapper)](LICENSE)
+[![PyPI](https://img.shields.io/pypi/v/fileio-wrapper)](https://pypi.org/project/fileio-wrapper/)
 
 # fileio-wrapper 
 This Python package is a wrapper for the file.io Restful API, allowing for easy 'uploading' and 'downloading' of files and retrieval of account information, such as storage usage and other relevant metrics.
 
 ## What is file.io?
 File.io is a cloud storage service that allows users to easily upload files, share them via links, and automatically delete them after download or within a set time period for added security. By default, the service is configured to delete files after they have been downloaded once.
  
@@ -64,16 +64,16 @@
 >    fileio = Fileio(fileio_api_key)
 >    ```
 
 ### Upload
 Uploading files to file.io is easy and can be done without authentication. However, if you authenticate with the service, you can manage your uploaded files and have access to greater storage capacity by purchasing a paid plan.
 > #### Upload Declaration: 
 > ```python
-> Fileio.upload(file, expires, max_downloads, auto_delete)
-> fileio.upload(file, expires, max_downloads, auto_delete)
+> Fileio.upload(file[, expires][, max_downloads][, auto_delete])
+> fileio.upload(file[, expires][, max_downloads][, auto_delete])
 > ```
 > #### Upload Parameter
 > | Parameter     | Description                                | Default Value | Free Account Limit |
 > |---------------|--------------------------------------------|---------------|--------------------|
 > | `file`        | The filepath of the file to upload         |               |                    |
 > | `expires`     | The expiration date of the uploaded file   | 14 days       | 1 year             |
 > | `max_downloads` | The maximum number of times the file can be downloaded | 1 | 1 |
@@ -113,16 +113,16 @@
 > link = resp['link']  # Link to file (not a direct link)
 > ```
 
 ### Download
 You can download the file from file.io without authentication. Notice that each file can only be downloaded once by default and will be automatically deleted afterwards, regardless of whether you authenticate or not. The maximum number of downloads allowed for a file is determined by the uploader, and can be increased with a paid account.
 > #### Download Declaration: 
 > ```python
-> Fileio.download(key, file)
-> fileio.download(key, file)
+> Fileio.download(key[, file])
+> fileio.download(key[, file])
 > ```
 > #### Download Parameter
 > | Parameter | Description                  | Default |
 > | --------- | ---------------------------- | ------- |
 > | `key`     | Identity of uploaded file    |         |
 > | `file`    | Filepath of file to download | `None`  |
 > 
@@ -153,15 +153,15 @@
 > name = resp['name']  # Filename of Downloaded file
 > ```
 
 ### List Files
 List File in an account. Authenticate is needed to call the method.
 > #### List Declaration: 
 > ```python
-> fileio.list(search, sort, offset, limit)
+> fileio.list([search][, sort][, offset][, limit])
 > ```
 > 
 > #### List Parameter
 > | Parameter     | Description                | Default |
 > | ------------- | -------------------------- | ------- |
 > | `search`      | Filter filename <br> (Can't search other field) | `None`  |
 > | `sort`        | Sort on specific field      | `None`  |
@@ -224,15 +224,16 @@
 > rate_limit = resp['rateLimit']  # Maximum number of API calls allowed per second
 > ```
 
 ### Update
 Update an uploaded file by providing its key and modifying its attributes, such as the expiration date, maximum number of downloads, or even the file itself associated with the key. Authenticate is needed to call the method.
 > #### Update Declaration: 
 > ```python
-> fileio.update(key, file, expires, max_downloads, auto_delete)
+> fileio.update(key[, file][, expires][, max_downloads][, auto_delete][, mode='replace_partial'])
+> fileio.update(key, file[, expires][, max_downloads][, auto_delete], mode='replace_all')
 > ```
 > #### Update Parameter
 > | Parameter     | Description                                | Default Value | Free Account Limit |
 > | ------------- | ------- | ------- | --- |
 > | `key` | Identity of uploaded file    |         |
 > | `file`        | The filepath of the file to upload         |               |                    |
 > | `expires`     | The expiration date of the uploaded file   | 14 days       | 1 year             |
```

### Comparing `fileio-wrapper-1.0.2/tests/test_fileio_wrapper.py` & `fileio-wrapper-1.0.3/tests/test_fileio_wrapper.py`

 * *Files identical despite different names*


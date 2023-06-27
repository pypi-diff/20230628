# Comparing `tmp/zscaler_api_talkers-4.0.2.tar.gz` & `tmp/zscaler_api_talkers-4.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "zscaler_api_talkers-4.0.2.tar", last modified: Tue Apr 25 00:45:25 2023, max compression
+gzip compressed data, was "zscaler_api_talkers-4.1.0.tar", max compression
```

## Comparing `zscaler_api_talkers-4.0.2.tar` & `zscaler_api_talkers-4.1.0.tar`

### file list

```diff
@@ -1,30 +1,21 @@
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.062869 zscaler_api_talkers-4.0.2/
--rw-r--r--   0 spereira   (501) staff       (20)     1071 2022-04-21 16:27:44.000000 zscaler_api_talkers-4.0.2/LICENSE.txt
--rw-r--r--   0 spereira   (501) staff       (20)     3031 2023-04-25 00:45:25.062569 zscaler_api_talkers-4.0.2/PKG-INFO
--rw-r--r--   0 spereira   (501) staff       (20)     2683 2023-04-19 16:20:53.000000 zscaler_api_talkers-4.0.2/README.md
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.054010 zscaler_api_talkers-4.0.2/models/
--rw-r--r--   0 spereira   (501) staff       (20)        0 2022-12-14 01:53:08.000000 zscaler_api_talkers-4.0.2/models/__init__.py
--rw-r--r--   0 spereira   (501) staff       (20)    14364 2022-12-14 01:53:08.000000 zscaler_api_talkers-4.0.2/models/models.py
--rw-r--r--   0 spereira   (501) staff       (20)       84 2022-04-21 20:33:36.000000 zscaler_api_talkers-4.0.2/pyproject.toml
--rw-r--r--   0 spereira   (501) staff       (20)       38 2023-04-25 00:45:25.062949 zscaler_api_talkers-4.0.2/setup.cfg
--rw-r--r--   0 spereira   (501) staff       (20)      568 2023-04-20 16:58:56.000000 zscaler_api_talkers-4.0.2/setup.py
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.054922 zscaler_api_talkers-4.0.2/zcc_talker/
--rw-r--r--   0 spereira   (501) staff       (20)        0 2022-12-14 01:53:08.000000 zscaler_api_talkers-4.0.2/zcc_talker/__init__.py
--rw-r--r--   0 spereira   (501) staff       (20)     4747 2023-04-05 17:08:58.000000 zscaler_api_talkers-4.0.2/zcc_talker/zcc_talker.py
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.056552 zscaler_api_talkers-4.0.2/zia_talker/
--rw-r--r--   0 spereira   (501) staff       (20)        0 2022-12-14 02:12:49.000000 zscaler_api_talkers-4.0.2/zia_talker/__init__.py
--rw-r--r--   0 spereira   (501) staff       (20)    15297 2023-04-20 16:51:44.000000 zscaler_api_talkers-4.0.2/zia_talker/zia_portaltalker.py
--rw-r--r--   0 spereira   (501) staff       (20)    66881 2023-04-14 15:49:45.000000 zscaler_api_talkers-4.0.2/zia_talker/zia_talker.py
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.059265 zscaler_api_talkers-4.0.2/zpa_talker/
--rw-r--r--   0 spereira   (501) staff       (20)        0 2022-12-14 01:53:08.000000 zscaler_api_talkers-4.0.2/zpa_talker/__init__.py
--rw-r--r--   0 spereira   (501) staff       (20)     2369 2023-04-05 17:08:09.000000 zscaler_api_talkers-4.0.2/zpa_talker/zpa_portaltalker.py
--rw-r--r--   0 spereira   (501) staff       (20)    22113 2023-04-25 00:44:34.000000 zscaler_api_talkers-4.0.2/zpa_talker/zpa_talker.py
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.061355 zscaler_api_talkers-4.0.2/zscaler_api_talkers.egg-info/
--rw-r--r--   0 spereira   (501) staff       (20)     3031 2023-04-25 00:45:24.000000 zscaler_api_talkers-4.0.2/zscaler_api_talkers.egg-info/PKG-INFO
--rw-r--r--   0 spereira   (501) staff       (20)      559 2023-04-25 00:45:25.000000 zscaler_api_talkers-4.0.2/zscaler_api_talkers.egg-info/SOURCES.txt
--rw-r--r--   0 spereira   (501) staff       (20)        1 2023-04-25 00:45:24.000000 zscaler_api_talkers-4.0.2/zscaler_api_talkers.egg-info/dependency_links.txt
--rw-r--r--   0 spereira   (501) staff       (20)       25 2023-04-25 00:45:24.000000 zscaler_api_talkers-4.0.2/zscaler_api_talkers.egg-info/requires.txt
--rw-r--r--   0 spereira   (501) staff       (20)       56 2023-04-25 00:45:24.000000 zscaler_api_talkers-4.0.2/zscaler_api_talkers.egg-info/top_level.txt
-drwxr-xr-x   0 spereira   (501) staff       (20)        0 2023-04-25 00:45:25.061847 zscaler_api_talkers-4.0.2/zscaler_helpers/
--rw-r--r--   0 spereira   (501) staff       (20)        0 2022-12-14 01:53:08.000000 zscaler_api_talkers-4.0.2/zscaler_helpers/__init__.py
--rw-r--r--   0 spereira   (501) staff       (20)     7203 2023-04-19 03:45:34.000000 zscaler_api_talkers-4.0.2/zscaler_helpers/http_calls.py
+-rw-r--r--   0        0        0     1071 2022-04-21 16:27:44.526756 zscaler_api_talkers-4.1.0/LICENSE.txt
+-rw-r--r--   0        0        0     2679 2023-06-27 21:07:15.062084 zscaler_api_talkers-4.1.0/README.md
+-rw-r--r--   0        0        0      454 2023-06-27 20:53:48.702831 zscaler_api_talkers-4.1.0/pyproject.toml
+-rw-r--r--   0        0        0      435 2023-06-27 20:53:48.706237 zscaler_api_talkers-4.1.0/zscaler_api_talkers/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-27 20:53:48.706445 zscaler_api_talkers-4.1.0/zscaler_api_talkers/models/__init__.py
+-rw-r--r--   0        0        0    13788 2023-06-27 20:53:48.707682 zscaler_api_talkers-4.1.0/zscaler_api_talkers/models/models.py
+-rw-r--r--   0        0        0        0 2023-06-27 20:53:48.707836 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zcc_talker/__init__.py
+-rw-r--r--   0        0        0     4910 2023-06-27 20:53:48.708260 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zcc_talker/zcc_talker.py
+-rw-r--r--   0        0        0        0 2023-06-27 20:53:48.708427 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zdx_talker/__init__.py
+-rw-r--r--   0        0        0    11378 2023-06-27 20:53:48.708864 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zdx_talker/zdx_portaltalker.py
+-rw-r--r--   0        0        0        0 2023-06-27 20:53:48.709020 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zia_talker/__init__.py
+-rw-r--r--   0        0        0    14967 2023-06-27 20:53:48.709468 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zia_talker/zia_portaltalker.py
+-rw-r--r--   0        0        0    68927 2023-06-27 20:53:48.710260 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zia_talker/zia_talker.py
+-rw-r--r--   0        0        0        0 2023-06-27 20:53:48.710832 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zpa_talker/__init__.py
+-rw-r--r--   0        0        0     2385 2023-06-27 20:53:48.711212 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zpa_talker/zpa_portaltalker.py
+-rw-r--r--   0        0        0    22707 2023-06-27 20:53:48.712114 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zpa_talker/zpa_talker.py
+-rw-r--r--   0        0        0      205 2023-06-27 20:53:48.717944 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zscaler_helpers/__init__.py
+-rw-r--r--   0        0        0     7782 2023-06-27 20:53:48.718457 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zscaler_helpers/http_calls.py
+-rw-r--r--   0        0        0     1707 2023-06-27 20:53:48.718942 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zscaler_helpers/logger.py
+-rw-r--r--   0        0        0     6487 2023-06-27 20:53:48.719333 zscaler_api_talkers-4.1.0/zscaler_api_talkers/zscaler_helpers/utilities.py
+-rw-r--r--   0        0        0     3169 1970-01-01 00:00:00.000000 zscaler_api_talkers-4.1.0/PKG-INFO
```

### Comparing `zscaler_api_talkers-4.0.2/LICENSE.txt` & `zscaler_api_talkers-4.1.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `zscaler_api_talkers-4.0.2/PKG-INFO` & `zscaler_api_talkers-4.1.0/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,18 +1,7 @@
-Metadata-Version: 2.1
-Name: zscaler_api_talkers
-Version: 4.0.2
-Summary: Unofficial Zscaler API python SDK for ZIA, ZPA and ZCC
-Home-page: https://github.com/sergitopereira/zscaler_api_talkers.git
-Author: Sergio Pereira
-Author-email: sergitopereira@hotmail.com
-License: LICENSE.txt
-Description-Content-Type: text/markdown
-License-File: LICENSE.txt
-
 # Unofficial Zscaler API talkers
 
 ### ZIA API Talker
 Python client to leverage  [Zscaler Internet Access API](https://help.zscaler.com/zia/api)
 
 ### ZPA API Talker
 Python client to leverage [Zscaler Private Access API](https://help.zscaler.com/zpa/api-reference)
@@ -53,49 +42,49 @@
    pip install zscaler-api-talkers  
 ```
 
 # Zscaler Secure Internet and SaaS Access SDK (zia_talker)
 
 ## Usage zia_talker
 ``` python
-from zia_talker.zia_talker import ZiaTalker
+from zscaler_api_talkers import ZiaTalker
 zia=ZiaTalker('<Zscaler Cloud Name>')
 zia.authenticate(apikey='API_KEY', username='USERNAME', password='PASSWORD')
 zia.list_urlcategories()
-a.list_users()
+zia.list_users()
 # To view all methods available
-print(dir(a))
+print(dir(zia))
 ```
 
 ## Usage zia_talker with OAUTH2.0
 ``` python
-from zia_talker.zia_talker import ZiaTalker
+from zscaler_api_talkers import ZiaTalker
 a=ZiaTalker('<Zscaler Cloud Name>', <Bear oauth2.0 token))
 a.list_url_categorie.url_categories()
 a.list_users()
 # To view all methods available
 print(dir(a))
 ```
 
 
 # Zscaler Secure Private Access SDK (zpa_talker)
 
 ## Usage zpa_talker
 ``` python
-from zpa_talker.zpa_talker import ZpaTalker
+from zscaler_api_talkers import ZpaTalker
 a=ZpaTalker('customerID')
 a.authenticate(client_id='clientID',client_secret='clientSecret')
 # To view all methods available
 print(dir(a))
 ```
 # Zscaler Client Connector SDK  (zcc_talker)
 
 ## Usage zcc_talker
 ``` python
-from zcc_talker.zcc_talker import ZccTalker
+from zscaler_api_talkers import ZccTalker
 a=ZccTalker('<Zscaler Cloud Name>')    
 a.authenticate(clientid='clientID',secretkey='clientSecret')
 a.list_devices('companyID')
 a.list_OTP('companyID','user device id')
 # To view all methods available
 print(dir(a))
 ```
```

### Comparing `zscaler_api_talkers-4.0.2/README.md` & `zscaler_api_talkers-4.1.0/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,7 +1,21 @@
+Metadata-Version: 2.1
+Name: zscaler-api-talkers
+Version: 4.1.0
+Summary: Unofficial Zscaler API python SDK for ZIA, ZPA, ZDX, and ZCC
+Author: Sergio Pereira
+Author-email: sergitopereira@hotmail.com
+Requires-Python: >=3.11,<4.0
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: appdirs (>=1.4.4,<2.0.0)
+Requires-Dist: ipython (>=8.14.0,<9.0.0)
+Requires-Dist: requests (>=2.31.0,<3.0.0)
+Description-Content-Type: text/markdown
+
 # Unofficial Zscaler API talkers
 
 ### ZIA API Talker
 Python client to leverage  [Zscaler Internet Access API](https://help.zscaler.com/zia/api)
 
 ### ZPA API Talker
 Python client to leverage [Zscaler Private Access API](https://help.zscaler.com/zpa/api-reference)
@@ -42,49 +56,49 @@
    pip install zscaler-api-talkers  
 ```
 
 # Zscaler Secure Internet and SaaS Access SDK (zia_talker)
 
 ## Usage zia_talker
 ``` python
-from zia_talker.zia_talker import ZiaTalker
+from zscaler_api_talkers import ZiaTalker
 zia=ZiaTalker('<Zscaler Cloud Name>')
 zia.authenticate(apikey='API_KEY', username='USERNAME', password='PASSWORD')
 zia.list_urlcategories()
-a.list_users()
+zia.list_users()
 # To view all methods available
-print(dir(a))
+print(dir(zia))
 ```
 
 ## Usage zia_talker with OAUTH2.0
 ``` python
-from zia_talker.zia_talker import ZiaTalker
+from zscaler_api_talkers import ZiaTalker
 a=ZiaTalker('<Zscaler Cloud Name>', <Bear oauth2.0 token))
 a.list_url_categorie.url_categories()
 a.list_users()
 # To view all methods available
 print(dir(a))
 ```
 
 
 # Zscaler Secure Private Access SDK (zpa_talker)
 
 ## Usage zpa_talker
 ``` python
-from zpa_talker.zpa_talker import ZpaTalker
+from zscaler_api_talkers import ZpaTalker
 a=ZpaTalker('customerID')
 a.authenticate(client_id='clientID',client_secret='clientSecret')
 # To view all methods available
 print(dir(a))
 ```
 # Zscaler Client Connector SDK  (zcc_talker)
 
 ## Usage zcc_talker
 ``` python
-from zcc_talker.zcc_talker import ZccTalker
+from zscaler_api_talkers import ZccTalker
 a=ZccTalker('<Zscaler Cloud Name>')    
 a.authenticate(clientid='clientID',secretkey='clientSecret')
 a.list_devices('companyID')
 a.list_OTP('companyID','user device id')
 # To view all methods available
 print(dir(a))
 ```
@@ -102,7 +116,8 @@
 
 Sergio Pereira 
 
 Zscaler Professional Services 
 
 
 
+
```

### Comparing `zscaler_api_talkers-4.0.2/zcc_talker/zcc_talker.py` & `zscaler_api_talkers-4.1.0/zscaler_api_talkers/zcc_talker/zcc_talker.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,54 +1,55 @@
-import pdb
 import time
 
-from zscaler_helpers.http_calls import HttpCalls
+from zscaler_helpers import HttpCalls
 
 
 class ZccTalker(object):
     """
     Client Connector API talker
     Documentation: under development
     Currently in beta status
     """
 
     def __init__(self, cloud):
-        self.base_uri = f'https://api-mobile.{cloud}/papi'
+        self.base_uri = f"https://api-mobile.{cloud}/papi"
         self.hp_http = HttpCalls(host=self.base_uri, verify=True)
         self.jsessionid = None
-        self.version = 'beta 0.1'
+        self.version = "beta 0.1"
 
     def authenticate(self, clientid, secretkey):
         """
         Method to authenticate.
         :param clientid: Client id
         :param secretkey: client secret, obtained from portal
         :return:  None
         """
-        payload = {
-            "apiKey": clientid,
-            "secretKey": secretkey
-        }
-        url = '/auth/v1/login'
-        response = self.hp_http.post_call(url=url, headers={'Accept': '*/*'}, payload=payload)
-        self.header = {
-            'auth-token': response.json()['jwtToken']
-        }
+        payload = {"apiKey": clientid, "secretKey": secretkey}
+        url = "/auth/v1/login"
+        response = self.hp_http.post_call(
+            url=url, headers={"Accept": "*/*"}, payload=payload
+        )
+        self.header = {"auth-token": response.json()["jwtToken"]}
 
     def _obtain_all(self, url, cookies=None, params=None, headers=None):
         """
         Internal method that queries all pages
         :param url:  URL
         :return:
         """
         page = 1
         result = []
         while True:
-            response = self.hp_http.get_call(f'{url}&page={page}', cookies=cookies, params=params, headers=headers,
-                                             error_handling=True)
+            response = self.hp_http.get_call(
+                f"{url}&page={page}",
+                cookies=cookies,
+                params=params,
+                headers=headers,
+                error_handling=True,
+            )
             if response.json():
                 result += response.json()
                 page += 1
                 time.sleep(0.5)
             else:
                 break
         return result
@@ -58,71 +59,73 @@
         Method to authenticate.
         :param companyID: type int. ORG ID
         :param username: type string. Username in email format
         :param osType  type int.
         :return:  type list
         """
         if username:
-            url = f'/public/v1/getDevices?username={username}'
+            url = f"/public/v1/getDevices?username={username}"
         elif osType:
-            url = f'/public/v1/getDevices?osType={osType}'
+            url = f"/public/v1/getDevices?osType={osType}"
         else:
-            url = '/public/v1/getDevices?pagesize100'
+            url = "/public/v1/getDevices?pagesize100"
         response = self._obtain_all(url=url, params=companyID, headers=self.header)
         return response
 
     def list_OTP(self, companyID, udid):
         """
         Method to fetch the One Time Password for a specific device. These passwords are unique and tied to a device UDID
         :param companyID: type int. ORG ID
         :param udid: type int. User device ID
         :return: type list
         """
-        url = f'/public/v1/getOtp?udid={udid}'
+        url = f"/public/v1/getOtp?udid={udid}"
         response = self.hp_http.get_call(url=url, params=companyID, headers=self.header)
         return response.json()
 
     def list_passwords(self, companyID, udid):
         """
         Method to fetch the One Time Password for a specific device. These passwords are unique and tied to a device UDID
         :param companyID: type int. ORG ID
         :param udid: type int. User device ID
         :return: type list
         """
-        url = f'/public/v1/getOtp?udid={udid}'
+        url = f"/public/v1/getOtp?udid={udid}"
         response = self.hp_http.get_call(url=url, params=companyID, headers=self.header)
         return response.json()
 
     def remove_devices(self, companyID, udids, osType=0):
         """
         Method to  mark the device for removal (Device Removal Pending).
         API currently can remove up to 30 devices per call
         :param companyID: type int. ORG ID
         :param udids: type list. List of user devices ids
         :param osType: 0 ALL OS types, 1 IOS, 2 Android, 3 Windows, 4 macOS, 5 Linux
         :return: type list
         """
-        url = f'/public/v1/removeDevices'
-        payload = {"companyId": companyID,
-                   "udids": udids,
-                   "osType": osType
-                   }
+        url = f"/public/v1/removeDevices"
+        payload = {"companyId": companyID, "udids": udids, "osType": osType}
         response = self.hp_http.post_call(url=url, headers=self.header, payload=payload)
         return response.json()
 
     def force_remove_devices(self, companyID, udids=[], osType=0):
         """
         Force Remove, has the same effect as Remove, though it additionally moves the device straight to Removed and also
         signals the cloud to invalidate the user’s session.
         API currently can remove up to 30 devices per call
         :param companyID: type int. ORG ID
         :param udids: type list. List of user devices ids
         :param osType: 0 ALL OS types, 1 IOS, 2 Android, 3 Windows, 4 macOS, 5 Linux
         :return: type list
         """
-        url = f'/public/v1/forceRemoveDevices'
-        payload = {"companyId": companyID,
-                   "udids": udids,
-                   "osType": osType
-                   }
+        url = f"/public/v1/forceRemoveDevices"
+        payload = {"companyId": companyID, "udids": udids, "osType": osType}
         response = self.hp_http.post_call(url=url, headers=self.header, payload=payload)
         return response.json()
+
+    def downloadServiceStatus(self, companyID):
+        """
+        Method to download Service Status
+        """
+        url = "/public/v1/downloadServiceStatus"
+        response = self.hp_http.get_call(url=url, params=companyID, headers=self.header)
+        return response.content
```

### Comparing `zscaler_api_talkers-4.0.2/zia_talker/zia_portaltalker.py` & `zscaler_api_talkers-4.1.0/zscaler_api_talkers/zia_talker/zia_portaltalker.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,30 +1,31 @@
-from zscaler_helpers.http_calls import HttpCalls
 import time
 from getpass import getpass
 
+from zscaler_helpers import HttpCalls
+
 
 class ZiaPortalTalker(object):
     """
     ZIA Portal API talker
     Documentation: https://help.zscaler.com/zia/zia-api/api-developer-reference-guide
     """
 
     def __init__(self, cloud_name):
         """
         Method to start the class
         :param cloud_name: type string. Example: zscalerbeta.net, zscalerone.net, zscalertwo.net
         zscalerthree.net, zscaler.net, zscloud.net
         """
-        self.base_uri = f'https://admin.{cloud_name}/zsapi/v1'
+        self.base_uri = f"https://admin.{cloud_name}/zsapi/v1"
         self.hp_http = HttpCalls(host=self.base_uri, verify=True)
         self.jsessionid = None
         self.zs_session_code = None
         self.headers = None
-        self.version = '0.1'
+        self.version = "0.1"
 
     def _obfuscateApiKey(self, seed):
         """
         Internal method to Obfuscate the API key
         :param seed: API key
         :return: timestamp,obfuscated key
         """
@@ -34,327 +35,457 @@
         key = ""
         for i in range(0, len(str(n)), 1):
             key += seed[int(str(n)[i])]
         for j in range(0, len(str(r)), 1):
             key += seed[int(str(r)[j]) + 2]
         return now, key
 
-    def authenticate(self, apikey, username, password=None, ):
+    def authenticate(
+        self,
+        apikey,
+        username,
+        password=None,
+    ):
         """
         Method to authenticate.
         :param apikey: API key
         :param username: A string that contains the email ID of the API admin
         :param password: A string that contains the password for the API admin
         :return:  JSESSIONID. This cookie expires by default 30 minutes from last request
         """
         if not password:
             password = getpass(" Introduce password: ")
-        timestamp, key = self._obfuscateApiKey('jj7tg80fEGao')
+        timestamp, key = self._obfuscateApiKey("jj7tg80fEGao")
 
         payload = {
             "apiKey": key,
             "username": username,
             "password": password,
-            "timestamp": timestamp
+            "timestamp": timestamp,
         }
-        url = '/authenticatedSession'
-        response = self.hp_http.post_call(url=url, payload=payload, headers={"Accept": "application/json"})
-        if response.cookies.get('JSESSIONID'):
-            self.jsessionid = response.cookies['JSESSIONID']
+        url = "/authenticatedSession"
+        response = self.hp_http.post_call(
+            url=url, payload=payload, headers={"Accept": "application/json"}
+        )
+        if response.cookies.get("JSESSIONID"):
+            self.jsessionid = response.cookies["JSESSIONID"]
         else:
             raise ValueError("Invalid Credentials")
-        if response.cookies.get('ZS_SESSION_CODE'):
-            self.zs_session_code = response.cookies['ZS_SESSION_CODE']
-            self.headers = {'Content-Type': 'application/json', 'ZS_CUSTOM_CODE': self.zs_session_code}
+        if response.cookies.get("ZS_SESSION_CODE"):
+            self.zs_session_code = response.cookies["ZS_SESSION_CODE"]
+            self.headers = {
+                "Content-Type": "application/json",
+                "ZS_CUSTOM_CODE": self.zs_session_code,
+            }
         else:
             raise ValueError("Invalid API key")
 
-    def add_dlpEngine(self, payload=None, EngineExpression=None, Name=None, CustomDlpEngine=True,
-                      PredefinedEngineName=None, Description=None):
+    def add_dlpEngine(
+        self,
+        payload=None,
+        EngineExpression=None,
+        Name=None,
+        CustomDlpEngine=True,
+        PredefinedEngineName=None,
+        Description=None,
+    ):
         """
         Method to create a DLP engine
         :param Name: type string. Name of the DLP ENGINE
         :param EngineExpression: type string. Engine Expression
         :param CustomDlpEngine: : type boolean. True if custom DLP engine
         :param PredefinedEngineName: type boolean.
         :param Description: type string. Description
         :return:
         """
-        url = '/dlpEngines'
+        url = "/dlpEngines"
         if payload:
             payload = payload
         else:
             payload = {
                 "EngineExpression": EngineExpression,
-                "CustomDlpEngine": CustomDlpEngine
+                "CustomDlpEngine": CustomDlpEngine,
             }
             if PredefinedEngineName:
                 payload.update(PredefinedEngineName=PredefinedEngineName)
             else:
                 payload.update(Name=Name)
 
             if Description:
                 payload.update(Description=Description)
-        response = self.hp_http.post_call(url=url, payload=payload, headers=self.headers,
-                                          cookies={'JSESSIONID': self.jsessionid,
-                                                   'ZS_SESSION_CODE': self.zs_session_code,
-                                                   })
+        response = self.hp_http.post_call(
+            url=url,
+            payload=payload,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response
 
     def update_dlpEngine(self, payload, id):
         """
         Method to update a DLP engine
         :param payload: type json. payload
         :return:
         """
-        url = f'/dlpEngines/{id}'
-        response = self.hp_http.put_call(url=url, payload=payload, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/dlpEngines/{id}"
+        response = self.hp_http.put_call(
+            url=url,
+            payload=payload,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response
 
     def list_PacFiles(self):
         """
         Method to list PAC files
         :return: json
         """
-        url = f'/pacFiles'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
-        return response.json()
-
-    def add_PacFile(self, name, description, domain, PacContent, editable=True, pacUrlObfuscated=True):
+        url = f"/pacFiles"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
+        return response.json()
+
+    def add_PacFile(
+        self,
+        name,
+        description,
+        domain,
+        PacContent,
+        editable=True,
+        pacUrlObfuscated=True,
+    ):
         """
         Method to Add a PAC file
         :param name: type string. Name of the PAC
         :param description: type string. Description
         :param domain: type string. Domain
         :param PacContent: Type string: PAC content
         :param editable: Type boolean. Default True
         :param pacUrlObfuscated: Type boolean. Default True
         :return:
         """
         payload = {
-            'name': name,
-            'editable': editable,
-            'pacContent': PacContent,
-            'pacUrlObfuscated': pacUrlObfuscated,
-            'domain': domain,
-            'description': description,
-            'pacVerificationStatus': 'VERIFY_NOERR'
+            "name": name,
+            "editable": editable,
+            "pacContent": PacContent,
+            "pacUrlObfuscated": pacUrlObfuscated,
+            "domain": domain,
+            "description": description,
+            "pacVerificationStatus": "VERIFY_NOERR",
         }
-        url = f'/pacFiles'
-        response = self.hp_http.post_call(url=url, headers=self.headers, payload=payload,
-                                          cookies={'JSESSIONID': self.jsessionid,
-                                                   'ZS_SESSION_CODE': self.zs_session_code,
-                                                   })
+        url = f"/pacFiles"
+        response = self.hp_http.post_call(
+            url=url,
+            headers=self.headers,
+            payload=payload,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_malwarePolicy(self):
         """
         Method to list Malware Policy.  Policy > Malware Protection > Malware Policy
         :return: json
         """
-        url = f'/malwarePolicy'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/malwarePolicy"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_virusSpywareSettings(self):
         """
         Method to list virus, malware, adware and spyware settings.  Policy > Malware Protection > Malware Policy
         :return: json
         """
-        url = f'/virusSpywareSettings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/virusSpywareSettings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_advancedUrlFilteringSettings(self):
         """
         Method to list Advanced Policy settings.  Policy > URL & Cloud App Control > Advanced  Policy Settings
         :return: json
         """
-        url = f'/advancedUrlFilterAndCloudAppSettings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/advancedUrlFilterAndCloudAppSettings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_subscriptions(self):
         """
         Method to list tenant subscriptions.  Administration > Company Profile > Subscriptions
         :return: json
         """
-        url = f'/subscriptions'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/subscriptions"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_cyberRiskScore(self):
         """
         Method to list tenant subscriptions.  Administration > Company Profile > Subscriptions
         :return: json
         """
-        url = f'/cyberRiskScore'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/cyberRiskScore"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def add_user_groups(self, group_name):
         """
         Creates user groups
         :return:
         :rtype:
         """
-        url = '/groups'
-        payload = {'name': group_name}
-        response = self.hp_http.post_call(url=url, headers=self.headers, payload=payload,
-                                          cookies={'JSESSIONID': self.jsessionid,
-                                                   'ZS_SESSION_CODE': self.zs_session_code,
-                                                   })
+        url = "/groups"
+        payload = {"name": group_name}
+        response = self.hp_http.post_call(
+            url=url,
+            headers=self.headers,
+            payload=payload,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_samlSettings(self):
         """
         Method to list SAML settings.  Administration > Authentication Settings
         """
-        url = f'/samlSettings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/samlSettings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_advancedSettings(self):
         """
         Method to list ZIA advanced settings.  Administration > Advanced Settings
         :return: json
         """
-        url = f'/advancedSettings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/advancedSettings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_idpConfig(self):
         """
         Method to list ZIA idp configuration.  Administration > Authentication Settings > identity Providers
         :return: json
         """
-        url = f'/idpConfig'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/idpConfig"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_icapServers(self):
         """
         Method to list ZIA icap servers.  Administration > DLP iincident Receiver > ICAP Settings
         :return: json
         """
-        url = f'/icapServers'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/icapServers"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_authSettings(self):
         """
         Method to list ZIA auth settings.  Administration > Authentication Settings
         :return: json
         """
-        url = f'/authSettings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/authSettings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_samlAdminSettings(self):
         """
         Method to list ZIA auth settings.  Administration > Authentication Settings
         :return: json
         """
-        url = f'/samlAdminSettings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/samlAdminSettings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_eun(self):
         """
         Method to list ZIA End User Notification settings.  Administration > End User Notifications
         :return: json
         """
-        url = f'/eun'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/eun"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_admin_password_mgt(self):
         """
         Method to list ZIA Administrator Management password.  Administration > Administration Management
         :return: json
         """
-        url = f'/passwordExpiry/settings'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/passwordExpiry/settings"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def list_apiKeys(self):
         """
         Method to list ZIA Administrator Management password.  Administration > Administration Management
         :return: json
         """
-        url = f'/apiKeys'
-        response = self.hp_http.get_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/apiKeys"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response.json()
 
     def delete_group(self, groupid):
         """
         Method to delete a group given group id
         :param groupid: type int. Group id
         :return: HTTP response
         """
-        url = f'/groups/{groupid}'
-        response = self.hp_http.delete_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
+        url = f"/groups/{groupid}"
+        response = self.hp_http.delete_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
         return response
 
     def delete_department(self, departmentid):
         """
         Method to delete a group given department
         :param departmentid: type int. Departmentid id
         :return: HTTP response
         """
-        url = f'/departments/{departmentid}'
-        response = self.hp_http.delete_call(url=url, headers=self.headers,
-                                         cookies={'JSESSIONID': self.jsessionid,
-                                                  'ZS_SESSION_CODE': self.zs_session_code,
-                                                  })
-        return response
+        url = f"/departments/{departmentid}"
+        response = self.hp_http.delete_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
+        return response
+
+    def list_webApplicationRules(self):
+        """
+        Method to list Cloud APP policies
+        :return:
+        :rtype:
+        """
+        url = "/webApplicationRules"
+        response = self.hp_http.get_call(
+            url=url,
+            headers=self.headers,
+            cookies={
+                "JSESSIONID": self.jsessionid,
+                "ZS_SESSION_CODE": self.zs_session_code,
+            },
+        )
+        return response.json()
```

### Comparing `zscaler_api_talkers-4.0.2/zia_talker/zia_talker.py` & `zscaler_api_talkers-4.1.0/zscaler_api_talkers/zia_talker/zia_talker.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,209 +1,258 @@
-import pdb
-
-from zscaler_helpers.http_calls import HttpCalls
+import pdb  # noqa
 import time
 from getpass import getpass
-from models.models import valid_category_ids
-from models.models import super_categories
-from models.models import valid_countries
+
+from models.models import super_categories, valid_category_ids, valid_countries
+from zscaler_helpers import HttpCalls
 
 
 class ZiaTalker(object):
     """
     ZIA API talker
-    Documentation: https://help.zscaler.com/zia/zia-api/api-developer-reference-guide
+    Documentation:
+    https://help.zscaler.com/zia/zia-api/api-developer-reference-guide
     """
 
     def __init__(self, cloud_name, bearer=None):
         """
         Method to start the class
-        :param cloud_name: type string. Example: zscalerbeta.net, zscalerone.net, zscalertwo.net,
+        :param cloud_name: type string. Example: zscalerbeta.net
+        zscalerone.net, zscalertwo.net,
         zscalerthree.net, zscaler.net, zscloud.net
         :param bearer: Type string. OAuth2.0 Bear token
         """
-        self.base_uri = f'https://zsapi.{cloud_name}/api/v1'
+        self.base_uri = f"https://zsapi.{cloud_name}/api/v1"
         self.hp_http = HttpCalls(host=self.base_uri, verify=True)
         self.cookies = None
         if bearer:
-            self.headers = {'Authorization': f'Bearer {bearer}'}
+            self.headers = {"Authorization": f"Bearer {bearer}"}
         else:
             self.headers = None
 
-    def _obfuscateApiKey(self, seed):
+    def _obfuscateApiKey(self, seed: str):
         """
         Internal method to Obfuscate the API key
         :param seed: API key
         :return: timestamp,obfuscated key
         """
+        seed = seed
         now = int(time.time() * 1000)
         n = str(now)[-6:]
         r = str(int(n) >> 1).zfill(6)
         key = ""
-        for i in range(0, len(str(n)), 1):
-            key += seed[int(str(n)[i])]
-        for j in range(0, len(str(r)), 1):
-            key += seed[int(str(r)[j]) + 2]
+        for digit in n:
+            key += seed[int(digit)]
+        for digit in r:
+            key += seed[int(digit) + 2]
         return now, key
 
-    def authenticate(self, apikey, username, password=None, ):
+    def authenticate(
+        self,
+        apikey: str,
+        username: str,
+        password: str = None,
+    ) -> None:
         """
         Method to authenticate.
         :param apikey: API key
         :param username: A string that contains the email ID of the API admin
         :param password: A string that contains the password for the API admin
-        :return:  JSESSIONID. This cookie expires by default 30 minutes from last request
+        :return:  JSESSIONID.
+        This cookie expires by default 30 minutes from last request
         """
         if not password:
             password = getpass(" Introduce password: ")
         timestamp, key = self._obfuscateApiKey(apikey)
 
         payload = {
             "apiKey": key,
             "username": username,
             "password": password,
-            "timestamp": timestamp
+            "timestamp": timestamp,
         }
-        url = '/authenticatedSession'
+        url = "/authenticatedSession"
         response = self.hp_http.post_call(url=url, payload=payload)
-        self.cookies = {'JSESSIONID': response.cookies['JSESSIONID']}
+        self.cookies = {"JSESSIONID": response.cookies["JSESSIONID"]}
 
     def authenticated_session(self):
         """
         Checks if there is an authenticated session
         :return: json
         """
-        url = '/authenticatedSession'
-        response = self.hp_http.get_call(url, cookies=self.cookies, error_handling=True, )
+        url = "/authenticatedSession"
+        response = self.hp_http.get_call(
+            url,
+            cookies=self.cookies,
+            error_handling=True,
+        )
         return response.json()
 
     def end_session(self):
         """
         Menthod to enf an authenticated session
         :return: None
         """
-        url = '/authenticatedSession'
-        response = self.hp_http.delete_call(url, cookies=self.cookies, error_handling=True,
-                                            payload={})
+        url = "/authenticatedSession"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, payload={}
+        )
         return response.json()
 
-    def _obtain_all(self, url):
+    def _obtain_all(self, url: str):
         """
         Internal method that queries all pages
         :param url:  URL
         :return:
         """
         page = 1
         result = []
         while True:
-            response = self.hp_http.get_call(f'{url}&page={page}', cookies=self.cookies,
-                                             error_handling=True, headers=self.headers, )
+            response = self.hp_http.get_call(
+                f"{url}&page={page}",
+                cookies=self.cookies,
+                error_handling=True,
+                headers=self.headers,
+            )
             if response.json():
                 result += response.json()
                 page += 1
                 time.sleep(1)
             else:
                 break
         return result
 
     def get_status(self):
         """
         Method to obtain the activation status for a configuration change
         :return: json object with the status
         """
-        url = '/status'
+        url = "/status"
         response = self.hp_http.get_call(url, cookies=self.cookies, error_handling=True)
         return response.json()
 
     def activate_status(self):
         """
         Method to activate configuration changes
         :return: json object with the status
         """
-        url = '/status/activate'
-        response = self.hp_http.post_call(url, payload={}, cookies=self.cookies, error_handling=True)
+        url = "/status/activate"
+        response = self.hp_http.post_call(
+            url, payload={}, cookies=self.cookies, error_handling=True
+        )
         return response.json()
 
     # Admin Audit Logs
 
-    def list_auditlogEntryReport(self):
+    def list_auditlogEntryReport(self) -> dict:
         """
-        Gets the status of a request for an audit log report. After sending a POST request to /auditlogEntryReport to
-        generate a report, you can continue to call GET /auditlogEntryReport to check whether the report has finished
-        generating. Once the status is COMPLETE, you can send another GET request to /auditlogEntryReport/download to
+        Gets the status of a request for an audit log report.
+        After sending a POST request to /auditlogEntryReport to
+        generate a report, you can continue to call GET /auditlogEntryReport
+        to check whether the report has finished
+        generating. Once the status is COMPLETE, you can send another GET
+        request to /auditlogEntryReport/download to
         download the report as a CSV file.
         :return: json
         """
 
         url = "/auditlogEntryReport"
 
-        response = self.hp_http.get_call(url, cookies=self.cookies, headers=self.headers,
-                                         error_handling=True)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, headers=self.headers, error_handling=True
+        )
         return response.json()
 
     def download_auditlogEntryReport(self):
         """
-        Gets the status of a request for an audit log report. After sending a POST request to /auditlogEntryReport to
-        generate a report, you can continue to call GET /auditlogEntryReport to check whether the report has finished
-        generating. Once the status is COMPLETE, you can send another GET request to /auditlogEntryReport/download to
+        Gets the status of a request for an audit log report. After sending a
+        POST request to /auditlogEntryReport to
+        generate a report, you can continue to call GET /auditlogEntryReport
+        to check whether the report has finished
+        generating. Once the status is COMPLETE, you can send another GET
+        request to /auditlogEntryReport/download to
         download the report as a CSV file.
         :return: json
         """
 
         url = "/auditlogEntryReport/download"
-        response = self.hp_http.get_call(url, cookies=self.cookies, headers=self.headers,
-                                         error_handling=True)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, headers=self.headers, error_handling=True
+        )
         return response
 
-    def add_auditlogEntryReport(self, startTime, endTime, actionTypes=None, category=None,
-                                subcategories=None, actionInterface=None, ):
-        """
-         Creates an audit log report for the specified time period and saves it as a CSV file. The report includes audit
-         information for every call made to the cloud service API during the specified time period.
-         Creating a new audit log report will overwrite a previously-generated report.
+    def add_auditlogEntryReport(
+        self,
+        startTime: int,
+        endTime: int,
+        actionTypes: list = None,
+        category: str = None,
+        subcategories: list = None,
+        actionInterface: str = None,
+    ):
+        """
+         Creates an audit log report for the specified time period and saves
+         it as a CSV file. The report includes audit
+         information for every call made to the cloud service API during the
+         specified time period.
+         Creating a new audit log report will overwrite a previously-generated
+         report.
         :param startTime: The timestamp, in epoch, of the admin's last login
         :param endTime: The timestamp, in epoch, of the admin's last logout.
-        :param actionTypes: type list. The action performed by the admin in the ZIA Admin Portal or API
-        :param actionResult: The outcome (i.e., Failure or Success) of an actionType.
-        :param category: tyoe string. The location in the Zscaler Admin Portal (i.e., Admin UI) where the actionType was performed
-        :param subcategories: type list. The area within a category where the actionType was performed.
-        :param actionInterface: type string. The interface (i.e., Admin UI or API) where the actionType was performed.
+        :param actionTypes: type list. The action performed by the admin in
+        the ZIA Admin Portal or API
+        :param actionResult: The outcome (i.e., Failure or Success) of an
+        actionType.
+        :param category: tyoe string. The location in the Zscaler Admin Portal
+        (i.e., Admin UI) where the actionType was performed
+        :param subcategories: type list. The area within a category where the
+        actionType was performed.
+        :param actionInterface: type string. The interface
+        (i.e., Admin UI or API) where the actionType was performed.
         :param clientIP: type string. The source IP address for the admin
         :param adminName: type string.  The admin's login ID
         :return: 204 Successfull Operation
         """
         url = "/auditlogEntryReport"
-        payload = {"startTime": startTime,
-                   "endTime": endTime,
-                   }
+        payload = {
+            "startTime": startTime,
+            "endTime": endTime,
+        }
         if category:
             payload.update(category=category)
         if subcategories:
             payload.update(subcategories=subcategories)
         if actionInterface:
             payload.update(actionInterface=actionInterface)
         if actionTypes:
             payload.update(actionTypes=actionTypes)
 
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response
 
     # Admin & Role Management
     def list_adminUsers(self, userId=None, query=None):
         """
-        Gets a list of admin users. By default, auditor user information is not included.
+        Gets a list of admin users. By default, auditor user
+        information is not included.
         :param userId: user ID
         :param query: HTTP query
         :return:json()
         """
         if userId:
-            url = f'/adminUsers/{userId}'
-            return self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers).json()
+            url = f"/adminUsers/{userId}"
+            return self.hp_http.get_call(
+                url, cookies=self.cookies, error_handling=True, headers=self.headers
+            ).json()
         else:
             if query:
                 url = f"/adminUsers?{query}?pageSize=1000"
             else:
                 url = "/adminUsers?pageSize=1000"
         return self._obtain_all(url)
 
@@ -213,290 +262,393 @@
         :param query: HTTP query
         :return: json
         """
         if query:
             url = f"/adminRoles/lite?{query}"
         else:
             url = "/adminRoles/lite"
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     # URL Categories
     def list_url_categories(self, custom=False):
         """
         Gets information about all or custom URL categories
         :param custom: Boolean, if True it will return custom categories only
         :return: json
         """
 
         if custom:
-            url = '/urlCategories?customOnly=true'
+            url = "/urlCategories?customOnly=true"
         else:
-            url = '/urlCategories'
+            url = "/urlCategories"
         # return self._obtain_all(url)
-        response = self.hp_http.get_call(url, cookies=self.cookies, error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_url_categories_lite(self):
         """
         Gets a lightweight key-value list of all or custom URL categories.
         """
-        url = '/urlCategories/lite'
-        response = self.hp_http.get_call(url, cookies=self.cookies, error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_url_categories(self, name, superCategory, type='URL_CATEGORY', urls=None, dbCategorizedUrls=None,
-                           keywordsRetainingParentCategory=[], keywords=[], customCategory=False, ipRanges=[],
-                           ipRangesRetainingParentCategory=[]):
+        url = "/urlCategories/lite"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_url_categories(
+        self,
+        name,
+        superCategory,
+        type="URL_CATEGORY",
+        urls=None,
+        dbCategorizedUrls=None,
+        keywordsRetainingParentCategory=[],
+        keywords=[],
+        customCategory=False,
+        ipRanges=[],
+        ipRangesRetainingParentCategory=[],
+    ):
         """
          Adds a new custom URL category.
-        :param name: type string. Name of the custom category. Possible values URL_CATEGORY, TLD_CATEGORY, ALL
+        :param name: type string. Name of the custom category. Possible values
+        URL_CATEGORY, TLD_CATEGORY, ALL
         :param superCategory: type string. super category
         :param urls: type list. List of urls
         :param dbCategorizedUrls: type list. URL retaining parent category
-        :param keywordsRetainingParentCategory: type list. Retained custom keywords from the parent URL category that is associated to a URL category.
-        :param keywords: type list. Custom keywords associated to a URL category.
-        :param customCategory: type boolean. Default False. Set to True for custom category
-        :param ipRanges: type list. Custom IP address ranges associated to a URL category
-        :param ipRangesRetainingParentCategory: The retaining parent custom IP address ranges associated to a URL category.
+        :param keywordsRetainingParentCategory: type list. Retained custom
+        keywords from the parent URL category that is associated to a
+        URL category.
+        :param keywords: type list. Custom keywords associated to a
+        URL category.
+        :param customCategory: type boolean. Default False. Set to True for
+        custom category
+        :param ipRanges: type list. Custom IP address ranges associated to a
+        URL category
+        :param ipRangesRetainingParentCategory: The retaining parent custom IP
+        address ranges associated to a URL category.
 
         :return:  json
         """
         if keywordsRetainingParentCategory is None:
             keywordsRetainingParentCategory = []
 
         if superCategory not in super_categories:
-            print(f'Error -> Invalid Super Category')
-            print(f'{super_categories}')
+            print("Error -> Invalid Super Category")
+            print(f"{super_categories}")
             raise ValueError("Invalid super category")
 
-        url = '/urlCategories'
+        url = "/urlCategories"
         payload = {
             "configuredName": name,
             "customCategory": customCategory,
             "superCategory": superCategory,
             "keywordsRetainingParentCategory": keywordsRetainingParentCategory,
             "keywords": keywords,
             "urls": urls,
             "dbCategorizedUrls": dbCategorizedUrls,
             "ipRanges": ipRanges,
             "ipRangesRetainingParentCategory": ipRangesRetainingParentCategory,
-            "type": type
+            "type": type,
         }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def add_url_categories1(self, payload):
         """
          Adds a new custom URL category.
         :param payload
         :return:  json
         """
-        url = '/urlCategories'
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
-        return response.json()
-
-    def update_url_categories(self, categoryId, action=None, configuredName=None, urls=None, dbCategorizedUrls=None,
-                              keywords=None, keywordsRetainingParentCategory=None, ):
-        """
-         Updates the URL category for the specified ID. If keywords are included within the request, then they
-         will replace existing ones for the specified URL category . If the keywords attribute is not included the
+        url = "/urlCategories"
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
+        return response.json()
+
+    def update_url_categories(
+        self,
+        categoryId,
+        action=None,
+        configuredName=None,
+        urls=None,
+        dbCategorizedUrls=None,
+        keywords=None,
+        keywordsRetainingParentCategory=None,
+    ):
+        """
+         Updates the URL category for the specified ID. If keywords are
+         included within the request, then they
+         will replace existing ones for the specified URL category . If the
+         keywords attribute is not included the
          request, the existing keywords are retained.
-         You can perform a full update for the specified URL category. However, if attributes are omitted within the
+         You can perform a full update for the specified URL category. However
+         if attributes are omitted within the
           update request, the values for those attributes are cleared.
 
-         You can also perform an incremental update, to add or remove URLs, for the specified URL category using the
+         You can also perform an incremental update, to add or remove URLs
+         for the specified URL category using the
          action parameter
         :param categoryId: type string. URL id
         :param configuredName: type string. Name of the custom category
         :param urls: list of urls
         :param dbCategorizedUrls: type list. URL retaining parent category
         :param keywordsRetainingParentCategory: list of key works
         :param action: Optional parameter. ADD_TO_LIST or REMOVE_FROM_LIST
         :return:  json
         """
-        '''if categoryId not in valid_category_ids:
+        """if categoryId not in valid_category_ids:
             print(f'Error -> Invalid category id')
-            raise ValueError("Invalid category id")'''
+            raise ValueError("Invalid category id")"""
 
-        if action == 'ADD_TO_LIST':
-            url = f'/urlCategories/{categoryId}?action=ADD_TO_LIST'
-        elif action == 'REMOVE_FROM_LIST':
-            url = f'/urlCategories/{categoryId}?action=REMOVE_FROM_LIST'
+        if action == "ADD_TO_LIST":
+            url = f"/urlCategories/{categoryId}?action=ADD_TO_LIST"
+        elif action == "REMOVE_FROM_LIST":
+            url = f"/urlCategories/{categoryId}?action=REMOVE_FROM_LIST"
         elif not action:
-            url = f'/urlCategories/{categoryId}'
+            url = f"/urlCategories/{categoryId}"
         else:
-            print(f'Error -> Invalid action')
-            print(f'{action}')
+            print("Error -> Invalid action")
+            print(f"{action}")
             raise ValueError("Invalid action")
 
         payload = {
             "configuredName": configuredName,
-
         }
         if keywordsRetainingParentCategory:
-            payload.update(keywordsRetainingParentCategory=keywordsRetainingParentCategory)
+            payload.update(
+                keywordsRetainingParentCategory=keywordsRetainingParentCategory
+            )
         if keywords:
             payload.update(keywords=keywords)
         if configuredName:
             payload.update(configuredName=configuredName)
         if urls:
             payload.update(urls=urls)
         if dbCategorizedUrls:
             payload.update(dbCategorizedUrls=dbCategorizedUrls)
 
-        response = self.hp_http.put_call(url, payload=payload, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.put_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_url_categories(self, categoryid):
         """
         Deletes the custom URL category for the specified ID.
-        You cannot delete a custom category while it is being used by a URL policy or NSS feed. Also, predefined
+        You cannot delete a custom category while it is being used by
+        a URL policy or NSS feed. Also, predefined
         categories cannot be deleted.
         :param categoryid: Category ID
         :return: json response
         """
-        url = f'/urlCategories/{categoryid}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        url = f"/urlCategories/{categoryid}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response
 
     def delete_urlFilteringRules(self, ruleId):
         """
         Deletes the custom URL category for the specified ID.
-        You cannot delete a custom category while it is being used by a URL policy or NSS feed. Also, predefined
+        You cannot delete a custom category while it is being used by a URL
+        policy or NSS feed. Also, predefined
         categories cannot be deleted.
         :param ruleId:  type int. Rule Id
         :return: json response
         """
-        url = f'/urlFilteringRules/{ruleId}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        url = f"/urlFilteringRules/{ruleId}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response
 
     def list_url_categories_urlquota(self):
         """
-        Gets information on the number of unique URLs that are currently provisioned for your organization as well as
+        Gets information on the number of unique URLs that are currently
+        provisioned for your organization as well as
         how many URLs you can add before reaching that number.
         :return: json
         """
-        url = '/urlCategories/urlQuota'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/urlCategories/urlQuota"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         print(response.json())
         return response.json()
 
     def list_url_categories_id(self, category_id):
         """
         Gets the URL category information for the specified ID
         :param category_id:
         :return:
         """
 
         url = f"/urlCategories/{category_id}"
 
         if category_id not in valid_category_ids:
-            print(f'Error -> Invalid Category ID')
-            print(f'{valid_category_ids}')
+            print("Error -> Invalid Category ID")
+            print(f"{valid_category_ids}")
             raise ValueError("Invalid Category ID")
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def url_lookup(self, url_list):
         """
-        Method to look up the categorization of the given list of URLs, ["abc.com","zyz.com"]
+        Method to look up the categorization of the
+        given list of URLs, ["abc.com","zyz.com"]
         :param url_list: list of urls
         :return:  json
         """
         result = []
-        url = '/urlLookup'
+        url = "/urlLookup"
         # Verify urls format
         list(set(url_list))
         # Rate limit 1/sec  and 400 hr and 100 URLs per call
-        list_of_lists = [url_list[i:i + 100] for i in range(0, len(url_list), 100)]
+        list_of_lists = [url_list[i : i + 100] for i in range(0, len(url_list), 100)]
         for item in list_of_lists:
-            response = self.hp_http.post_call(url, payload=item, cookies=self.cookies,
-                                              headers=self.headers,
-                                              error_handling=True)
+            response = self.hp_http.post_call(
+                url,
+                payload=item,
+                cookies=self.cookies,
+                headers=self.headers,
+                error_handling=True,
+            )
             result.append(response.json())
             time.sleep(1)
         final_result = []
         for i in result:
             for j in i:
                 final_result.append(j)
         return final_result
 
     # URL filtering Policies
-    def list_url_filtering_rules(self, ):
+    def list_url_filtering_rules(
+        self,
+    ):
         """
         Gets a list of all of URL Filtering Policy rules
         :return:
         """
-        url = '/urlFilteringRules'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_url_filtering_rules(self, name, order, protocols, state,
-                                action, urlcategories=[], requestMethods=None, description=None, groups=None,
-                                locations=None, departments=None, users=None, rank=7, locationGroups=None,
-                                enforceTimeValidity=False,
-                                validityEndTime=None, validityStartTime=None, validityTimeZoneId=None, cbiProfileId=0,
-                                blockOverride=False):
+        url = "/urlFilteringRules"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_url_filtering_rules(
+        self,
+        name,
+        order,
+        protocols,
+        state,
+        action,
+        urlcategories=[],
+        requestMethods=None,
+        description=None,
+        groups=None,
+        locations=None,
+        departments=None,
+        users=None,
+        rank=7,
+        locationGroups=None,
+        enforceTimeValidity=False,
+        validityEndTime=None,
+        validityStartTime=None,
+        validityTimeZoneId=None,
+        cbiProfileId=0,
+        blockOverride=False,
+    ):
         """
          Adds a URL Filtering Policy rule.
-         If you are using the Admin Rank feature, refer to About Admin Rank to determine which value to provide for rank
-         when adding a policy rule. If you are not using Admin Rank, the rank value must be 7.
+         If you are using the Admin Rank feature, refer to About Admin Rank
+         to determine which value to provide for rank
+         when adding a policy rule. If you are not using Admin Rank, the
+         rank value must be 7.
         :param name: type string.  Name of the rule
         :param order: type integer. Rule order
-        :param protocols: type string. Possible values SMRULEF_ZPA_BROKERS_RULE, ANY_RULE, TCP_RULE, UDP_RULE, DOHTTPS_RULE, TUNNELSSL_RULE,
-        HTTP_PROXY, FOHTTP_RULE, FTP_RULE, HTTPS_RULE, HTTP_RULE, SSL_RULE, TUNNEL_RULE
-        :param locations: type list. Each element is a  dictionary: Name-ID pairs of locations for which rule must be applied
-        :param groups: type list. Name-ID pairs of groups for which rule must be applied
-        :param departments:type list. Name-ID pairs of departments for which rule will be applied
-        :param users: type list. Name-ID pairs of users for which rule must be applied
-        :param urlcategories: type list. List of URL categories for which rule must be applied
+        :param protocols: type string. Possible values
+        SMRULEF_ZPA_BROKERS_RULE, ANY_RULE, TCP_RULE, UDP_RULE, DOHTTPS_RULE,
+        TUNNELSSL_RULE,
+        HTTP_PROXY, FOHTTP_RULE, FTP_RULE, HTTPS_RULE, HTTP_RULE,
+        SSL_RULE, TUNNEL_RULE
+        :param locations: type list. Each element is a  dictionary:
+        Name-ID pairs of locations for which rule must be applied
+        :param groups: type list. Name-ID pairs of groups for which
+        rule must be applied
+        :param departments:type list. Name-ID pairs of departments
+        for which rule will be applied
+        :param users: type list. Name-ID pairs of users for which rule must
+        be applied
+        :param urlcategories: type list. List of URL categories for which rule
+        must be applied
         :param admin_rack:Admin rank of the admin who creates this rule
-        :param timewindows: type list. Name-ID pairs of time interval during which rule must be enforced.
-        :param requestmethods: type list. Request method for which the rule must be applied. If not set, rule will be applied to all
+        :param timewindows: type list. Name-ID pairs of time interval
+        during which rule must be enforced.
+        :param requestmethods: type list. Request method for which the rule
+        must be applied. If not set, rule will be applied to all
          methods
-        :param endUserNotificationUrl: type string. URL of end user notification page to be displayed when the rule is matched. Not applicable if either
+        :param endUserNotificationUrl: type string. URL of end user
+        notification page to be displayed when the rule is matched. Not
+        applicable if either
         'overrideUsers' or 'overrideGroups' is specified.
-        :param overrideusers: Name-ID pairs of users for which this rule can be overridden. Applicable only if
-         blockOverride is set to 'true', action is 'BLOCK' and overrideGroups is not set.If this overrideUsers is not
+        :param overrideusers: Name-ID pairs of users for which this rule can
+        be overridden. Applicable only if
+         blockOverride is set to 'true', action is 'BLOCK' and overrideGroups
+         is not set.If this overrideUsers is not
          set, 'BLOCK' action can be overridden for any user.
-        :param overridegroups: Name-ID pairs of groups for which this rule can be overridden. Applicable only if
-        blockOverride is set to 'true' and action is 'BLOCK'. If this overrideGroups is not set, 'BLOCK' action can be
+        :param overridegroups: Name-ID pairs of groups for which this
+        rule can be overridden. Applicable only if
+        blockOverride is set to 'true' and action is 'BLOCK'. If this
+        overrideGroups is not set, 'BLOCK' action can be
         overridden for any group
-        :param blockOverride: boolean: When set to true, a 'BLOCK' action triggered by the rule could be overridden.
-        If true and both overrideGroup and overrideUsers are not set, the BLOCK triggered by this rule could be
-        overridden for any users. If blockOverride is not set, 'BLOCK' action cannot be overridden.
+        :param blockOverride: boolean: When set to true, a 'BLOCK' action
+        triggered by the rule could be overridden.
+        If true and both overrideGroup and overrideUsers are not set, the
+        BLOCK triggered by this rule could be
+        overridden for any users. If blockOverride is not set, 'BLOCK'
+        action cannot be overridden.
         :param description: Additional information about the URL Filtering rule
         :param state: enabled/disabled
         :param action: Allow, Caution, Block
         :return:
         """
-        url = '/urlFilteringRules'
+        url = "/urlFilteringRules"
         payload = {
             "blockOverride": blockOverride,
             "cbiProfileId": cbiProfileId,
             "description": description,
             "enforceTimeValidity": enforceTimeValidity,
             "name": name,
             "order": order,
             "protocols": protocols,
             "urlCategories": urlcategories,
             "state": state,
             "rank": rank,
-            "action": action
+            "action": action,
         }
         if locations:
             payload.update(locations=locations)
         if locationGroups:
             payload.update(locationGroups=locationGroups)
         if groups:
             payload.update(groups=groups)
@@ -509,531 +661,686 @@
         if enforceTimeValidity:
             payload.update(validityStartTime=validityStartTime)
             payload.update(validityEndTime=validityEndTime)
             payload.update(validityTimeZoneId=validityTimeZoneId)
 
         print(payload)
 
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     # User Management
 
     def list_departments(self, department_id=""):
         """
-        Gets a list of departments. The search parameters find matching values within the "name" or "comments"
+        Gets a list of departments. The search parameters find matching values
+        within the "name" or "comments"
         attributes.
         if ID, gets the department for the specified ID
         :param department_id: department ID
         :return:json()
         """
 
         if department_id:
             url = "/departments"
         else:
-            url = f'/departments/{department_id}'
+            url = f"/departments/{department_id}"
 
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_groups(self, group_id=None):
         """
         Gets a list of groups
         if ID, gets the group for the specified ID
         :param group_id: group ID
         :return:json()
         """
         if not group_id:
             url = "/groups?pageSize=10000"
             return self._obtain_all(url)
         else:
-            url = f'/groups/{group_id}'
-            response = self.hp_http.get_call(url, cookies=self.cookies,
-                                             error_handling=True, headers=self.headers)
+            url = f"/groups/{group_id}"
+            response = self.hp_http.get_call(
+                url, cookies=self.cookies, error_handling=True, headers=self.headers
+            )
 
         return response.json()
 
     def list_users(self, user_id=None, query=None):
         """
-        Gets a list of all users and allows user filtering by name, department, or group.
-        The name search parameter performs a partial match. The dept and group parameters perform a 'starts with' match.
+        Gets a list of all users and allows user filtering
+        by name, department, or group.
+        The name search parameter performs a partial match. The dept and group
+        parameters perform a 'starts with' match.
         if ID, gets user information for the specified ID
         :param user_id: user ID
         :return:json()
         """
         if user_id:
-            url = f'/users/{user_id}'
-            return self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers).json()
+            url = f"/users/{user_id}"
+            return self.hp_http.get_call(
+                url, cookies=self.cookies, error_handling=True, headers=self.headers
+            ).json()
         else:
             if query:
                 url = f"/users?{query}&pageSize=1000"
-                return self.hp_http.get_call(url, cookies=self.cookies,
-                                             error_handling=True, headers=self.headers).json()
+                return self.hp_http.get_call(
+                    url, cookies=self.cookies, error_handling=True, headers=self.headers
+                ).json()
             else:
                 url = "/users?pageSize=1000"
         return self._obtain_all(url)
 
-    def add_users(self, name, email, groups, department, comments, password, adminuser=False, ):
+    def add_users(
+        self,
+        name,
+        email,
+        groups,
+        department,
+        comments,
+        password,
+        adminuser=False,
+    ):
         """
-        Adds a new user. A user can belong to multiple groups, but can only belong to one department.
+        Adds a new user. A user can belong to multiple groups,
+        but can only belong to one department.
 
         :param name: string, user name
         :param email: string user email address
-        :param groups: list. each member is a dictionary, key id, value name [{"id":1234, "name":"guest-wifi"}]
-        :param department: dictionary, key is the id and value is the name {"id":1234, "name":"guests"}
+        :param groups: list. each member is a dictionary, key id, value name
+        [{"id":1234, "name":"guest-wifi"}]
+        :param department: dictionary, key is the id and value is the name
+        {"id":1234, "name":"guests"}
         :param comments: string, comments
         :param password: string password,
         :param adminuser: True if user is admin user. default False
         :return: Json
         """
-        url = '/users'
-        payload = {"name": name,
-                   "email": email,
-                   "groups": groups,
-                   "department": department,
-                   "comments": comments,
-                   "password": password,
-                   "adminUser": adminuser}
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        url = "/users"
+        payload = {
+            "name": name,
+            "email": email,
+            "groups": groups,
+            "department": department,
+            "comments": comments,
+            "password": password,
+            "adminUser": adminuser,
+        }
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_bulk_users(self, user_ids):
         """
-        Bulk delete users up to a maximum of 500 users per request. The response returns the user IDs that were
+        Bulk delete users up to a maximum of 500 users per request.
+        The response returns the user IDs that were
         successfully deleted.
         :param user_ids:  List of user IDS to be deleted
         """
-        url = '/users/bulkDelete'
+        url = "/users/bulkDelete"
         if len(user_ids) < 500:
-            payload = {
-                "ids": user_ids
-            }
-            response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                              error_handling=True, headers=self.headers)
+            payload = {"ids": user_ids}
+            response = self.hp_http.post_call(
+                url,
+                payload=payload,
+                cookies=self.cookies,
+                error_handling=True,
+                headers=self.headers,
+            )
             return response.json()
         else:
             raise ValueError("Maximum 500 users per request")
 
     # Location Management
 
     def list_locations(self, locationId=None):
         """
-        Gets locations only, not sub-locations. When a location matches the given search parameter criteria only its
+        Gets locations only, not sub-locations. When a location matches
+        the given search parameter criteria only its
         parent location is included in the result set, not its sub-locations.
         :param locationId: Location id
         """
         if locationId:
-            url = f'/locations/{locationId}'
+            url = f"/locations/{locationId}"
         else:
-            url = f'/locations'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/locations"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_sublocations(self, locationId):
         """
-        Gets the sub-location information for the location with the specified ID
+        Gets the sub-location information
+        for the location with the specified ID
         :param locationId: Location id
         """
         if locationId:
-            url = f'/locations/{locationId}/sublocations'
+            url = f"/locations/{locationId}/sublocations"
         else:
-            url = f'/locations'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/locations"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
-    def list_locationsgroups(self, ):
+    def list_locationsgroups(
+        self,
+    ):
         """
         Gets information on location groups
         :param locationgroupId: Location group id
         """
-        url = f'/locations/groups'
+        url = "/locations/groups"
         print(url)
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def delete_bulk_locations(self, locationIds):
         """
-        Bulk delete locations up to a maximum of 100 users per request. The response returns the location IDs that were successfully deleted..
+        Bulk delete locations up to a maximum of 100 users per request.
+        The response returns the location IDs that were successfully deleted.
         :param locationIds: list of location IDs
         """
-        url = '/locations/bulkDelete'
+        url = "/locations/bulkDelete"
         if len(locationIds) < 100:
-            payload = {
-                "ids": locationIds
-            }
-            response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                              error_handling=True, headers=self.headers)
+            payload = {"ids": locationIds}
+            response = self.hp_http.post_call(
+                url,
+                payload=payload,
+                cookies=self.cookies,
+                error_handling=True,
+                headers=self.headers,
+            )
             return response.json()
         else:
             raise ValueError("Maximum 100 locations per request")
 
     def delete_locations(self, locationId):
         """
         Deletes the location or sub-location for the specified ID
         :param locationId: location ID
         """
-        url = f'/locations/{locationId}'
+        url = f"/locations/{locationId}"
 
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response
 
     #   Traffic Forwarding
 
     def list_greTunnels(self, greTunnelId=None):
         """
         Gets the GRE tunnel information for the specified ID
         :param greTunnelId: Optional. The unique identifier for the GRE tunnel
         """
         if greTunnelId:
-            url = f'/greTunnels/{greTunnelId}'
+            url = f"/greTunnels/{greTunnelId}"
         else:
-            url = f'/greTunnels'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_greTunnels(self, sourceIp, primaryDestVip, secondaryDestVip, internalIpRange,
-                       withinCountry, comment, ipUnnumbered):
+            url = "/greTunnels"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_greTunnels(
+        self,
+        sourceIp,
+        primaryDestVip,
+        secondaryDestVip,
+        internalIpRange,
+        withinCountry,
+        comment,
+        ipUnnumbered,
+    ):
         """
         Adds a GRE tunnel configuration.
-        :param sourceIp: type string. The source IP address of the GRE tunnel. This is typically a static IP address in
-         the organization or SD-WAN. This IP address must be provisioned within the Zscaler service using the /staticIP
+        :param sourceIp: type string. The source IP address of the
+        GRE tunnel. This is typically a static IP address in
+         the organization or SD-WAN. This IP address must be provisioned
+         within the Zscaler service using the /staticIP
          endpoint.
-        :param primaryDestVip: type dictionary. {id:value} where value is integer: Unique identifier of the GRE primary
+        :param primaryDestVip: type dictionary. {id:value} where value is
+        integer: Unique identifier of the GRE primary
          VIP
-        :param secondaryDestVip: type dictionary. {id:value} where value is integer: Unique identifier of the GRE
+        :param secondaryDestVip: type dictionary. {id:value} where value is
+        integer: Unique identifier of the GRE
         secondary VIP
-        :param internalIpRange: type string. The start of the internal IP address in /29 CIDR range
-        :param withinCountry: type boolean. Restrict the data center virtual IP addresses (VIPs) only to those within
+        :param internalIpRange: type string. The start of the internal IP
+        address in /29 CIDR range
+        :param withinCountry: type boolean. Restrict the data center virtual
+        IP addresses (VIPs) only to those within
         the same country as the source IP address
-        :param comment: type string. Additional information about this GRE tunnel
-        :param ipUnnumbered:This is required to support the automated SD-WAN provisioning of GRE tunnels, when set to
+        :param comment: type string. Additional information about
+        this GRE tunnel
+        :param ipUnnumbered:This is required to support the automated SD-WAN
+        provisioning of GRE tunnels, when set to
         true gre_tun_ip and gre_tun_id are set to null
         :return:
         """
-        url = f'/greTunnels'
+        url = "/greTunnels"
         payload = {
             "sourceIp": sourceIp,
             "primaryDestVip": primaryDestVip,
             "secondaryDestVip": secondaryDestVip,
             "internalIpRange": internalIpRange,
             "withinCountry": withinCountry,
             "comment": comment,
-            "ipUnnumbered": ipUnnumbered
+            "ipUnnumbered": ipUnnumbered,
         }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def list_gre_validateAndGetAvailableInternalIpRanges(self):
         """
         Gets the next available GRE tunnel internal IP address ranges
         :return: list of available IP addresses
         """
-        url = f'/greTunnels/availableInternalIpRanges'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/greTunnels/availableInternalIpRanges"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_gre_recommended_vips(self, query):
         """
         Gets a list of recommended GRE tunnel virtual IP addresses (VIPs),
         based on source IP address or latitude/longitude coordinates.
         :param query: type string. URL query. Example:
         :return: list of available IP addresses
         """
-        url = f'/vips/recommendedList?{query}'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = f"/vips/recommendedList?{query}"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_gre_validate_ip(self, ip):
         """
-        Gets the static IP address and location mapping information for the specified GRE tunnel
+        Gets the static IP address and location mapping information for the
+        specified GRE tunnel
         IP address
         :param ip: type string. IP address of the GRE tunnel.
         :return:
         """
-        url = f'/greTunnels/validateIP/{ip}'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = f"/greTunnels/validateIP/{ip}"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_vpnCredentials(self, vpnId=None):
         """
         Gets VPN credentials that can be associated to locations.
-        :param vpnId: Optional. If specified, get VPN credentials for the specified ID.
+        :param vpnId: Optional. If specified, get VPN credentials for
+        the specified ID.
         """
         if vpnId:
-            url = f'/vpnCredentials/{vpnId}'
+            url = f"/vpnCredentials/{vpnId}"
         else:
-            url = f'/vpnCredentials'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/vpnCredentials"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
-    def add_vpnCredentials(self, fqdn, preSharedKey, type='UFQDN', comments=None, ):
+    def add_vpnCredentials(
+        self,
+        fqdn,
+        preSharedKey,
+        type="UFQDN",
+        comments=None,
+    ):
         """
         Adds VPN credentials that can be associated to locations.
         :param fqdn: type string. Example abc@domain.com
-        :param preSharedKey: type string. Pre-shared key. This is a required field for UFQDN and IP auth type
-        :param type: type string VPN authentication type. valid options CN, IP, UFQDN,XAUTH
-        :param comments: type string. Additional information about this VPN credential.
+        :param preSharedKey: type string. Pre-shared key. This is a
+        required field for UFQDN and IP auth type
+        :param type: type string VPN authentication type.
+        valid options CN, IP, UFQDN,XAUTH
+        :param comments: type string. Additional information
+        about this VPN credential.
         :return:
         """
-        url = f'/vpnCredentials'
-        payload = {
-            "type": type,
-            "fqdn": fqdn,
-            "preSharedKey": preSharedKey
-        }
+        url = "/vpnCredentials"
+        payload = {"type": type, "fqdn": fqdn, "preSharedKey": preSharedKey}
         if comments:
             payload.update(comments=comments)
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_vpnCredentials(self, vpnId):
         """
         Deletes the VPN credentials for the specified ID.
-        :param vpnId: type integer. The unique identifier for the VPN credential.
+        :param vpnId: type integer. The unique identifier
+        for the VPN credential.
         :return:
         """
-        url = f'/vpnCredentials/{vpnId}'
+        url = f"/vpnCredentials/{vpnId}"
 
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response
 
     def list_staticIP(self, IPId=None):
         """
         Gets all provisioned static IP addresses.
-        :param IPId: Optional. If specified, get IP address for the specified id
+        :param IPId: Optional. If specified, get IP address
+        for the specified id
         """
         if IPId:
-            url = f'/staticIP/{IPId}'
+            url = f"/staticIP/{IPId}"
         else:
-            url = f'/staticIP'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_staticIP(self, ipAddress, geoOverrride=False, routableIP=True, latitude=0, longitude=0, comment=''):
+            url = "/staticIP"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_staticIP(
+        self,
+        ipAddress,
+        geoOverrride=False,
+        routableIP=True,
+        latitude=0,
+        longitude=0,
+        comment="",
+    ):
         """
         Adds a static IP address
         :param ipAddress: String. The satic IP address
-        :param geoOverrride: Boolean. If not set, geographic coordinates and city are automatically determined from
-        the IP address. Otherwise, the latitude and longitude coordinates must be provided.
-        :param routableIP: Boolean. Indicates whether a non-RFC 1918 IP address is publicly routable. This attribute is
-        ignored if there is no ZIA Private Service Edge associated to the organization.
-        :param latitude: Required only if the geoOverride attribute is set. Latitude with 7 digit precision after
+        :param geoOverrride: Boolean. If not set, geographic
+        coordinates and city are automatically determined from
+        the IP address. Otherwise, the latitude and longitude
+        coordinates must be provided.
+        :param routableIP: Boolean. Indicates whether a non-RFC 1918
+        IP address is publicly routable. This attribute is
+        ignored if there is no ZIA Private Service Edge associated to
+        the organization.
+        :param latitude: Required only if the geoOverride attribute is set.
+        Latitude with 7 digit precision after
         decimal point, ranges between -90 and 90 degrees.
-        :param longitude: Required only if the geoOverride attribute is set. Longitude with 7 digit precision after
+        :param longitude: Required only if the geoOverride attribute is set.
+        Longitude with 7 digit precision after
         decimal point, ranges between -180 and 180 degrees.
-        :param comment: String Additional information about this static IP address
+        :param comment: String Additional information about this static
+        IP address
         """
-        url = '/staticIP'
+        url = "/staticIP"
 
         payload = {
             "ipAddress": ipAddress,
             "latitude": latitude,
             "longitude": longitude,
             "routableIP": routableIP,
-            "comment": comment
+            "comment": comment,
         }
         if geoOverrride:
             payload.update(geoOverrride=geoOverrride)
             payload.update(latitude=latitude)
             payload.update(longitude=longitude)
 
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_staticIP(self, Id):
         """
         Deletes the static IP address for the specified ID.
-        :param Id: type integer. The unique identifier for the provisioned static IP address.
+        :param Id: type integer. The unique identifier for the
+        provisioned static IP address.
         :return: json
         """
-        url = f'/staticIP/{Id}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        url = f"/staticIP/{Id}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
 
         return response
 
     # User Authentication Settings
     def list_exemptedUrls(self):
         """
         Gets a list of URLs that were exempted from cookie authentication
         """
-        url = '/authSettings/exemptedUrls'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/authSettings/exemptedUrls"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def add_exemptedUrls(self, urls):
         """
         Adds URLs to the cookie authentication exempt list to the list
         :param urls: List of urls. Example ['url1','url2']
         """
-        url = '/authSettings/exemptedUrls?action=ADD_TO_LIST'
+        url = "/authSettings/exemptedUrls?action=ADD_TO_LIST"
         payload = {"urls": urls}
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_exemptedUrls(self, urls):
         """
         Removed URLs to the cookie authentication exempt list to the list
         :param urls: List of urls. Example ['url1','url2']
         """
-        url = '/authSettings/exemptedUrls?action=REMOVE_FROM_LIST'
+        url = "/authSettings/exemptedUrls?action=REMOVE_FROM_LIST"
         payload = {"urls": urls}
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     # Security Policy Settings
 
     def list_security_whitelisted_urls(self):
         """
         Gets a list of white-listed URLs
         """
-        url = '/security'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/security"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def update_security_whitelisted_urls(self, urls):
         """
-        Updates the list of white-listed URLs. This will overwrite a previously-generated white list.
+        Updates the list of white-listed URLs. This will overwrite
+        a previously-generated white list.
         If you need to completely erase the white list, submit an empty list.
         :param urls: list of urls ['www.zscaler.com', 'www.example.com']
         """
-        url = '/security'
-        payload = {
-            "whitelistUrls": urls
-        }
-        response = self.hp_http.put_call(url, payload=payload, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/security"
+        payload = {"whitelistUrls": urls}
+        response = self.hp_http.put_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def list_security_blacklisted_urls(self):
         """
         Gets a list of white-listed URLs
         """
-        url = '/security/advanced'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/security/advanced"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def update_security_blacklisted_urls(self, urls):
         """
-       Updates the list of black-listed URLs. This will overwrite a previously-generated black list.
-       If you need to completely erase the black list, submit an empty list.
-        """
-        url = '/security/advanced'
-        payload = {
-            "blacklistUrls": urls
-        }
-        response = self.hp_http.put_call(url, payload=payload, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        Updates the list of black-listed URLs. This will overwrite
+        a previously-generated black list.
+        If you need to completely erase the black list, submit an empty list.
+        """
+        url = "/security/advanced"
+        payload = {"blacklistUrls": urls}
+        response = self.hp_http.put_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def add_security_blacklistUrls(self, urls):
         """
         :param urls: list of urls
         Adds a URL from the black list. To add a URL to the black list.
         """
-        url = '/security/advanced/blacklistUrls?action=ADD_TO_LIST'
-        payload = {
-            "blacklistUrls": urls
-        }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        url = "/security/advanced/blacklistUrls?action=ADD_TO_LIST"
+        payload = {"blacklistUrls": urls}
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response
 
     def remove_security_blacklistUrls(self, urls):
         """
         Removes a URL from the black list.
         :param urls: List of urls
         """
-        url = '/security/advanced/blacklistUrls?action=REMOVE_FROM_LIST'
-        payload = {
-            "blacklistUrls": urls
-        }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        url = "/security/advanced/blacklistUrls?action=REMOVE_FROM_LIST"
+        payload = {"blacklistUrls": urls}
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     # DLP Policies
 
     def list_dlpDictionaries(self, dlpDicId=None):
         """
         Gets a list of all DLP Dictionaries.
         :param dlpDicId: type int. dlp dictionary id ( optional parameter)
         """
         if dlpDicId:
-            url = f'/dlpDictionaries/{dlpDicId}'
+            url = f"/dlpDictionaries/{dlpDicId}"
         else:
-            url = '/dlpDictionaries'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/dlpDictionaries"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_dlpDictionaries_lite(self):
         """
         Gets a list of all DLP Dictionary names and ID's only. T
         """
 
-        url = '/dlpDictionaries/lite'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/dlpDictionaries/lite"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def validateDlpPattern(self, pattern):
         """
-        Validates the pattern used by a Pattern and Phrases DLP dictionary type, and provides error information if the
+        Validates the pattern used by a Pattern and Phrases DLP
+        dictionary type, and provides error information if the
         pattern is invalid.
         :param pattern: Regex pattern
         :return: json
         """
         payload = pattern
-        url = '/dlpDictionaries/validateDlpPattern'
-        response = self.hp_http.post_call(url, cookies=self.cookies, payload=payload,
-                                          error_handling=True, headers=self.headers)
+        url = "/dlpDictionaries/validateDlpPattern"
+        response = self.hp_http.post_call(
+            url,
+            cookies=self.cookies,
+            payload=payload,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_dlp_dictionaries(self, dlpDicId):
         """
         Deletes the custom DLP category for the specified ID.
         You cannot delete predefined DLP dictionaries.
-        You cannot delete a custom dictionary while it is being used by a DLP Engine or policy. Also, predefined
+        You cannot delete a custom dictionary while it is being used by a
+        DLP Engine or policy. Also, predefined
         DLP dictionaries cannot be deleted.
         :param dlpDicId: dlp dictionary ID
         :return: json response
         """
-        url = f'/dlpDictionaries/{dlpDicId}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        url = f"/dlpDictionaries/{dlpDicId}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response
 
-    def add_dlpDictionaries(self, dlpdicname, customPhraseMatchType="MATCH_ANY_CUSTOM_PHRASE_PATTERN_DICTIONARY",
-                            description=None, phrases=None, patterns=None):
+    def add_dlpDictionaries(
+        self,
+        dlpdicname,
+        customPhraseMatchType="MATCH_ANY_CUSTOM_PHRASE_PATTERN_DICTIONARY",
+        description=None,
+        phrases=None,
+        patterns=None,
+    ):
         """
-        Adds a new custom DLP dictionary that uses either Patterns and/or Phrases.
+        Adds a new custom DLP dictionary that uses either
+        Patterns and/or Phrases.
         :param dlpdicname: type string.name
         :param phrases: type list. list of phrases
         :phrases valid example:[{
         "action": "PHRASE_COUNT_TYPE_UNIQUE",
         "phrase": "string"
         }, {
         "action": "PHRASE_COUNT_TYPE_UNIQUE",
@@ -1047,290 +1354,383 @@
         "action": "PATTERN_COUNT_TYPE_UNIQUE",
         "phrase": "string"
         }]
         :param customPhraseMatchType: type string.customPhraseMatchType
         :param description: description
         """
 
-        if phrases != None:
+        if phrases is not None:
             for i in phrases:
-                if i['action'] not in ["PHRASE_COUNT_TYPE_UNIQUE", "PHRASE_COUNT_TYPE_ALL"]:
+                if i["action"] not in [
+                    "PHRASE_COUNT_TYPE_UNIQUE",
+                    "PHRASE_COUNT_TYPE_ALL",
+                ]:
                     raise ValueError("Invalid action")
-        if patterns != None:
+        if patterns is not None:
             for k in patterns:
-                if k['action'] not in ["PATTERN_COUNT_TYPE_UNIQUE", "PATTERN_COUNT_TYPE_ALL"]:
+                if k["action"] not in [
+                    "PATTERN_COUNT_TYPE_UNIQUE",
+                    "PATTERN_COUNT_TYPE_ALL",
+                ]:
                     raise ValueError("Invalid action")
 
-        if customPhraseMatchType not in ["MATCH_ALL_CUSTOM_PHRASE_PATTERN_DICTIONARY",
-                                         "MATCH_ANY_CUSTOM_PHRASE_PATTERN_DICTIONARY"]:
+        if customPhraseMatchType not in [
+            "MATCH_ALL_CUSTOM_PHRASE_PATTERN_DICTIONARY",
+            "MATCH_ANY_CUSTOM_PHRASE_PATTERN_DICTIONARY",
+        ]:
             raise ValueError("Invalid customPhraseMatchType")
 
-        url = '/dlpDictionaries'
+        url = "/dlpDictionaries"
         payload = {
             "name": dlpdicname,
             "description": description,
             "confidenceThreshold": None,
             "customPhraseMatchType": customPhraseMatchType,
             "dictionaryType": "PATTERNS_AND_PHRASES",
             "phrases": phrases,
-            "patterns": patterns
+            "patterns": patterns,
         }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def list_dlpEngines(self, dlpEngineId=None):
         """
         Get a list of DLP engines.
-        :param dlpEngineId: type integer. Optinal value. The unique identifier for the DLP engine
+        :param dlpEngineId: type integer. Optinal value.
+        The unique identifier for the DLP engine
         :return: json
         """
         if dlpEngineId:
-            url = f'/dlpEngines/{dlpEngineId}'
+            url = f"/dlpEngines/{dlpEngineId}"
         else:
-            url = '/dlpEngines'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/dlpEngines"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_dlpExactDataMatchSchemas(self):
         """
-        Exact Data Match (EDM) templates (or EDM schemas) allow the Zscaler service to identify a record from a structured
-        data source that matches predefined criteria. Using the Index Tool, you can create an EDM template that allows
-        you to define this criteria (i.e., define the tokens) for your data records by importing a CSV file.
-        After the data is defined and submitted within the tool, you can then apply the EDM template to a custom DLP
-        dictionary or engine. This endpoint gets the EDM templates for all Index Tools used by the organization
+        Exact Data Match (EDM) templates (or EDM schemas) allow the
+        Zscaler service to identify a record from a structured
+        data source that matches predefined criteria. Using the Index Tool,
+        you can create an EDM template that allows
+        you to define this criteria (i.e., define the tokens) for your data
+        records by importing a CSV file.
+        After the data is defined and submitted within the tool, you can then
+        apply the EDM template to a custom DLP
+        dictionary or engine. This endpoint gets the EDM templates for all
+        Index Tools used by the organization
 
         :return: json
         """
-        url = '/dlpExactDataMatchSchemas'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/dlpExactDataMatchSchemas"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_dlpNotificationTemplates(self, templateId=None):
         """
         Gets a list of DLP notification templates
-        :param templateId: type integer. Optional value. The unique identifier  for a DLP notification template
+        :param templateId: type integer. Optional value. The unique identifier
+        for a DLP notification template
         :return: json
         """
         if templateId:
-            url = f'/dlpNotificationTemplates/{templateId}'
+            url = f"/dlpNotificationTemplates/{templateId}"
         else:
-
-            url = '/dlpNotificationTemplates'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_dlpNotificationTemplates(self, name, subject, plainTextMessage, htmlMessage, attachContent=True,
-                                     tlsEnabled=True):
+            url = "/dlpNotificationTemplates"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_dlpNotificationTemplates(
+        self,
+        name,
+        subject,
+        plainTextMessage,
+        htmlMessage,
+        attachContent=True,
+        tlsEnabled=True,
+    ):
         """
 
         :param name: type string. The DLP notification template name
-        :param subject: type string. The Subject line that is displayed within the DLP notification template
-        :param plainTextMessage: type string. The temaplte for the plain text UTF-8 message body that must be displayed
+        :param subject: type string. The Subject line that is displayed
+        within the DLP notification template
+        :param plainTextMessage: type string. The temaplte for the plain text
+        UTF-8 message body that must be displayed
         in the DLP notification email.
-        :param htmlMessage: type string. The template for the HTML message body that myst tbe displayed in the DLP
+        :param htmlMessage: type string. The template for the HTML message
+        body that myst tbe displayed in the DLP
         notification email
-        :param attachContent: type boolean. if set to True, the content that is violation is attached to the DLP
+        :param attachContent: type boolean. if set to True, the content that
+        is violation is attached to the DLP
         notification email
-        :patam tlsEnabled: type boolean. If set to True tls will be used to send email.
+        :patam tlsEnabled: type boolean. If set to True tls will be used to
+        send email.
         :return:
         """
-        url = '/dlpNotificationTemplates'
+        url = "/dlpNotificationTemplates"
         payload = {
             "name": name,
             "subject": subject,
             "tlsEnabled": tlsEnabled,
             "attachContent": attachContent,
             "plainTextMessage": plainTextMessage,
-            "htmlMessage": htmlMessage
+            "htmlMessage": htmlMessage,
         }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_dlpNotificationTemplates(self, templateId):
         """
         Deletes a DLP notification template
-        :param templateId: type int. the unique identifies for the DLP notification template
+        :param templateId: type int. the unique identifies for
+        the DLP notification template
         :return: json
         """
         url = f"/dlpNotificationTemplates/{templateId}"
-        response = self.hp_http.delete_call(url=url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        response = self.hp_http.delete_call(
+            url=url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response
 
     def list_icapServer(self, icapServerId=None):
         """
         Gets a list of DLP notification templates
-        :param icapServerId: type integer. Optional value. The unique identifier for the DLP server using ICAP
+        :param icapServerId: type integer. Optional value. The unique
+        identifier for the DLP server using ICAP
         :return: json
         """
         if icapServerId:
-            url = f'/icapServers/{icapServerId}'
+            url = f"/icapServers/{icapServerId}"
         else:
-
-            url = '/icapServers'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/icapServers"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_idmprofile(self, profileId=None):
         """
-        List all the IDM templates for all Index Tools used by the organization. If profileId, it lists the
+        List all the IDM templates for all Index Tools
+        used by the organization. If profileId, it lists the
         IDM template information for the specified ID.
-        :param profileId: type integer. Optional value. The unique identifier for the IDM template (or profile)
+        :param profileId: type integer. Optional value. The unique
+        identifier for the IDM template (or profile)
         :return: json
         """
         if profileId:
-            url = f'/idmprofile/{profileId}'
+            url = f"/idmprofile/{profileId}"
         else:
-
-            url = '/idmprofile'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/idmprofile"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_webDlpRules(self, ruleId=None):
         """
-        list DLP policy rules, excluding SaaS Security API DLP policy rules. If ruleId, list DLP policy rule
+        list DLP policy rules, excluding SaaS Security API DLP policy rules.
+        If ruleId, list DLP policy rule
         information for the specified ID
-        :param ruleId: type integer. Optional value. The unique identifier for theDLP rule
+        :param ruleId: type integer. Optional value.
+        The unique identifier for theDLP rule
         :return: json
         """
         if ruleId:
-            url = f'/webDlpRules/{ruleId}'
+            url = f"/webDlpRules/{ruleId}"
         else:
-
-            url = '/webDlpRules'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/webDlpRules"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def delete_webDlpRules(self, ruleId):
         """
-        Deletes a DLP policy rule. This endpoint is not applicable to SaaS Security API DLP policy rules.
-        :param ruleId: type integer. The unique identifier for the DLP policy rule.
+        Deletes a DLP policy rule. This endpoint is not applicable
+        to SaaS Security API DLP policy rules.
+        :param ruleId: type integer. The unique identifier for the
+        DLP policy rule.
         :return: json
         """
-        url = f'/webDlpRules/{ruleId}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=True, headers=self.headers)
+        url = f"/webDlpRules/{ruleId}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     # Firewall Policies
 
     def list_networkServices(self, serviceId=None):
         """
-        Gets a list of all network service groups. The search parameters find matching values within the "name" or
+        Gets a list of all network service groups. The search parameters
+        find matching values within the "name" or
         "description" attributes.
         """
         if serviceId:
-            url = f'/networkServices/{serviceId}'
+            url = f"/networkServices/{serviceId}"
         else:
-            url = '/networkServices'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_networkServices(self, name, tag=None, srcTcpPorts=None, destTcpPorts=None, srcUdpPorts=None,
-                            destUdpPorts=None,
-                            type='CUSTOM', description=None, isNameL10nTag=False):
-
+            url = "/networkServices"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_networkServices(
+        self,
+        name,
+        tag=None,
+        srcTcpPorts=None,
+        destTcpPorts=None,
+        srcUdpPorts=None,
+        destUdpPorts=None,
+        type="CUSTOM",
+        description=None,
+        isNameL10nTag=False,
+    ):
         """
         Adds a new network service.
         :param name: type string. Name
         :param tag: type string
-        :param srcTcpPorts: type list. Each element is [{"start": int, "end": int}]
-        :param destTcpPorts: type list. Each element is [{"start": int, "end": int}]
-        :param srcUdpPorts: type list. Each element is [{"start": int, "end": int}]
-        :param destUdpPorts: type list. Each element is [{"start": int, "end": int}]
+        :param srcTcpPorts: type list. Each element
+        is [{"start": int, "end": int}]
+        :param destTcpPorts: type list. Each element
+        is [{"start": int, "end": int}]
+        :param srcUdpPorts: type list. Each element
+        is [{"start": int, "end": int}]
+        :param destUdpPorts: type list. Each element
+        is [{"start": int, "end": int}]
         :param type: type string. STANDARD|PREDEFINE|CUSTOM
         :param description: type string. Description
         :param isNameL10nTag: type boolean.
         :return: json response from API
         """
-        url = '/networkServices'
+        url = "/networkServices"
 
         payload = {
             "id": 0,
             "name": name,
             "tag": tag,
             "srcTcpPorts": srcTcpPorts,
             "destTcpPorts": destTcpPorts,
             "srcUdpPorts": srcUdpPorts,
             "destUdpPorts": destUdpPorts,
             "type": type,
             "description": description,
-            "isNameL10nTag": isNameL10nTag
+            "isNameL10nTag": isNameL10nTag,
         }
         print(payload)
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response
 
     def delete_networkServices(self, serviceid):
         """
 
-        :param serviceid: type int. the unique identifier for the netwokr service
+        :param serviceid: type int. The unique identifier
+        for the network service
         :return: json
         """
-        url = f'/networkServices/{serviceid}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=False, headers=self.headers)
+        url = f"/networkServices/{serviceid}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=False, headers=self.headers
+        )
         return response
 
     def list_firewallFilteringRules(self, ruleId=None):
         """
         Gets all rules in the Firewall Filtering policy.
         """
         if ruleId:
-            url = f'/firewallFilteringRules/{ruleId}'
+            url = f"/firewallFilteringRules/{ruleId}"
         else:
-            url = '/firewallFilteringRules'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
-        return response.json()
-
-    def add_firewallFilteringRules(self, name, order, state, action, description=None, defaultRule=False,
-                                   predefined=False, srcIps=None, destAddresses=None, destIpGroups=None,
-                                   srcIpGroups=None, destIpCategories=None, labels=None, nwServices=None, rank=0):
-        """
-        :param name: type str,  Name of the Firewall Filtering policy rule ["String"]
-        :param order: type int, Rule order number of the Firewall Filtering policy rule
+            url = "/firewallFilteringRules"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_firewallFilteringRules(
+        self,
+        name,
+        order,
+        state,
+        action,
+        description=None,
+        defaultRule=False,
+        predefined=False,
+        srcIps=None,
+        destAddresses=None,
+        destIpGroups=None,
+        srcIpGroups=None,
+        destIpCategories=None,
+        labels=None,
+        nwServices=None,
+        rank=0,
+        **kwargs,
+    ):
+        """
+        :param name: type str,  Name of the Firewall
+        Filtering policy rule ["String"]
+        :param order: type int, Rule order number of the
+        Firewall Filtering policy rule
         :param state: type str, Possible values : DISABLED or  ENABLED
-        :param action: type str, Possible values: ALLOW, BLOCK_DROP, BLOCK_RESET, BLOCK_ICMP, EVAL_NWAPP
+        :param action: type str, Possible values: ALLOW, BLOCK_DROP,
+        BLOCK_RESET, BLOCK_ICMP, EVAL_NWAPP
         :param rank: type int, Admin rank of the Firewall Filtering policy rule
         :param description: type str, Additional information about the rule
-        :param defaultRule: Default is false.If set to true, the default rule is applied
+        :param defaultRule: Default is false.If set to true,
+        the default rule is applied
         :param predefined: Boolean
         :param srcIps: type list, List of source IP addresses
         :param destAddresses: type list. List of destination addresses
-        :param destIpGroups: type list: List of user-definied destination IP address groups
-        :param srcIpGroups: type list: List of user defined source IP address groups
+        :param destIpGroups: type list: List of user-definied
+        destination IP address groups
+        :param srcIpGroups: type list: List of user defined source
+        IP address groups
         :param destIpCategories: type list: list of destination IP categories
-        :param nwServices: type list. List of user-defined network services on whih the rule is applied
+        :param nwServices: type list. List of user-defined network services
+        on whih the rule is applied
         :return: Default is false.If set to true, a predefined rule is applied
         """
 
-        url = '/firewallFilteringRules'
+        url = "/firewallFilteringRules"
         payload = {
             "accessControl": "READ_WRITE",
             "enableFullLogging": False,
             "name": name,
             "order": order,
             "rank": rank,
             "action": action,
             "state": state,
             "predefined": predefined,
             "defaultRule": defaultRule,
             "description": description,
-
         }
         if srcIps:
             payload.update(srcIps=srcIps)
         if srcIpGroups:
             payload.update(srcIpGroups=srcIpGroups)
         if destAddresses:
             payload.update(destAddresses=destAddresses)
@@ -1338,128 +1738,159 @@
             payload.update(destIpGroups=destIpGroups)
         if labels:
             payload.update(labels=labels)
         if destIpCategories:
             payload.update(destIpCategories=destIpCategories)
         if nwServices:
             payload.update(nwServices=nwServices)
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response
 
     def delete_firewallFIlteringRules(self, ruleId):
-
         """
         Deletes a Firewall Filtering policy rule for the specified ID.
 
         :param ruleId: type integer: The unique identifier for the policy rule
         :return: json
         """
-        url = f'/firewallFilteringRules/{ruleId}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies,
-                                            error_handling=False, headers=self.headers)
+        url = f"/firewallFilteringRules/{ruleId}"
+        response = self.hp_http.delete_call(
+            url, cookies=self.cookies, error_handling=False, headers=self.headers
+        )
         return response
 
     def list_ipSourceGroups(self, ipGroupId=None):
         """
-        Gets a list of all IP source groups. The search parameters find matching values within the "name" or
+        Gets a list of all IP source groups. The search parameters find
+        matching values within the "name" or
         "description" attributes.
         :param ipGroupId: Option ip group id
         """
         if ipGroupId:
-            url = f'/ipSourceGroups/{ipGroupId}'
+            url = f"/ipSourceGroups/{ipGroupId}"
         else:
-            url = '/ipSourceGroups'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/ipSourceGroups"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
-    def list_ipSourceGroups_lite(self, ):
+    def list_ipSourceGroups_lite(
+        self,
+    ):
         """
         Gets a name and ID dictionary of all IP source groups
         :return:
         """
-        url = '/ipSourceGroups/lite'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/ipSourceGroups/lite"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_ipDestinationGroups(self, ipGroupId=None):
         """
-        Gets a list of all IP source groups. The search parameters find matching values within the "name" or
+        Gets a list of all IP source groups. The search parameters
+        find matching values within the "name" or
         "description" attributes.
         :param ipGroupId: Option ip group id
         """
         if ipGroupId:
-            url = f'/ipDestinationGroups/{ipGroupId}'
+            url = f"/ipDestinationGroups/{ipGroupId}"
         else:
-            url = '/ipDestinationGroups/'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+            url = "/ipDestinationGroups/"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_ipDestinationGroups_lite(self):
         """
         Gets a name and ID dictionary of all IP destination groups
         return json
         """
 
-        url = '/ipDestinationGroups/lite'
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        url = "/ipDestinationGroups/lite"
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def add_ipSourceGroups(self, name, ipAddresses, description=None):
         """
         :param name: mame
         :param ipAddresses: list of IP addresses
         :param description: description
         """
 
-        url = '/ipSourceGroups'
-        payload = {
-            "name": name,
-            "ipAddresses": ipAddresses,
-            "description": description
-        }
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        url = "/ipSourceGroups"
+        payload = {"name": name, "ipAddresses": ipAddresses, "description": description}
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def delete_ipSourceGroups(self, ipGroupId):
         """
         Deletes the IP source group for the specified ID
-        :param ipGroupId:  type int. The unique identifies for the IP source group
+        :param ipGroupId:  type int. The unique identifies
+        for the IP source group
         :return: json
         """
-        url = f'/ipSourceGroups/{ipGroupId}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies, error_handling=True,
-                                            payload={}, headers=self.headers)
+        url = f"/ipSourceGroups/{ipGroupId}"
+        response = self.hp_http.delete_call(
+            url,
+            cookies=self.cookies,
+            error_handling=True,
+            payload={},
+            headers=self.headers,
+        )
         return response
 
     def delete_ipDestinationGroups(self, ipGroupId):
         """
         Deletes the IP destination group for the specified ID
-        :param ipGroupId:  type int. The uniquye identifies for the IP source group
+        :param ipGroupId:  type int. The uniquye identifies
+        for the IP source group
         :return: json
         """
-        url = f'/ipDestinationGroups/{ipGroupId}'
-        response = self.hp_http.delete_call(url, cookies=self.cookies, error_handling=True,
-                                            payload={}, headers=self.headers)
+        url = f"/ipDestinationGroups/{ipGroupId}"
+        response = self.hp_http.delete_call(
+            url,
+            cookies=self.cookies,
+            error_handling=True,
+            payload={},
+            headers=self.headers,
+        )
         return response
 
-    def add_ipDestinationGroups(self, name, type, addresses, ipCategories=None, countries=None, description=None):
+    def add_ipDestinationGroups(
+        self, name, type, addresses, ipCategories=None, countries=None, description=None
+    ):
         """
         :param name: mame
-        :param type: Destination IP group type. Either DSTN_IP or  DSTN_FQDN or DSTN_DOMAIN
+        :param type: Destination IP group type.
+        Either DSTN_IP or  DSTN_FQDN or DSTN_DOMAIN
         :param addresses: List of Destination IP addresses within the group.
         :param description: description
-        :param ipCategories: List of Destination IP address URL categories. You can identify destination based
+        :param ipCategories: List of Destination IP address URL categories.
+        You can identify destination based
         on the URL category of the domain. Default value ANY
-        :param countries: list of destination IP address countries. You can identify destinations based on the location
+        :param countries: list of destination IP address countries.
+        You can identify destinations based on the location
         of a server.Default value ANY
         """
         if type not in ["DSTN_IP", "DSTN_FQDN", "DSTN_DOMAIN"]:
             raise ValueError("Invalid destination type ")
         if countries:
             for i in countries:
                 if i not in valid_countries:
@@ -1470,26 +1901,31 @@
         if ipCategories:
             for j in ipCategories:
                 if j not in valid_category_ids:
                     raise ValueError("Invalid country ")
         else:
             ipCategories = []
 
-        url = '/ipDestinationGroups'
+        url = "/ipDestinationGroups"
         payload = {
             "name": name,
             "type": type,
             "addresses": addresses,
             "ipCategories": ipCategories,
             "countries": countries,
-            "description": description
+            "description": description,
         }
         print(payload)
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     # Device Groups
 
     def list_devices_groups(self, query=None):
         """
         Gets a list of device groups
@@ -1497,33 +1933,37 @@
         :return: List
         """
         if query:
             url = f"/deviceGroups?{query}"
         else:
             url = "/deviceGroups"
 
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     def list_devices(self, query=None):
         """
-        Gets a list of devices. Any given search parameters will be applied during device search. Search parameters are
-         based on device name, model, owner, OS type, and OS version. The devices listed can also be restricted to return
+        Gets a list of devices. Any given search parameters will be applied
+        during device search. Search parameters are
+         based on device name, model, owner, OS type, and OS version.
+         The devices listed can also be restricted to return
          information only for ones belonging to specific users.
         :param query:
         :return: List
         """
         if query:
             url = f"/deviceGroups/devices?{query}"
         else:
             url = "/deviceGroups/devices"
 
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
         return response.json()
 
     # Rule Labels
     def list_rule_labels(self, ruleLabelId=None):
         """
         Gets rule label information for the specified ID
         :param ruleLabelId:
@@ -1531,30 +1971,59 @@
         """
         if ruleLabelId:
             url = f"/ruleLabels/{ruleLabelId}"
 
         else:
             url = "/ruleLabels?pageSize=1000"
 
-        response = self.hp_http.get_call(url, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.get_call(
+            url, cookies=self.cookies, error_handling=True, headers=self.headers
+        )
+        return response.json()
+
+    def add_rule_label(self, payload):
+        """
+        Adds new rule labels with the given name
+        :param name: name
+        :param description: description
+        """
+        url = "/ruleLabels"
+        response = self.hp_http.post_call(
+            url,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+            payload=payload,
+        )
         return response.json()
 
     def update_call(self, url, payload):
         """
-        Generic PUT call. This call will overwrite all the configuration with the new payload
+        Generic PUT call. This call will overwrite all the
+        configuration with the new payload
         :param url: url of Zscaler API call
         :param payload: type json. Payload
         """
-        response = self.hp_http.put_call(url, payload=payload, cookies=self.cookies,
-                                         error_handling=True, headers=self.headers)
+        response = self.hp_http.put_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
 
     def add_call(self, url, payload):
         """
-        Generic POST call. This call will add all the configuration with the new payload
+        Generic POST call. This call will add all the
+        configuration with the new payload
         :param url: url of Zscaler API call
         :param payload: type json. Payload
         """
-        response = self.hp_http.post_call(url, payload=payload, cookies=self.cookies,
-                                          error_handling=True, headers=self.headers)
+        response = self.hp_http.post_call(
+            url,
+            payload=payload,
+            cookies=self.cookies,
+            error_handling=True,
+            headers=self.headers,
+        )
         return response.json()
```

### Comparing `zscaler_api_talkers-4.0.2/zpa_talker/zpa_portaltalker.py` & `zscaler_api_talkers-4.1.0/zscaler_api_talkers/zpa_talker/zpa_portaltalker.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,70 +1,67 @@
-import pdb
-
 import requests
-
-from zscaler_helpers.http_calls import HttpCalls
+from zscaler_helpers import HttpCalls
 
 
 class ZpaPortalTalker(object):
-
-    def __init__(self, customerId, cloud='https://api.private.zscaler.com'):
+    def __init__(self, customerId, cloud="https://api.private.zscaler.com"):
         self.base_uri = cloud
-        self.version = '1.0'
+        self.version = "1.0"
         self.cookies = None
         self.bear = None
         self.token = None
         self.headers = None
         self.customerId = customerId
         self.hp_http = HttpCalls(host=self.base_uri, verify=True)
 
     def _obtain_all_pages(self, url):
         result = []
         response = requests.request("GET", url, headers=self.token)
-        if int(response.json()['totalPages']) > 1:
+        if int(response.json()["totalPages"]) > 1:
             i = 1
-            while i <= int(response.json()['totalPages']):
-                result = result + requests.request("GET", url, headers=self.token).json()['list']
+            while i <= int(response.json()["totalPages"]):
+                result = (
+                    result
+                    + requests.request("GET", url, headers=self.token).json()["list"]
+                )
                 i += 1
         else:
-            result = response.json()['list']
+            result = response.json()["list"]
         return result
 
     def authenticate(self, username, password):
         """
         Method to obtain authorization token for subsequent calls.
         :param username: Email address
         :param password: Password for given user
         """
         url = "/base/api/zpa/signin"
-        payload = {'username': username,
-                   'password': password}
-        headers = {
-            'Content-Type': 'application/x-www-form-urlencoded'
-        }
-        response = self.hp_http.post_call(url=url, payload=payload, headers=headers, urlencoded=True)
-        self.token = response.json()['Z-AUTH-TOKEN']
+        payload = {"username": username, "password": password}
+        headers = {"Content-Type": "application/x-www-form-urlencoded"}
+        response = self.hp_http.post_call(
+            url=url, payload=payload, headers=headers, urlencoded=True
+        )
+        self.token = response.json()["Z-AUTH-TOKEN"]
         self.headers = {
-            'Content-Type': 'application/json',
-            'Accept': '*/*',
-            'Accept-Encoding': 'gzip, deflate, br',
-            'Authorization': 'Bearer ' + self.token
+            "Content-Type": "application/json",
+            "Accept": "*/*",
+            "Accept-Encoding": "gzip, deflate, br",
+            "Authorization": "Bearer " + self.token,
         }
         return
 
-
     def list_admin_users(self):
         """List admins users"""
-        url = f'/shift/api/v2/admin/customers/{self.customerId}/users'
+        url = f"/shift/api/v2/admin/customers/{self.customerId}/users"
         response = self.hp_http.get_call(url=url, headers=self.headers)
 
-        if int(response.json()['totalPages']) > 1:
+        if int(response.json()["totalPages"]) > 1:
             response = self._obtain_all_pages(url)
         else:
-            response = response.json()['list']
+            response = response.json()["list"]
         return response
 
     def list_admin_roles(self):
         """List admins roles"""
-        url = f'/zpn/api/v1/admin/customers/{self.customerId}/roles'
+        url = f"/zpn/api/v1/admin/customers/{self.customerId}/roles"
         response = self.hp_http.get_call(url=url, headers=self.headers)
         return response
```

### Comparing `zscaler_api_talkers-4.0.2/zpa_talker/zpa_talker.py` & `zscaler_api_talkers-4.1.0/zscaler_api_talkers/zpa_talker/zpa_talker.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,111 +1,134 @@
-from zscaler_helpers.http_calls import HttpCalls
+from zscaler_helpers import HttpCalls
 
 
 class ZpaTalker(object):
     """
     ZPA API talker
     Documentation: https://help.zscaler.com/zpa/zpa-api/api-developer-reference-guide
     """
 
-    def __init__(self, customerID, cloud='https://config.private.zscaler.com'):
+    def __init__(self, customerID, cloud="https://config.private.zscaler.com"):
         """
         :param cloud: type string. Example https://config.zpabeta.net
         :param customerID: type int. The unique identifier of the ZPA tenant
         """
-        self.base_uri = f'{cloud}'
+        self.base_uri = f"{cloud}"
         # self.base_uri = f'https://config.zpabeta.net'
         self.hp_http = HttpCalls(host=self.base_uri, verify=True)
         self.jsessionid = None
-        self.version = '1.3'
+        self.version = "1.3"
         self.header = None
         self.customerId = customerID
 
     def _obtain_all_results(self, url):
         """
         API response can have multiple pages. This method return the whole response in a list
         :param url: type string. url
         :return: type list
         """
         result = []
-        if '?pagesize' not in url:
-            url = url + '?pagesize=500'
+        if "?pagesize" not in url:
+            url = url + "?pagesize=500"
         response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
-        if 'list' not in response.json().keys():
+        if "list" not in response.json().keys():
             return []
-        if int(response.json()['totalPages']) > 1:
+        if int(response.json()["totalPages"]) > 1:
             i = 0
-            while i <= int(response.json()['totalPages']):
-                result = result + \
-                         self.hp_http.get_call(f'{url}&page={i}', headers=self.header, error_handling=True).json()[
-                             'list']
+            while i <= int(response.json()["totalPages"]):
+                result = (
+                    result
+                    + self.hp_http.get_call(
+                        f"{url}&page={i}", headers=self.header, error_handling=True
+                    ).json()["list"]
+                )
                 i += 1
         else:
-            result = response.json()['list']
+            result = response.json()["list"]
         return result
 
     def authenticate(self, client_id, client_secret):
         """
         Method to obtain the Bearer Token. Refer to https://help.zscaler.com/zpa/adding-api-keys
         :param client_id: type string. client id
         :param client_secret. type string. client secret
         return token
         """
-        url = f'/signin'
-        headers = {
-            'Content-Type': 'application/x-www-form-urlencoded'
-        }
-        payload = {
-            'client_id': client_id,
-            'client_secret': client_secret
-        }
-        response = self.hp_http.post_call(url, headers=headers, error_handling=True, payload=payload, urlencoded=True)
+        url = f"/signin"
+        headers = {"Content-Type": "application/x-www-form-urlencoded"}
+        payload = {"client_id": client_id, "client_secret": client_secret}
+        response = self.hp_http.post_call(
+            url, headers=headers, error_handling=True, payload=payload, urlencoded=True
+        )
         self.header = {
-            'Authorization': f"{response.json()['token_type']} {response.json()['access_token']}"
+            "Authorization": f"{response.json()['token_type']} {response.json()['access_token']}"
         }
         return response.json()
 
     # app-server-controller
 
     def list_servers(self, query=False, serverId=None):
         """
         Method to obtain all the configured Servers.
         :param serverId: type int. Unique server id number
         :param query: type string. Example ?page=1&pagesize=20&search=consequat
         :return:json
         """
         if serverId:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/server/{serverId}'
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/server/{serverId}"
         else:
             if not query:
-                query = '?pagesize=500'
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/server{query}'
+                query = "?pagesize=500"
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/server{query}"
         response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
         return response.json()
 
     # application-controller
     def list_application_segments(self, applicationId=None):
         """
         Method to obtain application segments
         :param applicationId type int. Application unique identified id
         """
         if applicationId:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/application/{applicationId}'
-            response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/application/{applicationId}"
+            response = self.hp_http.get_call(
+                url, headers=self.header, error_handling=True
+            )
             return response.json()
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/application'
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/application"
         response = self._obtain_all_results(url)
         return response
 
-    def add_application_segment(self, name, healthReporting, domainNames, segmentGroupId, serverGroups,
-                                commonAppsDto={}, segmentGroupName='', healthCheckType='DEFAULT', clientlessApps=[],
-                                inspectionApps=[], sraApps=[], tcpPortRange=[], tcpPortRanges=[], udpPortRanges=[],
-                                udpPortRange=[], description='', enabled=True, icmpAccessType='NONE', ipAnchored=False,
-                                doubleEncrypt=False, bypassType='NEVER', isCnameEnabled=True,
-                                selectConnectorCloseToApp=False, passiveHealthEnabled=True):
+    def add_application_segment(
+        self,
+        name,
+        healthReporting,
+        domainNames,
+        segmentGroupId,
+        serverGroups,
+        commonAppsDto={},
+        segmentGroupName="",
+        healthCheckType="DEFAULT",
+        clientlessApps=[],
+        inspectionApps=[],
+        sraApps=[],
+        tcpPortRange=[],
+        tcpPortRanges=[],
+        udpPortRanges=[],
+        udpPortRange=[],
+        description="",
+        enabled=True,
+        icmpAccessType="NONE",
+        ipAnchored=False,
+        doubleEncrypt=False,
+        bypassType="NEVER",
+        isCnameEnabled=True,
+        selectConnectorCloseToApp=False,
+        passiveHealthEnabled=True,
+    ):
         """
         Adds a new Application Segment for a ZPA tenant.
         :param name: type string. App Name
         :param description: type string. Description
         :param enabled: type boolean (True|False)
         :param healthReporting: type string. possible values: NONE, ON_ACCESS, CONTINUOUS
         :param icmpAccessType: type string. possible values: PING_TRACEROUTING, PING, NONE
@@ -154,255 +177,295 @@
             "udpPortRange": udpPortRange,
             "udpPortRanges": udpPortRanges,
             "domainNames": domainNames,
             "segmentGroupId": segmentGroupId,
             "segmentGroupName": segmentGroupName,
             "serverGroups": serverGroups,
         }
-        response = self.hp_http.post_call(url=url, payload=payload, headers=self.header, error_handling=True)
+        response = self.hp_http.post_call(
+            url=url, payload=payload, headers=self.header, error_handling=True
+        )
         return response.json()
 
-    def update_application_segment(self,applicationId,payload):
+    def update_application_segment(self, applicationId, payload):
         """
         Updates the Application Segment details for the specified ID
         :param applicationId: type int. Application ID
         """
         url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/application/{applicationId}"
-        response = self.hp_http.put_call(url=url, payload=payload, headers=self.header, error_handling=True)
+        response = self.hp_http.put_call(
+            url=url, payload=payload, headers=self.header, error_handling=True
+        )
         return response
-    def delete_application_segment(self,applicationId,):
+
+    def delete_application_segment(
+        self,
+        applicationId,
+    ):
         """
         Updates the Application Segment details for the specified ID
         :param applicationId: type int. Application ID
         """
         url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/application/{applicationId}"
         response = self.hp_http.delete_call(url=url, error_handling=True)
         return response
+
     # segment-group-controller
 
     def list_segment_group(self, segmentGroupId=None, query=False):
         """
         Get all the configured Segment Groups. If segmentGroupId obtains the segment sroup details
         :param segmentGroupId: The unique identifier of the Segment Group.
         :param query: url query: Example ?page=1&pagesize=20&search=consequat
         return json
         """
         if segmentGroupId:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/segmentGroup/{segmentGroupId}'
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/segmentGroup/{segmentGroupId}"
+            response = self.hp_http.get_call(
+                url, headers=self.header, error_handling=True
+            ).json()
         else:
             if not query:
-                query = '?pagesize=500'
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/segmentGroup{query}'
-        response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
-        return response.json()
+                query = "?pagesize=500"
+            url = (
+                f"/mgmtconfig/v1/admin/customers/{self.customerId}/segmentGroup{query}"
+            )
+            response = self._obtain_all_results(url)
+
+        return response
 
     def add_segment_group(self, name, description, enabled=True):
         """
         Add a new segment group
         :param name: type string. Name of segment Group
         :param description: type string. Description
         :param enabled: type boolean: True or False
         :return: Json
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/segmentGroup'
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/segmentGroup"
         payload = {
             "name": name,
             "description": description,
             "enabled": enabled,
         }
-        response = self.hp_http.post_call(url, headers=self.header, error_handling=True, payload=payload)
+        response = self.hp_http.post_call(
+            url, headers=self.header, error_handling=True, payload=payload
+        )
         return response.json()
 
     # connector-controller
-    def list_connector(self, connectorId=None, ):
+    def list_connector(
+        self,
+        connectorId=None,
+    ):
         """
         Get all the configured Segment Groups. If segmentGroupId obtains the segment group details
         :param connectorId: The unique identifier of the App Connector.
         return json
         """
         if connectorId:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/connector/{connectorId}'
-            return self.hp_http.get_call(url, headers=self.header, error_handling=True).json()
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/connector/{connectorId}"
+            return self.hp_http.get_call(
+                url, headers=self.header, error_handling=True
+            ).json()
         else:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/connector'
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/connector"
         response = self._obtain_all_results(url)
         return response
 
     def delete_bulk_connector(self, ids):
         """
         Get all the configured Segment Groups. If segmentGroupId obtains the segment sroup details
         :param ids: type list. list of resouces ids for bulk deleting the App Connectors..
         return json
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/connector/bulkDelete'
-        payload = {"ids": ids
-                   }
-        response = self.hp_http.post_call(url=url, headers=self.header, error_handling=True, payload=payload)
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/connector/bulkDelete"
+        payload = {"ids": ids}
+        response = self.hp_http.post_call(
+            url=url, headers=self.header, error_handling=True, payload=payload
+        )
         return response.json()
 
     # Connector-group-controller
     def list_connector_group(self, appConnectorGroupId=None):
         """
         Gets all configured App Connector Groups for a ZPA tenant.
         :param appConnectorGroupId: type int: The unique identifier of the Connector Group.
         return json
         """
         if appConnectorGroupId:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/appConnectorGroup/{appConnectorGroupId}'
-            return self.hp_http.get_call(url, headers=self.header, error_handling=True).json()
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/appConnectorGroup/{appConnectorGroupId}"
+            return self.hp_http.get_call(
+                url, headers=self.header, error_handling=True
+            ).json()
         else:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/appConnectorGroup'
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/appConnectorGroup"
             response = self._obtain_all_results(url)
         return response
 
     # ba-certificate-controller-v-2
 
     def list_browser_access_certificates(self):
         """
         Get all Browser issued certificates
         return json
         """
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/clientlessCertificate/issued'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/clientlessCertificate/issued"
         response = self._obtain_all_results(url)
         return response
 
     # enrollment-cert-controller
 
-    def list_enrollment_certificates(self, ):
+    def list_enrollment_certificates(
+        self,
+    ):
         """
         Get all the Enrollment certificates
         return list
         """
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/enrollmentCert'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/enrollmentCert"
         response = self._obtain_all_results(url)
         return response
 
     def list_browser_access_certificates(self):
         """
         Get all the issued certificates
         return list
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/visible/versionProfiles'
+        url = (
+            f"/mgmtconfig/v1/admin/customers/{self.customerId}/visible/versionProfiles"
+        )
         response = self._obtain_all_results(url)
         return response
 
     # customer-version-profile-controller
 
     def list_customer_version_profile(self, query=False):
         """
         Get Version Profiles visible to a customer
         :param query: url query: Example ?page=1&pagesize=20&search=consequat
         return json
         """
         if not query:
-            query = '?pagesize=500'
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/visible/versionProfiles{query}'
+            query = "?pagesize=500"
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/visible/versionProfiles{query}"
         response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
         return response.json()
 
     # cloud - connector - group - controller
     def list_cloud_connector_group(self, id=None, query=False):
         """
         Get all configured Cloud Connector Groups. If id, Get the Cloud Connector Group details
         :param query: url query: Example ?page=1&pagesize=20&search=consequat
         return json
         """
         if id:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/cloudConnectorGroup/{id}'
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/cloudConnectorGroup/{id}"
         else:
             if not query:
-                query = '?pagesize=500'
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/cloudConnectorGroup{query}'
+                query = "?pagesize=500"
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/cloudConnectorGroup{query}"
         response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
         return response.json()
 
     # idp-controller-v-2
     def list_idP(self, query=False):
         """
         Method to Get all the idP details for a ZPA tenant
         :param query: HTTP query
         :return: json
         """
         if not query:
-            query = '?pagesize=500'
+            query = "?pagesize=500"
 
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/idp{query}'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/idp{query}"
         response = self._obtain_all_results(url)
         return response
 
     # provisioningKey-controller
-    def list_provisioningKey(self, associationType='CONNECTOR_GRP'):
+    def list_provisioningKey(self, associationType="CONNECTOR_GRP"):
         """
         Gets details of all the configured provisioning keys.
         :param associationType: type string. The supported values are CONNECTOR_GRP and SERVICE_EDGE_GRP.
         :return: list
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/associationType/{associationType}/provisioningKey'
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/associationType/{associationType}/provisioningKey"
         response = self._obtain_all_results(url)
         return response
 
     # policy-set-controller
 
     # scim-attribute-header-controller
 
     def list_scim_attributes(self, idpId, query=False):
         """
 
         :param idpId: The unique identifies of the Idp
         :param query: ?page=1&pagesize=20&search=consequat
         """
         if not query:
-            query = '?pagesize=500'
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/idp/{idpId}/scimattribute{query}'
+            query = "?pagesize=500"
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/idp/{idpId}/scimattribute{query}"
         response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
         return response.json()
 
     # scim-group-controller
     def list_scim_groups(self, idpId, query=False):
         """
         Method to list all SCIM groups
         :param idpId: The unique identifies of the Idp
         :param query: ?page=1&pagesize=20&search=consequat
         """
         if not query:
-            query = '?pagesize=500'
-        url = f'/userconfig/v1/customers/{self.customerId}/scimgroup/idpId/{idpId}{query}'
+            query = "?pagesize=500"
+        url = (
+            f"/userconfig/v1/customers/{self.customerId}/scimgroup/idpId/{idpId}{query}"
+        )
         response = self._obtain_all_results(url)
         return response
 
     # saml-attr-controller-v-2
     def list_saml_attributes(self):
         """
         Method to get all SAML attributes
         """
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/samlAttribute'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/samlAttribute"
         response = self._obtain_all_results(url)
         return response
 
     # global-policy-controller
 
-    def list_policies(self, policyType='ACCESS_POLICY'):
+    def list_policies(self, policyType="ACCESS_POLICY"):
         """list policie(s)  by policy type,
-         :param policyType: Type string. Supported values Possible values=ACCESS_POLICY,GLOBAL_POLICY, TIMEOUT_POLICY,REAUTH_POLICY,
-         SIEM_POLICY, CLIENT_FORWARDING_POLICY,BYPASS_POLICY
-         """
+        :param policyType: Type string. Supported values Possible values=ACCESS_POLICY,GLOBAL_POLICY, TIMEOUT_POLICY,REAUTH_POLICY,
+        SIEM_POLICY, CLIENT_FORWARDING_POLICY,BYPASS_POLICY
+        """
         url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/policySet/rules/policyType/{policyType}"
         response = self._obtain_all_results(url)
         return response
 
-    def list_policySet(self, policyType='ACCESS_POLICY'):
-        """ Gets the policy set for the specified policy type
+    def list_policySet(self, policyType="ACCESS_POLICY"):
+        """Gets the policy set for the specified policy type
         :param policyType: Type string. Supported values are ACCESS_POLICY,GLOBAL_POLICY, TIMEOUT_POLICY,REAUTH_POLICY,
         SIEM_POLICY, CLIENT_FORWARDING_POLICY,BYPASS_POLICY
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/policySet/policyType/{policyType}'
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/policySet/policyType/{policyType}"
         response = self.hp_http.get_call(url, headers=self.header, error_handling=True)
         return response.json()
 
-    def add_policySet(self, app_operands, RuleName, Action, policySetId, operands, operator, MsgString=None):
+    def add_policySet(
+        self,
+        app_operands,
+        RuleName,
+        Action,
+        policySetId,
+        operands,
+        operator,
+        MsgString=None,
+    ):
         """
         Method to create a new access Policy
         :param app_operands: list of app_operands: Examples
         [{
                     "objectType": "APP",
                     "lhs": "id",
                     "rhs": applicationId,
@@ -420,94 +483,99 @@
             "lhs": "<scimAttrId>",
             "rhs": "<scimAttrValue>”
         }]
 
 
         :return:
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/policySet/{policySetId}/rule'
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/policySet/{policySetId}/rule"
         payload = {
-            "conditions": [{
-                "operands": app_operands
-            }, {
-
-                "operands": operands,
-                "operator": operator,
-            }, ],
+            "conditions": [
+                {"operands": app_operands},
+                {
+                    "operands": operands,
+                    "operator": operator,
+                },
+            ],
             # Seems here needs to be AND
-            "operator": 'AND',
+            "operator": "AND",
             "name": RuleName,
             "description": "Description",
             "action": Action,
-            "customMsg": MsgString
+            "customMsg": MsgString,
         }
         print(payload)
-        response = self.hp_http.post_call(url=url, headers=self.header, error_handling=True, payload=payload)
+        response = self.hp_http.post_call(
+            url=url, headers=self.header, error_handling=True, payload=payload
+        )
         return response.json()
 
     # Server Group Controller
 
     def list_server_groups(self, groupId=None):
         """
         Method to get all configured Server Groups. If groupI, get the Server Group details
         :param groupId: type integer. The unique identifier of the Server Group.
         return json
         """
         if groupId:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/serverGroup/{groupId}'
-            response = self.hp_http.get_call(url, headers=self.header, error_handling=True).json()
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/serverGroup/{groupId}"
+            response = self.hp_http.get_call(
+                url, headers=self.header, error_handling=True
+            ).json()
         else:
-            url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/serverGroup'
+            url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/serverGroup"
             response = self._obtain_all_results(url)
         return response
 
     def add_server_groups(self, name, description, connector_group_id):
         """
         :param name: Server Group Name
         :param description: Description
         :param connector_group_id: list of dictionaries with key as "id" and value connector_group_id.
             [{"id": connector_group_id}]
         """
-        url = f'/mgmtconfig/v1/admin/customers/{self.customerId}/serverGroup'
+        url = f"/mgmtconfig/v1/admin/customers/{self.customerId}/serverGroup"
 
         payload = {
             "enabled": True,
             "dynamicDiscovery": True,
             "name": name,
             "description": description,
-            "servers": [
-            ],
-            "appConnectorGroups": connector_group_id
+            "servers": [],
+            "appConnectorGroups": connector_group_id,
         }
-        response = self.hp_http.post_call(url=url, headers=self.header, error_handling=True, payload=payload)
+        response = self.hp_http.post_call(
+            url=url, headers=self.header, error_handling=True, payload=payload
+        )
         return response.json()
 
     def list_posture_profiles(self, query=False):
         """
         Method to Get all the idP details for a ZPA tenant
         :param query: HTTP query
         :return: json
         """
         if not query:
-            query = '?pagesize=500'
+            query = "?pagesize=500"
 
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/posture{query}'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/posture{query}"
         response = self._obtain_all_results(url)
         return response
 
     def list_privileged_consoles(self, query=False):
         """
         Method to Get all the privleged_remote_consoles for a ZPA tenant
         :param query: HTTP query
         :return: json
         """
         if not query:
-            query = '?pagesize=500'
+            query = "?pagesize=500"
 
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/privilegedConsoles{query}'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/privilegedConsoles{query}"
         response = self._obtain_all_results(url)
         return response
 
     def list_sra_consoles(self):
         """
         Method to obtain list of sra consoles from all application segments
         """
@@ -521,12 +589,12 @@
 
     # Certificate Controller v2
     def list_issued_certificates(self, query=None):
         """
         Method to get all issued certificates
         """
         if not query:
-            query = '?pagesize=500'
+            query = "?pagesize=500"
 
-        url = f'/mgmtconfig/v2/admin/customers/{self.customerId}/certificate/issued'
+        url = f"/mgmtconfig/v2/admin/customers/{self.customerId}/certificate/issued"
         response = self._obtain_all_results(url)
         return response
```

### Comparing `zscaler_api_talkers-4.0.2/zscaler_helpers/http_calls.py` & `zscaler_api_talkers-4.1.0/zscaler_api_talkers/zscaler_helpers/http_calls.py`

 * *Files 23% similar despite different names*

```diff
@@ -11,135 +11,182 @@
     def __init__(self, host, header=None, verify=True):
         """
         to start this instance, host IP address or fqdn is required
         :param host: IP address or fqdn
         :param header: dictionary. HTTP header
         :param verify: Boolean. True to verify ssl cert with in HTTP call
         """
-        self.version = '1.1'
+        self.version = "1.1"
         self.host = host
-        self.headers = {'Content-type': 'application/json',
-                        'Cache-Control': 'no-cache'
-                        }
+        self.headers = {"Content-type": "application/json", "Cache-Control": "no-cache"}
         if header:
             self.headers.update(header)
         self.cookies = None
         self.verify = verify
 
-    def get_call(self, url, cookies=None, headers=None, params=None, error_handling=False):
+    def get_call(
+        self, url, cookies=None, headers=None, params=None, error_handling=False
+    ):
         """
         Method to perform a GET HTTP  call
         :param url: url
         :param cookies: cookies
         :param headers: Additional HTTP headers
         :param params: Key,Value parameters in the URL after a question mark
         :param error_handling: Boolean, when TRUE will use Zscaler HTTP codes
         :return: response
         """
-        full_url = f'{self.host}{url}'
+        full_url = f"{self.host}{url}"
         if headers:
             self.headers.update(headers)
         try:
-            response = requests.get(url=full_url, headers=self.headers, cookies=cookies, params=params,
-                                    verify=self.verify)
+            response = requests.get(
+                url=full_url,
+                headers=self.headers,
+                cookies=cookies,
+                params=params,
+                verify=self.verify,
+            )
             if error_handling:
                 self._zia_http_codes(response)
             else:
                 if response.status_code not in [200, 201, 204]:
-                    raise ValueError(f'{response.status_code} -> {response.content}')
+                    raise ValueError(f"{response.status_code} -> {response.content}")
             return response
         except requests.HTTPError as e:
             raise ValueError(e)
 
-    def post_call(self, url, payload, headers=None, cookies=None, error_handling=False, urlencoded=False):
+    def post_call(
+        self,
+        url,
+        payload,
+        headers=None,
+        cookies=None,
+        error_handling=False,
+        urlencoded=False,
+    ):
         """
         Method to perform an HTTP POST call
         :param url: url
         :param cookies: cookies
         :param error_handling: Boolean, when TRUE will use Zscaler HTTP codes
         :return: response
         """
-        full_url = f'{self.host}{url}'
+        full_url = f"{self.host}{url}"
         try:
             if urlencoded:
                 url_encoded_headers = headers
-                response = requests.post(url=full_url, headers=url_encoded_headers, cookies=cookies, data=payload,
-                                         verify=self.verify)
+                response = requests.post(
+                    url=full_url,
+                    headers=url_encoded_headers,
+                    cookies=cookies,
+                    data=payload,
+                    verify=self.verify,
+                )
             else:
                 if headers:
                     self.headers.update(headers)
-                response = requests.post(url=full_url, headers=self.headers, cookies=cookies, json=payload,
-                                         verify=self.verify)          
+                response = requests.post(
+                    url=full_url,
+                    headers=self.headers,
+                    cookies=cookies,
+                    json=payload,
+                    verify=self.verify,
+                )
             if error_handling:
                 self._zia_http_codes(response)
             else:
                 if response.status_code not in [200, 201, 204]:
-                    raise ValueError(f'{response.status_code} -> {response.content}')
+                    raise ValueError(f"{response.status_code} -> {response.content}")
             return response
         except requests.HTTPError as e:
             raise ValueError(e)
 
-    def patch_call(self, url, payload, cookies=None, ):
+    def patch_call(
+        self,
+        url,
+        payload,
+        cookies=None,
+    ):
         """
         Method to perform an HTTP PATH call
         :param url: url
         :param cookies: cookies
         :return: response
         """
-        full_url = f'{self.host}{url}'
+        full_url = f"{self.host}{url}"
         try:
-            response = requests.patch(url=full_url, headers=self.headers, cookies=cookies, json=payload,
-                                      verify=self.verify)
+            response = requests.patch(
+                url=full_url,
+                headers=self.headers,
+                cookies=cookies,
+                json=payload,
+                verify=self.verify,
+            )
             if response.status_code not in [200, 201, 204]:
                 raise ValueError(response.status_code)
             return response
         except requests.HTTPError as e:
             raise ValueError(e)
 
     def put_call(self, url, payload, headers=None, cookies=None, error_handling=False):
         """
         Method to perform an HTTP PUT call
         :param url: url
         :param cookies: cookies
         :param error_handling: Boolean, when TRUE will use Zscaler HTTP codes
         :return: response
         """
-        full_url = f'{self.host}{url}'
+        full_url = f"{self.host}{url}"
         if headers:
             self.headers.update(headers)
         try:
-            response = requests.put(url=full_url, headers=self.headers, cookies=cookies, json=payload,
-                                    verify=self.verify)
+            response = requests.put(
+                url=full_url,
+                headers=self.headers,
+                cookies=cookies,
+                json=payload,
+                verify=self.verify,
+            )
             if error_handling:
                 self._zia_http_codes(response)
             else:
                 if response.status_code not in [200, 201, 204]:
                     try:
-                        raise ValueError(f'HTTPS Response code {response.status_code} : {response.json()}')
+                        raise ValueError(
+                            f"HTTPS Response code {response.status_code} : {response.json()}"
+                        )
                     except ValueError:
                         raise ValueError(response.status_code)
             return response
         except requests.HTTPError as e:
             raise ValueError(e)
 
-    def delete_call(self, url, payload=None, headers=None, cookies=None, error_handling=False):
+    def delete_call(
+        self, url, payload=None, headers=None, cookies=None, error_handling=False
+    ):
         """
         Method to perform an HTTP DELETE call
         :param url: url
         :param payload: json payload
         :param cookies: cookies
         :param error_handling: Boolean, when TRUE will use Zscaler HTTP codes
         :return: response
         """
-        full_url = f'{self.host}{url}'
+        full_url = f"{self.host}{url}"
         if headers:
             self.headers.update(headers)
         try:
-            response = requests.delete(url=full_url, headers=self.headers, cookies=cookies, json=payload,
-                                       verify=self.verify)
+            response = requests.delete(
+                url=full_url,
+                headers=self.headers,
+                cookies=cookies,
+                json=payload,
+                verify=self.verify,
+            )
             if error_handling:
                 self._zia_http_codes(response)
             else:
                 if response.status_code not in [200, 201, 204]:
                     raise ValueError(response.status_code)
             return response
         except requests.HTTPError as e:
@@ -149,28 +196,33 @@
         """
         Internal method to display HTTP error handling and response codes
         For more information, please refer to https://help.zscaler.com/zia/about-error-handling
         :param response:
         :return: None
         """
         if response.status_code in [200, 201, 202, 204]:
-            return    
+            return
         elif response.status_code == 401:
-            raise ValueError(f'{response.status_code} :Session is not authenticated or timed out')
+            raise ValueError(
+                f"{response.status_code} :Session is not authenticated or timed out"
+            )
         elif response.status_code == 403:
             raise ValueError(
-                f'{response.status_code} :API key disabled or SKU subscription missing or user role has not access')
+                f"{response.status_code} :API key disabled or SKU subscription missing or user role has not access"
+            )
         elif response.status_code == 404:
-            raise ValueError('Resource does not exist')
+            raise ValueError("Resource does not exist")
         elif response.status_code == 409:
-            raise ValueError('Request could not be processed because of possible edit conflict occurred')
+            raise ValueError(
+                "Request could not be processed because of possible edit conflict occurred"
+            )
         elif response.status_code == 415:
-            raise ValueError('Unsupported media type')
+            raise ValueError("Unsupported media type")
         elif response.status_code == 429:
-            raise ValueError('Exceeded the rate limit or quota')
+            raise ValueError("Exceeded the rate limit or quota")
         elif response.status_code == 500:
-            raise ValueError('Unexpected error')
+            raise ValueError("Unexpected error")
         elif response.status_code == 503:
-            raise ValueError('Service is temporarily unavailable')
+            raise ValueError("Service is temporarily unavailable")
         else:
             print(response.content)
-            raise ValueError(f'Unexpected HTTP response code: {response.status_code}')
+            raise ValueError(f"Unexpected HTTP response code: {response.status_code}")
```


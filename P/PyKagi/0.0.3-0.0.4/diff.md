# Comparing `tmp/PyKagi-0.0.3.tar.gz` & `tmp/PyKagi-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyKagi-0.0.3.tar", last modified: Mon Apr 24 01:32:21 2023, max compression
+gzip compressed data, was "PyKagi-0.0.4.tar", last modified: Wed Jun 28 06:54:01 2023, max compression
```

## Comparing `PyKagi-0.0.3.tar` & `PyKagi-0.0.4.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2023-04-24 01:32:21.149187 PyKagi-0.0.3/
--rw-rw-rw-   0        0        0    11558 2023-03-29 23:46:55.000000 PyKagi-0.0.3/LICENSE
--rw-rw-rw-   0        0        0     3194 2023-04-24 01:32:21.148191 PyKagi-0.0.3/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-04-24 01:32:21.135064 PyKagi-0.0.3/PyKagi/
--rw-rw-rw-   0        0        0      262 2023-03-30 01:22:53.000000 PyKagi-0.0.3/PyKagi/__init__.py
--rw-rw-rw-   0        0        0     2367 2023-04-24 01:31:24.000000 PyKagi-0.0.3/PyKagi/api.py
-drwxrwxrwx   0        0        0        0 2023-04-24 01:32:21.148191 PyKagi-0.0.3/PyKagi/config/
--rw-rw-rw-   0        0        0        0 2022-10-13 08:58:13.000000 PyKagi-0.0.3/PyKagi/config/__init__.py
--rw-rw-rw-   0        0        0      172 2023-04-24 01:31:58.000000 PyKagi-0.0.3/PyKagi/config/info.py
-drwxrwxrwx   0        0        0        0 2023-04-24 01:32:21.146196 PyKagi-0.0.3/PyKagi.egg-info/
--rw-rw-rw-   0        0        0     3194 2023-04-24 01:32:21.000000 PyKagi-0.0.3/PyKagi.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      256 2023-04-24 01:32:21.000000 PyKagi-0.0.3/PyKagi.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-04-24 01:32:21.000000 PyKagi-0.0.3/PyKagi.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       89 2023-04-24 01:32:21.000000 PyKagi-0.0.3/PyKagi.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-04-24 01:32:21.000000 PyKagi-0.0.3/PyKagi.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     2731 2023-04-24 01:22:21.000000 PyKagi-0.0.3/README.md
--rw-rw-rw-   0        0        0       42 2023-04-24 01:32:21.150186 PyKagi-0.0.3/setup.cfg
--rw-rw-rw-   0        0        0      903 2023-04-24 01:28:03.000000 PyKagi-0.0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:54:01.561262 PyKagi-0.0.4/
+-rw-rw-rw-   0        0        0    11558 2023-03-29 23:46:55.000000 PyKagi-0.0.4/LICENSE
+-rw-rw-rw-   0        0        0     7150 2023-06-28 06:54:01.560264 PyKagi-0.0.4/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 06:54:01.539320 PyKagi-0.0.4/PyKagi/
+-rw-rw-rw-   0        0        0      262 2023-03-30 01:22:53.000000 PyKagi-0.0.4/PyKagi/__init__.py
+-rw-rw-rw-   0        0        0     3024 2023-06-28 06:53:41.000000 PyKagi-0.0.4/PyKagi/api.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:54:01.559266 PyKagi-0.0.4/PyKagi/config/
+-rw-rw-rw-   0        0        0        0 2022-10-13 08:58:13.000000 PyKagi-0.0.4/PyKagi/config/__init__.py
+-rw-rw-rw-   0        0        0      172 2023-06-28 06:53:00.000000 PyKagi-0.0.4/PyKagi/config/info.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:54:01.558269 PyKagi-0.0.4/PyKagi.egg-info/
+-rw-rw-rw-   0        0        0     7150 2023-06-28 06:54:01.000000 PyKagi-0.0.4/PyKagi.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      256 2023-06-28 06:54:01.000000 PyKagi-0.0.4/PyKagi.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:54:01.000000 PyKagi-0.0.4/PyKagi.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       89 2023-06-28 06:54:01.000000 PyKagi-0.0.4/PyKagi.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 06:54:01.000000 PyKagi-0.0.4/PyKagi.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     6687 2023-06-28 06:52:18.000000 PyKagi-0.0.4/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 06:54:01.561262 PyKagi-0.0.4/setup.cfg
+-rw-rw-rw-   0        0        0      903 2023-04-24 01:28:03.000000 PyKagi-0.0.4/setup.py
```

### Comparing `PyKagi-0.0.3/LICENSE` & `PyKagi-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `PyKagi-0.0.3/PyKagi/api.py` & `PyKagi-0.0.4/PyKagi/api.py`

 * *Files 18% similar despite different names*

```diff
@@ -32,15 +32,15 @@
         else:
             headers["Content-Type"] = "application/json"
             data = {
                 "text": text,
                 "engine": engine,
                 "summary_type": summary_type,
                 "target_language": target_language,
-                "cache": str(cache).lower()
+                "cache": str(cache).lower(),
             }
             response = requests.post(self.base_url, headers=headers, json=data)
 
         if response.status_code == 200:
             return response.json()
         else:
             raise Exception(
@@ -56,17 +56,40 @@
     def search(self, query, limit=None):
         headers = {
             "Authorization": f"Bot {self.api_token}"
         }
 
         params = {
             "q": query,
-            "limit": limit
+            "limit": limit,
         }
 
         response = requests.get(self.base_url, headers=headers, params=params)
 
         if response.status_code == 200:
             return response.json()
         else:
             raise Exception(
                 f"Request failed with status code {response.status_code}")
+
+class FastGPT:
+
+    def __init__(self, api_token=None):
+        self.api_token = api_token
+        self.base_url = "https://kagi.com/api/v0/fastgpt"
+
+    def fastgpt(self, query, **kwargs):
+        headers = {
+            "Authorization": f"Bot {self.api_token}"
+        }
+        data = {
+            "query": query,
+        }
+        data.update(kwargs)
+
+        response = requests.post(self.base_url, headers=headers, json=data)
+    
+        if response.status_code == 200:
+            return response.json()
+        else:
+            raise Exception(
+                f"Request failed with status code {response.status_code}")
```

### Comparing `PyKagi-0.0.3/setup.py` & `PyKagi-0.0.4/setup.py`

 * *Files identical despite different names*


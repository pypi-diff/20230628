# Comparing `tmp/open_source_insights_api-0.1.5.tar.gz` & `tmp/open_source_insights_api-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "open_source_insights_api-0.1.5.tar", last modified: Fri May 19 17:45:42 2023, max compression
+gzip compressed data, was "open_source_insights_api-0.1.6.tar", max compression
```

## Comparing `open_source_insights_api-0.1.5.tar` & `open_source_insights_api-0.1.6.tar`

### file list

```diff
@@ -1,5 +1,6 @@
--rwxr-xr-x   0        0        0     1477 2023-05-19 14:38:48.904802 open_source_insights_api-0.1.5/LICENSE
--rwxr-xr-x   0        0        0       90 2023-05-19 17:23:05.161293 open_source_insights_api-0.1.5/open_source_insights_api/__init__.py
--rwxr-xr-x   0        0        0     7882 2023-05-19 15:07:52.296446 open_source_insights_api-0.1.5/open_source_insights_api/os_insights.py
--rwxr-xr-x   0        0        0      414 2023-05-19 15:00:27.324032 open_source_insights_api-0.1.5/pyproject.toml
--rw-r--r--   0        0        0      290 1970-01-01 00:00:00.000000 open_source_insights_api-0.1.5/PKG-INFO
+-rw-r--r--   0        0        0     1477 2023-06-28 12:33:48.709797 open_source_insights_api-0.1.6/LICENSE
+-rw-r--r--   0        0        0     1398 2023-06-28 12:33:48.709797 open_source_insights_api-0.1.6/README.md
+-rw-r--r--   0        0        0       90 2023-06-28 12:56:28.669792 open_source_insights_api-0.1.6/open_source_insights_api/__init__.py
+-rw-r--r--   0        0        0     7932 2023-06-28 12:33:48.709797 open_source_insights_api-0.1.6/open_source_insights_api/os_insights.py
+-rw-r--r--   0        0        0      927 2023-06-28 13:06:09.219789 open_source_insights_api-0.1.6/pyproject.toml
+-rw-r--r--   0        0        0     2280 1970-01-01 00:00:00.000000 open_source_insights_api-0.1.6/PKG-INFO
```

### Comparing `open_source_insights_api-0.1.5/LICENSE` & `open_source_insights_api-0.1.6/LICENSE`

 * *Files identical despite different names*

### Comparing `open_source_insights_api-0.1.5/open_source_insights_api/os_insights.py` & `open_source_insights_api-0.1.6/open_source_insights_api/os_insights.py`

 * *Files 1% similar despite different names*

```diff
@@ -116,15 +116,15 @@
         if self.__CheckSupportedSystem(system_repo):
             pkg_name = urllib.parse.quote_plus(pkg_name)
             url = f'https://api.deps.dev/v3alpha/systems/{system_repo}/packages/{pkg_name}/versions/{pkg_version}:dependencies'
             
             try:
                 r = requests.get(url)
             except:
-                return ConnectionError
+                return {"error": f"Connection with {url}", "status_code": r.status_code}
 
             if r.status_code == 404:
                 return {"error": f"Connection with {url} status invalid", "status_code": r.status_code}
             
             try:
                 r_json = json.loads(r.content)
             except:
```


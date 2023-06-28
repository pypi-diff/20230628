# Comparing `tmp/saagieapi-2.6.0.tar.gz` & `tmp/saagieapi-2.6.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "saagieapi-2.6.0.tar", max compression
+gzip compressed data, was "saagieapi-2.6.1.tar", max compression
```

## Comparing `saagieapi-2.6.0.tar` & `saagieapi-2.6.1.tar`

### file list

```diff
@@ -1,44 +1,44 @@
--rw-r--r--   0        0        0    11357 2023-06-23 14:20:49.337028 saagieapi-2.6.0/LICENSE
--rw-r--r--   0        0        0     4555 2023-06-23 14:20:49.337028 saagieapi-2.6.0/README.md
--rw-r--r--   0        0        0     1562 2023-06-23 14:21:19.237017 saagieapi-2.6.0/pyproject.toml
--rw-r--r--   0        0        0      583 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/__init__.py
--rw-r--r--   0        0        0       43 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/apps/__init__.py
--rw-r--r--   0        0        0    33369 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/apps/apps.py
--rw-r--r--   0        0        0     7591 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/apps/gql_queries.py
--rw-r--r--   0        0        0       83 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/docker_credentials/__init__.py
--rw-r--r--   0        0        0     8465 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/docker_credentials/docker_credentials.py
--rw-r--r--   0        0        0     1657 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/docker_credentials/gql_queries.py
--rw-r--r--   0        0        0       53 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/env_vars/__init__.py
--rw-r--r--   0        0        0    27280 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/env_vars/env_vars.py
--rw-r--r--   0        0        0     2671 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/env_vars/gql_queries.py
--rw-r--r--   0        0        0     4677 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/gql_queries.py
--rw-r--r--   0        0        0       49 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/groups/__init__.py
--rw-r--r--   0        0        0    14568 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/groups/groups.py
--rw-r--r--   0        0        0       43 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/jobs/__init__.py
--rw-r--r--   0        0        0     9510 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/jobs/gql_queries.py
--rw-r--r--   0        0        0    36314 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/jobs/jobs.py
--rw-r--r--   0        0        0      222 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/pipelines/__init__.py
--rw-r--r--   0        0        0     8853 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/pipelines/gql_queries.py
--rw-r--r--   0        0        0     3572 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/pipelines/graph_pipeline.py
--rw-r--r--   0        0        0    30113 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/pipelines/pipelines.py
--rw-r--r--   0        0        0       55 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/profiles/__init__.py
--rw-r--r--   0        0        0     4954 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/profiles/profiles.py
--rw-r--r--   0        0        0       55 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/projects/__init__.py
--rw-r--r--   0        0        0     2962 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/projects/gql_queries.py
--rw-r--r--   0        0        0    24404 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/projects/projects.py
--rw-r--r--   0        0        0       67 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/repositories/__init__.py
--rw-r--r--   0        0        0     8443 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/repositories/gql_queries.py
--rw-r--r--   0        0        0    10534 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/repositories/repositories.py
--rw-r--r--   0        0        0    19545 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/saagie_api.py
--rw-r--r--   0        0        0       55 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/storages/__init__.py
--rw-r--r--   0        0        0     1384 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/storages/gql_queries.py
--rw-r--r--   0        0        0     6561 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/storages/storages.py
--rw-r--r--   0        0        0       46 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/users/__init__.py
--rw-r--r--   0        0        0    10981 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/users/users.py
--rw-r--r--   0        0        0        0 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/utils/__init__.py
--rw-r--r--   0        0        0     1725 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/utils/bearer_auth.py
--rw-r--r--   0        0        0     3969 2023-06-23 14:20:49.345028 saagieapi-2.6.0/saagieapi/utils/folder_functions.py
--rw-r--r--   0        0        0     3113 2023-06-23 14:20:49.349028 saagieapi-2.6.0/saagieapi/utils/gql_client.py
--rw-r--r--   0        0        0     2336 2023-06-23 14:20:49.349028 saagieapi-2.6.0/saagieapi/utils/request_client.py
--rw-r--r--   0        0        0       54 2023-06-23 14:20:49.349028 saagieapi-2.6.0/saagieapi/utils/rich_console.py
--rw-r--r--   0        0        0     5504 1970-01-01 00:00:00.000000 saagieapi-2.6.0/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-28 09:33:57.612337 saagieapi-2.6.1/LICENSE
+-rw-r--r--   0        0        0     4612 2023-06-28 09:33:57.612337 saagieapi-2.6.1/README.md
+-rw-r--r--   0        0        0     1562 2023-06-28 09:34:27.021018 saagieapi-2.6.1/pyproject.toml
+-rw-r--r--   0        0        0      583 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/__init__.py
+-rw-r--r--   0        0        0       43 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/apps/__init__.py
+-rw-r--r--   0        0        0    33369 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/apps/apps.py
+-rw-r--r--   0        0        0     7591 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/apps/gql_queries.py
+-rw-r--r--   0        0        0       83 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/docker_credentials/__init__.py
+-rw-r--r--   0        0        0     8465 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/docker_credentials/docker_credentials.py
+-rw-r--r--   0        0        0     1657 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/docker_credentials/gql_queries.py
+-rw-r--r--   0        0        0       53 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/env_vars/__init__.py
+-rw-r--r--   0        0        0    27280 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/env_vars/env_vars.py
+-rw-r--r--   0        0        0     2671 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/env_vars/gql_queries.py
+-rw-r--r--   0        0        0     4677 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/gql_queries.py
+-rw-r--r--   0        0        0       49 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/groups/__init__.py
+-rw-r--r--   0        0        0    14568 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/groups/groups.py
+-rw-r--r--   0        0        0       43 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/jobs/__init__.py
+-rw-r--r--   0        0        0     9510 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/jobs/gql_queries.py
+-rw-r--r--   0        0        0    36521 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/jobs/jobs.py
+-rw-r--r--   0        0        0      222 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/pipelines/__init__.py
+-rw-r--r--   0        0        0     8853 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/pipelines/gql_queries.py
+-rw-r--r--   0        0        0     3572 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/pipelines/graph_pipeline.py
+-rw-r--r--   0        0        0    30113 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/pipelines/pipelines.py
+-rw-r--r--   0        0        0       55 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/profiles/__init__.py
+-rw-r--r--   0        0        0     4954 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/profiles/profiles.py
+-rw-r--r--   0        0        0       55 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/projects/__init__.py
+-rw-r--r--   0        0        0     2962 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/projects/gql_queries.py
+-rw-r--r--   0        0        0    24404 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/projects/projects.py
+-rw-r--r--   0        0        0       67 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/repositories/__init__.py
+-rw-r--r--   0        0        0     8443 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/repositories/gql_queries.py
+-rw-r--r--   0        0        0    10534 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/repositories/repositories.py
+-rw-r--r--   0        0        0    19545 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/saagie_api.py
+-rw-r--r--   0        0        0       55 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/storages/__init__.py
+-rw-r--r--   0        0        0     1384 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/storages/gql_queries.py
+-rw-r--r--   0        0        0     6561 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/storages/storages.py
+-rw-r--r--   0        0        0       46 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/users/__init__.py
+-rw-r--r--   0        0        0    10981 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/users/users.py
+-rw-r--r--   0        0        0        0 2023-06-28 09:33:57.616337 saagieapi-2.6.1/saagieapi/utils/__init__.py
+-rw-r--r--   0        0        0     1725 2023-06-28 09:33:57.620337 saagieapi-2.6.1/saagieapi/utils/bearer_auth.py
+-rw-r--r--   0        0        0     3969 2023-06-28 09:33:57.620337 saagieapi-2.6.1/saagieapi/utils/folder_functions.py
+-rw-r--r--   0        0        0     3113 2023-06-28 09:33:57.620337 saagieapi-2.6.1/saagieapi/utils/gql_client.py
+-rw-r--r--   0        0        0     2336 2023-06-28 09:33:57.620337 saagieapi-2.6.1/saagieapi/utils/request_client.py
+-rw-r--r--   0        0        0       54 2023-06-28 09:33:57.620337 saagieapi-2.6.1/saagieapi/utils/rich_console.py
+-rw-r--r--   0        0        0     5561 1970-01-01 00:00:00.000000 saagieapi-2.6.1/PKG-INFO
```

### Comparing `saagieapi-2.6.0/LICENSE` & `saagieapi-2.6.1/LICENSE`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/README.md` & `saagieapi-2.6.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -34,14 +34,15 @@
 ### Compatibility with your Saagie platform
 
 | **Saagie platform version** | **saagie-api release** |
 |-----------------------------|------------------------|
 | < 2.2.0                     | < 0.6.0                |
 | >= 2.2.0                    | >= 0.6.0               |
 | >= 2023.01                  | >= 2.4.0               |
+| >= 2023.02                  | >= 2.6.0               |
 
 ## Usage
 
 All the implemented features are documented in the [Wiki](https://github.com/saagie/api-saagie/wiki)
 
 Here's a full example of how to use the API:
```

### Comparing `saagieapi-2.6.0/pyproject.toml` & `saagieapi-2.6.1/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "saagieapi"
-version = "2.6.0"
+version = "2.6.1"
 description = "Python API to interact with Saagie"
 authors = ["Saagie"]
 license = "GLWTPL"
 readme = "README.md"
 repository = "https://github.com/saagie/api-saagie"
 
 [tool.poetry.dependencies]
```

### Comparing `saagieapi-2.6.0/saagieapi/__init__.py` & `saagieapi-2.6.1/saagieapi/__init__.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/apps/apps.py` & `saagieapi-2.6.1/saagieapi/apps/apps.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/apps/gql_queries.py` & `saagieapi-2.6.1/saagieapi/apps/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/docker_credentials/docker_credentials.py` & `saagieapi-2.6.1/saagieapi/docker_credentials/docker_credentials.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/docker_credentials/gql_queries.py` & `saagieapi-2.6.1/saagieapi/docker_credentials/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/env_vars/env_vars.py` & `saagieapi-2.6.1/saagieapi/env_vars/env_vars.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/env_vars/gql_queries.py` & `saagieapi-2.6.1/saagieapi/env_vars/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/gql_queries.py` & `saagieapi-2.6.1/saagieapi/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/groups/groups.py` & `saagieapi-2.6.1/saagieapi/groups/groups.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/jobs/gql_queries.py` & `saagieapi-2.6.1/saagieapi/jobs/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/jobs/jobs.py` & `saagieapi-2.6.1/saagieapi/jobs/jobs.py`

 * *Files 0% similar despite different names*

```diff
@@ -616,26 +616,27 @@
 
         job_list = self.saagie_api.jobs.list_for_project_minimal(project_id)["jobs"]
         job_names = [job["name"] for job in job_list]
 
         if job_name in job_names:
             job_id = [job["id"] for job in job_list if job["name"] == job_name][0]
 
-            responses = {}
-
-            responses["addJobVersion"] = self.upgrade(
-                job_id=job_id,
-                file=file,
-                use_previous_artifact=True,
-                runtime_version=runtime_version,
-                command_line=command_line,
-                release_note=release_note,
-                extra_technology=extra_technology,
-                extra_technology_version=extra_technology_version,
-            )["data"]["addJobVersion"]
+            use_previous_artifact = not file
+            responses = {
+                "addJobVersion": self.upgrade(
+                    job_id=job_id,
+                    file=file,
+                    use_previous_artifact=use_previous_artifact,
+                    runtime_version=runtime_version,
+                    command_line=command_line,
+                    release_note=release_note,
+                    extra_technology=extra_technology,
+                    extra_technology_version=extra_technology_version,
+                )["data"]["addJobVersion"]
+            }
 
             responses["editJob"] = self.edit(
                 job_id=job_id,
                 job_name=job_name,
                 description=description,
                 is_scheduled=is_scheduled,
                 cron_scheduling=cron_scheduling,
@@ -805,15 +806,17 @@
             variable values to pass to the GQL request
         Returns
         -------
         dict
             Dict of the request response
         """
         if file:
-            file = Path(file)
+            file_info = os.path.split(os.path.abspath(file))
+            os.chdir(file_info[0])
+            file = Path(file_info[-1])
             with file.open(mode="rb") as file_content:
                 params["file"] = file_content
                 try:
                     req = self.saagie_api.client.execute(
                         query=gql(payload_str), variable_values=params, upload_files=True
                     )
                     res = {"data": req}
```

### Comparing `saagieapi-2.6.0/saagieapi/pipelines/gql_queries.py` & `saagieapi-2.6.1/saagieapi/pipelines/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/pipelines/graph_pipeline.py` & `saagieapi-2.6.1/saagieapi/pipelines/graph_pipeline.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/pipelines/pipelines.py` & `saagieapi-2.6.1/saagieapi/pipelines/pipelines.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/profiles/profiles.py` & `saagieapi-2.6.1/saagieapi/profiles/profiles.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/projects/gql_queries.py` & `saagieapi-2.6.1/saagieapi/projects/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/projects/projects.py` & `saagieapi-2.6.1/saagieapi/projects/projects.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/repositories/gql_queries.py` & `saagieapi-2.6.1/saagieapi/repositories/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/repositories/repositories.py` & `saagieapi-2.6.1/saagieapi/repositories/repositories.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/saagie_api.py` & `saagieapi-2.6.1/saagieapi/saagie_api.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/storages/gql_queries.py` & `saagieapi-2.6.1/saagieapi/storages/gql_queries.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/storages/storages.py` & `saagieapi-2.6.1/saagieapi/storages/storages.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/users/users.py` & `saagieapi-2.6.1/saagieapi/users/users.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/utils/bearer_auth.py` & `saagieapi-2.6.1/saagieapi/utils/bearer_auth.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/utils/folder_functions.py` & `saagieapi-2.6.1/saagieapi/utils/folder_functions.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/utils/gql_client.py` & `saagieapi-2.6.1/saagieapi/utils/gql_client.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/saagieapi/utils/request_client.py` & `saagieapi-2.6.1/saagieapi/utils/request_client.py`

 * *Files identical despite different names*

### Comparing `saagieapi-2.6.0/PKG-INFO` & `saagieapi-2.6.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: saagieapi
-Version: 2.6.0
+Version: 2.6.1
 Summary: Python API to interact with Saagie
 Home-page: https://github.com/saagie/api-saagie
 License: GLWTPL
 Author: Saagie
 Requires-Python: >=3.7,<4.0
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
@@ -59,14 +59,15 @@
 ### Compatibility with your Saagie platform
 
 | **Saagie platform version** | **saagie-api release** |
 |-----------------------------|------------------------|
 | < 2.2.0                     | < 0.6.0                |
 | >= 2.2.0                    | >= 0.6.0               |
 | >= 2023.01                  | >= 2.4.0               |
+| >= 2023.02                  | >= 2.6.0               |
 
 ## Usage
 
 All the implemented features are documented in the [Wiki](https://github.com/saagie/api-saagie/wiki)
 
 Here's a full example of how to use the API:
```


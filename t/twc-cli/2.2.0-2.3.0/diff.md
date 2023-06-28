# Comparing `tmp/twc_cli-2.2.0.tar.gz` & `tmp/twc_cli-2.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "twc_cli-2.2.0.tar", max compression
+gzip compressed data, was "twc_cli-2.3.0.tar", max compression
```

## Comparing `twc_cli-2.2.0.tar` & `twc_cli-2.3.0.tar`

### file list

```diff
@@ -1,29 +1,30 @@
--rw-r--r--   0        0        0    19087 2023-06-07 15:44:59.845737 twc_cli-2.2.0/CHANGELOG.md
--rw-r--r--   0        0        0     1089 2023-02-27 16:18:31.000000 twc_cli-2.2.0/COPYING
--rw-r--r--   0        0        0      846 2023-06-06 19:20:41.558226 twc_cli-2.2.0/README.md
--rw-r--r--   0        0        0     1149 2023-06-07 15:45:06.045728 twc_cli-2.2.0/pyproject.toml
--rw-r--r--   0        0        0      113 2023-04-15 16:24:43.813223 twc_cli-2.2.0/twc/__init__.py
--rw-r--r--   0        0        0     1912 2023-06-07 15:35:21.777027 twc_cli-2.2.0/twc/__main__.py
--rw-r--r--   0        0        0      442 2023-06-07 15:45:14.505715 twc_cli-2.2.0/twc/__version__.py
--rw-r--r--   0        0        0      128 2023-04-27 07:49:09.917167 twc_cli-2.2.0/twc/api/__init__.py
--rw-r--r--   0        0        0     7781 2023-04-27 07:33:17.311019 twc_cli-2.2.0/twc/api/base.py
--rw-r--r--   0        0        0    38586 2023-06-07 15:35:21.777027 twc_cli-2.2.0/twc/api/client.py
--rw-r--r--   0        0        0     2279 2023-05-19 15:20:48.515105 twc_cli-2.2.0/twc/api/exceptions.py
--rw-r--r--   0        0        0     3499 2023-06-07 15:35:21.777027 twc_cli-2.2.0/twc/api/types.py
--rw-r--r--   0        0        0     2702 2023-04-27 08:25:15.189605 twc_cli-2.2.0/twc/apiwrap.py
--rw-r--r--   0        0        0      274 2023-06-07 15:35:21.777027 twc_cli-2.2.0/twc/commands/__init__.py
--rw-r--r--   0        0        0     5253 2023-05-01 16:59:46.116990 twc_cli-2.2.0/twc/commands/account.py
--rw-r--r--   0        0        0    19714 2023-06-07 15:37:36.003274 twc_cli-2.2.0/twc/commands/balancer.py
--rw-r--r--   0        0        0     7687 2023-06-06 14:43:15.085812 twc_cli-2.2.0/twc/commands/common.py
--rw-r--r--   0        0        0     8054 2023-05-01 17:04:38.382594 twc_cli-2.2.0/twc/commands/config.py
--rw-r--r--   0        0        0    16052 2023-05-02 19:59:22.542511 twc_cli-2.2.0/twc/commands/database.py
--rw-r--r--   0        0        0     8522 2023-05-02 19:59:29.622954 twc_cli-2.2.0/twc/commands/image.py
--rw-r--r--   0        0        0    10798 2023-05-02 22:28:14.925192 twc_cli-2.2.0/twc/commands/project.py
--rw-r--r--   0        0        0    67719 2023-06-06 14:43:15.085812 twc_cli-2.2.0/twc/commands/server.py
--rw-r--r--   0        0        0     7941 2023-05-01 17:10:37.824666 twc_cli-2.2.0/twc/commands/ssh_key.py
--rw-r--r--   0        0        0    19216 2023-05-01 17:12:04.101034 twc_cli-2.2.0/twc/commands/storage.py
--rw-r--r--   0        0        0     6148 2023-04-17 22:18:55.659001 twc_cli-2.2.0/twc/fmt.py
--rw-r--r--   0        0        0     6580 2023-05-01 20:29:58.139390 twc_cli-2.2.0/twc/typerx.py
--rw-r--r--   0        0        0      651 2023-04-29 21:55:47.435595 twc_cli-2.2.0/twc/utils.py
--rw-r--r--   0        0        0      552 2023-06-06 14:43:15.085812 twc_cli-2.2.0/twc/vars.py
--rw-r--r--   0        0        0     1772 1970-01-01 00:00:00.000000 twc_cli-2.2.0/PKG-INFO
+-rw-r--r--   0        0        0    19635 2023-06-28 13:40:10.269068 twc_cli-2.3.0/CHANGELOG.md
+-rw-r--r--   0        0        0     1089 2023-02-27 16:18:31.000000 twc_cli-2.3.0/COPYING
+-rw-r--r--   0        0        0      846 2023-06-06 19:20:41.558226 twc_cli-2.3.0/README.md
+-rw-r--r--   0        0        0     1183 2023-06-28 13:46:55.237091 twc_cli-2.3.0/pyproject.toml
+-rw-r--r--   0        0        0      113 2023-04-15 16:24:43.813223 twc_cli-2.3.0/twc/__init__.py
+-rw-r--r--   0        0        0     2013 2023-06-28 13:05:46.981902 twc_cli-2.3.0/twc/__main__.py
+-rw-r--r--   0        0        0      442 2023-06-28 13:47:04.703716 twc_cli-2.3.0/twc/__version__.py
+-rw-r--r--   0        0        0      128 2023-04-27 07:49:09.917167 twc_cli-2.3.0/twc/api/__init__.py
+-rw-r--r--   0        0        0     7975 2023-06-28 13:35:47.370613 twc_cli-2.3.0/twc/api/base.py
+-rw-r--r--   0        0        0    44894 2023-06-28 13:45:56.694024 twc_cli-2.3.0/twc/api/client.py
+-rw-r--r--   0        0        0     2369 2023-06-28 13:34:00.701335 twc_cli-2.3.0/twc/api/exceptions.py
+-rw-r--r--   0        0        0     3499 2023-06-27 16:16:24.590437 twc_cli-2.3.0/twc/api/types.py
+-rw-r--r--   0        0        0     2780 2023-06-28 13:35:25.240757 twc_cli-2.3.0/twc/apiwrap.py
+-rw-r--r--   0        0        0      306 2023-06-28 13:05:46.985236 twc_cli-2.3.0/twc/commands/__init__.py
+-rw-r--r--   0        0        0     5253 2023-05-01 16:59:46.116990 twc_cli-2.3.0/twc/commands/account.py
+-rw-r--r--   0        0        0    20070 2023-06-28 13:28:24.980539 twc_cli-2.3.0/twc/commands/balancer.py
+-rw-r--r--   0        0        0     7687 2023-06-06 14:43:15.085812 twc_cli-2.3.0/twc/commands/common.py
+-rw-r--r--   0        0        0     8057 2023-06-15 10:34:48.291911 twc_cli-2.3.0/twc/commands/config.py
+-rw-r--r--   0        0        0    16052 2023-05-02 19:59:22.542511 twc_cli-2.3.0/twc/commands/database.py
+-rw-r--r--   0        0        0     8522 2023-05-02 19:59:29.622954 twc_cli-2.3.0/twc/commands/image.py
+-rw-r--r--   0        0        0    20870 2023-06-28 13:45:18.607533 twc_cli-2.3.0/twc/commands/kubernetes.py
+-rw-r--r--   0        0        0    10798 2023-05-02 22:28:14.925192 twc_cli-2.3.0/twc/commands/project.py
+-rw-r--r--   0        0        0    67719 2023-06-06 14:43:15.085812 twc_cli-2.3.0/twc/commands/server.py
+-rw-r--r--   0        0        0     7941 2023-06-28 13:14:57.259823 twc_cli-2.3.0/twc/commands/ssh_key.py
+-rw-r--r--   0        0        0    19216 2023-06-12 07:01:01.835873 twc_cli-2.3.0/twc/commands/storage.py
+-rw-r--r--   0        0        0     6148 2023-04-17 22:18:55.659001 twc_cli-2.3.0/twc/fmt.py
+-rw-r--r--   0        0        0     6580 2023-05-01 20:29:58.139390 twc_cli-2.3.0/twc/typerx.py
+-rw-r--r--   0        0        0      651 2023-04-29 21:55:47.435595 twc_cli-2.3.0/twc/utils.py
+-rw-r--r--   0        0        0      560 2023-06-12 06:43:28.675413 twc_cli-2.3.0/twc/vars.py
+-rw-r--r--   0        0        0     1772 1970-01-01 00:00:00.000000 twc_cli-2.3.0/PKG-INFO
```

### Comparing `twc_cli-2.2.0/CHANGELOG.md` & `twc_cli-2.3.0/CHANGELOG.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,27 @@
 # Релизы Timeweb Cloud CLI
 
 В этом файле описаны все значимые изменения в Timeweb Cloud CLI. В выпусках мы придерживается правил [семантического версионирования](https://semver.org/lang/ru/).
 
+# Версия 2.3.0 (2023.06.28)
+
+## Добавлено
+
+- Добавлено управление кластерами Kubernetes — команда `twc cluster`, алиасы: `clusters`, `kubernetes`, `k8s`.
+
+## Изменено
+
+- Улучшена обработка ошибок HTTP.
+- Улучшена валидания пользозвательского ввода.
+
+## Исправлено
+
+- Изменён порядок аргументов у команды `twc ssh-key add`.
+- Исправления мелких ошибок.
+
 # Версия 2.2.0 (2023.06.07)
 
 ## Добавлено
 
 - Добавлена команда `balancer` для управления балансировщиками нагрузки.
 
 # Версия 2.1.1 (2023.06.07)
```

### Comparing `twc_cli-2.2.0/COPYING` & `twc_cli-2.3.0/COPYING`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/README.md` & `twc_cli-2.3.0/README.md`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/pyproject.toml` & `twc_cli-2.3.0/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "twc-cli"
-version = "2.2.0"
+version = "2.3.0"
 description = "Timeweb Cloud Command Line Interface."
 authors = ["ge <dev@timeweb.cloud>"]
 homepage = "https://github.com/timeweb-cloud/twc"
 repository = "https://github.com/timeweb-cloud/twc"
 license="MIT"
 readme = "README.md"
 include = ["CHANGELOG.md", "COPYING"]
@@ -43,8 +43,9 @@
     "too-many-statements",
     "too-many-arguments",
     "too-many-locals",
     "too-many-lines",
     "unused-argument",  # unused 'verbose' arg is OK
     "duplicate-code",
     "invalid-name",
+    "missing-function-docstring",
 ]
```

### Comparing `twc_cli-2.2.0/twc/__main__.py` & `twc_cli-2.3.0/twc/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,28 +12,32 @@
     server,
     ssh_key,
     image,
     project,
     database,
     storage,
     balancer,
+    cluster,
 )
 from .commands.common import version_callback, version_option, verbose_option
 
 
 cli = TyperAlias(help=__doc__)
 cli.add_typer(config, name="config")
 cli.add_typer(account, name="account")
 cli.add_typer(server, name="server", aliases=["servers", "s"])
 cli.add_typer(ssh_key, name="ssh-key", aliases=["ssh-keys", "k"])
 cli.add_typer(image, name="image", aliases=["images", "i"])
 cli.add_typer(project, name="project", aliases=["projects", "p"])
 cli.add_typer(database, name="database", aliases=["databases", "db"])
 cli.add_typer(storage, name="storage", aliases=["storages", "s3"])
 cli.add_typer(balancer, name="balancer", aliases=["balancers", "lb"])
+cli.add_typer(
+    cluster, name="cluster", aliases=["clusters", "kubernetes", "k8s"]
+)
 
 
 @cli.command("version")
 def version_command():
     """Show version and exit."""
     version_callback(True)
```

### Comparing `twc_cli-2.2.0/twc/api/base.py` & `twc_cli-2.3.0/twc/api/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -59,15 +59,15 @@
     def _secure_log(self, headers: dict) -> dict:
         """Replace API access token with placeholder."""
         _headers = headers.copy()
         if self.hide_token:
             _headers["Authorization"] = "Bearer <SENSITIVE_DATA_DELETED>"
         return _headers
 
-    def _log_request(self, response: requests.Request) -> None:
+    def _log_request(self, response: requests.Response) -> None:
         """Log HTTP requests."""
         if self.log_response_body:
             res_body = response.text or "<NO_BODY>"
         else:
             res_body = "<NOT_LOGGED>"
 
         self.log.debug(
@@ -113,24 +113,27 @@
 
         if not headers:
             headers = self.headers
 
         _headers = self._secure_log(headers)
         self.log.debug("Called with args: %s %s %s", method, url, _headers)
 
-        response = requests.request(
-            method,
-            url,
-            headers=headers,
-            params=params,
-            data=data,
-            json=json,
-            files=files,
-            timeout=timeout,
-        )
+        try:
+            response = requests.request(
+                method,
+                url,
+                headers=headers,
+                params=params,
+                data=data,
+                json=json,
+                files=files,
+                timeout=timeout,
+            )
+        except requests.exceptions.ConnectionError as conerr:
+            raise exc.NetworkError(f"Coul'd not connect to server: {conerr}")
 
         try:
             response.raise_for_status()
             self._log_request(response)
         except requests.HTTPError as e:
             self.log_response_body = True  # Always log response body on errors
             self._log_request(response)
```

### Comparing `twc_cli-2.2.0/twc/api/client.py` & `twc_cli-2.3.0/twc/api/client.py`

 * *Files 4% similar despite different names*

```diff
@@ -863,15 +863,15 @@
         is_public: Optional[bool] = None,
     ):
         """Update storage bucket."""
         self.headers.update({"Content-Type": "application/json"})
         payload = {
             **({"preset_id": preset_id} if preset_id else {}),
             **(
-                {"type": "public" if is_public else "private"}
+                {"bucket_type": "public" if is_public else "private"}
                 if is_public is not None
                 else {}
             ),
         }
         return self._request(
             "PATCH",
             f"{self.api_url}/storages/buckets/{bucket_id}",
@@ -1144,7 +1144,206 @@
             "DELETE",
             f"{self.api_url}/balancers/{balancer_id}/rules/{rule_id}",
         )
 
     def get_load_balancer_presets(self):
         """Get list of LB presets."""
         return self._request("GET", f"{self.api_url}/presets/balancers")
+
+    # -----------------------------------------------------------------------
+    # Kubernetes
+
+    def get_k8s_clusters(self, limit: int = 100, offset: int = 0):
+        """Get list of Kubernetes clusters."""
+        params = {"limit": limit, "offset": offset}
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters",
+            params=params,
+        )
+
+    def get_k8s_cluster(self, cluster_id: int):
+        """Get Kubernetes cluster info."""
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}",
+        )
+
+    def create_k8s_cluster(
+        self,
+        name: str,
+        k8s_version: str,
+        network_driver: str,
+        preset_id: int,
+        description: Optional[str] = None,
+        ingress: bool = True,
+        worker_groups: Optional[list] = None,
+    ):
+        """Create Kubernetes cluster. Default worker groups::
+
+            [{"name":"default","preset_id":399,"node_count":1}]
+
+        preset_id in worker_groups is worker node preset_id.
+
+        API also have `ha=False` field, but it is not functional. It means
+        master node replicas. By default master node have not any replicas.
+        """
+        payload = {
+            "name": name,
+            "description": description or "",
+            "ha": False,
+            "k8s_version": k8s_version,
+            "network_driver": network_driver,
+            "ingress": ingress,
+            "preset_id": preset_id,
+            **(
+                {"worker_groups": worker_groups}
+                if worker_groups is not None
+                else {}
+            ),
+        }
+        return self._request(
+            "POST",
+            f"{self.api_url}/k8s/clusters",
+            json=payload,
+        )
+
+    def delete_k8s_cluster(
+        self,
+        cluster_id: int,
+        delete_hash: Optional[str] = None,
+        code: Optional[int] = None,
+    ):
+        """Delete Kubernetes cluster."""
+        params = {
+            **({"hash": delete_hash} if delete_hash else {}),
+            **({"code": code} if code else {}),
+        }
+        return self._request(
+            "DELETE",
+            f"{self.api_url}/k8s/clusters/{cluster_id}",
+            params=params,
+        )
+
+    def update_k8s_cluster(self, cluster_id: int, description: str):
+        """Update Kubernetes cluster properties."""
+        payload = {
+            "description": description,
+        }
+        return self._request(
+            "PATCH",
+            f"{self.api_url}/k8s/clusters/{cluster_id}",
+            json=payload,
+        )
+
+    def get_k8s_cluster_resources(self, cluster_id: int):
+        """Return cluster resources status."""
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/resources",
+        )
+
+    def get_k8s_cluster_kubeconfig(self, cluster_id: int):
+        """Download kubeconfig for kubecctl util. API respond
+        with application/yaml data.
+        """
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/kubeconfig",
+        )
+
+    def get_k8s_node_groups(self, cluster_id: int):
+        """Get list of worker nodes groups."""
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups",
+        )
+
+    def get_k8s_node_group(self, cluster_id: int, group_id: int):
+        """Get nodes group info."""
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups/{group_id}",
+        )
+
+    def create_k8s_node_group(
+        self,
+        cluster_id: int,
+        name: str,
+        preset_id: int,
+        node_count: int,
+    ):
+        """Add new worker nodes group into Kubernetes cluster."""
+        payload = {
+            "name": name,
+            "preset_id": preset_id,
+            "node_count": node_count,
+        }
+        return self._request(
+            "POST",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups",
+            json=payload,
+        )
+
+    def delete_k8s_node_group(self, cluster_id: int, group_id: int):
+        """Delete cluster nodes group."""
+        return self._request(
+            "DELETE",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups/{group_id}",
+        )
+
+    def get_k8s_nodes_by_group(
+        self, cluster_id: int, group_id: int, limit: int = 100, offset: int = 0
+    ):
+        """Get list of Kubernetes nodes group nodes."""
+        params = {"limit": limit, "offset": offset}
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups/{group_id}/nodes",
+            params=params,
+        )
+
+    def add_k8s_nodes_to_group(
+        self, cluster_id: int, group_id: int, count: int = 0
+    ):
+        """Add new nodes to nodes group."""
+        return self._request(
+            "POST",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups/{group_id}/nodes",
+            json={"count": count},
+        )
+
+    def delete_k8s_nodes_from_group(
+        self, cluster_id: int, group_id: int, count: int = 0
+    ):
+        """Delete nodes from nodes group."""
+        return self._request(
+            "DELETE",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/groups/{group_id}/nodes",
+            json={"count": count},
+        )
+
+    def get_k8s_nodes(self, cluster_id: int):
+        """Get list of Kubernetes nodes."""
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/nodes",
+        )
+
+    def delete_k8s_node(self, cluster_id: int, node_id: int):
+        """Delete node from cluster."""
+        return self._request(
+            "GET",
+            f"{self.api_url}/k8s/clusters/{cluster_id}/nodes/{node_id}",
+        )
+
+    def get_k8s_versions(self):
+        """List available Kubernetes versions."""
+        return self._request("GET", f"{self.api_url}/k8s/k8s_versions")
+
+    def get_k8s_network_drivers(self):
+        """List available Kubernetes network drivers."""
+        return self._request("GET", f"{self.api_url}/k8s/network_drivers")
+
+    def get_k8s_presets(self):
+        """List available Kubernetes nodes presets."""
+        return self._request("GET", f"{self.api_url}/presets/k8s")
```

### Comparing `twc_cli-2.2.0/twc/api/exceptions.py` & `twc_cli-2.3.0/twc/api/exceptions.py`

 * *Files 3% similar despite different names*

```diff
@@ -84,7 +84,11 @@
 
 class TooManyRequestsError(TimewebCloudException):
     """429 Too Many Requests."""
 
 
 class InternalServerError(TimewebCloudException):
     """500 Internal Server Error."""
+
+
+class NetworkError(Exception):
+    """Raises on requests.exceptions.ConnectionError."""
```

### Comparing `twc_cli-2.2.0/twc/api/types.py` & `twc_cli-2.3.0/twc/api/types.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/apiwrap.py` & `twc_cli-2.3.0/twc/apiwrap.py`

 * *Files 4% similar despite different names*

```diff
@@ -15,14 +15,16 @@
     """Error handler decorator for requests. Wrap API exceptions
     and exit with human-readable error message.
     """
 
     def wrapper(self, *args, **kwargs):
         try:
             return func(self, *args, **kwargs)
+        except exc.NetworkError as err:
+            sys.exit(f"Error: {err}")
         except exc.UnauthorizedError as err:
             sys.exit(
                 textwrap.dedent(
                     f"""
                     Error: {err}
                     Please check your API access token. Try run 'twc config'
                     """
```

### Comparing `twc_cli-2.2.0/twc/commands/account.py` & `twc_cli-2.3.0/twc/commands/account.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/commands/balancer.py` & `twc_cli-2.3.0/twc/commands/balancer.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 """Manage load balancers."""
 
+import re
 import sys
 from typing import Optional, List
 from pathlib import Path
 from logging import debug
 
 import typer
 from requests import Response
@@ -476,14 +477,19 @@
 # $ twc balancer rule add                                       #
 # ------------------------------------------------------------- #
 
 
 def port_proto_callback(value):
     """Typer callback for PORT/PROTO validation."""
     if value:
+        if not re.match(r"^\d+\/(http|http2|https|tcp)$", value):
+            sys.exit(
+                f"Error: Malformed argument: '{value}': "
+                "Correct patterns: '443/https', '2000/tcp', etc."
+            )
         port, proto = value.split("/")
         if port.isdigit():
             port = int(port)
         else:
             raise typer.BadParameter("Port number must be integer.")
         try:
             LoadBalancerProto(proto)
@@ -499,19 +505,21 @@
     verbose: Optional[bool] = verbose_option,
     config: Optional[Path] = config_option,
     profile: Optional[str] = profile_option,
     output_format: Optional[str] = output_format_option,
     frontend: str = typer.Option(
         ...,
         callback=port_proto_callback,
+        metavar="PORT/PROTO",
         help="Frontend port and protocol.",
     ),
     backend: str = typer.Option(
         ...,
         callback=port_proto_callback,
+        metavar="PORT/PROTO",
         help="Backend port and protocol.",
     ),
 ):
     """Add load balancer rule."""
     client = create_client(config, profile)
 
     f_port, f_proto = frontend
@@ -555,19 +563,21 @@
     verbose: Optional[bool] = verbose_option,
     config: Optional[Path] = config_option,
     profile: Optional[str] = profile_option,
     output_format: Optional[str] = output_format_option,
     frontend: Optional[str] = typer.Option(
         None,
         callback=port_proto_callback,
+        metavar="PORT/PROTO",
         help="Frontend port and protocol.",
     ),
     backend: Optional[str] = typer.Option(
         None,
         callback=port_proto_callback,
+        metavar="PORT/PROTO",
         help="Backend port and protocol.",
     ),
 ):
     """Update load balancer rule."""
     client = create_client(config, profile)
 
     f_port = f_proto = None
```

### Comparing `twc_cli-2.2.0/twc/commands/common.py` & `twc_cli-2.3.0/twc/commands/common.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/commands/config.py` & `twc_cli-2.3.0/twc/commands/config.py`

 * *Files 0% similar despite different names*

```diff
@@ -198,15 +198,15 @@
 # $ twc config set                                              #
 # ------------------------------------------------------------- #
 
 
 def validate_params_callback(value: list) -> list:
     """Validate CLI configuration parameters."""
     for param in value:
-        if not re.match(r"^[a-z0-9_]+=[a-z0-9]+$", param, re.I):
+        if not re.match(r"^[a-z0-9_]+=[a-z0-9-_.]+$", param, re.I):
             raise typer.BadParameter(
                 f"'{param}': Parameter must be a KEY=VALUE pair."
             )
     return value
 
 
 @config.command("set")
```

### Comparing `twc_cli-2.2.0/twc/commands/database.py` & `twc_cli-2.3.0/twc/commands/database.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/commands/image.py` & `twc_cli-2.3.0/twc/commands/image.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/commands/project.py` & `twc_cli-2.3.0/twc/commands/project.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/commands/server.py` & `twc_cli-2.3.0/twc/commands/server.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/commands/ssh_key.py` & `twc_cli-2.3.0/twc/commands/ssh_key.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -201,16 +201,16 @@
 # ------------------------------------------------------------- #
 # $ twc ssh-key add                                             #
 # ------------------------------------------------------------- #
 
 
 @ssh_key.command("add", "copy")
 def ssh_key_add(
-    ssh_keys_ids: List[int] = typer.Argument(..., metavar="SSH_KEY_ID..."),
     server_id: int = typer.Argument(...),
+    ssh_keys_ids: List[int] = typer.Argument(..., metavar="SSH_KEY_ID..."),
     verbose: Optional[bool] = verbose_option,
     config: Optional[Path] = config_option,
     profile: Optional[str] = profile_option,
 ):
     """Copy SSH-keys to Cloud Server."""
     client = create_client(config, profile)
     response = client.add_ssh_key_to_server(server_id, ssh_keys_ids)
```

### Comparing `twc_cli-2.2.0/twc/commands/storage.py` & `twc_cli-2.3.0/twc/commands/storage.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -468,16 +468,16 @@
             ]
         )
     table.print()
 
 
 @storage_subdomain.command("add")
 def storage_subdomain_add(
-    subdomains: List[str] = typer.Argument(..., metavar="SUBDOMAIN..."),
     bucket: str = typer.Argument(...),
+    subdomains: List[str] = typer.Argument(..., metavar="SUBDOMAIN..."),
     verbose: Optional[bool] = verbose_option,
     config: Optional[Path] = config_option,
     profile: Optional[str] = profile_option,
     output_format: Optional[str] = output_format_option,
 ):
     """Attach subdomains to bucket."""
     client = create_client(config, profile)
```

### Comparing `twc_cli-2.2.0/twc/fmt.py` & `twc_cli-2.3.0/twc/fmt.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/typerx.py` & `twc_cli-2.3.0/twc/typerx.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/utils.py` & `twc_cli-2.3.0/twc/utils.py`

 * *Files identical despite different names*

### Comparing `twc_cli-2.2.0/twc/vars.py` & `twc_cli-2.3.0/twc/vars.py`

 * *Files 2% similar despite different names*

```diff
@@ -7,9 +7,9 @@
 CONTROL_PANEL_URL = "https://timeweb.cloud/my"
 S3_ENDPOINT = "s3.timeweb.com"
 
 # Location specific parameters. May change later.
 REGIONS_WITH_CONFIGURATOR = ["ru-1", "ru-2", "pl-1", "kz-1", "nl-1"]
 REGIONS_WITH_IPV6 = ["ru-1", "pl-1"]
 REGIONS_WITH_IMAGES = ["ru-1"]
-REGIONS_WITH_LAN = ["ru-1"]
+REGIONS_WITH_LAN = ["ru-1", "pl-1"]
 REGIONS_WITH_DBAAS = ["ru-1", "pl-1"]
```

### Comparing `twc_cli-2.2.0/PKG-INFO` & `twc_cli-2.3.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: twc-cli
-Version: 2.2.0
+Version: 2.3.0
 Summary: Timeweb Cloud Command Line Interface.
 Home-page: https://github.com/timeweb-cloud/twc
 License: MIT
 Author: ge
 Author-email: dev@timeweb.cloud
 Requires-Python: >=3.7.9,<4.0.0
 Classifier: License :: OSI Approved :: MIT License
```


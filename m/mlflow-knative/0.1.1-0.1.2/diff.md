# Comparing `tmp/mlflow_knative-0.1.1.tar.gz` & `tmp/mlflow_knative-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mlflow_knative-0.1.1.tar", max compression
+gzip compressed data, was "mlflow_knative-0.1.2.tar", max compression
```

## Comparing `mlflow_knative-0.1.1.tar` & `mlflow_knative-0.1.2.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0     1085 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/LICENSE.md
--rw-r--r--   0        0        0     4304 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/README.md
--rw-r--r--   0        0        0      506 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/mlflow_knative/__init__.py
--rw-r--r--   0        0        0    13077 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/mlflow_knative/deployment_client.py
--rw-r--r--   0        0        0     5359 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/mlflow_knative/knative.py
--rw-r--r--   0        0        0     1676 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/mlflow_knative/mlflow_docker.py
--rw-r--r--   0        0        0      808 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/mlflow_knative/service.yaml
--rw-r--r--   0        0        0     1089 2023-06-28 12:26:50.837706 mlflow_knative-0.1.1/mlflow_knative/templating.py
--rw-r--r--   0        0        0     1459 2023-06-28 12:26:50.838706 mlflow_knative-0.1.1/pyproject.toml
--rw-r--r--   0        0        0     5178 1970-01-01 00:00:00.000000 mlflow_knative-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1085 2023-06-28 15:55:30.133868 mlflow_knative-0.1.2/LICENSE.md
+-rw-r--r--   0        0        0     4304 2023-06-28 15:55:30.133868 mlflow_knative-0.1.2/README.md
+-rw-r--r--   0        0        0      506 2023-06-28 15:55:30.134868 mlflow_knative-0.1.2/mlflow_knative/__init__.py
+-rw-r--r--   0        0        0    13488 2023-06-28 15:55:30.134868 mlflow_knative-0.1.2/mlflow_knative/deployment_client.py
+-rw-r--r--   0        0        0     5759 2023-06-28 15:55:30.134868 mlflow_knative-0.1.2/mlflow_knative/knative.py
+-rw-r--r--   0        0        0     1676 2023-06-28 15:55:30.134868 mlflow_knative-0.1.2/mlflow_knative/mlflow_docker.py
+-rw-r--r--   0        0        0      808 2023-06-28 15:55:30.134868 mlflow_knative-0.1.2/mlflow_knative/service.yaml
+-rw-r--r--   0        0        0     1089 2023-06-28 15:55:30.134868 mlflow_knative-0.1.2/mlflow_knative/templating.py
+-rw-r--r--   0        0        0     1459 2023-06-28 15:55:30.135868 mlflow_knative-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0     5178 1970-01-01 00:00:00.000000 mlflow_knative-0.1.2/PKG-INFO
```

### Comparing `mlflow_knative-0.1.1/LICENSE.md` & `mlflow_knative-0.1.2/LICENSE.md`

 * *Files identical despite different names*

### Comparing `mlflow_knative-0.1.1/README.md` & `mlflow_knative-0.1.2/README.md`

 * *Files identical despite different names*

### Comparing `mlflow_knative-0.1.1/mlflow_knative/deployment_client.py` & `mlflow_knative-0.1.2/mlflow_knative/deployment_client.py`

 * *Files 3% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 
 import docker
 import kubernetes
 import mlflow
 import pandas
 import requests
 
-from .knative import KnativeServingV1Api
+from .knative import KnativeServingV1Api, KnativeTimeoutError
 from .mlflow_docker import push_model_as_image
 from .templating import get_service_body
 
 MLFLOW_MODEL_FLAVOR_PYFUNC = "python_function"
 IMAGE_REPOSITORY_CONFIG_KEY = "image_repository"
 IMAGE_TAG_CONFIG_KEY = "image_tag"
 DEFAULT_IMAGE_TAG = "latest"
@@ -159,14 +159,18 @@
                         f"no deployment with name '{name}' "
                         f"found in namespace '{namespace}'."
                     )
                 else:
                     raise mlflow.exceptions.MlflowException(
                         f"Kubernetes API error ({error.status})"
                     ) from error
+            except KnativeTimeoutError as error:
+                raise mlflow.exceptions.MlflowException(
+                    f"service creation failed: {str(error)}"
+                ) from error
 
         return {"name": service["metadata"]["name"], "flavor": flavor}
 
     def delete_deployment(
         self,
         name: str,
         config: dict[str, str] | None = None,
@@ -191,14 +195,18 @@
                         f"no deployment with name '{name}' "
                         f"found in namespace '{namespace}'."
                     )
                 else:
                     raise mlflow.exceptions.MlflowException(
                         f"Kubernetes API error ({error.status})"
                     ) from error
+            except KnativeTimeoutError as error:
+                raise mlflow.exceptions.MlflowException(
+                    f"service update failed: {str(error)}"
+                ) from error
 
     def list_deployments(self, endpoint: str | None = None) -> list[dict[str, str]]:
         """List deployments on a Knative target (across all namespaces)."""
         if endpoint:
             raise EndpointArgumentNotSupported
 
         with self._kubernetes_client as kubernetes_client:
```

### Comparing `mlflow_knative-0.1.1/mlflow_knative/knative.py` & `mlflow_knative-0.1.2/mlflow_knative/knative.py`

 * *Files 12% similar despite different names*

```diff
@@ -30,14 +30,18 @@
             condition["status"] == str(True)
             for condition in event["object"]["status"]["conditions"]
         )
     except KeyError:
         return False
 
 
+class KnativeTimeoutError(Exception):
+    """Raised when the creation or update of a Knative services reaches a timeout."""
+
+
 class KnativeServingV1Api:
     """Knative Serving v1 API.
 
     All methods are namespaced, only top-level Service resource is implemented.
 
     Unlike APIs provided by the Kubernetes client for Python, it waits for service
     readiness by default.
@@ -69,30 +73,33 @@
             service["metadata"]["name"],
             service["metadata"]["namespace"],
         )
         start = time.time()
         for event in self._watch.stream(
             self._custom_objects_api.list_namespaced_custom_object,
             timeout_seconds=WATCH_TIMEOUT,
-            **params
+            **params,
         ):
             if _handle_namespaced_service_is_ready_event(
                 namespace=service["metadata"]["namespace"],
                 name=service["metadata"]["name"],
                 event=event,
             ):
                 self._watch.stop()
                 logger.info(
                     "Service '%s' ready in namespace '%s' after %ss",
                     service["metadata"]["name"],
                     service["metadata"]["namespace"],
                     int(time.time() - start),
                 )
+                return service
 
-        return service
+        raise KnativeTimeoutError(
+            f"timeout during service '{service['metadata']['name']}' creation."
+        )
 
     def update_namespaced_service(self, namespace: str, name: str, body: dict) -> dict:
         """Update a Knative service."""
         params = self._get_knative_namespaced_service_params(namespace)
         service = self.get_namespaced_service(namespace=namespace, name=name)
         updated_service = self._custom_objects_api.patch_namespaced_custom_object(
             **params, name=name, body=body
@@ -110,30 +117,33 @@
             updated_service["metadata"]["name"],
             updated_service["metadata"]["namespace"],
         )
         start = time.time()
         for event in self._watch.stream(
             self._custom_objects_api.list_namespaced_custom_object,
             timeout_seconds=WATCH_TIMEOUT,
-            **params
+            **params,
         ):
             if _handle_namespaced_service_is_ready_event(
                 namespace=updated_service["metadata"]["namespace"],
                 name=updated_service["metadata"]["name"],
                 event=event,
             ):
                 self._watch.stop()
                 logger.info(
                     "Service '%s' ready in namespace '%s' after %ss",
                     updated_service["metadata"]["name"],
                     updated_service["metadata"]["namespace"],
                     int(time.time() - start),
                 )
+                return updated_service
 
-        return updated_service
+        raise KnativeTimeoutError(
+            f"timeout during service update '{updated_service['metadata']['name']}'."
+        )
 
     def delete_namespaced_service(self, namespace: str, name: str) -> dict:
         """Delete a Knative service."""
         return self._custom_objects_api.delete_namespaced_custom_object(
             **self._get_knative_namespaced_service_params(namespace), name=name
         )
```

### Comparing `mlflow_knative-0.1.1/mlflow_knative/mlflow_docker.py` & `mlflow_knative-0.1.2/mlflow_knative/mlflow_docker.py`

 * *Files identical despite different names*

### Comparing `mlflow_knative-0.1.1/mlflow_knative/service.yaml` & `mlflow_knative-0.1.2/mlflow_knative/service.yaml`

 * *Files identical despite different names*

### Comparing `mlflow_knative-0.1.1/mlflow_knative/templating.py` & `mlflow_knative-0.1.2/mlflow_knative/templating.py`

 * *Files identical despite different names*

### Comparing `mlflow_knative-0.1.1/pyproject.toml` & `mlflow_knative-0.1.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "mlflow-knative"
-version = "0.1.1"
+version = "0.1.2"
 description = "MLflow plugin adding a Knative deployment target"
 authors = ["Loris Zinsou <lzinsou@protonmail.com>"]
 readme = "README.md"
 keywords = ["mlflow", "plugin", "mlops", "deployment", "deployments", "knative", "kubernetes", "kn", "k8s"]
 classifiers = [
     "Development Status :: 3 - Alpha",
     "Environment :: Plugins",
```

### Comparing `mlflow_knative-0.1.1/PKG-INFO` & `mlflow_knative-0.1.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mlflow-knative
-Version: 0.1.1
+Version: 0.1.2
 Summary: MLflow plugin adding a Knative deployment target
 Home-page: https://gitlab.com/lzinsou/mlflow-knative
 Keywords: mlflow,plugin,mlops,deployment,deployments,knative,kubernetes,kn,k8s
 Author: Loris Zinsou
 Author-email: lzinsou@protonmail.com
 Requires-Python: >=3.10,<4.0
 Classifier: Development Status :: 3 - Alpha
```


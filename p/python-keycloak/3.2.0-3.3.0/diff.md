# Comparing `tmp/python_keycloak-3.2.0.tar.gz` & `tmp/python_keycloak-3.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "python_keycloak-3.2.0.tar", max compression
+gzip compressed data, was "python_keycloak-3.3.0.tar", max compression
```

## Comparing `python_keycloak-3.2.0.tar` & `python_keycloak-3.3.0.tar`

### file list

```diff
@@ -1,20 +1,20 @@
--rw-r--r--   0        0        0     6644 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/CHANGELOG.md
--rw-r--r--   0        0        0     3192 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/CONTRIBUTING.md
--rw-r--r--   0        0        0     1111 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/LICENSE
--rw-r--r--   0        0        0    14613 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/README.md
--rw-r--r--   0        0        0     2342 2023-06-23 21:41:48.862524 python_keycloak-3.2.0/pyproject.toml
--rw-r--r--   0        0        0     2375 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/__init__.py
--rw-r--r--   0        0        0     1268 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/_version.py
--rw-r--r--   0        0        0     3823 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/authorization/__init__.py
--rw-r--r--   0        0        0     4421 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/authorization/permission.py
--rw-r--r--   0        0        0     5252 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/authorization/policy.py
--rw-r--r--   0        0        0     2306 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/authorization/role.py
--rw-r--r--   0        0        0     8909 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/connection.py
--rw-r--r--   0        0        0     5464 2023-06-23 21:41:28.262439 python_keycloak-3.2.0/src/keycloak/exceptions.py
--rw-r--r--   0        0        0   164471 2023-06-23 21:41:28.266439 python_keycloak-3.2.0/src/keycloak/keycloak_admin.py
--rw-r--r--   0        0        0    25390 2023-06-23 21:41:28.266439 python_keycloak-3.2.0/src/keycloak/keycloak_openid.py
--rw-r--r--   0        0        0    15376 2023-06-23 21:41:28.266439 python_keycloak-3.2.0/src/keycloak/keycloak_uma.py
--rw-r--r--   0        0        0    11781 2023-06-23 21:41:28.266439 python_keycloak-3.2.0/src/keycloak/openid_connection.py
--rw-r--r--   0        0        0     8767 2023-06-23 21:41:28.266439 python_keycloak-3.2.0/src/keycloak/uma_permissions.py
--rw-r--r--   0        0        0    11898 2023-06-23 21:41:28.266439 python_keycloak-3.2.0/src/keycloak/urls_patterns.py
--rw-r--r--   0        0        0    16384 1970-01-01 00:00:00.000000 python_keycloak-3.2.0/PKG-INFO
+-rw-r--r--   0        0        0     6797 2023-06-27 23:37:53.737272 python_keycloak-3.3.0/CHANGELOG.md
+-rw-r--r--   0        0        0     3192 2023-06-27 23:37:53.737272 python_keycloak-3.3.0/CONTRIBUTING.md
+-rw-r--r--   0        0        0     1111 2023-06-27 23:37:53.737272 python_keycloak-3.3.0/LICENSE
+-rw-r--r--   0        0        0    14613 2023-06-27 23:37:53.737272 python_keycloak-3.3.0/README.md
+-rw-r--r--   0        0        0     2342 2023-06-27 23:38:12.413471 python_keycloak-3.3.0/pyproject.toml
+-rw-r--r--   0        0        0     2375 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/__init__.py
+-rw-r--r--   0        0        0     1268 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/_version.py
+-rw-r--r--   0        0        0     3823 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/authorization/__init__.py
+-rw-r--r--   0        0        0     4421 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/authorization/permission.py
+-rw-r--r--   0        0        0     5252 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/authorization/policy.py
+-rw-r--r--   0        0        0     2306 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/authorization/role.py
+-rw-r--r--   0        0        0     8909 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/connection.py
+-rw-r--r--   0        0        0     5464 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/exceptions.py
+-rw-r--r--   0        0        0   165922 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/keycloak_admin.py
+-rw-r--r--   0        0        0    25390 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/keycloak_openid.py
+-rw-r--r--   0        0        0    15376 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/keycloak_uma.py
+-rw-r--r--   0        0        0    11781 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/openid_connection.py
+-rw-r--r--   0        0        0     8767 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/uma_permissions.py
+-rw-r--r--   0        0        0    11898 2023-06-27 23:37:53.741272 python_keycloak-3.3.0/src/keycloak/urls_patterns.py
+-rw-r--r--   0        0        0    16384 1970-01-01 00:00:00.000000 python_keycloak-3.3.0/PKG-INFO
```

### Comparing `python_keycloak-3.2.0/CHANGELOG.md` & `python_keycloak-3.3.0/CHANGELOG.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,7 +1,13 @@
+## v3.2.0 (2023-06-23)
+
+### Feat
+
+- Implement missing admin method create_client_authz_scope_based_permission() and create_client_authz_policy() (#460)
+
 ## v3.1.1 (2023-06-23)
 
 ### Fix
 
 - remove duplicate slash in URL_ADMIN_IDP (#459)
 
 ## v3.1.0 (2023-06-23)
```

### Comparing `python_keycloak-3.2.0/CONTRIBUTING.md` & `python_keycloak-3.3.0/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/LICENSE` & `python_keycloak-3.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/README.md` & `python_keycloak-3.3.0/README.md`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/pyproject.toml` & `python_keycloak-3.3.0/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "python-keycloak"
-version = "v3.2.0"
+version = "v3.3.0"
 description = "python-keycloak is a Python package providing access to the Keycloak API."
 license = "MIT"
 readme = "README.md"
 keywords = [ "keycloak", "openid", "oidc" ]
 authors = [
     "Marcos Pereira <marcospereira.mpj@gmail.com>",
     "Richard Nemeth <ryshoooo@gmail.com>"
```

### Comparing `python_keycloak-3.2.0/src/keycloak/__init__.py` & `python_keycloak-3.3.0/src/keycloak/__init__.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/_version.py` & `python_keycloak-3.3.0/src/keycloak/_version.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/authorization/__init__.py` & `python_keycloak-3.3.0/src/keycloak/authorization/__init__.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/authorization/permission.py` & `python_keycloak-3.3.0/src/keycloak/authorization/permission.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/authorization/policy.py` & `python_keycloak-3.3.0/src/keycloak/authorization/policy.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/authorization/role.py` & `python_keycloak-3.3.0/src/keycloak/authorization/role.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/connection.py` & `python_keycloak-3.3.0/src/keycloak/connection.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/exceptions.py` & `python_keycloak-3.3.0/src/keycloak/exceptions.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/keycloak_admin.py` & `python_keycloak-3.3.0/src/keycloak/keycloak_admin.py`

 * *Files 1% similar despite different names*

```diff
@@ -1529,14 +1529,47 @@
             urls_patterns.URL_ADMIN_CLIENT_AUTHZ_RESOURCES.format(**params_path),
             data=json.dumps(payload),
         )
         return raise_error_from_response(
             data_raw, KeycloakPostError, expected_codes=[201], skip_exists=skip_exists
         )
 
+    def update_client_authz_resource(self, client_id, resource_id, payload):
+        """Update resource of client.
+
+        Any parameter missing from the ResourceRepresentation in the payload WILL be set
+        to default by the Keycloak server.
+
+        :param client_id: id in ClientRepresentation
+            https://www.keycloak.org/docs-api/18.0/rest-api/index.html#_clientrepresentation
+        :type client_id: str
+        :param payload: ResourceRepresentation
+            https://www.keycloak.org/docs-api/18.0/rest-api/index.html#_resourcerepresentation
+        :type payload: dict
+        :param client_id: id in ClientRepresentation
+            https://www.keycloak.org/docs-api/18.0/rest-api/index.html#_clientrepresentation
+        :type client_id: str
+        :param resource_id: id in ResourceRepresentation
+            https://www.keycloak.org/docs-api/18.0/rest-api/index.html#_resourcerepresentation
+        :type resource_id: str
+
+        :return: Keycloak server response
+        :rtype: bytes
+        """
+        params_path = {
+            "realm-name": self.connection.realm_name,
+            "id": client_id,
+            "resource-id": resource_id,
+        }
+        data_raw = self.connection.raw_put(
+            urls_patterns.URL_ADMIN_CLIENT_AUTHZ_RESOURCE.format(**params_path),
+            data=json.dumps(payload),
+        )
+        return raise_error_from_response(data_raw, KeycloakPutError, expected_codes=[204])
+
     def delete_client_authz_resource(self, client_id: str, resource_id: str):
         """Delete a client resource.
 
         :param client_id: id in ClientRepresentation
             https://www.keycloak.org/docs-api/18.0/rest-api/index.html#_clientrepresentation
         :type client_id: str
         :param resource_id: id in ResourceRepresentation
```

### Comparing `python_keycloak-3.2.0/src/keycloak/keycloak_openid.py` & `python_keycloak-3.3.0/src/keycloak/keycloak_openid.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/keycloak_uma.py` & `python_keycloak-3.3.0/src/keycloak/keycloak_uma.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/openid_connection.py` & `python_keycloak-3.3.0/src/keycloak/openid_connection.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/uma_permissions.py` & `python_keycloak-3.3.0/src/keycloak/uma_permissions.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/src/keycloak/urls_patterns.py` & `python_keycloak-3.3.0/src/keycloak/urls_patterns.py`

 * *Files identical despite different names*

### Comparing `python_keycloak-3.2.0/PKG-INFO` & `python_keycloak-3.3.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-keycloak
-Version: 3.2.0
+Version: 3.3.0
 Summary: python-keycloak is a Python package providing access to the Keycloak API.
 License: MIT
 Keywords: keycloak,openid,oidc
 Author: Marcos Pereira
 Author-email: marcospereira.mpj@gmail.com
 Requires-Python: >=3.7,<4.0
 Classifier: Development Status :: 3 - Alpha
```


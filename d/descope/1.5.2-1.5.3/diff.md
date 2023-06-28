# Comparing `tmp/descope-1.5.2.tar.gz` & `tmp/descope-1.5.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "descope-1.5.2.tar", max compression
+gzip compressed data, was "descope-1.5.3.tar", max compression
```

## Comparing `descope-1.5.2.tar` & `descope-1.5.3.tar`

### file list

```diff
@@ -1,31 +1,31 @@
--rw-r--r--   0        0        0     1064 2023-06-12 17:44:27.190722 descope-1.5.2/LICENSE
--rw-r--r--   0        0        0    31590 2023-06-12 17:44:27.190722 descope-1.5.2/README.md
--rw-r--r--   0        0        0      531 2023-06-12 17:44:27.190722 descope-1.5.2/descope/__init__.py
--rw-r--r--   0        0        0      211 2023-06-12 17:44:27.190722 descope-1.5.2/descope/_auth_base.py
--rw-r--r--   0        0        0    20602 2023-06-12 17:44:27.190722 descope-1.5.2/descope/auth.py
--rw-r--r--   0        0        0        0 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/__init__.py
--rw-r--r--   0        0        0     5352 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/enchantedlink.py
--rw-r--r--   0        0        0     6211 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/magiclink.py
--rw-r--r--   0        0        0     1528 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/oauth.py
--rw-r--r--   0        0        0    11078 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/otp.py
--rw-r--r--   0        0        0     8150 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/password.py
--rw-r--r--   0        0        0     1481 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/saml.py
--rw-r--r--   0        0        0     5128 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/totp.py
--rw-r--r--   0        0        0     6705 2023-06-12 17:44:27.190722 descope-1.5.2/descope/authmethod/webauthn.py
--rw-r--r--   0        0        0     4266 2023-06-12 17:44:27.190722 descope-1.5.2/descope/common.py
--rw-r--r--   0        0        0    11637 2023-06-12 17:44:27.190722 descope-1.5.2/descope/descope_client.py
--rw-r--r--   0        0        0     1420 2023-06-12 17:44:27.190722 descope-1.5.2/descope/exceptions.py
--rw-r--r--   0        0        0     5809 2023-06-12 17:44:27.190722 descope-1.5.2/descope/management/access_key.py
--rw-r--r--   0        0        0     4604 2023-06-12 17:44:27.190722 descope-1.5.2/descope/management/audit.py
--rw-r--r--   0        0        0     4050 2023-06-12 17:44:27.190722 descope-1.5.2/descope/management/common.py
--rw-r--r--   0        0        0     3394 2023-06-12 17:44:27.190722 descope-1.5.2/descope/management/flow.py
--rw-r--r--   0        0        0     3971 2023-06-12 17:44:27.190722 descope-1.5.2/descope/management/group.py
--rw-r--r--   0        0        0      959 2023-06-12 17:44:27.190722 descope-1.5.2/descope/management/jwt.py
--rw-r--r--   0        0        0     2535 2023-06-12 17:44:27.194722 descope-1.5.2/descope/management/permission.py
--rw-r--r--   0        0        0     3098 2023-06-12 17:44:27.194722 descope-1.5.2/descope/management/role.py
--rw-r--r--   0        0        0     6386 2023-06-12 17:44:27.194722 descope-1.5.2/descope/management/sso_settings.py
--rw-r--r--   0        0        0     3689 2023-06-12 17:44:27.194722 descope-1.5.2/descope/management/tenant.py
--rw-r--r--   0        0        0    30085 2023-06-12 17:44:27.194722 descope-1.5.2/descope/management/user.py
--rw-r--r--   0        0        0     1710 2023-06-12 17:44:27.194722 descope-1.5.2/descope/mgmt.py
--rw-r--r--   0        0        0     1220 2023-06-12 17:44:59.792024 descope-1.5.2/pyproject.toml
--rw-r--r--   0        0        0    32610 1970-01-01 00:00:00.000000 descope-1.5.2/PKG-INFO
+-rw-r--r--   0        0        0     1064 2023-06-28 13:50:17.971236 descope-1.5.3/LICENSE
+-rw-r--r--   0        0        0    32364 2023-06-28 13:50:17.971236 descope-1.5.3/README.md
+-rw-r--r--   0        0        0      531 2023-06-28 13:50:17.971236 descope-1.5.3/descope/__init__.py
+-rw-r--r--   0        0        0      211 2023-06-28 13:50:17.971236 descope-1.5.3/descope/_auth_base.py
+-rw-r--r--   0        0        0    21267 2023-06-28 13:50:17.971236 descope-1.5.3/descope/auth.py
+-rw-r--r--   0        0        0        0 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/__init__.py
+-rw-r--r--   0        0        0     5352 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/enchantedlink.py
+-rw-r--r--   0        0        0     6211 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/magiclink.py
+-rw-r--r--   0        0        0     1528 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/oauth.py
+-rw-r--r--   0        0        0    11078 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/otp.py
+-rw-r--r--   0        0        0     8150 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/password.py
+-rw-r--r--   0        0        0     1481 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/saml.py
+-rw-r--r--   0        0        0     5128 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/totp.py
+-rw-r--r--   0        0        0     6705 2023-06-28 13:50:17.971236 descope-1.5.3/descope/authmethod/webauthn.py
+-rw-r--r--   0        0        0     4266 2023-06-28 13:50:17.971236 descope-1.5.3/descope/common.py
+-rw-r--r--   0        0        0    12089 2023-06-28 13:50:17.971236 descope-1.5.3/descope/descope_client.py
+-rw-r--r--   0        0        0     1420 2023-06-28 13:50:17.971236 descope-1.5.3/descope/exceptions.py
+-rw-r--r--   0        0        0     5809 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/access_key.py
+-rw-r--r--   0        0        0     4604 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/audit.py
+-rw-r--r--   0        0        0     4155 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/common.py
+-rw-r--r--   0        0        0     3904 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/flow.py
+-rw-r--r--   0        0        0     3971 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/group.py
+-rw-r--r--   0        0        0      959 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/jwt.py
+-rw-r--r--   0        0        0     2535 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/permission.py
+-rw-r--r--   0        0        0     3098 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/role.py
+-rw-r--r--   0        0        0     6386 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/sso_settings.py
+-rw-r--r--   0        0        0     3689 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/tenant.py
+-rw-r--r--   0        0        0    31376 2023-06-28 13:50:17.971236 descope-1.5.3/descope/management/user.py
+-rw-r--r--   0        0        0     1710 2023-06-28 13:50:17.971236 descope-1.5.3/descope/mgmt.py
+-rw-r--r--   0        0        0     1220 2023-06-28 13:50:46.119566 descope-1.5.3/pyproject.toml
+-rw-r--r--   0        0        0    33384 1970-01-01 00:00:00.000000 descope-1.5.3/PKG-INFO
```

### Comparing `descope-1.5.2/LICENSE` & `descope-1.5.3/LICENSE`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/README.md` & `descope-1.5.3/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -52,15 +52,15 @@
 1. [Manage Tenants](#manage-tenants)
 2. [Manage Users](#manage-users)
 3. [Manage Access Keys](#manage-access-keys)
 4. [Manage SSO Setting](#manage-sso-setting)
 5. [Manage Permissions](#manage-permissions)
 6. [Manage Roles](#manage-roles)
 7. [Query SSO Groups](#query-sso-groups)
-8. [Manage Flows](#manage-flows)
+8. [Manage Flows](#manage-flows-and-theme)
 9. [Manage JWTs](#manage-jwts)
 10. [Search Audit](#search-audit)
 
 If you wish to run any of our code samples and play with them, check out our [Code Examples](#code-examples) section.
 
 If you're performing end-to-end testing, check out the [Utils for your end to end (e2e) tests and integration tests](#utils-for-your-end-to-end-e2e-tests-and-integration-tests) section. You will need to use the `DescopeClient` object created under [Setup](#setup-1) guide.
 
@@ -511,14 +511,18 @@
     display_name="Desmond Copeland",
     user_tenants=[
         AssociatedTenant("my-tenant-id", ["role-name1", "role-name2"]),
     ],
 )
 
 # Update explicit data for a user rather than overriding all fields
+descope_client.mgmt.user.update_login_id(
+    login_id="desmond@descope.com",
+    new_login_id="bane@descope.com"
+)
 descope_client.mgmt.user.update_phone(
     login_id="desmond@descope.com",
     phone="+18005551234",
     verified=True,
 )
 descope_client.mgmt.user.remove_tenant_roles(
     login_id="desmond@descope.com",
@@ -700,17 +704,24 @@
 roles = roles_resp["roles"]
     for role in roles:
         # Do something
 ```
 
 ### Manage Flows and Theme
 
-You can export and import your project flows and theme:
+You can list your flows and also import and export flows and screens, or the project theme:
 
 ```Python
+# List all project flows
+flows_resp = descope_client.mgmt.flow.list_flows()
+print(f'Total number of flows: {flows_resp["total"]}')
+flows = flows_resp["flows"]
+for flow in flows:
+    # Do something
+
 # Export a selected flow by id for the flow and matching screens.
 exported_flow_and_screens = descope_client.mgmt.flow.export_flow(
     flow_id="sign-up-or-in",
 )
 
 # Import a given flow and screens to the flow matching the id provided.
 imported_flow_and_screens = descope_client.mgmt.flow.import_flow(
@@ -854,14 +865,38 @@
     # This variable indicates how many seconds until the next valid API call can take place.
 ```
 
 ## Code Samples
 
 You can find various usage samples in the [samples folder](https://github.com/descope/python-sdk/blob/main/samples).
 
+## Run Locally
+
+### Prerequisites
+ - Python 3.7 or higher
+ - [Poetry](https://python-poetry.org) installed
+
+### Install dependencies
+
+```bash
+poetry install
+```
+
+### Run tests
+
+Running all tests:
+```bash
+poetry run pytest tests
+```
+
+Running all tests with coverage:
+```bash
+poetry run pytest --junitxml=/tmp/pytest.xml --cov-report=term-missing:skip-covered --cov=descope tests/ --cov-report=xml:/tmp/cov.xml
+```
+
 ## Learn More
 
 To learn more please see the [Descope Documentation and API reference page](https://docs.descope.com/).
 
 ## Contact Us
 
 If you need help you can email [Descope Support](mailto:support@descope.com)
```

### Comparing `descope-1.5.2/descope/__init__.py` & `descope-1.5.3/descope/__init__.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/auth.py` & `descope-1.5.3/descope/auth.py`

 * *Files 2% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 from threading import Lock
 from typing import Tuple
 
 import jwt
 import pkg_resources
 import requests
 from email_validator import EmailNotValidError, validate_email
+from jwt import ImmatureSignatureError
 
 from descope.common import (
     COOKIE_DATA_NAME,
     DEFAULT_BASE_URL,
     DEFAULT_TIMEOUT_SECONDS,
     PHONE_REGEX,
     REFRESH_SESSION_COOKIE_NAME,
@@ -47,28 +48,30 @@
     def __init__(
         self,
         project_id: str = None,
         public_key: str = None,
         skip_verify: bool = False,
         management_key: str = None,
         timeout_seconds: float = DEFAULT_TIMEOUT_SECONDS,
+        jwt_validation_leeway: int = 5,
     ):
         self.lock_public_keys = Lock()
         # validate project id
         project_id = project_id or os.getenv("DESCOPE_PROJECT_ID")
         if not project_id:
             raise AuthException(
                 400,
                 ERROR_TYPE_INVALID_ARGUMENT,
                 (
                     "Unable to init Auth object because project_id cannot be empty. "
                     "Set environment variable DESCOPE_PROJECT_ID or pass your Project ID to the init function."
                 ),
             )
         self.project_id = project_id
+        self.jwt_validation_leeway = jwt_validation_leeway
         self.secure = not skip_verify
 
         self.base_url = os.getenv("DESCOPE_BASE_URI") or DEFAULT_BASE_URL
         self.timeout_seconds = timeout_seconds
         self.management_key = management_key or os.getenv("DESCOPE_MANAGEMENT_KEY")
 
         public_key = public_key or os.getenv("DESCOPE_PUBLIC_KEY")
@@ -514,15 +517,29 @@
         alg_from_key = copy_key[1]
         if alg_header != alg_from_key:
             raise AuthException(
                 500,
                 ERROR_TYPE_INVALID_PUBLIC_KEY,
                 "Algorithm signature in JWT header does not match the algorithm signature in the public key",
             )
-        claims = jwt.decode(jwt=token, key=copy_key[0].key, algorithms=[alg_header])
+
+        try:
+            claims = jwt.decode(
+                jwt=token,
+                key=copy_key[0].key,
+                algorithms=[alg_header],
+                leeway=self.jwt_validation_leeway,
+            )
+        except ImmatureSignatureError:
+            raise AuthException(
+                400,
+                ERROR_TYPE_INVALID_TOKEN,
+                "Received Invalid token times error due to time glitch (between machines) during jwt validation, try to set the jwt_validation_leeway parameter (in DescopeClient) to higher value than 5sec which is the default",
+            )
+
         claims["jwt"] = token
         return claims
 
     def validate_session(self, session_token: str) -> dict:
         if not session_token:
             raise AuthException(
                 400,
@@ -532,15 +549,15 @@
 
         try:
             res = self._validate_token(session_token)
             res[SESSION_TOKEN_NAME] = copy.deepcopy(
                 res
             )  # Duplicate for saving backward compatibility but keep the same structure as the refresh operation response
             return self.adjust_properties(res, True)
-        except RateLimitException as e:
+        except (RateLimitException, AuthException) as e:
             raise e
         except Exception as e:
             raise AuthException(
                 401, ERROR_TYPE_INVALID_TOKEN, f"Invalid session token: {e}"
             )
 
     def refresh_session(self, refresh_token: str) -> dict:
```

### Comparing `descope-1.5.2/descope/authmethod/enchantedlink.py` & `descope-1.5.3/descope/authmethod/enchantedlink.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/magiclink.py` & `descope-1.5.3/descope/authmethod/magiclink.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/oauth.py` & `descope-1.5.3/descope/authmethod/oauth.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/otp.py` & `descope-1.5.3/descope/authmethod/otp.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/password.py` & `descope-1.5.3/descope/authmethod/password.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/saml.py` & `descope-1.5.3/descope/authmethod/saml.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/totp.py` & `descope-1.5.3/descope/authmethod/totp.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/authmethod/webauthn.py` & `descope-1.5.3/descope/authmethod/webauthn.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/common.py` & `descope-1.5.3/descope/common.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/descope_client.py` & `descope-1.5.3/descope/descope_client.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,17 +22,23 @@
     def __init__(
         self,
         project_id: str = None,
         public_key: str = None,
         skip_verify: bool = False,
         management_key: str = None,
         timeout_seconds: float = DEFAULT_TIMEOUT_SECONDS,
+        jwt_validation_leeway: int = 5,
     ):
         auth = Auth(
-            project_id, public_key, skip_verify, management_key, timeout_seconds
+            project_id,
+            public_key,
+            skip_verify,
+            management_key,
+            timeout_seconds,
+            jwt_validation_leeway,
         )
         self._auth = auth
         self._mgmt = MGMT(auth)
         self._magiclink = MagicLink(auth)
         self._enchantedlink = EnchantedLink(auth)
         self._oauth = OAuth(auth)
         self._saml = SAML(auth)
@@ -114,14 +120,17 @@
         if isinstance(permissions, str):
             permissions = [permissions]
 
         granted = []
         if tenant == "":
             granted = jwt_response.get("permissions", [])
         else:
+            # ensure that the tenant is associated with the jwt_response
+            if tenant not in jwt_response.get("tenants", {}):
+                return False
             granted = (
                 jwt_response.get("tenants", {}).get(tenant, {}).get("permissions", [])
             )
 
         for perm in permissions:
             if perm not in granted:
                 return False
@@ -160,14 +169,17 @@
         if isinstance(roles, str):
             roles = [roles]
 
         granted = []
         if tenant == "":
             granted = jwt_response.get("roles", [])
         else:
+            # ensure that the tenant is associated with the jwt_response
+            if tenant not in jwt_response.get("tenants", {}):
+                return False
             granted = jwt_response.get("tenants", {}).get(tenant, {}).get("roles", [])
 
         for role in roles:
             if role not in granted:
                 return False
         return True
```

### Comparing `descope-1.5.2/descope/exceptions.py` & `descope-1.5.3/descope/exceptions.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/access_key.py` & `descope-1.5.3/descope/management/access_key.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/audit.py` & `descope-1.5.3/descope/management/audit.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/common.py` & `descope-1.5.3/descope/management/common.py`

 * *Files 1% similar despite different names*

```diff
@@ -13,14 +13,15 @@
     user_update_path = "/v1/mgmt/user/update"
     user_delete_path = "/v1/mgmt/user/delete"
     user_delete_all_test_users_path = "/v1/mgmt/user/test/delete/all"
     user_load_path = "/v1/mgmt/user"
     users_search_path = "/v1/mgmt/user/search"
     user_get_provider_token = "/v1/mgmt/user/provider/token"
     user_update_status_path = "/v1/mgmt/user/update/status"
+    user_update_login_id_path = "/v1/mgmt/user/update/loginid"
     user_update_email_path = "/v1/mgmt/user/update/email"
     user_update_phone_path = "/v1/mgmt/user/update/phone"
     user_update_name_path = "/v1/mgmt/user/update/name"
     user_update_picture_path = "/v1/mgmt/user/update/picture"
     user_update_custom_attribute_path = "/v1/mgmt/user/update/customAttribute"
     user_add_role_path = "/v1/mgmt/user/update/role/add"
     user_remove_role_path = "/v1/mgmt/user/update/role/remove"
@@ -58,14 +59,15 @@
     # role
     role_create_path = "/v1/mgmt/role/create"
     role_update_path = "/v1/mgmt/role/update"
     role_delete_path = "/v1/mgmt/role/delete"
     role_load_all_path = "/v1/mgmt/role/all"
 
     # flow
+    flow_list_path = "/v1/mgmt/flow/list"
     flow_import_path = "/v1/mgmt/flow/import"
     flow_export_path = "/v1/mgmt/flow/export"
 
     # theme
     theme_import_path = "/v1/mgmt/theme/import"
     theme_export_path = "/v1/mgmt/theme/export"
```

### Comparing `descope-1.5.2/descope/management/flow.py` & `descope-1.5.3/descope/management/flow.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,14 +1,34 @@
 from typing import List
 
 from descope._auth_base import AuthBase
 from descope.management.common import MgmtV1
 
 
 class Flow(AuthBase):
+    def list_flows(
+        self,
+    ) -> dict:
+        """
+        List all project flows
+
+        Return value (dict):
+        Return dict in the format
+            { "flows": [{"id": "", "name": "", "description": "", "disabled": False}], total: number}
+
+        Raise:
+        AuthException: raised if list operation fails
+        """
+        response = self._auth.do_post(
+            MgmtV1.flow_list_path,
+            None,
+            pswd=self._auth.management_key,
+        )
+        return response.json()
+
     def export_flow(
         self,
         flow_id: str,
     ) -> dict:
         """
         Export the given flow id flow and screens.
 
@@ -16,15 +36,15 @@
         flow_id (str): the flow id to export.
 
         Return value (dict):
         Return dict in the format
             { "flow": {"id": "", "name": "", "description": "", "disabled": False, "etag": "", "dsl": {}}, screens: [{ "id": "", "inputs": [], "interactions": [] }] }
 
         Raise:
-        AuthException: raised if creation operation fails
+        AuthException: raised if export operation fails
         """
         response = self._auth.do_post(
             MgmtV1.flow_export_path,
             {
                 "flowId": flow_id,
             },
             pswd=self._auth.management_key,
@@ -49,15 +69,15 @@
             { "id": "", "inputs": [], "interactions": [] }
 
         Return value (dict):
         Return dict in the format
             { "flow": {"id": "", "name": "", "description": "", "disabled": False, "etag": "", "dsl": {}}, screens: [{ "id": "", "inputs": [], "interactions": [] }] }
 
         Raise:
-        AuthException: raised if creation operation fails
+        AuthException: raised if import operation fails
         """
         response = self._auth.do_post(
             MgmtV1.flow_import_path,
             {
                 "flowId": flow_id,
                 "flow": flow,
                 "screens": screens,
@@ -73,15 +93,15 @@
         Export the current project theme.
 
         Return value (dict):
         Return dict in the format
             {"id": "", "cssTemplate": {} }
 
         Raise:
-        AuthException: raised if creation operation fails
+        AuthException: raised if export operation fails
         """
         response = self._auth.do_post(
             MgmtV1.theme_export_path,
             {},
             pswd=self._auth.management_key,
         )
         return response.json()
@@ -99,15 +119,15 @@
             {"id": "", "cssTemplate": {} }
 
         Return value (dict):
         Return dict in the format
             {"id": "", "cssTemplate": {} }
 
         Raise:
-        AuthException: raised if creation operation fails
+        AuthException: raised if import operation fails
         """
         response = self._auth.do_post(
             MgmtV1.theme_import_path,
             {
                 "theme": theme,
             },
             pswd=self._auth.management_key,
```

### Comparing `descope-1.5.2/descope/management/group.py` & `descope-1.5.3/descope/management/group.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/jwt.py` & `descope-1.5.3/descope/management/jwt.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/permission.py` & `descope-1.5.3/descope/management/permission.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/role.py` & `descope-1.5.3/descope/management/role.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/sso_settings.py` & `descope-1.5.3/descope/management/sso_settings.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/tenant.py` & `descope-1.5.3/descope/management/tenant.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/descope/management/user.py` & `descope-1.5.3/descope/management/user.py`

 * *Files 2% similar despite different names*

```diff
@@ -173,14 +173,16 @@
         email: str = None,
         phone: str = None,
         display_name: str = None,
         role_names: List[str] = None,
         user_tenants: List[AssociatedTenant] = None,
         picture: str = None,
         custom_attributes: dict = None,
+        verified_email: bool = None,
+        verified_phone: bool = None,
     ):
         """
         Update an existing user with the given various fields. IMPORTANT: All parameters are used as overrides
         to the existing user. Empty fields will override populated fields. Use carefully.
 
         Args:
         login_id (str): The login ID of the user to update.
@@ -208,14 +210,16 @@
                 phone,
                 display_name,
                 role_names,
                 user_tenants,
                 False,
                 picture,
                 custom_attributes,
+                verified_email,
+                verified_phone,
             ),
             pswd=self._auth.management_key,
         )
 
     def delete(
         self,
         login_id: str,
@@ -434,14 +438,42 @@
         response = self._auth.do_post(
             MgmtV1.user_update_status_path,
             {"loginId": login_id, "status": "disabled"},
             pswd=self._auth.management_key,
         )
         return response.json()
 
+    def update_login_id(
+        self,
+        login_id: str,
+        new_login_id: str = None,
+    ) -> dict:
+        """
+        Update login id of user, leave new login empty to remove the ID.
+        A user must have at least one login ID. Trying to remove the last one will fail.
+
+        Args:
+        login_id (str): The login ID of the user to update.
+        new_login_id (str): New login ID to set for the user.
+
+        Return value (dict):
+        Return dict in the format
+             {"user": {}}
+        Containing the updated user information.
+
+        Raise:
+        AuthException: raised if the update operation fails
+        """
+        response = self._auth.do_post(
+            MgmtV1.user_update_login_id_path,
+            {"loginId": login_id, "newLoginId": new_login_id},
+            pswd=self._auth.management_key,
+        )
+        return response.json()
+
     def update_email(
         self,
         login_id: str,
         email: str = None,
         verified: bool = None,
     ) -> dict:
         """
@@ -921,19 +953,26 @@
         phone: str,
         display_name: str,
         role_names: List[str],
         user_tenants: List[AssociatedTenant],
         test: bool,
         picture: str,
         custom_attributes: dict,
+        verified_email: bool = None,
+        verified_phone: bool = None,
     ) -> dict:
-        return {
+        res = {
             "loginId": login_id,
             "email": email,
             "phone": phone,
             "displayName": display_name,
             "roleNames": role_names,
             "userTenants": associated_tenants_to_dict(user_tenants),
             "test": test,
             "picture": picture,
             "customAttributes": custom_attributes,
         }
+        if verified_email is not None:
+            res["verifiedEmail"] = verified_email
+        if verified_phone is not None:
+            res["verifiedPhone"] = verified_phone
+        return res
```

### Comparing `descope-1.5.2/descope/mgmt.py` & `descope-1.5.3/descope/mgmt.py`

 * *Files identical despite different names*

### Comparing `descope-1.5.2/pyproject.toml` & `descope-1.5.3/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "descope"
-version = "1.5.2"
+version = "1.5.3"
 description = "Descope Python SDK"
 authors = ["Descope <info@descope.com>"]
 license = "MIT"
 readme = "README.md"
 homepage = "https://descope.com/"
 repository = "https://github.com/descope/python-sdk"
 documentation = "https://docs.descope.com"
@@ -31,16 +31,16 @@
 
 [tool.poetry.group.dev.dependencies]
 mock = "5.0.2"
 pre-commit = "2.21.0"
 Flask = "2.2.5"
 flake8 = "5.0.4"
 flake8-bugbear = "22.12.6"
-pytest-cov = "4.0.0"
-pytest = "7.3.1"
+pytest-cov = "4.1.0"
+pytest = "7.3.2"
 black = "23.3.0"
 liccheck = "0.9.1"
 isort = "5.11.4"
 pep8-naming = "0.13.3"
 
 [build-system]
 requires = ["poetry-core>=1.1.0"]
```

### Comparing `descope-1.5.2/PKG-INFO` & `descope-1.5.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: descope
-Version: 1.5.2
+Version: 1.5.3
 Summary: Descope Python SDK
 Home-page: https://descope.com/
 License: MIT
 Author: Descope
 Author-email: info@descope.com
 Requires-Python: >=3.7,<4.0
 Classifier: License :: OSI Approved :: MIT License
@@ -78,15 +78,15 @@
 1. [Manage Tenants](#manage-tenants)
 2. [Manage Users](#manage-users)
 3. [Manage Access Keys](#manage-access-keys)
 4. [Manage SSO Setting](#manage-sso-setting)
 5. [Manage Permissions](#manage-permissions)
 6. [Manage Roles](#manage-roles)
 7. [Query SSO Groups](#query-sso-groups)
-8. [Manage Flows](#manage-flows)
+8. [Manage Flows](#manage-flows-and-theme)
 9. [Manage JWTs](#manage-jwts)
 10. [Search Audit](#search-audit)
 
 If you wish to run any of our code samples and play with them, check out our [Code Examples](#code-examples) section.
 
 If you're performing end-to-end testing, check out the [Utils for your end to end (e2e) tests and integration tests](#utils-for-your-end-to-end-e2e-tests-and-integration-tests) section. You will need to use the `DescopeClient` object created under [Setup](#setup-1) guide.
 
@@ -537,14 +537,18 @@
     display_name="Desmond Copeland",
     user_tenants=[
         AssociatedTenant("my-tenant-id", ["role-name1", "role-name2"]),
     ],
 )
 
 # Update explicit data for a user rather than overriding all fields
+descope_client.mgmt.user.update_login_id(
+    login_id="desmond@descope.com",
+    new_login_id="bane@descope.com"
+)
 descope_client.mgmt.user.update_phone(
     login_id="desmond@descope.com",
     phone="+18005551234",
     verified=True,
 )
 descope_client.mgmt.user.remove_tenant_roles(
     login_id="desmond@descope.com",
@@ -726,17 +730,24 @@
 roles = roles_resp["roles"]
     for role in roles:
         # Do something
 ```
 
 ### Manage Flows and Theme
 
-You can export and import your project flows and theme:
+You can list your flows and also import and export flows and screens, or the project theme:
 
 ```Python
+# List all project flows
+flows_resp = descope_client.mgmt.flow.list_flows()
+print(f'Total number of flows: {flows_resp["total"]}')
+flows = flows_resp["flows"]
+for flow in flows:
+    # Do something
+
 # Export a selected flow by id for the flow and matching screens.
 exported_flow_and_screens = descope_client.mgmt.flow.export_flow(
     flow_id="sign-up-or-in",
 )
 
 # Import a given flow and screens to the flow matching the id provided.
 imported_flow_and_screens = descope_client.mgmt.flow.import_flow(
@@ -880,14 +891,38 @@
     # This variable indicates how many seconds until the next valid API call can take place.
 ```
 
 ## Code Samples
 
 You can find various usage samples in the [samples folder](https://github.com/descope/python-sdk/blob/main/samples).
 
+## Run Locally
+
+### Prerequisites
+ - Python 3.7 or higher
+ - [Poetry](https://python-poetry.org) installed
+
+### Install dependencies
+
+```bash
+poetry install
+```
+
+### Run tests
+
+Running all tests:
+```bash
+poetry run pytest tests
+```
+
+Running all tests with coverage:
+```bash
+poetry run pytest --junitxml=/tmp/pytest.xml --cov-report=term-missing:skip-covered --cov=descope tests/ --cov-report=xml:/tmp/cov.xml
+```
+
 ## Learn More
 
 To learn more please see the [Descope Documentation and API reference page](https://docs.descope.com/).
 
 ## Contact Us
 
 If you need help you can email [Descope Support](mailto:support@descope.com)
```


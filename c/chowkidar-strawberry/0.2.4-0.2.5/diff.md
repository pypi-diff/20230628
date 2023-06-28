# Comparing `tmp/chowkidar-strawberry-0.2.4.tar.gz` & `tmp/chowkidar-strawberry-0.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chowkidar-strawberry-0.2.4.tar", last modified: Tue Jan 10 11:10:59 2023, max compression
+gzip compressed data, was "chowkidar-strawberry-0.2.5.tar", last modified: Wed Jun 28 10:08:27 2023, max compression
```

## Comparing `chowkidar-strawberry-0.2.4.tar` & `chowkidar-strawberry-0.2.5.tar`

### file list

```diff
@@ -1,26 +1,27 @@
-drwxr-xr-x   0 aswinshenoy   (501) staff       (20)        0 2023-01-10 11:10:59.239361 chowkidar-strawberry-0.2.4/
--rw-r--r--   0 aswinshenoy   (501) staff       (20)    35029 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/LICENSE
--rw-r--r--   0 aswinshenoy   (501) staff       (20)       33 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/MANIFEST.in
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     8594 2023-01-10 11:10:59.239479 chowkidar-strawberry-0.2.4/PKG-INFO
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     7495 2023-01-10 11:10:58.000000 chowkidar-strawberry-0.2.4/README.md
-drwxr-xr-x   0 aswinshenoy   (501) staff       (20)        0 2023-01-10 11:10:59.237539 chowkidar-strawberry-0.2.4/chowkidar/
--rw-r--r--   0 aswinshenoy   (501) staff       (20)        0 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/__init__.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     1789 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/decorators.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     7607 2023-01-10 11:05:46.000000 chowkidar-strawberry-0.2.4/chowkidar/extension.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     2407 2023-01-10 11:05:24.000000 chowkidar-strawberry-0.2.4/chowkidar/models.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     2082 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/settings.py
-drwxr-xr-x   0 aswinshenoy   (501) staff       (20)        0 2023-01-10 11:10:59.238211 chowkidar-strawberry-0.2.4/chowkidar/utils/
--rw-r--r--   0 aswinshenoy   (501) staff       (20)      516 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/utils/__init__.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     1492 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/utils/cookie.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)      431 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/utils/exceptions.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     2630 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/utils/jwt.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     2752 2023-01-10 11:04:58.000000 chowkidar-strawberry-0.2.4/chowkidar/view.py
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     2414 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/chowkidar/wrappers.py
-drwxr-xr-x   0 aswinshenoy   (501) staff       (20)        0 2023-01-10 11:10:59.239172 chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     8594 2023-01-10 11:10:59.000000 chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/PKG-INFO
--rw-r--r--   0 aswinshenoy   (501) staff       (20)      525 2023-01-10 11:10:59.000000 chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/SOURCES.txt
--rw-r--r--   0 aswinshenoy   (501) staff       (20)        1 2023-01-10 11:10:59.000000 chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/dependency_links.txt
--rw-r--r--   0 aswinshenoy   (501) staff       (20)        1 2022-12-10 10:04:44.000000 chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/not-zip-safe
--rw-r--r--   0 aswinshenoy   (501) staff       (20)       10 2023-01-10 11:10:59.000000 chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/top_level.txt
--rw-r--r--   0 aswinshenoy   (501) staff       (20)     1133 2023-01-10 11:10:59.239839 chowkidar-strawberry-0.2.4/setup.cfg
--rw-r--r--   0 aswinshenoy   (501) staff       (20)      262 2022-12-10 10:04:16.000000 chowkidar-strawberry-0.2.4/setup.py
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 10:08:27.582659 chowkidar-strawberry-0.2.5/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)    35029 2022-09-20 17:56:11.000000 chowkidar-strawberry-0.2.5/LICENSE
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)       33 2022-09-20 21:39:18.000000 chowkidar-strawberry-0.2.5/MANIFEST.in
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     9251 2023-06-28 10:08:27.582773 chowkidar-strawberry-0.2.5/PKG-INFO
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     8171 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.5/README.md
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 10:08:27.580631 chowkidar-strawberry-0.2.5/chowkidar/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)        0 2022-09-20 17:06:06.000000 chowkidar-strawberry-0.2.5/chowkidar/__init__.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2057 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.5/chowkidar/authentication.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1789 2022-09-22 09:55:22.000000 chowkidar-strawberry-0.2.5/chowkidar/decorators.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     7607 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.5/chowkidar/extension.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2407 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.5/chowkidar/models.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2082 2022-09-28 09:26:14.000000 chowkidar-strawberry-0.2.5/chowkidar/settings.py
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 10:08:27.581622 chowkidar-strawberry-0.2.5/chowkidar/utils/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      852 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.5/chowkidar/utils/__init__.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1492 2022-09-20 20:57:17.000000 chowkidar-strawberry-0.2.5/chowkidar/utils/cookie.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      920 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.5/chowkidar/utils/exceptions.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2630 2022-09-20 20:57:17.000000 chowkidar-strawberry-0.2.5/chowkidar/utils/jwt.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2752 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.5/chowkidar/view.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2414 2022-09-29 08:20:04.000000 chowkidar-strawberry-0.2.5/chowkidar/wrappers.py
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 10:08:27.582513 chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     9251 2023-06-28 10:08:27.000000 chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/PKG-INFO
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      553 2023-06-28 10:08:27.000000 chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/SOURCES.txt
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)        1 2023-06-28 10:08:27.000000 chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/dependency_links.txt
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)        1 2023-06-28 10:08:27.000000 chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/not-zip-safe
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)       10 2023-06-28 10:08:27.000000 chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/top_level.txt
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1133 2023-06-28 10:08:27.583211 chowkidar-strawberry-0.2.5/setup.cfg
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      262 2022-10-06 08:12:09.000000 chowkidar-strawberry-0.2.5/setup.py
```

### Comparing `chowkidar-strawberry-0.2.4/LICENSE` & `chowkidar-strawberry-0.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/PKG-INFO` & `chowkidar-strawberry-0.2.5/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 Metadata-Version: 2.1
 Name: chowkidar-strawberry
-Version: 0.2.4
+Version: 0.2.5
 Summary: All-in-One JWT Authentication plugin for Strawberry
 Home-page: https://github.com/traboda/chowkidar
 Author: Ashwin Shenoy
 Author-email: ashwin@traboda.com
 Maintainer: Ashwin Shenoy
 Maintainer-email: ashwin@traboda.com
 License: GNU-GPL-V3
-Platform: UNKNOWN
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Development Status :: 4 - Beta
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
@@ -35,15 +34,15 @@
 
 1. Install the package from PyPI:
 
 ```bash
 pip install chowkidar-strawberry
 ```
 
-2. Add `chowkidar_strawberry` to your `INSTALLED_APPS`:
+2. Add `chowkidar` to your `INSTALLED_APPS`:
 
 ```python
 INSTALLED_APPS = [
     ...
     "chowkidar",
 ]
 ```
@@ -56,15 +55,15 @@
 schema = strawberry.Schema(
     query=Query,
     mutation=Mutation,
     extensions=[JWTAuthExtension],
 )
 ```
 
-4. Wrap your Strawberry GraphQL view with `chowkidar.view.auth_enabled_view`:
+4. Wrap your Strawberry GraphQL view with `chowkidar.view.auth_enabled_view` in your `urls.py`:
 
 ```python
 from chowkidar.view import auth_enabled_view
 
 urlpatterns = [
   ...
   path(
@@ -72,58 +71,71 @@
       auth_enabled_view(
           GraphQLView.as_view(schema=schema, graphiql=settings.DEBUG)
       )
   ),
 ]
 ```
 
-5. Create a Refresh Token Model inheriting the `chowkidar.models.AbstractRefreshToken` abstract model:
+5. Create a Refresh Token Model in an app of your choice inheriting the `chowkidar.models.AbstractRefreshToken` abstract model:
 
 ```python
 class RefreshToken(AbstractRefreshToken, models.Model):
     pass
 ```
 
 (do not forget run to `python manage.py makemigrations` and `python manage.py migrate`)
 
-6. Implement Mutations for `login` and `logout` with `issue_tokens_on_login` and `revoke_tokens_on_logout` respectively:
+6. Add 'REFRESH_TOKEN_MODEL' to your `settings.py` and point it to the Refresh Token Model you created in the previous step:
+
+```python
+REFRESH_TOKEN_MODEL = '<your app>.RefreshToken'
+```
+
+7. Implement Mutations for `login` and `logout` with `issue_tokens_on_login` and `revoke_tokens_on_logout` respectively:
 
 ```python
 import strawberry
 from chowkidar.wrappers import issue_tokens_on_login, revoke_tokens_on_logout
+from chowkidar.authentication import authenticate  # You may also use your own authentication methods or other methods like `authenticate_with_email` from chowkidar as well.
+
 
 @strawberry.type
 class AuthMutations:
-  
+
   @strawberry.mutation
   @issue_tokens_on_login
   def login(self, info, username: str, password: str) -> bool:
-      user = authenticate(username=username, password=password)
-      if user is None:
-          raise Exception("Invalid username or password")
-      
-      # Set LOGIN_USER with the authenticated user's object, in case of successful authentication
-      # else, set LOGIN_USER to None
-      info.context.LOGIN_USER = user
-      
-      return True
-  
+    user = authenticate(username=username, password=password)
+    if user is None:
+      raise Exception("Invalid username or password")
+
+    # Set LOGIN_USER with the authenticated user's object, in case of successful authentication
+    # else, set LOGIN_USER to None
+    info.context.LOGIN_USER = user
+
+    return True
+
   @strawberry.mutation
   @revoke_tokens_on_logout
   def logout(self, info) -> bool:
-      # Set info.context.LOGIN_USER to True for logging out the user
-      info.context.LOGOUT_USER = True
-      
-      return True
+    # Set info.context.LOGIN_USER to True for logging out the user
+    info.context.LOGOUT_USER = True
+
+    return True
 ```
 
 All your resolvers will now get the following parameters from `info.context` -
  - `info.context.userID` - ID of the requesting user, None if not logged-in 
  - `info.context.refreshToken`- Refresh token string of the requesting user, None if not logged-in
 
+Chowkidar comes with 3 authentication methods (importable from `chowkidar.authentication`), which you may use -
+1. `authenticate_with_email` - authenticate with email and password
+2. `authenticate_with_username` - authenticate with username and password
+3. `authenticate` - authenticate with username or email and password
+
 ## Decorators
 
 You can use these decorators
 
 1. `@login_required` - wrap your resolver with this decorator to ensure the resolver is called only for logged-in users.
     
 ```python
@@ -253,8 +265,7 @@
 Contributions are welcome. Please open an issue or a PR.
 
 ## License
 
 This project is licensed under the [GNU General Public License V3](LICENSE).
 
 Made by [Traboda](https://github.com/traboda/chowkidar) with ❤️ in India 🇮🇳.
-
```

### Comparing `chowkidar-strawberry-0.2.4/README.md` & `chowkidar-strawberry-0.2.5/README.md`

 * *Files 13% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 
 1. Install the package from PyPI:
 
 ```bash
 pip install chowkidar-strawberry
 ```
 
-2. Add `chowkidar_strawberry` to your `INSTALLED_APPS`:
+2. Add `chowkidar` to your `INSTALLED_APPS`:
 
 ```python
 INSTALLED_APPS = [
     ...
     "chowkidar",
 ]
 ```
@@ -27,15 +27,15 @@
 schema = strawberry.Schema(
     query=Query,
     mutation=Mutation,
     extensions=[JWTAuthExtension],
 )
 ```
 
-4. Wrap your Strawberry GraphQL view with `chowkidar.view.auth_enabled_view`:
+4. Wrap your Strawberry GraphQL view with `chowkidar.view.auth_enabled_view` in your `urls.py`:
 
 ```python
 from chowkidar.view import auth_enabled_view
 
 urlpatterns = [
   ...
   path(
@@ -43,58 +43,71 @@
       auth_enabled_view(
           GraphQLView.as_view(schema=schema, graphiql=settings.DEBUG)
       )
   ),
 ]
 ```
 
-5. Create a Refresh Token Model inheriting the `chowkidar.models.AbstractRefreshToken` abstract model:
+5. Create a Refresh Token Model in an app of your choice inheriting the `chowkidar.models.AbstractRefreshToken` abstract model:
 
 ```python
 class RefreshToken(AbstractRefreshToken, models.Model):
     pass
 ```
 
 (do not forget run to `python manage.py makemigrations` and `python manage.py migrate`)
 
-6. Implement Mutations for `login` and `logout` with `issue_tokens_on_login` and `revoke_tokens_on_logout` respectively:
+6. Add 'REFRESH_TOKEN_MODEL' to your `settings.py` and point it to the Refresh Token Model you created in the previous step:
+
+```python
+REFRESH_TOKEN_MODEL = '<your app>.RefreshToken'
+```
+
+7. Implement Mutations for `login` and `logout` with `issue_tokens_on_login` and `revoke_tokens_on_logout` respectively:
 
 ```python
 import strawberry
 from chowkidar.wrappers import issue_tokens_on_login, revoke_tokens_on_logout
+from chowkidar.authentication import authenticate  # You may also use your own authentication methods or other methods like `authenticate_with_email` from chowkidar as well.
+
 
 @strawberry.type
 class AuthMutations:
-  
+
   @strawberry.mutation
   @issue_tokens_on_login
   def login(self, info, username: str, password: str) -> bool:
-      user = authenticate(username=username, password=password)
-      if user is None:
-          raise Exception("Invalid username or password")
-      
-      # Set LOGIN_USER with the authenticated user's object, in case of successful authentication
-      # else, set LOGIN_USER to None
-      info.context.LOGIN_USER = user
-      
-      return True
-  
+    user = authenticate(username=username, password=password)
+    if user is None:
+      raise Exception("Invalid username or password")
+
+    # Set LOGIN_USER with the authenticated user's object, in case of successful authentication
+    # else, set LOGIN_USER to None
+    info.context.LOGIN_USER = user
+
+    return True
+
   @strawberry.mutation
   @revoke_tokens_on_logout
   def logout(self, info) -> bool:
-      # Set info.context.LOGIN_USER to True for logging out the user
-      info.context.LOGOUT_USER = True
-      
-      return True
+    # Set info.context.LOGIN_USER to True for logging out the user
+    info.context.LOGOUT_USER = True
+
+    return True
 ```
 
 All your resolvers will now get the following parameters from `info.context` -
  - `info.context.userID` - ID of the requesting user, None if not logged-in 
  - `info.context.refreshToken`- Refresh token string of the requesting user, None if not logged-in
 
+Chowkidar comes with 3 authentication methods (importable from `chowkidar.authentication`), which you may use -
+1. `authenticate_with_email` - authenticate with email and password
+2. `authenticate_with_username` - authenticate with username and password
+3. `authenticate` - authenticate with username or email and password
+
 ## Decorators
 
 You can use these decorators
 
 1. `@login_required` - wrap your resolver with this decorator to ensure the resolver is called only for logged-in users.
     
 ```python
```

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/decorators.py` & `chowkidar-strawberry-0.2.5/chowkidar/decorators.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/extension.py` & `chowkidar-strawberry-0.2.5/chowkidar/extension.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/models.py` & `chowkidar-strawberry-0.2.5/chowkidar/models.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/settings.py` & `chowkidar-strawberry-0.2.5/chowkidar/settings.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/utils/cookie.py` & `chowkidar-strawberry-0.2.5/chowkidar/utils/cookie.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/utils/jwt.py` & `chowkidar-strawberry-0.2.5/chowkidar/utils/jwt.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/view.py` & `chowkidar-strawberry-0.2.5/chowkidar/view.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar/wrappers.py` & `chowkidar-strawberry-0.2.5/chowkidar/wrappers.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/PKG-INFO` & `chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 Metadata-Version: 2.1
 Name: chowkidar-strawberry
-Version: 0.2.4
+Version: 0.2.5
 Summary: All-in-One JWT Authentication plugin for Strawberry
 Home-page: https://github.com/traboda/chowkidar
 Author: Ashwin Shenoy
 Author-email: ashwin@traboda.com
 Maintainer: Ashwin Shenoy
 Maintainer-email: ashwin@traboda.com
 License: GNU-GPL-V3
-Platform: UNKNOWN
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Development Status :: 4 - Beta
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
@@ -35,15 +34,15 @@
 
 1. Install the package from PyPI:
 
 ```bash
 pip install chowkidar-strawberry
 ```
 
-2. Add `chowkidar_strawberry` to your `INSTALLED_APPS`:
+2. Add `chowkidar` to your `INSTALLED_APPS`:
 
 ```python
 INSTALLED_APPS = [
     ...
     "chowkidar",
 ]
 ```
@@ -56,15 +55,15 @@
 schema = strawberry.Schema(
     query=Query,
     mutation=Mutation,
     extensions=[JWTAuthExtension],
 )
 ```
 
-4. Wrap your Strawberry GraphQL view with `chowkidar.view.auth_enabled_view`:
+4. Wrap your Strawberry GraphQL view with `chowkidar.view.auth_enabled_view` in your `urls.py`:
 
 ```python
 from chowkidar.view import auth_enabled_view
 
 urlpatterns = [
   ...
   path(
@@ -72,58 +71,71 @@
       auth_enabled_view(
           GraphQLView.as_view(schema=schema, graphiql=settings.DEBUG)
       )
   ),
 ]
 ```
 
-5. Create a Refresh Token Model inheriting the `chowkidar.models.AbstractRefreshToken` abstract model:
+5. Create a Refresh Token Model in an app of your choice inheriting the `chowkidar.models.AbstractRefreshToken` abstract model:
 
 ```python
 class RefreshToken(AbstractRefreshToken, models.Model):
     pass
 ```
 
 (do not forget run to `python manage.py makemigrations` and `python manage.py migrate`)
 
-6. Implement Mutations for `login` and `logout` with `issue_tokens_on_login` and `revoke_tokens_on_logout` respectively:
+6. Add 'REFRESH_TOKEN_MODEL' to your `settings.py` and point it to the Refresh Token Model you created in the previous step:
+
+```python
+REFRESH_TOKEN_MODEL = '<your app>.RefreshToken'
+```
+
+7. Implement Mutations for `login` and `logout` with `issue_tokens_on_login` and `revoke_tokens_on_logout` respectively:
 
 ```python
 import strawberry
 from chowkidar.wrappers import issue_tokens_on_login, revoke_tokens_on_logout
+from chowkidar.authentication import authenticate  # You may also use your own authentication methods or other methods like `authenticate_with_email` from chowkidar as well.
+
 
 @strawberry.type
 class AuthMutations:
-  
+
   @strawberry.mutation
   @issue_tokens_on_login
   def login(self, info, username: str, password: str) -> bool:
-      user = authenticate(username=username, password=password)
-      if user is None:
-          raise Exception("Invalid username or password")
-      
-      # Set LOGIN_USER with the authenticated user's object, in case of successful authentication
-      # else, set LOGIN_USER to None
-      info.context.LOGIN_USER = user
-      
-      return True
-  
+    user = authenticate(username=username, password=password)
+    if user is None:
+      raise Exception("Invalid username or password")
+
+    # Set LOGIN_USER with the authenticated user's object, in case of successful authentication
+    # else, set LOGIN_USER to None
+    info.context.LOGIN_USER = user
+
+    return True
+
   @strawberry.mutation
   @revoke_tokens_on_logout
   def logout(self, info) -> bool:
-      # Set info.context.LOGIN_USER to True for logging out the user
-      info.context.LOGOUT_USER = True
-      
-      return True
+    # Set info.context.LOGIN_USER to True for logging out the user
+    info.context.LOGOUT_USER = True
+
+    return True
 ```
 
 All your resolvers will now get the following parameters from `info.context` -
  - `info.context.userID` - ID of the requesting user, None if not logged-in 
  - `info.context.refreshToken`- Refresh token string of the requesting user, None if not logged-in
 
+Chowkidar comes with 3 authentication methods (importable from `chowkidar.authentication`), which you may use -
+1. `authenticate_with_email` - authenticate with email and password
+2. `authenticate_with_username` - authenticate with username and password
+3. `authenticate` - authenticate with username or email and password
+
 ## Decorators
 
 You can use these decorators
 
 1. `@login_required` - wrap your resolver with this decorator to ensure the resolver is called only for logged-in users.
     
 ```python
@@ -253,8 +265,7 @@
 Contributions are welcome. Please open an issue or a PR.
 
 ## License
 
 This project is licensed under the [GNU General Public License V3](LICENSE).
 
 Made by [Traboda](https://github.com/traboda/chowkidar) with ❤️ in India 🇮🇳.
-
```

### Comparing `chowkidar-strawberry-0.2.4/chowkidar_strawberry.egg-info/SOURCES.txt` & `chowkidar-strawberry-0.2.5/chowkidar_strawberry.egg-info/SOURCES.txt`

 * *Files 16% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 LICENSE
 MANIFEST.in
 README.md
 setup.cfg
 setup.py
 chowkidar/__init__.py
+chowkidar/authentication.py
 chowkidar/decorators.py
 chowkidar/extension.py
 chowkidar/models.py
 chowkidar/settings.py
 chowkidar/view.py
 chowkidar/wrappers.py
 chowkidar/utils/__init__.py
```

### Comparing `chowkidar-strawberry-0.2.4/setup.cfg` & `chowkidar-strawberry-0.2.5/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = chowkidar-strawberry
-version = 0.2.4
+version = 0.2.5
 description = All-in-One JWT Authentication plugin for Strawberry
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/traboda/chowkidar
 author = Ashwin Shenoy
 author_email = ashwin@traboda.com
 maintainer = Ashwin Shenoy
```


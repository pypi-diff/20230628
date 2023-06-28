# Comparing `tmp/chowkidar-strawberry-0.2.6.tar.gz` & `tmp/chowkidar-strawberry-0.2.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chowkidar-strawberry-0.2.6.tar", last modified: Wed Jun 28 11:02:58 2023, max compression
+gzip compressed data, was "chowkidar-strawberry-0.2.7.tar", last modified: Wed Jun 28 11:50:47 2023, max compression
```

## Comparing `chowkidar-strawberry-0.2.6.tar` & `chowkidar-strawberry-0.2.7.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:02:58.496146 chowkidar-strawberry-0.2.6/
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)    35029 2022-09-20 17:56:11.000000 chowkidar-strawberry-0.2.6/LICENSE
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)       33 2022-09-20 21:39:18.000000 chowkidar-strawberry-0.2.6/MANIFEST.in
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     9251 2023-06-28 11:02:58.496250 chowkidar-strawberry-0.2.6/PKG-INFO
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     8171 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.6/README.md
-drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:02:58.494594 chowkidar-strawberry-0.2.6/chowkidar/
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)        0 2022-09-20 17:06:06.000000 chowkidar-strawberry-0.2.6/chowkidar/__init__.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2061 2023-06-28 11:01:17.000000 chowkidar-strawberry-0.2.6/chowkidar/authentication.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1789 2022-09-22 09:55:22.000000 chowkidar-strawberry-0.2.6/chowkidar/decorators.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     7607 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.6/chowkidar/extension.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2407 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.6/chowkidar/models.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2082 2022-09-28 09:26:14.000000 chowkidar-strawberry-0.2.6/chowkidar/settings.py
-drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:02:58.495207 chowkidar-strawberry-0.2.6/chowkidar/utils/
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)      852 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.6/chowkidar/utils/__init__.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1492 2022-09-20 20:57:17.000000 chowkidar-strawberry-0.2.6/chowkidar/utils/cookie.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)      920 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.6/chowkidar/utils/exceptions.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2630 2022-09-20 20:57:17.000000 chowkidar-strawberry-0.2.6/chowkidar/utils/jwt.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2752 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.6/chowkidar/view.py
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2414 2022-09-29 08:20:04.000000 chowkidar-strawberry-0.2.6/chowkidar/wrappers.py
-drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:02:58.495993 chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     9251 2023-06-28 11:02:58.000000 chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/PKG-INFO
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)      553 2023-06-28 11:02:58.000000 chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/SOURCES.txt
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)        1 2023-06-28 11:02:58.000000 chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/dependency_links.txt
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)        1 2023-06-28 11:02:58.000000 chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/not-zip-safe
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)       10 2023-06-28 11:02:58.000000 chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/top_level.txt
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1133 2023-06-28 11:02:58.496674 chowkidar-strawberry-0.2.6/setup.cfg
--rw-r--r--   0 ashwinshenoy   (501) staff       (20)      262 2022-10-06 08:12:09.000000 chowkidar-strawberry-0.2.6/setup.py
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:50:47.126338 chowkidar-strawberry-0.2.7/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)    35029 2022-09-20 17:56:11.000000 chowkidar-strawberry-0.2.7/LICENSE
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)       33 2022-09-20 21:39:18.000000 chowkidar-strawberry-0.2.7/MANIFEST.in
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     9251 2023-06-28 11:50:47.126434 chowkidar-strawberry-0.2.7/PKG-INFO
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     8171 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.7/README.md
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:50:47.124388 chowkidar-strawberry-0.2.7/chowkidar/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)        0 2022-09-20 17:06:06.000000 chowkidar-strawberry-0.2.7/chowkidar/__init__.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2069 2023-06-28 11:50:30.000000 chowkidar-strawberry-0.2.7/chowkidar/authentication.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1789 2022-09-22 09:55:22.000000 chowkidar-strawberry-0.2.7/chowkidar/decorators.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     7607 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.7/chowkidar/extension.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2407 2023-06-28 10:06:53.000000 chowkidar-strawberry-0.2.7/chowkidar/models.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2082 2022-09-28 09:26:14.000000 chowkidar-strawberry-0.2.7/chowkidar/settings.py
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:50:47.125271 chowkidar-strawberry-0.2.7/chowkidar/utils/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      852 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.7/chowkidar/utils/__init__.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1492 2022-09-20 20:57:17.000000 chowkidar-strawberry-0.2.7/chowkidar/utils/cookie.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      920 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.7/chowkidar/utils/exceptions.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2630 2022-09-20 20:57:17.000000 chowkidar-strawberry-0.2.7/chowkidar/utils/jwt.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2752 2023-06-28 10:06:54.000000 chowkidar-strawberry-0.2.7/chowkidar/view.py
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     2414 2022-09-29 08:20:04.000000 chowkidar-strawberry-0.2.7/chowkidar/wrappers.py
+drwxr-xr-x   0 ashwinshenoy   (501) staff       (20)        0 2023-06-28 11:50:47.126198 chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     9251 2023-06-28 11:50:47.000000 chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/PKG-INFO
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      553 2023-06-28 11:50:47.000000 chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/SOURCES.txt
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)        1 2023-06-28 11:50:47.000000 chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/dependency_links.txt
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)        1 2023-06-28 11:50:47.000000 chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/not-zip-safe
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)       10 2023-06-28 11:50:47.000000 chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/top_level.txt
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)     1133 2023-06-28 11:50:47.126850 chowkidar-strawberry-0.2.7/setup.cfg
+-rw-r--r--   0 ashwinshenoy   (501) staff       (20)      262 2022-10-06 08:12:09.000000 chowkidar-strawberry-0.2.7/setup.py
```

### Comparing `chowkidar-strawberry-0.2.6/LICENSE` & `chowkidar-strawberry-0.2.7/LICENSE`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/PKG-INFO` & `chowkidar-strawberry-0.2.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chowkidar-strawberry
-Version: 0.2.6
+Version: 0.2.7
 Summary: All-in-One JWT Authentication plugin for Strawberry
 Home-page: https://github.com/traboda/chowkidar
 Author: Ashwin Shenoy
 Author-email: ashwin@traboda.com
 Maintainer: Ashwin Shenoy
 Maintainer-email: ashwin@traboda.com
 License: GNU-GPL-V3
```

### Comparing `chowkidar-strawberry-0.2.6/README.md` & `chowkidar-strawberry-0.2.7/README.md`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/authentication.py` & `chowkidar-strawberry-0.2.7/chowkidar/authentication.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,15 +19,15 @@
             msg = 'The email or password you entered is wrong'
         raise AuthError(message=msg, code='INVALID_CREDENTIALS')
     return user
 
 
 def authenticate_with_email(password: str, email: str, request: Optional[HttpRequest] = None) -> User:
     try:
-        username = User.objects.get(email=validate_email(email)).username
+        username = User.objects.get(email__iexact=validate_email(email)).username
         return authenticate_with_username(password=password, username=username, request=request)
     except User.DoesNotExist:
         raise AuthError(message='An account with this email address does not exist', code='EMAIL_NOT_FOUND')
     except User.MultipleObjectsReturned:
         raise AuthError(
             message='We cannot authenticate you with your email address, please enter your username',
             code='EMAIL_NOT_UNIQUE'
```

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/decorators.py` & `chowkidar-strawberry-0.2.7/chowkidar/decorators.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/extension.py` & `chowkidar-strawberry-0.2.7/chowkidar/extension.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/models.py` & `chowkidar-strawberry-0.2.7/chowkidar/models.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/settings.py` & `chowkidar-strawberry-0.2.7/chowkidar/settings.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/utils/__init__.py` & `chowkidar-strawberry-0.2.7/chowkidar/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/utils/cookie.py` & `chowkidar-strawberry-0.2.7/chowkidar/utils/cookie.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/utils/exceptions.py` & `chowkidar-strawberry-0.2.7/chowkidar/utils/exceptions.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/utils/jwt.py` & `chowkidar-strawberry-0.2.7/chowkidar/utils/jwt.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/view.py` & `chowkidar-strawberry-0.2.7/chowkidar/view.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar/wrappers.py` & `chowkidar-strawberry-0.2.7/chowkidar/wrappers.py`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/PKG-INFO` & `chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chowkidar-strawberry
-Version: 0.2.6
+Version: 0.2.7
 Summary: All-in-One JWT Authentication plugin for Strawberry
 Home-page: https://github.com/traboda/chowkidar
 Author: Ashwin Shenoy
 Author-email: ashwin@traboda.com
 Maintainer: Ashwin Shenoy
 Maintainer-email: ashwin@traboda.com
 License: GNU-GPL-V3
```

### Comparing `chowkidar-strawberry-0.2.6/chowkidar_strawberry.egg-info/SOURCES.txt` & `chowkidar-strawberry-0.2.7/chowkidar_strawberry.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `chowkidar-strawberry-0.2.6/setup.cfg` & `chowkidar-strawberry-0.2.7/setup.cfg`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = chowkidar-strawberry
-version = 0.2.6
+version = 0.2.7
 description = All-in-One JWT Authentication plugin for Strawberry
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/traboda/chowkidar
 author = Ashwin Shenoy
 author_email = ashwin@traboda.com
 maintainer = Ashwin Shenoy
```


# Comparing `tmp/sentry-ldap-1.0.0.tar.gz` & `tmp/sentry-ldap-1.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sentry-ldap-1.0.0.tar", last modified: Wed Jun 28 05:50:03 2023, max compression
+gzip compressed data, was "sentry-ldap-1.2.0.tar", last modified: Wed Jun 28 07:24:46 2023, max compression
```

## Comparing `sentry-ldap-1.0.0.tar` & `sentry-ldap-1.2.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:50:03.389210 sentry-ldap-1.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-28 05:49:53.000000 sentry-ldap-1.0.0/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 05:50:03.389210 sentry-ldap-1.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 05:49:53.000000 sentry-ldap-1.0.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:50:03.389210 sentry-ldap-1.0.0/sentry_ldap/
--rw-r--r--   0 runner    (1001) docker     (123)     3800 2023-06-28 05:49:53.000000 sentry-ldap-1.0.0/sentry_ldap/backend.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:50:03.389210 sentry-ldap-1.0.0/sentry_ldap.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 05:50:03.000000 sentry-ldap-1.0.0/sentry_ldap.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      271 2023-06-28 05:50:03.000000 sentry-ldap-1.0.0/sentry_ldap.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 05:50:03.000000 sentry-ldap-1.0.0/sentry_ldap.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 05:50:03.000000 sentry-ldap-1.0.0/sentry_ldap.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 05:50:03.000000 sentry-ldap-1.0.0/sentry_ldap.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 05:50:03.000000 sentry-ldap-1.0.0/sentry_ldap.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-28 05:50:03.389210 sentry-ldap-1.0.0/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     1465 2023-06-28 05:49:53.000000 sentry-ldap-1.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:24:46.339679 sentry-ldap-1.2.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-28 07:24:36.000000 sentry-ldap-1.2.0/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 07:24:46.339679 sentry-ldap-1.2.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 07:24:36.000000 sentry-ldap-1.2.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:24:46.339679 sentry-ldap-1.2.0/sentry_ldap/
+-rw-r--r--   0 runner    (1001) docker     (123)     4100 2023-06-28 07:24:36.000000 sentry-ldap-1.2.0/sentry_ldap/backend.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:24:46.339679 sentry-ldap-1.2.0/sentry_ldap.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 07:24:46.000000 sentry-ldap-1.2.0/sentry_ldap.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      271 2023-06-28 07:24:46.000000 sentry-ldap-1.2.0/sentry_ldap.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:24:46.000000 sentry-ldap-1.2.0/sentry_ldap.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:24:46.000000 sentry-ldap-1.2.0/sentry_ldap.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 07:24:46.000000 sentry-ldap-1.2.0/sentry_ldap.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 07:24:46.000000 sentry-ldap-1.2.0/sentry_ldap.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-28 07:24:46.339679 sentry-ldap-1.2.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1465 2023-06-28 07:24:36.000000 sentry-ldap-1.2.0/setup.py
```

### Comparing `sentry-ldap-1.0.0/LICENSE.txt` & `sentry-ldap-1.2.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `sentry-ldap-1.0.0/PKG-INFO` & `sentry-ldap-1.2.0/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sentry-ldap
-Version: 1.0.0
+Version: 1.2.0
 Summary: A Sentry extension to add an LDAP server as an authentication source.
 Home-page: https://github.com/huynhminhtan/sentry-ldap
 Download-URL: https://github.com/huynhminhtan/sentry-ldap
 Author: 
 Author-email: 
 License: Apache-2.0
 Project-URL: Bug Tracker, https://github.com/huynhminhtan/sentry-ldap/issues
```

### Comparing `sentry-ldap-1.0.0/sentry_ldap/backend.py` & `sentry-ldap-1.2.0/sentry_ldap/backend.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+import logging
 import re
 from django_auth_ldap.backend import LDAPBackend
 from django.conf import settings
 from sentry.models import (
     Organization,
     OrganizationMember,
     UserEmail,
@@ -30,21 +31,29 @@
         return None
 
     highest_role = [role for role in role_priority_order if role in applicable_roles][-1]
     return highest_role
 
 
 class SentryLdapBackend(LDAPBackend):
+    def __init__(self, *args, **kwargs):
+        super().__init__(*args, **kwargs)
+        self.logger = logging.getLogger('ldap_logger')
+
     # Override ldap_to_django_username to preprocess the LDAP user
     def ldap_to_django_username(self, username):
         # Remove the domain part from the username
+        self.logger.debug(f'Preprocessed LDAP username: {username}')
+
         email_pattern = re.compile(r'^(.+)@')
         match = email_pattern.match(username)
         if match:
             username = match.group(1)
+
+        self.logger.debug(f'Preprocessed LDAP after username: {username}')
         return super().ldap_to_django_username(username)
 
     def get_or_build_user(self, username, ldap_user):
         (user, built) = super().get_or_build_user(username, ldap_user)
 
         user.is_managed = True
```

### Comparing `sentry-ldap-1.0.0/sentry_ldap.egg-info/PKG-INFO` & `sentry-ldap-1.2.0/sentry_ldap.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sentry-ldap
-Version: 1.0.0
+Version: 1.2.0
 Summary: A Sentry extension to add an LDAP server as an authentication source.
 Home-page: https://github.com/huynhminhtan/sentry-ldap
 Download-URL: https://github.com/huynhminhtan/sentry-ldap
 Author: 
 Author-email: 
 License: Apache-2.0
 Project-URL: Bug Tracker, https://github.com/huynhminhtan/sentry-ldap/issues
```

### Comparing `sentry-ldap-1.0.0/setup.py` & `sentry-ldap-1.2.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 install_requires = [
     'django-auth-ldap==4.1.0',
     'sentry>=23.6.0',
 ]
 
 setup(
     name='sentry-ldap',
-    version='1.0.0',
+    version='1.2.0',
     author='',
     author_email='',
     url='https://github.com/huynhminhtan/sentry-ldap',
     description='A Sentry extension to add an LDAP server as an authentication source.',
     long_description=long_description,
     long_description_content_type='text/markdown',
     packages=find_namespace_packages(),
```


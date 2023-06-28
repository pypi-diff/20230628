# Comparing `tmp/sentry-ldap-1.2.1.tar.gz` & `tmp/sentry-ldap-1.2.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sentry-ldap-1.2.1.tar", last modified: Wed Jun 28 07:37:01 2023, max compression
+gzip compressed data, was "sentry-ldap-1.2.3.tar", last modified: Wed Jun 28 10:35:20 2023, max compression
```

## Comparing `sentry-ldap-1.2.1.tar` & `sentry-ldap-1.2.3.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:37:01.921895 sentry-ldap-1.2.1/
--rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-28 07:36:49.000000 sentry-ldap-1.2.1/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 07:37:01.921895 sentry-ldap-1.2.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 07:36:49.000000 sentry-ldap-1.2.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:37:01.917895 sentry-ldap-1.2.1/sentry_ldap/
--rw-r--r--   0 runner    (1001) docker     (123)     4175 2023-06-28 07:36:49.000000 sentry-ldap-1.2.1/sentry_ldap/backend.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:37:01.921895 sentry-ldap-1.2.1/sentry_ldap.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 07:37:01.000000 sentry-ldap-1.2.1/sentry_ldap.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      271 2023-06-28 07:37:01.000000 sentry-ldap-1.2.1/sentry_ldap.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:37:01.000000 sentry-ldap-1.2.1/sentry_ldap.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:37:01.000000 sentry-ldap-1.2.1/sentry_ldap.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 07:37:01.000000 sentry-ldap-1.2.1/sentry_ldap.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 07:37:01.000000 sentry-ldap-1.2.1/sentry_ldap.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-28 07:37:01.921895 sentry-ldap-1.2.1/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     1465 2023-06-28 07:36:49.000000 sentry-ldap-1.2.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:35:20.893662 sentry-ldap-1.2.3/
+-rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-28 10:35:10.000000 sentry-ldap-1.2.3/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 10:35:20.893662 sentry-ldap-1.2.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 10:35:10.000000 sentry-ldap-1.2.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:35:20.889662 sentry-ldap-1.2.3/sentry_ldap/
+-rw-r--r--   0 runner    (1001) docker     (123)     4065 2023-06-28 10:35:10.000000 sentry-ldap-1.2.3/sentry_ldap/backend.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:35:20.893662 sentry-ldap-1.2.3/sentry_ldap.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 10:35:20.000000 sentry-ldap-1.2.3/sentry_ldap.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      271 2023-06-28 10:35:20.000000 sentry-ldap-1.2.3/sentry_ldap.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:35:20.000000 sentry-ldap-1.2.3/sentry_ldap.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:35:20.000000 sentry-ldap-1.2.3/sentry_ldap.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 10:35:20.000000 sentry-ldap-1.2.3/sentry_ldap.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 10:35:20.000000 sentry-ldap-1.2.3/sentry_ldap.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-28 10:35:20.893662 sentry-ldap-1.2.3/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1465 2023-06-28 10:35:10.000000 sentry-ldap-1.2.3/setup.py
```

### Comparing `sentry-ldap-1.2.1/LICENSE.txt` & `sentry-ldap-1.2.3/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `sentry-ldap-1.2.1/PKG-INFO` & `sentry-ldap-1.2.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sentry-ldap
-Version: 1.2.1
+Version: 1.2.3
 Summary: A Sentry extension to add an LDAP server as an authentication source.
 Home-page: https://github.com/huynhminhtan/sentry-ldap
 Download-URL: https://github.com/huynhminhtan/sentry-ldap
 Author: 
 Author-email: 
 License: Apache-2.0
 Project-URL: Bug Tracker, https://github.com/huynhminhtan/sentry-ldap/issues
```

### Comparing `sentry-ldap-1.2.1/sentry_ldap/backend.py` & `sentry-ldap-1.2.3/sentry_ldap/backend.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,18 +1,19 @@
-import logging
-import re
 from django_auth_ldap.backend import LDAPBackend
 from django.conf import settings
 from sentry.models import (
     Organization,
     OrganizationMember,
     UserEmail,
     UserOption,
 )
+import re
+import logging
 
+logger = logging.getLogger('django_auth_ldap')
 
 def _get_effective_sentry_role(ldap_user):
     role_priority_order = [
         'member',
         'admin',
         'manager',
         'owner',
@@ -31,37 +32,33 @@
         return None
 
     highest_role = [role for role in role_priority_order if role in applicable_roles][-1]
     return highest_role
 
 
 class SentryLdapBackend(LDAPBackend):
-    def __init__(self, *args, **kwargs):
-        super().__init__(*args, **kwargs)
-        self.logger = logging.getLogger('ldap_logger')
-
     # Override ldap_to_django_username to preprocess the LDAP user
     def ldap_to_django_username(self, username):
         # Remove the domain part from the username
-        self.logger.debug(f'Preprocessed LDAP username: {username}')
+        logger.info(f'Preprocessed LDAP username: {username}')
 
         email_pattern = re.compile(r'^(.+)@')
         match = email_pattern.match(username)
         if match:
             username = match.group(1)
 
-        self.logger.debug(f'Preprocessed LDAP after username: {username}')
+        logger.info(f'Preprocessed LDAP after username: {username}')
         return super().ldap_to_django_username(username)
 
     def get_or_build_user(self, username, ldap_user):
         (user, built) = super().get_or_build_user(username, ldap_user)
 
         user.is_managed = True
 
-        self.logger.debug(f'get_or_build_user LDAP username: {username}')
+        logger.info(f'get_or_build_user LDAP username: {username}')
 
         # Add the user email address
         mail_attr_name = self.settings.USER_ATTR_MAP.get('email', 'mail')
         mail_attr = ldap_user.attrs.get(mail_attr_name)
         if mail_attr:
             email = mail_attr[0]
         elif hasattr(settings, 'AUTH_LDAP_DEFAULT_EMAIL_DOMAIN'):
```

### Comparing `sentry-ldap-1.2.1/sentry_ldap.egg-info/PKG-INFO` & `sentry-ldap-1.2.3/sentry_ldap.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sentry-ldap
-Version: 1.2.1
+Version: 1.2.3
 Summary: A Sentry extension to add an LDAP server as an authentication source.
 Home-page: https://github.com/huynhminhtan/sentry-ldap
 Download-URL: https://github.com/huynhminhtan/sentry-ldap
 Author: 
 Author-email: 
 License: Apache-2.0
 Project-URL: Bug Tracker, https://github.com/huynhminhtan/sentry-ldap/issues
```

### Comparing `sentry-ldap-1.2.1/setup.py` & `sentry-ldap-1.2.3/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 install_requires = [
     'django-auth-ldap==4.1.0',
     'sentry>=23.6.0',
 ]
 
 setup(
     name='sentry-ldap',
-    version='1.2.1',
+    version='1.2.3',
     author='',
     author_email='',
     url='https://github.com/huynhminhtan/sentry-ldap',
     description='A Sentry extension to add an LDAP server as an authentication source.',
     long_description=long_description,
     long_description_content_type='text/markdown',
     packages=find_namespace_packages(),
```


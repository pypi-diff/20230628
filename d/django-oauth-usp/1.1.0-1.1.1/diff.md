# Comparing `tmp/django_oauth_usp-1.1.0.tar.gz` & `tmp/django_oauth_usp-1.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django_oauth_usp-1.1.0.tar", last modified: Thu Dec  9 17:30:08 2021, max compression
+gzip compressed data, was "django_oauth_usp-1.1.1.tar", max compression
```

## Comparing `django_oauth_usp-1.1.0.tar` & `django_oauth_usp-1.1.1.tar`

### file list

```diff
@@ -1,42 +1,31 @@
-drwxrwxr-x   0 schneider  (1000) schneider  (1000)        0 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1068 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/LICENSE
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2449 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/PKG-INFO
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1761 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/README.rst
-drwxrwxr-x   0 schneider  (1000) schneider  (1000)        0 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/django_oauth_usp/
--rw-rw-r--   0 schneider  (1000) schneider  (1000)        0 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/__init__.py
-drwxrwxr-x   0 schneider  (1000) schneider  (1000)        0 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/django_oauth_usp/accounts/
--rw-rw-r--   0 schneider  (1000) schneider  (1000)        0 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/__init__.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      402 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/admin.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      108 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/apps.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     3122 2021-12-09 14:35:19.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/managers.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      555 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/middleware.py
-drwxrwxr-x   0 schneider  (1000) schneider  (1000)        0 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/django_oauth_usp/accounts/migrations/
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2557 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/migrations/0001_initial.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)        0 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/migrations/__init__.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2288 2021-12-09 14:33:47.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/models.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1395 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/oauth.py
-drwxrwxr-x   0 schneider  (1000) schneider  (1000)        0 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/
--rw-rw-r--   0 schneider  (1000) schneider  (1000)        0 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/__init__.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1076 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/faker.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1985 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/mock.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      346 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_admin.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      324 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_manager.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2964 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_models.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1224 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_transform.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     4494 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_views.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1213 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_oauth.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      912 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_user_middleware.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      764 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/transform.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      361 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/urls.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2720 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/accounts/views.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2316 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/settings.py
--rw-rw-r--   0 schneider  (1000) schneider  (1000)      115 2021-12-09 13:48:42.000000 django_oauth_usp-1.1.0/django_oauth_usp/urls.py
-drwxrwxr-x   0 schneider  (1000) schneider  (1000)        0 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     2449 2021-12-09 17:30:08.000000 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/PKG-INFO
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1333 2021-12-09 17:30:08.000000 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/SOURCES.txt
--rw-rw-r--   0 schneider  (1000) schneider  (1000)        1 2021-12-09 17:30:08.000000 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/dependency_links.txt
--rw-rw-r--   0 schneider  (1000) schneider  (1000)        1 2021-12-09 16:50:53.000000 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/not-zip-safe
--rw-rw-r--   0 schneider  (1000) schneider  (1000)       44 2021-12-09 17:30:08.000000 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/requires.txt
--rw-rw-r--   0 schneider  (1000) schneider  (1000)       17 2021-12-09 17:30:08.000000 django_oauth_usp-1.1.0/django_oauth_usp.egg-info/top_level.txt
--rw-rw-r--   0 schneider  (1000) schneider  (1000)       73 2021-12-09 17:30:08.478379 django_oauth_usp-1.1.0/setup.cfg
--rw-rw-r--   0 schneider  (1000) schneider  (1000)     1084 2021-12-09 17:29:35.000000 django_oauth_usp-1.1.0/setup.py
+-rw-r--r--   0        0        0     1068 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/LICENSE
+-rw-r--r--   0        0        0     1761 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/__init__.py
+-rw-r--r--   0        0        0      402 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/admin.py
+-rw-r--r--   0        0        0      108 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/apps.py
+-rw-r--r--   0        0        0     3123 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/managers.py
+-rw-r--r--   0        0        0      555 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/middleware.py
+-rw-r--r--   0        0        0     2557 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/migrations/0001_initial.py
+-rw-r--r--   0        0        0        0 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/migrations/__init__.py
+-rw-r--r--   0        0        0     2289 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/models.py
+-rw-r--r--   0        0        0     1395 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/oauth.py
+-rw-r--r--   0        0        0      180 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/templates/main.html
+-rw-r--r--   0        0        0      624 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/templates/user.html
+-rw-r--r--   0        0        0        0 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/__init__.py
+-rw-r--r--   0        0        0     1076 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/faker.py
+-rw-r--r--   0        0        0     1985 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/mock.py
+-rw-r--r--   0        0        0      346 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_admin.py
+-rw-r--r--   0        0        0      324 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_manager.py
+-rw-r--r--   0        0        0     2964 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_models.py
+-rw-r--r--   0        0        0     1224 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_transform.py
+-rw-r--r--   0        0        0     4494 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_views.py
+-rw-r--r--   0        0        0     1213 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_oauth.py
+-rw-r--r--   0        0        0      912 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_user_middleware.py
+-rw-r--r--   0        0        0      764 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/transform.py
+-rw-r--r--   0        0        0      361 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/urls.py
+-rw-r--r--   0        0        0     2720 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/accounts/views.py
+-rw-r--r--   0        0        0     2316 2023-06-28 10:48:52.546683 django_oauth_usp-1.1.1/django_oauth_usp/settings.py
+-rw-r--r--   0        0        0      115 2023-06-28 10:48:52.550016 django_oauth_usp-1.1.1/django_oauth_usp/urls.py
+-rw-r--r--   0        0        0      536 2023-06-28 11:17:22.154848 django_oauth_usp-1.1.1/pyproject.toml
+-rw-r--r--   0        0        0     2312 1970-01-01 00:00:00.000000 django_oauth_usp-1.1.1/PKG-INFO
```

### Comparing `django_oauth_usp-1.1.0/LICENSE` & `django_oauth_usp-1.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/README.rst` & `django_oauth_usp-1.1.1/README.md`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/managers.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/managers.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from django.contrib.auth.models import BaseUserManager
-from django.utils.translation import gettext_lazy as _
+from django.utils.translation import ugettext_lazy as _
 from django.utils import timezone
 
 
 class UserManager(BaseUserManager):
     def _create_user(self, login, name, user_type, main_email, password,
                      is_staff, is_superuser, **extra_fields):
```

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/middleware.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/middleware.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/migrations/0001_initial.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/models.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/models.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import json
 from django.db import models
 from django.contrib.auth.models import AbstractBaseUser, PermissionsMixin
-from django.utils.translation import gettext_lazy as _
+from django.utils.translation import ugettext_lazy as _
 from django.core.mail import send_mail
 from django.conf import settings
 
 from .managers import UserManager
 
 
 class UserModel(AbstractBaseUser, PermissionsMixin):
```

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/oauth.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/oauth.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/faker.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/faker.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/mock.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/mock.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_models.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_models.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_transform.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_transform.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_accounts_views.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_accounts_views.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_oauth.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_oauth.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/tests/test_user_middleware.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/tests/test_user_middleware.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/transform.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/transform.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/accounts/views.py` & `django_oauth_usp-1.1.1/django_oauth_usp/accounts/views.py`

 * *Files identical despite different names*

### Comparing `django_oauth_usp-1.1.0/django_oauth_usp/settings.py` & `django_oauth_usp-1.1.1/django_oauth_usp/settings.py`

 * *Files identical despite different names*


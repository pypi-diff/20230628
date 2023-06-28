# Comparing `tmp/python_tldap-1.0.7.tar.gz` & `tmp/python_tldap-1.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "python_tldap-1.0.7.tar", max compression
+gzip compressed data, was "python_tldap-1.0.8.tar", max compression
```

## Comparing `python_tldap-1.0.7.tar` & `python_tldap-1.0.8.tar`

### file list

```diff
@@ -1,39 +1,39 @@
--rw-r--r--   0        0        0      410 2023-06-09 04:44:12.801242 python_tldap-1.0.7/README.rst
--rw-r--r--   0        0        0     1322 2023-06-09 04:44:12.801242 python_tldap-1.0.7/pyproject.toml
--rw-r--r--   0        0        0     1024 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/__init__.py
--rw-r--r--   0        0        0     2141 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/backend/__init__.py
--rw-r--r--   0        0        0     8635 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/backend/base.py
--rw-r--r--   0        0        0    13485 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/backend/fake_transactions.py
--rw-r--r--   0        0        0     3836 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/backend/no_transactions.py
--rw-r--r--   0        0        0    20957 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/database/__init__.py
--rw-r--r--   0        0        0    12564 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/database/helpers.py
--rw-r--r--   0        0        0     4085 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/dict.py
--rw-r--r--   0        0        0     1981 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/__init__.py
--rw-r--r--   0        0        0      154 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/apps.py
--rw-r--r--   0        0        0     2452 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/helpers.py
--rw-r--r--   0        0        0     1759 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/middleware.py
--rw-r--r--   0        0        0      759 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/migrations/0001_initial.py
--rw-r--r--   0        0        0        0 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/migrations/__init__.py
--rw-r--r--   0        0        0     1600 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/django/models.py
--rw-r--r--   0        0        0    13204 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/dn.py
--rw-r--r--   0        0        0     1494 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/exceptions.py
--rw-r--r--   0        0        0    15773 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/fields.py
--rw-r--r--   0        0        0     1852 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/filter.py
--rw-r--r--   0        0        0     1524 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/ldap_passwd.py
--rw-r--r--   0        0        0     5474 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/modlist.py
--rw-r--r--   0        0        0     5378 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/query.py
--rw-r--r--   0        0        0     1740 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/query_utils.py
--rw-r--r--   0        0        0      706 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/__init__.py
--rw-r--r--   0        0        0    20346 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/00-core.schema
--rw-r--r--   0        0        0    14030 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/10-cosine.schema
--rw-r--r--   0        0        0     6360 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/50-inetorgperson.schema
--rw-r--r--   0        0        0     4204 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/70-eduperson.schema
--rw-r--r--   0        0        0    14617 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/90-aueduperson.schema
--rw-r--r--   0        0        0    19957 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/90-schac.schema
--rw-r--r--   0        0        0     7723 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/ldap_schemas/nis.schema
--rw-r--r--   0        0        0    15901 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/test/slapd.py
--rw-r--r--   0        0        0     7902 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/transaction.py
--rw-r--r--   0        0        0     4915 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/tree.py
--rw-r--r--   0        0        0     1651 2023-06-09 04:44:12.805242 python_tldap-1.0.7/tldap/utils.py
--rw-r--r--   0        0        0     1325 1970-01-01 00:00:00.000000 python_tldap-1.0.7/setup.py
--rw-r--r--   0        0        0     1566 1970-01-01 00:00:00.000000 python_tldap-1.0.7/PKG-INFO
+-rw-r--r--   0        0        0      410 2023-06-28 01:32:15.695538 python_tldap-1.0.8/README.rst
+-rw-r--r--   0        0        0     1357 2023-06-28 01:32:15.695538 python_tldap-1.0.8/pyproject.toml
+-rw-r--r--   0        0        0     1024 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/__init__.py
+-rw-r--r--   0        0        0     2141 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/backend/__init__.py
+-rw-r--r--   0        0        0     8725 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/backend/base.py
+-rw-r--r--   0        0        0    13485 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/backend/fake_transactions.py
+-rw-r--r--   0        0        0     3836 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/backend/no_transactions.py
+-rw-r--r--   0        0        0    20957 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/database/__init__.py
+-rw-r--r--   0        0        0    12564 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/database/helpers.py
+-rw-r--r--   0        0        0     4085 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/dict.py
+-rw-r--r--   0        0        0     1981 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/django/__init__.py
+-rw-r--r--   0        0        0      154 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/django/apps.py
+-rw-r--r--   0        0        0     2452 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/django/helpers.py
+-rw-r--r--   0        0        0     1759 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/django/middleware.py
+-rw-r--r--   0        0        0      759 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/django/migrations/0001_initial.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:32:15.695538 python_tldap-1.0.8/tldap/django/migrations/__init__.py
+-rw-r--r--   0        0        0     1600 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/django/models.py
+-rw-r--r--   0        0        0    13204 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/dn.py
+-rw-r--r--   0        0        0     1494 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/exceptions.py
+-rw-r--r--   0        0        0    15773 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/fields.py
+-rw-r--r--   0        0        0     1852 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/filter.py
+-rw-r--r--   0        0        0     1524 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/ldap_passwd.py
+-rw-r--r--   0        0        0     5474 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/modlist.py
+-rw-r--r--   0        0        0     5378 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/query.py
+-rw-r--r--   0        0        0     1740 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/query_utils.py
+-rw-r--r--   0        0        0      706 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/__init__.py
+-rw-r--r--   0        0        0    20346 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/00-core.schema
+-rw-r--r--   0        0        0    14030 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/10-cosine.schema
+-rw-r--r--   0        0        0     6360 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/50-inetorgperson.schema
+-rw-r--r--   0        0        0     4204 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/70-eduperson.schema
+-rw-r--r--   0        0        0    14617 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/90-aueduperson.schema
+-rw-r--r--   0        0        0    19957 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/90-schac.schema
+-rw-r--r--   0        0        0     7723 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/ldap_schemas/nis.schema
+-rw-r--r--   0        0        0    15901 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/test/slapd.py
+-rw-r--r--   0        0        0     7902 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/transaction.py
+-rw-r--r--   0        0        0     4915 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/tree.py
+-rw-r--r--   0        0        0     1651 2023-06-28 01:32:15.699538 python_tldap-1.0.8/tldap/utils.py
+-rw-r--r--   0        0        0     1333 1970-01-01 00:00:00.000000 python_tldap-1.0.8/setup.py
+-rw-r--r--   0        0        0     1604 1970-01-01 00:00:00.000000 python_tldap-1.0.8/PKG-INFO
```

### Comparing `python_tldap-1.0.7/pyproject.toml` & `python_tldap-1.0.8/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "python-tldap"
-version = "1.0.7"
+version = "1.0.8"
 description = "High level python LDAP Library"
 authors = ["Brian May <brian@linuxpenguins.xyz>"]
 license = "GPL3+"
 packages = [
     { include = "tldap" },
 ]
 readme = "README.rst"
@@ -25,31 +25,31 @@
 passlib = "*"
 pyasn1 = "*"
 ldap3 = "*"
 six = "*"
 pip = "*"
 django = {version = "*", optional = true}
 sphinx = {version = "*", optional = true}
+furo = {version = "*", optional = true}
 
 [tool.poetry.dev-dependencies]
 pytest = "*"
 mock = "*"
 pytest-runner = "*"
 pytest-bdd = "*"
 pytest-django = "*"
 django = "*"
-sphinx = "*"
 tox = "*"
 flake8 = "*"
 twine = "*"
 pipenv-to-requirements = "*"
 pytest-cov = "*"
 isort = "*"
 wheel = "*"
 bumpversion = "*"
 
 [tool.poetry.extras]
-docs = ["sphinx", "django"]
+docs = ["sphinx", "django", "furo"]
 
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `python_tldap-1.0.7/tldap/__init__.py` & `python_tldap-1.0.8/tldap/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,8 +26,8 @@
 """
 
 from tldap.query_utils import Q  # noqa: F401
 
 
 __author__ = """Brian May"""
 __email__ = 'brian@linuxpenguins.xyz'
-__version__ = '1.0.7'
+__version__ = '1.0.8'
```

### Comparing `python_tldap-1.0.7/tldap/backend/__init__.py` & `python_tldap-1.0.8/tldap/backend/__init__.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/backend/base.py` & `python_tldap-1.0.8/tldap/backend/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -94,14 +94,18 @@
         start_tls = False
         if 'START_TLS' in settings and settings['START_TLS']:
             start_tls = True
 
         tls = None
         if use_ssl or start_tls:
             tls = ldap3.Tls()
+
+            if 'CIPHERS' in settings:
+                tls.ciphers = settings['CIPHERS']
+
             if 'TLS_CA' in settings and settings['TLS_CA']:
                 tls.ca_certs_file = settings['TLS_CA']
 
             if 'REQUIRE_TLS' in settings and settings['REQUIRE_TLS']:
                 tls.validate = ssl.CERT_REQUIRED
 
         s = ldap3.Server(host, port=port, use_ssl=use_ssl, tls=tls)
```

### Comparing `python_tldap-1.0.7/tldap/backend/fake_transactions.py` & `python_tldap-1.0.8/tldap/backend/fake_transactions.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/backend/no_transactions.py` & `python_tldap-1.0.8/tldap/backend/no_transactions.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/database/__init__.py` & `python_tldap-1.0.8/tldap/database/__init__.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/database/helpers.py` & `python_tldap-1.0.8/tldap/database/helpers.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/dict.py` & `python_tldap-1.0.8/tldap/dict.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/django/__init__.py` & `python_tldap-1.0.8/tldap/django/__init__.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/django/helpers.py` & `python_tldap-1.0.8/tldap/django/helpers.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/django/middleware.py` & `python_tldap-1.0.8/tldap/django/middleware.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/django/migrations/0001_initial.py` & `python_tldap-1.0.8/tldap/django/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/django/models.py` & `python_tldap-1.0.8/tldap/django/models.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/dn.py` & `python_tldap-1.0.8/tldap/dn.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/exceptions.py` & `python_tldap-1.0.8/tldap/exceptions.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/fields.py` & `python_tldap-1.0.8/tldap/fields.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/filter.py` & `python_tldap-1.0.8/tldap/filter.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/ldap_passwd.py` & `python_tldap-1.0.8/tldap/ldap_passwd.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/modlist.py` & `python_tldap-1.0.8/tldap/modlist.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/query.py` & `python_tldap-1.0.8/tldap/query.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/query_utils.py` & `python_tldap-1.0.8/tldap/query_utils.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/__init__.py` & `python_tldap-1.0.8/tldap/test/__init__.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/00-core.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/00-core.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/10-cosine.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/10-cosine.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/50-inetorgperson.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/50-inetorgperson.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/70-eduperson.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/70-eduperson.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/90-aueduperson.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/90-aueduperson.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/90-schac.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/90-schac.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/ldap_schemas/nis.schema` & `python_tldap-1.0.8/tldap/test/ldap_schemas/nis.schema`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/test/slapd.py` & `python_tldap-1.0.8/tldap/test/slapd.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/transaction.py` & `python_tldap-1.0.8/tldap/transaction.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/tree.py` & `python_tldap-1.0.8/tldap/tree.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/tldap/utils.py` & `python_tldap-1.0.8/tldap/utils.py`

 * *Files identical despite different names*

### Comparing `python_tldap-1.0.7/setup.py` & `python_tldap-1.0.8/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,19 +12,19 @@
 package_data = \
 {'': ['*'], 'tldap.test': ['ldap_schemas/*']}
 
 install_requires = \
 ['ldap3', 'passlib', 'pip', 'pyasn1', 'six']
 
 extras_require = \
-{'docs': ['django', 'sphinx']}
+{'docs': ['django', 'sphinx', 'furo']}
 
 setup_kwargs = {
     'name': 'python-tldap',
-    'version': '1.0.7',
+    'version': '1.0.8',
     'description': 'High level python LDAP Library',
     'long_description': 'python-tldap\n============\nTLDAP is a high level LDAP library for Python that uses Ecto like models\nto define LDAP schemas that can then be used in an easy way from Python code.\nIt also supports fake LDAP transactions, to try and ensure LDAP database\nremains in a consistent state, even if there are errors that cause the\ntransaction to fail.\n\nDocumentation can be found at http://python-tldap.readthedocs.org/\n',
     'author': 'Brian May',
     'author_email': 'brian@linuxpenguins.xyz',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'https://github.com/Karaage-Cluster/python-tldap/',
```

### Comparing `python_tldap-1.0.7/PKG-INFO` & `python_tldap-1.0.8/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-tldap
-Version: 1.0.7
+Version: 1.0.8
 Summary: High level python LDAP Library
 Home-page: https://github.com/Karaage-Cluster/python-tldap/
 License: GPL3+
 Author: Brian May
 Author-email: brian@linuxpenguins.xyz
 Requires-Python: >=3.10,<4.0
 Classifier: Development Status :: 5 - Production/Stable
@@ -17,14 +17,15 @@
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Provides-Extra: docs
 Requires-Dist: django ; extra == "docs"
+Requires-Dist: furo ; extra == "docs"
 Requires-Dist: ldap3
 Requires-Dist: passlib
 Requires-Dist: pip
 Requires-Dist: pyasn1
 Requires-Dist: six
 Requires-Dist: sphinx ; extra == "docs"
 Description-Content-Type: text/x-rst
```


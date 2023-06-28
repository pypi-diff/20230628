# Comparing `tmp/swh.web.client-0.5.0.tar.gz` & `tmp/swh.web.client-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/swh.web.client-0.5.0.tar", last modified: Wed Sep  8 11:34:11 2021, max compression
+gzip compressed data, was "swh.web.client-0.6.0.tar", last modified: Wed Jun 28 13:34:39 2023, max compression
```

## Comparing `swh.web.client-0.5.0.tar` & `swh.web.client-0.6.0.tar`

### file list

```diff
@@ -1,56 +1,56 @@
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/
--rw-r--r--   0 jenkins    (115) docker     (999)      111 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)     1021 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/.pre-commit-config.yaml
--rw-r--r--   0 jenkins    (115) docker     (999)      117 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/AUTHORS
--rw-r--r--   0 jenkins    (115) docker     (999)     3397 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/CODE_OF_CONDUCT.md
--rw-r--r--   0 jenkins    (115) docker     (999)       33 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/CONTRIBUTORS
--rw-r--r--   0 jenkins    (115) docker     (999)    35147 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/LICENSE
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/MANIFEST.in
--rw-r--r--   0 jenkins    (115) docker     (999)      163 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     1776 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)      820 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/README.rst
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/api_data.py
--rw-r--r--   0 jenkins    (115) docker     (999)       44 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/docs/
--rw-r--r--   0 jenkins    (115) docker     (999)       24 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)       39 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)      820 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/README.rst
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/docs/_static/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/_static/.placeholder
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/docs/_templates/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/_templates/.placeholder
--rw-r--r--   0 jenkins    (115) docker     (999)       43 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/conf.py
--rw-r--r--   0 jenkins    (115) docker     (999)     3168 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/docs/index.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      267 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/mypy.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      237 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/pyproject.toml
--rw-r--r--   0 jenkins    (115) docker     (999)       33 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/pytest.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      108 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/requirements-swh.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       83 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/requirements-test.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      256 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/requirements.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      145 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/setup.cfg
--rwxr-xr-x   0 jenkins    (115) docker     (999)     2530 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/setup.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh/
--rw-r--r--   0 jenkins    (115) docker     (999)      111 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh/web/
--rw-r--r--   0 jenkins    (115) docker     (999)      111 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh/web/client/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)     6982 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/cli.py
--rw-r--r--   0 jenkins    (115) docker     (999)    21233 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/client.py
--rw-r--r--   0 jenkins    (115) docker     (999)       27 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/py.typed
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh/web/client/tests/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)   374937 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/api_data.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1292 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/api_data_static.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2826 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/conftest.py
--rwxr-xr-x   0 jenkins    (115) docker     (999)     1677 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/gen-api-data.sh
--rw-r--r--   0 jenkins    (115) docker     (999)     3632 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/test_cli.py
--rw-r--r--   0 jenkins    (115) docker     (999)     9795 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/swh/web/client/tests/test_web_api_client.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/
--rw-r--r--   0 jenkins    (115) docker     (999)     1776 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     1006 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/SOURCES.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        1 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/dependency_links.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       66 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/entry_points.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      163 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/requires.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        4 2021-09-08 11:34:11.000000 swh.web.client-0.5.0/swh.web.client.egg-info/top_level.txt
--rw-r--r--   0 jenkins    (115) docker     (999)     1432 2021-09-08 11:34:09.000000 swh.web.client-0.5.0/tox.ini
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.985621 swh.web.client-0.6.0/
+-rw-r--r--   0 jenkins    (115) docker     (999)      140 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/.git-blame-ignore-revs
+-rw-r--r--   0 jenkins    (115) docker     (999)      111 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)      848 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/.pre-commit-config.yaml
+-rw-r--r--   0 jenkins    (115) docker     (999)      117 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/AUTHORS
+-rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/CODE_OF_CONDUCT.md
+-rw-r--r--   0 jenkins    (115) docker     (999)       33 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/CONTRIBUTORS
+-rw-r--r--   0 jenkins    (115) docker     (999)    35147 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/LICENSE
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/MANIFEST.in
+-rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     1739 2023-06-28 13:34:39.985621 swh.web.client-0.6.0/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)      820 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/README.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)       44 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/docs/
+-rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)      820 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/README.rst
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/docs/_static/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/_static/.placeholder
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/docs/_templates/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/_templates/.placeholder
+-rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/conf.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     3229 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/docs/index.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      267 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/mypy.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/pyproject.toml
+-rw-r--r--   0 jenkins    (115) docker     (999)       62 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/pytest.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      108 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/requirements-swh.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       83 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/requirements-test.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      256 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/requirements.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      172 2023-06-28 13:34:39.985621 swh.web.client-0.6.0/setup.cfg
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     2530 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/setup.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/swh/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/swh/web/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/swh/web/client/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     7051 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/cli.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    21259 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/client.py
+-rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/py.typed
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.985621 swh.web.client-0.6.0/swh/web/client/tests/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)   374937 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/api_data.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1292 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/api_data_static.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2814 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/conftest.py
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     1677 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/gen-api-data.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)     3632 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/test_cli.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     9782 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/swh/web/client/tests/test_web_api_client.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 13:34:39.981621 swh.web.client-0.6.0/swh.web.client.egg-info/
+-rw-r--r--   0 jenkins    (115) docker     (999)     1739 2023-06-28 13:34:39.000000 swh.web.client-0.6.0/swh.web.client.egg-info/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     1017 2023-06-28 13:34:39.000000 swh.web.client-0.6.0/swh.web.client.egg-info/SOURCES.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-06-28 13:34:39.000000 swh.web.client-0.6.0/swh.web.client.egg-info/dependency_links.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       47 2023-06-28 13:34:39.000000 swh.web.client-0.6.0/swh.web.client.egg-info/entry_points.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-28 13:34:39.000000 swh.web.client-0.6.0/swh.web.client.egg-info/requires.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-06-28 13:34:39.000000 swh.web.client-0.6.0/swh.web.client.egg-info/top_level.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)     1514 2023-06-28 13:34:34.000000 swh.web.client-0.6.0/tox.ini
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `swh.web.client-0.5.0/CODE_OF_CONDUCT.md` & `swh.web.client-0.6.0/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/LICENSE` & `swh.web.client-0.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/PKG-INFO` & `swh.web.client-0.6.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,20 +1,18 @@
 Metadata-Version: 2.1
 Name: swh.web.client
-Version: 0.5.0
+Version: 0.6.0
 Summary: Software Heritage Web client
 Home-page: https://forge.softwareheritage.org/source/swh-web-client/
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
-License: UNKNOWN
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-web-client
 Project-URL: Documentation, https://docs.softwareheritage.org/devel/swh-web-client/
-Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Development Status :: 3 - Alpha
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
@@ -44,9 +42,7 @@
 
    # get() always retrieve entire objects, following pagination
    # WARNING: this might *not* be what you want for large objects
    cli.get('swh:1:snp:6a3a2cf0b2b90ce7ae1cf0a221ed68035b686f5a')
 
    # type-specific methods support explicit iteration through pages
    next(cli.snapshot('swh:1:snp:cabcc7d7bf639bbe1cc3b41989e1806618dd5764'))
-
-
```

### Comparing `swh.web.client-0.5.0/README.rst` & `swh.web.client-0.6.0/README.rst`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/docs/README.rst` & `swh.web.client-0.6.0/docs/README.rst`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/docs/index.rst` & `swh.web.client-0.6.0/docs/index.rst`

 * *Files 3% similar despite different names*

```diff
@@ -62,15 +62,15 @@
   $ curl -H "Authorization: Bearer ${TOKEN}" https://archive.softwareheritage.org/api/1/<endpoint>
 
 Note that if you intend to use the :class:`swh.web.client.client.WebAPIClient`
 class, you can activate authentication by using the following code snippet::
 
   from swh.web.client.client import WebAPIClient
 
-  TOKEN = '.......'  # Use "swh web auth login" command to get it
+  TOKEN = '.......'  # Use "swh auth generate-token" command to get it
 
   client = WebAPIClient(bearer_token=TOKEN)
 
   # All requests to the Web API will be authenticated
   resp = client.get('swh:1:rev:aafb16d69fd30ff58afdd69036a26047f3aebdc6')
 
 It is also possible to revoke a token, preventing future Web API authentication
@@ -78,17 +78,19 @@
 to perform that task.
 
 .. code-block:: text
 
   $ swh auth --client-id swh-web revoke-token $REFRESH_TOKEN
   Token successfully revoked.
 
-API Reference
--------------
 
-.. toctree::
-   :maxdepth: 2
+.. only:: standalone_package_doc
 
-   /apidoc/swh.web.client
+   Indices and tables
+   ------------------
+
+   * :ref:`genindex`
+   * :ref:`modindex`
+   * :ref:`search`
 
 .. _Software Heritage Identity Provider:
   https://auth.softwareheritage.org/auth/realms/SoftwareHeritage/account/
```

### Comparing `swh.web.client-0.5.0/setup.py` & `swh.web.client-0.6.0/setup.py`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/swh/web/client/cli.py` & `swh.web.client-0.6.0/swh/web/client/cli.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,15 +46,15 @@
     from swh.core import config
     from swh.web.client.client import WebAPIClient
 
     if not config_file:
         config_file = DEFAULT_CONFIG_PATH
 
     try:
-        conf = config.read_raw_config(config.config_basepath(config_file))
+        conf = config.read_raw_config(config_file)
         if not conf:
             raise ValueError(f"Cannot parse configuration file: {config_file}")
 
         # TODO: Determine what the following conditional is for
         if config_file == DEFAULT_CONFIG_PATH:
             try:
                 conf = conf["swh"]["web"]["client"]
@@ -71,15 +71,18 @@
 
     ctx.ensure_object(dict)
     ctx.obj["client"] = WebAPIClient(conf["api_url"], conf["bearer_token"])
 
 
 @web.command(name="search")
 @click.argument(
-    "query", required=True, nargs=-1, metavar="KEYWORD...",
+    "query",
+    required=True,
+    nargs=-1,
+    metavar="KEYWORD...",
 )
 @click.option(
     "--limit",
     "limit",
     type=int,
     default=10,
     show_default=True,
@@ -95,15 +98,19 @@
     "--url-encode/--no-url-encode",
     default=False,
     show_default=True,
     help="if true, escape origin URLs in results with percent encoding (RFC 3986)",
 )
 @click.pass_context
 def search(
-    ctx: Context, query: List[str], limit: int, only_visited: bool, url_encode: bool,
+    ctx: Context,
+    query: List[str],
+    limit: int,
+    only_visited: bool,
+    url_encode: bool,
 ):
     """Search a query (as a list of keywords) into the Software Heritage
     archive.
 
     The search results are printed to CSV format, one result per line, using a
     tabulation as the field delimiter.
     """
@@ -128,33 +135,35 @@
     except (BrokenPipeError, IOError):
         # Get rid of the BrokenPipeError message
         sys.stderr.close()
 
 
 @web.group(name="save", context_settings=CONTEXT_SETTINGS)
 @click.pass_context
-def savecodenow(ctx: Context,):
-    """Subcommand to interact from the cli with the save code now feature
-
-    """
+def savecodenow(
+    ctx: Context,
+):
+    """Subcommand to interact from the cli with the save code now feature"""
     pass
 
 
 @savecodenow.command("submit-request")
 @click.option("--delimiter", "-d", default=",")
 @click.pass_context
 def submit_request(ctx, delimiter: str) -> None:
     """Submit new save code now request through cli pipe. The expected format of the request
     if one csv row ``<visit_type>,<origin>``.
 
-    Example:
+    Example::
 
+    \b
         cat list-origins | swh web save submit-request
 
-        echo svn;https://svn-url\ngit;https://git-url | swh web save \
+    \b
+        echo svn;https://svn-url\\ngit;https://git-url | swh web save \\
             submit-request --delimiter ';'
 
     Prints:
         The output of save code now requests as json output.
 
     """
     import json
@@ -171,15 +180,18 @@
 
         try:
             saved_origin = client.origin_save(visit_type, origin)
             logging.info("Submitted origin (%s, %s)", visit_type, origin)
             processed_origins.append(saved_origin)
         except Exception as e:
             logging.warning(
-                "Issue for origin (%s, %s)\n%s", origin, visit_type, e,
+                "Issue for origin (%s, %s)\n%s",
+                origin,
+                visit_type,
+                e,
             )
     logging.debug("Origin saved: %s", len(processed_origins))
     print(json.dumps(processed_origins))
 
 
 def _forward_context(ctx: Context, *args, **kwargs):
     ctx.forward(*args, **kwargs)
```

### Comparing `swh.web.client-0.5.0/swh/web/client/client.py` & `swh.web.client-0.6.0/swh/web/client/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -32,15 +32,15 @@
 from typing import Any, Callable, Dict, Iterator, List, Optional, Union
 from urllib.parse import urlparse
 
 import dateutil.parser
 import requests
 
 from swh.model.hashutil import hash_to_bytes, hash_to_hex
-from swh.model.identifiers import CoreSWHID, ObjectType
+from swh.model.swhids import CoreSWHID, ObjectType
 from swh.web.client.cli import DEFAULT_CONFIG
 
 SWHIDish = Union[CoreSWHID, str]
 
 
 CONTENT = "content"
 DIRECTORY = "directory"
@@ -129,28 +129,24 @@
     else:
         raise ValueError(f"invalid object type: {obj_type}")
 
     return data
 
 
 class WebAPIClient:
-    """Client for the Software Heritage archive Web API, see
-
-    https://archive.softwareheritage.org/api/
-
-    """
+    """Client for the Software Heritage archive Web API, see :swh_web:`api/`"""
 
     def __init__(
         self,
         api_url: str = DEFAULT_CONFIG["api_url"],
         bearer_token: Optional[str] = DEFAULT_CONFIG["bearer_token"],
     ):
         """Create a client for the Software Heritage Web API
 
-        See: https://archive.softwareheritage.org/api/
+        See: :swh_web:`api/`
 
         Args:
             api_url: base URL for API calls
             bearer_token: optional bearer token to do authenticated API calls
         """
         api_url = api_url.rstrip("/")
         u = urlparse(api_url)
@@ -518,15 +514,17 @@
 
         Raises:
           requests.HTTPError: if HTTP request fails
 
         """
         return bool(
             self._call(
-                f"release/{_get_object_id_hex(swhid)}/", http_method="head", **req_args,
+                f"release/{_get_object_id_hex(swhid)}/",
+                http_method="head",
+                **req_args,
             )
         )
 
     def snapshot_exists(self, swhid: SWHIDish, **req_args) -> bool:
         """Check if a snapshot object exists in the archive
 
         Args:
@@ -553,15 +551,19 @@
             req_args: extra keyword arguments for requests.head()
 
         Raises:
           requests.HTTPError: if HTTP request fails
 
         """
         return bool(
-            self._call(f"origin/{origin}/get/", http_method="head", **req_args,)
+            self._call(
+                f"origin/{origin}/get/",
+                http_method="head",
+                **req_args,
+            )
         )
 
     def content_raw(self, swhid: SWHIDish, **req_args) -> Iterator[bytes]:
         """Iterate over the raw content of a content object
 
         Args:
             swhid: object persistent identifier
```

### Comparing `swh.web.client-0.5.0/swh/web/client/tests/api_data.py` & `swh.web.client-0.6.0/swh/web/client/tests/api_data.py`

 * *Files 0% similar despite different names*

```diff
@@ -15,15 +15,15 @@
     "sha256": "b5c7fe0536f44ef60c8780b6065d30bca74a5cd06d78a4a71ba1ad064770f0c9"
   },
   "data_url": "https://archive.softwareheritage.org/api/1/content/sha1_git:fe95a46679d128ff167b7c55df5d02356c5a1ae1/raw/",
   "filetype_url": "https://archive.softwareheritage.org/api/1/content/sha1_git:fe95a46679d128ff167b7c55df5d02356c5a1ae1/filetype/",
   "language_url": "https://archive.softwareheritage.org/api/1/content/sha1_git:fe95a46679d128ff167b7c55df5d02356c5a1ae1/language/",
   "license_url": "https://archive.softwareheritage.org/api/1/content/sha1_git:fe95a46679d128ff167b7c55df5d02356c5a1ae1/license/"
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "directory/977fc4b98c0e85816348cebd3b12026407c368b6/": r"""
 [
   {
     "dir_id": "977fc4b98c0e85816348cebd3b12026407c368b6",
     "type": "file",
     "target": "58471109208922c9ee8c4b06135725f03ed16814",
     "name": ".bzrignore",
@@ -454,15 +454,15 @@
       "sha1_git": "6a05643838bb4ef64ae093f7a0f816a80d6f09f4",
       "sha1": "de26417bb7aa146bb6a9abfcfe820466e80f08fe",
       "sha256": "c8d512dfe55b7d9503ee84c750e10724c7528ed1beb0b84c1b9ae82e82344ad8"
     },
     "target_url": "https://archive.softwareheritage.org/api/1/content/sha1_git:6a05643838bb4ef64ae093f7a0f816a80d6f09f4/"
   }
 ]
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "release/b9db10d00835e9a43e2eebef2db1d04d4ae82342/": r"""
 {
   "author": {
     "fullname": "Paul Tagliamonte <tag@pault.ag>",
     "name": "Paul Tagliamonte",
     "email": "tag@pault.ag"
   },
@@ -471,15 +471,15 @@
   "name": "0.9.9",
   "message": "Tagging 0.9.9\n",
   "synthetic": false,
   "target": "e005cb773c769436709ca6a1d625dc784dbc1636",
   "target_type": "revision",
   "target_url": "https://archive.softwareheritage.org/api/1/revision/e005cb773c769436709ca6a1d625dc784dbc1636/"
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "revision/aafb16d69fd30ff58afdd69036a26047f3aebdc6/": r"""
 {
   "id": "aafb16d69fd30ff58afdd69036a26047f3aebdc6",
   "author": {
     "fullname": "Nicolas Dandrimont <nicolas.dandrimont@crans.org>",
     "name": "Nicolas Dandrimont",
     "email": "nicolas.dandrimont@crans.org"
@@ -507,15 +507,15 @@
     }
   ],
   "merge": true,
   "url": "https://archive.softwareheritage.org/api/1/revision/aafb16d69fd30ff58afdd69036a26047f3aebdc6/",
   "history_url": "https://archive.softwareheritage.org/api/1/revision/aafb16d69fd30ff58afdd69036a26047f3aebdc6/log/",
   "directory_url": "https://archive.softwareheritage.org/api/1/directory/9f2e5898e00a66e6ac11033959d7e05b1593353b/"
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "snapshot/6a3a2cf0b2b90ce7ae1cf0a221ed68035b686f5a/": r"""
 {
   "id": "6a3a2cf0b2b90ce7ae1cf0a221ed68035b686f5a",
   "branches": {
     "refs/heads/master": {
       "target": "83c20a6a63a7ebc1a549d367bc07a61b926cecf3",
       "target_type": "revision",
@@ -535,15 +535,15 @@
       "target": "0c9dbfbc0974ec8ac1d8253aa1092366a03633a8",
       "target_type": "revision",
       "target_url": "https://archive.softwareheritage.org/api/1/revision/0c9dbfbc0974ec8ac1d8253aa1092366a03633a8/"
     }
   },
   "next_branch": null
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "snapshot/cabcc7d7bf639bbe1cc3b41989e1806618dd5764/": r"""
 {
   "id": "cabcc7d7bf639bbe1cc3b41989e1806618dd5764",
   "branches": {
     "HEAD": {
       "target": "refs/heads/master",
       "target_type": "alias",
@@ -5543,15 +5543,15 @@
       "target": "8a79d68b5a847beef3f70b2ed16b2a757572cc5e",
       "target_type": "release",
       "target_url": "https://archive.softwareheritage.org/api/1/release/8a79d68b5a847beef3f70b2ed16b2a757572cc5e/"
     }
   },
   "next_branch": "refs/tags/v3.0-rc7"
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "snapshot/cabcc7d7bf639bbe1cc3b41989e1806618dd5764/?branches_count=1000&branches_from=refs/tags/v3.0-rc7": r"""
 {
   "id": "cabcc7d7bf639bbe1cc3b41989e1806618dd5764",
   "branches": {
     "refs/tags/v3.0-rc7": {
       "target": "394d6f903ac6889fa50ca5c19111ae659d524b4c",
       "target_type": "release",
@@ -7506,15 +7506,15 @@
       "target": "2bf590c16af975a0132e4a90967807d538cdc7de",
       "target_type": "release",
       "target_url": "https://archive.softwareheritage.org/api/1/release/2bf590c16af975a0132e4a90967807d538cdc7de/"
     }
   },
   "next_branch": null
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "origin/https://github.com/NixOS/nixpkgs/visits/?last_visit=50&per_page=10": r"""
 [
   {
     "origin": "https://github.com/NixOS/nixpkgs",
     "visit": 49,
     "date": "2018-07-31T04:34:23.298931+00:00",
     "type": "git",
@@ -7610,15 +7610,15 @@
     "type": "git",
     "status": "partial",
     "snapshot": null,
     "origin_visit_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/NixOS/nixpkgs/visit/40/",
     "snapshot_url": null
   }
 ]
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "origin/https://github.com/NixOS/nixpkgs/visits/?last_visit=40&per_page=10": r"""
 [
   {
     "origin": "https://github.com/NixOS/nixpkgs",
     "visit": 39,
     "date": "2018-07-16T23:24:15.061318+00:00",
     "type": "git",
@@ -7714,28 +7714,28 @@
     "type": "git",
     "status": "full",
     "snapshot": "100de51846f317e6ab48da79d985cefa6fdefe42",
     "origin_visit_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/NixOS/nixpkgs/visit/30/",
     "snapshot_url": "https://archive.softwareheritage.org/api/1/snapshot/100de51846f317e6ab48da79d985cefa6fdefe42/"
   }
 ]
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "origin/https://github.com/NixOS/nixpkgs/visit/latest/": r"""
 {
   "origin": "https://github.com/NixOS/nixpkgs",
   "visit": 128,
   "date": "2021-09-02T20:20:31.231786+00:00",
   "status": "full",
   "snapshot": "6e1fe7858066ff1a6905080ac6503a3a12b84f59",
   "type": "git",
   "metadata": {},
   "origin_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/NixOS/nixpkgs/get/",
   "snapshot_url": "https://archive.softwareheritage.org/api/1/snapshot/6e1fe7858066ff1a6905080ac6503a3a12b84f59/"
 }
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "origin/search/foo%20bar%20baz%20qux/?with_visit=true": r"""
 [
   {
     "url": "https://github.com/foo-bar-baz-qux/mygithubpage",
     "origin_visits_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/foo-bar-baz-qux/mygithubpage/visits/"
   },
   {
@@ -7835,15 +7835,15 @@
     "origin_visits_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/foo-bar-baz-qux/knowledge-repo/visits/"
   },
   {
     "url": "https://github.com/foo-bar-baz-qux/EconML",
     "origin_visits_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/foo-bar-baz-qux/EconML/visits/"
   }
 ]
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
     "origin/search/python/?limit=5": r"""
 [
   {
     "url": "https://github.com/neon670/python.dev",
     "origin_visits_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/neon670/python.dev/visits/"
   },
   {
@@ -7859,9 +7859,9 @@
     "origin_visits_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/zjmwqx/ipythonCode/visits/"
   },
   {
     "url": "https://github.com/knutab/Python-BSM",
     "origin_visits_url": "https://archive.softwareheritage.org/api/1/origin/https://github.com/knutab/Python-BSM/visits/"
   }
 ]
-    """,  # NoQA: E501  # NoQA: E501
+    """,  # NoQA: B950  # NoQA: B950
 }
```

### Comparing `swh.web.client-0.5.0/swh/web/client/tests/api_data_static.py` & `swh.web.client-0.6.0/swh/web/client/tests/api_data_static.py`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/swh/web/client/tests/conftest.py` & `swh.web.client-0.6.0/swh/web/client/tests/conftest.py`

 * *Files 10% similar despite different names*

```diff
@@ -18,23 +18,23 @@
 def web_api_mock(requests_mock):
     # monkey patch URLs that require a special response headers
     for api_call, data in API_DATA.items():
         headers = {}
         if api_call == "snapshot/cabcc7d7bf639bbe1cc3b41989e1806618dd5764/":
             # to make the client init and follow pagination
             headers = {
-                "Link": f'<{API_URL}/{api_call}?branches_count=1000&branches_from=refs/tags/v3.0-rc7>; rel="next"'  # NoQA: E501
+                "Link": f'<{API_URL}/{api_call}?branches_count=1000&branches_from=refs/tags/v3.0-rc7>; rel="next"'  # NoQA: B950
             }
         elif (
             api_call
-            == "origin/https://github.com/NixOS/nixpkgs/visits/?last_visit=50&per_page=10"  # NoQA: E501
+            == "origin/https://github.com/NixOS/nixpkgs/visits/?last_visit=50&per_page=10"  # NoQA: B950
         ):
             # to make the client follow pagination
             headers = {
-                "Link": f'<{API_URL}/origin/https://github.com/NixOS/nixpkgs/visits/?last_visit=40&per_page=10>; rel="next"'  # NoQA: E501
+                "Link": f'<{API_URL}/origin/https://github.com/NixOS/nixpkgs/visits/?last_visit=40&per_page=10>; rel="next"'  # NoQA: B950
             }
         requests_mock.get(f"{API_URL}/{api_call}", text=data, headers=headers)
 
     def known_callback(request, context):
         known_swhids = [
             "swh:1:cnt:fe95a46679d128ff167b7c55df5d02356c5a1ae1",
             "swh:1:dir:977fc4b98c0e85816348cebd3b12026407c368b6",
@@ -57,27 +57,23 @@
 def web_api_client():
     # use the fake base API URL that matches API data
     return WebAPIClient(api_url=API_URL)
 
 
 @pytest.fixture
 def cli_global_config_dict():
-    """Define a basic configuration yaml for the cli.
-
-    """
+    """Define a basic configuration yaml for the cli."""
     return {
         "api_url": API_URL,
         "bearer_token": None,
     }
 
 
 @pytest.fixture
 def cli_config_path(tmp_path, cli_global_config_dict, monkeypatch):
-    """Write a global.yml file and writes it in the environment
-
-    """
+    """Write a global.yml file and writes it in the environment"""
     config_path = os.path.join(tmp_path, "global.yml")
     with open(config_path, "w") as f:
         f.write(yaml.dump(cli_global_config_dict))
     monkeypatch.setenv("SWH_CONFIG_FILE", config_path)
 
     return config_path
```

### Comparing `swh.web.client-0.5.0/swh/web/client/tests/gen-api-data.sh` & `swh.web.client-0.6.0/swh/web/client/tests/gen-api-data.sh`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/swh/web/client/tests/test_cli.py` & `swh.web.client-0.6.0/swh/web/client/tests/test_cli.py`

 * *Files identical despite different names*

### Comparing `swh.web.client-0.5.0/swh/web/client/tests/test_web_api_client.py` & `swh.web.client-0.6.0/swh/web/client/tests/test_web_api_client.py`

 * *Files 2% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 # See top-level LICENSE file for more information
 
 import json
 
 from dateutil.parser import parse as parse_date
 import pytest
 
-from swh.model.identifiers import REVISION, CoreSWHID
+from swh.model.swhids import CoreSWHID
 from swh.web.client.client import typify_json
 
 from .api_data import API_DATA
 
 
 def test_get_content(web_api_client, web_api_mock):
     swhid = CoreSWHID.from_string("swh:1:cnt:fe95a46679d128ff167b7c55df5d02356c5a1ae1")
@@ -169,23 +169,23 @@
     results = list(web_api_client.origin_search("foo bar baz qux", with_visit=True))
     actual_urls = [r["url"] for r in results]
     actual_visits = [r["origin_visits_url"] for r in results]
     # Check *some* of the URLS since the search could return more results in the future
     expected = [
         (
             "https://github.com/foo-bar-baz-qux/mygithubpage",
-            "https://archive.softwareheritage.org/api/1/origin/https://github.com/foo-bar-baz-qux/mygithubpage/visits/",  # NoQA: E501
+            "https://archive.softwareheritage.org/api/1/origin/https://github.com/foo-bar-baz-qux/mygithubpage/visits/",  # NoQA: B950
         ),
         (
             "https://www.npmjs.com/package/foo-bar-baz-qux",
-            "https://archive.softwareheritage.org/api/1/origin/https://www.npmjs.com/package/foo-bar-baz-qux/visits/",  # NoQA: E501
+            "https://archive.softwareheritage.org/api/1/origin/https://www.npmjs.com/package/foo-bar-baz-qux/visits/",  # NoQA: B950
         ),
         (
             "https://bitbucket.org/foobarbazqux/rp.git",
-            "https://archive.softwareheritage.org/api/1/origin/https://bitbucket.org/foobarbazqux/rp.git/visits/",  # NoQA: E501
+            "https://archive.softwareheritage.org/api/1/origin/https://bitbucket.org/foobarbazqux/rp.git/visits/",  # NoQA: B950
         ),
     ]
     for (url, visit) in expected:
         assert url in actual_urls
         assert visit in actual_visits
 
 
@@ -254,11 +254,11 @@
     revision_data = {
         "id": "aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa",
         "directory": "aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa",
         "date": None,
         "committer_date": None,
         "parents": [],
     }
-    revision_typed = typify_json(revision_data, REVISION)
+    revision_typed = typify_json(revision_data, "revision")
     pid = "swh:1:rev:aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa"
     assert revision_typed["id"] == CoreSWHID.from_string(pid)
     assert revision_typed["date"] is None
```

### Comparing `swh.web.client-0.5.0/swh.web.client.egg-info/PKG-INFO` & `swh.web.client-0.6.0/swh.web.client.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,20 +1,18 @@
 Metadata-Version: 2.1
 Name: swh.web.client
-Version: 0.5.0
+Version: 0.6.0
 Summary: Software Heritage Web client
 Home-page: https://forge.softwareheritage.org/source/swh-web-client/
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
-License: UNKNOWN
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-web-client
 Project-URL: Documentation, https://docs.softwareheritage.org/devel/swh-web-client/
-Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Development Status :: 3 - Alpha
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
@@ -44,9 +42,7 @@
 
    # get() always retrieve entire objects, following pagination
    # WARNING: this might *not* be what you want for large objects
    cli.get('swh:1:snp:6a3a2cf0b2b90ce7ae1cf0a221ed68035b686f5a')
 
    # type-specific methods support explicit iteration through pages
    next(cli.snapshot('swh:1:snp:cabcc7d7bf639bbe1cc3b41989e1806618dd5764'))
-
-
```

### Comparing `swh.web.client-0.5.0/swh.web.client.egg-info/SOURCES.txt` & `swh.web.client-0.6.0/swh.web.client.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -1,17 +1,17 @@
+.git-blame-ignore-revs
 .gitignore
 .pre-commit-config.yaml
 AUTHORS
 CODE_OF_CONDUCT.md
 CONTRIBUTORS
 LICENSE
 MANIFEST.in
 Makefile
 README.rst
-api_data.py
 conftest.py
 mypy.ini
 pyproject.toml
 pytest.ini
 requirements-swh.txt
 requirements-test.txt
 requirements.txt
```

### Comparing `swh.web.client-0.5.0/tox.ini` & `swh.web.client-0.6.0/tox.ini`

 * *Files 8% similar despite different names*

```diff
@@ -1,8 +1,10 @@
 [tox]
+requires =
+  tox>4
 envlist=black,flake8,mypy,py3
 
 [testenv]
 extras =
   testing
 deps =
   pytest-cov
@@ -11,63 +13,62 @@
          {envsitepackagesdir}/swh/web/client \
          --cov={envsitepackagesdir}/swh/web/client \
          --cov-branch {posargs}
 
 [testenv:black]
 skip_install = true
 deps =
-  black==19.10b0
+  black==22.10.0
 commands =
   {envpython} -m black --check swh
 
 [testenv:flake8]
 skip_install = true
 deps =
-  flake8
+  flake8==5.0.4
+  flake8-bugbear==22.9.23
+  pycodestyle==2.9.1
 commands =
   {envpython} -m flake8
 
 [testenv:mypy]
 extras =
   testing
 deps =
-  mypy
+  mypy==1.0.1
 commands =
   mypy swh
 
 # build documentation outside swh-environment using the current
 # git HEAD of swh-docs, is executed on CI for each diff to prevent
 # breaking doc build
 [testenv:sphinx]
-whitelist_externals = make
+allowlist_externals = make
 usedevelop = true
 extras =
   testing
 deps =
   # fetch and install swh-docs in develop mode
-  -e git+https://forge.softwareheritage.org/source/swh-docs#egg=swh.docs
-
+  -e git+https://forge.softwareheritage.org/source/swh-docs.git\#egg=swh.docs
 setenv =
   SWH_PACKAGE_DOC_TOX_BUILD = 1
   # turn warnings into errors
   SPHINXOPTS = -W
 commands =
   make -I ../.tox/sphinx/src/swh-docs/swh/ -C docs
 
-
 # build documentation only inside swh-environment using local state
 # of swh-docs package
 [testenv:sphinx-dev]
-whitelist_externals = make
+allowlist_externals = make
 usedevelop = true
 extras =
   testing
 deps =
   # install swh-docs in develop mode
   -e ../swh-docs
-
 setenv =
   SWH_PACKAGE_DOC_TOX_BUILD = 1
   # turn warnings into errors
   SPHINXOPTS = -W
 commands =
   make -I ../.tox/sphinx-dev/src/swh-docs/swh/ -C docs
```


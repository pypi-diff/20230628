# Comparing `tmp/pyshv-0.1.1.tar.gz` & `tmp/pyshv-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyshv-0.1.1.tar", last modified: Mon May 22 19:34:04 2023, max compression
+gzip compressed data, was "pyshv-0.2.0.tar", last modified: Wed Jun 28 12:54:24 2023, max compression
```

## Comparing `pyshv-0.1.1.tar` & `pyshv-0.2.0.tar`

### file list

```diff
@@ -1,39 +1,46 @@
-drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-05-22 19:34:04.731304 pyshv-0.1.1/
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1071 2022-11-15 13:44:11.000000 pyshv-0.1.1/LICENSE
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1808 2023-05-22 19:34:04.731304 pyshv-0.1.1/PKG-INFO
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1186 2023-04-20 14:09:00.000000 pyshv-0.1.1/README.rst
-drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-05-22 19:34:04.724304 pyshv-0.1.1/docs/
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1110 2023-05-22 19:31:56.000000 pyshv-0.1.1/docs/conf.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1622 2023-05-22 19:33:50.000000 pyshv-0.1.1/pyproject.toml
-drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-05-22 19:34:04.726304 pyshv-0.1.1/pyshv.egg-info/
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1808 2023-05-22 19:34:04.000000 pyshv-0.1.1/pyshv.egg-info/PKG-INFO
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      624 2023-05-22 19:34:04.000000 pyshv-0.1.1/pyshv.egg-info/SOURCES.txt
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)        1 2023-05-22 19:34:04.000000 pyshv-0.1.1/pyshv.egg-info/dependency_links.txt
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)       52 2023-05-22 19:34:04.000000 pyshv-0.1.1/pyshv.egg-info/entry_points.txt
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      128 2023-05-22 19:34:04.000000 pyshv-0.1.1/pyshv.egg-info/requires.txt
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)       40 2023-05-22 19:34:04.000000 pyshv-0.1.1/pyshv.egg-info/top_level.txt
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)       38 2023-05-22 19:34:04.731304 pyshv-0.1.1/setup.cfg
-drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-05-22 19:34:04.729304 pyshv-0.1.1/shv/
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      476 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/__init__.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)    15479 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/chainpack.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     7478 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/clientconnection.py
-drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-05-22 19:34:04.729304 pyshv-0.1.1/shv/cp2cp/
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      135 2023-04-20 12:01:13.000000 pyshv-0.1.1/shv/cp2cp/__init__.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2134 2023-04-20 12:01:13.000000 pyshv-0.1.1/shv/cp2cp/__main__.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1990 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/cp2cp/cp2cp.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1396 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/cpcontext.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)    23349 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/cpon.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)        0 2023-04-07 07:26:23.000000 pyshv-0.1.1/shv/py.typed
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      962 2023-05-18 21:08:02.000000 pyshv-0.1.1/shv/rpcbroker.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     8107 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/rpcclient.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     4610 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/rpcmessage.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      229 2023-04-13 10:55:09.000000 pyshv-0.1.1/shv/rpcprotocol.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2211 2023-04-14 17:02:30.000000 pyshv-0.1.1/shv/rpcserver.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     6960 2023-05-22 19:31:56.000000 pyshv-0.1.1/shv/rpcvalue.py
-drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-05-22 19:34:04.731304 pyshv-0.1.1/tests/
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)        0 2023-04-03 08:25:38.000000 pyshv-0.1.1/tests/__init__.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1607 2023-05-22 19:31:56.000000 pyshv-0.1.1/tests/conftest.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)      462 2023-05-22 19:31:56.000000 pyshv-0.1.1/tests/test_client.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2199 2023-05-22 19:31:56.000000 pyshv-0.1.1/tests/test_clientconnection.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2911 2023-05-22 19:31:56.000000 pyshv-0.1.1/tests/test_conversions.py
--rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2872 2023-05-22 19:31:56.000000 pyshv-0.1.1/tests/test_example.py
+drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-06-28 12:54:24.209469 pyshv-0.2.0/
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1071 2022-11-15 13:44:11.000000 pyshv-0.2.0/LICENSE
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1873 2023-06-28 12:54:24.209469 pyshv-0.2.0/PKG-INFO
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1251 2023-05-30 14:54:14.000000 pyshv-0.2.0/README.rst
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1960 2023-06-16 08:05:50.000000 pyshv-0.2.0/pyproject.toml
+drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-06-28 12:54:24.205469 pyshv-0.2.0/pyshv.egg-info/
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1873 2023-06-28 12:54:24.000000 pyshv-0.2.0/pyshv.egg-info/PKG-INFO
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)      774 2023-06-28 12:54:24.000000 pyshv-0.2.0/pyshv.egg-info/SOURCES.txt
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)        1 2023-06-28 12:54:24.000000 pyshv-0.2.0/pyshv.egg-info/dependency_links.txt
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)       91 2023-06-28 12:54:24.000000 pyshv-0.2.0/pyshv.egg-info/entry_points.txt
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)      186 2023-06-28 12:54:24.000000 pyshv-0.2.0/pyshv.egg-info/requires.txt
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)       27 2023-06-28 12:54:24.000000 pyshv-0.2.0/pyshv.egg-info/top_level.txt
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)       38 2023-06-28 12:54:24.209469 pyshv-0.2.0/setup.cfg
+drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-06-28 12:54:24.207469 pyshv-0.2.0/shv/
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2275 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/__init__.py
+drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-06-28 12:54:24.207469 pyshv-0.2.0/shv/broker/
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)      173 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/broker/__init__.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1629 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/broker/__main__.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)    19712 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/broker/rpcbroker.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     9397 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/broker/rpcbrokerconfig.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)    12853 2023-06-28 12:53:33.000000 pyshv-0.2.0/shv/chainpack.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     7771 2023-05-23 07:59:11.000000 pyshv-0.2.0/shv/commonpack.py
+drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-06-28 12:54:24.207469 pyshv-0.2.0/shv/cp2cp/
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)      135 2023-04-20 12:01:13.000000 pyshv-0.2.0/shv/cp2cp/__init__.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2134 2023-04-20 12:01:13.000000 pyshv-0.2.0/shv/cp2cp/__main__.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2332 2023-05-23 07:59:11.000000 pyshv-0.2.0/shv/cp2cp/cp2cp.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)    15116 2023-05-22 19:59:41.000000 pyshv-0.2.0/shv/cpon.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)        0 2023-04-07 07:26:23.000000 pyshv-0.2.0/shv/py.typed
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     4207 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/rpcclient.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     3137 2023-05-22 19:59:41.000000 pyshv-0.2.0/shv/rpcerrors.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)    10377 2023-06-28 12:53:33.000000 pyshv-0.2.0/shv/rpcmessage.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     5271 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/rpcmethod.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1100 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/rpcserver.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     5378 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/rpcurl.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)    16525 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/simpleclient.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     7707 2023-06-16 08:04:39.000000 pyshv-0.2.0/shv/value.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     4470 2023-06-28 12:53:33.000000 pyshv-0.2.0/shv/valueclient.py
+drwxr-xr-x   0 cynerd    (1000) cynerd    (1000)        0 2023-06-28 12:54:24.208469 pyshv-0.2.0/tests/
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     3142 2023-05-22 19:59:41.000000 pyshv-0.2.0/tests/test_chainpack.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)      535 2023-05-22 19:59:41.000000 pyshv-0.2.0/tests/test_cp2cp.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     4588 2023-05-22 19:59:41.000000 pyshv-0.2.0/tests/test_cpon.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     1011 2023-05-22 19:59:41.000000 pyshv-0.2.0/tests/test_errors.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     3577 2023-06-16 08:04:39.000000 pyshv-0.2.0/tests/test_example.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     2274 2023-06-16 08:04:39.000000 pyshv-0.2.0/tests/test_rpcurl.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     5592 2023-05-30 10:00:30.000000 pyshv-0.2.0/tests/test_simpleclient.py
+-rw-r--r--   0 cynerd    (1000) cynerd    (1000)     5296 2023-06-16 08:04:39.000000 pyshv-0.2.0/tests/test_value.py
```

### Comparing `pyshv-0.1.1/LICENSE` & `pyshv-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pyshv-0.1.1/PKG-INFO` & `pyshv-0.2.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyshv
-Version: 0.1.1
+Version: 0.2.0
 Summary: Pure Python SHV implementation
 Author: Elektroline a.s.
 Project-URL: Homepage, https://gitlab.com/elektroline-predator/pyshv
 Project-URL: Bug Tracker, https://gitlab.com/elektroline-predator/pyshv/-/issues
 Project-URL: Github, https://github.com/silicon-heaven/libshv-py
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -28,28 +28,35 @@
 * `⁉️ Issue tracker <https://gitlab.com/elektroline-predator/pyshv/-/issues>`__
 * `📕 Documentation <https://elektroline-predator.gitlab.io/pyshv/>`__
 
 
 Installation
 ------------
 
-The installation can be done with package manager `pip`.
+The installation can be done with package manager ``pip``.
+
+.. code-block:: console
+
+   $ pip install pyshv
 
 
 Running tests
 -------------
 
-This project contains tests in directory tests.
+This project contains tests in directory ``tests``.
+
+Tests require `SHV applications <https://github.com/silicon-heaven/shvapp>`__.
 
 To run tests you have to use **pytest**. To run all tests just run it in the top
 level directory of the project. See the `pytest documentation
 <https://docs.pytest.org/>`__ for more info.
 
 
 Documentation
 -------------
 
-The documentation is available in `docs` directory and build version is
-available on https://elektroline-predator.gitlab.io/python-shvtree/. You can
-also build the latest version from the source code using:
+The documentation is stored in `docs` directory. You can build the latest
+version from the source code using:
+
+.. code-block:: console
 
-    sphinx-build -b html docs docs-html
+    $ sphinx-build -b html docs docs-html
```

### Comparing `pyshv-0.1.1/README.rst` & `pyshv-0.2.0/README.rst`

 * *Files 10% similar despite different names*

```diff
@@ -10,28 +10,35 @@
 * `⁉️ Issue tracker <https://gitlab.com/elektroline-predator/pyshv/-/issues>`__
 * `📕 Documentation <https://elektroline-predator.gitlab.io/pyshv/>`__
 
 
 Installation
 ------------
 
-The installation can be done with package manager `pip`.
+The installation can be done with package manager ``pip``.
+
+.. code-block:: console
+
+   $ pip install pyshv
 
 
 Running tests
 -------------
 
-This project contains tests in directory tests.
+This project contains tests in directory ``tests``.
+
+Tests require `SHV applications <https://github.com/silicon-heaven/shvapp>`__.
 
 To run tests you have to use **pytest**. To run all tests just run it in the top
 level directory of the project. See the `pytest documentation
 <https://docs.pytest.org/>`__ for more info.
 
 
 Documentation
 -------------
 
-The documentation is available in `docs` directory and build version is
-available on https://elektroline-predator.gitlab.io/python-shvtree/. You can
-also build the latest version from the source code using:
+The documentation is stored in `docs` directory. You can build the latest
+version from the source code using:
+
+.. code-block:: console
 
-    sphinx-build -b html docs docs-html
+    $ sphinx-build -b html docs docs-html
```

### Comparing `pyshv-0.1.1/pyshv.egg-info/PKG-INFO` & `pyshv-0.2.0/pyshv.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyshv
-Version: 0.1.1
+Version: 0.2.0
 Summary: Pure Python SHV implementation
 Author: Elektroline a.s.
 Project-URL: Homepage, https://gitlab.com/elektroline-predator/pyshv
 Project-URL: Bug Tracker, https://gitlab.com/elektroline-predator/pyshv/-/issues
 Project-URL: Github, https://github.com/silicon-heaven/libshv-py
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -28,28 +28,35 @@
 * `⁉️ Issue tracker <https://gitlab.com/elektroline-predator/pyshv/-/issues>`__
 * `📕 Documentation <https://elektroline-predator.gitlab.io/pyshv/>`__
 
 
 Installation
 ------------
 
-The installation can be done with package manager `pip`.
+The installation can be done with package manager ``pip``.
+
+.. code-block:: console
+
+   $ pip install pyshv
 
 
 Running tests
 -------------
 
-This project contains tests in directory tests.
+This project contains tests in directory ``tests``.
+
+Tests require `SHV applications <https://github.com/silicon-heaven/shvapp>`__.
 
 To run tests you have to use **pytest**. To run all tests just run it in the top
 level directory of the project. See the `pytest documentation
 <https://docs.pytest.org/>`__ for more info.
 
 
 Documentation
 -------------
 
-The documentation is available in `docs` directory and build version is
-available on https://elektroline-predator.gitlab.io/python-shvtree/. You can
-also build the latest version from the source code using:
+The documentation is stored in `docs` directory. You can build the latest
+version from the source code using:
+
+.. code-block:: console
 
-    sphinx-build -b html docs docs-html
+    $ sphinx-build -b html docs docs-html
```

### Comparing `pyshv-0.1.1/pyshv.egg-info/SOURCES.txt` & `pyshv-0.2.0/pyshv.egg-info/SOURCES.txt`

 * *Files 18% similar despite different names*

```diff
@@ -1,31 +1,38 @@
 LICENSE
 README.rst
 pyproject.toml
-docs/conf.py
 pyshv.egg-info/PKG-INFO
 pyshv.egg-info/SOURCES.txt
 pyshv.egg-info/dependency_links.txt
 pyshv.egg-info/entry_points.txt
 pyshv.egg-info/requires.txt
 pyshv.egg-info/top_level.txt
 shv/__init__.py
 shv/chainpack.py
-shv/clientconnection.py
-shv/cpcontext.py
+shv/commonpack.py
 shv/cpon.py
 shv/py.typed
-shv/rpcbroker.py
 shv/rpcclient.py
+shv/rpcerrors.py
 shv/rpcmessage.py
-shv/rpcprotocol.py
+shv/rpcmethod.py
 shv/rpcserver.py
-shv/rpcvalue.py
+shv/rpcurl.py
+shv/simpleclient.py
+shv/value.py
+shv/valueclient.py
+shv/broker/__init__.py
+shv/broker/__main__.py
+shv/broker/rpcbroker.py
+shv/broker/rpcbrokerconfig.py
 shv/cp2cp/__init__.py
 shv/cp2cp/__main__.py
 shv/cp2cp/cp2cp.py
-tests/__init__.py
-tests/conftest.py
-tests/test_client.py
-tests/test_clientconnection.py
-tests/test_conversions.py
-tests/test_example.py
+tests/test_chainpack.py
+tests/test_cp2cp.py
+tests/test_cpon.py
+tests/test_errors.py
+tests/test_example.py
+tests/test_rpcurl.py
+tests/test_simpleclient.py
+tests/test_value.py
```

### Comparing `pyshv-0.1.1/shv/chainpack.py` & `pyshv-0.2.0/shv/chainpack.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,17 +1,20 @@
+"""Chainpack data format reader and writer."""
+import collections.abc
+import datetime
+import decimal
+import math
 import struct
-import sys
 
-from .cpcontext import PackContext, UnpackContext
-from .rpcvalue import RpcValue
+from . import commonpack
+from .value import SHVMeta, SHVMetaType, SHVType, SHVUInt
 
 
 class ChainPack:
-    def __init__(self):
-        pass
+    """ChainPack constans and definitions."""
 
     ProtocolType = 1
 
     CP_Null = 128
     CP_UInt = 129
     CP_Int = 130
     CP_Double = 131
@@ -27,155 +30,85 @@
     CP_CString = 142
     CP_FALSE = 253
     CP_TRUE = 254
     CP_TERM = 255
 
     # UTC msec since 2.2. 2018
     # Fri Feb 02 2018 00:00:00 == 1517529600 EPOCH
-    SHV_EPOCH_MSEC = 1517529600000
+    SHV_EPOCH_SEC = 1517529600
     # ChainPack.INVALID_MIN_OFFSET_FROM_UTC = (-64 * 15)
 
-    @staticmethod
-    def is_little_endian():
-        return sys.byteorder == "little"
+    @classmethod
+    def unpack(cls, data: bytes | str) -> SHVType:
+        """Unpack single value from given data."""
+        return ChainPackReader.unpack(data)
 
+    @classmethod
+    def pack(cls, value: SHVType) -> bytes:
+        """Pack given value and return bytes."""
+        return ChainPackWriter.pack(value)
 
-class ChainPackReader:
-    def __init__(self, unpack_context):
-        if isinstance(unpack_context, (bytes, bytearray)):
-            unpack_context = UnpackContext(unpack_context)
-        self.ctx = unpack_context
-
-    def read(self):
-        packing_schema = self.ctx.get_byte()
-
-        if packing_schema == ChainPack.CP_MetaMap:
-            meta = self._read_map()
-            packing_schema = self.ctx.get_byte()
-        else:
-            meta = None
 
-        if packing_schema < 128:
-            if packing_schema & 64:
-                # tiny Int
-                value_type = RpcValue.Type.Int
-                value = packing_schema & 63
-            else:
-                # tiny UInt
-                value_type = RpcValue.Type.UInt
-                value = packing_schema & 63
-        else:
-            if packing_schema == ChainPack.CP_Null:
-                value_type = RpcValue.Type.Null
-                value = None
-            elif packing_schema == ChainPack.CP_TRUE:
-                value_type = RpcValue.Type.Bool
-                value = True
-
-            elif packing_schema == ChainPack.CP_FALSE:
-                value_type = RpcValue.Type.Bool
-                value = False
-
-            elif packing_schema == ChainPack.CP_Int:
-                value_type = RpcValue.Type.Int
-                value = self._read_int_data()
-            elif packing_schema == ChainPack.CP_UInt:
-                value_type = RpcValue.Type.UInt
-                value = self.read_uint_data()
-            elif packing_schema == ChainPack.CP_Double:
-                data = bytearray(8)
-                for i in range(8):
-                    data[i] = self.ctx.get_byte()
-                value_type = RpcValue.Type.Double
-                value = struct.unpack("<d", data)  # little endian
-            elif packing_schema == ChainPack.CP_Decimal:
-                mant = self._read_int_data()
-                exp = self._read_int_data()
-                value_type = RpcValue.Type.Decimal
-                value = RpcValue.Decimal(mant, exp)
-            elif packing_schema == ChainPack.CP_DateTime:
-                d = self.read_uint_data()
-                offset = 0
-                has_tz_offset = d & 1
-                has_not_msec = d & 2
-                d >>= 2
-                if has_tz_offset:
-                    offset = d & 0x7F
-                    if offset & 0b01000000:
-                        offset = offset - 128  # sign extension
-                    d >>= 7
-                if has_not_msec:
-                    d *= 1000
-                d += ChainPack.SHV_EPOCH_MSEC
-                value_type = RpcValue.Type.DateTime
-                value = RpcValue.DateTime(d, offset * 15)
-
-            elif packing_schema == ChainPack.CP_Map:
-                value_type = RpcValue.Type.Map
-                value = self._read_map()
-
-            elif packing_schema == ChainPack.CP_IMap:
-                value_type = RpcValue.Type.IMap
-                value = self._read_map()
-
-            elif packing_schema == ChainPack.CP_List:
-                value_type = RpcValue.Type.List
-                value = self._read_list()
-
-            elif packing_schema == ChainPack.CP_Blob:
-                str_len = self.read_uint_data()
-                arr = bytearray(str_len)
-                for i in range(str_len):
-                    arr[i] = self.ctx.get_byte()
-                value_type = RpcValue.Type.Blob
-                value = bytes(arr)
-
-            elif packing_schema == ChainPack.CP_String:
-                str_len = self.read_uint_data()
-                arr = bytearray(str_len)
-                for i in range(str_len):
-                    arr[i] = self.ctx.get_byte()
-                value_type = RpcValue.Type.String
-                value = bytes(arr).decode()
-
-            elif packing_schema == ChainPack.CP_CString:
-                # variation of CponReader.readCString()
-                pctx = PackContext()
-                while True:
-                    b = self.ctx.get_byte()
-                    if b == ord("\\"):
-                        b = self.ctx.get_byte()
-                        if b == ord("\\"):
-                            pctx.put_byte(ord("\\"))
-                        elif b == ord("0"):
-                            pctx.put_byte(0)
-                        else:
-                            pctx.put_byte(b)
-                    else:
-                        if b == 0:
-                            break  # end of string
-                        pctx.put_byte(b)
-                value_type = RpcValue.Type.String
-                value = pctx.data_bytes()
-            else:
-                raise TypeError("ChainPack - Invalid type info: " + packing_schema)
-        return RpcValue(value, meta, value_type)
+class ChainPackReader(commonpack.CommonReader):
+    """Read data in ChainPack format."""
 
-    @classmethod
-    def unpack(cls, chainpack):
-        if isinstance(chainpack, (bytes, bytearray)):
-            rd = ChainPackReader(UnpackContext(chainpack))
+    def read_meta(self) -> SHVMetaType | None:
+        if self._peek_byte() != ChainPack.CP_MetaMap:
+            return None
+        self._read_byte()
+        return self._read_map()
+
+    def read(self) -> SHVType:
+        meta = self.read_meta()
+
+        value: SHVType
+        packing_schema = self._read_byte()
+        if packing_schema < 128:
+            # tiny Int or UInt
+            value = packing_schema & 63
+            if not packing_schema & 64:
+                value = SHVUInt(value)
+        elif packing_schema == ChainPack.CP_Null:
+            value = None
+        elif packing_schema == ChainPack.CP_TRUE:
+            value = True
+        elif packing_schema == ChainPack.CP_FALSE:
+            value = False
+        elif packing_schema == ChainPack.CP_Int:
+            value = self._read_int_data()
+        elif packing_schema == ChainPack.CP_UInt:
+            value = SHVUInt(self.read_uint_data())
+        elif packing_schema == ChainPack.CP_Double:
+            value = self._read_double()
+        elif packing_schema == ChainPack.CP_Decimal:
+            value = self._read_decimal()
+        elif packing_schema == ChainPack.CP_DateTime:
+            value = self._read_datetime()
+        elif packing_schema == ChainPack.CP_Map:
+            value = self._read_map()
+        elif packing_schema == ChainPack.CP_IMap:
+            value = self._read_map()
+        elif packing_schema == ChainPack.CP_List:
+            value = self._read_list()
+        elif packing_schema == ChainPack.CP_Blob:
+            value = self._read_blob()
+        elif packing_schema == ChainPack.CP_String:
+            value = self._read_string()
+        elif packing_schema == ChainPack.CP_CString:
+            value = self._read_cstring()
         else:
-            raise TypeError("Unsupported type: " + type(chainpack))
-        return rd.read()
+            raise TypeError(f"ChainPack - Invalid type: {packing_schema}")
+        if meta is not None:
+            value = SHVMeta.new(value, meta)
+        return value
 
     def _read_uint_dataHelper(self):
         num = 0
         bitlen = 0
-        head = self.ctx.get_byte()
+        head = self._read_byte()
         if (head & 128) == 0:
             bytes_to_read_cnt = 0
             num = head & 127
             bitlen = 7
         elif (head & 64) == 0:
             bytes_to_read_cnt = 1
             num = head & 63
@@ -189,15 +122,15 @@
             num = head & 15
             bitlen = 4 + 3 * 8
         else:
             bytes_to_read_cnt = (head & 0xF) + 4
             bitlen = bytes_to_read_cnt * 8
 
         for _ in range(bytes_to_read_cnt):
-            r = self.ctx.get_byte()
+            r = self._read_byte()
             num = (num << 8) + r
         return num, bitlen
 
     def read_uint_data(self):
         num, _ = self._read_uint_dataHelper()
         return num
 
@@ -207,128 +140,132 @@
         neg = num & sign_bit_mask
         snum = num
         if neg:
             snum &= ~sign_bit_mask
             snum = -snum
         return snum
 
+    def _read_double(self) -> float:
+        res = struct.unpack("<d", self._read(8))  # little endian
+        return res[0]
+
+    def _read_decimal(self):
+        mant = self._read_int_data()
+        exp = self._read_int_data()
+        return decimal.Decimal(f"{mant}e{exp}")
+
+    def _read_datetime(self):
+        d = self.read_uint_data()
+        offset = 0
+        has_tz_offset = d & 1
+        has_not_msec = d & 2
+        d >>= 2
+        if has_tz_offset:
+            offset = d & 0x7F
+            if offset >= 128:
+                offset -= 128  # sign extension
+            d >>= 7
+        if not has_not_msec:
+            d /= 1000
+        d += ChainPack.SHV_EPOCH_SEC
+        tzone = datetime.timezone(datetime.timedelta(minutes=offset * 15))
+        return datetime.datetime.fromtimestamp(d, tzone)
+
+    def _read_blob(self) -> bytes:
+        dlen = self.read_uint_data()
+        return self._read(dlen)
+
+    def _read_string(self) -> str:
+        slen = self.read_uint_data()
+        if slen <= 0:
+            return ""
+        return self._read(slen).decode("utf-8")
+
+    def _read_cstring(self) -> str:
+        res = ""
+        while True:
+            b = self._read_byte()
+            if b == ord("\\"):
+                b = self._read_byte()
+                if b == ord("\\"):
+                    res += "\\"
+                elif b == ord("0"):
+                    res += "\0"
+                else:
+                    res += chr(b)
+            else:
+                if b == 0:
+                    break  # end of string
+                res += chr(b)
+        return res
+
     def _read_list(self):
         lst = []
         while True:
-            b = self.ctx.peek_byte()
+            b = self._peek_byte()
             if b == ChainPack.CP_TERM:
-                self.ctx.get_byte()
+                self._read_byte()
                 break
-            item = self.read()
-            lst.append(item)
+            lst.append(self.read())
         return lst
 
     def _read_map(self):
         mmap = {}
         while True:
-            b = self.ctx.peek_byte()
+            b = self._peek_byte()
             if b == ChainPack.CP_TERM:
-                self.ctx.get_byte()
+                self._read_byte()
                 break
             key = self.read()
-            # if !key)
-            #    raise TypeError("Malformed map, invalid key")
             val = self.read()
-            if key.type == RpcValue.Type.String:
-                mmap[key.value] = val
-            else:
-                mmap[int(key.value)] = val
+            mmap[key] = val
         return mmap
 
 
-class ChainPackWriter:
-    def __init__(self):
-        self.ctx = PackContext()
-
-    def write(self, rpc_val):
-        if not isinstance(rpc_val, RpcValue):
-            rpc_val = RpcValue(rpc_val)
-        if isinstance(rpc_val.meta, dict):
-            self.write_meta(rpc_val.meta)
-        if rpc_val.type == RpcValue.Type.Undefined:
-            # better to write null than create invalid chain-pack
-            self.ctx.put_byte(ChainPack.CP_Null)
-        if rpc_val.type == RpcValue.Type.Null:
-            self.ctx.put_byte(ChainPack.CP_Null)
-        elif rpc_val.type == RpcValue.Type.Bool:
-            self.ctx.put_byte(
-                ChainPack.CP_TRUE if rpc_val.value else ChainPack.CP_FALSE
-            )
-        elif rpc_val.type == RpcValue.Type.Blob:
-            self.write_blob(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.String:
-            self.write_string(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.UInt:
-            self.write_uint(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.Int:
-            self.write_int(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.Double:
-            self.write_double(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.Decimal:
-            self.write_decimal(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.List:
-            self.write_list(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.Map:
-            self.write_map(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.IMap:
-            self.write_imap(rpc_val.value)
-        elif rpc_val.type == RpcValue.Type.DateTime:
-            self.write_datetime(rpc_val.value)
-        else:
-            raise ValueError("Cannot pack invalid RpcValue type.")
-
-    def data_bytes(self):
-        return self.ctx.data_bytes()
-
-    @classmethod
-    def pack(cls, rpc_val):
-        wr = cls()
-        wr.write(rpc_val)
-        return wr.ctx.data_bytes()
+class ChainPackWriter(commonpack.CommonWriter):
+    """Write data in ChainPack format."""
 
-    # // see https://en.wikipedia.org/wiki/Find_first_set#CLZ
-    sig_table_4bit = [0, 1, 2, 2, 3, 3, 3, 3, 4, 4, 4, 4, 4, 4, 4, 4]
+    # Integer encoding:
+    #  0 ...  7 bits  1  byte  |0|s|x|x|x|x|x|x|<-- LSB
+    #  8 ... 14 bits  2  bytes |1|0|s|x|x|x|x|x| |x|x|x|x|x|x|x|x|<-- LSB
+    # 15 ... 21 bits  3  bytes |1|1|0|s|x|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x|<-- LSB
+    # 22 ... 28 bits  4  bytes |1|1|1|0|s|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x|<-- LSB
+    # 29+       bits  5+ bytes |1|1|1|1|n|n|n|n| |s|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x| ... <-- LSB
+    #                                         n ==  0 ->  4 bytes number (32 bit number)
+    #                                         n ==  1 ->  5 bytes number
+    #                                         n == 14 -> 18 bytes number
+    #                                         n == 15 -> for future (number of bytes will be specified in next byte)
 
     @staticmethod
-    def _significant_bits_part_length(num):
+    def _significant_bits_part_length(num: int) -> int:
         length = 0
         if num & 0xFFFFFFFF00000000:
             length += 32
             num >>= 32
         if num & 0xFFFF0000:
             length += 16
             num >>= 16
         if num & 0xFF00:
             length += 8
             num >>= 8
         if num & 0xF0:
             length += 4
             num >>= 4
-        length += ChainPackWriter.sig_table_4bit[num]
+        # see https://en.wikipedia.org/wiki/Find_first_set#CLZ
+        sig_table_4bit = [0, 1, 2, 2, 3, 3, 3, 3, 4, 4, 4, 4, 4, 4, 4, 4]
+        length += sig_table_4bit[num]
         return max(length, 1)
 
-    #  0 ...  7 bits  1  byte  |0|s|x|x|x|x|x|x|<-- LSB
-    #  8 ... 14 bits  2  bytes |1|0|s|x|x|x|x|x| |x|x|x|x|x|x|x|x|<-- LSB
-    # 15 ... 21 bits  3  bytes |1|1|0|s|x|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x|<-- LSB
-    # 22 ... 28 bits  4  bytes |1|1|1|0|s|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x|<-- LSB
-    # 29+       bits  5+ bytes |1|1|1|1|n|n|n|n| |s|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x| |x|x|x|x|x|x|x|x| ... <-- LSB
-    #                                         n ==  0 ->  4 bytes number (32 bit number)
-    #                                         n ==  1 ->  5 bytes number
-    #                                         n == 14 -> 18 bytes number
-    #                                         n == 15 -> for future (number of bytes will be specified in next byte)
-
-    # return max bit length >= bit_len, which can be encoded by same number of bytes
-    # number of bytes needed to encode bit_len
     @classmethod
-    def _bytes_needed(cls, bit_len):
+    def _bytes_needed(cls, bit_len: int) -> int:
+        """Calculate needed maximum number of bytes.
+
+        Return max bit length >= bit_len, which can be encoded by same number of
+        bytes number of bytes needed to encode bit_len.
+        """
         if bit_len <= 28:
             cnt = ((bit_len - 1) // 7) + 1
         else:
             cnt = ((bit_len - 1) // 8) + 2
         return cnt
 
     @classmethod
@@ -354,112 +291,115 @@
             mask = (mask << 1) & 0xFF
             data[0] = data[0] | mask
         else:
             data[0] = 0xF0 | (byte_cnt - 5)
 
         for i in range(0, byte_cnt):
             r = data[i]
-            self.ctx.put_byte(r)
+            self._write(r)
+
+    def write_meta(self, meta: dict) -> None:
+        self._write(ChainPack.CP_MetaMap)
+        self._write_map_data(meta)
+
+    def write_null(self) -> None:
+        self._write(ChainPack.CP_Null)
+
+    def write_bool(self, value: bool) -> None:
+        self._write(ChainPack.CP_TRUE if value else ChainPack.CP_FALSE)
+
+    def write_blob(self, value: bytes | bytearray) -> None:
+        self._write(ChainPack.CP_Blob)
+        self.write_uint_data(len(value))
+        self._write(value)
+
+    def write_string(self, value: str) -> None:
+        bstring = value.encode("utf-8")
+        self._write(ChainPack.CP_String)
+        self.write_uint_data(len(bstring))
+        self._write(bstring)
+
+    def write_cstring(self, value: str) -> None:
+        bstring = value.encode("utf-8")
+        self._write(ChainPack.CP_CString)
+        self._write(bstring)
+        self._write(b"\0")
+
+    def write_uint(self, value: int) -> None:
+        if value < 64:
+            self._write(value % 64)
+        else:
+            self._write(ChainPack.CP_UInt)
+            self.write_uint_data(value)
 
-    def write_uint_data(self, num):
-        bitcnt = self._significant_bits_part_length(num)
-        self._write_uint_data_helper(num, bitcnt)
-
-    def write_int_data(self, snum):
-        num = -snum if snum < 0 else snum
-        neg = snum < 0
+    def write_uint_data(self, value: int) -> None:
+        bitcnt = self._significant_bits_part_length(value)
+        self._write_uint_data_helper(value, bitcnt)
+
+    def write_int(self, value: int) -> None:
+        if 0 <= value < 64:
+            self._write((value % 64) + 64)
+        else:
+            self._write(ChainPack.CP_Int)
+            self.write_int_data(value)
+
+    def write_int_data(self, value: int) -> None:
+        num = -value if value < 0 else value
+        neg = value < 0
 
         bitlen = self._significant_bits_part_length(num)
         bitlen += 1  # add sign bit
         if neg:
             sign_pos = self._expand_bit_len(bitlen)
             sign_bit_mask = 1 << sign_pos
             num |= sign_bit_mask
         self._write_uint_data_helper(num, bitlen)
 
-    def write_uint(self, n):
-        if n < 64:
-            self.ctx.put_byte(n % 64)
-        else:
-            self.ctx.put_byte(ChainPack.CP_UInt)
-            self.write_uint_data(n)
-
-    def write_int(self, n):
-        if 0 <= n < 64:
-            self.ctx.put_byte((n % 64) + 64)
-        else:
-            self.ctx.put_byte(ChainPack.CP_Int)
-            self.write_int_data(n)
-
-    def write_decimal(self, val):
-        self.ctx.put_byte(ChainPack.CP_Decimal)
-        self.write_int_data(val.mantisa)
-        self.write_int_data(val.exponent)
-
-    def write_double(self, val: float):
-        self.ctx.put_byte(ChainPack.CP_Double)
-        data = struct.pack("<d", val)  # little endian
-        self.ctx.write_bytes(data)
-
-    def write_list(self, lst):
-        self.ctx.put_byte(ChainPack.CP_List)
-        for val in lst:
+    def write_double(self, value: float) -> None:
+        self._write(ChainPack.CP_Double)
+        self._write(struct.pack("<d", value))  # little endian
+
+    def write_decimal(self, value: decimal.Decimal) -> None:
+        n, d = value.as_integer_ratio()
+        self._write(ChainPack.CP_Decimal)
+        self.write_int_data(n)
+        self.write_int_data(-int(math.log10(d)))
+
+    def write_list(self, value: collections.abc.Iterable[SHVType]) -> None:
+        self._write(ChainPack.CP_List)
+        for val in value:
             self.write(val)
-        self.ctx.put_byte(ChainPack.CP_TERM)
+        self._write(ChainPack.CP_TERM)
 
-    def write_map_data(self, mmap):
+    def _write_map_data(self, mmap):
         for k, v in mmap.items():
             self.write(k)
             self.write(v)
-        self.ctx.put_byte(ChainPack.CP_TERM)
+        self._write(ChainPack.CP_TERM)
 
-    def write_map(self, mmap):
-        self.ctx.put_byte(ChainPack.CP_Map)
-        self.write_map_data(mmap)
-
-    def write_imap(self, mmap):
-        self.ctx.put_byte(ChainPack.CP_IMap)
-        self.write_map_data(mmap)
-
-    def write_meta(self, mmap):
-        self.ctx.put_byte(ChainPack.CP_MetaMap)
-        self.write_map_data(mmap)
-
-    def write_blob(self, data):
-        if not isinstance(data, (bytes, bytearray)):
-            raise TypeError("Unsupported type: " + type(data))
-        self.ctx.put_byte(ChainPack.CP_Blob)
-        self.write_uint_data(len(data))
-        for b in data:
-            self.ctx.put_byte(b)
-
-    def write_string(self, sstr):
-        if not isinstance(sstr, str):
-            raise TypeError("Unsupported type: " + type(sstr))
-        sstr = sstr.encode()
-        self.ctx.put_byte(ChainPack.CP_String)
-        self.write_uint_data(len(sstr))
-        for b in sstr:
-            self.ctx.put_byte(b)
-
-    def write_datetime(self, dt):
-        self.ctx.put_byte(ChainPack.CP_DateTime)
-
-        msecs = dt.epochMsec - ChainPack.SHV_EPOCH_MSEC
-        offset = dt.utcOffsetMin // 15
-        if not -63 <= offset <= 63:
-            raise TypeError("Invalid UTC offset value: " + offset)
-        # if offset < 0:
-        #     offset = 128 + offset
-        offset &= 0x7F
-        ms = msecs % 1000
-        if ms == 0:
-            msecs //= 1000
-        if offset != 0:
-            msecs <<= 7
-            msecs |= offset
-        msecs <<= 2
-        if offset != 0:
-            msecs |= 1
-        if ms == 0:
-            msecs |= 2
-        self.write_int_data(msecs)
+    def write_map(self, value: collections.abc.Mapping[str, SHVType]) -> None:
+        self._write(ChainPack.CP_Map)
+        self._write_map_data(value)
+
+    def write_imap(self, value: collections.abc.Mapping[int, SHVType]) -> None:
+        self._write(ChainPack.CP_IMap)
+        self._write_map_data(value)
+
+    def write_datetime(self, value: datetime.datetime) -> None:
+        self._write(ChainPack.CP_DateTime)
+        res = int(value.timestamp() * 1000) - (ChainPack.SHV_EPOCH_SEC * 1000)
+        tzdelta = value.utcoffset()
+        tzoff = int(tzdelta.total_seconds() // 60 // 15) if tzdelta is not None else 0
+        if not -63 <= tzoff <= 63:
+            raise TypeError(f"Invalid UTC offset value: {tzoff}")
+        ms = res % 1000 == 0
+        if ms:
+            res //= 1000
+        if tzoff != 0:
+            res <<= 7
+            res |= tzoff & 0x7F
+        res <<= 2
+        if tzoff != 0:
+            res |= 1
+        if ms:
+            res |= 2
+        self.write_int_data(res)
```

### Comparing `pyshv-0.1.1/shv/cp2cp/__main__.py` & `pyshv-0.2.0/shv/cp2cp/__main__.py`

 * *Files identical despite different names*


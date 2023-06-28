# Comparing `tmp/micropython-captive-dhcp-server-0.0.1.dev0.tar.gz` & `tmp/micropython-captive-dhcp-server-0.0.2.dev0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "micropython-captive-dhcp-server-0.0.1.dev0.tar", last modified: Fri Jun 23 07:53:25 2023, max compression
+gzip compressed data, was "micropython-captive-dhcp-server-0.0.2.dev0.tar", last modified: Wed Jun 28 08:12:55 2023, max compression
```

## Comparing `micropython-captive-dhcp-server-0.0.1.dev0.tar` & `micropython-captive-dhcp-server-0.0.2.dev0.tar`

### file list

```diff
@@ -1,15 +1,17 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-23 07:53:25.446891 micropython-captive-dhcp-server-0.0.1.dev0/
--rw-r--r--   0 runner    (1001) docker     (123)     1073 2023-06-23 07:53:21.000000 micropython-captive-dhcp-server-0.0.1.dev0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-23 07:53:25.446891 micropython-captive-dhcp-server-0.0.1.dev0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-23 07:53:21.000000 micropython-captive-dhcp-server-0.0.1.dev0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-23 07:53:25.446891 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-23 07:53:21.000000 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-23 07:53:25.446891 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-23 07:53:25.000000 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-23 07:53:25.000000 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-23 07:53:25.000000 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-23 07:53:25.000000 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-23 07:53:25.000000 micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      958 2023-06-23 07:53:21.000000 micropython-captive-dhcp-server-0.0.1.dev0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      608 2023-06-23 07:53:25.446891 micropython-captive-dhcp-server-0.0.1.dev0/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)       38 2023-06-23 07:53:21.000000 micropython-captive-dhcp-server-0.0.1.dev0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:12:55.171321 micropython-captive-dhcp-server-0.0.2.dev0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1073 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      915 2023-06-28 08:12:55.171321 micropython-captive-dhcp-server-0.0.2.dev0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      151 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:12:55.171321 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15413 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server/packet.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3412 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server/server.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:12:55.171321 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      915 2023-06-28 08:12:55.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      459 2023-06-28 08:12:55.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:12:55.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:12:55.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 08:12:55.000000 micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      958 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      608 2023-06-28 08:12:55.171321 micropython-captive-dhcp-server-0.0.2.dev0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)       38 2023-06-28 08:12:48.000000 micropython-captive-dhcp-server-0.0.2.dev0/setup.py
```

### Comparing `micropython-captive-dhcp-server-0.0.1.dev0/LICENSE` & `micropython-captive-dhcp-server-0.0.2.dev0/LICENSE`

 * *Files identical despite different names*

### Comparing `micropython-captive-dhcp-server-0.0.1.dev0/PKG-INFO` & `micropython-captive-dhcp-server-0.0.2.dev0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: micropython-captive-dhcp-server
-Version: 0.0.1.dev0
+Version: 0.0.2.dev0
 Summary: Micropython asyncio simplistic dhcp server for use with captive portals
 Author-email: Patrick McAndrew <patrick@urg.name>
 Project-URL: Homepage, https://github.com/urg/micropython-captive-dhcp-server
 Project-URL: Repository, https://github.com/urg/micropython-captive-dhcp-server
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
@@ -13,7 +13,9 @@
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # micropython-captive-dhcp-server
 Micropython asyncio simplistic dhcp server for use with captive portals
+
+docker compose exec busybox udhcpc -B -f -v
```

### Comparing `micropython-captive-dhcp-server-0.0.1.dev0/micropython_captive_dhcp_server.egg-info/PKG-INFO` & `micropython-captive-dhcp-server-0.0.2.dev0/micropython_captive_dhcp_server.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: micropython-captive-dhcp-server
-Version: 0.0.1.dev0
+Version: 0.0.2.dev0
 Summary: Micropython asyncio simplistic dhcp server for use with captive portals
 Author-email: Patrick McAndrew <patrick@urg.name>
 Project-URL: Homepage, https://github.com/urg/micropython-captive-dhcp-server
 Project-URL: Repository, https://github.com/urg/micropython-captive-dhcp-server
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
@@ -13,7 +13,9 @@
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # micropython-captive-dhcp-server
 Micropython asyncio simplistic dhcp server for use with captive portals
+
+docker compose exec busybox udhcpc -B -f -v
```

### Comparing `micropython-captive-dhcp-server-0.0.1.dev0/pyproject.toml` & `micropython-captive-dhcp-server-0.0.2.dev0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 requires = [
     "setuptools>=61.0"
 ]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "micropython-captive-dhcp-server"
-version = "0.0.1.dev"
+version = "0.0.2.dev"
 description = "Micropython asyncio simplistic dhcp server for use with captive portals"
 classifiers = [
     "Environment :: Web Environment",
     "Intended Audience :: Developers",
     "Programming Language :: Python :: 3",
     "Programming Language :: Python :: Implementation :: MicroPython",
     "License :: OSI Approved :: MIT License",
```

### Comparing `micropython-captive-dhcp-server-0.0.1.dev0/setup.cfg` & `micropython-captive-dhcp-server-0.0.2.dev0/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = "micropython-captive-dhcp-server"
-version = "0.0.1.dev"
+version = "0.0.2.dev"
 description = "Micropython asyncio simplistic dhcp server for use with captive portals"
 classifiers = 
 	Environment :: Web Environment
 	Intended Audience :: Developers
 	Programming Language :: Python :: 3
 	Programming Language :: Python :: Implementation :: MicroPython
 	License :: OSI Approved :: MIT License
```


# Comparing `tmp/iotics-grpc-client-3.0.1.tar.gz` & `tmp/iotics-grpc-client-4.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "iotics-grpc-client-3.0.1.tar", last modified: Tue May 23 12:09:12 2023, max compression
+gzip compressed data, was "iotics-grpc-client-4.0.0.tar", last modified: Wed Jun 28 15:31:34 2023, max compression
```

## Comparing `iotics-grpc-client-3.0.1.tar` & `iotics-grpc-client-4.0.0.tar`

### file list

```diff
@@ -1,48 +1,48 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.398499 iotics-grpc-client-3.0.1/
--rw-r--r--   0 runner    (1001) docker     (123)    11336 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     7022 2023-05-23 12:09:12.398499 iotics-grpc-client-3.0.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5278 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     1149 2023-05-23 12:09:12.398499 iotics-grpc-client-3.0.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.390500 iotics-grpc-client-3.0.1/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.390500 iotics-grpc-client-3.0.1/src/iotics/
--rw-r--r--   0 runner    (1001) docker     (123)      894 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.394499 iotics-grpc-client-3.0.1/src/iotics/api/
--rw-r--r--   0 runner    (1001) docker     (123)     5966 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/common_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)      159 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/common_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)    10085 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/feed_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)    11933 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/feed_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)     2116 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/host_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     3092 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/host_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)     9057 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/input_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     9814 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/input_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)     5498 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/interest_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     6570 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/interest_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)     4821 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/meta_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     7425 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/meta_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)     6883 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/search_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     8578 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/search_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)    11149 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/twin_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)    11352 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/api/twin_pb2_grpc.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.394499 iotics-grpc-client-3.0.1/src/iotics/lib/
--rw-r--r--   0 runner    (1001) docker     (123)      894 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.398499 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/
--rw-r--r--   0 runner    (1001) docker     (123)     1600 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1414 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/auth.py
--rw-r--r--   0 runner    (1001) docker     (123)     1095 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     8584 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/feeds.py
--rw-r--r--   0 runner    (1001) docker     (123)     5088 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/host.py
--rw-r--r--   0 runner    (1001) docker     (123)     7253 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/input.py
--rw-r--r--   0 runner    (1001) docker     (123)     7250 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/interest.py
--rw-r--r--   0 runner    (1001) docker     (123)     6701 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/iotics_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     6573 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/search.py
--rw-r--r--   0 runner    (1001) docker     (123)     3215 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/sparql.py
--rw-r--r--   0 runner    (1001) docker     (123)     8007 2023-05-23 12:09:07.000000 iotics-grpc-client-3.0.1/src/iotics/lib/grpc/twins.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-23 12:09:12.398499 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     7022 2023-05-23 12:09:12.000000 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-05-23 12:09:12.000000 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-23 12:09:12.000000 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      121 2023-05-23 12:09:12.000000 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-05-23 12:09:12.000000 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-23 12:09:12.000000 iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/zip-safe
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    11336 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     7098 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5346 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1149 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.965135 iotics-grpc-client-4.0.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.965135 iotics-grpc-client-4.0.0/src/iotics/
+-rw-r--r--   0 runner    (1001) docker     (123)      894 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/src/iotics/api/
+-rw-r--r--   0 runner    (1001) docker     (123)     5823 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/common_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/common_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10085 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/feed_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11933 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/feed_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2116 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/host_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3092 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/host_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9057 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/input_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9814 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/input_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5498 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/interest_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6570 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/interest_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4821 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/meta_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7425 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/meta_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6800 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/search_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8578 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/search_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10613 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/twin_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11352 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/api/twin_pb2_grpc.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/src/iotics/lib/
+-rw-r--r--   0 runner    (1001) docker     (123)      894 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/
+-rw-r--r--   0 runner    (1001) docker     (123)     1588 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1414 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1095 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8584 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/feeds.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5522 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/host.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7262 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/input.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7256 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/interest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6701 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/iotics_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6573 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/search.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3215 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/sparql.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7565 2023-06-28 15:31:29.000000 iotics-grpc-client-4.0.0/src/iotics/lib/grpc/twins.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:34.969135 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     7098 2023-06-28 15:31:34.000000 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-06-28 15:31:34.000000 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:31:34.000000 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      121 2023-06-28 15:31:34.000000 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 15:31:34.000000 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:31:34.000000 iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/zip-safe
```

### Comparing `iotics-grpc-client-3.0.1/LICENSE` & `iotics-grpc-client-4.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/PKG-INFO` & `iotics-grpc-client-4.0.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,24 +1,25 @@
 Metadata-Version: 2.1
 Name: iotics-grpc-client
-Version: 3.0.1
+Version: 4.0.0
 Summary: Iotics gRPC client library
 Home-page: https://github.com/Iotic-Labs/iotics-grpc-client-py
 Author: Iotics
 License: UNKNOWN
 Project-URL: Bug Tracker, https://github.com/Iotic-Labs/iotics-grpc-client-py/issues
 Project-URL: Changelog, https://github.com/Iotic-Labs/iotics-grpc-client-py/releases
 Description: # Iotics gRPC Python Client
         A Python library for interacting with Iotics API.
         
         
         ## Usage and Version Compatibility with Iotics host:
         
         | iotics-grpc-client-py | iotics-host |
         |----------------------| ----------- |
+        |      `pip install iotics-grpc-client~=4.0`       | `>= 6`       |
         |      `pip install iotics-grpc-client~=3.0`       | `>= 6`       |
         |      `pip install iotics-grpc-client~=2.0`       | `>= 5`       |
         |      `pip install iotics-grpc-client~=0.10.0`      | `>= 4`     |
         
         
         
         # Examples
@@ -28,15 +29,15 @@
         * __Required__:
           * `SPACE` - Domain name of the IOTICSpace with which to communicate. The scheme can be omitted, eg. examplecorp.
             iotics.space
           * `USER_DID` - Identity of the user
           * `AGENT_DID` - Identity of the agent authorised to operate on the user's behalf
           * `AGENT_KEY_NAME` - __secret__ value used to (re)create multiple key pairs
           * `AGENT_NAME` - registered identity name that can be used to e.g. identify public keys
-          * `AGENT SECRET` - __secret__ value, the agent's private key
+          * `AGENT_SECRET` - __secret__ value, the agent's private key
         
         * __Optional__:
           * `DID_RESOLVER_URL` - Where the database of identity documents is accessible, defaults to the one used by the given 
             space.
           * `TOKEN_TTL` - How long in seconds auth tokens will last if not specified in the method call, defaults to 30
         ## Running example scripts
         Next, create and activate your virtual environment and run any of the scripts in the [examples](https://github.com/Iotic-Labs/iotics-grpc-client-py/tree/main/examples) directory,
```

### Comparing `iotics-grpc-client-3.0.1/README.md` & `iotics-grpc-client-4.0.0/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 A Python library for interacting with Iotics API.
 
 
 ## Usage and Version Compatibility with Iotics host:
 
 | iotics-grpc-client-py | iotics-host |
 |----------------------| ----------- |
+|      `pip install iotics-grpc-client~=4.0`       | `>= 6`       |
 |      `pip install iotics-grpc-client~=3.0`       | `>= 6`       |
 |      `pip install iotics-grpc-client~=2.0`       | `>= 5`       |
 |      `pip install iotics-grpc-client~=0.10.0`      | `>= 4`     |
 
 
 
 # Examples
@@ -19,15 +20,15 @@
 * __Required__:
   * `SPACE` - Domain name of the IOTICSpace with which to communicate. The scheme can be omitted, eg. examplecorp.
     iotics.space
   * `USER_DID` - Identity of the user
   * `AGENT_DID` - Identity of the agent authorised to operate on the user's behalf
   * `AGENT_KEY_NAME` - __secret__ value used to (re)create multiple key pairs
   * `AGENT_NAME` - registered identity name that can be used to e.g. identify public keys
-  * `AGENT SECRET` - __secret__ value, the agent's private key
+  * `AGENT_SECRET` - __secret__ value, the agent's private key
 
 * __Optional__:
   * `DID_RESOLVER_URL` - Where the database of identity documents is accessible, defaults to the one used by the given 
     space.
   * `TOKEN_TTL` - How long in seconds auth tokens will last if not specified in the method call, defaults to 30
 ## Running example scripts
 Next, create and activate your virtual environment and run any of the scripts in the [examples](https://github.com/Iotic-Labs/iotics-grpc-client-py/tree/main/examples) directory,
```

### Comparing `iotics-grpc-client-3.0.1/setup.cfg` & `iotics-grpc-client-4.0.0/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = iotics-grpc-client
-version = 3.0.1
+version = 4.0.0
 description = Iotics gRPC client library
 long_description = file: README.md
 long_description_content_type = text/markdown
 author = Iotics
 platform = any
 url = https://github.com/Iotic-Labs/iotics-grpc-client-py
 keywords = iotics, grpc, digital twin
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/__init__.py` & `iotics-grpc-client-4.0.0/src/iotics/__init__.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/common_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/common_pb2.py`

 * *Files 4% similar despite different names*

```diff
@@ -11,26 +11,24 @@
 _sym_db = _symbol_database.Default()
 
 
 from google.protobuf import wrappers_pb2 as google_dot_protobuf_dot_wrappers__pb2
 from google.protobuf import timestamp_pb2 as google_dot_protobuf_dot_timestamp__pb2
 
 
-DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x17iotics/api/common.proto\x12\niotics.api\x1a\x1egoogle/protobuf/wrappers.proto\x1a\x1fgoogle/protobuf/timestamp.proto\"\x1d\n\x05Limit\x12\x14\n\x05value\x18\x01 \x01(\rR\x05value\"\x1e\n\x06Offset\x12\x14\n\x05value\x18\x01 \x01(\rR\x05value\"\\\n\x05Range\x12\'\n\x05limit\x18\x01 \x01(\x0b\x32\x11.iotics.api.LimitR\x05limit\x12*\n\x06offset\x18\x02 \x01(\x0b\x32\x12.iotics.api.OffsetR\x06offset\"7\n\x0bLangLiteral\x12\x12\n\x04lang\x18\x01 \x01(\tR\x04lang\x12\x14\n\x05value\x18\x02 \x01(\tR\x05value\"%\n\rStringLiteral\x12\x14\n\x05value\x18\x02 \x01(\tR\x05value\";\n\x07Literal\x12\x1a\n\x08\x64\x61taType\x18\x01 \x01(\tR\x08\x64\x61taType\x12\x14\n\x05value\x18\x02 \x01(\tR\x05value\"\x1b\n\x03Uri\x12\x14\n\x05value\x18\x01 \x01(\tR\x05value\"\xa3\x02\n\x08Property\x12\x10\n\x03key\x18\x01 \x01(\tR\x03key\x12\x39\n\x0cliteralValue\x18\x02 \x01(\x0b\x32\x13.iotics.api.LiteralH\x00R\x0cliteralValue\x12\x45\n\x10langLiteralValue\x18\x03 \x01(\x0b\x32\x17.iotics.api.LangLiteralH\x00R\x10langLiteralValue\x12K\n\x12stringLiteralValue\x18\x04 \x01(\x0b\x32\x19.iotics.api.StringLiteralH\x00R\x12stringLiteralValue\x12-\n\x08uriValue\x18\x05 \x01(\x0b\x32\x0f.iotics.api.UriH\x00R\x08uriValueB\x07\n\x05value\"1\n\x0bGeoLocation\x12\x10\n\x03lat\x18\x01 \x01(\x01R\x03lat\x12\x10\n\x03lon\x18\x02 \x01(\x01R\x03lon\"\\\n\tGeoCircle\x12\x33\n\x08location\x18\x01 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x1a\n\x08radiusKm\x18\x02 \x01(\x01R\x08radiusKm\"\xf9\x01\n\x07Headers\x12\x1c\n\tclientRef\x18\x01 \x01(\tR\tclientRef\x12 \n\x0b\x63lientAppId\x18\x02 \x01(\tR\x0b\x63lientAppId\x12&\n\x0etransactionRef\x18\x03 \x03(\tR\x0etransactionRef\x12\x42\n\rconsumerGroup\x18\x04 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\rconsumerGroup\x12\x42\n\x0erequestTimeout\x18\x05 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x0erequestTimeout\"\xa3\x01\n\x13SubscriptionHeaders\x12 \n\x0b\x63lientAppId\x18\x01 \x01(\tR\x0b\x63lientAppId\x12&\n\x0etransactionRef\x18\x02 \x03(\tR\x0etransactionRef\x12\x42\n\rconsumerGroup\x18\x03 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\rconsumerGroup\"0\n\x06TwinID\x12\x0e\n\x02id\x18\x01 \x01(\tR\x02id\x12\x16\n\x06hostId\x18\x02 \x01(\tR\x06hostId\"g\n\x05Value\x12\x14\n\x05label\x18\x01 \x01(\tR\x05label\x12\x18\n\x07\x63omment\x18\x02 \x01(\tR\x07\x63omment\x12\x12\n\x04unit\x18\x03 \x01(\tR\x04unit\x12\x1a\n\x08\x64\x61taType\x18\x04 \x01(\tR\x08\x64\x61taType\"Y\n\x06Values\x12\'\n\x05\x61\x64\x64\x65\x64\x18\x01 \x03(\x0b\x32\x11.iotics.api.ValueR\x05\x61\x64\x64\x65\x64\x12&\n\x0e\x64\x65letedByLabel\x18\x02 \x03(\tR\x0e\x64\x65letedByLabel\"n\n\x08\x46\x65\x65\x64\x44\x61ta\x12:\n\noccurredAt\x18\x02 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\noccurredAt\x12\x12\n\x04mime\x18\x03 \x01(\tR\x04mime\x12\x12\n\x04\x64\x61ta\x18\x04 \x01(\x0cR\x04\x64\x61ta\"\xb0\x01\n\x0ePropertyUpdate\x12\x1e\n\nclearedAll\x18\x01 \x01(\x08R\nclearedAll\x12.\n\x07\x64\x65leted\x18\x02 \x03(\x0b\x32\x14.iotics.api.PropertyR\x07\x64\x65leted\x12\"\n\x0c\x64\x65letedByKey\x18\x03 \x03(\tR\x0c\x64\x65letedByKey\x12*\n\x05\x61\x64\x64\x65\x64\x18\x04 \x03(\x0b\x32\x14.iotics.api.PropertyR\x05\x61\x64\x64\x65\x64*%\n\nVisibility\x12\x0b\n\x07PRIVATE\x10\x00\x12\n\n\x06PUBLIC\x10\x01*\x1e\n\x05Scope\x12\n\n\x06GLOBAL\x10\x00\x12\t\n\x05LOCAL\x10\x01\x42\x7f\n\x0e\x63om.iotics.apiB\x0b\x43ommonProtoP\x01Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\xa2\x02\x03IAX\xaa\x02\nIotics.Api\xca\x02\nIotics\\Apib\x06proto3')
+DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x17iotics/api/common.proto\x12\niotics.api\x1a\x1egoogle/protobuf/wrappers.proto\x1a\x1fgoogle/protobuf/timestamp.proto\"\x1d\n\x05Limit\x12\x14\n\x05value\x18\x01 \x01(\rR\x05value\"\x1e\n\x06Offset\x12\x14\n\x05value\x18\x01 \x01(\rR\x05value\"\\\n\x05Range\x12\'\n\x05limit\x18\x01 \x01(\x0b\x32\x11.iotics.api.LimitR\x05limit\x12*\n\x06offset\x18\x02 \x01(\x0b\x32\x12.iotics.api.OffsetR\x06offset\"7\n\x0bLangLiteral\x12\x12\n\x04lang\x18\x01 \x01(\tR\x04lang\x12\x14\n\x05value\x18\x02 \x01(\tR\x05value\"%\n\rStringLiteral\x12\x14\n\x05value\x18\x02 \x01(\tR\x05value\";\n\x07Literal\x12\x1a\n\x08\x64\x61taType\x18\x01 \x01(\tR\x08\x64\x61taType\x12\x14\n\x05value\x18\x02 \x01(\tR\x05value\"\x1b\n\x03Uri\x12\x14\n\x05value\x18\x01 \x01(\tR\x05value\"\xa3\x02\n\x08Property\x12\x10\n\x03key\x18\x01 \x01(\tR\x03key\x12\x39\n\x0cliteralValue\x18\x02 \x01(\x0b\x32\x13.iotics.api.LiteralH\x00R\x0cliteralValue\x12\x45\n\x10langLiteralValue\x18\x03 \x01(\x0b\x32\x17.iotics.api.LangLiteralH\x00R\x10langLiteralValue\x12K\n\x12stringLiteralValue\x18\x04 \x01(\x0b\x32\x19.iotics.api.StringLiteralH\x00R\x12stringLiteralValue\x12-\n\x08uriValue\x18\x05 \x01(\x0b\x32\x0f.iotics.api.UriH\x00R\x08uriValueB\x07\n\x05value\"1\n\x0bGeoLocation\x12\x10\n\x03lat\x18\x01 \x01(\x01R\x03lat\x12\x10\n\x03lon\x18\x02 \x01(\x01R\x03lon\"\\\n\tGeoCircle\x12\x33\n\x08location\x18\x01 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x1a\n\x08radiusKm\x18\x02 \x01(\x01R\x08radiusKm\"\xf9\x01\n\x07Headers\x12\x1c\n\tclientRef\x18\x01 \x01(\tR\tclientRef\x12 \n\x0b\x63lientAppId\x18\x02 \x01(\tR\x0b\x63lientAppId\x12&\n\x0etransactionRef\x18\x03 \x03(\tR\x0etransactionRef\x12\x42\n\rconsumerGroup\x18\x04 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\rconsumerGroup\x12\x42\n\x0erequestTimeout\x18\x05 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x0erequestTimeout\"\xa3\x01\n\x13SubscriptionHeaders\x12 \n\x0b\x63lientAppId\x18\x01 \x01(\tR\x0b\x63lientAppId\x12&\n\x0etransactionRef\x18\x02 \x03(\tR\x0etransactionRef\x12\x42\n\rconsumerGroup\x18\x03 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\rconsumerGroup\"0\n\x06TwinID\x12\x0e\n\x02id\x18\x01 \x01(\tR\x02id\x12\x16\n\x06hostId\x18\x02 \x01(\tR\x06hostId\"g\n\x05Value\x12\x14\n\x05label\x18\x01 \x01(\tR\x05label\x12\x18\n\x07\x63omment\x18\x02 \x01(\tR\x07\x63omment\x12\x12\n\x04unit\x18\x03 \x01(\tR\x04unit\x12\x1a\n\x08\x64\x61taType\x18\x04 \x01(\tR\x08\x64\x61taType\"Y\n\x06Values\x12\'\n\x05\x61\x64\x64\x65\x64\x18\x01 \x03(\x0b\x32\x11.iotics.api.ValueR\x05\x61\x64\x64\x65\x64\x12&\n\x0e\x64\x65letedByLabel\x18\x02 \x03(\tR\x0e\x64\x65letedByLabel\"n\n\x08\x46\x65\x65\x64\x44\x61ta\x12:\n\noccurredAt\x18\x02 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\noccurredAt\x12\x12\n\x04mime\x18\x03 \x01(\tR\x04mime\x12\x12\n\x04\x64\x61ta\x18\x04 \x01(\x0cR\x04\x64\x61ta\"\xb0\x01\n\x0ePropertyUpdate\x12\x1e\n\nclearedAll\x18\x01 \x01(\x08R\nclearedAll\x12.\n\x07\x64\x65leted\x18\x02 \x03(\x0b\x32\x14.iotics.api.PropertyR\x07\x64\x65leted\x12\"\n\x0c\x64\x65letedByKey\x18\x03 \x03(\tR\x0c\x64\x65letedByKey\x12*\n\x05\x61\x64\x64\x65\x64\x18\x04 \x03(\x0b\x32\x14.iotics.api.PropertyR\x05\x61\x64\x64\x65\x64*\x1e\n\x05Scope\x12\n\n\x06GLOBAL\x10\x00\x12\t\n\x05LOCAL\x10\x01\x42\x7f\n\x0e\x63om.iotics.apiB\x0b\x43ommonProtoP\x01Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\xa2\x02\x03IAX\xaa\x02\nIotics.Api\xca\x02\nIotics\\Apib\x06proto3')
 
 _builder.BuildMessageAndEnumDescriptors(DESCRIPTOR, globals())
 _builder.BuildTopDescriptorsAndMessages(DESCRIPTOR, 'iotics.api.common_pb2', globals())
 if _descriptor._USE_C_DESCRIPTORS == False:
 
   DESCRIPTOR._options = None
   DESCRIPTOR._serialized_options = b'\n\016com.iotics.apiB\013CommonProtoP\001Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\242\002\003IAX\252\002\nIotics.Api\312\002\nIotics\\Api'
-  _VISIBILITY._serialized_start=1841
-  _VISIBILITY._serialized_end=1878
-  _SCOPE._serialized_start=1880
-  _SCOPE._serialized_end=1910
+  _SCOPE._serialized_start=1841
+  _SCOPE._serialized_end=1871
   _LIMIT._serialized_start=104
   _LIMIT._serialized_end=133
   _OFFSET._serialized_start=135
   _OFFSET._serialized_end=165
   _RANGE._serialized_start=167
   _RANGE._serialized_end=259
   _LANGLITERAL._serialized_start=261
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/feed_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/feed_pb2.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/feed_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/feed_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/host_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/host_pb2.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/host_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/host_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/input_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/input_pb2.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/input_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/input_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/interest_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/interest_pb2.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/interest_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/interest_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/meta_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/meta_pb2.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/meta_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/meta_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/search_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/search_pb2.py`

 * *Files 8% similar despite different names*

```diff
@@ -15,42 +15,42 @@
 from google.protobuf import timestamp_pb2 as google_dot_protobuf_dot_timestamp__pb2
 from google.rpc import status_pb2 as google_dot_rpc_dot_status__pb2
 from iotics.api import common_pb2 as iotics_dot_api_dot_common__pb2
 from iotics.api import feed_pb2 as iotics_dot_api_dot_feed__pb2
 from iotics.api import input_pb2 as iotics_dot_api_dot_input__pb2
 
 
-DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x17iotics/api/search.proto\x12\niotics.api\x1a\x1egoogle/protobuf/wrappers.proto\x1a\x1fgoogle/protobuf/timestamp.proto\x1a\x17google/rpc/status.proto\x1a\x17iotics/api/common.proto\x1a\x15iotics/api/feed.proto\x1a\x16iotics/api/input.proto\"\xf3\x04\n\rSearchRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\'\n\x05scope\x18\x02 \x01(\x0e\x32\x11.iotics.api.ScopeR\x05scope\x12\x30\n\x04lang\x18\x03 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\x04lang\x12;\n\x07payload\x18\x06 \x01(\x0b\x32!.iotics.api.SearchRequest.PayloadR\x07payload\x12\'\n\x05range\x18\x14 \x01(\x0b\x32\x11.iotics.api.RangeR\x05range\x1a\xf1\x02\n\x07Payload\x12<\n\x0cresponseType\x18\x01 \x01(\x0e\x32\x18.iotics.api.ResponseTypeR\x0cresponseType\x12@\n\rexpiryTimeout\x18\x02 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\rexpiryTimeout\x12@\n\x06\x66ilter\x18\x03 \x01(\x0b\x32(.iotics.api.SearchRequest.Payload.FilterR\x06\x66ilter\x1a\xa3\x01\n\x06\x46ilter\x12\x30\n\x04text\x18\x01 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\x04text\x12\x31\n\x08location\x18\x02 \x01(\x0b\x32\x15.iotics.api.GeoCircleR\x08location\x12\x34\n\nproperties\x18\x03 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\"\xbe\x02\n\x15\x41\x64vancedSearchRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\'\n\x05scope\x18\x02 \x01(\x0e\x32\x11.iotics.api.ScopeR\x05scope\x12\x43\n\x07payload\x18\x03 \x01(\x0b\x32).iotics.api.AdvancedSearchRequest.PayloadR\x07payload\x12\'\n\x05range\x18\x14 \x01(\x0b\x32\x11.iotics.api.RangeR\x05range\x1a_\n\x07Payload\x12<\n\x0cresponseType\x18\x01 \x01(\x0e\x32\x18.iotics.api.ResponseTypeR\x0cresponseType\x12\x16\n\x06\x66ilter\x18\x02 \x01(\tR\x06\x66ilter\"\xa0\x08\n\x0eSearchResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12<\n\x07payload\x18\x02 \x01(\x0b\x32\".iotics.api.SearchResponse.PayloadR\x07payload\x1a\x8d\x01\n\x0b\x46\x65\x65\x64\x44\x65tails\x12*\n\x06\x66\x65\x65\x64Id\x18\x01 \x01(\x0b\x32\x12.iotics.api.FeedIDR\x06\x66\x65\x65\x64Id\x12\x1c\n\tstoreLast\x18\x03 \x01(\x08R\tstoreLast\x12\x34\n\nproperties\x18\x04 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x1as\n\x0cInputDetails\x12-\n\x07inputId\x18\x01 \x01(\x0b\x32\x13.iotics.api.InputIDR\x07inputId\x12\x34\n\nproperties\x18\x04 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x1a\xcf\x03\n\x0bTwinDetails\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x33\n\x08location\x18\x02 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x36\n\nvisibility\x18\x03 \x01(\x0e\x32\x16.iotics.api.VisibilityR\nvisibility\x12\x34\n\nproperties\x18\x05 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12<\n\x05\x66\x65\x65\x64s\x18\n \x03(\x0b\x32&.iotics.api.SearchResponse.FeedDetailsR\x05\x66\x65\x65\x64s\x12?\n\x06inputs\x18\x0b \x03(\x0b\x32\'.iotics.api.SearchResponse.InputDetailsR\x06inputs\x12\x38\n\tcreatedAt\x18\x0c \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tcreatedAt\x12\x38\n\tupdatedAt\x18\r \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tupdatedAt\x1a\xc9\x01\n\x07Payload\x12<\n\x0cresponseType\x18\x01 \x01(\x0e\x32\x18.iotics.api.ResponseTypeR\x0cresponseType\x12*\n\x06status\x18\x02 \x01(\x0b\x32\x12.google.rpc.StatusR\x06status\x12\x16\n\x06hostId\x18\x03 \x01(\tR\x06hostId\x12<\n\x05twins\x18\n \x03(\x0b\x32&.iotics.api.SearchResponse.TwinDetailsR\x05twins\"\x18\n\x16\x44ispatchSearchResponse*2\n\x0cResponseType\x12\x08\n\x04\x46ULL\x10\x00\x12\x0b\n\x07LOCATED\x10\x01\x12\x0b\n\x07MINIMAL\x10\x02\x32\xe8\x02\n\tSearchAPI\x12X\n\x15\x44ispatchSearchRequest\x12\x19.iotics.api.SearchRequest\x1a\".iotics.api.DispatchSearchResponse\"\x00\x12N\n\x11SynchronousSearch\x12\x19.iotics.api.SearchRequest\x1a\x1a.iotics.api.SearchResponse\"\x00\x30\x01\x12\\\n\x19ReceiveAllSearchResponses\x12\x1f.iotics.api.SubscriptionHeaders\x1a\x1a.iotics.api.SearchResponse\"\x00\x30\x01\x12S\n\x0e\x41\x64vancedSearch\x12!.iotics.api.AdvancedSearchRequest\x1a\x1a.iotics.api.SearchResponse\"\x00\x30\x01\x42\x7f\n\x0e\x63om.iotics.apiB\x0bSearchProtoP\x01Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\xa2\x02\x03IAX\xaa\x02\nIotics.Api\xca\x02\nIotics\\Apib\x06proto3')
+DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x17iotics/api/search.proto\x12\niotics.api\x1a\x1egoogle/protobuf/wrappers.proto\x1a\x1fgoogle/protobuf/timestamp.proto\x1a\x17google/rpc/status.proto\x1a\x17iotics/api/common.proto\x1a\x15iotics/api/feed.proto\x1a\x16iotics/api/input.proto\"\xf3\x04\n\rSearchRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\'\n\x05scope\x18\x02 \x01(\x0e\x32\x11.iotics.api.ScopeR\x05scope\x12\x30\n\x04lang\x18\x03 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\x04lang\x12;\n\x07payload\x18\x06 \x01(\x0b\x32!.iotics.api.SearchRequest.PayloadR\x07payload\x12\'\n\x05range\x18\x14 \x01(\x0b\x32\x11.iotics.api.RangeR\x05range\x1a\xf1\x02\n\x07Payload\x12<\n\x0cresponseType\x18\x01 \x01(\x0e\x32\x18.iotics.api.ResponseTypeR\x0cresponseType\x12@\n\rexpiryTimeout\x18\x02 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\rexpiryTimeout\x12@\n\x06\x66ilter\x18\x03 \x01(\x0b\x32(.iotics.api.SearchRequest.Payload.FilterR\x06\x66ilter\x1a\xa3\x01\n\x06\x46ilter\x12\x30\n\x04text\x18\x01 \x01(\x0b\x32\x1c.google.protobuf.StringValueR\x04text\x12\x31\n\x08location\x18\x02 \x01(\x0b\x32\x15.iotics.api.GeoCircleR\x08location\x12\x34\n\nproperties\x18\x03 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\"\xbe\x02\n\x15\x41\x64vancedSearchRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\'\n\x05scope\x18\x02 \x01(\x0e\x32\x11.iotics.api.ScopeR\x05scope\x12\x43\n\x07payload\x18\x03 \x01(\x0b\x32).iotics.api.AdvancedSearchRequest.PayloadR\x07payload\x12\'\n\x05range\x18\x14 \x01(\x0b\x32\x11.iotics.api.RangeR\x05range\x1a_\n\x07Payload\x12<\n\x0cresponseType\x18\x01 \x01(\x0e\x32\x18.iotics.api.ResponseTypeR\x0cresponseType\x12\x16\n\x06\x66ilter\x18\x02 \x01(\tR\x06\x66ilter\"\xe8\x07\n\x0eSearchResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12<\n\x07payload\x18\x02 \x01(\x0b\x32\".iotics.api.SearchResponse.PayloadR\x07payload\x1a\x8d\x01\n\x0b\x46\x65\x65\x64\x44\x65tails\x12*\n\x06\x66\x65\x65\x64Id\x18\x01 \x01(\x0b\x32\x12.iotics.api.FeedIDR\x06\x66\x65\x65\x64Id\x12\x1c\n\tstoreLast\x18\x03 \x01(\x08R\tstoreLast\x12\x34\n\nproperties\x18\x04 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x1as\n\x0cInputDetails\x12-\n\x07inputId\x18\x01 \x01(\x0b\x32\x13.iotics.api.InputIDR\x07inputId\x12\x34\n\nproperties\x18\x04 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x1a\x97\x03\n\x0bTwinDetails\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x33\n\x08location\x18\x02 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x34\n\nproperties\x18\x05 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12<\n\x05\x66\x65\x65\x64s\x18\n \x03(\x0b\x32&.iotics.api.SearchResponse.FeedDetailsR\x05\x66\x65\x65\x64s\x12?\n\x06inputs\x18\x0b \x03(\x0b\x32\'.iotics.api.SearchResponse.InputDetailsR\x06inputs\x12\x38\n\tcreatedAt\x18\x0c \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tcreatedAt\x12\x38\n\tupdatedAt\x18\r \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tupdatedAt\x1a\xc9\x01\n\x07Payload\x12<\n\x0cresponseType\x18\x01 \x01(\x0e\x32\x18.iotics.api.ResponseTypeR\x0cresponseType\x12*\n\x06status\x18\x02 \x01(\x0b\x32\x12.google.rpc.StatusR\x06status\x12\x16\n\x06hostId\x18\x03 \x01(\tR\x06hostId\x12<\n\x05twins\x18\n \x03(\x0b\x32&.iotics.api.SearchResponse.TwinDetailsR\x05twins\"\x18\n\x16\x44ispatchSearchResponse*2\n\x0cResponseType\x12\x08\n\x04\x46ULL\x10\x00\x12\x0b\n\x07LOCATED\x10\x01\x12\x0b\n\x07MINIMAL\x10\x02\x32\xe8\x02\n\tSearchAPI\x12X\n\x15\x44ispatchSearchRequest\x12\x19.iotics.api.SearchRequest\x1a\".iotics.api.DispatchSearchResponse\"\x00\x12N\n\x11SynchronousSearch\x12\x19.iotics.api.SearchRequest\x1a\x1a.iotics.api.SearchResponse\"\x00\x30\x01\x12\\\n\x19ReceiveAllSearchResponses\x12\x1f.iotics.api.SubscriptionHeaders\x1a\x1a.iotics.api.SearchResponse\"\x00\x30\x01\x12S\n\x0e\x41\x64vancedSearch\x12!.iotics.api.AdvancedSearchRequest\x1a\x1a.iotics.api.SearchResponse\"\x00\x30\x01\x42\x7f\n\x0e\x63om.iotics.apiB\x0bSearchProtoP\x01Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\xa2\x02\x03IAX\xaa\x02\nIotics.Api\xca\x02\nIotics\\Apib\x06proto3')
 
 _builder.BuildMessageAndEnumDescriptors(DESCRIPTOR, globals())
 _builder.BuildTopDescriptorsAndMessages(DESCRIPTOR, 'iotics.api.search_pb2', globals())
 if _descriptor._USE_C_DESCRIPTORS == False:
 
   DESCRIPTOR._options = None
   DESCRIPTOR._serialized_options = b'\n\016com.iotics.apiB\013SearchProtoP\001Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\242\002\003IAX\252\002\nIotics.Api\312\002\nIotics\\Api'
-  _RESPONSETYPE._serialized_start=2237
-  _RESPONSETYPE._serialized_end=2287
+  _RESPONSETYPE._serialized_start=2181
+  _RESPONSETYPE._serialized_end=2231
   _SEARCHREQUEST._serialized_start=202
   _SEARCHREQUEST._serialized_end=829
   _SEARCHREQUEST_PAYLOAD._serialized_start=460
   _SEARCHREQUEST_PAYLOAD._serialized_end=829
   _SEARCHREQUEST_PAYLOAD_FILTER._serialized_start=666
   _SEARCHREQUEST_PAYLOAD_FILTER._serialized_end=829
   _ADVANCEDSEARCHREQUEST._serialized_start=832
   _ADVANCEDSEARCHREQUEST._serialized_end=1150
   _ADVANCEDSEARCHREQUEST_PAYLOAD._serialized_start=1055
   _ADVANCEDSEARCHREQUEST_PAYLOAD._serialized_end=1150
   _SEARCHRESPONSE._serialized_start=1153
-  _SEARCHRESPONSE._serialized_end=2209
+  _SEARCHRESPONSE._serialized_end=2153
   _SEARCHRESPONSE_FEEDDETAILS._serialized_start=1281
   _SEARCHRESPONSE_FEEDDETAILS._serialized_end=1422
   _SEARCHRESPONSE_INPUTDETAILS._serialized_start=1424
   _SEARCHRESPONSE_INPUTDETAILS._serialized_end=1539
   _SEARCHRESPONSE_TWINDETAILS._serialized_start=1542
-  _SEARCHRESPONSE_TWINDETAILS._serialized_end=2005
-  _SEARCHRESPONSE_PAYLOAD._serialized_start=2008
-  _SEARCHRESPONSE_PAYLOAD._serialized_end=2209
-  _DISPATCHSEARCHRESPONSE._serialized_start=2211
-  _DISPATCHSEARCHRESPONSE._serialized_end=2235
-  _SEARCHAPI._serialized_start=2290
-  _SEARCHAPI._serialized_end=2650
+  _SEARCHRESPONSE_TWINDETAILS._serialized_end=1949
+  _SEARCHRESPONSE_PAYLOAD._serialized_start=1952
+  _SEARCHRESPONSE_PAYLOAD._serialized_end=2153
+  _DISPATCHSEARCHRESPONSE._serialized_start=2155
+  _DISPATCHSEARCHRESPONSE._serialized_end=2179
+  _SEARCHAPI._serialized_start=2234
+  _SEARCHAPI._serialized_end=2594
 # @@protoc_insertion_point(module_scope)
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/search_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/search_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/twin_pb2.py` & `iotics-grpc-client-4.0.0/src/iotics/api/twin_pb2.py`

 * *Files 14% similar despite different names*

```diff
@@ -13,78 +13,76 @@
 
 from google.protobuf import timestamp_pb2 as google_dot_protobuf_dot_timestamp__pb2
 from iotics.api import common_pb2 as iotics_dot_api_dot_common__pb2
 from iotics.api import feed_pb2 as iotics_dot_api_dot_feed__pb2
 from iotics.api import input_pb2 as iotics_dot_api_dot_input__pb2
 
 
-DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x15iotics/api/twin.proto\x12\niotics.api\x1a\x1fgoogle/protobuf/timestamp.proto\x1a\x17iotics/api/common.proto\x1a\x15iotics/api/feed.proto\x1a\x16iotics/api/input.proto\"m\n\x13ListAllTwinsRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\'\n\x05range\x18\x14 \x01(\x0b\x32\x11.iotics.api.RangeR\x05range\"\xab\x04\n\x14ListAllTwinsResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\x42\n\x07payload\x18\x02 \x01(\x0b\x32(.iotics.api.ListAllTwinsResponse.PayloadR\x07payload\x1a\xd0\x02\n\x0bTwinDetails\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x36\n\nvisibility\x18\x02 \x01(\x0e\x32\x16.iotics.api.VisibilityR\nvisibility\x12\x33\n\x08location\x18\x03 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x34\n\nproperties\x18\x05 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12\x38\n\tcreatedAt\x18\x06 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tcreatedAt\x12\x38\n\tupdatedAt\x18\x07 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tupdatedAt\x1aM\n\x07Payload\x12\x42\n\x05twins\x18\x01 \x03(\x0b\x32,.iotics.api.ListAllTwinsResponse.TwinDetailsR\x05twins\"\x9e\x01\n\x11\x43reateTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12?\n\x07payload\x18\x02 \x01(\x0b\x32%.iotics.api.CreateTwinRequest.PayloadR\x07payload\x1a\x19\n\x07Payload\x12\x0e\n\x02id\x18\x01 \x01(\tR\x02id\"\xbc\x01\n\x12\x43reateTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.CreateTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xb8\x01\n\x11\x44\x65leteTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12;\n\x04\x61rgs\x18\x02 \x01(\x0b\x32\'.iotics.api.DeleteTwinRequest.ArgumentsR\x04\x61rgs\x1a\x37\n\tArguments\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xbc\x01\n\x12\x44\x65leteTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.DeleteTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xbc\x01\n\x13\x44\x65scribeTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12=\n\x04\x61rgs\x18\x03 \x01(\x0b\x32).iotics.api.DescribeTwinRequest.ArgumentsR\x04\x61rgs\x1a\x37\n\tArguments\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"T\n\x08\x46\x65\x65\x64Meta\x12*\n\x06\x66\x65\x65\x64Id\x18\x01 \x01(\x0b\x32\x12.iotics.api.FeedIDR\x06\x66\x65\x65\x64Id\x12\x1c\n\tstoreLast\x18\x03 \x01(\x08R\tstoreLast\":\n\tInputMeta\x12-\n\x07inputId\x18\x01 \x01(\x0b\x32\x13.iotics.api.InputIDR\x07inputId\"\x86\x05\n\x14\x44\x65scribeTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\x42\n\x07payload\x18\x02 \x01(\x0b\x32(.iotics.api.DescribeTwinResponse.PayloadR\x07payload\x1a\xfe\x02\n\nMetaResult\x12\x33\n\x08location\x18\x01 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x36\n\nvisibility\x18\x02 \x01(\x0e\x32\x16.iotics.api.VisibilityR\nvisibility\x12*\n\x05\x66\x65\x65\x64s\x18\x04 \x03(\x0b\x32\x14.iotics.api.FeedMetaR\x05\x66\x65\x65\x64s\x12-\n\x06inputs\x18\x05 \x03(\x0b\x32\x15.iotics.api.InputMetaR\x06inputs\x12\x34\n\nproperties\x18\x06 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12\x38\n\tcreatedAt\x18\x07 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tcreatedAt\x12\x38\n\tupdatedAt\x18\x08 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tupdatedAt\x1az\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x43\n\x06result\x18\x02 \x01(\x0b\x32+.iotics.api.DescribeTwinResponse.MetaResultR\x06result\"J\n\x10VisibilityUpdate\x12\x36\n\nvisibility\x18\x01 \x01(\x0e\x32\x16.iotics.api.VisibilityR\nvisibility\"H\n\x11GeoLocationUpdate\x12\x33\n\x08location\x18\x01 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\"\xc0\x03\n\x11UpdateTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12;\n\x04\x61rgs\x18\x02 \x01(\x0b\x32\'.iotics.api.UpdateTwinRequest.ArgumentsR\x04\x61rgs\x12?\n\x07payload\x18\x03 \x01(\x0b\x32%.iotics.api.UpdateTwinRequest.PayloadR\x07payload\x1a\x37\n\tArguments\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x1a\xc4\x01\n\x07Payload\x12\x42\n\rnewVisibility\x18\x02 \x01(\x0b\x32\x1c.iotics.api.VisibilityUpdateR\rnewVisibility\x12:\n\nproperties\x18\x03 \x01(\x0b\x32\x1a.iotics.api.PropertyUpdateR\nproperties\x12\x39\n\x08location\x18\x06 \x01(\x0b\x32\x1d.iotics.api.GeoLocationUpdateR\x08location\"\xbc\x01\n\x12UpdateTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.UpdateTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xcd\x03\n\x11UpsertTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12?\n\x07payload\x18\x02 \x01(\x0b\x32%.iotics.api.UpsertTwinRequest.PayloadR\x07payload\x1a\xc7\x02\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x36\n\nvisibility\x18\x02 \x01(\x0e\x32\x16.iotics.api.VisibilityR\nvisibility\x12\x34\n\nproperties\x18\x05 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12\x33\n\x08location\x18\x06 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x34\n\x05\x66\x65\x65\x64s\x18\x07 \x03(\x0b\x32\x1e.iotics.api.UpsertFeedWithMetaR\x05\x66\x65\x65\x64s\x12\x37\n\x06inputs\x18\x08 \x03(\x0b\x32\x1f.iotics.api.UpsertInputWithMetaR\x06inputs\"\xbc\x01\n\x12UpsertTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.UpsertTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId2\xef\x03\n\x07TwinAPI\x12M\n\nCreateTwin\x12\x1d.iotics.api.CreateTwinRequest\x1a\x1e.iotics.api.CreateTwinResponse\"\x00\x12M\n\nUpsertTwin\x12\x1d.iotics.api.UpsertTwinRequest\x1a\x1e.iotics.api.UpsertTwinResponse\"\x00\x12M\n\nDeleteTwin\x12\x1d.iotics.api.DeleteTwinRequest\x1a\x1e.iotics.api.DeleteTwinResponse\"\x00\x12M\n\nUpdateTwin\x12\x1d.iotics.api.UpdateTwinRequest\x1a\x1e.iotics.api.UpdateTwinResponse\"\x00\x12S\n\x0c\x44\x65scribeTwin\x12\x1f.iotics.api.DescribeTwinRequest\x1a .iotics.api.DescribeTwinResponse\"\x00\x12S\n\x0cListAllTwins\x12\x1f.iotics.api.ListAllTwinsRequest\x1a .iotics.api.ListAllTwinsResponse\"\x00\x42}\n\x0e\x63om.iotics.apiB\tTwinProtoP\x01Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\xa2\x02\x03IAX\xaa\x02\nIotics.Api\xca\x02\nIotics\\Apib\x06proto3')
+DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n\x15iotics/api/twin.proto\x12\niotics.api\x1a\x1fgoogle/protobuf/timestamp.proto\x1a\x17iotics/api/common.proto\x1a\x15iotics/api/feed.proto\x1a\x16iotics/api/input.proto\"m\n\x13ListAllTwinsRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\'\n\x05range\x18\x14 \x01(\x0b\x32\x11.iotics.api.RangeR\x05range\"\xf3\x03\n\x14ListAllTwinsResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\x42\n\x07payload\x18\x02 \x01(\x0b\x32(.iotics.api.ListAllTwinsResponse.PayloadR\x07payload\x1a\x98\x02\n\x0bTwinDetails\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x33\n\x08location\x18\x03 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x34\n\nproperties\x18\x05 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12\x38\n\tcreatedAt\x18\x06 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tcreatedAt\x12\x38\n\tupdatedAt\x18\x07 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tupdatedAt\x1aM\n\x07Payload\x12\x42\n\x05twins\x18\x01 \x03(\x0b\x32,.iotics.api.ListAllTwinsResponse.TwinDetailsR\x05twins\"\x9e\x01\n\x11\x43reateTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12?\n\x07payload\x18\x02 \x01(\x0b\x32%.iotics.api.CreateTwinRequest.PayloadR\x07payload\x1a\x19\n\x07Payload\x12\x0e\n\x02id\x18\x01 \x01(\tR\x02id\"\xbc\x01\n\x12\x43reateTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.CreateTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xb8\x01\n\x11\x44\x65leteTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12;\n\x04\x61rgs\x18\x02 \x01(\x0b\x32\'.iotics.api.DeleteTwinRequest.ArgumentsR\x04\x61rgs\x1a\x37\n\tArguments\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xbc\x01\n\x12\x44\x65leteTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.DeleteTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\xbc\x01\n\x13\x44\x65scribeTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12=\n\x04\x61rgs\x18\x03 \x01(\x0b\x32).iotics.api.DescribeTwinRequest.ArgumentsR\x04\x61rgs\x1a\x37\n\tArguments\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"T\n\x08\x46\x65\x65\x64Meta\x12*\n\x06\x66\x65\x65\x64Id\x18\x01 \x01(\x0b\x32\x12.iotics.api.FeedIDR\x06\x66\x65\x65\x64Id\x12\x1c\n\tstoreLast\x18\x03 \x01(\x08R\tstoreLast\":\n\tInputMeta\x12-\n\x07inputId\x18\x01 \x01(\x0b\x32\x13.iotics.api.InputIDR\x07inputId\"\xce\x04\n\x14\x44\x65scribeTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12\x42\n\x07payload\x18\x02 \x01(\x0b\x32(.iotics.api.DescribeTwinResponse.PayloadR\x07payload\x1a\xc6\x02\n\nMetaResult\x12\x33\n\x08location\x18\x01 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12*\n\x05\x66\x65\x65\x64s\x18\x04 \x03(\x0b\x32\x14.iotics.api.FeedMetaR\x05\x66\x65\x65\x64s\x12-\n\x06inputs\x18\x05 \x03(\x0b\x32\x15.iotics.api.InputMetaR\x06inputs\x12\x34\n\nproperties\x18\x06 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12\x38\n\tcreatedAt\x18\x07 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tcreatedAt\x12\x38\n\tupdatedAt\x18\x08 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\tupdatedAt\x1az\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x43\n\x06result\x18\x02 \x01(\x0b\x32+.iotics.api.DescribeTwinResponse.MetaResultR\x06result\"H\n\x11GeoLocationUpdate\x12\x33\n\x08location\x18\x01 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\"\xfc\x02\n\x11UpdateTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12;\n\x04\x61rgs\x18\x02 \x01(\x0b\x32\'.iotics.api.UpdateTwinRequest.ArgumentsR\x04\x61rgs\x12?\n\x07payload\x18\x03 \x01(\x0b\x32%.iotics.api.UpdateTwinRequest.PayloadR\x07payload\x1a\x37\n\tArguments\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x1a\x80\x01\n\x07Payload\x12:\n\nproperties\x18\x03 \x01(\x0b\x32\x1a.iotics.api.PropertyUpdateR\nproperties\x12\x39\n\x08location\x18\x06 \x01(\x0b\x32\x1d.iotics.api.GeoLocationUpdateR\x08location\"\xbc\x01\n\x12UpdateTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.UpdateTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\"\x95\x03\n\x11UpsertTwinRequest\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12?\n\x07payload\x18\x02 \x01(\x0b\x32%.iotics.api.UpsertTwinRequest.PayloadR\x07payload\x1a\x8f\x02\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId\x12\x34\n\nproperties\x18\x05 \x03(\x0b\x32\x14.iotics.api.PropertyR\nproperties\x12\x33\n\x08location\x18\x06 \x01(\x0b\x32\x17.iotics.api.GeoLocationR\x08location\x12\x34\n\x05\x66\x65\x65\x64s\x18\x07 \x03(\x0b\x32\x1e.iotics.api.UpsertFeedWithMetaR\x05\x66\x65\x65\x64s\x12\x37\n\x06inputs\x18\x08 \x03(\x0b\x32\x1f.iotics.api.UpsertInputWithMetaR\x06inputs\"\xbc\x01\n\x12UpsertTwinResponse\x12-\n\x07headers\x18\x01 \x01(\x0b\x32\x13.iotics.api.HeadersR\x07headers\x12@\n\x07payload\x18\x02 \x01(\x0b\x32&.iotics.api.UpsertTwinResponse.PayloadR\x07payload\x1a\x35\n\x07Payload\x12*\n\x06twinId\x18\x01 \x01(\x0b\x32\x12.iotics.api.TwinIDR\x06twinId2\xef\x03\n\x07TwinAPI\x12M\n\nCreateTwin\x12\x1d.iotics.api.CreateTwinRequest\x1a\x1e.iotics.api.CreateTwinResponse\"\x00\x12M\n\nUpsertTwin\x12\x1d.iotics.api.UpsertTwinRequest\x1a\x1e.iotics.api.UpsertTwinResponse\"\x00\x12M\n\nDeleteTwin\x12\x1d.iotics.api.DeleteTwinRequest\x1a\x1e.iotics.api.DeleteTwinResponse\"\x00\x12M\n\nUpdateTwin\x12\x1d.iotics.api.UpdateTwinRequest\x1a\x1e.iotics.api.UpdateTwinResponse\"\x00\x12S\n\x0c\x44\x65scribeTwin\x12\x1f.iotics.api.DescribeTwinRequest\x1a .iotics.api.DescribeTwinResponse\"\x00\x12S\n\x0cListAllTwins\x12\x1f.iotics.api.ListAllTwinsRequest\x1a .iotics.api.ListAllTwinsResponse\"\x00\x42}\n\x0e\x63om.iotics.apiB\tTwinProtoP\x01Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\xa2\x02\x03IAX\xaa\x02\nIotics.Api\xca\x02\nIotics\\Apib\x06proto3')
 
 _builder.BuildMessageAndEnumDescriptors(DESCRIPTOR, globals())
 _builder.BuildTopDescriptorsAndMessages(DESCRIPTOR, 'iotics.api.twin_pb2', globals())
 if _descriptor._USE_C_DESCRIPTORS == False:
 
   DESCRIPTOR._options = None
   DESCRIPTOR._serialized_options = b'\n\016com.iotics.apiB\tTwinProtoP\001Z>github.com/Iotic-Labs/iotic-go-proto-qapi/iotics/api;ioticsapi\242\002\003IAX\252\002\nIotics.Api\312\002\nIotics\\Api'
   _LISTALLTWINSREQUEST._serialized_start=142
   _LISTALLTWINSREQUEST._serialized_end=251
   _LISTALLTWINSRESPONSE._serialized_start=254
-  _LISTALLTWINSRESPONSE._serialized_end=809
+  _LISTALLTWINSRESPONSE._serialized_end=753
   _LISTALLTWINSRESPONSE_TWINDETAILS._serialized_start=394
-  _LISTALLTWINSRESPONSE_TWINDETAILS._serialized_end=730
-  _LISTALLTWINSRESPONSE_PAYLOAD._serialized_start=732
-  _LISTALLTWINSRESPONSE_PAYLOAD._serialized_end=809
-  _CREATETWINREQUEST._serialized_start=812
-  _CREATETWINREQUEST._serialized_end=970
-  _CREATETWINREQUEST_PAYLOAD._serialized_start=945
-  _CREATETWINREQUEST_PAYLOAD._serialized_end=970
-  _CREATETWINRESPONSE._serialized_start=973
-  _CREATETWINRESPONSE._serialized_end=1161
-  _CREATETWINRESPONSE_PAYLOAD._serialized_start=1108
-  _CREATETWINRESPONSE_PAYLOAD._serialized_end=1161
-  _DELETETWINREQUEST._serialized_start=1164
-  _DELETETWINREQUEST._serialized_end=1348
-  _DELETETWINREQUEST_ARGUMENTS._serialized_start=1293
-  _DELETETWINREQUEST_ARGUMENTS._serialized_end=1348
-  _DELETETWINRESPONSE._serialized_start=1351
-  _DELETETWINRESPONSE._serialized_end=1539
-  _DELETETWINRESPONSE_PAYLOAD._serialized_start=1108
-  _DELETETWINRESPONSE_PAYLOAD._serialized_end=1161
-  _DESCRIBETWINREQUEST._serialized_start=1542
-  _DESCRIBETWINREQUEST._serialized_end=1730
-  _DESCRIBETWINREQUEST_ARGUMENTS._serialized_start=1293
-  _DESCRIBETWINREQUEST_ARGUMENTS._serialized_end=1348
-  _FEEDMETA._serialized_start=1732
-  _FEEDMETA._serialized_end=1816
-  _INPUTMETA._serialized_start=1818
-  _INPUTMETA._serialized_end=1876
-  _DESCRIBETWINRESPONSE._serialized_start=1879
-  _DESCRIBETWINRESPONSE._serialized_end=2525
-  _DESCRIBETWINRESPONSE_METARESULT._serialized_start=2019
-  _DESCRIBETWINRESPONSE_METARESULT._serialized_end=2401
-  _DESCRIBETWINRESPONSE_PAYLOAD._serialized_start=2403
-  _DESCRIBETWINRESPONSE_PAYLOAD._serialized_end=2525
-  _VISIBILITYUPDATE._serialized_start=2527
-  _VISIBILITYUPDATE._serialized_end=2601
-  _GEOLOCATIONUPDATE._serialized_start=2603
-  _GEOLOCATIONUPDATE._serialized_end=2675
-  _UPDATETWINREQUEST._serialized_start=2678
-  _UPDATETWINREQUEST._serialized_end=3126
-  _UPDATETWINREQUEST_ARGUMENTS._serialized_start=1293
-  _UPDATETWINREQUEST_ARGUMENTS._serialized_end=1348
-  _UPDATETWINREQUEST_PAYLOAD._serialized_start=2930
-  _UPDATETWINREQUEST_PAYLOAD._serialized_end=3126
-  _UPDATETWINRESPONSE._serialized_start=3129
-  _UPDATETWINRESPONSE._serialized_end=3317
-  _UPDATETWINRESPONSE_PAYLOAD._serialized_start=1108
-  _UPDATETWINRESPONSE_PAYLOAD._serialized_end=1161
-  _UPSERTTWINREQUEST._serialized_start=3320
-  _UPSERTTWINREQUEST._serialized_end=3781
-  _UPSERTTWINREQUEST_PAYLOAD._serialized_start=3454
-  _UPSERTTWINREQUEST_PAYLOAD._serialized_end=3781
-  _UPSERTTWINRESPONSE._serialized_start=3784
-  _UPSERTTWINRESPONSE._serialized_end=3972
-  _UPSERTTWINRESPONSE_PAYLOAD._serialized_start=1108
-  _UPSERTTWINRESPONSE_PAYLOAD._serialized_end=1161
-  _TWINAPI._serialized_start=3975
-  _TWINAPI._serialized_end=4470
+  _LISTALLTWINSRESPONSE_TWINDETAILS._serialized_end=674
+  _LISTALLTWINSRESPONSE_PAYLOAD._serialized_start=676
+  _LISTALLTWINSRESPONSE_PAYLOAD._serialized_end=753
+  _CREATETWINREQUEST._serialized_start=756
+  _CREATETWINREQUEST._serialized_end=914
+  _CREATETWINREQUEST_PAYLOAD._serialized_start=889
+  _CREATETWINREQUEST_PAYLOAD._serialized_end=914
+  _CREATETWINRESPONSE._serialized_start=917
+  _CREATETWINRESPONSE._serialized_end=1105
+  _CREATETWINRESPONSE_PAYLOAD._serialized_start=1052
+  _CREATETWINRESPONSE_PAYLOAD._serialized_end=1105
+  _DELETETWINREQUEST._serialized_start=1108
+  _DELETETWINREQUEST._serialized_end=1292
+  _DELETETWINREQUEST_ARGUMENTS._serialized_start=1237
+  _DELETETWINREQUEST_ARGUMENTS._serialized_end=1292
+  _DELETETWINRESPONSE._serialized_start=1295
+  _DELETETWINRESPONSE._serialized_end=1483
+  _DELETETWINRESPONSE_PAYLOAD._serialized_start=1052
+  _DELETETWINRESPONSE_PAYLOAD._serialized_end=1105
+  _DESCRIBETWINREQUEST._serialized_start=1486
+  _DESCRIBETWINREQUEST._serialized_end=1674
+  _DESCRIBETWINREQUEST_ARGUMENTS._serialized_start=1237
+  _DESCRIBETWINREQUEST_ARGUMENTS._serialized_end=1292
+  _FEEDMETA._serialized_start=1676
+  _FEEDMETA._serialized_end=1760
+  _INPUTMETA._serialized_start=1762
+  _INPUTMETA._serialized_end=1820
+  _DESCRIBETWINRESPONSE._serialized_start=1823
+  _DESCRIBETWINRESPONSE._serialized_end=2413
+  _DESCRIBETWINRESPONSE_METARESULT._serialized_start=1963
+  _DESCRIBETWINRESPONSE_METARESULT._serialized_end=2289
+  _DESCRIBETWINRESPONSE_PAYLOAD._serialized_start=2291
+  _DESCRIBETWINRESPONSE_PAYLOAD._serialized_end=2413
+  _GEOLOCATIONUPDATE._serialized_start=2415
+  _GEOLOCATIONUPDATE._serialized_end=2487
+  _UPDATETWINREQUEST._serialized_start=2490
+  _UPDATETWINREQUEST._serialized_end=2870
+  _UPDATETWINREQUEST_ARGUMENTS._serialized_start=1237
+  _UPDATETWINREQUEST_ARGUMENTS._serialized_end=1292
+  _UPDATETWINREQUEST_PAYLOAD._serialized_start=2742
+  _UPDATETWINREQUEST_PAYLOAD._serialized_end=2870
+  _UPDATETWINRESPONSE._serialized_start=2873
+  _UPDATETWINRESPONSE._serialized_end=3061
+  _UPDATETWINRESPONSE_PAYLOAD._serialized_start=1052
+  _UPDATETWINRESPONSE_PAYLOAD._serialized_end=1105
+  _UPSERTTWINREQUEST._serialized_start=3064
+  _UPSERTTWINREQUEST._serialized_end=3469
+  _UPSERTTWINREQUEST_PAYLOAD._serialized_start=3198
+  _UPSERTTWINREQUEST_PAYLOAD._serialized_end=3469
+  _UPSERTTWINRESPONSE._serialized_start=3472
+  _UPSERTTWINRESPONSE._serialized_end=3660
+  _UPSERTTWINRESPONSE_PAYLOAD._serialized_start=1052
+  _UPSERTTWINRESPONSE_PAYLOAD._serialized_end=1105
+  _TWINAPI._serialized_start=3663
+  _TWINAPI._serialized_end=4158
 # @@protoc_insertion_point(module_scope)
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/api/twin_pb2_grpc.py` & `iotics-grpc-client-4.0.0/src/iotics/api/twin_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/__init__.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/__init__.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/__init__.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -8,15 +8,15 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
-from iotics.api.common_pb2 import Scope, Visibility
+from iotics.api.common_pb2 import Scope
 from iotics.api.feed_pb2 import CreateFeedResponse, DeleteFeedResponse, DescribeFeedResponse, ListAllFeedsResponse, \
     ShareFeedDataResponse, UpdateFeedResponse
 from iotics.api.interest_pb2 import FetchInterestResponse
 from iotics.api.search_pb2 import SearchRequest, SearchResponse
 from iotics.api.meta_pb2 import SparqlQueryResponse, SparqlResultType, SparqlUpdateResponse
 from iotics.api.twin_pb2 import CreateTwinResponse, DeleteTwinResponse, DescribeTwinResponse, ListAllTwinsResponse, \
     UpdateTwinResponse, UpsertTwinResponse
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/auth.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/auth.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/base.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/base.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/feeds.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/feeds.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/helpers.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/helpers.py`

 * *Files 4% similar despite different names*

```diff
@@ -113,22 +113,35 @@
     key='http://www.w3.org/1999/02/22-rdf-syntax-ns#type',
     uriValue=Uri(value='https://data.iotics.com/app#Model')
 )
 PROPERTY_CREATED_BY_MODEL = Property(
     key='http://data.iotics.com/app#CreationMeans',
     uriValue=Uri(value='http://data.iotics.com/app#ByModel')
 )
+
+# whether or not twins can be found from other spaces
+METADATA_ALLOW_ALL = Property(
+    key='http://data.iotics.com/public#hostMetadataAllowList',
+    uriValue=Uri(value='http://data.iotics.com/public#all')
+)
+METADATA_ALLOW_NONE = Property(
+    key='http://data.iotics.com/public#hostMetadataAllowList',
+    uriValue=Uri(value='http://data.iotics.com/public#none')
+)
+
+# whether or not twins feeds can be followed from other spaces
 PROPERTY_ALLOW_ALL = Property(
     key='http://data.iotics.com/public#hostAllowList',
     uriValue=Uri(value='http://data.iotics.com/public#all')
 )
 PROPERTY_ALLOW_NONE = Property(
     key='http://data.iotics.com/public#hostAllowList',
     uriValue=Uri(value='http://data.iotics.com/public#none')
 )
+
 PROPERTY_KEY_HAS_MODEL = 'https://data.iotics.com/app#model'
 PROPERTY_KEY_COLOR = 'https://data.iotics.com/app#color'
 PROPERTY_KEY_CREATED_AT = 'https://data.iotics.com/app#createdAt'
 PROPERTY_KEY_CREATED_BY = 'https://data.iotics.com/app#createdBy'
 PROPERTY_KEY_UPDATED_AT = 'https://data.iotics.com/app#updatedAt'
 PROPERTY_KEY_UPDATED_BY = 'https://data.iotics.com/app#updatedBy'
 PROPERTY_KEY_LABEL = "http://www.w3.org/2000/01/rdf-schema#label"
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/host.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/host.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/input.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/input.py`

 * *Files 2% similar despite different names*

```diff
@@ -89,78 +89,78 @@
             )
         )
         return self.stub.UpdateInput(req)
 
 
     def describe_input(
         self,
-        twin_id: str,
+        twin_did: str,
         input_id: str,
         remote_host_id: typing.Optional[str] = None,
         headers: typing.Optional[common_pb2.Headers] = None,
     ) -> input_pb2.DescribeInputResponse:
         """Describes an input (local and remote).
 
         Args:
-            twin_id: The twin whose input will be described
+            twin_did: The twin whose input will be described
             input_id: The ID of the input to be described
             remote_host_id: The remote host on which the twin is found -- None if twin is local
             headers: optional request headers
 
         Returns: A response object describing the input.
         """
         request = input_pb2.DescribeInputRequest(
             headers=headers or create_headers(),
             args=input_pb2.DescribeInputRequest.Arguments(
-                inputId=InputID(id=input_id, twinId=twin_id, hostId=remote_host_id),
+                inputId=InputID(id=input_id, twinId=twin_did, hostId=remote_host_id),
             )
         )
         return self.stub.DescribeInput(request)
 
     def delete_input(
         self,
-        twin_id: str,
+        twin_did: str,
         input_id: str,
         headers: typing.Optional[common_pb2.Headers] = None,
     ) -> input_pb2.DeleteInputResponse:
         """Deletes an input (idempotent).
 
         Args:
-            twin_id: The twin whose input will be deleted
+            twin_did: The twin whose input will be deleted
             input_id: The ID of the input to be deleted
             headers: optional request headers
 
         Returns: A response object with a payload containing the deleted input.
 
         """
         request = input_pb2.DeleteInputRequest(
             headers=headers or create_headers(),
-            args=input_pb2.DeleteInputRequest.Arguments(inputId=InputID(id=input_id, twinId=twin_id)),
+            args=input_pb2.DeleteInputRequest.Arguments(inputId=InputID(id=input_id, twinId=twin_did)),
         )
         return self.stub.DeleteInput(request)
 
     def receive_input_messages(
             self,
-            twin_id: str,
+            twin_did: str,
             input_id: str,
             timeout: typing.Optional[int] = None,
             headers: typing.Optional[common_pb2.Headers] = None
     ) -> typing.Iterator[input_pb2.ReceiveInputMessageResponse]:
         """Initialises an iterator that listens for input messages for a given Twin ID and Input ID.
 
         Note: This function must be called before `InterestApi.send_input_message` otherwise messages may be lost.
 
         Args:
-            twin_id: The twin offering the input to receive messages on
+            twin_did: The twin offering the input to receive messages on
             input_id: The input that will receive the messages
             timeout: How long before the input stops listening
             headers: optional request headers
 
         Returns: Response iterator with extra blocking (e.g. `time_remaining`) and non-blocking (e.g. `code`) methods.
         """
-        args = input_pb2.ReceiveInputMessageRequest.Arguments(inputId=InputID(id=input_id, twinId=twin_id))
+        args = input_pb2.ReceiveInputMessageRequest.Arguments(inputId=InputID(id=input_id, twinId=twin_did))
         request = input_pb2.ReceiveInputMessageRequest(headers=headers or create_headers(), args=args)
 
         # Define type here to avoid: `TypeError: 'ABCMeta' object is not subscriptable`.
         input_responses: grpc._channel._MultiThreadedRendezvous[input_pb2.ReceiveInputMessageResponse] = \
             self.stub.ReceiveInputMessages(request, timeout=timeout)
         return input_responses
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/interest.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/interest.py`

 * *Files 2% similar despite different names*

```diff
@@ -118,36 +118,36 @@
             )
         )
         return self.stub.FetchLastStored(req)
 
     def send_input_message(
         self,
         message: typing.Any,
-        sender_twin_id: str,
-        receiver_twin_id: str,
+        sender_twin_did: str,
+        receiver_twin_did: str,
         input_id: str,
         remote_host_id: typing.Optional[str] = None,
         headers: typing.Optional[common_pb2.Headers] = None,
     ) -> interest_pb2.SendInputMessageResponse:
         """Sends a message to the input of a local or remote twin.
 
         Args:
             message: What to send the remote twin, usually in the form of a dict with keys matching the input's Values
-            sender_twin_id: The twin sending the message
-            receiver_twin_id: The twin receiving the message
+            sender_twin_did: The twin sending the message
+            receiver_twin_did: The twin receiving the message
             input_id: The ID of the input where the message will be sent
             remote_host_id: If the receiver twin is remote, its host ID (None if local)
             headers: optional request headers
 
         Returns: Response object indicating success
 
         """
         input_interest = interest_pb2.InputInterest(
-            senderTwinId=common_pb2.TwinID(id=sender_twin_id),
-            destInputId=InputID(id=input_id, twinId=receiver_twin_id, hostId=remote_host_id),
+            senderTwinId=common_pb2.TwinID(id=sender_twin_did),
+            destInputId=InputID(id=input_id, twinId=receiver_twin_did, hostId=remote_host_id),
         )
         input_message = input_pb2.InputMessage(
             occurredAt=create_timestamp(),
             mime='application/json',
             data=json.dumps(message).encode(),
         )
         request = interest_pb2.SendInputMessageRequest(
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/iotics_api.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/iotics_api.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/search.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/search.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/sparql.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/sparql.py`

 * *Files identical despite different names*

### Comparing `iotics-grpc-client-3.0.1/src/iotics/lib/grpc/twins.py` & `iotics-grpc-client-4.0.0/src/iotics/lib/grpc/twins.py`

 * *Files 6% similar despite different names*

```diff
@@ -91,76 +91,71 @@
 
     def list_twins(self, headers: typing.Optional[common_pb2.Headers] = None) -> twin_pb2.ListAllTwinsResponse:
         """Lists all local twins visible to the user making the request
 
         Args:
             headers: optional request headers
 
-        Returns: Response object listing twins with their location, visibility, and properties
+        Returns: Response object listing twins with their location and properties
         """
         req = twin_pb2.ListAllTwinsRequest(headers=headers or create_headers())
         return self.stub.ListAllTwins(req)
 
     def update_twin(
             self,
             twin_did: str,
-            visibility: common_pb2.Visibility = None,
             location: typing.Optional[common_pb2.GeoLocation] = None,
             props_added: typing.Optional[list] = None,
             props_deleted: typing.Optional[list] = None,
             props_keys_deleted: typing.Optional[list] = None,
             props_clear_all: bool = False,
             headers: typing.Optional[common_pb2.Headers] = None
     ) -> twin_pb2.UpdateTwinResponse:
-        """Update a twin to have the given visibility, location, and/or properties. Arguments omitted will not have
+        """Update a twin to have the given location, and/or properties. Arguments omitted will not have
         their values updated
         Args:
             twin_did: Decentralized Identifier of the twin to update
-            visibility: The new Visibility for the twin, PUBLIC or PRIVATE
             location: The new GeoLocation for the twin, created from lat/lon values using the create_location helper
             props_added: A list of semantic properties to be added to the twin, created using the create_property helper
             props_deleted: A list of semantic properties to be removed from the twin
             props_keys_deleted: A list of any property keys for which all values should be removed from the twin
             props_clear_all: Whether or not to clear all properties from the twin
             headers: optional request headers
 
         Returns: Response object confirming the ID of the twin that was updated
         """
 
         req = twin_pb2.UpdateTwinRequest(
             headers=headers or create_headers(),
             args=twin_pb2.UpdateTwinRequest.Arguments(twinId=common_pb2.TwinID(id=twin_did)),
             payload=twin_pb2.UpdateTwinRequest.Payload(
-                newVisibility=twin_pb2.VisibilityUpdate(visibility=visibility) if visibility else None,
                 location=twin_pb2.GeoLocationUpdate(location=location) if location else None,
                 properties=common_pb2.PropertyUpdate(
                     added=props_added,
                     deleted=props_deleted,
                     deletedByKey=props_keys_deleted,
                     clearedAll=props_clear_all
                 )
             ))
         return self.stub.UpdateTwin(req)
 
     def upsert_twin(
             self,
             twin_did: str,
-            visibility: common_pb2.Visibility.ValueType = None,
             location: typing.Optional[common_pb2.GeoLocation] = None,
             properties: typing.Optional[typing.Iterable[common_pb2.Property]] = None,
             feeds: typing.Optional[typing.Iterable[feed_pb2.UpsertFeedWithMeta]] = None,
             inputs: typing.Optional[typing.Iterable[input_pb2.UpsertInputWithMeta]] = None,
             headers: typing.Optional[common_pb2.Headers] = None
     ) -> twin_pb2.UpsertTwinResponse:
         """Upserts a twin with the given details, ie, the given ID will specify a twin with these details regardless of
         whether a twin previously existed with this ID. Any arguments omitted will become absent or given default values
 
         Args:
             twin_did: Decentralized Identifier of the twin to upsert
-            visibility: The Visibility for the twin, PUBLIC (default) or PRIVATE
             location: The GeoLocation for the twin, created from lat/lon values using the create_location helper
             properties: A list of semantic properties providing further information about the twin, created using the
                 create_property helper
             feeds: A list of feeds on which the twin may share real-time data, created using the create_feed_with_meta
                 helper
             inputs: A list of inputs on which the twin may receive messages
             headers: optional request headers
@@ -168,15 +163,14 @@
         Returns: Response object confirming the ID of the twin that was upserted
         """
 
         req = twin_pb2.UpsertTwinRequest(
             headers=headers or create_headers(),
             payload=twin_pb2.UpsertTwinRequest.Payload(
                 twinId=common_pb2.TwinID(id=twin_did),
-                visibility=visibility,
                 location=location,
                 properties=properties,
                 feeds=feeds,
                 inputs=inputs,
             )
         )
         return self.stub.UpsertTwin(req)
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/PKG-INFO` & `iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,24 +1,25 @@
 Metadata-Version: 2.1
 Name: iotics-grpc-client
-Version: 3.0.1
+Version: 4.0.0
 Summary: Iotics gRPC client library
 Home-page: https://github.com/Iotic-Labs/iotics-grpc-client-py
 Author: Iotics
 License: UNKNOWN
 Project-URL: Bug Tracker, https://github.com/Iotic-Labs/iotics-grpc-client-py/issues
 Project-URL: Changelog, https://github.com/Iotic-Labs/iotics-grpc-client-py/releases
 Description: # Iotics gRPC Python Client
         A Python library for interacting with Iotics API.
         
         
         ## Usage and Version Compatibility with Iotics host:
         
         | iotics-grpc-client-py | iotics-host |
         |----------------------| ----------- |
+        |      `pip install iotics-grpc-client~=4.0`       | `>= 6`       |
         |      `pip install iotics-grpc-client~=3.0`       | `>= 6`       |
         |      `pip install iotics-grpc-client~=2.0`       | `>= 5`       |
         |      `pip install iotics-grpc-client~=0.10.0`      | `>= 4`     |
         
         
         
         # Examples
@@ -28,15 +29,15 @@
         * __Required__:
           * `SPACE` - Domain name of the IOTICSpace with which to communicate. The scheme can be omitted, eg. examplecorp.
             iotics.space
           * `USER_DID` - Identity of the user
           * `AGENT_DID` - Identity of the agent authorised to operate on the user's behalf
           * `AGENT_KEY_NAME` - __secret__ value used to (re)create multiple key pairs
           * `AGENT_NAME` - registered identity name that can be used to e.g. identify public keys
-          * `AGENT SECRET` - __secret__ value, the agent's private key
+          * `AGENT_SECRET` - __secret__ value, the agent's private key
         
         * __Optional__:
           * `DID_RESOLVER_URL` - Where the database of identity documents is accessible, defaults to the one used by the given 
             space.
           * `TOKEN_TTL` - How long in seconds auth tokens will last if not specified in the method call, defaults to 30
         ## Running example scripts
         Next, create and activate your virtual environment and run any of the scripts in the [examples](https://github.com/Iotic-Labs/iotics-grpc-client-py/tree/main/examples) directory,
```

### Comparing `iotics-grpc-client-3.0.1/src/iotics_grpc_client.egg-info/SOURCES.txt` & `iotics-grpc-client-4.0.0/src/iotics_grpc_client.egg-info/SOURCES.txt`

 * *Files identical despite different names*


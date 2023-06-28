# Comparing `tmp/kuksa_client-0.4.0a3.tar.gz` & `tmp/kuksa_client-0.4.0a4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kuksa_client-0.4.0a3.tar", last modified: Thu Jun 22 08:59:30 2023, max compression
+gzip compressed data, was "kuksa_client-0.4.0a4.tar", last modified: Wed Jun 28 08:56:56 2023, max compression
```

## Comparing `kuksa_client-0.4.0a3.tar` & `kuksa_client-0.4.0a4.tar`

### file list

```diff
@@ -1,65 +1,65 @@
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.666995 kuksa_client-0.4.0a3/
--rw-r--r--   0 erik      (1000) erik      (1000)       35 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/MANIFEST.in
--rw-r--r--   0 erik      (1000) erik      (1000)    13241 2023-06-22 08:59:30.666995 kuksa_client-0.4.0a3/PKG-INFO
--rw-r--r--   0 erik      (1000) erik      (1000)    12381 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/README.md
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.655000 kuksa_client-0.4.0a3/kuksa/
--rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa/__init__.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.655000 kuksa_client-0.4.0a3/kuksa/val/
--rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa/val/__init__.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.655000 kuksa_client-0.4.0a3/kuksa/val/v1/
--rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa/val/v1/__init__.py
--rw-r--r--   0 erik      (1000) erik      (1000)     9374 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa/val/v1/types_pb2.py
--rw-r--r--   0 erik      (1000) erik      (1000)      159 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa/val/v1/types_pb2_grpc.py
--rw-r--r--   0 erik      (1000) erik      (1000)     3751 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa/val/v1/val_pb2.py
--rw-r--r--   0 erik      (1000) erik      (1000)     8731 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa/val/v1/val_pb2_grpc.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.658999 kuksa_client-0.4.0a3/kuksa_certificates/
--rw-r--r--   0 erik      (1000) erik      (1000)     1675 2022-09-02 12:03:09.000000 kuksa_client-0.4.0a3/kuksa_certificates/CA.key
--rw-r--r--   0 erik      (1000) erik      (1000)     1342 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_certificates/CA.pem
--rw-r--r--   0 erik      (1000) erik      (1000)     1679 2022-09-02 12:03:09.000000 kuksa_client-0.4.0a3/kuksa_certificates/Client.key
--rw-r--r--   0 erik      (1000) erik      (1000)     1704 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_certificates/Client.pem
--rw-r--r--   0 erik      (1000) erik      (1000)     3537 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_certificates/README.md
--rw-r--r--   0 erik      (1000) erik      (1000)     1679 2022-09-02 12:03:09.000000 kuksa_client-0.4.0a3/kuksa_certificates/Server.key
--rw-r--r--   0 erik      (1000) erik      (1000)     1704 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_certificates/Server.pem
--rw-r--r--   0 erik      (1000) erik      (1000)      114 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_certificates/__init__.py
--rwxr-xr-x   0 erik      (1000) erik      (1000)     2023 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_certificates/genCerts.sh
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.662997 kuksa_client-0.4.0a3/kuksa_certificates/jwt/
--rw-r--r--   0 erik      (1000) erik      (1000)      151 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/all-read-write.json
--rw-r--r--   0 erik      (1000) erik      (1000)      875 2022-11-01 08:41:15.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/all-read-write.json.token
--rwxr-xr-x   0 erik      (1000) erik      (1000)     1430 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/createToken.py
--rw-r--r--   0 erik      (1000) erik      (1000)     3243 2022-11-01 08:46:13.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/jwt.key
--rw-r--r--   0 erik      (1000) erik      (1000)      800 2022-11-01 08:46:13.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/jwt.key.pub
--rwxr-xr-x   0 erik      (1000) erik      (1000)      901 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/recreateJWTkeyPair.sh
--rw-r--r--   0 erik      (1000) erik      (1000)       34 2023-05-10 08:02:45.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/requirements.txt
--rw-r--r--   0 erik      (1000) erik      (1000)      167 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/single-read.json
--rw-r--r--   0 erik      (1000) erik      (1000)      895 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/single-read.json.token
--rw-r--r--   0 erik      (1000) erik      (1000)      175 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/super-admin.json
--rw-r--r--   0 erik      (1000) erik      (1000)      899 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a3/kuksa_certificates/jwt/super-admin.json.token
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.662997 kuksa_client-0.4.0a3/kuksa_client/
--rw-r--r--   0 erik      (1000) erik      (1000)     3929 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_client/__init__.py
--rwxr-xr-x   0 erik      (1000) erik      (1000)    25603 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_client/__main__.py
--rw-r--r--   0 erik      (1000) erik      (1000)     1708 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_client/_metadata.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.662997 kuksa_client-0.4.0a3/kuksa_client/cli_backend/
--rw-r--r--   0 erik      (1000) erik      (1000)     2259 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_client/cli_backend/__init__.py
--rw-r--r--   0 erik      (1000) erik      (1000)    11695 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_client/cli_backend/grpc.py
--rw-r--r--   0 erik      (1000) erik      (1000)     9892 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_client/cli_backend/ws.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.662997 kuksa_client-0.4.0a3/kuksa_client/grpc/
--rw-r--r--   0 erik      (1000) erik      (1000)    38987 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_client/grpc/__init__.py
--rw-r--r--   0 erik      (1000) erik      (1000)    16627 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/kuksa_client/grpc/aio.py
--rw-r--r--   0 erik      (1000) erik      (1000)      385 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_client/logging.ini
--rw-r--r--   0 erik      (1000) erik      (1000)      605 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_client/logo
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.662997 kuksa_client-0.4.0a3/kuksa_client/ws/
--rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/kuksa_client/ws/__init__.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.662997 kuksa_client-0.4.0a3/kuksa_client.egg-info/
--rw-r--r--   0 erik      (1000) erik      (1000)    13241 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa_client.egg-info/PKG-INFO
--rw-r--r--   0 erik      (1000) erik      (1000)     1534 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa_client.egg-info/SOURCES.txt
--rw-r--r--   0 erik      (1000) erik      (1000)        1 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa_client.egg-info/dependency_links.txt
--rw-r--r--   0 erik      (1000) erik      (1000)       60 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa_client.egg-info/entry_points.txt
--rw-r--r--   0 erik      (1000) erik      (1000)      212 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa_client.egg-info/requires.txt
--rw-r--r--   0 erik      (1000) erik      (1000)       44 2023-06-22 08:59:30.000000 kuksa_client-0.4.0a3/kuksa_client.egg-info/top_level.txt
--rw-r--r--   0 erik      (1000) erik      (1000)      625 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/pyproject.toml
--rw-r--r--   0 erik      (1000) erik      (1000)     1370 2023-06-22 08:59:30.666995 kuksa_client-0.4.0a3/setup.cfg
--rw-r--r--   0 erik      (1000) erik      (1000)     1168 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/setup.py
-drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-22 08:59:30.666995 kuksa_client-0.4.0a3/tests/
--rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/tests/__init__.py
--rw-r--r--   0 erik      (1000) erik      (1000)     2545 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a3/tests/conftest.py
--rw-r--r--   0 erik      (1000) erik      (1000)    63305 2023-06-21 14:42:58.000000 kuksa_client-0.4.0a3/tests/test_grpc.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/
+-rw-r--r--   0 erik      (1000) erik      (1000)       35 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/MANIFEST.in
+-rw-r--r--   0 erik      (1000) erik      (1000)    13411 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/PKG-INFO
+-rw-r--r--   0 erik      (1000) erik      (1000)    12551 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/README.md
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.575442 kuksa_client-0.4.0a4/kuksa/
+-rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa/__init__.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.575442 kuksa_client-0.4.0a4/kuksa/val/
+-rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa/val/__init__.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.575442 kuksa_client-0.4.0a4/kuksa/val/v1/
+-rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa/val/v1/__init__.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     9993 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa/val/v1/types_pb2.py
+-rw-r--r--   0 erik      (1000) erik      (1000)      159 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa/val/v1/types_pb2_grpc.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     4058 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa/val/v1/val_pb2.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     8731 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa/val/v1/val_pb2_grpc.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.579440 kuksa_client-0.4.0a4/kuksa_certificates/
+-rw-r--r--   0 erik      (1000) erik      (1000)     1675 2022-09-02 12:03:09.000000 kuksa_client-0.4.0a4/kuksa_certificates/CA.key
+-rw-r--r--   0 erik      (1000) erik      (1000)     1342 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_certificates/CA.pem
+-rw-r--r--   0 erik      (1000) erik      (1000)     1679 2022-09-02 12:03:09.000000 kuksa_client-0.4.0a4/kuksa_certificates/Client.key
+-rw-r--r--   0 erik      (1000) erik      (1000)     1704 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_certificates/Client.pem
+-rw-r--r--   0 erik      (1000) erik      (1000)     3537 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_certificates/README.md
+-rw-r--r--   0 erik      (1000) erik      (1000)     1679 2022-09-02 12:03:09.000000 kuksa_client-0.4.0a4/kuksa_certificates/Server.key
+-rw-r--r--   0 erik      (1000) erik      (1000)     1704 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_certificates/Server.pem
+-rw-r--r--   0 erik      (1000) erik      (1000)      114 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_certificates/__init__.py
+-rwxr-xr-x   0 erik      (1000) erik      (1000)     2023 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_certificates/genCerts.sh
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.587436 kuksa_client-0.4.0a4/kuksa_certificates/jwt/
+-rw-r--r--   0 erik      (1000) erik      (1000)      151 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/all-read-write.json
+-rw-r--r--   0 erik      (1000) erik      (1000)      875 2022-11-01 08:41:15.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/all-read-write.json.token
+-rwxr-xr-x   0 erik      (1000) erik      (1000)     1430 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/createToken.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     3243 2022-11-01 08:46:13.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/jwt.key
+-rw-r--r--   0 erik      (1000) erik      (1000)      800 2022-11-01 08:46:13.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/jwt.key.pub
+-rwxr-xr-x   0 erik      (1000) erik      (1000)      901 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/recreateJWTkeyPair.sh
+-rw-r--r--   0 erik      (1000) erik      (1000)       34 2023-05-10 08:02:45.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/requirements.txt
+-rw-r--r--   0 erik      (1000) erik      (1000)      167 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/single-read.json
+-rw-r--r--   0 erik      (1000) erik      (1000)      895 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/single-read.json.token
+-rw-r--r--   0 erik      (1000) erik      (1000)      175 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/super-admin.json
+-rw-r--r--   0 erik      (1000) erik      (1000)      899 2022-08-17 12:23:53.000000 kuksa_client-0.4.0a4/kuksa_certificates/jwt/super-admin.json.token
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.587436 kuksa_client-0.4.0a4/kuksa_client/
+-rw-r--r--   0 erik      (1000) erik      (1000)     3929 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_client/__init__.py
+-rwxr-xr-x   0 erik      (1000) erik      (1000)    25603 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_client/__main__.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     1708 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_client/_metadata.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/kuksa_client/cli_backend/
+-rw-r--r--   0 erik      (1000) erik      (1000)     2259 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_client/cli_backend/__init__.py
+-rw-r--r--   0 erik      (1000) erik      (1000)    11695 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_client/cli_backend/grpc.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     9892 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_client/cli_backend/ws.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/kuksa_client/grpc/
+-rw-r--r--   0 erik      (1000) erik      (1000)    39035 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_client/grpc/__init__.py
+-rw-r--r--   0 erik      (1000) erik      (1000)    16627 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/kuksa_client/grpc/aio.py
+-rw-r--r--   0 erik      (1000) erik      (1000)      385 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_client/logging.ini
+-rw-r--r--   0 erik      (1000) erik      (1000)      605 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_client/logo
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/kuksa_client/ws/
+-rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/kuksa_client/ws/__init__.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/kuksa_client.egg-info/
+-rw-r--r--   0 erik      (1000) erik      (1000)    13411 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa_client.egg-info/PKG-INFO
+-rw-r--r--   0 erik      (1000) erik      (1000)     1534 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa_client.egg-info/SOURCES.txt
+-rw-r--r--   0 erik      (1000) erik      (1000)        1 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa_client.egg-info/dependency_links.txt
+-rw-r--r--   0 erik      (1000) erik      (1000)       60 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa_client.egg-info/entry_points.txt
+-rw-r--r--   0 erik      (1000) erik      (1000)      212 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa_client.egg-info/requires.txt
+-rw-r--r--   0 erik      (1000) erik      (1000)       44 2023-06-28 08:56:56.000000 kuksa_client-0.4.0a4/kuksa_client.egg-info/top_level.txt
+-rw-r--r--   0 erik      (1000) erik      (1000)      625 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/pyproject.toml
+-rw-r--r--   0 erik      (1000) erik      (1000)     1370 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/setup.cfg
+-rw-r--r--   0 erik      (1000) erik      (1000)     1168 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/setup.py
+drwxr-xr-x   0 erik      (1000) erik      (1000)        0 2023-06-28 08:56:56.591435 kuksa_client-0.4.0a4/tests/
+-rw-r--r--   0 erik      (1000) erik      (1000)        0 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/tests/__init__.py
+-rw-r--r--   0 erik      (1000) erik      (1000)     2545 2023-05-09 13:51:21.000000 kuksa_client-0.4.0a4/tests/conftest.py
+-rw-r--r--   0 erik      (1000) erik      (1000)    63305 2023-06-28 08:55:35.000000 kuksa_client-0.4.0a4/tests/test_grpc.py
```

### Comparing `kuksa_client-0.4.0a3/PKG-INFO` & `kuksa_client-0.4.0a4/kuksa_client.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: kuksa_client
-Version: 0.4.0a3
+Name: kuksa-client
+Version: 0.4.0a4
 Summary: kuksa.val python clients and SDK
 Home-page: https://github.com/eclipse/kuksa.val
 Author: Sebastian Schildt, Naresh Nayak, Wenwen Chen
 Author-email: sebastian.schildt@de.bosch.com, naresh.nayak@de.bosch.com, wenwen.chen@de.bosch.com
 Project-URL: Source, https://github.com/eclipse/kuksa.val/tree/master/kuksa-client
 Project-URL: Bug Tracker, https://github.com/eclipse/kuksa.val/issues
 Classifier: Intended Audience :: Developers
@@ -79,42 +79,19 @@
 Websocket connected securely.
 Test Client>
 ```
 
 If the connected KUKSA.val Server or KUKSA.val Databroker require authorization the next step is to authorize.
 KUKSA.val Server and KUKSA.val Databroker use different token formats.
 
-### Authorizing against KUKSA.val Server
-
-The jwt tokens for testing can either be found under [../kuksa_certificates/jwt](../kuksa_certificates/jwt)
-or you can also use following command inside `kuksa-client` to find the via `pip` installed certificate directory.
-
-```console
-Test Client> printTokenDir
-```
-Select one of the tokens and use the `authorize` command like below:
-
-```console
-Test Client> authorize /some/path/kuksa_certificates/jwt/super-admin.json.token
-```
-
-### Authorizing against KUKSA.val Databroker
-
-If connecting to Databroker the command `printTokenDir` is not much help as it shows the default token directories
-for KUKSA.val Server example tokens. If the KUKSA.val Databroker use default example tokens then one of the
-tokens in [../jwt](../jwt) can be used, like in the example below:
-
-```console
-Test Client> authorize /some/path/jwt/provide-all.token
-```
-
-## Using TLS
+### Connecting to KUKSA.val Databroker
 
+A gRPC connection to KUKSA.val Databroker is started by specifying address and port for the Databroker and giving
+`--protocol grpc` as argument.
 KUKSA.val Client use TLS by default, it only run in insecure mode if `--insecure` is given as argument.
-
 By default the KUKSA.val example Root CA and Client keys are used, but client keys have no effect as mutual authentication is not supported by KUKSA.val Databroker or KUKSA.val Server.
 
 ```
 ~/kuksa.val/kuksa-client$ kuksa-client --ip localhost --port 55555 --protocol grpc
 ```
 
 This call with all parameters specified give same effect:
@@ -151,14 +128,38 @@
 
 This corresponds to this call:
 
 ```
 kuksa-client --ip 127.0.0.1 --port 8090 --protocol ws --cacertificate ./kuksa_certificates/CA.pem
 ```
 
+### Authorizing against KUKSA.val Server
+
+The jwt tokens for testing can either be found under [../kuksa_certificates/jwt](../kuksa_certificates/jwt)
+or you can also use following command inside `kuksa-client` to find the via `pip` installed certificate directory.
+
+```console
+Test Client> printTokenDir
+```
+Select one of the tokens and use the `authorize` command like below:
+
+```console
+Test Client> authorize /some/path/kuksa_certificates/jwt/super-admin.json.token
+```
+
+### Authorizing against KUKSA.val Databroker
+
+If connecting to Databroker the command `printTokenDir` is not much help as it shows the default token directories
+for KUKSA.val Server example tokens. If the KUKSA.val Databroker use default example tokens then one of the
+tokens in [../jwt](../jwt) can be used, like in the example below:
+
+```console
+Test Client> authorize /some/path/jwt/provide-all.token
+```
+
 ## Usage Instructions
 
 Refer help for further information
 
 ```console
 Test Client> help -v
```

### Comparing `kuksa_client-0.4.0a3/README.md` & `kuksa_client-0.4.0a4/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -59,42 +59,19 @@
 Websocket connected securely.
 Test Client>
 ```
 
 If the connected KUKSA.val Server or KUKSA.val Databroker require authorization the next step is to authorize.
 KUKSA.val Server and KUKSA.val Databroker use different token formats.
 
-### Authorizing against KUKSA.val Server
-
-The jwt tokens for testing can either be found under [../kuksa_certificates/jwt](../kuksa_certificates/jwt)
-or you can also use following command inside `kuksa-client` to find the via `pip` installed certificate directory.
-
-```console
-Test Client> printTokenDir
-```
-Select one of the tokens and use the `authorize` command like below:
-
-```console
-Test Client> authorize /some/path/kuksa_certificates/jwt/super-admin.json.token
-```
-
-### Authorizing against KUKSA.val Databroker
-
-If connecting to Databroker the command `printTokenDir` is not much help as it shows the default token directories
-for KUKSA.val Server example tokens. If the KUKSA.val Databroker use default example tokens then one of the
-tokens in [../jwt](../jwt) can be used, like in the example below:
-
-```console
-Test Client> authorize /some/path/jwt/provide-all.token
-```
-
-## Using TLS
+### Connecting to KUKSA.val Databroker
 
+A gRPC connection to KUKSA.val Databroker is started by specifying address and port for the Databroker and giving
+`--protocol grpc` as argument.
 KUKSA.val Client use TLS by default, it only run in insecure mode if `--insecure` is given as argument.
-
 By default the KUKSA.val example Root CA and Client keys are used, but client keys have no effect as mutual authentication is not supported by KUKSA.val Databroker or KUKSA.val Server.
 
 ```
 ~/kuksa.val/kuksa-client$ kuksa-client --ip localhost --port 55555 --protocol grpc
 ```
 
 This call with all parameters specified give same effect:
@@ -131,14 +108,38 @@
 
 This corresponds to this call:
 
 ```
 kuksa-client --ip 127.0.0.1 --port 8090 --protocol ws --cacertificate ./kuksa_certificates/CA.pem
 ```
 
+### Authorizing against KUKSA.val Server
+
+The jwt tokens for testing can either be found under [../kuksa_certificates/jwt](../kuksa_certificates/jwt)
+or you can also use following command inside `kuksa-client` to find the via `pip` installed certificate directory.
+
+```console
+Test Client> printTokenDir
+```
+Select one of the tokens and use the `authorize` command like below:
+
+```console
+Test Client> authorize /some/path/kuksa_certificates/jwt/super-admin.json.token
+```
+
+### Authorizing against KUKSA.val Databroker
+
+If connecting to Databroker the command `printTokenDir` is not much help as it shows the default token directories
+for KUKSA.val Server example tokens. If the KUKSA.val Databroker use default example tokens then one of the
+tokens in [../jwt](../jwt) can be used, like in the example below:
+
+```console
+Test Client> authorize /some/path/jwt/provide-all.token
+```
+
 ## Usage Instructions
 
 Refer help for further information
 
 ```console
 Test Client> help -v
```

### Comparing `kuksa_client-0.4.0a3/kuksa/val/v1/val_pb2_grpc.py` & `kuksa_client-0.4.0a4/kuksa/val/v1/val_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/CA.key` & `kuksa_client-0.4.0a4/kuksa_certificates/CA.key`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/CA.pem` & `kuksa_client-0.4.0a4/kuksa_certificates/CA.pem`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/Client.key` & `kuksa_client-0.4.0a4/kuksa_certificates/Client.key`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/Client.pem` & `kuksa_client-0.4.0a4/kuksa_certificates/Client.pem`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/README.md` & `kuksa_client-0.4.0a4/kuksa_certificates/README.md`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/Server.key` & `kuksa_client-0.4.0a4/kuksa_certificates/Server.key`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/Server.pem` & `kuksa_client-0.4.0a4/kuksa_certificates/Server.pem`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/genCerts.sh` & `kuksa_client-0.4.0a4/kuksa_certificates/genCerts.sh`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/all-read-write.json.token` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/all-read-write.json.token`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/createToken.py` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/createToken.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/jwt.key` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/jwt.key`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/jwt.key.pub` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/jwt.key.pub`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/recreateJWTkeyPair.sh` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/recreateJWTkeyPair.sh`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/single-read.json.token` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/single-read.json.token`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_certificates/jwt/super-admin.json.token` & `kuksa_client-0.4.0a4/kuksa_certificates/jwt/super-admin.json.token`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/__init__.py` & `kuksa_client-0.4.0a4/kuksa_client/__init__.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/__main__.py` & `kuksa_client-0.4.0a4/kuksa_client/__main__.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/_metadata.py` & `kuksa_client-0.4.0a4/kuksa_client/_metadata.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/cli_backend/__init__.py` & `kuksa_client-0.4.0a4/kuksa_client/cli_backend/__init__.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/cli_backend/grpc.py` & `kuksa_client-0.4.0a4/kuksa_client/cli_backend/grpc.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/cli_backend/ws.py` & `kuksa_client-0.4.0a4/kuksa_client/cli_backend/ws.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/grpc/__init__.py` & `kuksa_client-0.4.0a4/kuksa_client/grpc/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -515,15 +515,15 @@
                 certificate_chain = self.certificate_chain.read_bytes()
                 logger.info(f"Using private client key {self.private_key} "
                                  f"and chain/certificate {self.certificate_chain}")
                 return grpc.ssl_channel_credentials(root_certificates, private_key, certificate_chain)
             else:
                 logger.info(f"No client certificates provided, mutual TLS not supported!")
                 return grpc.ssl_channel_credentials(root_certificates)
-        logger.warning(f"No Root CA present!")
+        logger.info(f"No Root CA present, it will not be posible to use a secure connection!")
         return None
         
 
     def _prepare_get_request(self, entries: Iterable[EntryRequest]) -> val_pb2.GetRequest:
         req = val_pb2.GetRequest(entries=[])
         for entry in entries:
             entry_request = val_pb2.EntryRequest(
```

### Comparing `kuksa_client-0.4.0a3/kuksa_client/grpc/aio.py` & `kuksa_client-0.4.0a4/kuksa_client/grpc/aio.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client/logo` & `kuksa_client-0.4.0a4/kuksa_client/logo`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/kuksa_client.egg-info/PKG-INFO` & `kuksa_client-0.4.0a4/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: kuksa-client
-Version: 0.4.0a3
+Name: kuksa_client
+Version: 0.4.0a4
 Summary: kuksa.val python clients and SDK
 Home-page: https://github.com/eclipse/kuksa.val
 Author: Sebastian Schildt, Naresh Nayak, Wenwen Chen
 Author-email: sebastian.schildt@de.bosch.com, naresh.nayak@de.bosch.com, wenwen.chen@de.bosch.com
 Project-URL: Source, https://github.com/eclipse/kuksa.val/tree/master/kuksa-client
 Project-URL: Bug Tracker, https://github.com/eclipse/kuksa.val/issues
 Classifier: Intended Audience :: Developers
@@ -79,42 +79,19 @@
 Websocket connected securely.
 Test Client>
 ```
 
 If the connected KUKSA.val Server or KUKSA.val Databroker require authorization the next step is to authorize.
 KUKSA.val Server and KUKSA.val Databroker use different token formats.
 
-### Authorizing against KUKSA.val Server
-
-The jwt tokens for testing can either be found under [../kuksa_certificates/jwt](../kuksa_certificates/jwt)
-or you can also use following command inside `kuksa-client` to find the via `pip` installed certificate directory.
-
-```console
-Test Client> printTokenDir
-```
-Select one of the tokens and use the `authorize` command like below:
-
-```console
-Test Client> authorize /some/path/kuksa_certificates/jwt/super-admin.json.token
-```
-
-### Authorizing against KUKSA.val Databroker
-
-If connecting to Databroker the command `printTokenDir` is not much help as it shows the default token directories
-for KUKSA.val Server example tokens. If the KUKSA.val Databroker use default example tokens then one of the
-tokens in [../jwt](../jwt) can be used, like in the example below:
-
-```console
-Test Client> authorize /some/path/jwt/provide-all.token
-```
-
-## Using TLS
+### Connecting to KUKSA.val Databroker
 
+A gRPC connection to KUKSA.val Databroker is started by specifying address and port for the Databroker and giving
+`--protocol grpc` as argument.
 KUKSA.val Client use TLS by default, it only run in insecure mode if `--insecure` is given as argument.
-
 By default the KUKSA.val example Root CA and Client keys are used, but client keys have no effect as mutual authentication is not supported by KUKSA.val Databroker or KUKSA.val Server.
 
 ```
 ~/kuksa.val/kuksa-client$ kuksa-client --ip localhost --port 55555 --protocol grpc
 ```
 
 This call with all parameters specified give same effect:
@@ -151,14 +128,38 @@
 
 This corresponds to this call:
 
 ```
 kuksa-client --ip 127.0.0.1 --port 8090 --protocol ws --cacertificate ./kuksa_certificates/CA.pem
 ```
 
+### Authorizing against KUKSA.val Server
+
+The jwt tokens for testing can either be found under [../kuksa_certificates/jwt](../kuksa_certificates/jwt)
+or you can also use following command inside `kuksa-client` to find the via `pip` installed certificate directory.
+
+```console
+Test Client> printTokenDir
+```
+Select one of the tokens and use the `authorize` command like below:
+
+```console
+Test Client> authorize /some/path/kuksa_certificates/jwt/super-admin.json.token
+```
+
+### Authorizing against KUKSA.val Databroker
+
+If connecting to Databroker the command `printTokenDir` is not much help as it shows the default token directories
+for KUKSA.val Server example tokens. If the KUKSA.val Databroker use default example tokens then one of the
+tokens in [../jwt](../jwt) can be used, like in the example below:
+
+```console
+Test Client> authorize /some/path/jwt/provide-all.token
+```
+
 ## Usage Instructions
 
 Refer help for further information
 
 ```console
 Test Client> help -v
```

### Comparing `kuksa_client-0.4.0a3/kuksa_client.egg-info/SOURCES.txt` & `kuksa_client-0.4.0a4/kuksa_client.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/pyproject.toml` & `kuksa_client-0.4.0a4/pyproject.toml`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/setup.cfg` & `kuksa_client-0.4.0a4/setup.cfg`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/setup.py` & `kuksa_client-0.4.0a4/setup.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/tests/conftest.py` & `kuksa_client-0.4.0a4/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `kuksa_client-0.4.0a3/tests/test_grpc.py` & `kuksa_client-0.4.0a4/tests/test_grpc.py`

 * *Files identical despite different names*


# Comparing `tmp/mrlpy-0.3.0.tar.gz` & `tmp/mrlpy-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
+gzip compressed data, was "dist/mrlpy-1.0.0.tar", last modified: Tue Aug 15 16:46:38 2017, max compression
```

## Comparing `mrlpy-0.3.0.tar` & `mrlpy-1.0.0.tar`

### file list

```diff
@@ -1,31 +1,32 @@
--rw-r--r--   0        0        0     1418 2020-02-02 00:00:00.000000 mrlpy-0.3.0/_TemplateProxy.py
--rw-r--r--   0        0        0    13403 2020-02-02 00:00:00.000000 mrlpy-0.3.0/example-handshake.py
--rw-r--r--   0        0        0      486 2020-02-02 00:00:00.000000 mrlpy-0.3.0/setup.py
--rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 mrlpy-0.3.0/examples/exampleCompatScript.py
--rw-r--r--   0        0        0     1098 2020-02-02 00:00:00.000000 mrlpy-0.3.0/examples/exampleService.py
--rw-r--r--   0        0        0    11485 2020-02-02 00:00:00.000000 mrlpy-0.3.0/examples/llama-with-solr.py
--rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/__init__.py
--rw-r--r--   0        0        0      408 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/exceptions.py
--rwxr-xr-x   0        0        0    12564 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/mcommand.py
--rwxr-xr-x   0        0        0      479 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/mcompat-run.py
--rw-r--r--   0        0        0     1135 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/mcompat.py
--rw-r--r--   0        0        0     1156 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/mevent.py
--rw-r--r--   0        0        0     2167 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/meventdispatch.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/proxy.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/proxygen.py
--rw-r--r--   0        0        0      255 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/testService.py
--rw-r--r--   0        0        0     2015 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/utils.py
--rw-r--r--   0        0        0      823 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/framework/deserializer.py
--rw-r--r--   0        0        0      322 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/framework/interfaces.py
--rw-r--r--   0        0        0      801 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/framework/mrl_dataclass.py
--rw-r--r--   0        0        0     4985 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/framework/runtime.py
--rw-r--r--   0        0        0      486 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/framework/serializer.py
--rw-r--r--   0        0        0     6797 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/framework/service.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/service/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/service/data/__init__.py
--rw-r--r--   0        0        0      769 2020-02-02 00:00:00.000000 mrlpy-0.3.0/src/mrlpy/service/data/chat.py
--rw-r--r--   0        0        0      110 2020-02-02 00:00:00.000000 mrlpy-0.3.0/.gitignore
--rw-r--r--   0        0        0    11322 2020-02-02 00:00:00.000000 mrlpy-0.3.0/LICENSE
--rw-r--r--   0        0        0     5715 2020-02-02 00:00:00.000000 mrlpy-0.3.0/README.md
--rw-r--r--   0        0        0      532 2020-02-02 00:00:00.000000 mrlpy-0.3.0/pyproject.toml
--rw-r--r--   0        0        0     6045 2020-02-02 00:00:00.000000 mrlpy-0.3.0/PKG-INFO
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2017-08-15 16:46:38.000000 mrlpy-1.0.0/
+-rw-r--r--   0 pi        (1000) pi        (1000)      515 2017-08-15 16:41:25.000000 mrlpy-1.0.0/setup.py
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2017-08-15 16:46:38.000000 mrlpy-1.0.0/org/
+-rw-r--r--   0 pi        (1000) pi        (1000)        0 2017-05-25 21:51:32.000000 mrlpy-1.0.0/org/__init__.py
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2017-08-15 16:46:38.000000 mrlpy-1.0.0/org/myrobotlab/
+-rw-r--r--   0 pi        (1000) pi        (1000)        0 2017-05-25 21:51:14.000000 mrlpy-1.0.0/org/myrobotlab/__init__.py
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2017-08-15 16:46:38.000000 mrlpy-1.0.0/org/myrobotlab/service/
+-rw-r--r--   0 pi        (1000) pi        (1000)      576 2017-06-05 04:11:16.000000 mrlpy-1.0.0/org/myrobotlab/service/Runtime.py
+-rw-r--r--   0 pi        (1000) pi        (1000)       30 2017-05-25 23:19:09.000000 mrlpy-1.0.0/org/myrobotlab/service/__init__.py
+-rw-r--r--   0 pi        (1000) pi        (1000)       93 2017-05-25 23:01:59.000000 mrlpy-1.0.0/org/myrobotlab/service/Test.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      257 2017-08-15 16:46:38.000000 mrlpy-1.0.0/PKG-INFO
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy/
+-rw-r--r--   0 pi        (1000) pi        (1000)      691 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/mcompat.py
+-rw-r--r--   0 pi        (1000) pi        (1000)     1654 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/mproxygen.py
+-rwxr-xr-x   0 pi        (1000) pi        (1000)     9283 2017-08-14 18:54:36.000000 mrlpy-1.0.0/mrlpy/mcommand.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      389 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/exceptions.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      276 2017-08-14 18:31:14.000000 mrlpy-1.0.0/mrlpy/mutils.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      501 2017-08-14 17:34:55.000000 mrlpy-1.0.0/mrlpy/mrlmessage.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      224 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/testService.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      484 2017-08-14 14:53:07.000000 mrlpy-1.0.0/mrlpy/mevent.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      264 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/__init__.py
+-rw-r--r--   0 pi        (1000) pi        (1000)     3591 2017-08-15 15:28:10.000000 mrlpy-1.0.0/mrlpy/mservice.py
+-rw-r--r--   0 pi        (1000) pi        (1000)     1933 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/meventdispatch.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      143 2017-08-12 00:26:07.000000 mrlpy-1.0.0/mrlpy/mproxy.py
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy.egg-info/
+-rw-r--r--   0 pi        (1000) pi        (1000)       26 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy.egg-info/requires.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)      556 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy.egg-info/SOURCES.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)      257 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy.egg-info/PKG-INFO
+-rw-r--r--   0 pi        (1000) pi        (1000)        1 2017-06-06 17:36:53.000000 mrlpy-1.0.0/mrlpy.egg-info/not-zip-safe
+-rw-r--r--   0 pi        (1000) pi        (1000)       10 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy.egg-info/top_level.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)        1 2017-08-15 16:46:38.000000 mrlpy-1.0.0/mrlpy.egg-info/dependency_links.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)       59 2017-08-15 16:46:38.000000 mrlpy-1.0.0/setup.cfg
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive
+POSIX tar archive (GNU)
```


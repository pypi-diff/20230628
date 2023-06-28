# Comparing `tmp/chatglm-llm-1.4.1.tar.gz` & `tmp/chatglm-llm-1.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chatglm-llm-1.4.1.tar", last modified: Fri Jun 16 08:15:31 2023, max compression
+gzip compressed data, was "chatglm-llm-1.4.2.tar", last modified: Wed Jun 28 01:04:02 2023, max compression
```

## Comparing `chatglm-llm-1.4.1.tar` & `chatglm-llm-1.4.2.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-16 08:15:31.134631 chatglm-llm-1.4.1/
--rw-r--r--   0 mroy       (501) staff       (20)       36 2023-05-10 01:48:15.000000 chatglm-llm-1.4.1/MANIFEST.in
--rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-16 08:15:31.134503 chatglm-llm-1.4.1/PKG-INFO
--rw-r--r--   0 mroy       (501) staff       (20)     1887 2023-05-04 01:08:28.000000 chatglm-llm-1.4.1/README.md
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-16 08:15:31.133267 chatglm-llm-1.4.1/chatglm_llm.egg-info/
--rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-16 08:15:30.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/PKG-INFO
--rw-r--r--   0 mroy       (501) staff       (20)      511 2023-06-16 08:15:31.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/SOURCES.txt
--rw-r--r--   0 mroy       (501) staff       (20)        1 2023-06-16 08:15:30.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/dependency_links.txt
--rw-r--r--   0 mroy       (501) staff       (20)       53 2023-06-16 08:15:30.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/entry_points.txt
--rw-r--r--   0 mroy       (501) staff       (20)        1 2023-05-04 01:12:10.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/not-zip-safe
--rw-r--r--   0 mroy       (501) staff       (20)      266 2023-06-16 08:15:31.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/requires.txt
--rw-r--r--   0 mroy       (501) staff       (20)       12 2023-06-16 08:15:31.000000 chatglm-llm-1.4.1/chatglm_llm.egg-info/top_level.txt
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-16 08:15:31.133895 chatglm-llm-1.4.1/chatglm_src/
--rw-r--r--   0 mroy       (501) staff       (20)      755 2023-06-16 02:41:40.000000 chatglm-llm-1.4.1/chatglm_src/__init__.py
--rw-r--r--   0 mroy       (501) staff       (20)     4201 2023-05-13 02:36:58.000000 chatglm-llm-1.4.1/chatglm_src/callbacks.py
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-16 08:15:31.134178 chatglm-llm-1.4.1/chatglm_src/chains/
--rw-r--r--   0 mroy       (501) staff       (20)       69 2023-05-10 01:48:15.000000 chatglm-llm-1.4.1/chatglm_src/chains/__init__.py
--rw-r--r--   0 mroy       (501) staff       (20)     4402 2023-05-11 09:17:21.000000 chatglm-llm-1.4.1/chatglm_src/chains/local_qa.py
--rw-r--r--   0 mroy       (501) staff       (20)     2777 2023-06-16 06:08:22.000000 chatglm-llm-1.4.1/chatglm_src/cluster_and_smi.py
--rw-r--r--   0 mroy       (501) staff       (20)      537 2023-05-30 04:20:56.000000 chatglm-llm-1.4.1/chatglm_src/cmd.py
--rw-r--r--   0 mroy       (501) staff       (20)     3052 2023-06-15 08:48:00.000000 chatglm-llm-1.4.1/chatglm_src/embeding.py
--rw-r--r--   0 mroy       (501) staff       (20)    38577 2023-06-16 07:01:29.000000 chatglm-llm-1.4.1/chatglm_src/llm.py
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-16 08:15:31.134293 chatglm-llm-1.4.1/chatglm_src/loader/
--rw-r--r--   0 mroy       (501) staff       (20)     1403 2023-05-11 01:28:05.000000 chatglm-llm-1.4.1/chatglm_src/loader/__init__.py
--rw-r--r--   0 mroy       (501) staff       (20)       38 2023-06-16 08:15:31.134679 chatglm-llm-1.4.1/setup.cfg
--rw-r--r--   0 mroy       (501) staff       (20)     1078 2023-06-16 08:15:26.000000 chatglm-llm-1.4.1/setup.py
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.930417 chatglm-llm-1.4.2/
+-rw-r--r--   0 mroy       (501) staff       (20)       36 2023-05-10 01:48:15.000000 chatglm-llm-1.4.2/MANIFEST.in
+-rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-28 01:04:02.930297 chatglm-llm-1.4.2/PKG-INFO
+-rw-r--r--   0 mroy       (501) staff       (20)     1887 2023-05-04 01:08:28.000000 chatglm-llm-1.4.2/README.md
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.929171 chatglm-llm-1.4.2/chatglm_llm.egg-info/
+-rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/PKG-INFO
+-rw-r--r--   0 mroy       (501) staff       (20)      511 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/SOURCES.txt
+-rw-r--r--   0 mroy       (501) staff       (20)        1 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/dependency_links.txt
+-rw-r--r--   0 mroy       (501) staff       (20)       53 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/entry_points.txt
+-rw-r--r--   0 mroy       (501) staff       (20)        1 2023-05-04 01:12:10.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/not-zip-safe
+-rw-r--r--   0 mroy       (501) staff       (20)      266 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/requires.txt
+-rw-r--r--   0 mroy       (501) staff       (20)       12 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/top_level.txt
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.929792 chatglm-llm-1.4.2/chatglm_src/
+-rw-r--r--   0 mroy       (501) staff       (20)      755 2023-06-16 02:41:40.000000 chatglm-llm-1.4.2/chatglm_src/__init__.py
+-rw-r--r--   0 mroy       (501) staff       (20)     4201 2023-05-13 02:36:58.000000 chatglm-llm-1.4.2/chatglm_src/callbacks.py
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.930029 chatglm-llm-1.4.2/chatglm_src/chains/
+-rw-r--r--   0 mroy       (501) staff       (20)       69 2023-05-10 01:48:15.000000 chatglm-llm-1.4.2/chatglm_src/chains/__init__.py
+-rw-r--r--   0 mroy       (501) staff       (20)     4402 2023-05-11 09:17:21.000000 chatglm-llm-1.4.2/chatglm_src/chains/local_qa.py
+-rw-r--r--   0 mroy       (501) staff       (20)     2777 2023-06-16 06:08:22.000000 chatglm-llm-1.4.2/chatglm_src/cluster_and_smi.py
+-rw-r--r--   0 mroy       (501) staff       (20)      537 2023-05-30 04:20:56.000000 chatglm-llm-1.4.2/chatglm_src/cmd.py
+-rw-r--r--   0 mroy       (501) staff       (20)     3052 2023-06-15 08:48:00.000000 chatglm-llm-1.4.2/chatglm_src/embeding.py
+-rw-r--r--   0 mroy       (501) staff       (20)    38577 2023-06-16 07:01:29.000000 chatglm-llm-1.4.2/chatglm_src/llm.py
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.930130 chatglm-llm-1.4.2/chatglm_src/loader/
+-rw-r--r--   0 mroy       (501) staff       (20)     1403 2023-05-11 01:28:05.000000 chatglm-llm-1.4.2/chatglm_src/loader/__init__.py
+-rw-r--r--   0 mroy       (501) staff       (20)       38 2023-06-28 01:04:02.930455 chatglm-llm-1.4.2/setup.cfg
+-rw-r--r--   0 mroy       (501) staff       (20)     1078 2023-06-28 01:02:51.000000 chatglm-llm-1.4.2/setup.py
```

### Comparing `chatglm-llm-1.4.1/README.md` & `chatglm-llm-1.4.2/README.md`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/__init__.py` & `chatglm-llm-1.4.2/chatglm_src/__init__.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/callbacks.py` & `chatglm-llm-1.4.2/chatglm_src/callbacks.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/chains/local_qa.py` & `chatglm-llm-1.4.2/chatglm_src/chains/local_qa.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/cluster_and_smi.py` & `chatglm-llm-1.4.2/chatglm_src/cluster_and_smi.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/cmd.py` & `chatglm-llm-1.4.2/chatglm_src/cmd.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/embeding.py` & `chatglm-llm-1.4.2/chatglm_src/embeding.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/llm.py` & `chatglm-llm-1.4.2/chatglm_src/llm.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/chatglm_src/loader/__init__.py` & `chatglm-llm-1.4.2/chatglm_src/loader/__init__.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.1/setup.py` & `chatglm-llm-1.4.2/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 
 from setuptools import setup, find_packages
 
 
 setup(name='chatglm-llm',
-    version='1.4.1',
+    version='1.4.2',
     description='chatglm llm',
     url='https://github.com/xxx',
     author='auth',
     author_email='xxx@gmail.com',
     license='MIT',
     include_package_data=True,
     zip_safe=False,
```


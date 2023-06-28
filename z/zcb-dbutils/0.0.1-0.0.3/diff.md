# Comparing `tmp/zcb_dbutils-0.0.1.tar.gz` & `tmp/zcb_dbutils-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "zcb_dbutils-0.0.1.tar", last modified: Wed Jun 28 09:56:33 2023, max compression
+gzip compressed data, was "zcb_dbutils-0.0.3.tar", last modified: Wed Jun 28 10:20:58 2023, max compression
```

## Comparing `zcb_dbutils-0.0.1.tar` & `zcb_dbutils-0.0.3.tar`

### file list

```diff
@@ -1,12 +1,12 @@
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 09:56:32.581840 zcb_dbutils-0.0.1/
--rwxrwxrwx   0 root         (0) root         (0)      473 2023-06-28 09:56:32.571840 zcb_dbutils-0.0.1/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)        9 2023-06-28 09:39:35.000000 zcb_dbutils-0.0.1/README.md
--rwxrwxrwx   0 root         (0) root         (0)     3666 2022-10-25 12:58:40.000000 zcb_dbutils-0.0.1/dbutils.py
--rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 09:56:32.582839 zcb_dbutils-0.0.1/setup.cfg
--rwxrwxrwx   0 root         (0) root         (0)      884 2023-06-28 09:56:23.000000 zcb_dbutils-0.0.1/setup.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 09:56:32.552842 zcb_dbutils-0.0.1/zcb_dbutils.egg-info/
--rwxrwxrwx   0 root         (0) root         (0)      473 2023-06-28 09:56:31.000000 zcb_dbutils-0.0.1/zcb_dbutils.egg-info/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)      203 2023-06-28 09:56:32.000000 zcb_dbutils-0.0.1/zcb_dbutils.egg-info/SOURCES.txt
--rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 09:56:31.000000 zcb_dbutils-0.0.1/zcb_dbutils.egg-info/dependency_links.txt
--rwxrwxrwx   0 root         (0) root         (0)        8 2023-06-28 09:56:31.000000 zcb_dbutils-0.0.1/zcb_dbutils.egg-info/requires.txt
--rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 09:56:31.000000 zcb_dbutils-0.0.1/zcb_dbutils.egg-info/top_level.txt
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:20:57.237795 zcb_dbutils-0.0.3/
+-rwxrwxrwx   0 root         (0) root         (0)      726 2023-06-28 10:20:57.235796 zcb_dbutils-0.0.3/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)      325 2023-06-28 10:15:24.000000 zcb_dbutils-0.0.3/README.md
+-rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 10:20:57.237795 zcb_dbutils-0.0.3/setup.cfg
+-rwxrwxrwx   0 root         (0) root         (0)      724 2023-06-28 10:20:48.000000 zcb_dbutils-0.0.3/setup.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:20:57.222028 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/
+-rwxrwxrwx   0 root         (0) root         (0)      726 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)      207 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/SOURCES.txt
+-rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/dependency_links.txt
+-rwxrwxrwx   0 root         (0) root         (0)        8 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/requires.txt
+-rwxrwxrwx   0 root         (0) root         (0)       12 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/top_level.txt
+-rwxrwxrwx   0 root         (0) root         (0)     3666 2022-10-25 12:58:40.000000 zcb_dbutils-0.0.3/zcb_dbutils.py
```

### Comparing `zcb_dbutils-0.0.1/dbutils.py` & `zcb_dbutils-0.0.3/zcb_dbutils.py`

 * *Files identical despite different names*

### Comparing `zcb_dbutils-0.0.1/setup.py` & `zcb_dbutils-0.0.3/setup.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,31 +1,24 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.1'
-DESCRIPTION = 'DBUtils with pymysql by chzcb'
+VERSION = '0.0.3'
+DESCRIPTION = 'db utils with pymysql by chzcb'
 
 setup(
     name="zcb_dbutils",
     version=VERSION,
     author="chzcb",
     author_email="chzcb.04@163.com",
     description=DESCRIPTION,
     long_description_content_type="text/markdown",
     long_description=open('README.md',encoding="UTF8").read(),
-    packages=find_packages(),
     install_requires=['pymysql'],
     keywords=['python', 'pymysql', 'zcb_dbutils'],
-    data_files=[],
-    entry_points={
-    'console_scripts': [
-    ]
-    },
     license="MIT",
     url="https://github.com/chzcb/dbutils",
-    scripts=['dbutils.py'],
+    py_modules=['zcb_dbutils'],
     classifiers= [
         "Development Status :: 3 - Alpha",
         "Intended Audience :: Developers",
-        "Programming Language :: Python :: 3",
-        "Operating System :: Microsoft :: Windows"
+        "Programming Language :: Python :: 3"
     ]
 )
```


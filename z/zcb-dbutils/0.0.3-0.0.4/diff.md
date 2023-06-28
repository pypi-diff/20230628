# Comparing `tmp/zcb_dbutils-0.0.3.tar.gz` & `tmp/zcb_dbutils-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "zcb_dbutils-0.0.3.tar", last modified: Wed Jun 28 10:20:58 2023, max compression
+gzip compressed data, was "zcb_dbutils-0.0.4.tar", last modified: Wed Jun 28 10:46:27 2023, max compression
```

## Comparing `zcb_dbutils-0.0.3.tar` & `zcb_dbutils-0.0.4.tar`

### file list

```diff
@@ -1,12 +1,14 @@
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:20:57.237795 zcb_dbutils-0.0.3/
--rwxrwxrwx   0 root         (0) root         (0)      726 2023-06-28 10:20:57.235796 zcb_dbutils-0.0.3/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)      325 2023-06-28 10:15:24.000000 zcb_dbutils-0.0.3/README.md
--rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 10:20:57.237795 zcb_dbutils-0.0.3/setup.cfg
--rwxrwxrwx   0 root         (0) root         (0)      724 2023-06-28 10:20:48.000000 zcb_dbutils-0.0.3/setup.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:20:57.222028 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/
--rwxrwxrwx   0 root         (0) root         (0)      726 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)      207 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/SOURCES.txt
--rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/dependency_links.txt
--rwxrwxrwx   0 root         (0) root         (0)        8 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/requires.txt
--rwxrwxrwx   0 root         (0) root         (0)       12 2023-06-28 10:20:56.000000 zcb_dbutils-0.0.3/zcb_dbutils.egg-info/top_level.txt
--rwxrwxrwx   0 root         (0) root         (0)     3666 2022-10-25 12:58:40.000000 zcb_dbutils-0.0.3/zcb_dbutils.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:46:26.380865 zcb_dbutils-0.0.4/
+-rwxrwxrwx   0 root         (0) root         (0)      736 2023-06-28 10:46:26.379865 zcb_dbutils-0.0.4/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)      337 2023-06-28 10:44:08.000000 zcb_dbutils-0.0.4/README.md
+-rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 10:46:26.381865 zcb_dbutils-0.0.4/setup.cfg
+-rwxrwxrwx   0 root         (0) root         (0)      755 2023-06-28 10:46:23.000000 zcb_dbutils-0.0.4/setup.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:46:26.315886 zcb_dbutils-0.0.4/zcb_dbutils/
+-rwxrwxrwx   0 root         (0) root         (0)       33 2023-06-28 10:37:05.000000 zcb_dbutils-0.0.4/zcb_dbutils/__init__.py
+-rwxrwxrwx   0 root         (0) root         (0)     3666 2022-10-25 12:58:40.000000 zcb_dbutils-0.0.4/zcb_dbutils/dbutils.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 10:46:26.367866 zcb_dbutils-0.0.4/zcb_dbutils.egg-info/
+-rwxrwxrwx   0 root         (0) root         (0)      736 2023-06-28 10:46:26.000000 zcb_dbutils-0.0.4/zcb_dbutils.egg-info/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)      239 2023-06-28 10:46:26.000000 zcb_dbutils-0.0.4/zcb_dbutils.egg-info/SOURCES.txt
+-rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 10:46:26.000000 zcb_dbutils-0.0.4/zcb_dbutils.egg-info/dependency_links.txt
+-rwxrwxrwx   0 root         (0) root         (0)        8 2023-06-28 10:46:26.000000 zcb_dbutils-0.0.4/zcb_dbutils.egg-info/requires.txt
+-rwxrwxrwx   0 root         (0) root         (0)       12 2023-06-28 10:46:26.000000 zcb_dbutils-0.0.4/zcb_dbutils.egg-info/top_level.txt
```

### Comparing `zcb_dbutils-0.0.3/PKG-INFO` & `zcb_dbutils-0.0.4/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,26 +1,28 @@
 Metadata-Version: 2.1
 Name: zcb_dbutils
-Version: 0.0.3
+Version: 0.0.4
 Summary: db utils with pymysql by chzcb
 Home-page: https://github.com/chzcb/dbutils
 Author: chzcb
 Author-email: chzcb.04@163.com
 License: MIT
 Keywords: python,pymysql,zcb_dbutils
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
 Description-Content-Type: text/markdown
 
 # dbutils
 
 使用方法
+
 ```python
-from zcb_dbutils import DBConnection
+from zcb_dbutils.dbutils import DBConnection
+
 dbconn = DBConnection(host='localhost', port=3306, user='root', password='', database='mysql')
 
 # 查询单条数据
 row = dbconn.fetch_one('select * from table limit 1')
 # 查询多条数据
 rows = dbconn.fetch_rows('select * from table')
 ```
```

### Comparing `zcb_dbutils-0.0.3/setup.py` & `zcb_dbutils-0.0.4/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,23 +1,24 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.3'
+VERSION = '0.0.4'
 DESCRIPTION = 'db utils with pymysql by chzcb'
 
 setup(
     name="zcb_dbutils",
     version=VERSION,
     author="chzcb",
     author_email="chzcb.04@163.com",
     description=DESCRIPTION,
     long_description_content_type="text/markdown",
     long_description=open('README.md',encoding="UTF8").read(),
     install_requires=['pymysql'],
     keywords=['python', 'pymysql', 'zcb_dbutils'],
     license="MIT",
+    packages=find_packages(),
     url="https://github.com/chzcb/dbutils",
     py_modules=['zcb_dbutils'],
     classifiers= [
         "Development Status :: 3 - Alpha",
         "Intended Audience :: Developers",
         "Programming Language :: Python :: 3"
     ]
```

### Comparing `zcb_dbutils-0.0.3/zcb_dbutils.egg-info/PKG-INFO` & `zcb_dbutils-0.0.4/zcb_dbutils.egg-info/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,26 +1,28 @@
 Metadata-Version: 2.1
 Name: zcb-dbutils
-Version: 0.0.3
+Version: 0.0.4
 Summary: db utils with pymysql by chzcb
 Home-page: https://github.com/chzcb/dbutils
 Author: chzcb
 Author-email: chzcb.04@163.com
 License: MIT
 Keywords: python,pymysql,zcb_dbutils
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
 Description-Content-Type: text/markdown
 
 # dbutils
 
 使用方法
+
 ```python
-from zcb_dbutils import DBConnection
+from zcb_dbutils.dbutils import DBConnection
+
 dbconn = DBConnection(host='localhost', port=3306, user='root', password='', database='mysql')
 
 # 查询单条数据
 row = dbconn.fetch_one('select * from table limit 1')
 # 查询多条数据
 rows = dbconn.fetch_rows('select * from table')
 ```
```

### Comparing `zcb_dbutils-0.0.3/zcb_dbutils.py` & `zcb_dbutils-0.0.4/zcb_dbutils/dbutils.py`

 * *Files identical despite different names*


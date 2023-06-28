# Comparing `tmp/bkapi-plugins-py-0.627.tar.gz` & `tmp/bkapi-plugins-py-0.628.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bkapi-plugins-py-0.627.tar", last modified: Tue Jun 27 11:50:53 2023, max compression
+gzip compressed data, was "bkapi-plugins-py-0.628.tar", last modified: Wed Jun 28 08:19:26 2023, max compression
```

## Comparing `bkapi-plugins-py-0.627.tar` & `bkapi-plugins-py-0.628.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 11:50:53.259227 bkapi-plugins-py-0.627/
--rw-rw-rw-   0        0        0       39 2023-04-17 10:01:55.000000 bkapi-plugins-py-0.627/MANIFEST.in
--rw-rw-rw-   0        0        0      257 2023-06-27 11:50:53.259723 bkapi-plugins-py-0.627/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-27 11:50:53.242477 bkapi-plugins-py-0.627/bkapi_plugins/
-drwxrwxrwx   0        0        0        0 2023-06-27 11:50:53.250336 bkapi-plugins-py-0.627/bkapi_plugins/files/
--rw-rw-rw-   0        0        0   336586 2023-06-27 11:45:52.000000 bkapi-plugins-py-0.627/bkapi_plugins/files/mychart.tgz
-drwxrwxrwx   0        0        0        0 2023-06-27 11:50:53.257734 bkapi-plugins-py-0.627/bkapi_plugins_py.egg-info/
--rw-rw-rw-   0        0        0      257 2023-06-27 11:50:53.000000 bkapi-plugins-py-0.627/bkapi_plugins_py.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      222 2023-06-27 11:50:53.000000 bkapi-plugins-py-0.627/bkapi_plugins_py.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 11:50:53.000000 bkapi-plugins-py-0.627/bkapi_plugins_py.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 11:50:53.000000 bkapi-plugins-py-0.627/bkapi_plugins_py.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 11:50:53.260712 bkapi-plugins-py-0.627/setup.cfg
--rw-rw-rw-   0        0        0      890 2023-06-27 11:50:46.000000 bkapi-plugins-py-0.627/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:19:26.385046 bkapi-plugins-py-0.628/
+-rw-rw-rw-   0        0        0       39 2023-04-17 10:01:55.000000 bkapi-plugins-py-0.628/MANIFEST.in
+-rw-rw-rw-   0        0        0      257 2023-06-28 08:19:26.385046 bkapi-plugins-py-0.628/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 08:19:26.369691 bkapi-plugins-py-0.628/bkapi_plugins/
+drwxrwxrwx   0        0        0        0 2023-06-28 08:19:26.376970 bkapi-plugins-py-0.628/bkapi_plugins/files/
+-rw-rw-rw-   0        0        0    36372 2023-06-28 08:17:43.000000 bkapi-plugins-py-0.628/bkapi_plugins/files/influxdb-internals_rev1.json
+drwxrwxrwx   0        0        0        0 2023-06-28 08:19:26.383469 bkapi-plugins-py-0.628/bkapi_plugins_py.egg-info/
+-rw-rw-rw-   0        0        0      257 2023-06-28 08:19:26.000000 bkapi-plugins-py-0.628/bkapi_plugins_py.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      239 2023-06-28 08:19:26.000000 bkapi-plugins-py-0.628/bkapi_plugins_py.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:19:26.000000 bkapi-plugins-py-0.628/bkapi_plugins_py.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:19:26.000000 bkapi-plugins-py-0.628/bkapi_plugins_py.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:19:26.386877 bkapi-plugins-py-0.628/setup.cfg
+-rw-rw-rw-   0        0        0      890 2023-06-28 08:19:10.000000 bkapi-plugins-py-0.628/setup.py
```

### Comparing `bkapi-plugins-py-0.627/setup.py` & `bkapi-plugins-py-0.628/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 
 readme = ''
 
 setup(
     description='',
     long_description=readme,
     name='bkapi-plugins-py', # 包的名字
-    version='0.627', # 版本号每次打包完要改一下
+    version='0.628', # 版本号每次打包完要改一下
     python_requires='>=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*, !=3.5.*',
     author='fadewalk',
     license='Apach License 2.0',
     # packages=find_packages(),
     # namespace_packages=['bkapi_plugins'],
     package_dir={'': '.'},
     include_package_data=True,
```


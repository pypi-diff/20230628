# Comparing `tmp/performancetest-0.0.4.tar.gz` & `tmp/performancetest-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "performancetest-0.0.4.tar", last modified: Wed Jun 28 04:48:33 2023, max compression
+gzip compressed data, was "performancetest-1.0.3.tar", last modified: Wed Jun 28 04:44:53 2023, max compression
```

## Comparing `performancetest-0.0.4.tar` & `performancetest-1.0.3.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.677060 performancetest-0.0.4/
--rw-rw-rw-   0        0        0      515 2023-06-28 04:48:33.676783 performancetest-0.0.4/PKG-INFO
--rw-rw-rw-   0        0        0     4346 2023-06-27 05:36:55.000000 performancetest-0.0.4/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.619780 performancetest-0.0.4/performancetest/
--rw-rw-rw-   0        0        0       49 2023-06-21 09:23:31.000000 performancetest-0.0.4/performancetest/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.662321 performancetest-0.0.4/performancetest/core/
--rw-rw-rw-   0        0        0       25 2023-05-04 05:59:55.000000 performancetest-0.0.4/performancetest/core/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.667714 performancetest-0.0.4/performancetest/core/base/
--rw-rw-rw-   0        0        0       25 2023-05-04 05:59:55.000000 performancetest-0.0.4/performancetest/core/base/__init__.py
--rw-rw-rw-   0        0        0      289 2023-05-04 05:59:55.000000 performancetest-0.0.4/performancetest/core/base/actuator.py
--rw-rw-rw-   0        0        0      325 2023-05-04 05:59:55.000000 performancetest-0.0.4/performancetest/core/base/monitor.py
--rw-rw-rw-   0        0        0     3562 2023-06-21 12:46:09.000000 performancetest-0.0.4/performancetest/core/command.py
--rw-rw-rw-   0        0        0     4277 2023-06-27 06:56:49.000000 performancetest-0.0.4/performancetest/core/cpu.py
--rw-rw-rw-   0        0        0     6413 2023-06-23 08:54:45.000000 performancetest-0.0.4/performancetest/core/device.py
--rw-rw-rw-   0        0        0     4268 2023-06-21 12:46:09.000000 performancetest-0.0.4/performancetest/core/devicebattery.py
--rw-rw-rw-   0        0        0    18842 2023-06-25 06:05:19.000000 performancetest-0.0.4/performancetest/core/fps.py
--rw-rw-rw-   0        0        0      678 2023-06-21 12:46:09.000000 performancetest-0.0.4/performancetest/core/global_data.py
--rw-rw-rw-   0        0        0     3882 2023-06-27 06:56:49.000000 performancetest-0.0.4/performancetest/core/gpu.py
--rw-rw-rw-   0        0        0     6646 2023-06-21 12:47:53.000000 performancetest-0.0.4/performancetest/core/iosperf.py
--rw-rw-rw-   0        0        0     3928 2023-06-27 06:56:49.000000 performancetest-0.0.4/performancetest/core/memory.py
--rw-rw-rw-   0        0        0     4315 2023-06-23 08:54:45.000000 performancetest-0.0.4/performancetest/core/snapshot.py
--rw-rw-rw-   0        0        0     4254 2023-06-27 06:56:49.000000 performancetest-0.0.4/performancetest/core/task_handle.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.670071 performancetest-0.0.4/performancetest/test/
--rw-rw-rw-   0        0        0       25 2023-05-04 05:59:55.000000 performancetest-0.0.4/performancetest/test/__init__.py
--rw-rw-rw-   0        0        0     1133 2023-05-04 05:59:55.000000 performancetest-0.0.4/performancetest/test/all_property_test.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.674878 performancetest-0.0.4/performancetest/web/
--rw-rw-rw-   0        0        0       25 2023-05-05 12:26:54.000000 performancetest-0.0.4/performancetest/web/__init__.py
--rw-rw-rw-   0        0        0     1852 2023-06-21 12:46:09.000000 performancetest-0.0.4/performancetest/web/dao.py
--rw-rw-rw-   0        0        0      408 2023-06-21 10:25:13.000000 performancetest-0.0.4/performancetest/web/entity.py
--rw-rw-rw-   0        0        0     9191 2023-06-25 06:05:19.000000 performancetest-0.0.4/performancetest/web/main.py
--rw-rw-rw-   0        0        0    11864 2023-06-25 06:05:19.000000 performancetest-0.0.4/performancetest/web/util.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:48:33.642072 performancetest-0.0.4/performancetest.egg-info/
--rw-rw-rw-   0        0        0      515 2023-06-28 04:48:33.000000 performancetest-0.0.4/performancetest.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      921 2023-06-28 04:48:33.000000 performancetest-0.0.4/performancetest.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 04:48:33.000000 performancetest-0.0.4/performancetest.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       16 2023-06-28 04:48:33.000000 performancetest-0.0.4/performancetest.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 04:48:33.677520 performancetest-0.0.4/setup.cfg
--rw-rw-rw-   0        0        0      843 2023-06-28 04:48:16.000000 performancetest-0.0.4/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.875254 performancetest-1.0.3/
+-rw-rw-rw-   0        0        0      515 2023-06-28 04:44:53.873851 performancetest-1.0.3/PKG-INFO
+-rw-rw-rw-   0        0        0     4346 2023-06-27 05:36:55.000000 performancetest-1.0.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.775728 performancetest-1.0.3/performancetest/
+-rw-rw-rw-   0        0        0       49 2023-06-21 09:23:31.000000 performancetest-1.0.3/performancetest/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.846625 performancetest-1.0.3/performancetest/core/
+-rw-rw-rw-   0        0        0       25 2023-05-04 05:59:55.000000 performancetest-1.0.3/performancetest/core/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.855826 performancetest-1.0.3/performancetest/core/base/
+-rw-rw-rw-   0        0        0       25 2023-05-04 05:59:55.000000 performancetest-1.0.3/performancetest/core/base/__init__.py
+-rw-rw-rw-   0        0        0      289 2023-05-04 05:59:55.000000 performancetest-1.0.3/performancetest/core/base/actuator.py
+-rw-rw-rw-   0        0        0      325 2023-05-04 05:59:55.000000 performancetest-1.0.3/performancetest/core/base/monitor.py
+-rw-rw-rw-   0        0        0     3562 2023-06-21 12:46:09.000000 performancetest-1.0.3/performancetest/core/command.py
+-rw-rw-rw-   0        0        0     4277 2023-06-27 06:56:49.000000 performancetest-1.0.3/performancetest/core/cpu.py
+-rw-rw-rw-   0        0        0     6413 2023-06-23 08:54:45.000000 performancetest-1.0.3/performancetest/core/device.py
+-rw-rw-rw-   0        0        0     4268 2023-06-21 12:46:09.000000 performancetest-1.0.3/performancetest/core/devicebattery.py
+-rw-rw-rw-   0        0        0    18842 2023-06-25 06:05:19.000000 performancetest-1.0.3/performancetest/core/fps.py
+-rw-rw-rw-   0        0        0      678 2023-06-21 12:46:09.000000 performancetest-1.0.3/performancetest/core/global_data.py
+-rw-rw-rw-   0        0        0     3882 2023-06-27 06:56:49.000000 performancetest-1.0.3/performancetest/core/gpu.py
+-rw-rw-rw-   0        0        0     6646 2023-06-21 12:47:53.000000 performancetest-1.0.3/performancetest/core/iosperf.py
+-rw-rw-rw-   0        0        0     3928 2023-06-27 06:56:49.000000 performancetest-1.0.3/performancetest/core/memory.py
+-rw-rw-rw-   0        0        0     4315 2023-06-23 08:54:45.000000 performancetest-1.0.3/performancetest/core/snapshot.py
+-rw-rw-rw-   0        0        0     4254 2023-06-27 06:56:49.000000 performancetest-1.0.3/performancetest/core/task_handle.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.861004 performancetest-1.0.3/performancetest/test/
+-rw-rw-rw-   0        0        0       25 2023-05-04 05:59:55.000000 performancetest-1.0.3/performancetest/test/__init__.py
+-rw-rw-rw-   0        0        0     1133 2023-05-04 05:59:55.000000 performancetest-1.0.3/performancetest/test/all_property_test.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.871574 performancetest-1.0.3/performancetest/web/
+-rw-rw-rw-   0        0        0       25 2023-05-05 12:26:54.000000 performancetest-1.0.3/performancetest/web/__init__.py
+-rw-rw-rw-   0        0        0     1852 2023-06-21 12:46:09.000000 performancetest-1.0.3/performancetest/web/dao.py
+-rw-rw-rw-   0        0        0      408 2023-06-21 10:25:13.000000 performancetest-1.0.3/performancetest/web/entity.py
+-rw-rw-rw-   0        0        0     9191 2023-06-25 06:05:19.000000 performancetest-1.0.3/performancetest/web/main.py
+-rw-rw-rw-   0        0        0    11864 2023-06-25 06:05:19.000000 performancetest-1.0.3/performancetest/web/util.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:44:53.811176 performancetest-1.0.3/performancetest.egg-info/
+-rw-rw-rw-   0        0        0      515 2023-06-28 04:44:53.000000 performancetest-1.0.3/performancetest.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      921 2023-06-28 04:44:53.000000 performancetest-1.0.3/performancetest.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 04:44:53.000000 performancetest-1.0.3/performancetest.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       16 2023-06-28 04:44:53.000000 performancetest-1.0.3/performancetest.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 04:44:53.875832 performancetest-1.0.3/setup.cfg
+-rw-rw-rw-   0        0        0      841 2023-06-28 04:42:50.000000 performancetest-1.0.3/setup.py
```

### Comparing `performancetest-0.0.4/PKG-INFO` & `performancetest-1.0.3/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: performancetest
-Version: 0.0.4
+Version: 1.0.3
 Summary: Android, IOS app_performance
 Home-page: https://github.com/1033866383/perf-orange-cat
 Author: bozhou.fan
 Author-email: 15525730080@163.com
 License: UNKNOWN
 Description: UNKNOWN
 Platform: UNKNOWN
```

### Comparing `performancetest-0.0.4/README.md` & `performancetest-1.0.3/README.md`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/command.py` & `performancetest-1.0.3/performancetest/core/command.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/cpu.py` & `performancetest-1.0.3/performancetest/core/cpu.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/device.py` & `performancetest-1.0.3/performancetest/core/device.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/devicebattery.py` & `performancetest-1.0.3/performancetest/core/devicebattery.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/fps.py` & `performancetest-1.0.3/performancetest/core/fps.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/global_data.py` & `performancetest-1.0.3/performancetest/core/global_data.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/gpu.py` & `performancetest-1.0.3/performancetest/core/gpu.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/iosperf.py` & `performancetest-1.0.3/performancetest/core/iosperf.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/memory.py` & `performancetest-1.0.3/performancetest/core/memory.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/snapshot.py` & `performancetest-1.0.3/performancetest/core/snapshot.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/core/task_handle.py` & `performancetest-1.0.3/performancetest/core/task_handle.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/test/all_property_test.py` & `performancetest-1.0.3/performancetest/test/all_property_test.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/web/dao.py` & `performancetest-1.0.3/performancetest/web/dao.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/web/main.py` & `performancetest-1.0.3/performancetest/web/main.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest/web/util.py` & `performancetest-1.0.3/performancetest/web/util.py`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/performancetest.egg-info/PKG-INFO` & `performancetest-1.0.3/performancetest.egg-info/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: performancetest
-Version: 0.0.4
+Version: 1.0.3
 Summary: Android, IOS app_performance
 Home-page: https://github.com/1033866383/perf-orange-cat
 Author: bozhou.fan
 Author-email: 15525730080@163.com
 License: UNKNOWN
 Description: UNKNOWN
 Platform: UNKNOWN
```

### Comparing `performancetest-0.0.4/performancetest.egg-info/SOURCES.txt` & `performancetest-1.0.3/performancetest.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `performancetest-0.0.4/setup.py` & `performancetest-1.0.3/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 # # _*_ coding: utf-8 _*_
 from setuptools import setup, find_packages
 
 setup(
        name='performancetest',
-       version='0.0.4',
+       version='1.0.3',
        url='https://github.com/1033866383/perf-orange-cat',
        author='bozhou.fan',
        author_email='15525730080@163.com',
        description='Android, IOS app_performance',
        packages=find_packages(),
        install_requires=[],
        include_package_data=True,  # 这里添加 include_package_data 参数
        package_data={
-           'performancetest': ['web/test_result/*']
+           'performancetest': ['web/test_result']
        },
        classifiers=[
            'Development Status :: 3 - Alpha',
            'Intended Audience :: Developers',
            'License :: OSI Approved :: MIT License',
            'Programming Language :: Python :: 3',
            'Programming Language :: Python :: 3.9',
```


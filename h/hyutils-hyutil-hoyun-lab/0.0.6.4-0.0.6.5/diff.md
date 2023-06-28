# Comparing `tmp/hyutils-hyutil-hoyun-lab-0.0.6.4.tar.gz` & `tmp/hyutils-hyutil-hoyun-lab-0.0.6.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hyutils-hyutil-hoyun-lab-0.0.6.4.tar", last modified: Wed Jun 21 03:16:40 2023, max compression
+gzip compressed data, was "hyutils-hyutil-hoyun-lab-0.0.6.5.tar", last modified: Wed Jun 28 07:09:32 2023, max compression
```

## Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4.tar` & `hyutils-hyutil-hoyun-lab-0.0.6.5.tar`

### file list

```diff
@@ -1,22 +1,23 @@
-drwxrwxrwx   0        0        0        0 2023-06-21 03:16:40.908945 hyutils-hyutil-hoyun-lab-0.0.6.4/
--rw-rw-rw-   0        0        0       37 2023-06-08 03:25:08.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/LICENSE.txt
--rw-rw-rw-   0        0        0      600 2023-06-21 03:16:40.908445 hyutils-hyutil-hoyun-lab-0.0.6.4/PKG-INFO
--rw-rw-rw-   0        0        0       63 2023-06-07 07:35:00.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/README.md
--rw-rw-rw-   0        0        0      104 2023-06-07 07:28:49.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-21 03:16:40.909584 hyutils-hyutil-hoyun-lab-0.0.6.4/setup.cfg
--rw-rw-rw-   0        0        0      852 2023-06-21 03:16:17.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-21 03:16:40.888445 hyutils-hyutil-hoyun-lab-0.0.6.4/src/
-drwxrwxrwx   0        0        0        0 2023-06-21 03:16:40.902946 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/
--rw-rw-rw-   0        0        0      347 2023-06-21 03:16:17.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/__init__.py
--rw-rw-rw-   0        0        0      435 2023-01-19 02:15:34.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/appcontrol.py
--rw-rw-rw-   0        0        0      614 2023-05-30 04:04:27.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/date_time.py
--rw-rw-rw-   0        0        0     1290 2023-06-21 02:07:34.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/dirjob.py
--rw-rw-rw-   0        0        0      477 2023-06-16 04:42:56.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/filejob.py
--rw-rw-rw-   0        0        0     1086 2023-02-02 02:25:56.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/hashing.py
--rw-rw-rw-   0        0        0    15304 2023-06-20 04:05:24.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/tfrecrod_utils.py
--rw-rw-rw-   0        0        0     4046 2023-06-16 04:49:56.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/xml_util.py
-drwxrwxrwx   0        0        0        0 2023-06-21 03:16:40.907446 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/
--rw-rw-rw-   0        0        0      600 2023-06-21 03:16:40.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      522 2023-06-21 03:16:40.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-21 03:16:40.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       17 2023-06-21 03:16:40.000000 hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 07:09:32.942509 hyutils-hyutil-hoyun-lab-0.0.6.5/
+-rw-rw-rw-   0        0        0       37 2023-06-08 03:25:08.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/LICENSE.txt
+-rw-rw-rw-   0        0        0      600 2023-06-28 07:09:32.941996 hyutils-hyutil-hoyun-lab-0.0.6.5/PKG-INFO
+-rw-rw-rw-   0        0        0       63 2023-06-07 07:35:00.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/README.md
+-rw-rw-rw-   0        0        0      104 2023-06-07 07:28:49.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 07:09:32.942996 hyutils-hyutil-hoyun-lab-0.0.6.5/setup.cfg
+-rw-rw-rw-   0        0        0      852 2023-06-28 07:09:01.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:09:32.924996 hyutils-hyutil-hoyun-lab-0.0.6.5/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 07:09:32.937500 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/
+-rw-rw-rw-   0        0        0      347 2023-06-28 07:09:01.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/__init__.py
+-rw-rw-rw-   0        0        0      435 2023-01-19 02:15:34.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/appcontrol.py
+-rw-rw-rw-   0        0        0     4333 2023-06-28 05:31:55.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/augmentjob.py
+-rw-rw-rw-   0        0        0      614 2023-05-30 04:04:27.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/date_time.py
+-rw-rw-rw-   0        0        0     1471 2023-06-21 03:54:21.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/dirjob.py
+-rw-rw-rw-   0        0        0      477 2023-06-16 04:42:56.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/filejob.py
+-rw-rw-rw-   0        0        0     1086 2023-02-02 02:25:56.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/hashing.py
+-rw-rw-rw-   0        0        0    15362 2023-06-28 07:08:39.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/tfrecrod_utils.py
+-rw-rw-rw-   0        0        0     4046 2023-06-16 04:49:56.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/xml_util.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:09:32.940995 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/
+-rw-rw-rw-   0        0        0      600 2023-06-28 07:09:32.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      557 2023-06-28 07:09:32.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:09:32.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 07:09:32.000000 hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/top_level.txt
```

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/PKG-INFO` & `hyutils-hyutil-hoyun-lab-0.0.6.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hyutils-hyutil-hoyun-lab
-Version: 0.0.6.4
+Version: 0.0.6.5
 Summary: Hoyun Lab Python Utils
 Home-page: https://www.hoyun.co.kr
 Author: nohgan im
 Author-email: fory2k@hoyun.co.kr
 License: MIT
 Project-URL: Bug Tracker, https://github.com/schooldevops/python-tutorials/issues
 Classifier: Programming Language :: Python :: 3
```

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/setup.py` & `hyutils-hyutil-hoyun-lab-0.0.6.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
     
 
 setuptools.setup(
     name="hyutils-hyutil-hoyun-lab",
-    version="0.0.6.4",
+    version="0.0.6.5",
     url="https://www.hoyun.co.kr",
     license="MIT",
     author="nohgan im",
     author_email="fory2k@hoyun.co.kr",
     description="Hoyun Lab Python Utils",
     long_description=long_description,
     long_description_content_type="text/markdown",
```

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/date_time.py` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/date_time.py`

 * *Files identical despite different names*

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/dirjob.py` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/dirjob.py`

 * *Files 20% similar despite different names*

```diff
@@ -12,17 +12,19 @@
     for file in os.listdir(path):
         if os.path.isfile(os.path.join(path, file)):
             extension = os.path.splitext(file)[1]
             if extension == ext:
                 yield file
 
 def files_ext_sub(path, ext):
+    # path로 지정된 경로에 있는 서브디렉토리를 포함한 모든 디렉토리에 있는 파일들을 리턴.
     for root, dirs, files in os.walk(path):
         for file in files:
             extension = os.path.splitext(file)[1]
+            # 특정 확장자인 경우만 리턴함.
             if extension == ext:
                 file_path = os.path.join(root, file)
                 yield file_path, root
 
 def dirs(path):
     for file in os.listdir(path):
         if os.path.isdir(os.path.join(path, file)):
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/hashing.py` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/hashing.py`

 * *Files identical despite different names*

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/tfrecrod_utils.py` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/tfrecrod_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -336,15 +336,16 @@
             xmin = tf.sparse.to_dense(xmin, default_value=0.0).numpy()
             xmax = tf.sparse.to_dense(xmax, default_value=0.0).numpy()
             ymin = tf.sparse.to_dense(ymin, default_value=0.0).numpy()
             ymax = tf.sparse.to_dense(ymax, default_value=0.0).numpy()
             label = tf.sparse.to_dense(label, default_value='???').numpy()
 
             if mode == 'print':
-                print(f'filename:{filename}  label:{label[idx]} > xmin:{xmin[idx]} xmax:{xmax[idx]} ymin:{ymin[idx]} ymax:{ymax[idx]}, h:{h} w:{w} c:{c}')
+                for idx in np.arange(0, len(label)):
+                    print(f'filename:{filename}  label:{label[idx]} > xmin:{xmin[idx]} xmax:{xmax[idx]} ymin:{ymin[idx]} ymax:{ymax[idx]}, h:{h} w:{w} c:{c}')
                 if c != 3:
                     print('---------------------- invalid image\'s channel size ----------------------')
                     cv2.waitKey(0)
             else:
                 # 레이블 출력
                 for idx in np.arange(0, len(label)):
                     print(f'filename:{filename}  label:{label[idx]} > xmin:{xmin[idx]} xmax:{xmax[idx]} ymin:{ymin[idx]} ymax:{ymax[idx]}')
```

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutil_hoyun_lab/xml_util.py` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutil_hoyun_lab/xml_util.py`

 * *Files identical despite different names*

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/PKG-INFO` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hyutils-hyutil-hoyun-lab
-Version: 0.0.6.4
+Version: 0.0.6.5
 Summary: Hoyun Lab Python Utils
 Home-page: https://www.hoyun.co.kr
 Author: nohgan im
 Author-email: fory2k@hoyun.co.kr
 License: MIT
 Project-URL: Bug Tracker, https://github.com/schooldevops/python-tutorials/issues
 Classifier: Programming Language :: Python :: 3
```

### Comparing `hyutils-hyutil-hoyun-lab-0.0.6.4/src/hyutils_hyutil_hoyun_lab.egg-info/SOURCES.txt` & `hyutils-hyutil-hoyun-lab-0.0.6.5/src/hyutils_hyutil_hoyun_lab.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 LICENSE.txt
 README.md
 pyproject.toml
 setup.py
 src/hyutil_hoyun_lab/__init__.py
 src/hyutil_hoyun_lab/appcontrol.py
+src/hyutil_hoyun_lab/augmentjob.py
 src/hyutil_hoyun_lab/date_time.py
 src/hyutil_hoyun_lab/dirjob.py
 src/hyutil_hoyun_lab/filejob.py
 src/hyutil_hoyun_lab/hashing.py
 src/hyutil_hoyun_lab/tfrecrod_utils.py
 src/hyutil_hoyun_lab/xml_util.py
 src/hyutils_hyutil_hoyun_lab.egg-info/PKG-INFO
```


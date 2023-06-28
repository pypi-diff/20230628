# Comparing `tmp/simple_aws_ec2-0.6.1.tar.gz` & `tmp/simple_aws_ec2-0.6.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "simple_aws_ec2-0.6.1.tar", last modified: Wed Jun 28 14:15:28 2023, max compression
+gzip compressed data, was "simple_aws_ec2-0.6.2.tar", last modified: Wed Jun 28 15:03:26 2023, max compression
```

## Comparing `simple_aws_ec2-0.6.1.tar` & `simple_aws_ec2-0.6.2.tar`

### file list

```diff
@@ -1,35 +1,35 @@
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:15:28.257995 simple_aws_ec2-0.6.1/
--rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-15 19:02:16.000000 simple_aws_ec2-0.6.1/AUTHORS.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     1124 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.1/LICENSE.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      322 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.1/MANIFEST.in
--rw-r--r--   0 sanhehu    (501) staff       (20)     6784 2023-06-28 14:15:28.257852 simple_aws_ec2-0.6.1/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     5722 2023-06-14 19:01:43.000000 simple_aws_ec2-0.6.1/README.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     3237 2023-06-28 14:12:49.000000 simple_aws_ec2-0.6.1/release-history.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)      284 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.1/requirements-dev.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      621 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.1/requirements-doc.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      228 2023-06-14 13:05:19.000000 simple_aws_ec2-0.6.1/requirements-test.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       48 2023-06-14 12:12:36.000000 simple_aws_ec2-0.6.1/requirements.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 14:15:28.258035 simple_aws_ec2-0.6.1/setup.cfg
--rw-r--r--   0 sanhehu    (501) staff       (20)     7513 2023-05-03 14:54:47.000000 simple_aws_ec2-0.6.1/setup.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:15:28.255499 simple_aws_ec2-0.6.1/simple_aws_ec2/
--rw-r--r--   0 sanhehu    (501) staff       (20)      398 2023-05-03 16:05:44.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 14:11:41.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/_version.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     1438 2023-06-28 14:07:58.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/api.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:15:28.256402 simple_aws_ec2-0.6.1/simple_aws_ec2/docs/
--rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/docs/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)    34386 2023-06-28 14:04:52.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/ec2.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     5419 2023-06-28 14:10:38.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/ec2_metadata_cache.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       69 2023-06-15 22:05:33.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/exc.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:15:28.256888 simple_aws_ec2-0.6.1/simple_aws_ec2/vendor/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-15 18:28:54.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/vendor/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2351 2023-06-15 18:56:04.000000 simple_aws_ec2-0.6.1/simple_aws_ec2/vendor/waiter.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:15:28.256277 simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/
--rw-r--r--   0 sanhehu    (501) staff       (20)     6784 2023-06-28 14:15:28.000000 simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)      669 2023-06-28 14:15:28.000000 simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/SOURCES.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 14:15:28.000000 simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/dependency_links.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      264 2023-06-28 14:15:28.000000 simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/requires.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       15 2023-06-28 14:15:28.000000 simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/top_level.txt
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:15:28.257569 simple_aws_ec2-0.6.1/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)     3143 2023-06-28 14:08:02.000000 simple_aws_ec2-0.6.1/tests/test_api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     8301 2023-06-19 18:43:04.000000 simple_aws_ec2-0.6.1/tests/test_ec2.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      588 2023-06-28 14:11:04.000000 simple_aws_ec2-0.6.1/tests/test_ec2_metadata_cache.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:03:26.890377 simple_aws_ec2-0.6.2/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-15 19:02:16.000000 simple_aws_ec2-0.6.2/AUTHORS.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1124 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.2/LICENSE.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      322 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.2/MANIFEST.in
+-rw-r--r--   0 sanhehu    (501) staff       (20)     6784 2023-06-28 15:03:26.890235 simple_aws_ec2-0.6.2/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5722 2023-06-14 19:01:43.000000 simple_aws_ec2-0.6.2/README.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3431 2023-06-28 15:03:00.000000 simple_aws_ec2-0.6.2/release-history.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)      284 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.2/requirements-dev.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      621 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.2/requirements-doc.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      228 2023-06-14 13:05:19.000000 simple_aws_ec2-0.6.2/requirements-test.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       48 2023-06-14 12:12:36.000000 simple_aws_ec2-0.6.2/requirements.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 15:03:26.890419 simple_aws_ec2-0.6.2/setup.cfg
+-rw-r--r--   0 sanhehu    (501) staff       (20)     7513 2023-05-03 14:54:47.000000 simple_aws_ec2-0.6.2/setup.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:03:26.887542 simple_aws_ec2-0.6.2/simple_aws_ec2/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      227 2023-06-28 14:17:05.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 15:02:29.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/_version.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1438 2023-06-28 14:07:58.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:03:26.888515 simple_aws_ec2-0.6.2/simple_aws_ec2/docs/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-05-03 14:52:18.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/docs/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)    34386 2023-06-28 14:04:52.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/ec2.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5598 2023-06-28 15:02:19.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/ec2_metadata_cache.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       69 2023-06-15 22:05:33.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/exc.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:03:26.888953 simple_aws_ec2-0.6.2/simple_aws_ec2/vendor/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-15 18:28:54.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/vendor/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2351 2023-06-15 18:56:04.000000 simple_aws_ec2-0.6.2/simple_aws_ec2/vendor/waiter.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:03:26.888381 simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     6784 2023-06-28 15:03:26.000000 simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)      669 2023-06-28 15:03:26.000000 simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/SOURCES.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 15:03:26.000000 simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/dependency_links.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      264 2023-06-28 15:03:26.000000 simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/requires.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       15 2023-06-28 15:03:26.000000 simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/top_level.txt
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:03:26.889840 simple_aws_ec2-0.6.2/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3143 2023-06-28 14:08:02.000000 simple_aws_ec2-0.6.2/tests/test_api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     8301 2023-06-19 18:43:04.000000 simple_aws_ec2-0.6.2/tests/test_ec2.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      588 2023-06-28 14:11:04.000000 simple_aws_ec2-0.6.2/tests/test_ec2_metadata_cache.py
```

### Comparing `simple_aws_ec2-0.6.1/AUTHORS.rst` & `simple_aws_ec2-0.6.2/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/LICENSE.txt` & `simple_aws_ec2-0.6.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/PKG-INFO` & `simple_aws_ec2-0.6.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: simple_aws_ec2
-Version: 0.6.1
+Version: 0.6.2
 Summary: Simple AWS EC2 devtool.
 Home-page: https://github.com/MacHu-GWU/simple_aws_ec2-project
-Download-URL: https://pypi.python.org/pypi/simple_aws_ec2/0.6.1#downloads
+Download-URL: https://pypi.python.org/pypi/simple_aws_ec2/0.6.2#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Unknown
 License: MIT
 Platform: Windows
 Platform: MacOS
 Platform: Unix
```

### Comparing `simple_aws_ec2-0.6.1/README.rst` & `simple_aws_ec2-0.6.2/README.rst`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/release-history.rst` & `simple_aws_ec2-0.6.2/release-history.rst`

 * *Files 12% similar despite different names*

```diff
@@ -11,14 +11,21 @@
 **Minor Improvements**
 
 **Bugfixes**
 
 **Miscellaneous**
 
 
+0.6.2 (2023-06-28)
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+**Bugfixes**
+
+- fix a bug that ``EC2MetadataCache.get_xyz()`` methods always return ``None``.
+
+
 0.6.1 (2023-06-28)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Features and Improvements**
 
 - add :class:`~simple_aws_ec2.ec2_metadata_cache.EC2MetadataCache`.
```

### Comparing `simple_aws_ec2-0.6.1/requirements-doc.txt` & `simple_aws_ec2-0.6.2/requirements-doc.txt`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/setup.py` & `simple_aws_ec2-0.6.2/setup.py`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/simple_aws_ec2/api.py` & `simple_aws_ec2-0.6.2/simple_aws_ec2/api.py`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/simple_aws_ec2/ec2.py` & `simple_aws_ec2-0.6.2/simple_aws_ec2/ec2.py`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/simple_aws_ec2/ec2_metadata_cache.py` & `simple_aws_ec2-0.6.2/simple_aws_ec2/ec2_metadata_cache.py`

 * *Files 8% similar despite different names*

```diff
@@ -84,14 +84,15 @@
         """
         Get EC2 instance id.
         """
         if ignore_cache is True or self._instance_id is None or self.is_expired():
             self._instance_id = Ec2Instance.get_instance_id()
             if refresh_cache:
                 self.dump()
+            return self._instance_id
         else:
             return self._instance_id
 
     def get_instance_type(
         self,
         refresh_cache: bool = True,
         ignore_cache: bool = False,
@@ -99,14 +100,15 @@
         """
         Get EC2 instance type.
         """
         if ignore_cache is True or self._instance_type is None or self.is_expired():
             self._instance_type = Ec2Instance.get_instance_type()
             if refresh_cache:
                 self.dump()
+            return self._instance_type
         else:
             return self._instance_type
 
     def get_region(
         self,
         refresh_cache: bool = True,
         ignore_cache: bool = False,
@@ -114,14 +116,15 @@
         """
         Get EC2 placement region.
         """
         if ignore_cache is True or self._region is None or self.is_expired():
             self._region = Ec2Instance.get_placement_region()
             if refresh_cache:
                 self.dump()
+            return self._region
         else:
             return self._region
 
     def get_public_ipv4(
         self,
         refresh_cache: bool = True,
         ignore_cache: bool = False,
@@ -129,14 +132,15 @@
         """
         Get EC2 public IPv4 address.
         """
         if ignore_cache is True or self._public_ipv4 is None or self.is_expired():
             self._public_ipv4 = Ec2Instance.get_public_ipv4()
             if refresh_cache:
                 self.dump()
+            return self._public_ipv4
         else:
             return self._public_ipv4
 
     def get_iam_info(
         self,
         refresh_cache: bool = True,
         ignore_cache: bool = False,
@@ -153,14 +157,15 @@
                 "InstanceProfileArn" : "arn:aws:iam::111122223333:instance-profile/profile-name",
             }
         """
         if ignore_cache is True or self._iam_info is None or self.is_expired():
             self._iam_info = Ec2Instance.get_iam_info()
             if refresh_cache:
                 self.dump()
+            return self._iam_info
         else:
             return self._iam_info
 
     def get_boto_ses_from_ec2_inside(
         self,
         refresh_cache: bool = True,
         ignore_cache: bool = False,
```

### Comparing `simple_aws_ec2-0.6.1/simple_aws_ec2/vendor/waiter.py` & `simple_aws_ec2-0.6.2/simple_aws_ec2/vendor/waiter.py`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/PKG-INFO` & `simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: simple-aws-ec2
-Version: 0.6.1
+Version: 0.6.2
 Summary: Simple AWS EC2 devtool.
 Home-page: https://github.com/MacHu-GWU/simple_aws_ec2-project
-Download-URL: https://pypi.python.org/pypi/simple_aws_ec2/0.6.1#downloads
+Download-URL: https://pypi.python.org/pypi/simple_aws_ec2/0.6.2#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Unknown
 License: MIT
 Platform: Windows
 Platform: MacOS
 Platform: Unix
```

### Comparing `simple_aws_ec2-0.6.1/simple_aws_ec2.egg-info/SOURCES.txt` & `simple_aws_ec2-0.6.2/simple_aws_ec2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/tests/test_api.py` & `simple_aws_ec2-0.6.2/tests/test_api.py`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/tests/test_ec2.py` & `simple_aws_ec2-0.6.2/tests/test_ec2.py`

 * *Files identical despite different names*

### Comparing `simple_aws_ec2-0.6.1/tests/test_ec2_metadata_cache.py` & `simple_aws_ec2-0.6.2/tests/test_ec2_metadata_cache.py`

 * *Files identical despite different names*


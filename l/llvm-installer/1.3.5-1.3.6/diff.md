# Comparing `tmp/llvm-installer-1.3.5.tar.gz` & `tmp/llvm-installer-1.3.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "llvm-installer-1.3.5.tar", last modified: Fri Jun 23 22:47:48 2023, max compression
+gzip compressed data, was "llvm-installer-1.3.6.tar", last modified: Wed Jun 28 03:10:11 2023, max compression
```

## Comparing `llvm-installer-1.3.5.tar` & `llvm-installer-1.3.6.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-23 22:47:48.920337 llvm-installer-1.3.5/
--rw-r--r--   0 mikhail    (503) staff       (20)    11358 2022-05-26 15:06:09.000000 llvm-installer-1.3.5/LICENSE
--rw-r--r--   0 mikhail    (503) staff       (20)      989 2023-06-23 22:47:48.920210 llvm-installer-1.3.5/PKG-INFO
--rw-r--r--   0 mikhail    (503) staff       (20)      643 2022-07-07 03:18:16.000000 llvm-installer-1.3.5/README.md
--rw-r--r--   0 mikhail    (503) staff       (20)       38 2023-06-23 22:47:48.920379 llvm-installer-1.3.5/setup.cfg
--rw-r--r--   0 mikhail    (503) staff       (20)     2235 2023-06-23 22:47:02.000000 llvm-installer-1.3.5/setup.py
-drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-23 22:47:48.917868 llvm-installer-1.3.5/src/
-drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-23 22:47:48.919042 llvm-installer-1.3.5/src/llvm_installer/
--rw-r--r--   0 mikhail    (503) staff       (20)    11455 2022-08-17 05:24:37.000000 llvm-installer-1.3.5/src/llvm_installer/__init__.py
--rw-r--r--   0 mikhail    (503) staff       (20)     1641 2022-07-07 03:54:15.000000 llvm-installer-1.3.5/src/llvm_installer/__main__.py
--rw-r--r--   0 mikhail    (503) staff       (20)        0 2022-05-26 15:06:09.000000 llvm-installer-1.3.5/src/llvm_installer/py.typed
--rw-r--r--   0 mikhail    (503) staff       (20)    95017 2023-06-23 21:54:16.000000 llvm-installer-1.3.5/src/llvm_installer/release_tags.json
-drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-23 22:47:48.920014 llvm-installer-1.3.5/src/llvm_installer.egg-info/
--rw-r--r--   0 mikhail    (503) staff       (20)      989 2023-06-23 22:47:48.000000 llvm-installer-1.3.5/src/llvm_installer.egg-info/PKG-INFO
--rw-r--r--   0 mikhail    (503) staff       (20)      407 2023-06-23 22:47:48.000000 llvm-installer-1.3.5/src/llvm_installer.egg-info/SOURCES.txt
--rw-r--r--   0 mikhail    (503) staff       (20)        1 2023-06-23 22:47:48.000000 llvm-installer-1.3.5/src/llvm_installer.egg-info/dependency_links.txt
--rw-r--r--   0 mikhail    (503) staff       (20)       64 2023-06-23 22:47:48.000000 llvm-installer-1.3.5/src/llvm_installer.egg-info/entry_points.txt
--rw-r--r--   0 mikhail    (503) staff       (20)       86 2023-06-23 22:47:48.000000 llvm-installer-1.3.5/src/llvm_installer.egg-info/requires.txt
--rw-r--r--   0 mikhail    (503) staff       (20)       15 2023-06-23 22:47:48.000000 llvm-installer-1.3.5/src/llvm_installer.egg-info/top_level.txt
+drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-28 03:10:11.942002 llvm-installer-1.3.6/
+-rw-r--r--   0 mikhail    (503) staff       (20)    11358 2022-05-26 15:06:09.000000 llvm-installer-1.3.6/LICENSE
+-rw-r--r--   0 mikhail    (503) staff       (20)      989 2023-06-28 03:10:11.941889 llvm-installer-1.3.6/PKG-INFO
+-rw-r--r--   0 mikhail    (503) staff       (20)      643 2022-07-07 03:18:16.000000 llvm-installer-1.3.6/README.md
+-rw-r--r--   0 mikhail    (503) staff       (20)       38 2023-06-28 03:10:11.942047 llvm-installer-1.3.6/setup.cfg
+-rw-r--r--   0 mikhail    (503) staff       (20)     2235 2023-06-28 03:05:44.000000 llvm-installer-1.3.6/setup.py
+drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-28 03:10:11.939394 llvm-installer-1.3.6/src/
+drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-28 03:10:11.940742 llvm-installer-1.3.6/src/llvm_installer/
+-rw-r--r--   0 mikhail    (503) staff       (20)    11455 2022-08-17 05:24:37.000000 llvm-installer-1.3.6/src/llvm_installer/__init__.py
+-rw-r--r--   0 mikhail    (503) staff       (20)     1641 2022-07-07 03:54:15.000000 llvm-installer-1.3.6/src/llvm_installer/__main__.py
+-rw-r--r--   0 mikhail    (503) staff       (20)        0 2022-05-26 15:06:09.000000 llvm-installer-1.3.6/src/llvm_installer/py.typed
+-rw-r--r--   0 mikhail    (503) staff       (20)    98090 2023-06-28 02:52:23.000000 llvm-installer-1.3.6/src/llvm_installer/release_tags.json
+drwxr-xr-x   0 mikhail    (503) staff       (20)        0 2023-06-28 03:10:11.941711 llvm-installer-1.3.6/src/llvm_installer.egg-info/
+-rw-r--r--   0 mikhail    (503) staff       (20)      989 2023-06-28 03:10:11.000000 llvm-installer-1.3.6/src/llvm_installer.egg-info/PKG-INFO
+-rw-r--r--   0 mikhail    (503) staff       (20)      407 2023-06-28 03:10:11.000000 llvm-installer-1.3.6/src/llvm_installer.egg-info/SOURCES.txt
+-rw-r--r--   0 mikhail    (503) staff       (20)        1 2023-06-28 03:10:11.000000 llvm-installer-1.3.6/src/llvm_installer.egg-info/dependency_links.txt
+-rw-r--r--   0 mikhail    (503) staff       (20)       64 2023-06-28 03:10:11.000000 llvm-installer-1.3.6/src/llvm_installer.egg-info/entry_points.txt
+-rw-r--r--   0 mikhail    (503) staff       (20)       86 2023-06-28 03:10:11.000000 llvm-installer-1.3.6/src/llvm_installer.egg-info/requires.txt
+-rw-r--r--   0 mikhail    (503) staff       (20)       15 2023-06-28 03:10:11.000000 llvm-installer-1.3.6/src/llvm_installer.egg-info/top_level.txt
```

### Comparing `llvm-installer-1.3.5/LICENSE` & `llvm-installer-1.3.6/LICENSE`

 * *Files identical despite different names*

### Comparing `llvm-installer-1.3.5/PKG-INFO` & `llvm-installer-1.3.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: llvm-installer
-Version: 1.3.5
+Version: 1.3.6
 Summary: Allows installing pre-built LLVM packages for various operating systems
 Home-page: https://github.com/yugabyte/llvm-installer
 Author: Mikhail Bautin
 Author-email: mbautin@users.noreply.github.com
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
```

### Comparing `llvm-installer-1.3.5/README.md` & `llvm-installer-1.3.6/README.md`

 * *Files identical despite different names*

### Comparing `llvm-installer-1.3.5/setup.py` & `llvm-installer-1.3.6/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -21,15 +21,15 @@
     from os import path
     this_directory = path.abspath(path.dirname(__file__))
     with open(path.join(this_directory, 'README.md'), encoding='utf-8') as readme_file:
         long_description = readme_file.read()
 
     setup(
         name='llvm-installer',
-        version='1.3.5',
+        version='1.3.6',
         url='https://github.com/yugabyte/llvm-installer',
         author='Mikhail Bautin',
         author_email='mbautin@users.noreply.github.com',
         description='Allows installing pre-built LLVM packages for various operating systems',
         packages=find_packages(where='src'),
         package_dir={"": "src"},
         package_data={'llvm_installer': ['py.typed', 'release_tags.json']},
```

### Comparing `llvm-installer-1.3.5/src/llvm_installer/__init__.py` & `llvm-installer-1.3.6/src/llvm_installer/__init__.py`

 * *Files identical despite different names*

### Comparing `llvm-installer-1.3.5/src/llvm_installer/__main__.py` & `llvm-installer-1.3.6/src/llvm_installer/__main__.py`

 * *Files identical despite different names*

### Comparing `llvm-installer-1.3.5/src/llvm_installer/release_tags.json` & `llvm-installer-1.3.6/src/llvm_installer/release_tags.json`

 * *Files 1% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.984375%*

 * *Differences: {"'parsed_tags'": "{insert: [(160, OrderedDict([('architecture', 'x86_64'), "*

 * *                  "('is_old_tag_without_os_and_arch', False), ('major_version', 16), "*

 * *                  "('minor_version', 0), ('patch_version', 6), ('sha1_prefix', 'bdefb807'), "*

 * *                  "('short_os_name_and_version', 'almalinux8'), ('tag', "*

 * *                  "'v16.0.6-yb-2-1687902823-bdefb807-almalinux8-x86_64'), ('timestamp', "*

 * *                  "'1687902823'), ('version', '16.0.6'), ('version_suffix', 'yb-2'), "*

 * *   […]*

```diff
@@ -2237,14 +2237,28 @@
             "tag": "v16.0.6-yb-1-1687337167-5c765d34-almalinux8-x86_64",
             "timestamp": "1687337167",
             "version": "16.0.6",
             "version_suffix": "yb-1",
             "yb_suffix_version": 1
         },
         {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "bdefb807",
+            "short_os_name_and_version": "almalinux8",
+            "tag": "v16.0.6-yb-2-1687902823-bdefb807-almalinux8-x86_64",
+            "timestamp": "1687902823",
+            "version": "16.0.6",
+            "version_suffix": "yb-2",
+            "yb_suffix_version": 2
+        },
+        {
             "architecture": "aarch64",
             "is_old_tag_without_os_and_arch": false,
             "major_version": 16,
             "minor_version": 0,
             "patch_version": 5,
             "sha1_prefix": "0eb3e9aa",
             "short_os_name_and_version": "almalinux9",
@@ -2349,14 +2363,28 @@
             "tag": "v16.0.6-yb-1-1687339027-5c765d34-almalinux9-x86_64",
             "timestamp": "1687339027",
             "version": "16.0.6",
             "version_suffix": "yb-1",
             "yb_suffix_version": 1
         },
         {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "bdefb807",
+            "short_os_name_and_version": "almalinux9",
+            "tag": "v16.0.6-yb-2-1687904354-bdefb807-almalinux9-x86_64",
+            "timestamp": "1687904354",
+            "version": "16.0.6",
+            "version_suffix": "yb-2",
+            "yb_suffix_version": 2
+        },
+        {
             "architecture": "aarch64",
             "is_old_tag_without_os_and_arch": false,
             "major_version": 16,
             "minor_version": 0,
             "patch_version": 0,
             "sha1_prefix": "7ea85397",
             "short_os_name_and_version": "centos7",
@@ -2545,14 +2573,56 @@
             "tag": "v16.0.6-yb-1-1687335217-5c765d34-centos7-x86_64",
             "timestamp": "1687335217",
             "version": "16.0.6",
             "version_suffix": "yb-1",
             "yb_suffix_version": 1
         },
         {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "5c765d34",
+            "short_os_name_and_version": "centos7",
+            "tag": "v16.0.6-yb-1-1687897499-5c765d34-centos7-x86_64",
+            "timestamp": "1687897499",
+            "version": "16.0.6",
+            "version_suffix": "yb-1",
+            "yb_suffix_version": 1
+        },
+        {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "5c765d34",
+            "short_os_name_and_version": "centos7",
+            "tag": "v16.0.6-yb-1-1687897517-5c765d34-centos7-x86_64",
+            "timestamp": "1687897517",
+            "version": "16.0.6",
+            "version_suffix": "yb-1",
+            "yb_suffix_version": 1
+        },
+        {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "bdefb807",
+            "short_os_name_and_version": "centos7",
+            "tag": "v16.0.6-yb-2-1687901233-bdefb807-centos7-x86_64",
+            "timestamp": "1687901233",
+            "version": "16.0.6",
+            "version_suffix": "yb-2",
+            "yb_suffix_version": 2
+        },
+        {
             "architecture": "arm64",
             "is_old_tag_without_os_and_arch": false,
             "major_version": 16,
             "minor_version": 0,
             "patch_version": 0,
             "sha1_prefix": "7ea85397",
             "short_os_name_and_version": "macos",
@@ -2881,14 +2951,28 @@
             "tag": "v16.0.6-yb-1-1687340900-5c765d34-ubuntu20.04-x86_64",
             "timestamp": "1687340900",
             "version": "16.0.6",
             "version_suffix": "yb-1",
             "yb_suffix_version": 1
         },
         {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "bdefb807",
+            "short_os_name_and_version": "ubuntu20.04",
+            "tag": "v16.0.6-yb-2-1687905888-bdefb807-ubuntu20.04-x86_64",
+            "timestamp": "1687905888",
+            "version": "16.0.6",
+            "version_suffix": "yb-2",
+            "yb_suffix_version": 2
+        },
+        {
             "architecture": "aarch64",
             "is_old_tag_without_os_and_arch": false,
             "major_version": 16,
             "minor_version": 0,
             "patch_version": 0,
             "sha1_prefix": "7ea85397",
             "short_os_name_and_version": "ubuntu22.04",
@@ -3033,10 +3117,24 @@
             "sha1_prefix": "5c765d34",
             "short_os_name_and_version": "ubuntu22.04",
             "tag": "v16.0.6-yb-1-1687342813-5c765d34-ubuntu22.04-x86_64",
             "timestamp": "1687342813",
             "version": "16.0.6",
             "version_suffix": "yb-1",
             "yb_suffix_version": 1
+        },
+        {
+            "architecture": "x86_64",
+            "is_old_tag_without_os_and_arch": false,
+            "major_version": 16,
+            "minor_version": 0,
+            "patch_version": 6,
+            "sha1_prefix": "bdefb807",
+            "short_os_name_and_version": "ubuntu22.04",
+            "tag": "v16.0.6-yb-2-1687907456-bdefb807-ubuntu22.04-x86_64",
+            "timestamp": "1687907456",
+            "version": "16.0.6",
+            "version_suffix": "yb-2",
+            "yb_suffix_version": 2
         }
     ]
 }
```

### Comparing `llvm-installer-1.3.5/src/llvm_installer.egg-info/PKG-INFO` & `llvm-installer-1.3.6/src/llvm_installer.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: llvm-installer
-Version: 1.3.5
+Version: 1.3.6
 Summary: Allows installing pre-built LLVM packages for various operating systems
 Home-page: https://github.com/yugabyte/llvm-installer
 Author: Mikhail Bautin
 Author-email: mbautin@users.noreply.github.com
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
```


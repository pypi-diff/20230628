# Comparing `tmp/phdimporter-0.0.2.tar.gz` & `tmp/phdimporter-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "phdimporter-0.0.2.tar", last modified: Wed Jun 28 02:29:07 2023, max compression
+gzip compressed data, was "phdimporter-0.0.3.tar", last modified: Wed Jun 28 03:07:44 2023, max compression
```

## Comparing `phdimporter-0.0.2.tar` & `phdimporter-0.0.3.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 02:29:07.464065 phdimporter-0.0.2/
--rw-r--r--   0 adrea      (502) staff       (20)       78 2023-05-27 02:34:07.000000 phdimporter-0.0.2/.gitignore
--rw-r--r--   0 adrea      (502) staff       (20)     1062 2023-05-27 02:29:55.000000 phdimporter-0.0.2/LICENSE.md
--rw-r--r--   0 adrea      (502) staff       (20)     2164 2023-06-28 02:29:07.463921 phdimporter-0.0.2/PKG-INFO
--rw-r--r--   0 adrea      (502) staff       (20)     1710 2023-05-27 02:29:04.000000 phdimporter-0.0.2/README.md
-drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 02:29:07.461618 phdimporter-0.0.2/app/
-drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 02:29:07.462999 phdimporter-0.0.2/app/phdimporter/
--rw-r--r--   0 adrea      (502) staff       (20)       91 2023-05-27 02:27:42.000000 phdimporter-0.0.2/app/phdimporter/__init__.py
--rwxr-xr-x   0 adrea      (502) staff       (20)     7851 2023-06-28 02:18:06.000000 phdimporter-0.0.2/app/phdimporter/phd.py
-drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 02:29:07.463726 phdimporter-0.0.2/app/phdimporter.egg-info/
--rw-r--r--   0 adrea      (502) staff       (20)     2164 2023-06-28 02:29:07.000000 phdimporter-0.0.2/app/phdimporter.egg-info/PKG-INFO
--rw-r--r--   0 adrea      (502) staff       (20)      285 2023-06-28 02:29:07.000000 phdimporter-0.0.2/app/phdimporter.egg-info/SOURCES.txt
--rw-r--r--   0 adrea      (502) staff       (20)        1 2023-06-28 02:29:07.000000 phdimporter-0.0.2/app/phdimporter.egg-info/dependency_links.txt
--rw-r--r--   0 adrea      (502) staff       (20)       20 2023-06-28 02:29:07.000000 phdimporter-0.0.2/app/phdimporter.egg-info/requires.txt
--rw-r--r--   0 adrea      (502) staff       (20)       12 2023-06-28 02:29:07.000000 phdimporter-0.0.2/app/phdimporter.egg-info/top_level.txt
--rw-r--r--   0 adrea      (502) staff       (20)       38 2023-06-28 02:29:07.464114 phdimporter-0.0.2/setup.cfg
--rw-r--r--   0 adrea      (502) staff       (20)      782 2023-06-28 02:18:13.000000 phdimporter-0.0.2/setup.py
+drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 03:07:44.107417 phdimporter-0.0.3/
+-rw-r--r--   0 adrea      (502) staff       (20)       78 2023-05-27 02:34:07.000000 phdimporter-0.0.3/.gitignore
+-rw-r--r--   0 adrea      (502) staff       (20)     1062 2023-05-27 02:29:55.000000 phdimporter-0.0.3/LICENSE.md
+-rw-r--r--   0 adrea      (502) staff       (20)     2253 2023-06-28 03:07:44.107261 phdimporter-0.0.3/PKG-INFO
+-rw-r--r--   0 adrea      (502) staff       (20)     1799 2023-06-28 03:07:06.000000 phdimporter-0.0.3/README.md
+drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 03:07:44.104875 phdimporter-0.0.3/app/
+drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 03:07:44.106044 phdimporter-0.0.3/app/phdimporter/
+-rw-r--r--   0 adrea      (502) staff       (20)       91 2023-05-27 02:27:42.000000 phdimporter-0.0.3/app/phdimporter/__init__.py
+-rwxr-xr-x   0 adrea      (502) staff       (20)     7908 2023-06-28 02:45:36.000000 phdimporter-0.0.3/app/phdimporter/phd.py
+drwxr-xr-x   0 adrea      (502) staff       (20)        0 2023-06-28 03:07:44.107055 phdimporter-0.0.3/app/phdimporter.egg-info/
+-rw-r--r--   0 adrea      (502) staff       (20)     2253 2023-06-28 03:07:44.000000 phdimporter-0.0.3/app/phdimporter.egg-info/PKG-INFO
+-rw-r--r--   0 adrea      (502) staff       (20)      285 2023-06-28 03:07:44.000000 phdimporter-0.0.3/app/phdimporter.egg-info/SOURCES.txt
+-rw-r--r--   0 adrea      (502) staff       (20)        1 2023-06-28 03:07:44.000000 phdimporter-0.0.3/app/phdimporter.egg-info/dependency_links.txt
+-rw-r--r--   0 adrea      (502) staff       (20)       20 2023-06-28 03:07:44.000000 phdimporter-0.0.3/app/phdimporter.egg-info/requires.txt
+-rw-r--r--   0 adrea      (502) staff       (20)       12 2023-06-28 03:07:44.000000 phdimporter-0.0.3/app/phdimporter.egg-info/top_level.txt
+-rw-r--r--   0 adrea      (502) staff       (20)       38 2023-06-28 03:07:44.107469 phdimporter-0.0.3/setup.cfg
+-rw-r--r--   0 adrea      (502) staff       (20)      782 2023-06-28 03:05:45.000000 phdimporter-0.0.3/setup.py
```

### Comparing `phdimporter-0.0.2/LICENSE.md` & `phdimporter-0.0.3/LICENSE.md`

 * *Files identical despite different names*

### Comparing `phdimporter-0.0.2/PKG-INFO` & `phdimporter-0.0.3/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: phdimporter
-Version: 0.0.2
+Version: 0.0.3
 Summary: PicoHarp .PhD file importer
 Home-page: https://github.com/adreasnow/picoharp-phd
 Author: Adrea Snow
 Author-email: adrea.snow@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -19,14 +19,16 @@
 
 The layout of the file is as documented in the [PicoHarp 300 manual](http://ridl.cfd.rit.edu/products/manuals/PicoQuant/PicoHarp%20300%20v2.3/manual/Manual.pdf) in section 8.2.1 (pages 56-58).
 
 Both of these are easy to modify, however the scope of this projec tis limited to our usage case.
 
 The module also loads `.txt` files which are the copy-pasted data from the PicoHarp software. This is primary way our research group has extracted data in the past, so it makes sense to keep the functionality alive.
 
+For our friends at the University of Saskatchewan, I've also added `.asc` file loading.
+
 ## Installation
 
 ```bash
 pip install phdimporter
 ```
 
 ## Usage
```

### Comparing `phdimporter-0.0.2/README.md` & `phdimporter-0.0.3/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 
 The layout of the file is as documented in the [PicoHarp 300 manual](http://ridl.cfd.rit.edu/products/manuals/PicoQuant/PicoHarp%20300%20v2.3/manual/Manual.pdf) in section 8.2.1 (pages 56-58).
 
 Both of these are easy to modify, however the scope of this projec tis limited to our usage case.
 
 The module also loads `.txt` files which are the copy-pasted data from the PicoHarp software. This is primary way our research group has extracted data in the past, so it makes sense to keep the functionality alive.
 
+For our friends at the University of Saskatchewan, I've also added `.asc` file loading.
+
 ## Installation
 
 ```bash
 pip install phdimporter
 ```
 
 ## Usage
```

### Comparing `phdimporter-0.0.2/app/phdimporter/phd.py` & `phdimporter-0.0.3/app/phdimporter/phd.py`

 * *Files 1% similar despite different names*

```diff
@@ -75,15 +75,16 @@
         self.RouterEnable = struct.unpack('i', f.read(4))[0]
         self.RtCh_1 = RtCh(f)
         self.RtCh_2 = RtCh(f)
         self.RtCh_3 = RtCh(f)
         self.RtCh_4 = RtCh(f)
 
 class TRF:
-    def __init__(self, path):
+    def __init__(self, path, binSize = 0.0):
+        self.binSize = binSize
         if path[-4:] in ['.txt', '.asc']:
             self._from_txt(path)
         elif path[-4:] == '.phd':
             self._from_phd(path)
         return
     
     def _x_y(self):
@@ -103,15 +104,15 @@
         for line in lines:
             if '#PicoHarp 300' in line:
                 startLine = 10
                 binSize = int(float(lines[8]) * 1e3)
                 break
             elif 'Version : 1 920 M' in line:
                 startline = 10
-                binSize = 0
+                binSize = self.binSize
                 break
 
         self.Counts = []
         for line in lines[startLine:]:
             splitline = line.split()
             if len(splitline) == 1:
                 try:
```

### Comparing `phdimporter-0.0.2/app/phdimporter.egg-info/PKG-INFO` & `phdimporter-0.0.3/app/phdimporter.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: phdimporter
-Version: 0.0.2
+Version: 0.0.3
 Summary: PicoHarp .PhD file importer
 Home-page: https://github.com/adreasnow/picoharp-phd
 Author: Adrea Snow
 Author-email: adrea.snow@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -19,14 +19,16 @@
 
 The layout of the file is as documented in the [PicoHarp 300 manual](http://ridl.cfd.rit.edu/products/manuals/PicoQuant/PicoHarp%20300%20v2.3/manual/Manual.pdf) in section 8.2.1 (pages 56-58).
 
 Both of these are easy to modify, however the scope of this projec tis limited to our usage case.
 
 The module also loads `.txt` files which are the copy-pasted data from the PicoHarp software. This is primary way our research group has extracted data in the past, so it makes sense to keep the functionality alive.
 
+For our friends at the University of Saskatchewan, I've also added `.asc` file loading.
+
 ## Installation
 
 ```bash
 pip install phdimporter
 ```
 
 ## Usage
```

### Comparing `phdimporter-0.0.2/setup.py` & `phdimporter-0.0.3/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import find_packages, setup
 
 with open("README.md", "r", encoding = "utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name = "phdimporter",
-    version = "0.0.2",
+    version = "0.0.3",
     author = "Adrea Snow",
     author_email = "adrea.snow@gmail.com",
     description = "PicoHarp .PhD file importer",
     long_description = long_description,
     long_description_content_type = "text/markdown",
     url = "https://github.com/adreasnow/picoharp-phd",
     classifiers = [
```


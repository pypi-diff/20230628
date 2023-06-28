# Comparing `tmp/ssptools-0.4.0.tar.gz` & `tmp/ssptools-0.4.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ssptools-0.4.0.tar", last modified: Tue Jun  6 14:36:27 2023, max compression
+gzip compressed data, was "ssptools-0.4.1.tar", last modified: Wed Jun 28 12:48:34 2023, max compression
```

## Comparing `ssptools-0.4.0.tar` & `ssptools-0.4.1.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:27.988789 ssptools-0.4.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-06 14:36:15.000000 ssptools-0.4.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     3551 2023-06-06 14:36:27.988789 ssptools-0.4.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3114 2023-06-06 14:36:15.000000 ssptools-0.4.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-06 14:36:15.000000 ssptools-0.4.0/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:27.988789 ssptools-0.4.0/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-06 14:36:15.000000 ssptools-0.4.0/scripts/2POS.py
--rw-r--r--   0 runner    (1001) docker     (123)      648 2023-06-06 14:36:15.000000 ssptools-0.4.0/scripts/appendKPaths.py
--rw-r--r--   0 runner    (1001) docker     (123)      455 2023-06-06 14:36:15.000000 ssptools-0.4.0/scripts/compareEV.py
--rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-06 14:36:15.000000 ssptools-0.4.0/scripts/plotBS.py
--rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-06 14:36:15.000000 ssptools-0.4.0/scripts/sortPOS.py
--rw-r--r--   0 runner    (1001) docker     (123)      667 2023-06-06 14:36:27.992789 ssptools-0.4.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1048 2023-06-06 14:36:15.000000 ssptools-0.4.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:27.988789 ssptools-0.4.0/ssptools/
--rw-r--r--   0 runner    (1001) docker     (123)     4496 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/BSData.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      541 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/compare.py
--rw-r--r--   0 runner    (1001) docker     (123)     2409 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/eigenvalues.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:27.988789 ssptools-0.4.0/ssptools/io/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/io/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      654 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/io/main.py
--rw-r--r--   0 runner    (1001) docker     (123)     2867 2023-06-06 14:36:15.000000 ssptools-0.4.0/ssptools/kpaths.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 14:36:27.988789 ssptools-0.4.0/ssptools.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3551 2023-06-06 14:36:27.000000 ssptools-0.4.0/ssptools.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      455 2023-06-06 14:36:27.000000 ssptools-0.4.0/ssptools.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-06 14:36:27.000000 ssptools-0.4.0/ssptools.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-06 14:36:27.000000 ssptools-0.4.0/ssptools.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-06 14:36:27.000000 ssptools-0.4.0/ssptools.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:34.147478 ssptools-0.4.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 12:48:20.000000 ssptools-0.4.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     3551 2023-06-28 12:48:34.147478 ssptools-0.4.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3114 2023-06-28 12:48:20.000000 ssptools-0.4.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-28 12:48:20.000000 ssptools-0.4.1/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:34.147478 ssptools-0.4.1/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-28 12:48:20.000000 ssptools-0.4.1/scripts/2POS.py
+-rw-r--r--   0 runner    (1001) docker     (123)      648 2023-06-28 12:48:20.000000 ssptools-0.4.1/scripts/appendKPaths.py
+-rw-r--r--   0 runner    (1001) docker     (123)      455 2023-06-28 12:48:20.000000 ssptools-0.4.1/scripts/compareEV.py
+-rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-28 12:48:20.000000 ssptools-0.4.1/scripts/plotBS.py
+-rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-28 12:48:20.000000 ssptools-0.4.1/scripts/sortPOS.py
+-rw-r--r--   0 runner    (1001) docker     (123)      667 2023-06-28 12:48:34.147478 ssptools-0.4.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1048 2023-06-28 12:48:20.000000 ssptools-0.4.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:34.147478 ssptools-0.4.1/ssptools/
+-rw-r--r--   0 runner    (1001) docker     (123)     4577 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/BSData.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      541 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/compare.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2493 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/eigenvalues.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:34.147478 ssptools-0.4.1/ssptools/io/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/io/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      654 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/io/main.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2867 2023-06-28 12:48:20.000000 ssptools-0.4.1/ssptools/kpaths.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:48:34.147478 ssptools-0.4.1/ssptools.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3551 2023-06-28 12:48:34.000000 ssptools-0.4.1/ssptools.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      455 2023-06-28 12:48:34.000000 ssptools-0.4.1/ssptools.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:48:34.000000 ssptools-0.4.1/ssptools.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 12:48:34.000000 ssptools-0.4.1/ssptools.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 12:48:34.000000 ssptools-0.4.1/ssptools.egg-info/top_level.txt
```

### Comparing `ssptools-0.4.0/LICENSE` & `ssptools-0.4.1/LICENSE`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/PKG-INFO` & `ssptools-0.4.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ssptools
-Version: 0.4.0
+Version: 0.4.1
 Summary: Various specialized tools for working with the input and output of VASP
 Home-page: https://github.com/martin-eom/ssptools
 Author: Martin Keller
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.4
```

### Comparing `ssptools-0.4.0/README.md` & `ssptools-0.4.1/README.md`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/scripts/appendKPaths.py` & `ssptools-0.4.1/scripts/appendKPaths.py`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/scripts/plotBS.py` & `ssptools-0.4.1/scripts/plotBS.py`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/setup.cfg` & `ssptools-0.4.1/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = ssptools
-version = 0.4.0
+version = 0.4.1
 url = https://github.com/martin-eom/ssptools
 author = Martin Keller
 description = Various specialized tools for working with the input and output of VASP
 long_description = file: README.md
 long_description_content_type = text/markdown
 classifiers = 
 	Programming Language :: Python :: 3
```

### Comparing `ssptools-0.4.0/setup.py` & `ssptools-0.4.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 site.ENABLE_USER_SITE = "--user" in sys.argv[1:]
 
 with open("README.md", 'r', encoding="utf-8") as fh:
 	long_description = fh.read()
 
 setuptools.setup(
 	name="ssptools",
-	version="0.4.0",
+	version="0.4.1",
 	url="https://github.com/martin-eom/ssptools",
 	author="Martin Keller",
 	description="Various specialized tools for working with the input and output of VASP",
         long_description=long_description,
         classifiers=[
                 "Programming Language :: Python :: 3",
                 "License :: OSI Approved :: MIT License",
```

### Comparing `ssptools-0.4.0/ssptools/BSData.py` & `ssptools-0.4.1/ssptools/BSData.py`

 * *Files 3% similar despite different names*

```diff
@@ -29,15 +29,17 @@
             self.rec_vec = array(data["input"]["lattice_rec"]["matrix"])
             self.kpoints = [kp[0]*self.rec_vec[0] + kp[1]*self.rec_vec[1] + kp[2]*self.rec_vec[2] for kp in getKpoints(data)]
             last = self.kpoints[-nk]
             for kpoint in self.kpoints[-nk+1:]:
                 self.x_data.append(self.x_data[-1] + norm(kpoint-last))
                 last = kpoint
             bands = getBands(data)
-            if "auto_align" in kwargs and kwargs["auto_align"] == True:
+            if "alignment" in kwargs:
+                E0 = kwargs["alignment"]
+            elif "auto_align" in kwargs and kwargs["auto_align"] == True:
                 weighted_ind, weighted_bands = weighted_kpoint_inds(bands, getKweights(data))
                 if "LSORBIT" in data['input']['incar'].keys() and data['input']['incar']['LSORBIT'] == True:
                     div = 1
                 else:
                     div = 2
                 if "6H" in self.name:   E0 = alignment(weighted_bands, scheme = "bzavg", nvb = 24 // div, ncb = 12 // div)
                 elif "4H" in self.name: E0 = alignment(weighted_bands, scheme = "bzavg", nvb = 16 // div, ncb = 8 // div)
```

### Comparing `ssptools-0.4.0/ssptools/compare.py` & `ssptools-0.4.1/ssptools/compare.py`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/ssptools/eigenvalues.py` & `ssptools-0.4.1/ssptools/eigenvalues.py`

 * *Files 6% similar despite different names*

```diff
@@ -17,15 +17,17 @@
         else:
             v_bands.append(ev[0])
     c_bands.sort()
     v_bands.sort(reverse = True)
     return c_bands, v_bands
 
 def alignment(bands, **kwargs):
-    if "scheme" in kwargs.keys() and kwargs["scheme"] == "bzavg":   # eigenvalues should only inclued weighted kpoints
+    if "noalign" in kwargs.keys() and kwargs["noalign"] == True:
+        return 0
+    elif "scheme" in kwargs.keys() and kwargs["scheme"] == "bzavg":   # eigenvalues should only inclued weighted kpoints
         if "nvb" in kwargs.keys():
             nvb = kwargs["nvb"]
         else:
             nvb = 2
         if "ncb" in kwargs.keys():
             ncb = kwargs["ncb"]
         else:
```

### Comparing `ssptools-0.4.0/ssptools/io/main.py` & `ssptools-0.4.1/ssptools/io/main.py`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/ssptools/kpaths.py` & `ssptools-0.4.1/ssptools/kpaths.py`

 * *Files identical despite different names*

### Comparing `ssptools-0.4.0/ssptools.egg-info/PKG-INFO` & `ssptools-0.4.1/ssptools.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ssptools
-Version: 0.4.0
+Version: 0.4.1
 Summary: Various specialized tools for working with the input and output of VASP
 Home-page: https://github.com/martin-eom/ssptools
 Author: Martin Keller
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.4
```


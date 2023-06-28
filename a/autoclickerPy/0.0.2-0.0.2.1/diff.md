# Comparing `tmp/autoclickerPy-0.0.2.tar.gz` & `tmp/autoclickerPy-0.0.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "autoclickerPy-0.0.2.tar", last modified: Tue Jun 27 18:26:38 2023, max compression
+gzip compressed data, was "autoclickerPy-0.0.2.1.tar", last modified: Wed Jun 28 12:44:02 2023, max compression
```

## Comparing `autoclickerPy-0.0.2.tar` & `autoclickerPy-0.0.2.1.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 18:26:38.310161 autoclickerPy-0.0.2/
--rw-rw-rw-   0        0        0     1091 2023-06-27 16:29:17.000000 autoclickerPy-0.0.2/LICENSE
--rw-rw-rw-   0        0        0     1100 2023-06-27 18:26:38.309163 autoclickerPy-0.0.2/PKG-INFO
--rw-rw-rw-   0        0        0      535 2023-06-27 18:26:23.000000 autoclickerPy-0.0.2/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 18:26:38.306060 autoclickerPy-0.0.2/autoclickerPy/
--rw-rw-rw-   0        0        0       38 2023-06-27 18:19:40.000000 autoclickerPy-0.0.2/autoclickerPy/__init__.py
--rw-rw-rw-   0        0        0     2101 2023-06-27 18:21:53.000000 autoclickerPy-0.0.2/autoclickerPy/autoclicker.py
-drwxrwxrwx   0        0        0        0 2023-06-27 18:26:38.308167 autoclickerPy-0.0.2/autoclickerPy.egg-info/
--rw-rw-rw-   0        0        0     1100 2023-06-27 18:26:38.000000 autoclickerPy-0.0.2/autoclickerPy.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      265 2023-06-27 18:26:38.000000 autoclickerPy-0.0.2/autoclickerPy.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 18:26:38.000000 autoclickerPy-0.0.2/autoclickerPy.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2023-06-27 18:26:38.000000 autoclickerPy-0.0.2/autoclickerPy.egg-info/requires.txt
--rw-rw-rw-   0        0        0       14 2023-06-27 18:26:38.000000 autoclickerPy-0.0.2/autoclickerPy.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 18:26:38.310161 autoclickerPy-0.0.2/setup.cfg
--rw-rw-rw-   0        0        0     1022 2023-06-27 18:26:28.000000 autoclickerPy-0.0.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:44:02.282473 autoclickerPy-0.0.2.1/
+-rw-rw-rw-   0        0        0     1091 2023-06-27 16:29:17.000000 autoclickerPy-0.0.2.1/LICENSE
+-rw-rw-rw-   0        0        0     1102 2023-06-28 12:44:02.281477 autoclickerPy-0.0.2.1/PKG-INFO
+-rw-rw-rw-   0        0        0      535 2023-06-27 18:26:23.000000 autoclickerPy-0.0.2.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:44:02.278485 autoclickerPy-0.0.2.1/autoclickerPy/
+-rw-rw-rw-   0        0        0       38 2023-06-27 18:19:40.000000 autoclickerPy-0.0.2.1/autoclickerPy/__init__.py
+-rw-rw-rw-   0        0        0     2226 2023-06-28 12:39:53.000000 autoclickerPy-0.0.2.1/autoclickerPy/autoclicker.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:44:02.281477 autoclickerPy-0.0.2.1/autoclickerPy.egg-info/
+-rw-rw-rw-   0        0        0     1102 2023-06-28 12:44:02.000000 autoclickerPy-0.0.2.1/autoclickerPy.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      265 2023-06-28 12:44:02.000000 autoclickerPy-0.0.2.1/autoclickerPy.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:44:02.000000 autoclickerPy-0.0.2.1/autoclickerPy.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 12:44:02.000000 autoclickerPy-0.0.2.1/autoclickerPy.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       14 2023-06-28 12:44:02.000000 autoclickerPy-0.0.2.1/autoclickerPy.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:44:02.282473 autoclickerPy-0.0.2.1/setup.cfg
+-rw-rw-rw-   0        0        0     1024 2023-06-28 12:43:48.000000 autoclickerPy-0.0.2.1/setup.py
```

### Comparing `autoclickerPy-0.0.2/LICENSE` & `autoclickerPy-0.0.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `autoclickerPy-0.0.2/PKG-INFO` & `autoclickerPy-0.0.2.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: autoclickerPy
-Version: 0.0.2
+Version: 0.0.2.1
 Summary: Simple autoclicker for python
 Author: Geo
 Author-email: <geocraft31@gamil.com>
 Keywords: python,autoclicker
 Classifier: Development Status :: 1 - Planning
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
```

### Comparing `autoclickerPy-0.0.2/README.md` & `autoclickerPy-0.0.2.1/README.md`

 * *Files identical despite different names*

### Comparing `autoclickerPy-0.0.2/autoclickerPy/autoclicker.py` & `autoclickerPy-0.0.2.1/autoclickerPy/autoclicker.py`

 * *Files 3% similar despite different names*

```diff
@@ -71,15 +71,19 @@
         Raises:
             ValueError: if `timeSec` <= 0
         """
         if timeSec <= 0:
             raise ValueError("Variable `timeSec` can't be 0 or below")
 
         self.start()
-        time.sleep(timeSec)
+        now = time.time()
+        while time.time() - now < timeSec:
+            if not self.active:
+                return
+            time.sleep(0.01)
         self.stop()
 
     def _clicker(self):
         # private! Not for public use
         
         while not self._stopEvent.is_set():
             self._mouse.click(self.mouseButton)
```

### Comparing `autoclickerPy-0.0.2/autoclickerPy.egg-info/PKG-INFO` & `autoclickerPy-0.0.2.1/autoclickerPy.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: autoclickerPy
-Version: 0.0.2
+Version: 0.0.2.1
 Summary: Simple autoclicker for python
 Author: Geo
 Author-email: <geocraft31@gamil.com>
 Keywords: python,autoclicker
 Classifier: Development Status :: 1 - Planning
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
```

### Comparing `autoclickerPy-0.0.2/setup.py` & `autoclickerPy-0.0.2.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 import os
 
 here = os.path.abspath(os.path.dirname(__file__))
 
 with codecs.open(os.path.join(here, "README.md"), encoding="utf-8") as fh:
     long_description = "\n" + fh.read()
 
-VERSION = '0.0.2'
+VERSION = '0.0.2.1'
 DESCRIPTION = 'Simple autoclicker for python'
 LONGDESCRIPTION = 'Simple autoclicker for python long description'
 
 # Setting up
 setup(
     name="autoclickerPy",
     version=VERSION,
```


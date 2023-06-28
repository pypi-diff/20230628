# Comparing `tmp/webcam-1.6.tar.gz` & `tmp/webcam-1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "webcam-1.6.tar", last modified: Wed Jun 28 12:33:19 2023, max compression
+gzip compressed data, was "webcam-1.7.tar", last modified: Wed Jun 28 13:58:44 2023, max compression
```

## Comparing `webcam-1.6.tar` & `webcam-1.7.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 12:33:19.929921 webcam-1.6/
--rw-rw-rw-   0        0        0     1089 2023-05-04 16:30:34.000000 webcam-1.6/LICENSE
--rw-rw-rw-   0        0        0     4224 2023-06-28 12:33:19.929921 webcam-1.6/PKG-INFO
--rw-rw-rw-   0        0        0     3145 2023-05-09 10:11:35.000000 webcam-1.6/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 12:33:19.930915 webcam-1.6/setup.cfg
--rw-rw-rw-   0        0        0     1321 2023-06-28 12:33:12.000000 webcam-1.6/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:33:19.888843 webcam-1.6/webcam/
--rw-rw-rw-   0        0        0       42 2023-05-08 10:15:20.000000 webcam-1.6/webcam/__init__.py
--rw-rw-rw-   0        0        0    14854 2023-06-28 12:29:39.000000 webcam-1.6/webcam/_perspective_manager.py
--rw-rw-rw-   0        0        0     2687 2023-05-05 12:14:40.000000 webcam-1.6/webcam/_video_webcam.py
--rw-rw-rw-   0        0        0     1812 2023-05-05 10:19:36.000000 webcam-1.6/webcam/_webcam_background.py
--rw-rw-rw-   0        0        0    24481 2023-06-28 12:32:18.000000 webcam-1.6/webcam/webcam.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:33:19.927581 webcam-1.6/webcam.egg-info/
--rw-rw-rw-   0        0        0     4224 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      295 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       28 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 13:58:44.635107 webcam-1.7/
+-rw-rw-rw-   0        0        0     1089 2023-05-04 16:30:34.000000 webcam-1.7/LICENSE
+-rw-rw-rw-   0        0        0     4224 2023-06-28 13:58:44.632830 webcam-1.7/PKG-INFO
+-rw-rw-rw-   0        0        0     3145 2023-05-09 10:11:35.000000 webcam-1.7/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:58:44.636109 webcam-1.7/setup.cfg
+-rw-rw-rw-   0        0        0     1321 2023-06-28 13:58:40.000000 webcam-1.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:58:44.572967 webcam-1.7/webcam/
+-rw-rw-rw-   0        0        0       42 2023-05-08 10:15:20.000000 webcam-1.7/webcam/__init__.py
+-rw-rw-rw-   0        0        0    15431 2023-06-28 13:58:31.000000 webcam-1.7/webcam/_perspective_manager.py
+-rw-rw-rw-   0        0        0     2687 2023-05-05 12:14:40.000000 webcam-1.7/webcam/_video_webcam.py
+-rw-rw-rw-   0        0        0     1812 2023-05-05 10:19:36.000000 webcam-1.7/webcam/_webcam_background.py
+-rw-rw-rw-   0        0        0    24481 2023-06-28 12:32:18.000000 webcam-1.7/webcam/webcam.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:58:44.630830 webcam-1.7/webcam.egg-info/
+-rw-rw-rw-   0        0        0     4224 2023-06-28 13:58:44.000000 webcam-1.7/webcam.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      295 2023-06-28 13:58:44.000000 webcam-1.7/webcam.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:58:44.000000 webcam-1.7/webcam.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       28 2023-06-28 13:58:44.000000 webcam-1.7/webcam.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 13:58:44.000000 webcam-1.7/webcam.egg-info/top_level.txt
```

### Comparing `webcam-1.6/LICENSE` & `webcam-1.7/LICENSE`

 * *Files identical despite different names*

### Comparing `webcam-1.6/PKG-INFO` & `webcam-1.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: webcam
-Version: 1.6
+Version: 1.7
 Summary: A simple and convenient library to interact with webcams in Python without having to address Hardware Limitations
 Home-page: https://github.com/Eric-Canas/webcam
 Author: Eric-Canas
 Author-email: eric@ericcanas.com
 License: MIT
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `webcam-1.6/README.md` & `webcam-1.7/README.md`

 * *Files identical despite different names*

### Comparing `webcam-1.6/setup.py` & `webcam-1.7/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='webcam',
-    version='1.6',
+    version='1.7',
     author='Eric-Canas',
     author_email='eric@ericcanas.com',
     url='https://github.com/Eric-Canas/webcam',
     description='A simple and convenient library to interact with webcams in Python without having to address Hardware Limitations',
 
     long_description=open('README.md', 'r').read(),
     long_description_content_type='text/markdown',
```

### Comparing `webcam-1.6/webcam/_perspective_manager.py` & `webcam-1.7/webcam/_perspective_manager.py`

 * *Files 4% similar despite different names*

```diff
@@ -218,22 +218,31 @@
             xyxy_line = self.output_space_points_to_input_space(points_xy=xyxy_line)
 
         # Transform the line using homography matrix
         line_transformed = np.dot(self.homography_matrix, np.c_[xyxy_line, np.ones(2)].T)
         line_transformed /= line_transformed[2]
 
         # Calculate the lengths in x and y directions separately for the original and transformed lines
-        dx_original, dy_original = np.abs(xyxy_line[1] - xyxy_line[0])
-        dx_transformed, dy_transformed = np.abs(np.diff(line_transformed[:2], axis=1).squeeze())
+        #dx_original, dy_original = np.abs(xyxy_line[1] - xyxy_line[0])
+        #dx_transformed, dy_transformed = np.abs(np.diff(line_transformed[:2], axis=1).squeeze())
 
         # Calculate the magnification in x and y directions separately
-        magnification_w = dx_transformed / dx_original if dx_original != 0 else 1.0
-        magnification_h = dy_transformed / dy_original if dy_original != 0 else 1.0
+        #magnification_w = dx_transformed / dx_original if dx_original != 0 else 1.0
+        #magnification_h = dy_transformed / dy_original if dy_original != 0 else 1.0
 
-        return magnification_w, magnification_h
+        # TODO: We are calculating the magnification for the whole line, because h,w magnification becomes buggy when
+        #  lines are too horizontal or vertical. We should find a way to fix that.
+        # Calculate the lengths for the original and transformed lines
+        len_original = np.sqrt(np.sum((xyxy_line[1] - xyxy_line[0]) ** 2))
+        len_transformed = np.sqrt(np.sum(np.diff(line_transformed[:2], axis=1).squeeze() ** 2))
+
+        # Calculate the magnification
+        magnification = len_transformed / len_original if len_original != 0 else 1.0
+
+        return magnification, magnification
 
 
     def output_space_points_to_input_space(
         self, points_xy: np.ndarray | tuple[int | float, int | float, int | float, int | float]) -> np.ndarray:
         """
         Transform the given line from output space to input space.
```

### Comparing `webcam-1.6/webcam/_video_webcam.py` & `webcam-1.7/webcam/_video_webcam.py`

 * *Files identical despite different names*

### Comparing `webcam-1.6/webcam/_webcam_background.py` & `webcam-1.7/webcam/_webcam_background.py`

 * *Files identical despite different names*

### Comparing `webcam-1.6/webcam/webcam.py` & `webcam-1.7/webcam/webcam.py`

 * *Files identical despite different names*

### Comparing `webcam-1.6/webcam.egg-info/PKG-INFO` & `webcam-1.7/webcam.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: webcam
-Version: 1.6
+Version: 1.7
 Summary: A simple and convenient library to interact with webcams in Python without having to address Hardware Limitations
 Home-page: https://github.com/Eric-Canas/webcam
 Author: Eric-Canas
 Author-email: eric@ericcanas.com
 License: MIT
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```


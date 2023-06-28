# Comparing `tmp/webcam-1.5.tar.gz` & `tmp/webcam-1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "webcam-1.5.tar", last modified: Tue Jun 27 11:42:40 2023, max compression
+gzip compressed data, was "webcam-1.6.tar", last modified: Wed Jun 28 12:33:19 2023, max compression
```

## Comparing `webcam-1.5.tar` & `webcam-1.6.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 11:42:40.465687 webcam-1.5/
--rw-rw-rw-   0        0        0     1089 2023-05-04 16:30:34.000000 webcam-1.5/LICENSE
--rw-rw-rw-   0        0        0     4224 2023-06-27 11:42:40.464687 webcam-1.5/PKG-INFO
--rw-rw-rw-   0        0        0     3145 2023-05-09 10:11:35.000000 webcam-1.5/README.md
--rw-rw-rw-   0        0        0       42 2023-06-27 11:42:40.465687 webcam-1.5/setup.cfg
--rw-rw-rw-   0        0        0     1321 2023-06-27 11:42:34.000000 webcam-1.5/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-27 11:42:40.431361 webcam-1.5/webcam/
--rw-rw-rw-   0        0        0       42 2023-05-08 10:15:20.000000 webcam-1.5/webcam/__init__.py
--rw-rw-rw-   0        0        0    12272 2023-06-27 11:38:18.000000 webcam-1.5/webcam/_perspective_manager.py
--rw-rw-rw-   0        0        0     2687 2023-05-05 12:14:40.000000 webcam-1.5/webcam/_video_webcam.py
--rw-rw-rw-   0        0        0     1812 2023-05-05 10:19:36.000000 webcam-1.5/webcam/_webcam_background.py
--rw-rw-rw-   0        0        0    20189 2023-06-27 11:29:06.000000 webcam-1.5/webcam/webcam.py
-drwxrwxrwx   0        0        0        0 2023-06-27 11:42:40.462678 webcam-1.5/webcam.egg-info/
--rw-rw-rw-   0        0        0     4224 2023-06-27 11:42:40.000000 webcam-1.5/webcam.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      295 2023-06-27 11:42:40.000000 webcam-1.5/webcam.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 11:42:40.000000 webcam-1.5/webcam.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       28 2023-06-27 11:42:40.000000 webcam-1.5/webcam.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-27 11:42:40.000000 webcam-1.5/webcam.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 12:33:19.929921 webcam-1.6/
+-rw-rw-rw-   0        0        0     1089 2023-05-04 16:30:34.000000 webcam-1.6/LICENSE
+-rw-rw-rw-   0        0        0     4224 2023-06-28 12:33:19.929921 webcam-1.6/PKG-INFO
+-rw-rw-rw-   0        0        0     3145 2023-05-09 10:11:35.000000 webcam-1.6/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:33:19.930915 webcam-1.6/setup.cfg
+-rw-rw-rw-   0        0        0     1321 2023-06-28 12:33:12.000000 webcam-1.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:33:19.888843 webcam-1.6/webcam/
+-rw-rw-rw-   0        0        0       42 2023-05-08 10:15:20.000000 webcam-1.6/webcam/__init__.py
+-rw-rw-rw-   0        0        0    14854 2023-06-28 12:29:39.000000 webcam-1.6/webcam/_perspective_manager.py
+-rw-rw-rw-   0        0        0     2687 2023-05-05 12:14:40.000000 webcam-1.6/webcam/_video_webcam.py
+-rw-rw-rw-   0        0        0     1812 2023-05-05 10:19:36.000000 webcam-1.6/webcam/_webcam_background.py
+-rw-rw-rw-   0        0        0    24481 2023-06-28 12:32:18.000000 webcam-1.6/webcam/webcam.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:33:19.927581 webcam-1.6/webcam.egg-info/
+-rw-rw-rw-   0        0        0     4224 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      295 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       28 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 12:33:19.000000 webcam-1.6/webcam.egg-info/top_level.txt
```

### Comparing `webcam-1.5/LICENSE` & `webcam-1.6/LICENSE`

 * *Files identical despite different names*

### Comparing `webcam-1.5/PKG-INFO` & `webcam-1.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: webcam
-Version: 1.5
+Version: 1.6
 Summary: A simple and convenient library to interact with webcams in Python without having to address Hardware Limitations
 Home-page: https://github.com/Eric-Canas/webcam
 Author: Eric-Canas
 Author-email: eric@ericcanas.com
 License: MIT
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `webcam-1.5/README.md` & `webcam-1.6/README.md`

 * *Files identical despite different names*

### Comparing `webcam-1.5/setup.py` & `webcam-1.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='webcam',
-    version='1.5',
+    version='1.6',
     author='Eric-Canas',
     author_email='eric@ericcanas.com',
     url='https://github.com/Eric-Canas/webcam',
     description='A simple and convenient library to interact with webcams in Python without having to address Hardware Limitations',
 
     long_description=open('README.md', 'r').read(),
     long_description_content_type='text/markdown',
```

### Comparing `webcam-1.5/webcam/_perspective_manager.py` & `webcam-1.6/webcam/_perspective_manager.py`

 * *Files 12% similar despite different names*

```diff
@@ -9,23 +9,28 @@
 Date: 20-06-2023
 """
 from __future__ import annotations
 from functools import lru_cache
 import cv2
 import numpy as np
 
+INPUT, OUTPUT = 'input', 'output'
 
 class _PerspectiveManager:
     def __init__(self, homography_matrix: np.ndarray|list[list[float], ...], default_w: int, default_h: int,
                  crop_boundaries: bool = False,
                  boundaries_color: tuple[float|int, float|int, float|int] = (0., 0., 0.)):
         self.default_w, self.default_h = default_w, default_h
+
         homography_matrix = np.array(homography_matrix, dtype=np.float32)
         self.homography_matrix = self.__apply_non_negative_translation_to_homography_matrix(m=homography_matrix,
                                                                                              w=default_w, h=default_h)
+        # Inverse homography matrix is used for knowing the original place of coordinates in the warped image space
+        self.inverse_homography_matrix = np.linalg.inv(self.homography_matrix)
+
         self.crop_boundaries = crop_boundaries
         self.boundaries_color = boundaries_color
 
     @property
     def output_w(self) -> int:
         w, h = self.after_warp_image_shape(w=self.default_w, h=self.default_h)
         return w
@@ -140,14 +145,17 @@
         translation_matrix = np.array(((1., 0., -x_min), (0., 1., -y_min), (0., 0., 1.)), dtype=np.float32)
 
         # Combine the original matrix with the translation matrix
         combined_matrix = np.dot(a=translation_matrix, b=m)
 
         return combined_matrix
 
+
+    # ------------------------------ CALCULATE MAGNIFICATION FACTOR ------------------------------
+
     @lru_cache(maxsize=64)
     def get_hw_magnification_at_point(self, x:int|float, y:int|float) -> tuple[float, float]:
         """
         Get the magnification factor for the given point. It is calculated by setting two vectors extending along
         x and y axes around the point (x, y), a horizontal and a vertical one, with length 2. The vectors are then
         transformed by the homography matrix and the magnification factor is calculated as the ratio between the
         length of the transformed vectors and the original ones.
@@ -178,40 +186,77 @@
         homography_magnification_w = length_transformed_x / (vec_x[0, -1] - vec_x[0, 0]) if (vec_x[0, -1] - vec_x[
             0, 0]) != 0 else 1.0
         homography_magnification_h = length_transformed_y / (vec_y[1, -1] - vec_y[1, 0]) if (vec_y[1, -1] - vec_y[
             1, 0]) != 0 else 1.0
 
         return homography_magnification_w, homography_magnification_h
 
-    def get_hw_magnification_for_line(self, xyxy_line: np.ndarray | tuple[int | float, int | float, int | float, int | float]) \
+    def get_hw_magnification_for_line(self, xyxy_line: np.ndarray | tuple[int | float, int | float, int | float, int | float],
+                                      space: str = INPUT) \
             -> tuple[float, float]:
         """
         Get the magnification factor for the given line. It is calculated by transforming the two endpoints of the line
         and calculating the ratio between the length of the transformed line and the original one.
         :param xyxy_line: np.ndarray or tuple[int|float, int|float, int|float, int|float]. The line to which the magnification
         factor must be calculated. It can be either a tuple with the coordinates of the two endpoints of the line or a
         numpy array with shape (2, 2) containing the coordinates of the two endpoints of the line.
+        :param space: str. The space in which the line is defined. It can be either 'input' or 'output'. Default is 'output'.
         :return: tuple[float, float]. The magnification factor for the given line. In the form (h_magnification, w_magnification).
         """
         assert self.homography_matrix is not None, "Homography matrix must be set before calling this method."
         assert self.homography_matrix.shape == (
         3, 3), f"Homography matrix must be a 3x3 matrix. Got {'x'.join(map(str, self.homography_matrix.shape))}"
 
-        if isinstance(xyxy_line, tuple):
+        if isinstance(xyxy_line, (tuple, list)):
             assert len(xyxy_line) == 4, f"Expected tuple of length 4, but got length {len(xyxy_line)}."
             xyxy_line = np.array(xyxy_line, dtype=np.float32)
         assert isinstance(xyxy_line, np.ndarray), "Line must be either a tuple or a numpy array."
         xyxy_line = xyxy_line.reshape(2, 2)
 
+        # If line is given in output space, convert it. NOTE: That's dangerous. If using as module on webcam, if
+        # the line is received in the output space, will probably mean that the resize has not been reverted.
+        if space == OUTPUT:
+            xyxy_line = self.output_space_points_to_input_space(points_xy=xyxy_line)
+
         # Transform the line using homography matrix
         line_transformed = np.dot(self.homography_matrix, np.c_[xyxy_line, np.ones(2)].T)
         line_transformed /= line_transformed[2]
 
         # Calculate the lengths in x and y directions separately for the original and transformed lines
         dx_original, dy_original = np.abs(xyxy_line[1] - xyxy_line[0])
         dx_transformed, dy_transformed = np.abs(np.diff(line_transformed[:2], axis=1).squeeze())
 
         # Calculate the magnification in x and y directions separately
         magnification_w = dx_transformed / dx_original if dx_original != 0 else 1.0
         magnification_h = dy_transformed / dy_original if dy_original != 0 else 1.0
 
         return magnification_w, magnification_h
+
+
+    def output_space_points_to_input_space(
+        self, points_xy: np.ndarray | tuple[int | float, int | float, int | float, int | float]) -> np.ndarray:
+        """
+        Transform the given line from output space to input space.
+
+        :param points_xy: np.ndarray or tuple[int|float, int|float, int|float, int|float]. The line to be transformed.
+        It can be either a tuple with the coordinates of the two endpoints of the line or a numpy array with shape (2, 2)
+        containing the coordinates of the two endpoints of the line.
+
+        :return: np.ndarray. The transformed line in input space. It has shape (2, 2).
+        """
+        assert self.inverse_homography_matrix is not None, "Homography matrix must be set before calling this method."
+        assert self.inverse_homography_matrix.shape == (3, 3), \
+            f"Inverse Homograph matrix must be a 3x3 matrix. Got {'x'.join(map(str, self.homography_matrix.shape))}"
+
+        if isinstance(points_xy, (tuple, list)):
+            points_xy = np.array(points_xy, dtype=np.float32)
+        assert isinstance(points_xy, np.ndarray), "Line must be either a tuple, a list or a numpy array."
+        points_xy = points_xy.reshape(-1, 2)
+        n_points, coords = points_xy.shape
+        assert coords == 2, f"Expected 2 coordinates per point, but got {coords}."
+
+        # Transform the line back to the input space using the inverse homography matrix
+        points_transformed = np.dot(self.inverse_homography_matrix, np.c_[points_xy, np.ones(n_points)].T)
+        points_transformed /= points_transformed[2]
+        points_transformed = points_transformed[:2].T
+
+        return points_transformed
```

### Comparing `webcam-1.5/webcam/_video_webcam.py` & `webcam-1.6/webcam/_video_webcam.py`

 * *Files identical despite different names*

### Comparing `webcam-1.5/webcam/_webcam_background.py` & `webcam-1.6/webcam/_webcam_background.py`

 * *Files identical despite different names*

### Comparing `webcam-1.5/webcam/webcam.py` & `webcam-1.6/webcam/webcam.py`

 * *Files 16% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 import os
 
 from webcam._video_webcam import _VideoWebcam
 from webcam._webcam_background import _WebcamBackground
 from webcam._perspective_manager import _PerspectiveManager
 
 CROP, RESIZE = 'crop', 'resize'
+INPUT, OUTPUT = 'input', 'output'
 
 class Webcam:
     def __init__(
         self,
         src: int | str = 0,
         h: int | None = None,
         w: int | None = None,
@@ -82,14 +83,16 @@
 
         # Set batch size and frame rate attributes
         self.batch_size = batch_size
         self.start_timestamp = time.time()
         self.max_frame_rate = max_frame_rate
         self.last_frame_timestamp = self.start_timestamp
 
+
+
     @property
     def _h(self) -> int:
         h = int(self.cap.get(cv2.CAP_PROP_FRAME_HEIGHT))
         if self.perspective_manager is None:
             return h
         w = int(self.cap.get(cv2.CAP_PROP_FRAME_WIDTH))
         corrected_w, corrected_h = self.perspective_manager.after_warp_image_shape(w=w, h=h)
@@ -273,37 +276,37 @@
         # Calculate the position of the center crop
         y1, x1 = (new_h - h) // 2, (new_w - w) // 2
         y2, x2 = y1 + h, x1 + w
 
         # Crop the frame
         return frame[y1:y2, x1:x2]
 
-    def read(self) -> tuple[bool, np.ndarray|None]:
+    def read(self, transform: bool = True) -> tuple[bool, np.ndarray|None]:
         """
         Read a frame from the webcam.
 
         If the webcam's returned frame size is different from the user-set size, the frame is automatically resized.
 
         :return: tuple. A boolean indicating whether the frame was read successfully, and the frame itself.
         """
         ret, frame = self.cap.read()
 
-        if ret:
+        if ret and transform:
             # Adjust the perspective (if needed). If homography matrix is not defined it will do nothing
             if self.perspective_manager is not None:
                 frame = self.perspective_manager.warp(image=frame)
             # Get the height and width of the frame
             h, w = frame.shape[:2]
             # Resize the frame if the webcam's returned frame size is different from the user-set size
             if (h, w) != (self.h, self.w):
                 frame = self._adjust_image_shape(frame=frame, h=self.h, w=self.w)
 
-            # Convert the frame from BGR to RGB format if necessary
-            if not self.as_bgr:
-                cv2.cvtColor(src=frame, code=cv2.COLOR_BGR2RGB, dst=frame)
+        # Convert the frame from BGR to RGB format if necessary
+        if ret and not self.as_bgr:
+            cv2.cvtColor(src=frame, code=cv2.COLOR_BGR2RGB, dst=frame)
 
         return ret, frame
 
     def stop(self):
         self.cap.stop()
 
     def get(self, propId):
@@ -345,33 +348,40 @@
         # Calculate the pixel magnification for each axis when adjusting size
         magnification_h, magnification_w = self.__calculate_resizing_magnification_hw(input_h, input_w, magnification_h,
                                                                                       magnification_w)
 
         # Return the magnification of the pixel at (x, y)
         return magnification_h, magnification_w
 
-    def get_line_hw_magnification(self, line_xyxy: np.ndarray | tuple[int|float, int|float, int|float, int|float]) \
+    def get_line_hw_magnification(self, line_xyxy: np.ndarray | tuple[int|float, int|float, int|float, int|float],
+                                  space: str = OUTPUT) \
             -> tuple[float, float]:
         """
         Get the magnification factor for the given line. It allows to take precise measurements on the image, without
         having to worry about the perspective distortion, aspect ratio modifications or resizing.
         :param line_xyxy: tuple. The line to measure, in the format (x1, y1, x2, y2).
+        :param space: str. The space in which the line is defined. It can be either INPUT or OUTPUT.
         :return: tuple. The magnification factor for the line.
         """
+        if space == OUTPUT:
+            line_xyxy = self.output_space_points_to_input_space(points_xy=line_xyxy)
+
         # Calculate the homography magnification if appliable
         if self.perspective_manager is not None:
-            magnification_h, magnification_w = self.perspective_manager.get_hw_magnification_for_line(xyxy_line=line_xyxy)
+            magnification_h, magnification_w = self.perspective_manager.get_hw_magnification_for_line(xyxy_line=line_xyxy,
+                                                                                                      space=INPUT)
             input_h, input_w = self.perspective_manager.output_h, self.perspective_manager.output_w
         # Or use the default magnification
         else:
             magnification_h, magnification_w = 1.0, 1.0
             input_h, input_w = self._h, self._w
 
-        magnification_h, magnification_w = self.__calculate_resizing_magnification_hw(input_h, input_w, magnification_h,
-                                                                                      magnification_w)
+        magnification_h, magnification_w = self.__calculate_resizing_magnification_hw(input_h=input_h, input_w=input_w,
+                                                                                      pre_magnification_h=magnification_h,
+                                                                                      pre_magnification_w=magnification_w)
 
         return magnification_h, magnification_w
 
 
 
     # --------------- AUXILIARY METHODS ---------------
     def calculate_frame_size_keeping_aspect_ratio(self, h:int | None, w:int|None) -> tuple[int, int]:
@@ -402,26 +412,108 @@
         :param input_h: int. The input height.
         :param input_w: int. The input width.
         :param pre_magnification_h: float. The previous magnification in height. Default is 1.0.
         :param pre_magnification_w: float. The previous magnification in width. Default is 1.0.
         :return: tuple[float, float]. The updated magnification in height and width.
         """
         if self.on_aspect_ratio_lost == RESIZE:
-            pre_magnification_h *= self.h / input_h
-            pre_magnification_w *= self.w / input_w
+            magnification_h = pre_magnification_h * (self.h / input_h)
+            magnification_w = pre_magnification_w * (self.w / input_w)
 
         elif self.on_aspect_ratio_lost == CROP:
             resize_ratio = self.h / input_h if input_h < input_w else self.w / input_w
-            pre_magnification_h *= resize_ratio
-            pre_magnification_w *= resize_ratio
+            magnification_h = pre_magnification_h * resize_ratio
+            magnification_w = pre_magnification_w * resize_ratio
         else:
             raise ValueError(f"Invalid value for 'on_aspect_ratio_lost' parameter: {self.on_aspect_ratio_lost}."
                              f" Valid values are '{RESIZE}' and '{CROP}'.")
 
-        return pre_magnification_h, pre_magnification_w
+        return magnification_h, magnification_w
+
+    def output_space_points_to_input_space(self, points_xy: np.ndarray | tuple[float | int, ...] | list[float | int, ...]) ->\
+            np.ndarray:
+        """
+        Transform the given points from output space to input space.
+
+        :param points_xy: np.ndarray. Points to be transformed. It has shape (N, 2), where N is the number of points.
+        :return: np.ndarray. The transformed points. It has shape (N, 2).
+        """
+        if isinstance(points_xy, (tuple, list)):
+            points_xy = np.array(points_xy, dtype=np.float32)
+        assert isinstance(points_xy, np.ndarray), "Line must be either a tuple or a numpy array."
+        points_xy = points_xy.reshape(-1, 2)
+
+        if self.on_aspect_ratio_lost == RESIZE:
+            points_xy = self.__rollback_resize_for_points(points_xy=points_xy)
+        elif self.on_aspect_ratio_lost == CROP:
+            points_xy = self.__rollback_crop_for_points(points_xy=points_xy)
+        else:
+            raise ValueError(f"Invalid value for 'on_aspect_ratio_lost' parameter: {self.on_aspect_ratio_lost}. "
+                             f"Valid values are: {RESIZE}, {CROP}.")
+
+        # Undo the homography transformation using the Perspective Manager's method
+        points_transformed = self.perspective_manager.output_space_points_to_input_space(points_xy=points_xy)
+
+        return points_transformed
+
+    def __rollback_resize_for_points(self, points_xy: np.ndarray) -> np.ndarray:
+        """
+        Rollback the resize transformation.
+
+        :param points_xy: np.ndarray. Points to be transformed. It has shape (N, 2), where N is the number of points.
+        :return: np.ndarray. The transformed points. It has shape (N, 2).
+        """
+        scale_x = self.perspective_manager.output_w / self.w
+        scale_y = self.perspective_manager.output_h / self.h
+
+        points_xy[:, 0] *= scale_x
+        points_xy[:, 1] *= scale_y
+
+        return points_xy
+
+    def __rollback_crop_for_points(self, points_xy: np.ndarray) -> np.ndarray:
+        """
+        Rollback the crop transformation.
+
+        :param points_xy: np.ndarray. Points to be transformed. It has shape (N, 2), where N is the number of points.
+        :return: np.ndarray. The transformed points. It has shape (N, 2).
+        """
+        # The input dimensions that the crop received (the output of the warping
+        input_h, input_w = self.perspective_manager.output_h, self.perspective_manager.output_w
+        # The output dimensions that the crop should produce
+        output_h, output_w = self.h, self.w
+
+        aspect_ratio = input_w / input_h
+
+        # Calculate the intermediate dimensions that the crop should produce (dimensions to resize before cropping)
+        if input_h < input_w:
+            new_h = output_h
+            new_w = int(np.ceil(new_h * aspect_ratio))
+        else:
+            new_w = output_w
+            new_h = int(np.ceil(new_w / aspect_ratio))
+
+        # Calculate the scale factor of the resize
+        scale_x = new_w / input_w
+        scale_y = new_h / input_h
+
+        # Copy the points to avoid changing the original array
+        points_xy = points_xy.astype(np.float32)
+        # Divide the points by the scale factor (to rollback the resize)
+        points_xy[:, 0] /= scale_x
+        points_xy[:, 1] /= scale_y
+
+        # Calculate the position of the center crop
+        y1, x1 = (new_h - output_h) // 2, (new_w - output_w) // 2
+
+        # Translate the points
+        points_xy[:, 0] += x1
+        points_xy[:, 1] += y1
+
+        return points_xy
 
     def __iter__(self):
         return self
 
     def __next__(self):
         return self.read_next_frame()
```

### Comparing `webcam-1.5/webcam.egg-info/PKG-INFO` & `webcam-1.6/webcam.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: webcam
-Version: 1.5
+Version: 1.6
 Summary: A simple and convenient library to interact with webcams in Python without having to address Hardware Limitations
 Home-page: https://github.com/Eric-Canas/webcam
 Author: Eric-Canas
 Author-email: eric@ericcanas.com
 License: MIT
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```


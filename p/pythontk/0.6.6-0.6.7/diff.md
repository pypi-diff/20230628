# Comparing `tmp/pythontk-0.6.6.tar.gz` & `tmp/pythontk-0.6.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pythontk-0.6.6.tar", last modified: Sun Jun 25 23:02:01 2023, max compression
+gzip compressed data, was "pythontk-0.6.7.tar", last modified: Wed Jun 28 02:19:30 2023, max compression
```

## Comparing `pythontk-0.6.6.tar` & `pythontk-0.6.7.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwxrwx   0        0        0        0 2023-06-25 23:02:01.316895 pythontk-0.6.6/
--rw-rw-rw-   0        0        0     1093 2023-03-28 23:38:48.000000 pythontk-0.6.6/LICENSE
--rw-rw-rw-   0        0        0     1155 2023-06-25 23:02:01.316895 pythontk-0.6.6/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-25 23:02:01.303892 pythontk-0.6.6/pythontk/
--rw-rw-rw-   0        0        0     7133 2023-06-25 23:01:58.000000 pythontk-0.6.6/pythontk/__init__.py
--rw-rw-rw-   0        0        0    25612 2023-06-25 00:59:16.000000 pythontk-0.6.6/pythontk/file_utils.py
--rw-rw-rw-   0        0        0    29224 2023-06-24 12:30:01.000000 pythontk-0.6.6/pythontk/img_utils.py
--rw-rw-rw-   0        0        0    29221 2023-06-24 12:29:41.000000 pythontk-0.6.6/pythontk/img_utils.py.bak
--rw-rw-rw-   0        0        0    16156 2023-06-06 18:19:16.000000 pythontk-0.6.6/pythontk/iter_utils.py
--rw-rw-rw-   0        0        0    18312 2023-05-30 18:39:59.000000 pythontk-0.6.6/pythontk/math_utils.py
--rw-rw-rw-   0        0        0    11452 2023-06-14 16:03:32.000000 pythontk-0.6.6/pythontk/misc_utils.py
--rw-rw-rw-   0        0        0    25433 2023-06-14 21:04:19.000000 pythontk-0.6.6/pythontk/str_utils.py
-drwxrwxrwx   0        0        0        0 2023-06-25 23:02:01.315894 pythontk-0.6.6/pythontk.egg-info/
--rw-rw-rw-   0        0        0     1155 2023-06-25 23:02:01.000000 pythontk-0.6.6/pythontk.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1287 2023-05-20 13:28:19.000000 pythontk-0.6.6/pythontk.egg-info/PKG-INFO.bak
--rw-rw-rw-   0        0        0      392 2023-06-25 23:02:01.000000 pythontk-0.6.6/pythontk.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0      265 2023-05-07 12:53:37.000000 pythontk-0.6.6/pythontk.egg-info/SOURCES.txt.bak
--rw-rw-rw-   0        0        0        1 2023-06-25 23:02:01.000000 pythontk-0.6.6/pythontk.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        9 2023-06-25 23:02:01.000000 pythontk-0.6.6/pythontk.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-25 23:02:01.316895 pythontk-0.6.6/setup.cfg
--rw-rw-rw-   0        0        0     2212 2023-06-06 18:19:16.000000 pythontk-0.6.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:19:30.289131 pythontk-0.6.7/
+-rw-rw-rw-   0        0        0     1093 2023-03-28 23:38:48.000000 pythontk-0.6.7/LICENSE
+-rw-rw-rw-   0        0        0     1155 2023-06-28 02:19:30.287627 pythontk-0.6.7/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 02:19:30.256804 pythontk-0.6.7/pythontk/
+-rw-rw-rw-   0        0        0     7133 2023-06-28 02:19:24.000000 pythontk-0.6.7/pythontk/__init__.py
+-rw-rw-rw-   0        0        0    25637 2023-06-28 00:18:26.000000 pythontk-0.6.7/pythontk/file_utils.py
+-rw-rw-rw-   0        0        0    29291 2023-06-27 22:55:30.000000 pythontk-0.6.7/pythontk/img_utils.py
+-rw-rw-rw-   0        0        0    29221 2023-06-24 12:29:41.000000 pythontk-0.6.7/pythontk/img_utils.py.bak
+-rw-rw-rw-   0        0        0    16161 2023-06-28 00:25:24.000000 pythontk-0.6.7/pythontk/iter_utils.py
+-rw-rw-rw-   0        0        0    18070 2023-06-27 22:52:04.000000 pythontk-0.6.7/pythontk/math_utils.py
+-rw-rw-rw-   0        0        0    24621 2023-06-27 23:08:47.000000 pythontk-0.6.7/pythontk/str_utils.py
+-rw-rw-rw-   0        0        0    11206 2023-06-27 22:12:52.000000 pythontk-0.6.7/pythontk/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:19:30.287627 pythontk-0.6.7/pythontk.egg-info/
+-rw-rw-rw-   0        0        0     1155 2023-06-28 02:19:30.000000 pythontk-0.6.7/pythontk.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1287 2023-05-20 13:28:19.000000 pythontk-0.6.7/pythontk.egg-info/PKG-INFO.bak
+-rw-rw-rw-   0        0        0      387 2023-06-28 02:19:30.000000 pythontk-0.6.7/pythontk.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0      265 2023-05-07 12:53:37.000000 pythontk-0.6.7/pythontk.egg-info/SOURCES.txt.bak
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:19:30.000000 pythontk-0.6.7/pythontk.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 02:19:30.000000 pythontk-0.6.7/pythontk.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:19:30.289131 pythontk-0.6.7/setup.cfg
+-rw-rw-rw-   0        0        0     1416 2023-06-28 02:16:16.000000 pythontk-0.6.7/setup.py
```

### Comparing `pythontk-0.6.6/LICENSE` & `pythontk-0.6.7/LICENSE`

 * *Files identical despite different names*

### Comparing `pythontk-0.6.6/PKG-INFO` & `pythontk-0.6.7/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pythontk
-Version: 0.6.6
+Version: 0.6.7
 Summary: *pythontk is a collection of backend utilities for Python.*
 Home-page: https://github.com/m3trik/pythontk
 Author: Ryan Simpson
 Author-email: m3trik@outlook.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `pythontk-0.6.6/pythontk/__init__.py` & `pythontk-0.6.7/pythontk/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 # coding=utf-8
 import inspect
 import importlib
 import pkgutil
 
 
 __package__ = "pythontk"
-__version__ = '0.6.6'
+__version__ = '0.6.7'
 
 
 # Define dictionaries to map class names, method names, and class method names to their respective modules
 CLASS_TO_MODULE = {}
 METHOD_TO_MODULE = {}
 CLASS_METHOD_TO_MODULE = {}
```

### Comparing `pythontk-0.6.6/pythontk/file_utils.py` & `pythontk-0.6.7/pythontk/file_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,20 +3,20 @@
 import sys
 import os
 import re
 import json
 import traceback
 
 # from this package:
-from pythontk.misc_utils import Misc
-from pythontk.iter_utils import Iter
-from pythontk.str_utils import Str
+from pythontk.utils import Utils
+from pythontk.iter_utils import IterUtils
+from pythontk.str_utils import StrUtils
 
 
-class File:
+class FileUtils:
     """ """
 
     @staticmethod
     def is_valid(filepath: str) -> list:
         """Determine if the given file or dir is valid.
 
         Parameters:
@@ -177,16 +177,16 @@
         returnTypes = {t.strip().rstrip("s").lower() for t in returned_type.split("|")}
 
         def process_directory(root, dirs, files):
             result = []
             if not recursive and root != path:
                 return result
 
-            dirs = Iter.filter_list(dirs, inc_dirs, exc_dirs)
-            files = Iter.filter_list(files, inc_files, exc_files)
+            dirs = IterUtils.filter_list(dirs, inc_dirs, exc_dirs)
+            files = IterUtils.filter_list(files, inc_files, exc_files)
 
             if "dir" in returnTypes:
                 result.extend(dirs)
             if "dirpath" in returnTypes:
                 result.extend(os.path.join(root, d) for d in dirs)
             if "file" in returnTypes:
                 result.extend(files)
@@ -285,15 +285,15 @@
             return os.path.abspath(filepath)
         elif filepath:
             return os.path.abspath(os.path.dirname(filepath))
         else:
             return None
 
     @staticmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def format_path(p, section="", replace=""):
         """Format a given filepath(s).
         When a section arg is given, the correlating section of the string will be returned.
         If a replace arg is given, the stated section will be replaced by the given value.
 
         Parameters:
             p (str/list): The filepath(s) to be formatted.
@@ -341,15 +341,15 @@
         elif section == "ext":
             result = ext
 
         else:
             result = p
 
         if replace:
-            result = Str.rreplace(p, result, replace, 1)
+            result = StrUtils.rreplace(p, result, replace, 1)
 
         return result
 
     @classmethod
     def append_paths(cls, root_dir, **kwargs):
         """Append all sub-directories of the given 'root_dir' to the python path.
 
@@ -362,15 +362,15 @@
         """
         path = os.path.dirname(os.path.abspath(root_dir))
         return [
             sys.path.append(d) for d in cls.get_dir_contents(path, "dirs", **kwargs)
         ]
 
     @classmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def time_stamp(cls, filepath, stamp="%m-%d-%Y  %H:%M"):
         """Attach or detach a modified timestamp and date to/from a given file path.
 
         Parameters:
             filepath (str): The full path to a file. ie. 'C:/Windows/Temp/__AUTO-SAVE__untitled.0001.mb'
             stamp (str): The time stamp format.
 
@@ -494,15 +494,15 @@
     def set_json_file(cls, file):
         """Set the current json filepath.
 
         Parameters:
             file (str): The filepath to a json file. If a file doesn't exist, it will be created.
         """
         cls._jsonFile = file
-        File.get_file(cls._jsonFile)  # will create the file if it does not exist.
+        cls.get_file(cls._jsonFile)  # will create the file if it does not exist.
 
     @classmethod
     def get_json_file(cls):
         """Get the current json filepath.
 
         Returns:
             (str)
@@ -603,15 +603,14 @@
 
 # --------------------------------------------------------------------------------------------
 # Notes
 # --------------------------------------------------------------------------------------------
 
 
 # Deprecated ------------------------------------
-
 # @staticmethod
 # def get_filepath(obj, inc_filename=False):
 #     """Get the filepath of a class or module.
 
 #     Parameters:
 #             obj (obj): A python module, class, or the built-in __file__ variable.
 #             inc_filename (bool): Include the filename in the returned result.
```

### Comparing `pythontk-0.6.6/pythontk/img_utils.py` & `pythontk-0.6.7/pythontk/img_utils.py.bak`

 * *Files 1% similar despite different names*

```diff
@@ -84,15 +84,15 @@
         "Specular": "L",
         "Glossiness": "L",
         "Displacement": "L",
         "Refraction": "L",
         "Reflection": "L",
     }
 
-    bit_depth = {  # Get bit depth from mode.
+    bitDepth = {  # Get bit depth from mode.
         "1": 1,
         "L": 8,
         "P": 8,
         "RGB": 24,
         "RGBA": 32,
         "CMYK": 32,
         "YCbCr": 24,
@@ -733,17 +733,17 @@
 
 # def getBitDepth(cls, image):
 #       '''
 #       '''
 #       im = cls.load_image(image) if isinstance(image, str) else image
 #       data = np.array(im)
 
-#       bit_depth = {'uint8':8, 'uint16':16, 'uint32':32, 'uint64':64}
+#       bitDepth = {'uint8':8, 'uint16':16, 'uint32':32, 'uint64':64}
 
-#       return bit_depth[str(data.dtype)]
+#       return bitDepth[str(data.dtype)]
 
 
 # width, height = im.size
 
 # for i in range(0, width):# process all pixels
 #   for ii in range(0, height):
 #       data = im.getpixel((i, ii))
```

### Comparing `pythontk-0.6.6/pythontk/img_utils.py.bak` & `pythontk-0.6.7/pythontk/img_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,20 +12,20 @@
     print("{}\n # Error: {} #".format(__file__, error))
 try:
     from PySide2 import QtWidgets
 except ImportError as error:
     print("{}\n # Error: {} #".format(__file__, error))
 
 # from this package:
-from pythontk.misc_utils import Misc
-from pythontk.file_utils import File
-from pythontk.iter_utils import Iter
+from pythontk.utils import Utils
+from pythontk.file_utils import FileUtils
+from pythontk.iter_utils import IterUtils
 
 
-class Img:
+class ImgUtils:
     """Helper methods for working with image file formats."""
 
     app = QtWidgets.QApplication.instance() or QtWidgets.QApplication(
         sys.argv
     )  # return the existing QApplication object, or create a new one if none exists.
 
     map_types = {  # Get map type from filename suffix.
@@ -84,15 +84,15 @@
         "Specular": "L",
         "Glossiness": "L",
         "Displacement": "L",
         "Refraction": "L",
         "Reflection": "L",
     }
 
-    bitDepth = {  # Get bit depth from mode.
+    bit_depth = {  # Get bit depth from mode.
         "1": 1,
         "L": 8,
         "P": 8,
         "RGB": 24,
         "RGBA": 32,
         "CMYK": 32,
         "YCbCr": 24,
@@ -198,15 +198,15 @@
                                 supports using the '*' operator: startswith*, *endswith, *contains*
                 exc (str): The files to exclude.
                                 (exlude take precidence over include)
         Returns:
                 (dict) {<full file path>:<image object>}
         """
         images = {}
-        for f in File.get_dir_contents(
+        for f in FileUtils.get_dir_contents(
             directory, "filepaths", inc_files=inc.split("|"), exc_files=exc.split("|")
         ):
             im = cls.load_image(f)
             images[f] = im
 
         return images
 
@@ -249,15 +249,15 @@
                 file (str): Image filename, fullpath, or map type suffix.
                 key (bool): Get the corresponding key from the type in 'map_types'.
                         ie. Base_Color from <filename>_BC or BC. else: _BC from <filename>_BC.
 
         Returns:
                 (str)
         """
-        name = File.format_path(file, "name")
+        name = FileUtils.format_path(file, "name")
 
         if key:
             result = next(
                 (
                     k
                     for k, v in cls.map_types.items()
                     for i in v
@@ -287,15 +287,15 @@
                         Multiple types can be given separated by '|' ex. 'Base_Color|Roughness'
                         ex. 'Base_Color','Roughness','Metallic','Ambient_Occlusion','Normal',
                                 'Normal_DirectX','Normal_OpenGL','Height','Emissive','Diffuse','Specular',
                                 'Glossiness','Displacement','Refraction','Reflection'
         Returns:
                 (dict)
         """
-        types = Iter.make_iterable(types.split("|"))
+        types = IterUtils.make_iterable(types.split("|"))
         return [f for f in files if cls.get_image_type_from_filename(f) in types]
 
     @classmethod
     def sort_images_by_type(cls, files):
         """Sort images files by map type.
 
         Parameters:
@@ -409,17 +409,17 @@
                 file (str): The fullpath to a DirectX normal map file.
 
         Returns:
                 (str) filepath of the new image.
         """
         inverted_image = cls.invert_channels(file, "g")
 
-        output_dir = File.format_path(file, "path")
-        name = File.format_path(file, "name")
-        ext = File.format_path(file, "ext")
+        output_dir = FileUtils.format_path(file, "path")
+        name = FileUtils.format_path(file, "name")
+        ext = FileUtils.format_path(file, "ext")
 
         typ = cls.get_image_type_from_filename(file, key=False)
         try:
             index = cls.map_types["Normal_OpenGL"].index(typ)
             new_type = cls.map_types["Normal_DirectX"][index]
         except (IndexError, ValueError) as error:
             print("{} in create_dx_from_gl\n\t# Error: {} #".format(__file__, error))
@@ -440,17 +440,17 @@
                 file (str): The fullpath to a OpenGL normal map file.
 
         Returns:
                 (str) filepath of the new image.
         """
         inverted_image = cls.invert_channels(file, "g")
 
-        output_dir = File.format_path(file, "path")
-        name = File.format_path(file, "name")
-        ext = File.format_path(file, "ext")
+        output_dir = FileUtils.format_path(file, "path")
+        name = FileUtils.format_path(file, "name")
+        ext = FileUtils.format_path(file, "ext")
 
         typ = cls.get_image_type_from_filename(file, key=False)
         try:
             index = cls.map_types["Normal_DirectX"].index(typ)
             new_type = cls.map_types["Normal_OpenGL"][index]
         except IndexError as error:
             print("{} in create_gl_from_dx\n\t# Error: {} #".format(__file__, error))
@@ -459,15 +459,15 @@
         name = name.removesuffix(typ)
         filepath = "{}/{}{}.{}".format(output_dir, name, new_type, ext)
         inverted_image.save(filepath)
 
         return filepath
 
     @classmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def create_mask(
         cls, image, mask, background=(0, 0, 0, 255), foreground=(255, 255, 255, 255)
     ):
         """Create mask(s) from the given image(s).
 
         Parameters:
                 images (str/obj/list): Image(s) or path(s) to an image.
@@ -733,17 +733,17 @@
 
 # def getBitDepth(cls, image):
 #       '''
 #       '''
 #       im = cls.load_image(image) if isinstance(image, str) else image
 #       data = np.array(im)
 
-#       bitDepth = {'uint8':8, 'uint16':16, 'uint32':32, 'uint64':64}
+#       bit_depth = {'uint8':8, 'uint16':16, 'uint32':32, 'uint64':64}
 
-#       return bitDepth[str(data.dtype)]
+#       return bit_depth[str(data.dtype)]
 
 
 # width, height = im.size
 
 # for i in range(0, width):# process all pixels
 #   for ii in range(0, height):
 #       data = im.getpixel((i, ii))
@@ -788,25 +788,25 @@
 
 # def convertDXToGL(cls):
 #   '''
 #   '''
 #   files = cls.get_image_files()
 #   for file, image in files.items():
 #       inverted_image = cls.invert_channels(image, 'g')
-#       # name = File.format_path(file, remove='_DirectX', append='_OpenGL')
+#       # name = FileUtils.format_path(file, remove='_DirectX', append='_OpenGL')
 #       # cls.save_image(inverted_image, name)
 
 
 # def convertGLToDX(cls):
 #   '''
 #   '''
 #   files = cls.get_image_files()
 #   for file, image in files.items():
 #       inverted_image = cls.invert_channels(image, 'g')
-#       # name = File.format_path(file, remove='_OpenGL', append='_DirectX')
+#       # name = FileUtils.format_path(file, remove='_OpenGL', append='_DirectX')
 #       # cls.save_image(inverted_image, name)
 
 
 # def changeColorDepth(cls, image, depth):
 #   '''
 #   '''
 # return image.convert(image.mode, colors=depth)
```

### Comparing `pythontk-0.6.6/pythontk/iter_utils.py` & `pythontk-0.6.7/pythontk/iter_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # !/usr/bin/python
 # coding=utf-8
 
 
-class Iter:
+class IterUtils:
     """ """
 
     @staticmethod
     def make_iterable(x):
         """Convert the given obj to an iterable, unless it's a string, bytes, or bytearray.
 
         Parameters:
```

### Comparing `pythontk-0.6.6/pythontk/math_utils.py` & `pythontk-0.6.7/pythontk/math_utils.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,32 +1,32 @@
 # !/usr/bin/python
 # coding=utf-8
 from typing import List, Tuple
 
 # from this package:
-from pythontk.misc_utils import Misc
+from pythontk.utils import Utils
 
 
-class Math:
+class MathUtils:
     """ """
 
     @staticmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def move_decimal_point(num, places):
         """Move the decimal place in a given number.
 
         Parameters:
-                num (int/float): The number in which you are modifying.
-                places (int): The number of decimal places to move.
+            num (int/float): The number in which you are modifying.
+            places (int): The number of decimal places to move.
 
         Returns:
-                (float)
+            (float)
 
         Example:
-                move_decimal_point(11.05, -2) #returns: 0.1105
+            move_decimal_point(11.05, -2) #returns: 0.1105
         """
         from decimal import Decimal
 
         num_decimal = Decimal(str(num))  # Convert the input number to a Decimal object
         scaling_factor = Decimal(
             10**places
         )  # Create a scaling factor as a Decimal object
@@ -39,117 +39,122 @@
     @staticmethod
     def get_vector_from_two_points(
         a: List[float], b: List[float]
     ) -> Tuple[float, float, float]:
         """Get a directional vector from a given start and end point.
 
         Parameters:
-                a (List[float]): A start point given as [x, y, z].
-                b (List[float]): An end point given as [x, y, z].
+            a (List[float]): A start point given as [x, y, z].
+            b (List[float]): An end point given as [x, y, z].
 
         Returns:
-                Tuple[float, float, float]: The directional vector from the start point to the end point.
+            Tuple[float, float, float]: The directional vector from the start point to the end point.
 
         Example:
-                get_vector_from_two_points([1, 2, 3], [1, 1, -1]) #returns: (0, -1, -4)
+            get_vector_from_two_points([1, 2, 3], [1, 1, -1]) #returns: (0, -1, -4)
         """
         return (b[0] - a[0], b[1] - a[1], b[2] - a[2])
 
     @staticmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def clamp(n=0.0, minimum=0.0, maximum=1.0):
         """Clamps the value x between min and max.
 
         Parameters:
-                n (float)(tuple): The numeric value to clamp.
-                minimum (float) = Clamp min value.
-                maximum (float) = Clamp max value.
+            n (float)(tuple): The numeric value to clamp.
+            minimum (float): Clamp min value.
+            maximum (float): Clamp max value.
 
         Returns:
-                (float)
+            (float)
 
-        Example: clamp(range(10), 3, 7) #returns: [3, 3, 3, 3, 4, 5, 6, 7, 7, 7]
+        Example:
+            clamp(range(10), 3, 7) #returns: [3, 3, 3, 3, 4, 5, 6, 7, 7, 7]
         """
         return max(minimum, min(n, maximum))
 
     @classmethod
     def normalize(cls, vector, amount=1):
         """Normalize a 2 or 3 dimensional vector.
 
         Parameters:
-                vector (tuple): A two or three point vector. ie. (-0.03484, 0.0, -0.55195)
-                amount (float) = (1) Normalize standard. (value other than 0 or 1) Normalize using the given float value as desired length.
+            vector (tuple): A two or three point vector. ie. (-0.03484, 0.0, -0.55195)
+            amount (float): (1) Normalize standard. (value other than 0 or 1) Normalize using the given float value as desired length.
 
         Returns:
-                (tuple)
+            (tuple)
 
-        Example: normalize((2, 3, 4)) #returns: (0.3713906763541037, 0.5570860145311556, 0.7427813527082074)
-        Example: normalize((2, 3)) #returns: (0.5547001962252291, 0.8320502943378437)
-        Example: normalize((2, 3, 4), 2) #returns: (0.7427813527082074, 1.1141720290623112, 1.4855627054164149)
+        Example:
+            normalize((2, 3, 4)) #returns: (0.3713906763541037, 0.5570860145311556, 0.7427813527082074)
+            normalize((2, 3)) #returns: (0.5547001962252291, 0.8320502943378437)
+            normalize((2, 3, 4), 2) #returns: (0.7427813527082074, 1.1141720290623112, 1.4855627054164149)
         """
         n = len(vector)  # determine 2 or 3d vector.
         length = cls.get_magnitude(vector)
         return tuple(vector[i] / length * amount for i in range(n))
 
     @staticmethod
     def get_magnitude(vector):
         """Get the magnatude (length) of a given vector.
 
         Parameters:
-                vector (tuple): A two or three point vector. ie. (-0.03484, 0.0, -0.55195)
+            vector (tuple): A two or three point vector. ie. (-0.03484, 0.0, -0.55195)
 
         Returns:
-                (float)
+            (float)
 
-        Example: get_magnitude((2, 3, 4)) #returns: 5.385164807134504
-        Example: get_magnitude((2, 3)) #returns: 3.605551275463989
+        Example:
+            get_magnitude((2, 3, 4)) #returns: 5.385164807134504
+            get_magnitude((2, 3)) #returns: 3.605551275463989
         """
         from math import sqrt
 
         n = len(vector)  # determine 2 or 3d vector.
         return sqrt(sum(vector[i] * vector[i] for i in range(n)))
 
     @classmethod
     def dot_product(cls, v1, v2, normalize_input=False):
         """Returns the dot product of two 3D float arrays.  If $normalize_input
         is set then the vectors are normalized before the dot product is calculated.
 
         Parameters:
-                v1 (tuple): The first 3 point vector.
-                v2 (tuple): The second 3 point vector.
-                normalize_input (int): Normalize v1, v2 before calculating the point float list.
+            v1 (tuple): The first 3 point vector.
+            v2 (tuple): The second 3 point vector.
+            normalize_input (int): Normalize v1, v2 before calculating the point float list.
 
         Returns:
-                (float) Dot product of the two vectors.
+            (float) Dot product of the two vectors.
 
-        Example: dot_product((1, 2, 3), (1, 1, -1)) #returns: 0
-        Example: dot_product((1, 2), (1, 1)) #returns: 3
+        Example:
+            dot_product((1, 2, 3), (1, 1, -1)) #returns: 0
+            dot_product((1, 2), (1, 1)) #returns: 3
         """
         if normalize_input:  # normalize the input vectors
             v1 = cls.normalize(v1)
             v2 = cls.normalize(v2)
 
         return sum((a * b) for a, b in zip(v1, v2))  # the dot product
 
     @classmethod
     def cross_product(cls, a, b, c=None, normalize=0):
         """Get the cross product of two vectors, using two 3d vectors, or 3 points.
 
         Parameters:
-                a (tuple): A point represented as x,y,z or a 3 point vector.
-                b (tuple): A point represented as x,y,z or a 3 point vector.
-                c (tuple): A point represented as x,y,z (used only when working with 3 point values instead of 2 vectors).
-                normalize (float) = (0) Do not normalize. (1) Normalize standard. (value other than 0 or 1) Normalize using the given float value as desired length.
+            a (tuple): A point represented as x,y,z or a 3 point vector.
+            b (tuple): A point represented as x,y,z or a 3 point vector.
+            c (tuple): A point represented as x,y,z (used only when working with 3 point values instead of 2 vectors).
+            normalize (float): (0) Do not normalize. (1) Normalize standard. (value other than 0 or 1) Normalize using the given float value as desired length.
 
         Returns:
-                (tuple)
+            (tuple)
 
-        Example: cross_product((1, 2, 3), (1, 1, -1)) #returns: (-5, 4, -1),
-        Example: cross_product((3, 1, 1), (1, 4, 2), (1, 3, 4)) #returns: (7, 4, 2),
-        Example: cross_product((1, 2, 3), (1, 1, -1), None, 1) #returns: (-0.7715167498104595, 0.6172133998483676, -0.1543033499620919)
+        Example:
+            cross_product((1, 2, 3), (1, 1, -1)) #returns: (-5, 4, -1),
+            cross_product((3, 1, 1), (1, 4, 2), (1, 3, 4)) #returns: (7, 4, 2),
+            cross_product((1, 2, 3), (1, 1, -1), None, 1) #returns: (-0.7715167498104595, 0.6172133998483676, -0.1543033499620919)
         """
         if c is not None:  # convert points to vectors and unpack.
             a = cls.get_vector_from_two_points(a, b)
             b = cls.get_vector_from_two_points(b, c)
 
         ax, ay, az = a
         bx, by, bz = b
@@ -162,24 +167,25 @@
         return result
 
     @classmethod
     def move_point_relative(cls, p, d, v=None):
         """Move a point relative to it's current position.
 
         Parameters:
-                p (tuple): A points x, y, z values.
-                d (tuple)(float) = The distance to move. Use a float value when moving along a vector,
-                                        and a point value to move in a given distance.
-                v (tuple): Optional: A vectors x, y, z values can be given to move the point along that vector.
+            p (tuple): A points x, y, z values.
+            d (tuple)(float): The distance to move. Use a float value when moving along a vector,
+                                    and a point value to move in a given distance.
+            v (tuple): Optional: A vectors x, y, z values can be given to move the point along that vector.
 
         Returns:
-                (tuple) point.
+            (tuple) point.
 
-        Example: move_point_relative((0, 5, 0), (0, 5, 0)) #returns: (0, 10, 0)
-        Example: move_point_relative((0, 5, 0), 5, (0, 1, 0)) #returns: (0, 10, 0)
+        Example:
+            move_point_relative((0, 5, 0), (0, 5, 0)) #returns: (0, 10, 0)
+            move_point_relative((0, 5, 0), 5, (0, 1, 0)) #returns: (0, 10, 0)
         """
         x, y, z = p
 
         if v is not None:  # move along a vector if one is given.
             assert isinstance(
                 d, (float, int)
             ), "# Error: {}\n  The distance parameter requires an integer or float value when moving along a vector.\n  {} {} given. #".format(
@@ -199,22 +205,22 @@
         return result
 
     @classmethod
     def move_point_relative_along_vector(cls, a, b, vect, dist, toward=True):
         """Move a point (a) along a given vector toward or away from a given point (b).
 
         Parameters:
-                a (tuple): The point to move given as (x,y,z).
-                b (tuple): The point to move toward.
-                vect (tuple): A vector to move the point along.
-                dist (float) = The linear amount to move the point.
-                toward (bool): Move the point toward or away from.
+            a (tuple): The point to move given as (x,y,z).
+            b (tuple): The point to move toward.
+            vect (tuple): A vector to move the point along.
+            dist (float): The linear amount to move the point.
+            toward (bool): Move the point toward or away from.
 
         Returns:
-                (tuple) point.
+            (tuple) point.
 
         Example: move_point_relative_along_vector((0, 0, 0), (0, 10, 0), (0, 1, 0), 5) #returns: (0.0, 5.0, 0.0)
         Example: move_point_relative_along_vector((0, 0, 0), (0, 10, 0), (0, 1, 0), 5, False) #returns: (0.0, -15.0, 0.0)
         """
         lowest = None
         for i in [
             dist,
@@ -229,54 +235,55 @@
 
     @staticmethod
     def get_distance(a: List[float], b: List[float]) -> float:
         """
         Calculate the distance between two points.
 
         Parameters:
-                a (List[float]): A list of the first point's coordinates [x, y, z].
-                b (List[float]): A list of the second point's coordinates [x, y, z].
+            a (List[float]): A list of the first point's coordinates [x, y, z].
+            b (List[float]): A list of the second point's coordinates [x, y, z].
 
         Returns:
-                float: The distance between the two points.
+            float: The distance between the two points.
         """
         return ((b[0] - a[0]) ** 2 + (b[1] - a[1]) ** 2 + (b[2] - a[2]) ** 2) ** 0.5
 
     @staticmethod
     def get_center_of_two_points(
         a: List[float], b: List[float]
     ) -> Tuple[float, float, float]:
         """Get the point in the middle of two given points.
 
         Parameters:
-                a (List[float]): A point given as [x, y, z].
-                b (List[float]): A point given as [x, y, z].
+            a (List[float]): A point given as [x, y, z].
+            b (List[float]): A point given as [x, y, z].
 
         Returns:
-                Tuple[float, float, float]: The center point between the two input points.
+            Tuple[float, float, float]: The center point between the two input points.
 
         Example:
-                get_center_of_two_points([0, 10, 0], [0, 5, 0]) #returns: (0.0, 7.5, 0.0)
+            get_center_of_two_points([0, 10, 0], [0, 5, 0]) #returns: (0.0, 7.5, 0.0)
         """
         return ((a[0] + b[0]) / 2, (a[1] + b[1]) / 2, (a[2] + b[2]) / 2)
 
     @classmethod
     def get_angle_from_two_vectors(cls, v1, v2, degree=False):
         """Get an angle from two given vectors.
 
         Parameters:
-                v1 (tuple): A vectors xyz values as a tuple.
-                v2 (tuple): A vectors xyz values as a tuple.
-                degree (bool): Convert the radian result to degrees.
+            v1 (tuple): A vectors xyz values as a tuple.
+            v2 (tuple): A vectors xyz values as a tuple.
+            degree (bool): Convert the radian result to degrees.
 
         Returns:
-                (float)
+            (float)
 
-        Example: get_angle_from_two_vectors((1, 2, 3), (1, 1, -1)) #returns: 1.5707963267948966,
-        Example: get_angle_from_two_vectors((1, 2, 3), (1, 1, -1), True) #returns: 90
+        Example:
+            get_angle_from_two_vectors((1, 2, 3), (1, 1, -1)) #returns: 1.5707963267948966,
+            get_angle_from_two_vectors((1, 2, 3), (1, 1, -1), True) #returns: 90
         """
         from math import acos, degrees
 
         def length(v):
             return (cls.dot_product(v, v)) ** 0.5
 
         result = acos(cls.dot_product(v1, v2) / (length(v1) * length(v2)))
@@ -286,24 +293,25 @@
         return result
 
     @staticmethod
     def get_angle_from_three_points(a, b, c, degree=False):
         """Get the opposing angle from 3 given points.
 
         Parameters:
-                a (tuple): A point given as (x,y,z).
-                b (tuple): A point given as (x,y,z).
-                c (tuple): A point given as (x,y,z).
-                degree (bool): Convert the radian result to degrees.
+            a (tuple): A point given as (x,y,z).
+            b (tuple): A point given as (x,y,z).
+            c (tuple): A point given as (x,y,z).
+            degree (bool): Convert the radian result to degrees.
 
         Returns:
-                (float)
+            (float)
 
-        Example: get_angle_from_three_points((1, 1, 1), (-1, 2, 3), (1, 4, -3)) #returns: 0.7904487543360762,
-        Example: get_angle_from_three_points((1, 1, 1), (-1, 2, 3), (1, 4, -3), True) #returns: 45.29
+        Example:
+            get_angle_from_three_points((1, 1, 1), (-1, 2, 3), (1, 4, -3)) #returns: 0.7904487543360762,
+            get_angle_from_three_points((1, 1, 1), (-1, 2, 3), (1, 4, -3), True) #returns: 45.29
         """
         from math import sqrt, acos, degrees
 
         ba = [aa - bb for aa, bb in zip(a, b)]  # create vectors from points
         bc = [cc - bb for cc, bb in zip(c, b)]
 
         nba = sqrt(sum((x**2.0 for x in ba)))  # normalize vector
@@ -323,23 +331,24 @@
         return angle
 
     @staticmethod
     def get_two_sides_of_asa_triangle(a1, a2, s, unit="degrees"):
         """Get the length of two sides of a triangle, given two angles, and the length of the side in-between.
 
         Parameters:
-                a1 (float) = Angle in radians or degrees. (unit flag must be set if value given in radians)
-                a2 (float) = Angle in radians or degrees. (unit flag must be set if value given in radians)
-                s (float) = The distance of the side between the two given angles.
-                unit (str): Specify whether the angle values are given in degrees or radians. (valid: 'radians', 'degrees')(default: degrees)
+            a1 (float): Angle in radians or degrees. (unit flag must be set if value given in radians)
+            a2 (float): Angle in radians or degrees. (unit flag must be set if value given in radians)
+            s (float): The distance of the side between the two given angles.
+            unit (str): Specify whether the angle values are given in degrees or radians. (valid: 'radians', 'degrees')(default: degrees)
 
         Returns:
-                (tuple)
+            (tuple)
 
-        Example: get_two_sides_of_asa_triangle(60, 60, 100) #returns: (100.00015320566493, 100.00015320566493)
+        Example:
+            get_two_sides_of_asa_triangle(60, 60, 100) #returns: (100.00015320566493, 100.00015320566493)
         """
         from math import sin, radians
 
         if unit == "degrees":
             a1, a2 = radians(a1), radians(a2)
 
         a3 = 3.14159 - a1 - a2
@@ -351,24 +360,25 @@
     @classmethod
     def xyz_rotation(cls, theta, axis, rotation=[], degree=False):
         """Get the rotation about the X,Y,Z axes (in rotation) given
         an angle for rotation (in radians) and an axis about which to
         do the rotation.
 
         Parameters:
-                theta (float) = The angular position of a vector in radians.
-                axis (tuple): The rotation axis given as float values (x,y,z).
-                rotation (list):
-                degree (bool): Convert the radian result to degrees.
+            theta (float):The angular position of a vector in radians.
+            axis (tuple): The rotation axis given as float values (x,y,z).
+            rotation (list):
+            degree (bool): Convert the radian result to degrees.
 
         Returns:
-                (tuple) 3 point rotation.
+            (tuple) 3 point rotation.
 
-        Example: xyz_rotation(2, (0, 1, 0)) #returns: [3.589792907376932e-09, 1.9999999964102069, 3.589792907376932e-09]
-        Example: xyz_rotation(2, (0, 1, 0), [], True) #returns: [0.0, 114.59, 0.0]
+        Example:
+            xyz_rotation(2, (0, 1, 0)) #returns: [3.589792907376932e-09, 1.9999999964102069, 3.589792907376932e-09]
+            xyz_rotation(2, (0, 1, 0), [], True) #returns: [0.0, 114.59, 0.0]
         """
         from math import cos, sin, sqrt, atan2, degrees
 
         # set up the xyzw quaternion values
         theta *= 0.5
         w = cos(theta)
         factor = sin(theta)
@@ -424,26 +434,25 @@
             rotation = [atan2(-matrix[9], matrix[5]), atan2(-matrix[2], cosB), 0.0]
 
         if degree:
             rotation = [round(degrees(r), 2) for r in rotation]
         return tuple(rotation)
 
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 
 if __name__ == "__main__":
     pass
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 # Notes
-# --------------------------------------------------------------------------------------------
-
+# -----------------------------------------------------------------------------
 
-# Deprecated ------------------------------------
 
+# deprecated ---------------------
 # @classmethod
 # def normalize(cls, vector, amount=1):
 #   '''Normalize a vector
 
 #   Parameters:
 #       vector (vector) = The vector to normalize.
 #       amount (float) = (1) Normalize standard. (value other than 0 or 1) Normalize using the given float value as desired length.
```

### Comparing `pythontk-0.6.6/pythontk/misc_utils.py` & `pythontk-0.6.7/pythontk/utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,26 +2,25 @@
 # coding=utf-8
 import functools
 import inspect
 import collections.abc
 from typing import Any, Callable
 
 # from this package:
-from pythontk.iter_utils import Iter
+from pythontk.iter_utils import IterUtils
 
 
-class Misc:
+class Utils:
     """ """
 
     @staticmethod
     def cached_property(func: Callable) -> Any:
         """Decorator that converts a method with a single self argument into a property
         that runs the method only once and stores the result, returning the stored
         result on subsequent accesses.
-
         This is useful for expensive computations that don't change once computed.
 
         Parameters:
             func: Method to be converted into a cached property.
 
         Returns:
             A descriptor object that can be used as a decorator.
@@ -38,15 +37,15 @@
             return getattr(self, attr_name)
 
         return _cached_property
 
     @staticmethod
     def listify(func=None, arg_name=None, threading=False):
         if func is None:
-            return lambda func: Misc.listify(func, arg_name=arg_name)
+            return lambda func: Utils.listify(func, arg_name=arg_name)
 
         @functools.wraps(func)
         def wrapper(*args, **kwargs):
             func_args = inspect.getfullargspec(func).args
             if "self" in func_args or "cls" in func_args:
                 func_args = func_args[1:]  # skip 'self' or 'cls' argument for methods
 
@@ -89,19 +88,19 @@
     @classmethod
     def format_return(cls, lst, orig=None):
         """Return the list element if the given iterable only contains a single element.
         If the list contains multiple elements, always return the full list.
         If the 'orig' arg is a multi-element type then the original format will always be returned.
 
         Parameters:
-                lst (list): An iterable.
-                orig (obj): Optionally; derive the return type form the original value.
-                                ie. if it was a multi-value type; do not modify the return value.
+            lst (list): An iterable.
+            orig (obj): Optionally; derive the return type form the original value.
+                            ie. if it was a multi-value type; do not modify the return value.
         Returns:
-                (obj/list) dependant on flags.
+            (obj/list) dependant on flags.
         """
         orig_was_iter = isinstance(orig, (list, tuple, set, dict, range))
 
         if (
             len(lst) == 1
             and not orig_was_iter
             and not isinstance(lst, (str, bytes, bytearray))
@@ -111,50 +110,50 @@
         return lst if orig_was_iter or len(lst) > 1 else None
 
     @staticmethod
     def set_attributes(obj, **attributes):
         """Set attributes for a given object.
 
         Parameters:
-                obj (obj): The object to set attributes for.
-                attributes (kwargs) = Attributes and their correponding values as keyword args.
+            obj (obj): The object to set attributes for.
+            attributes (kwargs) = Attributes and their correponding values as keyword args.
         """
         [
             setattr(obj, attr, value)
             for attr, value in attributes.items()
             if attr and value
         ]
 
     @staticmethod
     def get_attributes(obj, inc=[], exc=[]):
         """Get attributes for a given object.
 
         Parameters:
-                obj (obj): The object to get the attributes of.
-                inc (list): Attributes to include. All other will be omitted. Exclude takes dominance over include. Meaning, if the same attribute is in both lists, it will be excluded.
-                exc (list): Attributes to exclude from the returned dictionay. ie. [u'Position',u'Rotation',u'Scale',u'renderable',u'isHidden',u'isFrozen',u'selected']
+            obj (obj): The object to get the attributes of.
+            inc (list): Attributes to include. All other will be omitted. Exclude takes dominance over include. Meaning, if the same attribute is in both lists, it will be excluded.
+            exc (list): Attributes to exclude from the returned dictionay. ie. [u'Position',u'Rotation',u'Scale',u'renderable',u'isHidden',u'isFrozen',u'selected']
 
         Returns:
-                (dict) {'string attribute': current value}
+            (dict) {'string attribute': current value}
         """
-        filtered = Iter.filter_list(obj.__dict__, inc, exc)
+        filtered = IterUtils.filter_list(obj.__dict__, inc, exc)
         return {attr: getattr(obj, attr) for attr in filtered}
 
     @staticmethod
     def has_attribute(cls, attr):
         """This function checks whether a class has a specific static attribute by using `inspect.getattr_static`.
         It does not invoke the class's `__getattr__` method, so it is useful for checking if an attribute is defined
         on the class itself, rather than on its instances.
 
         Parameters:
-                cls (obj): The class to check for the attribute.
-                attr (str): The name of the attribute to check.
+            cls (obj): The class to check for the attribute.
+            attr (str): The name of the attribute to check.
 
-        :return:
-                (bool) True if the class has the attribute, False otherwise.
+        Returns:
+            (bool) True if the class has the attribute, False otherwise.
         """
         import inspect
 
         try:
             inspect.getattr_static(cls, attr)
             return True
         except AttributeError:
@@ -206,18 +205,19 @@
     def cycle(cls, sequence, name=None, query=False):
         """Toggle between numbers in a given sequence.
         Used for maintaining toggling sequences for multiple objects simultaniously.
         Each time this function is called, it returns the next number in the sequence
         using the name string as an identifier key.
 
         Parameters:
-                sequence (list): sequence to cycle through. ie. [1,2,3].
-                name (str): identifier. used as a key to get the sequence value from the dict.
+            sequence (list): sequence to cycle through. ie. [1,2,3].
+            name (str): identifier. used as a key to get the sequence value from the dict.
 
-        ex. cycle([0,1,2,3,4], 'componentID')
+        Example:
+            cycle([0,1,2,3,4], 'componentID')
         """
         try:
             if query:  # return the value without changing it.
                 return cls.CYCLEDICT[name][-1]  # get the current value ie. 0
 
             value = cls.CYCLEDICT[
                 name
@@ -228,69 +228,69 @@
 
         value = cls.CYCLEDICT[name][0]  # get the current value. ie. 1
         cls.CYCLEDICT[name] = cls.CYCLEDICT[name][1:] + [
             value
         ]  # move the current value to the end of the list. ie. [2,3,1]
         return value  # return current value. ie. 1
 
-    @staticmethod
-    def are_similar(a, b, tolerance=0.0):
+    @classmethod
+    def are_similar(cls, a, b, tolerance=0.0):
         """Check if the two numberical values are within a given tolerance.
         Supports nested lists.
 
         Parameters:
-                a (obj)(tuple): The first object(s) to compare.
-                b (obj)(tuple): The second object(s) to compare.
-                tolerance (float) = The maximum allowed variation between the values.
+            a (obj)(tuple): The first object(s) to compare.
+            b (obj)(tuple): The second object(s) to compare.
+            tolerance (float) = The maximum allowed variation between the values.
 
         Returns:
-                (bool)
+            (bool)
 
-        Example: are_similar(1, 10, 9)" #returns: True
-        Example: are_similar(1, 10, 8)" #returns: False
+        Example:
+            are_similar(1, 10, 9)" #returns: True
+            are_similar(1, 10, 8)" #returns: False
         """
         func = (
             lambda a, b: abs(a - b) <= tolerance
             if isinstance(a, (int, float))
             else True
-            if isinstance(a, (list, set, tuple)) and are_similar(a, b, tolerance)
+            if isinstance(a, (list, set, tuple)) and cls.are_similar(a, b, tolerance)
             else a == b
         )
-        return all(map(func, Iter.make_iterable(a), Iter.make_iterable(b)))
+        return all(map(func, IterUtils.make_iterable(a), IterUtils.make_iterable(b)))
 
     @staticmethod
     def randomize(lst, ratio=1.0):
         """Random elements from the given list will be returned with a quantity determined by the given ratio.
         A value of 0.5 will return 50% of the original elements in random order.
 
         Parameters:
-                lst (tuple): A list to randomize.
-                ratio (float) = A value of 0.0-1. (default: 100%) With 0 representing 0% and
-                                1 representing 100% of the given elements returned in random order.
+            lst (tuple): A list to randomize.
+            ratio (float) = A value of 0.0-1. (default: 100%) With 0 representing 0% and
+                            1 representing 100% of the given elements returned in random order.
         Returns:
-                (list)
+            (list)
 
-        Example: randomize(range(10), 1.0) #returns: [8, 4, 7, 6, 0, 5, 9, 1, 3, 2]
-        Example: randomize(range(10), 0.5) #returns: [7, 6, 4, 2, 8]
+        Example:
+            randomize(range(10), 1.0) #returns: [8, 4, 7, 6, 0, 5, 9, 1, 3, 2]
+            randomize(range(10), 0.5) #returns: [7, 6, 4, 2, 8]
         """
         import random
 
         lower, upper = 0.0, ratio if ratio <= 1 else 1.0  # end result range.
         normalized = lower + (upper - lower) * len(lst)  # returns a float value.
         randomized = random.sample(lst, int(normalized))
 
         return randomized
 
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 
 if __name__ == "__main__":
     pass
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 # Notes
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 
 
-# --------------------------------------------------------------------------------------------
-# deprecated:
-# --------------------------------------------------------------------------------------------
+# deprecated ---------------------
```

### Comparing `pythontk-0.6.6/pythontk/str_utils.py` & `pythontk-0.6.7/pythontk/str_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,28 @@
 # !/usr/bin/python
 # coding=utf-8
 # from this package:
-from pythontk.misc_utils import Misc
-from pythontk.iter_utils import Iter
+from pythontk.utils import Utils
+from pythontk.iter_utils import IterUtils
 
 
-class Str:
+class StrUtils:
     """ """
 
     @staticmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def set_case(string, case="title"):
         """Format the given string(s) in the given case.
 
         Parameters:
-                string (str/list): The string(s) to format.
-                case (str): The desired return case. Accepts all python case operators.
-                        valid: 'upper', 'lower', 'capitalize' (default), 'swapcase', 'title', 'pascal', 'camel', None.
-
+            string (str/list): The string(s) to format.
+            case (str): The desired return case. Accepts all python case operators.
+                    valid: 'upper', 'lower', 'capitalize' (default), 'swapcase', 'title', 'pascal', 'camel', None.
         Returns:
-                (str/list) List if 'string' given as list.
+            (str/list) List if 'string' given as list.
         """
         if (not string) or (not isinstance(string, str)):
             return ""
 
         if case == "pascal":
             return string[:1].capitalize() + string[1:]  # capitalize the first letter.
 
@@ -72,35 +71,35 @@
 
     @staticmethod
     def get_text_between_delimiters(string, start_delim, end_delim, as_string=False):
         """Get any text between the specified start and end delimiters in the given string. The text can be returned as a
         generator (default behavior) or as a single concatenated string if `as_string` is set to True.
 
         Parameters:
-                string (str): The input string to search for matches.
-                start_delim (str): The starting delimiter to search for.
-                end_delim (str): The ending delimiter to search for.
-                as_string (bool, optional): If True, the function returns a single concatenated string of all matches.
-                                                                         If False (default), the function returns a generator that yields each match.
+            string (str): The input string to search for matches.
+            start_delim (str): The starting delimiter to search for.
+            end_delim (str): The ending delimiter to search for.
+            as_string (bool, optional): If True, the function returns a single concatenated string of all matches.
+                                                                     If False (default), the function returns a generator that yields each match.
 
         Returns:
-                If as_string is False (default): A generator that yields all matches found in the input string.
-                If as_string is True: A single concatenated string containing all matches found in the input string.
+            If as_string is False (default): A generator that yields all matches found in the input string.
+            If as_string is True: A single concatenated string containing all matches found in the input string.
 
         Examples:
-                input_string = "Here is the <!-- start -->first match<!-- end --> and here is the <!-- start -->second match<!-- end -->"
+            input_string = "Here is the <!-- start -->first match<!-- end --> and here is the <!-- start -->second match<!-- end -->"
 
-                # Get the matches as a generator (default behavior)
-                matches_generator = get_text_between_delimiters(input_string, '<!-- start -->', '<!-- end -->')
-                for match in matches_generator:
-                        print(match)  # Output: first match (first iteration), second match (second iteration)
-
-                # Get the matches as a single string
-                matches_string = get_text_between_delimiters(input_string, '<!-- start -->', '<!-- end -->', as_string=True)
-                print(matches_string)  # Output: "first match second match"
+            # Get the matches as a generator (default behavior)
+            matches_generator = get_text_between_delimiters(input_string, '<!-- start -->', '<!-- end -->')
+            for match in matches_generator:
+                    print(match)  # Output: first match (first iteration), second match (second iteration)
+
+            # Get the matches as a single string
+            matches_string = get_text_between_delimiters(input_string, '<!-- start -->', '<!-- end -->', as_string=True)
+            print(matches_string)  # Output: "first match second match"
         """
         import re
 
         def extract_matches(string, start_delim, end_delim, start_index=0):
             pattern = re.compile(
                 f"{re.escape(start_delim)}(.*?){re.escape(end_delim)}", re.DOTALL
             )
@@ -152,15 +151,15 @@
             target = "polygons.mesh"
             get_matching_hierarchy_items(hierarchy_items, target, upstream=True) -> ['polygons']
             get_matching_hierarchy_items(hierarchy_items, target, downstream=True) -> ['polygons|mesh|submenu', 'polygons|mesh|other']
             get_matching_hierarchy_items(hierarchy_items, target, exact=True) -> ['polygons|mesh']
         """
         import re
 
-        pattern = "|".join(re.escape(d) for d in Iter.make_iterable(delimiters))
+        pattern = "|".join(re.escape(d) for d in IterUtils.make_iterable(delimiters))
         target_parts = re.split(pattern, target)
 
         def match_hierarchy(item_parts):
             return all(p1 == p2 for p1, p2 in zip(item_parts, target_parts))
 
         def is_upstream(item_parts):
             return len(item_parts) < len(target_parts)
@@ -184,68 +183,68 @@
                 return True
             return False
 
         matches = [item for item in hierarchy_items if filter_items(item)]
         return sorted(matches, key=lambda x: len(x), reverse=reverse)
 
     @staticmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def split_at_chars(string, chars="|", occurrence=-1):
         """Split a string containing the given chars at the given occurrence and return
         a two element tuple containing both halves.
 
         Parameters:
-                strings (str/list): The string(s) to operate on.
-                chars (str): The chars to split at.
-                occurrence (int): The occurrence of the pipe to split at from left.
-                        ex. -1 would split at the last occurrence. 0 would split at the first.
-                                If the occurrence is out of range, the full string will be
-                                returned as: ('original string', '')
+            strings (str/list): The string(s) to operate on.
+            chars (str): The chars to split at.
+            occurrence (int): The occurrence of the pipe to split at from left.
+                    ex. -1 would split at the last occurrence. 0 would split at the first.
+                        If the occurrence is out of range, the full string will be
+                        returned as: ('original string', '')
         Returns:
-                (tuple)(list) two element tuple, or list of two element tuples if multiple strings given.
+            (tuple)(list) two element tuple, or list of two element tuples if multiple strings given.
 
-        Example: split_at_chars(['str|ing', 'string']) returns: [('str', 'ing'), ('string', '')]
+        Example:
+            split_at_chars(['str|ing', 'string']) returns: [('str', 'ing'), ('string', '')]
         """
         split = string.split(chars)
 
         try:
             s2 = "".join(split[occurrence])
             if chars in string:
                 s1 = chars.join(split[:occurrence])
                 return (s1, s2)
             else:
                 return (s2, "")
-        except IndexError as error:
+        except IndexError:
             return (string, "")
 
     @classmethod
     def insert(cls, src, ins, at, occurrence=1, before=False):
         """Insert character(s) into a string at a given location.
         if the character doesn't exist, the original string will be returned.
 
         Parameters:
-                src (str): The source string.
-                ins (str): The character(s) to insert.
-                at (str)(int): The index or char(s) to insert at.
-                occurrence (int): Specify which occurrence to insert at.
-                                                Valid only when 'at' is given as a string.
-                                                default: The first occurrence.
-                                                (A value of -1 would insert at the last occurrence)
-                before (bool): Specify inserting before or after. default: after
-                                                Valid only when 'at' is given as a string.
+            src (str): The source string.
+            ins (str): The character(s) to insert.
+            at (str)(int): The index or char(s) to insert at.
+            occurrence (int): Specify which occurrence to insert at.
+                        Valid only when 'at' is given as a string.
+                        default: The first occurrence.
+                        (A value of -1 would insert at the last occurrence)
+            before (bool): Specify inserting before or after. default: after
+                        Valid only when 'at' is given as a string.
         Returns:
-                (str)
+            (str)
         """
         try:
             return "".join((src[:at], str(ins), src[at:]))
 
         except TypeError:
-            if (
-                occurrence < 0
-            ):  # if 'occurrance' is a negative value, search from the right.
+            # if 'occurrance' is a negative value, search from the right.
+            if occurrence < 0:
                 i = src.replace(at, " " * len(at), occurrence - 1).rfind(at)
             else:
                 i = src.replace(at, " " * len(at), occurrence - 1).find(at)
             return (
                 cls.insert(src, str(ins), i if before else i + len(at))
                 if i != -1
                 else src
@@ -253,45 +252,46 @@
 
     @staticmethod
     def rreplace(string, old, new="", count=None):
         """Replace occurrances in a string from right to left.
         The number of occurrances replaced can be limited by using the 'count' argument.
 
         Parameters:
-                string (str):
-                old (str):
-                new (str)(int):
-                count (int):
+            string (str):
+            old (str):
+            new (str)(int):
+            count (int):
 
         Returns:
-                (str)
+            (str)
         """
         if not string or not isinstance(string, str):
             return string
 
         if count is not None:
             return str(new).join(string.rsplit(old, count))
         else:
             return str(new).join(string.rsplit(old))
 
     @staticmethod
-    @Misc.listify(threading=True)
+    @Utils.listify(threading=True)
     def truncate(string, length=75, beginning=True, insert=".."):
         """Shorten the given string to the given length.
         An ellipsis will be added to the section trimmed.
 
         Parameters:
-                length (int): The maximum allowed length before trunicating.
-                beginning (bool): Trim starting chars, else; ending.
-                insert (str): Chars to add at the trimmed area. (default: ellipsis)
+            length (int): The maximum allowed length before trunicating.
+            beginning (bool): Trim starting chars, else; ending.
+            insert (str): Chars to add at the trimmed area. (default: ellipsis)
 
         Returns:
-                (str)
+            (str)
 
-        Example: truncate('12345678', 4) #returns: '..5678'
+        Example:
+            truncate('12345678', 4) #returns: '..5678'
         """
         if not string or not isinstance(string, str):
             return string
 
         if len(string) > length:
             if beginning:  # trim starting chars.
                 string = insert + string[-length:]
@@ -300,22 +300,23 @@
         return string
 
     @staticmethod
     def get_trailing_integers(string, inc=0, as_string=False):
         """Returns any integers from the end of the given string.
 
         Parameters:
-                inc (int): Increment by a step amount. (default: 0)
-                                0 does not increment and returns the original number.
-                as_string (bool): Return the integers as a string instead of integers.
+            inc (int): Increment by a step amount. (default: 0)
+                    0 does not increment and returns the original number.
+            as_string (bool): Return the integers as a string instead of integers.
 
-        "Returns:
-                (int)
+        Returns:
+            (int)
 
-        ex. get_trailing_integers('p001Cube1', inc=1) #returns: 2
+        Example:
+            get_trailing_integers('p001Cube1', inc=1) #returns: 2
         """
         import re
 
         if not string or not isinstance(string, str):
             return string
 
         m = re.findall(r"\d+\s*$", string)
@@ -326,37 +327,38 @@
         return result
 
     @staticmethod
     def find_str(find, strings, regex=False, ignore_case=False):
         """Filter for elements that containing the given string in a list of strings.
 
         Parameters:
-                find (str): The search string. An asterisk denotes startswith*, *endswith, *contains*, and multiple search strings can be separated by pipe chars.
-                        wildcards:
-                                *chars* - string contains chars.
-                                *chars - string endswith chars.
-                                chars* - string startswith chars.
-                                chars1|chars2 - string matches any of.  can be used in conjuction with other modifiers.
-                        regular expressions (if regex True):
-                                (.) match any char. ex. re.match('1..', '1111') #returns the regex object <111>
-                                (^) match start. ex. re.match('^11', '011') #returns None
-                                ($) match end. ex. re.match('11$', '011') #returns the regex object <11>
-                                (|) or. ex. re.match('1|0', '011') #returns the regex object <0>
-                                (\A,\Z) beginning of a string and end of a string. ex. re.match(r'\A011\Z', '011') #
-                                (\b) empty string. (\B matches the empty string anywhere else). ex. re.match(r'\b(011)\b', '011 011 011') #
-                strings (list): The string list to search.
-                regex (bool): Use regular expressions instead of wildcards.
-                ignore_case (bool): Search case insensitive.
-
-        Returns:
-                (list)
-
-        ex. lst = ['invertVertexWeights', 'keepCreaseEdgeWeight', 'keepBorder', 'keepBorderWeight', 'keepColorBorder', 'keepColorBorderWeight']
-                find_str('*Weight*', lst) #find any element that contains the string 'Weight'.
-                find_str('Weight$|Weights$', lst, regex=True) #find any element that endswith 'Weight' or 'Weights'.
+            find (str): The search string. An asterisk denotes startswith*, *endswith, *contains*, and multiple search strings can be separated by pipe chars.
+                    wildcards:
+                        *chars* - string contains chars.
+                        *chars - string endswith chars.
+                        chars* - string startswith chars.
+                        chars1|chars2 - string matches any of.  can be used in conjuction with other modifiers.
+                    regular expressions (if regex True):
+                        (.) match any char. ex. re.match('1..', '1111') #returns the regex object <111>
+                        (^) match start. ex. re.match('^11', '011') #returns None
+                        ($) match end. ex. re.match('11$', '011') #returns the regex object <11>
+                        (|) or. ex. re.match('1|0', '011') #returns the regex object <0>
+                        (\A,\Z) beginning of a string and end of a string. ex. re.match(r'\A011\Z', '011') #
+                        (\b) empty string. (\B matches the empty string anywhere else). ex. re.match(r'\b(011)\b', '011 011 011') #
+            strings (list): The string list to search.
+            regex (bool): Use regular expressions instead of wildcards.
+            ignore_case (bool): Search case insensitive.
+
+        Returns:
+            (list)
+
+        Example:
+            lst = ['invertVertexWeights', 'keepCreaseEdgeWeight', 'keepBorder', 'keepBorderWeight', 'keepColorBorder', 'keepColorBorderWeight']
+            find_str('*Weight*', lst) #find any element that contains the string 'Weight'.
+            find_str('Weight$|Weights$', lst, regex=True) #find any element that endswith 'Weight' or 'Weights'.
         """
         if regex:  # search using a regular expression.
             import re
 
             try:
                 if ignore_case:
                     result = [i for i in strings if re.search(find, i, re.IGNORECASE)]
@@ -417,110 +419,99 @@
         regex=False,
         ignore_case=False,
         return_orig_strings=False,
     ):
         """Expanding on the 'find_str' function: Find matches of a string in a list of strings and re-format them.
 
         Parameters:
-                strings (list): A list of string objects to search.
-                to (str): An optional asterisk modifier can be used for formatting. An empty string will attempt to remove the part of the string designated in the from argument.
-                        "" - (empty string) - strip chars.
-                        *chars* - replace only.
-                        *chars - replace suffix.
-                        **chars - append suffix.
-                        chars* - replace prefix.
-                        chars** - append prefix.
-                fltr (str): See the 'find_str' function's 'fltr' parameter for documentation.
-                regex (bool): Use regular expressions instead of wildcards for the 'find' argument.
-                ignore_case (bool): Ignore case when searching. Applies only to the 'fltr' parameter's search.
-                return_orig_strings (bool): Return the old names as well as the new.
+            strings (list): A list of string objects to search.
+            to (str): An optional asterisk modifier can be used for formatting. An empty string will attempt to remove the part of the string designated in the from argument.
+                    "" - (empty string) - strip chars.
+                    *chars* - replace only.
+                    *chars - replace suffix.
+                    **chars - append suffix.
+                    chars* - replace prefix.
+                    chars** - append prefix.
+            fltr (str): See the 'find_str' function's 'fltr' parameter for documentation.
+            regex (bool): Use regular expressions instead of wildcards for the 'find' argument.
+            ignore_case (bool): Ignore case when searching. Applies only to the 'fltr' parameter's search.
+            return_orig_strings (bool): Return the old names as well as the new.
 
         Returns:
-                (list) if return_orig_strings: list of two element tuples containing the original and modified string pairs. [('frm','to')]
-                        else: a list of just the new names.
+            (list) if return_orig_strings: list of two element tuples containing the original and modified string pairs. [('frm','to')]
+                    else: a list of just the new names.
         """
         import re
 
-        if (
-            fltr
-        ):  # if 'fltr' is not an empty string; fltr 'strings' for matches using 'fltr'.
+        # if 'fltr' is not an empty string; fltr 'strings' for matches using 'fltr'.
+        if fltr:
             strings = cls.find_str(fltr, strings, regex=regex, ignore_case=ignore_case)
 
-        frm_ = fltr.strip("*").rstrip(
-            "*"
-        )  # re.sub('[^A-Za-z0-9_:]+', '', fltr) #strip any special chars other than '_'.
-        to_ = to.strip("*").rstrip(
-            "*"
-        )  # remove any modifiers from the left and right end chars.
+        # re.sub('[^A-Za-z0-9_:]+', '', fltr) #strip any special chars other than '_'.
+        frm_ = fltr.strip("*").rstrip("*")
+        # remove any modifiers from the left and right end chars.
+        to_ = to.strip("*").rstrip("*")
 
         result = []
         for orig_str in strings:
             # modifiers
             if to.startswith("*") and to.endswith("*"):  # replace chars
                 if ignore_case:
-                    s = re.sub(
-                        frm_, to_, orig_str, flags=re.IGNORECASE
-                    )  # remove frm_ from the string (case in-sensitive).
+                    # remove frm_ from the string (case in-sensitive).
+                    s = re.sub(frm_, to_, orig_str, flags=re.IGNORECASE)
                 else:
                     s = orig_str.replace(frm_, to_)
 
             elif to.startswith("**"):  # append suffix
                 s = orig_str + to_
 
             elif to.startswith("*"):  # replace suffix
                 if ignore_case:
-                    end_index = re.search(
-                        frm_, orig_str, flags=re.IGNORECASE
-                    ).start()  # get the starting index of 'frm_'.
+                    # get the starting index of 'frm_'.
+                    index = re.search(frm_, orig_str, flags=re.IGNORECASE).start()
                     s = orig_str[:index] + to_
                 else:
                     s = orig_str.split(frm_)[0] + to_
 
             elif to.endswith("**"):  # append prefix
                 s = to_ + orig_str
 
             elif to.endswith("*"):  # replace prefix
                 if ignore_case:
-                    end_index = re.search(
-                        frm_, orig_str, flags=re.IGNORECASE
-                    ).end()  # get the ending index of 'frm_'.
+                    # get the ending index of 'frm_'.
+                    index = re.search(frm_, orig_str, flags=re.IGNORECASE).end()
                     s = to_ + orig_str[index:]
                 else:
                     s = to_ + frm_ + orig_str.split(frm_)[-1]
 
             elif not to_:  # if 'to_' is an empty string:
                 if fltr.endswith("*") and not fltr.startswith(
                     "*"
                 ):  # strip only beginning chars.
                     if ignore_case:
-                        s = re.sub(
-                            frm_, "", orig_str, 1, flags=re.IGNORECASE
-                        )  # remove the first instance of frm_ from the string (case in-sensitive).
+                        # remove the first instance of frm_ from the string (case in-sensitive).
+                        s = re.sub(frm_, "", orig_str, 1, flags=re.IGNORECASE)
                     else:
-                        s = orig_str.replace(
-                            frm_, "", 1
-                        )  # remove first instance of frm_ from the string.
+                        # remove first instance of frm_ from the string.
+                        s = orig_str.replace(frm_, "", 1)
 
                 elif fltr.startswith("*") and not fltr.endswith(
                     "*"
                 ):  # strip only ending chars.
                     if ignore_case:
-                        s = re.sub(
-                            r"(.*)" + frm_, r"\1", orig_str, flags=re.IGNORECASE
-                        )  # remove the last instance of frm_ from the string (case in-sensitive).
+                        # remove the last instance of frm_ from the string (case in-sensitive).
+                        s = re.sub(r"(.*)" + frm_, r"\1", orig_str, flags=re.IGNORECASE)
                     else:
-                        s = "".join(
-                            orig_str.rsplit(frm_, 1)
-                        )  # remove last instance of frm_ from the string.
+                        # remove last instance of frm_ from the string.
+                        s = "".join(orig_str.rsplit(frm_, 1))
 
                 else:
                     if ignore_case:
-                        s = re.sub(
-                            frm_, "", orig_str, flags=re.IGNORECASE
-                        )  # remove frm_ from the string (case in-sensitive).
+                        # remove frm_ from the string (case in-sensitive).
+                        s = re.sub(frm_, "", orig_str, flags=re.IGNORECASE)
                     else:
                         s = orig_str.replace(frm_, "")  # remove frm_ from the string.
             else:  # else; replace whole string.
                 s = to_
 
             if return_orig_strings:
                 result.append((orig_str, s))
@@ -536,34 +527,34 @@
         strip="",
         strip_trailing_ints=False,
         strip_trailing_alpha=False,
     ):
         """Re-format the suffix for the given string.
 
         Parameters:
-                string (str): The string to format.
-                suffix (str): Append a new suffix to the given string.
-                strip (str/list): Specific string(s) to strip from the end of the given string.
-                strip_trailing_ints (bool): Strip all trailing integers.
-                strip_trailing_alpha (bool): Strip all upper-case letters preceeded by a non alphanumeric character.
+            string (str): The string to format.
+            suffix (str): Append a new suffix to the given string.
+            strip (str/list): Specific string(s) to strip from the end of the given string.
+            strip_trailing_ints (bool): Strip all trailing integers.
+            strip_trailing_alpha (bool): Strip all upper-case letters preceeded by a non alphanumeric character.
 
         Returns:
-                (str)
+            (str)
         """
         import re
 
         try:
             s = string.split("|")[-1]
-        except Exception as error:
+        except Exception:
             s = string.string().split("|")[-1]
 
         # strip each set of chars in 'strip' from end of string.
         if strip:
             strip = tuple(
-                [i for i in Iter.make_iterable(strip) if not i == ""]
+                [i for i in IterUtils.make_iterable(strip) if not i == ""]
             )  # assure 'strip' is a tuple and does not contain any empty strings.
             while s.endswith(strip):
                 for chars in strip:
                     s = s.rstrip(chars)
 
         while (
             ((s[-1] == "_" or s[-1].isdigit()) and strip_trailing_ints)
@@ -579,18 +570,18 @@
                 "_" in s and (s == "_" or s[-1].isupper())
             ) and strip_trailing_alpha:  # trailing underscore and uppercase alphanumeric char.
                 s = re.sub(re.escape(s[-1:]) + "$", "", s)
 
         return s + suffix
 
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 
 if __name__ == "__main__":
     pass
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 # Notes
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 
 
-# Deprecated ------------------------------------
+# deprecated ---------------------
```

### Comparing `pythontk-0.6.6/pythontk.egg-info/PKG-INFO` & `pythontk-0.6.7/pythontk.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pythontk
-Version: 0.6.6
+Version: 0.6.7
 Summary: *pythontk is a collection of backend utilities for Python.*
 Home-page: https://github.com/m3trik/pythontk
 Author: Ryan Simpson
 Author-email: m3trik@outlook.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `pythontk-0.6.6/pythontk.egg-info/PKG-INFO.bak` & `pythontk-0.6.7/pythontk.egg-info/PKG-INFO.bak`

 * *Files identical despite different names*


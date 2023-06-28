# Comparing `tmp/mayatk-0.6.6.tar.gz` & `tmp/mayatk-0.6.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mayatk-0.6.6.tar", last modified: Sun Jun 25 23:03:14 2023, max compression
+gzip compressed data, was "mayatk-0.6.7.tar", last modified: Wed Jun 28 02:20:01 2023, max compression
```

## Comparing `mayatk-0.6.6.tar` & `mayatk-0.6.7.tar`

### file list

```diff
@@ -1,50 +1,50 @@
-drwxrwxrwx   0        0        0        0 2023-06-25 23:03:14.063437 mayatk-0.6.6/
--rw-rw-rw-   0        0        0     1093 2023-03-28 23:39:14.000000 mayatk-0.6.6/LICENSE
--rw-rw-rw-   0        0        0       27 2023-03-28 23:39:14.000000 mayatk-0.6.6/MANIFEST.in
--rw-rw-rw-   0        0        0     1246 2023-06-25 23:03:14.063437 mayatk-0.6.6/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-25 23:03:14.044438 mayatk-0.6.6/mayatk/
--rw-rw-rw-   0        0        0     5784 2023-06-25 23:03:11.000000 mayatk-0.6.6/mayatk/__init__.py
--rw-rw-rw-   0        0        0     8075 2023-06-05 16:23:13.000000 mayatk-0.6.6/mayatk/cam_utils.py
--rw-rw-rw-   0        0        0     8083 2023-05-30 18:39:58.000000 mayatk-0.6.6/mayatk/cam_utils.py.bak
--rw-rw-rw-   0        0        0    65402 2023-06-14 17:05:48.000000 mayatk-0.6.6/mayatk/cmpt_utils.py
--rw-rw-rw-   0        0        0    48216 2023-05-30 18:39:58.000000 mayatk-0.6.6/mayatk/cmpt_utils.py.bak
-drwxrwxrwx   0        0        0        0 2023-06-25 23:03:14.053437 mayatk-0.6.6/mayatk/display_utils/
--rw-rw-rw-   0        0        0      397 2023-06-25 00:47:10.000000 mayatk-0.6.6/mayatk/display_utils/__init__.py
--rw-rw-rw-   0        0        0     7433 2023-06-13 02:25:19.000000 mayatk-0.6.6/mayatk/display_utils/exploded_view.py
--rw-rw-rw-   0        0        0    30588 2023-06-23 22:00:50.000000 mayatk-0.6.6/mayatk/edit_utils.py
--rw-rw-rw-   0        0        0    22313 2023-05-28 17:20:26.000000 mayatk-0.6.6/mayatk/macro_utils.py
--rw-rw-rw-   0        0        0    13411 2023-06-05 16:23:13.000000 mayatk-0.6.6/mayatk/mash_utils.py
--rw-rw-rw-   0        0        0    13413 2023-05-29 19:59:22.000000 mayatk-0.6.6/mayatk/mash_utils.py.bak
-drwxrwxrwx   0        0        0        0 2023-06-25 23:03:14.055439 mayatk-0.6.6/mayatk/mat_utils/
--rw-rw-rw-   0        0        0      337 2023-06-25 00:47:26.000000 mayatk-0.6.6/mayatk/mat_utils/__init__.py
--rw-rw-rw-   0        0        0     9122 2023-06-12 14:32:54.000000 mayatk-0.6.6/mayatk/mat_utils/mat_utils.py
--rw-rw-rw-   0        0        0    18613 2023-06-25 01:01:15.000000 mayatk-0.6.6/mayatk/mat_utils/stingray_arnold_shader.py
--rw-rw-rw-   0        0        0    15178 2023-06-23 15:06:20.000000 mayatk-0.6.6/mayatk/misc_utils.py
--rw-rw-rw-   0        0        0    15374 2023-06-17 12:29:07.000000 mayatk-0.6.6/mayatk/misc_utils.py.bak
--rw-rw-rw-   0        0        0    29580 2023-06-22 00:27:45.000000 mayatk-0.6.6/mayatk/node_utils.py
--rw-rw-rw-   0        0        0    13413 2023-06-16 01:20:55.000000 mayatk-0.6.6/mayatk/project_utils.py
--rw-rw-rw-   0        0        0    11613 2023-05-20 16:09:43.000000 mayatk-0.6.6/mayatk/project_utils.py.bak
--rw-rw-rw-   0        0        0    20346 2023-06-06 18:19:16.000000 mayatk-0.6.6/mayatk/rig_utils.py
--rw-rw-rw-   0        0        0    20342 2023-05-30 18:34:56.000000 mayatk-0.6.6/mayatk/rig_utils.py.bak
--rw-rw-rw-   0        0        0     2771 2023-05-20 16:34:41.000000 mayatk-0.6.6/mayatk/script_utils.py
--rw-rw-rw-   0        0        0    32313 2023-06-06 18:19:16.000000 mayatk-0.6.6/mayatk/xform_utils.py
--rw-rw-rw-   0        0        0    32309 2023-06-05 16:23:13.000000 mayatk-0.6.6/mayatk/xform_utils.py.bak
-drwxrwxrwx   0        0        0        0 2023-06-25 23:03:14.051439 mayatk-0.6.6/mayatk.egg-info/
--rw-rw-rw-   0        0        0     1246 2023-06-25 23:03:13.000000 mayatk-0.6.6/mayatk.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1157 2023-05-20 15:52:44.000000 mayatk-0.6.6/mayatk.egg-info/PKG-INFO.bak
--rw-rw-rw-   0        0        0     1016 2023-06-25 23:03:13.000000 mayatk-0.6.6/mayatk.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0      518 2023-03-29 13:02:37.000000 mayatk-0.6.6/mayatk.egg-info/SOURCES.txt.bak
--rw-rw-rw-   0        0        0        1 2023-06-25 23:03:13.000000 mayatk-0.6.6/mayatk.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       12 2023-06-25 23:03:13.000000 mayatk-0.6.6/mayatk.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-25 23:03:14.063437 mayatk-0.6.6/setup.cfg
--rw-rw-rw-   0        0        0     2238 2023-06-06 18:19:16.000000 mayatk-0.6.6/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-25 23:03:14.062438 mayatk-0.6.6/test/
--rw-rw-rw-   0        0        0     1289 2023-05-20 14:01:35.000000 mayatk-0.6.6/test/__init__.py
--rw-rw-rw-   0        0        0    26011 2023-06-14 17:56:40.000000 mayatk-0.6.6/test/cmpt_utils_test.py
--rw-rw-rw-   0        0        0     7670 2023-05-20 15:49:30.000000 mayatk-0.6.6/test/edit_utils_test.py
--rw-rw-rw-   0        0        0     4485 2023-06-11 12:52:05.000000 mayatk-0.6.6/test/mat_utils_test.py
--rw-rw-rw-   0        0        0     7863 2023-06-17 12:29:32.000000 mayatk-0.6.6/test/misc_utils_test.py
--rw-rw-rw-   0        0        0     8241 2023-06-14 16:56:33.000000 mayatk-0.6.6/test/node_utils_test.py
--rw-rw-rw-   0        0        0     5080 2023-05-20 16:17:57.000000 mayatk-0.6.6/test/rig_utils_test.py
--rw-rw-rw-   0        0        0     3406 2023-06-14 17:14:08.000000 mayatk-0.6.6/test/run_tests.py
--rw-rw-rw-   0        0        0     7292 2023-05-20 17:08:16.000000 mayatk-0.6.6/test/xform_utils_test.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:20:01.272482 mayatk-0.6.7/
+-rw-rw-rw-   0        0        0     1093 2023-03-28 23:39:14.000000 mayatk-0.6.7/LICENSE
+-rw-rw-rw-   0        0        0       27 2023-03-28 23:39:14.000000 mayatk-0.6.7/MANIFEST.in
+-rw-rw-rw-   0        0        0     1246 2023-06-28 02:20:01.272482 mayatk-0.6.7/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 02:20:01.225393 mayatk-0.6.7/mayatk/
+-rw-rw-rw-   0        0        0     4335 2023-06-28 02:19:57.000000 mayatk-0.6.7/mayatk/__init__.py
+-rw-rw-rw-   0        0        0     8065 2023-06-27 21:45:31.000000 mayatk-0.6.7/mayatk/cam_utils.py
+-rw-rw-rw-   0        0        0     8083 2023-05-30 18:39:58.000000 mayatk-0.6.7/mayatk/cam_utils.py.bak
+-rw-rw-rw-   0        0        0    64432 2023-06-28 00:14:46.000000 mayatk-0.6.7/mayatk/cmpt_utils.py
+-rw-rw-rw-   0        0        0    48216 2023-05-30 18:39:58.000000 mayatk-0.6.7/mayatk/cmpt_utils.py.bak
+drwxrwxrwx   0        0        0        0 2023-06-28 02:20:01.259189 mayatk-0.6.7/mayatk/display_utils/
+-rw-rw-rw-   0        0        0      397 2023-06-25 00:47:10.000000 mayatk-0.6.7/mayatk/display_utils/__init__.py
+-rw-rw-rw-   0        0        0     7746 2023-06-27 21:52:32.000000 mayatk-0.6.7/mayatk/display_utils/exploded_view.py
+-rw-rw-rw-   0        0        0    30701 2023-06-28 01:35:20.000000 mayatk-0.6.7/mayatk/edit_utils.py
+-rw-rw-rw-   0        0        0    22313 2023-05-28 17:20:26.000000 mayatk-0.6.7/mayatk/macro_utils.py
+-rw-rw-rw-   0        0        0    13411 2023-06-05 16:23:13.000000 mayatk-0.6.7/mayatk/mash_utils.py
+-rw-rw-rw-   0        0        0    13413 2023-05-29 19:59:22.000000 mayatk-0.6.7/mayatk/mash_utils.py.bak
+drwxrwxrwx   0        0        0        0 2023-06-28 02:20:01.262838 mayatk-0.6.7/mayatk/mat_utils/
+-rw-rw-rw-   0        0        0      337 2023-06-25 00:47:26.000000 mayatk-0.6.7/mayatk/mat_utils/__init__.py
+-rw-rw-rw-   0        0        0     8911 2023-06-28 02:10:10.000000 mayatk-0.6.7/mayatk/mat_utils/mat_utils.py
+-rw-rw-rw-   0        0        0    17681 2023-06-27 21:41:18.000000 mayatk-0.6.7/mayatk/mat_utils/stingray_arnold_shader.py
+-rw-rw-rw-   0        0        0    15374 2023-06-17 12:29:07.000000 mayatk-0.6.7/mayatk/misc_utils.py.bak
+-rw-rw-rw-   0        0        0    27018 2023-06-27 22:30:12.000000 mayatk-0.6.7/mayatk/node_utils.py
+-rw-rw-rw-   0        0        0    13327 2023-06-28 00:05:16.000000 mayatk-0.6.7/mayatk/project_utils.py
+-rw-rw-rw-   0        0        0    11613 2023-05-20 16:09:43.000000 mayatk-0.6.7/mayatk/project_utils.py.bak
+-rw-rw-rw-   0        0        0    18251 2023-06-27 23:39:34.000000 mayatk-0.6.7/mayatk/rig_utils.py
+-rw-rw-rw-   0        0        0    20342 2023-05-30 18:34:56.000000 mayatk-0.6.7/mayatk/rig_utils.py.bak
+-rw-rw-rw-   0        0        0     2771 2023-05-20 16:34:41.000000 mayatk-0.6.7/mayatk/script_utils.py
+-rw-rw-rw-   0        0        0    15184 2023-06-27 22:23:17.000000 mayatk-0.6.7/mayatk/utils.py
+-rw-rw-rw-   0        0        0    31389 2023-06-27 23:49:44.000000 mayatk-0.6.7/mayatk/xform_utils.py
+-rw-rw-rw-   0        0        0    32309 2023-06-05 16:23:13.000000 mayatk-0.6.7/mayatk/xform_utils.py.bak
+drwxrwxrwx   0        0        0        0 2023-06-28 02:20:01.256183 mayatk-0.6.7/mayatk.egg-info/
+-rw-rw-rw-   0        0        0     1246 2023-06-28 02:20:00.000000 mayatk-0.6.7/mayatk.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1157 2023-05-20 15:52:44.000000 mayatk-0.6.7/mayatk.egg-info/PKG-INFO.bak
+-rw-rw-rw-   0        0        0     1006 2023-06-28 02:20:01.000000 mayatk-0.6.7/mayatk.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0      518 2023-03-29 13:02:37.000000 mayatk-0.6.7/mayatk.egg-info/SOURCES.txt.bak
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:20:00.000000 mayatk-0.6.7/mayatk.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 02:20:00.000000 mayatk-0.6.7/mayatk.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:20:01.273483 mayatk-0.6.7/setup.cfg
+-rw-rw-rw-   0        0        0     1442 2023-06-28 02:16:01.000000 mayatk-0.6.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:20:01.271482 mayatk-0.6.7/test/
+-rw-rw-rw-   0        0        0     1289 2023-05-20 14:01:35.000000 mayatk-0.6.7/test/__init__.py
+-rw-rw-rw-   0        0        0    26026 2023-06-28 00:01:13.000000 mayatk-0.6.7/test/cmpt_utils_test.py
+-rw-rw-rw-   0        0        0     7676 2023-06-28 00:35:52.000000 mayatk-0.6.7/test/edit_utils_test.py
+-rw-rw-rw-   0        0        0     4505 2023-06-28 02:10:41.000000 mayatk-0.6.7/test/mat_utils_test.py
+-rw-rw-rw-   0        0        0     7396 2023-06-28 00:17:04.000000 mayatk-0.6.7/test/node_utils_test.py
+-rw-rw-rw-   0        0        0     5086 2023-06-28 01:40:55.000000 mayatk-0.6.7/test/rig_utils_test.py
+-rw-rw-rw-   0        0        0     2068 2023-06-28 01:24:21.000000 mayatk-0.6.7/test/run_tests.py
+-rw-rw-rw-   0        0        0     7022 2023-06-28 00:34:32.000000 mayatk-0.6.7/test/utils_test.py
+-rw-rw-rw-   0        0        0     7298 2023-06-28 01:39:40.000000 mayatk-0.6.7/test/xform_utils_test.py
```

### Comparing `mayatk-0.6.6/LICENSE` & `mayatk-0.6.7/LICENSE`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/PKG-INFO` & `mayatk-0.6.7/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mayatk
-Version: 0.6.6
+Version: 0.6.7
 Summary: *mayattk is a collection of backend utilities for Autodesk Maya.*
 Home-page: https://github.com/m3trik/mayatk
 Author: Ryan Simpson
 Author-email: m3trik@outlook.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `mayatk-0.6.6/mayatk/cam_utils.py` & `mayatk-0.6.7/mayatk/cam_utils.py.bak`

 * *Files 6% similar despite different names*

```diff
@@ -69,15 +69,15 @@
         return group
 
     @classmethod
     def toggle_safe_frames(cls):
         """Toggle display of the film gate for the current camera."""
         camera = cls.get_current_cam()
 
-        state = pm.camera(camera, q=True, displayResolution=1)
+        state = pm.camera(camera, query=1, displayResolution=1)
         if state:
             pm.camera(
                 camera,
                 edit=1,
                 displayFilmGate=False,
                 displayResolution=False,
                 overscan=1.0,
@@ -164,31 +164,31 @@
 #           component (str/obj): Object component.
 #           alignToNormal (bool): Constain to normal vector.
 
 #       Returns:
 #           (tuple) coordinate as xyz float values.
 #       '''
 #       if ".vtx" in str(component):
-#           x = pm.polyNormalPerVertex(component, q=True, x=1)
-#           y = pm.polyNormalPerVertex(component, q=True, y=1)
-#           z = pm.polyNormalPerVertex(component, q=True, z=1)
+#           x = pm.polyNormalPerVertex(component, query=1, x=1)
+#           y = pm.polyNormalPerVertex(component, query=1, y=1)
+#           z = pm.polyNormalPerVertex(component, query=1, z=1)
 #           xyz = [sum(x) / float(len(x)), sum(y) / float(len(y)), sum(z) / float(len(z))] #get average
 
 #       elif ".e" in str(component):
 #           componentName = str(component).split(".")[0]
 #           vertices = pm.polyInfo (component, edgeToVertex=1)[0]
 #           vertices = vertices.split()
 #           vertices = [componentName+".vtx["+vertices[2]+"]",componentName+".vtx["+vertices[3]+"]"]
 #           x=[];y=[];z=[]
 #           for vertex in vertices:
-#               x_ = pm.polyNormalPerVertex (vertex, q=True, x=1)
+#               x_ = pm.polyNormalPerVertex (vertex, query=1, x=1)
 #               x.append(sum(x_) / float(len(x_)))
-#               y_ = pm.polyNormalPerVertex (vertex, q=True, y=1)
+#               y_ = pm.polyNormalPerVertex (vertex, query=1, y=1)
 #               x.append(sum(y_) / float(len(y_)))
-#               z_ = pm.polyNormalPerVertex (vertex, q=True, z=1)
+#               z_ = pm.polyNormalPerVertex (vertex, query=1, z=1)
 #               x.append(sum(z_) / float(len(z_)))
 #           xyz = [sum(x) / float(len(x)), sum(y) / float(len(y)), sum(z) / float(len(z))] #get average
 
 #       else:# elif ".f" in str(component):
 #           xyz = pm.polyInfo (component, faceNormals=1)
 #           xyz = xyz[0].split()
 #           xyz = [float(xyz[2]), float(xyz[3]), float(xyz[4])]
@@ -196,13 +196,13 @@
 #       if alignToNormal: #normal constraint
 #           normal = pm.mel.eval("unit <<"+str(xyz[0])+", "+str(xyz[1])+", "+str(xyz[2])+">>;") #normalize value using MEL
 #           # normal = [round(i-min(xyz)/(max(xyz)-min(xyz)),6) for i in xyz] #normalize and round value using python
 
 #           constraint = pm.normalConstraint(component, object_,aimVector=normal,upVector=[0,1,0],worldUpVector=[0,1,0],worldUpType="vector") # "scene","object","objectrotation","vector","none"
 #           pm.delete(constraint) #orient object_ then remove constraint.
 
-#       vertexPoint = pm.xform (component, q=True, translation=1) #average vertex points on destination to get component center.
+#       vertexPoint = pm.xform (component, query=1, translation=1) #average vertex points on destination to get component center.
 #       x = vertexPoint[0::3]
 #       y = vertexPoint[1::3]
 #       z = vertexPoint[2::3]
 
 #       return tuple(round(sum(x) / float(len(x)),4), round(sum(y) / float(len(y)),4), round(sum(z) / float(len(z)),4))
```

### Comparing `mayatk-0.6.6/mayatk/cam_utils.py.bak` & `mayatk-0.6.7/mayatk/cam_utils.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,22 +2,22 @@
 # coding=utf-8
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
 
 # from this package:
-from mayatk import misc_utils
+from mayatk import utils
 
 
 class Cam(object):
     """ """
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def group_cameras(
         name="cameras", non_default=True, root_only=False, hide_group=False
     ):
         """Group cameras in the scene based on the provided parameters.
 
         Parameters:
                 name (str): The name of the group that will contain the cameras. Default is 'cameras'.
@@ -69,15 +69,15 @@
         return group
 
     @classmethod
     def toggle_safe_frames(cls):
         """Toggle display of the film gate for the current camera."""
         camera = cls.get_current_cam()
 
-        state = pm.camera(camera, query=1, displayResolution=1)
+        state = pm.camera(camera, q=True, displayResolution=1)
         if state:
             pm.camera(
                 camera,
                 edit=1,
                 displayFilmGate=False,
                 displayResolution=False,
                 overscan=1.0,
@@ -100,26 +100,26 @@
         view = M3dView.active3dView()
         cam = MDagPath()
         view.getCamera(cam)
         camPath = cam.fullPathName()
         return camPath
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def create_camera_from_view(name="camera#"):
         """Create a new camera based on the current view."""
         # Find the current modelPanel (viewport)
         current_panel = None
-        for panel in misc_utils.get_panel(all=True):
-            if misc_utils.get_panel(typeOf=panel) == "modelPanel":
+        for panel in utils.Utils.get_panel(all=True):
+            if utils.Utils.get_panel(typeOf=panel) == "modelPanel":
                 current_panel = panel
                 break
 
         if current_panel:
-            if misc_utils.get_panel(typeOf=current_panel) == "modelPanel":
+            if utils.Utils.get_panel(typeOf=current_panel) == "modelPanel":
                 camera = pm.modelPanel(current_panel, q=1, cam=1)
                 new_camera = pm.duplicate(camera)[0]
                 pm.showHidden(new_camera)
                 new_camera = pm.rename(new_camera, name)
                 print(f"# Result: {new_camera} #")
                 return new_camera
         else:
@@ -164,31 +164,31 @@
 #           component (str/obj): Object component.
 #           alignToNormal (bool): Constain to normal vector.
 
 #       Returns:
 #           (tuple) coordinate as xyz float values.
 #       '''
 #       if ".vtx" in str(component):
-#           x = pm.polyNormalPerVertex(component, query=1, x=1)
-#           y = pm.polyNormalPerVertex(component, query=1, y=1)
-#           z = pm.polyNormalPerVertex(component, query=1, z=1)
+#           x = pm.polyNormalPerVertex(component, q=True, x=1)
+#           y = pm.polyNormalPerVertex(component, q=True, y=1)
+#           z = pm.polyNormalPerVertex(component, q=True, z=1)
 #           xyz = [sum(x) / float(len(x)), sum(y) / float(len(y)), sum(z) / float(len(z))] #get average
 
 #       elif ".e" in str(component):
 #           componentName = str(component).split(".")[0]
 #           vertices = pm.polyInfo (component, edgeToVertex=1)[0]
 #           vertices = vertices.split()
 #           vertices = [componentName+".vtx["+vertices[2]+"]",componentName+".vtx["+vertices[3]+"]"]
 #           x=[];y=[];z=[]
 #           for vertex in vertices:
-#               x_ = pm.polyNormalPerVertex (vertex, query=1, x=1)
+#               x_ = pm.polyNormalPerVertex (vertex, q=True, x=1)
 #               x.append(sum(x_) / float(len(x_)))
-#               y_ = pm.polyNormalPerVertex (vertex, query=1, y=1)
+#               y_ = pm.polyNormalPerVertex (vertex, q=True, y=1)
 #               x.append(sum(y_) / float(len(y_)))
-#               z_ = pm.polyNormalPerVertex (vertex, query=1, z=1)
+#               z_ = pm.polyNormalPerVertex (vertex, q=True, z=1)
 #               x.append(sum(z_) / float(len(z_)))
 #           xyz = [sum(x) / float(len(x)), sum(y) / float(len(y)), sum(z) / float(len(z))] #get average
 
 #       else:# elif ".f" in str(component):
 #           xyz = pm.polyInfo (component, faceNormals=1)
 #           xyz = xyz[0].split()
 #           xyz = [float(xyz[2]), float(xyz[3]), float(xyz[4])]
@@ -196,13 +196,13 @@
 #       if alignToNormal: #normal constraint
 #           normal = pm.mel.eval("unit <<"+str(xyz[0])+", "+str(xyz[1])+", "+str(xyz[2])+">>;") #normalize value using MEL
 #           # normal = [round(i-min(xyz)/(max(xyz)-min(xyz)),6) for i in xyz] #normalize and round value using python
 
 #           constraint = pm.normalConstraint(component, object_,aimVector=normal,upVector=[0,1,0],worldUpVector=[0,1,0],worldUpType="vector") # "scene","object","objectrotation","vector","none"
 #           pm.delete(constraint) #orient object_ then remove constraint.
 
-#       vertexPoint = pm.xform (component, query=1, translation=1) #average vertex points on destination to get component center.
+#       vertexPoint = pm.xform (component, q=True, translation=1) #average vertex points on destination to get component center.
 #       x = vertexPoint[0::3]
 #       y = vertexPoint[1::3]
 #       z = vertexPoint[2::3]
 
 #       return tuple(round(sum(x) / float(len(x)),4), round(sum(y) / float(len(y)),4), round(sum(z) / float(len(z)),4))
```

### Comparing `mayatk-0.6.6/mayatk/cmpt_utils.py` & `mayatk-0.6.7/mayatk/cmpt_utils.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 # !/usr/bin/python
 # coding=utf-8
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-
-from pythontk import Iter, Math
+import pythontk as ptk
 
 # from this package:
-from mayatk import misc_utils, node_utils
+from mayatk import utils, node_utils
 
 
 class GetComponentsMixin:
     """ """
 
     componentTypes = [  # abv, singular, plural, full, int, hex
         (
@@ -226,28 +225,28 @@
     ]
 
     @classmethod
     def get_component_type(cls, component, returned_type="abv"):
         """Get the type of a given component.
 
         Parameters:
-                obj (str/obj/list): A single maya component.
-                        If multiple components are given, only the first will be sampled.
-                returned_type (str): Specify the desired return value type. (default: 'str')
-                        (valid: 'full' - object type as a string.
-                                        'int' - maya mask value as an integer.
-                                        'hex' - hex value. ie. 0x0001
-                                        'abv' - abreviated object type as a string. ie. 'vtx'
+            obj (str/obj/list): A single maya component.
+                    If multiple components are given, only the first will be sampled.
+            returned_type (str): Specify the desired return value type. (default: 'str')
+                    (valid: 'full' - object type as a string.
+                                    'int' - maya mask value as an integer.
+                                    'hex' - hex value. ie. 0x0001
+                                    'abv' - abreviated object type as a string. ie. 'vtx'
         Returns:
-                (str)(int) dependant on 'returned_type' arg.
+            (str)(int) dependant on 'returned_type' arg.
 
         Example:
-        get_component_type('cyl.e[:]') #returns: 'e'
-        get_component_type('cyl.vtx[:]', 'abv') #returns: 'vtx'
-        get_component_type('cyl.e[:]', 'int') #returns: 32
+            get_component_type('cyl.e[:]') #returns: 'e'
+            get_component_type('cyl.vtx[:]', 'abv') #returns: 'vtx'
+            get_component_type('cyl.e[:]', 'int') #returns: 32
         """
         for a, s, p, f, i, h in cls.componentTypes:
             try:
                 if pm.filterExpand(component, sm=i):
                     if returned_type == "abv":
                         return a
                     elif returned_type == "full":
@@ -256,40 +255,38 @@
                         return i
                     elif returned_type == "hex":
                         return h
                     elif returned_type == "plural":
                         return p
                     else:
                         return s
-            except Exception as error:
+            except Exception as e:
                 print(
-                    'File "{}" in get_component_type\n# Error: Not a valid component. #\n {}{}'.format(
-                        __file__, error, "(empty string)" if component == "" else ""
-                    )
+                    f'File "{__file__}" in get_component_type\n# Error: Not a valid component. #\n{e}{"(empty string)" if component == "" else ""}',
                 )
                 break
         return None
 
     @classmethod
     def convert_alias(cls, component_type, returned_type="abv"):
         """Return an alternate component alias for the given alias.
         ie. a hex value of 0x0001 for 'vertex'
         If nothing is found, a value of 'None' will be returned.
 
         Parameters:
-                component_type () = A component type. ex. 'vertex', 'vtx', 31, or 0x0001
-                returned_type (str): The desired returned alias.  (default: 'abv')
-                        (valid: 'abv', 'singular', 'plural', 'str', 'int', 'hex')
+            component_type () = A component type. ex. 'vertex', 'vtx', 31, or 0x0001
+            returned_type (str): The desired returned alias.  (default: 'abv')
+                    (valid: 'abv', 'singular', 'plural', 'str', 'int', 'hex')
 
         Returns:
-                (str)(int)(hex)(None) dependant on 'returned_type' argument.
+            (str)(int)(hex)(None) dependant on 'returned_type' argument.
 
         Example:
-        convert_alias('vertex', 'hex') #returns: 0x0001
-        convert_alias(0x0001, 'str') #returns: 'Polygon Vertex'
+            convert_alias('vertex', 'hex') #returns: 0x0001
+            convert_alias(0x0001, 'str') #returns: 'Polygon Vertex'
         """
         rtypes = ("abv", "singular", "plural", "full", "int", "hex")
 
         for t in cls.componentTypes:
             if component_type in t:
                 index = rtypes.index(returned_type)
                 return t[index]
@@ -298,136 +295,137 @@
     @classmethod
     def convert_component_type(
         cls, components, component_type, returned_type="str", flatten=False
     ):
         """Convert component(s) to it's sub-components of the given type.
 
         Parameters:
-                components (str/obj/list): The components(s) to convert.
-                component_type (str): The desired returned component type.
-                        valid: 'vtx' (or 'vertex', 'vertices', 'Polygon Vertex', 31, 0x0001),
-                                and the same for each: 'edge', 'uv', 'face'.
-                returned_type (str): The desired returned object type.
-                        (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            components (str/obj/list): The components(s) to convert.
+            component_type (str): The desired returned component type.
+                    valid: 'vtx' (or 'vertex', 'vertices', 'Polygon Vertex', 31, 0x0001),
+                            and the same for each: 'edge', 'uv', 'face'.
+            returned_type (str): The desired returned object type.
+                    (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list)(dict)
+            (list)(dict)
 
         Example:
-        convert_component_type('obj.vtx[:2]', 'vertex') #returns: ['obj.vtx[0:2]']
-        convert_component_type('obj.vtx[:2]', 'face') #returns: ['obj.f[0:2]', 'obj.f[11:14]', 'obj.f[23]']
-        convert_component_type('obj.vtx[:2]', 'edge') #returns: ['obj.e[0:2]', 'obj.e[11]', 'obj.e[24:26]', 'obj.e[36:38]']
-        convert_component_type('obj.vtx[:2]', 'uv') #returns: ['obj.map[0:2]', 'obj.map[12:14]', 'obj.map[24]']
+            convert_component_type('obj.vtx[:2]', 'vertex') #returns: ['obj.vtx[0:2]']
+            convert_component_type('obj.vtx[:2]', 'face') #returns: ['obj.f[0:2]', 'obj.f[11:14]', 'obj.f[23]']
+            convert_component_type('obj.vtx[:2]', 'edge') #returns: ['obj.e[0:2]', 'obj.e[11]', 'obj.e[24:26]', 'obj.e[36:38]']
+            convert_component_type('obj.vtx[:2]', 'uv') #returns: ['obj.map[0:2]', 'obj.map[12:14]', 'obj.map[24]']
         """
         d = {
             "vtx": "toVertex",
             "e": "toEdge",
             "uv": "toUV",
             "f": "toFace",
             "uv": "toUV",
             "shell": "toShell",
             "vertexFace": "toVertexFace",
         }
         typ = cls.convert_alias(
             component_type
         )  # get the correct component_type variable from possible args.
 
-        if not typ in d:
+        if typ not in d:
             return components
         components = pm.polyListComponentConversion(
             components, **{d[typ.lower()]: True}
         )
-        return misc_utils.Misc.convert_array_type(
+        return utils.Utils.convert_array_type(
             components, returned_type=returned_type, flatten=flatten
         )
 
     @classmethod
     def convert_int_to_component(
         cls, obj, integers, component_type, returned_type="str", flatten=False
     ):
         """Convert the given integers to components of the given object.
 
         Parameters:
-                obj (str/obj/list): The object to convert to vertices of.
-                integers (list): The integer(s) to convert.
-                component_type (str): The desired returned component type.
-                        valid: 'vtx' (or 'vertex', 'vertices', 'Polygon Vertex', 31, 0x0001),
-                                and the same for each: 'edge', 'uv', 'face'.
-                returned_type (str): The desired returned object type.
-                        (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            obj (str/obj/list): The object to convert to vertices of.
+            integers (list): The integer(s) to convert.
+            component_type (str): The desired returned component type.
+                    valid: 'vtx' (or 'vertex', 'vertices', 'Polygon Vertex', 31, 0x0001),
+                            and the same for each: 'edge', 'uv', 'face'.
+            returned_type (str): The desired returned object type.
+                    (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list)
+            (list)
 
-        Example: convert_int_to_component('cyl', range(4), 'f') #returns: ['cylShape.f[0:3]']
+        Example:
+            convert_int_to_component('cyl', range(4), 'f') #returns: ['cylShape.f[0:3]']
         """
         obj = pm.ls(obj, objectsOnly=True)[0]
         objName = obj.name()
 
+        def n(c):
+            return "{}:{}".format(c[0], c[-1]) if len(c) > 1 else str(c[0])
+
         if not flatten:
-            n = lambda c: "{}:{}".format(c[0], c[-1]) if len(c) > 1 else str(c[0])
             result = [
                 "{}.{}[{}]".format(objName, component_type, n(c))
-                for c in Iter.split_list(integers, "range")
+                for c in ptk.split_list(integers, "range")
             ]
         else:
             result = ["{}.{}[{}]".format(objName, component_type, c) for c in integers]
 
-        return misc_utils.Misc.convert_array_type(
+        return utils.Utils.convert_array_type(
             result, returned_type=returned_type, flatten=flatten
         )
 
     @classmethod
     def filter_components(cls, components, inc=[], exc=[], flatten=False):
         """Filter the given components.
 
         Parameters:
-                components (str/obj/list): The components(s) to filter.
-                inc (str)(int)(obj/list): The component(s) to include.
-                exc (str)(int)(obj/list): The component(s) to exclude.
-                                        (exlude take precidence over include)
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            components (str/obj/list): The components(s) to filter.
+            inc (str)(int)(obj/list): The component(s) to include.
+            exc (str)(int)(obj/list): The component(s) to exclude.
+                                    (exlude take precidence over include)
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list)
+            (list)
 
         Example:
-        filter_components('cyl.vtx[:]', 'cyl.vtx[:2]', 'cyl.vtx[1:23]') #returns: ['cyl.vtx[0]']
-        filter_components('cyl.f[:]', range(2), range(1, 23)) #returns: ['cyl.f[0]']
+            filter_components('cyl.vtx[:]', 'cyl.vtx[:2]', 'cyl.vtx[1:23]') #returns: ['cyl.vtx[0]']
+            filter_components('cyl.f[:]', range(2), range(1, 23)) #returns: ['cyl.f[0]']
         """
         typ = cls.get_component_type(components)
-        etyp = misc_utils.Misc.get_array_type(components)
-        etyp_inc = misc_utils.Misc.get_array_type(inc)
-        etyp_exc = misc_utils.Misc.get_array_type(exc)
+        etyp = utils.Utils.get_array_type(components)
+        etyp_inc = utils.Utils.get_array_type(inc)
+        etyp_exc = utils.Utils.get_array_type(exc)
 
         if etyp_inc == "int" or etyp_exc == "int":
             try:
                 obj = pm.ls(components, objectsOnly=True)[0]
-            except IndexError as error:
+            except IndexError as e:
                 print(
-                    'File "{}" in filter_components\n# Error: Operation requires at least one component. #\n {}'.format(
-                        __file__, error
-                    )
+                    f'File "{__file__}" in filter_components\n# Error: Operation requires at least one component. #\n{e}',
                 )
                 return []
 
         if etyp_inc == "int":
             inc = cls.convert_int_to_component(obj, inc, typ)
         inc = pm.ls(inc, flatten=True)
 
         if etyp_exc == "int":
             exc = cls.convert_int_to_component(obj, exc, typ)
         exc = pm.ls(exc, flatten=True)
 
         components = pm.ls(components, flatten=True)
 
-        filtered = Iter.filter_list(components, inc=inc, exc=exc)
-        result = misc_utils.Misc.convert_array_type(
+        filtered = ptk.filter_list(components, inc=inc, exc=exc)
+        result = utils.Utils.convert_array_type(
             filtered, returned_type=etyp, flatten=flatten
         )
         return result
 
     @classmethod
     def get_components(
         cls,
@@ -439,64 +437,64 @@
         randomize=0,
         flatten=False,
     ):
         """Get the components of the given type from the given object(s).
         If no objects are given the current selection will be used.
 
         Parameters:
-                objects (str/obj/list): The object(s) to get the components of. (Polygon, Polygon components)(default: current selection)
-                component_type (str)(int): The component type to return. (valid: any type allowed in the 'convert_alias' method)
-                returned_type (str): The desired returned object type.
-                        (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
-                inc (str/obj/list): The component(s) to include.
-                exc (str/obj/list): The component(s) to exclude. (exlude take precidence over include)
-                randomize (float) = If a 0.1-1 value is given, random components will be returned with a quantity determined by the given ratio.
-                                                        A value of 0.5 will return a 50% of the components of an object in random order.
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            objects (str/obj/list): The object(s) to get the components of. (Polygon, Polygon components)(default: current selection)
+            component_type (str)(int): The component type to return. (valid: any type allowed in the 'convert_alias' method)
+            returned_type (str): The desired returned object type.
+                    (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            inc (str/obj/list): The component(s) to include.
+            exc (str/obj/list): The component(s) to exclude. (exlude take precidence over include)
+            randomize (float) = If a 0.1-1 value is given, random components will be returned with a quantity determined by the given ratio.
+                                                    A value of 0.5 will return a 50% of the components of an object in random order.
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list)(dict) Dependant on flags.
+            (list)(dict) Dependant on flags.
 
         Example:
-        get_components(obj, 'vertex', 'str', '', 'obj.vtx[2:23]') #returns: ['objShape.vtx[0]', 'objShape.vtx[1]', 'objShape.vtx[24]', 'objShape.vtx[25]']
-        get_components(obj, 'vertex', 'obj', '', 'obj.vtx[:23]') #returns: [MeshVertex('objShape.vtx[24]'), MeshVertex('objShape.vtx[25]')]
-        get_components(obj, 'f', 'int') #returns: {nt.Mesh('objShape'): [(0, 35)]}
-        get_components(obj, 'edges') #returns: ['objShape.e[0:59]']
-        get_components(obj, 'edges', 'str', 'obj.e[:2]') #returns: ['objShape.e[0]', 'objShape.e[1]', 'objShape.e[2]']
+            get_components(obj, 'vertex', 'str', '', 'obj.vtx[2:23]') #returns: ['objShape.vtx[0]', 'objShape.vtx[1]', 'objShape.vtx[24]', 'objShape.vtx[25]']
+            get_components(obj, 'vertex', 'obj', '', 'obj.vtx[:23]') #returns: [MeshVertex('objShape.vtx[24]'), MeshVertex('objShape.vtx[25]')]
+            get_components(obj, 'f', 'int') #returns: {nt.Mesh('objShape'): [(0, 35)]}
+            get_components(obj, 'edges') #returns: ['objShape.e[0:59]']
+            get_components(obj, 'edges', 'str', 'obj.e[:2]') #returns: ['objShape.e[0]', 'objShape.e[1]', 'objShape.e[2]']
         """
         components = cls.convert_component_type(objects, component_type)
 
         if inc or exc:
             components = cls.filter_components(components, inc=inc, exc=exc)
 
         if randomize:
             components = randomize(pm.ls(components, flatten=1), randomize)
 
-        result = misc_utils.Misc.convert_array_type(
+        result = utils.Utils.convert_array_type(
             components, returned_type=returned_type, flatten=flatten
         )
         return result
 
 
-class Cmpt(GetComponentsMixin):
+class CmptUtils(GetComponentsMixin):
     """ """
 
     @classmethod
     def get_contigious_edges(cls, components):
         """Get a list containing sets of adjacent edges.
 
         Parameters:
-                components (list): Polygon components to be filtered for adjacent edges.
+            components (list): Polygon components to be filtered for adjacent edges.
 
         Returns:
-                (list) adjacent edge sets.
+            (list) adjacent edge sets.
 
         Example:
-        get_contigious_edges(['obj.e[:2]']) #returns: [{'objShape.e[1]', 'objShape.e[0]', 'objShape.e[2]'}]
-        get_contigious_edges(['obj.f[0]']) #returns: [{'objShape.e[24]', 'objShape.e[0]', 'objShape.e[25]', 'objShape.e[12]'}]
+            get_contigious_edges(['obj.e[:2]']) #returns: [{'objShape.e[1]', 'objShape.e[0]', 'objShape.e[2]'}]
+            get_contigious_edges(['obj.f[0]']) #returns: [{'objShape.e[24]', 'objShape.e[0]', 'objShape.e[25]', 'objShape.e[12]'}]
         """
         edges = cls.convert_component_type(components, "edge", flatten=1)
 
         sets = []
         for edge in edges:
             vertices = pm.polyListComponentConversion(edge, fromEdge=1, toVertex=1)
             connEdges = cls.convert_component_type(vertices, "edge", flatten=1)
@@ -528,21 +526,22 @@
         return result
 
     @classmethod
     def get_contigious_islands(cls, faces, face_islands=[]):
         """Get a list containing sets of adjacent polygon faces grouped by islands.
 
         Parameters:
-                faces (str/obj/list): The polygon faces to be filtered for adjacent.
-                face_islands (list/optional): list of sets. ability to add faces from previous calls to the return value.
+            faces (str/obj/list): The polygon faces to be filtered for adjacent.
+            face_islands (list/optional): list of sets. ability to add faces from previous calls to the return value.
 
         Returns:
-                (list): of sets of adjacent faces.
+            (list): of sets of adjacent faces.
 
-        Example: get_contigious_islands('obj.f[21:26]') #returns: [{'objShape.f[22]', 'objShape.f[21]', 'objShape.f[23]'}, {'objShape.f[26]', 'objShape.f[24]', 'objShape.f[25]'}]
+        Example:
+            get_contigious_islands('obj.f[21:26]') #returns: [{'objShape.f[22]', 'objShape.f[21]', 'objShape.f[23]'}, {'objShape.f[26]', 'objShape.f[24]', 'objShape.f[25]'}]
         """
         sets = []
         faces = pm.ls(faces, flatten=1)
         for face in faces:
             edges = pm.polyListComponentConversion(face, fromFace=1, toEdge=1)
             borderFaces = cls.convert_component_type(edges, "face", "obj", flatten=1)
             set_ = set([str(f) for f in borderFaces if f in faces])
@@ -571,22 +570,23 @@
         return face_islands
 
     @staticmethod
     def get_islands(obj, returned_type="str", flatten=False):
         """Get the group of components in each separate island of a combined mesh.
 
         Parameters:
-                obj (str/obj/list): The object to get shells from.
-                returned_type (bool): Return the shell faces as a list of type: 'str' (default), 'int', or 'obj'.
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            obj (str/obj/list): The object to get shells from.
+            returned_type (bool): Return the shell faces as a list of type: 'str' (default), 'int', or 'obj'.
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (generator)
+            (generator)
 
-        Example: get_islands('combined_obj') #returns: [['combined_obj.f[0]', 'combined_obj.f[5]', ..etc, ['combined_obj.f[15]', ..etc]]
+        Example:
+            get_islands('combined_obj') #returns: [['combined_obj.f[0]', 'combined_obj.f[5]', ..etc, ['combined_obj.f[15]', ..etc]]
         """
         # num_shells = pm.polyEvaluate(obj, shell=True)
         num_faces = pm.polyEvaluate(obj, face=True)
 
         unprocessed = set(range(num_faces))
 
         # shells = []
@@ -616,38 +616,36 @@
         component_border=False,
         flatten=False,
     ):
         """Get any object border components from given component(s) or a polygon object.
         A border is defined as a hole or detached edge.
 
         Parameters:
-                x (str/obj/list): Component(s) (or a polygon object) to find any border components for.
-                component_type (str): The desired returned component type. (valid: 'vertex','edge','face', '',
-                        An empty string returns the same type as the first given component, or edges if an object is given)
-                returned_type (str): The desired returned object type.
-                        (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
-                component_border (bool): Get the components that border given components instead of the mesh border.
-                        (valid: 'component', 'object'(default))
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            x (str/obj/list): Component(s) (or a polygon object) to find any border components for.
+            component_type (str): The desired returned component type. (valid: 'vertex','edge','face', '',
+                    An empty string returns the same type as the first given component, or edges if an object is given)
+            returned_type (str): The desired returned object type.
+                    (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            component_border (bool): Get the components that border given components instead of the mesh border.
+                    (valid: 'component', 'object'(default))
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list) components that border an open edge.
+            (list) components that border an open edge.
 
         Example:
         get_border_components('pln', 'vtx') #returns: ['plnShape.vtx[0:4]', 'plnShape.vtx[7:8]', 'plnShape.vtx[11:15]'],
-        get_border_components('pln') #returns: ['plnShape.e[0:2]', 'plnShape.e[4]', 'plnShape.e[6]', 'plnShape.e[8]', 'plnShape.e[13]', 'plnShape.e[15]', 'plnShape.e[20:23]'],
-        get_border_components('pln.e[:]') #returns: ['plnShape.e[0:2]', 'plnShape.e[4]', 'plnShape.e[6]', 'plnShape.e[8]', 'plnShape.e[13]', 'plnShape.e[15]', 'plnShape.e[20:23]'],
-        get_border_components(['pln.e[9]','pln.e[10]', 'pln.e[12]', 'pln.e[16]'], 'f', component_border=True) #returns: ['plnShape.f[1]', 'plnShape.f[3:5]', 'plnShape.f[7]'],
-        get_border_components('pln.f[3:4]', 'vtx', component_border=True) #returns: ['plnShape.vtx[4:6]', 'plnShape.vtx[8:10]'],
+            get_border_components('pln') #returns: ['plnShape.e[0:2]', 'plnShape.e[4]', 'plnShape.e[6]', 'plnShape.e[8]', 'plnShape.e[13]', 'plnShape.e[15]', 'plnShape.e[20:23]'],
+            get_border_components('pln.e[:]') #returns: ['plnShape.e[0:2]', 'plnShape.e[4]', 'plnShape.e[6]', 'plnShape.e[8]', 'plnShape.e[13]', 'plnShape.e[15]', 'plnShape.e[20:23]'],
+            get_border_components(['pln.e[9]','pln.e[10]', 'pln.e[12]', 'pln.e[16]'], 'f', component_border=True) #returns: ['plnShape.f[1]', 'plnShape.f[3:5]', 'plnShape.f[7]'],
+            get_border_components('pln.f[3:4]', 'vtx', component_border=True) #returns: ['plnShape.vtx[4:6]', 'plnShape.vtx[8:10]'],
         """
         if not x:
             print(
-                'File "{}" in get_border_components\n# Error: Operation requires a given object(s) or component(s). #'.format(
-                    __file__
-                )
+                f'File "{__file__}" in get_border_components\n# Error: Operation requires a given object(s) or component(s). #',
             )
             return []
 
         origType = cls.get_component_type(x, "abv")
         if not origType:
             origType, x = "mesh", cls.get_components(x, "edges")
         origVerts = cls.convert_component_type(x, "vtx", flatten=True)
@@ -689,44 +687,44 @@
                 attachedFaces = cls.convert_component_type(edge, "face", flatten=1)
                 if len(attachedFaces) == 1:
                     result.append(edge)
 
         result = cls.convert_component_type(
             result, component_type
         )  # convert back to the original component type and flatten /un-flatten list.
-        result = misc_utils.Misc.convert_array_type(
+        result = utils.Utils.convert_array_type(
             result, returned_type=returned_type, flatten=flatten
         )
         return result
 
     @classmethod
     def get_closest_verts(cls, a, b, tolerance=1000):
         """Find the two closest vertices between the two sets of vertices.
 
         Parameters:
-                a (str/list): The first set of vertices.
-                b (str/list): The second set of vertices.
-                tolerance (float) = Maximum search distance.
+            a (str/list): The first set of vertices.
+            b (str/list): The second set of vertices.
+            tolerance (float) = Maximum search distance.
 
         Returns:
-                (list): closest vertex pairs by order of distance (excluding those not meeting the tolerance). (<vertex from a>, <vertex from b>).
+            (list): closest vertex pairs by order of distance (excluding those not meeting the tolerance). (<vertex from a>, <vertex from b>).
 
         Example:
             get_closest_verts('pln.vtx[:10]', 'pln.vtx[11:]', 6.667) #returns: [('plnShape.vtx[7]', 'plnShape.vtx[11]'), ('plnShape.vtx[8]', 'plnShape.vtx[12]'), ('plnShape.vtx[9]', 'plnShape.vtx[13]'), ('plnShape.vtx[10]', 'plnShape.vtx[11]'), ('plnShape.vtx[10]', 'plnShape.vtx[14]')]
         """
         from operator import itemgetter
 
-        a = misc_utils.Misc.convert_array_type(a, returned_type="str", flatten=True)
-        b = misc_utils.Misc.convert_array_type(b, returned_type="str", flatten=True)
+        a = utils.Utils.convert_array_type(a, returned_type="str", flatten=True)
+        b = utils.Utils.convert_array_type(b, returned_type="str", flatten=True)
         vertPairsAndDistance = {}
         for v1 in a:
             v1Pos = pm.pointPosition(v1, world=1)
             for v2 in b:
                 v2Pos = pm.pointPosition(v2, world=1)
-                distance = Math.get_distance(v1Pos, v2Pos)
+                distance = ptk.get_distance(v1Pos, v2Pos)
                 if distance < tolerance:
                     vertPairsAndDistance[(v1, v2)] = distance
 
         sorted_ = sorted(vertPairsAndDistance.items(), key=itemgetter(1))
         vertPairs = [i[0] for i in sorted_]
 
         return vertPairs
@@ -734,47 +732,43 @@
     @classmethod
     def get_closest_vertex(
         cls, vertices, obj, tolerance=0.0, freeze_transforms=False, returned_type="str"
     ):
         """Find the closest vertex of the given object for each vertex in the list of given vertices.
 
         Parameters:
-                vertices (list): A set of vertices.
-                obj (str/obj/list): The reference object in which to find the closest vertex for each vertex in the list of given vertices.
-                tolerance (float) = Maximum search distance. Default is 0.0, which turns off the tolerance flag.
-                freeze_transforms (bool): Reset the selected transform and all of its children down to the shape level.
-                returned_type (str): The desired returned object type. This only affects the dict value (found vertex),
-                                the key (orig vertex) is always a string. ex. {'planeShape.vtx[0]': 'objShape.vtx[3]'} vs. {'planeShape.vtx[0]': MeshVertex('objShape.vtx[3]')}
-                                (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            vertices (list): A set of vertices.
+            obj (str/obj/list): The reference object in which to find the closest vertex for each vertex in the list of given vertices.
+            tolerance (float) = Maximum search distance. Default is 0.0, which turns off the tolerance flag.
+            freeze_transforms (bool): Reset the selected transform and all of its children down to the shape level.
+            returned_type (str): The desired returned object type. This only affects the dict value (found vertex),
+                            the key (orig vertex) is always a string. ex. {'planeShape.vtx[0]': 'objShape.vtx[3]'} vs. {'planeShape.vtx[0]': MeshVertex('objShape.vtx[3]')}
+                            (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
         Returns:
-                (dict) closest vertex pairs {<vertex from a>:<vertex from b>}.
+            (dict) closest vertex pairs {<vertex from a>:<vertex from b>}.
 
         Example:
-        get_closest_vertex('plnShape.vtx[0]', 'cyl', returned_type='int') #returns: {'plnShape.vtx[0]': 3},
-        get_closest_vertex('plnShape.vtx[0]', 'cyl') #returns: {'plnShape.vtx[0]': 'cylShape.vtx[3]'},
-        get_closest_vertex('plnShape.vtx[2:3]', 'cyl') #returns: {'plnShape.vtx[2]': 'cylShape.vtx[2]', 'plnShape.vtx[3]': 'cylShape.vtx[1]'}
+            get_closest_vertex('plnShape.vtx[0]', 'cyl', returned_type='int') #returns: {'plnShape.vtx[0]': 3},
+            get_closest_vertex('plnShape.vtx[0]', 'cyl') #returns: {'plnShape.vtx[0]': 'cylShape.vtx[3]'},
+            get_closest_vertex('plnShape.vtx[2:3]', 'cyl') #returns: {'plnShape.vtx[2]': 'cylShape.vtx[2]', 'plnShape.vtx[3]': 'cylShape.vtx[1]'}
         """
-        vertices = misc_utils.Misc.convert_array_type(
+        vertices = utils.Utils.convert_array_type(
             vertices, returned_type="str", flatten=True
         )
         pm.undoInfo(openChunk=True)
 
         if freeze_transforms:
             pm.makeIdentity(obj, apply=True)
 
-        obj2Shape = pm.listRelatives(obj, children=1, shapes=1)[
-            0
-        ]  # pm.listRelatives(obj, fullPath=False, shapes=True, noIntermediate=True)
-
-        cpmNode = pm.ls(pm.createNode("closestPointOnMesh"))[
-            0
-        ]  # create a closestPointOnMesh node.
-        pm.connectAttr(
-            obj2Shape.outMesh, cpmNode.inMesh, force=1
-        )  # object's shape mesh output to the cpm node.
+        # pm.listRelatives(obj, fullPath=False, shapes=True, noIntermediate=True)
+        obj2Shape = pm.listRelatives(obj, children=1, shapes=1)[0]
+        # create a closestPointOnMesh node.
+        cpmNode = pm.ls(pm.createNode("closestPointOnMesh"))[0]
+        # object's shape mesh output to the cpm node.
+        pm.connectAttr(obj2Shape.outMesh, cpmNode.inMesh, force=1)
 
         closestVerts = {}
         for (
             v1
         ) in (
             vertices
         ):  # assure the list of vertices is a flattened list of stings. prevent unhashable type error when closestVerts[v1] = v2.  may not be needed with python versions 3.8+
@@ -785,17 +779,17 @@
 
             index = pm.getAttr(
                 cpmNode.closestVertexIndex
             )  # vertex Index. | ie. result: [34]
             v2 = obj2Shape.vtx[index]
 
             v2Pos = pm.pointPosition(v2, world=True)
-            distance = Math.get_distance(v1Pos, v2Pos)
+            distance = ptk.get_distance(v1Pos, v2Pos)
 
-            v2_convertedType = misc_utils.Misc.convert_array_type(
+            v2_convertedType = utils.Utils.convert_array_type(
                 v2, returned_type=returned_type
             )[0]
             if not tolerance:
                 closestVerts[v1] = v2_convertedType
             elif distance < tolerance:
                 closestVerts[v1] = v2_convertedType
 
@@ -808,112 +802,104 @@
     def get_edge_path(
         cls, components, path="edgeLoop", returned_type="str", flatten=False
     ):
         """Query the polySelect command for the components along different edge paths.
         Supports components from a single object.
 
         Parameters:
-                components (str/obj/list): The components used for the query (dependant on the operation type).
-                path (str): The desired return type. valid: 'edgeLoop': Select an edge loop starting at the given edge.
-                        'edgeRing': Select an edge ring starting at the given edge.
-                        'edgeRingPath', Given two edges that are on the same edge ring, this will select the shortest path between them on the ring.
-                        'edgeLoopPath': Given two edges that are on the same edge loop, this will select the shortest path between them on the loop.
-                returned_type (str): The desired returned object type.
-                        (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            components (str/obj/list): The components used for the query (dependant on the operation type).
+            path (str): The desired return type. valid: 'edgeLoop': Select an edge loop starting at the given edge.
+                    'edgeRing': Select an edge ring starting at the given edge.
+                    'edgeRingPath', Given two edges that are on the same edge ring, this will select the shortest path between them on the ring.
+                    'edgeLoopPath': Given two edges that are on the same edge loop, this will select the shortest path between them on the loop.
+            returned_type (str): The desired returned object type.
+                    (valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list) The components comprising the path.
+            (list) The components comprising the path.
 
         Example:
-        get_edge_path('sph.e[12]', 'edgeLoop') #returns: ['sphShape.e[12]', 'sphShape.e[17]', 'sphShape.e[16]', 'sphShape.e[15]', 'sphShape.e[14]', 'sphShape.e[13]']
-        get_edge_path('sph.e[12]', 'edgeLoop', 'int') #returns: [12, 17, 16, 15, 14, 13]
-        get_edge_path('sph.e[12]', 'edgeRing') #returns: ['sphShape.e[0]', 'sphShape.e[6]', 'sphShape.e[12]', 'sphShape.e[18]', 'sphShape.e[24]']
-        get_edge_path(['sph.e[43]', 'sph.e[46]'], 'edgeRingPath') #returns: ['sphShape.e[43]', 'sphShape.e[42]', 'sphShape.e[47]', 'sphShape.e[46]']
-        get_edge_path(['sph.e[54]', 'sph.e[60]'], 'edgeLoopPath') #returns: ['sphShape.e[60]', 'sphShape.e[48]', 'sphShape.e[42]', 'sphShape.e[36]', 'sphShape.e[30]', 'sphShape.e[54]']
+            get_edge_path('sph.e[12]', 'edgeLoop') #returns: ['sphShape.e[12]', 'sphShape.e[17]', 'sphShape.e[16]', 'sphShape.e[15]', 'sphShape.e[14]', 'sphShape.e[13]']
+            get_edge_path('sph.e[12]', 'edgeLoop', 'int') #returns: [12, 17, 16, 15, 14, 13]
+            get_edge_path('sph.e[12]', 'edgeRing') #returns: ['sphShape.e[0]', 'sphShape.e[6]', 'sphShape.e[12]', 'sphShape.e[18]', 'sphShape.e[24]']
+            get_edge_path(['sph.e[43]', 'sph.e[46]'], 'edgeRingPath') #returns: ['sphShape.e[43]', 'sphShape.e[42]', 'sphShape.e[47]', 'sphShape.e[46]']
+            get_edge_path(['sph.e[54]', 'sph.e[60]'], 'edgeLoopPath') #returns: ['sphShape.e[60]', 'sphShape.e[48]', 'sphShape.e[42]', 'sphShape.e[36]', 'sphShape.e[30]', 'sphShape.e[54]']
         """
         obj, *other = pm.ls(components, objectsOnly=1)
         cnums = cls.convert_component_type(
             components, "edge", returned_type="int", flatten=True
         )
 
         if len(cnums) < 2 and path in ("edgeRingPath", "edgeLoopPath"):
             print(
-                'File "{}" in get_edge_path\n# Error: Operation requires at least two components. #\n Edges given: {}'.format(
-                    __file__, cnums
-                )
+                f'File "{__file__}" in get_edge_path\n# Error: Operation requires at least two components. #\n Edges given: {cnums}',
             )
             return []
 
         if path == "edgeRing":
             edgesLong = pm.polySelect(obj, q=True, edgeRing=cnums)  # (e..)
 
         elif path == "edgeRingPath":
             edgesLong = pm.polySelect(
                 obj, q=True, edgeRingPath=(cnums[0], cnums[1])
             )  # (e, e)
             if not edgesLong:
                 print(
-                    'File "{}" in get_edge_path\n# Error: get_edge_path: Operation requires two edges that are on the same edge ring. #\n   Edges given: {}, {}'.format(
-                        __file__, cnums[0], cnums[1]
-                    )
+                    f'File "{__file__}" in get_edge_path\n# Error: get_edge_path: Operation requires two edges that are on the same edge ring.\n\tEdges given: {cnums[0]}, {cnums[1]}',
                 )
                 return []
 
         elif path == "edgeLoopPath":
             edgesLong = pm.polySelect(
                 obj, q=True, edgeLoopPath=(cnums[0], cnums[1])
             )  # (e, e)
             if not edgesLong:
                 print(
-                    'File "{}" in get_edge_path\n# Error: get_edge_path: Operation requires two edges that are on the same edge loop. #\n   Edges given: {}, {}'.format(
-                        __file__, cnums[0], cnums[1]
-                    )
+                    f'File "{__file__}" in get_edge_path\n# Error: get_edge_path: Operation requires two edges that are on the same edge loop.\n\tEdges given: {cnums[0]}, {cnums[1]}',
                 )
                 return []
-        else:  #'edgeLoop'
+        else:  # EdgeLoop
             edgesLong = pm.polySelect(obj, q=True, edgeLoop=cnums)  # (e..)
 
         objName = obj.name()
-        result = Iter.remove_duplicates(
+        result = ptk.remove_duplicates(
             ["{}.e[{}]".format(objName, e) for e in edgesLong]
         )
-        return misc_utils.Misc.convert_array_type(
+        return utils.Utils.convert_array_type(
             result, returned_type=returned_type, flatten=flatten
         )
 
     @classmethod
     def get_shortest_path(cls, components, returned_type="str", flatten=False):
         """Get the shortest path between two components.
 
         Parameters:
-                components (obj): A Pair of vertices or edges.
-                returned_type (str): The desired returned object type.
-                        valid: 'str'(default), 'obj', 'int'(valid only at sub-object level)
-                flatten (bool): Flattens the returned list of objects so that each component is it's own element.
+            components (obj): A Pair of vertices or edges.
+            returned_type (str): The desired returned object type.
+                    valid: 'str'(default), 'obj', 'int'(valid only at sub-object level)
+            flatten (bool): Flattens the returned list of objects so that each component is it's own element.
 
         Returns:
-                (list) the components that comprise the path as strings.
+            (list) the components that comprise the path as strings.
 
         Example:
-        get_edge_path('sph.e[12]', 'edgeLoop') #returns: ['sphShape.e[12]', 'sphShape.e[17]', 'sphShape.e[16]', 'sphShape.e[15]', 'sphShape.e[14]', 'sphShape.e[13]']
-        get_edge_path('sph.e[12]', 'edgeLoop', 'int') #returns: [12, 17, 16, 15, 14, 13]
-        get_edge_path('sph.e[12]', 'edgeRing') #returns: ['sphShape.e[0]', 'sphShape.e[6]', 'sphShape.e[12]', 'sphShape.e[18]', 'sphShape.e[24]']
-        get_edge_path(['sph.e[43]', 'sph.e[46]'], 'edgeRingPath') #returns: ['sphShape.e[43]', 'sphShape.e[42]', 'sphShape.e[47]', 'sphShape.e[46]']
-        get_edge_path(['sph.e[54]', 'sph.e[60]'], 'edgeLoopPath') #returns: ['sphShape.e[60]', 'sphShape.e[48]', 'sphShape.e[42]', 'sphShape.e[36]', 'sphShape.e[30]', 'sphShape.e[54]']
+            get_edge_path('sph.e[12]', 'edgeLoop') #returns: ['sphShape.e[12]', 'sphShape.e[17]', 'sphShape.e[16]', 'sphShape.e[15]', 'sphShape.e[14]', 'sphShape.e[13]']
+            get_edge_path('sph.e[12]', 'edgeLoop', 'int') #returns: [12, 17, 16, 15, 14, 13]
+            get_edge_path('sph.e[12]', 'edgeRing') #returns: ['sphShape.e[0]', 'sphShape.e[6]', 'sphShape.e[12]', 'sphShape.e[18]', 'sphShape.e[24]']
+            get_edge_path(['sph.e[43]', 'sph.e[46]'], 'edgeRingPath') #returns: ['sphShape.e[43]', 'sphShape.e[42]', 'sphShape.e[47]', 'sphShape.e[46]']
+            get_edge_path(['sph.e[54]', 'sph.e[60]'], 'edgeLoopPath') #returns: ['sphShape.e[60]', 'sphShape.e[48]', 'sphShape.e[42]', 'sphShape.e[36]', 'sphShape.e[30]', 'sphShape.e[54]']
         """
         obj = pm.ls(components, objectsOnly=1)[0]
         ctype = cls.get_component_type(components)
         try:
             A, B = components = cls.convert_component_type(components, ctype)[:2]
-        except ValueError as error:
+        except ValueError as e:
             print(
-                'File "{}" in get_shortest_path\n# Error: Operation requires exactly two components. #\n  {}'.format(
-                    __file__, error
-                )
+                f'File "{__file__}" in get_shortest_path\n# Error: Operation requires exactly two components.\n\t{e}',
             )
             return []
 
         returnAsVerts = False
         if ctype == "vtx":
             edgesA = cls.convert_component_type(A, "e", flatten=1)
             vertsA = cls.convert_component_type(edgesA, "vtx", flatten=1)
@@ -1000,16 +986,15 @@
 
     @staticmethod
     def get_normal_vector(x):
         """Get the normal vectors of the given polygon object(s) or its components.
 
         Parameters:
             x (str/obj/list): A polygon mesh or its components. Accepts a string representation, a PyNode object,
-                              or a list of either, representing one or more polygon meshes or their faces.
-
+                    or a list of either, representing one or more polygon meshes or their faces.
         Returns:
             dict: A dictionary where each key-value pair corresponds to a face of the polygon object(s).
                   The key is the face's ID, and the value is a list representing the face's normal vector in the format [x, y, z].
 
         This function extracts the normal vectors for each face of the provided polygon object(s).
         If components (faces) are provided directly, the function will only calculate and return the normals for those faces.
         """
@@ -1143,18 +1128,16 @@
         return edges
 
     @classmethod
     def set_edge_hardness(
         cls, x, angle_threshold, upper_hardness=None, lower_hardness=None
     ):
         """Sets the hardness (softness) of edges in the provided objects based on their normal angles.
-
         The function recursively processes lists, tuples, and sets of objects, applying the hardness settings
         to each item individually. It also supports PyMel Transform, Mesh, and MeshEdge objects.
-
         If an edge's normal angle is greater than or equal to the given threshold, the edge is considered
         for upper hardness application. If an edge's normal angle is less than the threshold, the edge is
         considered for lower hardness application.
 
         Parameters:
             cls (class): The class that the method is part of.
             x (str, pm.nt.Transform, pm.nt.Mesh, pm.general.MeshEdge, list/tuple/set of these types):
@@ -1177,17 +1160,17 @@
                 cls.set_edge_hardness(
                     item, angle_threshold, upper_hardness, lower_hardness
                 )
             return
 
         # If x is a PyMel object, handle it accordingly
         if isinstance(x, pm.nt.Transform):
-            is_group = node_utils.Node.is_group(x)
+            is_group = node_utils.NodeUtils.is_group(x)
             if is_group:
-                grp_children = node_utils.Node.get_unique_children(x)
+                grp_children = node_utils.NodeUtils.get_unique_children(x)
                 cls.set_edge_hardness(
                     grp_children, angle_threshold, upper_hardness, lower_hardness
                 )
                 return
             shape = x.getShape()
             x = f"{shape.name()}.e[0:{len(shape.edges)-1}]"
         elif isinstance(x, pm.nt.Mesh):
@@ -1239,26 +1222,27 @@
         range_y=0.1,
         range_z=0.1,
         returned_type="str",
     ):
         """Filter for faces with normals that fall within an X,Y,Z tolerance.
 
         Parameters:
-                faces (list): ['polygon faces'] - faces to find similar normals for.
-                similar_faces (list): optional ability to add faces from previous calls to the return value.
-                transforms (list): [<shape nodes>] - objects to check faces on. If none are given the objects containing the given faces will be used.
-                range_x = float - x axis tolerance
-                range_y = float - y axis tolerance
-                range_z = float - z axis tolerance
-                returned_type (str): The desired returned object type.
-                                                valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
+            faces (list): ['polygon faces'] - faces to find similar normals for.
+            similar_faces (list): optional ability to add faces from previous calls to the return value.
+            transforms (list): [<shape nodes>] - objects to check faces on. If none are given the objects containing the given faces will be used.
+            range_x = float - x axis tolerance
+            range_y = float - y axis tolerance
+            range_z = float - z axis tolerance
+            returned_type (str): The desired returned object type.
+                        valid: 'str'(default), 'obj'(shape object), 'transform'(as string), 'int'(valid only at sub-object level).
         Returns:
-                (list) faces that fall within the given normal range.
+            (list) faces that fall within the given normal range.
 
-        ex. get_faces_with_similar_normals(selectedFaces, range_x=0.5, range_y=0.5, range_z=0.5)
+        Example:
+            get_faces_with_similar_normals(selectedFaces, range_x=0.5, range_y=0.5, range_z=0.5)
         """
         # Work on a copy of the argument so that removal of elements doesn't effect the passed in list.
         faces = pm.ls(faces, flatten=1)
         for face in faces:
             normals = cls.get_normal_vector(face)
 
             for k, v in normals.items():
@@ -1331,25 +1315,25 @@
     @classmethod
     def filter_components_by_connection_count(
         cls, components, num_of_connected=(0, 2), connected_type="", returned_type="str"
     ):
         """Get a list of components filtered by the number of their connected components.
 
         Parameters:
-                components (str/list)(obj): The components to filter.
-                num_of_connected (int)(tuple): The number of connected components. Can be given as a range. (Default: (0,2))
-                connected_type (str)(int): The desired component mask. (valid: 'vtx','vertex','vertices','Polygon Vertex',31,0x0001(vertices), 'e','edge','edges','Polygon Edge',32,0x8000(edges), 'f','face','faces','Polygon Face',34,0x0008(faces), 'uv','texture','texture coordinates','Polygon UV',35,0x0010(texture coordiantes).
-                returned_type (str): The desired returned object type.
+            components (str/list)(obj): The components to filter.
+            num_of_connected (int)(tuple): The number of connected components. Can be given as a range. (Default: (0,2))
+            connected_type (str)(int): The desired component mask. (valid: 'vtx','vertex','vertices','Polygon Vertex',31,0x0001(vertices), 'e','edge','edges','Polygon Edge',32,0x8000(edges), 'f','face','faces','Polygon Face',34,0x0008(faces), 'uv','texture','texture coordinates','Polygon UV',35,0x0010(texture coordiantes).
+            returned_type (str): The desired returned object type.
                         valid: 'str'(default), 'obj', 'int'(valid only at sub-object level)
-
         Returns:
-                (list) flattened list.
+            (list) flattened list.
 
-        ex. faces = filter_components_by_connection_count('sph.f[:]', 4, 'e') #returns faces with four connected edges (four sided faces).
-        ex. verts = filter_components_by_connection_count('pln.vtx[:]', (0,2), 'e') #returns vertices with up to two connected edges.
+        Example:
+            faces = filter_components_by_connection_count('sph.f[:]', 4, 'e') #returns faces with four connected edges (four sided faces).
+            verts = filter_components_by_connection_count('pln.vtx[:]', (0,2), 'e') #returns vertices with up to two connected edges.
         """
         try:
             lowRange, highRange = num_of_connected
         except TypeError:
             lowRange = highRange = num_of_connected
 
         typ = cls.get_component_type(components)
@@ -1361,52 +1345,52 @@
         result = []
         for c in pm.ls(components, flatten=True):
             attached = cls.convert_component_type(c, ctype, flatten=True)
             n = len(attached)
             if n >= lowRange and n <= highRange:
                 result.append(c)
 
-        result = misc_utils.Misc.convert_array_type(result, returned_type=returned_type)
+        result = utils.Utils.convert_array_type(result, returned_type=returned_type)
         return result
 
     @classmethod
     def get_vertex_normal(cls, vertex, angle_weighted=False):
         """Return the normal at the given vertex. The returned normal is a single
         per-vertex normal, so unshared normals at a vertex will be averaged.
 
         Parameters:
-                vertex (str/obj/list): A polygon vertex.
-                angle_weighted (bool): Weight by the angle subtended by the face at the vertex.
-                        If angle_weighted is set to false, a simple average of surround face normals is returned.
-                        The simple average evaluation is significantly faster than the angle-weighted average.
+            vertex (str/obj/list): A polygon vertex.
+            angle_weighted (bool): Weight by the angle subtended by the face at the vertex.
+                    If angle_weighted is set to false, a simple average of surround face normals is returned.
+                    The simple average evaluation is significantly faster than the angle-weighted average.
         Returns:
-                (MVector)
+            (MVector)
         """
         import maya.api.OpenMaya as om
 
         mesh = pm.ls(vertex, objectsOnly=True)[0].name()
         selectionList = om.MSelectionList()  # empty selection list.
         selectionList.add(mesh)
 
         dagPath = selectionList.getDagPath(0)  # create empty dag path object.
         mesh = om.MFnMesh(dagPath)  # get mesh.
 
-        vtxID = misc_utils.Misc.convert_array_type(vertex, "int")[0]
+        vtxID = utils.Utils.convert_array_type(vertex, "int")[0]
         # get vertex normal and use om.MSpace.kObject for object space.
         return mesh.getVertexNormal(vtxID, angle_weighted, space=om.MSpace.kWorld)
 
     @staticmethod
     def get_vector_from_components(components):
         """Get a vector representing the averaged and normalized vertex-face normals.
 
         Parameters:
-                components (list): A list of component to get normals of.
+            components (list): A list of component to get normals of.
 
         Returns:
-                (tuple) vector ie. (-4.5296159711938344e-08, 1.0, 1.6846732009412335e-08)
+            (tuple) vector ie. (-4.5296159711938344e-08, 1.0, 1.6846732009412335e-08)
         """
         vertices = pm.polyListComponentConversion(components, toVertex=1)
 
         norm = pm.polyNormalPerVertex(
             vertices, query=True, xyz=True
         )  # return all of the normals associated with the vert.
         normal_vector = (
@@ -1534,14 +1518,15 @@
                 ):  # If an edge has more than two uvs or less than 2 faces, it's a uv border edge.
                     uv_border_edges.append(edge)
 
         return uv_border_edges
 
     @staticmethod
     def transfer_uvs(source, target):
+        """ """
         import maya.api.OpenMaya as om2
 
         # Create a MSelectionList
         sList = om2.MSelectionList()
 
         # Add objects to the list (accepts both PyNodes and strings)
         if isinstance(source, str):
@@ -1575,28 +1560,25 @@
         for i in range(poly_count):
             count = sFnMesh.polygonVertexCount(i)
             for j in range(count):
                 uv_id = sFnMesh.getPolygonUVid(i, j)
                 tFnMesh.assignUV(i, j, uv_id)
 
 
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
 
-# --------------------------------------------------------------------------------------------
-# deprecated:
-# --------------------------------------------------------------------------------------------
 
+# deprecated ---------------------
 # def filter_components(cls, frm, inc=[], exc=[]):
 #       '''Filter the given 'frm' list for the items in 'exc'.
 
 #       Parameters:
 #           frm (str/obj/list): The components(s) to filter.
 #           inc (str/obj/list): The component(s) to include.
 #           exc (str/obj/list): The component(s) to exclude.
@@ -1634,10 +1616,10 @@
 #           obj = pm.ls(frm, objectsOnly=1)
 #           if len(obj)>1:
 #               return frm
 #           component_type = cls.get_component_type(frm[0])
 #           typ = cls.convert_alias(component_type) #get the correct component_type variable from possible args.
 #           inc = ["{}.{}[{}]".format(obj[0], typ, n) for n in inc]
 
-#       inc = misc_utils.Misc.convert_array_type(inc, returned_type=rtn, flatten=True) #assure both lists are of the same type for comparison.
-#       exc = misc_utils.Misc.convert_array_type(exc, returned_type=rtn, flatten=True)
+#       inc = utils.Utils.convert_array_type(inc, returned_type=rtn, flatten=True) #assure both lists are of the same type for comparison.
+#       exc = utils.Utils.convert_array_type(exc, returned_type=rtn, flatten=True)
 #       return [i for i in components if i not in exc and (inc and i in inc)]
```

### Comparing `mayatk-0.6.6/mayatk/cmpt_utils.py.bak` & `mayatk-0.6.7/mayatk/cmpt_utils.py.bak`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk/display_utils/exploded_view.py` & `mayatk-0.6.7/mayatk/display_utils/exploded_view.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,19 +5,18 @@
 except ModuleNotFoundError as error:
     print(__file__, error)
 try:
     import maya.OpenMaya as om
 except ModuleNotFoundError as error:
     print(__file__, error)
 
-from pythontk import get_distance
-
 # from this package:
-from mayatk.xform_utils import Xform
-from mayatk.node_utils import Node
+from mayatk.utils import Utils
+from mayatk.xform_utils import XformUtils
+from mayatk.node_utils import NodeUtils
 
 
 class ExplodedView:
     exploded_objects = []
 
     @staticmethod
     def calculate_repulsive_force(centroid1, size1, centroid2, size2, scale=0.05):
@@ -70,15 +69,17 @@
 
         Returns:
                 int: The number of iterations required for the system to converge.
         """
         iteration_count = 0
         converged = False
 
-        node_data = [Xform.get_bounding_box(node, "center|maxsize") for node in nodes]
+        node_data = [
+            XformUtils.get_bounding_box(node, "center|maxsize") for node in nodes
+        ]
 
         while not converged and iteration_count < max_iterations:
             total_system_force = om.MVector(0, 0, 0)
 
             for idx1, node1 in enumerate(nodes):
                 total_force = om.MVector(0, 0, 0)
 
@@ -121,27 +122,27 @@
             iteration_count += 1
 
         cls.exploded_objects.append(nodes)
         return iteration_count
 
     def explode_selected(self):
         """Explode selected"""
-        selection = Node.get_unique_children(pm.ls(sl=True))
+        selection = NodeUtils.get_unique_children(pm.ls(sl=True))
         for obj in selection:
             if obj.hasAttr("original_position"):
                 selection.remove(obj)
                 continue
             pos = pm.xform(obj, query=True, translation=True, worldSpace=True)
-            Node.set_node_attributes(obj, original_position=pos)
+            NodeUtils.set_node_attributes(obj, original_position=pos)
 
         iterations = self.arrange_objects(selection)
 
     def un_explode_selected(self):
         """Un-explode selected"""
-        selection = Node.get_unique_children(pm.ls(sl=True))
+        selection = NodeUtils.get_unique_children(pm.ls(sl=True))
         for obj in selection:
             if pm.attributeQuery("original_position", node=obj, exists=True):
                 pos = pm.getAttr(obj.original_position)
                 pm.move(pos[0], pos[1], pos[2], obj, absolute=True)
                 pm.deleteAttr(obj, attribute="original_position")
 
     def un_explode_all(self):
@@ -151,15 +152,15 @@
             obj = obj_attr.node()
             pos = pm.getAttr(obj.original_position)
             pm.move(pos[0], pos[1], pos[2], obj, absolute=True)
             pm.deleteAttr(obj, attribute="original_position")
 
     def toggle_explode(self):
         """Toggle explode"""
-        selection = Node.get_unique_children(pm.ls(sl=True))
+        selection = NodeUtils.get_unique_children(pm.ls(sl=True))
         if selection:
             if pm.attributeQuery("original_position", node=selection[0], exists=True):
                 self.un_explode_selected()
             else:
                 self.explode_selected()
 
 
@@ -181,17 +182,16 @@
         self.toggle_explode()
 
 
 def launch_gui(move_to_cursor=False, frameless_window=False):
     """Launch the UI"""
     from PySide2 import QtCore, QtGui
     from uitk import Switchboard
-    from mayatk.misc_utils import Misc
 
-    parent = Misc.get_main_window()
+    parent = Utils.get_main_window()
     sb = Switchboard(
         parent, ui_location="exploded_view.ui", slots_location=ExplodedViewSlots
     )
     if frameless_window:
         sb.ui.setWindowFlags(QtCore.Qt.Tool | QtCore.Qt.FramelessWindowHint)
         sb.ui.setAttribute(QtCore.Qt.WA_TranslucentBackground)
     else:
@@ -201,9 +201,19 @@
         sb.move_and_center_widget(sb.ui, QtGui.QCursor.pos())
     else:
         sb.center_widget_on_screen(sb.ui)
 
     sb.ui.show()
 
 
+# -----------------------------------------------------------------------------
+
+
 if __name__ == "__main__":
     launch_gui()
+
+# -----------------------------------------------------------------------------
+# Notes
+# -----------------------------------------------------------------------------
+
+
+# deprecated ---------------------
```

### Comparing `mayatk-0.6.6/mayatk/edit_utils.py` & `mayatk-0.6.7/mayatk/edit_utils.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,60 +1,60 @@
 # !/usr/bin/python
 # coding=utf-8
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-
-from pythontk import Str, Iter, are_similar
+import pythontk as ptk
 
 # from this package:
-from mayatk import misc_utils, node_utils, cmpt_utils, xform_utils
+from mayatk import utils, node_utils, cmpt_utils, xform_utils
 
 
-class Edit:
+class EditUtils:
     """ """
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def rename(objects, to, fltr="", regex=False, ignore_case=False):
         """Rename scene objects.
 
         Parameters:
-                objects (str/obj/list): The object(s to rename. If nothing is given, all scene objects will be renamed.
-                to (str): Desired name: An optional asterisk modifier can be used for formatting
-                        chars - replace all.
-                        *chars* - replace only.
-                        *chars - replace suffix.
-                        **chars - append suffix.
-                        chars* - replace prefix.
-                        chars** - append prefix.
-                fltr (str): Optionally, filter which the given objects to rename using the following:
-                        An asterisk denotes startswith*, *endswith, *contains*, and multiple search strings can be separated by pipe ('|') chars.
-                        chars - Search exact.
-                        *chars* - Search contains chars.
-                        *chars - Search endswith chars.
-                        chars* - Search startswith chars.
-                        chars|chars - Search any of.  can be used in conjuction with other modifiers.
-                regex (bool): If True, regular expression syntax is used instead of the default '*' and '|' modifiers.
-                ignore_case (bool): Ignore case when searching. Applies only to the 'fltr' parameter's search.
-
-        ex. rename(r'Cube', '*001', regex=True) #replace chars after 'fltr' on any object with a name that contains 'Cube'. ie. 'polyCube001' from 'polyCube'
-        ex. rename(r'Cube', '**001', regex=True) #append chars on any object with a name that contains 'Cube'. ie. 'polyCube1001' from 'polyCube1'
+            objects (str/obj/list): The object(s to rename. If nothing is given, all scene objects will be renamed.
+            to (str): Desired name: An optional asterisk modifier can be used for formatting
+                    chars - replace all.
+                    *chars* - replace only.
+                    *chars - replace suffix.
+                    **chars - append suffix.
+                    chars* - replace prefix.
+                    chars** - append prefix.
+            fltr (str): Optionally, filter which the given objects to rename using the following:
+                    An asterisk denotes startswith*, *endswith, *contains*, and multiple search strings can be separated by pipe ('|') chars.
+                    chars - Search exact.
+                    *chars* - Search contains chars.
+                    *chars - Search endswith chars.
+                    chars* - Search startswith chars.
+                    chars|chars - Search any of.  can be used in conjuction with other modifiers.
+            regex (bool): If True, regular expression syntax is used instead of the default '*' and '|' modifiers.
+            ignore_case (bool): Ignore case when searching. Applies only to the 'fltr' parameter's search.
+
+        Example:
+            rename(r'Cube', '*001', regex=True) #replace chars after 'fltr' on any object with a name that contains 'Cube'. ie. 'polyCube001' from 'polyCube'
+            rename(r'Cube', '**001', regex=True) #append chars on any object with a name that contains 'Cube'. ie. 'polyCube1001' from 'polyCube1'
         """
         # pm.undoInfo (openChunk=1)
         objects = pm.ls(objectsOnly=1) if not objects else pm.ls(objects)
 
         # get the short names from the long in order to correctly format. ex. 'NUT_' from: 'CENTER_HINGE_FEMALE_GRP|NUT_'
         long_names = [obj.name() for obj in objects]
         short_names = [
-            ii if ii else i for i, ii in Str.split_at_chars(long_names)
+            ii if ii else i for i, ii in ptk.split_at_chars(long_names)
         ]  # split the long names at the last '|' to get the short name.
 
-        names = Str.find_str_and_format(
+        names = ptk.find_str_and_format(
             short_names,
             to,
             fltr,
             regex=regex,
             ignore_case=ignore_case,
             return_orig_strings=True,
         )
@@ -88,66 +88,69 @@
                         '# Error: Attempt to rename "{}" to "{}" failed. {} #'.format(
                             oldName, newName, str(e).rstrip()
                         )
                     )
         # pm.undoInfo (closeChunk=1)
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def set_case(objects=[], case="caplitalize"):
         """Rename objects following the given case.
 
         Parameters:
-                objects (str/list): The objects to rename. default:all scene objects
-                case (str): Desired case using python case operators.
-                        valid: 'upper', 'lower', 'caplitalize', 'swapcase' 'title'. default:'caplitalize'
+            objects (str/list): The objects to rename. default:all scene objects
+            case (str): Desired case using python case operators.
+                    valid: 'upper', 'lower', 'caplitalize', 'swapcase' 'title'. default:'caplitalize'
 
-        Example: set_case(pm.ls(sl=1), 'upper')
+        Example:
+            set_case(pm.ls(sl=1), 'upper')
         """
         # pm.undoInfo(openChunk=1)
         for obj in pm.ls(objects):
             name = obj.name()
 
             newName = getattr(name, case)()
             try:
                 pm.rename(name, newName)
             except Exception as error:
                 if not pm.ls(obj, readOnly=True) == []:  # ignore read-only errors.
                     print(name + ": ", error)
         # pm.undoInfo(closeChunk=1)
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def append_location_based_suffix(
         objects,
         alphanumeric=False,
         strip_trailing_ints=True,
         strip_trailing_alpha=True,
         reverse=False,
     ):
         """Rename objects with a suffix defined by its location from origin.
 
         Parameters:
-                objects (str)(int/list): The object(s) to rename.
-                alphanumeric (str): When True use an alphanumeric character as a suffix when there is less than 26 objects else use integers.
-                strip_trailing_ints (bool): Strip any trailing integers. ie. 'cube123'
-                strip_trailing_alpha (bool): Strip any trailing uppercase alphanumeric chars that are prefixed with an underscore.  ie. 'cube_A'
-                reverse (bool): Reverse the naming order. (Farthest object first)
+            objects (str)(int/list): The object(s) to rename.
+            alphanumeric (str): When True use an alphanumeric character as a suffix when there is less than 26 objects else use integers.
+            strip_trailing_ints (bool): Strip any trailing integers. ie. 'cube123'
+            strip_trailing_alpha (bool): Strip any trailing uppercase alphanumeric chars that are prefixed with an underscore.  ie. 'cube_A'
+            reverse (bool): Reverse the naming order. (Farthest object first)
         """
         import string
         import re
 
         length = len(objects)
         if alphanumeric:
             if length <= 26:
                 suffix = string.ascii_lowercase.upper()
         else:
             suffix = [str(n).zfill(len(str(length))) for n in range(length)]
 
-        ordered_objs = xform_utils.Xform.order_by_distance(objects, reverse=reverse)
+        ordered_objs = xform_utils.XformUtils.order_by_distance(
+            objects, reverse=reverse
+        )
 
         newNames = {}  # the object with the new name set as a key.
         for n, obj in enumerate(ordered_objs):
             current_name = obj.name()
 
             while (
                 (current_name[-1] == "_" or current_name[-1].isdigit())
@@ -186,21 +189,21 @@
             pm.rename(obj, newNames[obj])
 
     @staticmethod
     def snap_closest_verts(obj1, obj2, tolerance=10.0, freeze_transforms=False):
         """Snap the vertices from object one to the closest verts on object two.
 
         Parameters:
-                obj1 (obj): The object in which the vertices are moved from.
-                obj2 (obj): The object in which the vertices are moved to.
-                tolerance (float) = Maximum search distance.
-                freeze_transforms (bool): Reset the selected transform and all of its children down to the shape level.
+            obj1 (obj): The object in which the vertices are moved from.
+            obj2 (obj): The object in which the vertices are moved to.
+            tolerance (float) = Maximum search distance.
+            freeze_transforms (bool): Reset the selected transform and all of its children down to the shape level.
         """
-        vertices = cmpt_utils.Cmpt.get_components(obj1, "vertices")
-        closestVerts = cmpt_utils.Cmpt.get_closest_vertex(
+        vertices = cmpt_utils.CmptUtils.get_components(obj1, "vertices")
+        closestVerts = cmpt_utils.CmptUtils.get_closest_vertex(
             vertices, obj2, tolerance=tolerance, freeze_transforms=freeze_transforms
         )
 
         progressBar = "mainProgressBar"
         pm.progressBar(
             progressBar,
             edit=True,
@@ -224,17 +227,17 @@
         pm.progressBar(progressBar, edit=True, endProgress=True)
 
     @staticmethod
     def merge_vertices(objects, selected=False, tolerance=0.001):
         """Merge Vertices on the given objects.
 
         Parameters:
-                objects (str/obj/list): The object(s) to merge vertices on.
-                selected (bool): Merge only the currently selected components.
-                tolerance (float) = The maximum merge distance.
+            objects (str/obj/list): The object(s) to merge vertices on.
+            selected (bool): Merge only the currently selected components.
+            tolerance (float) = The maximum merge distance.
         """
         for obj in pm.ls(objects):
             if selected:  # merge selected components.
                 if pm.filterExpand(selectionMask=31):  # selectionMask=vertices
                     sel = pm.ls(obj, sl=1)
                     pm.polyMergeVertex(
                         sel,
@@ -258,53 +261,70 @@
                 pm.select(objects)
 
     @staticmethod
     def get_all_faces_on_axis(obj, axis="-x", localspace=False):
         """Get all faces on a specified axis.
 
         Parameters:
-                obj (str/obj): The name of the geometry.
-                axis (str): The representing axis. case insensitive. (valid: 'x', '-x', 'y', '-y', 'z', '-z')
-                localspace (bool): Specify world or local space.
-
-        ex call: get_all_faces_on_axis('polyObject', 'y')
-        """
-        axis = axis.lower()  # assure case.
-
-        i = 0  #'x'
-        if any([axis == "y", axis == "-y"]):
-            i = 1
-        if any([axis == "z", axis == "-z"]):
-            i = 2
-
-        objName = pm.ls(obj)[0].name()
-
-        if axis.startswith("-"):  # any([axis=="-x", axis=="-y", axis=="-z"]):
-            return list(
-                face
-                for face in pm.filterExpand(objName + ".f[*]", sm=34)
-                if pm.exactWorldBoundingBox(face)[i] < -0.00001
+            obj (str/obj): The name of the geometry.
+            axis (str): The representing axis. case insensitive. (valid: 'x', '-x', 'y', '-y', 'z', '-z')
+            localspace (bool): Specify world or local space.
+
+        Example:
+            get_all_faces_on_axis('polyObject', 'y')
+        """
+        obj = pm.ls(obj)[0] if pm.ls(obj) else None
+
+        if not obj:
+            raise ValueError(f"No such object exists: {obj}")
+
+        # Get shape nodes
+        shapes = obj.getShapes()
+        if not shapes:
+            raise ValueError("The object has no shape nodes.")
+
+        # Validate axis
+        valid_axes = {"x": 0, "-x": 0, "y": 1, "-y": 1, "z": 2, "-z": 2}
+        axis = axis.lower()
+        if axis not in valid_axes:
+            raise ValueError(
+                "Invalid axis. Valid options are 'x', '-x', 'y', '-y', 'z', '-z'"
             )
+
+        i = valid_axes[axis]
+        # Collect faces from all geometry type shapes
+        faces = []
+        for shape in shapes:
+            if pm.nodeType(shape) not in ["mesh", "nurbsSurface", "subdiv"]:
+                continue
+            faces.extend(pm.filterExpand(f"{shape.name()}.f[*]", sm=34))
+
+        if not faces:
+            raise ValueError("The shape nodes have no faces.")
+
+        # Get faces on the specified axis
+        if axis.startswith("-"):
+            return [
+                face for face in faces if pm.exactWorldBoundingBox(face)[i] < -0.00001
+            ]
         else:
-            return list(
-                face
-                for face in pm.filterExpand(objName + ".f[*]", sm=34)
-                if pm.exactWorldBoundingBox(face)[i] > -0.00001
-            )
+            return [
+                face for face in faces if pm.exactWorldBoundingBox(face)[i] > -0.00001
+            ]
 
     @classmethod
     def delete_along_axis(cls, objects, axis="-x"):
         """Delete components of the given mesh object along the specified axis.
 
         Parameters:
             obj (obj): Mesh object.
             axis (str): Axis to delete on. ie. '-x' Components belonging to the mesh object given in the 'obj' arg, that fall on this axis, will be deleted.
         """
         # Get any mesh type child nodes of obj.
-        for node in (o for o in objects if not node_utils.Node.is_group(o)):
+        for node in (o for o in pm.ls(objects) if not node_utils.NodeUtils.is_group(o)):
             faces = cls.get_all_faces_on_axis(node, axis)
             # If all faces fall on the specified axis.
             if len(faces) == pm.polyEvaluate(node, face=1):
                 pm.delete(node)  # Delete entire node
             else:
                 pm.delete(faces)  # Else, delete any individual faces.
 
@@ -331,17 +351,17 @@
         invalidComponents=False,
         split_non_manifold_vertex=False,
         historyOn=True,
     ):
         """Select or remove unwanted geometry from a polygon mesh.
 
         Parameters:
-                objects (str/obj/list): The polygon objects to clean.
-                allMeshes (bool): Clean all geomtry in the scene instead of only the current selection.
-                repair (bool): Attempt to repair instead of just selecting geometry.
+            objects (str/obj/list): The polygon objects to clean.
+            allMeshes (bool): Clean all geomtry in the scene instead of only the current selection.
+            repair (bool): Attempt to repair instead of just selecting geometry.
         """
         arg_list = '"{0}","{1}","{2}","{3}","{4}","{5}","{6}","{7}","{8}","{9}","{10}","{11}","{12}","{13}","{14}","{15}","{16}","{17}"'.format(
             allMeshes,
             1 if repair else 2,
             historyOn,
             quads,
             nsided,
@@ -380,31 +400,32 @@
     @staticmethod
     def get_overlapping_dup_objects(
         objects=[], retain_given_objects=False, select=False, verbose=False
     ):
         """Find any duplicate overlapping geometry at the object level.
 
         Parameters:
-                objects (list): A list of objects to find duplicate overlapping geometry for. Default is selected objects, or all if nothing is selected.
-                retain_given_objects (bool): Search only for duplicates of the given objects (or any selected objects if None given), and omit them from the return results.
-                select (bool): Select any found duplicate objects.
-                verbose (bool): Print each found object to console.
+            objects (list): A list of objects to find duplicate overlapping geometry for. Default is selected objects, or all if nothing is selected.
+            retain_given_objects (bool): Search only for duplicates of the given objects (or any selected objects if None given), and omit them from the return results.
+            select (bool): Select any found duplicate objects.
+            verbose (bool): Print each found object to console.
 
         Returns:
-                (set)
+            (set)
 
-        ex call: duplicates = get_overlapping_dup_objects(retain_given_objects=True, select=True, verbose=True)
+        Example:
+            duplicates = get_overlapping_dup_objects(retain_given_objects=True, select=True, verbose=True)
         """
         scene_objs = pm.ls(transforms=1, geometry=1)  # get all scene geometry
 
         # attach a unique identifier consisting each objects polyEvaluate attributes, and it's bounding box center point in world space.
         scene_objs = {
             i: str(pm.objectCenter(i)) + str(pm.polyEvaluate(i))
             for i in scene_objs
-            if not node_utils.Node.is_group(i)
+            if not node_utils.NodeUtils.is_group(i)
         }
         selected_objs = pm.ls(scene_objs.keys(), sl=1) if not objects else objects
 
         objs_inverted = {}  # invert the dict, combining objects with like identifiers.
         for k, v in scene_objs.items():
             objs_inverted[v] = objs_inverted.get(v, []) + [k]
 
@@ -439,24 +460,24 @@
         return duplicates
 
     @staticmethod
     def find_non_manifold_vertex(objects, select=1):
         """Locate a connected vertex of non-manifold geometry where the faces share a single vertex.
 
         Parameters:
-                objects (str/obj/list): A polygon mesh, or a list of meshes.
-                select (int): Select any found non-manifold vertices. 0=off, 1=on, 2=on while keeping any existing vertex selections. (default: 1)
+            objects (str/obj/list): A polygon mesh, or a list of meshes.
+            select (int): Select any found non-manifold vertices. 0=off, 1=on, 2=on while keeping any existing vertex selections. (default: 1)
 
         Returns:
-                (set) any found non-manifold verts.
+            (set) any found non-manifold verts.
         """
         pm.undoInfo(openChunk=True)
         nonManifoldVerts = set()
 
-        vertices = cmpt_utils.Cmpt.get_components(objects, "vertices")
+        vertices = cmpt_utils.CmptUtils.get_components(objects, "vertices")
         for vertex in vertices:
             connected_faces = pm.polyListComponentConversion(
                 vertex, fromVertex=1, toFace=1
             )  # pm.mel.PolySelectConvert(1) #convert to faces
             connected_faces_flat = pm.ls(
                 connected_faces, flatten=1
             )  # selectedFaces = pm.ls(sl=1, flatten=1)
@@ -509,16 +530,16 @@
         return nonManifoldVerts
 
     @staticmethod
     def split_non_manifold_vertex(vertex, select=True):
         """Separate a connected vertex of non-manifold geometry where the faces share a single vertex.
 
         Parameters:
-                vertex (str/obj): A single polygon vertex.
-                select (bool): Select the vertex after the operation. (default is True)
+            vertex (str/obj): A single polygon vertex.
+            select (bool): Select the vertex after the operation. (default is True)
         """
         pm.undoInfo(openChunk=True)
         connected_faces = pm.polyListComponentConversion(
             vertex, fromVertex=1, toFace=1
         )  # pm.mel.PolySelectConvert(1) #convert to faces
         connected_faces_flat = pm.ls(
             connected_faces, flatten=1
@@ -533,22 +554,22 @@
                 face, fromFace=1, toVertex=1
             )  # pm.mel.PolySelectConvert(1) #convert to faces
             connected_verts_flat = [
                 str(i) for i in pm.ls(connected_verts, flatten=1)
             ]  # selectedFaces = pm.ls(sl=1, flatten=1)
             verts_sorted_by_face.append(connected_verts_flat)
 
-        out = (
-            []
-        )  # 1) take first set A from list. 2) for each other set B in the list do if B has common element(s) with A join B into A; remove B from list. 3) repeat 2. until no more overlap with A. 4) put A into outpup. 5) repeat 1. with rest of list.
+        # 1) take first set A from list. 2) for each other set B in the list do if B has common element(s) with A join B into A; remove B from list. 3) repeat 2. until no more overlap with A. 4) put A into outpup. 5) repeat 1. with rest of list.
+        out = []
         while len(verts_sorted_by_face) > 0:
+            # first, *rest = verts_sorted_by_face
             first, rest = (
                 verts_sorted_by_face[0],
                 verts_sorted_by_face[1:],
-            )  # first, *rest = verts_sorted_by_face
+            )
             first = set(first)
 
             lf = -1
             while len(first) > lf:
                 lf = len(first)
 
                 rest2 = []
@@ -561,39 +582,36 @@
 
             out.append(first)
             verts_sorted_by_face = rest
 
         for vertex_set in out:
             pm.polyMergeVertex(vertex_set, distance=0.001)
 
-        pm.select(
-            vertex_set, deselect=1
-        )  # deselect the vertices that were selected during the polyMergeVertex operation.
+        # deselect the vertices that were selected during the polyMergeVertex operation.
+        pm.select(vertex_set, deselect=1)
         if select:
             pm.select(vertex, add=1)
         pm.undoInfo(closeChunk=True)
 
     @staticmethod
     def get_ngons(objects, repair=False):
         """Get any N-Gons from the given object using selection contraints.
 
         Parameters:
-                objects (str/obj/list): The objects to query.
-                repair (bool): Repair any found N-gons.
+            objects (str/obj/list): The objects to query.
+            repair (bool): Repair any found N-gons.
 
         Returns:
-                (list)
+            (list)
         """
         pm.select(objects)
-        pm.mel.changeSelectMode(
-            1
-        )  # Change to Component mode to retain object highlighting
-        pm.selectType(
-            smp=0, sme=1, smf=0, smu=0, pv=0, pe=1, pf=0, puv=0
-        )  # Change to Face Component Mode
+        # Change to Component mode to retain object highlighting
+        pm.mel.changeSelectMode(1)
+        # Change to Face Component Mode
+        pm.selectType(smp=0, sme=1, smf=0, smu=0, pv=0, pe=1, pf=0, puv=0)
         # Select Object/s and Run Script to highlight N-Gons
         pm.polySelectConstraint(mode=3, type=0x0008, size=3)
         nGons = pm.ls(sl=1)
         pm.polySelectConstraint(disable=1)
 
         if repair:  # convert N-Sided Faces To Quads
             pm.polyQuad(nGons, angle=30, kgb=1, ktb=1, khe=1, ws=1)
@@ -601,24 +619,24 @@
         return nGons
 
     @staticmethod
     def get_overlapping_vertices(objects, threshold=0.0003):
         """Query the given objects for overlapping vertices.
 
         Parameters:
-                objects (str/obj/list): The objects to query.
-                threshold (float) = The maximum allowed distance.
+            objects (str/obj/list): The objects to query.
+            threshold (float) = The maximum allowed distance.
 
         Returns:
-                (list)
+            (list)
         """
         import maya.OpenMaya as om
 
         result = []
-        for mfnMesh in misc_utils.Misc.mfn_mesh_generator(objects):
+        for mfnMesh in utils.Utils.mfn_mesh_generator(objects):
             points = om.MPointArray()
             mfnMesh.getPoints(points, om.MSpace.kWorld)
 
             for i in range(points.length()):
                 for ii in range(points.length()):
                     if i == ii:
                         continue
@@ -633,26 +651,26 @@
         return result
 
     @classmethod
     def get_overlapping_faces(cls, objects):
         """Get any duplicate overlapping faces of the given objects.
 
         :Parameters:
-                objects (str/obj/list): Faces or polygon objects.
+            objects (str/obj/list): Faces or polygon objects.
 
         Returns:
-                (list) duplicate overlapping faces.
+            (list) duplicate overlapping faces.
 
         Example: pm.select(get_overlapping_faces(selection))
         """
         if not objects:
             return []
 
         elif not pm.nodeType(objects) == "mesh":  # if the objects are not faces.
-            duplicates = Iter.flatten(
+            duplicates = ptk.flatten(
                 [
                     cls.get_overlapping_faces(obj.faces)
                     for obj in pm.ls(objects, objectsOnly=1)
                 ]
             )
             return list(duplicates)
 
@@ -672,36 +690,36 @@
             ]
 
             if face_vtx_positions == otherFace_vtx_positions:  # duplicate found.
                 duplicates.append(otherFace)
                 otherFaces.remove(otherFace)
 
         if otherFaces:
-            duplicates += cls.get_overlapping_faces(
-                otherFaces
-            )  # after adding any found duplicates, call again with any remaining faces.
+            # after adding any found duplicates, call again with any remaining faces.
+            duplicates += cls.get_overlapping_faces(otherFaces)
 
         return duplicates
 
     @staticmethod
     def get_similar_mesh(obj, tolerance=0.0, inc_orig=False, **kwargs):
         """Find similar geometry objects using the polyEvaluate command.
         Default behaviour is to compare all flags.
 
         Parameters:
-                obj (str/obj/list): The object to find similar for.
-                tolerance (float) = The allowed difference in any of the given polyEvalute flag results (that return an int, float (or list of the int or float) value(s)).
-                inc_orig (bool): Include the original given obj with the return results.
-                kwargs (bool): Any keyword argument 'polyEvaluate' takes. Used to filter the results.
-                        ex: vertex, edge, face, uvcoord, triangle, shell, boundingBox, boundingBox2d,
-                        vertexComponent, boundingBoxComponent, boundingBoxComponent2d, area, worldArea
+            obj (str/obj/list): The object to find similar for.
+            tolerance (float) = The allowed difference in any of the given polyEvalute flag results (that return an int, float (or list of the int or float) value(s)).
+            inc_orig (bool): Include the original given obj with the return results.
+            kwargs (bool): Any keyword argument 'polyEvaluate' takes. Used to filter the results.
+                    ex: vertex, edge, face, uvcoord, triangle, shell, boundingBox, boundingBox2d,
+                    vertexComponent, boundingBoxComponent, boundingBoxComponent2d, area, worldArea
         Returns:
-                (list) Similar objects.
+            (list) Similar objects.
 
-        Example: get_similar_mesh(selection, vertex=1, area=1)
+        Example:
+            get_similar_mesh(selection, vertex=1, area=1)
         """
         lst = (
             lambda x: list(x)
             if isinstance(x, (list, tuple, set))
             else list(x.values())
             if isinstance(x, dict)
             else [x]
@@ -713,34 +731,34 @@
         otherSceneMeshes = set(
             pm.filterExpand(pm.ls(long=True, typ="transform"), selectionMask=12)
         )  # polygon selection mask.
         similar = pm.ls(
             [
                 m
                 for m in otherSceneMeshes
-                if are_similar(
+                if ptk.are_similar(
                     objProps, lst(pm.polyEvaluate(m, **kwargs)), tolerance=tolerance
                 )
                 and m != obj
             ]
         )
         return similar + [obj] if inc_orig else similar
 
     @staticmethod
     def get_similar_topo(obj, inc_orig=False, **kwargs):
         """Find similar geometry objects using the polyCompare command.
         Default behaviour is to compare all flags.
 
         Parameters:
-                obj (str/obj/list): The object to find similar for.
-                inc_orig (bool): Include the original given obj with the return results.
-                kwargs (bool): Any keyword argument 'polyCompare' takes. Used to filter the results.
-                        ex: vertices, edges, faceDesc, uvSets, uvSetIndices, colorSets, colorSetIndices, userNormals
+            obj (str/obj/list): The object to find similar for.
+            inc_orig (bool): Include the original given obj with the return results.
+            kwargs (bool): Any keyword argument 'polyCompare' takes. Used to filter the results.
+                    ex: vertices, edges, faceDesc, uvSets, uvSetIndices, colorSets, colorSetIndices, userNormals
         Returns:
-                (list) Similar objects.
+            (list) Similar objects.
         """
         obj, *other = pm.filterExpand(
             pm.ls(obj, long=True, tr=True), selectionMask=12
         )  # polygon selection mask.
 
         otherSceneMeshes = set(
             pm.filterExpand(pm.ls(long=True, typ="transform"), sm=12)
@@ -751,21 +769,17 @@
                 for m in otherSceneMeshes
                 if pm.polyCompare(obj, m, **kwargs) == 0 and m != obj
             ]
         )  # 0:equal,Verts:1,Edges:2,Faces:4,UVSets:8,UVIndices:16,ColorSets:32,ColorIndices:64,UserNormals=128. So a return value of 3 indicates both vertices and edges are different.
         return similar + [obj] if inc_orig else similar
 
 
-# --------------------------------------------------------------------------------------------
-
+# -----------------------------------------------------------------------------
 
 if __name__ == "__main__":
     pass
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 # Notes
-# --------------------------------------------------------------------------------------------
-
+# -----------------------------------------------------------------------------
 
-# --------------------------------------------------------------------------------------------
-# deprecated:
-# --------------------------------------------------------------------------------------------
+# deprecated ---------------------
```

### Comparing `mayatk-0.6.6/mayatk/macro_utils.py` & `mayatk-0.6.7/mayatk/macro_utils.py`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk/mash_utils.py` & `mayatk-0.6.7/mayatk/mash_utils.py`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk/mash_utils.py.bak` & `mayatk-0.6.7/mayatk/mash_utils.py.bak`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk/mat_utils/mat_utils.py` & `mayatk-0.6.7/mayatk/mat_utils/mat_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,15 +6,15 @@
     print(__file__, error)
 import pythontk as ptk
 
 # from this package:
 from mayatk import node_utils
 
 
-class Mat(object):
+class MatUtils(object):
     """ """
 
     @staticmethod
     def get_mats(objs):
         """Returns the set of materials assigned to a given list of objects or components.
 
         Parameters:
@@ -62,15 +62,15 @@
         Returns:
             list: A list of materials in the scene.
         """
         matList = pm.ls(mat=1, flatten=1)
 
         # convert to dictionary to filter material names and types.
         d = {m.name(): pm.nodeType(m) for m in matList}
-        filtered = ptk.Iter.filter_dict(d, inc, exc, keys=True, values=True)
+        filtered = ptk.filter_dict(d, inc, exc, keys=True, values=True)
 
         # use the filtered results to reconstruct a filtered list of actual materials.
         return [m for m in matList if m.name() in filtered]
 
     @staticmethod
     def get_fav_mats():
         """Retrieves the list of favorite materials in Maya.
@@ -186,15 +186,15 @@
 
         objs_with_material = []
         for sg in shading_groups:
             connected_objs = pm.sets(sg, query=True, noIntermediate=True)
             flattened = pm.ls(connected_objs, flatten=True)
             # Only add objects to the list if they are in the specified objects list
             for obj in flattened:
-                transform_node = node_utils.Node.get_transform_node(obj)
+                transform_node = node_utils.NodeUtils.get_transform_node(obj)
                 if transform_node in objects:
                     # Check if the object is a face. If not, convert to faces
                     if not isinstance(obj, pm.MeshFace):
                         shape_node = pm.listRelatives(transform_node, shapes=True)[0]
                         face_count = pm.polyEvaluate(shape_node, f=True)
                         faces = [f"{shape_node}.f[{i}]" for i in range(face_count)]
                         objs_with_material.extend(faces)
@@ -203,20 +203,18 @@
 
         if shell:
             objs_with_material = set(pm.ls(objs_with_material, objectsOnly=True))
 
         return objs_with_material
 
 
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

### Comparing `mayatk-0.6.6/mayatk/mat_utils/stingray_arnold_shader.py` & `mayatk-0.6.7/mayatk/mat_utils/stingray_arnold_shader.py`

 * *Files 7% similar despite different names*

```diff
@@ -6,16 +6,16 @@
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
 from uitk import Switchboard
 import pythontk as ptk
 
 # from this package:
-from mayatk.misc_utils import Misc
-from mayatk.node_utils import Node
+from mayatk.utils import Utils
+from mayatk.node_utils import NodeUtils
 
 
 __version__ = "0.5.3"
 
 
 class StingrayArnoldShader:
     """
@@ -34,50 +34,52 @@
             return node[0]
         except IndexError:
             return None
 
     @hdr_env.setter
     def hdr_env(self, tex) -> None:
         """ """
-        node = self.hdr_env  # Node.node_exists('aiSkyDomeLight', search='exactType')
+        node = (
+            self.hdr_env
+        )  # NodeUtils.node_exists('aiSkyDomeLight', search='exactType')
         if not node:
-            node = Node.create_render_node(
+            node = NodeUtils.create_render_node(
                 "aiSkyDomeLight",
                 "asLight",
                 name=self.hdr_env_name,
                 camera=0,
                 skyRadius=0,
             )  # turn off skydome and viewport visibility.
             self.hdr_env_transform.hiddenInOutliner.set(1)
             pm.outlinerEditor("outlinerPanel1", edit=True, refresh=True)
 
-        file_node = Node.get_incoming_node_by_type(node, "file")
+        file_node = NodeUtils.get_incoming_node_by_type(node, "file")
         if not file_node:
-            file_node = Node.create_render_node(
+            file_node = NodeUtils.create_render_node(
                 "file", "as2DTexture", texture_node=True
             )
             pm.connectAttr(file_node.outColor, node.color, force=True)
 
         file_node.fileTextureName.set(tex)
 
     @property
     def hdr_env_transform(self) -> object:
         """ """
-        node = Node.get_transform_node(self.hdr_env)
+        node = NodeUtils.get_transform_node(self.hdr_env)
         if not node:
             return None
         return node
 
     def set_hdr_map_visibility(self, state):
         """ """
         node = self.hdr_env
         if node:
             node.camera.set(state)
 
-    @Misc.undo
+    @Utils.undo
     def create_network(
         self,
         textures,
         name="",
         hdrMap="",
         hdrMapVisibility=False,
         normalMapType="OpenGL",
@@ -96,16 +98,16 @@
             return None
         try:
             pm.loadPlugin("mtoa", quiet=True)  # assure arnold plugin is loaded.
             pm.loadPlugin(
                 "shaderFXPlugin", quiet=True
             )  # assure stringray plugin is loaded.
 
-            sr_node = Node.create_render_node("StingrayPBS", name=name)
-            ai_node = Node.create_render_node(
+            sr_node = NodeUtils.create_render_node("StingrayPBS", name=name)
+            ai_node = NodeUtils.create_render_node(
                 "aiStandardSurface", name=name + "_ai" if name else ""
             )
 
             opacityMap = ptk.filter_images_by_type(textures, "Opacity")
             if opacityMap:
                 pm.shaderfx(
                     sfxnode="StingrayPBS1",
@@ -121,22 +123,22 @@
                 callback(f"OpenGL map created using {ptk.truncate(directXMap[0], 20)}.")
             if openGLMap and not directXMap and normalMapType == "Normal_DirectX":
                 mapPath = ptk.create_dx_from_gl(openGLMap[0])
                 textures.append(mapPath)
                 normal_map_created_from_other_type = True
                 callback(f"DirectX map created using {ptk.truncate(openGLMap[0], 20)}.")
 
-            srSG_node = Node.get_outgoing_node_by_type(sr_node, "shadingEngine")
+            srSG_node = NodeUtils.get_outgoing_node_by_type(sr_node, "shadingEngine")
 
             aiMult_node = pm.shadingNode("aiMultiply", asShader=True)
 
             bump_node = pm.shadingNode("bump2d", asShader=True)
             bump_node.bumpInterp.set(1)  # set bump node to 'tangent space normals'
 
-            Node.connect_multi_attr(  # set node connections.
+            NodeUtils.connect_multi_attr(  # set node connections.
                 (ai_node.outColor, srSG_node.aiSurfaceShader),
                 (aiMult_node.outColor, ai_node.baseColor),
                 (bump_node.outNormal, ai_node.normalCamera),
             )
 
             length = len(textures)
             progress = 0
@@ -155,101 +157,101 @@
 
                 callback(
                     f"creating nodes and connections for <b>{typ}</b> map ..",
                     [progress, length],
                 )
 
                 if typ == "Base_Color":
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outColor, sr_node.TEX_color_map, force=True)
                     sr_node.use_color_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file", "as2DTexture", tex=f, texture_node=True
                     )
                     pm.connectAttr(n2.outColor, aiMult_node.input1, force=True)
 
                 elif typ == "Roughness":
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outColor, sr_node.TEX_roughness_map, force=True)
                     sr_node.use_roughness_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file",
                         "as2DTexture",
                         tex=f,
                         texture_node=True,
                         colorSpace="Raw",
                         alphaIsLuminance=1,
                         ignoreColorSpaceFileRules=1,
                     )
                     pm.connectAttr(n2.outAlpha, ai_node.specularRoughness, force=True)
                     pm.connectAttr(
                         n2.outAlpha, ai_node.transmissionExtraRoughness, force=True
                     )  # opacity: same roughness map used in Specular Roughness to provide additional bluriness of refraction.
 
                 elif typ == "Metallic":
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outColor, sr_node.TEX_metallic_map, force=True)
                     sr_node.use_metallic_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file",
                         "as2DTexture",
                         tex=f,
                         texture_node=True,
                         colorSpace="Raw",
                         alphaIsLuminance=1,
                         ignoreColorSpaceFileRules=1,
                     )
                     pm.connectAttr(n2.outAlpha, ai_node.metalness, force=True)
 
                 elif typ == "Emissive":
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outColor, sr_node.TEX_emissive_map, force=True)
                     sr_node.use_emissive_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file", "as2DTexture", tex=f, texture_node=True
                     )
                     pm.connectAttr(n2.outAlpha, ai_node.emission, force=True)
                     pm.connectAttr(n2.outColor, ai_node.emissionColor, force=True)
 
                 elif "Normal" in typ:
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outColor, sr_node.TEX_normal_map, force=True)
                     sr_node.use_normal_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file",
                         "as2DTexture",
                         tex=f,
                         texture_node=True,
                         colorSpace="Raw",
                         alphaIsLuminance=1,
                         ignoreColorSpaceFileRules=1,
                     )
                     pm.connectAttr(n2.outAlpha, bump_node.bumpValue, force=True)
 
                 elif typ == "Ambient_Occlusion":
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outColor, sr_node.TEX_ao_map, force=True)
                     sr_node.use_ao_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file", "as2DTexture", tex=f, texture_node=True
                     )
                     pm.connectAttr(n2.outColor, aiMult_node.input2, force=True)
 
                 elif typ == "Opacity":
-                    n1 = Node.create_render_node("file", "as2DTexture", tex=f)
+                    n1 = NodeUtils.create_render_node("file", "as2DTexture", tex=f)
                     pm.connectAttr(n1.outAlpha, sr_node.opacity, force=True)
                     sr_node.use_opacity_map.set(1)
 
-                    n2 = Node.create_render_node(
+                    n2 = NodeUtils.create_render_node(
                         "file",
                         "as2DTexture",
                         tex=f,
                         texture_node=True,
                         colorSpace="Raw",
                         alphaIsLuminance=1,
                         ignoreColorSpaceFileRules=1,
@@ -286,114 +288,91 @@
     """
     msg_completed = '<br><hl style="color:rgb(0, 255, 255);"><b>COMPLETED.</b></hl>'
 
     proj_root_dir = ptk.get_filepath(__file__)
 
     def __init__(self, **kwargs):
         super().__init__()
-        """
-        """
+        """ """
         self.sb = self.switchboard()
         self.image_files = None
 
-        # set json file location.
-        path = f"{self.sb.default_dir}/stingray_arnold_shader.json"
-        ptk.set_json_file(path)  # set json file name
-
-        # add filenames|filepaths to the comboBox.
+        # Add filenames|filepaths to the comboBox.
         hdr_path = f"{self.proj_root_dir}/resources/hdr"
         hdr_filenames = ptk.get_dir_contents(hdr_path, "filenames", inc_files="*.exr")
         hdr_fullpaths = ptk.get_dir_contents(hdr_path, "filepaths", inc_files="*.exr")
         self.sb.ui.cmb000.add(dict(zip(hdr_filenames, hdr_fullpaths)), ascending=False)
 
-        # initialize widgets with any saved values.
-        self.sb.ui.txt000.setText(ptk.get_json("mat_name"))
         self.sb.ui.txt001.setText(self.msg_intro)
-        hdr_map_visibility = ptk.get_json("hdr_map_visibility")
-        if hdr_map_visibility:
-            self.sb.ui.chk000.setChecked(hdr_map_visibility)
-        hdr_map = ptk.get_json("hdr_map")
-        if hdr_map:
-            self.sb.ui.cmb000.setCurrentItem(hdr_map)
-        normal_map_type = ptk.get_json("normal_map_type")
-        if normal_map_type:
-            self.sb.ui.cmb001.setCurrentItem(normal_map_type)
+
         node = self.hdr_env_transform
         if node:
             rotation = node.rotateY.get()
             self.sb.ui.slider000.setSliderPosition(rotation)
 
     @property
     def mat_name(self) -> str:
         """Get the mat name from the user input text field.
 
         Returns:
-                (str)
+            (str)
         """
         text = self.sb.ui.txt000.text()
         return text
 
     @property
     def hdr_map(self) -> str:
         """Get the hdr map filepath from the comboBoxes current text.
 
         Returns:
-                (str) data as string.
+            (str) data as string.
         """
         data = self.sb.ui.cmb000.currentData()
         return data
 
     @property
     def hdr_map_visibility(self) -> bool:
         """Get the hdr map visibility state from the checkBoxes current state.
 
         Returns:
-                (bool)
+            (bool)
         """
         state = self.sb.ui.chk000.isChecked()
         return state
 
     @property
     def normal_map_type(self) -> str:
         """Get the normal map type from the comboBoxes current text.
 
         Returns:
-                (str)
+            (str)
         """
         text = self.sb.ui.cmb001.currentText()
         return text
 
     def cmb000(self, index, widget):
         """HDR map selection."""
-        text = widget.currentText()
         data = widget.currentData()
 
         self.hdr_env = data  # set the HDR map.
-        ptk.set_json("hdr_map", text)
 
     def cmb001(self, index, widget):
         """Normal map output selection."""
-        cmb = self.sb.ui.cmb001
-        text = cmb.currentText()
-        ptk.set_json("normal_map_type", text)
 
     def chk000(self, state, widget):
         """ """
         self.set_hdr_map_visibility(state)  # set the HDR map visibility.
-        ptk.set_json("hdr_map_visibility", state)
 
     def txt000(self, text, widget):
         """Material name."""
-        text = widget.text()
-        ptk.set_json("mat_name", text)
 
     def slider000(self, value, widget):
         """Rotate the HDR map."""
         if self.hdr_env:
-            transform = Node.get_transform_node(self.hdr_env)
+            transform = NodeUtils.get_transform_node(self.hdr_env)
             pm.rotate(
                 transform,
                 value,
                 rotateY=True,
                 forceOrderXYZ=True,
                 objectSpace=True,
                 absolute=True,
@@ -433,20 +412,33 @@
             ) in msg_mat_selection:  # format msg_intro using the map_types in imtools.
                 self.callback(ptk.truncate(i, 60))
 
             self.sb.ui.b000.setDisabled(False)
         elif not self.image_files:
             self.sb.ui.b000.setDisabled(True)
 
+    def toggle_expand(self, state, widget):
+        """ """
+        if state:
+            if not hasattr(self, "_height_open"):
+                self._height_closed = self.sb.ui.height()
+                self._height_open = self.sb.ui.sizeHint().height() + 100
+            self.sb.ui.txt001.show()
+            self.sb.ui.resize(self.sb.ui.width(), self._height_open)
+        else:
+            self._height_open = self.sb.ui.height()
+            self.sb.ui.txt001.hide()
+            self.sb.ui.resize(self.sb.ui.width(), self._height_closed)
+
     def callback(self, string, progress=None, clear=False):
         """
         Parameters:
-                string (str): The text to output to a textEdit widget.
-                progress (int/list): The progress amount to register with the progressBar.
-                        Can be given as an int or a tuple as: (progress, total_len)
+            string (str): The text to output to a textEdit widget.
+            progress (int/list): The progress amount to register with the progressBar.
+                    Can be given as an int or a tuple as: (progress, total_len)
         """
         if clear:
             self.sb.ui.txt003.clear()
 
         if isinstance(progress, (list, tuple, set)):
             p, length = progress
             progress = (p / length) * 100
@@ -465,39 +457,22 @@
         super().__init__(parent)
 
         self.ui_location = "stingray_arnold_shader.ui"
         self.slots_location = StingrayArnoldShaderSlots
 
         self.ui.draggableHeader.hide()
         self.ui.txt001.hide()
-        self.ui.toggle_expand.clicked.connect(self.toggle_text_edit)
 
         self.ui.resize(self.ui.sizeHint())
 
-    def toggle_text_edit(self):
-        txt = self.ui.txt001
-        if txt.isVisible():
-            self._height_open = self.ui.height()
-            txt.hide()
-            self.ui.resize(self.ui.width(), self._height_closed)
-        else:
-            self._height_closed = self.ui.height()
-            txt.show()
-            self.ui.resize(
-                self.ui.width(),
-                self._height_open
-                if hasattr(self, "_height_open")
-                else self.ui.sizeHint().height(),
-            )
-
 
 # -----------------------------------------------------------------------------
 
 if __name__ == "__main__":
-    parent = Misc.get_main_window()
+    parent = Utils.get_main_window()
     sb = StingrayArnoldShaderUI(parent)
     sb.ui.set_style(theme="dark")
     sb.ui.show(app_exec=True)
 
 # -----------------------------------------------------------------------------
 # Notes
 # -----------------------------------------------------------------------------
```

### Comparing `mayatk-0.6.6/mayatk/misc_utils.py` & `mayatk-0.6.7/mayatk/misc_utils.py.bak`

 * *Files 2% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 # coding=utf-8
 import os, sys
 
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-from pythontk import Iter, Str
+from pythontk import Iter
 
 # from this package:
 from mayatk import node_utils
 
 
 class Misc:
     """ """
@@ -162,37 +162,35 @@
             dagPath = om.MDagPath()
             selectionList.getDagPath(i, dagPath)
             # print (dagPath.fullPathName()) #debug
             mfnMesh = om.MFnMesh(dagPath)
             yield mfnMesh
 
     @staticmethod
-    def get_array_type(array):
-        """Determine the given element(s) type.
+    def get_array_type(lst):
+        """Determine if the given element(s) type.
         Samples only the first element.
 
         Parameters:
-            array (str/obj/list): The components(s) to query.
+            obj (str/obj/list): The components(s) to query.
 
         Returns:
-            (list) 'str', 'int'(valid only at sub-object level), or maya object type as string.
+            (list) 'str', 'obj'(shape node), 'transform'(as string), 'int'(valid only at sub-object level)
+
+        Example:
+        get_array_type('cyl.vtx[0]') #returns: 'transform'
+        get_array_type('cylShape.vtx[:]') #returns: 'str'
         """
         try:
-            o = Iter.make_iterable(array)[0]
-        except IndexError:
+            o = Iter.make_iterable(lst)[0]
+        except IndexError as error:
             # print (f'# Error: {__file__} in get_array_type:\n#\tOperation requires at least one object.\n#\t{error}')
             return ""
 
-        return (
-            "str"
-            if isinstance(o, str)
-            else "int"
-            if isinstance(o, int)
-            else node_utils.Node.get_type(o)
-        )
+        return "str" if isinstance(o, str) else "int" if isinstance(o, int) else "obj"
 
     @staticmethod
     def convert_array_type(lst, returned_type="str", flatten=False):
         """Convert the given element(s) to <obj>, 'str', or int values.
 
         Parameters:
             lst (str/obj/list): The components(s) to convert.
@@ -270,18 +268,25 @@
         Example:
             >>> get_parameter_mapping(obj, 'transformLimits', ['enableTranslationX','translationX'])
             {'enableTranslationX': [False, False], 'translationX': [-1.0, 1.0]}
         """
         cmd = getattr(pm, cmd)
         node = pm.ls(node)[0]
 
-        return {p: cmd(node, **{"q": True, p: True}) for p in parameters}
+        result = {}
+        for p in parameters:
+            # Query the parameter to get it's value.
+            values = cmd(node, **{"q": True, p: True})
+
+            result[p] = values
+
+        return result
 
     @staticmethod
-    def set_parameter_mapping(node, cmd, parameters):
+    def set_parameter_values(node, cmd, parameters):
         """Applies a set of parameter values to a specified Maya node using a given Maya command.
 
         Parameters:
             node (str/obj/list): The object to query attributes of.
             parameters (dict): The command's parameters and their desired values. ie. {'enableTranslationX': [False, False], 'translationX': [-1.0, 1.0]}
 
         Example:
@@ -308,15 +313,15 @@
         if attrs is None:
             attrs = []
         return attrs
 
     @staticmethod
     def get_panel(*args, **kwargs):
         """Returns panel and panel configuration information.
-        A fix for the broken pymel command `getPanel`.
+        A fix for the broken pymel command of the same name.
 
         Parameters:
             [allConfigs=boolean], [allPanels=boolean], [allScriptedTypes=boolean], [allTypes=boolean], [configWithLabel=string], [containing=string], [invisiblePanels=boolean], [scriptType=string], [type=string], [typeOf=string], [underPointer=boolean], [visiblePanels=boolean], [withFocus=boolean], [withLabel=string])
 
         Returns:
             (str) An array of panel names.
         """
```

### Comparing `mayatk-0.6.6/mayatk/misc_utils.py.bak` & `mayatk-0.6.7/mayatk/utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,22 +1,23 @@
 # !/usr/bin/python
 # coding=utf-8
-import os, sys
+import os
+import sys
 
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-from pythontk import Iter
+import pythontk as ptk
 
 # from this package:
 from mayatk import node_utils
 
 
-class Misc:
+class Utils:
     """ """
 
     def undo(fn):
         """A decorator to place a function into Maya's undo chunk.
         Prevents the undo queue from breaking entirely if an exception is raised within the given function.
 
         Parameters:
@@ -120,15 +121,15 @@
         """
         from PySide2 import QtWidgets
         from shiboken2 import wrapInstance
         from maya.OpenMayaUI import MQtUtil
 
         layout = QtWidgets.QVBoxLayout(container)
         layout.setContentsMargins(0, 0, 0, 0)
-        layoutName = Str.set_case(
+        layoutName = ptk.set_case(
             container.objectName() + "Layout", "camel"
         )  # results in '<objectName>Layout' or 'layout' if container objectName is ''
         layout.setObjectName(layoutName)
         pm.setParent(layoutName)
 
         from uitk.switchboard import Switchboard
 
@@ -151,46 +152,48 @@
 
         Returns:
             (generator)
         """
         import maya.OpenMaya as om
 
         selectionList = om.MSelectionList()
-        for mesh in node_utils.Node.get_shape_node(pm.ls(objects)):
+        for mesh in node_utils.NodeUtils.get_shape_node(pm.ls(objects)):
             selectionList.add(mesh)
 
         for i in range(selectionList.length()):
             dagPath = om.MDagPath()
             selectionList.getDagPath(i, dagPath)
             # print (dagPath.fullPathName()) #debug
             mfnMesh = om.MFnMesh(dagPath)
             yield mfnMesh
 
     @staticmethod
-    def get_array_type(lst):
-        """Determine if the given element(s) type.
+    def get_array_type(array):
+        """Determine the given element(s) type.
         Samples only the first element.
 
         Parameters:
-            obj (str/obj/list): The components(s) to query.
+            array (str/obj/list): The components(s) to query.
 
         Returns:
-            (list) 'str', 'obj'(shape node), 'transform'(as string), 'int'(valid only at sub-object level)
-
-        Example:
-        get_array_type('cyl.vtx[0]') #returns: 'transform'
-        get_array_type('cylShape.vtx[:]') #returns: 'str'
+            (list) 'str', 'int'(valid only at sub-object level), or maya object type as string.
         """
         try:
-            o = Iter.make_iterable(lst)[0]
-        except IndexError as error:
+            o = ptk.make_iterable(array)[0]
+        except IndexError:
             # print (f'# Error: {__file__} in get_array_type:\n#\tOperation requires at least one object.\n#\t{error}')
             return ""
 
-        return "str" if isinstance(o, str) else "int" if isinstance(o, int) else "obj"
+        return (
+            "str"
+            if isinstance(o, str)
+            else "int"
+            if isinstance(o, int)
+            else node_utils.NodeUtils.get_type(o)
+        )
 
     @staticmethod
     def convert_array_type(lst, returned_type="str", flatten=False):
         """Convert the given element(s) to <obj>, 'str', or int values.
 
         Parameters:
             lst (str/obj/list): The components(s) to convert.
@@ -236,16 +239,16 @@
                     )
                     break
 
             objects = set(pm.ls(lst, objectsOnly=True))
             if (
                 len(objects) == 1
             ):  # flatten the dict values from 'result' and remove any duplicates.
-                flattened = Iter.flatten(result.values())
-                result = Iter.remove_duplicates(flattened)
+                flattened = ptk.flatten(result.values())
+                result = ptk.remove_duplicates(flattened)
 
         elif returned_type == "str":
             result = list(map(str, lst))
 
         else:
             result = lst
 
@@ -268,25 +271,18 @@
         Example:
             >>> get_parameter_mapping(obj, 'transformLimits', ['enableTranslationX','translationX'])
             {'enableTranslationX': [False, False], 'translationX': [-1.0, 1.0]}
         """
         cmd = getattr(pm, cmd)
         node = pm.ls(node)[0]
 
-        result = {}
-        for p in parameters:
-            # Query the parameter to get it's value.
-            values = cmd(node, **{"q": True, p: True})
-
-            result[p] = values
-
-        return result
+        return {p: cmd(node, **{"q": True, p: True}) for p in parameters}
 
     @staticmethod
-    def set_parameter_values(node, cmd, parameters):
+    def set_parameter_mapping(node, cmd, parameters):
         """Applies a set of parameter values to a specified Maya node using a given Maya command.
 
         Parameters:
             node (str/obj/list): The object to query attributes of.
             parameters (dict): The command's parameters and their desired values. ie. {'enableTranslationX': [False, False], 'translationX': [-1.0, 1.0]}
 
         Example:
@@ -313,15 +309,15 @@
         if attrs is None:
             attrs = []
         return attrs
 
     @staticmethod
     def get_panel(*args, **kwargs):
         """Returns panel and panel configuration information.
-        A fix for the broken pymel command of the same name.
+        A fix for the broken pymel command `getPanel`.
 
         Parameters:
             [allConfigs=boolean], [allPanels=boolean], [allScriptedTypes=boolean], [allTypes=boolean], [configWithLabel=string], [containing=string], [invisiblePanels=boolean], [scriptType=string], [type=string], [typeOf=string], [underPointer=boolean], [visiblePanels=boolean], [withFocus=boolean], [withLabel=string])
 
         Returns:
             (str) An array of panel names.
         """
```

### Comparing `mayatk-0.6.6/mayatk/node_utils.py` & `mayatk-0.6.7/mayatk/node_utils.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 # !/usr/bin/python
 # coding=utf-8
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-from pythontk import Iter, format_return
+import pythontk as ptk
 
 # from this package:
-from mayatk import misc_utils, cmpt_utils
+from mayatk import utils, cmpt_utils
 
 
-class Node:
+class NodeUtils:
     """ """
 
     @staticmethod
     def node_exists(n, search="name"):
         """Check if the node exists in the current scene.
 
         Parameters:
@@ -43,20 +43,20 @@
         types = []
         for obj in pm.ls(objects):
             if cls.is_group(obj):
                 typ = "group"
             elif cls.is_locator(obj):
                 typ = "locator"
             else:
-                typ = cmpt_utils.Cmpt.get_component_type(obj)
+                typ = cmpt_utils.CmptUtils.get_component_type(obj)
             if not typ:
                 typ = pm.objectType(obj)
             types.append(typ)
 
-        return format_return(types, objects)
+        return ptk.format_return(types, objects)
 
     @classmethod
     def is_locator(cls, obj):
         """Check if the object is a locator.
         A locator is a transform node that has a shape node child.
         The shape node defines the appearance and behavior of the locator.
 
@@ -88,15 +88,15 @@
                 # Check if the transform node does not have any shape nodes directly beneath it
                 no_shapes = len(n.getShapes(noIntermediate=True)) == 0
                 q = is_transform and no_shapes
             except AttributeError:
                 q = False
             result.append(q)
 
-        return format_return(result, objects)
+        return ptk.format_return(result, objects)
 
     @classmethod
     def get_groups(cls, empty=False):
         """Get all groups in the scene.
 
         Parameters:
             empty (bool): Return only empty groups.
@@ -206,21 +206,21 @@
             for n in transforms:
                 result.append(n)
 
         if attributes:
             result = pm.listAttr(result, read=1, hasData=1)
 
         # convert element type.
-        result = misc_utils.Misc.convert_array_type(
+        result = utils.Utils.convert_array_type(
             result, returned_type=returned_type, flatten=True
         )
         # filter
-        result = Iter.filter_list(result, inc, exc)
+        result = ptk.filter_list(result, inc, exc)
         # return as list if `nodes` was given as a list.
-        return format_return(list(set(result)), nodes)
+        return ptk.format_return(list(set(result)), nodes)
 
     @classmethod
     def get_shape_node(
         cls, nodes, returned_type="obj", attributes=False, inc=[], exc=[]
     ):
         """Get shape node(s) or node attributes.
 
@@ -251,21 +251,21 @@
             for n in shapes:
                 result.append(n)
 
         if attributes:
             result = pm.listAttr(result, read=1, hasData=1)
 
         # convert element type.
-        result = misc_utils.Misc.convert_array_type(
+        result = utils.Utils.convert_array_type(
             result, returned_type=returned_type, flatten=True
         )
         # filter
-        result = Iter.filter_list(result, inc, exc)
+        result = ptk.filter_list(result, inc, exc)
         # return as list if `nodes` was given as a list.
-        return format_return(list(set(result)), nodes)
+        return ptk.format_return(list(set(result)), nodes)
 
     @staticmethod
     def get_history_node(nodes, returned_type="obj", attributes=False, inc=[], exc=[]):
         """Get history node(s) or node attributes.
 
         Parameters:
             nodes (str/obj/list): A relative of a history Node.
@@ -297,21 +297,21 @@
                     continue
             result.append(history)
 
         if attributes:
             result = pm.listAttr(result, read=1, hasData=1)
 
         # convert element type.
-        result = misc_utils.Misc.convert_array_type(
+        result = utils.Utils.convert_array_type(
             result, returned_type=returned_type, flatten=True
         )
         # filter
-        result = Iter.filter_list(result, inc, exc)
+        result = ptk.filter_list(result, inc, exc)
         # return as list if `nodes` was given as a list.
-        return format_return(list(set(result)), nodes)
+        return ptk.format_return(list(set(result)), nodes)
 
     @classmethod
     def create_render_node(
         cls,
         node_type,
         flag="asShader",
         secondary_flag="surfaceShader",
@@ -387,35 +387,37 @@
             node (str/obj): A node with incoming connections.
             typ (str): The node type to search for. ie. 'StingrayPBS'
             exact (bool): Only consider nodes of the exact type. Otherwise, derived types are also taken into account.
 
         Returns:
             (obj)(None) node if found.
 
-        Example: env_file_node = get_incoming_node_by_type(env_node, 'file') #get the incoming file node.
+        Example:
+            env_file_node = get_incoming_node_by_type(env_node, 'file') #get the incoming file node.
         """
         nodes = pm.listConnections(node, type=typ, source=True, exactType=exact)
-        return format_return([pm.PyNode(n) for n in nodes])
+        return ptk.format_return([pm.PyNode(n) for n in nodes])
 
     @staticmethod
     def get_outgoing_node_by_type(node, typ, exact=True):
         """Get the connected node of the given type with an outgoing connection to the given node.
 
         Parameters:
             node (str/obj): A node with outgoing connections.
             typ (str): The node type to search for. ie. 'file'
             exact (bool): Only consider nodes of the exact type. Otherwise, derived types are also taken into account.
 
         Returns:
             (list)(obj)(None) node(s)
 
-        Example: srSG_node = get_outgoing_node_by_type(sr_node, 'shadingEngine') #get the outgoing shadingEngine node.
+        Example:
+            srSG_node = get_outgoing_node_by_type(sr_node, 'shadingEngine') #get the outgoing shadingEngine node.
         """
         nodes = pm.listConnections(node, type=typ, destination=True, exactType=exact)
-        return format_return([pm.PyNode(n) for n in nodes])
+        return ptk.format_return([pm.PyNode(n) for n in nodes])
 
     @staticmethod
     def get_node_attributes(node, inc=[], exc=[], mapping=False, **kwargs):
         """Retrieves specified node's attributes along with their corresponding values, represented as a dictionary.
 
         Parameters:
             node (obj): The target node from which to extract attributes.
@@ -427,15 +429,15 @@
         Returns:
             dict: A dictionary that pairs each attribute (as a string) to its current value. If 'mapping' is False, only the values of the attributes are returned.
         """
         kwargs.setdefault("read", True)
         kwargs.setdefault("hasData", True)
         kwargs.setdefault("settable", True)
 
-        attr_names = Iter.filter_list(
+        attr_names = ptk.filter_list(
             pm.listAttr(node, **kwargs),
             inc,
             exc,
         )
 
         result = {}
         for attr_name in attr_names:
@@ -651,70 +653,18 @@
 
         assembly_node.addChild = lambda child: pm.parent(child, assembly_node)
         assembly_node.children = lambda: pm.listRelatives(assembly_node, children=True)
 
         return assembly_node
 
 
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
-
-
-# def filter_components(cls, frm, inc=[], exc=[]):
-#       '''Filter the given 'frm' list for the items in 'exc'.
-
-#       Parameters:
-#           frm (str/obj/list): The components(s) to filter.
-#           inc (str/obj/list): The component(s) to include.
-#           exc (str/obj/list): The component(s) to exclude.
-#                               (exlude take precidence over include)
-#       Returns:
-#           (list)
-
-#       Example: filter_components('obj.vtx[:]', 'obj.vtx[1:23]') #returns: [MeshVertex('objShape.vtx[0]'), MeshVertex('objShape.vtx[24]'), MeshVertex('objShape.vtx[25]')]
-#       '''
-#       exc = pm.ls(exc, flatten=True)
-#       if not exc:
-#           return frm
-
-#       c, *other = components = pm.ls(frm, flatten=True)
-#       #determine the type of items in 'exc' by sampling the first element.
-#       if isinstance(c, str):
-#           if 'Shape' in c:
-#               rtn = 'transform'
-#           else:
-#               rtn = 'str'
-#       elif isinstance(c, int):
-#           rtn = 'int'
-#       else:
-#           rtn = 'obj'
-
-#       if exc and isinstance(exc[0], int): #attempt to create a component list from the given integers. warning: this will only exclude from a single object.
-#           obj = pm.ls(frm, objectsOnly=1)
-#           if len(obj)>1:
-#               return frm
-#           component_type = cls.get_component_type(frm[0])
-#           typ = cls.convert_alias(component_type) #get the correct component_type variable from possible args.
-#           exc = ["{}.{}[{}]".format(obj[0], typ, n) for n in exc]
-
-#       if inc and isinstance(inc[0], int): #attempt to create a component list from the given integers. warning: this will only exclude from a single object.
-#           obj = pm.ls(frm, objectsOnly=1)
-#           if len(obj)>1:
-#               return frm
-#           component_type = cls.get_component_type(frm[0])
-#           typ = cls.convert_alias(component_type) #get the correct component_type variable from possible args.
-#           inc = ["{}.{}[{}]".format(obj[0], typ, n) for n in inc]
-
-#       inc = misc_utils.Misc.convert_array_type(inc, returned_type=rtn, flatten=True) #assure both lists are of the same type for comparison.
-#       exc = misc_utils.Misc.convert_array_type(exc, returned_type=rtn, flatten=True)
-#       return [i for i in components if i not in exc and (inc and i in inc)]
+# deprecated ---------------------
```

### Comparing `mayatk-0.6.6/mayatk/project_utils.py` & `mayatk-0.6.7/mayatk/project_utils.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,19 +2,18 @@
 # coding=utf-8
 import os
 
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
+from pythontk import FileUtils
 
-from pythontk import File
 
-
-class Project:
+class ProjectUtils:
     """ """
 
     @staticmethod
     def get_recent_files(index=None, format="standard"):
         """
         Get a list of recent files.
 
@@ -39,34 +38,34 @@
             get_recent_files(format='standard|timestamp') --> Returns a dictionary with standard paths as keys and timestamped paths as values.
         """
         files = pm.optionVar(query="RecentFilesList")
         if not files:
             return []
 
         result = [
-            File.format_path(f)
+            FileUtils.format_path(f)
             for f in reversed(files)
-            if File.is_valid(f) and "Autosave" not in f
+            if FileUtils.is_valid(f) and "Autosave" not in f
         ]
 
         if index is not None:
             try:
                 result = result[index]
             except (IndexError, TypeError):
                 print(f"Incorrect index or slice. Returning empty list.")
                 return []
 
         format = format.split("|")
         if len(format) == 2 and "timestamp" in format and "standard" in format:
             if format[0] == "timestamp":
-                result = {File.time_stamp(res): res for res in result}
+                result = {FileUtils.time_stamp(res): res for res in result}
             else:
-                result = {res: File.time_stamp(res) for res in result}
+                result = {res: FileUtils.time_stamp(res) for res in result}
         elif "timestamp" in format:
-            result = [File.time_stamp(res) for res in result]
+            result = [FileUtils.time_stamp(res) for res in result]
         # else return the standard format
 
         return result
 
     @staticmethod
     def get_recent_projects(index=None, format="standard"):
         """
@@ -92,31 +91,33 @@
             get_recent_projects(format='timestamp') --> Returns all recent projects in timestamp format.
             get_recent_projects(format='standard|timestamp') --> Returns a dictionary with standard paths as keys and timestamped paths as values.
         """
         files = pm.optionVar(query="RecentProjectsList")
         if not files:
             return []
 
-        result = [File.format_path(f) for f in reversed(files) if File.is_valid(f)]
+        result = [
+            FileUtils.format_path(f) for f in reversed(files) if FileUtils.is_valid(f)
+        ]
 
         if index is not None:
             try:
                 result = result[index]
             except (IndexError, TypeError):
-                print(f"Incorrect index or slice. Returning empty list.")
+                print("Incorrect index or slice. Returning empty list.")
                 return []
 
         format = format.split("|")
         if len(format) == 2 and "timestamp" in format and "standard" in format:
             if format[0] == "timestamp":
-                result = {File.time_stamp(res): res for res in result}
+                result = {FileUtils.time_stamp(res): res for res in result}
             else:
-                result = {res: File.time_stamp(res) for res in result}
+                result = {res: FileUtils.time_stamp(res) for res in result}
         elif "timestamp" in format:
-            result = [File.time_stamp(res) for res in result]
+            result = [FileUtils.time_stamp(res) for res in result]
         # else return the standard format
 
         return result
 
     @staticmethod
     def get_recent_autosave(index=None, format="standard"):
         """
@@ -158,31 +159,31 @@
 
         files = itertools.chain(
             glob.iglob(os.path.join(autosave_dir, "*.mb")),
             glob.iglob(os.path.join(autosave_dir, "*.ma")),
         )
 
         for file in files:
-            result.append(File.format_path(file))
+            result.append(FileUtils.format_path(file))
 
         if index is not None:
             try:
                 result = result[index]
             except (IndexError, TypeError):
-                print(f"Incorrect index or slice. Returning empty list.")
+                print("Incorrect index or slice. Returning empty list.")
                 return []
 
         format = format.split("|")
         if len(format) == 2 and "timestamp" in format and "standard" in format:
             if format[0] == "timestamp":
-                result = {File.time_stamp(res): res for res in result}
+                result = {FileUtils.time_stamp(res): res for res in result}
             else:
-                result = {res: File.time_stamp(res) for res in result}
+                result = {res: FileUtils.time_stamp(res) for res in result}
         elif "timestamp" in format:
-            result = [File.time_stamp(res) for res in result]
+            result = [FileUtils.time_stamp(res) for res in result]
         # else return the standard format
 
         return result
 
     @staticmethod
     def get_workspace_scenes(fullPath=True):
         """Get a list of maya scene files from the current workspace directory.
@@ -191,19 +192,19 @@
             fullPath (bool): Return the full path instead of just the filename.
 
         Returns:
             (list)
         """
         workspace_dir = str(pm.workspace(q=True, rd=1))  # get current project path.
 
-        files = File.get_dir_contents(
+        files = FileUtils.get_dir_contents(
             workspace_dir, "filepaths", inc_files=("*.mb", "*.ma")
         )
         # Replace any backslashes with forward slashes.
-        result = [File.format_path(f) for f in files]
+        result = [FileUtils.format_path(f) for f in files]
 
         if not fullPath:
             result = [f.split("\\")[-1] for f in result]
 
         return result
 
     @staticmethod
@@ -264,28 +265,25 @@
 
         Returns:
             (list): A list of all references in the current Maya scene.
         """
         return [ref.filePath() for ref in pm.system.listReferences()]
 
 
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
 
-# --------------------------------------------------------------------------------------------
-# deprecated:
-# --------------------------------------------------------------------------------------------
 
+# deprecated ---------------------
 # @staticmethod
 # def reference_scene(scene, remove=False, lockReference=False):
 #     """Create a reference to a Maya scene.
 
 #     Parameters:
 #         remove (bool): Remove a previously referenced scene.
 #     """
@@ -318,17 +316,17 @@
 #     """
 # dir1 = str(pm.workspace(q=True, rd=1)) + "autosave"  # current project path.
 # # get autosave dir path from env variable.
 # dir2 = os.environ.get("MAYA_AUTOSAVE_FOLDER")
 # if dir2 is not None:  # Check if the environment variable exists
 #     dir2 = dir2.split(";")[0]
 
-#     result = File.get_dir_contents(dir1, "filepaths", inc_files=("*.mb", "*.ma"))
+#     result = FileUtils.get_dir_contents(dir1, "filepaths", inc_files=("*.mb", "*.ma"))
 #     if dir2 is not None:  # Add the files from the second directory if it exists
-#         result += File.get_dir_contents(dir2, "filepaths", inc_files=("*.mb", "*.ma"))
+#         result += FileUtils.get_dir_contents(dir2, "filepaths", inc_files=("*.mb", "*.ma"))
 #     # # Replace any backslashes with forward slashes and reverse the list.
-#     # result = [File.format_path(f) for f in list(reversed(files))]
+#     # result = [FileUtils.format_path(f) for f in list(reversed(files))]
 
 #     if timestamp:  # attach modified timestamp
-#         result = File.time_stamp(result, sort=True)
+#         result = FileUtils.time_stamp(result, sort=True)
 
 #     return result
```

### Comparing `mayatk-0.6.6/mayatk/project_utils.py.bak` & `mayatk-0.6.7/mayatk/project_utils.py.bak`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk/rig_utils.py` & `mayatk-0.6.7/mayatk/rig_utils.py.bak`

 * *Files 0% similar despite different names*

```diff
@@ -217,15 +217,15 @@
                     obj = pm.listRelatives(obj, children=1, type="transform")[0]
             except IndexError as error:
                 return
 
             for attrs, state in attrs_and_state.items():
                 if state is None:
                     continue
-                for a in Iter.make_iterable(attrs):
+                for a in Iter.make_list(attrs):
                     pm.setAttr("{}.{}".format(obj, a), lock=state)
 
     @staticmethod
     def create_group(
         objects=[],
         name="",
         zero_translation=False,
```

### Comparing `mayatk-0.6.6/mayatk/rig_utils.py.bak` & `mayatk-0.6.7/mayatk/rig_utils.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,34 +1,33 @@
 # !/usr/bin/python
 # coding=utf-8
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-
-from pythontk import Str, Iter
+import pythontk as ptk
 
 # from this package:
 from mayatk import node_utils
 
 
-class Rig(object):
+class RigUtils(object):
     """ """
 
     @staticmethod
     def create_locator(name=None, pos=(), scale=1):
         """Create a locator with the given scale.
 
         Parameters:
-                name (str): Name the locator.
-                pos (tuple): The desired location in world space.
-                scale (float) = The desired scale of the locator.
+            name (str): Name the locator.
+            pos (tuple): The desired location in world space.
+            scale (float) = The desired scale of the locator.
 
         Returns:
-                (obj) locator
+            (obj) locator
         """
         loc = pm.spaceLocator()
 
         if name:
             pm.rename(loc, name)
         if pos:
             pm.move(pos[0], pos[1], pos[2], loc)
@@ -38,55 +37,53 @@
         return loc
 
     @classmethod
     def remove_locator(cls, objects):
         """Remove a parented locator from the child object.
 
         Parameters:
-                obj (str/obj/list): The child object or the locator itself.
+            obj (str/obj/list): The child object or the locator itself.
         """
-        errorMsg = lambda: pm.inViewMessage(
-            status_message="{} in remove_locator\n\t# Error: Unable to remove locator for the given object. #".format(
-                __file__
-            ),
-            pos="topCenter",
-            fade=True,
-        )
-
         pm.undoInfo(openChunk=1)
 
         for obj in pm.ls(objects, long=True, objectsOnly=True):
             if not pm.objExists(obj):
                 continue
 
             elif (
-                node_utils.Node.is_locator(obj)
-                and not node_utils.Node.get_type(obj)
-                and not node_utils.Node.get_children(obj)
+                node_utils.NodeUtils.is_locator(obj)
+                and not node_utils.NodeUtils.get_type(obj)
+                and not node_utils.NodeUtils.get_children(obj)
             ):
                 pm.delete(obj)
                 continue
 
             # unlock attributes
-            cls.set_attr_lock_state(
-                obj, translate=False, rotate=False, scale=False
-            )  # unlock all.
+            cls.set_attr_lock_state(obj, translate=False, rotate=False, scale=False)
 
-            if not node_utils.Node.is_locator(obj):
+            if not node_utils.NodeUtils.is_locator(obj):
                 try:  # if the 'obj' is not a locator, check if it's parent is.
-                    obj = node_utils.Node.get_parent(obj)
-                    if not node_utils.Node.is_locator(obj):
-                        errorMsg()
+                    obj = node_utils.NodeUtils.get_parent(obj)
+                    if not node_utils.NodeUtils.is_locator(obj):
+                        pm.inViewMessage(
+                            status_message="Error: Unable to remove locator for the given object.",
+                            pos="topCenter",
+                            fade=True,
+                        )
                         continue
-                except IndexError as error:
-                    errorMsg()
+                except IndexError:
+                    pm.inViewMessage(
+                        status_message="Error: Unable to remove locator for the given object.",
+                        pos="topCenter",
+                        fade=True,
+                    )
                     continue
 
             # unparent child object
-            children = node_utils.Node.get_children(obj)
+            children = node_utils.NodeUtils.get_children(obj)
             for child in children:
                 pm.parent(child, world=True)
 
             # remove locator
             pm.delete(obj)
 
         pm.undoInfo(closeChunk=1)
@@ -123,15 +120,15 @@
             customModeActive = pm.manipScaleContext("Scale", q=1, mode=1) == 6
         else:  # use the move tool orientation
             customOri = pm.manipMoveContext(
                 "Move", q=1, orientAxes=1
             )  # get custom orientation
             pivotModeActive = pm.manipMoveContext("Move", q=1, editPivotMode=1)
             customModeActive = pm.manipMoveContext("Move", q=1, mode=1) == 6
-            if not ctx in ("moveSuperContext", "manipMoveContext"):  # Move tool
+            if ctx not in ("moveSuperContext", "manipMoveContext"):  # Move tool
                 otherToolActive = 1  # some other tool
 
         if orientation and customModeActive:
             if not position:
                 pm.mel.error(
                     (pm.mel.uiRes("m_bakeCustomToolPivot.kWrongAxisOriToolError"))
                 )
@@ -188,18 +185,18 @@
     def set_attr_lock_state(
         cls, objects, translate=None, rotate=None, scale=None, **kwargs
     ):
         """Lock/Unlock any attribute for the given objects, by passing it into kwargs as <attr>=<value>.
         A 'True' value locks the attribute, 'False' unlocks, while 'None' leaves the state unchanged.
 
         Parameters:
-                objects (str/obj/list): The object(s) to lock/unlock attributes of.
-                translate (bool): Lock/Unlock all translate x,y,z values at once.
-                rotate (bool): Lock/Unlock all rotate x,y,z values at once.
-                scale (bool): Lock/Unlock all scale x,y,z values at once.
+            objects (str/obj/list): The object(s) to lock/unlock attributes of.
+            translate (bool): Lock/Unlock all translate x,y,z values at once.
+            rotate (bool): Lock/Unlock all rotate x,y,z values at once.
+            scale (bool): Lock/Unlock all scale x,y,z values at once.
         """
         objects = pm.ls(objects, transforms=1, long=True)
 
         attrs_and_state = {
             (
                 "tx",
                 "ty",
@@ -209,44 +206,44 @@
             ("sx", "sy", "sz"): scale,
         }
 
         attrs_and_state.update(kwargs)  # update the dict with any values from kwargs.
 
         for obj in objects:
             try:
-                if node_utils.Node.is_locator(obj):
+                if node_utils.NodeUtils.is_locator(obj):
                     obj = pm.listRelatives(obj, children=1, type="transform")[0]
-            except IndexError as error:
+            except IndexError:
                 return
 
             for attrs, state in attrs_and_state.items():
                 if state is None:
                     continue
-                for a in Iter.make_list(attrs):
+                for a in ptk.make_iterable(attrs):
                     pm.setAttr("{}.{}".format(obj, a), lock=state)
 
     @staticmethod
     def create_group(
         objects=[],
         name="",
         zero_translation=False,
         zero_rotation=False,
         zero_scale=False,
     ):
         """Create a group containing any given objects.
 
         Parameters:
-                objects (str/obj/list): The object(s) to group.
-                name (str): Name the group.
-                zero_translation (bool): Freeze translation before parenting.
-                zero_rotation (bool): Freeze rotation before parenting.
-                zero_scale (bool): Freeze scale before parenting.
+            objects (str/obj/list): The object(s) to group.
+            name (str): Name the group.
+            zero_translation (bool): Freeze translation before parenting.
+            zero_rotation (bool): Freeze rotation before parenting.
+            zero_scale (bool): Freeze scale before parenting.
 
         Returns:
-                (obj) the group.
+            (obj) the group.
         """
         grp = pm.group(empty=True, n=name)
         try:
             pm.parent(grp, objects)
         except Exception as error:
             print(
                 f"{__file__} in create_group\n\t# Error: Unable to parent object(s): {error} #"
@@ -266,21 +263,21 @@
         return grp
 
     @classmethod
     def create_group_with_first_obj_lra(cls, objects, name="", freeze_transforms=True):
         """Creates a group using the first object to define the local rotation axis.
 
         Parameters:
-                objects (str/obj/list): The objects to group. The first object will be used to define the groups LRA.
-                name (str): The group name.
-                freeze_transforms (bool): Freeze transforms on group child objects.
+            objects (str/obj/list): The objects to group. The first object will be used to define the groups LRA.
+            name (str): The group name.
+            freeze_transforms (bool): Freeze transforms on group child objects.
         """
         try:
             obj, *other = pm.ls(objects, transforms=1)
-        except IndexError as error:
+        except IndexError:
             print(
                 f"{__file__} in create_group_with_first_obj_lra\n\t# Error: Operation requires at least one object. #"
             )
             return None
 
         pm.undoInfo(openChunk=1)
         cls.bake_custom_pivot(
@@ -296,15 +293,15 @@
         objParent = pm.listRelatives(obj, parent=1)
         pm.parent(
             grp, objParent
         )  # parent the instance under the original objects parent.
 
         try:
             pm.parent(obj, grp)
-        except:  # root level objects
+        except Exception:  # root level objects
             pm.parent(grp, world=True)
             pm.parent(obj, grp)
 
         for o in other:  # parent any other objects to the new group.
             pm.parent(o, grp)
             if freeze_transforms:
                 pm.makeIdentity(o, apply=True)  # freeze transforms on child objects.
@@ -336,36 +333,37 @@
         lock_rotation=False,
         lock_scale=False,
     ):
         """Create locators with the same transforms as any selected object(s).
         If there are vertices selected it will create a locator at the center of the selected vertices bounding box.
 
         Parameters:
-                objects (str/obj/list): A list of objects, or an object name to create locators at.
-                parent (bool): Parent the object to the locator. (default=False)
-                freeze_transforms (bool): Freeze transforms on the locator. (default=True)
-                bake_child_pivot (bool): Bake pivot positions on the child object. (default=True)
-                grp_suffix (str): A string appended to the end of the created groups name. (default: '_GRP#')
-                loc_suffix (str): A string appended to the end of the created locators name. (default: '_LOC#')
-                obj_suffix (str): A string appended to the end of the existing objects name. (default: '_GEO#')
-                strip_digits (bool): Strip numeric characters from the string. If the resulting name is not unique, maya will append a trailing digit. (default=False)
-                strip_suffix (str): Strip any existing suffix. A suffix is defined by the last '_' (if one exists) and any chars trailing. (default=False)
-                scale (float) = The scale of the locator. (default=1)
-                lock_translate (bool): Lock the translate values of the child object. (default=False)
-                lock_rotation (bool): Lock the rotation values of the child object. (default=False)
-                lock_scale (bool): Lock the scale values of the child object. (default=False)
-                remove (bool): Removes the locator and any child locks. (not valid with component selections) (default=False)
+            objects (str/obj/list): A list of objects, or an object name to create locators at.
+            parent (bool): Parent the object to the locator. (default=False)
+            freeze_transforms (bool): Freeze transforms on the locator. (default=True)
+            bake_child_pivot (bool): Bake pivot positions on the child object. (default=True)
+            grp_suffix (str): A string appended to the end of the created groups name. (default: '_GRP#')
+            loc_suffix (str): A string appended to the end of the created locators name. (default: '_LOC#')
+            obj_suffix (str): A string appended to the end of the existing objects name. (default: '_GEO#')
+            strip_digits (bool): Strip numeric characters from the string. If the resulting name is not unique, maya will append a trailing digit. (default=False)
+            strip_suffix (str): Strip any existing suffix. A suffix is defined by the last '_' (if one exists) and any chars trailing. (default=False)
+            scale (float) = The scale of the locator. (default=1)
+            lock_translate (bool): Lock the translate values of the child object. (default=False)
+            lock_rotation (bool): Lock the rotation values of the child object. (default=False)
+            lock_scale (bool): Lock the scale values of the child object. (default=False)
+            remove (bool): Removes the locator and any child locks. (not valid with component selections) (default=False)
 
-        Example: createLocatorAtSelection(strip='_GEO', suffix='', strip_digits=True, parent=True, lock_translate=True, lock_rotation=True)
+        Example:
+            createLocatorAtSelection(strip='_GEO', suffix='', strip_digits=True, parent=True, lock_translate=True, lock_rotation=True)
         """
         getSuffix = (
             lambda o: loc_suffix
-            if node_utils.Node.is_locator(o)
+            if node_utils.NodeUtils.is_locator(o)
             else grp_suffix
-            if node_utils.Node.is_group(o)
+            if node_utils.NodeUtils.is_group(o)
             else obj_suffix
         )  # match the correct suffix to the object type.
 
         pm.undoInfo(openChunk=1)
 
         for obj in pm.ls(objects, long=True, type="transform"):
             if bake_child_pivot:
@@ -394,15 +392,15 @@
             try:
                 if parent:
                     origParent = pm.listRelatives(obj, parent=1)
 
                     grp = cls.create_group(obj, zero_translation=1, zero_rotation=1)
                     pm.rename(
                         grp,
-                        Str.format_suffix(
+                        ptk.format_suffix(
                             obj.name(),
                             suffix=getSuffix(grp),
                             strip=(obj_suffix, grp_suffix, loc_suffix),
                             strip_trailing_ints=strip_digits,
                             strip_trailing_alpha=strip_suffix,
                         ),
                     )
@@ -418,25 +416,25 @@
                     pm.makeIdentity(obj, apply=True, normal=1)
                     pm.makeIdentity(
                         loc, apply=True, normal=1
                     )  # 1=the normals on polygonal objects will be frozen. 2=the normals on polygonal objects will be frozen only if its a non-rigid transformation matrix.
 
                 pm.rename(
                     loc,
-                    Str.format_suffix(
+                    ptk.format_suffix(
                         obj.name(),
                         suffix=getSuffix(loc),
                         strip=(obj_suffix, grp_suffix, loc_suffix),
                         strip_trailing_ints=strip_digits,
                         strip_trailing_alpha=strip_suffix,
                     ),
                 )
                 pm.rename(
                     obj,
-                    Str.format_suffix(
+                    ptk.format_suffix(
                         obj.name(),
                         suffix=getSuffix(obj),
                         strip=(obj_suffix, grp_suffix, loc_suffix),
                         strip_trailing_ints=strip_digits,
                         strip_trailing_alpha=strip_suffix,
                     ),
                 )
@@ -451,20 +449,20 @@
             except Exception as error:
                 pm.delete(loc)
                 raise (error)
 
         pm.undoInfo(closeChunk=1)
 
 
-# --------------------------------------------------------------------------------------------
+# -----------------------------------------------------------------------------
 
 if __name__ == "__main__":
     sel = pm.ls(sl=1)
 
-    Rigtk.create_locator_at_object(
+    RigUtils.create_locator_at_object(
         sel,
         parent=1,
         freeze_transforms=1,
         bake_child_pivot=1,
         grp_suffix="_GRP",
         loc_suffix="_LCTR",
         obj_suffix="_GEO",
@@ -472,67 +470,16 @@
         strip_suffix=1,
         scale=1,
         lock_translate=0,
         lock_rotation=0,
         lock_scale=0,
     )
 
-# --------------------------------------------------------------------------------------------
-# Notes
-# --------------------------------------------------------------------------------------------
+if __name__ == "__main__":
+    pass
 
+# -----------------------------------------------------------------------------
+# Notes
+# -----------------------------------------------------------------------------
 
-# --------------------------------------------------------------------------------------------
-# deprecated:
-# --------------------------------------------------------------------------------------------
-
-
-# the following was replaced with chatgpt code that fixed a: RuntimeError: Can't ungroup leaf-level transforms, but is not tested aside from a few unit test cases.
-# def remove_locator(cls, objects):
-#       '''Remove a parented locator from the child object.
-
-#       Parameters:
-#           obj (str/obj/list): The child object or the locator itself.
-#       '''
-#       errorMsg = lambda: pm.inViewMessage(
-#           status_message="{} in remove_locator\n\t# Error: Unable to remove locator for the given object. #".format(__file__),
-#           pos='topCenter',
-#           fade=True
-#       )
-
-#       pm.undoInfo(openChunk=1)
-
-#       for obj in pm.ls(objects, long=True, objectsOnly=True):
-#           if not pm.objExists(obj):
-#               continue
-
-#           elif node_utils.Node.is_locator(obj) and not node_utils.Node.get_type(obj) and not node_utils.Node.get_children(obj):
-#               pm.delete(obj)
-#               continue
-
-#           #unlock attributes
-#           cls.set_attr_lock_state(obj, translate=False, rotate=False, scale=False) #unlock all.
-
-#           if not node_utils.Node.is_locator(obj):
-#               try: #if the 'obj' is not a locator, check if it's parent is.
-#                   obj = node_utils.Node.get_type(obj)
-#                   if not node_utils.Node.is_locator(obj):
-#                       errorMsg()
-#                       continue
-#               except IndexError as error:
-#                   errorMsg()
-#                   continue
-
-#           try: #remove from group
-#               grp = node_utils.Node.get_type(obj)
-#           except IndexError as error:
-#               errorMsg()
-#               continue
-#           if node_utils.Node.is_group(grp):
-#               if grp.split('_')[0]==obj.split('_')[0]:
-#                   pm.ungroup(grp)
-
-#           #remove locator
-#           pm.ungroup(obj)
-#           pm.delete(obj)
 
-#       pm.undoInfo(closeChunk=1)
+# deprecated ---------------------
```

### Comparing `mayatk-0.6.6/mayatk/script_utils.py` & `mayatk-0.6.7/mayatk/script_utils.py`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk/xform_utils.py` & `mayatk-0.6.7/mayatk/xform_utils.py.bak`

 * *Files 0% similar despite different names*

```diff
@@ -185,15 +185,15 @@
         Example: aim_object_at_point(['cube1', 'cube2'], (0, 15, 15))
         """
         if isinstance(target_pos, (tuple, set, list)):
             target = pm.createNode("transform", name="target_helper")
 
         pm.xform(target, translation=target_pos, absolute=True)
 
-        for obj in Iter.make_iterable(objects):
+        for obj in Iter.make_list(objects):
             const = pm.aimConstraint(
                 target, obj, aim=aim_vect, worldUpVector=up_vect, worldUpType="vector"
             )
 
         pm.delete(const, target)
 
     @classmethod
```

### Comparing `mayatk-0.6.6/mayatk/xform_utils.py.bak` & `mayatk-0.6.7/mayatk/xform_utils.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,31 +1,30 @@
 # !/usr/bin/python
 # coding=utf-8
 try:
     import pymel.core as pm
 except ImportError as error:
     print(__file__, error)
-
-from pythontk import Iter, Math, format_return
+import pythontk as ptk
 
 # from this package:
-from mayatk import misc_utils, cmpt_utils
+from mayatk import utils, cmpt_utils
 
 
-class Xform(object):
+class XformUtils:
     """ """
 
     @staticmethod
     def move_to(source, target, center=True):
         """Move an object(s) to the given target.
 
         Parameters:
-                source (str/obj/list): The objects to move.
-                target (str/obj): The object to move to.
-                center (bool): Move to target pivot pos, or the bounding box center of the target.
+            source (str/obj/list): The objects to move.
+            target (str/obj): The object to move to.
+            center (bool): Move to target pivot pos, or the bounding box center of the target.
         """
         if center:  # temporarily move the targets pivot to it's bounding box center.
             orig_target_piv = pm.xform(
                 target, q=1, worldSpace=1, rp=1
             )  # get target pivot position.
             pm.xform(target, centerPivots=1)  # center target pivot.
             target_pos = pm.xform(
@@ -38,30 +37,31 @@
             target_pos = pm.xform(
                 target, q=1, worldSpace=1, rp=1
             )  # get the pivot position.
 
         pm.xform(source, translation=target_pos, worldSpace=1, relative=1)
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def drop_to_grid(
         objects, align="Mid", origin=False, center_pivot=False, freeze_transforms=False
     ):
         """Align objects to Y origin on the grid using a helper plane.
 
         Parameters:
-                objects (str/obj/list): The objects to translate.
-                align (bool): Specify which point of the object's bounding box to align with the grid. (valid: 'Max','Mid'(default),'Min')
-                origin (bool): Move to world grid's center.
-                center_pivot (bool): Center the object's pivot.
-                freeze_transforms (bool): Reset the selected transform and all of its children down to the shape level.
+            objects (str/obj/list): The objects to translate.
+            align (bool): Specify which point of the object's bounding box to align with the grid. (valid: 'Max','Mid'(default),'Min')
+            origin (bool): Move to world grid's center.
+            center_pivot (bool): Center the object's pivot.
+            freeze_transforms (bool): Reset the selected transform and all of its children down to the shape level.
 
-        ex. drop_to_grid(obj, align='Min') #set the object onto the grid.
+        Example:
+            drop_to_grid(obj, align='Min') #set the object onto the grid.
         """
-        # pm.misc_utils.Misc.undoInfo(openChunk=1)
+        # pm.undoInfo(openChunk=1)
         for obj in pm.ls(objects, transforms=1):
             osPivot = pm.xform(
                 obj, q=True, rotatePivot=1, objectSpace=1
             )  # save the object space obj pivot.
             wsPivot = pm.xform(
                 obj, q=True, rotatePivot=1, worldSpace=1
             )  # save the world space obj pivot.
@@ -80,59 +80,59 @@
             if not center_pivot:
                 pm.xform(
                     obj, rotatePivot=osPivot, objectSpace=1
                 )  # return pivot to orig position.
 
             if freeze_transforms:
                 pm.makeIdentity(obj, apply=True)
-        # pm.misc_utils.Misc.undoInfo (closeChunk=1)
+        # pm.undoInfo (closeChunk=1)
 
     @classmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def reset_translation(cls, objects):
         """Reset the translation transformations on the given object(s).
 
         Parameters:
-                objects (str/obj/list): The object(s) to reset the translation values for.
+            objects (str/obj/list): The object(s) to reset the translation values for.
         """
-        # pm.misc_utils.Misc.undoInfo(openChunk=1)
+        # pm.undoInfo(openChunk=1)
         for obj in pm.ls(objects):
             pos = pm.objectCenter(obj)  # get the object's current position.
             cls.drop_to_grid(
                 obj, origin=1, center_pivot=1
             )  # move to origin and center pivot.
             pm.makeIdentity(obj, apply=1, t=1, r=0, s=0, n=0, pn=1)  # bake transforms
             pm.xform(
                 obj, translation=pos
             )  # move the object back to it's original position.
-        # pm.misc_utils.Misc.undoInfo(closeChunk=1)
+        # pm.undoInfo(closeChunk=1)
 
     @staticmethod
     def set_translation_to_pivot(node):
         """Set an object’s translation value from its pivot location.
 
         Parameters:
                 node (str/obj/list): An object, or it's name.
         """
-        x, y, z = pivot = pm.xform(node, query=True, worldSpace=True, rotatePivot=True)
+        x, y, z = pm.xform(node, query=True, worldSpace=True, rotatePivot=True)
         pm.xform(node, relative=True, translation=[-x, -y, -z])
         pm.makeIdentity(node, apply=True, translate=True)
         pm.xform(node, translation=[x, y, z])
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def align_pivot_to_selection(align_from=[], align_to=[], translate=True):
         """Align one objects pivot point to another using 3 point align.
 
         Parameters:
-                align_from (list): At minimum; 1 object, 1 Face, 2 Edges, or 3 Vertices.
-                align_to (list): The object to align with.
-                translate (bool): Move the object with it's pivot.
+            align_from (list): At minimum; 1 object, 1 Face, 2 Edges, or 3 Vertices.
+            align_to (list): The object to align with.
+            translate (bool): Move the object with it's pivot.
         """
-        # pm.misc_utils.Misc.undoInfo(openChunk=1)
+        # pm.undoInfo(openChunk=1)
         pos = pm.xform(align_to, q=1, translation=True, worldSpace=True)
         center_pos = [  # Get center by averaging of all x,y,z points.
             sum(pos[0::3]) / len(pos[0::3]),
             sum(pos[1::3]) / len(pos[1::3]),
             sum(pos[2::3]) / len(pos[2::3]),
         ]
 
@@ -165,58 +165,59 @@
                 worldSpace=True,
             )
 
             if translate:
                 pm.xform(obj, translation=center_pos, worldSpace=True)
 
             pm.delete(plane)
-        # pm.misc_utils.Misc.undoInfo(closeChunk=1)
+        # pm.undoInfo(closeChunk=1)
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def aim_object_at_point(objects, target_pos, aim_vect=(1, 0, 0), up_vect=(0, 1, 0)):
         """Aim the given object(s) at the given world space position.
 
-        :Paramters:
-                objects (str/obj/list): Transform node(s) of the objects to orient.
-                target_pos (obj)(tuple): A point as xyz, or one or more transform nodes at which to aim the other given 'objects'.
-                aim_vect (tuple): The vector in local coordinates that points at the target.
-                up_vect (tuple): The vector in local coordinates that aligns with the world up vector.
+        Paramters:
+            objects (str/obj/list): Transform node(s) of the objects to orient.
+            target_pos (obj)(tuple): A point as xyz, or one or more transform nodes at which to aim the other given 'objects'.
+            aim_vect (tuple): The vector in local coordinates that points at the target.
+            up_vect (tuple): The vector in local coordinates that aligns with the world up vector.
 
-        Example: aim_object_at_point(['cube1', 'cube2'], (0, 15, 15))
+        Example:
+            aim_object_at_point(['cube1', 'cube2'], (0, 15, 15))
         """
         if isinstance(target_pos, (tuple, set, list)):
             target = pm.createNode("transform", name="target_helper")
 
         pm.xform(target, translation=target_pos, absolute=True)
 
-        for obj in Iter.make_list(objects):
+        for obj in ptk.make_iterable(objects):
             const = pm.aimConstraint(
                 target, obj, aim=aim_vect, worldUpVector=up_vect, worldUpType="vector"
             )
 
         pm.delete(const, target)
 
     @classmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def rotate_axis(cls, objects, target_pos):
         """Aim the given object at the given world space position.
         All rotations in rotated channel, geometry is transformed so
         it does not appear to move during this transformation
 
         Parameters:
-                objects (str/obj/list): Transform node(s) of the objects to orient.
-                target_pos (obj)(tuple): A point as xyz, or one or more transform nodes at which to aim the other given 'objects'.
+            objects (str/obj/list): Transform node(s) of the objects to orient.
+            target_pos (obj)(tuple): A point as xyz, or one or more transform nodes at which to aim the other given 'objects'.
         """
         for obj in pm.ls(objects, objectsOnly=True):
             cls.aim_object_at_point(obj, target_pos)
 
             try:
                 c = obj.verts
-            except TypeError as error:
+            except TypeError:
                 c = obj.cp
 
             wim = pm.getAttr(obj.worldInverseMatrix)
             pm.xform(c, matrix=wim)
 
             pos = pm.xform(
                 obj, q=True, translation=True, absolute=True, worldSpace=True
@@ -224,19 +225,19 @@
             pm.xform(c, translation=pos, relative=True, worldSpace=True)
 
     @staticmethod
     def get_orientation(objects, returned_type="point"):
         """Get an objects orientation as a point or vector.
 
         Parameters:
-                objects (str/obj/list): The object(s) to get the orientation of.
-                returned_type (str): The desired returned value type. (valid: 'point'(default), 'vector')
+            objects (str/obj/list): The object(s) to get the orientation of.
+            returned_type (str): The desired returned value type. (valid: 'point'(default), 'vector')
 
         Returns:
-                (tuple)(list) If 'objects' given as a list, a list of tuples will be returned.
+            (tuple)(list) If 'objects' given as a list, a list of tuples will be returned.
         """
         result = []
         for obj in pm.ls(objects, objectsOnly=True):
             world_matrix = pm.xform(obj, q=True, matrix=True, worldSpace=True)
             rAxis = pm.getAttr(obj.rotateAxis)
             if any((rAxis[0], rAxis[1], rAxis[2])):
                 print(
@@ -252,28 +253,26 @@
                     MVector(world_matrix[8:11]),
                 )
 
             else:
                 ori = (world_matrix[0:3], world_matrix[4:7], world_matrix[8:11])
             result.append(ori)
 
-        return format_return(result, objects)
+        return ptk.format_return(result, objects)
 
     @staticmethod
     def get_dist_between_two_objects(a, b):
         """Get the magnatude of a vector using the center points of two given objects.
 
         Parameters:
-                a (obj)(str): Object, object name, or point (x,y,z).
-                b (obj)(str): Object, object name, or point (x,y,z).
+            a (obj)(str): Object, object name, or point (x,y,z).
+            b (obj)(str): Object, object name, or point (x,y,z).
 
         Returns:
-                (float)
-
-        # xmin, ymin, zmin, xmax, ymax, zmax = pm.exactWorldBoundingBox(startAndEndCurves)
+            (float)
         """
         x1, y1, z1 = pm.objectCenter(a)
         x2, y2, z2 = pm.objectCenter(b)
 
         from math import sqrt
 
         distance = sqrt(pow((x1 - x2), 2) + pow((y1 - y2), 2) + pow((z1 - z2), 2))
@@ -281,18 +280,18 @@
         return distance
 
     @staticmethod
     def get_center_point(objects):
         """Get the bounding box center point of any given object(s).
 
         Parameters:
-                objects (str)(obj(list): The objects or components to get the center of.
+            objects (str)(obj(list): The objects or components to get the center of.
 
         Returns:
-                (tuple) position as xyz float values.
+            (tuple) position as xyz float values.
         """
         objects = pm.ls(objects, flatten=True)
         pos = [
             i
             for sublist in [
                 pm.xform(s, q=1, translation=1, worldSpace=1, absolute=1)
                 for s in objects
@@ -307,25 +306,26 @@
         return center_pos
 
     @classmethod
     def get_bounding_box(cls, objects, value=""):
         """Get information of the given object(s) combined bounding box.
 
         Parameters:
-                objects (str/obj/list): The object(s) or component(s) to query.
-                        Multiple objects will be treated as a combined bounding box.
-                value (str): The type of value to return. Multiple types can be given
-                        separated by '|'. The order given determines the return order.
-                        valid (case insensitive): 'xmin', 'xmax', 'ymin', 'ymax', 'zmin', 'zmax', 'size',
-                        'x' or 'sizex', 'y' or 'sizey', 'z' or 'sizez', 'volume', 'center' or 'centroid'
-        Returns:
-                (float)(tuple) Dependant on args.
-
-        Example: get_bounding_box(sel, 'center|volume') #returns: [[171.9106216430664, 93.622802734375, -1308.4896240234375], 743.2855185396038]
-        Example: get_bounding_box(sel, 'sizeY') #returns: 144.71902465820312
+            objects (str/obj/list): The object(s) or component(s) to query.
+                    Multiple objects will be treated as a combined bounding box.
+            value (str): The type of value to return. Multiple types can be given
+                    separated by '|'. The order given determines the return order.
+                    valid (case insensitive): 'xmin', 'xmax', 'ymin', 'ymax', 'zmin', 'zmax', 'size',
+                    'x' or 'sizex', 'y' or 'sizey', 'z' or 'sizez', 'volume', 'center' or 'centroid'
+        Returns:
+            (float)(tuple) Dependant on args.
+
+        Example:
+            get_bounding_box(sel, 'center|volume') #returns: [[171.9106216430664, 93.622802734375, -1308.4896240234375], 743.2855185396038]
+            get_bounding_box(sel, 'sizeY') #returns: 144.71902465820312
         """
         if "|" in value:  # use recursion to construct the list using each value.
             return tuple(cls.get_bounding_box(objects, i) for i in value.split("|"))
 
         v = value.lower()
         xmin, ymin, zmin, xmax, ymax, zmax = pm.exactWorldBoundingBox(objects)
         if v == "xmin":
@@ -362,22 +362,22 @@
     @classmethod
     def sort_by_bounding_box_value(
         cls, objects, value="volume", descending=True, also_return_value=False
     ):
         """Sort the given objects by their bounding box value.
 
         Parameters:
-                objects (str/obj/list): The objects or components to sort.
-                value (str): See 'getBoundingBoxInfo' 'value' parameter.
-                                ex. 'xmin', 'xmax', 'sizex', 'volume', 'center' etc.
-                descending (bool): Sort the list from the largest value down.
-                also_return_value (bool): Instead of just the object; return a
-                                list of two element tuples as [(<value>, <obj>)].
+            objects (str/obj/list): The objects or components to sort.
+            value (str): See 'getBoundingBoxInfo' 'value' parameter.
+                            ex. 'xmin', 'xmax', 'sizex', 'volume', 'center' etc.
+            descending (bool): Sort the list from the largest value down.
+            also_return_value (bool): Instead of just the object; return a
+                            list of two element tuples as [(<value>, <obj>)].
         Returns:
-                (list)
+            (list)
         """
         valueAndObjs = []
         for obj in pm.ls(objects, flatten=False):
             v = cls.get_bounding_box(obj, value)
             valueAndObjs.append((v, obj))
 
         sorted_ = sorted(valueAndObjs, key=lambda x: int(x[0]), reverse=descending)
@@ -386,39 +386,39 @@
         return [obj for v, obj in sorted_]
 
     @staticmethod
     def match_scale(a, b, scale=True, average=False):
         """Scale each of the given objects to the combined bounding box of a second set of objects.
 
         Parameters:
-                a (str/obj/list): The object(s) to scale.
-                b (str/obj/list): The object(s) to get a bounding box size from.
-                scale (bool): Scale the objects. Else, just return the scale value.
-                average (bool): Average the result across all axes.
+            a (str/obj/list): The object(s) to scale.
+            b (str/obj/list): The object(s) to get a bounding box size from.
+            scale (bool): Scale the objects. Else, just return the scale value.
+            average (bool): Average the result across all axes.
 
         Returns:
-                (list) scale values as [x,y,z,x,y,z...]
+            (list) scale values as [x,y,z,x,y,z...]
         """
         to = pm.ls(a, flatten=True)
         frm = pm.ls(b, flatten=True)
 
         xmin, ymin, zmin, xmax, ymax, zmax = pm.exactWorldBoundingBox(frm)
-        ax, ay, az = aBoundBox = [xmax - xmin, ymax - ymin, zmax - zmin]
+        ax, ay, az = [xmax - xmin, ymax - ymin, zmax - zmin]
 
         result = []
         for obj in to:
             xmin, ymin, zmin, xmax, ymax, zmax = pm.exactWorldBoundingBox(obj)
-            bx, by, bz = bBoundBox = [xmax - xmin, ymax - ymin, zmax - zmin]
+            bx, by, bz = [xmax - xmin, ymax - ymin, zmax - zmin]
 
-            oldx, oldy, oldz = bScaleOld = pm.xform(obj, q=1, s=1, r=1)
+            oldx, oldy, oldz = pm.xform(obj, q=1, s=1, r=1)
 
             try:
-                diffx, diffy, diffz = boundDifference = [ax / bx, ay / by, az / bz]
-            except ZeroDivisionError as error:
-                diffx, diffy, diffz = boundDifference = [1, 1, 1]
+                diffx, diffy, diffz = [ax / bx, ay / by, az / bz]
+            except ZeroDivisionError:
+                diffx, diffy, diffz = [1, 1, 1]
 
             bScaleNew = [oldx * diffx, oldy * diffy, oldz * diffz]
 
             if average:
                 bScaleNew = [sum(bScaleNew) / len(bScaleNew) for _ in range(3)]
 
             if scale:
@@ -430,16 +430,16 @@
 
     @staticmethod
     def align_using_three_points(vertices):
         """Move and align the object defined by the first 3 points to the last 3 points.
 
         Parameters:
             vertices (list): The first 3 points must be on the same object (i.e. it is the
-                            object to be transformed). The second set of points define
-                            the position and plane to transform to.
+                    object to be transformed). The second set of points define
+                    the position and plane to transform to.
         """
         from maya import OpenMaya
 
         vertices = pm.ls(vertices, flatten=True)
         objectToMove = pm.ls(vertices[:3], objectsOnly=True)
 
         p0, p1, p2 = [
@@ -451,155 +451,158 @@
 
         # Translate
         pm.move(*(p3 - p0), objectToMove, r=True, ws=True)
 
         # First rotation
         axis1 = (p1 - p0).normal()
         axis2 = (p4 - p3).normal()
-        cross_product = axis1 ^ axis2
+        # cross_product = axis1 ^ axis2
         angle = axis1.angle(axis2)
         rotation = OpenMaya.MEulerRotation(0, 0, angle).asVector()
         pm.rotate(*rotation, objectToMove, p=p3, r=True, os=True)
 
         # Second rotation
         axis3 = (p2 - p0).normal()
         axis4 = (p5 - p3).normal()
-        cross_product = axis3 ^ axis4
+        # cross_product = axis3 ^ axis4
         angle = axis3.angle(axis4)
         rotation = OpenMaya.MEulerRotation(0, 0, angle).asVector()
         pm.rotate(*rotation, objectToMove, p=p4, r=True, os=True)
 
     @staticmethod
     def is_overlapping(a, b, tolerance=0.001):
         """Check if the vertices in a and b are overlapping within the given tolerance.
 
         Parameters:
-                a (str/obj): The first object to check. Object can be a component.
-                b (str/obj): The second object to check. Object can be a component.
-                tolerance (float) = The maximum search distance before a vertex is considered not overlapping.
+            a (str/obj): The first object to check. Object can be a component.
+            b (str/obj): The second object to check. Object can be a component.
+            tolerance (float) = The maximum search distance before a vertex is considered not overlapping.
 
         Returns:
-                (bool)
+            (bool)
         """
         vert_setA = pm.ls(pm.polyListComponentConversion(a, toVertex=1), flatten=1)
         vert_setB = pm.ls(pm.polyListComponentConversion(b, toVertex=1), flatten=1)
 
-        closestVerts = cmpt_utils.Cmpt.get_closest_verts(
+        closestVerts = cmpt_utils.CmptUtils.get_closest_verts(
             vert_setA, vert_setB, tolerance=tolerance
         )
 
         return True if vert_setA and len(closestVerts) == len(vert_setA) else False
 
     @staticmethod
     def get_vertex_positions(objects, worldSpace=True):
         """Get all vertex positions for the given objects.
 
         Parameters:
-                objects (str/obj/list): The polygon object(s).
-                worldSpace (bool): Sample in world or object space.
+            objects (str/obj/list): The polygon object(s).
+            worldSpace (bool): Sample in world or object space.
 
         Returns:
-                (list) Nested lists if multiple objects given.
+            (list) Nested lists if multiple objects given.
         """
         import maya.OpenMaya as om
 
         space = om.MSpace.kWorld if worldSpace else om.MSpace.kObject
 
         result = []
-        for mesh in misc_utils.Misc.mfn_mesh_generator(objects):
+        for mesh in utils.Utils.mfn_mesh_generator(objects):
             points = om.MPointArray()
             mesh.getPoints(points, space)
 
             result.append(
                 [
                     (points[i][0], points[i][1], points[i][2])
                     for i in range(points.length())
                 ]
             )
-        return format_return(result, objects)
+        return ptk.format_return(result, objects)
 
     @staticmethod
     def hash_points(points, precision=4):
         """Hash the given list of point values.
 
         Parameters:
-                points (list): A list of point values as tuples.
-                precision (int): determines the number of decimal places that are retained
-                        in the fixed-point representation. For example, with a value of 4, the
-                        fixed-point representation would retain 4 decimal place.
-
+            points (list): A list of point values as tuples.
+            precision (int): determines the number of decimal places that are retained
+                    in the fixed-point representation. For example, with a value of 4, the
+                    fixed-point representation would retain 4 decimal place.
         Returns:
-                (list) list(s) of hashed tuples.
+            (list) list(s) of hashed tuples.
         """
-        nested = Iter.nested_depth(points) > 1
+        nested = ptk.nested_depth(points) > 1
         sets = points if nested else [points]
 
+        def clamp(p):
+            return int(p * 10**precision)
+
         result = []
         for pset in sets:
-            clamp = lambda p: int(p * 10**precision)
-
             result.append([hash(tuple(map(clamp, i))) for i in pset])
-        return format_return(result, nested)
+        return ptk.format_return(result, nested)
 
     @classmethod
     def get_matching_verts(cls, a, b, world_space=False):
         """Find any vertices which point locations match between two given mesh.
 
         Parameters:
-                a (str/obj/list): The first polygon object.
-                a (str/obj/list): A second polygon object.
-                world_space (bool): Sample in world or object space.
+            a (str/obj/list): The first polygon object.
+            a (str/obj/list): A second polygon object.
+            world_space (bool): Sample in world or object space.
 
         Returns:
-                (list) nested tuples with int values representing matching vertex pairs.
+            (list) nested tuples with int values representing matching vertex pairs.
         """
         vert_pos_a, vert_pos_b = cls.get_vertex_positions([a, b], world_space)
         hash_a, hash_b = cls.hash_points([vert_pos_a, vert_pos_b])
 
         matching = set(hash_a).intersection(hash_b)
         return [
             i
             for h in matching
-            for i in zip(Iter.indices(hash_a, h), Iter.indices(hash_b, h))
+            for i in zip(ptk.indices(hash_a, h), ptk.indices(hash_b, h))
         ]
 
     @staticmethod
     def order_by_distance(objects, point=[0, 0, 0], reverse=False):
         """Order the given objects by their distance from the given point.
+
         Parameters:
-                objects (str)(int/list): The object(s) to order.
-                point (list): A three value float list x, y, z.
-                reverse (bool): Reverse the naming order. (Farthest object first)
+            objects (str)(int/list): The object(s) to order.
+            point (list): A three value float list x, y, z.
+            reverse (bool): Reverse the naming order. (Farthest object first)
+
         Returns:
-                (list) ordered objects
+            (list) ordered objects
         """
         distance = {}
         for obj in pm.ls(objects, flatten=1):
             xmin, ymin, zmin, xmax, ymax, zmax = pm.xform(obj, q=1, boundingBox=1)
             bb_pos = ((xmin + xmax) / 2, (ymin + ymax) / 2, (zmin + zmax) / 2)
-            bb_dist = Math.get_distance(point, bb_pos)
+            bb_dist = ptk.get_distance(point, bb_pos)
 
             distance[bb_dist] = obj
 
         result = [distance[i] for i in sorted(distance)]
         return list(reversed(result)) if reverse else result
 
     @staticmethod
-    @misc_utils.Misc.undo
+    @utils.Utils.undo
     def align_vertices(mode, average=False, edgeloop=False):
         """Align vertices.
 
         Parameters:
-                mode (int): possible values are align: 0-YZ, 1-XZ, 2-XY, 3-X, 4-Y, 5-Z, 6-XYZ
-                average (bool): align to average of all selected vertices. else, align to last selected
-                edgeloop (bool): align vertices in edgeloop from a selected edge
+            mode (int): possible values are align: 0-YZ, 1-XZ, 2-XY, 3-X, 4-Y, 5-Z, 6-XYZ
+            average (bool): align to average of all selected vertices. else, align to last selected
+            edgeloop (bool): align vertices in edgeloop from a selected edge
 
-        Example: align_vertices(mode=3, average=True, edgeloop=True)
+        Example:
+            align_vertices(mode=3, average=True, edgeloop=True)
         """
-        # pm.misc_utils.Misc.undoInfo (openChunk=True)
+        # pm.undoInfo (openChunk=True)
         selectTypeEdge = pm.selectType(query=True, edge=True)
 
         if edgeloop:
             pm.mel.SelectEdgeLoopSp()  # select edgeloop
 
         pm.mel.PolySelectConvert(3)  # convert to vertices
 
@@ -617,16 +620,16 @@
             z = xyz[2::3]
             alignX = float(sum(x)) / (len(xyz) / 3)
             alignY = float(sum(y)) / (len(xyz) / 3)
             alignZ = float(sum(z)) / (len(xyz) / 3)
 
         if len(selection) < 2:
             if len(selection) == 0:
-                misc_utils.Misc.viewport_message("No vertices selected")
-            misc_utils.Misc.viewport_message("Selection must contain at least two vertices")
+                utils.Utils.viewport_message("No vertices selected")
+            utils.Utils.viewport_message("Selection must contain at least two vertices")
 
         for vertex in selection:
             vertexXYZ = pm.xform(vertex, q=True, translation=1, worldSpace=1)
             vertX = vertexXYZ[0]
             vertY = vertexXYZ[1]
             vertZ = vertexXYZ[2]
 
@@ -640,34 +643,28 @@
                 6: (alignX, alignY, alignZ),  # align XYZ
             }
 
             pm.xform(vertex, translation=modes[mode], worldSpace=1)
 
         if selectTypeEdge:
             pm.selectType(edge=True)
-        # pm.misc_utils.Misc.undoInfo (closeChunk=True)
+        # pm.undoInfo (closeChunk=True)
 
 
-# --------------------------------------------------------------------------------------------
-
-
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
 
-# --------------------------------------------------------------------------------------------
-# deprecated:
-# --------------------------------------------------------------------------------------------
 
+# deprecated ---------------------
 
 # @staticmethod
 # def snap3PointsTo3Points(vertices):
 #     """Move and align the object defined by the first 3 points to the last 3 points.
 
 #     Parameters:
 #             vertices (list): The first 3 points must be on the same object (i.e. it is the
@@ -703,21 +700,21 @@
 #         p1[0] - p0[0],
 #         p1[1] - p0[1],
 #         p1[2] - p0[2],
 #     ]
 #     a2x, a2y, a2z = axis2 = [p4[0] - p3[0], p4[1] - p3[1], p4[2] - p3[2]]
 
 #     # get the angle (in radians) between the two vectors and the axis of rotation. This is used to move axis1 to match axis2
-#     dp = Math.dot_product(axis1, axis2, 1)
-#     dp = Math.clamp(-1.0, 1.0, dp)
+#     dp = ptk.dot_product(axis1, axis2, 1)
+#     dp = ptk.clamp(-1.0, 1.0, dp)
 #     angle = math.acos(dp)
-#     cross_product = Math.cross_product(axis1, axis2, 1, 1)
+#     cross_product = ptk.cross_product(axis1, axis2, 1, 1)
 
 #     # rotate the first object about the pivot point (the pivot is defined by the first point from the second pair of points. i.e. point 3 from the inputs above)
-#     rotation = Math.xyz_rotation(angle, cross_product)
+#     rotation = ptk.xyz_rotation(angle, cross_product)
 #     pm.rotate(
 #         objectToMove,
 #         str(rotation[0]) + "rad",
 #         str(rotation[1]) + "rad",
 #         str(rotation[2]) + "rad",
 #         pivot=p3,
 #         relative=1,
@@ -726,40 +723,40 @@
 #     # Get these points again since they may have moved
 #     p2 = pm.pointPosition(vertices[2])
 #     p5 = pm.pointPosition(vertices[5])
 
 #     axis3 = [p2[0] - p4[0], p2[1] - p4[1], p2[2] - p4[2]]
 #     axis4 = [p5[0] - p4[0], p5[1] - p4[1], p5[2] - p4[2]]
 
-#     axis2 = Math.normalize(axis2)
+#     axis2 = ptk.normalize(axis2)
 
 #     # Get the dot product of axis3 on axis2
-#     dp = Math.dot_product(axis3, axis2, 0)
+#     dp = ptk.dot_product(axis3, axis2, 0)
 #     axis3[0] = p2[0] - p4[0] + dp * axis2[0]
 #     axis3[1] = p2[1] - p4[1] + dp * axis2[1]
 #     axis3[2] = p2[2] - p4[2] + dp * axis2[2]
 
 #     # Get the dot product of axis4 on axis2
-#     dp = Math.dot_product(axis4, axis2, 0)
+#     dp = ptk.dot_product(axis4, axis2, 0)
 #     axis4[0] = p5[0] - p4[0] + dp * axis2[0]
 #     axis4[1] = p5[1] - p4[1] + dp * axis2[1]
 #     axis4[2] = p5[2] - p4[2] + dp * axis2[2]
 
 #     # rotate the first object again, this time about the 2nd axis so that the 3rd point is in the same plane. ie. match up axis3 with axis4.
-#     dp = Math.dot_product(axis3, axis4, 1)
-#     dp = Math.clamp(-1.0, 1.0, dp)
+#     dp = ptk.dot_product(axis3, axis4, 1)
+#     dp = ptk.clamp(-1.0, 1.0, dp)
 #     angle = math.acos(dp)
 
 #     # reverse the angle if the cross product is in the -ve axis direction
-#     cross_product = Math.cross_product(axis3, axis4, 1, 1)
-#     dp = Math.dot_product(cross_product, axis2, 0)
+#     cross_product = ptk.cross_product(axis3, axis4, 1, 1)
+#     dp = ptk.dot_product(cross_product, axis2, 0)
 #     if dp < 0:
 #         angle = -angle
 
-#     rotation = Math.xyz_rotation(angle, axis2)
+#     rotation = ptk.xyz_rotation(angle, axis2)
 #     pm.rotate(
 #         objectToMove,
 #         str(rotation[0]) + "rad",
 #         str(rotation[1]) + "rad",
 #         str(rotation[2]) + "rad",
 #         pivot=p4,
 #         relative=1,
```

### Comparing `mayatk-0.6.6/mayatk.egg-info/PKG-INFO` & `mayatk-0.6.7/mayatk.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mayatk
-Version: 0.6.6
+Version: 0.6.7
 Summary: *mayattk is a collection of backend utilities for Autodesk Maya.*
 Home-page: https://github.com/m3trik/mayatk
 Author: Ryan Simpson
 Author-email: m3trik@outlook.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `mayatk-0.6.6/mayatk.egg-info/PKG-INFO.bak` & `mayatk-0.6.7/mayatk.egg-info/PKG-INFO.bak`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/mayatk.egg-info/SOURCES.txt` & `mayatk-0.6.7/mayatk.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -6,22 +6,22 @@
 mayatk/cam_utils.py.bak
 mayatk/cmpt_utils.py
 mayatk/cmpt_utils.py.bak
 mayatk/edit_utils.py
 mayatk/macro_utils.py
 mayatk/mash_utils.py
 mayatk/mash_utils.py.bak
-mayatk/misc_utils.py
 mayatk/misc_utils.py.bak
 mayatk/node_utils.py
 mayatk/project_utils.py
 mayatk/project_utils.py.bak
 mayatk/rig_utils.py
 mayatk/rig_utils.py.bak
 mayatk/script_utils.py
+mayatk/utils.py
 mayatk/xform_utils.py
 mayatk/xform_utils.py.bak
 mayatk.egg-info/PKG-INFO
 mayatk.egg-info/PKG-INFO.bak
 mayatk.egg-info/SOURCES.txt
 mayatk.egg-info/SOURCES.txt.bak
 mayatk.egg-info/dependency_links.txt
@@ -31,12 +31,12 @@
 mayatk/mat_utils/__init__.py
 mayatk/mat_utils/mat_utils.py
 mayatk/mat_utils/stingray_arnold_shader.py
 test/__init__.py
 test/cmpt_utils_test.py
 test/edit_utils_test.py
 test/mat_utils_test.py
-test/misc_utils_test.py
 test/node_utils_test.py
 test/rig_utils_test.py
 test/run_tests.py
+test/utils_test.py
 test/xform_utils_test.py
```

### Comparing `mayatk-0.6.6/mayatk.egg-info/SOURCES.txt.bak` & `mayatk-0.6.7/mayatk.egg-info/SOURCES.txt.bak`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/test/__init__.py` & `mayatk-0.6.7/test/__init__.py`

 * *Files identical despite different names*

### Comparing `mayatk-0.6.6/test/cmpt_utils_test.py` & `mayatk-0.6.7/test/cmpt_utils_test.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # !/usr/bin/python
 # coding=utf-8
 import os
 import unittest
 import inspect
 import maya.OpenMaya as om
 import pymel.core as pm
-from mayatk import Cmpt
+from mayatk import CmptUtils
 
 
 # sfr = pm.melGlobals['cmdScrollFieldReporter']
 # pm.cmdScrollFieldReporter(sfr, edit=1, clear=1)
 
 
 class Main(unittest.TestCase):
@@ -56,15 +56,15 @@
                 "<class 'str'> <PySide2.QtWidgets.QWidget(0x00000000000, name='MayaWindow') at 0x00000000000>"
         """
         import re
 
         return re.sub(r"0x[a-fA-F\d]+", "0x00000000000", str(obj))
 
 
-class Cmpt_test(Main, Cmpt):
+class CmptUtils_test(Main, CmptUtils):
     """
     set object mode:
             pm.selectMode(object=1)
 
     set component mode:
             pm.selectMode(component=1)
```

### Comparing `mayatk-0.6.6/test/edit_utils_test.py` & `mayatk-0.6.7/test/edit_utils_test.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 # !/usr/bin/python
 # coding=utf-8
-import os, sys
+import os
 import unittest
 import inspect
-
 import pymel.core as pm
-
-from mayatk import Edit
+from mayatk import EditUtils
 
 
 # sfr = pm.melGlobals['cmdScrollFieldReporter']
 # pm.cmdScrollFieldReporter(sfr, edit=1, clear=1)
 
 
 class Main(unittest.TestCase):
@@ -57,15 +55,15 @@
                 "<class 'str'> <PySide2.QtWidgets.QWidget(0x00000000000, name='MayaWindow') at 0x00000000000>"
         """
         import re
 
         return re.sub(r"0x[a-fA-F\d]+", "0x00000000000", str(obj))
 
 
-class Edit_test(Main, Edit):
+class EditUtils_test(Main, EditUtils):
     """ """
 
     # Tear down the any previous test by creating a new scene:
     pm.mel.file(new=True, force=True)
 
     # assemble the test scene:
     if not pm.objExists("cube1"):
```

### Comparing `mayatk-0.6.6/test/mat_utils_test.py` & `mayatk-0.6.7/test/mat_utils_test.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 import importlib
 import pymel.core as pm
 from mayatk.mat_utils import mat_utils
 
 importlib.reload(mat_utils)
 
 
-class MatTest(unittest.TestCase, mat_utils.Mat):
+class MatUtilsTest(unittest.TestCase, mat_utils.MatUtils):
     def test_get_mats(self):
         """Test the get_mats method."""
         # Create a sphere and assign a lambert material to it
         sphere = pm.polySphere()[0]
         lambert = pm.shadingNode("lambert", asShader=True)
         pm.select(sphere)
         pm.hyperShade(assign=lambert)
@@ -68,24 +68,24 @@
         # Create a sphere
         sphere = pm.polySphere()[0]
 
         # Create a lambert material
         lambert = pm.shadingNode("lambert", asShader=True)
 
         # Assign the lambert material to the sphere
-        mat_utils.Mat.assign_mat([sphere], lambert)
+        mat_utils.MatUtils.assign_mat([sphere], lambert)
 
         # Print the materials of the sphere after assignment
         print(
             "Materials after assignment:",
             pm.ls(pm.listConnections(sphere), materials=True),
         )
 
         # Get the materials of the sphere
-        mats = list(mat_utils.Mat.get_mats(sphere))
+        mats = list(mat_utils.MatUtils.get_mats(sphere))
 
         # Print the materials retrieved by get_mats
         print("Materials from get_mats:", mats)
 
         # Check that the lambert material is in the materials of the sphere
         self.assertIn(lambert, mats)
```

### Comparing `mayatk-0.6.6/test/misc_utils_test.py` & `mayatk-0.6.7/test/utils_test.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 # !/usr/bin/python
 # coding=utf-8
-import os, sys
+import os
 import unittest
 import inspect
-
 import pymel.core as pm
-
-from mayatk import Misc
+from mayatk import Utils
 
 
 # sfr = pm.melGlobals['cmdScrollFieldReporter']
 # pm.cmdScrollFieldReporter(sfr, edit=1, clear=1)
 
 
 class Main(unittest.TestCase):
@@ -57,15 +55,15 @@
                 "<class 'str'> <PySide2.QtWidgets.QWidget(0x00000000000, name='MayaWindow') at 0x00000000000>"
         """
         import re
 
         return re.sub(r"0x[a-fA-F\d]+", "0x00000000000", str(obj))
 
 
-class Core_test(Main, Misc):
+class Core_test(Main, Utils):
     """
     set object mode:
             pm.selectMode(object=1)
 
     set component mode:
             pm.selectMode(component=1)
 
@@ -77,15 +75,15 @@
             pm.selectType(facet=1)
             pm.selectType(polymeshUV=1)
             pm.selectType(meshUVShell=1)
     """
 
     # test imports:
     import mayatk as mtk
-    from mayatk import Cmpt
+    from mayatk import CmptUtils
     from mayatk import get_components
 
     # Tear down the any previous test by creating a new scene:
     pm.mel.file(new=True, force=True)
 
     # assemble the test scene:
     if not pm.objExists("cyl"):
@@ -96,18 +94,17 @@
             subdivisionsY=1,
             subdivisionsZ=1,
             name="cyl",
         )
 
     def test_undo(self):
         """ """
-        self.perform_test(
-            {
-                "self.replace_mem_address(self.undo())": "<function Misc.undo.<locals>.wrapper at 0x00000000000>",
-            }
+        self.assertEqual(
+            self.replace_mem_address(self.undo()),
+            "<function Utils.undo.<locals>.wrapper at 0x00000000000>",
         )
 
     def test_getMainWindow(self):
         """ """
         self.perform_test(
             {
                 "self.replace_mem_address(self.get_main_window())": '<PySide2.QtWidgets.QWidget(0x00000000000, name="MayaWindow") at 0x00000000000>'
@@ -121,36 +118,36 @@
             {
                 "str(next(self.mfn_mesh_generator('cyl'))).split(';')[0]": "<maya.OpenMaya.MFnMesh",
             }
         )
 
     def test_getArrayType(self):
         """ """
-        self.perform_test(
-            {
-                "self.get_array_type(100)": "int",
-                "self.get_array_type('cylShape.vtx[:]')": "str",
-                "self.get_array_type(pm.ls('cylShape.vtx[:]'))": "obj",
-            }
-        )
+        self.assertEqual(self.get_array_type(100), "int")
+        self.assertEqual(self.get_array_type("cylShape.vtx[:]"), "str")
+        self.assertEqual(self.get_array_type(pm.ls("cylShape.vtx[:]")), "vtx")
 
     def test_convertArrayType(self):
         """ """
         self.perform_test(
             {
                 "self.convert_array_type('cyl.vtx[:2]', 'str')": ["cylShape.vtx[0:2]"],
                 "self.convert_array_type('cyl.vtx[:2]', 'str', flatten=True)": [
                     "cylShape.vtx[0]",
                     "cylShape.vtx[1]",
                     "cylShape.vtx[2]",
                 ],
                 "str(self.convert_array_type('cyl.vtx[:2]', 'obj'))": "[MeshVertex('cylShape.vtx[0:2]')]",
                 "str(self.convert_array_type('cyl.vtx[:2]', 'obj', flatten=True))": "[MeshVertex('cylShape.vtx[0]'), MeshVertex('cylShape.vtx[1]'), MeshVertex('cylShape.vtx[2]')]",
                 "self.convert_array_type('cyl.vtx[:2]', 'int')": [0, 2],
-                "self.convert_array_type('cyl.vtx[:2]', 'int', flatten=True)": [0, 1, 2],
+                "self.convert_array_type('cyl.vtx[:2]', 'int', flatten=True)": [
+                    0,
+                    1,
+                    2,
+                ],
             }
         )
 
     def test_getParameterValuesMEL(self):
         """ """
         self.perform_test(
             {
@@ -239,33 +236,7 @@
 #   '''
 #   self.perform_test({
 #       # "self.": '',
 #   })
 # """
 
 # Deprecated ---------------------
-
-
-# ------------------------------------------------------------------------------------
-# this is the missing stuff when running python.exe compared with mayapy.exe
-
-# mayaver = 2022
-# pythonver = 37
-
-# mayapath = '%ProgramFiles%/Autodesk/Maya{}'.format(mayaver)
-
-# os.environ['MAYA_LOCATION'] = mayapath
-# os.environ['PYTHONHOME'] = mayapath+'/Python{}'.format(mayaver, pythonver)
-# os.environ['PATH'] = mayapath+'/bin;'.format(mayaver) + os.environ['PATH']
-
-# from pythontk import File
-# for d in [
-#   '{}/bin'.format(mayapath),
-#   '{}/bin3'.format(mayapath),
-#   '{}/Python{}'.format(mayapath, pythonver)
-#   ]:
-#   for dd in File.get_dir_contents(d, 'dirpaths', exc_dirs='Python27',  recursive=True):
-#       print (dd)
-#       sys.path.append(dd)
-
-# import maya.standalone
-# maya.standalone.initialize(name='python')
```

### Comparing `mayatk-0.6.6/test/node_utils_test.py` & `mayatk-0.6.7/test/node_utils_test.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 # !/usr/bin/python
 # coding=utf-8
-import os, sys
+import os
 import unittest
 import inspect
-
 import pymel.core as pm
-
-from mayatk import Node
+from mayatk import NodeUtils
 
 
 # sfr = pm.melGlobals['cmdScrollFieldReporter']
 # pm.cmdScrollFieldReporter(sfr, edit=1, clear=1)
 
 
 class Main(unittest.TestCase):
@@ -57,15 +55,15 @@
                 "<class 'str'> <PySide2.QtWidgets.QWidget(0x00000000000, name='MayaWindow') at 0x00000000000>"
         """
         import re
 
         return re.sub(r"0x[a-fA-F\d]+", "0x00000000000", str(obj))
 
 
-class Node_test(Main, Node):
+class NodeUtils_test(Main, NodeUtils):
     """
     set object mode:
             pm.selectMode(object=1)
 
     set component mode:
             pm.selectMode(component=1)
 
@@ -239,33 +237,7 @@
 #   '''
 #   self.perform_test({
 #       # "self.": '',
 #   })
 # """
 
 # Deprecated ---------------------
-
-
-# ------------------------------------------------------------------------------------
-# this is the missing stuff when running python.exe compared with mayapy.exe
-
-# mayaver = 2022
-# pythonver = 37
-
-# mayapath = '%ProgramFiles%/Autodesk/Maya{}'.format(mayaver)
-
-# os.environ['MAYA_LOCATION'] = mayapath
-# os.environ['PYTHONHOME'] = mayapath+'/Python{}'.format(mayaver, pythonver)
-# os.environ['PATH'] = mayapath+'/bin;'.format(mayaver) + os.environ['PATH']
-
-# from pythontk import File
-# for d in [
-#   '{}/bin'.format(mayapath),
-#   '{}/bin3'.format(mayapath),
-#   '{}/Python{}'.format(mayapath, pythonver)
-#   ]:
-#   for dd in File.get_dir_contents(d, 'dirpaths', exc_dirs='Python27',  recursive=True):
-#       print (dd)
-#       sys.path.append(dd)
-
-# import maya.standalone
-# maya.standalone.initialize(name='python')
```

### Comparing `mayatk-0.6.6/test/rig_utils_test.py` & `mayatk-0.6.7/test/rig_utils_test.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 # !/usr/bin/python
 # coding=utf-8
-import os, sys
+import os
 import unittest
 import inspect
-
 import pymel.core as pm
-
-from mayatk import Rig
+from mayatk import RigUtils
 
 
 # sfr = pm.melGlobals['cmdScrollFieldReporter']
 # pm.cmdScrollFieldReporter(sfr, edit=1, clear=1)
 
 
 class Main(unittest.TestCase):
@@ -57,15 +55,15 @@
                 "<class 'str'> <PySide2.QtWidgets.QWidget(0x00000000000, name='MayaWindow') at 0x00000000000>"
         """
         import re
 
         return re.sub(r"0x[a-fA-F\d]+", "0x00000000000", str(obj))
 
 
-class Rig_test(Main, Rig):
+class RigUtils_test(Main, RigUtils):
     """ """
 
     # Tear down the any previous test by creating a new scene:
     pm.mel.file(new=True, force=True)
 
     # assemble the test scene:
     if not pm.objExists("loc"):
```

### Comparing `mayatk-0.6.6/test/xform_utils_test.py` & `mayatk-0.6.7/test/xform_utils_test.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 # !/usr/bin/python
 # coding=utf-8
-import os, sys
+import os
 import unittest
 import inspect
-
 import pymel.core as pm
-
-from mayatk import Xform
+from mayatk import XformUtils
 
 
 # sfr = pm.melGlobals['cmdScrollFieldReporter']
 # pm.cmdScrollFieldReporter(sfr, edit=1, clear=1)
 
 
 class Main(unittest.TestCase):
@@ -57,15 +55,15 @@
                 "<class 'str'> <PySide2.QtWidgets.QWidget(0x00000000000, name='MayaWindow') at 0x00000000000>"
         """
         import re
 
         return re.sub(r"0x[a-fA-F\d]+", "0x00000000000", str(obj))
 
 
-class Xform_test(Main, Xform):
+class XformUtils_test(Main, XformUtils):
     """ """
 
     # Tear down the any previous test by creating a new scene:
     pm.mel.file(new=True, force=True)
 
     # assemble the test scene:
     if not pm.objExists("cube1"):
```


# Comparing `tmp/robothub_oak-1.3.1.tar.gz` & `tmp/robothub_oak-1.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "robothub_oak-1.3.1.tar", last modified: Wed Jun  7 00:26:23 2023, max compression
+gzip compressed data, was "robothub_oak-1.4.0.tar", last modified: Tue Jun 27 23:12:29 2023, max compression
```

## Comparing `robothub_oak-1.3.1.tar` & `robothub_oak-1.4.0.tar`

### file list

```diff
@@ -1,33 +1,39 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      585 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1291 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-07 00:26:23.417897 robothub_oak-1.3.1/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/src/robothub_oak/
--rw-r--r--   0 runner    (1001) docker     (123)      256 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/__init__.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2215 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/callbacks.py
--rw-r--r--   0 runner    (1001) docker     (123)     8611 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/commands.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/src/robothub_oak/components/
--rw-r--r--   0 runner    (1001) docker     (123)       74 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/components/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3123 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/components/camera.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/components/imu.py
--rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/components/neural_network.py
--rw-r--r--   0 runner    (1001) docker     (123)     4001 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/components/stereo.py
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/components/streamable.py
--rw-r--r--   0 runner    (1001) docker     (123)     8195 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/device.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    13469 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/hub_camera.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     8584 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/manager.py
--rw-r--r--   0 runner    (1001) docker     (123)     2310 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/packets.py
--rw-r--r--   0 runner    (1001) docker     (123)      548 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/src/robothub_oak/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/src/robothub_oak.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-06-07 00:26:23.000000 robothub_oak-1.3.1/src/robothub_oak.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      735 2023-06-07 00:26:23.000000 robothub_oak-1.3.1/src/robothub_oak.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-07 00:26:23.000000 robothub_oak-1.3.1/src/robothub_oak.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-07 00:26:23.000000 robothub_oak-1.3.1/src/robothub_oak.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-07 00:26:23.421897 robothub_oak-1.3.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/tests/test_callback.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/tests/test_hub_camera.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-07 00:25:56.000000 robothub_oak-1.3.1/tests/test_manager.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.337386 robothub_oak-1.4.0/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1064 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/LICENSE
+-rwxr-xr-x   0 runner    (1001) docker     (123)       39 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-06-27 23:12:29.337386 robothub_oak-1.4.0/PKG-INFO
+-rwxr-xr-x   0 runner    (1001) docker     (123)      585 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 23:12:29.337386 robothub_oak-1.4.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1291 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.321386 robothub_oak-1.4.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.329386 robothub_oak-1.4.0/src/robothub_oak/
+-rwxr-xr-x   0 runner    (1001) docker     (123)      256 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/__init__.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1972 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/callbacks.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    13996 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/commands.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.333386 robothub_oak-1.4.0/src/robothub_oak/components/
+-rwxr-xr-x   0 runner    (1001) docker     (123)       74 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/__init__.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1367 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/_component.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      410 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/_streamable.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5101 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/camera.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/imu.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3173 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/neural_network.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4460 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/components/stereo.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     8486 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/device.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    13748 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/hub_camera.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     8656 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/manager.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2465 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/packets.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.333386 robothub_oak-1.4.0/src/robothub_oak/trigger_action/
+-rwxr-xr-x   0 runner    (1001) docker     (123)       47 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/trigger_action/__init__.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      924 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/trigger_action/actions.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      952 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/trigger_action/triggers.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      142 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/types.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1232 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/src/robothub_oak/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.329386 robothub_oak-1.4.0/src/robothub_oak.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-06-27 23:12:29.000000 robothub_oak-1.4.0/src/robothub_oak.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-27 23:12:29.000000 robothub_oak-1.4.0/src/robothub_oak.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:12:29.000000 robothub_oak-1.4.0/src/robothub_oak.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-27 23:12:29.000000 robothub_oak-1.4.0/src/robothub_oak.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:12:29.337386 robothub_oak-1.4.0/tests/
+-rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/tests/test_callback.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/tests/test_hub_camera.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:11:54.000000 robothub_oak-1.4.0/tests/test_manager.py
```

### Comparing `robothub_oak-1.3.1/LICENSE` & `robothub_oak-1.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `robothub_oak-1.3.1/PKG-INFO` & `robothub_oak-1.4.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: robothub_oak
-Version: 1.3.1
+Version: 1.4.0
 Summary: RobotHub-OAK integration library
 Home-page: https://www.luxonis.com/
 Author: Luxonis
 Author-email: support@luxonis.com
 License: MIT
 Project-URL: Homepage, https://github.com/luxonis/robothub-oak/
 Project-URL: Documentation, https://hub-docs.luxonis.com/
```

### Comparing `robothub_oak-1.3.1/README.md` & `robothub_oak-1.4.0/README.md`

 * *Files identical despite different names*

### Comparing `robothub_oak-1.3.1/setup.py` & `robothub_oak-1.4.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 from setuptools import setup
 
 long_description = io.open('README.md', encoding='utf-8').read()
 
 setup(
     name='robothub_oak',
-    version='1.3.1',
+    version='1.4.0',
     description='RobotHub-OAK integration library',
     long_description=long_description,
     long_description_content_type='text/markdown',
     url='https://www.luxonis.com/',
     license='MIT',
     keywords='robothub robot hub connect agent depthai oak sdk',
     author='Luxonis',
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/callbacks.py` & `robothub_oak-1.4.0/src/robothub_oak/callbacks.py`

 * *Files 5% similar despite different names*

```diff
@@ -56,19 +56,12 @@
     """
     Default callback for NN streams.
 
     :param stream_handle: StreamHandle instance to publish the data to.
     :param packet: Packet instance containing the data.
     """
     visualizer = packet.visualizer
-    metadata = None
-    if visualizer:
-        metadata = json.loads(visualizer.serialize())
-        visualizer.reset()
-
-        # temp fix to replace None value that causes errors on frontend
-        if not metadata['config']['detection']['color']:
-            metadata['config']['detection']['color'] = [255, 0, 0]
+    metadata = json.loads(visualizer.serialize()) if visualizer else None
 
     timestamp = int(time.time() * 1_000)
     frame_bytes = bytes(packet.msg.getData())
     stream_handle.publish_video_data(frame_bytes, timestamp, metadata)
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/components/camera.py` & `robothub_oak-1.4.0/src/robothub_oak/components/neural_network.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,85 +1,87 @@
 from dataclasses import dataclass, replace
-from typing import Optional, Tuple, Union
+from typing import Union, Callable, Optional, List
 
 import depthai as dai
+import depthai_sdk
+import depthai_sdk.components
 
-from robothub_oak.components.streamable import Streamable
+from robothub_oak.components import Camera
+from robothub_oak.components._component import Component
+from robothub_oak.utils import _process_kwargs, _get_methods_by_class
+from robothub_oak.components._streamable import Streamable
 
-__all__ = ['Camera']
-
-from robothub_oak.utils import _process_kwargs
+__all__ = ['NeuralNetwork']
 
 
 @dataclass
-class CameraConfig:
-    """
-    Dataclass representing the configuration of the camera.
-    """
-    interleaved: Optional[bool] = None
-    color_order: Union[None, dai.ColorCameraProperties.ColorOrder, str] = None
-    manual_focus: Optional[int] = None
-    af_mode: Optional[dai.CameraControl.AutoFocusMode] = None
-    awb_mode: Optional[dai.CameraControl.AutoWhiteBalanceMode] = None
-    scene_mode: Optional[dai.CameraControl.SceneMode] = None
-    anti_banding_mode: Optional[dai.CameraControl.AntiBandingMode] = None
-    effect_mode: Optional[dai.CameraControl.EffectMode] = None
-    isp_scale: Optional[Tuple[int, int]] = None
-    sharpness: Optional[int] = None
-    luma_denoise: Optional[int] = None
-    chroma_denoise: Optional[int] = None
-
-
-class Camera(Streamable):
-    """
-    This component represents a single camera on the OAK, either color or mono one.
-    The API provides a way to configure the camera, but it is not required to do so.
-    """
+class NNConfig:
+    resize_mode: Optional[depthai_sdk.ResizeMode] = None
+    conf_threshold: Optional[float] = None
+
 
-    def __init__(self, name: str, resolution: Optional[str], fps: Optional[int]) -> None:
-        super().__init__()
+@dataclass
+class TrackerConfig:
+    tracker_type: Optional[dai.TrackerType] = None
+    track_labels: Optional[List[int]] = None
+    assignment_policy: Optional[dai.TrackerIdAssignmentPolicy] = None
+    max_obj: Optional[int] = None
+    threshold: Optional[float] = None
+    apply_tracking_filter: Optional[bool] = None
+    forget_after_n_frames: Optional[int] = None
+    calculate_speed: Optional[bool] = None
+
+
+class NeuralNetwork(Component, Streamable):
+    def __init__(self,
+                 name: str,
+                 input: Union[Camera, 'NeuralNetwork'],
+                 nn_type: Optional[str] = None,  # Either 'yolo' or 'mobilenet'
+                 decode_fn: Optional[Callable] = None,
+                 tracker: bool = False,
+                 spatial: Optional[bool] = None):
+        Component.__init__(self)
+        Streamable.__init__(self)
         self.name = name
-        self.resolution = resolution
-        self.fps = fps
+        self.input = input
+        self.nn_type = nn_type
+        self.decode_fn = decode_fn
+        self.tracker = tracker
+        self.spatial = spatial
 
-        self.camera_component = None  # type: depthai_sdk.components.CameraComponent
-        self.camera_config = CameraConfig()
+        self.nn_config = NNConfig()
+        self.tracker_config = TrackerConfig()
+
+        self.nn_component: Optional[depthai_sdk.components.NNComponent] = None
 
     def configure(self,
-                  interleaved: Optional[bool] = None,
-                  color_order: Union[None, dai.ColorCameraProperties.ColorOrder, str] = None,
-                  # Cam control
-                  manual_focus: Optional[int] = None,
-                  af_mode: Optional[dai.CameraControl.AutoFocusMode] = None,
-                  awb_mode: Optional[dai.CameraControl.AutoWhiteBalanceMode] = None,
-                  scene_mode: Optional[dai.CameraControl.SceneMode] = None,
-                  anti_banding_mode: Optional[dai.CameraControl.AntiBandingMode] = None,
-                  effect_mode: Optional[dai.CameraControl.EffectMode] = None,
-                  # IQ settings
-                  isp_scale: Optional[Tuple[int, int]] = None,
-                  sharpness: Optional[int] = None,
-                  luma_denoise: Optional[int] = None,
-                  chroma_denoise: Optional[int] = None,
+                  conf_threshold: Optional[float] = None,
+                  resize_mode: depthai_sdk.ResizeMode = None,
                   ) -> None:
-        """
-        Configures the camera component.
-        """
+        if conf_threshold is not None:
+            self.nn_config.conf_threshold = conf_threshold
+        if resize_mode is not None:
+            self.nn_config.resize_mode = resize_mode
+
+    def configure_tracker(self,
+                          tracker_type: Optional[dai.TrackerType] = None,
+                          track_labels: Optional[List[int]] = None,
+                          assignment_policy: Optional[dai.TrackerIdAssignmentPolicy] = None,
+                          max_obj: Optional[int] = None,
+                          threshold: Optional[float] = None,
+                          apply_tracking_filter: Optional[bool] = None,
+                          forget_after_n_frames: Optional[int] = None,
+                          calculate_speed: Optional[bool] = None
+                          ) -> None:
         kwargs = _process_kwargs(locals())
 
         if len(kwargs) > 0:
-            self.camera_config = replace(self.camera_config, **kwargs)
+            self.tracker_config = replace(self.tracker_config, **kwargs)
 
-    def set_resolution(self, resolution: str) -> None:
-        """
-        Sets the resolution of the camera.
+    def set_valid_output_types(self) -> None:
+        self._valid_output_types = _get_methods_by_class(depthai_sdk.components.NNComponent.Out)
 
-        :param resolution: String representation of the resolution, e.g. '1080p' or '4K'.
+    def _get_sdk_component(self):
         """
-        self.resolution = resolution
-
-    def set_fps(self, fps: int) -> None:
-        """
-        Sets the FPS of the camera.
-
-        :param fps: FPS to set as an integer.
+        Returns the DepthAI SDK NN component.
         """
-        self.fps = fps
+        return self.nn_component
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/components/stereo.py` & `robothub_oak-1.4.0/src/robothub_oak/components/stereo.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 from dataclasses import dataclass, replace
 from enum import IntEnum
 from typing import Union, Optional
 
 import depthai as dai
+import depthai_sdk.components
 
-from robothub_oak.components.streamable import Streamable
+from robothub_oak.components._component import Component
+from robothub_oak.components._streamable import Streamable
+from robothub_oak.utils import _process_kwargs, _get_methods_by_class
 
 __all__ = ['Stereo', 'DepthQuality', 'DepthRange']
 
-from robothub_oak.utils import _process_kwargs
-
 
 class DepthQuality(IntEnum):
     FAST = 1  # nothing turned on
     DEFAULT = 2  # lr check, median filter
     QUALITY = 3  # lr check, subpixel
 
 
@@ -36,37 +37,38 @@
     extended: Optional[bool] = None
     subpixel: Optional[bool] = None
     lr_check: Optional[bool] = None
     sigma: Optional[int] = None
     lr_check_threshold: Optional[int] = None
 
 
-class Stereo(Streamable):
+class Stereo(Component, Streamable):
     def __init__(self,
                  resolution: Optional[str],
                  fps: Optional[int],
                  left_camera: Optional['Camera'] = None,
                  right_camera: Optional['Camera'] = None):
         """
         This component represents the stereo module of the OAK device.
 
         :param resolution: Resolution of the disparity/depth map. Can be one of '400p', '480p', '720p', or '800p'.
         :param fps: FPS of the stereo output.
         :param left_camera: Left camera component.
         :param right_camera: Right camera component.
         """
-        super().__init__()
+        Component.__init__(self)
+        Streamable.__init__(self)
         self.resolution = resolution
         self.fps = fps
 
         self.left_camera = left_camera
         self.right_camera = right_camera
 
         self.stereo_config = StereoConfig()
-        self.stereo_component = None  # type: depthai_sdk.components.StereoComponent
+        self.stereo_component: Optional[depthai_sdk.components.StereoComponent] = None
 
     def configure(self,
                   depth_quality: Union[str, DepthQuality] = None,
                   depth_range: Union[str, DepthRange] = None,
                   align: 'Camera' = None,
                   confidence: Optional[int] = None,
                   median: Union[None, int, dai.MedianFilter] = None,
@@ -96,15 +98,26 @@
             depth_range = self._set_enum_value(DepthRange, depth_range)
 
         kwargs = _process_kwargs(locals())
 
         if len(kwargs) > 0:
             self.stereo_config = replace(self.stereo_config, **kwargs)
 
+    def set_valid_output_types(self) -> None:
+        self._valid_output_types = _get_methods_by_class(depthai_sdk.components.StereoComponent.Out)
+
+    def _get_sdk_component(self):
+        """
+        Returns the DepthAI SDK stereo component.
+        """
+        return self.stereo_component
+
     @staticmethod
     def _set_enum_value(enum, value):
         if isinstance(value, str):
             return enum[value.upper()]
         elif isinstance(value, enum):
             return value
         else:
             raise ValueError(f'Invalid value: {value}')
+
+
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/device.py` & `robothub_oak-1.4.0/src/robothub_oak/device.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,22 +1,23 @@
 import traceback
 import warnings
-from typing import Callable, Any, Optional, Dict
+from typing import Callable, Any, Optional, Dict, Union
 
 from depthai import NNData
 
 from robothub_oak.commands import (
     CreateStereoCommand, CreateCameraCommand, CreateNeuralNetworkCommand,
-    StreamCommand, CommandHistory
+    StreamCommand, CommandHistory, CreateTriggerActionCommand
 )
+from robothub_oak.components._streamable import Streamable
 from robothub_oak.components.camera import Camera
 from robothub_oak.components.neural_network import NeuralNetwork
 from robothub_oak.components.stereo import Stereo
-from robothub_oak.components.streamable import Streamable
 from robothub_oak.hub_camera import HubCamera
+from robothub_oak.trigger_action import Trigger, Action
 
 __all__ = ['Device']
 
 
 class Device:
     """
     Device represents a single device. It is used to create components and execute commands.
@@ -190,14 +191,18 @@
             return self.stereo
 
         self.stereo = Stereo(resolution, fps, left_camera, right_camera)
         command = CreateStereoCommand(self, self.stereo)
         self._command_history.push(command)
         return self.stereo
 
+    def add_trigger(self, trigger: Trigger, action: Union[Action, Callable]) -> None:
+        command = CreateTriggerActionCommand(self, trigger, action)
+        self._command_history.push(command)
+
     def set_connect_callback(self, callback: Callable[[HubCamera], None]) -> None:
         """
         Sets the callback to be called when the device connects.
 
         :param callback: The callback to be called when the device connects.
         """
         self.connect_callback = callback
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/hub_camera.py` & `robothub_oak-1.4.0/src/robothub_oak/hub_camera.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,22 @@
+import logging
 import logging as log
 import time
+import traceback
 import warnings
 from pathlib import Path
 from typing import Union, Optional, Callable, Dict, Any
 
 import depthai
 import depthai as dai
 import depthai_sdk
 import robothub
 from depthai_sdk import OakCamera
 from depthai_sdk.components import CameraComponent, StereoComponent, NNComponent
+from depthai_sdk.trigger_action import Trigger, Action
 
 import robothub_oak
 from robothub_oak.callbacks import get_default_color_callback, get_default_nn_callback, get_default_depth_callback
 from robothub_oak.utils import try_or_default
 
 __all__ = ['HubCamera']
 
@@ -105,14 +108,15 @@
 
         :return: Neural network component.
         """
         comp = self.oak_camera.create_nn(model=model, input=input, nn_type=nn_type,
                                          tracker=tracker, spatial=spatial, decode_fn=decode_fn)
         return comp
 
+
     def create_stereo(self,
                       resolution: Union[None, str, dai.MonoCameraProperties.SensorResolution] = None,
                       fps: Optional[float] = None,
                       left: Union[None, dai.Node.Output, depthai_sdk.components.CameraComponent] = None,
                       right: Union[None, dai.Node.Output, depthai_sdk.components.CameraComponent] = None,
                       ) -> StereoComponent:
         """
@@ -190,14 +194,17 @@
 
         :param output: Output to set the callback for.
         :param callback: Callback function to be called when a new frame is received.
         :param enable_visualizer: Whether to enable the visualizer that provides metadata.
         """
         self.oak_camera.callback(output, callback=callback, enable_visualizer=enable_visualizer)
 
+    def create_trigger(self, trigger: Trigger, action: Union[Action, Callable]):
+        self.oak_camera.trigger_action(trigger, action)
+
     def poll(self) -> Optional[int]:
         """
         Polls the device for new data.
         """
         return self.oak_camera.poll()
 
     def start(self) -> None:
@@ -209,14 +216,15 @@
 
         while not self.stop_event.is_set():
             try:
                 self.oak_camera.start()
                 self.state = robothub.DeviceState.CONNECTED
                 return
             except Exception as e:
+                logging.debug(traceback.print_exc())
                 warnings.warn(f'Camera: could not start with exception {e}.')
 
             self.stop_event.wait(1)
 
     def stop(self) -> None:
         """
         Stops the device and sets the state to disconnected.
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/manager.py` & `robothub_oak-1.4.0/src/robothub_oak/manager.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 import contextlib
 import logging
 import logging as log
 import os
+import time
 from collections import defaultdict
 from typing import Optional, List
 
 import robothub
 
 from robothub_oak.device import Device
 from robothub_oak.hub_camera import HubCamera
@@ -129,15 +130,15 @@
         """
         while not self.stop_event.is_set():
             for camera in self._hub_cameras:
                 if not camera.poll():
                     self._disconnect_camera(camera)
                     continue
 
-            self.stop_event.wait(self.POLL_FREQUENCY)
+            time.sleep(self.POLL_FREQUENCY)
 
     def _connect(self) -> None:
         """
         Reconnects the cameras that were disconnected or reconnected.
         """
         while not self.stop_event.is_set():
             if len(self._hub_cameras) == len(self._devices) or self.connecting_to_device:
@@ -151,15 +152,15 @@
                     self._connect_device(device)
                     self.connecting_to_device = False
 
     def _connect_device(self, device: 'Device') -> None:
         """
         Connect a device to the app.
         """
-        hub_camera = HubCamera(device_name=device.get_device_name())
+        hub_camera = HubCamera(device_name=device.ip_address or device.mxid)
         if not device._start(hub_camera):  # Initialize the device (create streams, etc.)
             hub_camera.stop()
             return
 
         hub_camera.start()  # Start the pipeline
 
         device.connect_callback(hub_camera)
@@ -207,15 +208,16 @@
 
         :param id: The ID of the device.
         :param name: The name of the device.
         :param mxid: The mxid of the device.
         :param ip_address: The IP address of the device.
         :return: The device.
         """
-        assert id or name or mxid or ip_address, 'Must specify at least one of id, name, mxid or ip_address'
+        if not (id or name or mxid or ip_address):
+            raise ValueError('At least one of the following parameters must be specified: id, name, mxid, ip_address.')
 
         device = Device(id=id, name=name, mxid=mxid, ip_address=ip_address)
 
         # Check if device already exists
         for d in DEVICE_MANAGER.devices:
             if d == device:
                 return d
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak/packets.py` & `robothub_oak-1.4.0/src/robothub_oak/packets.py`

 * *Files 15% similar despite different names*

```diff
@@ -13,22 +13,24 @@
 class HubPacket:
     """
     Base class for all packets. Represents a packet containing a frame.
     """
 
     def __init__(self, device: 'Device', packet):
         self.device = device
-        self._packet = packet
+        self.depthai_sdk_packet = packet
 
-        self.frame = self._packet.frame
+        self.frame = self.depthai_sdk_packet.frame
+        self.msg = self.depthai_sdk_packet.msg
+        self.visualizer = self.depthai_sdk_packet.visualizer
 
     def upload_as_event(self, title: str):
         try:
             # convert numpy array to jpg
-            frame_bytes = cv2.imencode('.jpg', self._packet.frame)[1].tobytes()
+            frame_bytes = cv2.imencode('.jpg', self.depthai_sdk_packet.frame)[1].tobytes()
             robothub.DETECTIONS.send_frame_detection(imagedata=frame_bytes, title=title, camera_serial=self.device.mxid)
         except Exception as e:
             warnings.warn(f'Could not upload detection with error: {e}')
 
 
 class DepthPacket(HubPacket):
     def __init__(self, device: 'Device', packet):
@@ -46,29 +48,29 @@
             self.nn_data = packet.nnData
         except AttributeError:
             self.nn_data = None
 
     def upload_as_detection(self, title: str):
         try:
             # convert numpy array to jpg
-            frame_bytes = cv2.imencode('.jpg', self._packet.frame)[1].tobytes()
+            frame_bytes = cv2.imencode('.jpg', self.depthai_sdk_packet.frame)[1].tobytes()
 
             # TODO add metadata
             robothub.DETECTIONS.send_frame_detection(imagedata=frame_bytes, title=title, camera_serial=self.device.mxid)
         except Exception as e:
             warnings.warn(f'Could not upload detection with error: {e}')
 
     def upload_as_event(self, title):
         raise NotImplementedError('Not implemented yet')
 
 
 class TrackerPacket(DetectionPacket):
     def __init__(self, device: 'Device', packet):
         super().__init__(device, packet)
-        self.tracklets = packet.tracklets
+        self.tracklets = packet.daiTracklets
 
     def upload_as_event(self, title):
         raise NotImplementedError('Not implemented yet')
 
 
 class IMUPacket:
     def __init__(self, device: 'Device', packet):
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak.egg-info/PKG-INFO` & `robothub_oak-1.4.0/src/robothub_oak.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: robothub-oak
-Version: 1.3.1
+Version: 1.4.0
 Summary: RobotHub-OAK integration library
 Home-page: https://www.luxonis.com/
 Author: Luxonis
 Author-email: support@luxonis.com
 License: MIT
 Project-URL: Homepage, https://github.com/luxonis/robothub-oak/
 Project-URL: Documentation, https://hub-docs.luxonis.com/
```

### Comparing `robothub_oak-1.3.1/src/robothub_oak.egg-info/SOURCES.txt` & `robothub_oak-1.4.0/src/robothub_oak.egg-info/SOURCES.txt`

 * *Files 10% similar despite different names*

```diff
@@ -5,21 +5,26 @@
 src/robothub_oak/__init__.py
 src/robothub_oak/callbacks.py
 src/robothub_oak/commands.py
 src/robothub_oak/device.py
 src/robothub_oak/hub_camera.py
 src/robothub_oak/manager.py
 src/robothub_oak/packets.py
+src/robothub_oak/types.py
 src/robothub_oak/utils.py
 src/robothub_oak.egg-info/PKG-INFO
 src/robothub_oak.egg-info/SOURCES.txt
 src/robothub_oak.egg-info/dependency_links.txt
 src/robothub_oak.egg-info/top_level.txt
 src/robothub_oak/components/__init__.py
+src/robothub_oak/components/_component.py
+src/robothub_oak/components/_streamable.py
 src/robothub_oak/components/camera.py
 src/robothub_oak/components/imu.py
 src/robothub_oak/components/neural_network.py
 src/robothub_oak/components/stereo.py
-src/robothub_oak/components/streamable.py
+src/robothub_oak/trigger_action/__init__.py
+src/robothub_oak/trigger_action/actions.py
+src/robothub_oak/trigger_action/triggers.py
 tests/test_callback.py
 tests/test_hub_camera.py
 tests/test_manager.py
```


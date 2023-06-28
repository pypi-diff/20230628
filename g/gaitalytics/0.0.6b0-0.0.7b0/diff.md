# Comparing `tmp/gaitalytics-0.0.6b0.tar.gz` & `tmp/gaitalytics-0.0.7b0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gaitalytics-0.0.6b0.tar", last modified: Wed Jun 21 09:00:05 2023, max compression
+gzip compressed data, was "gaitalytics-0.0.7b0.tar", last modified: Wed Jun 28 08:05:50 2023, max compression
```

## Comparing `gaitalytics-0.0.6b0.tar` & `gaitalytics-0.0.7b0.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxrwxrwx   0        0        0        0 2023-06-21 09:00:05.099303 gaitalytics-0.0.6b0/
--rw-rw-rw-   0        0        0     1096 2023-04-25 17:34:59.000000 gaitalytics-0.0.6b0/LICENSE
--rw-rw-rw-   0        0        0     1405 2023-06-21 09:00:05.100808 gaitalytics-0.0.6b0/PKG-INFO
--rw-rw-rw-   0        0        0      879 2023-06-21 04:53:15.000000 gaitalytics-0.0.6b0/README.md
--rw-rw-rw-   0        0        0       84 2023-06-21 07:51:06.000000 gaitalytics-0.0.6b0/pyproject.toml
--rw-rw-rw-   0        0        0      730 2023-06-21 09:00:05.101817 gaitalytics-0.0.6b0/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-21 09:00:05.072786 gaitalytics-0.0.6b0/src/
-drwxrwxrwx   0        0        0        0 2023-06-21 09:00:05.093387 gaitalytics-0.0.6b0/src/gaitalytics/
--rw-rw-rw-   0        0        0        0 2023-06-21 08:57:09.000000 gaitalytics-0.0.6b0/src/gaitalytics/__init__.py
--rw-rw-rw-   0        0        0    20363 2023-06-21 08:58:38.000000 gaitalytics-0.0.6b0/src/gaitalytics/analysis.py
--rw-rw-rw-   0        0        0    10891 2023-06-21 08:58:01.000000 gaitalytics-0.0.6b0/src/gaitalytics/api.py
--rw-rw-rw-   0        0        0     4160 2023-06-20 15:51:04.000000 gaitalytics-0.0.6b0/src/gaitalytics/c3d.py
--rw-rw-rw-   0        0        0    19669 2023-06-21 08:58:01.000000 gaitalytics-0.0.6b0/src/gaitalytics/cycle.py
--rw-rw-rw-   0        0        0     3340 2023-06-20 15:51:04.000000 gaitalytics-0.0.6b0/src/gaitalytics/emg.py
--rw-rw-rw-   0        0        0    15493 2023-06-21 08:58:01.000000 gaitalytics-0.0.6b0/src/gaitalytics/events.py
--rw-rw-rw-   0        0        0     9462 2023-06-21 08:58:01.000000 gaitalytics-0.0.6b0/src/gaitalytics/modelling.py
--rw-rw-rw-   0        0        0     6133 2023-06-21 08:58:01.000000 gaitalytics-0.0.6b0/src/gaitalytics/plot.py
--rw-rw-rw-   0        0        0     1558 2023-06-21 08:58:00.000000 gaitalytics-0.0.6b0/src/gaitalytics/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-21 09:00:05.099303 gaitalytics-0.0.6b0/src/gaitalytics.egg-info/
--rw-rw-rw-   0        0        0     1405 2023-06-21 09:00:05.000000 gaitalytics-0.0.6b0/src/gaitalytics.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      490 2023-06-21 09:00:05.000000 gaitalytics-0.0.6b0/src/gaitalytics.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-21 09:00:05.000000 gaitalytics-0.0.6b0/src/gaitalytics.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       37 2023-06-21 09:00:05.000000 gaitalytics-0.0.6b0/src/gaitalytics.egg-info/requires.txt
--rw-rw-rw-   0        0        0       12 2023-06-21 09:00:05.000000 gaitalytics-0.0.6b0/src/gaitalytics.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 08:05:50.086303 gaitalytics-0.0.7b0/
+-rw-rw-rw-   0        0        0     1096 2023-04-25 17:34:59.000000 gaitalytics-0.0.7b0/LICENSE
+-rw-rw-rw-   0        0        0     1405 2023-06-28 08:05:50.086303 gaitalytics-0.0.7b0/PKG-INFO
+-rw-rw-rw-   0        0        0      879 2023-06-21 04:53:15.000000 gaitalytics-0.0.7b0/README.md
+-rw-rw-rw-   0        0        0       84 2023-06-21 07:51:06.000000 gaitalytics-0.0.7b0/pyproject.toml
+-rw-rw-rw-   0        0        0      730 2023-06-28 08:05:50.086303 gaitalytics-0.0.7b0/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 08:05:50.054940 gaitalytics-0.0.7b0/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 08:05:50.071294 gaitalytics-0.0.7b0/src/gaitalytics/
+-rw-rw-rw-   0        0        0        0 2023-06-21 08:57:09.000000 gaitalytics-0.0.7b0/src/gaitalytics/__init__.py
+-rw-rw-rw-   0        0        0    22257 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/analysis.py
+-rw-rw-rw-   0        0        0    12224 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/api.py
+-rw-rw-rw-   0        0        0     3226 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/c3d.py
+-rw-rw-rw-   0        0        0    13086 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/cycle.py
+-rw-rw-rw-   0        0        0     3340 2023-06-20 15:51:04.000000 gaitalytics-0.0.7b0/src/gaitalytics/emg.py
+-rw-rw-rw-   0        0        0    15668 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/events.py
+-rw-rw-rw-   0        0        0    10289 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/modelling.py
+-rw-rw-rw-   0        0        0     6139 2023-06-28 07:52:44.000000 gaitalytics-0.0.7b0/src/gaitalytics/plot.py
+-rw-rw-rw-   0        0        0    14361 2023-06-28 08:00:17.000000 gaitalytics-0.0.7b0/src/gaitalytics/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:05:50.086303 gaitalytics-0.0.7b0/src/gaitalytics.egg-info/
+-rw-rw-rw-   0        0        0     1405 2023-06-28 08:05:50.000000 gaitalytics-0.0.7b0/src/gaitalytics.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      490 2023-06-28 08:05:50.000000 gaitalytics-0.0.7b0/src/gaitalytics.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:05:50.000000 gaitalytics-0.0.7b0/src/gaitalytics.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       37 2023-06-28 08:05:50.000000 gaitalytics-0.0.7b0/src/gaitalytics.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 08:05:50.000000 gaitalytics-0.0.7b0/src/gaitalytics.egg-info/top_level.txt
```

### Comparing `gaitalytics-0.0.6b0/LICENSE` & `gaitalytics-0.0.7b0/LICENSE`

 * *Files identical despite different names*

### Comparing `gaitalytics-0.0.6b0/PKG-INFO` & `gaitalytics-0.0.7b0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gaitalytics
-Version: 0.0.6b0
+Version: 0.0.7b0
 Summary: Library to analyse gait data captured with a mocap system
 Home-page: https://github.com/cereneo-foundation/gait_analysis
 Author: André Böni
 Author-email: andre.boeni@cereneo.foundation
 License: MIT
 Keywords: gait,analysis,c3d,mocap
 Classifier: Programming Language :: Python :: 3
```

### Comparing `gaitalytics-0.0.6b0/README.md` & `gaitalytics-0.0.7b0/README.md`

 * *Files identical despite different names*

### Comparing `gaitalytics-0.0.6b0/setup.cfg` & `gaitalytics-0.0.7b0/setup.cfg`

 * *Files 15% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2067 6169 7461 6c79 7469 6373 0d0a   = gaitalytics..
-00000020: 7665 7273 696f 6e20 3d20 302e 302e 3662  version = 0.0.6b
+00000020: 7665 7273 696f 6e20 3d20 302e 302e 3762  version = 0.0.7b
 00000030: 6574 610d 0a61 7574 686f 7220 3d20 416e  eta..author = An
 00000040: 6472 c3a9 2042 c3b6 6e69 0d0a 6175 7468  dr.. B..ni..auth
 00000050: 6f72 5f65 6d61 696c 203d 2061 6e64 7265  or_email = andre
 00000060: 2e62 6f65 6e69 4063 6572 656e 656f 2e66  .boeni@cereneo.f
 00000070: 6f75 6e64 6174 696f 6e0d 0a75 726c 203d  oundation..url =
 00000080: 2068 7474 7073 3a2f 2f67 6974 6875 622e   https://github.
 00000090: 636f 6d2f 6365 7265 6e65 6f2d 666f 756e  com/cereneo-foun
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/analysis.py` & `gaitalytics-0.0.7b0/src/gaitalytics/analysis.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 from abc import ABC, abstractmethod
 from typing import Dict
+
 import numpy as np
 from pandas import DataFrame, concat
 from scipy import signal
-import gaitalytics.cycle
-import gaitalytics.c3d
-import gaitalytics.utils
 
+import gaitalytics.utils
 
 
 class AbstractAnalysis(ABC):
-    def __init__(self, data_list: Dict[str, gaitalytics.cycle.BasicCyclePoint]):
-        self._data_list: Dict[str, gaitalytics.cycle.BasicCyclePoint] = data_list
+    def __init__(self, data_list: Dict[str, gaitalytics.utils.BasicCyclePoint]):
+        self._data_list: Dict[str, gaitalytics.utils.BasicCyclePoint] = data_list
 
     def analyse(self) -> DataFrame:
         pass
 
 
 class AbstractCycleAnalysis(AbstractAnalysis, ABC):
 
-    def __init__(self, data_list: Dict[str, gaitalytics.cycle.BasicCyclePoint], data_type: gaitalytics.c3d.PointDataType):
+    def __init__(self, data_list: Dict[str, gaitalytics.utils.BasicCyclePoint],
+                 data_type: gaitalytics.utils.PointDataType):
         super().__init__(data_list)
         self._point_data_type = data_type
 
     @abstractmethod
     def _do_analysis(self, data: DataFrame) -> DataFrame:
         pass
 
@@ -40,15 +40,16 @@
                 if not by_phase:
                     result = self._do_analysis(data)
                     result['metric'] = key
                 else:
                     standing = data.copy()
                     swinging = data.copy()
                     for row in range(len(data)):
-                        event_frame = raw_point.event_frames.iloc[row][gaitalytics.cycle.BasicCyclePoint.EVENT_FRAME_NUMBER]
+                        event_frame = raw_point.event_frames.iloc[row][
+                            gaitalytics.utils.BasicCyclePoint.FOOT_OFF]
                         swinging.iloc[row, 1:event_frame] = float("Nan")
                         standing.iloc[row, event_frame + 1: -1] = float("Nan")
                     result1 = self._do_analysis(standing)
                     result1['metric'] = f"{key}.standing"
                     result2 = self._do_analysis(swinging)
                     result2['metric'] = f"{key}.swinging"
                     result = concat([result1, result2])
@@ -56,18 +57,42 @@
                 if results is None:
                     results = result
                 else:
                     results = concat([results, result])
         return results.pivot(columns="metric")
 
 
+class JointForcesCycleAnalysis(AbstractCycleAnalysis):
+
+    def __init__(self, data_list: Dict):
+        super().__init__(data_list, gaitalytics.utils.PointDataType.Forces)
+
+    def _filter_keys(self, key: str) -> bool:
+        if super()._filter_keys(key):
+            splits = key.split(".")
+            return splits[3].lower() in splits[0]
+        return False
+
+    def _do_analysis(self, data: DataFrame) -> DataFrame:
+        results = DataFrame(index=data.index)
+        rom_max = data.max(axis=1)
+        rom_min = data.min(axis=1)
+        rom_mean = data.mean(axis=1)
+        results['forces_mean'] = rom_mean
+        results['forces_max'] = rom_max
+        results['forces_min'] = rom_min
+        results['forces_sd'] = data.std(axis=1)
+        results['forces_amplitude'] = rom_max - rom_min
+        return results
+
+
 class JointMomentsCycleAnalysis(AbstractCycleAnalysis):
 
     def __init__(self, data_list: Dict):
-        super().__init__(data_list, gaitalytics.c3d.PointDataType.Moments)
+        super().__init__(data_list, gaitalytics.utils.PointDataType.Moments)
 
     def _filter_keys(self, key: str) -> bool:
         if super()._filter_keys(key):
             splits = key.split(".")
             return splits[3].lower() in splits[0]
         return False
 
@@ -83,21 +108,21 @@
         results['power_amplitude'] = rom_max - rom_min
         return results
 
 
 class JointPowerCycleAnalysis(AbstractCycleAnalysis):
 
     def __init__(self, data_list: Dict):
-        super().__init__(data_list, gaitalytics.c3d.PointDataType.Power)
+        super().__init__(data_list, gaitalytics.utils.PointDataType.Power)
 
     def _filter_keys(self, key: str) -> bool:
         if super()._filter_keys(key):
             splits = key.split(".")
             if splits[3].lower() in splits[0]:
-                return gaitalytics.c3d.AxesNames.z.name is splits[2]
+                return gaitalytics.utils.AxesNames.z.name is splits[2]
         return False
 
     def _do_analysis(self, data: DataFrame) -> DataFrame:
         results = DataFrame(index=data.index)
         rom_max = data.max(axis=1)
         rom_min = data.min(axis=1)
         rom_mean = data.mean(axis=1)
@@ -108,15 +133,15 @@
         results['power_amplitude'] = rom_max - rom_min
         return results
 
 
 class JointAnglesCycleAnalysis(AbstractCycleAnalysis):
 
     def __init__(self, data_list: Dict):
-        super().__init__(data_list, gaitalytics.c3d.PointDataType.Angles)
+        super().__init__(data_list, gaitalytics.utils.PointDataType.Angles)
 
     def _filter_keys(self, key: str) -> bool:
         if super()._filter_keys(key):
             splits = key.split(".")
             return splits[3].lower() in splits[0]
         return False
 
@@ -135,162 +160,179 @@
         results['angle_velocity_min'] = velocity.min(axis=1)
         results['angle_velocity_sd'] = velocity.std(axis=1)
         return results
 
 
 class SpatioTemporalAnalysis(AbstractAnalysis):
 
-    def __init__(self, configs: gaitalytics.utils.ConfigProvider, data_list: Dict, body_height: float = 1800, frequency: int = 100):
+    def __init__(self, configs: gaitalytics.utils.ConfigProvider, data_list: Dict, body_height: float = 1800,
+                 frequency: int = 100):
         super().__init__(data_list)
         self._configs = configs
         self._frequency = frequency
         self._body_height = body_height
 
     def analyse(self) -> DataFrame:
-        step_length = self._calculate_length()
+        subject = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.x,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)].subject
+        step_length = self._calculate_length(subject)
         durations = self._calculate_durations()
 
-        step_height = self._calculate_step_height()
-        step_width = self._calculate_step_width()
+        step_height = self._calculate_step_height(subject)
+        step_width = self._calculate_step_width(subject)
         result = step_length.merge(durations, on="cycle_number")
         result = result.merge(step_height, on="cycle_number")
         result = result.merge(step_width, on="cycle_number")
         result['metric'] = "Spatiotemporal"
         return result.pivot(columns="metric")
 
-    def _calculate_step_width(self) -> DataFrame:
-        right_heel_x_right = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
-                                                                             gaitalytics.c3d.PointDataType.Marker,
-                                                                             gaitalytics.c3d.AxesNames.x,
-                                                                             gaitalytics.c3d.GaitEventContext.RIGHT)].data_table
-        left_heel_x_right = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
-                                                                            gaitalytics.c3d.PointDataType.Marker,
-                                                                            gaitalytics.c3d.AxesNames.x,
-                                                                            gaitalytics.c3d.GaitEventContext.RIGHT)].data_table
-        right_heel_x_left = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
-                                                                            gaitalytics.c3d.PointDataType.Marker,
-                                                                            gaitalytics.c3d.AxesNames.x,
-                                                                            gaitalytics.c3d.GaitEventContext.LEFT)].data_table
-        left_heel_x_left = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
-                                                                           gaitalytics.c3d.PointDataType.Marker,
-                                                                           gaitalytics.c3d.AxesNames.x,
-                                                                           gaitalytics.c3d.GaitEventContext.LEFT)].data_table
+    def _calculate_step_width(self, subject: gaitalytics.utils.SubjectMeasures) -> DataFrame:
 
-        right = self._calculate_step_width_side(right_heel_x_right, left_heel_x_right, "right")
-        left = self._calculate_step_width_side(left_heel_x_left, right_heel_x_left, "left")
+        right_heel_x_right = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.x,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)].data_table
+        left_heel_x_right = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.x,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)].data_table
+        right_heel_x_left = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.x,
+                                                        gaitalytics.utils.GaitEventContext.LEFT)].data_table
+        left_heel_x_left = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.x,
+                                                        gaitalytics.utils.GaitEventContext.LEFT)].data_table
+
+        right = self._calculate_step_width_side(right_heel_x_right, left_heel_x_right, subject.body_height, "right")
+        left = self._calculate_step_width_side(left_heel_x_left, right_heel_x_left, subject.body_height, "left")
 
         return concat([left, right], axis=1)
 
     @staticmethod
-    def _calculate_step_width_side(context_heel_x: DataFrame, contra_heel_x: DataFrame, side: str) -> DataFrame:
+    def _calculate_step_width_side(context_heel_x: DataFrame, contra_heel_x: DataFrame, body_height: float,
+                                   side: str) -> DataFrame:
+        # TODO: Medial marker
         column_label = f"step_width_{side}"
         width = DataFrame(index=context_heel_x.index, columns=[column_label])
         for cycle_number in context_heel_x.index.to_series():
             width_c = abs(context_heel_x.loc[cycle_number][1] - contra_heel_x.loc[cycle_number][1])
-            width.loc[cycle_number][column_label] = width_c
+            width.loc[cycle_number][column_label] = width_c / body_height
         return width
 
-    def _calculate_step_height(self) -> DataFrame:
-        right_heel_z = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
-                                                                       gaitalytics.c3d.PointDataType.Marker,
-                                                                       gaitalytics.c3d.AxesNames.z,
-                                                                       gaitalytics.c3d.GaitEventContext.RIGHT)].data_table
-        left_heel_z = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
-                                                                      gaitalytics.c3d.PointDataType.Marker,
-                                                                      gaitalytics.c3d.AxesNames.z,
-                                                                      gaitalytics.c3d.GaitEventContext.LEFT)].data_table
+    def _calculate_step_height(self, subject: gaitalytics.utils.SubjectMeasures) -> DataFrame:
+        right_heel_z = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.z,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)].data_table
+        left_heel_z = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.z,
+                                                        gaitalytics.utils.GaitEventContext.LEFT)].data_table
 
-        right = self._calculate_step_height_side(right_heel_z, "right")
-        left = self._calculate_step_height_side(left_heel_z, "left")
+        right = self._calculate_step_height_side(right_heel_z, subject.body_height, "right")
+        left = self._calculate_step_height_side(left_heel_z, subject.body_height, "left")
         return concat([left, right], axis=1)
 
     @staticmethod
-    def _calculate_step_height_side(heel_z: DataFrame, side: str) -> DataFrame:
+    def _calculate_step_height_side(heel_z: DataFrame, body_height: float, side: str) -> DataFrame:
         column_label = f"step_height_{side}"
         height = DataFrame(index=heel_z.index, columns=[column_label])
-        height[column_label] = heel_z.max(axis=1) - heel_z.min(axis=1)
+        height[column_label] = (heel_z.max(axis=1) - heel_z.min(axis=1)) / body_height
         return height
 
     def _calculate_durations(self):
         right_heel_progression = self._data_list[
             gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
-                                            gaitalytics.c3d.PointDataType.Marker,
-                                            gaitalytics.c3d.AxesNames.y,
-                                            gaitalytics.c3d.GaitEventContext.RIGHT)]
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.y,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)]
         left_heel_progression = self._data_list[
             gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
-                                            gaitalytics.c3d.PointDataType.Marker,
-                                            gaitalytics.c3d.AxesNames.y,
-                                            gaitalytics.c3d.GaitEventContext.LEFT)]
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.y,
+                                                        gaitalytics.utils.GaitEventContext.LEFT)]
         right_durations = self._side_duration_calculation(right_heel_progression, "right")
         left_durations = self._side_duration_calculation(left_heel_progression, "left")
 
         return concat([left_durations, right_durations], axis=1)
 
     def _side_duration_calculation(self, progression: DataFrame, side: str) -> DataFrame:
         c_dur_label = f"cycle_duration_s_{side}"
         s_dur_label = f"step_duration_s_{side}"
         sw_dur_label = f"swing_duration_p_{side}"
         st_dur_label = f"stance_duration_p_{side}"
         columns = [c_dur_label, s_dur_label, sw_dur_label, st_dur_label]
         durations = DataFrame(index=progression.data_table.index, columns=columns)
         for cycle_number in progression.data_table.index.to_series():
-            toe_off = progression.event_frames.loc[cycle_number][gaitalytics.cycle.BasicCyclePoint.EVENT_FRAME_NUMBER]
+            toe_off = progression.event_frames.loc[cycle_number][gaitalytics.utils.BasicCyclePoint.FOOT_OFF]
             cycle_data = progression.data_table.loc[cycle_number][~progression.data_table.loc[cycle_number].isna()]
 
             durations.loc[cycle_number][c_dur_label] = len(cycle_data) / self._frequency
             durations.loc[cycle_number][s_dur_label] = len(cycle_data[toe_off: -1]) / self._frequency
         swing_percent = durations[s_dur_label] / durations[c_dur_label]
         durations[sw_dur_label] = swing_percent
-        durations[st_dur_label] = 100 - durations[sw_dur_label]
+        durations[st_dur_label] = 1 - durations[sw_dur_label]
         return durations
 
-    def _calculate_length(self) -> DataFrame:
+    def _calculate_length(self, subject: gaitalytics.utils.SubjectMeasures) -> DataFrame:
         right_heel_progression_right = self._data_list[
             gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
-                                            gaitalytics.c3d.PointDataType.Marker,
-                                            gaitalytics.c3d.AxesNames.y,
-                                            gaitalytics.c3d.GaitEventContext.RIGHT)].data_table
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.y,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)].data_table
         left_heel_progression_right = self._data_list[
             gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
-                                            gaitalytics.c3d.PointDataType.Marker,
-                                            gaitalytics.c3d.AxesNames.y,
-                                            gaitalytics.c3d.GaitEventContext.RIGHT)].data_table
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.y,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)].data_table
 
         left_heel_progression_left = self._data_list[
             gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_heel,
-                                            gaitalytics.c3d.PointDataType.Marker,
-                                            gaitalytics.c3d.AxesNames.y,
-                                            gaitalytics.c3d.GaitEventContext.LEFT)].data_table
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.y,
+                                                        gaitalytics.utils.GaitEventContext.LEFT)].data_table
         right_heel_progression_left = self._data_list[
             gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_heel,
-                                            gaitalytics.c3d.PointDataType.Marker,
-                                            gaitalytics.c3d.AxesNames.y,
-                                            gaitalytics.c3d.GaitEventContext.LEFT)].data_table
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.y,
+                                                        gaitalytics.utils.GaitEventContext.LEFT)].data_table
 
         right = self._side_step_length_calculation(right_heel_progression_right,
-                                                   left_heel_progression_right, "right")
+                                                   left_heel_progression_right, subject.body_height, "right")
         left = self._side_step_length_calculation(left_heel_progression_left,
-                                                  right_heel_progression_left, "left")
+                                                  right_heel_progression_left, subject.body_height, "left")
 
         results = concat([left, right], axis=1)
+        ## Todo: check stride length
         results['stride_length'] = results["step_length_right"] + results["step_length_left"]
 
         return results
 
     @staticmethod
     def _side_step_length_calculation(context_heel_progression: DataFrame,
-                                      contra_heel_progression: DataFrame, side: str) -> np.array:
+                                      contra_heel_progression: DataFrame, body_height: float, side: str) -> np.array:
+        # TODO: checks step definition
         s_len_label = f"step_length_{side}"
         step_length = DataFrame(index=context_heel_progression.index, columns=[s_len_label])
 
         for cycle_number in context_heel_progression.index.to_series():
             context_hs_pos = context_heel_progression.loc[cycle_number][1]
             contra_hs_pos = contra_heel_progression.loc[cycle_number][1]
-            step_length.loc[cycle_number][s_len_label] = abs(context_hs_pos - contra_hs_pos)
+            step_length.loc[cycle_number][s_len_label] = abs(context_hs_pos - contra_hs_pos) / body_height
 
         return step_length
 
     # drag_duration_gc = np.zeros(len(data))  # %GC
     # drag_duration_swing = np.zeros(len(data))  # %swing
     # single_stance_duration = np.zeros(len(data))  # %GC
     # double_stance_duration = np.zeros(len(data))  # %GC
@@ -301,42 +343,44 @@
     # length_com_trajectory = np.zeros(len(data))  # %BH
     # lateral_movement_during_swing = np.zeros(len(data))  # BH%
     # max_hip_vertical_amplitude = np.zeros(len(data))  # BH%
 
 
 class MinimalClearingDifference(AbstractAnalysis):
 
-    def __init__(self, data_list: Dict[str, gaitalytics.cycle.BasicCyclePoint], configs: gaitalytics.utils.ConfigProvider):
+    def __init__(self, data_list: Dict[str, gaitalytics.utils.BasicCyclePoint],
+                 configs: gaitalytics.utils.ConfigProvider):
         super().__init__(data_list)
         self._configs = configs
 
     def analyse(self) -> DataFrame:
-        right_toe = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_meta_2,
-                                                                    gaitalytics.c3d.PointDataType.Marker,
-                                                                    gaitalytics.c3d.AxesNames.z,
-                                                                    gaitalytics.c3d.GaitEventContext.RIGHT)]
+        right_toe = self._data_list[
+            gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.right_meta_2,
+                                                        gaitalytics.utils.PointDataType.Marker,
+                                                        gaitalytics.utils.AxesNames.z,
+                                                        gaitalytics.utils.GaitEventContext.RIGHT)]
         left_toe = self._data_list[gaitalytics.utils.ConfigProvider.define_key(self._configs.MARKER_MAPPING.left_meta_2,
-                                                                   gaitalytics.c3d.PointDataType.Marker,
-                                                                   gaitalytics.c3d.AxesNames.z,
-                                                                   gaitalytics.c3d.GaitEventContext.LEFT)]
+                                                                               gaitalytics.utils.PointDataType.Marker,
+                                                                               gaitalytics.utils.AxesNames.z,
+                                                                               gaitalytics.utils.GaitEventContext.LEFT)]
 
         right = self._calculate_minimal_clearance(right_toe.data_table, right_toe.event_frames, "right")
         left = self._calculate_minimal_clearance(left_toe.data_table, left_toe.event_frames, "left")
         result = concat([left, right], axis=1)
         result['metric'] = "MinimalToeClearance"
         return result.pivot(columns="metric")
 
     @staticmethod
     def _calculate_minimal_clearance(toe: DataFrame, event_frames: DataFrame, side: str) -> DataFrame:
         s_mtc_label = f"minimal_toe_clearance_{side}"
         s_mtc_cycle_label = f"minimal_toe_clearance_swing_p_{side}"
         s_tc_hs_label = f"toe_clearance_heel_strike_{side}"
         toe_clearance = DataFrame(index=toe.index, columns=[s_mtc_label, s_mtc_cycle_label, s_tc_hs_label])
         for cycle_number in toe.index.to_series():
-            toe_off_frame = event_frames.loc[cycle_number][gaitalytics.cycle.BasicCyclePoint.EVENT_FRAME_NUMBER]
+            toe_off_frame = event_frames.loc[cycle_number][gaitalytics.utils.BasicCyclePoint.FOOT_OFF]
             swing_phase_data = toe.loc[cycle_number][toe_off_frame: -1]
             mid_swing_index = round(len(swing_phase_data) / 2)
             peaks = signal.find_peaks(swing_phase_data[0:mid_swing_index], distance=len(swing_phase_data))
             toe_clear_min = min(swing_phase_data[peaks[0][0]:-1])
             tc_percent = np.where(swing_phase_data[peaks[0][0]:-1] == toe_clear_min)[0] / len(swing_phase_data)
             tc_clear_hs = max(swing_phase_data[mid_swing_index:-1])
             toe_clearance.loc[cycle_number][s_mtc_label] = toe_clear_min
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/api.py` & `gaitalytics-0.0.7b0/src/gaitalytics/api.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 from __future__ import annotations
 
 import os
 from typing import Dict, List
 
 from pandas import DataFrame
+
+import gaitalytics.analysis
 import gaitalytics.c3d
 import gaitalytics.cycle
 import gaitalytics.events
 import gaitalytics.utils
-import gaitalytics.analysis
-
 
 # constants
 CYCLE_METHOD_HEEL_STRIKE = "HS"
 CYCLE_METHOD_TOE_OFF = "TO"
 
 NORMALISE_METHODE_LINEAR = "linear"
 NORMALISE_METHODE_LIST = (NORMALISE_METHODE_LINEAR)
@@ -36,15 +36,15 @@
                  ANALYSIS_ANGLES,
                  ANALYSIS_POWERS,
                  ANALYSIS_FORCES,
                  ANALYSIS_SPATIO_TEMP,
                  ANALYSIS_TOE_CLEARANCE)
 
 
-def analyse_data(cycle_data: Dict[str, gaitalytics.cycle.BasicCyclePoint],
+def analyse_data(cycle_data: Dict[str, gaitalytics.utils.BasicCyclePoint],
                  config: gaitalytics.utils.ConfigProvider,
                  methode: List[str] = ANALYSIS_LIST) -> DataFrame:
     """
     runs specified analysis and concatenates into one frame
     :param cycle_data: unnormalised cycle data
     :param config: configs from marker and model mapping
     :param methode: list of methods, 'moments' api.ANALYSIS_MOMENTS, 'angles' api.ANALYSIS_ANGLES,
@@ -58,30 +58,65 @@
     methods: List[gaitalytics.analysis.AbstractAnalysis] = []
     if ANALYSIS_ANGLES in methode:
         methods.append(gaitalytics.analysis.JointAnglesCycleAnalysis(cycle_data))
     if ANALYSIS_MOMENTS in methode:
         methods.append(gaitalytics.analysis.JointMomentsCycleAnalysis(cycle_data))
     if ANALYSIS_POWERS in methode:
         methods.append(gaitalytics.analysis.JointPowerCycleAnalysis(cycle_data))
+    if ANALYSIS_FORCES in methode:
+        methods.append(gaitalytics.analysis.JointForcesCycleAnalysis(cycle_data))
     if ANALYSIS_SPATIO_TEMP in methode:
         methods.append(gaitalytics.analysis.SpatioTemporalAnalysis(config, cycle_data))
     if ANALYSIS_TOE_CLEARANCE in methode:
         methods.append(gaitalytics.analysis.MinimalClearingDifference(cycle_data, config))
 
     results = None
     for methode in methods:
         result = methode.analyse()
         if results is None:
             results = result
         else:
-            results = results.merge(result, on=gaitalytics.cycle.BasicCyclePoint.CYCLE_NUMBER)
+            results = results.merge(result, on=gaitalytics.utils.BasicCyclePoint.CYCLE_NUMBER)
 
     return results
 
 
+def check_gait_event(c3d_file_path: str,
+                     output_path: str,
+                     anomaly_checker: List[str] = GAIT_EVENT_CHECKER_LIST):
+    """
+    Checks events aditionally
+    with given anomaly_checker method and saves it in output_path with '*_anomaly.txt' extension
+    :param c3d_file_path: path of c3d file with modelled filtered data '.3.c3d'
+    :param output_path: path to dir to store c3d file with events
+    :param anomaly_checker: list of anomaly checkers, "context" api.GAIT_EVENT_CHECKER_CONTEXT,
+       "spacing" api.GAIT_EVENT_CHECKER_SPACING
+    """
+    if not os.path.isfile(c3d_file_path):
+        raise FileExistsError(f"{c3d_file_path} does not exists")
+    if not os.path.isdir(output_path):
+        raise FileExistsError(f"{output_path} does not exists")
+    if not all(item in GAIT_EVENT_CHECKER_LIST for item in anomaly_checker):
+        raise KeyError(f"{anomaly_checker} are not a valid anomaly checker")
+    # read c3d
+    acq_trial = gaitalytics.c3d.read_btk(c3d_file_path)
+    # get anomaly detection
+    checker = _get_anomaly_checker(anomaly_checker)
+    detected, anomalies = checker.check_events(acq_trial)
+
+    # write anomalies to file
+    if detected:
+        filename = os.path.basename(c3d_file_path).replace(".4.c3d", "_anomalies.txt")
+        out_path = os.path.join(output_path, filename)
+        f = open(out_path, "w")
+        for anomaly in anomalies:
+            print(anomaly, file=f)
+        f.close()
+
+
 def detect_gait_events(c3d_file_path: str,
                        output_path: str,
                        configs: gaitalytics.utils.ConfigProvider,
                        methode: str = GAIT_EVENT_METHODE_MARKER,
                        anomaly_checker: List[str] = GAIT_EVENT_CHECKER_LIST):
     """
     Adds gait events to c3d file and saves it in output_path with a '.4.c3d' extension. Checks events aditionally
@@ -116,29 +151,15 @@
         methode = gaitalytics.events.ZenisGaitEventDetector(configs)
 
     methode.detect_events(acq_trial)
 
     # write events c3d
     gaitalytics.c3d.write_btk(acq_trial, out_path)
 
-    # read c3d
-    acq_trial = gaitalytics.c3d.read_btk(c3d_file_path)
-
-    # get anomaly detection
-    checker = _get_anomaly_checker(anomaly_checker)
-    detected, anomalies = checker.check_events(acq_trial)
-
-    # write anomalies to file
-    if detected:
-        filename = os.path.basename(c3d_file_path).replace(".3.c3d", "_anomalies.txt")
-        out_path = os.path.join(output_path, filename)
-        f = open(out_path, "w")
-        for anomaly in anomalies:
-            print(anomaly)
-        f.close()
+    check_gait_event(out_path, output_path)
 
 
 def _get_anomaly_checker(anomaly_checker: List[str]) -> gaitalytics.events.AbstractEventAnomalyChecker:
     """
     defines checker by list of inputs
     :param anomaly_checker: list of checker name
     :return: checker object
@@ -147,15 +168,16 @@
     if GAIT_EVENT_CHECKER_CONTEXT in anomaly_checker:
         checker = gaitalytics.events.ContextPatternChecker()
     if GAIT_EVENT_CHECKER_SPACING in anomaly_checker:
         checker = gaitalytics.events.EventSpacingChecker(checker)
     return checker
 
 
-def extract_cycles_buffered(buffer_output_path: str, configs: gaitalytics.utils.ConfigProvider) -> gaitalytics.cycle.CyclePointLoader:
+def extract_cycles_buffered(buffer_output_path: str,
+                            configs: gaitalytics.utils.ConfigProvider) -> gaitalytics.cycle.CyclePointLoader:
     """
     gets normalised and unnormalised data from buffered folder. It is needed to run api.extract_cycles as
     api.normalise_cycles with given buffer_output_path once to use this function
     :param buffer_output_path: path to folder
     :param configs: configs from marker and model mapping
     :return: object containing normalised and unnormalised data lists
     """
@@ -167,15 +189,16 @@
     return loader
 
 
 def extract_cycles(c3d_file_path: str,
                    configs: gaitalytics.utils.ConfigProvider,
                    methode: str = CYCLE_METHOD_HEEL_STRIKE,
                    buffer_output_path: str = None,
-                   anomaly_checker: List[str] = GAIT_EVENT_CHECKER_LIST) -> Dict[str, gaitalytics.cycle.BasicCyclePoint]:
+                   anomaly_checker: List[str] = GAIT_EVENT_CHECKER_LIST) -> Dict[
+    str, gaitalytics.utils.BasicCyclePoint]:
     """
     extracts and returns cycles from c3d. If a buffered path is delivered data will be stored in the path in separated
     csv file. Do not edit files and structure.
     :param c3d_file_path: path of c3d file with foot_off and foot_strike events '*.4.c3d'
     :param configs: configs from marker and model mapping
     :param methode: method to cut gait cycles either "HS" api.CYCLE_METHOD_HEEL_STRIKE or "TO" api.CYCLE_METHOD_TOE_OFF
     :param buffer_output_path: if buffering needed path to folder
@@ -218,17 +241,17 @@
         prefix = os.path.basename(c3d_file_path).replace(".4.c3d", "")
         _cycle_points_to_csv(cycle_data, buffer_output_path, prefix)
 
     return cycle_data
 
 
 def normalise_cycles(c3d_file_path: str,
-                     cycle_data: Dict[str, gaitalytics.cycle.BasicCyclePoint],
+                     cycle_data: Dict[str, gaitalytics.utils.BasicCyclePoint],
                      method: str = NORMALISE_METHODE_LINEAR,
-                     buffer_output_path: str = None) -> Dict[str, gaitalytics.cycle.BasicCyclePoint]:
+                     buffer_output_path: str = None) -> Dict[str, gaitalytics.utils.BasicCyclePoint]:
     """
     normalise and returns cycles
     :param c3d_file_path:  path of c3d file with foot_off and foot_strike events '*.4.c3d'
     :param cycle_data: unnormalised cycle data
     :param method: method normalise "linear" api.NORMALISE_METHODE_LINEAR
     :param buffer_output_path: if buffering needed path to folder
     :return: normalised gait cycles
@@ -252,10 +275,13 @@
     if buffer_output_path:
         prefix = os.path.basename(c3d_file_path).replace(".4.c3d", "")
         _cycle_points_to_csv(normalised_data, buffer_output_path, prefix)
 
     return normalised_data
 
 
-def _cycle_points_to_csv(cycle_data: Dict, dir_path: str, prefix: str):
+def _cycle_points_to_csv(cycle_data: Dict[str, gaitalytics.utils.BasicCyclePoint], dir_path: str, prefix: str):
+    subject_saved = False
     for key in cycle_data:
         cycle_data[key].to_csv(dir_path, prefix)
+        if not subject_saved:
+            cycle_data[key].subject.to_file(dir_path)
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/c3d.py` & `gaitalytics-0.0.7b0/src/gaitalytics/c3d.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,46 +1,17 @@
 from __future__ import annotations
 
-from enum import Enum
 from statistics import mean
 
 import btk
 import numpy as np
 
-ANALOG_VOLTAGE_PREFIX_LABEL = "Voltage."
-
+import gaitalytics.utils
 
-class PointDataType(Enum):
-    Marker = 0
-    Angles = 1
-    Forces = 2
-    Moments = 3
-    Power = 4
-    Scalar = 5
-    Reaction = 6
-
-
-class AxesNames(Enum):
-    x = 0
-    y = 1
-    z = 2
-
-
-class GaitEventContext(Enum):
-    """
-    Representation of gait event contexts. At the moment mainly left and right
-    """
-    LEFT = "Left"
-    RIGHT = "Right"
-
-    @classmethod
-    def get_contrary_context(cls, context: str):
-        if context == cls.LEFT.value:
-            return cls.RIGHT
-        return cls.LEFT
+ANALOG_VOLTAGE_PREFIX_LABEL = "Voltage."
 
 
 def sort_events(acq):
     """
     sort events in acquisition
 
     Args:
@@ -93,15 +64,15 @@
     writer = btk.btkAcquisitionFileWriter()
     writer.SetInput(acq)
     writer.SetFilename(filename)
     writer.Update()
 
 
 def is_progression_axes_flip(left_heel, left_toe):
-    return 0 < mean(left_toe[AxesNames.y.value] - left_heel[AxesNames.y.value])
+    return 0 < mean(left_toe[gaitalytics.utils.AxesNames.y.value] - left_heel[gaitalytics.utils.AxesNames.y.value])
 
 
 def correct_points_frame_by_frame(acq_trial: btk.btkAcquisition):
     frame_size = acq_trial.GetPointFrameNumber()
     correction = get_fastest_point_by_frame(acq_trial, 1)
     for frame_number in range(1, frame_size):
         if (frame_number + 2) < frame_size:
@@ -126,22 +97,7 @@
     lfmh_dist = lfmh_point.GetValue(frame_number - 1, 1) - lfmh_point.GetValue(frame_number, 1)
     lhee_dist = lhee_point.GetValue(frame_number - 1, 1) - lhee_point.GetValue(frame_number, 1)
     rfmh_dist = rfmh_point.GetValue(frame_number - 1, 1) - rfmh_point.GetValue(frame_number, 1)
     rhee_dist = rhee_point.GetValue(frame_number - 1, 1) - rhee_point.GetValue(frame_number, 1)
     return np.min([lfmh_dist, lhee_dist, rfmh_dist, rhee_dist])
 
 
-class GaitEventLabel(Enum):
-    FOOT_STRIKE = "Foot Strike"
-    FOOT_OFF = "Foot Off"
-
-    @classmethod
-    def get_contrary_event(cls, event_label: str):
-        if event_label == cls.FOOT_STRIKE.value:
-            return cls.FOOT_OFF
-        return cls.FOOT_STRIKE
-
-    @classmethod
-    def get_type_id(cls, event_label: str):
-        if event_label == cls.FOOT_STRIKE.value:
-            return 1
-        return 2
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/emg.py` & `gaitalytics-0.0.7b0/src/gaitalytics/emg.py`

 * *Files identical despite different names*

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/events.py` & `gaitalytics-0.0.7b0/src/gaitalytics/events.py`

 * *Files 6% similar despite different names*

```diff
@@ -18,21 +18,21 @@
 
     @abstractmethod
     def detect_events(self, acq: btkAcquisition):
         pass
 
     @staticmethod
     def _create_event(acq, frame: int,
-                      event_label: gaitalytics.c3d.GaitEventLabel,
-                      event_context: gaitalytics.c3d.GaitEventContext):
+                      event_label: gaitalytics.utils.GaitEventLabel,
+                      event_context: gaitalytics.utils.GaitEventContext):
         frequency = acq.GetPointFrequency()
         event = btkEvent()
         event.SetLabel(event_label.value)
         # event.SetFrame(int(frame))
-        event.SetId(gaitalytics.c3d.GaitEventLabel.get_type_id(event_label.value))
+        event.SetId(gaitalytics.utils.GaitEventLabel.get_type_id(event_label.value))
         event.SetContext(event_context.value)
         event.SetTime(float((frame - 1) / frequency))
         return event
 
 
 class ZenisGaitEventDetector(AbstractGaitEventDetector):
     """
@@ -64,32 +64,37 @@
 
         sacrum = (right_hip + left_hip) / 2.0
         right_diff_heel = right_heel - sacrum
         left_diff_heel = left_heel - sacrum
         right_diff_toe = right_heel - sacrum
         left_diff_toe = left_heel - sacrum
 
-        self._create_events(acq, left_diff_toe, gaitalytics.c3d.GaitEventLabel.FOOT_OFF, gaitalytics.c3d.GaitEventContext.LEFT)
-        self._create_events(acq, right_diff_toe, gaitalytics.c3d.GaitEventLabel.FOOT_OFF, gaitalytics.c3d.GaitEventContext.RIGHT)
-        self._create_events(acq, left_diff_heel, gaitalytics.c3d.GaitEventLabel.FOOT_STRIKE, gaitalytics.c3d.GaitEventContext.LEFT)
-        self._create_events(acq, right_diff_heel, gaitalytics.c3d.GaitEventLabel.FOOT_STRIKE, gaitalytics.c3d.GaitEventContext.RIGHT)
+        self._create_events(acq, left_diff_toe, gaitalytics.utils.GaitEventLabel.FOOT_OFF,
+                            gaitalytics.utils.GaitEventContext.LEFT)
+        self._create_events(acq, right_diff_toe, gaitalytics.utils.GaitEventLabel.FOOT_OFF,
+                            gaitalytics.utils.GaitEventContext.RIGHT)
+        self._create_events(acq, left_diff_heel, gaitalytics.utils.GaitEventLabel.FOOT_STRIKE,
+                            gaitalytics.utils.GaitEventContext.LEFT)
+        self._create_events(acq, right_diff_heel, gaitalytics.utils.GaitEventLabel.FOOT_STRIKE,
+                            gaitalytics.utils.GaitEventContext.RIGHT)
 
     #   gaitalytics.c3d.sort_events(acq)
 
-    def _create_events(self, acq, diff, event_label: gaitalytics.c3d.GaitEventLabel,
-                       event_context: gaitalytics.c3d.GaitEventContext,
+    def _create_events(self, acq, diff, event_label: gaitalytics.utils.GaitEventLabel,
+                       event_context: gaitalytics.utils.GaitEventContext,
                        min_distance: int = 100,
                        show_plot: bool = False):
-        data = diff[:, gaitalytics.c3d.AxesNames.y.value]
-        if gaitalytics.c3d.is_progression_axes_flip(acq.GetPoint(self._config.MARKER_MAPPING.left_heel.value).GetValues(),
-                                        acq.GetPoint(self._config.MARKER_MAPPING.left_meta_5.value).GetValues()):
+        data = diff[:, gaitalytics.utils.AxesNames.y.value]
+        if gaitalytics.c3d.is_progression_axes_flip(
+                acq.GetPoint(self._config.MARKER_MAPPING.left_heel.value).GetValues(),
+                acq.GetPoint(self._config.MARKER_MAPPING.left_meta_5.value).GetValues()):
             data = data * -1
         data = gaitalytics.utils.min_max_norm(data)
 
-        if gaitalytics.c3d.GaitEventLabel.FOOT_STRIKE == event_label:
+        if gaitalytics.utils.GaitEventLabel.FOOT_STRIKE == event_label:
             data = [entry * -1 for entry in data]
 
         extremes, foo = signal.find_peaks(data, height=[0, 1], distance=min_distance)
         if show_plot:
             plt.plot(data)
             for i in extremes:
                 plt.plot(i, data[i], 'ro')
@@ -118,15 +123,15 @@
 
     def detect_events(self, acq: btkAcquisition):
         """
         Detect force plate gait events with peak detection
         :param acq: loaded and filtered acquisition
         """
 
-        for context in gaitalytics.c3d.GaitEventContext:
+        for context in gaitalytics.utils.GaitEventContext:
             force_down_sample = force_plate_down_sample(acq, self._mapped_force_plate[context.value])
             detection = detect_onset(force_down_sample, threshold=self._weight_threshold)
             sequence = self._detect_gait_event_type(force_down_sample, detection)
             self._store_force_plate_events(acq, context, sequence)
 
     def _store_force_plate_events(self, btk_acq, context, sequence):
         for elem in sequence:
@@ -152,17 +157,17 @@
 
                 # check for index out of bound
                 if 20 < signal_index < (signal_length - 20):
 
                     # positive or negative slope (FeetOff or FeetStrike)
                     diff = force_plate_signal[signal_index - 20] - force_plate_signal[signal_index + 20]
                     if diff > 0:
-                        detected_event_types.append([gaitalytics.c3d.GaitEventLabel.FOOT_OFF, signal_index])
+                        detected_event_types.append([gaitalytics.utils.GaitEventLabel.FOOT_OFF, signal_index])
                     else:
-                        detected_event_types.append([gaitalytics.c3d.GaitEventLabel.FOOT_STRIKE, signal_index])
+                        detected_event_types.append([gaitalytics.utils.GaitEventLabel.FOOT_STRIKE, signal_index])
         return detected_event_types  # Contain the label of the event and the corresponding index
 
 
 # Anomaly detection
 class GaitEventAnomaly:
     """
     Stores anomalies for easy print
@@ -269,23 +274,24 @@
                         abnormal_event_frames.append(anomaly)
                         anomaly_detected = True
                     break
         return [anomaly_detected, abnormal_event_frames]
 
 
 # utils
-def find_next_event(acq: btkAcquisition, label: str, context, start_index: int) -> [btkEvent, btkEvent]:
+def find_next_event(acq: btkAcquisition, label: str, context, start_index: int) -> [btkEvent, List[btkEvent]]:
     if acq.GetEventNumber() >= start_index + 1:
+        unused_events: List[btkEvent] = []
         for event_index in range(start_index + 1, acq.GetEventNumber()):
             event = acq.GetEvent(event_index)
             if event.GetContext() == context:
                 if event.GetLabel() == label:
-                    return [event, unused_event]
-                else:
-                    unused_event = event
+                    return [event, unused_events]
+
+            unused_events.append(event)
     raise IndexError()
 
 
 def force_plate_down_sample(acq: btkAcquisition, force_plate_index: int) -> list:
     """
 
     :param acq: c3d file
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/modelling.py` & `gaitalytics-0.0.7b0/src/gaitalytics/modelling.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,19 +1,18 @@
 from abc import ABC, abstractmethod
 
 import numpy as np
-from btk import btkAcquisition, btkPoint
-import gaitalytics.c3d
+from btk import btkAcquisition, btkPoint, btkEventCollection
+
 import gaitalytics.utils
-from . import c3d, utils
 
 
 class BaseOutputModeller(ABC):
 
-    def __init__(self, label: str, point_type: gaitalytics.c3d.PointDataType):
+    def __init__(self, label: str, point_type: gaitalytics.utils.PointDataType):
         self._label = label
         self._type = point_type
 
     def create_point(self, acq: btkAcquisition):
         result = self._calculate_point(acq)
         point = btkPoint(self._type.value)
         point.SetValues(result)
@@ -24,15 +23,15 @@
     def _calculate_point(self, acq: btkAcquisition) -> np.ndarray:
         pass
 
 
 class COMModeller(BaseOutputModeller):
 
     def __init__(self, configs: gaitalytics.utils.ConfigProvider):
-        super().__init__(configs.MARKER_MAPPING.com.value, gaitalytics.c3d.PointDataType.Scalar)
+        super().__init__(configs.MARKER_MAPPING.com.value, gaitalytics.utils.PointDataType.Scalar)
         self._configs = configs
 
     def _calculate_point(self, acq: btkAcquisition):
         l_hip_b = acq.GetPoint(self._configs.MARKER_MAPPING.left_back_hip.value).GetValues()
         r_hip_b = acq.GetPoint(self._configs.MARKER_MAPPING.right_back_hip.value).GetValues()
         l_hip_f = acq.GetPoint(self._configs.MARKER_MAPPING.left_front_hip.value).GetValues()
         r_hip_f = acq.GetPoint(self._configs.MARKER_MAPPING.right_front_hip.value).GetValues()
@@ -41,42 +40,59 @@
 
 class MLcMoSModeller(BaseOutputModeller):
 
     def __init__(self, configs: gaitalytics.utils.ConfigProvider, dominant_leg_length: float, belt_speed: float):
         self._configs = configs
         self._dominant_leg_length = dominant_leg_length
         self._belt_speed = belt_speed
-        super().__init__("MLcMoS", gaitalytics.c3d.PointDataType.Scalar)
+        super().__init__("MLcMoS", gaitalytics.utils.PointDataType.Scalar)
 
     def _calculate_point(self, acq: btkAcquisition) -> np.ndarray:
         freq = acq.GetPointFrequency()
         com = acq.GetPoint(self._configs.MARKER_MAPPING.com.value).GetValues()
         l_grf = acq.GetPoint(self._configs.MODEL_MAPPING.left_GRF.value).GetValues()
         r_grf = acq.GetPoint(self._configs.MODEL_MAPPING.right_GRF.value).GetValues()
-        l_lat_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.left_lateral_malleoli.value).GetValues()
-        r_lat_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.right_lateral_malleoli.value).GetValues()
-        l_med_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.left_medial_malleoli.value).GetValues()
-        r_med_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.right_medial_malleoli.value).GetValues()
+        l_lat_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.left_lat_malleoli.value).GetValues()
+        r_lat_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.right_lat_malleoli.value).GetValues()
+        l_med_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.left_med_malleoli.value).GetValues()
+        r_med_malleoli = acq.GetPoint(self._configs.MARKER_MAPPING.right_med_malleoli.value).GetValues()
         l_meta_2 = acq.GetPoint(self._configs.MARKER_MAPPING.left_meta_2.value).GetValues()
         r_meta_2 = acq.GetPoint(self._configs.MARKER_MAPPING.right_meta_2.value).GetValues()
         l_meta_5 = acq.GetPoint(self._configs.MARKER_MAPPING.left_meta_5.value).GetValues()
         r_meta_5 = acq.GetPoint(self._configs.MARKER_MAPPING.right_meta_5.value).GetValues()
         l_heel = acq.GetPoint(self._configs.MARKER_MAPPING.left_heel.value).GetValues()
         r_heel = acq.GetPoint(self._configs.MARKER_MAPPING.right_heel.value).GetValues()
+        events = acq.GetEvents()
         return self.ML_cMoS(com, freq, r_grf, l_grf, freq, r_lat_malleoli, l_lat_malleoli, r_med_malleoli,
                             l_med_malleoli,
                             r_meta_2, l_meta_2, r_meta_5, l_meta_5, r_heel, l_heel, freq, self._dominant_leg_length,
-                            self._belt_speed)
+                            self._belt_speed, events)
+
+    def ML_cMoS(self, COM : gaitalytics.utils.BasicCyclePoint,
+                COM_freq : int,
+                vGRF_Right : gaitalytics.utils.BasicCyclePoint,
+                vGRF_Left : gaitalytics.utils.BasicCyclePoint,
+                vGRF_freq: int,
+                Lat_Malleoli_Marker_Right: gaitalytics.utils.BasicCyclePoint,
+                Lat_Malleoli_Marker_Left: gaitalytics.utils.BasicCyclePoint,
+                Med_Malleoli_Marker_Right: gaitalytics.utils.BasicCyclePoint,
+                Med_Malleoli_Marker_Left: gaitalytics.utils.BasicCyclePoint,
+                Second_Meta_Head_Marker_Right: gaitalytics.utils.BasicCyclePoint,
+                Second_Meta_Head_Marker_Left: gaitalytics.utils.BasicCyclePoint,
+                Fifth_Meta_Head_Marker_Right: gaitalytics.utils.BasicCyclePoint,
+                Fifth_Meta_Head_Marker_Left: gaitalytics.utils.BasicCyclePoint,
+                Heel_Marker_Right: gaitalytics.utils.BasicCyclePoint,
+                Heel_Marker_Left: gaitalytics.utils.BasicCyclePoint,
+                Marker_freq: int,
+                dominant_leg_length: float,
+                belt_speed: float,
+                events: btkEventCollection,
+                show: bool=False) -> np.ndarray:
 
-    def ML_cMoS(self, COM, COM_freq, vGRF_Right, vGRF_Left, vGRF_freq, Lat_Malleoli_Marker_Right,
-                Lat_Malleoli_Marker_Left,
-                Med_Malleoli_Marker_Right, Med_Malleoli_Marker_Left, Second_Meta_Head_Marker_Right,
-                Second_Meta_Head_Marker_Left, Fifth_Meta_Head_Marker_Right, Fifth_Meta_Head_Marker_Left,
-                Heel_Marker_Right, Heel_Marker_Left, Marker_freq, dominant_leg_length, belt_speed,
-                show=False) -> np.ndarray:
+        # [[1,2,2, ML X][6,5,4, AP Y][0,0,0, None USe Z]]
         # TODO Adam: Do your magic
         """MLcMoS estimation.
 
         This function estimates and plot the continuous mediolateral margin of stability from processed (i.e., reconstructed, filled, filtered, ...)
         COM, vGRF and markers time series data. The cMoS is defined as the continuous distance between the boundary of the base of support and the
         extrapolated position of the body COM.
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics/plot.py` & `gaitalytics-0.0.7b0/src/gaitalytics/plot.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,14 +6,15 @@
 from typing import List
 
 from matplotlib import pyplot as plt
 from matplotlib.axes import Axes
 from matplotlib.backends.backend_pdf import PdfPages
 from matplotlib.figure import Figure
 from pandas import DataFrame
+
 import gaitalytics.utils
 import gaitalytics.c3d
 
 
 
 class PlotGroup(Enum):
     KINEMATICS = "Kinematics"
@@ -104,15 +105,15 @@
                  rows: int = 3):
         super().__init__(configs)
         self.plot_path = plot_path
         self.cols = cols
         self.rows = rows
         self.filename = filename
 
-    def plot(self, results: DataFrame, data_types: List[gaitalytics.c3d.PointDataType]):
+    def plot(self, results: DataFrame, data_types: List[gaitalytics.utils.PointDataType]):
         with PdfPages(f'{self.plot_path}/{self.filename}') as pdf:
             for data_type in data_types:
                 figures = self._plot_data_type(data_type, results)
                 for figure in figures:
                     figure.set_size_inches(11.69, 8.27)
                     pdf.savefig(figure)
                     plt.close(figure)
@@ -122,15 +123,15 @@
             d['ModDate'] = datetime.today()
 
     def _add_footer_header(self):
         ## TODO headers footers
         pass
 
     @staticmethod
-    def _create_figure(data_type: gaitalytics.c3d.PointDataType) -> Figure:
+    def _create_figure(data_type: gaitalytics.utils.PointDataType) -> Figure:
         figure = plt.figure()
         figure.suptitle(data_type.name)
         figure.subplots_adjust(hspace=0.3, wspace=0.4)
         return figure
 
     def _style_subplot(self, ax: Axes) -> Axes:
         for label in (ax.get_xticklabels() + ax.get_yticklabels()):
```

### Comparing `gaitalytics-0.0.6b0/src/gaitalytics.egg-info/PKG-INFO` & `gaitalytics-0.0.7b0/src/gaitalytics.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gaitalytics
-Version: 0.0.6b0
+Version: 0.0.7b0
 Summary: Library to analyse gait data captured with a mocap system
 Home-page: https://github.com/cereneo-foundation/gait_analysis
 Author: André Böni
 Author-email: andre.boeni@cereneo.foundation
 License: MIT
 Keywords: gait,analysis,c3d,mocap
 Classifier: Programming Language :: Python :: 3
```


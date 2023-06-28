# Comparing `tmp/pyneurosdk2-1.0.5.tar.gz` & `tmp/pyneurosdk2-1.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\pyneurosdk2-1.0.5.tar", last modified: Wed Jun 28 10:06:48 2023, max compression
+gzip compressed data, was "dist\pyneurosdk2-1.0.6.tar", last modified: Wed Jun 28 13:51:39 2023, max compression
```

## Comparing `pyneurosdk2-1.0.5.tar` & `pyneurosdk2-1.0.6.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/
--rw-rw-rw-   0        0        0     1090 2023-04-19 10:44:40.000000 pyneurosdk2-1.0.5/LICENSE
--rw-rw-rw-   0        0        0     9703 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/PKG-INFO
--rw-rw-rw-   0        0        0     9186 2023-05-22 16:32:16.000000 pyneurosdk2-1.0.5/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/neurosdk/
--rw-rw-rw-   0        0        0     6424 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/__cmn_types.py
--rw-rw-rw-   0        0        0        0 2022-11-24 14:53:06.000000 pyneurosdk2-1.0.5/neurosdk/__init__.py
--rw-rw-rw-   0        0        0      219 2023-02-28 10:25:36.000000 pyneurosdk2-1.0.5/neurosdk/__utils.py
--rw-rw-rw-   0        0        0     2228 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/amp_sensor.py
--rw-rw-rw-   0        0        0      456 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/brainbit_black_sensor.py
--rw-rw-rw-   0        0        0     4019 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/brainbit_sensor.py
--rw-rw-rw-   0        0        0    24001 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/callibri_sensor.py
--rw-rw-rw-   0        0        0     9161 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/cmn_types.py
--rw-rw-rw-   0        0        0      809 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/electrode_sensor.py
--rw-rw-rw-   0        0        0     1506 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/envelope_sensor.py
--rw-rw-rw-   0        0        0     5007 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/fpg_sensor.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/neurosdk/libs/
--rw-rw-rw-   0        0        0   716288 2023-06-27 17:10:48.000000 pyneurosdk2-1.0.5/neurosdk/libs/neurosdk2-x32.dll
--rw-rw-rw-   0        0        0   999936 2023-06-27 17:08:39.000000 pyneurosdk2-1.0.5/neurosdk/libs/neurosdk2-x64.dll
--rw-rw-rw-   0        0        0     4334 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/mems_sensor.py
--rw-rw-rw-   0        0        0     1073 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/neuro_smart_sensor.py
--rw-rw-rw-   0        0        0     1792 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/resist_sensor.py
--rw-rw-rw-   0        0        0     1588 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/respiration_sensor.py
--rw-rw-rw-   0        0        0     4478 2023-02-28 10:25:36.000000 pyneurosdk2-1.0.5/neurosdk/sample.py
--rw-rw-rw-   0        0        0     8522 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/scanner.py
--rw-rw-rw-   0        0        0    17383 2023-03-13 10:24:36.000000 pyneurosdk2-1.0.5/neurosdk/sensor.py
--rw-rw-rw-   0        0        0      864 2023-06-28 10:02:47.000000 pyneurosdk2-1.0.5/neurosdk/signal_sensor.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/pyneurosdk2.egg-info/
--rw-rw-rw-   0        0        0     9703 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/pyneurosdk2.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      706 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/pyneurosdk2.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/pyneurosdk2.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        9 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/pyneurosdk2.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 10:06:48.000000 pyneurosdk2-1.0.5/setup.cfg
--rw-rw-rw-   0        0        0     1500 2023-06-28 10:06:39.000000 pyneurosdk2-1.0.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/
+-rw-rw-rw-   0        0        0     1090 2023-04-19 10:44:40.000000 pyneurosdk2-1.0.6/LICENSE
+-rw-rw-rw-   0        0        0     9703 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/PKG-INFO
+-rw-rw-rw-   0        0        0     9186 2023-05-22 16:32:16.000000 pyneurosdk2-1.0.6/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/neurosdk/
+-rw-rw-rw-   0        0        0     6424 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/__cmn_types.py
+-rw-rw-rw-   0        0        0        0 2022-11-24 14:53:06.000000 pyneurosdk2-1.0.6/neurosdk/__init__.py
+-rw-rw-rw-   0        0        0      219 2023-02-28 10:25:36.000000 pyneurosdk2-1.0.6/neurosdk/__utils.py
+-rw-rw-rw-   0        0        0     2228 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/amp_sensor.py
+-rw-rw-rw-   0        0        0      456 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/brainbit_black_sensor.py
+-rw-rw-rw-   0        0        0     4019 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/brainbit_sensor.py
+-rw-rw-rw-   0        0        0    24000 2023-06-28 13:49:56.000000 pyneurosdk2-1.0.6/neurosdk/callibri_sensor.py
+-rw-rw-rw-   0        0        0     9161 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/cmn_types.py
+-rw-rw-rw-   0        0        0      809 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/electrode_sensor.py
+-rw-rw-rw-   0        0        0     1506 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/envelope_sensor.py
+-rw-rw-rw-   0        0        0     5007 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/fpg_sensor.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/neurosdk/libs/
+-rw-rw-rw-   0        0        0   716288 2023-06-27 17:10:48.000000 pyneurosdk2-1.0.6/neurosdk/libs/neurosdk2-x32.dll
+-rw-rw-rw-   0        0        0   999936 2023-06-27 17:08:39.000000 pyneurosdk2-1.0.6/neurosdk/libs/neurosdk2-x64.dll
+-rw-rw-rw-   0        0        0     4334 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/mems_sensor.py
+-rw-rw-rw-   0        0        0     1073 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/neuro_smart_sensor.py
+-rw-rw-rw-   0        0        0     1792 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/resist_sensor.py
+-rw-rw-rw-   0        0        0     1588 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/respiration_sensor.py
+-rw-rw-rw-   0        0        0     4478 2023-02-28 10:25:36.000000 pyneurosdk2-1.0.6/neurosdk/sample.py
+-rw-rw-rw-   0        0        0     8522 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/scanner.py
+-rw-rw-rw-   0        0        0    17383 2023-03-13 10:24:36.000000 pyneurosdk2-1.0.6/neurosdk/sensor.py
+-rw-rw-rw-   0        0        0      864 2023-06-28 13:48:39.000000 pyneurosdk2-1.0.6/neurosdk/signal_sensor.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/pyneurosdk2.egg-info/
+-rw-rw-rw-   0        0        0     9703 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/pyneurosdk2.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      706 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/pyneurosdk2.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/pyneurosdk2.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/pyneurosdk2.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:51:39.000000 pyneurosdk2-1.0.6/setup.cfg
+-rw-rw-rw-   0        0        0     1500 2023-06-28 13:50:16.000000 pyneurosdk2-1.0.6/setup.py
```

### Comparing `pyneurosdk2-1.0.5/LICENSE` & `pyneurosdk2-1.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/PKG-INFO` & `pyneurosdk2-1.0.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyneurosdk2
-Version: 1.0.5
+Version: 1.0.6
 Summary: Python wrapper for NeuroSDK2
 Home-page: https://gitlab.com/brainbit-inc/brainbit-sdk
 Author: Brainbit Inc.
 Author-email: support@brainbit.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pyneurosdk2-1.0.5/README.md` & `pyneurosdk2-1.0.6/README.md`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/__cmn_types.py` & `pyneurosdk2-1.0.6/neurosdk/__cmn_types.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/amp_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/amp_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/brainbit_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/brainbit_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/callibri_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/callibri_sensor.py`

 * *Files 0% similar despite different names*

```diff
@@ -152,15 +152,15 @@
         raise_exception_if(status)
         return [SensorFilter(filters_out[i]) for i in range(sz_filters_in_out.contents.value)]
 
     @hardware_filters.setter
     def hardware_filters(self, filters: list):
         status = OpStatus()
         filters_len = len(filters)
-        filters_values = (c_ubyte * filters_len)(*[filters[i].value for i in range(filters_len)])
+        filters_values = (c_int8 * filters_len)(*[filters[i].value for i in range(filters_len)])
         _neuro_lib.writeHardwareFiltersSensor(self.sensor_ptr, filters_values, filters_len, byref(status))
         raise_exception_if(status)
 
     @Sensor.data_offset.setter
     def data_offset(self, do: SensorDataOffset):
         status = OpStatus()
         _neuro_lib.writeDataOffsetSensor(self.sensor_ptr, do.value, byref(status))
```

### Comparing `pyneurosdk2-1.0.5/neurosdk/cmn_types.py` & `pyneurosdk2-1.0.6/neurosdk/cmn_types.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/electrode_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/electrode_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/envelope_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/envelope_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/fpg_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/fpg_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/libs/neurosdk2-x32.dll` & `pyneurosdk2-1.0.6/neurosdk/libs/neurosdk2-x32.dll`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/libs/neurosdk2-x64.dll` & `pyneurosdk2-1.0.6/neurosdk/libs/neurosdk2-x64.dll`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/mems_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/mems_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/neuro_smart_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/neuro_smart_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/resist_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/resist_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/respiration_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/respiration_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/sample.py` & `pyneurosdk2-1.0.6/neurosdk/sample.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/scanner.py` & `pyneurosdk2-1.0.6/neurosdk/scanner.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/sensor.py` & `pyneurosdk2-1.0.6/neurosdk/sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/neurosdk/signal_sensor.py` & `pyneurosdk2-1.0.6/neurosdk/signal_sensor.py`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/pyneurosdk2.egg-info/PKG-INFO` & `pyneurosdk2-1.0.6/pyneurosdk2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyneurosdk2
-Version: 1.0.5
+Version: 1.0.6
 Summary: Python wrapper for NeuroSDK2
 Home-page: https://gitlab.com/brainbit-inc/brainbit-sdk
 Author: Brainbit Inc.
 Author-email: support@brainbit.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pyneurosdk2-1.0.5/pyneurosdk2.egg-info/SOURCES.txt` & `pyneurosdk2-1.0.6/pyneurosdk2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pyneurosdk2-1.0.5/setup.py` & `pyneurosdk2-1.0.6/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setup(
     name='pyneurosdk2',
-    version='1.0.5',
+    version='1.0.6',
     py_modules=[
         'neurosdk.scanner',
         'neurosdk.sensor',
         'neurosdk.cmn_types',
         'neurosdk.__cmn_types',
         'neurosdk.__utils',
         'neurosdk.amp_sensor',
```


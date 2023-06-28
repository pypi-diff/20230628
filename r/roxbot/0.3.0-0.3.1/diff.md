# Comparing `tmp/roxbot-0.3.0.tar.gz` & `tmp/roxbot-0.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "roxbot-0.3.0.tar", last modified: Fri Jun  2 16:42:03 2023, max compression
+gzip compressed data, was "roxbot-0.3.1.tar", last modified: Wed Jun 28 16:13:34 2023, max compression
```

## Comparing `roxbot-0.3.0.tar` & `roxbot-0.3.1.tar`

### file list

```diff
@@ -1,29 +1,40 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-02 16:42:03.532494 roxbot-0.3.0/
--rw-rw-rw-   0 root         (0) root         (0)     1081 2023-06-02 16:41:54.000000 roxbot-0.3.0/LICENCE
--rw-r--r--   0 root         (0) root         (0)      382 2023-06-02 16:42:03.533494 roxbot-0.3.0/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     1734 2023-06-02 16:41:54.000000 roxbot-0.3.0/README.md
--rw-rw-rw-   0 root         (0) root         (0)      360 2023-06-02 16:42:03.533494 roxbot-0.3.0/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)     1487 2023-06-02 16:41:54.000000 roxbot-0.3.0/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-02 16:42:03.528494 roxbot-0.3.0/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-02 16:42:03.530494 roxbot-0.3.0/src/roxbot/
--rw-rw-rw-   0 root         (0) root         (0)       22 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      302 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/cli.py
--rw-rw-rw-   0 root         (0) root         (0)     5874 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/gps.py
--rw-rw-rw-   0 root         (0) root         (0)      337 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/interfaces.py
--rw-rw-rw-   0 root         (0) root         (0)     4913 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/models.py
--rw-rw-rw-   0 root         (0) root         (0)      209 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/utils.py
--rw-rw-rw-   0 root         (0) root         (0)     5020 2023-06-02 16:41:54.000000 roxbot-0.3.0/src/roxbot/vectors.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-02 16:42:03.531494 roxbot-0.3.0/src/roxbot.egg-info/
--rw-r--r--   0 root         (0) root         (0)      382 2023-06-02 16:42:03.000000 roxbot-0.3.0/src/roxbot.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      513 2023-06-02 16:42:03.000000 roxbot-0.3.0/src/roxbot.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-02 16:42:03.000000 roxbot-0.3.0/src/roxbot.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       42 2023-06-02 16:42:03.000000 roxbot-0.3.0/src/roxbot.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)       22 2023-06-02 16:42:03.000000 roxbot-0.3.0/src/roxbot.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        7 2023-06-02 16:42:03.000000 roxbot-0.3.0/src/roxbot.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-02 16:42:03.532494 roxbot-0.3.0/tests/
--rw-rw-rw-   0 root         (0) root         (0)      462 2023-06-02 16:41:54.000000 roxbot-0.3.0/tests/test_cli.py
--rw-rw-rw-   0 root         (0) root         (0)     2780 2023-06-02 16:41:54.000000 roxbot-0.3.0/tests/test_gps.py
--rw-rw-rw-   0 root         (0) root         (0)      103 2023-06-02 16:41:54.000000 roxbot-0.3.0/tests/test_interfaces.py
--rw-rw-rw-   0 root         (0) root         (0)     2070 2023-06-02 16:41:54.000000 roxbot-0.3.0/tests/test_models.py
--rw-rw-rw-   0 root         (0) root         (0)     1591 2023-06-02 16:41:54.000000 roxbot-0.3.0/tests/test_trike.py
--rw-rw-rw-   0 root         (0) root         (0)     2781 2023-06-02 16:41:54.000000 roxbot-0.3.0/tests/test_vectors.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.818577 roxbot-0.3.1/
+-rw-rw-rw-   0 root         (0) root         (0)     1081 2023-06-28 16:13:23.000000 roxbot-0.3.1/LICENCE
+-rw-r--r--   0 root         (0) root         (0)      382 2023-06-28 16:13:34.818577 roxbot-0.3.1/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     1734 2023-06-28 16:13:23.000000 roxbot-0.3.1/README.md
+-rw-rw-rw-   0 root         (0) root         (0)      360 2023-06-28 16:13:34.819578 roxbot-0.3.1/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)     1570 2023-06-28 16:13:23.000000 roxbot-0.3.1/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.811578 roxbot-0.3.1/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.814577 roxbot-0.3.1/src/roxbot/
+-rw-rw-rw-   0 root         (0) root         (0)       22 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1095 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/base_classes.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.816578 roxbot-0.3.1/src/roxbot/bridges/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/bridges/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4917 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/bridges/web_bridge.py
+-rw-rw-rw-   0 root         (0) root         (0)      302 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/cli.py
+-rw-rw-rw-   0 root         (0) root         (0)     5874 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/gps.py
+-rw-rw-rw-   0 root         (0) root         (0)      337 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/interfaces.py
+-rw-rw-rw-   0 root         (0) root         (0)     5514 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/models.py
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/py.typed
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.816578 roxbot-0.3.1/src/roxbot/simulators/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/simulators/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1809 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/simulators/trike.py
+-rw-rw-rw-   0 root         (0) root         (0)      209 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     5020 2023-06-28 16:13:23.000000 roxbot-0.3.1/src/roxbot/vectors.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.816578 roxbot-0.3.1/src/roxbot.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      382 2023-06-28 16:13:34.000000 roxbot-0.3.1/src/roxbot.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      770 2023-06-28 16:13:34.000000 roxbot-0.3.1/src/roxbot.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 16:13:34.000000 roxbot-0.3.1/src/roxbot.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       42 2023-06-28 16:13:34.000000 roxbot-0.3.1/src/roxbot.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 16:13:26.000000 roxbot-0.3.1/src/roxbot.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)       55 2023-06-28 16:13:34.000000 roxbot-0.3.1/src/roxbot.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        7 2023-06-28 16:13:34.000000 roxbot-0.3.1/src/roxbot.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 16:13:34.818577 roxbot-0.3.1/tests/
+-rw-rw-rw-   0 root         (0) root         (0)      462 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_cli.py
+-rw-rw-rw-   0 root         (0) root         (0)     2780 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_gps.py
+-rw-rw-rw-   0 root         (0) root         (0)      103 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_interfaces.py
+-rw-rw-rw-   0 root         (0) root         (0)     2070 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_models.py
+-rw-rw-rw-   0 root         (0) root         (0)     1591 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_trike.py
+-rw-rw-rw-   0 root         (0) root         (0)      748 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_trike_sim.py
+-rw-rw-rw-   0 root         (0) root         (0)     2781 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_vectors.py
+-rw-rw-rw-   0 root         (0) root         (0)     1982 2023-06-28 16:13:23.000000 roxbot-0.3.1/tests/test_ws_bridge.py
```

### Comparing `roxbot-0.3.0/LICENCE` & `roxbot-0.3.1/LICENCE`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/README.md` & `roxbot-0.3.1/README.md`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/setup.py` & `roxbot-0.3.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,15 +22,15 @@
             delim = '"' if '"' in line else "'"
             return line.split(delim)[1]
         else:
             raise RuntimeError("Unable to find version string.")
 
 
 # please keep this lean and mean. Add dev requirements to .devcontainer/requirments.txt
-requirements = ["click", "pymap3d", "pynmea2"]
+requirements = ["click", "pymap3d", "pynmea2", "websockets", "asyncio-mqtt", "pydantic"]
 
 test_requirements = [
     "pytest>=3",
 ]
 
 setup(
     author="ROX Autmation",
@@ -49,10 +49,11 @@
     name="roxbot",
     package_dir={"": "src"},
     packages=find_packages("src"),
     test_suite="tests",
     tests_require=test_requirements,
     url="",
     version=get_version("src/roxbot/__init__.py"),
-    # zip_safe=False,
+    zip_safe=False,
+    package_data={"roxbot": ["py.typed"]},
     entry_points={"console_scripts": ["roxbot=roxbot.cli:cli"]},
 )
```

### Comparing `roxbot-0.3.0/src/roxbot/gps.py` & `roxbot-0.3.1/src/roxbot/gps.py`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/src/roxbot/models.py` & `roxbot-0.3.1/src/roxbot/models.py`

 * *Files 13% similar despite different names*

```diff
@@ -107,22 +107,40 @@
     def step(self, dt: float) -> None:
         self._model.step(dt)
         self.revolutions += self.rps * dt
         self.time += dt
 
 
 class TrikeModel:
-    """Kinematic model of a trike
+    """
+    ## Kinematic model of a trike
+
+
+    Trike model is a combination of a bycicle and and a differential drive kinematic models.
+
+    Key features are:
+
+    * the path curvature is governed by steering wheel
+    * movement command interface is `(velocity,steering angle)`
+    * differential speeds for the driving wheels are calculated from the driving curvature.
+
+
+    !!! note
+        The steering wheel axle can be behind driving wheels resulting in rear wheel steering
+        To achieve this, use negative `L` value.
+
+
+    ### Geometry
 
-    for interactive geometry see: https://www.geogebra.org/calculator/rea6w9a2
+    !!! note
+        Axes in Geogebra model are different from the ones used in this model.
+        This model uses right handed coordinate system with x-axis pointing forward, y-axis pointing to the left and z-axis pointing up.
 
-    **note** : axis directions in geogebra model are different from the ones used here.
+    <iframe src="https://www.geogebra.org/calculator/rea6w9a2?embed" width="800" height="800" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>
 
-    The driving curvature is determined by the angle of the steering wheel.
-    Differential speeds for the driving wheels are calculated from the driving curvature.
 
     """
 
     __slots__ = ("L", "B", "wheel_diameter", "_steering_angle", "_velocity")
 
     def __init__(
         self, L: float = 1.0, B: float = 0.8, wheel_diameter: float = 0.4
```

### Comparing `roxbot-0.3.0/src/roxbot/vectors.py` & `roxbot-0.3.1/src/roxbot/vectors.py`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/src/roxbot.egg-info/SOURCES.txt` & `roxbot-0.3.1/src/roxbot.egg-info/SOURCES.txt`

 * *Files 24% similar despite different names*

```diff
@@ -1,23 +1,32 @@
 LICENCE
 README.md
 setup.cfg
 setup.py
 src/roxbot/__init__.py
+src/roxbot/base_classes.py
 src/roxbot/cli.py
 src/roxbot/gps.py
 src/roxbot/interfaces.py
 src/roxbot/models.py
+src/roxbot/py.typed
 src/roxbot/utils.py
 src/roxbot/vectors.py
 src/roxbot.egg-info/PKG-INFO
 src/roxbot.egg-info/SOURCES.txt
 src/roxbot.egg-info/dependency_links.txt
 src/roxbot.egg-info/entry_points.txt
+src/roxbot.egg-info/not-zip-safe
 src/roxbot.egg-info/requires.txt
 src/roxbot.egg-info/top_level.txt
+src/roxbot/bridges/__init__.py
+src/roxbot/bridges/web_bridge.py
+src/roxbot/simulators/__init__.py
+src/roxbot/simulators/trike.py
 tests/test_cli.py
 tests/test_gps.py
 tests/test_interfaces.py
 tests/test_models.py
 tests/test_trike.py
-tests/test_vectors.py
+tests/test_trike_sim.py
+tests/test_vectors.py
+tests/test_ws_bridge.py
```

### Comparing `roxbot-0.3.0/tests/test_gps.py` & `roxbot-0.3.1/tests/test_gps.py`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/tests/test_models.py` & `roxbot-0.3.1/tests/test_models.py`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/tests/test_trike.py` & `roxbot-0.3.1/tests/test_trike.py`

 * *Files identical despite different names*

### Comparing `roxbot-0.3.0/tests/test_vectors.py` & `roxbot-0.3.1/tests/test_vectors.py`

 * *Files identical despite different names*


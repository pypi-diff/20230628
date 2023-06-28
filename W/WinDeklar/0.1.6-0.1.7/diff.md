# Comparing `tmp/windeklar-0.1.6.tar.gz` & `tmp/windeklar-0.1.7.tar.gz`

## Comparing `windeklar-0.1.6.tar` & `windeklar-0.1.7.tar`

### file list

```diff
@@ -1,31 +1,31 @@
--rw-r--r--   0        0        0       78 2020-02-02 00:00:00.000000 windeklar-0.1.6/requirements.txt
--rw-r--r--   0        0        0      491 2020-02-02 00:00:00.000000 windeklar-0.1.6/setup.py
--rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 windeklar-0.1.6/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0       47 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/.gitignore
--rw-r--r--   0        0        0        9 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/.name
--rw-r--r--   0        0        0      385 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/WinDeklar.iml
--rw-r--r--   0        0        0      199 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/misc.xml
--rw-r--r--   0        0        0      296 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/modules.xml
--rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/vcs.xml
--rw-r--r--   0        0        0     1237 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 windeklar-0.1.6/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/__init__.py
--rwxr-xr-x   0        0        0    15884 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/QTAux.py
--rw-r--r--   0        0        0    43483 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/WindowForm.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/__init__.py
--rw-r--r--   0        0        0     3901 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/graph_aux.py
--rw-r--r--   0        0        0     2280 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/points_box.py
--rw-r--r--   0        0        0     3485 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/record.py
--rw-r--r--   0        0        0     4241 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/signal_aux.py
--rw-r--r--   0        0        0     4228 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/test_animation.py
--rw-r--r--   0        0        0     3376 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/test_pyqt.py
--rw-r--r--   0        0        0     2456 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/view_animation.py
--rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/view_animation.yaml
--rw-r--r--   0        0        0     5762 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/view_example.py
--rw-r--r--   0        0        0     3698 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/view_example.yaml
--rw-r--r--   0        0        0      798 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/view_simple_graph.py
--rwxr-xr-x   0        0        0     6638 2020-02-02 00:00:00.000000 windeklar-0.1.6/src/WinDeklar/yaml_functions.py
--rw-r--r--   0        0        0     1070 2020-02-02 00:00:00.000000 windeklar-0.1.6/LICENSE
--rw-r--r--   0        0        0     1144 2020-02-02 00:00:00.000000 windeklar-0.1.6/README.md
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 windeklar-0.1.6/pyproject.toml
--rw-r--r--   0        0        0     1700 2020-02-02 00:00:00.000000 windeklar-0.1.6/PKG-INFO
+-rw-r--r--   0        0        0       78 2020-02-02 00:00:00.000000 windeklar-0.1.7/requirements.txt
+-rw-r--r--   0        0        0      491 2020-02-02 00:00:00.000000 windeklar-0.1.7/setup.py
+-rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 windeklar-0.1.7/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0       47 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/.gitignore
+-rw-r--r--   0        0        0        9 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/.name
+-rw-r--r--   0        0        0      385 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/WinDeklar.iml
+-rw-r--r--   0        0        0      199 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/misc.xml
+-rw-r--r--   0        0        0      296 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/modules.xml
+-rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/vcs.xml
+-rw-r--r--   0        0        0     1237 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/inspectionProfiles/Project_Default.xml
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 windeklar-0.1.7/.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/__init__.py
+-rwxr-xr-x   0        0        0    15884 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/QTAux.py
+-rw-r--r--   0        0        0    43580 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/WindowForm.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/__init__.py
+-rw-r--r--   0        0        0     3901 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/graph_aux.py
+-rw-r--r--   0        0        0     2280 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/points_box.py
+-rw-r--r--   0        0        0     3485 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/record.py
+-rw-r--r--   0        0        0     4241 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/signal_aux.py
+-rw-r--r--   0        0        0     4228 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/test_animation.py
+-rw-r--r--   0        0        0     3376 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/test_pyqt.py
+-rw-r--r--   0        0        0     2456 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/view_animation.py
+-rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/view_animation.yaml
+-rw-r--r--   0        0        0     5762 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/view_example.py
+-rw-r--r--   0        0        0     3712 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/view_example.yaml
+-rw-r--r--   0        0        0      798 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/view_simple_graph.py
+-rwxr-xr-x   0        0        0     6638 2020-02-02 00:00:00.000000 windeklar-0.1.7/src/WinDeklar/yaml_functions.py
+-rw-r--r--   0        0        0     1070 2020-02-02 00:00:00.000000 windeklar-0.1.7/LICENSE
+-rw-r--r--   0        0        0     1144 2020-02-02 00:00:00.000000 windeklar-0.1.7/README.md
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 windeklar-0.1.7/pyproject.toml
+-rw-r--r--   0        0        0     1700 2020-02-02 00:00:00.000000 windeklar-0.1.7/PKG-INFO
```

### Comparing `windeklar-0.1.6/.github/workflows/python-publish.yml` & `windeklar-0.1.7/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/.idea/inspectionProfiles/Project_Default.xml` & `windeklar-0.1.7/.idea/inspectionProfiles/Project_Default.xml`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/QTAux.py` & `windeklar-0.1.7/src/WinDeklar/QTAux.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/WindowForm.py` & `windeklar-0.1.7/src/WinDeklar/WindowForm.py`

 * *Files 0% similar despite different names*

```diff
@@ -212,14 +212,15 @@
         axes_limits = self.parent.provider.axes_limits()
         if axes_limits is not None:
             self.x_lower, self.x_upper, self.y_lower, self.y_upper = axes_limits
         self.axes.set_xbound(lower=self.x_lower, upper=self.x_upper)
         self.axes.set_ybound(lower=self.y_lower, upper=self.y_upper)
         self.axes.get_xaxis().set_visible(self.x_visible)
         self.axes.get_yaxis().set_visible(self.y_visible)
+        self.axes.set_ylabel(' ', fontsize=20)  # quick fix to assure y values fit in the figure
 
     def onclick(self, event):
         self.parent.provider.on_mouse_click(event, self.axes, self)
         self.set_axis()
         self.draw()
 
     def on_mouse_move(self, event):
```

### Comparing `windeklar-0.1.6/src/WinDeklar/graph_aux.py` & `windeklar-0.1.7/src/WinDeklar/graph_aux.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/points_box.py` & `windeklar-0.1.7/src/WinDeklar/points_box.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/record.py` & `windeklar-0.1.7/src/WinDeklar/record.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/signal_aux.py` & `windeklar-0.1.7/src/WinDeklar/signal_aux.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/test_animation.py` & `windeklar-0.1.7/src/WinDeklar/test_animation.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/test_pyqt.py` & `windeklar-0.1.7/src/WinDeklar/test_pyqt.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/view_animation.py` & `windeklar-0.1.7/src/WinDeklar/view_animation.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/view_animation.yaml` & `windeklar-0.1.7/src/WinDeklar/view_animation.yaml`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/view_example.py` & `windeklar-0.1.7/src/WinDeklar/view_example.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/view_example.yaml` & `windeklar-0.1.7/src/WinDeklar/view_example.yaml`

 * *Files 2% similar despite different names*

```diff
@@ -96,21 +96,21 @@
                           type:    Slider
                           parms:   [2, 100, 1]      # [min_value, max_value, scale]
                           value:   20
                       - control:
                           name:    line_width
                           title:   Line Width
                           type:    EditNumberSpin
-                          parms:   {step: 1.0}
+                          parms:   {step: 1.0, maximum: 10}
                           value:   1.0
                       - control:
                           name:    redraw
                           title:   Draw again
                           type:    Button
                           action:  redraw   # method to call
 
                 - item:
                     name:    graph
                     type:    figure
                     subtype: graph
-                    view_size: [10, 10]
+                    view_size: [100, 10]
```

### Comparing `windeklar-0.1.6/src/WinDeklar/view_simple_graph.py` & `windeklar-0.1.7/src/WinDeklar/view_simple_graph.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/src/WinDeklar/yaml_functions.py` & `windeklar-0.1.7/src/WinDeklar/yaml_functions.py`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/LICENSE` & `windeklar-0.1.7/LICENSE`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/README.md` & `windeklar-0.1.7/README.md`

 * *Files identical despite different names*

### Comparing `windeklar-0.1.6/pyproject.toml` & `windeklar-0.1.7/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name    = "WinDeklar"
-version = "0.1.6"
+version = "0.1.7"
 authors = [
   { name="Nicolas Jodal", email="jnj@genexus.com" },
 ]
 description = "Create winforms in an easy, declarative way. Specially suited for Robotics applications"
 readme      = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `windeklar-0.1.6/PKG-INFO` & `windeklar-0.1.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WinDeklar
-Version: 0.1.6
+Version: 0.1.7
 Summary: Create winforms in an easy, declarative way. Specially suited for Robotics applications
 Project-URL: Homepage, https://github.com/njodal/WinDeklar
 Project-URL: Bug Tracker, https://github.com/njodal/WinDeklar/issues
 Author-email: Nicolas Jodal <jnj@genexus.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```


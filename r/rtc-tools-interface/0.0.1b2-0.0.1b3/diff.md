# Comparing `tmp/rtc-tools-interface-0.0.1b2.tar.gz` & `tmp/rtc-tools-interface-0.0.1b3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rtc-tools-interface-0.0.1b2.tar", last modified: Tue Jun 27 13:43:06 2023, max compression
+gzip compressed data, was "rtc-tools-interface-0.0.1b3.tar", last modified: Wed Jun 28 09:45:25 2023, max compression
```

## Comparing `rtc-tools-interface-0.0.1b2.tar` & `rtc-tools-interface-0.0.1b3.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 13:43:06.155802 rtc-tools-interface-0.0.1b2/
--rw-rw-rw-   0 root         (0) root         (0)     7652 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/COPYING.LESSER
--rw-r--r--   0 root         (0) root         (0)      270 2023-06-27 13:43:06.155802 rtc-tools-interface-0.0.1b2/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     3906 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 13:43:06.152802 rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/
--rw-r--r--   0 root         (0) root         (0)      270 2023-06-27 13:43:06.000000 rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      903 2023-06-27 13:43:06.000000 rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 13:43:06.000000 rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       41 2023-06-27 13:43:06.000000 rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       25 2023-06-27 13:43:06.000000 rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 13:43:06.155802 rtc-tools-interface-0.0.1b2/rtctools_interface/
--rw-rw-rw-   0 root         (0) root         (0)       73 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/__init__.py
--rw-r--r--   0 root         (0) root         (0)      499 2023-06-27 13:43:06.155802 rtc-tools-interface-0.0.1b2/rtctools_interface/_version.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 13:43:06.153802 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     4440 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/base_goal.py
--rw-rw-rw-   0 root         (0) root         (0)      928 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/base_optimization_problem.py
--rw-rw-rw-   0 root         (0) root         (0)     1055 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/goal_generator_mixin.py
--rw-rw-rw-   0 root         (0) root         (0)     6698 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/plot_goals_mixin.py
--rw-rw-rw-   0 root         (0) root         (0)      483 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/read_goals.py
--rw-rw-rw-   0 root         (0) root         (0)     1065 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/read_plot_table.py
--rw-rw-rw-   0 root         (0) root         (0)      285 2023-06-27 13:43:06.155802 rtc-tools-interface-0.0.1b2/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)      548 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 13:43:06.153802 rtc-tools-interface-0.0.1b2/tests/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/tests/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 13:43:06.154802 rtc-tools-interface-0.0.1b2/tests/optimization/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/tests/optimization/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      805 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/tests/optimization/get_test.py
--rw-rw-rw-   0 root         (0) root         (0)      844 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/tests/optimization/test_base_optimization_problem.py
--rw-rw-rw-   0 root         (0) root         (0)     1275 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/tests/optimization/test_plot_goals_mixin.py
--rw-rw-rw-   0 root         (0) root         (0)      386 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/tests/optimization/test_read_goals.py
--rw-rw-rw-   0 root         (0) root         (0)    83607 2023-06-27 13:43:04.000000 rtc-tools-interface-0.0.1b2/versioneer.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:45:25.194712 rtc-tools-interface-0.0.1b3/
+-rw-rw-rw-   0 root         (0) root         (0)     7652 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/COPYING.LESSER
+-rw-r--r--   0 root         (0) root         (0)      270 2023-06-28 09:45:25.194712 rtc-tools-interface-0.0.1b3/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     3906 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:45:25.191712 rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      270 2023-06-28 09:45:25.000000 rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      903 2023-06-28 09:45:25.000000 rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 09:45:25.000000 rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       41 2023-06-28 09:45:25.000000 rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       25 2023-06-28 09:45:25.000000 rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:45:25.195712 rtc-tools-interface-0.0.1b3/rtctools_interface/
+-rw-rw-rw-   0 root         (0) root         (0)       73 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      499 2023-06-28 09:45:25.195712 rtc-tools-interface-0.0.1b3/rtctools_interface/_version.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:45:25.193713 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4440 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/base_goal.py
+-rw-rw-rw-   0 root         (0) root         (0)      928 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/base_optimization_problem.py
+-rw-rw-rw-   0 root         (0) root         (0)     1106 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/goal_generator_mixin.py
+-rw-rw-rw-   0 root         (0) root         (0)     6698 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/plot_goals_mixin.py
+-rw-rw-rw-   0 root         (0) root         (0)      483 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/read_goals.py
+-rw-rw-rw-   0 root         (0) root         (0)     1065 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/read_plot_table.py
+-rw-rw-rw-   0 root         (0) root         (0)      285 2023-06-28 09:45:25.194712 rtc-tools-interface-0.0.1b3/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)      548 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:45:25.193713 rtc-tools-interface-0.0.1b3/tests/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/tests/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:45:25.194712 rtc-tools-interface-0.0.1b3/tests/optimization/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/tests/optimization/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      805 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/tests/optimization/get_test.py
+-rw-rw-rw-   0 root         (0) root         (0)      844 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/tests/optimization/test_base_optimization_problem.py
+-rw-rw-rw-   0 root         (0) root         (0)     1275 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/tests/optimization/test_plot_goals_mixin.py
+-rw-rw-rw-   0 root         (0) root         (0)      386 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/tests/optimization/test_read_goals.py
+-rw-rw-rw-   0 root         (0) root         (0)    83607 2023-06-28 09:45:23.000000 rtc-tools-interface-0.0.1b3/versioneer.py
```

### Comparing `rtc-tools-interface-0.0.1b2/COPYING.LESSER` & `rtc-tools-interface-0.0.1b3/COPYING.LESSER`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/README.md` & `rtc-tools-interface-0.0.1b3/README.md`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/rtc_tools_interface.egg-info/SOURCES.txt` & `rtc-tools-interface-0.0.1b3/rtc_tools_interface.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/base_goal.py` & `rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/base_goal.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/base_optimization_problem.py` & `rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/base_optimization_problem.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/goal_generator_mixin.py` & `rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/goal_generator_mixin.py`

 * *Files 8% similar despite different names*

```diff
@@ -23,10 +23,11 @@
             self.goal_table_file = os.path.join(self._input_folder, "goal_table.csv")
 
     def _goal_data_to_goal(self, goal_data: pd.Series):
         """Convert a series with goal data to a BaseGoal."""
         return BaseGoal(optimization_problem=self, **goal_data.to_dict())
 
     def path_goals(self):
+        goals = super().path_goals()
         goal_df = read_goals(self.goal_table_file)
-        goals = goal_df.apply(self._goal_data_to_goal, axis=1)
+        goals = goals + list(goal_df.apply(self._goal_data_to_goal, axis=1))
         return goals
```

### Comparing `rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/plot_goals_mixin.py` & `rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/plot_goals_mixin.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/rtctools_interface/optimization/read_plot_table.py` & `rtc-tools-interface-0.0.1b3/rtctools_interface/optimization/read_plot_table.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/setup.py` & `rtc-tools-interface-0.0.1b3/setup.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/tests/optimization/get_test.py` & `rtc-tools-interface-0.0.1b3/tests/optimization/get_test.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/tests/optimization/test_base_optimization_problem.py` & `rtc-tools-interface-0.0.1b3/tests/optimization/test_base_optimization_problem.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/tests/optimization/test_plot_goals_mixin.py` & `rtc-tools-interface-0.0.1b3/tests/optimization/test_plot_goals_mixin.py`

 * *Files identical despite different names*

### Comparing `rtc-tools-interface-0.0.1b2/versioneer.py` & `rtc-tools-interface-0.0.1b3/versioneer.py`

 * *Files identical despite different names*


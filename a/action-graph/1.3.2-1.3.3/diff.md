# Comparing `tmp/action-graph-1.3.2.tar.gz` & `tmp/action-graph-1.3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "action-graph-1.3.2.tar", last modified: Tue Jun 27 13:38:55 2023, max compression
+gzip compressed data, was "action-graph-1.3.3.tar", last modified: Wed Jun 28 14:35:26 2023, max compression
```

## Comparing `action-graph-1.3.2.tar` & `action-graph-1.3.3.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0     1078 2023-03-10 21:00:20.184864 action-graph-1.3.2/LICENSE
--rw-r--r--   0        0        0     1450 2023-03-10 21:03:34.335982 action-graph-1.3.2/README.md
--rw-r--r--   0        0        0      684 2023-06-27 13:37:46.128375 action-graph-1.3.2/action_graph/__init__.py
--rw-r--r--   0        0        0     3476 2023-06-25 03:34:21.964154 action-graph-1.3.2/action_graph/action.py
--rw-r--r--   0        0        0    10818 2023-06-23 21:27:59.160761 action-graph-1.3.2/action_graph/agent.py
--rw-r--r--   0        0        0     4664 2023-06-25 03:02:12.179040 action-graph-1.3.2/action_graph/planner.py
--rw-r--r--   0        0        0      832 2023-06-27 13:37:54.104349 action-graph-1.3.2/pyproject.toml
--rwxr-xr-x   0        0        0     1103 2023-06-16 14:34:49.765956 action-graph-1.3.2/tests/01-redundant_precon_test.py
--rwxr-xr-x   0        0        0     1039 2023-06-23 21:15:35.619807 action-graph-1.3.2/tests/02-multi_feasible_test.py
--rwxr-xr-x   0        0        0     1284 2023-06-16 14:37:32.454361 action-graph-1.3.2/tests/03-references_test.py
--rwxr-xr-x   0        0        0      909 2023-06-23 20:50:11.922048 action-graph-1.3.2/tests/04-loop_test.py
--rw-r--r--   0        0        0     1988 1970-01-01 00:00:00.000000 action-graph-1.3.2/PKG-INFO
+-rw-r--r--   0        0        0     1078 2023-03-10 21:00:20.184864 action-graph-1.3.3/LICENSE
+-rw-r--r--   0        0        0     1450 2023-03-10 21:03:34.335982 action-graph-1.3.3/README.md
+-rw-r--r--   0        0        0      684 2023-06-28 14:35:08.272045 action-graph-1.3.3/action_graph/__init__.py
+-rw-r--r--   0        0        0     3595 2023-06-28 00:55:07.217794 action-graph-1.3.3/action_graph/action.py
+-rw-r--r--   0        0        0    11552 2023-06-28 01:01:53.944495 action-graph-1.3.3/action_graph/agent.py
+-rw-r--r--   0        0        0     4664 2023-06-25 03:02:12.179040 action-graph-1.3.3/action_graph/planner.py
+-rw-r--r--   0        0        0      832 2023-06-28 14:35:13.504003 action-graph-1.3.3/pyproject.toml
+-rwxr-xr-x   0        0        0     1103 2023-06-16 14:34:49.765956 action-graph-1.3.3/tests/01-redundant_precon_test.py
+-rwxr-xr-x   0        0        0     1039 2023-06-23 21:15:35.619807 action-graph-1.3.3/tests/02-multi_feasible_test.py
+-rwxr-xr-x   0        0        0     1284 2023-06-16 14:37:32.454361 action-graph-1.3.3/tests/03-references_test.py
+-rwxr-xr-x   0        0        0      909 2023-06-23 20:50:11.922048 action-graph-1.3.3/tests/04-loop_test.py
+-rw-r--r--   0        0        0     1988 1970-01-01 00:00:00.000000 action-graph-1.3.3/PKG-INFO
```

### Comparing `action-graph-1.3.2/LICENSE` & `action-graph-1.3.3/LICENSE`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/README.md` & `action-graph-1.3.3/README.md`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/action_graph/__init__.py` & `action-graph-1.3.3/action_graph/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 #! /usr/bin/env python3
 
 from action_graph.action import Action, ActionStatus, State
 from action_graph.agent import Agent
 
 name = 'action_graph'
-__version__ = '1.3.2'
+__version__ = '1.3.3'
 __all__ = [
     'State',
     'Action',
     'ActionStatus',
     'ActionFailedException',
     'ActionAbortedException',
     'ActionTimedOutException',
```

### Comparing `action-graph-1.3.2/action_graph/action.py` & `action-graph-1.3.3/action_graph/action.py`

 * *Files 2% similar despite different names*

```diff
@@ -55,14 +55,17 @@
 
     def on_failure(self, outcome: State = None):
         pass
 
     def on_aborted(self, outcome: State = None):
         pass
 
+    def on_preempted(self, outcome: State = None):
+        pass
+
     def on_neutral(self, outcome: State = None):
         pass
 
     def on_exit(self, outcome: State = None):
         pass
 
     def apply_effects(self, outcome: State, state: State):
@@ -126,7 +129,11 @@
 
 class ActionAbortedException(Exception):
     pass
 
 
 class ActionTimedOutException(Exception):
     pass
+
+
+class ActionPreemptedException(Exception):
+    pass
```

### Comparing `action-graph-1.3.2/action_graph/agent.py` & `action-graph-1.3.3/action_graph/agent.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,23 +1,25 @@
 #! /usr/bin/env python3
 
 import logging
 from time import sleep, time
 from typing import Iterable, List
 
 from action_graph.action import (Action, ActionStatus, State,
-                                 ActionTimedOutException, ActionAbortedException, ActionFailedException)
+                                 ActionTimedOutException, ActionAbortedException, 
+                                 ActionFailedException, ActionPreemptedException)
 from action_graph.planner import Planner, PlanningFailedException
 
 
 class Agent:
     """Autonomous agent to monitor system state, keep track of feasible actions, generate plans and achive desired goals"""
 
     __planner: Planner = Planner([])
     __abort: bool = False
+    __preempted: bool = False
 
     def __init__(self, agent_name=None) -> None:
         if not agent_name:
             agent_name = self.__class__.__name__
         self.name = agent_name
         #
         self.state: State = {}
@@ -45,20 +47,28 @@
     def abort(self):
         """
         Abort execution.
         """
 
         self.__abort = True
 
+    def preempt(self):
+        """
+        Preempt execution.
+        """
+
+        self.__preempted = True
+
     def reset(self):
         """
-        Resets the abort status back to False in the event abort was triggered.
+        Resets the abort/preempt status back to False in the event abort was triggered.
         """
 
         self.__abort = False
+        self.__preempted = False
 
     def is_goal_met(self, goal: State) -> bool:
         """
         Compares the desired goal state against the system state to check if it is already met.
 
         :param goal:State: Desired goal state
         :return:bool: True if goal state and current system state is same; False otherwise
@@ -193,14 +203,19 @@
 
             except ActionFailedException as ex_fail:
                 logging.error(f"{ex_fail} / ATTEMPTING ALTERNATIVE PLAN")
                 if str(first_action) not in blacklisted_actions:
                     blacklisted_actions.append(str(first_action))
                 continue
 
+            except ActionPreemptedException as _ex_preempted:
+                # logging.info(f"{ex_preempted}")
+                self.__preempted = False  # reset preempted status
+                break
+
             except Exception as _ex:
                 logging.error(f"{_ex}")
                 raise
 
         logging.info(f"EXECUTION SUCCEDED!")
 
     def print_plan_to_console(self, plan: List[Action]):
@@ -213,14 +228,20 @@
     def execute_action(self, action: Action):
         # Check for abort status
         if self.__abort:
             # logging.error(f'ACTION: {action} : EXECUTION ABORTED BEFORE START !!')
             action.on_aborted(action.effects)
             raise ActionAbortedException(f'ACTION: {action} FAILED. ABORTED STATE IS ACTIVE!!')
 
+        # Check for preempt status
+        if self.__preempted:
+            # logging.error(f'ACTION: {action} : EXECUTION PREEMPTED BEFORE START !!')
+            action.on_preempted(action.effects)
+            raise ActionPreemptedException(f'EXECUTION PREEMPTED WHILE AT ACTION: {action}')
+
         # Check runtime precondition
         if not action.check_runtime_precondition(action.effects):
             raise ActionFailedException(f'ACTION: {action} RUNTIME PRECONDITION CHECK FAILED!!.')
 
         # Execute the plan step
         action._execute(action.effects)
         # action.execute is an async process inside _execute,
```

### Comparing `action-graph-1.3.2/action_graph/planner.py` & `action-graph-1.3.3/action_graph/planner.py`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/pyproject.toml` & `action-graph-1.3.3/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 [project]
 authors = [
     { name = "Bharath Achyutha Rao", email = "bharath.rao@hotmail.com" },
 ]
 name = "action_graph"
-version = "1.3.2"
+version = "1.3.3"
 description = "Autonomous agent for task/action planning and execution"
 readme = "README.md"
 requires-python = ">=3.7,<4.0"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
```

### Comparing `action-graph-1.3.2/tests/01-redundant_precon_test.py` & `action-graph-1.3.3/tests/01-redundant_precon_test.py`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/tests/02-multi_feasible_test.py` & `action-graph-1.3.3/tests/02-multi_feasible_test.py`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/tests/03-references_test.py` & `action-graph-1.3.3/tests/03-references_test.py`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/tests/04-loop_test.py` & `action-graph-1.3.3/tests/04-loop_test.py`

 * *Files identical despite different names*

### Comparing `action-graph-1.3.2/PKG-INFO` & `action-graph-1.3.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: action_graph
-Version: 1.3.2
+Version: 1.3.3
 Summary: Autonomous agent for task/action planning and execution
 Author-email: Bharath Achyutha Rao <bharath.rao@hotmail.com>
 Requires-Python: >=3.7,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Project-URL: Bug Tracker, https://github.com/bharathra/action_graph/issues
```


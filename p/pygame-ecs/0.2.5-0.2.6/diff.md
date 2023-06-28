# Comparing `tmp/pygame_ecs-0.2.5.tar.gz` & `tmp/pygame_ecs-0.2.6.tar.gz`

## Comparing `pygame_ecs-0.2.5.tar` & `pygame_ecs-0.2.6.tar`

### file list

```diff
@@ -1,20 +1,20 @@
--rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/.gitattributes
--rw-r--r--   0        0        0      435 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/__init__.py
--rw-r--r--   0        0        0      306 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/entity.py
--rw-r--r--   0        0        0      431 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/exceptions.py
--rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/components/base_component.py
--rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/managers/component_manager.py
--rw-r--r--   0        0        0     1976 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/managers/entity_manager.py
--rw-r--r--   0        0        0     1902 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/managers/system_manager.py
--rw-r--r--   0        0        0     1272 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/systems/base_system.py
--rw-r--r--   0        0        0    30680 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/circle.png
--rw-r--r--   0        0        0     2129 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/draw_test.py
--rw-r--r--   0        0        0     4188 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/particle_test_cpu.py
--rw-r--r--   0        0        0     5293 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/particle_test_gpu.py
--rw-r--r--   0        0        0     3275 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/speed_test.py
--rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/tester.py
--rw-r--r--   0        0        0     2940 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/.gitignore
--rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/LICENSE
--rw-r--r--   0        0        0     3654 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/README.md
--rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pyproject.toml
--rw-r--r--   0        0        0     4711 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/PKG-INFO
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/.gitattributes
+-rw-r--r--   0        0        0      435 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/__init__.py
+-rw-r--r--   0        0        0      306 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/entity.py
+-rw-r--r--   0        0        0      431 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/exceptions.py
+-rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/components/base_component.py
+-rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/managers/component_manager.py
+-rw-r--r--   0        0        0     1976 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/managers/entity_manager.py
+-rw-r--r--   0        0        0     1902 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/managers/system_manager.py
+-rw-r--r--   0        0        0     1272 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pygame_ecs/systems/base_system.py
+-rw-r--r--   0        0        0    30680 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/test/circle.png
+-rw-r--r--   0        0        0     2129 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/test/draw_test.py
+-rw-r--r--   0        0        0     4188 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/test/particle_test_cpu.py
+-rw-r--r--   0        0        0     5293 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/test/particle_test_gpu.py
+-rw-r--r--   0        0        0     3275 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/test/speed_test.py
+-rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/test/tester.py
+-rw-r--r--   0        0        0     2940 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/.gitignore
+-rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/LICENSE
+-rw-r--r--   0        0        0     3661 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/README.md
+-rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/pyproject.toml
+-rw-r--r--   0        0        0     4718 2020-02-02 00:00:00.000000 pygame_ecs-0.2.6/PKG-INFO
```

### Comparing `pygame_ecs-0.2.5/pygame_ecs/managers/component_manager.py` & `pygame_ecs-0.2.6/pygame_ecs/managers/component_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/pygame_ecs/managers/entity_manager.py` & `pygame_ecs-0.2.6/pygame_ecs/managers/entity_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/pygame_ecs/managers/system_manager.py` & `pygame_ecs-0.2.6/pygame_ecs/managers/system_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/pygame_ecs/systems/base_system.py` & `pygame_ecs-0.2.6/pygame_ecs/systems/base_system.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/test/circle.png` & `pygame_ecs-0.2.6/test/circle.png`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/test/draw_test.py` & `pygame_ecs-0.2.6/test/draw_test.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/test/particle_test_cpu.py` & `pygame_ecs-0.2.6/test/particle_test_cpu.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/test/particle_test_gpu.py` & `pygame_ecs-0.2.6/test/particle_test_gpu.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/test/speed_test.py` & `pygame_ecs-0.2.6/test/speed_test.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/.gitignore` & `pygame_ecs-0.2.6/.gitignore`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/LICENSE` & `pygame_ecs-0.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.5/README.md` & `pygame_ecs-0.2.6/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -74,15 +74,15 @@
 
 
 class BallDrawSystem(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, BallRenderer])
         self.screen = screen
 
-    def update(self, entity, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]
         ball_renderer: BallRenderer = entity_components[BallRenderer]
         pygame.draw.circle(
             self.screen, ball_renderer.color, (pos.x, pos.y), ball_renderer.radius
         )
```

### Comparing `pygame_ecs-0.2.5/pyproject.toml` & `pygame_ecs-0.2.6/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 
 [project]
 name = "pygame_ecs"
-version = "0.2.5"
+version = "0.2.6"
 authors = [
   { name="Notenlish", email="71970100+Notenlish@users.noreply.github.com" },
 ]
 description = "Pure Python, simple to use Entity Component System(ECS) for pygame"
 packages=["pygame_ecs", "pygame_ecs.components", "pygame_ecs.managers", "pygame_ecs.systems"]
 readme = "README.md"
 requires-python = ">=3.7"
```

### Comparing `pygame_ecs-0.2.5/PKG-INFO` & `pygame_ecs-0.2.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pygame_ecs
-Version: 0.2.5
+Version: 0.2.6
 Summary: Pure Python, simple to use Entity Component System(ECS) for pygame
 Project-URL: Homepage, https://github.com/Notenlish/pygame_ecs
 Project-URL: Bug Tracker, https://github.com/Notenlish/pygame_ecs/issues
 Author-email: Notenlish <71970100+Notenlish@users.noreply.github.com>
 License-Expression: MIT
 License-File: LICENSE
 Keywords: ECS,component,ecs,entity,entity component system,pygame,pygame-ce,pygame_ecs,system
@@ -100,15 +100,15 @@
 
 
 class BallDrawSystem(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, BallRenderer])
         self.screen = screen
 
-    def update(self, entity, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]
         ball_renderer: BallRenderer = entity_components[BallRenderer]
         pygame.draw.circle(
             self.screen, ball_renderer.color, (pos.x, pos.y), ball_renderer.radius
         )
```


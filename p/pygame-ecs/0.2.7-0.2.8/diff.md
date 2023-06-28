# Comparing `tmp/pygame_ecs-0.2.7.tar.gz` & `tmp/pygame_ecs-0.2.8.tar.gz`

## Comparing `pygame_ecs-0.2.7.tar` & `pygame_ecs-0.2.8.tar`

### file list

```diff
@@ -1,20 +1,20 @@
--rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/.gitattributes
--rw-r--r--   0        0        0      435 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/__init__.py
--rw-r--r--   0        0        0      306 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/entity.py
--rw-r--r--   0        0        0      431 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/exceptions.py
--rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/components/base_component.py
--rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/managers/component_manager.py
--rw-r--r--   0        0        0     1976 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/managers/entity_manager.py
--rw-r--r--   0        0        0     1902 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/managers/system_manager.py
--rw-r--r--   0        0        0     1272 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pygame_ecs/systems/base_system.py
--rw-r--r--   0        0        0    30680 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/test/circle.png
--rw-r--r--   0        0        0     2129 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/test/draw_test.py
--rw-r--r--   0        0        0     4188 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/test/particle_test_cpu.py
--rw-r--r--   0        0        0     5294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/test/particle_test_gpu.py
--rw-r--r--   0        0        0     3275 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/test/speed_test.py
--rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/test/tester.py
--rw-r--r--   0        0        0     2940 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/.gitignore
--rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/LICENSE
--rw-r--r--   0        0        0     3661 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/README.md
--rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/pyproject.toml
--rw-r--r--   0        0        0     4718 2020-02-02 00:00:00.000000 pygame_ecs-0.2.7/PKG-INFO
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/.gitattributes
+-rw-r--r--   0        0        0      435 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/__init__.py
+-rw-r--r--   0        0        0      306 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/entity.py
+-rw-r--r--   0        0        0      431 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/exceptions.py
+-rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/components/base_component.py
+-rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/managers/component_manager.py
+-rw-r--r--   0        0        0     1976 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/managers/entity_manager.py
+-rw-r--r--   0        0        0     1902 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/managers/system_manager.py
+-rw-r--r--   0        0        0     1272 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pygame_ecs/systems/base_system.py
+-rw-r--r--   0        0        0    30680 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/test/circle.png
+-rw-r--r--   0        0        0     2129 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/test/draw_test.py
+-rw-r--r--   0        0        0     4188 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/test/particle_test_cpu.py
+-rw-r--r--   0        0        0     5294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/test/particle_test_gpu.py
+-rw-r--r--   0        0        0     3275 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/test/speed_test.py
+-rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/test/tester.py
+-rw-r--r--   0        0        0     2940 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/.gitignore
+-rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/LICENSE
+-rw-r--r--   0        0        0     3508 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/README.md
+-rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/pyproject.toml
+-rw-r--r--   0        0        0     4570 2020-02-02 00:00:00.000000 pygame_ecs-0.2.8/PKG-INFO
```

### Comparing `pygame_ecs-0.2.7/pygame_ecs/managers/component_manager.py` & `pygame_ecs-0.2.8/pygame_ecs/managers/component_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/pygame_ecs/managers/entity_manager.py` & `pygame_ecs-0.2.8/pygame_ecs/managers/entity_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/pygame_ecs/managers/system_manager.py` & `pygame_ecs-0.2.8/pygame_ecs/managers/system_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/pygame_ecs/systems/base_system.py` & `pygame_ecs-0.2.8/pygame_ecs/systems/base_system.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/test/circle.png` & `pygame_ecs-0.2.8/test/circle.png`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/test/draw_test.py` & `pygame_ecs-0.2.8/test/draw_test.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/test/particle_test_cpu.py` & `pygame_ecs-0.2.8/test/particle_test_cpu.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/test/particle_test_gpu.py` & `pygame_ecs-0.2.8/test/particle_test_gpu.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/test/speed_test.py` & `pygame_ecs-0.2.8/test/speed_test.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/.gitignore` & `pygame_ecs-0.2.8/.gitignore`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/LICENSE` & `pygame_ecs-0.2.8/LICENSE`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.7/README.md` & `pygame_ecs-0.2.8/README.md`

 * *Files 7% similar despite different names*

```diff
@@ -3,24 +3,20 @@
 An Pure Python, simple to use ECS library for pygame.
 
 ## How it works
 
 Create an entity
 
 ```python
-entities = []
-entity = entity_manager.add_entity(component_manager)
-entities.append(entity)
+entity = entity_manager.add_entity()
 ```
 
 You can delete an entity like this:
 ```python
-    entity = entities[random.randint(0, len(entities) - 1)]
-    entity_manager.kill_entity(component_manager, entity)
-    entities.remove(entity)
+    entity_manager.kill_entity(entity)
 ```
 
 Components are just classes that hold data
 
 ```python
 class Position(pygame_ecs.BaseComponent):
     def __init__(self, x: int, y: int):
@@ -35,25 +31,24 @@
 
 class BallPhysics(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, Velocity])
         self.dt = 0
         self.screen = screen
 
-    def update(self, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]
         vel: Velocity = entity_components[Velocity]
         pos.x += vel.vec.x * self.dt
         pos.y += vel.vec.y * self.dt
         if pos.x > WIDTH or pos.x < 0:
             vel.vec.x *= -1
         if pos.y > HEIGHT or pos.y < 0:
             vel.vec.y *= -1
 
-
 ```
 
 ## Example Usage
 ```py
 import pygame
 import pygame_ecs
 import random
```

### Comparing `pygame_ecs-0.2.7/pyproject.toml` & `pygame_ecs-0.2.8/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 
 [project]
 name = "pygame_ecs"
-version = "0.2.7"
+version = "0.2.8"
 authors = [
   { name="Notenlish", email="71970100+Notenlish@users.noreply.github.com" },
 ]
 description = "Pure Python, simple to use Entity Component System(ECS) for pygame"
 packages=["pygame_ecs", "pygame_ecs.components", "pygame_ecs.managers", "pygame_ecs.systems"]
 readme = "README.md"
 requires-python = ">=3.7"
```

### Comparing `pygame_ecs-0.2.7/PKG-INFO` & `pygame_ecs-0.2.8/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pygame_ecs
-Version: 0.2.7
+Version: 0.2.8
 Summary: Pure Python, simple to use Entity Component System(ECS) for pygame
 Project-URL: Homepage, https://github.com/Notenlish/pygame_ecs
 Project-URL: Bug Tracker, https://github.com/Notenlish/pygame_ecs/issues
 Author-email: Notenlish <71970100+Notenlish@users.noreply.github.com>
 License-Expression: MIT
 License-File: LICENSE
 Keywords: ECS,component,ecs,entity,entity component system,pygame,pygame-ce,pygame_ecs,system
@@ -29,24 +29,20 @@
 An Pure Python, simple to use ECS library for pygame.
 
 ## How it works
 
 Create an entity
 
 ```python
-entities = []
-entity = entity_manager.add_entity(component_manager)
-entities.append(entity)
+entity = entity_manager.add_entity()
 ```
 
 You can delete an entity like this:
 ```python
-    entity = entities[random.randint(0, len(entities) - 1)]
-    entity_manager.kill_entity(component_manager, entity)
-    entities.remove(entity)
+    entity_manager.kill_entity(entity)
 ```
 
 Components are just classes that hold data
 
 ```python
 class Position(pygame_ecs.BaseComponent):
     def __init__(self, x: int, y: int):
@@ -61,25 +57,24 @@
 
 class BallPhysics(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, Velocity])
         self.dt = 0
         self.screen = screen
 
-    def update(self, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]
         vel: Velocity = entity_components[Velocity]
         pos.x += vel.vec.x * self.dt
         pos.y += vel.vec.y * self.dt
         if pos.x > WIDTH or pos.x < 0:
             vel.vec.x *= -1
         if pos.y > HEIGHT or pos.y < 0:
             vel.vec.y *= -1
 
-
 ```
 
 ## Example Usage
 ```py
 import pygame
 import pygame_ecs
 import random
```


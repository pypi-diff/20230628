# Comparing `tmp/pygame_ecs-0.2.4.tar.gz` & `tmp/pygame_ecs-0.2.5.tar.gz`

## Comparing `pygame_ecs-0.2.4.tar` & `pygame_ecs-0.2.5.tar`

### file list

```diff
@@ -1,20 +1,20 @@
--rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/.gitattributes
--rw-r--r--   0        0        0      351 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/__init__.py
--rw-r--r--   0        0        0      306 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/entity.py
--rw-r--r--   0        0        0      431 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/exceptions.py
--rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/components/base_component.py
--rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/managers/component_manager.py
--rw-r--r--   0        0        0     1972 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/managers/entity_manager.py
--rw-r--r--   0        0        0     1733 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/managers/system_manager.py
--rw-r--r--   0        0        0      808 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pygame_ecs/systems/base_system.py
--rw-r--r--   0        0        0    30680 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/test/circle.png
--rw-r--r--   0        0        0     2122 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/test/draw_test.py
--rw-r--r--   0        0        0     4174 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/test/particle_test_cpu.py
--rw-r--r--   0        0        0     4053 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/test/particle_test_gpu.py
--rw-r--r--   0        0        0     3268 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/test/speed_test.py
--rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/test/tester.py
--rw-r--r--   0        0        0     2940 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/.gitignore
--rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/LICENSE
--rw-r--r--   0        0        0     3654 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/README.md
--rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/pyproject.toml
--rw-r--r--   0        0        0     4711 2020-02-02 00:00:00.000000 pygame_ecs-0.2.4/PKG-INFO
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/.gitattributes
+-rw-r--r--   0        0        0      435 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/__init__.py
+-rw-r--r--   0        0        0      306 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/entity.py
+-rw-r--r--   0        0        0      431 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/exceptions.py
+-rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/components/base_component.py
+-rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/managers/component_manager.py
+-rw-r--r--   0        0        0     1976 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/managers/entity_manager.py
+-rw-r--r--   0        0        0     1902 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/managers/system_manager.py
+-rw-r--r--   0        0        0     1272 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pygame_ecs/systems/base_system.py
+-rw-r--r--   0        0        0    30680 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/circle.png
+-rw-r--r--   0        0        0     2129 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/draw_test.py
+-rw-r--r--   0        0        0     4188 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/particle_test_cpu.py
+-rw-r--r--   0        0        0     5293 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/particle_test_gpu.py
+-rw-r--r--   0        0        0     3275 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/speed_test.py
+-rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/test/tester.py
+-rw-r--r--   0        0        0     2940 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/.gitignore
+-rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/LICENSE
+-rw-r--r--   0        0        0     3654 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/README.md
+-rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/pyproject.toml
+-rw-r--r--   0        0        0     4711 2020-02-02 00:00:00.000000 pygame_ecs-0.2.5/PKG-INFO
```

### Comparing `pygame_ecs-0.2.4/pygame_ecs/managers/component_manager.py` & `pygame_ecs-0.2.5/pygame_ecs/managers/component_manager.py`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.4/pygame_ecs/managers/entity_manager.py` & `pygame_ecs-0.2.5/pygame_ecs/managers/entity_manager.py`

 * *Files 7% similar despite different names*

```diff
@@ -41,11 +41,11 @@
             except KeyError:
                 pass
 
     def _clear_limbo(self):
         """Function to get rid of entities that have been killed that frame.
         You probably won't need to call this yourself, it will be called automatically.
         """
-        for entity in self._limbo.keys():
+        for entity, _ in self._limbo.items():
             self.dead_entities.append(entity)
             del self.entities[entity]
         self._limbo = {}
```

### Comparing `pygame_ecs-0.2.4/pygame_ecs/managers/system_manager.py` & `pygame_ecs-0.2.5/pygame_ecs/managers/system_manager.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,21 +23,24 @@
         self.systems.remove(system)
 
     def update_entities(self):
         """Updates all of the systems that are active.
         NOTE: For updating values of systems, just set their values before calling this function.
         """
         for system in self.systems:
-            for entity in self.entity_manager.entities.keys():
-                has_components = True
-                components_to_give = {}
-                for comp_type in system.required_component_types:
-                    try:
-                        comp = self.component_manager.components[comp_type][entity]
-                        components_to_give[type(comp)] = comp
-                    except KeyError:
-                        self.component_manager.components[comp_type]
-                        has_components = False
-                        break
-                if has_components:
-                    system.update(entity, components_to_give)
+            if len(system.required_component_types) > 0:
+                for entity in self.entity_manager.entities.keys():
+                    has_components = True
+                    components_to_give = {}
+                    for comp_type in system.required_component_types:
+                        try:
+                            comp = self.component_manager.components[comp_type][entity]
+                            components_to_give[type(comp)] = comp
+                        except KeyError:
+                            self.component_manager.components[comp_type]
+                            has_components = False
+                            break
+                    if has_components:
+                        system.update_entity(entity, components_to_give)
+            else:
+                system.update()
         self.entity_manager._clear_limbo()
```

### Comparing `pygame_ecs-0.2.4/pygame_ecs/systems/base_system.py` & `pygame_ecs-0.2.5/pygame_ecs/systems/base_system.py`

 * *Files 17% similar despite different names*

```diff
@@ -9,16 +9,27 @@
     # typing.Type specifies that it will take subclasses of this class
     def __init__(
         self, required_component_types: list[typing.Type[BaseComponent]]
     ) -> None:
         self.required_component_types = required_component_types
         self.entity_manager: EntityManager
 
-    def update(
+    def update_entity(
         self,
         entity: Entity,
         entity_components: dict[typing.Type[BaseComponent], ComponentInstanceType],
     ):
+        """This function is called for every entity that has the required components if the required component size is bigger than 0.
+
+        Args:
+            entity (Entity): Entity instance
+
+            entity_components (dict[typing.Type[BaseComponent], ComponentInstanceType]): Components of the entity
+        """
+        pass
+
+    def update(self):
+        """This function is called only once a frame if the required components is 0."""
         pass
 
     def __str__(self) -> str:
         return f"<{type(self).__name__}>"
```

### Comparing `pygame_ecs-0.2.4/test/circle.png` & `pygame_ecs-0.2.5/test/circle.png`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.4/test/draw_test.py` & `pygame_ecs-0.2.5/test/draw_test.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 
 
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

### Comparing `pygame_ecs-0.2.4/test/particle_test_cpu.py` & `pygame_ecs-0.2.5/test/particle_test_cpu.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,27 +24,27 @@
 
 
 class BallDrawSystem(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, BallRenderer])
         self.screen = screen
 
-    def update(self, entity, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]  # type: ignore
         ball_renderer: BallRenderer = entity_components[BallRenderer]  # type: ignore
         pygame.draw.circle(self.screen, ball_renderer.color, (pos.x, pos.y), ball_renderer.radius)  # type: ignore
 
 
 class BallPhysics(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, Velocity])
         self.dt = 0
         self.screen = screen
 
-    def update(self, entity, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]  # type: ignore
         vel: Velocity = entity_components[Velocity]  # type: ignore
         pos.x += vel.vec.x * self.dt  # type: ignore
         pos.y += vel.vec.y * self.dt  # type: ignore
         if pos.x > self.screen.get_width() or pos.x < 0:
             vel.vec.x *= -1
         if pos.y > self.screen.get_height() or pos.y < 0:
```

### Comparing `pygame_ecs-0.2.4/test/particle_test_gpu.py` & `pygame_ecs-0.2.5/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -1,137 +1,128 @@
-import pygame
-import random
-import pygame_ecs
-from pygame._sdl2 import Renderer, Texture, Window, get_drivers
+# Pygame_ecs
 
-pygame.init()
+An Pure Python, simple to use ECS library for pygame.
 
-ENTITY_AMOUNT = 1_000 * 10
-WIDTH = 800
-HEIGHT = 600
+## How it works
 
+Create an entity
 
-class Position(pygame_ecs.BaseComponent):
-    __slots__ = ("x", "y")
+```python
+entities = []
+entity = entity_manager.add_entity(component_manager)
+entities.append(entity)
+```
 
+You can delete an entity like this:
+```python
+    entity = entities[random.randint(0, len(entities) - 1)]
+    entity_manager.kill_entity(component_manager, entity)
+    entities.remove(entity)
+```
+
+Components are just classes that hold data
+
+```python
+class Position(pygame_ecs.BaseComponent):
     def __init__(self, x: int, y: int):
         super().__init__()
         self.x = x
         self.y = y
+```
 
+Systems are just classes that hold logic
 
-class BallRenderer(pygame_ecs.BaseComponent):
-    __slots__ = ("radius", "color")
-
-    def __init__(self, radius: int, color) -> None:
-        super().__init__()
-        self.radius = radius
-        self.color = color
-
-
-class Velocity(pygame_ecs.BaseComponent):
-    __slots__ = "vec"
-
-    def __init__(self, vec: pygame.math.Vector2) -> None:
-        super().__init__()
-        self.vec = vec
-
-
-class BallDrawSystem(pygame_ecs.BaseSystem):
-    def __init__(self, texture: Texture) -> None:
-        super().__init__(required_component_types=[Position, BallRenderer])
-        self.texture = texture
-
-    def update(self, entity, entity_components):
-        pos: Position = entity_components[Position]  # type: ignore
-        ball_renderer: BallRenderer = entity_components[BallRenderer]  # type: ignore
-
-        self.texture.color = ball_renderer.color  # type: ignore
-        self.texture.draw(
-            None, (pos.x, pos.y, ball_renderer.radius, ball_renderer.radius)
-        )
-
+```python
 
 class BallPhysics(pygame_ecs.BaseSystem):
     def __init__(self, screen) -> None:
         super().__init__(required_component_types=[Position, Velocity])
         self.dt = 0
         self.screen = screen
 
-    def update(self, entity, entity_components):
-        pos: Position = entity_components[Position]  # type: ignore
-        vel: Velocity = entity_components[Velocity]  # type: ignore
-        pos.x += vel.vec.x * self.dt  # type: ignore
-        pos.y += vel.vec.y * self.dt  # type: ignore
+    def update(self, entity_components):
+        pos: Position = entity_components[Position]
+        vel: Velocity = entity_components[Velocity]
+        pos.x += vel.vec.x * self.dt
+        pos.y += vel.vec.y * self.dt
         if pos.x > WIDTH or pos.x < 0:
             vel.vec.x *= -1
         if pos.y > HEIGHT or pos.y < 0:
             vel.vec.y *= -1
 
 
-screen = pygame.display.set_mode((WIDTH, HEIGHT))
-window = Window.from_display_module()
+```
 
+## Example Usage
+```py
+import pygame
+import pygame_ecs
+import random
 
-print(list(get_drivers()))
-# change based on drivers
-renderer = Renderer(window, index=3, accelerated=1)
+
+class Position(pygame_ecs.BaseComponent):
+    def __init__(self, x: int, y: int):
+        super().__init__()
+        self.x = x
+        self.y = y
+
+
+class BallRenderer(pygame_ecs.BaseComponent):
+    def __init__(self, radius: int, color) -> None:
+        super().__init__()
+        self.radius = radius
+        self.color = color
+
+
+class BallDrawSystem(pygame_ecs.BaseSystem):
+    def __init__(self, screen) -> None:
+        super().__init__(required_component_types=[Position, BallRenderer])
+        self.screen = screen
+
+    def update(self, entity, entity_components):
+        pos: Position = entity_components[Position]
+        ball_renderer: BallRenderer = entity_components[BallRenderer]
+        pygame.draw.circle(
+            self.screen, ball_renderer.color, (pos.x, pos.y), ball_renderer.radius
+        )
 
 
-texture = Texture.from_surface(renderer, pygame.image.load("test/circle.png"))
+screen = pygame.display.set_mode((800, 600))
+clock = pygame.time.Clock()
 
 component_manager = pygame_ecs.ComponentManager()
 entity_manager = pygame_ecs.EntityManager(component_manager)
 system_manager = pygame_ecs.SystemManager(entity_manager, component_manager)
-ball_physics = BallPhysics(screen)
-ball_draw_system = BallDrawSystem(texture=texture)
+ball_draw_system = BallDrawSystem(screen)
 system_manager.add_system(ball_draw_system)
-system_manager.add_system(ball_physics)
 component_manager.init_components()
 
-
-for _ in range(ENTITY_AMOUNT):
+for _ in range(200):
     center = (
-        random.randint(0, WIDTH),
-        random.randint(0, HEIGHT),
+        random.randint(0, screen.get_width()),
+        random.randint(0, screen.get_height()),
     )
-    radius = random.randint(5, 15)
+    radius = random.randint(4, 18)
     color = [random.randint(0, 255) for _ in range(3)]
-    color.append(255)
     vel = pygame.math.Vector2(
         (random.random() - 0.5) * 400 / 1000,
         (random.random() - 0.5) * 400 / 1000,
     )
     entity = entity_manager.add_entity()
     component_manager.add_component(entity, Position(center[0], center[1]))
-    if random.randint(0, 1):
-        component_manager.add_component(entity, Velocity(vel))
     component_manager.add_component(entity, BallRenderer(radius, color))
 
-
-clock = pygame.time.Clock()
-dt = 0
-
-renderer.draw_color = (
-    0,
-    0,
-    0,
-    255,
-)  # type: ignore
-# renderer.draw_color is used for clearing the screen and drawing primitives
-
-running = True
-while running:
+while True:
     for event in pygame.event.get():
         if event.type == pygame.QUIT:
-            running = False
+            raise SystemExit
 
-        if event.type == pygame.KEYDOWN and event.key == pygame.K_ESCAPE:
-            running = False
-    pygame.display.set_caption(f"FPS: {clock.get_fps()}")
-    ball_physics.dt = dt
-    renderer.clear()
     system_manager.update_entities()
-    renderer.present()
-    dt = clock.tick(60)
+    pygame.display.update()
+    clock.tick(60)
+    pygame.display.set_caption(f"FPS: {clock.get_fps()}")
+```
+
+## Credits
 
-pygame.quit()
+I'd like to give credit to https://www.youtube.com/watch?v=71RSWVyOMEY and https://github.com/seanfisk/ecs
+As well as `dickerdackel` from pgc server and `SamieZaurus#8030` from UnitOfTime's server.
```

### Comparing `pygame_ecs-0.2.4/test/speed_test.py` & `pygame_ecs-0.2.5/test/speed_test.py`

 * *Files 3% similar despite different names*

```diff
@@ -33,15 +33,15 @@
         self.vec = vec
 
 
 class BallPhysics(pygame_ecs.BaseSystem):
     def __init__(self) -> None:
         super().__init__(required_component_types=[Position, Velocity])
 
-    def update(self, entity, entity_components):
+    def update_entity(self, entity, entity_components):
         pos: Position = entity_components[Position]  # type: ignore
         vel: Velocity = entity_components[Velocity]  # type: ignore
         pos.x += vel.vec[0]  # type: ignore
         pos.y += vel.vec[1]  # type: ignore
         if pos.x > WIDTH or pos.x < 0:
             vel.vec[0] *= -1
         if pos.y > HEIGHT or pos.y < 0:
```

### Comparing `pygame_ecs-0.2.4/.gitignore` & `pygame_ecs-0.2.5/.gitignore`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.4/LICENSE` & `pygame_ecs-0.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `pygame_ecs-0.2.4/pyproject.toml` & `pygame_ecs-0.2.5/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 
 [project]
 name = "pygame_ecs"
-version = "0.2.4"
+version = "0.2.5"
 authors = [
   { name="Notenlish", email="71970100+Notenlish@users.noreply.github.com" },
 ]
 description = "Pure Python, simple to use Entity Component System(ECS) for pygame"
 packages=["pygame_ecs", "pygame_ecs.components", "pygame_ecs.managers", "pygame_ecs.systems"]
 readme = "README.md"
 requires-python = ">=3.7"
```

### Comparing `pygame_ecs-0.2.4/PKG-INFO` & `pygame_ecs-0.2.5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pygame_ecs
-Version: 0.2.4
+Version: 0.2.5
 Summary: Pure Python, simple to use Entity Component System(ECS) for pygame
 Project-URL: Homepage, https://github.com/Notenlish/pygame_ecs
 Project-URL: Bug Tracker, https://github.com/Notenlish/pygame_ecs/issues
 Author-email: Notenlish <71970100+Notenlish@users.noreply.github.com>
 License-Expression: MIT
 License-File: LICENSE
 Keywords: ECS,component,ecs,entity,entity component system,pygame,pygame-ce,pygame_ecs,system
```


# Comparing `tmp/python_hue_v2-1.0.0.tar.gz` & `tmp/python_hue_v2-1.0.1.tar.gz`

## Comparing `python_hue_v2-1.0.0.tar` & `python_hue_v2-1.0.1.tar`

### file list

```diff
@@ -1,39 +1,39 @@
--rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/pytest.ini
--rw-r--r--   0        0        0     1124 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/.gitignore
--rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/hue-v2.iml
--rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/misc.xml
--rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/modules.xml
--rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/vcs.xml
--rw-r--r--   0        0        0     2232 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0      277 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.vscode/settings.json
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/__about__.py
--rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/__init__.py
--rw-r--r--   0        0        0     6031 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/bridge.py
--rw-r--r--   0        0        0     1905 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/grouped_light.py
--rw-r--r--   0        0        0     1783 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/hue.py
--rw-r--r--   0        0        0     1192 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/light.py
--rw-r--r--   0        0        0     1477 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/mdns.py
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/__init__.py
--rw-r--r--   0        0        0      399 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/resource_identifier_get.py
--rw-r--r--   0        0        0      511 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/room.py
--rw-r--r--   0        0        0      503 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/room_get.py
--rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/__init__.py
--rw-r--r--   0        0        0      262 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/group.py
--rw-r--r--   0        0        0      301 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/meta_data.py
--rw-r--r--   0        0        0     4514 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/scene.py
--rw-r--r--   0        0        0      323 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/target.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/__init__.py
--rw-r--r--   0        0        0     2613 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action.py
--rw-r--r--   0        0        0     1072 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_get.py
--rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_post.py
--rw-r--r--   0        0        0      451 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_put.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/tests/__init__.py
--rw-r--r--   0        0        0     3053 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/tests/test_hue.py
--rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/tests/test_object_convert.py
--rw-r--r--   0        0        0     4704 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.gitignore
--rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/LICENSE
--rw-r--r--   0        0        0     1628 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/README.md
--rw-r--r--   0        0        0     3366 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/pyproject.toml
--rw-r--r--   0        0        0     2632 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/PKG-INFO
+-rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/pytest.ini
+-rw-r--r--   0        0        0     1124 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/.gitignore
+-rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/hue-v2.iml
+-rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/misc.xml
+-rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/modules.xml
+-rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/vcs.xml
+-rw-r--r--   0        0        0     2232 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/inspectionProfiles/Project_Default.xml
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0        0        0      438 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.vscode/settings.json
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/__about__.py
+-rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/__init__.py
+-rw-r--r--   0        0        0     6031 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/bridge.py
+-rw-r--r--   0        0        0     1905 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/grouped_light.py
+-rw-r--r--   0        0        0     1509 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/hue.py
+-rw-r--r--   0        0        0     1192 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/light.py
+-rw-r--r--   0        0        0     1477 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/mdns.py
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/__init__.py
+-rw-r--r--   0        0        0      399 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/resource_identifier_get.py
+-rw-r--r--   0        0        0      511 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/room.py
+-rw-r--r--   0        0        0      503 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/room_get.py
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/__init__.py
+-rw-r--r--   0        0        0      262 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/group.py
+-rw-r--r--   0        0        0      301 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/meta_data.py
+-rw-r--r--   0        0        0     4539 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/scene.py
+-rw-r--r--   0        0        0      323 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/target.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/__init__.py
+-rw-r--r--   0        0        0     2613 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action.py
+-rw-r--r--   0        0        0     1072 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_get.py
+-rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_post.py
+-rw-r--r--   0        0        0      451 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_put.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/tests/__init__.py
+-rw-r--r--   0        0        0     3074 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/tests/test_hue.py
+-rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/tests/test_object_convert.py
+-rw-r--r--   0        0        0     4704 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.gitignore
+-rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/LICENSE
+-rw-r--r--   0        0        0     2887 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/README.md
+-rw-r--r--   0        0        0     3366 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/pyproject.toml
+-rw-r--r--   0        0        0     3891 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/PKG-INFO
```

### Comparing `python_hue_v2-1.0.0/.github/workflows/python-publish.yml` & `python_hue_v2-1.0.1/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/.idea/inspectionProfiles/Project_Default.xml` & `python_hue_v2-1.0.1/.idea/inspectionProfiles/Project_Default.xml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/bridge.py` & `python_hue_v2-1.0.1/src/python_hue_v2/bridge.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/grouped_light.py` & `python_hue_v2-1.0.1/src/python_hue_v2/grouped_light.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/light.py` & `python_hue_v2-1.0.1/src/python_hue_v2/light.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/mdns.py` & `python_hue_v2-1.0.1/src/python_hue_v2/mdns.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/scene/scene.py` & `python_hue_v2-1.0.1/src/python_hue_v2/scene/scene.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 from typing import List, Optional, Union, Literal
 from ..bridge import Bridge
 from .action import ActionGet, ActionPost
 from .meta_data import Metadata
 from .group import Group
 
+
 class SceneGet:
     """
     SceneGet Data, ref in https://developers.meethue.com/develop/hue-api-v2/api-reference/#resource_scene_get
     """
 
     def __init__(self, scene_get_data: dict):
         self._data_dict = scene_get_data
@@ -66,20 +67,20 @@
 
 class ScenePost:
     def __init__(self, scene_post_data: dict) -> None:
         self._data_dict: dict = scene_post_data
 
     @classmethod
     def create_by_parameters(
-        cls,
-        actions: List[Union[dict, ActionPost]],
-        name: str,
-        group_rid: str,
-        group_rtype: str,
-        palette: Optional[dict] = None,
+            cls,
+            actions: List[Union[dict, ActionPost]],
+            name: str,
+            group_rid: str,
+            group_rtype: str,
+            palette: Optional[dict] = None,
     ):
         if type(actions[0]) is dict:
             action_dicts = actions
         elif isinstance(actions[0], ActionPost):
             action_dicts = [i.data_dict for i in actions]
         else:
             raise TypeError('Actions must be dict or ActionPost')
```

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action.py` & `python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_get.py` & `python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_get.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_post.py` & `python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_post.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,9 +1,8 @@
-from ast import Tuple
-from typing import Optional, Union
+from typing import Optional, Union, Tuple
 from ..target import Target
 from .action import Action
 
 
 class ActionPost:
     def __init__(self, action_post_data: dict):
         self._action_post_data = action_post_data
@@ -20,15 +19,15 @@
     @classmethod
     def create_by_parameters(
         cls,
         target_rid: str,
         target_rtype : str,
         on: bool = False,
         brightness: float = 50.0,
-        color_xy: Union[Tuple, None] = (0.5, 0.5),
+        color_xy: Union[Tuple[float, float], None] = (0.5, 0.5),
         mirek: Optional[int] = None,
     ):
         action_post_data = {}
         action: Action = Action.create_by_parameters(on, brightness, color_xy=color_xy, mirek=mirek)
         action_post_data['action'] = action.data_dict
         action_post_data['target'] = {'rid': target_rid, 'rtype': target_rtype}
         return cls(action_post_data)
```

### Comparing `python_hue_v2-1.0.0/tests/test_hue.py` & `python_hue_v2-1.0.1/tests/test_hue.py`

 * *Files 1% similar despite different names*

```diff
@@ -78,14 +78,15 @@
     for scene in scenes:
         if scene.meta_data.name == 'test':
             test_scene = scene
             break
     test_scene.recall()
     time.sleep(3)
     groups = hue.grouped_lights
+    test_group = None
     for group in groups:
         if group.owner.rid == test_scene.group.rid:
             test_group = group
     if test_group:
         test_group.on = False
     else:
         assert False
@@ -98,15 +99,14 @@
         if scene.meta_data.name == 'test':
             test_scene = scene
             break
 
     hue.bridge.delete_scene(test_scene.id)
     assert 1
 
-
 # def test_grouped_light_type():
 #     assert hue.grouped_lights[0].type == 'grouped_light'
 
 
 # def test_grouped_light_brightness():
 #     assert type(hue.grouped_lights[0].brightness) == float
 #     hue.grouped_lights[0].on = True
```

### Comparing `python_hue_v2-1.0.0/.gitignore` & `python_hue_v2-1.0.1/.gitignore`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/LICENSE` & `python_hue_v2-1.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/pyproject.toml` & `python_hue_v2-1.0.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.0/PKG-INFO` & `python_hue_v2-1.0.1/README.md`

 * *Files 24% similar despite different names*

```diff
@@ -1,33 +1,11 @@
-Metadata-Version: 2.1
-Name: python-hue-v2
-Version: 1.0.0
-Summary: A python library to control the Philips Hue lighting system.
-Project-URL: Documentation, https://github.com/FengChendian/python-hue-v2#readme
-Project-URL: Issues, https://github.com/FengChendian/python-hue-v2/issues
-Project-URL: Source, https://github.com/FengChendian/python-hue-v2
-Author-email: Yichen Zhao <njuzhaoyichen@gmail.com>
-License-Expression: MIT
-License-File: LICENSE
-Classifier: Development Status :: 4 - Beta
-Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Programming Language :: Python :: Implementation :: PyPy
-Requires-Python: >=3.8
-Requires-Dist: requests>=2.30.0
-Requires-Dist: zeroconf>=0.62.0
-Description-Content-Type: text/markdown
-
 # Python Hue V2
 
-Python library to control the Philips Hue lighting system for Hue-V2 API.
+Python library to control the Philips Hue lighting system
+for [Hue-V2](https://developers.meethue.com/develop/hue-api-v2/api-reference/) API.
 
 ## Features
 
 - Design for Hue API 2.0
 
 ## High Level Control
 
@@ -48,46 +26,99 @@
 lights = hue.lights
 
 for light in lights:
     print(light.on)
     light.on = True
     light.brightness = 80.0
 ```
+
 ### Scenes
+
 You can get scenes from hue bridge.
+
 ```python
 from python_hue_v2 import Hue
 
 hue = Hue('bridge-ip', 'app-key')
 
 scenes = hue.scenes
 for scene in scenes:
     print(scene.id)
     print(scene.data_dict)
 ```
+
 Recall scene using `active`, `dynamic_palette`, `static`.
+
 ```python
 scene = scenes[0]
 scene.recall(action='active')
 ```
 
+If you want create one scene with light actions in a room:
+
+```python
+from python_hue_v2.scene import ActionPost, ScenePost
+
+light_id = []
+lights = hue.lights
+for light in lights:
+    light_id.append(light.light_id)
+
+actions = []
+for rid in light_id:
+    actions.append(
+        ActionPost.create_by_parameters(
+            target_rid=rid,
+            target_rtype='light',
+            on=True,
+            brightness=50,
+            color_xy=(0.1, 0.3)  # xy color tuple
+            # mirek=200 % or use mirek
+        )
+    )
+
+# Get all rooms, may be empty
+rooms = hue.rooms
+
+# ScenePost should have a group property, Here we bind with a room
+
+# refer to https://developers.meethue.com/develop/hue-api-v2/api-reference/#resource_scene_post
+# Group associated with this Scene. All services in the group are part of this scene. 
+# If the group is changed the scene is update (e.g. light added/removed)
+scene_post: ScenePost = ScenePost.create_by_parameters(
+    actions=actions, name='test', group_rid=rooms[0].id, group_rtype="room"
+)
+hue.create_scene(scene_post)
+```
+
+Also, you can delete scene by id.
+
+```python
+hue.delete_scene('scene-id-example')
+```
+
 ### Grouped Light
-Get Lights from hue.
+
+Get group Lights from hue.
+
 ```python
 from python_hue_v2 import Hue
 
 hue = Hue('bridge-ip', 'app-key')
 grouped_lights = hue.grouped_lights
 
 for group in grouped_lights:
     print(group.type)
+    group.on = True
 ```
 
 ## Low Level Control
+
 Also, you can use basic function in bridge class.
+
 ```python
 import time
 from python_hue_v2 import Hue
 
 # or hue = Hue('ip address','app-key')
 hue = Hue('host_name', 'hue app key')  # create Hue instance
 bridge = hue.bridge
```


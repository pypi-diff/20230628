# Comparing `tmp/python_hue_v2-1.0.1.tar.gz` & `tmp/python_hue_v2-1.0.2.tar.gz`

## Comparing `python_hue_v2-1.0.1.tar` & `python_hue_v2-1.0.2.tar`

### file list

```diff
@@ -1,39 +1,39 @@
--rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/pytest.ini
--rw-r--r--   0        0        0     1124 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/.gitignore
--rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/hue-v2.iml
--rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/misc.xml
--rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/modules.xml
--rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/vcs.xml
--rw-r--r--   0        0        0     2232 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0      438 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.vscode/settings.json
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/__about__.py
--rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/__init__.py
--rw-r--r--   0        0        0     6031 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/bridge.py
--rw-r--r--   0        0        0     1905 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/grouped_light.py
--rw-r--r--   0        0        0     1509 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/hue.py
--rw-r--r--   0        0        0     1192 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/light.py
--rw-r--r--   0        0        0     1477 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/mdns.py
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/__init__.py
--rw-r--r--   0        0        0      399 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/resource_identifier_get.py
--rw-r--r--   0        0        0      511 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/room.py
--rw-r--r--   0        0        0      503 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/room/room_get.py
--rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/__init__.py
--rw-r--r--   0        0        0      262 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/group.py
--rw-r--r--   0        0        0      301 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/meta_data.py
--rw-r--r--   0        0        0     4539 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/scene.py
--rw-r--r--   0        0        0      323 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/target.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/__init__.py
--rw-r--r--   0        0        0     2613 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action.py
--rw-r--r--   0        0        0     1072 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_get.py
--rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_post.py
--rw-r--r--   0        0        0      451 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_put.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/tests/__init__.py
--rw-r--r--   0        0        0     3074 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/tests/test_hue.py
--rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/tests/test_object_convert.py
--rw-r--r--   0        0        0     4704 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/.gitignore
--rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/LICENSE
--rw-r--r--   0        0        0     2887 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/README.md
--rw-r--r--   0        0        0     3366 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/pyproject.toml
--rw-r--r--   0        0        0     3891 2020-02-02 00:00:00.000000 python_hue_v2-1.0.1/PKG-INFO
+-rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/pytest.ini
+-rw-r--r--   0        0        0     1124 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/.gitignore
+-rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/hue-v2.iml
+-rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/misc.xml
+-rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/modules.xml
+-rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/vcs.xml
+-rw-r--r--   0        0        0     2232 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/inspectionProfiles/Project_Default.xml
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0        0        0      438 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.vscode/settings.json
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/__about__.py
+-rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/__init__.py
+-rw-r--r--   0        0        0     6485 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/bridge.py
+-rw-r--r--   0        0        0     1905 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/grouped_light.py
+-rw-r--r--   0        0        0     1536 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/hue.py
+-rw-r--r--   0        0        0     1192 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/light.py
+-rw-r--r--   0        0        0     1477 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/mdns.py
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/room/__init__.py
+-rw-r--r--   0        0        0      399 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/room/resource_identifier_get.py
+-rw-r--r--   0        0        0      511 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/room/room.py
+-rw-r--r--   0        0        0      503 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/room/room_get.py
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/__init__.py
+-rw-r--r--   0        0        0      262 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/group.py
+-rw-r--r--   0        0        0      301 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/meta_data.py
+-rw-r--r--   0        0        0     4539 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/scene.py
+-rw-r--r--   0        0        0      323 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/target.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/action/__init__.py
+-rw-r--r--   0        0        0     2613 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action.py
+-rw-r--r--   0        0        0     1072 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action_get.py
+-rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action_post.py
+-rw-r--r--   0        0        0      451 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action_put.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/tests/__init__.py
+-rw-r--r--   0        0        0     3242 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/tests/test_hue.py
+-rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/tests/test_object_convert.py
+-rw-r--r--   0        0        0     4704 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/.gitignore
+-rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/LICENSE
+-rw-r--r--   0        0        0     3104 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/README.md
+-rw-r--r--   0        0        0     3366 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/pyproject.toml
+-rw-r--r--   0        0        0     4108 2020-02-02 00:00:00.000000 python_hue_v2-1.0.2/PKG-INFO
```

### Comparing `python_hue_v2-1.0.1/.github/workflows/python-publish.yml` & `python_hue_v2-1.0.2/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/.idea/inspectionProfiles/Project_Default.xml` & `python_hue_v2-1.0.2/.idea/inspectionProfiles/Project_Default.xml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/bridge.py` & `python_hue_v2-1.0.2/src/python_hue_v2/bridge.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,15 +6,16 @@
 
 
 class Bridge:
     """
     Basic communication class with hue bridge. All Data should be dict or json. \\
     Don't import another hue device class to this file.
     """
-    def __init__(self, ip_address: str, hue_application_key: str):
+
+    def __init__(self, ip_address: str, hue_application_key: Union[str, None]):
         self.ip_address = ip_address
         self.hue_application_key = hue_application_key
         self.hue_application_key_name = 'hue-application-key'
         # url
         self.base_url = f'https://{self.ip_address}/clip/v2/resource'
 
         self._light_category = 'light'
@@ -24,34 +25,43 @@
         self._bridge_home_category = 'bridge_home'
         self._grouped_light_category = 'grouped_light'
         self._device_category = 'device'
         self._bridge_category = 'bridge'
         # requests.Request.
         urllib3.disable_warnings(urllib3.exceptions.InsecureRequestWarning)
 
+    def connect(self):
+        generate_command = {"devicetype": "app_name#instance_name", "generateclientkey": True}
+        res: dict = \
+            requests.post(f'https://{self.ip_address}/api', data=json.dumps(generate_command), verify=False).json()[0]
+        if 'error' in res.keys():
+            raise ConnectionError(res['error'])
+        else:
+            self.hue_application_key = res['success']['username']
+        return self.hue_application_key
+
     @staticmethod
     def _get_response_error(r_json: dict):
         return r_json['errors']
 
     @staticmethod
     def _get_response_data(r_json: dict) -> list:
         return r_json['data']
 
     @staticmethod
     def _convert_to_data(res: dict) -> List[dict]:
-        print(res)
         if res['errors']:
             raise ConnectionError(res['errors'])
         else:
             return res['data']
 
     def _get_by_id(self, category: str, item_id: str) -> dict:
         url = f'{self.base_url}/{category}/{item_id}'
         res = requests.get(url, headers={self.hue_application_key_name: self.hue_application_key}, verify=False).json()
-        return self._convert_to_data(res)[0] # data length should be 1, so return first element [0]
+        return self._convert_to_data(res)[0]  # data length should be 1, so return first element [0]
 
     def _get(self, category: str) -> List[dict]:
         url = f'{self.base_url}/{category}'
         res = requests.get(url, headers={self.hue_application_key_name: self.hue_application_key}, verify=False).json()
         return self._convert_to_data(res)
 
     def _put_by_id(self, category: str, item_id: str, properties: dict) -> dict:
@@ -104,15 +114,15 @@
         return self._delete_by_id(self._scene_category, scene_id)
 
     def get_rooms(self) -> List[dict]:
         return self._get(self._room_category)
 
     def get_room(self, room_id: str) -> dict:
         return self._get_by_id(self._room_category, room_id)
-    
+
     def set_room(self, room_id, room_property: str, property_value: Union[list, dict]):
         return self._put_by_id(self._room_category, room_id, {room_property: property_value})
 
     def get_zones(self) -> List[dict]:
         return self._get(self._zone_category)
 
     def get_zone(self, zone_id: str) -> dict:
```

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/grouped_light.py` & `python_hue_v2-1.0.2/src/python_hue_v2/grouped_light.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/hue.py` & `python_hue_v2-1.0.2/src/python_hue_v2/hue.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 import time
 
 from .room import Room
 from .bridge import Bridge
 from .light import Light
 from .scene import Scene, ScenePost
 from .grouped_light import GroupedLight
-from typing import List, Union
+from typing import List, Union, Optional
 
 
 class Hue:
-    def __init__(self, ip_address: str, hue_application_key: str):
+    def __init__(self, ip_address: str, hue_application_key: Optional[str] = None):
         self.bridge = Bridge(ip_address=ip_address, hue_application_key=hue_application_key)
 
     @property
     def lights(self) -> List[Light]:
         return [Light(self.bridge, light_data['id']) for light_data in self.bridge.get_lights()]
 
     @property
```

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/light.py` & `python_hue_v2-1.0.2/src/python_hue_v2/light.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/mdns.py` & `python_hue_v2-1.0.2/src/python_hue_v2/mdns.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/scene/scene.py` & `python_hue_v2-1.0.2/src/python_hue_v2/scene/scene.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action.py` & `python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_get.py` & `python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action_get.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/src/python_hue_v2/scene/action/action_post.py` & `python_hue_v2-1.0.2/src/python_hue_v2/scene/action/action_post.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/tests/test_hue.py` & `python_hue_v2-1.0.2/tests/test_hue.py`

 * *Files 5% similar despite different names*

```diff
@@ -3,20 +3,28 @@
 from src.python_hue_v2.grouped_light import GroupedLight
 from src.python_hue_v2.scene import ActionPost
 from src.python_hue_v2.scene import ScenePost
 from src.python_hue_v2 import Hue, Light, BridgeFinder, Scene
 
 finder = BridgeFinder()
 time.sleep(1)
-
 test_hostname = finder.get_bridge_server_lists()[0]
 test_key = '7K-IbBzEV3wZoXkTlSh6HyLTALLFsYrxCjIcW1o9'
 hue = Hue(test_hostname, test_key)
 
 
+def test_bridge_connect():
+    hue_test = Hue(test_hostname)
+    try:
+        hue_test.bridge.connect()
+    except ConnectionError as e:
+        print(e)
+    assert 1
+
+
 def test_light_on():
     assert hue is not None
     lights = hue.lights
     for light in lights:
         assert type(light.on) is bool
     # for light in lights:
     #     light.on = True
```

### Comparing `python_hue_v2-1.0.1/.gitignore` & `python_hue_v2-1.0.2/.gitignore`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/LICENSE` & `python_hue_v2-1.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/README.md` & `python_hue_v2-1.0.2/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -19,14 +19,18 @@
 time.sleep(1)  # wait for search
 # Get server by mdns
 host_name = finder.get_bridge_server_lists()[0]  # Here we use first Hue Bridge
 
 # or hue = Hue('ip address','app-key')
 hue = Hue(host_name, 'hue app key')  # create Hue instance
 
+# If you don't have hue-app-key, press the button and call bridge.connect() (this only needs to be run a single time)
+# hue = Hue(host_name)
+# app_key = hue.bridge.connect() # you can get app_key and storage on disk
+
 lights = hue.lights
 
 for light in lights:
     print(light.on)
     light.on = True
     light.brightness = 80.0
 ```
@@ -75,15 +79,15 @@
             # mirek=200 % or use mirek
         )
     )
 
 # Get all rooms, may be empty
 rooms = hue.rooms
 
-# ScenePost should have a group property, Here we bind with a room
+# ScenePost should have a group property, here we bind with a room
 
 # refer to https://developers.meethue.com/develop/hue-api-v2/api-reference/#resource_scene_post
 # Group associated with this Scene. All services in the group are part of this scene. 
 # If the group is changed the scene is update (e.g. light added/removed)
 scene_post: ScenePost = ScenePost.create_by_parameters(
     actions=actions, name='test', group_rid=rooms[0].id, group_rtype="room"
 )
```

### Comparing `python_hue_v2-1.0.1/pyproject.toml` & `python_hue_v2-1.0.2/pyproject.toml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-1.0.1/PKG-INFO` & `python_hue_v2-1.0.2/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-hue-v2
-Version: 1.0.1
+Version: 1.0.2
 Summary: A python library to control the Philips Hue lighting system.
 Project-URL: Documentation, https://github.com/FengChendian/python-hue-v2#readme
 Project-URL: Issues, https://github.com/FengChendian/python-hue-v2/issues
 Project-URL: Source, https://github.com/FengChendian/python-hue-v2
 Author-email: Yichen Zhao <njuzhaoyichen@gmail.com>
 License-Expression: MIT
 License-File: LICENSE
@@ -42,14 +42,18 @@
 time.sleep(1)  # wait for search
 # Get server by mdns
 host_name = finder.get_bridge_server_lists()[0]  # Here we use first Hue Bridge
 
 # or hue = Hue('ip address','app-key')
 hue = Hue(host_name, 'hue app key')  # create Hue instance
 
+# If you don't have hue-app-key, press the button and call bridge.connect() (this only needs to be run a single time)
+# hue = Hue(host_name)
+# app_key = hue.bridge.connect() # you can get app_key and storage on disk
+
 lights = hue.lights
 
 for light in lights:
     print(light.on)
     light.on = True
     light.brightness = 80.0
 ```
@@ -98,15 +102,15 @@
             # mirek=200 % or use mirek
         )
     )
 
 # Get all rooms, may be empty
 rooms = hue.rooms
 
-# ScenePost should have a group property, Here we bind with a room
+# ScenePost should have a group property, here we bind with a room
 
 # refer to https://developers.meethue.com/develop/hue-api-v2/api-reference/#resource_scene_post
 # Group associated with this Scene. All services in the group are part of this scene. 
 # If the group is changed the scene is update (e.g. light added/removed)
 scene_post: ScenePost = ScenePost.create_by_parameters(
     actions=actions, name='test', group_rid=rooms[0].id, group_rtype="room"
 )
```


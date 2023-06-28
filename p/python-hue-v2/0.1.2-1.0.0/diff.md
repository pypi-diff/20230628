# Comparing `tmp/python_hue_v2-0.1.2.tar.gz` & `tmp/python_hue_v2-1.0.0.tar.gz`

## Comparing `python_hue_v2-0.1.2.tar` & `python_hue_v2-1.0.0.tar`

### file list

```diff
@@ -1,23 +1,39 @@
--rw-r--r--   0        0        0     1124 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/.gitignore
--rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/hue-v2.iml
--rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/misc.xml
--rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/modules.xml
--rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/vcs.xml
--rw-r--r--   0        0        0     2232 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/__about__.py
--rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/__init__.py
--rw-r--r--   0        0        0     5621 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/bridge.py
--rw-r--r--   0        0        0      998 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/grouped_light.py
--rw-r--r--   0        0        0     1251 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/hue.py
--rw-r--r--   0        0        0     1192 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/light.py
--rw-r--r--   0        0        0     1477 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/mdns.py
--rw-r--r--   0        0        0     3854 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/src/python_hue_v2/scene.py
--rw-r--r--   0        0        0     1226 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/tests/test_connection.py
--rw-r--r--   0        0        0       30 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/tests/test_object_convert.py
--rw-r--r--   0        0        0     4672 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/.gitignore
--rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/LICENSE
--rw-r--r--   0        0        0     1561 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/README.md
--rw-r--r--   0        0        0     3208 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/pyproject.toml
--rw-r--r--   0        0        0     2533 2020-02-02 00:00:00.000000 python_hue_v2-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/pytest.ini
+-rw-r--r--   0        0        0     1124 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/.gitignore
+-rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/hue-v2.iml
+-rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/misc.xml
+-rw-r--r--   0        0        0      264 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/modules.xml
+-rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/vcs.xml
+-rw-r--r--   0        0        0     2232 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/inspectionProfiles/Project_Default.xml
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0        0        0      277 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.vscode/settings.json
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/__about__.py
+-rw-r--r--   0        0        0      102 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/__init__.py
+-rw-r--r--   0        0        0     6031 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/bridge.py
+-rw-r--r--   0        0        0     1905 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/grouped_light.py
+-rw-r--r--   0        0        0     1783 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/hue.py
+-rw-r--r--   0        0        0     1192 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/light.py
+-rw-r--r--   0        0        0     1477 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/mdns.py
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/__init__.py
+-rw-r--r--   0        0        0      399 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/resource_identifier_get.py
+-rw-r--r--   0        0        0      511 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/room.py
+-rw-r--r--   0        0        0      503 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/room/room_get.py
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/__init__.py
+-rw-r--r--   0        0        0      262 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/group.py
+-rw-r--r--   0        0        0      301 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/meta_data.py
+-rw-r--r--   0        0        0     4514 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/scene.py
+-rw-r--r--   0        0        0      323 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/target.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/__init__.py
+-rw-r--r--   0        0        0     2613 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action.py
+-rw-r--r--   0        0        0     1072 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_get.py
+-rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_post.py
+-rw-r--r--   0        0        0      451 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_put.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/tests/__init__.py
+-rw-r--r--   0        0        0     3053 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/tests/test_hue.py
+-rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/tests/test_object_convert.py
+-rw-r--r--   0        0        0     4704 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/.gitignore
+-rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/LICENSE
+-rw-r--r--   0        0        0     1628 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/README.md
+-rw-r--r--   0        0        0     3366 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/pyproject.toml
+-rw-r--r--   0        0        0     2632 2020-02-02 00:00:00.000000 python_hue_v2-1.0.0/PKG-INFO
```

### Comparing `python_hue_v2-0.1.2/.github/workflows/python-publish.yml` & `python_hue_v2-1.0.0/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-0.1.2/.idea/inspectionProfiles/Project_Default.xml` & `python_hue_v2-1.0.0/.idea/inspectionProfiles/Project_Default.xml`

 * *Files identical despite different names*

### Comparing `python_hue_v2-0.1.2/src/python_hue_v2/bridge.py` & `python_hue_v2-1.0.0/src/python_hue_v2/bridge.py`

 * *Files 3% similar despite different names*

```diff
@@ -2,14 +2,18 @@
 
 import requests
 import urllib3
 from typing import List, Union
 
 
 class Bridge:
+    """
+    Basic communication class with hue bridge. All Data should be dict or json. \\
+    Don't import another hue device class to this file.
+    """
     def __init__(self, ip_address: str, hue_application_key: str):
         self.ip_address = ip_address
         self.hue_application_key = hue_application_key
         self.hue_application_key_name = 'hue-application-key'
         # url
         self.base_url = f'https://{self.ip_address}/clip/v2/resource'
 
@@ -30,23 +34,24 @@
 
     @staticmethod
     def _get_response_data(r_json: dict) -> list:
         return r_json['data']
 
     @staticmethod
     def _convert_to_data(res: dict) -> List[dict]:
+        print(res)
         if res['errors']:
             raise ConnectionError(res['errors'])
         else:
             return res['data']
 
     def _get_by_id(self, category: str, item_id: str) -> dict:
         url = f'{self.base_url}/{category}/{item_id}'
         res = requests.get(url, headers={self.hue_application_key_name: self.hue_application_key}, verify=False).json()
-        return self._convert_to_data(res)[0]
+        return self._convert_to_data(res)[0] # data length should be 1, so return first element [0]
 
     def _get(self, category: str) -> List[dict]:
         url = f'{self.base_url}/{category}'
         res = requests.get(url, headers={self.hue_application_key_name: self.hue_application_key}, verify=False).json()
         return self._convert_to_data(res)
 
     def _put_by_id(self, category: str, item_id: str, properties: dict) -> dict:
@@ -88,25 +93,28 @@
 
     def get_scene(self, scene_id) -> dict:
         return self._get_by_id(self._scene_category, scene_id)
 
     def set_scene(self, scene_id, scene_property: str, property_value: Union[list, dict]):
         return self._put_by_id(self._scene_category, scene_id, {scene_property: property_value})
 
-    def create_scene(self, properties: dict) -> list:
+    def create_scene(self, properties) -> list:
         return self._post(self._scene_category, properties)
 
     def delete_scene(self, scene_id: str) -> list:
         return self._delete_by_id(self._scene_category, scene_id)
 
     def get_rooms(self) -> List[dict]:
         return self._get(self._room_category)
 
     def get_room(self, room_id: str) -> dict:
         return self._get_by_id(self._room_category, room_id)
+    
+    def set_room(self, room_id, room_property: str, property_value: Union[list, dict]):
+        return self._put_by_id(self._room_category, room_id, {room_property: property_value})
 
     def get_zones(self) -> List[dict]:
         return self._get(self._zone_category)
 
     def get_zone(self, zone_id: str) -> dict:
         return self._get_by_id(self._zone_category, zone_id)
```

### Comparing `python_hue_v2-0.1.2/src/python_hue_v2/grouped_light.py` & `python_hue_v2-1.0.0/src/python_hue_v2/scene/action/action_get.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,37 +1,46 @@
-from .bridge import Bridge
+from ..target import Target
+from .action import Action
 
 
-class GroupedLight:
-    def __init__(self, bridge: Bridge, grouped_light_id: str):
-        self.bridge = bridge
-        self.grouped_light_id: str = grouped_light_id
+class ActionGet:
+    def __init__(self, action_get_data: dict):
+        self._data_dict = action_get_data
 
-    def _get(self):
-        return self.bridge.get_grouped_light(self.grouped_light_id)
+        self._target: dict = action_get_data['target']
+        self.target = Target(self._target)
 
-    def _set(self, property_name: str, property_value: dict) -> dict:
-        return self.bridge.set_grouped_light_service(self.grouped_light_id, property_name, property_value)
+        self._action: dict = action_get_data['action']
+        self.action = Action(self._action)
 
     @property
     def data_dict(self) -> dict:
-        return self._get()
+        return self._data_dict
 
+    @DeprecationWarning
     @property
-    def on(self) -> bool:
-        return self._get()['on']['on']
+    def target_rid(self) -> str:
+        return self._target['rid']
+
+    @DeprecationWarning
+    @property
+    def target_rtype(self) -> str:
+        return self._target['rtype']
 
-    @on.setter
-    def on(self, value: bool):
-        self._set('on', {'on': value})
+    @property
+    def on(self) -> bool:
+        return self.action.on.on
 
+    @DeprecationWarning
     @property
-    def type(self) -> str:
-        return self._get()['type']
+    def color(self):
+        return self._action['color']
 
+    @DeprecationWarning
     @property
-    def brightness(self) -> float:
-        return self._get()['dimming']['brightness']
+    def color_xy(self) -> dict:
+        return self._action['color']['xy']
 
-    @brightness.setter
-    def brightness(self, value: float):
-        self._set('dimming', {'brightness': value})
+    @DeprecationWarning
+    @property
+    def color_temperature(self) -> dict:
+        return self._action['color_temperature']
```

### Comparing `python_hue_v2-0.1.2/src/python_hue_v2/light.py` & `python_hue_v2-1.0.0/src/python_hue_v2/light.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-0.1.2/src/python_hue_v2/mdns.py` & `python_hue_v2-1.0.0/src/python_hue_v2/mdns.py`

 * *Files identical despite different names*

### Comparing `python_hue_v2-0.1.2/.gitignore` & `python_hue_v2-1.0.0/.gitignore`

 * *Files 2% similar despite different names*

```diff
@@ -22,14 +22,16 @@
 wheels/
 share/python-wheels/
 *.egg-info/
 .installed.cfg
 *.egg
 MANIFEST
 
+tests/create_scene_config.json
+
 # PyInstaller
 #  Usually these files are written by a python script from a template
 #  before PyInstaller builds the exe, so as to inject date/other infos into it.
 *.manifest
 *.spec
 
 # Installer logs
```

### Comparing `python_hue_v2-0.1.2/LICENSE` & `python_hue_v2-1.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `python_hue_v2-0.1.2/README.md` & `python_hue_v2-1.0.0/README.md`

 * *Files 16% similar despite different names*

```diff
@@ -70,10 +70,15 @@
 bridge = hue.bridge
 
 bridge.get_lights()
 bridge.set_light('id', light_property_name='on', property_value={'on': True})
 
 bridge.get_zones()
 ```
+
+## Attention
+
+Some API may be de deprecated When major version updates.
+
 ## TODO
 
-- Zones, Rooms Control Class
+- Zones Control Class
```

### Comparing `python_hue_v2-0.1.2/pyproject.toml` & `python_hue_v2-1.0.0/pyproject.toml`

 * *Files 13% similar despite different names*

```diff
@@ -7,129 +7,130 @@
 dynamic = ["version"]
 description = 'A python library to control the Philips Hue lighting system.'
 readme = "README.md"
 requires-python = ">=3.8"
 license = "MIT"
 keywords = []
 authors = [
-  { name = "Yichen Zhao", email = "njuzhaoyichen@gmail.com" },
+    { name = "Yichen Zhao", email = "njuzhaoyichen@gmail.com" },
 ]
 classifiers = [
-  "Development Status :: 4 - Beta",
-  "Programming Language :: Python",
-  "Programming Language :: Python :: 3.8",
-  "Programming Language :: Python :: 3.9",
-  "Programming Language :: Python :: 3.10",
-  "Programming Language :: Python :: 3.11",
-  "Programming Language :: Python :: Implementation :: CPython",
-  "Programming Language :: Python :: Implementation :: PyPy",
+    "Development Status :: 4 - Beta",
+    "Programming Language :: Python",
+    "Programming Language :: Python :: 3.8",
+    "Programming Language :: Python :: 3.9",
+    "Programming Language :: Python :: 3.10",
+    "Programming Language :: Python :: 3.11",
+    "Programming Language :: Python :: Implementation :: CPython",
+    "Programming Language :: Python :: Implementation :: PyPy",
 ]
 dependencies = [
-"requests >= 2.30.0"
+    "requests >= 2.30.0",
+    "zeroconf >= 0.62.0"
 ]
 
 [project.urls]
 Documentation = "https://github.com/FengChendian/python-hue-v2#readme"
 Issues = "https://github.com/FengChendian/python-hue-v2/issues"
 Source = "https://github.com/FengChendian/python-hue-v2"
 
 [tool.hatch.version]
 path = "src/python_hue_v2/__about__.py"
 
 [tool.hatch.envs.default]
 dependencies = [
-  "coverage[toml]>=6.5",
-  "pytest",
+    "coverage[toml]>=6.5",
+    "pytest",
 ]
 [tool.hatch.envs.default.scripts]
 test = "pytest {args:tests}"
 test-cov = "coverage run -m pytest {args:tests}"
 cov-report = [
-  "- coverage combine",
-  "coverage report",
+    "- coverage combine",
+    "coverage report",
 ]
 cov = [
-  "test-cov",
-  "cov-report",
+    "test-cov",
+    "cov-report",
 ]
 
 [[tool.hatch.envs.all.matrix]]
 python = ["3.8", "3.9", "3.10", "3.11"]
 
 [tool.hatch.envs.lint]
 detached = true
 dependencies = [
-  "black>=23.1.0",
-  "mypy>=1.0.0",
-  "ruff>=0.0.243",
+    "black>=23.1.0",
+    "mypy>=1.0.0",
+    "ruff>=0.0.243",
 ]
 [tool.hatch.envs.lint.scripts]
 typing = "mypy --install-types --non-interactive {args:src/python_hue_v2 tests}"
 style = [
-  "ruff {args:.}",
-  "black --check --diff {args:.}",
+    "ruff {args:.}",
+    "black --check --diff {args:.}",
 ]
 fmt = [
-  "black {args:.}",
-  "ruff --fix {args:.}",
-  "style",
+    "black {args:.}",
+    "ruff --fix {args:.}",
+    "style",
 ]
 all = [
-  "style",
-  "typing",
+    "style",
+    "typing",
 ]
 
 [tool.black]
 target-version = ["py38"]
 line-length = 120
 skip-string-normalization = true
 
 [tool.ruff]
 target-version = "py38"
 line-length = 120
 select = [
-  "A",
-  "ARG",
-  "B",
-  "C",
-  "DTZ",
-  "E",
-  "EM",
-  "F",
-  "FBT",
-  "I",
-  "ICN",
-  "ISC",
-  "N",
-  "PLC",
-  "PLE",
-  "PLR",
-  "PLW",
-  "Q",
-  "RUF",
-  "S",
-  "T",
-  "TID",
-  "UP",
-  "W",
-  "YTT",
+    "A",
+    "ARG",
+    "B",
+    "C",
+    "DTZ",
+    "E",
+    "EM",
+    "F",
+    "FBT",
+    "I",
+    "ICN",
+    "ISC",
+    "N",
+    "PLC",
+    "PLE",
+    "PLR",
+    "PLW",
+    "Q",
+    "RUF",
+    "S",
+    "T",
+    "TID",
+    "UP",
+    "W",
+    "YTT",
 ]
 ignore = [
-  # Allow non-abstract empty methods in abstract base classes
-  "B027",
-  # Allow boolean positional values in function calls, like `dict.get(... True)`
-  "FBT003",
-  # Ignore checks for possible passwords
-  "S105", "S106", "S107",
-  # Ignore complexity
-  "C901", "PLR0911", "PLR0912", "PLR0913", "PLR0915",
+    # Allow non-abstract empty methods in abstract base classes
+    "B027",
+    # Allow boolean positional values in function calls, like `dict.get(... True)`
+    "FBT003",
+    # Ignore checks for possible passwords
+    "S105", "S106", "S107",
+    # Ignore complexity
+    "C901", "PLR0911", "PLR0912", "PLR0913", "PLR0915",
 ]
 unfixable = [
-  # Don't touch unused imports
-  "F401",
+    # Don't touch unused imports
+    "F401",
 ]
 
 [tool.ruff.isort]
 known-first-party = ["python_hue_v2"]
 
 [tool.ruff.flake8-tidy-imports]
 ban-relative-imports = "all"
@@ -139,20 +140,20 @@
 "tests/**/*" = ["PLR2004", "S101", "TID252"]
 
 [tool.coverage.run]
 source_pkgs = ["python_hue_v2", "tests"]
 branch = true
 parallel = true
 omit = [
-  "src/python_hue_v2/__about__.py",
+    "src/python_hue_v2/__about__.py",
 ]
 
 [tool.coverage.paths]
 python_hue_v2 = ["src/python_hue_v2", "*/python-hue-v2/src/python_hue_v2"]
 tests = ["tests", "*/python-hue-v2/tests"]
 
 [tool.coverage.report]
 exclude_lines = [
-  "no cov",
-  "if __name__ == .__main__.:",
-  "if TYPE_CHECKING:",
+    "no cov",
+    "if __name__ == .__main__.:",
+    "if TYPE_CHECKING:",
 ]
```

### Comparing `python_hue_v2-0.1.2/PKG-INFO` & `python_hue_v2-1.0.0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-hue-v2
-Version: 0.1.2
+Version: 1.0.0
 Summary: A python library to control the Philips Hue lighting system.
 Project-URL: Documentation, https://github.com/FengChendian/python-hue-v2#readme
 Project-URL: Issues, https://github.com/FengChendian/python-hue-v2/issues
 Project-URL: Source, https://github.com/FengChendian/python-hue-v2
 Author-email: Yichen Zhao <njuzhaoyichen@gmail.com>
 License-Expression: MIT
 License-File: LICENSE
@@ -14,14 +14,15 @@
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Requires-Python: >=3.8
 Requires-Dist: requests>=2.30.0
+Requires-Dist: zeroconf>=0.62.0
 Description-Content-Type: text/markdown
 
 # Python Hue V2
 
 Python library to control the Philips Hue lighting system for Hue-V2 API.
 
 ## Features
@@ -92,10 +93,15 @@
 bridge = hue.bridge
 
 bridge.get_lights()
 bridge.set_light('id', light_property_name='on', property_value={'on': True})
 
 bridge.get_zones()
 ```
+
+## Attention
+
+Some API may be de deprecated When major version updates.
+
 ## TODO
 
-- Zones, Rooms Control Class
+- Zones Control Class
```


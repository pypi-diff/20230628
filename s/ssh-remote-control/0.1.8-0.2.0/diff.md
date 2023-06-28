# Comparing `tmp/ssh_remote_control-0.1.8.tar.gz` & `tmp/ssh_remote_control-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ssh_remote_control-0.1.8.tar", last modified: Tue Jun 27 09:53:23 2023, max compression
+gzip compressed data, was "ssh_remote_control-0.2.0.tar", last modified: Wed Jun 28 10:41:41 2023, max compression
```

## Comparing `ssh_remote_control-0.1.8.tar` & `ssh_remote_control-0.2.0.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 09:53:23.957049 ssh_remote_control-0.1.8/
--rw-rw-rw-   0        0        0     1084 2023-06-24 10:20:33.000000 ssh_remote_control-0.1.8/LICENSE
--rw-rw-rw-   0        0        0     1569 2023-06-27 09:53:23.955046 ssh_remote_control-0.1.8/PKG-INFO
--rw-rw-rw-   0        0        0      973 2023-06-24 10:20:33.000000 ssh_remote_control-0.1.8/README.md
--rw-rw-rw-   0        0        0      846 2023-06-27 09:51:07.000000 ssh_remote_control-0.1.8/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-27 09:53:23.957049 ssh_remote_control-0.1.8/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-27 09:53:23.852045 ssh_remote_control-0.1.8/src/
-drwxrwxrwx   0        0        0        0 2023-06-27 09:53:23.895045 ssh_remote_control-0.1.8/src/ssh_remote_control/
--rw-rw-rw-   0        0        0    10418 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/__init__.py
--rw-rw-rw-   0        0        0     3503 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/collection.py
--rw-rw-rw-   0        0        0     6533 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/command.py
-drwxrwxrwx   0        0        0        0 2023-06-27 09:53:23.952050 ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/
--rw-rw-rw-   0        0        0      161 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/__init__.py
--rw-rw-rw-   0        0        0     1004 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/const.py
--rw-rw-rw-   0        0        0     3968 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/linux.py
--rw-rw-rw-   0        0        0     3812 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/windows_cmd.py
--rw-rw-rw-   0        0        0     4077 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/windows_ps.py
--rw-rw-rw-   0        0        0      637 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/errors.py
--rw-rw-rw-   0        0        0      645 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/event.py
--rw-rw-rw-   0        0        0      222 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/helpers.py
--rw-rw-rw-   0        0        0     1313 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/locker.py
--rw-rw-rw-   0        0        0     4340 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/manager.py
--rw-rw-rw-   0        0        0     9624 2023-06-27 09:48:00.000000 ssh_remote_control-0.1.8/src/ssh_remote_control/sensor.py
-drwxrwxrwx   0        0        0        0 2023-06-27 09:53:23.940073 ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/
--rw-rw-rw-   0        0        0     1569 2023-06-27 09:53:23.000000 ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      840 2023-06-27 09:53:23.000000 ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 09:53:23.000000 ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       89 2023-06-27 09:53:23.000000 ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/requires.txt
--rw-rw-rw-   0        0        0       19 2023-06-27 09:53:23.000000 ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 10:41:41.282119 ssh_remote_control-0.2.0/
+-rw-rw-rw-   0        0        0     1084 2023-06-24 10:20:33.000000 ssh_remote_control-0.2.0/LICENSE
+-rw-rw-rw-   0        0        0     1569 2023-06-28 10:41:41.279117 ssh_remote_control-0.2.0/PKG-INFO
+-rw-rw-rw-   0        0        0      973 2023-06-24 10:20:33.000000 ssh_remote_control-0.2.0/README.md
+-rw-rw-rw-   0        0        0      846 2023-06-28 10:40:43.000000 ssh_remote_control-0.2.0/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:41:41.283116 ssh_remote_control-0.2.0/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 10:41:41.169983 ssh_remote_control-0.2.0/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 10:41:41.212988 ssh_remote_control-0.2.0/src/ssh_remote_control/
+-rw-rw-rw-   0        0        0    10443 2023-06-28 10:38:00.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/__init__.py
+-rw-rw-rw-   0        0        0     3503 2023-06-28 10:38:00.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/collection.py
+-rw-rw-rw-   0        0        0     5370 2023-06-28 10:38:00.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/command.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:41:41.277116 ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/
+-rw-rw-rw-   0        0        0      161 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/__init__.py
+-rw-rw-rw-   0        0        0     1004 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/const.py
+-rw-rw-rw-   0        0        0     3825 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/linux.py
+-rw-rw-rw-   0        0        0     3720 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/windows_cmd.py
+-rw-rw-rw-   0        0        0     3961 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/windows_ps.py
+-rw-rw-rw-   0        0        0      637 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/errors.py
+-rw-rw-rw-   0        0        0      645 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/event.py
+-rw-rw-rw-   0        0        0      222 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/helpers.py
+-rw-rw-rw-   0        0        0     1346 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/locker.py
+-rw-rw-rw-   0        0        0     4526 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/manager.py
+-rw-rw-rw-   0        0        0     8447 2023-06-28 10:38:01.000000 ssh_remote_control-0.2.0/src/ssh_remote_control/sensor.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:41:41.261276 ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/
+-rw-rw-rw-   0        0        0     1569 2023-06-28 10:41:41.000000 ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      840 2023-06-28 10:41:41.000000 ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:41:41.000000 ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       89 2023-06-28 10:41:41.000000 ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       19 2023-06-28 10:41:41.000000 ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/top_level.txt
```

### Comparing `ssh_remote_control-0.1.8/LICENSE` & `ssh_remote_control-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `ssh_remote_control-0.1.8/PKG-INFO` & `ssh_remote_control-0.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ssh_remote_control
-Version: 0.1.8
+Version: 0.2.0
 Summary: Control and monitor remote devices through SSH
 Author-email: zhbjsh <zhbjsh@outlook.com>
 Project-URL: Homepage, https://github.com/zhbjsh/ssh-remote-control
 Project-URL: Bug Tracker, https://github.com/zhbjsh/ssh-remote-control/issues
 Keywords: ssh,command line,remote control
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `ssh_remote_control-0.1.8/README.md` & `ssh_remote_control-0.2.0/README.md`

 * *Files identical despite different names*

### Comparing `ssh_remote_control-0.1.8/pyproject.toml` & `ssh_remote_control-0.2.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ssh_remote_control"
-version = "0.1.8"
+version = "0.2.0"
 authors = [
   { name="zhbjsh", email="zhbjsh@outlook.com" },
 ]
 description = "Control and monitor remote devices through SSH"
 readme = "README.md"
 requires-python = ">=3.10"
 classifiers = [
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/__init__.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -7,29 +7,29 @@
 
 import async_timeout
 import icmplib
 import paramiko
 import wakeonlan
 
 from .collection import Collection
-from .command import ActionCommand, Command, CommandOutput, SensorCommand
+from .command import ActionCommand, Command, SensorCommand
 from .default_collections import ActionKey, SensorKey
 from .errors import (
     CommandExecuteError,
     CommandFormatError,
     MACAdressUnavailableError,
     OfflineError,
     SSHAuthError,
     SSHConnectError,
     SSHHostKeyUnknownError,
 )
 from .event import Event
 from .helpers import name_to_key
-from .manager import DEFAULT_COMMAND_TIMEOUT, Manager
-from .sensor import DynamicSensor, Sensor
+from .manager import DEFAULT_COMMAND_TIMEOUT, CommandOutput, Manager
+from .sensor import BinarySensor, NumberSensor, Sensor, TextSensor
 
 _LOGGER = logging.getLogger(__name__)
 _TEST_COMMAND = Command("")
 
 DEFAULT_SSH_PORT = 22
 DEFAULT_PING_TIMEOUT = 4
 DEFAULT_SSH_TIMEOUT = 4
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/collection.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/collection.py`

 * *Files identical despite different names*

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/command.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/command.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,51 +1,36 @@
 from __future__ import annotations
 
 from collections.abc import Callable
-from dataclasses import dataclass
+from dataclasses import KW_ONLY, dataclass, field
 from string import Formatter
-from time import time
 from typing import TYPE_CHECKING
 
 from .errors import CommandExecuteError, CommandFormatError
 from .helpers import name_to_key
-from .sensor import DynamicSensor, Sensor
+from .sensor import Sensor
 
 if TYPE_CHECKING:
-    from .manager import Manager
+    from .manager import CommandOutput, Manager
 
 SENSOR_PLACEHOLDER_KEY = "_"
 
 
-@dataclass(frozen=True)
-class CommandOutput:
-    """The CommandOutput class."""
-
-    timestamp: float
-    stdout: list[str] | None = None
-    stderr: list[str] | None = None
-    code: int | None = None
-
-
+@dataclass
 class Command:
     """The Command class."""
 
-    def __init__(
-        self,
-        string: str,
-        *,
-        timeout: float | None = None,
-        renderer: Callable[[str], str] | None = None,
-    ) -> None:
-        self.string = string
-        self.timeout = timeout
-        self.renderer = renderer
+    string: str
+    _: KW_ONLY
+    timeout: float | None = None
+    renderer: Callable[[str], str] | None = None
 
     @property
     def field_keys(self) -> list[str]:
+        """Field keys."""
         return {key for _, key, _, _ in Formatter().parse(self.string) if key}
 
     def get_context_keys(self, manager: Manager) -> set[str]:
         """Get context keys."""
         return {key for key in self.field_keys if key not in manager.sensors_by_key}
 
     def get_sensor_keys(self, manager: Manager) -> set[str]:
@@ -117,79 +102,55 @@
             output.stderr,
             output.code,
         )
 
         return output
 
 
+@dataclass
 class ActionCommand(Command):
     """The ActionCommand class."""
 
-    def __init__(
-        self,
-        string: str,
-        name: str | None = None,
-        key: str | None = None,
-        *,
-        timeout: float | None = None,
-        renderer: Callable[[str], str] | None = None,
-        options: dict | None = None,
-    ) -> None:
-        super().__init__(string, timeout=timeout, renderer=renderer)
-        self.name = name
-        self.key = key or name_to_key(name)
-        self.options = options or {}
+    name: str | None = None
+    key: str | None = None
+    _: KW_ONLY
+    options: dict = field(default_factory=dict)
+
+    def __post_init__(self):
+        self.key = self.key or name_to_key(self.name)
 
 
+@dataclass
 class SensorCommand(Command):
     """The SensorCommand class."""
 
-    last_update: float | None = None
+    sensors: list[Sensor] = field(default_factory=list)
+    _: KW_ONLY
+    interval: int | None = None
 
-    def __init__(
-        self,
-        string: str,
-        sensors: list[Sensor],
-        *,
-        timeout: float | None = None,
-        renderer: Callable[[str], str] | None = None,
-        interval: int | None = None,
-    ) -> None:
-        super().__init__(string, timeout=timeout, renderer=renderer)
-        self.sensors = sensors
-        self.interval = interval
+    def __post_init__(self):
+        self.last_update: float | None = None
 
     @property
     def sensors_by_key(self) -> dict[str, Sensor]:
         """Sensors by key."""
-        result = {}
-        for sensor in self.sensors:
-            if sensor.key == SENSOR_PLACEHOLDER_KEY:
-                continue
-            result.update(
-                {sensor.key: sensor, **sensor.child_sensors_by_key}
-                if isinstance(sensor, DynamicSensor)
-                else {sensor.key: sensor}
-            )
-        return result
+        return {
+            sensor.key: sensor
+            for command_sensor in self.sensors
+            for sensor in (command_sensor, *command_sensor.child_sensors)
+            if command_sensor.key != SENSOR_PLACEHOLDER_KEY
+        }
 
     @property
-    def dynamic_sensor(self) -> DynamicSensor | None:
+    def dynamic_sensor(self) -> Sensor | None:
         return next(
-            (sensor for sensor in self.sensors if isinstance(sensor, DynamicSensor)),
+            (sensor for sensor in self.sensors if sensor.is_dynamic),
             None,
         )
 
-    @property
-    def needs_update(self):
-        """The command was never updated or reached its interval."""
-        return self.last_update is None or (
-            self.interval and time() - self.last_update >= self.interval
-        )
-
     def remove_sensor(self, key: str) -> None:
         """Remove a sensor."""
         self.sensors = [
             Sensor(key=SENSOR_PLACEHOLDER_KEY) if sensor.key == key else sensor
             for sensor in self.sensors
         ]
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/const.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/const.py`

 * *Files identical despite different names*

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/linux.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/linux.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from ..collection import Collection
 from ..command import ActionCommand, SensorCommand
-from ..sensor import DynamicSensor, Sensor
+from ..sensor import BinarySensor, NumberSensor, TextSensor
 from .const import ActionKey, ActionName, SensorKey, SensorName
 
 linux = Collection(
     "Linux",
     [
         ActionCommand(
             "/sbin/shutdown -h now",
@@ -17,119 +17,114 @@
             ActionKey.RESTART,
         ),
     ],
     [
         SensorCommand(
             "cat /sys/class/net/{interface}/address",
             [
-                Sensor(
+                TextSensor(
                     SensorName.MAC_ADDRESS,
                     SensorKey.MAC_ADDRESS,
                 )
             ],
         ),
         SensorCommand(
             "cat /sys/class/net/{interface}/device/power/wakeup",
             [
-                Sensor(
+                BinarySensor(
                     SensorName.WOL_SUPPORT,
                     SensorKey.WOL_SUPPORT,
-                    value_type=bool,
                     payload_on="enabled",
                 )
             ],
         ),
         SensorCommand(
             "/sbin/route -n | awk '($1 == \"0.0.0.0\") {{print $NF; exit}}'",
             [
-                Sensor(
+                TextSensor(
                     SensorName.INTERFACE,
                     SensorKey.INTERFACE,
                 )
             ],
         ),
         SensorCommand(
             "uname -a | awk '{{print $1; print $3; print $2; print $(NF-1);}}'",
             [
-                Sensor(
+                TextSensor(
                     SensorName.OS_NAME,
                     SensorKey.OS_NAME,
                 ),
-                Sensor(
+                TextSensor(
                     SensorName.OS_VERSION,
                     SensorKey.OS_VERSION,
                 ),
-                Sensor(
+                TextSensor(
                     SensorName.HOSTNAME,
                     SensorKey.HOSTNAME,
                 ),
-                Sensor(
+                TextSensor(
                     SensorName.MACHINE_TYPE,
                     SensorKey.MACHINE_TYPE,
                 ),
             ],
         ),
         # TODO: OS_ARCHITECTURE
         SensorCommand(
             "free -m | awk 'tolower($0)~/mem/ {{print $2}}'",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.TOTAL_MEMORY,
                     SensorKey.TOTAL_MEMORY,
-                    value_type=int,
-                    value_unit="MB",
+                    unit="MB",
                 )
             ],
         ),
         SensorCommand(
             "free -m | awk 'tolower($0)~/mem/ {{print $4}}'",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.FREE_MEMORY,
                     SensorKey.FREE_MEMORY,
-                    value_type=int,
-                    value_unit="MB",
+                    unit="MB",
                 )
             ],
             interval=30,
         ),
         SensorCommand(
             "df -m | awk '/^\\/dev\\// {{print $6 \"|\" $4}}'",
             [
-                DynamicSensor(
+                NumberSensor(
                     SensorName.FREE_DISK_SPACE,
                     SensorKey.FREE_DISK_SPACE,
-                    value_type=int,
-                    value_unit="MB",
+                    dynamic=True,
                     separator="|",
+                    unit="MB",
                 )
             ],
             interval=300,
         ),
         SensorCommand(
             "top -bn1 | head -n3 | awk 'tolower($0)~/cpu/ "
             + "{{for(i=1;i<NF;i++){{if(tolower($i)~/cpu/)"
             + "{{idle=$(i+7); print 100-idle;}}}}}}'",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.CPU_LOAD,
                     SensorKey.CPU_LOAD,
-                    value_type=int,
-                    value_unit="%",
+                    unit="%",
                 )
             ],
             interval=30,
         ),
         SensorCommand(
             "echo $(($(cat /sys/class/thermal/thermal_zone0/temp) / 1000))",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.TEMPERATURE,
                     SensorKey.TEMPERATURE,
-                    value_type=int,
-                    value_unit="°C",
+                    unit="°C",
                 )
             ],
             interval=60,
         ),
     ],
 )
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/windows_cmd.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/windows_cmd.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from ..collection import Collection
 from ..command import ActionCommand, SensorCommand
-from ..sensor import Sensor
+from ..sensor import BinarySensor, NumberSensor, TextSensor
 from .const import ActionKey, ActionName, SensorKey, SensorName
 
 windows_cmd = Collection(
     "Windows",
     [
         ActionCommand(
             "shutdown -t 0",
@@ -21,107 +21,103 @@
         # TODO: MAC_ADDRESS
         # TODO: WOL_SUPPORT
         # TODO: INTERFACE
         SensorCommand(
             "for /f \"skip=1 delims=\" %i in ('wmic ComputerSystem get SystemType') "
             + "do @echo %i",
             [
-                Sensor(
+                TextSensor(
                     SensorName.MACHINE_TYPE,
                     SensorKey.MACHINE_TYPE,
                 )
             ],
         ),
         SensorCommand(
             "hostname",
             [
-                Sensor(
+                TextSensor(
                     SensorName.HOSTNAME,
                     SensorKey.HOSTNAME,
                 )
             ],
         ),
         SensorCommand(
             "for /f \"skip=1 delims=\" %i in ('wmic OS get Caption') do @echo %i",
             [
-                Sensor(
+                TextSensor(
                     SensorName.OS_NAME,
                     SensorKey.OS_NAME,
                 )
             ],
         ),
         SensorCommand(
             "for /f \"skip=1 delims=\" %i in ('wmic OS get Version') do @echo %i",
             [
-                Sensor(
+                TextSensor(
                     SensorName.OS_VERSION,
                     SensorKey.OS_VERSION,
                 )
             ],
         ),
         SensorCommand(
             "for /f \"skip=1 delims=\" %i in ('wmic OS get OSArchitecture') do @echo %i",
             [
-                Sensor(
+                TextSensor(
                     SensorName.OS_ARCHITECTURE,
                     SensorKey.OS_ARCHITECTURE,
                 )
             ],
         ),
         SensorCommand(
             # TODO: Should return MB but number is too long
             "for /f  %i in ('wmic ComputerSystem get TotalPhysicalMemory ^| "
             + 'findstr /r "\\<[0-9][0-9]*\\>"\') '
             + "do set /a mb=%i / 1024 / 1024",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.TOTAL_MEMORY,
                     SensorKey.TOTAL_MEMORY,
-                    value_type=int,
-                    value_unit="MB",
+                    unit="MB",
                 )
             ],
         ),
         SensorCommand(
             "for /f  %i in ('wmic OS get FreePhysicalMemory ^| "
             + 'findstr /r "\\<[0-9][0-9]*\\>"\') '
             + "do set /a mb=%i / 1024",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.FREE_MEMORY,
                     SensorKey.FREE_MEMORY,
-                    value_type=int,
-                    value_unit="MB",
+                    unit="MB",
                 )
             ],
             interval=30,
         ),
         # TODO: FREE_DISK_SPACE
         SensorCommand(
             "for /f \"skip=1\" %i in ('wmic CPU get LoadPercentage') do @echo %i",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.CPU_LOAD,
                     SensorKey.CPU_LOAD,
-                    value_type=int,
-                    value_unit="%",
+                    unit="%",
                 )
             ],
             interval=30,
         ),
         SensorCommand(
             "for /f  %i in ('wmic /namespace:\\\\root\\wmi "
             + "PATH MSAcpi_ThermalZoneTemperature get CurrentTemperature ^| "
             + 'findstr /r "\\<[0-9][0-9]*\\>"\') '
             + "do set /a mb=(%i - 2732) / 10",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.TEMPERATURE,
                     SensorKey.TEMPERATURE,
-                    value_type=int,
-                    value_unit="°C",
+                    unit="°C",
                 )
             ],
             interval=60,
         ),
     ],
 )
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/default_collections/windows_ps.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/default_collections/windows_ps.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from ..collection import Collection
 from ..command import ActionCommand, SensorCommand
-from ..sensor import DynamicSensor, Sensor
+from ..sensor import BinarySensor, NumberSensor, TextSensor
 from .const import ActionKey, ActionName, SensorKey, SensorName
 
 windows_ps = Collection(
     "Windows (Power Shell)",
     [
         ActionCommand(
             "Stop-Computer -Force",
@@ -23,111 +23,107 @@
         # TODO: INTERFACE
         SensorCommand(
             "$x = Get-CimInstance Win32_ComputerSystem | "
             + "Select Name, SystemType;"
             + "$x.Name;"
             + "$x.SystemType;",
             [
-                Sensor(
+                TextSensor(
                     SensorName.HOSTNAME,
                     SensorKey.HOSTNAME,
                 ),
-                Sensor(
+                TextSensor(
                     SensorName.MACHINE_TYPE,
                     SensorKey.MACHINE_TYPE,
                 ),
             ],
         ),
         SensorCommand(
             "$x = Get-CimInstance Win32_OperatingSystem | "
             + "Select Caption, Version, OSArchitecture;"
             + "$x.Caption;"
             + "$x.Version;"
             + "$x.OSArchitecture;",
             [
-                Sensor(
+                TextSensor(
                     SensorName.OS_NAME,
                     SensorKey.OS_NAME,
                 ),
-                Sensor(
+                TextSensor(
                     SensorName.OS_VERSION,
                     SensorKey.OS_VERSION,
                 ),
-                Sensor(
+                TextSensor(
                     SensorName.OS_ARCHITECTURE,
                     SensorKey.OS_ARCHITECTURE,
                 ),
             ],
         ),
         SensorCommand(
             "$x = Get-CimInstance Win32_ComputerSystem | "
             + "Select TotalPhysicalMemory;"
             + "[math]::Round($x.TotalPhysicalMemory/1MB);",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.TOTAL_MEMORY,
                     SensorKey.TOTAL_MEMORY,
-                    value_type=int,
-                    value_unit="MB",
+                    unit="MB",
                 )
             ],
         ),
         SensorCommand(
             "$x = Get-CimInstance Win32_OperatingSystem | "
             + "Select FreePhysicalMemory;"
             + "[math]::Round($x.FreePhysicalMemory/1KB);",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.FREE_MEMORY,
                     SensorKey.FREE_MEMORY,
-                    value_type=int,
-                    value_unit="MB",
+                    unit="MB",
                 )
             ],
             interval=30,
         ),
         SensorCommand(
             "Get-CimInstance Win32_LogicalDisk | "
             + "Select DeviceID, FreeSpace | ForEach-Object "
             + '{{$_.DeviceID+"|"+[math]::Round($_.FreeSpace/1MB)}}',
             [
-                DynamicSensor(
+                NumberSensor(
                     SensorName.FREE_DISK_SPACE,
                     SensorKey.FREE_DISK_SPACE,
-                    value_type=int,
-                    value_unit="MB",
+                    dynamic=True,
                     separator="|",
+                    unit="MB",
                 )
             ],
             interval=300,
         ),
         SensorCommand(
             "$x = Get-CimInstance Win32_Processor | "
             + "Select LoadPercentage;"
             + "$x.LoadPercentage;",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.CPU_LOAD,
                     SensorKey.CPU_LOAD,
-                    value_type=int,
-                    value_unit="%",
+                    unit="%",
                 )
             ],
             interval=30,
         ),
         SensorCommand(
             "$x = Get-CimInstance msacpi_thermalzonetemperature "
             + '-namespace "root/wmi" | '
             + "Select CurrentTemperature;"
             + "($x.CurrentTemperature - 2732) / 10;",
             [
-                Sensor(
+                NumberSensor(
                     SensorName.TEMPERATURE,
                     SensorKey.TEMPERATURE,
-                    value_type=int,
-                    value_unit="°C",
+                    unit="°C",
                 )
             ],
             interval=60,
         ),
     ],
 )
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/errors.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/errors.py`

 * *Files identical despite different names*

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/event.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/event.py`

 * *Files identical despite different names*

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/locker.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/locker.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,14 +3,16 @@
 import asyncio
 from collections.abc import Coroutine
 from functools import wraps
 import inspect
 
 
 def locked(coro: Coroutine):
+    """The locked decorator."""
+
     @wraps(coro)
     async def wrapper(instance: Locker, *args, **kwargs):
         async with instance.lock:
             return await coro(instance, *args, **kwargs)
 
     return wrapper
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control/manager.py` & `ssh_remote_control-0.2.0/src/ssh_remote_control/manager.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,25 +1,36 @@
 from __future__ import annotations
 
 from collections.abc import Sequence
+from dataclasses import dataclass
 import logging
 from typing import Any
 
 from .collection import Collection
-from .command import Command, CommandOutput
+from .command import Command
 from .errors import CommandExecuteError, CommandFormatError
 from .locker import Locker
 from .sensor import Sensor
 
 _LOGGER = logging.getLogger(__name__)
 
 DEFAULT_NAME = "Manager"
 DEFAULT_COMMAND_TIMEOUT = 15
 
 
+@dataclass(frozen=True)
+class CommandOutput:
+    """The CommandOutput class."""
+
+    timestamp: float
+    stdout: list[str]
+    stderr: list[str]
+    code: int
+
+
 class Manager(Collection, Locker):
     """The Manager class."""
 
     def __init__(
         self,
         *,
         name: str = DEFAULT_NAME,
@@ -87,15 +98,15 @@
         """Poll multiple sensors.
 
         Raises:
             CommandFormatError (`raise_errors`)
             CommandExecuteError (`raise_errors`)
         """
         sensors = [self.get_sensor(key) for key in keys]
-        commands = {self.get_sensor_command(key) for key in keys}
+        commands = [self.get_sensor_command(key) for key in set(keys)]
 
         for command in commands:
             try:
                 await self.async_execute_command(command)
             except (CommandFormatError, CommandExecuteError):
                 if raise_errors:
                     raise
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/PKG-INFO` & `ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ssh-remote-control
-Version: 0.1.8
+Version: 0.2.0
 Summary: Control and monitor remote devices through SSH
 Author-email: zhbjsh <zhbjsh@outlook.com>
 Project-URL: Homepage, https://github.com/zhbjsh/ssh-remote-control
 Project-URL: Bug Tracker, https://github.com/zhbjsh/ssh-remote-control/issues
 Keywords: ssh,command line,remote control
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `ssh_remote_control-0.1.8/src/ssh_remote_control.egg-info/SOURCES.txt` & `ssh_remote_control-0.2.0/src/ssh_remote_control.egg-info/SOURCES.txt`

 * *Files identical despite different names*


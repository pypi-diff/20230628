# Comparing `tmp/pybelt-1.1b1.tar.gz` & `tmp/pybelt-1.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\pybelt-1.1b1.tar", last modified: Tue May 16 07:31:38 2023, max compression
+gzip compressed data, was "dist\pybelt-1.2.0.tar", last modified: Wed Jun 28 14:41:55 2023, max compression
```

## Comparing `pybelt-1.1b1.tar` & `pybelt-1.2.0.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxrwxrwx   0        0        0        0 2023-05-16 07:31:38.000000 pybelt-1.1b1/
--rw-rw-rw-   0        0        0     2472 2023-05-16 07:31:38.000000 pybelt-1.1b1/PKG-INFO
--rw-rw-rw-   0        0        0     1636 2021-01-11 09:49:47.000000 pybelt-1.1b1/README.md
-drwxrwxrwx   0        0        0        0 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt/
--rw-rw-rw-   0        0        0      112 2020-06-22 14:06:02.000000 pybelt-1.1b1/pybelt/__init__.py
--rw-rw-rw-   0        0        0    37069 2023-05-16 07:04:42.000000 pybelt-1.1b1/pybelt/_communication_interface.py
--rw-rw-rw-   0        0        0     8833 2023-01-05 13:18:44.000000 pybelt-1.1b1/pybelt/_gatt_profile.py
--rw-rw-rw-   0        0        0    59380 2023-05-09 09:02:51.000000 pybelt-1.1b1/pybelt/belt_controller.py
--rw-rw-rw-   0        0        0     3980 2023-05-15 13:07:23.000000 pybelt-1.1b1/pybelt/belt_scanner.py
-drwxrwxrwx   0        0        0        0 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt.egg-info/
--rw-rw-rw-   0        0        0     2472 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      294 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       15 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-05-16 07:31:38.000000 pybelt-1.1b1/pybelt.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-05-16 07:31:38.000000 pybelt-1.1b1/setup.cfg
--rw-rw-rw-   0        0        0      759 2023-05-16 07:31:01.000000 pybelt-1.1b1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:41:55.000000 pybelt-1.2.0/
+-rw-rw-rw-   0        0        0     2472 2023-06-28 14:41:55.000000 pybelt-1.2.0/PKG-INFO
+-rw-rw-rw-   0        0        0     1636 2021-01-11 09:49:47.000000 pybelt-1.2.0/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 14:41:55.000000 pybelt-1.2.0/pybelt/
+-rw-rw-rw-   0        0        0      112 2020-06-22 14:06:02.000000 pybelt-1.2.0/pybelt/__init__.py
+-rw-rw-rw-   0        0        0    37069 2023-05-16 07:04:42.000000 pybelt-1.2.0/pybelt/_communication_interface.py
+-rw-rw-rw-   0        0        0     8833 2023-01-05 13:18:44.000000 pybelt-1.2.0/pybelt/_gatt_profile.py
+-rw-rw-rw-   0        0        0    66878 2023-06-28 14:33:07.000000 pybelt-1.2.0/pybelt/belt_controller.py
+-rw-rw-rw-   0        0        0     3980 2023-05-15 13:07:23.000000 pybelt-1.2.0/pybelt/belt_scanner.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:41:55.000000 pybelt-1.2.0/pybelt.egg-info/
+-rw-rw-rw-   0        0        0     2472 2023-06-28 14:41:54.000000 pybelt-1.2.0/pybelt.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      294 2023-06-28 14:41:54.000000 pybelt-1.2.0/pybelt.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:41:54.000000 pybelt-1.2.0/pybelt.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       15 2023-06-28 14:41:54.000000 pybelt-1.2.0/pybelt.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 14:41:54.000000 pybelt-1.2.0/pybelt.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:41:55.000000 pybelt-1.2.0/setup.cfg
+-rw-rw-rw-   0        0        0      759 2023-06-28 14:41:37.000000 pybelt-1.2.0/setup.py
```

### Comparing `pybelt-1.1b1/PKG-INFO` & `pybelt-1.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pybelt
-Version: 1.1b1
+Version: 1.2.0
 Summary: An Python library to control the feelSpace naviBelt from your application
 Home-page: https://github.com/feelSpace/pybelt
 Author: feelSpace GmbH
 Author-email: dev@feelspace.de
 License: UNKNOWN
 Description: # pyBelt
```

### Comparing `pybelt-1.1b1/README.md` & `pybelt-1.2.0/README.md`

 * *Files identical despite different names*

### Comparing `pybelt-1.1b1/pybelt/_communication_interface.py` & `pybelt-1.2.0/pybelt/_communication_interface.py`

 * *Files identical despite different names*

### Comparing `pybelt-1.1b1/pybelt/_gatt_profile.py` & `pybelt-1.2.0/pybelt/_gatt_profile.py`

 * *Files identical despite different names*

### Comparing `pybelt-1.1b1/pybelt/belt_controller.py` & `pybelt-1.2.0/pybelt/belt_controller.py`

 * *Files 9% similar despite different names*

```diff
@@ -50,15 +50,15 @@
         # Cache of belt parameters
         self._belt_mode = None
         self._default_intensity = None
         self._firmware_version = None
         self._battery_status = None
         self._belt_orientation = None
         self._heading_offset = None
-        self._compass_accuracy_signal_enabled = None
+        self._inaccurate_signal_state = None
 
     def connect(self, belt):
         """ Connects a belt via Bluetooth LE or USB.
 
         :param Union[str, bleak.backends.device.BLEDevice] belt: The interface to use for communicating with the belt.
             For a Bluetooth LE connection a `BLEDevice` must be passed. For USB connection, the name of the serial port
             must passed, e.g. 'COM1' on Windows or '/dev/ttyUSB0' on Linux.
@@ -335,14 +335,19 @@
         """
         self._notifications_handlers.remove(handler)
 
     def set_orientation_notifications(self, enabled) -> bool:
         """
         Sets the state of orientation notifications.
 
+        IMPORTANT: It is important to note that orientation updates from the belt were not designed for updating a
+        system in real-time, just for monitoring and showing on a map the orientation of the belt. In case you need a
+        vibration signal on the belt that is dependent on the orientation, you can use the `vibrate_at_magnetic_bearing`
+        or `send_pulse_command` (with orientation_type=MAGNETIC_BEARING) to get a vibration relative to magnetic North.
+
         :param enabled: 'True' to enable orientation notifications, 'False' to disable.
         :return: 'True' if the request has been sent successfully.
         """
         if self._connection_state == BeltConnectionState.DISCONNECTED:
             return False
         return self._communication_interface.set_gatt_notifications(self._gatt_profile.orientation_data_char, enabled)
 
@@ -425,14 +430,64 @@
                     (0x01 if save else 0x00),
                     (0x01 if pairing_required else 0x00)]),
                 self._gatt_profile.param_notification_char)
         if write_result == 2:
             raise TimeoutError("Timeout period reached when setting pairing requirement.")
         return write_result == 0
 
+    def set_orientation_notification_period(self, period, start_notification) -> bool:
+        """
+        Sets the period for orientation notifications.
+
+        Changing the period of orientation notifications is only available from firmware version 52. The minimum
+        notification period supported by the belt is 20ms (i.e. 50Hz).
+
+        IMPORTANT: It is important to note that orientation updates from the belt were not designed for updating a
+        system in real-time, just for monitoring and showing on a map the orientation of the belt. In case you need a
+        vibration signal on the belt that is dependent on the orientation, you can use the `vibrate_at_magnetic_bearing`
+        or `send_pulse_command` (with orientation_type=MAGNETIC_BEARING) to get a vibration relative to magnetic North.
+
+        The belt orientation may be inaccurate when used indoor because of magnetic interference. To get a better
+        orientation, it is recommended to calibrate the belt in the room where it is used (or outdoor if used outdoor).
+
+        It is not recommended to use short notification period over BLE connection. For short notification
+        periods, after disconnection, it may be required to wait a few seconds to reconnect the belt again. If the
+        reconnection failed, it may be necessary to restart the belt. In case the belt does not respond anymore, you can
+        make a “hard power-off” by pressing the power button of the belt more than 6 seconds and then pressing it again
+        to restart the belt.
+
+        :param period: The period in seconds. Minimum value is 20 milliseconds (50Hz).
+        :param start_notification: 'True' to start the orientation notification.
+        :return: 'True' on success, 'False' otherwise.
+        """
+        if self.get_connection_state() != BeltConnectionState.CONNECTED:
+            self.logger.warning("BeltController: No belt belt connected to set notification period.")
+            return False
+        if self.get_firmware_version() < 52:
+            self.logger.warning("BeltController: Belt firmware version not supported.")
+            return False
+        if period < 0.02:
+            self.logger.warning("BeltController: Notification period not supported.")
+            return False
+        period_ms = int(period * 1000.0)
+        self.set_orientation_notifications(False)
+        if self.write_gatt(self._gatt_profile.param_request_char,
+                           bytes([
+                               0x11,
+                               0x0F,
+                               0x00,
+                               period_ms & 0xFF,
+                               (period_ms >> 8) & 0xFF,
+                           ]),
+                           self._gatt_profile.param_notification_char,
+                           b'\x10\x0F') != 0:
+            self.logger.warning("BeltController: Failed to write notification period parameter.")
+            return False
+        return self.set_orientation_notifications(True)
+
     def vibrate_at_magnetic_bearing(
             self,
             bearing,
             switch_to_app_mode=True,
             channel_index=1,
             intensity=None,
             clear_other_channels=False) -> bool:
@@ -576,15 +631,15 @@
                 (0x00 if pattern_iterations is None else pattern_iterations),
                 pattern_period & 0xFF,
                 (pattern_period >> 8) & 0xFF,
                 pattern_start_time & 0xFF,
                 (pattern_start_time >> 8) & 0xFF,
                 (0x01 if exclusive_channel else 0x00),
                 (0x01 if clear_other_channels else 0x00)
-                ])) == 0
+            ])) == 0
 
     def send_pulse_command(
             self,
             channel_index,
             orientation_type,
             orientation,
             intensity,
@@ -684,14 +739,78 @@
                 self._gatt_profile.vibration_command_char,
                 bytes([0x30, 0xFF])) == 0
         else:
             return self.write_gatt(
                 self._gatt_profile.vibration_command_char,
                 bytes([0x30, channel_index & 0xFF])) == 0
 
+    def get_inaccurate_orientation_signal_state(self) -> (bool, bool):
+        """ Returns the state (enabled/disabled) of the inaccurate orientation signal.
+
+        :return: A tuple indicating the state of the inaccurate signal. The first value is the state in application
+            mode, the second one is the state in compass mode. Returns `None` if the belt is not connected,
+        """
+        return self._inaccurate_signal_state
+
+    def set_inaccurate_orientation_signal_state(self, enable_in_app, save_on_belt, enable_in_compass=True,
+                                                wait_ack=False) -> bool:
+        """ Sets the state of the inaccurate orientation signal.
+
+        The inaccurate orientation signal is a vibration signal that indicates a possible inaccuracy in orientation
+        relative to magnetic North. The signal consists in three pulses on both sides of the belt. If your application
+        does not rely on the compass for the direction of vibrations, you can disable temporarily the inaccurate
+        orientation signal for the application mode. You can also disable and save this configuration on the belt if
+        you use a belt for an experiment.
+
+        IMPORTANT: If your application is meant for other users than you, you must explicitly inform the user before
+        disabling the inaccurate orientation signal. The inaccurate orientation signal is important for a safe usage
+        of the belt.
+
+        :param bool enable_in_app: `True` to enable the inaccurate signal in application mode, `False` to disable the
+            signal.
+        :param bool save_on_belt: `True` to save the inaccurate signal configuration on the belt. If `False` the
+            configuration will be reset on power cycle.
+        :param bool enable_in_compass:  `True` to enable the inaccurate signal in compass mode, `False` to disable the
+            signal.
+        :param bool wait_ack: `True` to wait for request acknowledgment.
+        :return: `True` if the request has been sent correctly, `False` if no belt is connected or a communication
+            problem occurs.
+        :raise TimeoutError: If acknowledgment is not received within the timeout period.
+        """
+        if self._connection_state != BeltConnectionState.CONNECTED:
+            self.logger.warning("BeltController: Cannot set inaccurate signal state when not connected.")
+            return False
+        signal_state = 0
+        if enable_in_compass:
+            signal_state = signal_state + 1
+        if enable_in_app:
+            signal_state = signal_state + 2
+        if wait_ack:
+            write_result = self.write_gatt(
+                self._gatt_profile.param_request_char,
+                bytes([
+                    0x11,
+                    0x03,
+                    (0x01 if save_on_belt else 0x00),
+                    signal_state]),
+                self._gatt_profile.param_notification_char,
+                b'\x10\x03')
+        else:
+            write_result = self.write_gatt(
+                self._gatt_profile.param_request_char,
+                bytes([
+                    0x11,
+                    0x03,
+                    (0x01 if save_on_belt else 0x00),
+                    signal_state]),
+                self._gatt_profile.param_notification_char)
+        if write_result == 2:
+            raise TimeoutError("Timeout period reached when setting inaccurate signal state.")
+        return write_result == 0
+
     # --------------------------------------------------------------- #
     # Private methods
 
     def _set_connection_state(self, state, error=None, notify=True):
         """Sets the connection state.
         :param int state: The state to be set.
         :param Exception error: The error to notify if any.
@@ -714,15 +833,15 @@
             self._communication_interface.close()
         self._belt_mode = None
         self._default_intensity = None
         self._firmware_version = None
         self._battery_status = None
         self._belt_orientation = None
         self._heading_offset = None
-        self._compass_accuracy_signal_enabled = None
+        self._inaccurate_signal_state = None
 
     def _handshake(self):
         """Handshake procedure.
 
         :return: 'True' if the handshake is successful, 'False' otherwise.
         """
         self.logger.info("BeltController: Start handshake.")
@@ -785,15 +904,15 @@
         self.logger.debug("BeltController: Read compass accuracy signal state.")
         if (self.write_gatt(self._gatt_profile.param_request_char,
                             b'\x10\x01\x03',
                             self._gatt_profile.param_notification_char,
                             b'\x10\x03') != 0):
             self.logger.error("BeltController: Failed to request compass accuracy signal state.")
             return False
-        if self._compass_accuracy_signal_enabled is None:
+        if self._inaccurate_signal_state is None:
             self.logger.error("BeltController: Failed to read compass accuracy signal state.")
             return False
 
         # Register to button press
         self.logger.debug("BeltController: Register to button press events.")
         if not self._communication_interface.set_gatt_notifications(self._gatt_profile.button_press_char, True):
             self.logger.error("BeltController: Failed to register to button press events.")
@@ -916,17 +1035,19 @@
         Sets the compass accuracy signal state member variable and notifies the delegate.
 
         :param int state: The signal state.
         """
         if (self._connection_state == BeltConnectionState.DISCONNECTED or
                 self._connection_state == BeltConnectionState.DISCONNECTING):
             return
-        self._compass_accuracy_signal_enabled = state != 0
+        enabled_in_compass = (state == 1) or (state == 3)
+        enabled_in_app = (state == 2) or (state == 3)
+        self._inaccurate_signal_state = (enabled_in_app, enabled_in_compass)
         try:
-            self._delegate.on_compass_accuracy_signal_state_notified(state != 0)
+            self._delegate.on_inaccurate_orientation_signal_state_notified(enabled_in_app, enabled_in_compass)
         except:
             pass
 
     def _notify_pairing_requirement(self, pairing_required):
         """
         Notifies the delegate of the pairing requirement state.
         :param pairing_required: 'True' if pairing is required.
@@ -1345,23 +1466,14 @@
         """Called when the BT name of the belt has been changed or notified.
 
         :param str bt_name:
             The BT name of the belt.
         """
         pass
 
-    def on_compass_accuracy_signal_state_notified(self, enabled):
-        """
-        Called when the state of the compass accuracy signal has been changed or notified.
-
-        :param bool enabled:
-            'True' if the signal is enabled, 'False' otherwise.
-        """
-        pass
-
     def on_pairing_requirement_notified(self, pairing_required):
         """ Called when the pairing requirement has been changed or notified.
 
         :param pairing_required: 'True' if the pairing is required.
         """
         pass
 
@@ -1377,14 +1489,24 @@
     def on_belt_battery_notified(self, charge_level, extra):
         """ Called when the battery level of the belt is notified.
         :param float charge_level: Charge level of the belt battery in percent.
         :param List extra: Extra information on the belt battery.
         """
         pass
 
+    def on_inaccurate_orientation_signal_state_notified(self, signal_enabled_in_app_mode,
+                                                        signal_enabled_in_compass_mode):
+        """ Called when the state of the inaccurate orientation signal has been notified.
+        :param bool signal_enabled_in_app_mode: `True` if inaccurate orientation signal is enabled in application mode,
+        `False` otherwise.
+        :param bool signal_enabled_in_compass_mode: `True` if inaccurate orientation signal is enabled in compass mode,
+        `False` otherwise.
+        """
+        pass
+
 
 class BeltConnectionError(Exception):
     """Exception raised for belt connection problems.
     """
 
     def __init__(self, message):
         """Constructor.
```

### Comparing `pybelt-1.1b1/pybelt/belt_scanner.py` & `pybelt-1.2.0/pybelt/belt_scanner.py`

 * *Files identical despite different names*

### Comparing `pybelt-1.1b1/pybelt.egg-info/PKG-INFO` & `pybelt-1.2.0/pybelt.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pybelt
-Version: 1.1b1
+Version: 1.2.0
 Summary: An Python library to control the feelSpace naviBelt from your application
 Home-page: https://github.com/feelSpace/pybelt
 Author: feelSpace GmbH
 Author-email: dev@feelspace.de
 License: UNKNOWN
 Description: # pyBelt
```

### Comparing `pybelt-1.1b1/setup.py` & `pybelt-1.2.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="pybelt",
-    version="1.1b1",
+    version="1.2.0",
     author="feelSpace GmbH",
     author_email="dev@feelspace.de",
     description="An Python library to control the feelSpace naviBelt from your application",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/feelSpace/pybelt",
     packages=setuptools.find_packages(),
```


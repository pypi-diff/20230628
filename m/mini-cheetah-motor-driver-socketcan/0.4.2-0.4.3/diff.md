# Comparing `tmp/mini-cheetah-motor-driver-socketcan-0.4.2.tar.gz` & `tmp/mini-cheetah-motor-driver-socketcan-0.4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mini-cheetah-motor-driver-socketcan-0.4.2.tar", last modified: Tue Jun 27 13:46:45 2023, max compression
+gzip compressed data, was "mini-cheetah-motor-driver-socketcan-0.4.3.tar", last modified: Wed Jun 28 12:02:24 2023, max compression
```

## Comparing `mini-cheetah-motor-driver-socketcan-0.4.2.tar` & `mini-cheetah-motor-driver-socketcan-0.4.3.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 13:46:45.840307 mini-cheetah-motor-driver-socketcan-0.4.2/
--rw-r--r--   0 runner    (1001) docker     (122)     1542 2023-06-27 13:46:37.000000 mini-cheetah-motor-driver-socketcan-0.4.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (122)     8169 2023-06-27 13:46:45.840307 mini-cheetah-motor-driver-socketcan-0.4.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     7355 2023-06-27 13:46:37.000000 mini-cheetah-motor-driver-socketcan-0.4.2/README.md
--rw-r--r--   0 runner    (1001) docker     (122)      104 2023-06-27 13:46:37.000000 mini-cheetah-motor-driver-socketcan-0.4.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (122)      944 2023-06-27 13:46:45.840307 mini-cheetah-motor-driver-socketcan-0.4.2/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 13:46:45.840307 mini-cheetah-motor-driver-socketcan-0.4.2/src/
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 13:46:45.840307 mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/
--rw-r--r--   0 runner    (1001) docker     (122)     8169 2023-06-27 13:46:45.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)      417 2023-06-27 13:46:45.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-27 13:46:45.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (122)       10 2023-06-27 13:46:45.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (122)       13 2023-06-27 13:46:45.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 13:46:45.840307 mini-cheetah-motor-driver-socketcan-0.4.2/src/motor_driver/
--rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-27 13:46:37.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/motor_driver/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)    21168 2023-06-27 13:46:37.000000 mini-cheetah-motor-driver-socketcan-0.4.2/src/motor_driver/canmotorlib.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 12:02:24.627040 mini-cheetah-motor-driver-socketcan-0.4.3/
+-rw-r--r--   0 runner    (1001) docker     (122)     1542 2023-06-28 12:02:16.000000 mini-cheetah-motor-driver-socketcan-0.4.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (122)     8065 2023-06-28 12:02:24.627040 mini-cheetah-motor-driver-socketcan-0.4.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     7251 2023-06-28 12:02:16.000000 mini-cheetah-motor-driver-socketcan-0.4.3/README.md
+-rw-r--r--   0 runner    (1001) docker     (122)      104 2023-06-28 12:02:16.000000 mini-cheetah-motor-driver-socketcan-0.4.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (122)      944 2023-06-28 12:02:24.627040 mini-cheetah-motor-driver-socketcan-0.4.3/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 12:02:24.623040 mini-cheetah-motor-driver-socketcan-0.4.3/src/
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 12:02:24.623040 mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)     8065 2023-06-28 12:02:24.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)      417 2023-06-28 12:02:24.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 12:02:24.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       10 2023-06-28 12:02:24.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       13 2023-06-28 12:02:24.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 12:02:24.627040 mini-cheetah-motor-driver-socketcan-0.4.3/src/motor_driver/
+-rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-28 12:02:16.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/motor_driver/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)    21607 2023-06-28 12:02:16.000000 mini-cheetah-motor-driver-socketcan-0.4.3/src/motor_driver/canmotorlib.py
```

### Comparing `mini-cheetah-motor-driver-socketcan-0.4.2/LICENSE` & `mini-cheetah-motor-driver-socketcan-0.4.3/LICENSE`

 * *Files identical despite different names*

### Comparing `mini-cheetah-motor-driver-socketcan-0.4.2/PKG-INFO` & `mini-cheetah-motor-driver-socketcan-0.4.3/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mini-cheetah-motor-driver-socketcan
-Version: 0.4.2
+Version: 0.4.3
 Summary: A Python Driver for MIT Mini-Cheetah Actuator which uses SocketCAN for communication.
 Home-page: https://github.com/dfki-ric-underactuated-lab/mini-cheetah-tmotor-python-can
 Author: Shubham Vyas
 Author-email: Shubham.Vyas@dfki.de
 Project-URL: Bug Tracker, https://github.com/dfki-ric-underactuated-lab/mini-cheetah-tmotor-python-can/issues
 Classifier: Development Status :: 4 - Beta
 Classifier: Programming Language :: Python :: 3.6
@@ -33,15 +33,15 @@
 
 Install via:
 
 `pip3 install bitstring`
 
 # Documentation
 
-- Useful videos: 
+- Useful videos:
     - [From T-Motor](https://www.youtube.com/watch?v=hbqQCgebaF8)
     - [From Skyentific](https://www.youtube.com/watch?v=HzY9vzgPZkA)
 - [Motor Datasheets](https://store.cubemars.com/images/file/20220307/1646619452473352.pdf)
 - [Ben Katz Documentation](https://docs.google.com/document/d/1dzNVzblz6mqB3eZVEMyi2MtSngALHdgpTaDJIW_BpS4/edit)
 
 # Pre-requisites:
 
@@ -191,10 +191,10 @@
 
 ```
 
 To add a new constants configuration use the `change_motor_constants` function or create an issue with the constants and motor information on the GitHub page to be added to the driver.
 
 # Known Issues
 
-**Issue Fixed**: When having 2 motors on the CAN bus with either PCAN CAN-USB or ESD CAN-USB/2, sometimes the motors experience an initial short *kick/impulse* at when they are enabled again after being disabled. This was fixed.
+Currently, the driver does not support multiple CAN busses i.e. multiple CAN2USB devices. The fix for this is in the works...
 
 As this is experimental software, there might be other unknown issues.
```

### Comparing `mini-cheetah-motor-driver-socketcan-0.4.2/README.md` & `mini-cheetah-motor-driver-socketcan-0.4.3/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 
 Install via:
 
 `pip3 install bitstring`
 
 # Documentation
 
-- Useful videos: 
+- Useful videos:
     - [From T-Motor](https://www.youtube.com/watch?v=hbqQCgebaF8)
     - [From Skyentific](https://www.youtube.com/watch?v=HzY9vzgPZkA)
 - [Motor Datasheets](https://store.cubemars.com/images/file/20220307/1646619452473352.pdf)
 - [Ben Katz Documentation](https://docs.google.com/document/d/1dzNVzblz6mqB3eZVEMyi2MtSngALHdgpTaDJIW_BpS4/edit)
 
 # Pre-requisites:
 
@@ -173,10 +173,10 @@
 
 ```
 
 To add a new constants configuration use the `change_motor_constants` function or create an issue with the constants and motor information on the GitHub page to be added to the driver.
 
 # Known Issues
 
-**Issue Fixed**: When having 2 motors on the CAN bus with either PCAN CAN-USB or ESD CAN-USB/2, sometimes the motors experience an initial short *kick/impulse* at when they are enabled again after being disabled. This was fixed.
+Currently, the driver does not support multiple CAN busses i.e. multiple CAN2USB devices. The fix for this is in the works...
 
 As this is experimental software, there might be other unknown issues.
```

### Comparing `mini-cheetah-motor-driver-socketcan-0.4.2/setup.cfg` & `mini-cheetah-motor-driver-socketcan-0.4.3/setup.cfg`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = mini-cheetah-motor-driver-socketcan
-version = 0.4.2
+version = 0.4.3
 author = Shubham Vyas
 author_email = Shubham.Vyas@dfki.de
 description = A Python Driver for MIT Mini-Cheetah Actuator which uses SocketCAN for communication.
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/dfki-ric-underactuated-lab/mini-cheetah-tmotor-python-can
 project_urls =
```

### Comparing `mini-cheetah-motor-driver-socketcan-0.4.2/src/mini_cheetah_motor_driver_socketcan.egg-info/PKG-INFO` & `mini-cheetah-motor-driver-socketcan-0.4.3/src/mini_cheetah_motor_driver_socketcan.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mini-cheetah-motor-driver-socketcan
-Version: 0.4.2
+Version: 0.4.3
 Summary: A Python Driver for MIT Mini-Cheetah Actuator which uses SocketCAN for communication.
 Home-page: https://github.com/dfki-ric-underactuated-lab/mini-cheetah-tmotor-python-can
 Author: Shubham Vyas
 Author-email: Shubham.Vyas@dfki.de
 Project-URL: Bug Tracker, https://github.com/dfki-ric-underactuated-lab/mini-cheetah-tmotor-python-can/issues
 Classifier: Development Status :: 4 - Beta
 Classifier: Programming Language :: Python :: 3.6
@@ -33,15 +33,15 @@
 
 Install via:
 
 `pip3 install bitstring`
 
 # Documentation
 
-- Useful videos: 
+- Useful videos:
     - [From T-Motor](https://www.youtube.com/watch?v=hbqQCgebaF8)
     - [From Skyentific](https://www.youtube.com/watch?v=HzY9vzgPZkA)
 - [Motor Datasheets](https://store.cubemars.com/images/file/20220307/1646619452473352.pdf)
 - [Ben Katz Documentation](https://docs.google.com/document/d/1dzNVzblz6mqB3eZVEMyi2MtSngALHdgpTaDJIW_BpS4/edit)
 
 # Pre-requisites:
 
@@ -191,10 +191,10 @@
 
 ```
 
 To add a new constants configuration use the `change_motor_constants` function or create an issue with the constants and motor information on the GitHub page to be added to the driver.
 
 # Known Issues
 
-**Issue Fixed**: When having 2 motors on the CAN bus with either PCAN CAN-USB or ESD CAN-USB/2, sometimes the motors experience an initial short *kick/impulse* at when they are enabled again after being disabled. This was fixed.
+Currently, the driver does not support multiple CAN busses i.e. multiple CAN2USB devices. The fix for this is in the works...
 
 As this is experimental software, there might be other unknown issues.
```

### Comparing `mini-cheetah-motor-driver-socketcan-0.4.2/src/motor_driver/canmotorlib.py` & `mini-cheetah-motor-driver-socketcan-0.4.3/src/motor_driver/canmotorlib.py`

 * *Files 6% similar despite different names*

```diff
@@ -175,14 +175,16 @@
 
 
 class CanMotorController:
     """
     Class for creating a Mini-Cheetah Motor Controller over CAN. Uses SocketCAN driver for
     communication.
     """
+    can_socket_declared = False
+    motor_socket = None
 
     def __init__(self, can_socket="can0", motor_id=0x01, motor_type="AK80_6_V1p1", socket_timeout=0.05):
         """
         Instantiate the class with socket name, motor ID, and socket timeout.
         Sets up the socket communication for rest of the functions.
         """
         self.motorParams = AK80_6_V1p1_PARAMS  # default choice
@@ -206,24 +208,28 @@
             recvBytes = 16
             can_frame_fmt_recv = "=IB3x8s"
         elif motor_type == "AK70_10_V1p1":
             self.motorParams = AK70_10_V1p1_params
 
         can_socket = (can_socket,)
         self.motor_id = motor_id
-        # create a raw socket and bind it to the given CAN interface
-        try:
-            self.motor_socket = socket.socket(socket.AF_CAN, socket.SOCK_RAW, socket.CAN_RAW)
-            self.motor_socket.setsockopt(socket.SOL_CAN_RAW, socket.CAN_RAW_LOOPBACK, 0)
-            self.motor_socket.bind(can_socket)
-            self.motor_socket.settimeout(socket_timeout)
-            print("Bound to: ", can_socket)
-        except Exception as e:
-            print("Unable to Connect to Socket Specified: ", can_socket)
-            print("Error:", e)
+        if not CanMotorController.can_socket_declared:
+            # create a raw socket and bind it to the given CAN interface
+            try:
+                CanMotorController.motor_socket = socket.socket(socket.AF_CAN, socket.SOCK_RAW, socket.CAN_RAW)
+                CanMotorController.motor_socket.setsockopt(socket.SOL_CAN_RAW, socket.CAN_RAW_LOOPBACK, 0)
+                CanMotorController.motor_socket.bind(can_socket)
+                CanMotorController.motor_socket.settimeout(socket_timeout)
+                print("Bound to: ", can_socket)
+                CanMotorController.can_socket_declared = True
+            except Exception as e:
+                print("Unable to Connect to Socket Specified: ", can_socket)
+                print("Error:", e)
+        elif CanMotorController.can_socket_declared:
+            print("Socket already available. Using:  ", CanMotorController.motor_socket)
 
         # Initialize the command BitArrays for performance optimization
         self._p_des_BitArray = BitArray(
             uint=float_to_uint(0, self.motorParams["P_MIN"], self.motorParams["P_MAX"], 16), length=16
         )
         self._v_des_BitArray = BitArray(
             uint=float_to_uint(0, self.motorParams["V_MIN"], self.motorParams["V_MAX"], 12), length=12
@@ -237,26 +243,26 @@
     def _send_can_frame(self, data):
         """
         Send raw CAN data frame (in bytes) to the motor.
         """
         can_dlc = len(data)
         can_msg = struct.pack(can_frame_fmt_send, self.motor_id, can_dlc, data)
         try:
-            self.motor_socket.send(can_msg)
+            CanMotorController.motor_socket.send(can_msg)
         except Exception as e:
             print("Unable to Send CAN Frame.")
             print("Error: ", e)
 
     def _recv_can_frame(self):
         """
         Receive a CAN frame and unpack it. Returns can_id, can_dlc (data length), data (in bytes)
         """
         try:
             # The motor sends back only 6 bytes.
-            frame, addr = self.motor_socket.recvfrom(recvBytes)
+            frame, addr = CanMotorController.motor_socket.recvfrom(recvBytes)
             can_id, can_dlc, data = struct.unpack(can_frame_fmt_recv, frame)
             return can_id, can_dlc, data[:can_dlc]
         except Exception as e:
             print("Unable to Receive CAN Frame.")
             print("Error: ", e)
 
     def enable_motor(self):
```


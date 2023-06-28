# Comparing `tmp/ixcom-1.3.6.tar.gz` & `tmp/ixcom-1.3.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ixcom-1.3.6.tar", last modified: Wed May 31 12:13:42 2023, max compression
+gzip compressed data, was "ixcom-1.3.7.tar", last modified: Wed Jun 28 10:04:12 2023, max compression
```

## Comparing `ixcom-1.3.6.tar` & `ixcom-1.3.7.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-05-31 12:13:42.598461 ixcom-1.3.6/
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1069 2023-05-31 12:10:58.000000 ixcom-1.3.6/LICENSE
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)       22 2023-05-31 12:10:58.000000 ixcom-1.3.6/MANIFEST.in
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1272 2023-05-31 12:13:42.598461 ixcom-1.3.6/PKG-INFO
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      584 2023-05-31 12:10:58.000000 ixcom-1.3.6/README.md
-drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-05-31 12:13:42.598461 ixcom-1.3.6/ixcom/
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      105 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/__init__.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    10380 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/cmdline.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1462 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/commands.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     2780 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/crc16.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      304 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/data.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      401 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/exceptions.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     8142 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/grep.py
-drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-05-31 12:13:42.594461 ixcom-1.3.6/ixcom/json-files/
-drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-05-31 12:13:42.598461 ixcom-1.3.6/ixcom/json-files/messages/
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     2982 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/json-files/messages/0x03_inssol.json
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     4828 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/json-files/messages/0x9A_ekfstddev3.json
-drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-05-31 12:13:42.598461 ixcom-1.3.6/ixcom/json-files/parameters/
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     4978 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/json-files/parameters/0731_parekf_startupv2.json
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     8082 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/json-files/parameters/0760_parekf_imuconfig2.json
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    37317 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/messages.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    37288 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/parameters.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    71385 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/parser.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      273 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/plugin_messages.py
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    42598 2023-05-31 12:10:58.000000 ixcom-1.3.6/ixcom/protocol.py
-drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-05-31 12:13:42.598461 ixcom-1.3.6/ixcom.egg-info/
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1272 2023-05-31 12:13:42.000000 ixcom-1.3.6/ixcom.egg-info/PKG-INFO
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      628 2023-05-31 12:13:42.000000 ixcom-1.3.6/ixcom.egg-info/SOURCES.txt
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        1 2023-05-31 12:13:42.000000 ixcom-1.3.6/ixcom.egg-info/dependency_links.txt
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      250 2023-05-31 12:13:42.000000 ixcom-1.3.6/ixcom.egg-info/entry_points.txt
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)       33 2023-05-31 12:13:42.000000 ixcom-1.3.6/ixcom.egg-info/requires.txt
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        6 2023-05-31 12:13:42.000000 ixcom-1.3.6/ixcom.egg-info/top_level.txt
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)       38 2023-05-31 12:13:42.598461 ixcom-1.3.6/setup.cfg
--rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     2098 2023-05-31 12:10:58.000000 ixcom-1.3.6/setup.py
+drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-06-28 10:04:12.844170 ixcom-1.3.7/
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1069 2023-06-28 10:02:42.000000 ixcom-1.3.7/LICENSE
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)       22 2023-06-28 10:02:42.000000 ixcom-1.3.7/MANIFEST.in
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1272 2023-06-28 10:04:12.844170 ixcom-1.3.7/PKG-INFO
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      584 2023-06-28 10:02:42.000000 ixcom-1.3.7/README.md
+drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-06-28 10:04:12.844170 ixcom-1.3.7/ixcom/
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      105 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/__init__.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    10380 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/cmdline.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1462 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/commands.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     2780 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/crc16.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      304 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/data.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      401 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/exceptions.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     8142 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/grep.py
+drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-06-28 10:04:12.844170 ixcom-1.3.7/ixcom/json-files/
+drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-06-28 10:04:12.844170 ixcom-1.3.7/ixcom/json-files/messages/
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     2982 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/json-files/messages/0x03_inssol.json
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     4828 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/json-files/messages/0x9A_ekfstddev3.json
+drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-06-28 10:04:12.844170 ixcom-1.3.7/ixcom/json-files/parameters/
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     4978 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/json-files/parameters/0731_parekf_startupv2.json
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     8082 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/json-files/parameters/0760_parekf_imuconfig2.json
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    37317 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/messages.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    37288 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/parameters.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    72653 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/parser.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      273 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/plugin_messages.py
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)    43112 2023-06-28 10:02:42.000000 ixcom-1.3.7/ixcom/protocol.py
+drwxrwxr-x   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        0 2023-06-28 10:04:12.844170 ixcom-1.3.7/ixcom.egg-info/
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     1272 2023-06-28 10:04:12.000000 ixcom-1.3.7/ixcom.egg-info/PKG-INFO
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      628 2023-06-28 10:04:12.000000 ixcom-1.3.7/ixcom.egg-info/SOURCES.txt
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        1 2023-06-28 10:04:12.000000 ixcom-1.3.7/ixcom.egg-info/dependency_links.txt
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)      250 2023-06-28 10:04:12.000000 ixcom-1.3.7/ixcom.egg-info/entry_points.txt
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)       33 2023-06-28 10:04:12.000000 ixcom-1.3.7/ixcom.egg-info/requires.txt
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)        6 2023-06-28 10:04:12.000000 ixcom-1.3.7/ixcom.egg-info/top_level.txt
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)       38 2023-06-28 10:04:12.844170 ixcom-1.3.7/setup.cfg
+-rw-rw-r--   0 maximilianrehermann  (1001) maximilianrehermann  (1001)     2098 2023-06-28 10:02:42.000000 ixcom-1.3.7/setup.py
```

### Comparing `ixcom-1.3.6/LICENSE` & `ixcom-1.3.7/LICENSE`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/PKG-INFO` & `ixcom-1.3.7/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ixcom
-Version: 1.3.6
+Version: 1.3.7
 Summary: Library for communicating with xcom devices over network
 Home-page: http://www.imar-navigation.de
 Author: iMAR Navigation GmbH
 Author-email: support@imar-navigation.de
 License: UNKNOWN
 Project-URL: Documentation, https://ixcom.readthedocs.io/en/latest/
 Project-URL: Source Code, https://github.com/imar-navigation/ixcom-python
```

### Comparing `ixcom-1.3.6/README.md` & `ixcom-1.3.7/README.md`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/cmdline.py` & `ixcom-1.3.7/ixcom/cmdline.py`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/commands.py` & `ixcom-1.3.7/ixcom/commands.py`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/crc16.py` & `ixcom-1.3.7/ixcom/crc16.py`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/grep.py` & `ixcom-1.3.7/ixcom/grep.py`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/json-files/messages/0x03_inssol.json` & `ixcom-1.3.7/ixcom/json-files/messages/0x03_inssol.json`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/json-files/messages/0x9A_ekfstddev3.json` & `ixcom-1.3.7/ixcom/json-files/messages/0x9A_ekfstddev3.json`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/json-files/parameters/0731_parekf_startupv2.json` & `ixcom-1.3.7/ixcom/json-files/parameters/0731_parekf_startupv2.json`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/json-files/parameters/0760_parekf_imuconfig2.json` & `ixcom-1.3.7/ixcom/json-files/parameters/0760_parekf_imuconfig2.json`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/messages.py` & `ixcom-1.3.7/ixcom/messages.py`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/parameters.py` & `ixcom-1.3.7/ixcom/parameters.py`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/ixcom/parser.py` & `ixcom-1.3.7/ixcom/parser.py`

 * *Files 1% similar despite different names*

```diff
@@ -964,14 +964,43 @@
             ClientTimeoutError: Timeout while waiting for response or log from the XCOM server
             ResponseError: The response from the system was not 'OK'.
         '''
         msgToSend = data.getParameterWithID(data.PARDAT_SYSSTAT_Payload.parameter_id)
         msgToSend.payload.data['statMode'] = 127
         msgToSend.payload.data['action'] = data.ParameterAction.CHANGING
         self.send_msg_and_waitfor_okay(msgToSend)
+    
+    def set_ins_vel_output_frame(self, vel_output_mode: int = protocol.ParDatVelMode.NED):
+        '''Defines the velocity output frame of the INSSOL message
+            0: NED
+            1: ENU
+            2: ECEF
+            3: BODY
+
+        Raises:
+            ClientTimeoutError: Timeout while waiting for response or log from the XCOM server
+            ResponseError: The response from the system was not 'OK'.
+        '''
+        msgToSend = data.getParameterWithID(data.PARDAT_VEL_Payload.parameter_id)
+        msgToSend.payload.data['velMode'] = vel_output_mode
+        msgToSend.payload.data['action'] = data.ParameterAction.CHANGING
+        self.send_msg_and_waitfor_okay(msgToSend)
+
+    def get_ins_vel_output_frame(self):
+        '''Convenience getter for velocity output frame of the INSSOL message
+
+        Raises:
+            ClientTimeoutError: Timeout while waiting for response or parameter from the XCOM server
+            ResponseError: The response from the system was not 'OK'.
+
+        '''
+        msgToSend = data.getParameterWithID(data.PARDAT_VEL_Payload.parameter_id)
+        msgToSend.payload.data['action'] = data.ParameterAction.REQUESTING
+        self.send_msg_and_waitfor_okay(msgToSend)
+        return self.wait_for_parameter()
 
     def get_device_info(self):
         '''Get information about the connected device
 
         Returns:
             A dictionary containing information about the device, e.g. part number, serial number, etc.
```

### Comparing `ixcom-1.3.6/ixcom/protocol.py` & `ixcom-1.3.7/ixcom/protocol.py`

 * *Files 2% similar despite different names*

```diff
@@ -75,14 +75,26 @@
     ALTITUDE_BARO = 0b0000000100000000
     '''Altitude is baro altitude'''
     WGS84POS= 0b0000001000000000
     '''Position is longitude, latitude, altitude'''
     ECEFPOS = 0b0000010000000000
     '''Position is ECEF X,Y,Z'''
 
+class ParDatVelMode(IntEnum):
+    '''Enumeration for the velocity output frame of the INSSOL message'''
+
+    NED = 0
+    '''The velocity fields of the INSSOL message contain the velocity in NED frame.'''
+    ENU = 1
+    '''The velocity fields of the INSSOL message contain the velocity in ENU frame.'''
+    ECEF = 2
+    '''The velocity fields of the INSSOL message contain the velocity in ECEF frame.'''
+    BODY = 3
+    '''The velocity fields of the INSSOL message contain the velocity in vehicle body frame.'''
+
 class MessageID(IntEnum):
     '''Enumeration for special message IDs'''
     PLUGIN        = 0x64
     COMMAND       = 0xFD
     RESPONSE      = 0xFE
     PARAMETER     = 0xFF
```

### Comparing `ixcom-1.3.6/ixcom.egg-info/PKG-INFO` & `ixcom-1.3.7/ixcom.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ixcom
-Version: 1.3.6
+Version: 1.3.7
 Summary: Library for communicating with xcom devices over network
 Home-page: http://www.imar-navigation.de
 Author: iMAR Navigation GmbH
 Author-email: support@imar-navigation.de
 License: UNKNOWN
 Project-URL: Documentation, https://ixcom.readthedocs.io/en/latest/
 Project-URL: Source Code, https://github.com/imar-navigation/ixcom-python
```

### Comparing `ixcom-1.3.6/ixcom.egg-info/SOURCES.txt` & `ixcom-1.3.7/ixcom.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `ixcom-1.3.6/setup.py` & `ixcom-1.3.7/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 
 if __name__ == '__main__':
 
     readmePath = os.path.join(os.path.dirname(__file__), 'README.md')
     long_description = open(readmePath, "rt").read()
 
     setup(name='ixcom',
-          version='1.3.6',
+          version='1.3.7',
           description='Library for communicating with xcom devices over network',
           author='iMAR Navigation GmbH',
           author_email='support@imar-navigation.de',
           url='http://www.imar-navigation.de',
           keywords=['XCOM', 'Inertial navigation', 'INS', 'iMAR', 'iNAT', 'GNSS', 'GPS', 'AHRS'],
           packages=['ixcom'],
           package_data={'': ['ixcom/messages/*.json', 'ixcom/parameters/*.json']},
```


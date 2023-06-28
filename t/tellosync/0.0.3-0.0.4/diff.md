# Comparing `tmp/tellosync-0.0.3.tar.gz` & `tmp/tellosync-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tellosync-0.0.3.tar", last modified: Fri Jun 23 16:26:33 2023, max compression
+gzip compressed data, was "tellosync-0.0.4.tar", last modified: Wed Jun 28 02:59:13 2023, max compression
```

## Comparing `tellosync-0.0.3.tar` & `tellosync-0.0.4.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxrwxrwx   0        0        0        0 2023-06-23 16:26:33.073251 tellosync-0.0.3/
--rw-rw-rw-   0        0        0     1070 2023-06-22 13:01:38.000000 tellosync-0.0.3/LICENSE
--rw-rw-rw-   0        0        0     2132 2023-06-23 16:26:33.064229 tellosync-0.0.3/PKG-INFO
--rw-rw-rw-   0        0        0     1557 2023-06-22 13:01:38.000000 tellosync-0.0.3/README.md
--rw-rw-rw-   0        0        0       42 2023-06-23 16:26:33.073251 tellosync-0.0.3/setup.cfg
--rw-rw-rw-   0        0        0      755 2023-06-23 16:26:18.000000 tellosync-0.0.3/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-23 16:26:33.016042 tellosync-0.0.3/tellosync/
--rw-rw-rw-   0        0        0      223 2023-06-22 13:01:38.000000 tellosync-0.0.3/tellosync/__init__.py
--rw-rw-rw-   0        0        0     2276 2023-06-22 13:01:38.000000 tellosync-0.0.3/tellosync/stats.py
--rw-rw-rw-   0        0        0      503 2023-06-23 16:15:24.000000 tellosync-0.0.3/tellosync/synchro.py
--rw-rw-rw-   0        0        0     7136 2023-06-23 13:10:30.000000 tellosync-0.0.3/tellosync/tello.py
-drwxrwxrwx   0        0        0        0 2023-06-23 16:26:33.064229 tellosync-0.0.3/tellosync.egg-info/
--rw-rw-rw-   0        0        0     2132 2023-06-23 16:26:32.000000 tellosync-0.0.3/tellosync.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      271 2023-06-23 16:26:32.000000 tellosync-0.0.3/tellosync.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-23 16:26:32.000000 tellosync-0.0.3/tellosync.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       23 2023-06-23 16:26:32.000000 tellosync-0.0.3/tellosync.egg-info/requires.txt
--rw-rw-rw-   0        0        0       10 2023-06-23 16:26:32.000000 tellosync-0.0.3/tellosync.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 02:59:13.274714 tellosync-0.0.4/
+-rw-rw-rw-   0        0        0     1070 2023-06-22 13:01:38.000000 tellosync-0.0.4/LICENSE
+-rw-rw-rw-   0        0        0     2132 2023-06-28 02:59:13.273709 tellosync-0.0.4/PKG-INFO
+-rw-rw-rw-   0        0        0     1557 2023-06-22 13:01:38.000000 tellosync-0.0.4/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:59:13.275709 tellosync-0.0.4/setup.cfg
+-rw-rw-rw-   0        0        0      755 2023-06-28 02:40:07.000000 tellosync-0.0.4/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:59:13.255194 tellosync-0.0.4/tellosync/
+-rw-rw-rw-   0        0        0      223 2023-06-22 13:01:38.000000 tellosync-0.0.4/tellosync/__init__.py
+-rw-rw-rw-   0        0        0     2227 2023-06-27 11:55:49.000000 tellosync-0.0.4/tellosync/stats.py
+-rw-rw-rw-   0        0        0     1023 2023-06-28 02:35:45.000000 tellosync-0.0.4/tellosync/synchro.py
+-rw-rw-rw-   0        0        0     8657 2023-06-28 02:57:06.000000 tellosync-0.0.4/tellosync/tello.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:59:13.271711 tellosync-0.0.4/tellosync.egg-info/
+-rw-rw-rw-   0        0        0     2132 2023-06-28 02:59:13.000000 tellosync-0.0.4/tellosync.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      271 2023-06-28 02:59:13.000000 tellosync-0.0.4/tellosync.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:59:13.000000 tellosync-0.0.4/tellosync.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       23 2023-06-28 02:59:13.000000 tellosync-0.0.4/tellosync.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       10 2023-06-28 02:59:13.000000 tellosync-0.0.4/tellosync.egg-info/top_level.txt
```

### Comparing `tellosync-0.0.3/LICENSE` & `tellosync-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `tellosync-0.0.3/PKG-INFO` & `tellosync-0.0.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tellosync
-Version: 0.0.3
+Version: 0.0.4
 Summary: An easy framework to support DJI Tello scripting in Python 3
 Home-page: https://github.com/vwu1888/easyTello
 Author: Ezra Fielding, Vincent Wu
 Author-email: ezra.fielding@gmail.com, vwu1888@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
```

### Comparing `tellosync-0.0.3/README.md` & `tellosync-0.0.4/README.md`

 * *Files identical despite different names*

### Comparing `tellosync-0.0.3/setup.py` & `tellosync-0.0.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open('README.md', 'r') as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name='tellosync',
-    version='0.0.3',
+    version='0.0.4',
     author='Ezra Fielding, Vincent Wu',
     author_email='ezra.fielding@gmail.com, vwu1888@gmail.com',
     description='An easy framework to support DJI Tello scripting in Python 3',
     long_description=long_description,
     long_description_content_type='text/markdown',
     url='https://github.com/vwu1888/easyTello',
     packages=setuptools.find_packages(),
```

### Comparing `tellosync-0.0.3/tellosync/stats.py` & `tellosync-0.0.4/tellosync/stats.py`

 * *Files 4% similar despite different names*

```diff
@@ -7,24 +7,21 @@
         self.id = id
 
         self.start_time = datetime.now()
         self.end_time = None
         self.duration = None
 
     def add_response(self, response: str):
-        self.response = str(response)
+        self.response = response.rstrip("\r\n")
         # Calculating total time taken to execute command
         self.end_time = datetime.now()
         self.duration = (self.end_time-self.start_time).total_seconds()
 
     def got_response(self):
-        if self.response is None:
-            return False
-        else:
-            return True
+        return self.response is not None
 
     def get_raw_response(self):
         return self.response
 
     def numeric_response(self, data: str):
         num_val = ''.join(i for i in data if i.isdigit() or i=='-' or i=='.')
         return num_val
```

### Comparing `tellosync-0.0.3/tellosync/tello.py` & `tellosync-0.0.4/tellosync/tello.py`

 * *Files 14% similar despite different names*

```diff
@@ -2,179 +2,229 @@
 import threading
 import time
 import cv2
 from tellosync.stats import Stats
 from tellosync.synchro import Synchro
 
 class Tello:
-    def __init__(self, tello_ip: str='192.168.10.1', debug: bool=True, sync: Synchro=None):
+    def __init__(self, tello_ip: str='192.168.10.1', debug: bool=True, isSynced: bool=False, port: int=0):
         # Opening local UDP port on 8889 for Tello communication
         self.local_ip = ''
         self.local_port = 8889
         self.socket = socket.socket(socket.AF_INET, socket.SOCK_DGRAM)
         self.socket.setsockopt(socket.SOL_SOCKET, socket.SO_REUSEADDR, 1)
         self.socket.bind((self.local_ip, self.local_port))
         
         # Setting Tello ip and port info
         self.tello_ip = tello_ip
         self.tello_port = 8889
         self.tello_address = (self.tello_ip, self.tello_port)
-        self.log = []
+        self.log: list[Stats] = []
 
         # Intializing response thread
         self.receive_thread = threading.Thread(target=self._receive_thread)
         self.receive_thread.daemon = True
         self.receive_thread.start()
 
         # easyTello runtime options
         self.stream_state = False
         self.last_frame = None
         self.MAX_TIME_OUT = 15.0
         self.debug = debug
 
-        self.sync = sync
+        self.isSynced = isSynced 
+        if isSynced:
+            self.synchro = Synchro(port)
+            self.isSynced = self.synchro.open()
 
         # Setting Tello to command mode
         self.command()
 
-    def send_command(self, command: str, query: bool =False):
+    def send_command(self, command: str, delay: float=0.0, query: bool=False, tries: int=0):
         # New log entry created for the outbound command
         self.log.append(Stats(command, len(self.log)))
+        currentStats = self.log[-1]
+
+        if delay > 0:
+            self.wait(delay)
 
         # Sending command to Tello
         self.socket.sendto(command.encode('utf-8'), self.tello_address)
         # Displaying conformation message (if 'debug' os True)
         if self.debug is True:
-            print('Sending command: {}'.format(command))
-            
+            print(f'Sending command: {command}')
+
         # Checking whether the command has timed out or not (based on value in 'MAX_TIME_OUT')
         start = time.time()
-        while not self.log[-1].got_response():  # Runs while no repsonse has been received in log      
+        while not currentStats.got_response():  # Runs while no repsonse has been received in log      
             now = time.time()
             difference = now - start
             if difference > self.MAX_TIME_OUT:
-                print('Connection timed out!')
+                currentStats.add_response('Connection timed out!')
                 break
 
         # Prints out Tello response (if 'debug' is True)
-        if self.debug is True and query is False:
-            print('Response: {}'.format(self.log[-1].get_response()))
+        if self.debug is True and not query:
+            print(f'Response: {currentStats.get_response()}')
 
-        # Syncs commands with other drones when using a synchronizer
-        if self.sync is not None: 
-            self.sync.selfIsReady()
-            while not self.sync.isSynced():
-                pass
+        # sourcery skip: merge-nested-ifs
+        if tries < 3 and currentStats.got_response():
+            if currentStats.get_raw_response() == "error No valid imu" or currentStats.get_raw_response == "error Not joystick":
+                self.send_command(command, tries=tries+1)
+
+        if delay < 0:
+            self.wait(abs(delay))
+
+        self.wait_for_sync()
+
+    def _keep_alive(self):
+        # Sending command to Tello
+        print("Keeping connection alive")
+        self.socket.sendto("stop".encode('utf-8'), self.tello_address)
 
     def _receive_thread(self):
         while True:
             # Checking for Tello response, throws socket error
             try:
                 self.response, ip = self.socket.recvfrom(1024)
-                self.log[-1].add_response(self.response)
+                self.log[-1].add_response(self.response.decode('utf-8'))
             except socket.error as exc:
-                print('Socket error: {}'.format(exc))
+                print(f'Socket error: {exc}')
 
     def _video_thread(self):
         # Creating stream capture object
-        cap = cv2.VideoCapture('udp://'+self.tello_ip+':11111')
+        cap = cv2.VideoCapture(f'udp://{self.tello_ip}:11111')
         # Runs while 'stream_state' is True
         while self.stream_state:
             ret, self.last_frame = cap.read()
             cv2.imshow('DJI Tello', self.last_frame)
 
             # Video Stream is closed if escape key is pressed
             k = cv2.waitKey(1) & 0xFF
             if k == 27:
                 break
         cap.release()
         cv2.destroyAllWindows()
     
     def wait(self, delay: float):
+        if self.isSynced:
+            self.synchro.unsync()
         # Displaying wait message (if 'debug' is True)
-        if self.debug is True:
-            print('Waiting {} seconds...'.format(delay))
+        if self.debug:
+            print(f'Waiting {delay} seconds...')
         # Log entry for delay added
         self.log.append(Stats('wait', len(self.log)))
-        # Delay is activated
-        time.sleep(delay)
-    
+
+        delay = abs(delay)
+        while delay > 0.0:
+            self._keep_alive()
+            delay = delay - 8.0 
+            if (delay < 0.0):
+                time.sleep(delay + 8.0)
+                continue
+            # Delay is activated
+            time.sleep(8.0)
+        # self._keep_alive()
+        # delay = delay - 8.0 
+        # if (delay < 0.0):
+        #     time.sleep(delay)
+        # # Delay is activated
+        # time.sleep(8.0)
+        if self.isSynced:
+            self.wait_for_sync()
+
+    def wait_for_sync(self):
+        # Syncs commands with other drones when using a synchronizer
+        if self.isSynced:
+            self.synchro.selfIsReady()
+            while not self.synchro.waitSync():
+                print("Waiting for other drones...")
+                self._keep_alive()
+        
     def get_log(self):
         return self.log
     
     def close(self):
         self.socket.close()
 
     # Controll Commands
     def command(self):
+        if self.isSynced:
+            self.synchro.start()
         self.send_command('command')
     
     def takeoff(self):
         self.send_command('takeoff')
 
     def land(self):
+        if self.isSynced:
+            self.synchro.finished()
         self.send_command('land')
+        self.synchro.close()
 
     def streamon(self):
         self.send_command('streamon')
         self.stream_state = True
         self.video_thread = threading.Thread(target=self._video_thread)
         self.video_thread.daemon = True
         self.video_thread.start()
 
     def streamoff(self):
         self.stream_state = False
         self.send_command('streamoff')
 
     def emergency(self):
         self.send_command('emergency')
+
+    def stop(self):
+        self.send_command('stop')
     
     # Movement Commands
     def up(self, dist: int):
-        self.send_command('up {}'.format(dist))
+        self.send_command(f'up {dist}')
 
     def down(self, dist: int):
-        self.send_command('down {}'.format(dist))
+        self.send_command(f'down {dist}')
 
     def left(self, dist: int):
-        self.send_command('left {}'.format(dist))
+        self.send_command(f'left {dist}')
 
     def right(self, dist: int):
-        self.send_command('right {}'.format(dist))
+        self.send_command(f'right {dist}')
         
     def forward(self, dist: int):
-        self.send_command('forward {}'.format(dist))
+        self.send_command(f'forward {dist}')
 
     def back(self, dist: int):
-        self.send_command('back {}'.format(dist))
+        self.send_command(f'back {dist}')
 
     def cw(self, degr: int):
-        self.send_command('cw {}'.format(degr))
+        self.send_command(f'cw {degr}')
     
     def ccw(self, degr: int):
-        self.send_command('ccw {}'.format(degr))
+        self.send_command(f'ccw {degr}')
 
     def flip(self, direc: str):
-        self.send_command('flip {}'.format(direc))
+        self.send_command(f'flip {direc}')
 
     def go(self, x: int, y: int, z: int, speed: int):
-        self.send_command('go {} {} {} {}'.format(x, y, z, speed))
+        self.send_command(f'go {x} {y} {z} {speed}')
 
     def curve(self, x1: int, y1: int, z1: int, x2: int, y2: int, z2: int, speed: int):
-        self.send_command('curve {} {} {} {} {} {} {}'.format(x1, y1, z1, x2, y2, z2, speed))
+        self.send_command(f'curve {x1} {y1} {z1} {x2} {y2} {z2} {speed}')
 
     # Set Commands
     def set_speed(self, speed: int):
-        self.send_command('speed {}'.format(speed))
+        self.send_command(f'speed {speed}')
 
     def rc_control(self, a: int, b: int, c: int, d: int):
-        self.send_command('rc {} {} {} {}'.format(a, b, c, d))
+        self.send_command(f'rc {a} {b} {c} {d}')
 
     def set_wifi(self, ssid: str, passwrd: str):
-        self.send_command('wifi {} {}'.format(ssid, passwrd))
+        self.send_command(f'wifi {ssid} {passwrd}')
 
     # Read Commands
     def get_speed(self):
         self.send_command('speed?', True)
         return self.log[-1].get_response()
 
     def get_battery(self):
```

### Comparing `tellosync-0.0.3/tellosync.egg-info/PKG-INFO` & `tellosync-0.0.4/tellosync.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tellosync
-Version: 0.0.3
+Version: 0.0.4
 Summary: An easy framework to support DJI Tello scripting in Python 3
 Home-page: https://github.com/vwu1888/easyTello
 Author: Ezra Fielding, Vincent Wu
 Author-email: ezra.fielding@gmail.com, vwu1888@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
```


# Comparing `tmp/ARIclicker-0.3.5.tar.gz` & `tmp/ARIclicker-0.3.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ARIclicker-0.3.5.tar", last modified: Sat Jun 24 04:20:44 2023, max compression
+gzip compressed data, was "ARIclicker-0.3.6.tar", last modified: Wed Jun 28 11:17:11 2023, max compression
```

## Comparing `ARIclicker-0.3.5.tar` & `ARIclicker-0.3.6.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-24 04:20:44.901570 ARIclicker-0.3.5/
-drwxrwxrwx   0        0        0        0 2023-06-24 04:20:44.870348 ARIclicker-0.3.5/ARIclicker/
--rw-rw-rw-   0        0        0     4195 2023-06-24 04:10:02.000000 ARIclicker-0.3.5/ARIclicker/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-24 04:20:44.885958 ARIclicker-0.3.5/ARIclicker.egg-info/
--rw-rw-rw-   0        0        0     1891 2023-06-24 04:20:44.000000 ARIclicker-0.3.5/ARIclicker.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      222 2023-06-24 04:20:44.000000 ARIclicker-0.3.5/ARIclicker.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-24 04:20:44.000000 ARIclicker-0.3.5/ARIclicker.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       26 2023-06-24 04:20:44.000000 ARIclicker-0.3.5/ARIclicker.egg-info/requires.txt
--rw-rw-rw-   0        0        0       11 2023-06-24 04:20:44.000000 ARIclicker-0.3.5/ARIclicker.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     1891 2023-06-24 04:20:44.901570 ARIclicker-0.3.5/PKG-INFO
--rw-rw-rw-   0        0        0     1535 2023-06-24 04:20:24.000000 ARIclicker-0.3.5/README.md
--rw-rw-rw-   0        0        0     1093 2023-06-22 03:55:50.000000 ARIclicker-0.3.5/license.txt
--rw-rw-rw-   0        0        0       42 2023-06-24 04:20:44.901570 ARIclicker-0.3.5/setup.cfg
--rw-rw-rw-   0        0        0      696 2023-06-24 04:20:32.000000 ARIclicker-0.3.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:17:11.766009 ARIclicker-0.3.6/
+drwxrwxrwx   0        0        0        0 2023-06-28 11:17:11.642029 ARIclicker-0.3.6/ARIclicker/
+-rw-rw-rw-   0        0        0     4508 2023-06-28 11:13:26.000000 ARIclicker-0.3.6/ARIclicker/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:17:11.743978 ARIclicker-0.3.6/ARIclicker.egg-info/
+-rw-rw-rw-   0        0        0     1891 2023-06-28 11:17:11.000000 ARIclicker-0.3.6/ARIclicker.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      222 2023-06-28 11:17:11.000000 ARIclicker-0.3.6/ARIclicker.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:17:11.000000 ARIclicker-0.3.6/ARIclicker.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       26 2023-06-28 11:17:11.000000 ARIclicker-0.3.6/ARIclicker.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 11:17:11.000000 ARIclicker-0.3.6/ARIclicker.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     1891 2023-06-28 11:17:11.759017 ARIclicker-0.3.6/PKG-INFO
+-rw-rw-rw-   0        0        0     1535 2023-06-24 04:20:24.000000 ARIclicker-0.3.6/README.md
+-rw-rw-rw-   0        0        0     1093 2023-06-22 03:55:50.000000 ARIclicker-0.3.6/license.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 11:17:11.766009 ARIclicker-0.3.6/setup.cfg
+-rw-rw-rw-   0        0        0      696 2023-06-28 11:16:43.000000 ARIclicker-0.3.6/setup.py
```

### Comparing `ARIclicker-0.3.5/ARIclicker/__init__.py` & `ARIclicker-0.3.6/ARIclicker/__init__.py`

 * *Files 14% similar despite different names*

```diff
@@ -30,25 +30,19 @@
         mouse=Controller()
         while self.program_running:
             while self.running:
                 mouse.click(self.button)
                 time.sleep(random.uniform(self.delay_min, self.delay_max))
 
 
-def autoclick(start_stop_key_character, end_key_character, button,delay_min=None, delay_max=None, delay=None ):
+def autoclick(start_stop_key_character, end_key_character, button,delay_min, delay_max ):
     if button == "left":
         button = Button.left
     if button == "right":
         button = Button.right
-    if delay_min!=None:
-        if delay_max==None or delay!=None:
-            raise Exception
-    else:
-        if delay_min!=None or delay==None:
-            raise Exception
     start_stop_key = KeyCode(char=start_stop_key_character)
     stop_key = KeyCode(char=end_key_character)
     mouse = pynput.mouse.Controller()
     click_thread = ClickMouse(delay_min, delay_max, button)
     click_thread.start()
 
     def on_press(key):
@@ -103,32 +97,50 @@
             else:
                 press_thread.start_pressing()
         elif key == stop_key:
             press_thread.exit()
             listener.stop()
     with Listener(on_press=on_press) as listener:
         listener.join()
-
+autoclick("f","f","left",0.01,0.1)
+'''
 def quickclick(key_start,key_stop,program_stop_key=None,delay_min=None,delay_max=None,delay=None):
+  
     if delay_min!=None:
         if delay_max==None or delay!=None:
             raise Exception
+        else:
+            random=True
+            print(type(delay_min),delay_max)
     else:
-        if delay_min!=None or delay==None:
-            raise Exception  
+        if delay_max!=None or delay==None:
+            raise Exception
+        else:
+            random=False
+    
     def func(key_start,key_stop):
+        
        while True:
             keyboard.wait(key_start)
             time.sleep(0.1)
             while True:
-                pyautogui.click()
-                if keyboard.is_pressed(key_stop):
-                    time.sleep(0.1)
-                    break
+                
+                    delays=random.uniform(delay_min,delay_max)
+                    print(delays)
+
+                    pyautogui.click()
+                    time.sleep(delays)
+                
+                    pyautogui.click(interval=delay)
+                    if keyboard.is_pressed(key_stop):
+                        time.sleep(0.1)
+                        break
     def detect(key):
         while True:
             if keyboard.is_pressed(key):
                 exit(0)       
     t1=threading.Thread(target=func,args=(key_start,key_stop)).start()
     if program_stop_key!=None:
         t2 =threading.Thread(target=detect,args=(program_stop_key)).start()
-  
+quickclick("a","a",delay_min=0.01,delay_max=0.1)
+#autoclick("w","a","left",0.1,0.3)
+'''
```

### Comparing `ARIclicker-0.3.5/ARIclicker.egg-info/PKG-INFO` & `ARIclicker-0.3.6/ARIclicker.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ARIclicker
-Version: 0.3.5
+Version: 0.3.6
 Summary: AutoRandomIntervalClicker
 Home-page: UNKNOWN
 Author: lin_zhe
 Author-email: 2081812728@qq.com
 Maintainer: lin_zhe
 License: MIT License
 Keywords: AutoRandomIntervalClicker
```

### Comparing `ARIclicker-0.3.5/PKG-INFO` & `ARIclicker-0.3.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ARIclicker
-Version: 0.3.5
+Version: 0.3.6
 Summary: AutoRandomIntervalClicker
 Home-page: UNKNOWN
 Author: lin_zhe
 Author-email: 2081812728@qq.com
 Maintainer: lin_zhe
 License: MIT License
 Keywords: AutoRandomIntervalClicker
```

### Comparing `ARIclicker-0.3.5/README.md` & `ARIclicker-0.3.6/README.md`

 * *Files identical despite different names*

### Comparing `ARIclicker-0.3.5/license.txt` & `ARIclicker-0.3.6/license.txt`

 * *Files identical despite different names*

### Comparing `ARIclicker-0.3.5/setup.py` & `ARIclicker-0.3.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup, find_packages
 with open("README.md", "r", encoding='utf-8') as fh:
     long_description = fh.read()
 setup(
     name = 'ARIclicker',
-    version = '0.3.5',
+    version = '0.3.6',
     maintainer='lin_zhe',
     keywords='AutoRandomIntervalClicker',
     description = 'AutoRandomIntervalClicker',
     long_description_content_type='text/markdown',
     long_description=long_description,
     license = 'MIT License',
     author = 'lin_zhe',
```


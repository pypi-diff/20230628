# Comparing `tmp/mathsnip-0.0.4-py2.py3-none-any.whl.zip` & `tmp/mathsnip-0.0.5-py2.py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,15 +1,15 @@
-Zip file size: 7241 bytes, number of entries: 13
--rw-r--r--  2.0 unx      147 b- defN 20-Mar-21 12:43 mathsnip/__init__.py
--rw-r--r--  2.0 unx       80 b- defN 20-Mar-21 12:43 mathsnip/__main__.py
--rw-r--r--  2.0 unx     4832 b- defN 21-Oct-16 15:25 mathsnip/cv_engine.py
--rw-r--r--  2.0 unx     1942 b- defN 21-Oct-16 15:14 mathsnip/mathsnip.py
--rw-r--r--  2.0 unx      101 b- defN 20-Mar-21 12:43 mathsnip/logx/__init__.py
--rw-r--r--  2.0 unx      750 b- defN 20-Mar-21 12:43 mathsnip/logx/colored_handler.py
--rw-r--r--  2.0 unx      647 b- defN 20-Mar-21 12:43 mathsnip/logx/logging.yaml
--rw-r--r--  2.0 unx      851 b- defN 20-Mar-21 12:43 mathsnip/logx/setup_logging.py
--rw-r--r--  2.0 unx     1317 b- defN 21-Oct-16 15:48 mathsnip-0.0.4.dist-info/METADATA
--rw-r--r--  2.0 unx      110 b- defN 21-Oct-16 15:48 mathsnip-0.0.4.dist-info/WHEEL
--rw-r--r--  2.0 unx       51 b- defN 21-Oct-16 15:48 mathsnip-0.0.4.dist-info/entry_points.txt
--rw-r--r--  2.0 unx        9 b- defN 21-Oct-16 15:48 mathsnip-0.0.4.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx     1041 b- defN 21-Oct-16 15:48 mathsnip-0.0.4.dist-info/RECORD
-13 files, 11878 bytes uncompressed, 5497 bytes compressed:  53.7%
+Zip file size: 6041 bytes, number of entries: 13
+-rw-r--r--  2.0 unx      147 b- defN 23-Feb-22 07:13 mathsnip/__init__.py
+-rw-r--r--  2.0 unx       80 b- defN 23-Feb-22 07:13 mathsnip/__main__.py
+-rw-r--r--  2.0 unx     1989 b- defN 23-Jun-28 11:26 mathsnip/mathsnip.py
+-rw-r--r--  2.0 unx     1696 b- defN 23-Jun-28 11:20 mathsnip/service.py
+-rw-r--r--  2.0 unx      101 b- defN 23-Feb-22 07:13 mathsnip/logx/__init__.py
+-rw-r--r--  2.0 unx      750 b- defN 23-Feb-22 07:13 mathsnip/logx/colored_handler.py
+-rw-r--r--  2.0 unx      647 b- defN 23-Feb-22 07:13 mathsnip/logx/logging.yaml
+-rw-r--r--  2.0 unx      851 b- defN 23-Feb-22 07:13 mathsnip/logx/setup_logging.py
+-rw-r--r--  2.0 unx      936 b- defN 23-Jun-28 12:40 mathsnip-0.0.5.dist-info/METADATA
+-rw-r--r--  2.0 unx      110 b- defN 23-Jun-28 12:40 mathsnip-0.0.5.dist-info/WHEEL
+-rw-r--r--  2.0 unx       51 b- defN 23-Jun-28 12:40 mathsnip-0.0.5.dist-info/entry_points.txt
+-rw-r--r--  2.0 unx        9 b- defN 23-Jun-28 12:40 mathsnip-0.0.5.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx     1038 b- defN 23-Jun-28 12:40 mathsnip-0.0.5.dist-info/RECORD
+13 files, 8405 bytes uncompressed, 4301 bytes compressed:  48.8%
```

## zipnote {}

```diff
@@ -1,40 +1,40 @@
 Filename: mathsnip/__init__.py
 Comment: 
 
 Filename: mathsnip/__main__.py
 Comment: 
 
-Filename: mathsnip/cv_engine.py
+Filename: mathsnip/mathsnip.py
 Comment: 
 
-Filename: mathsnip/mathsnip.py
+Filename: mathsnip/service.py
 Comment: 
 
 Filename: mathsnip/logx/__init__.py
 Comment: 
 
 Filename: mathsnip/logx/colored_handler.py
 Comment: 
 
 Filename: mathsnip/logx/logging.yaml
 Comment: 
 
 Filename: mathsnip/logx/setup_logging.py
 Comment: 
 
-Filename: mathsnip-0.0.4.dist-info/METADATA
+Filename: mathsnip-0.0.5.dist-info/METADATA
 Comment: 
 
-Filename: mathsnip-0.0.4.dist-info/WHEEL
+Filename: mathsnip-0.0.5.dist-info/WHEEL
 Comment: 
 
-Filename: mathsnip-0.0.4.dist-info/entry_points.txt
+Filename: mathsnip-0.0.5.dist-info/entry_points.txt
 Comment: 
 
-Filename: mathsnip-0.0.4.dist-info/top_level.txt
+Filename: mathsnip-0.0.5.dist-info/top_level.txt
 Comment: 
 
-Filename: mathsnip-0.0.4.dist-info/RECORD
+Filename: mathsnip-0.0.5.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## mathsnip/mathsnip.py

```diff
@@ -1,69 +1,70 @@
-#coding: utf-8
-from .logx import setup_logging
-import logging
-import argparse
-from pynput import keyboard
-import os
-import subprocess
-
-# don`t remove this line
-import sys
-setup_logging()
-logger = logging.getLogger(__name__)
-
-current=set()
-
-# The key combination to check
-COMBINATIONS = [
-    {keyboard.Key.cmd,keyboard.Key.shift, keyboard.KeyCode(char='e')},
-    {keyboard.Key.cmd,keyboard.Key.shift, keyboard.KeyCode(char='E')}
-]
-
-
-def execute():
-    with open(os.path.join(os.getenv("HOME"),".mathsnip_keypressed"),"w") as f:
-        f.write("")
-
-    current.clear()
-
-def on_press(key):
-    if any([key in COMBO for COMBO in COMBINATIONS]):
-        current.add(key)
-        if any(all(k in current for k in COMBO) for COMBO in COMBINATIONS):
-            execute()
+# Python 3
 
-def on_release(key):
-    if key in current:
-        current.remove(key)
-
-def monitorKey():
-    print("monitor keys..")
-    with keyboard.Listener(on_press=on_press, on_release=on_release) as listener:
-        listener.join()
-
-
-def main(args):
-    if os.geteuid()!=0:
-        print("Must run with root permission!\ntry: sudo mathsnip -i <app_id> -k <app_key>")
-        return
-    # why call like this instread call as moudle? 
-    # both cv and key monitor need mainthread to perform , and both of them needs block somehow. so..
-    cdir = os.path.dirname(os.path.abspath(__file__))
-
-    subprocess.Popen(["python3",os.path.join(cdir,"cv_engine.py"),"-i",args.app_id,"-k",args.app_key])
-    print('monitor.....')
-    monitorKey()
-    print('monitor end.....')
-
-def entry_point():
-    parser = createParse() 
-    mainArgs=parser.parse_args()
-    main(mainArgs)
-
-
-def createParse():
-    parser = argparse.ArgumentParser( formatter_class=argparse.ArgumentDefaultsHelpFormatter, description="")
-    parser.add_argument('-i', '--app_id', help='app id',required=True,type=str)  
-    parser.add_argument('-k', '--app_key', help='app key', required=True,type=str) 
+#FOR TAKING USER PREDEFINED SCREENSHOTS
+# SCREENSHOT
+from PIL import ImageGrab
+# GUI
+import PySimpleGUI as sg
+# FOLDER AND DIRECTORY
+import os
+# GENERIC NAMING
+# Use pywildcard if fnmatch not available
+# just replace anywhere you see fnmatch with pywildcard
+# pip install pywildcard
+import fnmatch
+
+from .service import ocr
+# DEFINE GUI LAYOUT
+layout = [
+        [sg.Button('Screenshot'), sg.Button('Exit')],
+        [sg.Canvas(size=(1, 1), background_color=None, key= 'canvas')]
+        ]
+
+window = sg.Window('Onwa', layout,transparent_color=None,
+                   alpha_channel=.5, grab_anywhere = True, resizable = True) # disable_close=True
+window.Finalize()
+
+canvas = window['canvas']
+
+# SCREEN SHOT FUNC
+def screenshot():
+    window.refresh()
+    lx, ly = window.CurrentLocation()
+    x, y = window.size
+    coord = ((lx+7, ly+30,(x+5+lx +5), (y+ly+30)))
+    img = ImageGrab.grab(coord)
+    return img
+
+# Window main loop
+while True:
+    event, values = window.read()
+    #Close window with "x"  window button
+    # You can disable it by adding " disable_close=True" in the window declaration (Line 20).
+    if event == sg.WIN_CLOSED :
+        break
+
+    if event == 'Exit':
+        break
+
+
+        # Screen shot GUI events
+    elif event == 'Screenshot':
+        window.Hide()
+        img = screenshot()
+
+        #UnHide when function returns
+        window.UnHide()
+        #img.show()
+    # Learn how many screenshots with the same name
+    # Add "1' to the number  then create a new name with it
+    # THis is to avoid replacing existing screenshots
+        shots = fnmatch.filter((shot for shot in os.listdir('.')), 'Onwa*.png')
+        lrn = len(shots)
+        lrn = lrn+1
+        img.save('Onwa%s.png'%lrn)
+        latex = ocr('Onwa%s.png'%lrn)
+        if latex is not None:
+            sg.popup_notify('Screenshot saved!',  location=sg.DEFAULT_WINDOW_LOCATION, display_duration_in_ms=6, fade_in_duration=10)
 
-    return parser
+# CLOSE AND DELETE WINDOW
+window.close();del window
```


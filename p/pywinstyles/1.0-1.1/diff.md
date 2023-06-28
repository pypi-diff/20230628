# Comparing `tmp/pywinstyles-1.0.tar.gz` & `tmp/pywinstyles-1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pywinstyles-1.0.tar", last modified: Sat Jun 24 07:08:45 2023, max compression
+gzip compressed data, was "pywinstyles-1.1.tar", last modified: Wed Jun 28 08:39:14 2023, max compression
```

## Comparing `pywinstyles-1.0.tar` & `pywinstyles-1.1.tar`

### file list

```diff
@@ -1,13 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-24 07:08:45.091378 pywinstyles-1.0/
--rw-rw-rw-   0        0        0     3136 2023-06-24 07:08:45.091378 pywinstyles-1.0/PKG-INFO
--rw-rw-rw-   0        0        0     2559 2023-06-24 07:04:00.000000 pywinstyles-1.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-24 07:08:45.075749 pywinstyles-1.0/pywinstyles/
--rw-rw-rw-   0        0        0      427 2023-06-24 07:05:49.000000 pywinstyles-1.0/pywinstyles/__init__.py
--rw-rw-rw-   0        0        0    10027 2023-06-24 06:31:52.000000 pywinstyles-1.0/pywinstyles/py_win_style.py
-drwxrwxrwx   0        0        0        0 2023-06-24 07:08:45.091378 pywinstyles-1.0/pywinstyles.egg-info/
--rw-rw-rw-   0        0        0     3136 2023-06-24 07:08:45.000000 pywinstyles-1.0/pywinstyles.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      220 2023-06-24 07:08:45.000000 pywinstyles-1.0/pywinstyles.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-24 07:08:45.000000 pywinstyles-1.0/pywinstyles.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       12 2023-06-24 07:08:45.000000 pywinstyles-1.0/pywinstyles.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      602 2023-06-24 07:08:45.091378 pywinstyles-1.0/setup.cfg
--rw-rw-rw-   0        0        0     1026 2023-06-24 07:08:14.000000 pywinstyles-1.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:39:14.253406 pywinstyles-1.1/
+-rw-rw-rw-   0        0        0     7048 2022-11-20 16:16:56.000000 pywinstyles-1.1/LICENSE
+-rw-rw-rw-   0        0        0     3163 2023-06-28 08:39:14.253406 pywinstyles-1.1/PKG-INFO
+-rw-rw-rw-   0        0        0     2563 2023-06-28 08:38:57.000000 pywinstyles-1.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 08:39:14.237776 pywinstyles-1.1/pywinstyles/
+-rw-rw-rw-   0        0        0      427 2023-06-27 12:16:04.000000 pywinstyles-1.1/pywinstyles/__init__.py
+-rw-rw-rw-   0        0        0    10290 2023-06-28 08:36:10.000000 pywinstyles-1.1/pywinstyles/py_win_style.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:39:14.253406 pywinstyles-1.1/pywinstyles.egg-info/
+-rw-rw-rw-   0        0        0     3163 2023-06-28 08:39:14.000000 pywinstyles-1.1/pywinstyles.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      228 2023-06-28 08:39:14.000000 pywinstyles-1.1/pywinstyles.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:39:14.000000 pywinstyles-1.1/pywinstyles.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 08:39:14.000000 pywinstyles-1.1/pywinstyles.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      602 2023-06-28 08:39:14.269035 pywinstyles-1.1/setup.cfg
+-rw-rw-rw-   0        0        0     1026 2023-06-28 08:31:36.000000 pywinstyles-1.1/setup.py
```

### Comparing `pywinstyles-1.0/PKG-INFO` & `pywinstyles-1.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,25 +1,26 @@
 Metadata-Version: 2.1
 Name: pywinstyles
-Version: 1.0
+Version: 1.1
 Summary:  Customize window styles in windows 11
 Home-page: https://github.com/Akascape/py-window-styles
 Author: Akash Bora
 License: Creative Commons Zero v1.0 Universal
 Keywords: window-styles,customtkinter,tkinter,python-window,gui,python-gui,pyqt,title-bar,title-bar-color
 Classifier: License :: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+License-File: LICENSE
 
 # py-window-styles
 
 Customize your UI window with awesome built-in windows 11 header styles and themes.
-**This is only for windows 11 (some themes may not work in windows 10).**
+**This is only for windows 11 (some themes may not work with windows 10).**
 
 ![Screenshot 2023-06-19 205353](https://github.com/Akascape/py-window-styles/assets/89206401/986062c0-30a0-4289-929a-e5e2440b8dd1)
 
 ## Installation
 ```
 pip install pywinstyles
 ```
@@ -54,13 +55,13 @@
 ```
 ### Changing Title Text Color
 ```python
 pywinstyles.change_title_color(window, color="white") 
 ```
 ### Change Border Color
 ```python
-pywinstyles.change_border_color(root, color="#00ffff")
+pywinstyles.change_border_color(window, color="#00ffff")
 ```
 
 **Hope this project will help in UI development with python**
 
 **Author: Akash Bora**
```

### Comparing `pywinstyles-1.0/README.md` & `pywinstyles-1.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 # py-window-styles
 
 Customize your UI window with awesome built-in windows 11 header styles and themes.
-**This is only for windows 11 (some themes may not work in windows 10).**
+**This is only for windows 11 (some themes may not work with windows 10).**
 
 ![Screenshot 2023-06-19 205353](https://github.com/Akascape/py-window-styles/assets/89206401/986062c0-30a0-4289-929a-e5e2440b8dd1)
 
 ## Installation
 ```
 pip install pywinstyles
 ```
@@ -40,13 +40,13 @@
 ```
 ### Changing Title Text Color
 ```python
 pywinstyles.change_title_color(window, color="white") 
 ```
 ### Change Border Color
 ```python
-pywinstyles.change_border_color(root, color="#00ffff")
+pywinstyles.change_border_color(window, color="#00ffff")
 ```
 
 **Hope this project will help in UI development with python**
 
 **Author: Akash Bora**
```

### Comparing `pywinstyles-1.0/pywinstyles/py_win_style.py` & `pywinstyles-1.1/pywinstyles/py_win_style.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 """
 Py-Win-Styles
 Author: Akash Bora
-Version: 1.0
+Version: 1.1
 """
 
 try:
     from ctypes import POINTER, pointer, sizeof, windll, Structure, byref, c_int
     from ctypes.wintypes import DWORD, ULONG
 except ImportError:
     raise ImportError("pywinstyles import errror: No windows environment detected!")
@@ -44,16 +44,18 @@
         if style=="mica":
             ChangeDWMAttrib(self.HWND, 19, c_int(1))
             ChangeDWMAttrib(self.HWND, 1029, c_int(0x01))
         elif style=="optimised":
             ChangeDWMAccent(self.HWND, 30, 1)
         elif style=="dark":
             ChangeDWMAttrib(self.HWND, 19, c_int(1))
+            ChangeDWMAttrib(self.HWND, 20, c_int(1))
         elif style=="light":
             ChangeDWMAttrib(self.HWND, 19, c_int(0))
+            ChangeDWMAttrib(self.HWND, 20, c_int(0))
         elif style=="inverse":
             ChangeDWMAccent(self.HWND, 6, 1)
         elif style=="win7":
             ChangeDWMAccent(self.HWND, 11, 1)
         elif style=="aero":
             window.config(bg="black")
             ChangeDWMAccent(self.HWND, 30, 2)
@@ -284,14 +286,16 @@
         "yellow": "#ffff00",
         "yellowgreen": "#9acd32",
     }
     
     if not color_name.startswith("#"):
         if color_name in NAMES_TO_HEX:
             color =  NAMES_TO_HEX[color_name]
+        elif color_name.startswith("grey") or color_name.startswith("gray"):
+            color = f"#{color_name[-2:]}{color_name[-2:]}{color_name[-2:]}"
         else:
             raise ValueError(f"Invalid color passed: {color_name}")
     else:
         color = color_name
         
     color = f"{color[5:7]}{color[3:5]}{color[1:3]}"
     return color
```

### Comparing `pywinstyles-1.0/pywinstyles.egg-info/PKG-INFO` & `pywinstyles-1.1/pywinstyles.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,25 +1,26 @@
 Metadata-Version: 2.1
 Name: pywinstyles
-Version: 1.0
+Version: 1.1
 Summary:  Customize window styles in windows 11
 Home-page: https://github.com/Akascape/py-window-styles
 Author: Akash Bora
 License: Creative Commons Zero v1.0 Universal
 Keywords: window-styles,customtkinter,tkinter,python-window,gui,python-gui,pyqt,title-bar,title-bar-color
 Classifier: License :: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+License-File: LICENSE
 
 # py-window-styles
 
 Customize your UI window with awesome built-in windows 11 header styles and themes.
-**This is only for windows 11 (some themes may not work in windows 10).**
+**This is only for windows 11 (some themes may not work with windows 10).**
 
 ![Screenshot 2023-06-19 205353](https://github.com/Akascape/py-window-styles/assets/89206401/986062c0-30a0-4289-929a-e5e2440b8dd1)
 
 ## Installation
 ```
 pip install pywinstyles
 ```
@@ -54,13 +55,13 @@
 ```
 ### Changing Title Text Color
 ```python
 pywinstyles.change_title_color(window, color="white") 
 ```
 ### Change Border Color
 ```python
-pywinstyles.change_border_color(root, color="#00ffff")
+pywinstyles.change_border_color(window, color="#00ffff")
 ```
 
 **Hope this project will help in UI development with python**
 
 **Author: Akash Bora**
```

### Comparing `pywinstyles-1.0/setup.cfg` & `pywinstyles-1.1/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2070 7977 696e 7374 796c 6573 0d0a   = pywinstyles..
-00000020: 7665 7273 696f 6e20 3d20 312e 300d 0a64  version = 1.0..d
+00000020: 7665 7273 696f 6e20 3d20 312e 310d 0a64  version = 1.1..d
 00000030: 6573 6372 6970 7469 6f6e 203d 2043 7573  escription = Cus
 00000040: 746f 6d69 7a65 2077 696e 646f 7720 7374  tomize window st
 00000050: 796c 6573 2069 6e20 7769 6e64 6f77 7320  yles in windows 
 00000060: 3131 0d0a 6c6f 6e67 5f64 6573 6372 6970  11..long_descrip
 00000070: 7469 6f6e 203d 2066 696c 653a 2052 4541  tion = file: REA
 00000080: 444d 452e 6d64 0d0a 6c6f 6e67 5f64 6573  DME.md..long_des
 00000090: 6372 6970 7469 6f6e 5f63 6f6e 7465 6e74  cription_content
```

### Comparing `pywinstyles-1.0/setup.py` & `pywinstyles-1.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -4,15 +4,15 @@
     """Opens and fetches text of long descrition file."""
     with open(path, 'r') as f:
         text = f.read()
     return text
 
 setup(
     name = 'pywinstyles',
-    version = '1.0',
+    version = '1.1',
     description = " Customize window styles in windows 11",
     license = "Creative Commons Zero v1.0 Universal",
     readme = "README.md",
     long_description = get_long_description('README.md'),
     long_description_content_type = "text/markdown",
     author = 'Akash Bora',
     url = "https://github.com/Akascape/py-window-styles",
```


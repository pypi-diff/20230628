# Comparing `tmp/uitk-0.7.6.tar.gz` & `tmp/uitk-0.7.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "uitk-0.7.6.tar", last modified: Wed Jun 28 02:20:34 2023, max compression
+gzip compressed data, was "uitk-0.7.7.tar", last modified: Wed Jun 28 02:21:10 2023, max compression
```

## Comparing `uitk-0.7.6.tar` & `uitk-0.7.7.tar`

### file list

```diff
@@ -1,44 +1,44 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 02:20:34.826028 uitk-0.7.6/
--rw-rw-rw-   0        0        0     7815 2023-04-16 12:18:04.000000 uitk-0.7.6/COPYING.LESSER
--rw-rw-rw-   0        0        0       24 2023-03-28 23:38:26.000000 uitk-0.7.6/MANIFEST.in
--rw-rw-rw-   0        0        0     3691 2023-06-28 02:20:34.826028 uitk-0.7.6/PKG-INFO
--rw-rw-rw-   0        0        0       42 2023-06-28 02:20:34.827029 uitk-0.7.6/setup.cfg
--rw-rw-rw-   0        0        0     1535 2023-06-28 02:16:42.000000 uitk-0.7.6/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 02:20:34.767757 uitk-0.7.6/uitk/
--rw-rw-rw-   0        0        0     2937 2023-06-28 02:20:31.000000 uitk-0.7.6/uitk/__init__.py
--rw-rw-rw-   0        0        0    14483 2023-06-24 19:54:52.000000 uitk-0.7.6/uitk/events.py
--rw-rw-rw-   0        0        0   104230 2023-06-27 17:23:37.000000 uitk-0.7.6/uitk/switchboard.py
--rw-rw-rw-   0        0        0   102727 2023-06-24 17:53:40.000000 uitk-0.7.6/uitk/switchboard.py.bak
-drwxrwxrwx   0        0        0        0 2023-06-28 02:20:34.813822 uitk-0.7.6/uitk/widgets/
--rw-rw-rw-   0        0        0    18968 2023-06-27 13:33:51.000000 uitk-0.7.6/uitk/widgets/MainWindow.py
--rw-rw-rw-   0        0        0     3204 2023-05-24 20:56:51.000000 uitk-0.7.6/uitk/widgets/__init__.py
--rw-rw-rw-   0        0        0    15870 2023-06-24 02:15:31.000000 uitk-0.7.6/uitk/widgets/attributeWindow.py
--rw-rw-rw-   0        0        0     5204 2023-06-27 19:27:11.000000 uitk-0.7.6/uitk/widgets/checkBox.py
--rw-rw-rw-   0        0        0     8332 2023-06-20 19:15:01.000000 uitk-0.7.6/uitk/widgets/comboBox.py
--rw-rw-rw-   0        0        0     7036 2023-06-10 13:16:59.000000 uitk-0.7.6/uitk/widgets/draggableHeader.py
--rw-rw-rw-   0        0        0    22380 2023-06-02 21:56:26.000000 uitk-0.7.6/uitk/widgets/expandableList.py
--rw-rw-rw-   0        0        0     2498 2023-06-02 17:31:37.000000 uitk-0.7.6/uitk/widgets/label.py
--rw-rw-rw-   0        0        0     3295 2023-06-15 19:41:53.000000 uitk-0.7.6/uitk/widgets/lineEdit.py
--rw-rw-rw-   0        0        0    23456 2023-06-19 14:36:41.000000 uitk-0.7.6/uitk/widgets/menu.py
--rw-rw-rw-   0        0        0     8559 2023-06-23 14:22:44.000000 uitk-0.7.6/uitk/widgets/messageBox.py
-drwxrwxrwx   0        0        0        0 2023-06-28 02:20:34.825029 uitk-0.7.6/uitk/widgets/mixins/
--rw-rw-rw-   0        0        0     3028 2023-05-12 17:13:16.000000 uitk-0.7.6/uitk/widgets/mixins/__init__.py
--rw-rw-rw-   0        0        0    12614 2023-06-25 19:11:11.000000 uitk-0.7.6/uitk/widgets/mixins/attributes.py
--rw-rw-rw-   0        0        0     4023 2023-05-12 17:25:02.000000 uitk-0.7.6/uitk/widgets/mixins/convert.py
--rw-rw-rw-   0        0        0     9499 2023-05-20 02:33:14.000000 uitk-0.7.6/uitk/widgets/mixins/docking.py
--rw-rw-rw-   0        0        0     5044 2023-06-17 23:02:35.000000 uitk-0.7.6/uitk/widgets/mixins/menu_instance.py
--rw-rw-rw-   0        0        0    48322 2023-06-27 14:57:09.000000 uitk-0.7.6/uitk/widgets/mixins/style_sheet.py
--rw-rw-rw-   0        0        0     3409 2023-05-12 17:27:14.000000 uitk-0.7.6/uitk/widgets/mixins/tasks.py
--rw-rw-rw-   0        0        0    11099 2023-05-12 17:26:59.000000 uitk-0.7.6/uitk/widgets/mixins/text.py
--rw-rw-rw-   0        0        0     6204 2023-06-10 12:44:09.000000 uitk-0.7.6/uitk/widgets/optionBox.py
--rw-rw-rw-   0        0        0     3278 2023-06-05 16:23:13.000000 uitk-0.7.6/uitk/widgets/progressBar.py
--rw-rw-rw-   0        0        0     3069 2023-06-15 19:57:41.000000 uitk-0.7.6/uitk/widgets/pushButton.py
--rw-rw-rw-   0        0        0     7907 2023-05-28 21:08:35.000000 uitk-0.7.6/uitk/widgets/region.py
--rw-rw-rw-   0        0        0     3709 2023-06-12 14:42:27.000000 uitk-0.7.6/uitk/widgets/textEdit.py
-drwxrwxrwx   0        0        0        0 2023-06-28 02:20:34.799297 uitk-0.7.6/uitk.egg-info/
--rw-rw-rw-   0        0        0     3691 2023-06-28 02:20:34.000000 uitk-0.7.6/uitk.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     4282 2023-05-11 02:02:25.000000 uitk-0.7.6/uitk.egg-info/PKG-INFO.bak
--rw-rw-rw-   0        0        0      985 2023-06-28 02:20:34.000000 uitk-0.7.6/uitk.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0      767 2023-04-15 12:48:17.000000 uitk-0.7.6/uitk.egg-info/SOURCES.txt.bak
--rw-rw-rw-   0        0        0        1 2023-06-28 02:20:34.000000 uitk-0.7.6/uitk.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        5 2023-06-28 02:20:34.000000 uitk-0.7.6/uitk.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 02:21:10.937505 uitk-0.7.7/
+-rw-rw-rw-   0        0        0     7815 2023-04-16 12:18:04.000000 uitk-0.7.7/COPYING.LESSER
+-rw-rw-rw-   0        0        0       24 2023-03-28 23:38:26.000000 uitk-0.7.7/MANIFEST.in
+-rw-rw-rw-   0        0        0     3691 2023-06-28 02:21:10.936488 uitk-0.7.7/PKG-INFO
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:21:10.937505 uitk-0.7.7/setup.cfg
+-rw-rw-rw-   0        0        0     1535 2023-06-28 02:16:42.000000 uitk-0.7.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:21:10.896397 uitk-0.7.7/uitk/
+-rw-rw-rw-   0        0        0     2937 2023-06-28 02:21:07.000000 uitk-0.7.7/uitk/__init__.py
+-rw-rw-rw-   0        0        0    14483 2023-06-24 19:54:52.000000 uitk-0.7.7/uitk/events.py
+-rw-rw-rw-   0        0        0   104230 2023-06-27 17:23:37.000000 uitk-0.7.7/uitk/switchboard.py
+-rw-rw-rw-   0        0        0   102727 2023-06-24 17:53:40.000000 uitk-0.7.7/uitk/switchboard.py.bak
+drwxrwxrwx   0        0        0        0 2023-06-28 02:21:10.926968 uitk-0.7.7/uitk/widgets/
+-rw-rw-rw-   0        0        0    18968 2023-06-27 13:33:51.000000 uitk-0.7.7/uitk/widgets/MainWindow.py
+-rw-rw-rw-   0        0        0     3204 2023-05-24 20:56:51.000000 uitk-0.7.7/uitk/widgets/__init__.py
+-rw-rw-rw-   0        0        0    15870 2023-06-24 02:15:31.000000 uitk-0.7.7/uitk/widgets/attributeWindow.py
+-rw-rw-rw-   0        0        0     5204 2023-06-27 19:27:11.000000 uitk-0.7.7/uitk/widgets/checkBox.py
+-rw-rw-rw-   0        0        0     8332 2023-06-20 19:15:01.000000 uitk-0.7.7/uitk/widgets/comboBox.py
+-rw-rw-rw-   0        0        0     7036 2023-06-10 13:16:59.000000 uitk-0.7.7/uitk/widgets/draggableHeader.py
+-rw-rw-rw-   0        0        0    22380 2023-06-02 21:56:26.000000 uitk-0.7.7/uitk/widgets/expandableList.py
+-rw-rw-rw-   0        0        0     2498 2023-06-02 17:31:37.000000 uitk-0.7.7/uitk/widgets/label.py
+-rw-rw-rw-   0        0        0     3295 2023-06-15 19:41:53.000000 uitk-0.7.7/uitk/widgets/lineEdit.py
+-rw-rw-rw-   0        0        0    23456 2023-06-19 14:36:41.000000 uitk-0.7.7/uitk/widgets/menu.py
+-rw-rw-rw-   0        0        0     8559 2023-06-23 14:22:44.000000 uitk-0.7.7/uitk/widgets/messageBox.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:21:10.935486 uitk-0.7.7/uitk/widgets/mixins/
+-rw-rw-rw-   0        0        0     3028 2023-05-12 17:13:16.000000 uitk-0.7.7/uitk/widgets/mixins/__init__.py
+-rw-rw-rw-   0        0        0    12614 2023-06-25 19:11:11.000000 uitk-0.7.7/uitk/widgets/mixins/attributes.py
+-rw-rw-rw-   0        0        0     4023 2023-05-12 17:25:02.000000 uitk-0.7.7/uitk/widgets/mixins/convert.py
+-rw-rw-rw-   0        0        0     9499 2023-05-20 02:33:14.000000 uitk-0.7.7/uitk/widgets/mixins/docking.py
+-rw-rw-rw-   0        0        0     5044 2023-06-17 23:02:35.000000 uitk-0.7.7/uitk/widgets/mixins/menu_instance.py
+-rw-rw-rw-   0        0        0    48322 2023-06-27 14:57:09.000000 uitk-0.7.7/uitk/widgets/mixins/style_sheet.py
+-rw-rw-rw-   0        0        0     3409 2023-05-12 17:27:14.000000 uitk-0.7.7/uitk/widgets/mixins/tasks.py
+-rw-rw-rw-   0        0        0    11099 2023-05-12 17:26:59.000000 uitk-0.7.7/uitk/widgets/mixins/text.py
+-rw-rw-rw-   0        0        0     6204 2023-06-10 12:44:09.000000 uitk-0.7.7/uitk/widgets/optionBox.py
+-rw-rw-rw-   0        0        0     3278 2023-06-05 16:23:13.000000 uitk-0.7.7/uitk/widgets/progressBar.py
+-rw-rw-rw-   0        0        0     3069 2023-06-15 19:57:41.000000 uitk-0.7.7/uitk/widgets/pushButton.py
+-rw-rw-rw-   0        0        0     7907 2023-05-28 21:08:35.000000 uitk-0.7.7/uitk/widgets/region.py
+-rw-rw-rw-   0        0        0     3709 2023-06-12 14:42:27.000000 uitk-0.7.7/uitk/widgets/textEdit.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:21:10.910599 uitk-0.7.7/uitk.egg-info/
+-rw-rw-rw-   0        0        0     3691 2023-06-28 02:21:10.000000 uitk-0.7.7/uitk.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     4282 2023-05-11 02:02:25.000000 uitk-0.7.7/uitk.egg-info/PKG-INFO.bak
+-rw-rw-rw-   0        0        0      985 2023-06-28 02:21:10.000000 uitk-0.7.7/uitk.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0      767 2023-04-15 12:48:17.000000 uitk-0.7.7/uitk.egg-info/SOURCES.txt.bak
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:21:10.000000 uitk-0.7.7/uitk.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        5 2023-06-28 02:21:10.000000 uitk-0.7.7/uitk.egg-info/top_level.txt
```

### Comparing `uitk-0.7.6/COPYING.LESSER` & `uitk-0.7.7/COPYING.LESSER`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/PKG-INFO` & `uitk-0.7.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: uitk
-Version: 0.7.6
+Version: 0.7.7
 Home-page: https://github.com/m3trik/uitk
 Author: Ryan Simpson
 Author-email: m3trik@outlook.com
 License: LGPLv3
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Library or Lesser General Public License (LGPL)
 Classifier: Operating System :: OS Independent
```

### Comparing `uitk-0.7.6/setup.py` & `uitk-0.7.7/setup.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/__init__.py` & `uitk-0.7.7/uitk/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 import importlib
 import pkgutil
 import inspect
 from .switchboard import signals  # Make signals accessible at package root
 
 
 __package__ = "uitk"
-__version__ = '0.7.6'
+__version__ = '0.7.7'
 __path__ = [os.path.abspath(os.path.dirname(__file__))]
 
 
 # Define a dictionary to map class names to their respective modules
 CLASS_TO_MODULE = {}
 
 # Build the CLASS_TO_MODULE dictionary by iterating over all submodules of the package
```

### Comparing `uitk-0.7.6/uitk/events.py` & `uitk-0.7.7/uitk/events.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/switchboard.py` & `uitk-0.7.7/uitk/switchboard.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/switchboard.py.bak` & `uitk-0.7.7/uitk/switchboard.py.bak`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/MainWindow.py` & `uitk-0.7.7/uitk/widgets/MainWindow.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/__init__.py` & `uitk-0.7.7/uitk/widgets/__init__.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/attributeWindow.py` & `uitk-0.7.7/uitk/widgets/attributeWindow.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/checkBox.py` & `uitk-0.7.7/uitk/widgets/checkBox.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/comboBox.py` & `uitk-0.7.7/uitk/widgets/comboBox.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/draggableHeader.py` & `uitk-0.7.7/uitk/widgets/draggableHeader.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/expandableList.py` & `uitk-0.7.7/uitk/widgets/expandableList.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/label.py` & `uitk-0.7.7/uitk/widgets/label.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/lineEdit.py` & `uitk-0.7.7/uitk/widgets/lineEdit.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/menu.py` & `uitk-0.7.7/uitk/widgets/menu.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/messageBox.py` & `uitk-0.7.7/uitk/widgets/messageBox.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/__init__.py` & `uitk-0.7.7/uitk/widgets/mixins/__init__.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/attributes.py` & `uitk-0.7.7/uitk/widgets/mixins/attributes.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/convert.py` & `uitk-0.7.7/uitk/widgets/mixins/convert.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/docking.py` & `uitk-0.7.7/uitk/widgets/mixins/docking.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/menu_instance.py` & `uitk-0.7.7/uitk/widgets/mixins/menu_instance.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/style_sheet.py` & `uitk-0.7.7/uitk/widgets/mixins/style_sheet.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/tasks.py` & `uitk-0.7.7/uitk/widgets/mixins/tasks.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/mixins/text.py` & `uitk-0.7.7/uitk/widgets/mixins/text.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/optionBox.py` & `uitk-0.7.7/uitk/widgets/optionBox.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/progressBar.py` & `uitk-0.7.7/uitk/widgets/progressBar.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/pushButton.py` & `uitk-0.7.7/uitk/widgets/pushButton.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/region.py` & `uitk-0.7.7/uitk/widgets/region.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk/widgets/textEdit.py` & `uitk-0.7.7/uitk/widgets/textEdit.py`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk.egg-info/PKG-INFO` & `uitk-0.7.7/uitk.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: uitk
-Version: 0.7.6
+Version: 0.7.7
 Home-page: https://github.com/m3trik/uitk
 Author: Ryan Simpson
 Author-email: m3trik@outlook.com
 License: LGPLv3
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Library or Lesser General Public License (LGPL)
 Classifier: Operating System :: OS Independent
```

### Comparing `uitk-0.7.6/uitk.egg-info/PKG-INFO.bak` & `uitk-0.7.7/uitk.egg-info/PKG-INFO.bak`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk.egg-info/SOURCES.txt` & `uitk-0.7.7/uitk.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `uitk-0.7.6/uitk.egg-info/SOURCES.txt.bak` & `uitk-0.7.7/uitk.egg-info/SOURCES.txt.bak`

 * *Files identical despite different names*


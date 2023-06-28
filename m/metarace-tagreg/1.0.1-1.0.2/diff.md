# Comparing `tmp/metarace-tagreg-1.0.1.tar.gz` & `tmp/metarace-tagreg-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/home/ndf/dev/metarace/metarace-tagreg/dist/.tmp-x2gs8q9m/metarace-tagreg-1.0.1.tar", last modified: Tue Jun  6 07:37:31 2023, max compression
+gzip compressed data, was "metarace-tagreg-1.0.2.tar", last modified: Wed Jun 28 02:34:09 2023, max compression
```

## Comparing `metarace-tagreg-1.0.1.tar` & `metarace-tagreg-1.0.2.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1063 2022-11-13 23:56:28.000000 metarace-tagreg-1.0.1/LICENSE
--rw-r--r--   0 ndf       (1000) ndf       (1000)      897 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)      388 2023-06-06 07:36:17.000000 metarace-tagreg-1.0.1/README.md
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/
--rw-r--r--   0 ndf       (1000) ndf       (1000)      897 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)      278 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/SOURCES.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/dependency_links.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       39 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/entry_points.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       16 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/requires.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        7 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/metarace_tagreg.egg-info/top_level.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)      686 2023-06-06 07:27:08.000000 metarace-tagreg-1.0.1/pyproject.toml
--rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-06 07:37:31.000000 metarace-tagreg-1.0.1/setup.cfg
--rw-r--r--   0 ndf       (1000) ndf       (1000)    35530 2023-06-05 05:16:22.000000 metarace-tagreg-1.0.1/tagreg.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 02:34:09.148739 metarace-tagreg-1.0.2/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1063 2022-11-13 23:56:28.000000 metarace-tagreg-1.0.2/LICENSE
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1303 2023-06-28 02:34:09.148739 metarace-tagreg-1.0.2/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      794 2023-06-28 02:33:25.000000 metarace-tagreg-1.0.2/README.md
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 02:34:09.144739 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1303 2023-06-28 02:34:09.000000 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      278 2023-06-28 02:34:09.000000 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/SOURCES.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 02:34:09.000000 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/dependency_links.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       39 2023-06-28 02:34:09.000000 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/entry_points.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       16 2023-06-28 02:34:09.000000 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/requires.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        7 2023-06-28 02:34:09.000000 metarace-tagreg-1.0.2/metarace_tagreg.egg-info/top_level.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      686 2023-06-28 01:12:59.000000 metarace-tagreg-1.0.2/pyproject.toml
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 02:34:09.148739 metarace-tagreg-1.0.2/setup.cfg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    35649 2023-06-28 02:28:38.000000 metarace-tagreg-1.0.2/tagreg.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `metarace-tagreg-1.0.1/LICENSE` & `metarace-tagreg-1.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `metarace-tagreg-1.0.1/PKG-INFO` & `metarace-tagreg-1.0.2/PKG-INFO`

 * *Files 27% similar despite different names*

```diff
@@ -1,36 +1,49 @@
 Metadata-Version: 2.1
 Name: metarace-tagreg
-Version: 1.0.1
+Version: 1.0.2
 Summary: Transponder allocation tool
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace-tagreg
 Keywords: transponder
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
-Requires-Python: >=3.6
+Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # metarace-tagreg
 
 Read transponder ids from a connected
 decoder.
 
 ![tagreg screenshot](screenshot.png "tagreg")
 
 ## Requirements
 
+   - Python >= 3.9
    - Gtk >= 3.0
-   - metarace >= 2.1.0
+   - metarace >= 2.1.1
 
 
 ## Installation
 
-[Install metarace](https://github.com/ndf-zz/metarace#installation)
-and the required system packages then install tagreg using pip:
+### Debian 11+
+
+Install system requirements for tagreg and metarace with apt:
+
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-gtk-3.0 gir1.2-rsvg-2.0 gir1.2-pango-1.0
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
+
+If not already created, add a virtualenv for metarace packages:
+
+	$ python3 -m venv --system-site-packages ~/Documents/metarace/venv
+
+Activate the virtualenv and install tagreg with pip:
+
+	$ source ~/Documents/metarace/venv/bin/activate
+	(venv) $ pip3 install tagreg
 
-	$ sudo apt install gir1.2-gtk-3.0
-	$ pip install metarace-tagreg
```

### Comparing `metarace-tagreg-1.0.1/metarace_tagreg.egg-info/PKG-INFO` & `metarace-tagreg-1.0.2/metarace_tagreg.egg-info/PKG-INFO`

 * *Files 27% similar despite different names*

```diff
@@ -1,36 +1,49 @@
 Metadata-Version: 2.1
 Name: metarace-tagreg
-Version: 1.0.1
+Version: 1.0.2
 Summary: Transponder allocation tool
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace-tagreg
 Keywords: transponder
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
-Requires-Python: >=3.6
+Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # metarace-tagreg
 
 Read transponder ids from a connected
 decoder.
 
 ![tagreg screenshot](screenshot.png "tagreg")
 
 ## Requirements
 
+   - Python >= 3.9
    - Gtk >= 3.0
-   - metarace >= 2.1.0
+   - metarace >= 2.1.1
 
 
 ## Installation
 
-[Install metarace](https://github.com/ndf-zz/metarace#installation)
-and the required system packages then install tagreg using pip:
+### Debian 11+
+
+Install system requirements for tagreg and metarace with apt:
+
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-gtk-3.0 gir1.2-rsvg-2.0 gir1.2-pango-1.0
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
+
+If not already created, add a virtualenv for metarace packages:
+
+	$ python3 -m venv --system-site-packages ~/Documents/metarace/venv
+
+Activate the virtualenv and install tagreg with pip:
+
+	$ source ~/Documents/metarace/venv/bin/activate
+	(venv) $ pip3 install tagreg
 
-	$ sudo apt install gir1.2-gtk-3.0
-	$ pip install metarace-tagreg
```

### Comparing `metarace-tagreg-1.0.1/pyproject.toml` & `metarace-tagreg-1.0.2/pyproject.toml`

 * *Files 3% similar despite different names*

```diff
@@ -1,30 +1,30 @@
 [build-system]
 requires = ["setuptools>=62"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "metarace-tagreg"
-version = "1.0.1"
+version = "1.0.2"
 description = "Transponder allocation tool"
 readme = "README.md"
-requires-python = ">=3.6"
+requires-python = ">=3.9"
 license = {text = "MIT"}
 keywords = ["transponder"]
 authors = [
     {email = "ndf-zz@6-v.org", name = "Nathan Fraser"}
 ]
 classifiers = [
     "Development Status :: 3 - Alpha",
     "Topic :: Other/Nonlisted Topic",
     "Operating System :: OS Independent",
     "Programming Language :: Python :: 3",
 ]
 dependencies = [
-    "metarace>=2.1.0",
+    "metarace>=2.1.1",
 ]
 [project.urls]
 homepage = "https://github.com/ndf-zz/metarace-tagreg"
 
 [project.scripts]
 tagreg = "tagreg:main"
```

### Comparing `metarace-tagreg-1.0.1/tagreg.py` & `metarace-tagreg-1.0.2/tagreg.py`

 * *Files 1% similar despite different names*

```diff
@@ -21,21 +21,19 @@
 
 gi.require_version("GLib", "2.0")
 from gi.repository import GLib
 
 gi.require_version("Gtk", "3.0")
 from gi.repository import Gtk
 
-gi.require_version("Gdk", "3.0")
-from gi.repository import Gdk
-
 _LOGLEVEL = logging.DEBUG
 _log = logging.getLogger('tagreg')
 _log.setLevel(_LOGLEVEL)
 
+VERSION = '1.0.2'
 _DEFTYPE = 'rrs'
 _DEFPORT = ''
 _FAILTHRESH = 10
 _CONFIGFILE = '.tagreg.json'
 
 
 def addTextColumn(view,
@@ -73,15 +71,17 @@
 def chooseCsvFile(title='',
                   mode=Gtk.FileChooserAction.OPEN,
                   parent=None,
                   path=None,
                   hintfile=None):
     """Open a native file chooser dialog to load/save a CSV file"""
     ret = None
-    dialog = Gtk.FileChooserNative.new(title, parent, mode, None, None)
+    dialog = Gtk.FileChooserNative(title=title, modal=True)
+    dialog.set_transient_for(parent)
+    dialog.set_action(mode)
     filter = Gtk.FileFilter()
     filter.set_name('CSV Files')
     filter.add_mime_type('text/csv')
     filter.add_pattern('*.csv')
     dialog.add_filter(filter)
     filter = Gtk.FileFilter()
     filter.set_name('All Files')
@@ -926,14 +926,19 @@
         cw.set('tagreg', 'checkin', self._checkIn)
         with metarace.savefile(_CONFIGFILE) as f:
             cw.write(f)
 
 
 def main():
     """Run the tagreg application"""
+    chk = Gtk.init_check()
+    if not chk[0]:
+        print('Unable to init Gtk display')
+        sys.exit(-1)
+
     ch = logging.StreamHandler()
     ch.setLevel(_LOGLEVEL)
     fh = logging.Formatter(metarace.LOGFORMAT)
     ch.setFormatter(fh)
     logging.getLogger().addHandler(ch)
     metarace.init()
     _load_images(_button_images)
```


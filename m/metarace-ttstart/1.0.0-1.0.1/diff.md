# Comparing `tmp/metarace-ttstart-1.0.0.tar.gz` & `tmp/metarace-ttstart-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/home/ndf/dev/metarace/metarace-ttstart/dist/tmp79xud41t/metarace-ttstart-1.0.0.tar", last modified: Mon Oct 17 04:16:19 2022, max compression
+gzip compressed data, was "metarace-ttstart-1.0.1.tar", last modified: Wed Jun 28 03:22:21 2023, max compression
```

## Comparing `metarace-ttstart-1.0.0.tar` & `metarace-ttstart-1.0.1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1063 2022-10-16 22:46:07.000000 metarace-ttstart-1.0.0/LICENSE
--rw-r--r--   0 ndf       (1000) ndf       (1000)       30 2022-10-17 01:40:59.000000 metarace-ttstart-1.0.0/MANIFEST.in
--rw-r--r--   0 ndf       (1000) ndf       (1000)     2722 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)     2217 2022-10-17 04:13:48.000000 metarace-ttstart-1.0.0/README.md
--rw-r--r--   0 ndf       (1000) ndf       (1000)      680 2022-10-17 01:41:27.000000 metarace-ttstart-1.0.0/pyproject.toml
--rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/setup.cfg
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     2722 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)      380 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/SOURCES.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/dependency_links.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       41 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/entry_points.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/requires.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        8 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/top_level.txt
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2022-10-17 04:16:19.000000 metarace-ttstart-1.0.0/src/ttstart/
--rwxr-xr-x   0 ndf       (1000) ndf       (1000)    22754 2022-10-17 03:37:31.000000 metarace-ttstart-1.0.0/src/ttstart/__init__.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)       79 2022-10-17 01:36:19.000000 metarace-ttstart-1.0.0/src/ttstart/__main__.py
--rw-------   0 ndf       (1000) ndf       (1000)  1058444 2022-10-13 09:23:49.000000 metarace-ttstart-1.0.0/src/ttstart/start.wav
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 03:22:21.834377 metarace-ttstart-1.0.1/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1063 2022-10-16 22:46:07.000000 metarace-ttstart-1.0.1/LICENSE
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       30 2022-10-17 01:40:59.000000 metarace-ttstart-1.0.1/MANIFEST.in
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     3169 2023-06-28 03:22:21.834377 metarace-ttstart-1.0.1/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     2664 2023-06-28 03:03:24.000000 metarace-ttstart-1.0.1/README.md
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      687 2023-06-28 01:19:59.000000 metarace-ttstart-1.0.1/pyproject.toml
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 03:22:21.834377 metarace-ttstart-1.0.1/setup.cfg
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 03:22:21.830377 metarace-ttstart-1.0.1/src/
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 03:22:21.830377 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     3169 2023-06-28 03:22:21.000000 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      380 2023-06-28 03:22:21.000000 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/SOURCES.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 03:22:21.000000 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/dependency_links.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       41 2023-06-28 03:22:21.000000 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/entry_points.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       16 2023-06-28 03:22:21.000000 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/requires.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        8 2023-06-28 03:22:21.000000 metarace-ttstart-1.0.1/src/metarace_ttstart.egg-info/top_level.txt
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 03:22:21.830377 metarace-ttstart-1.0.1/src/ttstart/
+-rwxr-xr-x   0 ndf       (1000) ndf       (1000)    22884 2023-06-28 01:16:52.000000 metarace-ttstart-1.0.1/src/ttstart/__init__.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       79 2022-10-17 01:36:19.000000 metarace-ttstart-1.0.1/src/ttstart/__main__.py
+-rw-------   0 ndf       (1000) ndf       (1000)  1058444 2022-10-13 09:23:49.000000 metarace-ttstart-1.0.1/src/ttstart/start.wav
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `metarace-ttstart-1.0.0/LICENSE` & `metarace-ttstart-1.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `metarace-ttstart-1.0.0/PKG-INFO` & `metarace-ttstart-1.0.1/README.md`

 * *Files 13% similar despite different names*

```diff
@@ -1,23 +1,7 @@
-Metadata-Version: 2.1
-Name: metarace-ttstart
-Version: 1.0.0
-Summary: Time Trial Start Console
-Author-email: Nathan Fraser <ndf-zz@6-v.org>
-License: MIT
-Project-URL: homepage, https://github.com/ndf-zz/metarace-ttstart
-Keywords: TT,start
-Classifier: Development Status :: 3 - Alpha
-Classifier: Topic :: Other/Nonlisted Topic
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 # metarace-ttstart
 
 Time trial start console application. Includes time of day,
 rider number, rider name, a 30 second count-down and audible
 start beeps.
 
 ![ttstart screenshot](screenshot.png "ttstart")
@@ -30,16 +14,15 @@
 Configuration is via metarace sysconf section 'ttstart' with the
 following keys:
 
 key           | (type) description [default]
 ---           | ---
 topic         | (string) telegraph topic for start list updates [startlist]
 fullscreen    | (boolean) run application fullscreen after initialisation
-backlightdev  | (string) sysfs path to backlight device [null] (1)
-              |          eg: /sys/class/backlight/acpi_video0
+backlightdev  | (string) sysfs path to backlight device [null] (1) eg: /sys/class/backlight/acpi_video0
 backlightlow  | (float) dimmed backlight level between starters [0.25]
 backlighthigh | (float) backlight level during countdown [1.0]
 startlist     | (string) filename for a csv startlist file [startlist.csv]
 syncthresh    | (float) maximum allowed audio de-sync in seconds [0.12] (2)
 
 Notes:
 
@@ -62,28 +45,39 @@
 For example:
 
 	[["9h15:00","","","[Event Start]"], ["9h16:00","1","","First RIDER"]]
 
 
 ## Requirements
 
+   - Python >= 3.9
+   - Gtk >= 3.0
+   - metarace >= 2.1.1
    - tex-gyre fonts
    - gstreamer alsa plugins
-   - metarace >= 2.0
 
 Note: Some 32 bit systems (notably Intel Atom Toughbooks) will not
 play audio with the default Debian desktop installation.
 The workaround is to remove pulseaudio and use alsa directly:
 
-	# apt remove 'pulseaudio*'
+	$ sudo apt remove 'pulseaudio*'
 
 ## Installation
 
-[Install metarace](https://github.com/ndf-zz/metarace#installation)
-and the required system packages:
+### Debian 11+
+
+Install system requirements for ttstart and metarace with apt:
+
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-gtk-3.0 gir1.2-rsvg-2.0 gir1.2-pango-1.0 gir1.2-gstreamer-1.0 gstreamer1.0-alsa tex-gyre
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
+
+If not already created, add a virtualenv for metarace packages:
 
-	# apt install tex-gyre gir1.2-gtk-3.0 gir1.2-gstreamer-1.0 gstreamer1.0-alsa
+	$ mkdir -p ~/Documents/metarace
+	$ python3 -m venv --system-site-packages ~/Documents/metarace/venv
 
-Then install ttstart using pip:
+Activate the virtualenv and install ttstart with pip:
 
-	$ pip3 install metarace-ttstart
+	$ source ~/Documents/metarace/venv/bin/activate
+	(venv) $ pip3 install metarace-ttstart
```

### Comparing `metarace-ttstart-1.0.0/pyproject.toml` & `metarace-ttstart-1.0.1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,30 +1,30 @@
 [build-system]
 requires = ["setuptools>=62"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "metarace-ttstart"
-version = "1.0.0"
+version = "1.0.1"
 description = "Time Trial Start Console"
 readme = "README.md"
-requires-python = ">=3.6"
+requires-python = ">=3.9"
 license = {text = "MIT"}
 keywords = ["TT", "start"]
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
-    "metarace",
+    "metarace>=2.1.1",
 ]
 [project.urls]
 homepage = "https://github.com/ndf-zz/metarace-ttstart"
 
 [project.scripts]
 ttstart = "ttstart:main"
```

### Comparing `metarace-ttstart-1.0.0/src/metarace_ttstart.egg-info/PKG-INFO` & `metarace-ttstart-1.0.1/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 Metadata-Version: 2.1
 Name: metarace-ttstart
-Version: 1.0.0
+Version: 1.0.1
 Summary: Time Trial Start Console
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace-ttstart
 Keywords: TT,start
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
-Requires-Python: >=3.6
+Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # metarace-ttstart
 
 Time trial start console application. Includes time of day,
 rider number, rider name, a 30 second count-down and audible
@@ -30,16 +30,15 @@
 Configuration is via metarace sysconf section 'ttstart' with the
 following keys:
 
 key           | (type) description [default]
 ---           | ---
 topic         | (string) telegraph topic for start list updates [startlist]
 fullscreen    | (boolean) run application fullscreen after initialisation
-backlightdev  | (string) sysfs path to backlight device [null] (1)
-              |          eg: /sys/class/backlight/acpi_video0
+backlightdev  | (string) sysfs path to backlight device [null] (1) eg: /sys/class/backlight/acpi_video0
 backlightlow  | (float) dimmed backlight level between starters [0.25]
 backlighthigh | (float) backlight level during countdown [1.0]
 startlist     | (string) filename for a csv startlist file [startlist.csv]
 syncthresh    | (float) maximum allowed audio de-sync in seconds [0.12] (2)
 
 Notes:
 
@@ -62,28 +61,39 @@
 For example:
 
 	[["9h15:00","","","[Event Start]"], ["9h16:00","1","","First RIDER"]]
 
 
 ## Requirements
 
+   - Python >= 3.9
+   - Gtk >= 3.0
+   - metarace >= 2.1.1
    - tex-gyre fonts
    - gstreamer alsa plugins
-   - metarace >= 2.0
 
 Note: Some 32 bit systems (notably Intel Atom Toughbooks) will not
 play audio with the default Debian desktop installation.
 The workaround is to remove pulseaudio and use alsa directly:
 
-	# apt remove 'pulseaudio*'
+	$ sudo apt remove 'pulseaudio*'
 
 ## Installation
 
-[Install metarace](https://github.com/ndf-zz/metarace#installation)
-and the required system packages:
+### Debian 11+
 
-	# apt install tex-gyre gir1.2-gtk-3.0 gir1.2-gstreamer-1.0 gstreamer1.0-alsa
+Install system requirements for ttstart and metarace with apt:
 
-Then install ttstart using pip:
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-gtk-3.0 gir1.2-rsvg-2.0 gir1.2-pango-1.0 gir1.2-gstreamer-1.0 gstreamer1.0-alsa tex-gyre
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
 
-	$ pip3 install metarace-ttstart
+If not already created, add a virtualenv for metarace packages:
+
+	$ mkdir -p ~/Documents/metarace
+	$ python3 -m venv --system-site-packages ~/Documents/metarace/venv
+
+Activate the virtualenv and install ttstart with pip:
+
+	$ source ~/Documents/metarace/venv/bin/activate
+	(venv) $ pip3 install metarace-ttstart
```

### Comparing `metarace-ttstart-1.0.0/src/ttstart/__init__.py` & `metarace-ttstart-1.0.1/src/ttstart/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -36,15 +36,15 @@
 import gi
 import logging
 import metarace
 import csv
 import os
 import cairo
 import json
-from importlib_resources import files
+from importlib.resources import files
 from metarace import telegraph
 from metarace import tod
 from metarace import jsonconfig
 
 gi.require_version("GLib", "2.0")
 from gi.repository import GLib
 
@@ -59,14 +59,15 @@
 
 gi.require_version('PangoCairo', '1.0')
 from gi.repository import PangoCairo
 
 gi.require_version('Gst', '1.0')
 from gi.repository import Gst
 
+VERSION = '1.0.1'
 _DEFTOPIC = 'startlist'
 _DEFAUDIOSYNCTHRESH = 0.12
 _RESOURCE_PKG = 'ttstart'
 _SOUNDFILE = 'start.wav'
 _STARTLIST = 'startlist.csv'
 _TIMEFONT = 'TeXGyreHerosCn Bold '
 _COUNTERFONT = 'TeXGyreHerosCn Bold '
@@ -619,14 +620,19 @@
                 pass
         except Exception as e:
             _log.error('%s decoding json object: %s', e.__class__.__name__, e)
 
 
 def main():
     """Run the TT start application"""
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
     Gst.init()
```

### Comparing `metarace-ttstart-1.0.0/src/ttstart/start.wav` & `metarace-ttstart-1.0.1/src/ttstart/start.wav`

 * *Files identical despite different names*


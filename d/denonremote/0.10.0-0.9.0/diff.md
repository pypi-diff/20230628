# Comparing `tmp/denonremote-0.10.0.tar.gz` & `tmp/denonremote-0.9.0.tar.gz`

## Comparing `denonremote-0.10.0.tar` & `denonremote-0.9.0.tar`

### file list

```diff
@@ -1,38 +1,36 @@
--rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 denonremote-0.10.0/.gitattributes
--rw-r--r--   0        0        0    10558 2020-02-02 00:00:00.000000 denonremote-0.10.0/buildozer.spec
--rw-r--r--   0        0        0     1753 2020-02-02 00:00:00.000000 denonremote-0.10.0/denonremote.spec
--rw-r--r--   0        0        0    34542 2020-02-02 00:00:00.000000 denonremote-0.10.0/icon.ico
--rw-r--r--   0        0        0      418 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/__about__.py
--rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/__init__.py
--rw-r--r--   0        0        0     5563 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/__main__.py
--rw-r--r--   0        0        0      700 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/cli.py
--rw-r--r--   0        0        0    10285 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/denonremote.kv
--rw-r--r--   0        0        0    23776 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/gui.py
--rw-r--r--   0        0        0      214 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/denon/__init__.py
--rw-r--r--   0        0        0     7011 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/denon/communication.py
--rw-r--r--   0        0        0    26275 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/denon/dn500av.py
--rw-r--r--   0        0        0  3303588 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/fonts/FreeSerif.ttf
--rw-r--r--   0        0        0   126520 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/fonts/RobotoMono-Bold.ttf
--rw-r--r--   0        0        0   135832 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/fonts/RobotoMono-BoldItalic.ttf
--rw-r--r--   0        0        0   138352 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/fonts/RobotoMono-Italic.ttf
--rw-r--r--   0        0        0   125588 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/fonts/RobotoMono-Regular.ttf
--rw-r--r--   0        0        0     2256 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/fonts/Unicode_IEC_symbol.ttf
--rw-r--r--   0        0        0    23631 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/images/DN-500AV.png
--rw-r--r--   0        0        0    26402 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/images/icon.png
--rw-r--r--   0        0        0      255 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/communication.json
--rw-r--r--   0        0        0      331 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/source1.json
--rw-r--r--   0        0        0      331 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/source2.json
--rw-r--r--   0        0        0      331 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/source3.json
--rw-r--r--   0        0        0      333 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/source4.json
--rw-r--r--   0        0        0      333 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/source5.json
--rw-r--r--   0        0        0      333 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/source6.json
--rw-r--r--   0        0        0      618 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/volume.json
--rw-r--r--   0        0        0      544 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/volume_display.json
--rw-r--r--   0        0        0      189 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/settings/window.json
--rw-r--r--   0        0        0       46 2020-02-02 00:00:00.000000 denonremote-0.10.0/src/denonremote/__build__.py
--rw-r--r--   0        0        0      229 2020-02-02 00:00:00.000000 denonremote-0.10.0/.gitignore
--rw-r--r--   0        0        0    35802 2020-02-02 00:00:00.000000 denonremote-0.10.0/LICENSE
--rw-r--r--   0        0        0     9751 2020-02-02 00:00:00.000000 denonremote-0.10.0/README.md
--rw-r--r--   0        0        0     1186 2020-02-02 00:00:00.000000 denonremote-0.10.0/hatch_build.py
--rw-r--r--   0        0        0     4052 2020-02-02 00:00:00.000000 denonremote-0.10.0/pyproject.toml
--rw-r--r--   0        0        0    51890 2020-02-02 00:00:00.000000 denonremote-0.10.0/PKG-INFO
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 denonremote-0.9.0/.gitattributes
+-rw-r--r--   0        0        0    10558 2020-02-02 00:00:00.000000 denonremote-0.9.0/buildozer.spec
+-rw-r--r--   0        0        0     2162 2020-02-02 00:00:00.000000 denonremote-0.9.0/denonremote.spec
+-rw-r--r--   0        0        0    34542 2020-02-02 00:00:00.000000 denonremote-0.9.0/icon.ico
+-rw-r--r--   0        0        0      433 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/__about__.py
+-rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/__init__.py
+-rw-r--r--   0        0        0     5615 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/__main__.py
+-rw-r--r--   0        0        0      700 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/cli.py
+-rw-r--r--   0        0        0    10285 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/denonremote.kv
+-rw-r--r--   0        0        0    23265 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/gui.py
+-rw-r--r--   0        0        0      214 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/denon/__init__.py
+-rw-r--r--   0        0        0     6457 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/denon/communication.py
+-rw-r--r--   0        0        0    26275 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/denon/dn500av.py
+-rw-r--r--   0        0        0  3303588 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/fonts/FreeSerif.ttf
+-rw-r--r--   0        0        0   126520 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/fonts/RobotoMono-Bold.ttf
+-rw-r--r--   0        0        0   135832 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/fonts/RobotoMono-BoldItalic.ttf
+-rw-r--r--   0        0        0   138352 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/fonts/RobotoMono-Italic.ttf
+-rw-r--r--   0        0        0   125588 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/fonts/RobotoMono-Regular.ttf
+-rw-r--r--   0        0        0     2256 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/fonts/Unicode_IEC_symbol.ttf
+-rw-r--r--   0        0        0    23631 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/images/DN-500AV.png
+-rw-r--r--   0        0        0    26402 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/images/icon.png
+-rw-r--r--   0        0        0      255 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/communication.json
+-rw-r--r--   0        0        0      331 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/source1.json
+-rw-r--r--   0        0        0      331 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/source2.json
+-rw-r--r--   0        0        0      331 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/source3.json
+-rw-r--r--   0        0        0      333 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/source4.json
+-rw-r--r--   0        0        0      333 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/source5.json
+-rw-r--r--   0        0        0      333 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/source6.json
+-rw-r--r--   0        0        0      618 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/volume.json
+-rw-r--r--   0        0        0      544 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/volume_display.json
+-rw-r--r--   0        0        0      189 2020-02-02 00:00:00.000000 denonremote-0.9.0/src/denonremote/settings/window.json
+-rw-r--r--   0        0        0      138 2020-02-02 00:00:00.000000 denonremote-0.9.0/.gitignore
+-rw-r--r--   0        0        0    35802 2020-02-02 00:00:00.000000 denonremote-0.9.0/LICENSE
+-rw-r--r--   0        0        0     6486 2020-02-02 00:00:00.000000 denonremote-0.9.0/README.md
+-rw-r--r--   0        0        0     3602 2020-02-02 00:00:00.000000 denonremote-0.9.0/pyproject.toml
+-rw-r--r--   0        0        0    48621 2020-02-02 00:00:00.000000 denonremote-0.9.0/PKG-INFO
```

### Comparing `denonremote-0.10.0/buildozer.spec` & `denonremote-0.9.0/buildozer.spec`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/icon.ico` & `denonremote-0.9.0/icon.ico`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/__main__.py` & `denonremote-0.9.0/src/denonremote/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,46 +1,34 @@
 # This Python file uses the following encoding: utf-8
 #
-# SPDX-FileCopyrightText: 2021-2023 Raphaël Doursenaud <rdoursenaud@free.fr>
+# SPDX-FileCopyrightText: 2021-2022 Raphaël Doursenaud <rdoursenaud@free.fr>
 #
 # SPDX-License-Identifier: GPL-3.0-or-later
 
 """
 Denon DN-500AV Remote
 
 @author Raphael Doursenaud <rdoursenaud@gmail.com>
 """
 
 import argparse
-import importlib.resources
 import logging
 import os
 import sys
 
 import PIL.Image
-import kivy.resources
 import pystray
 import win32api
 import win32event
 from winerror import ERROR_ALREADY_EXISTS
 
-import denonremote
 from denonremote.__about__ import __TITLE__
 
 logger = logging.getLogger()
 
-for path in ['fonts', 'images', 'settings']:
-    if hasattr(sys, '_MEIPASS'):
-        # noinspection PyProtectedMember
-        kivy.resources.resource_add_path(os.path.join(sys._MEIPASS, path))
-    else:
-        kivy.resources.resource_add_path(
-            importlib.resources.files(denonremote).joinpath(path)
-        )
-
 
 def configure(args: argparse.Namespace) -> None:
     import kivy.config
 
     # App specific configuration
     # FIXME: use same implementation as Kivy to avoid issues
     kivy.config.Config.read(os.path.expanduser('~/.denonremote.ini'))
@@ -132,21 +120,34 @@
 
 def systray_quit(icon: pystray.Icon, _: pystray.MenuItem) -> None:
     import kivy.clock
     kivy.clock.Clock.schedule_once(kivy.app.App.get_running_app().stop)
     icon.stop()
 
 
+# FIXME: use kivy.resources.resource_find instead
+def resource_path(relative_path: str) -> os.path:
+    """ Get absolute path to resource, works for dev and for PyInstaller """
+    if hasattr(sys, '_MEIPASS'):
+        # PyInstaller creates a temp folder and stores path in _MEIPASS
+        # noinspection PyProtectedMember
+        base_path = sys._MEIPASS
+    else:
+        base_path = os.getcwd()
+
+    return os.path.join(base_path, relative_path)
+
+
 def run_gui_from_systray() -> None:
     default_menu_item = pystray.MenuItem(__TITLE__, systray_clicked, default=True, visible=True)
     settings_menu_item = pystray.MenuItem('Settings', systray_settings)
     quit_menu_item = pystray.MenuItem('Quit', systray_quit)
     systray_menu = pystray.Menu(default_menu_item, settings_menu_item, quit_menu_item)
     systray = pystray.Icon(__TITLE__, menu=systray_menu)
-    systray.icon = PIL.Image.open(kivy.resources.resource_find(r'icon.png'))
+    systray.icon = PIL.Image.open(resource_path(r'images/icon.png'))
     systray.run(setup=run_gui)
 
 
 def run(args: argparse.Namespace) -> None:
     if False:  # FIXME: implement CLI commands
         run_cli()
     elif args.no_systray:
```

### Comparing `denonremote-0.10.0/src/denonremote/cli.py` & `denonremote-0.9.0/src/denonremote/cli.py`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/denonremote.kv` & `denonremote-0.9.0/src/denonremote/denonremote.kv`

 * *Files 0% similar despite different names*

```diff
@@ -281,15 +281,15 @@
 
             Label:
                 id: brand_label
                 text: "EMA Tech."
 
             Label:
                 id: copyright_label
-                text: "(c) 2021-2023 Raphaël Doursenaud"
+                text: "(c) 2021-2022 Raphaël Doursenaud"
                 font_size: 12
 
             Label:
                 id: version_label
                 text: f"v{__version__} {system()} (Built on {__build_date__})"
                 font_size: 10
```

### Comparing `denonremote-0.10.0/src/denonremote/gui.py` & `denonremote-0.9.0/src/denonremote/gui.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,20 +3,18 @@
 # SPDX-FileCopyrightText: 2021-2022 Raphaël Doursenaud <rdoursenaud@free.fr>
 #
 # SPDX-License-Identifier: GPL-3.0-or-later
 
 """
 Denon Remote GUI.
 """
-import importlib.resources
+
 import os
 import sys
 
-import denonremote
-
 # Don't pass CLI arguments to Kivy.
 # Must be set before importing Kivy.
 os.environ['KIVY_NO_ARGS'] = '1'
 
 import configparser
 import kivy.app
 import kivy.clock
@@ -33,15 +31,14 @@
 import win32con
 
 # Must be called before importing or using the reactor
 from kivy.support import install_twisted_reactor
 
 install_twisted_reactor()
 import twisted.internet
-import twisted.internet.error
 import twisted.internet.tcp
 import twisted.python.failure
 
 from denonremote.__about__ import __TITLE__
 from denonremote.denon.communication import DenonClientGUIFactory
 from kivy.animation import Animation
 from kivy.uix.togglebutton import ToggleButton
@@ -53,17 +50,15 @@
 
 # PyInstaller data support
 for path in ['fonts', 'images', 'settings']:
     if hasattr(sys, '_MEIPASS'):
         # noinspection PyProtectedMember
         kivy.resources.resource_add_path(os.path.join(sys._MEIPASS, path))
     else:
-        kivy.resources.resource_add_path(
-            importlib.resources.files(denonremote).joinpath(path)
-        )
+        kivy.resources.resource_add_path(path)
 
 _BACKOFF = .05
 
 WIDTH = 800
 HEIGHT = 600
 SMALL_HEIGHT = 60
 
@@ -116,85 +111,62 @@
 
     settings_cls: kivy.uix.settings.Settings = kivy.uix.settings.SettingsWithSidebar
 
     maximum_volume = '  0.0dB'
 
     def build_config(self, config: configparser.ConfigParser) -> None:
         config.adddefaultsection('denonremote')
-        config.setdefaults(
-            'denonremote', {
-                'debug': False,
-                'receiver_ip': '192.168.x.y',
-                'receiver_port': TELNET_PORT,
-                'always_on_top': True,
-                'reference_level': '-20',
-                # SMPTE RP200:2012 & Katz metering system also equivalent to EBU 83dbSPLC@-20dBFS
-                'reference_spl': '83',
-                'reference_volume': '-18',  # The best alignment level with my current setup (Dynaudio BM5A)
-                'vol_preset_1': '-30.0dB',  # My preferred leisure level
-                'vol_preset_2': '-26.0dB',  # K-12
-                # -25.0dB  # EBU R 128
-                'vol_preset_3': '-24.0dB',  # K-14 / Dolby Home Cinema
-                'vol_preset_4': '-18.0dB',  # SMPTE/EBU/Dolby theater (Reference volume)
-                'fav_src_1_code': 'GAME',
-                'fav_src_1_label': "Computer HDMI",
-                'fav_src_2_code': 'CD',
-                'fav_src_2_label': "Pro Analog",
-                'fav_src_3_code': 'TV',
-                'fav_src_3_label': "Pro Digital",
-                'fav_src_4_code': '',
-                'fav_src_4_label': "",
-                'fav_src_5_code': '',
-                'fav_src_5_label': "",
-                'fav_src_6_code': '',
-                'fav_src_6_label': "",
-            }
-        )
+        config.setdefaults('denonremote', {
+            'debug': False,
+            'receiver_ip': '192.168.x.y',
+            'receiver_port': TELNET_PORT,
+            'always_on_top': True,
+            'reference_level': '-20',  # SMPTE RP200:2012 & Katz metering system also equivalent to EBU 83dbSPLC@-20dBFS
+            'reference_spl': '83',
+            'reference_volume': '-18',  # The best alignment level with my current setup (Dynaudio BM5A)
+            'vol_preset_1': '-30.0dB',  # My preferred leisure level
+            'vol_preset_2': '-26.0dB',  # K-12
+            # -25.0dB  # EBU R 128
+            'vol_preset_3': '-24.0dB',  # K-14 / Dolby Home Cinema
+            'vol_preset_4': '-18.0dB',  # SMPTE/EBU/Dolby theater (Reference volume)
+            'fav_src_1_code': 'GAME',
+            'fav_src_1_label': "Computer HDMI",
+            'fav_src_2_code': 'CD',
+            'fav_src_2_label': "Pro Analog",
+            'fav_src_3_code': 'TV',
+            'fav_src_3_label': "Pro Digital",
+            'fav_src_4_code': '',
+            'fav_src_4_label': "",
+            'fav_src_5_code': '',
+            'fav_src_5_label': "",
+            'fav_src_6_code': '',
+            'fav_src_6_label': "",
+        })
 
     def build_settings(self, settings: kivy.uix.settings.Settings) -> None:
-        settings.add_json_panel(
-            "Communication", self.config,
-            filename=kivy.resources.resource_find('communication.json')
-        )
-        settings.add_json_panel(
-            "Window", self.config,
-            filename=kivy.resources.resource_find('window.json')
-        )
-        settings.add_json_panel(
-            "Volume display", self.config,
-            filename=kivy.resources.resource_find('volume_display.json')
-        )
-        settings.add_json_panel(
-            "Volume presets", self.config,
-            filename=kivy.resources.resource_find('volume.json')
-        )
-        settings.add_json_panel(
-            "Favorite source 1", self.config,
-            filename=kivy.resources.resource_find('source1.json')
-        )
-        settings.add_json_panel(
-            "Favorite source 2", self.config,
-            filename=kivy.resources.resource_find('source2.json')
-        )
-        settings.add_json_panel(
-            "Favorite source 3", self.config,
-            filename=kivy.resources.resource_find('source3.json')
-        )
-        settings.add_json_panel(
-            "Favorite source 4", self.config,
-            filename=kivy.resources.resource_find('source4.json')
-        )
-        settings.add_json_panel(
-            "Favorite source 5", self.config,
-            filename=kivy.resources.resource_find('source5.json')
-        )
-        settings.add_json_panel(
-            "Favorite source 6", self.config,
-            filename=kivy.resources.resource_find('source6.json')
-        )
+        settings.add_json_panel("Communication", self.config,
+                                filename=kivy.resources.resource_find('communication.json'))
+        settings.add_json_panel("Window", self.config,
+                                filename=kivy.resources.resource_find('window.json'))
+        settings.add_json_panel("Volume display", self.config,
+                                filename=kivy.resources.resource_find('volume_display.json'))
+        settings.add_json_panel("Volume presets", self.config,
+                                filename=kivy.resources.resource_find('volume.json'))
+        settings.add_json_panel("Favorite source 1", self.config,
+                                filename=kivy.resources.resource_find('source1.json'))
+        settings.add_json_panel("Favorite source 2", self.config,
+                                filename=kivy.resources.resource_find('source2.json'))
+        settings.add_json_panel("Favorite source 3", self.config,
+                                filename=kivy.resources.resource_find('source3.json'))
+        settings.add_json_panel("Favorite source 4", self.config,
+                                filename=kivy.resources.resource_find('source4.json'))
+        settings.add_json_panel("Favorite source 5", self.config,
+                                filename=kivy.resources.resource_find('source5.json'))
+        settings.add_json_panel("Favorite source 6", self.config,
+                                filename=kivy.resources.resource_find('source6.json'))
 
     def get_application_config(self, _: str = '%(appdir)s/%(appname)s.ini') -> None:
         """
         Store config into user directory
         """
         return super().get_application_config('~/.%(appname)s.ini')
 
@@ -241,16 +213,15 @@
         self.print_debug('Connecting to ' + self.config.get('denonremote', 'receiver_ip') + '...', True)
 
         client_factory = DenonClientGUIFactory(self)
         self.connector = twisted.internet.reactor.connectTCP(
             host=self.config.get('denonremote', 'receiver_ip'),
             port=self.config.getint('denonremote', 'receiver_port'),
             factory=client_factory,
-            timeout=1
-        )
+            timeout=1)
 
     def _disconnect(self) -> None:
         if self.connector is not None:
             self.print_debug('Disconnecting', True)
             self.connector.disconnect()
             self.connector = None
 
@@ -258,33 +229,29 @@
         pass
 
     def on_start(self) -> None:
         """
         Fired by Kivy on application startup
         :return:
         """
+
+        print(self.root)
+
         # FIXME: Windows only ATM.
         if self.config.getboolean('denonremote', 'always_on_top'):
             KivyOnTop.register_topmost(kivy.core.window.Window, __TITLE__)
-            kivy.core.window.Window.bind(
-                on_stop=lambda *args, w=kivy.core.window.Window,
-                               t=__TITLE__: KivyOnTop.unregister_topmost(w, t)
-            )
+            kivy.core.window.Window.bind(on_stop=
+                                         lambda *args, w=kivy.core.window.Window,
+                                                t=__TITLE__: KivyOnTop.unregister_topmost(w, t))
 
         # Don’t steal focus
-        win32gui.SetWindowLong(
-            KivyOnTop.find_hwnd(__TITLE__),
-            win32con.GWL_EXSTYLE,
-            win32con.WS_EX_NOACTIVATE,
-        )
+        win32gui.SetWindowLong(KivyOnTop.find_hwnd(__TITLE__), win32con.GWL_EXSTYLE, win32con.WS_EX_NOACTIVATE)
 
         # Raise when mouse enters
-        kivy.core.window.Window.bind(
-            on_cursor_enter=lambda *_: kivy.core.window.Window.raise_window()
-        )
+        kivy.core.window.Window.bind(on_cursor_enter=lambda *_: kivy.core.window.Window.raise_window())
 
         # Custom titlebar
         kivy.core.window.Window.custom_titlebar = True
         kivy.core.window.Window.set_custom_titlebar(self.root.ids.header)
 
         if self.systray is not None:
             self.systray.visible = True
@@ -345,36 +312,31 @@
         self.client.get_source()
 
         self.close_settings()
 
         self.root.ids.power.disabled = False
         self.root.ids.main.disabled = False
 
-    def on_connection_failed(
-            self,
-            connector: twisted.internet.tcp.Connector,
-            reason: twisted.python.failure.Failure,
-    ) -> None:
+    def on_connection_failed(self, connector: twisted.internet.tcp.Connector, reason: twisted.python.failure.Failure
+                             ) -> None:
         if self.connector is connector:
-            logger.debug(f"Connection failed: {reason.value}")
+            logger.debug(f"Connection failed: {reason}")
             self.print_debug("Connection to receiver failed!")
             self.client = None
+            # TODO: open error popup?
             self.root.ids.power.disabled = True
             self.root.ids.main.disabled = True
             self.open_settings()
 
         self._reconnect()
 
-    def on_connection_lost(
-            self,
-            connector: twisted.internet.tcp.Connector,
-            reason: twisted.python.failure.Failure,
-    ) -> None:
+    def on_connection_lost(self, connector: twisted.internet.tcp.Connector, reason: twisted.python.failure.Failure
+                           ) -> None:
         if self.connector is connector:
-            logger.debug(f"Connection lost: {reason.value}")
+            logger.debug(f"Connection lost: {reason}")
             self.print_debug("Connection to receiver lost!")
             self.client = None
             self.root.ids.power.disabled = True
             self.root.ids.main.disabled = True
 
         self._reconnect()
 
@@ -396,38 +358,27 @@
     @kivy.clock.mainthread
     def hide(self, window: kivy.core.window.Window = None) -> None:
         if window is None:
             window = self.root_window
         window.hide()
         self.hidden = True
 
-    def hide_on_close(
-            self,
-            window: kivy.core.window.Window,
-            source: str = None,
-    ) -> True:
+    def hide_on_close(self, window: kivy.core.window.Window, source: str = None) -> True:
         logger.debug(f"Hide from {source}")
         self.hide(window)
         return True  # Keeps the application alive instead of stopping
 
     def enable_keyboard_shortcuts(self) -> None:
         kivy.core.window.Window.bind(on_keyboard=self.on_keyboard)
 
     def disable_keyboard_shortcuts(self) -> None:
         kivy.core.window.Window.unbind(on_keyboard=self.on_keyboard)
 
-    def on_keyboard(
-            self,
-            _: kivy.core.window.Window,
-            key: str,
-            scancode: int = None,
-            codepoint: str = None,
-            modifier: str = None,
-            **__,
-    ) -> None:
+    def on_keyboard(self, _: kivy.core.window.Window,
+                    key: str, scancode: int = None, codepoint: str = None, modifier: str = None, **__) -> None:
         """
         Handle keyboard shortcuts
         """
         logger.debug(f"key: {key}, scancode: {scancode}, codepoint: {codepoint}, modifier: {modifier}")
         if codepoint == 'm':
             if not self.root.ids.volume_mute.disabled:
                 self.root.ids.volume_mute.trigger_action()
@@ -512,28 +463,23 @@
             self.root.ids.volume_plus.disabled = False
 
     def _compute_spl_text(self, text: str = "", ref_level: int = -18) -> (str, str):
         # FIXME: Handle Absolute mode
         # Relative mode computation
         volume = float('-inf') if text == '---.-dB' else float(text.replace(' ', '')[:-2])  # Strip "dB"
         volume_delta = volume - float(
-            self.config.get('denonremote', 'reference_volume')
-        )  # compute delta with reference volume
+            self.config.get('denonremote', 'reference_volume'))  # compute delta with reference volume
         if volume == float('-inf'):
             spl = volume
         else:
-            spl = int(
-                round(
-                    float(self.config.get('denonremote', 'reference_spl')) + volume_delta
-                )
-            )  # apply delta to reference SPL
+            spl = int(round(
+                float(self.config.get('denonremote', 'reference_spl')) + volume_delta))  # apply delta to reference SPL
         # Reference mode handling
         ref_delta = ref_level - int(
-            self.config.get('denonremote', 'reference_level')
-        )  # compute delta with reference level
+            self.config.get('denonremote', 'reference_level'))  # compute delta with reference level
         spl = spl + ref_delta
         if spl == float('-inf'):
             spl = 0
         spl_text = f"{spl:d} dB SPL"  # format string with computed SPL and reference level mode
         ref_text = f"@ {ref_level:d} dBFS"
         text = (spl_text, ref_text)
         return text
```

### Comparing `denonremote-0.10.0/src/denonremote/denon/communication.py` & `denonremote-0.9.0/src/denonremote/denon/communication.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,101 +1,84 @@
 # This Python file uses the following encoding: utf-8
 #
-# SPDX-FileCopyrightText: 2021-2023 Raphaël Doursenaud <rdoursenaud@free.fr>
+# SPDX-FileCopyrightText: 2021-2022 Raphaël Doursenaud <rdoursenaud@free.fr>
 #
 # SPDX-License-Identifier: GPL-3.0-or-later
 
 import logging
-from typing import TYPE_CHECKING
 
 import twisted.internet.interfaces
 import twisted.python.failure
-from twisted.internet import reactor, task
+from twisted.internet import task, reactor
 from twisted.internet.protocol import ClientFactory
 from twisted.protocols.basic import LineOnlyReceiver
 from twisted.protocols.policies import TimeoutMixin
 
-from .dn500av import DN500AVFormat, DN500AVMessage
-
-if TYPE_CHECKING:
-    from denonremote.gui import DenonRemoteApp
+from .dn500av import DN500AVMessage, DN500AVFormat
 
 logger = logging.getLogger(__name__)
 
 
 # TODO: Implement Serial ?
 # See: https://twistedmatrix.com/documents/15.4.0/api/twisted.internet.serialport.SerialPort.html
 
 
 class DenonProtocol(LineOnlyReceiver, TimeoutMixin):
     # From DN-500 manual (DN-500AVEM_ENG_CD-ROM_v00.pdf) page 91 (97 in PDF form)
-    MAX_LENGTH: int = 135
-    DELAY: float = .2
+    MAX_LENGTH = 135
+    DELAY = 0.04
     """
     Delay between messages in seconds.
-    The documentation requires 200 ms.
-    20 ms seems safe.
+    The documentation requires 200 ms. 40 ms seems safe.
+    """
+    TIMEOUT = .2
+    """
+    Requests shall time out if no reply is received in under 200 ms.
     """
-    DEFAULT_TIMEOUT: float = .2
+    EXTENDED_TIMEOUT = 5
     """
     Changing sources takes way more than 200ms.
     Let's bump this case to 5 seconds to prevent spurious disconnections.
     """
-    delimiter: bytes
-    factory: 'DenonClientFactory'
-    ongoing_calls: int
-    timeOut: float
-    transport: twisted.internet.interfaces.ITCPTransport
-
-    def __init__(self):
-        self.delimiter = b'\r'
-        self.ongoing_calls = 0  # Delay handling.
+    delimiter = b'\r'
+    ongoing_calls = 0  # Delay handling.
 
     def connectionMade(self) -> None:
         logger.debug("Connection made")
         if self.factory.gui:
             self.factory.app.on_connection(self)
 
     def timeoutConnection(self) -> None:
         logger.debug("Connection timed out")
         self.transport.abortConnection()
         if self.factory.gui:
             self.factory.app.on_timeout()
 
-    def sendLine(self, line: bytes) -> task.Deferred | None:
-        deferred = None
-        line_len = len(line)
-        if line_len > self.MAX_LENGTH:
-            logger.warning(f'Line too long (>{self.MAX_LENGTH}): {line_len}')
-        if b'?' not in line:
-            logger.debug(f"Sending line: {line.decode('ASCII')}")
-            super().sendLine(line)
-        else:
+    def sendLine(self, line: bytes) -> task.Deferred:
+        if b'?' in line:
             # A request is made. We need to delay the next calls
             self.ongoing_calls += 1
             logger.debug(f'Ongoing calls for delay: {self.ongoing_calls}')
-            delay = 0  # Send now
-            if self.ongoing_calls > 0:
-                delay = self.DELAY * (self.ongoing_calls - 1)  # Send after other messages
-            logger.debug(f"Will send line: {line} in {delay} seconds")
-            deferred = task.deferLater(
-                reactor,
-                delay=delay,
-                callable=self.sendLineWithTimeout,
-                line=line,
-            )
-        return deferred
+        delay = 0  # Send now
+        if self.ongoing_calls > 0:
+            delay = self.DELAY * (self.ongoing_calls - 1)  # Send after other messages
+        logger.debug(f"Will send line: {line} in {delay} seconds")
+        line_len = len(line)
+        if line_len > self.MAX_LENGTH:
+            logger.warning(f'Line too long (>{self.MAX_LENGTH}): {line_len}')
+        return task.deferLater(reactor, delay=delay,
+                               callable=self.sendLineWithTimeout, line=line)
 
     # noinspection PyPep8Naming
     def sendLineWithTimeout(self, line: bytes) -> None:
-        timeout = self.DEFAULT_TIMEOUT
-        if self.timeOut:
-            timeout += self.timeOut
+        timeout = self.TIMEOUT
+        if b'SI' in line:
+            timeout = self.EXTENDED_TIMEOUT
         self.setTimeout(timeout)
-        logger.debug(f"Sending line with timeout ({timeout} s): {line.decode('ASCII')}")
+        logger.debug(f'Send accumulated timeout: {self.timeOut}')
         super().sendLine(line)
 
     def lineReceived(self, line: bytes) -> None:
         if self.ongoing_calls:
             # We received a reply
             self.resetTimeout()
             self.ongoing_calls -= 1
@@ -150,19 +133,19 @@
         else:
             self.sendLine('PWSTANDBY'.encode('ASCII'))
 
     def get_volume(self) -> None:
         self.sendLine('MV?'.encode('ASCII'))
 
     def set_volume(self, value: str) -> None:
-        raw_value = DN500AVFormat().mv_reverse_params.get(value)
-        if raw_value is None:
+        rawvalue = DN500AVFormat().mv_reverse_params.get(value)
+        if rawvalue is None:
             logger.warning(f"Set volume value {value} is invalid.")
         else:
-            message = 'MV' + raw_value
+            message = 'MV' + rawvalue
             self.sendLine(message.encode('ASCII'))
 
     def get_mute(self) -> None:
         self.sendLine('MU?'.encode('ASCII'))
 
     def set_mute(self, state: bool) -> None:
         if state:
@@ -175,36 +158,30 @@
 
     def set_source(self, source: str) -> None:
         message = 'SI' + source
         self.sendLine(message.encode('ASCII'))
 
 
 class DenonClientFactory(ClientFactory):
-    gui: bool
     protocol = DenonProtocol
 
     def __init__(self) -> None:
         self.gui = False
 
 
 class DenonClientGUIFactory(ClientFactory):
-    app: 'DenonRemoteApp'  # TODO: Extract interface
     protocol = DenonProtocol
 
     def __init__(self, app) -> None:
         self.gui = True
         self.app = app
         import kivy.logger
         global logger
         logger = kivy.logger.Logger
 
-    def clientConnectionFailed(
-            self, connector: twisted.internet.interfaces.IConnector,
-            reason: twisted.python.failure.Failure
-    ) -> None:
+    def clientConnectionFailed(self, connector: twisted.internet.interfaces.IConnector,
+                               reason: twisted.python.failure.Failure) -> None:
         self.app.on_connection_failed(connector, reason)
 
-    def clientConnectionLost(
-            self, connector: twisted.internet.interfaces.IConnector,
-            reason: twisted.python.failure.Failure
-    ) -> None:
+    def clientConnectionLost(self, connector: twisted.internet.interfaces.IConnector,
+                             reason: twisted.python.failure.Failure) -> None:
         self.app.on_connection_lost(connector, reason)
```

### Comparing `denonremote-0.10.0/src/denonremote/denon/dn500av.py` & `denonremote-0.9.0/src/denonremote/denon/dn500av.py`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/fonts/FreeSerif.ttf` & `denonremote-0.9.0/src/denonremote/fonts/FreeSerif.ttf`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/fonts/RobotoMono-Bold.ttf` & `denonremote-0.9.0/src/denonremote/fonts/RobotoMono-Bold.ttf`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/fonts/RobotoMono-BoldItalic.ttf` & `denonremote-0.9.0/src/denonremote/fonts/RobotoMono-BoldItalic.ttf`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/fonts/RobotoMono-Italic.ttf` & `denonremote-0.9.0/src/denonremote/fonts/RobotoMono-Italic.ttf`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/fonts/RobotoMono-Regular.ttf` & `denonremote-0.9.0/src/denonremote/fonts/RobotoMono-Regular.ttf`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/fonts/Unicode_IEC_symbol.ttf` & `denonremote-0.9.0/src/denonremote/fonts/Unicode_IEC_symbol.ttf`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/images/DN-500AV.png` & `denonremote-0.9.0/src/denonremote/images/DN-500AV.png`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/images/icon.png` & `denonremote-0.9.0/src/denonremote/images/icon.png`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/settings/volume.json` & `denonremote-0.9.0/src/denonremote/settings/volume.json`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/src/denonremote/settings/volume_display.json` & `denonremote-0.9.0/src/denonremote/settings/volume_display.json`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/LICENSE` & `denonremote-0.9.0/LICENSE`

 * *Files identical despite different names*

### Comparing `denonremote-0.10.0/README.md` & `denonremote-0.9.0/README.md`

 * *Files 24% similar despite different names*

```diff
@@ -1,29 +1,39 @@
-[![Denon Remote Logo](https://raw.githubusercontent.com/EMATech/denonremote/main/data/assets/icon_24.png) Denon Remote](https://github.com/ematech/denonremote)
-===================================================================================================
-
-[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
-[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/denonremote.svg)](https://pypi.org/project/denonremote)
-[![Downloads](https://pepy.tech/badge/denonremote)](https://pepy.tech/project/denonremote)
-[![PyPI - Version](https://img.shields.io/pypi/v/denonremote.svg)](https://pypi.org/project/denonremote)
+Denon Remote
+============
 
 Control [Denon Professional DN-500AV surround preamplifier](https://www.denonpro.com/index.php/products/view/dn-500av)
 remotely.
 
-![Screenshot](https://raw.githubusercontent.com/EMATech/denonremote/main/data/screenshots/screenshot-v0.9.0-main.png)
+![Screenshot](data/screenshots/screenshot-v0.9.0-main.png)
+
+![Settings Screenshot](data/screenshots/screenshot-v0.9.0-settings.png)
+
+Author: Raphael Doursenaud <rdoursenaud+denonremote@gmail.com>
+
+License: [GPLv3+](LICENSE)
+
+Language: [Python](https://python.org) 3
+
+Fonts used:
+
+- [Unicode Power Symbol](https://unicodepowersymbol.com/) Copyright (c) 2013 Joe Loughry licensed under MIT
+- [Free Serif](https://savannah.gnu.org/projects/freefont/) licensed under GPLv3
+- [Roboto](https://fonts.google.com/specimen/Roboto) Copyright Christian Robertson licensed under Apache 2.0
 
-![Settings Screenshot](https://raw.githubusercontent.com/EMATech/denonremote/main/data/screenshots/screenshot-v0.9.0-settings.png)
 
 ### Features
 
+
 #### Target hardware
 
 - [x] Denon Professional DN-500AV (Seems to be based on the same platform as the Denon AVR-1912 and AVR-2112CI)
 - [ ] More? Contributions welcome!
 
+
 #### Communication
 
 - [x] Ethernet
     - [x] Using [Twisted](https://twistedmatrix.com)
     - [x] connection status detection
     - [x] automatically try to reconnect with exponential backoff
 - [ ] RS-232? also using Twisted
@@ -98,30 +108,27 @@
         - [x] M for Mute
         - [x] Up/Down Vol +/-
         - [ ] Left/Right VolPreset +/-
         - [ ] PgUp/PgDwn SrcPreset +/-
 - [x] Systray/Taskbar support using [pystray](https://pypi.org/project/pystray/)
 - [x] Only one instance is allowed (Microsoft Windows only)
 - [X] Option to make window stay always on top (Microsoft Windows only)
-- [x] Touch doesn't activate the window and doesn't steal focus (Microsoft Windows only)
+- [x] Touch doesn’t activate the window and doesn’t steal focus (Microsoft Windows only)
 - [x] Trigger events without having to activate the window first (Microsoft Windows only)
 - [ ] Draw it on the first touch enabled display if available instead of the main one
 
 ##### Windows executable
 
 - [ ] Handle shutdown to power off the device
-- [x] Generate icon with [IconMaker](https://github.com/Inedo/iconmaker)
-- [x] [PyInstaller](https://www.pyinstaller.org) (Fairly stable for Microsoft Windows)
+- [x] [PyInstaller](https://www.pyinstaller.org)
+    - [x] Generate icon with [IconMaker](https://github.com/Inedo/iconmaker)
     - [x] [UPX](https://upx.github.io/) support
     - How to build:
         - Review [denonremote.spec](denonremote.spec)
-        - Use `hatch build; hatch run build:pyinstaller`
-- [x] [Nuitka](https://nuitka.net) (Alpha support for Microsoft Windows)
-    - Use `hatch build; hatch run build:nuitka`
-- [ ] [PyOxidiser](https://github.com/indygreg/PyOxidizer)
+        - Use `python -m PyInstaller --clean --upx-dir=c:\upx-3.96-win64 denonremote.spec`
 - [ ] [cx-Freeze](https://pypi.org/project/cx-Freeze/) for multiplatform support?
 - [ ] VST plugin? (Not required if MIDI input is implemented but would be neat to have in the monitoring section of a
   DAW)
     - [ ] See [PyVST](https://pypi.org/project/pyvst/)
 
 #### Mobile
 
@@ -141,16 +148,15 @@
 - 23/tcp (TELNET): BridgeCo AG Telnet server  
   AVR serial protocol used here
 - 80/tcp (HTTP): GoAhead WebServer  
   Web control (index.asp) Shows nothing.  
   Most of the useful code is commented!  
   CSS loading at "css/mainMenu.css" times out.  
   Main control is available at "MainZone/index.html"!
-- 443/tcp (HTTPS):  
-  ERR_SSL_PROTOCOL_ERROR in Google Chrome  
+- 443/tcp (HTTPS): ERR_SSL_PROTOCOL_ERROR in Google Chrome  
   SSL_ERROR_EXTRACT_PUBLIC_KEY_FAILURE in Mozilla Firefox
 - 1026/tcp (RTSP): Apple AirTunes rtspd 103.2
 - 6666/tcp: ?
 - 8080/tcp (HTTP): AV receiver http config
 
 ### Similar projects
 
@@ -175,77 +181,7 @@
 - https://github.com/toebsen/python-denonavr (HTTP RESTful server)
 - https://github.com/MrJavaWolf/DenonPhoneController (Landline phone controller)
 - https://github.com/troykelly/python-denon-avr-serial-over-ip (Library)
 - https://github.com/auchter/denonavr_serial (Library)
 - https://github.com/jphutchins/pyavreceiver (Nice library)
 - https://github.com/frawau/aiomadeavr (Library)
 - https://github.com/scarface-4711/denonavr (Uses the HTTP/XML interface. Library)
-
-Legal notice
-------------
-
-### License
-
-![GPLv3](https://raw.githubusercontent.com/EMATech/denonremote/main/data/assets/sources/gplv3-or-later.svg)
-
-Author: ©2021-2022 Raphaël Doursenaud.
-
-This software is released under the terms of the GNU General Public License, version 3.0 or later (GPL-3.0-or-later).
-
-See [LICENSE](LICENSE).
-
-Logo and icons released under the
-[Creative Commons Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).
-
-### Dependencies & License Acknowledgment
-
-- [Python](https://python.org) v3.10  
-  Copyright © 2001-2022 Python Software Foundation.  
-  Used under the terms of the PSF License Agreement.
-- [Kivy](https://kivy.org/)  
-  Copyright 2010-2022, The Kivy Authors.  
-  Used under the terms of the MIT license.  
-  Uses:
-    - [docutils](https://docutils.sourceforge.io/COPYING.html)
-    - [pygments](https://github.com/pygments/pygments/blob/master/LICENSE)
-    - [sdl2](https://www.libsdl.org/license.php)
-    - [glew](https://glew.sourceforge.net/glew.txt)
-    - [pywin32](https://pypi.org/project/pywin32/)
-    - [zlib](https://github.com/madler/zlib/blob/master/README)
-- [Twisted](https://twisted.org/)  
-  Copyright (c) 2001-2022 Twisted Matrix Laboratories.  
-  Used under the terms of the MIT license.
-- [PyInstaller](https://pyinstaller.org)  
-  Copyright (c) 2010-2022, PyInstaller Development Team.  
-  Copyright (c) 2005-2009, Giovanni Bajo.  
-  Based on previous work under copyright (c) 2002 McMillan Enterprises, Inc.  
-  Used under the terms of the GNU General Public License version 2.0.
-    - includes [cpython](https://hg.python.org/cpython/file/tip/Tools/msi/exe/crtlicense.txt)
-
-#### Fonts
-
-- [Free Serif](https://www.gnu.org/software/freefont/)  
-  Copyright © 2022 Free Software Foundation, Inc.  
-  Used under the terms of the GNU General Public License version 3.0.
-- [Roboto Mono](https://github.com/googlefonts/RobotoMono)  
-  Copyright (c) 2015 The Roboto Mono Project Authors.  
-  Used under the terms of the Apache License, Version 2.0.
-- [Unicode Power Symbol](https://unicodepowersymbol.com/)  
-  Copyright (c) 2013 Joe Loughry.  
-  Used under the terms of the MIT license.
-
-#### Logo and icons
-
-Own work based upon:
-
-- [Denon Professional DN-500AV Front](https://www.denonpro.com/index.php/products/view/dn-500av#tab-images)  
-  Marketing material from Denon Professional.  
-  Copyright 2012-2022 inMusic Brands, Inc.
-
-### Trademarks
-
-- [Denon](https://www.denon.com) is a trademark of Sound United, LLC and Affiliates.
-- [Denon Professional](https://www.denonpro.com) is a trademark of inMusic Brands, Inc.
-
-#### Other
-
-Other trademarks are property of their respective owners and used fairly for descriptive and nominative purposes only.
```

### Comparing `denonremote-0.10.0/PKG-INFO` & `denonremote-0.9.0/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: denonremote
-Version: 0.10.0
+Version: 0.9.0
 Summary: A desktop GUI remote for the Denon DN-500 AV receiver.
 Project-URL: Homepage, https://github.com/ematech/denonremote
 Project-URL: Issues, https://github.com/ematech/denonremote/issues
 Author-email: Raphaël Doursenaud <rdoursenaud@free.fr>
 License: GNU GENERAL PUBLIC LICENSE
                                Version 3, 29 June 2007
         
@@ -692,50 +692,61 @@
 Classifier: Operating System :: MacOS :: MacOS X
 Classifier: Operating System :: Microsoft :: Windows :: Windows 10
 Classifier: Operating System :: Microsoft :: Windows :: Windows 11
 Classifier: Operating System :: POSIX :: Linux
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Home Automation
 Classifier: Topic :: Multimedia :: Sound/Audio
 Classifier: Topic :: Scientific/Engineering :: Human Machine Interfaces
 Classifier: Topic :: Utilities
 Classifier: Typing :: Typed
-Requires-Python: ~=3.10
-Requires-Dist: kivy[sdl2]==2.2.1
-Requires-Dist: kivyontop==1.4
-Requires-Dist: pillow~=9.5.0
+Requires-Python: >=3.10
+Requires-Dist: kivy-deps-glew
+Requires-Dist: kivy-deps-sdl2
+Requires-Dist: kivy==2.1.0
+Requires-Dist: kivyontop
+Requires-Dist: pillow~=9.1.0
 Requires-Dist: pystray==0.19.4
-Requires-Dist: twisted==22.10.0
+Requires-Dist: twisted==22.4.0
 Description-Content-Type: text/markdown
 
-[![Denon Remote Logo](https://raw.githubusercontent.com/EMATech/denonremote/main/data/assets/icon_24.png) Denon Remote](https://github.com/ematech/denonremote)
-===================================================================================================
-
-[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
-[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/denonremote.svg)](https://pypi.org/project/denonremote)
-[![Downloads](https://pepy.tech/badge/denonremote)](https://pepy.tech/project/denonremote)
-[![PyPI - Version](https://img.shields.io/pypi/v/denonremote.svg)](https://pypi.org/project/denonremote)
+Denon Remote
+============
 
 Control [Denon Professional DN-500AV surround preamplifier](https://www.denonpro.com/index.php/products/view/dn-500av)
 remotely.
 
-![Screenshot](https://raw.githubusercontent.com/EMATech/denonremote/main/data/screenshots/screenshot-v0.9.0-main.png)
+![Screenshot](data/screenshots/screenshot-v0.9.0-main.png)
+
+![Settings Screenshot](data/screenshots/screenshot-v0.9.0-settings.png)
+
+Author: Raphael Doursenaud <rdoursenaud+denonremote@gmail.com>
+
+License: [GPLv3+](LICENSE)
+
+Language: [Python](https://python.org) 3
+
+Fonts used:
+
+- [Unicode Power Symbol](https://unicodepowersymbol.com/) Copyright (c) 2013 Joe Loughry licensed under MIT
+- [Free Serif](https://savannah.gnu.org/projects/freefont/) licensed under GPLv3
+- [Roboto](https://fonts.google.com/specimen/Roboto) Copyright Christian Robertson licensed under Apache 2.0
 
-![Settings Screenshot](https://raw.githubusercontent.com/EMATech/denonremote/main/data/screenshots/screenshot-v0.9.0-settings.png)
 
 ### Features
 
+
 #### Target hardware
 
 - [x] Denon Professional DN-500AV (Seems to be based on the same platform as the Denon AVR-1912 and AVR-2112CI)
 - [ ] More? Contributions welcome!
 
+
 #### Communication
 
 - [x] Ethernet
     - [x] Using [Twisted](https://twistedmatrix.com)
     - [x] connection status detection
     - [x] automatically try to reconnect with exponential backoff
 - [ ] RS-232? also using Twisted
@@ -810,30 +821,27 @@
         - [x] M for Mute
         - [x] Up/Down Vol +/-
         - [ ] Left/Right VolPreset +/-
         - [ ] PgUp/PgDwn SrcPreset +/-
 - [x] Systray/Taskbar support using [pystray](https://pypi.org/project/pystray/)
 - [x] Only one instance is allowed (Microsoft Windows only)
 - [X] Option to make window stay always on top (Microsoft Windows only)
-- [x] Touch doesn't activate the window and doesn't steal focus (Microsoft Windows only)
+- [x] Touch doesn’t activate the window and doesn’t steal focus (Microsoft Windows only)
 - [x] Trigger events without having to activate the window first (Microsoft Windows only)
 - [ ] Draw it on the first touch enabled display if available instead of the main one
 
 ##### Windows executable
 
 - [ ] Handle shutdown to power off the device
-- [x] Generate icon with [IconMaker](https://github.com/Inedo/iconmaker)
-- [x] [PyInstaller](https://www.pyinstaller.org) (Fairly stable for Microsoft Windows)
+- [x] [PyInstaller](https://www.pyinstaller.org)
+    - [x] Generate icon with [IconMaker](https://github.com/Inedo/iconmaker)
     - [x] [UPX](https://upx.github.io/) support
     - How to build:
         - Review [denonremote.spec](denonremote.spec)
-        - Use `hatch build; hatch run build:pyinstaller`
-- [x] [Nuitka](https://nuitka.net) (Alpha support for Microsoft Windows)
-    - Use `hatch build; hatch run build:nuitka`
-- [ ] [PyOxidiser](https://github.com/indygreg/PyOxidizer)
+        - Use `python -m PyInstaller --clean --upx-dir=c:\upx-3.96-win64 denonremote.spec`
 - [ ] [cx-Freeze](https://pypi.org/project/cx-Freeze/) for multiplatform support?
 - [ ] VST plugin? (Not required if MIDI input is implemented but would be neat to have in the monitoring section of a
   DAW)
     - [ ] See [PyVST](https://pypi.org/project/pyvst/)
 
 #### Mobile
 
@@ -853,16 +861,15 @@
 - 23/tcp (TELNET): BridgeCo AG Telnet server  
   AVR serial protocol used here
 - 80/tcp (HTTP): GoAhead WebServer  
   Web control (index.asp) Shows nothing.  
   Most of the useful code is commented!  
   CSS loading at "css/mainMenu.css" times out.  
   Main control is available at "MainZone/index.html"!
-- 443/tcp (HTTPS):  
-  ERR_SSL_PROTOCOL_ERROR in Google Chrome  
+- 443/tcp (HTTPS): ERR_SSL_PROTOCOL_ERROR in Google Chrome  
   SSL_ERROR_EXTRACT_PUBLIC_KEY_FAILURE in Mozilla Firefox
 - 1026/tcp (RTSP): Apple AirTunes rtspd 103.2
 - 6666/tcp: ?
 - 8080/tcp (HTTP): AV receiver http config
 
 ### Similar projects
 
@@ -887,77 +894,7 @@
 - https://github.com/toebsen/python-denonavr (HTTP RESTful server)
 - https://github.com/MrJavaWolf/DenonPhoneController (Landline phone controller)
 - https://github.com/troykelly/python-denon-avr-serial-over-ip (Library)
 - https://github.com/auchter/denonavr_serial (Library)
 - https://github.com/jphutchins/pyavreceiver (Nice library)
 - https://github.com/frawau/aiomadeavr (Library)
 - https://github.com/scarface-4711/denonavr (Uses the HTTP/XML interface. Library)
-
-Legal notice
-------------
-
-### License
-
-![GPLv3](https://raw.githubusercontent.com/EMATech/denonremote/main/data/assets/sources/gplv3-or-later.svg)
-
-Author: ©2021-2022 Raphaël Doursenaud.
-
-This software is released under the terms of the GNU General Public License, version 3.0 or later (GPL-3.0-or-later).
-
-See [LICENSE](LICENSE).
-
-Logo and icons released under the
-[Creative Commons Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).
-
-### Dependencies & License Acknowledgment
-
-- [Python](https://python.org) v3.10  
-  Copyright © 2001-2022 Python Software Foundation.  
-  Used under the terms of the PSF License Agreement.
-- [Kivy](https://kivy.org/)  
-  Copyright 2010-2022, The Kivy Authors.  
-  Used under the terms of the MIT license.  
-  Uses:
-    - [docutils](https://docutils.sourceforge.io/COPYING.html)
-    - [pygments](https://github.com/pygments/pygments/blob/master/LICENSE)
-    - [sdl2](https://www.libsdl.org/license.php)
-    - [glew](https://glew.sourceforge.net/glew.txt)
-    - [pywin32](https://pypi.org/project/pywin32/)
-    - [zlib](https://github.com/madler/zlib/blob/master/README)
-- [Twisted](https://twisted.org/)  
-  Copyright (c) 2001-2022 Twisted Matrix Laboratories.  
-  Used under the terms of the MIT license.
-- [PyInstaller](https://pyinstaller.org)  
-  Copyright (c) 2010-2022, PyInstaller Development Team.  
-  Copyright (c) 2005-2009, Giovanni Bajo.  
-  Based on previous work under copyright (c) 2002 McMillan Enterprises, Inc.  
-  Used under the terms of the GNU General Public License version 2.0.
-    - includes [cpython](https://hg.python.org/cpython/file/tip/Tools/msi/exe/crtlicense.txt)
-
-#### Fonts
-
-- [Free Serif](https://www.gnu.org/software/freefont/)  
-  Copyright © 2022 Free Software Foundation, Inc.  
-  Used under the terms of the GNU General Public License version 3.0.
-- [Roboto Mono](https://github.com/googlefonts/RobotoMono)  
-  Copyright (c) 2015 The Roboto Mono Project Authors.  
-  Used under the terms of the Apache License, Version 2.0.
-- [Unicode Power Symbol](https://unicodepowersymbol.com/)  
-  Copyright (c) 2013 Joe Loughry.  
-  Used under the terms of the MIT license.
-
-#### Logo and icons
-
-Own work based upon:
-
-- [Denon Professional DN-500AV Front](https://www.denonpro.com/index.php/products/view/dn-500av#tab-images)  
-  Marketing material from Denon Professional.  
-  Copyright 2012-2022 inMusic Brands, Inc.
-
-### Trademarks
-
-- [Denon](https://www.denon.com) is a trademark of Sound United, LLC and Affiliates.
-- [Denon Professional](https://www.denonpro.com) is a trademark of inMusic Brands, Inc.
-
-#### Other
-
-Other trademarks are property of their respective owners and used fairly for descriptive and nominative purposes only.
```


# Comparing `tmp/hspylib-cfman-0.9.90.tar.gz` & `tmp/hspylib-cfman-0.9.91.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hspylib-cfman-0.9.90.tar", last modified: Fri May 19 18:15:24 2023, max compression
+gzip compressed data, was "hspylib-cfman-0.9.91.tar", last modified: Tue Jun 27 22:01:07 2023, max compression
```

## Comparing `hspylib-cfman-0.9.90.tar` & `hspylib-cfman-0.9.91.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-05-19 18:15:24.774511 hspylib-cfman-0.9.90/
--rw-r--r--   0 hjunior    (504) staff       (20)       49 2022-02-23 03:43:53.000000 hspylib-cfman-0.9.90/MANIFEST.in
--rw-r--r--   0 hjunior    (504) staff       (20)     1548 2023-05-19 18:15:24.772963 hspylib-cfman-0.9.90/PKG-INFO
--rw-r--r--   0 hjunior    (504) staff       (20)      677 2023-05-19 18:15:23.000000 hspylib-cfman-0.9.90/README.md
-drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-05-19 18:15:24.707268 hspylib-cfman-0.9.90/cfman/
--rw-r--r--   0 hjunior    (504) staff       (20)        7 2023-05-19 18:15:23.000000 hspylib-cfman-0.9.90/cfman/.version
--rw-r--r--   0 hjunior    (504) staff       (20)      716 2023-04-19 22:01:52.000000 hspylib-cfman-0.9.90/cfman/__classpath__.py
--rw-r--r--   0 hjunior    (504) staff       (20)      167 2023-05-19 18:15:23.000000 hspylib-cfman-0.9.90/cfman/__init__.py
--rw-r--r--   0 hjunior    (504) staff       (20)     3595 2023-04-19 22:17:47.000000 hspylib-cfman-0.9.90/cfman/__main__.py
-drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-05-19 18:15:24.727146 hspylib-cfman-0.9.90/cfman/core/
--rw-r--r--   0 hjunior    (504) staff       (20)      238 2023-05-19 18:15:23.000000 hspylib-cfman-0.9.90/cfman/core/__init__.py
--rw-r--r--   0 hjunior    (504) staff       (20)     7619 2023-04-19 22:17:47.000000 hspylib-cfman-0.9.90/cfman/core/cf.py
--rw-r--r--   0 hjunior    (504) staff       (20)     2950 2023-05-17 21:37:29.000000 hspylib-cfman-0.9.90/cfman/core/cf_application.py
--rw-r--r--   0 hjunior    (504) staff       (20)     5534 2023-04-19 22:17:47.000000 hspylib-cfman-0.9.90/cfman/core/cf_blue_green_checker.py
--rw-r--r--   0 hjunior    (504) staff       (20)     1234 2023-04-19 22:17:47.000000 hspylib-cfman-0.9.90/cfman/core/cf_endpoint.py
--rw-r--r--   0 hjunior    (504) staff       (20)    15395 2023-05-17 21:37:29.000000 hspylib-cfman-0.9.90/cfman/core/cf_manager.py
-drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-05-19 18:15:24.736126 hspylib-cfman-0.9.90/cfman/exception/
--rw-r--r--   0 hjunior    (504) staff       (20)      167 2023-05-19 18:15:23.000000 hspylib-cfman-0.9.90/cfman/exception/__init__.py
--rw-r--r--   0 hjunior    (504) staff       (20)      845 2023-04-19 22:01:52.000000 hspylib-cfman-0.9.90/cfman/exception/exceptions.py
--rw-r--r--   0 hjunior    (504) staff       (20)      204 2022-02-17 02:35:48.000000 hspylib-cfman-0.9.90/cfman/welcome.txt
-drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-05-19 18:15:24.769586 hspylib-cfman-0.9.90/hspylib_cfman.egg-info/
--rw-r--r--   0 hjunior    (504) staff       (20)     1548 2023-05-19 18:15:24.000000 hspylib-cfman-0.9.90/hspylib_cfman.egg-info/PKG-INFO
--rw-r--r--   0 hjunior    (504) staff       (20)      520 2023-05-19 18:15:24.000000 hspylib-cfman-0.9.90/hspylib_cfman.egg-info/SOURCES.txt
--rw-r--r--   0 hjunior    (504) staff       (20)        1 2023-05-19 18:15:24.000000 hspylib-cfman-0.9.90/hspylib_cfman.egg-info/dependency_links.txt
--rw-r--r--   0 hjunior    (504) staff       (20)       28 2023-05-19 18:15:24.000000 hspylib-cfman-0.9.90/hspylib_cfman.egg-info/requires.txt
--rw-r--r--   0 hjunior    (504) staff       (20)        6 2023-05-19 18:15:24.000000 hspylib-cfman-0.9.90/hspylib_cfman.egg-info/top_level.txt
--rw-r--r--   0 hjunior    (504) staff       (20)       38 2023-05-19 18:15:24.774722 hspylib-cfman-0.9.90/setup.cfg
--rw-r--r--   0 hjunior    (504) staff       (20)     1934 2023-04-19 22:13:46.000000 hspylib-cfman-0.9.90/setup.py
+drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-06-27 22:01:07.102869 hspylib-cfman-0.9.91/
+-rw-r--r--   0 hjunior    (504) staff       (20)       49 2022-02-23 03:43:53.000000 hspylib-cfman-0.9.91/MANIFEST.in
+-rw-r--r--   0 hjunior    (504) staff       (20)     1548 2023-06-27 22:01:07.101518 hspylib-cfman-0.9.91/PKG-INFO
+-rw-r--r--   0 hjunior    (504) staff       (20)      677 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/README.md
+drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-06-27 22:01:07.074968 hspylib-cfman-0.9.91/cfman/
+-rw-r--r--   0 hjunior    (504) staff       (20)        7 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/cfman/.version
+-rw-r--r--   0 hjunior    (504) staff       (20)      716 2023-04-19 22:01:52.000000 hspylib-cfman-0.9.91/cfman/__classpath__.py
+-rw-r--r--   0 hjunior    (504) staff       (20)      167 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/cfman/__init__.py
+-rw-r--r--   0 hjunior    (504) staff       (20)     3472 2023-06-27 21:55:04.000000 hspylib-cfman-0.9.91/cfman/__main__.py
+drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-06-27 22:01:07.086120 hspylib-cfman-0.9.91/cfman/core/
+-rw-r--r--   0 hjunior    (504) staff       (20)      238 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/cfman/core/__init__.py
+-rw-r--r--   0 hjunior    (504) staff       (20)     7745 2023-06-27 21:59:43.000000 hspylib-cfman-0.9.91/cfman/core/cf.py
+-rw-r--r--   0 hjunior    (504) staff       (20)     2950 2023-05-17 21:37:29.000000 hspylib-cfman-0.9.91/cfman/core/cf_application.py
+-rw-r--r--   0 hjunior    (504) staff       (20)     5534 2023-04-19 22:17:47.000000 hspylib-cfman-0.9.91/cfman/core/cf_blue_green_checker.py
+-rw-r--r--   0 hjunior    (504) staff       (20)     1234 2023-04-19 22:17:47.000000 hspylib-cfman-0.9.91/cfman/core/cf_endpoint.py
+-rw-r--r--   0 hjunior    (504) staff       (20)    16928 2023-06-27 21:59:31.000000 hspylib-cfman-0.9.91/cfman/core/cf_manager.py
+drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-06-27 22:01:07.090829 hspylib-cfman-0.9.91/cfman/exception/
+-rw-r--r--   0 hjunior    (504) staff       (20)      167 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/cfman/exception/__init__.py
+-rw-r--r--   0 hjunior    (504) staff       (20)      845 2023-04-19 22:01:52.000000 hspylib-cfman-0.9.91/cfman/exception/exceptions.py
+-rw-r--r--   0 hjunior    (504) staff       (20)      204 2022-02-17 02:35:48.000000 hspylib-cfman-0.9.91/cfman/welcome.txt
+drwxr-xr-x   0 hjunior    (504) staff       (20)        0 2023-06-27 22:01:07.099666 hspylib-cfman-0.9.91/hspylib_cfman.egg-info/
+-rw-r--r--   0 hjunior    (504) staff       (20)     1548 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/hspylib_cfman.egg-info/PKG-INFO
+-rw-r--r--   0 hjunior    (504) staff       (20)      520 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/hspylib_cfman.egg-info/SOURCES.txt
+-rw-r--r--   0 hjunior    (504) staff       (20)        1 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/hspylib_cfman.egg-info/dependency_links.txt
+-rw-r--r--   0 hjunior    (504) staff       (20)       28 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/hspylib_cfman.egg-info/requires.txt
+-rw-r--r--   0 hjunior    (504) staff       (20)        6 2023-06-27 22:01:06.000000 hspylib-cfman-0.9.91/hspylib_cfman.egg-info/top_level.txt
+-rw-r--r--   0 hjunior    (504) staff       (20)       38 2023-06-27 22:01:07.103095 hspylib-cfman-0.9.91/setup.cfg
+-rw-r--r--   0 hjunior    (504) staff       (20)     1934 2023-04-19 22:13:46.000000 hspylib-cfman-0.9.91/setup.py
```

### Comparing `hspylib-cfman-0.9.90/PKG-INFO` & `hspylib-cfman-0.9.91/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hspylib-cfman
-Version: 0.9.90
+Version: 0.9.91
 Summary: HsPyLib - CloudFoundry manager
 Home-page: https://github.com/yorevs/hspylib
 Author: Hugo Saporetti Junior
 Author-email: yorevs@hotmail.com
 License: MIT
 Project-URL: GitHub, https://github.com/yorevs/hspylib
 Project-URL: PyPi, https://pypi.org/project/hspylib-cfman/
@@ -24,12 +24,12 @@
 Description-Content-Type: text/markdown
 
 # HomeSetup - CloudFoundry manager
 
 ## Manage your PCF applications
 
 [![License](https://badgen.net/badge/license/MIT/gray)](LICENSE.md)
-[![Release](https://badgen.net/badge/release/v0.9.90/gray)](CHANGELOG.md#unreleased)
+[![Release](https://badgen.net/badge/release/v0.9.91/gray)](CHANGELOG.md#unreleased)
 [![PyPi](https://badgen.net/badge/icon/python?icon=pypi&label)](https://pypi.org/project/hspylib-cfman)
 [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/yorevs/hspylib)
 [![Gitter](https://badgen.net/badge/icon/gitter?icon=gitter&label)](https://gitter.im/hspylib/community)
 [![Donate](https://badgen.net/badge/paypal/donate/yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=J5CDEFLF6M3H4)
```

### Comparing `hspylib-cfman-0.9.90/cfman/__classpath__.py` & `hspylib-cfman-0.9.91/cfman/__classpath__.py`

 * *Files identical despite different names*

### Comparing `hspylib-cfman-0.9.90/cfman/__main__.py` & `hspylib-cfman-0.9.91/cfman/__main__.py`

 * *Files 7% similar despite different names*

```diff
@@ -8,28 +8,28 @@
    @created: Tue, 4 May 2021
     @author: <B>H</B>ugo <B>S</B>aporetti <B>J</B>unior"
       @site: https://github.com/yorevs/hspylib
    @license: MIT - Please refer to <https://opensource.org/licenses/MIT>
 
    Copyright 2023, HsPyLib team
 """
-from cfman.__classpath__ import _Classpath
-from cfman.core.cf_manager import CFManager
+import logging as log
+import os
+import sys
+from textwrap import dedent
+
 from clitt.core.tui.tui_application import TUIApplication
 from hspylib.core.enums.charset import Charset
 from hspylib.core.zoned_datetime import now
 from hspylib.modules.application.argparse.parser_action import ParserAction
 from hspylib.modules.application.exit_status import ExitStatus
 from hspylib.modules.application.version import Version
-from hspylib.modules.cli.vt100.vt_utils import clear_screen, prepare_render
-from textwrap import dedent
 
-import logging as log
-import os
-import sys
+from cfman.__classpath__ import _Classpath
+from cfman.core.cf_manager import CFManager
 
 
 class Main(TUIApplication):
     """Cloud Foundry Manager - Manage PCF applications."""
 
     # The welcome message
     DESCRIPTION = _Classpath.get_source_path("welcome.txt").read_text(encoding=Charset.UTF_8.val)
@@ -83,16 +83,14 @@
         """
             )
         )
         return self._exec_application()
 
     def _exec_application(self) -> ExitStatus:
         """Execute the application."""
-        prepare_render()
         self._cf_manager.run()
-        clear_screen()
         return ExitStatus.SUCCESS
 
 
 if __name__ == "__main__":
     # Application entry point
     Main("cfman").INSTANCE.run(sys.argv[1:])
```

### Comparing `hspylib-cfman-0.9.90/cfman/core/cf.py` & `hspylib-cfman-0.9.91/cfman/core/cf.py`

 * *Files 2% similar despite different names*

```diff
@@ -8,22 +8,23 @@
    @created: Tue, 4 May 2021
     @author: <B>H</B>ugo <B>S</B>aporetti <B>J</B>unior"
       @site: https://github.com/yorevs/hspylib
    @license: MIT - Please refer to <https://opensource.org/licenses/MIT>
 
    Copyright 2023, HsPyLib team
 """
+import os
 from collections import namedtuple
+from typing import List, Optional
+
 from hspylib.core.metaclass.singleton import Singleton
 from hspylib.core.tools.commons import sysout
 from hspylib.modules.application.exit_status import ExitStatus
 from hspylib.modules.cli.terminal import Terminal
-from typing import List, Optional
-
-import os
+from hspylib.modules.cli.vt100.vt_utils import clear_screen, set_auto_wrap
 
 CFTarget = namedtuple("CFTarget", ["user", "org", "space", "connected"])
 
 
 class CloudFoundry(metaclass=Singleton):
     """Cloud Foundry command line tool wrapper."""
 
@@ -181,14 +182,16 @@
     def logs(self, **kwargs) -> None:
         """Tail or show recent logs for an app
         Kwargs:
             app (str): the application name.
                recent: dump recent logs instead of tailing.
         :param kwargs arbitrary CF command keyword arguments.
         """
+        clear_screen()
+        set_auto_wrap(True)
         return self._exec(cmd_line=f"logs {kwargs['app']} {'--recent' if 'recent' in kwargs else ''}", poll=True)
 
     # Execution of a CF command
     def _exec(self, cmd_line: str, poll: bool = False) -> Optional[str]:
         """Execute the CF command.
         :param cmd_line: the cf command line string
         :param poll: whether to poll or execute the command. If poll is set I/O events can be registered for any number
```

### Comparing `hspylib-cfman-0.9.90/cfman/core/cf_application.py` & `hspylib-cfman-0.9.91/cfman/core/cf_application.py`

 * *Files identical despite different names*

### Comparing `hspylib-cfman-0.9.90/cfman/core/cf_blue_green_checker.py` & `hspylib-cfman-0.9.91/cfman/core/cf_blue_green_checker.py`

 * *Files identical despite different names*

### Comparing `hspylib-cfman-0.9.90/cfman/core/cf_endpoint.py` & `hspylib-cfman-0.9.91/cfman/core/cf_endpoint.py`

 * *Files identical despite different names*

### Comparing `hspylib-cfman-0.9.90/cfman/core/cf_manager.py` & `hspylib-cfman-0.9.91/cfman/core/cf_manager.py`

 * *Files 8% similar despite different names*

```diff
@@ -8,36 +8,37 @@
    @created: Tue, 4 May 2021
     @author: <B>H</B>ugo <B>S</B>aporetti <B>J</B>unior"
       @site: https://github.com/yorevs/hspylib
    @license: MIT - Please refer to <https://opensource.org/licenses/MIT>
 
    Copyright 2023, HsPyLib team
 """
-from cfman.core.cf import CloudFoundry
-from cfman.core.cf_application import CFApplication
-from cfman.core.cf_blue_green_checker import CFBlueGreenChecker
-from cfman.core.cf_endpoint import CFEndpoint
-from cfman.exception.exceptions import CFAuthenticationError, CFConnectionError, CFExecutionError
+import sys
+from functools import partial
+from time import sleep
+from typing import Any, List, Optional, Tuple
+
+import requests
 from clitt.core.tui.mchoose.mchoose import mchoose
-from clitt.core.tui.menu.tui_menu_utils import TUIMenuUtils
 from clitt.core.tui.minput.minput import MenuInput, minput
 from clitt.core.tui.mselect.mselect import mselect
-from functools import partial
+from clitt.core.tui.tui_screen import TUIScreen
 from hspylib.core.enums.http_code import HttpCode
 from hspylib.core.preconditions import check_state
-from hspylib.core.tools.commons import syserr, sysout
 from hspylib.modules.cache.ttl_cache import TTLCache
-from hspylib.modules.cli.vt100.vt_utils import clear_screen
+from hspylib.modules.cli.keyboard import Keyboard
+from hspylib.modules.cli.vt100.vt_utils import clear_screen, set_auto_wrap, set_show_cursor
 from hspylib.modules.fetch.fetch import head
 from retry import retry
-from time import sleep
-from typing import List, Optional, Tuple
 
-import requests
-import sys
+from cfman.core.cf import CloudFoundry
+from cfman.core.cf_application import CFApplication
+from cfman.core.cf_blue_green_checker import CFBlueGreenChecker
+from cfman.core.cf_endpoint import CFEndpoint
+from cfman.exception.exceptions import CFAuthenticationError, CFConnectionError, CFExecutionError
 
 
 class CFManager:
     """Responsible for the CloudFoundry application functionalities."""
 
     CFMAN_ACTIONS = [
         "Information",
@@ -80,15 +81,16 @@
                 return "stopped"
             case "logs" | "stop" | "restart":
                 return "started"
             case _:
                 return "started", "stopped"
 
     def __init__(self, api: str, org: str, space: str, username: str, password: str, no_cache: str, cf_endpoints: str):
-        self._cf = CloudFoundry()
+        self._screen = TUIScreen.INSTANCE or TUIScreen()
+        self._cf = CloudFoundry.INSTANCE or CloudFoundry()
         self._cache = TTLCache()
         self._api = api
         self._org = org
         self._space = space
         self._username = username
         self._password = password
         self._no_cache = no_cache or False
@@ -111,83 +113,123 @@
     def __repr__(self) -> str:
         return str(self)
 
     @property
     def apps(self) -> List[CFApplication]:
         return self._get_apps() or []
 
+    @property
+    def screen(self) -> TUIScreen:
+        return self._screen
+
+    @property
+    def cursor(self) -> TUIScreen.Cursor:
+        return self.screen.cursor
+
+    def write(self, obj: Any) -> None:
+        """Write the string representation of the object to the screen."""
+        self.cursor.write(obj)
+
+    def writeln(self, obj: Any) -> None:
+        """Write the string representation of the object to the screen, appending a new line."""
+        self.cursor.writeln(obj)
+
+    def write_err(self, obj: Any) -> None:
+        """Write the string representation of the object to the screen, appending a new line."""
+        self.cursor.writeln(f"%RED%{str(obj)}%NC%")
+
     def run(self) -> None:
         """Run the main cf manager application flow."""
-        sysout("%BLUE%Checking CloudFoundry authorization...")
+
+        self._prepare_render()
+        self.writeln("%BLUE%Checking CloudFoundry authorization...")
+
         if self._cf.is_logged():
             self._api = self._cf.api()
             target = self._cf.target()
             self._username, self._org, self._space = target.user, target.org, target.space
-            sysout("%YELLOW%Already authorized to CloudFoundry!")
+            self.writeln("%YELLOW%Already authorized to CloudFoundry!")
         else:
             authorized = False
-            sysout("%YELLOW%Unauthorized to CloudFoundry, login required...")
+            self.writeln("%YELLOW%Unauthorized to CloudFoundry, login required...")
             sleep(2)
             while not authorized:
                 if not self._api:
                     self._select_endpoint()
                 if not self._username or not self._password:
                     self._prompt_credentials()
-                sysout(f"%BLUE%Authorizing {self._username}@{self._api}...")
+                self.writeln(f"%BLUE%Authorizing {self._username}@{self._api}...")
                 authorized = self._authorize()
                 if not authorized:
                     self._password = None
-                    syserr("Not authorized !")
+                    self.write_err("Not authorized !")
                     self._abort()
-            sysout("%GREEN%Successfully authorized!")
-        sysout(f"%HOM%%ED0%%WHITE%--- Target information ---%EOL%{self}")
-        TUIMenuUtils.wait_keystroke()
+            self.writeln("%GREEN%Successfully authorized!")
+
+        self.writeln(f"%HOM%%ED0%%WHITE%--- Target information ---%EOL%{self}")
+        self._wait_keystroke()
         self._loop_actions()
+        self.screen.clear()
+        self.cursor.home()
+
+    def _prepare_render(self) -> None:
+        """Prepare the screen for renderization."""
+        set_auto_wrap(False)
+        set_show_cursor(False)
+        self._screen.clear()
+        self.cursor.save()
+
+    def _wait_keystroke(self, wait_message: str = "%YELLOW%%EOL%Press any key to continue%EOL%%NC%") -> None:
+        """Wait for a keypress (blocking).
+        :param wait_message: the message to present to the user.
+        """
+        self.writeln(wait_message)
+        Keyboard.wait_keystroke()
 
     @retry(exceptions=CFConnectionError, tries=3, delay=2, backoff=3, max_delay=30)
     def _select_endpoint(self) -> None:
         """Select the PCF endpoint to connect to."""
         try:
             with open(self._cf_endpoints_file, "r", encoding="utf-8") as f_hosts:
                 endpoints = list(map(lambda l: CFEndpoint(*l.strip().split(",")), f_hosts.readlines()))
                 if len(endpoints) > 0:
                     selected = mselect(endpoints, title="Please select an endpoint")
                     if not selected:
                         self._abort()
-                    sysout(f"%BLUE%Connecting to endpoint: {selected}...")
+                    self.writeln(f"%BLUE%Connecting to endpoint: {selected}...")
                     try:
                         response = head(selected.host)
                         if response.status_code and HttpCode.OK:
                             self._api = selected.host
                         else:
-                            syserr(
+                            self.write_err(
                                 CFConnectionError(
                                     f"Failed to contact CF API %EOL%" f"  Status: ({response.status_code}): {selected}"
                                 )
                             )
                             self._abort()
                     except requests.exceptions.ConnectionError as err:
-                        syserr(
+                        self.write_err(
                             CFConnectionError(
                                 f"Failed to connect to CloudFoundry API%EOL%"
                                 f"  Host: '{selected.host}'%EOL%"
                                 f"  => {err.__class__.__name__}"
                             )
                         )
                         self._abort()
                 else:
-                    syserr(
+                    self.write_err(
                         CFExecutionError(
                             f'No endpoint yet configured. Please create the file "{self._cf_endpoints_file}" '
                             f"with at least one endpoint and try again!"
                         )
                     )
                     self._abort()
         except (IndexError, FileNotFoundError) as err:
-            syserr(
+            self.write_err(
                 CFExecutionError(
                     f'Endpoint file "{self._cf_endpoints_file}" is invalid: %EOL%'
                     f"  => {str(err)}! %EOL%"
                     f"Make sure it exists contains the following: %EOL%"
                     f"<alias>,<cf_api_url>,<protected [true|false]>%EOL%"
                 )
             )
@@ -225,49 +267,49 @@
             raise CFAuthenticationError(f"Unable to authenticate to => {self._api}")
 
         return True
 
     def _set_org(self) -> None:
         """Set the active PCF organization."""
         if not self._org:
-            sysout(f'%BLUE%Retrieving all organizations from api: "{self._api}"...')
+            self.writeln(f'%BLUE%Retrieving all organizations from api: "{self._api}"...')
             if not (orgs := self._cf.orgs()):
                 raise CFExecutionError(f"Unable to retrieve organizations: => {self._cf.last_output}")
             self._org = mselect(orgs, title="Please select the PCF organization")
             if not self._org:
                 self._abort()
             else:
                 self._target()
 
     def _set_space(self) -> None:
         """Set the active PCF space."""
         if not self._space:
             if self._no_cache or not (spaces := self._cache.read(f"cf-spaces-{self._org}")):
-                sysout(f'%BLUE%Retrieving all spaces from org: "{self._org}"...')
+                self.writeln(f'%BLUE%Retrieving all spaces from org: "{self._org}"...')
                 spaces = self._cf.spaces()
                 self._cache.save(f"cf-spaces-{self._org}", spaces)
             if not spaces:
                 raise CFExecutionError(f"Unable to retrieve org={self._org} spaces: => {self._cf.last_output}")
             self._space = mselect(spaces, title="Please select the PCF space")
             if not self._space:
                 self._abort()
             else:
                 self._target()
 
     def _get_apps(self) -> List[CFApplication]:
         """Retrieve all cf applications under the targeted org-space."""
         if self._no_cache or not (apps := self._cache.read(f"cf-apps-{self._space}")):
-            sysout(f'%BLUE%Retrieving applications from space: "{self._space}"...')
+            self.writeln(f'%BLUE%Retrieving applications from space: "{self._space}"...')
             apps = self._cf.apps()
-            sysout(f'%GREEN%Found {len(apps)} apps in space: "{self._space}"')
+            self.writeln(f'%GREEN%Found {len(apps)} apps in space: "{self._space}"')
             self._cache.save(f"cf-apps-{self._space}", apps)
         if not apps:
             if "OK" not in self._cf.last_output:
                 raise CFExecutionError(f"Unable to retrieve applications: => {self._cf.last_output}")
-            syserr(f'%YELLOW%No applications found for space: "{self._space}"')
+            self.write_err(f'%YELLOW%No applications found for space: "{self._space}"')
         cf_apps = list(map(CFApplication.of, apps if apps else []))
         self._cf_apps = cf_apps
 
         return self._cf_apps
 
     def _choose_apps(self, required_states: str | Tuple[str, str]) -> Optional[List[CFApplication]]:
         """Choose multiple PCF apps from the available list.
@@ -308,17 +350,16 @@
                     case "target":
                         self._space = self._org = self._cf_apps = None
                         self._cf.clear_target()
                         continue
                     case "blue-green-check":
                         self._blue_green_check()
                     case "information":
-                        sysout(f"%HOM%%ED0%%WHITE%--- Target information ---%EOL%{self}")
-
-                TUIMenuUtils.wait_keystroke()
+                        self.writeln(f"%HOM%%ED0%%WHITE%--- Target information ---%EOL%{self}")
+                self._wait_keystroke()
 
     def _assert_target(self) -> bool:
         if not self._org:
             self._set_org()
         if not self._space:
             self._set_space()
         if not self._cf.is_targeted():
@@ -330,28 +371,28 @@
     def _display_app_status(self) -> None:
         """Display all PCF space-application statuses."""
         apps = self.apps
 
         if len(apps) > 0:
             clear_screen()
             # fmt: off
-            sysout(
+            self.writeln(
                 f"%BLUE%Listing '{self._org}::{self._space}' applications ...%EOL%%WHITE%"
                 f"{'-=' * 60 + '%EOL%'}"
                 f"{'Name':{CFApplication.max_name_length + 2}}"
                 f"{'State':<9}{'Instances':<12}{'Mem':<6}{'Disk':<6}Routes%EOL%")
             # fmt: on
             list(map(CFApplication.print_status, apps))
-            sysout("-=" * 60 + "%EOL%")
+            self.writeln("-=" * 60 + "%EOL%")
 
     def _blue_green_check(self) -> None:
         """Display all PCF space-application blue/green check."""
         if len(self.apps) > 0:
             clear_screen()
-            sysout(f"%BLUE%Checking blue/green deployments ...%EOL%")
+            self.writeln(f"%BLUE%Checking blue/green deployments ...%EOL%")
             CFBlueGreenChecker.check(self._org, self._space, self.apps)
 
     def _perform_callable(self, action: str) -> None:
         """Wrapper of the _perform method.
         :param action the action to perform.
         """
         act = action.lower()
@@ -368,11 +409,12 @@
         """Perform the selected PCF action.
         Kwargs:
               org (str): the PCF organization name.
             space (str): the PCF space name.
         :param kwargs arbitrary PCF action arguments.
         :param action the action to perform.
         """
-        sysout(f"%BLUE%Performing {action} {str(kwargs)}...")
+        self.writeln(f"%BLUE%Performing {action} {str(kwargs)}...")
+        sleep(1)
         action_method = getattr(self._cf, action)
         check_state(callable(action_method))
-        sysout(action_method(**kwargs))
+        self.writeln(action_method(**kwargs))
```

### Comparing `hspylib-cfman-0.9.90/cfman/exception/exceptions.py` & `hspylib-cfman-0.9.91/cfman/exception/exceptions.py`

 * *Files identical despite different names*

### Comparing `hspylib-cfman-0.9.90/hspylib_cfman.egg-info/PKG-INFO` & `hspylib-cfman-0.9.91/hspylib_cfman.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hspylib-cfman
-Version: 0.9.90
+Version: 0.9.91
 Summary: HsPyLib - CloudFoundry manager
 Home-page: https://github.com/yorevs/hspylib
 Author: Hugo Saporetti Junior
 Author-email: yorevs@hotmail.com
 License: MIT
 Project-URL: GitHub, https://github.com/yorevs/hspylib
 Project-URL: PyPi, https://pypi.org/project/hspylib-cfman/
@@ -24,12 +24,12 @@
 Description-Content-Type: text/markdown
 
 # HomeSetup - CloudFoundry manager
 
 ## Manage your PCF applications
 
 [![License](https://badgen.net/badge/license/MIT/gray)](LICENSE.md)
-[![Release](https://badgen.net/badge/release/v0.9.90/gray)](CHANGELOG.md#unreleased)
+[![Release](https://badgen.net/badge/release/v0.9.91/gray)](CHANGELOG.md#unreleased)
 [![PyPi](https://badgen.net/badge/icon/python?icon=pypi&label)](https://pypi.org/project/hspylib-cfman)
 [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/yorevs/hspylib)
 [![Gitter](https://badgen.net/badge/icon/gitter?icon=gitter&label)](https://gitter.im/hspylib/community)
 [![Donate](https://badgen.net/badge/paypal/donate/yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=J5CDEFLF6M3H4)
```

### Comparing `hspylib-cfman-0.9.90/hspylib_cfman.egg-info/SOURCES.txt` & `hspylib-cfman-0.9.91/hspylib_cfman.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `hspylib-cfman-0.9.90/setup.py` & `hspylib-cfman-0.9.91/setup.py`

 * *Files identical despite different names*


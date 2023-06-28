# Comparing `tmp/anwdlserver-1.0.4.tar.gz` & `tmp/anwdlserver-1.1.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "anwdlserver-1.0.4.tar", last modified: Mon Jun 26 20:27:34 2023, max compression
+gzip compressed data, was "anwdlserver-1.1.5.tar", last modified: Wed Jun 28 13:00:41 2023, max compression
```

## Comparing `anwdlserver-1.0.4.tar` & `anwdlserver-1.1.5.tar`

### file list

```diff
@@ -1,36 +1,36 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/
--rw-r--r--   0 runner    (1001) docker     (123)     1150 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/CONTRIBUTING
--rw-r--r--   0 runner    (1001) docker     (123)    35129 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      140 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    44508 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3147 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/anwdlserver/
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20262 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     4481 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/anwdlserver/core/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7332 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7935 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/crypto.py
--rw-r--r--   0 runner    (1001) docker     (123)     5629 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/database.py
--rw-r--r--   0 runner    (1001) docker     (123)     5926 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/sanitize.py
--rw-r--r--   0 runner    (1001) docker     (123)    22929 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/server.py
--rw-r--r--   0 runner    (1001) docker     (123)     1604 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/util.py
--rw-r--r--   0 runner    (1001) docker     (123)    13013 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/core/virtualization.py
--rw-r--r--   0 runner    (1001) docker     (123)     9575 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/process.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/anwdlserver/tools/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/tools/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4255 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/anwdlserver/tools/accesstk.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/anwdlserver.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    44508 2023-06-26 20:27:34.000000 anwdlserver-1.0.4/anwdlserver.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      710 2023-06-26 20:27:34.000000 anwdlserver-1.0.4/anwdlserver.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 20:27:34.000000 anwdlserver-1.0.4/anwdlserver.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-26 20:27:34.000000 anwdlserver-1.0.4/anwdlserver.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       74 2023-06-26 20:27:34.000000 anwdlserver-1.0.4/anwdlserver.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-26 20:27:34.000000 anwdlserver-1.0.4/anwdlserver.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1098 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/resources/
--rw-r--r--   0 runner    (1001) docker     (123)      321 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/resources/anweddol-server.service
--rw-r--r--   0 runner    (1001) docker     (123)     3016 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/resources/config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 20:27:34.423325 anwdlserver-1.0.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     3456 2023-06-26 20:27:24.000000 anwdlserver-1.0.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/
+-rw-r--r--   0 runner    (1001) docker     (123)     1150 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/CONTRIBUTING
+-rw-r--r--   0 runner    (1001) docker     (123)    35129 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      140 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    44315 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2953 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/anwdlserver/
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19690 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4481 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/anwdlserver/core/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7332 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7935 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/crypto.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5629 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/database.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5926 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/sanitize.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22929 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/server.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1604 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13013 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/core/virtualization.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13088 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/process.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/anwdlserver/tools/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/tools/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4255 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/anwdlserver/tools/accesstk.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/anwdlserver.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    44315 2023-06-28 13:00:41.000000 anwdlserver-1.1.5/anwdlserver.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      710 2023-06-28 13:00:41.000000 anwdlserver-1.1.5/anwdlserver.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:00:41.000000 anwdlserver-1.1.5/anwdlserver.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-28 13:00:41.000000 anwdlserver-1.1.5/anwdlserver.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       74 2023-06-28 13:00:41.000000 anwdlserver-1.1.5/anwdlserver.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 13:00:41.000000 anwdlserver-1.1.5/anwdlserver.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1098 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)      321 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/resources/anweddol-server.service
+-rw-r--r--   0 runner    (1001) docker     (123)     3016 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/resources/config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:00:41.322038 anwdlserver-1.1.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     3477 2023-06-28 13:00:29.000000 anwdlserver-1.1.5/setup.py
```

### Comparing `anwdlserver-1.0.4/CONTRIBUTING` & `anwdlserver-1.1.5/CONTRIBUTING`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/LICENSE` & `anwdlserver-1.1.5/LICENSE`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/PKG-INFO` & `anwdlserver-1.1.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: anwdlserver
-Version: 1.0.4
+Version: 1.1.5
 Summary: The Anweddol server implementation
 Home-page: https://github.com/the-anweddol-project/Anweddol-server
 Author: The Anweddol project
 Author-email: The Anweddol project <the-anweddol-project@proton.me>
 License:  GNU GENERAL PUBLIC LICENSE
                                Version 3, 29 June 2007
         
@@ -701,17 +701,15 @@
 
 ## Introduction
 
 Anweddol is a client/server system providing temporary, SSH-controllable virtual machines to enhance anonymity online.
 
 It’s usefulness comes when someone wants to use a fully functional computer while being exposed to less dangers by using it remotely on a dedicated server, and by destroying it after use.
 
-## NOTE
-
-This is the beta version, some bugs or malfunctions can occur during usage. 
+**NOTE** : This is the beta version, some bugs or malfunctions can occur during usage
 
 ## Content
 
 This repository contains : 
 
 - The Anweddol server core features source code ;
 - The Anweddol server CLI implementation source code ;
@@ -759,19 +757,12 @@
 
 ## License
 
 This software is under the GNU general public license v3, available under any later version.
 
 This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.
 
-## Contact
-
-See the Anweddol community pages : 
-
-- Anweddol [reddit community page](https://www.reddit.com/r/Anweddol)
-- Join the Anweddol [Zulip organization](https://anweddol.zulipchat.com)
-
 ## Developer / Maintainer
 
 - Darnethal0z ([GitHub profile](https://github.com/Darnethal0z))
 
 *Copyright 2023 The Anweddol project*
```

### Comparing `anwdlserver-1.0.4/README.md` & `anwdlserver-1.1.5/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -8,17 +8,15 @@
 
 ## Introduction
 
 Anweddol is a client/server system providing temporary, SSH-controllable virtual machines to enhance anonymity online.
 
 It’s usefulness comes when someone wants to use a fully functional computer while being exposed to less dangers by using it remotely on a dedicated server, and by destroying it after use.
 
-## NOTE
-
-This is the beta version, some bugs or malfunctions can occur during usage. 
+**NOTE** : This is the beta version, some bugs or malfunctions can occur during usage
 
 ## Content
 
 This repository contains : 
 
 - The Anweddol server core features source code ;
 - The Anweddol server CLI implementation source code ;
@@ -66,19 +64,12 @@
 
 ## License
 
 This software is under the GNU general public license v3, available under any later version.
 
 This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.
 
-## Contact
-
-See the Anweddol community pages : 
-
-- Anweddol [reddit community page](https://www.reddit.com/r/Anweddol)
-- Join the Anweddol [Zulip organization](https://anweddol.zulipchat.com)
-
 ## Developer / Maintainer
 
 - Darnethal0z ([GitHub profile](https://github.com/Darnethal0z))
 
-*Copyright 2023 The Anweddol project*
+*Copyright 2023 The Anweddol project*
```

### Comparing `anwdlserver-1.0.4/anwdlserver/cli.py` & `anwdlserver-1.1.5/anwdlserver/cli.py`

 * *Files 14% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 """
 from datetime import datetime
 import daemon.pidfile
 import argparse
 import hashlib
 import daemon
 import signal
+import time
 import json
 import pwd
 import sys
 import os
 
 # Intern importation
 from .core.crypto import RSAWrapper, DEFAULT_RSA_KEY_SIZE
@@ -36,19 +37,14 @@
 # Constants definition
 CONFIG_FILE_PATH = (
     "C:\\Windows\\Anweddol\\config.yaml"
     if os.name == "nt"
     else "/etc/anweddol/config.yaml"
 )
 
-LOG_START_ERROR = "x>"
-LOG_START_INFO = "i>"
-LOG_START_WARNING = "!>"
-LOG_START_SUCCESS = "+>"
-
 LOG_JSON_STATUS_SUCCESS = "OK"
 LOG_JSON_STATUS_ERROR = "ERROR"
 
 
 class MainAnweddolServerCLI:
     def __init__(self):
         self.json = False
@@ -92,63 +88,59 @@
             if not self.config_content[0]:
                 raise ValueError(
                     f"Invalid configuration file :\n{json.dumps(self.config_content[1], indent=4)}"
                 )
 
             self.config_content = self.config_content[1]
 
+        except KeyboardInterrupt:
+            self.__log_stdout("")
+            exit(0)
+
         except Exception as E:
-            self.__log(
-                LOG_START_ERROR, f"Error during configuration file processing : {E}"
-            )
+            self.__log_stdout(f"Error during configuration file processing : {E}\n")
             exit(-1)
 
         try:
             getattr(self, args.command.replace("-", "_"))()
             exit(0)
 
+        except KeyboardInterrupt:
+            self.__log_stdout("")
+            exit(0)
+
         except Exception as E:
             if self.json:
                 self.__log_json(
                     LOG_JSON_STATUS_ERROR, "An error occured", data={"error": str(E)}
                 )
 
             else:
-                self.__log(LOG_START_ERROR, f"Error : {E}")
+                self.__log_stdout(f"An error occured : {E}\n")
 
             exit(-1)
 
-    def __log(self, start=None, message="", tabulation=False, bypass=False):
-        if bypass:
-            return
-
-        print(
-            ("    " if tabulation else "")
-            + (("\n" + start + " ") if start else "")
-            + message
-            + ("\n" if start else ""),
-            file=sys.stderr
-            if (start == LOG_START_ERROR or start == LOG_START_WARNING)
-            else sys.stdout,
-        )
+    def __log_stdout(self, message, bypass=False):
+        if not bypass:
+            print(message)
 
     def __log_json(self, status, message, data={}):
         print(json.dumps({"status": status, "message": message, "data": data}))
 
-    def __create_file_recursively(self, file_path, dir_folder_only=False):
+    def __create_file_recursively(self, path, is_folder=False):
         try:
-            os.makedirs(os.path.dirname(file_path))
+            os.makedirs(os.path.dirname(path) if not is_folder else path)
 
         except FileExistsError:
             pass
 
-        if dir_folder_only:
+        if is_folder:
             return
 
-        with open(file_path, "w") as fd:
+        with open(path, "w") as fd:
             fd.close()
 
     def start(self):
         parser = argparse.ArgumentParser(
             formatter_class=argparse.RawDescriptionHelpFormatter,
             description="\033[1m-> Start the server\033[0m",
             usage=f"{sys.argv[0]} start [OPT]",
@@ -160,90 +152,109 @@
         )
         parser.add_argument(
             "-d",
             help="execute the server in direct mode (parent terminal). Server will run as the actual effective user",
             action="store_true",
         )
         parser.add_argument(
+            "-y", "--assume-yes", help="answer 'y' to any prompts", action="store_true"
+        )
+        parser.add_argument(
+            "-n", "--assume-no", help="answer 'n' to any prompts", action="store_true"
+        )
+        parser.add_argument(
             "--skip-check", help="skip environment validity check", action="store_true"
         )
         parser.add_argument(
             "--json", help="print output in JSON format", action="store_true"
         )
         args = parser.parse_args(sys.argv[2:])
 
         self.json = args.json
 
         if os.path.exists(self.config_content["paths"].get("pid_file_path")):
-            raise RuntimeError("The server is already running")
+            self.__log_stdout(
+                f"A PID file already exists on {self.config_content['paths'].get('pid_file_path')}",
+                bypass=args.json
+            )
+            choice = (
+                input(" ↳ Kill the affiliated processus (y/n) ? : ")
+                if not args.assume_yes and not args.assume_no
+                else ("y" if args.assume_yes else "n")
+            )
 
-        if not args.skip_check:
-            self.__log(message="Verifying server environment ...", bypass=args.json)
+            if choice == "y":
+                with open(self.config_content["paths"].get("pid_file_path"), "r") as fd:
+                    os.kill(int(fd.read()), signal.SIGTERM)
+
+                while 1:
+                    if isPortBindable(self.config_content["server"].get("listen_port")):
+                        break
+
+                    time.sleep(1)
 
+            self.__log_stdout("", bypass=args.json)
+
+        if not args.skip_check:
             counter = 0
             errors_list = []
 
             if not isPortBindable(self.config_content["server"].get("listen_port")):
-                self.__log(
-                    message=f"\033[0;31mPort {self.config_content['server'].get('listen_port')} is not bindable\033[0m",
-                    tabulation=True,
+                self.__log_stdout(
+                    f"- Port {self.config_content['server'].get('listen_port')} is not bindable",
                     bypass=args.json,
                 )
 
                 counter += 1
                 errors_list.append(
                     f"Port {self.config_content['server'].get('listen_port')} is not bindable"
                 )
 
             if not isInterfaceExists(
                 self.config_content["container"].get("nat_interface_name")
             ):
-                self.__log(
-                    message=f"\033[0;31mInterface '{self.config_content['container'].get('nat_interface_name')}' does not exists on system\033[0m",
-                    tabulation=True,
+                self.__log_stdout(
+                    f"- Interface '{self.config_content['container'].get('nat_interface_name')}' does not exists on system",
                     bypass=args.json,
                 )
 
                 counter += 1
                 errors_list.append(
                     f"Interface '{self.config_content['container'].get('nat_interface_name')}' does not exists on system"
                 )
 
             if not isInterfaceExists(
                 self.config_content["container"].get("bridge_interface_name")
             ):
-                self.__log(
-                    message=f"\033[0;31mInterface '{self.config_content['container'].get('bridge_interface_name')}' does not exists on system\033[0m",
-                    tabulation=True,
+                self.__log_stdout(
+                    f"- Interface '{self.config_content['container'].get('bridge_interface_name')}' does not exists on system",
                     bypass=args.json,
                 )
 
                 counter += 1
                 errors_list.append(
                     f"Interface '{self.config_content['container'].get('bridge_interface_name')}' does not exists on system"
                 )
 
             if not isUserExists(self.config_content["server"].get("user")):
-                self.__log(
-                    message=f"\033[0;31mUser '{self.config_content['server'].get('user')}' does not exists on system\033[0m",
-                    tabulation=True,
+                self.__log_stdout(
+                    f"- User '{self.config_content['server'].get('user')}' does not exists on system",
                     bypass=args.json,
                 )
 
                 counter += 1
                 errors_list.append(
                     f"User '{self.config_content['server'].get('user')}' does not exists on system"
                 )
 
             if not os.path.exists(
                 self.config_content["paths"].get("container_iso_path")
             ):
-                self.__log(
-                    message=f"\033[0;31m{self.config_content['paths'].get('container_iso_path')} was not found on system\033[0m",
-                    tabulation=True,
+                self.__log_stdout(
+                    f"- {self.config_content['paths'].get('container_iso_path')} was not found on system",
                     bypass=args.json,
                 )
 
                 counter += 1
                 errors_list.append(
                     f"{self.config_content['paths'].get('container_iso_path')} was not found on system"
                 )
@@ -253,18 +264,15 @@
                     self.__log_json(
                         LOG_JSON_STATUS_SUCCESS,
                         "Check done",
                         data={"errors_recorded": counter, "errors_list": errors_list},
                     )
 
                 else:
-                    self.__log(
-                        LOG_START_INFO,
-                        f"Check done. {counter} error(s) recorded",
-                    )
+                    self.__log_stdout(f"\nCheck done. {counter} error(s) recorded\n", bypass=args.json)
 
                 return
 
             if counter != 0:
                 if args.json:
                     self.__log_json(
                         LOG_JSON_STATUS_ERROR,
@@ -274,43 +282,38 @@
                     return
 
                 else:
                     raise EnvironmentError(
                         f"{counter} error(s) detected on server environment"
                     )
 
-        self.__log(message="Starting server ...", bypass=args.json)
-
         if args.d:
-            self.__log(
-                message="INFO : Direct execution mode enabled. Use CTRL+C to stop the server.",
+            self.__log_stdout(
+                "Direct execution mode enabled. Use CTRL+C to stop the server.",
                 bypass=args.json,
             )
             launchServerProcess(self.config_content)
 
         else:
+            if args.json:
+                self.__log_json(
+                    LOG_JSON_STATUS_SUCCESS,
+                    "Server is started",
+                )
+
             # https://pypi.org/project/python-daemon/
             with daemon.DaemonContext(
                 uid=pwd.getpwnam(self.config_content["server"].get("user")).pw_uid,
                 gid=pwd.getpwnam(self.config_content["server"].get("user")).pw_gid,
                 pidfile=daemon.pidfile.PIDLockFile(
                     self.config_content["paths"].get("pid_file_path")
                 ),
             ):
                 launchServerProcess(self.config_content)
 
-            if args.json:
-                self.__log_json(LOG_JSON_STATUS_SUCCESS, "Server is started")
-                return
-
-            self.__log(
-                LOG_START_SUCCESS,
-                "Server is started",
-            )
-
     def stop(self):
         parser = argparse.ArgumentParser(
             formatter_class=argparse.RawDescriptionHelpFormatter,
             description="""\033[1m-> Stop the server\033[0m
 
 Sends a SIGINT signal to the server daemon to stop it.""",
             usage=f"{sys.argv[0]} stop [OPT]",
@@ -318,74 +321,78 @@
         parser.add_argument(
             "--json", help="print output in JSON format", action="store_true"
         )
         args = parser.parse_args(sys.argv[2:])
 
         self.json = args.json
 
-        self.__log(message="Stopping server ...", bypass=args.json)
-
         if not os.path.exists(self.config_content["paths"].get("pid_file_path")):
-            raise RuntimeError("The server is not running")
+            if args.json:
+                self.__log_json(
+                    LOG_JSON_STATUS_SUCCESS,
+                    "Server is already stopped"
+                )
+                return
+
+            self.__log_stdout("Server is already stopped\n")
+            return
 
         with open(self.config_content["paths"].get("pid_file_path"), "r") as fd:
             os.kill(int(fd.read()), signal.SIGTERM)
 
         if args.json:
             self.__log_json(LOG_JSON_STATUS_SUCCESS, "Server is stopped")
             return
 
-        self.__log(
-            LOG_START_SUCCESS,
-            "Server is stopped",
-        )
-
     def restart(self):
         parser = argparse.ArgumentParser(
             formatter_class=argparse.RawDescriptionHelpFormatter,
             description="\033[1m-> Restart the server\033[0m",
             usage=f"{sys.argv[0]} restart [OPT]",
         )
         parser.add_argument(
             "--json", help="print output in JSON format", action="store_true"
         )
         args = parser.parse_args(sys.argv[2:])
 
         self.json = args.json
 
-        self.__log(
-            message="Restarting server ...",
-            bypass=args.json,
-        )
-
         if not os.path.exists(self.config_content["paths"].get("pid_file_path")):
-            raise RuntimeError("The server is not running")
+            if args.json:
+                self.__log_json(
+                    LOG_JSON_STATUS_SUCCESS,
+                    "Server is already stopped"
+                )
+                return
+
+            self.__log_stdout("Server is already stopped\n")
+            return
 
         with open(self.config_content["paths"].get("pid_file_path"), "r") as fd:
             os.kill(int(fd.read()), signal.SIGTERM)
 
+            while 1:
+                if isPortBindable(self.config_content["server"].get("listen_port")):
+                    break
+
+                time.sleep(1)
+
+        if args.json:
+            self.__log_json(LOG_JSON_STATUS_SUCCESS, "Server is started")
+            return
+
         with daemon.DaemonContext(
             uid=pwd.getpwnam(self.config_content["server"].get("user")).pw_uid,
             gid=pwd.getpwnam(self.config_content["server"].get("user")).pw_gid,
             pidfile=daemon.pidfile.PIDLockFile(
                 self.config_content["paths"].get("pid_file_path")
             ),
         ):
             launchServerProcess(self.config_content)
 
-        if args.json:
-            self.__log_json(LOG_JSON_STATUS_SUCCESS, "Server is started")
-            return
-
-        self.__log(
-            LOG_START_SUCCESS,
-            "Server is started",
-            bypass=args.json,
-        )
-
     def access_tk(self):
         parser = argparse.ArgumentParser(
             formatter_class=argparse.RawDescriptionHelpFormatter,
             description="""\033[1m-> Manage access tokens\033[0m""",
             usage=f"{sys.argv[0]} access-tk [OPT]",
         )
         parser.add_argument("-a", help="add a new token entry", action="store_true")
@@ -431,126 +438,94 @@
             )
 
         access_token_manager = AccessTokenManager(
             self.config_content["paths"].get("access_tokens_database_path")
         )
 
         if args.a:
-            self.__log(
-                message="Creating access token ...",
-                bypass=args.json,
-            )
-
             new_entry_tuple = access_token_manager.addEntry(
                 disable=True if args.disabled else False
             )
 
             if args.json:
                 self.__log_json(
                     LOG_JSON_STATUS_SUCCESS,
                     "New access token created",
                     data={
                         "entry_id": new_entry_tuple[0],
                         "access_token": new_entry_tuple[2],
                     },
                 )
-
                 return
 
-            self.__log(
-                LOG_START_SUCCESS,
-                f"New access token created (Entry ID : {new_entry_tuple[0]})",
-            )
-            self.__log(
-                message=f"Token : {new_entry_tuple[2]}\n",
-                tabulation=True,
+            self.__log_stdout(
+                f"New access token created (Entry ID : {new_entry_tuple[0]})"
             )
+            self.__log_stdout(f" ↳ Token : {new_entry_tuple[2]}\n")
 
         elif args.l:
             if args.json:
                 entry_list = access_token_manager.listEntries()
 
                 self.__log_json(
                     LOG_JSON_STATUS_SUCCESS,
                     "Recorded entries ID",
                     data={"entry_list": entry_list},
                 )
 
                 return
 
-            self.__log(
-                message="Listing recorded entries ID ...",
-            )
-
             for entries in access_token_manager.listEntries():
-                self.__log(
-                    message=f"\n  - Entry ID {entries[0]}",
-                )
-                self.__log(
-                    message=f"     Created : {datetime.fromtimestamp(entries[1])}",
-                    tabulation=True,
-                )
-                self.__log(
-                    message=f"     Enabled : {bool(entries[2])}",
-                    tabulation=True,
-                )
-
-            self.__log(LOG_START_SUCCESS, "Done")
+                self.__log_stdout(f"Entry ID {entries[0]}")
+                self.__log_stdout(f" ↳ Created : {datetime.fromtimestamp(entries[1])}")
+                self.__log_stdout(f" ↳ Enabled : {bool(entries[2])}\n")
 
         else:
-
-            def __check_entry_existence(entry_id):
-                if not access_token_manager.getEntry(entry_id):
-                    access_token_manager.closeDatabase()
-                    raise LookupError(
-                        f"Entry ID {entry_id} does not exists on database"
+            if args.delete_entry:
+                if not access_token_manager.getEntry(args.delete_entry):
+                    self.__log_stdout(
+                        f"Entry ID {args.delete_entry} does not exists on database\n"
                     )
+                    return
 
-            if args.delete_entry:
-                __check_entry_existence(args.delete_entry)
                 access_token_manager.deleteEntry(args.delete_entry)
 
                 if args.json:
-                    self.__log_json(LOG_JSON_STATUS_SUCCESS, "Entry ID was deleted")
+                    self.__log_json(LOG_JSON_STATUS_SUCCESS, "Entry ID was deleted\n")
                     return
 
-                self.__log(
-                    LOG_START_SUCCESS,
-                    f"Entry ID {args.delete_entry} was deleted",
-                )
-
             elif args.enable_entry:
-                __check_entry_existence(args.enable_entry)
+                if not access_token_manager.getEntry(args.enable_entry):
+                    self.__log_stdout(
+                        f"Entry ID {args.enable_entry} does not exists on database\n"
+                    )
+                    return
+
                 access_token_manager.enableEntry(args.enable_entry)
 
                 if args.json:
                     self.__log_json(LOG_JSON_STATUS_SUCCESS, "Entry ID was enabled")
                     return
 
-                self.__log(
-                    LOG_START_SUCCESS,
-                    f"Entry ID {args.enable_entry} was enabled",
-                )
-
             else:
                 if args.disable_entry:
-                    __check_entry_existence(args.disable_entry)
+                    if not access_token_manager.getEntry(args.disable_entry):
+                        self.__log_stdout(
+                            f"Entry ID {args.disable_entry} does not exists on database\n"
+                        )
+                        return
+
                     access_token_manager.disableEntry(args.disable_entry)
 
                     if args.json:
                         self.__log_json(
                             LOG_JSON_STATUS_SUCCESS, "Entry ID was disabled"
                         )
                         return
 
-                    self.__log(
-                        LOG_START_SUCCESS,
-                        f"Entry ID {args.disable_entry} was disabled",
-                    )
-
         access_token_manager.closeDatabase()
 
     def regen_rsa(self):
         parser = argparse.ArgumentParser(
             description="\033[1m-> Regenerate RSA keys\033[0m",
             usage=f"{sys.argv[0]} regen-rsa [OPT]",
         )
@@ -563,27 +538,21 @@
         parser.add_argument(
             "--json", help="print output in JSON format", action="store_true"
         )
         args = parser.parse_args(sys.argv[2:])
 
         self.json = args.json
 
-        self.__log(
-            message=f"Generating {args.key_size if args.key_size else DEFAULT_RSA_KEY_SIZE} bytes RSA key pair ...",
-            bypass=args.json,
-        )
-
         new_rsa_wrapper = RSAWrapper(
             key_size=args.key_size if args.key_size else DEFAULT_RSA_KEY_SIZE
         )
 
         if not os.path.exists(self.config_content["paths"].get("rsa_keys_root_path")):
             self.__create_file_recursively(
-                self.config_content["paths"].get("rsa_keys_root_path"),
-                dir_folder_only=True,
+                self.config_content["paths"].get("rsa_keys_root_path"), is_folder=True
             )
 
         with open(
             self.config_content["paths"].get("rsa_keys_root_path")
             + "/"
             + PRIVATE_PEM_KEY_FILENAME,
             "w",
@@ -594,25 +563,23 @@
             self.config_content["paths"].get("rsa_keys_root_path")
             + "/"
             + PUBLIC_PEM_KEY_FILENAME,
             "w",
         ) as fd:
             fd.write(new_rsa_wrapper.getPublicKey().decode())
 
-        new_fingerprint = hashlib.sha256(new_rsa_wrapper.getPublicKey()).hexdigest()
-
         if args.json:
             self.__log_json(
                 LOG_JSON_STATUS_SUCCESS,
                 "RSA keys re-generated",
-                data={"fingerprint": new_fingerprint},
+                data={
+                    "fingerprint": hashlib.sha256(
+                        new_rsa_wrapper.getPublicKey()
+                    ).hexdigest()
+                },
             )
             return
 
-        self.__log(
-            LOG_START_SUCCESS,
-            "RSA keys re-generated",
-        )
-        self.__log(
-            message=f"Fingerprint : {new_fingerprint}",
-            tabulation=True,
+        self.__log_stdout("RSA keys re-generated")
+        self.__log_stdout(
+            f" ↳ Fingerprint : {hashlib.sha256(new_rsa_wrapper.getPublicKey()).hexdigest()}\n"
         )
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `anwdlserver-1.0.4/anwdlserver/config.py` & `anwdlserver-1.1.5/anwdlserver/config.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/client.py` & `anwdlserver-1.1.5/anwdlserver/core/client.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/crypto.py` & `anwdlserver-1.1.5/anwdlserver/core/crypto.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/database.py` & `anwdlserver-1.1.5/anwdlserver/core/database.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/sanitize.py` & `anwdlserver-1.1.5/anwdlserver/core/sanitize.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/server.py` & `anwdlserver-1.1.5/anwdlserver/core/server.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/util.py` & `anwdlserver-1.1.5/anwdlserver/core/util.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/core/virtualization.py` & `anwdlserver-1.1.5/anwdlserver/core/virtualization.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver/process.py` & `anwdlserver-1.1.5/anwdlserver/process.py`

 * *Files 22% similar despite different names*

```diff
@@ -23,250 +23,300 @@
 
 
 # Constants definition
 PUBLIC_PEM_KEY_FILENAME = "public_key.pem"
 PRIVATE_PEM_KEY_FILENAME = "private_key.pem"
 
 
-def launchServerProcess(config_content):
-    runtime_rsa_wrapper = None
+class AnweddolServerCLIProcess:
+    def __init__(self, config_content):
+        self.config_content = config_content
+        self.access_token_manager = None
+        self.runtime_rsa_wrapper = None
+        self.server_interface = None
+
+    def initializeProcess(self):
+        try:
+            logging.basicConfig(
+                format="%(asctime)s %(levelname)s : %(message)s",
+                filename=self.config_content["paths"].get("log_file_path"),
+                level=logging.INFO,
+                encoding="utf-8",
+                filemode="a",
+            )
+
+        except Exception as E:
+            raise RuntimeError(f"FATAL : Cannot load log file ({E})")
 
-    if not config_content["server"].get("enable_onetime_rsa_keys"):
-        if not os.path.exists(config_content["paths"].get("rsa_keys_root_path")):
-            os.mkdir(config_content["paths"].get("rsa_keys_root_path"))
-
-        if not os.path.exists(
-            config_content["paths"].get("rsa_keys_root_path")
-            + "/"
-            + PRIVATE_PEM_KEY_FILENAME
-        ):
-            runtime_rsa_wrapper = RSAWrapper()
-
-            with open(
-                config_content["paths"].get("rsa_keys_root_path")
-                + "/"
-                + PUBLIC_PEM_KEY_FILENAME,
-                "w",
-            ) as fd:
-                fd.write(runtime_rsa_wrapper.getPublicKey().decode())
-
-            with open(
-                config_content["paths"].get("rsa_keys_root_path")
-                + "/"
-                + PRIVATE_PEM_KEY_FILENAME,
-                "w",
-            ) as fd:
-                fd.write(runtime_rsa_wrapper.getPrivateKey().decode())
-
-        else:
-            runtime_rsa_wrapper = RSAWrapper(generate_key_pair=False)
-
-            with open(
-                config_content["paths"].get("rsa_keys_root_path")
-                + "/"
-                + PUBLIC_PEM_KEY_FILENAME,
-                "r",
-            ) as fd:
-                runtime_rsa_wrapper.setPublicKey(fd.read().encode())
-
-            with open(
-                config_content["paths"].get("rsa_keys_root_path")
-                + "/"
-                + PRIVATE_PEM_KEY_FILENAME,
-                "r",
-            ) as fd:
-                runtime_rsa_wrapper.setPrivateKey(fd.read().encode())
-
-    server_interface = ServerInterface(
-        bind_address=config_content["server"].get("bind_address"),
-        listen_port=config_content["server"].get("listen_port"),
-        client_timeout=config_content["server"].get("timeout"),
-        runtime_virtualization_interface=VirtualizationInterface(
-            config_content["paths"].get("container_iso_path"),
-            max_allowed_containers=config_content["container"].get(
-                "max_allowed_running_containers"
-            ),
-        ),
-        runtime_rsa_wrapper=runtime_rsa_wrapper,
-    )
-
-    logging.basicConfig(
-        format="%(asctime)s %(levelname)s : %(message)s",
-        filename=config_content["paths"].get("log_file_path"),
-        level=logging.INFO,
-        encoding="utf-8",
-        filemode="a",
-    )
-
-    if config_content["access_token"].get("enabled"):
-        access_token_manager = AccessTokenManager(
-            config_content["paths"].get("access_tokens_database_path")
-        )
-
-    @server_interface.on_created_container
-    def handle_container_creation(**kwargs):
-        container_instance = kwargs.get("container_instance")
-
-        logging.info(
-            f"[{kwargs['client_instance'].getID()}] Container {kwargs['container_instance'].getUUID()} was created"
-        )
-
-        container_instance.setMemory(
-            config_content["container"].get("container_memory")
-        )
-        container_instance.setVCPUs(config_content["container"].get("container_vcpus"))
-        container_instance.setNATInterfaceName(
-            config_content["container"].get("nat_interface_name")
-        )
-        container_instance.setBridgeInterfaceName(
-            config_content["container"].get("bridge_interface_name")
-        )
-        container_instance.setEndpointSSHAuthenticationCredentials(
-            config_content["container"].get("endpoint_username"),
-            config_content["container"].get("endpoint_password"),
-            config_content["container"].get("endpoint_listen_port"),
-        )
-        container_instance.startDomain()
-
-        logging.info(
-            f"[{kwargs['client_instance'].getID()}] Container {kwargs['container_instance'].getUUID()} domain is started"
-        )
-
-    @server_interface.on_connection
-    def handle_new_connection(**kwargs):
-        if config_content["ip_filter"].get("enabled"):
-            client_socket = kwargs.get("client_socket")
-
-            if "any" in config_content["ip_filter"].get("denied_ip_list"):
-                if client_socket.getpeername()[0] not in config_content[
-                    "ip_filter"
-                ].get("allowed_ip_list") and "any" not in config_content[
-                    "ip_filter"
-                ].get(
-                    "allowed_ip_list"
+        try:
+            logging.warning(
+                f"[INIT] Initializing server (running as '{getpass.getuser()}') ..."
+            )
+
+            logging.info("[INIT] Loading instance RSA key pair ...")
+            if not self.config_content["server"].get("enable_onetime_rsa_keys"):
+                if not os.path.exists(
+                    self.config_content["paths"].get("rsa_keys_root_path")
                 ):
-                    client_socket.shutdown(2)
-                    client_socket.close()
-                    logging.error(
-                        f"[unspec] Denied ip : {client_socket.getpeername()[0]} (IP not allowed)"
-                    )
+                    os.mkdir(self.config_content["paths"].get("rsa_keys_root_path"))
 
-            if client_socket.getpeername()[0] in config_content["ip_filter"].get(
-                "denied_ip_list"
-            ):
-                client_socket.shutdown(2)
-                client_socket.close()
-                logging.error(
-                    f"[unspec] Denied ip : {client_socket.getpeername()[0]} (Denied IP)"
+                if not os.path.exists(
+                    self.config_content["paths"].get("rsa_keys_root_path")
+                    + "/"
+                    + PRIVATE_PEM_KEY_FILENAME
+                ):
+                    self.runtime_rsa_wrapper = RSAWrapper()
+
+                    with open(
+                        self.config_content["paths"].get("rsa_keys_root_path")
+                        + "/"
+                        + PUBLIC_PEM_KEY_FILENAME,
+                        "w",
+                    ) as fd:
+                        fd.write(self.runtime_rsa_wrapper.getPublicKey().decode())
+
+                    with open(
+                        self.config_content["paths"].get("rsa_keys_root_path")
+                        + "/"
+                        + PRIVATE_PEM_KEY_FILENAME,
+                        "w",
+                    ) as fd:
+                        fd.write(self.runtime_rsa_wrapper.getPrivateKey().decode())
+
+                else:
+                    self.runtime_rsa_wrapper = RSAWrapper(generate_key_pair=False)
+
+                    with open(
+                        self.config_content["paths"].get("rsa_keys_root_path")
+                        + "/"
+                        + PUBLIC_PEM_KEY_FILENAME,
+                        "r",
+                    ) as fd:
+                        self.runtime_rsa_wrapper.setPublicKey(fd.read().encode())
+
+                    with open(
+                        self.config_content["paths"].get("rsa_keys_root_path")
+                        + "/"
+                        + PRIVATE_PEM_KEY_FILENAME,
+                        "r",
+                    ) as fd:
+                        self.runtime_rsa_wrapper.setPrivateKey(fd.read().encode())
+
+            logging.info("[INIT] Initializing server interface ...")
+            self.server_interface = ServerInterface(
+                bind_address=self.config_content["server"].get("bind_address"),
+                listen_port=self.config_content["server"].get("listen_port"),
+                client_timeout=self.config_content["server"].get("timeout"),
+                runtime_virtualization_interface=VirtualizationInterface(
+                    self.config_content["paths"].get("container_iso_path"),
+                    max_allowed_containers=self.config_content["container"].get(
+                        "max_allowed_running_containers"
+                    ),
+                ),
+                runtime_rsa_wrapper=self.runtime_rsa_wrapper,
+            )
+
+            if self.config_content["access_token"].get("enabled"):
+                logging.info("[INIT] Loading access token database ...")
+                self.access_token_manager = AccessTokenManager(
+                    self.config_content["paths"].get("access_tokens_database_path")
                 )
 
-            logging.info("[unspec] IP allowed")
+            logging.info("[INIT] Binding handlers routine ...")
+            @self.server_interface.on_created_container
+            def handle_container_creation(**kwargs):
+                container_instance = kwargs.get("container_instance")
 
-    @server_interface.on_client
-    def handle_new_client(**kwargs):
-        client_instance = kwargs.get("client_instance")
+                logging.info(
+                    f"(client ID {kwargs['client_instance'].getID()}) Container {kwargs['container_instance'].getUUID()} was created"
+                )
+
+                container_instance.setMemory(
+                    self.config_content["container"].get("container_memory")
+                )
+                container_instance.setVCPUs(
+                    self.config_content["container"].get("container_vcpus")
+                )
+                container_instance.setNATInterfaceName(
+                    self.config_content["container"].get("nat_interface_name")
+                )
+                container_instance.setBridgeInterfaceName(
+                    self.config_content["container"].get("bridge_interface_name")
+                )
+                container_instance.setEndpointSSHAuthenticationCredentials(
+                    self.config_content["container"].get("endpoint_username"),
+                    self.config_content["container"].get("endpoint_password"),
+                    self.config_content["container"].get("endpoint_listen_port"),
+                )
+                container_instance.startDomain()
 
-        logging.info(f"[{client_instance.getID()}] New client connected")
+                logging.info(
+                    f"(client ID {kwargs['client_instance'].getID()}) Container {kwargs['container_instance'].getUUID()} domain is started"
+                )
 
-    @server_interface.on_request
-    def handle_request(**kwargs):
-        client_instance = kwargs["client_instance"]
-        request_verb = client_instance.getStoredRequest()["verb"]
+            @self.server_interface.on_connection
+            def handle_new_connection(**kwargs):
+                if self.config_content["ip_filter"].get("enabled"):
+                    client_socket = kwargs.get("client_socket")
+
+                    if "any" in self.config_content["ip_filter"].get("denied_ip_list"):
+                        if client_socket.getpeername()[0] not in self.config_content[
+                            "ip_filter"
+                        ].get("allowed_ip_list") and "any" not in self.config_content[
+                            "ip_filter"
+                        ].get(
+                            "allowed_ip_list"
+                        ):
+                            client_socket.shutdown(2)
+                            client_socket.close()
+                            logging.error(
+                                f"(unspec) Denied ip : {client_socket.getpeername()[0]} (IP not allowed)"
+                            )
+
+                    if client_socket.getpeername()[0] in self.config_content[
+                        "ip_filter"
+                    ].get("denied_ip_list"):
+                        client_socket.shutdown(2)
+                        client_socket.close()
+                        logging.error(
+                            f"(unspec) Denied ip : {client_socket.getpeername()[0]} (Denied IP)"
+                        )
+
+                    logging.info("(unspec) IP allowed")
+
+            @self.server_interface.on_client
+            def handle_new_client(**kwargs):
+                client_instance = kwargs.get("client_instance")
 
-        logging.info(
-            f"[{kwargs['client_instance'].getID()}] Received {request_verb} request"
-        )
+                logging.info(
+                    f"(client ID {client_instance.getID()}) New client connected"
+                )
 
-        if config_content.get("access_token").get("enabled"):
-            client_request = client_instance.getStoredRequest()
+            @self.server_interface.on_request
+            def handle_request(**kwargs):
+                client_instance = kwargs["client_instance"]
+                request_verb = client_instance.getStoredRequest()["verb"]
 
-            if not client_request["parameters"].get("access_token"):
-                client_instance.sendResponse(
-                    False,
-                    RESPONSE_MSG_BAD_REQ,
-                    reason="Access token is required",
+                logging.info(
+                    f"(client ID {kwargs['client_instance'].getID()}) Received {request_verb} request"
                 )
-                client_instance.closeConnection()
+
+                if self.config_content.get("access_token").get("enabled"):
+                    client_request = client_instance.getStoredRequest()
+
+                    if not client_request["parameters"].get("access_token"):
+                        client_instance.sendResponse(
+                            False,
+                            RESPONSE_MSG_BAD_REQ,
+                            reason="Access token is required",
+                        )
+                        client_instance.closeConnection()
+                        logging.error(
+                            f"(client ID {client_instance.getID()}) Authorization failed (No access token provided)"
+                        )
+                        return -1
+
+                    if not self.access_token_manager.getEntryID(
+                        client_request["parameters"].get("access_token")
+                    ):
+                        client_instance.sendResponse(
+                            False, RESPONSE_MSG_BAD_AUTH, reason="Invalid access token"
+                        )
+                        client_instance.closeConnection()
+                        logging.error(
+                            f"(client ID {client_instance.getID()}) Authorization failed (Invalid access token)"
+                        )
+                        return -1
+
+                    logging.info(
+                        f"(client ID {client_instance.getID()}) Authorization success"
+                    )
+
+            @self.server_interface.on_stopped
+            def handle_stopped(**kwargs):
+                logging.info("Server is stopped")
+
+                if self.config_content["access_token"].get("enabled"):
+                    self.access_token_manager.closeDatabase()
+
+            @self.server_interface.on_started
+            def notify_started(**kwargs):
+                logging.info("Server is started")
+
+            @self.server_interface.on_created_endpoint_shell
+            def notify_endpoint_shell_creation(**kwargs):
+                logging.info(
+                    f"(client ID {kwargs.get('client_instance').getID()}) Endpoint shell opened"
+                )
+
+            @self.server_interface.on_destroyed_container
+            def notify_destroyed_container(**kwargs):
+                logging.info(
+                    f"(client ID {kwargs.get('client_instance').getID()}) Container {kwargs.get('container_instance').getUUID()} was destroyed"
+                )
+
+            @self.server_interface.on_client_closed
+            def notify_client_closed(**kwargs):
+                logging.info(
+                    f"(client ID {kwargs.get('client_instance').getID()}) Connection closed"
+                )
+
+            @self.server_interface.on_malformed_request
+            def notify_malformed_request(**kwargs):
                 logging.error(
-                    f"[{client_instance.getID()}] Authorization failed (No access token provided)"
+                    f"(client ID {kwargs.get('client_instance').getID()}) Received malformed request"
                 )
-                return
 
-            if not access_token_manager.getEntryID(
-                client_request["parameters"].get("access_token")
-            ):
-                client_instance.sendResponse(
-                    False, RESPONSE_MSG_BAD_AUTH, reason="Invalid access token"
+            @self.server_interface.on_unknown_verb
+            def notify_unknown_verb(**kwargs):
+                verb = kwargs.get("client_instance").getStoredRequest()["verb"]
+                logging.error(
+                    f"(client ID {kwargs.get('client_instance').getID()}) Received unknown verb : '{verb}'"
                 )
-                client_instance.closeConnection()
+
+            @self.server_interface.on_runtime_error
+            def notify_runtime_error(**kwargs):
                 logging.error(
-                    f"[{client_instance.getID()}] Authorization failed (Invalid access token)"
+                    "(client ID {}) {} : {}".format(
+                        kwargs["client_instance"].getID()
+                        if kwargs.get("client_instance")
+                        else "unspec",
+                        type(kwargs.get("ex_class")),
+                        kwargs.get("ex_class"),
+                    )
                 )
-                return
 
-            logging.info(f"[{client_instance.getID()}] Authorization success")
+            logging.info("[INIT] All done. Server is ready to use")
 
-    @server_interface.on_stopped
-    def handle_stopped(**kwargs):
-        logging.info("Server is stopped")
-
-        if config_content["access_token"].get("enabled"):
-            access_token_manager.closeDatabase()
-
-    @server_interface.on_started
-    def notify_started(**kwargs):
-        logging.info("Server is started")
-        logging.info(f"Running as {getpass.getuser()}")
-
-    @server_interface.on_created_endpoint_shell
-    def notify_endpoint_shell_creation(**kwargs):
-        logging.info(f"[{kwargs.get('client_instance').getID()}] Endpoint shell opened")
-
-    @server_interface.on_destroyed_container
-    def notify_destroyed_container(**kwargs):
-        logging.info(
-            f"[{kwargs.get('client_instance').getID()}] Container {kwargs.get('container_instance').getUUID()} was destroyed"
-        )
-
-    @server_interface.on_client_closed
-    def notify_client_closed(**kwargs):
-        logging.info(f"[{kwargs.get('client_instance').getID()}] Connection closed")
-
-    @server_interface.on_malformed_request
-    def notify_malformed_request(**kwargs):
-        logging.error(
-            f"[{kwargs.get('client_instance').getID()}] Received malformed request"
-        )
-
-    @server_interface.on_unknown_verb
-    def notify_unknown_verb(**kwargs):
-        verb = kwargs.get("client_instance").getStoredRequest()["verb"]
-        logging.error(
-            f"[{kwargs.get('client_instance').getID()}] Received unknown verb : '{verb}'"
-        )
-
-    @server_interface.on_runtime_error
-    def notify_runtime_error(**kwargs):
-        logging.error(
-            "[{}] {} : {}".format(
-                kwargs["client_instance"].getID()
-                if kwargs.get("client_instance")
-                else "unspec",
-                type(kwargs.get("ex_class")),
-                kwargs.get("ex_class"),
-            )
-        )
+        except Exception as E:
+            if self.access_token_manager:
+                self.access_token_manager.closeDatabase()
+
+            logging.error(f"[INIT] An error occured during server initialization : {E}")
+            return -1
 
-    def _start():
-        logging.warning("Starting server ...")
-        server_interface.startServer()
+    def startProcess(self):
+        logging.info("Starting server ...")
+        signal.signal(signal.SIGTERM, self.stopProcess)
+        signal.signal(signal.SIGINT, self.stopProcess)
+
+        self.server_interface.startServer()
 
     # 2 parameters are given on method call ?
     # Probably missing info here
-    def _stop(n=None, p=None):
-        logging.warning("Stopping server ...")
-        server_interface.stopServer()
+    def stopProcess(self, n=None, p=None):
+        logging.info("Stopping server ...")
+        if self.access_token_manager:
+            self.access_token_manager.closeDatabase()
+
+        self.server_interface.stopServer()
+
+
+def launchServerProcess(config_content):
+    process = AnweddolServerCLIProcess(config_content)
 
-    signal.signal(signal.SIGTERM, _stop)
-    signal.signal(signal.SIGINT, _stop)
+    try:
+        process.initializeProcess()
+        process.startProcess()
 
-    _start()
+    except KeyboardInterrupt:
+        process.stopProcess()
```

### Comparing `anwdlserver-1.0.4/anwdlserver/tools/accesstk.py` & `anwdlserver-1.1.5/anwdlserver/tools/accesstk.py`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/anwdlserver.egg-info/PKG-INFO` & `anwdlserver-1.1.5/anwdlserver.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: anwdlserver
-Version: 1.0.4
+Version: 1.1.5
 Summary: The Anweddol server implementation
 Home-page: https://github.com/the-anweddol-project/Anweddol-server
 Author: The Anweddol project
 Author-email: The Anweddol project <the-anweddol-project@proton.me>
 License:  GNU GENERAL PUBLIC LICENSE
                                Version 3, 29 June 2007
         
@@ -701,17 +701,15 @@
 
 ## Introduction
 
 Anweddol is a client/server system providing temporary, SSH-controllable virtual machines to enhance anonymity online.
 
 It’s usefulness comes when someone wants to use a fully functional computer while being exposed to less dangers by using it remotely on a dedicated server, and by destroying it after use.
 
-## NOTE
-
-This is the beta version, some bugs or malfunctions can occur during usage. 
+**NOTE** : This is the beta version, some bugs or malfunctions can occur during usage
 
 ## Content
 
 This repository contains : 
 
 - The Anweddol server core features source code ;
 - The Anweddol server CLI implementation source code ;
@@ -759,19 +757,12 @@
 
 ## License
 
 This software is under the GNU general public license v3, available under any later version.
 
 This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.
 
-## Contact
-
-See the Anweddol community pages : 
-
-- Anweddol [reddit community page](https://www.reddit.com/r/Anweddol)
-- Join the Anweddol [Zulip organization](https://anweddol.zulipchat.com)
-
 ## Developer / Maintainer
 
 - Darnethal0z ([GitHub profile](https://github.com/Darnethal0z))
 
 *Copyright 2023 The Anweddol project*
```

### Comparing `anwdlserver-1.0.4/anwdlserver.egg-info/SOURCES.txt` & `anwdlserver-1.1.5/anwdlserver.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/pyproject.toml` & `anwdlserver-1.1.5/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 build-backend = "setuptools.build_meta"
 
 [tools.setuptools]
 packages = ["anwdlserver", "anwdlserver.core", "anwdlserver.tools"]
 
 [project]
 name = "anwdlserver"
-version = "1.0.4"
+version = "1.1.5"
 description = "The Anweddol server implementation"
 authors = [
   { name="The Anweddol project", email="the-anweddol-project@proton.me" },
 ]
 classifiers = [
   "Development Status :: 4 - Beta",
   "License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)",
```

### Comparing `anwdlserver-1.0.4/resources/config.yaml` & `anwdlserver-1.1.5/resources/config.yaml`

 * *Files identical despite different names*

### Comparing `anwdlserver-1.0.4/setup.py` & `anwdlserver-1.1.5/setup.py`

 * *Files 15% similar despite different names*

```diff
@@ -7,21 +7,15 @@
 
 """
 from setuptools import setup
 from subprocess import Popen, PIPE
 import shutil
 import os
 
-
-def checkUserExistence(username):
-    with open("/etc/passwd", "r") as fd:
-        if username not in fd.read():
-            return False
-
-    return True
+ACTUAL_VERSION = "1.1.5"
 
 
 def executeCommand(command):
     Popen(command.split(" "), shell=False, stdout=PIPE, stderr=PIPE)
 
 
 print("[SETUP] Checking operating system ...")
@@ -42,25 +36,28 @@
         os.remove("/etc/anweddol/config.yaml")
 
     shutil.copy(
         os.path.dirname(os.path.realpath(__file__)) + "/resources/config.yaml",
         "/etc/anweddol/",
     )
 
-    # Add the user anweddol and create ACL entries for rwx 'anweddol' user permission
-    # on the /etc/anweddol directory
-    print("[SETUP (root)] Creating user 'anweddol' ...")
-    if checkUserExistence("anweddol"):
-        executeCommand("userdel -r anweddol")
+    print("[SETUP (root)] Creating uninstallation script ...")
+    shutil.copy(
+        os.path.dirname(os.path.realpath(__file__)) + "/anwdlserver-uninstall",
+        "/usr/local/bin",
+    )
 
+    # Add the user anweddol and rwx 'anweddol' user permission
+    # on the /etc/anweddol and the /var/log/anweddol directory
+    print("[SETUP (root)] Creating user 'anweddol' ...")
     executeCommand("useradd -s /sbin/nologin -M anweddol")
-    executeCommand("usermod -a -G libvirt anweddol")
-    executeCommand(
-        "setfacl -m u:anweddol:rwx /etc/anweddol /var/log/anweddol/runtime.txt/"
-    )
+    executeCommand("usermod -aG libvirt anweddol")
+
+    executeCommand("chown root.anweddol /etc/anweddol /var/log/anweddol")
+    executeCommand("chmod -R g+rwX /etc/anweddol /var/log/anweddol")
 
     # Create the systemctl service and enable it
     print("[SETUP (root)] Creating systemctl service ...")
     if os.path.exists("/usr/lib/systemd/system/anweddol-server.service"):
         os.remove("/usr/lib/systemd/system/anweddol-server.service")
 
     shutil.copy(
@@ -74,15 +71,15 @@
     print(
         "[SETUP] WARN : Non-root user detected, the installation limits to the 'anwdlserver' python package installation"
     )
 
 print("[SETUP] Installing Anweddol server package ...")
 setup(
     name="anwdlserver",
-    version="1.0.4",
+    version=ACTUAL_VERSION,
     description="The Anweddol server implementation",
     author="The Anweddol project",
     author_email="the-anweddol-project@proton.me",
     classifiers=[
         "Development Status :: 4 - Beta",
         "License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)",
         "Intended Audience :: Developers",
```


# Comparing `tmp/myalias-0.1.0.tar.gz` & `tmp/myalias-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "myalias-0.1.0.tar", max compression
+gzip compressed data, was "myalias-0.1.1.tar", max compression
```

## Comparing `myalias-0.1.0.tar` & `myalias-0.1.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
--rw-r--r--   0        0        0    35148 2023-06-17 15:52:58.410419 myalias-0.1.0/LICENSE
--rw-r--r--   0        0        0     3414 2023-06-17 15:52:58.410419 myalias-0.1.0/README.md
--rw-r--r--   0        0        0       22 2023-06-17 15:53:19.726690 myalias-0.1.0/myalias/__init__.py
--rw-r--r--   0        0        0     1360 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/cli.py
--rw-r--r--   0        0        0        0 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/commands/__init__.py
--rw-r--r--   0        0        0     1802 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/commands/add_alias_command.py
--rw-r--r--   0        0        0     1758 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/commands/list_alias_command.py
--rw-r--r--   0        0        0      908 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/commands/remove_alias_command.py
--rw-r--r--   0        0        0        0 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/__init__.py
--rw-r--r--   0        0        0        0 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/commands/__init__.py
--rw-r--r--   0        0        0     2172 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/commands/about_command.py
--rw-r--r--   0        0        0     3179 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/commands/setup_command.py
--rw-r--r--   0        0        0        0 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/interfaces/__init__.py
--rw-r--r--   0        0        0      213 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/interfaces/command_interface.py
--rw-r--r--   0        0        0      208 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/interfaces/service_interface.py
--rw-r--r--   0        0        0        0 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/__init__.py
--rw-r--r--   0        0        0      676 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/append_commands_cli_service.py
--rw-r--r--   0        0        0      546 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/create_folders_app_service.py
--rw-r--r--   0        0        0     2043 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/get_all_command_service.py
--rw-r--r--   0        0        0      723 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/get_path_application_service.py
--rw-r--r--   0        0        0      369 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/get_path_config_service.py
--rw-r--r--   0        0        0      359 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/get_version_app_service.py
--rw-r--r--   0        0        0      461 2023-06-17 15:52:58.410419 myalias-0.1.0/myalias/core/services/update_version_app_service.py
--rw-r--r--   0        0        0     1737 2023-06-17 15:53:19.710690 myalias-0.1.0/pyproject.toml
--rw-r--r--   0        0        0     4598 1970-01-01 00:00:00.000000 myalias-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0    35148 2023-06-28 01:35:07.779995 myalias-0.1.1/LICENSE
+-rw-r--r--   0        0        0     3543 2023-06-28 01:35:07.779995 myalias-0.1.1/README.md
+-rw-r--r--   0        0        0       22 2023-06-28 01:35:32.976187 myalias-0.1.1/myalias/__init__.py
+-rw-r--r--   0        0        0     2110 2023-06-28 01:35:07.779995 myalias-0.1.1/myalias/cli.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:35:07.779995 myalias-0.1.1/myalias/commands/__init__.py
+-rw-r--r--   0        0        0     1802 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/commands/add_alias_command.py
+-rw-r--r--   0        0        0     1758 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/commands/list_alias_command.py
+-rw-r--r--   0        0        0      908 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/commands/remove_alias_command.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/commands/__init__.py
+-rw-r--r--   0        0        0     2172 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/commands/about_command.py
+-rw-r--r--   0        0        0     3179 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/commands/setup_command.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/interfaces/__init__.py
+-rw-r--r--   0        0        0      213 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/interfaces/command_interface.py
+-rw-r--r--   0        0        0      208 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/interfaces/service_interface.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/__init__.py
+-rw-r--r--   0        0        0      676 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/append_commands_cli_service.py
+-rw-r--r--   0        0        0      546 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/create_folders_app_service.py
+-rw-r--r--   0        0        0     2043 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/get_all_command_service.py
+-rw-r--r--   0        0        0      723 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/get_path_application_service.py
+-rw-r--r--   0        0        0      369 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/get_path_config_service.py
+-rw-r--r--   0        0        0      359 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/get_version_app_service.py
+-rw-r--r--   0        0        0      461 2023-06-28 01:35:07.783995 myalias-0.1.1/myalias/core/services/update_version_app_service.py
+-rw-r--r--   0        0        0     1737 2023-06-28 01:35:32.960187 myalias-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0     4727 1970-01-01 00:00:00.000000 myalias-0.1.1/PKG-INFO
```

### Comparing `myalias-0.1.0/LICENSE` & `myalias-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/README.md` & `myalias-0.1.1/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -4,22 +4,26 @@
 
 <p align="center">
   <image src="./screenshots/about.png">
 </p>
 
 ## Install
 
-```
+```bash
   pip install myalias
 ```
 
 ## Setup
 
-```
+```bash
+
   myalias setup
+
+  # if the path is not defined add the following line to the configuration file
+  export PATH="$HOME/.local/bin:$PATH"
 ```
 
 - ### Commands
 
   - [help](#help)
   - [add](#add)
   - [remove](#remove)
```

### Comparing `myalias-0.1.0/myalias/cli.py` & `myalias-0.1.1/myalias/cli.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,10 +1,13 @@
 import typer
 from rich.console import Console
 
+from myalias.commands.add_alias_command import AddAliasCommand
+from myalias.commands.list_alias_command import ListAliasCommand
+from myalias.commands.remove_alias_command import RemoveAliasCommand
 from myalias.core.commands.about_command import AboutCommand
 from myalias.core.commands.setup_command import SetupCommand
 from myalias.core.services.append_commands_cli_service import (
     AppendCommandsCliService,
 )
 from myalias.core.services.update_version_app_service import (
     UpdateVersionAppService,
@@ -48,17 +51,38 @@
 
 @app.command(name='setup', rich_help_panel='Help and Others')
 def setup():
     """Setup initial to configure application."""
     SetupCommand().execute()
 
 
-@app.command(name='updateVersion', hidden=True)
-def updateVersion():
-    """Update version app."""
-    UpdateVersionAppService().execute()
+@app.command(name='add-alias', rich_help_panel='Commands')
+def add_alias(name, description, command):
+    """
+    Add alias to the application.
+    Args:
+        name (str): Name of command.
+        description (str): Description of command.
+        command (str): Command to execute.
+
+    """
+    AddAliasCommand().execute(name, description, command)
+
+
+@app.command(name='remove-alias', rich_help_panel='Commands')
+def remove_alias(name):
+    """
+    Remove alias to the application.
+    Args:
+        name (str): Name of command.
+    """
+    RemoveAliasCommand().execute(name)
+
+
+@app.command(name='list-alias', rich_help_panel='Commands')
+def list_alias():
+    """List alias to the application."""
+    ListAliasCommand().execute()
 
 
-AppendCommandsCliService().execute(app)
-
 if __name__ == '__main__':
     app()
```

### Comparing `myalias-0.1.0/myalias/commands/add_alias_command.py` & `myalias-0.1.1/myalias/commands/add_alias_command.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/commands/list_alias_command.py` & `myalias-0.1.1/myalias/commands/list_alias_command.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/commands/remove_alias_command.py` & `myalias-0.1.1/myalias/commands/remove_alias_command.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/core/commands/about_command.py` & `myalias-0.1.1/myalias/core/commands/about_command.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/core/commands/setup_command.py` & `myalias-0.1.1/myalias/core/commands/setup_command.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/core/services/append_commands_cli_service.py` & `myalias-0.1.1/myalias/core/services/append_commands_cli_service.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/core/services/create_folders_app_service.py` & `myalias-0.1.1/myalias/core/services/create_folders_app_service.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/core/services/get_all_command_service.py` & `myalias-0.1.1/myalias/core/services/get_all_command_service.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/myalias/core/services/get_path_application_service.py` & `myalias-0.1.1/myalias/core/services/get_path_application_service.py`

 * *Files identical despite different names*

### Comparing `myalias-0.1.0/pyproject.toml` & `myalias-0.1.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "myalias"
-version = "0.1.0"
+version = "0.1.1"
 description = ""
 authors = ["Thiago Melo <4thiagomelo5@gmail.com>"]
 license = "GPLv3"
 packages = [{include = "myalias"}]
 readme = "README.md"
 classifiers = [ 
   "Programming Language :: Python :: 3.10",
```

### Comparing `myalias-0.1.0/PKG-INFO` & `myalias-0.1.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: myalias
-Version: 0.1.0
+Version: 0.1.1
 Summary: 
 License: GPLv3
 Author: Thiago Melo
 Author-email: 4thiagomelo5@gmail.com
 Requires-Python: >=3.10,<4.0
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
@@ -33,22 +33,26 @@
 
 <p align="center">
   <image src="./screenshots/about.png">
 </p>
 
 ## Install
 
-```
+```bash
   pip install myalias
 ```
 
 ## Setup
 
-```
+```bash
+
   myalias setup
+
+  # if the path is not defined add the following line to the configuration file
+  export PATH="$HOME/.local/bin:$PATH"
 ```
 
 - ### Commands
 
   - [help](#help)
   - [add](#add)
   - [remove](#remove)
```


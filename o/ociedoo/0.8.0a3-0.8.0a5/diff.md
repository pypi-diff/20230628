# Comparing `tmp/ociedoo-0.8.0a3.tar.gz` & `tmp/ociedoo-0.8.0a5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ociedoo-0.8.0a3.tar", max compression
+gzip compressed data, was "ociedoo-0.8.0a5.tar", max compression
```

## Comparing `ociedoo-0.8.0a3.tar` & `ociedoo-0.8.0a5.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxr-xr-x   0        0        0        0 2023-06-27 13:23:15.371784 ociedoo-0.8.0a3/LICENSES/
--rw-r--r--   0        0        0     3502 2022-10-24 21:32:42.859135 ociedoo-0.8.0a3/README.md
--rw-r--r--   0        0        0     1076 2023-06-27 13:23:15.371784 ociedoo-0.8.0a3/ociedoo/__init__.py
--rw-r--r--   0        0        0      244 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/__main__.py
--rw-r--r--   0        0        0     1806 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/check.py
--rw-r--r--   0        0        0     1101 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/__init__.py
--rw-r--r--   0        0        0        0 2023-06-27 11:05:12.252786 ociedoo-0.8.0a3/ociedoo/cli/cmd/__init__.py
--rw-r--r--   0        0        0     1257 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/configuration.py
--rw-r--r--   0        0        0     1419 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/copy_db.py
--rw-r--r--   0        0        0     1323 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/drop_db.py
--rw-r--r--   0        0        0     1566 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/list_db.py
--rw-r--r--   0        0        0      738 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/list_module.py
--rw-r--r--   0        0        0     2266 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/main.py
--rw-r--r--   0        0        0     1448 2023-06-27 13:23:15.375784 ociedoo-0.8.0a3/ociedoo/cli/cmd/odooctl.py
--rw-r--r--   0        0        0     1645 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/cli/cmd/rename_db.py
--rw-r--r--   0        0        0     6694 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/cli/cmd/restore_db.py
--rw-r--r--   0        0        0     1930 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/cli/cmd/run.py
--rw-r--r--   0        0        0     3145 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/cli/cmd/set_password.py
--rw-r--r--   0        0        0    10757 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/cli/cmd/update_module.py
--rw-r--r--   0        0        0     1127 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/cli/tool.py
--rw-r--r--   0        0        0     5627 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/complete.py
--rw-r--r--   0        0        0      532 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/defaults/config
--rw-r--r--   0        0        0     9470 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/ociedoo/lib.py
--rw-r--r--   0        0        0     1441 2023-06-27 13:23:15.379784 ociedoo-0.8.0a3/pyproject.toml
--rw-r--r--   0        0        0     4640 2023-06-27 13:23:28.283065 ociedoo-0.8.0a3/setup.py
--rw-r--r--   0        0        0     4764 2023-06-27 13:23:28.283571 ociedoo-0.8.0a3/PKG-INFO
+drwxr-xr-x   0        0        0        0 2023-06-27 13:23:15.371784 ociedoo-0.8.0a5/LICENSES/
+-rw-r--r--   0        0        0     3502 2022-10-24 21:32:42.859135 ociedoo-0.8.0a5/README.md
+-rw-r--r--   0        0        0     1076 2023-06-28 11:54:26.496990 ociedoo-0.8.0a5/ociedoo/__init__.py
+-rw-r--r--   0        0        0      244 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/__main__.py
+-rw-r--r--   0        0        0     1806 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/check.py
+-rw-r--r--   0        0        0     1130 2023-06-28 10:14:09.980553 ociedoo-0.8.0a5/ociedoo/cli/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-27 11:05:12.252786 ociedoo-0.8.0a5/ociedoo/cli/cmd/__init__.py
+-rw-r--r--   0        0        0     1257 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/configuration.py
+-rw-r--r--   0        0        0     1419 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/copy_db.py
+-rw-r--r--   0        0        0     1323 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/drop_db.py
+-rw-r--r--   0        0        0     1566 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/list_db.py
+-rw-r--r--   0        0        0      738 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/list_module.py
+-rw-r--r--   0        0        0     2266 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/main.py
+-rw-r--r--   0        0        0     1448 2023-06-27 13:23:15.375784 ociedoo-0.8.0a5/ociedoo/cli/cmd/odooctl.py
+-rw-r--r--   0        0        0     1645 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/cli/cmd/rename_db.py
+-rw-r--r--   0        0        0     6585 2023-06-28 11:54:26.496990 ociedoo-0.8.0a5/ociedoo/cli/cmd/restore_db.py
+-rw-r--r--   0        0        0     1930 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/cli/cmd/run.py
+-rw-r--r--   0        0        0     3145 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/cli/cmd/set_password.py
+-rw-r--r--   0        0        0    10757 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/cli/cmd/update_module.py
+-rw-r--r--   0        0        0     1127 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/cli/tool.py
+-rw-r--r--   0        0        0     5627 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/complete.py
+-rw-r--r--   0        0        0      532 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/defaults/config
+-rw-r--r--   0        0        0     9470 2023-06-27 13:23:15.379784 ociedoo-0.8.0a5/ociedoo/lib.py
+-rw-r--r--   0        0        0     1441 2023-06-28 11:54:26.496990 ociedoo-0.8.0a5/pyproject.toml
+-rw-r--r--   0        0        0     4640 2023-06-28 11:54:37.376607 ociedoo-0.8.0a5/setup.py
+-rw-r--r--   0        0        0     4764 2023-06-28 11:54:37.377002 ociedoo-0.8.0a5/PKG-INFO
```

### Comparing `ociedoo-0.8.0a3/README.md` & `ociedoo-0.8.0a5/README.md`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/__init__.py` & `ociedoo-0.8.0a5/ociedoo/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 
 import os
 from pathlib import Path
 
 from prgconfig import PrgConfig
 
 __productname__ = "ociedoo"
-__version__ = "0.8.0-alpha.3"
+__version__ = "0.8.0-alpha.5"
 __license__ = "GPL-3.0-or-later"
 
 # Path for default value for config file
 PGRNAME = "ociedoo"
 DEFAULTSPATH = str(Path(__file__).parent / Path("defaults"))
 DEFAULT_CONF = str(Path(DEFAULTSPATH) / "config")
```

### Comparing `ociedoo-0.8.0a3/ociedoo/check.py` & `ociedoo-0.8.0a5/ociedoo/check.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/__init__.py` & `ociedoo-0.8.0a5/ociedoo/cli/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 # SPDX-FileCopyrightText: 2018 Coop IT Easy SC <https://coopiteasy.be>
 #
 # SPDX-License-Identifier: GPL-3.0-or-later
 
 """CLI commands"""
 
+from ociedoo.cli import tool
 from ociedoo.cli.cmd.configuration import configuration
 from ociedoo.cli.cmd.copy_db import copy_db
 from ociedoo.cli.cmd.drop_db import drop_db
 from ociedoo.cli.cmd.list_db import list_db
 from ociedoo.cli.cmd.list_module import list_module
 from ociedoo.cli.cmd.main import main
 from ociedoo.cli.cmd.odooctl import start_odoo, status_odoo, stop_odoo
```

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/configuration.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/configuration.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/copy_db.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/copy_db.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/drop_db.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/drop_db.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/list_db.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/list_db.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/list_module.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/list_module.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/main.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/main.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/odooctl.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/odooctl.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/rename_db.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/rename_db.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/restore_db.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/restore_db.py`

 * *Files 3% similar despite different names*

```diff
@@ -126,28 +126,23 @@
             ctx.echo(
                 "Error: file '%s' given in as 'posthook' in the "
                 "configuration file does not exist." % posthook,
                 err=True,
             )
             ctx.exit(1)
 
-    if filestore_backup:
-        filestore_path = cli.tool.get_filestore_path(ctx, database)
-        if filestore_path.exists():
-            ctx.fail("A filestore named {0} already exists.".format(database))
-
     # Ask for a password if needed
     if not no_pwd:
         pwd = click.prompt(
             "New password for user '%s'" % login,
             hide_input=True,
             confirmation_prompt=True,
         )
 
-    # Save or drop db
+    # Save or drop db and fs
     if database in lib.get_all_db():
         if save:
             try:
                 ctx.invoke(cli.rename_db, oldname=database, newname=save)
             except click.exceptions.Exit as err:
                 if err.exit_code:
                     raise
@@ -169,14 +164,15 @@
                 click.echo(err.stderr, err=True)
                 ctx.exit(1)
         else:
             ctx.fail(
                 "Database '%s' already exists. Look at --force, "
                 "--autosave or --save options." % database
             )
+
     # Create new db
     try:
         sh.createdb(database, _done=cli.tool.cb_print_cmd)
     except sh.ErrorReturnCode as err:
         click.echo("Error: ", nl=False, err=True)
         click.echo(err.stderr, err=True)
         ctx.exit(1)
@@ -207,13 +203,15 @@
 
     # Set admin password and admin login
     if not no_pwd:
         ctx.invoke(
             cli.set_password, database=database, login=login, password=pwd
         )
 
+    # Restore filestore
     if filestore_backup:
+        filestore_path = cli.tool.get_filestore_path(ctx, database)
         click.echo("Restoring filestore...")
         try:
             lib.restore_filestore_backup(filestore_backup, filestore_path)
         except ValueError as e:
             ctx.fail(e)
```

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/run.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/run.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/set_password.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/set_password.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/cmd/update_module.py` & `ociedoo-0.8.0a5/ociedoo/cli/cmd/update_module.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/cli/tool.py` & `ociedoo-0.8.0a5/ociedoo/cli/tool.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/complete.py` & `ociedoo-0.8.0a5/ociedoo/complete.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/defaults/config` & `ociedoo-0.8.0a5/ociedoo/defaults/config`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/ociedoo/lib.py` & `ociedoo-0.8.0a5/ociedoo/lib.py`

 * *Files identical despite different names*

### Comparing `ociedoo-0.8.0a3/pyproject.toml` & `ociedoo-0.8.0a5/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 
 [tool.isort]
 profile = "black"
 line_length = 79
 
 [tool.poetry]
 name = "ociedoo"
-version = "0.8.0-alpha.3"
+version = "0.8.0-alpha.5"
 description = "CLI tool to simplify the management of Odoo"
 authors = ["Coop IT Easy SCRLfs <remy@coopiteasy.be>"]
 maintainers = ["Rémy Taymans <remy@coopiteasy.be>"]
 license = "GPL-3.0-or-later"
 readme = "README.md"
 repository = "https://gitlab.com/coopiteasy/ociedoo"
 keywords = ["cli", "odoo", "coopiteasy"]
```

### Comparing `ociedoo-0.8.0a3/setup.py` & `ociedoo-0.8.0a5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,15 @@
  'sh>=1.12,<2.0']
 
 entry_points = \
 {'console_scripts': ['ociedoo = ociedoo.cli:main']}
 
 setup_kwargs = {
     'name': 'ociedoo',
-    'version': '0.8.0a3',
+    'version': '0.8.0a5',
     'description': 'CLI tool to simplify the management of Odoo',
     'long_description': '[![pipeline status](https://gitlab.com/coopiteasy/ociedoo/badges/master/pipeline.svg)](https://gitlab.com/coopiteasy/ociedoo)\n\nociedoo\n=======\n\nociedoo is a cli collection of tools to simplify the management of odoo\non a server.\n\nSee help for more info.\n\n\nInstallation\n------------\n\nociedoo needs python version >= 3.5. So ensure `pip` points to a correct\nversion of python. To do this run:\n```shell\npip --version\n```\n\nIt should return something like:\n```\npip xx.y from /path/to/pip (python 3.5)\n```\n\nIf `pip` doesn\'t run python >=3.5, try running `pip3` which is on\ncertain distribution the `pip` for python >=3.\n\n\n### Dependencies\n\nociedoo uses external programs via the shell. Be sure they are installed\nand accessible for the current user.\n\n- psql\n- createdb\n- dropdb\n- systemctl\n\n\n### Install for a specific user\n\n\n#### Installation with pipx (recommended python >= 3.6)\n\n```shell\npipx install ociedoo\n```\n\n\n#### Installation with pipsi (recommended python < 3.5)\n\n```shell\npipsi install ociedoo\n```\n\n\n#### Install with pip\n\n```shell\npip install --user ociedoo\n```\n\n\n### Install system wide (for all users)\n\n\n#### Install with pipx (recommended python >= 3.6)\n\nFirst install pipx if not already installed:\n```shell\nsudo pip install pipx\n```\n\nThen install ociedoo:\n```shell\nsudo PIPX_HOME=/usr/local PIPX_BIN_DIR=/usr/local/bin pipx install ociedoo\n```\n\n\n#### Install with pipsi (recommended python < 3.6)\n\nFirst install pipsi, if not already installed:\n```shell\nsudo curl https://raw.githubusercontent.com/mitsuhiko/pipsi/master/get-pipsi.py | sudo python3 - --bin-dir /usr/local/bin --home /usr/local/venvs --no-modify-path\n```\n\nThen install ociedoo:\n```shell\nsudo pipsi --bin-dir /usr/local/bin --home /usr/local/venvs install ociedoo\n```\n\n\n#### Install with pip\n```shell\nsudo pip install ociedoo\n```\n\n\n### Enable bash completion\n\n\n#### Bash completion for a specific user\n\nTo enable bash completion add the following in your `.bashrc`:\n\n```shell\n# ociedoo\n# =======\nif command -v ociedoo >/dev/null; then\n    eval "$(_OCIEDOO_COMPLETE=source ociedoo)"\nfi\n```\n\nOr if you use zsh, add this to your `.zshrc`:\n```shell\n# ociedoo\n# =======\nif command -v ociedoo >/dev/null; then\n    eval "$(_OCIEDOO_COMPLETE=source_zsh ociedoo)"\nfi\n```\n\n\n#### Bash completion system wide (for all users)\n\nTo enable bash completion add the following in `/etc/bash.bashrc`:\n```shell\n# ociedoo\n# =======\nif command -v ociedoo >/dev/null; then\n    eval "$(_OCIEDOO_COMPLETE=source ociedoo)"\nfi\n```\n\nOr if you use zsh, add this to your `/etc/zsh/zshrc`:\n```shell\n# ociedoo\n# =======\nif command -v ociedoo >/dev/null; then\n    eval "$(_OCIEDOO_COMPLETE=source_zsh ociedoo)"\nfi\n```\n\n\nUpgrade\n-------\n\n\n### Upgrade for a specific user\n\n\n#### Upgrade with pipx (recommended python >= 3.6)\n\n```shell\npipx upgrade ociedoo\n```\n\n\n#### Upgrade with pipsi (recommended python < 3.5)\n\n```shell\npipsi upgrade ociedoo\n```\n\n\n#### Upgrade with pip\n\n```shell\npip install --user --upgrade ociedoo\n```\n\n\n### Upgrade system wide (for all users)\n\n\n#### Upgrade with pipx (recommended python >= 3.6)\n\n```shell\nsudo PIPX_HOME=/usr/local PIPX_BIN_DIR=/usr/local/bin pipx upgrade ociedoo\n```\n\n\n#### Upgrade with pipsi (recommended python < 3.5)\n\n```shell\nsudo pipsi --bin-dir /usr/local/bin --home /usr/local/venvs upgrade ociedoo\n```\n\n\n#### Upgrade with pip\n\n```shell\nsudo pip install --upgrade ociedoo\n```\n\nBuild and publish\n-----------------\n\nFirst do not forget to upgrade version. Then:\n\n```shell\npoetry build\npoetry publish -u coopiteasy\n',
     'author': 'Coop IT Easy SCRLfs',
     'author_email': 'remy@coopiteasy.be',
     'maintainer': 'Rémy Taymans',
     'maintainer_email': 'remy@coopiteasy.be',
     'url': 'https://gitlab.com/coopiteasy/ociedoo',
```

### Comparing `ociedoo-0.8.0a3/PKG-INFO` & `ociedoo-0.8.0a5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ociedoo
-Version: 0.8.0a3
+Version: 0.8.0a5
 Summary: CLI tool to simplify the management of Odoo
 Home-page: https://gitlab.com/coopiteasy/ociedoo
 License: GPL-3.0-or-later
 Keywords: cli,odoo,coopiteasy
 Author: Coop IT Easy SCRLfs
 Author-email: remy@coopiteasy.be
 Maintainer: Rémy Taymans
```


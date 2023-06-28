# Comparing `tmp/viur_cli-1.0.4.tar.gz` & `tmp/viur_cli-1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "viur_cli-1.0.4.tar", last modified: Thu May  4 17:24:02 2023, max compression
+gzip compressed data, was "viur_cli-1.0.5.tar", last modified: Wed Jun 28 06:55:25 2023, max compression
```

## Comparing `viur_cli-1.0.4.tar` & `viur_cli-1.0.5.tar`

### file list

```diff
@@ -1,49 +1,49 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.661356 viur_cli-1.0.4/
--rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-05-04 17:23:54.000000 viur_cli-1.0.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     6237 2023-05-04 17:24:02.661356 viur_cli-1.0.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5701 2023-05-04 17:23:54.000000 viur_cli-1.0.4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      104 2023-05-04 17:23:54.000000 viur_cli-1.0.4/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-05-04 17:24:02.665356 viur_cli-1.0.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      507 2023-05-04 17:23:54.000000 viur_cli-1.0.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.657356 viur_cli-1.0.4/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.661356 viur_cli-1.0.4/src/viur_cli/
--rw-r--r--   0 runner    (1001) docker     (123)      239 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4816 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/build.py
--rw-r--r--   0 runner    (1001) docker     (123)     1014 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)    10024 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     6301 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/deploy.py
--rw-r--r--   0 runner    (1001) docker     (123)     1367 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/flare.py
--rw-r--r--   0 runner    (1001) docker     (123)     6023 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/install.py
--rw-r--r--   0 runner    (1001) docker     (123)     4361 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/local.py
--rw-r--r--   0 runner    (1001) docker     (123)      738 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/npm.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.661356 viur_cli-1.0.4/src/viur_cli/scriptor/
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10180 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/cli.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.661356 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/
--rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3898 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/csvwriter.py
--rw-r--r--   0 runner    (1001) docker     (123)     5877 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/dialog.py
--rw-r--r--   0 runner    (1001) docker     (123)     2069 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)     5720 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/module.py
--rw-r--r--   0 runner    (1001) docker     (123)     3490 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/network.py
--rw-r--r--   0 runner    (1001) docker     (123)      380 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/progressbar.py
--rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/readers.py
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     6031 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/viur.py
--rw-r--r--   0 runner    (1001) docker     (123)     6883 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/writer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.661356 viur_cli-1.0.4/src/viur_cli/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scripts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9803 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scripts/flare.py
--rw-r--r--   0 runner    (1001) docker     (123)     4470 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scripts/get_pyodide.py
--rw-r--r--   0 runner    (1001) docker     (123)     3781 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/scripts/viur_2to3.py
--rw-r--r--   0 runner    (1001) docker     (123)     1482 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/setup.py
--rw-r--r--   0 runner    (1001) docker     (123)     1907 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/tool.py
--rw-r--r--   0 runner    (1001) docker     (123)     1556 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-05-04 17:23:54.000000 viur_cli-1.0.4/src/viur_cli/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-04 17:24:02.661356 viur_cli-1.0.4/src/viur_cli.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6237 2023-05-04 17:24:02.000000 viur_cli-1.0.4/src/viur_cli.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1213 2023-05-04 17:24:02.000000 viur_cli-1.0.4/src/viur_cli.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-04 17:24:02.000000 viur_cli-1.0.4/src/viur_cli.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      166 2023-05-04 17:24:02.000000 viur_cli-1.0.4/src/viur_cli.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       96 2023-05-04 17:24:02.000000 viur_cli-1.0.4/src/viur_cli.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-05-04 17:24:02.000000 viur_cli-1.0.4/src/viur_cli.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.939722 viur_cli-1.0.5/
+-rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-06-28 06:55:15.000000 viur_cli-1.0.5/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     6368 2023-06-28 06:55:25.939722 viur_cli-1.0.5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5832 2023-06-28 06:55:15.000000 viur_cli-1.0.5/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-28 06:55:15.000000 viur_cli-1.0.5/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     1004 2023-06-28 06:55:25.939722 viur_cli-1.0.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      507 2023-06-28 06:55:15.000000 viur_cli-1.0.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.931722 viur_cli-1.0.5/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.935722 viur_cli-1.0.5/src/viur_cli/
+-rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4816 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/build.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1014 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10024 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6564 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/deploy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1367 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/flare.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6023 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/install.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6145 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/local.py
+-rw-r--r--   0 runner    (1001) docker     (123)      738 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/npm.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.935722 viur_cli-1.0.5/src/viur_cli/scriptor/
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10180 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.939722 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/
+-rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3898 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/csvwriter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5877 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/dialog.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2069 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5720 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/module.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3490 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/network.py
+-rw-r--r--   0 runner    (1001) docker     (123)      380 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/progressbar.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/readers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6031 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/viur.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6883 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/writer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.939722 viur_cli-1.0.5/src/viur_cli/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scripts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9803 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scripts/flare.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4470 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scripts/get_pyodide.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3781 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/scripts/viur_2to3.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1482 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/setup.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1907 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/tool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1556 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 06:55:15.000000 viur_cli-1.0.5/src/viur_cli/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:55:25.935722 viur_cli-1.0.5/src/viur_cli.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6368 2023-06-28 06:55:25.000000 viur_cli-1.0.5/src/viur_cli.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1213 2023-06-28 06:55:25.000000 viur_cli-1.0.5/src/viur_cli.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:55:25.000000 viur_cli-1.0.5/src/viur_cli.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      166 2023-06-28 06:55:25.000000 viur_cli-1.0.5/src/viur_cli.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-28 06:55:25.000000 viur_cli-1.0.5/src/viur_cli.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 06:55:25.000000 viur_cli-1.0.5/src/viur_cli.egg-info/top_level.txt
```

### Comparing `viur_cli-1.0.4/LICENSE` & `viur_cli-1.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/PKG-INFO` & `viur_cli-1.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: viur_cli
-Version: 1.0.4
+Version: 1.0.5
 Summary: Command-line interface for ViUR application maintenance.
 Home-page: https://github.com/viur-framework/viur-cli
 Author: Andreas H. Kelch
 Author-email: ak@mausbrand.de
 Project-URL: Bug Tracker, https://github.com/viur-framework/viur-cli/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
@@ -60,14 +60,19 @@
 
 ```sh
 $ viur run [target]
 ```
 run the appserver and start your app locally. You may specify a target projectID.
 
 ```sh
+$ viur check {--dev}
+```
+Runs a security check for the python environment and for each npm project registered under builds.
+
+```sh
 $ viur deploy {app|index} [target]
 ```
 you can deploy the app or the index.yaml to a google cloud project target of your choice, though the target is optional.
 By default this would be the projectID you gave when initializing the project, but you can add targets to the project.json
 if you would like to have an additional system for testing for example.
 
 ```sh
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: viur_cli Version: 1.0.4 Summary: Command-line
+Metadata-Version: 2.1 Name: viur_cli Version: 1.0.5 Summary: Command-line
 interface for ViUR application maintenance. Home-page: https://github.com/viur-
 framework/viur-cli Author: Andreas H. Kelch Author-email: ak@mausbrand.de
 Project-URL: Bug Tracker, https://github.com/viur-framework/viur-cli/issues
 Classifier: Programming Language :: Python :: 3 Classifier: Operating System ::
 OS Independent Classifier: License :: OSI Approved :: MIT License Requires-
 Python: >=3.10 Description-Content-Type: text/markdown License-File: LICENSE
                       [A hexagonal logo of the viur-cli]
@@ -18,60 +18,61 @@
 project folder, clone the base project and then call `viur init` to prepare a
 project.json you can use this to get started quickly with a new viur project
 from scratch. ```sh $ viur init ``` this will initialize a new project in the
 current folder, you will be asked a couple of questions like if you would like
 to create a new project.json file, what components should be preinstalled and
 what the projectID of your application will be. ```sh $ viur run [target] ```
 run the appserver and start your app locally. You may specify a target
-projectID. ```sh $ viur deploy {app|index} [target] ``` you can deploy the app
-or the index.yaml to a google cloud project target of your choice, though the
-target is optional. By default this would be the projectID you gave when
-initializing the project, but you can add targets to the project.json if you
-would like to have an additional system for testing for example. ```sh $ viur
-install {vi|scriptor} ``` ask viur-cli to install either vi or the scriptor
-into your project ```sh $ viur flare {release|debug|watch} [appname] ``` if you
-have a flare component in your project you can build a `release`, start a
-`debug` helper or `watch` the flare app for code changes which will
-automatically rebuild it when you save your changes. ```sh $ viur flare watch
-vi ``` this would watch the vi flare app for changes and automatically rebuild
-it in case of changes. ```sh $ viur build release ``` build all flare and npm
-apps and produce a release that can be deployed ```sh $ viur build app
-[appname] ``` build a specific app ```sh $ viur env ``` check the environment
-you are in right now, show versions of viur-cli, viur-core and vi etc. ```sh $
-viur project {add|remove|list|addFlare|scanNpm} ``` with this you can manage
-your project.json or generate a new one. You can add or remove targets to/from
-the project.json, list what has been added to the project.json, add a flare
-application with `addFlare` to be built when running `viur build release` or
-walk through the projects sources with `scanNpm` and identify all npm
-applications to be added ## Viur scripting interface There is a new core
-component that enables us to pull and push python scripts from/to a deployed
-application and run these in a sandbox or even locally. The GUI version is
-called scriptor and can be accessed via a webinterface, but viur-cli also has a
-cli for this: ```sh $ viur script {configure|pull|push|run|setup} ``` Commands:
-- `configure` Manage configuration settings. - `pull` Pull contents from server
-to working_dir. - `push` Push contents of working_dir to server. - `run`
-Locally run a script located in the working_dir. - `setup` Setup user session
-with a given username and... ## Packaged tools In order to use the packaged
-tools, you can run: ```sh $ viur tool {2to3|flare|pyodide|ssl-fix} ``` Scripts:
-- `2to3` viur porting script - `flare` flare build script - `pyodide` run the
-get_pyodide command - `ssl-fix` ssl fix for MacOS for example the 2to3 script
-helps porting viur2 project to viur3, it can be used to automatically rename
-some things that are deprecated in viur3 as well, so you can use it whenever a
-new core version is released for viur3 projects as well: ```sh $ viur tool 2to3
--d . ``` will dry-run the script in the current directory and not make any
-changes, only suggestions. If you want to make the changes, leave out the -
-d argument and if you are a daring go-getter and like to live dangerously,
-replace the -d with -x, which will write the suggested changes without making a
-backup of the changed files. ## Development If you want to hack `viur-cli`,
-clone this repository next to the folder of your ViUR project. ```sh $ git
-clone git@github.com:viur-framework/viur-cli.git $ ls -1 viur-cli your-project
-``` Then, add it to your project as an editable dependency using ```sh $ cd
-your-project $ pipenv install --dev --editable ../viur-cli ``` ## Dependencies
-viur-cli depends on * [click](https://click.palletsprojects.com/) *
-[app_server](https://github.com/XeoN-GHMB/app_server) * [pipfile-requirements]
-(https://github.com/frostming/pipfile-requirements) * [watchgod](https://
-github.com/samuelcolvin/watchgod) * [python-minifier](https://github.com/
-dflook/python-minifier) ## License Copyright Â© 2023 by Mausbrand
-Informationssysteme GmbH.
+projectID. ```sh $ viur check {--dev} ``` Runs a security check for the python
+environment and for each npm project registered under builds. ```sh $ viur
+deploy {app|index} [target] ``` you can deploy the app or the index.yaml to a
+google cloud project target of your choice, though the target is optional. By
+default this would be the projectID you gave when initializing the project, but
+you can add targets to the project.json if you would like to have an additional
+system for testing for example. ```sh $ viur install {vi|scriptor} ``` ask
+viur-cli to install either vi or the scriptor into your project ```sh $ viur
+flare {release|debug|watch} [appname] ``` if you have a flare component in your
+project you can build a `release`, start a `debug` helper or `watch` the flare
+app for code changes which will automatically rebuild it when you save your
+changes. ```sh $ viur flare watch vi ``` this would watch the vi flare app for
+changes and automatically rebuild it in case of changes. ```sh $ viur build
+release ``` build all flare and npm apps and produce a release that can be
+deployed ```sh $ viur build app [appname] ``` build a specific app ```sh $ viur
+env ``` check the environment you are in right now, show versions of viur-cli,
+viur-core and vi etc. ```sh $ viur project {add|remove|list|addFlare|scanNpm}
+``` with this you can manage your project.json or generate a new one. You can
+add or remove targets to/from the project.json, list what has been added to the
+project.json, add a flare application with `addFlare` to be built when running
+`viur build release` or walk through the projects sources with `scanNpm` and
+identify all npm applications to be added ## Viur scripting interface There is
+a new core component that enables us to pull and push python scripts from/to a
+deployed application and run these in a sandbox or even locally. The GUI
+version is called scriptor and can be accessed via a webinterface, but viur-cli
+also has a cli for this: ```sh $ viur script {configure|pull|push|run|setup}
+``` Commands: - `configure` Manage configuration settings. - `pull` Pull
+contents from server to working_dir. - `push` Push contents of working_dir to
+server. - `run` Locally run a script located in the working_dir. - `setup`
+Setup user session with a given username and... ## Packaged tools In order to
+use the packaged tools, you can run: ```sh $ viur tool {2to3|flare|pyodide|ssl-
+fix} ``` Scripts: - `2to3` viur porting script - `flare` flare build script -
+`pyodide` run the get_pyodide command - `ssl-fix` ssl fix for MacOS for example
+the 2to3 script helps porting viur2 project to viur3, it can be used to
+automatically rename some things that are deprecated in viur3 as well, so you
+can use it whenever a new core version is released for viur3 projects as well:
+```sh $ viur tool 2to3 -d . ``` will dry-run the script in the current
+directory and not make any changes, only suggestions. If you want to make the
+changes, leave out the -d argument and if you are a daring go-getter and like
+to live dangerously, replace the -d with -x, which will write the suggested
+changes without making a backup of the changed files. ## Development If you
+want to hack `viur-cli`, clone this repository next to the folder of your ViUR
+project. ```sh $ git clone git@github.com:viur-framework/viur-cli.git $ ls -
+1 viur-cli your-project ``` Then, add it to your project as an editable
+dependency using ```sh $ cd your-project $ pipenv install --dev --editable ../
+viur-cli ``` ## Dependencies viur-cli depends on * [click](https://
+click.palletsprojects.com/) * [app_server](https://github.com/XeoN-GHMB/
+app_server) * [pipfile-requirements](https://github.com/frostming/pipfile-
+requirements) * [watchgod](https://github.com/samuelcolvin/watchgod) * [python-
+minifier](https://github.com/dflook/python-minifier) ## License Copyright Â©
+2023 by Mausbrand Informationssysteme GmbH.
 Mausbrand and ViUR are registered trademarks of Mausbrand Informationssysteme
 GmbH. This project is free software under the MIT license.
 Please see the LICENSE file for details.
```

### Comparing `viur_cli-1.0.4/README.md` & `viur_cli-1.0.5/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -45,14 +45,19 @@
 
 ```sh
 $ viur run [target]
 ```
 run the appserver and start your app locally. You may specify a target projectID.
 
 ```sh
+$ viur check {--dev}
+```
+Runs a security check for the python environment and for each npm project registered under builds.
+
+```sh
 $ viur deploy {app|index} [target]
 ```
 you can deploy the app or the index.yaml to a google cloud project target of your choice, though the target is optional.
 By default this would be the projectID you gave when initializing the project, but you can add targets to the project.json
 if you would like to have an additional system for testing for example.
 
 ```sh
```

#### html2text {}

```diff
@@ -11,60 +11,61 @@
 project folder, clone the base project and then call `viur init` to prepare a
 project.json you can use this to get started quickly with a new viur project
 from scratch. ```sh $ viur init ``` this will initialize a new project in the
 current folder, you will be asked a couple of questions like if you would like
 to create a new project.json file, what components should be preinstalled and
 what the projectID of your application will be. ```sh $ viur run [target] ```
 run the appserver and start your app locally. You may specify a target
-projectID. ```sh $ viur deploy {app|index} [target] ``` you can deploy the app
-or the index.yaml to a google cloud project target of your choice, though the
-target is optional. By default this would be the projectID you gave when
-initializing the project, but you can add targets to the project.json if you
-would like to have an additional system for testing for example. ```sh $ viur
-install {vi|scriptor} ``` ask viur-cli to install either vi or the scriptor
-into your project ```sh $ viur flare {release|debug|watch} [appname] ``` if you
-have a flare component in your project you can build a `release`, start a
-`debug` helper or `watch` the flare app for code changes which will
-automatically rebuild it when you save your changes. ```sh $ viur flare watch
-vi ``` this would watch the vi flare app for changes and automatically rebuild
-it in case of changes. ```sh $ viur build release ``` build all flare and npm
-apps and produce a release that can be deployed ```sh $ viur build app
-[appname] ``` build a specific app ```sh $ viur env ``` check the environment
-you are in right now, show versions of viur-cli, viur-core and vi etc. ```sh $
-viur project {add|remove|list|addFlare|scanNpm} ``` with this you can manage
-your project.json or generate a new one. You can add or remove targets to/from
-the project.json, list what has been added to the project.json, add a flare
-application with `addFlare` to be built when running `viur build release` or
-walk through the projects sources with `scanNpm` and identify all npm
-applications to be added ## Viur scripting interface There is a new core
-component that enables us to pull and push python scripts from/to a deployed
-application and run these in a sandbox or even locally. The GUI version is
-called scriptor and can be accessed via a webinterface, but viur-cli also has a
-cli for this: ```sh $ viur script {configure|pull|push|run|setup} ``` Commands:
-- `configure` Manage configuration settings. - `pull` Pull contents from server
-to working_dir. - `push` Push contents of working_dir to server. - `run`
-Locally run a script located in the working_dir. - `setup` Setup user session
-with a given username and... ## Packaged tools In order to use the packaged
-tools, you can run: ```sh $ viur tool {2to3|flare|pyodide|ssl-fix} ``` Scripts:
-- `2to3` viur porting script - `flare` flare build script - `pyodide` run the
-get_pyodide command - `ssl-fix` ssl fix for MacOS for example the 2to3 script
-helps porting viur2 project to viur3, it can be used to automatically rename
-some things that are deprecated in viur3 as well, so you can use it whenever a
-new core version is released for viur3 projects as well: ```sh $ viur tool 2to3
--d . ``` will dry-run the script in the current directory and not make any
-changes, only suggestions. If you want to make the changes, leave out the -
-d argument and if you are a daring go-getter and like to live dangerously,
-replace the -d with -x, which will write the suggested changes without making a
-backup of the changed files. ## Development If you want to hack `viur-cli`,
-clone this repository next to the folder of your ViUR project. ```sh $ git
-clone git@github.com:viur-framework/viur-cli.git $ ls -1 viur-cli your-project
-``` Then, add it to your project as an editable dependency using ```sh $ cd
-your-project $ pipenv install --dev --editable ../viur-cli ``` ## Dependencies
-viur-cli depends on * [click](https://click.palletsprojects.com/) *
-[app_server](https://github.com/XeoN-GHMB/app_server) * [pipfile-requirements]
-(https://github.com/frostming/pipfile-requirements) * [watchgod](https://
-github.com/samuelcolvin/watchgod) * [python-minifier](https://github.com/
-dflook/python-minifier) ## License Copyright Â© 2023 by Mausbrand
-Informationssysteme GmbH.
+projectID. ```sh $ viur check {--dev} ``` Runs a security check for the python
+environment and for each npm project registered under builds. ```sh $ viur
+deploy {app|index} [target] ``` you can deploy the app or the index.yaml to a
+google cloud project target of your choice, though the target is optional. By
+default this would be the projectID you gave when initializing the project, but
+you can add targets to the project.json if you would like to have an additional
+system for testing for example. ```sh $ viur install {vi|scriptor} ``` ask
+viur-cli to install either vi or the scriptor into your project ```sh $ viur
+flare {release|debug|watch} [appname] ``` if you have a flare component in your
+project you can build a `release`, start a `debug` helper or `watch` the flare
+app for code changes which will automatically rebuild it when you save your
+changes. ```sh $ viur flare watch vi ``` this would watch the vi flare app for
+changes and automatically rebuild it in case of changes. ```sh $ viur build
+release ``` build all flare and npm apps and produce a release that can be
+deployed ```sh $ viur build app [appname] ``` build a specific app ```sh $ viur
+env ``` check the environment you are in right now, show versions of viur-cli,
+viur-core and vi etc. ```sh $ viur project {add|remove|list|addFlare|scanNpm}
+``` with this you can manage your project.json or generate a new one. You can
+add or remove targets to/from the project.json, list what has been added to the
+project.json, add a flare application with `addFlare` to be built when running
+`viur build release` or walk through the projects sources with `scanNpm` and
+identify all npm applications to be added ## Viur scripting interface There is
+a new core component that enables us to pull and push python scripts from/to a
+deployed application and run these in a sandbox or even locally. The GUI
+version is called scriptor and can be accessed via a webinterface, but viur-cli
+also has a cli for this: ```sh $ viur script {configure|pull|push|run|setup}
+``` Commands: - `configure` Manage configuration settings. - `pull` Pull
+contents from server to working_dir. - `push` Push contents of working_dir to
+server. - `run` Locally run a script located in the working_dir. - `setup`
+Setup user session with a given username and... ## Packaged tools In order to
+use the packaged tools, you can run: ```sh $ viur tool {2to3|flare|pyodide|ssl-
+fix} ``` Scripts: - `2to3` viur porting script - `flare` flare build script -
+`pyodide` run the get_pyodide command - `ssl-fix` ssl fix for MacOS for example
+the 2to3 script helps porting viur2 project to viur3, it can be used to
+automatically rename some things that are deprecated in viur3 as well, so you
+can use it whenever a new core version is released for viur3 projects as well:
+```sh $ viur tool 2to3 -d . ``` will dry-run the script in the current
+directory and not make any changes, only suggestions. If you want to make the
+changes, leave out the -d argument and if you are a daring go-getter and like
+to live dangerously, replace the -d with -x, which will write the suggested
+changes without making a backup of the changed files. ## Development If you
+want to hack `viur-cli`, clone this repository next to the folder of your ViUR
+project. ```sh $ git clone git@github.com:viur-framework/viur-cli.git $ ls -
+1 viur-cli your-project ``` Then, add it to your project as an editable
+dependency using ```sh $ cd your-project $ pipenv install --dev --editable ../
+viur-cli ``` ## Dependencies viur-cli depends on * [click](https://
+click.palletsprojects.com/) * [app_server](https://github.com/XeoN-GHMB/
+app_server) * [pipfile-requirements](https://github.com/frostming/pipfile-
+requirements) * [watchgod](https://github.com/samuelcolvin/watchgod) * [python-
+minifier](https://github.com/dflook/python-minifier) ## License Copyright Â©
+2023 by Mausbrand Informationssysteme GmbH.
 Mausbrand and ViUR are registered trademarks of Mausbrand Informationssysteme
 GmbH. This project is free software under the MIT license.
 Please see the LICENSE file for details.
```

### Comparing `viur_cli-1.0.4/setup.cfg` & `viur_cli-1.0.5/setup.cfg`

 * *Files 11% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 [options]
 package_dir = 
 	= src
 packages = find:
 python_requires = >=3.10
 install_requires = 
 	watchgod==0.7
-	python-minifier==2.5.0
+	python-minifier==2.9
 	app_server==0.9.4
 	click==8.1.3
 	pipfile-requirements==0.3.0
 
 [options.packages.find]
 where = src
```

### Comparing `viur_cli-1.0.4/src/viur_cli/build.py` & `viur_cli-1.0.5/src/viur_cli/build.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/cli.py` & `viur_cli-1.0.5/src/viur_cli/cli.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/conf.py` & `viur_cli-1.0.5/src/viur_cli/conf.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/deploy.py` & `viur_cli-1.0.5/src/viur_cli/deploy.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,20 @@
         echo_error(f"{name} is not a valid config name.")
         return
 
     conf = projectConfig["default"].copy()
     conf.update(projectConfig[name])
 
     if action == "app":
+        from . import do_checks
+        if not do_checks(dev=False):
+            if not click.confirm(f"The checks were not successful, do you want to continue?"):
+                return
+        else:
+            echo_info("\U00002714 No vulnerabilities found.")
         version = replace_vars(
             conf["version"],
             {k: v for k, v in conf.items() if k not in ["version"]}
         )
 
         # gcloud only allows for version identifiers in lower-case order and only accepting these characters
         version = "".join([c for c in version.lower() if c in string.ascii_lowercase + string.digits + "-"])
```

### Comparing `viur_cli-1.0.4/src/viur_cli/flare.py` & `viur_cli-1.0.5/src/viur_cli/flare.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/install.py` & `viur_cli-1.0.5/src/viur_cli/install.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/local.py` & `viur_cli-1.0.5/src/viur_cli/local.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-import click, os, shutil, subprocess
+import click, os, shutil, subprocess, json
 from . import cli, echo_error, get_config, utils
 from .install import vi as vi_install
 
 
 @cli.command(context_settings={"ignore_unknown_options": True})
 @click.argument("name", default='develop')
 @click.argument("additional_args", nargs=-1)
@@ -121,8 +121,55 @@
 @click.option('--next', '-n', 'next_',  is_flag=True, default=False)
 def vi(version, next_):
     """DEPRECATED please use viur install vi"""
     utils.echo_info("DEPRECATED please use: viur install vi")
     if next_:
         os.system(f'viur install vi --next')
     else:
-        os.system(f'viur install vi')
+        os.system(f'viur install vi')
+
+@cli.command()
+@click.option('--dev', '-d', is_flag=True, default=False)
+def check(dev):
+    """do security checks"""
+    if do_checks(dev):
+        utils.echo_info("\U00002714 No vulnerabilities found.")
+
+def do_checks(dev=True):
+
+    all_checks_passed=True
+    result = subprocess.check_output(['pipenv', 'check','--output', 'minimal']).decode("utf-8")
+    if "0 vulnerabilities found." in result:
+        pass
+    else:
+        os.system("pipenv check")
+        all_checks_passed=False
+
+    if dev:
+        result = subprocess.check_output(['pipenv', 'check','--output', 'minimal', "--categories", "develop"]).decode("utf-8")
+        if "0 vulnerabilities found." in result:
+            pass
+        else:
+            os.system("pipenv check --categories develop")
+            all_checks_passed=False
+
+
+    projectConfig = get_config()
+    cfg = projectConfig["default"].copy()
+    if builds_cfg := cfg.get("builds"):
+        if npm_apps := [k for k,v in builds_cfg.items() if builds_cfg[k]["kind"] == "npm"]:
+            for name in npm_apps:
+                if dev:
+                    result = subprocess.check_output(['npm', 'audit','--prefix',cfg["sources_folder"]+builds_cfg[name]["source"]]).decode("utf-8")
+                else:
+                    result = subprocess.check_output(['npm', 'audit','--omit','dev', '--prefix',cfg["sources_folder"]+builds_cfg[name]["source"]]).decode("utf-8")
+                if "found 0 vulnerabilities" in result:
+                    pass
+                else:
+                    utils.echo_info(f"checking {name}...")
+                    os.system(f'cd {cfg["sources_folder"]}{builds_cfg[name]["source"]} && npm audit')
+                    all_checks_passed=False
+
+    if all_checks_passed:
+        return True
+
+    return False
```

### Comparing `viur_cli-1.0.4/src/viur_cli/npm.py` & `viur_cli-1.0.5/src/viur_cli/npm.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/cli.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/cli.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/__init__.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/__init__.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/csvwriter.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/csvwriter.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/dialog.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/dialog.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/logger.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/logger.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/module.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/module.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/network.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/network.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/readers.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/readers.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/viur.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/viur.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scriptor/scriptor/writer.py` & `viur_cli-1.0.5/src/viur_cli/scriptor/scriptor/writer.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scripts/flare.py` & `viur_cli-1.0.5/src/viur_cli/scripts/flare.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scripts/get_pyodide.py` & `viur_cli-1.0.5/src/viur_cli/scripts/get_pyodide.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/scripts/viur_2to3.py` & `viur_cli-1.0.5/src/viur_cli/scripts/viur_2to3.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/setup.py` & `viur_cli-1.0.5/src/viur_cli/setup.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/tool.py` & `viur_cli-1.0.5/src/viur_cli/tool.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli/utils.py` & `viur_cli-1.0.5/src/viur_cli/utils.py`

 * *Files identical despite different names*

### Comparing `viur_cli-1.0.4/src/viur_cli.egg-info/PKG-INFO` & `viur_cli-1.0.5/src/viur_cli.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: viur-cli
-Version: 1.0.4
+Version: 1.0.5
 Summary: Command-line interface for ViUR application maintenance.
 Home-page: https://github.com/viur-framework/viur-cli
 Author: Andreas H. Kelch
 Author-email: ak@mausbrand.de
 Project-URL: Bug Tracker, https://github.com/viur-framework/viur-cli/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
@@ -60,14 +60,19 @@
 
 ```sh
 $ viur run [target]
 ```
 run the appserver and start your app locally. You may specify a target projectID.
 
 ```sh
+$ viur check {--dev}
+```
+Runs a security check for the python environment and for each npm project registered under builds.
+
+```sh
 $ viur deploy {app|index} [target]
 ```
 you can deploy the app or the index.yaml to a google cloud project target of your choice, though the target is optional.
 By default this would be the projectID you gave when initializing the project, but you can add targets to the project.json
 if you would like to have an additional system for testing for example.
 
 ```sh
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: viur-cli Version: 1.0.4 Summary: Command-line
+Metadata-Version: 2.1 Name: viur-cli Version: 1.0.5 Summary: Command-line
 interface for ViUR application maintenance. Home-page: https://github.com/viur-
 framework/viur-cli Author: Andreas H. Kelch Author-email: ak@mausbrand.de
 Project-URL: Bug Tracker, https://github.com/viur-framework/viur-cli/issues
 Classifier: Programming Language :: Python :: 3 Classifier: Operating System ::
 OS Independent Classifier: License :: OSI Approved :: MIT License Requires-
 Python: >=3.10 Description-Content-Type: text/markdown License-File: LICENSE
                       [A hexagonal logo of the viur-cli]
@@ -18,60 +18,61 @@
 project folder, clone the base project and then call `viur init` to prepare a
 project.json you can use this to get started quickly with a new viur project
 from scratch. ```sh $ viur init ``` this will initialize a new project in the
 current folder, you will be asked a couple of questions like if you would like
 to create a new project.json file, what components should be preinstalled and
 what the projectID of your application will be. ```sh $ viur run [target] ```
 run the appserver and start your app locally. You may specify a target
-projectID. ```sh $ viur deploy {app|index} [target] ``` you can deploy the app
-or the index.yaml to a google cloud project target of your choice, though the
-target is optional. By default this would be the projectID you gave when
-initializing the project, but you can add targets to the project.json if you
-would like to have an additional system for testing for example. ```sh $ viur
-install {vi|scriptor} ``` ask viur-cli to install either vi or the scriptor
-into your project ```sh $ viur flare {release|debug|watch} [appname] ``` if you
-have a flare component in your project you can build a `release`, start a
-`debug` helper or `watch` the flare app for code changes which will
-automatically rebuild it when you save your changes. ```sh $ viur flare watch
-vi ``` this would watch the vi flare app for changes and automatically rebuild
-it in case of changes. ```sh $ viur build release ``` build all flare and npm
-apps and produce a release that can be deployed ```sh $ viur build app
-[appname] ``` build a specific app ```sh $ viur env ``` check the environment
-you are in right now, show versions of viur-cli, viur-core and vi etc. ```sh $
-viur project {add|remove|list|addFlare|scanNpm} ``` with this you can manage
-your project.json or generate a new one. You can add or remove targets to/from
-the project.json, list what has been added to the project.json, add a flare
-application with `addFlare` to be built when running `viur build release` or
-walk through the projects sources with `scanNpm` and identify all npm
-applications to be added ## Viur scripting interface There is a new core
-component that enables us to pull and push python scripts from/to a deployed
-application and run these in a sandbox or even locally. The GUI version is
-called scriptor and can be accessed via a webinterface, but viur-cli also has a
-cli for this: ```sh $ viur script {configure|pull|push|run|setup} ``` Commands:
-- `configure` Manage configuration settings. - `pull` Pull contents from server
-to working_dir. - `push` Push contents of working_dir to server. - `run`
-Locally run a script located in the working_dir. - `setup` Setup user session
-with a given username and... ## Packaged tools In order to use the packaged
-tools, you can run: ```sh $ viur tool {2to3|flare|pyodide|ssl-fix} ``` Scripts:
-- `2to3` viur porting script - `flare` flare build script - `pyodide` run the
-get_pyodide command - `ssl-fix` ssl fix for MacOS for example the 2to3 script
-helps porting viur2 project to viur3, it can be used to automatically rename
-some things that are deprecated in viur3 as well, so you can use it whenever a
-new core version is released for viur3 projects as well: ```sh $ viur tool 2to3
--d . ``` will dry-run the script in the current directory and not make any
-changes, only suggestions. If you want to make the changes, leave out the -
-d argument and if you are a daring go-getter and like to live dangerously,
-replace the -d with -x, which will write the suggested changes without making a
-backup of the changed files. ## Development If you want to hack `viur-cli`,
-clone this repository next to the folder of your ViUR project. ```sh $ git
-clone git@github.com:viur-framework/viur-cli.git $ ls -1 viur-cli your-project
-``` Then, add it to your project as an editable dependency using ```sh $ cd
-your-project $ pipenv install --dev --editable ../viur-cli ``` ## Dependencies
-viur-cli depends on * [click](https://click.palletsprojects.com/) *
-[app_server](https://github.com/XeoN-GHMB/app_server) * [pipfile-requirements]
-(https://github.com/frostming/pipfile-requirements) * [watchgod](https://
-github.com/samuelcolvin/watchgod) * [python-minifier](https://github.com/
-dflook/python-minifier) ## License Copyright Â© 2023 by Mausbrand
-Informationssysteme GmbH.
+projectID. ```sh $ viur check {--dev} ``` Runs a security check for the python
+environment and for each npm project registered under builds. ```sh $ viur
+deploy {app|index} [target] ``` you can deploy the app or the index.yaml to a
+google cloud project target of your choice, though the target is optional. By
+default this would be the projectID you gave when initializing the project, but
+you can add targets to the project.json if you would like to have an additional
+system for testing for example. ```sh $ viur install {vi|scriptor} ``` ask
+viur-cli to install either vi or the scriptor into your project ```sh $ viur
+flare {release|debug|watch} [appname] ``` if you have a flare component in your
+project you can build a `release`, start a `debug` helper or `watch` the flare
+app for code changes which will automatically rebuild it when you save your
+changes. ```sh $ viur flare watch vi ``` this would watch the vi flare app for
+changes and automatically rebuild it in case of changes. ```sh $ viur build
+release ``` build all flare and npm apps and produce a release that can be
+deployed ```sh $ viur build app [appname] ``` build a specific app ```sh $ viur
+env ``` check the environment you are in right now, show versions of viur-cli,
+viur-core and vi etc. ```sh $ viur project {add|remove|list|addFlare|scanNpm}
+``` with this you can manage your project.json or generate a new one. You can
+add or remove targets to/from the project.json, list what has been added to the
+project.json, add a flare application with `addFlare` to be built when running
+`viur build release` or walk through the projects sources with `scanNpm` and
+identify all npm applications to be added ## Viur scripting interface There is
+a new core component that enables us to pull and push python scripts from/to a
+deployed application and run these in a sandbox or even locally. The GUI
+version is called scriptor and can be accessed via a webinterface, but viur-cli
+also has a cli for this: ```sh $ viur script {configure|pull|push|run|setup}
+``` Commands: - `configure` Manage configuration settings. - `pull` Pull
+contents from server to working_dir. - `push` Push contents of working_dir to
+server. - `run` Locally run a script located in the working_dir. - `setup`
+Setup user session with a given username and... ## Packaged tools In order to
+use the packaged tools, you can run: ```sh $ viur tool {2to3|flare|pyodide|ssl-
+fix} ``` Scripts: - `2to3` viur porting script - `flare` flare build script -
+`pyodide` run the get_pyodide command - `ssl-fix` ssl fix for MacOS for example
+the 2to3 script helps porting viur2 project to viur3, it can be used to
+automatically rename some things that are deprecated in viur3 as well, so you
+can use it whenever a new core version is released for viur3 projects as well:
+```sh $ viur tool 2to3 -d . ``` will dry-run the script in the current
+directory and not make any changes, only suggestions. If you want to make the
+changes, leave out the -d argument and if you are a daring go-getter and like
+to live dangerously, replace the -d with -x, which will write the suggested
+changes without making a backup of the changed files. ## Development If you
+want to hack `viur-cli`, clone this repository next to the folder of your ViUR
+project. ```sh $ git clone git@github.com:viur-framework/viur-cli.git $ ls -
+1 viur-cli your-project ``` Then, add it to your project as an editable
+dependency using ```sh $ cd your-project $ pipenv install --dev --editable ../
+viur-cli ``` ## Dependencies viur-cli depends on * [click](https://
+click.palletsprojects.com/) * [app_server](https://github.com/XeoN-GHMB/
+app_server) * [pipfile-requirements](https://github.com/frostming/pipfile-
+requirements) * [watchgod](https://github.com/samuelcolvin/watchgod) * [python-
+minifier](https://github.com/dflook/python-minifier) ## License Copyright Â©
+2023 by Mausbrand Informationssysteme GmbH.
 Mausbrand and ViUR are registered trademarks of Mausbrand Informationssysteme
 GmbH. This project is free software under the MIT license.
 Please see the LICENSE file for details.
```

### Comparing `viur_cli-1.0.4/src/viur_cli.egg-info/SOURCES.txt` & `viur_cli-1.0.5/src/viur_cli.egg-info/SOURCES.txt`

 * *Files identical despite different names*


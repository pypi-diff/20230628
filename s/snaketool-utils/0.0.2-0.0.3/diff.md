# Comparing `tmp/snaketool_utils-0.0.2.tar.gz` & `tmp/snaketool_utils-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "snaketool_utils-0.0.2.tar", last modified: Mon Jun 26 07:02:36 2023, max compression
+gzip compressed data, was "snaketool_utils-0.0.3.tar", last modified: Wed Jun 28 00:30:54 2023, max compression
```

## Comparing `snaketool_utils-0.0.2.tar` & `snaketool_utils-0.0.3.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 07:02:36.551738 snaketool_utils-0.0.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       86 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-26 07:02:36.551738 snaketool_utils-0.0.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/README.md
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/VERSION
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 07:02:36.551738 snaketool_utils-0.0.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1190 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 07:02:36.547738 snaketool_utils-0.0.2/snaketool_utils/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/snaketool_utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7042 2023-06-26 07:02:19.000000 snaketool_utils-0.0.2/snaketool_utils/cli_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 07:02:36.551738 snaketool_utils-0.0.2/snaketool_utils.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-26 07:02:36.000000 snaketool_utils-0.0.2/snaketool_utils.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-26 07:02:36.000000 snaketool_utils-0.0.2/snaketool_utils.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 07:02:36.000000 snaketool_utils-0.0.2/snaketool_utils.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-26 07:02:36.000000 snaketool_utils-0.0.2/snaketool_utils.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-26 07:02:36.000000 snaketool_utils-0.0.2/snaketool_utils.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:30:54.282803 snaketool_utils-0.0.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       86 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-28 00:30:54.282803 snaketool_utils-0.0.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/VERSION
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 00:30:54.282803 snaketool_utils-0.0.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1190 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:30:54.282803 snaketool_utils-0.0.3/snaketool_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/snaketool_utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7233 2023-06-28 00:30:44.000000 snaketool_utils-0.0.3/snaketool_utils/cli_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:30:54.282803 snaketool_utils-0.0.3/snaketool_utils.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-28 00:30:54.000000 snaketool_utils-0.0.3/snaketool_utils.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-28 00:30:54.000000 snaketool_utils-0.0.3/snaketool_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:30:54.000000 snaketool_utils-0.0.3/snaketool_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 00:30:54.000000 snaketool_utils-0.0.3/snaketool_utils.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-28 00:30:54.000000 snaketool_utils-0.0.3/snaketool_utils.egg-info/top_level.txt
```

### Comparing `snaketool_utils-0.0.2/LICENSE` & `snaketool_utils-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `snaketool_utils-0.0.2/setup.py` & `snaketool_utils-0.0.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,15 +26,15 @@
     "Topic :: Scientific/Engineering :: Bio-Informatics",
 ]
 
 
 setup(
     name="snaketool_utils",
     url="https://github.com/beardymcjohnface/snaketool-utils",
-    python_requires=">=3.9",
+    python_requires=">=3.7",
     description="Utility functions for Snaketool CLI",
     long_description=get_description(),
     long_description_content_type="text/markdown",
     version=get_version(),
     author="Michael Roach",
     author_email="beardymcjohnface@gmail.com",
     install_requires=[
```

### Comparing `snaketool_utils-0.0.2/snaketool_utils/cli_utils.py` & `snaketool_utils-0.0.3/snaketool_utils/cli_utils.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,8 +1,7 @@
-
 import sys
 import os
 import subprocess
 import yaml
 import click
 import collections.abc
 from shutil import copyfile
@@ -76,21 +75,23 @@
 
     Args:
         config (dict): Config dictionary to overwrite (e.g. defaults)
         overwrite_config (dict): Config dictionary of new/updated values to add
 
     Returns (dict): Merged dictionary
     """
+
     def _update(d, u):
-        for (key, value) in u.items():
+        for key, value in u.items():
             if isinstance(value, collections.abc.Mapping):
                 d[key] = _update(d.get(key, {}), value)
             else:
                 d[key] = value
         return d
+
     _update(config, overwrite_config)
 
 
 def update_config(in_config=None, merge=None, output_config=None, log=None):
     """Update the default config with the new config values
 
     Args:
@@ -161,29 +162,31 @@
     snakefile_path=None,
     merge_config=None,
     threads=1,
     use_conda=False,
     conda_prefix=None,
     snake_default=None,
     snake_args=[],
+    profile=None,
     log=None,
-    **kwargs
+    **kwargs,
 ):
     """Run a Snakefile!
 
     Args:
         configfile (str): Filepath of config file to pass with --configfile
         system_config (str): Filepath of system config to copy if configfile not present
         snakefile_path (str): Filepath of Snakefile
         merge_config (dict): Config values to merge with your config file
         threads (int): Number of local threads to request
         use_conda (bool): Snakemake's --use-conda
         conda_prefix (str): Filepath for Snakemake's --conda-prefix
         snake_default (list): Snakemake args to pass to Snakemake
         snake_args (list): Additional args to pass to Snakemake
+        profile (str): Name of Snakemake profile
         log (str): Log file for writing STDERR
         **kwargs:
 
     Returns (int): Exit code
     """
     snake_command = ["snakemake", "-s", snakefile_path]
 
@@ -202,15 +205,15 @@
         msg_box(
             "Runtime config",
             errmsg=yaml.dump(snake_config, Dumper=yaml.Dumper),
             log=log,
         )
 
     # add threads
-    if not "--profile" in snake_args:
+    if "--profile" not in snake_args and profile is None:
         snake_command += ["--cores", threads]
 
     # add conda args if using conda
     if use_conda:
         snake_command += ["--use-conda"]
         if conda_prefix:
             snake_command += ["--conda-prefix", conda_prefix]
@@ -219,14 +222,18 @@
     if snake_default:
         snake_command += snake_default
 
     # add any additional snakemake commands
     if snake_args:
         snake_command += list(snake_args)
 
+    # allow double-handling of profile
+    if profile:
+        snake_command += ["--profile", profile]
+
     # Run Snakemake!!!
     snake_command = " ".join(str(s) for s in snake_command)
     msg_box("Snakemake command", errmsg=snake_command, log=log)
     if not subprocess.run(snake_command, shell=True).returncode == 0:
         msg("ERROR: Snakemake failed", log=log)
         sys.exit(1)
     else:
```


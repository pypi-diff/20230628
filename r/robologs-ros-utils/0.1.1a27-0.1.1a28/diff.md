# Comparing `tmp/robologs_ros_utils-0.1.1a27.tar.gz` & `tmp/robologs_ros_utils-0.1.1a28.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "robologs_ros_utils-0.1.1a27.tar", max compression
+gzip compressed data, was "robologs_ros_utils-0.1.1a28.tar", max compression
```

## Comparing `robologs_ros_utils-0.1.1a27.tar` & `robologs_ros_utils-0.1.1a28.tar`

### file list

```diff
@@ -1,26 +1,19 @@
--rw-r--r--   0        0        0        0 2023-06-26 13:09:39.586726 robologs_ros_utils-0.1.1a27/README.md
--rw-r--r--   0        0        0     1608 2023-06-27 14:28:19.042780 robologs_ros_utils-0.1.1a27/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-26 13:09:39.586726 robologs_ros_utils-0.1.1a27/robologs_ros_utils/__init__.py
--rw-r--r--   0        0        0      949 2023-06-27 08:15:43.054590 robologs_ros_utils-0.1.1a27/robologs_ros_utils/cli.py
--rw-r--r--   0        0        0        0 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/__init__.py
--rw-r--r--   0        0        0      171 2023-06-26 14:13:16.767932 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0        0 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/__init__.py
--rw-r--r--   0        0        0      176 2023-06-26 14:13:16.767932 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     2595 2023-06-26 14:13:17.695938 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/__pycache__/ros_img_tools.cpython-38.pyc
--rw-r--r--   0        0        0    11396 2023-06-27 13:51:54.362193 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/__pycache__/ros_utils.cpython-38.pyc
--rw-r--r--   0        0        0      523 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/argument_parsers.py
--rw-r--r--   0        0        0     2578 2023-06-27 11:55:49.889627 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/clip_rosbag.py
--rw-r--r--   0        0        0      399 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/commands.py
--rw-r--r--   0        0        0     2698 2023-06-27 11:55:58.437675 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/get_images_from_bag.py
--rw-r--r--   0        0        0     1052 2023-06-27 11:55:36.549553 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/get_summary_from_bag.py
--rw-r--r--   0        0        0     3029 2023-06-27 11:56:05.773716 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/get_videos_from_bag.py
--rw-r--r--   0        0        0     2669 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/ros_img_tools.py
--rw-r--r--   0        0        0    15655 2023-06-27 13:51:44.266140 robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/ros_utils.py
--rw-r--r--   0        0        0        0 2023-06-27 11:36:54.527450 robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/__init__.py
--rw-r--r--   0        0        0      169 2023-06-27 11:37:14.987556 robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     5212 2023-06-27 11:59:04.658716 robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/__pycache__/file_utils.cpython-38.pyc
--rw-r--r--   0        0        0     1376 2023-06-27 11:59:04.774716 robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/__pycache__/img_utils.cpython-38.pyc
--rw-r--r--   0        0        0     4615 2023-06-26 13:09:39.682727 robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/file_utils.py
--rw-r--r--   0        0        0     1147 2023-06-26 13:09:39.682727 robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/img_utils.py
--rw-r--r--   0        0        0     1330 1970-01-01 00:00:00.000000 robologs_ros_utils-0.1.1a27/setup.py
--rw-r--r--   0        0        0     1214 1970-01-01 00:00:00.000000 robologs_ros_utils-0.1.1a27/PKG-INFO
+-rw-r--r--   0        0        0        0 2023-06-26 13:09:39.586726 robologs_ros_utils-0.1.1a28/README.md
+-rw-r--r--   0        0        0     1608 2023-06-28 12:58:15.304851 robologs_ros_utils-0.1.1a28/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-26 13:09:39.586726 robologs_ros_utils-0.1.1a28/robologs_ros_utils/__init__.py
+-rw-r--r--   0        0        0      859 2023-06-28 12:49:42.241674 robologs_ros_utils-0.1.1a28/robologs_ros_utils/cli.py
+-rw-r--r--   0        0        0        0 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/__init__.py
+-rw-r--r--   0        0        0      523 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/argument_parsers.py
+-rw-r--r--   0        0        0     2578 2023-06-27 11:55:49.889627 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/clip_rosbag.py
+-rw-r--r--   0        0        0      399 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/commands.py
+-rw-r--r--   0        0        0     2698 2023-06-27 11:55:58.437675 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/get_images_from_bag.py
+-rw-r--r--   0        0        0     1052 2023-06-27 11:55:36.549553 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/get_summary_from_bag.py
+-rw-r--r--   0        0        0     3029 2023-06-27 11:56:05.773716 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/get_videos_from_bag.py
+-rw-r--r--   0        0        0     2669 2023-06-26 13:09:39.590726 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/ros_img_tools.py
+-rw-r--r--   0        0        0    15655 2023-06-27 13:51:44.266140 robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/ros_utils.py
+-rw-r--r--   0        0        0        0 2023-06-27 11:36:54.527450 robologs_ros_utils-0.1.1a28/robologs_ros_utils/utils/__init__.py
+-rw-r--r--   0        0        0     4615 2023-06-26 13:09:39.682727 robologs_ros_utils-0.1.1a28/robologs_ros_utils/utils/file_utils.py
+-rw-r--r--   0        0        0     1147 2023-06-26 13:09:39.682727 robologs_ros_utils-0.1.1a28/robologs_ros_utils/utils/img_utils.py
+-rw-r--r--   0        0        0     1330 1970-01-01 00:00:00.000000 robologs_ros_utils-0.1.1a28/setup.py
+-rw-r--r--   0        0        0     1214 1970-01-01 00:00:00.000000 robologs_ros_utils-0.1.1a28/PKG-INFO
```

### Comparing `robologs_ros_utils-0.1.1a27/pyproject.toml` & `robologs_ros_utils-0.1.1a28/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "robologs-ros-utils"
-version = "0.1.1a27"
+version = "0.1.1a28"
 description = "robologs-ros-utils is an open source library of containerized data transformations for the robotics and drone communities"
 authors = ["roboto.ai <info@roboto.ai>"]
 license = "Apache-2.0"
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.8.2"
```

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/cli.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/cli.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,12 +1,11 @@
 from inspect import getmembers
 
 import click
 
-from robologs_ros_utils.connectors.commands import connectors
 from robologs_ros_utils.sources.ros1.commands import ros
 
 
 @click.group(invoke_without_command=True)
 @click.pass_context
 def cli(ctx):
     if ctx.invoked_subcommand is None:
@@ -23,15 +22,14 @@
     if ctx.invoked_subcommand is None:
         click.echo("Robologs is an open source collection of sensor data transforms")
         click.echo("Run robologs --help to see a list of available commands")
         click.echo("")
 
 
 cli.add_command(ros)
-cli.add_command(connectors)
 
 
 def main():
     cli()
 
 
 if __name__ == "__main__":
```

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/argument_parsers.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/argument_parsers.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/clip_rosbag.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/clip_rosbag.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/get_images_from_bag.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/get_images_from_bag.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/get_summary_from_bag.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/get_summary_from_bag.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/get_videos_from_bag.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/get_videos_from_bag.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/ros_img_tools.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/ros_img_tools.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/sources/ros1/ros_utils.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/sources/ros1/ros_utils.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/file_utils.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/utils/file_utils.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/robologs_ros_utils/utils/img_utils.py` & `robologs_ros_utils-0.1.1a28/robologs_ros_utils/utils/img_utils.py`

 * *Files identical despite different names*

### Comparing `robologs_ros_utils-0.1.1a27/setup.py` & `robologs_ros_utils-0.1.1a28/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -28,15 +28,15 @@
  'types-tqdm>=4.64.7.9,<5.0.0.0']
 
 entry_points = \
 {'console_scripts': ['robologs-ros-utils = robologs_ros_utils.cli:main']}
 
 setup_kwargs = {
     'name': 'robologs-ros-utils',
-    'version': '0.1.1a27',
+    'version': '0.1.1a28',
     'description': 'robologs-ros-utils is an open source library of containerized data transformations for the robotics and drone communities',
     'long_description': '',
     'author': 'roboto.ai',
     'author_email': 'info@roboto.ai',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `robologs_ros_utils-0.1.1a27/PKG-INFO` & `robologs_ros_utils-0.1.1a28/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: robologs-ros-utils
-Version: 0.1.1a27
+Version: 0.1.1a28
 Summary: robologs-ros-utils is an open source library of containerized data transformations for the robotics and drone communities
 License: Apache-2.0
 Author: roboto.ai
 Author-email: info@roboto.ai
 Requires-Python: >=3.8.2,<4.0.0
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
```


# Comparing `tmp/argus-rico-0.0.2.tar.gz` & `tmp/argus-rico-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "argus-rico-0.0.2.tar", max compression
+gzip compressed data, was "argus-rico-0.0.3.tar", max compression
```

## Comparing `argus-rico-0.0.2.tar` & `argus-rico-0.0.3.tar`

### file list

```diff
@@ -1,17 +1,17 @@
--rw-r--r--   0        0        0     1071 2023-05-24 01:07:47.899290 argus-rico-0.0.2/LICENSE
--rw-r--r--   0        0        0     1287 2023-06-12 16:38:56.432646 argus-rico-0.0.2/pyproject.toml
--rw-r--r--   0        0        0     2765 2023-06-12 16:35:31.667188 argus-rico-0.0.2/src/argus_rico/__init__.py
--rw-r--r--   0        0        0     1648 2023-06-12 16:35:31.667312 argus-rico-0.0.2/src/argus_rico/cli.py
--rw-r--r--   0        0        0      572 2023-06-05 21:00:52.783870 argus-rico-0.0.2/src/argus_rico/consumer.py
--rw-r--r--   0        0        0      792 2023-06-12 16:35:31.667436 argus-rico-0.0.2/src/argus_rico/efte_runner.py
--rw-r--r--   0        0        0     2060 2023-06-12 16:35:31.667549 argus-rico-0.0.2/src/argus_rico/heartbeat.py
--rw-r--r--   0        0        0     4505 2023-06-12 16:35:31.667685 argus-rico-0.0.2/src/argus_rico/images.py
--rw-r--r--   0        0        0      262 2023-06-12 16:35:31.667792 argus-rico-0.0.2/src/argus_rico/models/__init__.py
--rw-r--r--   0        0        0     8111 2023-06-12 16:35:31.667921 argus-rico-0.0.2/src/argus_rico/models/evr_image.py
--rw-r--r--   0        0        0     2740 2023-06-12 16:35:31.668047 argus-rico-0.0.2/src/argus_rico/producer.py
--rw-r--r--   0        0        0        0 2023-06-12 16:35:31.668081 argus-rico-0.0.2/src/argus_rico/py.typed
--rw-r--r--   0        0        0     2462 2023-06-12 16:35:31.668225 argus-rico-0.0.2/src/argus_rico/raw_streamer.py
--rw-r--r--   0        0        0     3597 2023-06-12 16:35:31.668377 argus-rico-0.0.2/src/argus_rico/schemas/raw_candidate.avsc
--rw-r--r--   0        0        0     6838 2023-06-12 16:35:31.668525 argus-rico-0.0.2/src/argus_rico/slack.py
--rw-r--r--   0        0        0     1363 2023-06-12 16:45:57.794383 argus-rico-0.0.2/setup.py
--rw-r--r--   0        0        0     1085 2023-06-12 16:45:57.794625 argus-rico-0.0.2/PKG-INFO
+-rw-r--r--   0        0        0     1071 2023-05-24 01:07:47.899290 argus-rico-0.0.3/LICENSE
+-rw-r--r--   0        0        0     1093 2023-06-27 22:00:39.860607 argus-rico-0.0.3/pyproject.toml
+-rw-r--r--   0        0        0     2913 2023-06-27 22:01:41.485016 argus-rico-0.0.3/src/argus_rico/__init__.py
+-rw-r--r--   0        0        0     1648 2023-06-12 16:35:31.667312 argus-rico-0.0.3/src/argus_rico/cli.py
+-rw-r--r--   0        0        0      572 2023-06-05 21:00:52.783870 argus-rico-0.0.3/src/argus_rico/consumer.py
+-rw-r--r--   0        0        0      792 2023-06-12 16:35:31.667436 argus-rico-0.0.3/src/argus_rico/efte_runner.py
+-rw-r--r--   0        0        0     2060 2023-06-12 16:35:31.667549 argus-rico-0.0.3/src/argus_rico/heartbeat.py
+-rw-r--r--   0        0        0     4960 2023-06-27 21:48:18.466470 argus-rico-0.0.3/src/argus_rico/images.py
+-rw-r--r--   0        0        0      262 2023-06-12 16:35:31.667792 argus-rico-0.0.3/src/argus_rico/models/__init__.py
+-rw-r--r--   0        0        0     8111 2023-06-12 16:35:31.667921 argus-rico-0.0.3/src/argus_rico/models/evr_image.py
+-rw-r--r--   0        0        0     2740 2023-06-12 16:35:31.668047 argus-rico-0.0.3/src/argus_rico/producer.py
+-rw-r--r--   0        0        0        0 2023-06-12 16:35:31.668081 argus-rico-0.0.3/src/argus_rico/py.typed
+-rw-r--r--   0        0        0     2462 2023-06-12 16:35:31.668225 argus-rico-0.0.3/src/argus_rico/raw_streamer.py
+-rw-r--r--   0        0        0     3597 2023-06-12 16:35:31.668377 argus-rico-0.0.3/src/argus_rico/schemas/raw_candidate.avsc
+-rw-r--r--   0        0        0     6838 2023-06-12 16:35:31.668525 argus-rico-0.0.3/src/argus_rico/slack.py
+-rw-r--r--   0        0        0     1417 2023-06-27 22:02:20.454635 argus-rico-0.0.3/setup.py
+-rw-r--r--   0        0        0     1161 2023-06-27 22:02:20.454868 argus-rico-0.0.3/PKG-INFO
```

### Comparing `argus-rico-0.0.2/LICENSE` & `argus-rico-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/__init__.py` & `argus-rico-0.0.3/src/argus_rico/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,22 +1,26 @@
 """Top-level package for Evryscope-Argus Transient Reporter."""
 
 __author__ = """Hank Corbett"""
 __email__ = "htc@unc.edu"
-__version__ = "0.0.2"
+__version__ = "0.0.3"
 
 __all__ = ["RicoHeartBeat", "RawStreamer", "EVRImageLoader"]
 
 import logging
 import os
 
 from dotenv import load_dotenv
 
 basedir = os.path.abspath(os.path.dirname(__file__))
-load_dotenv(os.path.join(basedir, ".env"))
+
+if os.path.isfile(os.path.join(os.path.expanduser("~"), ".ricoenv")):
+    load_dotenv(os.path.join(os.path.expanduser("~"), ".ricoenv"))
+else:
+    load_dotenv(os.path.join(basedir, ".env"))
 
 
 class Config(object):
     """
     Configuration class for managing application settings.
 
     Attributes:
```

### Comparing `argus-rico-0.0.2/src/argus_rico/cli.py` & `argus-rico-0.0.3/src/argus_rico/cli.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/consumer.py` & `argus-rico-0.0.3/src/argus_rico/consumer.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/efte_runner.py` & `argus-rico-0.0.3/src/argus_rico/efte_runner.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/heartbeat.py` & `argus-rico-0.0.3/src/argus_rico/heartbeat.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/images.py` & `argus-rico-0.0.3/src/argus_rico/images.py`

 * *Files 11% similar despite different names*

```diff
@@ -54,14 +54,36 @@
                 "wcspath": str,
             }
         ),
     )
     return images
 
 
+def get_image_meta(
+    path: str,
+) -> Dict[str, Any]:
+    """
+    Retrieve image metadata by filename.
+
+    Args:
+        path (str): Filename for the image
+
+    Returns:
+        Dict: Dictionary of image metadata
+
+    """
+
+    basename = os.path.basename(path).split(".")[0]
+
+    client = MongoClient(config.MONGODB_URI)
+    collection = client[config.MONGO_DBNAME].evr_images
+    image = collection.find_one({"basename": basename})
+    return image
+
+
 class EVRImageProducer(Producer):
     """
     A Kafka producer for sending EVR images.
 
     Args:
         None
```

### Comparing `argus-rico-0.0.2/src/argus_rico/models/evr_image.py` & `argus-rico-0.0.3/src/argus_rico/models/evr_image.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/producer.py` & `argus-rico-0.0.3/src/argus_rico/producer.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/raw_streamer.py` & `argus-rico-0.0.3/src/argus_rico/raw_streamer.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/schemas/raw_candidate.avsc` & `argus-rico-0.0.3/src/argus_rico/schemas/raw_candidate.avsc`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/src/argus_rico/slack.py` & `argus-rico-0.0.3/src/argus_rico/slack.py`

 * *Files identical despite different names*

### Comparing `argus-rico-0.0.2/setup.py` & `argus-rico-0.0.3/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,29 +18,31 @@
  'confluent-kafka>=2.1.1,<3.0.0',
  'fastapi>=0.95.2,<0.96.0',
  'fastavro>=1.4.12,<2.0.0',
  'geojson-pydantic>=0.6.2,<0.7.0',
  'ipython>=8.14.0,<9.0.0',
  'numpy>=1.24.3,<2.0.0',
  'orjson>=3.8.13,<4.0.0',
+ 'pandas>=2.0.2,<3.0.0',
  'pyarrow>=10.0.0',
  'pydantic>=1.10.8,<2.0.0',
  'pymongo>=4.3.3,<5.0.0',
  'pymongoarrow>=0.7.0,<0.8.0',
  'python-dotenv>=0.19.0,<0.20.0',
+ 'qlsc>=1.0.6,<2.0.0',
  'rich>=13.3.5,<14.0.0',
  'sanitize-filename>=1.2.0,<2.0.0',
  'slack-bolt>=1.18.0,<2.0.0']
 
 entry_points = \
-{'console_scripts': ['rico = rico.cli:main']}
+{'console_scripts': ['rico = argus_rico.cli:main']}
 
 setup_kwargs = {
     'name': 'argus-rico',
-    'version': '0.0.2',
+    'version': '0.0.3',
     'description': 'Transient alert generation and database interaction for Argus and Evryscope',
     'long_description': None,
     'author': 'Hank Corbett',
     'author_email': None,
     'maintainer': None,
     'maintainer_email': None,
     'url': None,
```

### Comparing `argus-rico-0.0.2/PKG-INFO` & `argus-rico-0.0.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: argus-rico
-Version: 0.0.2
+Version: 0.0.3
 Summary: Transient alert generation and database interaction for Argus and Evryscope
 Author: Hank Corbett
 Requires-Python: >=3.10,<3.11
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Requires-Dist: astropy (>=5.3,<6.0)
 Requires-Dist: black (>=23.3.0,<24.0.0)
@@ -13,15 +13,17 @@
 Requires-Dist: confluent-kafka (>=2.1.1,<3.0.0)
 Requires-Dist: fastapi (>=0.95.2,<0.96.0)
 Requires-Dist: fastavro (>=1.4.12,<2.0.0)
 Requires-Dist: geojson-pydantic (>=0.6.2,<0.7.0)
 Requires-Dist: ipython (>=8.14.0,<9.0.0)
 Requires-Dist: numpy (>=1.24.3,<2.0.0)
 Requires-Dist: orjson (>=3.8.13,<4.0.0)
+Requires-Dist: pandas (>=2.0.2,<3.0.0)
 Requires-Dist: pyarrow (>=10.0.0)
 Requires-Dist: pydantic (>=1.10.8,<2.0.0)
 Requires-Dist: pymongo (>=4.3.3,<5.0.0)
 Requires-Dist: pymongoarrow (>=0.7.0,<0.8.0)
 Requires-Dist: python-dotenv (>=0.19.0,<0.20.0)
+Requires-Dist: qlsc (>=1.0.6,<2.0.0)
 Requires-Dist: rich (>=13.3.5,<14.0.0)
 Requires-Dist: sanitize-filename (>=1.2.0,<2.0.0)
 Requires-Dist: slack-bolt (>=1.18.0,<2.0.0)
```


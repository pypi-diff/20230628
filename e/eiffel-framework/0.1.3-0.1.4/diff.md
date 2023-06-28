# Comparing `tmp/eiffel_framework-0.1.3.tar.gz` & `tmp/eiffel_framework-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "eiffel_framework-0.1.3.tar", max compression
+gzip compressed data, was "eiffel_framework-0.1.4.tar", max compression
```

## Comparing `eiffel_framework-0.1.3.tar` & `eiffel_framework-0.1.4.tar`

### file list

```diff
@@ -1,8 +1,8 @@
--rw-r--r--   0        0        0     1061 2023-06-23 15:27:52.569113 eiffel_framework-0.1.3/LICENSE
--rw-r--r--   0        0        0       77 2023-06-23 15:27:52.569233 eiffel_framework-0.1.3/README.md
--rw-r--r--   0        0        0      962 2023-06-23 15:30:11.612153 eiffel_framework-0.1.3/eiffel/__init__.py
--rw-r--r--   0        0        0      146 2023-06-23 15:30:11.612748 eiffel_framework-0.1.3/eiffel/__main__.py
--rw-r--r--   0        0        0      173 2023-06-23 15:30:11.614450 eiffel_framework-0.1.3/eiffel/module.py
--rw-r--r--   0        0        0     1294 2023-06-27 12:23:36.148934 eiffel_framework-0.1.3/pyproject.toml
--rw-r--r--   0        0        0     1183 1970-01-01 00:00:00.000000 eiffel_framework-0.1.3/setup.py
--rw-r--r--   0        0        0     1146 1970-01-01 00:00:00.000000 eiffel_framework-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0     1061 2023-06-23 15:27:52.569113 eiffel_framework-0.1.4/LICENSE
+-rw-r--r--   0        0        0       77 2023-06-23 15:27:52.569233 eiffel_framework-0.1.4/README.md
+-rw-r--r--   0        0        0      962 2023-06-23 15:30:11.612153 eiffel_framework-0.1.4/eiffel/__init__.py
+-rw-r--r--   0        0        0      146 2023-06-23 15:30:11.612748 eiffel_framework-0.1.4/eiffel/__main__.py
+-rw-r--r--   0        0        0      173 2023-06-27 22:05:43.538287 eiffel_framework-0.1.4/eiffel/module.py
+-rw-r--r--   0        0        0     1332 2023-06-28 08:22:58.969581 eiffel_framework-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0     1298 1970-01-01 00:00:00.000000 eiffel_framework-0.1.4/setup.py
+-rw-r--r--   0        0        0     1226 1970-01-01 00:00:00.000000 eiffel_framework-0.1.4/PKG-INFO
```

### Comparing `eiffel_framework-0.1.3/LICENSE` & `eiffel_framework-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `eiffel_framework-0.1.3/eiffel/__init__.py` & `eiffel_framework-0.1.4/eiffel/__init__.py`

 * *Files identical despite different names*

### Comparing `eiffel_framework-0.1.3/pyproject.toml` & `eiffel_framework-0.1.4/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,18 +1,20 @@
 [tool.poetry]
 name = "eiffel-framework"
-version = "0.1.3"
+version = "0.1.4"
 description = "Evaluation Framework for FL-based intrusion detection using Flower."
 authors = ["phdcybersec <82591009+phdcybersec@users.noreply.github.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{ include = "eiffel", from = "." }]
 
 [tool.poetry.dependencies]
 python = "~3.10"
+hydra-core = "^1.3.2"
+flwr = "^1.4.0"
 
 # darwin
 tensorflow-metal = { platform = "darwin", version = "~0.6.0", optional = true }
 tensorflow-macos = { platform = "darwin", version = "~2.10.0", optional = true }
 grpcio = { platform = "darwin", version = ">=1.37.0,<2.0", optional = true }
 h5py = { platform = "darwin", version = ">=3.6.0,<3.7", optional = true }
 numpy = { platform = "darwin", version = ">=1.23.2,<1.23.3", optional = true }
```

### Comparing `eiffel_framework-0.1.3/setup.py` & `eiffel_framework-0.1.4/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -6,34 +6,38 @@
 
 packages = \
 ['eiffel']
 
 package_data = \
 {'': ['*']}
 
+install_requires = \
+['flwr>=1.4.0,<2.0.0', 'hydra-core>=1.3.2,<2.0.0']
+
 extras_require = \
 {'darwin:sys_platform == "darwin"': ['tensorflow-metal>=0.6.0,<0.7.0',
                                      'tensorflow-macos>=2.10.0,<2.11.0',
                                      'grpcio>=1.37.0,<2.0',
                                      'h5py>=3.6.0,<3.7',
                                      'numpy>=1.23.2,<1.23.3',
                                      'protobuf>=3.19.1,<3.20']}
 
 setup_kwargs = {
     'name': 'eiffel-framework',
-    'version': '0.1.3',
+    'version': '0.1.4',
     'description': 'Evaluation Framework for FL-based intrusion detection using Flower.',
     'long_description': '# eiffel\nEvaluation framework for FL-based intrusion detection using Flower.\n',
     'author': 'phdcybersec',
     'author_email': '82591009+phdcybersec@users.noreply.github.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
     'package_dir': package_dir,
     'packages': packages,
     'package_data': package_data,
+    'install_requires': install_requires,
     'extras_require': extras_require,
     'python_requires': '>=3.10,<3.11',
 }
 
 
 setup(**setup_kwargs)
```

### Comparing `eiffel_framework-0.1.3/PKG-INFO` & `eiffel_framework-0.1.4/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,22 +1,24 @@
 Metadata-Version: 2.1
 Name: eiffel-framework
-Version: 0.1.3
+Version: 0.1.4
 Summary: Evaluation Framework for FL-based intrusion detection using Flower.
 License: MIT
 Author: phdcybersec
 Author-email: 82591009+phdcybersec@users.noreply.github.com
 Requires-Python: >=3.10,<3.11
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Provides-Extra: darwin
 Provides-Extra: linux
+Requires-Dist: flwr (>=1.4.0,<2.0.0)
 Requires-Dist: grpcio (>=1.37.0,<2.0) ; (sys_platform == "darwin") and (extra == "darwin")
 Requires-Dist: h5py (>=3.6.0,<3.7) ; (sys_platform == "darwin") and (extra == "darwin")
+Requires-Dist: hydra-core (>=1.3.2,<2.0.0)
 Requires-Dist: numpy (>=1.23.2,<1.23.3) ; (sys_platform == "darwin") and (extra == "darwin")
 Requires-Dist: protobuf (>=3.19.1,<3.20) ; (sys_platform == "darwin") and (extra == "darwin")
 Requires-Dist: tensorflow-macos (>=2.10.0,<2.11.0) ; (sys_platform == "darwin") and (extra == "darwin")
 Requires-Dist: tensorflow-metal (>=0.6.0,<0.7.0) ; (sys_platform == "darwin") and (extra == "darwin")
 Description-Content-Type: text/markdown
 
 # eiffel
```


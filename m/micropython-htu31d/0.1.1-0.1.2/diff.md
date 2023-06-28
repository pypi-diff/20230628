# Comparing `tmp/micropython-htu31d-0.1.1.tar.gz` & `tmp/micropython-htu31d-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "micropython-htu31d-0.1.1.tar", last modified: Sat Jun 17 14:13:00 2023, max compression
+gzip compressed data, was "micropython-htu31d-0.1.2.tar", last modified: Wed Jun 28 03:29:39 2023, max compression
```

## Comparing `micropython-htu31d-0.1.1.tar` & `micropython-htu31d-0.1.2.tar`

### file list

```diff
@@ -1,41 +1,40 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.415625 micropython-htu31d-0.1.1/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      447 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/.github/workflows/release_pypi.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1650 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1144 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     3004 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/.pylintrc
--rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/.readthedocs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1122 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     3207 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2454 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/docs/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/docs/_static/
--rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/_static/Logo.png
--rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/_static/Logo.png.license
--rw-r--r--   0 runner    (1001) docker     (123)      173 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/_static/extra_css.css
--rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/_static/extra_css.css.license
--rw-r--r--   0 runner    (1001) docker     (123)     4414 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/_static/favicon.ico
--rw-r--r--   0 runner    (1001) docker     (123)      105 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/_static/favicon.ico.license
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/api.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6684 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)      447 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/examples.rst
--rw-r--r--   0 runner    (1001) docker     (123)      374 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      105 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/docs/requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/examples/
--rw-r--r--   0 runner    (1001) docker     (123)      777 2023-06-17 14:12:53.000000 micropython-htu31d-0.1.1/examples/htu31d_settings_resolutions.py
--rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-17 14:12:53.000000 micropython-htu31d-0.1.1/examples/htu31d_simpletest.py
--rw-r--r--   0 runner    (1001) docker     (123)      321 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/examples.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/micropython_htu31d/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-17 14:12:53.000000 micropython-htu31d-0.1.1/micropython_htu31d/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6573 2023-06-17 14:12:53.000000 micropython-htu31d-0.1.1/micropython_htu31d/htu31d.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/micropython_htu31d.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3207 2023-06-17 14:13:00.000000 micropython-htu31d-0.1.1/micropython_htu31d.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      767 2023-06-17 14:13:00.000000 micropython-htu31d-0.1.1/micropython_htu31d.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-17 14:13:00.000000 micropython-htu31d-0.1.1/micropython_htu31d.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-17 14:13:00.000000 micropython-htu31d-0.1.1/micropython_htu31d.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-17 14:13:00.000000 micropython-htu31d-0.1.1/micropython_htu31d.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      263 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/package.json
--rw-r--r--   0 runner    (1001) docker     (123)     1160 2023-06-17 14:12:53.000000 micropython-htu31d-0.1.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-17 14:12:45.000000 micropython-htu31d-0.1.1/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-17 14:13:00.419625 micropython-htu31d-0.1.1/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.724673 micropython-htu31d-0.1.2/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      447 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/.github/workflows/release_pypi.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1650 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1144 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     3004 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/.pylintrc
+-rw-r--r--   0 runner    (1001) docker     (123)      212 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/.readthedocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1122 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     3207 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2454 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/docs/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/docs/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/_static/Logo.png
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/_static/Logo.png.license
+-rw-r--r--   0 runner    (1001) docker     (123)      173 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/_static/extra_css.css
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/_static/extra_css.css.license
+-rw-r--r--   0 runner    (1001) docker     (123)    11062 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/_static/favicon.ico
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/_static/favicon.ico.license
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/api.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     7132 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      447 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/examples.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      374 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/docs/requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     1107 2023-06-28 03:29:32.000000 micropython-htu31d-0.1.2/examples/htu31d_settings_resolutions.py
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 03:29:32.000000 micropython-htu31d-0.1.2/examples/htu31d_simpletest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      321 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/examples.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/micropython_htu31d/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:32.000000 micropython-htu31d-0.1.2/micropython_htu31d/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6600 2023-06-28 03:29:32.000000 micropython-htu31d-0.1.2/micropython_htu31d/htu31d.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/micropython_htu31d.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3207 2023-06-28 03:29:39.000000 micropython-htu31d-0.1.2/micropython_htu31d.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      726 2023-06-28 03:29:39.000000 micropython-htu31d-0.1.2/micropython_htu31d.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 03:29:39.000000 micropython-htu31d-0.1.2/micropython_htu31d.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 03:29:39.000000 micropython-htu31d-0.1.2/micropython_htu31d.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      263 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/package.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1170 2023-06-28 03:29:32.000000 micropython-htu31d-0.1.2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-28 03:29:24.000000 micropython-htu31d-0.1.2/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 03:29:39.728673 micropython-htu31d-0.1.2/setup.cfg
```

### Comparing `micropython-htu31d-0.1.1/.gitignore` & `micropython-htu31d-0.1.2/.gitignore`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/.pre-commit-config.yaml` & `micropython-htu31d-0.1.2/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/.pylintrc` & `micropython-htu31d-0.1.2/.pylintrc`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/LICENSE` & `micropython-htu31d-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/PKG-INFO` & `micropython-htu31d-0.1.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: micropython-htu31d
-Version: 0.1.1
+Version: 0.1.2
 Summary: MicroPython library for TE HTU31D temperature and humidity sensors
 Author-email: JDM <xxyx@mailmeto.mozmail.com>
 License: MIT
 Project-URL: Homepage, https://github.com/jposada202020/MicroPython_HTU31D
 Keywords: sensor,micropython,htu31d,humidity,temperature,TE,htu31d,sensor,driver,micropython
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Libraries
```

### Comparing `micropython-htu31d-0.1.1/README.rst` & `micropython-htu31d-0.1.2/README.rst`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/docs/_static/Logo.png` & `micropython-htu31d-0.1.2/docs/_static/Logo.png`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/docs/conf.py` & `micropython-htu31d-0.1.2/docs/conf.py`

 * *Files 4% similar despite different names*

```diff
@@ -6,14 +6,31 @@
 
 import os
 import sys
 import datetime
 
 sys.path.insert(0, os.path.abspath(".."))
 
+try:
+    # Inject mock modules so that we can build the
+    # documentation without having the real stuff available
+    from mock import Mock
+
+    to_be_mocked = [
+        "micropython",
+        "machine",
+    ]
+    for module in to_be_mocked:
+        sys.modules[module] = Mock()
+        print("Mocked '{}' module".format(module))
+
+    import micropython_htu31d
+except ImportError:
+    raise SystemExit("micropython_htu31d has to be importable")
+
 # -- General configuration ------------------------------------------------
 
 extensions = [
     "sphinx.ext.autodoc",
     "sphinx.ext.intersphinx",
     "sphinx.ext.napoleon",
     "sphinx.ext.viewcode",
```

### Comparing `micropython-htu31d-0.1.1/examples/htu31d_simpletest.py` & `micropython-htu31d-0.1.2/examples/htu31d_simpletest.py`

 * *Files identical despite different names*

### Comparing `micropython-htu31d-0.1.1/micropython_htu31d/htu31d.py` & `micropython-htu31d-0.1.2/micropython_htu31d/htu31d.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 from micropython import const
 
 try:
     from typing import Tuple, Any, Literal
 except ImportError:
     pass
 
-__version__ = "0.1.1"
+__version__ = "0.1.2"
 __repo__ = "https://github.com/jposada202020/MicroPython_HTU31D.git"
 
 _READSERIAL = const(0x0A)  # Read Out of Serial Register
 _SOFTRESET = const(0x1E)  # Soft Reset
 _HEATERON = const(0x04)  # Enable heater
 _HEATEROFF = const(0x02)  # Disable heater
 _CONVERSION = const(0x40)  # Start a conversion
@@ -47,21 +47,21 @@
 
     Here is an example of using the :class:`HTU31D` class.
     First you will need to import the libraries to use the sensor
 
     .. code-block:: python
 
         from machine import Pin, I2C
-        import htu31d
+        from micropython_htu31d import htu31d
 
     Once this is done you can define your `machine.I2C` object and define your sensor object
 
     .. code-block:: python
 
-        i2c = I2C(sda=Pin28), scl=Pin(3))
+        i2c = I2C(1, sda=Pin(2), scl=Pin(3))
         htu31d = htu31d.HTU31D(i2c)
 
     Now you have access to the :attr:`temperature` and :attr:`relative_humidity`
     attributes
 
     .. code-block:: python
 
@@ -178,43 +178,43 @@
             * "0.020%"
             * "0.014%"
             * "0.010%"
             * "0.007%"
 
         """
 
-        return _HUMIDITY_RES[self._conversion_command >> 4 & 3]
+        return _HUMIDITY_RES[self._conversion_command >> 3 & 3]
 
     @humidity_resolution.setter
     def humidity_resolution(
         self, value: Literal["0.020%", "0.014%", "0.010%", "0.007%"]
     ) -> None:
         if value not in _HUMIDITY_RES:
             raise ValueError(f"Humidity resolution must be one of: {_HUMIDITY_RES}")
-        register = self._conversion_command & 0xCF
+        register = self._conversion_command & 0xE7
         hum_res = _HUMIDITY_RES.index(value)
-        self._conversion_command = register | hum_res << 4
+        self._conversion_command = register | hum_res << 3
 
     @property
     def temp_resolution(self) -> Literal["0.040", "0.025", "0.016", "0.012"]:
         """The current temperature resolution in Celsius.
 
         Possibles values:
 
             * "0.040"
             * "0.025"
             * "0.016"
             * "0.012"
 
         """
 
-        return _TEMP_RES[self._conversion_command >> 2 & 3]
+        return _TEMP_RES[self._conversion_command >> 1 & 3]
 
     @temp_resolution.setter
     def temp_resolution(
         self, value: Literal["0.040", "0.025", "0.016", "0.012"]
     ) -> None:
         if value not in _TEMP_RES:
             raise ValueError(f"Temperature resolution must be one of: {_TEMP_RES}")
-        register = self._conversion_command & 0xF3
+        register = self._conversion_command & 0xF9
         temp_res = _TEMP_RES.index(value)
-        self._conversion_command = register | temp_res << 2
+        self._conversion_command = register | temp_res << 1
```

### Comparing `micropython-htu31d-0.1.1/micropython_htu31d.egg-info/PKG-INFO` & `micropython-htu31d-0.1.2/micropython_htu31d.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: micropython-htu31d
-Version: 0.1.1
+Version: 0.1.2
 Summary: MicroPython library for TE HTU31D temperature and humidity sensors
 Author-email: JDM <xxyx@mailmeto.mozmail.com>
 License: MIT
 Project-URL: Homepage, https://github.com/jposada202020/MicroPython_HTU31D
 Keywords: sensor,micropython,htu31d,humidity,temperature,TE,htu31d,sensor,driver,micropython
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Libraries
```

### Comparing `micropython-htu31d-0.1.1/micropython_htu31d.egg-info/SOURCES.txt` & `micropython-htu31d-0.1.2/micropython_htu31d.egg-info/SOURCES.txt`

 * *Files 15% similar despite different names*

```diff
@@ -23,9 +23,8 @@
 examples/htu31d_settings_resolutions.py
 examples/htu31d_simpletest.py
 micropython_htu31d/__init__.py
 micropython_htu31d/htu31d.py
 micropython_htu31d.egg-info/PKG-INFO
 micropython_htu31d.egg-info/SOURCES.txt
 micropython_htu31d.egg-info/dependency_links.txt
-micropython_htu31d.egg-info/requires.txt
 micropython_htu31d.egg-info/top_level.txt
```

### Comparing `micropython-htu31d-0.1.1/pyproject.toml` & `micropython-htu31d-0.1.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -8,15 +8,15 @@
     "wheel",
     "setuptools-scm",
 ]
 
 [project]
 name = "micropython-htu31d"
 description = "MicroPython library for TE HTU31D temperature and humidity sensors"
-version = "0.1.1"
+version = "0.1.2"
 readme = "README.rst"
 authors = [
     {name = "JDM", email = "xxyx@mailmeto.mozmail.com"}
 ]
 urls = {Homepage = "https://github.com/jposada202020/MicroPython_HTU31D"}
 keywords = [
     "sensor",
@@ -38,11 +38,11 @@
     "Topic :: System :: Hardware",
     "License :: OSI Approved :: MIT License",
     "Programming Language :: Python :: Implementation :: MicroPython",
 ]
 dynamic = ["dependencies", "optional-dependencies"]
 
 [tool.setuptools]
-py-modules = ["htu31d"]
+packages = ["micropython_htu31d"]
 
 [tool.setuptools.dynamic]
 dependencies = {file = ["requirements.txt"]}
```


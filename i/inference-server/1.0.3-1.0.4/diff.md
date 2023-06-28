# Comparing `tmp/inference-server-1.0.3.tar.gz` & `tmp/inference-server-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "inference-server-1.0.3.tar", last modified: Wed May 10 17:41:25 2023, max compression
+gzip compressed data, was "inference-server-1.0.4.tar", last modified: Wed Jun 28 09:20:04 2023, max compression
```

## Comparing `inference-server-1.0.3.tar` & `inference-server-1.0.4.tar`

### file list

```diff
@@ -1,42 +1,44 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.341382 inference-server-1.0.3/
--rw-r--r--   0 runner    (1001) docker     (123)      163 2023-05-10 17:41:12.000000 inference-server-1.0.3/.editorconfig
--rw-r--r--   0 runner    (1001) docker     (123)      804 2023-05-10 17:41:12.000000 inference-server-1.0.3/.flake8
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.333381 inference-server-1.0.3/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.337381 inference-server-1.0.3/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1502 2023-05-10 17:41:12.000000 inference-server-1.0.3/.github/workflows/release-package.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1548 2023-05-10 17:41:12.000000 inference-server-1.0.3/.github/workflows/test-package.yml
--rw-r--r--   0 runner    (1001) docker     (123)     3880 2023-05-10 17:41:12.000000 inference-server-1.0.3/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1487 2023-05-10 17:41:12.000000 inference-server-1.0.3/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-05-10 17:41:12.000000 inference-server-1.0.3/.readthedocs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)    10141 2023-05-10 17:41:12.000000 inference-server-1.0.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      564 2023-05-10 17:41:12.000000 inference-server-1.0.3/LICENSE_HEADER.txt
--rw-r--r--   0 runner    (1001) docker     (123)    14170 2023-05-10 17:41:25.341382 inference-server-1.0.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1462 2023-05-10 17:41:12.000000 inference-server-1.0.3/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.337381 inference-server-1.0.3/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     1912 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     4441 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/deployment.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5802 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/hooks.rst
--rw-r--r--   0 runner    (1001) docker     (123)      349 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      124 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/inference_server.rst
--rw-r--r--   0 runner    (1001) docker     (123)      242 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/inference_server_testing.rst
--rw-r--r--   0 runner    (1001) docker     (123)      883 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/introduction.rst
--rw-r--r--   0 runner    (1001) docker     (123)      115 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/modules.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2035 2023-05-10 17:41:12.000000 inference-server-1.0.3/docs/testing.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2674 2023-05-10 17:41:12.000000 inference-server-1.0.3/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-10 17:41:25.341382 inference-server-1.0.3/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.337381 inference-server-1.0.3/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.341382 inference-server-1.0.3/src/inference_server/
--rw-r--r--   0 runner    (1001) docker     (123)     3726 2023-05-10 17:41:12.000000 inference-server-1.0.3/src/inference_server/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5288 2023-05-10 17:41:12.000000 inference-server-1.0.3/src/inference_server/_plugin.py
--rw-r--r--   0 runner    (1001) docker     (123)     2797 2023-05-10 17:41:12.000000 inference-server-1.0.3/src/inference_server/default_plugin.py
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-05-10 17:41:12.000000 inference-server-1.0.3/src/inference_server/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2749 2023-05-10 17:41:12.000000 inference-server-1.0.3/src/inference_server/testing.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.341382 inference-server-1.0.3/src/inference_server.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14170 2023-05-10 17:41:25.000000 inference-server-1.0.3/src/inference_server.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-05-10 17:41:25.000000 inference-server-1.0.3/src/inference_server.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-10 17:41:25.000000 inference-server-1.0.3/src/inference_server.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      176 2023-05-10 17:41:25.000000 inference-server-1.0.3/src/inference_server.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-05-10 17:41:25.000000 inference-server-1.0.3/src/inference_server.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 17:41:25.341382 inference-server-1.0.3/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     2734 2023-05-10 17:41:12.000000 inference-server-1.0.3/tests/test_inference_server.py
--rw-r--r--   0 runner    (1001) docker     (123)     2178 2023-05-10 17:41:12.000000 inference-server-1.0.3/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.721482 inference-server-1.0.4/
+-rw-r--r--   0 runner    (1001) docker     (123)      163 2023-06-28 09:19:51.000000 inference-server-1.0.4/.editorconfig
+-rw-r--r--   0 runner    (1001) docker     (123)      804 2023-06-28 09:19:51.000000 inference-server-1.0.4/.flake8
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.717482 inference-server-1.0.4/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.717482 inference-server-1.0.4/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1502 2023-06-28 09:19:51.000000 inference-server-1.0.4/.github/workflows/release-package.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1548 2023-06-28 09:19:51.000000 inference-server-1.0.4/.github/workflows/test-package.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     3880 2023-06-28 09:19:51.000000 inference-server-1.0.4/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1487 2023-06-28 09:19:51.000000 inference-server-1.0.4/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-06-28 09:19:51.000000 inference-server-1.0.4/.readthedocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)    10141 2023-06-28 09:19:51.000000 inference-server-1.0.4/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      564 2023-06-28 09:19:51.000000 inference-server-1.0.4/LICENSE_HEADER.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    14170 2023-06-28 09:20:04.721482 inference-server-1.0.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1462 2023-06-28 09:19:51.000000 inference-server-1.0.4/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.721482 inference-server-1.0.4/docs/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.721482 inference-server-1.0.4/docs/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)      242 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/_static/custom.css
+-rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4441 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/deployment.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5802 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/hooks.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      349 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      124 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/inference_server.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      242 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/inference_server_testing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2591 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/introduction.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      115 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/modules.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2035 2023-06-28 09:19:51.000000 inference-server-1.0.4/docs/testing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2674 2023-06-28 09:19:51.000000 inference-server-1.0.4/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:20:04.721482 inference-server-1.0.4/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.717482 inference-server-1.0.4/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.721482 inference-server-1.0.4/src/inference_server/
+-rw-r--r--   0 runner    (1001) docker     (123)     3726 2023-06-28 09:19:51.000000 inference-server-1.0.4/src/inference_server/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5288 2023-06-28 09:19:51.000000 inference-server-1.0.4/src/inference_server/_plugin.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2797 2023-06-28 09:19:51.000000 inference-server-1.0.4/src/inference_server/default_plugin.py
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 09:19:51.000000 inference-server-1.0.4/src/inference_server/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2749 2023-06-28 09:19:51.000000 inference-server-1.0.4/src/inference_server/testing.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.721482 inference-server-1.0.4/src/inference_server.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14170 2023-06-28 09:20:04.000000 inference-server-1.0.4/src/inference_server.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      826 2023-06-28 09:20:04.000000 inference-server-1.0.4/src/inference_server.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:20:04.000000 inference-server-1.0.4/src/inference_server.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      176 2023-06-28 09:20:04.000000 inference-server-1.0.4/src/inference_server.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 09:20:04.000000 inference-server-1.0.4/src/inference_server.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:20:04.721482 inference-server-1.0.4/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     2734 2023-06-28 09:19:51.000000 inference-server-1.0.4/tests/test_inference_server.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2178 2023-06-28 09:19:51.000000 inference-server-1.0.4/tox.ini
```

### Comparing `inference-server-1.0.3/.flake8` & `inference-server-1.0.4/.flake8`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/.github/workflows/release-package.yml` & `inference-server-1.0.4/.github/workflows/release-package.yml`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/.github/workflows/test-package.yml` & `inference-server-1.0.4/.github/workflows/test-package.yml`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/.gitignore` & `inference-server-1.0.4/.gitignore`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/.pre-commit-config.yaml` & `inference-server-1.0.4/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/.readthedocs.yaml` & `inference-server-1.0.4/.readthedocs.yaml`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/LICENSE` & `inference-server-1.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/LICENSE_HEADER.txt` & `inference-server-1.0.4/LICENSE_HEADER.txt`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/PKG-INFO` & `inference-server-1.0.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: inference-server
-Version: 1.0.3
+Version: 1.0.4
 Summary: Deploy your AI/ML model to Amazon SageMaker for real-time inference using your own Docker container image.
 Author-email: "J.P. Morgan Chase & Co." <open_source@jpmorgan.com>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
```

### Comparing `inference-server-1.0.3/README.md` & `inference-server-1.0.4/README.md`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/docs/conf.py` & `inference-server-1.0.4/docs/conf.py`

 * *Files 16% similar despite different names*

```diff
@@ -47,7 +47,15 @@
     "sklearn": ("https://scikit-learn.org/stable/", None),
 }
 
 # List of patterns, relative to source directory, that match files and
 # directories to ignore when looking for source files.
 # This pattern also affects html_static_path and html_extra_path.
 exclude_patterns = ["_build", "Thumbs.db", ".DS_Store"]
+
+# These folders are copied to the documentation's HTML output
+html_static_path = ["_static"]
+
+# These paths are either relative to html_static_path or fully qualified paths (eg. https://...)
+html_css_files = [
+    "custom.css",
+]
```

### Comparing `inference-server-1.0.3/docs/deployment.rst` & `inference-server-1.0.4/docs/deployment.rst`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/docs/hooks.rst` & `inference-server-1.0.4/docs/hooks.rst`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/docs/testing.rst` & `inference-server-1.0.4/docs/testing.rst`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/pyproject.toml` & `inference-server-1.0.4/pyproject.toml`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/src/inference_server/__init__.py` & `inference-server-1.0.4/src/inference_server/__init__.py`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/src/inference_server/_plugin.py` & `inference-server-1.0.4/src/inference_server/_plugin.py`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/src/inference_server/default_plugin.py` & `inference-server-1.0.4/src/inference_server/default_plugin.py`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/src/inference_server/testing.py` & `inference-server-1.0.4/src/inference_server/testing.py`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/src/inference_server.egg-info/PKG-INFO` & `inference-server-1.0.4/src/inference_server.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: inference-server
-Version: 1.0.3
+Version: 1.0.4
 Summary: Deploy your AI/ML model to Amazon SageMaker for real-time inference using your own Docker container image.
 Author-email: "J.P. Morgan Chase & Co." <open_source@jpmorgan.com>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
```

### Comparing `inference-server-1.0.3/src/inference_server.egg-info/SOURCES.txt` & `inference-server-1.0.4/src/inference_server.egg-info/SOURCES.txt`

 * *Files 9% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 docs/hooks.rst
 docs/index.rst
 docs/inference_server.rst
 docs/inference_server_testing.rst
 docs/introduction.rst
 docs/modules.rst
 docs/testing.rst
+docs/_static/custom.css
 src/inference_server/__init__.py
 src/inference_server/_plugin.py
 src/inference_server/default_plugin.py
 src/inference_server/py.typed
 src/inference_server/testing.py
 src/inference_server.egg-info/PKG-INFO
 src/inference_server.egg-info/SOURCES.txt
```

### Comparing `inference-server-1.0.3/tests/test_inference_server.py` & `inference-server-1.0.4/tests/test_inference_server.py`

 * *Files identical despite different names*

### Comparing `inference-server-1.0.3/tox.ini` & `inference-server-1.0.4/tox.ini`

 * *Files identical despite different names*


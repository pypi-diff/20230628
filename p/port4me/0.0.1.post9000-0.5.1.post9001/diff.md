# Comparing `tmp/port4me-0.0.1.post9000.tar.gz` & `tmp/port4me-0.5.1.post9001.tar.gz`

## Comparing `port4me-0.0.1.post9000.tar` & `port4me-0.5.1.post9001.tar`

### file list

```diff
@@ -1,6 +1,11 @@
--rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 port4me-0.0.1.post9000/port4me/__init__.py
--rw-r--r--   0        0        0       39 2020-02-02 00:00:00.000000 port4me-0.0.1.post9000/.gitignore
--rw-r--r--   0        0        0       47 2020-02-02 00:00:00.000000 port4me-0.0.1.post9000/LICENSE
--rw-r--r--   0        0        0      318 2020-02-02 00:00:00.000000 port4me-0.0.1.post9000/README.md
--rw-r--r--   0        0        0      891 2020-02-02 00:00:00.000000 port4me-0.0.1.post9000/pyproject.toml
--rw-r--r--   0        0        0     1152 2020-02-02 00:00:00.000000 port4me-0.0.1.post9000/PKG-INFO
+-rw-r--r--   0        0        0      441 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/Makefile
+-rw-r--r--   0        0        0     6908 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/port4me/__init__.py
+-rw-r--r--   0        0        0     1198 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/port4me/__main__.py
+-rw-r--r--   0        0        0        1 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/tests/__init__.py
+-rw-r--r--   0        0        0     2492 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/tests/test_port4me.py
+-rw-r--r--   0        0        0      319 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/tests/test_uint_hash.py
+-rw-r--r--   0        0        0       57 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/.gitignore
+-rw-r--r--   0        0        0       64 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/LICENSE
+-rw-r--r--   0        0        0     8153 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/README.md
+-rw-r--r--   0        0        0     1110 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/pyproject.toml
+-rw-r--r--   0        0        0     9010 2020-02-02 00:00:00.000000 port4me-0.5.1.post9001/PKG-INFO
```

### Comparing `port4me-0.0.1.post9000/pyproject.toml` & `port4me-0.5.1.post9001/pyproject.toml`

 * *Files 22% similar despite different names*

```diff
@@ -1,22 +1,34 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "port4me"
-version = "0.0.1-9000"
+dynamic = ["version"]
 authors = [
   { name="Henrik Bengtsson", email="henrikb@braju.com" },
+  { name="Finn Reichertz" },
 ]
 description = "The 'port4me' tool: (1) finds a free TCP port in [1024,65535] that the user can open, (2) is designed to work in multi-user environments, (3), gives different users, different ports, (4) gives the user the same port over time with high probability, (5) gives different ports for different software tools, and (6) requires no configuration."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
 ]
 
 [project.urls]
 "Homepage" = "https://github.com/HenrikBengtsson/port4me"
 "Bug Tracker" = "https://github.com/HenrikBengtsson/port4me/issues"
+
+[tool.setuptools.dynamic]
+version = {attr = "port4me.__version__"}
+
+[tool.pytest.ini_options]
+addopts = [
+    "--import-mode=importlib",
+]
+
+[tool.hatch.version]
+path = "port4me/__init__.py"
```


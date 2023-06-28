# Comparing `tmp/qiskit_han-0.0.1.tar.gz` & `tmp/qiskit_han-0.0.2.tar.gz`

## Comparing `qiskit_han-0.0.1.tar` & `qiskit_han-0.0.2.tar`

### file list

```diff
@@ -1,10 +1,11 @@
--rw-r--r--   0        0        0     3048 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/src/qiskit_han/Untitled.ipynb
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/src/qiskit_han/__init__.py
--rw-r--r--   0        0        0     2598 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/src/qiskit_han/backend.py
--rw-r--r--   0        0        0      502 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/src/qiskit_han/job.py
--rw-r--r--   0        0        0      583 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/src/qiskit_han/provider.py
--rw-r--r--   0        0        0       72 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/src/qiskit_han/.ipynb_checkpoints/Untitled-checkpoint.ipynb
--rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/LICENSE
--rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/README.md
--rw-r--r--   0        0        0      561 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/pyproject.toml
--rw-r--r--   0        0        0      531 2020-02-02 00:00:00.000000 qiskit_han-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0     5001 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/Untitled.ipynb
+-rw-r--r--   0        0        0     5040 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/.ipynb_checkpoints/Untitled-checkpoint.ipynb
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/qiskit_han/__init__.py
+-rw-r--r--   0        0        0     2598 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/qiskit_han/backend.py
+-rw-r--r--   0        0        0      502 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/qiskit_han/job.py
+-rw-r--r--   0        0        0      594 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/qiskit_han/provider.py
+-rw-r--r--   0        0        0       72 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/qiskit_han/.ipynb_checkpoints/Untitled-checkpoint.ipynb
+-rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/LICENSE
+-rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/README.md
+-rw-r--r--   0        0        0      561 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0      531 2020-02-02 00:00:00.000000 qiskit_han-0.0.2/PKG-INFO
```

### Comparing `qiskit_han-0.0.1/src/qiskit_han/backend.py` & `qiskit_han-0.0.2/qiskit_han/backend.py`

 * *Files identical despite different names*

### Comparing `qiskit_han-0.0.1/src/qiskit_han/provider.py` & `qiskit_han-0.0.2/qiskit_han/provider.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 from qiskit.providers import ProviderV1 as Provider
 from qiskit.providers.providerutils import filter_backends
 
-from backend import HanBackend
+from qiskit_han.backend import HanBackend
 
 class MyProvider(Provider):
 
     def __init__(self, token=None):
         super().__init__()
         self.token = token
         self.backends = [HanBackend()]
```

### Comparing `qiskit_han-0.0.1/LICENSE` & `qiskit_han-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `qiskit_han-0.0.1/pyproject.toml` & `qiskit_han-0.0.2/pyproject.toml`

 * *Files 20% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling", "qiskit"]
 build-backend = "hatchling.build"
 
 [project]
 name = "qiskit_han"
-version = "0.0.1"
+version = "0.0.2"
 authors = [
   { name="Hangyul Son", email="hsn@example.com" },
 ]
 description = "qiskit provider han"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `qiskit_han-0.0.1/PKG-INFO` & `qiskit_han-0.0.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: qiskit_han
-Version: 0.0.1
+Version: 0.0.2
 Summary: qiskit provider han
 Project-URL: Homepage, https://github.com/pypa/sampleproject
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Author-email: Hangyul Son <hsn@example.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```


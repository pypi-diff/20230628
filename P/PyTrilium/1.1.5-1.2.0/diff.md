# Comparing `tmp/pytrilium-1.1.5.tar.gz` & `tmp/pytrilium-1.2.0.tar.gz`

## Comparing `pytrilium-1.1.5.tar` & `pytrilium-1.2.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
--rw-r--r--   0        0        0     1212 2020-02-02 00:00:00.000000 pytrilium-1.1.5/.drone.yml
--rw-r--r--   0        0        0     5202 2020-02-02 00:00:00.000000 pytrilium-1.1.5/CODE_OF_CONDUCT.md
--rw-r--r--   0        0        0      502 2020-02-02 00:00:00.000000 pytrilium-1.1.5/.github/dependabot.yml
--rw-r--r--   0        0        0     1330 2020-02-02 00:00:00.000000 pytrilium-1.1.5/.github/workflows/main.yml
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pytrilium-1.1.5/logs/.gitkeep
--rw-r--r--   0        0        0     3970 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTrilium.py
--rw-r--r--   0        0        0     1157 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTriliumAttributeClient.py
--rw-r--r--   0        0        0     2218 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTriliumBranchClient.py
--rw-r--r--   0        0        0     1892 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTriliumCalendarClient.py
--rw-r--r--   0        0        0     5533 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTriliumClient.py
--rw-r--r--   0        0        0      600 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTriliumCustomClient.py
--rw-r--r--   0        0        0     6260 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/PyTriliumNoteClient.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/__init__.py
--rw-r--r--   0        0        0     3355 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pytrilium/log.py
--rw-r--r--   0        0        0     2415 2020-02-02 00:00:00.000000 pytrilium-1.1.5/.gitignore
--rw-r--r--   0        0        0     1078 2020-02-02 00:00:00.000000 pytrilium-1.1.5/LICENSE
--rw-r--r--   0        0        0     3144 2020-02-02 00:00:00.000000 pytrilium-1.1.5/README.md
--rw-r--r--   0        0        0      882 2020-02-02 00:00:00.000000 pytrilium-1.1.5/pyproject.toml
--rw-r--r--   0        0        0     3719 2020-02-02 00:00:00.000000 pytrilium-1.1.5/PKG-INFO
+-rw-r--r--   0        0        0     1212 2020-02-02 00:00:00.000000 pytrilium-1.2.0/.drone.yml
+-rw-r--r--   0        0        0     5202 2020-02-02 00:00:00.000000 pytrilium-1.2.0/CODE_OF_CONDUCT.md
+-rw-r--r--   0        0        0      502 2020-02-02 00:00:00.000000 pytrilium-1.2.0/.github/dependabot.yml
+-rw-r--r--   0        0        0     1330 2020-02-02 00:00:00.000000 pytrilium-1.2.0/.github/workflows/main.yml
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pytrilium-1.2.0/logs/.gitkeep
+-rw-r--r--   0        0        0     3970 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTrilium.py
+-rw-r--r--   0        0        0     1157 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTriliumAttributeClient.py
+-rw-r--r--   0        0        0     2218 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTriliumBranchClient.py
+-rw-r--r--   0        0        0     1892 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTriliumCalendarClient.py
+-rw-r--r--   0        0        0     5263 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTriliumClient.py
+-rw-r--r--   0        0        0      600 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTriliumCustomClient.py
+-rw-r--r--   0        0        0     6260 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/PyTriliumNoteClient.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/__init__.py
+-rw-r--r--   0        0        0     3355 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pytrilium/log.py
+-rw-r--r--   0        0        0     2415 2020-02-02 00:00:00.000000 pytrilium-1.2.0/.gitignore
+-rw-r--r--   0        0        0     1078 2020-02-02 00:00:00.000000 pytrilium-1.2.0/LICENSE
+-rw-r--r--   0        0        0     3144 2020-02-02 00:00:00.000000 pytrilium-1.2.0/README.md
+-rw-r--r--   0        0        0      882 2020-02-02 00:00:00.000000 pytrilium-1.2.0/pyproject.toml
+-rw-r--r--   0        0        0     3719 2020-02-02 00:00:00.000000 pytrilium-1.2.0/PKG-INFO
```

### Comparing `pytrilium-1.1.5/.drone.yml` & `pytrilium-1.2.0/.drone.yml`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/CODE_OF_CONDUCT.md` & `pytrilium-1.2.0/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/.github/workflows/main.yml` & `pytrilium-1.2.0/.github/workflows/main.yml`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/PyTrilium.py` & `pytrilium-1.2.0/pytrilium/PyTrilium.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/PyTriliumAttributeClient.py` & `pytrilium-1.2.0/pytrilium/PyTriliumAttributeClient.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/PyTriliumBranchClient.py` & `pytrilium-1.2.0/pytrilium/PyTriliumBranchClient.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/PyTriliumCalendarClient.py` & `pytrilium-1.2.0/pytrilium/PyTriliumCalendarClient.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/PyTriliumClient.py` & `pytrilium-1.2.0/pytrilium/PyTriliumClient.py`

 * *Files 6% similar despite different names*

```diff
@@ -44,15 +44,15 @@
         self.valid_response_codes = [200, 201, 202, 204]
 
     def make_requests_session(self) -> None:
         """Creates a requests session with the token and user agent header."""
         self.session = requests.Session()
 
         # Version here
-        self.session.headers.update({"User-Agent": f"pytrilium/{self.get_version()}"})
+        self.session.headers.update({"User-Agent": "pytrilium/1.2.0"})
         #self.session.headers.update({"Content-Type": "application/json"})
 
         # Set up retry logic
         retries = Retry(total=5, backoff_factor=1, status_forcelist=[502, 503, 504])
 
         # Have it work for both http and https
         self.session.mount("https://", HTTPAdapter(max_retries=retries))
@@ -140,17 +140,7 @@
         return self.make_request("/app-info").json()
     
     def get_pyproject_toml(self) -> dict:
         """Load the pyproject.toml file. This should not be called manually."""
         import toml
         with open("pyproject.toml", "r") as f:
             return toml.load(f)
-
-    def get_version(self) -> str:
-        """Gets the version of the PyTriliumClient.
-
-        Returns
-        -------
-        str
-            The version of the PyTriliumClient.
-        """
-        return self.get_pyproject_toml()["project"]["version"]
```

### Comparing `pytrilium-1.1.5/pytrilium/PyTriliumCustomClient.py` & `pytrilium-1.2.0/pytrilium/PyTriliumCustomClient.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/PyTriliumNoteClient.py` & `pytrilium-1.2.0/pytrilium/PyTriliumNoteClient.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pytrilium/log.py` & `pytrilium-1.2.0/pytrilium/log.py`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/.gitignore` & `pytrilium-1.2.0/.gitignore`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/LICENSE` & `pytrilium-1.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/README.md` & `pytrilium-1.2.0/README.md`

 * *Files identical despite different names*

### Comparing `pytrilium-1.1.5/pyproject.toml` & `pytrilium-1.2.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "PyTrilium"
-version = "1.1.5"
+version = "1.2.0"
 authors = [
   { name="perfectra1n", email="perf3ctsec@gmail.com" },
 ]
 description = "A Python wrapper for the Trilium Notes API"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `pytrilium-1.1.5/PKG-INFO` & `pytrilium-1.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: PyTrilium
-Version: 1.1.5
+Version: 1.2.0
 Summary: A Python wrapper for the Trilium Notes API
 Project-URL: Homepage, https://github.com/perfectra1n/pytrilium
 Project-URL: Bug Tracker, https://github.com/perfectra1n/pytrilium/issues
 Author-email: perfectra1n <perf3ctsec@gmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```


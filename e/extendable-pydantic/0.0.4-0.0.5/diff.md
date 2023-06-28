# Comparing `tmp/extendable_pydantic-0.0.4.tar.gz` & `tmp/extendable_pydantic-0.0.5.tar.gz`

## Comparing `extendable_pydantic-0.0.4.tar` & `extendable_pydantic-0.0.5.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/extendable_pydantic_patcher.pth
--rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/src/extendable_pydantic/__init__.py
--rw-r--r--   0        0        0     2788 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/src/extendable_pydantic/_patch.py
--rw-r--r--   0        0        0     4538 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/src/extendable_pydantic/main.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/src/extendable_pydantic/py.typed
--rw-r--r--   0        0        0     1799 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/.gitignore
--rw-r--r--   0        0        0     1080 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/LICENSE
--rw-r--r--   0        0        0     1535 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/README.md
--rw-r--r--   0        0        0     1588 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/pyproject.toml
--rw-r--r--   0        0        0     3442 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.4/PKG-INFO
+-rw-r--r--   0        0        0       34 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/extendable_pydantic_patcher.pth
+-rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/src/extendable_pydantic/__init__.py
+-rw-r--r--   0        0        0     2788 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/src/extendable_pydantic/_patch.py
+-rw-r--r--   0        0        0     4538 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/src/extendable_pydantic/main.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/src/extendable_pydantic/py.typed
+-rw-r--r--   0        0        0     1799 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/.gitignore
+-rw-r--r--   0        0        0     1080 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/LICENSE
+-rw-r--r--   0        0        0     1535 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/README.md
+-rw-r--r--   0        0        0     1588 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/pyproject.toml
+-rw-r--r--   0        0        0     3442 2020-02-02 00:00:00.000000 extendable_pydantic-0.0.5/PKG-INFO
```

### Comparing `extendable_pydantic-0.0.4/src/extendable_pydantic/_patch.py` & `extendable_pydantic-0.0.5/src/extendable_pydantic/_patch.py`

 * *Files identical despite different names*

### Comparing `extendable_pydantic-0.0.4/src/extendable_pydantic/main.py` & `extendable_pydantic-0.0.5/src/extendable_pydantic/main.py`

 * *Files identical despite different names*

### Comparing `extendable_pydantic-0.0.4/.gitignore` & `extendable_pydantic-0.0.5/.gitignore`

 * *Files identical despite different names*

### Comparing `extendable_pydantic-0.0.4/LICENSE` & `extendable_pydantic-0.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `extendable_pydantic-0.0.4/README.md` & `extendable_pydantic-0.0.5/README.md`

 * *Files identical despite different names*

### Comparing `extendable_pydantic-0.0.4/pyproject.toml` & `extendable_pydantic-0.0.5/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 ]
 dynamic = ["version", "description"]
 dependencies = [
     "extendable>=0.0.3",
     "pydantic",
     "wrapt",
 ]
-requires-python = ">=3.7"
+requires-python = ">=3.6"
 
 [project.optional-dependencies]
 test = [
     "pytest",
     "coverage[toml]",
 ]
 mypy = [
```

### Comparing `extendable_pydantic-0.0.4/PKG-INFO` & `extendable_pydantic-0.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: extendable_pydantic
-Version: 0.0.4
+Version: 0.0.5
 Project-URL: Source, https://github.com/lmignon/extendable-pydantic
 Author-email: Laurent Mignon <laurent.mignon@acsone.eu>
 License: MIT License
         
         Copyright (c) 2021 Laurent Mignon (ACSONE)
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -24,15 +24,15 @@
         LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
         OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
         SOFTWARE.
 License-File: LICENSE
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.7
+Requires-Python: >=3.6
 Requires-Dist: extendable>=0.0.3
 Requires-Dist: pydantic
 Requires-Dist: wrapt
 Provides-Extra: mypy
 Requires-Dist: mypy; extra == 'mypy'
 Provides-Extra: test
 Requires-Dist: coverage[toml]; extra == 'test'
```


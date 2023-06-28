# Comparing `tmp/multi_start-0.0.1.tar.gz` & `tmp/multi_start-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "multi_start-0.0.1.tar", max compression
+gzip compressed data, was "multi_start-0.0.2.tar", max compression
```

## Comparing `multi_start-0.0.1.tar` & `multi_start-0.0.2.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1494 2023-06-28 09:32:26.735498 multi_start-0.0.1/LICENSE
--rw-r--r--   0        0        0      596 2023-06-28 09:32:26.735498 multi_start-0.0.1/README.md
--rw-r--r--   0        0        0      757 2023-06-28 09:32:26.735498 multi_start-0.0.1/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-28 09:32:26.735498 multi_start-0.0.1/src/__init__.py
--rw-r--r--   0        0        0     2443 2023-06-28 09:32:26.735498 multi_start-0.0.1/src/cli.py
--rw-r--r--   0        0        0     6135 2023-06-28 09:32:26.735498 multi_start-0.0.1/src/starter.py
--rw-r--r--   0        0        0     1257 1970-01-01 00:00:00.000000 multi_start-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0     1494 2023-06-28 14:30:20.736815 multi_start-0.0.2/LICENSE
+-rw-r--r--   0        0        0      596 2023-06-28 14:30:20.736815 multi_start-0.0.2/README.md
+-rw-r--r--   0        0        0      757 2023-06-28 14:30:20.736815 multi_start-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 14:30:20.736815 multi_start-0.0.2/src/__init__.py
+-rw-r--r--   0        0        0     2443 2023-06-28 14:30:20.736815 multi_start-0.0.2/src/cli.py
+-rw-r--r--   0        0        0     6135 2023-06-28 14:30:20.736815 multi_start-0.0.2/src/starter.py
+-rw-r--r--   0        0        0     1257 1970-01-01 00:00:00.000000 multi_start-0.0.2/PKG-INFO
```

### Comparing `multi_start-0.0.1/LICENSE` & `multi_start-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `multi_start-0.0.1/README.md` & `multi_start-0.0.2/README.md`

 * *Files identical despite different names*

### Comparing `multi_start-0.0.1/pyproject.toml` & `multi_start-0.0.2/pyproject.toml`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "multi-start"
-version = "0.0.1"
+version = "0.0.2"
 description = "Run multiple services inside a docker container"
 license = "BSD-3-Clause"
 readme = "README.md"
 repository = "https://github.com/ioxiocom/multi-start"
 authors = ["IOXIO Ltd"]
 packages = [
     {include="src", from="."}
```

### Comparing `multi_start-0.0.1/src/cli.py` & `multi_start-0.0.2/src/cli.py`

 * *Files identical despite different names*

### Comparing `multi_start-0.0.1/src/starter.py` & `multi_start-0.0.2/src/starter.py`

 * *Files 1% similar despite different names*

```diff
@@ -51,15 +51,15 @@
 
 def debug_msg(msg: str) -> None:
     """
     Print message only when DEBUG environment variable is set
     :param msg: Message to print
     """
     if os.environ.get("DEBUG"):
-        print(str)
+        print(msg)
 
 
 async def run_and_wait(cmd, cwd=None):
     proc = await run(cmd, cwd)
     code = await proc.wait()
     if code != 0:
         raise RuntimeError(f"{cmd} failed with code {code}")
```

### Comparing `multi_start-0.0.1/PKG-INFO` & `multi_start-0.0.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: multi-start
-Version: 0.0.1
+Version: 0.0.2
 Summary: Run multiple services inside a docker container
 Home-page: https://github.com/ioxiocom/multi-start
 License: BSD-3-Clause
 Author: IOXIO Ltd
 Requires-Python: >=3.10,<4.0
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Programming Language :: Python :: 3
```


# Comparing `tmp/toontown_utils-2.0.0.tar.gz` & `tmp/toontown_utils-2.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "toontown_utils-2.0.0.tar", max compression
+gzip compressed data, was "toontown_utils-2.0.1.tar", max compression
```

## Comparing `toontown_utils-2.0.0.tar` & `toontown_utils-2.0.1.tar`

### file list

```diff
@@ -1,20 +1,33 @@
--rw-r--r--   0        0        0     1067 2023-06-13 05:24:07.094841 toontown_utils-2.0.0/LICENSE
--rw-r--r--   0        0        0      509 2023-06-26 04:38:50.278471 toontown_utils-2.0.0/pyproject.toml
--rw-r--r--   0        0        0     1336 2023-06-26 05:18:03.141824 toontown_utils-2.0.0/README.md
--rw-r--r--   0        0        0        0 2023-06-25 20:32:20.704870 toontown_utils-2.0.0/toontown_utils/__init__.py
--rw-r--r--   0        0        0        0 2023-06-25 20:32:20.706865 toontown_utils-2.0.0/toontown_utils/cog/__init__.py
--rw-r--r--   0        0        0    15277 2023-06-25 20:32:20.705867 toontown_utils-2.0.0/toontown_utils/cog/CogActor.py
--rw-r--r--   0        0        0      328 2023-06-25 20:32:20.705867 toontown_utils-2.0.0/toontown_utils/cog/CogBody.py
--rw-r--r--   0        0        0      749 2023-06-25 20:32:20.705867 toontown_utils-2.0.0/toontown_utils/cog/CogGlobals.py
--rw-r--r--   0        0        0     5583 2023-06-25 20:32:20.705867 toontown_utils-2.0.0/toontown_utils/cog/CogLoader.py
--rw-r--r--   0        0        0      312 2023-06-25 20:32:20.706865 toontown_utils-2.0.0/toontown_utils/cog/Department.py
--rw-r--r--   0        0        0      404 2023-06-25 20:32:20.706865 toontown_utils-2.0.0/toontown_utils/cog/TemplateCog.py
--rw-r--r--   0        0        0      599 2023-06-25 23:24:48.000385 toontown_utils-2.0.0/toontown_utils/LoaderUtils.py
--rw-r--r--   0        0        0     1704 2023-06-25 21:14:59.680631 toontown_utils-2.0.0/toontown_utils/TemplateManager.py
--rw-r--r--   0        0        0        0 2023-06-25 20:32:20.708859 toontown_utils-2.0.0/toontown_utils/toon/__init__.py
--rw-r--r--   0        0        0     6976 2023-06-26 04:39:59.415149 toontown_utils-2.0.0/toontown_utils/toon/ToonActor.py
--rw-r--r--   0        0        0      458 2023-06-25 20:32:20.707862 toontown_utils-2.0.0/toontown_utils/toon/ToonHead.py
--rw-r--r--   0        0        0     4030 2023-06-25 20:32:20.707862 toontown_utils-2.0.0/toontown_utils/toon/ToonLoader.py
--rw-r--r--   0        0        0      107 2023-06-25 20:32:20.707862 toontown_utils-2.0.0/toontown_utils/toon/ToonPart.py
--rw-r--r--   0        0        0      173 2023-06-25 20:32:20.708859 toontown_utils-2.0.0/toontown_utils/toon/ToonSpecies.py
--rw-r--r--   0        0        0     1914 1970-01-01 00:00:00.000000 toontown_utils-2.0.0/PKG-INFO
+-rw-r--r--   0        0        0     1067 2023-06-13 05:24:07.094841 toontown_utils-2.0.1/LICENSE
+-rw-r--r--   0        0        0      509 2023-06-28 03:34:41.559090 toontown_utils-2.0.1/pyproject.toml
+-rw-r--r--   0        0        0     1336 2023-06-26 05:18:03.141824 toontown_utils-2.0.1/README.md
+-rw-r--r--   0        0        0        0 2023-06-25 20:32:20.704870 toontown_utils-2.0.1/toontown_utils/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-25 20:32:20.706865 toontown_utils-2.0.1/toontown_utils/cog/__init__.py
+-rw-r--r--   0        0        0      172 2023-06-27 05:04:32.766984 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0    22450 2023-06-27 05:04:32.901770 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/CogActor.cpython-311.pyc
+-rw-r--r--   0        0        0     1104 2023-06-27 05:04:32.791034 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/CogBody.cpython-311.pyc
+-rw-r--r--   0        0        0     1273 2023-06-27 05:04:32.933685 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/CogGlobals.cpython-311.pyc
+-rw-r--r--   0        0        0     8064 2023-06-27 05:04:32.778069 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/CogLoader.cpython-311.pyc
+-rw-r--r--   0        0        0     1070 2023-06-27 05:04:32.782060 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/Department.cpython-311.pyc
+-rw-r--r--   0        0        0     1026 2023-06-27 05:04:32.780069 toontown_utils-2.0.1/toontown_utils/cog/__pycache__/TemplateCog.cpython-311.pyc
+-rw-r--r--   0        0        0    15277 2023-06-25 20:32:20.705867 toontown_utils-2.0.1/toontown_utils/cog/CogActor.py
+-rw-r--r--   0        0        0      328 2023-06-25 20:32:20.705867 toontown_utils-2.0.1/toontown_utils/cog/CogBody.py
+-rw-r--r--   0        0        0      749 2023-06-25 20:32:20.705867 toontown_utils-2.0.1/toontown_utils/cog/CogGlobals.py
+-rw-r--r--   0        0        0     5583 2023-06-25 20:32:20.705867 toontown_utils-2.0.1/toontown_utils/cog/CogLoader.py
+-rw-r--r--   0        0        0      312 2023-06-25 20:32:20.706865 toontown_utils-2.0.1/toontown_utils/cog/Department.py
+-rw-r--r--   0        0        0      404 2023-06-25 20:32:20.706865 toontown_utils-2.0.1/toontown_utils/cog/TemplateCog.py
+-rw-r--r--   0        0        0      599 2023-06-25 23:24:48.000385 toontown_utils-2.0.1/toontown_utils/LoaderUtils.py
+-rw-r--r--   0        0        0     1704 2023-06-25 21:14:59.680631 toontown_utils-2.0.1/toontown_utils/TemplateManager.py
+-rw-r--r--   0        0        0        0 2023-06-25 20:32:20.708859 toontown_utils-2.0.1/toontown_utils/toon/__init__.py
+-rw-r--r--   0        0        0      173 2023-06-27 05:04:32.792031 toontown_utils-2.0.1/toontown_utils/toon/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0    13925 2023-06-28 03:24:25.993002 toontown_utils-2.0.1/toontown_utils/toon/__pycache__/ToonActor.cpython-311.pyc
+-rw-r--r--   0        0        0     1346 2023-06-27 05:04:32.837941 toontown_utils-2.0.1/toontown_utils/toon/__pycache__/ToonHead.cpython-311.pyc
+-rw-r--r--   0        0        0     6308 2023-06-27 05:04:32.822980 toontown_utils-2.0.1/toontown_utils/toon/__pycache__/ToonLoader.cpython-311.pyc
+-rw-r--r--   0        0        0      569 2023-06-27 05:04:32.824975 toontown_utils-2.0.1/toontown_utils/toon/__pycache__/ToonPart.cpython-311.pyc
+-rw-r--r--   0        0        0      680 2023-06-27 05:04:32.825972 toontown_utils-2.0.1/toontown_utils/toon/__pycache__/ToonSpecies.cpython-311.pyc
+-rw-r--r--   0        0        0     7143 2023-06-28 03:33:00.858015 toontown_utils-2.0.1/toontown_utils/toon/ToonActor.py
+-rw-r--r--   0        0        0      458 2023-06-25 20:32:20.707862 toontown_utils-2.0.1/toontown_utils/toon/ToonHead.py
+-rw-r--r--   0        0        0     4030 2023-06-25 20:32:20.707862 toontown_utils-2.0.1/toontown_utils/toon/ToonLoader.py
+-rw-r--r--   0        0        0      107 2023-06-25 20:32:20.707862 toontown_utils-2.0.1/toontown_utils/toon/ToonPart.py
+-rw-r--r--   0        0        0      173 2023-06-25 20:32:20.708859 toontown_utils-2.0.1/toontown_utils/toon/ToonSpecies.py
+-rw-r--r--   0        0        0     1914 1970-01-01 00:00:00.000000 toontown_utils-2.0.1/PKG-INFO
```

### Comparing `toontown_utils-2.0.0/LICENSE` & `toontown_utils-2.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/README.md` & `toontown_utils-2.0.1/README.md`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/toontown_utils/cog/CogActor.py` & `toontown_utils-2.0.1/toontown_utils/cog/CogActor.py`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/toontown_utils/cog/CogGlobals.py` & `toontown_utils-2.0.1/toontown_utils/cog/CogGlobals.py`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/toontown_utils/cog/CogLoader.py` & `toontown_utils-2.0.1/toontown_utils/cog/CogLoader.py`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/toontown_utils/LoaderUtils.py` & `toontown_utils-2.0.1/toontown_utils/LoaderUtils.py`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/toontown_utils/TemplateManager.py` & `toontown_utils-2.0.1/toontown_utils/TemplateManager.py`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/toontown_utils/toon/ToonActor.py` & `toontown_utils-2.0.1/toontown_utils/toon/ToonActor.py`

 * *Files 1% similar despite different names*

```diff
@@ -68,15 +68,19 @@
         # TODO: maybe remove nodes instead of stashing them
         self.loadModel(head.model, "head")
         if head.anims is not None:
             self.loadAnims(head.anims, "head")
         self.head: NodePath = self.getPart("head")
 
         if not head.keepAllParts:
-            self.head.getChildren()[0].getChildren().stash()
+            # TODO: dirty fix, do this better
+            if self.head.getNumChildren() > 1:
+                self.head.getChildren().stash()
+            else:
+                self.head.getChildren()[0].getChildren().stash()
             if head.keepParts is not None:
                 for part in head.keepParts:
                     partNode: NodePath = self.head.find(f"**/{part};+s")
                     if partNode.isEmpty():
                         continue
                     partNode.unstash()
```

### Comparing `toontown_utils-2.0.0/toontown_utils/toon/ToonLoader.py` & `toontown_utils-2.0.1/toontown_utils/toon/ToonLoader.py`

 * *Files identical despite different names*

### Comparing `toontown_utils-2.0.0/PKG-INFO` & `toontown_utils-2.0.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: toontown-utils
-Version: 2.0.0
+Version: 2.0.1
 Summary: Toontown-specific utilities for Panda3D
 Home-page: https://github.com/demiurgeQuantified/ToontownUtils
 License: MIT
 Author: albion
 Author-email: 8355611+demiurgeQuantified@users.noreply.github.com
 Requires-Python: >=3.11,<4.0
 Classifier: License :: OSI Approved :: MIT License
```


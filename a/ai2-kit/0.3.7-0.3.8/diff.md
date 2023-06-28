# Comparing `tmp/ai2_kit-0.3.7.tar.gz` & `tmp/ai2_kit-0.3.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ai2_kit-0.3.7.tar", max compression
+gzip compressed data, was "ai2_kit-0.3.8.tar", max compression
```

## Comparing `ai2_kit-0.3.7.tar` & `ai2_kit-0.3.8.tar`

### file list

```diff
@@ -1,37 +1,37 @@
--rw-r--r--   0        0        0     1067 2023-02-07 08:30:11.900671 ai2_kit-0.3.7/LICENSE
--rw-r--r--   0        0        0     1627 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/README.md
--rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.7/ai2_kit/__init__.py
--rw-r--r--   0        0        0        0 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/algorithm/__init__.py
--rw-r--r--   0        0        0    12100 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/algorithm/proton_transfer.py
--rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.7/ai2_kit/core/__init__.py
--rw-r--r--   0        0        0     1854 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/core/artifact.py
--rw-r--r--   0        0        0     5465 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/core/checkpoint.py
--rw-r--r--   0        0        0      169 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/core/cmd.py
--rw-r--r--   0        0        0     5766 2023-02-06 09:01:27.000000 ai2_kit-0.3.7/ai2_kit/core/connector.py
--rw-r--r--   0        0        0     7939 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/core/executor.py
--rw-r--r--   0        0        0      365 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/core/future.py
--rw-r--r--   0        0        0     1852 2023-06-28 01:16:35.057371 ai2_kit-0.3.7/ai2_kit/core/job.py
--rw-r--r--   0        0        0      298 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/core/log.py
--rw-r--r--   0        0        0     9449 2023-06-28 02:30:53.156473 ai2_kit-0.3.7/ai2_kit/core/queue_system.py
--rw-r--r--   0        0        0     2572 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/core/resource_manager.py
--rw-r--r--   0        0        0     2358 2023-06-19 08:54:25.567391 ai2_kit-0.3.7/ai2_kit/core/script.py
--rw-r--r--   0        0        0     4195 2023-06-28 02:30:46.056474 ai2_kit-0.3.7/ai2_kit/core/util.py
--rw-r--r--   0        0        0        0 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/dflow/__init__.py
--rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.7/ai2_kit/domain/__init__.py
--rw-r--r--   0        0        0     1734 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/domain/cll.py
--rw-r--r--   0        0        0      381 2023-06-28 02:30:53.156473 ai2_kit-0.3.7/ai2_kit/domain/constant.py
--rw-r--r--   0        0        0     8210 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/domain/cp2k.py
--rw-r--r--   0        0        0     4424 2023-06-28 02:30:53.156473 ai2_kit-0.3.7/ai2_kit/domain/data_helper.py
--rw-r--r--   0        0        0     7169 2023-06-28 02:30:53.156473 ai2_kit-0.3.7/ai2_kit/domain/deepmd.py
--rw-r--r--   0        0        0    16845 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/domain/lammps.py
--rw-r--r--   0        0        0     3039 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/domain/selector.py
--rw-r--r--   0        0        0      183 2023-03-22 04:23:44.538179 ai2_kit-0.3.7/ai2_kit/domain/updater.py
--rw-r--r--   0        0        0     9346 2023-06-28 02:30:53.156473 ai2_kit-0.3.7/ai2_kit/domain/vasp.py
--rw-r--r--   0        0        0     1588 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/main.py
--rw-r--r--   0        0        0        0 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/tool/__init__.py
--rw-r--r--   0        0        0      676 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/tool/ase.py
--rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.7/ai2_kit/workflow/__init__.py
--rw-r--r--   0        0        0     9230 2023-06-28 02:30:53.156473 ai2_kit-0.3.7/ai2_kit/workflow/cll_mlp.py
--rw-r--r--   0        0        0     9117 2023-06-28 01:16:35.067371 ai2_kit-0.3.7/ai2_kit/workflow/fep_mlp.py
--rw-r--r--   0        0        0      843 2023-06-28 02:34:31.616425 ai2_kit-0.3.7/pyproject.toml
--rw-r--r--   0        0        0     2654 1970-01-01 00:00:00.000000 ai2_kit-0.3.7/PKG-INFO
+-rw-r--r--   0        0        0     1067 2023-02-07 08:30:11.900671 ai2_kit-0.3.8/LICENSE
+-rw-r--r--   0        0        0     1627 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/README.md
+-rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.8/ai2_kit/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/algorithm/__init__.py
+-rw-r--r--   0        0        0    12100 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/algorithm/proton_transfer.py
+-rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.8/ai2_kit/core/__init__.py
+-rw-r--r--   0        0        0     1854 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/core/artifact.py
+-rw-r--r--   0        0        0     5465 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/core/checkpoint.py
+-rw-r--r--   0        0        0      169 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/core/cmd.py
+-rw-r--r--   0        0        0     5766 2023-02-06 09:01:27.000000 ai2_kit-0.3.8/ai2_kit/core/connector.py
+-rw-r--r--   0        0        0     7939 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/core/executor.py
+-rw-r--r--   0        0        0      365 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/core/future.py
+-rw-r--r--   0        0        0     1852 2023-06-28 01:16:35.057371 ai2_kit-0.3.8/ai2_kit/core/job.py
+-rw-r--r--   0        0        0      298 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/core/log.py
+-rw-r--r--   0        0        0     9449 2023-06-28 02:30:53.156473 ai2_kit-0.3.8/ai2_kit/core/queue_system.py
+-rw-r--r--   0        0        0     2572 2023-06-28 06:44:38.463386 ai2_kit-0.3.8/ai2_kit/core/resource_manager.py
+-rw-r--r--   0        0        0     2358 2023-06-19 08:54:25.567391 ai2_kit-0.3.8/ai2_kit/core/script.py
+-rw-r--r--   0        0        0     4195 2023-06-28 08:04:13.892405 ai2_kit-0.3.8/ai2_kit/core/util.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/dflow/__init__.py
+-rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.8/ai2_kit/domain/__init__.py
+-rw-r--r--   0        0        0     1734 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/domain/cll.py
+-rw-r--r--   0        0        0      381 2023-06-28 02:30:53.156473 ai2_kit-0.3.8/ai2_kit/domain/constant.py
+-rw-r--r--   0        0        0     8210 2023-06-28 08:04:13.892405 ai2_kit-0.3.8/ai2_kit/domain/cp2k.py
+-rw-r--r--   0        0        0     4424 2023-06-28 02:30:53.156473 ai2_kit-0.3.8/ai2_kit/domain/data_helper.py
+-rw-r--r--   0        0        0     7169 2023-06-28 02:30:53.156473 ai2_kit-0.3.8/ai2_kit/domain/deepmd.py
+-rw-r--r--   0        0        0    16845 2023-06-28 08:04:13.892405 ai2_kit-0.3.8/ai2_kit/domain/lammps.py
+-rw-r--r--   0        0        0     3039 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/domain/selector.py
+-rw-r--r--   0        0        0      183 2023-06-28 03:52:57.155461 ai2_kit-0.3.8/ai2_kit/domain/updater.py
+-rw-r--r--   0        0        0     9346 2023-06-28 02:30:53.156473 ai2_kit-0.3.8/ai2_kit/domain/vasp.py
+-rw-r--r--   0        0        0     1588 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/main.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/tool/__init__.py
+-rw-r--r--   0        0        0     1039 2023-06-28 08:16:01.942257 ai2_kit-0.3.8/ai2_kit/tool/ase.py
+-rw-r--r--   0        0        0        0 2023-02-06 09:01:27.000000 ai2_kit-0.3.8/ai2_kit/workflow/__init__.py
+-rw-r--r--   0        0        0     9230 2023-06-28 03:52:57.155461 ai2_kit-0.3.8/ai2_kit/workflow/cll_mlp.py
+-rw-r--r--   0        0        0     9117 2023-06-28 01:16:35.067371 ai2_kit-0.3.8/ai2_kit/workflow/fep_mlp.py
+-rw-r--r--   0        0        0      843 2023-06-28 08:18:00.732237 ai2_kit-0.3.8/pyproject.toml
+-rw-r--r--   0        0        0     2654 1970-01-01 00:00:00.000000 ai2_kit-0.3.8/PKG-INFO
```

### Comparing `ai2_kit-0.3.7/LICENSE` & `ai2_kit-0.3.8/LICENSE`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/README.md` & `ai2_kit-0.3.8/README.md`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/algorithm/proton_transfer.py` & `ai2_kit-0.3.8/ai2_kit/algorithm/proton_transfer.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/artifact.py` & `ai2_kit-0.3.8/ai2_kit/core/artifact.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/checkpoint.py` & `ai2_kit-0.3.8/ai2_kit/core/checkpoint.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/connector.py` & `ai2_kit-0.3.8/ai2_kit/core/connector.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/executor.py` & `ai2_kit-0.3.8/ai2_kit/core/executor.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/job.py` & `ai2_kit-0.3.8/ai2_kit/core/job.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/queue_system.py` & `ai2_kit-0.3.8/ai2_kit/core/queue_system.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/resource_manager.py` & `ai2_kit-0.3.8/ai2_kit/core/resource_manager.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/script.py` & `ai2_kit-0.3.8/ai2_kit/core/script.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/core/util.py` & `ai2_kit-0.3.8/ai2_kit/core/util.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/cll.py` & `ai2_kit-0.3.8/ai2_kit/domain/cll.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/cp2k.py` & `ai2_kit-0.3.8/ai2_kit/domain/cp2k.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/data_helper.py` & `ai2_kit-0.3.8/ai2_kit/domain/data_helper.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/deepmd.py` & `ai2_kit-0.3.8/ai2_kit/domain/deepmd.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/lammps.py` & `ai2_kit-0.3.8/ai2_kit/domain/lammps.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/selector.py` & `ai2_kit-0.3.8/ai2_kit/domain/selector.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/domain/vasp.py` & `ai2_kit-0.3.8/ai2_kit/domain/vasp.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/main.py` & `ai2_kit-0.3.8/ai2_kit/main.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/tool/ase.py` & `ai2_kit-0.3.8/ai2_kit/tool/ase.py`

 * *Files 14% similar despite different names*

```diff
@@ -13,10 +13,21 @@
             data = [data]
         self._atoms_list = data
         return self
 
     def write(self, filename: str, **kwargs):
         ase.io.write(filename, self._atoms_list, **kwargs)
 
+    def set_cell(self, cell, scale_atoms=False, apply_constraint=True):
+        for atoms in self._atoms_list:
+            atoms.set_cell(cell, scale_atoms=scale_atoms, apply_constraint=apply_constraint)
+        return self
+
+    def set_pbc(self, pbc):
+        print(pbc)
+        for atoms in self._atoms_list:
+            atoms.set_pbc(pbc)
+        return self
+
     def write_each_frame(self, filename: str, **kwargs):
         for i, atoms in enumerate(self._atoms_list):
             ase.io.write(filename.format(i=i), atoms, **kwargs)
```

### Comparing `ai2_kit-0.3.7/ai2_kit/workflow/cll_mlp.py` & `ai2_kit-0.3.8/ai2_kit/workflow/cll_mlp.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/ai2_kit/workflow/fep_mlp.py` & `ai2_kit-0.3.8/ai2_kit/workflow/fep_mlp.py`

 * *Files identical despite different names*

### Comparing `ai2_kit-0.3.7/pyproject.toml` & `ai2_kit-0.3.8/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "ai2-kit"
-version = "0.3.7"
+version = "0.3.8"
 description = ""
 authors = ["weihong.xu <xuweihong.cn@gmail.com>"]
 readme = "README.md"
 packages = [{include = "ai2_kit"}]
 
 [tool.poetry.dependencies]
 python = "^3.8"
```

### Comparing `ai2_kit-0.3.7/PKG-INFO` & `ai2_kit-0.3.8/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ai2-kit
-Version: 0.3.7
+Version: 0.3.8
 Summary: 
 Author: weihong.xu
 Author-email: xuweihong.cn@gmail.com
 Requires-Python: >=3.8,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
```


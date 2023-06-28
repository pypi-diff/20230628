# Comparing `tmp/hadder-1.7.tar.gz` & `tmp/hadder-1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hadder-1.7.tar", last modified: Mon Jan 30 02:07:55 2023, max compression
+gzip compressed data, was "hadder-1.8.tar", last modified: Wed Jun 28 07:08:28 2023, max compression
```

## Comparing `hadder-1.7.tar` & `hadder-1.8.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 dechin    (1000) dechin    (1000)        0 2023-01-30 02:07:55.916657 hadder-1.7/
--rw-r--r--   0 dechin    (1000) dechin    (1000)    11357 2022-06-24 11:42:21.000000 hadder-1.7/LICENSE
--rw-r--r--   0 dechin    (1000) dechin    (1000)     3200 2023-01-30 02:07:55.916657 hadder-1.7/PKG-INFO
--rw-r--r--   0 dechin    (1000) dechin    (1000)     2901 2022-09-03 15:04:30.000000 hadder-1.7/README.md
-drwxr-xr-x   0 dechin    (1000) dechin    (1000)        0 2023-01-30 02:07:55.916657 hadder-1.7/hadder/
--rw-r--r--   0 dechin    (1000) dechin    (1000)     8549 2023-01-11 08:20:32.000000 hadder-1.7/hadder/__init__.py
--rw-r--r--   0 dechin    (1000) dechin    (1000)      893 2022-09-03 15:04:30.000000 hadder-1.7/hadder/__main__.py
--rw-r--r--   0 dechin    (1000) dechin    (1000)    40338 2023-01-30 02:05:00.000000 hadder-1.7/hadder/constants.py
--rw-r--r--   0 dechin    (1000) dechin    (1000)     6755 2023-01-11 07:31:48.000000 hadder-1.7/hadder/parsers.py
-drwxr-xr-x   0 dechin    (1000) dechin    (1000)        0 2023-01-30 02:07:55.916657 hadder-1.7/hadder.egg-info/
--rw-r--r--   0 dechin    (1000) dechin    (1000)     3200 2023-01-30 02:07:55.000000 hadder-1.7/hadder.egg-info/PKG-INFO
--rw-r--r--   0 dechin    (1000) dechin    (1000)      251 2023-01-30 02:07:55.000000 hadder-1.7/hadder.egg-info/SOURCES.txt
--rw-r--r--   0 dechin    (1000) dechin    (1000)        1 2023-01-30 02:07:55.000000 hadder-1.7/hadder.egg-info/dependency_links.txt
--rw-r--r--   0 dechin    (1000) dechin    (1000)       20 2023-01-30 02:07:55.000000 hadder-1.7/hadder.egg-info/requires.txt
--rw-r--r--   0 dechin    (1000) dechin    (1000)        7 2023-01-30 02:07:55.000000 hadder-1.7/hadder.egg-info/top_level.txt
--rw-r--r--   0 dechin    (1000) dechin    (1000)       38 2023-01-30 02:07:55.916657 hadder-1.7/setup.cfg
--rw-r--r--   0 dechin    (1000) dechin    (1000)     1488 2023-01-30 02:07:25.000000 hadder-1.7/setup.py
+drwxrwxr-x   0 dechin    (1001) dechin    (1001)        0 2023-06-28 07:08:28.886664 hadder-1.8/
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)    11357 2023-06-27 09:36:35.000000 hadder-1.8/LICENSE
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)     3199 2023-06-28 07:08:28.886664 hadder-1.8/PKG-INFO
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)     2901 2023-06-27 09:36:35.000000 hadder-1.8/README.md
+drwxrwxr-x   0 dechin    (1001) dechin    (1001)        0 2023-06-28 07:08:28.886664 hadder-1.8/hadder/
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)     8549 2023-06-27 09:36:35.000000 hadder-1.8/hadder/__init__.py
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)      893 2023-06-27 09:36:35.000000 hadder-1.8/hadder/__main__.py
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)    40338 2023-06-27 09:36:35.000000 hadder-1.8/hadder/constants.py
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)     6476 2023-06-28 07:07:08.000000 hadder-1.8/hadder/parsers.py
+drwxrwxr-x   0 dechin    (1001) dechin    (1001)        0 2023-06-28 07:08:28.886664 hadder-1.8/hadder.egg-info/
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)     3199 2023-06-28 07:08:28.000000 hadder-1.8/hadder.egg-info/PKG-INFO
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)      251 2023-06-28 07:08:28.000000 hadder-1.8/hadder.egg-info/SOURCES.txt
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)        1 2023-06-28 07:08:28.000000 hadder-1.8/hadder.egg-info/dependency_links.txt
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)       20 2023-06-28 07:08:28.000000 hadder-1.8/hadder.egg-info/requires.txt
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)        7 2023-06-28 07:08:28.000000 hadder-1.8/hadder.egg-info/top_level.txt
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)       38 2023-06-28 07:08:28.890664 hadder-1.8/setup.cfg
+-rw-rw-r--   0 dechin    (1001) dechin    (1001)     1488 2023-06-28 07:07:50.000000 hadder-1.8/setup.py
```

### Comparing `hadder-1.7/LICENSE` & `hadder-1.8/LICENSE`

 * *Files identical despite different names*

### Comparing `hadder-1.7/PKG-INFO` & `hadder-1.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hadder
-Version: 1.7
+Version: 1.8
 Summary: Hydrogen adder for pdb protein files
 Home-page: https://gitee.com/dechin/hadder
 Author: Dechin CHEN
 Author-email: dechin.phy@gmail.com
 License: Apache 2.0 Licence
 Platform: any
 Description-Content-Type: text/markdown
@@ -72,8 +72,7 @@
 如果返回的结果为空，即表明当前路径下的所有python文件符合相关的规范要求，可以提交PR进入审核阶段。
 
 # 博客推荐
 1. [从Hadder看蛋白质分子中的加氢算法](https://www.cnblogs.com/dechinphy/p/hadder.html)
 2. [用脚本的形式运行Hadder](https://www.cnblogs.com/dechinphy/p/pym.html)
 3. [蛋白质基础组成结构](https://www.cnblogs.com/dechinphy/p/pdb.html)
 4. [氨基酸分子结构和原子命名](https://www.cnblogs.com/dechinphy/p/cnaminos.html)
-
```

### Comparing `hadder-1.7/README.md` & `hadder-1.8/README.md`

 * *Files identical despite different names*

### Comparing `hadder-1.7/hadder/__init__.py` & `hadder-1.8/hadder/__init__.py`

 * *Files identical despite different names*

### Comparing `hadder-1.7/hadder/__main__.py` & `hadder-1.8/hadder/__main__.py`

 * *Files identical despite different names*

### Comparing `hadder-1.7/hadder/constants.py` & `hadder-1.8/hadder/constants.py`

 * *Files identical despite different names*

### Comparing `hadder-1.7/hadder/parsers.py` & `hadder-1.8/hadder/parsers.py`

 * *Files 5% similar despite different names*

```diff
@@ -76,38 +76,29 @@
         if res_ids == []:
             res_ids.append(res_id)
             res_names.append(res_name)
             atom_group.append(atom_name)
             crd_group.append(crd)
             res_pointer.append(0)
             atom_pos = np.zeros((14, 3))
-            if not atom_name.startswith('H') and atom_name != 'OXT':
-                atom_pos[atom14_order_dict[res_name]
-                         [atom_name]] = np.array(crd)
         elif res_id != res_ids[-1]:
             atom14_positions.append(atom_pos)
             atom_pos = np.zeros((14, 3))
-            if not atom_name.startswith('H') and atom_name != 'OXT':
-                atom_pos[atom14_order_dict[res_name]
-                         [atom_name]] = np.array(crd)
             atom_names.append(atom_group)
             crds.append(crd_group)
             atom_group = []
             crd_group = []
             res_ids.append(res_id)
             res_names.append(res_name)
             atom_group.append(atom_name)
             crd_group.append(crd)
             res_pointer.append(pointer)
         else:
             atom_group.append(atom_name)
             crd_group.append(crd)
-            if not atom_name.startswith('H') and atom_name != 'OXT':
-                atom_pos[atom14_order_dict[res_name]
-                         [atom_name]] = np.array(crd)
         if index == len(lines) - 1:
             atom_names.append(atom_group)
             crds.append(crd_group)
             atom14_positions.append(atom_pos)
     atom_names = atom_names
     res_names = res_names
     res_ids = np.array(res_ids, np.int32)
@@ -117,15 +108,22 @@
     init_res_names = np.array(init_res_names)
     init_res_ids = np.array(init_res_ids, np.int32)
     res_pointer = np.array(res_pointer, np.int32)
     # Violation loss parameters
     residue_index = np.arange(res_pointer.shape[0])
     aatype = np.zeros_like(residue_index)
     for i in range(res_pointer.shape[0]):
-        aatype[i] = resdict[res_names[i]]
+        if res_names[i] == 'HIP':
+            aatype[i] = resdict['HIS']
+        elif res_names[i] == 'GLH':
+            aatype[i] = resdict['GLY']
+        elif res_names[i] == 'ASH':
+            aatype[i] = resdict['ASP']
+        else:
+            aatype[i] = resdict[res_names[i]]
     atom14_atom_exists = np.array(atom14_atom_exists, np.float32)
 
     atom14_positions = np.array(atom14_positions, np.float32)
 
     return atom_names, res_names, res_ids, crds, res_pointer, flatten_atoms, flatten_crds, init_res_names, init_res_ids,\
         residue_index, aatype, atom14_positions, atom14_atom_exists, residx_atom14_to_atom37
 
@@ -150,15 +148,15 @@
                 pdb.write('  ')
                 pdb.write(atom_names[i].ljust(3))
             else:
                 pdb.write(' ')
                 pdb.write(atom_names[i].ljust(4))
             pdb.write(res_names[i].rjust(4))
             pdb.write('A'.rjust(2))
-            pdb.write('{}'.format(res_ids[i]).rjust(4))
+            pdb.write('{}'.format(res_ids[i] % 10000).rjust(4))
             pdb.write('    ')
             pdb.write('{:.3f}'.format(c[0]).rjust(8))
             pdb.write('{:.3f}'.format(c[1]).rjust(8))
             pdb.write('{:.3f}'.format(c[2]).rjust(8))
             pdb.write('1.0'.rjust(6))
             pdb.write('0.0'.rjust(6))
             pdb.write('{}'.format(atom_names[i][0]).rjust(12))
```

### Comparing `hadder-1.7/hadder.egg-info/PKG-INFO` & `hadder-1.8/hadder.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hadder
-Version: 1.7
+Version: 1.8
 Summary: Hydrogen adder for pdb protein files
 Home-page: https://gitee.com/dechin/hadder
 Author: Dechin CHEN
 Author-email: dechin.phy@gmail.com
 License: Apache 2.0 Licence
 Platform: any
 Description-Content-Type: text/markdown
@@ -72,8 +72,7 @@
 如果返回的结果为空，即表明当前路径下的所有python文件符合相关的规范要求，可以提交PR进入审核阶段。
 
 # 博客推荐
 1. [从Hadder看蛋白质分子中的加氢算法](https://www.cnblogs.com/dechinphy/p/hadder.html)
 2. [用脚本的形式运行Hadder](https://www.cnblogs.com/dechinphy/p/pym.html)
 3. [蛋白质基础组成结构](https://www.cnblogs.com/dechinphy/p/pdb.html)
 4. [氨基酸分子结构和原子命名](https://www.cnblogs.com/dechinphy/p/cnaminos.html)
-
```

### Comparing `hadder-1.7/setup.py` & `hadder-1.8/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,15 +22,15 @@
 from pathlib import Path
 
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 
 setup(
     name="hadder",
-    version="1.7",
+    version="1.8",
     description="Hydrogen adder for pdb protein files",
     long_description=long_description,
     long_description_content_type='text/markdown',
     license="Apache 2.0 Licence",
 
     url="https://gitee.com/dechin/hadder",
     author="Dechin CHEN",
```


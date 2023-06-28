# Comparing `tmp/spci-1.1.1.tar.gz` & `tmp/spci-1.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/spci-1.1.1.tar", last modified: Tue Mar 23 10:33:50 2021, max compression
+gzip compressed data, was "dist/spci-1.1.2.tar", last modified: Wed Jun 28 08:52:58 2023, max compression
```

## Comparing `spci-1.1.1.tar` & `spci-1.1.2.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2021-03-23 10:33:50.000000 spci-1.1.1/
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     3777 2021-03-23 10:33:50.000000 spci-1.1.1/PKG-INFO
-drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     3777 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/PKG-INFO
--rw-rw-r--   0 pavel     (1000) pavel     (1000)      668 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/SOURCES.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)      645 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/entry_points.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)        5 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/top_level.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       37 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/requires.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)        1 2021-03-23 10:33:50.000000 spci-1.1.1/spci.egg-info/dependency_links.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       79 2021-03-23 10:33:50.000000 spci-1.1.1/setup.cfg
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     2609 2021-03-23 10:19:17.000000 spci-1.1.1/README.md
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       78 2021-02-08 09:54:17.000000 spci-1.1.1/MANIFEST.in
-drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2021-03-23 10:33:50.000000 spci-1.1.1/spci/
--rwxrwxr-x   0 pavel     (1000) pavel     (1000)    60875 2021-03-23 10:09:55.000000 spci-1.1.1/spci/spci.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)    16881 2021-03-23 10:09:55.000000 spci-1.1.1/spci/plot_contributions.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)    10396 2021-03-23 10:09:55.000000 spci-1.1.1/spci/predict.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     5795 2021-03-23 10:09:55.000000 spci-1.1.1/spci/calc_atomic_properties_chemaxon.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     3882 2021-03-23 10:09:55.000000 spci-1.1.1/spci/find_murcko_rdkit.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     3472 2021-03-23 10:09:55.000000 spci-1.1.1/spci/plot_property_distribution.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)    10842 2021-02-08 09:54:17.000000 spci-1.1.1/spci/mol_context.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       97 2021-02-08 09:54:17.000000 spci-1.1.1/spci/setup.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     5524 2021-03-23 10:09:55.000000 spci-1.1.1/spci/sirms_file_class.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     1779 2021-03-23 10:09:55.000000 spci-1.1.1/spci/sdf_field2title.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     5603 2021-03-23 10:09:55.000000 spci-1.1.1/spci/filter_descriptors.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)    19659 2021-03-23 10:09:55.000000 spci-1.1.1/spci/model.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     2153 2021-02-08 09:54:17.000000 spci-1.1.1/spci/std_rules.xml
--rwxrwxr-x   0 pavel     (1000) pavel     (1000)     6764 2021-03-23 10:09:55.000000 spci-1.1.1/spci/find_frags_auto_rdkit.py
--rwxrwxr-x   0 pavel     (1000) pavel     (1000)    14556 2021-03-23 10:09:55.000000 spci-1.1.1/spci/calc_frag_contrib.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       21 2021-03-23 10:06:24.000000 spci-1.1.1/spci/__init__.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     8366 2021-03-23 10:09:55.000000 spci-1.1.1/spci/find_frags_rdkit.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     4701 2021-02-08 09:54:17.000000 spci-1.1.1/spci/default.smarts
--rwxrwxr-x   0 pavel     (1000) pavel     (1000)     8094 2021-03-04 15:36:20.000000 spci-1.1.1/spci/descriptors.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     4233 2021-03-23 10:09:55.000000 spci-1.1.1/spci/extractsdf.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     2007 2021-03-23 10:06:24.000000 spci-1.1.1/setup.py
+drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-28 08:52:58.000000 spci-1.1.2/
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     4125 2023-06-28 08:52:58.000000 spci-1.1.2/PKG-INFO
+drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     4125 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/PKG-INFO
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)      668 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/SOURCES.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)      645 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/entry_points.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)        5 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/top_level.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       37 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/requires.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)        1 2023-06-28 08:52:58.000000 spci-1.1.2/spci.egg-info/dependency_links.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       79 2023-06-28 08:52:58.000000 spci-1.1.2/setup.cfg
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     2877 2023-06-28 08:49:35.000000 spci-1.1.2/README.md
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       78 2021-02-08 09:54:17.000000 spci-1.1.2/MANIFEST.in
+drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-28 08:52:58.000000 spci-1.1.2/spci/
+-rwxrwxr-x   0 pavel     (1000) pavel     (1000)    60875 2021-03-23 10:09:55.000000 spci-1.1.2/spci/spci.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)    16881 2021-03-23 10:09:55.000000 spci-1.1.2/spci/plot_contributions.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)    10396 2021-03-23 10:09:55.000000 spci-1.1.2/spci/predict.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     5795 2021-03-23 10:09:55.000000 spci-1.1.2/spci/calc_atomic_properties_chemaxon.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     3882 2021-03-23 10:09:55.000000 spci-1.1.2/spci/find_murcko_rdkit.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     3472 2021-03-23 10:09:55.000000 spci-1.1.2/spci/plot_property_distribution.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)    10842 2021-02-08 09:54:17.000000 spci-1.1.2/spci/mol_context.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       97 2021-02-08 09:54:17.000000 spci-1.1.2/spci/setup.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     5524 2021-03-23 10:09:55.000000 spci-1.1.2/spci/sirms_file_class.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     1779 2021-03-23 10:09:55.000000 spci-1.1.2/spci/sdf_field2title.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     5603 2021-03-23 10:09:55.000000 spci-1.1.2/spci/filter_descriptors.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)    19659 2021-03-23 10:09:55.000000 spci-1.1.2/spci/model.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     2153 2021-02-08 09:54:17.000000 spci-1.1.2/spci/std_rules.xml
+-rwxrwxr-x   0 pavel     (1000) pavel     (1000)     7344 2023-06-28 08:47:55.000000 spci-1.1.2/spci/find_frags_auto_rdkit.py
+-rwxrwxr-x   0 pavel     (1000) pavel     (1000)    14556 2021-03-23 10:09:55.000000 spci-1.1.2/spci/calc_frag_contrib.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       22 2023-06-28 08:49:56.000000 spci-1.1.2/spci/__init__.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     8366 2021-03-23 10:09:55.000000 spci-1.1.2/spci/find_frags_rdkit.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     4701 2021-02-08 09:54:17.000000 spci-1.1.2/spci/default.smarts
+-rwxrwxr-x   0 pavel     (1000) pavel     (1000)     8094 2021-03-04 15:36:20.000000 spci-1.1.2/spci/descriptors.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     4233 2021-03-23 10:09:55.000000 spci-1.1.2/spci/extractsdf.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     2007 2021-03-23 10:06:24.000000 spci-1.1.2/setup.py
```

### Comparing `spci-1.1.1/PKG-INFO` & `spci-1.1.2/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,24 +1,28 @@
 Metadata-Version: 2.1
 Name: spci
-Version: 1.1.1
+Version: 1.1.2
 Summary: SPCI: structural and physicochemical interpretation of QSAR models
 Home-page: https://github.com/DrrDom/spci
 Author: Pavel Polishchuk
 Author-email: pavel_polishchuk@ukr.net
 License: UNKNOWN
 Description: # SPCI
         
         Automatic tool for mining structure-property relationships from chemical data sets
         
         #### Description
         
         Retrieves structure-property relationship from data sets in a chemically meaningful way.  
         Returns estimated contributions of fragments to the investigated property of compounds from a data set and can estimate contribution of different physicochemical factors as well.
         
+        #### Installation
+        
+        `pip install spci`
+        
         #### Features
         
         1. Easy to use straightforward workflow with GUI.
         2. Automatic model building and cross-validation.
         3. Build models for imbalanced data set using the multiple oversampling approach.
         4. Prediction with built models.
         5. Several fragmentation schemes to compute fragment contributions of:
@@ -30,14 +34,15 @@
         
         #### Visualization and analysis of results
         
         1. Built-in visualization.
         2. rspci - R package for custom visualization and analysis (https://github.com/DrrDom/rspci)
         3. Online tool for visualization, plot customization and figure downloading (http://158.194.101.252:3838/spci-vis/). Demo version is here (http://158.194.101.252:3838/spci-vis-demo/)
         4. Per atom contributions can be visualized with RDKit similarity maps.
+        
         #### Manual
         
         The short manual is included.
         
         #### Citation
         
         1.	Polishchuk, P. G.; Kuz'min, V. E.; Artemenko, A. G.; Muratov, E. N., Universal Approach for Structural Interpretation of Qsar/Qspr Models. Mol. Inf. 2013, 32, 843-853 - http://dx.doi.org/10.1002/minf.201300029 - structural interpretation.
@@ -66,14 +71,19 @@
         - reorganized as a Python package
         - console scripts have prefix spci_*
         
         1.1.1 (23.03.2021)
         - changed license to LGPLv3
         - fixed arguments in scpi_descriptors
         
+        1.1.2 (28.06.2023)
+        - add max_size argument to find_frag_auto_rdkit.py to limit maximum size of output fragments
+        - skip fragments with H as a context from output of find_frag_auto_rdkit.py
+        - update README and installation notes
+        
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Lesser General Public License v3 (LGPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Topic :: Scientific/Engineering :: Bio-Informatics
 Classifier: Topic :: Scientific/Engineering :: Chemistry
 Requires-Python: >=3.6
```

### Comparing `spci-1.1.1/spci.egg-info/PKG-INFO` & `spci-1.1.2/spci.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,24 +1,28 @@
 Metadata-Version: 2.1
 Name: spci
-Version: 1.1.1
+Version: 1.1.2
 Summary: SPCI: structural and physicochemical interpretation of QSAR models
 Home-page: https://github.com/DrrDom/spci
 Author: Pavel Polishchuk
 Author-email: pavel_polishchuk@ukr.net
 License: UNKNOWN
 Description: # SPCI
         
         Automatic tool for mining structure-property relationships from chemical data sets
         
         #### Description
         
         Retrieves structure-property relationship from data sets in a chemically meaningful way.  
         Returns estimated contributions of fragments to the investigated property of compounds from a data set and can estimate contribution of different physicochemical factors as well.
         
+        #### Installation
+        
+        `pip install spci`
+        
         #### Features
         
         1. Easy to use straightforward workflow with GUI.
         2. Automatic model building and cross-validation.
         3. Build models for imbalanced data set using the multiple oversampling approach.
         4. Prediction with built models.
         5. Several fragmentation schemes to compute fragment contributions of:
@@ -30,14 +34,15 @@
         
         #### Visualization and analysis of results
         
         1. Built-in visualization.
         2. rspci - R package for custom visualization and analysis (https://github.com/DrrDom/rspci)
         3. Online tool for visualization, plot customization and figure downloading (http://158.194.101.252:3838/spci-vis/). Demo version is here (http://158.194.101.252:3838/spci-vis-demo/)
         4. Per atom contributions can be visualized with RDKit similarity maps.
+        
         #### Manual
         
         The short manual is included.
         
         #### Citation
         
         1.	Polishchuk, P. G.; Kuz'min, V. E.; Artemenko, A. G.; Muratov, E. N., Universal Approach for Structural Interpretation of Qsar/Qspr Models. Mol. Inf. 2013, 32, 843-853 - http://dx.doi.org/10.1002/minf.201300029 - structural interpretation.
@@ -66,14 +71,19 @@
         - reorganized as a Python package
         - console scripts have prefix spci_*
         
         1.1.1 (23.03.2021)
         - changed license to LGPLv3
         - fixed arguments in scpi_descriptors
         
+        1.1.2 (28.06.2023)
+        - add max_size argument to find_frag_auto_rdkit.py to limit maximum size of output fragments
+        - skip fragments with H as a context from output of find_frag_auto_rdkit.py
+        - update README and installation notes
+        
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Lesser General Public License v3 (LGPLv3)
 Classifier: Operating System :: OS Independent
 Classifier: Topic :: Scientific/Engineering :: Bio-Informatics
 Classifier: Topic :: Scientific/Engineering :: Chemistry
 Requires-Python: >=3.6
```

### Comparing `spci-1.1.1/spci.egg-info/SOURCES.txt` & `spci-1.1.2/spci.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci.egg-info/entry_points.txt` & `spci-1.1.2/spci.egg-info/entry_points.txt`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/README.md` & `spci-1.1.2/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -3,14 +3,18 @@
 Automatic tool for mining structure-property relationships from chemical data sets
 
 #### Description
 
 Retrieves structure-property relationship from data sets in a chemically meaningful way.  
 Returns estimated contributions of fragments to the investigated property of compounds from a data set and can estimate contribution of different physicochemical factors as well.
 
+#### Installation
+
+`pip install spci`
+
 #### Features
 
 1. Easy to use straightforward workflow with GUI.
 2. Automatic model building and cross-validation.
 3. Build models for imbalanced data set using the multiple oversampling approach.
 4. Prediction with built models.
 5. Several fragmentation schemes to compute fragment contributions of:
@@ -22,14 +26,15 @@
 
 #### Visualization and analysis of results
 
 1. Built-in visualization.
 2. rspci - R package for custom visualization and analysis (https://github.com/DrrDom/rspci)
 3. Online tool for visualization, plot customization and figure downloading (http://158.194.101.252:3838/spci-vis/). Demo version is here (http://158.194.101.252:3838/spci-vis-demo/)
 4. Per atom contributions can be visualized with RDKit similarity maps.
+
 #### Manual
 
 The short manual is included.
 
 #### Citation
 
 1.	Polishchuk, P. G.; Kuz'min, V. E.; Artemenko, A. G.; Muratov, E. N., Universal Approach for Structural Interpretation of Qsar/Qspr Models. Mol. Inf. 2013, 32, 843-853 - http://dx.doi.org/10.1002/minf.201300029 - structural interpretation.
@@ -57,7 +62,12 @@
 - added per atom fragmentation
 - reorganized as a Python package
 - console scripts have prefix spci_*
 
 1.1.1 (23.03.2021)
 - changed license to LGPLv3
 - fixed arguments in scpi_descriptors
+
+1.1.2 (28.06.2023)
+- add max_size argument to find_frag_auto_rdkit.py to limit maximum size of output fragments
+- skip fragments with H as a context from output of find_frag_auto_rdkit.py
+- update README and installation notes
```

### Comparing `spci-1.1.1/spci/spci.py` & `spci-1.1.2/spci/spci.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/plot_contributions.py` & `spci-1.1.2/spci/plot_contributions.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/predict.py` & `spci-1.1.2/spci/predict.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/calc_atomic_properties_chemaxon.py` & `spci-1.1.2/spci/calc_atomic_properties_chemaxon.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/find_murcko_rdkit.py` & `spci-1.1.2/spci/find_murcko_rdkit.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/plot_property_distribution.py` & `spci-1.1.2/spci/plot_property_distribution.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/mol_context.py` & `spci-1.1.2/spci/mol_context.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/sirms_file_class.py` & `spci-1.1.2/spci/sirms_file_class.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/sdf_field2title.py` & `spci-1.1.2/spci/sdf_field2title.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/filter_descriptors.py` & `spci-1.1.2/spci/filter_descriptors.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/model.py` & `spci-1.1.2/spci/model.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/std_rules.xml` & `spci-1.1.2/spci/std_rules.xml`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/find_frags_auto_rdkit.py` & `spci-1.1.2/spci/find_frags_auto_rdkit.py`

 * *Files 24% similar despite different names*

```diff
@@ -23,15 +23,15 @@
 
 def replace_no2(mol):
     query = Chem.MolFromSmarts('n(:o):o')
     repl = Chem.MolFromSmiles('[N+](=O)[O-]')
     return AllChem.ReplaceSubstructs(mol, query, repl, replaceAll=True)[0]
 
 
-def fragment_mol(mol, query, max_cuts, keep_stereo, radius):
+def fragment_mol(mol, query, max_cuts, keep_stereo, radius, max_size):
     # returns list of lists: [['F', [0]], ['C#N', [3, 4]], ... ]
 
     def get_atom_prop(molecule, prop="Index", only_heavy=True):
         res = []
         for a in molecule.GetAtoms():
             if only_heavy and a.GetAtomicNum() > 1:
                 try:
@@ -67,38 +67,41 @@
 
     for core, chains in frags:
         if core is None:  # single cut
             components = list(Chem.GetMolFrags(chains, asMols=True))
             ids_0 = get_atom_prop(components[0])
             ids_1 = get_atom_prop(components[1])
             if Chem.MolToSmiles(components[0]) != '[H][*:1]':  # context cannot be H
-                frag_name = get_frag_name(components[0], components[1], radius, keep_stereo)
-                if frag_name:
-                    output.append((frag_name, ids_1))
+                if max_size is None or components[1].GetNumHeavyAtoms() <= max_size:
+                    frag_name = get_frag_name(components[0], components[1], radius, keep_stereo)
+                    if frag_name:
+                        output.append((frag_name, ids_1))
             if Chem.MolToSmiles(components[1]) != '[H][*:1]':  # context cannot be H
-                frag_name = get_frag_name(components[1], components[0], radius, keep_stereo)
-                if frag_name:
-                    output.append((frag_name, ids_0))
+                if max_size is None or components[0].GetNumHeavyAtoms() <= max_size:
+                    frag_name = get_frag_name(components[1], components[0], radius, keep_stereo)
+                    if frag_name:
+                        output.append((frag_name, ids_0))
         else:   # multiple cuts
-            # there are no checks for H needed because H can be present only in single cuts
-            frag_name = get_frag_name(chains, core, radius, keep_stereo)
-            if frag_name:
-                output.append((frag_name, get_atom_prop(core)))
+            if Chem.MolToSmiles(chains).find('[H][*:1]') == -1:  # context cannot be H
+                if max_size is None or core.GetNumHeavyAtoms() <= max_size:
+                    frag_name = get_frag_name(chains, core, radius, keep_stereo)
+                    if frag_name:
+                        output.append((frag_name, get_atom_prop(core)))
 
     return output
 
 
-def main_params(in_sdf, out_txt, query, max_cuts, keep_stereo, radius, verbose, error_fname):
+def main_params(in_sdf, out_txt, query, max_cuts, keep_stereo, radius, verbose, error_fname, max_size=None):
 
     with open(out_txt, 'wt') as f:
         for i, mol in enumerate(Chem.SDMolSupplier(in_sdf, sanitize=False, removeHs=False)):
             if mol is not None:
                 if verbose:
                     print(mol.GetProp("_Name") + ' is processing')
-                res = fragment_mol(mol, query, max_cuts, keep_stereo, radius)
+                res = fragment_mol(mol, query, max_cuts, keep_stereo, radius, max_size)
                 for item in res:
                     ids = [i + 1 for i in item[1]]  # save as 1-based ids
                     f.write(mol.GetProp("_Name") + '\t' + item[0] + '\t' + '\t'.join(map(str, ids)) + '\n')
             else:
                 print('Molecule #%i was skipped due to error' % i)
                 with open(error_fname, 'at') as f_err:
                     f_err.write('%s\t%s\tMolecule #%i\n' % (datetime.now().strftime('%Y-%m-%d %H:%M:%S'),
@@ -119,14 +122,16 @@
     parser.add_argument('-u', '--upper_cuts_number', metavar='integer', default=3,
                         help='maximal number of bonds cleaved simultaneously. Default: 3')
     parser.add_argument('-r', '--radius', metavar='integer', default=[0], nargs='*',
                         help='radius of molecular context (in bonds) which will be taken into account. '
                              '0 means no context. Several values separated by space can be specified. '
                              'The output fragment names will consist of core_smi_1|env_smi_1||core_smi_2|env_smi_2.'
                              ' Default: [0].')
+    parser.add_argument('--max_size', metavar='integer', default=None, required=False, type=int,
+                        help='maximum number of heavy atoms in output fragments. Default: no restriction.')
     parser.add_argument('-s', '--keep_stereo', action='store_true', default=False,
                         help='set this flag to keep stereo in context and core parts.')
     parser.add_argument('-v', '--verbose', action='store_true', default=False,
                         help='show progress on the screen.')
     parser.add_argument('-e', '--error_file', metavar='log_file_name.txt', default="rdkit_errors.txt",
                         help='save a number of molecules which cause error. Default file name: rdkit_errors.txt.')
 
@@ -137,13 +142,14 @@
         if o == "out": out_txt = v
         if o == "query": query = v
         if o == "upper_cuts_number": max_cuts = int(v)
         if o == "verbose": verbose = v
         if o == "error_file": error_fname = v
         if o == "keep_stereo": keep_stereo = v
         if o == "radius": radius = tuple(sorted(map(int, v)))
+        if o == "max_size": max_size = v
 
-    main_params(in_sdf, out_txt, query, max_cuts, keep_stereo, radius, verbose, error_fname)
+    main_params(in_sdf, out_txt, query, max_cuts, keep_stereo, radius, verbose, error_fname, max_size)
 
 
 if __name__ == '__main__':
     main()
```

### Comparing `spci-1.1.1/spci/calc_frag_contrib.py` & `spci-1.1.2/spci/calc_frag_contrib.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/find_frags_rdkit.py` & `spci-1.1.2/spci/find_frags_rdkit.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/default.smarts` & `spci-1.1.2/spci/default.smarts`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/descriptors.py` & `spci-1.1.2/spci/descriptors.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/spci/extractsdf.py` & `spci-1.1.2/spci/extractsdf.py`

 * *Files identical despite different names*

### Comparing `spci-1.1.1/setup.py` & `spci-1.1.2/setup.py`

 * *Files identical despite different names*


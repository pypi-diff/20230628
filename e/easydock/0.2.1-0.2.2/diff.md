# Comparing `tmp/easydock-0.2.1.tar.gz` & `tmp/easydock-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/easydock-0.2.1.tar", last modified: Thu Jun 15 18:20:59 2023, max compression
+gzip compressed data, was "dist/easydock-0.2.2.tar", last modified: Wed Jun 28 10:20:05 2023, max compression
```

## Comparing `easydock-0.2.1.tar` & `easydock-0.2.2.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-15 18:20:59.000000 easydock-0.2.1/
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     1516 2019-11-25 13:17:56.000000 easydock-0.2.1/LICENSE.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     8857 2023-06-15 18:20:59.000000 easydock-0.2.1/PKG-INFO
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       79 2023-06-15 18:20:59.000000 easydock-0.2.1/setup.cfg
-drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock/
--rw-rw-r--   0 pavel     (1000) pavel     (1000)    21656 2023-06-15 18:00:36.000000 easydock-0.2.1/easydock/preparation_for_docking.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)    13642 2023-06-15 14:29:36.000000 easydock-0.2.1/easydock/run_dock.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     3382 2023-05-16 09:01:52.000000 easydock-0.2.1/easydock/vina_dock_cli.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     7491 2023-05-16 09:01:52.000000 easydock-0.2.1/easydock/read_input.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       22 2023-06-15 18:16:50.000000 easydock-0.2.1/easydock/__init__.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     5965 2023-05-30 12:11:29.000000 easydock-0.2.1/easydock/get_sdf_from_dock_db.py
--rwxrwxr-x   0 pavel     (1000) pavel     (1000)     5288 2023-05-16 09:01:52.000000 easydock-0.2.1/easydock/vina_dock.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     2713 2023-05-16 09:01:52.000000 easydock-0.2.1/easydock/gnina_dock.py
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     6802 2023-06-15 18:18:52.000000 easydock-0.2.1/README.md
-drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     8857 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/PKG-INFO
--rw-rw-r--   0 pavel     (1000) pavel     (1000)      439 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/SOURCES.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)      111 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/entry_points.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)        9 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/top_level.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)       24 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/requires.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)        1 2023-06-15 18:20:59.000000 easydock-0.2.1/easydock.egg-info/dependency_links.txt
--rw-rw-r--   0 pavel     (1000) pavel     (1000)     1155 2023-05-16 09:01:52.000000 easydock-0.2.1/setup.py
+drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-28 10:20:05.000000 easydock-0.2.2/
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     1516 2019-11-25 13:17:56.000000 easydock-0.2.2/LICENSE.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     9135 2023-06-28 10:20:05.000000 easydock-0.2.2/PKG-INFO
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       79 2023-06-28 10:20:05.000000 easydock-0.2.2/setup.cfg
+drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-28 10:20:05.000000 easydock-0.2.2/easydock/
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)    22000 2023-06-28 09:30:15.000000 easydock-0.2.2/easydock/preparation_for_docking.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)    13918 2023-06-28 10:08:30.000000 easydock-0.2.2/easydock/run_dock.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     3382 2023-05-16 09:01:52.000000 easydock-0.2.2/easydock/vina_dock_cli.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     7491 2023-05-16 09:01:52.000000 easydock-0.2.2/easydock/read_input.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       22 2023-06-28 10:18:21.000000 easydock-0.2.2/easydock/__init__.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     5965 2023-05-30 12:11:29.000000 easydock-0.2.2/easydock/get_sdf_from_dock_db.py
+-rwxrwxr-x   0 pavel     (1000) pavel     (1000)     5288 2023-05-16 09:01:52.000000 easydock-0.2.2/easydock/vina_dock.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     2713 2023-05-16 09:01:52.000000 easydock-0.2.2/easydock/gnina_dock.py
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     7048 2023-06-28 10:18:21.000000 easydock-0.2.2/README.md
+drwxrwxr-x   0 pavel     (1000) pavel     (1000)        0 2023-06-28 10:20:05.000000 easydock-0.2.2/easydock.egg-info/
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     9135 2023-06-28 10:20:04.000000 easydock-0.2.2/easydock.egg-info/PKG-INFO
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)      439 2023-06-28 10:20:05.000000 easydock-0.2.2/easydock.egg-info/SOURCES.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)      111 2023-06-28 10:20:04.000000 easydock-0.2.2/easydock.egg-info/entry_points.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)        9 2023-06-28 10:20:04.000000 easydock-0.2.2/easydock.egg-info/top_level.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)       24 2023-06-28 10:20:04.000000 easydock-0.2.2/easydock.egg-info/requires.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)        1 2023-06-28 10:20:04.000000 easydock-0.2.2/easydock.egg-info/dependency_links.txt
+-rw-rw-r--   0 pavel     (1000) pavel     (1000)     1155 2023-05-16 09:01:52.000000 easydock-0.2.2/setup.py
```

### Comparing `easydock-0.2.1/LICENSE.txt` & `easydock-0.2.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `easydock-0.2.1/PKG-INFO` & `easydock-0.2.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: easydock
-Version: 0.2.1
+Version: 0.2.2
 Summary: EasyDock Python module to facilitate molecular docking
 Home-page: https://github.com/ci-lab-cz/easydock
 Author: Pavel Polishchuk, Guzel Minibaeva, Aleksandra Ivanova
 Author-email: pavel_polishchuk@ukr.net
 License: UNKNOWN
 Description: # EasyDock - Python module to automate molecular docking
         
@@ -164,14 +164,18 @@
         
         ##### Customization
         
         To implement support of a custom docking program one should implement a function like `mol_dock` which will take as input an RDKit mol object (named molecule) and an yml-file with all docking parameters. The function should run a command line script/utility and return back a tuple of a molecule name and a dictionary of parameters and their values which should be stored in DB (parameter names should be exactly the same as corresponding field names in DB). For examples, please look at `mol_dock` functions in `vina_dock` or `gnina_dock`.
         
         ### Changelog
         
+        **0.2.2**
+        - fix bug with continuation of calculations after db was transferred to other machine
+        - restrict precedence of command line arguments over arguments restored from DB only to specific ones (output, hostfile, dask_report, ncpu, verbose)
+        
         **0.2.1**
         - fix treatment of molecule ids in get_sdf_from_dock_db
         - change installation instructions, vina must be installed from sources
         - add argument no_tautomerization to disable tautomerization during protonation
         - (critical) fix conversion of PDBQT to Mol which could not assign bond orders and returned molecules with only single bonds 
         
         **0.2.0**
```

### Comparing `easydock-0.2.1/easydock/preparation_for_docking.py` & `easydock-0.2.2/easydock/preparation_for_docking.py`

 * *Files 2% similar despite different names*

```diff
@@ -93,15 +93,20 @@
                           f"{'-M' if tautomerize else ''} -K '{tmp.name}' > '{output}'"
                 subprocess.call(cmd_run, shell=True)
                 sdf_protonated = Chem.SDMolSupplier(output)
                 for mol in sdf_protonated:
                     mol_name = mol.GetProp('_Name')
                     smi = mol.GetPropsAsDict().get('MAJORMS', None)
                     if smi is not None:
-                        cansmi = Chem.CanonSmiles(smi)
+                        try:
+                            cansmi = Chem.CanonSmiles(smi)
+                        except:
+                            sys.stderr.write(f'EASYDOCK ERROR: {mol_name}, smiles {smi} obtained after protonation '
+                                             f'could not be read by RDKit. The molecule was skipped.\n')
+                            continue
                         if mol_name in smi_ids:
                             output_data_smi.append((cansmi, mol_name))
                         elif mol_name in mol_ids:
                             try:
                                 # mol block in chemaxon sdf is an input molecule
                                 # so, we make all bonds single, remove Hs and assign bond orders from SMILES
                                 # this should work even if a generated tautomer differs from the input molecule
@@ -402,15 +407,16 @@
             else:
                 raise KeyError(f'During loading no relevant argument name was found to match the loading field name: {colname}')
             open(tmppath[1], 'wt').write(value)
 
         tmppath = tempfile.mkstemp(suffix='.yml', text=True)
         d['config'] = tmppath[1]
         tmpfiles.append(tmppath[1])
-        open(tmppath[1], 'wt').write(values['config'])
+        with open(tmppath[1], 'wt') as f:
+            yaml.safe_dump(c, f)
 
     except Exception as e:
         for fname in tmpfiles:
             os.unlink(fname)
         raise e
 
     return d, tmpfiles
```

### Comparing `easydock-0.2.1/easydock/run_dock.py` & `easydock-0.2.2/easydock/run_dock.py`

 * *Files 2% similar despite different names*

```diff
@@ -84,17 +84,18 @@
                                                  '  run_dock.py -i input.smi -o output.db --program vina --config config.yml -c 4 -v\n\n'
                                                  'To run on several machines using dask ssh-cluster (on PBS system):\n'
                                                  '  dask ssh --hostfile $PBS_NODEFILE --nprocs 8 --nthreads 5 &\n'
                                                  '  sleep 10\n'
                                                  '  run_dock.py -i input.smi -o output.db --program vina --config config.yml -hostfile $PBS_NODEFILE\n\n'
                                                  '  $PBS_NODEFILE contains the list of addresses of computational nodes\n'
                                                  'To continue interrupted calculations it is enough to run the script '
-                                                 'with just output argument, all other arguments and data is stored '
-                                                 'in DB. If you supply other arguments ina command line they will have '
-                                                 'higher precedence over those ones stored in DB.',
+                                                 'with just the output argument, all other arguments and data is '
+                                                 'stored in DB. If you supply other arguments in a command line they '
+                                                 'will be ignored with the exception of hostfile, dask_report, ncpu '
+                                                 'and verbose.',
                                      formatter_class=RawTextArgumentDefaultsHelpFormatter)
     parser.add_argument('-i', '--input', metavar='FILENAME', required=False, type=filepath_type,
                         help='input file with molecules (SMI, SDF, SDF.GZ, PKL). Maybe be omitted if output DB was '
                              'previosuly created. In this case calculations will be continued from the interrupted '
                              'point.')
     parser.add_argument('-o', '--output', metavar='FILENAME', required=True, type=filepath_type,
                         help='output SQLite DB with scores and poses in PDBQT and MOL formats. It also stores '
@@ -136,14 +137,17 @@
     parser.add_argument('-v', '--verbose', action='store_true', default=False,
                         help='print progress to STDERR.')
     # parser.add_argument('--table_name', metavar='STRING', required=False, default='mols',
     #                     help='name of the main table in a database.')
 
     args = parser.parse_args()
     supplied_args = get_supplied_args(parser)
+    # allow update of only given arguments
+    allowed_args = ['output', 'hostfile', 'dask_report', 'ncpu', 'verbose']
+    supplied_args = tuple(arg for arg in supplied_args if arg in allowed_args)
 
     # if args.tmpdir is not None:
     #     tempfile.tempdir = args.tmpdir
 
     tmpfiles = []  # store text files which were saved to the setup table
 
     try:
```

### Comparing `easydock-0.2.1/easydock/vina_dock_cli.py` & `easydock-0.2.2/easydock/vina_dock_cli.py`

 * *Files identical despite different names*

### Comparing `easydock-0.2.1/easydock/read_input.py` & `easydock-0.2.2/easydock/read_input.py`

 * *Files identical despite different names*

### Comparing `easydock-0.2.1/easydock/get_sdf_from_dock_db.py` & `easydock-0.2.2/easydock/get_sdf_from_dock_db.py`

 * *Files identical despite different names*

### Comparing `easydock-0.2.1/easydock/vina_dock.py` & `easydock-0.2.2/easydock/vina_dock.py`

 * *Files identical despite different names*

### Comparing `easydock-0.2.1/easydock/gnina_dock.py` & `easydock-0.2.2/easydock/gnina_dock.py`

 * *Files identical despite different names*

### Comparing `easydock-0.2.1/README.md` & `easydock-0.2.2/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -156,14 +156,18 @@
 
 ##### Customization
 
 To implement support of a custom docking program one should implement a function like `mol_dock` which will take as input an RDKit mol object (named molecule) and an yml-file with all docking parameters. The function should run a command line script/utility and return back a tuple of a molecule name and a dictionary of parameters and their values which should be stored in DB (parameter names should be exactly the same as corresponding field names in DB). For examples, please look at `mol_dock` functions in `vina_dock` or `gnina_dock`.
 
 ### Changelog
 
+**0.2.2**
+- fix bug with continuation of calculations after db was transferred to other machine
+- restrict precedence of command line arguments over arguments restored from DB only to specific ones (output, hostfile, dask_report, ncpu, verbose)
+
 **0.2.1**
 - fix treatment of molecule ids in get_sdf_from_dock_db
 - change installation instructions, vina must be installed from sources
 - add argument no_tautomerization to disable tautomerization during protonation
 - (critical) fix conversion of PDBQT to Mol which could not assign bond orders and returned molecules with only single bonds 
 
 **0.2.0**
```

### Comparing `easydock-0.2.1/easydock.egg-info/PKG-INFO` & `easydock-0.2.2/easydock.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: easydock
-Version: 0.2.1
+Version: 0.2.2
 Summary: EasyDock Python module to facilitate molecular docking
 Home-page: https://github.com/ci-lab-cz/easydock
 Author: Pavel Polishchuk, Guzel Minibaeva, Aleksandra Ivanova
 Author-email: pavel_polishchuk@ukr.net
 License: UNKNOWN
 Description: # EasyDock - Python module to automate molecular docking
         
@@ -164,14 +164,18 @@
         
         ##### Customization
         
         To implement support of a custom docking program one should implement a function like `mol_dock` which will take as input an RDKit mol object (named molecule) and an yml-file with all docking parameters. The function should run a command line script/utility and return back a tuple of a molecule name and a dictionary of parameters and their values which should be stored in DB (parameter names should be exactly the same as corresponding field names in DB). For examples, please look at `mol_dock` functions in `vina_dock` or `gnina_dock`.
         
         ### Changelog
         
+        **0.2.2**
+        - fix bug with continuation of calculations after db was transferred to other machine
+        - restrict precedence of command line arguments over arguments restored from DB only to specific ones (output, hostfile, dask_report, ncpu, verbose)
+        
         **0.2.1**
         - fix treatment of molecule ids in get_sdf_from_dock_db
         - change installation instructions, vina must be installed from sources
         - add argument no_tautomerization to disable tautomerization during protonation
         - (critical) fix conversion of PDBQT to Mol which could not assign bond orders and returned molecules with only single bonds 
         
         **0.2.0**
```

### Comparing `easydock-0.2.1/setup.py` & `easydock-0.2.2/setup.py`

 * *Files identical despite different names*


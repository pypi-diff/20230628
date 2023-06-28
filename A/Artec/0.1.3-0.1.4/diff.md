# Comparing `tmp/Artec-0.1.3.tar.gz` & `tmp/Artec-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "Artec-0.1.3.tar", last modified: Sat Jun 17 17:51:41 2023, max compression
+gzip compressed data, was "Artec-0.1.4.tar", last modified: Wed Jun 28 14:50:56 2023, max compression
```

## Comparing `Artec-0.1.3.tar` & `Artec-0.1.4.tar`

### file list

```diff
@@ -1,20 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-17 17:51:41.594045 Artec-0.1.3/
-drwxrwxrwx   0        0        0        0 2023-06-17 17:51:41.561018 Artec-0.1.3/Artec.egg-info/
--rw-rw-rw-   0        0        0     2366 2023-06-17 17:51:41.000000 Artec-0.1.3/Artec.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      293 2023-06-17 17:51:41.000000 Artec-0.1.3/Artec.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-17 17:51:41.000000 Artec-0.1.3/Artec.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       46 2023-06-17 17:51:41.000000 Artec-0.1.3/Artec.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0        6 2023-06-17 17:51:41.000000 Artec-0.1.3/Artec.egg-info/top_level.txt
--rw-rw-rw-   0        0        0    35821 2023-06-09 04:27:29.000000 Artec-0.1.3/LICENSE
--rw-rw-rw-   0        0        0     2366 2023-06-17 17:51:41.594045 Artec-0.1.3/PKG-INFO
--rw-rw-rw-   0        0        0     1707 2023-06-17 17:51:12.000000 Artec-0.1.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-17 17:51:41.591024 Artec-0.1.3/artec/
--rw-rw-rw-   0        0        0      388 2023-06-17 17:51:12.000000 Artec-0.1.3/artec/__init__.py
--rw-rw-rw-   0        0        0      257 2023-06-17 12:39:07.000000 Artec-0.1.3/artec/__main__.py
--rw-rw-rw-   0        0        0     1748 2023-06-17 12:44:40.000000 Artec-0.1.3/artec/argparser.py
--rw-rw-rw-   0        0        0     2290 2023-06-17 13:43:01.000000 Artec-0.1.3/artec/boiler.py
--rw-rw-rw-   0        0        0        2 2023-06-17 13:44:50.000000 Artec-0.1.3/artec/exceptions.py
--rw-rw-rw-   0        0        0        0 2023-06-17 13:43:41.000000 Artec-0.1.3/artec/tui.py
--rw-rw-rw-   0        0        0      829 2023-06-17 17:51:12.000000 Artec-0.1.3/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-17 17:51:41.594045 Artec-0.1.3/setup.cfg
--rw-rw-rw-   0        0        0       41 2023-06-13 22:05:57.000000 Artec-0.1.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:50:56.694309 Artec-0.1.4/
+drwxrwxrwx   0        0        0        0 2023-06-28 14:50:56.677168 Artec-0.1.4/Artec.egg-info/
+-rw-rw-rw-   0        0        0     2518 2023-06-28 14:50:56.000000 Artec-0.1.4/Artec.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      315 2023-06-28 14:50:56.000000 Artec-0.1.4/Artec.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:50:56.000000 Artec-0.1.4/Artec.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       46 2023-06-28 14:50:56.000000 Artec-0.1.4/Artec.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 14:50:56.000000 Artec-0.1.4/Artec.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0    35821 2023-06-09 04:27:29.000000 Artec-0.1.4/LICENSE
+-rw-rw-rw-   0        0        0     2518 2023-06-28 14:50:56.693308 Artec-0.1.4/PKG-INFO
+-rw-rw-rw-   0        0        0     1859 2023-06-28 14:41:47.000000 Artec-0.1.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 14:50:56.688214 Artec-0.1.4/artec/
+-rw-rw-rw-   0        0        0      413 2023-06-28 14:43:45.000000 Artec-0.1.4/artec/__main__.py
+-rw-rw-rw-   0        0        0     1942 2023-06-28 14:43:45.000000 Artec-0.1.4/artec/argparser.py
+-rw-rw-rw-   0        0        0     2392 2023-06-28 14:41:47.000000 Artec-0.1.4/artec/boiler.py
+-rw-rw-rw-   0        0        0      686 2023-06-28 14:41:47.000000 Artec-0.1.4/artec/exceptions.py
+-rw-rw-rw-   0        0        0        0 2023-06-17 13:43:41.000000 Artec-0.1.4/artec/tui.py
+-rw-rw-rw-   0        0        0      829 2023-06-28 14:41:47.000000 Artec-0.1.4/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:50:56.694309 Artec-0.1.4/setup.cfg
+-rw-rw-rw-   0        0        0       41 2023-06-13 22:05:57.000000 Artec-0.1.4/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:50:56.692308 Artec-0.1.4/test/
+-rw-rw-rw-   0        0        0      572 2023-06-18 18:36:52.000000 Artec-0.1.4/test/test_boiler.py
+-rw-rw-rw-   0        0        0      767 2023-06-28 14:43:45.000000 Artec-0.1.4/test/test_parser.py
```

### Comparing `Artec-0.1.3/Artec.egg-info/PKG-INFO` & `Artec-0.1.4/Artec.egg-info/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: Artec
-Version: 0.1.3
+Version: 0.1.4
 Summary: Creates a configurable python project template in a given directory.
 Author-email: HushmKun <HushmKun@outlook.com>, Link- <bsm.dgdy@gmail.com>
 Project-URL: Homepage, https://github.com/HushmKun/Artec
 Project-URL: Bug Tracker, https://github.com/HushmKun/Artec/issues
 Classifier: Intended Audience :: Developers
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Environment :: Console
@@ -31,53 +31,54 @@
 ```bash
 $ cd Artec
 $ pip install . 
 ```
 ## Usage
 Create a JSON file to match the folder structure you desire
 ```
-    $: vim structure.json 
+$ vim structure.json 
     
-    # Paste the below into your file and modify as you desire
-	[{'folder': 'source'}, 
-     {'file': 'source/file1.txt'}, # Nested file
-     {'folder': 'sublime'}, 
-     {'file': 'sublime/file2.txt'}, 
-     {'folder': 'docs'}, 
-     {'file': 'docs/file3.txt'}, 
-     {'file': 'docs/file4.txt'},
-     {'file': 'README.md'}]
+# Paste the below into your file and modify as you desire
+[{'folder': 'source'}, 
+{'file': 'source/file1.txt'}, # Nested file
+{'folder': 'sublime'}, 
+{'file': 'sublime/file2.txt'}, 
+{'folder': 'docs'}, 
+{'file': 'docs/file3.txt'}, 
+{'file': 'docs/file4.txt'},
+{'file': 'README.md'}]
 ```
  How to execute
 ```
-	usage: artec [-h] -o PROJECT_PATH
+usage: artec [OPTIONS] -o [DEST] 
 
-	required arguments:
-  		-o PROJECT_PATH, --project-directory PROJECT_PATH 
-  				Project's absolute path where the structure will be created  		
-                        	
-    optional arguments:
-      	-h, --help 	
-      			Show this help message and exit
-      			
-        -s FOLDER_STRUCTURE, --folder-structure FOLDER_STRUCTURE
-                JSON file containing the template folder/file
-                structure to be created
-
-    Examples :
-            artec -o dest
-            artec -o dest -s res/simple.json
+Artec is a simple python 3 script to create a project template in a given directory.
+
+options:
+  -h, --help            show this help message and exit
+  -o TARGET, --output-directory TARGET
+                        Target output path where the structure will be created
+  -s SOURCE, --source-file SOURCE
+                        Source JSON file containing structure to be created
+  -i, --interactive     Runs Artec in interactive mode.
+  -v, --verbose         Runs Artec in verbose mode.
+  -V, --version         Display current version of Artec
+
+Examples:
+        artec -o dest
+        artec -o dest -s structure.json
 ```
 ## Version
 
-    0.1.3
+    0.1.4
 
 ## Contributing
 
-Big Thanks to [Link-](https://github.com/Link-) for jump starting the project.
+* Big Thanks to [Link-](https://github.com/Link-) for jump starting the project.
+* Thanks for [Narayandas Akhil Achary](https://github.com/0018akhil) for various fixes & features.
 
 Pull requests are welcome. For major changes, please open an issue first
 to discuss what you would like to change.
 
 Please make sure to update tests as appropriate.
 
 ## License
```

### Comparing `Artec-0.1.3/LICENSE` & `Artec-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `Artec-0.1.3/PKG-INFO` & `Artec-0.1.4/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: Artec
-Version: 0.1.3
+Version: 0.1.4
 Summary: Creates a configurable python project template in a given directory.
 Author-email: HushmKun <HushmKun@outlook.com>, Link- <bsm.dgdy@gmail.com>
 Project-URL: Homepage, https://github.com/HushmKun/Artec
 Project-URL: Bug Tracker, https://github.com/HushmKun/Artec/issues
 Classifier: Intended Audience :: Developers
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Environment :: Console
@@ -31,53 +31,54 @@
 ```bash
 $ cd Artec
 $ pip install . 
 ```
 ## Usage
 Create a JSON file to match the folder structure you desire
 ```
-    $: vim structure.json 
+$ vim structure.json 
     
-    # Paste the below into your file and modify as you desire
-	[{'folder': 'source'}, 
-     {'file': 'source/file1.txt'}, # Nested file
-     {'folder': 'sublime'}, 
-     {'file': 'sublime/file2.txt'}, 
-     {'folder': 'docs'}, 
-     {'file': 'docs/file3.txt'}, 
-     {'file': 'docs/file4.txt'},
-     {'file': 'README.md'}]
+# Paste the below into your file and modify as you desire
+[{'folder': 'source'}, 
+{'file': 'source/file1.txt'}, # Nested file
+{'folder': 'sublime'}, 
+{'file': 'sublime/file2.txt'}, 
+{'folder': 'docs'}, 
+{'file': 'docs/file3.txt'}, 
+{'file': 'docs/file4.txt'},
+{'file': 'README.md'}]
 ```
  How to execute
 ```
-	usage: artec [-h] -o PROJECT_PATH
+usage: artec [OPTIONS] -o [DEST] 
 
-	required arguments:
-  		-o PROJECT_PATH, --project-directory PROJECT_PATH 
-  				Project's absolute path where the structure will be created  		
-                        	
-    optional arguments:
-      	-h, --help 	
-      			Show this help message and exit
-      			
-        -s FOLDER_STRUCTURE, --folder-structure FOLDER_STRUCTURE
-                JSON file containing the template folder/file
-                structure to be created
-
-    Examples :
-            artec -o dest
-            artec -o dest -s res/simple.json
+Artec is a simple python 3 script to create a project template in a given directory.
+
+options:
+  -h, --help            show this help message and exit
+  -o TARGET, --output-directory TARGET
+                        Target output path where the structure will be created
+  -s SOURCE, --source-file SOURCE
+                        Source JSON file containing structure to be created
+  -i, --interactive     Runs Artec in interactive mode.
+  -v, --verbose         Runs Artec in verbose mode.
+  -V, --version         Display current version of Artec
+
+Examples:
+        artec -o dest
+        artec -o dest -s structure.json
 ```
 ## Version
 
-    0.1.3
+    0.1.4
 
 ## Contributing
 
-Big Thanks to [Link-](https://github.com/Link-) for jump starting the project.
+* Big Thanks to [Link-](https://github.com/Link-) for jump starting the project.
+* Thanks for [Narayandas Akhil Achary](https://github.com/0018akhil) for various fixes & features.
 
 Pull requests are welcome. For major changes, please open an issue first
 to discuss what you would like to change.
 
 Please make sure to update tests as appropriate.
 
 ## License
```

### Comparing `Artec-0.1.3/artec/argparser.py` & `Artec-0.1.4/artec/argparser.py`

 * *Files 15% similar despite different names*

```diff
@@ -29,14 +29,22 @@
             "--source-file",
             dest="source",
             help="Source JSON file containing structure to be created",
             type=str,
             required=False,
         )
 
+        self.add_argument(
+            "-t",
+            "--template",
+            dest="template",
+            help="Uses ready-made templates.",
+            required=False,
+        )
+
         # ! Not Implemented Yet.
         self.add_argument(
             "-i",
             "--interactive",
             dest="tui",
             help="Runs Artec in interactive mode.",
             action="store_true",
```

### Comparing `Artec-0.1.3/artec/boiler.py` & `Artec-0.1.4/artec/boiler.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,72 +1,71 @@
 """
 	Main module core.
 	#3 Step
 """
 import json
 import os
-
-
+from pathlib import Path
+from .exceptions import NotJsonFile, NotValidJson, NoSource
 class boiler_builder:
     #! TUI is not implemented yet.
-    def __init__(self, source=None, target=None, tui=False, verbose=False) -> None:
+    def __init__(self, source=None, target=None, verbose=False, template=None, tui=False) -> None:
         self.verbose = verbose
         self.target = target
-        self.structure = self._source(source)
+        self.template = template    
+        if self.template is None :
+            self.structure = self._source(source)
 
     def _source(self, source) -> list[dict[str, str]]:
         try:
-            if os.path.isfile(source):
+            if os.path.isfile(source) and source.endswith('.json'):
                 with open(source, "rt", encoding="utf-8") as file_data:
                     structure = json.load(file_data)
             else : 
-                raise Exception()
-            # TODO : What if it's a directory ?  
+                raise NotJsonFile(self.verbose)
     
-        except :
-            if (source is None) and (self.verbose) :
-                print("> No Source Provided.")
+        except Exception as e :
             
-            elif (self.verbose) and not os.path.isfile(source):
-                print("> Provided Source isn't a file.")
-                
-            print("> Reverting to default structure.")
+            if not hasattr(e,"errno") : 
+                NoSource()                
+
             structure = DEFAULT_FOLDER_STRUCTURE
         return structure
 
     def build(self):
         print("> Creating folder structure: {}\n".format(self.target))
 
         for entry in self.structure:
             for _type, name in entry.items():
                 try:
-                    joined = os.path.join(self.target, name)
+                    joined = Path(os.path.join(self.target, name))
                     if _type == "folder":
                         self._make_folder(joined)
                     elif _type == "file":
                         self._make_file(joined)
+                    else : 
+                        raise NotValidJson(self.verbose)
                     print("Created: %s" % joined)
-                except OSError:
+                except Exception:
                     exit("> Fatal error - exiting...")
-
+                
     def _make_file(self, path):
         """Create an empty file in a given directory"""
+        path.parent.mkdir(parents=True, exist_ok=True)
         open(path, "a").close()
 
     def _make_folder(self, path):
         """Create an empty directory"""
-        if not os.path.exists(path):
-            os.makedirs(path)
-
+        os.makedirs(path, exist_ok=True)
 
 DEFAULT_FOLDER_STRUCTURE = [
     {"folder": "src"},
-    {"folder": "src\\__init__.py"},
-    {"folder": "tests"},
-    {"folder": "tests\\__init__.py"},
+    {"file": "src/__init__.py"},
+    {"folder": "test"},
+    {"file": "test/__init__.py"},
     {"folder": "res"},
     {"file": "README.md"},
     {"file": "setup.py"},
     {"file": "setup.cfg"},
     {"file": "pyproject.toml"},
 ]
```

### Comparing `Artec-0.1.3/pyproject.toml` & `Artec-0.1.4/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 00000010: 7265 7175 6972 6573 203d 205b 2273 6574  requires = ["set
 00000020: 7570 746f 6f6c 733e 3d36 312e 3022 5d0d  uptools>=61.0"].
 00000030: 0a62 7569 6c64 2d62 6163 6b65 6e64 203d  .build-backend =
 00000040: 2022 7365 7475 7074 6f6f 6c73 2e62 7569   "setuptools.bui
 00000050: 6c64 5f6d 6574 6122 0d0a 0d0a 5b70 726f  ld_meta"....[pro
 00000060: 6a65 6374 5d0d 0a6e 616d 6520 3d20 2241  ject]..name = "A
 00000070: 7274 6563 220d 0a76 6572 7369 6f6e 203d  rtec"..version =
-00000080: 2022 302e 312e 3322 0d0a 6175 7468 6f72   "0.1.3"..author
+00000080: 2022 302e 312e 3422 0d0a 6175 7468 6f72   "0.1.4"..author
 00000090: 7320 3d20 5b0d 0a20 207b 206e 616d 653d  s = [..  { name=
 000000a0: 2248 7573 686d 4b75 6e22 2c20 656d 6169  "HushmKun", emai
 000000b0: 6c3d 2248 7573 686d 4b75 6e40 6f75 746c  l="HushmKun@outl
 000000c0: 6f6f 6b2e 636f 6d22 207d 2c0d 0a20 207b  ook.com" },..  {
 000000d0: 206e 616d 653d 224c 696e 6b2d 222c 2065   name="Link-", e
 000000e0: 6d61 696c 3d22 6273 6d2e 6467 6479 4067  mail="bsm.dgdy@g
 000000f0: 6d61 696c 2e63 6f6d 2220 7d2c 0d0a 5d0d  mail.com" },..].
@@ -44,9 +44,9 @@
 000002b0: 2f67 6974 6875 622e 636f 6d2f 4875 7368  /github.com/Hush
 000002c0: 6d4b 756e 2f41 7274 6563 220d 0a22 4275  mKun/Artec".."Bu
 000002d0: 6720 5472 6163 6b65 7222 203d 2022 6874  g Tracker" = "ht
 000002e0: 7470 733a 2f2f 6769 7468 7562 2e63 6f6d  tps://github.com
 000002f0: 2f48 7573 686d 4b75 6e2f 4172 7465 632f  /HushmKun/Artec/
 00000300: 6973 7375 6573 220d 0a0d 0a5b 7072 6f6a  issues"....[proj
 00000310: 6563 742e 7363 7269 7074 735d 0d0a 6172  ect.scripts]..ar
-00000320: 7465 6320 3d20 2261 7274 6563 2e5f 5f69  tec = "artec.__i
-00000330: 6e69 745f 5f3a 6d61 696e 220d 0a         nit__:main"..
+00000320: 7465 6320 3d20 2261 7274 6563 2e5f 5f6d  tec = "artec.__m
+00000330: 6169 6e5f 5f3a 6d61 696e 220d 0a         ain__:main"..
```


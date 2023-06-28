# Comparing `tmp/gulagcleaner-0.6.4.tar.gz` & `tmp/gulagcleaner-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gulagcleaner-0.6.4.tar", last modified: Wed Jun 14 23:14:24 2023, max compression
+gzip compressed data, was "gulagcleaner-0.7.0.tar", last modified: Wed Jun 28 00:54:13 2023, max compression
```

## Comparing `gulagcleaner-0.6.4.tar` & `gulagcleaner-0.7.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-14 23:14:24.753174 gulagcleaner-0.6.4/
--rw-rw-rw-   0        0        0    71644 2023-06-12 15:18:46.000000 gulagcleaner-0.6.4/LICENSE
--rw-rw-rw-   0        0        0     3072 2023-06-14 23:14:24.754172 gulagcleaner-0.6.4/PKG-INFO
--rw-rw-rw-   0        0        0     2528 2023-06-12 19:45:14.000000 gulagcleaner-0.6.4/README.md
-drwxrwxrwx   0        0        0        0 2023-06-14 23:14:24.727173 gulagcleaner-0.6.4/gulagcleaner/
--rw-rw-rw-   0        0        0        0 2023-06-12 15:18:46.000000 gulagcleaner-0.6.4/gulagcleaner/__init__.py
--rw-rw-rw-   0        0        0     3121 2023-06-14 23:12:12.000000 gulagcleaner-0.6.4/gulagcleaner/command_line.py
--rw-rw-rw-   0        0        0      228 2023-06-12 19:36:30.000000 gulagcleaner-0.6.4/gulagcleaner/decrypt.py
--rw-rw-rw-   0        0        0     4746 2023-06-14 23:06:43.000000 gulagcleaner-0.6.4/gulagcleaner/extract.py
--rw-rw-rw-   0        0        0      968 2023-06-12 19:36:30.000000 gulagcleaner-0.6.4/gulagcleaner/metadata.py
-drwxrwxrwx   0        0        0        0 2023-06-14 23:14:24.753174 gulagcleaner-0.6.4/gulagcleaner.egg-info/
--rw-rw-rw-   0        0        0     3072 2023-06-14 23:14:24.000000 gulagcleaner-0.6.4/gulagcleaner.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      387 2023-06-14 23:14:24.000000 gulagcleaner-0.6.4/gulagcleaner.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-14 23:14:24.000000 gulagcleaner-0.6.4/gulagcleaner.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       64 2023-06-14 23:14:24.000000 gulagcleaner-0.6.4/gulagcleaner.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       49 2023-06-14 23:14:24.000000 gulagcleaner-0.6.4/gulagcleaner.egg-info/requires.txt
--rw-rw-rw-   0        0        0       13 2023-06-14 23:14:24.000000 gulagcleaner-0.6.4/gulagcleaner.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       86 2023-06-12 15:18:46.000000 gulagcleaner-0.6.4/pyproject.toml
--rw-rw-rw-   0        0        0      834 2023-06-14 23:14:24.755174 gulagcleaner-0.6.4/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 00:54:13.544805 gulagcleaner-0.7.0/
+-rw-rw-rw-   0        0        0    71644 2023-06-12 15:18:46.000000 gulagcleaner-0.7.0/LICENSE
+-rw-rw-rw-   0        0        0     3072 2023-06-28 00:54:13.544805 gulagcleaner-0.7.0/PKG-INFO
+-rw-rw-rw-   0        0        0     2528 2023-06-12 19:45:14.000000 gulagcleaner-0.7.0/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 00:54:13.519804 gulagcleaner-0.7.0/gulagcleaner/
+-rw-rw-rw-   0        0        0        0 2023-06-12 15:18:46.000000 gulagcleaner-0.7.0/gulagcleaner/__init__.py
+-rw-rw-rw-   0        0        0     2707 2023-06-28 00:51:25.000000 gulagcleaner-0.7.0/gulagcleaner/command_line.py
+-rw-rw-rw-   0        0        0      228 2023-06-12 19:36:30.000000 gulagcleaner-0.7.0/gulagcleaner/decrypt.py
+-rw-rw-rw-   0        0        0     7880 2023-06-28 00:46:24.000000 gulagcleaner-0.7.0/gulagcleaner/extract.py
+-rw-rw-rw-   0        0        0      968 2023-06-12 19:36:30.000000 gulagcleaner-0.7.0/gulagcleaner/metadata.py
+drwxrwxrwx   0        0        0        0 2023-06-28 00:54:13.543806 gulagcleaner-0.7.0/gulagcleaner.egg-info/
+-rw-rw-rw-   0        0        0     3072 2023-06-28 00:54:13.000000 gulagcleaner-0.7.0/gulagcleaner.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      387 2023-06-28 00:54:13.000000 gulagcleaner-0.7.0/gulagcleaner.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 00:54:13.000000 gulagcleaner-0.7.0/gulagcleaner.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       64 2023-06-28 00:54:13.000000 gulagcleaner-0.7.0/gulagcleaner.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 00:54:13.000000 gulagcleaner-0.7.0/gulagcleaner.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       13 2023-06-28 00:54:13.000000 gulagcleaner-0.7.0/gulagcleaner.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       86 2023-06-12 15:18:46.000000 gulagcleaner-0.7.0/pyproject.toml
+-rw-rw-rw-   0        0        0      834 2023-06-28 00:54:13.545805 gulagcleaner-0.7.0/setup.cfg
```

### Comparing `gulagcleaner-0.6.4/LICENSE` & `gulagcleaner-0.7.0/LICENSE`

 * *Files identical despite different names*

### Comparing `gulagcleaner-0.6.4/PKG-INFO` & `gulagcleaner-0.7.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gulagcleaner
-Version: 0.6.4
+Version: 0.7.0
 Summary: Ad removal tool for PDFs written in python.
 Home-page: https://github.com/YM162/gulag-cleaner-cli
 Author: YM162
 Author-email: david.fontaneda16@gmail.com
 Project-URL: Bug Tracker, https://github.com/YM162/gulag-cleaner-cli/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `gulagcleaner-0.6.4/README.md` & `gulagcleaner-0.7.0/README.md`

 * *Files identical despite different names*

### Comparing `gulagcleaner-0.6.4/gulagcleaner/command_line.py` & `gulagcleaner-0.7.0/gulagcleaner/command_line.py`

 * *Files 12% similar despite different names*

```diff
@@ -8,67 +8,58 @@
     Main function for the "gulagcleaner" CLI command.
 
     The "gulagcleaner" command takes an argument for the path of a PDF file and tries to remove the ads inside it. The new PDF is saved in the same folder.
     
     Available CLI arguments:
     -h : Display help information.
     -r : Replace the original file with the cleaned file.
-    -o : Use the old cleaning method (for files older than 18/05/2023).
     -v : Display the version of the program.
 
     '''
     import sys
-    import os.path
 
     # Check for the -h argument
     if '-h' in sys.argv:
         print("Usage: gulagcleaner [-h] [-r] [-o] [-v] <pdf_path>")
         print("")
         print("Removes ads from a PDF file.")
         print("")
         print("Positional arguments:")
         print("  pdf_path      The PDF file to clean.")
         print("")
         print("Optional arguments:")
         print("  -h            Show this help message.")
         print("  -r            Replace the original file with the cleaned file.")
-        print("  -o            Use the old cleaning method (for files older than 18/05/2023).")
         print("  -v            Show the version of the program.")
         return
 
     # Check for the -v argument
     if '-v' in sys.argv:
-        print("Current version: 0.6.4")
+        print("Current version: 0.7.0")
         return
 
     # Get the pdf_path argument
     if len(sys.argv) < 2:
-        print('Usage: gulagcleaner [-h] [-r] [-o] [-v] <pdf_path>')
+        print('Usage: gulagcleaner [-h] [-r] [-v] <pdf_path>')
         return
     pdf_path = sys.argv[-1]
 
     # Check if the file exists
     if not exists(pdf_path):
         print("File not found.")
         return
-
+    
     # Check if the -r argument is present
     if '-r' in sys.argv:
         output_path = pdf_path
     else:
         output_path = pdf_path[:-4] + "_clean.pdf"
 
-     # Check if the -o argument is present
-    if '-o' in sys.argv:
-        method = "old"
-        pdf_path = decrypt_pdf(pdf_path)
-        intermediate = True
-    else:
-        method = "new"
-        intermediate = False
+    #We decrypt the PDF file
+    pdf_path = decrypt_pdf(pdf_path)
 
     #Extract metadata
     try:
         metadict = extract_metadata(pdf_path)
         print("Metadata:")
         print("Archivo: " + metadict["Archivo"])
         print("Autor: " + metadict["Autor"])
@@ -76,19 +67,16 @@
         print("Curso y Grado: " + metadict["Curso y Grado"])
         print("Facultad: " + metadict["Facultad"])
         print("Universidad: " + metadict["Universidad"])
     except Exception as e:
         print("Failed to extract metadata:", e)         
 
     # Call the cleaning function
-    return_msg = clean_pdf(pdf_path, output_path, method)
+    return_msg = clean_pdf(pdf_path, output_path)
 
     if return_msg["Success"]:
         print("Cleaning successful. File saved in", return_msg["return_path"])
     else:
         print("Error:", return_msg["Error"])
 
-    if intermediate:
-        os.remove(pdf_path)
-
 if __name__ == "__main__":
     print('Call from the "gulagcleaner" command.')
```

### Comparing `gulagcleaner-0.6.4/gulagcleaner/metadata.py` & `gulagcleaner-0.7.0/gulagcleaner/metadata.py`

 * *Files identical despite different names*

### Comparing `gulagcleaner-0.6.4/gulagcleaner.egg-info/PKG-INFO` & `gulagcleaner-0.7.0/gulagcleaner.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gulagcleaner
-Version: 0.6.4
+Version: 0.7.0
 Summary: Ad removal tool for PDFs written in python.
 Home-page: https://github.com/YM162/gulag-cleaner-cli
 Author: YM162
 Author-email: david.fontaneda16@gmail.com
 Project-URL: Bug Tracker, https://github.com/YM162/gulag-cleaner-cli/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `gulagcleaner-0.6.4/setup.cfg` & `gulagcleaner-0.7.0/setup.cfg`

 * *Files 13% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2067 756c 6167 636c 6561 6e65 720d   = gulagcleaner.
-00000020: 0a76 6572 7369 6f6e 203d 2030 2e36 2e34  .version = 0.6.4
+00000020: 0a76 6572 7369 6f6e 203d 2030 2e37 2e30  .version = 0.7.0
 00000030: 0d0a 6175 7468 6f72 203d 2059 4d31 3632  ..author = YM162
 00000040: 0d0a 6175 7468 6f72 5f65 6d61 696c 203d  ..author_email =
 00000050: 2064 6176 6964 2e66 6f6e 7461 6e65 6461   david.fontaneda
 00000060: 3136 4067 6d61 696c 2e63 6f6d 0d0a 6465  16@gmail.com..de
 00000070: 7363 7269 7074 696f 6e20 3d20 4164 2072  scription = Ad r
 00000080: 656d 6f76 616c 2074 6f6f 6c20 666f 7220  emoval tool for 
 00000090: 5044 4673 2077 7269 7474 656e 2069 6e20  PDFs written in
```


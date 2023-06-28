# Comparing `tmp/datasette-upload-csvs-0.8.2.tar.gz` & `tmp/datasette-upload-csvs-0.8.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "datasette-upload-csvs-0.8.2.tar", last modified: Thu Sep  8 20:16:53 2022, max compression
+gzip compressed data, was "datasette-upload-csvs-0.8.3.tar", last modified: Wed Jun 28 01:26:39 2023, max compression
```

## Comparing `datasette-upload-csvs-0.8.2.tar` & `datasette-upload-csvs-0.8.3.tar`

### file list

```diff
@@ -1,18 +1,20 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-08 20:16:53.536859 datasette-upload-csvs-0.8.2/
--rw-r--r--   0 runner    (1001) docker     (121)    11357 2022-09-08 20:16:31.000000 datasette-upload-csvs-0.8.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)     1837 2022-09-08 20:16:53.536859 datasette-upload-csvs-0.8.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     1224 2022-09-08 20:16:31.000000 datasette-upload-csvs-0.8.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-08 20:16:53.536859 datasette-upload-csvs-0.8.2/datasette_upload_csvs/
--rw-r--r--   0 runner    (1001) docker     (121)     6275 2022-09-08 20:16:31.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-08 20:16:53.536859 datasette-upload-csvs-0.8.2/datasette_upload_csvs/templates/
--rw-r--r--   0 runner    (1001) docker     (121)     5656 2022-09-08 20:16:31.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs/templates/upload_csv.html
--rw-r--r--   0 runner    (1001) docker     (121)      216 2022-09-08 20:16:31.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs/templates/upload_csv_done.html
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-08 20:16:53.536859 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     1837 2022-09-08 20:16:53.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      433 2022-09-08 20:16:53.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-09-08 20:16:53.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       48 2022-09-08 20:16:53.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (121)      157 2022-09-08 20:16:53.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)       22 2022-09-08 20:16:53.000000 datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)       38 2022-09-08 20:16:53.536859 datasette-upload-csvs-0.8.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     1420 2022-09-08 20:16:31.000000 datasette-upload-csvs-0.8.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2001 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1388 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/datasette_upload_csvs/
+-rw-r--r--   0 runner    (1001) docker     (123)     6275 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/datasette_upload_csvs/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)     5755 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs/templates/upload_csv.html
+-rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs/templates/upload_csv_done.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2001 2023-06-28 01:26:39.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      469 2023-06-28 01:26:39.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:26:39.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-28 01:26:39.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 01:26:39.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:26:39.000000 datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1420 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:39.527042 datasette-upload-csvs-0.8.3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     7226 2023-06-28 01:26:19.000000 datasette-upload-csvs-0.8.3/tests/test_datasette_upload_csvs.py
```

### Comparing `datasette-upload-csvs-0.8.2/LICENSE` & `datasette-upload-csvs-0.8.3/LICENSE`

 * *Files identical despite different names*

### Comparing `datasette-upload-csvs-0.8.2/PKG-INFO` & `datasette-upload-csvs-0.8.3/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: datasette-upload-csvs
-Version: 0.8.2
+Version: 0.8.3
 Summary: Datasette plugin for uploading CSV files and converting them to database tables
 Home-page: https://datasette.io/plugins/datasette-upload-csvs
 Author: Simon Willison
 License: Apache License, Version 2.0
 Project-URL: Issues, https://github.com/simonw/datasette-upload-csvs/issues
 Project-URL: CI, https://github.com/simonw/datasette-upload-csvs/actions
 Project-URL: Changelog, https://github.com/simonw/datasette-upload-csvs/releases
@@ -13,14 +13,15 @@
 Provides-Extra: test
 License-File: LICENSE
 
 # datasette-upload-csvs
 
 [![PyPI](https://img.shields.io/pypi/v/datasette-upload-csvs.svg)](https://pypi.org/project/datasette-upload-csvs/)
 [![Changelog](https://img.shields.io/github/v/release/simonw/datasette-upload-csvs?include_prereleases&label=changelog)](https://github.com/simonw/datasette-upload-csvs/releases)
+[![Tests](https://github.com/simonw/datasette-upload-csvs/workflows/Test/badge.svg)](https://github.com/simonw/datasette-upload-csvs/actions?query=workflow%3ATest)
 [![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/simonw/datasette-upload-csvs/blob/main/LICENSE)
 
 Datasette plugin for uploading CSV files and converting them to database tables
 
 ## Installation
 
     datasette install datasette-upload-csvs
```

### Comparing `datasette-upload-csvs-0.8.2/README.md` & `datasette-upload-csvs-0.8.3/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 # datasette-upload-csvs
 
 [![PyPI](https://img.shields.io/pypi/v/datasette-upload-csvs.svg)](https://pypi.org/project/datasette-upload-csvs/)
 [![Changelog](https://img.shields.io/github/v/release/simonw/datasette-upload-csvs?include_prereleases&label=changelog)](https://github.com/simonw/datasette-upload-csvs/releases)
+[![Tests](https://github.com/simonw/datasette-upload-csvs/workflows/Test/badge.svg)](https://github.com/simonw/datasette-upload-csvs/actions?query=workflow%3ATest)
 [![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/simonw/datasette-upload-csvs/blob/main/LICENSE)
 
 Datasette plugin for uploading CSV files and converting them to database tables
 
 ## Installation
 
     datasette install datasette-upload-csvs
```

### Comparing `datasette-upload-csvs-0.8.2/datasette_upload_csvs/__init__.py` & `datasette-upload-csvs-0.8.3/datasette_upload_csvs/__init__.py`

 * *Files identical despite different names*

### Comparing `datasette-upload-csvs-0.8.2/datasette_upload_csvs/templates/upload_csv.html` & `datasette-upload-csvs-0.8.3/datasette_upload_csvs/templates/upload_csv.html`

 * *Files 4% similar despite different names*

```diff
@@ -68,14 +68,18 @@
 var uploadForm = document.getElementById("uploadForm");
 var fileInput = document.getElementsByName("csv")[0];
 var dropArea = document.getElementById("file-drop");
 var progress = document.getElementsByTagName("progress")[0];
 var progressLabel = document.getElementById("progress-label");
 var label = dropArea.getElementsByTagName("label")[0];
 var tableName = document.getElementById("id_table_name");
+
+// State that holds the most-recent uploaded File, from a FileList
+let currentFile = null;
+
 progress.style.display = "none";
 fileInput.addEventListener("change", () => {
   setFile(fileInput.files[0]);
 });
 ["dragenter", "dragover", "dragleave", "drop"].forEach(eventName => {
   dropArea.addEventListener(
     eventName,
@@ -126,30 +130,33 @@
   }
   if (bytes < 1024 * 1024 * 1024 * 1024) {
     return (bytes / 1024 / 1024 / 1024).toFixed(1) + " GB";
   }
 }
 
 function setFile(file) {
-  if (fileInput.files[0] != file) {
-    fileInput.files[0] = file;
+  if (currentFile != file) {
+    currentFile = file;
   }
   label.innerText = file.name;
   label.innerHTML += '<br><span style="font-size: 0.9em">' + formattedBytes(file.size) + '</span>';
   if (!tableName.value.trim()) {
     tableName.value = file.name.replace(/\.csv$/i, "").trim();
   }
 }
 
 // Onsubmit handler
 uploadForm.addEventListener("submit", ev => {
   ev.preventDefault();
-  var file = fileInput.files[0];
-  if (!file || !tableName.value.trim()) {
-    alert("Please select a file and enter a table name");
+  if (!tableName.value.trim()) {
+    alert("Please enter a table name");
+    return;
+  }
+  if (!currentFile) {
+    alert("Please select a file");
     return;
   }
   var xhr = new XMLHttpRequest();
   var formData = new FormData();
   dropArea.style.display = "none";
   progressLabel.style.display = "block";
   xhr.open("POST", fileInput.form.action, true);
@@ -186,13 +193,13 @@
     } else if (xhr.readyState == 4 && xhr.status != 200) {
       alert("Error!");
     }
   });
 
   formData.append("xhr", "1");
   formData.append("csrftoken", "{{ csrftoken() }}");
-  formData.append("csv", file);
+  formData.append("csv", currentFile);
   formData.append("table", tableName.value);
   xhr.send(formData);
 });
 </script>
 {% endblock %}
```

### Comparing `datasette-upload-csvs-0.8.2/datasette_upload_csvs.egg-info/PKG-INFO` & `datasette-upload-csvs-0.8.3/datasette_upload_csvs.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: datasette-upload-csvs
-Version: 0.8.2
+Version: 0.8.3
 Summary: Datasette plugin for uploading CSV files and converting them to database tables
 Home-page: https://datasette.io/plugins/datasette-upload-csvs
 Author: Simon Willison
 License: Apache License, Version 2.0
 Project-URL: Issues, https://github.com/simonw/datasette-upload-csvs/issues
 Project-URL: CI, https://github.com/simonw/datasette-upload-csvs/actions
 Project-URL: Changelog, https://github.com/simonw/datasette-upload-csvs/releases
@@ -13,14 +13,15 @@
 Provides-Extra: test
 License-File: LICENSE
 
 # datasette-upload-csvs
 
 [![PyPI](https://img.shields.io/pypi/v/datasette-upload-csvs.svg)](https://pypi.org/project/datasette-upload-csvs/)
 [![Changelog](https://img.shields.io/github/v/release/simonw/datasette-upload-csvs?include_prereleases&label=changelog)](https://github.com/simonw/datasette-upload-csvs/releases)
+[![Tests](https://github.com/simonw/datasette-upload-csvs/workflows/Test/badge.svg)](https://github.com/simonw/datasette-upload-csvs/actions?query=workflow%3ATest)
 [![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/simonw/datasette-upload-csvs/blob/main/LICENSE)
 
 Datasette plugin for uploading CSV files and converting them to database tables
 
 ## Installation
 
     datasette install datasette-upload-csvs
```

### Comparing `datasette-upload-csvs-0.8.2/setup.py` & `datasette-upload-csvs-0.8.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 from setuptools import setup
 import os
 
-VERSION = "0.8.2"
+VERSION = "0.8.3"
 
 
 def get_long_description():
     with open(
         os.path.join(os.path.dirname(os.path.abspath(__file__)), "README.md"),
         encoding="utf8",
     ) as fp:
```


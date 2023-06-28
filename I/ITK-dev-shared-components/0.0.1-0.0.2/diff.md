# Comparing `tmp/ITK_dev_shared_components-0.0.1.tar.gz` & `tmp/ITK_dev_shared_components-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ITK_dev_shared_components-0.0.1.tar", last modified: Tue Jun 27 06:09:22 2023, max compression
+gzip compressed data, was "ITK_dev_shared_components-0.0.2.tar", last modified: Wed Jun 28 09:05:36 2023, max compression
```

## Comparing `ITK_dev_shared_components-0.0.1.tar` & `ITK_dev_shared_components-0.0.2.tar`

### file list

```diff
@@ -1,15 +1,17 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 06:09:22.344242 ITK_dev_shared_components-0.0.1/
--rw-rw-rw-   0        0        0      626 2023-06-27 06:09:22.343247 ITK_dev_shared_components-0.0.1/PKG-INFO
--rw-rw-rw-   0        0        0       52 2023-06-27 06:06:37.000000 ITK_dev_shared_components-0.0.1/README.md
--rw-rw-rw-   0        0        0      675 2023-06-27 06:09:01.000000 ITK_dev_shared_components-0.0.1/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-27 06:09:22.345364 ITK_dev_shared_components-0.0.1/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-27 06:09:22.304001 ITK_dev_shared_components-0.0.1/src/
-drwxrwxrwx   0        0        0        0 2023-06-27 06:09:22.312257 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components/
-drwxrwxrwx   0        0        0        0 2023-06-27 06:09:22.340235 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components/SAP/
--rw-rw-rw-   0        0        0     1339 2023-06-26 11:48:50.000000 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components/SAP/sap_login.py
--rw-rw-rw-   0        0        0        0 2023-06-26 12:05:07.000000 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 06:09:22.338232 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components.egg-info/
--rw-rw-rw-   0        0        0      626 2023-06-27 06:09:22.000000 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      325 2023-06-27 06:09:22.000000 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 06:09:22.000000 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       26 2023-06-27 06:09:22.000000 ITK_dev_shared_components-0.0.1/src/ITK_dev_shared_components.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      656 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.619444 ITK_dev_shared_components-0.0.2/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/
+-rw-r--r--   0 runner    (1001) docker     (123)     3610 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/multi_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/sap_login.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/top_level.txt
```

### Comparing `ITK_dev_shared_components-0.0.1/PKG-INFO` & `ITK_dev_shared_components-0.0.2/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,16 +1,17 @@
-Metadata-Version: 2.1
-Name: ITK_dev_shared_components
-Version: 0.0.1
-Summary: Shared components to use in RPA projects
-Author-email: ITK Development <itk-rpa@mkb.aarhus.dk>
-Project-URL: Homepage, https://github.com/itk-dev-rpa/itk-dev-shared-components
-Project-URL: Bug Tracker, https://github.com/itk-dev-rpa/itk-dev-shared-components/issues
-Classifier: Programming Language :: Python :: 3
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Operating System :: Microsoft :: Windows
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-
-# itk-dev-shared-components
-
-Hej itk du er min ven
+Metadata-Version: 2.1
+Name: ITK_dev_shared_components
+Version: 0.0.2
+Summary: Shared components to use in RPA projects
+Author-email: ITK Development <itk-rpa@mkb.aarhus.dk>
+Project-URL: Homepage, https://github.com/itk-dev-rpa/itk-dev-shared-components
+Project-URL: Bug Tracker, https://github.com/itk-dev-rpa/itk-dev-shared-components/issues
+Classifier: Programming Language :: Python :: 3
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Operating System :: Microsoft :: Windows
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
+# itk-dev-shared-components
+
+Version 0.0.2
```


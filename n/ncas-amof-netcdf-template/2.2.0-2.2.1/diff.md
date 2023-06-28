# Comparing `tmp/ncas_amof_netcdf_template-2.2.0.tar.gz` & `tmp/ncas_amof_netcdf_template-2.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ncas_amof_netcdf_template-2.2.0.tar", last modified: Wed Apr  5 09:35:01 2023, max compression
+gzip compressed data, was "ncas_amof_netcdf_template-2.2.1.tar", last modified: Wed Jun 28 08:47:00 2023, max compression
```

## Comparing `ncas_amof_netcdf_template-2.2.0.tar` & `ncas_amof_netcdf_template-2.2.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     6766 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4228 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     1590 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/
--rw-r--r--   0 runner    (1001) docker     (123)      191 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22320 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/create_netcdf.py
--rw-r--r--   0 runner    (1001) docker     (123)     5004 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/remove_empty_variables.py
--rw-r--r--   0 runner    (1001) docker     (123)    11944 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/tsv2dict.py
--rw-r--r--   0 runner    (1001) docker     (123)     5703 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/util.py
--rw-r--r--   0 runner    (1001) docker     (123)     3810 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/values.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6766 2023-04-05 09:35:01.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      651 2023-04-05 09:35:01.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-05 09:35:01.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-04-05 09:35:01.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-04-05 09:35:01.000000 ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-05 09:35:01.750688 ncas_amof_netcdf_template-2.2.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      508 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/tests/test_build.py
--rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/tests/test_create_netcdf.py
--rw-r--r--   0 runner    (1001) docker     (123)      346 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/tests/test_tsv2dict.py
--rw-r--r--   0 runner    (1001) docker     (123)      358 2023-04-05 09:34:48.000000 ncas_amof_netcdf_template-2.2.0/tests/test_util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:47:00.698795 ncas_amof_netcdf_template-2.2.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     6837 2023-06-28 08:47:00.698795 ncas_amof_netcdf_template-2.2.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4299 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1590 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 08:47:00.698795 ncas_amof_netcdf_template-2.2.1/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:47:00.694795 ncas_amof_netcdf_template-2.2.1/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:47:00.698795 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/
+-rw-r--r--   0 runner    (1001) docker     (123)      191 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22463 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/create_netcdf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5004 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/remove_empty_variables.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11944 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/tsv2dict.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5703 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3810 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/values.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:47:00.698795 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6837 2023-06-28 08:47:00.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      651 2023-06-28 08:47:00.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:47:00.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 08:47:00.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 08:47:00.000000 ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:47:00.698795 ncas_amof_netcdf_template-2.2.1/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      508 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/tests/test_build.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1006 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/tests/test_create_netcdf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      346 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/tests/test_tsv2dict.py
+-rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-28 08:46:50.000000 ncas_amof_netcdf_template-2.2.1/tests/test_util.py
```

### Comparing `ncas_amof_netcdf_template-2.2.0/LICENSE` & `ncas_amof_netcdf_template-2.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `ncas_amof_netcdf_template-2.2.0/PKG-INFO` & `ncas_amof_netcdf_template-2.2.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ncas_amof_netcdf_template
-Version: 2.2.0
+Version: 2.2.1
 Summary: Package to create NCAS AMOF netCDF files.
 Author-email: "Joshua M. Ralph-Hampton" <joshua.hampton@ncas.ac.uk>
 License: MIT License
         
         Copyright (c) 2023 Joshua Hampton
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -57,15 +57,15 @@
 [![Documentation Status](https://readthedocs.org/projects/ncas-amof-netcdf-template/badge/?version=stable)](https://ncas-amof-netcdf-template.readthedocs.io/en/stable)
 [![GitHub Workflow Status](https://github.com/joshua-hampton/ncas_amof_netcdf_template/actions/workflows/run_tests.yml/badge.svg)](https://github.com/joshua-hampton/ncas_amof_netcdf_template/actions/workflows/run_tests.yml)
 [![pre-commit.ci status](https://results.pre-commit.ci/badge/github/joshua-hampton/ncas_amof_netcdf_template/main.svg)](https://results.pre-commit.ci/latest/github/joshua-hampton/ncas_amof_netcdf_template/main)
 
 [![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v1.json)](https://github.com/charliermarsh/ruff)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
 
-Makes 'just-add-data' AMOF-compliant netCDF4 file.
+Makes 'just-add-data' AMOF-compliant netCDF4 file for either a given NCAS instrument or one of the defined data products.
 
 A full description on how to install and use this module can be found [through the documentation](https://ncas-amof-netcdf-template.readthedocs.io/en/stable).
 
 Requirements
 ------------
 * Python 3.7 or above
 * Python modules:
```

### Comparing `ncas_amof_netcdf_template-2.2.0/README.md` & `ncas_amof_netcdf_template-2.2.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 [![Documentation Status](https://readthedocs.org/projects/ncas-amof-netcdf-template/badge/?version=stable)](https://ncas-amof-netcdf-template.readthedocs.io/en/stable)
 [![GitHub Workflow Status](https://github.com/joshua-hampton/ncas_amof_netcdf_template/actions/workflows/run_tests.yml/badge.svg)](https://github.com/joshua-hampton/ncas_amof_netcdf_template/actions/workflows/run_tests.yml)
 [![pre-commit.ci status](https://results.pre-commit.ci/badge/github/joshua-hampton/ncas_amof_netcdf_template/main.svg)](https://results.pre-commit.ci/latest/github/joshua-hampton/ncas_amof_netcdf_template/main)
 
 [![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v1.json)](https://github.com/charliermarsh/ruff)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
 
-Makes 'just-add-data' AMOF-compliant netCDF4 file.
+Makes 'just-add-data' AMOF-compliant netCDF4 file for either a given NCAS instrument or one of the defined data products.
 
 A full description on how to install and use this module can be found [through the documentation](https://ncas-amof-netcdf-template.readthedocs.io/en/stable).
 
 Requirements
 ------------
 * Python 3.7 or above
 * Python modules:
```

### Comparing `ncas_amof_netcdf_template-2.2.0/pyproject.toml` & `ncas_amof_netcdf_template-2.2.1/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ncas_amof_netcdf_template"
-version = "2.2.0"
+version = "2.2.1"
 authors = [
   { name="Joshua M. Ralph-Hampton", email="joshua.hampton@ncas.ac.uk" },
 ]
 description = "Package to create NCAS AMOF netCDF files."
 readme = "README.md"
 license = {file = "LICENSE"}
 requires-python = ">=3.7, <4"
```

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/create_netcdf.py` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/create_netcdf.py`

 * *Files 0% similar despite different names*

```diff
@@ -175,15 +175,19 @@
                         )
                     # don't add EXAMPLE standard name
                     if not (
                         mdatkey == "standard_name"
                         and ("EXAMPLE" in mdatvalue or mdatvalue == "")
                     ):
                         # don't add empty attributes
-                        if mdatvalue == "" and verbose >= 1:
+                        if (
+                            isinstance(mdatvalue, str)
+                            and mdatvalue == ""
+                            and verbose >= 1
+                        ):
                             print(
                                 f"WARN: No value for attribute {mdatkey} "
                                 "for variable {key}, attribute not added"
                             )
                         else:
                             var.setncattr(mdatkey, mdatvalue)
```

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/remove_empty_variables.py` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/remove_empty_variables.py`

 * *Files identical despite different names*

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/tsv2dict.py` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/tsv2dict.py`

 * *Files identical despite different names*

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/util.py` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/util.py`

 * *Files identical despite different names*

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template/values.py` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template/values.py`

 * *Files identical despite different names*

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/PKG-INFO` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ncas-amof-netcdf-template
-Version: 2.2.0
+Version: 2.2.1
 Summary: Package to create NCAS AMOF netCDF files.
 Author-email: "Joshua M. Ralph-Hampton" <joshua.hampton@ncas.ac.uk>
 License: MIT License
         
         Copyright (c) 2023 Joshua Hampton
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -57,15 +57,15 @@
 [![Documentation Status](https://readthedocs.org/projects/ncas-amof-netcdf-template/badge/?version=stable)](https://ncas-amof-netcdf-template.readthedocs.io/en/stable)
 [![GitHub Workflow Status](https://github.com/joshua-hampton/ncas_amof_netcdf_template/actions/workflows/run_tests.yml/badge.svg)](https://github.com/joshua-hampton/ncas_amof_netcdf_template/actions/workflows/run_tests.yml)
 [![pre-commit.ci status](https://results.pre-commit.ci/badge/github/joshua-hampton/ncas_amof_netcdf_template/main.svg)](https://results.pre-commit.ci/latest/github/joshua-hampton/ncas_amof_netcdf_template/main)
 
 [![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v1.json)](https://github.com/charliermarsh/ruff)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
 
-Makes 'just-add-data' AMOF-compliant netCDF4 file.
+Makes 'just-add-data' AMOF-compliant netCDF4 file for either a given NCAS instrument or one of the defined data products.
 
 A full description on how to install and use this module can be found [through the documentation](https://ncas-amof-netcdf-template.readthedocs.io/en/stable).
 
 Requirements
 ------------
 * Python 3.7 or above
 * Python modules:
```

### Comparing `ncas_amof_netcdf_template-2.2.0/src/ncas_amof_netcdf_template.egg-info/SOURCES.txt` & `ncas_amof_netcdf_template-2.2.1/src/ncas_amof_netcdf_template.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `ncas_amof_netcdf_template-2.2.0/tests/test_create_netcdf.py` & `ncas_amof_netcdf_template-2.2.1/tests/test_create_netcdf.py`

 * *Files identical despite different names*


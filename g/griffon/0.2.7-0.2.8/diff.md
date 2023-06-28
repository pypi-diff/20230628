# Comparing `tmp/griffon-0.2.7.tar.gz` & `tmp/griffon-0.2.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "griffon-0.2.7.tar", last modified: Wed Jun 14 09:26:25 2023, max compression
+gzip compressed data, was "griffon-0.2.8.tar", last modified: Wed Jun 28 11:45:57 2023, max compression
```

## Comparing `griffon-0.2.7.tar` & `griffon-0.2.8.tar`

### file list

```diff
@@ -1,58 +1,58 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.028515 griffon-0.2.7/
--rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-14 09:26:07.000000 griffon-0.2.7/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     2475 2023-06-14 09:26:25.028515 griffon-0.2.7/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-06-14 09:26:07.000000 griffon-0.2.7/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.016517 griffon-0.2.7/griffon/
--rw-r--r--   0 runner    (1001) docker     (123)    11108 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.016517 griffon-0.2.7/griffon/autocomplete/
--rw-r--r--   0 runner    (1001) docker     (123)     3108 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/autocomplete/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3889 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/cli.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.020516 griffon-0.2.7/griffon/commands/
--rw-r--r--   0 runner    (1001) docker     (123)     1525 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/configure.py
--rw-r--r--   0 runner    (1001) docker     (123)     1756 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/docs.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.020516 griffon-0.2.7/griffon/commands/entities/
--rw-r--r--   0 runner    (1001) docker     (123)      748 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/entities/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26909 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/entities/community_component_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)    27403 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/entities/corgi.py
--rw-r--r--   0 runner    (1001) docker     (123)     5468 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/entities/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)    14400 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/entities/osidb.py
--rw-r--r--   0 runner    (1001) docker     (123)     1663 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugin_commands.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.024516 griffon-0.2.7/griffon/commands/plugins/
--rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/bugzilla.py
--rw-r--r--   0 runner    (1001) docker     (123)      821 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/cve_mitre.py
--rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/cvelib.py
--rw-r--r--   0 runner    (1001) docker     (123)      396 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/fcc.py
--rw-r--r--   0 runner    (1001) docker     (123)     1068 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/go_vuln.py
--rw-r--r--   0 runner    (1001) docker     (123)     1810 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/osv.py
--rw-r--r--   0 runner    (1001) docker     (123)      858 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/plugins/semgrep.py
--rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/process.py
--rw-r--r--   0 runner    (1001) docker     (123)    26911 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/queries.py
--rw-r--r--   0 runner    (1001) docker     (123)     2815 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/commands/reports.py
--rw-r--r--   0 runner    (1001) docker     (123)      443 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)    51266 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/output.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.024516 griffon-0.2.7/griffon/services/
--rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/services/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      592 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/services/core_process.py
--rw-r--r--   0 runner    (1001) docker     (123)    35881 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/services/core_queries.py
--rw-r--r--   0 runner    (1001) docker     (123)    20730 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/services/core_reports.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.024516 griffon-0.2.7/griffon/static/
--rw-r--r--   0 runner    (1001) docker     (123)     2168 2023-06-14 09:26:07.000000 griffon-0.2.7/griffon/static/default_griffonrc
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.016517 griffon-0.2.7/griffon.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2475 2023-06-14 09:26:25.000000 griffon-0.2.7/griffon.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1291 2023-06-14 09:26:25.000000 griffon-0.2.7/griffon.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-14 09:26:25.000000 griffon-0.2.7/griffon.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-14 09:26:25.000000 griffon-0.2.7/griffon.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-14 09:26:25.000000 griffon-0.2.7/griffon.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-14 09:26:25.000000 griffon-0.2.7/griffon.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1038 2023-06-14 09:26:07.000000 griffon-0.2.7/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-14 09:26:25.028515 griffon-0.2.7/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-14 09:26:07.000000 griffon-0.2.7/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 09:26:25.028515 griffon-0.2.7/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      601 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     1636 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_entities.py
--rw-r--r--   0 runner    (1001) docker     (123)      587 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_manage.py
--rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_plugins.py
--rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_process.py
--rw-r--r--   0 runner    (1001) docker     (123)      625 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_queries.py
--rw-r--r--   0 runner    (1001) docker     (123)      625 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_reports.py
--rw-r--r--   0 runner    (1001) docker     (123)     1450 2023-06-14 09:26:07.000000 griffon-0.2.7/tests/test_unit.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.841769 griffon-0.2.8/
+-rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-28 11:45:42.000000 griffon-0.2.8/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2475 2023-06-28 11:45:57.841769 griffon-0.2.8/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-06-28 11:45:42.000000 griffon-0.2.8/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.837769 griffon-0.2.8/griffon/
+-rw-r--r--   0 runner    (1001) docker     (123)    11108 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.837769 griffon-0.2.8/griffon/autocomplete/
+-rw-r--r--   0 runner    (1001) docker     (123)     3108 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/autocomplete/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3889 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.837769 griffon-0.2.8/griffon/commands/
+-rw-r--r--   0 runner    (1001) docker     (123)     1525 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/configure.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1756 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/docs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.837769 griffon-0.2.8/griffon/commands/entities/
+-rw-r--r--   0 runner    (1001) docker     (123)      748 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/entities/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26909 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/entities/community_component_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27403 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/entities/corgi.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5468 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/entities/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25401 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/entities/osidb.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1663 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugin_commands.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.837769 griffon-0.2.8/griffon/commands/plugins/
+-rw-r--r--   0 runner    (1001) docker     (123)     2294 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/bugzilla.py
+-rw-r--r--   0 runner    (1001) docker     (123)      821 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/cve_mitre.py
+-rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/cvelib.py
+-rw-r--r--   0 runner    (1001) docker     (123)      396 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/fcc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1068 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/go_vuln.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1810 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/osv.py
+-rw-r--r--   0 runner    (1001) docker     (123)      858 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/plugins/semgrep.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/process.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26911 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/queries.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2815 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/commands/reports.py
+-rw-r--r--   0 runner    (1001) docker     (123)      443 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51297 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/output.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.841769 griffon-0.2.8/griffon/services/
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/services/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      592 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/services/core_process.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35881 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/services/core_queries.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20730 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/services/core_reports.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.841769 griffon-0.2.8/griffon/static/
+-rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-06-28 11:45:42.000000 griffon-0.2.8/griffon/static/default_griffonrc
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.837769 griffon-0.2.8/griffon.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2475 2023-06-28 11:45:57.000000 griffon-0.2.8/griffon.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1291 2023-06-28 11:45:57.000000 griffon-0.2.8/griffon.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:45:57.000000 griffon-0.2.8/griffon.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-28 11:45:57.000000 griffon-0.2.8/griffon.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 11:45:57.000000 griffon-0.2.8/griffon.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 11:45:57.000000 griffon-0.2.8/griffon.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1038 2023-06-28 11:45:42.000000 griffon-0.2.8/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:45:57.841769 griffon-0.2.8/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-28 11:45:42.000000 griffon-0.2.8/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:45:57.841769 griffon-0.2.8/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      601 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1636 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_entities.py
+-rw-r--r--   0 runner    (1001) docker     (123)      587 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_manage.py
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_plugins.py
+-rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_process.py
+-rw-r--r--   0 runner    (1001) docker     (123)      625 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_queries.py
+-rw-r--r--   0 runner    (1001) docker     (123)      625 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_reports.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1450 2023-06-28 11:45:42.000000 griffon-0.2.8/tests/test_unit.py
```

### Comparing `griffon-0.2.7/LICENSE` & `griffon-0.2.8/LICENSE`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/PKG-INFO` & `griffon-0.2.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: griffon
-Version: 0.2.7
+Version: 0.2.8
 Summary: Red Hat Product Security CLI
 Home-page: https://github.com/RedHatProductSecurity/griffon
 Author: James Fuller, Red Hat Product Security
 License: MIT
 Classifier: Topic :: Security
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

### Comparing `griffon-0.2.7/README.md` & `griffon-0.2.8/README.md`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/__init__.py` & `griffon-0.2.8/griffon/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -8,15 +8,15 @@
 import osidb_bindings
 from osidb_bindings.bindings.python_client.models import Affect, Flaw, Tracker
 from pkg_resources import resource_filename  # type: ignore
 from rich.logging import RichHandler
 
 from griffon.output import console
 
-__version__ = "0.2.7"
+__version__ = "0.2.8"
 
 if "CORGI_API_URL" not in os.environ:
     print("Must set CORGI_API_URL environment variable.")
     exit(1)
 CORGI_API_URL = os.environ["CORGI_API_URL"]
 
 if "OSIDB_API_URL" not in os.environ:
```

### Comparing `griffon-0.2.7/griffon/autocomplete/__init__.py` & `griffon-0.2.8/griffon/autocomplete/__init__.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/cli.py` & `griffon-0.2.8/griffon/cli.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/configure.py` & `griffon-0.2.8/griffon/commands/configure.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/docs.py` & `griffon-0.2.8/griffon/commands/docs.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/entities/__init__.py` & `griffon-0.2.8/griffon/commands/entities/__init__.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/entities/community_component_registry.py` & `griffon-0.2.8/griffon/commands/entities/community_component_registry.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/entities/corgi.py` & `griffon-0.2.8/griffon/commands/entities/corgi.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/entities/helpers.py` & `griffon-0.2.8/griffon/commands/entities/helpers.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/plugin_commands.py` & `griffon-0.2.8/griffon/commands/plugin_commands.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/plugins/bugzilla.py` & `griffon-0.2.8/griffon/commands/plugins/bugzilla.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/plugins/cve_mitre.py` & `griffon-0.2.8/griffon/commands/plugins/cve_mitre.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/plugins/go_vuln.py` & `griffon-0.2.8/griffon/commands/plugins/go_vuln.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/plugins/osv.py` & `griffon-0.2.8/griffon/commands/plugins/osv.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/plugins/semgrep.py` & `griffon-0.2.8/griffon/commands/plugins/semgrep.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/process.py` & `griffon-0.2.8/griffon/commands/process.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/queries.py` & `griffon-0.2.8/griffon/commands/queries.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/commands/reports.py` & `griffon-0.2.8/griffon/commands/reports.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/output.py` & `griffon-0.2.8/griffon/output.py`

 * *Files 1% similar despite different names*

```diff
@@ -268,15 +268,14 @@
                     # ensure {component name} is not in profile exclude components enum
                     if not any([match in cn for match in exclude_components]):
                         console.print(
                             f"{pv}/{cn}={flaw_operation}",
                             no_wrap=no_wrap,
                         )
         else:
-
             if ctx.obj["VERBOSE"] == 0:  # product_version X component_name
                 for pv in result_tree.keys():
                     component_names = set()
                     for ps in result_tree[pv].keys():
                         component_names.update(result_tree[pv][ps].keys())
                     # we should only show component name if both {component name} and {component name-container} exists # noqa
                     if (
@@ -916,15 +915,15 @@
                     row["state"],
                     row["impact"],
                     row["resolution"],
                     no_wrap=no_wrap,
                 )
 
         # handle trackers
-        if "external_system_id" in output["results"][0]:
+        if all(key in output["results"][0] for key in ("external_system_id", "status")):
             for row in output["results"]:
                 console.print(
                     row["external_system_id"],
                     row["type"],
                     row["status"],
                     no_wrap=no_wrap,
                 )
```

### Comparing `griffon-0.2.7/griffon/services/__init__.py` & `griffon-0.2.8/griffon/services/__init__.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/services/core_process.py` & `griffon-0.2.8/griffon/services/core_process.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/services/core_queries.py` & `griffon-0.2.8/griffon/services/core_queries.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/services/core_reports.py` & `griffon-0.2.8/griffon/services/core_reports.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/griffon/static/default_griffonrc` & `griffon-0.2.8/griffon/static/default_griffonrc`

 * *Files 4% similar despite different names*

```diff
@@ -11,14 +11,17 @@
 exclude_components = -container-source
     -debuginfo
     -debugsource
     -static
     -common-debuginfo
     -doc
     -devel
+    -javadoc 
+    -testlib 
+    -repolib
 
 # profile sections (use with --profile {profile} flag)
 [cloud]
 exclude=3amp-2
     amq-.*
     ansible_automation_platform-.*
     codeready_ws-2
```

### Comparing `griffon-0.2.7/griffon.egg-info/PKG-INFO` & `griffon-0.2.8/griffon.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: griffon
-Version: 0.2.7
+Version: 0.2.8
 Summary: Red Hat Product Security CLI
 Home-page: https://github.com/RedHatProductSecurity/griffon
 Author: James Fuller, Red Hat Product Security
 License: MIT
 Classifier: Topic :: Security
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

### Comparing `griffon-0.2.7/griffon.egg-info/SOURCES.txt` & `griffon-0.2.8/griffon.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/pyproject.toml` & `griffon-0.2.8/pyproject.toml`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/setup.py` & `griffon-0.2.8/setup.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_cli.py` & `griffon-0.2.8/tests/test_cli.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_entities.py` & `griffon-0.2.8/tests/test_entities.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_manage.py` & `griffon-0.2.8/tests/test_manage.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_plugins.py` & `griffon-0.2.8/tests/test_plugins.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_process.py` & `griffon-0.2.8/tests/test_process.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_queries.py` & `griffon-0.2.8/tests/test_queries.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_reports.py` & `griffon-0.2.8/tests/test_reports.py`

 * *Files identical despite different names*

### Comparing `griffon-0.2.7/tests/test_unit.py` & `griffon-0.2.8/tests/test_unit.py`

 * *Files identical despite different names*


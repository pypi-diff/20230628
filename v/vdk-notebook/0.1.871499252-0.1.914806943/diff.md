# Comparing `tmp/vdk-notebook-0.1.871499252.tar.gz` & `tmp/vdk-notebook-0.1.914806943.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vdk-notebook-0.1.871499252.tar", last modified: Thu May 18 12:08:29 2023, max compression
+gzip compressed data, was "vdk-notebook-0.1.914806943.tar", last modified: Wed Jun 28 13:44:31 2023, max compression
```

## Comparing `vdk-notebook-0.1.871499252.tar` & `vdk-notebook-0.1.914806943.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.367636 vdk-notebook-0.1.871499252/
--rw-r--r--   0 root         (0) root         (0)     1804 2023-05-18 12:08:29.367636 vdk-notebook-0.1.871499252/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     1263 2023-05-18 12:08:15.000000 vdk-notebook-0.1.871499252/README.md
--rw-r--r--   0 root         (0) root         (0)       38 2023-05-18 12:08:29.367636 vdk-notebook-0.1.871499252/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)     1007 2023-05-18 12:08:19.000000 vdk-notebook-0.1.871499252/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.359636 vdk-notebook-0.1.871499252/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.359636 vdk-notebook-0.1.871499252/src/vdk/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.359636 vdk-notebook-0.1.871499252/src/vdk/plugin/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.363636 vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/
--rw-rw-rw-   0 root         (0) root         (0)      522 2023-05-18 12:08:15.000000 vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/cell.py
--rw-rw-rw-   0 root         (0) root         (0)     4204 2023-05-18 12:08:15.000000 vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/notebook.py
--rw-rw-rw-   0 root         (0) root         (0)     4452 2023-05-18 12:08:15.000000 vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/notebook_based_step.py
--rw-rw-rw-   0 root         (0) root         (0)     2008 2023-05-18 12:08:15.000000 vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/notebook_plugin.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.367636 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/
--rw-r--r--   0 root         (0) root         (0)     1804 2023-05-18 12:08:29.000000 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      439 2023-05-18 12:08:29.000000 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-05-18 12:08:29.000000 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       64 2023-05-18 12:08:29.000000 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)        9 2023-05-18 12:08:29.000000 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        4 2023-05-18 12:08:29.000000 vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-18 12:08:29.367636 vdk-notebook-0.1.871499252/tests/
--rw-rw-rw-   0 root         (0) root         (0)     2028 2023-05-18 12:08:15.000000 vdk-notebook-0.1.871499252/tests/test_plugin.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/
+-rw-r--r--   0 root         (0) root         (0)     1804 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     1263 2023-06-28 13:44:17.000000 vdk-notebook-0.1.914806943/README.md
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)     1007 2023-06-28 13:44:21.000000 vdk-notebook-0.1.914806943/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/src/vdk/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/src/vdk/plugin/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/
+-rw-rw-rw-   0 root         (0) root         (0)      522 2023-06-28 13:44:17.000000 vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/cell.py
+-rw-rw-rw-   0 root         (0) root         (0)     4289 2023-06-28 13:44:17.000000 vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/notebook.py
+-rw-rw-rw-   0 root         (0) root         (0)     4452 2023-06-28 13:44:17.000000 vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/notebook_based_step.py
+-rw-rw-rw-   0 root         (0) root         (0)     2008 2023-06-28 13:44:17.000000 vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/notebook_plugin.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     1804 2023-06-28 13:44:31.000000 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      439 2023-06-28 13:44:31.000000 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 13:44:31.000000 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       64 2023-06-28 13:44:31.000000 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)        9 2023-06-28 13:44:31.000000 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        4 2023-06-28 13:44:31.000000 vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:44:31.500340 vdk-notebook-0.1.914806943/tests/
+-rw-rw-rw-   0 root         (0) root         (0)     2608 2023-06-28 13:44:17.000000 vdk-notebook-0.1.914806943/tests/test_plugin.py
```

### Comparing `vdk-notebook-0.1.871499252/PKG-INFO` & `vdk-notebook-0.1.914806943/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vdk-notebook
-Version: 0.1.871499252
+Version: 0.1.914806943
 Summary: A VDK plugin for working with notebooks
 Home-page: https://github.com/vmware/versatile-data-kit
 Classifier: Development Status :: 3 - Alpha
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
```

### Comparing `vdk-notebook-0.1.871499252/README.md` & `vdk-notebook-0.1.914806943/README.md`

 * *Files identical despite different names*

### Comparing `vdk-notebook-0.1.871499252/setup.py` & `vdk-notebook-0.1.914806943/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # Copyright 2021-2023 VMware, Inc.
 # SPDX-License-Identifier: Apache-2.0
 import pathlib
 
 import setuptools
 
 
-__version__ = "0.1.871499252"
+__version__ = "0.1.914806943"
 
 setuptools.setup(
     name="vdk-notebook",
     version=__version__,
     url="https://github.com/vmware/versatile-data-kit",
     description="A VDK plugin for working with notebooks",
     long_description=pathlib.Path("README.md").read_text(),
```

### Comparing `vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/cell.py` & `vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/cell.py`

 * *Files identical despite different names*

### Comparing `vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/notebook.py` & `vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/notebook.py`

 * *Files 3% similar despite different names*

```diff
@@ -78,15 +78,15 @@
                             job_dir=context.job_directory,
                             source=cell.source,
                             cell_id=cell.id,
                             module=python_module,
                         )
                         notebook_steps.append(step)
                         context.step_builder.add_step(step)
-
+            context.step_builder._StepBuilder__steps.sort(key=lambda step: step.name)
             log.debug(f"{len(notebook_steps)} " f"cells with vdk tag were detected!")
         except json.JSONDecodeError as e:
             errors.log_and_rethrow(
                 to_be_fixed_by=errors.ResolvableBy.USER_ERROR,
                 log=log,
                 what_happened=f"Failed to read the {file_path.name} file.",
                 why_it_happened=f"The provided {file_path.name} cannot be loaded into json format and "
```

### Comparing `vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/notebook_based_step.py` & `vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/notebook_based_step.py`

 * *Files identical despite different names*

### Comparing `vdk-notebook-0.1.871499252/src/vdk/plugin/notebook/notebook_plugin.py` & `vdk-notebook-0.1.914806943/src/vdk/plugin/notebook/notebook_plugin.py`

 * *Files identical despite different names*

### Comparing `vdk-notebook-0.1.871499252/src/vdk_notebook.egg-info/PKG-INFO` & `vdk-notebook-0.1.914806943/src/vdk_notebook.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vdk-notebook
-Version: 0.1.871499252
+Version: 0.1.914806943
 Summary: A VDK plugin for working with notebooks
 Home-page: https://github.com/vmware/versatile-data-kit
 Classifier: Development Status :: 3 - Alpha
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
```

### Comparing `vdk-notebook-0.1.871499252/tests/test_plugin.py` & `vdk-notebook-0.1.914806943/tests/test_plugin.py`

 * *Files 13% similar despite different names*

```diff
@@ -21,36 +21,50 @@
 )
 class JupyterTests(unittest.TestCase):
     def setUp(self) -> None:
         self.__runner = CliEntryBasedTestRunner(notebook_plugin, sqlite_plugin)
 
     def test_successful_job(self) -> None:
         result: Result = self.__runner.invoke(
-            ["run", jobs_path_from_caller_directory("rest-api-job")]
+            ["run", jobs_path_from_caller_directory("ingest-job")]
         )
         cli_assert_equal(0, result)
         actual_rs: Result = self.__runner.invoke(
             ["sqlite-query", "--query", "SELECT * FROM rest_target_table"]
         )
         assert actual_rs.stdout == (
             "  userId    id  title                 completed\n"
             "--------  ----  ------------------  -----------\n"
             "       1     1  delectus aut autem            0\n"
         )
 
     def test_failing_job_with_syntax_error(self) -> None:
         result: Result = self.__runner.invoke(
-            ["run", jobs_path_from_caller_directory("rest-api-job-fail-syntax-error")]
+            ["run", jobs_path_from_caller_directory("ingest-job-fail-syntax-error")]
         )
         cli_assert_equal(1, result)
 
     def test_failing_job_with_code_error(self) -> None:
         result: Result = self.__runner.invoke(
-            ["run", jobs_path_from_caller_directory("rest-api-job-fail-code-error")]
+            ["run", jobs_path_from_caller_directory("ingest-job-fail-code-error")]
         )
         cli_assert_equal(2, result)
 
     def test_failing_job_with_sql_error(self) -> None:
         result: Result = self.__runner.invoke(
-            ["run", jobs_path_from_caller_directory("rest-api-job-sql-error")]
+            ["run", jobs_path_from_caller_directory("ingest-job-sql-error")]
         )
         cli_assert_equal(1, result)
+
+    def test_mixed_job_with_py_and_sql(self) -> None:
+        result: Result = self.__runner.invoke(
+            ["run", jobs_path_from_caller_directory("mixed-job")]
+        )
+        cli_assert_equal(0, result)
+        actual_rs: Result = self.__runner.invoke(
+            ["sqlite-query", "--query", "SELECT * FROM rest_target_table"]
+        )
+        assert actual_rs.stdout == (
+            "  userId    id  title                 completed\n"
+            "--------  ----  ------------------  -----------\n"
+            "       1     1  delectus aut autem            0\n"
+        )
```


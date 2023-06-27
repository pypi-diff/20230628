# Comparing `tmp/dbt_metrics_converter-0.1.0.tar.gz` & `tmp/dbt_metrics_converter-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dbt_metrics_converter-0.1.0.tar", max compression
+gzip compressed data, was "dbt_metrics_converter-0.1.1.tar", max compression
```

## Comparing `dbt_metrics_converter-0.1.0.tar` & `dbt_metrics_converter-0.1.1.tar`

### file list

```diff
@@ -1,19 +1,7 @@
--rw-r--r--   0        0        0      312 2023-06-27 00:03:40.585849 dbt_metrics_converter-0.1.0/README.md
--rw-r--r--   0        0        0        0 2023-06-27 00:10:14.086345 dbt_metrics_converter-0.1.0/converter/__init_.py
--rw-r--r--   0        0        0        0 2023-06-21 17:05:08.434049 dbt_metrics_converter-0.1.0/converter/converter/__init__.py
--rw-r--r--   0        0        0     2888 2023-06-26 22:38:50.673974 dbt_metrics_converter-0.1.0/converter/converter/dbt_metrics_to_semantic_model_converter.py
--rw-r--r--   0        0        0     3943 2023-06-21 17:05:08.438959 dbt_metrics_converter-0.1.0/converter/converter/spec_upgrade.py
--rwxr-xr-x   0        0        0      958 2023-06-26 22:33:36.843520 dbt_metrics_converter-0.1.0/converter/main.py
--rw-r--r--   0        0        0        0 2023-06-21 17:01:46.345560 dbt_metrics_converter-0.1.0/converter/metricflow_parsing/__init__.py
--rw-r--r--   0        0        0     2027 2023-06-21 17:05:08.441120 dbt_metrics_converter-0.1.0/converter/metricflow_parsing/__pycache__/dbt_cloud_to_model.cpython-39.pyc
--rw-r--r--   0        0        0     2073 2023-06-21 17:05:08.441898 dbt_metrics_converter-0.1.0/converter/metricflow_parsing/__pycache__/dbt_dir_to_model.cpython-39.pyc
--rw-r--r--   0        0        0    14498 2023-06-21 16:45:24.909461 dbt_metrics_converter-0.1.0/converter/metricflow_parsing/__pycache__/dbt_to_metricflow.cpython-39.pyc
--rw-r--r--   0        0        0     1898 2023-06-21 04:12:46.499583 dbt_metrics_converter-0.1.0/converter/metricflow_parsing/dbt_dir_to_model.py
--rw-r--r--   0        0        0    19978 2023-06-20 23:18:20.300119 dbt_metrics_converter-0.1.0/converter/metricflow_parsing/dbt_to_metricflow.py
--rw-r--r--   0        0        0        0 2023-06-21 17:18:42.657772 dbt_metrics_converter-0.1.0/converter/tests/__init__.py
--rw-r--r--   0        0        0       20 2023-06-21 17:07:43.703942 dbt_metrics_converter-0.1.0/converter/tests/fixtures.py
--rw-r--r--   0        0        0        0 2023-06-21 17:18:55.870746 dbt_metrics_converter-0.1.0/converter/tests/unit/__init__.py
--rw-r--r--   0        0        0      221 2023-06-21 17:22:49.547475 dbt_metrics_converter-0.1.0/converter/tests/unit/test_create_manifest.py
--rw-r--r--   0        0        0      241 2023-06-21 17:22:51.236057 dbt_metrics_converter-0.1.0/converter/tests/unit/test_generate_semantic_manifest.py
--rw-r--r--   0        0        0      531 2023-06-27 04:36:43.874683 dbt_metrics_converter-0.1.0/pyproject.toml
--rw-r--r--   0        0        0      890 1970-01-01 00:00:00.000000 dbt_metrics_converter-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0      312 2023-06-27 22:07:13.604230 dbt_metrics_converter-0.1.1/README.md
+-rw-r--r--   0        0        0        0 2023-06-27 22:07:13.604392 dbt_metrics_converter-0.1.1/converter/__init__.py
+-rw-r--r--   0        0        0     2888 2023-06-27 22:07:13.605469 dbt_metrics_converter-0.1.1/converter/dbt_metrics_to_semantic_model_converter.py
+-rwxr-xr-x   0        0        0     1015 2023-06-27 22:07:13.605728 dbt_metrics_converter-0.1.1/converter/main.py
+-rw-r--r--   0        0        0     3943 2023-06-27 22:07:13.605875 dbt_metrics_converter-0.1.1/converter/spec_upgrade.py
+-rw-r--r--   0        0        0      590 2023-06-27 22:07:13.607812 dbt_metrics_converter-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0      890 1970-01-01 00:00:00.000000 dbt_metrics_converter-0.1.1/PKG-INFO
```

### Comparing `dbt_metrics_converter-0.1.0/converter/converter/dbt_metrics_to_semantic_model_converter.py` & `dbt_metrics_converter-0.1.1/converter/dbt_metrics_to_semantic_model_converter.py`

 * *Files identical despite different names*

### Comparing `dbt_metrics_converter-0.1.0/converter/converter/spec_upgrade.py` & `dbt_metrics_converter-0.1.1/converter/spec_upgrade.py`

 * *Files identical despite different names*

### Comparing `dbt_metrics_converter-0.1.0/converter/main.py` & `dbt_metrics_converter-0.1.1/converter/main.py`

 * *Files 8% similar despite different names*

```diff
@@ -6,24 +6,25 @@
 @click.group()
 def cli():
     pass
 
 @cli.command()
 @click.option('--dbt-project-path', default= os.getcwd(), help='Path to dbt project containing models and metrics')
 def convert(dbt_project_path: str):
+    # from converter.spec_upgrade import MetricFLowConfig, to_yaml_mutli_file
+
     try:
         model = get_model(dbt_project_path)
     except Exception as e:
         print(f'{e}. Please check if the path to dbt project is correct: {dbt_project_path}')
         return
     write_semantic_models(model)
     write_metrics(model)
 
     delete_json_files('metrics')
     delete_json_files('data_source')
     configs = MetricFLowConfig(os.path.join(os.getcwd(),'semantic_models'), os.path.join(os.getcwd(),'metrics'))
     to_yaml_mutli_file(config=configs)
 
-def main():
-    cli()
+
 if __name__ == "__main__":
-    main()
+    cli()
```

### Comparing `dbt_metrics_converter-0.1.0/pyproject.toml` & `dbt_metrics_converter-0.1.1/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "dbt-metrics-converter"
-version = "0.1.0"
+version = "0.1.1"
 description = "Easily convert out of date, or unsported metrics spec into the latest suported metrics spec in dbt"
 authors = ["Jordan Stein <jordan.stein77@gmail.com>"]
 readme = "README.md"
 packages = [{include = "converter"}]
 
 [tool.poetry.dependencies]
 python = ">=3.9,<3.10"
@@ -13,7 +13,11 @@
 dbt-core = "^1.5.0"
 click = "^8.1.3"
 
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
+
+[tool.poetry.scripts]
+ dbt-convert= 'converter.main:cli'
+
```

### Comparing `dbt_metrics_converter-0.1.0/PKG-INFO` & `dbt_metrics_converter-0.1.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbt-metrics-converter
-Version: 0.1.0
+Version: 0.1.1
 Summary: Easily convert out of date, or unsported metrics spec into the latest suported metrics spec in dbt
 Author: Jordan Stein
 Author-email: jordan.stein77@gmail.com
 Requires-Python: >=3.9,<3.10
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Requires-Dist: click (>=8.1.3,<9.0.0)
```


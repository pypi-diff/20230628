# Comparing `tmp/astronomer_starship-1.0.4.tar.gz` & `tmp/astronomer_starship-1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "astronomer_starship-1.0.4.tar", max compression
+gzip compressed data, was "astronomer_starship-1.0.5.tar", max compression
```

## Comparing `astronomer_starship-1.0.4.tar` & `astronomer_starship-1.0.5.tar`

### file list

```diff
@@ -1,44 +1,43 @@
--rw-r--r--   0        0        0      547 2023-06-23 17:12:31.917882 astronomer_starship-1.0.4/LICENSE
--rw-r--r--   0        0        0     9187 2023-06-23 17:12:31.917882 astronomer_starship-1.0.4/README.rst
--rw-r--r--   0        0        0        0 2023-06-23 17:12:31.917882 astronomer_starship-1.0.4/astronomer/__init__.py
--rw-r--r--   0        0        0        0 2023-06-23 17:12:31.917882 astronomer_starship-1.0.4/astronomer/aeroscope/__init__.py
--rw-r--r--   0        0        0     2434 2023-06-23 17:12:31.917882 astronomer_starship-1.0.4/astronomer/aeroscope/operators.py
--rw-r--r--   0        0        0     4126 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/aeroscope/plugins/__init__.py
--rw-r--r--   0        0        0      262 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/aeroscope/plugins/templates/aeroscope/formhelper.html
--rw-r--r--   0        0        0     2524 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/aeroscope/plugins/templates/aeroscope/main.html
--rw-r--r--   0        0        0     1561 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/aeroscope/util.py
--rw-r--r--   0        0        0        0 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/__init__.py
--rw-r--r--   0        0        0    14265 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/main.py
--rw-r--r--   0        0        0     7950 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/operators.py
--rw-r--r--   0        0        0        0 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/services/__init__.py
--rw-r--r--   0        0        0     7382 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/services/astro_client.py
--rw-r--r--   0        0        0     4416 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/services/local_airflow_client.py
--rw-r--r--   0        0        0     6601 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/services/remote_airflow_client.py
--rw-r--r--   0        0        0    39434 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/static/js/htmx.min.js
--rw-r--r--   0        0        0     7015 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/static/js/idiomorph.min.js
--rw-r--r--   0        0        0    20095 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/static/js/popper.js
--rw-r--r--   0        0        0    25717 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/static/js/tippy.js
--rw-r--r--   0        0        0     1309 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/static/tail-spin.svg
--rw-r--r--   0        0        0     2926 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/dag_row.html
--rw-r--r--   0        0        0      283 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/env_checkbox.html
--rw-r--r--   0        0        0      200 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/github_loop.html
--rw-r--r--   0        0        0      738 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/migrate_connection_button.html
--rw-r--r--   0        0        0      360 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/migrate_pool_button.html
--rw-r--r--   0        0        0      367 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/migrate_variable_button.html
--rw-r--r--   0        0        0     1194 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/tabs.html
--rw-r--r--   0        0        0     2088 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/tabs_loading.html
--rw-r--r--   0        0        0     1696 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/target_deployment_select.html
--rw-r--r--   0        0        0     1227 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/target_deployment_select_loading.html
--rw-r--r--   0        0        0      177 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/test_connection_label.html
--rw-r--r--   0        0        0     2644 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/token_modal.html
--rw-r--r--   0        0        0       15 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/user_label.html
--rw-r--r--   0        0        0     1759 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/connections.html
--rw-r--r--   0        0        0     1089 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/dags.html
--rw-r--r--   0        0        0     1847 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/env.html
--rw-r--r--   0        0        0      775 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/main.html
--rw-r--r--   0        0        0      980 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/migration.html
--rw-r--r--   0        0        0     1415 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/pools.html
--rw-r--r--   0        0        0     1376 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/templates/starship/variables.html
--rw-r--r--   0        0        0     1363 2023-06-23 17:12:31.921882 astronomer_starship-1.0.4/astronomer/starship/variables/operators.py
--rw-r--r--   0        0        0     3190 2023-06-23 17:12:31.929882 astronomer_starship-1.0.4/pyproject.toml
--rw-r--r--   0        0        0    10034 1970-01-01 00:00:00.000000 astronomer_starship-1.0.4/PKG-INFO
+-rw-r--r--   0        0        0      547 2023-06-27 23:01:49.612861 astronomer_starship-1.0.5/LICENSE
+-rw-r--r--   0        0        0     9909 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/README.rst
+-rw-r--r--   0        0        0        0 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/aeroscope/__init__.py
+-rw-r--r--   0        0        0     2434 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/aeroscope/operators.py
+-rw-r--r--   0        0        0     4126 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/aeroscope/plugins/__init__.py
+-rw-r--r--   0        0        0      262 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/aeroscope/plugins/templates/aeroscope/formhelper.html
+-rw-r--r--   0        0        0     2524 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/aeroscope/plugins/templates/aeroscope/main.html
+-rw-r--r--   0        0        0     1561 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/aeroscope/util.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/__init__.py
+-rw-r--r--   0        0        0    14265 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/main.py
+-rw-r--r--   0        0        0     7950 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/operators.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/services/__init__.py
+-rw-r--r--   0        0        0     7382 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/services/astro_client.py
+-rw-r--r--   0        0        0     4416 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/services/local_airflow_client.py
+-rw-r--r--   0        0        0     6601 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/services/remote_airflow_client.py
+-rw-r--r--   0        0        0    39434 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/static/js/htmx.min.js
+-rw-r--r--   0        0        0     7015 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/static/js/idiomorph.min.js
+-rw-r--r--   0        0        0    20095 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/static/js/popper.js
+-rw-r--r--   0        0        0    25717 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/static/js/tippy.js
+-rw-r--r--   0        0        0     1309 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/static/tail-spin.svg
+-rw-r--r--   0        0        0     2926 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/dag_row.html
+-rw-r--r--   0        0        0      283 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/env_checkbox.html
+-rw-r--r--   0        0        0      738 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/migrate_connection_button.html
+-rw-r--r--   0        0        0      360 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/migrate_pool_button.html
+-rw-r--r--   0        0        0      367 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/migrate_variable_button.html
+-rw-r--r--   0        0        0     1194 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/tabs.html
+-rw-r--r--   0        0        0     2088 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/tabs_loading.html
+-rw-r--r--   0        0        0     1696 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/target_deployment_select.html
+-rw-r--r--   0        0        0     1227 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/target_deployment_select_loading.html
+-rw-r--r--   0        0        0      177 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/test_connection_label.html
+-rw-r--r--   0        0        0     2644 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/token_modal.html
+-rw-r--r--   0        0        0       15 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/user_label.html
+-rw-r--r--   0        0        0     1759 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/connections.html
+-rw-r--r--   0        0        0     1089 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/dags.html
+-rw-r--r--   0        0        0     1847 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/env.html
+-rw-r--r--   0        0        0      775 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/main.html
+-rw-r--r--   0        0        0      980 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/migration.html
+-rw-r--r--   0        0        0     1415 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/pools.html
+-rw-r--r--   0        0        0     1376 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/templates/starship/variables.html
+-rw-r--r--   0        0        0     1363 2023-06-27 23:01:49.616860 astronomer_starship-1.0.5/astronomer/starship/variables/operators.py
+-rw-r--r--   0        0        0     3244 2023-06-27 23:01:49.624860 astronomer_starship-1.0.5/pyproject.toml
+-rw-r--r--   0        0        0    10708 1970-01-01 00:00:00.000000 astronomer_starship-1.0.5/PKG-INFO
```

### Comparing `astronomer_starship-1.0.4/LICENSE` & `astronomer_starship-1.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/README.rst` & `astronomer_starship-1.0.5/README.rst`

 * *Files 2% similar despite different names*

```diff
@@ -191,11 +191,25 @@
 2. In the table displaying the DAGs present in both the source and target environments, click the Pause ⏸️ icon under ``Local``
 
 .. image:: images/cutover-pause-local.png
 
 3. In the table displaying the DAGs present in both the source and target environments, click the Start ▶️ icon under ``Remote``
 4. After completing this process, you will see the DAG is paused in the ``Local`` environment (a Start ▶️ Icon) and is un-paused in the ``Remote`` environment (a Pause ⏸️ icon)
 
+
+FAQ
+---
+- If you have an error installing Starship via pip and see a message like :code:`ERROR: pip's dependency resolver does not currently take into account all the packages that are installed`, add the dependencies that are listed in the error to your :code:`pip install` or :code:`requirements.txt`, e.g.
+
+.. code-block::
+
+    ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
+    rich 10.9.0 requires typing-extensions<4.0.0,>=3.7.4; python_version < "3.8", but you have typing-extensions 4.6.3 which is incompatible.
+
+.. code-block:: bash
+
+    pip install astronomer-starship rich==10.9.0
+
 License
 -------
 
 `License <LICENSE.txt>`_
```

### Comparing `astronomer_starship-1.0.4/astronomer/aeroscope/operators.py` & `astronomer_starship-1.0.5/astronomer/aeroscope/operators.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/aeroscope/plugins/__init__.py` & `astronomer_starship-1.0.5/astronomer/aeroscope/plugins/__init__.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/aeroscope/plugins/templates/aeroscope/main.html` & `astronomer_starship-1.0.5/astronomer/aeroscope/plugins/templates/aeroscope/main.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/aeroscope/util.py` & `astronomer_starship-1.0.5/astronomer/aeroscope/util.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/main.py` & `astronomer_starship-1.0.5/astronomer/starship/main.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/operators.py` & `astronomer_starship-1.0.5/astronomer/starship/operators.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/services/astro_client.py` & `astronomer_starship-1.0.5/astronomer/starship/services/astro_client.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/services/local_airflow_client.py` & `astronomer_starship-1.0.5/astronomer/starship/services/local_airflow_client.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/services/remote_airflow_client.py` & `astronomer_starship-1.0.5/astronomer/starship/services/remote_airflow_client.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/static/js/htmx.min.js` & `astronomer_starship-1.0.5/astronomer/starship/static/js/htmx.min.js`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/static/js/idiomorph.min.js` & `astronomer_starship-1.0.5/astronomer/starship/static/js/idiomorph.min.js`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/static/js/popper.js` & `astronomer_starship-1.0.5/astronomer/starship/static/js/popper.js`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/static/js/tippy.js` & `astronomer_starship-1.0.5/astronomer/starship/static/js/tippy.js`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/static/tail-spin.svg` & `astronomer_starship-1.0.5/astronomer/starship/static/tail-spin.svg`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/dag_row.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/dag_row.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/migrate_connection_button.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/migrate_connection_button.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/tabs.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/tabs.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/tabs_loading.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/tabs_loading.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/target_deployment_select.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/target_deployment_select.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/target_deployment_select_loading.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/target_deployment_select_loading.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/components/token_modal.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/components/token_modal.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/connections.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/connections.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/dags.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/dags.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/env.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/env.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/main.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/main.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/migration.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/migration.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/pools.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/pools.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/templates/starship/variables.html` & `astronomer_starship-1.0.5/astronomer/starship/templates/starship/variables.html`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/astronomer/starship/variables/operators.py` & `astronomer_starship-1.0.5/astronomer/starship/variables/operators.py`

 * *Files identical despite different names*

### Comparing `astronomer_starship-1.0.4/pyproject.toml` & `astronomer_starship-1.0.5/pyproject.toml`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "astronomer-starship"
-version = "1.0.4"
+version = "1.0.5"
 description = "Migrations to Astro"
 authors = ["ADE Team <ade@astronomer.io>"]
 readme = "README.rst"
 repository = "https://github.com/astronomer/starship"
 homepage = "https://astronomer.io"
 license = "Proprietary"
 packages = [{include = "astronomer"}]  #, from = "." }]
@@ -18,19 +18,19 @@
 #package-dir = {"" = "astronomer"}
 #
 #[tool.setuptools.packages.find]
 #where = ["astronomer"]
 
 [tool.poetry.dependencies]
 python = ">=3.7.2,<4.0"
-pydash = "^7.0.0"
-python-graphql-client = "^0.4.3"
-requests = "^2.28.2"
-cachetools = "^5.3.0"
-pygithub = "^1.58.1"
+pydash = "^7"
+python-graphql-client = "^0"
+requests = "^2"
+cachetools = "<6,>=4"
+pyjwt = ">=1"
 
 [tool.poetry.group.orion.dependencies]
 click = "^8.1.3"
 halo = "^0.0.31"
 fs = "^2.4.16"
 
 [tool.poetry.group.dev.dependencies]
@@ -49,14 +49,16 @@
 pytest-mock = "^3.10.0"
 apache-airflow = "^2.6.1"
 isort = {version = "^5.12.0", python = ">=3.8.1"}
 python-dotenv = {version = "^1.0.0", python = ">=3.8.1"}
 sh = {version = "^2.0.4", python = ">=3.8.1"}
 pre-commit = {version = "^3.3.3", python = ">=3.8.1"}
 toml = {version = "^0.10.2", python = "<3.11"}
+docker = "^6.1.3"
+pytest-xdist = {extras = ["psutil"], version = "^3.3.1"}
 
 
 [tool.poetry.group.aws.dependencies]
 boto3 = "^1.26.81"
 boto3-stubs = {extras = ["mwaa", "s3"], version = "^1.26.81"}
 fs-s3fs = "^1.1.1"
 
@@ -104,15 +106,15 @@
 norecursedirs =["tests/resources/", "hooks", "*.egg", ".eggs", "dist", "build", "docs", ".tox", ".git", "__pycache__"]
 doctest_optionflags = ["NUMBER", "NORMALIZE_WHITESPACE", "IGNORE_EXCEPTION_DETAIL"]
 
 # Extra options:
 addopts = [
 #  "--ignore=tests/resources/example-dag.py",
 #  "--ignore=resources/fix.py",
-#  "--numprocesses=auto",
+  "--numprocesses=auto",
   "--strict-markers",
   "--tb=short",
   "--disable-warnings",
   "--no-header",
   "--doctest-modules",
   "--doctest-continue-on-failure",
 ]
```

### Comparing `astronomer_starship-1.0.4/PKG-INFO` & `astronomer_starship-1.0.5/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 Metadata-Version: 2.1
 Name: astronomer-starship
-Version: 1.0.4
+Version: 1.0.5
 Summary: Migrations to Astro
 Home-page: https://astronomer.io
 License: Proprietary
 Author: ADE Team
 Author-email: ade@astronomer.io
 Requires-Python: >=3.7.2,<4.0
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Requires-Dist: cachetools (>=5.3.0,<6.0.0)
-Requires-Dist: pydash (>=7.0.0,<8.0.0)
-Requires-Dist: pygithub (>=1.58.1,<2.0.0)
-Requires-Dist: python-graphql-client (>=0.4.3,<0.5.0)
-Requires-Dist: requests (>=2.28.2,<3.0.0)
+Requires-Dist: cachetools (>=4,<6)
+Requires-Dist: pydash (>=7,<8)
+Requires-Dist: pyjwt (>=1)
+Requires-Dist: python-graphql-client (>=0,<1)
+Requires-Dist: requests (>=2,<3)
 Project-URL: Repository, https://github.com/astronomer/starship
 Description-Content-Type: text/x-rst
 
 Astronomer Starship
 ===================
 A suite of Apache Airflow utilities containing Plugins and Operators from Astronomer. The purpose of these utilities is to better assist customers migrating Variables, Connections, and Environment Variables to Astronomer hosted Airflow environments from MWAA, GCC, and OSS environments, as well as Astronomer Software and Nebula instances.
 
@@ -214,12 +214,26 @@
 2. In the table displaying the DAGs present in both the source and target environments, click the Pause ⏸️ icon under ``Local``
 
 .. image:: images/cutover-pause-local.png
 
 3. In the table displaying the DAGs present in both the source and target environments, click the Start ▶️ icon under ``Remote``
 4. After completing this process, you will see the DAG is paused in the ``Local`` environment (a Start ▶️ Icon) and is un-paused in the ``Remote`` environment (a Pause ⏸️ icon)
 
+
+FAQ
+---
+- If you have an error installing Starship via pip and see a message like :code:`ERROR: pip's dependency resolver does not currently take into account all the packages that are installed`, add the dependencies that are listed in the error to your :code:`pip install` or :code:`requirements.txt`, e.g.
+
+.. code-block::
+
+    ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
+    rich 10.9.0 requires typing-extensions<4.0.0,>=3.7.4; python_version < "3.8", but you have typing-extensions 4.6.3 which is incompatible.
+
+.. code-block:: bash
+
+    pip install astronomer-starship rich==10.9.0
+
 License
 -------
 
 `License <LICENSE.txt>`_
```


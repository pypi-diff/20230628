# Comparing `tmp/summerepi2-1.2.3.tar.gz` & `tmp/summerepi2-1.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "summerepi2-1.2.3.tar", max compression
+gzip compressed data, was "summerepi2-1.2.4.tar", max compression
```

## Comparing `summerepi2-1.2.3.tar` & `summerepi2-1.2.4.tar`

### file list

```diff
@@ -1,36 +1,36 @@
--rw-r--r--   0        0        0     1512 2022-09-01 20:25:00.648111 summerepi2-1.2.3/LICENSE.txt
--rw-r--r--   0        0        0     1930 2023-05-11 01:54:34.520878 summerepi2-1.2.3/pyproject.toml
--rw-r--r--   0        0        0     4101 2023-04-12 23:09:18.690955 summerepi2-1.2.3/README.md
--rw-r--r--   0        0        0      280 2022-09-01 05:32:07.966265 summerepi2-1.2.3/summer2/__init__.py
--rw-r--r--   0        0        0     4095 2022-09-01 05:32:07.967266 summerepi2-1.2.3/summer2/adjust.py
--rw-r--r--   0        0        0     4782 2022-09-01 05:32:07.967769 summerepi2-1.2.3/summer2/compartment.py
--rw-r--r--   0        0        0      137 2022-08-26 06:17:31.101047 summerepi2-1.2.3/summer2/compute_bak/__init__.py
--rw-r--r--   0        0        0     2151 2022-08-27 21:20:06.649159 summerepi2-1.2.3/summer2/compute_bak/compute_jax.py
--rw-r--r--   0        0        0    11683 2022-09-01 05:32:07.968765 summerepi2-1.2.3/summer2/derived_outputs.py
--rw-r--r--   0        0        0    10490 2023-04-05 00:33:04.716810 summerepi2-1.2.3/summer2/experimental/model_builder.py
--rw-r--r--   0        0        0     2603 2023-04-19 22:25:13.644705 summerepi2-1.2.3/summer2/extras/test_models.py
--rw-r--r--   0        0        0    19144 2022-09-01 05:32:07.970266 summerepi2-1.2.3/summer2/flows.py
--rw-r--r--   0        0        0      203 2023-02-10 00:07:02.891606 summerepi2-1.2.3/summer2/functions/__init__.py
--rw-r--r--   0        0        0     4620 2023-01-17 01:08:37.545738 summerepi2-1.2.3/summer2/functions/interpolate.py
--rw-r--r--   0        0        0     3453 2023-02-09 22:50:26.022665 summerepi2-1.2.3/summer2/functions/time.py
--rw-r--r--   0        0        0     3670 2023-04-12 21:11:57.753156 summerepi2-1.2.3/summer2/functions/util.py
--rw-r--r--   0        0        0     6019 2022-10-11 00:26:22.994134 summerepi2-1.2.3/summer2/inspect.py
--rw-r--r--   0        0        0    53798 2023-05-11 03:19:13.430929 summerepi2-1.2.3/summer2/model.py
--rw-r--r--   0        0        0       22 2022-10-11 01:49:59.803947 summerepi2-1.2.3/summer2/parameters/__init__.py
--rw-r--r--   0        0        0    10987 2023-04-18 23:12:23.096368 summerepi2-1.2.3/summer2/parameters/param_impl.py
--rw-r--r--   0        0        0     4255 2023-04-05 00:33:04.747809 summerepi2-1.2.3/summer2/parameters/params.py
--rw-r--r--   0        0        0     4804 2022-09-01 05:32:07.974766 summerepi2-1.2.3/summer2/population.py
--rw-r--r--   0        0        0       40 2022-09-01 05:32:07.975265 summerepi2-1.2.3/summer2/runner/__init__.py
--rw-r--r--   0        0        0        0 2022-09-01 05:32:07.975767 summerepi2-1.2.3/summer2/runner/jax/__init__.py
--rw-r--r--   0        0        0     5240 2023-05-02 00:15:48.813286 summerepi2-1.2.3/summer2/runner/jax/derived_outputs.py
--rw-r--r--   0        0        0    25476 2023-05-11 03:24:09.889928 summerepi2-1.2.3/summer2/runner/jax/model_impl.py
--rw-r--r--   0        0        0    11588 2023-04-05 00:33:04.765810 summerepi2-1.2.3/summer2/runner/jax/ode.py
--rw-r--r--   0        0        0    11222 2022-10-12 17:29:54.983503 summerepi2-1.2.3/summer2/runner/jax/ode2.py
--rw-r--r--   0        0        0     2736 2022-11-30 22:02:39.159369 summerepi2-1.2.3/summer2/runner/jax/solvers.py
--rw-r--r--   0        0        0     5111 2022-09-01 05:32:08.044494 summerepi2-1.2.3/summer2/runner/jax/stratify.py
--rw-r--r--   0        0        0     8170 2022-12-02 02:13:10.114800 summerepi2-1.2.3/summer2/runner/model_runner.py
--rw-r--r--   0        0        0     6277 2022-10-11 01:50:00.034457 summerepi2-1.2.3/summer2/solver.py
--rw-r--r--   0        0        0    17065 2023-04-18 23:09:58.702374 summerepi2-1.2.3/summer2/stratification.py
--rw-r--r--   0        0        0      472 2022-09-01 05:32:08.049501 summerepi2-1.2.3/summer2/tracker.py
--rw-r--r--   0        0        0     3760 2023-05-11 02:02:50.793367 summerepi2-1.2.3/summer2/utils.py
--rw-r--r--   0        0        0     5622 1970-01-01 00:00:00.000000 summerepi2-1.2.3/PKG-INFO
+-rw-r--r--   0        0        0     1512 2022-09-01 20:25:00.648111 summerepi2-1.2.4/LICENSE.txt
+-rw-r--r--   0        0        0     1930 2023-06-28 03:15:41.862897 summerepi2-1.2.4/pyproject.toml
+-rw-r--r--   0        0        0     4207 2023-06-28 03:16:29.056785 summerepi2-1.2.4/README.md
+-rw-r--r--   0        0        0      280 2022-09-01 05:32:07.966265 summerepi2-1.2.4/summer2/__init__.py
+-rw-r--r--   0        0        0     4095 2022-09-01 05:32:07.967266 summerepi2-1.2.4/summer2/adjust.py
+-rw-r--r--   0        0        0     4782 2022-09-01 05:32:07.967769 summerepi2-1.2.4/summer2/compartment.py
+-rw-r--r--   0        0        0      137 2022-08-26 06:17:31.101047 summerepi2-1.2.4/summer2/compute_bak/__init__.py
+-rw-r--r--   0        0        0     2151 2022-08-27 21:20:06.649159 summerepi2-1.2.4/summer2/compute_bak/compute_jax.py
+-rw-r--r--   0        0        0    11683 2022-09-01 05:32:07.968765 summerepi2-1.2.4/summer2/derived_outputs.py
+-rw-r--r--   0        0        0    10490 2023-04-05 00:33:04.716810 summerepi2-1.2.4/summer2/experimental/model_builder.py
+-rw-r--r--   0        0        0     2603 2023-04-19 22:25:13.644705 summerepi2-1.2.4/summer2/extras/test_models.py
+-rw-r--r--   0        0        0    19144 2022-09-01 05:32:07.970266 summerepi2-1.2.4/summer2/flows.py
+-rw-r--r--   0        0        0      203 2023-02-10 00:07:02.891606 summerepi2-1.2.4/summer2/functions/__init__.py
+-rw-r--r--   0        0        0     4620 2023-01-17 01:08:37.545738 summerepi2-1.2.4/summer2/functions/interpolate.py
+-rw-r--r--   0        0        0     3453 2023-02-09 22:50:26.022665 summerepi2-1.2.4/summer2/functions/time.py
+-rw-r--r--   0        0        0     3670 2023-04-12 21:11:57.753156 summerepi2-1.2.4/summer2/functions/util.py
+-rw-r--r--   0        0        0     6019 2022-10-11 00:26:22.994134 summerepi2-1.2.4/summer2/inspect.py
+-rw-r--r--   0        0        0    53798 2023-05-11 03:19:13.430929 summerepi2-1.2.4/summer2/model.py
+-rw-r--r--   0        0        0       22 2022-10-11 01:49:59.803947 summerepi2-1.2.4/summer2/parameters/__init__.py
+-rw-r--r--   0        0        0    10987 2023-04-18 23:12:23.096368 summerepi2-1.2.4/summer2/parameters/param_impl.py
+-rw-r--r--   0        0        0     4255 2023-04-05 00:33:04.747809 summerepi2-1.2.4/summer2/parameters/params.py
+-rw-r--r--   0        0        0     4804 2022-09-01 05:32:07.974766 summerepi2-1.2.4/summer2/population.py
+-rw-r--r--   0        0        0       40 2022-09-01 05:32:07.975265 summerepi2-1.2.4/summer2/runner/__init__.py
+-rw-r--r--   0        0        0        0 2022-09-01 05:32:07.975767 summerepi2-1.2.4/summer2/runner/jax/__init__.py
+-rw-r--r--   0        0        0     5240 2023-05-02 00:15:48.813286 summerepi2-1.2.4/summer2/runner/jax/derived_outputs.py
+-rw-r--r--   0        0        0    25537 2023-06-28 03:14:36.552513 summerepi2-1.2.4/summer2/runner/jax/model_impl.py
+-rw-r--r--   0        0        0    11588 2023-04-05 00:33:04.765810 summerepi2-1.2.4/summer2/runner/jax/ode.py
+-rw-r--r--   0        0        0    11222 2022-10-12 17:29:54.983503 summerepi2-1.2.4/summer2/runner/jax/ode2.py
+-rw-r--r--   0        0        0     2736 2022-11-30 22:02:39.159369 summerepi2-1.2.4/summer2/runner/jax/solvers.py
+-rw-r--r--   0        0        0     5111 2022-09-01 05:32:08.044494 summerepi2-1.2.4/summer2/runner/jax/stratify.py
+-rw-r--r--   0        0        0     8170 2022-12-02 02:13:10.114800 summerepi2-1.2.4/summer2/runner/model_runner.py
+-rw-r--r--   0        0        0     6277 2022-10-11 01:50:00.034457 summerepi2-1.2.4/summer2/solver.py
+-rw-r--r--   0        0        0    17065 2023-04-18 23:09:58.702374 summerepi2-1.2.4/summer2/stratification.py
+-rw-r--r--   0        0        0      472 2022-09-01 05:32:08.049501 summerepi2-1.2.4/summer2/tracker.py
+-rw-r--r--   0        0        0     3760 2023-05-11 02:02:50.793367 summerepi2-1.2.4/summer2/utils.py
+-rw-r--r--   0        0        0     5728 1970-01-01 00:00:00.000000 summerepi2-1.2.4/PKG-INFO
```

### Comparing `summerepi2-1.2.3/LICENSE.txt` & `summerepi2-1.2.4/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/pyproject.toml` & `summerepi2-1.2.4/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "summerepi2"
-version = "1.2.3"
+version = "1.2.4"
 readme = "README.md"
 license = "BSD-2-Clause"
 homepage = "http://summerepi.com/"
 documentation = "http://summerepi.com/"
 repository = "https://github.com/monash-emu/summer2"
 keywords = [
     "epidemiology",
```

### Comparing `summerepi2-1.2.3/README.md` & `summerepi2-1.2.4/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -92,14 +92,16 @@
 - 1.0.0/1:
   - Initial release
 - 1.2.1
   - Dropped support for Python 3.7.  Variety of bugfixes and expanded features, see documentation
 - 1.2.2
   - Added capture utils
   - Removed inner jit in model building to improve debugging
+- 1.2.4
+  - CompartmentValues not functioning previously; include more comprehensive check in graph split
 
 ## Release process
 
 To do a release:
 
 - Commit any code changes and push them to GitHub
 - Choose a new release number accoridng to [Semantic Versioning](https://semver.org/)
```

### Comparing `summerepi2-1.2.3/summer2/adjust.py` & `summerepi2-1.2.4/summer2/adjust.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/compartment.py` & `summerepi2-1.2.4/summer2/compartment.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/compute_bak/compute_jax.py` & `summerepi2-1.2.4/summer2/compute_bak/compute_jax.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/derived_outputs.py` & `summerepi2-1.2.4/summer2/derived_outputs.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/experimental/model_builder.py` & `summerepi2-1.2.4/summer2/experimental/model_builder.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/extras/test_models.py` & `summerepi2-1.2.4/summer2/extras/test_models.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/flows.py` & `summerepi2-1.2.4/summer2/flows.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/functions/interpolate.py` & `summerepi2-1.2.4/summer2/functions/interpolate.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/functions/time.py` & `summerepi2-1.2.4/summer2/functions/time.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/functions/util.py` & `summerepi2-1.2.4/summer2/functions/util.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/inspect.py` & `summerepi2-1.2.4/summer2/inspect.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/model.py` & `summerepi2-1.2.4/summer2/model.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/parameters/param_impl.py` & `summerepi2-1.2.4/summer2/parameters/param_impl.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/parameters/params.py` & `summerepi2-1.2.4/summer2/parameters/params.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/population.py` & `summerepi2-1.2.4/summer2/population.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/runner/jax/derived_outputs.py` & `summerepi2-1.2.4/summer2/runner/jax/derived_outputs.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/runner/jax/model_impl.py` & `summerepi2-1.2.4/summer2/runner/jax/model_impl.py`

 * *Files 0% similar despite different names*

```diff
@@ -480,16 +480,20 @@
     get_compartment_infectiousness = build_get_compartment_infectiousness(runner.model)
 
     do_cg, calc_derived_outputs = build_derived_outputs_runner(
         runner.model, whitelist=derived_outputs
     )
 
     m = runner.model
-    if "model_variables.time" in m.graph.dag:
-        tv_keys = list(m.graph.filter(sources="model_variables.time").dag)
+    dag_keys = list(m.graph.dag)
+
+    mvars = [k for k in dag_keys if k.startswith("model_variables.")]
+
+    if len(mvars):
+        tv_keys = list(m.graph.filter(sources=mvars).dag)
     else:
         tv_keys = []
 
     static_flow_map = {k: m._flow_key_map[k] for k in set(m._flow_key_map).difference(set(tv_keys))}
 
     model_times = jnp.array(m.times)
```

### Comparing `summerepi2-1.2.3/summer2/runner/jax/ode.py` & `summerepi2-1.2.4/summer2/runner/jax/ode.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/runner/jax/ode2.py` & `summerepi2-1.2.4/summer2/runner/jax/ode2.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/runner/jax/solvers.py` & `summerepi2-1.2.4/summer2/runner/jax/solvers.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/runner/jax/stratify.py` & `summerepi2-1.2.4/summer2/runner/jax/stratify.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/runner/model_runner.py` & `summerepi2-1.2.4/summer2/runner/model_runner.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/solver.py` & `summerepi2-1.2.4/summer2/solver.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/stratification.py` & `summerepi2-1.2.4/summer2/stratification.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/summer2/utils.py` & `summerepi2-1.2.4/summer2/utils.py`

 * *Files identical despite different names*

### Comparing `summerepi2-1.2.3/PKG-INFO` & `summerepi2-1.2.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: summerepi2
-Version: 1.2.3
+Version: 1.2.4
 Summary: Summer is a compartmental disease modelling framework, written in Python. It provides a high-level API to build and run models.
 Home-page: http://summerepi.com/
 License: BSD-2-Clause
 Keywords: epidemiology,disease,compartmental,infectious
 Author: James Trauer
 Author-email: james.trauer@monash.edu
 Requires-Python: >=3.8.0
@@ -126,14 +126,16 @@
 - 1.0.0/1:
   - Initial release
 - 1.2.1
   - Dropped support for Python 3.7.  Variety of bugfixes and expanded features, see documentation
 - 1.2.2
   - Added capture utils
   - Removed inner jit in model building to improve debugging
+- 1.2.4
+  - CompartmentValues not functioning previously; include more comprehensive check in graph split
 
 ## Release process
 
 To do a release:
 
 - Commit any code changes and push them to GitHub
 - Choose a new release number accoridng to [Semantic Versioning](https://semver.org/)
```


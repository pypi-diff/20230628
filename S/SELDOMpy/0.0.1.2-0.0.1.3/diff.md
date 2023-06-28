# Comparing `tmp/SELDOMpy-0.0.1.2.tar.gz` & `tmp/SELDOMpy-0.0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\SELDOMpy-0.0.1.2.tar", last modified: Wed Jun 28 10:53:02 2023, max compression
+gzip compressed data, was "dist\SELDOMpy-0.0.1.3.tar", last modified: Wed Jun 28 10:58:42 2023, max compression
```

## Comparing `SELDOMpy-0.0.1.2.tar` & `SELDOMpy-0.0.1.3.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 10:53:02.124151 SELDOMpy-0.0.1.2/
--rw-rw-rw-   0        0        0      731 2023-06-28 10:53:02.124151 SELDOMpy-0.0.1.2/PKG-INFO
--rw-rw-rw-   0        0        0      182 2023-06-28 07:06:15.000000 SELDOMpy-0.0.1.2/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 10:53:02.110152 SELDOMpy-0.0.1.2/SELDOMpy/
--rw-rw-rw-   0        0        0      492 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.2/SELDOMpy/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:53:02.123153 SELDOMpy-0.0.1.2/SELDOMpy/functions/
--rw-rw-rw-   0        0        0        0 2023-06-28 09:26:39.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/__init__.py
--rw-rw-rw-   0        0        0     2309 2023-06-22 08:44:09.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/buildmim.py
--rw-rw-rw-   0        0        0     1271 2023-04-14 17:44:15.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/extras.py
--rw-rw-rw-   0        0        0     4159 2023-04-19 14:22:26.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/gen_exps.py
--rw-rw-rw-   0        0        0     4848 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/getLBODEmodel.py
--rw-rw-rw-   0        0        0     3232 2023-04-24 18:45:26.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/getRandomLBODEmodel.py
--rw-rw-rw-   0        0        0     2470 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/opt_mealpy.py
--rw-rw-rw-   0        0        0     1438 2023-06-23 11:21:41.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/plot_results.py
--rw-rw-rw-   0        0        0     2534 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/reduce_fun.py
--rw-rw-rw-   0        0        0     4073 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/simulate_logic_based_ode.py
--rw-rw-rw-   0        0        0     3626 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.2/SELDOMpy/functions/simulate_logic_based_ode_obs.py
--rw-rw-rw-   0        0        0     6479 2023-06-28 09:37:33.000000 SELDOMpy-0.0.1.2/SELDOMpy/training_and_reduce.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:53:02.114151 SELDOMpy-0.0.1.2/SELDOMpy.egg-info/
--rw-rw-rw-   0        0        0      731 2023-06-28 10:53:02.000000 SELDOMpy-0.0.1.2/SELDOMpy.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      638 2023-06-28 10:53:02.000000 SELDOMpy-0.0.1.2/SELDOMpy.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 10:53:02.000000 SELDOMpy-0.0.1.2/SELDOMpy.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       55 2023-06-28 10:53:02.000000 SELDOMpy-0.0.1.2/SELDOMpy.egg-info/requires.txt
--rw-rw-rw-   0        0        0        9 2023-06-28 10:53:02.000000 SELDOMpy-0.0.1.2/SELDOMpy.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 10:53:02.124151 SELDOMpy-0.0.1.2/setup.cfg
--rw-rw-rw-   0        0        0     1241 2023-06-28 10:53:00.000000 SELDOMpy-0.0.1.2/setup_seldompy.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:58:42.389154 SELDOMpy-0.0.1.3/
+-rw-rw-rw-   0        0        0      731 2023-06-28 10:58:42.389154 SELDOMpy-0.0.1.3/PKG-INFO
+-rw-rw-rw-   0        0        0      182 2023-06-28 07:06:15.000000 SELDOMpy-0.0.1.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 10:58:42.372158 SELDOMpy-0.0.1.3/SELDOMpy/
+-rw-rw-rw-   0        0        0      492 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.3/SELDOMpy/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:58:42.388154 SELDOMpy-0.0.1.3/SELDOMpy/functions/
+-rw-rw-rw-   0        0        0        0 2023-06-28 09:26:39.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/__init__.py
+-rw-rw-rw-   0        0        0     2309 2023-06-22 08:44:09.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/buildmim.py
+-rw-rw-rw-   0        0        0     1271 2023-04-14 17:44:15.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/extras.py
+-rw-rw-rw-   0        0        0     4159 2023-04-19 14:22:26.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/gen_exps.py
+-rw-rw-rw-   0        0        0     4848 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/getLBODEmodel.py
+-rw-rw-rw-   0        0        0     3232 2023-04-24 18:45:26.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/getRandomLBODEmodel.py
+-rw-rw-rw-   0        0        0     2470 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/opt_mealpy.py
+-rw-rw-rw-   0        0        0     1438 2023-06-23 11:21:41.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/plot_results.py
+-rw-rw-rw-   0        0        0     2534 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/reduce_fun.py
+-rw-rw-rw-   0        0        0     4073 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/simulate_logic_based_ode.py
+-rw-rw-rw-   0        0        0     3626 2023-06-28 09:27:05.000000 SELDOMpy-0.0.1.3/SELDOMpy/functions/simulate_logic_based_ode_obs.py
+-rw-rw-rw-   0        0        0     6479 2023-06-28 09:37:33.000000 SELDOMpy-0.0.1.3/SELDOMpy/training_and_reduce.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:58:42.378153 SELDOMpy-0.0.1.3/SELDOMpy.egg-info/
+-rw-rw-rw-   0        0        0      731 2023-06-28 10:58:42.000000 SELDOMpy-0.0.1.3/SELDOMpy.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      629 2023-06-28 10:58:42.000000 SELDOMpy-0.0.1.3/SELDOMpy.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:58:42.000000 SELDOMpy-0.0.1.3/SELDOMpy.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       55 2023-06-28 10:58:42.000000 SELDOMpy-0.0.1.3/SELDOMpy.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 10:58:42.000000 SELDOMpy-0.0.1.3/SELDOMpy.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:58:42.389154 SELDOMpy-0.0.1.3/setup.cfg
+-rw-rw-rw-   0        0        0     1241 2023-06-28 10:55:03.000000 SELDOMpy-0.0.1.3/setup.py
```

### Comparing `SELDOMpy-0.0.1.2/PKG-INFO` & `SELDOMpy-0.0.1.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: SELDOMpy
-Version: 0.0.1.2
+Version: 0.0.1.3
 Summary: Package for modelling cellular signalling networks
 Home-page: https://github.com/lupralo31/SELDOMpy
 Download-URL: https://github.com/lupralo31/SELDOMpy
 Author: Luis Prado
 Author-email: <pradolopezluis@gmail.com>
 License: MIT
 Keywords: python,SELDOMpy
```

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/buildmim.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/buildmim.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/extras.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/extras.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/gen_exps.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/gen_exps.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/getLBODEmodel.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/getLBODEmodel.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/getRandomLBODEmodel.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/getRandomLBODEmodel.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/opt_mealpy.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/opt_mealpy.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/plot_results.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/plot_results.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/reduce_fun.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/reduce_fun.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/simulate_logic_based_ode.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/simulate_logic_based_ode.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/functions/simulate_logic_based_ode_obs.py` & `SELDOMpy-0.0.1.3/SELDOMpy/functions/simulate_logic_based_ode_obs.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy/training_and_reduce.py` & `SELDOMpy-0.0.1.3/SELDOMpy/training_and_reduce.py`

 * *Files identical despite different names*

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy.egg-info/PKG-INFO` & `SELDOMpy-0.0.1.3/SELDOMpy.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: SELDOMpy
-Version: 0.0.1.2
+Version: 0.0.1.3
 Summary: Package for modelling cellular signalling networks
 Home-page: https://github.com/lupralo31/SELDOMpy
 Download-URL: https://github.com/lupralo31/SELDOMpy
 Author: Luis Prado
 Author-email: <pradolopezluis@gmail.com>
 License: MIT
 Keywords: python,SELDOMpy
```

### Comparing `SELDOMpy-0.0.1.2/SELDOMpy.egg-info/SOURCES.txt` & `SELDOMpy-0.0.1.3/SELDOMpy.egg-info/SOURCES.txt`

 * *Files 11% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 README.md
-setup_seldompy.py
+setup.py
 SELDOMpy/__init__.py
 SELDOMpy/training_and_reduce.py
 SELDOMpy.egg-info/PKG-INFO
 SELDOMpy.egg-info/SOURCES.txt
 SELDOMpy.egg-info/dependency_links.txt
 SELDOMpy.egg-info/requires.txt
 SELDOMpy.egg-info/top_level.txt
```

### Comparing `SELDOMpy-0.0.1.2/setup_seldompy.py` & `SELDOMpy-0.0.1.3/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.1.2'
+VERSION = '0.0.1.3'
 DESCRIPTION = 'Package for modelling cellular signalling networks'
 readme = open("README.md", "r")
 # Configurando
 setup(
     # el nombre debe coincidir con el nombre de la carpeta
     # 'modulomuysimple'
     name="SELDOMpy",
```


# Comparing `tmp/sleepeeg-0.3.0.tar.gz` & `tmp/sleepeeg-0.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sleepeeg-0.3.0.tar", last modified: Sat Jun 24 13:04:15 2023, max compression
+gzip compressed data, was "sleepeeg-0.3.1.tar", last modified: Wed Jun 28 12:55:18 2023, max compression
```

## Comparing `sleepeeg-0.3.0.tar` & `sleepeeg-0.3.1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-24 13:04:15.672348 sleepeeg-0.3.0/
--rw-rw-rw-   0        0        0     1088 2023-03-20 20:54:05.000000 sleepeeg-0.3.0/LICENSE
--rw-rw-rw-   0        0        0     1728 2023-06-24 13:04:15.671350 sleepeeg-0.3.0/PKG-INFO
--rw-rw-rw-   0        0        0     1306 2023-06-09 12:52:22.000000 sleepeeg-0.3.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-24 13:04:15.643424 sleepeeg-0.3.0/docs/
--rw-rw-rw-   0        0        0     2433 2023-06-24 10:09:30.000000 sleepeeg-0.3.0/docs/conf.py
--rw-rw-rw-   0        0        0      839 2023-06-24 12:45:44.000000 sleepeeg-0.3.0/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-24 13:04:15.673344 sleepeeg-0.3.0/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-24 13:04:15.651403 sleepeeg-0.3.0/sleepeeg/
--rw-rw-rw-   0        0        0    48299 2023-06-24 12:09:58.000000 sleepeeg-0.3.0/sleepeeg/base.py
--rw-rw-rw-   0        0        0    12311 2023-06-24 12:39:28.000000 sleepeeg-0.3.0/sleepeeg/dashboard.py
--rw-rw-rw-   0        0        0    28327 2023-06-24 12:51:40.000000 sleepeeg-0.3.0/sleepeeg/pipeline.py
--rw-rw-rw-   0        0        0     2005 2023-06-24 08:52:40.000000 sleepeeg-0.3.0/sleepeeg/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-24 13:04:15.669355 sleepeeg-0.3.0/sleepeeg.egg-info/
--rw-rw-rw-   0        0        0     1728 2023-06-24 13:04:15.000000 sleepeeg-0.3.0/sleepeeg.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      282 2023-06-24 13:04:15.000000 sleepeeg-0.3.0/sleepeeg.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-24 13:04:15.000000 sleepeeg-0.3.0/sleepeeg.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      118 2023-06-24 13:04:15.000000 sleepeeg-0.3.0/sleepeeg.egg-info/requires.txt
--rw-rw-rw-   0        0        0       19 2023-06-24 13:04:15.000000 sleepeeg-0.3.0/sleepeeg.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 12:55:18.991817 sleepeeg-0.3.1/
+-rw-rw-rw-   0        0        0     1088 2023-03-20 20:54:05.000000 sleepeeg-0.3.1/LICENSE
+-rw-rw-rw-   0        0        0     1728 2023-06-28 12:55:18.990816 sleepeeg-0.3.1/PKG-INFO
+-rw-rw-rw-   0        0        0     1306 2023-06-09 12:52:22.000000 sleepeeg-0.3.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:55:18.955908 sleepeeg-0.3.1/docs/
+-rw-rw-rw-   0        0        0     2433 2023-06-24 10:09:30.000000 sleepeeg-0.3.1/docs/conf.py
+-rw-rw-rw-   0        0        0      839 2023-06-28 12:52:35.000000 sleepeeg-0.3.1/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:55:18.992811 sleepeeg-0.3.1/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 12:55:18.970869 sleepeeg-0.3.1/sleepeeg/
+-rw-rw-rw-   0        0        0    48389 2023-06-28 12:51:11.000000 sleepeeg-0.3.1/sleepeeg/base.py
+-rw-rw-rw-   0        0        0    12311 2023-06-24 12:39:28.000000 sleepeeg-0.3.1/sleepeeg/dashboard.py
+-rw-rw-rw-   0        0        0    28327 2023-06-24 12:51:40.000000 sleepeeg-0.3.1/sleepeeg/pipeline.py
+-rw-rw-rw-   0        0        0     2005 2023-06-24 08:52:40.000000 sleepeeg-0.3.1/sleepeeg/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:55:18.988821 sleepeeg-0.3.1/sleepeeg.egg-info/
+-rw-rw-rw-   0        0        0     1728 2023-06-28 12:55:18.000000 sleepeeg-0.3.1/sleepeeg.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      282 2023-06-28 12:55:18.000000 sleepeeg-0.3.1/sleepeeg.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:55:18.000000 sleepeeg-0.3.1/sleepeeg.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      118 2023-06-28 12:55:18.000000 sleepeeg-0.3.1/sleepeeg.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       19 2023-06-28 12:55:18.000000 sleepeeg-0.3.1/sleepeeg.egg-info/top_level.txt
```

### Comparing `sleepeeg-0.3.0/LICENSE` & `sleepeeg-0.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `sleepeeg-0.3.0/PKG-INFO` & `sleepeeg-0.3.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sleepeeg
-Version: 0.3.0
+Version: 0.3.1
 Summary: Sleep EEG preprocessing and analysis
 Author-email: Gennadiy Belonosov <gennadiyb@mail.tau.ac.il>
 License: MIT
 Project-URL: Homepage, https://github.com/NirLab-TAU/sleepeeg
 Project-URL: Documentation, https://nirlab-tau.github.io/sleepeeg/
 Keywords: sleep,eeg
 Requires-Python: >=3.10
```

### Comparing `sleepeeg-0.3.0/README.md` & `sleepeeg-0.3.1/README.md`

 * *Files identical despite different names*

### Comparing `sleepeeg-0.3.0/docs/conf.py` & `sleepeeg-0.3.1/docs/conf.py`

 * *Files identical despite different names*

### Comparing `sleepeeg-0.3.0/pyproject.toml` & `sleepeeg-0.3.1/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 build-backend = "setuptools.build_meta"
 
 [tool.setuptools.packages.find]
 exclude = ["notebooks"]  # empty by default
 
 [project]
 name = "sleepeeg"
-version = "0.3.0"
+version = "0.3.1"
 authors = [
     {name = "Gennadiy Belonosov", email = "gennadiyb@mail.tau.ac.il"},
 ]
 description = "Sleep EEG preprocessing and analysis"
 readme = "README.md"
 requires-python = ">=3.10"
 license = {text = "MIT"}
```

### Comparing `sleepeeg-0.3.0/sleepeeg/base.py` & `sleepeeg-0.3.1/sleepeeg/base.py`

 * *Files 0% similar despite different names*

```diff
@@ -997,14 +997,15 @@
             )[0],
             axis=1,
         ).sum(axis=1)
 
         self._plot_topomap(
             data=psds,
             axis=axis,
+            info=self.psds[stage].info,
             topomap_args=topomap_args,
             cbar_args=cbar_args,
         )
 
         if is_new_axis:
             fig.suptitle(f"{stage} ({b[0]}-{b[1]} Hz)")
         if save and is_new_axis:
@@ -1119,14 +1120,15 @@
                     topomap_args["vlim"][0] = perc_low[band_key]
                 if high_percentile:
                     topomap_args["vlim"][1] = perc_high[band_key]
 
                 self._plot_topomap(
                     data=psds_per_stage_per_band[row_index, col_index],
                     axis=axes[col_index],
+                    info=self.psds[stage].info,
                     topomap_args=topomap_args,
                     cbar_args=cbar_args,
                 )
                 axes[col_index].set_title(
                     f"{band_key} ({bands[band_key][0]}-{bands[band_key][1]} Hz)"
                 )
```

### Comparing `sleepeeg-0.3.0/sleepeeg/dashboard.py` & `sleepeeg-0.3.1/sleepeeg/dashboard.py`

 * *Files identical despite different names*

### Comparing `sleepeeg-0.3.0/sleepeeg/pipeline.py` & `sleepeeg-0.3.1/sleepeeg/pipeline.py`

 * *Files identical despite different names*

### Comparing `sleepeeg-0.3.0/sleepeeg/utils.py` & `sleepeeg-0.3.1/sleepeeg/utils.py`

 * *Files identical despite different names*

### Comparing `sleepeeg-0.3.0/sleepeeg.egg-info/PKG-INFO` & `sleepeeg-0.3.1/sleepeeg.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sleepeeg
-Version: 0.3.0
+Version: 0.3.1
 Summary: Sleep EEG preprocessing and analysis
 Author-email: Gennadiy Belonosov <gennadiyb@mail.tau.ac.il>
 License: MIT
 Project-URL: Homepage, https://github.com/NirLab-TAU/sleepeeg
 Project-URL: Documentation, https://nirlab-tau.github.io/sleepeeg/
 Keywords: sleep,eeg
 Requires-Python: >=3.10
```


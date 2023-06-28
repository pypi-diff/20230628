# Comparing `tmp/domino-composite-0.273.tar.gz` & `tmp/domino-composite-0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "domino-composite-0.273.tar", last modified: Thu Jun 22 14:50:09 2023, max compression
+gzip compressed data, was "domino-composite-0.3.tar", last modified: Wed Jun 28 12:14:20 2023, max compression
```

## Comparing `domino-composite-0.273.tar` & `domino-composite-0.3.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-22 14:50:09.374956 domino-composite-0.273/
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     1719 2023-06-22 14:50:09.374956 domino-composite-0.273/PKG-INFO
-drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-22 14:50:09.362956 domino-composite-0.273/domino/
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2022-11-23 14:01:08.000000 domino-composite-0.273/domino/__init__.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     1034 2023-06-19 15:18:52.000000 domino-composite-0.273/domino/agg.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2702 2022-11-23 14:10:17.000000 domino-composite-0.273/domino/categorical_analysis.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    50731 2023-06-19 15:18:52.000000 domino-composite-0.273/domino/core.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4248 2023-01-30 10:05:05.000000 domino-composite-0.273/domino/deseasonaliser.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     3870 2023-06-20 12:38:32.000000 domino-composite-0.273/domino/filtering.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4784 2023-04-03 16:12:11.000000 domino-composite-0.273/domino/plsr.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    14070 2023-04-12 16:04:19.000000 domino-composite-0.273/domino/prediction.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     5814 2023-06-19 15:18:52.000000 domino-composite-0.273/domino/util.py
-drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-22 14:50:09.374956 domino-composite-0.273/domino_composite.egg-info/
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     1719 2023-06-22 14:50:09.000000 domino-composite-0.273/domino_composite.egg-info/PKG-INFO
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      382 2023-06-22 14:50:09.000000 domino-composite-0.273/domino_composite.egg-info/SOURCES.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        1 2023-06-22 14:50:09.000000 domino-composite-0.273/domino_composite.egg-info/dependency_links.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2023-06-22 14:50:09.000000 domino-composite-0.273/domino_composite.egg-info/requires.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        7 2023-06-22 14:50:09.000000 domino-composite-0.273/domino_composite.egg-info/top_level.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       38 2023-06-22 14:50:09.374956 domino-composite-0.273/setup.cfg
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      728 2023-06-22 14:49:41.000000 domino-composite-0.273/setup.py
+drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 12:14:20.805783 domino-composite-0.3/
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2224 2023-06-28 12:14:20.805783 domino-composite-0.3/PKG-INFO
+drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 12:14:20.805783 domino-composite-0.3/domino/
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2022-11-23 14:01:08.000000 domino-composite-0.3/domino/__init__.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     1034 2023-06-19 15:18:52.000000 domino-composite-0.3/domino/agg.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2702 2022-11-23 14:10:17.000000 domino-composite-0.3/domino/categorical_analysis.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    50731 2023-06-19 15:18:52.000000 domino-composite-0.3/domino/core.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4248 2023-01-30 10:05:05.000000 domino-composite-0.3/domino/deseasonaliser.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     3850 2023-06-28 11:12:03.000000 domino-composite-0.3/domino/filtering.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4784 2023-04-03 16:12:11.000000 domino-composite-0.3/domino/plsr.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    14070 2023-04-12 16:04:19.000000 domino-composite-0.3/domino/prediction.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     5814 2023-06-19 15:18:52.000000 domino-composite-0.3/domino/util.py
+drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 12:14:20.805783 domino-composite-0.3/domino_composite.egg-info/
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2224 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/PKG-INFO
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      382 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/SOURCES.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        1 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/dependency_links.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/requires.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        7 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/top_level.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       38 2023-06-28 12:14:20.805783 domino-composite-0.3/setup.cfg
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      726 2023-06-28 12:14:00.000000 domino-composite-0.3/setup.py
```

### Comparing `domino-composite-0.273/PKG-INFO` & `domino-composite-0.3/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,36 +1,38 @@
 Metadata-Version: 2.1
 Name: domino-composite
-Version: 0.273
+Version: 0.3
 Summary: A package for compositing atmospheric datasets
 Home-page: https://github.com/joshdorrington/domino
 Author: Josh Dorrington
 Author-email: joshua.dorrington@kit.edu
 License: bsd-3-clause
 Description-Content-Type: text/markdown
 
 # Domino is a package for analysing composites of atmospheric data.
 ## Based on xarray, Domino makes it easy to calculate lagged composites of fields and scalar indices around categorical event time series, and to compute bootstrapped confidence bounds. This is still an alpha release! While core functionality is stable, there could be some bugs!
 
+![title](Imgs/domino_logo.png)
+
+
 ## Documentation
 
-See our API reference here: https://github.com/joshdorrington/domino/blob/master/docbuild/domino-composite.pdf
+See our [API reference](https://github.com/joshdorrington/domino/blob/master/docbuild/domino-composite.pdf) for a full description of all functionality.
+
+[//]: # (Our preprint on Domino (under consideration at QJRMS), and its application to extreme rainfall prediction can be found [here](where))
 
 ## Examples
 
 See our Jupyter notebook examples for more detailed discussion of how to apply Domino to different use cases.
 
 Our [basic](https://github.com/joshdorrington/domino/blob/master/examples/basic_compositing.ipynb) and [advanced](https://github.com/joshdorrington/domino/blob/master/examples/advanced_compositing.ipynb) compositing guides cover the use of Domino's flexible LaggedAnalyser class to easily compute time-lagged composites and apply bootstrap significance tests to them.
 
-Producing filtered precursor patterns from composites, and computing precursor activity indices from those is covered in our [IndexGenerator](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb) guide.
+Producing filtered precursor patterns from composites, and computing precursor activity indices from those, is covered in our [Index_Computation guide](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb), while an introduction to assessing the predictive power of indices is in the [Index_Predictability guide](https://github.com/joshdorrington/domino/blob/master/examples/Index_predictability.ipynb).
 
 
 ## Install
 
 domino can be installed using pip:
 ```
-python -m pip install "domino-composite==0.272"
-```
-If you want to run the worked examples in the Jupyter notebooks you will need:
-```
-TO BE DECIDED
+python -m pip install domino-composite
 ```
+If you want to run the worked examples in the Jupyter notebooks you will need to download the [netcdf files containing example data](https://github.com/joshdorrington/domino/releases/tag/v1-data).
```

### Comparing `domino-composite-0.273/domino/agg.py` & `domino-composite-0.3/domino/agg.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino/categorical_analysis.py` & `domino-composite-0.3/domino/categorical_analysis.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino/core.py` & `domino-composite-0.3/domino/core.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino/deseasonaliser.py` & `domino-composite-0.3/domino/deseasonaliser.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino/filtering.py` & `domino-composite-0.3/domino/filtering.py`

 * *Files 1% similar despite different names*

```diff
@@ -69,15 +69,14 @@
     connected,ncon=label(grid)
     connected=connected.astype(float)
     ix,n=np.unique(connected,return_counts=True)
     
     connected_da=xr.DataArray(connected,coords=area.coords)
     ix_areas=np.array([area.where(connected_da==i).sum().values\
               for i in ix])
-    print(ix_areas)
     for m in ix[ix_areas<area_thresh]:
         connected[connected==m]=0
     return connected>0
 
 
 def da_large_regions(da,n,dims,area_based=False):
```

### Comparing `domino-composite-0.273/domino/plsr.py` & `domino-composite-0.3/domino/plsr.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino/prediction.py` & `domino-composite-0.3/domino/prediction.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino/util.py` & `domino-composite-0.3/domino/util.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.273/domino_composite.egg-info/PKG-INFO` & `domino-composite-0.3/domino_composite.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,36 +1,38 @@
 Metadata-Version: 2.1
 Name: domino-composite
-Version: 0.273
+Version: 0.3
 Summary: A package for compositing atmospheric datasets
 Home-page: https://github.com/joshdorrington/domino
 Author: Josh Dorrington
 Author-email: joshua.dorrington@kit.edu
 License: bsd-3-clause
 Description-Content-Type: text/markdown
 
 # Domino is a package for analysing composites of atmospheric data.
 ## Based on xarray, Domino makes it easy to calculate lagged composites of fields and scalar indices around categorical event time series, and to compute bootstrapped confidence bounds. This is still an alpha release! While core functionality is stable, there could be some bugs!
 
+![title](Imgs/domino_logo.png)
+
+
 ## Documentation
 
-See our API reference here: https://github.com/joshdorrington/domino/blob/master/docbuild/domino-composite.pdf
+See our [API reference](https://github.com/joshdorrington/domino/blob/master/docbuild/domino-composite.pdf) for a full description of all functionality.
+
+[//]: # (Our preprint on Domino (under consideration at QJRMS), and its application to extreme rainfall prediction can be found [here](where))
 
 ## Examples
 
 See our Jupyter notebook examples for more detailed discussion of how to apply Domino to different use cases.
 
 Our [basic](https://github.com/joshdorrington/domino/blob/master/examples/basic_compositing.ipynb) and [advanced](https://github.com/joshdorrington/domino/blob/master/examples/advanced_compositing.ipynb) compositing guides cover the use of Domino's flexible LaggedAnalyser class to easily compute time-lagged composites and apply bootstrap significance tests to them.
 
-Producing filtered precursor patterns from composites, and computing precursor activity indices from those is covered in our [IndexGenerator](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb) guide.
+Producing filtered precursor patterns from composites, and computing precursor activity indices from those, is covered in our [Index_Computation guide](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb), while an introduction to assessing the predictive power of indices is in the [Index_Predictability guide](https://github.com/joshdorrington/domino/blob/master/examples/Index_predictability.ipynb).
 
 
 ## Install
 
 domino can be installed using pip:
 ```
-python -m pip install "domino-composite==0.272"
-```
-If you want to run the worked examples in the Jupyter notebooks you will need:
-```
-TO BE DECIDED
+python -m pip install domino-composite
 ```
+If you want to run the worked examples in the Jupyter notebooks you will need to download the [netcdf files containing example data](https://github.com/joshdorrington/domino/releases/tag/v1-data).
```

### Comparing `domino-composite-0.273/setup.py` & `domino-composite-0.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("/data/ox5324/Domino/readme.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name='domino-composite',
-    version='0.273',
+    version='0.3',
     author='Josh Dorrington',
     author_email='joshua.dorrington@kit.edu',
     description='A package for compositing atmospheric datasets',
     long_description=long_description,
     long_description_content_type="text/markdown",
     url='https://github.com/joshdorrington/domino',
     license='bsd-3-clause',
```


# Comparing `tmp/domino-composite-0.3.tar.gz` & `tmp/domino-composite-0.31.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "domino-composite-0.3.tar", last modified: Wed Jun 28 12:14:20 2023, max compression
+gzip compressed data, was "domino-composite-0.31.tar", last modified: Wed Jun 28 13:57:05 2023, max compression
```

## Comparing `domino-composite-0.3.tar` & `domino-composite-0.31.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 12:14:20.805783 domino-composite-0.3/
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2224 2023-06-28 12:14:20.805783 domino-composite-0.3/PKG-INFO
-drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 12:14:20.805783 domino-composite-0.3/domino/
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2022-11-23 14:01:08.000000 domino-composite-0.3/domino/__init__.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     1034 2023-06-19 15:18:52.000000 domino-composite-0.3/domino/agg.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2702 2022-11-23 14:10:17.000000 domino-composite-0.3/domino/categorical_analysis.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    50731 2023-06-19 15:18:52.000000 domino-composite-0.3/domino/core.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4248 2023-01-30 10:05:05.000000 domino-composite-0.3/domino/deseasonaliser.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     3850 2023-06-28 11:12:03.000000 domino-composite-0.3/domino/filtering.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4784 2023-04-03 16:12:11.000000 domino-composite-0.3/domino/plsr.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    14070 2023-04-12 16:04:19.000000 domino-composite-0.3/domino/prediction.py
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     5814 2023-06-19 15:18:52.000000 domino-composite-0.3/domino/util.py
-drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 12:14:20.805783 domino-composite-0.3/domino_composite.egg-info/
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2224 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/PKG-INFO
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      382 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/SOURCES.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        1 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/dependency_links.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/requires.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        7 2023-06-28 12:14:20.000000 domino-composite-0.3/domino_composite.egg-info/top_level.txt
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       38 2023-06-28 12:14:20.805783 domino-composite-0.3/setup.cfg
--rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      726 2023-06-28 12:14:00.000000 domino-composite-0.3/setup.py
+drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 13:57:05.289451 domino-composite-0.31/
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2332 2023-06-28 13:57:05.289451 domino-composite-0.31/PKG-INFO
+drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 13:57:05.289451 domino-composite-0.31/domino/
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      832 2023-06-28 13:50:59.000000 domino-composite-0.31/domino/__init__.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     1034 2023-06-19 15:18:52.000000 domino-composite-0.31/domino/agg.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2702 2022-11-23 14:10:17.000000 domino-composite-0.31/domino/categorical_analysis.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    51187 2023-06-28 13:27:01.000000 domino-composite-0.31/domino/core.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     5491 2023-06-28 13:32:47.000000 domino-composite-0.31/domino/deseasonaliser.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     3850 2023-06-28 11:12:03.000000 domino-composite-0.31/domino/filtering.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     4929 2023-06-28 13:43:05.000000 domino-composite-0.31/domino/plsr.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)    15026 2023-06-28 13:41:55.000000 domino-composite-0.31/domino/prediction.py
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     5814 2023-06-28 12:42:20.000000 domino-composite-0.31/domino/util.py
+drwxr-xr-x   0 ox5324   (243050) imk-tro  (44470)        0 2023-06-28 13:57:05.289451 domino-composite-0.31/domino_composite.egg-info/
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)     2332 2023-06-28 13:57:05.000000 domino-composite-0.31/domino_composite.egg-info/PKG-INFO
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      382 2023-06-28 13:57:05.000000 domino-composite-0.31/domino_composite.egg-info/SOURCES.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        1 2023-06-28 13:57:05.000000 domino-composite-0.31/domino_composite.egg-info/dependency_links.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       62 2023-06-28 13:57:05.000000 domino-composite-0.31/domino_composite.egg-info/requires.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)        7 2023-06-28 13:57:05.000000 domino-composite-0.31/domino_composite.egg-info/top_level.txt
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)       38 2023-06-28 13:57:05.289451 domino-composite-0.31/setup.cfg
+-rw-r--r--   0 ox5324   (243050) imk-tro  (44470)      727 2023-06-28 13:57:00.000000 domino-composite-0.31/setup.py
```

### Comparing `domino-composite-0.3/PKG-INFO` & `domino-composite-0.31/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,36 +1,38 @@
 Metadata-Version: 2.1
 Name: domino-composite
-Version: 0.3
+Version: 0.31
 Summary: A package for compositing atmospheric datasets
 Home-page: https://github.com/joshdorrington/domino
 Author: Josh Dorrington
 Author-email: joshua.dorrington@kit.edu
 License: bsd-3-clause
 Description-Content-Type: text/markdown
 
 # Domino is a package for analysing composites of atmospheric data.
-## Based on xarray, Domino makes it easy to calculate lagged composites of fields and scalar indices around categorical event time series, and to compute bootstrapped confidence bounds. This is still an alpha release! While core functionality is stable, there could be some bugs!
+## Based on xarray, Domino makes it easy to calculate lagged composites of fields and scalar indices around categorical event time series, and to compute bootstrapped confidence bounds.
 
-![title](Imgs/domino_logo.png)
+## This is a beta release. While core functionality is stable, there may be some bugs: please contact me at joshua.dorrington@kit.edu if you encounter unexpected behaviour.
+
+<img src="Imgs/domino_logo.png" alt="logo" width="180"/>
 
 
 ## Documentation
 
 See our [API reference](https://github.com/joshdorrington/domino/blob/master/docbuild/domino-composite.pdf) for a full description of all functionality.
 
-[//]: # (Our preprint on Domino (under consideration at QJRMS), and its application to extreme rainfall prediction can be found [here](where))
+<!-- (Our preprint on Domino (under consideration at QJRMS), and its application to extreme rainfall prediction can be found [here](where)) -->
 
 ## Examples
 
 See our Jupyter notebook examples for more detailed discussion of how to apply Domino to different use cases.
 
 Our [basic](https://github.com/joshdorrington/domino/blob/master/examples/basic_compositing.ipynb) and [advanced](https://github.com/joshdorrington/domino/blob/master/examples/advanced_compositing.ipynb) compositing guides cover the use of Domino's flexible LaggedAnalyser class to easily compute time-lagged composites and apply bootstrap significance tests to them.
 
-Producing filtered precursor patterns from composites, and computing precursor activity indices from those, is covered in our [Index_Computation guide](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb), while an introduction to assessing the predictive power of indices is in the [Index_Predictability guide](https://github.com/joshdorrington/domino/blob/master/examples/Index_predictability.ipynb).
+Producing filtered precursor patterns from composites, and computing precursor activity indices from those, is covered in our [Index_Computation guide](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb), while an introduction to assessing the predictive power of indices is in the [Index_Predictability guide](https://github.com/joshdorrington/domino/blob/master/examples/Index_Predictability.ipynb).
 
 
 ## Install
 
 domino can be installed using pip:
 ```
 python -m pip install domino-composite
```

### Comparing `domino-composite-0.3/domino/agg.py` & `domino-composite-0.31/domino/agg.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.3/domino/categorical_analysis.py` & `domino-composite-0.31/domino/categorical_analysis.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.3/domino/core.py` & `domino-composite-0.31/domino/core.py`

 * *Files 3% similar despite different names*

```diff
@@ -11,45 +11,59 @@
 from domino.util import holm_bonferroni_correction, split_to_contiguous, is_time_type, make_all_dims_coords, drop_scalar_coords, squeeze_da,offset_time_dim
 from domino.filtering import ds_large_regions, convolve_pad_ds
 from domino.deseasonaliser import Agg_Deseasonaliser
 
 class LaggedAnalyser(object):
     """Computes lagged composites of variables with respect to a categorical categorical event series, with support for bootstrap resampling to provide a non-parametric assessment of composite significance, and for deseasonalisation of variables.
     
-        **Arguments:**
+    **Arguments:**
         
-        *event*
-            An xarray.DataArray with one dimension taking on categorical values, each defining a class of event (or non-event).
+    *event*
             
-        **Optional arguments**
+    An xarray.DataArray with one dimension taking on categorical values, each defining a class of event (or non-event).
+            
+    **Optional arguments**
         
-        *variables, name, is_categorical*
+    *variables, name, is_categorical*
         
-            Arguments for adding variables to the LaggedAnalyser. Identical behaviour to calling add_variables directly.
-"""
+    Arguments for adding variables to the LaggedAnalyser. Identical behaviour to calling *LaggedAnalyser.add_variables* directly.
+    """
+    
     def __init__(self,event,variables=None,name=None,is_categorical=None):
+        """Initialise a new LaggedAnalyser object."""
+        
+        #: event is a dataarray
+        self.event=xr.DataArray(event)#: This is a docstring?
+        """@private"""
         
-        #event is a dataarray
-        self.event=xr.DataArray(event)
         #variables are stored in a dataset, and can be added later,
         #or passed as a DataArray, a Dataset or as a dict of DataArrays
         self.variables=xr.Dataset(coords=event.coords)
+        """@private"""
+
         if variables is not None:
             self.add_variable(variables,name,is_categorical,False)
             
         #Time lagged versions of the dataset self.variables will be stored here, with a key
         #equal to the lag applied. Designed to be accessed by the self.lagged_variables function
         self._lagged_variables={}
         self.lagged_means=None
+        """@private"""
+
         #variables that are a linear combination of other variables are more efficiently
         #computed after compositing using the self.add_derived_composite method
         self._derived_variables={}
-        self.deseasonalisers_={}
+        self._deseasonalisers={}
+        
         self.composite_mask=None
+        """@private"""
+
         self.boot_indices=None
+        """@private"""
+
         return
     
     def __repr__(self):
         l1='A LaggedAnalyser object\n'
         l2='event:\n\n'
         da_string=self.event.__str__().split('\n')[0]
         l3='\n\nvariables:\n\n'
@@ -67,39 +81,44 @@
 
     def add_variable(self,variables,name=None,is_categorical=None,overwrite=False,join_type='outer'):
         """Adds an additional variable to LaggedAnalyser.variables.
         
         **Arguments**
         
         *variables* 
-            An xarray.DataArray, xarray.Dataset or dictionary of xarray.DataArrays, containing data to be composited with respect to *event*. One of the coordinates of *variables* should have the same name as the coordinate of *events*. Stored internally as an xarray.Dataset. If a dictionary is passed, the DataArrays are joined according to the method *join_type* which defaults to 'outer'.
+        
+        An xarray.DataArray, xarray.Dataset or dictionary of xarray.DataArrays, containing data to be composited with respect to *event*. One of the coordinates of *variables* should have the same name as the coordinate of *events*. Stored internally as an xarray.Dataset. If a dictionary is passed, the DataArrays are joined according to the method *join_type* which defaults to 'outer'.
             
         **Optional Arguments**
         
         *name* 
-            A string. If *variables* is a single xarray.DataArray then *name* will be used as the name of the array in the LaggedAnalyser.variables DataArray. Otherwise ignored.
+        
+        A string. If *variables* is a single xarray.DataArray then *name* will be used as the name of the array in the LaggedAnalyser.variables DataArray. Otherwise ignored.
         
         *is_categorical* 
-            An integer, if *variables* is an xarray.DataArray, or else a dictionary of integers with keys corresponding to DataArrays in the xarray.Dataset/dictionary. 0 indicates that the variable is continuous, and 1 indicates that it is categorical. Note that continuous and categorical variables are by default composited differently (see LaggedAnalyser.compute_composites). Default assumption is all DataArrays are continuous, unless a DataAarray contains an 'is_categorical' key in its DataArray.attrs, in which case this value is used.
+        
+        An integer, if *variables* is an xarray.DataArray, or else a dictionary of integers with keys corresponding to DataArrays in the xarray.Dataset/dictionary. 0 indicates that the variable is continuous, and 1 indicates that it is categorical. Note that continuous and categorical variables are by default composited differently (see LaggedAnalyser.compute_composites). Default assumption is all DataArrays are continuous, unless a DataAarray contains an 'is_categorical' key in its DataArray.attrs, in which case this value is used.
             
         *overwrite*
-            A boolean. If False then attempts to assign a variable who's name is already in *LaggedAnalyser.variables* will raise a ValueError
+        
+        A boolean. If False then attempts to assign a variable who's name is already in *LaggedAnalyser.variables* will raise a ValueError
         
         *join_type*
-            A string setting the rules for how differences in the coordinate indices of different variables are handled:
-            “outer”: use the union of object indexes
-            “inner”: use the intersection of object indexes
+        
+        A string setting the rules for how differences in the coordinate indices of different variables are handled:
+        “outer”: use the union of object indexes
+        “inner”: use the intersection of object indexes
 
-            “left”: use indexes from the pre-existing *LaggedAnalyser.variables* with each dimension
+        “left”: use indexes from the pre-existing *LaggedAnalyser.variables* with each dimension
 
-            “right”: use indexes from the new *variables* with each dimension
+        “right”: use indexes from the new *variables* with each dimension
 
-            “exact”: instead of aligning, raise ValueError when indexes to be aligned are not equal
+        “exact”: instead of aligning, raise ValueError when indexes to be aligned are not equal
 
-            “override”: if indexes are of same size, rewrite indexes to be those of the pre-existing *LaggedAnalyser.variables*. Indexes for the same dimension must have the same size in all objects.
+        “override”: if indexes are of same size, rewrite indexes to be those of the pre-existing *LaggedAnalyser.variables*. Indexes for the same dimension must have the same size in all objects.
         """
         if isinstance(variables,dict):
             
             if is_categorical is None:
                 is_categorical={v:None for v in variables}
                 
             [self._add_variable(da,v,is_categorical[v],overwrite,join_type) for v,da in variables.items()]
@@ -164,29 +183,34 @@
         
     def lag_variables(self,offsets,offset_unit='days',offset_dim='time',mode='any',overwrite=False):
         """Produces time lags of *LaggedAnalyser.variables*, which can be used to produce lagged composites.
         
         **Arguments**
         
         *offsets*
-            An iterable of integers which represent time lags at which to lag *LaggedAnalyser.variables* in the units specified by *offset_unit*. Positive offsets denote variables *preceding* the event.
+        
+        An iterable of integers which represent time lags at which to lag *LaggedAnalyser.variables* in the units specified by *offset_unit*. Positive offsets denote variables *preceding* the event.
             
         **Optional arguments**
         
         *offset_unit*
-            A string, defining the units of *offsets*. Valid options are weeks, days, hours, minutes, seconds, milliseconds, and microseconds.
+        
+        A string, defining the units of *offsets*. Valid options are weeks, days, hours, minutes, seconds, milliseconds, and microseconds.
             
         *offset_dim*
-            A string, defining the coordinate of *LaggedAnalyser.variables* along which offsets are to be calculated.
+        
+        A string, defining the coordinate of *LaggedAnalyser.variables* along which offsets are to be calculated.
             
         *mode*
-            One of 'any', 'past', or 'future'. If 'past' or 'future' is used then only positive or negative lags are valid, respectively.
+        
+        One of 'any', 'past', or 'future'. If 'past' or 'future' is used then only positive or negative lags are valid, respectively.
             
         *overwrite*
-            A boolean. If False, then attempts to produce a lag which already exist will raise a ValueError.
+        
+        A boolean. If False, then attempts to produce a lag which already exist will raise a ValueError.
         
         """
         time_type=int(is_time_type(self.variables[offset_dim][0].values))
         self.offset_unit=offset_unit
         lag_funcs=[self._ilag_variables,self._lag_variables]
         offsets=np.atleast_1d(offsets)
         for o in offsets:
@@ -271,33 +295,40 @@
         
         """
         Partitions *LaggedAnalyser.variables*, and any time-lagged equivalents, into subsets depending on the value of *LaggedAnalyser.event*, and then computes a bulk summary metric for each.
 
         **Optional arguments**
         
         *dim*
-            A string, the coordinate along which to compute composites.
+        
+        A string, the coordinate along which to compute composites.
             
         *lag_vals*
-            Either 'All', or a list of integers, denoting the time lags for which composites should be computed.
+        
+        Either 'All', or a list of integers, denoting the time lags for which composites should be computed.
             
         *as_anomaly*
-            A Boolean, defining whether composites should be given as absolute values or differences from the unpartitioned value.
+        
+        A Boolean, defining whether composites should be given as absolute values or differences from the unpartitioned value.
             
         *con_func*
-            The summary metric to use for continuous variables. Defaults to a standard mean average. If None, then continuous variables will be ignored
+        
+        The summary metric to use for continuous variables. Defaults to a standard mean average. If None, then continuous variables will be ignored
             
         *cat_func*
-            The summary metric to use for categorical variables. Defaults to the occurrence probability of each categorical value. If None, then categorical variables will be ignored
+        
+        The summary metric to use for categorical variables. Defaults to the occurrence probability of each categorical value. If None, then categorical variables will be ignored
             
         *inplace*
-            A boolean, defining whether the composite should be stored in *LaggedAnalyser.composites*
+    
+        A boolean, defining whether the composite should be stored in *LaggedAnalyser.composites*
         
         **returns**
-            An xarray.Dataset like  *LaggedAnalyser.variables* but summarised according to *con_func* and *cat_func*, and with an additional coordinate *index_val*, which indexes over the values taken by *LaggedAnalyser.event*.
+        
+        An xarray.Dataset like  *LaggedAnalyser.variables* but summarised according to *con_func* and *cat_func*, and with an additional coordinate *index_val*, which indexes over the values taken by *LaggedAnalyser.event*.
             
         """
         composite=self._compute_aggregate_over_lags(self.event,dim,lag_vals,con_func,cat_func)
         lagged_means=self.aggregate_variables(dim,lag_vals,con_func,cat_func)
 
         if as_anomaly:
             composite=composite-lagged_means
@@ -316,51 +347,59 @@
     def aggregate_variables(self,dim='time',lag_vals='all',con_func=agg.mean_ds,cat_func=agg.cat_occ_ds):
         
         """Calculates a summary metric from *LaggedAnalyser.variables* at all points where *LaggedAnalyser.event* is defined, regardless of its value.
         
         **Optional arguments**
         
         *dim*
-            A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*.
+        
+        A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*.
         
         *lag_vals*
-            'all' or a iterable of integers, specifying for which lag values to compute the summary metric.
+        
+        'all' or a iterable of integers, specifying for which lag values to compute the summary metric.
         
         *con_func*
-            The summary metric to use for continuous variables. Defaults to a standard mean average. If None, then continuous variables will be ignored
+        
+        The summary metric to use for continuous variables. Defaults to a standard mean average. If None, then continuous variables will be ignored
             
         *cat_func*
-            The summary metric to use for categorical variables. Defaults to the occurrence probability of each categorical value. If None, then continuous variables will be ignored
+        
+        The summary metric to use for categorical variables. Defaults to the occurrence probability of each categorical value. If None, then continuous variables will be ignored
 
         **returns**
         
-            An xarray.Dataset like  *LaggedAnalyser.variables* but summarised according to *con_func* and *cat_func*.
+        An xarray.Dataset like  *LaggedAnalyser.variables* but summarised according to *con_func* and *cat_func*.
 
 """
         fake_event=self.event.copy(data=np.zeros_like(self.event))
         return self._compute_aggregate_over_lags(fake_event,dim,lag_vals,con_func,cat_func).isel(index_val=0)
 
     def add_derived_composite(self,name,func,composite_vars,as_anomaly=False):
         """Applies *func* to one or multiple composites to calculate composites of derived quantities, and additionally, stores *func* to allow derived bootstrap composites to be calculated. For linear quantities, where Ex[f(x)]==f(Ex[x]), then this can minimise redundant memory use.
         
         **Arguments**
         
         *name*
-            A string, providing the name of the new variable to add.
+        
+        A string, providing the name of the new variable to add.
             
         *func*
-            A callable which must take 1 or more xarray.DataArrays as inputs
+        
+         A callable which must take 1 or more xarray.DataArrays as inputs
             
         *composite_vars*
-            An iterable of strings, of the same length as the number of arguments taken by *func*. Each string must be the name of a variable in *LaggedAnalyser.variables* which will be passed into *func* in order.
+        
+        An iterable of strings, of the same length as the number of arguments taken by *func*. Each string must be the name of a variable in *LaggedAnalyser.variables* which will be passed into *func* in order.
         
         **Optional arguments**
         
         *as_anomaly*
-            A boolean. Whether anomaly composites or full composites should be passed in to func.
+        
+        A boolean. Whether anomaly composites or full composites should be passed in to func.
         """
         
         if np.ndim(as_anomaly)==1:
             raise(NotImplementedError('variable-specific anomalies not yet implemented'))
 
         self._derived_variables[name]=(func,composite_vars,as_anomaly)
         self.composites[name]=self._compute_derived_da(self.composites,func,composite_vars,as_anomaly)
@@ -376,44 +415,58 @@
     def compute_bootstraps(self,bootnum,dim='time',con_func=agg.mean_ds,cat_func=agg.cat_occ_ds,lag=0,synth_mode='markov',data_vars=None,reuse_ixs=False):
         
         """Computes composites from synthetic event indices, which can be used to assess whether composites are insignificant.
         
         **Arguments**
         
         *bootnum*
-            An integer, the number of bootstrapped composites to compute
+        
+        An integer, the number of bootstrapped composites to compute
             
         **Optional arguments**
         
         *dim*
-            A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*.
+        
+        A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*.
             
         *con_func*
-            The summary metric to use for continuous variables. Defaults to a standard mean average. If None, then continuous variables will be ignored
+        
+        The summary metric to use for continuous variables. Defaults to a standard mean average. If None, then continuous variables will be ignored
             
         *cat_func*
-            The summary metric to use for categorical variables. Defaults to the occurrence probability of each categorical value. If None, then continuous variables will be ignored
+        
+        The summary metric to use for categorical variables. Defaults to the occurrence probability of each categorical value. If None, then continuous variables will be ignored
 
         *lag*
-            An integer, specifying which lagged variables to use for the bootstraps. i.e. bootstraps for lag=90 will be from a completely different season than those for lag=0.
+        
+        An integer, specifying which lagged variables to use for the bootstraps. i.e. bootstraps for lag=90 will be from a completely different season than those for lag=0.
             
         *synth_mode*
-            A string, specifying how synthetic event indices are to be computed. Valid options are:
-            
-            "random": categorical values are randomly chosen with the same probability of occurrence as those found in *LaggedAnalyser.event*, but with no autocorrelation.
-            
-            "markov": A first order Markov chain is fitted to *LaggedAnalyser.event*, producing some autocorrelation and state dependence in the synthetic series. Generally a better approximation than "random" and so should normally be used.
+        
+        A string, specifying how synthetic event indices are to be computed. Valid options are:
             
-            "shuffle": The values are randomly reordered. This means that each value will occur exactly the same amount of times as in the original index, and so is ideal for particularly rare events or short series.
+        "random": 
+        
+        categorical values are randomly chosen with the same probability of occurrence as those found in *LaggedAnalyser.event*, but with no autocorrelation.
+
+        "markov": 
+        
+        A first order Markov chain is fitted to *LaggedAnalyser.event*, producing some autocorrelation and state dependence in the synthetic series. Generally a better approximation than "random" and so should normally be used.
+
+        "shuffle": 
+        
+        The values are randomly reordered. This means that each value will occur exactly the same amount of times as in the original index, and so is ideal for particularly rare events or short series.
             
         *data_vars*
-            An iterable of strings, specifying for which variables bootstraps should be computed.
+        
+        An iterable of strings, specifying for which variables bootstraps should be computed.
                 
         **returns**
-            An xarray.Dataset like *LaggedAnalyser.variables* but summarised according to *con_func* and *cat_func*, and with a new coordinate 'bootnum' of length *bootnum*.
+        
+        An xarray.Dataset like *LaggedAnalyser.variables* but summarised according to *con_func* and *cat_func*, and with a new coordinate 'bootnum' of length *bootnum*.
 
         """
         if data_vars==None:
             data_vars=list(self.variables.data_vars)
 
         boots=self._add_derived_boots(self._compute_bootstraps(bootnum,dim,con_func,cat_func,lag,synth_mode,data_vars,reuse_ixs))
         if self.composites_are_anomaly:
@@ -488,32 +541,38 @@
     
     def get_significance(self,bootstraps,comp,p,data_vars=None,hb_correction=False):
         
         """Computes whether a composite is significant with respect to a given distribution of bootstrapped composites. 
         
         **Arguments**
         
-            *bootstraps*
-                An xarray.Dataset with a coordinate 'bootnum', such as produced by *LaggedAnalyser.compute_bootstraps*
-                
-            *comp*
-                An xarray Dataset of the same shape as *bootstraps* but without a 'bootnum' coordinate. Missing or additional variables are allowed, and are simply ignored.
-            *p*
-                A float, specifying the p-value of the 2-sided significance test (values in the range 0 to 1). 
+        *bootstraps*
+
+        An xarray.Dataset with a coordinate 'bootnum', such as produced by *LaggedAnalyser.compute_bootstraps*
+
+        *comp*
+
+        An xarray Dataset of the same shape as *bootstraps* but without a 'bootnum' coordinate. Missing or additional variables are allowed, and are simply ignored.
+        *p*
+
+        A float, specifying the p-value of the 2-sided significance test (values in the range 0 to 1). 
             
         **Optional arguments**
 
         *data_vars*
-            An iterable of strings, specifying for which variables significance should be computed.
+            
+        An iterable of strings, specifying for which variables significance should be computed.
             
         *hb_correction*
-            A Boolean, specifying whether a Holm-Bonferroni correction should be applied to *p*, in order to reduce the family-wide error rate. Note that this correction is currently only applied to each variable in *comp* independently, and so will have no impact on scalar variables.
+        
+        A Boolean, specifying whether a Holm-Bonferroni correction should be applied to *p*, in order to reduce the family-wide error rate. Note that this correction is currently only applied to each variable in *comp* independently, and so will have no impact on scalar variables.
         
         **returns**
-            An xarray.Dataset like *comp* but with boolean data, specifying whether each feature of each variable passed the significance test.
+        
+        An xarray.Dataset like *comp* but with boolean data, specifying whether each feature of each variable passed the significance test.
         """
         if data_vars==None:
             data_vars=list(bootstraps.data_vars)
 
         bootnum=len(bootstraps.boot_num)
         comp=comp[data_vars]
         bootstraps=bootstraps[data_vars]
@@ -530,43 +589,48 @@
         self.composite_sigs=pval_ds.assign_coords(lag=comp.lag)
         return self.composite_sigs
     
     def bootstrap_significance(self,bootnum,p,dim='time',synth_mode='markov',reuse_lag0_boots=False,data_vars=None,hb_correction=False):
         
         """A wrapper around *compute_bootstraps* and *get_significance*, that calculates bootstraps and applies a significance test to a number of time lagged composites simulataneously.
         
-        **Arguments**
-        
-        *bootnum*
-            An integer, the number of bootstrapped composites to compute
-            
-        *p*
-            A float, specifying the p-value of the 2-sided significance test (values in the range 0 to 1). 
+    **Arguments**
 
-        **Optional arguments**
-    
-        *dim*
-            A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*.
-            
-        *synth_mode*
-            A string, specifying how synthetic event indices are to be computed. Valid options are:
-            "random": categorical values are randomly chosen with the same probability of occurrence as those found in *LaggedAnalyser.event*, but with no autocorrelation.
-            'markov': A first order Markov chain is fitted to *LaggedAnalyser.event*, producing some autocorrelation and state dependence in the synthetic series. Generally a better approximation than "random" and so should normally be used.
+    *bootnum*
 
-        *reuse_lag0_boots*
-            A Boolean. If True, bootstraps are only computed for lag=0, and then used as a null distribution to assess all lagged composites. For variables which are approximately stationary across the lag timescale, then this is a good approximation and can increase performance. However if used incorrectly, it may lead to 'significant composites' which simply reflect the seasonal cycle. if False, separate bootstraps are computed for all time lags.
-            
-        *data_vars*
-            An iterable of strings, specifying for which variables significance should be computed.
-        
-        *hb_correction*
-            A Boolean, specifying whether a Holm-Bonferroni correction should be applied to *p*, in order to reduce the family-wide error rate. Note that this correction is currently only applied to each variable in *comp* independently, and so will have no impact on scalar variables.
+    An integer, the number of bootstrapped composites to compute
+
+    *p*
+
+    A float, specifying the p-value of the 2-sided significance test (values in the range 0 to 1). 
+
+    **Optional arguments**
+
+    *dim*
+
+    A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*.
+
+    *synth_mode*
+
+    A string, specifying how synthetic event indices are to be computed. Valid options are:
+    "random": categorical values are randomly chosen with the same probability of occurrence as those found in *LaggedAnalyser.event*, but with no autocorrelation.
+    'markov': A first order Markov chain is fitted to *LaggedAnalyser.event*, producing some autocorrelation and state dependence in the synthetic series. Generally a better approximation than "random" and so should normally be used.
+
+    *reuse_lag0_boots*
+        A Boolean. If True, bootstraps are only computed for lag=0, and then used as a null distribution to assess all lagged composites. For variables which are approximately stationary across the lag timescale, then this is a good approximation and can increase performance. However if used incorrectly, it may lead to 'significant composites' which simply reflect the seasonal cycle. if False, separate bootstraps are computed for all time lags.
+
+    *data_vars*
+        An iterable of strings, specifying for which variables significance should be computed.
+
+    *hb_correction*
+        A Boolean, specifying whether a Holm-Bonferroni correction should be applied to *p*, in order to reduce the family-wide error rate. Note that this correction is currently only applied to each variable in *comp* independently, and so will have no impact on scalar variables.
         
-        **returns**
-            An xarray.Dataset like *LaggedAnalyser.variables* but with the *dim* dimension summarised according to *con_func* and *cat_func*, an additional *lag* coordinate, and with boolean data specifying whether each feature of each variable passed the significance test.
+    **returns**
+
+    An xarray.Dataset like *LaggedAnalyser.variables* but with the *dim* dimension summarised according to *con_func* and *cat_func*, an additional *lag* coordinate, and with boolean data specifying whether each feature of each variable passed the significance test.
 
         """
         lag_vals=list(self._lagged_variables)
         
         con_func,cat_func=self.composite_func
         
         boots=self.compute_bootstraps(bootnum,dim,con_func,cat_func,0,synth_mode,data_vars)
@@ -584,27 +648,32 @@
     
     def deseasonalise_variables(self,variable_list=None,dim='time',agg='dayofyear',smooth=1,coeffs=None):
         """Computes a seasonal cycle for each variable in *LaggedAnalyser.variables* and subtracts it inplace, turning *LaggedAnalyser.variables* into deseasonalised anomalies. The seasonal cycle is computed via temporal aggregation of each variable over a given period - by default the calendar day of the year. This cycle can then be smoothed with an n-point rolling average.
 
                 **Optional arguments**
 
                 *variable_list*
-                    A list of variables to deseasonalise. Defaults to all variables in the *LaggedAnalyser.variables*
+                
+                A list of variables to deseasonalise. Defaults to all variables in the *LaggedAnalyser.variables*
 
                 *dim*
-                    A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*, along which the seasonal cycle is computed. Currently, only timelike coordinates are supported.
+                
+                A string, the name of the shared coordinate between *LaggedAnalyser.variables* and *LaggedAnalyser.event*, along which the seasonal cycle is computed. Currently, only timelike coordinates are supported.
                 
                 *agg*
-                    A string specifying the datetime-like field to aggregate over. Useful and supported values are 'season', 'month', 'weekofyear', and 'dayofyear'
+                
+                A string specifying the datetime-like field to aggregate over. Useful and supported values are 'season', 'month', 'weekofyear', and 'dayofyear'
                     
                 *smooth*
-                    An integer, specifying the size of the n-timestep centred rolling mean applied to the aggregated seasonal cycle. By default *smooth*=1 results in no smoothing.
+                
+                An integer, specifying the size of the n-timestep centred rolling mean applied to the aggregated seasonal cycle. By default *smooth*=1 results in no smoothing.
 
                 *coeffs*
-                    A Dataset containing a precomputed seasonal cycle, which, if *LaggedAnalyser.variables* has coordinates (*dim*,[X,Y,...,Z]), has coords (*agg*,[X,Y,...,Z]), and has the same data variables as *LaggedAnalyser.variables*. If *coeffs* is provided, no seasonal cycle is fitted to *LaggedAnalyser.variables*, *coeffs* is used instead.
+                
+                A Dataset containing a precomputed seasonal cycle, which, if *LaggedAnalyser.variables* has coordinates (*dim*,[X,Y,...,Z]), has coords (*agg*,[X,Y,...,Z]), and has the same data variables as *LaggedAnalyser.variables*. If *coeffs* is provided, no seasonal cycle is fitted to *LaggedAnalyser.variables*, *coeffs* is used instead.
 
         """        
 
         if variable_list is None:
             variable_list=list(self.variables)
         for var in variable_list:
             da=self.variables[var]
@@ -613,44 +682,44 @@
                 dsnlsr.fit_cycle(da,dim=dim,agg=agg)
             else:
                 dsnslr.cycle_coeffs=coeffs[var]
 
             cycle=dsnlsr.evaluate_cycle(data=da[dim],smooth=smooth)
             self.variables[var]=da.copy(data=da.data-cycle.data)
             dsnlsr.data=None #Prevents excess memory storage
-            self.deseasonalisers_[var]=dsnlsr
+            self._deseasonalisers[var]=dsnlsr
         return   
     
     def get_seasonal_cycle_coeffs(self):
         """ Retrieve seasonal cycle coeffs computed with *LaggedAnalyser.deseasonalise_variables*, suitable for passing into *coeffs* in other *LaggedAnalyser.deseasonalise_variables* function calls as a precomputed cycle.
         
         **Returns**
         An xarray.Dataset, as specified in  the *LaggedAnalyser.deseasonalise_variables* *coeff* optional keyword.
         """
-        coeffs=xr.Dataset({v:dsnlsr.cycle_coeffs for v,dsnlsr in self.deseasonalisers_.items()})
+        coeffs=xr.Dataset({v:dsnlsr.cycle_coeffs for v,dsnlsr in self._deseasonalisers.items()})
         return coeffs
 
     #If deseasonalise_variables has been called, then this func can be used to compute the
     #seasonal mean state corresponding to a given composite. This mean state+ the composite
     # produced by self.compute_composites gives the full field composite pattern.
     def get_composite_seasonal_mean(self):
         """
         If *LaggedAnalyser.deseasonalise_variables* has been called, then this function returns the seasonal mean state corresponding to a given composite, given by a sum of the seasonal cycle weighted by the time-varying occurrence of each categorical value in *LaggedAnalyser.events*. This mean state + the deseasonalised anomaly composite
     produced by *LaggedAnalyser.compute_composites* then retrieves the full composite pattern.
     
-        **Returns**
-            An xarray.Dataset containing the composite seasonal mean values.
+    **Returns**
+        An xarray.Dataset containing the composite seasonal mean values.
         """
-        variable_list=list(self.deseasonalisers_)
+        variable_list=list(self._deseasonalisers)
         ts={e:self.event[self.event==e].time for e in np.unique(self.event)}
         lags=np.unique([0,*list(self._lagged_variables)])
         
         mean_states={}
         for var in variable_list:
-            dsnlsr=self.deseasonalisers_[var]
+            dsnlsr=self._deseasonalisers[var]
             agg=dsnlsr.agg
             mean_states[var]=xr.concat([\
                                  xr.concat([\
                                     self._lag_average_cycle(dsnlsr,agg,l,t,i)\
                                 for l in lags],'lag')\
                             for i,t in ts.items()],'index_val')
             
@@ -664,28 +733,35 @@
         cycle_mean=cycle_eval.mean(agg).assign_coords({'lag':l,'index_val':i})
         return cycle_mean
     
 class PatternFilter(object):
     """Provides filtering methods to refine n-dimensional boolean masks, and apply them to an underlying dataset.
     
         **Optional arguments:**
+        
         *mask_ds*
-            An xarray boolean Dataset of arbitrary dimensions which provides the initial mask dataset. If *mask_ds*=None  and *analyser*=None, then *mask_ds* will be initialised as a Dataset of the same dimensions and data_vars as *val_ds*, with all values = 1 (i.e. initially unmasked). 
+        
+        An xarray boolean Dataset of arbitrary dimensions which provides the initial mask dataset. If *mask_ds*=None  and *analyser*=None, then *mask_ds* will be initialised as a Dataset of the same dimensions and data_vars as *val_ds*, with all values = 1 (i.e. initially unmasked). 
         
         *val_ds*
-            An xarray Dataset with the same dimensions as *mask_ds* if provided, otherwise arbitrary, consisting of an underlying dataset to which the mask is applied. If *val_ds*=None and *analyser*=None, then *PatternFilter.apply_value_mask* will raise an Error
+        
+        An xarray Dataset with the same dimensions as *mask_ds* if provided, otherwise arbitrary, consisting of an underlying dataset to which the mask is applied. If *val_ds*=None and *analyser*=None, then *PatternFilter.apply_value_mask* will raise an Error
             
         *analyser*
-            An instance of a  core.LaggedAnalyser class for which both composites and significance masks have been computed, used to infer the *val_ds* and *mask_ds* arguments respectively. This overrides any values passed explicitly to  *mask_ds* and *val_ds*.
+        
+        An instance of a  core.LaggedAnalyser class for which both composites and significance masks have been computed, used to infer the *val_ds* and *mask_ds* arguments respectively. This overrides any values passed explicitly to  *mask_ds* and *val_ds*.
             
     """
     def __init__(self,mask_ds=None,val_ds=None,analyser=None):
-        
+        """Initialise a new PatternFilter object"""
         self.mask_ds=mask_ds
+        """@private"""
         self.val_ds=val_ds
+        """@private"""
+
         if analyser is not None:
             self._parse_analyser(analyser)
             
         else:
             if mask_ds is None:
                 self.mask_ds=self._mask_ds_like_val_ds()
                 
@@ -707,91 +783,105 @@
         y=x.where(x!=0).fillna(1) #replace nans and 0s with 1
         y=(y/y).astype(int) #make everything 1 via division and assert integer type.
         self.mask_ds=y
         return
     
     def update_mask(self,new_mask,mode):
         """ Update *PatternFilter.mask_ds* with a new mask, either taking their union or intersection, or replacing the current mask with new_mask.
+        
         **Arguments**
         
-            *new_mask*
-            An xarray.Dataset with the same coords and variables as *PatternFilter.mask_ds*.
-            
-            *mode*
-            A string, one of 'replace','intersection' or 'union', defining how *new_mask* should be used to update the mask.
+        *new_mask*
+
+        An xarray.Dataset with the same coords and variables as *PatternFilter.mask_ds*.
+
+        *mode*
+
+        A string, one of 'replace','intersection' or 'union', defining how *new_mask* should be used to update the mask.
         """
         new_mask=new_mask.astype(int)
         if mode=='replace':
             self.mask_ds=new_mask
         elif mode=='intersection':
             self.mask_ds=self.mask_ds*new_mask
         elif mode == 'union':
             self.mask_ds=self.mask_ds|new_mask
         else:
             raise(ValueError(f'Invalid mode, {mode}'))
         return
                   
     def apply_value_mask(self,truth_function,*args,mode='intersection'):
         """ Apply a filter to *PatternFilter.mask_ds* based on a user-specified truth function which is applied to *PatternFilter.val_ds. 
-                **Examples**
-                    #Mask values beneath a threshold:
-                    def larger_than_thresh(ds,thresh):
-                        return ds>thresh
-                    patternfilter.apply_value_mask(is_positive,thresh)
-
-                    #Mask values where absolute value is less than a reference field:
-                    def amp_greater_than_reference(ds,ref_ds):
-                        return np.abs(ds)>ref_ds
-                    pattern_filter.apply_value_mask(amp_greater_than_reference,ref_ds)
+        
+        **Examples**
+        
+            #Mask values beneath a threshold:
+            def larger_than_thresh(ds,thresh):
+                return ds>thresh
+            patternfilter.apply_value_mask(is_positive,thresh)
+
+            #Mask values where absolute value is less than a reference field:
+            def amp_greater_than_reference(ds,ref_ds):
+                return np.abs(ds)>ref_ds
+            pattern_filter.apply_value_mask(amp_greater_than_reference,ref_ds)
 
-                **Arguments**
+        **Arguments**
 
-                    *truth_function*
-                    A function with inputs (val_ds,*args) that returns a boolean dataset with the same coords and data variables as *PatternFilter.val_ds*.
+        *truth_function*
+        
+        A function with inputs (val_ds,*args) that returns a boolean dataset with the same coords and data variables as *PatternFilter.val_ds*.
 
-                **Optional arguments**
-                    *mode*
-                    A string, one of 'replace','intersection' or 'union', defining how the value filter should be used to update the *PatternFilter.mask_ds*.
+        **Optional arguments**
+        
+        *mode*
+            
+        A string, one of 'replace','intersection' or 'union', defining how the value filter should be used to update the *PatternFilter.mask_ds*.
         """        
         if self.val_ds is None:
             raise(ValueError('val_ds must be provided to apply value mask.'))
         value_mask=truth_function(self.val_ds,*args)
         self.update_mask(value_mask,mode)
         return
     
     def apply_area_mask(self,n,dims=None,mode='intersection',area_type='gridpoint'):
         """ Apply a filter to *PatternFilter.mask_ds* that identifies connected groups of True values within a subspace of the Dataset's dimensions specified by *dims*, and masks out groups which are beneath a threshold size *n*. This is done through the application of *scipy.ndimage.label* using the default structuring element (https://docs.scipy.org/doc/scipy/reference/generated/scipy.ndimage.label.html). 
     
         When *area_type*='gridpoint', *n* specifies the number of connected datapoints within each connected region. For the special case where *dims* consists of a latitude- and longitude-like coordinate, area_type='spherical' applies a cosine-latitude weighting, such that *n* can be interpreted as a measure of area, where a datapoint with lat=0 would have area 1. 
         
         **Examples**
+        
             #Keep groups of True values consisting of an area >=30 square equatorial gridpoints
             patternfilter.apply_area_mask(30,dims=('lat','lon'),area_type='spherical')
             
             #Keep groups of True values that are consistent for at least 3 neighbouring time lags
             patternfilter.apply_area_mask(3,dims=('time'))
             
             #Keep groups of true values consisting of >=10 longitudinal values, or >=30 values in longitude and altitude if the variables have an altitude coord:
             patternfilter.apply_area_mask(10,dims=('longitude'))
             patternfilter.apply_area_mask(30,dims=('longitude,altitude'),mode='union')
 
         **Arguments**
 
-            *n*
-            A scalar indicating the minimum size of an unmasked group, in terms of number of gridpoints (for *area_type*=gridpoint) or the weighted area (for *area_type*=spherical), beneath which the group will be masked.
+        *n*
+            
+        A scalar indicating the minimum size of an unmasked group, in terms of number of gridpoints (for *area_type*=gridpoint) or the weighted area (for *area_type*=spherical), beneath which the group will be masked.
 
         **Optional arguments**
-            *dims*
-            An iterable of strings specifying coords in *PatternFilter.mask_ds* which define the subspace in which groups of connected True values are identified. Other dims will be iterated over. DataArrays within *PatternFilter.mask_ds* that do not contain all the *dims* will be ignored. If *dims*=None, all dims in each DataArray will be used.
+        
+        *dims*
             
-            *mode*
-            A string, one of 'replace','intersection' or 'union', defining how the area filter should be used to update the *PatternFilter.mask_ds*.
+        An iterable of strings specifying coords in *PatternFilter.mask_ds* which define the subspace in which groups of connected True values are identified. Other dims will be iterated over. DataArrays within *PatternFilter.mask_ds* that do not contain all the *dims* will be ignored. If *dims*=None, all dims in each DataArray will be used.
+            
+        *mode*
+
+        A string, one of 'replace','intersection' or 'union', defining how the area filter should be used to update the *PatternFilter.mask_ds*.
             
-            *area_type*
-            A string, one of 'gridpoint' or 'spherical' as specified above. 'spherical' is currently only supported for len-2 *dims* kwargs, with the first assumed to be latitude-like. 
+        *area_type*
+
+        A string, one of 'gridpoint' or 'spherical' as specified above. 'spherical' is currently only supported for len-2 *dims* kwargs, with the first assumed to be latitude-like. 
             
         """        
         if area_type=='gridpoint':
             area_based=False
         elif area_type=='spherical':
             area_based=True
         else:
@@ -801,22 +891,26 @@
         return
     
     
     def apply_convolution(self,n,dims,mode='replace'):
         """ Apply a square n-point convolution filter to *PatternFilter.mask_ds* in one or two dimensions specified by *dims*, iterated over remaining dimensions. This has the effect of extending the unmasked regions and smoothing the mask overall.
         
         **Arguments**
-            *n*
-            A positive integer specifying the size of the convolution filter. *n*=1 leaves the mask unchanged. Even *n* are asymmetric and shifted right. 
-            
-            *dims*
-            A length 1 or 2 iterable of strings specifying the dims in which the convolution is applied. Other dims will be iterated over. DataArrays within *PatternFilter.mask_ds* that do not contain all the *dims* will be ignored. 
+        
+        *n*
             
-            *mode*
-            A string, one of 'replace','intersection' or 'union', defining how the area filter should be used to update the *PatternFilter.mask_ds*.
+        A positive integer specifying the size of the convolution filter. *n*=1 leaves the mask unchanged. Even *n* are asymmetric and shifted right. 
+
+        *dims*
+
+        A length 1 or 2 iterable of strings specifying the dims in which the convolution is applied. Other dims will be iterated over. DataArrays within *PatternFilter.mask_ds* that do not contain all the *dims* will be ignored. 
+
+        *mode*
+
+        A string, one of 'replace','intersection' or 'union', defining how the area filter should be used to update the *PatternFilter.mask_ds*.
         """
         
         if not len(dims) in [1,2]:
             raise(ValueError('Only 1 and 2D dims currently supported'))
             
         convolution=convolve_pad_ds(self.mask_ds,n,dims=dims)
         self.update_mask(convolution,mode)
@@ -830,22 +924,27 @@
         return self.mask_ds
     
     def filter(self,ds=None,drop_empty=True,fill_val=np.nan):
         """ Apply the current mask to *ds* or to *PatternFilter.val_ds* (if *ds* is None), replacing masked gridpoints with *fill_val*.
         **Optional arguments**
         
         *ds*
+        
         An xarray.Dataset to apply the mask to. Should have the same coords and data_vars as *PatternFilter.mask_ds*. If None, the mask is applied to *PatternFilter.val_ds*.
         
         *drop_empty*
+        
         A boolean value. If True, then completely masked variables are dropped from the returned masked Dataset.
+        
         *fill_val*
+        
         A scalar that defaults to np.nan. The value with which masked gridpoints in the Dataset are replaced.
         
         **Returns**
+        
         A Dataset with masked values replaced by *fill_val*.
         """
         if ds is None:
             ds=self.val_ds.copy(deep=True)
             
         ds=ds.where(self.mask_ds)
         if drop_empty:
@@ -872,31 +971,38 @@
         self._rename_function=_DEFAULT_RENAME_FUNC
         
     def __repr__(self):
         return 'An IndexGenerator object'
         
     def __str__(self):
             return self.__repr__
-        
+    
+    
     def centre(self,x,dim='time',ref=None):
+        """@private"""
+
         if ref is None:
             ref=x.mean(dim=dim)
         return x-ref
     
     def normalise(self,x,dim='time',ref=None):
+        """@private"""
+
         if ref is None:
             ref=x.std(dim=dim)
         return x/ref
     
     def standardise(self,x,dim='time',mean_ref=None,std_ref=None):
+        """@private"""
         centred_x=self.centre(x,dim,mean_ref)
         standardised_x=self.normalise(centred_x,dim,std_ref)
         return standardised_x
         
     def collapse_index(self,ix,dims):
+        """@private"""
         lat_coords=['lat','latitude','grid_latitude']
         if not np.any(np.isin(lat_coords,dims)):
             return ix.sum(dims)
         
         else:
             #assumes only one lat coord: seems safe.
             lat_dim=lat_coords[np.where(np.isin(lat_coords,dims))[0][0]]
@@ -908,39 +1014,47 @@
         
         **Arguments**
         
         *pattern_ds*
         
         An xarray.Dataset of patterns to project onto with arbitrary dimensions.
         
-        series_ds*
+        *series_ds*
         
         An xarray.Dataset of variables to project onto the patterns. Coordinates of *series_ds* once subsetted using *slices* must match the dimensions of *pattern_ds* + the extra coord *dim*.
+        
         **Optional arguments**
         
         *dim*:
+        
         A string specifying the remaining coord of the scalar indices. Defaults to 'time', which should be the choice for most use cases.
         
         *slices*
+        
         A dictionary or iterable of dictionaries, each specifying a subset of *pattern_ds* to take before computing an index, with one index returned for each dictionary and for each variable. Subsetting is based on the *xr.Dataset.sel* method: e.g. *slices*=[dict(lag=0,index_val=1)] will produce 1 set of indices based on pattern_ds.sel(lag=0,index_val=1). If *slices*=None, no subsets are computed.
         
         *ix_means*
+        
         If None, the mean of each index is calculated and subtracted, resulting in centred indices. Otherwise, *ix_means* should be a dictionary of index names and predefined mean values which are subtracted instead. Of most use for online computations, updating a precomputed index in a new dataset.
         
         *ix_stds*
+        
         If None, the standard deviation of each index is calculated and is divided by, resulting in standardised indices. Otherwise, *ix_stds* should be a dictionary of index names and predefined std values which are divided by instead. Of most use for online computations, updating a precomputed index in a new dataset.
 
         *drop_blank*
+        
         A boolean. If True, drop indices where the corresponding pattern is entirely blank. If False, returns an all np.nan time series.
         *in_place*
         
         *strict_metadata*
+        
         If False, indices will be merged into a common dataset regardless of metadata. If True, nonmatching metadata will raise a ValueError.
         
         **Returns
+        
         An xarray.Dataset of indices with a single coordinate (*dim*).
         """
         #Parse inputs
         
         if slices is None:
             self.slices=[{}]
         elif type(slices) is dict:
```

### Comparing `domino-composite-0.3/domino/deseasonaliser.py` & `domino-composite-0.31/domino/deseasonaliser.py`

 * *Files 20% similar despite different names*

```diff
@@ -6,46 +6,80 @@
 import os
 from domino.util import xarr_times_to_ints
 
 class Agg_Deseasonaliser(object):
     """
     Computes a seasonal cycle from an xarray dataset based on an aggregation
     criteria i.e. month, day of year, week of year etc.
-    ----------
-    Methods
-    -------
-    fit_cycle(DataArray,dim=str,agg=str): Aggregates the input DataArray arr.
-
-    evaluate_cycle(data=DataArray): When data is None, creates a seasonal cycle
-    DataArray the same shape as the input data used in fit_cycle. data can be
-    a DataArray with a differing dim coordinate, but matching other coordinates.
-    This can be used to fit a seasonal cycle on one dataset, but evaluate it on
-    another, as long as the grid, levels, etc are the same.
-    Returns The seasonal cycle as a DataArray
+    
     """
     def __init__(self):
+        
         self.data=None
+        """@private"""
+        
         self.cycle_coeffs=None
-
+        """@private"""
 
     def fit_cycle(self,arr,dim="time",agg="dayofyear"):
+        """
+        Computes a seasonal cycle for *arr* by aggregating over the coordinate *dim* and then taking the mean. Default functionality is to compute the average by day of year.
+        Seasonal cycle coefficients are stored in self.cycle_coeffs
+        
+        **Arguments**
+        
+        *arr*
+        
+        An xarray.DataArray for which a seasonal cycle is to be computed.
+        
+        **Optional Arguments**
+        
+        *dim*
+        
+        Defaults to 'time': the time-like dimension of *arr* along which the seasonal cycle is to be computed. Values of the coordinate must be a Pandas.DatetimeIndex.
+        
+        *agg*
+        
+        Defaults to 'dayofyear': The time parameter along which aggregation will be carried out. This can be any valid string which specifies a property of Pandas.DatetimeIndex. Likely alternate choices are 'month','day' and 'quarter'.
+        
+        
+        """
         var=dim+"."+agg
         self.data=arr
         self.dim=dim
         self.agg=agg
         self.cycle_coeffs=arr.groupby(var).mean(dim=dim)
         return
 
     def evaluate_cycle(self,data=None,smooth=1):
+        
+        """
+        
+        When data is None, creates a seasonal cycle DataArray the same shape as the input data used in fit_cycle.
+        data can be a DataArray with a differing dim coordinate, but matching other coordinates. 
+        This can be used to fit a seasonal cycle on one dataset, but evaluate it on  another, as long as the grid, levels, etc are the same.
+        Returns The seasonal cycle as a DataArray A centred rolling mean can be optionally applied to the cycle.
+        
+        **Optional Arguments**
+        
+        *data*
+        
+        An xarray.DataArray or Dataset with a time coordinate with the same name as the *arr* used in fit_cycle.
+        
+        *smooth*
+        
+        An integer specifying the width of the rolling mean to apply in terms of timesteps. No checks are made that timesteps are evenly spaced!
+        """
         if data is None:
             data=self.data
         cycle=self.cycle_coeffs.sel({self.agg:getattr(data[self.dim].dt,self.agg).data})
         return self.smooth(cycle,smooth)
     
     def smooth(self,arr,w):
+        """@private"""
         if w==1:
             return arr
         else:
             return arr.rolling({self.agg:w},min_periods=1,center=True).mean()
         
 class Agg_FlexiDeseasonaliser(Agg_Deseasonaliser):
     """Modifies Agg_Deseasonaliser, with the ability
@@ -64,23 +98,15 @@
     
 class Sinefit_Deseasonaliser(Agg_Deseasonaliser):
 
     """
     Same functionalityy as Agg_Deseasonaliser but fits a number of sin modes
     to the data using least squares fitting. This produces a smoother cycle than
     aggregating but can be slow for large datasets.
-    ----------
-    Methods
-    -------
-    fit_cycle(DataArray,dim=str,N=int,period=float): N sets the number of sin modes
-    to fit as fractions of the period. i.e. the default of N=4 fits waves with
-    periods of period, period/2, period/3 and period/4. period is a float setting
-    the length of a year in days.
-
-    evaluate_cycle(data=DataArray): As for Agg_Deseasonaliser
+    
     """
     def _func_residual(self,p,x,t,N,period):
         return x - self._evaluate_fit(t,p,N,period)
 
     def _evaluate_fit(self,t,p,N,period):
         ans=p[1]
         for i in range(0,N):
@@ -94,31 +120,33 @@
         p=np.zeros(2*(N+1))
         for i in range(0,N):
             p[2+2*i]=std/(i+1.0)
         plsq=leastsq(self._func_residual,p,args=(arr,t,N,period))
         return plsq[0]
 
     def fit_cycle(self,arr,dim="time",N=4,period=365.25):
-
-            dims=arr.dims
-            self.dim=dim
-            self.data=arr
-            self.N=N
-            self.period=period
-            t=xarr_times_to_ints(arr[dim])
-            self.coeffs= xr.apply_ufunc(
-                self._lstsq_sine_fit,
-                arr,
-                input_core_dims=[[dim]],
-                output_core_dims=[["coeffs"]],
-                vectorize=True,
-                kwargs={"t":t,"N":N,"period":period})
-            return
+        """N sets the number of sine modes to fit as fractions of the period. i.e. the default of N=4 fits waves with periods of period, period/2, period/3 and period/4. period is a float setting the length of a year in days.
+        """
+        dims=arr.dims
+        self.dim=dim
+        self.data=arr
+        self.N=N
+        self.period=period
+        t=xarr_times_to_ints(arr[dim])
+        self.coeffs= xr.apply_ufunc(
+            self._lstsq_sine_fit,
+            arr,
+            input_core_dims=[[dim]],
+            output_core_dims=[["coeffs"]],
+            vectorize=True,
+            kwargs={"t":t,"N":N,"period":period})
+        return
 
     def evaluate_cycle(self,data=None):
+        """As for Agg_Deseasonaliser but without the option for further smoothing."""
         if data is None:
             data=self.data
         dims=data.dims
         t=xarr_times_to_ints(data[self.dim])
         print(self.coeffs.shape)
         cycle=np.array([[self._evaluate_fit(t,c2.data,self.N,self.period)\
                 for c2 in c1] for c1 in np.atleast_3d(self.coeffs)])
```

### Comparing `domino-composite-0.3/domino/filtering.py` & `domino-composite-0.31/domino/filtering.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.3/domino/plsr.py` & `domino-composite-0.31/domino/plsr.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,23 +1,26 @@
 import numpy as np
 import xarray as xr
 import sklearn.cross_decomposition as skcc
 
 class PLSR_Reduction(object):
     """
     Wraps around the scikit-learn partial-least-squares-regression algorithm, supporting prediction-focused dimensionality reduction.
+    
     **Arguments**
     
     *mode_num*
+    
     An integer number of PLSR modes to retain. Defaults to the second dimension of the predictor variables *X* passed to *PLSR_Reduction.fit*
     
     """    
     def __init__(self,mode_num):
-        
+        """Initialise a PLSR_Reduction object"""
         self.mode_num=mode_num
+        """@private"""
         return
     
     def __repr__(self):
         return 'A PLSR_Reduction object'
     
     def __str__(self):
         return self.__repr__()
@@ -41,27 +44,31 @@
     def fit(self,X,y,sample_dim='time'):
         """ 
         Performs the partial-least-squares regression of *X* against *y*, returning the transformed PLSR modes.
         
         **Arguments**
     
         *X*
+        
         The predictor variables to transform. An xarray.Datarray with two coordinates representing the sample and feature dimensions as specified by *sample_dim*.
         
         *y*
+        
         The target variables to be predicted. An xarray.Datarray with two coordinates representing the sample and feature dimensions as specified by *sample_dim*.
         
         **Optional arguments**
         
         *sample_dim*
+        
         A string specifying the sample dimension which must be shared between *X* and *y*. Defaults to *time*.
         
         **Returns**
         
         *plsr_X*
+        
         A DataArray containing PLSR modes, with a sample coordinate given by the intersection of the sample coordinates of *X* and *y*
 
         """
         X,y=xr.align(X.dropna(sample_dim),y.dropna(sample_dim))
         assert len(y>1)
         self.sample_dim=sample_dim
         self.X=self._validate_shape(X)
@@ -92,19 +99,21 @@
         Use precomputed rotation matrix from calling *PLSR_Reduction.fit* to project *X* into the space of PLSR modes.
         This can be used to extend the PLSR modes to times when the target events are not defined.
         
         **Arguments**
         
         
         *X*
+        
         The predictor variables to transform. An xarray.Datarray with two coordinates representing the sample and feature dimensions as specified by the *sample_dim* used to fit the PLSR regression.
         
         **Returns**
         
         *proj_plsr_X*
+        
         A DataArray containing projected PLSR modes, with the same sample coordinate as *X*.
         
         """       
         
         #PLSR_projection
         
         X=self._validate_shape(X)
@@ -119,19 +128,21 @@
         """ 
         Compute the patterns corresponding to each PLSR mode, by computing a weighted sum of the spatial patterns corresponding to the predictor indices used to fit the partial least squares regression.
 
         **Arguments**
         
         
         *X*
+        
         The pattern to transform. An xarray.Datarray of arbitrary shape, and with an identical feature coordinate to the predictor variables passed into *PLSR_Reduction.fit*.
         
         **Returns**
         
         *pattern*
+        
         A DataArray containing the resulting weighted sums, with the same coordinates as *X*, except for the feature coordinate is replaced with the PLSR_mode coordinate.
         """
         assert self.feature_dim in X.dims
         pattern=(self.rotation_da*X).sum(self.feature_dim)
         return pattern
```

### Comparing `domino-composite-0.3/domino/prediction.py` & `domino-composite-0.31/domino/prediction.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,32 +1,34 @@
 import numpy as np
 import xarray as xr
 from sklearn.linear_model import LogisticRegression
 from sklearn.metrics import roc_auc_score
 
 
 def CV_None(predictors,target,**cv_kwargs):
+    """No cross validation: train and test data are the same."""
     return [[predictors,target,predictors,target]]
 
 def CV_drop1year(predictors,target,**cv_kwargs):
-    
+    """Cross validation is performed by dropping out single years of data from the training set to use as test data. This is repeated for all years with non-nan data."""
+
     X,y=xr.align(predictors.dropna('time',how='all'),target.dropna('time',how='all'))
     years=np.unique(X['time.year'])
     iters=[]
     for t in years:
         it=[]
         it.append(X.where(X['time.year']!=t).dropna('time'))
         it.append(y.where(y['time.year']!=t).dropna('time'))
         it.append(X.where(X['time.year']==t).dropna('time'))
         it.append(y.where(y['time.year']==t).dropna('time'))
         iters.append(it)
     return iters
 
 def CV_n_chunks(predictors,target,N=2):
-    
+    """The dataset is split into *N* chunks and each is successively held out as test data."""
     X,y=xr.align(predictors,target)
     L=len(y)
     l=L//N
     iters=[]
     for n in range(N):
         
         test_times=np.arange(n*l,(n+1)*l)
@@ -38,38 +40,38 @@
         X_test=X.isel(time=test_times)
         y_test=y.isel(time=test_times)
         
         iters.append([X_train,y_train,X_test,y_test])
     return iters
 
 def CV_manual(train_pred,train_targ,test_pred=None,test_targ=None):
-    
+    """Separate training and test datasets are passed manually."""
     if test_pred is None or test_targ is None:
         raise(ValueError('Both test_pred and test_targ must be specified when using CV_manual'))
     return [[train_pred,train_targ,test_pred,test_targ]]
 
 def log_regression_model(X_train,y_train,X_test,**model_kwargs):
-    
+    """A wrapper around sklearn's *LogisticRegression* class, which accepts the same *model_kwargs*"""
     LR=LogisticRegression(**model_kwargs)
     LR=LR.fit(X_train,y_train)
     
     det_pred=LR.predict(X_test)
     prob_pred=LR.predict_proba(X_test)
     return LR,det_pred,prob_pred
 
 def blank_score(det_pred,prob_pred,target,**score_kwargs):
-    
+    """@private"""
     if det_pred is not None:
         assert det_pred.shape[0]==target.shape[0]
     if prob_pred is not None:
         assert prob_pred.shape[0]==target.shape[0]
     return len(target)
 
 def ROC_AUC(det_pred,prob_pred,target,**score_kwargs):
-    
+    """Computes the ROC AUC score, as implemented in sklearn, and accepting the same *score_kwargs*"""
     #No ROC_AUC for a variable with only one value
     if len(np.unique(target))==1:
         return np.nan
     if len(np.unique(target))==2:
         prob_pred=prob_pred[:,1]
         
     
@@ -79,42 +81,54 @@
     """
     Supports quick and simple testing of the predictive power of predictor variables stored in an xarray.Dataset applied to a target variable stored in an xarray.DataArray.
     Supports different predictive models, cross validation approaches and skill scores within a straightforward API.
     
     **Arguments**
     
     *predictors*
+    
     An xarray Dataset of scalar predictors
     
     *predictand*
+    
     An xarray DataArray with a shared coord to *predictors*.
     """
     def __init__(self,predictors,predictand,tolerate_empty_variables=False):
+        """Initialise a PredictionTest object"""
         
         self.predictand=self._predictand_to_dataarray(predictand)
-        self.predictors=self._predictors_to_dataset(predictors)
+        """@private"""
         
+        self.predictors=self._predictors_to_dataset(predictors)
+        """@private"""
+
         
         self.predefined_models=dict(
             logregression=log_regression_model
         )
+        """@private"""
         
         self.predefined_cv_methods=dict(
             nchunks=CV_n_chunks,
             drop_year=CV_drop1year,
             manual=CV_manual
         )
+        """@private"""
         
         self.predefined_scores=dict(
             sklearn_roc_auc=ROC_AUC,
             test=blank_score
         )
+        """@private"""
+        
         self.computed_scores=None
+        """@private"""
         
         self.tol_empty=tolerate_empty_variables
+        """@private"""
         return
     
     def __repr__(self):
         return 'A PredictionTest object'
     def __str__(self):
         return self.__repr__
     
@@ -135,56 +149,75 @@
     def categorical_prediction(self,model,score='sklearn_roc_auc',cv_method=None,predictor_variables='univariate',keep_models=False,model_kwargs={},cv_kwargs={},score_kwargs={}):
         
         """
         
         **Arguments**
         
         *model*
+        
         A function with the following signature:
-            Input: Three numpy arrays of shape [T1,N], [T1], [T2,N] (train_predictors, train_target, and test_predictors respectively), and an arbitrary number of keyword arguments.
-            Output: *model* (A scikit-learn-like fitted model object),*det_pred* (a numpy array of shape [T2] with deterministic predictions) and *prob_pred* (a numpy array of shape [T2,M] with probabilistic predictions, where M is the number of unique values in *train_target* and each element predicts the probability of a given class). Any output can instead be replaced with None, but at least one of *det_pred* and *prob_pred* must not be None.
+        
+        Input: Three numpy arrays of shape [T1,N], [T1], [T2,N] (train_predictors, train_target, and test_predictors respectively), and an arbitrary number of keyword arguments.
+        
+        Output: *model* (A scikit-learn-like fitted model object),*det_pred* (a numpy array of shape [T2] with deterministic predictions) and *prob_pred* (a numpy array of shape [T2,M] with probabilistic predictions, where M is the number of unique values in *train_target* and each element predicts the probability of a given class). Any output can instead be replaced with None, but at least one of *det_pred* and *prob_pred* must not be None.
             
         **Optional arguments**
         
         *score*
-            A string specifying a predefined skill score (currently only 'sklearn_roc_auc') or a function with the signature:
-            Input: det_pred (a numpy array of shape [T2]), prob_pred (a numpy array of shape [T2,M], a truth series (a numpy array of shape [T2]), and an arbitrary number of keyword arguments.
-            Output: a scalar skill score.
+        
+        A string specifying a predefined skill score (currently only 'sklearn_roc_auc') or a function with the signature:
+        
+        Input: det_pred (a numpy array of shape [T2]), prob_pred (a numpy array of shape [T2,M], a truth series (a numpy array of shape [T2]), and an arbitrary number of keyword arguments.
+        Output: a scalar skill score.
             
         *cv_method*
-            A string specifying a predefined cross-validation method, a custom cross-validation function with corresponding signature, or None, in which case no cross-validation is used (the training and test datasets are the same). Predefined cross-validation methods are:
-                *nchunks* - Divide the dataset into *n* chunks, using each as the test dataset predicted by the other *n*-1 chunks, to produce *n* total skill estimates. *n* defaults to 2, and is specified in *cv_kwargs*
-                *drop_year* - Split the dataset by calendar year, using each year as the test dataset predicted by the remaining years.
-                *manual* - Treat *predictors* and *predictand* as training data. Test data must be passed explicitly via *cv_kwargs* as *test_pred* and *test_targ*.
-            If a custom function is passed it must have the following signature:
-            Input: predictors (a Dataset), target (a DataArray), and an arbitrary number of keyword arguments.
-            Output: A train predictor Dataset, a train target DatArray, a test predictor Dataset, and a test target DataArray.
+        A string specifying a predefined cross-validation method, a custom cross-validation function with corresponding signature, or None, in which case no cross-validation is used (the training and test datasets are the same). Predefined cross-validation methods are:
+        
+        *nchunks* - Divide the dataset into *n* chunks, using each as the test dataset predicted by the other *n*-1 chunks, to produce *n* total skill estimates. *n* defaults to 2, and is specified in *cv_kwargs*
+        
+        *drop_year* - Split the dataset by calendar year, using each year as the test dataset predicted by the remaining years.
+        *manual* - Treat *predictors* and *predictand* as training data. Test data must be passed explicitly via *cv_kwargs* as *test_pred* and *test_targ*.
+        
+        If a custom function is passed it must have the following signature:
+        Input: predictors (a Dataset), target (a DataArray), and an arbitrary number of keyword arguments.
+        
+        Output: A train predictor Dataset, a train target DatArray, a test predictor Dataset, and a test target DataArray.
 
         *predictor_variables*
-            If 'univariate' all variables in *PredictionTest.predictors* are used individually to predict *PredictionTest.predictand*.
-            If 'all' all variables in *PredictionTest.predictors* are used collectively to predict *PredictionTest.predictand*.
-            If a 1D array of variable names in *PredictionTest.predictors*, each specified variable is used individually to predict *PredictionTest.predictand*.
-            If a 2D array of iterables over variable names in *PredictionTest.predictors*, each specified combination of variables is used to predict *PredictionTest.predictand*.
+        
+        If 'univariate' all variables in *PredictionTest.predictors* are used individually to predict *PredictionTest.predictand*.
+        
+        If 'all' all variables in *PredictionTest.predictors* are used collectively to predict *PredictionTest.predictand*.
+        
+        If a 1D array of variable names in *PredictionTest.predictors*, each specified variable is used individually to predict *PredictionTest.predictand*.
+        
+        If a 2D array of iterables over variable names in *PredictionTest.predictors*, each specified combination of variables is used to predict *PredictionTest.predictand*.
             
         *keep_models*
-            If True, a dictionary of arrays of fitted models is returned, corresponding to each variable combination and cross validated model that was computed.
+        If True, a dictionary of arrays of fitted models is returned, corresponding to each variable combination and cross validated model that was computed.
         
         *model_kwargs*
-            A dictionary of keyword arguments to pass to *model*
+        
+        A dictionary of keyword arguments to pass to *model*
         *cv_kwargs*
-            A dictionary of keyword arguments to pass to *cv_method*
+        
+        A dictionary of keyword arguments to pass to *cv_method*
 
         *score_kwargs*
-            A dictionary of keyword arguments to pass to *score*
+        
+        A dictionary of keyword arguments to pass to *score*
         
         **Returns**
+        
         If keep_models is False:
+        
         returns *score_da*, a Dataset of skill scores for each prediction experiment, with a cross_validation coordinate.
         
         if keep_models is True:
+        
         return (*score_da*,*model_da*)
         """
         if np.ndim(predictor_variables)==1:
             el_type=[np.ndim(element) for element in predictor_variables]
             
             if len(np.unique(el_type))==1 and np.unique(el_type)==1:#a list of ragged lists
                 score_labels=[f'predictor_set_{i+1}' for i in range(len(predictor_variables))]
@@ -303,27 +336,33 @@
         
         cv_iterator=cv_method(predictors,target,**cv_kwargs)
         return cv_iterator
     
     def add_score_to_index_metadata(self,indices,label='score',raise_on_missing_var=False,reduce_func=np.nanmean):
         
         """ Annotate a Dataset of indices with computed skill scores by adding them to the attributes of each DataArray in the Dataset.
+        
         **Arguments**
         
         *indices*
+        
         *An xarray.Dataset of indices*.
         
         **Optional arguments**
         
         *label*
+        
         A string determining the name of the added attribute key.
+        
         *raise_on_missing_var*
+        
         A boolean, determining if an error is raised if not all variables present in the computed skill scores are present in the indices.
         
         *reduce_func*
+        
         The function used to reduce the 'cv' vector of skill scores to a single value. Default is the mean average, ignoring nans. To add the entire vector of scores for different cross validations, pass *reduce_func*=lambda x: x
         
         """
         s=self.computed_scores
         if s is None:
             raise(ValueError('No scores computed.'))
         for var in s.data_vars:
```

### Comparing `domino-composite-0.3/domino/util.py` & `domino-composite-0.31/domino/util.py`

 * *Files identical despite different names*

### Comparing `domino-composite-0.3/domino_composite.egg-info/PKG-INFO` & `domino-composite-0.31/domino_composite.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,36 +1,38 @@
 Metadata-Version: 2.1
 Name: domino-composite
-Version: 0.3
+Version: 0.31
 Summary: A package for compositing atmospheric datasets
 Home-page: https://github.com/joshdorrington/domino
 Author: Josh Dorrington
 Author-email: joshua.dorrington@kit.edu
 License: bsd-3-clause
 Description-Content-Type: text/markdown
 
 # Domino is a package for analysing composites of atmospheric data.
-## Based on xarray, Domino makes it easy to calculate lagged composites of fields and scalar indices around categorical event time series, and to compute bootstrapped confidence bounds. This is still an alpha release! While core functionality is stable, there could be some bugs!
+## Based on xarray, Domino makes it easy to calculate lagged composites of fields and scalar indices around categorical event time series, and to compute bootstrapped confidence bounds.
 
-![title](Imgs/domino_logo.png)
+## This is a beta release. While core functionality is stable, there may be some bugs: please contact me at joshua.dorrington@kit.edu if you encounter unexpected behaviour.
+
+<img src="Imgs/domino_logo.png" alt="logo" width="180"/>
 
 
 ## Documentation
 
 See our [API reference](https://github.com/joshdorrington/domino/blob/master/docbuild/domino-composite.pdf) for a full description of all functionality.
 
-[//]: # (Our preprint on Domino (under consideration at QJRMS), and its application to extreme rainfall prediction can be found [here](where))
+<!-- (Our preprint on Domino (under consideration at QJRMS), and its application to extreme rainfall prediction can be found [here](where)) -->
 
 ## Examples
 
 See our Jupyter notebook examples for more detailed discussion of how to apply Domino to different use cases.
 
 Our [basic](https://github.com/joshdorrington/domino/blob/master/examples/basic_compositing.ipynb) and [advanced](https://github.com/joshdorrington/domino/blob/master/examples/advanced_compositing.ipynb) compositing guides cover the use of Domino's flexible LaggedAnalyser class to easily compute time-lagged composites and apply bootstrap significance tests to them.
 
-Producing filtered precursor patterns from composites, and computing precursor activity indices from those, is covered in our [Index_Computation guide](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb), while an introduction to assessing the predictive power of indices is in the [Index_Predictability guide](https://github.com/joshdorrington/domino/blob/master/examples/Index_predictability.ipynb).
+Producing filtered precursor patterns from composites, and computing precursor activity indices from those, is covered in our [Index_Computation guide](https://github.com/joshdorrington/domino/blob/master/examples/precursor_index_computation.ipynb), while an introduction to assessing the predictive power of indices is in the [Index_Predictability guide](https://github.com/joshdorrington/domino/blob/master/examples/Index_Predictability.ipynb).
 
 
 ## Install
 
 domino can be installed using pip:
 ```
 python -m pip install domino-composite
```

### Comparing `domino-composite-0.3/setup.py` & `domino-composite-0.31/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("/data/ox5324/Domino/readme.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name='domino-composite',
-    version='0.3',
+    version='0.31',
     author='Josh Dorrington',
     author_email='joshua.dorrington@kit.edu',
     description='A package for compositing atmospheric datasets',
     long_description=long_description,
     long_description_content_type="text/markdown",
     url='https://github.com/joshdorrington/domino',
     license='bsd-3-clause',
```


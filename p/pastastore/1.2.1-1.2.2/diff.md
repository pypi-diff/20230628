# Comparing `tmp/pastastore-1.2.1.tar.gz` & `tmp/pastastore-1.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pastastore-1.2.1.tar", last modified: Fri May 12 13:03:39 2023, max compression
+gzip compressed data, was "pastastore-1.2.2.tar", last modified: Wed Jun 28 07:50:38 2023, max compression
```

## Comparing `pastastore-1.2.1.tar` & `pastastore-1.2.2.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-12 13:03:39.086528 pastastore-1.2.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-05-12 13:03:20.000000 pastastore-1.2.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     6432 2023-05-12 13:03:39.086528 pastastore-1.2.1/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-12 13:03:39.086528 pastastore-1.2.1/pastastore/
--rw-r--r--   0 runner    (1001) docker     (123)      225 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    62290 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/base.py
--rw-r--r--   0 runner    (1001) docker     (123)    28727 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/connectors.py
--rw-r--r--   0 runner    (1001) docker     (123)     6631 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/datasets.py
--rw-r--r--   0 runner    (1001) docker     (123)    41622 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/plotting.py
--rw-r--r--   0 runner    (1001) docker     (123)    34126 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/store.py
--rw-r--r--   0 runner    (1001) docker     (123)    31203 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/util.py
--rw-r--r--   0 runner    (1001) docker     (123)      203 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    29490 2023-05-12 13:03:20.000000 pastastore-1.2.1/pastastore/yaml_interface.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-12 13:03:39.086528 pastastore-1.2.1/pastastore.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6432 2023-05-12 13:03:39.000000 pastastore-1.2.1/pastastore.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      567 2023-05-12 13:03:39.000000 pastastore-1.2.1/pastastore.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-12 13:03:39.000000 pastastore-1.2.1/pastastore.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      420 2023-05-12 13:03:39.000000 pastastore-1.2.1/pastastore.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-05-12 13:03:39.000000 pastastore-1.2.1/pastastore.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-05-12 13:03:20.000000 pastastore-1.2.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     3576 2023-05-12 13:03:20.000000 pastastore-1.2.1/readme.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-12 13:03:39.086528 pastastore-1.2.1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-12 13:03:39.086528 pastastore-1.2.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      170 2023-05-12 13:03:20.000000 pastastore-1.2.1/tests/test_001_import.py
--rw-r--r--   0 runner    (1001) docker     (123)     8057 2023-05-12 13:03:20.000000 pastastore-1.2.1/tests/test_002_connectors.py
--rw-r--r--   0 runner    (1001) docker     (123)     8412 2023-05-12 13:03:20.000000 pastastore-1.2.1/tests/test_003_pastastore.py
--rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-05-12 13:03:20.000000 pastastore-1.2.1/tests/test_004_yaml.py
--rw-r--r--   0 runner    (1001) docker     (123)     1852 2023-05-12 13:03:20.000000 pastastore-1.2.1/tests/test_005_maps_plots.py
--rw-r--r--   0 runner    (1001) docker     (123)     7695 2023-05-12 13:03:20.000000 pastastore-1.2.1/tests/test_006_benchmark.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:50:38.989019 pastastore-1.2.2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-06-28 07:50:24.000000 pastastore-1.2.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     6453 2023-06-28 07:50:38.989019 pastastore-1.2.2/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:50:38.989019 pastastore-1.2.2/pastastore/
+-rw-r--r--   0 runner    (1001) docker     (123)      225 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62290 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28727 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/connectors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6640 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/datasets.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41758 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/plotting.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34126 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/store.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30268 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)      203 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29490 2023-06-28 07:50:24.000000 pastastore-1.2.2/pastastore/yaml_interface.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:50:38.989019 pastastore-1.2.2/pastastore.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6453 2023-06-28 07:50:38.000000 pastastore-1.2.2/pastastore.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      567 2023-06-28 07:50:38.000000 pastastore-1.2.2/pastastore.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:50:38.000000 pastastore-1.2.2/pastastore.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      469 2023-06-28 07:50:38.000000 pastastore-1.2.2/pastastore.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 07:50:38.000000 pastastore-1.2.2/pastastore.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2611 2023-06-28 07:50:24.000000 pastastore-1.2.2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     3576 2023-06-28 07:50:24.000000 pastastore-1.2.2/readme.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 07:50:38.989019 pastastore-1.2.2/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:50:38.989019 pastastore-1.2.2/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      170 2023-06-28 07:50:24.000000 pastastore-1.2.2/tests/test_001_import.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8057 2023-06-28 07:50:24.000000 pastastore-1.2.2/tests/test_002_connectors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8491 2023-06-28 07:50:24.000000 pastastore-1.2.2/tests/test_003_pastastore.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-06-28 07:50:24.000000 pastastore-1.2.2/tests/test_004_yaml.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1852 2023-06-28 07:50:24.000000 pastastore-1.2.2/tests/test_005_maps_plots.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7695 2023-06-28 07:50:24.000000 pastastore-1.2.2/tests/test_006_benchmark.py
```

### Comparing `pastastore-1.2.1/LICENSE` & `pastastore-1.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/PKG-INFO` & `pastastore-1.2.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pastastore
-Version: 1.2.1
+Version: 1.2.2
 Summary: Tools for managing Pastas time series models.
 Author: D.A. Brakenhoff
 Maintainer-email: "D.A. Brakenhoff" <d.brakenhoff@artesia-water.nl>, "R. Calje" <r.calje@artesia-water.nl>, "M.A. Vonk" <m.vonk@artesia-water.nl>
 License: The MIT License (MIT)
         
         Copyright (c) 2020 D.A. Brakenhoff
         
@@ -45,14 +45,15 @@
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Topic :: Scientific/Engineering :: Hydrology
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
+Provides-Extra: full
 Provides-Extra: lint
 Provides-Extra: optional
 Provides-Extra: test
 Provides-Extra: pystore
 Provides-Extra: arctic
 Provides-Extra: arcticdb
 Provides-Extra: docs
```

### Comparing `pastastore-1.2.1/pastastore/base.py` & `pastastore-1.2.2/pastastore/base.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/pastastore/connectors.py` & `pastastore-1.2.2/pastastore/connectors.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/pastastore/datasets.py` & `pastastore-1.2.2/pastastore/datasets.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import os
 
-import hydropandas as hpd
 import pandas as pd
+from hydropandas import Obs, ObsCollection
 
 try:
     from pastas.timeseries_utils import timestep_weighted_resample
 except ModuleNotFoundError:
     from pastas.utils import timestep_weighted_resample
 
 import pastastore as pst
@@ -110,15 +110,15 @@
         metadata={"x": 200_000, "y": 450_000.0},
     )
     # TODO: temporary fix for older version of hydropandas that does not
     # read Menyanthes time series names correctly.
     # multiwell notebook data
     fname = os.path.join(datadir, "MenyanthesTest.men")
     # meny = ps.read.MenyData(fname)
-    meny = hpd.ObsCollection.from_menyanthes(fname, hpd.Obs)
+    meny = ObsCollection.from_menyanthes(fname, Obs)
 
     oseries = meny.loc["Obsevation well", "obs"]
     ometa = {
         "x": oseries.meta["x"],
         "y": oseries.meta["y"],
     }
     pstore.add_oseries(oseries.dropna(), "head_mw", metadata=ometa)
```

### Comparing `pastastore-1.2.1/pastastore/plotting.py` & `pastastore-1.2.2/pastastore/plotting.py`

 * *Files 1% similar despite different names*

```diff
@@ -119,15 +119,14 @@
             iax.plot(ts.index, ts.squeeze(), label=n, **kwargs)
             if split:
                 iax.legend(loc="best", fontsize="x-small")
 
         if not split:
             axes.legend(loc=(0, 1), frameon=False, ncol=7, fontsize="x-small")
 
-        fig.tight_layout()
         return axes
 
     def oseries(self, names=None, ax=None, split=False, figsize=(10, 5), **kwargs):
         """Plot oseries.
 
         Parameters
         ----------
@@ -407,15 +406,15 @@
         if set_yticks:
             ax.set_yticks(np.arange(0.5, len(series) + 0.5))
             if names is None:
                 names = [s.name for s in series]
             ax.set_yticklabels(names)
         else:
             ax.set_ylabel("Timeseries (-)")
-        ax.grid()
+        ax.grid(True)
 
         return ax
 
     def cumulative_hist(
         self,
         statistic="rsq",
         modelnames=None,
@@ -1264,21 +1263,29 @@
         adjust: bool
             automated smart label placement using adjustText
         **kwargs:
             keyword arguments to ax.annotate
         """
         stroke = [patheffects.withStroke(linewidth=3, foreground="w")]
 
+        fontsize = kwargs.pop("fontsize", 10)
+
         if adjust:
             from adjustText import adjust_text
 
             texts = []
             for name, row in df.iterrows():
                 texts.append(
-                    ax.text(row["x"], row["y"], name, **{"path_effects": stroke})
+                    ax.text(
+                        row["x"],
+                        row["y"],
+                        name,
+                        fontsize=fontsize,
+                        **{"path_effects": stroke},
+                    )
                 )
 
             adjust_text(
                 texts,
                 force_text=0.05,
                 **{
                     "arrowprops": {
@@ -1286,15 +1293,14 @@
                         "color": "k",
                         "alpha": 0.5,
                     }
                 },
             )
 
         else:
-            fontsize = kwargs.pop("fontsize", 10)
             textcoords = kwargs.pop("textcoords", "offset points")
             xytext = kwargs.pop("xytext", (10, 10))
 
             for name, row in df.iterrows():
                 namestr = str(name)
                 ax.annotate(
                     text=namestr,
```

### Comparing `pastastore-1.2.1/pastastore/store.py` & `pastastore-1.2.2/pastastore/store.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/pastastore/util.py` & `pastastore-1.2.2/pastastore/util.py`

 * *Files 2% similar despite different names*

```diff
@@ -680,15 +680,15 @@
                     check_st_acf_passed,
                 )
 
         # Check 3 - Response Time
         if check3_tmem:
             len_oseries_calib = (ml.settings["tmax"] - ml.settings["tmin"]).days
             for sm_name, sm in ml.stressmodels.items():
-                if sm_name.startswith("wells"):
+                if sm._name == "WellModel":
                     nwells = sm.distances.index.size
                     for iw in range(nwells):
                         p = sm.get_parameters(model=ml, istress=iw)
                         t = sm.rfunc.get_t(p, dt=1, cutoff=0.999)
                         step = sm.rfunc.step(p, cutoff=0.999) / sm.rfunc.gain(p)
                         tmem = np.interp(check3_cutoff, step, t)
                         check_tmem_passed = tmem < len_oseries_calib / 2
@@ -711,32 +711,15 @@
                         "days",
                         check_tmem_passed,
                     )
 
         # Check 4 - Uncertainty Gain
         if check4_gain:
             for sm_name, sm in ml.stressmodels.items():
-                if sm_name.startswith("wells"):
-                    p = ml.get_parameters(sm_name)
-                    gain = sm.rfunc.gain(p)
-                    A = ml.parameters.loc[f"{sm_name}_A", "optimal"]
-                    b = ml.parameters.loc[f"{sm_name}_b", "optimal"]
-                    var_A = ml.parameters.loc[f"{sm_name}_A", "stderr"] ** 2
-                    var_b = ml.parameters.loc[f"{sm_name}_b", "stderr"] ** 2
-                    cov_Ab = ml.fit.pcov.loc[f"{sm_name}_A", f"{sm_name}_b"]
-                    gain_std = np.sqrt(
-                        sm.rfunc.variance_gain(A, b, var_A, var_b, cov_Ab)
-                    )
-                    if gain_std is None:
-                        gain_std = np.nan
-                        check_gain_passed = pd.NA
-                    elif np.isnan(gain_std):
-                        check_gain_passed = pd.NA
-                    else:
-                        check_gain_passed = np.abs(gain) > 2 * gain_std
+                if sm._name == "WellModel":
                     for iw in range(sm.distances.index.size):
                         p = sm.get_parameters(model=ml, istress=iw)
                         gain = sm.rfunc.gain(p)
                         gain_std = np.sqrt(sm.variance_gain(model=ml, istress=iw))
                         if gain_std is None:
                             gain_std = np.nan
                             check_gain_passed = pd.NA
```

### Comparing `pastastore-1.2.1/pastastore/yaml_interface.py` & `pastastore-1.2.2/pastastore/yaml_interface.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/pastastore.egg-info/PKG-INFO` & `pastastore-1.2.2/pastastore.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pastastore
-Version: 1.2.1
+Version: 1.2.2
 Summary: Tools for managing Pastas time series models.
 Author: D.A. Brakenhoff
 Maintainer-email: "D.A. Brakenhoff" <d.brakenhoff@artesia-water.nl>, "R. Calje" <r.calje@artesia-water.nl>, "M.A. Vonk" <m.vonk@artesia-water.nl>
 License: The MIT License (MIT)
         
         Copyright (c) 2020 D.A. Brakenhoff
         
@@ -45,14 +45,15 @@
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Topic :: Scientific/Engineering :: Hydrology
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
+Provides-Extra: full
 Provides-Extra: lint
 Provides-Extra: optional
 Provides-Extra: test
 Provides-Extra: pystore
 Provides-Extra: arctic
 Provides-Extra: arcticdb
 Provides-Extra: docs
```

### Comparing `pastastore-1.2.1/pastastore.egg-info/SOURCES.txt` & `pastastore-1.2.2/pastastore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/pyproject.toml` & `pastastore-1.2.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -41,26 +41,28 @@
 
 [project.urls]
 homepage = "https://github.com/pastas/pastastore"
 repository = "https://github.com/pastas/pastastore"
 documentation = "https://pastastore.readthedocs.io/en/latest/"
 
 [project.optional-dependencies]
+full = ["pastastore[arcticdb,optional]"]
 lint = ["black", "flake8", "isort"]
 optional = ["contextily", "pyproj", "adjustText"]
 test = [
     "pastastore[arcticdb,lint,optional]",
-    "hydropandas",
+    "hydropandas[full]",
     "coverage",
     "codecov",
     "pytest",
     "pytest-cov",
     "pytest-dependency",
     "pytest-benchmark",
     "codacy-coverage",
+    "lxml",  # temporary fix: for hydropandas 0.8.0
 ]
 pystore = ["fsspec>=0.3.3", "python-snappy", "dask[dataframe]"]
 arctic = [
     "arctic", # will not work as releases not uploaded to PyPI
 ]
 arcticdb = ["arcticdb"]
 docs = [
```

### Comparing `pastastore-1.2.1/readme.md` & `pastastore-1.2.2/readme.md`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/tests/test_002_connectors.py` & `pastastore-1.2.2/tests/test_002_connectors.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/tests/test_003_pastastore.py` & `pastastore-1.2.2/tests/test_003_pastastore.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 import warnings
 
 import numpy as np
 import pandas as pd
 import pastas as ps
 import pytest
 from numpy import allclose
+from packaging.version import parse
 from pytest_dependency import depends
 
 with warnings.catch_warnings():
     warnings.simplefilter(action="ignore", category=FutureWarning)
     import pastastore as pst
 
 
@@ -253,17 +254,17 @@
 
 def test_copy_dbase(pstore):
     conn2 = pst.DictConnector("destination")
     pst.util.copy_database(pstore.conn, conn2, overwrite=False, progressbar=True)
 
 
 def test_to_from_zip(pstore):
-    zipname = f"test_{pstore.type}.zip"
-    if pstore.type == "arcticdb":
+    if pstore.type == "arcticdb" and parse(ps.__version__) < parse("1.1.0"):
         pytest.xfail("model datetime objects not supported")
+    zipname = f"test_{pstore.type}.zip"
     pstore.to_zip(zipname, progressbar=False, overwrite=True)
     conn = pst.DictConnector("test")
     try:
         store = pst.PastaStore.from_zip(zipname, conn)
         assert not store.oseries.empty
     finally:
         os.remove(zipname)
```

### Comparing `pastastore-1.2.1/tests/test_004_yaml.py` & `pastastore-1.2.2/tests/test_004_yaml.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/tests/test_005_maps_plots.py` & `pastastore-1.2.2/tests/test_005_maps_plots.py`

 * *Files identical despite different names*

### Comparing `pastastore-1.2.1/tests/test_006_benchmark.py` & `pastastore-1.2.2/tests/test_006_benchmark.py`

 * *Files identical despite different names*


# Comparing `tmp/xdas-0.1b0.tar.gz` & `tmp/xdas-0.1b1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "xdas-0.1b0.tar", last modified: Tue Jun 13 10:07:02 2023, max compression
+gzip compressed data, was "xdas-0.1b1.tar", last modified: Wed Jun 28 14:23:15 2023, max compression
```

## Comparing `xdas-0.1b0.tar` & `xdas-0.1b1.tar`

### file list

```diff
@@ -1,28 +1,31 @@
-drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-13 10:07:02.276571 xdas-0.1b0/
--rw-r--r--   0 trabatto   (502) staff       (20)    35149 2023-01-26 16:18:03.000000 xdas-0.1b0/LICENSE.md
--rw-r--r--   0 trabatto   (502) staff       (20)      180 2023-06-13 10:07:02.276410 xdas-0.1b0/PKG-INFO
--rw-r--r--   0 trabatto   (502) staff       (20)      664 2023-06-13 10:01:52.000000 xdas-0.1b0/README.md
--rw-r--r--   0 trabatto   (502) staff       (20)      519 2023-06-13 09:50:51.000000 xdas-0.1b0/pyproject.toml
--rw-r--r--   0 trabatto   (502) staff       (20)       38 2023-06-13 10:07:02.276615 xdas-0.1b0/setup.cfg
-drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-13 10:07:02.274176 xdas-0.1b0/tests/
--rw-r--r--   0 trabatto   (502) staff       (20)    10709 2023-06-13 09:50:51.000000 xdas-0.1b0/tests/test_coordinates.py
--rw-r--r--   0 trabatto   (502) staff       (20)        0 2023-06-13 09:50:51.000000 xdas-0.1b0/tests/test_core.py
--rw-r--r--   0 trabatto   (502) staff       (20)     1550 2023-06-13 09:50:51.000000 xdas-0.1b0/tests/test_database.py
--rw-r--r--   0 trabatto   (502) staff       (20)     2568 2023-06-13 09:50:51.000000 xdas-0.1b0/tests/test_signal.py
-drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-13 10:07:02.275054 xdas-0.1b0/xdas/
--rw-r--r--   0 trabatto   (502) staff       (20)      179 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/__init__.py
--rw-r--r--   0 trabatto   (502) staff       (20)    11805 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/coordinates.py
--rw-r--r--   0 trabatto   (502) staff       (20)     3420 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/core.py
--rw-r--r--   0 trabatto   (502) staff       (20)    12260 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/database.py
-drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-13 10:07:02.276229 xdas-0.1b0/xdas/io/
--rw-r--r--   0 trabatto   (502) staff       (20)        0 2022-12-29 11:57:28.000000 xdas-0.1b0/xdas/io/__init__.py
--rw-r--r--   0 trabatto   (502) staff       (20)      627 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/io/asn.py
--rw-r--r--   0 trabatto   (502) staff       (20)     3691 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/io/febus.py
--rw-r--r--   0 trabatto   (502) staff       (20)     5363 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/signal.py
--rw-r--r--   0 trabatto   (502) staff       (20)     2449 2023-06-13 09:50:51.000000 xdas-0.1b0/xdas/virtual.py
-drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-13 10:07:02.275842 xdas-0.1b0/xdas.egg-info/
--rw-r--r--   0 trabatto   (502) staff       (20)      180 2023-06-13 10:07:02.000000 xdas-0.1b0/xdas.egg-info/PKG-INFO
--rw-r--r--   0 trabatto   (502) staff       (20)      413 2023-06-13 10:07:02.000000 xdas-0.1b0/xdas.egg-info/SOURCES.txt
--rw-r--r--   0 trabatto   (502) staff       (20)        1 2023-06-13 10:07:02.000000 xdas-0.1b0/xdas.egg-info/dependency_links.txt
--rw-r--r--   0 trabatto   (502) staff       (20)      145 2023-06-13 10:07:02.000000 xdas-0.1b0/xdas.egg-info/requires.txt
--rw-r--r--   0 trabatto   (502) staff       (20)        5 2023-06-13 10:07:02.000000 xdas-0.1b0/xdas.egg-info/top_level.txt
+drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-28 14:23:15.893174 xdas-0.1b1/
+-rw-r--r--   0 trabatto   (502) staff       (20)    35149 2023-01-26 16:18:03.000000 xdas-0.1b1/LICENSE.md
+-rw-r--r--   0 trabatto   (502) staff       (20)      200 2023-06-28 14:23:15.893026 xdas-0.1b1/PKG-INFO
+-rw-r--r--   0 trabatto   (502) staff       (20)      664 2023-06-13 10:17:32.000000 xdas-0.1b1/README.md
+-rw-r--r--   0 trabatto   (502) staff       (20)      602 2023-06-28 14:19:21.000000 xdas-0.1b1/pyproject.toml
+-rw-r--r--   0 trabatto   (502) staff       (20)       38 2023-06-28 14:23:15.893248 xdas-0.1b1/setup.cfg
+drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-28 14:23:15.890513 xdas-0.1b1/tests/
+-rw-r--r--   0 trabatto   (502) staff       (20)    10709 2023-06-13 09:50:51.000000 xdas-0.1b1/tests/test_coordinates.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     1353 2023-06-28 14:18:52.000000 xdas-0.1b1/tests/test_core.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     1550 2023-06-13 09:50:51.000000 xdas-0.1b1/tests/test_database.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     2356 2023-06-28 14:18:52.000000 xdas-0.1b1/tests/test_processing.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     2289 2023-06-28 14:18:52.000000 xdas-0.1b1/tests/test_signal.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     2069 2023-06-28 14:18:52.000000 xdas-0.1b1/tests/test_virtual.py
+drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-28 14:23:15.891454 xdas-0.1b1/xdas/
+-rw-r--r--   0 trabatto   (502) staff       (20)      179 2023-06-27 07:52:45.000000 xdas-0.1b1/xdas/__init__.py
+-rw-r--r--   0 trabatto   (502) staff       (20)    11805 2023-06-13 09:50:51.000000 xdas-0.1b1/xdas/coordinates.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     4459 2023-06-28 14:18:52.000000 xdas-0.1b1/xdas/core.py
+-rw-r--r--   0 trabatto   (502) staff       (20)    12260 2023-06-13 09:50:51.000000 xdas-0.1b1/xdas/database.py
+drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-28 14:23:15.892823 xdas-0.1b1/xdas/io/
+-rw-r--r--   0 trabatto   (502) staff       (20)        0 2022-12-29 11:57:28.000000 xdas-0.1b1/xdas/io/__init__.py
+-rw-r--r--   0 trabatto   (502) staff       (20)      677 2023-06-28 14:18:52.000000 xdas-0.1b1/xdas/io/asn.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     3691 2023-06-13 09:50:51.000000 xdas-0.1b1/xdas/io/febus.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     9268 2023-06-28 14:18:52.000000 xdas-0.1b1/xdas/processing.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     3308 2023-06-28 14:18:52.000000 xdas-0.1b1/xdas/signal.py
+-rw-r--r--   0 trabatto   (502) staff       (20)     3666 2023-06-28 14:18:52.000000 xdas-0.1b1/xdas/virtual.py
+drwxr-xr-x   0 trabatto   (502) staff       (20)        0 2023-06-28 14:23:15.892161 xdas-0.1b1/xdas.egg-info/
+-rw-r--r--   0 trabatto   (502) staff       (20)      200 2023-06-28 14:23:15.000000 xdas-0.1b1/xdas.egg-info/PKG-INFO
+-rw-r--r--   0 trabatto   (502) staff       (20)      479 2023-06-28 14:23:15.000000 xdas-0.1b1/xdas.egg-info/SOURCES.txt
+-rw-r--r--   0 trabatto   (502) staff       (20)        1 2023-06-28 14:23:15.000000 xdas-0.1b1/xdas.egg-info/dependency_links.txt
+-rw-r--r--   0 trabatto   (502) staff       (20)      170 2023-06-28 14:23:15.000000 xdas-0.1b1/xdas.egg-info/requires.txt
+-rw-r--r--   0 trabatto   (502) staff       (20)        5 2023-06-28 14:23:15.000000 xdas-0.1b1/xdas.egg-info/top_level.txt
```

### Comparing `xdas-0.1b0/LICENSE.md` & `xdas-0.1b1/LICENSE.md`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/README.md` & `xdas-0.1b1/README.md`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/pyproject.toml` & `xdas-0.1b1/pyproject.toml`

 * *Files 27% similar despite different names*

```diff
@@ -1,33 +1,41 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "xdas"
-version = "0.1b"
+version = "0.1b1"
 authors = [
     {name = "Alister Trabattoni", email = "alister.trabattoni@gmail.com"},
 ]
 dependencies = [
     "dask",
     "h5py",
     "netcdf4",
     "numpy",
     "scipy",
     "tqdm",
     "xarray",
 ]
 
 [project.optional-dependencies]
+dev = [
+    "black",
+    "isort",
+    "twine",
+]
 docs = [
     "ipykernel",
     "matplotlib",
     "myst-nb",
     "sphinx-book-theme",
     "sphinx-design",
     "sphinx",
 ]
 tests = [
     "pytest",
     "pytest-cov",
-]
+]
+
+[tool.isort]
+profile = "black"
```

### Comparing `xdas-0.1b0/tests/test_coordinates.py` & `xdas-0.1b1/tests/test_coordinates.py`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/tests/test_database.py` & `xdas-0.1b1/tests/test_database.py`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/tests/test_signal.py` & `xdas-0.1b1/tests/test_processing.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 import dask.array as da
 import numpy as np
 import scipy.signal as sp
 
 from xdas.core import Coordinate, Database
-from xdas.signal import LFilter, SignalProcessingChain, SOSFilter
+from xdas.processing import LFilter, SignalProcessingChain, SOSFilter
 
 
-class TestSignal:
-    def test_signal(self):
+class TestProcessing:
+    def test_processing(self):
         fs = 125
         ks = 1 / 10
         data = da.random.normal(size=(1000, 100))
         time = Coordinate([0, data.shape[0] - 1], [0.0, (data.shape[0] - 1) / fs])
         distance = Coordinate([0, data.shape[1] - 1], [0.0, (data.shape[1] - 1) / ks])
         xarr = Database(data, {"time": time, "distance": distance})
         b, a = sp.iirfilter(4, 0.5, btype="lowpass")
@@ -22,36 +22,32 @@
         result_chunks = xarr.copy()
         for k in range(xarr.shape[0] // chunk_size):
             query = {"time": slice(k * chunk_size, (k + 1) * chunk_size)}
             result_chunks[query] = lfilter(xarr[query]).data
         lfilter.reset()
         chain = SignalProcessingChain([lfilter])
         out = chain.process(xarr, "time", chunk_size, parallel=False)
-        out = np.concatenate([x.data for x in out])
         lfilter.reset()
         assert chain.filters[0].zi == None
         out_parallel = chain.process(xarr, "time", chunk_size, parallel=True)
-        out_parallel = np.concatenate([x.data for x in out_parallel])
         assert np.allclose(result_chunks.data, result_direct.data)
-        assert np.allclose(out, result_direct.data)
-        assert np.allclose(out_parallel, result_direct.data)
+        assert np.allclose(out.data, result_direct.data)
+        assert np.allclose(out_parallel.data, result_direct.data)
 
         sos = sp.iirfilter(4, 0.5, btype="lowpass", output="sos")
         sosfilter = SOSFilter(sos, "time")
         result_direct = sosfilter(xarr)
         chunk_size = 100
         sosfilter.reset()
         result_chunks = xarr.copy()
         for k in range(xarr.shape[0] // chunk_size):
             query = {"time": slice(k * chunk_size, (k + 1) * chunk_size)}
             result_chunks[query] = sosfilter(xarr[query]).data
         sosfilter.reset()
         chain = SignalProcessingChain([sosfilter])
         out = chain.process(xarr, "time", chunk_size, parallel=False)
-        out = np.concatenate([x.data for x in out])
         sosfilter.reset()
         assert chain.filters[0].zi == None
         out_parallel = chain.process(xarr, "time", chunk_size, parallel=True)
-        out_parallel = np.concatenate([x.data for x in out_parallel])
         assert np.allclose(result_chunks.data, result_direct.data)
-        assert np.allclose(out, result_direct.data)
-        assert np.allclose(out_parallel, result_direct.data)
+        assert np.allclose(out.data, result_direct.data)
+        assert np.allclose(out_parallel.data, result_direct.data)
```

### Comparing `xdas-0.1b0/xdas/coordinates.py` & `xdas-0.1b1/xdas/coordinates.py`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/xdas/core.py` & `xdas-0.1b1/xdas/core.py`

 * *Files 16% similar despite different names*

```diff
@@ -19,67 +19,99 @@
         The path names given using shell=style wildcards.
     engine: str
         The engine to use to read the file.
     tolerance: timedelta64
         The tolerance to consider that the end of a file is continuous with the begging
         of the following
 
-    Returns
+    ReturnsDA
     -------
     Database
         The database containing all files data.
     """
     fnames = sorted(glob(paths))
+    if len(fnames) > 100_000:
+        raise NotImplementedError(
+            "The maximum number of file that can be opened at once is for now limited "
+            "to 100 000."
+        )
     with ProcessPoolExecutor() as executor:
         futures = [
             executor.submit(open_database, fname, engine=engine) for fname in fnames
         ]
         dbs = [
             future.result()
             for future in tqdm(
                 as_completed(futures),
                 total=len(futures),
                 desc="Fetching metadata from files",
             )
         ]
-    return concatenate(dbs, tolerance=tolerance)
+    return concatenate(dbs, tolerance=tolerance, virtual=True)
 
 
-def concatenate(dbs, tolerance=np.timedelta64(0, "us")):
+def concatenate(dbs, dim="time", tolerance=None, virtual=False):
     """
-    Concatenate several databases along the time dimension.
+    Concatenate several databases along a given dimension.
 
     Parameters
     ----------
     dbs : list
         List of databases to concatenate.
-    tolerance : timedelta64, optional
+    dim : str
+        The dimension along which concatenate.
+    tolerance : float of timedelta64, optional
         The tolerance to consider that the end of a file is continuous with beginning of
-        the following, by default np.timedelta64(0, "us").
+        the following, zero by default.
+    virtual : bool, optional
+        Whether to create a virtual dataset. It requires that all concatenated
+        databases are virtual.
 
     Returns
     -------
     Database
         The concatenated database.
     """
-
-    dbs = sorted(dbs, key=lambda db: db["time"][0])
-    shape = (sum([db.shape[0] for db in dbs]), dbs[0].shape[1])
+    dbs = sorted(dbs, key=lambda db: db[dim][0])
+    axis = dbs[0].get_axis_num(dim)
+    dims = dbs[0].dims
     dtype = dbs[0].dtype
-    layout = DataLayout(shape=shape, dtype=dtype)
+    shape = tuple(
+        sum([db.shape[a] for db in dbs]) if a == axis else dbs[0].shape[a]
+        for a in range(len(dims))
+    )
+    if virtual:
+        data = DataLayout(shape, dtype)
+    else:
+        data = np.zeros(shape, dtype)
     idx = 0
     tie_indices = []
     tie_values = []
-    for db in dbs:
-        layout[idx : idx + db.shape[0]] = db.data
-        tie_indices.extend(idx + db["time"].tie_indices)
-        tie_values.extend(db["time"].tie_values)
-        idx += db.shape[0]
-    time = Coordinate(tie_indices, tie_values).simplify(tolerance)
-    return Database(layout, {"time": time, "distance": dbs[0]["distance"]})
+    for db in tqdm(dbs, desc="Linking database"):
+        selection = tuple(
+            slice(idx, idx + db.shape[axis]) if d == dim else slice(None) for d in dims
+        )
+        if virtual:
+            data[selection] = db.data.vsource
+        else:
+            data[selection] = db.values
+        tie_indices.extend(idx + db[dim].tie_indices)
+        tie_values.extend(db[dim].tie_values)
+        idx += db.shape[axis]
+    coord = Coordinate(tie_indices, tie_values)
+    if tolerance is None:
+        if np.issubdtype(dbs[0][dim].dtype, np.datetime64):
+            tolerance = np.timedelta64(0, "us")
+        else:
+            tolerance = 0.0
+    if not tolerance == 0:
+        coord = coord.simplify(tolerance)
+    coords = dbs[0].coords
+    coords[dim] = coord
+    return Database(data, coords)
 
 
 def open_database(fname, group=None, engine="netcdf", **kwargs):
     """
     Open a database.
 
     Parameters
```

### Comparing `xdas-0.1b0/xdas/database.py` & `xdas-0.1b1/xdas/database.py`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/xdas/io/asn.py` & `xdas-0.1b1/xdas/io/asn.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,11 +1,13 @@
 import h5py
 import numpy as np
 
-from ..core import Coordinate, Database, DataSource
+from ..coordinates import Coordinate
+from ..database import Database
+from ..virtual import DataSource
 
 
 def read(fname):
     with h5py.File(fname, "r") as file:
         header = file["header"]
         t0 = np.datetime64(round(header["time"][()] * 1e6), "us")
         dt = np.timedelta64(round(1e6 * header["dt"][()]), "us")
```

### Comparing `xdas-0.1b0/xdas/io/febus.py` & `xdas-0.1b1/xdas/io/febus.py`

 * *Files identical despite different names*

### Comparing `xdas-0.1b0/xdas/virtual.py` & `xdas-0.1b1/xdas/virtual.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,55 +1,94 @@
 import os
+from copy import deepcopy
 from tempfile import TemporaryDirectory
 
 import h5py
 import numpy as np
 
 
-class DataSource(h5py.VirtualSource):
+class DataSource:
     """
     A lazy array object pointing toward a netCDF4/HDF5 file.
     """
 
+    def __init__(
+        self, path_or_dataset, name=None, shape=None, dtype=None, maxshape=None
+    ):
+        _vsource = h5py.VirtualSource(
+            path_or_dataset, name=None, shape=None, dtype=None, maxshape=None
+        )
+        _slices = tuple([slice(None)] for axis in range(len(_vsource.shape)))
+        self._slices = _slices
+        self._vsource = _vsource
+
+    def __getitem__(self, key):
+        dsource = deepcopy(self)
+        if not isinstance(key, tuple):
+            key = (key,)
+        for k in key:
+            if not isinstance(k, slice):
+                raise ValueError("only slicing is allowed.")
+        for axis, k in enumerate(key):
+            dsource._slices[axis].append(k)
+        return dsource
+
     def __array__(self):
         return self.to_layout().__array__()
 
     def __repr__(self):
         return f"DataSource: {to_human(self.nbytes)} ({self.dtype})"
 
     @property
+    def slices(self):
+        return tuple(
+            combine_slices(length, *slices)
+            for length, slices in zip(self._vsource.shape, self._slices)
+        )
+
+    @property
+    def vsource(self):
+        return self._vsource.__getitem__(self.slices)
+
+    @property
+    def shape(self):
+        return self.vsource.shape
+
+    @property
+    def dtype(self):
+        return self.vsource.dtype
+
+    @property
+    def path(self):
+        return self.vsource.path
+
+    @property
+    def name(self):
+        return self.vsource.name
+
+    @property
+    def id(self):
+        return self.vsource.id
+
+    @property
+    def sel(self):
+        return self.vsource.sel
+
+    @property
     def nbytes(self):
         return np.prod(self.shape) * self.dtype.itemsize
 
     def to_layout(self):
         layout = DataLayout(self.shape, self.dtype)
-        layout[...] = self
+        layout[...] = self.vsource
         return layout
 
     def to_dataset(self, file, name):
         self.to_layout().to_dataset(file, name)
 
-    def to_dict(self):
-        return {
-            "path": self.path,
-            "name": self.name,
-            "shape": self.shape,
-            "dtype": str(self.dtype),
-            "maxshape": self.maxshape,
-            "sel": self.sel._sel,
-        }
-
-    @classmethod
-    def from_dict(cls, dtc):
-        vsource = cls(
-            dtc["path"], dtc["name"], dtc["shape"], dtc["dtype"], dtc["maxshape"]
-        )
-        vsource.sel._sel = dtc["sel"]
-        return vsource
-
 
 class DataLayout(h5py.VirtualLayout):
     """
     A composite lazy array pointing toward multiple netCDF4/HDF5 files.
     """
 
     def __array__(self):
@@ -84,7 +123,19 @@
 def to_human(size):
     unit = {0: "B", 1: "K", 2: "M", 3: "G", 4: "T"}
     n = 0
     while size > 1024:
         size /= 1024
         n += 1
     return f"{size:.1f}{unit[n]}"
+
+
+def combine_slices(length, *slices):
+    r = range(length)
+    for s in slices:
+        r = r[s]
+    if len(r) == 0:
+        return slice(0)
+    elif r.stop < 0:
+        return slice(r.start, None, r.step)
+    else:
+        return slice(r.start, r.stop, r.step)
```


# Comparing `tmp/noiseflow-0.0.1a0.tar.gz` & `tmp/noiseflow-0.0.1a1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "noiseflow-0.0.1a0.tar", max compression
+gzip compressed data, was "noiseflow-0.0.1a1.tar", max compression
```

## Comparing `noiseflow-0.0.1a0.tar` & `noiseflow-0.0.1a1.tar`

### file list

```diff
@@ -1,48 +1,49 @@
--rw-r--r--   0        0        0    11357 2023-06-28 04:34:48.952123 noiseflow-0.0.1a0/LICENSE
--rw-r--r--   0        0        0     2376 2023-06-28 04:37:06.795543 noiseflow-0.0.1a0/README.md
--rw-r--r--   0        0        0     3408 2023-06-28 04:37:18.336283 noiseflow-0.0.1a0/build.py
--rw-r--r--   0        0        0      702 2023-06-28 04:37:37.994608 noiseflow-0.0.1a0/noiseflow/__init__.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:37.995878 noiseflow-0.0.1a0/noiseflow/app/__init__.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:37.996681 noiseflow-0.0.1a0/noiseflow/cc/__init__.py
--rw-r--r--   0        0        0    11738 2023-06-28 04:37:37.998982 noiseflow-0.0.1a0/noiseflow/cc/corrdata.py
--rw-r--r--   0        0        0    10160 2023-06-28 04:37:37.999829 noiseflow-0.0.1a0/noiseflow/cc/include/corr.hpp
--rw-r--r--   0        0        0    10099 2023-06-28 04:37:38.000182 noiseflow-0.0.1a0/noiseflow/cc/include/rfft.hpp
--rw-r--r--   0        0        0    11023 2023-06-28 04:37:38.000528 noiseflow-0.0.1a0/noiseflow/cc/include/stack.hpp
--rw-r--r--   0        0        0     8396 2023-06-28 04:37:38.000877 noiseflow-0.0.1a0/noiseflow/cc/include/utils.hpp
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.001208 noiseflow-0.0.1a0/noiseflow/cc/python/__init__.py
--rw-r--r--   0        0        0     6071 2023-06-28 04:37:38.002507 noiseflow-0.0.1a0/noiseflow/cc/python/corr.py
--rw-r--r--   0        0        0     5299 2023-06-28 04:37:38.002679 noiseflow-0.0.1a0/noiseflow/cc/python/rfft.py
--rw-r--r--   0        0        0    27254 2023-06-28 04:37:38.002871 noiseflow-0.0.1a0/noiseflow/cc/python/stack.py
--rw-r--r--   0        0        0     3310 2023-06-28 04:37:38.003179 noiseflow-0.0.1a0/noiseflow/cc/python/utils.py
--rw-r--r--   0        0        0     8127 2023-06-28 04:37:38.003381 noiseflow-0.0.1a0/noiseflow/cc/rfftdata.py
--rw-r--r--   0        0        0     5512 2023-06-28 04:37:38.003886 noiseflow-0.0.1a0/noiseflow/cc/src/pybind11.cpp
--rw-r--r--   0        0        0    37323 2023-06-28 04:37:38.004125 noiseflow-0.0.1a0/noiseflow/cc/stackdata.py
--rw-r--r--   0        0        0    10646 2023-06-28 04:37:38.004396 noiseflow-0.0.1a0/noiseflow/cc/utils_load.py
--rw-r--r--   0        0        0     1368 2023-06-28 04:37:38.004660 noiseflow-0.0.1a0/noiseflow/cc/utils_time.py
--rw-r--r--   0        0        0     8754 2023-06-28 04:37:38.004871 noiseflow-0.0.1a0/noiseflow/cc/wrapper.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.005404 noiseflow-0.0.1a0/noiseflow/client/__init__.py
--rw-r--r--   0        0        0     7840 2023-06-28 04:37:38.005648 noiseflow-0.0.1a0/noiseflow/client/client.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.005953 noiseflow-0.0.1a0/noiseflow/dispersion/__init__.py
--rw-r--r--   0        0        0       29 2023-06-28 04:37:38.006142 noiseflow-0.0.1a0/noiseflow/dispersion/app_dispersion.py
--rw-r--r--   0        0        0       27 2023-06-28 04:37:38.006416 noiseflow-0.0.1a0/noiseflow/dispersion/test.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.006792 noiseflow-0.0.1a0/noiseflow/dvv/__init__.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.006945 noiseflow-0.0.1a0/noiseflow/dvv/monitoring.py
--rw-r--r--   0        0        0      189 2023-06-28 04:37:38.007718 noiseflow-0.0.1a0/noiseflow/real_time/watch_dog.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.008340 noiseflow-0.0.1a0/noiseflow/signal/__init__.py
--rw-r--r--   0        0        0     2899 2023-06-28 04:37:38.010514 noiseflow-0.0.1a0/noiseflow/signal/include/decimate.hpp
--rw-r--r--   0        0        0     3291 2023-06-28 04:37:38.010804 noiseflow-0.0.1a0/noiseflow/signal/include/detrend.hpp
--rw-r--r--   0        0        0    12708 2023-06-28 04:37:38.011071 noiseflow-0.0.1a0/noiseflow/signal/include/filter.hpp
--rw-r--r--   0        0        0     4737 2023-06-28 04:37:38.011376 noiseflow-0.0.1a0/noiseflow/signal/include/taper.hpp
--rw-r--r--   0        0        0     1284 2023-06-28 04:37:38.011559 noiseflow-0.0.1a0/noiseflow/signal/include/utils.hpp
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.011873 noiseflow-0.0.1a0/noiseflow/signal/python/__init__.py
--rw-r--r--   0        0        0      747 2023-06-28 04:37:38.012044 noiseflow-0.0.1a0/noiseflow/signal/python/decimate.py
--rw-r--r--   0        0        0     2004 2023-06-28 04:37:38.012193 noiseflow-0.0.1a0/noiseflow/signal/python/detrend.py
--rw-r--r--   0        0        0     6813 2023-06-28 04:37:38.012352 noiseflow-0.0.1a0/noiseflow/signal/python/filter.py
--rw-r--r--   0        0        0     2917 2023-06-28 04:37:38.012507 noiseflow-0.0.1a0/noiseflow/signal/python/taper.py
--rw-r--r--   0        0        0     3263 2023-06-28 04:37:38.012663 noiseflow-0.0.1a0/noiseflow/signal/rawdata.py
--rw-r--r--   0        0        0     7355 2023-06-28 04:37:38.013154 noiseflow-0.0.1a0/noiseflow/signal/src/pybind11.cpp
--rw-r--r--   0        0        0    10121 2023-06-28 04:37:38.013311 noiseflow-0.0.1a0/noiseflow/signal/wrapper.py
--rw-r--r--   0        0        0        0 2023-06-28 04:37:38.013629 noiseflow-0.0.1a0/noiseflow/tests/__init__.py
--rw-r--r--   0        0        0      771 2023-06-28 05:17:15.340011 noiseflow-0.0.1a0/pyproject.toml
--rw-r--r--   0        0        0     3593 1970-01-01 00:00:00.000000 noiseflow-0.0.1a0/setup.py
--rw-r--r--   0        0        0     3148 1970-01-01 00:00:00.000000 noiseflow-0.0.1a0/PKG-INFO
+-rw-r--r--   0        0        0     5779 2023-06-28 04:37:18.124189 noiseflow-0.0.1a1/CMakeLists.txt
+-rw-r--r--   0        0        0    11357 2023-06-28 04:34:48.952123 noiseflow-0.0.1a1/LICENSE
+-rw-r--r--   0        0        0     2453 2023-06-28 05:49:42.040866 noiseflow-0.0.1a1/README.md
+-rw-r--r--   0        0        0     3408 2023-06-28 04:37:18.336283 noiseflow-0.0.1a1/build.py
+-rw-r--r--   0        0        0      702 2023-06-28 04:37:37.994608 noiseflow-0.0.1a1/noiseflow/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:37.995878 noiseflow-0.0.1a1/noiseflow/app/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:37.996681 noiseflow-0.0.1a1/noiseflow/cc/__init__.py
+-rw-r--r--   0        0        0    11738 2023-06-28 04:37:37.998982 noiseflow-0.0.1a1/noiseflow/cc/corrdata.py
+-rw-r--r--   0        0        0    10160 2023-06-28 04:37:37.999829 noiseflow-0.0.1a1/noiseflow/cc/include/corr.hpp
+-rw-r--r--   0        0        0    10099 2023-06-28 04:37:38.000182 noiseflow-0.0.1a1/noiseflow/cc/include/rfft.hpp
+-rw-r--r--   0        0        0    11023 2023-06-28 04:37:38.000528 noiseflow-0.0.1a1/noiseflow/cc/include/stack.hpp
+-rw-r--r--   0        0        0     8396 2023-06-28 04:37:38.000877 noiseflow-0.0.1a1/noiseflow/cc/include/utils.hpp
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.001208 noiseflow-0.0.1a1/noiseflow/cc/python/__init__.py
+-rw-r--r--   0        0        0     6071 2023-06-28 04:37:38.002507 noiseflow-0.0.1a1/noiseflow/cc/python/corr.py
+-rw-r--r--   0        0        0     5299 2023-06-28 04:37:38.002679 noiseflow-0.0.1a1/noiseflow/cc/python/rfft.py
+-rw-r--r--   0        0        0    27254 2023-06-28 04:37:38.002871 noiseflow-0.0.1a1/noiseflow/cc/python/stack.py
+-rw-r--r--   0        0        0     3310 2023-06-28 04:37:38.003179 noiseflow-0.0.1a1/noiseflow/cc/python/utils.py
+-rw-r--r--   0        0        0     8127 2023-06-28 04:37:38.003381 noiseflow-0.0.1a1/noiseflow/cc/rfftdata.py
+-rw-r--r--   0        0        0     5512 2023-06-28 04:37:38.003886 noiseflow-0.0.1a1/noiseflow/cc/src/pybind11.cpp
+-rw-r--r--   0        0        0    37323 2023-06-28 04:37:38.004125 noiseflow-0.0.1a1/noiseflow/cc/stackdata.py
+-rw-r--r--   0        0        0    10646 2023-06-28 04:37:38.004396 noiseflow-0.0.1a1/noiseflow/cc/utils_load.py
+-rw-r--r--   0        0        0     1368 2023-06-28 04:37:38.004660 noiseflow-0.0.1a1/noiseflow/cc/utils_time.py
+-rw-r--r--   0        0        0     8754 2023-06-28 04:37:38.004871 noiseflow-0.0.1a1/noiseflow/cc/wrapper.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.005404 noiseflow-0.0.1a1/noiseflow/client/__init__.py
+-rw-r--r--   0        0        0     7840 2023-06-28 04:37:38.005648 noiseflow-0.0.1a1/noiseflow/client/client.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.005953 noiseflow-0.0.1a1/noiseflow/dispersion/__init__.py
+-rw-r--r--   0        0        0       29 2023-06-28 04:37:38.006142 noiseflow-0.0.1a1/noiseflow/dispersion/app_dispersion.py
+-rw-r--r--   0        0        0       27 2023-06-28 04:37:38.006416 noiseflow-0.0.1a1/noiseflow/dispersion/test.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.006792 noiseflow-0.0.1a1/noiseflow/dvv/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.006945 noiseflow-0.0.1a1/noiseflow/dvv/monitoring.py
+-rw-r--r--   0        0        0      189 2023-06-28 04:37:38.007718 noiseflow-0.0.1a1/noiseflow/real_time/watch_dog.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.008340 noiseflow-0.0.1a1/noiseflow/signal/__init__.py
+-rw-r--r--   0        0        0     2899 2023-06-28 04:37:38.010514 noiseflow-0.0.1a1/noiseflow/signal/include/decimate.hpp
+-rw-r--r--   0        0        0     3291 2023-06-28 04:37:38.010804 noiseflow-0.0.1a1/noiseflow/signal/include/detrend.hpp
+-rw-r--r--   0        0        0    12708 2023-06-28 04:37:38.011071 noiseflow-0.0.1a1/noiseflow/signal/include/filter.hpp
+-rw-r--r--   0        0        0     4737 2023-06-28 04:37:38.011376 noiseflow-0.0.1a1/noiseflow/signal/include/taper.hpp
+-rw-r--r--   0        0        0     1284 2023-06-28 04:37:38.011559 noiseflow-0.0.1a1/noiseflow/signal/include/utils.hpp
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.011873 noiseflow-0.0.1a1/noiseflow/signal/python/__init__.py
+-rw-r--r--   0        0        0      747 2023-06-28 04:37:38.012044 noiseflow-0.0.1a1/noiseflow/signal/python/decimate.py
+-rw-r--r--   0        0        0     2004 2023-06-28 04:37:38.012193 noiseflow-0.0.1a1/noiseflow/signal/python/detrend.py
+-rw-r--r--   0        0        0     6813 2023-06-28 04:37:38.012352 noiseflow-0.0.1a1/noiseflow/signal/python/filter.py
+-rw-r--r--   0        0        0     2917 2023-06-28 04:37:38.012507 noiseflow-0.0.1a1/noiseflow/signal/python/taper.py
+-rw-r--r--   0        0        0     3263 2023-06-28 04:37:38.012663 noiseflow-0.0.1a1/noiseflow/signal/rawdata.py
+-rw-r--r--   0        0        0     7355 2023-06-28 04:37:38.013154 noiseflow-0.0.1a1/noiseflow/signal/src/pybind11.cpp
+-rw-r--r--   0        0        0    10121 2023-06-28 04:37:38.013311 noiseflow-0.0.1a1/noiseflow/signal/wrapper.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:37:38.013629 noiseflow-0.0.1a1/noiseflow/tests/__init__.py
+-rw-r--r--   0        0        0      909 2023-06-28 05:52:58.512625 noiseflow-0.0.1a1/pyproject.toml
+-rw-r--r--   0        0        0     3827 1970-01-01 00:00:00.000000 noiseflow-0.0.1a1/setup.py
+-rw-r--r--   0        0        0     3463 1970-01-01 00:00:00.000000 noiseflow-0.0.1a1/PKG-INFO
```

### Comparing `noiseflow-0.0.1a0/LICENSE` & `noiseflow-0.0.1a1/LICENSE`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/README.md` & `noiseflow-0.0.1a1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -92,14 +92,17 @@
 module load Clang/13.0.1
 export CXX=clang++
 python setup.py install
 ```
 
 ```bash
 conda install -c conda-forge stockwell
+
+NOISEFLOW_USE_CPP=1 pip install --no-binary :all: noiseflow --no-cache-dir
+
 ```
 
 
 
 ##
 Noiseflow is dual-licensed, available under both commercial and apache license.
```

### Comparing `noiseflow-0.0.1a0/build.py` & `noiseflow-0.0.1a1/build.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/__init__.py` & `noiseflow-0.0.1a1/noiseflow/__init__.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/corrdata.py` & `noiseflow-0.0.1a1/noiseflow/cc/corrdata.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/include/corr.hpp` & `noiseflow-0.0.1a1/noiseflow/cc/include/corr.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/include/rfft.hpp` & `noiseflow-0.0.1a1/noiseflow/cc/include/rfft.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/include/stack.hpp` & `noiseflow-0.0.1a1/noiseflow/cc/include/stack.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/include/utils.hpp` & `noiseflow-0.0.1a1/noiseflow/cc/include/utils.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/python/corr.py` & `noiseflow-0.0.1a1/noiseflow/cc/python/corr.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/python/rfft.py` & `noiseflow-0.0.1a1/noiseflow/cc/python/rfft.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/python/stack.py` & `noiseflow-0.0.1a1/noiseflow/cc/python/stack.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/python/utils.py` & `noiseflow-0.0.1a1/noiseflow/cc/python/utils.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/rfftdata.py` & `noiseflow-0.0.1a1/noiseflow/cc/rfftdata.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/src/pybind11.cpp` & `noiseflow-0.0.1a1/noiseflow/cc/src/pybind11.cpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/stackdata.py` & `noiseflow-0.0.1a1/noiseflow/cc/stackdata.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/utils_load.py` & `noiseflow-0.0.1a1/noiseflow/cc/utils_load.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/utils_time.py` & `noiseflow-0.0.1a1/noiseflow/cc/utils_time.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/cc/wrapper.py` & `noiseflow-0.0.1a1/noiseflow/cc/wrapper.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/client/client.py` & `noiseflow-0.0.1a1/noiseflow/client/client.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/include/decimate.hpp` & `noiseflow-0.0.1a1/noiseflow/signal/include/decimate.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/include/detrend.hpp` & `noiseflow-0.0.1a1/noiseflow/signal/include/detrend.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/include/filter.hpp` & `noiseflow-0.0.1a1/noiseflow/signal/include/filter.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/include/taper.hpp` & `noiseflow-0.0.1a1/noiseflow/signal/include/taper.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/include/utils.hpp` & `noiseflow-0.0.1a1/noiseflow/signal/include/utils.hpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/python/decimate.py` & `noiseflow-0.0.1a1/noiseflow/signal/python/decimate.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/python/detrend.py` & `noiseflow-0.0.1a1/noiseflow/signal/python/detrend.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/python/filter.py` & `noiseflow-0.0.1a1/noiseflow/signal/python/filter.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/python/taper.py` & `noiseflow-0.0.1a1/noiseflow/signal/python/taper.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/rawdata.py` & `noiseflow-0.0.1a1/noiseflow/signal/rawdata.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/src/pybind11.cpp` & `noiseflow-0.0.1a1/noiseflow/signal/src/pybind11.cpp`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/noiseflow/signal/wrapper.py` & `noiseflow-0.0.1a1/noiseflow/signal/wrapper.py`

 * *Files identical despite different names*

### Comparing `noiseflow-0.0.1a0/pyproject.toml` & `noiseflow-0.0.1a1/pyproject.toml`

 * *Files 22% similar despite different names*

```diff
@@ -1,24 +1,31 @@
 [tool.poetry]
 name = "noiseflow"
-version = "0.0.1a"
+version = "0.0.1a1"
 description = "An ambient noise package"
 authors = ["Fu Yin <oucyinfu@gmail.com>"]
 license = "BSD"
 readme = "README.md"
+include = ["CMakeLists.txt"]
 
 [tool.poetry.dependencies]
 python = ">=3.9,<3.13"
 numpy = "^1.24.0"
 matplotlib = "^3.7.1"
 scipy = "^1.11.0"
 obspy = "^1.4.0"
 stockwell = "^1.1"
 setuptools = "^58.0.4"
 numba = "^0.57.1"
+h5py = "^3.9.0"
+tqdm = "^4.65.0"
+joblib = "^1.2.0"
+tslearn = "^0.5.3.2"
+faker = "^18.11.2"
+retry = "^0.9.2"
 
 [tool.poetry.group.dev.dependencies]
 numpy = "^1.24.0"
 scipy = "^1.11.0"
 matplotlib = "^3.7.1"
 setuptools = "^58.0.4"
```

### Comparing `noiseflow-0.0.1a0/setup.py` & `noiseflow-0.0.1a1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -16,27 +16,33 @@
 
 package_data = \
 {'': ['*'],
  'noiseflow.cc': ['include/*', 'src/*'],
  'noiseflow.signal': ['include/*', 'src/*']}
 
 install_requires = \
-['matplotlib>=3.7.1,<4.0.0',
+['faker>=18.11.2,<19.0.0',
+ 'h5py>=3.9.0,<4.0.0',
+ 'joblib>=1.2.0,<2.0.0',
+ 'matplotlib>=3.7.1,<4.0.0',
  'numba>=0.57.1,<0.58.0',
  'numpy>=1.24.0,<2.0.0',
  'obspy>=1.4.0,<2.0.0',
+ 'retry>=0.9.2,<0.10.0',
  'scipy>=1.11.0,<2.0.0',
  'setuptools>=58.0.4,<59.0.0',
- 'stockwell>=1.1,<2.0']
+ 'stockwell>=1.1,<2.0',
+ 'tqdm>=4.65.0,<5.0.0',
+ 'tslearn>=0.5.3.2,<0.6.0.0']
 
 setup_kwargs = {
     'name': 'noiseflow',
-    'version': '0.0.1a0',
+    'version': '0.0.1a1',
     'description': 'An ambient noise package',
-    'long_description': '# NoiseFlow\n\n\n## Prerequisites\n\nNoiseFlow now supports `Clang` and `GCC` compiler in MacOS and Linux system separately, and all installation processes are under the `conda` environment, and we recommend to use miniconda. Make sure to install the following pre-packages before installing noiseflow:\n\n\nIf you use `Clang` in Mac, please install `OpenMP` via `brew` as following:\n\n```bash\nbrew install openmp\n```\n\nAnd use `pip` and `conda` to install the following packages:\n\n```bash\npip install joblib\n\nconda install -c conda-forge numpy scipy matplotlib \nconda install -c conda-forge obspy\nconda install -c conda-forge fftw\nconda install -c conda-forge pybind11\nconda install -c conda-forge xtensor xsimd xtl xtensor-blas xtensor-python\nconda install -c conda-forge xtensor-fftw  #(usually failed at most time)  \n```\n\nThe `xtensor-fftw` and `KFR` need to be installed from source, first download them:\n\n\n```bash\ngit clone https://github.com/OUCyf/noiseflow.git\ncd noiseflow\ngit submodule init\ngit submodule update\n```\n\n\n\nNote the `xtensor-fftw` do not support M1 chip, and if it is failed to install via conda, you can install it from source into conda environment as `$CONDA_PREFIX`\n\n```bash\ncd ./extern/xtensor-fftw\nmkdir build && cd build\ncmake .. -DCMAKE_INSTALL_PREFIX=$CONDA_PREFIX\nmake install\n```\n\n\n\nThe `KFR` package is C++ DSP framework, should be installed in `./extern/kfr` from source\n\n```bash\ncd ./extern/kfr\nmkdir build && cd build\ncmake ..\nmake install\n```\n\n\n\n\n## Installation\n\nNow you can install `NoiseFlow`. If you use `MacOS`, please make sure to use Clang as the complier\n\n```bash\nexport CXX=clang++\n# unset CXX\npython setup.py install\n```\n\nIf you use `Linux`, please use GCC as the compiler\n\n```bash\nexport CXX=g++-13\npython setup.py install\n```\n\n\nIf you use `HPC` with `module` tool, you can use both Clang and GCC, for example using NOTS in Rice University.\n\n```bash\n# use gcc\nmodule load GCC/13.1.0\nexport CXX=g++\npython setup.py install\nINCLUDE_CMAKE_EXTENSION=1 pip install .\n\n# use clang\nmodule load GCCcore/11.2.0\nmodule load Clang/13.0.1\nexport CXX=clang++\npython setup.py install\n```\n\n```bash\nconda install -c conda-forge stockwell\n```\n\n\n\n##\nNoiseflow is dual-licensed, available under both commercial and apache license.\n\nIf you want to use noiseflow in a commercial product or a closed-source project, you need to purchase a Commercial License.\n',
+    'long_description': '# NoiseFlow\n\n\n## Prerequisites\n\nNoiseFlow now supports `Clang` and `GCC` compiler in MacOS and Linux system separately, and all installation processes are under the `conda` environment, and we recommend to use miniconda. Make sure to install the following pre-packages before installing noiseflow:\n\n\nIf you use `Clang` in Mac, please install `OpenMP` via `brew` as following:\n\n```bash\nbrew install openmp\n```\n\nAnd use `pip` and `conda` to install the following packages:\n\n```bash\npip install joblib\n\nconda install -c conda-forge numpy scipy matplotlib \nconda install -c conda-forge obspy\nconda install -c conda-forge fftw\nconda install -c conda-forge pybind11\nconda install -c conda-forge xtensor xsimd xtl xtensor-blas xtensor-python\nconda install -c conda-forge xtensor-fftw  #(usually failed at most time)  \n```\n\nThe `xtensor-fftw` and `KFR` need to be installed from source, first download them:\n\n\n```bash\ngit clone https://github.com/OUCyf/noiseflow.git\ncd noiseflow\ngit submodule init\ngit submodule update\n```\n\n\n\nNote the `xtensor-fftw` do not support M1 chip, and if it is failed to install via conda, you can install it from source into conda environment as `$CONDA_PREFIX`\n\n```bash\ncd ./extern/xtensor-fftw\nmkdir build && cd build\ncmake .. -DCMAKE_INSTALL_PREFIX=$CONDA_PREFIX\nmake install\n```\n\n\n\nThe `KFR` package is C++ DSP framework, should be installed in `./extern/kfr` from source\n\n```bash\ncd ./extern/kfr\nmkdir build && cd build\ncmake ..\nmake install\n```\n\n\n\n\n## Installation\n\nNow you can install `NoiseFlow`. If you use `MacOS`, please make sure to use Clang as the complier\n\n```bash\nexport CXX=clang++\n# unset CXX\npython setup.py install\n```\n\nIf you use `Linux`, please use GCC as the compiler\n\n```bash\nexport CXX=g++-13\npython setup.py install\n```\n\n\nIf you use `HPC` with `module` tool, you can use both Clang and GCC, for example using NOTS in Rice University.\n\n```bash\n# use gcc\nmodule load GCC/13.1.0\nexport CXX=g++\npython setup.py install\nINCLUDE_CMAKE_EXTENSION=1 pip install .\n\n# use clang\nmodule load GCCcore/11.2.0\nmodule load Clang/13.0.1\nexport CXX=clang++\npython setup.py install\n```\n\n```bash\nconda install -c conda-forge stockwell\n\nNOISEFLOW_USE_CPP=1 pip install --no-binary :all: noiseflow --no-cache-dir\n\n```\n\n\n\n##\nNoiseflow is dual-licensed, available under both commercial and apache license.\n\nIf you want to use noiseflow in a commercial product or a closed-source project, you need to purchase a Commercial License.\n',
     'author': 'Fu Yin',
     'author_email': 'oucyinfu@gmail.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
     'packages': packages,
     'package_data': package_data,
```

### Comparing `noiseflow-0.0.1a0/PKG-INFO` & `noiseflow-0.0.1a1/PKG-INFO`

 * *Files 18% similar despite different names*

```diff
@@ -1,28 +1,34 @@
 Metadata-Version: 2.1
 Name: noiseflow
-Version: 0.0.1a0
+Version: 0.0.1a1
 Summary: An ambient noise package
 License: BSD
 Author: Fu Yin
 Author-email: oucyinfu@gmail.com
 Requires-Python: >=3.9,<3.13
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: cpp
+Requires-Dist: faker (>=18.11.2,<19.0.0)
+Requires-Dist: h5py (>=3.9.0,<4.0.0)
+Requires-Dist: joblib (>=1.2.0,<2.0.0)
 Requires-Dist: matplotlib (>=3.7.1,<4.0.0)
 Requires-Dist: numba (>=0.57.1,<0.58.0)
 Requires-Dist: numpy (>=1.24.0,<2.0.0)
 Requires-Dist: obspy (>=1.4.0,<2.0.0)
+Requires-Dist: retry (>=0.9.2,<0.10.0)
 Requires-Dist: scipy (>=1.11.0,<2.0.0)
 Requires-Dist: setuptools (>=58.0.4,<59.0.0)
 Requires-Dist: stockwell (>=1.1,<2.0)
+Requires-Dist: tqdm (>=4.65.0,<5.0.0)
+Requires-Dist: tslearn (>=0.5.3.2,<0.6.0.0)
 Description-Content-Type: text/markdown
 
 # NoiseFlow
 
 
 ## Prerequisites
 
@@ -115,14 +121,17 @@
 module load Clang/13.0.1
 export CXX=clang++
 python setup.py install
 ```
 
 ```bash
 conda install -c conda-forge stockwell
+
+NOISEFLOW_USE_CPP=1 pip install --no-binary :all: noiseflow --no-cache-dir
+
 ```
 
 
 
 ##
 Noiseflow is dual-licensed, available under both commercial and apache license.
```


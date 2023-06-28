# Comparing `tmp/spright-23.6.27.tar.gz` & `tmp/spright-23.6.28.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "spright-23.6.27.tar", last modified: Tue Jun 27 21:32:34 2023, max compression
+gzip compressed data, was "spright-23.6.28.tar", last modified: Wed Jun 28 09:35:42 2023, max compression
```

## Comparing `spright-23.6.27.tar` & `spright-23.6.28.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-27 21:32:34.409185 spright-23.6.27/
--rw-r--r--   0 hannu     (1000) hannu     (1000)    35149 2022-10-08 15:41:02.000000 spright-23.6.27/LICENSE
--rw-rw-r--   0 hannu     (1000) hannu     (1000)       19 2022-10-24 17:07:23.000000 spright-23.6.27/MANIFEST.in
--rw-rw-r--   0 hannu     (1000) hannu     (1000)      655 2023-06-27 21:32:34.409185 spright-23.6.27/PKG-INFO
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     1338 2023-06-27 21:30:33.000000 spright-23.6.27/README.md
--rw-rw-r--   0 hannu     (1000) hannu     (1000)      976 2023-06-27 21:32:19.000000 spright-23.6.27/pyproject.toml
--rw-rw-r--   0 hannu     (1000) hannu     (1000)       38 2023-06-27 21:32:34.409185 spright-23.6.27/setup.cfg
-drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-27 21:32:34.409185 spright-23.6.27/spright/
--rw-rw-r--   0 hannu     (1000) hannu     (1000)      113 2023-06-16 11:10:55.000000 spright-23.6.27/spright/__init__.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)      686 2023-06-16 11:10:55.000000 spright-23.6.27/spright/core.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     4221 2023-06-27 21:30:33.000000 spright-23.6.27/spright/distribution.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     1740 2023-06-16 11:10:55.000000 spright-23.6.27/spright/io.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     3119 2023-06-16 11:10:55.000000 spright-23.6.27/spright/lpf.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)    10980 2023-06-27 21:30:33.000000 spright-23.6.27/spright/model.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     3147 2023-06-16 11:10:55.000000 spright-23.6.27/spright/rdmodel.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     7543 2023-06-27 21:30:33.000000 spright-23.6.27/spright/relationmap.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)    12088 2023-06-27 21:30:33.000000 spright-23.6.27/spright/rmestimator.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)     5803 2023-06-27 21:30:33.000000 spright-23.6.27/spright/rmrelation.py
--rw-rw-r--   0 hannu     (1000) hannu     (1000)       67 2023-06-16 11:10:55.000000 spright-23.6.27/spright/version.py
-drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-27 21:32:34.409185 spright-23.6.27/spright.egg-info/
--rw-rw-r--   0 hannu     (1000) hannu     (1000)      655 2023-06-27 21:32:33.000000 spright-23.6.27/spright.egg-info/PKG-INFO
--rw-rw-r--   0 hannu     (1000) hannu     (1000)      437 2023-06-27 21:32:33.000000 spright-23.6.27/spright.egg-info/SOURCES.txt
--rw-rw-r--   0 hannu     (1000) hannu     (1000)        1 2023-06-27 21:32:33.000000 spright-23.6.27/spright.egg-info/dependency_links.txt
--rw-rw-r--   0 hannu     (1000) hannu     (1000)       90 2023-06-27 21:32:33.000000 spright-23.6.27/spright.egg-info/requires.txt
--rw-rw-r--   0 hannu     (1000) hannu     (1000)        8 2023-06-27 21:32:33.000000 spright-23.6.27/spright.egg-info/top_level.txt
-drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-27 21:32:34.409185 spright-23.6.27/tests/
--rw-rw-r--   0 hannu     (1000) hannu     (1000)       58 2023-06-16 16:52:08.000000 spright-23.6.27/tests/test_installation.py
+drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-28 09:35:42.440823 spright-23.6.28/
+-rw-r--r--   0 hannu     (1000) hannu     (1000)    35149 2022-10-08 15:41:02.000000 spright-23.6.28/LICENSE
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)       19 2022-10-24 17:07:23.000000 spright-23.6.28/MANIFEST.in
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)      655 2023-06-28 09:35:42.440823 spright-23.6.28/PKG-INFO
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     1338 2023-06-27 21:30:33.000000 spright-23.6.28/README.md
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)      976 2023-06-28 09:35:21.000000 spright-23.6.28/pyproject.toml
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)       38 2023-06-28 09:35:42.440823 spright-23.6.28/setup.cfg
+drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-28 09:35:42.396823 spright-23.6.28/spright/
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)      113 2023-06-16 11:10:55.000000 spright-23.6.28/spright/__init__.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)      686 2023-06-16 11:10:55.000000 spright-23.6.28/spright/core.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     4221 2023-06-27 21:30:33.000000 spright-23.6.28/spright/distribution.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     1740 2023-06-16 11:10:55.000000 spright-23.6.28/spright/io.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     3119 2023-06-16 11:10:55.000000 spright-23.6.28/spright/lpf.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)    10980 2023-06-27 21:30:33.000000 spright-23.6.28/spright/model.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     3147 2023-06-16 11:10:55.000000 spright-23.6.28/spright/rdmodel.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     7543 2023-06-27 21:30:33.000000 spright-23.6.28/spright/relationmap.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)    12088 2023-06-27 21:30:33.000000 spright-23.6.28/spright/rmestimator.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)     7467 2023-06-28 09:35:03.000000 spright-23.6.28/spright/rmrelation.py
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)       67 2023-06-16 11:10:55.000000 spright-23.6.28/spright/version.py
+drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-28 09:35:42.424823 spright-23.6.28/spright.egg-info/
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)      655 2023-06-28 09:35:42.000000 spright-23.6.28/spright.egg-info/PKG-INFO
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)      437 2023-06-28 09:35:42.000000 spright-23.6.28/spright.egg-info/SOURCES.txt
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)        1 2023-06-28 09:35:42.000000 spright-23.6.28/spright.egg-info/dependency_links.txt
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)       90 2023-06-28 09:35:42.000000 spright-23.6.28/spright.egg-info/requires.txt
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)        8 2023-06-28 09:35:42.000000 spright-23.6.28/spright.egg-info/top_level.txt
+drwxrwxr-x   0 hannu     (1000) hannu     (1000)        0 2023-06-28 09:35:42.424823 spright-23.6.28/tests/
+-rw-rw-r--   0 hannu     (1000) hannu     (1000)       58 2023-06-16 16:52:08.000000 spright-23.6.28/tests/test_installation.py
```

### Comparing `spright-23.6.27/LICENSE` & `spright-23.6.28/LICENSE`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/PKG-INFO` & `spright-23.6.28/PKG-INFO`

 * *Files 13% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: spright
-Version: 23.6.27
+Version: 23.6.28
 Summary: Bayesian radius-density-mass relation for small planets.
 Author-email: Hannu Parviainen <hpparvi@gmail.com>
 Project-URL: homepage, https://github.com/hpparvi/spright
 Keywords: astronomy,astrophysics,exoplanets
 Classifier: Topic :: Scientific/Engineering
 Classifier: Intended Audience :: Science/Research
 Classifier: Intended Audience :: Developers
```

### Comparing `spright-23.6.27/README.md` & `spright-23.6.28/README.md`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/pyproject.toml` & `spright-23.6.28/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "spright"
-version = "23.06.27"
+version = "23.06.28"
 description = 'Bayesian radius-density-mass relation for small planets.'
 authors=[{name='Hannu Parviainen', email='hpparvi@gmail.com'}]
 classifiers=[
   "Topic :: Scientific/Engineering",
   "Intended Audience :: Science/Research",
   "Intended Audience :: Developers",
   "Development Status :: 5 - Production/Stable",
```

### Comparing `spright-23.6.27/spright/core.py` & `spright-23.6.28/spright/core.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/distribution.py` & `spright-23.6.28/spright/distribution.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/io.py` & `spright-23.6.28/spright/io.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/lpf.py` & `spright-23.6.28/spright/lpf.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/model.py` & `spright-23.6.28/spright/model.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/rdmodel.py` & `spright-23.6.28/spright/rdmodel.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/relationmap.py` & `spright-23.6.28/spright/relationmap.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/rmestimator.py` & `spright-23.6.28/spright/rmestimator.py`

 * *Files identical despite different names*

### Comparing `spright-23.6.27/spright/rmrelation.py` & `spright-23.6.28/spright/rmrelation.py`

 * *Files 18% similar despite different names*

```diff
@@ -52,14 +52,55 @@
         with pf.open(fname) as f:
             self.rdmap = RDRelationMap.load(fname)
             self.rmmap = RMRelationMap.load(fname)
             self.posterior_samples = Table.read(fname, 10).to_pandas()
             self.catalog = Table.read(fname, 11).to_pandas()
             self.rdsamples = Table.read(fname, 12).to_pandas()
 
+
+    def sample(self, quantity: str, radius: oprq = None, mass: oprq = None,
+               mstar: oprq = None, period: oprq = None, ecc: oprq = None,
+               nsamples: int = 5000) -> Distribution:
+        """
+
+        Parameters
+        ----------
+        quantity: {'radius', 'density', 'mass', 'k'}
+            Returned quantity.
+        radius
+            Planet radius either as a single float or as a tuple with radius and its uncertainty.
+        mass
+            Planet mass either as a single float or as a tuple with radius and its uncertainty.
+        mstar
+            Stellar mass either as a single float or as a tuple with radius and its uncertainty.
+        period
+            Orbital period of the planet either as a single float or as a tuple with radius and its uncertainty.
+        ecc
+            Planet's orbital eccentricity either as a single float or as a tuple with radius and its uncertainty.
+        nsamples
+            Number of samples to return.
+
+        Returns
+        -------
+        ndarray
+            Samples from either the density or mass posterior given the planet radius.
+        """
+        qs = ('radius', 'density', 'mass', 'k')
+        if quantity not in qs:
+            raise ValueError(f"Quantity has to be one of {qs}")
+
+        if quantity == 'density':
+            return self.predict_density(radius, nsamples)
+        elif quantity == 'mass':
+            return self.predict_mass(radius, nsamples)
+        elif quantity == 'k':
+            return self.predict_rv_semi_amplitude(radius, period, mstar, ecc, nsamples)
+        if quantity == 'radius':
+            return self.predict_radius(mass, nsamples)
+
     def predict_density(self, radius: prq, nsamples: int = 5000) -> Distribution:
         """
 
         Parameters
         ----------
         radius
             Planet radius either as a ufloat, a single float or as a tuple with radius and its uncertainty.
```

### Comparing `spright-23.6.27/spright.egg-info/PKG-INFO` & `spright-23.6.28/spright.egg-info/PKG-INFO`

 * *Files 13% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: spright
-Version: 23.6.27
+Version: 23.6.28
 Summary: Bayesian radius-density-mass relation for small planets.
 Author-email: Hannu Parviainen <hpparvi@gmail.com>
 Project-URL: homepage, https://github.com/hpparvi/spright
 Keywords: astronomy,astrophysics,exoplanets
 Classifier: Topic :: Scientific/Engineering
 Classifier: Intended Audience :: Science/Research
 Classifier: Intended Audience :: Developers
```


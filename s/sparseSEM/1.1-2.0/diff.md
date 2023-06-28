# Comparing `tmp/sparseSEM-1.1.tar.gz` & `tmp/sparseSEM-2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sparseSEM-1.1.tar", last modified: Wed May 24 20:33:07 2023, max compression
+gzip compressed data, was "sparseSEM-2.0.tar", last modified: Wed Jun 28 02:43:37 2023, max compression
```

## Comparing `sparseSEM-1.1.tar` & `sparseSEM-2.0.tar`

### file list

```diff
@@ -1,40 +1,42 @@
-drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-05-24 20:33:07.020300 sparseSEM-1.1/
--rw-r--r--   0 anhui      (501) staff       (20)       52 2023-05-11 03:19:57.000000 sparseSEM-1.1/MANIFEST.in
--rw-r--r--   0 anhui      (501) staff       (20)     3243 2023-05-24 20:33:07.019832 sparseSEM-1.1/PKG-INFO
--rw-r--r--   0 anhui      (501) staff       (20)     2211 2023-05-12 03:20:51.000000 sparseSEM-1.1/README.md
-drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-05-24 20:33:06.995738 sparseSEM-1.1/data/
--rw-r--r--   0 anhui      (501) staff       (20)     2393 2023-04-25 02:30:52.000000 sparseSEM-1.1/data/B.csv
--rw-r--r--   0 anhui      (501) staff       (20)    13436 2023-04-19 01:21:12.000000 sparseSEM-1.1/data/Missing.csv
--rw-r--r--   0 anhui      (501) staff       (20)    13436 2023-04-19 01:21:08.000000 sparseSEM-1.1/data/X.csv
--rw-r--r--   0 anhui      (501) staff       (20)    62636 2023-04-19 01:21:05.000000 sparseSEM-1.1/data/Y.csv
-drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-05-24 20:33:07.009626 sparseSEM-1.1/doc/
--rw-r--r--   0 anhui      (501) staff       (20)     6148 2023-04-27 02:57:56.000000 sparseSEM-1.1/doc/.DS_Store
--rw-r--r--   0 anhui      (501) staff       (20)   173524 2023-04-17 18:15:54.000000 sparseSEM-1.1/doc/Fig1_nCPU.png
--rw-r--r--   0 anhui      (501) staff       (20)   369870 2023-04-17 18:15:54.000000 sparseSEM-1.1/doc/Fig2_sigma01.png
--rw-r--r--   0 anhui      (501) staff       (20)   380492 2023-04-17 18:15:54.000000 sparseSEM-1.1/doc/Fig3_sigma05.png
--rwxr-xr-x   0 anhui      (501) staff       (20)  1989713 2023-04-17 18:15:54.000000 sparseSEM-1.1/doc/Fig4_cisTransNetworkYeast_clusters_manualAdjusted_GOterm.jpg
--rwxr-xr-x   0 anhui      (501) staff       (20)   928929 2023-04-17 18:15:54.000000 sparseSEM-1.1/doc/Fig5_yeast_grn_genome_biology.png
--rw-r--r--   0 anhui      (501) staff       (20)    37882 2023-04-18 23:35:33.000000 sparseSEM-1.1/doc/sparseSEM.md
--rw-r--r--   0 anhui      (501) staff       (20)   909391 2023-05-05 02:24:33.000000 sparseSEM-1.1/doc/sparseSEM.pdf
--rw-r--r--   0 anhui      (501) staff       (20)   166880 2023-04-17 19:32:38.000000 sparseSEM-1.1/doc/table1_data.png
--rw-r--r--   0 anhui      (501) staff       (20)   281918 2023-04-17 19:56:05.000000 sparseSEM-1.1/doc/table2_data.png
--rw-r--r--   0 anhui      (501) staff       (20)   144048 2023-04-17 19:57:17.000000 sparseSEM-1.1/doc/table3_data.png
--rw-r--r--   0 anhui      (501) staff       (20)       38 2023-05-24 20:33:07.020508 sparseSEM-1.1/setup.cfg
--rw-r--r--   0 anhui      (501) staff       (20)     2279 2023-05-24 20:33:04.000000 sparseSEM-1.1/setup.py
-drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-05-24 20:33:07.013117 sparseSEM-1.1/sparseSEM/
--rw-r--r--   0 anhui      (501) staff       (20)      479 2023-05-02 18:28:38.000000 sparseSEM-1.1/sparseSEM/__init__.py
--rw-r--r--   0 anhui      (501) staff       (20)     8064 2023-05-16 02:29:32.000000 sparseSEM-1.1/sparseSEM/elasticNetSML.py
--rw-r--r--   0 anhui      (501) staff       (20)     8684 2023-05-05 02:30:30.000000 sparseSEM-1.1/sparseSEM/elasticNetSMLcv.py
--rw-r--r--   0 anhui      (501) staff       (20)     7919 2023-05-05 02:30:30.000000 sparseSEM-1.1/sparseSEM/elasticNetSMLpoint.py
--rw-r--r--   0 anhui      (501) staff       (20)      911 2023-04-25 02:24:54.000000 sparseSEM-1.1/sparseSEM/loadSEMlib.py
--rwxr-xr-x   0 anhui      (501) staff       (20)   100424 2023-05-03 02:42:08.000000 sparseSEM-1.1/sparseSEM/sparseSEM.cpython-310-darwin.so
-drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-05-24 20:33:07.018810 sparseSEM-1.1/sparseSEM/src/
--rw-r--r--   0 anhui      (501) staff       (20)    41900 2023-04-23 02:55:12.000000 sparseSEM-1.1/sparseSEM/src/lassoSEM.c
--rw-r--r--   0 anhui      (501) staff       (20)     1550 2023-04-17 14:36:00.000000 sparseSEM-1.1/sparseSEM/src/lassoSEM.h
--rw-r--r--   0 anhui      (501) staff       (20)    90448 2023-05-03 02:40:40.000000 sparseSEM-1.1/sparseSEM/src/lassoSMLv11beta.c
-drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-05-24 20:33:07.016772 sparseSEM-1.1/sparseSEM.egg-info/
--rw-r--r--   0 anhui      (501) staff       (20)     3243 2023-05-24 20:33:06.000000 sparseSEM-1.1/sparseSEM.egg-info/PKG-INFO
--rw-r--r--   0 anhui      (501) staff       (20)      774 2023-05-24 20:33:06.000000 sparseSEM-1.1/sparseSEM.egg-info/SOURCES.txt
--rw-r--r--   0 anhui      (501) staff       (20)        1 2023-05-24 20:33:06.000000 sparseSEM-1.1/sparseSEM.egg-info/dependency_links.txt
--rw-r--r--   0 anhui      (501) staff       (20)       33 2023-05-24 20:33:06.000000 sparseSEM-1.1/sparseSEM.egg-info/requires.txt
--rw-r--r--   0 anhui      (501) staff       (20)       10 2023-05-24 20:33:06.000000 sparseSEM-1.1/sparseSEM.egg-info/top_level.txt
+drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-06-28 02:43:37.116677 sparseSEM-2.0/
+-rw-r--r--   0 anhui      (501) staff       (20)       52 2023-05-11 03:19:57.000000 sparseSEM-2.0/MANIFEST.in
+-rw-r--r--   0 anhui      (501) staff       (20)     3803 2023-06-28 02:43:37.115990 sparseSEM-2.0/PKG-INFO
+-rw-r--r--   0 anhui      (501) staff       (20)     2771 2023-06-28 02:40:34.000000 sparseSEM-2.0/README.md
+drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-06-28 02:43:37.060050 sparseSEM-2.0/data/
+-rw-r--r--   0 anhui      (501) staff       (20)     2393 2023-04-25 02:30:52.000000 sparseSEM-2.0/data/B.csv
+-rw-r--r--   0 anhui      (501) staff       (20)    13436 2023-04-19 01:21:12.000000 sparseSEM-2.0/data/Missing.csv
+-rw-r--r--   0 anhui      (501) staff       (20)    13436 2023-04-19 01:21:08.000000 sparseSEM-2.0/data/X.csv
+-rw-r--r--   0 anhui      (501) staff       (20)    62636 2023-04-19 01:21:05.000000 sparseSEM-2.0/data/Y.csv
+drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-06-28 02:43:37.096940 sparseSEM-2.0/doc/
+-rw-r--r--   0 anhui      (501) staff       (20)     6148 2023-06-17 02:26:05.000000 sparseSEM-2.0/doc/.DS_Store
+-rw-r--r--   0 anhui      (501) staff       (20)   173524 2023-04-17 18:15:54.000000 sparseSEM-2.0/doc/Fig1_nCPU.png
+-rw-r--r--   0 anhui      (501) staff       (20)   369870 2023-04-17 18:15:54.000000 sparseSEM-2.0/doc/Fig2_sigma01.png
+-rw-r--r--   0 anhui      (501) staff       (20)   380492 2023-04-17 18:15:54.000000 sparseSEM-2.0/doc/Fig3_sigma05.png
+-rwxr-xr-x   0 anhui      (501) staff       (20)  1989713 2023-04-17 18:15:54.000000 sparseSEM-2.0/doc/Fig4_cisTransNetworkYeast_clusters_manualAdjusted_GOterm.jpg
+-rwxr-xr-x   0 anhui      (501) staff       (20)   928929 2023-04-17 18:15:54.000000 sparseSEM-2.0/doc/Fig5_yeast_grn_genome_biology.png
+-rw-r--r--   0 anhui      (501) staff       (20)    92194 2023-06-17 02:42:00.000000 sparseSEM-2.0/doc/Network-Inference-via-sparseSEM.pdf
+-rw-r--r--   0 anhui      (501) staff       (20)    37882 2023-04-18 23:35:33.000000 sparseSEM-2.0/doc/sparseSEM.md
+-rw-r--r--   0 anhui      (501) staff       (20)   922166 2023-06-14 02:59:16.000000 sparseSEM-2.0/doc/sparseSEM.pdf
+-rw-r--r--   0 anhui      (501) staff       (20)   166880 2023-04-17 19:32:38.000000 sparseSEM-2.0/doc/table1_data.png
+-rw-r--r--   0 anhui      (501) staff       (20)   281918 2023-04-17 19:56:05.000000 sparseSEM-2.0/doc/table2_data.png
+-rw-r--r--   0 anhui      (501) staff       (20)   144048 2023-04-17 19:57:17.000000 sparseSEM-2.0/doc/table3_data.png
+-rw-r--r--   0 anhui      (501) staff       (20)       38 2023-06-28 02:43:37.116941 sparseSEM-2.0/setup.cfg
+-rw-r--r--   0 anhui      (501) staff       (20)     2279 2023-06-27 03:37:11.000000 sparseSEM-2.0/setup.py
+drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-06-28 02:43:37.105286 sparseSEM-2.0/sparseSEM/
+-rw-r--r--   0 anhui      (501) staff       (20)      567 2023-06-20 03:19:37.000000 sparseSEM-2.0/sparseSEM/__init__.py
+-rw-r--r--   0 anhui      (501) staff       (20)     8509 2023-06-18 02:44:17.000000 sparseSEM-2.0/sparseSEM/elasticNetSML.py
+-rw-r--r--   0 anhui      (501) staff       (20)     9096 2023-06-22 02:53:48.000000 sparseSEM-2.0/sparseSEM/elasticNetSMLcv.py
+-rw-r--r--   0 anhui      (501) staff       (20)     7928 2023-06-17 02:51:30.000000 sparseSEM-2.0/sparseSEM/elasticNetSMLpoint.py
+-rw-r--r--   0 anhui      (501) staff       (20)    12980 2023-06-27 02:59:31.000000 sparseSEM-2.0/sparseSEM/enSEM_STS.py
+-rw-r--r--   0 anhui      (501) staff       (20)      911 2023-04-25 02:24:54.000000 sparseSEM-2.0/sparseSEM/loadSEMlib.py
+-rwxr-xr-x   0 anhui      (501) staff       (20)   100424 2023-06-23 03:07:36.000000 sparseSEM-2.0/sparseSEM/sparseSEM.cpython-310-darwin.so
+drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-06-28 02:43:37.113658 sparseSEM-2.0/sparseSEM/src/
+-rw-r--r--   0 anhui      (501) staff       (20)    41900 2023-04-23 02:55:12.000000 sparseSEM-2.0/sparseSEM/src/lassoSEM.c
+-rw-r--r--   0 anhui      (501) staff       (20)     1550 2023-04-17 14:36:00.000000 sparseSEM-2.0/sparseSEM/src/lassoSEM.h
+-rw-r--r--   0 anhui      (501) staff       (20)    90780 2023-06-23 03:05:03.000000 sparseSEM-2.0/sparseSEM/src/lassoSMLv11beta.c
+drwxr-xr-x   0 anhui      (501) staff       (20)        0 2023-06-28 02:43:37.109963 sparseSEM-2.0/sparseSEM.egg-info/
+-rw-r--r--   0 anhui      (501) staff       (20)     3803 2023-06-28 02:43:36.000000 sparseSEM-2.0/sparseSEM.egg-info/PKG-INFO
+-rw-r--r--   0 anhui      (501) staff       (20)      837 2023-06-28 02:43:37.000000 sparseSEM-2.0/sparseSEM.egg-info/SOURCES.txt
+-rw-r--r--   0 anhui      (501) staff       (20)        1 2023-06-28 02:43:36.000000 sparseSEM-2.0/sparseSEM.egg-info/dependency_links.txt
+-rw-r--r--   0 anhui      (501) staff       (20)       33 2023-06-28 02:43:36.000000 sparseSEM-2.0/sparseSEM.egg-info/requires.txt
+-rw-r--r--   0 anhui      (501) staff       (20)       10 2023-06-28 02:43:36.000000 sparseSEM-2.0/sparseSEM.egg-info/top_level.txt
```

### Comparing `sparseSEM-1.1/PKG-INFO` & `sparseSEM-2.0/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sparseSEM
-Version: 1.1
+Version: 2.0
 Summary: Python wrapper for sparseSEM
 Home-page: https://scholar.google.com/citations?user=WhDMZEIAAAAJ&hl=en
 Author: Anhui Huang
 Author-email: anhuihuang@gmail.com
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Programming Language :: Python
@@ -25,44 +25,52 @@
 
 # Elastic Net for Structural Equation Models (SEM)
 
 Anhui Huang | Ph.D. Electrical and Computer Engineering 
 
 <https://scholar.google.com/citations?user=WhDMZEIAAAAJ&hl=en>
 
+## Summary
+Provides elastic net penalized maximum likelihood for structural equation models (SEM).   The package implements 
+`lasso` and `elastic net` (l1/l2) penalized SEM and 
+estimates the model parameters with an efficient block coordinate ascent algorithm that maximizes the penalized 
+likelihood of the SEM.  Hyperparameters are inferred from cross-validation (CV).  A Stability Selection (STS) function 
+is also available to provide accurate causal effect selection. 
+
+The experimental study and vignettes are also available in the `doc/` folder in the package.  
 
 ## PyPI installation 
-`sparseSEM` is available on PyPI:  https://pypi.org/project/sparseSEM/1.0/. Run command `pip install sparseSEM` to install 
+`sparseSEM` is available on PyPI:  https://pypi.org/project/sparseSEM/. Run command `pip install sparseSEM` to install 
 from PyPI.
 
 `test/` folder contains examples using data packed along with this package in `data/` folder. 
 To run `test/` examples, clone this repo, and run from `test/` directory. 
 
 
-## Documentation
-The theory and background for network topology inference using sparse Structural Equation Models (SEM) can be found 
-in my Ph.D dissertation (Huang A. 2014). The experimental study are also available in the `doc/` folder in the package.  
-
-
-## Configuration
+### Configuration
 This package was originally developed to leverage high performance computer clusters to enable parallel computation 
 through openMPI.  Users who have access to large scale computational resources can explore the functionality and 
 checkout the openMPI module in this package.
 
 Current package utilizes blas/lapack for high speed computation. To build the C/C++ code, the intel OneMKL library is 
 specified in the package setup. 
 - Install the free OneMKL package (https://www.intel.com/content/www/us/en/docs/oneapi/programming-guide/2023-0/intel-oneapi-math-kernel-library-onemkl.html)
 - Check if your package is the same as in the setup.py file ('/opt/intel/oneapi/mkl/2023.1.0/include'). Update the file 
 accordingly if it was installed in a different path.
 
+### Release Note
+- V2.0: add more output information include CV results, hyperparameter, and details of model fit. V2.0 is a major release with stability selection added.
+- V1: initial release with corresponding to R package v2.
+
 
-## R package
-An R package with similiar implementation is also available at CRAN: https://cran.r-project.org/web/packages/sparseSEM/index.html
+## Package for other platforms
+### R package
+An R package for `sparseSEM` is also available at CRAN: https://cran.r-project.org/web/packages/sparseSEM/index.html
 
-## OpenMPI
+### OpenMPI
 C/C++ implementation of sparseSEM with openMPI for parallel computation is available in openMPI branch (https://github.com/anhuihng/pySparseSEM/tree/openMPI). 
 
     
 ## Reference
     - Huang A. (2014) Sparse Model Learning for Inferring Genotype and Phenotype Associations. Ph.D Dissertation,
     University of Miami, Coral Gables, FL, USA.
     - Huang A. (2014) sparseSEM: Sparse-Aware Maximum Likelihood for Structural Equation Models. Rpackage
```

### Comparing `sparseSEM-1.1/README.md` & `sparseSEM-2.0/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -1,43 +1,51 @@
 # Elastic Net for Structural Equation Models (SEM)
 
 Anhui Huang | Ph.D. Electrical and Computer Engineering 
 
 <https://scholar.google.com/citations?user=WhDMZEIAAAAJ&hl=en>
 
+## Summary
+Provides elastic net penalized maximum likelihood for structural equation models (SEM).   The package implements 
+`lasso` and `elastic net` (l1/l2) penalized SEM and 
+estimates the model parameters with an efficient block coordinate ascent algorithm that maximizes the penalized 
+likelihood of the SEM.  Hyperparameters are inferred from cross-validation (CV).  A Stability Selection (STS) function 
+is also available to provide accurate causal effect selection. 
+
+The experimental study and vignettes are also available in the `doc/` folder in the package.  
 
 ## PyPI installation 
-`sparseSEM` is available on PyPI:  https://pypi.org/project/sparseSEM/1.0/. Run command `pip install sparseSEM` to install 
+`sparseSEM` is available on PyPI:  https://pypi.org/project/sparseSEM/. Run command `pip install sparseSEM` to install 
 from PyPI.
 
 `test/` folder contains examples using data packed along with this package in `data/` folder. 
 To run `test/` examples, clone this repo, and run from `test/` directory. 
 
 
-## Documentation
-The theory and background for network topology inference using sparse Structural Equation Models (SEM) can be found 
-in my Ph.D dissertation (Huang A. 2014). The experimental study are also available in the `doc/` folder in the package.  
-
-
-## Configuration
+### Configuration
 This package was originally developed to leverage high performance computer clusters to enable parallel computation 
 through openMPI.  Users who have access to large scale computational resources can explore the functionality and 
 checkout the openMPI module in this package.
 
 Current package utilizes blas/lapack for high speed computation. To build the C/C++ code, the intel OneMKL library is 
 specified in the package setup. 
 - Install the free OneMKL package (https://www.intel.com/content/www/us/en/docs/oneapi/programming-guide/2023-0/intel-oneapi-math-kernel-library-onemkl.html)
 - Check if your package is the same as in the setup.py file ('/opt/intel/oneapi/mkl/2023.1.0/include'). Update the file 
 accordingly if it was installed in a different path.
 
+### Release Note
+- V2.0: add more output information include CV results, hyperparameter, and details of model fit. V2.0 is a major release with stability selection added.
+- V1: initial release with corresponding to R package v2.
+
 
-## R package
-An R package with similiar implementation is also available at CRAN: https://cran.r-project.org/web/packages/sparseSEM/index.html
+## Package for other platforms
+### R package
+An R package for `sparseSEM` is also available at CRAN: https://cran.r-project.org/web/packages/sparseSEM/index.html
 
-## OpenMPI
+### OpenMPI
 C/C++ implementation of sparseSEM with openMPI for parallel computation is available in openMPI branch (https://github.com/anhuihng/pySparseSEM/tree/openMPI). 
 
     
 ## Reference
     - Huang A. (2014) Sparse Model Learning for Inferring Genotype and Phenotype Associations. Ph.D Dissertation,
     University of Miami, Coral Gables, FL, USA.
     - Huang A. (2014) sparseSEM: Sparse-Aware Maximum Likelihood for Structural Equation Models. Rpackage
```

### Comparing `sparseSEM-1.1/data/B.csv` & `sparseSEM-2.0/data/B.csv`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/data/Missing.csv` & `sparseSEM-2.0/data/Missing.csv`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/data/X.csv` & `sparseSEM-2.0/data/X.csv`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/data/Y.csv` & `sparseSEM-2.0/data/Y.csv`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/.DS_Store` & `sparseSEM-2.0/doc/.DS_Store`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/Fig1_nCPU.png` & `sparseSEM-2.0/doc/Fig1_nCPU.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/Fig2_sigma01.png` & `sparseSEM-2.0/doc/Fig2_sigma01.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/Fig3_sigma05.png` & `sparseSEM-2.0/doc/Fig3_sigma05.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/Fig4_cisTransNetworkYeast_clusters_manualAdjusted_GOterm.jpg` & `sparseSEM-2.0/doc/Fig4_cisTransNetworkYeast_clusters_manualAdjusted_GOterm.jpg`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/Fig5_yeast_grn_genome_biology.png` & `sparseSEM-2.0/doc/Fig5_yeast_grn_genome_biology.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/sparseSEM.md` & `sparseSEM-2.0/doc/sparseSEM.md`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/sparseSEM.pdf` & `sparseSEM-2.0/doc/sparseSEM.pdf`

 * *Installing the 'pypdf' Python module from the 'python3-pypdf' package may produce a better output.*

 * *Files 3% similar despite different names*

#### pdftotext {} -

```diff
@@ -1,11 +1,11 @@
 Elastic Net Enabled Sparse-Aware Maximum Likelihood for
 Structural Equation Models in Inferring Gene Regulatory Networks
 Anhui Huang
-April 19, 2023
+June 13, 2023
 
 Contents
 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
 1
 
 Key Words: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
@@ -22,20 +22,24 @@
 
 Sparse SEM model for gene regulatory networks . . . . . . . . . . . . . . . . . . . . . . . . .
 
 3
 
 Structural equation models with adaptive elastic net penalty (SEM-EN) . . . . . . . . . . . .
 
-3
+4
 
 Software implementation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
 5
 
+Simulation study and real data analysis . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
+
+5
+
 Results
 
 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
 5
 
 Simulation study . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
@@ -44,38 +48,38 @@
 
 Inference of the yeast GRN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
 6
 
 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
-10
+13
 
 References . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
-13
+14
 
 Summary
 Understanding the multiple levels of gene regulations is the key for the prediction of complex cellular behavior. Integrating genetic perturbations with gene expression data has been proven to be more accurate
 in learning of causal regulatory relationships among genes comparing to treating each gene expression level
 as an individual quantitative trait. The previously designed sparse-aware maximum likelihood method for
 structural equation models (SEM-SML) has been shown to be able to integrate such information to infer
 gene regulatory networks (GRN) systematically and offer significant better performance than state-of-the-art
 algorithms. We extended the SEM-SML to incorporate adaptive elastic net (EN) penalty for the likelihood
 function of the SEMs, and implemented the SEM-EN software in efficient C/C++ with parallel computational capability by Message Passing Interface (MPI). The parallel design is capable of scaling up the
 network structure inference in a computer cluster, and enables SEM-EN to infer a network structure with
 thousands of nodes. Simulation studies demonstrated that SEM-EN was capable of inferring a large network
 within affordable computational time while achieved more accurate power of detection than SEM-SML.
 The software was further applied to infer the GRN in budding yeast systematically, in which two set of
 experimental perturbations with co-regulated gene set information were available on the AMN1 and LEU2
-genes. The SEM-EN identified GRN had two clusters with hubs and members in line with the experimental
-perturbations, corroborating the strength of SEM-EN. While the parallel version of the SEM-EN software
 1
 
-for computer cluster is implemented with command line interface, the SEM-EN method is also implemented
+genes. The SEM-EN identified GRN had two clusters with hubs and members in line with the experimental
+perturbations, corroborating the strength of SEM-EN. While the parallel version of the SEM-EN software
+for computer cluster is implemented with command line interface, the SEM-EN method is also implemented
 in C/C++ with a user-friendly R interface for personal computers. An R software package sparseSEM with
 both SEM-SML and SEM-EN features is available on the Comprehensive R Archive Network (CRAN), and
 the command-line software is freely available upon request.
 Key Words:
 • SEM: structural equation models
 • EN: elastic net
 • GRN: gen regulatory network
@@ -106,19 +110,19 @@
 The SEM-SML algorithm was motivated by the fact that the gene networks are sparse [13-15]. While this
 is the first study that infers sparse SEM systematically, other penalty functions, especially the penalty
 function of the elastic net (EN) [16, 17] may improve the inference accuracy for GRNs. This is based on
 the following observations. Although the Lasso-based methods achieve good performance in the inference
 of GRNs and are ranked top on the list of a number of methods for GRN inference [18], they tend to miss
 interactions in feed-forward loops, fan-in motifs and fan-out motifs. This is likely due to the fact that Lasso
 typically chooses only one variable among several highly correlated variables. On the other hand, it has
-been known through experimentation that a gene regulator in GRN can typically shape the expression
-profile of a set of genes, meaning that the expression of the set of co-regulated genes can be highly correlated
 2
 
-[1, 2]. For example, in gene expression microarray analysis, researchers aim at finding a group of up and
+been known through experimentation that a gene regulator in GRN can typically shape the expression
+profile of a set of genes, meaning that the expression of the set of co-regulated genes can be highly correlated
+[1, 2]. For example, in gene expression microarray analysis, researchers aim at finding a group of up and
 down-regulated gene expression patterns under different experimental treatments, and discover novel and
 unexpected functional relationships among genes [19]. Such observations make the elastic net the right fit
 since it retains correlated variables while still yielding a sparse model [16].
 In this paper, we developed an SEM-based method for the inference of GRNs that maximizes the l1/l2regularized likelihood function similar to the one used in the adaptive EN [16, 17]. The SEM with adaptive
 elastic net penalty algorithm (SEM-EN) was maximized through a parallelized efficient block coordinate
 ascent algorithm, which inferred the network structure on each node in parallel. Considering that the
 MATLAB implementation of the SEM-SML algorithm in [12] was time consuming and not applicable to
@@ -136,22 +140,22 @@
 Consider the expression levels of Ng genes from N individuals measured in microarray or RNAseq experiments. Following the design of [12], the gene regulatory network is postulated to obey the SEM:
 yi = Byi + Fxi + µ + εi ,
 
 i = 1, · · · , N
 
 (1)
 
-
 T
-where yi := yi1 , · · · , yiNg
-is the expression levels of Ng genes from N individuals, and xi :=
 
+is the expression levels of Ng genes from N individuals, and xi :=
+where yi := yi1 , · · · , yiNg
 T
-xi1 , · · · , xiNq
+
 denotes the genotype of Nq ⩾ Ng eQTLs of individual i, i = 1, . . . , N . In this paper, we
+xi1 , · · · , xiNq
 focus on the genetic variations observed at expression quantitative trait loci (eQTLs), and the developed
 methods can be applied to other genetic variations such as single nucleotide polymorphisms (SNPs),
 copy number variations (CNVs) and gene knockdown by RNA interference (RNAi) or controlled gene
 overexpression. B is an Ng × Ng matrix contains unknown parameters defining the network structure, and
 is assumed to be sparse; F is an Ng × Nq matrix captures the effect of Nq eQTLs for Ng genes; µ is an
 Ng × 1 vector accounts for possible model bias; and εi is an Ng × 1 vector captures the residual error.
 Typically, εi is modeled as a zero-mean Gaussian vector with covariance σ 2 , where I denotes the Ng × Ng
@@ -160,20 +164,21 @@
 F has Nq entries with known locations but unknown effect size, and Ng Nq − Nq of zero entries. Note that
 there are two structural properties in the GRN. First, as noted in [12], GRN and other general biochemical
 networks are sparse, meaning that only a relative smaller number of genes can be regulators of a given
 gene, thus matrix B is sparse. Second, a regulator typically can shape the expression profile of a set of
 genes, meaning that the expression of the set of co-regulated genes can be highly correlated [1, 2]. Based
 on the SEM-SML algorithm designed in [12], we developed a network inference algorithm that exploits the
 aforementioned structural properties.
-Structural equation models with adaptive elastic net penalty (SEM-EN)
-Let us define Y = [y1 , · · · , yN ] , X = [x1 , · · · , xN ] and E = [ε1 , · · · , εN ], then we can write the SEM in (1)
-as Y = BY + FX + µ1T + E. The SEM-EN algorithm applied the I1 /I2 -norm penalty to the log-likelihood
+
 3
 
-PN
+Structural equation models with adaptive elastic net penalty (SEM-EN)
+Let us define Y = [y1 , · · · , yN ] , X = [x1 , · · · , xN ] and E = [ε1 , · · · , εN ], then we can write the SEM in (1)
+as Y = BY + FX + µ1T + E. The SEM-EN algorithm applied the I1 /I2 -norm penalty to the log-likelihood
+PN
 function of SEM in eq (2) of [12]. Let ỹ i = y i − y i and x̃i = xi − x, i = 1, · · · , N , where y = i=1 y i /N
 PN
 and x = i=1 xi /N , and collect them into matrices Ỹ = [ỹ1 , · · · , ỹN ] , X̃ = [x̃1 , · · · , x̃N ]. Then SEM-EN
 infers the model parameters through I1 /I2 penalized ML estimation:
 1
 1
 (B̂, F̂)EN = arg max N σ 2 log | det(I − B)| − ∥Ỹ − BỸ − FX̃∥2F − λα∥B∥1,W − (1 − α)λ∥B∥2
@@ -195,15 +200,16 @@
 −λαwij |Bij | − (1 − α)λBij
 /2 applied to eq(10) in [12], we have the following objective function:
 
 
 1
 2
 − λwij |Bij |
-gij (Bij ) := N σ̂ 2 log |α0 − cij Bij | + α1 Bij − (1 − α)λ + α2 Bij
+gij (Bij ) := N σ̂ log |α0 − cij Bij | + α1 Bij − (1 − α)λ + α2 Bij
+2
 2
 
 (3)
 
 where σ̂ 2 is the variance estimate, cij denotes the (i, j) th co-factor of matrix (I − B̂) with B̂ being the h
 estimate of matrix
  B, α0 := det(Ii − B̂) + cij B̂ij with B̂ij being the estimate of Bij ,
@@ -223,16 +229,16 @@
 Q̃ij (λ) =
 
 N σ 2 cij (λ)
 det(I − B̂(λ))
 
 h
 i
-− (1 − α)λB̂(λ)
 + ỸỸT − B̂(λ)ỸỸT − F̂(λ)X̃ỸT
+− (1 − α)λB̂(λ)
 ij
 
 (4)
 
 where B̂(λ) and F̂(λ) denote the optimal estimate of (2) for a given λ with fixed α, and σ 2 can be estimated
 as σ̂ 2 = N 1Ng ∥Ỹ − B̂(λ)Ỹ − F̂(λ)X̃∥2F . Then the strong rule [39] for SEM-EN is available as following. Let
 λmax denote the smallest λ that yields B̂ij = 0, ∀i, j, and λmax > λ1 > · · · > λmin is a decreasing set of
@@ -263,165 +269,192 @@
 
 Software implementation
 The block coordinate ascent algorithm in Algorithm 1 of [12] is updated with equations (3) and (4) along
 with the discarding rules in equations (5) and (6), and is parallelized to reduce execution time.
 Specifically, a master computer node is designated to compute and check to convergence criterion, which is
 2
 
-2
-
 determined as err = B̂ − B̂new
 
 F
 
+2
+
 /∥B̂∥2F + F̂ − F̂new
 
 F
 
 /∥F̂∥2F being smaller than a prespecified small
 
 value. And several slavery nodes will be assigned to compute the solution for each row of B̂. The parallelized
 computation is achieved in a high performance computing (HPC) clusters, and the software is implemented
 in C/C + + utilizing open MPI. On the other hand, when the scale and degree of a network to be inferred
 is small and computation is less demanding, we also provide the serial version of the C/C + + program
 with a user friendly R interface. To achieve fast computation, BLAS and LAPACK [37] were utilized in
 implementation of both software packages.
+Simulation study and real data analysis
+The network simulation method described in [12] was followed to simulate networks for this study, except
+that networks were simulated with larger scale and degree. While Ng and number of expected edges (Ne )
+in simulations of [12] were small (Ng = 10 or 30, Ne = 1 or 3) due to the large amount of computation, we
+simulated a large network with Ng = 300 and Ne = 3 to examine the scalability of SEM-EN algorithm.
+Specifically, a random DAG of Ng = 300 and an expected Ne = 3 edges per node was first generated by
+creating directed edges between two randomly picked nodes. Then matrix F was set as the Ng × Ng identity
+matrix, and Bij was generated randomly from uniform distribution in (0.5, 1) or (−1, −0.5) if there was an
+edge from node j to node i. We simulated two sets of DAGs with different noise levels. The first one had
+Eij sampled from a Gaussian distribution with zero mean and variance 0.01 , while the second one having
+variance 0.05 . For each network, 100 replicates were generated and analyzed by SEM-EN for each sample
+size ranging from 100 to 1000 by step of 100 . We considered 20 values of α ranging from 1 to 0.05 by step
+size of 0.05 and 20λs from λmax to 0.0001λmax with even step size at log scale. Ten-folds CV were used to
+determine the optimal parameters. The PD and FDR of SEM-EN were compared with that of SEM-SML.
+We also applied the SEM-EN algorithms to infer a GRN in budding yeast
+(Saccharomyces cerevisiae) [40]. The data contains expression levels of 6,126 yeast ORFs and 2,956 genetic
+markers from 112 yeast segregants from the cross of a laboratory strain (BY4716) and a wild strain (RM111a) [30]. We only kept ORFs accepted in the Yeast Comparative Genomics database [41] and those with
+less than 5% of missing expression data, resulted in 3,380 ORFs. To obtain the set of cis-eQTLs out of
+the 2,957 genetic markers, we first associated gene markers with an ORF if they were in distance ≤ 20 kb
+representing the QTL resolution for this cross [40]. The set of cis-eQTLs was then obtained by testing gene
+expression levels with their associated gene markers through Wilcoxon rank-sum test following the procedure
+described in [40]. Totally, 1,162 ORFs were found having cis-eQTLs. For simplicity, we only kept one of the
+most significant cis-eQTLs with the smallest p-value if multiple cis-eQTLs were found for an ORF. The gene
+expression profile of 3,380 ORFs and genetic marker of 1,162 eQTLs were then used for network inference
+by SEM-EN.
 Back to Top
 
 Results
 ### Scalability of the parallel network structure inference
 To achieve feasible computation of inferring a GRN with hundreds or thousands of nodes, the parallel block
 coordinate ascent algorithm was implemented with a master-slavery paradigm. While one master node as
 designated for the computation of program initialization, decomposing the problem into small tasks, assign
 tasks for multiple slave nodes, gathering the results for determining convergence and generate the final result
-[20], number of slavery nodes can be supplied by users upon available system resources. To gain insights
+
+5
+
+[20], number of slavery nodes can be supplied by users upon available system resources. To gain insights
 into the scaling property of the parallel computation, we also implemented the SEM-SML algorithms [12]
 with C/C + + and paralleled the block coordinate ascent algorithm with Open MPI. In fact, the SEM-SML
 algorithm is a special case of SEM-EN with shrinkage parameter α = 1 (see Methods section for details).
 The scaling property of the parallel computation was shown in Figure 1, where the performance was obtained
 from inference of a sparse DAG having N = 300 samples, Ng = 300 genes, Ne = 3 edges, and σ 2 = 0.05. The
 computational time was the mean of 5 replicates. From Figure 1, a strong scaling pattern [21] was observed
 for both SEM-SML and SEM-EN.
 
 Figure 1: Scaling pattern for SEM-SML and SEM-EN
 
-5
-
-Simulation study
+Simulation study
 To evaluate the performance of SEM-EN, we compared PD and FDR with that of SEM-SML. If B̂ij ̸= 0,
 then we consider there is an edge from gene j to gene i. the PD and FDR of the SEM-SML and SEM-EN
 for different sample sizes are depicted in Figure 2 and Figure 3 corresponding to two directed acyclic graphs
 (DAGs) with number of genes Ng = 300, expected number of edges per node Ne = 3 and residual variance
 σ 2 = 0.01 and σ 2 = 0.05, respectively. The result of Figure 2 and 3 represents mean PD and FDR for 100
 replicates for each for the 10 different sample sizes. It is observed that SEM-EN achieves higher PD and
 similar FDR comparing with that of SEM-SML for both DAGs despite of different sample sizes. Moreover,
 it can be seen that the performance gain of SEM-EN is more significant for the DAG with larger noise level
 (Figure 3). Take N = 500 for example, the PD/FDR of SEM-EN for σ 2 = 0.01 are 0.9537/0.0433, comparing
 to 0.9005/0.0375 of SEM-SML. For σ 2 = 0.05 with the same sample size, the numbers are 0.9008/0.1300,
 and 0.7663/0.1182 for the two methods, respectively.
-
-Figure 2: Performance of SEM-SML and SEM-EN for DAG simulation σ 2 = 0.01
-
 Inference of the yeast GRN
 The gene expression profile of 3,380 ORFs and genetic marker of 1,162 cis-eQTLs were used for network
 inference by SEM-EN. Two parameters controlling degree of sparseness in the GRN need to be learnt from
+data. Cross validation (CV) identified the optimal shrinkage parameters as (α, λ) = (0.45, 0.0063) (see
+Methods section for the definitions of shrinkage parameters) for the SEM-EN method. With the pair of
+parameters, SEM-EN inferred a sparse GRN with 159 open reading frames (ORFs) involving 267 edges. The
+
 6
 
+Figure 2: Performance of SEM-SML and SEM-EN for DAG simulation σ 2 = 0.01
+
+7
+
 Figure 3: Performance of SEM-SML and SEM-EN for DAG simulation σ 2 = 0.05
 
 Figure 4: PD and FDR for SEM-SML and SEM-EN in analyzing the two simulated DAGs
-7
+8
 
-data. Cross validation (CV) identified the optimal shrinkage parameters as (α, λ) = (0.45, 0.0063) (see
-Methods section for the definitions of shrinkage parameters) for the SEM-EN method. With the pair of
-parameters, SEM-EN inferred a sparse GRN with 159 open reading frames (ORFs) involving 267 edges. The
-network was visualized via Cytoscape [22] shown in Figure 4 and the positional information of the ORFs
-involved in the GRN was depicted in Figure 5 by Circos software [23].
+network was visualized via Cytoscape [22] shown in Figure 5 and the positional information of the ORFs
+involved in the GRN was depicted in Figure 7 by Circos software [23].
 It has been known that in GRN, sub-network are typically associated with particular biological functions
 [24]. In our study, five major clusters of the GRN was identified via Cytoscape [22] shown in different colors
-in Figure 4, and gene ontology (GO) term enrichment analysis was performed for each clusters by Gorilla
-[25] (Table 1). Specific to molecular functions, Cluster 1 (lime color in Figure 4) includes 28 ORFs and is
-enriched with aldehyde dehydrogenase (NAD) activity and transferase activity that transferring aldehyde
+in Figure 5, and gene ontology (GO) term enrichment analysis was performed for each clusters by Gorilla [25]
+(Table 1/Figure 4). Specific to molecular functions, Cluster 1 (lime color in Figure 5) includes 28 ORFs and
+is enriched with aldehyde dehydrogenase (NAD) activity and transferase activity that transferring aldehyde
 or ketonic groups. Cluster 2 (teal color) includes 10 ORFs and is enriched with asparaginase activity and
 iron ion transmembrane transporter activity. Cluster 3 (slate blue color) contains 30 ORFs and is enriched
 with carbamoyl-phosphate synthase activity, oxidoreductase activity, NAD binding, ad dicarboxylic acid
 transmembrane transporter activity. Cluster 4 (olive color) contains 13 ORFs and is enriched with mating
 pheromone activity, DNA binding and bending, and RNA polymerase II transcription. Cluster 5 (red color)
 contains 16 ORFs and is enriched with glucosidase activity. The corresponding significant terms were shown
-in Figure 4.
+in Figure 5.
 
 Figure 5: Sparse budding yeast GRN inferred by SEM-EN
+Within a network cluster, nodes that are most relevant for the corresponding cluster function often have
+higher degree, meaning that there are more edges connected to them than other nodes [26]. Encoding
+the leucine biosynthetic enzyme, LEU2 is deleted in the RM parents in the segregants [27], and has been
 
-8
+9
 
 Figure 6: Enriched GO terms of the five clusters in yeast GRN
 
-9
+10
 
-Within a network cluster, nodes that are most relevant for the corresponding cluster function often have
-higher degree, meaning that there are more edges connected to them than other nodes [26]. Encoding
-the leucine biosynthetic enzyme, LEU2 is deleted in the RM parents in the segregants [27], and has been
-previously predicted as a causal regulator for the expression of a subset of genes by several independent
+previously predicted as a causal regulator for the expression of a subset of genes by several independent
 studies [27-29]. In our GO term enrichment analysis
-shown in Table 1 , leucine biosynthetic process is
-
-significant for Cluster 3 (p -value = 4.77 × 10−6 , and LEU2 is identified as regional hub in for the cluster
-with 20 genes directly connected to it (Figure 4). The parent lab strain BY4716 has AMN1 gene deleted.
+ shown in Table 1/Figure 4, leucine biosynthetic process
+is significant for Cluster 3 (p -value = 4.77 × 10−6 , and LEU2 is identified as regional hub in for the cluster
+with 20 genes directly connected to it (Figure 5). The parent lab strain BY4716 has AMN1 gene deleted.
 AM N 1 gene encodes a protein required for daughter cell separation, multiple mitotic checkpoints, and
 chromosome stability [27]. It has been verified in previous study that AM N 1 gene is responsible for the
 regulation of a set of genes (SCW11, DSE1, DSE2, DSE3, DSE4, ISR1, PRY3, EGT2, SUN4, BUD9) [27].
-Among them, SCW11, DSE1, DSE2, DSE3, ISR1, EGT2, SUN4, and BUD9 are in Cluster 5 in Figure 4.
+Among them, SCW11, DSE1, DSE2, DSE3, ISR1, EGT2, SUN4, and BUD9 are in Cluster 5 in Figure 5.
 These results from previous biological experiments and independent research studies corroborate the strength
 of the SEM-EN algorithm.
+
+Figure 7: Budding yeast gene interaction pattern with link edges identified by SEM-EN
 While the genetic engineering of AM N 1 and LEU2 genes serves as a direct positive control for the GRN
+11
+
+Figure 8: eQTL hotspots identified in the original publication of the budding yeast dataset and predicted
+using SEM-EN
 inference in budding yeast [27, 29, 30], the network structure inferred by SEM-EN shed light into the gene
-regulatory relationships. Previous study on single cis-eQTL mapping revealed 13 eQTL hot spots (Table 2),
-where eQTLs have pleiotropic effects on a number of expression traits [27]. The positions of eQTL hot spots
-can be visualized as the red ticks on the yeast chromosomes in Figure 5, and the regulator genes in the GRN
-inferred from SEM-EN are listed in Table 2. While the original study analyzed all 6,126 yeast ORFs and
-identified 8 regulators for the 13 eQTL hot spots, our study considered 3,380 ORFs that passed data quality
-control (see the Methods section for details) and identified regulators for 9 of the hot spots. Regulators such
-as AM N 1, LEU 2, and MATALPHA1 are consistent with previous study (Table 2). Particularly, SEM-EN
-identified regulators that are missed in previous study including RIB5 for hot spot 3 , TSL1 for hot spot
-10 and SUN4 for hotspot 11. Among them, RIB5 is a gene encodes the riboflavin synthase that catalyzes
-the last step of the riboflavin biosynthesis pathway and involves in amino acid biosynthesis. RIB5 interacts
-with ARG1 in the SEM-EN identified GRN. Association of RIB5 and ARG1 has been characterized in
-previous study [31], and both are key proteins for cellular growth. TSL1 interacts with CTT1, both of
-which have been identified to be associated with cellular growth under stress [32]. SUN4 is a gene involved
-in cell wall separation [33], and interacts with DSE2 and SCW11 in the SEM-EN inferred GRN (Figure
-4). DSE2 is a daughter cell-specific secreted protein that plays a key role in daughter cell separation.
-During the separation process, DSE2 degrades cell wall from the daughter side and causes daughter cell to
-separate from the mother cell [34]. SCW11 is a cell wall protein that plays a key role in conjugation during
-mating [35], and its functional association with DSE2 have been experimentally characterized [36]. Given the
-genetic perturbation background in daughter cell separation and amino acid biosynthesis, previous molecular
-experiment results corroborate the predictive power of the inferred GRN and the strength of the SEM-EN
-method.
+regulatory relationships. Previous study on single cis-eQTL mapping revealed 13 eQTL hot spots (Table
+3/Figure 8), where eQTLs have pleiotropic effects on a number of expression traits [27]. The positions of
+eQTL hot spots can be visualized as the red ticks on the yeast chromosomes in Figure 7, and the regulator
+genes in the GRN inferred from SEM-EN are listed in Table 3/Figure 8. While the original study analyzed
+all 6,126 yeast ORFs and identified 8 regulators for the 13 eQTL hot spots, our study considered 3,380 ORFs
+that passed data quality control (see the Methods section for details) and identified regulators for 9 of the
+hot spots. Regulators such as AM N 1, LEU 2, and MATALPHA1 are consistent with previous study (Table
+3/Figure 8). Particularly, SEM-EN identified regulators that are missed in previous study including RIB5
+for hot spot 3 , TSL1 for hot spot 10 and SUN4 for hotspot 11. Among them, RIB5 is a gene encodes
+the riboflavin synthase that catalyzes the last step of the riboflavin biosynthesis pathway and involves in
+amino acid biosynthesis. RIB5 interacts with ARG1 in the SEM-EN identified GRN. Association of RIB5
+and ARG1 has been characterized in previous study [31], and both are key proteins for cellular growth.
+TSL1 interacts with CTT1, both of which have been identified to be associated with cellular growth under
+stress [32]. SUN4 is a gene involved in cell wall separation [33], and interacts with DSE2 and SCW11 in the
+SEM-EN inferred GRN (Figure 5). DSE2 is a daughter cell-specific secreted protein that plays a key role
+in daughter cell separation. During the separation process, DSE2 degrades cell wall from the daughter side
+and causes daughter cell to separate from the mother cell [34]. SCW11 is a cell wall protein that plays a key
+role in conjugation during mating [35], and its functional association with DSE2 have been experimentally
+characterized [36]. Given the genetic perturbation background in daughter cell separation and amino acid
+biosynthesis, previous molecular experiment results corroborate the predictive power of the inferred GRN
+and the strength of the SEM-EN method.
 Back to Top
 
-Discussion
+12
+
+Discussion
 Understanding the multiple levels of gene regulations is the key for the prediction of complex cellular behavior.
 Integrating genetic perturbations with gene expression data has been proven to be more accurate in learning
 causal regulatory relation among genes comparing to treating each gene expression level as an individual
 quantitative trait [12]. The SEM-SML has been shown to be able to integrate such information to infer
 GRN systematically and offer significant better performance than state-of-the-art algorithms. We extended
 the SEM-SML to incorporate adaptive elastic net penalty [16] for the likelihood function of the SEMs, and
 implemented the SEM-EN software in efficient C/C + + with parallel computational capability by MPI.
 Simulation studies demonstrated that SEM-EN is capable of inferring a large network within affordable
 computational time while achieving high power of detection than SEM-SML. The software is further applied
 to systematically infer the GRN in budding yeast.
 The work in this paper improved the SEM-SML algorithm [12] from two directions. First, while previous work
 was implemented in MATLAB, the SEM-SML algorithm and the new SEM-EN algorithm were implemented
-10
-
-Figure 7: Budding yeast gene interaction pattern with link edges identified by SEM-EN
-
-11
-
-Figure 8: eQTL hotspots identified in the original publication of the budding yeast dataset and predicted
-using SEM-EN
 in C/C + + with the fast basic linear algebra subprograms (BLAS) and linear algebra package (LAPACK)
 [37] in this paper. Simulation demonstrated that computational time for SEM-SML in C/C + + was reduced
 by more than 10 times compared to the one implemented in MATLAB using a single CPU node. To achieve
 computational feasibility for inferring large network with thousands of nodes, the block coordinate ascent
 technique in Algorithm 1 of [12] is parallelized with Open MPI [38]. A strong scaling pattern for the parallel
 implementation was observed and depicted in Figure 1, and the new software is capable of inferring a network
 structure more than 100 times faster. For example, while the MATLAB implementation takes several days
@@ -442,24 +475,24 @@
 since it has been known that elastic net penalty enjoys a strong grouping effect than the ll -norm penalty in
 linear regression. In fact, SEM-SML becomes a special case of SEM-EN with parameter α = 1.
 In inferring the GRN of budding yeast, SEM-EN integrates genetic perturbations with genome-wide expression data. On the one hand, for the set of regulation that have been verified in previous studies such as
 the set of genes regulated by AM N 1 and LEU 2, the GRN obtained by SEM-EN is in line with previous
 findings, which corroborates the strength of the SEM-EN method. On the other hand, with the grouping
 effect encouraged by SEM-EN, we were also able to identify other ORFs interacting with known regulators.
 For example, seven ORFs in Custer 5 was not reported in the list of [27] that linked to AMN1. Among them,
-12
-
-RM A1 interacts with DSE2 and SCW 11, both are directly linked to AM N 1; AGP 2 directly interacts with
+RM A1 interacts with DSE2 and SCW 11, both are directly linked to AM N 1; AGP 2 directly interacts with
 DSE 1 and has a distance of 2 to AM N 1, and TOF1 and HRR25 both interacts with DSE2. The genes in
 the cluster were known to specifically expressed in daughter cells during budding [36], and it may be worthy
 of experimental investigation to further study their roles in gene regulation affecting daughter-cell separation
 after budding.
 Back to Top
 
-References
+13
+
+References
 1. Civelek M, Lusis AJ: Systems genetics approaches to understand complex traits. Nat Rev Genet 2014,
 15:34-48.
 2. Nuzhdin SV, Friesen ML, McIntyre LM: Genotype-phenotype mapping in a post-GWAS world. Trends
 in Genetics 2012, 28 : 421 − 426
 3. Butte AJ, Tamayo P, Slonim D, Golub TR, Kohane IS: Discovering functional relationships between
 RNA expression and chemotherapeutic susceptibility using relevance networks. Proc Natl Acad Sci
 USA 2000, 97:12182-12186
@@ -484,24 +517,24 @@
 equation models exploiting genetic perturbations. PLoS Comput Biol 2013, 9:e1003068.
 13. Jeong H, Mason SP, Barabasi A-L, Oltvai ZN: Lethality and centrality in protein networks. Nature
 2001, 411:41-42.
 14. Tegner J, Yeung MS, Hasty J, Collins JJ: Reverse engineering gene networks: integrating genetic
 perturbations with dynamical modeling. Proc Natl Acad Sci USA 2003, 100:5944-5949.
 15. Thieffry D, Huerta AM, Perez-Rueda E, Collado-Vides J: From specific gene regulation to genomic
 networks: a global analysis of transcriptional regulation in Escherichia coli. Bioessays 1998, 20:433440.
-
-13
-
-16. Zou H, Hastie T: Regularization and variable selection via the elastic net. J Roy Stat Soc B Met 2005,
+16. Zou H, Hastie T: Regularization and variable selection via the elastic net. J Roy Stat Soc B Met 2005,
 67:301-320.
 17. Zou H, Zhang HH: On the adaptive elastic-net with a diverging number of parameters. Ann Stat 2009
 , 37:1733.
 18. Marbach D, Costello JC, Kuffner R, Vega NM, Prill RJ, Camacho DM, Allison KR, Kellis M, Collins
 JJ, Stolovitzky G: Wisdom of crowds for robust gene network inference. Nat Meth 2012, 9:796-804
-19. Slonim DK, Yanai I: Getting started in gene expression microarray analysis. PLoS Comput Biol 2009,
+
+14
+
+19. Slonim DK, Yanai I: Getting started in gene expression microarray analysis. PLoS Comput Biol 2009,
 5:e1000543
 20. Quinn MJ: Parallel Programming. TMH CSE; 2003.
 21. Akl SG: Parallel computation: models and methods. Prentice-Hall, Inc.; 1997.
 22. Shannon P, Markiel A, Ozier O, Baliga NS, Wang JT, Ramage D, Amin N, Schwikowski B, Ideker
 T: Cytoscape: A software environment for integrated models of biomolecular interaction networks.
 Genome Res 2003, 13:2498-2504.
 23. Krzywinski M, Schein J, Birol I, Connors J, Gascoyne R, Horsman D, Jones SJ, Marra MA: Circos:
@@ -529,27 +562,28 @@
 33. Mouassite M, Camougrand N, Schwob E, Demaison G, Laclau M, Guerin M: The SU , family: yeast
 SN , 4/SCW 3 is involved in cell septation. Yeast 2000, 16 : 905 − 919
 34. Klis FM, Mol P, Hellingwerf K, Brul S: Dynamics of cell wall structure in Saccharomyces cerevisiae.
 FEMS microbiology reviews 2002, 26 : 239 − 256
 35. Zeitlinger J, Simon I, Harbison CT, Hannett NM, Volkert TL, Fink GR, Young RA: Program-specific
 distribution of a transcription factor dependent on partner transcription factor and MAPK signaling.
 Cell 2003, 113:395-404.
-14
-
-36. Colman-Lerner A, Chin TE, Brent R: Yeast Cbk1 and M ob2 activate daughter-specific genetic programs to induce asymmetric cell fates. Cell 2001, 107 : 739 − 750
+36. Colman-Lerner A, Chin TE, Brent R: Yeast Cbk1 and M ob2 activate daughter-specific genetic programs to induce asymmetric cell fates. Cell 2001, 107 : 739 − 750
 37. Anderson E: LAPACK Users’ Guide. Society for Industrial and Applied Mathematics; 1999.
-38. Gabriel E, Fagg G, Bosilca G, Angskun T, Dongarra J, Squyres J, Sahay V, Kambadur P, Barrett B,
+
+15
+
+38. Gabriel E, Fagg G, Bosilca G, Angskun T, Dongarra J, Squyres J, Sahay V, Kambadur P, Barrett B,
 Lumsdaine A, et al: Open MPI: goals, concept, and design of a next generation MPI implementation.
 In Recent Advances in Parallel Virtual Machine and Message Passing Interface. Volume 3241. Edited
 by Kranzlmuller D, Kacsuk P, Dongarra J: Springer Berlin Heidelberg; 2004: 97-104: Lecture Notes
 in Computer Science].
 39. Tibshirani R, Bien J, Friedman J, Hastie T, Simon N, Taylor J, Tibshirani RJ: Strong rules for discarding predictors in lasso-type problems. Journal of the Royal Statistical Society: Series B (Statistical
 Methodology) 2012, 74:245-266.
 40. Brem RB, Kruglyak L: The landscape of genetic complexity across 5,700 gene expression traits in yeast.
 Proceedings of the National Academy of Sciences of the United States of America 2005, 102:1572-1577
 41. Kellis M, Patterson N, Endrizzi M, Birren B, Lander ES: Sequencing and comparison of yeast species
 to identify genes and regulatory elements. Nature 2003, 423 : 241 − 254
 Back to Top
 
-15
+16
```

### Comparing `sparseSEM-1.1/doc/table1_data.png` & `sparseSEM-2.0/doc/table1_data.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/table2_data.png` & `sparseSEM-2.0/doc/table2_data.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/doc/table3_data.png` & `sparseSEM-2.0/doc/table3_data.png`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/setup.py` & `sparseSEM-2.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import os
 from setuptools import setup, Extension, find_packages
 
-_VERSION = "1.1"
+_VERSION = "2.0"
 
 sparseSEM_lib = Extension(name='sparseSEM.lassoSML',
                           sources=['sparseSEM/src/lassoSEM.c',
                                    'sparseSEM/src/lassoSMLv11beta.c',
                                    ],
                           include_dirs=['sparseSEM/src',
                                         '/opt/intel/oneapi/mkl/2023.1.0/include'],
```

### Comparing `sparseSEM-1.1/sparseSEM/elasticNetSML.py` & `sparseSEM-2.0/sparseSEM/elasticNetSML.py`

 * *Files 7% similar despite different names*

```diff
@@ -112,15 +112,16 @@
     Meinshausen, N. and P. Buhlmann, 2010 Stability selection. J. R. Stat. Soc. Series B. Stat. Methodol. 72: 417-473.
 
 """
 import ctypes
 import numpy as np
 from loadSEMlib import loadSEMlib
 import time
-def elasticNetSML(X, Y, Missing = None, B = None, verbose = 0):
+def elasticNetSEM(X, Y, Missing = None, B = None, verbose = 0):
+    this_call = locals()
     M, N = X.shape;
     if B is None:
         B = np.zeros(M,M);
     if Missing is None:
         Missing = np.zeros(M,N);
 
     if B.shape == (M,M) and Y.shape == (M,N):
@@ -143,33 +144,40 @@
     f = np.asfortranarray(f);
     f = f.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
     stat = np.asfortranarray(stat);
     stat = stat.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
 
     m = ctypes.c_int(M);
     n = ctypes.c_int(N);
+    hyperparameters = np.zeros(2);
+    hyperparameters = np.asfortranarray(hyperparameters);
+    hyperparameters = hyperparameters.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
     v = ctypes.c_int(verbose);
     startTime = time.time();
-    semlib.mainSML_adaEN(Y, X, m, n, Missing, B, f, stat, v);
+    semlib.mainSML_adaEN(Y, X, m, n, Missing, B, f, stat, hyperparameters, v);
     #void mainSML_adaEN(double *Y, double *X, int *m, int *n, int *Missing,double*B, double *f,double*stat,int*VB)
     endTime = time.time();
     runTime = endTime - startTime;
 
     if (verbose >= 0):
-        print(f"\t sparseSEM running time: ", runTime, " seconds \n");
+        print(f"\t sparseSEM running time: {runTime} seconds, verbose= {v} \n");
     output = dict();
     output['weight'] = np.ctypeslib.as_array(B, shape=(M, M));
     output["F"] = np.ctypeslib.as_array(f, shape=(1, M));
     output["statistics"] = [];
     stats = ["True positive",
                  "Total positive",
                  "False positive",
                 "Positive detected",
                 "Power of detection (PD)",
                  "False Discovery Rate (FDR)",
             ]
 
     for i in range(len(stats)):
         output["statistics"].append((stats[i], stat[i]) );
-
+    output['hyperparameters'] ={"alpha_factor": hyperparameters[0],
+                                "lambda_factor": hyperparameters[1]}
     output["runTime"] = runTime;
+    del this_call['Y']
+    del this_call['X']
+    output['call'] = this_call
     return output;
```

### Comparing `sparseSEM-1.1/sparseSEM/elasticNetSMLcv.py` & `sparseSEM-2.0/sparseSEM/elasticNetSMLcv.py`

 * *Files 4% similar despite different names*

```diff
@@ -105,15 +105,15 @@
 
 """
 import ctypes
 import numpy as np
 from loadSEMlib import loadSEMlib
 import time
 
-def elasticNetSMLcv(X, Y, Missing=None, B=None,
+def elasticNetSEMcv(X, Y, Missing=None, B=None,
                     alpha_factors = np.linspace(1, 0.05, 20),
                     lambda_factors =10**np.linspace(-0.2, -4, 20),
                     kFold = 5,
                     verbose=0):
     M, N = X.shape;
     if B is None:
         B = np.zeros(M*M).reshape(M,M);
@@ -163,48 +163,54 @@
     mse = np.asfortranarray(mse);
     mse = mse.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
     mseSte = np.asfortranarray(mseSte);
     mseSte = mseSte.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
     mseStd = np.asfortranarray(mseStd);
     mseStd = mseStd.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
     _kFold = ctypes.c_int(kFold);
-
+    hyperparameters = np.zeros(2);
+    hyperparameters = np.asfortranarray(hyperparameters);
+    hyperparameters = hyperparameters.ctypes.data_as(ctypes.POINTER(ctypes.c_double));
     m = ctypes.c_int(M);
     n = ctypes.c_int(N);
     v = ctypes.c_int(verbose);
     startTime = time.time();
 
     semlib.mainSML_adaENcv(Y, X, m, n, Missing, B, f, stat,
                            alpha_factors, _nAlpha,
                            lambda_factors,_nLambda,
                            mse, mseSte, mseStd,
-                           _kFold, v);
+                           _kFold,
+                           hyperparameters,
+                           v);
 
     endTime = time.time();
     runTime = endTime - startTime;
 
     if (verbose >= 0):
         print(f"\t sparseSEM CV running time: ", runTime, " seconds \n");
     output = dict();
-    output['weight'] = np.ctypeslib.as_array(B, shape=(M, M));
-    output["F"] = np.ctypeslib.as_array(f, shape=(1, M));
-
-    output["statistics"] = [];
+    fit = dict();
+    fit['weight'] = np.ctypeslib.as_array(B, shape=(M, M));
+    fit["F"] = np.ctypeslib.as_array(f, shape=(1, M));
+    fit['hyperparameters'] ={"alpha_factor": hyperparameters[0],
+                                "lambda_factor": hyperparameters[1]}
+    fit["statistics"] = [];
     stats = ["True positive",
              "Total positive",
              "False positive",
              "Positive detected",
              "Power of detection (PD)",
              "False Discovery Rate (FDR)",
              ]
 
     for i in range(len(stats)):
-        output["statistics"].append((stats[i], stat[i]));
+        fit["statistics"].append((stats[i], stat[i]));
 
     mse = np.ctypeslib.as_array(mse, shape=(nAlpha*nLambda, 1));
     mseSte = np.ctypeslib.as_array(mseSte, shape=(nAlpha * nLambda, 1));
     output["cv"] = np.column_stack((parameters, mse, mse) );
-
+    output['fit'] = fit
     output["runTime"] = runTime;
     return output;
```

### Comparing `sparseSEM-1.1/sparseSEM/elasticNetSMLpoint.py` & `sparseSEM-2.0/sparseSEM/elasticNetSMLpoint.py`

 * *Files 0% similar despite different names*

```diff
@@ -105,18 +105,18 @@
 
 """
 import ctypes
 import numpy as np
 from loadSEMlib import loadSEMlib
 import time
 
-def elasticNetSMLpoint(X, Y, Missing=None, B=None,
-                    alpha_factor = 1,
-                    lambda_factor =0.01,
-                    verbose=0):
+def elasticNetSEMpoint(X, Y, Missing=None, B=None,
+                       alpha_factor = 1,
+                       lambda_factor =0.01,
+                       verbose=0):
     M, N = X.shape;
     if B is None:
         B = np.zeros(M*M).reshape(M,M);
     if Missing is None:
         Missing = np.zeros(M*N).reshape(M,N);
 
     if B.shape == (M, M) and Y.shape == (M, N):
```

### Comparing `sparseSEM-1.1/sparseSEM/loadSEMlib.py` & `sparseSEM-2.0/sparseSEM/loadSEMlib.py`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/sparseSEM/sparseSEM.cpython-310-darwin.so` & `sparseSEM-2.0/sparseSEM/sparseSEM.cpython-310-darwin.so`

 * *Files 10% similar despite different names*

#### strings -a -n 8 {}

```diff
@@ -1,16 +1,17 @@
 __stub_helper
 __cstring
 __unwind_info
 __nl_symbol_ptr
 __la_symbol_ptr
 __LINKEDIT
+@rpath/libmkl_rt.2.dylib
 /usr/lib/libSystem.B.dylib
-/usr/local/anaconda3/lib
-/usr/local/anaconda3/lib
+/usr/local/anaconda3/envs/sparseSEM-env/lib
+/usr/local/anaconda3/envs/sparseSEM-env/lib
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
 h[A\A]A^A_]
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
@@ -30,33 +31,40 @@
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
+?ffffff.
 [A\A]A^A_]
 AWAVAUATSH
 QSPQAUQAT
 x[A\A]A^A_]
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
+)ffffff.
 [A\A]A^A_]
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
 [A\A]A^A_]
 AWAVAUATSH
+8ffffff.
+7ffffff.
 [A\A]A^A_]
 AWAVAUATSH
+t+fffff.
 [A\A]A^A_]
 AWAVAUATSH
+EHPAVARh
 [A\A]A^A_]
 AWAVAUATSH
+AVASATPh
 [A\A]A^A_]
 								Enter Function: Ridge Regression. Shrinkage ratio rho is: %f.
 									 Gene number: %d,	 shrinkage rho: %f
 								Exit function: Ridge Regression. sigma^2 is: %f.
 				Enter Function: weighted_LassoSf. The maximum lambda is: %f
 					 updating gene %d 
 							 gene %d 	 interact with gene %d.	Linear equation
@@ -82,42 +90,41 @@
 			 step 1 SML lasso regression, lambda: %f.
 			 cv: %d 	end; err_mean = %f.
 			 %d/Nlambdas. %d fold cv; 	 Err_Mean: %f; std:%f; 	 sigma2learnt:%f.
 		Exit Function: cv_support. optimal lambda index: %d.
 Step 1: CV support; return number of lambda needed: %d
 	%d/%d lambdas. 	lambda_factor: %f
 	lambda: %f
+					 updating Node %d 
+							 gene %d 	 interact with Node %d.	Quadratic equation
+							 Node %d 	 interact with Node %d.	Linear equation
+							 Node %d 	 interact with Node %d.	Quadratic equation
+		 updating Node %d 
+			 Node %d 	 interact with Node %d.	Linear equation
+			 Node %d 	 interact with Node %d.	Quadratic equation
 		i_alpha %d; 	 Enter Function: cv_support. Nlambdas: %d; 	 %d-fold cross validation.
 Step 1: ridge CV; find rho : %f
 	Adaptive_EN %d-fold CV, alpha: %f.
 Step 3: CV support; alpha: %f, number of lambda needed: %d
+SEM fit with alpha: %f, lambda: %f
 	Adaptive_EN %d-fold CV for ridge-weight, alpha: %f.
 Step 3: ridge; calculate weights.
 			 step 2 SML ZeroRegression.
 Step 2: ridge; calculate weights.
 Step 4: lasso selection path.
 Step 5: Finish calculation; detection power in stat vector.
 Step 4: lasso/elasticNet selection path.
 @dyld_stub_binder
 @_calloc
->@_dasum
-q >@_daxpy
-q(>@_dcopy
-q0>@_ddot
-q8>@_dgemm
-q@>@_dgemv
-qH>@_dgesv
-qP>@_dnrm2
-qX>@_dscal
-q`>@_dsyevd
-qp>@_idamax
+@_dsyevd
+@_idamax
 @_printf
 @_putchar
 UpdateIBinv
-Weighted_LassoSf
+}Weighted_LassoSf
 lambdaMax
 printMat
 onstrained_ridge_cff
 v_gene_nets_support_
 pointLambda
 stabilitySelection
 _QlambdaMiddle
```

#### llvm-readobj --file-headers {}

```diff
@@ -3,16 +3,16 @@
 Arch: x86_64
 AddressSize: 64bit
 MachHeader {
   Magic: Magic64 (0xFEEDFACF)
   CpuType: X86-64 (0x1000007)
   CpuSubType: CPU_SUBTYPE_X86_64_ALL (0x3)
   FileType: Bundle (0x8)
-  NumOfLoadCommands: 14
-  SizeOfLoadCommands: 1312
+  NumOfLoadCommands: 15
+  SizeOfLoadCommands: 1400
   Flags [ (0x85)
     MH_DYLDLINK (0x4)
     MH_NOUNDEFS (0x1)
     MH_TWOLEVEL (0x80)
   ]
   Reserved: 0x0
 }
```

#### llvm-readobj --needed-libs {}

```diff
@@ -1,7 +1,8 @@
 
 Format: Mach-O 64-bit x86-64
 Arch: x86_64
 AddressSize: 64bit
 NeededLibraries [
   /usr/lib/libSystem.B.dylib
+  @rpath/libmkl_rt.2.dylib
 ]
```

#### llvm-readobj --symbols {}

```diff
@@ -7,440 +7,429 @@
     Name: _QlambdaMiddle (2)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x4100
+    Value: 0x3920
   }
   Symbol {
     Name: _QlambdaMiddleCenter (17)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x4540
+    Value: 0x3D60
   }
   Symbol {
     Name: _QlambdaStart (38)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x3E50
+    Value: 0x3670
   }
   Symbol {
     Name: _UpdateIBinv (52)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x4A40
+    Value: 0x4260
   }
   Symbol {
     Name: _UpdateIBinvPermute (65)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x4810
+    Value: 0x4030
   }
   Symbol {
     Name: _Weighted_LassoSf (85)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x4BF0
+    Value: 0x4410
   }
   Symbol {
     Name: _Weighted_LassoSf_MLf (103)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x5DE0
+    Value: 0x5620
   }
   Symbol {
     Name: _Weighted_LassoSf_MLf_adaEN (125)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0xB350
+    Value: 0xAD40
   }
   Symbol {
     Name: _Weighted_LassoSf_adaEN (153)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0xA0B0
+    Value: 0x9A70
   }
   Symbol {
     Name: _centerYX (177)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x2BA0
+    Value: 0x23B0
   }
   Symbol {
     Name: _constrained_ridge_cff (187)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x2D80
+    Value: 0x2590
   }
   Symbol {
     Name: _cv_gene_nets_support_Rdg (210)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x7B50
+    Value: 0x73E0
   }
   Symbol {
     Name: _cv_gene_nets_support_adaEN (236)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0xD110
+    Value: 0xCB70
   }
   Symbol {
     Name: _cv_gene_nets_support_adaENcv (264)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0xF950
+    Value: 0xF580
   }
   Symbol {
     Name: _lambdaMax (294)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x3BB0
+    Value: 0x33D0
   }
   Symbol {
     Name: _lambdaMax_adaEN (305)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x9DA0
+    Value: 0x9760
   }
   Symbol {
     Name: _mainSML (322)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x9440
+    Value: 0x8CC0
   }
   Symbol {
     Name: _mainSML_adaEN (331)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0xEBD0
+    Value: 0xE630
   }
   Symbol {
     Name: _mainSML_adaENcv (346)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x114F0
+    Value: 0x110C0
   }
   Symbol {
     Name: _mainSML_adaENpointLambda (363)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x12120
+    Value: 0x11E10
   }
   Symbol {
     Name: _mainSML_adaENstabilitySelection (389)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x12B40
+    Value: 0x128D0
   }
   Symbol {
     Name: _printMat (422)
     Extern
     Type: Section (0xE)
     Section: __text (0x1)
     RefType: UndefinedNonLazy (0x0)
     Flags [ (0x0)
     ]
-    Value: 0x2B00
+    Value: 0x2310
   }
   Symbol {
     Name: _calloc (432)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dasum (440)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _daxpy (447)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dcopy (454)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _ddot (461)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dgemm (467)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dgemv (474)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dgesv (481)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dnrm2 (488)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dscal (495)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _dsyevd (502)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _free (510)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _idamax (516)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0xFE00)
-      AltEntry (0x200)
-      ColdFunc (0x400)
+    Flags [ (0x100)
+      SymbolResolver (0x100)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _log (524)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _pow (529)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _printf (534)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _putchar (542)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: _puts (551)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
   Symbol {
     Name: dyld_stub_binder (557)
     Extern
     Type: Undef (0x0)
     Section:  (0x0)
     RefType: UndefinedNonLazy (0x0)
-    Flags [ (0x100)
-      SymbolResolver (0x100)
+    Flags [ (0x200)
+      AltEntry (0x200)
     ]
     Value: 0x0
   }
 ]
```

#### x86_64

##### llvm-objdump --arch=x86_64 --section=__TEXT,__text --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -7,45 +7,45 @@
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
 	subq	$24, %rsp
 	movl	%edx, -48(%rbp)
 	movl	%esi, %ebx
 	movq	%rdi, %r15
-	leaq	69576(%rip), %rdi ## literal pool for: "Printing the matrix\n"
-	callq	0x13556 ## symbol stub for: _puts
+	leaq	71240(%rip), %rdi ## literal pool for: "Printing the matrix\n"
+	callq	0x133d0 ## symbol stub for: _puts
 	testl	%ebx, %ebx
-	jle	0x2b8e
+	jle	0x239d
 	movl	-48(%rbp), %eax
 	movq	%rax, -56(%rbp)
 	movl	$0, -44(%rbp)
-	leaq	68850(%rip), %r12 ## literal pool for: "%f\t"
-	jmp	0x2b57
+	leaq	70514(%rip), %r12 ## literal pool for: "%f\t"
+	jmp	0x2366
 	movl	$10, %edi
-	callq	0x13550 ## symbol stub for: _putchar
+	callq	0x133ca ## symbol stub for: _putchar
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	%ebx, %eax
-	je	0x2b8e
+	je	0x239d
 	cmpl	$0, -48(%rbp)
-	jle	0x2b40
+	jle	0x2350
 	movq	-56(%rbp), %r14
 	movl	-44(%rbp), %eax
 	movl	%eax, %r13d
-	nopw	(%rax,%rax)
+	nopw	%cs:(%rax,%rax)
 	movslq	%r13d, %r13
 	movsd	(%r15,%r13,8), %xmm0
 	movq	%r12, %rdi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	addl	%ebx, %r13d
-	addq	$-1, %r14
-	jne	0x2b70
-	jmp	0x2b40
+	decq	%r14
+	jne	0x2380
+	jmp	0x2350
 	addq	$24, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
@@ -68,26 +68,26 @@
 	movl	%r9d, -48(%rbp)
 	movl	$1, -56(%rbp)
 	movl	$1, -52(%rbp)
 	movl	$0, -80(%rbp)
 	movl	%r8d, -76(%rbp)
 	movslq	%r9d, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -112(%rbp)
 	movq	$0, -104(%rbp)
 	leaq	-48(%rbp), %rdi
 	leaq	-112(%rbp), %r15
 	leaq	-80(%rbp), %rdx
 	leaq	-56(%rbp), %r8
 	movq	%r15, %rsi
 	movq	%r13, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movb	$78, -41(%rbp)
 	subq	$8, %rsp
 	leaq	-52(%rbp), %rax
 	leaq	-104(%rbp), %r10
 	leaq	-41(%rbp), %rdi
 	leaq	-60(%rbp), %r14
 	leaq	-76(%rbp), %r9
@@ -100,15 +100,15 @@
 	pushq	%rax
 	movq	-96(%rbp), %r15
 	pushq	%r15
 	pushq	%r10
 	leaq	-56(%rbp), %rax
 	pushq	%rax
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$40, %rsp
 	leaq	-41(%rbp), %rdi
 	movq	%r14, %rsi
 	leaq	-48(%rbp), %rdx
 	leaq	-112(%rbp), %rcx
 	movq	-88(%rbp), %r8
 	movq	%rbx, %r9
@@ -117,37 +117,37 @@
 	pushq	%r12
 	leaq	-104(%rbp), %rax
 	pushq	%rax
 	leaq	-56(%rbp), %r14
 	pushq	%r14
 	movq	%r13, -120(%rbp)
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	cvtsi2sdl	-48(%rbp), %xmm0
-	movsd	67970(%rip), %xmm1
+	movsd	69602(%rip), %xmm1
 	divsd	%xmm0, %xmm1
 	movsd	%xmm1, -72(%rbp)
 	leaq	-72(%rbp), %r13
 	leaq	-60(%rbp), %rbx
 	movq	%rbx, %rdi
 	movq	%r13, %rsi
 	movq	%r12, -136(%rbp)
 	movq	%r12, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	%rbx, %rdi
 	movq	%r13, %rsi
 	movq	%r15, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	cmpl	$0, -48(%rbp)
-	jle	0x2d5e
+	jle	0x256d
 	xorl	%ebx, %ebx
 	nop
 	movl	-60(%rbp), %eax
 	imull	%ebx, %eax
 	cltq
 	movq	-128(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r13
@@ -157,27 +157,27 @@
 	movq	%r15, %rdi
 	leaq	-72(%rbp), %r12
 	movq	%r12, %rsi
 	movq	-136(%rbp), %rdx
 	leaq	-56(%rbp), %r14
 	movq	%r14, %rcx
 	leaq	-52(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r15, %rdi
 	movq	%r12, %rsi
 	movq	-96(%rbp), %rdx
 	movq	%r14, %rcx
 	movq	%r13, %r8
 	leaq	-52(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	addl	$1, %ebx
+	callq	0x13376 ## symbol stub for: _daxpy
+	incl	%ebx
 	cmpl	-48(%rbp), %ebx
-	jl	0x2d00
+	jl	0x2510
 	movq	-120(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$104, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
@@ -202,192 +202,192 @@
 	movl	%ecx, -72(%rbp)
 	movl	%ecx, %r14d
 	movl	%ecx, -144(%rbp)
 	movslq	%edx, %rbx
 	movq	%rbx, -152(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -264(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -256(%rbp)
 	movl	%r14d, %eax
 	imull	%ebx, %eax
 	movl	%eax, -100(%rbp)
 	movslq	%eax, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r12
 	movl	$1, -64(%rbp)
 	movl	$1, -60(%rbp)
 	leaq	-100(%rbp), %rbx
 	leaq	-64(%rbp), %r14
 	leaq	-60(%rbp), %r8
 	movq	%rbx, %rdi
 	movq	-136(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r13, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%rbx, %rdi
 	movq	-120(%rbp), %rsi
 	movq	%r14, %rdx
 	movl	-144(%rbp), %ebx
 	movq	%r12, %rcx
 	leaq	-60(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r13, -168(%rbp)
 	movq	%r13, %rdi
 	movq	%r12, -192(%rbp)
 	movq	%r12, %rsi
 	movq	-264(%rbp), %rdx
 	movq	-256(%rbp), %rcx
 	movq	-152(%rbp), %r8
 	movl	%ebx, %r9d
 	callq	_centerYX
 	cmpl	$8, 24(%rbp)
-	jl	0x2ec4
-	leaq	67974(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t\tEnter Function: Ridge Regression. Shrinkage ratio rho is: %f.\n\n"
+	jl	0x26d4
+	leaq	69638(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t\tEnter Function: Ridge Regression. Shrinkage ratio rho is: %f.\n\n"
 	movsd	-272(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %r15d
 	movl	-72(%rbp), %ebx
 	leal	-1(%r15), %ecx
 	movl	%ecx, -52(%rbp)
 	movl	%ebx, %eax
 	imull	%ecx, %eax
 	movl	%ecx, %r12d
 	movslq	%eax, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -144(%rbp)
 	movl	%ebx, %eax
 	imull	%ebx, %eax
 	movslq	%eax, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -200(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -120(%rbp)
 	movslq	%ebx, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -152(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -128(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -216(%rbp)
 	movb	$78, -42(%rbp)
 	movb	$78, -41(%rbp)
 	movl	%r12d, %ebx
 	movl	%r12d, %eax
 	imull	%r12d, %eax
 	movl	%eax, -240(%rbp)
 	movl	%r13d, -236(%rbp)
 	movslq	%eax, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -280(%rbp)
 	movslq	%ebx, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -136(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -304(%rbp)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -96(%rbp)
 	movq	$0, -112(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -328(%rbp)
 	movb	$78, -82(%rbp)
 	movb	$85, -81(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -320(%rbp)
 	leal	(%rbx,%rbx,4), %eax
 	addl	$10, %eax
 	movl	%eax, -232(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -312(%rbp)
 	movl	$10, -228(%rbp)
 	movl	$10, %edi
 	movl	$4, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -296(%rbp)
 	movl	$0, -156(%rbp)
 	movl	$4, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -288(%rbp)
 	testl	%r15d, %r15d
-	jle	0x3692
+	jle	0x2eba
 	xorl	%r12d, %r12d
 	leaq	-72(%rbp), %rbx
-	jmp	0x3081
+	jmp	0x2890
 	nopw	(%rax,%rax)
-	addq	$1, %r12
+	incq	%r12
 	cmpq	%r15, %r12
 	leaq	-72(%rbp), %rbx
-	jge	0x3692
+	jge	0x2eba
 	movq	-192(%rbp), %rax
 	leaq	(%rax,%r12,8), %rsi
 	movq	%rbx, %rdi
 	leaq	-56(%rbp), %rdx
 	movq	-152(%rbp), %r13
 	movq	%r13, %rcx
 	leaq	-64(%rbp), %r15
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%rbx, %rdi
 	movq	%r13, %rsi
 	movq	%r15, %rdx
 	movq	-128(%rbp), %rcx
 	leaq	-60(%rbp), %r14
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	-168(%rbp), %rax
 	leaq	(%rax,%r12,8), %rsi
 	movq	%rbx, %rdi
 	leaq	-56(%rbp), %rdx
 	movq	-216(%rbp), %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%rbx, %rdi
 	movq	%r13, %rsi
 	movq	%r15, %rdx
 	movq	%r13, %rcx
 	movq	%r14, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movapd	%xmm0, %xmm1
-	movsd	66869(%rip), %xmm0
+	movsd	68502(%rip), %xmm0
 	movsd	%xmm1, -176(%rbp)
 	divsd	%xmm1, %xmm0
 	movsd	%xmm0, -224(%rbp)
 	movb	$78, -41(%rbp)
 	movl	-72(%rbp), %eax
 	movl	%eax, -48(%rbp)
 	movl	%eax, -68(%rbp)
@@ -407,92 +407,89 @@
 	leaq	-112(%rbp), %rax
 	pushq	%rax
 	pushq	%r14
 	pushq	-128(%rbp)
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%r13
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	leaq	-236(%rbp), %rdi
 	leaq	-224(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movsd	66723(%rip), %xmm1
+	callq	0x133a0 ## symbol stub for: _dscal
+	movsd	68356(%rip), %xmm1
 	movl	-72(%rbp), %r8d
 	testl	%r8d, %r8d
-	jle	0x3224
+	jle	0x2a34
 	cmpl	$1, %r8d
-	jne	0x31b0
+	jne	0x29c0
 	xorl	%ecx, %ecx
-	jmp	0x3203
+	jmp	0x2a13
 	nopw	%cs:(%rax,%rax)
-	nop
 	movl	%r8d, %edx
 	andl	$-2, %edx
 	leal	1(%r8), %esi
 	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
 	nopw	%cs:(%rax,%rax)
-	nop
 	movslq	%ebx, %rbx
 	movsd	(%r15,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r15,%rbx,8)
 	leal	(%rsi,%rbx), %eax
 	cltq
 	movsd	(%r15,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r15,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
 	cmpq	%rcx, %rdx
-	jne	0x31d0
+	jne	0x29e0
 	testb	$1, %r8b
-	je	0x3224
+	je	0x2a34
 	movl	%r8d, %edx
 	imull	%ecx, %edx
 	addl	%ecx, %edx
 	movslq	%edx, %rcx
 	movsd	(%r15,%rcx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r15,%rcx,8)
 	movl	-56(%rbp), %edx
 	testl	%edx, %edx
 	leaq	-72(%rbp), %r13
-	jle	0x329b
+	jle	0x2aab
 	xorl	%ebx, %ebx
 	movq	-168(%rbp), %r15
 	xorl	%r14d, %r14d
 	movq	-120(%rbp), %rcx
-	jmp	0x3260
+	jmp	0x2a6f
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
-	addq	$1, %rbx
+	incq	%rbx
 	movslq	%edx, %rax
 	addq	$8, %r15
 	cmpq	%rax, %rbx
-	jge	0x3290
+	jge	0x2aa0
 	cmpq	%rbx, %r12
-	je	0x3250
+	je	0x2a60
 	movq	%r13, %rdi
 	movq	%r15, %rsi
 	leaq	-56(%rbp), %rdx
 	leaq	-52(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	addl	$1, %r14d
+	callq	0x1337c ## symbol stub for: _dcopy
+	incl	%r14d
 	movslq	%r14d, %rax
 	movq	-120(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	movl	-56(%rbp), %edx
-	jmp	0x3250
-	nopl	(%rax)
+	jmp	0x2a60
+	nopw	(%rax,%rax)
 	movl	-72(%rbp), %r8d
 	movq	-200(%rbp), %r15
 	movl	-52(%rbp), %eax
 	movl	%eax, -48(%rbp)
 	movl	%r8d, -68(%rbp)
 	movl	%eax, -80(%rbp)
 	movl	%r8d, -76(%rbp)
@@ -513,15 +510,15 @@
 	leaq	-68(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	movq	-120(%rbp), %r15
 	pushq	%r15
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movb	$84, -41(%rbp)
 	movl	-52(%rbp), %eax
 	movl	%eax, -76(%rbp)
 	movl	%eax, -48(%rbp)
 	movl	%eax, -68(%rbp)
 	movl	%eax, -80(%rbp)
@@ -540,24 +537,24 @@
 	pushq	%rax
 	leaq	-68(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
 	leaq	-48(%rbp), %r15
 	pushq	%r15
 	pushq	%r14
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movb	$78, -41(%rbp)
 	leaq	-240(%rbp), %rdi
 	movq	%rbx, %rsi
 	leaq	-64(%rbp), %rdx
 	movq	-328(%rbp), %r14
 	movq	%r14, %rcx
 	leaq	-60(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-52(%rbp), %eax
 	movl	%eax, -48(%rbp)
 	subq	$8, %rsp
 	leaq	-82(%rbp), %rdi
 	leaq	-81(%rbp), %rsi
 	leaq	-52(%rbp), %rdx
 	movq	%r14, %rcx
@@ -568,63 +565,62 @@
 	pushq	%rax
 	leaq	-228(%rbp), %rax
 	pushq	%rax
 	pushq	-296(%rbp)
 	leaq	-232(%rbp), %rax
 	pushq	%rax
 	pushq	-312(%rbp)
-	callq	0x1352c ## symbol stub for: _dsyevd
+	callq	0x133a6 ## symbol stub for: _dsyevd
 	addq	$48, %rsp
 	movl	-52(%rbp), %r9d
 	leal	-1(%r9), %ecx
 	movslq	%ecx, %rcx
 	movsd	(%r14,%rcx,8), %xmm0
 	mulsd	-272(%rbp), %xmm0
 	cmpl	$9, 24(%rbp)
-	jl	0x340b
-	leaq	66703(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t\t\t Gene number: %d,\t shrinkage rho: %f\n"
+	jl	0x2c1b
+	leaq	68367(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t\t\t Gene number: %d,\t shrinkage rho: %f\n"
 	movl	%r12d, %esi
 	movb	$1, %al
 	movsd	%xmm0, -208(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-208(%rbp), %xmm0
 	movl	-52(%rbp), %r9d
 	testl	%r9d, %r9d
 	movq	-136(%rbp), %r10
-	jle	0x349a
+	jle	0x2caa
 	movl	%r9d, %r8d
 	cmpl	$1, %r9d
-	jne	0x3430
+	jne	0x2c40
 	xorl	%edx, %edx
-	jmp	0x3480
+	jmp	0x2c90
 	nopl	(%rax,%rax)
 	movl	%r8d, %esi
 	andl	$-2, %esi
 	leal	1(%r9), %r11d
 	leal	(%r9,%r9), %edi
 	addl	$2, %edi
 	xorl	%ecx, %ecx
 	xorl	%edx, %edx
 	nopw	%cs:(%rax,%rax)
-	nop
 	movslq	%ecx, %rcx
 	movsd	(%rbx,%rcx,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%rbx,%rcx,8)
 	leal	(%r11,%rcx), %eax
 	cltq
 	movsd	(%rbx,%rax,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%rbx,%rax,8)
 	addq	$2, %rdx
 	addl	%edi, %ecx
 	cmpq	%rdx, %rsi
-	jne	0x3450
+	jne	0x2c60
 	testb	$1, %r8b
-	je	0x349a
+	je	0x2caa
 	movl	%r9d, %eax
 	imull	%edx, %eax
 	addl	%edx, %eax
 	cltq
 	addsd	(%rbx,%rax,8), %xmm0
 	movsd	%xmm0, (%rbx,%rax,8)
 	movl	%r9d, -48(%rbp)
@@ -641,15 +637,15 @@
 	leaq	-112(%rbp), %rax
 	pushq	%rax
 	movq	%r13, %r14
 	leaq	-64(%rbp), %r13
 	pushq	%r13
 	movq	-216(%rbp), %r13
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	movl	-52(%rbp), %eax
 	movl	%eax, -48(%rbp)
 	movl	%eax, -68(%rbp)
 	leaq	-52(%rbp), %r15
 	movq	%r15, %rdi
 	leaq	-64(%rbp), %rsi
@@ -658,15 +654,15 @@
 	movq	%rbx, %rcx
 	movq	-288(%rbp), %r8
 	movq	-136(%rbp), %r9
 	leaq	-156(%rbp), %rax
 	pushq	%rax
 	leaq	-68(%rbp), %rax
 	pushq	%rax
-	callq	0x1351a ## symbol stub for: _dgesv
+	callq	0x13394 ## symbol stub for: _dgesv
 	addq	$16, %rsp
 	movl	-52(%rbp), %eax
 	movl	%eax, -48(%rbp)
 	subq	$8, %rsp
 	leaq	-42(%rbp), %rdi
 	movq	%r15, %rsi
 	movq	%r14, %rdx
@@ -679,151 +675,154 @@
 	pushq	%r15
 	leaq	-112(%rbp), %rax
 	pushq	%rax
 	leaq	-64(%rbp), %rax
 	pushq	%rax
 	movq	-152(%rbp), %rbx
 	pushq	%rbx
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	movq	%r14, %rdi
 	movq	%rbx, %rsi
 	leaq	-64(%rbp), %rbx
 	movq	%rbx, %rdx
 	movq	%r13, %rcx
 	movq	-136(%rbp), %r14
 	leaq	-60(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -208(%rbp)
 	leaq	-52(%rbp), %rdi
 	movq	%r15, %rsi
 	movq	%rbx, %rdx
 	leaq	-60(%rbp), %r8
 	movq	%r14, %rcx
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	-208(%rbp), %xmm1
 	subsd	%xmm0, %xmm1
 	divsd	-176(%rbp), %xmm1
 	movq	-336(%rbp), %rax
 	movsd	%xmm1, (%rax,%r12,8)
 	movslq	-56(%rbp), %r15
 	testq	%r15, %r15
-	jle	0x3070
+	jle	0x2880
 	movl	%r15d, %r8d
 	cmpl	$1, %r15d
-	jne	0x3620
-	xorl	%ebx, %ebx
-	xorl	%ecx, %ecx
+	jne	0x2e10
+	xorl	%eax, %eax
+	xorl	%edx, %edx
 	testb	$1, %r8b
-	je	0x3070
-	cmpq	%r12, %rbx
-	je	0x3070
-	movslq	%ecx, %rax
-	movsd	(%r14,%rax,8), %xmm0
-	imull	%r15d, %ebx
-	addl	%r12d, %ebx
-	movslq	%ebx, %rax
-	movq	-184(%rbp), %rcx
-	movsd	%xmm0, (%rcx,%rax,8)
-	jmp	0x3070
-	nopl	(%rax)
+	jne	0x2e8e
+	jmp	0x2880
+	nopw	%cs:(%rax,%rax)
 	movl	%r8d, %r10d
 	andl	$-2, %r10d
 	leal	(%r15,%r15), %r9d
-	xorl	%esi, %esi
-	movl	%r12d, %edi
 	xorl	%ecx, %ecx
-	movq	-184(%rbp), %rdx
-	jmp	0x3656
+	movl	%r12d, %ebx
+	xorl	%edx, %edx
+	movq	-184(%rbp), %rsi
+	jmp	0x2e3b
 	nopl	(%rax,%rax)
-	movq	%rsi, %rbx
-	addq	$2, %rbx
-	addl	%r9d, %edi
-	addq	$1, %rax
-	movq	%rax, %rsi
-	cmpq	%rbx, %r10
-	je	0x35e6
-	cmpq	%rsi, %r12
-	je	0x366f
-	movslq	%ecx, %rcx
-	movsd	(%r14,%rcx,8), %xmm0
-	movslq	%edi, %rax
-	movsd	%xmm0, (%rdx,%rax,8)
-	addl	$1, %ecx
-	leaq	1(%rsi), %rax
+	addl	%r9d, %ebx
+	incq	%rcx
+	cmpq	%r10, %rcx
+	je	0x2e80
+	movq	%rcx, %rax
+	cmpq	%rcx, %r12
+	je	0x2e56
+	movslq	%edx, %rdx
+	movsd	(%r14,%rdx,8), %xmm0
+	movslq	%ebx, %rcx
+	movsd	%xmm0, (%rsi,%rcx,8)
+	incl	%edx
+	leaq	1(%rax), %rcx
+	cmpq	%r12, %rcx
+	je	0x2e30
+	movslq	%edx, %rdx
+	movsd	(%r14,%rdx,8), %xmm0
+	leal	(%r15,%rbx), %edi
+	movslq	%edi, %rdi
+	movsd	%xmm0, (%rsi,%rdi,8)
+	incl	%edx
+	jmp	0x2e30
+	nopl	(%rax,%rax)
+	addq	$2, %rax
+	testb	$1, %r8b
+	je	0x2880
 	cmpq	%r12, %rax
-	je	0x3640
-	movslq	%ecx, %rcx
+	je	0x2880
+	movslq	%edx, %rcx
 	movsd	(%r14,%rcx,8), %xmm0
-	leal	(%r15,%rdi), %ebx
-	movslq	%ebx, %rbx
-	movsd	%xmm0, (%rdx,%rbx,8)
-	addl	$1, %ecx
-	jmp	0x3640
+	imull	%r15d, %eax
+	addl	%r12d, %eax
+	cltq
+	movq	-184(%rbp), %rcx
+	movsd	%xmm0, (%rcx,%rax,8)
+	jmp	0x2880
 	imull	%r15d, %r15d
 	movl	%r15d, -244(%rbp)
 	movslq	%r15d, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	leaq	-244(%rbp), %rbx
 	leaq	-64(%rbp), %r15
 	leaq	-60(%rbp), %r8
 	movq	%rbx, %rdi
 	movq	-184(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -224(%rbp)
 	leaq	-224(%rbp), %rsi
 	movq	%rbx, %rdi
 	movq	%r13, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	-56(%rbp), %r14d
 	testl	%r14d, %r14d
-	jle	0x378f
+	jle	0x2fbf
 	xorl	%eax, %eax
 	cmpl	$1, %r14d
-	je	0x3768
+	je	0x2f98
 	movl	%r14d, %ecx
 	andl	$-2, %ecx
 	leal	1(%r14), %edx
 	leal	(%r14,%r14), %esi
 	addl	$2, %esi
 	xorl	%edi, %edi
-	movsd	65289(%rip), %xmm0
+	movsd	66897(%rip), %xmm0
 	xorl	%eax, %eax
-	nopl	(%rax)
+	nopw	%cs:(%rax,%rax)
 	movslq	%edi, %rdi
 	movsd	(%r13,%rdi,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r13,%rdi,8)
 	leal	(%rdx,%rdi), %ebx
 	movslq	%ebx, %rbx
 	movsd	(%r13,%rbx,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r13,%rbx,8)
 	addq	$2, %rax
 	addl	%esi, %edi
 	cmpq	%rax, %rcx
-	jne	0x3730
+	jne	0x2f60
 	testb	$1, %r14b
-	je	0x378f
+	je	0x2fbf
 	movl	%r14d, %ecx
 	imull	%eax, %ecx
 	addl	%eax, %ecx
 	movslq	%ecx, %rax
 	movsd	(%r13,%rax,8), %xmm0
-	addsd	65192(%rip), %xmm0
+	addsd	66792(%rip), %xmm0
 	movsd	%xmm0, (%r13,%rax,8)
 	movslq	-100(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movb	$78, -41(%rbp)
 	movl	%r14d, -76(%rbp)
 	movl	%r14d, -48(%rbp)
 	movl	%r14d, -68(%rbp)
 	movl	%r14d, -80(%rbp)
 	subq	$8, %rsp
 	leaq	-80(%rbp), %r14
@@ -840,103 +839,74 @@
 	movq	%rax, -128(%rbp)
 	pushq	%rax
 	pushq	%rbx
 	pushq	%r11
 	pushq	-168(%rbp)
 	pushq	%r10
 	pushq	%r13
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	cmpl	$0, -56(%rbp)
 	movq	-336(%rbp), %r14
-	jle	0x3863
+	jle	0x3092
 	xorl	%ebx, %ebx
 	movq	-192(%rbp), %r15
 	movq	-128(%rbp), %r12
 	nopw	%cs:(%rax,%rax)
-	nop
 	movsd	(%r14,%rbx,8), %xmm0
-	xorpd	65122(%rip), %xmm0
+	xorpd	66706(%rip), %xmm0
 	movlpd	%xmm0, -96(%rbp)
 	leaq	-72(%rbp), %rdi
 	leaq	-96(%rbp), %rsi
 	movq	%r15, %rdx
 	leaq	-76(%rbp), %rcx
 	movq	%r12, %r8
 	leaq	-56(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	addq	$1, %rbx
+	callq	0x13376 ## symbol stub for: _daxpy
+	incq	%rbx
 	movslq	-56(%rbp), %rax
 	addq	$8, %r12
 	addq	$8, %r15
 	cmpq	%rax, %rbx
-	jl	0x3820
+	jl	0x3050
 	movq	16(%rbp), %r12
 	leaq	-100(%rbp), %rdi
 	leaq	-64(%rbp), %rdx
 	leaq	-60(%rbp), %r15
 	movq	-128(%rbp), %rcx
 	movq	%rcx, %rsi
 	movq	%r15, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movl	-100(%rbp), %eax
-	addl	$-1, %eax
+	decl	%eax
 	cvtsi2sd	%eax, %xmm5
 	movl	-56(%rbp), %eax
 	testl	%eax, %eax
 	movq	-256(%rbp), %rbx
-	jle	0x3a33
-	cmpl	$4, %eax
-	jb	0x38bd
-	leaq	(%r14,%rax,8), %rcx
-	cmpq	%r12, %rcx
-	jbe	0x393b
-	leaq	(%r12,%rax,8), %rcx
-	cmpq	%r14, %rcx
-	jbe	0x393b
+	jle	0x3256
 	xorl	%ecx, %ecx
-	movq	%rcx, %rdx
-	notq	%rdx
-	testb	$1, %al
-	je	0x38e6
-	movsd	(%r14,%rcx,8), %xmm1
-	xorpd	64953(%rip), %xmm1
-	mulsd	(%rbx,%rcx,8), %xmm1
-	movsd	%xmm1, (%r12,%rcx,8)
-	orq	$1, %rcx
-	addq	%rax, %rdx
-	je	0x3a33
-	movapd	64921(%rip), %xmm1
-	nopw	(%rax,%rax)
-	movsd	(%r14,%rcx,8), %xmm2
-	xorpd	%xmm1, %xmm2
-	mulsd	(%rbx,%rcx,8), %xmm2
-	movsd	%xmm2, (%r12,%rcx,8)
-	movsd	8(%r14,%rcx,8), %xmm2
-	xorpd	%xmm1, %xmm2
-	mulsd	8(%rbx,%rcx,8), %xmm2
-	movsd	%xmm2, 8(%r12,%rcx,8)
-	addq	$2, %rcx
-	cmpq	%rcx, %rax
-	jne	0x3900
-	jmp	0x3a33
+	cmpl	$4, %eax
+	jb	0x31df
+	movq	%r12, %rdx
+	subq	%r14, %rdx
+	cmpq	$32, %rdx
+	jb	0x31df
 	movl	%eax, %ecx
 	andl	$-4, %ecx
 	leaq	-4(%rcx), %rdx
 	movq	%rdx, %r8
 	shrq	$2, %r8
-	addq	$1, %r8
+	incq	%r8
 	testq	%rdx, %rdx
-	je	0x3b9a
+	je	0x33bd
 	movq	%r8, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
 	xorl	%edx, %edx
-	movapd	64804(%rip), %xmm1
-	nopl	(%rax)
+	movapd	66524(%rip), %xmm1
+	nopw	%cs:(%rax,%rax)
 	movupd	(%r14,%rdx,8), %xmm2
 	movupd	16(%r14,%rdx,8), %xmm3
 	xorpd	%xmm1, %xmm2
 	xorpd	%xmm1, %xmm3
 	movupd	(%rbx,%rdx,8), %xmm4
 	mulpd	%xmm2, %xmm4
 	movupd	16(%rbx,%rdx,8), %xmm2
@@ -950,31 +920,55 @@
 	movupd	32(%rbx,%rdx,8), %xmm4
 	mulpd	%xmm2, %xmm4
 	movupd	48(%rbx,%rdx,8), %xmm2
 	mulpd	%xmm3, %xmm2
 	movupd	%xmm4, 32(%r12,%rdx,8)
 	movupd	%xmm2, 48(%r12,%rdx,8)
 	addq	$8, %rdx
-	addq	$2, %rdi
-	jne	0x3970
+	addq	$-2, %rdi
+	jne	0x3120
 	testb	$1, %r8b
-	je	0x3a2a
+	je	0x31da
 	movupd	(%r14,%rdx,8), %xmm1
 	movupd	16(%r14,%rdx,8), %xmm2
-	movapd	64654(%rip), %xmm3
+	movapd	66366(%rip), %xmm3
 	xorpd	%xmm3, %xmm1
 	xorpd	%xmm3, %xmm2
 	movupd	(%rbx,%rdx,8), %xmm3
 	mulpd	%xmm1, %xmm3
 	movupd	16(%rbx,%rdx,8), %xmm1
 	mulpd	%xmm2, %xmm1
 	movupd	%xmm3, (%r12,%rdx,8)
 	movupd	%xmm1, 16(%r12,%rdx,8)
 	cmpq	%rax, %rcx
-	jne	0x38bf
+	je	0x3256
+	movq	%rcx, %rdx
+	notq	%rdx
+	testb	$1, %al
+	je	0x3206
+	movsd	(%r14,%rcx,8), %xmm1
+	xorpd	66297(%rip), %xmm1
+	mulsd	(%rbx,%rcx,8), %xmm1
+	movsd	%xmm1, (%r12,%rcx,8)
+	orq	$1, %rcx
+	addq	%rax, %rdx
+	je	0x3256
+	movapd	66269(%rip), %xmm1
+	nopw	%cs:(%rax,%rax)
+	movsd	(%r14,%rcx,8), %xmm2
+	xorpd	%xmm1, %xmm2
+	mulsd	(%rbx,%rcx,8), %xmm2
+	movsd	%xmm2, (%r12,%rcx,8)
+	movsd	8(%r14,%rcx,8), %xmm2
+	xorpd	%xmm1, %xmm2
+	mulsd	8(%rbx,%rcx,8), %xmm2
+	movsd	%xmm2, 8(%r12,%rcx,8)
+	addq	$2, %rcx
+	cmpq	%rcx, %rax
+	jne	0x3220
 	divsd	%xmm5, %xmm0
 	movsd	%xmm0, -176(%rbp)
 	movabsq	$4607182418800017408, %rcx
 	movq	%rcx, -112(%rbp)
 	movl	%eax, -76(%rbp)
 	movl	%eax, -48(%rbp)
 	movq	%rcx, -96(%rbp)
@@ -989,74 +983,74 @@
 	pushq	%r12
 	leaq	-112(%rbp), %rax
 	pushq	%rax
 	leaq	-64(%rbp), %rax
 	pushq	%rax
 	movq	-264(%rbp), %r14
 	pushq	%r14
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	cmpl	$8, 24(%rbp)
-	jl	0x3aae
-	leaq	65036(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t\tExit function: Ridge Regression. sigma^2 is: %f.\n\n"
+	jl	0x32d1
+	leaq	66681(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t\tExit function: Ridge Regression. sigma^2 is: %f.\n\n"
 	movsd	-176(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-144(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-280(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-136(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-304(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-128(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-120(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-152(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-216(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-328(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-320(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-296(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-288(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movsd	-176(%rbp), %xmm0
 	addq	$296, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
 	xorl	%edx, %edx
 	testb	$1, %r8b
-	jne	0x39ed
-	jmp	0x3a2a
-	nopl	(%rax,%rax)
+	jne	0x319d
+	jmp	0x31da
+	nop
 _lambdaMax:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -1068,101 +1062,100 @@
 	movq	%rsi, %r12
 	movq	%rdi, -112(%rbp)
 	movl	%ecx, -44(%rbp)
 	movl	%r8d, -52(%rbp)
 	movslq	%ecx, %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movl	$1, -56(%rbp)
 	movl	$1, -88(%rbp)
 	movl	%r15d, -64(%rbp)
 	testl	%r15d, %r15d
 	movq	%rax, -96(%rbp)
-	jle	0x3c71
+	jle	0x3490
 	xorl	%r14d, %r14d
 	movq	%r12, -120(%rbp)
 	movq	-112(%rbp), %r15
 	nopl	(%rax)
 	leaq	-52(%rbp), %rbx
 	movq	%rbx, %rdi
 	movq	%r12, %rsi
 	leaq	-64(%rbp), %rdx
 	movq	%r12, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -72(%rbp)
 	movq	%rbx, %rdi
 	movq	%r12, %rsi
 	leaq	-64(%rbp), %rdx
 	movq	%r15, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movq	-96(%rbp), %rax
 	divsd	-72(%rbp), %xmm0
 	movsd	%xmm0, (%rax,%r14,8)
-	addq	$1, %r14
+	incq	%r14
 	movslq	-44(%rbp), %rbx
 	addq	$8, %r15
 	addq	$8, %r12
 	cmpq	%rbx, %r14
-	jl	0x3c10
+	jl	0x3430
 	movl	-52(%rbp), %r14d
 	movq	-120(%rbp), %r12
 	imull	%ebx, %r14d
 	movl	%r14d, -60(%rbp)
 	movslq	%r14d, %rdi
 	movl	$8, %esi
 	movq	%rax, %r15
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	-60(%rbp), %rdi
 	leaq	-56(%rbp), %rdx
 	leaq	-88(%rbp), %r8
 	movq	%r12, %rsi
 	movq	%rax, -72(%rbp)
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$0, -44(%rbp)
-	jle	0x3cf7
+	jle	0x3516
 	xorl	%r14d, %r14d
 	leaq	-44(%rbp), %rbx
 	movq	-72(%rbp), %r12
 	nopw	%cs:(%rax,%rax)
-	nop
 	movsd	(%r15,%r14,8), %xmm0
-	xorpd	63938(%rip), %xmm0
+	xorpd	65538(%rip), %xmm0
 	movlpd	%xmm0, -80(%rbp)
 	leaq	-52(%rbp), %rdi
 	leaq	-80(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	addq	$1, %r14
+	callq	0x133a0 ## symbol stub for: _dscal
+	incq	%r14
 	movslq	-44(%rbp), %rax
 	addq	$8, %r12
 	cmpq	%rax, %r14
-	jl	0x3cc0
+	jl	0x34e0
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -80(%rbp)
 	leaq	-60(%rbp), %rdi
 	leaq	-80(%rbp), %r14
 	leaq	-56(%rbp), %rcx
 	movq	%r14, %rsi
 	movq	-112(%rbp), %r15
 	movq	%r15, %rdx
 	movq	-72(%rbp), %r12
 	movq	%r12, %r8
 	movq	%rcx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movl	-44(%rbp), %eax
 	imull	%eax, %eax
 	movl	%eax, -84(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	movb	$78, -46(%rbp)
 	movb	$84, -45(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -80(%rbp)
 	movq	$0, -128(%rbp)
 	subq	$8, %rsp
@@ -1176,72 +1169,70 @@
 	pushq	%rcx
 	pushq	%rbx
 	pushq	%rax
 	pushq	%rcx
 	pushq	%r12
 	pushq	%rcx
 	pushq	%r15
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
-	jle	0x3dfa
+	jle	0x3619
 	movq	%rax, %rcx
 	negq	%rcx
 	xorl	%edx, %edx
 	xorl	%r8d, %r8d
-	jmp	0x3dbd
+	jmp	0x35db
 	nopw	%cs:(%rax,%rax)
-	nop
-	addq	$1, %r8
-	addq	$-1, %rdx
+	incq	%r8
+	decq	%rdx
 	cmpq	%rax, %r8
-	je	0x3dfa
+	je	0x3619
 	movl	%r8d, %edi
 	xorl	%esi, %esi
-	jmp	0x3de0
+	jmp	0x35ff
 	nopw	%cs:(%rax,%rax)
-	nop
 	movsd	%xmm0, (%rbx,%rdi,8)
-	addq	$-1, %rsi
+	decq	%rsi
 	addl	%eax, %edi
 	cmpq	%rsi, %rcx
-	je	0x3db0
+	je	0x35d0
 	movslq	%edi, %rdi
 	xorpd	%xmm0, %xmm0
 	cmpq	%rsi, %rdx
-	je	0x3dd0
+	je	0x35f0
 	movsd	(%rbx,%rdi,8), %xmm0
 	divsd	(%r13,%rdi,8), %xmm0
-	jmp	0x3dd0
+	jmp	0x35f0
 	leaq	-84(%rbp), %rdi
 	leaq	-56(%rbp), %rdx
 	movq	%rbx, %rsi
-	callq	0x13538 ## symbol stub for: _idamax
-	addl	$-1, %eax
+	callq	0x133b2 ## symbol stub for: _idamax
+	decl	%eax
 	cltq
 	movsd	(%rbx,%rax,8), %xmm0
-	andps	63621(%rip), %xmm0
+	andps	65223(%rip), %xmm0
 	movaps	%xmm0, -112(%rbp)
 	movq	-96(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movaps	-112(%rbp), %xmm0
 	addq	$88, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopl	(%rax,%rax)
+	nopl	(%rax)
 _QlambdaStart:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -1254,98 +1245,98 @@
 	movq	%rsi, %r12
 	movq	%rdi, -120(%rbp)
 	movl	%ecx, -44(%rbp)
 	movl	%r8d, -52(%rbp)
 	movslq	%ecx, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movl	$1, -64(%rbp)
 	movl	$1, -60(%rbp)
 	movl	%r14d, -68(%rbp)
 	testl	%r14d, %r14d
 	movq	%rax, -128(%rbp)
-	jle	0x3f23
+	jle	0x3742
 	xorl	%r13d, %r13d
 	movq	%r12, -96(%rbp)
 	movq	%r12, %r15
 	movq	-120(%rbp), %r12
 	nopl	(%rax)
 	leaq	-52(%rbp), %rbx
 	movq	%rbx, %rdi
 	movq	%r15, %rsi
 	leaq	-68(%rbp), %r14
 	movq	%r14, %rdx
 	movq	%r15, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -80(%rbp)
 	movq	%rbx, %rdi
 	movq	%r15, %rsi
 	movq	%r14, %rdx
 	movq	%r12, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movq	-128(%rbp), %rax
 	divsd	-80(%rbp), %xmm0
 	movsd	%xmm0, (%rax,%r13,8)
-	addq	$1, %r13
+	incq	%r13
 	movslq	-44(%rbp), %rbx
 	addq	$8, %r12
 	addq	$8, %r15
 	cmpq	%rbx, %r13
-	jl	0x3ec0
+	jl	0x36e0
 	movl	-52(%rbp), %r15d
 	movq	-96(%rbp), %r12
 	movl	%r15d, -96(%rbp)
 	imull	%r15d, %ebx
 	movl	%ebx, -56(%rbp)
 	movslq	%ebx, %rdi
 	movl	$8, %esi
 	movq	%rax, %r14
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	-56(%rbp), %rdi
 	leaq	-64(%rbp), %rdx
 	leaq	-60(%rbp), %r8
 	movq	%r12, %rsi
 	movq	%rax, -80(%rbp)
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$0, -44(%rbp)
-	jle	0x3fa6
+	jle	0x37c5
 	xorl	%r13d, %r13d
 	leaq	-88(%rbp), %r15
 	leaq	-44(%rbp), %rbx
 	movq	-80(%rbp), %r12
-	nop
+	nopl	(%rax)
 	movsd	(%r14,%r13,8), %xmm0
-	xorpd	63250(%rip), %xmm0
+	xorpd	64850(%rip), %xmm0
 	movlpd	%xmm0, -88(%rbp)
 	leaq	-52(%rbp), %rdi
 	movq	%r15, %rsi
 	movq	%r12, %rdx
 	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	addq	$1, %r13
+	callq	0x133a0 ## symbol stub for: _dscal
+	incq	%r13
 	movslq	-44(%rbp), %rax
 	addq	$8, %r12
 	cmpq	%rax, %r13
-	jl	0x3f70
+	jl	0x3790
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -88(%rbp)
 	leaq	-56(%rbp), %rdi
 	leaq	-88(%rbp), %r15
 	leaq	-64(%rbp), %rcx
 	leaq	-60(%rbp), %r9
 	movq	%r15, %rsi
 	movq	-120(%rbp), %rbx
 	movq	%rbx, %rdx
 	movq	-80(%rbp), %r12
 	movq	%r12, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movb	$78, -46(%rbp)
 	movb	$84, -45(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -88(%rbp)
 	movq	$0, -152(%rbp)
 	movl	-44(%rbp), %eax
 	movl	%eax, -104(%rbp)
@@ -1366,57 +1357,57 @@
 	movq	-144(%rbp), %r15
 	pushq	%r15
 	pushq	%r10
 	pushq	%r11
 	pushq	%rbx
 	pushq	%r14
 	pushq	%r12
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	-44(%rbp), %r8d
 	testl	%r8d, %r8d
-	jle	0x40df
+	jle	0x38ff
 	xorps	%xmm0, %xmm0
 	cvtsi2sdl	-96(%rbp), %xmm0
 	mulsd	-136(%rbp), %xmm0
 	xorl	%ecx, %ecx
 	cmpl	$1, %r8d
-	je	0x40c3
+	je	0x38e3
 	movl	%r8d, %edx
 	andl	$-2, %edx
 	leal	1(%r8), %esi
 	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
-	nopl	(%rax,%rax)
+	nopw	(%rax,%rax)
 	movslq	%ebx, %rbx
 	movsd	(%r15,%rbx,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r15,%rbx,8)
 	leal	(%rsi,%rbx), %eax
 	cltq
 	movsd	(%r15,%rax,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r15,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
 	cmpq	%rcx, %rdx
-	jne	0x4090
+	jne	0x38b0
 	testb	$1, %r8b
-	je	0x40df
+	je	0x38ff
 	imull	%ecx, %r8d
 	addl	%ecx, %r8d
 	movslq	%r8d, %rax
 	addsd	(%r15,%rax,8), %xmm0
 	movsd	%xmm0, (%r15,%rax,8)
 	movq	-128(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$120, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
@@ -1445,67 +1436,67 @@
 	movl	%eax, -72(%rbp)
 	movl	%ecx, -108(%rbp)
 	imull	%r14d, %ecx
 	movl	%ecx, -88(%rbp)
 	movslq	%eax, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -144(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -128(%rbp)
 	movl	$1, -48(%rbp)
 	movl	$1, -60(%rbp)
 	leaq	-72(%rbp), %r12
 	leaq	-48(%rbp), %rdx
 	leaq	-60(%rbp), %r8
 	movq	%r12, %rdi
 	movq	-96(%rbp), %rsi
 	movq	%r15, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, -152(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -56(%rbp)
 	leaq	-56(%rbp), %rbx
 	movq	%r12, %rdi
 	movq	%rbx, %rsi
 	movq	%r15, %rdx
 	leaq	-48(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, -56(%rbp)
 	movl	$0, -116(%rbp)
 	leaq	-116(%rbp), %rdx
 	movq	%r12, %rdi
 	movq	%rbx, %rsi
 	movq	-144(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r15, %rsi
 	movabsq	$4607182418800017408, %r12
 	testl	%r14d, %r14d
-	jle	0x42c1
+	jle	0x3ae1
 	movq	%rbx, %r10
 	movl	%r14d, %r8d
 	xorl	%ecx, %ecx
 	cmpl	$1, %r14d
-	je	0x4298
+	je	0x3ab8
 	movl	%r8d, %r11d
 	andl	$-2, %r11d
 	leal	1(%r14), %r9d
 	leal	(%r14,%r14), %edi
 	addl	$2, %edi
 	xorl	%eax, %eax
-	movsd	62429(%rip), %xmm0
+	movsd	64045(%rip), %xmm0
 	xorl	%ecx, %ecx
 	movq	%r10, %rdx
 	nopl	(%rax,%rax)
 	cltq
 	movsd	(%rsi,%rax,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%rsi,%rax,8)
@@ -1515,37 +1506,37 @@
 	movsd	(%rsi,%rbx,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%rsi,%rbx,8)
 	movq	%r12, (%rdx,%rbx,8)
 	addq	$2, %rcx
 	addl	%edi, %eax
 	cmpq	%rcx, %r11
-	jne	0x4260
+	jne	0x3a80
 	testb	$1, %r8b
 	movq	%r10, %rbx
-	je	0x42c1
+	je	0x3ae1
 	movl	%ecx, %eax
 	imull	%r14d, %eax
 	addl	%ecx, %eax
 	cltq
 	movsd	(%rsi,%rax,8), %xmm0
-	addsd	62328(%rip), %xmm0
+	addsd	63944(%rip), %xmm0
 	movsd	%xmm0, (%rsi,%rax,8)
 	movq	%r12, (%rbx,%rax,8)
 	leaq	-72(%rbp), %rdi
 	leaq	-48(%rbp), %rdx
 	leaq	-60(%rbp), %r8
 	movq	-128(%rbp), %r15
 	movq	%r15, %rcx
 	movq	%rsi, -96(%rbp)
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	$0, -112(%rbp)
 	movslq	%r14d, %rdi
 	movl	$4, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r8
 	movl	%r14d, -68(%rbp)
 	movl	%r14d, -80(%rbp)
 	movl	%r14d, -76(%rbp)
 	movl	%r14d, -64(%rbp)
 	leaq	-112(%rbp), %r10
 	leaq	-80(%rbp), %rax
@@ -1555,19 +1546,19 @@
 	movq	%r15, %rdx
 	movq	%r14, %rcx
 	movq	%r8, -160(%rbp)
 	movq	%rbx, %r9
 	pushq	%r10
 	pushq	%rax
 	movq	%rax, %r15
-	callq	0x1351a ## symbol stub for: _dgesv
+	callq	0x13394 ## symbol stub for: _dgesv
 	addq	$16, %rsp
 	movslq	-88(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movb	$78, -42(%rbp)
 	movb	$78, -41(%rbp)
 	movq	%r12, -56(%rbp)
 	subq	$8, %rsp
 	leaq	-76(%rbp), %rbx
 	leaq	-152(%rbp), %r10
 	leaq	-42(%rbp), %rdi
@@ -1580,71 +1571,71 @@
 	movq	%rax, -88(%rbp)
 	pushq	%rax
 	pushq	%r10
 	pushq	%r15
 	pushq	-136(%rbp)
 	pushq	%r14
 	pushq	-96(%rbp)
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	cmpl	$0, 16(%rbp)
 	movq	-168(%rbp), %r14
-	jle	0x43f2
+	jle	0x3c11
 	xorl	%r12d, %r12d
 	leaq	16(%rbp), %rbx
 	movq	-88(%rbp), %r15
 	nop
 	movsd	(%r14,%r12,8), %xmm0
-	xorpd	62162(%rip), %xmm0
+	xorpd	63762(%rip), %xmm0
 	movlpd	%xmm0, -56(%rbp)
 	leaq	24(%rbp), %rdi
 	leaq	-56(%rbp), %rsi
 	movq	%r13, %rdx
 	leaq	-68(%rbp), %rcx
 	movq	%r15, %r8
 	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	addq	$1, %r12
+	callq	0x13376 ## symbol stub for: _daxpy
+	incq	%r12
 	movslq	16(%rbp), %rax
 	addq	$8, %r15
 	addq	$8, %r13
 	cmpq	%rax, %r12
-	jl	0x43b0
+	jl	0x3bd0
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -56(%rbp)
 	cmpl	$0, 24(%rbp)
 	movq	-176(%rbp), %r14
 	movq	-88(%rbp), %r15
-	jle	0x446a
+	jle	0x3c89
 	leaq	16(%rbp), %rdi
 	leaq	-56(%rbp), %rsi
 	leaq	-48(%rbp), %rcx
 	leaq	-60(%rbp), %r9
 	movq	%r14, %rdx
 	movq	%r15, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	cmpl	$2, 24(%rbp)
-	jl	0x446a
+	jl	0x3c89
 	movl	$1, %ebx
 	leaq	-48(%rbp), %r12
 	leaq	-60(%rbp), %r13
 	nop
 	movl	16(%rbp), %eax
 	imull	%ebx, %eax
 	cltq
 	leaq	(%r15,%rax,8), %r8
 	leaq	16(%rbp), %rdi
 	leaq	-56(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r12, %rcx
 	movq	%r13, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	addl	$1, %ebx
+	callq	0x13376 ## symbol stub for: _daxpy
+	incl	%ebx
 	cmpl	24(%rbp), %ebx
-	jl	0x4440
+	jl	0x3c60
 	xorps	%xmm0, %xmm0
 	cvtsi2sdl	-108(%rbp), %xmm0
 	mulsd	-104(%rbp), %xmm0
 	movsd	%xmm0, -104(%rbp)
 	movb	$84, -41(%rbp)
 	subq	$8, %rsp
 	leaq	-42(%rbp), %rdi
@@ -1662,45 +1653,45 @@
 	pushq	%rax
 	leaq	-80(%rbp), %rax
 	pushq	%rax
 	pushq	-136(%rbp)
 	leaq	-68(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movsd	-104(%rbp), %xmm0
 	movsd	%xmm0, -56(%rbp)
 	leaq	-72(%rbp), %rdi
 	leaq	-48(%rbp), %rcx
 	leaq	-60(%rbp), %r9
 	movq	%r14, %rsi
 	movq	-144(%rbp), %rbx
 	movq	%rbx, %rdx
 	movq	%r12, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	-96(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-128(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-160(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$152, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopl	(%rax,%rax)
+	nopw	(%rax,%rax)
 _QlambdaMiddleCenter:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -1719,77 +1710,77 @@
 	imull	%r9d, %eax
 	movl	%eax, -84(%rbp)
 	movl	%ecx, -108(%rbp)
 	imull	%r9d, %ecx
 	movl	%ecx, -96(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movl	$1, -80(%rbp)
 	movl	$1, -76(%rbp)
 	leaq	-84(%rbp), %r12
 	leaq	-80(%rbp), %rdx
 	leaq	-76(%rbp), %r8
 	movq	%r12, %rdi
 	movq	%r15, %rsi
 	movq	%rdx, %r15
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, -128(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -56(%rbp)
 	leaq	-56(%rbp), %rsi
 	movq	%r12, %rdi
 	movq	%r13, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	testl	%r14d, %r14d
-	jle	0x467e
+	jle	0x3e9e
 	movl	%r14d, %r8d
 	xorl	%ecx, %ecx
 	cmpl	$1, %r14d
-	je	0x4658
+	je	0x3e78
 	movl	%r8d, %edx
 	andl	$-2, %edx
 	leal	1(%r14), %r9d
 	leal	(%r14,%r14), %edi
 	addl	$2, %edi
 	xorl	%eax, %eax
-	movsd	61458(%rip), %xmm0
+	movsd	63074(%rip), %xmm0
 	xorl	%ecx, %ecx
 	cltq
 	movsd	(%r13,%rax,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r13,%rax,8)
 	leal	(%r9,%rax), %esi
 	movslq	%esi, %rsi
 	movsd	(%r13,%rsi,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r13,%rsi,8)
 	addq	$2, %rcx
 	addl	%edi, %eax
 	cmpq	%rcx, %rdx
-	jne	0x4620
+	jne	0x3e40
 	testb	$1, %r8b
-	je	0x467e
+	je	0x3e9e
 	movl	%ecx, %eax
 	imull	%r14d, %eax
 	addl	%ecx, %eax
 	cltq
 	movsd	(%r13,%rax,8), %xmm0
-	addsd	61369(%rip), %xmm0
+	addsd	62985(%rip), %xmm0
 	movsd	%xmm0, (%r13,%rax,8)
 	movl	%r14d, -60(%rbp)
 	movl	%r14d, -72(%rbp)
 	movl	%r14d, -68(%rbp)
 	movl	%r14d, -64(%rbp)
 	movslq	-96(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movb	$78, -42(%rbp)
 	movb	$78, -41(%rbp)
 	movabsq	$4607182418800017408, %rcx
 	movq	%rcx, -56(%rbp)
 	subq	$8, %rsp
 	leaq	-68(%rbp), %r15
 	leaq	-128(%rbp), %r11
@@ -1805,38 +1796,38 @@
 	movq	%rax, -96(%rbp)
 	pushq	%rax
 	pushq	%r11
 	pushq	%r14
 	pushq	-120(%rbp)
 	pushq	%r10
 	pushq	%r13
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	cmpl	$0, -48(%rbp)
 	movq	-136(%rbp), %r15
-	jle	0x4753
+	jle	0x3f72
 	xorl	%r12d, %r12d
 	movq	-96(%rbp), %r14
 	nopl	(%rax)
 	movsd	(%r15,%r12,8), %xmm0
-	xorpd	61298(%rip), %xmm0
+	xorpd	62898(%rip), %xmm0
 	movlpd	%xmm0, -56(%rbp)
 	leaq	16(%rbp), %rdi
 	leaq	-56(%rbp), %rsi
 	movq	%rbx, %rdx
 	leaq	-60(%rbp), %rcx
 	movq	%r14, %r8
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	addq	$1, %r12
+	callq	0x13376 ## symbol stub for: _daxpy
+	incq	%r12
 	movslq	-48(%rbp), %rax
 	addq	$8, %r14
 	addq	$8, %rbx
 	cmpq	%rax, %r12
-	jl	0x4710
+	jl	0x3f30
 	xorps	%xmm0, %xmm0
 	cvtsi2sdl	-108(%rbp), %xmm0
 	mulsd	-104(%rbp), %xmm0
 	movsd	%xmm0, -104(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -56(%rbp)
 	movb	$84, -41(%rbp)
@@ -1857,38 +1848,38 @@
 	leaq	-72(%rbp), %rax
 	pushq	%rax
 	pushq	-120(%rbp)
 	leaq	-60(%rbp), %rax
 	pushq	%rax
 	movq	-96(%rbp), %r15
 	pushq	%r15
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movsd	-104(%rbp), %xmm0
 	movsd	%xmm0, -56(%rbp)
 	leaq	-84(%rbp), %rdi
 	leaq	-80(%rbp), %rcx
 	leaq	-76(%rbp), %r9
 	movq	%r14, %rsi
 	movq	24(%rbp), %rdx
 	movq	%rbx, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$104, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopl	(%rax,%rax)
+	nopw	(%rax,%rax)
 _UpdateIBinvPermute:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -1903,59 +1894,59 @@
 	movl	%eax, -76(%rbp)
 	movl	%edx, -72(%rbp)
 	movl	%edx, -68(%rbp)
 	movl	%edx, -64(%rbp)
 	movslq	%eax, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
 	movl	$1, -44(%rbp)
 	movl	$1, -52(%rbp)
 	movl	$0, -60(%rbp)
 	leaq	-76(%rbp), %rbx
 	leaq	-44(%rbp), %rdx
 	leaq	-52(%rbp), %r8
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	%r13, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -88(%rbp)
 	leaq	-88(%rbp), %r14
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	%r13, %rdx
 	leaq	-44(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, -88(%rbp)
 	leaq	-60(%rbp), %rdx
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	%r15, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r12d, %r12d
-	jle	0x4979
+	jle	0x4199
 	movl	%r12d, %r8d
 	xorl	%edx, %edx
 	movabsq	$4607182418800017408, %r9
 	cmpl	$1, %r12d
-	je	0x494f
+	je	0x416f
 	movl	%r8d, %esi
 	andl	$-2, %esi
 	leal	1(%r12), %edi
 	leal	(%r12,%r12), %ebx
 	addl	$2, %ebx
 	xorl	%ecx, %ecx
-	movsd	60707(%rip), %xmm0
+	movsd	62323(%rip), %xmm0
 	xorl	%edx, %edx
 	nop
 	movslq	%ecx, %rcx
 	movsd	(%r13,%rcx,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r13,%rcx,8)
 	movq	%r9, (%r15,%rcx,8)
@@ -1964,81 +1955,80 @@
 	movsd	(%r13,%rax,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%r13,%rax,8)
 	movq	%r9, (%r15,%rax,8)
 	addq	$2, %rdx
 	addl	%ebx, %ecx
 	cmpq	%rdx, %rsi
-	jne	0x4910
+	jne	0x4130
 	testb	$1, %r8b
-	je	0x4979
+	je	0x4199
 	movl	%edx, %eax
 	imull	%r12d, %eax
 	addl	%edx, %eax
 	cltq
 	movsd	(%r13,%rax,8), %xmm0
-	addsd	60610(%rip), %xmm0
+	addsd	62226(%rip), %xmm0
 	movsd	%xmm0, (%r13,%rax,8)
 	movq	%r9, (%r15,%rax,8)
 	movl	$0, -56(%rbp)
 	movslq	%r12d, %rdi
 	movl	$4, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	leaq	-56(%rbp), %rax
 	leaq	-68(%rbp), %r10
 	leaq	-48(%rbp), %rdi
 	leaq	-64(%rbp), %rsi
 	leaq	-72(%rbp), %rcx
 	movq	%r13, %rdx
 	movq	%rbx, %r8
 	movq	%r15, %r9
 	pushq	%rax
 	pushq	%r10
-	callq	0x1351a ## symbol stub for: _dgesv
+	callq	0x13394 ## symbol stub for: _dgesv
 	addq	$16, %rsp
 	movl	-48(%rbp), %eax
 	testl	%eax, %eax
 	movq	-96(%rbp), %r12
-	jle	0x4a0c
+	jle	0x422a
 	xorl	%r14d, %r14d
 	nopw	(%rax,%rax)
 	movl	(%rbx,%r14,4), %ecx
-	addl	$-1, %ecx
+	decl	%ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%r12,%rcx,8), %rcx
 	movl	%r14d, %edx
 	imull	%eax, %edx
 	movslq	%edx, %rax
 	leaq	(%r15,%rax,8), %rsi
 	leaq	-48(%rbp), %rdi
 	leaq	-44(%rbp), %rdx
 	leaq	-52(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	addq	$1, %r14
+	callq	0x1337c ## symbol stub for: _dcopy
+	incq	%r14
 	movslq	-48(%rbp), %rax
 	cmpq	%rax, %r14
-	jl	0x49d0
+	jl	0x41f0
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$56, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 _UpdateIBinv:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -2052,55 +2042,55 @@
 	imull	%edx, %eax
 	movl	%eax, -72(%rbp)
 	movl	%edx, -68(%rbp)
 	movl	%edx, -64(%rbp)
 	movl	%edx, -60(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	movl	$1, -44(%rbp)
 	movl	$1, -56(%rbp)
 	movl	$0, -52(%rbp)
 	leaq	-72(%rbp), %r13
 	leaq	-44(%rbp), %rdx
 	leaq	-56(%rbp), %r8
 	movq	%r13, %rdi
 	movq	%r12, %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -88(%rbp)
 	leaq	-88(%rbp), %r12
 	movq	%r13, %rdi
 	movq	%r12, %rsi
 	movq	%rbx, %rdx
 	leaq	-44(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, -88(%rbp)
 	leaq	-52(%rbp), %rdx
 	movq	%r13, %rdi
 	movq	%r12, %rsi
 	movq	%r14, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r15d, %r15d
-	jle	0x4b8e
+	jle	0x43ae
 	movl	%r15d, %r8d
 	xorl	%edx, %edx
 	movabsq	$4607182418800017408, %r9
 	cmpl	$1, %r15d
-	je	0x4b68
+	je	0x4388
 	movl	%r8d, %esi
 	andl	$-2, %esi
 	leal	1(%r15), %r10d
 	leal	(%r15,%r15), %ecx
 	addl	$2, %ecx
 	xorl	%eax, %eax
-	movsd	60168(%rip), %xmm0
+	movsd	61784(%rip), %xmm0
 	xorl	%edx, %edx
 	nopw	(%rax,%rax)
 	cltq
 	movsd	(%rbx,%rax,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%rbx,%rax,8)
 	movq	%r9, (%r14,%rax,8)
@@ -2109,46 +2099,46 @@
 	movsd	(%rbx,%rdi,8), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, (%rbx,%rdi,8)
 	movq	%r9, (%r14,%rdi,8)
 	addq	$2, %rdx
 	addl	%ecx, %eax
 	cmpq	%rdx, %rsi
-	jne	0x4b30
+	jne	0x4350
 	testb	$1, %r8b
-	je	0x4b8e
+	je	0x43ae
 	movl	%edx, %eax
 	imull	%r15d, %eax
 	addl	%edx, %eax
 	cltq
 	movsd	(%rbx,%rax,8), %xmm0
-	addsd	60075(%rip), %xmm0
+	addsd	61691(%rip), %xmm0
 	movsd	%xmm0, (%rbx,%rax,8)
 	movq	%r9, (%r14,%rax,8)
 	movl	$0, -48(%rbp)
 	movslq	%r15d, %rdi
 	movl	$4, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
 	leaq	-48(%rbp), %rax
 	leaq	-64(%rbp), %r10
 	leaq	-76(%rbp), %rdi
 	leaq	-60(%rbp), %rsi
 	leaq	-68(%rbp), %rcx
 	movq	%rbx, %rdx
 	movq	%r15, %r8
 	movq	%r14, %r9
 	pushq	%rax
 	pushq	%r10
-	callq	0x1351a ## symbol stub for: _dgesv
+	callq	0x13394 ## symbol stub for: _dgesv
 	addq	$16, %rsp
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$56, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
@@ -2159,1912 +2149,1935 @@
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
 	subq	$504, %rsp
-	movsd	%xmm3, -160(%rbp)
+	movsd	%xmm3, -64(%rbp)
 	movsd	%xmm2, -504(%rbp)
-	movsd	%xmm1, -88(%rbp)
+	movsd	%xmm1, -96(%rbp)
 	movsd	%xmm0, -128(%rbp)
 	movq	%r9, %rbx
 	movq	%r8, -136(%rbp)
-	movq	%rcx, -104(%rbp)
-	movq	%rdx, -176(%rbp)
+	movq	%rcx, -240(%rbp)
+	movq	%rdx, -160(%rbp)
 	movq	%rsi, -72(%rbp)
-	movq	%rdi, -432(%rbp)
-	movslq	24(%rbp), %r14
+	movq	%rdi, -416(%rbp)
 	movl	32(%rbp), %r15d
-	movl	%r15d, -96(%rbp)
-	movl	%r14d, -60(%rbp)
+	movl	%r15d, -112(%rbp)
+	movl	24(%rbp), %eax
+	movl	%eax, -76(%rbp)
+	movslq	%eax, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -384(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -368(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -376(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -360(%rbp)
 	movl	%r15d, %eax
 	imull	%r14d, %eax
-	movl	%eax, -336(%rbp)
-	imull	%r14d, %r14d
-	movl	%r14d, -56(%rbp)
+	movl	%eax, -188(%rbp)
+	movl	%r14d, %r15d
+	imull	%r14d, %r15d
+	movl	%r15d, -56(%rbp)
 	movslq	%eax, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r15
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r12
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
-	movl	$0, -200(%rbp)
-	leaq	-336(%rbp), %r12
+	movl	$0, -184(%rbp)
+	leaq	-188(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	movq	%r12, %rdi
-	movq	-104(%rbp), %rsi
+	movq	-240(%rbp), %rsi
 	movq	%r13, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r12, %rdi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-188(%rbp), %rdi
 	movq	-136(%rbp), %rsi
 	leaq	-52(%rbp), %rdx
-	movq	%r15, %rcx
+	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	24(%rbp), %r8d
-	movq	%r13, -168(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	%r13, -144(%rbp)
 	movq	%r13, %rdi
-	movq	%r15, -264(%rbp)
-	movq	%r15, %rsi
-	movq	-384(%rbp), %rdx
-	movq	-376(%rbp), %rcx
-	movl	-96(%rbp), %r9d
+	movq	%r12, -264(%rbp)
+	movq	%r12, %rsi
+	movq	-368(%rbp), %rdx
+	movq	-360(%rbp), %rcx
+	movl	%r14d, %r8d
+	movl	-112(%rbp), %r9d
 	callq	_centerYX
 	cmpl	$5, 40(%rbp)
-	jl	0x4d4d
-	leaq	60332(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
-	movsd	-160(%rbp), %xmm0
+	jl	0x4575
+	leaq	61973(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
+	movsd	-64(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movl	-56(%rbp), %r14d
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-56(%rbp), %r15d
+	movslq	24(%rbp), %r14
 	movq	$0, -328(%rbp)
-	movslq	%r14d, %r14
+	movslq	%r15d, %r15
 	movl	$8, %esi
-	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -136(%rbp)
-	movslq	24(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%r14, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -288(%rbp)
 	movl	$8, %esi
-	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r12
 	leaq	-56(%rbp), %r15
 	leaq	-52(%rbp), %r14
 	leaq	-48(%rbp), %r8
 	movq	%r15, %rdi
-	movq	-432(%rbp), %rsi
+	movq	-416(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movsd	-128(%rbp), %xmm0
 	addsd	%xmm0, %xmm0
-	subsd	-88(%rbp), %xmm0
-	mulsd	-160(%rbp), %xmm0
-	movsd	%xmm0, -536(%rbp)
-	leaq	-536(%rbp), %rsi
+	subsd	-96(%rbp), %xmm0
+	mulsd	-64(%rbp), %xmm0
+	movsd	%xmm0, -544(%rbp)
+	leaq	-544(%rbp), %rsi
 	movq	%r15, %rdi
-	movq	%r12, -400(%rbp)
+	movq	%r12, -384(%rbp)
 	movq	%r12, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	$0, -464(%rbp)
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	$0, -440(%rbp)
 	movslq	24(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	24(%rbp), %rdi
-	leaq	-464(%rbp), %rsi
-	leaq	-200(%rbp), %rdx
-	movq	%rax, -232(%rbp)
+	leaq	-440(%rbp), %rsi
+	leaq	-184(%rbp), %rdx
+	movq	%rax, -224(%rbp)
 	movq	%rax, %rcx
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %r12d
 	testl	%r12d, %r12d
-	jle	0x4ef9
+	jle	0x4718
 	xorl	%r15d, %r15d
-	movapd	59484(%rip), %xmm1
-	leaq	-60(%rbp), %r13
-	jmp	0x4e8f
-	nopw	(%rax,%rax)
+	movapd	61080(%rip), %xmm1
+	leaq	-76(%rbp), %r13
+	jmp	0x46ae
+	nop
 	subl	%r12d, %eax
-	movl	%eax, -64(%rbp)
+	movl	%eax, -80(%rbp)
 	movq	-136(%rbp), %rax
 	leaq	(%rax,%r15,8), %rsi
 	leaq	24(%rbp), %rdi
 	movq	%r13, %rdx
-	callq	0x134f6 ## symbol stub for: _dasum
-	movapd	59435(%rip), %xmm1
+	callq	0x13370 ## symbol stub for: _dasum
+	movapd	61035(%rip), %xmm1
 	movq	-288(%rbp), %rax
 	movsd	%xmm0, (%rax,%r15,8)
-	addq	$1, %r15
+	incq	%r15
 	movslq	24(%rbp), %r12
 	cmpq	%r12, %r15
-	jge	0x4ef9
+	jge	0x4718
 	testl	%r12d, %r12d
-	movq	-400(%rbp), %rdi
-	jle	0x4e56
+	movq	-384(%rbp), %rdi
+	jle	0x4676
 	movl	%r12d, %ecx
 	movl	%r15d, %eax
 	xorl	%edx, %edx
-	movsd	59269(%rip), %xmm2
-	jmp	0x4edc
+	movsd	60886(%rip), %xmm2
+	jmp	0x46fb
 	nopl	(%rax)
 	movq	-72(%rbp), %rsi
 	movq	$0, (%rsi,%rax,8)
 	xorpd	%xmm0, %xmm0
 	movq	-136(%rbp), %rsi
 	movsd	%xmm0, (%rsi,%rax,8)
-	addq	$1, %rdx
+	incq	%rdx
 	addl	%r12d, %eax
 	cmpq	%rdx, %rcx
-	je	0x4e50
+	je	0x4670
 	cltq
 	movsd	(%rbx,%rax,8), %xmm0
 	andpd	%xmm1, %xmm0
 	ucomisd	(%rdi,%rax,8), %xmm0
-	jb	0x4eb0
+	jb	0x46d0
 	movapd	%xmm2, %xmm0
 	cmpq	%rdx, %r15
-	jne	0x4ec0
-	jmp	0x4eb0
+	jne	0x46e0
+	jmp	0x46d0
 	movslq	%r12d, %rbx
 	movb	$78, -41(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -280(%rbp)
 	movslq	-56(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movslq	32(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rbx, %rcx
 	movq	%rax, -312(%rbp)
 	testl	%ecx, %ecx
 	movq	%r13, -272(%rbp)
-	jle	0x5037
+	jle	0x4856
 	xorl	%ebx, %ebx
 	movq	-264(%rbp), %r13
-	movq	-168(%rbp), %r15
+	movq	-144(%rbp), %r15
 	leaq	24(%rbp), %r14
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	leaq	32(%rbp), %r12
 	movq	%r12, %rdi
 	movq	%r13, %rsi
 	movq	%r14, %rdx
 	movq	%r15, %rcx
 	movq	%r14, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	%xmm0, -88(%rbp)
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	%xmm0, -96(%rbp)
 	movq	%r12, %rdi
 	movq	%r13, %rsi
 	movq	%r14, %rdx
 	movq	%r13, %rcx
 	movq	%r14, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	-88(%rbp), %xmm1
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	-96(%rbp), %xmm1
 	divsd	%xmm0, %xmm1
 	movq	-280(%rbp), %rax
 	movsd	%xmm1, (%rax,%rbx,8)
 	movl	24(%rbp), %eax
 	imull	%ebx, %eax
 	cltq
 	movq	-272(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r10
-	movsd	58975(%rip), %xmm1
+	movsd	60591(%rip), %xmm1
 	divsd	%xmm0, %xmm1
-	movsd	%xmm1, -80(%rbp)
+	movsd	%xmm1, -88(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	movq	%r14, %rsi
 	movq	%r12, %rdx
-	leaq	-80(%rbp), %rcx
-	movq	-168(%rbp), %r8
-	leaq	-60(%rbp), %r9
+	leaq	-88(%rbp), %rcx
+	movq	-144(%rbp), %r8
+	leaq	-76(%rbp), %r9
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%r10
 	leaq	-328(%rbp), %rax
 	pushq	%rax
 	pushq	%r14
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	addq	$1, %rbx
+	incq	%rbx
 	movl	24(%rbp), %r12d
 	movslq	%r12d, %rcx
 	addq	$8, %r15
 	addq	$8, %r13
 	cmpq	%rcx, %rbx
-	jl	0x4f70
+	jl	0x4790
 	movslq	32(%rbp), %r15
 	leaq	-52(%rbp), %r14
 	movsd	-128(%rbp), %xmm0
-	mulsd	-160(%rbp), %xmm0
+	mulsd	-64(%rbp), %xmm0
 	movsd	%xmm0, -128(%rbp)
 	movl	$8, %esi
 	movq	%rcx, %rbx
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -424(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -408(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -304(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -296(%rbp)
 	leal	1(%r12), %eax
 	imull	%r12d, %eax
-	movl	%eax, -64(%rbp)
+	movl	%eax, -80(%rbp)
 	movslq	%eax, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -256(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -248(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -392(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -376(%rbp)
 	xorl	%eax, %eax
 	movl	16(%rbp), %ecx
 	testl	%ecx, %ecx
 	cmovlel	%eax, %ecx
-	movl	%ecx, -196(%rbp)
+	movl	%ecx, -180(%rbp)
 	xorl	%esi, %esi
 	leaq	-48(%rbp), %rbx
 	movq	-280(%rbp), %r12
-	jmp	0x511f
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
+	jmp	0x492e
+	nop
 	movl	-332(%rbp), %esi
-	addl	$1, %esi
-	movsd	58703(%rip), %xmm0
+	incl	%esi
+	movsd	60344(%rip), %xmm0
 	ucomisd	%xmm1, %xmm0
 	leaq	-52(%rbp), %r14
-	ja	0x5cdd
-	cmpl	-196(%rbp), %esi
-	je	0x5cd7
+	ja	0x5517
+	cmpl	-180(%rbp), %esi
+	je	0x5511
 	movl	%esi, -332(%rbp)
 	leaq	-56(%rbp), %rdi
 	movq	-72(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	-256(%rbp), %r15
 	movq	%r15, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-56(%rbp), %rax
 	leaq	(%r15,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	-176(%rbp), %rsi
+	movq	-160(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	xorpd	%xmm1, %xmm1
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
-	jle	0x5bc0
+	jle	0x5400
 	xorl	%r15d, %r15d
-	jmp	0x51cb
+	jmp	0x49da
+	nop
 	movq	-72(%rbp), %rax
 	leaq	(%rax,%r15,8), %rcx
 	leaq	24(%rbp), %rdi
-	leaq	-464(%rbp), %rsi
-	leaq	-200(%rbp), %rdx
-	leaq	-60(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	leaq	-440(%rbp), %rsi
+	leaq	-184(%rbp), %rdx
+	leaq	-76(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movsd	(%r12,%r15,8), %xmm0
-	movq	-176(%rbp), %rax
+	movq	-160(%rbp), %rax
 	movsd	%xmm0, (%rax,%r15,8)
-	addq	$1, %r15
+	incq	%r15
 	movslq	24(%rbp), %rax
 	cmpq	%rax, %r15
 	xorpd	%xmm1, %xmm1
-	jge	0x5bc0
+	jge	0x5400
 	movq	-288(%rbp), %rcx
 	movsd	(%rcx,%r15,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0x5180
+	jbe	0x4990
 	cmpl	$7, 40(%rbp)
-	jl	0x51fc
-	leaq	59197(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating gene %d \n"
+	jl	0x4a0b
+	leaq	60862(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating gene %d \n"
 	movl	%r15d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	xorpd	%xmm1, %xmm1
 	movl	24(%rbp), %eax
-	movq	-232(%rbp), %rcx
+	movq	-224(%rbp), %rcx
 	movabsq	$4607182418800017408, %rdx
 	movq	%rdx, (%rcx,%r15,8)
-	movq	-72(%rbp), %rcx
-	leaq	(%rcx,%r15,8), %rcx
-	movq	%rcx, -448(%rbp)
 	testl	%eax, %eax
-	jle	0x5b40
+	jle	0x5380
 	movl	%eax, %ecx
 	imull	%r15d, %ecx
 	movslq	%ecx, %rcx
 	movq	48(%rbp), %rdx
 	leaq	(%rdx,%rcx,8), %r12
+	movq	-72(%rbp), %rcx
+	leaq	(%rcx,%r15,8), %rcx
+	movq	%rcx, -520(%rbp)
 	movq	-264(%rbp), %rcx
 	leaq	(%rcx,%r15,8), %rcx
 	movq	%rcx, -512(%rbp)
 	movl	%r15d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%rdx,%rcx,8), %rcx
-	movq	%rcx, -520(%rbp)
-	movq	-168(%rbp), %rsi
+	movq	%rcx, -528(%rbp)
+	movq	-144(%rbp), %rsi
 	xorl	%ebx, %ebx
-	movq	%r12, -440(%rbp)
+	movq	%r12, -424(%rbp)
 	movq	%r15, -320(%rbp)
-	jmp	0x52ed
-	movapd	-160(%rbp), %xmm2
-	movsd	-192(%rbp), %xmm0
-	movq	-416(%rbp), %rcx
+	jmp	0x4afb
+	movsd	-176(%rbp), %xmm1
+	movapd	-240(%rbp), %xmm3
+	movq	-400(%rbp), %rcx
 	movq	-72(%rbp), %rax
-	movsd	%xmm4, (%rax,%rcx,8)
-	subsd	%xmm4, %xmm0
-	mulsd	%xmm0, %xmm2
-	movsd	58248(%rip), %xmm0
-	addsd	%xmm0, %xmm2
-	divsd	%xmm2, %xmm0
-	movsd	%xmm0, -528(%rbp)
+	movsd	%xmm5, (%rax,%rcx,8)
+	subsd	%xmm5, %xmm1
+	mulsd	%xmm3, %xmm1
+	movsd	59881(%rip), %xmm0
+	addsd	%xmm0, %xmm1
+	divsd	%xmm1, %xmm0
+	movsd	%xmm0, -536(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-528(%rbp), %rsi
+	leaq	-536(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	-88(%rbp), %rsi
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	-96(%rbp), %rsi
 	movl	24(%rbp), %eax
 	xorpd	%xmm1, %xmm1
-	addq	$1, %rbx
+	incq	%rbx
 	movslq	%eax, %rcx
 	addq	$8, %rsi
 	cmpq	%rcx, %rbx
-	jge	0x5b40
+	jge	0x5380
 	movl	%ebx, %ecx
 	imull	%eax, %ecx
 	addl	%r15d, %ecx
 	movslq	%ecx, %rcx
 	movq	-136(%rbp), %rdx
 	movsd	(%rdx,%rcx,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0x52d9
-	movq	-520(%rbp), %rax
-	movsd	(%rax,%rbx,8), %xmm2
+	jbe	0x4ae8
+	movq	-528(%rbp), %rax
+	movsd	(%rax,%rbx,8), %xmm3
 	movq	-72(%rbp), %rax
-	movsd	(%rax,%rcx,8), %xmm0
-	movapd	%xmm0, %xmm4
+	movsd	(%rax,%rcx,8), %xmm1
+	movapd	%xmm1, %xmm5
 	cmpq	%rbx, %r15
-	movq	%rsi, -88(%rbp)
-	je	0x5298
-	movsd	%xmm0, -192(%rbp)
+	movq	%rsi, -96(%rbp)
+	je	0x4aa7
+	movsd	%xmm1, -176(%rbp)
 	leaq	32(%rbp), %rdi
 	leaq	24(%rbp), %r13
 	movq	%r13, %rdx
 	movq	-312(%rbp), %rcx
 	movq	%r14, %r8
-	movapd	%xmm2, -160(%rbp)
-	callq	0x13502 ## symbol stub for: _dcopy
+	movapd	%xmm3, -240(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	imull	%ebx, %eax
 	addl	%r15d, %eax
 	cltq
-	movq	-432(%rbp), %rcx
+	movq	-416(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
 	mulsd	-128(%rbp), %xmm0
-	movsd	%xmm0, -104(%rbp)
+	movsd	%xmm0, -64(%rbp)
 	movq	%r13, %rdi
-	movq	-448(%rbp), %rsi
-	leaq	-60(%rbp), %rdx
+	movq	-520(%rbp), %rsi
+	leaq	-76(%rbp), %rdx
 	movq	-296(%rbp), %r12
 	movq	%r12, %rcx
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
-	movq	%rax, -80(%rbp)
+	movq	%rax, -88(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-80(%rbp), %rsi
+	leaq	-88(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	%rbx, -456(%rbp)
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	%rbx, -432(%rbp)
 	movq	$0, (%r12,%rbx,8)
 	leaq	24(%rbp), %rdi
-	movq	-232(%rbp), %rsi
+	movq	-224(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	-304(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r14, %r15
 	leaq	-48(%rbp), %r14
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
-	movq	%rax, -80(%rbp)
+	movq	%rax, -88(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-80(%rbp), %rsi
+	leaq	-88(%rbp), %rsi
 	movq	%r12, %rdx
 	leaq	24(%rbp), %r13
 	movq	%r15, %rcx
 	movq	%rbx, %r8
 	movq	%r14, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	leaq	32(%rbp), %rbx
 	movq	%rbx, %rdi
 	movq	-512(%rbp), %rsi
 	movq	%r13, %rdx
-	movq	-424(%rbp), %r14
+	movq	-408(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	-176(%rbp), %rax
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	-160(%rbp), %rax
 	movq	-320(%rbp), %rcx
 	movsd	(%rax,%rcx,8), %xmm0
-	xorpd	57909(%rip), %xmm0
-	movlpd	%xmm0, -80(%rbp)
+	xorpd	59527(%rip), %xmm0
+	movlpd	%xmm0, -88(%rbp)
 	movq	%rbx, %rdi
-	leaq	-80(%rbp), %r12
+	leaq	-88(%rbp), %r12
 	movq	%r12, %rsi
 	movq	%r14, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movb	$84, -41(%rbp)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -328(%rbp)
-	movq	%rax, -80(%rbp)
+	movq	%rax, -88(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
 	movq	%r12, %rcx
-	movq	-168(%rbp), %r8
-	leaq	-60(%rbp), %r9
+	movq	-144(%rbp), %r8
+	leaq	-76(%rbp), %r9
 	leaq	-48(%rbp), %r13
 	pushq	%r13
 	pushq	%r14
 	leaq	-328(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
 	pushq	-304(%rbp)
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	movq	%rbx, %rdi
 	movq	-312(%rbp), %r12
 	movq	%r12, %rsi
 	movq	%r15, %rdx
 	movq	%r12, %rcx
 	movq	%r13, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	%xmm0, -96(%rbp)
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	%xmm0, -112(%rbp)
 	movq	%rbx, %rdi
 	movq	%r12, %rsi
 	movq	%r15, %rdx
 	movq	%r14, %rcx
 	movq	%r13, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movapd	-160(%rbp), %xmm2
-	movapd	%xmm0, %xmm8
-	movapd	%xmm2, %xmm0
-	andpd	57736(%rip), %xmm0
-	movsd	57632(%rip), %xmm1
-	ucomisd	%xmm0, %xmm1
-	jbe	0x55a1
+	callq	0x13382 ## symbol stub for: _ddot
+	movapd	-240(%rbp), %xmm3
+	movapd	%xmm3, %xmm2
+	andpd	59359(%rip), %xmm2
+	movsd	59271(%rip), %xmm1
+	ucomisd	%xmm2, %xmm1
+	jbe	0x4da7
 	cmpl	$8, 40(%rbp)
 	movq	-320(%rbp), %r15
-	movq	-456(%rbp), %rbx
-	jl	0x5561
-	leaq	58368(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
+	movq	-432(%rbp), %rbx
+	jl	0x4d68
+	leaq	60039(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
 	movl	%r15d, %esi
 	movl	%ebx, %edx
 	xorl	%eax, %eax
-	movsd	%xmm8, -120(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-120(%rbp), %xmm8
-	movapd	-160(%rbp), %xmm2
-	movapd	%xmm8, %xmm4
-	movsd	-104(%rbp), %xmm1
-	subsd	%xmm1, %xmm4
-	movsd	-96(%rbp), %xmm3
-	divsd	%xmm3, %xmm4
-	xorpd	%xmm0, %xmm0
-	ucomisd	%xmm0, %xmm4
+	movsd	%xmm0, -104(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-104(%rbp), %xmm0
+	movapd	-240(%rbp), %xmm3
+	movapd	%xmm0, %xmm5
+	movsd	-64(%rbp), %xmm1
+	subsd	%xmm1, %xmm5
+	movsd	-112(%rbp), %xmm2
+	divsd	%xmm2, %xmm5
+	xorpd	%xmm4, %xmm4
+	ucomisd	%xmm4, %xmm5
 	leaq	-52(%rbp), %r14
-	movq	-440(%rbp), %r12
-	jbe	0x5831
+	movq	-424(%rbp), %r12
+	jbe	0x4fe8
 	movl	24(%rbp), %eax
 	imull	%ebx, %eax
 	addl	%r15d, %eax
 	cltq
-	jmp	0x5853
+	jmp	0x5009
 	cmpl	$8, 40(%rbp)
 	movq	-320(%rbp), %r15
-	movq	-456(%rbp), %rbx
-	movsd	%xmm8, -120(%rbp)
-	jl	0x55dc
-	leaq	58297(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
+	movq	-432(%rbp), %rbx
+	movsd	%xmm0, -104(%rbp)
+	jl	0x4de0
+	leaq	59972(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
 	movl	%r15d, %esi
 	movl	%ebx, %edx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-120(%rbp), %xmm8
-	movapd	-160(%rbp), %xmm2
-	movsd	57419(%rip), %xmm10
-	movapd	%xmm10, %xmm11
-	divsd	%xmm2, %xmm11
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-104(%rbp), %xmm0
+	movapd	-240(%rbp), %xmm3
+	movsd	59064(%rip), %xmm2
+	movapd	%xmm2, %xmm4
+	divsd	%xmm3, %xmm4
 	movl	24(%rbp), %eax
 	imull	%ebx, %eax
 	addl	%r15d, %eax
 	movslq	%eax, %rcx
 	movq	-72(%rbp), %rax
-	movq	%rcx, -416(%rbp)
-	addsd	(%rax,%rcx,8), %xmm11
-	movsd	-96(%rbp), %xmm4
-	movapd	%xmm4, %xmm9
-	mulsd	%xmm11, %xmm9
-	movapd	%xmm8, %xmm1
-	addsd	%xmm9, %xmm1
-	movsd	-104(%rbp), %xmm0
-	subsd	%xmm0, %xmm1
-	movapd	%xmm8, %xmm2
-	subsd	%xmm0, %xmm2
-	cvtsi2sdl	32(%rbp), %xmm3
-	mulsd	%xmm11, %xmm2
-	mulsd	-504(%rbp), %xmm3
-	movsd	%xmm3, -184(%rbp)
-	subsd	%xmm3, %xmm2
-	movapd	%xmm1, %xmm12
-	movapd	%xmm1, %xmm7
-	movapd	%xmm0, %xmm6
-	addsd	%xmm0, %xmm6
-	addsd	%xmm1, %xmm6
-	mulsd	%xmm1, %xmm1
-	movapd	%xmm4, %xmm3
-	movsd	57294(%rip), %xmm5
-	mulsd	%xmm5, %xmm3
-	mulsd	%xmm2, %xmm3
-	subsd	%xmm3, %xmm1
-	movapd	%xmm4, %xmm2
-	addsd	%xmm4, %xmm2
-	movapd	%xmm10, %xmm4
-	divsd	%xmm2, %xmm4
-	xorps	%xmm2, %xmm2
-	sqrtsd	%xmm1, %xmm2
-	addsd	%xmm2, %xmm12
-	mulsd	%xmm4, %xmm12
-	movapd	%xmm12, -224(%rbp)
-	subsd	%xmm2, %xmm7
-	movapd	%xmm4, -352(%rbp)
-	mulsd	%xmm4, %xmm7
-	movapd	%xmm7, -496(%rbp)
-	subsd	%xmm9, %xmm8
-	mulsd	%xmm5, %xmm0
-	mulsd	%xmm0, %xmm8
-	addsd	%xmm1, %xmm8
+	movq	%rcx, -400(%rbp)
+	addsd	(%rax,%rcx,8), %xmm4
+	movsd	-112(%rbp), %xmm7
+	movapd	%xmm7, %xmm3
+	mulsd	%xmm4, %xmm3
+	movsd	%xmm3, -216(%rbp)
+	addsd	%xmm0, %xmm3
+	movsd	-64(%rbp), %xmm6
+	subsd	%xmm6, %xmm3
 	xorps	%xmm1, %xmm1
-	sqrtsd	%xmm8, %xmm1
-	movsd	%xmm6, -240(%rbp)
-	movapd	%xmm6, %xmm0
-	movsd	%xmm1, -408(%rbp)
+	cvtsi2sdl	32(%rbp), %xmm1
+	subsd	%xmm6, %xmm0
+	mulsd	-504(%rbp), %xmm1
+	movsd	%xmm1, -168(%rbp)
+	mulsd	%xmm4, %xmm0
 	subsd	%xmm1, %xmm0
-	movapd	%xmm0, -368(%rbp)
-	movapd	%xmm11, -480(%rbp)
-	movapd	%xmm11, %xmm0
-	andpd	57222(%rip), %xmm0
-	movsd	57134(%rip), %xmm1
-	addsd	%xmm1, %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-184(%rbp), %xmm10
-	movapd	%xmm0, %xmm11
-	mulsd	%xmm10, %xmm11
-	xorpd	%xmm4, %xmm4
-	movapd	-224(%rbp), %xmm0
-	ucomisd	%xmm4, %xmm0
+	movapd	%xmm7, %xmm1
+	mulsd	58970(%rip), %xmm1
+	mulsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm5
+	mulsd	%xmm3, %xmm5
+	addsd	%xmm1, %xmm5
+	movapd	%xmm7, %xmm0
+	addsd	%xmm7, %xmm0
+	divsd	%xmm0, %xmm2
+	movsd	%xmm5, -480(%rbp)
+	xorps	%xmm0, %xmm0
+	sqrtsd	%xmm5, %xmm0
+	movsd	%xmm3, -152(%rbp)
+	movsd	%xmm0, -464(%rbp)
+	addsd	%xmm0, %xmm3
+	movapd	%xmm2, -352(%rbp)
+	mulsd	%xmm2, %xmm3
+	movapd	%xmm3, -208(%rbp)
+	movapd	%xmm6, %xmm0
+	mulsd	58883(%rip), %xmm0
+	movsd	%xmm0, -392(%rbp)
+	movapd	%xmm4, -496(%rbp)
+	movapd	%xmm4, %xmm0
+	andpd	58919(%rip), %xmm0
+	movsd	58855(%rip), %xmm1
+	addsd	%xmm1, %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-168(%rbp), %xmm9
+	movapd	%xmm0, %xmm13
+	mulsd	%xmm9, %xmm13
+	xorpd	%xmm5, %xmm5
+	movapd	-208(%rbp), %xmm0
+	ucomisd	%xmm5, %xmm0
 	leaq	-52(%rbp), %r14
-	movq	-440(%rbp), %r12
-	jbe	0x5869
-	movapd	-480(%rbp), %xmm0
-	subsd	-224(%rbp), %xmm0
-	movapd	57129(%rip), %xmm1
+	movq	-424(%rbp), %r12
+	jbe	0x501f
+	movapd	-496(%rbp), %xmm0
+	subsd	-208(%rbp), %xmm0
+	movapd	58826(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	57037(%rip), %xmm0
-	movsd	%xmm11, -112(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-112(%rbp), %xmm11
-	movsd	-184(%rbp), %xmm10
-	xorpd	%xmm4, %xmm4
-	mulsd	%xmm10, %xmm0
-	movapd	-224(%rbp), %xmm2
+	addsd	58758(%rip), %xmm0
+	movsd	%xmm13, -120(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-120(%rbp), %xmm13
+	movsd	-168(%rbp), %xmm9
+	xorpd	%xmm5, %xmm5
+	movapd	-208(%rbp), %xmm2
 	movapd	%xmm2, %xmm1
 	mulsd	%xmm2, %xmm1
-	movsd	-96(%rbp), %xmm8
-	mulsd	%xmm8, %xmm1
-	mulsd	56975(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movsd	-120(%rbp), %xmm0
-	mulsd	%xmm2, %xmm0
+	mulsd	-112(%rbp), %xmm1
+	mulsd	58707(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	57018(%rip), %xmm1
-	mulsd	-104(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	ucomisd	%xmm11, %xmm0
-	xorpd	%xmm1, %xmm1
-	movapd	-352(%rbp), %xmm6
-	movapd	-368(%rbp), %xmm2
-	movapd	-496(%rbp), %xmm3
-	movsd	-240(%rbp), %xmm5
-	movsd	-408(%rbp), %xmm7
-	jbe	0x5895
-	movapd	-224(%rbp), %xmm4
-	movapd	%xmm0, %xmm11
-	jmp	0x5895
-	addsd	%xmm8, %xmm1
-	movapd	%xmm1, %xmm4
-	divsd	%xmm3, %xmm4
+	movsd	-104(%rbp), %xmm10
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm2, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm2, %xmm0
+	andpd	58715(%rip), %xmm0
+	movsd	-64(%rbp), %xmm8
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	xorpd	%xmm11, %xmm11
+	movapd	-352(%rbp), %xmm7
+	movsd	-152(%rbp), %xmm12
+	movsd	-464(%rbp), %xmm0
+	jbe	0x5049
+	movapd	-208(%rbp), %xmm5
+	movapd	%xmm1, %xmm13
+	jmp	0x5049
+	addsd	%xmm0, %xmm1
+	movapd	%xmm1, %xmm5
+	divsd	%xmm2, %xmm5
 	movl	24(%rbp), %eax
 	imull	%ebx, %eax
 	addl	%r15d, %eax
-	ucomisd	%xmm4, %xmm0
+	ucomisd	%xmm5, %xmm4
 	cltq
-	jbe	0x5b1c
+	jbe	0x5360
 	movq	-72(%rbp), %rcx
-	movsd	%xmm4, (%rcx,%rax,8)
-	movsd	-192(%rbp), %xmm0
-	jmp	0x5298
-	xorpd	%xmm1, %xmm1
-	movapd	-352(%rbp), %xmm6
-	movapd	-368(%rbp), %xmm2
-	movapd	-496(%rbp), %xmm3
-	movsd	-240(%rbp), %xmm5
-	movsd	-408(%rbp), %xmm7
-	addsd	%xmm7, %xmm5
-	mulsd	%xmm6, %xmm2
-	ucomisd	%xmm1, %xmm3
-	movapd	%xmm2, -368(%rbp)
-	jbe	0x5981
-	movapd	-480(%rbp), %xmm0
-	subsd	%xmm3, %xmm0
-	movapd	56797(%rip), %xmm1
+	movsd	%xmm5, (%rcx,%rax,8)
+	movsd	-176(%rbp), %xmm1
+	jmp	0x4aa7
+	xorpd	%xmm11, %xmm11
+	movsd	-64(%rbp), %xmm8
+	movsd	-104(%rbp), %xmm10
+	movapd	-352(%rbp), %xmm7
+	movsd	-152(%rbp), %xmm12
+	movsd	-464(%rbp), %xmm0
+	movapd	%xmm12, %xmm2
+	subsd	%xmm0, %xmm2
+	mulsd	%xmm7, %xmm2
+	ucomisd	%xmm11, %xmm2
+	jbe	0x5147
+	movapd	-496(%rbp), %xmm0
+	subsd	%xmm2, %xmm0
+	movapd	58507(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	56705(%rip), %xmm0
-	movsd	%xmm4, -224(%rbp)
-	movsd	%xmm11, -112(%rbp)
-	movsd	%xmm5, -240(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-240(%rbp), %xmm5
-	movapd	-496(%rbp), %xmm3
-	movapd	-368(%rbp), %xmm2
-	movsd	-112(%rbp), %xmm11
-	movapd	-352(%rbp), %xmm6
-	movsd	-184(%rbp), %xmm10
-	movsd	-224(%rbp), %xmm4
-	movsd	-120(%rbp), %xmm9
-	movsd	-96(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
+	addsd	58439(%rip), %xmm0
+	movsd	%xmm5, -208(%rbp)
+	movsd	%xmm13, -120(%rbp)
+	movapd	%xmm2, -464(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-464(%rbp), %xmm3
+	movsd	-152(%rbp), %xmm12
+	movsd	-120(%rbp), %xmm13
+	movapd	-352(%rbp), %xmm7
+	movsd	-168(%rbp), %xmm9
+	movsd	-208(%rbp), %xmm5
+	movsd	-104(%rbp), %xmm10
+	movsd	-64(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
 	movapd	%xmm3, %xmm1
 	mulsd	%xmm3, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	56593(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm3, %xmm0
+	mulsd	-112(%rbp), %xmm1
+	mulsd	58334(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm3, %xmm1
-	andpd	56636(%rip), %xmm1
-	mulsd	-104(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0x5981
-	movapd	%xmm3, %xmm4
-	movapd	%xmm0, %xmm11
-	mulsd	%xmm5, %xmm6
-	ucomisd	%xmm2, %xmm1
-	movapd	%xmm6, -352(%rbp)
-	jbe	0x5a51
-	movapd	-480(%rbp), %xmm0
-	subsd	%xmm2, %xmm0
-	movapd	56565(%rip), %xmm1
-	andpd	%xmm1, %xmm0
-	addsd	56473(%rip), %xmm0
-	movsd	%xmm4, -224(%rbp)
-	movsd	%xmm11, -112(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-368(%rbp), %xmm2
-	movsd	-112(%rbp), %xmm11
-	movapd	-352(%rbp), %xmm6
-	movsd	-184(%rbp), %xmm10
-	movsd	-224(%rbp), %xmm4
-	movsd	-120(%rbp), %xmm9
-	movsd	-96(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
-	movapd	%xmm2, %xmm1
-	mulsd	%xmm2, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	56385(%rip), %xmm1
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
 	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm2, %xmm0
+	movapd	%xmm3, %xmm0
+	andpd	58348(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	movsd	-216(%rbp), %xmm4
+	movsd	-480(%rbp), %xmm2
+	movsd	-392(%rbp), %xmm6
+	jbe	0x515f
+	movapd	%xmm3, %xmm5
+	movapd	%xmm1, %xmm13
+	jmp	0x515f
+	movsd	-216(%rbp), %xmm4
+	movsd	-480(%rbp), %xmm2
+	movsd	-392(%rbp), %xmm6
+	movapd	%xmm10, %xmm0
+	subsd	%xmm4, %xmm0
+	mulsd	%xmm0, %xmm6
+	addsd	%xmm2, %xmm6
+	movapd	%xmm8, %xmm0
+	addsd	%xmm8, %xmm0
+	addsd	%xmm12, %xmm0
+	xorps	%xmm2, %xmm2
+	sqrtsd	%xmm6, %xmm2
+	movapd	%xmm0, %xmm3
+	subsd	%xmm2, %xmm3
+	mulsd	%xmm7, %xmm3
+	ucomisd	%xmm3, %xmm11
+	jbe	0x5280
+	movsd	%xmm0, -152(%rbp)
+	movapd	-496(%rbp), %xmm0
+	subsd	%xmm3, %xmm0
+	movapd	58183(%rip), %xmm1
+	andpd	%xmm1, %xmm0
+	addsd	58115(%rip), %xmm0
+	movsd	%xmm5, -208(%rbp)
+	movsd	%xmm13, -120(%rbp)
+	movsd	%xmm2, -216(%rbp)
+	movapd	%xmm3, -480(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-480(%rbp), %xmm3
+	movsd	-216(%rbp), %xmm2
+	movsd	-120(%rbp), %xmm13
+	movapd	-352(%rbp), %xmm7
+	movsd	-168(%rbp), %xmm9
+	movsd	-208(%rbp), %xmm5
+	movsd	-104(%rbp), %xmm10
+	movsd	-64(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
+	movapd	%xmm3, %xmm1
+	mulsd	%xmm3, %xmm1
+	mulsd	-112(%rbp), %xmm1
+	mulsd	58003(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	56428(%rip), %xmm1
-	mulsd	-104(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0x5a51
-	movapd	%xmm2, %xmm4
-	movapd	%xmm0, %xmm11
-	ucomisd	%xmm6, %xmm1
-	jbe	0x5278
-	movapd	-480(%rbp), %xmm1
-	subsd	%xmm6, %xmm1
-	movapd	56369(%rip), %xmm0
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	andpd	58017(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	movsd	-152(%rbp), %xmm0
+	ucomisd	%xmm13, %xmm1
+	jbe	0x5280
+	movapd	%xmm3, %xmm5
+	movapd	%xmm1, %xmm13
+	addsd	%xmm2, %xmm0
+	mulsd	%xmm0, %xmm7
+	ucomisd	%xmm7, %xmm11
+	jbe	0x4a87
+	movapd	-496(%rbp), %xmm1
+	subsd	%xmm7, %xmm1
+	movapd	57945(%rip), %xmm0
 	andpd	%xmm0, %xmm1
-	addsd	56277(%rip), %xmm1
+	addsd	57877(%rip), %xmm1
 	movapd	%xmm1, %xmm0
-	movsd	%xmm4, -224(%rbp)
-	movsd	%xmm11, -112(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-352(%rbp), %xmm3
-	movsd	-224(%rbp), %xmm4
-	movsd	-184(%rbp), %xmm2
-	mulsd	%xmm0, %xmm2
-	movapd	%xmm3, %xmm0
-	mulsd	%xmm3, %xmm0
-	movsd	-96(%rbp), %xmm1
+	movsd	%xmm5, -208(%rbp)
+	movapd	%xmm7, -352(%rbp)
+	movsd	%xmm13, -120(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-352(%rbp), %xmm4
+	movsd	-208(%rbp), %xmm5
+	movapd	%xmm4, %xmm1
+	mulsd	%xmm4, %xmm1
+	movsd	-112(%rbp), %xmm2
+	mulsd	%xmm1, %xmm2
+	mulsd	57813(%rip), %xmm2
+	movsd	-168(%rbp), %xmm1
 	mulsd	%xmm0, %xmm1
-	mulsd	56209(%rip), %xmm1
 	addsd	%xmm2, %xmm1
-	movsd	-120(%rbp), %xmm2
-	mulsd	%xmm3, %xmm2
-	addsd	%xmm1, %xmm2
-	movapd	%xmm3, %xmm0
-	andpd	56252(%rip), %xmm0
+	movapd	%xmm1, %xmm0
 	movsd	-104(%rbp), %xmm1
-	mulsd	%xmm0, %xmm1
-	subsd	%xmm1, %xmm2
-	ucomisd	-112(%rbp), %xmm2
-	movapd	-160(%rbp), %xmm2
-	movsd	-192(%rbp), %xmm0
-	movq	-416(%rbp), %rcx
-	jbe	0x528f
-	movapd	%xmm3, %xmm4
-	jmp	0x528f
+	mulsd	%xmm4, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm4, %xmm0
+	andpd	57816(%rip), %xmm0
+	movsd	-64(%rbp), %xmm2
+	mulsd	%xmm0, %xmm2
+	subsd	%xmm2, %xmm1
+	ucomisd	-120(%rbp), %xmm1
+	movsd	-176(%rbp), %xmm1
+	movapd	-240(%rbp), %xmm3
+	movq	-400(%rbp), %rcx
+	jbe	0x4a9e
+	movapd	%xmm4, %xmm5
+	jmp	0x4a9e
 	movq	-72(%rbp), %rcx
 	movq	$0, (%rcx,%rax,8)
-	xorpd	%xmm4, %xmm4
-	movsd	-192(%rbp), %xmm0
-	jmp	0x5298
+	xorpd	%xmm5, %xmm5
+	movsd	-176(%rbp), %xmm1
+	jmp	0x4aa7
 	nopl	(%rax)
+	movq	-72(%rbp), %rax
+	leaq	(%rax,%r15,8), %rsi
 	leaq	24(%rbp), %r13
 	movq	%r13, %rdi
-	movq	-448(%rbp), %rsi
-	leaq	-60(%rbp), %rdx
+	leaq	-76(%rbp), %rdx
 	movq	-296(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	cltq
 	movq	-272(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	movq	%r13, %rdi
 	movq	%rbx, %rsi
 	movq	%r14, %rdx
 	leaq	-48(%rbp), %rbx
 	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movq	-280(%rbp), %r12
 	movsd	(%r12,%r15,8), %xmm1
 	subsd	%xmm0, %xmm1
-	movq	-176(%rbp), %rax
+	movq	-160(%rbp), %rax
 	movsd	%xmm1, (%rax,%r15,8)
-	movq	-232(%rbp), %rax
+	movq	-224(%rbp), %rax
 	movq	$0, (%rax,%r15,8)
-	jmp	0x51b6
-	nop
+	jmp	0x49c6
 	leaq	-56(%rbp), %rdi
 	movq	%r14, %r15
 	movq	-72(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	-248(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-56(%rbp), %rax
 	leaq	(%r14,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	-176(%rbp), %rsi
+	movq	-160(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	leal	1(%rax), %ecx
 	imull	%eax, %ecx
-	movl	%ecx, -64(%rbp)
+	movl	%ecx, -80(%rbp)
 	movabsq	$-4616189618054758400, %rax
-	movq	%rax, -80(%rbp)
-	leaq	-64(%rbp), %rdi
+	movq	%rax, -88(%rbp)
+	leaq	-80(%rbp), %rdi
 	movq	-256(%rbp), %r13
 	movq	%r13, %rsi
 	movq	%r15, %rdx
-	movq	-392(%rbp), %r14
+	movq	-376(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-64(%rbp), %rdi
-	leaq	-80(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-80(%rbp), %rdi
+	leaq	-88(%rbp), %rsi
 	movq	-248(%rbp), %rdx
 	movq	%r15, %rcx
 	movq	%r14, %r8
 	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	leaq	-64(%rbp), %rdi
+	callq	0x13376 ## symbol stub for: _daxpy
+	leaq	-80(%rbp), %rdi
 	movq	%r13, %rsi
 	movq	%r15, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -160(%rbp)
-	leaq	-64(%rbp), %rdi
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -64(%rbp)
+	leaq	-80(%rbp), %rdi
 	movq	%r14, %rsi
 	movq	%r15, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -88(%rbp)
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -96(%rbp)
 	movl	24(%rbp), %edx
 	movq	48(%rbp), %rdi
 	movq	-72(%rbp), %rsi
 	callq	_UpdateIBinv
-	movsd	-88(%rbp), %xmm1
-	movsd	-160(%rbp), %xmm0
-	addsd	55704(%rip), %xmm0
+	movsd	-96(%rbp), %xmm1
+	movsd	-64(%rbp), %xmm0
+	addsd	57294(%rip), %xmm0
 	divsd	%xmm0, %xmm1
 	cmpl	$6, 40(%rbp)
-	jl	0x5100
-	leaq	56571(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
+	jl	0x4910
+	leaq	58193(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
-	movsd	%xmm1, -88(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-88(%rbp), %xmm1
-	jmp	0x5100
-	movl	-196(%rbp), %esi
+	movsd	%xmm1, -96(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-96(%rbp), %xmm1
+	jmp	0x4910
+	movl	-180(%rbp), %esi
 	cmpl	$5, 40(%rbp)
-	movq	-168(%rbp), %rbx
-	jl	0x5cfd
-	leaq	56539(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
+	movq	-144(%rbp), %rbx
+	jl	0x5537
+	leaq	58161(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
 	movsd	-128(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movq	-384(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-376(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133c4 ## symbol stub for: _printf
+	movq	-368(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-360(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-264(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-136(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-288(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-272(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-400(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-384(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-232(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-424(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-224(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-408(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-304(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-296(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-256(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-248(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-392(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-376(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movsd	-128(%rbp), %xmm0
 	addq	$504, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopl	(%rax,%rax)
+	nopw	%cs:(%rax,%rax)
 _Weighted_LassoSf_MLf:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
-	subq	$568, %rsp
-	movsd	%xmm3, -80(%rbp)
-	movsd	%xmm2, -544(%rbp)
+	subq	$584, %rsp
+	movsd	%xmm3, -176(%rbp)
+	movsd	%xmm2, -552(%rbp)
 	movsd	%xmm1, -128(%rbp)
-	movsd	%xmm0, -184(%rbp)
+	movsd	%xmm0, -216(%rbp)
 	movq	%r9, %r13
 	movq	%r8, -96(%rbp)
 	movq	%rcx, -88(%rbp)
-	movq	%rdx, -152(%rbp)
-	movq	%rsi, -264(%rbp)
-	movq	%rdi, -536(%rbp)
-	movslq	24(%rbp), %r14
+	movq	%rdx, -144(%rbp)
+	movq	%rsi, -416(%rbp)
+	movq	%rdi, -544(%rbp)
 	movl	32(%rbp), %ebx
-	imull	%r14d, %ebx
-	movl	%r14d, -68(%rbp)
+	movl	%ebx, -80(%rbp)
+	movl	24(%rbp), %eax
+	movl	%eax, -68(%rbp)
+	movslq	%eax, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -512(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -520(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
-	movl	%ebx, -300(%rbp)
-	imull	%r14d, %r14d
-	movl	%r14d, -56(%rbp)
-	movslq	%ebx, %rbx
-	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r15
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -424(%rbp)
+	movl	%ebx, %eax
+	imull	%r14d, %eax
+	movl	%eax, -292(%rbp)
+	movl	%r14d, %r15d
+	imull	%r14d, %r15d
+	movl	%r15d, -56(%rbp)
+	movslq	%eax, %r12
 	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%r12, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
+	movl	$8, %esi
+	movq	%r12, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r12
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
-	movl	$0, -296(%rbp)
-	leaq	-300(%rbp), %rdi
+	movl	$0, -288(%rbp)
+	leaq	-292(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
 	movq	-88(%rbp), %rsi
-	movq	%r15, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-300(%rbp), %rdi
+	movq	%rbx, %rcx
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-292(%rbp), %rdi
 	movq	-96(%rbp), %rsi
 	leaq	-52(%rbp), %rdx
-	movq	%rbx, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	24(%rbp), %r8d
-	movl	32(%rbp), %r9d
-	movq	%r15, -160(%rbp)
-	movq	%r15, %rdi
-	movq	%rbx, -320(%rbp)
-	movq	%rbx, %rsi
-	movq	-512(%rbp), %rdx
-	movq	%r12, -504(%rbp)
 	movq	%r12, %rcx
+	leaq	-48(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	%rbx, -192(%rbp)
+	movq	%rbx, %rdi
+	movq	%r12, -336(%rbp)
+	movq	%r12, %rsi
+	movq	-520(%rbp), %rdx
+	movq	-424(%rbp), %rcx
+	movl	%r14d, %r8d
+	movl	-80(%rbp), %r9d
 	callq	_centerYX
 	cmpl	$5, 40(%rbp)
-	jl	0x5f2f
-	leaq	55751(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
-	movsd	-80(%rbp), %xmm0
+	jl	0x5782
+	leaq	57355(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
+	movsd	-176(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movl	-56(%rbp), %r14d
-	movq	$0, -200(%rbp)
-	movslq	%r14d, %r14
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-56(%rbp), %r15d
+	movslq	24(%rbp), %r14
+	movq	$0, -232(%rbp)
+	movslq	%r15d, %r15
 	movl	$8, %esi
-	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -96(%rbp)
-	movslq	24(%rbp), %rdi
-	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -256(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -272(%rbp)
+	movl	$8, %esi
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	leaq	-56(%rbp), %r14
 	leaq	-52(%rbp), %r15
 	leaq	-48(%rbp), %r8
 	movq	%r14, %rdi
-	movq	-536(%rbp), %rsi
+	movq	-544(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movsd	-184(%rbp), %xmm0
+	callq	0x1337c ## symbol stub for: _dcopy
+	movsd	-216(%rbp), %xmm0
 	addsd	%xmm0, %xmm0
 	subsd	-128(%rbp), %xmm0
-	mulsd	-80(%rbp), %xmm0
-	movsd	%xmm0, -600(%rbp)
-	leaq	-600(%rbp), %rsi
+	mulsd	-176(%rbp), %xmm0
+	movsd	%xmm0, -616(%rbp)
+	leaq	-616(%rbp), %rsi
 	movq	%r14, %rdi
-	movq	%rbx, -520(%rbp)
+	movq	%rbx, -528(%rbp)
 	movq	%rbx, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	$0, -552(%rbp)
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	$0, -560(%rbp)
 	movslq	24(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	24(%rbp), %rdi
-	leaq	-552(%rbp), %rsi
-	leaq	-296(%rbp), %rdx
-	movq	%rax, -168(%rbp)
+	leaq	-560(%rbp), %rsi
+	leaq	-288(%rbp), %rdx
+	movq	%rax, -200(%rbp)
 	movq	%rax, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %r14d
 	testl	%r14d, %r14d
-	jle	0x60cc
+	jle	0x592b
 	xorl	%r15d, %r15d
-	movapd	54909(%rip), %xmm1
+	movapd	56456(%rip), %xmm1
 	leaq	-68(%rbp), %r12
-	movq	-264(%rbp), %rbx
-	jmp	0x6068
+	movq	-416(%rbp), %rbx
+	jmp	0x58c7
+	nopw	%cs:(%rax,%rax)
 	subl	%r14d, %eax
 	movl	%eax, -100(%rbp)
 	leaq	(%rdi,%r15,8), %rsi
 	leaq	24(%rbp), %rdi
 	movq	%r12, %rdx
-	callq	0x134f6 ## symbol stub for: _dasum
-	movapd	54866(%rip), %xmm1
-	movq	-256(%rbp), %rax
+	callq	0x13370 ## symbol stub for: _dasum
+	movapd	56402(%rip), %xmm1
+	movq	-272(%rbp), %rax
 	movsd	%xmm0, (%rax,%r15,8)
-	addq	$1, %r15
+	incq	%r15
 	movslq	24(%rbp), %r14
 	cmpq	%r14, %r15
-	jge	0x60cc
+	jge	0x592b
 	testl	%r14d, %r14d
-	movq	-520(%rbp), %rsi
+	movq	-528(%rbp), %rsi
 	movq	-96(%rbp), %rdi
-	jle	0x6036
+	jle	0x5896
 	movl	%r14d, %ecx
 	movl	%r15d, %eax
 	xorl	%edx, %edx
-	movsd	54696(%rip), %xmm2
-	jmp	0x60ad
-	nopw	(%rax,%rax)
+	movsd	56249(%rip), %xmm2
+	jmp	0x590c
+	nopl	(%rax)
 	movq	$0, (%rbx,%rax,8)
 	xorpd	%xmm0, %xmm0
 	movsd	%xmm0, (%rdi,%rax,8)
-	addq	$1, %rdx
+	incq	%rdx
 	addl	%r14d, %eax
 	cmpq	%rdx, %rcx
-	je	0x6030
+	je	0x5890
 	cltq
 	movsd	(%r13,%rax,8), %xmm0
 	andpd	%xmm1, %xmm0
 	ucomisd	(%rsi,%rax,8), %xmm0
-	jb	0x6090
+	jb	0x58f0
 	movapd	%xmm2, %xmm0
 	cmpq	%rdx, %r15
-	jne	0x609c
-	jmp	0x6090
+	jne	0x58fc
+	jmp	0x58f0
 	movslq	%r14d, %rbx
 	movb	$78, -41(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
 	movslq	-56(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -192(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -224(%rbp)
 	movslq	32(%rbp), %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rbx, %rcx
-	movq	%rax, -328(%rbp)
+	movq	%rax, -360(%rbp)
 	testl	%ecx, %ecx
-	movq	%r13, -176(%rbp)
-	jle	0x620f
+	movq	%r13, -208(%rbp)
+	jle	0x5a6e
 	xorl	%r15d, %r15d
-	movq	-320(%rbp), %r13
-	movq	-160(%rbp), %r12
+	movq	-336(%rbp), %r13
+	movq	-192(%rbp), %r12
 	leaq	24(%rbp), %rbx
-	nopw	(%rax,%rax)
+	nopl	(%rax)
 	leaq	32(%rbp), %r14
 	movq	%r14, %rdi
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
 	movq	%r12, %rcx
 	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -128(%rbp)
 	movq	%r14, %rdi
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
 	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	-128(%rbp), %xmm1
 	divsd	%xmm0, %xmm1
-	movq	-176(%rbp), %rax
+	movq	-208(%rbp), %rax
 	movsd	%xmm1, (%rax,%r15,8)
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	cltq
-	movq	-192(%rbp), %rcx
+	movq	-224(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r10
-	movsd	54413(%rip), %xmm1
+	movsd	55965(%rip), %xmm1
 	divsd	%xmm0, %xmm1
 	movsd	%xmm1, -64(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%r14, %rdx
 	leaq	-64(%rbp), %rcx
-	movq	-160(%rbp), %r8
+	movq	-192(%rbp), %r8
 	leaq	-68(%rbp), %r9
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%r10
-	leaq	-200(%rbp), %rax
+	leaq	-232(%rbp), %rax
 	pushq	%rax
 	pushq	%rbx
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	addq	$1, %r15
+	incq	%r15
 	movl	24(%rbp), %r14d
 	movslq	%r14d, %rcx
 	addq	$8, %r12
 	addq	$8, %r13
 	cmpq	%rcx, %r15
-	jl	0x6140
+	jl	0x59a0
 	movslq	-56(%rbp), %r15
 	movslq	32(%rbp), %r12
-	movq	-176(%rbp), %r13
-	movsd	-184(%rbp), %xmm0
-	mulsd	-80(%rbp), %xmm0
-	movsd	%xmm0, -184(%rbp)
+	movq	-208(%rbp), %r13
+	movsd	-216(%rbp), %xmm0
+	mulsd	-176(%rbp), %xmm0
+	movsd	%xmm0, -216(%rbp)
 	movl	$8, %esi
 	movq	%rcx, %rbx
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -584(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -600(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -424(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -448(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -416(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -440(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -280(%rbp)
 	leal	1(%r14), %eax
 	imull	%r14d, %eax
 	movl	%eax, -100(%rbp)
 	movslq	%eax, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -248(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -264(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -312(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -328(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -408(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -432(%rbp)
 	movl	16(%rbp), %eax
 	testl	%eax, %eax
 	movl	$0, %ecx
 	cmovgl	%eax, %ecx
-	movl	%ecx, -292(%rbp)
+	movl	%ecx, -284(%rbp)
 	xorl	%esi, %esi
-	movq	-192(%rbp), %r14
-	movq	-264(%rbp), %r12
+	movq	-224(%rbp), %r14
+	movq	-416(%rbp), %r12
 	leaq	-48(%rbp), %r15
-	jmp	0x6316
-	nopw	(%rax,%rax)
-	movl	-444(%rbp), %esi
-	addl	$1, %esi
-	movsd	54111(%rip), %xmm0
+	jmp	0x5b75
+	nopl	(%rax)
+	movl	-476(%rbp), %esi
+	incl	%esi
+	movsd	55672(%rip), %xmm0
 	ucomisd	%xmm1, %xmm0
 	leaq	-48(%rbp), %r15
-	movq	-176(%rbp), %r13
-	ja	0x6f23
-	cmpl	-292(%rbp), %esi
-	je	0x6f1d
-	movl	%esi, -444(%rbp)
+	movq	-208(%rbp), %r13
+	ja	0x67a9
+	cmpl	-284(%rbp), %esi
+	je	0x67a3
+	movl	%esi, -476(%rbp)
 	leaq	-56(%rbp), %rdi
 	movq	%r12, %rsi
 	leaq	-52(%rbp), %rdx
-	movq	-248(%rbp), %rbx
+	movq	-264(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-56(%rbp), %rax
 	leaq	(%rbx,%rax,8), %rcx
 	movq	%r13, %rbx
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
+	movq	-144(%rbp), %rsi
 	leaq	-52(%rbp), %rdx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	xorpd	%xmm1, %xmm1
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
 	movq	-96(%rbp), %rdx
-	movq	-256(%rbp), %r15
-	jle	0x6e00
+	movq	-272(%rbp), %r15
+	jle	0x6680
 	xorl	%r13d, %r13d
-	jmp	0x63db
+	jmp	0x5c3a
 	nopw	%cs:(%rax,%rax)
 	leaq	(%r12,%r13,8), %rcx
 	leaq	24(%rbp), %rdi
-	leaq	-552(%rbp), %rsi
-	leaq	-296(%rbp), %rdx
+	leaq	-560(%rbp), %rsi
+	leaq	-288(%rbp), %rdx
 	leaq	-68(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movsd	(%rbx,%r13,8), %xmm0
-	movq	-152(%rbp), %rax
+	movq	-144(%rbp), %rax
 	movsd	%xmm0, (%rax,%r13,8)
-	addq	$1, %r13
+	incq	%r13
 	movslq	24(%rbp), %rax
 	cmpq	%rax, %r13
 	movq	-96(%rbp), %rdx
 	xorpd	%xmm1, %xmm1
-	jge	0x6e00
+	jge	0x6680
 	movsd	(%r15,%r13,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0x6390
+	jbe	0x5bf0
 	cmpl	$7, 40(%rbp)
-	jl	0x6409
-	leaq	54580(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating gene %d \n"
+	jl	0x5c68
+	leaq	56165(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating gene %d \n"
 	movl	%r13d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	xorpd	%xmm1, %xmm1
 	movq	-96(%rbp), %rdx
 	movl	24(%rbp), %eax
-	movq	-168(%rbp), %rcx
+	movq	-200(%rbp), %rcx
 	movabsq	$4607182418800017408, %rsi
 	movq	%rsi, (%rcx,%r13,8)
-	leaq	(%r12,%r13,8), %rcx
-	movq	%rcx, -272(%rbp)
 	testl	%eax, %eax
-	movq	%r13, -400(%rbp)
-	jle	0x6d70
+	movq	%r13, -152(%rbp)
+	jle	0x65f0
 	movl	%eax, %ecx
 	imull	%r13d, %ecx
 	movslq	%ecx, %rcx
 	movq	72(%rbp), %rsi
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -432(%rbp)
-	movq	-320(%rbp), %rcx
+	movq	%rcx, -464(%rbp)
+	leaq	(%r12,%r13,8), %rcx
+	movq	%rcx, -352(%rbp)
+	movq	-336(%rbp), %rcx
 	leaq	(%rcx,%r13,8), %rcx
-	movq	%rcx, -592(%rbp)
+	movq	%rcx, -608(%rbp)
 	movl	%r13d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -288(%rbp)
-	movq	-160(%rbp), %rbx
+	movq	%rcx, -456(%rbp)
+	movq	-192(%rbp), %rbx
 	xorl	%r15d, %r15d
-	jmp	0x6507
-	movsd	53667(%rip), %xmm0
-	movapd	-128(%rbp), %xmm2
-	movsd	-384(%rbp), %xmm1
-	movsd	%xmm4, (%r12,%rbx,8)
-	movq	-192(%rbp), %r14
-	movq	-400(%rbp), %r13
-	movq	-496(%rbp), %rbx
-	subsd	%xmm4, %xmm1
-	mulsd	%xmm1, %xmm2
-	addsd	%xmm0, %xmm2
-	divsd	%xmm2, %xmm0
-	movsd	%xmm0, -440(%rbp)
+	jmp	0x5d68
+	movsd	55220(%rip), %xmm0
+	movsd	-400(%rbp), %xmm1
+	movapd	-176(%rbp), %xmm3
+	movsd	%xmm5, (%r12,%rbx,8)
+	movq	-224(%rbp), %r14
+	movq	-152(%rbp), %r13
+	movq	-512(%rbp), %rbx
+	subsd	%xmm5, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	divsd	%xmm1, %xmm0
+	movsd	%xmm0, -472(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-440(%rbp), %rsi
-	movq	-432(%rbp), %rdx
+	leaq	-472(%rbp), %rsi
+	movq	-464(%rbp), %rdx
 	leaq	-52(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	24(%rbp), %eax
 	movq	-96(%rbp), %rdx
 	xorpd	%xmm1, %xmm1
-	addq	$1, %r15
+	incq	%r15
 	movslq	%eax, %rcx
 	addq	$8, %rbx
 	cmpq	%rcx, %r15
-	jge	0x6d70
+	jge	0x65f0
 	movl	%r15d, %ecx
 	imull	%eax, %ecx
 	addl	%r13d, %ecx
 	movslq	%ecx, %rcx
 	movsd	(%rdx,%rcx,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0x64f3
-	movq	-288(%rbp), %rax
-	movsd	(%rax,%r15,8), %xmm2
+	jbe	0x5d55
+	movq	-456(%rbp), %rax
+	movsd	(%rax,%r15,8), %xmm3
 	movsd	(%r12,%rcx,8), %xmm1
-	movapd	%xmm1, %xmm4
+	movapd	%xmm1, %xmm5
 	cmpq	%r15, %r13
-	movsd	53488(%rip), %xmm0
-	je	0x64b5
-	movsd	%xmm1, -384(%rbp)
+	movsd	55039(%rip), %xmm0
+	je	0x5d17
+	movsd	%xmm1, -400(%rbp)
 	leaq	32(%rbp), %rdi
-	movq	%rbx, -496(%rbp)
+	movq	%rbx, -512(%rbp)
 	movq	%rbx, %rsi
 	leaq	24(%rbp), %r12
 	movq	%r12, %rdx
-	movq	-328(%rbp), %rcx
+	movq	-360(%rbp), %rcx
 	leaq	-52(%rbp), %r14
 	movq	%r14, %r8
-	movapd	%xmm2, -128(%rbp)
-	callq	0x13502 ## symbol stub for: _dcopy
+	movapd	%xmm3, -176(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	addl	%r13d, %eax
 	cltq
-	movq	-536(%rbp), %rcx
+	movq	-544(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	mulsd	-184(%rbp), %xmm0
-	movsd	%xmm0, -80(%rbp)
+	mulsd	-216(%rbp), %xmm0
+	movsd	%xmm0, -128(%rbp)
 	movq	%r12, %rdi
-	movq	-272(%rbp), %rsi
+	movq	-352(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
 	movq	-280(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	movq	%r12, %rdi
 	leaq	-64(%rbp), %r13
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, (%rbx,%r15,8)
 	movq	%r12, %rdi
-	movq	-168(%rbp), %rsi
+	movq	-200(%rbp), %rsi
 	movq	%r14, %rdx
-	movq	-416(%rbp), %r14
+	movq	-440(%rbp), %r14
 	movq	%r14, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
 	movq	%r12, %rdi
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
-	movq	-400(%rbp), %rbx
+	movq	-152(%rbp), %rbx
 	leaq	-52(%rbp), %r13
 	movq	%r13, %rcx
 	movq	%r14, %r8
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	leaq	32(%rbp), %rdi
-	movq	-592(%rbp), %rsi
+	movq	-608(%rbp), %rsi
 	movq	%r12, %rdx
-	movq	-424(%rbp), %r12
+	movq	-448(%rbp), %r12
 	movq	%r12, %rcx
 	movq	%r13, %r8
 	movq	%rbx, %r13
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	-152(%rbp), %rax
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	-144(%rbp), %rax
 	movsd	(%rax,%rbx,8), %xmm0
-	xorpd	53277(%rip), %xmm0
+	xorpd	54809(%rip), %xmm0
 	movlpd	%xmm0, -64(%rbp)
 	leaq	32(%rbp), %rdi
 	movq	%rdi, %rbx
 	leaq	-64(%rbp), %rsi
 	movq	%r12, %rdx
 	leaq	-52(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movb	$84, -41(%rbp)
 	movabsq	$4607182418800017408, %rax
-	movq	%rax, -200(%rbp)
+	movq	%rax, -232(%rbp)
 	movq	%rax, -64(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
 	movq	%rbx, %rdx
 	leaq	-64(%rbp), %rcx
-	movq	-160(%rbp), %r8
+	movq	-192(%rbp), %r8
 	leaq	-68(%rbp), %r9
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%r12
-	leaq	-200(%rbp), %rax
+	leaq	-232(%rbp), %rax
 	pushq	%rax
 	leaq	-52(%rbp), %rbx
 	pushq	%rbx
 	pushq	%r14
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	leaq	32(%rbp), %rdi
-	movq	-328(%rbp), %rcx
+	movq	-360(%rbp), %rcx
 	movq	%rcx, %rsi
 	movq	%rbx, %rdx
 	movq	%rcx, %rbx
 	leaq	-48(%rbp), %r8
 	movq	%r8, %r14
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -88(%rbp)
 	leaq	32(%rbp), %rdi
 	movq	%rbx, %rsi
 	leaq	-52(%rbp), %rdx
 	movq	%r12, %rcx
 	movq	%r14, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movapd	-128(%rbp), %xmm2
-	movapd	%xmm0, %xmm8
-	movapd	%xmm2, %xmm0
-	andpd	53098(%rip), %xmm0
-	movsd	52994(%rip), %xmm1
-	ucomisd	%xmm0, %xmm1
-	jbe	0x67c8
+	callq	0x13382 ## symbol stub for: _ddot
+	movapd	-176(%rbp), %xmm3
+	movapd	%xmm3, %xmm2
+	andpd	54632(%rip), %xmm2
+	movsd	54544(%rip), %xmm1
+	ucomisd	%xmm2, %xmm1
+	jbe	0x6020
 	cmpl	$8, 40(%rbp)
-	xorpd	%xmm0, %xmm0
-	jl	0x6781
-	leaq	53736(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
+	xorpd	%xmm4, %xmm4
+	jl	0x5fda
+	leaq	55322(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
 	movl	%r13d, %esi
 	movl	%r15d, %edx
 	xorl	%eax, %eax
-	movsd	%xmm8, -144(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-144(%rbp), %xmm8
-	movapd	-128(%rbp), %xmm2
-	xorpd	%xmm0, %xmm0
-	movapd	%xmm8, %xmm4
-	movsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm4
-	movsd	-88(%rbp), %xmm3
-	divsd	%xmm3, %xmm4
-	ucomisd	%xmm0, %xmm4
-	movq	-192(%rbp), %r14
-	movq	-264(%rbp), %r12
-	movq	-496(%rbp), %rbx
-	jbe	0x6a49
+	movsd	%xmm0, -80(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-80(%rbp), %xmm0
+	movapd	-176(%rbp), %xmm3
+	xorpd	%xmm4, %xmm4
+	movapd	%xmm0, %xmm5
+	movsd	-128(%rbp), %xmm1
+	subsd	%xmm1, %xmm5
+	movsd	-88(%rbp), %xmm2
+	divsd	%xmm2, %xmm5
+	ucomisd	%xmm4, %xmm5
+	movq	-224(%rbp), %r14
+	movq	-416(%rbp), %r12
+	movq	-512(%rbp), %rbx
+	jbe	0x624d
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	addl	%r13d, %eax
 	cltq
-	jmp	0x6a6c
+	jmp	0x626f
 	cmpl	$8, 40(%rbp)
-	movsd	%xmm8, -144(%rbp)
-	jl	0x67f9
-	leaq	53661(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
+	movsd	%xmm0, -80(%rbp)
+	jl	0x604c
+	leaq	55257(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
 	movl	%r13d, %esi
 	movl	%r15d, %edx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-144(%rbp), %xmm8
-	movapd	-128(%rbp), %xmm2
-	movsd	52782(%rip), %xmm10
-	movapd	%xmm10, %xmm11
-	divsd	%xmm2, %xmm11
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-80(%rbp), %xmm0
+	movapd	-176(%rbp), %xmm3
+	movsd	54348(%rip), %xmm2
+	movapd	%xmm2, %xmm4
+	divsd	%xmm3, %xmm4
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	addl	%r13d, %eax
 	movslq	%eax, %rbx
-	movq	-264(%rbp), %r12
-	addsd	(%r12,%rbx,8), %xmm11
-	movsd	-88(%rbp), %xmm4
-	movapd	%xmm4, %xmm9
-	mulsd	%xmm11, %xmm9
-	movapd	%xmm8, %xmm1
-	addsd	%xmm9, %xmm1
-	movsd	-80(%rbp), %xmm0
-	subsd	%xmm0, %xmm1
-	movapd	%xmm8, %xmm2
-	subsd	%xmm0, %xmm2
-	cvtsi2sdl	32(%rbp), %xmm3
-	mulsd	%xmm11, %xmm2
-	mulsd	-544(%rbp), %xmm3
-	movsd	%xmm3, -368(%rbp)
-	subsd	%xmm3, %xmm2
-	movapd	%xmm1, %xmm12
-	movapd	%xmm1, %xmm7
-	movapd	%xmm0, %xmm6
-	addsd	%xmm0, %xmm6
-	addsd	%xmm1, %xmm6
-	mulsd	%xmm1, %xmm1
-	movapd	%xmm4, %xmm3
-	movsd	52660(%rip), %xmm5
-	mulsd	%xmm5, %xmm3
-	mulsd	%xmm2, %xmm3
-	subsd	%xmm3, %xmm1
-	movapd	%xmm4, %xmm2
-	addsd	%xmm4, %xmm2
-	movapd	%xmm10, %xmm4
-	divsd	%xmm2, %xmm4
-	xorps	%xmm2, %xmm2
-	sqrtsd	%xmm1, %xmm2
-	addsd	%xmm2, %xmm12
-	mulsd	%xmm4, %xmm12
-	movapd	%xmm12, -224(%rbp)
-	subsd	%xmm2, %xmm7
-	movapd	%xmm4, -240(%rbp)
-	mulsd	%xmm4, %xmm7
-	movapd	%xmm7, -576(%rbp)
-	subsd	%xmm9, %xmm8
-	mulsd	%xmm5, %xmm0
-	mulsd	%xmm0, %xmm8
-	addsd	%xmm1, %xmm8
+	movq	-416(%rbp), %r12
+	addsd	(%r12,%rbx,8), %xmm4
+	movsd	-88(%rbp), %xmm7
+	movapd	%xmm7, %xmm3
+	mulsd	%xmm4, %xmm3
+	movsd	%xmm3, -344(%rbp)
+	addsd	%xmm0, %xmm3
+	movsd	-128(%rbp), %xmm6
+	subsd	%xmm6, %xmm3
 	xorps	%xmm1, %xmm1
-	sqrtsd	%xmm8, %xmm1
-	movsd	%xmm6, -464(%rbp)
-	movapd	%xmm6, %xmm0
-	movsd	%xmm1, -528(%rbp)
+	cvtsi2sdl	32(%rbp), %xmm1
+	subsd	%xmm6, %xmm0
+	mulsd	-552(%rbp), %xmm1
+	movsd	%xmm1, -384(%rbp)
+	mulsd	%xmm4, %xmm0
 	subsd	%xmm1, %xmm0
-	movapd	%xmm0, -352(%rbp)
-	movapd	%xmm11, -480(%rbp)
-	movapd	%xmm11, %xmm0
-	andpd	52588(%rip), %xmm0
-	movsd	52500(%rip), %xmm1
-	addsd	%xmm1, %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-368(%rbp), %xmm10
-	movapd	%xmm0, %xmm11
-	mulsd	%xmm10, %xmm11
-	xorpd	%xmm4, %xmm4
-	movapd	-224(%rbp), %xmm0
-	ucomisd	%xmm4, %xmm0
-	jbe	0x6a77
-	movapd	-480(%rbp), %xmm0
-	subsd	-224(%rbp), %xmm0
-	movapd	52506(%rip), %xmm1
+	movapd	%xmm7, %xmm1
+	mulsd	54256(%rip), %xmm1
+	mulsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm5
+	mulsd	%xmm3, %xmm5
+	addsd	%xmm1, %xmm5
+	movapd	%xmm7, %xmm0
+	addsd	%xmm7, %xmm0
+	divsd	%xmm0, %xmm2
+	movsd	%xmm5, -592(%rbp)
+	xorps	%xmm0, %xmm0
+	sqrtsd	%xmm5, %xmm0
+	movsd	%xmm3, -184(%rbp)
+	movsd	%xmm0, -576(%rbp)
+	addsd	%xmm0, %xmm3
+	movapd	%xmm2, -320(%rbp)
+	mulsd	%xmm2, %xmm3
+	movapd	%xmm3, -256(%rbp)
+	movapd	%xmm6, %xmm0
+	mulsd	54169(%rip), %xmm0
+	movsd	%xmm0, -536(%rbp)
+	movapd	%xmm4, -496(%rbp)
+	movapd	%xmm4, %xmm0
+	andpd	54205(%rip), %xmm0
+	movsd	54141(%rip), %xmm1
+	addsd	%xmm1, %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-384(%rbp), %xmm9
+	movapd	%xmm0, %xmm13
+	mulsd	%xmm9, %xmm13
+	xorpd	%xmm5, %xmm5
+	movapd	-256(%rbp), %xmm0
+	ucomisd	%xmm5, %xmm0
+	jbe	0x627a
+	movapd	-496(%rbp), %xmm0
+	subsd	-256(%rbp), %xmm0
+	movapd	54123(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	52414(%rip), %xmm0
-	movsd	%xmm11, -136(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-136(%rbp), %xmm11
-	movsd	-368(%rbp), %xmm10
-	xorpd	%xmm4, %xmm4
-	mulsd	%xmm10, %xmm0
-	movapd	-224(%rbp), %xmm2
+	addsd	54055(%rip), %xmm0
+	movsd	%xmm13, -136(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-136(%rbp), %xmm13
+	movsd	-384(%rbp), %xmm9
+	xorpd	%xmm5, %xmm5
+	movapd	-256(%rbp), %xmm2
 	movapd	%xmm2, %xmm1
 	mulsd	%xmm2, %xmm1
-	movsd	-88(%rbp), %xmm8
-	mulsd	%xmm8, %xmm1
-	mulsd	52346(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movsd	-144(%rbp), %xmm0
-	mulsd	%xmm2, %xmm0
+	mulsd	-88(%rbp), %xmm1
+	mulsd	53998(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	52386(%rip), %xmm1
-	mulsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	ucomisd	%xmm11, %xmm0
-	xorpd	%xmm1, %xmm1
-	movapd	-240(%rbp), %xmm6
-	movapd	-352(%rbp), %xmm2
-	movapd	-576(%rbp), %xmm3
-	movsd	-464(%rbp), %xmm5
-	movsd	-528(%rbp), %xmm7
-	jbe	0x6aa3
-	movapd	%xmm0, %xmm11
-	movapd	-224(%rbp), %xmm4
-	jmp	0x6aa3
-	addsd	%xmm8, %xmm1
-	movapd	%xmm1, %xmm4
-	divsd	%xmm3, %xmm4
+	movsd	-80(%rbp), %xmm10
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm2, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm2, %xmm0
+	andpd	54006(%rip), %xmm0
+	movsd	-128(%rbp), %xmm8
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	xorpd	%xmm11, %xmm11
+	movapd	-320(%rbp), %xmm7
+	movsd	-184(%rbp), %xmm12
+	movsd	-576(%rbp), %xmm0
+	jbe	0x62a4
+	movapd	%xmm1, %xmm13
+	movapd	-256(%rbp), %xmm5
+	jmp	0x62a4
+	addsd	%xmm0, %xmm1
+	movapd	%xmm1, %xmm5
+	divsd	%xmm2, %xmm5
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	addl	%r13d, %eax
-	ucomisd	%xmm4, %xmm0
+	ucomisd	%xmm5, %xmm4
 	cltq
-	jbe	0x6d43
-	movsd	%xmm4, (%r12,%rax,8)
-	jmp	0x6d4f
-	xorpd	%xmm1, %xmm1
-	movapd	-240(%rbp), %xmm6
-	movapd	-352(%rbp), %xmm2
-	movapd	-576(%rbp), %xmm3
-	movsd	-464(%rbp), %xmm5
-	movsd	-528(%rbp), %xmm7
-	addsd	%xmm7, %xmm5
-	mulsd	%xmm6, %xmm2
-	ucomisd	%xmm1, %xmm3
-	movapd	%xmm2, -352(%rbp)
-	jbe	0x6b98
-	movapd	-480(%rbp), %xmm0
-	subsd	%xmm3, %xmm0
-	movapd	52175(%rip), %xmm1
+	jbe	0x65ce
+	movsd	%xmm5, (%r12,%rax,8)
+	jmp	0x65da
+	xorpd	%xmm11, %xmm11
+	movsd	-128(%rbp), %xmm8
+	movsd	-80(%rbp), %xmm10
+	movapd	-320(%rbp), %xmm7
+	movsd	-184(%rbp), %xmm12
+	movsd	-576(%rbp), %xmm0
+	movapd	%xmm12, %xmm2
+	subsd	%xmm0, %xmm2
+	mulsd	%xmm7, %xmm2
+	ucomisd	%xmm11, %xmm2
+	jbe	0x63a8
+	movapd	-496(%rbp), %xmm0
+	subsd	%xmm2, %xmm0
+	movapd	53808(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	52083(%rip), %xmm0
-	movsd	%xmm4, -224(%rbp)
-	movsd	%xmm11, -136(%rbp)
-	movsd	%xmm5, -464(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-464(%rbp), %xmm5
+	addsd	53740(%rip), %xmm0
+	movsd	%xmm5, -256(%rbp)
+	movsd	%xmm13, -136(%rbp)
+	movapd	%xmm2, -576(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
 	movapd	-576(%rbp), %xmm3
-	movapd	-352(%rbp), %xmm2
-	movsd	-136(%rbp), %xmm11
-	movapd	-240(%rbp), %xmm6
-	movsd	-368(%rbp), %xmm10
-	movsd	-224(%rbp), %xmm4
-	movsd	-144(%rbp), %xmm9
-	movsd	-88(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
+	movsd	-184(%rbp), %xmm12
+	movsd	-136(%rbp), %xmm13
+	movapd	-320(%rbp), %xmm7
+	movsd	-384(%rbp), %xmm9
+	movsd	-256(%rbp), %xmm5
+	movsd	-80(%rbp), %xmm10
+	movsd	-128(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
 	movapd	%xmm3, %xmm1
 	mulsd	%xmm3, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	51962(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm3, %xmm0
+	mulsd	-88(%rbp), %xmm1
+	mulsd	53629(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm3, %xmm1
-	andpd	52005(%rip), %xmm1
-	mulsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0x6b98
-	movapd	%xmm0, %xmm11
-	movapd	%xmm3, %xmm4
-	mulsd	%xmm5, %xmm6
-	ucomisd	%xmm2, %xmm1
-	movapd	%xmm6, -240(%rbp)
-	jbe	0x6c71
-	movapd	-480(%rbp), %xmm0
-	subsd	%xmm2, %xmm0
-	movapd	51934(%rip), %xmm1
-	andpd	%xmm1, %xmm0
-	addsd	51842(%rip), %xmm0
-	movsd	%xmm4, -224(%rbp)
-	movsd	%xmm11, -136(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-352(%rbp), %xmm2
-	movsd	-136(%rbp), %xmm11
-	movapd	-240(%rbp), %xmm6
-	movsd	-368(%rbp), %xmm10
-	movsd	-224(%rbp), %xmm4
-	movsd	-144(%rbp), %xmm9
-	movsd	-88(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
-	movapd	%xmm2, %xmm1
-	mulsd	%xmm2, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	51745(%rip), %xmm1
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
 	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm2, %xmm0
+	movapd	%xmm3, %xmm0
+	andpd	53643(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	movsd	-344(%rbp), %xmm4
+	movsd	-592(%rbp), %xmm2
+	movsd	-536(%rbp), %xmm6
+	jbe	0x63c0
+	movapd	%xmm1, %xmm13
+	movapd	%xmm3, %xmm5
+	jmp	0x63c0
+	movsd	-344(%rbp), %xmm4
+	movsd	-592(%rbp), %xmm2
+	movsd	-536(%rbp), %xmm6
+	movapd	%xmm10, %xmm0
+	subsd	%xmm4, %xmm0
+	mulsd	%xmm0, %xmm6
+	addsd	%xmm2, %xmm6
+	movapd	%xmm8, %xmm0
+	addsd	%xmm8, %xmm0
+	addsd	%xmm12, %xmm0
+	xorps	%xmm2, %xmm2
+	sqrtsd	%xmm6, %xmm2
+	movapd	%xmm0, %xmm3
+	subsd	%xmm2, %xmm3
+	mulsd	%xmm7, %xmm3
+	ucomisd	%xmm3, %xmm11
+	jbe	0x64e7
+	movsd	%xmm0, -184(%rbp)
+	movapd	-496(%rbp), %xmm0
+	subsd	%xmm3, %xmm0
+	movapd	53478(%rip), %xmm1
+	andpd	%xmm1, %xmm0
+	addsd	53410(%rip), %xmm0
+	movsd	%xmm5, -256(%rbp)
+	movsd	%xmm13, -136(%rbp)
+	movsd	%xmm2, -344(%rbp)
+	movapd	%xmm3, -592(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-592(%rbp), %xmm3
+	movsd	-344(%rbp), %xmm2
+	movsd	-136(%rbp), %xmm13
+	movapd	-320(%rbp), %xmm7
+	movsd	-384(%rbp), %xmm9
+	movsd	-256(%rbp), %xmm5
+	movsd	-80(%rbp), %xmm10
+	movsd	-128(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
+	movapd	%xmm3, %xmm1
+	mulsd	%xmm3, %xmm1
+	mulsd	-88(%rbp), %xmm1
+	mulsd	53292(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	51788(%rip), %xmm1
-	mulsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0x6c71
-	movapd	%xmm0, %xmm11
-	movapd	%xmm2, %xmm4
-	ucomisd	%xmm6, %xmm1
-	jbe	0x6485
-	movapd	-480(%rbp), %xmm1
-	subsd	%xmm6, %xmm1
-	movapd	51729(%rip), %xmm0
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	andpd	53306(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	movsd	-184(%rbp), %xmm0
+	ucomisd	%xmm13, %xmm1
+	jbe	0x64e7
+	movapd	%xmm1, %xmm13
+	movapd	%xmm3, %xmm5
+	addsd	%xmm2, %xmm0
+	mulsd	%xmm0, %xmm7
+	ucomisd	%xmm7, %xmm11
+	jbe	0x5ce4
+	movapd	-496(%rbp), %xmm1
+	subsd	%xmm7, %xmm1
+	movapd	53234(%rip), %xmm0
 	andpd	%xmm0, %xmm1
-	addsd	51637(%rip), %xmm1
+	addsd	53166(%rip), %xmm1
 	movapd	%xmm1, %xmm0
-	movsd	%xmm4, -224(%rbp)
-	movsd	%xmm11, -136(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-240(%rbp), %xmm3
-	movsd	-224(%rbp), %xmm4
-	movsd	-368(%rbp), %xmm2
-	mulsd	%xmm0, %xmm2
-	movapd	%xmm3, %xmm0
-	mulsd	%xmm3, %xmm0
-	movsd	-88(%rbp), %xmm1
+	movsd	%xmm5, -256(%rbp)
+	movapd	%xmm7, -320(%rbp)
+	movsd	%xmm13, -136(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-320(%rbp), %xmm4
+	movsd	-256(%rbp), %xmm5
+	movapd	%xmm4, %xmm1
+	mulsd	%xmm4, %xmm1
+	movsd	-88(%rbp), %xmm2
+	mulsd	%xmm1, %xmm2
+	mulsd	53099(%rip), %xmm2
+	movsd	-384(%rbp), %xmm1
 	mulsd	%xmm0, %xmm1
-	mulsd	51566(%rip), %xmm1
 	addsd	%xmm2, %xmm1
-	movsd	-144(%rbp), %xmm2
-	mulsd	%xmm3, %xmm2
-	addsd	%xmm1, %xmm2
-	movapd	%xmm3, %xmm0
-	andpd	51606(%rip), %xmm0
+	movapd	%xmm1, %xmm0
 	movsd	-80(%rbp), %xmm1
-	mulsd	%xmm0, %xmm1
-	subsd	%xmm1, %xmm2
-	ucomisd	-136(%rbp), %xmm2
-	movsd	51465(%rip), %xmm0
-	movapd	-128(%rbp), %xmm2
-	movsd	-384(%rbp), %xmm1
-	jbe	0x649a
-	movapd	%xmm3, %xmm4
-	jmp	0x649a
+	mulsd	%xmm4, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm4, %xmm0
+	andpd	53102(%rip), %xmm0
+	movsd	-128(%rbp), %xmm2
+	mulsd	%xmm0, %xmm2
+	subsd	%xmm2, %xmm1
+	ucomisd	-136(%rbp), %xmm1
+	movsd	52977(%rip), %xmm0
+	movsd	-400(%rbp), %xmm1
+	movapd	-176(%rbp), %xmm3
+	jbe	0x5cfc
+	movapd	%xmm4, %xmm5
+	jmp	0x5cfc
 	movq	$0, (%r12,%rax,8)
-	xorpd	%xmm4, %xmm4
-	movsd	51417(%rip), %xmm0
-	movsd	-384(%rbp), %xmm1
-	jmp	0x64b5
-	nopw	%cs:(%rax,%rax)
+	xorpd	%xmm5, %xmm5
+	movsd	52926(%rip), %xmm0
+	movsd	-400(%rbp), %xmm1
+	jmp	0x5d17
 	nop
+	leaq	(%r12,%r13,8), %rsi
 	leaq	24(%rbp), %r13
 	movq	%r13, %rdi
-	movq	-272(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
 	movq	-280(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-52(%rbp), %r15
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
-	imull	-400(%rbp), %eax
+	imull	-152(%rbp), %eax
 	cltq
 	leaq	(%r14,%rax,8), %rcx
 	movq	%r13, %rdi
 	movq	%rbx, %rsi
-	movq	-400(%rbp), %r13
+	movq	-152(%rbp), %r13
 	movq	%r15, %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movq	-176(%rbp), %rbx
+	callq	0x13382 ## symbol stub for: _ddot
+	movq	-208(%rbp), %rbx
 	movsd	(%rbx,%r13,8), %xmm1
 	subsd	%xmm0, %xmm1
-	movq	-152(%rbp), %rax
+	movq	-144(%rbp), %rax
 	movsd	%xmm1, (%rax,%r13,8)
-	movq	-168(%rbp), %rax
+	movq	-200(%rbp), %rax
 	movq	$0, (%rax,%r13,8)
-	movq	-256(%rbp), %r15
-	jmp	0x63c2
+	movq	-272(%rbp), %r15
+	jmp	0x5c22
 	nopw	(%rax,%rax)
 	leaq	-56(%rbp), %rdi
 	movq	%r12, %rsi
 	leaq	-52(%rbp), %r13
 	movq	%r13, %rdx
-	movq	-312(%rbp), %rbx
+	movq	-328(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r15
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-56(%rbp), %rax
 	leaq	(%rbx,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
+	movq	-144(%rbp), %rsi
 	movq	%r13, %rdx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	leal	1(%rax), %ecx
 	imull	%eax, %ecx
 	movl	%ecx, -100(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-100(%rbp), %r15
 	movq	%r15, %rdi
-	movq	-248(%rbp), %rbx
+	movq	-264(%rbp), %rbx
 	movq	%rbx, %rsi
 	movq	%r13, %rdx
-	movq	-408(%rbp), %r12
+	movq	-432(%rbp), %r12
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r15, %rdi
 	leaq	-64(%rbp), %rsi
-	movq	-312(%rbp), %rdx
+	movq	-328(%rbp), %rdx
 	movq	%r13, %rcx
 	movq	%r12, %r8
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r15, %rdi
 	movq	%rbx, %rsi
 	movq	%r13, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -80(%rbp)
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -176(%rbp)
 	movq	%r15, %rdi
 	movq	%r12, %rsi
-	movq	-264(%rbp), %r12
+	movq	-416(%rbp), %r12
 	movq	%r13, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	movsd	%xmm0, -128(%rbp)
 	movl	24(%rbp), %edx
 	movq	72(%rbp), %rdi
 	movq	%r12, %rsi
 	callq	_UpdateIBinv
 	movsd	-128(%rbp), %xmm1
-	movsd	-80(%rbp), %xmm0
-	addsd	51026(%rip), %xmm0
+	movsd	-176(%rbp), %xmm0
+	addsd	52540(%rip), %xmm0
 	divsd	%xmm0, %xmm1
 	cmpl	$6, 40(%rbp)
-	jl	0x62f0
-	leaq	51893(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
+	jl	0x5b50
+	leaq	53439(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
 	movsd	%xmm1, -128(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-128(%rbp), %xmm1
-	jmp	0x62f0
-	movl	-292(%rbp), %esi
+	jmp	0x5b50
+	movl	-284(%rbp), %esi
 	cmpl	$4, 40(%rbp)
-	jl	0x6f3f
-	leaq	51868(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
-	movsd	-184(%rbp), %xmm0
+	jl	0x67c5
+	leaq	53414(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
+	movsd	-216(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	leaq	-56(%rbp), %rdi
 	leaq	-52(%rbp), %r14
 	leaq	-48(%rbp), %rbx
 	movq	%r12, %rsi
 	movq	%r14, %rdx
 	movq	48(%rbp), %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
+	movq	-144(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	56(%rbp), %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$5, 40(%rbp)
-	movq	-256(%rbp), %r15
-	jl	0x6f90
-	leaq	52082(%rip), %rdi ## literal pool for: "Enter Function: constrained-MLf. Shrinkage lambda is: 0. "
-	callq	0x13556 ## symbol stub for: _puts
+	movq	-272(%rbp), %r15
+	jl	0x6816
+	leaq	53628(%rip), %rdi ## literal pool for: "Enter Function: constrained-MLf. Shrinkage lambda is: 0. "
+	callq	0x133d0 ## symbol stub for: _puts
 	movl	-56(%rbp), %eax
 	testl	%eax, %eax
 	movq	-96(%rbp), %rsi
-	jle	0x70ad
+	jle	0x693c
 	cmpl	$4, %eax
-	jae	0x6fab
+	jae	0x6831
 	xorl	%ecx, %ecx
-	jmp	0x7081
+	jmp	0x6911
 	movl	%eax, %ecx
 	andl	$-4, %ecx
 	leaq	-4(%rcx), %rdx
 	movq	%rdx, %r8
 	shrq	$2, %r8
-	addq	$1, %r8
+	incq	%r8
 	testq	%rdx, %rdx
-	je	0x7b38
+	je	0x73c7
 	movq	%r8, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
 	xorl	%edx, %edx
 	xorpd	%xmm0, %xmm0
-	movapd	50896(%rip), %xmm1
+	movapd	52398(%rip), %xmm1
+	nopw	%cs:(%rax,%rax)
 	movupd	(%r12,%rdx,8), %xmm2
 	movupd	16(%r12,%rdx,8), %xmm3
 	cmpneqpd	%xmm0, %xmm2
 	andpd	%xmm1, %xmm2
 	cmpneqpd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movupd	%xmm2, (%rsi,%rdx,8)
@@ -4074,628 +4087,626 @@
 	cmpneqpd	%xmm0, %xmm2
 	andpd	%xmm1, %xmm2
 	cmpneqpd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movupd	%xmm2, 32(%rsi,%rdx,8)
 	movupd	%xmm3, 48(%rsi,%rdx,8)
 	addq	$8, %rdx
-	addq	$2, %rdi
-	jne	0x6fe0
+	addq	$-2, %rdi
+	jne	0x6870
 	testb	$1, %r8b
-	je	0x707c
+	je	0x690c
 	movupd	(%r12,%rdx,8), %xmm0
 	movupd	16(%r12,%rdx,8), %xmm1
 	xorpd	%xmm2, %xmm2
 	cmpneqpd	%xmm2, %xmm0
-	movapd	50764(%rip), %xmm3
+	movapd	52252(%rip), %xmm3
 	andpd	%xmm3, %xmm0
 	cmpneqpd	%xmm2, %xmm1
 	andpd	%xmm3, %xmm1
 	movupd	%xmm0, (%rsi,%rdx,8)
 	movupd	%xmm1, 16(%rsi,%rdx,8)
 	cmpq	%rax, %rcx
-	je	0x70ad
+	je	0x693c
 	xorpd	%xmm0, %xmm0
-	movsd	50595(%rip), %xmm1
+	movsd	52099(%rip), %xmm1
 	nopl	(%rax)
 	movsd	(%r12,%rcx,8), %xmm2
 	cmpeqsd	%xmm0, %xmm2
 	andnpd	%xmm1, %xmm2
 	movlpd	%xmm2, (%rsi,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %rax
-	jne	0x7090
+	jne	0x6920
 	cmpl	$0, 24(%rbp)
-	jle	0x70f5
+	jle	0x6984
 	xorl	%r13d, %r13d
 	leaq	24(%rbp), %rbx
 	leaq	-68(%rbp), %r14
 	movq	-96(%rbp), %r12
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movq	%rbx, %rdi
 	movq	%r12, %rsi
 	movq	%r14, %rdx
-	callq	0x134f6 ## symbol stub for: _dasum
+	callq	0x13370 ## symbol stub for: _dasum
 	movsd	%xmm0, (%r15,%r13,8)
-	addq	$1, %r13
+	incq	%r13
 	movslq	24(%rbp), %rax
 	addq	$8, %r12
 	cmpq	%rax, %r13
-	jl	0x70d0
-	movabsq	$4607182418800017408, %rax
-	movq	%rax, -200(%rbp)
+	jl	0x6960
 	movslq	16(%rbp), %rax
 	imulq	$1717986919, %rax, %rcx
 	movq	%rcx, %rax
 	shrq	$63, %rax
 	sarq	$33, %rcx
 	addl	%eax, %ecx
 	xorl	%eax, %eax
 	testl	%ecx, %ecx
 	cmovlel	%eax, %ecx
-	movq	%rcx, -272(%rbp)
+	movq	%rcx, -352(%rbp)
+	movabsq	$4607182418800017408, %rax
+	movq	%rax, -232(%rbp)
 	xorl	%r14d, %r14d
 	movq	%r15, %r12
 	movq	48(%rbp), %rbx
 	leaq	-52(%rbp), %r15
-	jmp	0x7171
-	nopl	(%rax)
-	movl	-152(%rbp), %r14d
-	addl	$1, %r14d
+	jmp	0x6a00
+	nopl	(%rax,%rax)
+	movl	-184(%rbp), %r14d
+	incl	%r14d
 	movl	24(%rbp), %edx
 	movq	80(%rbp), %rdi
 	movq	48(%rbp), %rbx
 	movq	%rbx, %rsi
 	callq	_UpdateIBinv
-	movsd	50450(%rip), %xmm0
+	movsd	51947(%rip), %xmm0
 	ucomisd	-128(%rbp), %xmm0
-	ja	0x792e
-	cmpl	-272(%rbp), %r14d
-	je	0x7924
-	movl	%r14d, -152(%rbp)
+	ja	0x71be
+	cmpl	-352(%rbp), %r14d
+	je	0x71b4
+	movl	%r14d, -184(%rbp)
 	leaq	-56(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%r15, %rdx
-	movq	-248(%rbp), %r14
+	movq	-264(%rbp), %r14
 	movq	%r14, %rcx
 	leaq	-48(%rbp), %r13
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-56(%rbp), %rax
 	leaq	(%r14,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
 	movq	56(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
 	movq	-96(%rbp), %rdx
-	jle	0x7830
+	jle	0x70c0
 	xorl	%r13d, %r13d
-	jmp	0x7275
-	nopw	(%rax,%rax)
+	jmp	0x6b04
+	nopw	%cs:(%rax,%rax)
 	movq	%r12, %r13
 	leaq	24(%rbp), %r12
 	movq	%r12, %rdi
-	movq	-352(%rbp), %rsi
+	movq	-136(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
 	movq	-280(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	imull	%r13d, %eax
 	cltq
-	movq	-192(%rbp), %rcx
+	movq	-224(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	movq	%r15, %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movq	-96(%rbp), %rdx
-	movq	-176(%rbp), %rsi
+	movq	-208(%rbp), %rsi
 	movsd	(%rsi,%r13,8), %xmm1
 	subsd	%xmm0, %xmm1
 	movq	56(%rbp), %rax
 	movsd	%xmm1, (%rax,%r13,8)
-	movq	-168(%rbp), %rax
+	movq	-200(%rbp), %rax
 	movq	$0, (%rax,%r13,8)
 	movl	24(%rbp), %eax
-	movq	-256(%rbp), %r12
-	addq	$1, %r13
+	movq	-272(%rbp), %r12
+	incq	%r13
 	movslq	%eax, %rcx
 	cmpq	%rcx, %r13
-	jge	0x7830
+	jge	0x70c0
 	movq	%r13, -88(%rbp)
 	movsd	(%r12,%r13,8), %xmm0
-	ucomisd	50169(%rip), %xmm0
-	jbe	0x7820
+	ucomisd	51666(%rip), %xmm0
+	jbe	0x70b0
 	cmpl	$7, 40(%rbp)
 	movq	-88(%rbp), %r12
-	jl	0x72af
-	leaq	51070(%rip), %rdi ## literal pool for: "\t\t updating gene %d \n"
+	jl	0x6b3e
+	leaq	52607(%rip), %rdi ## literal pool for: "\t\t updating gene %d \n"
 	movl	%r12d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	-96(%rbp), %rdx
 	movl	24(%rbp), %eax
-	movq	-168(%rbp), %rcx
+	movq	-200(%rbp), %rcx
 	movabsq	$4607182418800017408, %rsi
 	movq	%rsi, (%rcx,%r12,8)
 	leaq	(%rbx,%r12,8), %rcx
-	movq	%rcx, -352(%rbp)
+	movq	%rcx, -136(%rbp)
 	testl	%eax, %eax
-	jle	0x71e0
+	jle	0x6a70
 	movl	%eax, %ecx
 	imull	%r12d, %ecx
 	movslq	%ecx, %rcx
 	movq	80(%rbp), %rsi
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -136(%rbp)
-	movq	-320(%rbp), %rcx
+	movq	%rcx, -256(%rbp)
+	movq	-336(%rbp), %rcx
 	leaq	(%rcx,%r12,8), %rcx
-	movq	%rcx, -224(%rbp)
+	movq	%rcx, -496(%rbp)
 	movl	%r12d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -480(%rbp)
-	movq	-160(%rbp), %rsi
+	movq	%rcx, -144(%rbp)
+	movq	-192(%rbp), %rsi
 	xorl	%r13d, %r13d
-	jmp	0x75a2
+	jmp	0x6e34
 	nopw	%cs:(%rax,%rax)
-	nop
-	movsd	49912(%rip), %xmm0
-	movapd	%xmm0, %xmm1
+	movsd	51416(%rip), %xmm0
+	movapd	%xmm0, %xmm6
 	movapd	%xmm0, %xmm5
-	divsd	%xmm3, %xmm1
+	divsd	%xmm3, %xmm6
 	movl	24(%rbp), %eax
 	imull	%r13d, %eax
 	addl	%r12d, %eax
 	movslq	%eax, %r14
 	movq	48(%rbp), %rbx
-	addsd	(%rbx,%r14,8), %xmm1
-	movsd	-80(%rbp), %xmm0
+	addsd	(%rbx,%r14,8), %xmm6
+	movsd	-176(%rbp), %xmm0
 	movapd	%xmm0, %xmm3
-	movapd	%xmm0, %xmm6
-	mulsd	%xmm1, %xmm3
+	movapd	%xmm0, %xmm2
+	mulsd	%xmm6, %xmm3
 	addsd	%xmm4, %xmm3
-	movapd	%xmm4, %xmm0
-	cvtsi2sdl	32(%rbp), %xmm2
-	mulsd	%xmm1, %xmm0
-	movapd	%xmm1, %xmm4
-	movapd	%xmm1, -384(%rbp)
-	mulsd	-544(%rbp), %xmm2
-	movsd	%xmm2, -288(%rbp)
-	subsd	%xmm2, %xmm0
-	movapd	%xmm3, %xmm1
-	mulsd	%xmm3, %xmm1
-	movapd	%xmm6, %xmm2
-	mulsd	49847(%rip), %xmm2
-	mulsd	%xmm0, %xmm2
-	addsd	%xmm1, %xmm2
+	xorps	%xmm1, %xmm1
+	cvtsi2sdl	32(%rbp), %xmm1
+	mulsd	-552(%rbp), %xmm1
+	movsd	%xmm1, -152(%rbp)
 	movapd	%xmm6, %xmm0
-	addsd	%xmm6, %xmm0
-	movapd	%xmm5, %xmm1
-	divsd	%xmm0, %xmm1
-	xorps	%xmm0, %xmm0
-	sqrtsd	%xmm2, %xmm0
-	movapd	%xmm3, %xmm2
-	addsd	%xmm0, %xmm2
-	mulsd	%xmm1, %xmm2
-	movapd	%xmm2, -368(%rbp)
+	movapd	%xmm6, -384(%rbp)
+	mulsd	%xmm4, %xmm0
+	subsd	%xmm1, %xmm0
+	movapd	%xmm2, %xmm1
+	mulsd	51325(%rip), %xmm1
+	mulsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	mulsd	%xmm3, %xmm0
+	addsd	%xmm1, %xmm0
+	movapd	%xmm2, %xmm1
+	addsd	%xmm2, %xmm1
+	movapd	%xmm5, %xmm2
+	divsd	%xmm1, %xmm2
+	sqrtsd	%xmm0, %xmm0
+	movapd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	mulsd	%xmm2, %xmm1
+	movapd	%xmm1, -320(%rbp)
 	subsd	%xmm0, %xmm3
-	mulsd	%xmm1, %xmm3
-	movapd	%xmm3, -496(%rbp)
-	movapd	%xmm4, %xmm0
-	movapd	49824(%rip), %xmm1
+	mulsd	%xmm2, %xmm3
+	movapd	%xmm3, -400(%rbp)
+	movapd	%xmm6, %xmm0
+	movapd	51313(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	movsd	49732(%rip), %xmm1
+	movsd	51245(%rip), %xmm1
 	addsd	%xmm1, %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	mulsd	-288(%rbp), %xmm0
-	movapd	%xmm0, -400(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	mulsd	-152(%rbp), %xmm0
+	movapd	%xmm0, -512(%rbp)
 	movapd	-384(%rbp), %xmm0
-	subsd	-368(%rbp), %xmm0
-	andpd	49763(%rip), %xmm0
-	addsd	49675(%rip), %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	mulsd	-288(%rbp), %xmm0
-	movapd	-368(%rbp), %xmm3
+	subsd	-320(%rbp), %xmm0
+	andpd	51252(%rip), %xmm0
+	addsd	51188(%rip), %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-320(%rbp), %xmm3
 	movapd	%xmm3, %xmm1
 	mulsd	%xmm3, %xmm1
-	mulsd	-80(%rbp), %xmm1
-	movsd	49665(%rip), %xmm2
+	mulsd	-176(%rbp), %xmm1
+	movsd	51159(%rip), %xmm2
 	mulsd	%xmm2, %xmm1
-	subsd	%xmm1, %xmm0
-	movsd	-240(%rbp), %xmm1
+	mulsd	-152(%rbp), %xmm0
+	addsd	%xmm1, %xmm0
+	movsd	-80(%rbp), %xmm1
 	mulsd	%xmm3, %xmm1
 	addsd	%xmm0, %xmm1
 	movapd	%xmm1, %xmm2
-	movapd	-400(%rbp), %xmm0
+	movapd	-512(%rbp), %xmm0
 	maxsd	%xmm0, %xmm2
-	movapd	%xmm2, -464(%rbp)
+	movapd	%xmm2, -416(%rbp)
 	cmpltsd	%xmm1, %xmm0
 	andpd	%xmm3, %xmm0
-	movapd	%xmm0, -400(%rbp)
+	movapd	%xmm0, -512(%rbp)
 	movapd	-384(%rbp), %xmm0
-	subsd	-496(%rbp), %xmm0
-	andpd	49624(%rip), %xmm0
-	addsd	49536(%rip), %xmm0
-	callq	0x1353e ## symbol stub for: _log
+	subsd	-400(%rbp), %xmm0
+	andpd	51113(%rip), %xmm0
+	addsd	51049(%rip), %xmm0
+	callq	0x133b8 ## symbol stub for: _log
 	movapd	-128(%rbp), %xmm3
-	movsd	49486(%rip), %xmm2
-	mulsd	-288(%rbp), %xmm0
-	movapd	-496(%rbp), %xmm4
+	movsd	50991(%rip), %xmm2
+	movapd	-400(%rbp), %xmm4
 	movapd	%xmm4, %xmm1
 	mulsd	%xmm4, %xmm1
-	mulsd	-80(%rbp), %xmm1
-	mulsd	49513(%rip), %xmm1
-	subsd	%xmm1, %xmm0
-	movsd	-240(%rbp), %xmm1
-	mulsd	%xmm4, %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	-464(%rbp), %xmm0
-	cmpltsd	%xmm1, %xmm0
-	andpd	%xmm0, %xmm4
-	andnpd	-400(%rbp), %xmm0
-	orpd	%xmm4, %xmm0
+	mulsd	-176(%rbp), %xmm1
+	mulsd	51007(%rip), %xmm1
+	mulsd	-152(%rbp), %xmm0
+	addsd	%xmm1, %xmm0
+	movapd	%xmm4, %xmm1
+	movsd	-80(%rbp), %xmm4
+	mulsd	%xmm1, %xmm4
+	addsd	%xmm0, %xmm4
+	movapd	-416(%rbp), %xmm0
+	cmpltsd	%xmm4, %xmm0
+	andpd	%xmm0, %xmm1
+	andnpd	-512(%rbp), %xmm0
+	orpd	%xmm1, %xmm0
 	movlpd	%xmm0, (%rbx,%r14,8)
 	movapd	%xmm0, %xmm4
-	movsd	-432(%rbp), %xmm0
-	subsd	%xmm4, %xmm0
-	mulsd	%xmm0, %xmm3
-	addsd	%xmm2, %xmm3
+	movsd	-456(%rbp), %xmm1
+	subsd	%xmm4, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm2, %xmm1
 	movapd	%xmm2, %xmm0
-	divsd	%xmm3, %xmm0
-	movsd	%xmm0, -440(%rbp)
+	divsd	%xmm1, %xmm0
+	movsd	%xmm0, -472(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-440(%rbp), %rsi
-	movq	-136(%rbp), %rdx
+	leaq	-472(%rbp), %rsi
+	movq	-256(%rbp), %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	24(%rbp), %eax
 	movq	-96(%rbp), %rdx
-	movq	-144(%rbp), %rsi
-	addq	$1, %r13
+	movq	-464(%rbp), %rsi
+	incq	%r13
 	movslq	%eax, %rcx
 	addq	$8, %rsi
 	cmpq	%rcx, %r13
-	jge	0x71e0
+	jge	0x6a70
 	movl	%r13d, %ecx
 	imull	%eax, %ecx
 	addl	%r12d, %ecx
 	movslq	%ecx, %rcx
 	movsd	(%rdx,%rcx,8), %xmm0
-	ucomisd	49349(%rip), %xmm0
-	jbe	0x758e
-	movq	-480(%rbp), %rax
+	ucomisd	50843(%rip), %xmm0
+	jbe	0x6e21
+	movq	-144(%rbp), %rax
 	movsd	(%rax,%r13,8), %xmm0
 	movaps	%xmm0, -128(%rbp)
 	movsd	(%rbx,%rcx,8), %xmm0
-	movsd	%xmm0, -432(%rbp)
+	movsd	%xmm0, -456(%rbp)
 	leaq	32(%rbp), %rdi
-	movq	%rsi, -144(%rbp)
+	movq	%rsi, -464(%rbp)
 	leaq	24(%rbp), %r12
 	movq	%r12, %rdx
-	movq	-328(%rbp), %r14
+	movq	-360(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r12, %rdi
-	movq	-352(%rbp), %rsi
+	movq	-136(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
 	movq	-280(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, (%rbx,%r13,8)
 	movq	%r12, %rdi
-	movq	-168(%rbp), %rsi
+	movq	-200(%rbp), %rsi
 	movq	%r15, %rdx
-	movq	-416(%rbp), %r15
+	movq	-440(%rbp), %r15
 	movq	%r15, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
 	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
 	leaq	-52(%rbp), %rcx
 	movq	%r15, %r8
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	leaq	32(%rbp), %r12
 	movq	%r12, %rdi
-	movq	-224(%rbp), %rsi
+	movq	-496(%rbp), %rsi
 	leaq	24(%rbp), %rdx
-	movq	-424(%rbp), %rbx
+	movq	-448(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-52(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	56(%rbp), %rax
 	movq	-88(%rbp), %rcx
 	movsd	(%rax,%rcx,8), %xmm0
-	xorpd	49095(%rip), %xmm0
+	xorpd	50581(%rip), %xmm0
 	movlpd	%xmm0, -64(%rbp)
 	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
 	leaq	-52(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movb	$84, -41(%rbp)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
 	movq	%r12, %rdx
 	leaq	-64(%rbp), %rcx
-	movq	-160(%rbp), %r8
+	movq	-192(%rbp), %r8
 	leaq	-68(%rbp), %r9
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%rbx
-	leaq	-200(%rbp), %rax
+	leaq	-232(%rbp), %rax
 	pushq	%rax
 	leaq	-52(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
 	leaq	-52(%rbp), %r15
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	movq	%r15, %rdx
 	movq	%r14, %rcx
 	movq	%r15, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	%xmm0, -80(%rbp)
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	%xmm0, -176(%rbp)
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	movq	%r15, %rdx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movapd	-128(%rbp), %xmm3
 	movapd	%xmm0, %xmm4
 	movapd	%xmm3, %xmm0
-	andpd	48938(%rip), %xmm0
-	movsd	48834(%rip), %xmm1
+	andpd	50421(%rip), %xmm0
+	movsd	50333(%rip), %xmm1
 	ucomisd	%xmm0, %xmm1
-	jbe	0x77e0
+	jbe	0x7070
 	cmpl	$8, 40(%rbp)
 	movq	-88(%rbp), %r12
-	jl	0x77b7
-	leaq	49821(%rip), %rdi ## literal pool for: "\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
+	jl	0x7046
+	leaq	51352(%rip), %rdi ## literal pool for: "\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
 	movl	%r12d, %esi
 	movl	%r13d, %edx
 	xorl	%eax, %eax
-	movsd	%xmm4, -240(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-240(%rbp), %xmm4
+	movsd	%xmm4, -80(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-80(%rbp), %xmm4
 	movapd	-128(%rbp), %xmm3
-	divsd	-80(%rbp), %xmm4
+	divsd	-176(%rbp), %xmm4
 	movl	24(%rbp), %eax
 	imull	%r13d, %eax
 	addl	%r12d, %eax
 	cltq
 	movq	48(%rbp), %rbx
 	movsd	%xmm4, (%rbx,%rax,8)
-	movsd	48727(%rip), %xmm2
-	jmp	0x7542
-	nop
+	movsd	50229(%rip), %xmm2
+	jmp	0x6dd5
 	cmpl	$8, 40(%rbp)
 	movq	-88(%rbp), %r12
-	movsd	%xmm4, -240(%rbp)
-	jl	0x7330
-	leaq	49771(%rip), %rdi ## literal pool for: "\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
+	movsd	%xmm4, -80(%rbp)
+	jl	0x6bc0
+	leaq	51310(%rip), %rdi ## literal pool for: "\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
 	movl	%r12d, %esi
 	movl	%r13d, %edx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-240(%rbp), %xmm4
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-80(%rbp), %xmm4
 	movapd	-128(%rbp), %xmm3
-	jmp	0x7330
-	nopl	(%rax)
+	jmp	0x6bc0
+	nopw	%cs:(%rax,%rax)
 	movq	-88(%rbp), %r13
-	jmp	0x7265
+	jmp	0x6af5
 	nopl	(%rax)
 	leaq	-56(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%r15, %rdx
-	movq	-312(%rbp), %r14
+	movq	-328(%rbp), %r14
 	movq	%r14, %rcx
 	leaq	-48(%rbp), %rbx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-56(%rbp), %rax
 	leaq	(%r14,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
 	movq	56(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	leal	1(%rax), %ecx
 	imull	%eax, %ecx
 	movl	%ecx, -100(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-100(%rbp), %r13
 	movq	%r13, %rdi
-	movq	-248(%rbp), %r15
+	movq	-264(%rbp), %r15
 	movq	%r15, %rsi
 	leaq	-52(%rbp), %rdx
-	movq	-408(%rbp), %rbx
+	movq	-432(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r13, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r14, %rdx
 	leaq	-52(%rbp), %rcx
 	movq	%rbx, %r8
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r13, %rdi
 	movq	%r15, %rsi
 	leaq	-52(%rbp), %r15
 	movq	%r15, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	movsd	%xmm0, -128(%rbp)
 	movq	%r13, %rdi
 	movq	%rbx, %rsi
 	movq	%r15, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	movsd	-128(%rbp), %xmm1
-	addsd	48455(%rip), %xmm1
+	addsd	49959(%rip), %xmm1
 	divsd	%xmm1, %xmm0
 	movsd	%xmm0, -128(%rbp)
 	cmpl	$6, 40(%rbp)
-	jl	0x7140
-	leaq	49550(%rip), %rdi ## literal pool for: "\t\tdelta_BF: %f\n"
+	jl	0x69d0
+	leaq	51086(%rip), %rdi ## literal pool for: "\t\tdelta_BF: %f\n"
 	movsd	-128(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	jmp	0x7140
-	movq	-272(%rbp), %rax
+	callq	0x133c4 ## symbol stub for: _printf
+	jmp	0x69d0
+	movq	-352(%rbp), %rax
 	movl	%eax, %r14d
 	cmpl	$4, 40(%rbp)
-	jl	0x7945
-	leaq	49526(%rip), %rdi ## literal pool for: "\t number of iteration is: %d.\nExiting constrained_MLf\n"
+	jl	0x71d5
+	leaq	51062(%rip), %rdi ## literal pool for: "\t number of iteration is: %d.\nExiting constrained_MLf\n"
 	movl	%r14d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	leaq	-56(%rbp), %r14
 	leaq	-52(%rbp), %r15
 	leaq	-48(%rbp), %r8
 	movq	%r14, %rdi
 	movq	48(%rbp), %rsi
 	movq	%r15, %rdx
-	movq	-584(%rbp), %rbx
+	movq	-600(%rbp), %rbx
 	movq	%rbx, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-64(%rbp), %rsi
 	movq	%r14, %rdi
 	movq	%rbx, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
 	movq	64(%rbp), %r10
-	jle	0x79fa
+	jle	0x7289
 	leal	1(%rax), %edx
 	xorl	%ecx, %ecx
 	xorl	%esi, %esi
-	movq	-504(%rbp), %rdi
+	movq	-424(%rbp), %rdi
 	movq	56(%rbp), %r8
-	movsd	48257(%rip), %xmm1
-	movapd	48345(%rip), %xmm2
+	movsd	49761(%rip), %xmm1
+	movapd	49833(%rip), %xmm2
 	nopw	(%rax,%rax)
 	movslq	%ecx, %rcx
 	movsd	(%rbx,%rcx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%rbx,%rcx,8)
 	movsd	(%r8,%rsi,8), %xmm0
 	xorpd	%xmm2, %xmm0
 	mulsd	(%rdi,%rsi,8), %xmm0
 	movsd	%xmm0, (%r10,%rsi,8)
-	addq	$1, %rsi
+	incq	%rsi
 	addl	%edx, %ecx
 	cmpq	%rsi, %rax
-	jne	0x79c0
+	jne	0x7250
 	movl	%eax, %edx
 	notl	%edx
 	addl	%ecx, %edx
 	movl	%edx, -100(%rbp)
 	movb	$78, -41(%rbp)
 	movabsq	$4607182418800017408, %rcx
 	movq	%rcx, -64(%rbp)
-	movl	%eax, -448(%rbp)
+	movl	%eax, -480(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
-	leaq	-448(%rbp), %rdx
+	leaq	-480(%rbp), %rdx
 	leaq	-64(%rbp), %rcx
 	leaq	-68(%rbp), %r9
 	movq	%rbx, %r8
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%r10
-	leaq	-200(%rbp), %rax
+	leaq	-232(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
 	movq	%rbx, %r14
-	movq	-512(%rbp), %rbx
+	movq	-520(%rbp), %rbx
 	pushq	%rbx
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-504(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-160(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-320(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-424(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-192(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-336(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-96(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-520(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-328(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-208(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-224(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-528(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-360(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-200(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-424(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-416(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-448(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-440(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-280(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-248(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-408(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movsd	-184(%rbp), %xmm0
-	addq	$568, %rsp
+	callq	0x133ac ## symbol stub for: _free
+	movq	-264(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-328(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-432(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movsd	-216(%rbp), %xmm0
+	addq	$584, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
 	xorl	%edx, %edx
 	testb	$1, %r8b
-	jne	0x7046
-	jmp	0x707c
+	jne	0x68d6
+	jmp	0x690c
+	nop
 	nop
 	nop
 	nop
 	nop
 	nop
 	nop
 	nop
@@ -4722,52 +4733,52 @@
 	movl	%eax, -100(%rbp)
 	imull	%r12d, %ecx
 	movl	%ecx, -176(%rbp)
 	movl	%ecx, -144(%rbp)
 	movslq	%eax, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -344(%rbp)
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -112(%rbp)
 	movslq	%r12d, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -120(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
 	movq	%rbx, -88(%rbp)
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -192(%rbp)
 	movl	$8, %esi
 	movq	%r13, -80(%rbp)
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -360(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -296(%rbp)
 	movl	24(%rbp), %ecx
 	movl	%ecx, %eax
 	cltd
 	movl	%r14d, %r13d
 	idivl	%r14d
 	movl	%eax, %r14d
 	movl	%eax, -56(%rbp)
 	movl	%ecx, %ebx
 	subl	%eax, %ebx
 	movslq	%r15d, %rdi
 	movl	$8, %esi
 	movq	%rdi, -376(%rbp)
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -328(%rbp)
 	movl	%r15d, -232(%rbp)
 	movl	%r15d, %eax
 	imull	%r13d, %eax
 	movl	%r13d, %r15d
 	movl	%r12d, %r13d
 	movl	%eax, -44(%rbp)
@@ -4776,138 +4787,137 @@
 	imull	%r12d, %eax
 	movl	%eax, -364(%rbp)
 	imull	%r12d, %r14d
 	movl	%r14d, -140(%rbp)
 	movslq	%eax, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -216(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -160(%rbp)
 	movslq	%r14d, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -264(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -256(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -312(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -304(%rbp)
 	movl	$8, %esi
 	movq	-88(%rbp), %rbx
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -392(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
 	movl	48(%rbp), %r14d
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -384(%rbp)
 	movabsq	$4681608360884174848, %rax
 	movq	%rax, -128(%rbp)
 	cmpl	$1, %r14d
 	movl	%r15d, -72(%rbp)
-	jle	0x7db5
+	jle	0x7645
 	movl	%r15d, %edx
-	leaq	48594(%rip), %rdi ## literal pool for: "\t\tEnter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n"
+	leaq	50130(%rip), %rdi ## literal pool for: "\t\tEnter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n"
 	movl	$0, -224(%rbp)
 	movl	-232(%rbp), %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
 	movl	$0, -136(%rbp)
 	cmpl	$5, %r14d
-	jl	0x7dd7
-	leaq	48607(%rip), %rdi ## literal pool for: "\n\t\t\t\t\tEnter Function: ridge_cvf. %d-fold cross validation.\n"
+	jb	0x7667
+	leaq	50143(%rip), %rdi ## literal pool for: "\n\t\t\t\t\tEnter Function: ridge_cvf. %d-fold cross validation.\n"
 	movl	-72(%rbp), %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movb	$1, %al
 	movl	%eax, -224(%rbp)
-	jmp	0x7dd7
+	jmp	0x7667
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
 	movl	$0, -136(%rbp)
 	movl	$0, -224(%rbp)
 	movl	$0, -92(%rbp)
 	movslq	-176(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -176(%rbp)
 	movl	$8, %esi
 	movq	-80(%rbp), %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -208(%rbp)
 	movb	$78, -66(%rbp)
 	movb	$78, -65(%rbp)
 	movl	%r13d, -284(%rbp)
 	movl	%r13d, -280(%rbp)
 	movl	%r13d, -276(%rbp)
 	movl	%r13d, -132(%rbp)
 	cmpl	$0, 40(%rbp)
 	movq	-192(%rbp), %r14
-	jle	0x843b
-	movsd	47080(%rip), %xmm0
-	movsd	47216(%rip), %xmm1
+	jle	0x7cb9
+	movsd	48584(%rip), %xmm0
+	movsd	48704(%rip), %xmm1
 	movsd	%xmm0, -80(%rbp)
 	xorl	%esi, %esi
 	movq	-120(%rbp), %r9
 	movl	-72(%rbp), %r15d
-	jmp	0x7e79
+	jmp	0x7709
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	cmpl	40(%rbp), %esi
-	jge	0x8459
+	jge	0x7cd7
 	movsd	%xmm1, -248(%rbp)
 	movslq	%esi, %rax
 	movq	-184(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
 	movsd	%xmm0, -168(%rbp)
 	movq	$0, -128(%rbp)
 	testl	%r15d, %r15d
-	jle	0x83e0
+	jle	0x7c60
 	xorl	%ebx, %ebx
-	jmp	0x7ee6
+	jmp	0x7776
 	nopl	(%rax)
 	leaq	-140(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%r12, %rdx
 	movq	%rbx, %rcx
 	movq	%r13, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movapd	%xmm0, %xmm1
 	addsd	-128(%rbp), %xmm1
 	movsd	%xmm1, -128(%rbp)
 	movl	-72(%rbp), %r15d
 	movl	-88(%rbp), %ebx
 	cmpl	%r15d, %ebx
-	je	0x83d0
+	je	0x7c50
 	movl	48(%rbp), %eax
 	cmpl	$7, %eax
-	jl	0x7efe
-	leaq	48327(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t crossValidation %d/Kcv\n\n"
+	jl	0x778e
+	leaq	49863(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t crossValidation %d/Kcv\n\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %edx
 	movl	%edx, %r13d
 	imull	%ebx, %r13d
-	addl	$1, %ebx
+	incl	%ebx
 	movl	%edx, %r14d
 	movl	%ebx, -88(%rbp)
 	imull	%ebx, %r14d
 	movl	16(%rbp), %eax
 	movl	%r13d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
@@ -4918,30 +4928,30 @@
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %r15
 	movq	%r15, %rdi
 	leaq	-52(%rbp), %r12
 	movq	%r12, %rdx
 	movq	-256(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r13d, %r13d
 	movl	%r14d, -80(%rbp)
-	je	0x7fe0
+	je	0x7860
 	movl	16(%rbp), %eax
 	imull	%r13d, %eax
 	movl	%eax, -44(%rbp)
 	movq	%r15, %rdi
 	movq	%rbx, %rsi
 	movq	%r12, %rdx
 	movq	-160(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %r14d
 	movl	-152(%rbp), %ebx
-	je	0x8015
+	je	0x7895
 	movl	24(%rbp), %eax
 	movl	-80(%rbp), %edx
 	subl	%edx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -96(%rbp)
 	imull	%edx, %ecx
@@ -4950,60 +4960,59 @@
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	movq	-160(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	leaq	-96(%rbp), %rdi
 	movq	%r12, %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	jmp	0x8015
-	nopl	(%rax)
+	callq	0x1337c ## symbol stub for: _dcopy
+	jmp	0x7895
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%r14d, %ecx
 	imull	%eax, %ecx
 	imull	%r14d, %eax
 	cltq
 	leaq	(%rbx,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%r15, %rdi
 	movq	%r12, %rdx
 	movq	-160(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-152(%rbp), %ebx
 	movl	16(%rbp), %eax
 	imull	%eax, %ebx
 	imull	%r13d, %eax
 	cltq
 	movq	-240(%rbp), %r14
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ebx, -44(%rbp)
 	movq	%r15, %rdi
 	movq	%r12, %rdx
 	movq	-264(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r13d, %r13d
-	je	0x80d0
+	je	0x7950
 	imull	16(%rbp), %r13d
 	movl	%r13d, -44(%rbp)
 	movq	%r15, %rdi
 	movq	%r14, %rsi
 	movq	%r12, %rdx
 	movq	-216(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-80(%rbp), %edx
 	cmpl	24(%rbp), %edx
 	movq	-112(%rbp), %r14
 	movq	-120(%rbp), %r9
 	leaq	-56(%rbp), %r15
-	je	0x8112
+	je	0x7992
 	movl	24(%rbp), %eax
 	subl	%edx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -96(%rbp)
 	imull	%edx, %ecx
 	movslq	%ecx, %rax
@@ -5011,17 +5020,17 @@
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	leaq	(%rbx,%rax,8), %rcx
 	leaq	-96(%rbp), %rdi
 	movq	%r12, %rdx
 	leaq	-48(%rbp), %r8
 	movq	%r9, %r13
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r13, %r9
-	jmp	0x8112
+	jmp	0x7992
 	nopw	(%rax,%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	movq	%r15, %rdi
 	movl	-80(%rbp), %r15d
 	subl	%r15d, %ecx
 	imull	%eax, %ecx
@@ -5029,15 +5038,15 @@
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%r12, %rdx
 	movq	-216(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	-112(%rbp), %r14
 	movq	-120(%rbp), %r9
 	leaq	-56(%rbp), %r15
 	movl	16(%rbp), %edx
 	movq	%rbx, %rdi
 	movq	-160(%rbp), %rsi
 	movsd	-168(%rbp), %xmm0
@@ -5054,65 +5063,63 @@
 	leaq	-100(%rbp), %r14
 	movq	%r14, %rdi
 	movq	%rbx, %rsi
 	movq	%r12, %rdx
 	movq	-208(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	movq	%r14, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
 	movq	%r12, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	16(%rbp), %r8d
 	testl	%r8d, %r8d
-	jle	0x81c0
+	jle	0x7a40
 	cmpl	$1, %r8d
-	jne	0x81e0
+	jne	0x7a60
 	xorl	%ecx, %ecx
 	movq	-208(%rbp), %rsi
-	movsd	46209(%rip), %xmm1
-	jmp	0x8240
+	movsd	47729(%rip), %xmm1
+	jmp	0x7ac0
 	nopw	%cs:(%rax,%rax)
-	nop
 	xorl	%r8d, %r8d
 	movabsq	$4607182418800017408, %rax
 	leaq	16(%rbp), %rdx
-	jmp	0x826c
+	jmp	0x7aec
 	nopw	%cs:(%rax,%rax)
 	movl	%r8d, %edx
 	andl	$-2, %edx
 	leal	1(%r8), %r9d
 	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
 	movq	-208(%rbp), %rsi
-	movsd	46124(%rip), %xmm1
+	movsd	47644(%rip), %xmm1
 	nopw	%cs:(%rax,%rax)
-	nop
 	movslq	%ebx, %rbx
 	movsd	(%rsi,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%rsi,%rbx,8)
 	leal	(%r9,%rbx), %eax
 	cltq
 	movsd	(%rsi,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%rsi,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
 	cmpq	%rcx, %rdx
-	jne	0x8210
+	jne	0x7a90
 	testb	$1, %r8b
 	leaq	16(%rbp), %rdx
-	je	0x8262
+	je	0x7ae2
 	movl	%r8d, %eax
 	imull	%ecx, %eax
 	addl	%ecx, %eax
 	cltq
 	movsd	(%rsi,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%rsi,%rax,8)
@@ -5135,317 +5142,313 @@
 	pushq	%rax
 	leaq	-280(%rbp), %rax
 	pushq	%rax
 	pushq	-264(%rbp)
 	leaq	-284(%rbp), %rax
 	pushq	%rax
 	pushq	-208(%rbp)
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	$0, -44(%rbp)
 	cmpl	$0, 16(%rbp)
-	movapd	45988(%rip), %xmm1
+	movapd	47492(%rip), %xmm1
 	movq	-120(%rbp), %r13
 	movq	%r15, %r12
 	movq	-256(%rbp), %r15
-	jle	0x8343
+	jle	0x7bc2
 	xorl	%eax, %eax
 	nop
 	cltq
 	leaq	(%r15,%rax,8), %rdx
 	leaq	(%rbx,%rax,8), %r8
 	movsd	(%r13,%rax,8), %xmm0
 	xorpd	%xmm1, %xmm0
 	movlpd	%xmm0, -64(%rbp)
 	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r14, %rcx
 	leaq	16(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	movapd	45915(%rip), %xmm1
+	callq	0x13376 ## symbol stub for: _daxpy
+	movapd	47419(%rip), %xmm1
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	16(%rbp), %eax
-	jl	0x8300
+	jl	0x7b80
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	movl	$0, -44(%rbp)
 	cmpl	$0, -56(%rbp)
 	leaq	16(%rbp), %r15
 	leaq	-52(%rbp), %r12
 	leaq	-48(%rbp), %r13
 	movq	-192(%rbp), %r14
-	jle	0x7eb0
+	jle	0x7740
 	movq	%r15, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r12, %rcx
 	movq	%rbx, %r8
 	nopw	%cs:(%rax,%rax)
-	nop
 	movq	%r13, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	-56(%rbp), %eax
-	jge	0x7eb0
+	jge	0x7740
 	imull	16(%rbp), %eax
 	cltq
 	leaq	(%rbx,%rax,8), %r8
 	movq	%r15, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r12, %rcx
-	jmp	0x8390
+	jmp	0x7c10
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movl	-92(%rbp), %esi
 	movq	-120(%rbp), %r9
-	jmp	0x83e4
+	jmp	0x7c64
 	nopl	(%rax)
 	xorpd	%xmm1, %xmm1
-	addl	$1, %esi
+	incl	%esi
 	movl	%esi, -92(%rbp)
 	movl	48(%rbp), %eax
 	cmpl	$6, %eax
-	jl	0x841c
-	leaq	47076(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t Test rho ratio %f; (%d/Nrho)\t error: %f.\n"
+	jl	0x7c9b
+	leaq	48629(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t Test rho ratio %f; (%d/Nrho)\t error: %f.\n"
 	movsd	-168(%rbp), %xmm0
 	movb	$2, %al
 	movq	%r14, %rbx
 	movq	%r9, %r14
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	%r14, %r9
 	movq	%rbx, %r14
 	movl	-92(%rbp), %esi
 	movsd	-128(%rbp), %xmm1
 	cmpl	$2, %esi
-	jl	0x7e70
+	jl	0x7700
 	ucomisd	-248(%rbp), %xmm1
-	jb	0x7e70
-	addl	$-1, %esi
+	jb	0x7700
+	decl	%esi
 	movl	%esi, -92(%rbp)
-	jmp	0x8459
+	jmp	0x7cd7
 	xorps	%xmm0, %xmm0
 	movsd	%xmm0, -248(%rbp)
-	movsd	45538(%rip), %xmm0
+	movsd	47060(%rip), %xmm0
 	movsd	%xmm0, -80(%rbp)
 	xorl	%esi, %esi
 	movq	-120(%rbp), %r9
 	movl	-224(%rbp), %ebx
 	testb	%bl, %bl
-	je	0x8485
-	leaq	47012(%rip), %rdi ## literal pool for: "\t\t\t\t\tExit RidgeCV. sigma2R: %f\t"
+	je	0x7d03
+	leaq	48566(%rip), %rdi ## literal pool for: "\t\t\t\t\tExit RidgeCV. sigma2R: %f\t"
 	movsd	-80(%rbp), %xmm0
 	movb	$1, %al
 	movq	%r14, %r15
 	movq	%r9, %r14
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	%r14, %r9
 	movq	%r15, %r14
 	movl	-92(%rbp), %esi
 	movsd	-128(%rbp), %xmm1
 	movapd	%xmm1, %xmm0
 	cmpl	$1, %esi
-	je	0x849b
+	je	0x7d19
 	movsd	-248(%rbp), %xmm0
 	movl	-144(%rbp), %eax
 	cmpl	40(%rbp), %esi
-	je	0x84aa
+	je	0x7d28
 	movapd	%xmm0, %xmm1
-	addl	$-1, %eax
+	decl	%eax
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
-	addl	$-1, %esi
+	decl	%esi
 	movslq	%esi, %rax
 	movl	24(%rbp), %ecx
 	cvtsi2sd	%ecx, %xmm2
 	movq	-184(%rbp), %rdx
 	mulsd	(%rdx,%rax,8), %xmm2
 	movl	%ecx, %eax
 	subl	-56(%rbp), %eax
 	divsd	%xmm0, %xmm1
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
 	testb	%bl, %bl
 	movsd	%xmm1, -80(%rbp)
-	je	0x8518
-	leaq	46913(%rip), %rdi ## literal pool for: "sigma2learnt: %f\n"
+	je	0x7d94
+	leaq	48469(%rip), %rdi ## literal pool for: "sigma2learnt: %f\n"
 	movsd	%xmm0, -152(%rbp)
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
 	movq	%r9, %rbx
 	movsd	%xmm2, -88(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-152(%rbp), %xmm0
 	movsd	-88(%rbp), %xmm2
 	movq	%rbx, %r9
 	divsd	%xmm0, %xmm2
 	movl	48(%rbp), %r13d
 	movq	%r13, %rax
 	testl	%eax, %eax
 	movq	-240(%rbp), %rbx
-	je	0x8559
+	je	0x7dd5
 	movl	16(%rbp), %edx
 	movq	%rbx, %rdi
 	movq	-200(%rbp), %rsi
 	movapd	%xmm2, %xmm0
 	movl	24(%rbp), %ecx
 	movq	-112(%rbp), %r8
 	pushq	%rax
 	pushq	%r14
 	callq	_constrained_ridge_cff
 	movsd	-80(%rbp), %xmm5
 	addq	$16, %rsp
-	jmp	0x85ba
-	leaq	46816(%rip), %rdi ## literal pool for: "Step 2: ridge CV; find rho : %f\n"
+	jmp	0x7e36
+	leaq	48372(%rip), %rdi ## literal pool for: "Step 2: ridge CV; find rho : %f\n"
 	movapd	%xmm2, %xmm0
 	movb	$1, %al
 	movq	%r14, %r15
 	movq	%r9, %r14
 	movsd	%xmm2, -88(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	16(%rbp), %edx
 	movq	%rbx, %rdi
 	movq	-200(%rbp), %rsi
 	movsd	-88(%rbp), %xmm0
 	movl	24(%rbp), %ecx
 	movq	-112(%rbp), %r8
 	movq	%r14, %r9
 	pushq	$0
 	pushq	%r15
 	callq	_constrained_ridge_cff
 	addq	$16, %rsp
 	movsd	%xmm0, -88(%rbp)
-	leaq	47387(%rip), %rdi ## literal pool for: "Step 3: ridge; calculate weights."
-	callq	0x13556 ## symbol stub for: _puts
+	leaq	49317(%rip), %rdi ## literal pool for: "Step 3: ridge; calculate weights."
+	callq	0x133d0 ## symbol stub for: _puts
 	movsd	-80(%rbp), %xmm5
 	movsd	-88(%rbp), %xmm0
 	movl	-72(%rbp), %r15d
 	movsd	%xmm0, -88(%rbp)
 	movq	64(%rbp), %r8
 	movl	-100(%rbp), %ebx
 	testl	%ebx, %ebx
-	jle	0x85de
+	jle	0x7e5a
 	cmpl	$1, %ebx
-	jne	0x85e5
+	jne	0x7e61
 	xorl	%ecx, %ecx
-	movq	-112(%rbp), %rdx
-	jmp	0x86a7
-	xorl	%eax, %eax
-	jmp	0x86f5
+	movq	-112(%rbp), %rsi
+	jmp	0x7f27
+	xorl	%edx, %edx
+	jmp	0x7f74
 	movl	%ebx, %ecx
 	andl	$-2, %ecx
-	leaq	-2(%rcx), %rsi
-	movq	%rsi, %r9
+	leaq	-2(%rcx), %rdx
+	movq	%rdx, %r9
 	shrq	%r9
-	addq	$1, %r9
-	testq	%rsi, %rsi
-	movq	-112(%rbp), %rdx
-	je	0x942c
+	incq	%r9
+	testq	%rdx, %rdx
+	movq	-112(%rbp), %rsi
+	je	0x8caa
 	movq	%r9, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
-	xorl	%esi, %esi
-	movapd	45271(%rip), %xmm0
-	movapd	45183(%rip), %xmm1
-	movapd	45191(%rip), %xmm2
+	xorl	%edx, %edx
+	movapd	46799(%rip), %xmm0
+	movapd	46695(%rip), %xmm1
+	movapd	46703(%rip), %xmm2
 	movq	56(%rbp), %rax
-	nopl	(%rax)
-	movupd	(%rdx,%rsi,8), %xmm3
+	nopw	%cs:(%rax,%rax)
+	movupd	(%rsi,%rdx,8), %xmm3
 	addpd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divpd	%xmm3, %xmm4
-	movupd	%xmm4, (%rax,%rsi,8)
-	movupd	16(%rdx,%rsi,8), %xmm3
+	movupd	%xmm4, (%rax,%rdx,8)
+	movupd	16(%rsi,%rdx,8), %xmm3
 	addpd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divpd	%xmm3, %xmm4
-	movupd	%xmm4, 16(%rax,%rsi,8)
-	addq	$4, %rsi
-	addq	$2, %rdi
-	jne	0x8630
+	movupd	%xmm4, 16(%rax,%rdx,8)
+	addq	$4, %rdx
+	addq	$-2, %rdi
+	jne	0x7eb0
 	testb	$1, %r9b
-	je	0x86a0
-	movupd	(%rdx,%rsi,8), %xmm0
-	addpd	45165(%rip), %xmm0
-	andpd	45077(%rip), %xmm0
-	movapd	45085(%rip), %xmm1
+	je	0x7f20
+	movupd	(%rsi,%rdx,8), %xmm0
+	addpd	46685(%rip), %xmm0
+	andpd	46581(%rip), %xmm0
+	movapd	46589(%rip), %xmm1
 	divpd	%xmm0, %xmm1
 	movq	56(%rbp), %rax
-	movupd	%xmm1, (%rax,%rsi,8)
-	movl	%ebx, %eax
+	movupd	%xmm1, (%rax,%rdx,8)
+	movl	%ebx, %edx
 	cmpq	%rbx, %rcx
-	je	0x86f5
-	movsd	44945(%rip), %xmm0
-	movapd	45033(%rip), %xmm1
-	movsd	44913(%rip), %xmm2
+	je	0x7f74
+	movsd	46465(%rip), %xmm0
+	movapd	46537(%rip), %xmm1
+	movsd	46433(%rip), %xmm2
 	movq	56(%rbp), %rax
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	movsd	(%rdx,%rcx,8), %xmm3
+	movsd	(%rsi,%rcx,8), %xmm3
 	addsd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divsd	%xmm3, %xmm4
 	movsd	%xmm4, (%rax,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %rbx
-	jne	0x86d0
-	movl	%ebx, %eax
-	movl	%eax, -44(%rbp)
+	jne	0x7f50
+	movl	%ebx, %edx
+	movl	%edx, -44(%rbp)
 	movsd	%xmm5, (%r8)
 	movl	%ebx, %eax
 	imull	%r15d, %eax
 	movl	%eax, -92(%rbp)
 	movslq	%eax, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -184(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -352(%rbp)
 	movslq	%r15d, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -336(%rbp)
 	movq	$0, -272(%rbp)
 	testl	%r15d, %r15d
-	jle	0x886b
+	jle	0x80e9
 	xorl	%r14d, %r14d
 	leaq	-100(%rbp), %r12
+	nop
 	imull	%r14d, %ebx
 	movslq	%ebx, %rax
 	movq	-184(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r13
 	movq	%r12, %rdi
 	leaq	-272(%rbp), %rsi
 	leaq	-136(%rbp), %rdx
 	movq	%r13, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %r8d
 	movl	$0, %eax
 	testl	%r8d, %r8d
-	jle	0x8853
+	jle	0x80d2
 	leaq	-1(%r8), %rax
 	movl	%r8d, %ecx
 	andl	$3, %ecx
 	cmpq	$3, %rax
-	jae	0x87c0
+	jae	0x8040
 	xorl	%edx, %edx
-	jmp	0x8827
+	jmp	0x80a7
 	nopw	%cs:(%rax,%rax)
-	nop
 	movl	%r8d, %r10d
 	andl	$-4, %r10d
 	leal	(%r8,%r8), %r9d
 	addl	$2, %r9d
 	leal	4(,%r8,4), %r11d
 	leal	1(%r8), %r15d
 	leal	(%r8,%r8,2), %edi
@@ -5463,77 +5466,77 @@
 	movq	%rax, (%r13,%rbx,8)
 	leal	(%rdi,%rsi), %ebx
 	movslq	%ebx, %rbx
 	movq	%rax, (%r13,%rbx,8)
 	addq	$4, %rdx
 	addl	%r11d, %esi
 	cmpq	%rdx, %r10
-	jne	0x87f0
+	jne	0x8070
 	testq	%rcx, %rcx
-	je	0x8850
+	je	0x80cf
 	leal	1(%r8), %eax
 	imull	%eax, %edx
 	movabsq	$4607182418800017408, %rsi
 	nopl	(%rax)
 	movslq	%edx, %rdx
 	movq	%rsi, (%r13,%rdx,8)
 	addl	%eax, %edx
-	addq	$-1, %rcx
-	jne	0x8840
+	decq	%rcx
+	jne	0x80c0
 	movl	%r8d, %eax
 	movl	%eax, -44(%rbp)
-	addl	$1, %r14d
+	incl	%r14d
 	movl	-72(%rbp), %r15d
 	cmpl	%r15d, %r14d
-	je	0x886b
+	je	0x80e9
 	movl	-100(%rbp), %ebx
-	jmp	0x8760
+	jmp	0x7fe0
 	leaq	-92(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
 	movq	-184(%rbp), %rsi
 	movq	-352(%rbp), %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$0, -232(%rbp)
 	movl	48(%rbp), %r12d
 	movq	-176(%rbp), %r14
-	jle	0x927b
+	jle	0x8af9
 	movl	%r15d, %eax
 	movq	%rax, -400(%rbp)
-	movsd	44412(%rip), %xmm0
+	movsd	45934(%rip), %xmm0
 	leaq	-48(%rbp), %r13
 	movsd	%xmm0, -232(%rbp)
 	xorl	%eax, %eax
 	movq	%rax, -168(%rbp)
-	jmp	0x88f9
-	nopl	(%rax,%rax)
+	jmp	0x8178
+	nopl	(%rax)
 	movq	-168(%rbp), %rcx
-	addq	$1, %rcx
+	incq	%rcx
 	movq	%rcx, %rax
 	movq	%rcx, -168(%rbp)
 	cmpq	-376(%rbp), %rcx
 	movq	%r13, %r14
 	leaq	-48(%rbp), %r13
-	jge	0x927b
+	jge	0x8af9
 	movq	$0, -128(%rbp)
 	testl	%r15d, %r15d
-	jle	0x90a0
+	jle	0x8920
 	xorl	%ebx, %ebx
-	jmp	0x8927
-	nop
+	jmp	0x81a7
+	nopl	(%rax)
 	movq	-248(%rbp), %rax
 	movq	%rax, %rbx
 	cmpq	-400(%rbp), %rax
-	je	0x9080
+	je	0x8900
 	cmpl	$4, %r12d
-	jl	0x893d
-	leaq	45869(%rip), %rdi ## literal pool for: "\t\t %d/Kcv cross validation.\n"
+	jl	0x81bd
+	leaq	47421(%rip), %rdi ## literal pool for: "\t\t %d/Kcv cross validation.\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %r15d
 	movl	%r15d, %r12d
 	imull	%ebx, %r12d
 	movq	%rbx, -80(%rbp)
 	leaq	1(%rbx), %rax
 	movq	%rax, -248(%rbp)
 	movl	%eax, %ebx
@@ -5546,30 +5549,30 @@
 	leaq	(%r14,%rcx,8), %rsi
 	imull	%r15d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	movq	-256(%rbp), %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r12d, %r12d
 	movl	%ebx, -152(%rbp)
-	je	0x8a20
+	je	0x82a0
 	movl	16(%rbp), %eax
 	imull	%r12d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	movq	%r14, %rsi
 	leaq	-52(%rbp), %rdx
 	movq	-160(%rbp), %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %ebx
 	movq	-240(%rbp), %r14
-	je	0x8a55
+	je	0x82d5
 	movl	24(%rbp), %eax
 	movl	-152(%rbp), %edx
 	subl	%edx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -96(%rbp)
 	imull	%edx, %ecx
@@ -5578,140 +5581,139 @@
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	movq	-160(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	leaq	-96(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	jmp	0x8a55
+	callq	0x1337c ## symbol stub for: _dcopy
+	jmp	0x82d5
 	nopl	(%rax,%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%ebx, %ecx
 	imull	%eax, %ecx
 	imull	%ebx, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	movq	-160(%rbp), %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	-240(%rbp), %r14
 	movl	16(%rbp), %eax
 	imull	%eax, %r15d
 	imull	%r12d, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%r15d, -44(%rbp)
 	leaq	-44(%rbp), %rbx
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %r15
 	movq	%r15, %rdx
 	movq	-264(%rbp), %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r12d, %r12d
-	je	0x8af0
+	je	0x8370
 	imull	16(%rbp), %r12d
 	movl	%r12d, -44(%rbp)
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	%r15, %rdx
 	movq	-216(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-152(%rbp), %edx
 	cmpl	24(%rbp), %edx
-	je	0x8b25
+	je	0x83a5
 	movl	24(%rbp), %eax
 	subl	%edx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -96(%rbp)
 	imull	%edx, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r14,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	leaq	(%rbx,%rax,8), %rcx
 	leaq	-96(%rbp), %rdi
 	movq	%r15, %rdx
-	jmp	0x8b1d
+	jmp	0x839d
 	nopw	%cs:(%rax,%rax)
-	nop
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	movl	-152(%rbp), %edx
 	subl	%edx, %ecx
 	imull	%eax, %ecx
 	imull	%edx, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%rbx, %rdi
 	movq	%r15, %rdx
 	movq	-216(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	-364(%rbp), %r12
 	movq	%r12, %rdi
 	movq	-160(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	-304(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r12, %rdi
 	movq	%rbx, %rsi
 	movq	%r15, %rdx
 	movq	-312(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %r8d
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	-392(%rbp), %rdx
 	movq	-384(%rbp), %rcx
 	movq	-320(%rbp), %r15
 	movl	%r15d, %r9d
 	callq	_centerYX
 	cmpq	$0, -168(%rbp)
-	je	0x8bd0
+	je	0x8450
 	movq	-336(%rbp), %rax
 	movq	-80(%rbp), %rdi
 	movsd	(%rax,%rdi,8), %xmm3
 	movq	-112(%rbp), %rsi
 	movq	-120(%rbp), %rdx
 	movq	-296(%rbp), %r10
 	movsd	-88(%rbp), %xmm2
 	movq	56(%rbp), %rbx
 	movq	-344(%rbp), %r15
-	jmp	0x8c82
+	jmp	0x8502
 	nopl	(%rax,%rax)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
 	leaq	16(%rbp), %rdi
 	leaq	-64(%rbp), %rsi
 	leaq	-136(%rbp), %r15
 	movq	%r15, %rdx
 	movq	-120(%rbp), %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, -64(%rbp)
 	leaq	-100(%rbp), %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	-112(%rbp), %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %ecx
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	-344(%rbp), %r15
 	movq	%r15, %rdx
 	movsd	-88(%rbp), %xmm0
 	movq	-320(%rbp), %r12
@@ -5760,32 +5762,32 @@
 	movq	-320(%rbp), %rbx
 	pushq	%rbx
 	pushq	%r11
 	pushq	-416(%rbp)
 	callq	_Weighted_LassoSf_MLf
 	addq	$80, %rsp
 	cmpl	$4, %r12d
-	jl	0x8d60
-	leaq	44898(%rip), %rdi ## literal pool for: "\t\t\t step 1 SML lasso regression, lambda: %f.\n"
+	jl	0x85e0
+	leaq	46450(%rip), %rdi ## literal pool for: "\t\t\t step 1 SML lasso regression, lambda: %f.\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	16(%rbp), %r9d
 	movq	-312(%rbp), %rdi
 	movq	-304(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	-112(%rbp), %rcx
 	movq	-120(%rbp), %r8
 	movsd	-88(%rbp), %xmm0
 	pushq	%r14
 	pushq	%rbx
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	leaq	45456(%rip), %rdi ## literal pool for: "\t\t\t step 2 SML ZeroRegression."
-	callq	0x13556 ## symbol stub for: _puts
-	jmp	0x8d8e
+	leaq	47382(%rip), %rdi ## literal pool for: "\t\t\t step 2 SML ZeroRegression."
+	callq	0x133d0 ## symbol stub for: _puts
+	jmp	0x860e
 	nop
 	movl	16(%rbp), %r9d
 	movq	-312(%rbp), %rdi
 	movq	-304(%rbp), %rsi
 	movq	%r15, %rdx
 	movq	-112(%rbp), %rcx
 	movq	-120(%rbp), %r8
@@ -5798,61 +5800,60 @@
 	movq	%r15, %rdi
 	movq	-360(%rbp), %rsi
 	leaq	-52(%rbp), %rbx
 	movq	%rbx, %rdx
 	movq	-208(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	movq	%r15, %rdi
 	leaq	-64(%rbp), %r15
 	movq	%r15, %rsi
 	movq	%r14, %rdx
 	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	16(%rbp), %r8d
 	testl	%r8d, %r8d
 	movq	-176(%rbp), %r9
-	jle	0x8e00
+	jle	0x8680
 	cmpl	$1, %r8d
-	jne	0x8e10
+	jne	0x8690
 	xorl	%ecx, %ecx
-	movsd	43064(%rip), %xmm1
-	jmp	0x8e63
+	movsd	44584(%rip), %xmm1
+	jmp	0x86e3
 	nopw	(%rax,%rax)
 	xorl	%r8d, %r8d
-	jmp	0x8e83
+	jmp	0x8703
 	nopw	%cs:(%rax,%rax)
-	nop
 	movl	%r8d, %edx
 	andl	$-2, %edx
 	leal	1(%r8), %esi
 	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
-	movsd	43011(%rip), %xmm1
+	movsd	44531(%rip), %xmm1
 	nopl	(%rax)
 	movslq	%ebx, %rbx
 	movsd	(%r14,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r14,%rbx,8)
 	leal	(%rsi,%rbx), %eax
 	cltq
 	movsd	(%r14,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r14,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
 	cmpq	%rcx, %rdx
-	jne	0x8e30
+	jne	0x86b0
 	testb	$1, %r8b
-	je	0x8e83
+	je	0x8703
 	movl	%r8d, %eax
 	imull	%ecx, %eax
 	addl	%ecx, %eax
 	cltq
 	movsd	(%r14,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r14,%rax,8)
@@ -5881,24 +5882,24 @@
 	pushq	%rax
 	leaq	-280(%rbp), %rax
 	pushq	%rax
 	pushq	-264(%rbp)
 	leaq	-284(%rbp), %rax
 	pushq	%rax
 	pushq	%r14
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	$0, -44(%rbp)
 	movl	16(%rbp), %eax
 	testl	%eax, %eax
 	movq	%r15, %rsi
 	movq	-296(%rbp), %r15
 	movq	-256(%rbp), %r14
-	movapd	42845(%rip), %xmm1
-	jle	0x8fa0
+	movapd	44349(%rip), %xmm1
+	jle	0x881f
 	xorl	%ecx, %ecx
 	nopw	(%rax,%rax)
 	movslq	%ecx, %rax
 	leaq	(%r14,%rax,8), %rdx
 	movl	-140(%rbp), %ecx
 	imull	-80(%rbp), %ecx
 	addl	%eax, %ecx
@@ -5908,113 +5909,109 @@
 	movsd	(%r15,%rax,8), %xmm0
 	xorpd	%xmm1, %xmm0
 	movlpd	%xmm0, -64(%rbp)
 	movq	%r12, %rdi
 	movq	%rsi, %rbx
 	movq	%r13, %rcx
 	leaq	-132(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	movapd	42755(%rip), %xmm1
+	callq	0x13376 ## symbol stub for: _daxpy
+	movapd	44259(%rip), %xmm1
 	movq	%rbx, %rsi
 	movl	-44(%rbp), %ecx
-	addl	$1, %ecx
+	incl	%ecx
 	movl	%ecx, -44(%rbp)
 	movl	16(%rbp), %eax
 	cmpl	%eax, %ecx
-	jl	0x8f40
+	jl	0x87c0
 	movabsq	$-4616189618054758400, %rcx
 	movq	%rcx, -64(%rbp)
 	movl	$0, -44(%rbp)
 	cmpl	$0, -56(%rbp)
 	leaq	-52(%rbp), %rbx
 	movq	-176(%rbp), %r14
 	leaq	-48(%rbp), %r13
 	movq	-80(%rbp), %r15
-	jle	0x9030
+	jle	0x88b0
 	movq	%rsi, %r12
 	xorl	%ecx, %ecx
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movq	-192(%rbp), %rdx
 	imull	%ecx, %eax
 	movl	-140(%rbp), %ecx
 	imull	%r15d, %ecx
 	addl	%eax, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r14,%rax,8), %r8
 	leaq	16(%rbp), %rdi
 	movq	%r12, %rsi
 	movq	%rbx, %rcx
 	movq	%r13, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movl	-44(%rbp), %ecx
-	addl	$1, %ecx
+	incl	%ecx
 	movl	%ecx, -44(%rbp)
 	cmpl	-56(%rbp), %ecx
-	jge	0x9030
+	jge	0x88b0
 	movl	16(%rbp), %eax
-	jmp	0x8fe0
+	jmp	0x8860
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	leaq	-140(%rbp), %rdi
 	movq	-152(%rbp), %rcx
 	movq	%rcx, %rsi
 	movq	%rbx, %rdx
 	movq	%r13, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	-128(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -128(%rbp)
 	movl	48(%rbp), %r12d
 	cmpl	$4, %r12d
-	jl	0x8910
-	leaq	44093(%rip), %rdi ## literal pool for: "\t\t\t cv: %d \tend; err_mean = %f.\n"
+	jl	0x8190
+	leaq	45645(%rip), %rdi ## literal pool for: "\t\t\t cv: %d \tend; err_mean = %f.\n"
 	movl	%r15d, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	jmp	0x8910
+	callq	0x133c4 ## symbol stub for: _printf
+	jmp	0x8190
 	nop
 	movsd	-128(%rbp), %xmm0
 	movsd	-224(%rbp), %xmm1
 	movsd	%xmm1, -232(%rbp)
-	jmp	0x90a4
+	jmp	0x8924
 	nopw	(%rax,%rax)
 	xorpd	%xmm0, %xmm0
 	movl	-144(%rbp), %eax
 	xorps	%xmm1, %xmm1
 	cvtsi2sd	%eax, %xmm1
 	divsd	%xmm1, %xmm0
 	movsd	%xmm0, -128(%rbp)
 	movq	-328(%rbp), %rcx
 	movq	-168(%rbp), %rdx
 	movsd	%xmm0, (%rcx,%rdx,8)
 	testl	%eax, %eax
-	jle	0x90f0
+	jle	0x8970
 	cmpl	$4, %eax
-	jae	0x9100
+	jae	0x8980
 	xorl	%ecx, %ecx
 	movl	-72(%rbp), %r15d
-	jmp	0x91b0
+	jmp	0x8a30
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	xorl	%eax, %eax
 	movl	-72(%rbp), %r15d
-	jmp	0x91c9
+	jmp	0x8a48
 	nopl	(%rax,%rax)
 	movl	%eax, %ecx
 	andl	$-4, %ecx
 	leaq	-4(%rcx), %rsi
 	movq	%rsi, %rdx
 	shrq	$2, %rdx
-	addq	$1, %rdx
+	incq	%rdx
 	testq	%rsi, %rsi
-	je	0x9267
+	je	0x8ae5
 	movq	%rdx, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
 	xorl	%esi, %esi
 	movl	-72(%rbp), %r15d
 	nopl	(%rax)
 	movupd	(%r14,%rsi,8), %xmm0
 	movupd	16(%r14,%rsi,8), %xmm1
 	movupd	32(%r14,%rsi,8), %xmm2
 	movupd	48(%r14,%rsi,8), %xmm3
@@ -6023,726 +6020,784 @@
 	movupd	%xmm0, (%r14,%rsi,8)
 	movupd	%xmm1, 16(%r14,%rsi,8)
 	mulpd	%xmm2, %xmm2
 	mulpd	%xmm3, %xmm3
 	movupd	%xmm2, 32(%r14,%rsi,8)
 	movupd	%xmm3, 48(%r14,%rsi,8)
 	addq	$8, %rsi
-	addq	$2, %rdi
-	jne	0x9130
+	addq	$-2, %rdi
+	jne	0x89b0
 	testb	$1, %dl
-	je	0x91a7
+	je	0x8a27
 	movupd	(%r14,%rsi,8), %xmm0
 	movupd	16(%r14,%rsi,8), %xmm1
 	mulpd	%xmm0, %xmm0
 	mulpd	%xmm1, %xmm1
 	movupd	%xmm0, (%r14,%rsi,8)
 	movupd	%xmm1, 16(%r14,%rsi,8)
 	cmpq	%rax, %rcx
-	je	0x91c9
+	je	0x8a48
 	nopl	(%rax)
 	movsd	(%r14,%rcx,8), %xmm0
 	mulsd	%xmm0, %xmm0
 	movsd	%xmm0, (%r14,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %rax
-	jne	0x91b0
+	jne	0x8a30
 	movl	%eax, -44(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-144(%rbp), %r13
 	movq	%r13, %rdi
 	leaq	-64(%rbp), %rsi
 	leaq	-128(%rbp), %rdx
 	leaq	-136(%rbp), %rcx
 	movq	%r14, %r8
 	movq	%r14, %rbx
 	leaq	-52(%rbp), %r14
 	movq	%r14, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r13, %rdi
 	movq	%rbx, %r13
 	movq	%rbx, %rsi
 	movq	%r14, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	cmpl	$3, %r12d
-	jl	0x88d0
+	jl	0x8150
 	movapd	%xmm0, %xmm1
 	movl	-144(%rbp), %eax
-	addl	$-1, %eax
+	decl	%eax
 	imull	%r15d, %eax
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
 	sqrtsd	%xmm0, %xmm0
 	divsd	%xmm0, %xmm1
 	movsd	-128(%rbp), %xmm0
-	leaq	43649(%rip), %rdi ## literal pool for: "\t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n"
+	leaq	45203(%rip), %rdi ## literal pool for: "\t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n"
 	movq	-168(%rbp), %rsi
 	movl	%r15d, %edx
 	movsd	-88(%rbp), %xmm2
 	movb	$3, %al
-	callq	0x1354a ## symbol stub for: _printf
-	jmp	0x88d0
+	callq	0x133c4 ## symbol stub for: _printf
+	jmp	0x8150
 	xorl	%esi, %esi
 	movl	-72(%rbp), %r15d
 	testb	$1, %dl
-	jne	0x9185
-	jmp	0x91a7
+	jne	0x8a05
+	jmp	0x8a27
 	movl	$8, %esi
 	movq	-376(%rbp), %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	xorps	%xmm0, %xmm0
 	cvtsi2sdl	-144(%rbp), %xmm0
 	movq	%rax, %rbx
-	movsd	42022(%rip), %xmm1
+	movsd	43528(%rip), %xmm1
 	subsd	%xmm0, %xmm1
 	movsd	%xmm1, -424(%rbp)
 	leaq	32(%rbp), %r14
 	leaq	-424(%rbp), %rsi
 	leaq	-136(%rbp), %rdx
 	leaq	-52(%rbp), %r13
 	movq	%r14, %rdi
 	movq	%rax, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-64(%rbp), %rsi
 	leaq	-48(%rbp), %r9
 	movq	%r14, %rdi
 	movq	-328(%rbp), %rdx
 	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r14, %rdi
 	movq	%rbx, %rsi
 	movq	%r13, %rdx
-	callq	0x13538 ## symbol stub for: _idamax
+	callq	0x133b2 ## symbol stub for: _idamax
 	movl	%eax, %r14d
 	cmpl	$2, %r12d
-	jl	0x9325
-	leaq	43515(%rip), %rdi ## literal pool for: "\t\tExit Function: cv_support. optimal lambda index: %d.\n\n"
+	jl	0x8ba3
+	leaq	45069(%rip), %rdi ## literal pool for: "\t\tExit Function: cv_support. optimal lambda index: %d.\n\n"
 	movl	%r14d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-208(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-344(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-112(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-120(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-360(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-296(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-328(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-216(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-160(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-264(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-256(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-304(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-392(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-384(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-352(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-336(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movl	%r14d, %eax
 	addq	$392, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	xorl	%esi, %esi
+	xorl	%edx, %edx
 	testb	$1, %r9b
-	jne	0x8676
-	jmp	0x86a0
-	nopl	(%rax)
+	jne	0x7ef6
+	jmp	0x7f20
+	nopl	(%rax,%rax)
 _mainSML:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
 	subq	$216, %rsp
-	movq	%r9, %r12
+	movq	%r9, %r15
 	movq	%r8, -56(%rbp)
-	movq	%rsi, -136(%rbp)
-	movq	%rdi, -96(%rbp)
-	movq	24(%rbp), %rbx
+	movq	%rsi, -120(%rbp)
+	movq	%rdi, -128(%rbp)
+	movq	24(%rbp), %r12
 	movq	32(%rbp), %rax
 	movl	$1, -68(%rbp)
 	movl	$1, -64(%rbp)
-	movl	$0, -84(%rbp)
+	movl	$0, -136(%rbp)
 	movl	(%rdx), %r13d
 	movl	%r13d, -44(%rbp)
 	movl	(%rcx), %ecx
 	movl	(%rax), %eax
 	movq	%rax, -112(%rbp)
-	movq	%rcx, -120(%rbp)
+	movq	%rcx, -96(%rbp)
 	movl	%ecx, %eax
 	imull	%r13d, %eax
 	movl	%eax, -80(%rbp)
-	movl	%eax, -124(%rbp)
+	movl	%eax, -132(%rbp)
 	movl	%r13d, %eax
 	imull	%r13d, %eax
 	movl	%eax, -60(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r14
 	leaq	-60(%rbp), %rdi
 	leaq	-68(%rbp), %rdx
 	leaq	-64(%rbp), %r8
-	movq	%r12, %rsi
+	movq	%r15, %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	$0, 8(%rbx)
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	$0, 8(%r12)
 	testl	%r13d, %r13d
-	jle	0x95cf
-	movq	%rbx, %r9
+	jle	0x8e62
 	movl	%r13d, %r8d
 	andl	$-2, %r8d
 	leal	(%r13,%r13), %ecx
 	xorpd	%xmm0, %xmm0
 	xorl	%edx, %edx
-	movsd	41263(%rip), %xmm1
+	movsd	42782(%rip), %xmm1
 	xorpd	%xmm2, %xmm2
-	jmp	0x951d
-	nopw	(%rax,%rax)
-	addq	$1, %rdx
+	jmp	0x8d9c
+	nopl	(%rax,%rax)
+	incq	%rdx
 	cmpq	%r13, %rdx
-	je	0x95cf
+	je	0x8e62
 	cmpl	$1, %r13d
-	jne	0x9560
-	xorl	%edi, %edi
+	jne	0x8db0
+	xorl	%ebx, %ebx
 	testb	$1, %r13b
-	je	0x9510
-	cmpq	%rdi, %rdx
-	je	0x9510
-	imull	%r13d, %edi
-	addl	%edx, %edi
-	movslq	%edi, %rax
-	movsd	(%r12,%rax,8), %xmm3
+	je	0x8d90
+	jmp	0x8e2e
+	nop
+	movl	%edx, %edi
+	xorl	%esi, %esi
+	jmp	0x8dca
+	nopw	%cs:(%rax,%rax)
+	addl	%ecx, %edi
+	incq	%rsi
+	cmpq	%r8, %rsi
+	je	0x8e20
+	movq	%rsi, %rbx
+	cmpq	%rsi, %rdx
+	je	0x8dee
+	movslq	%edi, %rsi
+	movsd	(%r15,%rsi,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x9547
-	jnp	0x9510
+	jne	0x8de3
+	jnp	0x8dee
 	addsd	%xmm1, %xmm2
-	movsd	%xmm2, 8(%r9)
-	jmp	0x9510
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	movl	%edx, %esi
-	xorl	%eax, %eax
-	jmp	0x9585
-	nopw	%cs:(%rax,%rax)
-	movq	%rax, %rdi
-	addq	$2, %rdi
-	addl	%ecx, %esi
-	addq	$1, %rbx
-	movq	%rbx, %rax
-	cmpq	%rdi, %r8
-	je	0x9525
-	cmpq	%rax, %rdx
-	je	0x95a5
-	movslq	%esi, %rdi
-	movsd	(%r12,%rdi,8), %xmm3
+	movsd	%xmm2, 8(%r12)
+	leaq	1(%rbx), %rsi
+	cmpq	%rsi, %rdx
+	je	0x8dc0
+	leal	(%rdi,%r13), %eax
+	cltq
+	movsd	(%r15,%rax,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x959b
-	jnp	0x95a5
+	jne	0x8e0b
+	jnp	0x8dc0
 	addsd	%xmm1, %xmm2
-	movsd	%xmm2, 8(%r9)
-	leaq	1(%rax), %rbx
+	movsd	%xmm2, 8(%r12)
+	jmp	0x8dc0
+	nopl	(%rax,%rax)
+	addq	$2, %rbx
+	testb	$1, %r13b
+	je	0x8d90
 	cmpq	%rbx, %rdx
-	je	0x9570
-	leal	(%rsi,%r13), %edi
-	movslq	%edi, %rdi
-	movsd	(%r12,%rdi,8), %xmm3
+	je	0x8d90
+	imull	%r13d, %ebx
+	addl	%edx, %ebx
+	movslq	%ebx, %rax
+	movsd	(%r15,%rax,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x95c3
-	jnp	0x9570
+	jne	0x8e52
+	jnp	0x8d90
 	addsd	%xmm1, %xmm2
-	movsd	%xmm2, 8(%r9)
-	jmp	0x9570
-	movabsq	$4607182418800017408, %r13
-	movq	%r13, -216(%rbp)
+	movsd	%xmm2, 8(%r12)
+	jmp	0x8d90
+	movabsq	$4607182418800017408, %rax
+	movq	%rax, -192(%rbp)
 	leaq	-44(%rbp), %rdi
-	leaq	-216(%rbp), %r15
-	leaq	-84(%rbp), %rdx
-	leaq	-68(%rbp), %rbx
-	movq	%r15, %rsi
+	leaq	-192(%rbp), %rsi
+	leaq	-136(%rbp), %rbx
+	leaq	-68(%rbp), %r13
+	movq	%rbx, %rdx
 	movq	16(%rbp), %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	$0, -216(%rbp)
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	$0, -192(%rbp)
 	leaq	-60(%rbp), %rdi
-	movq	%r15, %rsi
-	leaq	-84(%rbp), %rdx
-	movq	%r12, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	leaq	-192(%rbp), %rsi
+	movq	%rbx, %rdx
+	movq	%r15, %rcx
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	cmpl	$0, -80(%rbp)
+	movq	-128(%rbp), %rdi
+	movq	-56(%rbp), %rbx
+	jle	0x9001
 	movl	-80(%rbp), %ecx
-	testl	%ecx, %ecx
-	movq	-56(%rbp), %rdi
-	jle	0x9651
 	movl	%ecx, %eax
-	cmpl	$1, %ecx
-	jne	0x9829
+	cmpl	$4, %ecx
+	jb	0x8eea
+	leaq	(%rbx,%rax,4), %rcx
+	cmpq	%rdi, %rcx
+	jbe	0x8f4d
+	leaq	(%rdi,%rax,8), %rcx
+	cmpq	%rbx, %rcx
+	jbe	0x8f4d
 	xorl	%ecx, %ecx
+	movq	%rcx, %rdx
+	notq	%rdx
 	testb	$1, %al
-	je	0x9651
-	cmpl	$1, (%rdi,%rcx,4)
-	jne	0x9651
-	movq	-96(%rbp), %rax
-	movq	$0, (%rax,%rcx,8)
+	je	0x8f08
+	cmpl	$1, (%rbx,%rcx,4)
+	jne	0x8f04
+	movq	$0, (%rdi,%rcx,8)
+	orq	$1, %rcx
+	addq	%rax, %rdx
+	jne	0x8f2d
+	jmp	0x9001
+	nopw	%cs:(%rax,%rax)
+	addq	$2, %rcx
+	cmpq	%rcx, %rax
+	je	0x9001
+	cmpl	$1, (%rbx,%rcx,4)
+	jne	0x8f3b
+	movq	$0, (%rdi,%rcx,8)
+	cmpl	$1, 4(%rbx,%rcx,4)
+	jne	0x8f20
+	movq	$0, 8(%rdi,%rcx,8)
+	jmp	0x8f20
+	movl	%eax, %ecx
+	andl	$-4, %ecx
+	xorl	%edx, %edx
+	movdqa	42516(%rip), %xmm0
+	movdqa	42524(%rip), %xmm1
+	jmp	0x8f79
+	nopw	%cs:(%rax,%rax)
+	addq	$4, %rdx
+	cmpq	%rdx, %rcx
+	je	0x8ff8
+	movq	(%rbx,%rdx,4), %xmm3
+	movq	8(%rbx,%rdx,4), %xmm2
+	movdqa	%xmm3, %xmm4
+	pcmpeqd	%xmm0, %xmm4
+	movd	%xmm4, %esi
+	testb	$1, %sil
+	je	0x8f9e
+	movq	$0, (%rdi,%rdx,8)
+	pshufd	$212, %xmm3, %xmm3
+	pcmpeqd	%xmm1, %xmm3
+	pextrw	$4, %xmm3, %esi
+	testb	$1, %sil
+	je	0x8fbb
+	movq	$0, 8(%rdi,%rdx,8)
+	movdqa	%xmm2, %xmm3
+	pcmpeqd	%xmm0, %xmm3
+	movd	%xmm3, %esi
+	testb	$1, %sil
+	je	0x8fd6
+	movq	$0, 16(%rdi,%rdx,8)
+	pshufd	$212, %xmm2, %xmm2
+	pcmpeqd	%xmm1, %xmm2
+	pextrw	$4, %xmm2, %esi
+	testb	$1, %sil
+	je	0x8f70
+	movq	$0, 24(%rdi,%rdx,8)
+	jmp	0x8f70
+	cmpq	%rax, %rcx
+	jne	0x8eec
 	movl	$20, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movaps	41113(%rip), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movaps	42361(%rip), %xmm0
 	movups	%xmm0, (%rax)
-	movaps	41119(%rip), %xmm0
+	movaps	42367(%rip), %xmm0
 	movups	%xmm0, 16(%rax)
-	movaps	41124(%rip), %xmm0
+	movaps	42372(%rip), %xmm0
 	movups	%xmm0, 32(%rax)
-	movaps	41129(%rip), %xmm0
+	movaps	42377(%rip), %xmm0
 	movups	%xmm0, 48(%rax)
-	movaps	41134(%rip), %xmm0
+	movaps	42382(%rip), %xmm0
 	movups	%xmm0, 64(%rax)
-	movaps	41139(%rip), %xmm0
+	movaps	42387(%rip), %xmm0
 	movups	%xmm0, 80(%rax)
-	movaps	41144(%rip), %xmm0
+	movaps	42392(%rip), %xmm0
 	movups	%xmm0, 96(%rax)
-	movaps	41149(%rip), %xmm0
+	movaps	42397(%rip), %xmm0
 	movups	%xmm0, 112(%rax)
-	movaps	41154(%rip), %xmm0
+	movaps	42402(%rip), %xmm0
 	movups	%xmm0, 128(%rax)
-	movaps	41156(%rip), %xmm0
+	movaps	42404(%rip), %xmm0
 	movq	%rax, -176(%rbp)
 	movups	%xmm0, 144(%rax)
 	movl	$31, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r15
-	movsd	40924(%rip), %xmm1
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r13
+	movsd	42124(%rip), %xmm1
 	movl	$3, %ebx
 	nopl	(%rax)
-	movsd	40912(%rip), %xmm0
+	movsd	42112(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -24(%r15,%rbx,8)
-	movsd	40895(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -24(%r13,%rbx,8)
+	movsd	42095(%rip), %xmm0
 	movsd	-56(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	40865(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -16(%r15,%rbx,8)
+	movsd	42065(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -16(%r13,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	40848(%rip), %xmm1
-	movsd	40832(%rip), %xmm0
+	addsd	42048(%rip), %xmm1
+	movsd	42032(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -8(%r15,%rbx,8)
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -8(%r13,%rbx,8)
 	cmpq	$31, %rbx
-	je	0x97ae
+	je	0x915f
 	movsd	-56(%rbp), %xmm1
-	movsd	40804(%rip), %xmm0
+	movsd	42004(%rip), %xmm0
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	40779(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, (%r15,%rbx,8)
+	movsd	41979(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, (%r13,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	40763(%rip), %xmm1
+	addsd	41962(%rip), %xmm1
 	addq	$4, %rbx
-	jmp	0x9700
-	movq	%r15, -152(%rbp)
-	movslq	-60(%rbp), %rbx
+	jmp	0x90b0
+	movq	%r13, -160(%rbp)
+	movslq	-60(%rbp), %r13
 	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r15
+	movq	%r13, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -104(%rbp)
 	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %rbx
+	movq	%r13, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -88(%rbp)
 	movq	$0, -240(%rbp)
 	leaq	-60(%rbp), %rdi
 	leaq	-240(%rbp), %rsi
-	leaq	-84(%rbp), %rdx
+	leaq	-136(%rbp), %rdx
 	leaq	-64(%rbp), %r8
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	-44(%rbp), %r10d
-	testl	%r10d, %r10d
-	movq	%r15, -104(%rbp)
-	jle	0x98ef
-	leaq	-1(%r10), %rax
-	movl	%r10d, %ecx
+	callq	0x1337c ## symbol stub for: _dcopy
+	movl	-44(%rbp), %r11d
+	testl	%r11d, %r11d
+	movq	-120(%rbp), %rsi
+	jle	0x928f
+	leaq	-1(%r11), %rax
+	movl	%r11d, %ecx
 	andl	$3, %ecx
 	xorl	%esi, %esi
 	cmpq	$3, %rax
-	jae	0x986d
+	movq	%r11, -56(%rbp)
+	jae	0x91ee
 	xorl	%edx, %edx
-	jmp	0x98d0
-	movl	%eax, %edx
-	andl	$-2, %edx
-	xorl	%ecx, %ecx
-	movq	-96(%rbp), %rsi
-	jmp	0x984d
-	nopw	%cs:(%rax,%rax)
-	addq	$2, %rcx
-	cmpq	%rcx, %rdx
-	je	0x963b
-	cmpl	$1, (%rdi,%rcx,4)
-	jne	0x985b
-	movq	$0, (%rsi,%rcx,8)
-	cmpl	$1, 4(%rdi,%rcx,4)
-	jne	0x9840
-	movq	$0, 8(%rsi,%rcx,8)
-	jmp	0x9840
-	movl	%r10d, %r9d
+	movq	-88(%rbp), %r13
+	movabsq	$4607182418800017408, %r10
+	jmp	0x9263
+	movl	%r11d, %r9d
 	andl	$-4, %r9d
-	leal	(%r10,%r10), %r8d
+	leal	(%r11,%r11), %r8d
 	addl	$2, %r8d
-	leal	4(,%r10,4), %r11d
-	leal	1(%r10), %r15d
-	leal	(%r10,%r10,2), %edi
+	movq	%r11, %rax
+	leal	4(,%r11,4), %r11d
+	leal	1(%rax), %ebx
+	leal	(%rax,%rax,2), %edi
 	addl	$3, %edi
 	xorl	%edx, %edx
+	movq	-88(%rbp), %r13
+	movabsq	$4607182418800017408, %r10
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	movslq	%esi, %rsi
-	movq	%r13, (%rbx,%rsi,8)
-	leal	(%r15,%rsi), %eax
+	movq	%r10, (%r13,%rsi,8)
+	leal	(%rbx,%rsi), %eax
 	cltq
-	movq	%r13, (%rbx,%rax,8)
+	movq	%r10, (%r13,%rax,8)
 	leal	(%r8,%rsi), %eax
 	cltq
-	movq	%r13, (%rbx,%rax,8)
+	movq	%r10, (%r13,%rax,8)
 	leal	(%rdi,%rsi), %eax
 	cltq
-	movq	%r13, (%rbx,%rax,8)
+	movq	%r10, (%r13,%rax,8)
 	addq	$4, %rdx
 	addl	%r11d, %esi
 	cmpq	%rdx, %r9
-	jne	0x98a0
+	jne	0x9230
 	testq	%rcx, %rcx
-	movq	-104(%rbp), %r15
-	je	0x98ef
-	leal	1(%r10), %eax
+	movq	-120(%rbp), %rsi
+	movq	-56(%rbp), %r11
+	je	0x928f
+	leal	1(%r11), %eax
 	imull	%eax, %edx
+	nopw	(%rax,%rax)
 	movslq	%edx, %rdx
-	movq	%r13, (%rbx,%rdx,8)
+	movq	%r10, (%r13,%rdx,8)
 	addl	%eax, %edx
-	addq	$-1, %rcx
-	jne	0x98e0
-	movq	%rbx, -144(%rbp)
+	decq	%rcx
+	jne	0x9280
 	subq	$8, %rsp
 	leaq	-248(%rbp), %rax
-	movq	-96(%rbp), %rdi
-	movq	-136(%rbp), %rsi
+	movq	-128(%rbp), %rdi
 	movl	$5, %edx
 	movq	-176(%rbp), %rcx
-	movq	-152(%rbp), %r8
+	movq	-160(%rbp), %r8
 	movl	$500, %r9d
 	pushq	%rax
-	pushq	%r15
+	pushq	-104(%rbp)
 	movq	-112(%rbp), %rbx
 	pushq	%rbx
 	pushq	$31
 	pushq	$20
-	pushq	-120(%rbp)
-	pushq	%r10
+	pushq	-96(%rbp)
+	pushq	%r11
 	callq	_cv_gene_nets_support_Rdg
 	addq	$64, %rsp
-	movl	%eax, %r13d
+	movl	%eax, %eax
+	movq	%rax, -144(%rbp)
 	testl	%ebx, %ebx
-	jne	0x9957
-	leaq	41986(%rip), %rdi ## literal pool for: "Step 1: CV support; return number of lambda needed: %d\n"
-	movl	%r13d, %esi
+	jne	0x92f4
+	leaq	43257(%rip), %rdi ## literal pool for: "Step 1: CV support; return number of lambda needed: %d\n"
+	movq	-144(%rbp), %rsi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	movq	%r13, -160(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
 	movslq	-44(%rbp), %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -184(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -152(%rbp)
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %rbx
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -200(%rbp)
 	movslq	-80(%rbp), %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r15
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %rbx
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r13
-	leaq	-124(%rbp), %rdi
+	leaq	-132(%rbp), %rdi
 	leaq	-68(%rbp), %rdx
 	leaq	-64(%rbp), %r8
-	movq	-136(%rbp), %rsi
+	movq	-120(%rbp), %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-124(%rbp), %rdi
-	movq	-96(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-132(%rbp), %rdi
+	movq	-128(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
-	movq	%r15, %rcx
+	movq	%rbx, %rcx
 	leaq	-64(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r8d
-	movq	%r15, %rdi
+	movq	%rbx, %rdi
 	movq	%r13, %rsi
-	movq	-184(%rbp), %rdx
-	movq	%rbx, -224(%rbp)
-	movq	%rbx, %rcx
-	movq	-120(%rbp), %rbx
-	movl	%ebx, %r9d
+	movq	%r13, -184(%rbp)
+	movq	-152(%rbp), %rdx
+	movq	-200(%rbp), %rcx
+	movq	-96(%rbp), %r9
 	callq	_centerYX
 	movslq	-60(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movsd	-248(%rbp), %xmm0
 	movl	-44(%rbp), %ecx
-	movq	%r15, %rdi
+	movq	%rbx, %rdi
 	movq	%r13, %rsi
 	movq	%rax, -168(%rbp)
 	movq	%rax, %rdx
 	movsd	%xmm0, -80(%rbp)
-	movl	%ebx, %r8d
+	movq	-96(%rbp), %r13
+	movl	%r13d, %r8d
 	callq	_QlambdaStart
 	movl	-44(%rbp), %ecx
-	movq	%r15, -208(%rbp)
-	movq	%r15, %rdi
-	movq	%r13, -200(%rbp)
-	movq	%r13, %rsi
+	movq	%rbx, -216(%rbp)
+	movq	%rbx, %rdi
+	movq	-184(%rbp), %rsi
 	movq	-104(%rbp), %rdx
-	movl	%ebx, %r8d
+	movl	%r13d, %r8d
 	callq	_lambdaMax
-	movsd	%xmm0, -192(%rbp)
+	movsd	%xmm0, -208(%rbp)
 	movq	-112(%rbp), %r10
 	testl	%r10d, %r10d
-	jne	0x9a7e
-	leaq	42164(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
-	callq	0x13556 ## symbol stub for: _puts
+	je	0x941b
+	cmpl	$0, -144(%rbp)
+	jg	0x9438
+	jmp	0x95b4
+	leaq	43789(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
+	callq	0x133d0 ## symbol stub for: _puts
 	movq	-112(%rbp), %r10
-	movq	-160(%rbp), %rbx
-	testl	%ebx, %ebx
-	movq	-144(%rbp), %r15
-	jle	0x9c03
-	movsd	39828(%rip), %xmm1
+	cmpl	$0, -144(%rbp)
+	jle	0x95b4
+	movq	-144(%rbp), %rax
+	decq	%rax
+	movq	%rax, -224(%rbp)
+	movsd	41039(%rip), %xmm1
+	movsd	41199(%rip), %xmm0
 	xorl	%r13d, %r13d
-	jmp	0x9b86
-	nopw	%cs:(%rax,%rax)
-	nop
-	leaq	41680(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
+	nopl	(%rax)
+	testl	%r10d, %r10d
+	movsd	%xmm0, -56(%rbp)
+	jle	0x9510
+	leaq	42914(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
 	movl	%r13d, %esi
-	movl	%ebx, %edx
+	movq	-144(%rbp), %rdx
 	movb	$1, %al
 	movsd	%xmm1, -232(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
 	movq	-104(%rbp), %rdi
-	movq	%r12, %rsi
-	movq	16(%rbp), %r15
-	movq	%r15, %rdx
-	movq	-96(%rbp), %rcx
-	movq	-136(%rbp), %r8
-	movq	-168(%rbp), %rbx
-	movq	%rbx, %r9
+	movq	%r15, %rsi
+	movq	16(%rbp), %rdx
+	movq	-128(%rbp), %rcx
+	movq	-120(%rbp), %r8
+	movq	%r12, %rbx
+	movq	-168(%rbp), %r12
+	movq	%r12, %r9
 	movsd	-56(%rbp), %xmm0
 	movsd	-232(%rbp), %xmm1
 	movsd	-80(%rbp), %xmm2
-	movsd	-192(%rbp), %xmm3
-	pushq	-144(%rbp)
+	movsd	-208(%rbp), %xmm3
+	pushq	-88(%rbp)
 	pushq	-112(%rbp)
-	pushq	-120(%rbp)
+	pushq	-96(%rbp)
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf
 	addq	$48, %rsp
-	leaq	41593(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
+	leaq	42828(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-80(%rbp), %xmm0
-	movq	%rbx, %rdx
-	movq	-160(%rbp), %rbx
-	movq	%r15, %r8
-	movq	-144(%rbp), %r15
-	movl	-44(%rbp), %r9d
-	movq	-208(%rbp), %rdi
-	movq	-200(%rbp), %rsi
-	movq	%r12, %rcx
-	pushq	%r15
-	pushq	-120(%rbp)
-	callq	_QlambdaMiddleCenter
-	addq	$16, %rsp
-	addq	$1, %r13
-	movsd	-56(%rbp), %xmm1
-	cmpq	%r13, %rbx
-	movq	-112(%rbp), %r10
-	je	0x9c03
-	movq	-176(%rbp), %rax
-	movsd	(%rax,%r13,8), %xmm0
-	testl	%r10d, %r10d
-	movsd	%xmm0, -56(%rbp)
-	jg	0x9ab0
+	movq	%r12, %rdx
+	movq	%rbx, %r12
+	movq	16(%rbp), %r8
+	movq	-88(%rbp), %rbx
+	movq	-96(%rbp), %rax
+	jmp	0x956c
+	nop
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
 	movq	-104(%rbp), %rdi
-	movq	%r12, %rsi
+	movq	%r15, %rsi
 	movq	16(%rbp), %rdx
-	movq	-96(%rbp), %rcx
-	movq	-136(%rbp), %r8
+	movq	-128(%rbp), %rcx
+	movq	-120(%rbp), %r8
 	movq	-168(%rbp), %rbx
 	movq	%rbx, %r9
 	movsd	-80(%rbp), %xmm2
-	movsd	-192(%rbp), %xmm3
-	pushq	%r15
+	movsd	-208(%rbp), %xmm3
+	pushq	-88(%rbp)
 	pushq	%r10
-	pushq	-120(%rbp)
+	pushq	-96(%rbp)
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf
 	movsd	-80(%rbp), %xmm0
 	movq	%rbx, %rdx
-	movq	-160(%rbp), %rbx
 	movq	16(%rbp), %r8
+	movq	-88(%rbp), %rbx
+	movq	-96(%rbp), %rax
 	addq	$48, %rsp
-	jmp	0x9b51
-	movq	24(%rbp), %r11
-	movq	$0, (%r11)
+	movl	-44(%rbp), %r9d
+	movq	-216(%rbp), %rdi
+	movq	-184(%rbp), %rsi
+	movq	%r15, %rcx
+	pushq	%rbx
+	pushq	%rax
+	callq	_QlambdaMiddleCenter
+	addq	$16, %rsp
+	cmpq	%r13, -224(%rbp)
+	movq	-112(%rbp), %r10
+	je	0x95b4
+	movq	-176(%rbp), %rax
+	movsd	8(%rax,%r13,8), %xmm0
+	incq	%r13
+	movsd	-56(%rbp), %xmm1
+	jmp	0x9460
+	movq	$0, (%r12)
 	xorpd	%xmm0, %xmm0
-	movupd	%xmm0, 16(%r11)
+	movupd	%xmm0, 16(%r12)
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
-	jle	0x9ce9
-	leaq	16(%r11), %r9
+	jle	0x969e
+	leaq	16(%r12), %r9
 	movq	%rax, %rdx
 	negq	%rdx
 	xorpd	%xmm2, %xmm2
 	xorl	%esi, %esi
-	movsd	39413(%rip), %xmm3
-	xorpd	%xmm0, %xmm0
+	movsd	40629(%rip), %xmm3
 	xorpd	%xmm1, %xmm1
-	xorpd	%xmm4, %xmm4
+	pxor	%xmm4, %xmm4
+	xorpd	%xmm0, %xmm0
 	xorl	%r8d, %r8d
-	movq	-152(%rbp), %r15
-	jmp	0x9c6d
+	movq	-160(%rbp), %r13
+	jmp	0x961b
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	addq	$1, %r8
-	addq	$-1, %rsi
+	incq	%r8
+	decq	%rsi
 	cmpq	%rax, %r8
-	je	0x9ce3
-	movl	%r8d, %edi
-	xorl	%ebx, %ebx
-	jmp	0x9c8b
+	je	0x9694
+	movl	%r8d, %ebx
+	xorl	%edi, %edi
+	jmp	0x963a
 	nopw	%cs:(%rax,%rax)
-	nop
-	addq	$-1, %rbx
-	addl	%eax, %edi
-	cmpq	%rbx, %rdx
-	je	0x9c60
-	movslq	%edi, %rcx
+	decq	%rdi
+	addl	%eax, %ebx
+	cmpq	%rdi, %rdx
+	je	0x9610
+	movslq	%ebx, %rcx
 	movsd	(%r14,%rcx,8), %xmm5
 	ucomisd	%xmm2, %xmm5
-	jne	0x9cb3
-	jp	0x9cb3
-	movsd	(%r12,%rcx,8), %xmm6
+	jne	0x9662
+	jp	0x9662
+	movsd	(%r15,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0x9caa
-	jnp	0x9cb3
-	addsd	%xmm3, %xmm4
-	movsd	%xmm4, (%r9)
-	cmpq	%rbx, %rsi
-	je	0x9c80
-	movsd	(%r12,%rcx,8), %xmm6
+	jne	0x9659
+	jnp	0x9662
+	addsd	%xmm3, %xmm0
+	movsd	%xmm0, (%r9)
+	cmpq	%rdi, %rsi
+	je	0x9630
+	movsd	(%r15,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0x9cc6
-	jnp	0x9c80
-	addsd	%xmm3, %xmm1
-	movsd	%xmm1, 24(%r11)
+	jne	0x9675
+	jnp	0x9630
+	addsd	%xmm3, %xmm4
+	movsd	%xmm4, 24(%r12)
 	ucomisd	%xmm2, %xmm5
-	jne	0x9cd8
-	jnp	0x9c80
-	addsd	%xmm3, %xmm0
-	movsd	%xmm0, (%r11)
-	jmp	0x9c80
-	unpcklpd	%xmm4, %xmm0
-	jmp	0x9cf4
+	jne	0x9688
+	jnp	0x9630
+	addsd	%xmm3, %xmm1
+	movsd	%xmm1, (%r12)
+	jmp	0x9630
+	divsd	%xmm4, %xmm0
+	movq	-112(%rbp), %r10
+	jmp	0x96b1
+	movsd	40618(%rip), %xmm0
 	xorpd	%xmm1, %xmm1
-	movq	-152(%rbp), %r15
-	movsd	8(%r11), %xmm2
-	unpcklpd	%xmm1, %xmm2
-	divpd	%xmm2, %xmm0
-	movupd	%xmm0, 32(%r11)
+	movq	-160(%rbp), %r13
+	movq	-104(%rbp), %r15
+	movq	-152(%rbp), %rbx
+	divsd	8(%r12), %xmm1
+	movsd	%xmm1, 32(%r12)
+	movsd	%xmm0, 40(%r12)
 	testl	%r10d, %r10d
-	jne	0x9d19
-	leaq	41523(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
-	callq	0x13556 ## symbol stub for: _puts
+	jne	0x96e2
+	leaq	43120(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
+	callq	0x133d0 ## symbol stub for: _puts
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-224(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%rbx, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-200(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r13, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-216(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-184(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-208(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-104(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-144(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-88(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$216, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopl	(%rax,%rax)
+	nopl	(%rax)
 _lambdaMax_adaEN:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -6754,118 +6809,117 @@
 	movq	%rdi, -144(%rbp)
 	movl	%ecx, -44(%rbp)
 	movl	%r8d, -60(%rbp)
 	movsd	%xmm0, -160(%rbp)
 	movslq	%ecx, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -104(%rbp)
 	movl	$1, -52(%rbp)
 	movl	$1, -80(%rbp)
 	movl	%r14d, -84(%rbp)
 	imull	%r14d, %ebx
 	movl	%ebx, -108(%rbp)
 	movl	%ebx, -76(%rbp)
 	movl	%r14d, %eax
 	imull	%r14d, %eax
 	movl	%eax, -56(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
 	leaq	-56(%rbp), %r12
 	leaq	-52(%rbp), %r13
 	leaq	-80(%rbp), %r8
 	movq	%r12, %rdi
 	movq	-72(%rbp), %rsi
 	movq	%r13, %rdx
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	-160(%rbp), %rsi
 	movq	%r12, %rdi
 	movq	%r15, %rdx
 	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	testl	%r14d, %r14d
-	jle	0x9ec9
+	jle	0x9888
 	xorl	%r13d, %r13d
 	movq	-120(%rbp), %r14
 	movq	-144(%rbp), %rbx
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	leaq	-60(%rbp), %r12
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	leaq	-84(%rbp), %rdx
 	movq	%r14, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -72(%rbp)
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	leaq	-84(%rbp), %rdx
 	movq	%rbx, %rcx
 	leaq	-44(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	divsd	-72(%rbp), %xmm0
 	movq	-104(%rbp), %rax
 	movsd	%xmm0, (%rax,%r13,8)
-	addq	$1, %r13
+	incq	%r13
 	movslq	-44(%rbp), %rax
 	addq	$8, %rbx
 	addq	$8, %r14
 	cmpq	%rax, %r13
-	jl	0x9e70
+	jl	0x9830
 	movslq	-108(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	-76(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-80(%rbp), %r8
 	movq	-120(%rbp), %rsi
 	movq	%rax, -72(%rbp)
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$0, -44(%rbp)
-	jle	0x9f4a
+	jle	0x9909
 	xorl	%r14d, %r14d
 	leaq	-96(%rbp), %r13
 	leaq	-44(%rbp), %rbx
 	movq	-72(%rbp), %r12
-	nopl	(%rax,%rax)
+	nopw	(%rax,%rax)
 	movq	-104(%rbp), %rax
 	movsd	(%rax,%r14,8), %xmm0
-	xorpd	38766(%rip), %xmm0
+	xorpd	39950(%rip), %xmm0
 	movlpd	%xmm0, -96(%rbp)
 	leaq	-60(%rbp), %rdi
 	movq	%r13, %rsi
 	movq	%r12, %rdx
 	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	addq	$1, %r14
+	callq	0x133a0 ## symbol stub for: _dscal
+	incq	%r14
 	movslq	-44(%rbp), %rax
 	addq	$8, %r12
 	cmpq	%rax, %r14
-	jl	0x9f10
+	jl	0x98d0
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -96(%rbp)
 	leaq	-76(%rbp), %rdi
 	leaq	-96(%rbp), %r14
 	leaq	-52(%rbp), %rcx
 	movq	%r14, %rsi
 	movq	-144(%rbp), %r12
 	movq	%r12, %rdx
 	movq	-72(%rbp), %r13
 	movq	%r13, %r8
 	movq	%rcx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movslq	-56(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	movb	$78, -46(%rbp)
 	movb	$84, -45(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -96(%rbp)
 	movq	$0, -152(%rbp)
 	subq	$8, %rsp
@@ -6879,2040 +6933,2061 @@
 	pushq	%rcx
 	pushq	%rbx
 	pushq	%rax
 	pushq	%rcx
 	pushq	%r13
 	pushq	%rcx
 	pushq	%r12
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
 	movq	-104(%rbp), %r14
-	jle	0xa049
+	jle	0x9a08
 	movq	%rax, %rcx
 	negq	%rcx
 	xorl	%edx, %edx
 	xorl	%r8d, %r8d
-	jmp	0xa00d
+	jmp	0x99cb
 	nopl	(%rax)
-	addq	$1, %r8
-	addq	$-1, %rdx
+	incq	%r8
+	decq	%rdx
 	cmpq	%rax, %r8
-	je	0xa049
+	je	0x9a08
 	movl	%r8d, %edi
 	xorl	%esi, %esi
-	jmp	0xa030
+	jmp	0x99ef
 	nopw	%cs:(%rax,%rax)
-	nop
 	movsd	%xmm0, (%rbx,%rdi,8)
-	addq	$-1, %rsi
+	decq	%rsi
 	addl	%eax, %edi
 	cmpq	%rsi, %rcx
-	je	0xa000
+	je	0x99c0
 	movslq	%edi, %rdi
 	xorpd	%xmm0, %xmm0
 	cmpq	%rsi, %rdx
-	je	0xa020
+	je	0x99e0
 	movsd	(%rbx,%rdi,8), %xmm0
 	divsd	(%r15,%rdi,8), %xmm0
-	jmp	0xa020
+	jmp	0x99e0
 	leaq	-56(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	movq	%rbx, %rsi
-	callq	0x13538 ## symbol stub for: _idamax
-	addl	$-1, %eax
+	callq	0x133b2 ## symbol stub for: _idamax
+	decl	%eax
 	cltq
 	movsd	(%rbx,%rax,8), %xmm0
-	andps	38454(%rip), %xmm0
+	andps	39640(%rip), %xmm0
 	movaps	%xmm0, -144(%rbp)
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movaps	-144(%rbp), %xmm0
 	addq	$120, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopw	(%rax,%rax)
+	nopw	%cs:(%rax,%rax)
 _Weighted_LassoSf_adaEN:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
-	subq	$504, %rsp
+	subq	$536, %rsp
 	movsd	%xmm3, -88(%rbp)
 	movsd	%xmm2, -520(%rbp)
 	movsd	%xmm1, -120(%rbp)
-	movsd	%xmm0, -224(%rbp)
+	movsd	%xmm0, -64(%rbp)
 	movq	%r9, %rbx
-	movq	%r8, -136(%rbp)
-	movq	%rcx, -272(%rbp)
-	movq	%rdx, -152(%rbp)
-	movq	%rsi, -64(%rbp)
-	movq	%rdi, -112(%rbp)
-	movslq	24(%rbp), %r15
+	movq	%r8, -144(%rbp)
+	movq	%rcx, -128(%rbp)
+	movq	%rdx, -176(%rbp)
+	movq	%rsi, -72(%rbp)
+	movq	%rdi, -288(%rbp)
 	movl	32(%rbp), %r14d
-	movl	%r14d, -104(%rbp)
-	movsd	%xmm4, -360(%rbp)
-	movl	%r15d, -72(%rbp)
+	movl	%r14d, -112(%rbp)
+	movl	24(%rbp), %eax
+	movsd	%xmm4, -344(%rbp)
+	movl	%eax, -80(%rbp)
+	movslq	%eax, %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -400(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -384(%rbp)
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -392(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -376(%rbp)
 	movl	%r14d, %eax
 	imull	%r15d, %eax
-	movl	%eax, -368(%rbp)
-	imull	%r15d, %r15d
-	movl	%r15d, -52(%rbp)
+	movl	%eax, -212(%rbp)
+	movl	%r15d, %r12d
+	imull	%r15d, %r12d
+	movl	%r12d, -52(%rbp)
 	movslq	%eax, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r14
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
-	movl	$1, -68(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r13
+	movl	$1, -76(%rbp)
 	movl	$1, -48(%rbp)
-	movl	$0, -184(%rbp)
-	leaq	-368(%rbp), %r13
-	leaq	-68(%rbp), %rdx
+	movl	$0, -208(%rbp)
+	leaq	-212(%rbp), %rdi
+	leaq	-76(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	movq	%r13, %rdi
-	movq	-272(%rbp), %rsi
+	movq	-128(%rbp), %rsi
 	movq	%r14, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r13, %rdi
-	movq	-136(%rbp), %rsi
-	leaq	-68(%rbp), %rdx
-	movq	%r12, %rcx
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-212(%rbp), %rdi
+	movq	-144(%rbp), %rsi
+	leaq	-76(%rbp), %rdx
+	movq	%r13, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	24(%rbp), %r8d
-	movq	%r14, -144(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	%r14, -160(%rbp)
 	movq	%r14, %rdi
-	movq	%r12, -288(%rbp)
-	movq	%r12, %rsi
-	movq	-400(%rbp), %rdx
-	movq	-392(%rbp), %rcx
-	movl	-104(%rbp), %r9d
+	movq	%r13, -304(%rbp)
+	movq	%r13, %rsi
+	movq	-384(%rbp), %rdx
+	movq	-376(%rbp), %rcx
+	movl	%r15d, %r8d
+	movl	-112(%rbp), %r9d
 	callq	_centerYX
 	cmpl	$5, 40(%rbp)
-	jl	0xa215
-	leaq	38625(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
+	jl	0x9bd7
+	leaq	39859(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
 	movsd	-88(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movl	-52(%rbp), %r15d
-	movsd	-224(%rbp), %xmm0
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-52(%rbp), %r12d
+	movslq	24(%rbp), %r15
+	movsd	-64(%rbp), %xmm0
 	mulsd	-88(%rbp), %xmm0
-	movsd	%xmm0, -176(%rbp)
-	movq	$0, -352(%rbp)
-	movslq	%r15d, %r14
+	movsd	%xmm0, -200(%rbp)
+	movq	$0, -336(%rbp)
+	movslq	%r12d, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -136(%rbp)
-	movslq	24(%rbp), %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -144(%rbp)
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -312(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
 	leaq	-52(%rbp), %r14
-	leaq	-68(%rbp), %r13
+	leaq	-76(%rbp), %r13
 	leaq	-48(%rbp), %r8
 	movq	%r14, %rdi
-	movq	-112(%rbp), %rsi
+	movq	-288(%rbp), %rsi
 	movq	%r13, %rdx
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-360(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-344(%rbp), %rsi
 	movq	%r14, %rdi
 	movq	%r15, %rdx
 	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movslq	-52(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r12
 	movq	%r14, %rdi
 	movq	%r15, -448(%rbp)
 	movq	%r15, %rsi
 	movq	%r13, %rdx
 	movq	%rax, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movsd	-224(%rbp), %xmm0
+	callq	0x1337c ## symbol stub for: _dcopy
+	movsd	-64(%rbp), %xmm0
 	addsd	%xmm0, %xmm0
 	subsd	-120(%rbp), %xmm0
 	mulsd	-88(%rbp), %xmm0
-	movsd	%xmm0, -544(%rbp)
-	leaq	-544(%rbp), %rsi
+	movsd	%xmm0, -568(%rbp)
+	leaq	-568(%rbp), %rsi
 	movq	%r14, %rdi
-	movq	%r12, -416(%rbp)
+	movq	%r12, -408(%rbp)
 	movq	%r12, %rdx
 	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	$0, -480(%rbp)
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	$0, -456(%rbp)
 	movslq	24(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	24(%rbp), %rdi
-	leaq	-480(%rbp), %rsi
-	leaq	-184(%rbp), %rdx
-	movq	%rax, -240(%rbp)
+	leaq	-456(%rbp), %rsi
+	leaq	-208(%rbp), %rdx
+	movq	%rax, -264(%rbp)
 	movq	%rax, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %r15d
 	testl	%r15d, %r15d
-	jle	0xa44a
+	jle	0x9e05
 	xorl	%r14d, %r14d
-	movsd	37584(%rip), %xmm3
-	movapd	37688(%rip), %xmm4
-	leaq	-72(%rbp), %r12
-	jmp	0xa3bb
-	nop
+	movsd	38786(%rip), %xmm2
+	movapd	38874(%rip), %xmm3
+	leaq	-80(%rbp), %r12
+	jmp	0x9d7a
+	nopl	(%rax)
 	subl	%r15d, %eax
-	movl	%eax, -76(%rbp)
-	movq	-136(%rbp), %rax
+	movl	%eax, -100(%rbp)
+	movq	-144(%rbp), %rax
 	leaq	(%rax,%r14,8), %rsi
 	leaq	24(%rbp), %rdi
 	movq	%r12, %rdx
-	callq	0x134f6 ## symbol stub for: _dasum
-	movapd	37643(%rip), %xmm4
-	movsd	37523(%rip), %xmm3
+	callq	0x13370 ## symbol stub for: _dasum
+	movapd	38827(%rip), %xmm3
+	movsd	38723(%rip), %xmm2
 	movq	-312(%rbp), %rax
 	movsd	%xmm0, (%rax,%r14,8)
-	addq	$1, %r14
+	incq	%r14
 	movslq	24(%rbp), %r15
 	cmpq	%r15, %r14
-	jge	0xa44a
+	jge	0x9e05
 	testl	%r15d, %r15d
-	movq	-416(%rbp), %rdi
-	jle	0xa376
-	movapd	%xmm3, %xmm0
-	subsd	-360(%rbp), %xmm0
-	mulsd	-176(%rbp), %xmm0
+	movq	-408(%rbp), %rdi
+	jle	0x9d36
+	movapd	%xmm2, %xmm0
+	subsd	-344(%rbp), %xmm0
+	xorpd	38742(%rip), %xmm0
+	mulsd	-200(%rbp), %xmm0
 	movl	%r15d, %ecx
 	movl	%r14d, %eax
 	xorl	%edx, %edx
-	jmp	0xa41c
-	nopw	%cs:(%rax,%rax)
-	nop
-	movq	-64(%rbp), %rsi
+	jmp	0x9ddb
+	nopl	(%rax)
+	movq	-72(%rbp), %rsi
 	movq	$0, (%rsi,%rax,8)
 	xorpd	%xmm1, %xmm1
-	movq	-136(%rbp), %rsi
+	movq	-144(%rbp), %rsi
 	movsd	%xmm1, (%rsi,%rax,8)
-	addq	$1, %rdx
+	incq	%rdx
 	addl	%r15d, %eax
 	cmpq	%rdx, %rcx
-	je	0xa370
+	je	0x9d30
 	cltq
-	movsd	(%rbx,%rax,8), %xmm1
-	movq	-64(%rbp), %rsi
-	movsd	(%rsi,%rax,8), %xmm2
-	mulsd	%xmm0, %xmm2
-	subsd	%xmm2, %xmm1
-	andpd	%xmm4, %xmm1
+	movq	-72(%rbp), %rsi
+	movsd	(%rsi,%rax,8), %xmm1
+	mulsd	%xmm0, %xmm1
+	addsd	(%rbx,%rax,8), %xmm1
+	andpd	%xmm3, %xmm1
 	ucomisd	(%rdi,%rax,8), %xmm1
-	jb	0xa3f0
-	movapd	%xmm3, %xmm1
+	jb	0x9db0
+	movapd	%xmm2, %xmm1
 	cmpq	%rdx, %r14
-	jne	0xa400
-	jmp	0xa3f0
+	jne	0x9dc0
+	jmp	0x9db0
 	movslq	%r15d, %rbx
 	movb	$78, -41(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -248(%rbp)
 	movslq	-52(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -304(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -152(%rbp)
 	movslq	32(%rbp), %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rbx, %rcx
-	movq	%rax, -336(%rbp)
+	movq	%rax, -328(%rbp)
 	testl	%ecx, %ecx
-	movq	%r12, -296(%rbp)
-	jle	0xa58e
+	jle	0x9f36
 	xorl	%ebx, %ebx
-	movq	-288(%rbp), %r12
-	movq	-144(%rbp), %r14
+	movq	-304(%rbp), %r12
+	movq	-160(%rbp), %r14
 	leaq	24(%rbp), %r13
-	nopw	%cs:(%rax,%rax)
-	nop
+	nopl	(%rax)
 	leaq	32(%rbp), %r15
 	movq	%r15, %rdi
 	movq	%r12, %rsi
 	movq	%r13, %rdx
 	movq	%r14, %rcx
 	movq	%r13, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	%xmm0, -88(%rbp)
 	movq	%r15, %rdi
 	movq	%r12, %rsi
 	movq	%r13, %rdx
 	movq	%r12, %rcx
 	movq	%r13, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	-88(%rbp), %xmm1
 	divsd	%xmm0, %xmm1
-	movq	-296(%rbp), %rax
+	movq	-248(%rbp), %rax
 	movsd	%xmm1, (%rax,%rbx,8)
 	movl	24(%rbp), %eax
 	imull	%ebx, %eax
 	cltq
-	movq	-304(%rbp), %rcx
+	movq	-152(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r10
-	movsd	37135(%rip), %xmm1
+	movsd	38351(%rip), %xmm1
 	divsd	%xmm0, %xmm1
 	movsd	%xmm1, -96(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	movq	%r13, %rsi
 	movq	%r15, %rdx
 	leaq	-96(%rbp), %rcx
-	movq	-144(%rbp), %r8
-	leaq	-72(%rbp), %r9
+	movq	-160(%rbp), %r8
+	leaq	-80(%rbp), %r9
 	leaq	-48(%rbp), %rax
 	pushq	%rax
 	pushq	%r10
-	leaq	-352(%rbp), %rax
+	leaq	-336(%rbp), %rax
 	pushq	%rax
 	pushq	%r13
 	pushq	%r12
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	addq	$1, %rbx
+	incq	%rbx
 	movl	24(%rbp), %r15d
 	movslq	%r15d, %rcx
 	addq	$8, %r14
 	addq	$8, %r12
 	cmpq	%rcx, %rbx
-	jl	0xa4c0
+	jl	0x9e70
 	movslq	32(%rbp), %r14
-	leaq	-68(%rbp), %r13
-	movq	-296(%rbp), %r12
+	leaq	-76(%rbp), %r13
 	movl	$8, %esi
 	movq	%rcx, %rbx
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -440(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -328(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -432(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -320(%rbp)
 	leal	1(%r15), %eax
 	imull	%r15d, %eax
-	movl	%eax, -76(%rbp)
-	movslq	%eax, %rbx
+	movl	%eax, -100(%rbp)
+	movslq	%eax, %r14
 	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -232(%rbp)
+	movq	%r14, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -296(%rbp)
 	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -280(%rbp)
+	movq	%r14, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -400(%rbp)
 	movl	$8, %esi
-	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -408(%rbp)
+	movq	%r14, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -392(%rbp)
 	xorl	%eax, %eax
 	movl	16(%rbp), %ecx
 	testl	%ecx, %ecx
 	cmovlel	%eax, %ecx
-	movl	%ecx, -180(%rbp)
+	movl	%ecx, -204(%rbp)
 	xorl	%esi, %esi
-	leaq	-48(%rbp), %rbx
-	movq	-304(%rbp), %r14
-	jmp	0xa65b
+	leaq	-48(%rbp), %r12
+	movq	-248(%rbp), %r14
+	movq	-152(%rbp), %r15
+	jmp	0xa018
 	nopw	%cs:(%rax,%rax)
-	movl	-364(%rbp), %esi
-	addl	$1, %esi
-	movsd	36879(%rip), %xmm0
+	movl	-348(%rbp), %esi
+	incl	%esi
+	movsd	38104(%rip), %xmm0
 	ucomisd	%xmm1, %xmm0
-	ja	0xb23b
-	cmpl	-180(%rbp), %esi
-	je	0xb235
-	movl	%esi, -364(%rbp)
+	movq	-248(%rbp), %r14
+	movq	-152(%rbp), %r15
+	ja	0xac32
+	cmpl	-204(%rbp), %esi
+	je	0xac2c
+	movl	%esi, -348(%rbp)
 	leaq	-52(%rbp), %rdi
-	movq	-64(%rbp), %rsi
+	movq	-72(%rbp), %rsi
 	movq	%r13, %rdx
-	movq	-232(%rbp), %r15
-	movq	%r15, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	-296(%rbp), %rbx
+	movq	%rbx, %rcx
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-52(%rbp), %rax
-	leaq	(%r15,%rax,8), %rcx
+	leaq	(%rbx,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
+	movq	-176(%rbp), %rsi
 	movq	%r13, %rdx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	xorpd	%xmm1, %xmm1
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
-	jle	0xb120
-	xorl	%r15d, %r15d
-	jmp	0xa70b
-	nopl	(%rax)
-	movq	-64(%rbp), %rax
-	leaq	(%rax,%r15,8), %rcx
+	jle	0xab20
+	xorl	%ebx, %ebx
+	jmp	0xa0c9
+	nopl	(%rax,%rax)
+	movq	-72(%rbp), %rax
+	leaq	(%rax,%rbx,8), %rcx
 	leaq	24(%rbp), %rdi
-	leaq	-480(%rbp), %rsi
-	leaq	-184(%rbp), %rdx
-	leaq	-72(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movsd	(%r12,%r15,8), %xmm0
-	movq	-152(%rbp), %rax
-	movsd	%xmm0, (%rax,%r15,8)
-	addq	$1, %r15
+	leaq	-456(%rbp), %rsi
+	leaq	-208(%rbp), %rdx
+	leaq	-80(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movsd	(%r14,%rbx,8), %xmm0
+	movq	-176(%rbp), %rax
+	movsd	%xmm0, (%rax,%rbx,8)
+	incq	%rbx
 	movslq	24(%rbp), %rax
-	cmpq	%rax, %r15
+	cmpq	%rax, %rbx
 	xorpd	%xmm1, %xmm1
-	jge	0xb120
+	jge	0xab20
 	movq	-312(%rbp), %rcx
-	movsd	(%rcx,%r15,8), %xmm0
+	movsd	(%rcx,%rbx,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0xa6c0
+	jbe	0xa080
 	cmpl	$7, 40(%rbp)
-	jl	0xa73c
-	leaq	37373(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating gene %d \n"
-	movl	%r15d, %esi
+	jl	0xa0f8
+	leaq	39775(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating Node %d \n"
+	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	xorpd	%xmm1, %xmm1
 	movl	24(%rbp), %eax
-	movq	-240(%rbp), %rcx
+	movq	-264(%rbp), %rcx
 	movabsq	$4607182418800017408, %rdx
-	movq	%rdx, (%rcx,%r15,8)
-	movq	-64(%rbp), %rcx
-	leaq	(%rcx,%r15,8), %rcx
-	movq	%rcx, -472(%rbp)
+	movq	%rdx, (%rcx,%rbx,8)
 	testl	%eax, %eax
-	jle	0xb0a0
+	leaq	24(%rbp), %r12
+	movq	%rbx, -64(%rbp)
+	jle	0xaaa0
 	movl	%eax, %ecx
-	imull	%r15d, %ecx
+	imull	%ebx, %ecx
 	movslq	%ecx, %rcx
 	movq	48(%rbp), %rdx
-	leaq	(%rdx,%rcx,8), %r12
-	movq	-288(%rbp), %rcx
-	leaq	(%rcx,%r15,8), %rcx
+	leaq	(%rdx,%rcx,8), %rcx
+	movq	%rcx, -552(%rbp)
+	movq	-72(%rbp), %rcx
+	leaq	(%rcx,%rbx,8), %rcx
+	movq	%rcx, -536(%rbp)
+	movq	-304(%rbp), %rcx
+	leaq	(%rcx,%rbx,8), %rcx
 	movq	%rcx, -528(%rbp)
-	movl	%r15d, %ecx
+	movl	%ebx, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
-	leaq	(%rdx,%rcx,8), %rbx
-	movq	-144(%rbp), %rsi
+	leaq	(%rdx,%rcx,8), %rcx
+	movq	%rcx, -544(%rbp)
+	movq	-160(%rbp), %rsi
 	xorl	%r14d, %r14d
-	movq	%r12, -464(%rbp)
-	movq	%rbx, -456(%rbp)
-	movq	%r15, -344(%rbp)
-	jmp	0xa82e
-	movapd	-224(%rbp), %xmm2
-	movsd	-168(%rbp), %xmm0
-	movq	-432(%rbp), %rcx
-	movq	-64(%rbp), %rax
-	movsd	%xmm4, (%rax,%rcx,8)
-	subsd	%xmm4, %xmm0
-	mulsd	%xmm0, %xmm2
-	movsd	36423(%rip), %xmm0
-	addsd	%xmm0, %xmm2
-	divsd	%xmm2, %xmm0
-	movsd	%xmm0, -536(%rbp)
-	leaq	24(%rbp), %rdi
-	leaq	-536(%rbp), %rsi
-	movq	%r12, %rdx
+	jmp	0xa1eb
+	movsd	-192(%rbp), %xmm1
+	movapd	-288(%rbp), %xmm3
+	movq	-424(%rbp), %rcx
+	movq	-72(%rbp), %rax
+	movsd	%xmm5, (%rax,%rcx,8)
+	subsd	%xmm5, %xmm1
+	mulsd	%xmm3, %xmm1
+	movsd	37628(%rip), %xmm0
+	addsd	%xmm0, %xmm1
+	divsd	%xmm1, %xmm0
+	movsd	%xmm0, -560(%rbp)
+	movq	%r12, %rdi
+	leaq	-560(%rbp), %rsi
+	movq	-552(%rbp), %rdx
 	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	-88(%rbp), %rsi
 	movl	24(%rbp), %eax
 	xorpd	%xmm1, %xmm1
-	addq	$1, %r14
+	incq	%r14
 	movslq	%eax, %rcx
 	addq	$8, %rsi
 	cmpq	%rcx, %r14
-	jge	0xb0a0
+	jge	0xaaa0
 	movl	%r14d, %ecx
 	imull	%eax, %ecx
-	addl	%r15d, %ecx
+	addl	%ebx, %ecx
 	movslq	%ecx, %rcx
-	movq	-136(%rbp), %rdx
+	movq	-144(%rbp), %rdx
 	movsd	(%rdx,%rcx,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0xa81a
-	movsd	(%rbx,%r14,8), %xmm2
-	movq	-64(%rbp), %rax
-	movsd	(%rax,%rcx,8), %xmm0
-	movapd	%xmm0, %xmm4
-	cmpq	%r14, %r15
+	jbe	0xa1d8
+	movq	-544(%rbp), %rax
+	movsd	(%rax,%r14,8), %xmm3
+	movq	-72(%rbp), %rax
+	movsd	(%rax,%rcx,8), %xmm1
+	movapd	%xmm1, %xmm5
+	cmpq	%r14, %rbx
 	movq	%rsi, -88(%rbp)
-	je	0xa7d9
-	movsd	%xmm0, -168(%rbp)
+	je	0xa194
+	movsd	%xmm1, -192(%rbp)
 	leaq	32(%rbp), %rdi
-	leaq	24(%rbp), %rbx
-	movq	%rbx, %rdx
-	movq	-336(%rbp), %rcx
+	movq	%r12, %rdx
+	movq	-328(%rbp), %rcx
 	movq	%r13, %r8
-	movapd	%xmm2, -224(%rbp)
-	callq	0x13502 ## symbol stub for: _dcopy
+	movapd	%xmm3, -288(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	imull	%r14d, %eax
-	addl	%r15d, %eax
+	addl	%ebx, %eax
 	cltq
 	movq	-448(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	mulsd	-176(%rbp), %xmm0
+	mulsd	-200(%rbp), %xmm0
 	movsd	%xmm0, -120(%rbp)
-	movq	%rbx, %rdi
-	movq	-472(%rbp), %rsi
-	leaq	-72(%rbp), %rdx
+	movq	%r12, %rdi
+	movq	-536(%rbp), %rsi
+	leaq	-80(%rbp), %rdx
 	movq	-320(%rbp), %r12
 	movq	%r12, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -96(%rbp)
 	leaq	24(%rbp), %rdi
 	leaq	-96(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, (%r12,%r14,8)
 	leaq	24(%rbp), %rdi
-	movq	-240(%rbp), %rsi
+	movq	-264(%rbp), %rsi
 	movq	%r13, %rdx
-	movq	-328(%rbp), %r15
+	movq	-432(%rbp), %r15
 	movq	%r15, %rcx
 	movq	%r13, %rbx
 	leaq	-48(%rbp), %r13
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -96(%rbp)
 	leaq	24(%rbp), %rdi
 	leaq	-96(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	%rbx, %rcx
 	movq	%r15, %r8
 	movq	%r13, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	leaq	32(%rbp), %r12
 	movq	%r12, %rdi
 	movq	-528(%rbp), %rsi
 	leaq	24(%rbp), %rdx
 	movq	-440(%rbp), %r13
 	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	-152(%rbp), %rax
-	movq	-344(%rbp), %rcx
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	-176(%rbp), %rax
+	movq	-64(%rbp), %rcx
 	movsd	(%rax,%rcx,8), %xmm0
-	xorpd	36095(%rip), %xmm0
+	xorpd	37284(%rip), %xmm0
 	movlpd	%xmm0, -96(%rbp)
 	movq	%r12, %rdi
 	leaq	-96(%rbp), %rsi
 	movq	%r13, %rdx
 	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movb	$84, -41(%rbp)
 	movabsq	$4607182418800017408, %rax
-	movq	%rax, -352(%rbp)
+	movq	%rax, -336(%rbp)
 	movq	%rax, -96(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
 	movq	%r12, %rdx
-	movq	%r12, %r15
 	leaq	-96(%rbp), %rcx
-	movq	-144(%rbp), %r8
-	leaq	-72(%rbp), %r9
+	movq	-160(%rbp), %r8
+	leaq	-80(%rbp), %r9
 	leaq	-48(%rbp), %r12
 	pushq	%r12
 	pushq	%r13
-	leaq	-352(%rbp), %rax
+	leaq	-336(%rbp), %rax
 	pushq	%rax
 	pushq	%rbx
-	pushq	-328(%rbp)
-	callq	0x13514 ## symbol stub for: _dgemv
+	pushq	%r15
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	movq	%r15, %rdi
-	movq	-336(%rbp), %r15
+	leaq	32(%rbp), %rdi
+	movq	-328(%rbp), %r15
 	movq	%r15, %rsi
 	movq	%rbx, %rdx
 	movq	%r15, %rcx
 	movq	%r12, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	35851(%rip), %xmm1
-	subsd	-360(%rbp), %xmm1
-	mulsd	-176(%rbp), %xmm1
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	37062(%rip), %xmm1
+	subsd	-344(%rbp), %xmm1
+	mulsd	-200(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
-	movsd	%xmm1, -112(%rbp)
+	movsd	%xmm1, -128(%rbp)
 	leaq	32(%rbp), %rdi
 	movq	%r15, %rsi
 	movq	%rbx, %rdx
 	movq	%r13, %rcx
 	movq	%r12, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movapd	-224(%rbp), %xmm2
-	movapd	%xmm0, %xmm8
-	movapd	%xmm2, %xmm0
-	andpd	35892(%rip), %xmm0
-	movsd	35788(%rip), %xmm1
-	ucomisd	%xmm0, %xmm1
-	jbe	0xaaf7
+	callq	0x13382 ## symbol stub for: _ddot
+	movapd	-288(%rbp), %xmm3
+	movapd	%xmm3, %xmm2
+	andpd	37092(%rip), %xmm2
+	movsd	37004(%rip), %xmm1
+	ucomisd	%xmm2, %xmm1
+	jbe	0xa49e
 	cmpl	$8, 40(%rbp)
-	movq	-344(%rbp), %r15
-	jl	0xaaaf
-	leaq	36531(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
-	movl	%r15d, %esi
+	jl	0xa457
+	leaq	37786(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
+	movq	-64(%rbp), %rsi
 	movl	%r14d, %edx
 	xorl	%eax, %eax
-	movsd	%xmm8, -104(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-104(%rbp), %xmm8
-	movapd	-224(%rbp), %xmm2
-	movapd	%xmm8, %xmm4
+	movsd	%xmm0, -112(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-112(%rbp), %xmm0
+	movapd	-288(%rbp), %xmm3
+	movapd	%xmm0, %xmm5
 	movsd	-120(%rbp), %xmm1
-	subsd	%xmm1, %xmm4
-	movsd	-112(%rbp), %xmm3
-	divsd	%xmm3, %xmm4
-	xorpd	%xmm0, %xmm0
-	ucomisd	%xmm0, %xmm4
-	leaq	-68(%rbp), %r13
-	movq	-464(%rbp), %r12
-	movq	-456(%rbp), %rbx
-	jbe	0xad89
+	subsd	%xmm1, %xmm5
+	movsd	-128(%rbp), %xmm2
+	divsd	%xmm2, %xmm5
+	xorpd	%xmm4, %xmm4
+	ucomisd	%xmm4, %xmm5
+	leaq	-76(%rbp), %r13
+	movq	-152(%rbp), %r15
+	leaq	24(%rbp), %r12
+	jbe	0xa6e3
 	movl	24(%rbp), %eax
 	imull	%r14d, %eax
-	addl	%r15d, %eax
+	movq	-64(%rbp), %rbx
+	addl	%ebx, %eax
 	cltq
-	jmp	0xadac
+	jmp	0xa708
 	cmpl	$8, 40(%rbp)
-	movq	-344(%rbp), %r15
-	movsd	%xmm8, -104(%rbp)
-	jl	0xab2c
-	leaq	36458(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
-	movl	%r15d, %esi
+	movq	-64(%rbp), %rbx
+	movsd	%xmm0, -112(%rbp)
+	jl	0xa4cd
+	leaq	38828(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with Node %d.\tQuadratic equation\n"
+	movl	%ebx, %esi
 	movl	%r14d, %edx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-104(%rbp), %xmm8
-	movapd	-224(%rbp), %xmm2
-	movsd	35579(%rip), %xmm10
-	movapd	%xmm10, %xmm11
-	divsd	%xmm2, %xmm11
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-112(%rbp), %xmm0
+	movapd	-288(%rbp), %xmm3
+	movsd	36811(%rip), %xmm2
+	movapd	%xmm2, %xmm4
+	divsd	%xmm3, %xmm4
 	movl	24(%rbp), %eax
 	imull	%r14d, %eax
-	addl	%r15d, %eax
+	addl	%ebx, %eax
 	movslq	%eax, %rcx
-	movq	-64(%rbp), %rax
-	movq	%rcx, -432(%rbp)
-	addsd	(%rax,%rcx,8), %xmm11
-	movsd	-112(%rbp), %xmm4
-	movapd	%xmm4, %xmm9
-	mulsd	%xmm11, %xmm9
-	movapd	%xmm8, %xmm1
-	addsd	%xmm9, %xmm1
-	movsd	-120(%rbp), %xmm0
-	subsd	%xmm0, %xmm1
-	movapd	%xmm8, %xmm2
-	subsd	%xmm0, %xmm2
-	cvtsi2sdl	32(%rbp), %xmm3
-	mulsd	%xmm11, %xmm2
-	mulsd	-520(%rbp), %xmm3
-	movsd	%xmm3, -160(%rbp)
-	subsd	%xmm3, %xmm2
-	movapd	%xmm1, %xmm12
-	movapd	%xmm1, %xmm7
-	movapd	%xmm0, %xmm6
-	addsd	%xmm0, %xmm6
-	addsd	%xmm1, %xmm6
-	mulsd	%xmm1, %xmm1
-	movapd	%xmm4, %xmm3
-	movsd	35453(%rip), %xmm5
-	mulsd	%xmm5, %xmm3
-	mulsd	%xmm2, %xmm3
-	subsd	%xmm3, %xmm1
-	movapd	%xmm4, %xmm2
-	addsd	%xmm4, %xmm2
-	movapd	%xmm10, %xmm4
-	divsd	%xmm2, %xmm4
-	xorps	%xmm2, %xmm2
-	sqrtsd	%xmm1, %xmm2
-	addsd	%xmm2, %xmm12
-	mulsd	%xmm4, %xmm12
-	movapd	%xmm12, -208(%rbp)
-	subsd	%xmm2, %xmm7
-	movapd	%xmm4, -272(%rbp)
-	mulsd	%xmm4, %xmm7
-	movapd	%xmm7, -512(%rbp)
-	subsd	%xmm9, %xmm8
-	mulsd	%xmm5, %xmm0
-	mulsd	%xmm0, %xmm8
-	addsd	%xmm1, %xmm8
+	movq	-72(%rbp), %rax
+	movq	%rcx, -424(%rbp)
+	addsd	(%rax,%rcx,8), %xmm4
+	movsd	-128(%rbp), %xmm7
+	movapd	%xmm7, %xmm3
+	mulsd	%xmm4, %xmm3
+	movsd	%xmm3, -256(%rbp)
+	addsd	%xmm0, %xmm3
+	movsd	-120(%rbp), %xmm6
+	subsd	%xmm6, %xmm3
 	xorps	%xmm1, %xmm1
-	sqrtsd	%xmm8, %xmm1
-	movsd	%xmm6, -248(%rbp)
-	movapd	%xmm6, %xmm0
-	movsd	%xmm1, -424(%rbp)
+	cvtsi2sdl	32(%rbp), %xmm1
+	subsd	%xmm6, %xmm0
+	mulsd	-520(%rbp), %xmm1
+	movsd	%xmm1, -184(%rbp)
+	mulsd	%xmm4, %xmm0
 	subsd	%xmm1, %xmm0
-	movapd	%xmm0, -384(%rbp)
-	movapd	%xmm11, -496(%rbp)
-	movapd	%xmm11, %xmm0
-	andpd	35381(%rip), %xmm0
-	movsd	35293(%rip), %xmm1
-	addsd	%xmm1, %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-160(%rbp), %xmm10
-	movapd	%xmm0, %xmm11
-	mulsd	%xmm10, %xmm11
-	xorpd	%xmm4, %xmm4
-	movapd	-208(%rbp), %xmm0
-	ucomisd	%xmm4, %xmm0
-	leaq	-68(%rbp), %r13
-	movq	-464(%rbp), %r12
-	movq	-456(%rbp), %rbx
-	jbe	0xadc2
-	movapd	-496(%rbp), %xmm0
-	subsd	-208(%rbp), %xmm0
-	movapd	35281(%rip), %xmm1
+	movapd	%xmm7, %xmm1
+	mulsd	36717(%rip), %xmm1
+	mulsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm5
+	mulsd	%xmm3, %xmm5
+	addsd	%xmm1, %xmm5
+	movapd	%xmm7, %xmm0
+	addsd	%xmm7, %xmm0
+	divsd	%xmm0, %xmm2
+	movsd	%xmm5, -496(%rbp)
+	xorps	%xmm0, %xmm0
+	sqrtsd	%xmm5, %xmm0
+	movsd	%xmm3, -168(%rbp)
+	movsd	%xmm0, -480(%rbp)
+	addsd	%xmm0, %xmm3
+	movapd	%xmm2, -368(%rbp)
+	mulsd	%xmm2, %xmm3
+	movapd	%xmm3, -240(%rbp)
+	movapd	%xmm6, %xmm0
+	mulsd	36630(%rip), %xmm0
+	movsd	%xmm0, -416(%rbp)
+	movapd	%xmm4, -512(%rbp)
+	movapd	%xmm4, %xmm0
+	andpd	36666(%rip), %xmm0
+	movsd	36602(%rip), %xmm1
+	addsd	%xmm1, %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-184(%rbp), %xmm9
+	movapd	%xmm0, %xmm13
+	mulsd	%xmm9, %xmm13
+	xorpd	%xmm5, %xmm5
+	movapd	-240(%rbp), %xmm0
+	ucomisd	%xmm5, %xmm0
+	leaq	-76(%rbp), %r13
+	movq	-152(%rbp), %r15
+	leaq	24(%rbp), %r12
+	jbe	0xa71e
+	movapd	-512(%rbp), %xmm0
+	subsd	-240(%rbp), %xmm0
+	movapd	36569(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	35189(%rip), %xmm0
-	movsd	%xmm11, -128(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-128(%rbp), %xmm11
-	movsd	-160(%rbp), %xmm10
-	xorpd	%xmm4, %xmm4
-	mulsd	%xmm10, %xmm0
-	movapd	-208(%rbp), %xmm2
+	addsd	36501(%rip), %xmm0
+	movsd	%xmm13, -136(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-136(%rbp), %xmm13
+	movsd	-184(%rbp), %xmm9
+	xorpd	%xmm5, %xmm5
+	movapd	-240(%rbp), %xmm2
 	movapd	%xmm2, %xmm1
 	mulsd	%xmm2, %xmm1
-	movsd	-112(%rbp), %xmm8
-	mulsd	%xmm8, %xmm1
-	mulsd	35127(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movsd	-104(%rbp), %xmm0
-	mulsd	%xmm2, %xmm0
+	mulsd	-128(%rbp), %xmm1
+	mulsd	36444(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	35170(%rip), %xmm1
-	mulsd	-120(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	ucomisd	%xmm11, %xmm0
-	xorpd	%xmm1, %xmm1
-	movapd	-272(%rbp), %xmm6
-	movapd	-384(%rbp), %xmm2
-	movapd	-512(%rbp), %xmm3
-	movsd	-248(%rbp), %xmm5
-	movsd	-424(%rbp), %xmm7
-	jbe	0xadee
-	movapd	-208(%rbp), %xmm4
-	movapd	%xmm0, %xmm11
-	jmp	0xadee
-	addsd	%xmm8, %xmm1
-	movapd	%xmm1, %xmm4
-	divsd	%xmm3, %xmm4
+	movsd	-112(%rbp), %xmm10
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm2, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm2, %xmm0
+	andpd	36452(%rip), %xmm0
+	movsd	-120(%rbp), %xmm8
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	xorpd	%xmm11, %xmm11
+	movq	-64(%rbp), %rbx
+	movapd	-368(%rbp), %xmm7
+	movsd	-168(%rbp), %xmm12
+	movsd	-480(%rbp), %xmm0
+	jbe	0xa74c
+	movapd	-240(%rbp), %xmm5
+	movapd	%xmm1, %xmm13
+	jmp	0xa74c
+	addsd	%xmm0, %xmm1
+	movapd	%xmm1, %xmm5
+	divsd	%xmm2, %xmm5
 	movl	24(%rbp), %eax
 	imull	%r14d, %eax
-	addl	%r15d, %eax
-	ucomisd	%xmm4, %xmm0
+	movq	-64(%rbp), %rbx
+	addl	%ebx, %eax
+	ucomisd	%xmm5, %xmm4
 	cltq
-	jbe	0xb075
-	movq	-64(%rbp), %rcx
-	movsd	%xmm4, (%rcx,%rax,8)
-	movsd	-168(%rbp), %xmm0
-	jmp	0xa7d9
-	xorpd	%xmm1, %xmm1
-	movapd	-272(%rbp), %xmm6
-	movapd	-384(%rbp), %xmm2
-	movapd	-512(%rbp), %xmm3
-	movsd	-248(%rbp), %xmm5
-	movsd	-424(%rbp), %xmm7
-	addsd	%xmm7, %xmm5
-	mulsd	%xmm6, %xmm2
-	ucomisd	%xmm1, %xmm3
-	movapd	%xmm2, -384(%rbp)
-	jbe	0xaeda
-	movapd	-496(%rbp), %xmm0
-	subsd	%xmm3, %xmm0
-	movapd	34948(%rip), %xmm1
+	jbe	0xaa75
+	movq	-72(%rbp), %rcx
+	movsd	%xmm5, (%rcx,%rax,8)
+	movsd	-192(%rbp), %xmm1
+	jmp	0xa194
+	xorpd	%xmm11, %xmm11
+	movq	-64(%rbp), %rbx
+	movsd	-120(%rbp), %xmm8
+	movsd	-112(%rbp), %xmm10
+	movapd	-368(%rbp), %xmm7
+	movsd	-168(%rbp), %xmm12
+	movsd	-480(%rbp), %xmm0
+	movapd	%xmm12, %xmm2
+	subsd	%xmm0, %xmm2
+	mulsd	%xmm7, %xmm2
+	ucomisd	%xmm11, %xmm2
+	jbe	0xa850
+	movapd	-512(%rbp), %xmm0
+	subsd	%xmm2, %xmm0
+	movapd	36232(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	34856(%rip), %xmm0
-	movsd	%xmm4, -208(%rbp)
-	movsd	%xmm11, -128(%rbp)
-	movsd	%xmm5, -248(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-248(%rbp), %xmm5
-	movapd	-512(%rbp), %xmm3
-	movapd	-384(%rbp), %xmm2
-	movsd	-128(%rbp), %xmm11
-	movapd	-272(%rbp), %xmm6
-	movsd	-160(%rbp), %xmm10
-	movsd	-208(%rbp), %xmm4
-	movsd	-104(%rbp), %xmm9
-	movsd	-112(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
+	addsd	36164(%rip), %xmm0
+	movsd	%xmm5, -240(%rbp)
+	movsd	%xmm13, -136(%rbp)
+	movapd	%xmm2, -480(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-480(%rbp), %xmm3
+	movsd	-168(%rbp), %xmm12
+	movsd	-136(%rbp), %xmm13
+	movapd	-368(%rbp), %xmm7
+	movsd	-184(%rbp), %xmm9
+	movsd	-240(%rbp), %xmm5
+	movsd	-112(%rbp), %xmm10
+	movsd	-120(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
 	movapd	%xmm3, %xmm1
 	mulsd	%xmm3, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	34744(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm3, %xmm0
+	mulsd	-128(%rbp), %xmm1
+	mulsd	36053(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm3, %xmm1
-	andpd	34787(%rip), %xmm1
-	mulsd	-120(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0xaeda
-	movapd	%xmm3, %xmm4
-	movapd	%xmm0, %xmm11
-	mulsd	%xmm5, %xmm6
-	ucomisd	%xmm2, %xmm1
-	movapd	%xmm6, -272(%rbp)
-	jbe	0xafaa
-	movapd	-496(%rbp), %xmm0
-	subsd	%xmm2, %xmm0
-	movapd	34716(%rip), %xmm1
-	andpd	%xmm1, %xmm0
-	addsd	34624(%rip), %xmm0
-	movsd	%xmm4, -208(%rbp)
-	movsd	%xmm11, -128(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-384(%rbp), %xmm2
-	movsd	-128(%rbp), %xmm11
-	movapd	-272(%rbp), %xmm6
-	movsd	-160(%rbp), %xmm10
-	movsd	-208(%rbp), %xmm4
-	movsd	-104(%rbp), %xmm9
-	movsd	-112(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
-	movapd	%xmm2, %xmm1
-	mulsd	%xmm2, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	34536(%rip), %xmm1
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
 	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm2, %xmm0
+	movapd	%xmm3, %xmm0
+	andpd	36067(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	movsd	-256(%rbp), %xmm4
+	movsd	-496(%rbp), %xmm2
+	movsd	-416(%rbp), %xmm6
+	jbe	0xa868
+	movapd	%xmm3, %xmm5
+	movapd	%xmm1, %xmm13
+	jmp	0xa868
+	movsd	-256(%rbp), %xmm4
+	movsd	-496(%rbp), %xmm2
+	movsd	-416(%rbp), %xmm6
+	movapd	%xmm10, %xmm0
+	subsd	%xmm4, %xmm0
+	mulsd	%xmm0, %xmm6
+	addsd	%xmm2, %xmm6
+	movapd	%xmm8, %xmm0
+	addsd	%xmm8, %xmm0
+	addsd	%xmm12, %xmm0
+	xorps	%xmm2, %xmm2
+	sqrtsd	%xmm6, %xmm2
+	movapd	%xmm0, %xmm3
+	subsd	%xmm2, %xmm3
+	mulsd	%xmm7, %xmm3
+	ucomisd	%xmm3, %xmm11
+	jbe	0xa98f
+	movsd	%xmm0, -168(%rbp)
+	movapd	-512(%rbp), %xmm0
+	subsd	%xmm3, %xmm0
+	movapd	35902(%rip), %xmm1
+	andpd	%xmm1, %xmm0
+	addsd	35834(%rip), %xmm0
+	movsd	%xmm5, -240(%rbp)
+	movsd	%xmm13, -136(%rbp)
+	movsd	%xmm2, -256(%rbp)
+	movapd	%xmm3, -496(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-496(%rbp), %xmm3
+	movsd	-256(%rbp), %xmm2
+	movsd	-136(%rbp), %xmm13
+	movapd	-368(%rbp), %xmm7
+	movsd	-184(%rbp), %xmm9
+	movsd	-240(%rbp), %xmm5
+	movsd	-112(%rbp), %xmm10
+	movsd	-120(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
+	movapd	%xmm3, %xmm1
+	mulsd	%xmm3, %xmm1
+	mulsd	-128(%rbp), %xmm1
+	mulsd	35716(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	34579(%rip), %xmm1
-	mulsd	-120(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0xafaa
-	movapd	%xmm2, %xmm4
-	movapd	%xmm0, %xmm11
-	ucomisd	%xmm6, %xmm1
-	jbe	0xa7b9
-	movapd	-496(%rbp), %xmm1
-	subsd	%xmm6, %xmm1
-	movapd	34520(%rip), %xmm0
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	andpd	35730(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	movsd	-168(%rbp), %xmm0
+	ucomisd	%xmm13, %xmm1
+	jbe	0xa98f
+	movapd	%xmm3, %xmm5
+	movapd	%xmm1, %xmm13
+	addsd	%xmm2, %xmm0
+	mulsd	%xmm0, %xmm7
+	ucomisd	%xmm7, %xmm11
+	jbe	0xa174
+	movapd	-512(%rbp), %xmm1
+	subsd	%xmm7, %xmm1
+	movapd	35658(%rip), %xmm0
 	andpd	%xmm0, %xmm1
-	addsd	34428(%rip), %xmm1
+	addsd	35590(%rip), %xmm1
 	movapd	%xmm1, %xmm0
-	movsd	%xmm4, -208(%rbp)
-	movsd	%xmm11, -128(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-272(%rbp), %xmm3
-	movsd	-208(%rbp), %xmm4
-	movsd	-160(%rbp), %xmm2
-	mulsd	%xmm0, %xmm2
-	movapd	%xmm3, %xmm0
-	mulsd	%xmm3, %xmm0
-	movsd	-112(%rbp), %xmm1
+	movsd	%xmm5, -240(%rbp)
+	movapd	%xmm7, -368(%rbp)
+	movsd	%xmm13, -136(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-368(%rbp), %xmm4
+	movsd	-240(%rbp), %xmm5
+	movapd	%xmm4, %xmm1
+	mulsd	%xmm4, %xmm1
+	movsd	-128(%rbp), %xmm2
+	mulsd	%xmm1, %xmm2
+	mulsd	35523(%rip), %xmm2
+	movsd	-184(%rbp), %xmm1
 	mulsd	%xmm0, %xmm1
-	mulsd	34360(%rip), %xmm1
 	addsd	%xmm2, %xmm1
-	movsd	-104(%rbp), %xmm2
-	mulsd	%xmm3, %xmm2
-	addsd	%xmm1, %xmm2
-	movapd	%xmm3, %xmm0
-	andpd	34403(%rip), %xmm0
-	movsd	-120(%rbp), %xmm1
-	mulsd	%xmm0, %xmm1
-	subsd	%xmm1, %xmm2
-	ucomisd	-128(%rbp), %xmm2
-	movapd	-224(%rbp), %xmm2
-	movsd	-168(%rbp), %xmm0
-	movq	-432(%rbp), %rcx
-	jbe	0xa7d0
-	movapd	%xmm3, %xmm4
-	jmp	0xa7d0
-	movq	-64(%rbp), %rcx
+	movapd	%xmm1, %xmm0
+	movsd	-112(%rbp), %xmm1
+	mulsd	%xmm4, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm4, %xmm0
+	andpd	35526(%rip), %xmm0
+	movsd	-120(%rbp), %xmm2
+	mulsd	%xmm0, %xmm2
+	subsd	%xmm2, %xmm1
+	ucomisd	-136(%rbp), %xmm1
+	movsd	-192(%rbp), %xmm1
+	movapd	-288(%rbp), %xmm3
+	movq	-424(%rbp), %rcx
+	jbe	0xa18b
+	movapd	%xmm4, %xmm5
+	jmp	0xa18b
+	movq	-72(%rbp), %rcx
 	movq	$0, (%rcx,%rax,8)
-	xorpd	%xmm4, %xmm4
-	movsd	-168(%rbp), %xmm0
-	jmp	0xa7d9
+	xorpd	%xmm5, %xmm5
+	movsd	-192(%rbp), %xmm1
+	jmp	0xa194
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	leaq	24(%rbp), %r12
+	movq	-72(%rbp), %rax
+	leaq	(%rax,%rbx,8), %rsi
 	movq	%r12, %rdi
-	movq	-472(%rbp), %rsi
-	leaq	-72(%rbp), %rdx
+	leaq	-80(%rbp), %rdx
 	movq	-320(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
-	imull	%r15d, %eax
+	imull	-64(%rbp), %eax
 	cltq
-	movq	-304(%rbp), %r14
-	leaq	(%r14,%rax,8), %rcx
+	leaq	(%r15,%rax,8), %rcx
 	movq	%r12, %rdi
 	movq	%rbx, %rsi
+	movq	-64(%rbp), %rbx
 	movq	%r13, %rdx
-	leaq	-48(%rbp), %rbx
-	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movq	-296(%rbp), %r12
-	movsd	(%r12,%r15,8), %xmm1
+	leaq	-48(%rbp), %r12
+	movq	%r12, %r8
+	callq	0x13382 ## symbol stub for: _ddot
+	movq	-248(%rbp), %r14
+	movsd	(%r14,%rbx,8), %xmm1
 	subsd	%xmm0, %xmm1
-	movq	-152(%rbp), %rax
-	movsd	%xmm1, (%rax,%r15,8)
-	movq	-240(%rbp), %rax
-	movq	$0, (%rax,%r15,8)
-	jmp	0xa6f6
-	nop
+	movq	-176(%rbp), %rax
+	movsd	%xmm1, (%rax,%rbx,8)
+	movq	-264(%rbp), %rax
+	movq	$0, (%rax,%rbx,8)
+	jmp	0xa0b5
+	nopl	(%rax,%rax)
 	leaq	-52(%rbp), %rdi
-	movq	-64(%rbp), %rsi
+	movq	-72(%rbp), %rsi
 	movq	%r13, %rdx
-	movq	-280(%rbp), %r15
+	movq	-400(%rbp), %r15
 	movq	%r15, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	-52(%rbp), %rax
 	leaq	(%r15,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
+	movq	-176(%rbp), %rsi
 	movq	%r13, %rdx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	leal	1(%rax), %ecx
 	imull	%eax, %ecx
-	movl	%ecx, -76(%rbp)
+	movl	%ecx, -100(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -96(%rbp)
-	leaq	-76(%rbp), %rdi
-	movq	-232(%rbp), %rsi
+	leaq	-100(%rbp), %rdi
+	movq	-296(%rbp), %rbx
+	movq	%rbx, %rsi
 	movq	%r13, %rdx
-	movq	-408(%rbp), %r15
-	movq	%r15, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-76(%rbp), %rdi
+	movq	-392(%rbp), %r14
+	movq	%r14, %rcx
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-100(%rbp), %rdi
 	leaq	-96(%rbp), %rsi
-	movq	-280(%rbp), %rdx
+	movq	%r15, %rdx
 	movq	%r13, %rcx
-	movq	%r15, %r8
-	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	leaq	-76(%rbp), %rdi
-	movq	-232(%rbp), %rsi
+	movq	%r14, %r8
+	movq	%r12, %r9
+	callq	0x13376 ## symbol stub for: _daxpy
+	leaq	-100(%rbp), %rdi
+	movq	%rdi, %r15
+	movq	%rbx, %rsi
 	movq	%r13, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -224(%rbp)
-	leaq	-76(%rbp), %rdi
-	movq	%r15, %rsi
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -64(%rbp)
+	movq	%r15, %rdi
+	movq	%r14, %rsi
 	movq	%r13, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	movsd	%xmm0, -88(%rbp)
 	movl	24(%rbp), %edx
 	movq	48(%rbp), %rdi
-	movq	-64(%rbp), %rsi
+	movq	-72(%rbp), %rsi
 	callq	_UpdateIBinv
 	movsd	-88(%rbp), %xmm1
-	movsd	-224(%rbp), %xmm0
-	addsd	33850(%rip), %xmm0
+	movsd	-64(%rbp), %xmm0
+	addsd	34995(%rip), %xmm0
 	divsd	%xmm0, %xmm1
 	cmpl	$6, 40(%rbp)
-	jl	0xa640
-	leaq	34717(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
+	jl	0x9ff0
+	leaq	35894(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
 	movsd	%xmm1, -88(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-88(%rbp), %xmm1
-	jmp	0xa640
-	movl	-180(%rbp), %esi
+	jmp	0x9ff0
+	movl	-204(%rbp), %esi
 	cmpl	$5, 40(%rbp)
-	movq	-144(%rbp), %rbx
-	jl	0xb25e
-	leaq	34685(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
-	movsd	-176(%rbp), %xmm0
+	movq	-160(%rbp), %rbx
+	jl	0xac55
+	leaq	35862(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
+	movsd	-200(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movq	-400(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-392(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133c4 ## symbol stub for: _printf
+	movq	-384(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-376(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-288(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-136(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-304(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-144(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-416(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-336(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-240(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-440(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r15, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-408(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-328(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-264(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-440(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-432(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-320(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-232(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-280(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-408(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-296(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-400(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-392(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-448(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movsd	-176(%rbp), %xmm0
-	addq	$504, %rsp
+	callq	0x133ac ## symbol stub for: _free
+	movsd	-200(%rbp), %xmm0
+	addq	$536, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopw	%cs:(%rax,%rax)
-	nop
+	nopl	(%rax,%rax)
 _Weighted_LassoSf_MLf_adaEN:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
-	subq	$552, %rsp
-	movsd	%xmm3, -144(%rbp)
-	movsd	%xmm2, -536(%rbp)
-	movsd	%xmm1, -192(%rbp)
-	movsd	%xmm0, -128(%rbp)
-	movq	%r9, %r15
+	subq	$584, %rsp
+	movsd	%xmm3, -112(%rbp)
+	movsd	%xmm2, -552(%rbp)
+	movsd	%xmm1, -80(%rbp)
+	movsd	%xmm0, -160(%rbp)
+	movq	%r9, %r13
 	movq	%r8, -88(%rbp)
-	movq	%rcx, -96(%rbp)
-	movq	%rdx, -152(%rbp)
-	movq	%rsi, -136(%rbp)
-	movq	%rdi, -80(%rbp)
-	movslq	24(%rbp), %r13
-	movsd	%xmm4, -416(%rbp)
+	movq	%rcx, -192(%rbp)
+	movq	%rdx, -368(%rbp)
+	movq	%rsi, -144(%rbp)
+	movq	%rdi, -136(%rbp)
 	movl	32(%rbp), %ebx
-	imull	%r13d, %ebx
-	movl	%r13d, -68(%rbp)
-	movl	$8, %esi
-	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -496(%rbp)
+	movl	%ebx, -120(%rbp)
+	movl	24(%rbp), %eax
+	movsd	%xmm4, -464(%rbp)
+	movl	%eax, -68(%rbp)
+	movslq	%eax, %r15
 	movl	$8, %esi
-	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
-	movl	%ebx, -424(%rbp)
-	imull	%r13d, %r13d
-	movl	%r13d, -52(%rbp)
-	movslq	%ebx, %r13
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -520(%rbp)
 	movl	$8, %esi
-	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %rbx
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -408(%rbp)
+	movl	%ebx, %eax
+	imull	%r15d, %eax
+	movl	%eax, -292(%rbp)
+	movl	%r15d, %r12d
+	imull	%r15d, %r12d
+	movl	%r12d, -56(%rbp)
+	movslq	%eax, %rbx
 	movl	$8, %esi
-	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	%rbx, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r14
-	movl	$1, -56(%rbp)
+	movl	$8, %esi
+	movq	%rbx, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %rbx
 	movl	$1, -48(%rbp)
-	movl	$0, -296(%rbp)
-	leaq	-424(%rbp), %r13
-	leaq	-56(%rbp), %rdx
-	leaq	-48(%rbp), %r8
-	movq	%r13, %rdi
-	movq	-96(%rbp), %rsi
-	movq	%rbx, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r13, %rdi
-	movq	-88(%rbp), %rsi
-	leaq	-56(%rbp), %rdx
+	movl	$1, -52(%rbp)
+	movl	$0, -288(%rbp)
+	leaq	-292(%rbp), %rdi
+	leaq	-48(%rbp), %rdx
+	leaq	-52(%rbp), %r8
+	movq	-192(%rbp), %rsi
 	movq	%r14, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	24(%rbp), %r8d
-	movl	32(%rbp), %r9d
-	movq	%rbx, -160(%rbp)
-	movq	%rbx, %rdi
-	movq	%r14, -304(%rbp)
-	movq	%r14, %rsi
-	movq	-496(%rbp), %rdx
-	movq	%r12, -488(%rbp)
-	movq	%r12, %rcx
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-292(%rbp), %rdi
+	movq	-88(%rbp), %rsi
+	leaq	-48(%rbp), %rdx
+	movq	%rbx, %rcx
+	leaq	-52(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	%r14, -176(%rbp)
+	movq	%r14, %rdi
+	movq	%rbx, -328(%rbp)
+	movq	%rbx, %rsi
+	movq	-520(%rbp), %rdx
+	movq	-408(%rbp), %rcx
+	movl	%r15d, %r8d
+	movl	-120(%rbp), %r9d
 	callq	_centerYX
 	cmpl	$5, 40(%rbp)
-	jl	0xb4a5
-	leaq	33872(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
-	movsd	-144(%rbp), %xmm0
+	jl	0xaeaa
+	leaq	35040(%rip), %rdi ## literal pool for: "\t\t\t\tEnter Function: weighted_LassoSf. The maximum lambda is: %f\n\n"
+	movsd	-112(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-128(%rbp), %xmm0
-	mulsd	-144(%rbp), %xmm0
-	movsd	%xmm0, -280(%rbp)
-	movq	$0, -216(%rbp)
-	movslq	-52(%rbp), %r14
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-56(%rbp), %r12d
+	movslq	24(%rbp), %r15
+	movsd	-160(%rbp), %xmm0
+	mulsd	-112(%rbp), %xmm0
+	movsd	%xmm0, -264(%rbp)
+	movq	$0, -200(%rbp)
+	movslq	%r12d, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -88(%rbp)
-	movslq	24(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -200(%rbp)
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -256(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
-	leaq	-52(%rbp), %r14
-	leaq	-56(%rbp), %r13
-	leaq	-48(%rbp), %r8
+	leaq	-56(%rbp), %r14
+	leaq	-48(%rbp), %r12
+	leaq	-52(%rbp), %r8
 	movq	%r14, %rdi
-	movq	-80(%rbp), %rsi
-	movq	%r13, %rdx
+	movq	-136(%rbp), %rsi
+	movq	%r12, %rdx
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-416(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-464(%rbp), %rsi
 	movq	%r14, %rdi
 	movq	%rbx, %rdx
-	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movslq	-52(%rbp), %rdi
+	movq	%r12, %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
+	movslq	-56(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r15
 	movq	%r14, %rdi
-	movq	%rbx, -520(%rbp)
+	movq	%rbx, -544(%rbp)
 	movq	%rbx, %rsi
-	movq	%r13, %rdx
+	movq	%r12, %rdx
 	movq	%rax, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movsd	-128(%rbp), %xmm0
+	leaq	-52(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movsd	-160(%rbp), %xmm0
 	addsd	%xmm0, %xmm0
-	subsd	-192(%rbp), %xmm0
-	mulsd	-144(%rbp), %xmm0
-	movsd	%xmm0, -584(%rbp)
-	leaq	-584(%rbp), %rsi
+	subsd	-80(%rbp), %xmm0
+	mulsd	-112(%rbp), %xmm0
+	movsd	%xmm0, -616(%rbp)
+	leaq	-616(%rbp), %rsi
 	movq	%r14, %rdi
-	movq	%r12, -504(%rbp)
-	movq	%r12, %rdx
-	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	$0, -544(%rbp)
+	movq	%r15, -528(%rbp)
+	movq	%r15, %rdx
+	movq	%r12, %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	$0, -560(%rbp)
 	movslq	24(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	24(%rbp), %rdi
-	leaq	-544(%rbp), %rsi
-	leaq	-296(%rbp), %rdx
-	movq	%rax, -168(%rbp)
+	leaq	-560(%rbp), %rsi
+	leaq	-288(%rbp), %rdx
+	movq	%rax, -184(%rbp)
 	movq	%rax, %rcx
-	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %r14d
 	testl	%r14d, %r14d
-	jle	0xb6da
-	xorl	%r13d, %r13d
-	movsd	32831(%rip), %xmm3
-	movapd	32935(%rip), %xmm4
+	jle	0xb0e6
+	xorl	%r15d, %r15d
+	movsd	33964(%rip), %xmm2
+	movapd	34052(%rip), %xmm3
 	leaq	-68(%rbp), %r12
-	jmp	0xb644
-	nop
+	jmp	0xb053
+	nopw	%cs:(%rax,%rax)
 	subl	%r14d, %eax
 	movl	%eax, -72(%rbp)
-	leaq	(%rsi,%r13,8), %rsi
+	leaq	(%rsi,%r15,8), %rsi
 	leaq	24(%rbp), %rdi
 	movq	%r12, %rdx
-	callq	0x134f6 ## symbol stub for: _dasum
-	movapd	32898(%rip), %xmm4
-	movsd	32778(%rip), %xmm3
-	movq	-200(%rbp), %rax
-	movsd	%xmm0, (%rax,%r13,8)
-	addq	$1, %r13
+	callq	0x13370 ## symbol stub for: _dasum
+	movapd	34002(%rip), %xmm3
+	movsd	33898(%rip), %xmm2
+	movq	-256(%rbp), %rax
+	movsd	%xmm0, (%rax,%r15,8)
+	incq	%r15
 	movslq	24(%rbp), %r14
-	cmpq	%r14, %r13
-	jge	0xb6da
+	cmpq	%r14, %r15
+	jge	0xb0e6
 	testl	%r14d, %r14d
 	movq	-88(%rbp), %rsi
-	movq	-504(%rbp), %rdi
-	jle	0xb606
-	movapd	%xmm3, %xmm0
-	subsd	-416(%rbp), %xmm0
-	mulsd	-280(%rbp), %xmm0
+	movq	-528(%rbp), %rdi
+	jle	0xb016
+	movapd	%xmm2, %xmm0
+	subsd	-464(%rbp), %xmm0
+	xorpd	33913(%rip), %xmm0
+	mulsd	-264(%rbp), %xmm0
 	movl	%r14d, %ecx
-	movl	%r13d, %eax
+	movl	%r15d, %eax
 	xorl	%edx, %edx
-	jmp	0xb6a8
-	nopw	%cs:(%rax,%rax)
+	jmp	0xb0b7
 	nopl	(%rax)
-	movq	-136(%rbp), %rbx
+	movq	-144(%rbp), %rbx
 	movq	$0, (%rbx,%rax,8)
 	xorpd	%xmm1, %xmm1
 	movsd	%xmm1, (%rsi,%rax,8)
-	addq	$1, %rdx
+	incq	%rdx
 	addl	%r14d, %eax
 	cmpq	%rdx, %rcx
-	je	0xb600
+	je	0xb010
 	cltq
-	movsd	(%r15,%rax,8), %xmm1
-	movq	-136(%rbp), %rbx
-	movsd	(%rbx,%rax,8), %xmm2
-	mulsd	%xmm0, %xmm2
-	subsd	%xmm2, %xmm1
-	andpd	%xmm4, %xmm1
+	movq	-144(%rbp), %rbx
+	movsd	(%rbx,%rax,8), %xmm1
+	mulsd	%xmm0, %xmm1
+	addsd	(%r13,%rax,8), %xmm1
+	andpd	%xmm3, %xmm1
 	ucomisd	(%rdi,%rax,8), %xmm1
-	jb	0xb680
-	movapd	%xmm3, %xmm1
-	cmpq	%rdx, %r13
-	jne	0xb693
-	jmp	0xb680
+	jb	0xb090
+	movapd	%xmm2, %xmm1
+	cmpq	%rdx, %r15
+	jne	0xb0a3
+	jmp	0xb090
 	movslq	%r14d, %rbx
 	movb	$78, -41(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -264(%rbp)
-	movslq	-52(%rbp), %r15
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -240(%rbp)
+	movslq	-56(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -256(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r13
 	movslq	32(%rbp), %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rbx, %rcx
-	movq	%rax, -144(%rbp)
+	movq	%rax, -192(%rbp)
 	testl	%ecx, %ecx
-	jle	0xb818
+	movq	%r13, -248(%rbp)
+	jle	0xb227
 	xorl	%r15d, %r15d
-	movq	-304(%rbp), %r13
-	movq	-160(%rbp), %r12
+	movq	-328(%rbp), %r13
+	movq	-176(%rbp), %r12
 	leaq	24(%rbp), %rbx
 	nopw	%cs:(%rax,%rax)
-	nop
 	leaq	32(%rbp), %r14
 	movq	%r14, %rdi
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
 	movq	%r12, %rcx
 	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	%xmm0, -128(%rbp)
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	%xmm0, -112(%rbp)
 	movq	%r14, %rdi
 	movq	%r13, %rsi
 	movq	%rbx, %rdx
 	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	-128(%rbp), %xmm1
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	-112(%rbp), %xmm1
 	divsd	%xmm0, %xmm1
-	movq	-264(%rbp), %rax
+	movq	-240(%rbp), %rax
 	movsd	%xmm1, (%rax,%r15,8)
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	cltq
-	movq	-256(%rbp), %rcx
+	movq	-248(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r10
-	movsd	32381(%rip), %xmm1
+	movsd	33501(%rip), %xmm1
 	divsd	%xmm0, %xmm1
 	movsd	%xmm1, -64(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%r14, %rdx
 	leaq	-64(%rbp), %rcx
-	movq	-160(%rbp), %r8
+	movq	-176(%rbp), %r8
 	leaq	-68(%rbp), %r9
-	leaq	-48(%rbp), %rax
+	leaq	-52(%rbp), %rax
 	pushq	%rax
 	pushq	%r10
-	leaq	-216(%rbp), %rax
+	leaq	-200(%rbp), %rax
 	pushq	%rax
 	pushq	%rbx
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	addq	$1, %r15
+	incq	%r15
 	movl	24(%rbp), %r14d
 	movslq	%r14d, %rcx
 	addq	$8, %r12
 	addq	$8, %r13
 	cmpq	%rcx, %r15
-	jl	0xb750
-	movslq	-52(%rbp), %r15
+	jl	0xb160
+	movslq	-56(%rbp), %r15
 	movslq	32(%rbp), %r12
-	movq	56(%rbp), %r13
 	movl	$8, %esi
 	movq	%rcx, %rbx
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -568(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -600(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -400(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -440(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -392(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -432(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -288(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -272(%rbp)
 	leal	1(%r14), %eax
 	imull	%r14d, %eax
 	movl	%eax, -72(%rbp)
 	movslq	%eax, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -248(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -232(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -384(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -424(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -376(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -416(%rbp)
 	movl	16(%rbp), %eax
 	testl	%eax, %eax
 	movl	$0, %ecx
 	cmovgl	%eax, %ecx
-	movl	%ecx, -292(%rbp)
+	movl	%ecx, -284(%rbp)
 	xorl	%esi, %esi
-	movq	-136(%rbp), %r15
-	leaq	-48(%rbp), %rbx
-	jmp	0xb903
-	nopl	(%rax,%rax)
-	movl	-420(%rbp), %esi
-	addl	$1, %esi
-	movsd	32111(%rip), %xmm0
+	movq	-240(%rbp), %r12
+	movq	-144(%rbp), %r15
+	leaq	-48(%rbp), %r14
+	leaq	-52(%rbp), %r13
+	jmp	0xb31a
+	nopw	%cs:(%rax,%rax)
+	movl	-468(%rbp), %esi
+	incl	%esi
+	movsd	33224(%rip), %xmm0
 	ucomisd	%xmm1, %xmm0
-	movq	56(%rbp), %r13
-	leaq	-48(%rbp), %rbx
-	ja	0xc4f0
-	cmpl	-292(%rbp), %esi
-	je	0xc4ea
-	movl	%esi, -420(%rbp)
-	leaq	-52(%rbp), %rdi
+	ja	0xbf45
+	cmpl	-284(%rbp), %esi
+	je	0xbf3f
+	movl	%esi, -468(%rbp)
+	leaq	-56(%rbp), %rdi
 	movq	%r15, %rsi
-	leaq	-56(%rbp), %r13
-	movq	%r13, %rdx
-	movq	-248(%rbp), %r14
+	movq	%r14, %rdx
+	movq	-232(%rbp), %r14
 	movq	%r14, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movslq	-52(%rbp), %rax
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movslq	-56(%rbp), %rax
 	leaq	(%r14,%rax,8), %rcx
-	movq	-136(%rbp), %r14
+	leaq	-48(%rbp), %rdx
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
-	movq	%r13, %rdx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	-368(%rbp), %rsi
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	xorpd	%xmm1, %xmm1
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
 	movq	-88(%rbp), %rdx
-	movq	-200(%rbp), %r15
-	jle	0xc3d0
-	xorl	%r12d, %r12d
-	jmp	0xb9d2
-	nopl	(%rax)
-	leaq	(%r14,%r12,8), %rcx
+	jle	0xbe20
+	xorl	%ebx, %ebx
+	jmp	0xb3c9
+	nop
+	leaq	(%r15,%rbx,8), %rcx
 	leaq	24(%rbp), %rdi
-	leaq	-544(%rbp), %rsi
-	leaq	-296(%rbp), %rdx
+	leaq	-560(%rbp), %rsi
+	leaq	-288(%rbp), %rdx
 	leaq	-68(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	-264(%rbp), %rax
-	movsd	(%rax,%r12,8), %xmm0
-	movq	-152(%rbp), %rax
-	movsd	%xmm0, (%rax,%r12,8)
-	addq	$1, %r12
+	callq	0x1337c ## symbol stub for: _dcopy
+	movsd	(%r12,%rbx,8), %xmm0
+	movq	-368(%rbp), %rax
+	movsd	%xmm0, (%rax,%rbx,8)
+	incq	%rbx
 	movslq	24(%rbp), %rax
-	cmpq	%rax, %r12
+	cmpq	%rax, %rbx
 	movq	-88(%rbp), %rdx
 	xorpd	%xmm1, %xmm1
-	jge	0xc3d0
-	movsd	(%r15,%r12,8), %xmm0
+	jge	0xbe20
+	movq	-256(%rbp), %rcx
+	movsd	(%rcx,%rbx,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0xb980
+	jbe	0xb380
 	cmpl	$7, 40(%rbp)
-	movq	%r12, %rbx
-	jl	0xba02
-	leaq	32570(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating gene %d \n"
-	movl	%ebx, %esi
+	movq	%rbx, %r13
+	jl	0xb400
+	leaq	34908(%rip), %rdi ## literal pool for: "\t\t\t\t\t updating Node %d \n"
+	movl	%r13d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	xorpd	%xmm1, %xmm1
 	movq	-88(%rbp), %rdx
 	movl	24(%rbp), %eax
-	movq	-168(%rbp), %rcx
+	movq	-184(%rbp), %rcx
 	movabsq	$4607182418800017408, %rsi
-	movq	%rsi, (%rcx,%rbx,8)
-	leaq	(%r14,%rbx,8), %rcx
-	movq	%rcx, -272(%rbp)
+	movq	%rsi, (%rcx,%r13,8)
 	testl	%eax, %eax
-	jle	0xc340
+	jle	0xbd90
 	movl	%eax, %ecx
-	imull	%ebx, %ecx
+	imull	%r13d, %ecx
 	movslq	%ecx, %rcx
 	movq	72(%rbp), %rsi
-	leaq	(%rsi,%rcx,8), %r12
-	movq	-304(%rbp), %rcx
-	leaq	(%rcx,%rbx,8), %rcx
-	movq	%rcx, -576(%rbp)
-	movl	%ebx, %ecx
+	leaq	(%rsi,%rcx,8), %rcx
+	movq	%rcx, -448(%rbp)
+	leaq	(%r15,%r13,8), %rcx
+	movq	%rcx, -344(%rbp)
+	movq	-328(%rbp), %rcx
+	leaq	(%rcx,%r13,8), %rcx
+	movq	%rcx, -608(%rbp)
+	movl	%r13d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -480(%rbp)
-	movq	-160(%rbp), %rsi
-	xorl	%r15d, %r15d
-	movq	%rbx, -208(%rbp)
-	movq	%r12, -528(%rbp)
-	jmp	0xbaef
-	movsd	31663(%rip), %xmm0
-	movapd	-192(%rbp), %xmm2
-	movsd	-352(%rbp), %xmm1
-	movsd	%xmm4, (%r14,%rbx,8)
-	movq	-208(%rbp), %rbx
-	subsd	%xmm4, %xmm1
-	mulsd	%xmm1, %xmm2
-	addsd	%xmm0, %xmm2
-	divsd	%xmm2, %xmm0
-	movsd	%xmm0, -408(%rbp)
+	movq	%rcx, -280(%rbp)
+	movq	-176(%rbp), %rbx
+	xorl	%r12d, %r12d
+	movq	%r13, -136(%rbp)
+	jmp	0xb4ef
+	movsd	32799(%rip), %xmm0
+	movsd	-400(%rbp), %xmm1
+	movapd	-160(%rbp), %xmm3
+	movsd	%xmm5, (%r15,%r14,8)
+	movq	-136(%rbp), %r13
+	subsd	%xmm5, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	divsd	%xmm1, %xmm0
+	movsd	%xmm0, -456(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-408(%rbp), %rsi
-	movq	%r12, %rdx
-	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	-128(%rbp), %rsi
+	leaq	-456(%rbp), %rsi
+	movq	-448(%rbp), %rdx
+	leaq	-48(%rbp), %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	24(%rbp), %eax
 	movq	-88(%rbp), %rdx
 	xorpd	%xmm1, %xmm1
-	addq	$1, %r15
+	incq	%r12
 	movslq	%eax, %rcx
-	addq	$8, %rsi
-	cmpq	%rcx, %r15
-	jge	0xc340
-	movl	%r15d, %ecx
+	addq	$8, %rbx
+	cmpq	%rcx, %r12
+	jge	0xbd90
+	movl	%r12d, %ecx
 	imull	%eax, %ecx
-	addl	%ebx, %ecx
+	addl	%r13d, %ecx
 	movslq	%ecx, %rcx
 	movsd	(%rdx,%rcx,8), %xmm0
 	ucomisd	%xmm1, %xmm0
-	jbe	0xbadb
-	movq	-480(%rbp), %rax
-	movsd	(%rax,%r15,8), %xmm2
-	movsd	(%r14,%rcx,8), %xmm1
-	movapd	%xmm1, %xmm4
-	cmpq	%r15, %rbx
-	movsd	31497(%rip), %xmm0
-	movq	%rsi, -128(%rbp)
-	je	0xba9e
-	movsd	%xmm1, -352(%rbp)
+	jbe	0xb4dc
+	movq	-280(%rbp), %rax
+	movsd	(%rax,%r12,8), %xmm3
+	movsd	(%r15,%rcx,8), %xmm1
+	movapd	%xmm1, %xmm5
+	cmpq	%r12, %r13
+	movsd	32632(%rip), %xmm0
+	je	0xb49e
+	movsd	%xmm1, -400(%rbp)
 	leaq	32(%rbp), %rdi
-	leaq	24(%rbp), %r12
-	movq	%r12, %rdx
-	movq	-144(%rbp), %rcx
-	movq	%r13, %r8
-	movapd	%xmm2, -192(%rbp)
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%rbx, -512(%rbp)
+	movq	%rbx, %rsi
+	leaq	24(%rbp), %r15
+	movq	%r15, %rdx
+	movq	-192(%rbp), %rcx
+	leaq	-48(%rbp), %r14
+	movq	%r14, %r8
+	movapd	%xmm3, -160(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
-	imull	%r15d, %eax
-	addl	%ebx, %eax
+	imull	%r12d, %eax
+	addl	%r13d, %eax
 	cltq
-	movq	-520(%rbp), %rcx
+	movq	-544(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	mulsd	-280(%rbp), %xmm0
-	movsd	%xmm0, -80(%rbp)
-	movq	%r12, %rdi
-	movq	-272(%rbp), %rsi
+	mulsd	-264(%rbp), %xmm0
+	movsd	%xmm0, -112(%rbp)
+	movq	%r15, %rdi
+	movq	-344(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
-	movq	-288(%rbp), %rbx
+	movq	-272(%rbp), %rbx
 	movq	%rbx, %rcx
-	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r14, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
-	movq	%r12, %rdi
+	movq	%r15, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
-	movq	%r13, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movq	$0, (%rbx,%r15,8)
-	movq	%r12, %rdi
-	movq	-168(%rbp), %rsi
-	movq	%r13, %rdx
-	movq	-392(%rbp), %r14
 	movq	%r14, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x133a0 ## symbol stub for: _dscal
+	movq	$0, (%rbx,%r12,8)
+	movq	%r15, %rdi
+	movq	-184(%rbp), %rsi
+	movq	%r14, %rdx
+	movq	-432(%rbp), %r14
+	movq	%r14, %rcx
+	leaq	-52(%rbp), %r13
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
-	movq	%r12, %rdi
+	movq	%r15, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
-	movq	%r13, %rcx
+	leaq	-48(%rbp), %rcx
 	movq	%r14, %r8
-	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	leaq	32(%rbp), %r12
-	movq	%r12, %rdi
-	movq	-576(%rbp), %rsi
-	leaq	24(%rbp), %rdx
-	movq	%r13, %rbx
-	movq	-400(%rbp), %r13
-	movq	%r13, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	-152(%rbp), %rax
-	movq	-208(%rbp), %rcx
+	movq	%r13, %r9
+	callq	0x13376 ## symbol stub for: _daxpy
+	leaq	32(%rbp), %r13
+	movq	%r13, %rdi
+	movq	-608(%rbp), %rsi
+	movq	%r15, %rdx
+	movq	-440(%rbp), %r15
+	movq	%r15, %rcx
+	leaq	-48(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	-368(%rbp), %rax
+	movq	-136(%rbp), %rcx
 	movsd	(%rax,%rcx,8), %xmm0
-	xorpd	31296(%rip), %xmm0
+	xorpd	32404(%rip), %xmm0
 	movlpd	%xmm0, -64(%rbp)
-	movq	%r12, %rdi
-	leaq	-64(%rbp), %rsi
-	movq	%r13, %rdx
-	movq	%rbx, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	movq	%r13, %rdi
+	leaq	-64(%rbp), %rbx
+	movq	%rbx, %rsi
+	movq	%r15, %rdx
+	leaq	-48(%rbp), %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
 	movb	$84, -41(%rbp)
 	movabsq	$4607182418800017408, %rax
-	movq	%rax, -216(%rbp)
+	movq	%rax, -200(%rbp)
 	movq	%rax, -64(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
-	movq	%r12, %rdx
-	leaq	-64(%rbp), %rcx
-	movq	-160(%rbp), %r8
+	movq	%r13, %rdx
+	movq	%rbx, %rcx
+	movq	-176(%rbp), %r8
 	leaq	-68(%rbp), %r9
-	leaq	-48(%rbp), %r12
-	pushq	%r12
-	pushq	%r13
-	leaq	-216(%rbp), %rax
-	pushq	%rax
+	leaq	-52(%rbp), %rbx
 	pushq	%rbx
+	pushq	%r15
+	leaq	-200(%rbp), %rax
+	pushq	%rax
+	leaq	-48(%rbp), %rax
+	pushq	%rax
 	pushq	%r14
-	callq	0x13514 ## symbol stub for: _dgemv
+	leaq	-48(%rbp), %r14
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	leaq	32(%rbp), %rdi
-	movq	-144(%rbp), %r14
-	movq	%r14, %rsi
-	movq	%rbx, %rdx
-	movq	%r14, %rcx
-	movq	%r12, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	31058(%rip), %xmm1
-	subsd	-416(%rbp), %xmm1
-	mulsd	-280(%rbp), %xmm1
+	movq	%r13, %rdi
+	movq	-192(%rbp), %rcx
+	movq	%rcx, %rsi
+	movq	%r14, %rdx
+	movq	%r14, %r13
+	movq	%rcx, %r14
+	movq	%rbx, %r8
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	32170(%rip), %xmm1
+	subsd	-464(%rbp), %xmm1
+	mulsd	-264(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
-	movsd	%xmm1, -96(%rbp)
+	movsd	%xmm1, -80(%rbp)
 	leaq	32(%rbp), %rdi
+	movq	%r13, %rdx
 	movq	%r14, %rsi
-	movq	%rbx, %rdx
-	movq	%r13, %rcx
-	movq	%r12, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movapd	-192(%rbp), %xmm2
-	movapd	%xmm0, %xmm8
-	movapd	%xmm2, %xmm0
-	andpd	31099(%rip), %xmm0
-	movsd	30995(%rip), %xmm1
-	ucomisd	%xmm0, %xmm1
-	jbe	0xbdb2
+	movq	%r15, %rcx
+	movq	%rbx, %r8
+	callq	0x13382 ## symbol stub for: _ddot
+	movapd	-160(%rbp), %xmm3
+	movapd	%xmm3, %xmm2
+	andpd	32200(%rip), %xmm2
+	movsd	32112(%rip), %xmm1
+	ucomisd	%xmm2, %xmm1
+	jbe	0xb7c0
 	cmpl	$8, 40(%rbp)
-	xorpd	%xmm0, %xmm0
-	movq	-208(%rbp), %rbx
-	jl	0xbd6f
-	leaq	31734(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
-	movl	%ebx, %esi
-	movl	%r15d, %edx
+	xorpd	%xmm4, %xmm4
+	movq	-136(%rbp), %r13
+	jl	0xb781
+	leaq	34111(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t Node %d \t interact with Node %d.\tLinear equation\n"
+	movl	%r13d, %esi
+	movl	%r12d, %edx
 	xorl	%eax, %eax
-	movsd	%xmm8, -104(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-104(%rbp), %xmm8
-	movapd	-192(%rbp), %xmm2
-	xorpd	%xmm0, %xmm0
-	movapd	%xmm8, %xmm4
-	movsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm4
-	movsd	-96(%rbp), %xmm3
-	divsd	%xmm3, %xmm4
-	ucomisd	%xmm0, %xmm4
-	movq	-136(%rbp), %r14
-	leaq	-56(%rbp), %r13
-	movq	-528(%rbp), %r12
-	jbe	0xc037
+	movsd	%xmm0, -120(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-120(%rbp), %xmm0
+	movapd	-160(%rbp), %xmm3
+	xorpd	%xmm4, %xmm4
+	movapd	%xmm0, %xmm5
+	movsd	-112(%rbp), %xmm1
+	subsd	%xmm1, %xmm5
+	movsd	-80(%rbp), %xmm2
+	divsd	%xmm2, %xmm5
+	ucomisd	%xmm4, %xmm5
+	movq	-144(%rbp), %r15
+	movq	-512(%rbp), %rbx
+	jbe	0xb9f3
 	movl	24(%rbp), %eax
-	imull	%r15d, %eax
-	addl	%ebx, %eax
+	imull	%r12d, %eax
+	addl	%r13d, %eax
 	cltq
-	jmp	0xc059
+	jmp	0xba15
 	cmpl	$8, 40(%rbp)
-	movq	-208(%rbp), %rbx
-	movsd	%xmm8, -104(%rbp)
-	jl	0xbde6
-	leaq	31663(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
+	movq	-136(%rbp), %rbx
+	movsd	%xmm0, -120(%rbp)
+	jl	0xb7f2
+	leaq	34046(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t Node %d \t interact with Node %d.\tQuadratic equation\n"
 	movl	%ebx, %esi
-	movl	%r15d, %edx
+	movl	%r12d, %edx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-104(%rbp), %xmm8
-	movapd	-192(%rbp), %xmm2
-	movsd	30785(%rip), %xmm10
-	movapd	%xmm10, %xmm11
-	divsd	%xmm2, %xmm11
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-120(%rbp), %xmm0
+	movapd	-160(%rbp), %xmm3
+	movsd	31910(%rip), %xmm2
+	movapd	%xmm2, %xmm4
+	divsd	%xmm3, %xmm4
 	movl	24(%rbp), %eax
-	imull	%r15d, %eax
+	imull	%r12d, %eax
 	addl	%ebx, %eax
-	movslq	%eax, %rbx
-	movq	-136(%rbp), %r14
-	addsd	(%r14,%rbx,8), %xmm11
-	movsd	-96(%rbp), %xmm4
-	movapd	%xmm4, %xmm9
-	mulsd	%xmm11, %xmm9
-	movapd	%xmm8, %xmm1
-	addsd	%xmm9, %xmm1
-	movsd	-80(%rbp), %xmm0
-	subsd	%xmm0, %xmm1
-	movapd	%xmm8, %xmm2
-	subsd	%xmm0, %xmm2
-	cvtsi2sdl	32(%rbp), %xmm3
-	mulsd	%xmm11, %xmm2
-	mulsd	-536(%rbp), %xmm3
+	movslq	%eax, %r14
+	movq	-144(%rbp), %r15
+	addsd	(%r15,%r14,8), %xmm4
+	movsd	-80(%rbp), %xmm7
+	movapd	%xmm7, %xmm3
+	mulsd	%xmm4, %xmm3
 	movsd	%xmm3, -336(%rbp)
-	subsd	%xmm3, %xmm2
-	movapd	%xmm1, %xmm12
-	movapd	%xmm1, %xmm7
-	movapd	%xmm0, %xmm6
-	addsd	%xmm0, %xmm6
-	addsd	%xmm1, %xmm6
-	mulsd	%xmm1, %xmm1
-	movapd	%xmm4, %xmm3
-	movsd	30664(%rip), %xmm5
-	mulsd	%xmm5, %xmm3
-	mulsd	%xmm2, %xmm3
-	subsd	%xmm3, %xmm1
-	movapd	%xmm4, %xmm2
-	addsd	%xmm4, %xmm2
-	movapd	%xmm10, %xmm4
-	divsd	%xmm2, %xmm4
-	xorps	%xmm2, %xmm2
-	sqrtsd	%xmm1, %xmm2
-	addsd	%xmm2, %xmm12
-	mulsd	%xmm4, %xmm12
-	movapd	%xmm12, -240(%rbp)
-	subsd	%xmm2, %xmm7
-	movapd	%xmm4, -368(%rbp)
-	mulsd	%xmm4, %xmm7
-	movapd	%xmm7, -560(%rbp)
-	subsd	%xmm9, %xmm8
-	mulsd	%xmm5, %xmm0
-	mulsd	%xmm0, %xmm8
-	addsd	%xmm1, %xmm8
+	addsd	%xmm0, %xmm3
+	movsd	-112(%rbp), %xmm6
+	subsd	%xmm6, %xmm3
 	xorps	%xmm1, %xmm1
-	sqrtsd	%xmm8, %xmm1
-	movsd	%xmm6, -448(%rbp)
-	movapd	%xmm6, %xmm0
-	movsd	%xmm1, -512(%rbp)
+	cvtsi2sdl	32(%rbp), %xmm1
+	subsd	%xmm6, %xmm0
+	mulsd	-552(%rbp), %xmm1
+	movsd	%xmm1, -384(%rbp)
+	mulsd	%xmm4, %xmm0
 	subsd	%xmm1, %xmm0
-	movapd	%xmm0, -320(%rbp)
-	movapd	%xmm11, -464(%rbp)
-	movapd	%xmm11, %xmm0
-	andpd	30592(%rip), %xmm0
-	movsd	30504(%rip), %xmm1
-	addsd	%xmm1, %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-336(%rbp), %xmm10
-	movapd	%xmm0, %xmm11
-	mulsd	%xmm10, %xmm11
-	xorpd	%xmm4, %xmm4
-	movapd	-240(%rbp), %xmm0
-	ucomisd	%xmm4, %xmm0
-	leaq	-56(%rbp), %r13
-	movq	-528(%rbp), %r12
-	jbe	0xc064
-	movapd	-464(%rbp), %xmm0
-	subsd	-240(%rbp), %xmm0
-	movapd	30499(%rip), %xmm1
+	movapd	%xmm7, %xmm1
+	mulsd	31819(%rip), %xmm1
+	mulsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm5
+	mulsd	%xmm3, %xmm5
+	addsd	%xmm1, %xmm5
+	movapd	%xmm7, %xmm0
+	addsd	%xmm7, %xmm0
+	divsd	%xmm0, %xmm2
+	movsd	%xmm5, -592(%rbp)
+	xorps	%xmm0, %xmm0
+	sqrtsd	%xmm5, %xmm0
+	movsd	%xmm3, -168(%rbp)
+	movsd	%xmm0, -576(%rbp)
+	addsd	%xmm0, %xmm3
+	movapd	%xmm2, -320(%rbp)
+	mulsd	%xmm2, %xmm3
+	movapd	%xmm3, -224(%rbp)
+	movapd	%xmm6, %xmm0
+	mulsd	31732(%rip), %xmm0
+	movsd	%xmm0, -536(%rbp)
+	movapd	%xmm4, -496(%rbp)
+	movapd	%xmm4, %xmm0
+	andpd	31768(%rip), %xmm0
+	movsd	31704(%rip), %xmm1
+	addsd	%xmm1, %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-384(%rbp), %xmm9
+	movapd	%xmm0, %xmm13
+	mulsd	%xmm9, %xmm13
+	xorpd	%xmm5, %xmm5
+	movapd	-224(%rbp), %xmm0
+	ucomisd	%xmm5, %xmm0
+	movq	-512(%rbp), %rbx
+	jbe	0xba20
+	movapd	-496(%rbp), %xmm0
+	subsd	-224(%rbp), %xmm0
+	movapd	31679(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	30407(%rip), %xmm0
-	movsd	%xmm11, -112(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-112(%rbp), %xmm11
-	movsd	-336(%rbp), %xmm10
-	xorpd	%xmm4, %xmm4
-	mulsd	%xmm10, %xmm0
-	movapd	-240(%rbp), %xmm2
+	addsd	31611(%rip), %xmm0
+	movsd	%xmm13, -128(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movsd	-128(%rbp), %xmm13
+	movsd	-384(%rbp), %xmm9
+	xorpd	%xmm5, %xmm5
+	movapd	-224(%rbp), %xmm2
 	movapd	%xmm2, %xmm1
 	mulsd	%xmm2, %xmm1
-	movsd	-96(%rbp), %xmm8
-	mulsd	%xmm8, %xmm1
-	mulsd	30345(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movsd	-104(%rbp), %xmm0
-	mulsd	%xmm2, %xmm0
-	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	30388(%rip), %xmm1
 	mulsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	ucomisd	%xmm11, %xmm0
-	xorpd	%xmm1, %xmm1
-	movapd	-368(%rbp), %xmm6
-	movapd	-320(%rbp), %xmm2
-	movapd	-560(%rbp), %xmm3
-	movsd	-448(%rbp), %xmm5
-	movsd	-512(%rbp), %xmm7
-	jbe	0xc090
-	movapd	%xmm0, %xmm11
-	movapd	-240(%rbp), %xmm4
-	jmp	0xc090
-	addsd	%xmm8, %xmm1
-	movapd	%xmm1, %xmm4
-	divsd	%xmm3, %xmm4
+	mulsd	31560(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
+	addsd	%xmm1, %xmm0
+	movsd	-120(%rbp), %xmm10
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm2, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm2, %xmm0
+	andpd	31568(%rip), %xmm0
+	movsd	-112(%rbp), %xmm8
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	xorpd	%xmm11, %xmm11
+	movapd	-320(%rbp), %xmm7
+	movsd	-168(%rbp), %xmm12
+	movsd	-576(%rbp), %xmm0
+	jbe	0xba4a
+	movapd	%xmm1, %xmm13
+	movapd	-224(%rbp), %xmm5
+	jmp	0xba4a
+	addsd	%xmm0, %xmm1
+	movapd	%xmm1, %xmm5
+	divsd	%xmm2, %xmm5
 	movl	24(%rbp), %eax
-	imull	%r15d, %eax
-	addl	%ebx, %eax
-	ucomisd	%xmm4, %xmm0
+	imull	%r12d, %eax
+	addl	%r13d, %eax
+	ucomisd	%xmm5, %xmm4
 	cltq
-	jbe	0xc318
-	movsd	%xmm4, (%r14,%rax,8)
-	jmp	0xc324
-	xorpd	%xmm1, %xmm1
-	movapd	-368(%rbp), %xmm6
-	movapd	-320(%rbp), %xmm2
-	movapd	-560(%rbp), %xmm3
-	movsd	-448(%rbp), %xmm5
-	movsd	-512(%rbp), %xmm7
-	addsd	%xmm7, %xmm5
-	mulsd	%xmm6, %xmm2
-	ucomisd	%xmm1, %xmm3
-	movapd	%xmm2, -320(%rbp)
-	jbe	0xc17c
-	movapd	-464(%rbp), %xmm0
-	subsd	%xmm3, %xmm0
-	movapd	30178(%rip), %xmm1
+	jbe	0xbd62
+	movsd	%xmm5, (%r15,%rax,8)
+	jmp	0xbd6e
+	xorpd	%xmm11, %xmm11
+	movsd	-112(%rbp), %xmm8
+	movsd	-120(%rbp), %xmm10
+	movapd	-320(%rbp), %xmm7
+	movsd	-168(%rbp), %xmm12
+	movsd	-576(%rbp), %xmm0
+	movapd	%xmm12, %xmm2
+	subsd	%xmm0, %xmm2
+	mulsd	%xmm7, %xmm2
+	ucomisd	%xmm11, %xmm2
+	jbe	0xbb48
+	movapd	-496(%rbp), %xmm0
+	subsd	%xmm2, %xmm0
+	movapd	31370(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	addsd	30086(%rip), %xmm0
-	movsd	%xmm4, -240(%rbp)
-	movsd	%xmm11, -112(%rbp)
-	movsd	%xmm5, -448(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movsd	-448(%rbp), %xmm5
-	movapd	-560(%rbp), %xmm3
-	movapd	-320(%rbp), %xmm2
-	movsd	-112(%rbp), %xmm11
-	movapd	-368(%rbp), %xmm6
-	movsd	-336(%rbp), %xmm10
-	movsd	-240(%rbp), %xmm4
-	movsd	-104(%rbp), %xmm9
-	movsd	-96(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
+	addsd	31302(%rip), %xmm0
+	movsd	%xmm5, -224(%rbp)
+	movsd	%xmm13, -128(%rbp)
+	movapd	%xmm2, -576(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-576(%rbp), %xmm3
+	movsd	-168(%rbp), %xmm12
+	movsd	-128(%rbp), %xmm13
+	movapd	-320(%rbp), %xmm7
+	movsd	-384(%rbp), %xmm9
+	movsd	-224(%rbp), %xmm5
+	movsd	-120(%rbp), %xmm10
+	movsd	-112(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
 	movapd	%xmm3, %xmm1
 	mulsd	%xmm3, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	29974(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm3, %xmm0
+	mulsd	-80(%rbp), %xmm1
+	mulsd	31197(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	andpd	31211(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	ucomisd	%xmm13, %xmm1
+	movsd	-336(%rbp), %xmm4
+	movsd	-592(%rbp), %xmm2
+	movsd	-536(%rbp), %xmm6
+	jbe	0xbb60
+	movapd	%xmm1, %xmm13
+	movapd	%xmm3, %xmm5
+	jmp	0xbb60
+	movsd	-336(%rbp), %xmm4
+	movsd	-592(%rbp), %xmm2
+	movsd	-536(%rbp), %xmm6
+	movapd	%xmm10, %xmm0
+	subsd	%xmm4, %xmm0
+	mulsd	%xmm0, %xmm6
+	addsd	%xmm2, %xmm6
+	movapd	%xmm8, %xmm0
+	addsd	%xmm8, %xmm0
+	addsd	%xmm12, %xmm0
+	xorps	%xmm2, %xmm2
+	sqrtsd	%xmm6, %xmm2
+	movapd	%xmm0, %xmm3
+	subsd	%xmm2, %xmm3
+	mulsd	%xmm7, %xmm3
+	ucomisd	%xmm3, %xmm11
+	jbe	0xbc81
+	movsd	%xmm0, -168(%rbp)
+	movapd	-496(%rbp), %xmm0
+	subsd	%xmm3, %xmm0
+	movapd	31046(%rip), %xmm1
+	andpd	%xmm1, %xmm0
+	addsd	30978(%rip), %xmm0
+	movsd	%xmm5, -224(%rbp)
+	movsd	%xmm13, -128(%rbp)
+	movsd	%xmm2, -336(%rbp)
+	movapd	%xmm3, -592(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-592(%rbp), %xmm3
+	movsd	-336(%rbp), %xmm2
+	movsd	-128(%rbp), %xmm13
+	movapd	-320(%rbp), %xmm7
+	movsd	-384(%rbp), %xmm9
+	movsd	-224(%rbp), %xmm5
+	movsd	-120(%rbp), %xmm10
+	movsd	-112(%rbp), %xmm8
+	xorpd	%xmm11, %xmm11
 	movapd	%xmm3, %xmm1
-	andpd	30017(%rip), %xmm1
+	mulsd	%xmm3, %xmm1
 	mulsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0xc17c
-	movapd	%xmm0, %xmm11
-	movapd	%xmm3, %xmm4
-	mulsd	%xmm5, %xmm6
-	ucomisd	%xmm2, %xmm1
-	movapd	%xmm6, -368(%rbp)
-	jbe	0xc24c
-	movapd	-464(%rbp), %xmm0
-	subsd	%xmm2, %xmm0
-	movapd	29946(%rip), %xmm1
-	andpd	%xmm1, %xmm0
-	addsd	29854(%rip), %xmm0
-	movsd	%xmm4, -240(%rbp)
-	movsd	%xmm11, -112(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-320(%rbp), %xmm2
-	movsd	-112(%rbp), %xmm11
-	movapd	-368(%rbp), %xmm6
-	movsd	-336(%rbp), %xmm10
-	movsd	-240(%rbp), %xmm4
-	movsd	-104(%rbp), %xmm9
-	movsd	-96(%rbp), %xmm8
-	mulsd	%xmm10, %xmm0
-	movapd	%xmm2, %xmm1
-	mulsd	%xmm2, %xmm1
-	mulsd	%xmm8, %xmm1
-	mulsd	29766(%rip), %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	%xmm9, %xmm0
-	mulsd	%xmm2, %xmm0
+	mulsd	30866(%rip), %xmm1
+	mulsd	%xmm9, %xmm0
 	addsd	%xmm1, %xmm0
-	movapd	%xmm2, %xmm1
-	andpd	29809(%rip), %xmm1
-	mulsd	-80(%rbp), %xmm1
-	subsd	%xmm1, %xmm0
-	xorpd	%xmm1, %xmm1
-	ucomisd	%xmm11, %xmm0
-	jbe	0xc24c
-	movapd	%xmm0, %xmm11
-	movapd	%xmm2, %xmm4
-	ucomisd	%xmm6, %xmm1
-	jbe	0xba79
-	movapd	-464(%rbp), %xmm1
-	subsd	%xmm6, %xmm1
-	movapd	29750(%rip), %xmm0
+	movapd	%xmm10, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	andpd	30880(%rip), %xmm0
+	mulsd	%xmm8, %xmm0
+	subsd	%xmm0, %xmm1
+	movsd	-168(%rbp), %xmm0
+	ucomisd	%xmm13, %xmm1
+	jbe	0xbc81
+	movapd	%xmm1, %xmm13
+	movapd	%xmm3, %xmm5
+	addsd	%xmm2, %xmm0
+	mulsd	%xmm0, %xmm7
+	ucomisd	%xmm7, %xmm11
+	jbe	0xb479
+	movapd	-496(%rbp), %xmm1
+	subsd	%xmm7, %xmm1
+	movapd	30808(%rip), %xmm0
 	andpd	%xmm0, %xmm1
-	addsd	29658(%rip), %xmm1
+	addsd	30740(%rip), %xmm1
 	movapd	%xmm1, %xmm0
-	movsd	%xmm4, -240(%rbp)
-	movsd	%xmm11, -112(%rbp)
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-368(%rbp), %xmm3
-	movsd	-240(%rbp), %xmm4
-	movsd	-336(%rbp), %xmm2
-	mulsd	%xmm0, %xmm2
-	movapd	%xmm3, %xmm0
-	mulsd	%xmm3, %xmm0
-	movsd	-96(%rbp), %xmm1
+	movsd	%xmm5, -224(%rbp)
+	movapd	%xmm7, -320(%rbp)
+	movsd	%xmm13, -128(%rbp)
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-320(%rbp), %xmm4
+	movsd	-224(%rbp), %xmm5
+	movapd	%xmm4, %xmm1
+	mulsd	%xmm4, %xmm1
+	movsd	-80(%rbp), %xmm2
+	mulsd	%xmm1, %xmm2
+	mulsd	30676(%rip), %xmm2
+	movsd	-384(%rbp), %xmm1
 	mulsd	%xmm0, %xmm1
-	mulsd	29590(%rip), %xmm1
 	addsd	%xmm2, %xmm1
-	movsd	-104(%rbp), %xmm2
-	mulsd	%xmm3, %xmm2
-	addsd	%xmm1, %xmm2
-	movapd	%xmm3, %xmm0
-	andpd	29633(%rip), %xmm0
-	movsd	-80(%rbp), %xmm1
-	mulsd	%xmm0, %xmm1
-	subsd	%xmm1, %xmm2
-	ucomisd	-112(%rbp), %xmm2
-	movsd	29495(%rip), %xmm0
-	movapd	-192(%rbp), %xmm2
-	movsd	-352(%rbp), %xmm1
-	jbe	0xba91
-	movapd	%xmm3, %xmm4
-	jmp	0xba91
-	movq	$0, (%r14,%rax,8)
-	xorpd	%xmm4, %xmm4
-	movsd	29444(%rip), %xmm0
-	movsd	-352(%rbp), %xmm1
-	jmp	0xba9e
-	nopl	(%rax)
-	leaq	24(%rbp), %r15
-	movq	%r15, %rdi
-	movq	-272(%rbp), %rsi
+	movapd	%xmm1, %xmm0
+	movsd	-120(%rbp), %xmm1
+	mulsd	%xmm4, %xmm1
+	addsd	%xmm0, %xmm1
+	movapd	%xmm4, %xmm0
+	andpd	30679(%rip), %xmm0
+	movsd	-112(%rbp), %xmm2
+	mulsd	%xmm0, %xmm2
+	subsd	%xmm2, %xmm1
+	ucomisd	-128(%rbp), %xmm1
+	movsd	30557(%rip), %xmm0
+	movsd	-400(%rbp), %xmm1
+	movapd	-160(%rbp), %xmm3
+	jbe	0xb491
+	movapd	%xmm4, %xmm5
+	jmp	0xb491
+	movq	$0, (%r15,%rax,8)
+	xorpd	%xmm5, %xmm5
+	movsd	30506(%rip), %xmm0
+	movsd	-400(%rbp), %xmm1
+	jmp	0xb49e
+	nopw	%cs:(%rax,%rax)
+	leaq	(%r15,%r13,8), %rsi
+	leaq	24(%rbp), %r12
+	movq	%r12, %rdi
 	leaq	-68(%rbp), %rdx
-	movq	%rbx, %r12
-	movq	-288(%rbp), %rbx
-	movq	%rbx, %rcx
-	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r13, %rbx
+	movq	-272(%rbp), %r13
+	movq	%r13, %rcx
+	leaq	-48(%rbp), %r14
+	movq	%r14, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
-	imull	%r12d, %eax
+	imull	%ebx, %eax
 	cltq
-	movq	-256(%rbp), %rcx
+	movq	-248(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
-	movq	%r15, %rdi
-	movq	%rbx, %rsi
-	movq	%r13, %rdx
-	leaq	-48(%rbp), %rbx
-	movq	%rbx, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movq	-264(%rbp), %rax
-	movsd	(%rax,%r12,8), %xmm1
+	movq	%r12, %rdi
+	movq	%r13, %rsi
+	movq	%r14, %rdx
+	leaq	-52(%rbp), %r13
+	movq	%r13, %r8
+	callq	0x13382 ## symbol stub for: _ddot
+	movq	-240(%rbp), %r12
+	movsd	(%r12,%rbx,8), %xmm1
 	subsd	%xmm0, %xmm1
-	movq	-152(%rbp), %rax
-	movsd	%xmm1, (%rax,%r12,8)
-	movq	-168(%rbp), %rax
-	movq	$0, (%rax,%r12,8)
-	movq	-200(%rbp), %r15
-	jmp	0xb9b9
-	nopl	(%rax)
-	leaq	-52(%rbp), %rdi
-	movq	%r14, %rsi
-	movq	%r13, %rdx
-	movq	-384(%rbp), %r15
+	movq	-368(%rbp), %rax
+	movsd	%xmm1, (%rax,%rbx,8)
+	movq	-184(%rbp), %rax
+	movq	$0, (%rax,%rbx,8)
+	jmp	0xb3b1
+	nopw	%cs:(%rax,%rax)
+	leaq	-56(%rbp), %rdi
+	movq	%r15, %rsi
+	leaq	-48(%rbp), %rbx
+	movq	%rbx, %rdx
+	movq	-424(%rbp), %r15
 	movq	%r15, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movslq	-52(%rbp), %rax
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movslq	-56(%rbp), %rax
 	leaq	(%r15,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
-	movq	%r13, %rdx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	-368(%rbp), %rsi
+	movq	%rbx, %rdx
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	leal	1(%rax), %ecx
 	imull	%eax, %ecx
 	movl	%ecx, -72(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-72(%rbp), %rdi
-	movq	-248(%rbp), %r12
-	movq	%r12, %rsi
-	movq	%r13, %rdx
-	movq	%r13, %r14
-	movq	-376(%rbp), %r13
-	movq	%r13, %rcx
-	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	-232(%rbp), %r14
+	movq	%r14, %rsi
+	leaq	-48(%rbp), %rdx
+	movq	-416(%rbp), %rbx
+	movq	%rbx, %rcx
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	-72(%rbp), %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r15, %rdx
-	movq	%r14, %rcx
-	movq	%r13, %r8
-	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	movq	-144(%rbp), %r15
+	leaq	-48(%rbp), %rcx
+	movq	%rbx, %r8
+	movq	%r13, %r9
+	callq	0x13376 ## symbol stub for: _daxpy
 	leaq	-72(%rbp), %rdi
-	movq	%rdi, %rbx
-	movq	%r12, %rsi
-	movq	-136(%rbp), %r15
+	movq	%r14, %rsi
+	leaq	-48(%rbp), %r14
 	movq	%r14, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -192(%rbp)
-	movq	%rbx, %rdi
-	movq	%r13, %rsi
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -160(%rbp)
+	leaq	-72(%rbp), %rdi
+	movq	%rbx, %rsi
 	movq	%r14, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -128(%rbp)
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -112(%rbp)
 	movl	24(%rbp), %edx
 	movq	72(%rbp), %rdi
 	movq	%r15, %rsi
 	callq	_UpdateIBinv
-	movsd	-128(%rbp), %xmm1
-	movsd	-192(%rbp), %xmm0
-	addsd	29061(%rip), %xmm0
+	movsd	-112(%rbp), %xmm1
+	movsd	-160(%rbp), %xmm0
+	addsd	30112(%rip), %xmm0
 	divsd	%xmm0, %xmm1
 	cmpl	$6, 40(%rbp)
-	jl	0xb8e0
-	leaq	29928(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
+	jl	0xb300
+	leaq	31011(%rip), %rdi ## literal pool for: "\t\t\t\t\t\tdelta_BF: %f\n"
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
-	movsd	%xmm1, -128(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-128(%rbp), %xmm1
-	jmp	0xb8e0
-	movl	-292(%rbp), %esi
+	movsd	%xmm1, -112(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-112(%rbp), %xmm1
+	jmp	0xb300
+	movl	-284(%rbp), %esi
 	cmpl	$4, 40(%rbp)
-	jl	0xc50c
-	leaq	29903(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
-	movsd	-280(%rbp), %xmm0
+	jl	0xbf61
+	leaq	30986(%rip), %rdi ## literal pool for: "\t\t\t\tCurrent lambda: %f;\t number of iteration is: %d.\tExiting Weighted_LassoSf\n\n"
+	movsd	-264(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	leaq	-52(%rbp), %rdi
-	leaq	-56(%rbp), %rbx
+	callq	0x133c4 ## symbol stub for: _printf
+	leaq	-56(%rbp), %rdi
 	leaq	-48(%rbp), %r14
+	leaq	-52(%rbp), %rbx
 	movq	%r15, %rsi
-	movq	%rbx, %rdx
+	movq	%r14, %rdx
 	movq	48(%rbp), %rcx
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%rbx, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	24(%rbp), %rdi
-	movq	-152(%rbp), %rsi
-	movq	%rbx, %rdx
-	movq	%r13, %rcx
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	-368(%rbp), %rsi
+	movq	%r14, %rdx
+	movq	56(%rbp), %rcx
+	movq	%rbx, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$5, 40(%rbp)
-	jl	0xc555
-	leaq	30125(%rip), %rdi ## literal pool for: "Enter Function: constrained-MLf. Shrinkage lambda is: 0. "
-	callq	0x13556 ## symbol stub for: _puts
-	movl	-52(%rbp), %eax
+	jl	0xbfab
+	leaq	31207(%rip), %rdi ## literal pool for: "Enter Function: constrained-MLf. Shrinkage lambda is: 0. "
+	callq	0x133d0 ## symbol stub for: _puts
+	movl	-56(%rbp), %eax
 	testl	%eax, %eax
 	movq	-88(%rbp), %rsi
-	jle	0xc67d
+	jle	0xc0cc
 	cmpl	$4, %eax
-	jae	0xc570
+	jae	0xbfc6
 	xorl	%ecx, %ecx
-	jmp	0xc651
+	jmp	0xc0a1
 	movl	%eax, %ecx
 	andl	$-4, %ecx
 	leaq	-4(%rcx), %rdx
 	movq	%rdx, %r8
 	shrq	$2, %r8
-	addq	$1, %r8
+	incq	%r8
 	testq	%rdx, %rdx
-	je	0xd0f1
+	je	0xcb50
 	movq	%r8, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
 	xorl	%edx, %edx
 	xorpd	%xmm0, %xmm0
-	movapd	28939(%rip), %xmm1
-	nopw	%cs:(%rax,%rax)
-	nop
+	movapd	29977(%rip), %xmm1
+	nopw	(%rax,%rax)
 	movupd	(%r15,%rdx,8), %xmm2
 	movupd	16(%r15,%rdx,8), %xmm3
 	cmpneqpd	%xmm0, %xmm2
 	andpd	%xmm1, %xmm2
 	cmpneqpd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movupd	%xmm2, (%rsi,%rdx,8)
@@ -8922,628 +8997,625 @@
 	cmpneqpd	%xmm0, %xmm2
 	andpd	%xmm1, %xmm2
 	cmpneqpd	%xmm0, %xmm3
 	andpd	%xmm1, %xmm3
 	movupd	%xmm2, 32(%rsi,%rdx,8)
 	movupd	%xmm3, 48(%rsi,%rdx,8)
 	addq	$8, %rdx
-	addq	$2, %rdi
-	jne	0xc5b0
+	addq	$-2, %rdi
+	jne	0xc000
 	testb	$1, %r8b
-	je	0xc64c
+	je	0xc09c
 	movupd	(%r15,%rdx,8), %xmm0
 	movupd	16(%r15,%rdx,8), %xmm1
 	xorpd	%xmm2, %xmm2
 	cmpneqpd	%xmm2, %xmm0
-	movapd	28796(%rip), %xmm3
+	movapd	29836(%rip), %xmm3
 	andpd	%xmm3, %xmm0
 	cmpneqpd	%xmm2, %xmm1
 	andpd	%xmm3, %xmm1
 	movupd	%xmm0, (%rsi,%rdx,8)
 	movupd	%xmm1, 16(%rsi,%rdx,8)
 	cmpq	%rax, %rcx
-	je	0xc67d
+	je	0xc0cc
 	xorpd	%xmm0, %xmm0
-	movsd	28627(%rip), %xmm1
+	movsd	29683(%rip), %xmm1
 	nopl	(%rax)
 	movsd	(%r15,%rcx,8), %xmm2
 	cmpeqsd	%xmm0, %xmm2
 	andnpd	%xmm1, %xmm2
 	movlpd	%xmm2, (%rsi,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %rax
-	jne	0xc660
+	jne	0xc0b0
 	cmpl	$0, 24(%rbp)
-	movq	-200(%rbp), %r15
-	jle	0xc6c5
+	movq	-256(%rbp), %r15
+	jle	0xc114
 	xorl	%r13d, %r13d
 	leaq	24(%rbp), %rbx
 	leaq	-68(%rbp), %r14
 	movq	-88(%rbp), %r12
-	nopl	(%rax)
+	nopl	(%rax,%rax)
 	movq	%rbx, %rdi
 	movq	%r12, %rsi
 	movq	%r14, %rdx
-	callq	0x134f6 ## symbol stub for: _dasum
+	callq	0x13370 ## symbol stub for: _dasum
 	movsd	%xmm0, (%r15,%r13,8)
-	addq	$1, %r13
+	incq	%r13
 	movslq	24(%rbp), %rax
 	addq	$8, %r12
 	cmpq	%rax, %r13
-	jl	0xc6a0
-	movabsq	$4607182418800017408, %rax
-	movq	%rax, -216(%rbp)
+	jl	0xc0f0
 	movslq	16(%rbp), %rax
 	imulq	$1717986919, %rax, %rcx
 	movq	%rcx, %rax
 	shrq	$63, %rax
 	sarq	$33, %rcx
 	addl	%eax, %ecx
 	xorl	%eax, %eax
 	testl	%ecx, %ecx
 	cmovlel	%eax, %ecx
-	movq	%rcx, -272(%rbp)
-	xorl	%r14d, %r14d
-	movq	-256(%rbp), %r12
-	movq	56(%rbp), %rbx
-	movq	48(%rbp), %r13
-	jmp	0xc748
-	movl	-152(%rbp), %r14d
-	addl	$1, %r14d
+	movq	%rcx, -344(%rbp)
+	movabsq	$4607182418800017408, %rax
+	movq	%rax, -200(%rbp)
+	xorl	%ebx, %ebx
+	movq	-248(%rbp), %r12
+	leaq	-48(%rbp), %r13
+	jmp	0xc192
+	nopw	(%rax,%rax)
+	movl	-168(%rbp), %ebx
+	incl	%ebx
 	movl	24(%rbp), %edx
 	movq	80(%rbp), %rdi
-	movq	48(%rbp), %r13
-	movq	%r13, %rsi
+	movq	48(%rbp), %rsi
 	callq	_UpdateIBinv
-	movsd	28482(%rip), %xmm0
-	ucomisd	-128(%rbp), %xmm0
-	movq	-256(%rbp), %r12
-	ja	0xcee0
-	cmpl	-272(%rbp), %r14d
-	je	0xced6
-	movl	%r14d, -152(%rbp)
-	leaq	-52(%rbp), %rdi
-	movq	%r13, %rsi
-	leaq	-56(%rbp), %r12
-	movq	%r12, %rdx
-	movq	-248(%rbp), %r14
-	movq	%r14, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movslq	-52(%rbp), %rax
-	leaq	(%r14,%rax,8), %rcx
+	movsd	29536(%rip), %xmm0
+	ucomisd	-112(%rbp), %xmm0
+	movq	-248(%rbp), %r12
+	ja	0xc93a
+	cmpl	-344(%rbp), %ebx
+	je	0xc931
+	movl	%ebx, -168(%rbp)
+	leaq	-56(%rbp), %rdi
+	movq	48(%rbp), %rsi
+	movq	%r13, %rdx
+	movq	-232(%rbp), %rbx
+	movq	%rbx, %rcx
+	leaq	-52(%rbp), %r14
+	movq	%r14, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movslq	-56(%rbp), %rax
+	leaq	(%rbx,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	%rbx, %rsi
-	movq	%r12, %rdx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	56(%rbp), %rsi
+	movq	%r13, %rdx
+	movq	%r14, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
 	movq	-88(%rbp), %rdx
-	jle	0xcde0
+	jle	0xc840
 	xorl	%r12d, %r12d
-	jmp	0xc843
-	nop
-	leaq	24(%rbp), %r15
-	movq	%r15, %rdi
-	movq	-112(%rbp), %rsi
+	jmp	0xc28e
+	nopw	(%rax,%rax)
+	leaq	24(%rbp), %r14
+	movq	%r14, %rdi
+	movq	-128(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
-	movq	-288(%rbp), %rbx
+	movq	-272(%rbp), %rbx
 	movq	%rbx, %rcx
-	leaq	-56(%rbp), %r14
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	imull	%r12d, %eax
 	cltq
-	movq	-256(%rbp), %rcx
+	movq	-248(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
-	movq	%r15, %rdi
+	movq	%r14, %rdi
 	movq	%rbx, %rsi
-	movq	%r14, %rdx
-	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	movq	%r13, %rdx
+	leaq	-52(%rbp), %r8
+	callq	0x13382 ## symbol stub for: _ddot
 	movq	-88(%rbp), %rdx
-	movq	-264(%rbp), %rax
+	movq	-240(%rbp), %rax
 	movsd	(%rax,%r12,8), %xmm1
 	subsd	%xmm0, %xmm1
-	movq	56(%rbp), %rbx
-	movsd	%xmm1, (%rbx,%r12,8)
-	movq	-168(%rbp), %rax
+	movq	56(%rbp), %rax
+	movsd	%xmm1, (%rax,%r12,8)
+	movq	-184(%rbp), %rax
 	movq	$0, (%rax,%r12,8)
 	movl	24(%rbp), %eax
-	movq	-200(%rbp), %r15
-	addq	$1, %r12
+	movq	-256(%rbp), %r15
+	incq	%r12
 	movslq	%eax, %rcx
 	cmpq	%rcx, %r12
-	jge	0xcde0
+	jge	0xc840
 	movsd	(%r15,%r12,8), %xmm0
-	ucomisd	28207(%rip), %xmm0
-	jbe	0xc833
+	ucomisd	29260(%rip), %xmm0
+	jbe	0xc27f
 	cmpl	$7, 40(%rbp)
-	jl	0xc871
-	leaq	29116(%rip), %rdi ## literal pool for: "\t\t updating gene %d \n"
+	jl	0xc2bc
+	leaq	31337(%rip), %rdi ## literal pool for: "\t\t updating Node %d \n"
 	movl	%r12d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	-88(%rbp), %rdx
 	movl	24(%rbp), %eax
-	movq	-168(%rbp), %rcx
+	movq	-184(%rbp), %rcx
 	movabsq	$4607182418800017408, %rsi
 	movq	%rsi, (%rcx,%r12,8)
-	leaq	(,%r12,8), %rcx
-	addq	%r13, %rcx
-	movq	%rcx, -112(%rbp)
+	movq	48(%rbp), %rcx
+	leaq	(%rcx,%r12,8), %rcx
+	movq	%rcx, -128(%rbp)
 	testl	%eax, %eax
-	jle	0xc7b0
+	jle	0xc200
 	movl	%eax, %ecx
 	imull	%r12d, %ecx
 	movslq	%ecx, %rcx
 	movq	80(%rbp), %rsi
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -136(%rbp)
-	movq	-304(%rbp), %rcx
+	movq	%rcx, -144(%rbp)
+	movq	-328(%rbp), %rcx
 	leaq	(%rcx,%r12,8), %rcx
-	movq	%rcx, -240(%rbp)
+	movq	%rcx, -224(%rbp)
 	movl	%r12d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%rsi,%rcx,8), %rcx
-	movq	%rcx, -464(%rbp)
-	movq	-160(%rbp), %rsi
+	movq	%rcx, -496(%rbp)
+	movq	-176(%rbp), %rsi
 	xorl	%r15d, %r15d
-	movq	%r12, -96(%rbp)
-	jmp	0xcb5c
-	nop
-	movsd	27960(%rip), %xmm0
-	movapd	%xmm0, %xmm1
+	movq	%r12, -136(%rbp)
+	jmp	0xc5b1
+	nopl	(%rax)
+	movsd	29016(%rip), %xmm0
+	movapd	%xmm0, %xmm6
 	movapd	%xmm0, %xmm5
-	divsd	%xmm3, %xmm1
+	divsd	%xmm3, %xmm6
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	addl	%r12d, %eax
 	movslq	%eax, %r14
-	movq	48(%rbp), %r13
-	addsd	(%r13,%r14,8), %xmm1
-	movsd	-192(%rbp), %xmm0
+	movq	48(%rbp), %rbx
+	addsd	(%rbx,%r14,8), %xmm6
+	movsd	-160(%rbp), %xmm0
 	movapd	%xmm0, %xmm3
-	movapd	%xmm0, %xmm6
-	mulsd	%xmm1, %xmm3
+	movapd	%xmm0, %xmm2
+	mulsd	%xmm6, %xmm3
 	addsd	%xmm4, %xmm3
-	movapd	%xmm4, %xmm0
-	cvtsi2sdl	32(%rbp), %xmm2
-	mulsd	%xmm1, %xmm0
-	movapd	%xmm1, %xmm4
-	movapd	%xmm1, -336(%rbp)
-	mulsd	-536(%rbp), %xmm2
-	movsd	%xmm2, -104(%rbp)
-	subsd	%xmm2, %xmm0
-	movapd	%xmm3, %xmm1
-	mulsd	%xmm3, %xmm1
-	movapd	%xmm6, %xmm2
-	mulsd	27894(%rip), %xmm2
-	mulsd	%xmm0, %xmm2
-	addsd	%xmm1, %xmm2
+	xorps	%xmm1, %xmm1
+	cvtsi2sdl	32(%rbp), %xmm1
+	mulsd	-552(%rbp), %xmm1
+	movsd	%xmm1, -280(%rbp)
 	movapd	%xmm6, %xmm0
-	addsd	%xmm6, %xmm0
-	movapd	%xmm5, %xmm1
-	divsd	%xmm0, %xmm1
-	xorps	%xmm0, %xmm0
-	sqrtsd	%xmm2, %xmm0
-	movapd	%xmm3, %xmm2
-	addsd	%xmm0, %xmm2
-	mulsd	%xmm1, %xmm2
-	movapd	%xmm2, -320(%rbp)
+	movapd	%xmm6, -384(%rbp)
+	mulsd	%xmm4, %xmm0
+	subsd	%xmm1, %xmm0
+	movapd	%xmm2, %xmm1
+	mulsd	28925(%rip), %xmm1
+	mulsd	%xmm0, %xmm1
+	movapd	%xmm3, %xmm0
+	mulsd	%xmm3, %xmm0
+	addsd	%xmm1, %xmm0
+	movapd	%xmm2, %xmm1
+	addsd	%xmm2, %xmm1
+	movapd	%xmm5, %xmm2
+	divsd	%xmm1, %xmm2
+	sqrtsd	%xmm0, %xmm0
+	movapd	%xmm3, %xmm1
+	addsd	%xmm0, %xmm1
+	mulsd	%xmm2, %xmm1
+	movapd	%xmm1, -320(%rbp)
 	subsd	%xmm0, %xmm3
-	mulsd	%xmm1, %xmm3
-	movapd	%xmm3, -352(%rbp)
-	movapd	%xmm4, %xmm0
-	movapd	27871(%rip), %xmm1
+	mulsd	%xmm2, %xmm3
+	movapd	%xmm3, -400(%rbp)
+	movapd	%xmm6, %xmm0
+	movapd	28913(%rip), %xmm1
 	andpd	%xmm1, %xmm0
-	movsd	27779(%rip), %xmm1
+	movsd	28845(%rip), %xmm1
 	addsd	%xmm1, %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	mulsd	-104(%rbp), %xmm0
-	movapd	%xmm0, -480(%rbp)
-	movapd	-336(%rbp), %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	mulsd	-280(%rbp), %xmm0
+	movapd	%xmm0, -512(%rbp)
+	movapd	-384(%rbp), %xmm0
 	subsd	-320(%rbp), %xmm0
-	andpd	27813(%rip), %xmm0
-	addsd	27725(%rip), %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	mulsd	-104(%rbp), %xmm0
+	andpd	28852(%rip), %xmm0
+	addsd	28788(%rip), %xmm0
+	callq	0x133b8 ## symbol stub for: _log
 	movapd	-320(%rbp), %xmm3
 	movapd	%xmm3, %xmm1
 	mulsd	%xmm3, %xmm1
-	mulsd	-192(%rbp), %xmm1
-	movsd	27715(%rip), %xmm2
+	mulsd	-160(%rbp), %xmm1
+	movsd	28759(%rip), %xmm2
 	mulsd	%xmm2, %xmm1
-	subsd	%xmm1, %xmm0
+	mulsd	-280(%rbp), %xmm0
+	addsd	%xmm1, %xmm0
 	movsd	-80(%rbp), %xmm1
 	mulsd	%xmm3, %xmm1
 	addsd	%xmm0, %xmm1
 	movapd	%xmm1, %xmm2
-	movapd	-480(%rbp), %xmm0
+	movapd	-512(%rbp), %xmm0
 	maxsd	%xmm0, %xmm2
-	movapd	%xmm2, -448(%rbp)
+	movapd	%xmm2, -368(%rbp)
 	cmpltsd	%xmm1, %xmm0
 	andpd	%xmm3, %xmm0
-	movapd	%xmm0, -480(%rbp)
-	movapd	-336(%rbp), %xmm0
-	subsd	-352(%rbp), %xmm0
-	andpd	27677(%rip), %xmm0
-	addsd	27589(%rip), %xmm0
-	callq	0x1353e ## symbol stub for: _log
-	movapd	-128(%rbp), %xmm3
-	movsd	27539(%rip), %xmm2
-	mulsd	-104(%rbp), %xmm0
-	movapd	-352(%rbp), %xmm4
+	movapd	%xmm0, -512(%rbp)
+	movapd	-384(%rbp), %xmm0
+	subsd	-400(%rbp), %xmm0
+	andpd	28713(%rip), %xmm0
+	addsd	28649(%rip), %xmm0
+	callq	0x133b8 ## symbol stub for: _log
+	movapd	-112(%rbp), %xmm3
+	movsd	28591(%rip), %xmm2
+	movapd	-400(%rbp), %xmm4
 	movapd	%xmm4, %xmm1
 	mulsd	%xmm4, %xmm1
-	mulsd	-192(%rbp), %xmm1
-	mulsd	27566(%rip), %xmm1
-	subsd	%xmm1, %xmm0
-	movsd	-80(%rbp), %xmm1
-	mulsd	%xmm4, %xmm1
-	addsd	%xmm0, %xmm1
-	movapd	-448(%rbp), %xmm0
-	cmpltsd	%xmm1, %xmm0
-	andpd	%xmm0, %xmm4
-	andnpd	-480(%rbp), %xmm0
-	orpd	%xmm4, %xmm0
-	movlpd	%xmm0, (%r13,%r14,8)
+	mulsd	-160(%rbp), %xmm1
+	mulsd	28607(%rip), %xmm1
+	mulsd	-280(%rbp), %xmm0
+	addsd	%xmm1, %xmm0
+	movapd	%xmm4, %xmm1
+	movsd	-80(%rbp), %xmm4
+	mulsd	%xmm1, %xmm4
+	addsd	%xmm0, %xmm4
+	movapd	-368(%rbp), %xmm0
+	cmpltsd	%xmm4, %xmm0
+	andpd	%xmm0, %xmm1
+	andnpd	-512(%rbp), %xmm0
+	orpd	%xmm1, %xmm0
+	movlpd	%xmm0, (%rbx,%r14,8)
 	movapd	%xmm0, %xmm4
-	movsd	-368(%rbp), %xmm0
-	subsd	%xmm4, %xmm0
-	mulsd	%xmm0, %xmm3
-	addsd	%xmm2, %xmm3
+	movsd	-448(%rbp), %xmm1
+	subsd	%xmm4, %xmm1
+	mulsd	%xmm3, %xmm1
+	addsd	%xmm2, %xmm1
 	movapd	%xmm2, %xmm0
-	divsd	%xmm3, %xmm0
-	movsd	%xmm0, -408(%rbp)
+	divsd	%xmm1, %xmm0
+	movsd	%xmm0, -456(%rbp)
 	leaq	24(%rbp), %rdi
-	leaq	-408(%rbp), %rsi
-	movq	-136(%rbp), %rdx
-	leaq	-56(%rbp), %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	leaq	-456(%rbp), %rsi
+	movq	-144(%rbp), %rdx
+	movq	%r13, %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	24(%rbp), %eax
 	movq	-88(%rbp), %rdx
-	movq	-208(%rbp), %rsi
-	addq	$1, %r15
+	movq	-120(%rbp), %rsi
+	incq	%r15
 	movslq	%eax, %rcx
 	addq	$8, %rsi
 	cmpq	%rcx, %r15
-	jge	0xc7b0
+	jge	0xc200
 	movl	%r15d, %ecx
 	imull	%eax, %ecx
 	addl	%r12d, %ecx
 	movslq	%ecx, %rcx
 	movsd	(%rdx,%rcx,8), %xmm0
-	ucomisd	27403(%rip), %xmm0
-	jbe	0xcb48
-	movq	-464(%rbp), %rax
+	ucomisd	28446(%rip), %xmm0
+	jbe	0xc59e
+	movq	-496(%rbp), %rax
 	movsd	(%rax,%r15,8), %xmm0
-	movaps	%xmm0, -128(%rbp)
-	movsd	(%r13,%rcx,8), %xmm0
-	movsd	%xmm0, -368(%rbp)
+	movaps	%xmm0, -112(%rbp)
+	movq	48(%rbp), %rax
+	movsd	(%rax,%rcx,8), %xmm0
+	movsd	%xmm0, -448(%rbp)
 	leaq	32(%rbp), %rdi
-	movq	%rsi, -208(%rbp)
-	leaq	24(%rbp), %r14
-	movq	%r14, %rdx
-	movq	-144(%rbp), %rcx
-	leaq	-56(%rbp), %r12
-	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r14, %rdi
-	movq	-112(%rbp), %rsi
+	movq	%rsi, -120(%rbp)
+	leaq	24(%rbp), %r12
+	movq	%r12, %rdx
+	movq	-192(%rbp), %r14
+	movq	%r14, %rcx
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	%r12, %rdi
+	movq	-128(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
-	movq	-288(%rbp), %rbx
+	movq	-272(%rbp), %rbx
 	movq	%rbx, %rcx
-	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
-	movq	%r14, %rdi
+	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
-	movq	%r12, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	movq	%r13, %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
 	movq	$0, (%rbx,%r15,8)
-	movq	%r14, %rdi
-	movq	-168(%rbp), %rsi
-	movq	%r12, %rdx
-	movq	-392(%rbp), %r13
+	movq	%r12, %rdi
+	movq	-184(%rbp), %rsi
+	movq	%r13, %rdx
+	movq	-432(%rbp), %r13
 	movq	%r13, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	leaq	-52(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
-	movq	%r14, %rdi
+	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
-	movq	%r12, %rcx
+	leaq	-48(%rbp), %rcx
 	movq	%r13, %r8
-	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	leaq	32(%rbp), %r14
-	movq	%r14, %rdi
-	movq	-240(%rbp), %rsi
+	leaq	-52(%rbp), %r9
+	callq	0x13376 ## symbol stub for: _daxpy
+	leaq	32(%rbp), %r12
+	movq	%r12, %rdi
+	movq	-224(%rbp), %rsi
 	leaq	24(%rbp), %rdx
-	movq	-400(%rbp), %rbx
+	movq	-440(%rbp), %rbx
 	movq	%rbx, %rcx
-	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	leaq	-48(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	56(%rbp), %rax
-	movq	-96(%rbp), %rcx
+	movq	-136(%rbp), %rcx
 	movsd	(%rax,%rcx,8), %xmm0
-	xorpd	27151(%rip), %xmm0
+	xorpd	28183(%rip), %xmm0
 	movlpd	%xmm0, -64(%rbp)
-	movq	%r14, %rdi
+	movq	%r12, %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%rbx, %rdx
-	movq	%r12, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	leaq	-48(%rbp), %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
 	movb	$84, -41(%rbp)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -64(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
-	movq	%r14, %rdx
+	movq	%r12, %rdx
 	leaq	-64(%rbp), %rcx
-	movq	-160(%rbp), %r8
+	movq	-176(%rbp), %r8
 	leaq	-68(%rbp), %r9
-	leaq	-48(%rbp), %rax
+	leaq	-52(%rbp), %rax
 	pushq	%rax
 	pushq	%rbx
-	leaq	-216(%rbp), %rax
+	leaq	-200(%rbp), %rax
+	pushq	%rax
+	leaq	-48(%rbp), %rax
 	pushq	%rax
-	pushq	%r12
 	pushq	%r13
-	callq	0x13514 ## symbol stub for: _dgemv
+	leaq	-48(%rbp), %r13
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
-	movq	%r14, %rdi
-	movq	%r14, %r13
-	movq	-144(%rbp), %r14
+	movq	%r12, %rdi
 	movq	%r14, %rsi
-	movq	%r12, %rdx
+	movq	%r13, %rdx
 	movq	%r14, %rcx
-	movq	%r12, %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	%xmm0, -192(%rbp)
-	movq	%r13, %rdi
+	movq	%r13, %r8
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	%xmm0, -160(%rbp)
+	movq	%r12, %rdi
 	movq	%r14, %rsi
-	movq	%r12, %rdx
+	movq	%r13, %rdx
 	movq	%rbx, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movapd	-128(%rbp), %xmm3
+	leaq	-52(%rbp), %r8
+	callq	0x13382 ## symbol stub for: _ddot
+	movapd	-112(%rbp), %xmm3
 	movapd	%xmm0, %xmm4
 	movapd	%xmm3, %xmm0
-	andpd	26989(%rip), %xmm0
-	movsd	26885(%rip), %xmm1
+	andpd	28023(%rip), %xmm0
+	movsd	27935(%rip), %xmm1
 	ucomisd	%xmm0, %xmm1
-	jbe	0xcda0
+	jbe	0xc800
 	cmpl	$8, 40(%rbp)
-	movq	-96(%rbp), %r12
-	jl	0xcd6e
-	leaq	27872(%rip), %rdi ## literal pool for: "\t\t\t gene %d \t interact with gene %d.\tLinear equation\n"
+	movq	-136(%rbp), %r12
+	jl	0xc7c7
+	leaq	30079(%rip), %rdi ## literal pool for: "\t\t\t Node %d \t interact with Node %d.\tLinear equation\n"
 	movl	%r12d, %esi
 	movl	%r15d, %edx
 	xorl	%eax, %eax
 	movsd	%xmm4, -80(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-80(%rbp), %xmm4
-	movapd	-128(%rbp), %xmm3
-	divsd	-192(%rbp), %xmm4
+	movapd	-112(%rbp), %xmm3
+	divsd	-160(%rbp), %xmm4
 	movl	24(%rbp), %eax
 	imull	%r15d, %eax
 	addl	%r12d, %eax
 	cltq
-	movq	48(%rbp), %r13
-	movsd	%xmm4, (%r13,%rax,8)
-	movsd	26779(%rip), %xmm2
-	jmp	0xcafb
-	nopw	(%rax,%rax)
+	movq	48(%rbp), %rcx
+	movsd	%xmm4, (%rcx,%rax,8)
+	movsd	27828(%rip), %xmm2
+	jmp	0xc555
+	nopw	%cs:(%rax,%rax)
 	cmpl	$8, 40(%rbp)
-	movq	-96(%rbp), %r12
+	movq	-136(%rbp), %r12
 	movsd	%xmm4, -80(%rbp)
-	jl	0xc8f0
-	leaq	27822(%rip), %rdi ## literal pool for: "\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n"
+	jl	0xc340
+	leaq	30019(%rip), %rdi ## literal pool for: "\t\t\t Node %d \t interact with Node %d.\tQuadratic equation\n"
 	movl	%r12d, %esi
 	movl	%r15d, %edx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-80(%rbp), %xmm4
-	movapd	-128(%rbp), %xmm3
-	jmp	0xc8f0
-	nopw	%cs:(%rax,%rax)
-	leaq	-52(%rbp), %rdi
-	movq	%r13, %rsi
-	leaq	-56(%rbp), %r12
-	movq	%r12, %rdx
-	movq	-384(%rbp), %r14
+	movapd	-112(%rbp), %xmm3
+	jmp	0xc340
+	nopl	(%rax)
+	leaq	-56(%rbp), %rdi
+	movq	48(%rbp), %rsi
+	movq	%r13, %rdx
+	movq	-424(%rbp), %r14
 	movq	%r14, %rcx
-	leaq	-48(%rbp), %r13
-	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movslq	-52(%rbp), %rax
+	leaq	-52(%rbp), %rbx
+	movq	%rbx, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movslq	-56(%rbp), %rax
 	leaq	(%r14,%rax,8), %rcx
 	leaq	24(%rbp), %rdi
-	movq	%rbx, %rsi
-	movq	%r12, %rdx
-	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	56(%rbp), %rsi
+	movq	%r13, %rdx
+	movq	%rbx, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	24(%rbp), %eax
 	leal	1(%rax), %ecx
 	imull	%eax, %ecx
 	movl	%ecx, -72(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-72(%rbp), %rdi
-	movq	-248(%rbp), %r12
+	movq	-232(%rbp), %r12
 	movq	%r12, %rsi
-	leaq	-56(%rbp), %rdx
-	movq	-376(%rbp), %r13
-	movq	%r13, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r13, %rdx
+	movq	-416(%rbp), %rbx
+	movq	%rbx, %rcx
+	leaq	-52(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	-72(%rbp), %rdi
 	leaq	-64(%rbp), %rsi
 	movq	%r14, %rdx
-	leaq	-56(%rbp), %r14
-	movq	%r14, %rcx
-	movq	%r13, %r8
-	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	movq	%r13, %rcx
+	movq	%rbx, %r8
+	leaq	-52(%rbp), %r9
+	callq	0x13376 ## symbol stub for: _daxpy
 	leaq	-72(%rbp), %rdi
+	movq	%rdi, %r14
 	movq	%r12, %rsi
-	movq	%r14, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	%xmm0, -128(%rbp)
-	leaq	-72(%rbp), %rdi
-	movq	%r13, %rsi
-	movq	%r14, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
-	movsd	-128(%rbp), %xmm1
-	addsd	26517(%rip), %xmm1
+	movq	%r13, %rdx
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	%xmm0, -112(%rbp)
+	movq	%r14, %rdi
+	movq	%rbx, %rsi
+	movq	%r13, %rdx
+	callq	0x1339a ## symbol stub for: _dnrm2
+	movsd	-112(%rbp), %xmm1
+	addsd	27562(%rip), %xmm1
 	divsd	%xmm1, %xmm0
-	movsd	%xmm0, -128(%rbp)
+	movsd	%xmm0, -112(%rbp)
 	cmpl	$6, 40(%rbp)
-	jl	0xc710
-	leaq	27612(%rip), %rdi ## literal pool for: "\t\tdelta_BF: %f\n"
-	movsd	-128(%rbp), %xmm0
+	jl	0xc160
+	leaq	28689(%rip), %rdi ## literal pool for: "\t\tdelta_BF: %f\n"
+	movsd	-112(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	jmp	0xc710
-	movq	-272(%rbp), %rax
-	movl	%eax, %r14d
+	callq	0x133c4 ## symbol stub for: _printf
+	jmp	0xc160
+	movq	-344(%rbp), %rax
+	movl	%eax, %ebx
 	cmpl	$4, 40(%rbp)
-	jl	0xcef7
-	leaq	27588(%rip), %rdi ## literal pool for: "\t number of iteration is: %d.\nExiting constrained_MLf\n"
-	movl	%r14d, %esi
+	jl	0xc950
+	leaq	28666(%rip), %rdi ## literal pool for: "\t number of iteration is: %d.\nExiting constrained_MLf\n"
+	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
-	leaq	-52(%rbp), %r13
-	leaq	-56(%rbp), %r15
-	leaq	-48(%rbp), %r14
+	callq	0x133c4 ## symbol stub for: _printf
+	leaq	-56(%rbp), %r13
+	leaq	-48(%rbp), %r15
+	leaq	-52(%rbp), %r14
 	movq	%r13, %rdi
 	movq	48(%rbp), %rsi
 	movq	%r15, %rdx
-	movq	-568(%rbp), %rbx
+	movq	-600(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -64(%rbp)
 	leaq	-64(%rbp), %rsi
 	movq	%r13, %rdi
 	movq	%rbx, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	24(%rbp), %eax
 	testl	%eax, %eax
 	movq	64(%rbp), %r10
-	jle	0xcfaa
+	jle	0xca09
 	leal	1(%rax), %edx
 	xorl	%ecx, %ecx
 	xorl	%esi, %esi
-	movq	-488(%rbp), %rdi
+	movq	-408(%rbp), %rdi
 	movq	56(%rbp), %r8
-	movsd	26316(%rip), %xmm1
-	movapd	26404(%rip), %xmm2
-	nopl	(%rax)
+	movsd	27363(%rip), %xmm1
+	movapd	27435(%rip), %xmm2
+	nopw	%cs:(%rax,%rax)
 	movslq	%ecx, %rcx
 	movsd	(%rbx,%rcx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%rbx,%rcx,8)
 	movsd	(%r8,%rsi,8), %xmm0
 	xorpd	%xmm2, %xmm0
 	mulsd	(%rdi,%rsi,8), %xmm0
 	movsd	%xmm0, (%r10,%rsi,8)
-	addq	$1, %rsi
+	incq	%rsi
 	addl	%edx, %ecx
 	cmpq	%rsi, %rax
-	jne	0xcf70
+	jne	0xc9d0
 	movl	%eax, %edx
 	notl	%edx
 	addl	%ecx, %edx
 	movl	%edx, -72(%rbp)
 	movb	$78, -41(%rbp)
 	movabsq	$4607182418800017408, %rcx
 	movq	%rcx, -64(%rbp)
-	movl	%eax, -428(%rbp)
+	movl	%eax, -472(%rbp)
 	subq	$8, %rsp
 	leaq	-41(%rbp), %rdi
 	leaq	24(%rbp), %rsi
-	leaq	-428(%rbp), %rdx
+	leaq	-472(%rbp), %rdx
 	leaq	-64(%rbp), %rcx
 	leaq	-68(%rbp), %r9
 	movq	%rbx, %r8
 	pushq	%r14
 	pushq	%r10
-	leaq	-216(%rbp), %rax
+	leaq	-200(%rbp), %rax
 	pushq	%rax
 	pushq	%r15
 	movq	%rbx, %r14
-	movq	-496(%rbp), %rbx
+	movq	-520(%rbp), %rbx
 	pushq	%rbx
-	callq	0x13514 ## symbol stub for: _dgemv
+	callq	0x1338e ## symbol stub for: _dgemv
 	addq	$48, %rsp
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-488(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-160(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-304(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-408(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-176(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-328(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-88(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-264(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-256(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-240(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-504(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-144(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-528(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-192(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-184(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-400(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-392(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-288(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-248(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-384(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-376(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-520(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movsd	-280(%rbp), %xmm0
-	addq	$552, %rsp
+	callq	0x133ac ## symbol stub for: _free
+	movq	-440(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-432(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-272(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-232(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-424(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-416(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-544(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movsd	-264(%rbp), %xmm0
+	addq	$584, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
 	xorl	%edx, %edx
 	testb	$1, %r8b
-	jne	0xc616
-	jmp	0xc64c
+	jne	0xc066
+	jmp	0xc09c
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 _cv_gene_nets_support_adaEN:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
@@ -9568,215 +9640,215 @@
 	imull	%ebx, %eax
 	movl	%ebx, -104(%rbp)
 	movl	%eax, -136(%rbp)
 	movl	%eax, -148(%rbp)
 	movslq	%r15d, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -344(%rbp)
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -248(%rbp)
 	movslq	%ebx, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -112(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
 	movq	%rbx, -176(%rbp)
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -168(%rbp)
 	movl	$8, %esi
 	movq	%r13, -80(%rbp)
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -368(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -264(%rbp)
 	movl	%r12d, %eax
 	cltd
 	idivl	%r14d
 	movl	%eax, %r13d
 	movl	%eax, -56(%rbp)
 	movl	%r12d, %ebx
 	subl	%eax, %ebx
 	movl	-216(%rbp), %r14d
 	movslq	%r14d, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -312(%rbp)
 	movl	$8, %esi
 	movq	%r12, -384(%rbp)
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -240(%rbp)
 	imull	-116(%rbp), %r14d
 	movl	%r14d, -44(%rbp)
 	movq	%rbx, -408(%rbp)
 	movl	%ebx, %eax
 	movl	-104(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -372(%rbp)
 	imull	%ecx, %r13d
 	movl	%r13d, -144(%rbp)
 	movslq	%eax, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -232(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -160(%rbp)
 	movslq	%r13d, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -280(%rbp)
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -208(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -328(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
 	movl	48(%rbp), %r12d
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -272(%rbp)
 	movl	$8, %esi
 	movq	-176(%rbp), %rbx
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -400(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -392(%rbp)
 	movabsq	$4681608360884174848, %rax
 	movq	%rax, -128(%rbp)
 	cmpl	$2, %r12d
-	jl	0xd3a8
-	leaq	27244(%rip), %rdi ## literal pool for: "\t\ti_alpha %d; \t Enter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n"
+	jl	0xce08
+	leaq	28654(%rip), %rdi ## literal pool for: "\t\ti_alpha %d; \t Enter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n"
 	movl	72(%rbp), %esi
 	movl	-216(%rbp), %edx
 	movl	-116(%rbp), %r13d
 	movl	%r13d, %ecx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	cmpl	$4, %r12d
-	jle	0xd3db
-	leaq	26641(%rip), %rbx ## literal pool for: "\n\t\t\t\t\tEnter Function: ridge_cvf. %d-fold cross validation.\n"
+	jbe	0xce3b
+	leaq	27713(%rip), %rbx ## literal pool for: "\n\t\t\t\t\tEnter Function: ridge_cvf. %d-fold cross validation.\n"
 	movq	%rbx, %rdi
 	movl	%r13d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
 	movl	$0, -120(%rbp)
 	movq	%rbx, %rdi
 	movl	%r13d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movb	$1, %al
 	movl	%eax, -184(%rbp)
-	jmp	0xd3fa
+	jmp	0xce5a
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
 	movl	$0, -120(%rbp)
 	movl	$0, -184(%rbp)
 	movq	-168(%rbp), %r14
 	movq	-208(%rbp), %r12
 	movl	-116(%rbp), %r13d
-	jmp	0xd408
+	jmp	0xce68
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
 	movl	$0, -120(%rbp)
 	movl	$0, -184(%rbp)
 	movq	-168(%rbp), %r14
 	movq	-208(%rbp), %r12
 	movl	-136(%rbp), %eax
 	movq	88(%rbp), %rbx
 	movl	$0, -84(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -176(%rbp)
 	movl	$8, %esi
 	movq	-80(%rbp), %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -224(%rbp)
 	movb	$78, -58(%rbp)
 	movb	$78, -57(%rbp)
 	movl	-104(%rbp), %eax
 	movl	%eax, -300(%rbp)
 	movl	%eax, -296(%rbp)
 	movl	%eax, -292(%rbp)
 	movl	%eax, -140(%rbp)
 	cmpl	$0, 72(%rbp)
-	je	0xd479
+	je	0xced9
 	movsd	(%rbx), %xmm0
 	movsd	%xmm0, -80(%rbp)
-	jmp	0xdcf8
+	jmp	0xd757
 	cmpl	$0, 40(%rbp)
-	jle	0xdb36
-	movsd	24997(%rip), %xmm0
-	movsd	25133(%rip), %xmm1
+	jle	0xd592
+	movsd	26037(%rip), %xmm0
+	movsd	26157(%rip), %xmm1
 	movsd	%xmm0, -136(%rbp)
 	xorl	%esi, %esi
 	movq	-112(%rbp), %r15
 	movq	%r14, %rbx
-	jmp	0xd4b9
+	jmp	0xcf19
 	nopw	%cs:(%rax,%rax)
 	cmpl	40(%rbp), %esi
-	jge	0xda3a
+	jge	0xd498
 	movsd	%xmm1, -200(%rbp)
 	movslq	%esi, %rax
 	movq	-192(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
 	movsd	%xmm0, -80(%rbp)
 	movq	$0, -128(%rbp)
 	testl	%r13d, %r13d
-	jle	0xd9f0
+	jle	0xd450
 	xorl	%ebx, %ebx
-	jmp	0xd52e
+	jmp	0xcf8e
 	nopw	(%rax,%rax)
 	leaq	-144(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%rcx, %rdx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movapd	%xmm0, %xmm1
 	addsd	-128(%rbp), %xmm1
 	movsd	%xmm1, -128(%rbp)
 	movl	-116(%rbp), %r13d
 	movl	-104(%rbp), %ebx
 	cmpl	%r13d, %ebx
 	movq	-208(%rbp), %r12
-	je	0xd9e0
+	je	0xd440
 	movl	48(%rbp), %eax
 	cmpl	$7, %eax
-	jl	0xd546
-	leaq	26239(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t crossValidation %d/Kcv\n\n"
+	jl	0xcfa6
+	leaq	27311(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t crossValidation %d/Kcv\n\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %r13d
 	movl	%r13d, %r15d
 	imull	%ebx, %r15d
-	addl	$1, %ebx
+	incl	%ebx
 	movl	%r13d, %eax
 	movl	%ebx, -104(%rbp)
 	imull	%ebx, %eax
 	movl	%eax, %ebx
 	movl	16(%rbp), %eax
 	movl	%r15d, %ecx
 	imull	%eax, %ecx
@@ -9786,90 +9858,91 @@
 	imull	%r13d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r12
 	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r15d, %r15d
-	je	0xd600
+	je	0xd060
 	movl	16(%rbp), %eax
 	imull	%r15d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	movq	%r14, %rsi
 	leaq	-52(%rbp), %rdx
 	movq	-160(%rbp), %rcx
 	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %ebx
 	leaq	-44(%rbp), %r12
-	je	0xd634
+	je	0xd094
 	movl	24(%rbp), %eax
 	subl	%ebx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -88(%rbp)
 	imull	%ebx, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r14,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	movq	-160(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	leaq	-88(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	jmp	0xd634
+	callq	0x1337c ## symbol stub for: _dcopy
+	jmp	0xd094
+	nop
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%ebx, %ecx
 	imull	%eax, %ecx
 	imull	%ebx, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	leaq	-44(%rbp), %r14
 	movq	%r14, %rdi
 	leaq	-52(%rbp), %rdx
 	movq	-160(%rbp), %rcx
 	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r14, %r12
 	movl	16(%rbp), %eax
 	imull	%eax, %r13d
 	imull	%r15d, %eax
 	cltq
 	movq	-256(%rbp), %r14
 	leaq	(%r14,%rax,8), %rsi
 	movl	%r13d, -44(%rbp)
 	movq	%r12, %rdi
 	leaq	-52(%rbp), %r13
 	movq	%r13, %rdx
 	movq	-280(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r15d, %r15d
-	je	0xd700
+	je	0xd160
 	imull	16(%rbp), %r15d
 	movl	%r15d, -44(%rbp)
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	movq	%r13, %rdx
 	movq	-232(%rbp), %r12
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %ebx
 	movq	%r13, %r14
 	movq	-112(%rbp), %r9
 	movq	-168(%rbp), %r13
 	leaq	-56(%rbp), %r15
-	je	0xd742
+	je	0xd1a2
 	movl	24(%rbp), %eax
 	subl	%ebx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -88(%rbp)
 	imull	%ebx, %ecx
 	movslq	%ecx, %rax
@@ -9877,33 +9950,32 @@
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	leaq	(%r12,%rax,8), %rcx
 	leaq	-88(%rbp), %rdi
 	movq	%r14, %rdx
 	leaq	-48(%rbp), %r8
 	movq	%r9, %rbx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%rbx, %r9
-	jmp	0xd742
+	jmp	0xd1a2
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%ebx, %ecx
 	imull	%eax, %ecx
 	imull	%ebx, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%r12, %rdi
 	movq	%r13, %rdx
 	movq	-232(%rbp), %r12
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r13, %r14
 	movq	-112(%rbp), %r9
 	movq	-168(%rbp), %r13
 	leaq	-56(%rbp), %r15
 	movl	16(%rbp), %edx
 	movq	%r12, %rdi
 	movq	-160(%rbp), %rsi
@@ -9920,61 +9992,61 @@
 	leaq	-92(%rbp), %r13
 	movq	%r13, %rdi
 	movq	%rbx, %rsi
 	movq	%r14, %rdx
 	movq	-224(%rbp), %r12
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	movq	%r13, %rdi
 	leaq	-72(%rbp), %r13
 	movq	%r13, %rsi
 	movq	%r12, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	16(%rbp), %r8d
 	testl	%r8d, %r8d
-	jle	0xd7e0
+	jle	0xd240
 	cmpl	$1, %r8d
-	jne	0xd7f0
+	jne	0xd250
 	xorl	%ecx, %ecx
-	movsd	24152(%rip), %xmm1
-	jmp	0xd843
+	movsd	25192(%rip), %xmm1
+	jmp	0xd2a3
 	nopw	(%rax,%rax)
 	xorl	%r8d, %r8d
 	leaq	16(%rbp), %r14
-	jmp	0xd86c
+	jmp	0xd2cc
 	nopl	(%rax)
 	movl	%r8d, %edx
 	andl	$-2, %edx
 	leal	1(%r8), %esi
 	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
-	movsd	24099(%rip), %xmm1
+	movsd	25139(%rip), %xmm1
 	nopl	(%rax)
 	movslq	%ebx, %rbx
 	movsd	(%r12,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r12,%rbx,8)
 	leal	(%rsi,%rbx), %eax
 	cltq
 	movsd	(%r12,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r12,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
 	cmpq	%rcx, %rdx
-	jne	0xd810
+	jne	0xd270
 	testb	$1, %r8b
 	leaq	16(%rbp), %r14
-	je	0xd86c
+	je	0xd2cc
 	movl	%r8d, %eax
 	imull	%ecx, %eax
 	addl	%ecx, %eax
 	cltq
 	movq	-224(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
@@ -9998,305 +10070,305 @@
 	pushq	%rax
 	leaq	-296(%rbp), %rax
 	pushq	%rax
 	pushq	-280(%rbp)
 	leaq	-300(%rbp), %rax
 	pushq	%rax
 	pushq	-224(%rbp)
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	$0, -44(%rbp)
 	cmpl	$0, 16(%rbp)
-	movapd	23962(%rip), %xmm1
+	movapd	24986(%rip), %xmm1
 	movq	%r13, %r12
 	movq	-112(%rbp), %r13
 	movq	%r15, %r14
 	movq	-208(%rbp), %r15
-	jle	0xd959
+	jle	0xd3b8
 	xorl	%eax, %eax
 	nopl	(%rax,%rax)
 	cltq
 	leaq	(%r15,%rax,8), %rdx
 	movq	-176(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r8
 	movsd	(%r13,%rax,8), %xmm0
 	xorpd	%xmm1, %xmm0
 	movlpd	%xmm0, -72(%rbp)
 	movq	%r14, %rdi
 	movq	%r12, %rsi
 	movq	%rbx, %rcx
 	leaq	16(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	movapd	23877(%rip), %xmm1
+	callq	0x13376 ## symbol stub for: _daxpy
+	movapd	24901(%rip), %xmm1
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	16(%rbp), %eax
-	jl	0xd910
+	jl	0xd370
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	movl	$0, -44(%rbp)
 	cmpl	$0, -56(%rbp)
 	leaq	16(%rbp), %r15
 	leaq	-52(%rbp), %rcx
 	movq	-168(%rbp), %r13
 	movq	-176(%rbp), %rbx
-	jle	0xd4f0
+	jle	0xcf50
 	movq	%r15, %rdi
 	movq	%r12, %r14
 	movq	%r12, %rsi
 	movq	%r13, %rdx
 	movq	%rcx, %r12
 	movq	%rbx, %r8
+	nop
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r12, %rcx
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	-56(%rbp), %eax
-	jge	0xd4f0
+	jge	0xcf50
 	imull	16(%rbp), %eax
 	cltq
 	leaq	(%rbx,%rax,8), %r8
 	movq	%r15, %rdi
 	movq	%r14, %rsi
 	movq	%r13, %rdx
 	movq	%r12, %rcx
-	jmp	0xd9a0
+	jmp	0xd400
 	nopw	%cs:(%rax,%rax)
 	movl	-84(%rbp), %esi
 	movq	-168(%rbp), %rbx
 	movq	-112(%rbp), %r15
-	jmp	0xd9f4
+	jmp	0xd454
 	xorpd	%xmm1, %xmm1
-	addl	$1, %esi
+	incl	%esi
 	movl	%esi, -84(%rbp)
 	movl	48(%rbp), %eax
 	cmpl	$6, %eax
-	jl	0xda1d
-	leaq	25044(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t Test rho ratio %f; (%d/Nrho)\t error: %f.\n"
+	jl	0xd47c
+	leaq	26117(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t Test rho ratio %f; (%d/Nrho)\t error: %f.\n"
 	movsd	-80(%rbp), %xmm0
 	movb	$2, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-84(%rbp), %esi
 	movsd	-128(%rbp), %xmm1
 	cmpl	$2, %esi
-	jl	0xd4b0
+	jl	0xcf10
 	ucomisd	-200(%rbp), %xmm1
-	jb	0xd4b0
-	addl	$-1, %esi
+	jb	0xcf10
+	decl	%esi
 	movl	%esi, -84(%rbp)
 	cmpb	$0, -184(%rbp)
-	je	0xda5c
-	leaq	25028(%rip), %rdi ## literal pool for: "\t\t\t\t\tExit RidgeCV. sigma2R: %f\t"
+	je	0xd4ba
+	leaq	26102(%rip), %rdi ## literal pool for: "\t\t\t\t\tExit RidgeCV. sigma2R: %f\t"
 	movsd	-136(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-84(%rbp), %esi
 	movsd	-128(%rbp), %xmm1
 	movapd	%xmm1, %xmm0
 	cmpl	$1, %esi
 	movq	-320(%rbp), %r14
 	movq	-248(%rbp), %r12
-	je	0xda80
+	je	0xd4de
 	movsd	-200(%rbp), %xmm0
 	movl	-148(%rbp), %eax
 	cmpl	40(%rbp), %esi
-	je	0xda8f
+	je	0xd4ed
 	movapd	%xmm0, %xmm1
-	addl	$-1, %eax
+	decl	%eax
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
-	addl	$-1, %esi
+	decl	%esi
 	movslq	%esi, %rax
 	movl	24(%rbp), %ecx
 	cvtsi2sd	%ecx, %xmm2
 	movq	-192(%rbp), %rdx
 	mulsd	(%rdx,%rax,8), %xmm2
 	movl	%ecx, %eax
 	subl	-56(%rbp), %eax
 	divsd	%xmm0, %xmm1
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
 	cmpb	$0, -184(%rbp)
 	movsd	%xmm1, -104(%rbp)
-	je	0xdafc
-	leaq	24919(%rip), %rdi ## literal pool for: "sigma2learnt: %f\n"
+	je	0xd558
+	leaq	25995(%rip), %rdi ## literal pool for: "sigma2learnt: %f\n"
 	movsd	%xmm0, -136(%rbp)
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
 	movsd	%xmm2, -80(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-136(%rbp), %xmm0
 	movsd	-80(%rbp), %xmm2
 	divsd	%xmm0, %xmm2
 	movl	48(%rbp), %eax
 	testl	%eax, %eax
-	je	0xdb6c
+	je	0xd5c8
 	movl	16(%rbp), %edx
 	movq	-256(%rbp), %rdi
 	movq	%r14, %rsi
 	movapd	%xmm2, %xmm0
 	movl	24(%rbp), %ecx
 	movq	%r12, %r8
 	movq	%r15, %r9
 	pushq	%rax
 	pushq	%rbx
 	callq	_constrained_ridge_cff
 	movsd	-104(%rbp), %xmm6
 	addq	$16, %rsp
-	jmp	0xdbc5
+	jmp	0xd621
 	xorps	%xmm0, %xmm0
 	movsd	%xmm0, -200(%rbp)
-	movsd	23271(%rip), %xmm0
+	movsd	24315(%rip), %xmm0
 	movsd	%xmm0, -136(%rbp)
 	xorl	%esi, %esi
 	movq	-112(%rbp), %r15
 	movq	%r14, %rbx
 	cmpb	$0, -184(%rbp)
-	jne	0xda43
-	jmp	0xda5c
-	leaq	25243(%rip), %rdi ## literal pool for: "Step 1: ridge CV; find rho : %f\n"
+	jne	0xd4a1
+	jmp	0xd4ba
+	leaq	26657(%rip), %rdi ## literal pool for: "Step 1: ridge CV; find rho : %f\n"
 	movapd	%xmm2, %xmm0
 	movb	$1, %al
 	movsd	%xmm2, -80(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	16(%rbp), %edx
 	movq	-256(%rbp), %rdi
 	movq	%r14, %rsi
 	movsd	-80(%rbp), %xmm0
 	movl	24(%rbp), %ecx
 	movq	%r12, %r8
 	movq	%r15, %r9
 	pushq	$0
 	pushq	%rbx
 	callq	_constrained_ridge_cff
 	addq	$16, %rsp
 	movsd	%xmm0, -80(%rbp)
-	leaq	25425(%rip), %rdi ## literal pool for: "Step 2: ridge; calculate weights."
-	callq	0x13556 ## symbol stub for: _puts
+	leaq	26875(%rip), %rdi ## literal pool for: "Step 2: ridge; calculate weights."
+	callq	0x133d0 ## symbol stub for: _puts
 	movsd	-104(%rbp), %xmm6
 	movsd	-80(%rbp), %xmm0
 	movq	56(%rbp), %rbx
 	movq	88(%rbp), %rax
 	movq	64(%rbp), %r8
 	movl	-92(%rbp), %r15d
 	testl	%r15d, %r15d
-	jle	0xdbe7
+	jle	0xd643
 	cmpl	$1, %r15d
-	jne	0xdbee
+	jne	0xd64a
 	xorl	%ecx, %ecx
-	jmp	0xdca6
+	jmp	0xd707
 	xorl	%edx, %edx
-	jmp	0xdce7
+	jmp	0xd746
 	movl	%r15d, %ecx
 	andl	$-2, %ecx
-	leaq	-2(%rcx), %rsi
-	movq	%rsi, %rdx
-	shrq	%rdx
-	addq	$1, %rdx
-	testq	%rsi, %rsi
-	je	0xebb6
-	movq	%rdx, %rdi
+	leaq	-2(%rcx), %rdx
+	movq	%rdx, %rsi
+	shrq	%rsi
+	incq	%rsi
+	testq	%rdx, %rdx
+	je	0xe619
+	movq	%rsi, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
-	xorl	%esi, %esi
-	movapd	23249(%rip), %xmm5
-	movapd	23161(%rip), %xmm1
-	movapd	23169(%rip), %xmm2
-	nop
-	movupd	(%r12,%rsi,8), %xmm3
+	xorl	%edx, %edx
+	movapd	24297(%rip), %xmm5
+	movapd	24193(%rip), %xmm1
+	movapd	24201(%rip), %xmm2
+	nopw	(%rax,%rax)
+	movupd	(%r12,%rdx,8), %xmm3
 	addpd	%xmm5, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divpd	%xmm3, %xmm4
-	movupd	%xmm4, (%rbx,%rsi,8)
-	movupd	16(%r12,%rsi,8), %xmm3
+	movupd	%xmm4, (%rbx,%rdx,8)
+	movupd	16(%r12,%rdx,8), %xmm3
 	addpd	%xmm5, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divpd	%xmm3, %xmm4
-	movupd	%xmm4, 16(%rbx,%rsi,8)
-	addq	$4, %rsi
-	addq	$2, %rdi
-	jne	0xdc30
-	testb	$1, %dl
-	je	0xdc9e
-	movupd	(%r12,%rsi,8), %xmm2
-	addpd	23147(%rip), %xmm2
-	andpd	23059(%rip), %xmm2
-	movapd	23067(%rip), %xmm1
+	movupd	%xmm4, 16(%rbx,%rdx,8)
+	addq	$4, %rdx
+	addq	$-2, %rdi
+	jne	0xd690
+	testb	$1, %sil
+	je	0xd6ff
+	movupd	(%r12,%rdx,8), %xmm2
+	addpd	24186(%rip), %xmm2
+	andpd	24082(%rip), %xmm2
+	movapd	24090(%rip), %xmm1
 	divpd	%xmm2, %xmm1
-	movupd	%xmm1, (%rbx,%rsi,8)
+	movupd	%xmm1, (%rbx,%rdx,8)
 	movl	%r15d, %edx
 	cmpq	%r15, %rcx
-	je	0xdce7
-	movsd	22930(%rip), %xmm5
-	movapd	23018(%rip), %xmm1
-	movsd	22898(%rip), %xmm2
+	je	0xd746
+	movsd	23969(%rip), %xmm5
+	movapd	24041(%rip), %xmm1
+	movsd	23937(%rip), %xmm2
 	nop
 	movsd	(%r12,%rcx,8), %xmm3
 	addsd	%xmm5, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divsd	%xmm3, %xmm4
 	movsd	%xmm4, (%rbx,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %r15
-	jne	0xdcc0
+	jne	0xd720
 	movl	%r15d, %edx
 	movl	%edx, -44(%rbp)
 	movsd	%xmm6, (%r8)
 	movsd	%xmm0, -80(%rbp)
 	movsd	%xmm0, (%rax)
 	movl	%r15d, %eax
 	imull	%r13d, %eax
 	movl	%eax, -84(%rbp)
 	movslq	%eax, %r14
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -184(%rbp)
 	movl	$8, %esi
 	movq	%r14, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -352(%rbp)
 	movslq	%r13d, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -336(%rbp)
 	movq	$0, -288(%rbp)
 	testl	%r13d, %r13d
-	jle	0xde5c
+	jle	0xd8ba
 	xorl	%r12d, %r12d
 	leaq	-48(%rbp), %r14
-	nopl	(%rax)
+	nopl	(%rax,%rax)
 	imull	%r12d, %r15d
 	movslq	%r15d, %rax
 	movq	-184(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r13
 	leaq	-92(%rbp), %rdi
 	leaq	-288(%rbp), %rsi
 	leaq	-120(%rbp), %rdx
 	movq	%r13, %rcx
 	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %r8d
 	movl	$0, %eax
 	testl	%r8d, %r8d
-	jle	0xde43
+	jle	0xd8a2
 	leaq	-1(%r8), %rax
 	movl	%r8d, %ecx
 	andl	$3, %ecx
 	cmpq	$3, %rax
-	jae	0xddc0
+	jae	0xd820
 	xorl	%edx, %edx
 	movabsq	$4607182418800017408, %rbx
-	jmp	0xde24
+	jmp	0xd884
 	nopl	(%rax)
 	movl	%r8d, %r10d
 	andl	$-4, %r10d
 	leal	(%r8,%r8), %r9d
 	addl	$2, %r9d
 	leal	4(,%r8,4), %r11d
 	leal	1(%r8), %r15d
@@ -10315,73 +10387,72 @@
 	movq	%rbx, (%r13,%rax,8)
 	leal	(%rdi,%rsi), %eax
 	cltq
 	movq	%rbx, (%r13,%rax,8)
 	addq	$4, %rdx
 	addl	%r11d, %esi
 	cmpq	%rdx, %r10
-	jne	0xddf0
+	jne	0xd850
 	testq	%rcx, %rcx
-	je	0xde40
+	je	0xd89f
 	leal	1(%r8), %eax
 	imull	%eax, %edx
 	movslq	%edx, %rdx
 	movq	%rbx, (%r13,%rdx,8)
 	addl	%eax, %edx
-	addq	$-1, %rcx
-	jne	0xde30
+	decq	%rcx
+	jne	0xd890
 	movl	%r8d, %eax
 	movl	%eax, -44(%rbp)
-	addl	$1, %r12d
+	incl	%r12d
 	movl	-116(%rbp), %r13d
 	cmpl	%r13d, %r12d
-	je	0xde5c
+	je	0xd8ba
 	movl	-92(%rbp), %r15d
-	jmp	0xdd60
+	jmp	0xd7c0
 	leaq	-84(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
 	movq	-184(%rbp), %rsi
 	movq	-352(%rbp), %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$0, -216(%rbp)
 	movl	48(%rbp), %r12d
 	movq	-264(%rbp), %r14
 	movq	-240(%rbp), %rdx
 	movq	-176(%rbp), %r15
-	jle	0xe8b9
+	jle	0xe317
 	movl	%r13d, %eax
 	movq	%rax, -424(%rbp)
-	movsd	22397(%rip), %xmm0
+	movsd	23439(%rip), %xmm0
 	movsd	%xmm0, -216(%rbp)
 	xorl	%ecx, %ecx
-	jmp	0xded8
-	nop
-	addq	$1, %rcx
+	jmp	0xd937
+	nopl	(%rax)
+	incq	%rcx
 	cmpq	-384(%rbp), %rcx
 	movq	-240(%rbp), %rdx
-	jge	0xe8b9
+	jge	0xe317
 	movq	$0, -128(%rbp)
 	testl	%r13d, %r13d
 	movq	%rcx, -192(%rbp)
-	jle	0xe6c0
+	jle	0xe120
 	xorl	%ebx, %ebx
-	jmp	0xdf17
+	jmp	0xd977
 	nopw	%cs:(%rax,%rax)
-	nop
 	movq	-136(%rbp), %rax
 	movq	%rax, %rbx
 	cmpq	-424(%rbp), %rax
-	je	0xe690
+	je	0xe0f0
 	cmpl	$4, %r12d
-	jl	0xdf2d
-	leaq	23869(%rip), %rdi ## literal pool for: "\t\t %d/Kcv cross validation.\n"
+	jl	0xd98d
+	leaq	24941(%rip), %rdi ## literal pool for: "\t\t %d/Kcv cross validation.\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %r12d
 	movl	%r12d, %r13d
 	imull	%ebx, %r13d
 	movq	%rbx, -104(%rbp)
 	leaq	1(%rbx), %rax
 	movq	%rax, -136(%rbp)
 	movl	%eax, %r14d
@@ -10395,169 +10466,168 @@
 	imull	%r12d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rbx
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %rdx
 	movq	-208(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r13d, %r13d
-	je	0xe000
+	je	0xda60
 	movl	16(%rbp), %eax
 	imull	%r13d, %eax
 	movl	%eax, -44(%rbp)
 	movq	%rbx, %rdi
 	movq	%r15, %rsi
 	leaq	-52(%rbp), %rdx
 	movq	-160(%rbp), %rcx
 	leaq	-48(%rbp), %r15
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %r14d
-	je	0xe033
+	je	0xda93
 	movl	24(%rbp), %eax
 	subl	%r14d, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -88(%rbp)
 	imull	%r14d, %ecx
 	movslq	%ecx, %rax
 	movq	-320(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	movq	-160(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	leaq	-88(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
-	jmp	0xe02b
+	jmp	0xda8b
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%r14d, %ecx
 	imull	%eax, %ecx
 	imull	%r14d, %eax
 	cltq
 	leaq	(%r15,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %rdx
 	movq	-160(%rbp), %rcx
 	leaq	-48(%rbp), %r15
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %eax
 	imull	%eax, %r12d
 	imull	%r13d, %eax
 	cltq
 	movq	%r15, %r8
 	movq	-256(%rbp), %r15
 	leaq	(%r15,%rax,8), %rsi
 	movl	%r12d, -44(%rbp)
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %r12
 	movq	%r12, %rdx
 	movq	-280(%rbp), %rcx
 	movq	%r8, %rbx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r13d, %r13d
 	leaq	-44(%rbp), %rdi
-	je	0xe0d0
+	je	0xdb30
 	imull	16(%rbp), %r13d
 	movl	%r13d, -44(%rbp)
 	movq	%r15, %rsi
 	movq	%r12, %rdx
 	movq	-232(%rbp), %r13
 	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %r14d
-	je	0xe0fe
+	je	0xdb5e
 	movl	24(%rbp), %eax
 	subl	%r14d, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
 	movl	%eax, -88(%rbp)
 	imull	%r14d, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r15,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	leaq	(,%rax,8), %rcx
 	addq	%r13, %rcx
 	leaq	-88(%rbp), %rdi
 	movq	%r12, %rdx
-	jmp	0xe0f6
+	jmp	0xdb56
 	nopl	(%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%r14d, %ecx
 	imull	%eax, %ecx
 	imull	%r14d, %eax
 	cltq
 	leaq	(%r15,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%r12, %rdx
 	movq	-232(%rbp), %r13
 	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	leaq	-372(%rbp), %r14
 	movq	%r14, %rdi
 	movq	-160(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	-272(%rbp), %r15
 	movq	%r15, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r14, %rdi
 	movq	%r13, %rsi
 	movq	%r12, %rdx
 	movq	-328(%rbp), %r14
 	movq	%r14, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %r8d
 	movq	%r14, %rdi
 	movq	%r15, %rsi
 	movq	-400(%rbp), %rdx
 	movq	-392(%rbp), %rcx
 	movq	-408(%rbp), %r15
 	movl	%r15d, %r9d
 	callq	_centerYX
 	movq	-192(%rbp), %rcx
 	testq	%rcx, %rcx
-	je	0xe1b0
+	je	0xdc10
 	movq	-336(%rbp), %rax
 	movq	-104(%rbp), %rdx
 	movsd	(%rax,%rdx,8), %xmm3
 	movq	-248(%rbp), %r13
 	movsd	-360(%rbp), %xmm4
 	movq	%r15, %r11
 	movq	-344(%rbp), %r14
 	movq	56(%rbp), %r12
 	movsd	-80(%rbp), %xmm2
-	jmp	0xe273
+	jmp	0xdcd3
 	nopl	(%rax)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -72(%rbp)
 	leaq	16(%rbp), %rdi
 	leaq	-72(%rbp), %rsi
 	leaq	-120(%rbp), %r12
 	movq	%r12, %rdx
 	movq	-112(%rbp), %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, -72(%rbp)
 	leaq	-92(%rbp), %rdi
 	leaq	-72(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	-248(%rbp), %rcx
 	movq	%rcx, %r13
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %ecx
 	movq	%r14, %rdi
 	movq	-272(%rbp), %r12
 	movq	%r12, %rsi
 	movq	-344(%rbp), %rbx
 	movq	%rbx, %rdx
 	movsd	-80(%rbp), %xmm0
@@ -10611,32 +10681,32 @@
 	movq	%r11, %r12
 	pushq	%r11
 	pushq	%r10
 	pushq	-440(%rbp)
 	callq	_Weighted_LassoSf_MLf_adaEN
 	addq	$80, %rsp
 	cmpl	$4, %r15d
-	jl	0xe360
-	leaq	22885(%rip), %rdi ## literal pool for: "\t\t\t step 1 SML lasso regression, lambda: %f.\n"
+	jl	0xddc0
+	leaq	23957(%rip), %rdi ## literal pool for: "\t\t\t step 1 SML lasso regression, lambda: %f.\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	16(%rbp), %r9d
 	movq	-328(%rbp), %rdi
 	movq	-272(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r13, %rcx
 	movq	-112(%rbp), %r8
 	movsd	-80(%rbp), %xmm0
 	pushq	-200(%rbp)
 	pushq	%r12
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	leaq	23439(%rip), %rdi ## literal pool for: "\t\t\t step 2 SML ZeroRegression."
-	callq	0x13556 ## symbol stub for: _puts
-	jmp	0xe392
+	leaq	24885(%rip), %rdi ## literal pool for: "\t\t\t step 2 SML ZeroRegression."
+	callq	0x133d0 ## symbol stub for: _puts
+	jmp	0xddf2
 	movl	16(%rbp), %r9d
 	movq	-328(%rbp), %rdi
 	movq	-272(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r13, %rcx
 	movq	-112(%rbp), %r8
 	movsd	-80(%rbp), %xmm0
@@ -10649,63 +10719,63 @@
 	leaq	-92(%rbp), %r13
 	movq	%r13, %rdi
 	movq	-368(%rbp), %rsi
 	leaq	-52(%rbp), %r14
 	movq	%r14, %rdx
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	movq	%r13, %rdi
 	leaq	-72(%rbp), %rsi
 	movq	%r12, %rdx
 	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	16(%rbp), %r10d
 	testl	%r10d, %r10d
-	jle	0xe410
+	jle	0xde70
 	cmpl	$1, %r10d
 	leaq	-56(%rbp), %rcx
 	leaq	-140(%rbp), %r8
-	jne	0xe430
+	jne	0xde90
 	xorl	%esi, %esi
-	movsd	21038(%rip), %xmm1
-	jmp	0xe484
+	movsd	22078(%rip), %xmm1
+	jmp	0xdee4
 	nopw	(%rax,%rax)
 	xorl	%r10d, %r10d
 	leaq	16(%rbp), %rdx
 	leaq	-56(%rbp), %rcx
 	leaq	-140(%rbp), %r8
-	jmp	0xe4a8
+	jmp	0xdf08
 	nopw	(%rax,%rax)
 	movl	%r10d, %edx
 	andl	$-2, %edx
 	leal	1(%r10), %r9d
 	leal	(%r10,%r10), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%esi, %esi
-	movsd	20963(%rip), %xmm1
+	movsd	22003(%rip), %xmm1
 	nopl	(%rax)
 	movslq	%ebx, %rbx
 	movsd	(%r12,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r12,%rbx,8)
 	leal	(%r9,%rbx), %eax
 	cltq
 	movsd	(%r12,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r12,%rax,8)
 	addq	$2, %rsi
 	addl	%edi, %ebx
 	cmpq	%rsi, %rdx
-	jne	0xe450
+	jne	0xdeb0
 	testb	$1, %r10b
-	je	0xe4a4
+	je	0xdf04
 	movl	%r10d, %eax
 	imull	%esi, %eax
 	addl	%esi, %eax
 	cltq
 	movsd	(%r12,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
 	movsd	%xmm0, (%r12,%rax,8)
@@ -10734,26 +10804,25 @@
 	pushq	%rax
 	leaq	-296(%rbp), %rax
 	pushq	%rax
 	pushq	-280(%rbp)
 	leaq	-300(%rbp), %rax
 	pushq	%rax
 	pushq	%r12
-	callq	0x1350e ## symbol stub for: _dgemm
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	$0, -44(%rbp)
 	movl	16(%rbp), %eax
 	testl	%eax, %eax
 	movq	-208(%rbp), %r12
-	movapd	20806(%rip), %xmm1
+	movapd	21830(%rip), %xmm1
 	movq	-264(%rbp), %r13
-	jle	0xe5bb
+	jle	0xe01a
 	xorl	%ecx, %ecx
 	nopw	%cs:(%rax,%rax)
-	nop
 	movslq	%ecx, %rax
 	leaq	(%r12,%rax,8), %rdx
 	movl	-144(%rbp), %ecx
 	imull	-104(%rbp), %ecx
 	addl	%eax, %ecx
 	movslq	%ecx, %rcx
 	movq	-176(%rbp), %rsi
@@ -10761,263 +10830,259 @@
 	movsd	(%r13,%rax,8), %xmm0
 	xorpd	%xmm1, %xmm0
 	movlpd	%xmm0, -72(%rbp)
 	movq	%r15, %rdi
 	leaq	-72(%rbp), %rsi
 	movq	%r14, %rcx
 	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	movapd	20709(%rip), %xmm1
+	callq	0x13376 ## symbol stub for: _daxpy
+	movapd	21733(%rip), %xmm1
 	movl	-44(%rbp), %ecx
-	addl	$1, %ecx
+	incl	%ecx
 	movl	%ecx, -44(%rbp)
 	movl	16(%rbp), %eax
 	cmpl	%eax, %ecx
-	jl	0xe560
+	jl	0xdfc0
 	movabsq	$-4616189618054758400, %rcx
 	movq	%rcx, -72(%rbp)
 	movl	$0, -44(%rbp)
 	cmpl	$0, -56(%rbp)
 	leaq	-72(%rbp), %r13
 	movl	48(%rbp), %r12d
 	movq	-104(%rbp), %rbx
 	movq	-176(%rbp), %r15
-	jle	0xe640
+	jle	0xe0a0
 	xorl	%ecx, %ecx
-	nopl	(%rax,%rax)
+	nopw	(%rax,%rax)
 	imull	%ecx, %eax
 	movl	-144(%rbp), %ecx
 	imull	%ebx, %ecx
 	addl	%eax, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r15,%rax,8), %r8
 	leaq	16(%rbp), %rdi
 	movq	%r13, %rsi
 	movq	-168(%rbp), %rdx
 	leaq	-52(%rbp), %rcx
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movl	-44(%rbp), %ecx
-	addl	$1, %ecx
+	incl	%ecx
 	movl	%ecx, -44(%rbp)
 	cmpl	-56(%rbp), %ecx
-	jge	0xe640
+	jge	0xe0a0
 	movl	16(%rbp), %eax
-	jmp	0xe5f0
+	jmp	0xe050
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	leaq	-144(%rbp), %rdi
 	movq	-200(%rbp), %rcx
 	movq	%rcx, %rsi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movsd	-128(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -128(%rbp)
 	cmpl	$4, %r12d
-	jl	0xdf00
-	leaq	22063(%rip), %rdi ## literal pool for: "\t\t\t cv: %d \tend; err_mean = %f.\n"
+	jl	0xd960
+	leaq	23135(%rip), %rdi ## literal pool for: "\t\t\t cv: %d \tend; err_mean = %f.\n"
 	movl	%ebx, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	jmp	0xdf00
+	callq	0x133c4 ## symbol stub for: _printf
+	jmp	0xd960
 	nopl	(%rax,%rax)
 	movsd	-128(%rbp), %xmm0
 	movsd	-448(%rbp), %xmm1
 	movsd	%xmm1, -216(%rbp)
 	movq	-240(%rbp), %rdx
 	movq	-192(%rbp), %rcx
 	movq	-264(%rbp), %r14
-	jmp	0xe6c4
+	jmp	0xe124
 	nopl	(%rax)
 	xorpd	%xmm0, %xmm0
 	movl	-148(%rbp), %eax
 	xorps	%xmm1, %xmm1
 	cvtsi2sd	%eax, %xmm1
 	divsd	%xmm1, %xmm0
 	movsd	%xmm0, -128(%rbp)
 	movsd	%xmm0, (%rdx,%rcx,8)
 	testl	%eax, %eax
-	jle	0xe6f0
+	jle	0xe150
 	cmpl	$4, %eax
-	jae	0xe700
+	jae	0xe160
 	xorl	%ecx, %ecx
-	jmp	0xe7c0
+	jmp	0xe220
 	nop
 	movq	%r15, %rbx
 	movq	%r12, %r13
 	xorl	%eax, %eax
-	jmp	0xe7ec
+	jmp	0xe24b
 	nopl	(%rax)
 	movl	%eax, %ecx
 	andl	$-4, %ecx
 	leaq	-4(%rcx), %rsi
 	movq	%rsi, %rdx
 	shrq	$2, %rdx
-	addq	$1, %rdx
+	incq	%rdx
 	testq	%rsi, %rsi
-	je	0xe8a9
+	je	0xe307
 	movq	%rdx, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
 	xorl	%esi, %esi
-	nopl	(%rax)
+	nopw	%cs:(%rax,%rax)
 	movupd	(%r15,%rsi,8), %xmm0
 	movupd	16(%r15,%rsi,8), %xmm1
 	movupd	32(%r15,%rsi,8), %xmm2
 	movupd	48(%r15,%rsi,8), %xmm3
 	mulpd	%xmm0, %xmm0
 	mulpd	%xmm1, %xmm1
 	movupd	%xmm0, (%r15,%rsi,8)
 	movupd	%xmm1, 16(%r15,%rsi,8)
 	mulpd	%xmm2, %xmm2
 	mulpd	%xmm3, %xmm3
 	movupd	%xmm2, 32(%r15,%rsi,8)
 	movupd	%xmm3, 48(%r15,%rsi,8)
 	addq	$8, %rsi
-	addq	$2, %rdi
-	jne	0xe730
+	addq	$-2, %rdi
+	jne	0xe190
 	testb	$1, %dl
-	je	0xe7a7
+	je	0xe207
 	movupd	(%r15,%rsi,8), %xmm0
 	movupd	16(%r15,%rsi,8), %xmm1
 	mulpd	%xmm0, %xmm0
 	mulpd	%xmm1, %xmm1
 	movupd	%xmm0, (%r15,%rsi,8)
 	movupd	%xmm1, 16(%r15,%rsi,8)
 	cmpq	%rax, %rcx
-	jne	0xe7c0
+	jne	0xe220
 	movq	%r15, %rbx
 	movq	%r12, %r13
-	jmp	0xe7ec
+	jmp	0xe24b
 	nopw	%cs:(%rax,%rax)
-	nop
 	movq	%r12, %r13
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movsd	(%r15,%rcx,8), %xmm0
 	mulsd	%xmm0, %xmm0
 	movsd	%xmm0, (%r15,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %rax
-	jne	0xe7d0
+	jne	0xe230
 	movq	%r15, %rbx
 	movl	%eax, -44(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	leaq	-148(%rbp), %r15
 	movq	%r15, %rdi
 	leaq	-72(%rbp), %rsi
 	leaq	-128(%rbp), %rdx
 	leaq	-120(%rbp), %rcx
 	movq	%rbx, %r12
 	movq	%rbx, %r8
 	leaq	-52(%rbp), %rbx
 	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r15, %rdi
 	movq	%r12, %r15
 	movq	%r12, %rsi
 	movq	%rbx, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	movapd	%xmm0, %xmm1
 	movl	-148(%rbp), %eax
-	addl	$-1, %eax
+	decl	%eax
 	movl	-116(%rbp), %edx
 	imull	%edx, %eax
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
 	sqrtsd	%xmm0, %xmm0
 	divsd	%xmm0, %xmm1
 	movq	-312(%rbp), %rax
 	movq	-192(%rbp), %rcx
 	movsd	%xmm1, (%rax,%rcx,8)
 	movq	%r13, %r12
 	movl	%edx, %r13d
 	cmpl	$3, %r12d
-	jl	0xdec0
+	jl	0xd920
 	movsd	-128(%rbp), %xmm0
-	leaq	21574(%rip), %rdi ## literal pool for: "\t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n"
+	leaq	22648(%rip), %rdi ## literal pool for: "\t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n"
 	movq	-192(%rbp), %rsi
 	movl	%r13d, %edx
 	movsd	-80(%rbp), %xmm2
 	movb	$3, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	-192(%rbp), %rcx
-	jmp	0xdec0
+	jmp	0xd920
 	xorl	%esi, %esi
 	testb	$1, %dl
-	jne	0xe785
-	jmp	0xe7a7
+	jne	0xe1e5
+	jmp	0xe207
 	movq	96(%rbp), %rbx
 	movl	$8, %esi
 	movq	-384(%rbp), %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	xorps	%xmm0, %xmm0
 	cvtsi2sdl	-148(%rbp), %xmm0
 	movq	%rax, %r14
-	movsd	19940(%rip), %xmm1
+	movsd	20966(%rip), %xmm1
 	subsd	%xmm0, %xmm1
 	movsd	%xmm1, -416(%rbp)
 	leaq	32(%rbp), %r13
 	leaq	-416(%rbp), %rsi
 	leaq	-120(%rbp), %rdx
 	leaq	-52(%rbp), %r15
 	movq	%r13, %rdi
 	movq	%rax, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -72(%rbp)
 	leaq	-72(%rbp), %rsi
 	leaq	-48(%rbp), %r9
 	movq	%r13, %rdi
 	movq	-240(%rbp), %rdx
 	movq	%r15, %rcx
 	movq	%r14, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r13, %rdi
 	movq	-240(%rbp), %r13
 	movq	%r14, %rsi
 	movq	%r15, %rdx
-	callq	0x13538 ## symbol stub for: _idamax
+	callq	0x133b2 ## symbol stub for: _idamax
 	leal	-1(%rax), %r15d
 	movslq	%r15d, %rcx
 	movsd	(%r13,%rcx,8), %xmm0
 	movq	-312(%rbp), %rdx
 	addsd	(%rdx,%rcx,8), %xmm0
 	movsd	%xmm0, -416(%rbp)
 	movq	%r12, %r8
 	testl	%ecx, %ecx
-	je	0xea3a
+	je	0xe49d
 	addl	$-2, %eax
 	testl	%eax, %eax
-	jle	0xea51
+	jle	0xe4b4
 	movl	%eax, %ecx
 	movsd	(%r13,%rcx,8), %xmm1
 	subsd	%xmm0, %xmm1
-	andpd	19714(%rip), %xmm1
+	andpd	20740(%rip), %xmm1
 	testb	$1, %cl
 	movq	-112(%rbp), %r12
 	movq	104(%rbp), %rdi
 	movq	80(%rbp), %rsi
-	je	0xe9d6
+	je	0xe433
 	movsd	(%r13,%rcx,8), %xmm2
 	subsd	%xmm0, %xmm2
-	andpd	19678(%rip), %xmm2
+	andpd	20704(%rip), %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmoval	%r15d, %r15d
 	minsd	%xmm1, %xmm2
-	addq	$-1, %rcx
+	decq	%rcx
 	movapd	%xmm2, %xmm1
 	movl	72(%rbp), %edx
 	cmpl	$1, %eax
-	je	0xea36
-	movapd	19642(%rip), %xmm2
+	je	0xe499
+	movapd	20669(%rip), %xmm2
 	nopw	%cs:(%rax,%rax)
 	movsd	(%r13,%rcx,8), %xmm3
 	subsd	%xmm0, %xmm3
 	andpd	%xmm2, %xmm3
 	ucomisd	%xmm3, %xmm1
 	minsd	%xmm1, %xmm3
 	movsd	-8(%r13,%rcx,8), %xmm1
@@ -11025,25 +11090,26 @@
 	cmoval	%eax, %r15d
 	subsd	%xmm0, %xmm1
 	andpd	%xmm2, %xmm1
 	ucomisd	%xmm1, %xmm3
 	cmoval	%ecx, %r15d
 	minsd	%xmm3, %xmm1
 	leaq	-2(%rcx), %rax
-	cmpq	$2, %rcx
+	decq	%rcx
+	cmpq	$1, %rcx
 	movq	%rax, %rcx
-	jg	0xe9f0
+	ja	0xe450
 	xorl	%eax, %eax
-	jmp	0xea60
+	jmp	0xe4c3
 	movl	$1, %r15d
 	movq	-112(%rbp), %r12
 	movl	72(%rbp), %edx
 	movq	104(%rbp), %rdi
 	movq	80(%rbp), %rsi
-	jmp	0xea63
+	jmp	0xe4c6
 	movq	-112(%rbp), %r12
 	movl	72(%rbp), %edx
 	movq	104(%rbp), %rdi
 	movq	80(%rbp), %rsi
 	movl	%eax, -44(%rbp)
 	leal	-1(%r15), %eax
 	cltq
@@ -11051,441 +11117,498 @@
 	movslq	%edx, %rcx
 	movsd	%xmm0, (%rsi,%rcx,8)
 	movsd	%xmm0, (%rbx,%rcx,8)
 	movq	-312(%rbp), %rdx
 	movsd	(%rdx,%rax,8), %xmm0
 	movsd	%xmm0, (%rdi,%rcx,8)
 	cmpl	$2, %r8d
-	jl	0xeaa5
-	leaq	21115(%rip), %rdi ## literal pool for: "\t\tExit Function: cv_support. optimal lambda index: %d.\n\n"
+	jl	0xe508
+	leaq	22184(%rip), %rdi ## literal pool for: "\t\tExit Function: cv_support. optimal lambda index: %d.\n\n"
 	movl	%r15d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-224(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-344(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-248(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-368(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-264(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-232(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-160(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-280(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-208(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-328(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-272(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-400(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-392(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-352(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-336(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movl	%r15d, %eax
 	addq	$408, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	xorl	%esi, %esi
-	testb	$1, %dl
-	jne	0xdc77
-	jmp	0xdc9e
-	nopw	%cs:(%rax,%rax)
+	xorl	%edx, %edx
+	testb	$1, %sil
+	jne	0xd6d8
+	jmp	0xd6ff
+	nopw	(%rax,%rax)
 _mainSML_adaEN:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
-	subq	$248, %rsp
+	subq	$280, %rsp
 	movq	%r9, %r15
 	movq	%r8, %r13
 	movl	%edx, %r12d
-	movq	%rsi, -136(%rbp)
-	movq	%rdi, -96(%rbp)
+	movq	%rsi, -160(%rbp)
+	movq	%rdi, -64(%rbp)
 	movq	24(%rbp), %rbx
 	movl	%edx, -44(%rbp)
-	movl	$1, -68(%rbp)
-	movl	$1, -64(%rbp)
-	movl	$0, -128(%rbp)
-	movq	%rcx, -104(%rbp)
+	movl	$1, -88(%rbp)
+	movl	$1, -84(%rbp)
+	movl	$0, -108(%rbp)
+	movq	%rcx, -128(%rbp)
 	movl	%ecx, %eax
 	imull	%edx, %eax
-	movl	%eax, -80(%rbp)
-	movl	%eax, -124(%rbp)
+	movl	%eax, -96(%rbp)
+	movl	%eax, -132(%rbp)
 	movl	%edx, %eax
 	imull	%edx, %eax
-	movl	%eax, -60(%rbp)
+	movl	%eax, -68(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	leaq	-60(%rbp), %rdi
-	leaq	-68(%rbp), %rdx
-	leaq	-64(%rbp), %r8
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r14
+	leaq	-68(%rbp), %rdi
+	leaq	-88(%rbp), %rdx
+	leaq	-84(%rbp), %r8
 	movq	%r15, %rsi
-	movq	%rax, -208(%rbp)
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, 8(%rbx)
 	testl	%r12d, %r12d
-	jle	0xed4e
+	jle	0xe7c1
 	movq	%rbx, %r10
 	movl	%r12d, %r8d
 	movl	%r8d, %r9d
 	andl	$-2, %r9d
 	leal	(%r12,%r12), %edx
 	xorpd	%xmm0, %xmm0
-	xorl	%esi, %esi
-	movsd	18858(%rip), %xmm1
+	xorl	%eax, %eax
+	movsd	19899(%rip), %xmm1
 	xorpd	%xmm2, %xmm2
-	jmp	0xec9d
-	nopl	(%rax)
-	addq	$1, %rsi
-	cmpq	%r8, %rsi
-	je	0xed4e
+	jmp	0xe6fc
+	nopl	(%rax,%rax)
+	incq	%rax
+	cmpq	%r8, %rax
+	je	0xe7c1
 	cmpl	$1, %r12d
-	jne	0xece0
-	xorl	%eax, %eax
+	jne	0xe710
+	xorl	%ebx, %ebx
 	testb	$1, %r8b
-	je	0xec90
-	cmpq	%rax, %rsi
-	je	0xec90
-	imull	%r12d, %eax
-	addl	%esi, %eax
-	cltq
-	movsd	(%r15,%rax,8), %xmm3
+	je	0xe6f0
+	jmp	0xe78e
+	nop
+	movl	%eax, %esi
+	xorl	%edi, %edi
+	jmp	0xe72a
+	nopw	%cs:(%rax,%rax)
+	addl	%edx, %esi
+	incq	%rdi
+	cmpq	%r9, %rdi
+	je	0xe780
+	movq	%rdi, %rbx
+	cmpq	%rdi, %rax
+	je	0xe74d
+	movslq	%esi, %rdi
+	movsd	(%r15,%rdi,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0xecc6
-	jnp	0xec90
+	jne	0xe743
+	jnp	0xe74d
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r10)
-	jmp	0xec90
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	movl	%esi, %edi
-	xorl	%ecx, %ecx
-	jmp	0xed05
-	nopw	%cs:(%rax,%rax)
-	movq	%rcx, %rax
-	addq	$2, %rax
-	addl	%edx, %edi
-	addq	$1, %rbx
-	movq	%rbx, %rcx
-	cmpq	%rax, %r9
-	je	0xeca5
-	cmpq	%rcx, %rsi
-	je	0xed25
-	movslq	%edi, %rax
-	movsd	(%r15,%rax,8), %xmm3
+	leaq	1(%rbx), %rdi
+	cmpq	%rdi, %rax
+	je	0xe720
+	leal	(%r12,%rsi), %ecx
+	movslq	%ecx, %rcx
+	movsd	(%r15,%rcx,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0xed1b
-	jnp	0xed25
+	jne	0xe76b
+	jnp	0xe720
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r10)
-	leaq	1(%rcx), %rbx
-	cmpq	%rbx, %rsi
-	je	0xecf0
-	leal	(%r12,%rdi), %eax
-	cltq
-	movsd	(%r15,%rax,8), %xmm3
+	jmp	0xe720
+	nopw	(%rax,%rax)
+	addq	$2, %rbx
+	testb	$1, %r8b
+	je	0xe6f0
+	cmpq	%rbx, %rax
+	je	0xe6f0
+	imull	%r12d, %ebx
+	addl	%eax, %ebx
+	movslq	%ebx, %rcx
+	movsd	(%r15,%rcx,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0xed42
-	jnp	0xecf0
+	jne	0xe7b2
+	jnp	0xe6f0
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r10)
-	jmp	0xecf0
+	jmp	0xe6f0
 	movabsq	$4607182418800017408, %rax
-	movq	%rax, -248(%rbp)
+	movq	%rax, -264(%rbp)
 	leaq	-44(%rbp), %rdi
-	leaq	-248(%rbp), %rbx
-	leaq	-128(%rbp), %r12
-	leaq	-68(%rbp), %r14
+	leaq	-264(%rbp), %rbx
+	leaq	-108(%rbp), %rdx
+	leaq	-88(%rbp), %r12
 	movq	%rbx, %rsi
-	movq	%r12, %rdx
 	movq	16(%rbp), %rcx
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	$0, -248(%rbp)
-	leaq	-60(%rbp), %rdi
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	$0, -264(%rbp)
+	leaq	-68(%rbp), %rdi
 	movq	%rbx, %rsi
-	movq	%r12, %rdx
+	leaq	-108(%rbp), %rdx
 	movq	%r15, %rcx
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	cmpl	$0, -80(%rbp)
-	jle	0xedd2
-	movl	-80(%rbp), %ecx
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	cmpl	$0, -96(%rbp)
+	jle	0xe98c
+	movl	-96(%rbp), %ecx
 	movl	%ecx, %eax
-	cmpl	$1, %ecx
-	jne	0xf092
+	cmpl	$4, %ecx
+	jb	0xe846
+	leaq	(,%rax,4), %rcx
+	addq	%r13, %rcx
+	movq	-64(%rbp), %rdx
+	cmpq	%rdx, %rcx
+	jbe	0xe8b8
+	leaq	(%rdx,%rax,8), %rcx
+	cmpq	%r13, %rcx
+	jbe	0xe8b8
 	xorl	%ecx, %ecx
+	movq	%rcx, %rdx
+	notq	%rdx
 	testb	$1, %al
-	je	0xedd2
+	je	0xe86a
 	cmpl	$1, (%r13,%rcx,4)
-	jne	0xedd2
-	movq	-96(%rbp), %rax
-	movq	$0, (%rax,%rcx,8)
+	jne	0xe866
+	movq	-64(%rbp), %rsi
+	movq	$0, (%rsi,%rcx,8)
+	orq	$1, %rcx
+	addq	%rax, %rdx
+	jne	0xe88d
+	jmp	0xe98c
+	nopw	%cs:(%rax,%rax)
+	addq	$2, %rcx
+	cmpq	%rcx, %rax
+	je	0xe98c
+	cmpl	$1, (%r13,%rcx,4)
+	jne	0xe8a1
+	movq	-64(%rbp), %rdx
+	movq	$0, (%rdx,%rcx,8)
+	cmpl	$1, 4(%r13,%rcx,4)
+	jne	0xe880
+	movq	-64(%rbp), %rdx
+	movq	$0, 8(%rdx,%rcx,8)
+	jmp	0xe880
+	movl	%eax, %ecx
+	andl	$-4, %ecx
+	xorl	%edx, %edx
+	movdqa	19625(%rip), %xmm0
+	movdqa	19633(%rip), %xmm1
+	jmp	0xe8ed
+	nopw	%cs:(%rax,%rax)
+	addq	$4, %rdx
+	cmpq	%rdx, %rcx
+	je	0xe983
+	movq	(%r13,%rdx,4), %xmm3
+	movq	8(%r13,%rdx,4), %xmm2
+	movdqa	%xmm3, %xmm4
+	pcmpeqd	%xmm0, %xmm4
+	movd	%xmm4, %esi
+	testb	$1, %sil
+	je	0xe919
+	movq	-64(%rbp), %rsi
+	movq	$0, (%rsi,%rdx,8)
+	pshufd	$212, %xmm3, %xmm3
+	pcmpeqd	%xmm1, %xmm3
+	pextrw	$4, %xmm3, %esi
+	testb	$1, %sil
+	je	0xe93a
+	movq	-64(%rbp), %rsi
+	movq	$0, 8(%rsi,%rdx,8)
+	movdqa	%xmm2, %xmm3
+	pcmpeqd	%xmm0, %xmm3
+	movd	%xmm3, %esi
+	testb	$1, %sil
+	je	0xe959
+	movq	-64(%rbp), %rsi
+	movq	$0, 16(%rsi,%rdx,8)
+	pshufd	$212, %xmm2, %xmm2
+	pcmpeqd	%xmm1, %xmm2
+	pextrw	$4, %xmm2, %esi
+	testb	$1, %sil
+	je	0xe8e0
+	movq	-64(%rbp), %rsi
+	movq	$0, 24(%rsi,%rdx,8)
+	jmp	0xe8e0
+	cmpq	%rax, %rcx
+	jne	0xe848
 	movl	$20, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movaps	18712(%rip), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movaps	19438(%rip), %xmm0
 	movups	%xmm0, (%rax)
-	movaps	18718(%rip), %xmm0
+	movaps	19444(%rip), %xmm0
 	movups	%xmm0, 16(%rax)
-	movaps	18723(%rip), %xmm0
+	movaps	19449(%rip), %xmm0
 	movups	%xmm0, 32(%rax)
-	movaps	18728(%rip), %xmm0
+	movaps	19454(%rip), %xmm0
 	movups	%xmm0, 48(%rax)
-	movaps	18733(%rip), %xmm0
+	movaps	19459(%rip), %xmm0
 	movups	%xmm0, 64(%rax)
-	movaps	18738(%rip), %xmm0
+	movaps	19464(%rip), %xmm0
 	movups	%xmm0, 80(%rax)
-	movaps	18743(%rip), %xmm0
+	movaps	19469(%rip), %xmm0
 	movups	%xmm0, 96(%rax)
-	movaps	18748(%rip), %xmm0
+	movaps	19474(%rip), %xmm0
 	movups	%xmm0, 112(%rax)
-	movaps	18753(%rip), %xmm0
+	movaps	19479(%rip), %xmm0
 	movups	%xmm0, 128(%rax)
-	movaps	18755(%rip), %xmm0
-	movq	%rax, -200(%rbp)
+	movaps	19481(%rip), %xmm0
+	movq	%rax, -232(%rbp)
 	movups	%xmm0, 144(%rax)
 	movl	$31, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r12
-	movsd	18523(%rip), %xmm1
+	movsd	19201(%rip), %xmm1
 	movl	$3, %ebx
-	nopw	(%rax,%rax)
-	movsd	18512(%rip), %xmm0
+	nopw	%cs:(%rax,%rax)
+	movsd	19184(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, -24(%r12,%rbx,8)
-	movsd	18495(%rip), %xmm0
+	movsd	19167(%rip), %xmm0
 	movsd	-56(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	18465(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
+	movsd	19137(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, -16(%r12,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	18448(%rip), %xmm1
-	movsd	18432(%rip), %xmm0
+	addsd	19120(%rip), %xmm1
+	movsd	19104(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, -8(%r12,%rbx,8)
 	cmpq	$31, %rbx
-	je	0xef2e
+	je	0xeaee
 	movsd	-56(%rbp), %xmm1
-	movsd	18404(%rip), %xmm0
+	movsd	19076(%rip), %xmm0
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	18379(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
+	movsd	19051(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, (%r12,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	18363(%rip), %xmm1
+	addsd	19035(%rip), %xmm1
 	addq	$4, %rbx
-	jmp	0xee80
+	jmp	0xea40
 	movl	$19, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	movl	$19, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -184(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -152(%rbp)
 	movl	$19, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -176(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -224(%rbp)
 	movl	$19, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -168(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -216(%rbp)
 	movl	$19, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -160(%rbp)
-	movaps	18433(%rip), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -208(%rbp)
+	movaps	19153(%rip), %xmm0
 	movups	%xmm0, (%rbx)
-	movaps	18439(%rip), %xmm0
+	movaps	19159(%rip), %xmm0
 	movups	%xmm0, 16(%rbx)
-	movaps	18444(%rip), %xmm0
+	movaps	19164(%rip), %xmm0
 	movups	%xmm0, 32(%rbx)
-	movaps	18449(%rip), %xmm0
+	movaps	19169(%rip), %xmm0
 	movups	%xmm0, 48(%rbx)
-	movaps	18454(%rip), %xmm0
+	movaps	19174(%rip), %xmm0
 	movups	%xmm0, 64(%rbx)
-	movaps	18459(%rip), %xmm0
+	movaps	19179(%rip), %xmm0
 	movups	%xmm0, 80(%rbx)
-	movaps	18464(%rip), %xmm0
+	movaps	19184(%rip), %xmm0
 	movups	%xmm0, 96(%rbx)
-	movaps	18469(%rip), %xmm0
+	movaps	19189(%rip), %xmm0
 	movups	%xmm0, 112(%rbx)
-	movapd	18473(%rip), %xmm0
-	movupd	%xmm0, 128(%rbx)
-	movabsq	$4587366580439587216, %rax
-	movq	%rbx, -192(%rbp)
+	movaps	19194(%rip), %xmm0
+	movups	%xmm0, 128(%rbx)
+	movabsq	$4587366580439587212, %rax
+	movq	%rbx, -200(%rbp)
 	movq	%rax, 144(%rbx)
-	movslq	-60(%rbp), %rbx
+	movslq	-68(%rbp), %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -56(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
-	movq	$0, -272(%rbp)
-	leaq	-60(%rbp), %rdi
-	leaq	-272(%rbp), %rsi
-	leaq	-128(%rbp), %rdx
-	leaq	-64(%rbp), %r8
+	movq	$0, -296(%rbp)
+	leaq	-68(%rbp), %rdi
+	leaq	-296(%rbp), %rsi
+	leaq	-108(%rbp), %rdx
+	leaq	-84(%rbp), %r8
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r10d
 	testl	%r10d, %r10d
 	movabsq	$4607182418800017408, %rdi
-	jle	0xf18f
+	jle	0xed0e
 	leaq	-1(%r10), %rdx
 	movl	%r10d, %ecx
 	andl	$3, %ecx
 	xorl	%esi, %esi
 	cmpq	$3, %rdx
-	jae	0xf0d8
+	jae	0xec50
 	xorl	%edx, %edx
-	jmp	0xf165
-	movl	%eax, %edx
-	andl	$-2, %edx
-	xorl	%ecx, %ecx
-	jmp	0xf0ad
-	nopl	(%rax,%rax)
-	addq	$2, %rcx
-	cmpq	%rcx, %rdx
-	je	0xedba
-	cmpl	$1, (%r13,%rcx,4)
-	jne	0xf0c1
-	movq	-96(%rbp), %rsi
-	movq	$0, (%rsi,%rcx,8)
-	cmpl	$1, 4(%r13,%rcx,4)
-	jne	0xf0a0
-	movq	-96(%rbp), %rsi
-	movq	$0, 8(%rsi,%rcx,8)
-	jmp	0xf0a0
-	movl	%r10d, %r14d
-	andl	$-4, %r14d
+	jmp	0xece6
+	movl	%r10d, %eax
+	andl	$-4, %eax
+	movq	%rax, -120(%rbp)
 	leal	(%r10,%r10), %eax
 	addl	$2, %eax
-	movq	%rax, -88(%rbp)
+	movq	%rax, -80(%rbp)
 	leal	4(,%r10,4), %r13d
 	leal	1(%r10), %r11d
 	leal	(%r10,%r10,2), %r9d
 	addl	$3, %r9d
 	xorl	%edx, %edx
 	movabsq	$4607182418800017408, %r8
-	nopw	(%rax,%rax)
+	nopw	%cs:(%rax,%rax)
 	movslq	%esi, %rsi
 	movq	%rdi, (%rbx,%rsi,8)
 	leal	(%r11,%rsi), %edi
 	movslq	%edi, %rdi
 	movq	%r8, (%rbx,%rdi,8)
-	movq	-88(%rbp), %rax
+	movq	-80(%rbp), %rax
 	leal	(%rax,%rsi), %edi
 	movslq	%edi, %rdi
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, (%rbx,%rdi,8)
 	leal	(%r9,%rsi), %edi
 	movslq	%edi, %rdi
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, (%rbx,%rdi,8)
 	movabsq	$4607182418800017408, %rdi
 	addq	$4, %rdx
 	addl	%r13d, %esi
-	cmpq	%rdx, %r14
-	jne	0xf110
+	cmpq	%rdx, -120(%rbp)
+	jne	0xec90
 	testq	%rcx, %rcx
-	je	0xf18f
+	je	0xed0e
 	leal	1(%r10), %esi
 	imull	%esi, %edx
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	movslq	%edx, %rdx
 	movq	%rdi, (%rbx,%rdx,8)
 	addl	%esi, %edx
-	addq	$-1, %rcx
-	jne	0xf180
-	movq	%rbx, -120(%rbp)
-	movq	%r12, -152(%rbp)
+	decq	%rcx
+	jne	0xed00
+	movq	%rbx, -80(%rbp)
+	movq	%r12, -256(%rbp)
+	movsd	18487(%rip), %xmm0
 	xorl	%ebx, %ebx
-	leaq	-288(%rbp), %r13
-	leaq	-280(%rbp), %r12
-	nopw	(%rax,%rax)
-	movl	32(%rbp), %eax
-	movq	-192(%rbp), %rcx
-	movsd	(%rcx,%rbx,8), %xmm0
-	movq	-96(%rbp), %rdi
-	movq	-136(%rbp), %rsi
+	leaq	-312(%rbp), %r13
+	leaq	-304(%rbp), %r12
+	nopw	%cs:(%rax,%rax)
+	movl	40(%rbp), %eax
+	movq	%rax, %r11
+	movq	-152(%rbp), %rax
+	movq	-64(%rbp), %rdi
+	movq	-160(%rbp), %rsi
 	movl	$5, %edx
-	movq	-200(%rbp), %rcx
-	movq	-152(%rbp), %r8
+	movq	-232(%rbp), %rcx
+	movq	-256(%rbp), %r8
 	movl	$500, %r9d
-	pushq	-160(%rbp)
-	pushq	-168(%rbp)
+	pushq	-208(%rbp)
+	pushq	-216(%rbp)
 	pushq	%r13
-	pushq	-184(%rbp)
+	pushq	%rax
 	pushq	%rbx
 	pushq	%r12
 	pushq	-56(%rbp)
-	pushq	%rax
+	pushq	%r11
 	pushq	$31
 	pushq	$20
-	pushq	-104(%rbp)
+	pushq	-128(%rbp)
 	pushq	%r10
 	callq	_cv_gene_nets_support_adaEN
 	addq	$96, %rsp
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
-	movq	-176(%rbp), %rax
+	movq	-224(%rbp), %rax
 	movsd	%xmm0, (%rax,%rbx,8)
 	cmpq	$18, %rbx
-	je	0xf236
+	je	0xedcc
+	movq	-200(%rbp), %rax
+	movsd	8(%rax,%rbx,8), %xmm0
 	movl	-44(%rbp), %r10d
-	addq	$1, %rbx
-	jmp	0xf1b0
-	movq	-184(%rbp), %rbx
+	incq	%rbx
+	jmp	0xed40
+	movq	-152(%rbp), %rbx
 	movsd	(%rbx), %xmm0
 	movsd	8(%rbx), %xmm1
 	xorl	%eax, %eax
 	ucomisd	%xmm1, %xmm0
 	seta	%al
 	minsd	%xmm0, %xmm1
 	movsd	16(%rbx), %xmm0
@@ -11568,48 +11691,52 @@
 	movl	$17, %edx
 	cmovbel	%ecx, %edx
 	minsd	%xmm0, %xmm1
 	ucomisd	144(%rbx), %xmm1
 	movl	$18, %eax
 	cmovbel	%edx, %eax
 	testl	%eax, %eax
-	jle	0xf40f
-	movq	-168(%rbp), %rcx
+	jle	0xefb0
+	movq	-216(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	movq	-160(%rbp), %rcx
+	movq	-208(%rbp), %rcx
 	addsd	(%rcx,%rax,8), %xmm0
 	leal	-1(%rax), %edx
 	movl	%eax, %esi
 	andl	$3, %esi
-	movl	32(%rbp), %edi
-	je	0xf418
+	je	0xefbc
 	xorpd	%xmm1, %xmm1
 	movl	%eax, %ecx
-	movq	-120(%rbp), %r12
-	nopl	(%rax)
-	addl	$-1, %eax
+	movl	40(%rbp), %edi
+	movq	%rdi, %r8
+	movq	-80(%rbp), %r13
+	nopw	%cs:(%rax,%rax)
+	decl	%eax
 	movsd	(%rbx,%rax,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%eax, %ecx
-	addl	$-1, %esi
-	jne	0xf3f0
+	decl	%esi
+	jne	0xef90
 	cmpl	$3, %edx
-	jae	0xf423
-	jmp	0xf484
-	movl	32(%rbp), %edi
-	movq	-120(%rbp), %r12
-	jmp	0xf487
+	jae	0xefcd
+	jmp	0xf034
+	movl	40(%rbp), %edi
+	movq	%rdi, %r8
+	movq	-80(%rbp), %r13
+	jmp	0xf037
 	movl	%eax, %ecx
-	movq	-120(%rbp), %r12
+	movl	40(%rbp), %edi
+	movq	%rdi, %r8
+	movq	-80(%rbp), %r13
 	cmpl	$3, %edx
-	jb	0xf484
+	jb	0xf034
 	addl	$4, %eax
 	xorpd	%xmm1, %xmm1
-	nopw	(%rax,%rax)
+	nopw	%cs:(%rax,%rax)
 	leal	-5(%rax), %edx
 	movsd	(%rbx,%rdx,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%edx, %ecx
 	leal	-6(%rax), %edx
 	movsd	(%rbx,%rdx,8), %xmm2
@@ -11624,1075 +11751,1070 @@
 	leal	-8(%rax), %edx
 	movsd	(%rbx,%rdx,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%edx, %ecx
 	addl	$-4, %eax
 	cmpl	$4, %eax
-	jg	0xf430
+	jg	0xefe0
 	movslq	%ecx, %rax
-	movq	-176(%rbp), %rcx
-	cvttsd2si	(%rcx,%rax,8), %ecx
-	movq	%rcx, -88(%rbp)
-	movq	-192(%rbp), %rcx
+	movq	-224(%rbp), %rcx
+	cvttsd2si	(%rcx,%rax,8), %ebx
+	movq	-200(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	movsd	%xmm0, -112(%rbp)
-	testl	%edi, %edi
-	jne	0xf4db
-	leaq	18812(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV, alpha: %f.\n"
+	movsd	%xmm0, -104(%rbp)
+	testl	%r8d, %r8d
+	js	0xf086
+	leaq	19889(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV, alpha: %f.\n"
 	movl	$5, %esi
-	movsd	-112(%rbp), %xmm0
+	movsd	-104(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	leaq	18825(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
-	movsd	-112(%rbp), %xmm0
-	movq	-88(%rbp), %rsi
+	callq	0x133c4 ## symbol stub for: _printf
+	leaq	19902(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
+	movsd	-104(%rbp), %xmm0
+	movl	%ebx, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
+	movq	%rbx, -248(%rbp)
 	movslq	-44(%rbp), %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r13
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -176(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -216(%rbp)
-	movslq	-80(%rbp), %rbx
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -168(%rbp)
+	movslq	-96(%rbp), %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r14
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r12
+	movq	%rax, -192(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
-	leaq	-124(%rbp), %rdi
-	leaq	-68(%rbp), %rdx
-	leaq	-64(%rbp), %r8
-	movq	-136(%rbp), %rsi
+	leaq	-132(%rbp), %rdi
+	leaq	-88(%rbp), %rdx
+	leaq	-84(%rbp), %r8
+	movq	-160(%rbp), %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-124(%rbp), %rdi
-	movq	-96(%rbp), %rsi
-	leaq	-68(%rbp), %rdx
-	movq	%r14, %rcx
-	leaq	-64(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%rax, -144(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-132(%rbp), %rdi
+	movq	-64(%rbp), %rsi
+	leaq	-88(%rbp), %rdx
+	movq	%r12, %rcx
+	leaq	-84(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r8d
-	movq	%r14, %rdi
+	movq	%r12, %rdi
 	movq	%rbx, %rsi
-	movq	%r13, -256(%rbp)
-	movq	%r13, %rdx
-	movq	-216(%rbp), %rcx
-	movq	-104(%rbp), %r13
-	movl	%r13d, %r9d
+	movq	-176(%rbp), %rdx
+	movq	-168(%rbp), %rcx
+	movq	-128(%rbp), %r12
+	movl	%r12d, %r9d
 	callq	_centerYX
-	movslq	-60(%rbp), %rdi
+	movslq	-68(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movsd	-280(%rbp), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movsd	-304(%rbp), %xmm0
 	movl	-44(%rbp), %ecx
-	movq	%r14, %rdi
-	movq	%rbx, %rsi
-	movq	%rax, -144(%rbp)
+	movq	-192(%rbp), %rbx
+	movq	%rbx, %rdi
+	movq	-144(%rbp), %rsi
+	movq	%rax, -184(%rbp)
 	movq	%rax, %rdx
-	movsd	%xmm0, -80(%rbp)
-	movl	%r13d, %r8d
+	movsd	%xmm0, -96(%rbp)
+	movl	%r12d, %r8d
 	callq	_QlambdaStart
 	movl	-44(%rbp), %ecx
-	movq	%r14, -240(%rbp)
-	movq	%r14, %rdi
-	movq	%rbx, -232(%rbp)
-	movq	%rbx, %rsi
+	movq	%rbx, %rdi
+	movq	-144(%rbp), %rsi
 	movq	-56(%rbp), %rdx
-	movl	%r13d, %r8d
-	movsd	-112(%rbp), %xmm0
+	movl	%r12d, %r8d
+	movsd	-104(%rbp), %xmm0
 	callq	_lambdaMax_adaEN
-	movsd	%xmm0, -224(%rbp)
-	movl	32(%rbp), %r11d
+	movsd	%xmm0, -240(%rbp)
+	movl	40(%rbp), %r11d
 	testl	%r11d, %r11d
-	jne	0xf600
-	leaq	18738(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
-	callq	0x13556 ## symbol stub for: _puts
-	movl	32(%rbp), %r11d
-	movq	-88(%rbp), %r14
-	testl	%r14d, %r14d
-	movq	16(%rbp), %r13
-	jle	0xf773
-	movsd	16407(%rip), %xmm1
-	xorl	%ebx, %ebx
-	jmp	0xf6f6
-	leaq	18272(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
-	movl	%ebx, %esi
-	movl	%r14d, %edx
+	js	0xf1c8
+	leaq	19824(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
+	callq	0x133d0 ## symbol stub for: _puts
+	movl	40(%rbp), %r11d
+	movq	-248(%rbp), %rdx
+	testl	%edx, %edx
+	jle	0xf385
+	movq	%r14, -272(%rbp)
+	leaq	-1(%rdx), %rax
+	movq	%rax, -280(%rbp)
+	movsd	17071(%rip), %xmm1
+	movsd	17231(%rip), %xmm0
+	xorl	%r14d, %r14d
+	nopl	(%rax)
+	testl	%r11d, %r11d
+	movsd	%xmm0, -120(%rbp)
+	jle	0xf2b0
+	leaq	18946(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
+	movl	%r14d, %esi
 	movb	$1, %al
-	movq	%r11, %r13
-	movsd	%xmm1, -264(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	movq	%r11, %r12
+	movsd	%xmm1, -288(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
 	movq	-56(%rbp), %rdi
 	movq	%r15, %rsi
 	movq	16(%rbp), %rdx
-	movq	-96(%rbp), %rcx
-	movq	-136(%rbp), %r8
-	movq	-144(%rbp), %r12
-	movq	%r12, %r9
-	movsd	-88(%rbp), %xmm0
-	movsd	-264(%rbp), %xmm1
-	movsd	-80(%rbp), %xmm2
-	movsd	-224(%rbp), %xmm3
-	movsd	-112(%rbp), %xmm4
-	pushq	-120(%rbp)
-	pushq	%r13
-	movq	-120(%rbp), %r13
-	pushq	-104(%rbp)
+	movq	-64(%rbp), %rcx
+	movq	-160(%rbp), %r8
+	movq	-184(%rbp), %r13
+	movq	%r13, %r9
+	movsd	-120(%rbp), %xmm0
+	movsd	-288(%rbp), %xmm1
+	movsd	-96(%rbp), %xmm2
+	movsd	-240(%rbp), %xmm3
+	movq	-104(%rbp), %xmm4
+	pushq	-80(%rbp)
+	pushq	%r12
+	movq	-128(%rbp), %rbx
+	pushq	%rbx
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	addq	$48, %rsp
-	leaq	18180(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
+	leaq	18858(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-80(%rbp), %xmm0
-	movq	%r12, %rdx
-	movq	%r13, %r12
-	movq	16(%rbp), %r13
-	movq	-104(%rbp), %rax
-	movl	-44(%rbp), %r9d
-	movq	-240(%rbp), %rdi
-	movq	-232(%rbp), %rsi
-	movq	%r15, %rcx
-	movq	%r13, %r8
-	pushq	%r12
-	pushq	%rax
-	callq	_QlambdaMiddleCenter
-	addq	$16, %rsp
-	addq	$1, %rbx
-	movsd	-88(%rbp), %xmm1
-	cmpq	%rbx, %r14
-	movl	32(%rbp), %r11d
-	je	0xf773
-	movq	-200(%rbp), %rax
-	movsd	(%rax,%rbx,8), %xmm0
-	testl	%r11d, %r11d
-	movsd	%xmm0, -88(%rbp)
-	jg	0xf620
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-96(%rbp), %xmm0
+	movq	%r13, %rdx
+	movq	16(%rbp), %r8
+	movq	-80(%rbp), %r13
+	jmp	0xf316
+	nopl	(%rax)
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
 	movq	-56(%rbp), %rdi
 	movq	%r15, %rsi
+	movq	16(%rbp), %r13
 	movq	%r13, %rdx
-	movq	-96(%rbp), %rcx
-	movq	-136(%rbp), %r8
-	movq	-144(%rbp), %r13
-	movq	%r13, %r9
-	movsd	-80(%rbp), %xmm2
-	movsd	-224(%rbp), %xmm3
-	movsd	-112(%rbp), %xmm4
-	pushq	%r12
+	movq	-64(%rbp), %rcx
+	movq	-160(%rbp), %r8
+	movq	-184(%rbp), %r12
+	movq	%r12, %r9
+	movsd	-96(%rbp), %xmm2
+	movsd	-240(%rbp), %xmm3
+	movq	-104(%rbp), %xmm4
+	pushq	-80(%rbp)
 	pushq	%r11
-	pushq	-104(%rbp)
+	pushq	-128(%rbp)
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
-	movsd	-80(%rbp), %xmm0
-	movq	%r13, %rdx
-	movq	16(%rbp), %r13
-	movq	-104(%rbp), %rax
+	movsd	-96(%rbp), %xmm0
+	movq	%r12, %rdx
+	movq	-128(%rbp), %rbx
+	movq	%r13, %r8
+	movq	-80(%rbp), %r13
 	addq	$48, %rsp
-	jmp	0xf6c0
-	movq	%r12, %r13
+	movl	-44(%rbp), %r9d
+	movq	-192(%rbp), %rdi
+	movq	-144(%rbp), %rsi
+	movq	%r15, %rcx
+	pushq	%r13
+	pushq	%rbx
+	callq	_QlambdaMiddleCenter
+	addq	$16, %rsp
+	cmpq	%r14, -280(%rbp)
+	je	0xf366
+	movq	-232(%rbp), %rax
+	movsd	8(%rax,%r14,8), %xmm0
+	incq	%r14
+	movsd	-120(%rbp), %xmm1
+	movl	40(%rbp), %r11d
+	movq	-248(%rbp), %rdx
+	jmp	0xf200
+	movq	24(%rbp), %r10
+	movl	40(%rbp), %r11d
+	movq	32(%rbp), %rax
+	movq	-272(%rbp), %r14
+	movsd	-104(%rbp), %xmm0
+	movsd	-120(%rbp), %xmm1
+	jmp	0xf392
+	movq	24(%rbp), %r10
+	movq	32(%rbp), %rax
+	movsd	-104(%rbp), %xmm0
+	movsd	%xmm0, (%rax)
+	movsd	%xmm1, 8(%rax)
+	testl	%r11d, %r11d
+	js	0xf3b6
+	leaq	19147(%rip), %rdi ## literal pool for: "SEM fit with alpha: %f, lambda: %f\n"
+	movb	$2, %al
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	40(%rbp), %r11d
 	movq	24(%rbp), %r10
 	movq	$0, (%r10)
 	xorpd	%xmm0, %xmm0
 	movupd	%xmm0, 16(%r10)
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
-	jle	0xf859
+	jle	0xf488
 	leaq	16(%r10), %r9
 	movq	%rax, %rdx
 	negq	%rdx
 	xorpd	%xmm2, %xmm2
 	xorl	%esi, %esi
-	movsd	16002(%rip), %xmm3
-	xorpd	%xmm0, %xmm0
+	movsd	16566(%rip), %xmm3
 	xorpd	%xmm1, %xmm1
-	xorpd	%xmm4, %xmm4
+	pxor	%xmm4, %xmm4
+	xorpd	%xmm0, %xmm0
 	xorl	%r8d, %r8d
-	movq	-152(%rbp), %r12
-	movq	-208(%rbp), %r14
-	jmp	0xf7dd
-	nopl	(%rax)
-	addq	$1, %r8
-	addq	$-1, %rsi
+	jmp	0xf40b
+	nopl	(%rax,%rax)
+	incq	%r8
+	decq	%rsi
 	cmpq	%rax, %r8
-	je	0xf853
+	je	0xf482
 	movl	%r8d, %ebx
 	xorl	%edi, %edi
-	jmp	0xf7fb
+	jmp	0xf42a
 	nopw	%cs:(%rax,%rax)
-	nop
-	addq	$-1, %rdi
+	decq	%rdi
 	addl	%eax, %ebx
 	cmpq	%rdi, %rdx
-	je	0xf7d0
+	je	0xf400
 	movslq	%ebx, %rcx
 	movsd	(%r14,%rcx,8), %xmm5
 	ucomisd	%xmm2, %xmm5
-	jne	0xf823
-	jp	0xf823
+	jne	0xf452
+	jp	0xf452
 	movsd	(%r15,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0xf81a
-	jnp	0xf823
-	addsd	%xmm3, %xmm4
-	movsd	%xmm4, (%r9)
+	jne	0xf449
+	jnp	0xf452
+	addsd	%xmm3, %xmm0
+	movsd	%xmm0, (%r9)
 	cmpq	%rdi, %rsi
-	je	0xf7f0
+	je	0xf420
 	movsd	(%r15,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0xf836
-	jnp	0xf7f0
-	addsd	%xmm3, %xmm1
-	movsd	%xmm1, 24(%r10)
+	jne	0xf465
+	jnp	0xf420
+	addsd	%xmm3, %xmm4
+	movsd	%xmm4, 24(%r10)
 	ucomisd	%xmm2, %xmm5
-	jne	0xf848
-	jnp	0xf7f0
-	addsd	%xmm3, %xmm0
-	movsd	%xmm0, (%r10)
-	jmp	0xf7f0
-	unpcklpd	%xmm4, %xmm0
-	jmp	0xf86b
+	jne	0xf477
+	jnp	0xf420
+	addsd	%xmm3, %xmm1
+	movsd	%xmm1, (%r10)
+	jmp	0xf420
+	divsd	%xmm4, %xmm0
+	jmp	0xf494
+	movsd	16576(%rip), %xmm0
 	xorpd	%xmm1, %xmm1
-	movq	-152(%rbp), %r12
-	movq	-208(%rbp), %r14
-	movsd	8(%r10), %xmm2
-	unpcklpd	%xmm1, %xmm2
-	divpd	%xmm2, %xmm0
-	movupd	%xmm0, 32(%r10)
+	movq	-176(%rbp), %rbx
+	movq	-168(%rbp), %r15
+	divsd	8(%r10), %xmm1
+	movsd	%xmm1, 32(%r10)
+	movsd	%xmm0, 40(%r10)
 	testl	%r11d, %r11d
-	jne	0xf890
-	leaq	18108(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
-	callq	0x13556 ## symbol stub for: _puts
+	js	0xf4c5
+	leaq	19085(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
+	callq	0x133d0 ## symbol stub for: _puts
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-256(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-216(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-240(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%rbx, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r15, %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-232(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-256(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-192(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-144(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-56(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-144(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-160(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	addq	$248, %rsp
+	callq	0x133ac ## symbol stub for: _free
+	movq	-200(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-152(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-224(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-216(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-208(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	addq	$280, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopw	(%rax,%rax)
+	nopl	(%rax,%rax)
 _cv_gene_nets_support_adaENcv:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
 	subq	$408, %rsp
-	movsd	%xmm0, -352(%rbp)
-	movq	%r9, -432(%rbp)
-	movq	%r8, -200(%rbp)
-	movq	%rcx, -424(%rbp)
+	movsd	%xmm0, -360(%rbp)
+	movq	%r9, -440(%rbp)
+	movq	%r8, -168(%rbp)
+	movq	%rcx, -432(%rbp)
 	movl	%edx, %r14d
-	movl	%edx, -92(%rbp)
-	movq	%rsi, -232(%rbp)
-	movq	%rdi, -256(%rbp)
+	movl	%edx, -116(%rbp)
+	movq	%rsi, -240(%rbp)
+	movq	%rdi, -272(%rbp)
 	movl	32(%rbp), %eax
-	movl	%eax, -160(%rbp)
+	movl	%eax, -232(%rbp)
 	movl	24(%rbp), %r12d
 	movl	16(%rbp), %ebx
 	movl	%ebx, %r15d
 	imull	%r15d, %r15d
-	movl	%r15d, -104(%rbp)
+	movl	%r15d, -100(%rbp)
 	movl	%r12d, %eax
 	imull	%ebx, %eax
-	movl	%ebx, -88(%rbp)
-	movl	%eax, -112(%rbp)
-	movl	%eax, -144(%rbp)
+	movl	%ebx, -80(%rbp)
+	movl	%eax, -136(%rbp)
+	movl	%eax, -152(%rbp)
 	movslq	%r15d, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -336(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -344(%rbp)
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -184(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -264(%rbp)
 	movslq	%ebx, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -120(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -112(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
 	movq	%rbx, -216(%rbp)
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -176(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -208(%rbp)
 	movl	$8, %esi
-	movq	%r13, -80(%rbp)
+	movq	%r13, -88(%rbp)
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -360(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -368(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -240(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -248(%rbp)
 	movl	%r12d, %eax
 	cltd
 	idivl	%r14d
 	movl	%eax, %r13d
 	movl	%eax, -56(%rbp)
 	movl	%r12d, %ebx
 	subl	%eax, %ebx
-	movl	-160(%rbp), %r14d
+	movl	-232(%rbp), %r14d
 	movslq	%r14d, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -304(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -312(%rbp)
 	movl	$8, %esi
-	movq	%r12, -384(%rbp)
+	movq	%r12, -392(%rbp)
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -192(%rbp)
-	movl	%r14d, %eax
-	imull	-92(%rbp), %eax
-	movl	%eax, -44(%rbp)
-	movq	%rbx, -408(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -224(%rbp)
+	imull	-116(%rbp), %r14d
+	movl	%r14d, -44(%rbp)
+	movq	%rbx, -416(%rbp)
 	movl	%ebx, %eax
-	movl	-88(%rbp), %edx
-	imull	%edx, %eax
-	movl	%eax, -372(%rbp)
-	imull	%edx, %r13d
-	movl	%r13d, -140(%rbp)
+	movl	-80(%rbp), %ecx
+	imull	%ecx, %eax
+	movl	%eax, -380(%rbp)
+	imull	%ecx, %r13d
+	movl	%r13d, -148(%rbp)
 	movslq	%eax, %r12
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -248(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -256(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -168(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -160(%rbp)
 	movslq	%r13d, %r13
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -272(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -280(%rbp)
 	movl	$8, %esi
 	movq	%r13, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -264(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -176(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -320(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -328(%rbp)
 	movl	$8, %esi
 	movq	%r12, %rdi
 	movl	48(%rbp), %r12d
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -312(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -320(%rbp)
 	movl	$8, %esi
 	movq	-216(%rbp), %rbx
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -400(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -408(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -392(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -400(%rbp)
 	movabsq	$4681608360884174848, %rax
-	movq	%rax, -136(%rbp)
+	movq	%rax, -144(%rbp)
 	cmpl	$2, %r12d
-	jl	0xfbed
-	leaq	16939(%rip), %rdi ## literal pool for: "\t\ti_alpha %d; \t Enter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n"
+	jl	0xf81b
+	leaq	17883(%rip), %rdi ## literal pool for: "\t\ti_alpha %d; \t Enter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n"
 	movl	72(%rbp), %esi
-	movl	%r14d, %edx
-	movl	-92(%rbp), %r13d
+	movl	-232(%rbp), %edx
+	movl	-116(%rbp), %r13d
 	movl	%r13d, %ecx
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	cmpl	$4, %r12d
-	jle	0xfbed
-	leaq	16339(%rip), %rbx ## literal pool for: "\n\t\t\t\t\tEnter Function: ridge_cvf. %d-fold cross validation.\n"
+	jbe	0xf847
+	leaq	16942(%rip), %rbx ## literal pool for: "\n\t\t\t\t\tEnter Function: ridge_cvf. %d-fold cross validation.\n"
 	movq	%rbx, %rdi
 	movl	%r13d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
-	movl	$0, -128(%rbp)
+	movl	$0, -124(%rbp)
 	movq	%rbx, %rdi
-	movl	-160(%rbp), %r14d
 	movl	%r13d, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movb	$1, %al
-	movl	%eax, -224(%rbp)
-	jmp	0xfc0c
+	movl	%eax, -184(%rbp)
+	jmp	0xf866
 	movl	$1, -52(%rbp)
 	movl	$1, -48(%rbp)
-	movl	$0, -128(%rbp)
-	movl	$0, -224(%rbp)
-	movl	-112(%rbp), %eax
-	movq	88(%rbp), %r12
-	movl	$0, -96(%rbp)
+	movl	$0, -124(%rbp)
+	movl	$0, -184(%rbp)
+	movq	-176(%rbp), %r12
+	movl	-116(%rbp), %r13d
+	jmp	0xf86d
+	movl	$1, -52(%rbp)
+	movl	$1, -48(%rbp)
+	movl	$0, -124(%rbp)
+	movl	$0, -184(%rbp)
+	movq	-176(%rbp), %r12
+	movl	-80(%rbp), %ebx
+	movl	-136(%rbp), %eax
+	movq	88(%rbp), %r14
+	movl	$0, -92(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -216(%rbp)
 	movl	$8, %esi
-	movq	-80(%rbp), %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -112(%rbp)
+	movq	-88(%rbp), %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -136(%rbp)
 	movb	$78, -58(%rbp)
 	movb	$78, -57(%rbp)
-	movl	-88(%rbp), %eax
-	movl	%eax, -292(%rbp)
-	movl	%eax, -288(%rbp)
-	movl	%eax, -284(%rbp)
-	movl	%eax, -124(%rbp)
+	movl	%ebx, -300(%rbp)
+	movl	%ebx, -296(%rbp)
+	movl	%ebx, -292(%rbp)
+	movl	%ebx, -120(%rbp)
 	cmpl	$0, 72(%rbp)
-	je	0xfc76
-	movsd	(%r12), %xmm0
-	movsd	%xmm0, -80(%rbp)
-	jmp	0x10570
+	je	0xf8dc
+	movsd	(%r14), %xmm0
+	movsd	%xmm0, -88(%rbp)
+	jmp	0x10167
 	cmpl	$0, 40(%rbp)
-	jle	0x1028b
-	movsd	14760(%rip), %xmm0
-	movsd	14896(%rip), %xmm1
-	movsd	%xmm0, -208(%rbp)
+	jle	0xfebd
+	movsd	15282(%rip), %xmm0
+	movsd	15402(%rip), %xmm1
+	movsd	%xmm0, -200(%rbp)
 	xorl	%esi, %esi
-	movq	-184(%rbp), %r13
-	movq	-120(%rbp), %r9
-	movl	-92(%rbp), %r12d
-	movq	-176(%rbp), %r10
-	jmp	0xfcc9
+	movq	-112(%rbp), %r15
+	jmp	0xf919
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	cmpl	40(%rbp), %esi
-	jge	0x102ba
-	movsd	%xmm1, -152(%rbp)
+	jge	0xfede
+	movsd	%xmm1, -192(%rbp)
 	movslq	%esi, %rax
-	movq	-200(%rbp), %rcx
+	movq	-168(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	movsd	%xmm0, -80(%rbp)
-	movq	$0, -136(%rbp)
-	testl	%r12d, %r12d
-	jle	0x10230
+	movsd	%xmm0, -88(%rbp)
+	movq	$0, -144(%rbp)
+	testl	%r13d, %r13d
+	jle	0xfe70
 	xorl	%ebx, %ebx
-	jmp	0xfd43
+	jmp	0xf993
 	nopl	(%rax)
-	leaq	-140(%rbp), %rdi
+	leaq	-148(%rbp), %rdi
 	movq	%rbx, %rsi
 	movq	%rcx, %rdx
 	movq	%rbx, %rcx
 	movq	%r9, %r8
-	callq	0x13508 ## symbol stub for: _ddot
+	callq	0x13382 ## symbol stub for: _ddot
 	movapd	%xmm0, %xmm1
-	addsd	-136(%rbp), %xmm1
-	movsd	%xmm1, -136(%rbp)
-	movl	-92(%rbp), %r12d
-	movl	-88(%rbp), %ebx
-	cmpl	%r12d, %ebx
-	movq	-184(%rbp), %r13
-	je	0x10220
+	addsd	-144(%rbp), %xmm1
+	movsd	%xmm1, -144(%rbp)
+	movl	-116(%rbp), %r13d
+	movl	-80(%rbp), %ebx
+	cmpl	%r13d, %ebx
+	movq	-176(%rbp), %r12
+	je	0xfe60
 	movl	48(%rbp), %eax
 	cmpl	$7, %eax
-	jl	0xfd5b
-	leaq	15978(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t crossValidation %d/Kcv\n\n"
+	jl	0xf9ab
+	leaq	16554(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t\t crossValidation %d/Kcv\n\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %r13d
 	movl	%r13d, %r15d
 	imull	%ebx, %r15d
-	addl	$1, %ebx
+	incl	%ebx
 	movl	%r13d, %eax
-	movl	%ebx, -88(%rbp)
+	movl	%ebx, -80(%rbp)
 	imull	%ebx, %eax
 	movl	%eax, %ebx
 	movl	16(%rbp), %eax
 	movl	%r15d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
-	movq	-232(%rbp), %r14
+	movq	-240(%rbp), %r14
 	leaq	(%r14,%rcx,8), %rsi
 	imull	%r13d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
-	movq	-264(%rbp), %rcx
+	movq	%r12, %rcx
 	leaq	-48(%rbp), %r12
 	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r15d, %r15d
-	je	0xfe20
+	je	0xfa70
 	movl	16(%rbp), %eax
 	imull	%r15d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rdi
 	movq	%r14, %rsi
 	leaq	-52(%rbp), %rdx
-	movq	-168(%rbp), %rcx
+	movq	-160(%rbp), %rcx
 	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %ebx
 	leaq	-44(%rbp), %r12
-	je	0xfe54
+	je	0xfaa4
 	movl	24(%rbp), %eax
 	subl	%ebx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
-	movl	%eax, -100(%rbp)
+	movl	%eax, -96(%rbp)
 	imull	%ebx, %ecx
 	movslq	%ecx, %rax
-	movq	-232(%rbp), %rcx
+	movq	-240(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
-	movq	-168(%rbp), %rcx
+	movq	-160(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
-	leaq	-100(%rbp), %rdi
+	leaq	-96(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	jmp	0xfe54
+	callq	0x1337c ## symbol stub for: _dcopy
+	jmp	0xfaa4
+	nopl	(%rax,%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%ebx, %ecx
 	imull	%eax, %ecx
 	imull	%ebx, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	leaq	-44(%rbp), %r14
 	movq	%r14, %rdi
 	leaq	-52(%rbp), %rdx
-	movq	-168(%rbp), %rcx
+	movq	-160(%rbp), %rcx
 	movq	%r12, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r14, %r12
 	movl	16(%rbp), %eax
 	imull	%eax, %r13d
 	imull	%r15d, %eax
 	cltq
-	movq	-256(%rbp), %r14
+	movq	-272(%rbp), %r14
 	leaq	(%r14,%rax,8), %rsi
 	movl	%r13d, -44(%rbp)
 	movq	%r12, %rdi
 	leaq	-52(%rbp), %r13
 	movq	%r13, %rdx
-	movq	-272(%rbp), %rcx
+	movq	-280(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r15d, %r15d
-	je	0xff30
+	je	0xfb60
 	imull	16(%rbp), %r15d
 	movl	%r15d, -44(%rbp)
 	movq	%r12, %rdi
 	movq	%r14, %rsi
 	movq	%r13, %rdx
-	movq	-248(%rbp), %r12
+	movq	-256(%rbp), %r12
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	%ebx, %edx
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %ebx
-	movq	%r13, %r14
-	movq	-120(%rbp), %r9
-	movq	-176(%rbp), %r10
-	movq	-184(%rbp), %rbx
-	leaq	-56(%rbp), %r15
-	je	0xff79
+	movq	-112(%rbp), %r15
+	movq	-208(%rbp), %r10
+	leaq	-56(%rbp), %r14
+	je	0xfb9f
 	movl	24(%rbp), %eax
-	subl	%edx, %eax
+	subl	%ebx, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
-	movl	%eax, -100(%rbp)
-	imull	%edx, %ecx
+	movl	%eax, -96(%rbp)
+	imull	%ebx, %ecx
 	movslq	%ecx, %rax
-	movq	-256(%rbp), %rcx
+	movq	-272(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	leaq	(%r12,%rax,8), %rcx
-	leaq	-100(%rbp), %rdi
-	movq	%r14, %rdx
+	leaq	-96(%rbp), %rdi
+	movq	%r13, %rdx
 	leaq	-48(%rbp), %r8
-	movq	%r9, %r13
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r13, %r9
-	movq	-176(%rbp), %r10
-	jmp	0xff79
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
+	movq	%r10, %rbx
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	%rbx, %r10
+	jmp	0xfb9f
+	nop
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%ebx, %ecx
 	imull	%eax, %ecx
 	imull	%ebx, %eax
 	cltq
 	leaq	(%r14,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%r12, %rdi
 	movq	%r13, %rdx
-	movq	-248(%rbp), %r12
+	movq	-256(%rbp), %r12
 	movq	%r12, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r13, %r14
-	movq	-120(%rbp), %r9
-	movq	-176(%rbp), %r10
-	movq	-184(%rbp), %rbx
-	leaq	-56(%rbp), %r15
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	-112(%rbp), %r15
+	movq	-208(%rbp), %r10
+	leaq	-56(%rbp), %r14
 	movl	16(%rbp), %edx
 	movq	%r12, %rdi
-	movq	-168(%rbp), %rsi
-	movsd	-80(%rbp), %xmm0
-	movq	-408(%rbp), %rcx
+	movq	-160(%rbp), %rsi
+	movsd	-88(%rbp), %xmm0
+	movq	-416(%rbp), %rcx
+	movq	-264(%rbp), %rbx
 	movq	%rbx, %r8
+	movq	%r15, %r9
 	movl	48(%rbp), %eax
 	pushq	%rax
 	pushq	%r10
 	callq	_constrained_ridge_cff
 	addq	$16, %rsp
-	movsd	%xmm0, -208(%rbp)
-	leaq	-104(%rbp), %r12
-	movq	%r12, %rdi
+	movsd	%xmm0, -200(%rbp)
+	leaq	-100(%rbp), %r15
+	movq	%r15, %rdi
 	movq	%rbx, %rsi
-	movq	%r14, %rdx
-	movq	-112(%rbp), %rbx
+	movq	%r13, %rdx
+	movq	-136(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
-	movq	%r12, %rdi
-	leaq	-72(%rbp), %r13
-	movq	%r13, %rsi
+	movq	%r15, %rdi
+	leaq	-72(%rbp), %r15
+	movq	%r15, %rsi
 	movq	%rbx, %rdx
-	movq	%r14, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
+	movq	%r13, %rcx
+	callq	0x133a0 ## symbol stub for: _dscal
 	movl	16(%rbp), %r8d
 	testl	%r8d, %r8d
-	jle	0x10010
+	jle	0xfc50
 	cmpl	$1, %r8d
-	jne	0x10030
+	jne	0xfc60
 	xorl	%ecx, %ecx
-	movq	-112(%rbp), %r10
-	movsd	13863(%rip), %xmm1
-	jmp	0x10093
-	nop
-	xorl	%r8d, %r8d
-	movq	-112(%rbp), %r10
-	leaq	16(%rbp), %rdx
-	leaq	-124(%rbp), %r12
-	jmp	0x100bb
+	movq	-136(%rbp), %rsi
+	movsd	14433(%rip), %xmm1
+	leaq	16(%rbp), %r13
+	jmp	0xfcc0
 	nopw	%cs:(%rax,%rax)
-	nop
+	xorl	%r8d, %r8d
+	leaq	16(%rbp), %r13
+	leaq	-120(%rbp), %r12
+	jmp	0xfce2
 	movl	%r8d, %edx
 	andl	$-2, %edx
-	leal	1(%r8), %esi
+	leal	1(%r8), %r9d
 	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
-	movq	-112(%rbp), %r10
-	movsd	13791(%rip), %xmm1
-	nopw	%cs:(%rax,%rax)
+	movq	-136(%rbp), %rsi
+	movsd	14364(%rip), %xmm1
+	leaq	16(%rbp), %r13
 	nopl	(%rax,%rax)
 	movslq	%ebx, %rbx
-	movsd	(%r10,%rbx,8), %xmm0
+	movsd	(%rsi,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
-	movsd	%xmm0, (%r10,%rbx,8)
-	leal	(%rsi,%rbx), %eax
+	movsd	%xmm0, (%rsi,%rbx,8)
+	leal	(%r9,%rbx), %eax
 	cltq
-	movsd	(%r10,%rax,8), %xmm0
+	movsd	(%rsi,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
-	movsd	%xmm0, (%r10,%rax,8)
+	movsd	%xmm0, (%rsi,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
 	cmpq	%rcx, %rdx
-	jne	0x10060
+	jne	0xfc90
 	testb	$1, %r8b
-	leaq	16(%rbp), %rdx
-	leaq	-124(%rbp), %r12
-	je	0x100bb
+	leaq	-120(%rbp), %r12
+	je	0xfce2
 	movl	%r8d, %eax
 	imull	%ecx, %eax
 	addl	%ecx, %eax
 	cltq
-	movsd	(%r10,%rax,8), %xmm0
+	movsd	(%rsi,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
-	movsd	%xmm0, (%r10,%rax,8)
+	movsd	%xmm0, (%rsi,%rax,8)
 	movl	%r8d, -44(%rbp)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -72(%rbp)
-	movq	$0, -280(%rbp)
+	movq	$0, -288(%rbp)
 	subq	$8, %rsp
 	leaq	-58(%rbp), %rdi
 	leaq	-57(%rbp), %rsi
-	movq	%r15, %rcx
+	movq	%r13, %rdx
+	movq	%r14, %rcx
 	movq	%r12, %r8
-	movq	%r13, %r9
-	leaq	-284(%rbp), %rax
-	pushq	%rax
-	movq	-216(%rbp), %rbx
-	pushq	%rbx
-	leaq	-280(%rbp), %rax
+	movq	%r15, %r9
+	leaq	-292(%rbp), %rax
 	pushq	%rax
+	pushq	-216(%rbp)
 	leaq	-288(%rbp), %rax
 	pushq	%rax
-	pushq	-272(%rbp)
-	leaq	-292(%rbp), %rax
+	leaq	-296(%rbp), %rax
 	pushq	%rax
-	pushq	%r10
-	callq	0x1350e ## symbol stub for: _dgemm
+	pushq	-280(%rbp)
+	leaq	-300(%rbp), %rax
+	pushq	%rax
+	pushq	-136(%rbp)
+	movq	%r13, %rbx
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	$0, -44(%rbp)
 	cmpl	$0, 16(%rbp)
-	movapd	13655(%rip), %xmm1
-	movq	%r13, %r12
-	movq	-120(%rbp), %r13
-	movq	%r15, %r14
-	movq	-264(%rbp), %r15
-	jle	0x10193
+	movapd	14216(%rip), %xmm1
+	movq	%r15, %r12
+	movq	-112(%rbp), %r15
+	movq	%r14, %r13
+	movq	-176(%rbp), %r14
+	jle	0xfdc7
 	xorl	%eax, %eax
-	nop
+	nopl	(%rax)
 	cltq
-	leaq	(%r15,%rax,8), %rdx
-	leaq	(%rbx,%rax,8), %r8
-	movsd	(%r13,%rax,8), %xmm0
+	leaq	(%r14,%rax,8), %rdx
+	movq	-216(%rbp), %rcx
+	leaq	(%rcx,%rax,8), %r8
+	movsd	(%r15,%rax,8), %xmm0
 	xorpd	%xmm1, %xmm0
 	movlpd	%xmm0, -72(%rbp)
-	movq	%r14, %rdi
+	movq	%r13, %rdi
 	movq	%r12, %rsi
-	leaq	-124(%rbp), %rcx
-	leaq	16(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	movapd	13579(%rip), %xmm1
+	leaq	-120(%rbp), %rcx
+	movq	%rbx, %r9
+	callq	0x13376 ## symbol stub for: _daxpy
+	movapd	14134(%rip), %xmm1
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	16(%rbp), %eax
-	jl	0x10150
+	jl	0xfd80
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	movl	$0, -44(%rbp)
 	cmpl	$0, -56(%rbp)
-	leaq	16(%rbp), %r12
+	movq	%rbx, %r14
 	leaq	-52(%rbp), %rcx
 	leaq	-48(%rbp), %r9
-	movq	-176(%rbp), %r13
-	jle	0xfd00
-	movq	%r12, %rdi
+	movq	-208(%rbp), %r12
+	movq	-216(%rbp), %rbx
+	jle	0xf950
+	movq	%r14, %rdi
 	leaq	-72(%rbp), %rsi
-	movq	%r13, %rdx
-	movq	%rcx, %r14
+	movq	%r12, %rdx
+	movq	%rcx, %r15
 	movq	%rbx, %r8
-	movq	%r9, %r15
-	nopl	(%rax,%rax)
-	callq	0x134fc ## symbol stub for: _daxpy
-	movq	%r14, %rcx
-	movq	%r15, %r9
+	movq	%r9, %r13
+	nopw	%cs:(%rax,%rax)
+	callq	0x13376 ## symbol stub for: _daxpy
+	movq	%r15, %rcx
+	movq	%r13, %r9
 	movl	-44(%rbp), %eax
-	addl	$1, %eax
+	incl	%eax
 	movl	%eax, -44(%rbp)
 	cmpl	-56(%rbp), %eax
-	jge	0xfd00
+	jge	0xf950
 	imull	16(%rbp), %eax
 	cltq
 	leaq	(%rbx,%rax,8), %r8
-	movq	%r12, %rdi
+	movq	%r14, %rdi
 	leaq	-72(%rbp), %rsi
-	movq	%r13, %rdx
-	movq	%r14, %rcx
-	movq	%r15, %r9
-	jmp	0x101e0
+	movq	%r12, %rdx
+	movq	%r15, %rcx
+	movq	%r13, %r9
+	jmp	0xfe20
+	nopl	(%rax,%rax)
+	movl	-92(%rbp), %esi
+	movq	-112(%rbp), %r15
+	jmp	0xfe74
 	nopl	(%rax)
-	movl	-96(%rbp), %esi
-	movq	-176(%rbp), %r10
-	movq	-120(%rbp), %r9
-	jmp	0x10234
 	xorpd	%xmm1, %xmm1
-	addl	$1, %esi
-	movl	%esi, -96(%rbp)
+	incl	%esi
+	movl	%esi, -92(%rbp)
 	movl	48(%rbp), %eax
 	cmpl	$6, %eax
-	jl	0x1026c
-	leaq	14740(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t Test rho ratio %f; (%d/Nrho)\t error: %f.\n"
-	movsd	-80(%rbp), %xmm0
+	jl	0xfe9f
+	leaq	15333(%rip), %rdi ## literal pool for: "\t\t\t\t\t\t Test rho ratio %f; (%d/Nrho)\t error: %f.\n"
+	movsd	-88(%rbp), %xmm0
 	movb	$2, %al
-	movq	%r10, %r14
-	movq	%r9, %r15
-	callq	0x1354a ## symbol stub for: _printf
-	movq	%r15, %r9
-	movq	%r14, %r10
-	movl	-96(%rbp), %esi
-	movsd	-136(%rbp), %xmm1
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-92(%rbp), %esi
+	movsd	-144(%rbp), %xmm1
 	cmpl	$2, %esi
-	jl	0xfcc0
-	ucomisd	-152(%rbp), %xmm1
-	jb	0xfcc0
-	addl	$-1, %esi
-	movl	%esi, -96(%rbp)
-	jmp	0x102ba
+	jl	0xf910
+	ucomisd	-192(%rbp), %xmm1
+	jb	0xf910
+	decl	%esi
+	movl	%esi, -92(%rbp)
+	jmp	0xfede
 	xorps	%xmm0, %xmm0
-	movsd	%xmm0, -152(%rbp)
-	movsd	13202(%rip), %xmm0
-	movsd	%xmm0, -208(%rbp)
+	movsd	%xmm0, -192(%rbp)
+	movsd	13776(%rip), %xmm0
+	movsd	%xmm0, -200(%rbp)
 	xorl	%esi, %esi
-	movq	-184(%rbp), %r13
-	movq	-120(%rbp), %r9
-	movq	-176(%rbp), %r10
-	movq	%r13, %r14
-	movl	-224(%rbp), %ebx
+	movq	-112(%rbp), %r15
+	movl	-184(%rbp), %ebx
 	testb	%bl, %bl
-	je	0x102ec
-	leaq	14656(%rip), %rdi ## literal pool for: "\t\t\t\t\tExit RidgeCV. sigma2R: %f\t"
-	movsd	-208(%rbp), %xmm0
+	je	0xff01
+	leaq	15279(%rip), %rdi ## literal pool for: "\t\t\t\t\tExit RidgeCV. sigma2R: %f\t"
+	movsd	-200(%rbp), %xmm0
 	movb	$1, %al
-	movq	%r10, %r15
-	movq	%r9, %r12
-	callq	0x1354a ## symbol stub for: _printf
-	movq	%r12, %r9
-	movq	%r15, %r10
-	movl	-96(%rbp), %esi
-	movsd	-136(%rbp), %xmm1
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-92(%rbp), %esi
+	movsd	-144(%rbp), %xmm1
 	movapd	%xmm1, %xmm0
 	cmpl	$1, %esi
-	je	0x10305
-	movsd	-152(%rbp), %xmm0
-	movl	-144(%rbp), %eax
+	movq	-264(%rbp), %r14
+	je	0xff21
+	movsd	-192(%rbp), %xmm0
+	movl	-152(%rbp), %eax
 	cmpl	40(%rbp), %esi
-	je	0x10314
+	je	0xff30
 	movapd	%xmm0, %xmm1
-	addl	$-1, %eax
+	decl	%eax
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
-	addl	$-1, %esi
+	decl	%esi
 	movslq	%esi, %rax
 	movl	24(%rbp), %ecx
 	cvtsi2sd	%ecx, %xmm2
-	movq	-200(%rbp), %rdx
+	movq	-168(%rbp), %rdx
 	mulsd	(%rdx,%rax,8), %xmm2
 	movl	%ecx, %eax
 	subl	-56(%rbp), %eax
 	divsd	%xmm0, %xmm1
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
 	testb	%bl, %bl
-	movsd	%xmm1, -88(%rbp)
-	je	0x10388
-	leaq	14551(%rip), %rdi ## literal pool for: "sigma2learnt: %f\n"
-	movsd	%xmm0, -208(%rbp)
+	movsd	%xmm1, -200(%rbp)
+	je	0xff93
+	leaq	15178(%rip), %rdi ## literal pool for: "sigma2learnt: %f\n"
+	movsd	%xmm0, -88(%rbp)
 	movapd	%xmm1, %xmm0
 	movb	$1, %al
-	movq	%r10, %rbx
-	movq	%r9, %r15
 	movsd	%xmm2, -80(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movsd	-208(%rbp), %xmm0
+	callq	0x133c4 ## symbol stub for: _printf
+	movsd	-88(%rbp), %xmm0
 	movsd	-80(%rbp), %xmm2
-	movq	%r15, %r9
-	movq	%rbx, %r10
 	divsd	%xmm0, %xmm2
-	movl	48(%rbp), %eax
-	testl	%eax, %eax
-	movq	%r14, %rbx
-	je	0x103c4
-	movl	16(%rbp), %edx
-	movq	-256(%rbp), %rdi
-	movq	-232(%rbp), %rsi
-	movapd	%xmm2, %xmm0
-	movl	24(%rbp), %ecx
-	movq	%rbx, %r8
-	pushq	%rax
-	pushq	%r10
-	callq	_constrained_ridge_cff
-	movsd	-88(%rbp), %xmm6
-	addq	$16, %rsp
-	jmp	0x10428
-	leaq	14915(%rip), %rdi ## literal pool for: "Step 1: ridge CV; find rho : %f\n"
+	movl	48(%rbp), %ebx
+	testl	%ebx, %ebx
+	js	0x10004
+	leaq	15947(%rip), %rdi ## literal pool for: "Step 1: ridge CV; find rho : %f\n"
 	movapd	%xmm2, %xmm0
 	movb	$1, %al
-	movq	%r10, %r15
-	movq	%r9, %r12
 	movsd	%xmm2, -80(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	16(%rbp), %edx
-	movq	-256(%rbp), %rdi
-	movq	-232(%rbp), %rsi
+	movq	-272(%rbp), %rdi
+	movq	-240(%rbp), %rsi
 	movsd	-80(%rbp), %xmm0
 	movl	24(%rbp), %ecx
-	movq	%rbx, %r8
-	movq	%r12, %r9
-	pushq	$0
-	pushq	%r15
+	movq	%r14, %r8
+	movq	%r15, %r9
+	pushq	%rbx
+	pushq	-208(%rbp)
 	callq	_constrained_ridge_cff
 	addq	$16, %rsp
-	movsd	%xmm0, -80(%rbp)
-	leaq	15086(%rip), %rdi ## literal pool for: "Step 2: ridge; calculate weights."
-	callq	0x13556 ## symbol stub for: _puts
-	movsd	-88(%rbp), %xmm6
-	movsd	-80(%rbp), %xmm0
+	movsd	%xmm0, -88(%rbp)
+	leaq	16157(%rip), %rdi ## literal pool for: "Step 2: ridge; calculate weights."
+	callq	0x133d0 ## symbol stub for: _puts
+	movsd	-200(%rbp), %xmm6
+	movsd	-88(%rbp), %xmm0
+	jmp	0x1003a
+	movl	16(%rbp), %edx
+	movq	-272(%rbp), %rdi
+	movq	-240(%rbp), %rsi
+	movapd	%xmm2, %xmm0
+	movl	24(%rbp), %ecx
+	movq	%r14, %r8
+	movq	%r15, %r9
+	pushq	%rbx
+	pushq	-208(%rbp)
+	callq	_constrained_ridge_cff
+	movsd	-200(%rbp), %xmm6
+	addq	$16, %rsp
 	movq	56(%rbp), %rbx
-	movq	88(%rbp), %r9
+	movq	88(%rbp), %rax
 	movq	64(%rbp), %r8
-	movl	-104(%rbp), %r15d
+	movl	-100(%rbp), %r15d
 	testl	%r15d, %r15d
-	jle	0x1044a
+	jle	0x1005c
 	cmpl	$1, %r15d
-	jne	0x10451
+	jne	0x10063
 	xorl	%ecx, %ecx
-	jmp	0x10514
+	jmp	0x10117
 	xorl	%edx, %edx
-	jmp	0x10557
+	jmp	0x10156
 	movl	%r15d, %ecx
 	andl	$-2, %ecx
-	leaq	-2(%rcx), %rsi
-	movq	%rsi, %rdx
-	shrq	%rdx
-	addq	$1, %rdx
-	testq	%rsi, %rsi
-	je	0x114dd
-	movq	%rdx, %rdi
+	leaq	-2(%rcx), %rdx
+	movq	%rdx, %rsi
+	shrq	%rsi
+	incq	%rsi
+	testq	%rdx, %rdx
+	je	0x110a3
+	movq	%rsi, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
-	xorl	%esi, %esi
-	movapd	12910(%rip), %xmm5
-	movapd	12822(%rip), %xmm1
-	movapd	12830(%rip), %xmm2
-	movq	%r14, %rax
-	nopw	%cs:(%rax,%rax)
-	nop
-	movupd	(%rax,%rsi,8), %xmm3
+	xorl	%edx, %edx
+	movapd	13520(%rip), %xmm5
+	movapd	13416(%rip), %xmm1
+	movapd	13424(%rip), %xmm2
+	movupd	(%r14,%rdx,8), %xmm3
 	addpd	%xmm5, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divpd	%xmm3, %xmm4
-	movupd	%xmm4, (%rbx,%rsi,8)
-	movupd	16(%rax,%rsi,8), %xmm3
+	movupd	%xmm4, (%rbx,%rdx,8)
+	movupd	16(%r14,%rdx,8), %xmm3
 	addpd	%xmm5, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divpd	%xmm3, %xmm4
-	movupd	%xmm4, 16(%rbx,%rsi,8)
-	addq	$4, %rsi
-	addq	$2, %rdi
-	jne	0x104a0
-	testb	$1, %dl
-	je	0x1050c
-	movupd	(%r14,%rsi,8), %xmm2
-	addpd	12797(%rip), %xmm2
-	andpd	12709(%rip), %xmm2
-	movapd	12717(%rip), %xmm1
+	movupd	%xmm4, 16(%rbx,%rdx,8)
+	addq	$4, %rdx
+	addq	$-2, %rdi
+	jne	0x100a0
+	testb	$1, %sil
+	je	0x1010f
+	movupd	(%r14,%rdx,8), %xmm2
+	addpd	13418(%rip), %xmm2
+	andpd	13314(%rip), %xmm2
+	movapd	13322(%rip), %xmm1
 	divpd	%xmm2, %xmm1
-	movupd	%xmm1, (%rbx,%rsi,8)
+	movupd	%xmm1, (%rbx,%rdx,8)
 	movl	%r15d, %edx
 	cmpq	%r15, %rcx
-	je	0x10557
-	movsd	12580(%rip), %xmm5
-	movapd	12668(%rip), %xmm1
-	movsd	12548(%rip), %xmm2
-	nopl	(%rax)
+	je	0x10156
+	movsd	13201(%rip), %xmm5
+	movapd	13273(%rip), %xmm1
+	movsd	13169(%rip), %xmm2
+	nop
 	movsd	(%r14,%rcx,8), %xmm3
 	addsd	%xmm5, %xmm3
 	andpd	%xmm1, %xmm3
 	movapd	%xmm2, %xmm4
 	divsd	%xmm3, %xmm4
 	movsd	%xmm4, (%rbx,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %r15
-	jne	0x10530
+	jne	0x10130
 	movl	%r15d, %edx
 	movl	%edx, -44(%rbp)
 	movsd	%xmm6, (%r8)
-	movsd	%xmm0, -80(%rbp)
-	movsd	%xmm0, (%r9)
-	movl	-160(%rbp), %r14d
+	movsd	%xmm0, -88(%rbp)
+	movsd	%xmm0, (%rax)
 	movl	%r15d, %eax
-	movl	-92(%rbp), %ebx
-	imull	%ebx, %eax
-	movl	%eax, -96(%rbp)
-	movslq	%eax, %r12
+	imull	%r13d, %eax
+	movl	%eax, -92(%rbp)
+	movslq	%eax, %r14
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -200(%rbp)
+	movq	%r14, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -184(%rbp)
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -344(%rbp)
-	movslq	%ebx, %rdi
+	movq	%r14, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -352(%rbp)
+	movslq	%r13d, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -328(%rbp)
-	movq	$0, -280(%rbp)
-	testl	%ebx, %ebx
-	jle	0x106e2
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -336(%rbp)
+	movq	$0, -288(%rbp)
+	testl	%r13d, %r13d
+	jle	0x102ca
 	xorl	%r12d, %r12d
-	nopw	%cs:(%rax,%rax)
+	leaq	-48(%rbp), %r14
 	nopl	(%rax,%rax)
 	imull	%r12d, %r15d
 	movslq	%r15d, %rax
-	movq	-200(%rbp), %rcx
+	movq	-184(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %r13
-	leaq	-104(%rbp), %rdi
-	leaq	-280(%rbp), %rsi
-	leaq	-128(%rbp), %rdx
+	leaq	-100(%rbp), %rdi
+	leaq	-288(%rbp), %rsi
+	leaq	-124(%rbp), %rdx
 	movq	%r13, %rcx
-	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r14, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %r8d
 	movl	$0, %eax
 	testl	%r8d, %r8d
-	jle	0x106ca
+	jle	0x102b2
 	leaq	-1(%r8), %rax
 	movl	%r8d, %ecx
 	andl	$3, %ecx
 	cmpq	$3, %rax
-	jae	0x10640
+	jae	0x10230
 	xorl	%edx, %edx
 	movabsq	$4607182418800017408, %rbx
-	jmp	0x106a4
+	jmp	0x10294
 	nopl	(%rax)
 	movl	%r8d, %r10d
 	andl	$-4, %r10d
 	leal	(%r8,%r8), %r9d
 	addl	$2, %r9d
 	leal	4(,%r8,4), %r11d
 	leal	1(%r8), %r15d
@@ -12711,736 +12833,717 @@
 	movq	%rbx, (%r13,%rax,8)
 	leal	(%rdi,%rsi), %eax
 	cltq
 	movq	%rbx, (%r13,%rax,8)
 	addq	$4, %rdx
 	addl	%r11d, %esi
 	cmpq	%rdx, %r10
-	jne	0x10670
+	jne	0x10260
 	testq	%rcx, %rcx
-	je	0x106c0
+	je	0x102af
 	leal	1(%r8), %eax
 	imull	%eax, %edx
 	movslq	%edx, %rdx
 	movq	%rbx, (%r13,%rdx,8)
 	addl	%eax, %edx
-	addq	$-1, %rcx
-	jne	0x106b0
+	decq	%rcx
+	jne	0x102a0
 	movl	%r8d, %eax
-	movl	-160(%rbp), %r14d
 	movl	%eax, -44(%rbp)
-	addl	$1, %r12d
-	movl	-92(%rbp), %ebx
-	cmpl	%ebx, %r12d
-	je	0x106e2
-	movl	-104(%rbp), %r15d
-	jmp	0x105e0
-	leaq	-96(%rbp), %rdi
+	incl	%r12d
+	movl	-116(%rbp), %r13d
+	cmpl	%r13d, %r12d
+	je	0x102ca
+	movl	-100(%rbp), %r15d
+	jmp	0x101d0
+	leaq	-92(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	movq	-200(%rbp), %rsi
-	movq	-344(%rbp), %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	testl	%r14d, %r14d
+	movq	-184(%rbp), %rsi
+	movq	-352(%rbp), %rcx
+	callq	0x1337c ## symbol stub for: _dcopy
+	cmpl	$0, -232(%rbp)
 	movl	48(%rbp), %r12d
 	movq	%r12, %r14
-	movq	-192(%rbp), %r13
+	movq	-224(%rbp), %rbx
 	movq	-216(%rbp), %r12
-	movq	-232(%rbp), %r15
-	jle	0x11182
-	movl	%ebx, %eax
-	movq	%rax, -416(%rbp)
-	movsd	12025(%rip), %xmm0
-	movsd	%xmm0, -224(%rbp)
+	movq	-240(%rbp), %r15
+	jle	0x10d44
+	movl	%r13d, %eax
+	movq	%rax, -424(%rbp)
+	movsd	12668(%rip), %xmm0
+	movsd	%xmm0, -232(%rbp)
 	xorl	%ecx, %ecx
-	jmp	0x10768
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	addq	$1, %rcx
-	cmpq	-384(%rbp), %rcx
-	movq	-192(%rbp), %r13
-	jge	0x11182
-	movq	$0, -136(%rbp)
-	testl	%ebx, %ebx
-	movq	%rcx, -152(%rbp)
-	jle	0x10f80
+	jmp	0x10347
+	incq	%rcx
+	cmpq	-392(%rbp), %rcx
+	movq	-224(%rbp), %rbx
+	jge	0x10d44
+	movq	$0, -144(%rbp)
+	testl	%r13d, %r13d
+	movq	%rcx, -168(%rbp)
+	jle	0x10b40
 	xorl	%ebx, %ebx
-	jmp	0x107a7
+	jmp	0x10387
 	nopw	%cs:(%rax,%rax)
-	movq	-208(%rbp), %rax
+	movq	-200(%rbp), %rax
 	movq	%rax, %rbx
-	cmpq	-416(%rbp), %rax
-	je	0x10f50
+	cmpq	-424(%rbp), %rax
+	je	0x10b10
 	cmpl	$4, %r14d
-	jl	0x107bd
-	leaq	13485(%rip), %rdi ## literal pool for: "\t\t %d/Kcv cross validation.\n"
+	jl	0x1039d
+	leaq	14173(%rip), %rdi ## literal pool for: "\t\t %d/Kcv cross validation.\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-56(%rbp), %r12d
 	movl	%r12d, %r13d
 	imull	%ebx, %r13d
-	movq	%rbx, -88(%rbp)
+	movq	%rbx, -80(%rbp)
 	leaq	1(%rbx), %rax
-	movq	%rax, -208(%rbp)
+	movq	%rax, -200(%rbp)
 	movl	%eax, %r14d
 	imull	%r12d, %r14d
 	movl	16(%rbp), %eax
 	movl	%r13d, %ecx
 	imull	%eax, %ecx
 	movslq	%ecx, %rcx
 	leaq	(%r15,%rcx,8), %rsi
 	imull	%r12d, %eax
 	movl	%eax, -44(%rbp)
 	leaq	-44(%rbp), %rbx
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %rdx
-	movq	-264(%rbp), %rcx
+	movq	-176(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r13d, %r13d
-	je	0x10880
+	je	0x10460
 	movl	16(%rbp), %eax
 	imull	%r13d, %eax
 	movl	%eax, -44(%rbp)
 	movq	%rbx, %rdi
 	movq	%r15, %rsi
 	leaq	-52(%rbp), %rdx
-	movq	-168(%rbp), %rcx
+	movq	-160(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %r14d
-	je	0x108b0
+	je	0x10490
 	movl	24(%rbp), %eax
 	subl	%r14d, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
-	movl	%eax, -100(%rbp)
+	movl	%eax, -96(%rbp)
 	imull	%r14d, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r15,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
-	movq	-168(%rbp), %rcx
+	movq	-160(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
-	leaq	-100(%rbp), %rdi
+	leaq	-96(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
-	jmp	0x108a7
+	jmp	0x10487
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%r14d, %ecx
 	imull	%eax, %ecx
 	imull	%r14d, %eax
 	cltq
 	leaq	(%r15,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %rdx
-	movq	-168(%rbp), %rcx
+	movq	-160(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %eax
 	imull	%eax, %r12d
 	imull	%r13d, %eax
 	cltq
-	movq	-256(%rbp), %r15
+	movq	-272(%rbp), %r15
 	leaq	(%r15,%rax,8), %rsi
 	movl	%r12d, -44(%rbp)
 	movq	%rbx, %rdi
 	leaq	-52(%rbp), %r12
 	movq	%r12, %rdx
-	movq	-272(%rbp), %rcx
+	movq	-280(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r13d, %r13d
-	je	0x10950
+	je	0x10530
 	imull	16(%rbp), %r13d
 	movl	%r13d, -44(%rbp)
 	movq	%rbx, %rdi
 	movq	%r15, %rsi
 	movq	%r12, %rdx
-	movq	-248(%rbp), %rbx
+	movq	-256(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	24(%rbp), %r14d
-	je	0x10982
+	je	0x10562
 	movl	24(%rbp), %eax
 	subl	%r14d, %eax
 	movl	16(%rbp), %ecx
 	imull	%ecx, %eax
-	movl	%eax, -100(%rbp)
+	movl	%eax, -96(%rbp)
 	imull	%r14d, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r15,%rax,8), %rsi
 	movslq	-44(%rbp), %rax
 	leaq	(%rbx,%rax,8), %rcx
-	leaq	-100(%rbp), %rdi
+	leaq	-96(%rbp), %rdi
 	movq	%r12, %rdx
-	jmp	0x10979
+	jmp	0x10559
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	movl	16(%rbp), %eax
 	movl	24(%rbp), %ecx
 	subl	%r14d, %ecx
 	imull	%eax, %ecx
 	imull	%r14d, %eax
 	cltq
 	leaq	(%r15,%rax,8), %rsi
 	movl	%ecx, -44(%rbp)
 	movq	%rbx, %rdi
 	movq	%r12, %rdx
-	movq	-248(%rbp), %rbx
+	movq	-256(%rbp), %rbx
 	movq	%rbx, %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-372(%rbp), %r15
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-380(%rbp), %r15
 	movq	%r15, %rdi
-	movq	-168(%rbp), %rsi
+	movq	-160(%rbp), %rsi
 	movq	%r12, %rdx
-	movq	-312(%rbp), %r14
+	movq	-320(%rbp), %r14
 	movq	%r14, %rcx
 	leaq	-48(%rbp), %r13
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	%r15, %rdi
 	movq	%rbx, %rsi
 	movq	%r12, %rdx
-	movq	-320(%rbp), %rbx
+	movq	-328(%rbp), %rbx
 	movq	%rbx, %rcx
 	movq	%r13, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %r8d
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
-	movq	-400(%rbp), %rdx
-	movq	-392(%rbp), %rcx
-	movq	-408(%rbp), %r15
+	movq	-408(%rbp), %rdx
+	movq	-400(%rbp), %rcx
+	movq	-416(%rbp), %r15
 	movl	%r15d, %r9d
 	callq	_centerYX
-	movq	-152(%rbp), %rcx
+	movq	-168(%rbp), %rcx
 	testq	%rcx, %rcx
-	je	0x10a40
-	movq	-328(%rbp), %rax
-	movq	-88(%rbp), %rdx
+	je	0x10620
+	movq	-336(%rbp), %rax
+	movq	-80(%rbp), %rdx
 	movsd	(%rax,%rdx,8), %xmm3
-	movq	-184(%rbp), %r13
-	movsd	-352(%rbp), %xmm4
+	movq	-264(%rbp), %r13
+	movsd	-360(%rbp), %xmm4
 	movq	%r15, %r11
-	movq	-336(%rbp), %r14
+	movq	-344(%rbp), %r14
 	movq	56(%rbp), %r12
-	movsd	-80(%rbp), %xmm2
-	jmp	0x10b00
+	movsd	-88(%rbp), %xmm2
+	jmp	0x106e0
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -72(%rbp)
 	leaq	16(%rbp), %rdi
 	leaq	-72(%rbp), %r12
 	movq	%r12, %rsi
-	leaq	-128(%rbp), %r13
+	leaq	-124(%rbp), %r13
 	movq	%r13, %rdx
-	movq	-120(%rbp), %rcx
+	movq	-112(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, -72(%rbp)
-	leaq	-104(%rbp), %rdi
+	leaq	-100(%rbp), %rdi
 	movq	%r12, %rsi
 	movq	%r13, %rdx
-	movq	-184(%rbp), %rcx
+	movq	-264(%rbp), %rcx
 	movq	%rcx, %r13
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	16(%rbp), %ecx
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
-	movq	-336(%rbp), %r12
+	movq	-344(%rbp), %r12
 	movq	%r12, %rdx
-	movsd	-80(%rbp), %xmm0
+	movsd	-88(%rbp), %xmm0
 	movl	%r15d, %r8d
 	callq	_QlambdaStart
 	movl	16(%rbp), %ecx
 	movq	%rbx, %rdi
 	movq	%r14, %rsi
 	movq	%r12, %r14
 	movq	56(%rbp), %r12
 	movq	%r12, %rdx
 	movl	%r15d, %r8d
-	movsd	-352(%rbp), %xmm0
+	movsd	-360(%rbp), %xmm0
 	callq	_lambdaMax_adaEN
-	movsd	-352(%rbp), %xmm4
-	movsd	-80(%rbp), %xmm2
-	movq	-152(%rbp), %rcx
+	movsd	-360(%rbp), %xmm4
+	movsd	-88(%rbp), %xmm2
+	movq	-168(%rbp), %rcx
 	movapd	%xmm0, %xmm3
-	movq	-328(%rbp), %rax
-	movq	-88(%rbp), %rdx
+	movq	-336(%rbp), %rax
+	movq	-80(%rbp), %rdx
 	movsd	%xmm0, (%rax,%rdx,8)
 	movq	%r15, %r11
-	movq	-424(%rbp), %rax
+	movq	-432(%rbp), %rax
 	movsd	(%rax,%rcx,8), %xmm0
-	movl	-104(%rbp), %eax
+	movl	-100(%rbp), %eax
 	imull	%edx, %eax
 	cltq
-	movq	-200(%rbp), %rcx
+	movq	-184(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rbx
-	movq	-344(%rbp), %rcx
+	movq	-352(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rax
 	movl	16(%rbp), %r10d
 	subq	$8, %rsp
 	movq	%r12, %rdi
 	movq	%r13, %rsi
-	movq	-120(%rbp), %rdx
-	movq	-248(%rbp), %rcx
-	movq	-168(%rbp), %r8
+	movq	-112(%rbp), %rdx
+	movq	-256(%rbp), %rcx
+	movq	-160(%rbp), %r8
 	movq	%r14, %r9
-	movsd	%xmm0, -440(%rbp)
-	movsd	-224(%rbp), %xmm1
-	movsd	%xmm2, -80(%rbp)
+	movsd	%xmm0, -448(%rbp)
+	movsd	-232(%rbp), %xmm1
+	movsd	%xmm2, -88(%rbp)
 	pushq	%rax
-	movq	%rbx, -160(%rbp)
+	movq	%rbx, -192(%rbp)
 	pushq	%rbx
-	pushq	-176(%rbp)
-	pushq	-240(%rbp)
-	pushq	-360(%rbp)
+	pushq	-208(%rbp)
+	pushq	-248(%rbp)
+	pushq	-368(%rbp)
 	movl	48(%rbp), %r15d
 	pushq	%r15
 	movq	%r11, %r12
 	pushq	%r11
 	pushq	%r10
-	pushq	-432(%rbp)
+	pushq	-440(%rbp)
 	callq	_Weighted_LassoSf_MLf_adaEN
 	addq	$80, %rsp
 	cmpl	$4, %r15d
-	jl	0x10bf0
-	leaq	12504(%rip), %rdi ## literal pool for: "\t\t\t step 1 SML lasso regression, lambda: %f.\n"
+	jl	0x107d0
+	leaq	13192(%rip), %rdi ## literal pool for: "\t\t\t step 1 SML lasso regression, lambda: %f.\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	16(%rbp), %r9d
-	movq	-320(%rbp), %rdi
-	movq	-312(%rbp), %rsi
+	movq	-328(%rbp), %rdi
+	movq	-320(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r13, %rcx
-	movq	-120(%rbp), %r8
-	movsd	-80(%rbp), %xmm0
-	pushq	-160(%rbp)
+	movq	-112(%rbp), %r8
+	movsd	-88(%rbp), %xmm0
+	pushq	-192(%rbp)
 	pushq	%r12
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	leaq	13058(%rip), %rdi ## literal pool for: "\t\t\t step 2 SML ZeroRegression."
-	callq	0x13556 ## symbol stub for: _puts
-	jmp	0x10c22
+	leaq	14120(%rip), %rdi ## literal pool for: "\t\t\t step 2 SML ZeroRegression."
+	callq	0x133d0 ## symbol stub for: _puts
+	jmp	0x10802
 	nopl	(%rax)
 	movl	16(%rbp), %r9d
-	movq	-320(%rbp), %rdi
-	movq	-312(%rbp), %rsi
+	movq	-328(%rbp), %rdi
+	movq	-320(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r13, %rcx
-	movq	-120(%rbp), %r8
-	movsd	-80(%rbp), %xmm0
-	pushq	-160(%rbp)
+	movq	-112(%rbp), %r8
+	movsd	-88(%rbp), %xmm0
+	pushq	-192(%rbp)
 	pushq	%r12
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	movq	-216(%rbp), %r12
-	movq	-112(%rbp), %r14
-	movabsq	$4607182418800017408, %rbx
-	leaq	-48(%rbp), %r8
-	leaq	-104(%rbp), %r13
+	movq	-136(%rbp), %r14
+	movabsq	$4607182418800017408, %r12
+	leaq	-100(%rbp), %r13
 	movq	%r13, %rdi
-	movq	-360(%rbp), %rsi
+	movq	-368(%rbp), %rsi
 	leaq	-52(%rbp), %r15
 	movq	%r15, %rdx
 	movq	%r14, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	leaq	-48(%rbp), %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
 	movq	%r13, %rdi
 	leaq	-72(%rbp), %rsi
 	movq	%r14, %rdx
 	movq	%r15, %rcx
-	callq	0x13526 ## symbol stub for: _dscal
-	movl	16(%rbp), %r9d
-	testl	%r9d, %r9d
-	jle	0x10cb0
-	cmpl	$1, %r9d
-	leaq	16(%rbp), %r15
-	leaq	-56(%rbp), %r13
-	leaq	-124(%rbp), %r8
-	movq	%rbx, %r11
-	jne	0x10cd0
+	callq	0x133a0 ## symbol stub for: _dscal
+	movl	16(%rbp), %r8d
+	testl	%r8d, %r8d
+	jle	0x10880
+	cmpl	$1, %r8d
+	leaq	16(%rbp), %rdx
+	jne	0x10890
 	xorl	%ecx, %ecx
-	movq	-112(%rbp), %r10
-	movsd	10636(%rip), %xmm1
-	leaq	-72(%rbp), %r14
-	jmp	0x10d33
-	nopl	(%rax)
-	xorl	%r9d, %r9d
-	movq	-112(%rbp), %r10
-	leaq	16(%rbp), %r15
-	leaq	-72(%rbp), %r14
-	leaq	-56(%rbp), %r13
-	leaq	-124(%rbp), %r8
-	jmp	0x10d56
+	movsd	11311(%rip), %xmm1
+	jmp	0x108e4
+	nopw	%cs:(%rax,%rax)
+	xorl	%r8d, %r8d
+	leaq	16(%rbp), %rdx
+	jmp	0x10904
 	nopl	(%rax)
-	movl	%r9d, %edx
-	andl	$-2, %edx
-	leal	1(%r9), %esi
-	leal	(%r9,%r9), %edi
+	movl	%r8d, %esi
+	andl	$-2, %esi
+	leal	1(%r8), %r9d
+	leal	(%r8,%r8), %edi
 	addl	$2, %edi
 	xorl	%ebx, %ebx
 	xorl	%ecx, %ecx
-	movq	-112(%rbp), %r10
-	movsd	10559(%rip), %xmm1
-	leaq	-72(%rbp), %r14
-	nopw	%cs:(%rax,%rax)
-	nop
+	movsd	11251(%rip), %xmm1
+	nopl	(%rax)
 	movslq	%ebx, %rbx
-	movsd	(%r10,%rbx,8), %xmm0
+	movsd	(%r14,%rbx,8), %xmm0
 	addsd	%xmm1, %xmm0
-	movsd	%xmm0, (%r10,%rbx,8)
-	leal	(%rsi,%rbx), %eax
+	movsd	%xmm0, (%r14,%rbx,8)
+	leal	(%r9,%rbx), %eax
 	cltq
-	movsd	(%r10,%rax,8), %xmm0
+	movsd	(%r14,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
-	movsd	%xmm0, (%r10,%rax,8)
+	movsd	%xmm0, (%r14,%rax,8)
 	addq	$2, %rcx
 	addl	%edi, %ebx
-	cmpq	%rcx, %rdx
-	jne	0x10d00
-	testb	$1, %r9b
-	je	0x10d53
-	movl	%r9d, %eax
+	cmpq	%rcx, %rsi
+	jne	0x108b0
+	testb	$1, %r8b
+	je	0x10904
+	movl	%r8d, %eax
 	imull	%ecx, %eax
 	addl	%ecx, %eax
 	cltq
-	movsd	(%r10,%rax,8), %xmm0
+	movsd	(%r14,%rax,8), %xmm0
 	addsd	%xmm1, %xmm0
-	movsd	%xmm0, (%r10,%rax,8)
-	movq	%r11, %rbx
-	movl	%r9d, -44(%rbp)
-	movq	%rbx, -72(%rbp)
-	movq	$0, -280(%rbp)
-	movl	-140(%rbp), %eax
-	imull	-88(%rbp), %eax
+	movsd	%xmm0, (%r14,%rax,8)
+	leaq	-72(%rbp), %r15
+	leaq	-56(%rbp), %r13
+	leaq	-120(%rbp), %r14
+	movl	%r8d, -44(%rbp)
+	movq	%r12, -72(%rbp)
+	movq	$0, -288(%rbp)
+	movl	-148(%rbp), %eax
+	imull	-80(%rbp), %eax
 	cltq
+	movq	-216(%rbp), %r12
 	leaq	(%r12,%rax,8), %rbx
 	subq	$8, %rsp
 	leaq	-58(%rbp), %rdi
 	leaq	-57(%rbp), %rsi
-	movq	%r15, %rdx
 	movq	%r13, %rcx
-	movq	%r14, %r9
-	leaq	-284(%rbp), %rax
+	movq	%r14, %r8
+	movq	%r15, %r9
+	leaq	-292(%rbp), %rax
 	pushq	%rax
-	movq	%rbx, -160(%rbp)
+	movq	%rbx, -192(%rbp)
 	pushq	%rbx
-	leaq	-280(%rbp), %rax
-	pushq	%rax
 	leaq	-288(%rbp), %rax
 	pushq	%rax
-	pushq	-272(%rbp)
-	leaq	-292(%rbp), %rax
+	leaq	-296(%rbp), %rax
 	pushq	%rax
-	pushq	%r10
-	callq	0x1350e ## symbol stub for: _dgemm
+	pushq	-280(%rbp)
+	leaq	-300(%rbp), %rax
+	pushq	%rax
+	pushq	-136(%rbp)
+	callq	0x13388 ## symbol stub for: _dgemm
 	addq	$64, %rsp
 	movl	$0, -44(%rbp)
 	movl	16(%rbp), %eax
 	testl	%eax, %eax
-	movq	%r15, %rcx
-	movq	%r13, %rdi
-	movq	-264(%rbp), %r13
-	movapd	10408(%rip), %xmm1
-	movq	-240(%rbp), %r15
-	jle	0x10e67
+	leaq	16(%rbp), %rcx
+	movq	%r15, %r9
+	movq	-176(%rbp), %rsi
+	movapd	11074(%rip), %xmm1
+	movq	-248(%rbp), %r10
+	jle	0x10a2e
 	xorl	%edx, %edx
-	nopw	%cs:(%rax,%rax)
 	nopl	(%rax)
 	movslq	%edx, %rax
-	leaq	(,%rax,8), %rdx
-	addq	%r13, %rdx
-	movl	-140(%rbp), %ebx
-	imull	-88(%rbp), %ebx
+	leaq	(%rsi,%rax,8), %rdx
+	movl	-148(%rbp), %ebx
+	imull	-80(%rbp), %ebx
 	addl	%eax, %ebx
 	movslq	%ebx, %rbx
 	leaq	(%r12,%rbx,8), %r8
-	movsd	(%r15,%rax,8), %xmm0
+	movsd	(%r10,%rax,8), %xmm0
 	xorpd	%xmm1, %xmm0
 	movlpd	%xmm0, -72(%rbp)
-	movq	%r14, %rsi
+	movq	%r13, %rdi
+	movq	%r9, %r15
+	movq	%r9, %rsi
 	movq	%rcx, %r12
-	movq	%rdi, %rbx
-	leaq	-124(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
-	movapd	10310(%rip), %xmm1
-	movq	%rbx, %rdi
+	movq	%r14, %r9
+	movq	%r10, %rbx
+	callq	0x13376 ## symbol stub for: _daxpy
+	movq	%rbx, %r10
+	movapd	10981(%rip), %xmm1
+	movq	-176(%rbp), %rsi
 	movq	%r12, %rcx
 	movq	-216(%rbp), %r12
+	movq	%r15, %r9
 	movl	-44(%rbp), %edx
-	addl	$1, %edx
+	incl	%edx
 	movl	%edx, -44(%rbp)
 	movl	16(%rbp), %eax
 	cmpl	%eax, %edx
-	jl	0x10e00
+	jl	0x109c0
 	movabsq	$-4616189618054758400, %rcx
 	movq	%rcx, -72(%rbp)
 	movl	$0, -44(%rbp)
 	cmpl	$0, -56(%rbp)
-	movq	-232(%rbp), %r15
-	movq	%r14, %r13
+	movq	-240(%rbp), %r15
 	movl	48(%rbp), %ebx
 	movq	%rbx, %r14
-	movq	-88(%rbp), %rbx
-	jle	0x10ef0
+	movq	-80(%rbp), %rbx
+	jle	0x10ab0
+	movq	%r9, %r13
 	xorl	%ecx, %ecx
-	nopl	(%rax,%rax)
+	nop
 	imull	%ecx, %eax
-	movl	-140(%rbp), %ecx
+	movl	-148(%rbp), %ecx
 	imull	%ebx, %ecx
 	addl	%eax, %ecx
 	movslq	%ecx, %rax
 	leaq	(%r12,%rax,8), %r8
 	leaq	16(%rbp), %rdi
 	movq	%r13, %rsi
-	movq	-176(%rbp), %rdx
+	movq	-208(%rbp), %rdx
 	leaq	-52(%rbp), %rcx
 	leaq	-48(%rbp), %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movl	-44(%rbp), %ecx
-	addl	$1, %ecx
+	incl	%ecx
 	movl	%ecx, -44(%rbp)
 	cmpl	-56(%rbp), %ecx
-	jge	0x10ef0
+	jge	0x10ab0
 	movl	16(%rbp), %eax
-	jmp	0x10ea0
+	jmp	0x10a60
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	leaq	-140(%rbp), %rdi
-	movq	-160(%rbp), %rcx
+	leaq	-148(%rbp), %rdi
+	movq	-192(%rbp), %rcx
 	movq	%rcx, %rsi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13508 ## symbol stub for: _ddot
-	movsd	-136(%rbp), %xmm1
+	callq	0x13382 ## symbol stub for: _ddot
+	movsd	-144(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
-	movsd	%xmm1, -136(%rbp)
+	movsd	%xmm1, -144(%rbp)
 	cmpl	$4, %r14d
-	jl	0x10790
-	leaq	11641(%rip), %rdi ## literal pool for: "\t\t\t cv: %d \tend; err_mean = %f.\n"
+	jl	0x10370
+	leaq	12361(%rip), %rdi ## literal pool for: "\t\t\t cv: %d \tend; err_mean = %f.\n"
 	movl	%ebx, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	jmp	0x10790
+	callq	0x133c4 ## symbol stub for: _printf
+	jmp	0x10370
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
-	movsd	-136(%rbp), %xmm0
-	movsd	-440(%rbp), %xmm1
-	movsd	%xmm1, -224(%rbp)
-	movq	-192(%rbp), %r13
-	movq	-152(%rbp), %rcx
-	jmp	0x10f84
+	movsd	-144(%rbp), %xmm0
+	movsd	-448(%rbp), %xmm1
+	movsd	%xmm1, -232(%rbp)
+	movq	-224(%rbp), %rbx
+	movq	-168(%rbp), %rcx
+	jmp	0x10b44
 	nopl	(%rax,%rax)
 	xorpd	%xmm0, %xmm0
-	movl	-144(%rbp), %eax
+	movl	-152(%rbp), %eax
 	xorps	%xmm1, %xmm1
 	cvtsi2sd	%eax, %xmm1
 	divsd	%xmm1, %xmm0
-	movsd	%xmm0, -136(%rbp)
-	movsd	%xmm0, (%r13,%rcx,8)
+	movsd	%xmm0, -144(%rbp)
+	movsd	%xmm0, (%rbx,%rcx,8)
 	testl	%eax, %eax
-	jle	0x10fc0
+	jle	0x10b80
 	cmpl	$4, %eax
-	jae	0x10fd0
+	jae	0x10b90
 	xorl	%ecx, %ecx
-	jmp	0x11090
+	jmp	0x10c50
 	nopw	%cs:(%rax,%rax)
-	nop
 	movq	%r14, %r13
 	xorl	%eax, %eax
-	jmp	0x110b9
+	jmp	0x10c78
 	nopw	(%rax,%rax)
 	movl	%eax, %ecx
 	andl	$-4, %ecx
 	leaq	-4(%rcx), %rsi
 	movq	%rsi, %rdx
 	shrq	$2, %rdx
-	addq	$1, %rdx
+	incq	%rdx
 	testq	%rsi, %rsi
-	je	0x11172
+	je	0x10d34
 	movq	%rdx, %rdi
 	andq	$-2, %rdi
-	negq	%rdi
 	xorl	%esi, %esi
-	nopl	(%rax)
+	nopw	%cs:(%rax,%rax)
 	movupd	(%r12,%rsi,8), %xmm0
 	movupd	16(%r12,%rsi,8), %xmm1
 	movupd	32(%r12,%rsi,8), %xmm2
 	movupd	48(%r12,%rsi,8), %xmm3
 	mulpd	%xmm0, %xmm0
 	mulpd	%xmm1, %xmm1
 	movupd	%xmm0, (%r12,%rsi,8)
 	movupd	%xmm1, 16(%r12,%rsi,8)
 	mulpd	%xmm2, %xmm2
 	mulpd	%xmm3, %xmm3
 	movupd	%xmm2, 32(%r12,%rsi,8)
 	movupd	%xmm3, 48(%r12,%rsi,8)
 	addq	$8, %rsi
-	addq	$2, %rdi
-	jne	0x11000
+	addq	$-2, %rdi
+	jne	0x10bc0
 	testb	$1, %dl
-	je	0x11077
+	je	0x10c37
 	movupd	(%r12,%rsi,8), %xmm0
 	movupd	16(%r12,%rsi,8), %xmm1
 	mulpd	%xmm0, %xmm0
 	mulpd	%xmm1, %xmm1
 	movupd	%xmm0, (%r12,%rsi,8)
 	movupd	%xmm1, 16(%r12,%rsi,8)
 	cmpq	%rax, %rcx
-	jne	0x11090
+	jne	0x10c50
 	movq	%r14, %r13
-	jmp	0x110b9
+	jmp	0x10c78
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	movq	%r14, %r13
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movsd	(%r12,%rcx,8), %xmm0
 	mulsd	%xmm0, %xmm0
 	movsd	%xmm0, (%r12,%rcx,8)
-	addq	$1, %rcx
+	incq	%rcx
 	cmpq	%rcx, %rax
-	jne	0x110a0
+	jne	0x10c60
 	movl	%eax, -44(%rbp)
 	movabsq	$-4616189618054758400, %rax
 	movq	%rax, -72(%rbp)
-	leaq	-144(%rbp), %r14
+	leaq	-152(%rbp), %r14
 	movq	%r14, %rdi
 	leaq	-72(%rbp), %rsi
-	leaq	-136(%rbp), %rdx
-	leaq	-128(%rbp), %rcx
+	leaq	-144(%rbp), %rdx
+	leaq	-124(%rbp), %rcx
 	movq	%r12, %r8
 	leaq	-52(%rbp), %rbx
 	movq	%rbx, %r9
-	callq	0x134fc ## symbol stub for: _daxpy
+	callq	0x13376 ## symbol stub for: _daxpy
 	movq	%r14, %rdi
 	movq	%r12, %rsi
 	movq	%rbx, %rdx
-	callq	0x13520 ## symbol stub for: _dnrm2
+	callq	0x1339a ## symbol stub for: _dnrm2
 	movapd	%xmm0, %xmm1
-	movl	-144(%rbp), %eax
-	addl	$-1, %eax
-	movl	-92(%rbp), %ebx
-	imull	%ebx, %eax
+	movl	-152(%rbp), %eax
+	decl	%eax
+	movl	-116(%rbp), %edx
+	imull	%edx, %eax
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
 	sqrtsd	%xmm0, %xmm0
 	divsd	%xmm0, %xmm1
-	movq	-304(%rbp), %rax
-	movq	-152(%rbp), %rcx
+	movq	-312(%rbp), %rax
+	movq	-168(%rbp), %rcx
 	movsd	%xmm1, (%rax,%rcx,8)
 	movq	%r13, %r14
+	movl	%edx, %r13d
 	cmpl	$3, %r14d
-	jl	0x10750
-	movsd	-136(%rbp), %xmm0
-	leaq	11132(%rip), %rdi ## literal pool for: "\t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n"
-	movq	-152(%rbp), %rsi
-	movl	%ebx, %edx
-	movsd	-80(%rbp), %xmm2
+	jl	0x10330
+	movsd	-144(%rbp), %xmm0
+	leaq	11851(%rip), %rdi ## literal pool for: "\t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n"
+	movq	-168(%rbp), %rsi
+	movl	%r13d, %edx
+	movsd	-88(%rbp), %xmm2
 	movb	$3, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movq	-152(%rbp), %rcx
-	jmp	0x10750
+	callq	0x133c4 ## symbol stub for: _printf
+	movq	-168(%rbp), %rcx
+	jmp	0x10330
 	xorl	%esi, %esi
 	testb	$1, %dl
-	jne	0x11055
-	jmp	0x11077
+	jne	0x10c15
+	jmp	0x10c37
 	movl	$8, %esi
-	movq	-384(%rbp), %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	movq	-392(%rbp), %rdi
+	callq	0x1336a ## symbol stub for: _calloc
 	xorps	%xmm0, %xmm0
-	cvtsi2sdl	-144(%rbp), %xmm0
-	movq	%rax, %rbx
-	movsd	9503(%rip), %xmm1
+	cvtsi2sdl	-152(%rbp), %xmm0
+	movq	%rax, %r14
+	movsd	10173(%rip), %xmm1
 	subsd	%xmm0, %xmm1
-	movsd	%xmm1, -368(%rbp)
-	leaq	32(%rbp), %r14
-	leaq	-368(%rbp), %rsi
-	leaq	-128(%rbp), %rdx
-	leaq	-52(%rbp), %r15
-	movq	%r14, %rdi
+	movsd	%xmm1, -376(%rbp)
+	leaq	32(%rbp), %r15
+	leaq	-376(%rbp), %rsi
+	leaq	-124(%rbp), %rdx
+	leaq	-52(%rbp), %r13
+	movq	%r15, %rdi
 	movq	%rax, %rcx
-	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	movq	%r13, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movabsq	$4607182418800017408, %rax
 	movq	%rax, -72(%rbp)
 	leaq	-72(%rbp), %rsi
 	leaq	-48(%rbp), %r9
-	movq	%r14, %rdi
+	movq	%r15, %rdi
+	movq	%rbx, %rdx
+	movq	%r13, %rcx
+	movq	%r14, %r8
+	callq	0x13376 ## symbol stub for: _daxpy
+	movq	%r15, %rdi
+	movq	%r14, -80(%rbp)
+	movq	%r14, %rsi
 	movq	%r13, %rdx
-	movq	%r15, %rcx
-	movq	%rbx, %r8
-	callq	0x134fc ## symbol stub for: _daxpy
-	movq	%r14, %rdi
-	movq	%rbx, -88(%rbp)
+	callq	0x133b2 ## symbol stub for: _idamax
 	movq	%rbx, %rsi
-	movq	%r15, %rdx
-	callq	0x13538 ## symbol stub for: _idamax
-	movq	%r13, %rsi
 	movl	%eax, %r13d
 	leal	-1(%r13), %ebx
 	movslq	%ebx, %r15
 	movsd	(%rsi,%r15,8), %xmm0
-	movq	-304(%rbp), %r14
+	movq	-312(%rbp), %r14
 	addsd	(%r14,%r15,8), %xmm0
-	movsd	%xmm0, -368(%rbp)
+	movsd	%xmm0, -376(%rbp)
 	leaq	32(%rbp), %rdi
 	leaq	-52(%rbp), %rdx
 	movq	96(%rbp), %rcx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	32(%rbp), %rax
 	movq	96(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	leaq	32(%rbp), %rdi
 	movq	%r14, %rsi
 	leaq	-52(%rbp), %rdx
 	leaq	-48(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	testl	%r15d, %r15d
-	je	0x11346
+	je	0x10f09
 	addl	$-2, %r13d
 	testl	%r13d, %r13d
-	jle	0x1136e
-	movsd	-368(%rbp), %xmm0
+	jle	0x10f31
+	movsd	-376(%rbp), %xmm0
 	movl	%r13d, %eax
-	movq	-192(%rbp), %rcx
+	movq	-224(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm1
 	subsd	%xmm0, %xmm1
-	andpd	9211(%rip), %xmm1
+	andpd	9881(%rip), %xmm1
 	testb	$1, %al
 	movq	112(%rbp), %r8
 	movq	104(%rbp), %r9
 	movq	80(%rbp), %rdi
-	je	0x112d9
+	je	0x10e9a
 	movsd	(%rcx,%rax,8), %xmm2
 	subsd	%xmm0, %xmm2
-	andpd	9178(%rip), %xmm2
+	andpd	9848(%rip), %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmoval	%ebx, %ebx
 	minsd	%xmm1, %xmm2
-	addq	$-1, %rax
+	decq	%rax
 	movapd	%xmm2, %xmm1
-	movq	-120(%rbp), %r14
+	movq	-112(%rbp), %r14
 	movl	72(%rbp), %edx
-	movq	-240(%rbp), %r15
+	movq	-248(%rbp), %r15
 	cmpl	$1, %r13d
-	je	0x11341
-	movapd	9131(%rip), %xmm2
-	movq	-192(%rbp), %rsi
+	je	0x10f04
+	movapd	9802(%rip), %xmm2
+	movq	-224(%rbp), %rsi
 	nopl	(%rax)
 	movsd	(%rsi,%rax,8), %xmm3
 	subsd	%xmm0, %xmm3
 	andpd	%xmm2, %xmm3
 	ucomisd	%xmm3, %xmm1
 	minsd	%xmm1, %xmm3
 	movsd	-8(%rsi,%rax,8), %xmm1
@@ -13448,2057 +13551,2195 @@
 	cmoval	%ecx, %ebx
 	subsd	%xmm0, %xmm1
 	andpd	%xmm2, %xmm1
 	ucomisd	%xmm1, %xmm3
 	cmoval	%eax, %ebx
 	minsd	%xmm3, %xmm1
 	leaq	-2(%rax), %rcx
-	cmpq	$2, %rax
+	decq	%rax
+	cmpq	$1, %rax
 	movq	%rcx, %rax
-	jg	0x11300
+	ja	0x10ec0
 	xorl	%r13d, %r13d
-	jmp	0x11388
+	jmp	0x10f4b
 	movl	$1, %ebx
-	movq	-120(%rbp), %r14
+	movq	-112(%rbp), %r14
 	movl	72(%rbp), %edx
-	movq	-240(%rbp), %r15
-	movq	-192(%rbp), %r13
+	movq	-248(%rbp), %r15
+	movq	-224(%rbp), %r13
 	movq	112(%rbp), %r8
 	movq	104(%rbp), %r9
 	movq	80(%rbp), %rdi
-	jmp	0x11393
-	movq	-120(%rbp), %r14
+	jmp	0x10f56
+	movq	-112(%rbp), %r14
 	movl	72(%rbp), %edx
-	movq	-240(%rbp), %r15
+	movq	-248(%rbp), %r15
 	movq	112(%rbp), %r8
 	movq	104(%rbp), %r9
 	movq	80(%rbp), %rdi
 	movl	%r13d, -44(%rbp)
-	movq	-192(%rbp), %r13
+	movq	-224(%rbp), %r13
 	leal	-1(%rbx), %eax
 	cltq
 	movsd	(%r13,%rax,8), %xmm0
 	movslq	%edx, %rcx
 	movsd	%xmm0, (%rdi,%rcx,8)
 	movsd	%xmm0, (%r9,%rcx,8)
-	movq	-304(%rbp), %rdx
+	movq	-312(%rbp), %rdx
 	movsd	(%rdx,%rax,8), %xmm0
 	movsd	%xmm0, (%r8,%rcx,8)
 	movl	48(%rbp), %eax
 	cmpl	$2, %eax
-	jl	0x113d7
-	leaq	10568(%rip), %rdi ## literal pool for: "\t\tExit Function: cv_support. optimal lambda index: %d.\n\n"
+	jl	0x10f9a
+	leaq	11285(%rip), %rdi ## literal pool for: "\t\tExit Function: cv_support. optimal lambda index: %d.\n\n"
 	movl	%ebx, %esi
 	xorl	%eax, %eax
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-112(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-336(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-136(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-344(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-264(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-360(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-208(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-368(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-304(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-312(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-88(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-248(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-272(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-264(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-80(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-256(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-160(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-280(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-176(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-328(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-320(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-312(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-408(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-400(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-392(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-344(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-328(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-184(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-352(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-336(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movl	%ebx, %eax
 	addq	$408, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	xorl	%esi, %esi
-	testb	$1, %dl
-	jne	0x104e5
-	jmp	0x1050c
-	nopl	(%rax)
+	xorl	%edx, %edx
+	testb	$1, %sil
+	jne	0x100e8
+	jmp	0x1010f
+	nopw	%cs:(%rax,%rax)
 _mainSML_adaENcv:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
 	subq	$248, %rsp
 	movq	%r9, %r13
-	movq	%r8, -56(%rbp)
+	movq	%r8, %r14
 	movl	%edx, %r12d
 	movq	%rsi, -144(%rbp)
-	movq	%rdi, -88(%rbp)
+	movq	%rdi, -120(%rbp)
 	movq	24(%rbp), %r15
 	movl	%edx, -44(%rbp)
 	movl	$1, -68(%rbp)
 	movl	$1, -64(%rbp)
-	movl	$0, -124(%rbp)
-	movq	%rcx, -120(%rbp)
+	movl	$0, -128(%rbp)
+	movq	%rcx, -112(%rbp)
 	movl	%ecx, %eax
 	imull	%edx, %eax
-	movl	%eax, -80(%rbp)
-	movl	%eax, -204(%rbp)
+	movl	%eax, -96(%rbp)
+	movl	%eax, -124(%rbp)
 	movl	%edx, %eax
 	imull	%edx, %eax
 	movl	%eax, -60(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	-60(%rbp), %rdi
 	leaq	-68(%rbp), %rdx
 	leaq	-64(%rbp), %r8
 	movq	%r13, %rsi
-	movq	%rax, -224(%rbp)
+	movq	%rax, -232(%rbp)
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, 8(%r15)
 	testl	%r12d, %r12d
-	jle	0x11670
+	jle	0x11252
 	movl	%r12d, %r8d
 	movl	%r8d, %r9d
 	andl	$-2, %r9d
 	leal	(%r12,%r12), %edx
 	xorpd	%xmm0, %xmm0
-	xorl	%esi, %esi
-	movsd	8329(%rip), %xmm1
+	xorl	%eax, %eax
+	movsd	9005(%rip), %xmm1
 	xorpd	%xmm2, %xmm2
-	jmp	0x115bd
+	jmp	0x1118c
 	nopl	(%rax)
-	addq	$1, %rsi
-	cmpq	%r8, %rsi
-	je	0x11670
+	incq	%rax
+	cmpq	%r8, %rax
+	je	0x11252
 	cmpl	$1, %r12d
-	jne	0x11600
-	xorl	%eax, %eax
+	jne	0x111a0
+	xorl	%ebx, %ebx
 	testb	$1, %r8b
-	je	0x115b0
-	cmpq	%rax, %rsi
-	je	0x115b0
-	imull	%r12d, %eax
-	addl	%esi, %eax
-	cltq
-	movsd	(%r13,%rax,8), %xmm3
+	je	0x11180
+	jmp	0x1121e
+	nop
+	movl	%eax, %esi
+	xorl	%edi, %edi
+	jmp	0x111ba
+	nopw	%cs:(%rax,%rax)
+	addl	%edx, %esi
+	incq	%rdi
+	cmpq	%r9, %rdi
+	je	0x11210
+	movq	%rdi, %rbx
+	cmpq	%rdi, %rax
+	je	0x111de
+	movslq	%esi, %rdi
+	movsd	(%r13,%rdi,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x115e7
-	jnp	0x115b0
+	jne	0x111d4
+	jnp	0x111de
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r15)
-	jmp	0x115b0
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	movl	%esi, %edi
-	xorl	%ecx, %ecx
-	jmp	0x11625
-	nopw	%cs:(%rax,%rax)
-	movq	%rcx, %rax
-	addq	$2, %rax
-	addl	%edx, %edi
-	addq	$1, %rbx
-	movq	%rbx, %rcx
-	cmpq	%rax, %r9
-	je	0x115c5
-	cmpq	%rcx, %rsi
-	je	0x11646
-	movslq	%edi, %rax
-	movsd	(%r13,%rax,8), %xmm3
+	leaq	1(%rbx), %rdi
+	cmpq	%rdi, %rax
+	je	0x111b0
+	leal	(%r12,%rsi), %ecx
+	movslq	%ecx, %rcx
+	movsd	(%r13,%rcx,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x1163c
-	jnp	0x11646
+	jne	0x111fd
+	jnp	0x111b0
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r15)
-	leaq	1(%rcx), %rbx
-	cmpq	%rbx, %rsi
-	je	0x11610
-	leal	(%r12,%rdi), %eax
-	cltq
-	movsd	(%r13,%rax,8), %xmm3
+	jmp	0x111b0
+	nopl	(%rax)
+	addq	$2, %rbx
+	testb	$1, %r8b
+	je	0x11180
+	cmpq	%rbx, %rax
+	je	0x11180
+	imull	%r12d, %ebx
+	addl	%eax, %ebx
+	movslq	%ebx, %rcx
+	movsd	(%r13,%rcx,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x11664
-	jnp	0x11610
+	jne	0x11243
+	jnp	0x11180
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r15)
-	jmp	0x11610
-	movabsq	$4607182418800017408, %r12
-	movq	%r12, -256(%rbp)
+	jmp	0x11180
+	movabsq	$4607182418800017408, %rax
+	movq	%rax, -256(%rbp)
 	leaq	-44(%rbp), %rdi
 	leaq	-256(%rbp), %rbx
-	leaq	-124(%rbp), %r14
+	leaq	-128(%rbp), %r12
 	leaq	-68(%rbp), %r15
 	movq	%rbx, %rsi
-	movq	%r14, %rdx
+	movq	%r12, %rdx
 	movq	16(%rbp), %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, -256(%rbp)
 	leaq	-60(%rbp), %rdi
 	movq	%rbx, %rsi
-	movq	%r14, %rdx
+	movq	%r12, %rdx
 	movq	%r13, %rcx
 	movq	%r15, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	-80(%rbp), %r14d
-	testl	%r14d, %r14d
-	movq	-56(%rbp), %rdi
-	jle	0x116f8
-	movl	%r14d, %eax
-	cmpl	$1, %r14d
-	jne	0x1189a
+	callq	0x1337c ## symbol stub for: _dcopy
+	cmpl	$0, -96(%rbp)
+	movq	-120(%rbp), %rdi
+	jle	0x113e7
+	movl	-96(%rbp), %ecx
+	movl	%ecx, %eax
+	cmpl	$4, %ecx
+	jb	0x112d2
+	leaq	(%r14,%rax,4), %rcx
+	cmpq	%rdi, %rcx
+	jbe	0x1132f
+	leaq	(%rdi,%rax,8), %rcx
+	cmpq	%r14, %rcx
+	jbe	0x1132f
 	xorl	%ecx, %ecx
+	movq	%rcx, %rdx
+	notq	%rdx
 	testb	$1, %al
-	je	0x116f8
-	cmpl	$1, (%rdi,%rcx,4)
-	jne	0x116f8
-	movq	-88(%rbp), %rax
-	movq	$0, (%rax,%rcx,8)
+	je	0x112f1
+	cmpl	$1, (%r14,%rcx,4)
+	jne	0x112ed
+	movq	$0, (%rdi,%rcx,8)
+	orq	$1, %rcx
+	addq	%rax, %rdx
+	jne	0x1130d
+	jmp	0x113e7
+	nopl	(%rax,%rax)
+	addq	$2, %rcx
+	cmpq	%rcx, %rax
+	je	0x113e7
+	cmpl	$1, (%r14,%rcx,4)
+	jne	0x1131c
+	movq	$0, (%rdi,%rcx,8)
+	cmpl	$1, 4(%r14,%rcx,4)
+	jne	0x11300
+	movq	$0, 8(%rdi,%rcx,8)
+	jmp	0x11300
+	movl	%eax, %ecx
+	andl	$-4, %ecx
+	xorl	%edx, %edx
+	movdqa	8754(%rip), %xmm0
+	movdqa	8762(%rip), %xmm1
+	jmp	0x1135d
+	nopl	(%rax,%rax)
+	addq	$4, %rdx
+	cmpq	%rdx, %rcx
+	je	0x113de
+	movq	(%r14,%rdx,4), %xmm3
+	movq	8(%r14,%rdx,4), %xmm2
+	movdqa	%xmm3, %xmm4
+	pcmpeqd	%xmm0, %xmm4
+	movd	%xmm4, %esi
+	testb	$1, %sil
+	je	0x11384
+	movq	$0, (%rdi,%rdx,8)
+	pshufd	$212, %xmm3, %xmm3
+	pcmpeqd	%xmm1, %xmm3
+	pextrw	$4, %xmm3, %esi
+	testb	$1, %sil
+	je	0x113a1
+	movq	$0, 8(%rdi,%rdx,8)
+	movdqa	%xmm2, %xmm3
+	pcmpeqd	%xmm0, %xmm3
+	movd	%xmm3, %esi
+	testb	$1, %sil
+	je	0x113bc
+	movq	$0, 16(%rdi,%rdx,8)
+	pshufd	$212, %xmm2, %xmm2
+	pcmpeqd	%xmm1, %xmm2
+	pextrw	$4, %xmm2, %esi
+	testb	$1, %sil
+	je	0x11350
+	movq	$0, 24(%rdi,%rdx,8)
+	jmp	0x11350
+	cmpq	%rax, %rcx
+	jne	0x112d4
 	movl	$31, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
-	movsd	8126(%rip), %xmm1
+	movsd	8495(%rip), %xmm1
 	movl	$3, %ebx
-	nopw	(%rax,%rax)
-	movsd	8112(%rip), %xmm0
+	nopw	%cs:(%rax,%rax)
+	movsd	8480(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, -24(%r15,%rbx,8)
-	movsd	8095(%rip), %xmm0
+	movsd	8463(%rip), %xmm0
 	movsd	-56(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	8065(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
+	movsd	8433(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, -16(%r15,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	8048(%rip), %xmm1
-	movsd	8032(%rip), %xmm0
+	addsd	8416(%rip), %xmm1
+	movsd	8400(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, -8(%r15,%rbx,8)
 	cmpq	$31, %rbx
-	je	0x117ce
+	je	0x114be
 	movsd	-56(%rbp), %xmm1
-	movsd	8004(%rip), %xmm0
+	movsd	8372(%rip), %xmm0
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	7979(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
+	movsd	8347(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
 	movsd	%xmm0, (%r15,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	7963(%rip), %xmm1
+	addsd	8331(%rip), %xmm1
 	addq	$4, %rbx
-	jmp	0x11720
+	jmp	0x11410
 	movl	40(%rbp), %eax
 	movslq	%eax, %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -136(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r12
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -192(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -216(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -176(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -192(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -168(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -184(%rbp)
 	movslq	-60(%rbp), %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -56(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -104(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -96(%rbp)
-	movq	$0, -272(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %rbx
+	movq	$0, -264(%rbp)
 	leaq	-60(%rbp), %rdi
-	leaq	-272(%rbp), %rsi
-	leaq	-124(%rbp), %rdx
+	leaq	-264(%rbp), %rsi
+	leaq	-128(%rbp), %rdx
 	leaq	-64(%rbp), %r8
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r10d
 	testl	%r10d, %r10d
-	jle	0x1196f
+	movq	%rbx, -56(%rbp)
+	movabsq	$4607182418800017408, %rax
+	movq	%r12, -136(%rbp)
+	jle	0x1165e
 	leaq	-1(%r10), %rdx
 	movl	%r10d, %ecx
 	andl	$3, %ecx
 	xorl	%esi, %esi
 	cmpq	$3, %rdx
-	jae	0x118e5
+	jae	0x11596
 	xorl	%edx, %edx
-	movq	-96(%rbp), %rax
-	jmp	0x11943
-	movl	%eax, %edx
-	andl	$-2, %edx
-	xorl	%ecx, %ecx
-	jmp	0x118bd
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	addq	$2, %rcx
-	cmpq	%rcx, %rdx
-	je	0x116e2
-	cmpl	$1, (%rdi,%rcx,4)
-	jne	0x118cf
-	movq	-88(%rbp), %rsi
-	movq	$0, (%rsi,%rcx,8)
-	cmpl	$1, 4(%rdi,%rcx,4)
-	jne	0x118b0
-	movq	-88(%rbp), %rsi
-	movq	$0, 8(%rsi,%rcx,8)
-	jmp	0x118b0
+	jmp	0x11635
 	movl	%r10d, %r9d
 	andl	$-4, %r9d
-	leal	(%r10,%r10), %r8d
-	addl	$2, %r8d
+	leal	(%r10,%r10), %edx
+	addl	$2, %edx
+	movq	%rdx, -80(%rbp)
 	leal	4(,%r10,4), %r14d
 	leal	1(%r10), %r11d
-	leal	(%r10,%r10,2), %ebx
-	addl	$3, %ebx
+	leal	(%r10,%r10,2), %r8d
+	addl	$3, %r8d
 	xorl	%edx, %edx
-	movq	-96(%rbp), %rax
-	nopl	(%rax)
+	movabsq	$4607182418800017408, %r12
+	nopl	(%rax,%rax)
 	movslq	%esi, %rsi
-	movq	%r12, (%rax,%rsi,8)
+	movq	%rax, (%rbx,%rsi,8)
 	leal	(%r11,%rsi), %edi
 	movslq	%edi, %rdi
+	movq	-56(%rbp), %rax
 	movq	%r12, (%rax,%rdi,8)
-	leal	(%r8,%rsi), %edi
+	movq	-80(%rbp), %rax
+	leal	(%rax,%rsi), %edi
 	movslq	%edi, %rdi
-	movq	%r12, (%rax,%rdi,8)
-	leal	(%rbx,%rsi), %edi
+	movq	-56(%rbp), %rax
+	movabsq	$4607182418800017408, %rbx
+	movq	%rbx, (%rax,%rdi,8)
+	leal	(%r8,%rsi), %edi
 	movslq	%edi, %rdi
-	movq	%r12, (%rax,%rdi,8)
+	movq	-56(%rbp), %rax
+	movabsq	$4607182418800017408, %rbx
+	movq	%rbx, (%rax,%rdi,8)
+	movabsq	$4607182418800017408, %rax
+	movq	-56(%rbp), %rbx
 	addq	$4, %rdx
 	addl	%r14d, %esi
 	cmpq	%rdx, %r9
-	jne	0x11910
+	jne	0x115d0
 	testq	%rcx, %rcx
-	movl	-80(%rbp), %r14d
-	je	0x1196f
+	je	0x1165e
 	leal	1(%r10), %esi
 	imull	%esi, %edx
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
 	movslq	%edx, %rdx
-	movq	%r12, (%rax,%rdx,8)
+	movq	%rax, (%rbx,%rdx,8)
 	addl	%esi, %edx
-	addq	$-1, %rcx
-	jne	0x11960
+	decq	%rcx
+	jne	0x11650
 	movl	40(%rbp), %eax
 	testl	%eax, %eax
-	movq	-120(%rbp), %r11
-	movq	%r15, -160(%rbp)
-	jle	0x11adc
+	movl	104(%rbp), %r11d
+	movq	48(%rbp), %rcx
+	movq	%r15, -168(%rbp)
+	jle	0x117c1
 	movl	%eax, %eax
-	movq	%rax, -200(%rbp)
-	addq	$-1, %rax
-	movq	%rax, -112(%rbp)
+	movq	%rax, -224(%rbp)
+	decq	%rax
+	movq	%rax, -80(%rbp)
 	xorl	%ebx, %ebx
-	movq	48(%rbp), %rcx
-	movq	%r10, %r15
-	nop
+	movq	%r11, %r15
+	nopl	(%rax)
 	movq	32(%rbp), %rax
 	movsd	(%rax,%rbx,8), %xmm0
-	movl	56(%rbp), %r10d
+	movl	56(%rbp), %r14d
 	subq	$8, %rsp
-	movq	-88(%rbp), %rdi
+	movq	-120(%rbp), %rdi
 	movq	-144(%rbp), %rsi
 	movl	88(%rbp), %edx
-	movq	-160(%rbp), %r8
+	movq	-168(%rbp), %r8
 	movl	$500, %r9d
-	pushq	-168(%rbp)
-	pushq	-176(%rbp)
-	movq	80(%rbp), %r14
-	pushq	%r14
-	leaq	-288(%rbp), %rax
-	pushq	%rax
+	pushq	-184(%rbp)
+	pushq	-192(%rbp)
+	movq	80(%rbp), %r12
+	pushq	%r12
+	leaq	-280(%rbp), %r11
+	pushq	%r11
 	pushq	-136(%rbp)
 	pushq	%rbx
-	leaq	-280(%rbp), %rax
+	leaq	-272(%rbp), %rax
 	pushq	%rax
-	pushq	-56(%rbp)
-	movl	96(%rbp), %r12d
-	pushq	%r12
+	pushq	-104(%rbp)
+	pushq	%r15
 	pushq	$31
+	pushq	%r14
+	pushq	-112(%rbp)
 	pushq	%r10
-	pushq	%r11
-	pushq	%r15
 	callq	_cv_gene_nets_support_adaENcv
 	addq	$112, %rsp
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
-	movq	-192(%rbp), %rax
+	movq	-216(%rbp), %rax
 	movsd	%xmm0, (%rax,%rbx,8)
 	movl	56(%rbp), %eax
 	imull	%ebx, %eax
 	cltq
 	movq	64(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
-	leaq	56(%rbp), %r15
-	movq	%r15, %rdi
-	movq	%r14, %rsi
-	leaq	-68(%rbp), %r12
-	movq	%r12, %rdx
-	leaq	-64(%rbp), %r14
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	leaq	56(%rbp), %r14
+	movq	%r14, %rdi
+	movq	%r12, %rsi
+	leaq	-68(%rbp), %r15
+	movq	%r15, %rdx
+	leaq	-64(%rbp), %r12
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
 	movslq	56(%rbp), %rax
 	movq	80(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rsi
 	imull	%ebx, %eax
 	cltq
 	movq	72(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
-	movq	%r15, %rdi
-	movq	%r12, %rdx
-	movq	%r14, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	-112(%rbp), %rdi
-	cmpq	%rbx, %rdi
-	je	0x11a94
-	movl	-44(%rbp), %r15d
-	addq	$1, %rbx
-	movq	-120(%rbp), %r11
+	movq	%r14, %rdi
+	movq	%r15, %rdx
+	movq	%r12, %r8
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	-80(%rbp), %rsi
+	cmpq	%rbx, %rsi
+	je	0x11781
+	movl	-44(%rbp), %r10d
+	incq	%rbx
+	movl	104(%rbp), %r15d
 	movq	48(%rbp), %rcx
-	jmp	0x119a0
+	jmp	0x11690
 	xorl	%eax, %eax
 	movl	40(%rbp), %ecx
 	cmpl	$2, %ecx
-	movq	-136(%rbp), %rbx
-	movl	-80(%rbp), %r14d
-	jl	0x11c45
-	movsd	(%rbx), %xmm0
-	movq	-200(%rbp), %rax
+	movl	104(%rbp), %r11d
+	movq	-136(%rbp), %r12
+	jl	0x11929
+	movsd	(%r12), %xmm0
+	movq	-224(%rbp), %rax
 	addq	$-2, %rax
-	movl	%edi, %ecx
-	andl	$3, %ecx
+	movl	%esi, %r9d
+	andl	$3, %r9d
 	cmpq	$3, %rax
-	jae	0x11ae3
+	jae	0x117c8
 	xorl	%eax, %eax
 	movl	$1, %edx
-	testq	%rcx, %rcx
-	jne	0x11b60
-	jmp	0x11b7e
+	jmp	0x1183d
 	xorl	%eax, %eax
-	jmp	0x11c45
-	andq	$-4, %rdi
-	xorl	%edx, %edx
+	jmp	0x11929
+	andq	$-4, %rsi
 	xorl	%eax, %eax
-	nopl	(%rax,%rax)
-	movsd	8(%rbx,%rdx,8), %xmm1
+	movl	$1, %edx
+	xorl	%ecx, %ecx
+	nopw	%cs:(%rax,%rax)
+	movsd	(%r12,%rdx,8), %xmm1
 	ucomisd	%xmm1, %xmm0
-	leal	1(%rdx), %esi
-	cmovbel	%eax, %esi
-	movsd	16(%rbx,%rdx,8), %xmm2
+	cmoval	%edx, %eax
+	movsd	8(%r12,%rdx,8), %xmm2
 	minsd	%xmm0, %xmm1
 	ucomisd	%xmm2, %xmm1
-	leal	2(%rdx), %eax
-	cmovbel	%esi, %eax
+	leal	1(%rdx), %edi
+	cmovbel	%eax, %edi
 	minsd	%xmm1, %xmm2
-	movsd	24(%rbx,%rdx,8), %xmm1
+	movsd	16(%r12,%rdx,8), %xmm1
 	ucomisd	%xmm1, %xmm2
-	leal	3(%rdx), %esi
-	cmovbel	%eax, %esi
+	leal	2(%rdx), %ebx
+	cmovbel	%edi, %ebx
 	minsd	%xmm2, %xmm1
-	movsd	32(%rbx,%rdx,8), %xmm0
+	movsd	24(%r12,%rdx,8), %xmm0
 	ucomisd	%xmm0, %xmm1
-	leal	4(%rdx), %eax
-	cmovbel	%esi, %eax
+	leal	3(%rdx), %eax
+	cmovbel	%ebx, %eax
 	minsd	%xmm1, %xmm0
 	addq	$4, %rdx
-	cmpq	%rdx, %rdi
-	jne	0x11af0
-	addq	$1, %rdx
-	testq	%rcx, %rcx
-	je	0x11b7e
+	addq	$4, %rcx
+	cmpq	%rsi, %rcx
+	jne	0x117e0
+	testq	%r9, %r9
+	je	0x1186d
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	movsd	(%rbx,%rdx,8), %xmm1
+	movsd	(%r12,%rdx,8), %xmm1
 	ucomisd	%xmm1, %xmm0
 	cmoval	%edx, %eax
 	minsd	%xmm0, %xmm1
-	addq	$1, %rdx
+	incq	%rdx
 	movapd	%xmm1, %xmm0
-	addq	$-1, %rcx
-	jne	0x11b60
+	decq	%r9
+	jne	0x11850
 	movl	%eax, %edx
-	addl	$-1, %edx
-	js	0x11c45
+	decl	%edx
+	js	0x11929
 	movslq	%eax, %rcx
-	movq	-176(%rbp), %rsi
+	movq	-192(%rbp), %rsi
 	movsd	(%rsi,%rcx,8), %xmm0
-	movq	-168(%rbp), %rsi
+	movq	-184(%rbp), %rsi
 	addsd	(%rsi,%rcx,8), %xmm0
 	movl	%eax, %esi
 	andl	$3, %esi
-	je	0x11be1
+	je	0x118c0
 	xorpd	%xmm1, %xmm1
 	movl	%edx, %ecx
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
+	nop
 	movl	%ecx, %edi
-	movsd	(%rbx,%rdi,8), %xmm2
+	movsd	(%r12,%rdi,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%ecx, %eax
-	addl	$-1, %ecx
-	addl	$-1, %esi
-	jne	0x11bc0
+	decl	%ecx
+	decl	%esi
+	jne	0x118a0
 	cmpl	$3, %edx
-	jae	0x11be8
-	jmp	0x11c45
+	jae	0x118c7
+	jmp	0x11929
 	movl	%edx, %ecx
 	cmpl	$3, %edx
-	jb	0x11c45
+	jb	0x11929
 	xorpd	%xmm1, %xmm1
-	nopl	(%rax)
+	nopl	(%rax,%rax)
 	movl	%ecx, %edx
-	movsd	(%rbx,%rdx,8), %xmm2
+	movsd	(%r12,%rdx,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%ecx, %eax
 	leal	-1(%rcx), %edx
-	movsd	(%rbx,%rdx,8), %xmm2
+	movsd	(%r12,%rdx,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%edx, %eax
 	leal	-2(%rcx), %edx
-	movsd	(%rbx,%rdx,8), %xmm2
+	movsd	(%r12,%rdx,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%edx, %eax
 	leal	-3(%rcx), %edx
-	movsd	(%rbx,%rdx,8), %xmm2
+	movsd	(%r12,%rdx,8), %xmm2
 	subsd	%xmm0, %xmm2
 	ucomisd	%xmm2, %xmm1
 	cmovael	%edx, %eax
 	leal	-4(%rcx), %edx
 	cmpl	$3, %ecx
 	movl	%edx, %ecx
-	jg	0x11bf0
+	jg	0x118d0
 	cltq
-	movq	-192(%rbp), %rcx
+	movq	-216(%rbp), %rcx
 	cvttsd2si	(%rcx,%rax,8), %ecx
-	movq	%rcx, -184(%rbp)
+	movq	%rcx, -200(%rbp)
 	movq	32(%rbp), %rcx
 	movsd	(%rcx,%rax,8), %xmm0
-	movsd	%xmm0, -104(%rbp)
-	movl	96(%rbp), %r12d
-	testl	%r12d, %r12d
-	jne	0x11ca1
-	leaq	8631(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV, alpha: %f.\n"
+	movsd	%xmm0, -88(%rbp)
+	testl	%r11d, %r11d
+	jne	0x11981
+	leaq	9401(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV, alpha: %f.\n"
 	movl	88(%rbp), %esi
-	movsd	-104(%rbp), %xmm0
+	movsd	-88(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	leaq	8646(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
-	movsd	-104(%rbp), %xmm0
-	movq	-184(%rbp), %rsi
+	callq	0x133c4 ## symbol stub for: _printf
+	leaq	9416(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
+	movsd	-88(%rbp), %xmm0
+	movq	-200(%rbp), %rsi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movslq	-44(%rbp), %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -152(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -160(%rbp)
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
-	movslq	%r14d, %rbx
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -152(%rbp)
+	movslq	-96(%rbp), %rbx
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r14
 	movl	$8, %esi
 	movq	%rbx, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r15
-	leaq	-204(%rbp), %rbx
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %rbx
+	leaq	-124(%rbp), %rdi
 	leaq	-68(%rbp), %rdx
 	leaq	-64(%rbp), %r8
-	movq	%rbx, %rdi
 	movq	-144(%rbp), %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%rbx, %rdi
-	movq	-88(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-124(%rbp), %rdi
+	movq	-120(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
 	movq	%r14, %rcx
 	leaq	-64(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r8d
 	movq	%r14, %rdi
-	movq	%r15, %rsi
-	movq	-152(%rbp), %rdx
-	movq	%r12, -216(%rbp)
-	movq	%r12, %rcx
-	movq	-120(%rbp), %rbx
-	movl	%ebx, %r9d
+	movq	%r14, -208(%rbp)
+	movq	%rbx, %rsi
+	movq	-160(%rbp), %rdx
+	movq	-152(%rbp), %rcx
+	movq	-112(%rbp), %r9
 	callq	_centerYX
 	movslq	-60(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movsd	-280(%rbp), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movsd	-272(%rbp), %xmm0
 	movl	-44(%rbp), %ecx
 	movq	%r14, %rdi
-	movq	%r15, %rsi
-	movq	%rax, -112(%rbp)
+	movq	%rbx, %rsi
+	movq	%rax, -176(%rbp)
 	movq	%rax, %rdx
 	movsd	%xmm0, -80(%rbp)
-	movl	%ebx, %r8d
+	movq	-112(%rbp), %r14
+	movl	%r14d, %r8d
 	callq	_QlambdaStart
 	movl	-44(%rbp), %ecx
-	movq	%r14, -248(%rbp)
-	movq	%r14, %rdi
-	movq	%r15, -240(%rbp)
-	movq	%r15, %rsi
-	movq	-56(%rbp), %rdx
-	movl	%ebx, %r8d
-	movsd	-104(%rbp), %xmm0
+	movq	-208(%rbp), %rdi
+	movq	%rbx, -248(%rbp)
+	movq	%rbx, %rsi
+	movq	-104(%rbp), %rdx
+	movl	%r14d, %r8d
+	movsd	-88(%rbp), %xmm0
 	callq	_lambdaMax_adaEN
-	movsd	%xmm0, -232(%rbp)
-	movl	96(%rbp), %r15d
-	testl	%r15d, %r15d
-	jne	0x11dc3
-	leaq	8555(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
-	callq	0x13556 ## symbol stub for: _puts
-	movq	-184(%rbp), %rcx
-	testl	%ecx, %ecx
-	movq	48(%rbp), %rax
-	jle	0x11f39
-	movsd	6226(%rip), %xmm1
+	movsd	%xmm0, -240(%rbp)
+	movl	104(%rbp), %r11d
+	testl	%r11d, %r11d
+	jne	0x11aac
+	leaq	9356(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
+	callq	0x133d0 ## symbol stub for: _puts
+	movl	104(%rbp), %r11d
+	movq	-200(%rbp), %rdx
+	testl	%edx, %edx
+	jle	0x11c28
+	movsd	6621(%rip), %xmm1
 	xorl	%ebx, %ebx
-	jmp	0x11ecd
+	movq	-120(%rbp), %rcx
+	movq	48(%rbp), %r14
+	jmp	0x11bbd
 	nopw	%cs:(%rax,%rax)
-	nop
-	leaq	8080(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
+	leaq	8496(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
 	movl	%ebx, %esi
-	movq	%rcx, %rdx
-	movsd	%xmm0, -264(%rbp)
 	movb	$1, %al
-	movsd	%xmm1, -200(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
+	movq	%r11, %r12
+	movq	%rcx, %r14
+	movsd	%xmm1, -224(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
-	movq	-56(%rbp), %rdi
+	movq	-104(%rbp), %rdi
 	movq	%r13, %rsi
-	movq	%r12, %rdx
-	movq	-88(%rbp), %rcx
+	movq	16(%rbp), %rdx
+	movq	%r14, %rcx
 	movq	-144(%rbp), %r8
-	movq	%r14, %r9
-	movsd	-264(%rbp), %xmm0
-	movsd	-200(%rbp), %xmm1
+	movq	-176(%rbp), %r15
+	movq	%r15, %r9
+	movsd	-96(%rbp), %xmm0
+	movsd	-224(%rbp), %xmm1
 	movsd	-80(%rbp), %xmm2
-	movsd	-232(%rbp), %xmm3
-	movsd	-104(%rbp), %xmm4
-	movq	-96(%rbp), %r14
+	movsd	-240(%rbp), %xmm3
+	movq	-88(%rbp), %xmm4
+	movq	-56(%rbp), %r14
 	pushq	%r14
-	pushq	%r15
-	movq	%r12, %r15
-	movq	-120(%rbp), %r12
+	pushq	%r12
+	movq	-112(%rbp), %r12
 	pushq	%r12
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	addq	$48, %rsp
-	leaq	7983(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
+	leaq	8403(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movl	-44(%rbp), %r9d
-	movq	-248(%rbp), %rdi
-	movq	-240(%rbp), %rsi
-	movq	-112(%rbp), %rdx
+	movq	-208(%rbp), %rdi
+	movq	-248(%rbp), %rsi
+	movq	%r15, %rdx
 	movq	%r13, %rcx
-	movq	%r15, %r8
+	movq	16(%rbp), %r8
 	movsd	-80(%rbp), %xmm0
 	pushq	%r14
 	pushq	%r12
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	movq	48(%rbp), %rax
-	movsd	(%rax,%rbx,8), %xmm1
-	addq	$1, %rbx
-	movq	-184(%rbp), %rcx
-	cmpq	%rbx, %rcx
-	movl	96(%rbp), %r15d
-	je	0x11f39
-	movsd	(%rax,%rbx,8), %xmm0
-	testl	%r15d, %r15d
-	movq	16(%rbp), %r12
-	movq	-112(%rbp), %r14
-	jg	0x11df0
+	movq	48(%rbp), %r14
+	movsd	(%r14,%rbx,8), %xmm1
+	incq	%rbx
+	movq	-200(%rbp), %rdx
+	cmpq	%rbx, %rdx
+	movq	-120(%rbp), %rcx
+	movl	104(%rbp), %r11d
+	je	0x11c28
+	movsd	(%r14,%rbx,8), %xmm0
+	testl	%r11d, %r11d
+	movsd	%xmm0, -96(%rbp)
+	jg	0x11ae0
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
-	movq	-56(%rbp), %rdi
+	movq	-104(%rbp), %rdi
 	movq	%r13, %rsi
-	movq	%r12, %rdx
-	movq	-88(%rbp), %rcx
+	movq	16(%rbp), %rdx
 	movq	-144(%rbp), %r8
-	movq	%r14, %r9
+	movq	-176(%rbp), %r15
+	movq	%r15, %r9
 	movsd	-80(%rbp), %xmm2
-	movsd	-232(%rbp), %xmm3
-	movsd	-104(%rbp), %xmm4
-	movq	-96(%rbp), %r14
+	movsd	-240(%rbp), %xmm3
+	movq	-88(%rbp), %xmm4
+	movq	-56(%rbp), %r14
 	pushq	%r14
-	pushq	%r15
-	movq	%r12, %r15
-	movq	-120(%rbp), %r12
+	pushq	%r11
+	movq	-112(%rbp), %r12
 	pushq	%r12
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	addq	$48, %rsp
-	jmp	0x11e82
+	jmp	0x11b6e
+	movq	96(%rbp), %rax
+	movsd	-88(%rbp), %xmm0
+	movsd	%xmm0, (%rax)
+	movsd	-96(%rbp), %xmm0
+	movsd	%xmm0, 8(%rax)
 	movq	24(%rbp), %r10
 	movq	$0, (%r10)
 	xorpd	%xmm0, %xmm0
 	movupd	%xmm0, 16(%r10)
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
-	jle	0x12032
+	jle	0x11d2a
 	leaq	16(%r10), %r9
 	movq	%rax, %rdx
 	negq	%rdx
 	xorpd	%xmm2, %xmm2
 	xorl	%esi, %esi
-	movsd	5823(%rip), %xmm3
-	xorpd	%xmm0, %xmm0
+	movsd	6185(%rip), %xmm3
 	xorpd	%xmm1, %xmm1
-	xorpd	%xmm4, %xmm4
+	pxor	%xmm4, %xmm4
+	xorpd	%xmm0, %xmm0
 	xorl	%r8d, %r8d
-	movq	-160(%rbp), %r15
-	movq	-224(%rbp), %r14
-	movq	-152(%rbp), %r12
-	jmp	0x11fad
-	nopw	(%rax,%rax)
-	addq	$1, %r8
-	addq	$-1, %rsi
+	movq	-168(%rbp), %r15
+	movq	-136(%rbp), %r12
+	movq	-232(%rbp), %r14
+	jmp	0x11cab
+	nopl	(%rax)
+	incq	%r8
+	decq	%rsi
 	cmpq	%rax, %r8
-	je	0x12025
+	je	0x11d24
 	movl	%r8d, %ebx
 	xorl	%edi, %edi
-	jmp	0x11fcb
+	jmp	0x11cca
 	nopw	%cs:(%rax,%rax)
-	nop
-	addq	$-1, %rdi
+	decq	%rdi
 	addl	%eax, %ebx
 	cmpq	%rdi, %rdx
-	je	0x11fa0
+	je	0x11ca0
 	movslq	%ebx, %rcx
 	movsd	(%r14,%rcx,8), %xmm5
 	ucomisd	%xmm2, %xmm5
-	jne	0x11ff4
-	jp	0x11ff4
+	jne	0x11cf3
+	jp	0x11cf3
 	movsd	(%r13,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0x11feb
-	jnp	0x11ff4
-	addsd	%xmm3, %xmm4
-	movsd	%xmm4, (%r9)
+	jne	0x11cea
+	jnp	0x11cf3
+	addsd	%xmm3, %xmm0
+	movsd	%xmm0, (%r9)
 	cmpq	%rdi, %rsi
-	je	0x11fc0
+	je	0x11cc0
 	movsd	(%r13,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0x12008
-	jnp	0x11fc0
-	addsd	%xmm3, %xmm1
-	movsd	%xmm1, 24(%r10)
+	jne	0x11d07
+	jnp	0x11cc0
+	addsd	%xmm3, %xmm4
+	movsd	%xmm4, 24(%r10)
 	ucomisd	%xmm2, %xmm5
-	jne	0x1201a
-	jnp	0x11fc0
-	addsd	%xmm3, %xmm0
-	movsd	%xmm0, (%r10)
-	jmp	0x11fc0
-	unpcklpd	%xmm4, %xmm0
-	movq	-136(%rbp), %r13
-	jmp	0x12052
+	jne	0x11d19
+	jnp	0x11cc0
+	addsd	%xmm3, %xmm1
+	movsd	%xmm1, (%r10)
+	jmp	0x11cc0
+	divsd	%xmm4, %xmm0
+	jmp	0x11d4b
+	movsd	6174(%rip), %xmm0
 	xorpd	%xmm1, %xmm1
-	movq	-160(%rbp), %r15
-	movq	-136(%rbp), %r13
-	movq	-224(%rbp), %r14
-	movq	-152(%rbp), %r12
-	movq	-216(%rbp), %rbx
-	movsd	8(%r10), %xmm2
-	unpcklpd	%xmm1, %xmm2
-	divpd	%xmm2, %xmm0
-	movupd	%xmm0, 32(%r10)
-	movl	96(%rbp), %eax
-	testl	%eax, %eax
-	jne	0x12080
-	leaq	7884(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
-	callq	0x13556 ## symbol stub for: _puts
+	movq	-168(%rbp), %r15
+	movq	-136(%rbp), %r12
+	movq	-232(%rbp), %r14
+	movq	-160(%rbp), %rbx
+	movq	-152(%rbp), %r13
+	divsd	8(%r10), %xmm1
+	movsd	%xmm1, 32(%r10)
+	movsd	%xmm0, 40(%r10)
+	testl	%r11d, %r11d
+	jne	0x11d7c
+	leaq	8662(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
+	callq	0x133d0 ## symbol stub for: _puts
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r13, %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r15, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-208(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-248(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-240(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-104(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-56(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-96(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-112(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	%r13, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-168(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r12, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-216(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-192(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-184(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	addq	$248, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 _mainSML_adaENpointLambda:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
 	subq	$248, %rsp
-	movq	%r9, %r13
-	movq	%r8, %r15
-	movl	%edx, %r12d
-	movq	%rsi, -128(%rbp)
-	movq	%rdi, -88(%rbp)
+	movq	%r9, %r12
+	movq	%r8, -56(%rbp)
+	movl	%edx, %r15d
+	movq	%rsi, -120(%rbp)
+	movq	%rdi, -96(%rbp)
 	movq	24(%rbp), %rbx
 	movl	%edx, -44(%rbp)
 	movl	$1, -68(%rbp)
 	movl	$1, -64(%rbp)
-	movl	$0, -120(%rbp)
-	movq	%rcx, -104(%rbp)
+	movl	$0, -84(%rbp)
+	movq	%rcx, -224(%rbp)
 	movl	%ecx, %eax
 	imull	%edx, %eax
 	movl	%eax, -80(%rbp)
-	movl	%eax, -116(%rbp)
+	movl	%eax, -108(%rbp)
 	movl	%edx, %eax
 	imull	%edx, %eax
 	movl	%eax, -60(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r14
 	leaq	-60(%rbp), %rdi
 	leaq	-68(%rbp), %rdx
 	leaq	-64(%rbp), %r8
-	movq	%r13, %rsi
-	movq	%rax, -160(%rbp)
+	movq	%r12, %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, 8(%rbx)
-	testl	%r12d, %r12d
-	jle	0x122a1
+	testl	%r15d, %r15d
+	jle	0x11fa0
 	movq	%rbx, %r10
-	movl	%r12d, %r8d
+	movl	%r15d, %r8d
 	movl	%r8d, %r9d
 	andl	$-2, %r9d
-	leal	(%r12,%r12), %edx
+	leal	(%r15,%r15), %edx
 	xorpd	%xmm0, %xmm0
-	xorl	%esi, %esi
-	movsd	5213(%rip), %xmm1
+	xorl	%ebx, %ebx
+	movsd	5597(%rip), %xmm1
 	xorpd	%xmm2, %xmm2
-	jmp	0x121ed
+	jmp	0x11edc
 	nopl	(%rax)
-	addq	$1, %rsi
-	cmpq	%r8, %rsi
-	je	0x122a1
-	cmpl	$1, %r12d
-	jne	0x12230
-	xorl	%ebx, %ebx
+	incq	%rbx
+	cmpq	%r8, %rbx
+	je	0x11fa0
+	cmpl	$1, %r15d
+	jne	0x11ef0
+	xorl	%eax, %eax
 	testb	$1, %r8b
-	je	0x121e0
-	cmpq	%rbx, %rsi
-	je	0x121e0
-	imull	%r12d, %ebx
-	addl	%esi, %ebx
-	movslq	%ebx, %rax
-	movsd	(%r13,%rax,8), %xmm3
+	je	0x11ed0
+	jmp	0x11f6e
+	nop
+	movl	%ebx, %esi
+	xorl	%edi, %edi
+	jmp	0x11f0a
+	nopw	%cs:(%rax,%rax)
+	addl	%edx, %esi
+	incq	%rdi
+	cmpq	%r9, %rdi
+	je	0x11f60
+	movq	%rdi, %rax
+	cmpq	%rdi, %rbx
+	je	0x11f2d
+	movslq	%esi, %rdi
+	movsd	(%r12,%rdi,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x12218
-	jnp	0x121e0
+	jne	0x11f23
+	jnp	0x11f2d
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r10)
-	jmp	0x121e0
-	nopw	%cs:(%rax,%rax)
-	nop
-	movl	%esi, %edi
-	xorl	%ecx, %ecx
-	jmp	0x12255
-	nopw	%cs:(%rax,%rax)
-	movq	%rcx, %rbx
-	addq	$2, %rbx
-	addl	%edx, %edi
-	addq	$1, %rax
-	movq	%rax, %rcx
-	cmpq	%rbx, %r9
-	je	0x121f5
-	cmpq	%rcx, %rsi
-	je	0x12276
-	movslq	%edi, %rax
-	movsd	(%r13,%rax,8), %xmm3
+	leaq	1(%rax), %rdi
+	cmpq	%rdi, %rbx
+	je	0x11f00
+	leal	(%r15,%rsi), %ecx
+	movslq	%ecx, %rcx
+	movsd	(%r12,%rcx,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x1226c
-	jnp	0x12276
+	jne	0x11f4b
+	jnp	0x11f00
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r10)
-	leaq	1(%rcx), %rax
-	cmpq	%rax, %rsi
-	je	0x12240
-	leal	(%r12,%rdi), %ebx
-	movslq	%ebx, %rbx
-	movsd	(%r13,%rbx,8), %xmm3
+	jmp	0x11f00
+	nopw	(%rax,%rax)
+	addq	$2, %rax
+	testb	$1, %r8b
+	je	0x11ed0
+	cmpq	%rax, %rbx
+	je	0x11ed0
+	imull	%r15d, %eax
+	addl	%ebx, %eax
+	cltq
+	movsd	(%r12,%rax,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x12295
-	jnp	0x12240
+	jne	0x11f91
+	jnp	0x11ed0
 	addsd	%xmm1, %xmm2
 	movsd	%xmm2, 8(%r10)
-	jmp	0x12240
+	jmp	0x11ed0
 	movabsq	$4607182418800017408, %rax
-	movq	%rax, -216(%rbp)
+	movq	%rax, %r13
+	movq	%rax, -232(%rbp)
 	leaq	-44(%rbp), %rdi
-	leaq	-216(%rbp), %r12
-	leaq	-120(%rbp), %r14
+	leaq	-232(%rbp), %r15
+	leaq	-84(%rbp), %rdx
 	leaq	-68(%rbp), %rbx
-	movq	%r12, %rsi
-	movq	%r14, %rdx
+	movq	%r15, %rsi
 	movq	16(%rbp), %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	$0, -216(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	$0, -232(%rbp)
 	leaq	-60(%rbp), %rdi
-	movq	%r12, %rsi
-	movq	%r14, %rdx
-	movq	%r13, %rcx
+	movq	%r15, %rsi
+	leaq	-84(%rbp), %rdx
+	movq	%r12, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	cmpl	$0, -80(%rbp)
-	jle	0x12324
+	movq	-96(%rbp), %rdi
+	movq	-56(%rbp), %rbx
+	jle	0x12131
 	movl	-80(%rbp), %ecx
 	movl	%ecx, %eax
-	cmpl	$1, %ecx
-	jne	0x124da
+	cmpl	$4, %ecx
+	jb	0x12025
+	leaq	(%rbx,%rax,4), %rcx
+	cmpq	%rdi, %rcx
+	jbe	0x1207d
+	leaq	(%rdi,%rax,8), %rcx
+	cmpq	%rbx, %rcx
+	jbe	0x1207d
 	xorl	%ecx, %ecx
+	movq	%rcx, %rdx
+	notq	%rdx
 	testb	$1, %al
-	je	0x12324
-	cmpl	$1, (%r15,%rcx,4)
-	jne	0x12324
-	movq	-88(%rbp), %rax
-	movq	$0, (%rax,%rcx,8)
+	je	0x12043
+	cmpl	$1, (%rbx,%rcx,4)
+	jne	0x1203f
+	movq	$0, (%rdi,%rcx,8)
+	orq	$1, %rcx
+	addq	%rax, %rdx
+	jne	0x1205d
+	jmp	0x12131
+	nopl	(%rax)
+	addq	$2, %rcx
+	cmpq	%rcx, %rax
+	je	0x12131
+	cmpl	$1, (%rbx,%rcx,4)
+	jne	0x1206b
+	movq	$0, (%rdi,%rcx,8)
+	cmpl	$1, 4(%rbx,%rcx,4)
+	jne	0x12050
+	movq	$0, 8(%rdi,%rcx,8)
+	jmp	0x12050
+	movl	%eax, %ecx
+	andl	$-4, %ecx
+	xorl	%edx, %edx
+	movdqa	5348(%rip), %xmm0
+	movdqa	5356(%rip), %xmm1
+	jmp	0x120a9
+	nopw	%cs:(%rax,%rax)
+	addq	$4, %rdx
+	cmpq	%rdx, %rcx
+	je	0x12128
+	movq	(%rbx,%rdx,4), %xmm3
+	movq	8(%rbx,%rdx,4), %xmm2
+	movdqa	%xmm3, %xmm4
+	pcmpeqd	%xmm0, %xmm4
+	movd	%xmm4, %esi
+	testb	$1, %sil
+	je	0x120ce
+	movq	$0, (%rdi,%rdx,8)
+	pshufd	$212, %xmm3, %xmm3
+	pcmpeqd	%xmm1, %xmm3
+	pextrw	$4, %xmm3, %esi
+	testb	$1, %sil
+	je	0x120eb
+	movq	$0, 8(%rdi,%rdx,8)
+	movdqa	%xmm2, %xmm3
+	pcmpeqd	%xmm0, %xmm3
+	movd	%xmm3, %esi
+	testb	$1, %sil
+	je	0x12106
+	movq	$0, 16(%rdi,%rdx,8)
+	pshufd	$212, %xmm2, %xmm2
+	pcmpeqd	%xmm1, %xmm2
+	pextrw	$4, %xmm2, %esi
+	testb	$1, %sil
+	je	0x120a0
+	movq	$0, 24(%rdi,%rdx,8)
+	jmp	0x120a0
+	cmpq	%rax, %rcx
+	jne	0x12027
 	movl	$31, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -136(%rbp)
-	movsd	5006(%rip), %xmm1
-	movl	$3, %r15d
-	movq	-136(%rbp), %rbx
-	nop
-	movsd	4992(%rip), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r15
+	movsd	5093(%rip), %xmm1
+	movl	$3, %ebx
+	movsd	5088(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -24(%rbx,%r15,8)
-	movsd	4975(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -24(%r15,%rbx,8)
+	movsd	5071(%rip), %xmm0
 	movsd	-56(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	4945(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -16(%rbx,%r15,8)
+	movsd	5041(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -16(%r15,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	4928(%rip), %xmm1
-	movsd	4912(%rip), %xmm0
+	addsd	5024(%rip), %xmm1
+	movsd	5008(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -8(%rbx,%r15,8)
-	cmpq	$31, %r15
-	je	0x12405
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -8(%r15,%rbx,8)
+	cmpq	$31, %rbx
+	je	0x121fe
 	movsd	-56(%rbp), %xmm1
-	movsd	4884(%rip), %xmm0
+	movsd	4980(%rip), %xmm0
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	4859(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
-	movq	-136(%rbp), %rax
-	movsd	%xmm0, (%rax,%r15,8)
+	movsd	4955(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, (%r15,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	4836(%rip), %xmm1
-	addq	$4, %r15
-	jmp	0x12350
+	addsd	4939(%rip), %xmm1
+	addq	$4, %rbx
+	jmp	0x12150
+	movq	%r15, -152(%rbp)
 	movslq	40(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -208(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -216(%rbp)
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -152(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -160(%rbp)
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -200(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -208(%rbp)
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -192(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -200(%rbp)
 	movslq	-60(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, -56(%rbp)
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -96(%rbp)
-	movq	$0, -264(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %rbx
+	movq	$0, -272(%rbp)
 	leaq	-60(%rbp), %rdi
-	leaq	-264(%rbp), %rsi
-	leaq	-120(%rbp), %rdx
+	leaq	-272(%rbp), %rsi
+	leaq	-84(%rbp), %rdx
 	leaq	-64(%rbp), %r8
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movl	-44(%rbp), %r12d
-	testl	%r12d, %r12d
-	movabsq	$4607182418800017408, %rbx
-	jle	0x125bf
-	leaq	-1(%r12), %rdx
-	movl	%r12d, %ecx
+	callq	0x1337c ## symbol stub for: _dcopy
+	movl	-44(%rbp), %r10d
+	testl	%r10d, %r10d
+	jle	0x1234e
+	movq	%r13, %rdi
+	leaq	-1(%r10), %rdx
+	movl	%r10d, %ecx
 	andl	$3, %ecx
 	xorl	%esi, %esi
 	cmpq	$3, %rdx
-	jae	0x12527
+	jae	0x122ca
 	xorl	%edx, %edx
-	movq	-96(%rbp), %rax
-	jmp	0x12594
-	movl	%eax, %edx
-	andl	$-2, %edx
-	xorl	%ecx, %ecx
-	jmp	0x124fd
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	addq	$2, %rcx
-	cmpq	%rcx, %rdx
-	je	0x1230d
-	cmpl	$1, (%r15,%rcx,4)
-	jne	0x12510
-	movq	-88(%rbp), %rsi
-	movq	$0, (%rsi,%rcx,8)
-	cmpl	$1, 4(%r15,%rcx,4)
-	jne	0x124f0
-	movq	-88(%rbp), %rsi
-	movq	$0, 8(%rsi,%rcx,8)
-	jmp	0x124f0
-	movl	%r12d, %r9d
+	jmp	0x12326
+	movl	%r10d, %r9d
 	andl	$-4, %r9d
-	leal	(%r12,%r12), %r8d
+	leal	(%r10,%r10), %r8d
 	addl	$2, %r8d
-	leal	4(,%r12,4), %r10d
-	leal	1(%r12), %r11d
-	leal	(%r12,%r12,2), %r15d
-	addl	$3, %r15d
+	leal	4(,%r10,4), %r15d
+	leal	1(%r10), %r11d
+	leal	(%r10,%r10,2), %eax
+	addl	$3, %eax
 	xorl	%edx, %edx
-	movq	-96(%rbp), %rax
-	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
+	nop
 	movslq	%esi, %rsi
-	movq	%rbx, (%rax,%rsi,8)
+	movq	%rdi, (%rbx,%rsi,8)
 	leal	(%r11,%rsi), %edi
 	movslq	%edi, %rdi
-	movq	%rbx, (%rax,%rdi,8)
+	movq	%r13, (%rbx,%rdi,8)
 	leal	(%r8,%rsi), %edi
 	movslq	%edi, %rdi
-	movq	%rbx, (%rax,%rdi,8)
-	leal	(%r15,%rsi), %edi
+	movq	%r13, (%rbx,%rdi,8)
+	leal	(%rax,%rsi), %edi
 	movslq	%edi, %rdi
-	movq	%rbx, (%rax,%rdi,8)
+	movq	%r13, (%rbx,%rdi,8)
+	movq	%r13, %rdi
 	addq	$4, %rdx
-	addl	%r10d, %esi
+	addl	%r15d, %esi
 	cmpq	%rdx, %r9
-	jne	0x12560
+	jne	0x122f0
 	testq	%rcx, %rcx
-	je	0x125bf
-	leal	1(%r12), %esi
+	je	0x1234e
+	leal	1(%r10), %esi
 	imull	%esi, %edx
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax,%rax)
 	movslq	%edx, %rdx
-	movq	%rbx, (%rax,%rdx,8)
+	movq	%rdi, (%rbx,%rdx,8)
 	addl	%esi, %edx
-	addq	$-1, %rcx
-	jne	0x125b0
+	decq	%rcx
+	jne	0x12340
+	movq	%rbx, -144(%rbp)
 	movl	40(%rbp), %eax
 	testl	%eax, %eax
-	movl	72(%rbp), %r10d
-	jle	0x12673
+	movq	64(%rbp), %r13
+	jle	0x12402
 	movl	%eax, %r15d
-	addq	$-1, %r15
+	decq	%r15
 	xorl	%ebx, %ebx
-	nopw	(%rax,%rax)
+	nopl	(%rax)
+	movq	-96(%rbp), %rdi
+	movq	48(%rbp), %rcx
 	movq	32(%rbp), %rax
 	movsd	(%rax,%rbx,8), %xmm0
 	subq	$8, %rsp
-	movq	-88(%rbp), %rdi
-	movq	-128(%rbp), %rsi
+	movq	-120(%rbp), %rsi
 	movl	$5, %edx
-	movq	48(%rbp), %rcx
-	movq	-136(%rbp), %r8
+	movq	-152(%rbp), %r8
 	movl	$500, %r9d
-	pushq	-192(%rbp)
 	pushq	-200(%rbp)
-	pushq	64(%rbp)
-	leaq	-280(%rbp), %rax
-	pushq	%rax
 	pushq	-208(%rbp)
+	pushq	%r13
+	leaq	-288(%rbp), %rax
+	pushq	%rax
+	pushq	-216(%rbp)
 	pushq	%rbx
-	leaq	-272(%rbp), %rax
+	leaq	-280(%rbp), %rax
 	pushq	%rax
 	pushq	-56(%rbp)
-	pushq	%r10
+	movl	72(%rbp), %eax
+	pushq	%rax
 	pushq	$31
 	movl	56(%rbp), %eax
 	pushq	%rax
-	pushq	-104(%rbp)
-	pushq	%r12
+	pushq	-224(%rbp)
+	pushq	%r10
 	callq	_cv_gene_nets_support_adaENcv
-	movl	72(%rbp), %r10d
 	addq	$112, %rsp
 	xorps	%xmm0, %xmm0
 	cvtsi2sd	%eax, %xmm0
-	movq	-152(%rbp), %rax
+	movq	-160(%rbp), %rax
 	movsd	%xmm0, (%rax,%rbx,8)
 	cmpq	%rbx, %r15
-	je	0x12673
-	movl	-44(%rbp), %r12d
-	addq	$1, %rbx
-	jmp	0x125e0
+	je	0x12402
+	movl	-44(%rbp), %r10d
+	incq	%rbx
+	jmp	0x12370
 	movq	32(%rbp), %rax
 	movsd	(%rax), %xmm0
-	movsd	%xmm0, -112(%rbp)
-	testl	%r10d, %r10d
-	jne	0x126bf
-	movq	-152(%rbp), %rax
+	movsd	%xmm0, -104(%rbp)
+	movl	72(%rbp), %ebx
+	testl	%ebx, %ebx
+	jne	0x12450
+	movq	-160(%rbp), %rax
 	cvttsd2si	(%rax), %r15d
-	leaq	6039(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV, alpha: %f.\n"
+	leaq	6632(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV, alpha: %f.\n"
 	movl	$5, %esi
-	movsd	-112(%rbp), %xmm0
+	movsd	-104(%rbp), %xmm0
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	leaq	6052(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
-	movsd	-112(%rbp), %xmm0
+	callq	0x133c4 ## symbol stub for: _printf
+	leaq	6645(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
+	movsd	-104(%rbp), %xmm0
 	movl	%r15d, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movslq	-44(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r14
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -128(%rbp)
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %rbx
 	movslq	-80(%rbp), %r15
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r13
 	movl	$8, %esi
 	movq	%r15, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
+	callq	0x1336a ## symbol stub for: _calloc
 	movq	%rax, %r15
-	leaq	-116(%rbp), %rdi
+	leaq	-108(%rbp), %rdi
 	leaq	-68(%rbp), %rdx
 	leaq	-64(%rbp), %r8
-	movq	-128(%rbp), %rsi
+	movq	-120(%rbp), %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	leaq	-116(%rbp), %rdi
-	movq	-88(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-108(%rbp), %rdi
+	movq	-96(%rbp), %rsi
 	leaq	-68(%rbp), %rdx
-	movq	%r12, %rcx
+	movq	%r13, %rcx
 	leaq	-64(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r8d
-	movq	%r12, %rdi
+	movq	%r13, %rdi
 	movq	%r15, %rsi
-	movq	%r14, -232(%rbp)
-	movq	%r14, %rdx
-	movq	%rbx, -224(%rbp)
+	movq	-128(%rbp), %rdx
+	movq	%rbx, -168(%rbp)
 	movq	%rbx, %rcx
-	movq	-104(%rbp), %rbx
+	movq	-224(%rbp), %rbx
 	movl	%ebx, %r9d
 	callq	_centerYX
 	movslq	-60(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movsd	-272(%rbp), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movsd	-280(%rbp), %xmm0
 	movl	-44(%rbp), %ecx
-	movq	%r12, %rdi
+	movq	%r13, %rdi
 	movq	%r15, %rsi
-	movq	%rax, -144(%rbp)
+	movq	%rax, -136(%rbp)
 	movq	%rax, %rdx
 	movsd	%xmm0, -80(%rbp)
 	movl	%ebx, %r8d
 	callq	_QlambdaStart
 	movl	-44(%rbp), %ecx
-	movq	%r12, -184(%rbp)
-	movq	%r12, %rdi
-	movq	%rbx, %r12
-	movq	%r15, -176(%rbp)
+	movq	%r13, -192(%rbp)
+	movq	%r13, %rdi
+	movq	%r15, -184(%rbp)
 	movq	%r15, %rsi
 	movq	-56(%rbp), %rdx
-	movl	%r12d, %r8d
-	movsd	-112(%rbp), %xmm0
+	movl	%ebx, %r8d
+	movsd	-104(%rbp), %xmm0
 	callq	_lambdaMax_adaEN
-	movsd	%xmm0, -168(%rbp)
-	movl	72(%rbp), %r11d
-	testl	%r11d, %r11d
-	movq	48(%rbp), %rbx
-	jne	0x127e7
-	leaq	5963(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
-	callq	0x13556 ## symbol stub for: _puts
-	movl	72(%rbp), %r11d
+	movsd	%xmm0, -176(%rbp)
+	movl	72(%rbp), %r10d
+	testl	%r10d, %r10d
+	jne	0x1256f
+	leaq	6601(%rip), %rdi ## literal pool for: "Step 4: lasso selection path."
+	callq	0x133d0 ## symbol stub for: _puts
+	movl	72(%rbp), %r10d
 	movl	56(%rbp), %eax
 	testl	%eax, %eax
-	movq	-96(%rbp), %r14
-	jle	0x1297d
+	movq	48(%rbp), %rcx
+	jle	0x1270f
 	movl	56(%rbp), %eax
 	movl	%eax, %eax
 	movq	%rax, -240(%rbp)
-	movsd	3622(%rip), %xmm1
+	movsd	3854(%rip), %xmm1
 	xorl	%r15d, %r15d
-	jmp	0x12906
+	movq	%r14, -248(%rbp)
+	jmp	0x1269b
 	nopw	%cs:(%rax,%rax)
-	nopl	(%rax)
-	leaq	5472(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
+	leaq	5728(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
 	movl	%r15d, %esi
 	movl	56(%rbp), %edx
-	movsd	%xmm0, -256(%rbp)
+	movsd	%xmm0, -264(%rbp)
 	movb	$1, %al
-	movsd	%xmm1, -248(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movl	-44(%rbp), %eax
+	movsd	%xmm1, -256(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-44(%rbp), %r10d
 	subq	$8, %rsp
 	movq	-56(%rbp), %rdi
-	movq	%r13, %rsi
-	movq	16(%rbp), %r14
-	movq	%r14, %rdx
-	movq	-88(%rbp), %rcx
-	movq	-128(%rbp), %r8
-	movq	-144(%rbp), %r12
-	movq	%r12, %r9
-	movsd	-256(%rbp), %xmm0
-	movsd	-248(%rbp), %xmm1
+	movq	%r12, %rsi
+	movq	%rbx, %r14
+	movq	16(%rbp), %rdx
+	movq	-96(%rbp), %rcx
+	movq	-120(%rbp), %r8
+	movq	-136(%rbp), %r13
+	movq	%r13, %r9
+	movsd	-264(%rbp), %xmm0
+	movsd	-256(%rbp), %xmm1
 	movsd	-80(%rbp), %xmm2
-	movsd	-168(%rbp), %xmm3
-	movsd	-112(%rbp), %xmm4
-	pushq	-96(%rbp)
-	movl	72(%rbp), %ebx
+	movsd	-176(%rbp), %xmm3
+	movq	-104(%rbp), %xmm4
+	movq	-144(%rbp), %rbx
 	pushq	%rbx
-	movq	48(%rbp), %rbx
-	pushq	-104(%rbp)
+	movl	72(%rbp), %eax
 	pushq	%rax
+	pushq	%r14
+	pushq	%r10
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	addq	$48, %rsp
-	leaq	5369(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
+	leaq	5623(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-80(%rbp), %xmm0
-	movq	%r12, %rdx
-	movq	-104(%rbp), %r10
-	movq	%r14, %r8
-	movq	-96(%rbp), %rax
+	movq	%r13, %rdx
+	movq	16(%rbp), %r8
 	movl	-44(%rbp), %r9d
-	movq	-184(%rbp), %rdi
-	movq	-176(%rbp), %rsi
-	movq	%r13, %rcx
-	movq	%rax, %r14
-	pushq	%rax
-	pushq	%r10
+	movq	-192(%rbp), %rdi
+	movq	-184(%rbp), %rsi
+	movq	%r12, %rcx
+	pushq	%rbx
+	pushq	%r14
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	movsd	(%rbx,%r15,8), %xmm1
-	addq	$1, %r15
+	movq	48(%rbp), %rcx
+	movsd	(%rcx,%r15,8), %xmm1
+	incq	%r15
 	cmpq	%r15, -240(%rbp)
-	movl	72(%rbp), %r11d
-	je	0x1297d
-	movsd	(%rbx,%r15,8), %xmm0
-	testl	%r11d, %r11d
-	jg	0x12820
+	movl	72(%rbp), %r10d
+	movq	%r14, %rbx
+	movq	-248(%rbp), %r14
+	je	0x1270f
+	movsd	(%rcx,%r15,8), %xmm0
+	testl	%r10d, %r10d
+	jg	0x125b0
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
 	movq	-56(%rbp), %rdi
-	movq	%r13, %rsi
+	movq	%r12, %rsi
+	movq	%rbx, %r14
 	movq	16(%rbp), %rdx
-	movq	-88(%rbp), %rcx
-	movq	-128(%rbp), %r8
-	movq	-144(%rbp), %r12
-	movq	%r12, %r9
+	movq	-96(%rbp), %rcx
+	movq	-120(%rbp), %r8
+	movq	-136(%rbp), %r13
+	movq	%r13, %r9
 	movsd	-80(%rbp), %xmm2
-	movsd	-168(%rbp), %xmm3
-	movsd	-112(%rbp), %xmm4
+	movsd	-176(%rbp), %xmm3
+	movq	-104(%rbp), %xmm4
+	movq	-144(%rbp), %rbx
+	pushq	%rbx
+	pushq	%r10
 	pushq	%r14
-	pushq	%r11
-	pushq	-104(%rbp)
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	movsd	-80(%rbp), %xmm0
-	movq	%r12, %rdx
+	movq	%r13, %rdx
 	movq	16(%rbp), %r8
-	movq	%r14, %rax
-	movq	-104(%rbp), %r10
-	movq	48(%rbp), %rbx
 	addq	$48, %rsp
-	jmp	0x128cb
-	movq	24(%rbp), %r10
-	movq	$0, (%r10)
+	jmp	0x12656
+	movq	24(%rbp), %r11
+	movq	$0, (%r11)
 	xorpd	%xmm0, %xmm0
-	movupd	%xmm0, 16(%r10)
+	movupd	%xmm0, 16(%r11)
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
-	jle	0x12a5f
-	leaq	16(%r10), %r9
+	jle	0x127e8
+	leaq	16(%r11), %r9
 	movq	%rax, %rdx
 	negq	%rdx
 	xorpd	%xmm2, %xmm2
 	xorl	%esi, %esi
-	movsd	3195(%rip), %xmm3
-	xorpd	%xmm0, %xmm0
+	movsd	3417(%rip), %xmm3
 	xorpd	%xmm1, %xmm1
-	xorpd	%xmm4, %xmm4
+	pxor	%xmm4, %xmm4
+	xorpd	%xmm0, %xmm0
 	xorl	%r8d, %r8d
-	movq	-160(%rbp), %r14
-	jmp	0x129dd
-	nopl	(%rax)
-	addq	$1, %r8
-	addq	$-1, %rsi
+	movq	-152(%rbp), %r15
+	jmp	0x1276b
+	nop
+	incq	%r8
+	decq	%rsi
 	cmpq	%rax, %r8
-	je	0x12a55
+	je	0x127e2
 	movl	%r8d, %ebx
 	xorl	%edi, %edi
-	jmp	0x129fb
+	jmp	0x1278a
 	nopw	%cs:(%rax,%rax)
-	nop
-	addq	$-1, %rdi
+	decq	%rdi
 	addl	%eax, %ebx
 	cmpq	%rdi, %rdx
-	je	0x129d0
+	je	0x12760
 	movslq	%ebx, %rcx
 	movsd	(%r14,%rcx,8), %xmm5
 	ucomisd	%xmm2, %xmm5
-	jne	0x12a24
-	jp	0x12a24
-	movsd	(%r13,%rcx,8), %xmm6
+	jne	0x127b2
+	jp	0x127b2
+	movsd	(%r12,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0x12a1b
-	jnp	0x12a24
-	addsd	%xmm3, %xmm4
-	movsd	%xmm4, (%r9)
+	jne	0x127a9
+	jnp	0x127b2
+	addsd	%xmm3, %xmm0
+	movsd	%xmm0, (%r9)
 	cmpq	%rdi, %rsi
-	je	0x129f0
-	movsd	(%r13,%rcx,8), %xmm6
+	je	0x12780
+	movsd	(%r12,%rcx,8), %xmm6
 	ucomisd	%xmm2, %xmm6
-	jne	0x12a38
-	jnp	0x129f0
-	addsd	%xmm3, %xmm1
-	movsd	%xmm1, 24(%r10)
+	jne	0x127c5
+	jnp	0x12780
+	addsd	%xmm3, %xmm4
+	movsd	%xmm4, 24(%r11)
 	ucomisd	%xmm2, %xmm5
-	jne	0x12a4a
-	jnp	0x129f0
-	addsd	%xmm3, %xmm0
-	movsd	%xmm0, (%r10)
-	jmp	0x129f0
-	unpcklpd	%xmm4, %xmm0
-	movq	-96(%rbp), %rbx
-	jmp	0x12a6d
+	jne	0x127d7
+	jnp	0x12780
+	addsd	%xmm3, %xmm1
+	movsd	%xmm1, (%r11)
+	jmp	0x12780
+	divsd	%xmm4, %xmm0
+	jmp	0x127fb
+	movsd	3424(%rip), %xmm0
 	xorpd	%xmm1, %xmm1
-	movq	%r14, %rbx
-	movq	-160(%rbp), %r14
-	movsd	8(%r10), %xmm2
-	unpcklpd	%xmm1, %xmm2
-	divpd	%xmm2, %xmm0
-	movupd	%xmm0, 32(%r10)
-	testl	%r11d, %r11d
-	jne	0x12a92
-	leaq	5306(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
-	callq	0x13556 ## symbol stub for: _puts
+	movq	-152(%rbp), %r15
+	movq	-128(%rbp), %rbx
+	movq	-168(%rbp), %r12
+	divsd	8(%r11), %xmm1
+	movsd	%xmm1, 32(%r11)
+	movsd	%xmm0, 40(%r11)
+	testl	%r10d, %r10d
+	jne	0x12829
+	leaq	5929(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
+	callq	0x133d0 ## symbol stub for: _puts
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-232(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-224(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-136(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%rbx, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r12, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r15, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-192(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-56(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	%rbx, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-144(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	-136(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-216(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-160(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-208(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-152(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	addq	$248, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
 	nopw	%cs:(%rax,%rax)
-	nop
 _mainSML_adaENstabilitySelection:
 	pushq	%rbp
 	movq	%rsp, %rbp
 	pushq	%r15
 	pushq	%r14
 	pushq	%r13
 	pushq	%r12
 	pushq	%rbx
-	subq	$232, %rsp
-	movq	%r9, %r15
-	movq	%r8, %r12
-	movq	%rsi, -128(%rbp)
-	movq	%rdi, -72(%rbp)
+	subq	$216, %rsp
+	movq	%r9, %r13
+	movq	%r8, %r15
+	movl	%edx, %r12d
+	movq	%rsi, -112(%rbp)
+	movq	%rdi, -96(%rbp)
 	movq	24(%rbp), %rbx
-	movq	72(%rbp), %rax
+	movl	%edx, -44(%rbp)
 	movl	$1, -64(%rbp)
 	movl	$1, -60(%rbp)
-	movl	$0, -84(%rbp)
-	movl	(%rdx), %r13d
-	movl	%r13d, -44(%rbp)
-	movl	(%rcx), %ecx
-	movl	(%rax), %eax
-	movq	%rax, -96(%rbp)
-	movq	%rcx, -104(%rbp)
+	movl	$0, -104(%rbp)
+	movq	%rcx, -120(%rbp)
 	movl	%ecx, %eax
-	imull	%r13d, %eax
-	movl	%eax, -80(%rbp)
-	movl	%eax, -164(%rbp)
-	movl	%r13d, %eax
-	imull	%r13d, %eax
+	imull	%edx, %eax
+	movl	%eax, -72(%rbp)
+	movl	%eax, -100(%rbp)
+	movl	%edx, %eax
+	imull	%edx, %eax
 	movl	%eax, -48(%rbp)
 	movslq	%eax, %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r14
+	callq	0x1336a ## symbol stub for: _calloc
 	leaq	-48(%rbp), %rdi
 	leaq	-64(%rbp), %rdx
 	leaq	-60(%rbp), %r8
-	movq	%r15, %rsi
+	movq	%r13, %rsi
+	movq	%rax, -200(%rbp)
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movq	$0, 8(%rbx)
-	testl	%r13d, %r13d
-	jle	0x12ccf
-	movq	%rbx, %r9
-	movl	%r13d, %r8d
-	andl	$-2, %r8d
-	leal	(%r13,%r13), %ecx
+	testl	%r12d, %r12d
+	jle	0x12a61
+	movq	%rbx, %r10
+	movl	%r12d, %r8d
+	movl	%r8d, %r9d
+	andl	$-2, %r9d
+	leal	(%r12,%r12), %edx
 	xorpd	%xmm0, %xmm0
-	xorl	%edx, %edx
-	movsd	2608(%rip), %xmm1
+	xorl	%ebx, %ebx
+	movsd	2845(%rip), %xmm1
 	xorpd	%xmm2, %xmm2
-	jmp	0x12c1d
-	nopw	%cs:(%rax,%rax)
-	addq	$1, %rdx
-	cmpq	%r13, %rdx
-	je	0x12ccf
-	cmpl	$1, %r13d
-	jne	0x12c60
-	xorl	%edi, %edi
-	testb	$1, %r13b
-	je	0x12c10
-	cmpq	%rdi, %rdx
-	je	0x12c10
-	imull	%r13d, %edi
-	addl	%edx, %edi
-	movslq	%edi, %rax
-	movsd	(%r15,%rax,8), %xmm3
-	ucomisd	%xmm0, %xmm3
-	jne	0x12c47
-	jnp	0x12c10
-	addsd	%xmm1, %xmm2
-	movsd	%xmm2, 8(%r9)
-	jmp	0x12c10
-	nopw	%cs:(%rax,%rax)
+	jmp	0x1299c
 	nopl	(%rax)
-	movl	%edx, %esi
+	incq	%rbx
+	cmpq	%r8, %rbx
+	je	0x12a61
+	cmpl	$1, %r12d
+	jne	0x129b0
 	xorl	%eax, %eax
-	jmp	0x12c85
+	testb	$1, %r8b
+	je	0x12990
+	jmp	0x12a2e
+	nop
+	movl	%ebx, %esi
+	xorl	%edi, %edi
+	jmp	0x129ca
 	nopw	%cs:(%rax,%rax)
-	movq	%rax, %rdi
-	addq	$2, %rdi
-	addl	%ecx, %esi
-	addq	$1, %rbx
-	movq	%rbx, %rax
-	cmpq	%rdi, %r8
-	je	0x12c25
-	cmpq	%rax, %rdx
-	je	0x12ca5
+	addl	%edx, %esi
+	incq	%rdi
+	cmpq	%r9, %rdi
+	je	0x12a20
+	movq	%rdi, %rax
+	cmpq	%rdi, %rbx
+	je	0x129ee
 	movslq	%esi, %rdi
-	movsd	(%r15,%rdi,8), %xmm3
+	movsd	(%r13,%rdi,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x12c9b
-	jnp	0x12ca5
+	jne	0x129e4
+	jnp	0x129ee
 	addsd	%xmm1, %xmm2
-	movsd	%xmm2, 8(%r9)
-	leaq	1(%rax), %rbx
-	cmpq	%rbx, %rdx
-	je	0x12c70
-	leal	(%rsi,%r13), %edi
-	movslq	%edi, %rdi
-	movsd	(%r15,%rdi,8), %xmm3
+	movsd	%xmm2, 8(%r10)
+	leaq	1(%rax), %rdi
+	cmpq	%rdi, %rbx
+	je	0x129c0
+	leal	(%r12,%rsi), %ecx
+	movslq	%ecx, %rcx
+	movsd	(%r13,%rcx,8), %xmm3
 	ucomisd	%xmm0, %xmm3
-	jne	0x12cc3
-	jnp	0x12c70
+	jne	0x12a0d
+	jnp	0x129c0
 	addsd	%xmm1, %xmm2
-	movsd	%xmm2, 8(%r9)
-	jmp	0x12c70
-	movabsq	$4607182418800017408, %r13
-	movq	%r13, -160(%rbp)
+	movsd	%xmm2, 8(%r10)
+	jmp	0x129c0
+	nopl	(%rax)
+	addq	$2, %rax
+	testb	$1, %r8b
+	je	0x12990
+	cmpq	%rax, %rbx
+	je	0x12990
+	imull	%r12d, %eax
+	addl	%ebx, %eax
+	cltq
+	movsd	(%r13,%rax,8), %xmm3
+	ucomisd	%xmm0, %xmm3
+	jne	0x12a52
+	jnp	0x12990
+	addsd	%xmm1, %xmm2
+	movsd	%xmm2, 8(%r10)
+	jmp	0x12990
+	movabsq	$4607182418800017408, %rax
+	movq	%rax, -208(%rbp)
 	leaq	-44(%rbp), %rdi
-	leaq	-160(%rbp), %rsi
-	leaq	-84(%rbp), %rdx
+	leaq	-208(%rbp), %r12
+	leaq	-104(%rbp), %r14
 	leaq	-64(%rbp), %rbx
+	movq	%r12, %rsi
+	movq	%r14, %rdx
 	movq	16(%rbp), %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	$0, -160(%rbp)
+	callq	0x1337c ## symbol stub for: _dcopy
+	movq	$0, -208(%rbp)
 	leaq	-48(%rbp), %rdi
-	leaq	-160(%rbp), %rsi
-	leaq	-84(%rbp), %rdx
-	movq	%r15, %rcx
+	movq	%r12, %rsi
+	movq	%r14, %rdx
+	movq	%r13, %rcx
 	movq	%rbx, %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	cmpl	$0, -80(%rbp)
-	jle	0x12d51
-	movl	-80(%rbp), %ecx
+	callq	0x1337c ## symbol stub for: _dcopy
+	cmpl	$0, -72(%rbp)
+	movq	-96(%rbp), %rdi
+	jle	0x12bf7
+	movl	-72(%rbp), %ecx
 	movl	%ecx, %eax
-	cmpl	$1, %ecx
-	jne	0x12edd
+	cmpl	$4, %ecx
+	jb	0x12ae1
+	leaq	(%r15,%rax,4), %rcx
+	cmpq	%rdi, %rcx
+	jbe	0x12b3f
+	leaq	(%rdi,%rax,8), %rcx
+	cmpq	%r15, %rcx
+	jbe	0x12b3f
 	xorl	%ecx, %ecx
+	movq	%rcx, %rdx
+	notq	%rdx
 	testb	$1, %al
-	je	0x12d51
-	cmpl	$1, (%r12,%rcx,4)
-	jne	0x12d51
-	movq	-72(%rbp), %rax
-	movq	$0, (%rax,%rcx,8)
+	je	0x12b00
+	cmpl	$1, (%r15,%rcx,4)
+	jne	0x12afc
+	movq	$0, (%rdi,%rcx,8)
+	orq	$1, %rcx
+	addq	%rax, %rdx
+	jne	0x12b1d
+	jmp	0x12bf7
+	nopw	(%rax,%rax)
+	addq	$2, %rcx
+	cmpq	%rcx, %rax
+	je	0x12bf7
+	cmpl	$1, (%r15,%rcx,4)
+	jne	0x12b2c
+	movq	$0, (%rdi,%rcx,8)
+	cmpl	$1, 4(%r15,%rcx,4)
+	jne	0x12b10
+	movq	$0, 8(%rdi,%rcx,8)
+	jmp	0x12b10
+	movl	%eax, %ecx
+	andl	$-4, %ecx
+	xorl	%edx, %edx
+	movdqa	2594(%rip), %xmm0
+	movdqa	2602(%rip), %xmm1
+	jmp	0x12b6d
+	nopl	(%rax,%rax)
+	addq	$4, %rdx
+	cmpq	%rdx, %rcx
+	je	0x12bee
+	movq	(%r15,%rdx,4), %xmm3
+	movq	8(%r15,%rdx,4), %xmm2
+	movdqa	%xmm3, %xmm4
+	pcmpeqd	%xmm0, %xmm4
+	movd	%xmm4, %esi
+	testb	$1, %sil
+	je	0x12b94
+	movq	$0, (%rdi,%rdx,8)
+	pshufd	$212, %xmm3, %xmm3
+	pcmpeqd	%xmm1, %xmm3
+	pextrw	$4, %xmm3, %esi
+	testb	$1, %sil
+	je	0x12bb1
+	movq	$0, 8(%rdi,%rdx,8)
+	movdqa	%xmm2, %xmm3
+	pcmpeqd	%xmm0, %xmm3
+	movd	%xmm3, %esi
+	testb	$1, %sil
+	je	0x12bcc
+	movq	$0, 16(%rdi,%rdx,8)
+	pshufd	$212, %xmm2, %xmm2
+	pcmpeqd	%xmm1, %xmm2
+	pextrw	$4, %xmm2, %esi
+	testb	$1, %sil
+	je	0x12b60
+	movq	$0, 24(%rdi,%rdx,8)
+	jmp	0x12b60
+	cmpq	%rax, %rcx
+	jne	0x12ae3
 	movl	$31, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r12
-	movsd	2405(%rip), %xmm1
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r15
+	movsd	2335(%rip), %xmm1
 	movl	$3, %ebx
-	movsd	2400(%rip), %xmm0
+	nopw	%cs:(%rax,%rax)
+	movsd	2320(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -24(%r12,%rbx,8)
-	movsd	2383(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -24(%r15,%rbx,8)
+	movsd	2303(%rip), %xmm0
 	movsd	-56(%rbp), %xmm1
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	2353(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -16(%r12,%rbx,8)
+	movsd	2273(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -16(%r15,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	2336(%rip), %xmm1
-	movsd	2320(%rip), %xmm0
+	addsd	2256(%rip), %xmm1
+	movsd	2240(%rip), %xmm0
 	movsd	%xmm1, -56(%rbp)
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, -8(%r12,%rbx,8)
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, -8(%r15,%rbx,8)
 	cmpq	$31, %rbx
-	je	0x12e1e
+	je	0x12cce
 	movsd	-56(%rbp), %xmm1
-	movsd	2292(%rip), %xmm0
+	movsd	2212(%rip), %xmm0
 	addsd	%xmm0, %xmm1
 	movsd	%xmm1, -56(%rbp)
-	movsd	2267(%rip), %xmm0
-	callq	0x13544 ## symbol stub for: _pow
-	movsd	%xmm0, (%r12,%rbx,8)
+	movsd	2187(%rip), %xmm0
+	callq	0x133be ## symbol stub for: _pow
+	movsd	%xmm0, (%r15,%rbx,8)
 	movsd	-56(%rbp), %xmm1
-	addsd	2251(%rip), %xmm1
+	addsd	2171(%rip), %xmm1
 	addq	$4, %rbx
-	jmp	0x12d70
+	jmp	0x12c20
 	movl	$1, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -208(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -168(%rbp)
 	movl	$1, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -200(%rbp)
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -160(%rbp)
 	movl	$1, %edi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -192(%rbp)
-	movq	%r12, -152(%rbp)
-	movslq	-48(%rbp), %r12
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -152(%rbp)
+	movq	%r15, -128(%rbp)
+	movslq	-48(%rbp), %r15
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -120(%rbp)
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r12
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -112(%rbp)
-	movq	$0, -256(%rbp)
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, -80(%rbp)
+	movq	$0, -240(%rbp)
 	leaq	-48(%rbp), %rdi
-	leaq	-256(%rbp), %rsi
-	leaq	-84(%rbp), %rdx
+	leaq	-240(%rbp), %rsi
+	leaq	-104(%rbp), %rdx
 	leaq	-60(%rbp), %r8
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r10d
 	testl	%r10d, %r10d
-	jle	0x12f9f
+	jle	0x12e1e
 	leaq	-1(%r10), %rax
 	movl	%r10d, %ecx
 	andl	$3, %ecx
 	xorl	%esi, %esi
 	cmpq	$3, %rax
-	jae	0x12f27
+	jae	0x12d90
 	xorl	%edx, %edx
-	movq	-112(%rbp), %r12
-	jmp	0x12f7f
-	movl	%eax, %edx
-	andl	$-2, %edx
-	xorl	%ecx, %ecx
-	jmp	0x12efd
-	nopw	%cs:(%rax,%rax)
-	addq	$2, %rcx
-	cmpq	%rcx, %rdx
-	je	0x12d3a
-	cmpl	$1, (%r12,%rcx,4)
-	jne	0x12f10
-	movq	-72(%rbp), %rsi
-	movq	$0, (%rsi,%rcx,8)
-	cmpl	$1, 4(%r12,%rcx,4)
-	jne	0x12ef0
-	movq	-72(%rbp), %rsi
-	movq	$0, 8(%rsi,%rcx,8)
-	jmp	0x12ef0
+	movq	-80(%rbp), %rbx
+	movabsq	$4607182418800017408, %r15
+	jmp	0x12e00
 	movl	%r10d, %r9d
 	andl	$-4, %r9d
 	leal	(%r10,%r10), %r8d
 	addl	$2, %r8d
 	leal	4(,%r10,4), %r11d
-	leal	1(%r10), %ebx
+	leal	1(%r10), %r14d
 	leal	(%r10,%r10,2), %edi
 	addl	$3, %edi
 	xorl	%edx, %edx
-	movq	-112(%rbp), %r12
-	nop
+	movq	-80(%rbp), %rbx
+	movabsq	$4607182418800017408, %r15
+	nopw	%cs:(%rax,%rax)
 	movslq	%esi, %rsi
-	movq	%r13, (%r12,%rsi,8)
-	leal	(%rbx,%rsi), %eax
+	movq	%r15, (%rbx,%rsi,8)
+	leal	(%r14,%rsi), %eax
 	cltq
-	movq	%r13, (%r12,%rax,8)
+	movq	%r15, (%rbx,%rax,8)
 	leal	(%r8,%rsi), %eax
 	cltq
-	movq	%r13, (%r12,%rax,8)
+	movq	%r15, (%rbx,%rax,8)
 	leal	(%rdi,%rsi), %eax
 	cltq
-	movq	%r13, (%r12,%rax,8)
+	movq	%r15, (%rbx,%rax,8)
 	addq	$4, %rdx
 	addl	%r11d, %esi
 	cmpq	%rdx, %r9
-	jne	0x12f50
+	jne	0x12dd0
 	testq	%rcx, %rcx
-	je	0x12f9f
+	je	0x12e1e
 	leal	1(%r10), %eax
 	imull	%eax, %edx
-	nopl	(%rax,%rax)
+	nopl	(%rax)
 	movslq	%edx, %rdx
-	movq	%r13, (%r12,%rdx,8)
+	movq	%r15, (%rbx,%rdx,8)
 	addl	%eax, %edx
-	addq	$-1, %rcx
-	jne	0x12f90
-	movq	32(%rbp), %r13
-	movsd	(%r13), %xmm0
+	decq	%rcx
+	jne	0x12e10
+	movq	32(%rbp), %rax
+	movsd	(%rax), %xmm0
 	subq	$8, %rsp
-	leaq	-272(%rbp), %rax
-	leaq	-264(%rbp), %rbx
-	movq	-72(%rbp), %rdi
-	movq	-128(%rbp), %rsi
-	movl	$5, %edx
+	leaq	-256(%rbp), %rax
+	leaq	-248(%rbp), %r11
+	movq	-96(%rbp), %rdi
+	movq	-112(%rbp), %rsi
+	movl	88(%rbp), %r14d
+	movl	%r14d, %edx
 	movq	48(%rbp), %rcx
-	movq	-152(%rbp), %r8
+	movq	-128(%rbp), %r8
 	movl	$500, %r9d
-	pushq	-192(%rbp)
-	pushq	-200(%rbp)
+	pushq	-152(%rbp)
+	pushq	-160(%rbp)
 	pushq	64(%rbp)
 	pushq	%rax
-	pushq	-208(%rbp)
+	pushq	-168(%rbp)
 	pushq	$0
-	pushq	%rbx
-	pushq	-120(%rbp)
-	movq	-96(%rbp), %rbx
-	pushq	%rbx
+	pushq	%r11
+	pushq	%r12
+	movq	%r12, -88(%rbp)
+	movl	72(%rbp), %r12d
+	pushq	%r12
 	pushq	$31
 	pushq	$1
-	pushq	-104(%rbp)
+	pushq	-120(%rbp)
 	pushq	%r10
 	callq	_cv_gene_nets_support_adaENcv
 	addq	$112, %rsp
-	testl	%ebx, %ebx
-	je	0x1301e
-	movq	56(%rbp), %rax
-	movl	(%rax), %eax
-	movl	%eax, -136(%rbp)
-	jmp	0x13061
-	movl	%eax, %r12d
-	movsd	(%r13), %xmm0
+	testl	%r12d, %r12d
+	jne	0x12ec9
+	movl	%eax, %r15d
+	movq	32(%rbp), %rax
+	movsd	(%rax), %xmm0
 	movsd	%xmm0, -56(%rbp)
-	leaq	3677(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV for ridge-weight, alpha: %f.\n"
-	movl	$5, %esi
+	leaq	4077(%rip), %rdi ## literal pool for: "\tAdaptive_EN %d-fold CV for ridge-weight, alpha: %f.\n"
+	movl	%r14d, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movq	56(%rbp), %rax
-	movl	(%rax), %eax
-	movl	%eax, -136(%rbp)
-	leaq	3586(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
+	callq	0x133c4 ## symbol stub for: _printf
+	leaq	3964(%rip), %rdi ## literal pool for: "Step 3: CV support; alpha: %f, number of lambda needed: %d\n"
 	movsd	-56(%rbp), %xmm0
-	movl	%r12d, %esi
+	movl	%r15d, %esi
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
-	movslq	-44(%rbp), %r12
+	callq	0x133c4 ## symbol stub for: _printf
+	movslq	-44(%rbp), %r15
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -184(%rbp)
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %rbx
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, -176(%rbp)
-	movslq	-80(%rbp), %r12
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r14
+	movslq	-72(%rbp), %r15
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %rbx
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r12
 	movl	$8, %esi
-	movq	%r12, %rdi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movq	%rax, %r13
-	leaq	-164(%rbp), %r12
+	movq	%r15, %rdi
+	callq	0x1336a ## symbol stub for: _calloc
+	movq	%rax, %r15
+	leaq	-100(%rbp), %rdi
 	leaq	-64(%rbp), %rdx
 	leaq	-60(%rbp), %r8
-	movq	%r12, %rdi
-	movq	-128(%rbp), %rsi
+	movq	-112(%rbp), %rsi
 	movq	%rax, %rcx
-	callq	0x13502 ## symbol stub for: _dcopy
-	movq	%r12, %rdi
-	movq	-72(%rbp), %rsi
+	callq	0x1337c ## symbol stub for: _dcopy
+	leaq	-100(%rbp), %rdi
+	movq	-96(%rbp), %rsi
 	leaq	-64(%rbp), %rdx
-	movq	%rbx, %rcx
+	movq	%r12, %rcx
 	leaq	-60(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
+	callq	0x1337c ## symbol stub for: _dcopy
 	movl	-44(%rbp), %r8d
-	movq	%rbx, %rdi
-	movq	%r13, %rsi
-	movq	-184(%rbp), %rdx
-	movq	-176(%rbp), %rcx
-	movq	-104(%rbp), %r12
-	movl	%r12d, %r9d
+	movq	%r12, %rdi
+	movq	%r15, %rsi
+	movq	%rbx, -144(%rbp)
+	movq	%rbx, %rdx
+	movq	%r14, -216(%rbp)
+	movq	%r14, %rcx
+	movq	-120(%rbp), %rbx
+	movl	%ebx, %r9d
 	callq	_centerYX
 	movslq	-48(%rbp), %rdi
 	movl	$8, %esi
-	callq	0x134f0 ## symbol stub for: _calloc
-	movsd	-264(%rbp), %xmm0
+	callq	0x1336a ## symbol stub for: _calloc
+	movsd	-248(%rbp), %xmm0
 	movl	-44(%rbp), %ecx
-	movq	%rbx, %rdi
-	movq	%r13, %rsi
-	movq	%rax, -144(%rbp)
+	movq	%r12, %rdi
+	movq	%r15, %rsi
+	movq	%rax, -136(%rbp)
 	movq	%rax, %rdx
 	movsd	%xmm0, -56(%rbp)
-	movl	%r12d, %r8d
+	movl	%ebx, %r8d
 	callq	_QlambdaStart
 	movl	-44(%rbp), %ecx
-	movsd	1253(%rip), %xmm0
-	movq	%rbx, -232(%rbp)
-	movq	%rbx, %rdi
-	movq	%r13, -224(%rbp)
-	movq	%r13, %rsi
-	movq	-120(%rbp), %rdx
-	movl	%r12d, %r8d
+	movsd	1268(%rip), %xmm0
+	movq	%r12, -192(%rbp)
+	movq	%r12, %rdi
+	movq	%r15, -184(%rbp)
+	movq	%r15, %rsi
+	movq	-88(%rbp), %rdx
+	movl	%ebx, %r8d
 	callq	_lambdaMax_adaEN
-	movsd	%xmm0, -216(%rbp)
-	movl	-136(%rbp), %ecx
-	movq	-96(%rbp), %rbx
-	testl	%ebx, %ebx
-	jne	0x13197
-	leaq	3579(%rip), %rdi ## literal pool for: "Step 4: lasso/elasticNet selection path."
-	movq	%rcx, %rbx
-	callq	0x13556 ## symbol stub for: _puts
-	movq	%rbx, %rcx
-	movq	-96(%rbp), %rbx
-	testl	%ecx, %ecx
-	movq	48(%rbp), %r13
-	movsd	1163(%rip), %xmm6
-	jle	0x13354
-	xorl	%r12d, %r12d
-	movsd	%xmm6, -80(%rbp)
-	movq	%rcx, -240(%rbp)
-	jmp	0x132d6
-	nop
-	leaq	3008(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
-	movl	%r12d, %esi
-	movq	%rcx, %rdx
-	movsd	%xmm0, -248(%rbp)
+	movsd	%xmm0, -176(%rbp)
+	movl	72(%rbp), %r11d
+	testl	%r11d, %r11d
+	jne	0x12fed
+	leaq	4005(%rip), %rdi ## literal pool for: "Step 4: lasso/elasticNet selection path."
+	callq	0x133d0 ## symbol stub for: _puts
+	movl	72(%rbp), %r11d
+	movl	56(%rbp), %eax
+	testl	%eax, %eax
+	movq	48(%rbp), %r14
+	movq	-200(%rbp), %rax
+	movsd	1179(%rip), %xmm6
+	jle	0x131c2
+	movl	56(%rbp), %eax
+	movl	%eax, %eax
+	movq	%rax, -224(%rbp)
+	xorl	%r15d, %r15d
+	movsd	%xmm6, -72(%rbp)
+	jmp	0x13146
+	nopw	%cs:(%rax,%rax)
+	leaq	3040(%rip), %rdi ## literal pool for: "\t%d/%d lambdas. \tlambda_factor: %f"
+	movl	%r15d, %esi
+	movl	56(%rbp), %edx
+	movsd	%xmm0, -232(%rbp)
 	movb	$1, %al
-	movsd	%xmm4, -136(%rbp)
-	callq	0x1354a ## symbol stub for: _printf
-	movl	-44(%rbp), %eax
+	movq	%xmm4, -120(%rbp)
+	callq	0x133c4 ## symbol stub for: _printf
+	movl	-44(%rbp), %r10d
 	subq	$8, %rsp
-	movq	-120(%rbp), %rdi
-	movq	%r15, %rsi
+	movq	-88(%rbp), %rdi
+	movq	%r13, %rsi
 	movq	16(%rbp), %rdx
-	movq	-72(%rbp), %rcx
-	movq	-128(%rbp), %r8
-	movq	-144(%rbp), %rbx
-	movq	%rbx, %r9
-	movsd	-248(%rbp), %xmm0
-	movsd	-80(%rbp), %xmm1
+	movq	-96(%rbp), %rcx
+	movq	-112(%rbp), %r8
+	movq	-136(%rbp), %r12
+	movq	%r12, %r9
+	movsd	-232(%rbp), %xmm0
+	movsd	-72(%rbp), %xmm1
 	movsd	-56(%rbp), %xmm2
-	movsd	-216(%rbp), %xmm3
-	movsd	-136(%rbp), %xmm4
-	movq	-112(%rbp), %r13
-	pushq	%r13
-	pushq	-96(%rbp)
-	pushq	-104(%rbp)
+	movsd	-176(%rbp), %xmm3
+	movq	-120(%rbp), %xmm4
+	movq	-80(%rbp), %r14
+	pushq	%r14
+	movl	72(%rbp), %eax
 	pushq	%rax
+	pushq	%rbx
+	pushq	%r10
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	addq	$48, %rsp
-	leaq	2910(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
+	leaq	2947(%rip), %rdi ## literal pool for: "\tlambda: %f\n"
 	movb	$1, %al
-	callq	0x1354a ## symbol stub for: _printf
+	callq	0x133c4 ## symbol stub for: _printf
 	movsd	-56(%rbp), %xmm0
-	movq	%rbx, %rdx
+	movq	%r12, %rdx
 	movq	16(%rbp), %r8
-	movq	-104(%rbp), %rax
-	movl	%r12d, %ebx
+	movq	%rbx, %r12
+	movl	%r15d, %ebx
 	movl	-44(%rbp), %r9d
-	movq	-232(%rbp), %rdi
-	movq	-224(%rbp), %rsi
-	movq	%r15, %rcx
-	pushq	%r13
-	pushq	%rax
+	movq	-192(%rbp), %rdi
+	movq	-184(%rbp), %rsi
+	movq	%r13, %rcx
+	pushq	%r14
+	pushq	%r12
 	callq	_QlambdaMiddleCenter
 	addq	$16, %rsp
-	movq	48(%rbp), %r13
-	movsd	(%r13,%r12,8), %xmm0
-	movsd	%xmm0, -80(%rbp)
+	movq	48(%rbp), %r14
+	movsd	(%r14,%r15,8), %xmm0
+	movsd	%xmm0, -72(%rbp)
 	imull	-48(%rbp), %ebx
 	movslq	%ebx, %rax
 	movq	80(%rbp), %rcx
 	leaq	(%rcx,%rax,8), %rcx
 	leaq	-48(%rbp), %rdi
-	movq	%r15, %rsi
+	movq	%r13, %rsi
 	leaq	-64(%rbp), %rdx
 	leaq	-60(%rbp), %r8
-	callq	0x13502 ## symbol stub for: _dcopy
-	addq	$1, %r12
-	movq	-240(%rbp), %rcx
-	cmpq	%r12, %rcx
-	movq	-96(%rbp), %rbx
+	callq	0x1337c ## symbol stub for: _dcopy
+	incq	%r15
+	cmpq	%r15, -224(%rbp)
+	movq	%r12, %rbx
+	movl	72(%rbp), %r11d
+	movq	-200(%rbp), %rax
 	movsd	860(%rip), %xmm6
-	je	0x13354
+	je	0x131c2
 	movq	32(%rbp), %rax
-	movsd	(%rax,%r12,8), %xmm4
-	movsd	(%r13,%r12,8), %xmm0
-	testl	%ebx, %ebx
-	jg	0x131c0
+	movq	(%rax,%r15,8), %xmm4
+	movsd	(%r14,%r15,8), %xmm0
+	testl	%r11d, %r11d
+	jg	0x13030
 	movl	-44(%rbp), %eax
 	subq	$8, %rsp
-	movq	-120(%rbp), %rdi
-	movq	%r15, %rsi
+	movq	-88(%rbp), %rdi
+	movq	%r13, %rsi
 	movq	16(%rbp), %rdx
-	movq	-72(%rbp), %rcx
-	movq	-128(%rbp), %r8
-	movq	-144(%rbp), %r9
-	movsd	-80(%rbp), %xmm1
+	movq	-96(%rbp), %rcx
+	movq	-112(%rbp), %r8
+	movq	%rbx, %r12
+	movq	-136(%rbp), %rbx
+	movq	%rbx, %r9
+	movsd	-72(%rbp), %xmm1
 	movsd	-56(%rbp), %xmm2
-	movsd	-216(%rbp), %xmm3
-	movq	-112(%rbp), %r13
-	pushq	%r13
-	pushq	%rbx
-	pushq	-104(%rbp)
+	movsd	-176(%rbp), %xmm3
+	movq	-80(%rbp), %r14
+	pushq	%r14
+	pushq	%r11
+	pushq	%r12
 	pushq	%rax
 	pushq	$500
 	callq	_Weighted_LassoSf_adaEN
 	movsd	-56(%rbp), %xmm0
-	movq	-144(%rbp), %rdx
+	movq	%rbx, %rdx
 	movq	16(%rbp), %r8
-	movq	-104(%rbp), %rax
 	addq	$48, %rsp
-	jmp	0x13263
+	jmp	0x130cd
+	movq	%rax, %r14
 	movq	24(%rbp), %r10
 	movq	$0, (%r10)
 	xorpd	%xmm0, %xmm0
 	movupd	%xmm0, 16(%r10)
 	movl	-44(%rbp), %eax
 	testl	%eax, %eax
-	jle	0x1342d
+	jle	0x1329a
 	leaq	16(%r10), %r9
 	movq	%rax, %rdx
 	negq	%rdx
 	xorpd	%xmm2, %xmm2
 	xorl	%esi, %esi
-	xorpd	%xmm0, %xmm0
 	xorpd	%xmm1, %xmm1
 	xorpd	%xmm3, %xmm3
+	xorpd	%xmm0, %xmm0
 	xorl	%r8d, %r8d
-	movq	-152(%rbp), %r12
-	jmp	0x133ad
-	nopl	(%rax)
-	addq	$1, %r8
-	addq	$-1, %rsi
+	movq	-128(%rbp), %r15
+	movq	-88(%rbp), %r12
+	jmp	0x1321b
+	nop
+	incq	%r8
+	decq	%rsi
 	cmpq	%rax, %r8
-	je	0x13423
+	je	0x13294
 	movl	%r8d, %ebx
 	xorl	%edi, %edi
-	jmp	0x133cb
+	jmp	0x1323a
 	nopw	%cs:(%rax,%rax)
-	nop
-	addq	$-1, %rdi
+	decq	%rdi
 	addl	%eax, %ebx
 	cmpq	%rdi, %rdx
-	je	0x133a0
+	je	0x13210
 	movslq	%ebx, %rcx
 	movsd	(%r14,%rcx,8), %xmm4
 	ucomisd	%xmm2, %xmm4
-	jne	0x133f3
-	jp	0x133f3
-	movsd	(%r15,%rcx,8), %xmm5
+	jne	0x13263
+	jp	0x13263
+	movsd	(%r13,%rcx,8), %xmm5
 	ucomisd	%xmm2, %xmm5
-	jne	0x133ea
-	jnp	0x133f3
-	addsd	%xmm6, %xmm3
-	movsd	%xmm3, (%r9)
+	jne	0x1325a
+	jnp	0x13263
+	addsd	%xmm6, %xmm0
+	movsd	%xmm0, (%r9)
 	cmpq	%rdi, %rsi
-	je	0x133c0
-	movsd	(%r15,%rcx,8), %xmm5
+	je	0x13230
+	movsd	(%r13,%rcx,8), %xmm5
 	ucomisd	%xmm2, %xmm5
-	jne	0x13406
-	jnp	0x133c0
-	addsd	%xmm6, %xmm1
-	movsd	%xmm1, 24(%r10)
+	jne	0x13277
+	jnp	0x13230
+	addsd	%xmm6, %xmm3
+	movsd	%xmm3, 24(%r10)
 	ucomisd	%xmm2, %xmm4
-	jne	0x13418
-	jnp	0x133c0
-	addsd	%xmm6, %xmm0
-	movsd	%xmm0, (%r10)
-	jmp	0x133c0
-	unpcklpd	%xmm3, %xmm0
-	movq	-96(%rbp), %rbx
-	jmp	0x13438
+	jne	0x13289
+	jnp	0x13230
+	addsd	%xmm6, %xmm1
+	movsd	%xmm1, (%r10)
+	jmp	0x13230
+	divsd	%xmm3, %xmm0
+	jmp	0x132ae
+	movsd	686(%rip), %xmm0
 	xorpd	%xmm1, %xmm1
-	movq	-152(%rbp), %r12
-	movsd	8(%r10), %xmm2
-	unpcklpd	%xmm1, %xmm2
-	divpd	%xmm2, %xmm0
-	movupd	%xmm0, 32(%r10)
-	testl	%ebx, %ebx
-	jne	0x1345c
-	leaq	2800(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
-	callq	0x13556 ## symbol stub for: _puts
+	movq	-128(%rbp), %r15
+	movq	-88(%rbp), %r12
+	movq	-80(%rbp), %r13
+	movq	-144(%rbp), %rbx
+	divsd	8(%r10), %xmm1
+	movsd	%xmm1, 32(%r10)
+	movsd	%xmm0, 40(%r10)
+	testl	%r11d, %r11d
+	jne	0x132dc
+	leaq	3190(%rip), %rdi ## literal pool for: "Step 5: Finish calculation; detection power in stat vector."
+	callq	0x133d0 ## symbol stub for: _puts
 	movq	%r14, %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
+	movq	%rbx, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-216(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r15, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-192(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
 	movq	-184(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-176(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
+	callq	0x133ac ## symbol stub for: _free
 	movq	%r12, %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-232(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-224(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-120(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-112(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-144(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-208(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-200(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	movq	-192(%rbp), %rdi
-	callq	0x13532 ## symbol stub for: _free
-	addq	$232, %rsp
+	callq	0x133ac ## symbol stub for: _free
+	movq	%r13, %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-136(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-168(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-160(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	movq	-152(%rbp), %rdi
+	callq	0x133ac ## symbol stub for: _free
+	addq	$216, %rsp
 	popq	%rbx
 	popq	%r12
 	popq	%r13
 	popq	%r14
 	popq	%r15
 	popq	%rbp
 	retq
```

##### llvm-objdump --arch=x86_64 --section=__TEXT,__stubs --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -1,19 +1,19 @@
 Contents of (__TEXT,__stubs) section
-	jmpq	*2842(%rip) ## literal pool symbol address: _calloc
-	jmpq	*2844(%rip) ## literal pool symbol address: _dasum
-	jmpq	*2846(%rip) ## literal pool symbol address: _daxpy
-	jmpq	*2848(%rip) ## literal pool symbol address: _dcopy
-	jmpq	*2850(%rip) ## literal pool symbol address: _ddot
-	jmpq	*2852(%rip) ## literal pool symbol address: _dgemm
-	jmpq	*2854(%rip) ## literal pool symbol address: _dgemv
-	jmpq	*2856(%rip) ## literal pool symbol address: _dgesv
-	jmpq	*2858(%rip) ## literal pool symbol address: _dnrm2
-	jmpq	*2860(%rip) ## literal pool symbol address: _dscal
-	jmpq	*2862(%rip) ## literal pool symbol address: _dsyevd
-	jmpq	*2864(%rip) ## literal pool symbol address: _free
-	jmpq	*2866(%rip) ## literal pool symbol address: _idamax
-	jmpq	*2868(%rip) ## literal pool symbol address: _log
-	jmpq	*2870(%rip) ## literal pool symbol address: _pow
-	jmpq	*2872(%rip) ## literal pool symbol address: _printf
-	jmpq	*2874(%rip) ## literal pool symbol address: _putchar
-	jmpq	*2876(%rip) ## literal pool symbol address: _puts
+	jmpq	*3232(%rip) ## literal pool symbol address: _calloc
+	jmpq	*3234(%rip) ## literal pool symbol address: _dasum
+	jmpq	*3236(%rip) ## literal pool symbol address: _daxpy
+	jmpq	*3238(%rip) ## literal pool symbol address: _dcopy
+	jmpq	*3240(%rip) ## literal pool symbol address: _ddot
+	jmpq	*3242(%rip) ## literal pool symbol address: _dgemm
+	jmpq	*3244(%rip) ## literal pool symbol address: _dgemv
+	jmpq	*3246(%rip) ## literal pool symbol address: _dgesv
+	jmpq	*3248(%rip) ## literal pool symbol address: _dnrm2
+	jmpq	*3250(%rip) ## literal pool symbol address: _dscal
+	jmpq	*3252(%rip) ## literal pool symbol address: _dsyevd
+	jmpq	*3254(%rip) ## literal pool symbol address: _free
+	jmpq	*3256(%rip) ## literal pool symbol address: _idamax
+	jmpq	*3258(%rip) ## literal pool symbol address: _log
+	jmpq	*3260(%rip) ## literal pool symbol address: _pow
+	jmpq	*3262(%rip) ## literal pool symbol address: _printf
+	jmpq	*3264(%rip) ## literal pool symbol address: _putchar
+	jmpq	*3266(%rip) ## literal pool symbol address: _puts
```

##### llvm-objdump --arch=x86_64 --section=__TEXT,__stub_helper --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -1,42 +1,41 @@
 Contents of (__TEXT,__stub_helper) section
+	leaq	3105(%rip), %r11
+	pushq	%r11
+	jmpq	*3105(%rip) ## literal pool symbol address: dyld_stub_binder
+	nop
 	pushq	$14
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$27
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$40
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$53
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$65
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$78
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$91
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$104
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$117
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$130
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$156
-	jmp	0x135cc
-	addb	%al, (%rax)
-	leaq	2605(%rip), %r11
-	pushq	%r11
-	jmpq	*2605(%rip) ## literal pool symbol address: dyld_stub_binder
-	nop
+	jmp	0x133d8
 	pushq	$0
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$144
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$170
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$181
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$193
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$208
-	jmp	0x135cc
+	jmp	0x133d8
 	pushq	$224
-	jmp	0x135cc
+	jmp	0x133d8
```

##### llvm-objdump --arch=x86_64 --section=__TEXT,__const --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -1,33 +1,35 @@
 Contents of (__TEXT,__const) section
-0000000000013630	00 00 00 00 00 00 f0 3f 00 00 00 00 00 00 f0 bf 
-0000000000013640	bb bd d7 d9 df 7c db 3d 00 00 00 00 00 00 10 40 
-0000000000013650	bc 89 d8 97 b2 d2 9c 3c 00 00 00 00 00 00 e0 bf 
-0000000000013660	fc a9 f1 d2 4d 62 50 3f 00 00 00 00 00 00 10 c0 
-0000000000013670	00 00 00 00 00 00 e0 3f 7b 14 ae 47 e1 7a 84 3f 
-0000000000013680	00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 
-0000000000013690	00 00 00 00 00 00 00 80 00 00 00 00 00 00 00 80 
-00000000000136a0	ff ff ff ff ff ff ff 7f ff ff ff ff ff ff ff 7f 
-00000000000136b0	00 00 00 00 00 00 f0 3f 00 00 00 00 00 00 f0 3f 
-00000000000136c0	00 00 00 00 00 6a f8 40 00 00 00 00 00 6a f8 c0 
-00000000000136d0	00 00 00 00 00 00 18 c0 00 00 00 00 00 00 24 40 
-00000000000136e0	9a 99 99 99 99 99 c9 3f 00 00 00 00 00 00 00 00 
-00000000000136f0	bb bd d7 d9 df 7c db 3d bb bd d7 d9 df 7c db 3d 
-0000000000013700	78 d4 f6 74 cd 30 e4 3f b2 24 75 7f 96 7a d9 3f 
-0000000000013710	4b 70 dd 87 79 13 d0 3f 75 b3 76 c5 60 49 c4 3f 
-0000000000013720	9a 99 99 99 99 99 b9 3f fa a9 f8 c3 0a 27 b0 3f 
-0000000000013730	2a ea 90 ff 11 62 a4 3f e2 e6 fb 72 c2 b8 99 3f 
-0000000000013740	c6 c2 2b d1 b3 3a 90 3f 7e 14 ae 47 e1 7a 84 3f 
-0000000000013750	c7 dc 8d 39 11 d8 79 3f 88 ee 73 cc 74 4e 70 3f 
-0000000000013760	18 1f 63 c2 ce 93 64 3f 9c 37 79 1b 86 f7 59 3f 
-0000000000013770	f7 a9 f1 d2 4d 62 50 3f 60 7d 71 94 da ac 44 3f 
-0000000000013780	fe e3 1f 47 21 17 3a 3f a4 e5 e8 01 3f 76 30 3f 
-0000000000013790	a4 5f c7 e2 04 c6 24 3f 1e 43 1c eb e2 36 1a 3f 
-00000000000137a0	66 66 66 66 66 66 ee 3f cc cc cc cc cc cc ec 3f 
-00000000000137b0	33 33 33 33 33 33 eb 3f 99 99 99 99 99 99 e9 3f 
-00000000000137c0	00 00 00 00 00 00 e8 3f 66 66 66 66 66 66 e6 3f 
-00000000000137d0	cc cc cc cc cc cc e4 3f 32 33 33 33 33 33 e3 3f 
-00000000000137e0	99 99 99 99 99 99 e1 3f ff ff ff ff ff ff df 3f 
-00000000000137f0	cc cc cc cc cc cc dc 3f 98 99 99 99 99 99 d9 3f 
-0000000000013800	64 66 66 66 66 66 d6 3f 32 33 33 33 33 33 d3 3f 
-0000000000013810	fc ff ff ff ff ff cf 3f 98 99 99 99 99 99 c9 3f 
-0000000000013820	30 33 33 33 33 33 c3 3f 90 99 99 99 99 99 b9 3f 
+00000000000134a0	00 00 00 00 00 00 f0 3f 00 00 00 00 00 00 f0 bf 
+00000000000134b0	bb bd d7 d9 df 7c db 3d 00 00 00 00 00 00 10 c0 
+00000000000134c0	00 00 00 00 00 00 10 40 bc 89 d8 97 b2 d2 9c 3c 
+00000000000134d0	00 00 00 00 00 00 e0 bf fc a9 f1 d2 4d 62 50 3f 
+00000000000134e0	7b 14 ae 47 e1 7a 84 3f 00 00 00 00 00 00 00 00 
+00000000000134f0	00 00 00 00 00 00 00 80 00 00 00 00 00 00 00 80 
+0000000000013500	ff ff ff ff ff ff ff 7f ff ff ff ff ff ff ff 7f 
+0000000000013510	00 00 00 00 00 00 f0 3f 00 00 00 00 00 00 f0 3f 
+0000000000013520	00 00 00 00 00 6a f8 40 00 00 00 00 00 6a f8 c0 
+0000000000013530	00 00 00 00 00 00 18 c0 00 00 00 00 00 00 24 40 
+0000000000013540	9a 99 99 99 99 99 c9 3f 78 d4 f6 74 cd 30 e4 3f 
+0000000000013550	00 00 00 00 00 00 f8 7f 66 66 66 66 66 66 ee 3f 
+0000000000013560	bb bd d7 d9 df 7c db 3d bb bd d7 d9 df 7c db 3d 
+0000000000013570	01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 
+0000000000013580	01 00 00 00 01 00 00 00 01 00 00 00 00 00 00 00 
+0000000000013590	78 d4 f6 74 cd 30 e4 3f b2 24 75 7f 96 7a d9 3f 
+00000000000135a0	4b 70 dd 87 79 13 d0 3f 75 b3 76 c5 60 49 c4 3f 
+00000000000135b0	9a 99 99 99 99 99 b9 3f fa a9 f8 c3 0a 27 b0 3f 
+00000000000135c0	2a ea 90 ff 11 62 a4 3f e2 e6 fb 72 c2 b8 99 3f 
+00000000000135d0	c6 c2 2b d1 b3 3a 90 3f 7e 14 ae 47 e1 7a 84 3f 
+00000000000135e0	c7 dc 8d 39 11 d8 79 3f 88 ee 73 cc 74 4e 70 3f 
+00000000000135f0	18 1f 63 c2 ce 93 64 3f 9c 37 79 1b 86 f7 59 3f 
+0000000000013600	f7 a9 f1 d2 4d 62 50 3f 60 7d 71 94 da ac 44 3f 
+0000000000013610	fe e3 1f 47 21 17 3a 3f a4 e5 e8 01 3f 76 30 3f 
+0000000000013620	a4 5f c7 e2 04 c6 24 3f 1e 43 1c eb e2 36 1a 3f 
+0000000000013630	66 66 66 66 66 66 ee 3f cc cc cc cc cc cc ec 3f 
+0000000000013640	33 33 33 33 33 33 eb 3f 99 99 99 99 99 99 e9 3f 
+0000000000013650	00 00 00 00 00 00 e8 3f 66 66 66 66 66 66 e6 3f 
+0000000000013660	cc cc cc cc cc cc e4 3f 33 33 33 33 33 33 e3 3f 
+0000000000013670	99 99 99 99 99 99 e1 3f ff ff ff ff ff ff df 3f 
+0000000000013680	cc cc cc cc cc cc dc 3f 98 99 99 99 99 99 d9 3f 
+0000000000013690	65 66 66 66 66 66 d6 3f 32 33 33 33 33 33 d3 3f 
+00000000000136a0	fd ff ff ff ff ff cf 3f 96 99 99 99 99 99 c9 3f 
+00000000000136b0	30 33 33 33 33 33 c3 3f 93 99 99 99 99 99 b9 3f
```

##### llvm-objdump --arch=x86_64 --section=__TEXT,__cstring --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -27,18 +27,26 @@
 \t\t\t step 1 SML lasso regression, lambda: %f.\n
 \t\t\t cv: %d \tend; err_mean = %f.\n
 \t\t\t %d/Nlambdas. %d fold cv; \t Err_Mean: %f; std:%f; \t sigma2learnt:%f.\n
 \t\tExit Function: cv_support. optimal lambda index: %d.\n\n
 Step 1: CV support; return number of lambda needed: %d\n
 \t%d/%d lambdas. \tlambda_factor: %f
 \tlambda: %f\n
+\t\t\t\t\t updating Node %d \n
+\t\t\t\t\t\t\t gene %d \t interact with Node %d.\tQuadratic equation\n
+\t\t\t\t\t\t\t Node %d \t interact with Node %d.\tLinear equation\n
+\t\t\t\t\t\t\t Node %d \t interact with Node %d.\tQuadratic equation\n
+\t\t updating Node %d \n
+\t\t\t Node %d \t interact with Node %d.\tLinear equation\n
+\t\t\t Node %d \t interact with Node %d.\tQuadratic equation\n
 \t\ti_alpha %d; \t Enter Function: cv_support. Nlambdas: %d; \t %d-fold cross validation.\n
 Step 1: ridge CV; find rho : %f\n
 \tAdaptive_EN %d-fold CV, alpha: %f.\n
 Step 3: CV support; alpha: %f, number of lambda needed: %d\n
+SEM fit with alpha: %f, lambda: %f\n
 \tAdaptive_EN %d-fold CV for ridge-weight, alpha: %f.\n
 Step 3: ridge; calculate weights.
 \t\t\t step 2 SML ZeroRegression.
 Step 2: ridge; calculate weights.
 Step 4: lasso selection path.
 Step 5: Finish calculation; detection power in stat vector.
 Step 4: lasso/elasticNet selection path.
```

##### llvm-objdump --arch=x86_64 --section=__TEXT,__unwind_info --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -1,6 +1,6 @@
 Contents of (__TEXT,__unwind_info) section
-0000000000013fac	01 00 00 00 1c 00 00 00 00 00 00 00 1c 00 00 00 
-0000000000013fbc	00 00 00 00 1c 00 00 00 02 00 00 00 00 2b 00 00 
-0000000000013fcc	34 00 00 00 34 00 00 00 f1 34 01 00 00 00 00 00 
-0000000000013fdc	34 00 00 00 03 00 00 00 0c 00 01 00 10 00 01 00 
-0000000000013fec	00 00 00 00 d1 58 05 01 
+0000000000013fb4	01 00 00 00 1c 00 00 00 00 00 00 00 1c 00 00 00 
+0000000000013fc4	00 00 00 00 1c 00 00 00 02 00 00 00 10 23 00 00 
+0000000000013fd4	34 00 00 00 34 00 00 00 6b 33 01 00 00 00 00 00 
+0000000000013fe4	34 00 00 00 03 00 00 00 0c 00 01 00 10 00 01 00 
+0000000000013ff4	00 00 00 00 d1 58 05 01
```

##### llvm-objdump --arch=x86_64 --section=__DATA,__la_symbol_ptr --macho --demangle --no-leading-addr --no-show-raw-insn {}

```diff
@@ -1,11 +1,11 @@
 Contents of (__DATA,__la_symbol_ptr) section
 Unknown section type (0x00000007)
-0000000000014010	dc 35 01 00 00 00 00 00 5c 35 01 00 00 00 00 00 
-0000000000014020	66 35 01 00 00 00 00 00 70 35 01 00 00 00 00 00 
-0000000000014030	7a 35 01 00 00 00 00 00 84 35 01 00 00 00 00 00 
-0000000000014040	8e 35 01 00 00 00 00 00 98 35 01 00 00 00 00 00 
-0000000000014050	a2 35 01 00 00 00 00 00 ac 35 01 00 00 00 00 00 
-0000000000014060	b6 35 01 00 00 00 00 00 e6 35 01 00 00 00 00 00 
-0000000000014070	c0 35 01 00 00 00 00 00 f0 35 01 00 00 00 00 00 
-0000000000014080	fa 35 01 00 00 00 00 00 04 36 01 00 00 00 00 00 
-0000000000014090	0e 36 01 00 00 00 00 00 18 36 01 00 00 00 00 00 
+0000000000014010	56 34 01 00 00 00 00 00 e8 33 01 00 00 00 00 00 
+0000000000014020	f2 33 01 00 00 00 00 00 fc 33 01 00 00 00 00 00 
+0000000000014030	06 34 01 00 00 00 00 00 10 34 01 00 00 00 00 00 
+0000000000014040	1a 34 01 00 00 00 00 00 24 34 01 00 00 00 00 00 
+0000000000014050	2e 34 01 00 00 00 00 00 38 34 01 00 00 00 00 00 
+0000000000014060	42 34 01 00 00 00 00 00 60 34 01 00 00 00 00 00 
+0000000000014070	4c 34 01 00 00 00 00 00 6a 34 01 00 00 00 00 00 
+0000000000014080	74 34 01 00 00 00 00 00 7e 34 01 00 00 00 00 00 
+0000000000014090	88 34 01 00 00 00 00 00 92 34 01 00 00 00 00 00
```

### Comparing `sparseSEM-1.1/sparseSEM/src/lassoSEM.c` & `sparseSEM-2.0/sparseSEM/src/lassoSEM.c`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/sparseSEM/src/lassoSEM.h` & `sparseSEM-2.0/sparseSEM/src/lassoSEM.h`

 * *Files identical despite different names*

### Comparing `sparseSEM-1.1/sparseSEM/src/lassoSMLv11beta.c` & `sparseSEM-2.0/sparseSEM/src/lassoSMLv11beta.c`

 * *Files 1% similar despite different names*

```diff
@@ -898,15 +898,15 @@
 		F1ptr = &BfOld[MM];
 		dcopy(&M,f,&inci,F1ptr,&incj);
 
 		for(i=0;i<M;i++)
 		{
 			if(s[i] >0)
 			{ 	//
-				if(verbose>6) printf("\t\t\t\t\t updating gene %d \n",i);
+				if(verbose>6) printf("\t\t\t\t\t updating Node %d \n",i);
 				ei[i] = 1;
 
 
 				zi = &QIBinv[i*M];
 				for(j=0;j<M;j++)
 				{
 					js_i = S[j*M + i]; 		//ith row
@@ -967,15 +967,15 @@
 									{
 										B[j*M+i] = 0;
 									}
 								}//B_ij>0
 							}else //m_ij ~=0 go to the quadratic equation
 							{
 								//
-								if(verbose>7) printf("\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n",i,j);
+								if(verbose>7) printf("\t\t\t\t\t\t\t gene %d \t interact with Node %d.\tQuadratic equation\n",i,j);
 
 								d_ij = 1/m_ij + B[j*M+i];
 								theta_ijp = r_ij*d_ij + beta_ij - lambdaW;
 								k_ijp = d_ij*(beta_ij - lambdaW) - N*sigma2;
 
 								q_ijp = theta_ijp*theta_ijp - 4*r_ij * k_ijp;
 								Bijpp = (1/(2*r_ij))*(theta_ijp + sqrt(q_ijp));
@@ -1240,15 +1240,15 @@
 	eiB = (double* ) calloc(M, sizeof(double));
 	double *BiT;
 	BiT = (double* ) calloc(M, sizeof(double));
 	//quadratic function
 	double d_ij, theta_ijp,k_ijp,q_ijp,Bijpp, Bijpm; //case (14)
 	double q_ijm, theta_ijm, Bijmm, Bijmp,Lss,candsBij,LssCands;
 
-	//converge of gene i
+	//converge of Node i
 	double dB,ziDb,BF1;
 
 	//converge of while
 	double delta_BF,FnormOld, FnormChange;
 	double *BfOld,*BfNew,*BfChange;
 	index = M*(M  +1);
 	BfOld = (double* ) calloc(index, sizeof(double));
@@ -1263,15 +1263,15 @@
 		F1ptr = &BfOld[MM];
 		dcopy(&M,f,&inci,F1ptr,&incj);
 
 		for(i=0;i<M;i++)
 		{
 			if(s[i] >0)
 			{ 	//
-				if(verbose>6) printf("\t\t\t\t\t updating gene %d \n",i);
+				if(verbose>6) printf("\t\t\t\t\t updating Node %d \n",i);
 				//
 				ei[i] = 1;
 
 				zi = &QIBinv[i*M];
 				for(j=0;j<M;j++)
 				{
 					js_i = S[j*M + i]; 		//ith row
@@ -1311,15 +1311,15 @@
 r_ij = r_ij + (1 -alpha_factor)*lambda;
 
 							beta_ij = ddot(&N, y_j, &inci,a_iT, &incj);
 
 							if (fabs(m_ij)<1e-10) //go to the linear equation
 							{
 								//
-								if(verbose>7) printf("\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tLinear equation\n",i,j);
+								if(verbose>7) printf("\t\t\t\t\t\t\t Node %d \t interact with Node %d.\tLinear equation\n",i,j);
 								//
 								Bij = (beta_ij-lambdaW)/r_ij;
 								if(Bij>0)
 								{
 									B[j*M+i] = Bij;//B(i,j)      = Bij;
 								}else
 								{
@@ -1331,15 +1331,15 @@
 									{
 										B[j*M+i] = 0;
 									}
 								}//B_ij>0
 							}else //m_ij ~=0 go to the quadratic equation
 							{
 								//
-								if(verbose>7) printf("\t\t\t\t\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n",i,j);
+								if(verbose>7) printf("\t\t\t\t\t\t\t Node %d \t interact with Node %d.\tQuadratic equation\n",i,j);
 								//
 								//assume Bij >0
 								d_ij = 1/m_ij + B[j*M+i];
 								theta_ijp = r_ij*d_ij + beta_ij - lambdaW;
 								k_ijp = d_ij*(beta_ij - lambdaW) - N*sigma2;
 
 								q_ijp = theta_ijp*theta_ijp - 4*r_ij * k_ijp;
@@ -1411,15 +1411,15 @@
 				dcopy(&M,readPtr,&ldM,BiT,&inci);
 
 				F1ptr = &F1[M*i];
 				BF1 = ddot(&M, BiT, &inci,F1ptr, &incj);
 
 				f[i] = f0[i] - BF1;
 				ei[i] = 0; // re-set ei for next i
-			}else//s[i]  no un-zero weight in this gene
+			}else//s[i]  no un-zero weight in this Node
 			{
 				readPtr = &B[i];
 				dcopy(&M,&toyZero,&inc0,readPtr,&ldM);
 				f[i] = f0[i];
 			} // s[i]
 		}//i= 1:M
 
@@ -1491,15 +1491,15 @@
 
 		// inner loop
 		for(i=0;i<M;i++)
 		{
 			if(s[i] >0)
 			{
 				//
-				if(verbose>6) printf("\t\t updating gene %d \n",i);
+				if(verbose>6) printf("\t\t updating Node %d \n",i);
 				//
 			ei[i] = 1;
 
 				zi = &IBinvZero[i*M];
 				for(j=0;j<M;j++)
 				{
 					js_i = S[j*M + i]; 		//ith row
@@ -1532,21 +1532,21 @@
 
 						r_ij = ddot(&N, y_j, &inci,y_j, &inci);
 						beta_ij = ddot(&N, y_j, &inci,a_iT, &incj);
 
 						if (fabs(m_ij)<1e-10) //go to the linear equation
 						{
 							//
-							if(verbose>7) printf("\t\t\t gene %d \t interact with gene %d.\tLinear equation\n",i,j);
+							if(verbose>7) printf("\t\t\t Node %d \t interact with Node %d.\tLinear equation\n",i,j);
 							B[j*M+i] = beta_ij/r_ij;
 
 						}else //m_ij ~=0 go to the quadratic equation
 						{
 							//
-							if(verbose>7) printf("\t\t\t gene %d \t interact with gene %d.\tQuadratic equation\n",i,j);
+							if(verbose>7) printf("\t\t\t Node %d \t interact with Node %d.\tQuadratic equation\n",i,j);
 							//
 
 							d_ij = 1/m_ij + B[j*M+i];
 							theta_ij = r_ij*d_ij + beta_ij;
 							k_ij = d_ij*beta_ij - N*sigma2;
 
 							q_ij = theta_ij*theta_ij - 4*r_ij* k_ij;
@@ -2160,15 +2160,17 @@
 	return ilambda_ms;
 
 
 } //end of cv_gene_nets_support
 
 
 //void mainSML_adaEN(double *Y, double *X, int *m, int *n, int *Missing,double*B, double *f,double*stat,int*VB)
-void mainSML_adaEN(double *Y, double *X, int M, int N, int *Missing,double*B, double *f,double*stat,int verbose)
+void mainSML_adaEN(double *Y, double *X, int M, int N, int *Missing,double*B, double *f,double*stat,
+                    double *out_paras,
+                    int verbose)
 {
 	int i, j,index;//M, N, ,verbose
 	int inci = 1;
 	int incj = 1;
 	int inc0 = 0;
 	//M 			= m[0];
 	//N 			= n[0];
@@ -2294,18 +2296,18 @@
 			temIndex = i_alpha;
 		}
 	}
 	ind_minEN = temIndex;
 
 	ilambda_cv_ms 			= lambdaEN[ind_minEN];
 	alpha_factor  			= alpha_factors[ind_minEN];
-	if(verbose==0) printf("\tAdaptive_EN %d-fold CV, alpha: %f.\n", Kcv,alpha_factor);
+	if(verbose>=0) printf("\tAdaptive_EN %d-fold CV, alpha: %f.\n", Kcv,alpha_factor);
 
 
-	if(verbose==0) printf("Step 3: CV support; alpha: %f, number of lambda needed: %d\n", alpha_factor,ilambda_cv_ms);
+	if(verbose>=0) printf("Step 3: CV support; alpha: %f, number of lambda needed: %d\n", alpha_factor,ilambda_cv_ms);
 
 	//call centerYX;
 	double *meanY, *meanX, *Ycopy, *Xcopy;
 	meanY = (double* ) calloc(M, sizeof(double));
 	meanX = (double* ) calloc(M, sizeof(double));
 	Ycopy = (double* ) calloc(MN, sizeof(double));
 	Xcopy = (double* ) calloc(MN, sizeof(double));
@@ -2326,15 +2328,15 @@
 	double lambda_factor;
 	int ilambda;
 	double lambda;
 	double lambda_max;
 
 	lambda_max = lambdaMax_adaEN(Ycopy,Xcopy,W,M, N,alpha_factor);
 
-	if(verbose==0) printf("Step 4: lasso selection path.\n");
+	if(verbose>=0) printf("Step 4: lasso selection path.\n");
 
 	for(ilambda = 0;ilambda<ilambda_cv_ms;ilambda++)
 	{
 		lambda_factor = lambda_factors[ilambda];
 		if(verbose>0) printf("\t%d/%d lambdas. \tlambda_factor: %f", ilambda, ilambda_cv_ms,lambda_factor);
 		// call Weighted_LassoSf		Missing,
 		lambda = Weighted_LassoSf_adaEN(W, B, f, Y,X, Q, lambda_factor,lambda_factor_prev,
@@ -2342,14 +2344,18 @@
 					alpha_factor); 	// mueL not calculated
 
 if(verbose>0) printf("\tlambda: %f\n", lambda);
 
 		QlambdaMiddleCenter(Ycopy,Xcopy, Q,B,f,sigma2,M, N,QIBinv); //same set of Y,X 		<-- mueL not needed
 		lambda_factor_prev = lambda_factors[ilambda];
 	}//ilambda: selection path
+
+	out_paras[0] = alpha_factor;
+	out_paras[1] = lambda_factor;
+	if(verbose>=0) printf("SEM fit with alpha: %f, lambda: %f\n", alpha_factor, lambda_factor);
 	stat[0] = 0;// correct positive
 	stat[2] = 0;//false positive
 	stat[3] = 0;//positive detected
 	for(i=0;i<M;i++)
 	{
 		for(j=0;j<M;j++)
 		{
@@ -2365,15 +2371,15 @@
 				}
 			}
 		}
 	}
 	//power
 	stat[4] = stat[0]/stat[1];
 	stat[5] = stat[2]/stat[3];
-	if(verbose==0) printf("Step 5: Finish calculation; detection power in stat vector.\n");
+	if(verbose>=0) printf("Step 5: Finish calculation; detection power in stat vector.\n");
 	free(Strue);
 	free(meanY);
 	free(meanX);
 	free(lambda_factors);
 	free(rho_factors);
 	free(Ycopy);
 	free(Xcopy);
@@ -2626,17 +2632,17 @@
 	{
 		sigma2R = err_mean_prev/(MN -1);
 	}
 
 	rho_factor = rho_factors[irho-1]*N/(N-Ntest);
 	if(verbose>4) printf("sigma2learnt: %f\n",sigma2R);
 
-	if(verbose==0) printf("Step 1: ridge CV; find rho : %f\n", rho_factor);
+	if(verbose>=0) printf("Step 1: ridge CV; find rho : %f\n", rho_factor);
 	sigma2learnt = constrained_ridge_cff(Y, X, rho_factor, M, N,BR,fR,mueR,verbose);
-	if(verbose==0) printf("Step 2: ridge; calculate weights.\n");
+	if(verbose>=0) printf("Step 2: ridge; calculate weights.\n");
 
 	for(i=0;i<MM;i++) W[i] = 1/fabs(BL[i]+ 1e-10);
 
 	sigmaLasso[0] = sigma2R;
 	sigma2learnt_EN[0] = sigma2learnt;
 	}else	//i_alpha ==0
 	{
@@ -2899,14 +2905,15 @@
 
 void mainSML_adaENcv(double *Y, double *X, int M, int N, int *Missing, double*B, double *f,double*stat,
 			double*alpha_factors,int L_alpha, 	// must be scalar
 			double *lambda_factors, int Nlambdas,
 			double *mse, double*mseSte,
 			double *mseStd,
 			int Kcv,
+			double *out_paras,
 			int verbose) 						// mseStd: nLmabda x 2 matrix, keep mse + std
 {
 
 	int i, j,index;
 	int inci 				= 1;
 	int incj 				= 1;
 	int inc0 				= 0;
@@ -3085,14 +3092,16 @@
 					alpha_factor); 	// mueL not calculated
 					if(verbose>0) printf("\tlambda: %f\n", lambda);
 		QlambdaMiddleCenter(Ycopy,Xcopy, Q,B,f,sigma2,M, N,QIBinv); //same set of Y,X 		<-- mueL not needed
 		lambda_factor_prev = lambda_factors[ilambda];
 
 	}//ilambda; selection path
 
+    out_paras[0] = alpha_factor;
+    out_paras[1] = lambda_factor;
 	stat[0] = 0;// correct positive
 	stat[2] = 0;//false positive
 	stat[3] = 0;//positive detected
 	for(i=0;i<M;i++)
 	{
 		for(j=0;j<M;j++)
 		{
@@ -3341,26 +3350,27 @@
 //----------------------- Stability Selection -----------------------
 //-----------------------     June 2013       -----------------------
 //-------------------------------------------------------------------
 
 // compute Bs for all {alpha, lambda} return to R
 // R will repeat calling this functions for 100times, compute FDR Ev for all setups.
 //from input: {alpha, lambda} are in descending order with among of shrinkage
-void mainSML_adaENstabilitySelection(double *Y, double *X, int *m, int *n, int *Missing,
+void mainSML_adaENstabilitySelection(double *Y, double *X, int M, int N, int *Missing,
 			double*B, double *f,double*stat,double*alpha_factors,int *nAlpha,
-			double *lambda_factors, int *nLambda, double *mseStd, int*VB,
-			double *Bout) 						// mseStd: nLmabda x 2 matrix, keep mse + std
+			double *lambda_factors, int nLambda, double *mseStd, int verbose,
+			double *Bout,
+			int Kcv) 						// mseStd: nLmabda x 2 matrix, keep mse + std
 {
-	int M, N, i, j,index,verbose;
+	int i, j,index; //M, N,,verbose
 	int inci 				= 1;
 	int incj 				= 1;
 	int inc0 				= 0;
-	M 						= m[0];
-	N 						= n[0];
-	verbose 				= VB[0];
+	//M 						= m[0];
+	//N 						= n[0];
+	//verbose 				= VB[0];
 	int MN 					= M*N;
 	int MM 					= M*M;
 	double *Strue;
 	Strue 					= (double* ) calloc(MM, sizeof(double));
 	dcopy(&MM,B,&inci,Strue,&incj);
 	stat[1] 				= 0;
 	for(i=0;i<M;i++)
@@ -3381,15 +3391,15 @@
 	for(i=0;i<MN;i++)
 	{
 		if(Missing[i] == 1) Y[i] = 0;
 	}
 
 	//call cv_gene_nets_support ------------------------SYSTEM PARAMETERS
 	int maxiter 			= 500;
-	int Kcv 				= 5;
+	//int Kcv 				= 5;
 
 	double step 	= -0.2;
 	//rho factor
 	step 					= -6;
 	double * rho_factors;
 	int L 					= 31; // number of rho_factors
 	rho_factors 			= (double* ) calloc(L, sizeof(double));
@@ -3471,15 +3481,15 @@
 	}
 	ind_minEN = temIndex;
 
 	ilambda_cv_ms 			= lambdaEN[ind_minEN];
 	alpha_factor  			= alpha_factors[ind_minEN];
 	if(verbose==0) printf("\tAdaptive_EN %d-fold CV for ridge-weight, alpha: %f.\n", Kcv,alpha_factor);
 	//----------------------------------------------------------R-package
-	Nlambdas 				= nLambda[0];
+	Nlambdas 				= nLambda; //[0];
 
 	//----------------------------------------------------------R-package
 	if(verbose==0) printf("Step 3: CV support; alpha: %f, number of lambda needed: %d\n", alpha_factor,ilambda_cv_ms);
 
 	//call centerYX;
 	double *meanY, *meanX, *Ycopy, *Xcopy;
 	meanY = (double* ) calloc(M, sizeof(double));
```

### Comparing `sparseSEM-1.1/sparseSEM.egg-info/PKG-INFO` & `sparseSEM-2.0/sparseSEM.egg-info/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sparseSEM
-Version: 1.1
+Version: 2.0
 Summary: Python wrapper for sparseSEM
 Home-page: https://scholar.google.com/citations?user=WhDMZEIAAAAJ&hl=en
 Author: Anhui Huang
 Author-email: anhuihuang@gmail.com
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Programming Language :: Python
@@ -25,44 +25,52 @@
 
 # Elastic Net for Structural Equation Models (SEM)
 
 Anhui Huang | Ph.D. Electrical and Computer Engineering 
 
 <https://scholar.google.com/citations?user=WhDMZEIAAAAJ&hl=en>
 
+## Summary
+Provides elastic net penalized maximum likelihood for structural equation models (SEM).   The package implements 
+`lasso` and `elastic net` (l1/l2) penalized SEM and 
+estimates the model parameters with an efficient block coordinate ascent algorithm that maximizes the penalized 
+likelihood of the SEM.  Hyperparameters are inferred from cross-validation (CV).  A Stability Selection (STS) function 
+is also available to provide accurate causal effect selection. 
+
+The experimental study and vignettes are also available in the `doc/` folder in the package.  
 
 ## PyPI installation 
-`sparseSEM` is available on PyPI:  https://pypi.org/project/sparseSEM/1.0/. Run command `pip install sparseSEM` to install 
+`sparseSEM` is available on PyPI:  https://pypi.org/project/sparseSEM/. Run command `pip install sparseSEM` to install 
 from PyPI.
 
 `test/` folder contains examples using data packed along with this package in `data/` folder. 
 To run `test/` examples, clone this repo, and run from `test/` directory. 
 
 
-## Documentation
-The theory and background for network topology inference using sparse Structural Equation Models (SEM) can be found 
-in my Ph.D dissertation (Huang A. 2014). The experimental study are also available in the `doc/` folder in the package.  
-
-
-## Configuration
+### Configuration
 This package was originally developed to leverage high performance computer clusters to enable parallel computation 
 through openMPI.  Users who have access to large scale computational resources can explore the functionality and 
 checkout the openMPI module in this package.
 
 Current package utilizes blas/lapack for high speed computation. To build the C/C++ code, the intel OneMKL library is 
 specified in the package setup. 
 - Install the free OneMKL package (https://www.intel.com/content/www/us/en/docs/oneapi/programming-guide/2023-0/intel-oneapi-math-kernel-library-onemkl.html)
 - Check if your package is the same as in the setup.py file ('/opt/intel/oneapi/mkl/2023.1.0/include'). Update the file 
 accordingly if it was installed in a different path.
 
+### Release Note
+- V2.0: add more output information include CV results, hyperparameter, and details of model fit. V2.0 is a major release with stability selection added.
+- V1: initial release with corresponding to R package v2.
+
 
-## R package
-An R package with similiar implementation is also available at CRAN: https://cran.r-project.org/web/packages/sparseSEM/index.html
+## Package for other platforms
+### R package
+An R package for `sparseSEM` is also available at CRAN: https://cran.r-project.org/web/packages/sparseSEM/index.html
 
-## OpenMPI
+### OpenMPI
 C/C++ implementation of sparseSEM with openMPI for parallel computation is available in openMPI branch (https://github.com/anhuihng/pySparseSEM/tree/openMPI). 
 
     
 ## Reference
     - Huang A. (2014) Sparse Model Learning for Inferring Genotype and Phenotype Associations. Ph.D Dissertation,
     University of Miami, Coral Gables, FL, USA.
     - Huang A. (2014) sparseSEM: Sparse-Aware Maximum Likelihood for Structural Equation Models. Rpackage
```

### Comparing `sparseSEM-1.1/sparseSEM.egg-info/SOURCES.txt` & `sparseSEM-2.0/sparseSEM.egg-info/SOURCES.txt`

 * *Files 13% similar despite different names*

```diff
@@ -7,23 +7,25 @@
 data/Y.csv
 doc/.DS_Store
 doc/Fig1_nCPU.png
 doc/Fig2_sigma01.png
 doc/Fig3_sigma05.png
 doc/Fig4_cisTransNetworkYeast_clusters_manualAdjusted_GOterm.jpg
 doc/Fig5_yeast_grn_genome_biology.png
+doc/Network-Inference-via-sparseSEM.pdf
 doc/sparseSEM.md
 doc/sparseSEM.pdf
 doc/table1_data.png
 doc/table2_data.png
 doc/table3_data.png
 sparseSEM/__init__.py
 sparseSEM/elasticNetSML.py
 sparseSEM/elasticNetSMLcv.py
 sparseSEM/elasticNetSMLpoint.py
+sparseSEM/enSEM_STS.py
 sparseSEM/loadSEMlib.py
 sparseSEM/sparseSEM.cpython-310-darwin.so
 sparseSEM.egg-info/PKG-INFO
 sparseSEM.egg-info/SOURCES.txt
 sparseSEM.egg-info/dependency_links.txt
 sparseSEM.egg-info/requires.txt
 sparseSEM.egg-info/top_level.txt
```


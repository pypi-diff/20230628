# Comparing `tmp/SumOfSquares-1.2.1.tar.gz` & `tmp/SumOfSquares-1.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "SumOfSquares-1.2.1.tar", last modified: Fri Apr 29 19:38:52 2022, max compression
+gzip compressed data, was "SumOfSquares-1.2.2.tar", last modified: Wed Jun 28 01:54:45 2023, max compression
```

## Comparing `SumOfSquares-1.2.1.tar` & `SumOfSquares-1.2.2.tar`

### file list

```diff
@@ -1,17 +1,21 @@
-drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2022-04-29 19:38:52.673391 SumOfSquares-1.2.1/
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1053 2022-04-29 18:49:06.000000 SumOfSquares-1.2.1/LICENSE
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1437 2022-04-29 19:38:52.673391 SumOfSquares-1.2.1/PKG-INFO
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)      836 2022-04-29 19:27:21.000000 SumOfSquares-1.2.1/README.md
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)      121 2022-04-29 18:51:48.000000 SumOfSquares-1.2.1/pyproject.toml
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)      689 2022-04-29 19:38:52.676725 SumOfSquares-1.2.1/setup.cfg
-drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2022-04-29 19:38:52.673391 SumOfSquares-1.2.1/src/
-drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2022-04-29 19:38:52.673391 SumOfSquares-1.2.1/src/SumOfSquares/
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)    10280 2022-04-29 19:37:06.000000 SumOfSquares-1.2.1/src/SumOfSquares/SoS.py
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)      374 2021-05-19 18:31:44.000000 SumOfSquares-1.2.1/src/SumOfSquares/__init__.py
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)     4829 2021-04-25 03:07:25.000000 SumOfSquares-1.2.1/src/SumOfSquares/basis.py
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1466 2021-05-19 19:14:03.000000 SumOfSquares-1.2.1/src/SumOfSquares/util.py
-drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2022-04-29 19:38:52.673391 SumOfSquares-1.2.1/src/SumOfSquares.egg-info/
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1437 2022-04-29 19:38:52.000000 SumOfSquares-1.2.1/src/SumOfSquares.egg-info/PKG-INFO
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)      306 2022-04-29 19:38:52.000000 SumOfSquares-1.2.1/src/SumOfSquares.egg-info/SOURCES.txt
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)        1 2022-04-29 19:38:52.000000 SumOfSquares-1.2.1/src/SumOfSquares.egg-info/dependency_links.txt
--rw-r--r--   0 chenyang  (1000) chenyang  (1000)       13 2022-04-29 19:38:52.000000 SumOfSquares-1.2.1/src/SumOfSquares.egg-info/top_level.txt
+drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1053 2022-04-29 18:49:06.000000 SumOfSquares-1.2.2/LICENSE
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     3327 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/PKG-INFO
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1337 2022-12-30 02:25:15.000000 SumOfSquares-1.2.2/README.md
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1440 2023-06-28 01:48:11.000000 SumOfSquares-1.2.2/pyproject.toml
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)       38 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/setup.cfg
+drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/src/
+drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/src/SumOfSquares/
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)    10368 2022-12-30 03:23:20.000000 SumOfSquares-1.2.2/src/SumOfSquares/SoS.py
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)      374 2021-05-19 18:31:44.000000 SumOfSquares-1.2.2/src/SumOfSquares/__init__.py
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     4988 2022-12-30 03:02:36.000000 SumOfSquares-1.2.2/src/SumOfSquares/basis.py
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     1466 2021-05-19 19:14:03.000000 SumOfSquares-1.2.2/src/SumOfSquares/util.py
+drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/src/SumOfSquares.egg-info/
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     3327 2023-06-28 01:54:45.000000 SumOfSquares-1.2.2/src/SumOfSquares.egg-info/PKG-INFO
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)      373 2023-06-28 01:54:45.000000 SumOfSquares-1.2.2/src/SumOfSquares.egg-info/SOURCES.txt
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)        1 2023-06-28 01:54:45.000000 SumOfSquares-1.2.2/src/SumOfSquares.egg-info/dependency_links.txt
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)       64 2023-06-28 01:54:45.000000 SumOfSquares-1.2.2/src/SumOfSquares.egg-info/requires.txt
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)       13 2023-06-28 01:54:45.000000 SumOfSquares-1.2.2/src/SumOfSquares.egg-info/top_level.txt
+drwxr-xr-x   0 chenyang  (1000) chenyang  (1000)        0 2023-06-28 01:54:45.717245 SumOfSquares-1.2.2/tests/
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)      813 2022-04-29 19:31:17.000000 SumOfSquares-1.2.2/tests/test_basis.py
+-rw-r--r--   0 chenyang  (1000) chenyang  (1000)     7234 2022-12-30 03:23:50.000000 SumOfSquares-1.2.2/tests/test_sos.py
```

### Comparing `SumOfSquares-1.2.1/LICENSE` & `SumOfSquares-1.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `SumOfSquares-1.2.1/src/SumOfSquares/SoS.py` & `SumOfSquares-1.2.2/src/SumOfSquares/SoS.py`

 * *Files 1% similar despite different names*

```diff
@@ -141,24 +141,27 @@
         p = poly_variable(f'c{i}', vars, 2*deg - poly_degree(eq, vars))
         f += p * eq
     for i, ineq in enumerate(ineqs):
         s = poly_variable(f'd{i}', vars, (2*deg - poly_degree(ineq, vars))//2*2)
         prob.add_sos_constraint(s, vars, name=f'd{i}', sparse=sparse)
         f += s * ineq
 
+    i = 0
     if ineq_prods:
         for r in range(len(ineqs)):
             for comb in combinations(ineqs, r):
                 total_deg = sum(map(lambda p: sp.poly(p, vars).total_degree(), comb))
                 if total_deg <= 2*deg:
                     s = poly_variable(f'e{i}', vars, (2*deg - total_deg)//2*2)
+                    i += 1
                     prob.add_sos_constraint(s, vars, name=f'e{i}', sparse=sparse)
                     f += s * prod(comb)
 
-    prob.add_sos_constraint(obj - gamma - f, vars, sparse=sparse)
+    # Much faster after using sp.expand
+    prob.add_sos_constraint(sp.expand(obj - gamma - f), vars, sparse=sparse)
     prob.set_objective('max', gamma_p)
     return prob
 
 def poly_cert_prob(vars, poly, eqs=None, ineqs=None, ineq_prods=False, deg=None, sparse=False):
     '''Formulates and returns a degree DEG Sum-of-Squares relaxation of a polynomial
     optimization problem in variables VARS that certifies POLY is a sum of
     squares on the set defined by EQS and INEQS. INEQ_PRODS determines if
```

### Comparing `SumOfSquares-1.2.1/src/SumOfSquares/basis.py` & `SumOfSquares-1.2.2/src/SumOfSquares/basis.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,12 +1,11 @@
 import sympy as sp
 import numpy as np
 import math
 from collections import defaultdict
-from scipy.spatial import ConvexHull
 
 from .util import *
 
 def basis_hom(n, d):
     '''Generator for a homogeneous polynomial basis for n variables of degree d,
     represented as a list of tuples (same as sympy), so that:
     len(list(basis_hom(n,d))) == binom(n+d-1, d)
@@ -58,14 +57,18 @@
         '''Returns a basis from a polynomial compatible with SoS,
         ordering monomials in lexicographic order'''
         poly_deg = poly.total_degree()
         monoms = np.array(poly.monoms())/2
         full_basis = Basis.from_degree(len(poly.gens), math.ceil(poly_deg / 2),
                                        is_hom(poly, poly_deg))
         if sparse and len(monoms) >= 3: # Newton polytope sparsity reduction
+            try:
+                from scipy.spatial import ConvexHull
+            except ImportError:
+                raise ImportError('Convex hull calculation requires scipy.spatial installed')
             a = np.mean(monoms, axis=0)
             U, U_ = orth(monoms - a) # U orthogonal to U_
             proj, proj_ = lambda m: U.dot(m - a), lambda m: U_.dot(m - a)
             hull = ConvexHull(np.apply_along_axis(proj, 1, monoms))
             def in_hull(pt): # Point lies in affine subspace and convex hull
                 return np.linalg.norm(proj_(pt)) < 1e-9 and \
                     sum(hull.equations.dot(np.append(proj(pt), 1)) > 1e-9) == 0
```

### Comparing `SumOfSquares-1.2.1/src/SumOfSquares/util.py` & `SumOfSquares-1.2.2/src/SumOfSquares/util.py`

 * *Files identical despite different names*


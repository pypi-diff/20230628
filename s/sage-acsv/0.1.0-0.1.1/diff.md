# Comparing `tmp/sage_acsv-0.1.0.tar.gz` & `tmp/sage_acsv-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sage_acsv-0.1.0.tar", max compression
+gzip compressed data, was "sage_acsv-0.1.1.tar", max compression
```

## Comparing `sage_acsv-0.1.0.tar` & `sage_acsv-0.1.1.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0     1066 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/LICENSE
--rw-r--r--   0        0        0     1296 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/README.md
--rw-r--r--   0        0        0      661 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/pyproject.toml
--rw-r--r--   0        0        0       70 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/sage_acsv/__init__.py
--rw-r--r--   0        0        0    10489 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/sage_acsv/asymptotics.py
--rw-r--r--   0        0        0     1125 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/sage_acsv/debug.py
--rw-r--r--   0        0        0     3139 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/sage_acsv/helpers.py
--rw-r--r--   0        0        0     5156 2023-03-14 18:48:48.673862 sage_acsv-0.1.0/sage_acsv/kronecker.py
--rw-r--r--   0        0        0     1999 1970-01-01 00:00:00.000000 sage_acsv-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0     1066 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/LICENSE
+-rw-r--r--   0        0        0     1662 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/README.md
+-rw-r--r--   0        0        0      661 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0       70 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/sage_acsv/__init__.py
+-rw-r--r--   0        0        0    13664 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/sage_acsv/asymptotics.py
+-rw-r--r--   0        0        0     1125 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/sage_acsv/debug.py
+-rw-r--r--   0        0        0     3441 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/sage_acsv/helpers.py
+-rw-r--r--   0        0        0     5156 2023-06-28 03:24:16.416500 sage_acsv-0.1.1/sage_acsv/kronecker.py
+-rw-r--r--   0        0        0     2365 1970-01-01 00:00:00.000000 sage_acsv-0.1.1/PKG-INFO
```

### Comparing `sage_acsv-0.1.0/LICENSE` & `sage_acsv-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `sage_acsv-0.1.0/README.md` & `sage_acsv-0.1.1/README.md`

 * *Files 21% similar despite different names*

```diff
@@ -2,23 +2,31 @@
 
 This repository hosts the implementation of a SageMath package
 containing algorithms for analytic combinatorics in several variables.
 
 The package works with any reasonably recent version of SageMath, we
 recommend to have SageMath 9.4 (released in August 2021) or newer.
 
+
 ## Quickstart
 
 The easiest way to install the latest released version of the package
 is via PyPI simply by running
 
 ```sh
 sage -pip install sage-acsv
 ```
 
+The package can be run in an interactive environment in the browser
+using [Binder](https://mybinder.org/v2/gh/ACSVMath/sage_acsv/HEAD).
+
+An article serving as an introduction to version 0.1.0 of the package
+and its internals can be found on the [arXiv](https://arxiv.org/abs/2303.09603).
+
+
 ## Installation from source
 
 To install the package from the source code, either clone the git repository
 and run the command
 ```sh
 sage -pip install .
 ```
@@ -29,18 +37,19 @@
 
 Alternatively, to install the latest version of the main branch directly from
 the GitHub repository, run
 ```sh
 sage -pip install git+https://github.com/ACSVMath/sage_acsv.git
 ```
 
+
 ## Running package tests 
 
 The doctests that are added in the package can be run by executing
 ```sh
 sage -t sage_acsv
 ```
 from the root of the cloned repository. The tests are run automatically
 on every push and for any PR to the `main` branch, and compatibility with
-several different SageMath releases (the oldest currently being SageMath 9.4)
+several different SageMath releases (see [recent workflows to see all tested versions](https://github.com/ACSVMath/sage_acsv/actions/workflows/ci.yml))
 is checked.
```

### Comparing `sage_acsv-0.1.0/pyproject.toml` & `sage_acsv-0.1.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sage-acsv"
-version = "0.1.0"
+version = "0.1.1"
 description = "A SageMath package with algorithms for analytic combinatorics in several variables."
 authors = [
   "Benjamin Hackl <devel@benjamin-hackl.at>",
   "Andrew Luo <j92luo@uwaterloo.ca>",
   "Stephen Melczer <steve.melczer@uwaterloo.ca>",
   "Jesse Selover <jselover@umass.edu>",
   "Elaine Wong <elaine.wong@ricam.oeaw.ac.at>",
```

### Comparing `sage_acsv-0.1.0/sage_acsv/asymptotics.py` & `sage_acsv-0.1.1/sage_acsv/asymptotics.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,39 +1,44 @@
 """Functions for determining asymptotics of the coefficients
 of multivariate rational functions.
 """
 
 from sage.all import AA, PolynomialRing, QQ, QQbar, SR, gcd, prod, pi
 
 from sage_acsv.kronecker import _kronecker_representation
-from sage_acsv.helpers import ACSVException, RationalFunctionReduce, DetHessianWithLog
+from sage_acsv.helpers import ACSVException, RationalFunctionReduce, DetHessianWithLog, OutputFormat
 from sage_acsv.debug import Timer, acsv_logger
 
 
 MAX_MIN_CRIT_RETRIES = 3
 
 
-def diagonal_asy(F, r=None, linear_form=None, return_points=False, as_symbolic=False):
+def diagonal_asy(F, r=None, linear_form=None, return_points=False, output_format=None, as_symbolic=False):
     r"""Asymptotics in a given direction r of the multivariate rational function F.
 
     INPUT:
 
     * ``F`` -- The rational function ``G/H`` in ``d`` variables. This function is
       assumed to have a combinatorial expansion.
     * ``r`` -- A vector of length d of positive integers.
     * ``linear_form`` -- (Optional) A linear combination of the input
       variables that separates the critical point solutions.
     * ``return_points`` -- If ``True``, also returns the coordinates of
       minimal critical points. By default ``False``.
-    * ``as_symbolic`` -- If ``False`` (the default value), a list of tuples
-      of the form ``(a, n^b, pi^c, d)`` is returned, such that the `r`-diagonal
-      of `F` is the sum of `a^n n^b \pi^c d + O(a^n n^{b-1})` over these tuples.
-      Otherwise, if ``True``, the symbolic expression corresponding to the sum
-      from the other case without the error terms (i.e., a symbolic representation
-      of the asympttoic main term) is returned.
+    * ``output_format`` -- (Optional) A string or :class:`.OutputFormat` specifying
+      the way the asymptotic growth is returned. Allowed values currently are:
+      - ``"tuple"`` or ``None``, the default: the growth is returned as a list of
+        tuples of the form ``(a, n^b, pi^c, d)`` such that the `r`-diagonal of `F`
+        is the sum of ``a^n n^b pi^c d + O(a^n n^{b-1})`` over these tuples.
+      - ``"symbolic"``: the growth is returned as an expression from the symbolic
+        ring ``SR`` in the variable ``n``.
+      - ``"asymptotic"``: the growth is returned as an expression from an appropriate
+        ``AsymptoticRing`` in the variable ``n``.
+    * ``as_symbolic`` -- deprecated in favor of the equivalent
+      ``output_format="symbolic"``. Will be removed in a future release.
 
     OUTPUT:
 
     A representation of the asymptotic main term, either as a list of tuples,
     or as a symbolic expression.
 
     NOTE:
@@ -48,42 +53,85 @@
         sage: from sage_acsv import diagonal_asy
         sage: var('x,y,z,w')
         (x, y, z, w)
         sage: diagonal_asy(1/(1-x-y))
         [(4, 1/sqrt(n), 1/sqrt(pi), 1)]
         sage: diagonal_asy(1/(1-(1+x)*y), r = [1,2], return_points=True)
         ([(4, 1/sqrt(n), 1/sqrt(pi), 1)], [[1, 1/2]])
-        sage: diagonal_asy(1/(1-(x+y+z)+(3/4)*x*y*z), as_symbolic=True)
-        0.840484893481498?*24.68093482214177?^n/(pi^1.0*n^1.0)
+        sage: diagonal_asy(1/(1-(x+y+z)+(3/4)*x*y*z), output_format="symbolic")
+        0.840484893481498?*24.68093482214177?^n/(pi*n)
         sage: diagonal_asy(1/(1-(x+y+z)+(3/4)*x*y*z))
-        [(24.68093482214177?, n^(-1.0), pi^(-1.0), 0.840484893481498?)]
+        [(24.68093482214177?, 1/n, 1/pi, 0.840484893481498?)]
         sage: var('n')
         n
         sage: asy = diagonal_asy(
         ....:     1/(1 - w*(1 + x)*(1 + y)*(1 + z)*(x*y*z + y*z + y + z + 1))
         ....: )
         sage: sum([
         ....:      a.radical_expression()^n * b * c * d.radical_expression()
         ....:      for (a, b, c, d) in asy
         ....: ])
-        1/4*(12*sqrt(2) + 17)^n*sqrt(17/2*sqrt(2) + 12)/(pi^1.5*n^1.5)
+        1/4*(12*sqrt(2) + 17)^n*sqrt(17/2*sqrt(2) + 12)/(pi^(3/2)*n^(3/2))
+
+    Not specifying any ``output_format`` falls back to the default tuple
+    representation::
+
+        sage: from sage_acsv import diagonal_asy, OutputFormat
+        sage: var('x')
+        x
+        sage: diagonal_asy(1/(1 - 2*x))
+        [(2, 1, 1, 1)]
+        sage: diagonal_asy(1/(1 - 2*x), output_format="tuple")
+        [(2, 1, 1, 1)]
+
+    Passing ``"symbolic"`` lets the function return an element of the
+    symbolic ring in the variable ``n`` that describes the asymptotic growth::
+
+        sage: growth = diagonal_asy(1/(1 - 2*x), output_format="symbolic"); growth
+        2^n
+        sage: growth.parent()
+        Symbolic Ring
+
+    The argument ``"asymptotic"`` constructs an asymptotic expansion over
+    an appropriate ``AsymptoticRing`` in the variable ``n``, including the
+    appropriate error term::
+
+        sage: assume(SR.an_element() > 0)  # required to make coercions involving SR work properly
+        sage: growth = diagonal_asy(1/(1 - x - y), output_format="asymptotic"); growth
+        1/sqrt(pi)*4^n*n^(-1/2) + O(4^n*n^(-3/2))
+        sage: growth.parent()
+        Asymptotic Ring <SR^n * n^QQ * Arg_SR^n> over Symbolic Ring
 
     The function times individual steps of the algorithm, timings can
     be displayed by increasing the printed verbosity level of our debug logger::
 
         sage: import logging
         sage: from sage_acsv.debug import acsv_logger
         sage: acsv_logger.setLevel(logging.INFO)
         sage: diagonal_asy(1/(1 - x - y))
         INFO:sage_acsv:... Executed Kronecker in ... seconds.
         INFO:sage_acsv:... Executed Minimal Points in ... seconds.
         INFO:sage_acsv:... Executed Final Asymptotics in ... seconds.
         [(4, 1/sqrt(n), 1/sqrt(pi), 1)]
         sage: acsv_logger.setLevel(logging.WARNING)
 
+
+    Tests:
+
+    Check that passing a non-supported ``output_format`` errors out::
+
+        sage: diagonal_asy(1/(1 - x - y), output_format='hello world')
+        Traceback (most recent call last):
+        ...
+        ValueError: 'hello world' is not a valid OutputFormat
+        sage: diagonal_asy(1/(1 - x - y), output_format=42)
+        Traceback (most recent call last):
+        ...
+        ValueError: 42 is not a valid OutputFormat
+
     """
     G, H = F.numerator(), F.denominator()
     if r is None:
         n = len(H.variables())
         r = [1 for _ in range(n)]
 
     # Initialize variables
@@ -143,25 +191,61 @@
     # Compute constants at contributing singularities
     asm_quantities = [
         [QQbar(q.subs([SR(v) == V for (v, V) in zip(vs, cp)])) for q in [A, B, C]]
         for cp in min_crit_pts
     ]
     n = SR.var('n')
     asm_vals = [
-        (c, n**((1-d)/2), pi**((1-d)/2), a * b.sqrt())
+        (c, QQ(1 - d)/2, a * b.sqrt())
         for (a, b, c) in asm_quantities
     ]
     timer.checkpoint("Final Asymptotics")
 
-    result = asm_vals
     if as_symbolic:
-        result = sum([a**n * b * c * d for (a, b, c, d) in result])
+        from warnings import warn
 
+        warn(
+            "The as_symbolic argument has been deprecated in favor of output_format='symbolic' "
+            "and will be removed in a future release.",
+            DeprecationWarning,
+            stacklevel=2,
+        )
+        if output_format is None:
+            output_format = OutputFormat.SYMBOLIC
+
+    if output_format is None:
+        output_format = OutputFormat.TUPLE
+    else:
+        output_format = OutputFormat(output_format)
+
+    if output_format in (OutputFormat.TUPLE, OutputFormat.SYMBOLIC):
+        n = SR.var('n')
+        result = [
+            (base, n**exponent, pi**exponent, constant)
+            for (base, exponent, constant) in asm_vals
+        ]
+        if output_format == OutputFormat.SYMBOLIC:
+            result = sum([a**n * b * c * d for (a, b, c, d) in result])
+
+    elif output_format == OutputFormat.ASYMPTOTIC:
+        from sage.all import AsymptoticRing
+        AR = AsymptoticRing('SR^n * n^QQ', SR)
+        n = AR.gen()
+        result = sum([
+            base**n * n**exponent * pi**exponent * constant 
+            + (base**n * n**(exponent - 1)).O()
+            for (base, exponent, constant) in asm_vals
+        ])
+
+    else:
+        raise NotImplementedError(f"Missing implementation for {output_format}")
+    
     if return_points:
         return result, min_crit_pts
+
     return result
 
 
 def MinimalCriticalCombinatorial(G, H, variables, r=None, linear_form=None):
     r"""Compute minimal critical points of a combinatorial multivariate
     rational function F=G/H admitting a finite number of critical points.
```

### Comparing `sage_acsv-0.1.0/sage_acsv/debug.py` & `sage_acsv-0.1.1/sage_acsv/debug.py`

 * *Files identical despite different names*

### Comparing `sage_acsv-0.1.0/sage_acsv/helpers.py` & `sage_acsv-0.1.1/sage_acsv/helpers.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,26 @@
+from enum import Enum
+
 from sage.all import QQ, ceil, gcd, matrix, randint
 
 
+class OutputFormat(Enum):
+    """Output options for displaying the asymptotic behavior determined
+    by :func:`.diagonal_asy`.
+
+    See also:
+
+    - :func:`.diagonal_asy`
+    """
+    ASYMPTOTIC = "asymptotic"
+    SYMBOLIC = "symbolic"
+    TUPLE = "tuple"
+    
+
+
 def RationalFunctionReduce(G, H):
     r"""Reduction of G and H by dividing out their GCD.
 
     INPUT:
 
     * ``G``, ``H`` -- polynomials
```

### Comparing `sage_acsv-0.1.0/sage_acsv/kronecker.py` & `sage_acsv-0.1.1/sage_acsv/kronecker.py`

 * *Files identical despite different names*

### Comparing `sage_acsv-0.1.0/PKG-INFO` & `sage_acsv-0.1.1/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sage-acsv
-Version: 0.1.0
+Version: 0.1.1
 Summary: A SageMath package with algorithms for analytic combinatorics in several variables.
 Home-page: https://github.com/ACSVMath/sage_acsv
 License: MIT
 Author: Benjamin Hackl
 Author-email: devel@benjamin-hackl.at
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: MIT License
@@ -20,23 +20,31 @@
 
 This repository hosts the implementation of a SageMath package
 containing algorithms for analytic combinatorics in several variables.
 
 The package works with any reasonably recent version of SageMath, we
 recommend to have SageMath 9.4 (released in August 2021) or newer.
 
+
 ## Quickstart
 
 The easiest way to install the latest released version of the package
 is via PyPI simply by running
 
 ```sh
 sage -pip install sage-acsv
 ```
 
+The package can be run in an interactive environment in the browser
+using [Binder](https://mybinder.org/v2/gh/ACSVMath/sage_acsv/HEAD).
+
+An article serving as an introduction to version 0.1.0 of the package
+and its internals can be found on the [arXiv](https://arxiv.org/abs/2303.09603).
+
+
 ## Installation from source
 
 To install the package from the source code, either clone the git repository
 and run the command
 ```sh
 sage -pip install .
 ```
@@ -47,19 +55,20 @@
 
 Alternatively, to install the latest version of the main branch directly from
 the GitHub repository, run
 ```sh
 sage -pip install git+https://github.com/ACSVMath/sage_acsv.git
 ```
 
+
 ## Running package tests 
 
 The doctests that are added in the package can be run by executing
 ```sh
 sage -t sage_acsv
 ```
 from the root of the cloned repository. The tests are run automatically
 on every push and for any PR to the `main` branch, and compatibility with
-several different SageMath releases (the oldest currently being SageMath 9.4)
+several different SageMath releases (see [recent workflows to see all tested versions](https://github.com/ACSVMath/sage_acsv/actions/workflows/ci.yml))
 is checked.
```


# Comparing `tmp/gym_cas-0.0.5.tar.gz` & `tmp/gym_cas-0.0.6.tar.gz`

## Comparing `gym_cas-0.0.5.tar` & `gym_cas-0.0.6.tar`

### file list

```diff
@@ -1,19 +1,20 @@
--rw-r--r--   0        0        0      258 2020-02-02 00:00:00.000000 gym_cas-0.0.5/bitbucket-pipelines.yml
--rw-r--r--   0        0        0       39 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.pytest_cache/.gitignore
--rw-r--r--   0        0        0      191 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.pytest_cache/CACHEDIR.TAG
--rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.pytest_cache/README.md
--rw-r--r--   0        0        0        2 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.pytest_cache/v/cache/lastfailed
--rw-r--r--   0        0        0      336 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.pytest_cache/v/cache/nodeids
--rw-r--r--   0        0        0        2 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.pytest_cache/v/cache/stepwise
--rw-r--r--   0        0        0      117 2020-02-02 00:00:00.000000 gym_cas-0.0.5/src/gym_cas/__about__.py
--rw-r--r--   0        0        0      299 2020-02-02 00:00:00.000000 gym_cas-0.0.5/src/gym_cas/__init__.py
--rw-r--r--   0        0        0     1838 2020-02-02 00:00:00.000000 gym_cas-0.0.5/src/gym_cas/trigonometry.py
--rw-r--r--   0        0        0       94 2020-02-02 00:00:00.000000 gym_cas-0.0.5/tests/__init__.py
--rw-r--r--   0        0        0      251 2020-02-02 00:00:00.000000 gym_cas-0.0.5/tests/test_abc.py
--rw-r--r--   0        0        0     1328 2020-02-02 00:00:00.000000 gym_cas-0.0.5/tests/test_trigonometry.py
--rw-r--r--   0        0        0      247 2020-02-02 00:00:00.000000 gym_cas-0.0.5/.gitignore
--rw-r--r--   0        0        0     1092 2020-02-02 00:00:00.000000 gym_cas-0.0.5/LICENSE.txt
--rw-r--r--   0        0        0      441 2020-02-02 00:00:00.000000 gym_cas-0.0.5/README.md
--rw-r--r--   0        0        0      793 2020-02-02 00:00:00.000000 gym_cas-0.0.5/hatch.toml
--rw-r--r--   0        0        0     2318 2020-02-02 00:00:00.000000 gym_cas-0.0.5/pyproject.toml
--rw-r--r--   0        0        0     1121 2020-02-02 00:00:00.000000 gym_cas-0.0.5/PKG-INFO
+-rw-r--r--   0        0        0      258 2020-02-02 00:00:00.000000 gym_cas-0.0.6/bitbucket-pipelines.yml
+-rw-r--r--   0        0        0       39 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.pytest_cache/.gitignore
+-rw-r--r--   0        0        0      191 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.pytest_cache/CACHEDIR.TAG
+-rw-r--r--   0        0        0      310 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.pytest_cache/README.md
+-rw-r--r--   0        0        0        2 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.pytest_cache/v/cache/lastfailed
+-rw-r--r--   0        0        0      537 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.pytest_cache/v/cache/nodeids
+-rw-r--r--   0        0        0        2 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.pytest_cache/v/cache/stepwise
+-rw-r--r--   0        0        0      117 2020-02-02 00:00:00.000000 gym_cas-0.0.6/src/gym_cas/__about__.py
+-rw-r--r--   0        0        0      299 2020-02-02 00:00:00.000000 gym_cas-0.0.6/src/gym_cas/__init__.py
+-rw-r--r--   0        0        0     1939 2020-02-02 00:00:00.000000 gym_cas-0.0.6/src/gym_cas/trigonometry.py
+-rw-r--r--   0        0        0       94 2020-02-02 00:00:00.000000 gym_cas-0.0.6/tests/__init__.py
+-rw-r--r--   0        0        0      190 2020-02-02 00:00:00.000000 gym_cas-0.0.6/tests/cheatsheet_examples.py
+-rw-r--r--   0        0        0      251 2020-02-02 00:00:00.000000 gym_cas-0.0.6/tests/test_abc.py
+-rw-r--r--   0        0        0     1328 2020-02-02 00:00:00.000000 gym_cas-0.0.6/tests/test_trigonometry.py
+-rw-r--r--   0        0        0      247 2020-02-02 00:00:00.000000 gym_cas-0.0.6/.gitignore
+-rw-r--r--   0        0        0     1092 2020-02-02 00:00:00.000000 gym_cas-0.0.6/LICENSE.txt
+-rw-r--r--   0        0        0      894 2020-02-02 00:00:00.000000 gym_cas-0.0.6/README.md
+-rw-r--r--   0        0        0      793 2020-02-02 00:00:00.000000 gym_cas-0.0.6/hatch.toml
+-rw-r--r--   0        0        0     2318 2020-02-02 00:00:00.000000 gym_cas-0.0.6/pyproject.toml
+-rw-r--r--   0        0        0     1556 2020-02-02 00:00:00.000000 gym_cas-0.0.6/PKG-INFO
```

### Comparing `gym_cas-0.0.5/src/gym_cas/trigonometry.py` & `gym_cas-0.0.6/src/gym_cas/trigonometry.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,58 +1,58 @@
-from sympy import cos, sin, tan, acos, asin, atan, pi, N
+from sympy import cos, sin, tan, acos, asin, atan, pi, Symbol
 
-def Sin(v: float):
+def Sin(v: float | Symbol):
     '''
     Hjælpefunktion til at udregne sinus til vinklen i grader.
 
     Brug sin fra sympy hvis der skal arbejdes med udtrykket (fx differentieres).
     '''
-    return N(sin(v / 180 * pi))
+    return (sin(v / 180 * pi)).evalf()
 
-def Cos(v: float):
+def Cos(v: float | Symbol):
     '''
     Hjælpefunktion til at udregne cosinus til vinklen i grader.
 
     Brug cos fra sympy hvis der skal arbejdes med udtrykket (fx differentieres).
     '''
-    return N(cos(v / 180 * pi))
+    return (cos(v / 180 * pi)).evalf()
 
 
-def Tan(v: float):
+def Tan(v: float | Symbol):
     '''
     Hjælpefunktion til at udregne tangens til vinklen i grader.
 
     Brug tan fra sympy hvis der skal arbejdes med udtrykket (fx differentieres).
     '''
-    return N(tan(v / 180 * pi))
+    return (tan(v / 180 * pi)).evalf()
 
-def aSin(val: float):
+def aSin(val: float | Symbol):
     '''
     Hjælpefunktion til at udregne invers sinus til sinusværdien.
 
     Brug asin fra sympy hvis der skal arbejdes med udtrykket (fx differentieres).
     '''
-    return N(asin(val) / pi * 180)
+    return (asin(val) / pi * 180).evalf()
 
-def aCos(val: float):
+def aCos(val: float | Symbol):
     '''
     Hjælpefunktion til at udregne invers cosinus til cosinusværdien.
 
     Brug acos fra sympy hvis der skal arbejdes med udtrykket (fx differentieres).
     '''
-    return N(acos(val) / pi * 180)
+    return (acos(val) / pi * 180).evalf()
 
 
-def aTan(val: float):
+def aTan(val: float | Symbol):
     '''
     Hjælpefunktion til at udregne invers tangens til tangensværdien.
 
     Brug atan fra sympy hvis der skal arbejdes med udtrykket (fx differentieres).
     '''
-    return N(atan(val) / pi * 180)
+    return (atan(val) / pi * 180).evalf()
 
 if __name__ == "__main__":
     print(Sin(90))
     print(Sin(135))
     print(Sin(180))
     print(Cos(90))
     print(Cos(135))
```

### Comparing `gym_cas-0.0.5/tests/test_trigonometry.py` & `gym_cas-0.0.6/tests/test_trigonometry.py`

 * *Files identical despite different names*

### Comparing `gym_cas-0.0.5/LICENSE.txt` & `gym_cas-0.0.6/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `gym_cas-0.0.5/hatch.toml` & `gym_cas-0.0.6/hatch.toml`

 * *Files identical despite different names*

### Comparing `gym_cas-0.0.5/pyproject.toml` & `gym_cas-0.0.6/pyproject.toml`

 * *Files identical despite different names*


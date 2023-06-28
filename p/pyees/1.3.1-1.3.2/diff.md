# Comparing `tmp/pyees-1.3.1.tar.gz` & `tmp/pyees-1.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyees-1.3.1.tar", last modified: Fri Jun 16 06:49:58 2023, max compression
+gzip compressed data, was "pyees-1.3.2.tar", last modified: Wed Jun 28 06:47:35 2023, max compression
```

## Comparing `pyees-1.3.1.tar` & `pyees-1.3.2.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxrwxrwx   0        0        0        0 2023-06-16 06:49:58.027954 pyees-1.3.1/
--rw-rw-rw-   0        0        0     1085 2022-02-05 11:46:00.000000 pyees-1.3.1/LICENSE.txt
--rw-rw-rw-   0        0        0      768 2023-06-16 06:49:58.043579 pyees-1.3.1/PKG-INFO
--rw-rw-rw-   0        0        0     1017 2023-03-10 10:19:19.000000 pyees-1.3.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-16 06:49:57.809320 pyees-1.3.1/pyees/
--rw-rw-rw-   0        0        0      320 2023-05-12 12:42:57.000000 pyees-1.3.1/pyees/__init__.py
--rw-rw-rw-   0        0        0    12841 2023-05-16 05:19:59.000000 pyees-1.3.1/pyees/fit.py
--rw-rw-rw-   0        0        0      811 2023-04-03 12:11:18.000000 pyees-1.3.1/pyees/profilePyees.py
--rw-rw-rw-   0        0        0     9126 2023-05-11 09:38:14.000000 pyees-1.3.1/pyees/prop.py
--rw-rw-rw-   0        0        0    17741 2023-06-16 06:49:37.000000 pyees-1.3.1/pyees/sheet.py
--rw-rw-rw-   0        0        0    10197 2023-05-16 06:21:10.000000 pyees-1.3.1/pyees/solve.py
--rw-rw-rw-   0        0        0     1406 2022-03-24 20:23:42.000000 pyees-1.3.1/pyees/stackOverflowODR.py
--rw-rw-rw-   0        0        0     7669 2023-04-27 10:39:41.000000 pyees-1.3.1/pyees/testFit.py
--rw-rw-rw-   0        0        0    12431 2023-05-11 09:11:30.000000 pyees-1.3.1/pyees/testProp.py
--rw-rw-rw-   0        0        0     1044 2023-05-12 12:42:48.000000 pyees-1.3.1/pyees/testPyees.py
--rw-rw-rw-   0        0        0    15668 2023-05-12 12:42:26.000000 pyees-1.3.1/pyees/testSheet.py
--rw-rw-rw-   0        0        0    20218 2023-04-05 08:10:48.000000 pyees-1.3.1/pyees/testSolve.py
--rw-rw-rw-   0        0        0     9094 2023-05-12 06:37:13.000000 pyees-1.3.1/pyees/testUnit.py
--rw-rw-rw-   0        0        0    82221 2023-06-15 11:40:52.000000 pyees-1.3.1/pyees/testVariable.py
--rw-rw-rw-   0        0        0    44623 2023-06-15 11:34:25.000000 pyees-1.3.1/pyees/unit.py
--rw-rw-rw-   0        0        0    35132 2023-06-15 11:40:28.000000 pyees-1.3.1/pyees/variable.py
-drwxrwxrwx   0        0        0        0 2023-06-16 06:49:57.994263 pyees-1.3.1/pyees.egg-info/
--rw-rw-rw-   0        0        0      768 2023-06-16 06:49:56.000000 pyees-1.3.1/pyees.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      471 2023-06-16 06:49:56.000000 pyees-1.3.1/pyees.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-16 06:49:56.000000 pyees-1.3.1/pyees.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       40 2023-06-16 06:49:56.000000 pyees-1.3.1/pyees.egg-info/requires.txt
--rw-rw-rw-   0        0        0        6 2023-06-16 06:49:56.000000 pyees-1.3.1/pyees.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       86 2023-06-16 06:49:58.074831 pyees-1.3.1/setup.cfg
--rw-rw-rw-   0        0        0     1224 2023-06-16 06:49:50.000000 pyees-1.3.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:47:35.370594 pyees-1.3.2/
+-rw-rw-rw-   0        0        0     1085 2022-02-05 11:46:00.000000 pyees-1.3.2/LICENSE.txt
+-rw-rw-rw-   0        0        0      768 2023-06-28 06:47:35.386219 pyees-1.3.2/PKG-INFO
+-rw-rw-rw-   0        0        0     1017 2023-03-10 10:19:19.000000 pyees-1.3.2/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 06:47:35.134377 pyees-1.3.2/pyees/
+-rw-rw-rw-   0        0        0      320 2023-05-12 12:42:57.000000 pyees-1.3.2/pyees/__init__.py
+-rw-rw-rw-   0        0        0    12847 2023-06-28 06:38:17.000000 pyees-1.3.2/pyees/fit.py
+-rw-rw-rw-   0        0        0      811 2023-04-03 12:11:18.000000 pyees-1.3.2/pyees/profilePyees.py
+-rw-rw-rw-   0        0        0     9126 2023-05-11 09:38:14.000000 pyees-1.3.2/pyees/prop.py
+-rw-rw-rw-   0        0        0    17903 2023-06-28 06:44:48.000000 pyees-1.3.2/pyees/sheet.py
+-rw-rw-rw-   0        0        0    10197 2023-05-16 06:21:10.000000 pyees-1.3.2/pyees/solve.py
+-rw-rw-rw-   0        0        0     1406 2022-03-24 20:23:42.000000 pyees-1.3.2/pyees/stackOverflowODR.py
+-rw-rw-rw-   0        0        0     7669 2023-06-28 06:38:39.000000 pyees-1.3.2/pyees/testFit.py
+-rw-rw-rw-   0        0        0    12431 2023-05-11 09:11:30.000000 pyees-1.3.2/pyees/testProp.py
+-rw-rw-rw-   0        0        0     1044 2023-05-12 12:42:48.000000 pyees-1.3.2/pyees/testPyees.py
+-rw-rw-rw-   0        0        0    16959 2023-06-28 06:46:30.000000 pyees-1.3.2/pyees/testSheet.py
+-rw-rw-rw-   0        0        0    20218 2023-04-05 08:10:48.000000 pyees-1.3.2/pyees/testSolve.py
+-rw-rw-rw-   0        0        0     9094 2023-05-12 06:37:13.000000 pyees-1.3.2/pyees/testUnit.py
+-rw-rw-rw-   0        0        0    83073 2023-06-28 06:43:51.000000 pyees-1.3.2/pyees/testVariable.py
+-rw-rw-rw-   0        0        0    44623 2023-06-15 11:34:25.000000 pyees-1.3.2/pyees/unit.py
+-rw-rw-rw-   0        0        0    35206 2023-06-28 06:43:10.000000 pyees-1.3.2/pyees/variable.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:47:35.338288 pyees-1.3.2/pyees.egg-info/
+-rw-rw-rw-   0        0        0      768 2023-06-28 06:47:33.000000 pyees-1.3.2/pyees.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      471 2023-06-28 06:47:33.000000 pyees-1.3.2/pyees.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:47:33.000000 pyees-1.3.2/pyees.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       40 2023-06-28 06:47:33.000000 pyees-1.3.2/pyees.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 06:47:33.000000 pyees-1.3.2/pyees.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       86 2023-06-28 06:47:35.417468 pyees-1.3.2/setup.cfg
+-rw-rw-rw-   0        0        0     1224 2023-06-28 06:47:26.000000 pyees-1.3.2/setup.py
```

### Comparing `pyees-1.3.1/LICENSE.txt` & `pyees-1.3.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/PKG-INFO` & `pyees-1.3.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyees
-Version: 1.3.1
+Version: 1.3.2
 Summary: EES but for python. Pyees can be used do perform uncertanty (error) propagation. Furthermore, it can solve nonlinear systems of equations and look up material properties.
 Home-page: https://github.com/jacobv95/pyees
 Download-URL: https://github.com/jacobv95/pyees/archive/refs/tags/v1.0.tar.gz
 Author: Jacob Vestergaard
 Author-email: jacobvestergaard95@gmail.com
 License: MIT
 Keywords: python,data processing,uncertanty,EES
```

### Comparing `pyees-1.3.1/README.md` & `pyees-1.3.2/README.md`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/fit.py` & `pyees-1.3.2/pyees/fit.py`

 * *Files 0% similar despite different names*

```diff
@@ -76,15 +76,15 @@
             self.r_squared = 1
         np.seterr('warn')
 
     def __str__(self):
         return self.func_name() + ',  ' + self._r2_name()
 
     def _r2_name(self):
-        return f'$R^2 = {self.r_squared:.5f}$'
+        return f'$R^2 = {self.r_squared.value:.5f}$'
 
     def scatter(self, ax, label=True, showUncert=True, **kwargs):
 
         if all(self.xUncert == 0) and all(self.yUncert == 0):
             showUncert = False
 
         # parse label
```

### Comparing `pyees-1.3.1/pyees/profilePyees.py` & `pyees-1.3.2/pyees/profilePyees.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/prop.py` & `pyees-1.3.2/pyees/prop.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/sheet.py` & `pyees-1.3.2/pyees/sheet.py`

 * *Files 1% similar despite different names*

```diff
@@ -440,7 +440,11 @@
         variables = []
         for _, item in self.__dict__.items():
             if isinstance(item, scalarVariable):
                 variables.append(item)
         
         return iter(variables)
     
+    def pop(self, index = -1):
+        for key, item in self.__dict__.items():
+            if isinstance(item, scalarVariable):
+                item.pop(index)
```

### Comparing `pyees-1.3.1/pyees/solve.py` & `pyees-1.3.2/pyees/solve.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/stackOverflowODR.py` & `pyees-1.3.2/pyees/stackOverflowODR.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/testFit.py` & `pyees-1.3.2/pyees/testFit.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/testProp.py` & `pyees-1.3.2/pyees/testProp.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/testPyees.py` & `pyees-1.3.2/pyees/testPyees.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/testSheet.py` & `pyees-1.3.2/pyees/testSheet.py`

 * *Files 6% similar despite different names*

```diff
@@ -261,12 +261,37 @@
         np.testing.assert_array_equal(sheets[1].D.value, [11,12,13,14,11,12,13,14])
         np.testing.assert_array_equal(sheets[1].D.uncert,  np.array([11,12,13,14,11,12,13,14])/100)
         self.assertEqual(sheets[1].D.unit, 'L')
         np.testing.assert_array_equal(sheets[1].E.value, [15,16,17,18,15,16,17,18])
         np.testing.assert_array_equal(sheets[1].E.uncert, np.array([15,16,17,18,15,16,17,18])/100)
         self.assertEqual(sheets[1].E.unit, 'C')
         
+    def pop(self):
+
+        dat = sheetsFromFile('testData/data1.xlsx', 'A-B')
+        dat.pop(0)
+        np.testing.assert_array_equal(dat.A.value, [2, 3, 4, 5])
+        self.assertEqual(str(dat.A.unit), 'L/min')
+        np.testing.assert_array_equal(dat.A.uncert, [0, 0, 0, 0])
+        np.testing.assert_array_equal(dat.B.value, [6, 7, 8, 9])
+        self.assertEqual(str(dat.B.unit), 'mA')
+        np.testing.assert_array_equal(dat.B.uncert, [0, 0, 0, 0])
         
+        dat = sheetsFromFile('testData/data1.xlsx', 'A-B')
+        dat.pop(3)
+        np.testing.assert_array_equal(dat.A.value, [1, 2, 3, 5])
+        self.assertEqual(str(dat.A.unit), 'L/min')
+        np.testing.assert_array_equal(dat.A.uncert, [0, 0, 0, 0])
+        np.testing.assert_array_equal(dat.B.value, [5, 6, 7, 9])
+        self.assertEqual(str(dat.B.unit), 'mA')
+        np.testing.assert_array_equal(dat.B.uncert, [0, 0, 0, 0])
         
+        dat.pop(2)
+        np.testing.assert_array_equal(dat.A.value, [1, 2, 5])
+        self.assertEqual(str(dat.A.unit), 'L/min')
+        np.testing.assert_array_equal(dat.A.uncert, [0, 0, 0])
+        np.testing.assert_array_equal(dat.B.value, [5, 6, 9])
+        self.assertEqual(str(dat.B.unit), 'mA')
+        np.testing.assert_array_equal(dat.B.uncert, [0, 0, 0])
         
 if __name__ == '__main__':
     unittest.main()
```

### Comparing `pyees-1.3.1/pyees/testSolve.py` & `pyees-1.3.2/pyees/testSolve.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/testUnit.py` & `pyees-1.3.2/pyees/testUnit.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/testVariable.py` & `pyees-1.3.2/pyees/testVariable.py`

 * *Files 1% similar despite different names*

```diff
@@ -1883,13 +1883,31 @@
         
 
         a = variable([20,30], 'C')
         c = np.mean(a)
         self.assertEqual(c.value, 25)
         self.assertEqual(c.unit, 'C')
                 
+    def testPop(self):
         
+        A_vec = variable([12.3, 54.3, 91.3], 'L/min', uncert=[2.6, 5.4, 10.56])
+        A_vec.pop(0)
+        np.testing.assert_equal(A_vec.value, [54.3, 91.3])
+        self.assertEqual(A_vec.unit,'L/min')
+        np.testing.assert_equal(A_vec.uncert, [5.4, 10.56])
+        
+        A_vec = variable([12.3, 54.3, 91.3], 'L/min', uncert=[2.6, 5.4, 10.56])
+        A_vec.pop(1)
+        np.testing.assert_equal(A_vec.value, [12.3, 91.3])
+        self.assertEqual(A_vec.unit,'L/min')
+        np.testing.assert_equal(A_vec.uncert, [2.6, 10.56])
+        
+        A_vec = variable([12.3, 54.3, 91.3], 'L/min', uncert=[2.6, 5.4, 10.56])
+        A_vec.pop(2)
+        np.testing.assert_equal(A_vec.value, [12.3, 54.3])
+        self.assertEqual(A_vec.unit,'L/min')
+        np.testing.assert_equal(A_vec.uncert, [2.6, 5.4])
         
 
 if __name__ == '__main__':
     unittest.main()
```

### Comparing `pyees-1.3.1/pyees/unit.py` & `pyees-1.3.2/pyees/unit.py`

 * *Files identical despite different names*

### Comparing `pyees-1.3.1/pyees/variable.py` & `pyees-1.3.2/pyees/variable.py`

 * *Files 0% similar despite different names*

```diff
@@ -963,14 +963,17 @@
         if self.n < len(self):
             out = self.scalarVariables[self.n]
             self.n += 1
             return out
 
         raise StopIteration
 
+    def pop(self,index = -1):
+        self.scalarVariables.pop(index)
+
 def variable(value, unit = '', uncert = None, nDigits = 3):
     # store the value and the uncertaty
     def evaluateInput(input):
         if input is None:
             return input
         if isinstance(input, np.ndarray):
             return input
```

### Comparing `pyees-1.3.1/pyees.egg-info/PKG-INFO` & `pyees-1.3.2/pyees.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyees
-Version: 1.3.1
+Version: 1.3.2
 Summary: EES but for python. Pyees can be used do perform uncertanty (error) propagation. Furthermore, it can solve nonlinear systems of equations and look up material properties.
 Home-page: https://github.com/jacobv95/pyees
 Download-URL: https://github.com/jacobv95/pyees/archive/refs/tags/v1.0.tar.gz
 Author: Jacob Vestergaard
 Author-email: jacobvestergaard95@gmail.com
 License: MIT
 Keywords: python,data processing,uncertanty,EES
```

### Comparing `pyees-1.3.1/setup.py` & `pyees-1.3.2/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from distutils.core import setup
 setup(
     name='pyees',
     packages=['pyees'],
-    version='1.3.1',
+    version='1.3.2',
     license='MIT',
     description='EES but for python. Pyees can be used do perform uncertanty (error) propagation. Furthermore, it can solve nonlinear systems of equations and look up material properties.',
     author='Jacob Vestergaard',
     author_email='jacobvestergaard95@gmail.com',
     url='https://github.com/jacobv95/pyees',
     download_url='https://github.com/jacobv95/pyees/archive/refs/tags/v1.0.tar.gz',
     keywords=['python', 'data processing', 'uncertanty', 'EES'],
```


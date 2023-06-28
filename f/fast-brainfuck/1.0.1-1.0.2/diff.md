# Comparing `tmp/fast-brainfuck-1.0.1.tar.gz` & `tmp/fast-brainfuck-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\fast-brainfuck-1.0.1.tar", last modified: Tue Jun 27 14:36:17 2023, max compression
+gzip compressed data, was "dist\fast-brainfuck-1.0.2.tar", last modified: Wed Jun 28 01:47:38 2023, max compression
```

## Comparing `fast-brainfuck-1.0.1.tar` & `fast-brainfuck-1.0.2.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 14:36:17.789626 fast-brainfuck-1.0.1/
--rw-rw-rw-   0        0        0     3143 2023-06-27 14:36:17.789626 fast-brainfuck-1.0.1/PKG-INFO
--rw-rw-rw-   0        0        0     1936 2023-06-27 14:27:06.000000 fast-brainfuck-1.0.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 14:36:17.789626 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/
--rw-rw-rw-   0        0        0     3143 2023-06-27 14:36:17.000000 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      258 2023-06-27 14:36:17.000000 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 14:36:17.000000 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       49 2023-06-27 14:36:17.000000 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       20 2023-06-27 14:36:17.000000 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-27 14:36:17.000000 fast-brainfuck-1.0.1/fast_brainfuck.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     3950 2023-06-27 13:41:59.000000 fast-brainfuck-1.0.1/fastbf.py
--rw-rw-rw-   0        0        0       42 2023-06-27 14:36:17.789626 fast-brainfuck-1.0.1/setup.cfg
--rw-rw-rw-   0        0        0     1145 2023-06-27 14:36:09.000000 fast-brainfuck-1.0.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/PKG-INFO
+-rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.2/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      258 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     4320 2023-06-28 01:38:20.000000 fast-brainfuck-1.0.2/fastbf.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/setup.cfg
+-rw-rw-rw-   0        0        0     1145 2023-06-28 01:41:22.000000 fast-brainfuck-1.0.2/setup.py
```

### Comparing `fast-brainfuck-1.0.1/PKG-INFO` & `fast-brainfuck-1.0.2/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.1
+Version: 1.0.2
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
         
@@ -46,15 +46,22 @@
         ```
         to run the brainfuck in your script (which **CAN** be frozen into executables).
         
         Note that fast-brainfuck does **NOT** clean up the temporary files it creates. You have to manually delete them if you want.
         
         fast-brainfuck can run on **CPython** or **PyPy**.
         
-        PS: This package consists of only one Python file less than 4KB.
+        #### ImportError: xxx
+        If you encountered this error when using this package in PyPy in Windows, that means your username has non-ASCII characters.
+        You can run
+        ```python
+        import os
+        os.environ['TMP']='C:\\Somedir'
+        ```
+        before using fast-brainfuck to fix the error.
 Keywords: brainfuck
 Platform: UNKNOWN
 Classifier: Programming Language :: C++
 Classifier: Operating System :: Microsoft :: Windows
 Classifier: Operating System :: Unix
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: Implementation :: CPython
```

### Comparing `fast-brainfuck-1.0.1/README.md` & `fast-brainfuck-1.0.2/README.md`

 * *Files 13% similar despite different names*

```diff
@@ -40,8 +40,15 @@
 ```
 to run the brainfuck in your script (which **CAN** be frozen into executables).
 
 Note that fast-brainfuck does **NOT** clean up the temporary files it creates. You have to manually delete them if you want.
 
 fast-brainfuck can run on **CPython** or **PyPy**.
 
-PS: This package consists of only one Python file less than 4KB.
+#### ImportError: xxx
+If you encountered this error when using this package in PyPy in Windows, that means your username has non-ASCII characters.
+You can run
+```python
+import os
+os.environ['TMP']='C:\\Somedir'
+```
+before using fast-brainfuck to fix the error.
```

### Comparing `fast-brainfuck-1.0.1/fast_brainfuck.egg-info/PKG-INFO` & `fast-brainfuck-1.0.2/fast_brainfuck.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.1
+Version: 1.0.2
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
         
@@ -46,15 +46,22 @@
         ```
         to run the brainfuck in your script (which **CAN** be frozen into executables).
         
         Note that fast-brainfuck does **NOT** clean up the temporary files it creates. You have to manually delete them if you want.
         
         fast-brainfuck can run on **CPython** or **PyPy**.
         
-        PS: This package consists of only one Python file less than 4KB.
+        #### ImportError: xxx
+        If you encountered this error when using this package in PyPy in Windows, that means your username has non-ASCII characters.
+        You can run
+        ```python
+        import os
+        os.environ['TMP']='C:\\Somedir'
+        ```
+        before using fast-brainfuck to fix the error.
 Keywords: brainfuck
 Platform: UNKNOWN
 Classifier: Programming Language :: C++
 Classifier: Operating System :: Microsoft :: Windows
 Classifier: Operating System :: Unix
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: Implementation :: CPython
```

### Comparing `fast-brainfuck-1.0.1/fastbf.py` & `fast-brainfuck-1.0.2/fastbf.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,7 +1,10 @@
+"""
+fast-brainfuck main module
+"""
 import platform,os
 import sys
 from random import choice
 from setuptools import setup,Extension
 from pybind11 import get_include
 from subprocess import run,PIPE
 def random_string():
@@ -64,18 +67,19 @@
         language='c++',
         include_dirs=[get_include()],
         extra_compile_args=['-std=c++11']
     )
     setup(
         ext_modules=[_foo]
     )
-def brainfuck_to_function(brainfuck):
+def brainfuck_to_function(brainfuck,cellsize=300000):
     """
     Converts brainfuck into a fast Python function.
     :param brainfuck: Brainfuck code
+    :param cellsize: Number of cells, default is 300000.
     :return: A function, call it with no arguments to run the brainfuck code
     """
     cwd=os.getcwd()
     os.chdir(_tmp())
     dn=random_string()
     os.mkdir(dn)
     os.chdir(dn)
@@ -89,15 +93,15 @@
     include_dirs=[get_include()],
     extra_compile_args=['-std=c++11']
 )
 setup(
     ext_modules=[_foo]
 )
     '''
-    cpp=brainfuck_to_cpp(brainfuck)
+    cpp=brainfuck_to_cpp(brainfuck,cellsize)
     wrap=wrap_cpp(cpp)
     with open('_foo.cpp','w') as f:
         f.write(wrap)
     with open('setup.py','w') as f:
         f.write(distcode)
     python=sys.executable
     run(
@@ -109,30 +113,33 @@
         ],shell=True,stdout=PIPE,stderr=PIPE
     )
     sys.path.append(os.path.join(_tmp(),dn))
     foo=__import__('_foo')
     os.chdir(cwd)
     sys.path.pop()
     return foo.run
-def dist_brainfuck(brainfuck,modulename='foo'):
+def dist_brainfuck(brainfuck,modulename='foo',cellsize=300000):
     """
     Distribute brainfuck code into a python module.
     :param brainfuck: Brainfuck code
     :param modulename: Python module name.
+    :param cellsize: Number of cells, default is 300000.
     :return: None
     """
     with open(modulename+'.py','w') as f:
         f.write('from ._foo import *')
-    cpp = brainfuck_to_cpp(brainfuck)
+    cpp = brainfuck_to_cpp(brainfuck,cellsize)
     wrap = wrap_cpp(cpp)
     dist_cpp(wrap)
 def _fastbf_inter():
     from argparse import ArgumentParser
     ap=ArgumentParser(description='FastBF brainfuck interpreter')
     ap.add_argument('filename',help='Input brainfuck file name')
+    ap.add_argument('-c','--cellsize',help='Number of cells, default is 300000.',default='300000')
     args=ap.parse_args()
     with open(args.filename) as f:
         code=f.read()
-    func=brainfuck_to_function(code)
+    func=brainfuck_to_function(code,args.cellsize)
     func()
+__all__=['brainfuck_to_function','dist_brainfuck']
 if __name__=='__main__':
     _fastbf_inter()
```

### Comparing `fast-brainfuck-1.0.1/setup.py` & `fast-brainfuck-1.0.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup
 def readme():
     with open('README.md','r') as f:
         return f.read()
 setup(
     name='fast-brainfuck',
     py_modules=['fastbf'],
-    version='1.0.1',
+    version='1.0.2',
     entry_points={
         'console_scripts':[
             'fastbf=fastbf:_fastbf_inter'
         ]
     },
     description='Brainfuck "compiler" for Python (fast)',
     long_description=readme(),
```


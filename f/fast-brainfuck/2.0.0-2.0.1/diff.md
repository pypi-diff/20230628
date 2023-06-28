# Comparing `tmp/fast-brainfuck-2.0.0.tar.gz` & `tmp/fast-brainfuck-2.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\fast-brainfuck-2.0.0.tar", last modified: Wed Jun 28 02:53:30 2023, max compression
+gzip compressed data, was "dist\fast-brainfuck-2.0.1.tar", last modified: Wed Jun 28 03:01:10 2023, max compression
```

## Comparing `fast-brainfuck-2.0.0.tar` & `fast-brainfuck-2.0.1.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 02:53:30.585403 fast-brainfuck-2.0.0/
--rw-rw-rw-   0        0        0     3446 2023-06-28 02:53:30.585403 fast-brainfuck-2.0.0/PKG-INFO
--rw-rw-rw-   0        0        0     2175 2023-06-28 02:53:12.000000 fast-brainfuck-2.0.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 02:53:30.585403 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/
--rw-rw-rw-   0        0        0     3446 2023-06-28 02:53:30.000000 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      258 2023-06-28 02:53:30.000000 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 02:53:30.000000 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       49 2023-06-28 02:53:30.000000 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       20 2023-06-28 02:53:30.000000 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 02:53:30.000000 fast-brainfuck-2.0.0/fast_brainfuck.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     4608 2023-06-28 02:52:49.000000 fast-brainfuck-2.0.0/fastbf.py
--rw-rw-rw-   0        0        0       42 2023-06-28 02:53:30.585403 fast-brainfuck-2.0.0/setup.cfg
--rw-rw-rw-   0        0        0     1145 2023-06-28 02:53:26.000000 fast-brainfuck-2.0.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:01:10.091283 fast-brainfuck-2.0.1/
+-rw-rw-rw-   0        0        0     3592 2023-06-28 03:01:10.091283 fast-brainfuck-2.0.1/PKG-INFO
+-rw-rw-rw-   0        0        0     2313 2023-06-28 03:01:05.000000 fast-brainfuck-2.0.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 03:01:10.091283 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/
+-rw-rw-rw-   0        0        0     3592 2023-06-28 03:01:10.000000 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      258 2023-06-28 03:01:10.000000 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 03:01:10.000000 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 03:01:10.000000 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 03:01:10.000000 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 03:01:10.000000 fast-brainfuck-2.0.1/fast_brainfuck.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     4629 2023-06-28 02:58:25.000000 fast-brainfuck-2.0.1/fastbf.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 03:01:10.091283 fast-brainfuck-2.0.1/setup.cfg
+-rw-rw-rw-   0        0        0     1145 2023-06-28 03:00:18.000000 fast-brainfuck-2.0.1/setup.py
```

### Comparing `fast-brainfuck-2.0.0/PKG-INFO` & `fast-brainfuck-2.0.1/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 2.0.0
+Version: 2.0.1
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         Finally! I've fixed Linux support!
+        All the 1.0.* versions are yanked by now, if you're using Linux and encountered an error, consider upgrading to version 2.0.0 or higher.
         ### This is a very fast brainfuck "compiler".
         
         When used, it builds brainfuck code into Python extension modules, and imports it.
         
         Requires:
         1. Python>=3.6
         2. C++ Compiler available
```

### Comparing `fast-brainfuck-2.0.0/README.md` & `fast-brainfuck-2.0.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
 
 Finally! I've fixed Linux support!
+All the 1.0.* versions are yanked by now, if you're using Linux and encountered an error, consider upgrading to version 2.0.0 or higher.
 ### This is a very fast brainfuck "compiler".
 
 When used, it builds brainfuck code into Python extension modules, and imports it.
 
 Requires:
 1. Python>=3.6
 2. C++ Compiler available
```

### Comparing `fast-brainfuck-2.0.0/fast_brainfuck.egg-info/PKG-INFO` & `fast-brainfuck-2.0.1/fast_brainfuck.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 2.0.0
+Version: 2.0.1
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         Finally! I've fixed Linux support!
+        All the 1.0.* versions are yanked by now, if you're using Linux and encountered an error, consider upgrading to version 2.0.0 or higher.
         ### This is a very fast brainfuck "compiler".
         
         When used, it builds brainfuck code into Python extension modules, and imports it.
         
         Requires:
         1. Python>=3.6
         2. C++ Compiler available
```

### Comparing `fast-brainfuck-2.0.0/fastbf.py` & `fast-brainfuck-2.0.1/fastbf.py`

 * *Files 1% similar despite different names*

```diff
@@ -143,9 +143,10 @@
     ap.add_argument('-c','--cellsize',help='Number of cells, default is 300000.',default='300000')
     args=ap.parse_args()
     with open(args.filename) as f:
         code=f.read()
     func=brainfuck_to_function(code,int(args.cellsize))
     func()
 __all__=['brainfuck_to_function','dist_brainfuck']
+__version__='2.0.1'
 if __name__=='__main__':
     _fastbf_inter()
```

### Comparing `fast-brainfuck-2.0.0/setup.py` & `fast-brainfuck-2.0.1/setup.py`

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
-    version='2.0.0',
+    version='2.0.1',
     entry_points={
         'console_scripts':[
             'fastbf=fastbf:_fastbf_inter'
         ]
     },
     description='Brainfuck "compiler" for Python (fast)',
     long_description=readme(),
```


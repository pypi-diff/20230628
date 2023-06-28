# Comparing `tmp/fast-brainfuck-1.0.2.tar.gz` & `tmp/fast-brainfuck-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\fast-brainfuck-1.0.2.tar", last modified: Wed Jun 28 01:47:38 2023, max compression
+gzip compressed data, was "dist\fast-brainfuck-1.0.3.tar", last modified: Wed Jun 28 01:56:22 2023, max compression
```

## Comparing `fast-brainfuck-1.0.2.tar` & `fast-brainfuck-1.0.3.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/
--rw-rw-rw-   0        0        0     3402 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/PKG-INFO
--rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.2/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/
--rw-rw-rw-   0        0        0     3402 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      258 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       49 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       20 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 01:47:38.000000 fast-brainfuck-1.0.2/fast_brainfuck.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     4320 2023-06-28 01:38:20.000000 fast-brainfuck-1.0.2/fastbf.py
--rw-rw-rw-   0        0        0       42 2023-06-28 01:47:38.754110 fast-brainfuck-1.0.2/setup.cfg
--rw-rw-rw-   0        0        0     1145 2023-06-28 01:41:22.000000 fast-brainfuck-1.0.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 01:56:22.826491 fast-brainfuck-1.0.3/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 01:56:22.825513 fast-brainfuck-1.0.3/PKG-INFO
+-rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 01:56:22.824540 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      258 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     4325 2023-06-28 01:56:07.000000 fast-brainfuck-1.0.3/fastbf.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 01:56:22.826491 fast-brainfuck-1.0.3/setup.cfg
+-rw-rw-rw-   0        0        0     1145 2023-06-28 01:56:18.000000 fast-brainfuck-1.0.3/setup.py
```

### Comparing `fast-brainfuck-1.0.2/PKG-INFO` & `fast-brainfuck-1.0.3/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.2
+Version: 1.0.3
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.2/README.md` & `fast-brainfuck-1.0.3/README.md`

 * *Files identical despite different names*

### Comparing `fast-brainfuck-1.0.2/fast_brainfuck.egg-info/PKG-INFO` & `fast-brainfuck-1.0.3/fast_brainfuck.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.2
+Version: 1.0.3
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.2/fastbf.py` & `fast-brainfuck-1.0.3/fastbf.py`

 * *Files 1% similar despite different names*

```diff
@@ -134,12 +134,12 @@
     from argparse import ArgumentParser
     ap=ArgumentParser(description='FastBF brainfuck interpreter')
     ap.add_argument('filename',help='Input brainfuck file name')
     ap.add_argument('-c','--cellsize',help='Number of cells, default is 300000.',default='300000')
     args=ap.parse_args()
     with open(args.filename) as f:
         code=f.read()
-    func=brainfuck_to_function(code,args.cellsize)
+    func=brainfuck_to_function(code,int(args.cellsize))
     func()
 __all__=['brainfuck_to_function','dist_brainfuck']
 if __name__=='__main__':
     _fastbf_inter()
```

### Comparing `fast-brainfuck-1.0.2/setup.py` & `fast-brainfuck-1.0.3/setup.py`

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
-    version='1.0.2',
+    version='1.0.3',
     entry_points={
         'console_scripts':[
             'fastbf=fastbf:_fastbf_inter'
         ]
     },
     description='Brainfuck "compiler" for Python (fast)',
     long_description=readme(),
```


# Comparing `tmp/fast-brainfuck-1.0.3.tar.gz` & `tmp/fast-brainfuck-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\fast-brainfuck-1.0.3.tar", last modified: Wed Jun 28 01:56:22 2023, max compression
+gzip compressed data, was "dist\fast-brainfuck-1.0.4.tar", last modified: Wed Jun 28 02:22:01 2023, max compression
```

## Comparing `fast-brainfuck-1.0.3.tar` & `fast-brainfuck-1.0.4.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 01:56:22.826491 fast-brainfuck-1.0.3/
--rw-rw-rw-   0        0        0     3402 2023-06-28 01:56:22.825513 fast-brainfuck-1.0.3/PKG-INFO
--rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 01:56:22.824540 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/
--rw-rw-rw-   0        0        0     3402 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      258 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       49 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       20 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 01:56:22.000000 fast-brainfuck-1.0.3/fast_brainfuck.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     4325 2023-06-28 01:56:07.000000 fast-brainfuck-1.0.3/fastbf.py
--rw-rw-rw-   0        0        0       42 2023-06-28 01:56:22.826491 fast-brainfuck-1.0.3/setup.cfg
--rw-rw-rw-   0        0        0     1145 2023-06-28 01:56:18.000000 fast-brainfuck-1.0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:22:01.079219 fast-brainfuck-1.0.4/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 02:22:01.079219 fast-brainfuck-1.0.4/PKG-INFO
+-rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 02:22:01.079219 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 02:22:01.000000 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      258 2023-06-28 02:22:01.000000 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:22:01.000000 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 02:22:01.000000 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 02:22:01.000000 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 02:22:01.000000 fast-brainfuck-1.0.4/fast_brainfuck.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     4412 2023-06-28 02:21:34.000000 fast-brainfuck-1.0.4/fastbf.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:22:01.079219 fast-brainfuck-1.0.4/setup.cfg
+-rw-rw-rw-   0        0        0     1145 2023-06-28 02:21:59.000000 fast-brainfuck-1.0.4/setup.py
```

### Comparing `fast-brainfuck-1.0.3/PKG-INFO` & `fast-brainfuck-1.0.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.3
+Version: 1.0.4
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.3/README.md` & `fast-brainfuck-1.0.4/README.md`

 * *Files identical despite different names*

### Comparing `fast-brainfuck-1.0.3/fast_brainfuck.egg-info/PKG-INFO` & `fast-brainfuck-1.0.4/fast_brainfuck.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.3
+Version: 1.0.4
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.3/fastbf.py` & `fast-brainfuck-1.0.4/fastbf.py`

 * *Files 1% similar despite different names*

```diff
@@ -100,14 +100,16 @@
     cpp=brainfuck_to_cpp(brainfuck,cellsize)
     wrap=wrap_cpp(cpp)
     with open('_foo.cpp','w') as f:
         f.write(wrap)
     with open('setup.py','w') as f:
         f.write(distcode)
     python=sys.executable
+    if platform.system()!='Windows':
+        os.chmod(os.path.join(_tmp(),dn),0o777)
     run(
         [
             python,
             'setup.py',
             'build_ext',
             '--inplace',
         ],shell=True,stdout=PIPE,stderr=PIPE
```

### Comparing `fast-brainfuck-1.0.3/setup.py` & `fast-brainfuck-1.0.4/setup.py`

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
-    version='1.0.3',
+    version='1.0.4',
     entry_points={
         'console_scripts':[
             'fastbf=fastbf:_fastbf_inter'
         ]
     },
     description='Brainfuck "compiler" for Python (fast)',
     long_description=readme(),
```


# Comparing `tmp/fast-brainfuck-1.0.7.tar.gz` & `tmp/fast-brainfuck-1.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\fast-brainfuck-1.0.7.tar", last modified: Wed Jun 28 02:40:52 2023, max compression
+gzip compressed data, was "dist\fast-brainfuck-1.0.8.tar", last modified: Wed Jun 28 02:47:26 2023, max compression
```

## Comparing `fast-brainfuck-1.0.7.tar` & `fast-brainfuck-1.0.8.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 02:40:52.415230 fast-brainfuck-1.0.7/
--rw-rw-rw-   0        0        0     3402 2023-06-28 02:40:52.414253 fast-brainfuck-1.0.7/PKG-INFO
--rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.7/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 02:40:52.413280 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/
--rw-rw-rw-   0        0        0     3402 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      258 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       49 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       20 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     4805 2023-06-28 02:40:43.000000 fast-brainfuck-1.0.7/fastbf.py
--rw-rw-rw-   0        0        0       42 2023-06-28 02:40:52.415230 fast-brainfuck-1.0.7/setup.cfg
--rw-rw-rw-   0        0        0     1145 2023-06-28 02:40:48.000000 fast-brainfuck-1.0.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:47:26.859654 fast-brainfuck-1.0.8/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 02:47:26.858681 fast-brainfuck-1.0.8/PKG-INFO
+-rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.8/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 02:47:26.857710 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 02:47:26.000000 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      258 2023-06-28 02:47:26.000000 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:47:26.000000 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 02:47:26.000000 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 02:47:26.000000 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 02:47:26.000000 fast-brainfuck-1.0.8/fast_brainfuck.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     4571 2023-06-28 02:47:04.000000 fast-brainfuck-1.0.8/fastbf.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:47:26.859654 fast-brainfuck-1.0.8/setup.cfg
+-rw-rw-rw-   0        0        0     1145 2023-06-28 02:47:16.000000 fast-brainfuck-1.0.8/setup.py
```

### Comparing `fast-brainfuck-1.0.7/PKG-INFO` & `fast-brainfuck-1.0.8/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.7
+Version: 1.0.8
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.7/README.md` & `fast-brainfuck-1.0.8/README.md`

 * *Files identical despite different names*

### Comparing `fast-brainfuck-1.0.7/fast_brainfuck.egg-info/PKG-INFO` & `fast-brainfuck-1.0.8/fast_brainfuck.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.7
+Version: 1.0.8
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.7/fastbf.py` & `fast-brainfuck-1.0.8/fastbf.py`

 * *Files 2% similar despite different names*

```diff
@@ -103,26 +103,16 @@
         f.write(wrap)
     with open('setup.py','w') as f:
         f.write(distcode)
     python=sys.executable
     if platform.system()!='Windows':
         os.chmod(os.path.join(_tmp(),dn),0o777)
         run(
-            [
-                python,
-                'setup.py',
-                'build_ext',
-            ],shell=True,stdout=PIPE,stderr=PIPE
+            f'{python} setup.py build_ext --inplace',shell=True,stdout=PIPE,stderr=PIPE
         )
-        os.chdir('build')
-        dn += '/build'
-        for i in os.listdir('.'):
-            if i.startswith('lib.'):
-                dn+='/'+i
-                break
     else:
         run(
             [
                 python,
                 'setup.py',
                 'build_ext',
                 '--inplace'
```

### Comparing `fast-brainfuck-1.0.7/setup.py` & `fast-brainfuck-1.0.8/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup
 def readme():
     with open('README.md','r') as f:
         return f.read()
 setup(
     name='fast-brainfuck',
     py_modules=['fastbf'],
-    version='1.0.7',
+    version='1.0.8',
     entry_points={
         'console_scripts':[
             'fastbf=fastbf:_fastbf_inter'
         ]
     },
     description='Brainfuck "compiler" for Python (fast)',
     long_description=readme(),
```


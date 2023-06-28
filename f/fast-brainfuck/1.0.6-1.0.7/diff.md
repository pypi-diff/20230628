# Comparing `tmp/fast-brainfuck-1.0.6.tar.gz` & `tmp/fast-brainfuck-1.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\fast-brainfuck-1.0.6.tar", last modified: Wed Jun 28 02:38:49 2023, max compression
+gzip compressed data, was "dist\fast-brainfuck-1.0.7.tar", last modified: Wed Jun 28 02:40:52 2023, max compression
```

## Comparing `fast-brainfuck-1.0.6.tar` & `fast-brainfuck-1.0.7.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 02:38:49.107055 fast-brainfuck-1.0.6/
--rw-rw-rw-   0        0        0     3402 2023-06-28 02:38:49.107055 fast-brainfuck-1.0.6/PKG-INFO
--rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.6/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 02:38:49.104759 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/
--rw-rw-rw-   0        0        0     3402 2023-06-28 02:38:49.000000 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      258 2023-06-28 02:38:49.000000 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 02:38:49.000000 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       49 2023-06-28 02:38:49.000000 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       20 2023-06-28 02:38:49.000000 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 02:38:49.000000 fast-brainfuck-1.0.6/fast_brainfuck.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     4803 2023-06-28 02:38:19.000000 fast-brainfuck-1.0.6/fastbf.py
--rw-rw-rw-   0        0        0       42 2023-06-28 02:38:49.108066 fast-brainfuck-1.0.6/setup.cfg
--rw-rw-rw-   0        0        0     1145 2023-06-28 02:38:44.000000 fast-brainfuck-1.0.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:40:52.415230 fast-brainfuck-1.0.7/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 02:40:52.414253 fast-brainfuck-1.0.7/PKG-INFO
+-rw-rw-rw-   0        0        0     2139 2023-06-28 01:44:51.000000 fast-brainfuck-1.0.7/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 02:40:52.413280 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/
+-rw-rw-rw-   0        0        0     3402 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      258 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       49 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 02:40:52.000000 fast-brainfuck-1.0.7/fast_brainfuck.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     4805 2023-06-28 02:40:43.000000 fast-brainfuck-1.0.7/fastbf.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:40:52.415230 fast-brainfuck-1.0.7/setup.cfg
+-rw-rw-rw-   0        0        0     1145 2023-06-28 02:40:48.000000 fast-brainfuck-1.0.7/setup.py
```

### Comparing `fast-brainfuck-1.0.6/PKG-INFO` & `fast-brainfuck-1.0.7/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.6
+Version: 1.0.7
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.6/README.md` & `fast-brainfuck-1.0.7/README.md`

 * *Files identical despite different names*

### Comparing `fast-brainfuck-1.0.6/fast_brainfuck.egg-info/PKG-INFO` & `fast-brainfuck-1.0.7/fast_brainfuck.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fast-brainfuck
-Version: 1.0.6
+Version: 1.0.7
 Summary: Brainfuck "compiler" for Python (fast)
 Home-page: UNKNOWN
 License: UNKNOWN
 Description: <p><span><span style="font-family:Verdana, Arial, Helvetica, sans-serif;line-height:19px;text-indent:26px;"><span style="font-size:14px;"><span style="font-family:Arial;line-height:26px;"><br></span></span></span></span></p>
         
         ### This is a very fast brainfuck "compiler".
```

### Comparing `fast-brainfuck-1.0.6/fastbf.py` & `fast-brainfuck-1.0.7/fastbf.py`

 * *Files 2% similar despite different names*

```diff
@@ -102,23 +102,23 @@
     with open('_foo.cpp','w') as f:
         f.write(wrap)
     with open('setup.py','w') as f:
         f.write(distcode)
     python=sys.executable
     if platform.system()!='Windows':
         os.chmod(os.path.join(_tmp(),dn),0o777)
-        os.chdir('build')
-        dn+='/build'
         run(
             [
                 python,
                 'setup.py',
                 'build_ext',
             ],shell=True,stdout=PIPE,stderr=PIPE
         )
+        os.chdir('build')
+        dn += '/build'
         for i in os.listdir('.'):
             if i.startswith('lib.'):
                 dn+='/'+i
                 break
     else:
         run(
             [
```

### Comparing `fast-brainfuck-1.0.6/setup.py` & `fast-brainfuck-1.0.7/setup.py`

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
-    version='1.0.6',
+    version='1.0.7',
     entry_points={
         'console_scripts':[
             'fastbf=fastbf:_fastbf_inter'
         ]
     },
     description='Brainfuck "compiler" for Python (fast)',
     long_description=readme(),
```


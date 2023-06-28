# Comparing `tmp/dynamic-links-0.0.2.tar.gz` & `tmp/dynamic-links-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dynamic-links-0.0.2.tar", last modified: Wed Jun 28 06:04:35 2023, max compression
+gzip compressed data, was "dynamic-links-0.0.3.tar", last modified: Wed Jun 28 06:19:17 2023, max compression
```

## Comparing `dynamic-links-0.0.2.tar` & `dynamic-links-0.0.3.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:04:35.385835 dynamic-links-0.0.2/
--rw-r--r--   0 pic        (501) staff       (20)     5249 2023-06-28 06:04:35.385686 dynamic-links-0.0.2/PKG-INFO
--rw-r--r--   0 pic        (501) staff       (20)     4976 2023-06-28 06:02:18.000000 dynamic-links-0.0.2/README.md
-drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:04:35.384705 dynamic-links-0.0.2/dlframe/
--rw-r--r--   0 pic        (501) staff       (20)     2630 2023-06-27 04:59:53.000000 dynamic-links-0.0.2/dlframe/CalculationNode.py
--rw-r--r--   0 pic        (501) staff       (20)     1924 2023-06-27 03:29:25.000000 dynamic-links-0.0.2/dlframe/CalculationNodeManager.py
--rw-r--r--   0 pic        (501) staff       (20)     2048 2023-06-27 04:00:46.000000 dynamic-links-0.0.2/dlframe/ExecutionNode.py
--rw-r--r--   0 pic        (501) staff       (20)      939 2023-06-27 05:19:42.000000 dynamic-links-0.0.2/dlframe/Logger.py
--rw-r--r--   0 pic        (501) staff       (20)     5170 2023-06-27 05:20:48.000000 dynamic-links-0.0.2/dlframe/WebManager.py
--rw-r--r--   0 pic        (501) staff       (20)      141 2023-06-26 17:09:16.000000 dynamic-links-0.0.2/dlframe/__init__.py
-drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:04:35.385468 dynamic-links-0.0.2/dynamic_links.egg-info/
--rw-r--r--   0 pic        (501) staff       (20)     5249 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/PKG-INFO
--rw-r--r--   0 pic        (501) staff       (20)      348 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/SOURCES.txt
--rw-r--r--   0 pic        (501) staff       (20)        1 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/dependency_links.txt
--rw-r--r--   0 pic        (501) staff       (20)       30 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/requires.txt
--rw-r--r--   0 pic        (501) staff       (20)        8 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/top_level.txt
--rw-r--r--   0 pic        (501) staff       (20)       38 2023-06-28 06:04:35.385879 dynamic-links-0.0.2/setup.cfg
--rw-r--r--   0 pic        (501) staff       (20)      682 2023-06-28 06:04:18.000000 dynamic-links-0.0.2/setup.py
+drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:19:17.729780 dynamic-links-0.0.3/
+-rw-r--r--   0 pic        (501) staff       (20)     5342 2023-06-28 06:19:17.729632 dynamic-links-0.0.3/PKG-INFO
+-rw-r--r--   0 pic        (501) staff       (20)     5069 2023-06-28 06:18:33.000000 dynamic-links-0.0.3/README.md
+drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:19:17.728721 dynamic-links-0.0.3/dlframe/
+-rw-r--r--   0 pic        (501) staff       (20)     2630 2023-06-27 04:59:53.000000 dynamic-links-0.0.3/dlframe/CalculationNode.py
+-rw-r--r--   0 pic        (501) staff       (20)     1924 2023-06-27 03:29:25.000000 dynamic-links-0.0.3/dlframe/CalculationNodeManager.py
+-rw-r--r--   0 pic        (501) staff       (20)     2048 2023-06-27 04:00:46.000000 dynamic-links-0.0.3/dlframe/ExecutionNode.py
+-rw-r--r--   0 pic        (501) staff       (20)      939 2023-06-27 05:19:42.000000 dynamic-links-0.0.3/dlframe/Logger.py
+-rw-r--r--   0 pic        (501) staff       (20)     5170 2023-06-27 05:20:48.000000 dynamic-links-0.0.3/dlframe/WebManager.py
+-rw-r--r--   0 pic        (501) staff       (20)      141 2023-06-26 17:09:16.000000 dynamic-links-0.0.3/dlframe/__init__.py
+drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:19:17.729429 dynamic-links-0.0.3/dynamic_links.egg-info/
+-rw-r--r--   0 pic        (501) staff       (20)     5342 2023-06-28 06:19:17.000000 dynamic-links-0.0.3/dynamic_links.egg-info/PKG-INFO
+-rw-r--r--   0 pic        (501) staff       (20)      348 2023-06-28 06:19:17.000000 dynamic-links-0.0.3/dynamic_links.egg-info/SOURCES.txt
+-rw-r--r--   0 pic        (501) staff       (20)        1 2023-06-28 06:19:17.000000 dynamic-links-0.0.3/dynamic_links.egg-info/dependency_links.txt
+-rw-r--r--   0 pic        (501) staff       (20)       30 2023-06-28 06:19:17.000000 dynamic-links-0.0.3/dynamic_links.egg-info/requires.txt
+-rw-r--r--   0 pic        (501) staff       (20)        8 2023-06-28 06:19:17.000000 dynamic-links-0.0.3/dynamic_links.egg-info/top_level.txt
+-rw-r--r--   0 pic        (501) staff       (20)       38 2023-06-28 06:19:17.729823 dynamic-links-0.0.3/setup.cfg
+-rw-r--r--   0 pic        (501) staff       (20)      682 2023-06-28 06:18:12.000000 dynamic-links-0.0.3/setup.py
```

### Comparing `dynamic-links-0.0.2/PKG-INFO` & `dynamic-links-0.0.3/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dynamic-links
-Version: 0.0.2
+Version: 0.0.3
 Summary: a calculation framework
 Home-page: https://github.com/picpic2013/dlframe-back
 Author: PIC
 Author-email: picpic2019@gmail.com
 License: MIT
 Requires-Python: >=3.8, <4
 Description-Content-Type: text/markdown
@@ -34,19 +34,22 @@
     print('f1', x)
 
 def f2(x):
     print('f2', x)
 
 # 定义元素管理器
 with WebManager() as manager:
+    
+    # 定义元素 + 定义元素可选的 python 对象
     func = manager.register_element('func', {
         'f1': f1, 
         'f2': f2
     })
 
+    # 定义框架执行逻辑
     func('test')
 ~~~
 
 运行程序，即可通过[前端](https://picpic2013.github.io/dlframe-front/)选择执行 `f1` 或 `f2`。
 
 ### 更复杂的例子
```

### Comparing `dynamic-links-0.0.2/README.md` & `dynamic-links-0.0.3/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -23,19 +23,22 @@
     print('f1', x)
 
 def f2(x):
     print('f2', x)
 
 # 定义元素管理器
 with WebManager() as manager:
+    
+    # 定义元素 + 定义元素可选的 python 对象
     func = manager.register_element('func', {
         'f1': f1, 
         'f2': f2
     })
 
+    # 定义框架执行逻辑
     func('test')
 ~~~
 
 运行程序，即可通过[前端](https://picpic2013.github.io/dlframe-front/)选择执行 `f1` 或 `f2`。
 
 ### 更复杂的例子
```

### Comparing `dynamic-links-0.0.2/dlframe/CalculationNode.py` & `dynamic-links-0.0.3/dlframe/CalculationNode.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.2/dlframe/CalculationNodeManager.py` & `dynamic-links-0.0.3/dlframe/CalculationNodeManager.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.2/dlframe/ExecutionNode.py` & `dynamic-links-0.0.3/dlframe/ExecutionNode.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.2/dlframe/Logger.py` & `dynamic-links-0.0.3/dlframe/Logger.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.2/dlframe/WebManager.py` & `dynamic-links-0.0.3/dlframe/WebManager.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.2/dynamic_links.egg-info/PKG-INFO` & `dynamic-links-0.0.3/dynamic_links.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dynamic-links
-Version: 0.0.2
+Version: 0.0.3
 Summary: a calculation framework
 Home-page: https://github.com/picpic2013/dlframe-back
 Author: PIC
 Author-email: picpic2019@gmail.com
 License: MIT
 Requires-Python: >=3.8, <4
 Description-Content-Type: text/markdown
@@ -34,19 +34,22 @@
     print('f1', x)
 
 def f2(x):
     print('f2', x)
 
 # 定义元素管理器
 with WebManager() as manager:
+    
+    # 定义元素 + 定义元素可选的 python 对象
     func = manager.register_element('func', {
         'f1': f1, 
         'f2': f2
     })
 
+    # 定义框架执行逻辑
     func('test')
 ~~~
 
 运行程序，即可通过[前端](https://picpic2013.github.io/dlframe-front/)选择执行 `f1` 或 `f2`。
 
 ### 更复杂的例子
```

### Comparing `dynamic-links-0.0.2/setup.py` & `dynamic-links-0.0.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 here = pathlib.Path(__file__).parent.resolve()
 
 with open(os.path.join(here, 'README.md'), 'r',encoding='UTF-8') as mdFile:
     long_description = mdFile.read()
 
 setup(
     name='dynamic-links', 
-    version='0.0.2', 
+    version='0.0.3', 
     packages=['dlframe'], 
     url='https://github.com/picpic2013/dlframe-back', 
     license='MIT', 
     author='PIC', 
     author_email='picpic2019@gmail.com', 
     description='a calculation framework', 
     long_description=long_description,
```


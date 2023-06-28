# Comparing `tmp/chatgpt_functions-0.1.3.tar.gz` & `tmp/chatgpt_functions-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chatgpt_functions-0.1.3.tar", last modified: Tue Jun 27 15:33:02 2023, max compression
+gzip compressed data, was "chatgpt_functions-0.1.4.tar", last modified: Wed Jun 28 09:15:42 2023, max compression
```

## Comparing `chatgpt_functions-0.1.3.tar` & `chatgpt_functions-0.1.4.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 15:33:02.347543 chatgpt_functions-0.1.3/
--rw-rw-rw-   0        0        0     1091 2023-06-26 13:13:15.000000 chatgpt_functions-0.1.3/LICENSE
--rw-rw-rw-   0        0        0     1935 2023-06-27 15:33:02.348543 chatgpt_functions-0.1.3/PKG-INFO
--rw-rw-rw-   0        0        0     1374 2023-06-26 12:54:41.000000 chatgpt_functions-0.1.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 15:33:02.330490 chatgpt_functions-0.1.3/chatgpt_functions/
--rw-rw-rw-   0        0        0       83 2023-06-26 13:35:12.000000 chatgpt_functions-0.1.3/chatgpt_functions/__init__.py
--rw-rw-rw-   0        0        0     2858 2023-06-27 15:30:53.000000 chatgpt_functions-0.1.3/chatgpt_functions/chatgpt.py
--rw-rw-rw-   0        0        0      722 2023-06-26 11:01:56.000000 chatgpt_functions-0.1.3/chatgpt_functions/chatgpt_function.py
--rw-rw-rw-   0        0        0      476 2023-06-26 15:36:46.000000 chatgpt_functions-0.1.3/chatgpt_functions/chatgpt_types.py
--rw-rw-rw-   0        0        0     1319 2023-06-26 12:53:31.000000 chatgpt_functions-0.1.3/chatgpt_functions/function_parameters.py
-drwxrwxrwx   0        0        0        0 2023-06-27 15:33:02.345537 chatgpt_functions-0.1.3/chatgpt_functions.egg-info/
--rw-rw-rw-   0        0        0     1935 2023-06-27 15:33:02.000000 chatgpt_functions-0.1.3/chatgpt_functions.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      428 2023-06-27 15:33:02.000000 chatgpt_functions-0.1.3/chatgpt_functions.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 15:33:02.000000 chatgpt_functions-0.1.3/chatgpt_functions.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       36 2023-06-27 15:33:02.000000 chatgpt_functions-0.1.3/chatgpt_functions.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-27 15:33:02.000000 chatgpt_functions-0.1.3/chatgpt_functions.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      682 2023-06-26 14:36:57.000000 chatgpt_functions-0.1.3/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-27 15:33:02.349542 chatgpt_functions-0.1.3/setup.cfg
--rw-rw-rw-   0        0        0      875 2023-06-27 15:32:49.000000 chatgpt_functions-0.1.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:15:42.675195 chatgpt_functions-0.1.4/
+-rw-rw-rw-   0        0        0     1091 2023-06-26 13:13:15.000000 chatgpt_functions-0.1.4/LICENSE
+-rw-rw-rw-   0        0        0     1935 2023-06-28 09:15:42.675195 chatgpt_functions-0.1.4/PKG-INFO
+-rw-rw-rw-   0        0        0     1374 2023-06-26 12:54:41.000000 chatgpt_functions-0.1.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 09:15:42.659149 chatgpt_functions-0.1.4/chatgpt_functions/
+-rw-rw-rw-   0        0        0       83 2023-06-26 13:35:12.000000 chatgpt_functions-0.1.4/chatgpt_functions/__init__.py
+-rw-rw-rw-   0        0        0     5257 2023-06-28 09:04:28.000000 chatgpt_functions-0.1.4/chatgpt_functions/chatgpt.py
+-rw-rw-rw-   0        0        0      722 2023-06-26 11:01:56.000000 chatgpt_functions-0.1.4/chatgpt_functions/chatgpt_function.py
+-rw-rw-rw-   0        0        0      476 2023-06-26 15:36:46.000000 chatgpt_functions-0.1.4/chatgpt_functions/chatgpt_types.py
+-rw-rw-rw-   0        0        0     1319 2023-06-26 12:53:31.000000 chatgpt_functions-0.1.4/chatgpt_functions/function_parameters.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:15:42.673195 chatgpt_functions-0.1.4/chatgpt_functions.egg-info/
+-rw-rw-rw-   0        0        0     1935 2023-06-28 09:15:42.000000 chatgpt_functions-0.1.4/chatgpt_functions.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      428 2023-06-28 09:15:42.000000 chatgpt_functions-0.1.4/chatgpt_functions.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:15:42.000000 chatgpt_functions-0.1.4/chatgpt_functions.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       50 2023-06-28 09:15:42.000000 chatgpt_functions-0.1.4/chatgpt_functions.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 09:15:42.000000 chatgpt_functions-0.1.4/chatgpt_functions.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      682 2023-06-26 14:36:57.000000 chatgpt_functions-0.1.4/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 09:15:42.677195 chatgpt_functions-0.1.4/setup.cfg
+-rw-rw-rw-   0        0        0     1093 2023-06-28 09:15:24.000000 chatgpt_functions-0.1.4/setup.py
```

### Comparing `chatgpt_functions-0.1.3/LICENSE` & `chatgpt_functions-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.3/PKG-INFO` & `chatgpt_functions-0.1.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chatgpt_functions
-Version: 0.1.3
+Version: 0.1.4
 Summary: Wrapper over the gpt3.5 model, capable of calling functions
 Home-page: https://github.com/Wellmare/chatgpt-functions
 Author: Wellmare
 Author-email: ivan.kolipov@gmail.com
 Keywords: chatgpt functions gpt
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `chatgpt_functions-0.1.3/README.md` & `chatgpt_functions-0.1.4/README.md`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.3/chatgpt_functions/chatgpt_function.py` & `chatgpt_functions-0.1.4/chatgpt_functions/chatgpt_function.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.3/chatgpt_functions/function_parameters.py` & `chatgpt_functions-0.1.4/chatgpt_functions/function_parameters.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.3/chatgpt_functions.egg-info/PKG-INFO` & `chatgpt_functions-0.1.4/chatgpt_functions.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chatgpt-functions
-Version: 0.1.3
+Version: 0.1.4
 Summary: Wrapper over the gpt3.5 model, capable of calling functions
 Home-page: https://github.com/Wellmare/chatgpt-functions
 Author: Wellmare
 Author-email: ivan.kolipov@gmail.com
 Keywords: chatgpt functions gpt
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `chatgpt_functions-0.1.3/pyproject.toml` & `chatgpt_functions-0.1.4/pyproject.toml`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.3/setup.py` & `chatgpt_functions-0.1.4/setup.py`

 * *Files 20% similar despite different names*

```diff
@@ -2,25 +2,33 @@
 
 
 def readme():
     with open("README.md", "r") as f:
         return f.read()
 
 
+def read_requirements():
+    with open('requirements.txt', 'rb') as file:
+        content = file.read().decode('utf-8')
+    lines = content.splitlines()
+    lines = [line.strip() for line in lines if line.strip()]
+    return lines
+
+
 setup(
     name="chatgpt_functions",
-    version="0.1.3",
+    version="0.1.4",
     author="Wellmare",
     author_email="ivan.kolipov@gmail.com",
     description="Wrapper over the gpt3.5 model, capable of calling functions",
     long_description=readme(),
     long_description_content_type="text/markdown",
     url="https://github.com/Wellmare/chatgpt-functions",
     packages=find_packages(),
-    install_requires=["openai==0.27.8", "python-dotenv==1.0.0"],
+    install_requires=read_requirements(),
     classifiers=[
         "Programming Language :: Python :: 3.10",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
     ],
     keywords="chatgpt functions gpt",
     # project_urls={"Documentation": "link"},
```


# Comparing `tmp/importils-0.3.tar.gz` & `tmp/importils-0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "importils-0.3.tar", last modified: Tue Jun 27 21:13:22 2023, max compression
+gzip compressed data, was "importils-0.4.tar", last modified: Tue Jun 27 21:14:19 2023, max compression
```

## Comparing `importils-0.3.tar` & `importils-0.4.tar`

### file list

```diff
@@ -1,13 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 21:13:22.590315 importils-0.3/
--rw-rw-rw-   0        0        0     1094 2023-06-27 21:06:07.000000 importils-0.3/LICENSE
--rw-rw-rw-   0        0        0      772 2023-06-27 21:13:22.590315 importils-0.3/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-27 21:06:07.000000 importils-0.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 21:13:22.578585 importils-0.3/importils/
--rw-rw-rw-   0        0        0       44 2023-06-27 21:09:46.000000 importils-0.3/importils/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 21:13:22.588711 importils-0.3/importils.egg-info/
--rw-rw-rw-   0        0        0      772 2023-06-27 21:13:22.000000 importils-0.3/importils.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      190 2023-06-27 21:13:22.000000 importils-0.3/importils.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 21:13:22.000000 importils-0.3/importils.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       10 2023-06-27 21:13:22.000000 importils-0.3/importils.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       86 2023-06-27 21:13:22.593337 importils-0.3/setup.cfg
--rw-rw-rw-   0        0        0     1651 2023-06-27 21:13:14.000000 importils-0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-27 21:14:19.458898 importils-0.4/
+-rw-rw-rw-   0        0        0     1094 2023-06-27 21:06:07.000000 importils-0.4/LICENSE
+-rw-rw-rw-   0        0        0      772 2023-06-27 21:14:19.458898 importils-0.4/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-27 21:06:07.000000 importils-0.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-27 21:14:19.448343 importils-0.4/importils/
+-rw-rw-rw-   0        0        0       44 2023-06-27 21:09:46.000000 importils-0.4/importils/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-27 21:14:19.456898 importils-0.4/importils.egg-info/
+-rw-rw-rw-   0        0        0      772 2023-06-27 21:14:19.000000 importils-0.4/importils.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      222 2023-06-27 21:14:19.000000 importils-0.4/importils.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 21:14:19.000000 importils-0.4/importils.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       12 2023-06-27 21:14:19.000000 importils-0.4/importils.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       10 2023-06-27 21:14:19.000000 importils-0.4/importils.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       86 2023-06-27 21:14:19.462898 importils-0.4/setup.cfg
+-rw-rw-rw-   0        0        0     1685 2023-06-27 21:14:14.000000 importils-0.4/setup.py
```

### Comparing `importils-0.3/LICENSE` & `importils-0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `importils-0.3/PKG-INFO` & `importils-0.4/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: importils
-Version: 0.3
+Version: 0.4
 Summary: TYPE YOUR DESCRIPTION HERE
 Home-page: https://github.com/TogiFerretFerret/importils
 Download-URL: https://github.com/TogiFerretFerret/importils/archive/refs/tags/v_03.tar.gz
 Author: YOUR NAME
 Author-email: your.email@domain.com
 License: MIT
 Keywords: SOME,MEANINGFULL,KEYWORDS
```

### Comparing `importils-0.3/importils.egg-info/PKG-INFO` & `importils-0.4/importils.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: importils
-Version: 0.3
+Version: 0.4
 Summary: TYPE YOUR DESCRIPTION HERE
 Home-page: https://github.com/TogiFerretFerret/importils
 Download-URL: https://github.com/TogiFerretFerret/importils/archive/refs/tags/v_03.tar.gz
 Author: YOUR NAME
 Author-email: your.email@domain.com
 License: MIT
 Keywords: SOME,MEANINGFULL,KEYWORDS
```

### Comparing `importils-0.3/setup.py` & `importils-0.4/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,20 +1,22 @@
 from distutils.core import setup
 setup(
   name = 'importils',         # How you named your package folder (MyLib)
   packages = ['importils'],   # Chose the same as "name"
-  version = '0.3',      # Start with a small number and increase it with every change you make
+  version = '0.4',      # Start with a small number and increase it with every change you make
   license='MIT',        # Chose a license from here: https://help.github.com/articles/licensing-a-repository
   description = 'TYPE YOUR DESCRIPTION HERE',   # Give a short description about your library
   author = 'YOUR NAME',                   # Type in your name
   author_email = 'your.email@domain.com',      # Type in your E-Mail
   url = 'https://github.com/TogiFerretFerret/importils',   # Provide either the link to your github or to your website
   download_url = 'https://github.com/TogiFerretFerret/importils/archive/refs/tags/v_03.tar.gz',    # I explain this later on
   keywords = ['SOME', 'MEANINGFULL', 'KEYWORDS'],   # Keywords that define your package best
-  install_requires=[            # I get to this in a second
+  install_requires=[     
+      'pick',
+           'Pillow'     # I get to this in a second
       ],
   classifiers=[
     'Development Status :: 3 - Alpha',      # Chose either "3 - Alpha", "4 - Beta" or "5 - Production/Stable" as the current state of your package
     'Intended Audience :: Developers',      # Define that your audience are developers
     'Topic :: Software Development :: Build Tools',
     'License :: OSI Approved :: MIT License',   # Again, pick a license
     'Programming Language :: Python :: 3',      #Specify which pyhton versions that you want to support
```


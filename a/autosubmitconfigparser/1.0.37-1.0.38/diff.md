# Comparing `tmp/autosubmitconfigparser-1.0.37.tar.gz` & `tmp/autosubmitconfigparser-1.0.38.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "autosubmitconfigparser-1.0.37.tar", last modified: Mon Jun 12 13:17:01 2023, max compression
+gzip compressed data, was "autosubmitconfigparser-1.0.38.tar", last modified: Wed Jun 28 12:15:51 2023, max compression
```

## Comparing `autosubmitconfigparser-1.0.37.tar` & `autosubmitconfigparser-1.0.38.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)       41 2023-03-03 13:49:23.000000 autosubmitconfigparser-1.0.37/MANIFEST.in
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     2086 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/PKG-INFO
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     1493 2022-12-05 09:31:33.000000 autosubmitconfigparser-1.0.37/README.md
-drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/autosubmitconfigparser/
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-07 13:48:23.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/__init__.py
-drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-07 13:49:24.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/__init__.py
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     7990 2023-04-25 12:49:03.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/basicconfig.py
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)   104540 2023-06-12 11:54:21.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/configcommon.py
-drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      269 2023-02-14 09:38:41.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/autosubmit-dummy.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      269 2023-02-14 09:38:41.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/autosubmit.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      562 2023-02-14 09:24:09.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/expdef-dummy.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      557 2023-02-14 10:53:51.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/expdef.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      401 2023-03-03 11:06:17.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/git-minimal.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      669 2022-10-26 08:50:59.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/jobs-dummy.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      669 2022-10-26 08:50:59.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/jobs.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      321 2023-03-03 12:26:14.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/local-minimal.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     1247 2023-02-14 10:53:51.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/platforms-dummy.yml
--rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     1247 2023-02-14 10:53:51.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/platforms.yml
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)      275 2023-06-07 12:06:41.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/yamlparser.py
-drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     2086 2023-06-12 13:17:01.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/PKG-INFO
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     1029 2023-06-12 13:17:01.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/SOURCES.txt
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        1 2023-06-12 13:17:01.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/dependency_links.txt
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)      305 2023-06-12 13:17:01.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/requires.txt
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)       27 2023-06-12 13:17:01.000000 autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/top_level.txt
-drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/log/
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        0 2022-10-26 08:51:23.000000 autosubmitconfigparser-1.0.37/log/__init__.py
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)      871 2022-10-26 08:51:23.000000 autosubmitconfigparser-1.0.37/log/fd_show.py
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)    13106 2022-10-26 08:51:23.000000 autosubmitconfigparser-1.0.37/log/log.py
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)       38 2023-06-12 13:17:01.445726 autosubmitconfigparser-1.0.37/setup.cfg
--rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     1464 2023-06-12 12:15:46.000000 autosubmitconfigparser-1.0.37/setup.py
+drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-28 12:15:51.326060 autosubmitconfigparser-1.0.38/
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)       41 2023-03-03 13:49:23.000000 autosubmitconfigparser-1.0.38/MANIFEST.in
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     2123 2023-06-28 12:15:51.326060 autosubmitconfigparser-1.0.38/PKG-INFO
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     1493 2022-12-05 09:31:33.000000 autosubmitconfigparser-1.0.38/README.md
+drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-28 12:15:51.322060 autosubmitconfigparser-1.0.38/autosubmitconfigparser/
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-07 13:48:23.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/__init__.py
+drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-28 12:15:51.322060 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-07 13:49:24.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/__init__.py
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     7990 2023-04-25 12:49:03.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/basicconfig.py
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)   104413 2023-06-28 12:03:57.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/configcommon.py
+drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-28 12:15:51.326060 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      269 2023-02-14 09:38:41.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/autosubmit-dummy.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      269 2023-02-14 09:38:41.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/autosubmit.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      562 2023-02-14 09:24:09.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/expdef-dummy.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      557 2023-02-14 10:53:51.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/expdef.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      401 2023-03-03 11:06:17.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/git-minimal.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      669 2022-10-26 08:50:59.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/jobs-dummy.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      669 2022-10-26 08:50:59.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/jobs.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)      321 2023-03-03 12:26:14.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/local-minimal.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     1247 2023-02-14 10:53:51.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/platforms-dummy.yml
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     1247 2023-02-14 10:53:51.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/platforms.yml
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)      275 2023-06-07 12:06:41.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/yamlparser.py
+drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-28 12:15:51.322060 autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     2123 2023-06-28 12:15:50.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/PKG-INFO
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)     1029 2023-06-28 12:15:51.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/SOURCES.txt
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        1 2023-06-28 12:15:50.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/dependency_links.txt
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)      321 2023-06-28 12:15:50.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/requires.txt
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)       27 2023-06-28 12:15:51.000000 autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/top_level.txt
+drwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)        0 2023-06-28 12:15:51.326060 autosubmitconfigparser-1.0.38/log/
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)        0 2022-10-26 08:51:23.000000 autosubmitconfigparser-1.0.38/log/__init__.py
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)      871 2022-10-26 08:51:23.000000 autosubmitconfigparser-1.0.38/log/fd_show.py
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)    13106 2022-10-26 08:51:23.000000 autosubmitconfigparser-1.0.38/log/log.py
+-rw-rw-r--   0 dbeltran  (1001) dbeltran  (1001)       38 2023-06-28 12:15:51.326060 autosubmitconfigparser-1.0.38/setup.cfg
+-rwxrwxr-x   0 dbeltran  (1001) dbeltran  (1001)     1461 2023-06-28 12:14:29.000000 autosubmitconfigparser-1.0.38/setup.py
```

### Comparing `autosubmitconfigparser-1.0.37/PKG-INFO` & `autosubmitconfigparser-1.0.38/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,15 +1,17 @@
 Metadata-Version: 2.1
 Name: autosubmitconfigparser
-Version: 1.0.37
+Version: 1.0.38
 Summary: An utility library that allows to read an Autosubmit 4 experiment configuration.
 Home-page: https://earth.bsc.es/gitlab/ces/autosubmit4-config-parser.git
 Author: Daniel Beltran Mora
 Author-email: daniel.beltran@bsc.es
+License: UNKNOWN
 Keywords: climate,weather,workflow,HPC
+Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.9
 Classifier: License :: OSI Approved :: GNU General Public License (GPL)
 Classifier: Operating System :: POSIX :: Linux
 Description-Content-Type: text/markdown
 
 Simple library that allows to read the data of an Autosubmit experiment.
@@ -56,7 +58,9 @@
 # This is a sample text with a placeholder expid
 
 # delete samples
 os.remove("as_sample.txt")
 os.remove("as_sample_parsed.txt")
 ```
 
+
+
```

### Comparing `autosubmitconfigparser-1.0.37/README.md` & `autosubmitconfigparser-1.0.38/README.md`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/basicconfig.py` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/basicconfig.py`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/configcommon.py` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/configcommon.py`

 * *Files 0% similar despite different names*

```diff
@@ -772,23 +772,20 @@
 
         if parameters is None:
             parameters = self.deep_parameters_export(self.experiment_data)
         # Check if the parameters key provided are long(%DEFAULT.EXPID%) or short(DEFAULT[EXPID]) if it is not specified.
         if dict_keys_type is None:
             dict_keys_type = self.check_dict_keys_type(parameters)
         pattern = '%[a-zA-Z0-9_.]*%'
-        keys = ""
         backup_variables = self.dynamic_variables
         max_deep = max_deep + len(self.dynamic_variables)
 
         while len(self.dynamic_variables) > 0 and max_deep > 0:
             dynamic_variables = []
             for dynamic_var in self.dynamic_variables:
-                rest_of_keys_start = ""
-                rest_of_keys_end = ""
                 #get value of placeholder with  name without %%
                 if dict_keys_type == "long":
                     keys = parameters.get(str(dynamic_var[0][1:-1]),None)
                     if keys is None:
                         keys = parameters.get(str(dynamic_var[0]), None)
                 else:
                     keys = dynamic_var[1]
@@ -797,16 +794,15 @@
                     match = (re.search(pattern, keys,flags=re.IGNORECASE))
                 else:
                     match = None
                 if match is not None:
                     rest_of_keys_start = keys[:match.start()]
                     rest_of_keys_end = keys[match.end():]
                     keys = keys[match.start():match.end()]
-
-                    if "." in keys:
+                    if "." in keys and dict_keys_type != "long":
                         keys = keys[1:-1].split(".")
                     else:
                         keys = [keys[1:-1]]
                     aux_dict = parameters
                     for k in keys:
                         aux_dict = aux_dict.get(k.upper(),{})
                     if len(aux_dict) > 0:
@@ -821,17 +817,15 @@
                         dict_key = parameters.get(str(dynamic_var[0]), {})
                         if len(dict_key) > 0:
                             substituted = True
                             parameters[str(dynamic_var[0])] = value
                         else:
                             substituted = False
                     else:
-                        # See input and output below todo
                         parameters = self.dict_replace_value(parameters, dynamic_var[1], value)
-
                         substituted = False
                 else:
                     # This may be True instead of False
                     substituted = False
                 if not substituted:
                     if value is not None:
                         dynamic_variables.append((dynamic_var[0],value))
```

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/expdef-dummy.yml` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/expdef-dummy.yml`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/expdef.yml` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/expdef.yml`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/jobs-dummy.yml` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/jobs-dummy.yml`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/jobs.yml` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/jobs.yml`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/platforms-dummy.yml` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/platforms-dummy.yml`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser/config/files/platforms.yml` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser/config/files/platforms.yml`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/PKG-INFO` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,15 +1,17 @@
 Metadata-Version: 2.1
 Name: autosubmitconfigparser
-Version: 1.0.37
+Version: 1.0.38
 Summary: An utility library that allows to read an Autosubmit 4 experiment configuration.
 Home-page: https://earth.bsc.es/gitlab/ces/autosubmit4-config-parser.git
 Author: Daniel Beltran Mora
 Author-email: daniel.beltran@bsc.es
+License: UNKNOWN
 Keywords: climate,weather,workflow,HPC
+Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.9
 Classifier: License :: OSI Approved :: GNU General Public License (GPL)
 Classifier: Operating System :: POSIX :: Linux
 Description-Content-Type: text/markdown
 
 Simple library that allows to read the data of an Autosubmit experiment.
@@ -56,7 +58,9 @@
 # This is a sample text with a placeholder expid
 
 # delete samples
 os.remove("as_sample.txt")
 os.remove("as_sample_parsed.txt")
 ```
 
+
+
```

### Comparing `autosubmitconfigparser-1.0.37/autosubmitconfigparser.egg-info/SOURCES.txt` & `autosubmitconfigparser-1.0.38/autosubmitconfigparser.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/log/fd_show.py` & `autosubmitconfigparser-1.0.38/log/fd_show.py`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/log/log.py` & `autosubmitconfigparser-1.0.38/log/log.py`

 * *Files identical despite different names*

### Comparing `autosubmitconfigparser-1.0.37/setup.py` & `autosubmitconfigparser-1.0.38/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -3,31 +3,30 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="autosubmitconfigparser",
-    version="1.0.37",
+    version="1.0.38",
     author="Daniel Beltran Mora",
     author_email="daniel.beltran@bsc.es",
     description="An utility library that allows to read an Autosubmit 4 experiment configuration.",
     keywords=['climate', 'weather', 'workflow', 'HPC'],
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://earth.bsc.es/gitlab/ces/autosubmit4-config-parser.git",
     include_package_data=True,
     package_data={'files': ['autosubmitconfigparser/conf/files/*']},
     packages=setuptools.find_packages(),
-    install_requires=['ruamel.yaml','packaging>19', 'six>=1.10.0', 'configobj>=5.0.6', 'argparse>=1.4.0', 'python-dateutil>=2.8.2',
-                       'pyparsing>=3.0.7',
-                      'mock>=4.0.3', 'portalocker>=2.3.2', 'networkx>=2.6.3', 'requests>=2.27.1',
+    install_requires=['cython','ruamel.yaml==0.17.21','packaging>19', 'six>=1.10.0', 'configobj>=5.0.6', 'argparse>=1.4.0', 'python-dateutil>=2.8.2',
+                       'pyparsing>=3.0.7', 'mock>=4.0.3', 'portalocker>=2.3.2', 'networkx>=2.6.3', 'requests>=2.27.1',
                       'bscearth.utils>=0.5.2', 'cryptography>=36.0.1', 'setuptools>=60.8.2',
                       'pip>=22.0.3', 'pythondialog', 'pytest', 'nose', 'coverage', 'PyNaCl>=1.4.0',
                       'Pygments'],
     classifiers=[
         "Programming Language :: Python :: 3.7",
         "Programming Language :: Python :: 3.9",
         "License :: OSI Approved :: GNU General Public License (GPL)",
         "Operating System :: POSIX :: Linux"
     ],
-)
+)
```


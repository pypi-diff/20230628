# Comparing `tmp/kanonym4text-0.0.8.tar.gz` & `tmp/kanonym4text-0.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kanonym4text-0.0.8.tar", last modified: Wed Jun 28 12:55:12 2023, max compression
+gzip compressed data, was "kanonym4text-0.0.9.tar", last modified: Wed Jun 28 13:03:11 2023, max compression
```

## Comparing `kanonym4text-0.0.8.tar` & `kanonym4text-0.0.9.tar`

### file list

```diff
@@ -1,22 +1,24 @@
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:55:12.853754 kanonym4text-0.0.8/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 12:55:12.853754 kanonym4text-0.0.8/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.8/README.md
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:55:12.853754 kanonym4text-0.0.8/kanonym4text/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 11:09:26.000000 kanonym4text-0.0.8/kanonym4text/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10627 2023-06-28 12:55:08.000000 kanonym4text-0.0.8/kanonym4text/k_anonym_text.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:55:12.853754 kanonym4text-0.0.8/kanonym4text/utils/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.8/kanonym4text/utils/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 12:10:36.000000 kanonym4text-0.0.8/kanonym4text/utils/anonym_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.8/kanonym4text/utils/cluster_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.8/kanonym4text/utils/llm_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.8/kanonym4text/utils/models.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.8/kanonym4text/utils/nlp_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.8/kanonym4text/utils/utilization_utils.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:55:12.853754 kanonym4text-0.0.8/kanonym4text.egg-info/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 12:55:12.000000 kanonym4text-0.0.8/kanonym4text.egg-info/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 12:55:12.000000 kanonym4text-0.0.8/kanonym4text.egg-info/SOURCES.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 12:55:12.000000 kanonym4text-0.0.8/kanonym4text.egg-info/dependency_links.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 12:55:12.000000 kanonym4text-0.0.8/kanonym4text.egg-info/requires.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 12:55:12.000000 kanonym4text-0.0.8/kanonym4text.egg-info/top_level.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 12:55:12.853754 kanonym4text-0.0.8/setup.cfg
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 12:53:36.000000 kanonym4text-0.0.8/setup.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 13:03:11.535129 kanonym4text-0.0.9/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 13:03:11.535129 kanonym4text-0.0.9/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.9/README.md
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 13:03:11.535129 kanonym4text-0.0.9/kanonym4text/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 11:09:26.000000 kanonym4text-0.0.9/kanonym4text/__init__.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 13:03:11.535129 kanonym4text-0.0.9/kanonym4text/data/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 13:02:05.000000 kanonym4text-0.0.9/kanonym4text/data/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10638 2023-06-28 13:02:50.000000 kanonym4text-0.0.9/kanonym4text/k_anonym_text.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 13:03:11.535129 kanonym4text-0.0.9/kanonym4text/utils/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.9/kanonym4text/utils/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 12:10:36.000000 kanonym4text-0.0.9/kanonym4text/utils/anonym_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.9/kanonym4text/utils/cluster_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.9/kanonym4text/utils/llm_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.9/kanonym4text/utils/models.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.9/kanonym4text/utils/nlp_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.9/kanonym4text/utils/utilization_utils.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 13:03:11.535129 kanonym4text-0.0.9/kanonym4text.egg-info/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 13:03:11.000000 kanonym4text-0.0.9/kanonym4text.egg-info/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      517 2023-06-28 13:03:11.000000 kanonym4text-0.0.9/kanonym4text.egg-info/SOURCES.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 13:03:11.000000 kanonym4text-0.0.9/kanonym4text.egg-info/dependency_links.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 13:03:11.000000 kanonym4text-0.0.9/kanonym4text.egg-info/requires.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 13:03:11.000000 kanonym4text-0.0.9/kanonym4text.egg-info/top_level.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 13:03:11.539129 kanonym4text-0.0.9/setup.cfg
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 13:03:09.000000 kanonym4text-0.0.9/setup.py
```

### Comparing `kanonym4text-0.0.8/PKG-INFO` & `kanonym4text-0.0.9/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.8
+Version: 0.0.9
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.8/README.md` & `kanonym4text-0.0.9/README.md`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text/k_anonym_text.py` & `kanonym4text-0.0.9/kanonym4text/k_anonym_text.py`

 * *Files 1% similar despite different names*

```diff
@@ -118,15 +118,15 @@
     """
     The main function. Runs the anonymization.
     """
     from kanonym4text.utils import nlp_utils, cluster_utils, utilization_utils, anonym_utils, models
 
     ####### TEMP #######
     print(os.getcwd())
-    stop_file = './data/5000_most_common_words_by_order.txt'
+    stop_file = 'kanonym4text/data/5000_most_common_words_by_order.txt'
     short_stopword_list = nlp_utils.stopwords.words('english')
     long_stopword_list = list(set(short_stopword_list + nlp_utils.get_list_from_file(stop_file, num_stop)))
     ####################
 
     init_logger(verbose)
 
     logging.info(f'{os.path.basename(__file__)} {__version__} WE pipeline')
```

### Comparing `kanonym4text-0.0.8/kanonym4text/utils/anonym_utils.py` & `kanonym4text-0.0.9/kanonym4text/utils/anonym_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text/utils/cluster_utils.py` & `kanonym4text-0.0.9/kanonym4text/utils/cluster_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text/utils/llm_utils.py` & `kanonym4text-0.0.9/kanonym4text/utils/llm_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text/utils/models.py` & `kanonym4text-0.0.9/kanonym4text/utils/models.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text/utils/nlp_utils.py` & `kanonym4text-0.0.9/kanonym4text/utils/nlp_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text/utils/utilization_utils.py` & `kanonym4text-0.0.9/kanonym4text/utils/utilization_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.8/kanonym4text.egg-info/PKG-INFO` & `kanonym4text-0.0.9/kanonym4text.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.8
+Version: 0.0.9
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.8/setup.py` & `kanonym4text-0.0.9/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.8'
+VERSION = '0.0.9'
 DESCRIPTION = 'k-anonymity for texts'
 LONG_DESCRIPTION = 'A package that applies k-anonymity on extual documents.'
 
 # Setting up
 setup(
     name="kanonym4text",
     version=VERSION,
```


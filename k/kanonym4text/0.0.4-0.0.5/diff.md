# Comparing `tmp/kanonym4text-0.0.4.tar.gz` & `tmp/kanonym4text-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kanonym4text-0.0.4.tar", last modified: Wed Jun 28 11:42:40 2023, max compression
+gzip compressed data, was "kanonym4text-0.0.5.tar", last modified: Wed Jun 28 12:13:00 2023, max compression
```

## Comparing `kanonym4text-0.0.4.tar` & `kanonym4text-0.0.5.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.4/README.md
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/kanonym4text/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 11:09:26.000000 kanonym4text-0.0.4/kanonym4text/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10291 2023-06-28 11:41:45.000000 kanonym4text-0.0.4/kanonym4text/k_anonym_text.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/kanonym4text/utils/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.4/kanonym4text/utils/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/anonym_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/cluster_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.4/kanonym4text/utils/llm_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.4/kanonym4text/utils/models.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/nlp_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/utilization_utils.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/kanonym4text.egg-info/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/SOURCES.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/dependency_links.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/requires.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/top_level.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/setup.cfg
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 11:42:27.000000 kanonym4text-0.0.4/setup.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:13:00.341187 kanonym4text-0.0.5/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 12:13:00.341187 kanonym4text-0.0.5/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.5/README.md
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:13:00.341187 kanonym4text-0.0.5/kanonym4text/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 11:09:26.000000 kanonym4text-0.0.5/kanonym4text/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10304 2023-06-28 12:12:01.000000 kanonym4text-0.0.5/kanonym4text/k_anonym_text.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:13:00.341187 kanonym4text-0.0.5/kanonym4text/utils/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.5/kanonym4text/utils/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 12:10:36.000000 kanonym4text-0.0.5/kanonym4text/utils/anonym_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.5/kanonym4text/utils/cluster_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.5/kanonym4text/utils/llm_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.5/kanonym4text/utils/models.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.5/kanonym4text/utils/nlp_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.5/kanonym4text/utils/utilization_utils.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 12:13:00.341187 kanonym4text-0.0.5/kanonym4text.egg-info/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 12:13:00.000000 kanonym4text-0.0.5/kanonym4text.egg-info/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 12:13:00.000000 kanonym4text-0.0.5/kanonym4text.egg-info/SOURCES.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 12:13:00.000000 kanonym4text-0.0.5/kanonym4text.egg-info/dependency_links.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 12:13:00.000000 kanonym4text-0.0.5/kanonym4text.egg-info/requires.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 12:13:00.000000 kanonym4text-0.0.5/kanonym4text.egg-info/top_level.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 12:13:00.341187 kanonym4text-0.0.5/setup.cfg
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 12:12:32.000000 kanonym4text-0.0.5/setup.py
```

### Comparing `kanonym4text-0.0.4/PKG-INFO` & `kanonym4text-0.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.4
+Version: 0.0.5
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.4/README.md` & `kanonym4text-0.0.5/README.md`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text/k_anonym_text.py` & `kanonym4text-0.0.5/kanonym4text/k_anonym_text.py`

 * *Files 0% similar despite different names*

```diff
@@ -133,15 +133,15 @@
     
     wemodel = models.upload_we_model(wemodel)
     if wemodel is None:
         exit(1) 
 
     # TEMP
     prefix = 'temp_prefix' # TEMP
-    stop_file = 'data/5000_most_common_words_by_order.txt'
+    stop_file = 'kanonym4text/data/5000_most_common_words_by_order.txt'
 
     logging.info(f'Number of documents: {df.shape[0]}')  # Logging
     
     short_stopword_list = nlp_utils.stopwords.words('english')
     long_stopword_list = list(set(short_stopword_list + nlp_utils.get_list_from_file(stop_file, num_stop)))
 
     out_str = f'Stopword list contains {len(long_stopword_list)} words'
```

### Comparing `kanonym4text-0.0.4/kanonym4text/utils/anonym_utils.py` & `kanonym4text-0.0.5/kanonym4text/utils/anonym_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text/utils/cluster_utils.py` & `kanonym4text-0.0.5/kanonym4text/utils/cluster_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text/utils/llm_utils.py` & `kanonym4text-0.0.5/kanonym4text/utils/llm_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text/utils/models.py` & `kanonym4text-0.0.5/kanonym4text/utils/models.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text/utils/nlp_utils.py` & `kanonym4text-0.0.5/kanonym4text/utils/nlp_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text/utils/utilization_utils.py` & `kanonym4text-0.0.5/kanonym4text/utils/utilization_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.4/kanonym4text.egg-info/PKG-INFO` & `kanonym4text-0.0.5/kanonym4text.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.4
+Version: 0.0.5
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.4/setup.py` & `kanonym4text-0.0.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.4'
+VERSION = '0.0.5'
 DESCRIPTION = 'k-anonymity for texts'
 LONG_DESCRIPTION = 'A package that applies k-anonymity on extual documents.'
 
 # Setting up
 setup(
     name="kanonym4text",
     version=VERSION,
```


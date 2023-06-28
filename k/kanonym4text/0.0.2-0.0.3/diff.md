# Comparing `tmp/kanonym4text-0.0.2.tar.gz` & `tmp/kanonym4text-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kanonym4text-0.0.2.tar", last modified: Wed Jun 28 09:44:42 2023, max compression
+gzip compressed data, was "kanonym4text-0.0.3.tar", last modified: Wed Jun 28 10:13:29 2023, max compression
```

## Comparing `kanonym4text-0.0.2.tar` & `kanonym4text-0.0.3.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.2/README.md
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.916198 kanonym4text-0.0.2/kanonym4text/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       48 2023-06-28 09:12:08.000000 kanonym4text-0.0.2/kanonym4text/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10256 2023-06-28 09:42:04.000000 kanonym4text-0.0.2/kanonym4text/k_anonym_text.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/kanonym4text/utils/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.2/kanonym4text/utils/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/anonym_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/cluster_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.2/kanonym4text/utils/llm_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.2/kanonym4text/utils/models.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/nlp_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/utilization_utils.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/kanonym4text.egg-info/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/SOURCES.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/dependency_links.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/requires.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/top_level.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/setup.cfg
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 09:43:50.000000 kanonym4text-0.0.2/setup.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.3/README.md
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/kanonym4text/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 10:12:22.000000 kanonym4text-0.0.3/kanonym4text/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10274 2023-06-28 09:50:44.000000 kanonym4text-0.0.3/kanonym4text/k_anonym_text.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/kanonym4text/utils/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.3/kanonym4text/utils/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/anonym_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/cluster_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.3/kanonym4text/utils/llm_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.3/kanonym4text/utils/models.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/nlp_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/utilization_utils.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/kanonym4text.egg-info/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 10:13:29.000000 kanonym4text-0.0.3/kanonym4text.egg-info/SOURCES.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/dependency_links.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/requires.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/top_level.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/setup.cfg
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 10:12:48.000000 kanonym4text-0.0.3/setup.py
```

### Comparing `kanonym4text-0.0.2/PKG-INFO` & `kanonym4text-0.0.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.2
+Version: 0.0.3
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.2/README.md` & `kanonym4text-0.0.3/README.md`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text/k_anonym_text.py` & `kanonym4text-0.0.3/kanonym4text/k_anonym_text.py`

 * *Files 1% similar despite different names*

```diff
@@ -209,16 +209,16 @@
     Defines the ArgumentParser
     :return: The parser
     """
     parser_func = argparse.ArgumentParser(description='Converts dot tree to newick tree format')
     parser_func.add_argument('-f', '--file', help='Input CSV file', required=True)
 
     parser_func.add_argument('-k', help='The k anonymity degree',  required=True)
-    parser_func.add_argument('-s', '--stop', help='Stop word list file. default=data/1000_most_common_words.txt', 
-                             default='data/1000_most_common_words.txt')
+    parser_func.add_argument('-s', '--stop', help='Stop word list file. default=data/5000_most_common_words_by_order.txt', 
+                             default='data/5000_most_common_words_by_order.txt')
     parser_func.add_argument('--col', help='Text column. Default - txt', default='txt')
     parser_func.add_argument('--out', help='Output file name. default - based on input file and k')
     parser_func.add_argument('--llm', action="store_true",
                              help='Use LLM methods. default: False')
     parser_func.add_argument('--plot', action="store_true",
                              help='Plot semantic distance before and after the anonymization. default: False')
     parser_func.add_argument('--sample',
```

### Comparing `kanonym4text-0.0.2/kanonym4text/utils/anonym_utils.py` & `kanonym4text-0.0.3/kanonym4text/utils/anonym_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text/utils/cluster_utils.py` & `kanonym4text-0.0.3/kanonym4text/utils/cluster_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text/utils/llm_utils.py` & `kanonym4text-0.0.3/kanonym4text/utils/llm_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text/utils/models.py` & `kanonym4text-0.0.3/kanonym4text/utils/models.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text/utils/nlp_utils.py` & `kanonym4text-0.0.3/kanonym4text/utils/nlp_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text/utils/utilization_utils.py` & `kanonym4text-0.0.3/kanonym4text/utils/utilization_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.2/kanonym4text.egg-info/PKG-INFO` & `kanonym4text-0.0.3/kanonym4text.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.2
+Version: 0.0.3
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.2/setup.py` & `kanonym4text-0.0.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.2'
+VERSION = '0.0.3'
 DESCRIPTION = 'k-anonymity for texts'
 LONG_DESCRIPTION = 'A package that applies k-anonymity on extual documents.'
 
 # Setting up
 setup(
     name="kanonym4text",
     version=VERSION,
```


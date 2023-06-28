# Comparing `tmp/kanonym4text-0.0.3.tar.gz` & `tmp/kanonym4text-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kanonym4text-0.0.3.tar", last modified: Wed Jun 28 10:13:29 2023, max compression
+gzip compressed data, was "kanonym4text-0.0.4.tar", last modified: Wed Jun 28 11:42:40 2023, max compression
```

## Comparing `kanonym4text-0.0.3.tar` & `kanonym4text-0.0.4.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.3/README.md
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/kanonym4text/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 10:12:22.000000 kanonym4text-0.0.3/kanonym4text/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10274 2023-06-28 09:50:44.000000 kanonym4text-0.0.3/kanonym4text/k_anonym_text.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/kanonym4text/utils/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.3/kanonym4text/utils/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/anonym_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/cluster_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.3/kanonym4text/utils/llm_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.3/kanonym4text/utils/models.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/nlp_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.3/kanonym4text/utils/utilization_utils.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/kanonym4text.egg-info/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 10:13:29.000000 kanonym4text-0.0.3/kanonym4text.egg-info/SOURCES.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/dependency_links.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/requires.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 10:13:28.000000 kanonym4text-0.0.3/kanonym4text.egg-info/top_level.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 10:13:29.050572 kanonym4text-0.0.3/setup.cfg
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 10:12:48.000000 kanonym4text-0.0.3/setup.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.4/README.md
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/kanonym4text/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       51 2023-06-28 11:09:26.000000 kanonym4text-0.0.4/kanonym4text/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10291 2023-06-28 11:41:45.000000 kanonym4text-0.0.4/kanonym4text/k_anonym_text.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/kanonym4text/utils/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.4/kanonym4text/utils/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/anonym_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/cluster_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.4/kanonym4text/utils/llm_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.4/kanonym4text/utils/models.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/nlp_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.4/kanonym4text/utils/utilization_utils.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/kanonym4text.egg-info/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/SOURCES.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/dependency_links.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/requires.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 11:42:40.000000 kanonym4text-0.0.4/kanonym4text.egg-info/top_level.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 11:42:40.109085 kanonym4text-0.0.4/setup.cfg
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 11:42:27.000000 kanonym4text-0.0.4/setup.py
```

### Comparing `kanonym4text-0.0.3/PKG-INFO` & `kanonym4text-0.0.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.3
+Version: 0.0.4
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.3/README.md` & `kanonym4text-0.0.4/README.md`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text/k_anonym_text.py` & `kanonym4text-0.0.4/kanonym4text/k_anonym_text.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,15 +24,15 @@
 warnings.filterwarnings("ignore", message=".*The 'nopython' keyword.*")
 
 
 def llm_method(df: pd.DataFrame, k: int, col: str='txt', plot: bool=False, n_jobs: int = 1, verbose: int=0):
     """
     Uses LLM methods to preform anonymization
     """
-    from utils import llm_utils, utilization_utils, anonym_utils
+    from kanonym4text.utils import llm_utils, utilization_utils, anonym_utils
 
     # TEMP
     prefix = 'temp_prefix_llm' # TEMP
     init_logger(verbose)
     # logging.info('Start LLM pipeline')  # Logging
     logging.info(f'{os.path.basename(__file__)} {__version__} LLM pipeline')
 
@@ -114,15 +114,15 @@
 
 # def run_anonym(arguments):
 def run_anonym(df: pd.DataFrame, k: int, col: str='txt', plot: bool=False, wemodel: str = 'fasttext-wiki-news-subwords-300',
                 num_stop: int = 0, n_jobs: int = 1, verbose: int=0):
     """
     The main function. Runs the anonymization.
     """
-    from utils import nlp_utils, cluster_utils, utilization_utils, anonym_utils, models
+    from kanonym4text.utils import nlp_utils, cluster_utils, utilization_utils, anonym_utils, models
 
     init_logger(verbose)
 
     logging.info(f'{os.path.basename(__file__)} {__version__} WE pipeline')
     logging.info(f'Word embedding model: {wemodel}')  # Logging
 
     # Uploading the word embedding model
@@ -209,15 +209,15 @@
     Defines the ArgumentParser
     :return: The parser
     """
     parser_func = argparse.ArgumentParser(description='Converts dot tree to newick tree format')
     parser_func.add_argument('-f', '--file', help='Input CSV file', required=True)
 
     parser_func.add_argument('-k', help='The k anonymity degree',  required=True)
-    parser_func.add_argument('-s', '--stop', help='Stop word list file. default=data/5000_most_common_words_by_order.txt', 
+    parser_func.add_argument('-s', '--stop', help='Stop word list file. default=data/1000_most_common_words.txt', 
                              default='data/5000_most_common_words_by_order.txt')
     parser_func.add_argument('--col', help='Text column. Default - txt', default='txt')
     parser_func.add_argument('--out', help='Output file name. default - based on input file and k')
     parser_func.add_argument('--llm', action="store_true",
                              help='Use LLM methods. default: False')
     parser_func.add_argument('--plot', action="store_true",
                              help='Plot semantic distance before and after the anonymization. default: False')
```

### Comparing `kanonym4text-0.0.3/kanonym4text/utils/anonym_utils.py` & `kanonym4text-0.0.4/kanonym4text/utils/anonym_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text/utils/cluster_utils.py` & `kanonym4text-0.0.4/kanonym4text/utils/cluster_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text/utils/llm_utils.py` & `kanonym4text-0.0.4/kanonym4text/utils/llm_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text/utils/models.py` & `kanonym4text-0.0.4/kanonym4text/utils/models.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text/utils/nlp_utils.py` & `kanonym4text-0.0.4/kanonym4text/utils/nlp_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text/utils/utilization_utils.py` & `kanonym4text-0.0.4/kanonym4text/utils/utilization_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.3/kanonym4text.egg-info/PKG-INFO` & `kanonym4text-0.0.4/kanonym4text.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.3
+Version: 0.0.4
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.3/setup.py` & `kanonym4text-0.0.4/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.3'
+VERSION = '0.0.4'
 DESCRIPTION = 'k-anonymity for texts'
 LONG_DESCRIPTION = 'A package that applies k-anonymity on extual documents.'
 
 # Setting up
 setup(
     name="kanonym4text",
     version=VERSION,
```


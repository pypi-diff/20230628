# Comparing `tmp/kanonym4text-0.0.1.tar.gz` & `tmp/kanonym4text-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kanonym4text-0.0.1.tar", last modified: Wed Jun 28 09:38:36 2023, max compression
+gzip compressed data, was "kanonym4text-0.0.2.tar", last modified: Wed Jun 28 09:44:42 2023, max compression
```

## Comparing `kanonym4text-0.0.1.tar` & `kanonym4text-0.0.2.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:38:36.838090 kanonym4text-0.0.1/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 09:38:36.838090 kanonym4text-0.0.1/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.1/README.md
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:38:36.834090 kanonym4text-0.0.1/kanonym4text/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       48 2023-06-28 09:12:08.000000 kanonym4text-0.0.1/kanonym4text/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10524 2023-06-28 09:08:35.000000 kanonym4text-0.0.1/kanonym4text/k_anonym_text.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:38:36.838090 kanonym4text-0.0.1/kanonym4text/utils/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.1/kanonym4text/utils/__init__.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.1/kanonym4text/utils/anonym_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.1/kanonym4text/utils/cluster_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.1/kanonym4text/utils/llm_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.1/kanonym4text/utils/models.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.1/kanonym4text/utils/nlp_utils.py
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.1/kanonym4text/utils/utilization_utils.py
-drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:38:36.834090 kanonym4text-0.0.1/kanonym4text.egg-info/
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 09:38:36.000000 kanonym4text-0.0.1/kanonym4text.egg-info/PKG-INFO
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 09:38:36.000000 kanonym4text-0.0.1/kanonym4text.egg-info/SOURCES.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 09:38:36.000000 kanonym4text-0.0.1/kanonym4text.egg-info/dependency_links.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 09:38:36.000000 kanonym4text-0.0.1/kanonym4text.egg-info/requires.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 09:38:36.000000 kanonym4text-0.0.1/kanonym4text.egg-info/top_level.txt
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 09:38:36.838090 kanonym4text-0.0.1/setup.cfg
--rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 09:37:52.000000 kanonym4text-0.0.1/setup.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3128 2023-06-28 09:00:50.000000 kanonym4text-0.0.2/README.md
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.916198 kanonym4text-0.0.2/kanonym4text/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       48 2023-06-28 09:12:08.000000 kanonym4text-0.0.2/kanonym4text/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    10256 2023-06-28 09:42:04.000000 kanonym4text-0.0.2/kanonym4text/k_anonym_text.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/kanonym4text/utils/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:11:15.000000 kanonym4text-0.0.2/kanonym4text/utils/__init__.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    13374 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/anonym_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     8761 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/cluster_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     6128 2023-06-28 09:09:21.000000 kanonym4text-0.0.2/kanonym4text/utils/llm_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      939 2023-06-28 09:09:21.000000 kanonym4text-0.0.2/kanonym4text/utils/models.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)    11195 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/nlp_utils.py
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     3187 2023-06-28 09:09:22.000000 kanonym4text-0.0.2/kanonym4text/utils/utilization_utils.py
+drwxrwxr-x   0 neumanh   (1000) neumanh   (1001)        0 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/kanonym4text.egg-info/
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      660 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/PKG-INFO
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      487 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/SOURCES.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)        1 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/dependency_links.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)      189 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/requires.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       13 2023-06-28 09:44:42.000000 kanonym4text-0.0.2/kanonym4text.egg-info/top_level.txt
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)       38 2023-06-28 09:44:42.920198 kanonym4text-0.0.2/setup.cfg
+-rw-rw-r--   0 neumanh   (1000) neumanh   (1001)     1193 2023-06-28 09:43:50.000000 kanonym4text-0.0.2/setup.py
```

### Comparing `kanonym4text-0.0.1/PKG-INFO` & `kanonym4text-0.0.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.1
+Version: 0.0.2
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.1/README.md` & `kanonym4text-0.0.2/README.md`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text/k_anonym_text.py` & `kanonym4text-0.0.2/kanonym4text/k_anonym_text.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,278 +1,278 @@
-#!/usr/bin/python3
-
-"""
-K-anonymity for texts
-"""
-
-# Info
-__author__ = 'Lior Treiman and Hadas Neuman'
-__version__ = '1.1'
-__date__ = '3/6/23'
-
-# Imports
-import sys
-import pandas as pd
-import numpy as np
-import re
-import os
-import argparse
-from datetime import datetime
-import time
-import warnings
-from datetime import date
-import logging
-warnings.filterwarnings("ignore", message=".*The 'nopython' keyword.*")
-
-
-def llm_method(df: pd.DataFrame, k: int, col: str='txt', plot: bool=False, n_jobs: int = 1, verbose: int=0):
-    """
-    Uses LLM methods to preform anonymization
-    """
-    from utils import llm_utils, utilization_utils, anonym_utils
-
-    # TEMP
-    prefix = 'temp_prefix_llm' # TEMP
-    init_logger(verbose)
-    # logging.info('Start LLM pipeline')  # Logging
-    logging.info(f'{os.path.basename(__file__)} {__version__} LLM pipeline')
-
-    # Adding number of characters
-    num_chars_col = 'Num_characters'
-    df[num_chars_col] = df[col].str.len()
-    docs = df[col]
-    
-    logging.info(f'Number of documents: {len(docs)}')
-    logging.info(f'Average number of characters in documents: {df[num_chars_col].mean()} maximum characters in a document {df[num_chars_col].max()}')
-
-    # Runing the anonymization
-    annon_docs, _ = llm_utils.run_anonymization_on_txt(docs, k, n_jobs)
-    df['anonymized_text'] = annon_docs
-
-    curr_k, non_anon_indexes = anonym_utils.get_anonym_degree(docs=annon_docs, min_k=k)
-    out_str = f'Anonymity after reduction:{curr_k}  number of un-anonymized documents: {len(non_anon_indexes)}'
-    logging.info(out_str)  # Logging
-
-    # Logging the un-anonymized documents
-    if len(non_anon_indexes) > 0: 
-        out_str = f'Un-anonymized documents: {non_anon_indexes}'
-        logging.info(out_str)  # Logging
-
-    # Utilization utils
-    if plot:
-        plot_prefix = prefix
-    else:
-        plot_prefix = None
-    mean_dist = utilization_utils.get_mean_semantice_distance_for_corpus(df[col], df['anonymized_text'], prefix=plot_prefix)
-    out_str = f'Mean semantic distance before and after the anonymization process: {mean_dist}'
-    logging.info(out_str)  # Logging
-
-    logging.info('Done')  # Logging
-    return df, mean_dist
-
-
-def get_prefix(arguments):
-    """
-    Creates a prefix based on the input file and k.
-    """
-    # Removing extension
-    if arguments.out:
-        file = arguments.out
-    else:
-        file = arguments.file
-
-    _, file_extension = os.path.splitext(file)
-    base_name = os.path.basename(file).replace(file_extension, '')
-    prefix = f'{base_name}_k{arguments.k}_stop_{arguments.num_stop}'
-
-    if arguments.sample:
-         prefix += f'_sample_of_{arguments.sample}'
-
-    # LLM
-    if arguments.llm:
-        prefix += '_llm'
-    
-
-    return prefix
-
-
-def init_logger(verbose):
-    """
-    Initiating the logger
-    """
-    # log_name = f'logs/{prefix}.log'
-    logging.basicConfig(
-    level=max(0, 30 - (verbose*10)),
-    format='%(asctime)s.%(msecs)03d %(levelname)s %(module)s - %(funcName)s: %(message)s')
-
-
-def print_size(var, var_name):
-    """
-    Prints the variable size to the log
-    """
-    logging.debug(f'The size of {var_name}: {sys.getsizeof(var)/1000000}MB')
-
-
-# def run_anonym(arguments):
-def run_anonym(df: pd.DataFrame, k: int, col: str='txt', plot: bool=False, wemodel: str = 'fasttext-wiki-news-subwords-300',
-                num_stop: int = 0, n_jobs: int = 1, verbose: int=0):
-    """
-    The main function. Runs the anonymization.
-    """
-    from utils import nlp_utils, cluster_utils, utilization_utils, anonym_utils, models
-
-    init_logger(verbose)
-
-    logging.info(f'{os.path.basename(__file__)} {__version__} WE pipeline')
-    logging.info(f'Word embedding model: {wemodel}')  # Logging
-
-    # Uploading the word embedding model
-    if wemodel == 'glove-twitter-25':
-        cos = False
-    else:
-        cos = True
-    
-    wemodel = models.upload_we_model(wemodel)
-    if wemodel is None:
-        exit(1) 
-
-    # TEMP
-    prefix = 'temp_prefix' # TEMP
-    stop_file = 'data/1000_most_common_words.txt'
-
-    logging.info(f'Number of documents: {df.shape[0]}')  # Logging
-    
-    short_stopword_list = nlp_utils.stopwords.words('english')
-    long_stopword_list = list(set(short_stopword_list + nlp_utils.get_list_from_file(stop_file, num_stop)))
-
-    out_str = f'Stopword list contains {len(long_stopword_list)} words'
-    logging.info(out_str)  # Logging
-
-    # Creating the word dictionary and word list
-    word_dict = nlp_utils.create_word_dict(df[col], long_stopword_list)  # this function takes too long need to make more efficient
-    out_str = f'Number of unique words in dataset: {len(word_dict)}'
-    logging.info(out_str)  # Logging
-
-    # Run clustering
-    cluster_dict, dist_dict, _ = cluster_utils.run_clustering(word_dict, stop_list=long_stopword_list, wemodel=wemodel, cosine=cos, n_jobs=n_jobs)
-    out_str = f'Number of DBSCAN clusters:\t {len(cluster_dict)}'
-    logging.info(out_str)  # Logging
-
-    # Generalization
-    df, _, long_stopword_list = nlp_utils.replace_words_in_df(df, cluster_dict, dist_dict, word_dict, 
-                                                              col, wemodel=wemodel, stop_list = long_stopword_list)
-    out_str = f'Generalization completed.'
-    logging.info(out_str)  # Logging
-    
-    # Find k neighbors
-    neighbor_list = anonym_utils.ckmeans_clustering(docs=df['anon_txt'], k=k, n_jobs=n_jobs, stop_list=short_stopword_list)
-
-    out_str = f'Found {len(neighbor_list)} groups of {k} neighbors'
-    logging.info(out_str)  # Logging
-
-    # Reduction
-    force_anon_txt_annoy = anonym_utils.force_anonym(docs=df['anon_txt'], neighbor_list=neighbor_list, stop_list=long_stopword_list)
-
-    # Testing success
-    curr_k, non_anon_indexes = anonym_utils.get_anonym_degree(docs=force_anon_txt_annoy, min_k=k, stop_list=long_stopword_list)
-    out_str = f'Anonymity after reduction:{curr_k}  number of un-anonymized documents: {len(non_anon_indexes)}'
-    logging.info(out_str)  # Logging
-
-    # Logging the un-anonymized documents
-    if len(non_anon_indexes) > 0: 
-        out_str = f'Un-anonymized documents: {non_anon_indexes}'
-        logging.info(out_str)  # Logging
-
-    # Adding the anonymized corpus to the dataframe
-    anonym_col = 'force_anon_txt'
-    df[anonym_col] = force_anon_txt_annoy
-    del(force_anon_txt_annoy)  # Freeing space
-    df = anonym_utils.add_neighbor_list_to_df(df, neighbor_list)
-    # Counting the number of words and *
-    df['num_of_words_after_forcing'] = df['force_anon_txt'].apply(lambda x: len(re.findall(r'\w+', x)))
-    df['num_of_deleting_after_forcing'] = df['force_anon_txt'].apply(lambda x: len(re.findall(r'\*', x)))
-
-    # Utilization utils
-    if plot:
-        plot_prefix = prefix
-    else:
-        plot_prefix = None
-    mean_dist = utilization_utils.get_mean_semantice_distance_for_corpus(df[col], df[anonym_col], prefix=plot_prefix)
-    out_str = f'Mean semantic distance before and after the anonymization process: {mean_dist}'
-    logging.info(out_str)  # Logging
-    
-    logging.info('Done')  # Logging
-    return df, mean_dist
-
-
-def parse_args():
-    """
-    Defines the ArgumentParser
-    :return: The parser
-    """
-    parser_func = argparse.ArgumentParser(description='Converts dot tree to newick tree format')
-    parser_func.add_argument('-f', '--file', help='Input CSV file', required=True)
-
-    parser_func.add_argument('-k', help='The k anonymity degree',  required=True)
-    parser_func.add_argument('-s', '--stop', help='Stop word list file. default=data/1000_most_common_words.txt', 
-                             default='data/1000_most_common_words.txt')
-    parser_func.add_argument('--col', help='Text column. Default - txt', default='txt')
-    parser_func.add_argument('--out', help='Output file name. default - based on input file and k')
-    parser_func.add_argument('--llm', action="store_true",
-                             help='Use LLM methods. default: False')
-    parser_func.add_argument('--plot', action="store_true",
-                             help='Plot semantic distance before and after the anonymization. default: False')
-    parser_func.add_argument('--sample', 
-                             help='Take only the first N rows. For debugging.', type=int)
-    parser_func.add_argument('--wemodel', 
-                             help='Word embedding model.', default='fasttext-wiki-news-subwords-300')
-    parser_func.add_argument('--num_stop', 
-                             help='Number of stop words, ordered by frequency. Must be between 0-5000. default 1000', type=int, default='1000')
-    parser_func.add_argument('--n_jobs',
-                             help='The number of parallel jobs to run. -1 means using all processors. default -1', 
-                             type=int, default=1)
-    parser_func.add_argument('--verbose', type=int, default=0,
-                             help='Prevent the program from displaying screen output. default: 0')
-    parser_func.add_argument('-version', action='version', version='%(prog)s:' + ' %s-%s' % (__version__, __date__))
-    return parser_func
-
-
-def run_from_command_line():
-    """
-    Runs the functions from command line
-    """
-    parser = parse_args()
-    args = parser.parse_args()
-
-    # getting the input arguments
-    input_file = args.file  # Input database
-    k = int(args.k)  # Desired k degree
-    col = args.col  # The text columns  
-
-    # df from csv
-    df = pd.read_csv(input_file)
-    if args.sample:
-        df = df.head(args.sample)
-
-    prefix = get_prefix(args) 
-
-    if not args.llm:
-        df, mean_dist = run_anonym(df=df, k=k, col=col, plot=args.plot, num_stop=args.num_stop, wemodel=args.wemodel, n_jobs=args.n_jobs, verbose=args.verbose)
-    else:
-        df, mean_dist = llm_method(df=df, k=k, col=col, plot=args.plot, n_jobs=args.n_jobs, verbose=args.verbose)
-    
-    print('Mean semantic distance:', mean_dist)
-    # Saving
-    if args.out:
-        output_name = args.out
-    else:
-        output_name = f'{prefix}_anonymized.csv'
-    out_file = 'outputs/' + output_name
-    df.to_csv(out_file, index=False)
-    
-
-if __name__ == "__main__":    
-    start_time = time.time()
-    run_from_command_line()
-    print(f'Running time: {round((time.time() - start_time),2)} seconds')
-    
+#!/usr/bin/python3
+
+"""
+K-anonymity for texts
+"""
+
+# Info
+__author__ = 'Lior Treiman and Hadas Neuman'
+__version__ = '1.1'
+__date__ = '3/6/23'
+
+# Imports
+import sys
+import pandas as pd
+import numpy as np
+import re
+import os
+import argparse
+from datetime import datetime
+import time
+import warnings
+from datetime import date
+import logging
+warnings.filterwarnings("ignore", message=".*The 'nopython' keyword.*")
+
+
+def llm_method(df: pd.DataFrame, k: int, col: str='txt', plot: bool=False, n_jobs: int = 1, verbose: int=0):
+    """
+    Uses LLM methods to preform anonymization
+    """
+    from utils import llm_utils, utilization_utils, anonym_utils
+
+    # TEMP
+    prefix = 'temp_prefix_llm' # TEMP
+    init_logger(verbose)
+    # logging.info('Start LLM pipeline')  # Logging
+    logging.info(f'{os.path.basename(__file__)} {__version__} LLM pipeline')
+
+    # Adding number of characters
+    num_chars_col = 'Num_characters'
+    df[num_chars_col] = df[col].str.len()
+    docs = df[col]
+    
+    logging.info(f'Number of documents: {len(docs)}')
+    logging.info(f'Average number of characters in documents: {df[num_chars_col].mean()} maximum characters in a document {df[num_chars_col].max()}')
+
+    # Runing the anonymization
+    annon_docs, _ = llm_utils.run_anonymization_on_txt(docs, k, n_jobs)
+    df['anonymized_text'] = annon_docs
+
+    curr_k, non_anon_indexes = anonym_utils.get_anonym_degree(docs=annon_docs, min_k=k)
+    out_str = f'Anonymity after reduction:{curr_k}  number of un-anonymized documents: {len(non_anon_indexes)}'
+    logging.info(out_str)  # Logging
+
+    # Logging the un-anonymized documents
+    if len(non_anon_indexes) > 0: 
+        out_str = f'Un-anonymized documents: {non_anon_indexes}'
+        logging.info(out_str)  # Logging
+
+    # Utilization utils
+    if plot:
+        plot_prefix = prefix
+    else:
+        plot_prefix = None
+    mean_dist = utilization_utils.get_mean_semantice_distance_for_corpus(df[col], df['anonymized_text'], prefix=plot_prefix)
+    out_str = f'Mean semantic distance before and after the anonymization process: {mean_dist}'
+    logging.info(out_str)  # Logging
+
+    logging.info('Done')  # Logging
+    return df, mean_dist
+
+
+def get_prefix(arguments):
+    """
+    Creates a prefix based on the input file and k.
+    """
+    # Removing extension
+    if arguments.out:
+        file = arguments.out
+    else:
+        file = arguments.file
+
+    _, file_extension = os.path.splitext(file)
+    base_name = os.path.basename(file).replace(file_extension, '')
+    prefix = f'{base_name}_k{arguments.k}_stop_{arguments.num_stop}'
+
+    if arguments.sample:
+         prefix += f'_sample_of_{arguments.sample}'
+
+    # LLM
+    if arguments.llm:
+        prefix += '_llm'
+    
+
+    return prefix
+
+
+def init_logger(verbose):
+    """
+    Initiating the logger
+    """
+    # log_name = f'logs/{prefix}.log'
+    logging.basicConfig(
+    level=max(0, 30 - (verbose*10)),
+    format='%(asctime)s.%(msecs)03d %(levelname)s %(module)s - %(funcName)s: %(message)s')
+
+
+def print_size(var, var_name):
+    """
+    Prints the variable size to the log
+    """
+    logging.debug(f'The size of {var_name}: {sys.getsizeof(var)/1000000}MB')
+
+
+# def run_anonym(arguments):
+def run_anonym(df: pd.DataFrame, k: int, col: str='txt', plot: bool=False, wemodel: str = 'fasttext-wiki-news-subwords-300',
+                num_stop: int = 0, n_jobs: int = 1, verbose: int=0):
+    """
+    The main function. Runs the anonymization.
+    """
+    from utils import nlp_utils, cluster_utils, utilization_utils, anonym_utils, models
+
+    init_logger(verbose)
+
+    logging.info(f'{os.path.basename(__file__)} {__version__} WE pipeline')
+    logging.info(f'Word embedding model: {wemodel}')  # Logging
+
+    # Uploading the word embedding model
+    if wemodel == 'glove-twitter-25':
+        cos = False
+    else:
+        cos = True
+    
+    wemodel = models.upload_we_model(wemodel)
+    if wemodel is None:
+        exit(1) 
+
+    # TEMP
+    prefix = 'temp_prefix' # TEMP
+    stop_file = 'data/5000_most_common_words_by_order.txt'
+
+    logging.info(f'Number of documents: {df.shape[0]}')  # Logging
+    
+    short_stopword_list = nlp_utils.stopwords.words('english')
+    long_stopword_list = list(set(short_stopword_list + nlp_utils.get_list_from_file(stop_file, num_stop)))
+
+    out_str = f'Stopword list contains {len(long_stopword_list)} words'
+    logging.info(out_str)  # Logging
+
+    # Creating the word dictionary and word list
+    word_dict = nlp_utils.create_word_dict(df[col], long_stopword_list)  # this function takes too long need to make more efficient
+    out_str = f'Number of unique words in dataset: {len(word_dict)}'
+    logging.info(out_str)  # Logging
+
+    # Run clustering
+    cluster_dict, dist_dict, _ = cluster_utils.run_clustering(word_dict, stop_list=long_stopword_list, wemodel=wemodel, cosine=cos, n_jobs=n_jobs)
+    out_str = f'Number of DBSCAN clusters:\t {len(cluster_dict)}'
+    logging.info(out_str)  # Logging
+
+    # Generalization
+    df, _, long_stopword_list = nlp_utils.replace_words_in_df(df, cluster_dict, dist_dict, word_dict, 
+                                                              col, wemodel=wemodel, stop_list = long_stopword_list)
+    out_str = f'Generalization completed.'
+    logging.info(out_str)  # Logging
+    
+    # Find k neighbors
+    neighbor_list = anonym_utils.ckmeans_clustering(docs=df['anon_txt'], k=k, n_jobs=n_jobs, stop_list=short_stopword_list)
+
+    out_str = f'Found {len(neighbor_list)} groups of {k} neighbors'
+    logging.info(out_str)  # Logging
+
+    # Reduction
+    force_anon_txt_annoy = anonym_utils.force_anonym(docs=df['anon_txt'], neighbor_list=neighbor_list, stop_list=long_stopword_list)
+
+    # Testing success
+    curr_k, non_anon_indexes = anonym_utils.get_anonym_degree(docs=force_anon_txt_annoy, min_k=k, stop_list=long_stopword_list)
+    out_str = f'Anonymity after reduction:{curr_k}  number of un-anonymized documents: {len(non_anon_indexes)}'
+    logging.info(out_str)  # Logging
+
+    # Logging the un-anonymized documents
+    if len(non_anon_indexes) > 0: 
+        out_str = f'Un-anonymized documents: {non_anon_indexes}'
+        logging.info(out_str)  # Logging
+
+    # Adding the anonymized corpus to the dataframe
+    anonym_col = 'force_anon_txt'
+    df[anonym_col] = force_anon_txt_annoy
+    del(force_anon_txt_annoy)  # Freeing space
+    df = anonym_utils.add_neighbor_list_to_df(df, neighbor_list)
+    # Counting the number of words and *
+    df['num_of_words_after_forcing'] = df['force_anon_txt'].apply(lambda x: len(re.findall(r'\w+', x)))
+    df['num_of_deleting_after_forcing'] = df['force_anon_txt'].apply(lambda x: len(re.findall(r'\*', x)))
+
+    # Utilization utils
+    if plot:
+        plot_prefix = prefix
+    else:
+        plot_prefix = None
+    mean_dist = utilization_utils.get_mean_semantice_distance_for_corpus(df[col], df[anonym_col], prefix=plot_prefix)
+    out_str = f'Mean semantic distance before and after the anonymization process: {mean_dist}'
+    logging.info(out_str)  # Logging
+    
+    logging.info('Done')  # Logging
+    return df, mean_dist
+
+
+def parse_args():
+    """
+    Defines the ArgumentParser
+    :return: The parser
+    """
+    parser_func = argparse.ArgumentParser(description='Converts dot tree to newick tree format')
+    parser_func.add_argument('-f', '--file', help='Input CSV file', required=True)
+
+    parser_func.add_argument('-k', help='The k anonymity degree',  required=True)
+    parser_func.add_argument('-s', '--stop', help='Stop word list file. default=data/1000_most_common_words.txt', 
+                             default='data/1000_most_common_words.txt')
+    parser_func.add_argument('--col', help='Text column. Default - txt', default='txt')
+    parser_func.add_argument('--out', help='Output file name. default - based on input file and k')
+    parser_func.add_argument('--llm', action="store_true",
+                             help='Use LLM methods. default: False')
+    parser_func.add_argument('--plot', action="store_true",
+                             help='Plot semantic distance before and after the anonymization. default: False')
+    parser_func.add_argument('--sample', 
+                             help='Take only the first N rows. For debugging.', type=int)
+    parser_func.add_argument('--wemodel', 
+                             help='Word embedding model.', default='fasttext-wiki-news-subwords-300')
+    parser_func.add_argument('--num_stop', 
+                             help='Number of stop words, ordered by frequency. Must be between 0-5000. default 1000', type=int, default='1000')
+    parser_func.add_argument('--n_jobs',
+                             help='The number of parallel jobs to run. -1 means using all processors. default -1', 
+                             type=int, default=1)
+    parser_func.add_argument('--verbose', type=int, default=0,
+                             help='Prevent the program from displaying screen output. default: 0')
+    parser_func.add_argument('-version', action='version', version='%(prog)s:' + ' %s-%s' % (__version__, __date__))
+    return parser_func
+
+
+def run_from_command_line():
+    """
+    Runs the functions from command line
+    """
+    parser = parse_args()
+    args = parser.parse_args()
+
+    # getting the input arguments
+    input_file = args.file  # Input database
+    k = int(args.k)  # Desired k degree
+    col = args.col  # The text columns  
+
+    # df from csv
+    df = pd.read_csv(input_file)
+    if args.sample:
+        df = df.head(args.sample)
+
+    prefix = get_prefix(args) 
+
+    if not args.llm:
+        df, mean_dist = run_anonym(df=df, k=k, col=col, plot=args.plot, num_stop=args.num_stop, wemodel=args.wemodel, n_jobs=args.n_jobs, verbose=args.verbose)
+    else:
+        df, mean_dist = llm_method(df=df, k=k, col=col, plot=args.plot, n_jobs=args.n_jobs, verbose=args.verbose)
+    
+    print('Mean semantic distance:', mean_dist)
+    # Saving
+    if args.out:
+        output_name = args.out
+    else:
+        output_name = f'{prefix}_anonymized.csv'
+    out_file = 'outputs/' + output_name
+    df.to_csv(out_file, index=False)
+    
+
+if __name__ == "__main__":    
+    start_time = time.time()
+    run_from_command_line()
+    print(f'Running time: {round((time.time() - start_time),2)} seconds')
+
```

### Comparing `kanonym4text-0.0.1/kanonym4text/utils/anonym_utils.py` & `kanonym4text-0.0.2/kanonym4text/utils/anonym_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text/utils/cluster_utils.py` & `kanonym4text-0.0.2/kanonym4text/utils/cluster_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text/utils/llm_utils.py` & `kanonym4text-0.0.2/kanonym4text/utils/llm_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text/utils/models.py` & `kanonym4text-0.0.2/kanonym4text/utils/models.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text/utils/nlp_utils.py` & `kanonym4text-0.0.2/kanonym4text/utils/nlp_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text/utils/utilization_utils.py` & `kanonym4text-0.0.2/kanonym4text/utils/utilization_utils.py`

 * *Files identical despite different names*

### Comparing `kanonym4text-0.0.1/kanonym4text.egg-info/PKG-INFO` & `kanonym4text-0.0.2/kanonym4text.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kanonym4text
-Version: 0.0.1
+Version: 0.0.2
 Summary: k-anonymity for texts
 Home-page: UNKNOWN
 Author: Lior Trieman, Hadas Neuman
 Author-email: liortr30@gmail.com, hadas.doron@gmail.com
 License: UNKNOWN
 Description: A package that applies k-anonymity on extual documents.
 Keywords: python,k-anonymity,privacy,NLP
```

### Comparing `kanonym4text-0.0.1/setup.py` & `kanonym4text-0.0.2/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 from setuptools import setup, find_packages
 
-VERSION = '0.0.1'
+VERSION = '0.0.2'
 DESCRIPTION = 'k-anonymity for texts'
 LONG_DESCRIPTION = 'A package that applies k-anonymity on extual documents.'
 
 # Setting up
 setup(
     name="kanonym4text",
     version=VERSION,
     author="Lior Trieman, Hadas Neuman",
     author_email="liortr30@gmail.com, hadas.doron@gmail.com",
     description=DESCRIPTION,
     long_description_content_type="text/markdown",
     long_description=LONG_DESCRIPTION,
     packages=find_packages(),
     install_requires=[
-        'numpy==1.22.4',
+        'numpy==1.23.0',
         'pandas==1.5.3',
         'matplotlib==3.7.1',
         'gensim==4.3.1',
         'torch==2.0.1',
         'transformers==4.29.0',
         'sentence-transformers==2.2.2',
         'spacy==3.5.3',
```


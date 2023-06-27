# Comparing `tmp/hypernetx-2.0.0.post1.tar.gz` & `tmp/hypernetx-2.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hypernetx-2.0.0.post1.tar", last modified: Mon May 15 22:35:07 2023, max compression
+gzip compressed data, was "hypernetx-2.0.1.tar", last modified: Tue Jun 27 23:47:28 2023, max compression
```

## Comparing `hypernetx-2.0.0.post1.tar` & `hypernetx-2.0.1.tar`

### file list

```diff
@@ -1,51 +1,51 @@
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.791526 hypernetx-2.0.0.post1/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1794 2023-05-11 23:29:15.000000 hypernetx-2.0.0.post1/LICENSE.rst
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3239 2023-05-15 21:24:48.000000 hypernetx-2.0.0.post1/LONG_DESCRIPTION.rst
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3834 2023-05-15 22:35:07.791687 hypernetx-2.0.0.post1/PKG-INFO
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    13828 2023-05-15 21:24:48.000000 hypernetx-2.0.0.post1/README.md
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.601817 hypernetx-2.0.0.post1/hypernetx/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      400 2023-05-15 22:34:16.000000 hypernetx-2.0.0.post1/hypernetx/__init__.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.662372 hypernetx-2.0.0.post1/hypernetx/algorithms/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2596 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/__init__.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    39961 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/contagion.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     8678 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/generative_models.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    24275 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/homology_mod2.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    15464 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/hypergraph_modularity.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     7820 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/laplacians_clustering.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     9966 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/algorithms/s_centrality_measures.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.703416 hypernetx-2.0.0.post1/hypernetx/classes/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      195 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/classes/__init__.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    55664 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/classes/entity.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    27383 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/classes/entityset.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     8557 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/classes/helpers.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    82331 2023-05-15 21:15:27.000000 hypernetx-2.0.0.post1/hypernetx/classes/hypergraph.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.738198 hypernetx-2.0.0.post1/hypernetx/drawing/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      151 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/drawing/__init__.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    15120 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/drawing/rubber_band.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     5596 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/drawing/two_column.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3398 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/drawing/util.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      640 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/exception.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      379 2022-07-07 16:12:57.000000 hypernetx-2.0.0.post1/hypernetx/read_write.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.745789 hypernetx-2.0.0.post1/hypernetx/reports/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      491 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/reports/__init__.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    11362 2023-05-15 21:22:51.000000 hypernetx-2.0.0.post1/hypernetx/reports/descriptive_stats.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.762330 hypernetx-2.0.0.post1/hypernetx/utils/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      760 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/utils/__init__.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2428 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/utils/decorators.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     5960 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/utils/extras.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1423 2023-05-11 23:29:16.000000 hypernetx-2.0.0.post1/hypernetx/utils/log.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.790842 hypernetx-2.0.0.post1/hypernetx/utils/toys/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      409 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/utils/toys/__init__.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      353 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/utils/toys/gene_data.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2844 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/utils/toys/harrypotter.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    14357 2023-05-15 21:06:49.000000 hypernetx-2.0.0.post1/hypernetx/utils/toys/lesmis.py
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      552 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/hypernetx/utils/toys/transmission_problem.py
-drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-05-15 22:35:07.614553 hypernetx-2.0.0.post1/hypernetx.egg-info/
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3834 2023-05-15 22:35:07.000000 hypernetx-2.0.0.post1/hypernetx.egg-info/PKG-INFO
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1220 2023-05-15 22:35:07.000000 hypernetx-2.0.0.post1/hypernetx.egg-info/SOURCES.txt
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)        1 2023-05-15 22:35:07.000000 hypernetx-2.0.0.post1/hypernetx.egg-info/dependency_links.txt
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1067 2023-05-15 22:35:07.000000 hypernetx-2.0.0.post1/hypernetx.egg-info/requires.txt
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)       10 2023-05-15 22:35:07.000000 hypernetx-2.0.0.post1/hypernetx.egg-info/top_level.txt
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)       97 2023-05-11 23:28:49.000000 hypernetx-2.0.0.post1/pyproject.toml
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2369 2023-05-15 22:35:07.792907 hypernetx-2.0.0.post1/setup.cfg
--rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)       86 2023-05-15 22:34:16.000000 hypernetx-2.0.0.post1/setup.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.287028 hypernetx-2.0.1/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1794 2023-05-15 23:30:43.000000 hypernetx-2.0.1/LICENSE.rst
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3239 2023-05-15 23:30:43.000000 hypernetx-2.0.1/LONG_DESCRIPTION.rst
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3828 2023-06-27 23:47:28.287215 hypernetx-2.0.1/PKG-INFO
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    13839 2023-06-23 18:39:50.000000 hypernetx-2.0.1/README.md
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:27.928032 hypernetx-2.0.1/hypernetx/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      394 2023-06-23 18:39:50.000000 hypernetx-2.0.1/hypernetx/__init__.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.028367 hypernetx-2.0.1/hypernetx/algorithms/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2596 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/algorithms/__init__.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    40009 2023-06-23 18:39:50.000000 hypernetx-2.0.1/hypernetx/algorithms/contagion.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     8678 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/algorithms/generative_models.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    24275 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/algorithms/homology_mod2.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    15474 2023-06-23 18:39:50.000000 hypernetx-2.0.1/hypernetx/algorithms/hypergraph_modularity.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     7820 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/algorithms/laplacians_clustering.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     9966 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/algorithms/s_centrality_measures.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.110655 hypernetx-2.0.1/hypernetx/classes/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      195 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/classes/__init__.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    55664 2023-06-27 21:38:45.000000 hypernetx-2.0.1/hypernetx/classes/entity.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    27383 2023-06-27 21:38:45.000000 hypernetx-2.0.1/hypernetx/classes/entityset.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     8557 2023-06-09 21:15:31.000000 hypernetx-2.0.1/hypernetx/classes/helpers.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    82331 2023-06-27 21:38:45.000000 hypernetx-2.0.1/hypernetx/classes/hypergraph.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.157967 hypernetx-2.0.1/hypernetx/drawing/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      151 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/drawing/__init__.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    15120 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/drawing/rubber_band.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     5596 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/drawing/two_column.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3398 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/drawing/util.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      640 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/exception.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      379 2022-07-07 16:12:57.000000 hypernetx-2.0.1/hypernetx/read_write.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.170890 hypernetx-2.0.1/hypernetx/reports/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      491 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/reports/__init__.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    11362 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/reports/descriptive_stats.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.236371 hypernetx-2.0.1/hypernetx/utils/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      760 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/utils/__init__.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2428 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/utils/decorators.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     5960 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/utils/extras.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1423 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/utils/log.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:28.286315 hypernetx-2.0.1/hypernetx/utils/toys/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      409 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/utils/toys/__init__.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      353 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/utils/toys/gene_data.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2844 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/utils/toys/harrypotter.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)    14357 2023-05-15 23:30:43.000000 hypernetx-2.0.1/hypernetx/utils/toys/lesmis.py
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)      552 2023-05-11 23:28:49.000000 hypernetx-2.0.1/hypernetx/utils/toys/transmission_problem.py
+drwxr-xr-x   0 boni407  (1550152542) PNL\Domain Users (2016721313)        0 2023-06-27 23:47:27.959199 hypernetx-2.0.1/hypernetx.egg-info/
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     3828 2023-06-27 23:47:27.000000 hypernetx-2.0.1/hypernetx.egg-info/PKG-INFO
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1220 2023-06-27 23:47:27.000000 hypernetx-2.0.1/hypernetx.egg-info/SOURCES.txt
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)        1 2023-06-27 23:47:27.000000 hypernetx-2.0.1/hypernetx.egg-info/dependency_links.txt
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     1062 2023-06-27 23:47:27.000000 hypernetx-2.0.1/hypernetx.egg-info/requires.txt
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)       10 2023-06-27 23:47:27.000000 hypernetx-2.0.1/hypernetx.egg-info/top_level.txt
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)       97 2023-05-11 23:28:49.000000 hypernetx-2.0.1/pyproject.toml
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)     2364 2023-06-27 23:47:28.308361 hypernetx-2.0.1/setup.cfg
+-rw-r--r--   0 boni407  (1550152542) PNL\Domain Users (2016721313)       80 2023-06-23 18:39:50.000000 hypernetx-2.0.1/setup.py
```

### Comparing `hypernetx-2.0.0.post1/LICENSE.rst` & `hypernetx-2.0.1/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/LONG_DESCRIPTION.rst` & `hypernetx-2.0.1/LONG_DESCRIPTION.rst`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/PKG-INFO` & `hypernetx-2.0.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hypernetx
-Version: 2.0.0.post1
+Version: 2.0.1
 Summary: HyperNetX is a Python library for the creation and study of hypergraphs.
 Home-page: https://github.com/pnnl/HyperNetX
 Author: Brenda Praggastis, Dustin Arendt, Sinan Aksoy, Emilie Purvine, Cliff Joslyn
 Author-email: hypernetx@pnnl.gov
 License: 3-Clause BSD license
 Description-Content-Type: text/x-rst
 Provides-Extra: releases
```

### Comparing `hypernetx-2.0.0.post1/README.md` & `hypernetx-2.0.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -61,55 +61,62 @@
 1. The `static` and `dynamic` distinctions no longer exist. All hypergraphs use the same underlying data structure, supported by Pandas dataFrames. All hypergraphs maintain a `state_dict` to avoid repeating computations.
 1. Methods for adding nodes and hyperedges are currently not supported.
 1. The `nwhy` optimizations are no longer supported.
 1. Entity and EntitySet classes are being moved to the background. The Hypergraph constructor does not accept either.
 
 
 
-Tutorials may be run in your browser using Google Colab
--------------------------------------------------------
+Tutorials
+=========
+
+Google Colab
+------------
 
-**Additional Tutorials may be found on in the Tutorials Folder.**
 
 <a href="https://colab.research.google.com/github/pnnl/HyperNetX/blob/master/tutorials/Tutorial%201%20-%20HNX%20Basics.ipynb" target="_blank">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
     <span >Tutorial 1 - HNX Basics</span>
 </a>
-</br>
+<br>
 
 <a href="https://colab.research.google.com/github/pnnl/HyperNetX/blob/master/tutorials/Tutorial%202%20-%20Visualization%20Methods.ipynb" target="_blank">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
     <span >Tutorial 2 - Visualization Methods</span>
 </a>
-</br>
+<br>
 
 <a href="https://colab.research.google.com/github/pnnl/HyperNetX/blob/master/tutorials/Tutorial%203%20-%20LesMis%20Case%20Study.ipynb" target="_blank">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
     <span >Tutorial 3 - LesMis Case Study</span>
 </a>
-</br>
+<br>
 
 <a href="https://colab.research.google.com/github/pnnl/HyperNetX/blob/master/tutorials/Tutorial%204%20-%20LesMis%20Visualizations-BookTour.ipynb" target="_blank">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
     <span >Tutorial 4 - LesMis Visualizations-Book Tour</span>
 </a>
-</br>
+<br>
 
 <a href="https://colab.research.google.com/github/pnnl/HyperNetX/blob/master/tutorials/Tutorial%205%20-%20s-Centrality.ipynb" target="_blank">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
     <span >Tutorial 5 - s-Centrality</span>
 </a>
-</br>
+<br>
 
 <a href="https://colab.research.google.com/github/pnnl/HyperNetX/blob/master/tutorials/Tutorial%206%20-%20Homology%20mod%202%20for%20TriLoop%20Example.ipynb" target="_blank">
   <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
     <span >Tutorial 6 - Homology mod2 for TriLoop Example</span>
 </a>
-</br>
+<br>
+
+
+Jupyter Notebooks
+-----------------
 
+Additional tutorials that can be run as Jupyter Notebooks can be found in the 'tutorials-jupyter' folder.
 
 Installation
 ====================
 
 The recommended installation method for most users is to create a virtual environment and install HyperNetX from PyPi.
 
 HyperNetX may be cloned or forked from [Github](https://github.com/pnnl/HyperNetX).
@@ -361,15 +368,15 @@
 
 This project uses [`commitizen`](https://github.com/commitizen-tools/commitizen) to manage versioning.
 The files where "version" will be updated are listed in the '.cz.toml' file. To create a new version and the associated tag,
 run the following commands:
 
 ```shell
 # Install commitizen tool to environment
-make releases
+make version-deps
 
 # Updates version; values for '--increment' can be MAJOR, MINOR, or PATCH
 # Autocreates a tag and commit for the updated version
 cz bump  --increment MAJOR  --dry-run
 cz bump  --increment MAJOR
 ```
```

#### html2text {}

```diff
@@ -40,40 +40,42 @@
 onto s-linegraphs as node attributes of Networkx graphs. 1. New hnxwidget
 available using `pip install hnxwidget`. What's Changed -------------- 1. The
 `static` and `dynamic` distinctions no longer exist. All hypergraphs use the
 same underlying data structure, supported by Pandas dataFrames. All hypergraphs
 maintain a `state_dict` to avoid repeating computations. 1. Methods for adding
 nodes and hyperedges are currently not supported. 1. The `nwhy` optimizations
 are no longer supported. 1. Entity and EntitySet classes are being moved to the
-background. The Hypergraph constructor does not accept either. Tutorials may be
-run in your browser using Google Colab ----------------------------------------
---------------- **Additional Tutorials may be found on in the Tutorials
-Folder.** [Open_In_Colab]_Tutorial_1_-_HNX_Basics  [Open_In_Colab]_Tutorial_2_-
-Visualization_Methods  [Open_In_Colab]_Tutorial_3_-_LesMis_Case_Study  [Open_In
-Colab]_Tutorial_4_-_LesMis_Visualizations-Book_Tour  [Open_In_Colab]_Tutorial_5
--_s-Centrality  [Open_In_Colab]_Tutorial_6_-_Homology_mod2_for_TriLoop_Example
-Installation ==================== The recommended installation method for most
-users is to create a virtual environment and install HyperNetX from PyPi.
-HyperNetX may be cloned or forked from [Github](https://github.com/pnnl/
-HyperNetX). Prerequisites ------------- HyperNetX officially supports Python
-3.8, 3.9, 3.10 and 3.11. Create a virtual environment -------------------------
---- ### Using venv ```shell python -m venv venv-hnx source venv-hnx/bin/
-activate ``` ### Using Anaconda ```shell conda create -n venv-hnx python=3.11 -
-y conda activate venv-hnx ``` ### Using virtualenv ```shell virtualenv env-hnx
-source env-hnx/bin/activate ``` ### For Windows Users On both Windows
-PowerShell or Command Prompt, you can use the following command to activate
-your virtual environment: ```shell .\env-hnx\Scripts\activate ``` To deactivate
-your environment, use: ```shell .\env-hnx\Scripts\deactivate ``` Installing
-HyperNetX ==================== Regardless of how you install HyperNetX, ensure
-that your environment is activated and that you are running Python >=3.8.
-Installing from PyPi -------------------- ```shell pip install hypernetx ```
-Installing from Source ---------------------- Ensure that you have [git](https:
-//git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed. ```shell
-git clone https://github.com/pnnl/HyperNetX.git cd HyperNetX pip install . ```
-Post-Installation Actions ========================= Running Tests ------------
+background. The Hypergraph constructor does not accept either. Tutorials
+========= Google Colab ------------ [Open_In_Colab]_Tutorial_1_-_HNX_Basics
+[Open_In_Colab]_Tutorial_2_-_Visualization_Methods
+[Open_In_Colab]_Tutorial_3_-_LesMis_Case_Study
+[Open_In_Colab]_Tutorial_4_-_LesMis_Visualizations-Book_Tour
+[Open_In_Colab]_Tutorial_5_-_s-Centrality
+[Open_In_Colab]_Tutorial_6_-_Homology_mod2_for_TriLoop_Example
+Jupyter Notebooks ----------------- Additional tutorials that can be run as
+Jupyter Notebooks can be found in the 'tutorials-jupyter' folder. Installation
+==================== The recommended installation method for most users is to
+create a virtual environment and install HyperNetX from PyPi. HyperNetX may be
+cloned or forked from [Github](https://github.com/pnnl/HyperNetX).
+Prerequisites ------------- HyperNetX officially supports Python 3.8, 3.9, 3.10
+and 3.11. Create a virtual environment ---------------------------- ### Using
+venv ```shell python -m venv venv-hnx source venv-hnx/bin/activate ``` ###
+Using Anaconda ```shell conda create -n venv-hnx python=3.11 -y conda activate
+venv-hnx ``` ### Using virtualenv ```shell virtualenv env-hnx source env-hnx/
+bin/activate ``` ### For Windows Users On both Windows PowerShell or Command
+Prompt, you can use the following command to activate your virtual environment:
+```shell .\env-hnx\Scripts\activate ``` To deactivate your environment, use:
+```shell .\env-hnx\Scripts\deactivate ``` Installing HyperNetX
+==================== Regardless of how you install HyperNetX, ensure that your
+environment is activated and that you are running Python >=3.8. Installing from
+PyPi -------------------- ```shell pip install hypernetx ``` Installing from
+Source ---------------------- Ensure that you have [git](https://git-scm.com/
+book/en/v2/Getting-Started-Installing-Git) installed. ```shell git clone https:
+//github.com/pnnl/HyperNetX.git cd HyperNetX pip install . ``` Post-
+Installation Actions ========================= Running Tests ------------
 - ```shell python -m pytest ``` Development =========== Install an editable
 version --------------------------- ``` pip install -e . ``` Install an
 editable version with access to jupyter notebooks -----------------------------
 ------------------------------- ```shell pip install -e .'[all]' ``` Install
 support for testing ----------------------------- > â¹ï¸ **NOTE:** This
 project has a pytest configuration file named 'pytest.ini'. By default, pytest
 will use those configuration settings to run tests. ```shell pip install .'
@@ -130,15 +132,15 @@
 ```commandline # login to Github gh auth login --with-token < ~/.ssh/tokens/ #
 Trigger CI gh workflow run ci.yml --repo pnnl/HyperNetX --ref  --field
 triggeredBy="" # Get the status of the workflow gh run list --workflow=ci.yml -
 -repo pnnl/HyperNetX ``` Versioning ---------- This project uses [`commitizen`]
 (https://github.com/commitizen-tools/commitizen) to manage versioning. The
 files where "version" will be updated are listed in the '.cz.toml' file. To
 create a new version and the associated tag, run the following commands:
-```shell # Install commitizen tool to environment make releases # Updates
+```shell # Install commitizen tool to environment make version-deps # Updates
 version; values for '--increment' can be MAJOR, MINOR, or PATCH # Autocreates a
 tag and commit for the updated version cz bump --increment MAJOR --dry-run cz
 bump --increment MAJOR ``` Notice ====== This material was prepared as an
 account of work sponsored by an agency of the United States Government. Neither
 the United States Government nor the United States Department of Energy, nor
 Battelle, nor any of their employees, nor any jurisdiction or organization that
 has cooperated in the development of these materials, makes any warranty,
```

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/__init__.py` & `hypernetx-2.0.1/hypernetx/algorithms/__init__.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/contagion.py` & `hypernetx-2.0.1/hypernetx/algorithms/contagion.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,20 +1,13 @@
 import random
 import numpy as np
 from collections import defaultdict
 from collections import Counter
 import hypernetx as hnx
 
-try:
-    from celluloid import Camera
-except Exception as e:
-    print(
-        f" {e}. If you need to use {__name__}, please install additional packages by running the following command: pip install .['all']"
-    )
-
 
 def contagion_animation(
     fig,
     H,
     transition_events,
     node_state_color_dict,
     edge_state_color_dict,
@@ -68,14 +61,22 @@
         >>> edge_state_color_dict = {"S":(0, 1, 0, 0.3), "I":(1, 0, 0, 0.3), "R":(0, 0, 1, 0.3), "OFF": (1, 1, 1, 0)}
         >>> fps = 1
         >>> fig = plt.figure()
         >>> animation = contagion.contagion_animation(fig, H, transition_events, node_state_color_dict, edge_state_color_dict, node_radius=1, fps=fps)
         >>> HTML(animation.to_jshtml())
     """
 
+    try:
+        from celluloid import Camera
+    except ModuleNotFoundError as e:
+        print(
+            f" {e}. If you need to use {__name__}, please install additional packages by running the following command: pip install .['all']"
+        )
+        raise
+
     nodeState = defaultdict(lambda: "S")
 
     camera = Camera(fig)
 
     for t in sorted(list(transition_events.keys())):
         edgeState = defaultdict(lambda: "OFF")
```

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/generative_models.py` & `hypernetx-2.0.1/hypernetx/algorithms/generative_models.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/homology_mod2.py` & `hypernetx-2.0.1/hypernetx/algorithms/homology_mod2.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/hypergraph_modularity.py` & `hypernetx-2.0.1/hypernetx/algorithms/hypergraph_modularity.py`

 * *Files 1% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 from collections import Counter
 import numpy as np
 import itertools
 from scipy.special import comb
 
 try:
     import igraph as ig
-except Exception as e:
+except ModuleNotFoundError as e:
     print(
         f" {e}. If you need to use {__name__}, please install additional packages by running the following command: pip install .['all']"
     )
 ################################################################################
 
 # we use 2 representations for partitions (0-based part ids):
 # (1) dictionary or (2) list of sets
```

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/laplacians_clustering.py` & `hypernetx-2.0.1/hypernetx/algorithms/laplacians_clustering.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/algorithms/s_centrality_measures.py` & `hypernetx-2.0.1/hypernetx/algorithms/s_centrality_measures.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/classes/entity.py` & `hypernetx-2.0.1/hypernetx/classes/entity.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/classes/entityset.py` & `hypernetx-2.0.1/hypernetx/classes/entityset.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/classes/helpers.py` & `hypernetx-2.0.1/hypernetx/classes/helpers.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/classes/hypergraph.py` & `hypernetx-2.0.1/hypernetx/classes/hypergraph.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/drawing/rubber_band.py` & `hypernetx-2.0.1/hypernetx/drawing/rubber_band.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/drawing/two_column.py` & `hypernetx-2.0.1/hypernetx/drawing/two_column.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/drawing/util.py` & `hypernetx-2.0.1/hypernetx/drawing/util.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/exception.py` & `hypernetx-2.0.1/hypernetx/exception.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/reports/descriptive_stats.py` & `hypernetx-2.0.1/hypernetx/reports/descriptive_stats.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/__init__.py` & `hypernetx-2.0.1/hypernetx/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/decorators.py` & `hypernetx-2.0.1/hypernetx/utils/decorators.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/extras.py` & `hypernetx-2.0.1/hypernetx/utils/extras.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/log.py` & `hypernetx-2.0.1/hypernetx/utils/log.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/toys/harrypotter.py` & `hypernetx-2.0.1/hypernetx/utils/toys/harrypotter.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/toys/lesmis.py` & `hypernetx-2.0.1/hypernetx/utils/toys/lesmis.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx/utils/toys/transmission_problem.py` & `hypernetx-2.0.1/hypernetx/utils/toys/transmission_problem.py`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx.egg-info/PKG-INFO` & `hypernetx-2.0.1/hypernetx.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hypernetx
-Version: 2.0.0.post1
+Version: 2.0.1
 Summary: HyperNetX is a Python library for the creation and study of hypergraphs.
 Home-page: https://github.com/pnnl/HyperNetX
 Author: Brenda Praggastis, Dustin Arendt, Sinan Aksoy, Emilie Purvine, Cliff Joslyn
 Author-email: hypernetx@pnnl.gov
 License: 3-Clause BSD license
 Description-Content-Type: text/x-rst
 Provides-Extra: releases
```

### Comparing `hypernetx-2.0.0.post1/hypernetx.egg-info/SOURCES.txt` & `hypernetx-2.0.1/hypernetx.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `hypernetx-2.0.0.post1/hypernetx.egg-info/requires.txt` & `hypernetx-2.0.1/hypernetx.egg-info/requires.txt`

 * *Files 2% similar despite different names*

```diff
@@ -17,17 +17,17 @@
 jupyter>=1.0
 python-igraph>=0.10.4
 partition-igraph>=0.0.6
 celluloid>=0.2.0
 igraph>=0.10.4
 
 [documentation]
-sphinx>=6.2.1
+sphinx<7
 nb2plots>=0.6.1
-sphinx-rtd-theme>=1.2.0
+sphinx-rtd-theme>=1.2.1
 sphinx-autobuild>=2021.3.14
 sphinx-copybutton>=0.5.1
 
 [linting]
 pre-commit>=3.2.2
 pylint>=2.17.2
 pylint-exit>=1.2.0
```

### Comparing `hypernetx-2.0.0.post1/setup.cfg` & `hypernetx-2.0.1/setup.cfg`

 * *Files 6% similar despite different names*

```diff
@@ -93,17 +93,17 @@
 	partition-igraph>=0.0.6
 	celluloid>=0.2.0
 widget = 
 	hnxwidget>=0.1.1b3
 	jupyter-contrib-nbextensions>=0.7.0
 	jupyter-nbextensions-configurator>=0.6.2
 documentation = 
-	sphinx>=6.2.1
+	sphinx<7
 	nb2plots>=0.6.1
-	sphinx-rtd-theme>=1.2.0
+	sphinx-rtd-theme>=1.2.1
 	sphinx-autobuild>=2021.3.14
 	sphinx-copybutton>=0.5.1
 packaging = 
 	build>=0.10.0
 	twine>=4.0.2
 	setuptools>=67.6.1
 	tox>=4.4.11
```


# Comparing `tmp/cytocipher-0.1.15.tar.gz` & `tmp/cytocipher-0.1.20.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cytocipher-0.1.15.tar", last modified: Fri Dec  2 04:59:45 2022, max compression
+gzip compressed data, was "cytocipher-0.1.20.tar", last modified: Wed Jun 28 09:12:18 2023, max compression
```

## Comparing `cytocipher-0.1.15.tar` & `cytocipher-0.1.20.tar`

### file list

```diff
@@ -1,43 +1,43 @@
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.391009 cytocipher-0.1.15/
--rw-r--r--   0 uqbbalde (1163551179) 411385356    35149 2022-10-27 06:28:22.000000 cytocipher-0.1.15/LICENSE
--rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:56:30.000000 cytocipher-0.1.15/MANIFEST.in
--rw-r--r--   0 uqbbalde (1163551179) 411385356     3616 2022-12-02 04:59:45.390828 cytocipher-0.1.15/PKG-INFO
--rw-r--r--   0 uqbbalde (1163551179) 411385356     2954 2022-12-02 04:56:30.000000 cytocipher-0.1.15/README.md
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.362808 cytocipher-0.1.15/cytocipher/
--rw-r--r--   0 uqbbalde (1163551179) 411385356      194 2022-12-02 04:59:07.000000 cytocipher-0.1.15/cytocipher/__init__.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356      338 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/ld.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356      229 2022-12-02 04:56:30.000000 cytocipher-0.1.15/cytocipher/pl.py
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.371098 cytocipher-0.1.15/cytocipher/plotting/
--rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:56:30.000000 cytocipher-0.1.15/cytocipher/plotting/__init__.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     2387 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/act_helpers.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     2898 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/act_plots.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     4386 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/bfs_plots.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     3889 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/cd_helpers.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356    35386 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/cluster_diagnostics.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     9123 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/general_plots.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     9397 2022-10-27 06:28:25.000000 cytocipher-0.1.15/cytocipher/plotting/sankey.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     1918 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/plotting/utils.py
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.380446 cytocipher-0.1.15/cytocipher/score_and_merge/
--rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-12-02 01:16:59.000000 cytocipher-0.1.15/cytocipher/score_and_merge/__init__.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     2892 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/score_and_merge/_group_methods.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     5489 2022-12-02 04:56:30.000000 cytocipher-0.1.15/cytocipher/score_and_merge/_neighbors.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356    23529 2022-12-02 04:56:30.000000 cytocipher-0.1.15/cytocipher/score_and_merge/cluster_merge.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356    34941 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/score_and_merge/cluster_score.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     5215 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/score_and_merge/group_optimisation.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356      265 2022-12-02 04:56:30.000000 cytocipher-0.1.15/cytocipher/tl.py
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.381081 cytocipher-0.1.15/cytocipher/utils/
--rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/utils/__init__.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356     3474 2022-12-02 04:56:30.000000 cytocipher-0.1.15/cytocipher/utils/general.py
--rw-r--r--   0 uqbbalde (1163551179) 411385356      503 2022-10-27 06:28:22.000000 cytocipher-0.1.15/cytocipher/utils/r_helpers.py
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.363900 cytocipher-0.1.15/cytocipher.egg-info/
--rw-r--r--   0 uqbbalde (1163551179) 411385356     3616 2022-12-02 04:59:45.000000 cytocipher-0.1.15/cytocipher.egg-info/PKG-INFO
--rw-r--r--   0 uqbbalde (1163551179) 411385356     1019 2022-12-02 04:59:45.000000 cytocipher-0.1.15/cytocipher.egg-info/SOURCES.txt
--rw-r--r--   0 uqbbalde (1163551179) 411385356        1 2022-12-02 04:59:45.000000 cytocipher-0.1.15/cytocipher.egg-info/dependency_links.txt
--rw-r--r--   0 uqbbalde (1163551179) 411385356       62 2022-12-02 04:59:45.000000 cytocipher-0.1.15/cytocipher.egg-info/requires.txt
--rw-r--r--   0 uqbbalde (1163551179) 411385356       11 2022-12-02 04:59:45.000000 cytocipher-0.1.15/cytocipher.egg-info/top_level.txt
-drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:59:45.390095 cytocipher-0.1.15/img/
--rw-r--r--   0 uqbbalde (1163551179) 411385356   680843 2022-10-27 06:28:22.000000 cytocipher-0.1.15/img/cytocipher_icon.png
--rw-r--r--   0 uqbbalde (1163551179) 411385356    39116 2022-10-27 06:28:22.000000 cytocipher-0.1.15/img/enrichscore_violin_example.png
--rw-r--r--   0 uqbbalde (1163551179) 411385356    21640 2022-10-27 06:28:22.000000 cytocipher-0.1.15/img/example_heatmap.png
--rw-r--r--   0 uqbbalde (1163551179) 411385356       38 2022-12-02 04:59:45.391076 cytocipher-0.1.15/setup.cfg
--rw-r--r--   0 uqbbalde (1163551179) 411385356     1128 2022-12-02 04:59:07.000000 cytocipher-0.1.15/setup.py
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.590911 cytocipher-0.1.20/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356    35149 2022-10-27 06:28:22.000000 cytocipher-0.1.20/LICENSE
+-rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:56:30.000000 cytocipher-0.1.20/MANIFEST.in
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     3616 2023-06-28 09:12:18.590783 cytocipher-0.1.20/PKG-INFO
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     2954 2022-12-02 04:56:30.000000 cytocipher-0.1.20/README.md
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.578801 cytocipher-0.1.20/cytocipher/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356      197 2023-06-28 09:12:07.000000 cytocipher-0.1.20/cytocipher/__init__.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356      338 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/ld.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356      229 2022-12-02 04:56:30.000000 cytocipher-0.1.20/cytocipher/pl.py
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.581739 cytocipher-0.1.20/cytocipher/plotting/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-12-02 04:56:30.000000 cytocipher-0.1.20/cytocipher/plotting/__init__.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     2387 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/act_helpers.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     2898 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/act_plots.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     4386 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/bfs_plots.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     3889 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/cd_helpers.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356    35386 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/cluster_diagnostics.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     9123 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/general_plots.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     9397 2022-10-27 06:28:25.000000 cytocipher-0.1.20/cytocipher/plotting/sankey.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     1918 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/plotting/utils.py
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.582881 cytocipher-0.1.20/cytocipher/score_and_merge/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-12-02 01:16:59.000000 cytocipher-0.1.20/cytocipher/score_and_merge/__init__.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     2892 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/score_and_merge/_group_methods.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     7412 2023-06-28 09:12:07.000000 cytocipher-0.1.20/cytocipher/score_and_merge/_neighbors.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356    25966 2023-06-28 09:12:07.000000 cytocipher-0.1.20/cytocipher/score_and_merge/cluster_merge.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356    38882 2023-06-28 09:12:07.000000 cytocipher-0.1.20/cytocipher/score_and_merge/cluster_score.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     5215 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/score_and_merge/group_optimisation.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356      265 2022-12-02 04:56:30.000000 cytocipher-0.1.20/cytocipher/tl.py
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.583344 cytocipher-0.1.20/cytocipher/utils/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356        0 2022-10-27 06:28:22.000000 cytocipher-0.1.20/cytocipher/utils/__init__.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     3474 2022-12-02 04:56:30.000000 cytocipher-0.1.20/cytocipher/utils/general.py
+-rw-r--r--   0 uqbbalde (1163551179) 411385356      502 2023-06-28 09:12:07.000000 cytocipher-0.1.20/cytocipher/utils/r_helpers.py
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.579650 cytocipher-0.1.20/cytocipher.egg-info/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     3616 2023-06-28 09:12:18.000000 cytocipher-0.1.20/cytocipher.egg-info/PKG-INFO
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     1019 2023-06-28 09:12:18.000000 cytocipher-0.1.20/cytocipher.egg-info/SOURCES.txt
+-rw-r--r--   0 uqbbalde (1163551179) 411385356        1 2023-06-28 09:12:18.000000 cytocipher-0.1.20/cytocipher.egg-info/dependency_links.txt
+-rw-r--r--   0 uqbbalde (1163551179) 411385356       62 2023-06-28 09:12:18.000000 cytocipher-0.1.20/cytocipher.egg-info/requires.txt
+-rw-r--r--   0 uqbbalde (1163551179) 411385356       11 2023-06-28 09:12:18.000000 cytocipher-0.1.20/cytocipher.egg-info/top_level.txt
+drwxr-xr-x   0 uqbbalde (1163551179) 411385356        0 2023-06-28 09:12:18.590364 cytocipher-0.1.20/img/
+-rw-r--r--   0 uqbbalde (1163551179) 411385356   680843 2022-10-27 06:28:22.000000 cytocipher-0.1.20/img/cytocipher_icon.png
+-rw-r--r--   0 uqbbalde (1163551179) 411385356    39116 2022-10-27 06:28:22.000000 cytocipher-0.1.20/img/enrichscore_violin_example.png
+-rw-r--r--   0 uqbbalde (1163551179) 411385356    21640 2022-10-27 06:28:22.000000 cytocipher-0.1.20/img/example_heatmap.png
+-rw-r--r--   0 uqbbalde (1163551179) 411385356       38 2023-06-28 09:12:18.590949 cytocipher-0.1.20/setup.cfg
+-rw-r--r--   0 uqbbalde (1163551179) 411385356     1128 2023-06-28 09:12:07.000000 cytocipher-0.1.20/setup.py
```

### Comparing `cytocipher-0.1.15/LICENSE` & `cytocipher-0.1.20/LICENSE`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/PKG-INFO` & `cytocipher-0.1.20/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cytocipher
-Version: 0.1.15
+Version: 0.1.20
 Summary: Cluster significance analysis in scRNA-seq
 Home-page: https://github.com/BradBalderson/Cytocipher
 Author: Brad Balderson
 Author-email: brad.balderson@uqconnect.edu.au
 License: GNU GENERAL PUBLIC LICENSE V3
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Science/Research
```

### Comparing `cytocipher-0.1.15/README.md` & `cytocipher-0.1.20/README.md`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/act_helpers.py` & `cytocipher-0.1.20/cytocipher/plotting/act_helpers.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/act_plots.py` & `cytocipher-0.1.20/cytocipher/plotting/act_plots.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/bfs_plots.py` & `cytocipher-0.1.20/cytocipher/plotting/bfs_plots.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/cd_helpers.py` & `cytocipher-0.1.20/cytocipher/plotting/cd_helpers.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/cluster_diagnostics.py` & `cytocipher-0.1.20/cytocipher/plotting/cluster_diagnostics.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/general_plots.py` & `cytocipher-0.1.20/cytocipher/plotting/general_plots.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/sankey.py` & `cytocipher-0.1.20/cytocipher/plotting/sankey.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/plotting/utils.py` & `cytocipher-0.1.20/cytocipher/plotting/utils.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/score_and_merge/_group_methods.py` & `cytocipher-0.1.20/cytocipher/score_and_merge/_group_methods.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/score_and_merge/cluster_merge.py` & `cytocipher-0.1.20/cytocipher/score_and_merge/cluster_merge.py`

 * *Files 4% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 from scipy.stats import ttest_ind
 from statsmodels.stats.multitest import multipletests
 
 from sklearn.cluster import KMeans
 
 from collections import defaultdict
 from numba.typed import List
+from numba import jit
 
 from .cluster_score import giotto_page_enrich, code_enrich, coexpr_enrich, \
                                                                      get_markers
 from ._group_methods import group_scores
 from ._neighbors import enrich_neighbours, all_neighbours, general_neighbours
 from ..utils.general import summarise_data_fast
 
@@ -27,15 +28,15 @@
     [label_indices.append(np.where(labels == label)[0]) for label in label_set]
     if type(expr) == pd.DataFrame:
         expr = expr.values
     avg_data = summarise_data_fast(expr, label_indices)
 
     return avg_data
 
-def get_merge_groups(label_pairs: list):
+def get_merge_groups_SLOW(label_pairs: list):
     """Examines the pairs to be merged, and groups them into large groups of
         of clusters to be merged. This implementation will merge cluster pairs
         if there exists a mutual cluster they are both non-significantly
         different from. Can be mediated by filtering the pairs based on the
         overlap of clusters they are both non-significantly different from
         (which is performed in a separate function).
     """
@@ -78,14 +79,67 @@
         group_str = '_'.join(group)
         if group_str not in merge_groups_str:
             merge_groups.append( group )
             merge_groups_str.append( group_str )
 
     return merge_groups
 
+@jit(parallel=False, forceobj=True, nopython=False)
+def get_merge_groups(label_pairs: list):
+    """Examines the pairs to be merged, and groups them into large groups of
+        of clusters to be merged. This implementation will merge cluster pairs
+        if there exists a mutual cluster they are both non-significantly
+        different from. Can be mediated by filtering the pairs based on the
+        overlap of clusters they are both non-significantly different from
+        (which is performed in a separate function).
+    """
+    #### Using a syncing strategy with a dictionary.
+    clust_groups = defaultdict(set)
+    #all_match_bool = [False] * len(label_pairs)
+    for pairi, pair in enumerate(label_pairs):
+        # NOTE we only need to do it for one clust of pair,
+        # since below syncs for other clust
+        clust_groups[pair[0]] = clust_groups[pair[0]].union(pair)
+
+        # Pull in the clusts from each other clust.
+        for clust in clust_groups[pair[0]]:  # Syncing across clusters.
+            clust_groups[pair[0]] = clust_groups[pair[0]].union(
+                                                           clust_groups[clust] )
+
+        # Update each other clust with this clusters clusts to merge
+        for clust in clust_groups[pair[0]]:  # Syncing across clusters.
+            clust_groups[clust] = clust_groups[clust].union(
+                                                         clust_groups[pair[0]] )
+
+        # Checking to make sure they now all represent the same thing....
+        # clusts = clust_groups[pair[0]]
+        # match_bool = [False] * len(clusts)
+        # for i, clust in enumerate(clusts):
+        #     match_bool[i] = np.all(
+        #         np.array(clust_groups[clust]) == np.array(clusts))
+        #
+        # all_match_bool[pairi] = np.all(match_bool)
+
+    # Just for testing purposes...
+    #print(np.all(all_match_bool))
+
+    # Getting the merge groups now.
+    merge_groups = [] #np.unique([tuple(group) for group in clust_groups.values()])
+    merge_groups_str = []
+    all_groups = list(clust_groups.values())
+    for group in all_groups:
+        group = list(group)
+        group.sort()
+        group_str = '_'.join(group)
+        if group_str not in merge_groups_str:
+            merge_groups.append( group )
+            merge_groups_str.append( group_str )
+
+    return merge_groups
+
 ##### Merging the clusters....
 def merge_neighbours_v2(cluster_labels: np.array,
                         label_pairs: list):
     """ Merges pairs of clusters specified in label pairs, giving a new set
         of labels per cell with the clusters merged, as well as a dictionary
         mapping the original cluster label to the merged cluster labels.
     """
@@ -289,14 +343,15 @@
         kmeans = KMeans(n_clusters=k, random_state=random_state)
     else:
         kmeans = None
 
     ps_dict = {}
     for i, labeli in enumerate(label_set):
         for j, labelj in enumerate(label_set):
+            ### Only compare mutual neighbours ###
             if labelj in neighbours[i] and labeli in neighbours[j]:
 
                 labeli_labelj_scores = label_scores[j][labels == labeli]
                 labelj_labelj_scores = label_scores[j][labels == labelj]
 
                 ##### Performing the aggregation of scores that correct for
                 ##### bias toward pairs with higher abundance.
```

### Comparing `cytocipher-0.1.15/cytocipher/score_and_merge/cluster_score.py` & `cytocipher-0.1.20/cytocipher/score_and_merge/cluster_score.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,28 +8,51 @@
 from scanpy import AnnData
 
 from scipy.spatial import distance
 from sklearn.preprocessing import minmax_scale
 
 import numba
 from numba.typed import List
-from numba import njit, prange
+from numba import jit, njit, prange
 
+##### COMMON helper methods
 def calc_page_enrich_input(data):
     """ Calculates stats necessary to calculate enrichment score.
     """
     full_expr = data.to_df().values
 
     gene_means = full_expr.mean(axis=0)
-    fcs = np.apply_along_axis(np.subtract, 1, full_expr, gene_means)
-    mean_fcs = np.apply_along_axis(np.mean, 1, fcs)
-    std_fcs = np.apply_along_axis(np.std, 1, fcs)
+    # fcs = np.apply_along_axis(np.subtract, 1, full_expr, gene_means)
+    # mean_fcs = np.apply_along_axis(np.mean, 1, fcs)
+    # std_fcs = np.apply_along_axis(np.std, 1, fcs)
+
+    return calc_page_enrich_FAST( full_expr, gene_means )
+
+@njit(parallel=True)
+def calc_page_enrich_FAST(full_expr: np.ndarray, gene_means: np.array):
+    """ Calculates necessary statistics for Giotto enrichment scoring....
+    """
+
+    # gene_means = np.zeros((full_expr.shape[1]), dtype=np.float64)
+    # for i in range(len(gene_means)):
+    #     gene_means[i] = np.mean( full_expr[:,i] )
+
+    n = full_expr.shape[0]
+    fcs = np.zeros((n, len(gene_means)), dtype=np.float64)
+    mean_fcs = np.zeros((n), dtype=np.float64)
+    std_fcs = np.zeros((n), dtype=np.float64)
+
+    for i in prange(n):
+        fcs[i, :] = np.subtract(full_expr[i, :], gene_means)
+        mean_fcs[i] = np.mean( fcs[i, :] )
+        std_fcs[i] = np.std( fcs[i, :] )
 
     return fcs, mean_fcs, std_fcs
 
+##### METHODs when want to score just one gene set...
 def giotto_page_enrich_min(gene_set, var_names, fcs, mean_fcs, std_fcs):
     """ Calculates enrichment scores with most values pre-calculated.
     """
     gene_indices = [np.where(var_names == gene)[0][0] for gene in gene_set]
     set_fcs = np.apply_along_axis(np.mean, 1, fcs[:, gene_indices])
 
     giotto_scores = ((set_fcs - mean_fcs) * np.sqrt(len(gene_indices)))/std_fcs
@@ -45,19 +68,65 @@
     if type(obs_key)==type(None):
         return giotto_scores
     else:
         data.obs[obs_key] = giotto_scores
         if verbose:
             print(f"Added data.obs['{obs_key}']")
 
+##### METHODs for cluster scoring...
+@njit
+def giotto_page_enrich_min_FAST(gene_indices, fcs, mean_fcs, std_fcs):
+    """ Calculates enrichment scores with most values pre-calculated.
+    """
+    set_fcs = np.zeros((len(mean_fcs)), dtype=np.float64)
+
+    geneset_fcs = fcs[:, gene_indices]
+    for i in range(len(mean_fcs)):
+        set_fcs[i] = np.mean( geneset_fcs[i,:] )
+
+    giotto_scores = ((set_fcs - mean_fcs) * np.sqrt(len(gene_indices)))/std_fcs
+
+    return giotto_scores
+
+### Tried jit but getting errors; njit on the above function reduces run time
+### to 3 sec for 248 clusters anyhow, better off optimising elsewhere...
+#@jit(parallel=True, #forceobj=True,
+#     nopython=False)
+#@jit(parallel=True)
+def giotto_page_percluster(n_cells: int, cluster_genes: dict,
+                           var_names: np.array, fcs: np.array,
+                           mean_fcs: np.array, std_fcs: np.array):
+    """ Runs Giotto PAGE enrichment per cluster!
+    """
+    cell_scores = np.zeros((n_cells, len(cluster_genes)), dtype=np.float64)
+    cluster_names = list(cluster_genes.keys())
+    for i in prange(len(cluster_names)):
+
+        clusteri = cluster_names[i]
+
+        if len(cluster_genes[clusteri])==0:
+            raise Exception(f"No marker genes for a cluster detected. "
+                             f"Rerun with more relaxed marker gene parameters.")
+
+        gene_indices = np.array([np.where(var_names == gene)[0][0]
+                                 for gene in cluster_genes[clusteri]],
+                                dtype=np.int64)
+
+        cluster_scores_ = giotto_page_enrich_min_FAST(gene_indices, fcs,
+                                                     mean_fcs, std_fcs)
+        cell_scores[:, i] = cluster_scores_
+
+    return cell_scores
+
 def giotto_page_enrich(data: AnnData, groupby: str,
                        var_groups: str='highly_variable',
                        logfc_cutoff: float=0, padj_cutoff: float=.05,
                        n_top: int=5, cluster_marker_key: str=None,
                        rerun_de: bool=True, gene_order='logfc',
+                       n_cpus: int=1,
                        verbose: bool=True):
     """ Runs Giotto PAGE enrichment for cluster markers. Imporant to note that
         by default this function will automatically determine marker genes,
         as opposed to coexpr_enrich and code_enrich. To disable this,
         specify a value for cluster_marker_key, after running get_markers()
         with the same 'groupby' as input.
 
@@ -96,14 +165,16 @@
             Print statements during computation (True) or silent run (False).
         Returns
         --------
             data.obsm[f'{groupby}_enrich_scores']
                 Cell by cell type data frame, with the coexpr enrichment scores
                 for the values.
     """
+    numba.set_num_threads( n_cpus )
+
     n_top = data.shape[1] if type(n_top)==type(None) else n_top
 
     #### First performing differential expression...
     if type(cluster_marker_key)==type(None) and \
             f'{groupby}_markers' not in data.uns:
         if type(var_groups)!=type(None) and rerun_de:
             data_sub = data[:,data.var[var_groups]]
@@ -139,60 +210,70 @@
 
     cluster_genes = data.uns[cluster_marker_key]
 
     ###### Getting the enrichment scores...
     # Precalculations..
     fcs, mean_fcs, std_fcs = calc_page_enrich_input(data)
 
-    cell_scores = np.zeros((data.shape[0], len(cluster_genes)))
-    for i, clusteri in enumerate(cluster_genes):
-        if len(cluster_genes[clusteri])==0:
-            raise Exception(f"No marker genes for {clusteri}. "
-                            f"Rerun with more relaxed marker gene parameters.")
-
-        cluster_scores_ = giotto_page_enrich_min(cluster_genes[clusteri],
-                                                    data.var_names, fcs,
-                                                    mean_fcs, std_fcs)
-        cell_scores[:, i] = cluster_scores_
+    # cell_scores = np.zeros((data.shape[0], len(cluster_genes)))
+    # for i, clusteri in enumerate(cluster_genes):
+    #     if len(cluster_genes[clusteri])==0:
+    #         raise Exception(f"No marker genes for {clusteri}. "
+    #                         f"Rerun with more relaxed marker gene parameters.")
+    #
+    #     cluster_scores_ = giotto_page_enrich_min(cluster_genes[clusteri],
+    #                                                 data.var_names, fcs,
+    #                                                 mean_fcs, std_fcs)
+    #     cell_scores[:, i] = cluster_scores_
+    cell_scores = giotto_page_percluster(data.shape[0], cluster_genes,
+                                              data.var_names.values.astype(str),
+                                                         fcs, mean_fcs, std_fcs)
+    # if not np.any( cell_scores ):
+    #     raise Exception(f"No marker genes for a cluster detected. "
+    #                     f"Rerun with more relaxed marker gene parameters.")
 
     ###### Adding to AnnData
     cluster_scores = pd.DataFrame(cell_scores, index=data.obs_names,
                                   columns=list(cluster_genes.keys()))
     data.obsm[f'{groupby}_enrich_scores'] = cluster_scores
 
     if verbose:
         print(f"Added data.obsm['{groupby}_enrich_scores']")
 
 ################################################################################
              # Functions related to Coexpression Score #
 ################################################################################
 @njit
 def coexpr_score(expr: np.ndarray, min_counts: int = 2):
-    """Enriches for the genes in the data"""
+    """Enriches for the genes in the data. Now optimised.
+    """
 
     expr_bool = expr > 0
     coexpr_counts = expr_bool.sum(axis=1)
 
     ### Accounting for case where might have only one marker gene !!
     if expr.shape[1] < min_counts:
         min_counts = expr.shape[1]
 
     ### Must be coexpression of atleast min_count markers!
     nonzero_indices = np.where(coexpr_counts > 0)[0]
     coexpr_indices = np.where(coexpr_counts >= min_counts)[0]
+    expr_nonzero = expr[nonzero_indices, :]
     cell_scores = np.zeros((expr.shape[0]), dtype=np.float64)
+
     for i in coexpr_indices:
-        expr_probs = np.zeros((coexpr_counts[i]))
-        cell_nonzero = np.where(expr_bool[i, :])[0]
-        for j, genej in enumerate(cell_nonzero):
-            expr_probs[j] = len(
-                np.where(expr[nonzero_indices, genej] >= expr[i, genej])[0]) / \
-                            expr.shape[0]
+        cell_expr_bool = expr_bool[i, :]
+        cell_expr = expr[i, :]
+
+        cells_greater_bool = expr_nonzero[:, cell_expr_bool] >= \
+                                                       cell_expr[cell_expr_bool]
+        expr_probs = cells_greater_bool.sum( axis=0 ) / expr.shape[0]
 
-        cell_scores[i] = np.log2(coexpr_counts[i] / np.prod(expr_probs))
+        joint_coexpr_prob = np.prod( expr_probs )
+        cell_scores[i] = np.log2(coexpr_counts[i] / joint_coexpr_prob)
 
     return cell_scores
 
 @njit(parallel=True)
 def get_enrich_scores(full_expr: np.ndarray, all_genes: np.array,
                       cluster_genes_List: List,
                       min_counts: int,
@@ -336,14 +417,38 @@
             neg_cells_bool[coexpr_bool] = 1
 
             start_index = end_index + 1 # Go one position further along.
 
     return neg_cells_bool
 
 @njit
+def code_score_cell(expr: np.ndarray, coexpr_counts_all: np.ndarray,
+                    coexpr_indices: np.ndarray, expr_pos: np.ndarray,
+                    expr_bool_pos: np.ndarray, coexpr_counts_pos: np.ndarray):
+    """ Performs code scoring for each cell in a loop...
+    """
+    ### Need to check all nonzero indices to get expression level frequency.
+    nonzero_indices = np.where(coexpr_counts_all > 0)[0]
+    expr_pos_nonzero = expr_pos[nonzero_indices, :]
+    cell_scores = np.zeros((expr.shape[0]), dtype=np.float64)
+
+    for i in coexpr_indices:
+        cell_expr_pos_bool = expr_bool_pos[i, :]
+        cell_expr_pos = expr_pos[i, :]
+
+        cells_greater_bool = expr_pos_nonzero[:, cell_expr_pos_bool] >= \
+                                               cell_expr_pos[cell_expr_pos_bool]
+        expr_probs = cells_greater_bool.sum( axis=0 ) / expr.shape[0]
+
+        joint_coexpr_prob = np.prod( expr_probs )
+        cell_scores[i] = np.log2(coexpr_counts_pos[i] / joint_coexpr_prob)
+
+    return cell_scores
+
+@njit
 def code_score(expr: np.ndarray, in_index_end: int,
                negative_indices: List, min_counts: int = 2):
     """Enriches for the genes in the data, while controlling for genes that
         shouldn't be in the cells.
     """
     ### Need to check all places of expression to get expression probablility
     expr_bool = expr > 0
@@ -365,28 +470,29 @@
     ### Getting which cells coexpress atleast min_counts of
     ###  positive set but not min_counts of negative set
     coexpr_bool = np.logical_and(coexpr_counts_pos >= min_,
                                  neg_cells_bool==0)
     coexpr_indices = np.where( coexpr_bool )[0]
 
     ### Need to check all nonzero indices to get expression level frequency.
-    nonzero_indices = np.where(coexpr_counts_all > 0)[0]
-    cell_scores = np.zeros((expr.shape[0]), dtype=np.float64)
-    for i in coexpr_indices:
-        expr_probs = np.zeros(( expr_pos.shape[1] ))
-        cell_nonzero = np.where( expr_bool_pos[i, :] )[0]
-        for j, genej in enumerate(cell_nonzero):
-            expr_level_count = len(np.where(expr_pos[nonzero_indices, genej]
-                                                      >= expr_pos[i, genej])[0])
-            expr_probs[j] = expr_level_count / expr.shape[0]
+    cell_scores = code_score_cell(expr, coexpr_counts_all, coexpr_indices,
+                                  expr_pos, expr_bool_pos, coexpr_counts_pos)
+    return cell_scores
 
-        joint_coexpr_prob = np.prod( expr_probs[expr_probs > 0] )
-        cell_scores[i] = np.log2(coexpr_counts_pos[i] / joint_coexpr_prob)
+@njit
+def get_item_indices(items: List, full_items: np.array):
+    """ Gets indices of items in larger array...
+    """
+    item_indices = np.zeros(items.shape, dtype=np.int_)
+    for index, item in enumerate(items):
+        for index2, item2 in enumerate(full_items):
+            if item == item2:
+                item_indices[index] = index2
 
-    return cell_scores
+    return item_indices
 
 @njit(parallel=True)
 def get_code_scores(full_expr: np.ndarray, all_genes: np.array,
                       cluster_genes_List: List,
                       cluster_diff_List: List,
                       cluster_diff_cluster_List: List,
                       min_counts: int,
@@ -397,35 +503,29 @@
     cell_scores = np.zeros((full_expr.shape[0], len(cluster_genes_List)))
     for i in prange( len(cluster_genes_List) ):
         genes_ = cluster_genes_List[i]
         genes_diff = cluster_diff_List[i]
         clusts_diff = cluster_diff_cluster_List[i]
 
         #### Getting genes should be in cluster
-        gene_indices = np.zeros( genes_.shape, dtype=np.int_ )
-        for gene_index, gene in enumerate( genes_ ):
-            for gene_index2, gene2 in enumerate( all_genes ):
-                if gene == gene2:
-                    gene_indices[gene_index] = gene_index2
+        gene_indices = get_item_indices(genes_, all_genes)
 
         #### Getting genes shouldn't be in cluster
-        diff_indices = np.zeros(genes_diff.shape, dtype=np.int_)
-        for gene_index, gene in enumerate( genes_diff ):
-            for gene_index2, gene2 in enumerate(all_genes):
-                if gene == gene2:
-                    diff_indices[gene_index] = gene_index2
+        diff_indices = get_item_indices(genes_diff, all_genes)
 
         #### Getting indices of which genes are in what cluster.
         clusts = np.unique(clusts_diff)
         negative_indices = np.zeros((len(clusts)), dtype=np.int_)
         if len(clusts) > 0:
             for clusti, clust in enumerate(clusts):
                 for clustj in range(len(clusts_diff)):
-                    if clusts_diff[clustj]==clust and \
-                            clusts_diff[clustj+1]!=clust:
+                    ### Added in accounting for the end of the list...
+                    ###### Turns out this only happens if
+                    if (clusts_diff[clustj]==clust and (clustj+1)==len(clusts_diff)) or \
+                       (clusts_diff[clustj]==clust and clusts_diff[clustj+1]!=clust):
                         negative_indices[clusti] = clustj
                         break
 
         #### Now getting the coexpression scores
         all_indices = np.concatenate((gene_indices, diff_indices))
         cluster_scores_ = code_score(full_expr[:, all_indices],
                                      in_index_end=len(gene_indices),
@@ -514,16 +614,17 @@
         ### Getting genes which are different if clusters with similar genes
         cluster_diff_full = []
         cluster_diff_clusters = []
         for clusterj in cluster_genes_dict:
             if cluster!=clusterj:
 
                 ##### Accounting for full overlap!!!!
-                if np.all( np.unique(cluster_genes_dict[clusterj])==\
-                                                     np.unique(cluster_genes) ):
+                #if np.all( np.unique(cluster_genes_dict[clusterj])==\
+                #                                     np.unique(cluster_genes) ):
+                if set(cluster_genes_dict[clusterj])==set(cluster_genes):
                     error = "Full overlap of + and - gene sets detected " + \
                             f"for {cluster} and {clusterj}; suggested to " + \
                             f"increase number of marker genes for scoring."
                     if not squash_exception:
                         raise Exception(error)
                     else:
                         print(error)
```

### Comparing `cytocipher-0.1.15/cytocipher/score_and_merge/group_optimisation.py` & `cytocipher-0.1.20/cytocipher/score_and_merge/group_optimisation.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher/utils/general.py` & `cytocipher-0.1.20/cytocipher/utils/general.py`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/cytocipher.egg-info/PKG-INFO` & `cytocipher-0.1.20/cytocipher.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cytocipher
-Version: 0.1.15
+Version: 0.1.20
 Summary: Cluster significance analysis in scRNA-seq
 Home-page: https://github.com/BradBalderson/Cytocipher
 Author: Brad Balderson
 Author-email: brad.balderson@uqconnect.edu.au
 License: GNU GENERAL PUBLIC LICENSE V3
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Science/Research
```

### Comparing `cytocipher-0.1.15/cytocipher.egg-info/SOURCES.txt` & `cytocipher-0.1.20/cytocipher.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/img/cytocipher_icon.png` & `cytocipher-0.1.20/img/cytocipher_icon.png`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/img/enrichscore_violin_example.png` & `cytocipher-0.1.20/img/enrichscore_violin_example.png`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/img/example_heatmap.png` & `cytocipher-0.1.20/img/example_heatmap.png`

 * *Files identical despite different names*

### Comparing `cytocipher-0.1.15/setup.py` & `cytocipher-0.1.20/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setup(
     name='cytocipher',
-    version='0.1.15',
+    version='0.1.20',
     description='Cluster significance analysis in scRNA-seq',
     url='https://github.com/BradBalderson/Cytocipher',
     author='Brad Balderson',
     author_email='brad.balderson@uqconnect.edu.au',
     license='GNU GENERAL PUBLIC LICENSE V3',
     long_description_content_type="text/markdown",
     long_description=long_description,
```


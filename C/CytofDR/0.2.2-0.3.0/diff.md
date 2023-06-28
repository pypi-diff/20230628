# Comparing `tmp/CytofDR-0.2.2.tar.gz` & `tmp/CytofDR-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "CytofDR-0.2.2.tar", last modified: Wed Jun 28 01:46:59 2023, max compression
+gzip compressed data, was "CytofDR-0.3.0.tar", last modified: Sat Feb 18 20:12:56 2023, max compression
```

## Comparing `CytofDR-0.2.2.tar` & `CytofDR-0.3.0.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2023-06-28 01:46:58.319660 CytofDR-0.2.2/
-drwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2023-06-28 01:46:57.983278 CytofDR-0.2.2/CytofDR/
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)       59 2023-06-27 23:35:02.000000 CytofDR-0.2.2/CytofDR/__init__.py
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2022-06-04 20:05:45.000000 CytofDR-0.2.2/CytofDR/__main__.py
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)    63405 2023-06-27 23:26:05.000000 CytofDR-0.2.2/CytofDR/dr.py
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)    35795 2023-06-27 23:26:05.000000 CytofDR-0.2.2/CytofDR/evaluation.py
-drwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2023-06-28 01:46:58.242020 CytofDR-0.2.2/CytofDR.egg-info/
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)     9271 2023-06-28 01:46:57.000000 CytofDR-0.2.2/CytofDR.egg-info/PKG-INFO
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)      283 2023-06-28 01:46:57.000000 CytofDR-0.2.2/CytofDR.egg-info/SOURCES.txt
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)        1 2023-06-28 01:46:57.000000 CytofDR-0.2.2/CytofDR.egg-info/dependency_links.txt
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)       76 2023-06-28 01:46:57.000000 CytofDR-0.2.2/CytofDR.egg-info/requires.txt
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)        8 2023-06-28 01:46:57.000000 CytofDR-0.2.2/CytofDR.egg-info/top_level.txt
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)     1085 2023-02-18 20:33:40.000000 CytofDR-0.2.2/LICENSE.txt
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)     1712 2022-06-04 20:05:45.000000 CytofDR-0.2.2/LICENSE_associated.txt
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)     9271 2023-06-28 01:46:58.317469 CytofDR-0.2.2/PKG-INFO
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)     8802 2023-06-27 23:33:23.000000 CytofDR-0.2.2/README.md
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)       38 2023-06-28 01:46:58.320797 CytofDR-0.2.2/setup.cfg
--rwxrwxrwx   0 kevin     (1000) kevin     (1000)     2304 2023-06-27 23:33:56.000000 CytofDR-0.2.2/setup.py
+drwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2023-02-18 20:12:56.271742 CytofDR-0.3.0/
+drwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2023-02-18 20:12:55.791594 CytofDR-0.3.0/CytofDR/
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)       59 2023-02-18 20:10:15.000000 CytofDR-0.3.0/CytofDR/__init__.py
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2022-06-04 20:05:45.000000 CytofDR-0.3.0/CytofDR/__main__.py
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)    64757 2023-02-18 20:10:16.000000 CytofDR-0.3.0/CytofDR/dr.py
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)    39069 2023-02-18 20:10:16.000000 CytofDR-0.3.0/CytofDR/evaluation.py
+drwxrwxrwx   0 kevin     (1000) kevin     (1000)        0 2023-02-18 20:12:56.150932 CytofDR-0.3.0/CytofDR.egg-info/
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)     8800 2023-02-18 20:12:54.000000 CytofDR-0.3.0/CytofDR.egg-info/PKG-INFO
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)      283 2023-02-18 20:12:55.000000 CytofDR-0.3.0/CytofDR.egg-info/SOURCES.txt
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)        1 2023-02-18 20:12:54.000000 CytofDR-0.3.0/CytofDR.egg-info/dependency_links.txt
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)       76 2023-02-18 20:12:55.000000 CytofDR-0.3.0/CytofDR.egg-info/requires.txt
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)        8 2023-02-18 20:12:55.000000 CytofDR-0.3.0/CytofDR.egg-info/top_level.txt
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)     1085 2023-02-18 20:01:59.000000 CytofDR-0.3.0/LICENSE.txt
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)     1712 2022-06-04 20:05:45.000000 CytofDR-0.3.0/LICENSE_associated.txt
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)     8800 2023-02-18 20:12:56.268742 CytofDR-0.3.0/PKG-INFO
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)     8331 2023-02-18 20:10:16.000000 CytofDR-0.3.0/README.md
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)       38 2023-02-18 20:12:56.272742 CytofDR-0.3.0/setup.cfg
+-rwxrwxrwx   0 kevin     (1000) kevin     (1000)     2304 2023-02-18 20:10:16.000000 CytofDR-0.3.0/setup.py
```

### Comparing `CytofDR-0.2.2/CytofDR/dr.py` & `CytofDR-0.3.0/CytofDR/dr.py`

 * *Files 1% similar despite different names*

```diff
@@ -201,15 +201,17 @@
                  category: Union[str, List[str]],
                  pwd_metric: str="PCD",
                  k_neighbors: int=5,
                  annoy_original_data_path: Optional[str]=None,
                  auto_cluster: bool=True,
                  n_clusters: int=20,
                  verbose: bool=True,
-                 pairwise_downsample_size: int=10000):     
+                 pairwise_downsample_size: int=10000,
+                 normalize_pwd: Optional[str]=None,
+                 NPE_method: str="L1"):     
         """Evaluate DR Methods Using Default DR Evaluation Scheme.
 
         This method ranks the DR methods based on any of the four default categories:
         ``global``, ``local``, ``downstream``, or ``concordance``. 
         
         :param category: The major evaluation category: ``global``, ``local``, ``downstream``, or ``concordance``.
         :param pwd_metric: The pairwise distance metric. Three options are "PCD", "pairwise_downsample", or "pairwise".
@@ -225,14 +227,19 @@
         :param n_clusters: The number of clusters for the `auto_cluster` option. Defaults to 20.
         :param verbose: Whether to print out progress. Defaults to `True`.
         :param pairwise_downsample_size: The downsample size if the `pairwise_downsample` is chosen for the
             `pwd_metric`. If this is larger than the sample size of the original dataset, this methods falls
             back to the `pairwise` option for `pwd_metric`. On a typical machine, it is not recommended to 
             go beyond the default, and for datasets smaller than 10,000, no downsample is strictly necessary.
             Defaults to 10,000.
+        :param normalize_pwd: Whether to perform minmax normalize on the pwd metric for EMD. If needed, enter
+            "minmax". If ``None``, then the raw distances are used. For more details, see ``EvaluationMetrics.EMD``.
+            This only matters when ``Global`` is chosen in the ``category`` parameter. Defaults to None.
+        :param NPE_method: The distance measure used for the NPE metric as part of the ``Local`` categorty.
+            "L1" for L1-norm or "tvd" for Total Variation Distance. Defaults to "L1". 
         
         :raises ValueError: No reductions to evalate.
         :raises ValueError: Unsupported 'pwd_metric': 'PCD', 'Pairwise', or 'pairwise_downsample' only.
         :raises ValueError: Evaluation needs 'original_data', 'original_labels', and 'embedding_labels' attributes.
         
         .. note::
         
@@ -241,14 +248,26 @@
             you wish to use clustering results for embedding and comparison files, set the appropriate
             clusterings to ``embedding_cell_types`` and ``comparison_cell_types``.
             
         .. versionadded:: 0.2.0 
         
             The `pairwise_downsample` option for `pwd_metric`; the `pairwise_downsample_size` parameter for when
             `pairwise_downbsample` is chosen.
+            
+        .. versionadded:: 0.3.0
+        
+            The `normalize_pwd` parameter. It was added to allow for nromalization in the EMD metric for ``Global``.
+            This should be used in cases that there are scale differences in different DR embeddings. For this
+            specific update, only "minmax" is supported.
+            
+        .. versionadded:: 0.3.0
+        
+            The `NPE_method` parameter. It was added to allow for alternative implementations of NPE's distance measure.
+            Originally, "L1" was implemented and it is stil the default. In this new version, now "tvd" is also an option.
+            Defaults to "L1".
         """
         
         if len(self.reductions) == 0:
             raise ValueError("No reductions to evalate. Add your reductions first.")
         if pwd_metric.lower() not in  ["pcd", "pairwise", "pairwise_downsample"]:
             raise ValueError("Unsupported 'pwd_metric': 'PCD', 'Pairwise', or 'pairwise_downsample' only.")
         
@@ -299,26 +318,26 @@
                 for e in self.reductions.keys():
                     embedding_distance[e] = scipy.spatial.distance.pdist(self.reductions[e], metric="euclidean")
                     
             for e in self.reductions.keys():
                 val: float = EvaluationMetrics.correlation(x=data_distance, y=embedding_distance[e], metric="Spearman")
                 self.evaluations["global"]["spearman"][e] = val
                 
-                val: float = EvaluationMetrics.EMD(x=data_distance, y=embedding_distance[e])
+                val: float = EvaluationMetrics.EMD(x=data_distance, y=embedding_distance[e], normalization=normalize_pwd)
                 self.evaluations["global"]["emd"][e] = val
                    
         if "local" in category:
             _verbose("Evaluating local...", verbose=verbose)
             assert self.original_labels is not None
             self.evaluations["local"] = {"knn": {}, "npe": {}}
             
             data_neighbors: "np.ndarray" = EvaluationMetrics.build_annoy(self.original_data, annoy_original_data_path, k_neighbors)
             for e in self.reductions.keys():
                 embedding_neighbors: "np.ndarray" = EvaluationMetrics.build_annoy(self.reductions[e], None, k_neighbors)
-                self.evaluations["local"]["npe"][e] = EvaluationMetrics.NPE(labels = self.original_labels, data_neighbors=data_neighbors, embedding_neighbors=embedding_neighbors)
+                self.evaluations["local"]["npe"][e] = EvaluationMetrics.NPE(labels = self.original_labels, data_neighbors=data_neighbors, embedding_neighbors=embedding_neighbors, method=NPE_method)
                 self.evaluations["local"]["knn"][e] = EvaluationMetrics.KNN(data_neighbors=data_neighbors, embedding_neighbors=embedding_neighbors)
                              
         if "downstream" in category:
             _verbose("Evaluating downstream...", verbose=verbose)
             self.evaluations["downstream"] = {"cluster reconstruction: silhouette": {},
                                               "cluster reconstruction: DBI": {},
                                               "cluster reconstruction: CHI": {},
```

### Comparing `CytofDR-0.2.2/CytofDR/evaluation.py` & `CytofDR-0.3.0/CytofDR/evaluation.py`

 * *Files 3% similar despite different names*

```diff
@@ -106,26 +106,43 @@
             raise ValueError("'r' must be between -1 and 1.")
         else:
             return 1 - r**2
         
         
     @staticmethod
     def EMD(x: "np.ndarray",
-            y: "np.ndarray") -> float:
+            y: "np.ndarray",
+            normalization: Optional[str] = None) -> float:
         '''Earth Mover's Distance (EMD)
         
         This metric computes the EMD between the pairwise distance of between points in the
         high and low dimensional space. This implementation uses the ``scipy.stats.wasserstein_distance``.
         The usage of EMD is proposed in Heiser & Lou (2020).
         
         :param x: The first distribution x as a 1D array.
         :param y: The second distribution y as a 1D array.
-
+        :param normalization: Whether to perfrom minmax normalization on `x` and `y`. The acceptable
+            value is `minmax`, which performs min-max normalization. If `None`, no normalization is performed.
+            Defaults to `None`.
+            
+        :raises ValueError: Unsupported normalization method.
         :return: Earth mover's distance.
+        
+        .. versionadded:: 0.3.0
+        
+            The `normalization` parameter. It was added to allow for nromalization of `x` and `y` with
+            min-max normalization using `minmax`. This is useful when `x` and `y` are empirical observations
+            that are on different scales, and the scale itself is not of interest.
         '''
+        if normalization is not None:
+            if normalization.lower() == "minmax":
+                x = (x-np.min(x))/(np.max(x)-np.min(x))
+                y = (y-np.min(y))/(np.max(y)-np.min(y))
+            else:
+                raise ValueError("Unsupported normalization method. Use 'minmax' or `None`.")
         return scipy.stats.wasserstein_distance(x, y)
 
     
     @staticmethod
     def KNN(data_neighbors: "np.ndarray",
             embedding_neighbors: "np.ndarray") -> float:
         '''K-Nearest Neighbors Preservation (KNN)
@@ -148,26 +165,53 @@
         
         return intersect/data_neighbors.size
 
     
     @staticmethod
     def NPE(data_neighbors: "np.ndarray",
             embedding_neighbors: "np.ndarray",
-            labels: "np.ndarray") -> float:
+            labels: "np.ndarray",
+            method: "str" = "L1") -> float:
         '''Neighborhood Proportion Error (NPE)
         
         The NPE metric is proposed by Konstorum et al. (2019). It measures the total variation distance between
         the proportion of nearest points belonging to the same class of each point in the HD and LD space. The
         lower the NPE, the more similar the embedding and the original data are.
         
+        To further elaborate on the difference between L1 norm and TVD, the NPE metric involves the following calculation
+        :math:`\\delta (P, Q)`, where :math:`\\delta` is a distance measureon :math:`P` and :math:`Q`. The "L1" optioc
+        computes
+        
+        .. math::
+        
+            \\sum_i |P_i-Q_i|
+            
+        whereas the TVD computes
+        
+        .. math::
+        
+            \\sup_{a\\in [0,1]} |P(a) - Q(a)| \\, .
+            
+        There is questionably some debate on the implementation used to calculate NPE, but TVD should align
+        more with the original authors' implementation.
+        
         :param data_neighbors: A nearest-neighbor array of the original data.
         :param embedding_neighbors: A nearest-neighbor array of the embedding.
         :param labels: The class labels of each observation.
+        :param method: The distance measure used for computing the distance between the neighborhood-proportion
+            vector. "L1" for L1-norm or "tvd" for Total Variation Distance. The latter is likely the intended
+            implementation by Konstorum et al. Defaults to "L1".
 
+        :raises ValueError: Unsupported `method` provided. We only support "L1" or "tvd".
         :return: Neighborhood proportion error.
+
+        .. versionadded:: 0.3.0
+        
+            The `method` parameter. It was added to allow for alternative implementations. Originally, "L1" was implemented
+            and it is stil the default. In this new version, now "tvd" is also an option.
         '''
         
         classes: "np.ndarray"
         classes_index: "np.ndarray"
         classes, classes_index = np.unique(labels, return_inverse=True)
         
         same_class_data: "np.ndarray" = np.zeros(data_neighbors.shape[0])
@@ -179,20 +223,37 @@
             i_index = classes_index[i]
             i_neighbors_data = data_neighbors[i]
             i_neighbors_embedding = embedding_neighbors[i]
             
             same_class_data[i] = np.count_nonzero(classes_index[i_neighbors_data]==i_index)/k
             same_class_embedding[i] = np.count_nonzero(classes_index[i_neighbors_embedding]==i_index)/k
         
-        distance: float=0.0
-        c: Any
-        for c in classes:
-            P: "np.ndarray" = same_class_data[labels==c]
-            Q: "np.ndarray" = same_class_embedding[labels==c]
-            distance += np.sum(np.absolute(P-Q))/2
+        distance: float = 0.0
+        c: str
+        if method.lower() == "l1":
+            for c in classes:
+                P: "np.ndarray" = same_class_data[labels==c]
+                Q: "np.ndarray" = same_class_embedding[labels==c]
+                distance += np.sum(np.absolute(P-Q))/2
+        elif method.lower() == "tvd":
+            for c in classes:
+                P: "np.ndarray" = same_class_data[labels==c]
+                Q: "np.ndarray" = same_class_embedding[labels==c]
+                if P.shape[0] < 2 or Q.shape[0] < 2:
+                    continue
+                try:
+                    P_density: "np.ndarray" = scipy.stats.gaussian_kde(P).evaluate(P)
+                    Q_density: "np.ndarray" = scipy.stats.gaussian_kde(Q).evaluate(Q)
+                except np.linalg.LinAlgError: # pragma: no cover
+                    # This is a rare situation of point mass with P or Q
+                    continue
+                else:
+                    distance += np.max(np.absolute(P_density-Q_density))
+        else:
+            raise ValueError("Method unsupported: Use 'L1' or 'tvd' instead.")
             
         return distance/classes.size
     
     
     @staticmethod
     def neighborhood_agreement(data_neighbors: "np.ndarray",
                                embedding_neighbors: "np.ndarray") -> float:
```

### Comparing `CytofDR-0.2.2/CytofDR.egg-info/PKG-INFO` & `CytofDR-0.3.0/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,45 +1,23 @@
-Metadata-Version: 2.1
-Name: CytofDR
-Version: 0.2.2
-Summary: CyTOF Dimension Reduction Framework
-Home-page: https://github.com/kevin931/CytofDR
-Author: Kevin Wang
-License: MIT
-Platform: UNKNOWN
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Natural Language :: English
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE.txt
-License-File: LICENSE_associated.txt
-
 # CyTOF Dimension Reduction Framework
 
 > A framework of dimension reduction and its evaluation for both CyTOF and general-purpose usages.
 
 ![Logo](/assets/logo.png)
 
 | Branch | Release | CI/CD | Documentation | Code Coverage |
 | --- | --- | --- | --- | --- |
-| dev | ![Badge1](https://img.shields.io/badge/Version-0.2.1-success) |![Tests](https://github.com/kevin931/CytofDR/actions/workflows/ci.yml/badge.svg?branch=dev) | [![Documentation Status](https://readthedocs.org/projects/cytofdr/badge/?version=latest)](https://cytofdr.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/kevin931/CytofDR/branch/dev/graph/badge.svg?token=K9AJQLYU8N)](https://codecov.io/gh/kevin931/CytofDR) |
+| dev | ![Badge1](https://img.shields.io/badge/Version-0.3.0-success) |![Tests](https://github.com/kevin931/CytofDR/actions/workflows/ci.yml/badge.svg?branch=dev) | [![Documentation Status](https://readthedocs.org/projects/cytofdr/badge/?version=latest)](https://cytofdr.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/kevin931/CytofDR/branch/dev/graph/badge.svg?token=K9AJQLYU8N)](https://codecov.io/gh/kevin931/CytofDR) |
 
 
 ## About
 
 CytofDR is a framework of dimension reduction (DR) and its evaluation for both Cytometry by Time-of-Flight (CyTOF) and general-purpose usages. It allows you to
 conveniently run many different DRs at one place and then evaluate them to pick your embedding using our extensive evaluation framework! We aim to provide you with a reliable, extensible, and convenient interface for all your DR needs for both data analyses and future research!
 
-### Key Resources
-
-- For **detailed benchmarks and methodology explanations**, please check out [our paper](https://doi.org/10.1038/s41467-023-37478-w) in *Nature Communications*!
-- For an online version of **interactive results**, please checkout [CytofDR Playground](https://dbai.biohpc.swmed.edu/cytof-dr-playground/).
-- For **documentation**, please visit our free and detailed [documentation page](https://cytofdr.readthedocs.io/en/stable/index.html).
-
 ## Installation
 
 You can install our CytofDR package, which is currentl on ``PyPI``:
 
 ```shell
 pip install CytofDR
 ```
@@ -81,15 +59,15 @@
 
 ``CytofDR`` is a member of the **PyCytoData Alliance Plus**, meaning that we're compatible with the ``PyCytoData`` package. The ``PyCytoData`` package is used mainly for loading datasets and managing every step of the CyTOF workflow. By creating and maintaining this ecosystem, we hope to create a robust workflow as a one-stop solution for CyTOF practioners using Python. To install ``PyCytoData``, you can simply use the following command:
 
 ```shell
 pip install PyCytoData
 ```
 
-To view how you can perform DR using ``PyCYtoData``, [this tutorial](https://pycytodata.readthedocs.io/en/latest/tutorial/dr.html) walks through every step.
+To view how you can perform DR using ``PyCYtoData``, [this tutorial](https://pycytodata.readthedocs.io/en/latest/tutorial/dr.html) walks through every ste
 
 ## Quick Tutorial
 
 ``CytofDR`` makes it easy to run many DR methods while also evaluating them for your CyTOF samples. We have a greatly simplified pipeline for your needs. To get started, follow this example:
 
 ```python
 >>> import numpy as np
@@ -149,51 +127,46 @@
 
 ### Documentation
 
 Of course, there are many more customizations and ways you can use ``CytofDR``. So, for detailed tutorials and other guides, we suggest that you vists our [Official Documentation](https://cytofdr.readthedocs.io/en/latest/index.html).
 
 There you will find ways to install our package and get started! Also, we offer tutorials on customizations, working with DR methods, and finally our detailed evaluation framework. We hope that you can find what you need over there!
 
-## Latest Release: v0.2.2
+## Latest Release: v0.3.0
 
-This is a minor maintenance update of v0.2.x with a few improvements on documentation and docstrings.
-
-This is a minor maintenance update of v0.2.x with updated references and documentation.
+This releases adds some new features along with some minor improvements and fixes.
 
 ### Changes and New Features
 
-- Updated referneces and citation information in all relavent documentaion pages
-- Removed a warning on SAUCIE's installation documentation
+- Add `minmax` normalization option for the `evaluation.EvaluationMetric.EMD` method
+- Add alternative implementation of `evaluation.EvaluationMetric.NPE` with total variation distance (TVD)
+- Allow both min-max EMD and and TVD NPE for automatic evaluation of DR methods
 
 ### Improvements
 
-- Update-to-date documentation and references
+- Docstrings and documentations reformatted for clarity
 
 ### Deprecations
 
 - (Since v0.2.0) The `comparison_classes` parameter of the `EvaluationMetrics.embedding_concordance` method will no longer accept `str` input.
 
 ## Issues and Contributions
 
 If you run into issues or have questions, feel free to open an issue [here](https://github.com/kevin931/CytofDR/issues). I'd love to help you out! We also welcome any contributions, but you may want to also look our [contribution guide](https://cytofdr.readthedocs.io/en/latest/change/contribution.html). Even if you just have an idea, that'll be great!
 
 ## References
 
-Our preprint "Comparative Analysis of Dimension Reductions Methods for Cytometry by Time-of-Flight Data" is on bioRxiv and can be accessed [right here](https://doi.org/10.1038/s41467-023-37478-w). If you use our package in your research or deployment, a citation of our paper is highly appreciated:
+Our preprint "Comparative Analysis of Dimension Reductions Methods for Cytometry by Time-of-Flight Data" is on bioRxiv and can be accessed [right here](https://doi.org/10.1101/2022.04.26.489549). If you use our package in your research or deployment, a citation of our paper is highly appreciated:
 
 ```
-@article{wang2023comparative,
-  title={Comparative analysis of dimension reduction methods for cytometry by time-of-flight data},
+@article{wang2022comparison,
+  title={A Comparison of Dimension Reduction Methods for Cytometry by Time-of-Flight Data},
   author={Wang, Kaiwen and Yang, Yuqiu and Wu, Fangjiang and Song, Bing and Wang, Xinlei and Wang, Tao},
-  journal={Nature Communications},
-  volume={14},
-  number={1},
-  pages={1--18},
-  year={2023},
-  publisher={Nature Publishing Group}
+  journal={BioRxiv},
+  pages={2022--04},
+  year={2022},
+  publisher={Cold Spring Harbor Laboratory}
 }
 ```
 
 For a list of references of the methods, metrics, etc. used in the package, please visit our [References](https://cytofdr.readthedocs.io/en/latest/references.html) and bibliography of our paper.
 
-
-
```

### Comparing `CytofDR-0.2.2/LICENSE.txt` & `CytofDR-0.3.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `CytofDR-0.2.2/LICENSE_associated.txt` & `CytofDR-0.3.0/LICENSE_associated.txt`

 * *Files identical despite different names*

### Comparing `CytofDR-0.2.2/PKG-INFO` & `CytofDR-0.3.0/CytofDR.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: CytofDR
-Version: 0.2.2
+Version: 0.3.0
 Summary: CyTOF Dimension Reduction Framework
 Home-page: https://github.com/kevin931/CytofDR
 Author: Kevin Wang
 License: MIT
 Platform: UNKNOWN
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3 :: Only
@@ -18,28 +18,22 @@
 
 > A framework of dimension reduction and its evaluation for both CyTOF and general-purpose usages.
 
 ![Logo](/assets/logo.png)
 
 | Branch | Release | CI/CD | Documentation | Code Coverage |
 | --- | --- | --- | --- | --- |
-| dev | ![Badge1](https://img.shields.io/badge/Version-0.2.1-success) |![Tests](https://github.com/kevin931/CytofDR/actions/workflows/ci.yml/badge.svg?branch=dev) | [![Documentation Status](https://readthedocs.org/projects/cytofdr/badge/?version=latest)](https://cytofdr.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/kevin931/CytofDR/branch/dev/graph/badge.svg?token=K9AJQLYU8N)](https://codecov.io/gh/kevin931/CytofDR) |
+| dev | ![Badge1](https://img.shields.io/badge/Version-0.3.0-success) |![Tests](https://github.com/kevin931/CytofDR/actions/workflows/ci.yml/badge.svg?branch=dev) | [![Documentation Status](https://readthedocs.org/projects/cytofdr/badge/?version=latest)](https://cytofdr.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/kevin931/CytofDR/branch/dev/graph/badge.svg?token=K9AJQLYU8N)](https://codecov.io/gh/kevin931/CytofDR) |
 
 
 ## About
 
 CytofDR is a framework of dimension reduction (DR) and its evaluation for both Cytometry by Time-of-Flight (CyTOF) and general-purpose usages. It allows you to
 conveniently run many different DRs at one place and then evaluate them to pick your embedding using our extensive evaluation framework! We aim to provide you with a reliable, extensible, and convenient interface for all your DR needs for both data analyses and future research!
 
-### Key Resources
-
-- For **detailed benchmarks and methodology explanations**, please check out [our paper](https://doi.org/10.1038/s41467-023-37478-w) in *Nature Communications*!
-- For an online version of **interactive results**, please checkout [CytofDR Playground](https://dbai.biohpc.swmed.edu/cytof-dr-playground/).
-- For **documentation**, please visit our free and detailed [documentation page](https://cytofdr.readthedocs.io/en/stable/index.html).
-
 ## Installation
 
 You can install our CytofDR package, which is currentl on ``PyPI``:
 
 ```shell
 pip install CytofDR
 ```
@@ -81,15 +75,15 @@
 
 ``CytofDR`` is a member of the **PyCytoData Alliance Plus**, meaning that we're compatible with the ``PyCytoData`` package. The ``PyCytoData`` package is used mainly for loading datasets and managing every step of the CyTOF workflow. By creating and maintaining this ecosystem, we hope to create a robust workflow as a one-stop solution for CyTOF practioners using Python. To install ``PyCytoData``, you can simply use the following command:
 
 ```shell
 pip install PyCytoData
 ```
 
-To view how you can perform DR using ``PyCYtoData``, [this tutorial](https://pycytodata.readthedocs.io/en/latest/tutorial/dr.html) walks through every step.
+To view how you can perform DR using ``PyCYtoData``, [this tutorial](https://pycytodata.readthedocs.io/en/latest/tutorial/dr.html) walks through every ste
 
 ## Quick Tutorial
 
 ``CytofDR`` makes it easy to run many DR methods while also evaluating them for your CyTOF samples. We have a greatly simplified pipeline for your needs. To get started, follow this example:
 
 ```python
 >>> import numpy as np
@@ -149,51 +143,48 @@
 
 ### Documentation
 
 Of course, there are many more customizations and ways you can use ``CytofDR``. So, for detailed tutorials and other guides, we suggest that you vists our [Official Documentation](https://cytofdr.readthedocs.io/en/latest/index.html).
 
 There you will find ways to install our package and get started! Also, we offer tutorials on customizations, working with DR methods, and finally our detailed evaluation framework. We hope that you can find what you need over there!
 
-## Latest Release: v0.2.2
-
-This is a minor maintenance update of v0.2.x with a few improvements on documentation and docstrings.
+## Latest Release: v0.3.0
 
-This is a minor maintenance update of v0.2.x with updated references and documentation.
+This releases adds some new features along with some minor improvements and fixes.
 
 ### Changes and New Features
 
-- Updated referneces and citation information in all relavent documentaion pages
-- Removed a warning on SAUCIE's installation documentation
+- Add `minmax` normalization option for the `evaluation.EvaluationMetric.EMD` method
+- Add alternative implementation of `evaluation.EvaluationMetric.NPE` with total variation distance (TVD)
+- Allow both min-max EMD and and TVD NPE for automatic evaluation of DR methods
 
 ### Improvements
 
-- Update-to-date documentation and references
+- Docstrings and documentations reformatted for clarity
 
 ### Deprecations
 
 - (Since v0.2.0) The `comparison_classes` parameter of the `EvaluationMetrics.embedding_concordance` method will no longer accept `str` input.
 
 ## Issues and Contributions
 
 If you run into issues or have questions, feel free to open an issue [here](https://github.com/kevin931/CytofDR/issues). I'd love to help you out! We also welcome any contributions, but you may want to also look our [contribution guide](https://cytofdr.readthedocs.io/en/latest/change/contribution.html). Even if you just have an idea, that'll be great!
 
 ## References
 
-Our preprint "Comparative Analysis of Dimension Reductions Methods for Cytometry by Time-of-Flight Data" is on bioRxiv and can be accessed [right here](https://doi.org/10.1038/s41467-023-37478-w). If you use our package in your research or deployment, a citation of our paper is highly appreciated:
+Our preprint "Comparative Analysis of Dimension Reductions Methods for Cytometry by Time-of-Flight Data" is on bioRxiv and can be accessed [right here](https://doi.org/10.1101/2022.04.26.489549). If you use our package in your research or deployment, a citation of our paper is highly appreciated:
 
 ```
-@article{wang2023comparative,
-  title={Comparative analysis of dimension reduction methods for cytometry by time-of-flight data},
+@article{wang2022comparison,
+  title={A Comparison of Dimension Reduction Methods for Cytometry by Time-of-Flight Data},
   author={Wang, Kaiwen and Yang, Yuqiu and Wu, Fangjiang and Song, Bing and Wang, Xinlei and Wang, Tao},
-  journal={Nature Communications},
-  volume={14},
-  number={1},
-  pages={1--18},
-  year={2023},
-  publisher={Nature Publishing Group}
+  journal={BioRxiv},
+  pages={2022--04},
+  year={2022},
+  publisher={Cold Spring Harbor Laboratory}
 }
 ```
 
 For a list of references of the methods, metrics, etc. used in the package, please visit our [References](https://cytofdr.readthedocs.io/en/latest/references.html) and bibliography of our paper.
```

### Comparing `CytofDR-0.2.2/README.md` & `CytofDR-0.3.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,29 +1,39 @@
+Metadata-Version: 2.1
+Name: CytofDR
+Version: 0.3.0
+Summary: CyTOF Dimension Reduction Framework
+Home-page: https://github.com/kevin931/CytofDR
+Author: Kevin Wang
+License: MIT
+Platform: UNKNOWN
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Natural Language :: English
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE.txt
+License-File: LICENSE_associated.txt
+
 # CyTOF Dimension Reduction Framework
 
 > A framework of dimension reduction and its evaluation for both CyTOF and general-purpose usages.
 
 ![Logo](/assets/logo.png)
 
 | Branch | Release | CI/CD | Documentation | Code Coverage |
 | --- | --- | --- | --- | --- |
-| dev | ![Badge1](https://img.shields.io/badge/Version-0.2.1-success) |![Tests](https://github.com/kevin931/CytofDR/actions/workflows/ci.yml/badge.svg?branch=dev) | [![Documentation Status](https://readthedocs.org/projects/cytofdr/badge/?version=latest)](https://cytofdr.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/kevin931/CytofDR/branch/dev/graph/badge.svg?token=K9AJQLYU8N)](https://codecov.io/gh/kevin931/CytofDR) |
+| dev | ![Badge1](https://img.shields.io/badge/Version-0.3.0-success) |![Tests](https://github.com/kevin931/CytofDR/actions/workflows/ci.yml/badge.svg?branch=dev) | [![Documentation Status](https://readthedocs.org/projects/cytofdr/badge/?version=latest)](https://cytofdr.readthedocs.io/en/latest/?badge=latest) | [![codecov](https://codecov.io/gh/kevin931/CytofDR/branch/dev/graph/badge.svg?token=K9AJQLYU8N)](https://codecov.io/gh/kevin931/CytofDR) |
 
 
 ## About
 
 CytofDR is a framework of dimension reduction (DR) and its evaluation for both Cytometry by Time-of-Flight (CyTOF) and general-purpose usages. It allows you to
 conveniently run many different DRs at one place and then evaluate them to pick your embedding using our extensive evaluation framework! We aim to provide you with a reliable, extensible, and convenient interface for all your DR needs for both data analyses and future research!
 
-### Key Resources
-
-- For **detailed benchmarks and methodology explanations**, please check out [our paper](https://doi.org/10.1038/s41467-023-37478-w) in *Nature Communications*!
-- For an online version of **interactive results**, please checkout [CytofDR Playground](https://dbai.biohpc.swmed.edu/cytof-dr-playground/).
-- For **documentation**, please visit our free and detailed [documentation page](https://cytofdr.readthedocs.io/en/stable/index.html).
-
 ## Installation
 
 You can install our CytofDR package, which is currentl on ``PyPI``:
 
 ```shell
 pip install CytofDR
 ```
@@ -65,15 +75,15 @@
 
 ``CytofDR`` is a member of the **PyCytoData Alliance Plus**, meaning that we're compatible with the ``PyCytoData`` package. The ``PyCytoData`` package is used mainly for loading datasets and managing every step of the CyTOF workflow. By creating and maintaining this ecosystem, we hope to create a robust workflow as a one-stop solution for CyTOF practioners using Python. To install ``PyCytoData``, you can simply use the following command:
 
 ```shell
 pip install PyCytoData
 ```
 
-To view how you can perform DR using ``PyCYtoData``, [this tutorial](https://pycytodata.readthedocs.io/en/latest/tutorial/dr.html) walks through every step.
+To view how you can perform DR using ``PyCYtoData``, [this tutorial](https://pycytodata.readthedocs.io/en/latest/tutorial/dr.html) walks through every ste
 
 ## Quick Tutorial
 
 ``CytofDR`` makes it easy to run many DR methods while also evaluating them for your CyTOF samples. We have a greatly simplified pipeline for your needs. To get started, follow this example:
 
 ```python
 >>> import numpy as np
@@ -133,49 +143,48 @@
 
 ### Documentation
 
 Of course, there are many more customizations and ways you can use ``CytofDR``. So, for detailed tutorials and other guides, we suggest that you vists our [Official Documentation](https://cytofdr.readthedocs.io/en/latest/index.html).
 
 There you will find ways to install our package and get started! Also, we offer tutorials on customizations, working with DR methods, and finally our detailed evaluation framework. We hope that you can find what you need over there!
 
-## Latest Release: v0.2.2
+## Latest Release: v0.3.0
 
-This is a minor maintenance update of v0.2.x with a few improvements on documentation and docstrings.
-
-This is a minor maintenance update of v0.2.x with updated references and documentation.
+This releases adds some new features along with some minor improvements and fixes.
 
 ### Changes and New Features
 
-- Updated referneces and citation information in all relavent documentaion pages
-- Removed a warning on SAUCIE's installation documentation
+- Add `minmax` normalization option for the `evaluation.EvaluationMetric.EMD` method
+- Add alternative implementation of `evaluation.EvaluationMetric.NPE` with total variation distance (TVD)
+- Allow both min-max EMD and and TVD NPE for automatic evaluation of DR methods
 
 ### Improvements
 
-- Update-to-date documentation and references
+- Docstrings and documentations reformatted for clarity
 
 ### Deprecations
 
 - (Since v0.2.0) The `comparison_classes` parameter of the `EvaluationMetrics.embedding_concordance` method will no longer accept `str` input.
 
 ## Issues and Contributions
 
 If you run into issues or have questions, feel free to open an issue [here](https://github.com/kevin931/CytofDR/issues). I'd love to help you out! We also welcome any contributions, but you may want to also look our [contribution guide](https://cytofdr.readthedocs.io/en/latest/change/contribution.html). Even if you just have an idea, that'll be great!
 
 ## References
 
-Our preprint "Comparative Analysis of Dimension Reductions Methods for Cytometry by Time-of-Flight Data" is on bioRxiv and can be accessed [right here](https://doi.org/10.1038/s41467-023-37478-w). If you use our package in your research or deployment, a citation of our paper is highly appreciated:
+Our preprint "Comparative Analysis of Dimension Reductions Methods for Cytometry by Time-of-Flight Data" is on bioRxiv and can be accessed [right here](https://doi.org/10.1101/2022.04.26.489549). If you use our package in your research or deployment, a citation of our paper is highly appreciated:
 
 ```
-@article{wang2023comparative,
-  title={Comparative analysis of dimension reduction methods for cytometry by time-of-flight data},
+@article{wang2022comparison,
+  title={A Comparison of Dimension Reduction Methods for Cytometry by Time-of-Flight Data},
   author={Wang, Kaiwen and Yang, Yuqiu and Wu, Fangjiang and Song, Bing and Wang, Xinlei and Wang, Tao},
-  journal={Nature Communications},
-  volume={14},
-  number={1},
-  pages={1--18},
-  year={2023},
-  publisher={Nature Publishing Group}
+  journal={BioRxiv},
+  pages={2022--04},
+  year={2022},
+  publisher={Cold Spring Harbor Laboratory}
 }
 ```
 
 For a list of references of the methods, metrics, etc. used in the package, please visit our [References](https://cytofdr.readthedocs.io/en/latest/references.html) and bibliography of our paper.
 
+
+
```

### Comparing `CytofDR-0.2.2/setup.py` & `CytofDR-0.3.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import setuptools
 import sys
 import os
 import shutil
 import distutils.cmd
 
-VERSION = "0.2.2"
+VERSION = "0.3.0"
 
 class PypiCommand(distutils.cmd.Command):
     
     description = "Build and upload for PyPI."
     user_options = []
     
     def initialize_options(self):
```


# Comparing `tmp/drfetools-0.3.3.tar.gz` & `tmp/drfetools-0.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "drfetools-0.3.3.tar", max compression
+gzip compressed data, was "drfetools-0.3.4.tar", max compression
```

## Comparing `drfetools-0.3.3.tar` & `drfetools-0.3.4.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0    35149 2021-09-02 20:40:08.000000 drfetools-0.3.3/LICENSE
--rw-r--r--   0        0        0    18709 2023-06-26 21:39:30.000000 drfetools-0.3.3/README.md
--rw-r--r--   0        0        0       48 2023-06-27 13:02:05.000000 drfetools-0.3.3/dRFEtools/__init__.py
--rwxr-xr-x   0        0        0     9851 2023-06-27 12:59:16.000000 drfetools-0.3.3/dRFEtools/dRFEtools.py
--rw-r--r--   0        0        0     8251 2023-06-21 20:40:36.000000 drfetools-0.3.3/dRFEtools/dev_scoring.py
--rw-r--r--   0        0        0     7643 2023-06-21 20:55:18.000000 drfetools-0.3.3/dRFEtools/lowess_redundant.py
--rw-r--r--   0        0        0     7306 2023-06-21 20:40:54.000000 drfetools-0.3.3/dRFEtools/random_forest.py
--rw-r--r--   0        0        0     1605 2021-09-30 19:29:32.000000 drfetools-0.3.3/dRFEtools/rank_function.py
--rw-r--r--   0        0        0     1035 2023-06-27 13:01:56.000000 drfetools-0.3.3/pyproject.toml
--rw-r--r--   0        0        0    19886 1970-01-01 00:00:00.000000 drfetools-0.3.3/PKG-INFO
+-rw-r--r--   0        0        0    35149 2021-09-02 20:40:08.000000 drfetools-0.3.4/LICENSE
+-rw-r--r--   0        0        0    18802 2023-06-27 16:08:58.000000 drfetools-0.3.4/README.md
+-rw-r--r--   0        0        0       48 2023-06-28 12:28:37.000000 drfetools-0.3.4/dRFEtools/__init__.py
+-rwxr-xr-x   0        0        0     9851 2023-06-27 12:59:16.000000 drfetools-0.3.4/dRFEtools/dRFEtools.py
+-rw-r--r--   0        0        0    10166 2023-06-27 16:06:35.000000 drfetools-0.3.4/dRFEtools/dev_scoring.py
+-rw-r--r--   0        0        0     7643 2023-06-21 20:55:18.000000 drfetools-0.3.4/dRFEtools/lowess_redundant.py
+-rw-r--r--   0        0        0     7303 2023-06-27 14:28:21.000000 drfetools-0.3.4/dRFEtools/random_forest.py
+-rw-r--r--   0        0        0     1605 2021-09-30 19:29:32.000000 drfetools-0.3.4/dRFEtools/rank_function.py
+-rw-r--r--   0        0        0     1035 2023-06-28 12:28:27.000000 drfetools-0.3.4/pyproject.toml
+-rw-r--r--   0        0        0    19979 1970-01-01 00:00:00.000000 drfetools-0.3.4/PKG-INFO
```

### Comparing `drfetools-0.3.3/LICENSE` & `drfetools-0.3.4/LICENSE`

 * *Files identical despite different names*

### Comparing `drfetools-0.3.3/README.md` & `drfetools-0.3.4/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -4,15 +4,16 @@
 sklearn.
 
 Authors: Apuã Paquola, Kynon Jade Benjamin, and Tarun Katipalli
 
 Package developed in Python 3.8+.
 
 In addition to scikit-learn, `dRFEtools` is also built with NumPy, SciPy,
-Pandas, matplotlib, plotnine, and statsmodels.
+Pandas, matplotlib, plotnine, and statsmodels. Currently, dynamic RFE supports
+models with `coef_` or `feature_importances_` attribute.
 
 This package has several function to run dynamic recursive feature elimination
 (dRFE) for random forest and linear model classifier and regression models. For
 random forest, it assumes Out-of-Bag (OOB) is set to True. For linear models,
 it generates a developmental set. For both classification and regression, three
 measurements are calculated for feature selection:
 
@@ -26,15 +27,15 @@
 
 1.  R2 (this can be negative if model is arbitrarily worse)
 2.  Explained variance
 3.  Mean squared error
 
 The package has been split in to four additional scripts for:
 
-1.  Out-of-bag dynamic RFE metrics (AP)
+1.  Out-of-bag dynamic RFE metrics (AP/KJB)
 2.  Validation set dynamic RFE metrics (KJB)
 3.  Rank features function (TK)
 4.  Lowess core + peripheral selection (KJB)
 
 # Table of Contents
 
 1.  [Citation](#org7b64d47)
```

### Comparing `drfetools-0.3.3/dRFEtools/dRFEtools.py` & `drfetools-0.3.4/dRFEtools/dRFEtools.py`

 * *Files identical despite different names*

### Comparing `drfetools-0.3.3/dRFEtools/dev_scoring.py` & `drfetools-0.3.4/dRFEtools/dev_scoring.py`

 * *Files 20% similar despite different names*

```diff
@@ -6,40 +6,93 @@
 Developed by Kynon Jade Benjamin.
 """
 
 __author__ = 'Kynon J Benjamin'
 
 import numpy as np
 from itertools import chain
+from operator import attrgetter
 from sklearn.metrics import r2_score
 from sklearn.base import is_classifier
 from .rank_function import features_rank_fnc
 from sklearn.metrics import mean_squared_error
 from sklearn.model_selection import train_test_split
 from sklearn.metrics import explained_variance_score
 from sklearn.inspection import permutation_importance
 from sklearn.metrics import normalized_mutual_info_score
 from sklearn.metrics import roc_auc_score, accuracy_score
 
 
-def cal_feature_imp(estimator):
+def dev_cal_feature_imp(estimator):
     """
     Adds feature importance to a scikit-learn estimator. This is similar
     to random forest output feature importances output.
 
     This function also checks dimensions to handle multi-class inputs.
     """
-    if estimator.coef_.ndim == 1:
-        estimator.feature_importances_ = np.abs(estimator.coef_).flatten()
-    else:
-        estimator.feature_importances_ = np.amax(np.abs(estimator.coef_),
+    if hasattr(estimator, "feature_log_prob_"):
+        prob = np.exp(np.amax(estimator.feature_log_prob_, axis=0))
+        estimator.feature_importances_ = prob.flatten()
+    elif hasattr(estimator, "feature_importances_"):
+        pass
+    elif hasattr(estimator, "coef_"):
+        if estimator.coef_.ndim == 1:
+            estimator.feature_importances_ = np.abs(estimator.coef_).flatten()
+        else:
+            estimator.feature_importances_ = np.amax(np.abs(estimator.coef_),
+                                                     axis=0).flatten()
+    elif hasattr(estimator, "dual_coef_"):
+        estimator.feature_importances_ = np.amax(np.abs(estimator.dual_coef_),
                                                  axis=0).flatten()
+    else:
+        raise AttributeError("model not supported")
     return estimator
 
 
+def _get_feature_importances(estimator):
+    """
+    Retrieve and aggregate (ndim > 1) feature importance
+    from scikit-learn estimator.
+
+    This function also checks dimensions to handle multi-class inputs.
+
+    Parameters
+    ----------
+    estimator : estimator
+        A scikit-learn estimator from which we want to get the feature
+        importances
+
+    Returns
+    -------
+    importances : ndarray of shape (n_features,)
+        The features importances, optionally transformed
+    """
+    if hasattr(estimator, "coef_"):
+        getter = attrgetter("coef_")
+        transform_fnc = "norm"
+    elif hasattr(estimator, "feature_importances_"):
+        getter = attrgetter("feature_importances_")
+        transform_fnc = None
+    else:
+        raise ValueError(
+            f"the underlying estimator {estimator.__class__.__name__} "
+            "should have `coef_` or `features_importances_` attribute."
+        )
+    importances = getter(estimator)
+    if transform_fnc is None:
+        return importances
+    elif transform_fnc == "norm":
+        if importances.ndim == 1:
+            importances = np.abs(importances).flatten()
+        else:
+            importances = np.linalg.norm(importances, axis=0,
+                                         ord=1).flatten()
+    return importances
+
+
 def dev_predictions(estimator, X):
     """
     Extracts predictions using a development fold for linear model
     regression.
 
     Args:
     estimator: linear model regression object
@@ -184,15 +237,15 @@
     X1, X2, Y1, Y2 = train_test_split(X, Y, **kwargs)
     # print(X.shape[1], n_features_to_keep)
     assert n_features_to_keep <= X1.shape[1]
     estimator.fit(X1, Y1)
     test_indices = np.array(range(X1.shape[1]))
     #res = permutation_importance(estimator, X2, Y2, n_jobs=-1, random_state=13)
     #rank = test_indices[res.importances_mean.argsort()]
-    estimator = cal_feature_imp(estimator)
+    estimator.feature_importances_ = _get_feature_importances(estimator)
     rank = test_indices[np.argsort(estimator.feature_importances_)]
     rank = rank[::-1] # reverse sort
     selected = rank[0:n_features_to_keep]
     features_rank_fnc(features, rank, n_features_to_keep, fold, out_dir, RANK)
     if is_classifier(estimator):
         return {"n_features": X1.shape[1],
                 "nmi_score": dev_score_nmi(estimator, X2, Y2),
```

### Comparing `drfetools-0.3.3/dRFEtools/lowess_redundant.py` & `drfetools-0.3.4/dRFEtools/lowess_redundant.py`

 * *Files identical despite different names*

### Comparing `drfetools-0.3.3/dRFEtools/random_forest.py` & `drfetools-0.3.4/dRFEtools/random_forest.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 """
-This package has several function to run feature elimination for random forest
-classifier. Specifically, Out-of-Bag (OOB) must be set to True. Three
-measurements are calculated for feature selection.
+This package has several function to run feature elimination for
+random forest, it will use the out-of-bag (OOB), assuming
+OOB set to True. Three measurements are calculated for feature selection.
 
 1. Normalized mutual information
 2. Accuracy
 3. Area under the curve (AUC) ROC curve
 
 Original author Apua Paquola.
 Edits: Kynon Jade Benjamin
```

### Comparing `drfetools-0.3.3/dRFEtools/rank_function.py` & `drfetools-0.3.4/dRFEtools/rank_function.py`

 * *Files identical despite different names*

### Comparing `drfetools-0.3.3/pyproject.toml` & `drfetools-0.3.4/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 [tool.poetry]
 name = "dRFEtools"
 packages = [
     {include = "dRFEtools"}
 ]
-version = "0.3.3"
+version = "0.3.4"
 description = "A package for preforming dynamic recursive feature elimination with sklearn."
 authors = ["Kynon JM Benjamin <kj.benjamin90@gmail.com>", "Apuã Paquola <apua.paquola@libd.org>"]
 maintainers = ["Kynon JM Benjamin <kj.benjamin90@gmail.com>"]
 license = "GPL-3.0-only"
 readme = "README.md"
 homepage = "https://github.com/LieberInstitute/dRFEtools.git"
 repository = "https://github.com/LieberInstitute/dRFEtools.git"
```

### Comparing `drfetools-0.3.3/PKG-INFO` & `drfetools-0.3.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: drfetools
-Version: 0.3.3
+Version: 0.3.4
 Summary: A package for preforming dynamic recursive feature elimination with sklearn.
 Home-page: https://github.com/LieberInstitute/dRFEtools.git
 License: GPL-3.0-only
 Keywords: recursive feature elimination,sklearn,feature ranking
 Author: Kynon JM Benjamin
 Author-email: kj.benjamin90@gmail.com
 Maintainer: Kynon JM Benjamin
@@ -32,15 +32,16 @@
 sklearn.
 
 Authors: Apuã Paquola, Kynon Jade Benjamin, and Tarun Katipalli
 
 Package developed in Python 3.8+.
 
 In addition to scikit-learn, `dRFEtools` is also built with NumPy, SciPy,
-Pandas, matplotlib, plotnine, and statsmodels.
+Pandas, matplotlib, plotnine, and statsmodels. Currently, dynamic RFE supports
+models with `coef_` or `feature_importances_` attribute.
 
 This package has several function to run dynamic recursive feature elimination
 (dRFE) for random forest and linear model classifier and regression models. For
 random forest, it assumes Out-of-Bag (OOB) is set to True. For linear models,
 it generates a developmental set. For both classification and regression, three
 measurements are calculated for feature selection:
 
@@ -54,15 +55,15 @@
 
 1.  R2 (this can be negative if model is arbitrarily worse)
 2.  Explained variance
 3.  Mean squared error
 
 The package has been split in to four additional scripts for:
 
-1.  Out-of-bag dynamic RFE metrics (AP)
+1.  Out-of-bag dynamic RFE metrics (AP/KJB)
 2.  Validation set dynamic RFE metrics (KJB)
 3.  Rank features function (TK)
 4.  Lowess core + peripheral selection (KJB)
 
 # Table of Contents
 
 1.  [Citation](#org7b64d47)
```


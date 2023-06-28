# Comparing `tmp/pyBigKinds-1.1.1-py3-none-any.whl.zip` & `tmp/pyBigKinds-1.2.0-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,13 +1,13 @@
-Zip file size: 7552 bytes, number of entries: 11
--rw-r--r--  2.0 unx      783 b- defN 23-Jun-08 17:25 pyBigKinds/__init__.py
--rw-r--r--  2.0 unx       22 b- defN 23-Jun-08 17:25 pyBigKinds/_version.py
--rw-r--r--  2.0 unx     2475 b- defN 23-Jun-08 17:25 pyBigKinds/base.py
--rw-r--r--  2.0 unx     2552 b- defN 23-Jun-08 17:25 pyBigKinds/preprocessing.py
--rw-r--r--  2.0 unx     4080 b- defN 23-Jun-08 17:25 pyBigKinds/representation.py
--rw-r--r--  2.0 unx     2386 b- defN 23-Jun-08 17:25 pyBigKinds/visualization.py
--rw-r--r--  2.0 unx     1070 b- defN 23-Jun-08 17:27 pyBigKinds-1.1.1.dist-info/LICENSE
--rw-r--r--  2.0 unx     1521 b- defN 23-Jun-08 17:27 pyBigKinds-1.1.1.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-Jun-08 17:27 pyBigKinds-1.1.1.dist-info/WHEEL
--rw-r--r--  2.0 unx       11 b- defN 23-Jun-08 17:27 pyBigKinds-1.1.1.dist-info/top_level.txt
--rw-rw-r--  2.0 unx      884 b- defN 23-Jun-08 17:27 pyBigKinds-1.1.1.dist-info/RECORD
-11 files, 15876 bytes uncompressed, 6058 bytes compressed:  61.8%
+Zip file size: 7719 bytes, number of entries: 11
+-rw-r--r--  2.0 unx      800 b- defN 23-Jun-28 15:28 pyBigKinds/__init__.py
+-rw-r--r--  2.0 unx       22 b- defN 23-Jun-28 15:28 pyBigKinds/_version.py
+-rw-r--r--  2.0 unx     2501 b- defN 23-Jun-28 15:28 pyBigKinds/base.py
+-rw-r--r--  2.0 unx     2552 b- defN 23-Jun-28 15:28 pyBigKinds/preprocessing.py
+-rw-r--r--  2.0 unx     4566 b- defN 23-Jun-28 15:28 pyBigKinds/representation.py
+-rw-r--r--  2.0 unx     2386 b- defN 23-Jun-28 15:28 pyBigKinds/visualization.py
+-rw-r--r--  2.0 unx     1070 b- defN 23-Jun-28 15:29 pyBigKinds-1.2.0.dist-info/LICENSE
+-rw-r--r--  2.0 unx     1526 b- defN 23-Jun-28 15:29 pyBigKinds-1.2.0.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 15:29 pyBigKinds-1.2.0.dist-info/WHEEL
+-rw-r--r--  2.0 unx       11 b- defN 23-Jun-28 15:29 pyBigKinds-1.2.0.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx      884 b- defN 23-Jun-28 15:29 pyBigKinds-1.2.0.dist-info/RECORD
+11 files, 16410 bytes uncompressed, 6225 bytes compressed:  62.1%
```

## zipnote {}

```diff
@@ -12,23 +12,23 @@
 
 Filename: pyBigKinds/representation.py
 Comment: 
 
 Filename: pyBigKinds/visualization.py
 Comment: 
 
-Filename: pyBigKinds-1.1.1.dist-info/LICENSE
+Filename: pyBigKinds-1.2.0.dist-info/LICENSE
 Comment: 
 
-Filename: pyBigKinds-1.1.1.dist-info/METADATA
+Filename: pyBigKinds-1.2.0.dist-info/METADATA
 Comment: 
 
-Filename: pyBigKinds-1.1.1.dist-info/WHEEL
+Filename: pyBigKinds-1.2.0.dist-info/WHEEL
 Comment: 
 
-Filename: pyBigKinds-1.1.1.dist-info/top_level.txt
+Filename: pyBigKinds-1.2.0.dist-info/top_level.txt
 Comment: 
 
-Filename: pyBigKinds-1.1.1.dist-info/RECORD
+Filename: pyBigKinds-1.2.0.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## pyBigKinds/__init__.py

```diff
@@ -28,10 +28,11 @@
     "normalize_vector",
     "pca",
     "nmf",
     "t_sne",
     "lsa",
     "kmeans",
     "dbscan",
+    "meanshift",
     "lda",
     "association",
 ]
```

## pyBigKinds/_version.py

```diff
@@ -1 +1 @@
-__version__ = "1.1.1"
+__version__ = "1.2.0"
```

## pyBigKinds/base.py

```diff
@@ -1,16 +1,16 @@
 import pandas as pd
 
 
 def header_remover(df):
     """[]로 표시된 헤더 삭제"""
     if isinstance(df, pd.DataFrame):
-        ans = df["제목"].str.replace("\[[^)]*\]", "")
+        ans = df["제목"].str.replace(r"\[[^)]*\]", "", regex=True)
     elif isinstance(df, list):
-        ans = df.str.replace("\[[^)]*\]", "")
+        ans = df.str.replace(r"\[[^)]*\]", "", regex=True)
     else:
         raise TypeError("input value is to be have to list or DataFrame")
     return ans
 
 
 def keyword_list(df):
     """키워드를 list로 변환"""
```

## pyBigKinds/representation.py

```diff
@@ -1,15 +1,15 @@
 # pylint: disable=E1101
 
 import numpy as np
 import pandas as pd
 import tomotopy as tp
 from mlxtend.frequent_patterns import apriori, association_rules
 from mlxtend.preprocessing import TransactionEncoder
-from sklearn.cluster import DBSCAN, KMeans
+from sklearn.cluster import DBSCAN, KMeans, MeanShift, estimate_bandwidth
 from sklearn.decomposition import NMF, PCA, TruncatedSVD
 from sklearn.manifold import TSNE
 
 from .base import keyword_list, keyword_parser
 
 
 def day_range(df):
@@ -21,15 +21,15 @@
 
 
 def press_counter(df):
     """언론사 별 보도 빈도"""
     if isinstance(df, pd.DataFrame):
         freq = df["언론사"].value_counts()
         brod_df = pd.DataFrame(freq).reset_index()
-        brod_df.rename(columns={"index": "언론사", "언론사": "기사"}, inplace=True)
+        brod_df.rename(columns={"count": "기사"}, inplace=True)
         return brod_df
     else:
         raise TypeError("input type is to be have to DataFrame")
 
 
 def pca(vec, Random_State=123):
     """PCA"""
@@ -93,14 +93,27 @@
     if isinstance(vec, np.ndarray):
         dbscan_model = DBSCAN(eps=eps, min_samples=min_samples, metric=metric)
         return dbscan_model.fit_predict(vec)
     else:
         raise TypeError("input type is to be have to ndarray")
 
 
+def meanshift(vec, qt=0.25):
+    """Mean Shift"""
+    if isinstance(vec, np.ndarray):
+        best_bandwidth = estimate_bandwidth(vec, quantile=qt)
+        print(f'{qt}기준 최적 bandwidth 값:', round(best_bandwidth, 2))
+
+        ms_model = MeanShift(bandwidth=best_bandwidth)
+        print('cluster 갯수:', np.unique(ms_model.fit_predict(vec)))
+        return ms_model.fit_predict(vec)
+    else:
+        raise TypeError("input type is to be have to ndarray")
+
+
 def lda(dataframe, k=10, train=100, fit=10):
     """topic modeling"""
     if isinstance(dataframe, pd.DataFrame):
         lis = keyword_parser(keyword_list(dataframe))
         model = tp.LDAModel(k=k)
 
         for words in lis:
```

## Comparing `pyBigKinds-1.1.1.dist-info/LICENSE` & `pyBigKinds-1.2.0.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `pyBigKinds-1.1.1.dist-info/METADATA` & `pyBigKinds-1.2.0.dist-info/METADATA`

 * *Files 12% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 Metadata-Version: 2.1
 Name: pyBigKinds
-Version: 1.1.1
+Version: 1.2.0
 Summary: BigKinds Data Analysis Toolkit for python
 Home-page: https://github.com/sorrychoe/pyBigKinds
 Author: Sorrychoe
 License: MIT
 Project-URL: Source Code, https://github.com/sorrychoe/pyBigKinds
 Project-URL: Bug Tracker, https://github.com/sorrychoe/pyBigKinds/issues
 Keywords: Journalism,preprocessing-data,BigKinds
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 Requires-Dist: matplotlib (>=3.5.3)
-Requires-Dist: pandas (<2)
+Requires-Dist: pandas (>=1.5.3)
 Requires-Dist: wordcloud (>=1.8.2.2)
 Requires-Dist: scikit-learn (>=1.0.0)
 Requires-Dist: tomotopy (>=0.12.4)
 Requires-Dist: openpyxl (>=3.1.2)
 Requires-Dist: mlxtend (>=0.22.0)
 Provides-Extra: dev
 Requires-Dist: flake8 (>=3.9) ; extra == 'dev'
```

## Comparing `pyBigKinds-1.1.1.dist-info/RECORD` & `pyBigKinds-1.2.0.dist-info/RECORD`

 * *Files 23% similar despite different names*

```diff
@@ -1,11 +1,11 @@
-pyBigKinds/__init__.py,sha256=3Trd45Kpi8CK1BvxsOR1d2Kf9v_wN3qdZLuVADyUwU4,783
-pyBigKinds/_version.py,sha256=q8_5C0f-8mHWNb6mMw02zlYPnEGXBqvOmP3z0CEwZKM,22
-pyBigKinds/base.py,sha256=KrKO3O1wpXvWr8TVq-3hl2JwwWu4l3lLBtpuXUyv1mg,2475
+pyBigKinds/__init__.py,sha256=5FLLK2UOW_tQyRVSBPnxf-ldwHQap704IJaPkoncBAM,800
+pyBigKinds/_version.py,sha256=MpAT5hgNoHnTtG1XRD_GV_A7QrHVU6vJjGSw_8qMGA4,22
+pyBigKinds/base.py,sha256=oTV3tnweRdjpUOhbRFXMHiTnIi2NiaedZ1mkrh7rJEU,2501
 pyBigKinds/preprocessing.py,sha256=4blorjI5OFdg99mgioKLnybbD_xlyjLctCIAx1Ut15U,2552
-pyBigKinds/representation.py,sha256=uFqybooPWrrHvKTy6rcjrKbuvb3ay3_pTv9ajZvdH1g,4080
+pyBigKinds/representation.py,sha256=iBthP94Mvw0O7j5m2Hkt-sl8DCedODonz-qR-JKhq-4,4566
 pyBigKinds/visualization.py,sha256=oSuvR2x64tSm6I11C-FG9z6WmAhUtz0KR4qTuvxXNWU,2386
-pyBigKinds-1.1.1.dist-info/LICENSE,sha256=4qpntoObC47xSDR5kl1lMvxC4Hz6PuFVKIthT3E3j8Y,1070
-pyBigKinds-1.1.1.dist-info/METADATA,sha256=jokaHRzrXRaW3T_2FEpSLAoGdCoLp1oXBg-KnpzPjPA,1521
-pyBigKinds-1.1.1.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
-pyBigKinds-1.1.1.dist-info/top_level.txt,sha256=LDFcWpfU5Sf0n08ITRMJP20n-2u9ckNkEErPtU8iYbg,11
-pyBigKinds-1.1.1.dist-info/RECORD,,
+pyBigKinds-1.2.0.dist-info/LICENSE,sha256=4qpntoObC47xSDR5kl1lMvxC4Hz6PuFVKIthT3E3j8Y,1070
+pyBigKinds-1.2.0.dist-info/METADATA,sha256=I6TfvR08qP1yWv_u1TLIo4-9EHsTwZCAPkzaSK66L64,1526
+pyBigKinds-1.2.0.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
+pyBigKinds-1.2.0.dist-info/top_level.txt,sha256=LDFcWpfU5Sf0n08ITRMJP20n-2u9ckNkEErPtU8iYbg,11
+pyBigKinds-1.2.0.dist-info/RECORD,,
```


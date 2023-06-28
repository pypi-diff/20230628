# Comparing `tmp/event2vec-0.0.41.tar.gz` & `tmp/event2vec-0.0.42.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "event2vec-0.0.41.tar", max compression
+gzip compressed data, was "event2vec-0.0.42.tar", max compression
```

## Comparing `event2vec-0.0.41.tar` & `event2vec-0.0.42.tar`

### file list

```diff
@@ -1,18 +1,18 @@
--rw-r--r--   0        0        0    15731 2023-03-14 22:29:01.448203 event2vec-0.0.41/LICENSE
--rw-r--r--   0        0        0      762 2023-03-14 22:29:01.448203 event2vec-0.0.41/README.md
--rw-r--r--   0        0        0      242 2023-03-14 22:29:01.448203 event2vec-0.0.41/bin/config.cfg
--rw-r--r--   0        0        0     5993 2023-04-21 19:43:26.765843 event2vec-0.0.41/bin/submit_i2b2.py
--rw-r--r--   0        0        0     5384 2023-04-21 19:43:24.325844 event2vec-0.0.41/bin/submit_omop.py
--rw-r--r--   0        0        0       17 2023-03-14 22:29:01.778203 event2vec-0.0.41/event2vec/__init__.py
--rw-r--r--   0        0        0     1148 2023-03-14 22:29:01.778203 event2vec-0.0.41/event2vec/concept_proximity.py
--rw-r--r--   0        0        0     1411 2023-05-25 16:23:01.245183 event2vec-0.0.41/event2vec/config.py
--rw-r--r--   0        0        0     5203 2023-05-31 16:16:31.163153 event2vec-0.0.41/event2vec/cooccurrence_matrix_pandas.py
--rw-r--r--   0        0        0     5296 2023-06-19 14:43:33.718449 event2vec-0.0.41/event2vec/cooccurrence_matrix_polars.py
--rw-r--r--   0        0        0     7099 2023-04-22 02:17:00.822933 event2vec-0.0.41/event2vec/cooccurrence_matrix_spark.py
--rw-r--r--   0        0        0     1848 2023-06-19 15:48:12.938080 event2vec-0.0.41/event2vec/datasets.py
--rw-r--r--   0        0        0    15608 2023-06-19 15:50:02.368083 event2vec-0.0.41/event2vec/event_transformer.py
--rw-r--r--   0        0        0     6425 2023-03-14 22:29:01.778203 event2vec-0.0.41/event2vec/nomenclatures.py
--rw-r--r--   0        0        0     6867 2023-05-25 20:21:37.250039 event2vec-0.0.41/event2vec/svd_ppmi.py
--rw-r--r--   0        0        0     4315 2023-06-19 15:42:20.098117 event2vec-0.0.41/event2vec/utils.py
--rw-r--r--   0        0        0     4622 2023-06-19 15:50:38.108078 event2vec-0.0.41/pyproject.toml
--rw-r--r--   0        0        0     2954 1970-01-01 00:00:00.000000 event2vec-0.0.41/PKG-INFO
+-rw-r--r--   0        0        0    15731 2023-03-14 22:29:01.448203 event2vec-0.0.42/LICENSE
+-rw-r--r--   0        0        0      762 2023-03-14 22:29:01.448203 event2vec-0.0.42/README.md
+-rw-r--r--   0        0        0      242 2023-03-14 22:29:01.448203 event2vec-0.0.42/bin/config.cfg
+-rw-r--r--   0        0        0     5993 2023-04-21 19:43:26.765843 event2vec-0.0.42/bin/submit_i2b2.py
+-rw-r--r--   0        0        0     5384 2023-04-21 19:43:24.325844 event2vec-0.0.42/bin/submit_omop.py
+-rw-r--r--   0        0        0       17 2023-03-14 22:29:01.778203 event2vec-0.0.42/event2vec/__init__.py
+-rw-r--r--   0        0        0     1148 2023-03-14 22:29:01.778203 event2vec-0.0.42/event2vec/concept_proximity.py
+-rw-r--r--   0        0        0     1411 2023-05-25 16:23:01.245183 event2vec-0.0.42/event2vec/config.py
+-rw-r--r--   0        0        0     5203 2023-05-31 16:16:31.163153 event2vec-0.0.42/event2vec/cooccurrence_matrix_pandas.py
+-rw-r--r--   0        0        0     5296 2023-06-19 14:43:33.718449 event2vec-0.0.42/event2vec/cooccurrence_matrix_polars.py
+-rw-r--r--   0        0        0     7099 2023-04-22 02:17:00.822933 event2vec-0.0.42/event2vec/cooccurrence_matrix_spark.py
+-rw-r--r--   0        0        0     1848 2023-06-28 13:20:35.514368 event2vec-0.0.42/event2vec/datasets.py
+-rw-r--r--   0        0        0    16413 2023-06-28 15:04:48.774277 event2vec-0.0.42/event2vec/event_transformer.py
+-rw-r--r--   0        0        0     6425 2023-03-14 22:29:01.778203 event2vec-0.0.42/event2vec/nomenclatures.py
+-rw-r--r--   0        0        0     6867 2023-05-25 20:21:37.250039 event2vec-0.0.42/event2vec/svd_ppmi.py
+-rw-r--r--   0        0        0     4315 2023-06-28 13:20:35.514368 event2vec-0.0.42/event2vec/utils.py
+-rw-r--r--   0        0        0     4622 2023-06-28 15:05:46.014282 event2vec-0.0.42/pyproject.toml
+-rw-r--r--   0        0        0     2954 1970-01-01 00:00:00.000000 event2vec-0.0.42/PKG-INFO
```

### Comparing `event2vec-0.0.41/LICENSE` & `event2vec-0.0.42/LICENSE`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/README.md` & `event2vec-0.0.42/README.md`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/bin/submit_i2b2.py` & `event2vec-0.0.42/bin/submit_i2b2.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/bin/submit_omop.py` & `event2vec-0.0.42/bin/submit_omop.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/concept_proximity.py` & `event2vec-0.0.42/event2vec/concept_proximity.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/config.py` & `event2vec-0.0.42/event2vec/config.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/cooccurrence_matrix_pandas.py` & `event2vec-0.0.42/event2vec/cooccurrence_matrix_pandas.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/cooccurrence_matrix_polars.py` & `event2vec-0.0.42/event2vec/cooccurrence_matrix_polars.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/cooccurrence_matrix_spark.py` & `event2vec-0.0.42/event2vec/cooccurrence_matrix_spark.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/datasets.py` & `event2vec-0.0.42/event2vec/datasets.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/event_transformer.py` & `event2vec-0.0.42/event2vec/event_transformer.py`

 * *Files 7% similar despite different names*

```diff
@@ -65,35 +65,40 @@
     From a event table, create a vocabulary at fit, and pivot the data for a
     count one-hot encoding, ie. count for each code in the vocabulary, and for
     each patient if the event is present or not.
     """
 
     def __init__(
         self,
-        event: pd.DataFrame,
+        event: DataFrameType,
         n_min_events: int = 10,
         colname_demographics: List[str] = None,
         decay_half_life_in_days: np.array = np.array([0]),
         vocabulary: List[str] = None,
     ) -> None:
-        self.event = event
         self.vocabulary = vocabulary
         self.n_min_events = n_min_events
         self.colname_demographics = colname_demographics
         self.decay_half_life_in_days = decay_half_life_in_days
+        if isinstance(event, pd.DataFrame):
+            self.dataframe_type = pl.DataFrame
+            self.event = to_polars(event)
+        else:
+            self.dataframe_type = type(event)
+            self.event = event
 
     def fit(
         self,
         X: pd.DataFrame,
         y: pd.DataFrame = None,
     ):
-        if isinstance(self.event, pd.DataFrame):
-            self.event = to_polars(self.event)
+        # force types
+        X_typed = to(X, self.dataframe_type)
         X_event = self.event.join(
-            to_polars(X[[COLNAME_PERSON]]), on=COLNAME_PERSON, how="inner"
+            X_typed.select([COLNAME_PERSON]), on=COLNAME_PERSON, how="inner"
         )
 
         if check_colnames_subset(
             colnames_subset=self.colname_demographics, colnames=X.columns
         ):
             self.colname_demographics_ = self.colname_demographics
         else:
@@ -106,35 +111,38 @@
                 n_min_events=self.n_min_events,
             )
         else:
             self.vocabulary_ = self.vocabulary
         return self
 
     def transform(self, X: pd.DataFrame) -> np.array:
-        X_ = X.reset_index(drop=True)
+        X_typed = to(X.reset_index(drop=True), self.dataframe_type)
+
         X_event = self.event.join(
-            to_polars(X_[[COLNAME_PERSON]]), on=COLNAME_PERSON, how="inner"
+            X_typed.select([COLNAME_PERSON]), on=COLNAME_PERSON, how="inner"
         )
         X_counts = make_counts_pl(
             event=X_event,
-            person_id=X_[[COLNAME_PERSON]],
+            person_id=X_typed.select([COLNAME_PERSON]),
             decay_half_life_in_days=self.decay_half_life_in_days,
             vocabulary=self.vocabulary_,
             sparse=True,
         ).toarray()
 
         X_columns = []
         for decay in self.decay_half_life_in_days:
             for code_ in self.vocabulary_:
                 X_columns.append(f"{code_}__decay_{decay}")
 
         X_df = pd.DataFrame(X_counts, columns=X_columns)
         if self.colname_demographics_ is not None:
-            X_df = pd.concat([X_[self.colname_demographics_], X_df], axis=1)
-
+            X_df = pd.concat(
+                [to_pandas(X_typed.select(self.colname_demographics_)), X_df],
+                axis=1,
+            )
         return X_df
 
 
 class Event2vecFeaturizer(EventTransformerMixin, BaseEstimator):
     """
     Transformer for the event2vec model.
     """
@@ -152,15 +160,20 @@
         d: int = 150,
         smoothing_factor: float = 0.75,
         k: int = 1,
         n_min_events: int = 10,
         vocabulary: List[str] = None,
         decay_half_life_in_days: np.array = np.array([0]),
     ) -> None:
-        self.event = event
+        if isinstance(event, pd.DataFrame):
+            self.dataframe_type = pl.DataFrame
+            self.event = to_polars(event)
+        else:
+            self.dataframe_type = type(event)
+            self.event = event
         self.output_dir = output_dir
         self.colname_code = colname_code
         self.window_orientation = window_orientation
         self.window_radius_in_days = window_radius_in_days
         self.matrix_type = matrix_type
         self.backend = backend
         self.d = d
@@ -172,18 +185,19 @@
         self.decay_half_life_in_days = decay_half_life_in_days
 
     def fit(
         self,
         X: pd.DataFrame,
         y: pd.DataFrame = None,
     ):
-        if isinstance(self.event, pd.DataFrame):
-            self.event = to_polars(self.event)
+        X_typed = to(X, self.dataframe_type)
         X_event = self.event.join(
-            to_polars(X[[COLNAME_PERSON]]), on=COLNAME_PERSON, how="inner"
+            to_polars(X_typed.select([COLNAME_PERSON])),
+            on=COLNAME_PERSON,
+            how="inner",
         )
         if check_colnames_subset(
             colnames_subset=self.colname_demographics, colnames=X.columns
         ):
             self.colname_demographics_ = self.colname_demographics
         else:
             raise ValueError(
@@ -219,22 +233,22 @@
         # order the columns to correspond to the vocabulary.
         self.embedding_ = embedding[self.vocabulary_]
         return self
 
     def transform(self, X: pd.DataFrame) -> np.array:
         # passing the person ids is necessary to aligne make_counts aggregated
         # rows with the person ids in y.
-        X_ = X.reset_index(drop=True)
+        X_typed = to(X.reset_index(drop=True), self.dataframe_type)
 
         X_event = self.event.join(
-            to_polars(X_[[COLNAME_PERSON]]), on=COLNAME_PERSON, how="inner"
+            X_typed.select([COLNAME_PERSON]), on=COLNAME_PERSON, how="inner"
         )
         X_counts = make_counts_pl(
             event=X_event,
-            person_id=X_[[COLNAME_PERSON]],
+            person_id=X_typed.select([COLNAME_PERSON]),
             decay_half_life_in_days=self.decay_half_life_in_days,
             vocabulary=self.vocabulary_,
             sparse=True,
         )
         embedding_array_ = sp.csr_matrix(
             self.embedding_[self.vocabulary_].values
         )
@@ -250,15 +264,19 @@
         embedding_dimension = embedding_array_.shape[0]
         for decay_ in self.decay_half_life_in_days:
             for i in range(embedding_dimension):
                 X_embedded_columns.append(f"dim_{i}__decay_{decay_}")
         X_embedded_df = pd.DataFrame(X_embedded, columns=X_embedded_columns)
         if self.colname_demographics_ is not None:
             X_embedded_df = pd.concat(
-                [X_[self.colname_demographics_], X_embedded_df], axis=1
+                [
+                    to_pandas(X_typed.select(self.colname_demographics_)),
+                    X_embedded_df,
+                ],
+                axis=1,
             )
         return X_embedded_df
 
 
 class Event2vecPretrained(Event2vecFeaturizer):
     def __init__(
         self,
@@ -266,15 +284,20 @@
         embeddings: Union[str, Path, pd.DataFrame],
         colname_demographics: str = None,
         colname_code: str = COLNAME_SOURCE_CODE,
         n_min_events: int = 10,
         decay_half_life_in_days: np.array = np.array([0]),
         vocabulary: List[str] = None,
     ) -> None:
-        self.event = event
+        if isinstance(event, pd.DataFrame):
+            self.dataframe_type = pl.DataFrame
+            self.event = to_polars(event)
+        else:
+            self.dataframe_type = type(event)
+            self.event = event
         self.colname_code = colname_code
         self.n_min_events = n_min_events
         self.colname_demographics = colname_demographics
         self.vocabulary = vocabulary
         self.decay_half_life_in_days = decay_half_life_in_days
         if isinstance(embeddings, str) | isinstance(embeddings, Path):
             self.embeddings = pd.read_parquet(embeddings)
@@ -282,18 +305,20 @@
             self.embeddings = embeddings
 
     def fit(
         self,
         X: pd.DataFrame,
         y: pd.DataFrame = None,
     ):
-        if isinstance(self.event, pd.DataFrame):
-            self.event = to_polars(self.event)
+        # force types
+        X_typed = to(X, self.dataframe_type)
         X_event = self.event.join(
-            to_polars(X[[COLNAME_PERSON]]), on=COLNAME_PERSON, how="inner"
+            X_typed.select([COLNAME_PERSON]),
+            on=COLNAME_PERSON,
+            how="inner",
         )
         if check_colnames_subset(
             colnames_subset=self.colname_demographics, colnames=X.columns
         ):
             self.colname_demographics_ = self.colname_demographics
         else:
             raise ValueError(
```

### Comparing `event2vec-0.0.41/event2vec/nomenclatures.py` & `event2vec-0.0.42/event2vec/nomenclatures.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/svd_ppmi.py` & `event2vec-0.0.42/event2vec/svd_ppmi.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/event2vec/utils.py` & `event2vec-0.0.42/event2vec/utils.py`

 * *Files identical despite different names*

### Comparing `event2vec-0.0.41/pyproject.toml` & `event2vec-0.0.42/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "event2vec"
-version = "0.0.41"
+version = "0.0.42"
 description = "event2vec"
 authors = ["Matthieu Doutreligne <matt.dout@gmail.com>"]
 license = "EUPL-v1.2"
 readme = "README.md"
 repository = "https://gitlab.com/strayMat/event2vec"
 homepage = "https://gitlab.com/strayMat/event2vec"
 include = ["bin"]
```

### Comparing `event2vec-0.0.41/PKG-INFO` & `event2vec-0.0.42/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: event2vec
-Version: 0.0.41
+Version: 0.0.42
 Summary: event2vec
 Home-page: https://gitlab.com/strayMat/event2vec
 License: EUPL-v1.2
 Author: Matthieu Doutreligne
 Author-email: matt.dout@gmail.com
 Requires-Python: >=3.7.1,<3.11
 Classifier: Intended Audience :: Developers
```


# Comparing `tmp/aequilibrium-1.0.0.tar.gz` & `tmp/aequilibrium-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "aequilibrium-1.0.0.tar", max compression
+gzip compressed data, was "aequilibrium-1.0.1.tar", max compression
```

## Comparing `aequilibrium-1.0.0.tar` & `aequilibrium-1.0.1.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0    10349 2023-04-11 20:54:03.040856 aequilibrium-1.0.0/LICENSE
--rw-r--r--   0        0        0      757 2023-04-11 20:54:03.050042 aequilibrium-1.0.0/aequilibrium/__init__.py
--rw-r--r--   0        0        0     6823 2023-04-11 20:54:03.054409 aequilibrium-1.0.0/aequilibrium/balance.py
--rw-r--r--   0        0        0     4767 2023-04-11 20:54:03.058472 aequilibrium-1.0.0/aequilibrium/dataset.py
--rw-r--r--   0        0        0     4033 2023-04-11 20:54:03.062211 aequilibrium-1.0.0/aequilibrium/model.py
--rw-r--r--   0        0        0     8157 2023-04-20 19:32:57.572521 aequilibrium-1.0.0/aequilibrium/results.py
--rw-r--r--   0        0        0     1263 2023-04-11 20:54:03.070083 aequilibrium-1.0.0/aequilibrium/utils/__init__.py
--rw-r--r--   0        0        0    10689 2023-04-11 20:54:03.074095 aequilibrium-1.0.0/aequilibrium/utils/api_wrapper.py
--rw-r--r--   0        0        0     7270 2023-04-20 19:32:57.591211 aequilibrium-1.0.0/aequilibrium/visualize.py
--rw-r--r--   0        0        0     1553 2023-04-11 20:54:03.303390 aequilibrium-1.0.0/pyproject.toml
--rw-r--r--   0        0        0      845 2023-04-20 19:46:41.498650 aequilibrium-1.0.0/setup.py
--rw-r--r--   0        0        0      663 2023-04-20 19:46:41.499113 aequilibrium-1.0.0/PKG-INFO
+-rw-r--r--   0        0        0    10349 2023-04-11 20:54:03.040856 aequilibrium-1.0.1/LICENSE
+-rw-r--r--   0        0        0      757 2023-04-11 20:54:03.050042 aequilibrium-1.0.1/aequilibrium/__init__.py
+-rw-r--r--   0        0        0     6823 2023-04-11 20:54:03.054409 aequilibrium-1.0.1/aequilibrium/balance.py
+-rw-r--r--   0        0        0     4767 2023-04-11 20:54:03.058472 aequilibrium-1.0.1/aequilibrium/dataset.py
+-rw-r--r--   0        0        0     4033 2023-04-11 20:54:03.062211 aequilibrium-1.0.1/aequilibrium/model.py
+-rw-r--r--   0        0        0     9060 2023-06-27 13:50:54.423071 aequilibrium-1.0.1/aequilibrium/results.py
+-rw-r--r--   0        0        0     1263 2023-04-11 20:54:03.070083 aequilibrium-1.0.1/aequilibrium/utils/__init__.py
+-rw-r--r--   0        0        0    10689 2023-04-11 20:54:03.074095 aequilibrium-1.0.1/aequilibrium/utils/api_wrapper.py
+-rw-r--r--   0        0        0     7819 2023-06-27 13:50:54.427111 aequilibrium-1.0.1/aequilibrium/visualize.py
+-rw-r--r--   0        0        0     1544 2023-06-27 13:52:58.361467 aequilibrium-1.0.1/pyproject.toml
+-rw-r--r--   0        0        0      836 2023-06-27 13:54:51.697927 aequilibrium-1.0.1/setup.py
+-rw-r--r--   0        0        0      645 2023-06-27 13:54:51.698554 aequilibrium-1.0.1/PKG-INFO
```

### Comparing `aequilibrium-1.0.0/LICENSE` & `aequilibrium-1.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/__init__.py` & `aequilibrium-1.0.1/aequilibrium/__init__.py`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/balance.py` & `aequilibrium-1.0.1/aequilibrium/balance.py`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/dataset.py` & `aequilibrium-1.0.1/aequilibrium/dataset.py`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/model.py` & `aequilibrium-1.0.1/aequilibrium/model.py`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/results.py` & `aequilibrium-1.0.1/aequilibrium/results.py`

 * *Files 10% similar despite different names*

```diff
@@ -30,20 +30,18 @@
     def __init__(
         self,
         actuals: pd.Series,
         predictions: pd.Series,
         probabilities: pd.Series,
     ):
         """Helper class to manage and evaluate model output
-
         Args:
             actuals (pd.Series): The actual observed response variable
             predictions (pd.Series): The predicted response variable
             probabilities (pd.Series): The probability of the positive class
-
         Returns:
             None
         """
         self.actuals = actuals
         self.predictions = predictions
         self.probabilities = probabilities
 
@@ -136,33 +134,30 @@
         precision, recall, thresholds = precision_recall_curve(
             self.actuals, self.probabilities
         )
         return auc(recall, precision)
 
     def get_confusion_matrix(self) -> pd.DataFrame:
         """Get the confusion matrix for this model results
-
         Returns:
             pd.DataFrame: Confusion matrix
         """
 
         confusion_matrix_data = pd.DataFrame(
             confusion_matrix(self.actuals, self.predictions)
         )
         confusion_matrix_data.columns = ["Neg", "Pos"]
         confusion_matrix_data.index = ["Neg", "Pos"]
 
         return confusion_matrix_data
 
     def get_summary_table(self, num_bins: int = 5) -> pd.DataFrame:
         """Replacement for enrichment table function
-
         Args:
             num_bins (int): _description_. Defaults to 5.
-
         Returns:
             pd.DataFrame: _description_
         """
         # Organize original results
         original_results = pd.DataFrame(self.to_dict())
 
         # Partition the results based on predicted probabilities
@@ -189,15 +184,14 @@
         return results.sort_index()
 
     def build_enrich_table(
         self,
         num_decimals: int = 2,
     ) -> pd.DataFrame:
         """Creates enrichment table to be returned and used in lift and gain functions
-
         Returns:
             pd.DataFrame of enrichment table
         """
         metrics = (
             pd.DataFrame(self.to_dict())
             .sort_values(by="probabilities", ascending=False)
             .reset_index()
@@ -205,37 +199,61 @@
         num_rows = metrics.shape[0]
         metrics["percentile"] = (
             pd.Series(range(num_rows)).divide(num_rows).round(num_decimals)
         )
 
         enrich_df = (
             metrics.groupby("percentile")
-            .agg({"probabilities": ["min", "max"], "index": "count", "actuals": "sum"})
+            .agg(
+                {
+                    "probabilities": ["min", "max", "mean"],
+                    "index": "count",
+                    "actuals": "sum",
+                }
+            )
             .reset_index()
         )
         enrich_df.columns = [
             "percentile",
             "min_y_proba",
             "max_y_proba",
-            "row_count",
-            "pos_count",
+            "mean_y_proba",
+            "percentile_row_count",
+            "percentile_pos_count",
         ]
 
-        total_events = enrich_df["pos_count"].sum()
-        enrich_df["perc_random_events"] = (1 / len(enrich_df["percentile"])) * 100
+        total_events = enrich_df["percentile_pos_count"].sum()
+        enrich_df["percentile_perc_random_events"] = (
+            1 / len(enrich_df["percentile"])
+        ) * 100
         # enrich_df[["row_count", "pos_count", "perc_random_events"]] = pd.DataFrame.cumsum(enrich_df)[["row_count", "pos_count", "perc_random_events"]]
+
+        # Metrics with prefix "percentile" are metrics are calculated non-cumulative. row_count, pos_count, and perc_random_events are cumulative
         enrich_df[["row_count", "pos_count", "perc_random_events"]] = enrich_df[
-            ["row_count", "pos_count", "perc_random_events"]
+            [
+                "percentile_row_count",
+                "percentile_pos_count",
+                "percentile_perc_random_events",
+            ]
         ].cumsum()
 
         enrich_df = enrich_df.assign(
             perc_actual_events=(enrich_df["pos_count"] / total_events) * 100,
+            percentile_perc_actual_events=(
+                enrich_df["percentile_pos_count"] / total_events
+            )
+            * 100,
+            percent_of_population_x_100=(enrich_df["percentile_row_count"] / num_rows)
+            * 100,
             percentile_x_100=enrich_df["percentile"] * 100,
             Random_Lift=1,
             precision=enrich_df["pos_count"] / enrich_df["row_count"],
         )
 
         return enrich_df.assign(
             Model_Lift=enrich_df["perc_actual_events"]
             / enrich_df["perc_random_events"],
+            Percentile_Model_Lift=enrich_df["percentile_perc_actual_events"]
+            / enrich_df["percent_of_population_x_100"],
             recall=enrich_df["perc_actual_events"],
+            percentile_recall=enrich_df["percentile_perc_actual_events"],
         )
```

### Comparing `aequilibrium-1.0.0/aequilibrium/utils/__init__.py` & `aequilibrium-1.0.1/aequilibrium/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/utils/api_wrapper.py` & `aequilibrium-1.0.1/aequilibrium/utils/api_wrapper.py`

 * *Files identical despite different names*

### Comparing `aequilibrium-1.0.0/aequilibrium/visualize.py` & `aequilibrium-1.0.1/aequilibrium/visualize.py`

 * *Files 4% similar despite different names*

```diff
@@ -27,19 +27,17 @@
 class Visualize:
     def __init__(
         self,
         results: Results,
         num_decimals: int = 2,
     ):
         """My class description
-
         Args:
             results (Results): An aequilibrium Results instance
             num_decimals (int): Desired rounding for floats
-
         Returns:
             None
         """
         self.results = results
 
         self.num_decimals = num_decimals
         self.metric_summary = self.results.build_enrich_table(
@@ -48,19 +46,17 @@
 
     def plot_pr_curve(
         self,
         display: bool = True,
         save_file_name: Optional[str] = None,
     ) -> None:
         """Displays a precision recall curve of the given results of a model
-
         Args:
             display (bool): True displays PR Curve
             save_file_name (str): Filename to save plot to file
-
         Returns:
             TODO
         """
         # Data to plot precision - recall curve
         precision, recall, _ = precision_recall_curve(
             self.results.actuals, self.results.probabilities
         )
@@ -80,19 +76,17 @@
 
     def plot_confusion_matrix(
         self,
         display: bool = True,
         save_file_name: Optional[str] = None,
     ) -> None:
         """Function that displays a heatmap of a confusion matrix.
-
         Args:
             display (bool): True displays PR Curve
             save_file_name (str): Filename to save plot to file
-
         Returns:
             None
         """
         confusion_matrix_data = self.results.get_confusion_matrix()
 
         sb.heatmap(confusion_matrix_data, annot=True, fmt="g", cmap="viridis")
         plt.title("Confusion Matrix", fontsize=28, fontweight="bold")
@@ -107,19 +101,17 @@
 
     def plot_gain_chart(
         self,
         display: bool = True,
         save_file_name: Optional[str] = None,
     ) -> None:
         """Displays a gain chart of the given results of a model
-
         Args:
             display (bool): True displays gain chart
             save_file_name (str): Filename to save plot to file
-
         Returns:
             None
         """
 
         enrich_table = self.metric_summary
 
         dict = {}
@@ -163,50 +155,59 @@
             plt.savefig(save_file_name)
 
         if display:
             plt.show()
 
     def plot_lift_chart(
         self,
+        cumulative: bool = True,
         display: bool = True,
         save_file_name: Optional[str] = None,
     ) -> None:
         """Displays a lift chart of the given results of a model
-
         Args:
+            cumulative (bool): True displays cumulative lift chart, False displays non-cumulative, percentile-wise
+                lift chart
             display (bool): True displays gain chart
             save_file_name (str): Filename to save plot to file
-
         Returns:
             None
         """
+        if cumulative == True:
+            y_name: str = "Model_Lift"
+            chart_title_prefix: str = "Cumulative"
+        elif cumulative == False:
+            y_name: str = "Percentile_Model_Lift"
+            chart_title_prefix: str = "Non-Cumulative, Percentile-Wise"
+        else:
+            raise ValueError("cumulative parameter only supports bool types.")
 
         enrich_table = self.metric_summary
         sb.lineplot(
             x="percentile_x_100",
             y="Random_Lift",
             data=enrich_table,
             dashes=False,
             color="red",
             marker="o",
             label="Random_Lift",
             sort=False,
         )
         sb.lineplot(
             x="percentile_x_100",
-            y="Model_Lift",
+            y=y_name,
             data=enrich_table,
             dashes=False,
             color="blue",
             marker="o",
             label="Model_Lift",
             sort=False,
         )
 
-        plt.title("Lift Chart", fontsize=32, fontweight="bold")
+        plt.title(f"{chart_title_prefix} Lift Chart", fontsize=32, fontweight="bold")
         plt.xlabel("Percent Group", fontsize=22)
         plt.ylabel("Lift", fontsize=22)
         plt.grid(axis="x", color="0.95")
         plt.grid(axis="y", color="0.95")
         plt.xticks(np.arange(0, 100, step=5))
 
         if save_file_name:
@@ -217,19 +218,17 @@
 
     def complete_evaluation(
         self,
         display: bool = True,
         save_dir: Optional[str] = False,
     ) -> pd.DataFrame:
         """Creates evaluation metrics from results dataframe
-
         Args:
             display (bool): True displays gain chart
             save_dir (str): File directory to save plots
-
         Returns:
             Enrichment dataframe
         """
 
         if save_dir:
             if not os.path.exists(save_dir):
                 os.makedirs(save_dir)
```

### Comparing `aequilibrium-1.0.0/pyproject.toml` & `aequilibrium-1.0.1/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,24 +1,24 @@
 [tool.poetry]
 name = "aequilibrium"
-version = "1.0.0"
+version = "1.0.1"
 description = "Python package for classification of imbalanced data."
 authors = ["Luke Beasley <beasleyl2@aetna.com>",
     "Lin Han <hanl1@aetna.com>",
     "Matthew Trudeau <trudeaum@aetna.com>",
     "Alex Xu <alex.xu2@cvshealth.com>",
     "Jason Dwyer <DwyerJ1@aetna.com>",]
 maintainers = [
     "Luke Beasley <beasleyl2@aetna.com>",
     "Lin Han <hanl1@aetna.com>",
     "Matthew Trudeau <trudeaum@aetna.com>",
     "Alex Xu <alex.xu2@cvshealth.com>",
     "Jason Dwyer <DwyerJ1@aetna.com>",
 ]
-repository = "https://github.aetna.com/analytics-org/aequilibrium"
+repository = "https://github.com/cvs-health/aequilibrium"
 
 [tool.poetry.dependencies]
 python = ">=3.7.1,<3.8"
 numpy = "^1.21"
 pandas = "^1.3"
 imbalanced-learn = "<0.9"
 scikit-learn = "<1.1"
```

### Comparing `aequilibrium-1.0.0/setup.py` & `aequilibrium-1.0.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -13,22 +13,22 @@
  'numpy>=1.21,<2.0',
  'pandas>=1.3,<2.0',
  'scikit-learn<1.1',
  'seaborn<0.12']
 
 setup_kwargs = {
     'name': 'aequilibrium',
-    'version': '1.0.0',
+    'version': '1.0.1',
     'description': 'Python package for classification of imbalanced data.',
     'long_description': None,
     'author': 'Luke Beasley',
     'author_email': 'beasleyl2@aetna.com',
     'maintainer': 'Luke Beasley',
     'maintainer_email': 'beasleyl2@aetna.com',
-    'url': 'https://github.aetna.com/analytics-org/aequilibrium',
+    'url': 'https://github.com/cvs-health/aequilibrium',
     'packages': packages,
     'package_data': package_data,
     'install_requires': install_requires,
     'python_requires': '>=3.7.1,<3.8',
 }
```

### Comparing `aequilibrium-1.0.0/PKG-INFO` & `aequilibrium-1.0.1/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 Metadata-Version: 2.1
 Name: aequilibrium
-Version: 1.0.0
+Version: 1.0.1
 Summary: Python package for classification of imbalanced data.
-Home-page: https://github.aetna.com/analytics-org/aequilibrium
+Home-page: https://github.com/cvs-health/aequilibrium
 Author: Luke Beasley
 Author-email: beasleyl2@aetna.com
 Maintainer: Luke Beasley
 Maintainer-email: beasleyl2@aetna.com
 Requires-Python: >=3.7.1,<3.8
 Classifier: Programming Language :: Python :: 3
 Requires-Dist: imbalanced-learn (<0.9)
 Requires-Dist: matplotlib (<3.6)
 Requires-Dist: numpy (>=1.21,<2.0)
 Requires-Dist: pandas (>=1.3,<2.0)
 Requires-Dist: scikit-learn (<1.1)
 Requires-Dist: seaborn (<0.12)
-Project-URL: Repository, https://github.aetna.com/analytics-org/aequilibrium
+Project-URL: Repository, https://github.com/cvs-health/aequilibrium
```


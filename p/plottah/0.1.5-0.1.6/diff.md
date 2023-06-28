# Comparing `tmp/plottah-0.1.5.tar.gz` & `tmp/plottah-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "plottah-0.1.5.tar", max compression
+gzip compressed data, was "plottah-0.1.6.tar", max compression
```

## Comparing `plottah-0.1.5.tar` & `plottah-0.1.6.tar`

### file list

```diff
@@ -1,18 +1,17 @@
--rw-r--r--   0        0        0      835 2023-06-26 14:13:16.672074 plottah-0.1.5/README.md
--rw-r--r--   0        0        0       22 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/__init__.py
--rw-r--r--   0        0        0     1012 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/__main__.py
--rw-r--r--   0        0        0     1339 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/colors.py
--rw-r--r--   0        0        0     3124 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/config.py
--rw-r--r--   0        0        0      988 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/main.py
--rw-r--r--   0        0        0       24 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/plot_builder/__init__.py
--rw-r--r--   0        0        0     2684 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/plot_builder/builders.py
--rw-r--r--   0        0        0     7487 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/plot_handler/PlotHandler.py
--rw-r--r--   0        0        0       37 2023-06-26 14:13:18.148086 plottah-0.1.5/plottah/plot_handler/__init__.py
--rw-r--r--   0        0        0     7584 2023-06-26 14:13:18.152086 plottah-0.1.5/plottah/plots/BinEventRatePlot.py
--rw-r--r--   0        0        0     3987 2023-06-26 14:13:18.152086 plottah-0.1.5/plottah/plots/DistPlot.py
--rw-r--r--   0        0        0     1927 2023-06-26 14:13:18.152086 plottah-0.1.5/plottah/plots/PlotProtocol.py
--rw-r--r--   0        0        0     3578 2023-06-26 14:13:18.152086 plottah-0.1.5/plottah/plots/RocCurvePlot.py
--rw-r--r--   0        0        0      117 2023-06-26 14:13:18.152086 plottah-0.1.5/plottah/plots/__init__.py
--rw-r--r--   0        0        0     4200 2023-06-26 14:13:18.152086 plottah-0.1.5/plottah/utils.py
--rw-r--r--   0        0        0      505 2023-06-26 14:13:56.280349 plottah-0.1.5/pyproject.toml
--rw-r--r--   0        0        0     1824 1970-01-01 00:00:00.000000 plottah-0.1.5/PKG-INFO
+-rw-r--r--   0        0        0      835 2023-06-28 09:10:14.987435 plottah-0.1.6/README.md
+-rw-r--r--   0        0        0       22 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/__init__.py
+-rw-r--r--   0        0        0     1617 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/__main__.py
+-rw-r--r--   0        0        0     1339 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/colors.py
+-rw-r--r--   0        0        0     4266 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/config.py
+-rw-r--r--   0        0        0       24 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plot_builder/__init__.py
+-rw-r--r--   0        0        0     2884 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plot_builder/builders.py
+-rw-r--r--   0        0        0     7487 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plot_handler/PlotHandler.py
+-rw-r--r--   0        0        0       37 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plot_handler/__init__.py
+-rw-r--r--   0        0        0     9975 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plots/BinEventRatePlot.py
+-rw-r--r--   0        0        0     3987 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plots/DistPlot.py
+-rw-r--r--   0        0        0     1927 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plots/PlotProtocol.py
+-rw-r--r--   0        0        0     3578 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plots/RocCurvePlot.py
+-rw-r--r--   0        0        0      117 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/plots/__init__.py
+-rw-r--r--   0        0        0     4179 2023-06-28 09:10:16.003464 plottah-0.1.6/plottah/utils.py
+-rw-r--r--   0        0        0      505 2023-06-28 09:10:44.675516 plottah-0.1.6/pyproject.toml
+-rw-r--r--   0        0        0     1724 1970-01-01 00:00:00.000000 plottah-0.1.6/PKG-INFO
```

### Comparing `plottah-0.1.5/README.md` & `plottah-0.1.6/README.md`

 * *Files identical despite different names*

### Comparing `plottah-0.1.5/plottah/__main__.py` & `plottah-0.1.6/plottah/__main__.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,15 +1,20 @@
 from plottah.plot_builder import build_univariate_plots
 from plottah.config import settings
 from plottah.colors import PlotColors
 
 import pandas as pd
 
+import logging
+
 
 def main():
+    # set logging level
+    logging.basicConfig(level=logging.WARNING)
+
     # set color palette to use
     color_palette = PlotColors(
         primary_color=settings.primary_color,
         secondary_color=settings.secondary_color,
         tertiary_color=settings.tertiary_color,
         grey_tint_color=settings.grey_tint_color,
     )
@@ -21,19 +26,35 @@
     bins = {
         feature_schema.name: feature_schema.bins
         if feature_schema.bins is not None
         else None
         for feature_schema in settings.features
     }
 
+    # create mapping from feature name to number of bins
+    n_bins = {
+        feature_schema.name: feature_schema.n_bins
+        for feature_schema in settings.features
+    }
+
+    # create mapping from feature name to feature type
+    feature_types = {
+        feature_schema.name: feature_schema.type
+        if feature_schema.type is not None
+        else "float"
+        for feature_schema in settings.features
+    }
+
     build_univariate_plots(
-        pd.read_csv(settings.file_path),
-        features,
-        settings.target,
-        settings.output_path,
+        df=pd.read_csv(settings.file_path),
+        features=features,
+        target=settings.target,
+        feature_types=feature_types,
+        save_directory=settings.output_path,
         colors=color_palette,
         bins=bins,
+        n_bins=n_bins,
     )
 
 
 if __name__ == "__main__":
     main()
```

### Comparing `plottah-0.1.5/plottah/colors.py` & `plottah-0.1.6/plottah/colors.py`

 * *Files identical despite different names*

### Comparing `plottah-0.1.5/plottah/plot_builder/builders.py` & `plottah-0.1.6/plottah/plot_builder/builders.py`

 * *Files 20% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 from plottah.plots import DistPlot, RocCurvePlot, BinEventRatePlot
 
 
 def build_univariate_plot(
     df,
     feature_col: str,
     target: str,
+    feature_type: str = "float",
     colors: PlotColors = PlotColors(),
     show_plot: bool = True,
     hoverinfo="all",
     n_bins: int = 10,
     bins: list = None,
     specs: list = None,
 ):
@@ -24,43 +25,47 @@
 
     Returns
     """
 
     roc_plot = RocCurvePlot(hoverinfo=hoverinfo, colors=colors)
     dist_plot = DistPlot(hoverinfo=hoverinfo, colors=colors)
     event_plot = BinEventRatePlot(
-        hoverinfo=hoverinfo, colors=colors, n_bins=n_bins, bins=bins
+        hoverinfo=hoverinfo,
+        colors=colors,
+        n_bins=n_bins,
+        bins=bins,
+        feature_type=feature_type,
     )
 
     specs = (
         [[{}, {}], [{"colspan": 2, "secondary_y": True}, None]]
         if specs is None
         else specs
     )
 
     plot = PlotHandler(feature_col, target, specs)
-
     plot.build(df, feature_col, target, roc_plot, dist_plot, event_plot, show_fig=False)
 
     if show_plot:
         plot.show()
 
     return plot
 
 
 def build_univariate_plots(
     df,
     features: list,
     target: str,
+    feature_types: dict,
+    n_bins: dict = None,
+    bins: dict = None,
     save_directory: pathlib.Path() = None,
     colors: PlotColors = PlotColors(),
     show_plot: bool = False,
     hoverinfo="all",
-    n_bins: int = 10,
-    bins: dict = None,
 ) -> Dict[str, PlotHandler]:
     """
     function that generates standard univariate plots
 
     Args:
         df (pd.DataFrame): dataframe containing columns to analyze,
         features (list): list of columns,
@@ -82,21 +87,22 @@
     figs = {}
     for i, feature in enumerate(features):
         print(f"[{i+1}/{len(features)}] Starting univariate analysis for: {feature}")
         if feature not in df.columns:
             raise ValueError(f"{feature} not in columns of dataframe")
 
         fig = build_univariate_plot(
-            df,
-            feature,
-            target,
+            df=df,
+            feature_col=feature,
+            target=target,
+            feature_type=feature_types[feature],
             colors=colors,
             show_plot=show_plot,
             hoverinfo=hoverinfo,
-            n_bins=n_bins,
+            n_bins=n_bins[feature],
             bins=bins[feature],
         )
 
         if save_directory is not None:
             fig.save_fig(save_directory)
             print(f"[{i+1}/{len(features)}] Saving univariate anaylsis for {feature}")
```

### Comparing `plottah-0.1.5/plottah/plot_handler/PlotHandler.py` & `plottah-0.1.6/plottah/plot_handler/PlotHandler.py`

 * *Files identical despite different names*

### Comparing `plottah-0.1.5/plottah/plots/BinEventRatePlot.py` & `plottah-0.1.6/plottah/plots/BinEventRatePlot.py`

 * *Files 26% similar despite different names*

```diff
@@ -4,105 +4,111 @@
 import pandas as pd
 from dataclasses import dataclass, field
 
 from .PlotProtocol import PlotProtocol
 from plottah.colors import PlotColors
 from plottah.utils import get_bins, get_min_max_adj, get_labels_from_bins
 
+import logging
+
+MIN_N_UNIQUE = 25
+
 
 @dataclass
-class BinEventRatePlot(PlotProtocol):
-    # set the colorway
-    colors: PlotColors = field(default_factory=lambda: PlotColors())
+class CategoricalBinner:
+    _labels: list = field(default_factory=lambda: None)
 
-    # set (number of) bins
-    bins: list = field(default_factory=lambda: None)
-    n_bins: int = field(default_factory=lambda: 10)
+    def get_labels(self):
+        return self._labels.copy()
 
-    # set hover setting
-    hoverinfo: str = field(default_factory=lambda: "skip")
+    def add_bins(self, df: pd.DataFrame, feature_col: str) -> pd.DataFrame:
+        # Extract unique values
+        unique_vals = df[feature_col].sort_values().unique()
 
-    def do_math(
-        self,
-        df,
-        feature_col,
-        target_col,
-        fillna: bool = False,
-        method: str = "quantile",
-    ):
-        """
-        does the required math to generate the traces, annotations and axes for the roc-curve plot
+        # Convert sorted elements to int
+        # mapping = pd.factorize(unique_vals, na_sentinel=len(unique_vals))
+        mapping = pd.factorize(unique_vals, use_na_sentinel=False)
 
-        1. imputes/removes missing values
-        2. extract traces from the distplot function from plotly
-        3. get the max density and feature value after imputing
-        """
+        # Create mapping
+        mapping_values = list(mapping[0])
+        mapping_keys = list(mapping[1])
 
-        # set feature and target column names
-        self.feature_col = feature_col
-        self.target_col = target_col
+        # Create mapping dictionary
+        mapping_dict = dict(zip(mapping_keys, mapping_values))
 
-        # make fresh copy of df
-        self.df = df.copy()
+        # Apply mapping to column
+        df = df.assign(bins=df[feature_col].map(mapping_dict))
 
-        # Calculate global event rate
-        self.event_rate = np.mean(self.df[target_col])
+        # Set labels for plotting
+        self._labels = [str(key) for key in mapping_keys]
+        self._labels[-1] = "NA"
+
+        return df, self._labels
 
-        # Adjust n_bins if less unique values exist
-        self.n_bins = self.n_bins if self.bins is None else len(self.bins)
-        n_unique_feat_vals = df[feature_col].nunique()
-        self.n_bins = np.minimum(n_unique_feat_vals, self.n_bins)
 
+@dataclass
+class StandardBinner:
+    _labels: list = field(default_factory=lambda: None)
+
+    def get_labels(self):
+        return self._labels.copy()
+
+    def add_bins(
+        self,
+        df: pd.DataFrame,
+        feature_col: str,
+        n_bins: int,
+        bins=None,
+        method="quantile",
+    ) -> pd.DataFrame:
         # Get unadjusted min and max
-        min_val, max_val = get_min_max_adj(self.df, feature_col)
-        min_val_adj, max_val_adj = get_min_max_adj(self.df, feature_col)
+        min_val, max_val = get_min_max_adj(df, feature_col)
+        min_val_adj, max_val_adj = get_min_max_adj(df, feature_col)
 
         ## BINNING
-        self.bins = (
-            self.bins
-            if self.bins is not None
+        bins = (
+            bins
+            if bins is not None
             else get_bins(
-                self.df,
-                self.feature_col,
-                self.target_col,
+                df,
+                feature_col,
                 min_val_adj,
                 max_val_adj,
-                n_bins=self.n_bins,
+                n_bins=n_bins,
                 method=method,
             )
         )
-        print(self.bins)
+
         # convert type to list
-        self.bins = list(self.bins)
+        bins = list(bins)
 
         # set first and last value back to min and max before imputing
-        self.bins[0] = min_val
-        self.bins[self.n_bins - 1] = max_val
+        bins[0] = min_val
+        bins[n_bins - 1] = max_val
 
         # update number of bins
-        assert self.n_bins == len(self.bins)
+        assert n_bins == len(bins)
 
         # Create bins (return None if binning is not successfull)
         try:
             # create new column indicating what bin record belongs to
-            self.df = self.df.assign(
+            df = df.assign(
                 bins=pd.cut(
-                    x=self.df.loc[:, feature_col],
-                    bins=self.bins,
+                    x=df.loc[:, feature_col],
+                    bins=bins,
                     include_lowest=True,
                     right=True,
                     labels=False,
                 )
             )
         except Exception as e:
             raise ValueError("{self.feature_col} cannot be binned")
 
         # Create plot labels: [(4, 6), (6, 10), ...]
-        self.labels = get_labels_from_bins(self.bins)
-        print(self.labels)
+        self._labels = get_labels_from_bins(bins)
 
         ## CLIPPING
 
         # Clip values according to min/max values
         df[feature_col].clip(lower=min_val, upper=max_val, inplace=True)
 
         # Ensure clipping values does not remove all but a single value
@@ -110,27 +116,95 @@
             raise ValueError(
                 "{self.feature_col} contains less than 2 features after clipping outliers!!"
             )
 
         ## NA's
 
         # Handle NAs
-        if self.df["bins"].isna().sum() > 0:
+        if df["bins"].isna().sum() > 0:
             # replace the NA bin w/ n_bins - 1
-            self.df.loc[:, "bins"] = self.df.loc[:, "bins"].where(
-                ~self.df.loc[:, "bins"].isna(), self.n_bins - 1
+            df.loc[:, "bins"] = df.loc[:, "bins"].where(
+                ~df.loc[:, "bins"].isna(), n_bins - 1
             )
-            self.labels.append("NA")
-            self.n_bins += 1
+            self._labels.append("NA")
+            n_bins += 1
 
         # Convert bins to categories
-        self.df.bins = self.df.bins.astype("category")
+        df.bins = df.bins.astype("category")
 
         # Set all categories
-        self.df.bins = self.df.bins.cat.set_categories(list(range(self.n_bins - 1)))
+        df.bins = df.bins.cat.set_categories(list(range(n_bins - 1)))
+
+        return df, self._labels
+
+
+@dataclass
+class BinEventRatePlot(PlotProtocol):
+    # set the colorway
+    colors: PlotColors = field(default_factory=lambda: PlotColors())
+
+    # set (number of) bins
+    bins: list = field(default_factory=lambda: None)
+    n_bins: int = field(default_factory=lambda: 10)
+
+    # set hover setting
+    hoverinfo: str = field(default_factory=lambda: "skip")
+
+    # set default feature type
+    feature_type: str = field(default_factory=lambda: "float")
+
+    def do_math(
+        self,
+        df: pd.DataFrame,
+        feature_col: str,
+        target_col: str,
+        fillna: bool = False,
+        method: str = "quantile",
+    ):
+        """
+        does the required math to generate the traces, annotations and axes for the roc-curve plot
+
+        1. imputes/removes missing values
+        2. extract traces from the distplot function from plotly
+        3. get the max density and feature value after imputing
+        """
+
+        # set feature and target column names
+        self.feature_col = feature_col
+        self.target_col = target_col
+
+        # make fresh copy of df
+        self.df = df.copy()
+
+        # Calculate global event rate
+        self.event_rate = np.mean(self.df[target_col])
+
+        # Adjust n_bins if less unique values exist
+        self.n_bins = self.n_bins if self.bins is None else len(self.bins)
+        n_unique_feat_vals = df[feature_col].nunique()
+        self.n_bins = np.minimum(n_unique_feat_vals, self.n_bins)
+
+        # add bins column using strategy depending on feature type
+        if self.feature_type == "categorical":
+            print("using categorical binner")
+            if self.df[self.feature_col].nunique() > self.n_bins:
+                raise ValueError(
+                    f"Too many unique values for feature: {self.feature_col} ({self.df[self.feature_col].nunique()}) to only use {self.n_bins} bins. Increase n_bins to at least {self.df[self.feature_col].nunique()}!"
+                )
+            binner = CategoricalBinner()
+            self.df, self.labels = binner.add_bins(self.df, self.feature_col)
+        else:
+            if self.df[self.feature_col].nunique() < MIN_N_UNIQUE:
+                logging.warning(
+                    f"{self.feature_col} only has {self.df[self.feature_col].nunique()} distinct values, consider switching feature type for {self.feature_col} to categorical (currenly {self.feature_type})"
+                )
+            binner = StandardBinner()
+            self.df, self.labels = binner.add_bins(
+                self.df, self.feature_col, self.n_bins, self.bins, method=method
+            )
 
         # Group into bins and calculate required metrics
         self.df_binned = self.df.groupby("bins").agg(
             {feature_col: [len], target_col: ["mean"]}
         )
 
         # Rename columns
```

### Comparing `plottah-0.1.5/plottah/plots/DistPlot.py` & `plottah-0.1.6/plottah/plots/DistPlot.py`

 * *Files identical despite different names*

### Comparing `plottah-0.1.5/plottah/plots/PlotProtocol.py` & `plottah-0.1.6/plottah/plots/PlotProtocol.py`

 * *Files identical despite different names*

### Comparing `plottah-0.1.5/plottah/plots/RocCurvePlot.py` & `plottah-0.1.6/plottah/plots/RocCurvePlot.py`

 * *Files identical despite different names*

### Comparing `plottah-0.1.5/plottah/utils.py` & `plottah-0.1.6/plottah/utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -63,15 +63,14 @@
 
     return df
 
 
 def get_bins(
     df: pd.DataFrame,
     feature_col: str,
-    target_col: str,
     min_val_adj: float,
     max_val_adj: float,
     n_bins: int = 10,
     method: str = "quantile",
     bins: list = None,
 ) -> np.ndarray:
     """
```

### Comparing `plottah-0.1.5/PKG-INFO` & `plottah-0.1.6/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,22 +1,20 @@
 Metadata-Version: 2.1
 Name: plottah
-Version: 0.1.5
+Version: 0.1.6
 Summary: 
 Author: Niels Ota
-Requires-Python: >=3.6,<4.0
+Requires-Python: >=3.8,<4.0
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: jupyter (>=1.0.0,<2.0.0)
-Requires-Dist: numpy (>=1.25.0,<2.0.0)
+Requires-Dist: numpy (>=1.20.0,<2.0.0)
 Requires-Dist: pandas (>=2.0.2,<3.0.0)
 Requires-Dist: plotly (>=5.15.0,<6.0.0)
 Requires-Dist: pre-commit (>=3.3.3,<4.0.0)
 Requires-Dist: pydantic[dotenv] (>=1.10.9,<2.0.0)
 Requires-Dist: pylint (>=2.17.4,<3.0.0)
 Requires-Dist: pytest (>=7.3.2,<8.0.0)
 Requires-Dist: pyyaml (>=6.0,<7.0)
```


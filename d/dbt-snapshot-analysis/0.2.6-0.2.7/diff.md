# Comparing `tmp/dbt_snapshot_analysis-0.2.6.tar.gz` & `tmp/dbt_snapshot_analysis-0.2.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dbt_snapshot_analysis-0.2.6.tar", last modified: Mon Jun 26 15:35:46 2023, max compression
+gzip compressed data, was "dbt_snapshot_analysis-0.2.7.tar", last modified: Wed Jun 28 09:52:33 2023, max compression
```

## Comparing `dbt_snapshot_analysis-0.2.6.tar` & `dbt_snapshot_analysis-0.2.7.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 sammyteillet   (501) staff       (20)        0 2023-06-26 15:35:46.691938 dbt_snapshot_analysis-0.2.6/
--rw-r--r--   0 sammyteillet   (501) staff       (20)     1355 2023-06-26 15:35:46.691810 dbt_snapshot_analysis-0.2.6/PKG-INFO
--rw-r--r--   0 sammyteillet   (501) staff       (20)      936 2023-06-26 08:26:25.000000 dbt_snapshot_analysis-0.2.6/README.md
-drwxr-xr-x   0 sammyteillet   (501) staff       (20)        0 2023-06-26 15:35:46.690692 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/
--rw-r--r--   0 sammyteillet   (501) staff       (20)        0 2023-06-23 13:17:16.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/__init__.py
--rw-r--r--   0 sammyteillet   (501) staff       (20)      873 2023-06-21 15:26:08.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/data_validation.py
--rw-r--r--   0 sammyteillet   (501) staff       (20)     9807 2023-06-26 15:35:00.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/dbt_snapshot_analysis.py
--rw-r--r--   0 sammyteillet   (501) staff       (20)     2025 2023-06-26 15:24:40.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/snapshot_utils.py
--rw-r--r--   0 sammyteillet   (501) staff       (20)      372 2023-06-23 13:21:59.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/streamlit_entry_point.py
-drwxr-xr-x   0 sammyteillet   (501) staff       (20)        0 2023-06-26 15:35:46.691603 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/
--rw-r--r--   0 sammyteillet   (501) staff       (20)     1355 2023-06-26 15:35:46.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/PKG-INFO
--rw-r--r--   0 sammyteillet   (501) staff       (20)      499 2023-06-26 15:35:46.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/SOURCES.txt
--rw-r--r--   0 sammyteillet   (501) staff       (20)        1 2023-06-26 15:35:46.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/dependency_links.txt
--rw-r--r--   0 sammyteillet   (501) staff       (20)       91 2023-06-26 15:35:46.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/entry_points.txt
--rw-r--r--   0 sammyteillet   (501) staff       (20)       24 2023-06-26 15:35:46.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/requires.txt
--rw-r--r--   0 sammyteillet   (501) staff       (20)       22 2023-06-26 15:35:46.000000 dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/top_level.txt
--rw-r--r--   0 sammyteillet   (501) staff       (20)       38 2023-06-26 15:35:46.691982 dbt_snapshot_analysis-0.2.6/setup.cfg
--rw-r--r--   0 sammyteillet   (501) staff       (20)      847 2023-06-26 15:35:43.000000 dbt_snapshot_analysis-0.2.6/setup.py
+drwxr-xr-x   0 sammyteillet   (501) staff       (20)        0 2023-06-28 09:52:33.380275 dbt_snapshot_analysis-0.2.7/
+-rw-r--r--   0 sammyteillet   (501) staff       (20)     1355 2023-06-28 09:52:33.380035 dbt_snapshot_analysis-0.2.7/PKG-INFO
+-rw-r--r--   0 sammyteillet   (501) staff       (20)      936 2023-06-26 08:26:25.000000 dbt_snapshot_analysis-0.2.7/README.md
+drwxr-xr-x   0 sammyteillet   (501) staff       (20)        0 2023-06-28 09:52:33.378561 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/
+-rw-r--r--   0 sammyteillet   (501) staff       (20)        0 2023-06-23 13:17:16.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/__init__.py
+-rw-r--r--   0 sammyteillet   (501) staff       (20)      873 2023-06-21 15:26:08.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/data_validation.py
+-rw-r--r--   0 sammyteillet   (501) staff       (20)    10834 2023-06-28 09:51:13.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/dbt_snapshot_analysis.py
+-rw-r--r--   0 sammyteillet   (501) staff       (20)     2025 2023-06-26 15:24:40.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/snapshot_utils.py
+-rw-r--r--   0 sammyteillet   (501) staff       (20)      372 2023-06-23 13:21:59.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/streamlit_entry_point.py
+drwxr-xr-x   0 sammyteillet   (501) staff       (20)        0 2023-06-28 09:52:33.379639 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/
+-rw-r--r--   0 sammyteillet   (501) staff       (20)     1355 2023-06-28 09:52:33.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/PKG-INFO
+-rw-r--r--   0 sammyteillet   (501) staff       (20)      499 2023-06-28 09:52:33.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/SOURCES.txt
+-rw-r--r--   0 sammyteillet   (501) staff       (20)        1 2023-06-28 09:52:33.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/dependency_links.txt
+-rw-r--r--   0 sammyteillet   (501) staff       (20)       91 2023-06-28 09:52:33.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/entry_points.txt
+-rw-r--r--   0 sammyteillet   (501) staff       (20)       24 2023-06-28 09:52:33.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/requires.txt
+-rw-r--r--   0 sammyteillet   (501) staff       (20)       22 2023-06-28 09:52:33.000000 dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/top_level.txt
+-rw-r--r--   0 sammyteillet   (501) staff       (20)       38 2023-06-28 09:52:33.380353 dbt_snapshot_analysis-0.2.7/setup.cfg
+-rw-r--r--   0 sammyteillet   (501) staff       (20)      847 2023-06-28 09:52:30.000000 dbt_snapshot_analysis-0.2.7/setup.py
```

### Comparing `dbt_snapshot_analysis-0.2.6/PKG-INFO` & `dbt_snapshot_analysis-0.2.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbt_snapshot_analysis
-Version: 0.2.6
+Version: 0.2.7
 Summary: A package for analyzing snapshots
 Home-page: https://github.com/data-drift/dbt-snapshot-analytics
 Author: Sammy Teillet
 Author-email: sammy.teillet@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

#### html2text {}

 * *error from `html2text {}`:*

 * *File "/tmp/diffoscope_yezgkbjf_/tmpwcrn3hnh_TarContainer/0/1", line 21, column 2: Levels of opening and closing headings don't match*

 * *File "/tmp/diffoscope_yezgkbjf_/tmpwcrn3hnh_TarContainer/0/1", line 21, column 2: Levels of opening and closing headings don't match*

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: dbt_snapshot_analysis Version: 0.2.6 Summary: A
+Metadata-Version: 2.1 Name: dbt_snapshot_analysis Version: 0.2.7 Summary: A
 package for analyzing snapshots Home-page: https://github.com/data-drift/dbt-
 snapshot-analytics Author: Sammy Teillet Author-email: sammy.teillet@gmail.com
 Classifier: Programming Language :: Python :: 3 Classifier: License :: OSI
 Approved :: MIT License Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
                                [DataDrift_logo]
                        ***** A Changelog for Data *****
```

### Comparing `dbt_snapshot_analysis-0.2.6/README.md` & `dbt_snapshot_analysis-0.2.7/README.md`

 * *Files identical despite different names*

### Comparing `dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/data_validation.py` & `dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/data_validation.py`

 * *Files identical despite different names*

### Comparing `dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/dbt_snapshot_analysis.py` & `dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/dbt_snapshot_analysis.py`

 * *Files 10% similar despite different names*

```diff
@@ -242,15 +242,21 @@
 
             all_monthly_volatility = (
                 all_results[all_results["metric_value"] > 0]
                 .groupby("metric_date")["relative_value"]
                 .std()
             )
 
-            print("all_monthly_volatility", all_monthly_volatility)
+            all_monthly_volatility_from_latest_value = (
+                all_results[all_results["metric_value"] > 0]
+                .groupby("metric_date")["relative_value"]
+                .apply(lambda x: ((x - 1) ** 2).mean() ** 0.5)
+            )
+
+            print("all_monthly_volatility", all_monthly_volatility_from_latest_value)
 
             grouped_df = all_results.groupby("metric_date")
 
             st.set_option("deprecation.showPyplotGlobalUse", False)
             fig = go.Figure()
 
             for metric_name, group in grouped_df:
@@ -268,15 +274,31 @@
                 yaxis_title="Metric Value",
                 showlegend=True,
             )
             st.plotly_chart(fig)
 
             st.subheader("Monthly volatility")
 
-            st.dataframe(all_monthly_volatility)
+            st.dataframe(all_monthly_volatility_from_latest_value)
+
+            st.header("Summary")
+            summary1, summary2 = st.columns(2)
+            with summary1:
+                st.subheader("Mean lifespan of a row")
+                st.write("The average time it takes for an error to be corrected.")
+                meanLifespan = dead_versions.mean()
+                st.write(f"{meanLifespan:.2f} days")
+
+            with summary2:
+                st.subheader("Volatility of the metric")
+                st.write(
+                    "Between 0 and 1. Represents the difference between the displayed value at time T and the latest value."
+                )
+                meanVolatility = all_monthly_volatility_from_latest_value.mean()
+                st.write(f"{meanVolatility:.4f}")
 
 
 def main():
     run()
 
 
 if __name__ == "__main__":
```

### Comparing `dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis/snapshot_utils.py` & `dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis/snapshot_utils.py`

 * *Files identical despite different names*

### Comparing `dbt_snapshot_analysis-0.2.6/dbt_snapshot_analysis.egg-info/PKG-INFO` & `dbt_snapshot_analysis-0.2.7/dbt_snapshot_analysis.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbt-snapshot-analysis
-Version: 0.2.6
+Version: 0.2.7
 Summary: A package for analyzing snapshots
 Home-page: https://github.com/data-drift/dbt-snapshot-analytics
 Author: Sammy Teillet
 Author-email: sammy.teillet@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

#### html2text {}

 * *error from `html2text {}`:*

 * *File "/tmp/diffoscope_yezgkbjf_/tmpwcrn3hnh_TarContainer/0/10", line 21, column 2: Levels of opening and closing headings don't match*

 * *File "/tmp/diffoscope_yezgkbjf_/tmpwcrn3hnh_TarContainer/0/10", line 21, column 2: Levels of opening and closing headings don't match*

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: dbt-snapshot-analysis Version: 0.2.6 Summary: A
+Metadata-Version: 2.1 Name: dbt-snapshot-analysis Version: 0.2.7 Summary: A
 package for analyzing snapshots Home-page: https://github.com/data-drift/dbt-
 snapshot-analytics Author: Sammy Teillet Author-email: sammy.teillet@gmail.com
 Classifier: Programming Language :: Python :: 3 Classifier: License :: OSI
 Approved :: MIT License Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
                                [DataDrift_logo]
                        ***** A Changelog for Data *****
```

### Comparing `dbt_snapshot_analysis-0.2.6/setup.py` & `dbt_snapshot_analysis-0.2.7/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name="dbt_snapshot_analysis",
-    version="0.2.6",
+    version="0.2.7",
     packages=find_packages(),
     py_modules=["dbt_snapshot_analysis"],
     install_requires=["pandas", "plotly", "streamlit"],
     long_description=open("README.md", "r").read(),
     long_description_content_type="text/markdown",
     entry_points={
         "console_scripts": [
```


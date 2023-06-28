# Comparing `tmp/acro-0.1.0.tar.gz` & `tmp/acro-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "acro-0.1.0.tar", last modified: Fri Apr 28 13:36:23 2023, max compression
+gzip compressed data, was "acro-0.2.0.tar", last modified: Wed Jun 28 15:01:33 2023, max compression
```

## Comparing `acro-0.1.0.tar` & `acro-0.2.0.tar`

### file list

```diff
@@ -1,20 +1,22 @@
-drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-04-28 13:36:23.972102 acro-0.1.0/
--rw-rw-r--   0 unknown   (1000) unknown   (1000)     1063 2022-09-08 13:00:24.000000 acro-0.1.0/LICENSE
--rw-rw-r--   0 unknown   (1000) unknown   (1000)     3149 2023-04-28 13:36:23.972102 acro-0.1.0/PKG-INFO
--rw-rw-r--   0 unknown   (1000) unknown   (1000)     2247 2022-11-17 15:40:19.000000 acro-0.1.0/README.md
-drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-04-28 13:36:23.972102 acro-0.1.0/acro/
--rw-rw-r--   0 unknown   (1000) unknown   (1000)       32 2023-03-13 11:57:55.000000 acro-0.1.0/acro/__init__.py
--rw-rw-r--   0 unknown   (1000) unknown   (1000)    29746 2023-04-28 11:01:46.000000 acro-0.1.0/acro/acro.py
--rw-rw-r--   0 unknown   (1000) unknown   (1000)     1072 2023-04-18 18:15:41.000000 acro-0.1.0/acro/default.yaml
--rw-rw-r--   0 unknown   (1000) unknown   (1000)    11895 2023-04-28 11:01:46.000000 acro-0.1.0/acro/utils.py
-drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-04-28 13:36:23.972102 acro-0.1.0/acro.egg-info/
--rw-rw-r--   0 unknown   (1000) unknown   (1000)     3149 2023-04-28 13:36:23.000000 acro-0.1.0/acro.egg-info/PKG-INFO
--rw-rw-r--   0 unknown   (1000) unknown   (1000)      265 2023-04-28 13:36:23.000000 acro-0.1.0/acro.egg-info/SOURCES.txt
--rw-rw-r--   0 unknown   (1000) unknown   (1000)        1 2023-04-28 13:36:23.000000 acro-0.1.0/acro.egg-info/dependency_links.txt
--rw-rw-r--   0 unknown   (1000) unknown   (1000)       46 2023-04-28 13:36:23.000000 acro-0.1.0/acro.egg-info/requires.txt
--rw-rw-r--   0 unknown   (1000) unknown   (1000)       10 2023-04-28 13:36:23.000000 acro-0.1.0/acro.egg-info/top_level.txt
--rw-rw-r--   0 unknown   (1000) unknown   (1000)       38 2023-04-28 13:36:23.972102 acro-0.1.0/setup.cfg
--rw-rw-r--   0 unknown   (1000) unknown   (1000)     1427 2023-04-28 13:27:48.000000 acro-0.1.0/setup.py
-drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-04-28 13:36:23.972102 acro-0.1.0/test/
--rw-rw-r--   0 unknown   (1000) unknown   (1000)        0 2022-09-26 11:44:01.000000 acro-0.1.0/test/__init__.py
--rw-rw-r--   0 unknown   (1000) unknown   (1000)    10759 2023-04-27 09:35:54.000000 acro-0.1.0/test/test_initial.py
+drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-06-28 15:01:33.486188 acro-0.2.0/
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     1063 2022-09-08 13:00:24.000000 acro-0.2.0/LICENSE
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     3129 2023-06-28 15:01:33.486188 acro-0.2.0/PKG-INFO
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     2227 2023-06-28 14:56:03.000000 acro-0.2.0/README.md
+drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-06-28 15:01:33.486188 acro-0.2.0/acro/
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)       32 2023-03-13 11:57:55.000000 acro-0.2.0/acro/__init__.py
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)    28771 2023-06-28 14:56:29.000000 acro-0.2.0/acro/acro.py
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     1072 2023-04-18 18:15:41.000000 acro-0.2.0/acro/default.yaml
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)    14979 2023-06-28 14:56:03.000000 acro-0.2.0/acro/record.py
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     9107 2023-06-28 14:56:03.000000 acro-0.2.0/acro/utils.py
+drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-06-28 15:01:33.486188 acro-0.2.0/acro.egg-info/
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     3129 2023-06-28 15:01:33.000000 acro-0.2.0/acro.egg-info/PKG-INFO
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)      294 2023-06-28 15:01:33.000000 acro-0.2.0/acro.egg-info/SOURCES.txt
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)        1 2023-06-28 15:01:33.000000 acro-0.2.0/acro.egg-info/dependency_links.txt
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)       46 2023-06-28 15:01:33.000000 acro-0.2.0/acro.egg-info/requires.txt
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)       10 2023-06-28 15:01:33.000000 acro-0.2.0/acro.egg-info/top_level.txt
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)       38 2023-06-28 15:01:33.486188 acro-0.2.0/setup.cfg
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     1427 2023-06-28 14:56:03.000000 acro-0.2.0/setup.py
+drwxrwxr-x   0 unknown   (1000) unknown   (1000)        0 2023-06-28 15:01:33.486188 acro-0.2.0/test/
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)        0 2022-09-26 11:44:01.000000 acro-0.2.0/test/__init__.py
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)     2058 2023-05-08 20:18:08.000000 acro-0.2.0/test/stata.py
+-rw-rw-r--   0 unknown   (1000) unknown   (1000)    11152 2023-06-28 14:56:03.000000 acro-0.2.0/test/test_initial.py
```

### Comparing `acro-0.1.0/LICENSE` & `acro-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `acro-0.1.0/PKG-INFO` & `acro-0.2.0/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: acro
-Version: 0.1.0
+Version: 0.2.0
 Summary: ACRO: Tools for the Automatic Checking of Research Outputs
 Home-page: https://github.com/AI-SDC/ACRO
 Maintainer: Jim Smith
 Maintainer-email: james.smith@uwe.ac.uk
 License: MIT
 Keywords: data-privacy,data-protection,privacy,privacy-tools,statistical-disclosure-control
 Classifier: Development Status :: 3 - Alpha
@@ -45,18 +45,20 @@
 *   produce simple summary documents TRE staff can use to streamline their
     workflow.
 
 ![ACRO workflow and architecture schematic](docs/schematic.png)
 
 See the project [wiki](https://github.com/AI-SDC/ACRO/wiki) for details.
 
+## Coding standards
+Are also described in the project [wiki](https://github.com/AI-SDC/ACRO/wiki)
+
 *******************************************************************************
 
 [![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://opensource.org/licenses/MIT)
 [![Latest Version](https://img.shields.io/github/v/release/AI-SDC/ACRO?style=flat)](https://github.com/AI-SDC/ACRO/releases)
 [![DOI](https://zenodo.org/badge/534172863.svg)](https://zenodo.org/badge/latestdoi/534172863)
 [![PyPI package](https://img.shields.io/pypi/v/acro.svg)](https://pypi.org/project/acro)
 [![Python versions](https://img.shields.io/pypi/pyversions/acro.svg)](https://pypi.org/project/acro)
 
 [![Codacy](https://app.codacy.com/project/badge/Grade/a125e023fd7744d79cb42cd31f6ea05e)](https://www.codacy.com/gh/AI-SDC/ACRO/dashboard)
-[![Codiga](https://api.codiga.io/project/34766/status/svg)](https://app.codiga.io/public/project/34766/ACRO/dashboard)
 [![codecov](https://codecov.io/gh/AI-SDC/ACRO/branch/main/graph/badge.svg?token=VVHI41N05F)](https://codecov.io/gh/AI-SDC/ACRO)
```

### Comparing `acro-0.1.0/README.md` & `acro-0.2.0/README.md`

 * *Files 15% similar despite different names*

```diff
@@ -22,18 +22,20 @@
 *   produce simple summary documents TRE staff can use to streamline their
     workflow.
 
 ![ACRO workflow and architecture schematic](docs/schematic.png)
 
 See the project [wiki](https://github.com/AI-SDC/ACRO/wiki) for details.
 
+## Coding standards
+Are also described in the project [wiki](https://github.com/AI-SDC/ACRO/wiki)
+
 *******************************************************************************
 
 [![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://opensource.org/licenses/MIT)
 [![Latest Version](https://img.shields.io/github/v/release/AI-SDC/ACRO?style=flat)](https://github.com/AI-SDC/ACRO/releases)
 [![DOI](https://zenodo.org/badge/534172863.svg)](https://zenodo.org/badge/latestdoi/534172863)
 [![PyPI package](https://img.shields.io/pypi/v/acro.svg)](https://pypi.org/project/acro)
 [![Python versions](https://img.shields.io/pypi/pyversions/acro.svg)](https://pypi.org/project/acro)
 
 [![Codacy](https://app.codacy.com/project/badge/Grade/a125e023fd7744d79cb42cd31f6ea05e)](https://www.codacy.com/gh/AI-SDC/ACRO/dashboard)
-[![Codiga](https://api.codiga.io/project/34766/status/svg)](https://app.codiga.io/public/project/34766/ACRO/dashboard)
 [![codecov](https://codecov.io/gh/AI-SDC/ACRO/branch/main/graph/badge.svg?token=VVHI41N05F)](https://codecov.io/gh/AI-SDC/ACRO)
```

### Comparing `acro-0.1.0/acro/acro.py` & `acro-0.2.0/acro/acro.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,175 +1,115 @@
 """ACRO: Automatic Checking of Research Outputs."""
 
-import datetime
 import logging
-import os
 import pathlib
 import warnings
 from inspect import stack
 
 import pandas as pd
 import statsmodels.api as sm
 import statsmodels.formula.api as smf
 import yaml
 from pandas import DataFrame
 from statsmodels.discrete.discrete_model import BinaryResultsWrapper
 from statsmodels.iolib.table import SimpleTable
 from statsmodels.regression.linear_model import RegressionResultsWrapper
 
 from . import utils
+from .record import Records
 
 logging.basicConfig(level=logging.INFO)
 logger = logging.getLogger("acro")
 
 
 class ACRO:
     """ACRO: Automatic Checking of Research Outputs.
 
     Attributes
     ----------
     config : dict
         Safe parameters and their values.
-    results : dict
+    results : Records
         The current outputs including the results of checks.
     output_id : int
         The next identifier to be assigned to an output.
 
     Examples
     --------
     >>> acro = ACRO()
     >>> results = acro.ols(y, x)
     >>> results.summary()
-    >>> acro.finalise("my_results.json")
+    >>> acro.finalise("MYFOLDER", "json")
     """
 
     def __init__(self, config: str = "default") -> None:
         """Constructs a new ACRO object and reads parameters from config.
 
         Parameters
         ----------
         config : str
             Name of a yaml configuration file with safe parameters.
         """
         self.config: dict = {}
-        self.results: dict = {}
-        self.output_id: int = 0
+        self.results: Records = Records()
         path = pathlib.Path(__file__).with_name(config + ".yaml")
         logger.debug("path: %s", path)
         with open(path, encoding="utf-8") as handle:
             self.config = yaml.load(handle, Loader=yaml.loader.SafeLoader)
         logger.info("config: %s", self.config)
         # set globals needed for aggregation functions
         utils.THRESHOLD = self.config["safe_threshold"]
         utils.SAFE_PRATIO_P = self.config["safe_pratio_p"]
         utils.SAFE_NK_N = self.config["safe_nk_n"]
         utils.SAFE_NK_K = self.config["safe_nk_k"]
         utils.CHECK_MISSING_VALUES = self.config["check_missing_values"]
 
-    def finalise(self, filename: str = "results.json") -> dict:
+    def finalise(self, path: str = "outputs", ext="json") -> Records:
         """Creates a results file for checking.
 
         Parameters
         ----------
-        filename : str
-            Name of the output file. Valid extensions: {.json, .xlsx}.
+        path : str
+            Name of a folder to save outputs.
+        ext : str
+            Extension of the results file. Valid extensions: {json, xlsx}.
 
         Returns
         -------
-        dict
-            Dictionary representation of the output.
+        Records
+            Object storing the outputs.
         """
-        logger.debug("finalise()")
-        _, extension = os.path.splitext(filename)
-        if extension == ".json":
-            utils.finalise_json(filename, self.results)
-        elif extension == ".xlsx":
-            utils.finalise_excel(filename, self.results)
-        else:
-            raise ValueError("Invalid file extension. Options: {.json, .xlsx}")
-        logger.info("output written to: %s", filename)
+        self.results.finalise(path, ext)
         return self.results
 
-    def __add_output(  # pylint: disable=too-many-arguments
-        self,
-        command: str,
-        summary: str,
-        outcome: DataFrame,
-        output: str | list[DataFrame],
-        comments: str = "",
-    ) -> None:
-        """Adds an output to the results dictionary.
-
-        Parameters
-        ----------
-        command : str
-            String representation of the operation performed.
-        summary : str
-            String summarising the ACRO checks.
-        outcome : DataFrame
-            DataFrame describing the details of ACRO checks.
-        output : list[DataFrame]
-            List of output DataFrames.
-        comments: str
-            String entered by the user to add comments to the output.
-        """
-
-        now = datetime.datetime.now()
-        timestamp = str(now.strftime("%Y-%m-%d-%H%M%S%f")[:-4])
-
-        name: str = f"output_{self.output_id}_{timestamp}"
-        self.output_id += 1
-        self.results[name] = {
-            "command": command,
-            "summary": summary,
-            "outcome": outcome,
-            "output": output,  # json.loads(output),  # JSON to dict
-            "timestamp": timestamp,
-            "comments": comments,
-        }
-        logger.info("add_output(): %s", name)
-
     def remove_output(self, key: str) -> None:
-        """Removes an output from the results dictionary.
+        """Removes an output from the results.
 
         Parameters
         ----------
         key : str
             Key specifying which output to remove, e.g., 'output_0'.
         """
-        if key in self.results:
-            del self.results[key]
-            logger.info("remove_output(): %s removed", key)
-        else:
-            warnings.warn(f"unable to remove {key}, key not found", stacklevel=8)
+        self.results.remove(key)
 
     def print_outputs(self) -> None:
         """Prints the current results dictionary."""
-        logger.debug("print_outputs()")
-        for name, result in self.results.items():
-            print(f"{name}:")
-            for key, item in result.items():
-                print(f"{key}: {item}")
-            print("\n")
+        self.results.print()
 
     def custom_output(self, filename: str, comment: str = "") -> None:
         """Adds an unsupported output to the results dictionary.
 
         Parameters
         ----------
         filename : str
             The name of the file that will be added to the list of the outputs.
+        comment : str
+            An optional comment.
         """
-        self.__add_output(
-            command="custom",
-            summary="review",
-            outcome=DataFrame(),
-            output=os.path.abspath(filename),
-            comments=comment,
-        )
+        self.results.add_custom(filename, comment)
 
     def crosstab(  # pylint: disable=too-many-arguments,too-many-locals
         self,
         index,
         columns,
         values=None,
         rownames=None,
@@ -276,16 +216,26 @@
         for name, mask in masks.items():
             mask.fillna(value=1, inplace=True)
             mask = mask.astype(int)
             mask.replace({0: False, 1: True}, inplace=True)
             masks[name] = mask
 
         table, outcome = utils.apply_suppression(table, masks)
-        summary = utils.get_summary(masks)
-        self.__add_output(command, summary, outcome, [table])
+        properties: dict = {"method": "crosstab"}
+        status, summary = utils.get_summary(masks, properties)
+
+        self.results.add(
+            status=status,
+            output_type="table",
+            properties=properties,
+            command=command,
+            summary=summary,
+            outcome=outcome,
+            output=[table],
+        )
         return table
 
     def pivot_table(  # pylint: disable=too-many-arguments,too-many-locals
         self,
         data: DataFrame,
         values=None,
         index=None,
@@ -391,42 +341,58 @@
             if utils.CHECK_MISSING_VALUES:
                 agg = [utils.agg_missing] * n_agg if n_agg > 1 else utils.agg_missing
                 masks["missing"] = pd.pivot_table(
                     data, values, index, columns, aggfunc=agg
                 )
 
         table, outcome = utils.apply_suppression(table, masks)
-        summary = utils.get_summary(masks)
-        self.__add_output(command, summary, outcome, [table])
+        properties: dict = {"method": "pivot_table"}
+        status, summary = utils.get_summary(masks, properties)
+
+        self.results.add(
+            status=status,
+            output_type="table",
+            properties=properties,
+            command=command,
+            summary=summary,
+            outcome=outcome,
+            output=[table],
+        )
         return table
 
-    def __check_model_dof(self, name: str, model) -> str:
+    def __check_model_dof(self, name: str, model) -> [str, str, float]:
         """Check model DOF.
 
         Parameters
         ----------
         name : str
             The name of the model.
         model
             A statsmodels model.
 
         Returns
         -------
         str
+            Status: {"review", "fail", "pass"}.
+        str
             Summary of the check.
+        float
+            The degrees of freedom.
         """
+        status = "fail"
         dof: int = model.df_resid
         threshold: int = self.config["safe_dof_threshold"]
         if dof < threshold:
             summary = f"fail; dof={dof} < {threshold}"
             warnings.warn(f"Unsafe {name}: {summary}", stacklevel=8)
         else:
+            status = "pass"
             summary = f"pass; dof={dof} >= {threshold}"
         logger.info("%s() outcome: %s", name, summary)
-        return summary
+        return status, summary, float(dof)
 
     def ols(  # pylint: disable=too-many-locals
         self, endog, exog=None, missing="none", hasconst=None, **kwargs
     ) -> RegressionResultsWrapper:
         """Fits Ordinary Least Squares Regression.
 
         Parameters
@@ -455,18 +421,24 @@
         RegressionResultsWrapper
             Results.
         """
         logger.debug("ols()")
         command: str = utils.get_command("ols()", stack())
         model = sm.OLS(endog, exog=exog, missing=missing, hasconst=hasconst, **kwargs)
         results = model.fit()
-        summary = self.__check_model_dof("ols", model)
+        status, summary, dof = self.__check_model_dof("ols", model)
         tables: list[SimpleTable] = results.summary().tables
-        self.__add_output(
-            command, summary, DataFrame(), utils.get_summary_dataframes(tables)
+        self.results.add(
+            status=status,
+            output_type="regression",
+            properties={"method": "ols", "dof": dof},
+            command=command,
+            summary=summary,
+            outcome=DataFrame(),
+            output=utils.get_summary_dataframes(tables),
         )
         return results
 
     def olsr(  # pylint: disable=too-many-locals,keyword-arg-before-vararg
         self, formula, data, subset=None, drop_cols=None, *args, **kwargs
     ) -> RegressionResultsWrapper:
         """Fits Ordinary Least Squares Regression from a formula and dataframe.
@@ -512,18 +484,24 @@
             data=data,
             subset=subset,
             drop_cols=drop_cols,
             *args,
             **kwargs,
         )
         results = model.fit()
-        summary = self.__check_model_dof("olsr", model)
+        status, summary, dof = self.__check_model_dof("olsr", model)
         tables: list[SimpleTable] = results.summary().tables
-        self.__add_output(
-            command, summary, DataFrame(), utils.get_summary_dataframes(tables)
+        self.results.add(
+            status=status,
+            output_type="regression",
+            properties={"method": "olsr", "dof": dof},
+            command=command,
+            summary=summary,
+            outcome=DataFrame(),
+            output=utils.get_summary_dataframes(tables),
         )
         return results
 
     def logit(  # pylint: disable=too-many-arguments,too-many-locals
         self,
         endog,
         exog,
@@ -554,18 +532,24 @@
         BinaryResultsWrapper
             Results.
         """
         logger.debug("logit()")
         command: str = utils.get_command("logit()", stack())
         model = sm.Logit(endog, exog, missing=missing, check_rank=check_rank)
         results = model.fit()
-        summary = self.__check_model_dof("logit", model)
+        status, summary, dof = self.__check_model_dof("logit", model)
         tables: list[SimpleTable] = results.summary().tables
-        self.__add_output(
-            command, summary, DataFrame(), utils.get_summary_dataframes(tables)
+        self.results.add(
+            status=status,
+            output_type="regression",
+            properties={"method": "logit", "dof": dof},
+            command=command,
+            summary=summary,
+            outcome=DataFrame(),
+            output=utils.get_summary_dataframes(tables),
         )
         return results
 
     def logitr(  # pylint: disable=too-many-locals,keyword-arg-before-vararg
         self, formula, data, subset=None, drop_cols=None, *args, **kwargs
     ) -> RegressionResultsWrapper:
         """Fits Logit model from a formula and dataframe.
@@ -611,18 +595,24 @@
             data=data,
             subset=subset,
             drop_cols=drop_cols,
             *args,
             **kwargs,
         )
         results = model.fit()
-        summary = self.__check_model_dof("logitr", model)
+        status, summary, dof = self.__check_model_dof("logitr", model)
         tables: list[SimpleTable] = results.summary().tables
-        self.__add_output(
-            command, summary, DataFrame(), utils.get_summary_dataframes(tables)
+        self.results.add(
+            status=status,
+            output_type="regression",
+            properties={"method": "logitr", "dof": dof},
+            command=command,
+            summary=summary,
+            outcome=DataFrame(),
+            output=utils.get_summary_dataframes(tables),
         )
         return results
 
     def probit(  # pylint: disable=too-many-arguments,too-many-locals
         self,
         endog,
         exog,
@@ -653,18 +643,24 @@
         BinaryResultsWrapper
             Results.
         """
         logger.debug("probit()")
         command: str = utils.get_command("probit()", stack())
         model = sm.Probit(endog, exog, missing=missing, check_rank=check_rank)
         results = model.fit()
-        summary = self.__check_model_dof("probit", model)
+        status, summary, dof = self.__check_model_dof("probit", model)
         tables: list[SimpleTable] = results.summary().tables
-        self.__add_output(
-            command, summary, DataFrame(), utils.get_summary_dataframes(tables)
+        self.results.add(
+            status=status,
+            output_type="regression",
+            properties={"method": "probit", "dof": dof},
+            command=command,
+            summary=summary,
+            outcome=DataFrame(),
+            output=utils.get_summary_dataframes(tables),
         )
         return results
 
     def probitr(  # pylint: disable=too-many-locals,keyword-arg-before-vararg
         self, formula, data, subset=None, drop_cols=None, *args, **kwargs
     ) -> RegressionResultsWrapper:
         """Fits Probit model from a formula and dataframe.
@@ -710,61 +706,50 @@
             data=data,
             subset=subset,
             drop_cols=drop_cols,
             *args,
             **kwargs,
         )
         results = model.fit()
-        summary = self.__check_model_dof("probitr", model)
+        status, summary, dof = self.__check_model_dof("probitr", model)
         tables: list[SimpleTable] = results.summary().tables
-        self.__add_output(
-            command, summary, DataFrame(), utils.get_summary_dataframes(tables)
+        self.results.add(
+            status=status,
+            output_type="regression",
+            properties={"method": "probitr", "dof": dof},
+            command=command,
+            summary=summary,
+            outcome=DataFrame(),
+            output=utils.get_summary_dataframes(tables),
         )
         return results
 
     def rename_output(self, old: str, new: str) -> None:
-        """Rename an output and take the timestamp from the old name
-        and suffix it to the new name
+        """Rename an output.
 
         Parameters
         ----------
         old : str
             The old name of the output.
         new : str
             The new name of the output.
         """
-        timestamp = old.split("_")[2]
-        new = new + "_" + timestamp
-        if old in self.results:
-            self.results[new] = self.results[old]
-            del self.results[old]
-            logger.info("rename_output(): %s renamed to %s", old, new)
-        else:
-            warnings.warn(f"unable to rename {old}, key not found", stacklevel=8)
+        self.results.rename(old, new)
 
     def add_comments(self, output: str, comment: str) -> None:
-        """Adds comments to outputs
+        """Adds a comment to an output.
 
         Parameters
         ----------
         output : str
             The name of the output.
         comment : str
             The comment.
         """
-        if output in self.results:
-            if self.results[output]["comments"] == "":
-                self.results[output]["comments"] = comment
-            else:
-                self.results[output]["comments"] = (
-                    self.results[output]["comments"] + ", " + comment
-                )
-            logger.info("a comment was added to %s", output)
-        else:
-            warnings.warn(f"unable to find {output}, key not found", stacklevel=8)
+        self.results.add_comments(output, comment)
 
 
 def add_constant(data, prepend: bool = True, has_constant: str = "skip"):
     """Add a column of ones to an array.
 
     Parameters
     ----------
```

### Comparing `acro-0.1.0/acro/default.yaml` & `acro-0.2.0/acro/default.yaml`

 * *Files identical despite different names*

### Comparing `acro-0.1.0/acro.egg-info/PKG-INFO` & `acro-0.2.0/acro.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: acro
-Version: 0.1.0
+Version: 0.2.0
 Summary: ACRO: Tools for the Automatic Checking of Research Outputs
 Home-page: https://github.com/AI-SDC/ACRO
 Maintainer: Jim Smith
 Maintainer-email: james.smith@uwe.ac.uk
 License: MIT
 Keywords: data-privacy,data-protection,privacy,privacy-tools,statistical-disclosure-control
 Classifier: Development Status :: 3 - Alpha
@@ -45,18 +45,20 @@
 *   produce simple summary documents TRE staff can use to streamline their
     workflow.
 
 ![ACRO workflow and architecture schematic](docs/schematic.png)
 
 See the project [wiki](https://github.com/AI-SDC/ACRO/wiki) for details.
 
+## Coding standards
+Are also described in the project [wiki](https://github.com/AI-SDC/ACRO/wiki)
+
 *******************************************************************************
 
 [![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://opensource.org/licenses/MIT)
 [![Latest Version](https://img.shields.io/github/v/release/AI-SDC/ACRO?style=flat)](https://github.com/AI-SDC/ACRO/releases)
 [![DOI](https://zenodo.org/badge/534172863.svg)](https://zenodo.org/badge/latestdoi/534172863)
 [![PyPI package](https://img.shields.io/pypi/v/acro.svg)](https://pypi.org/project/acro)
 [![Python versions](https://img.shields.io/pypi/pyversions/acro.svg)](https://pypi.org/project/acro)
 
 [![Codacy](https://app.codacy.com/project/badge/Grade/a125e023fd7744d79cb42cd31f6ea05e)](https://www.codacy.com/gh/AI-SDC/ACRO/dashboard)
-[![Codiga](https://api.codiga.io/project/34766/status/svg)](https://app.codiga.io/public/project/34766/ACRO/dashboard)
 [![codecov](https://codecov.io/gh/AI-SDC/ACRO/branch/main/graph/badge.svg?token=VVHI41N05F)](https://codecov.io/gh/AI-SDC/ACRO)
```

### Comparing `acro-0.1.0/setup.py` & `acro-0.2.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 from setuptools import find_packages, setup
 
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 
 setup(
     name="acro",
-    version="0.1.0",
+    version="0.2.0",
     license="MIT",
     maintainer="Jim Smith",
     maintainer_email="james.smith@uwe.ac.uk",
     description="ACRO: Tools for the Automatic Checking of Research Outputs",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/AI-SDC/ACRO",
```

### Comparing `acro-0.1.0/test/test_initial.py` & `acro-0.2.0/test/test_initial.py`

 * *Files 27% similar despite different names*

```diff
@@ -3,15 +3,16 @@
 import json
 import os
 
 import numpy as np
 import pandas as pd
 import pytest
 
-from acro import ACRO, add_constant, utils
+from acro import ACRO, add_constant, record, utils
+from acro.record import Record, Records
 
 # pylint: disable=redefined-outer-name
 
 
 @pytest.fixture
 def data() -> pd.DataFrame:
     """Load test data."""
@@ -25,78 +26,78 @@
     """Initialise ACRO."""
     return ACRO()
 
 
 def test_crosstab_threshold(data, acro):
     """Crosstab threshold test."""
     _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
     correct_summary: str = "fail; threshold: 6 cells suppressed; "
-    output_0 = list(output.keys())[0]
-    assert output[output_0]["summary"] == correct_summary
+    output = results.get_index(0)
+    assert output.summary == correct_summary
 
 
 def test_crosstab_multiple(data, acro):
     """Crosstab multiple rule test."""
     _ = acro.crosstab(
         data.year, data.grant_type, values=data.inc_grants, aggfunc="mean"
     )
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
     correct_summary: str = (
         "fail; threshold: 6 cells suppressed; p-ratio: 1 cells suppressed; "
         "nk-rule: 1 cells suppressed; "
     )
-    output_0 = list(output.keys())[0]
-    assert output[output_0]["summary"] == correct_summary
+    output = results.get_index(0)
+    assert output.summary == correct_summary
 
 
 def test_negatives(data, acro):
     """Pivot table and Crosstab with negative values."""
     data.loc[0:10, "inc_grants"] = -10
     _ = acro.crosstab(
         data.year, data.grant_type, values=data.inc_grants, aggfunc="mean"
     )
     _ = acro.pivot_table(
         data, index=["grant_type"], values=["inc_grants"], aggfunc=["mean", "std"]
     )
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
     correct_summary: str = "review; negative values found"
-    output_0 = list(output.keys())[0]
-    output_1 = list(output.keys())[1]
-    assert output[output_0]["summary"] == correct_summary
-    assert output[output_1]["summary"] == correct_summary
+    output_0 = results.get_index(0)
+    output_1 = results.get_index(1)
+    assert output_0.summary == correct_summary
+    assert output_1.summary == correct_summary
 
 
 def test_pivot_table_pass(data, acro):
     """Pivot table pass test."""
     _ = acro.pivot_table(
         data, index=["grant_type"], values=["inc_grants"], aggfunc=["mean", "std"]
     )
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
     correct_summary: str = "pass"
-    output_0 = list(output.keys())[0]
-    assert output[output_0]["summary"] == correct_summary
+    output_0 = results.get_index(0)
+    assert output_0.summary == correct_summary
 
 
 def test_pivot_table_cols(data, acro):
     """Pivot table with columns test."""
     _ = acro.pivot_table(
         data,
         index=["grant_type"],
         columns=["year"],
         values=["inc_grants"],
         aggfunc=["mean", "std"],
     )
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
     correct_summary: str = (
         "fail; threshold: 14 cells suppressed; "
         "p-ratio: 2 cells suppressed; nk-rule: 2 cells suppressed; "
     )
-    output_0 = list(output.keys())[0]
-    assert output[output_0]["summary"] == correct_summary
+    output_0 = results.get_index(0)
+    assert output_0.summary == correct_summary
 
 
 def test_ols(data, acro):
     """Ordinary Least Squares test."""
     new_df = data[["inc_activity", "inc_grants", "inc_donations", "total_costs"]]
     new_df = new_df.dropna()
     # OLS
@@ -109,20 +110,20 @@
     # OLSR
     results = acro.olsr(
         formula="inc_activity ~ inc_grants + inc_donations + total_costs", data=new_df
     )
     assert results.df_resid == 807
     assert results.rsquared == pytest.approx(0.894, 0.001)
     # Finalise
-    output: dict = acro.finalise()
+    results: dict = acro.finalise()
     correct_summary: str = "pass; dof=807.0 >= 10"
-    output_0 = list(output.keys())[0]
-    output_1 = list(output.keys())[1]
-    assert output[output_0]["summary"] == correct_summary
-    assert output[output_1]["summary"] == correct_summary
+    output_0 = results.get_index(0)
+    output_1 = results.get_index(1)
+    assert output_0.summary == correct_summary
+    assert output_1.summary == correct_summary
 
 
 def test_probit_logit(data, acro):
     """Probit and Logit tests."""
     new_df = data[
         ["survivor", "inc_activity", "inc_grants", "inc_donations", "total_costs"]
     ]
@@ -151,159 +152,174 @@
     results = acro.logitr(
         formula="survivor ~ inc_activity + inc_grants + inc_donations + total_costs",
         data=new_df,
     )
     assert results.df_resid == 806
     assert results.prsquared == pytest.approx(0.214, 0.01)
     # Finalise
-    output: dict = acro.finalise()
+    results: dict = acro.finalise()
     correct_summary: str = "pass; dof=806.0 >= 10"
-    output_0 = list(output.keys())[0]
-    output_1 = list(output.keys())[1]
-    output_2 = list(output.keys())[2]
-    output_3 = list(output.keys())[3]
-    assert output[output_0]["summary"] == correct_summary
-    assert output[output_1]["summary"] == correct_summary
-    assert output[output_2]["summary"] == correct_summary
-    assert output[output_3]["summary"] == correct_summary
+    output_0 = results.get_index(0)
+    output_1 = results.get_index(1)
+    output_2 = results.get_index(2)
+    output_3 = results.get_index(3)
+    assert output_0.summary == correct_summary
+    assert output_1.summary == correct_summary
+    assert output_2.summary == correct_summary
+    assert output_3.summary == correct_summary
 
 
 def test_finalise_excel(data, acro):
     """Finalise excel test."""
     _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise("test.xlsx")
-    output_0 = list(output.keys())[0]
-    load_data = pd.read_excel("test.xlsx", sheet_name=output_0)
+    path: str = "RES_PYTEST"
+    results: Records = acro.finalise(path, "xlsx")
+    output_0 = results.get_index(0)
+    filename = os.path.normpath(f"{path}/results.xlsx")
+    load_data = pd.read_excel(filename, sheet_name=output_0.uid)
     correct_cell: str = "_ = acro.crosstab(data.year, data.grant_type)"
     assert load_data.iloc[0, 0] == "Command"
     assert load_data.iloc[0, 1] == correct_cell
 
 
 def test_output_removal(data, acro):
     """Output removal and print test."""
     _ = acro.crosstab(data.year, data.grant_type)
     _ = acro.crosstab(data.year, data.grant_type)
     _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise()
-    output_0 = list(output.keys())[0]
-    output_1 = list(output.keys())[1]
-    acro.remove_output(output_0)
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
+    output_0 = results.get("output_0")
+    output_1 = results.get("output_1")
+    # remove something that is there
+    acro.remove_output(output_0.uid)
+    results = acro.finalise()
     correct_summary: str = "fail; threshold: 6 cells suppressed; "
-    assert output_0 not in output
-    assert output_1 in output
-    assert output[output_1]["summary"] == correct_summary
+    keys = results.get_keys()
+    assert output_0.uid not in keys
+    assert output_1.uid in keys
+    assert output_1.summary == correct_summary
     acro.print_outputs()
+    # remove something that is not there
+    with pytest.warns(UserWarning):
+        acro.remove_output("123")
 
 
-def test_finalise_json(data, acro):
-    """Finalise json test."""
-    _ = acro.crosstab(data.year, data.grant_type)
-    _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise("test.json")
-    output_0_name = list(output.keys())[0]
-    output_1_name = list(output.keys())[1]
-    output_0 = pd.read_csv(f"outputs/{output_0_name}.csv")
-    output_1 = pd.read_csv(f"outputs/{output_1_name}.csv")
-    assert (output[output_0_name]["output"][0].reset_index()).equals(output_0)
-    assert (output[output_1_name]["output"][0].reset_index()).equals(output_1)
-
-    with open("./outputs/test.json", encoding="utf-8") as file:
-        json_data = json.load(file)
-    assert json_data[output_0_name]["output"] == os.path.abspath(
-        f"outputs/{output_0_name}.csv"
-    )
-    assert json_data[output_1_name]["output"] == os.path.abspath(
-        f"outputs/{output_1_name}.csv"
-    )
+def test_load_output():
+    """Empty array when loading output."""
+    path: str = "RES_PYTEST"
+    with pytest.raises(ValueError):
+        record.load_output(path, [])
 
 
-def test_output_timestamp(data, acro):
-    """Adding timestamp to the output name and meta data test."""
+def test_finalise_invalid(data, acro):
+    """Invalid output format when finalising."""
     _ = acro.crosstab(data.year, data.grant_type)
-    _ = acro.pivot_table(
-        data,
-        index=["grant_type"],
-        columns=["year"],
-        values=["inc_grants"],
-        aggfunc=["mean", "std"],
-    )
-    output: dict = acro.finalise("test.json")
-    output_0_name = list(output.keys())[0]
-    output_1_name = list(output.keys())[1]
+    path: str = "RES_PYTEST"
+    with pytest.raises(ValueError):
+        _ = acro.finalise(path, "123")
 
-    del acro
 
-    acro = ACRO()
+def test_finalise_json(data, acro):
+    """Finalise json test."""
     _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise("test.json")
-    output_2_name = list(output.keys())[0]
-
-    with open("./outputs/test.json", encoding="utf-8") as file:
+    # write JSON
+    path: str = "RES_PYTEST"
+    result: Records = acro.finalise(path, "json")
+    # load JSON
+    loaded: Records = Records()
+    loaded.load_json(path)
+    orig = result.get_index(0)
+    read = loaded.get_index(0)
+    # check equal
+    assert orig.uid == read.uid
+    assert orig.status == read.status
+    assert orig.output_type == read.output_type
+    assert orig.properties == read.properties
+    assert orig.command == read.command
+    assert orig.summary == read.summary
+    assert orig.comments == read.comments
+    assert orig.timestamp == read.timestamp
+    assert (orig.output[0].reset_index()).equals(read.output[0])
+    # test reading JSON
+    with open(os.path.normpath(f"{path}/results.json"), encoding="utf-8") as file:
         json_data = json.load(file)
-        assert output_0_name in json_data.keys()
-        assert output_1_name in json_data.keys()
-        assert output_2_name in json_data.keys()
+    assert json_data[orig.uid]["output"][0] == f"{orig.uid}_0.csv"
+    # regression check: the outcome fields are dicts not strings
+    assert json_data[orig.uid]["outcome"]["R/G"] == {
+        "2010": "threshold; ",
+        "2011": "threshold; ",
+        "2012": "threshold; ",
+        "2013": "threshold; ",
+        "2014": "threshold; ",
+        "2015": "threshold; ",
+    }
 
 
 def test_rename_output(data, acro):
     """Output renaming test."""
     _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise()
-    output_0 = list(output.keys())[0]
-    timestamp = output_0.split("_")[2]
-    acro.rename_output(output_0, "cross_table")
-    output: dict = acro.finalise()
-    new_name = "cross_table" + "_" + timestamp
-    assert output_0 not in output
-    assert new_name in output
-
-    assert os.path.exists(f"outputs/{new_name}.csv") == 1
+    results: Record = acro.finalise()
+    output_0 = results.get_index(0)
+    orig_name = output_0.uid
+    new_name = "cross_table"
+    acro.rename_output(orig_name, new_name)
+    results = acro.finalise()
+    assert output_0.uid == new_name
+    assert orig_name not in results.get_keys()
+    assert os.path.exists(f"outputs/{new_name}_0.csv")
+    # rename an output that doesn't exist
+    with pytest.warns(UserWarning):
+        acro.rename_output("123", "name")
 
 
 def test_add_comments(data, acro):
     """Adding comments to output test"""
     _ = acro.crosstab(data.year, data.grant_type)
-    output: dict = acro.finalise()
-    output_0 = list(output.keys())[0]
-    assert output[output_0]["comments"] == ""
+    results: Record = acro.finalise()
+    output_0 = results.get_index(0)
+    assert output_0.comments == []
     comment = "This is a cross table between year and grant_type"
-    acro.add_comments(output_0, comment)
-    assert output[output_0]["comments"] == comment
+    acro.add_comments(output_0.uid, comment)
+    assert output_0.comments == [comment]
     comment_1 = "6 cells were suppressed"
-    acro.add_comments(output_0, comment_1)
-    assert output[output_0]["comments"] == comment + ", " + comment_1
+    acro.add_comments(output_0.uid, comment_1)
+    assert output_0.comments == [comment, comment_1]
+    # add a comment to something that is not there
+    with pytest.warns(UserWarning):
+        acro.add_comments("123", "comment")
 
 
 def test_custom_output(acro):
     """Adding an unsupported output to the results dictionary test"""
-    filename = "XandY.jfif"
-    file_path = os.path.abspath(filename)
+    save_path = "RES_PYTEST"
+    filename = "notebooks/XandY.jfif"
+    file_path = os.path.normpath(filename)
     acro.custom_output(filename)
-    output: dict = acro.finalise()
-    output_0 = list(output.keys())[0]
-    assert output[output_0]["output"] == file_path
+    results: Records = acro.finalise(path=save_path)
+    output_0 = results.get_index(0)
+    assert output_0.output == file_path
+    assert os.path.exists(os.path.normpath(f"{save_path}/XandY.jfif"))
 
 
 def test_missing(data, acro):
     """Pivot table and Crosstab with negative values."""
     utils.CHECK_MISSING_VALUES = True
     data.loc[0:10, "inc_grants"] = np.NaN
     _ = acro.crosstab(
         data.year, data.grant_type, values=data.inc_grants, aggfunc="mean"
     )
     _ = acro.pivot_table(
         data, index=["grant_type"], values=["inc_grants"], aggfunc=["mean", "std"]
     )
-    output: dict = acro.finalise()
+    results: Records = acro.finalise()
     correct_summary: str = "review; missing values found"
-    output_0 = list(output.keys())[0]
-    output_1 = list(output.keys())[1]
-    assert output[output_0]["summary"] == correct_summary
-    assert output[output_1]["summary"] == correct_summary
+    output_0 = results.get_index(0)
+    output_1 = results.get_index(1)
+    assert output_0.summary == correct_summary
+    assert output_1.summary == correct_summary
 
 
 def test_suppression_error(caplog):
     """Apply suppression type error test."""
     table_data = {"col1": [1, 2], "col2": [3, 4]}
     mask_data = {"col1": [np.NaN, True], "col2": [True, True]}
     table = pd.DataFrame(data=table_data)
```


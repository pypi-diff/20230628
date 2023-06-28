# Comparing `tmp/enfobench-0.1.1.tar.gz` & `tmp/enfobench-0.2.2.tar.gz`

## Comparing `enfobench-0.1.1.tar` & `enfobench-0.2.2.tar`

### file list

```diff
@@ -1,22 +1,26 @@
--rw-r--r--   0        0        0     3454 2020-02-02 00:00:00.000000 enfobench-0.1.1/Makefile
--rw-r--r--   0        0        0     3533 2020-02-02 00:00:00.000000 enfobench-0.1.1/README.md
--rw-r--r--   0        0        0     3194 2020-02-02 00:00:00.000000 enfobench-0.1.1/pyproject.toml
--rw-r--r--   0        0        0       67 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/__init__.py
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/__version__.py
--rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/py.typed
--rw-r--r--   0        0        0      313 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/utils.py
--rw-r--r--   0        0        0      242 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/__init__.py
--rw-r--r--   0        0        0     2485 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/_cross_validate.py
--rw-r--r--   0        0        0     2395 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/_evaluate.py
--rw-r--r--   0        0        0     1807 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/client.py
--rw-r--r--   0        0        0     3849 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/metrics.py
--rw-r--r--   0        0        0      699 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/protocols.py
--rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 enfobench-0.1.1/src/enfobench/evaluation/server.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 enfobench-0.1.1/tests/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 enfobench-0.1.1/tests/conftest.py
--rw-r--r--   0        0        0     1710 2020-02-02 00:00:00.000000 enfobench-0.1.1/tests/test_metrics.py
--rw-r--r--   0        0        0     3319 2020-02-02 00:00:00.000000 enfobench-0.1.1/.gitignore
--rw-r--r--   0        0        0     1596 2020-02-02 00:00:00.000000 enfobench-0.1.1/LICENCE
--rw-r--r--   0        0        0     3533 2020-02-02 00:00:00.000000 enfobench-0.1.1/README.md
--rw-r--r--   0        0        0     3194 2020-02-02 00:00:00.000000 enfobench-0.1.1/pyproject.toml
--rw-r--r--   0        0        0     5173 2020-02-02 00:00:00.000000 enfobench-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     3488 2020-02-02 00:00:00.000000 enfobench-0.2.2/Makefile
+-rw-r--r--   0        0        0     3637 2020-02-02 00:00:00.000000 enfobench-0.2.2/README.md
+-rw-r--r--   0        0        0     3215 2020-02-02 00:00:00.000000 enfobench-0.2.2/pyproject.toml
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/__init__.py
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/__version__.py
+-rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/py.typed
+-rw-r--r--   0        0        0      326 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/__init__.py
+-rw-r--r--   0        0        0     2147 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/client.py
+-rw-r--r--   0        0        0     6333 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/evaluate.py
+-rw-r--r--   0        0        0     3849 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/metrics.py
+-rw-r--r--   0        0        0     6098 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/protocols.py
+-rw-r--r--   0        0        0     2029 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/server.py
+-rw-r--r--   0        0        0     2725 2020-02-02 00:00:00.000000 enfobench-0.2.2/src/enfobench/evaluation/utils.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/__init__.py
+-rw-r--r--   0        0        0     2189 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/conftest.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/test_evaluations/__init__.py
+-rw-r--r--   0        0        0     4364 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/test_evaluations/test_dataset.py
+-rw-r--r--   0        0        0     4729 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/test_evaluations/test_evaluate.py
+-rw-r--r--   0        0        0     1710 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/test_evaluations/test_metrics.py
+-rw-r--r--   0        0        0     1944 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/test_evaluations/test_server.py
+-rw-r--r--   0        0        0     1411 2020-02-02 00:00:00.000000 enfobench-0.2.2/tests/test_evaluations/test_utils.py
+-rw-r--r--   0        0        0     3319 2020-02-02 00:00:00.000000 enfobench-0.2.2/.gitignore
+-rw-r--r--   0        0        0     1596 2020-02-02 00:00:00.000000 enfobench-0.2.2/LICENCE
+-rw-r--r--   0        0        0     3637 2020-02-02 00:00:00.000000 enfobench-0.2.2/README.md
+-rw-r--r--   0        0        0     3215 2020-02-02 00:00:00.000000 enfobench-0.2.2/pyproject.toml
+-rw-r--r--   0        0        0     5323 2020-02-02 00:00:00.000000 enfobench-0.2.2/PKG-INFO
```

### Comparing `enfobench-0.1.1/Makefile` & `enfobench-0.2.2/Makefile`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-.PHONY: install clean lint format tests
+.PHONY: install clean format lint tests build publish publish-test
 
 #################################################################################
 # GLOBALS                                                                       #
 #################################################################################
 
 PROJECT_DIR := $(shell dirname $(realpath $(lastword $(MAKEFILE_LIST))))
 PROJECT_NAME = energy-forecat-benchmark-toolkit
@@ -19,27 +19,27 @@
 	mypy --install-types
 
 ## Delete all compiled Python files
 clean:
 	find . -type f -name "*.py[co]" -delete
 	find . -type d -name "__pycache__" -delete
 
-## Lint using ruff, mypy, black, and isort
-lint:
-	mypy src
-	ruff src tests
-	black src tests --check
-	isort src tests --check-only
-
 ## Format using black
 format:
 	ruff src tests --fix
 	black src tests
 	isort src tests
 
+## Lint using ruff, mypy, black, and isort
+lint: format
+	mypy src
+	ruff src tests
+	black src tests --check
+	isort src tests --check-only
+
 ## Run pytest with coverage
 tests:
 	pytest src tests
 
 #################################################################################
 # PROJECT RULES                                                                 #
 #################################################################################
```

### Comparing `enfobench-0.1.1/README.md` & `enfobench-0.2.2/README.md`

 * *Files 23% similar despite different names*

```diff
@@ -23,77 +23,81 @@
 
 ```bash
 pip install enfobench
 ```
 
 ## Usage
 
-Import your dataset and make sure that the timestamp column in named 'ds' and the target values named 'y'.
+Load your own data and create a dataset.
 
 ```python
 import pandas as pd
 
+from enfobench.evaluation import Dataset
+
 # Load your dataset and make sure that the timestamp column in named 'ds' and the target values named 'y'
-data = (
-    pd.read_csv("../path/to/your/data.csv")
-    .rename(columns={"timestamp": "ds", "value": "y"})
+data = pd.read_csv("../path/to/your/data.csv", parse_dates=['timestamp'], index_col='timestamp')
+covariates = data.drop(columns=['target_column'])
+
+dataset = Dataset(
+    target=data['target_column'],
+    covariates=covariates,
 )
-y = data.set_index("ds")["y"]
 ```
 
 You can perform a cross validation on any model locally that adheres to the `enfobench.Model` protocol.
 
 ```python
 import MyModel
 from enfobench.evaluation import cross_validate
 
 # Import your model and instantiate it
 model = MyModel()
 
 # Run cross validation on your model
 cv_results = cross_validate(
     model,
-    start=pd.Timestamp("2018-01-01"),
-    end=pd.Timestamp("2018-01-31"),
+    dataset,
+    start_date=pd.Timestamp("2018-01-01"),
+    end_date=pd.Timestamp("2018-01-31"),
     horizon=pd.Timedelta("24 hours"),
     step=pd.Timedelta("1 day"),
-    y=y,
 )
 ```
 
 You can use the same crossvalidation interface with your model served behind an API.
 
 ```python
 from enfobench.evaluation import cross_validate, ForecastClient
 
 # Import your model and instantiate it
 client = ForecastClient(host='localhost', port=3000)
 
 # Run cross validation on your model
 cv_results = cross_validate(
     client,
-    start=pd.Timestamp("2018-01-01"),
-    end=pd.Timestamp("2018-01-31"),
+    dataset,
+    start_date=pd.Timestamp("2018-01-01"),
+    end_date=pd.Timestamp("2018-01-31"),
     horizon=pd.Timedelta("24 hours"),
     step=pd.Timedelta("1 day"),
-    y=y,
 )
 ```
 
 The package also collects common metrics for you that you can quickly evaluate on your results.
 
 ```python
 from enfobench.evaluation import evaluate_metrics_on_forecasts
 
 from enfobench.evaluation.metrics import (
     mean_bias_error, mean_absolute_error, mean_squared_error, root_mean_squared_error,
 )
 
 # Merge the cross validation results with the original data
-forecasts = cv_results.merge(data, on="ds", how="left")
+forecasts = cv_results.merge(dataset.target, on="ds", how="left")
 
 metrics = evaluate_metrics_on_forecasts(
     forecasts,
     metrics={
         "mean_bias_error": mean_bias_error,
         "mean_absolute_error": mean_absolute_error,
         "mean_squared_error": mean_squared_error,
```

### Comparing `enfobench-0.1.1/pyproject.toml` & `enfobench-0.2.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -41,14 +41,15 @@
 [project.urls]
 "Homepage" = "https://github.com/attila-balint-kul/energy-forecast-benchmark-toolkit"
 
 [project.optional-dependencies]
 test = [
     "black==23.3.0",
     "isort==5.12.0",
+    "httpx==0.24.1",
     "mypy==1.4.0",
     "ruff==0.0.274",
     "pytest==7.3.2",
 ]
 dev = [
     "twine>=4.0.0,<5.0.0",
     "pre-commit>=3.0.0,<4.0.0",
```

### Comparing `enfobench-0.1.1/src/enfobench/evaluation/client.py` & `enfobench-0.2.2/src/enfobench/evaluation/client.py`

 * *Files 21% similar despite different names*

```diff
@@ -11,55 +11,60 @@
     buffer = io.BytesIO()
     df.to_parquet(buffer, index=False)
     buffer.seek(0)
     return buffer
 
 
 class ForecastClient:
-    def __init__(self, host: str = "localhost", port: int = 3000, secure: bool = False):
+    def __init__(
+        self, host: str = "localhost", port: int = 3000, secure: bool = False, client=None
+    ):
         self.base_url = f"{'https' if secure else 'http'}://{host}:{port}"
-        self.session = requests.Session()
+        self._session = requests.Session() if client is None else client
 
     def info(self) -> ModelInfo:
-        response = self.session.get(f"{self.base_url}/info")
-        if not response.ok:
+        response = self._session.get(f"{self.base_url}/info")
+        if response.status_code != 200:
             response.raise_for_status()
 
         return ModelInfo(**response.json())
 
     def environment(self) -> EnvironmentInfo:
-        response = self.session.get(f"{self.base_url}/environment")
-        if not response.ok:
+        response = self._session.get(f"{self.base_url}/environment")
+        if response.status_code != 200:
             response.raise_for_status()
 
         return EnvironmentInfo(**response.json())
 
-    def predict(
+    def forecast(
         self,
         horizon: int,
-        y: pd.Series,
-        # X: pd.DataFrame,
+        history: pd.DataFrame,
+        past_covariates: Optional[pd.DataFrame] = None,
+        future_covariates: Optional[pd.DataFrame] = None,
         level: Optional[List[int]] = None,
     ) -> pd.DataFrame:
         params: Dict[str, Union[int, List[int]]] = {
             "horizon": horizon,
         }
         if level is not None:
             params["level"] = level
 
-        y_df = y.rename_axis("ds").reset_index()
         files = {
-            "y": to_buffer(y_df),
-            # "X": to_buffer(X),
+            "history": to_buffer(history),
         }
+        if past_covariates is not None:
+            files["past_covariates"] = to_buffer(past_covariates)
+        if future_covariates is not None:
+            files["future_covariates"] = to_buffer(future_covariates)
 
-        response = self.session.post(
-            url=f"{self.base_url}/predict",
+        response = self._session.post(
+            url=f"{self.base_url}/forecast",
             params=params,
             files=files,
         )
-        if not response.ok:
+        if response.status_code != 200:
             response.raise_for_status()
 
         df = pd.DataFrame.from_records(response.json()["forecast"])
         df["ds"] = pd.to_datetime(df["ds"])
         return df
```

### Comparing `enfobench-0.1.1/src/enfobench/evaluation/metrics.py` & `enfobench-0.2.2/src/enfobench/evaluation/metrics.py`

 * *Files identical despite different names*

### Comparing `enfobench-0.1.1/tests/test_metrics.py` & `enfobench-0.2.2/tests/test_evaluations/test_metrics.py`

 * *Files identical despite different names*

### Comparing `enfobench-0.1.1/.gitignore` & `enfobench-0.2.2/.gitignore`

 * *Files identical despite different names*

### Comparing `enfobench-0.1.1/LICENCE` & `enfobench-0.2.2/LICENCE`

 * *Files identical despite different names*

### Comparing `enfobench-0.1.1/PKG-INFO` & `enfobench-0.2.2/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: enfobench
-Version: 0.1.1
+Version: 0.2.2
 Summary: Energy forecast benchmarking toolkit.
 Project-URL: Homepage, https://github.com/attila-balint-kul/energy-forecast-benchmark-toolkit
 Author-email: attila.balint@kuleuven.be
 License-File: LICENCE
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: BSD License
@@ -28,14 +28,15 @@
 Requires-Dist: tqdm<5.0.0,>=4.60.0
 Requires-Dist: uvicorn<1.0.0,>=0.20.0
 Provides-Extra: dev
 Requires-Dist: pre-commit<4.0.0,>=3.0.0; extra == 'dev'
 Requires-Dist: twine<5.0.0,>=4.0.0; extra == 'dev'
 Provides-Extra: test
 Requires-Dist: black==23.3.0; extra == 'test'
+Requires-Dist: httpx==0.24.1; extra == 'test'
 Requires-Dist: isort==5.12.0; extra == 'test'
 Requires-Dist: mypy==1.4.0; extra == 'test'
 Requires-Dist: pytest==7.3.2; extra == 'test'
 Requires-Dist: ruff==0.0.274; extra == 'test'
 Description-Content-Type: text/markdown
 
 Energy  Forecast Benchmark Toolkit
@@ -63,77 +64,81 @@
 
 ```bash
 pip install enfobench
 ```
 
 ## Usage
 
-Import your dataset and make sure that the timestamp column in named 'ds' and the target values named 'y'.
+Load your own data and create a dataset.
 
 ```python
 import pandas as pd
 
+from enfobench.evaluation import Dataset
+
 # Load your dataset and make sure that the timestamp column in named 'ds' and the target values named 'y'
-data = (
-    pd.read_csv("../path/to/your/data.csv")
-    .rename(columns={"timestamp": "ds", "value": "y"})
+data = pd.read_csv("../path/to/your/data.csv", parse_dates=['timestamp'], index_col='timestamp')
+covariates = data.drop(columns=['target_column'])
+
+dataset = Dataset(
+    target=data['target_column'],
+    covariates=covariates,
 )
-y = data.set_index("ds")["y"]
 ```
 
 You can perform a cross validation on any model locally that adheres to the `enfobench.Model` protocol.
 
 ```python
 import MyModel
 from enfobench.evaluation import cross_validate
 
 # Import your model and instantiate it
 model = MyModel()
 
 # Run cross validation on your model
 cv_results = cross_validate(
     model,
-    start=pd.Timestamp("2018-01-01"),
-    end=pd.Timestamp("2018-01-31"),
+    dataset,
+    start_date=pd.Timestamp("2018-01-01"),
+    end_date=pd.Timestamp("2018-01-31"),
     horizon=pd.Timedelta("24 hours"),
     step=pd.Timedelta("1 day"),
-    y=y,
 )
 ```
 
 You can use the same crossvalidation interface with your model served behind an API.
 
 ```python
 from enfobench.evaluation import cross_validate, ForecastClient
 
 # Import your model and instantiate it
 client = ForecastClient(host='localhost', port=3000)
 
 # Run cross validation on your model
 cv_results = cross_validate(
     client,
-    start=pd.Timestamp("2018-01-01"),
-    end=pd.Timestamp("2018-01-31"),
+    dataset,
+    start_date=pd.Timestamp("2018-01-01"),
+    end_date=pd.Timestamp("2018-01-31"),
     horizon=pd.Timedelta("24 hours"),
     step=pd.Timedelta("1 day"),
-    y=y,
 )
 ```
 
 The package also collects common metrics for you that you can quickly evaluate on your results.
 
 ```python
 from enfobench.evaluation import evaluate_metrics_on_forecasts
 
 from enfobench.evaluation.metrics import (
     mean_bias_error, mean_absolute_error, mean_squared_error, root_mean_squared_error,
 )
 
 # Merge the cross validation results with the original data
-forecasts = cv_results.merge(data, on="ds", how="left")
+forecasts = cv_results.merge(dataset.target, on="ds", how="left")
 
 metrics = evaluate_metrics_on_forecasts(
     forecasts,
     metrics={
         "mean_bias_error": mean_bias_error,
         "mean_absolute_error": mean_absolute_error,
         "mean_squared_error": mean_squared_error,
```


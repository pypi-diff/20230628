# Comparing `tmp/mozilla_nimbus_schemas-2023.6.5.tar.gz` & `tmp/mozilla_nimbus_schemas-2023.6.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mozilla_nimbus_schemas-2023.6.5.tar", max compression
+gzip compressed data, was "mozilla_nimbus_schemas-2023.6.6.tar", max compression
```

## Comparing `mozilla_nimbus_schemas-2023.6.5.tar` & `mozilla_nimbus_schemas-2023.6.6.tar`

### file list

```diff
@@ -1,13 +1,13 @@
--rw-r--r--   0        0        0    16725 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/LICENSE
--rw-r--r--   0        0        0      839 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/README.md
--rw-r--r--   0        0        0        0 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/__init__.py
--rw-r--r--   0        0        0      365 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/__init__.py
--rw-r--r--   0        0        0      624 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/analysis_errors.py
--rw-r--r--   0        0        0     1591 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/metadata.py
--rw-r--r--   0        0        0      753 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/statistics.py
--rw-r--r--   0        0        0     4646 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/tests/jetstream/test_analysis_errors.py
--rw-r--r--   0        0        0     2266 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/tests/jetstream/test_metadata.py
--rw-r--r--   0        0        0     2521 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/tests/jetstream/test_statistics.py
--rw-r--r--   0        0        0     1043 2023-06-23 13:07:51.801154 mozilla_nimbus_schemas-2023.6.5/pyproject.toml
--rw-r--r--   0        0        0     1598 1970-01-01 00:00:00.000000 mozilla_nimbus_schemas-2023.6.5/setup.py
--rw-r--r--   0        0        0     1317 1970-01-01 00:00:00.000000 mozilla_nimbus_schemas-2023.6.5/PKG-INFO
+-rw-r--r--   0        0        0    16725 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/LICENSE
+-rw-r--r--   0        0        0      839 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/__init__.py
+-rw-r--r--   0        0        0      365 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/__init__.py
+-rw-r--r--   0        0        0      624 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/analysis_errors.py
+-rw-r--r--   0        0        0     1591 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/metadata.py
+-rw-r--r--   0        0        0      753 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/statistics.py
+-rw-r--r--   0        0        0     4646 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/tests/jetstream/test_analysis_errors.py
+-rw-r--r--   0        0        0     2266 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/tests/jetstream/test_metadata.py
+-rw-r--r--   0        0        0     2521 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/tests/jetstream/test_statistics.py
+-rw-r--r--   0        0        0     1043 2023-06-28 14:42:11.404108 mozilla_nimbus_schemas-2023.6.6/pyproject.toml
+-rw-r--r--   0        0        0     1598 1970-01-01 00:00:00.000000 mozilla_nimbus_schemas-2023.6.6/setup.py
+-rw-r--r--   0        0        0     1317 1970-01-01 00:00:00.000000 mozilla_nimbus_schemas-2023.6.6/PKG-INFO
```

### Comparing `mozilla_nimbus_schemas-2023.6.5/LICENSE` & `mozilla_nimbus_schemas-2023.6.6/LICENSE`

 * *Files identical despite different names*

### Comparing `mozilla_nimbus_schemas-2023.6.5/README.md` & `mozilla_nimbus_schemas-2023.6.6/README.md`

 * *Files identical despite different names*

### Comparing `mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/analysis_errors.py` & `mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/analysis_errors.py`

 * *Files identical despite different names*

### Comparing `mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/metadata.py` & `mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/metadata.py`

 * *Files identical despite different names*

### Comparing `mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/jetstream/statistics.py` & `mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/jetstream/statistics.py`

 * *Files 5% similar despite different names*

```diff
@@ -3,16 +3,16 @@
 
 from pydantic import BaseModel, Field
 
 SCHEMA_VERSION = 4
 
 
 class AnalysisBasis(str, Enum):
-    enrollments = "enrollments"
-    exposures = "exposures"
+    ENROLLMENTS = "enrollments"
+    EXPOSURES = "exposures"
 
 
 class Statistic(BaseModel):
     metric: str
     statistic: str
     branch: str
     parameter: Optional[float] = None
```

### Comparing `mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/tests/jetstream/test_analysis_errors.py` & `mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/tests/jetstream/test_analysis_errors.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,29 +11,29 @@
 Test cases for analysis errors schemas:
 - AnalysisError, AnalysisErrors
 """
 
 
 def test_analysis_errors():
     ae0 = AnalysisError(
-        analysis_basis=AnalysisBasis.enrollments,
+        analysis_basis=AnalysisBasis.ENROLLMENTS,
         exception="(<class 'errors.TestException'>, TestException('err')",
         exception_type="EnrollmentNotCompleteException",
         experiment="test-experiment-slug",
         filename="cli.py",
         func_name="execute",
         log_level="ERROR",
         message="test-experiment-slug -> Test error.",
         metric="test-metric",
         segment="test-segment",
         statistic="test-statistic",
         timestamp="2023-05-17T06:42:31+00:00",
     )
     ae1 = AnalysisError(
-        analysis_basis=AnalysisBasis.exposures,
+        analysis_basis=AnalysisBasis.EXPOSURES,
         exception="(<class 'errors.TestException'>, TestException('err')",
         exception_type="EnrollmentNotCompleteException",
         experiment="test-experiment-slug",
         filename="cli.py",
         func_name="execute",
         log_level="ERROR",
         message="test-experiment-slug -> Test error.",
```

### Comparing `mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/tests/jetstream/test_metadata.py` & `mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/tests/jetstream/test_metadata.py`

 * *Files identical despite different names*

### Comparing `mozilla_nimbus_schemas-2023.6.5/mozilla_nimbus_schemas/tests/jetstream/test_statistics.py` & `mozilla_nimbus_schemas-2023.6.6/mozilla_nimbus_schemas/tests/jetstream/test_statistics.py`

 * *Files 16% similar despite different names*

```diff
@@ -11,37 +11,37 @@
         metric="test-metric",
         statistic="test-statistic",
         branch="test-branch",
         ci_width=0.95,
         point=1.0,
         lower=0.2,
         upper=1.2,
-        analysis_basis=AnalysisBasis.enrollments,
+        analysis_basis=AnalysisBasis.ENROLLMENTS,
         window_index="1",
     )
     s1 = Statistic(
         metric="test-metric",
         statistic="test-statistic",
         branch="test-branch",
         ci_width=0.95,
         point=1.0,
         lower=0.2,
         upper=1.2,
-        analysis_basis=AnalysisBasis.enrollments,
+        analysis_basis=AnalysisBasis.ENROLLMENTS,
         window_index="1",
     )
     s2 = Statistic(
         metric="test-metric",
         statistic="test-statistic",
         branch="test-branch",
         ci_width=0.95,
         point=1.0,
         lower=0.2,
         upper=1.2,
-        analysis_basis=AnalysisBasis.enrollments,
+        analysis_basis=AnalysisBasis.ENROLLMENTS,
         window_index="1",
     )
 
     stats = Statistics.parse_obj([s0, s1])
     assert type(stats) == Statistics
     assert len(stats.__root__) == 2
     stats.__root__.append(s2)
```

### Comparing `mozilla_nimbus_schemas-2023.6.5/pyproject.toml` & `mozilla_nimbus_schemas-2023.6.6/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "mozilla-nimbus-schemas"
-version = "2023.6.5"
+version = "2023.6.6"
 description = "Schemas used by Mozilla Nimbus and related projects."
 authors = ["mikewilli"]
 license = "MPL 2.0"
 readme = "README.md"
 packages = [{include = "mozilla_nimbus_schemas"}]
 
 [tool.poetry.dependencies]
```

### Comparing `mozilla_nimbus_schemas-2023.6.5/setup.py` & `mozilla_nimbus_schemas-2023.6.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 {'': ['*']}
 
 install_requires = \
 ['pydantic>=1.10.7,<2.0.0']
 
 setup_kwargs = {
     'name': 'mozilla-nimbus-schemas',
-    'version': '2023.6.5',
+    'version': '2023.6.6',
     'description': 'Schemas used by Mozilla Nimbus and related projects.',
     'long_description': '# Nimbus Schemas\n\nThis directory contains a published package of schemas used by different parts of the Mozilla Nimbus experimentation ecosystem.\n\n## Versioning\n`mozilla-nimbus-schemas` uses a date-based versioning scheme. The format is `yyyy.m.#`, where `m` is the non-zero-padded month, and `#` is an incrementing number starting from 1 for each month. For example, the second release in June of 2023 would have a version of `2023.6.2`.\n\n## Installation/Usage\n### Prerequisites\n- python ^3.10\n- poetry ^1.2.2\n\nFrom project root (i.e., parent to this directory)\n- Install: `make schemas_install`\n- Run linting and tests: `make schemas_check`\n- Code formatting: `make schemas_code_format`\n\n## Schemas\n### Jetstream\n\nContains schemas describing analysis results, metadata, and errors from [Jetstream](https://github.com/mozilla/jetstream).\n',
     'author': 'mikewilli',
     'author_email': 'None',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `mozilla_nimbus_schemas-2023.6.5/PKG-INFO` & `mozilla_nimbus_schemas-2023.6.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mozilla-nimbus-schemas
-Version: 2023.6.5
+Version: 2023.6.6
 Summary: Schemas used by Mozilla Nimbus and related projects.
 License: MPL 2.0
 Author: mikewilli
 Requires-Python: >=3.10,<4.0
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
```


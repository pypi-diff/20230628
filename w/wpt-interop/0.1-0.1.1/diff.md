# Comparing `tmp/wpt_interop-0.1.tar.gz` & `tmp/wpt_interop-0.1.1.tar.gz`

## Comparing `wpt_interop-0.1.tar` & `wpt_interop-0.1.1.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0      241 1970-01-01 00:00:00.000000 wpt_interop-0.1/local_dependencies/wpt-interop/Cargo.toml
--rw-r--r--   0     1001      123      305 2023-06-13 08:25:22.000000 wpt_interop-0.1/local_dependencies/wpt-interop/README.md
--rw-r--r--   0     1001      123     6152 2023-06-13 08:25:22.000000 wpt_interop-0.1/local_dependencies/wpt-interop/src/lib.rs
--rw-r--r--   0        0        0      311 1970-01-01 00:00:00.000000 wpt_interop-0.1/Cargo.toml
--rw-r--r--   0     1001      123      143 2023-06-13 08:25:22.000000 wpt_interop-0.1/README.md
--rw-r--r--   0     1001      123      635 2023-06-13 08:25:22.000000 wpt_interop-0.1/pyproject.toml
--rw-r--r--   0     1001      123        1 2023-06-13 08:25:22.000000 wpt_interop-0.1/python/wpt_interop/__init__.py
--rw-r--r--   0     1001      123     3557 2023-06-13 08:25:22.000000 wpt_interop-0.1/python/wpt_interop/score.py
--rw-r--r--   0     1001      123     1952 2023-06-13 08:25:22.000000 wpt_interop-0.1/src/lib.rs
--rw-r--r--   0     1001      123     7495 2023-06-13 08:27:39.000000 wpt_interop-0.1/Cargo.lock
--rw-r--r--   0        0        0      545 1970-01-01 00:00:00.000000 wpt_interop-0.1/PKG-INFO
+-rw-r--r--   0        0        0      241 1970-01-01 00:00:00.000000 wpt_interop-0.1.1/local_dependencies/wpt-interop/Cargo.toml
+-rw-r--r--   0     1001      123      305 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/local_dependencies/wpt-interop/README.md
+-rw-r--r--   0     1001      123     6152 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/local_dependencies/wpt-interop/src/lib.rs
+-rw-r--r--   0        0        0      311 1970-01-01 00:00:00.000000 wpt_interop-0.1.1/Cargo.toml
+-rw-r--r--   0     1001      123      143 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/README.md
+-rw-r--r--   0     1001      123      637 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/pyproject.toml
+-rw-r--r--   0     1001      123        1 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/python/wpt_interop/__init__.py
+-rw-r--r--   0     1001      123     4435 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/python/wpt_interop/score.py
+-rw-r--r--   0     1001      123     1952 2023-06-28 15:31:18.000000 wpt_interop-0.1.1/src/lib.rs
+-rw-r--r--   0     1001      123     7495 2023-06-28 15:31:23.000000 wpt_interop-0.1.1/Cargo.lock
+-rw-r--r--   0        0        0      547 1970-01-01 00:00:00.000000 wpt_interop-0.1.1/PKG-INFO
```

### Comparing `wpt_interop-0.1/local_dependencies/wpt-interop/src/lib.rs` & `wpt_interop-0.1.1/local_dependencies/wpt-interop/src/lib.rs`

 * *Files identical despite different names*

### Comparing `wpt_interop-0.1/pyproject.toml` & `wpt_interop-0.1.1/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 [project]
 name = "wpt-interop"
 requires-python = ">=3.7"
 description = "web-platform-tests Interop Project helpers"
 author = "James Graham"
 author_email = "james@hoppipolla.co.uk"
 license = "BSD-3-Clause"
-version = "0.1"
+version = "0.1.1"
 classifiers = [
     "Programming Language :: Rust",
     "Programming Language :: Python :: Implementation :: CPython",
     "Programming Language :: Python :: Implementation :: PyPy",
 ]
 install_requires = [
   "requests"
```

### Comparing `wpt_interop-0.1/python/wpt_interop/score.py` & `wpt_interop-0.1.1/python/wpt_interop/score.py`

 * *Files 22% similar despite different names*

```diff
@@ -5,21 +5,26 @@
 from typing import Any, Callable, Iterable, List, Mapping, Optional, Set
 
 import requests
 
 from . import _wpt_interop  # type: ignore
 
 CATEGORY_URL = "https://raw.githubusercontent.com/web-platform-tests/results-analysis/main/interop-scoring/category-data.json"
+INTEROP_DATA_URL = "https://wpt.fyi/static/interop-data.json"
 METADATA_URL = "https://wpt.fyi/api/metadata?includeTestLevel=true&product=chrome"
 
 
 def fetch_category_data() -> Mapping[str, Mapping[str, Any]]:
     return requests.get(CATEGORY_URL).json()
 
 
+def fetch_interop_data() -> Mapping[str, Mapping[str, Any]]:
+    return requests.get(INTEROP_DATA_URL).json()
+
+
 def fetch_labelled_tests() -> Mapping[str, set]:
     rv = defaultdict(set)
     data = requests.get(METADATA_URL).json()
     for test, metadata in data.items():
         for meta_item in metadata:
             if "label" in meta_item:
                 rv[meta_item["label"]].add(test)
@@ -33,14 +38,25 @@
         # Check for magic number at the start of the file
         with open(path, "rb") as f:
             return f.read(2) == b"\x1f\x8b"
     except Exception:
         return False
 
 
+def categories_for_year(year: int,
+                        category_data: Mapping[str, Mapping[str, Any]],
+                        interop_data: Mapping[str, Mapping[str, Any]]) -> List[Mapping[str, Any]]:
+    year_key = str(year)
+    if year_key not in category_data or year_key not in interop_data:
+        raise ValueError(f"Invalid year {year}")
+    all_categories = category_data[year_key]["categories"]
+    year_categories = {key for key, value in interop_data[year_key]["focus_areas"].items() if value["countsTowardScore"]}
+    return [item for item in all_categories if item["name"] in year_categories]
+
+
 def load_wptreport(path: str) -> Mapping[str, Any]:
     rv = {}
     opener = gzip.GzipFile if is_gzip(path) else open
     with opener(path) as f:  # type: ignore
         try:
             data = json.load(f)
         except Exception as e:
@@ -81,17 +97,20 @@
 
     :param runs: A list/iterable with one item per run. Each item is a
     list of wptreport files for that run.
     :param year: Integer year for which to calculate interop scores.
     :param:
 
     """
-    categories = fetch_category_data()[str(year)]["categories"]
+    category_data = fetch_category_data()
+    interop_data = fetch_interop_data()
     labelled_tests = fetch_labelled_tests()
 
+    categories = categories_for_year(year, category_data, interop_data)
+
     tests_by_category = {}
     all_tests = set()
     for category in categories:
         if category_filter is not None and not category_filter(category["name"]):
             continue
         tests = set()
         for label in category["labels"]:
```

### Comparing `wpt_interop-0.1/src/lib.rs` & `wpt_interop-0.1.1/src/lib.rs`

 * *Files identical despite different names*

### Comparing `wpt_interop-0.1/Cargo.lock` & `wpt_interop-0.1.1/Cargo.lock`

 * *Files 2% similar despite different names*

```diff
@@ -24,17 +24,17 @@
 name = "indoc"
 version = "1.0.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "bfa799dd5ed20a7e349f3b4639aa80d74549c81716d9ec4f994c9b5815598306"
 
 [[package]]
 name = "libc"
-version = "0.2.146"
+version = "0.2.147"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "f92be4933c13fd498862a9e02a3055f8a8d9c039ce33db97306fd5a6caa7f29b"
+checksum = "b4668fb0ea861c1df094127ac5f1da3409a82116a4ba74fca2e58ef927159bb3"
 
 [[package]]
 name = "lock_api"
 version = "0.4.10"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "c1cc9717a20b1bb222f333e6a92fd32f7d8a18ddc5a3191a11af45dcbf4dcd16"
 dependencies = [
@@ -78,24 +78,24 @@
  "redox_syscall",
  "smallvec",
  "windows-targets",
 ]
 
 [[package]]
 name = "proc-macro2"
-version = "1.0.60"
+version = "1.0.63"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "dec2b086b7a862cf4de201096214fa870344cf922b2b30c167badb3af3195406"
+checksum = "7b368fba921b0dce7e60f5e04ec15e565b3303972b42bcfde1d0713b881959eb"
 dependencies = [
  "unicode-ident",
 ]
 
 [[package]]
 name = "py-wpt-interop"
-version = "0.1.0"
+version = "0.1.1"
 dependencies = [
  "pyo3",
  "wpt-interop",
 ]
 
 [[package]]
 name = "pyo3"
@@ -196,17 +196,17 @@
  "proc-macro2",
  "quote",
  "unicode-ident",
 ]
 
 [[package]]
 name = "target-lexicon"
-version = "0.12.7"
+version = "0.12.8"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "fd1ba337640d60c3e96bc6f0638a939b9c9a7f2c316a1598c279828b3d1dc8c5"
+checksum = "1b1c7f239eb94671427157bd93b3694320f3668d4e1eff08c7285366fd777fac"
 
 [[package]]
 name = "unicode-ident"
 version = "1.0.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "b15811caf2415fb889178633e7724bad2509101cde276048e013b9def5e51fa0"
```

### Comparing `wpt_interop-0.1/PKG-INFO` & `wpt_interop-0.1.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wpt-interop
-Version: 0.1
+Version: 0.1.1
 Classifier: Programming Language :: Rust
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Summary: web-platform-tests Interop Project helpers
 License: BSD-3-Clause
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown; charset=UTF-8; variant=GFM
```


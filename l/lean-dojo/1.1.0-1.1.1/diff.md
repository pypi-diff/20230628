# Comparing `tmp/lean_dojo-1.1.0.tar.gz` & `tmp/lean_dojo-1.1.1.tar.gz`

## Comparing `lean_dojo-1.1.0.tar` & `lean_dojo-1.1.1.tar`

### file list

```diff
@@ -1,35 +1,35 @@
--rw-r--r--   0        0        0      874 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/.readthedocs.yaml
--rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/mypy.ini
--rw-r--r--   0        0        0      711 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/__init__.py
--rw-r--r--   0        0        0     2549 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/constants.py
--rw-r--r--   0        0        0    11641 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/container.py
--rw-r--r--   0        0        0    11619 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/utils.py
--rw-r--r--   0        0        0    17589 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/0001-Modify-Lean-for-proof-recording.patch
--rw-r--r--   0        0        0    12065 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/ExtractData.lean
--rw-r--r--   0        0        0     5376 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/build_lean3_repo.py
--rw-r--r--   0        0        0     4699 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/build_lean4_repo.py
--rw-r--r--   0        0        0     3746 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/cache.py
--rw-r--r--   0        0        0    17785 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/lean.py
--rw-r--r--   0        0        0     6185 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/trace.py
--rw-r--r--   0        0        0    47904 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/traced_data.py
--rw-r--r--   0        0        0      390 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean3/ast_utils.py
--rw-r--r--   0        0        0    12503 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean3/expr.py
--rw-r--r--   0        0        0    74077 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean3/node.py
--rw-r--r--   0        0        0    26808 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean4/node.py
--rw-r--r--   0        0        0     8056 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/interaction/Lean4Repl.lean
--rw-r--r--   0        0        0    17727 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/interaction/dojo.py
--rw-r--r--   0        0        0    20967 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/src/lean_dojo/interaction/lean3_repl.lean
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/__init__.py
--rw-r--r--   0        0        0     2490 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/conftest.py
--rw-r--r--   0        0        0      390 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/data_extraction/test_trace.py
--rw-r--r--   0        0        0      634 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/interaction/test_env.py
--rw-r--r--   0        0        0    11463 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/interaction/test_examples.py
--rw-r--r--   0        0        0     1632 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/interaction/test_init_errors.py
--rw-r--r--   0        0        0      739 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/interaction/test_sorry.py
--rw-r--r--   0        0        0      978 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/interaction/test_timeout.py
--rw-r--r--   0        0        0     4364 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/tests/interaction/test_unexpected_errors.py
--rw-r--r--   0        0        0     1821 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/.gitignore
--rw-r--r--   0        0        0     1070 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/LICENSE
--rw-r--r--   0        0        0     4107 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/README.md
--rw-r--r--   0        0        0     1418 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/pyproject.toml
--rw-r--r--   0        0        0     6890 2020-02-02 00:00:00.000000 lean_dojo-1.1.0/PKG-INFO
+-rw-r--r--   0        0        0      874 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/.readthedocs.yaml
+-rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/mypy.ini
+-rw-r--r--   0        0        0      711 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/__init__.py
+-rw-r--r--   0        0        0     2549 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/constants.py
+-rw-r--r--   0        0        0    11641 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/container.py
+-rw-r--r--   0        0        0    11619 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/utils.py
+-rw-r--r--   0        0        0    17589 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/0001-Modify-Lean-for-proof-recording.patch
+-rw-r--r--   0        0        0    12065 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/ExtractData.lean
+-rw-r--r--   0        0        0     5376 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/build_lean3_repo.py
+-rw-r--r--   0        0        0     4699 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/build_lean4_repo.py
+-rw-r--r--   0        0        0     3758 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/cache.py
+-rw-r--r--   0        0        0    17785 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/lean.py
+-rw-r--r--   0        0        0     6185 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/trace.py
+-rw-r--r--   0        0        0    47904 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/traced_data.py
+-rw-r--r--   0        0        0      390 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean3/ast_utils.py
+-rw-r--r--   0        0        0    12503 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean3/expr.py
+-rw-r--r--   0        0        0    74077 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean3/node.py
+-rw-r--r--   0        0        0    26808 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean4/node.py
+-rw-r--r--   0        0        0     8056 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/interaction/Lean4Repl.lean
+-rw-r--r--   0        0        0    17727 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/interaction/dojo.py
+-rw-r--r--   0        0        0    20967 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/src/lean_dojo/interaction/lean3_repl.lean
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/__init__.py
+-rw-r--r--   0        0        0     2490 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/conftest.py
+-rw-r--r--   0        0        0      390 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/data_extraction/test_trace.py
+-rw-r--r--   0        0        0      634 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/interaction/test_env.py
+-rw-r--r--   0        0        0    11463 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/interaction/test_examples.py
+-rw-r--r--   0        0        0     1632 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/interaction/test_init_errors.py
+-rw-r--r--   0        0        0      739 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/interaction/test_sorry.py
+-rw-r--r--   0        0        0      978 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/interaction/test_timeout.py
+-rw-r--r--   0        0        0     4364 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/tests/interaction/test_unexpected_errors.py
+-rw-r--r--   0        0        0     1821 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/.gitignore
+-rw-r--r--   0        0        0     1070 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/LICENSE
+-rw-r--r--   0        0        0     4106 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/README.md
+-rw-r--r--   0        0        0     1418 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/pyproject.toml
+-rw-r--r--   0        0        0     6889 2020-02-02 00:00:00.000000 lean_dojo-1.1.1/PKG-INFO
```

### Comparing `lean_dojo-1.1.0/.readthedocs.yaml` & `lean_dojo-1.1.1/.readthedocs.yaml`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/__init__.py` & `lean_dojo-1.1.1/src/lean_dojo/__init__.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/constants.py` & `lean_dojo-1.1.1/src/lean_dojo/constants.py`

 * *Files 0% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 Many of them are configurable via :ref:`environment-variables`.
 """
 import os
 import multiprocessing
 from pathlib import Path
 
 
-__version__ = "1.1.0"
+__version__ = "1.1.1"
 
 CACHE_DIR = (
     Path(os.environ["CACHE_DIR"])
     if "CACHE_DIR" in os.environ
     else Path.home() / ".cache/lean_dojo"
 )
 """Cache directory for storing traced repos (see :ref:`caching`).
```

### Comparing `lean_dojo-1.1.0/src/lean_dojo/container.py` & `lean_dojo-1.1.1/src/lean_dojo/container.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/utils.py` & `lean_dojo-1.1.1/src/lean_dojo/utils.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/0001-Modify-Lean-for-proof-recording.patch` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/0001-Modify-Lean-for-proof-recording.patch`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/ExtractData.lean` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/ExtractData.lean`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/build_lean3_repo.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/build_lean3_repo.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/build_lean4_repo.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/build_lean4_repo.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/cache.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/cache.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,15 +46,15 @@
 
     def __iter__(self) -> Generator[Path, None, None]:
         """Iterate over all traced repos in the cache."""
         yield from self.cache_dir.glob("*")
 
     def __post_init__(self):
         if not os.path.exists(self.cache_dir):
-            self.cache_dir.mkdir()
+            self.cache_dir.mkdir(parents=True)
         lock_path = self.cache_dir.with_suffix(".lock")
         object.__setattr__(self, "lock", FileLock(lock_path))
 
     def get(self, url: str, commit: str) -> Optional[Path]:
         """Get the path of a traced repo with URL ``url`` and commit hash ``commit``. Return None if no such repo can be found."""
         _, repo_name = _split_git_url(url)
         dirname = _format_dirname(url, commit)
```

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/lean.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/lean.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/trace.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/trace.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/traced_data.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/traced_data.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean3/expr.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean3/expr.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean3/node.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean3/node.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/data_extraction/ast/lean4/node.py` & `lean_dojo-1.1.1/src/lean_dojo/data_extraction/ast/lean4/node.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/interaction/Lean4Repl.lean` & `lean_dojo-1.1.1/src/lean_dojo/interaction/Lean4Repl.lean`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/interaction/dojo.py` & `lean_dojo-1.1.1/src/lean_dojo/interaction/dojo.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/src/lean_dojo/interaction/lean3_repl.lean` & `lean_dojo-1.1.1/src/lean_dojo/interaction/lean3_repl.lean`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/conftest.py` & `lean_dojo-1.1.1/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/interaction/test_env.py` & `lean_dojo-1.1.1/tests/interaction/test_env.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/interaction/test_examples.py` & `lean_dojo-1.1.1/tests/interaction/test_examples.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/interaction/test_init_errors.py` & `lean_dojo-1.1.1/tests/interaction/test_init_errors.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/interaction/test_sorry.py` & `lean_dojo-1.1.1/tests/interaction/test_sorry.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/interaction/test_timeout.py` & `lean_dojo-1.1.1/tests/interaction/test_timeout.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/tests/interaction/test_unexpected_errors.py` & `lean_dojo-1.1.1/tests/interaction/test_unexpected_errors.py`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/.gitignore` & `lean_dojo-1.1.1/.gitignore`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/LICENSE` & `lean_dojo-1.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `lean_dojo-1.1.0/README.md` & `lean_dojo-1.1.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -47,16 +47,15 @@
 * To report a potential bug, please open an issue.
 
 
 ## Related Links
 
 * [LeanDojo Website](https://leandojo.org/): The official website of LeanDojo.
 * [LeanDojo Benchmark](https://zenodo.org/record/8016386) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8016386.svg)](https://doi.org/10.5281/zenodo.8016386): The dataset used in our paper, consisting of 96,962 theorems and proofs extracted from [mathlib](https://github.com/leanprover-community/mathlib/commits/8c1b484d6a214e059531e22f1be9898ed6c1fd47) by [generate-benchmark-lean3.ipynb](./scripts/generate-benchmark-lean3.ipynb). 
-* [LeanDojo Benchmark 4](https://zenodo.org/record/8040110) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8040110.svg)](https://doi.org/10.5281/zenodo.8040110)
-: The Lean 4 version of LeanDojo Benchmark, consisting of 91,766 theorems and proofs extracted from [mathlib4](https://github.com/leanprover-community/mathlib4/commit/5a919533f110b7d76410134a237ee374f24eaaad) by [generate-benchmark-lean4.ipynb](./scripts/generate-benchmark-lean4.ipynb).
+* [LeanDojo Benchmark 4](https://zenodo.org/record/8040110) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8040110.svg)](https://doi.org/10.5281/zenodo.8040110): The Lean 4 version of LeanDojo Benchmark, consisting of 91,766 theorems and proofs extracted from [mathlib4](https://github.com/leanprover-community/mathlib4/commit/5a919533f110b7d76410134a237ee374f24eaaad) by [generate-benchmark-lean4.ipynb](./scripts/generate-benchmark-lean4.ipynb).
 * [ReProver](https://github.com/lean-dojo/ReProver): The ReProver (Retrieval-Augmented Prover) model in our paper.
 * [LeanDojo ChatGPT Plugin](https://github.com/lean-dojo/LeanDojoChatGPT)
 
 
 ## Citation
 
 [LeanDojo: Theorem Proving with Retrieval-Augmented Language Models](https://arxiv.org/abs/xxxx.xxxxx)      
@@ -64,11 +63,11 @@
 [Kaiyu Yang](https://yangky11.github.io/), [Aidan Swope](https://aidanswope.com/about), [Alex Gu](https://minimario.github.io/), [Rahul Chalamala](https://rchalamala.github.io/),  
 [Peiyang Song](https://www.linkedin.com/in/peiyang-song-3279b3251/), [Shixing Yu](https://billysx.github.io/), [Saad Godil](https://www.linkedin.com/in/saad-godil-9728353/), [Ryan Prenger](https://www.linkedin.com/in/ryan-prenger-18797ba1/), [Anima Anandkumar](http://tensorlab.cms.caltech.edu/users/anima/)
 
 ```bibtex
 @article{yang2023leandojo,
   title={{LeanDojo}: Theorem Proving with Retrieval-Augmented Language Models},
   author={Yang, Kaiyu and Swope, Aidan and Gu, Alex and Chalamala, Rahul and Song, Peiyang and Yu, Shixing and Godil, Saad and Prenger, Ryan and Anandkumar, Anima},
-  journal={arXiv preprint arXiv:xxxx.xxxxx},
+  journal={arXiv preprint arXiv:2306.15626},
   year={2023}
 }
 ```
```

### Comparing `lean_dojo-1.1.0/pyproject.toml` & `lean_dojo-1.1.1/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -9,15 +9,15 @@
   "/docs",
   "/images",
   "/scripts",
 ]
 
 [project]
 name = "lean-dojo"
-version = "1.1.0"
+version = "1.1.1"
 authors = [
   { name="Kaiyu Yang", email="kaiyuy@caltech.edu" },
 ]
 description = "LeanDojo: Machine Learning for Theorem Proving in Lean"
 keywords = ["theorem proving", "machine learning", "Lean"]
 readme = "README.md"
 license = { file = "LICENSE" }
```

### Comparing `lean_dojo-1.1.0/PKG-INFO` & `lean_dojo-1.1.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lean-dojo
-Version: 1.1.0
+Version: 1.1.1
 Summary: LeanDojo: Machine Learning for Theorem Proving in Lean
 Project-URL: Homepage, https://leandojo.org/
 Project-URL: Bug Tracker, https://github.com/lean-dojo/LeanDojo/issues
 Author-email: Kaiyu Yang <kaiyuy@caltech.edu>
 License: MIT License
         
         Copyright (c) 2023 LeanDojo Team
@@ -113,16 +113,15 @@
 * To report a potential bug, please open an issue.
 
 
 ## Related Links
 
 * [LeanDojo Website](https://leandojo.org/): The official website of LeanDojo.
 * [LeanDojo Benchmark](https://zenodo.org/record/8016386) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8016386.svg)](https://doi.org/10.5281/zenodo.8016386): The dataset used in our paper, consisting of 96,962 theorems and proofs extracted from [mathlib](https://github.com/leanprover-community/mathlib/commits/8c1b484d6a214e059531e22f1be9898ed6c1fd47) by [generate-benchmark-lean3.ipynb](./scripts/generate-benchmark-lean3.ipynb). 
-* [LeanDojo Benchmark 4](https://zenodo.org/record/8040110) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8040110.svg)](https://doi.org/10.5281/zenodo.8040110)
-: The Lean 4 version of LeanDojo Benchmark, consisting of 91,766 theorems and proofs extracted from [mathlib4](https://github.com/leanprover-community/mathlib4/commit/5a919533f110b7d76410134a237ee374f24eaaad) by [generate-benchmark-lean4.ipynb](./scripts/generate-benchmark-lean4.ipynb).
+* [LeanDojo Benchmark 4](https://zenodo.org/record/8040110) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8040110.svg)](https://doi.org/10.5281/zenodo.8040110): The Lean 4 version of LeanDojo Benchmark, consisting of 91,766 theorems and proofs extracted from [mathlib4](https://github.com/leanprover-community/mathlib4/commit/5a919533f110b7d76410134a237ee374f24eaaad) by [generate-benchmark-lean4.ipynb](./scripts/generate-benchmark-lean4.ipynb).
 * [ReProver](https://github.com/lean-dojo/ReProver): The ReProver (Retrieval-Augmented Prover) model in our paper.
 * [LeanDojo ChatGPT Plugin](https://github.com/lean-dojo/LeanDojoChatGPT)
 
 
 ## Citation
 
 [LeanDojo: Theorem Proving with Retrieval-Augmented Language Models](https://arxiv.org/abs/xxxx.xxxxx)      
@@ -130,11 +129,11 @@
 [Kaiyu Yang](https://yangky11.github.io/), [Aidan Swope](https://aidanswope.com/about), [Alex Gu](https://minimario.github.io/), [Rahul Chalamala](https://rchalamala.github.io/),  
 [Peiyang Song](https://www.linkedin.com/in/peiyang-song-3279b3251/), [Shixing Yu](https://billysx.github.io/), [Saad Godil](https://www.linkedin.com/in/saad-godil-9728353/), [Ryan Prenger](https://www.linkedin.com/in/ryan-prenger-18797ba1/), [Anima Anandkumar](http://tensorlab.cms.caltech.edu/users/anima/)
 
 ```bibtex
 @article{yang2023leandojo,
   title={{LeanDojo}: Theorem Proving with Retrieval-Augmented Language Models},
   author={Yang, Kaiyu and Swope, Aidan and Gu, Alex and Chalamala, Rahul and Song, Peiyang and Yu, Shixing and Godil, Saad and Prenger, Ryan and Anandkumar, Anima},
-  journal={arXiv preprint arXiv:xxxx.xxxxx},
+  journal={arXiv preprint arXiv:2306.15626},
   year={2023}
 }
 ```
```


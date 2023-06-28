# Comparing `tmp/alpha_dom-0.1.3.tar.gz` & `tmp/alpha_dom-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "alpha_dom-0.1.3.tar", max compression
+gzip compressed data, was "alpha_dom-0.1.4.tar", max compression
```

## Comparing `alpha_dom-0.1.3.tar` & `alpha_dom-0.1.4.tar`

### file list

```diff
@@ -1,40 +1,40 @@
--rw-r--r--   0        0        0     1085 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/LICENSE
--rw-r--r--   0        0        0      340 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/README.md
--rw-r--r--   0        0        0      661 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/pyproject.toml
--rw-r--r--   0        0        0       82 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/__init__.py
--rw-r--r--   0        0        0      117 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/__main__.py
--rw-r--r--   0        0        0      339 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/cards/__init__.py
--rw-r--r--   0        0        0      200 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Artisan.json
--rw-r--r--   0        0        0      263 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Bandit.json
--rw-r--r--   0        0        0      285 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Bureaucrat.json
--rw-r--r--   0        0        0      177 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Cellar.json
--rw-r--r--   0        0        0      145 2023-06-26 01:51:24.612395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Chapel.json
--rw-r--r--   0        0        0      120 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Copper.json
--rw-r--r--   0        0        0      165 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Council Room.json
--rw-r--r--   0        0        0      125 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Curse.json
--rw-r--r--   0        0        0      128 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Duchy.json
--rw-r--r--   0        0        0      128 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Estate.json
--rw-r--r--   0        0        0      141 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Festival.json
--rw-r--r--   0        0        0      160 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Gardens.json
--rw-r--r--   0        0        0      118 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Gold.json
--rw-r--r--   0        0        0      207 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Harbinger.json
--rw-r--r--   0        0        0      221 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Library.json
--rw-r--r--   0        0        0      146 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Market.json
--rw-r--r--   0        0        0      184 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Merchant.json
--rw-r--r--   0        0        0      186 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Militia.json
--rw-r--r--   0        0        0      217 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Mine.json
--rw-r--r--   0        0        0      257 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Moat.json
--rw-r--r--   0        0        0      167 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Moneylender.json
--rw-r--r--   0        0        0      177 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Poacher.json
--rw-r--r--   0        0        0      131 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Province.json
--rw-r--r--   0        0        0      201 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Remodel.json
--rw-r--r--   0        0        0      255 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Sentry.json
--rw-r--r--   0        0        0      120 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Silver.json
--rw-r--r--   0        0        0      119 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Smithy.json
--rw-r--r--   0        0        0      165 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Throne Room.json
--rw-r--r--   0        0        0      195 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Vassal.json
--rw-r--r--   0        0        0      131 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Village.json
--rw-r--r--   0        0        0      170 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Witch.json
--rw-r--r--   0        0        0      146 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/expansions/base/Workshop.json
--rw-r--r--   0        0        0     3224 2023-06-26 01:51:24.616395 alpha_dom-0.1.3/python/alpha_dom/cards/model.py
--rw-r--r--   0        0        0      783 1970-01-01 00:00:00.000000 alpha_dom-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0     1085 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/LICENSE
+-rw-r--r--   0        0        0      340 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/README.md
+-rw-r--r--   0        0        0      710 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0       82 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/__init__.py
+-rw-r--r--   0        0        0      131 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/__main__.py
+-rw-r--r--   0        0        0      426 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/__init__.py
+-rw-r--r--   0        0        0      200 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Artisan.json
+-rw-r--r--   0        0        0      263 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Bandit.json
+-rw-r--r--   0        0        0      285 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Bureaucrat.json
+-rw-r--r--   0        0        0      177 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Cellar.json
+-rw-r--r--   0        0        0      145 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Chapel.json
+-rw-r--r--   0        0        0      165 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Council Room.json
+-rw-r--r--   0        0        0      141 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Festival.json
+-rw-r--r--   0        0        0      160 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Gardens.json
+-rw-r--r--   0        0        0      207 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Harbinger.json
+-rw-r--r--   0        0        0      221 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Library.json
+-rw-r--r--   0        0        0      146 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Market.json
+-rw-r--r--   0        0        0      184 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Merchant.json
+-rw-r--r--   0        0        0      186 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Militia.json
+-rw-r--r--   0        0        0      217 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Mine.json
+-rw-r--r--   0        0        0      257 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Moat.json
+-rw-r--r--   0        0        0      167 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Moneylender.json
+-rw-r--r--   0        0        0      177 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Poacher.json
+-rw-r--r--   0        0        0      201 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Remodel.json
+-rw-r--r--   0        0        0      255 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Sentry.json
+-rw-r--r--   0        0        0      119 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Smithy.json
+-rw-r--r--   0        0        0      165 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Throne Room.json
+-rw-r--r--   0        0        0      195 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Vassal.json
+-rw-r--r--   0        0        0      131 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Village.json
+-rw-r--r--   0        0        0      170 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Witch.json
+-rw-r--r--   0        0        0      146 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Base/Workshop.json
+-rw-r--r--   0        0        0      120 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Copper.json
+-rw-r--r--   0        0        0      125 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Curse.json
+-rw-r--r--   0        0        0      128 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Duchy.json
+-rw-r--r--   0        0        0      128 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Estate.json
+-rw-r--r--   0        0        0      118 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Gold.json
+-rw-r--r--   0        0        0      131 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Province.json
+-rw-r--r--   0        0        0      120 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/expansions/Common/Silver.json
+-rw-r--r--   0        0        0     5553 2023-06-28 15:51:23.442801 alpha_dom-0.1.4/python/alpha_dom/cards/model.py
+-rw-r--r--   0        0        0      783 1970-01-01 00:00:00.000000 alpha_dom-0.1.4/PKG-INFO
```

### Comparing `alpha_dom-0.1.3/LICENSE` & `alpha_dom-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `alpha_dom-0.1.3/pyproject.toml` & `alpha_dom-0.1.4/pyproject.toml`

 * *Files 14% similar despite different names*

```diff
@@ -1,30 +1,31 @@
 [tool.poetry]
 name = "alpha-dom"
-version = "0.1.3"
+version = "0.1.4"
 description = "Playing Dominion with Deep Reinforcement Learning"
 authors = [
     "Najib Ishaq <najib_ishaq@zoho.com>",
     "Morgan Prior <meprior424@gmail.com>",
 ]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "alpha_dom", from = "python"}]
 
 [tool.poetry.dependencies]
 python = "^3.11"
 pydantic = "^1.10.9"
 
-
 [tool.poetry.group.dev.dependencies]
 pre-commit = "^3.3.3"
 bump2version = "^1.0.1"
 black = "^23.3.0"
 ruff = "^0.0.272"
 mypy = "^1.3.0"
 pytest = "^7.3.2"
 pytest-xdist = "^3.3.1"
 pytest-sugar = "^0.9.7"
+pytest-cov = "^4.1.0"
+pytest-benchmark = "^4.0.0"
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `alpha_dom-0.1.3/PKG-INFO` & `alpha_dom-0.1.4/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 Metadata-Version: 2.1
 Name: alpha-dom
-Version: 0.1.3
+Version: 0.1.4
 Summary: Playing Dominion with Deep Reinforcement Learning
 License: MIT
 Author: Najib Ishaq
 Author-email: najib_ishaq@zoho.com
 Requires-Python: >=3.11,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: pydantic (>=1.10.9,<2.0.0)
 Description-Content-Type: text/markdown
 
-# AlphaDom (v0.1.3)
+# AlphaDom (v0.1.4)
 
 Playing Dominion with Deep Reinforcement Learning.
 
 ## References
 
 1. [AlphaZero](https://arxiv.org/abs/1712.01815)
    - Notes
```


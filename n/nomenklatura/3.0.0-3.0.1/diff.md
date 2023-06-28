# Comparing `tmp/nomenklatura-3.0.0.tar.gz` & `tmp/nomenklatura-3.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nomenklatura-3.0.0.tar", last modified: Mon Jun 26 14:45:37 2023, max compression
+gzip compressed data, was "nomenklatura-3.0.1.tar", last modified: Wed Jun 28 10:36:40 2023, max compression
```

## Comparing `nomenklatura-3.0.0.tar` & `nomenklatura-3.0.1.tar`

### file list

```diff
@@ -1,108 +1,108 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.882036 nomenklatura-3.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     5024 2023-06-26 14:45:37.882036 nomenklatura-3.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4613 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.874036 nomenklatura-3.0.0/nomenklatura/
--rw-r--r--   0 runner    (1001) docker     (123)      341 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5450 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/cache.py
--rw-r--r--   0 runner    (1001) docker     (123)    11092 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/cli.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.874036 nomenklatura-3.0.0/nomenklatura/data/
--rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/data/regression-v1.pkl
--rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/data/regression-v2.pkl
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/dataset/
--rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1922 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/catalog.py
--rw-r--r--   0 runner    (1001) docker     (123)     1237 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/coverage.py
--rw-r--r--   0 runner    (1001) docker     (123)     5332 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/publisher.py
--rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     1868 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/dataset/util.py
--rw-r--r--   0 runner    (1001) docker     (123)      861 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/db.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/enrich/
--rw-r--r--   0 runner    (1001) docker     (123)     3386 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5614 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/aleph.py
--rw-r--r--   0 runner    (1001) docker     (123)     5209 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/common.py
--rw-r--r--   0 runner    (1001) docker     (123)     2381 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/nominatim.py
--rw-r--r--   0 runner    (1001) docker     (123)     9948 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/opencorporates.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/
--rw-r--r--   0 runner    (1001) docker     (123)     9974 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2380 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/lang.py
--rw-r--r--   0 runner    (1001) docker     (123)     3580 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     1699 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/props.py
--rw-r--r--   0 runner    (1001) docker     (123)     1711 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/qualified.py
--rw-r--r--   0 runner    (1001) docker     (123)     1915 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/wikidata/value.py
--rw-r--r--   0 runner    (1001) docker     (123)     4542 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/enrich/yente.py
--rw-r--r--   0 runner    (1001) docker     (123)    16011 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/entity.py
--rw-r--r--   0 runner    (1001) docker     (123)      179 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/index/
--rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/index/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2988 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/index/entry.py
--rw-r--r--   0 runner    (1001) docker     (123)     5011 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/index/index.py
--rw-r--r--   0 runner    (1001) docker     (123)     2282 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/index/tokenizer.py
--rw-r--r--   0 runner    (1001) docker     (123)      578 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/judgement.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/matching/
--rw-r--r--   0 runner    (1001) docker     (123)     1032 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/matching/heuristic/
--rw-r--r--   0 runner    (1001) docker     (123)     5942 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/heuristic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2468 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/heuristic/logic.py
--rw-r--r--   0 runner    (1001) docker     (123)     1201 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/pairs.py
--rw-r--r--   0 runner    (1001) docker     (123)     1057 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/types.py
--rw-r--r--   0 runner    (1001) docker     (123)     2630 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/matching/v1/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1289 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/dates.py
--rw-r--r--   0 runner    (1001) docker     (123)     2785 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/misc.py
--rw-r--r--   0 runner    (1001) docker     (123)     3859 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2346 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/names.py
--rw-r--r--   0 runner    (1001) docker     (123)     3478 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/train.py
--rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v1/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/matching/v2/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1289 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/dates.py
--rw-r--r--   0 runner    (1001) docker     (123)     2456 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/misc.py
--rw-r--r--   0 runner    (1001) docker     (123)     3741 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2890 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/names.py
--rw-r--r--   0 runner    (1001) docker     (123)     3220 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/train.py
--rw-r--r--   0 runner    (1001) docker     (123)     1541 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/matching/v2/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/publish/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/publish/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1842 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/publish/dates.py
--rw-r--r--   0 runner    (1001) docker     (123)      691 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/publish/edges.py
--rw-r--r--   0 runner    (1001) docker     (123)     1282 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/publish/names.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.878036 nomenklatura-3.0.0/nomenklatura/resolver/
--rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/resolver/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/resolver/common.py
--rw-r--r--   0 runner    (1001) docker     (123)     1854 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/resolver/edge.py
--rw-r--r--   0 runner    (1001) docker     (123)     1611 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/resolver/identifier.py
--rw-r--r--   0 runner    (1001) docker     (123)    12467 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/resolver/resolver.py
--rw-r--r--   0 runner    (1001) docker     (123)     5009 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/senzing.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.882036 nomenklatura-3.0.0/nomenklatura/statement/
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/statement/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4293 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/statement/serialize.py
--rw-r--r--   0 runner    (1001) docker     (123)     7803 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/statement/statement.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.882036 nomenklatura-3.0.0/nomenklatura/store/
--rw-r--r--   0 runner    (1001) docker     (123)     1375 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/store/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3786 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/store/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     5562 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/store/level.py
--rw-r--r--   0 runner    (1001) docker     (123)     3749 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/store/memory.py
--rw-r--r--   0 runner    (1001) docker     (123)     1192 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/store/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.882036 nomenklatura-3.0.0/nomenklatura/tui/
--rw-r--r--   0 runner    (1001) docker     (123)      388 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/tui/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4909 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/tui/app.py
--rw-r--r--   0 runner    (1001) docker     (123)     2719 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/tui/comparison.py
--rw-r--r--   0 runner    (1001) docker     (123)     1093 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/tui/util.py
--rw-r--r--   0 runner    (1001) docker     (123)     3712 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/util.py
--rw-r--r--   0 runner    (1001) docker     (123)     3229 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/nomenklatura/xref.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:45:37.874036 nomenklatura-3.0.0/nomenklatura.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     5024 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2764 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       80 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/namespace_packages.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 14:45:14.000000 nomenklatura-3.0.0/nomenklatura.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      291 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-26 14:45:37.000000 nomenklatura-3.0.0/nomenklatura.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 14:45:37.882036 nomenklatura-3.0.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1571 2023-06-26 14:43:41.000000 nomenklatura-3.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     5044 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4613 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.773881 nomenklatura-3.0.1/nomenklatura/
+-rw-r--r--   0 runner    (1001) docker     (123)      341 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5450 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/cache.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11092 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.773881 nomenklatura-3.0.1/nomenklatura/data/
+-rw-r--r--   0 runner    (1001) docker     (123)     2271 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/data/regression-v1.pkl
+-rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/data/regression-v2.pkl
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/dataset/
+-rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1922 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/catalog.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1237 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/coverage.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5332 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/publisher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1868 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/dataset/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)      861 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/db.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/enrich/
+-rw-r--r--   0 runner    (1001) docker     (123)     3386 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5614 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/aleph.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5209 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2381 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/nominatim.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9948 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/opencorporates.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/
+-rw-r--r--   0 runner    (1001) docker     (123)     9974 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2380 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/lang.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3580 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1699 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/props.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1711 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/qualified.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1915 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/wikidata/value.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4542 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/enrich/yente.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16011 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/entity.py
+-rw-r--r--   0 runner    (1001) docker     (123)      179 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/index/
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/index/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2988 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/index/entry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5011 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/index/index.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2282 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/index/tokenizer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      578 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/judgement.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/matching/
+-rw-r--r--   0 runner    (1001) docker     (123)     1032 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/matching/heuristic/
+-rw-r--r--   0 runner    (1001) docker     (123)     5942 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/heuristic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2468 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/heuristic/logic.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1201 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/pairs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1057 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/types.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2630 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.777881 nomenklatura-3.0.1/nomenklatura/matching/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1289 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/dates.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2785 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/misc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3859 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2346 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/names.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3478 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/train.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v1/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/nomenklatura/matching/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1289 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/dates.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2456 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/misc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3741 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2890 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/names.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3220 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/train.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1541 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/matching/v2/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/nomenklatura/publish/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/publish/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1842 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/publish/dates.py
+-rw-r--r--   0 runner    (1001) docker     (123)      691 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/publish/edges.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1282 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/publish/names.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/nomenklatura/resolver/
+-rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/resolver/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/resolver/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1854 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/resolver/edge.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1611 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/resolver/identifier.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12467 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/resolver/resolver.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5009 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/senzing.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/nomenklatura/statement/
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/statement/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4302 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/statement/serialize.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7803 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/statement/statement.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/nomenklatura/store/
+-rw-r--r--   0 runner    (1001) docker     (123)     1375 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/store/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3786 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/store/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5562 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/store/level.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3749 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/store/memory.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1192 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/store/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/nomenklatura/tui/
+-rw-r--r--   0 runner    (1001) docker     (123)      388 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/tui/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4909 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/tui/app.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2719 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/tui/comparison.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1093 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/tui/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3712 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3229 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/nomenklatura/xref.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:36:40.773881 nomenklatura-3.0.1/nomenklatura.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     5044 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2764 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/namespace_packages.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:36:15.000000 nomenklatura-3.0.1/nomenklatura.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      298 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 10:36:40.000000 nomenklatura-3.0.1/nomenklatura.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:36:40.781881 nomenklatura-3.0.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1580 2023-06-28 10:34:39.000000 nomenklatura-3.0.1/setup.py
```

### Comparing `nomenklatura-3.0.0/LICENSE` & `nomenklatura-3.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/PKG-INFO` & `nomenklatura-3.0.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 Metadata-Version: 2.1
 Name: nomenklatura
-Version: 3.0.0
+Version: 3.0.1
 Summary: Make record linkages in followthemoney data.
 Home-page: https://github.com/opensanctions/nomenklatura
 Author: Friedrich Lindenberg
 Author-email: friedrich@pudo.org
 License: MIT
 Keywords: data mapping identity followthemoney linkage record
+Platform: UNKNOWN
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 Provides-Extra: leveldb
 License-File: LICENSE
 
 # nomenklatura
 
@@ -91,7 +92,9 @@
 ## Contact, contributions etc.
 
 This codebase is licensed under the terms of an MIT license (see LICENSE).
 
 We're keen for any contributions, bug fixes and feature suggestions, please use the GitHub issue tracker for this repository. 
 
 Nomenklatura is currently developed thanks to a Prototypefund grant for [OpenSanctions](https://opensanctions.org). Previous iterations of the package were developed with support from [Knight-Mozilla OpenNews](http://opennews.org) and the [Open Knowledge Foundation Labs](http://okfnlabs.org).
+
+
```

### Comparing `nomenklatura-3.0.0/README.md` & `nomenklatura-3.0.1/README.md`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/cache.py` & `nomenklatura-3.0.1/nomenklatura/cache.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/cli.py` & `nomenklatura-3.0.1/nomenklatura/cli.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/data/regression-v1.pkl` & `nomenklatura-3.0.1/nomenklatura/data/regression-v1.pkl`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/data/regression-v2.pkl` & `nomenklatura-3.0.1/nomenklatura/data/regression-v2.pkl`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/dataset/catalog.py` & `nomenklatura-3.0.1/nomenklatura/dataset/catalog.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/dataset/coverage.py` & `nomenklatura-3.0.1/nomenklatura/dataset/coverage.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/dataset/dataset.py` & `nomenklatura-3.0.1/nomenklatura/dataset/dataset.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/dataset/publisher.py` & `nomenklatura-3.0.1/nomenklatura/dataset/publisher.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/dataset/resource.py` & `nomenklatura-3.0.1/nomenklatura/dataset/resource.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/dataset/util.py` & `nomenklatura-3.0.1/nomenklatura/dataset/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/db.py` & `nomenklatura-3.0.1/nomenklatura/db.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/__init__.py` & `nomenklatura-3.0.1/nomenklatura/enrich/__init__.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/aleph.py` & `nomenklatura-3.0.1/nomenklatura/enrich/aleph.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/common.py` & `nomenklatura-3.0.1/nomenklatura/enrich/common.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/nominatim.py` & `nomenklatura-3.0.1/nomenklatura/enrich/nominatim.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/opencorporates.py` & `nomenklatura-3.0.1/nomenklatura/enrich/opencorporates.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/wikidata/__init__.py` & `nomenklatura-3.0.1/nomenklatura/enrich/wikidata/__init__.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/wikidata/lang.py` & `nomenklatura-3.0.1/nomenklatura/enrich/wikidata/lang.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/wikidata/model.py` & `nomenklatura-3.0.1/nomenklatura/enrich/wikidata/model.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/wikidata/props.py` & `nomenklatura-3.0.1/nomenklatura/enrich/wikidata/props.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/wikidata/qualified.py` & `nomenklatura-3.0.1/nomenklatura/enrich/wikidata/qualified.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/wikidata/value.py` & `nomenklatura-3.0.1/nomenklatura/enrich/wikidata/value.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/enrich/yente.py` & `nomenklatura-3.0.1/nomenklatura/enrich/yente.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/entity.py` & `nomenklatura-3.0.1/nomenklatura/entity.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/index/entry.py` & `nomenklatura-3.0.1/nomenklatura/index/entry.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/index/index.py` & `nomenklatura-3.0.1/nomenklatura/index/index.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/index/tokenizer.py` & `nomenklatura-3.0.1/nomenklatura/index/tokenizer.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/judgement.py` & `nomenklatura-3.0.1/nomenklatura/judgement.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/__init__.py` & `nomenklatura-3.0.1/nomenklatura/matching/__init__.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/heuristic/__init__.py` & `nomenklatura-3.0.1/nomenklatura/matching/heuristic/__init__.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/heuristic/logic.py` & `nomenklatura-3.0.1/nomenklatura/matching/heuristic/logic.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/pairs.py` & `nomenklatura-3.0.1/nomenklatura/matching/pairs.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/types.py` & `nomenklatura-3.0.1/nomenklatura/matching/types.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/util.py` & `nomenklatura-3.0.1/nomenklatura/matching/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v1/dates.py` & `nomenklatura-3.0.1/nomenklatura/matching/v1/dates.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v1/misc.py` & `nomenklatura-3.0.1/nomenklatura/matching/v1/misc.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v1/model.py` & `nomenklatura-3.0.1/nomenklatura/matching/v1/model.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v1/names.py` & `nomenklatura-3.0.1/nomenklatura/matching/v1/names.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v1/train.py` & `nomenklatura-3.0.1/nomenklatura/matching/v1/train.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v1/util.py` & `nomenklatura-3.0.1/nomenklatura/matching/v1/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v2/dates.py` & `nomenklatura-3.0.1/nomenklatura/matching/v2/dates.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v2/misc.py` & `nomenklatura-3.0.1/nomenklatura/matching/v2/misc.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v2/model.py` & `nomenklatura-3.0.1/nomenklatura/matching/v2/model.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v2/names.py` & `nomenklatura-3.0.1/nomenklatura/matching/v2/names.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v2/train.py` & `nomenklatura-3.0.1/nomenklatura/matching/v2/train.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/matching/v2/util.py` & `nomenklatura-3.0.1/nomenklatura/matching/v2/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/publish/dates.py` & `nomenklatura-3.0.1/nomenklatura/publish/dates.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/publish/edges.py` & `nomenklatura-3.0.1/nomenklatura/publish/edges.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/publish/names.py` & `nomenklatura-3.0.1/nomenklatura/publish/names.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/resolver/edge.py` & `nomenklatura-3.0.1/nomenklatura/resolver/edge.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/resolver/identifier.py` & `nomenklatura-3.0.1/nomenklatura/resolver/identifier.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/resolver/resolver.py` & `nomenklatura-3.0.1/nomenklatura/resolver/resolver.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/senzing.py` & `nomenklatura-3.0.1/nomenklatura/senzing.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/statement/serialize.py` & `nomenklatura-3.0.1/nomenklatura/statement/serialize.py`

 * *Files 2% similar despite different names*

```diff
@@ -64,21 +64,22 @@
         yield statement_type.from_row(row)
 
 
 def read_pack_statements(
     fh: BinaryIO, statement_type: Type[S]
 ) -> Generator[S, None, None]:
     wrapped = TextIOWrapper(fh, encoding="utf-8")
-    for row in csv.DictReader(wrapped, dialect=csv.unix_dialect):
-        row["canonical_id"] = row["entity_id"]
-        schema, prop_type, prop = unpack_prop(row["prop"])
-        row["schema"] = schema
-        row["prop"] = prop
-        row["prop_type"] = prop_type
-        yield statement_type.from_row(row)
+    for row in csv.reader(wrapped, dialect=csv.unix_dialect):
+        data = dict(zip(PACK_COLUMNS, row))
+        data["canonical_id"] = data["entity_id"]
+        schema, prop_type, prop = unpack_prop(data["prop"])
+        data["schema"] = schema
+        data["prop"] = prop
+        data["prop_type"] = prop_type
+        yield statement_type.from_row(data)
 
 
 def read_statements(
     fh: BinaryIO, format: str, statement_type: Type[S]
 ) -> Generator[S, None, None]:
     if format == CSV:
         yield from read_csv_statements(fh, statement_type)
@@ -123,26 +124,25 @@
     row = stmt.to_row()
     row.pop("canonical_id", None)
     row.pop("prop_type", None)
     prop = row.pop("prop")
     schema = row.pop("schema")
     if prop is None or schema is None:
         raise ValueError("Cannot pack statement without prop and schema")
-    row["prop"] = pack_prop(prop, schema)
+    row["prop"] = pack_prop(schema, prop)
     return row
 
 
 def write_pack_statements(fh: BinaryIO, statements: Iterable[S]) -> None:
     with TextIOWrapper(fh, encoding="utf-8") as wrapped:
         writer = csv.writer(
             wrapped,
             dialect=csv.unix_dialect,
             quoting=csv.QUOTE_MINIMAL,
         )
-        writer.writerow(PACK_COLUMNS)
         for stmt in statements:
             row = pack_statement(stmt)
             writer.writerow([row.get(c) for c in PACK_COLUMNS])
 
 
 def write_statements(fh: BinaryIO, format: str, statements: Iterable[S]) -> None:
     if format == CSV:
```

### Comparing `nomenklatura-3.0.0/nomenklatura/statement/statement.py` & `nomenklatura-3.0.1/nomenklatura/statement/statement.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/store/__init__.py` & `nomenklatura-3.0.1/nomenklatura/store/__init__.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/store/base.py` & `nomenklatura-3.0.1/nomenklatura/store/base.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/store/level.py` & `nomenklatura-3.0.1/nomenklatura/store/level.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/store/memory.py` & `nomenklatura-3.0.1/nomenklatura/store/memory.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/store/util.py` & `nomenklatura-3.0.1/nomenklatura/store/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/tui/app.py` & `nomenklatura-3.0.1/nomenklatura/tui/app.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/tui/comparison.py` & `nomenklatura-3.0.1/nomenklatura/tui/comparison.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/tui/util.py` & `nomenklatura-3.0.1/nomenklatura/tui/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/util.py` & `nomenklatura-3.0.1/nomenklatura/util.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura/xref.py` & `nomenklatura-3.0.1/nomenklatura/xref.py`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/nomenklatura.egg-info/PKG-INFO` & `nomenklatura-3.0.1/nomenklatura.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 Metadata-Version: 2.1
 Name: nomenklatura
-Version: 3.0.0
+Version: 3.0.1
 Summary: Make record linkages in followthemoney data.
 Home-page: https://github.com/opensanctions/nomenklatura
 Author: Friedrich Lindenberg
 Author-email: friedrich@pudo.org
 License: MIT
 Keywords: data mapping identity followthemoney linkage record
+Platform: UNKNOWN
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 Provides-Extra: leveldb
 License-File: LICENSE
 
 # nomenklatura
 
@@ -91,7 +92,9 @@
 ## Contact, contributions etc.
 
 This codebase is licensed under the terms of an MIT license (see LICENSE).
 
 We're keen for any contributions, bug fixes and feature suggestions, please use the GitHub issue tracker for this repository. 
 
 Nomenklatura is currently developed thanks to a Prototypefund grant for [OpenSanctions](https://opensanctions.org). Previous iterations of the package were developed with support from [Knight-Mozilla OpenNews](http://opennews.org) and the [Open Knowledge Foundation Labs](http://okfnlabs.org).
+
+
```

### Comparing `nomenklatura-3.0.0/nomenklatura.egg-info/SOURCES.txt` & `nomenklatura-3.0.1/nomenklatura.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `nomenklatura-3.0.0/setup.py` & `nomenklatura-3.0.1/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 with open("README.md") as f:
     long_description = f.read()
 
 
 setup(
     name="nomenklatura",
-    version="3.0.0",
+    version="3.0.1",
     description="Make record linkages in followthemoney data.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     keywords="data mapping identity followthemoney linkage record",
     author="Friedrich Lindenberg",
     author_email="friedrich@pudo.org",
     url="https://github.com/opensanctions/nomenklatura",
@@ -19,15 +19,15 @@
     namespace_packages=[],
     include_package_data=True,
     package_data={"": ["nomenklatura/data/*", "nomenklatura/py.typed"]},
     zip_safe=False,
     install_requires=[
         "followthemoney >= 3.3.0, < 4.0.0",
         "shortuuid >= 1.0.11, < 2.0.0",
-        "jellyfish == 1.0.0",
+        "jellyfish >= 1.0.0, < 2.0.0",
         "rich >= 10.9.0, < 14.0.0",
         "textual >= 0.19.0, < 0.29.0",
         "scikit-learn == 1.2.2",
         "click >= 8.0.0, < 9.0.0",
     ],
     tests_require=[],
     entry_points={
```


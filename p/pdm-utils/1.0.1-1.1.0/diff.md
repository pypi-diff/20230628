# Comparing `tmp/pdm_utils-1.0.1.tar.gz` & `tmp/pdm_utils-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/Users/labad/git_repos/pdm_utils/dist/.tmp-k0ze0vqk/pdm_utils-1.0.1.tar", last modified: Thu Jun 15 20:39:06 2023, max compression
+gzip compressed data, was "/Users/labad/git_repos/pdm_utils/dist/.tmp-c202e_h2/pdm_utils-1.1.0.tar", last modified: Tue Jun 27 23:16:41 2023, max compression
```

## Comparing `pdm_utils-1.0.1.tar` & `pdm_utils-1.1.0.tar`

### file list

```diff
@@ -1,96 +1,97 @@
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.641003 pdm_utils-1.0.1/
--rw-r--r--   0 labad      (502) staff       (20)    35186 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/LICENSE
--rw-r--r--   0 labad      (502) staff       (20)     1720 2023-06-15 20:39:06.641282 pdm_utils-1.0.1/PKG-INFO
--rw-r--r--   0 labad      (502) staff       (20)      790 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/README.md
--rw-r--r--   0 labad      (502) staff       (20)       89 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/pyproject.toml
--rw-r--r--   0 labad      (502) staff       (20)     1413 2023-06-15 20:39:06.642413 pdm_utils-1.0.1/setup.cfg
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.602948 pdm_utils-1.0.1/src/
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.606074 pdm_utils-1.0.1/src/pdm_utils/
--rw-r--r--   0 labad      (502) staff       (20)      146 2023-06-15 20:37:17.000000 pdm_utils-1.0.1/src/pdm_utils/__init__.py
--rw-r--r--   0 labad      (502) staff       (20)      114 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/__main__.py
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.619656 pdm_utils-1.0.1/src/pdm_utils/classes/
--rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/__init__.py
--rw-r--r--   0 labad      (502) staff       (20)    20060 2020-10-30 13:34:57.000000 pdm_utils-1.0.1/src/pdm_utils/classes/alchemyhandler.py
--rw-r--r--   0 labad      (502) staff       (20)     8100 2021-09-17 01:24:47.000000 pdm_utils-1.0.1/src/pdm_utils/classes/aragornhandler.py
--rw-r--r--   0 labad      (502) staff       (20)    10410 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/bundle.py
--rw-r--r--   0 labad      (502) staff       (20)    39957 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/cds.py
--rw-r--r--   0 labad      (502) staff       (20)     2461 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/cdspair.py
--rw-r--r--   0 labad      (502) staff       (20)     9923 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/dbcomparesummary.py
--rw-r--r--   0 labad      (502) staff       (20)      165 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/classes/error.py
--rw-r--r--   0 labad      (502) staff       (20)      696 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/evaluation.py
--rw-r--r--   0 labad      (502) staff       (20)     7966 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/fileio.py
--rw-r--r--   0 labad      (502) staff       (20)    23716 2021-09-17 01:24:47.000000 pdm_utils-1.0.1/src/pdm_utils/classes/filter.py
--rw-r--r--   0 labad      (502) staff       (20)    41595 2021-09-22 16:59:23.000000 pdm_utils-1.0.1/src/pdm_utils/classes/genome.py
--rw-r--r--   0 labad      (502) staff       (20)     5574 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/genomepair.py
--rw-r--r--   0 labad      (502) staff       (20)    18395 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/genometriad.py
--rw-r--r--   0 labad      (502) staff       (20)     1124 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/classes/progress.py
--rw-r--r--   0 labad      (502) staff       (20)     7244 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/randomfieldupdatehandler.py
--rw-r--r--   0 labad      (502) staff       (20)     4243 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/source.py
--rw-r--r--   0 labad      (502) staff       (20)     8694 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/ticket.py
--rw-r--r--   0 labad      (502) staff       (20)    37793 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/tmrna.py
--rw-r--r--   0 labad      (502) staff       (20)    64069 2021-09-22 15:49:23.000000 pdm_utils-1.0.1/src/pdm_utils/classes/trna.py
--rw-r--r--   0 labad      (502) staff       (20)     3694 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/classes/trnascansehandler.py
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.622175 pdm_utils-1.0.1/src/pdm_utils/constants/
--rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/constants/__init__.py
--rw-r--r--   0 labad      (502) staff       (20)     6185 2023-06-15 19:41:31.000000 pdm_utils-1.0.1/src/pdm_utils/constants/constants.py
--rw-r--r--   0 labad      (502) staff       (20)    10763 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/constants/db_schema_0.py
--rw-r--r--   0 labad      (502) staff       (20)    12305 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/constants/eval_descriptions.py
--rw-r--r--   0 labad      (502) staff       (20)    37071 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/constants/schema_conversions.py
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.631534 pdm_utils-1.0.1/src/pdm_utils/functions/
--rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/__init__.py
--rw-r--r--   0 labad      (502) staff       (20)     6113 2020-10-30 13:34:57.000000 pdm_utils-1.0.1/src/pdm_utils/functions/annotation.py
--rw-r--r--   0 labad      (502) staff       (20)    45918 2021-01-04 16:11:55.000000 pdm_utils-1.0.1/src/pdm_utils/functions/basic.py
--rw-r--r--   0 labad      (502) staff       (20)     2962 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/cartography.py
--rw-r--r--   0 labad      (502) staff       (20)     2182 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/configfile.py
--rw-r--r--   0 labad      (502) staff       (20)     2853 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/functions/deeptmhmm.py
--rw-r--r--   0 labad      (502) staff       (20)     4638 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/eval_modes.py
--rw-r--r--   0 labad      (502) staff       (20)     2301 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/fasta.py
--rw-r--r--   0 labad      (502) staff       (20)    10526 2021-03-23 03:57:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/fileio.py
--rw-r--r--   0 labad      (502) staff       (20)    30706 2021-09-22 16:59:23.000000 pdm_utils-1.0.1/src/pdm_utils/functions/flat_files.py
--rw-r--r--   0 labad      (502) staff       (20)     2858 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/multiprocess.py
--rw-r--r--   0 labad      (502) staff       (20)     5299 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/multithread.py
--rw-r--r--   0 labad      (502) staff       (20)    27400 2022-10-18 17:47:46.000000 pdm_utils-1.0.1/src/pdm_utils/functions/mysqldb.py
--rw-r--r--   0 labad      (502) staff       (20)    13414 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/mysqldb_basic.py
--rw-r--r--   0 labad      (502) staff       (20)     6605 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/ncbi.py
--rw-r--r--   0 labad      (502) staff       (20)    10972 2020-12-29 20:15:44.000000 pdm_utils-1.0.1/src/pdm_utils/functions/parsing.py
--rw-r--r--   0 labad      (502) staff       (20)    12611 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/phagesdb.py
--rw-r--r--   0 labad      (502) staff       (20)     8600 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/pham_alignment.py
--rw-r--r--   0 labad      (502) staff       (20)     9900 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/phameration.py
--rw-r--r--   0 labad      (502) staff       (20)     8473 2021-01-04 16:11:55.000000 pdm_utils-1.0.1/src/pdm_utils/functions/pipeline_shells.py
--rw-r--r--   0 labad      (502) staff       (20)     8828 2020-12-28 19:11:26.000000 pdm_utils-1.0.1/src/pdm_utils/functions/pipelines_basic.py
--rw-r--r--   0 labad      (502) staff       (20)    30269 2021-09-17 01:24:47.000000 pdm_utils-1.0.1/src/pdm_utils/functions/querying.py
--rw-r--r--   0 labad      (502) staff       (20)     6325 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/rpsblast.py
--rw-r--r--   0 labad      (502) staff       (20)     3475 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/server.py
--rw-r--r--   0 labad      (502) staff       (20)      978 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/functions/subprocess.py
--rw-r--r--   0 labad      (502) staff       (20)    11826 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/functions/tickets.py
--rw-r--r--   0 labad      (502) staff       (20)    15996 2021-01-04 16:11:55.000000 pdm_utils-1.0.1/src/pdm_utils/functions/url_basic.py
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.639710 pdm_utils-1.0.1/src/pdm_utils/pipelines/
--rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/__init__.py
--rwxr-xr-x   0 labad      (502) staff       (20)    60772 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/compare_db.py
--rw-r--r--   0 labad      (502) staff       (20)     8327 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/convert_db.py
--rw-r--r--   0 labad      (502) staff       (20)    33685 2021-09-22 16:59:23.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/export_db.py
--rw-r--r--   0 labad      (502) staff       (20)    17323 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/find_domains.py
--rw-r--r--   0 labad      (502) staff       (20)      972 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/find_membrane.py
--rw-r--r--   0 labad      (502) staff       (20)    14635 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/find_transmembrane.py
--rwxr-xr-x   0 labad      (502) staff       (20)     7930 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/freeze_db.py
--rw-r--r--   0 labad      (502) staff       (20)    37362 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/get_data.py
--rw-r--r--   0 labad      (502) staff       (20)    16273 2021-01-05 20:20:36.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/get_db.py
--rw-r--r--   0 labad      (502) staff       (20)    10665 2020-10-30 13:34:57.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/get_gb_records.py
--rw-r--r--   0 labad      (502) staff       (20)    91016 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/import_genome.py
--rw-r--r--   0 labad      (502) staff       (20)    12771 2021-09-17 01:23:58.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/pham_finder.py
--rw-r--r--   0 labad      (502) staff       (20)    25213 2020-10-30 13:34:57.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/pham_review.py
--rw-r--r--   0 labad      (502) staff       (20)    10125 2023-06-15 19:38:37.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/phamerate.py
--rw-r--r--   0 labad      (502) staff       (20)     7937 2020-12-13 18:52:56.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/push_db.py
--rw-r--r--   0 labad      (502) staff       (20)    36843 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/revise.py
--rw-r--r--   0 labad      (502) staff       (20)     5642 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/pipelines/update_field.py
--rw-r--r--   0 labad      (502) staff       (20)     3494 2023-06-15 19:40:19.000000 pdm_utils-1.0.1/src/pdm_utils/run.py
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.608642 pdm_utils-1.0.1/src/pdm_utils.egg-info/
--rw-r--r--   0 labad      (502) staff       (20)     1720 2023-06-15 20:39:06.000000 pdm_utils-1.0.1/src/pdm_utils.egg-info/PKG-INFO
--rw-r--r--   0 labad      (502) staff       (20)     3023 2023-06-15 20:39:06.000000 pdm_utils-1.0.1/src/pdm_utils.egg-info/SOURCES.txt
--rw-r--r--   0 labad      (502) staff       (20)        1 2023-06-15 20:39:06.000000 pdm_utils-1.0.1/src/pdm_utils.egg-info/dependency_links.txt
--rw-r--r--   0 labad      (502) staff       (20)       54 2023-06-15 20:39:06.000000 pdm_utils-1.0.1/src/pdm_utils.egg-info/entry_points.txt
--rw-r--r--   0 labad      (502) staff       (20)      160 2023-06-15 20:39:06.000000 pdm_utils-1.0.1/src/pdm_utils.egg-info/requires.txt
--rw-r--r--   0 labad      (502) staff       (20)       10 2023-06-15 20:39:06.000000 pdm_utils-1.0.1/src/pdm_utils.egg-info/top_level.txt
-drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-15 20:39:06.640663 pdm_utils-1.0.1/tests/
--rw-r--r--   0 labad      (502) staff       (20)    20144 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/tests/test_data_utils.py
--rw-r--r--   0 labad      (502) staff       (20)    15441 2020-10-23 17:14:54.000000 pdm_utils-1.0.1/tests/test_db_utils.py
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.499214 pdm_utils-1.1.0/
+-rw-r--r--   0 labad      (502) staff       (20)    35186 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/LICENSE
+-rw-r--r--   0 labad      (502) staff       (20)     1720 2023-06-27 23:16:41.499334 pdm_utils-1.1.0/PKG-INFO
+-rw-r--r--   0 labad      (502) staff       (20)      790 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/README.md
+-rw-r--r--   0 labad      (502) staff       (20)       89 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/pyproject.toml
+-rw-r--r--   0 labad      (502) staff       (20)     1506 2023-06-27 23:16:41.499965 pdm_utils-1.1.0/setup.cfg
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.436447 pdm_utils-1.1.0/src/
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.441256 pdm_utils-1.1.0/src/pdm_utils/
+-rw-r--r--   0 labad      (502) staff       (20)      146 2023-06-27 23:16:18.000000 pdm_utils-1.1.0/src/pdm_utils/__init__.py
+-rw-r--r--   0 labad      (502) staff       (20)      114 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/__main__.py
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.459646 pdm_utils-1.1.0/src/pdm_utils/classes/
+-rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/__init__.py
+-rw-r--r--   0 labad      (502) staff       (20)    20060 2020-10-30 13:34:57.000000 pdm_utils-1.1.0/src/pdm_utils/classes/alchemyhandler.py
+-rw-r--r--   0 labad      (502) staff       (20)     8100 2021-09-17 01:24:47.000000 pdm_utils-1.1.0/src/pdm_utils/classes/aragornhandler.py
+-rw-r--r--   0 labad      (502) staff       (20)    10410 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/bundle.py
+-rw-r--r--   0 labad      (502) staff       (20)    39957 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/cds.py
+-rw-r--r--   0 labad      (502) staff       (20)     2461 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/cdspair.py
+-rw-r--r--   0 labad      (502) staff       (20)     9923 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/dbcomparesummary.py
+-rw-r--r--   0 labad      (502) staff       (20)      165 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/classes/error.py
+-rw-r--r--   0 labad      (502) staff       (20)      696 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/evaluation.py
+-rw-r--r--   0 labad      (502) staff       (20)     7966 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/fileio.py
+-rw-r--r--   0 labad      (502) staff       (20)    23716 2021-09-17 01:24:47.000000 pdm_utils-1.1.0/src/pdm_utils/classes/filter.py
+-rw-r--r--   0 labad      (502) staff       (20)    41595 2021-09-22 16:59:23.000000 pdm_utils-1.1.0/src/pdm_utils/classes/genome.py
+-rw-r--r--   0 labad      (502) staff       (20)     5574 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/genomepair.py
+-rw-r--r--   0 labad      (502) staff       (20)    18395 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/genometriad.py
+-rw-r--r--   0 labad      (502) staff       (20)     1124 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/classes/progress.py
+-rw-r--r--   0 labad      (502) staff       (20)     7244 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/randomfieldupdatehandler.py
+-rw-r--r--   0 labad      (502) staff       (20)     4243 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/source.py
+-rw-r--r--   0 labad      (502) staff       (20)     8694 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/ticket.py
+-rw-r--r--   0 labad      (502) staff       (20)    37793 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/tmrna.py
+-rw-r--r--   0 labad      (502) staff       (20)    64069 2021-09-22 15:49:23.000000 pdm_utils-1.1.0/src/pdm_utils/classes/trna.py
+-rw-r--r--   0 labad      (502) staff       (20)     3694 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/classes/trnascansehandler.py
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.463065 pdm_utils-1.1.0/src/pdm_utils/constants/
+-rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/constants/__init__.py
+-rw-r--r--   0 labad      (502) staff       (20)     6185 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/constants/constants.py
+-rw-r--r--   0 labad      (502) staff       (20)    10763 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/constants/db_schema_0.py
+-rw-r--r--   0 labad      (502) staff       (20)    12305 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/constants/eval_descriptions.py
+-rw-r--r--   0 labad      (502) staff       (20)    37168 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/constants/schema_conversions.py
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.482856 pdm_utils-1.1.0/src/pdm_utils/functions/
+-rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/__init__.py
+-rw-r--r--   0 labad      (502) staff       (20)     6113 2020-10-30 13:34:57.000000 pdm_utils-1.1.0/src/pdm_utils/functions/annotation.py
+-rw-r--r--   0 labad      (502) staff       (20)    45918 2021-01-04 16:11:55.000000 pdm_utils-1.1.0/src/pdm_utils/functions/basic.py
+-rw-r--r--   0 labad      (502) staff       (20)     2962 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/cartography.py
+-rw-r--r--   0 labad      (502) staff       (20)     2182 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/configfile.py
+-rw-r--r--   0 labad      (502) staff       (20)     2853 2023-06-15 19:40:19.000000 pdm_utils-1.1.0/src/pdm_utils/functions/deeptmhmm.py
+-rw-r--r--   0 labad      (502) staff       (20)     4638 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/eval_modes.py
+-rw-r--r--   0 labad      (502) staff       (20)     2301 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/fasta.py
+-rw-r--r--   0 labad      (502) staff       (20)    10526 2021-03-23 03:57:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/fileio.py
+-rw-r--r--   0 labad      (502) staff       (20)    30706 2021-09-22 16:59:23.000000 pdm_utils-1.1.0/src/pdm_utils/functions/flat_files.py
+-rw-r--r--   0 labad      (502) staff       (20)     2858 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/multiprocess.py
+-rw-r--r--   0 labad      (502) staff       (20)     5299 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/multithread.py
+-rw-r--r--   0 labad      (502) staff       (20)    27400 2022-10-18 17:47:46.000000 pdm_utils-1.1.0/src/pdm_utils/functions/mysqldb.py
+-rw-r--r--   0 labad      (502) staff       (20)    13414 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/mysqldb_basic.py
+-rw-r--r--   0 labad      (502) staff       (20)     6605 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/ncbi.py
+-rw-r--r--   0 labad      (502) staff       (20)    10972 2020-12-29 20:15:44.000000 pdm_utils-1.1.0/src/pdm_utils/functions/parsing.py
+-rw-r--r--   0 labad      (502) staff       (20)    12611 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/phagesdb.py
+-rw-r--r--   0 labad      (502) staff       (20)     8600 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/pham_alignment.py
+-rw-r--r--   0 labad      (502) staff       (20)     9900 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/phameration.py
+-rw-r--r--   0 labad      (502) staff       (20)     8473 2021-01-04 16:11:55.000000 pdm_utils-1.1.0/src/pdm_utils/functions/pipeline_shells.py
+-rw-r--r--   0 labad      (502) staff       (20)     8828 2020-12-28 19:11:26.000000 pdm_utils-1.1.0/src/pdm_utils/functions/pipelines_basic.py
+-rw-r--r--   0 labad      (502) staff       (20)    30269 2021-09-17 01:24:47.000000 pdm_utils-1.1.0/src/pdm_utils/functions/querying.py
+-rw-r--r--   0 labad      (502) staff       (20)     6325 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/rpsblast.py
+-rw-r--r--   0 labad      (502) staff       (20)     3475 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/server.py
+-rw-r--r--   0 labad      (502) staff       (20)      978 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/functions/subprocess.py
+-rw-r--r--   0 labad      (502) staff       (20)    11826 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/functions/tickets.py
+-rw-r--r--   0 labad      (502) staff       (20)    15996 2021-01-04 16:11:55.000000 pdm_utils-1.1.0/src/pdm_utils/functions/url_basic.py
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.497265 pdm_utils-1.1.0/src/pdm_utils/pipelines/
+-rw-r--r--   0 labad      (502) staff       (20)        0 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/__init__.py
+-rw-r--r--   0 labad      (502) staff       (20)    27107 2023-06-27 23:12:34.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/cluster_db.py
+-rwxr-xr-x   0 labad      (502) staff       (20)    60772 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/compare_db.py
+-rw-r--r--   0 labad      (502) staff       (20)     8327 2023-06-15 19:40:19.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/convert_db.py
+-rw-r--r--   0 labad      (502) staff       (20)    33685 2021-09-22 16:59:23.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/export_db.py
+-rw-r--r--   0 labad      (502) staff       (20)    17337 2023-06-27 23:13:56.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/find_domains.py
+-rw-r--r--   0 labad      (502) staff       (20)      972 2023-06-15 19:40:19.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/find_membrane.py
+-rw-r--r--   0 labad      (502) staff       (20)    14635 2023-06-15 19:40:19.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/find_transmembrane.py
+-rwxr-xr-x   0 labad      (502) staff       (20)     7930 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/freeze_db.py
+-rw-r--r--   0 labad      (502) staff       (20)    37362 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/get_data.py
+-rw-r--r--   0 labad      (502) staff       (20)    16273 2021-01-05 20:20:36.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/get_db.py
+-rw-r--r--   0 labad      (502) staff       (20)    10665 2020-10-30 13:34:57.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/get_gb_records.py
+-rw-r--r--   0 labad      (502) staff       (20)    91016 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/import_genome.py
+-rw-r--r--   0 labad      (502) staff       (20)    12771 2021-09-17 01:23:58.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/pham_finder.py
+-rw-r--r--   0 labad      (502) staff       (20)    25213 2020-10-30 13:34:57.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/pham_review.py
+-rw-r--r--   0 labad      (502) staff       (20)    10125 2023-06-18 16:32:34.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/phamerate.py
+-rw-r--r--   0 labad      (502) staff       (20)     7937 2020-12-13 18:52:56.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/push_db.py
+-rw-r--r--   0 labad      (502) staff       (20)    36843 2023-06-15 19:40:19.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/revise.py
+-rw-r--r--   0 labad      (502) staff       (20)     5642 2023-06-15 19:40:19.000000 pdm_utils-1.1.0/src/pdm_utils/pipelines/update_field.py
+-rw-r--r--   0 labad      (502) staff       (20)     3630 2023-06-27 20:56:00.000000 pdm_utils-1.1.0/src/pdm_utils/run.py
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.443961 pdm_utils-1.1.0/src/pdm_utils.egg-info/
+-rw-r--r--   0 labad      (502) staff       (20)     1720 2023-06-27 23:16:41.000000 pdm_utils-1.1.0/src/pdm_utils.egg-info/PKG-INFO
+-rw-r--r--   0 labad      (502) staff       (20)     3061 2023-06-27 23:16:41.000000 pdm_utils-1.1.0/src/pdm_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 labad      (502) staff       (20)        1 2023-06-27 23:16:41.000000 pdm_utils-1.1.0/src/pdm_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 labad      (502) staff       (20)       54 2023-06-27 23:16:41.000000 pdm_utils-1.1.0/src/pdm_utils.egg-info/entry_points.txt
+-rw-r--r--   0 labad      (502) staff       (20)      238 2023-06-27 23:16:41.000000 pdm_utils-1.1.0/src/pdm_utils.egg-info/requires.txt
+-rw-r--r--   0 labad      (502) staff       (20)       10 2023-06-27 23:16:41.000000 pdm_utils-1.1.0/src/pdm_utils.egg-info/top_level.txt
+drwxr-xr-x   0 labad      (502) staff       (20)        0 2023-06-27 23:16:41.498634 pdm_utils-1.1.0/tests/
+-rw-r--r--   0 labad      (502) staff       (20)    20144 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/tests/test_data_utils.py
+-rw-r--r--   0 labad      (502) staff       (20)    15441 2020-10-23 17:14:54.000000 pdm_utils-1.1.0/tests/test_db_utils.py
```

### Comparing `pdm_utils-1.0.1/LICENSE` & `pdm_utils-1.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/PKG-INFO` & `pdm_utils-1.1.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pdm_utils
-Version: 1.0.1
+Version: 1.1.0
 Summary: MySQL phage genomics database management utilities
 Home-page: https://github.com/SEA-PHAGES/pdm_utils
 Author: Christian Gauthier
 Author-email: chg60@pitt.edu
 Project-URL: Documentation, https://pdm-utils.readthedocs.io/en/latest/
 Project-URL: Source, https://github.com/SEA-PHAGES/pdm_utils/
 Classifier: Intended Audience :: Science/Research
```

### Comparing `pdm_utils-1.0.1/README.md` & `pdm_utils-1.1.0/README.md`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/setup.cfg` & `pdm_utils-1.1.0/setup.cfg`

 * *Files 11% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [metadata]
 license_files = LICENSE
 name = pdm_utils
-version = 1.0.1
+version = 1.1.0
 author = Christian Gauthier
 author_email = chg60@pitt.edu
 description = MySQL phage genomics database management utilities
 long_description = file:README.md
 long_description_content_type = text/markdown
 url = https://github.com/SEA-PHAGES/pdm_utils
 project_urls = 
@@ -26,20 +26,25 @@
 [options]
 python_requires = >=3.7
 package_dir = 
 	=src
 packages = find:
 install_requires = 
 	biopython == 1.77
+	kaleido == 0.2.1
 	networkx >= 2.4
+	pandas == 2.0.2
 	paramiko >= 2.7.2
+	parasail == 1.3.4
 	phammseqs >= 1.0.4
+	psutil == 5.9.5
 	pybiolib >= 1.1.918
 	pymysql == 0.9.3
 	pyyaml >= 5.3.1
+	sciit-learn == 1.2.2
 	sqlalchemy == 1.4.2
 	tabulate >= 0.8.3
 	urllib3 >= 1.25.8
 
 [options.packages.find]
 where = src
 include =
```

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/alchemyhandler.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/alchemyhandler.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/aragornhandler.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/aragornhandler.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/bundle.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/bundle.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/cds.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/cds.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/cdspair.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/cdspair.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/dbcomparesummary.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/dbcomparesummary.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/evaluation.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/evaluation.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/fileio.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/fileio.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/filter.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/filter.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/genome.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/genome.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/genomepair.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/genomepair.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/genometriad.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/genometriad.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/progress.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/progress.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/randomfieldupdatehandler.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/randomfieldupdatehandler.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/source.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/source.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/ticket.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/ticket.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/tmrna.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/tmrna.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/trna.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/trna.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/classes/trnascansehandler.py` & `pdm_utils-1.1.0/src/pdm_utils/classes/trnascansehandler.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/constants/constants.py` & `pdm_utils-1.1.0/src/pdm_utils/constants/constants.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/constants/db_schema_0.py` & `pdm_utils-1.1.0/src/pdm_utils/constants/db_schema_0.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/constants/eval_descriptions.py` & `pdm_utils-1.1.0/src/pdm_utils/constants/eval_descriptions.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/constants/schema_conversions.py` & `pdm_utils-1.1.0/src/pdm_utils/constants/schema_conversions.py`

 * *Files 0% similar despite different names*

```diff
@@ -371,18 +371,20 @@
                   `ID` int(10) unsigned NOT NULL AUTO_INCREMENT,
                   `GeneID` varchar(35) DEFAULT NULL,
                   `QueryStart` int(10) unsigned NOT NULL,
                   `QueryEnd` int(10) unsigned NOT NULL,
                   `Type` enum('signal', 'transmembrane') DEFAULT NULL,
                   `Source`  enum('deeptmhmm', 'sosui') DEFAULT NULL,
                   PRIMARY KEY (`ID`),
-                  KEY `GeneID` (`GeneID`),
+                  CONSTRAINT `fk_gene_transmembrane_gene`
                   FOREIGN KEY (`GeneID`) REFERENCES `gene` (`GeneID`)
+                  ON DELETE CASCADE
+                  ON UPDATE CASCADE
                 ) ENGINE=InnoDB DEFAULT CHARSET=latin1;""",
-            """ALTER TABLE `gene` ADD COLUMN `MembraneStatus` tinyint(1) NOT NULL AFTER `PhamID`;""",
+            """ALTER TABLE `gene` ADD COLUMN `MembraneStatus` tinyint(1) DEFAULT 1 NOT NULL AFTER `PhamID`;""",
             """UPDATE `version` SET `SchemaVersion` = 11;"""
             ],
         step_summary_dict: {
             inaccurate_column: [
                 "gene.MembraneStatus"
                 ]
             }
```

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/annotation.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/annotation.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/basic.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/basic.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/cartography.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/cartography.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/configfile.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/configfile.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/deeptmhmm.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/deeptmhmm.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/eval_modes.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/eval_modes.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/fasta.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/fasta.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/fileio.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/fileio.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/flat_files.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/flat_files.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/multiprocess.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/multiprocess.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/multithread.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/multithread.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/mysqldb.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/mysqldb.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/mysqldb_basic.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/mysqldb_basic.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/ncbi.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/ncbi.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/parsing.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/parsing.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/phagesdb.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/phagesdb.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/pham_alignment.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/pham_alignment.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/phameration.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/phameration.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/pipeline_shells.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/pipeline_shells.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/pipelines_basic.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/pipelines_basic.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/querying.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/querying.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/rpsblast.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/rpsblast.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/server.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/server.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/subprocess.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/subprocess.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/tickets.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/tickets.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/functions/url_basic.py` & `pdm_utils-1.1.0/src/pdm_utils/functions/url_basic.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/compare_db.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/compare_db.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/convert_db.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/convert_db.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/export_db.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/export_db.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/find_domains.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/find_domains.py`

 * *Files 0% similar despite different names*

```diff
@@ -96,15 +96,15 @@
     :param cdd_dir: directory where Cdd database files live
     :type cdd_dir: pathlib.Path
     :return: cdd_name
     """
     filenames = list()
     for filepath in cdd_dir.iterdir():
         if filepath.is_file() and filepath.name != ".DS_Store":
-            filenames.append(filepath.stem)
+            filenames.append(filepath.name.split(".")[0])
 
     name_set = set(filenames)
     if len(name_set) == 1:
         return filenames[0]
 
 
 def find_domains(program, sequences, cdd, evalue, cpus):
```

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/find_membrane.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/find_membrane.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/find_transmembrane.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/find_transmembrane.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/freeze_db.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/freeze_db.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/get_data.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/get_data.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/get_db.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/get_db.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/get_gb_records.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/get_gb_records.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/import_genome.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/import_genome.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/pham_finder.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/pham_finder.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/pham_review.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/pham_review.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/phamerate.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/phamerate.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/push_db.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/push_db.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/revise.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/revise.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/pipelines/update_field.py` & `pdm_utils-1.1.0/src/pdm_utils/pipelines/update_field.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/src/pdm_utils/run.py` & `pdm_utils-1.1.0/src/pdm_utils/run.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 """Use this script to run all pipelines within the pipelines folder.
 It verifies a valid pipeline is selected,
 then passes all command line arguments to the main pipeline module.
 """
 import sys
 import argparse
 
+from pdm_utils.pipelines import cluster_db
 from pdm_utils.pipelines import compare_db
 from pdm_utils.pipelines import convert_db
 from pdm_utils.pipelines import export_db
 from pdm_utils.pipelines import find_domains
 from pdm_utils.pipelines import find_transmembrane
 from pdm_utils.pipelines import freeze_db
 from pdm_utils.pipelines import get_data
@@ -18,18 +19,18 @@
 from pdm_utils.pipelines import phamerate
 from pdm_utils.pipelines import pham_finder
 from pdm_utils.pipelines import push_db
 from pdm_utils.pipelines import revise
 from pdm_utils.pipelines import pham_review
 from pdm_utils.pipelines import update_field
 
-VALID_PIPELINES = {"compare", "convert", "export", "find_domains",
-                   "find_transmembrane", "find_phams", "freeze", "get_data",
-                   "get_db", "get_gb_records", "import", "phamerate", "push",
-                   "revise", "pham_review", "update"}
+VALID_PIPELINES = {"cluster_db", "compare", "convert", "export",
+                   "find_domains", "find_transmembrane", "find_phams",
+                   "freeze", "get_data", "get_db", "get_gb_records", "import",
+                   "phamerate", "push", "revise", "pham_review", "update"}
 
 
 def parse_args(unparsed_args):
     """
     Use argparse to verify pipeline argument only.
 
     :param unparsed_args: raw command line args
@@ -54,15 +55,17 @@
     if not unparsed_args:
         if len(sys.argv) == 1:
             sys.argv.append("-h")
         unparsed_args = sys.argv
 
     args = parse_args(unparsed_args)
 
-    if args.pipeline == "compare":
+    if args.pipeline == "cluster_db":
+        cluster_db.main(unparsed_args)
+    elif args.pipeline == "compare":
         compare_db.main(unparsed_args)
     elif args.pipeline == "convert":
         convert_db.main(unparsed_args)
     elif args.pipeline == "find_transmembrane":
         find_transmembrane.main(unparsed_args)
     elif args.pipeline == "export":
         export_db.main(unparsed_args)
```

### Comparing `pdm_utils-1.0.1/src/pdm_utils.egg-info/PKG-INFO` & `pdm_utils-1.1.0/src/pdm_utils.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pdm-utils
-Version: 1.0.1
+Version: 1.1.0
 Summary: MySQL phage genomics database management utilities
 Home-page: https://github.com/SEA-PHAGES/pdm_utils
 Author: Christian Gauthier
 Author-email: chg60@pitt.edu
 Project-URL: Documentation, https://pdm-utils.readthedocs.io/en/latest/
 Project-URL: Source, https://github.com/SEA-PHAGES/pdm_utils/
 Classifier: Intended Audience :: Science/Research
```

### Comparing `pdm_utils-1.0.1/src/pdm_utils.egg-info/SOURCES.txt` & `pdm_utils-1.1.0/src/pdm_utils.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -61,14 +61,15 @@
 src/pdm_utils/functions/querying.py
 src/pdm_utils/functions/rpsblast.py
 src/pdm_utils/functions/server.py
 src/pdm_utils/functions/subprocess.py
 src/pdm_utils/functions/tickets.py
 src/pdm_utils/functions/url_basic.py
 src/pdm_utils/pipelines/__init__.py
+src/pdm_utils/pipelines/cluster_db.py
 src/pdm_utils/pipelines/compare_db.py
 src/pdm_utils/pipelines/convert_db.py
 src/pdm_utils/pipelines/export_db.py
 src/pdm_utils/pipelines/find_domains.py
 src/pdm_utils/pipelines/find_membrane.py
 src/pdm_utils/pipelines/find_transmembrane.py
 src/pdm_utils/pipelines/freeze_db.py
```

### Comparing `pdm_utils-1.0.1/tests/test_data_utils.py` & `pdm_utils-1.1.0/tests/test_data_utils.py`

 * *Files identical despite different names*

### Comparing `pdm_utils-1.0.1/tests/test_db_utils.py` & `pdm_utils-1.1.0/tests/test_db_utils.py`

 * *Files identical despite different names*


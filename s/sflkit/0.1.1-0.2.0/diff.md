# Comparing `tmp/sflkit-0.1.1.tar.gz` & `tmp/sflkit-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sflkit-0.1.1.tar", last modified: Fri Mar 24 13:02:48 2023, max compression
+gzip compressed data, was "sflkit-0.2.0.tar", last modified: Wed Jun 28 11:12:49 2023, max compression
```

## Comparing `sflkit-0.1.1.tar` & `sflkit-0.2.0.tar`

### file list

```diff
@@ -1,73 +1,74 @@
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.111436 sflkit-0.1.1/
--rw-r--r--   0 marius     (501) staff       (20)     1112 2023-03-23 09:55:10.000000 sflkit-0.1.1/LICENSE
--rw-r--r--   0 marius     (501) staff       (20)     4800 2023-03-24 13:02:48.111581 sflkit-0.1.1/PKG-INFO
--rw-r--r--   0 marius     (501) staff       (20)     4045 2023-03-24 12:56:45.000000 sflkit-0.1.1/README.md
--rw-r--r--   0 marius     (501) staff       (20)      948 2023-03-24 12:56:55.000000 sflkit-0.1.1/pyproject.toml
--rw-r--r--   0 marius     (501) staff       (20)     1242 2023-03-24 13:02:48.112169 sflkit-0.1.1/setup.cfg
--rw-r--r--   0 marius     (501) staff       (20)       39 2023-03-23 09:55:13.000000 sflkit-0.1.1/setup.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.090333 sflkit-0.1.1/src/
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.095126 sflkit-0.1.1/src/SFLKit.egg-info/
--rw-r--r--   0 marius     (501) staff       (20)     4800 2023-03-24 13:02:48.000000 sflkit-0.1.1/src/SFLKit.egg-info/PKG-INFO
--rw-r--r--   0 marius     (501) staff       (20)     1918 2023-03-24 13:02:48.000000 sflkit-0.1.1/src/SFLKit.egg-info/SOURCES.txt
--rw-r--r--   0 marius     (501) staff       (20)        1 2023-03-24 13:02:48.000000 sflkit-0.1.1/src/SFLKit.egg-info/dependency_links.txt
--rw-r--r--   0 marius     (501) staff       (20)       43 2023-03-24 13:02:48.000000 sflkit-0.1.1/src/SFLKit.egg-info/entry_points.txt
--rw-r--r--   0 marius     (501) staff       (20)      277 2023-03-24 13:02:48.000000 sflkit-0.1.1/src/SFLKit.egg-info/requires.txt
--rw-r--r--   0 marius     (501) staff       (20)        7 2023-03-24 13:02:48.000000 sflkit-0.1.1/src/SFLKit.egg-info/top_level.txt
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.096190 sflkit-0.1.1/src/sflkit/
--rw-r--r--   0 marius     (501) staff       (20)     1808 2023-03-24 12:57:11.000000 sflkit-0.1.1/src/sflkit/__init__.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.099791 sflkit-0.1.1/src/sflkit/analysis/
--rw-r--r--   0 marius     (501) staff       (20)      161 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/analysis/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)     3331 2023-03-24 10:29:50.000000 sflkit-0.1.1/src/sflkit/analysis/analysis_type.py
--rw-r--r--   0 marius     (501) staff       (20)     2228 2023-03-23 17:28:40.000000 sflkit-0.1.1/src/sflkit/analysis/analyzer.py
--rw-r--r--   0 marius     (501) staff       (20)    13816 2023-03-24 11:51:43.000000 sflkit-0.1.1/src/sflkit/analysis/factory.py
--rw-r--r--   0 marius     (501) staff       (20)     1511 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/analysis/mapping.py
--rw-r--r--   0 marius     (501) staff       (20)    10720 2023-03-24 10:26:59.000000 sflkit-0.1.1/src/sflkit/analysis/predicate.py
--rw-r--r--   0 marius     (501) staff       (20)     1045 2023-03-24 10:29:08.000000 sflkit-0.1.1/src/sflkit/analysis/similarity.py
--rw-r--r--   0 marius     (501) staff       (20)    17367 2023-03-24 11:47:15.000000 sflkit-0.1.1/src/sflkit/analysis/spectra.py
--rw-r--r--   0 marius     (501) staff       (20)     1224 2023-03-23 15:58:48.000000 sflkit-0.1.1/src/sflkit/analysis/suggestion.py
--rw-r--r--   0 marius     (501) staff       (20)     3174 2023-03-23 17:38:06.000000 sflkit-0.1.1/src/sflkit/cli.py
--rw-r--r--   0 marius     (501) staff       (20)     3432 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/color.py
--rw-r--r--   0 marius     (501) staff       (20)    10870 2023-03-24 10:53:42.000000 sflkit-0.1.1/src/sflkit/config.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.100621 sflkit-0.1.1/src/sflkit/events/
--rw-r--r--   0 marius     (501) staff       (20)      362 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/events/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)    16791 2023-03-24 10:34:43.000000 sflkit-0.1.1/src/sflkit/events/event.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.101935 sflkit-0.1.1/src/sflkit/instrumentation/
--rw-r--r--   0 marius     (501) staff       (20)      665 2023-03-24 09:12:31.000000 sflkit-0.1.1/src/sflkit/instrumentation/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)     3437 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/instrumentation/dir_instrumentation.py
--rw-r--r--   0 marius     (501) staff       (20)      446 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/instrumentation/file_instrumentation.py
--rw-r--r--   0 marius     (501) staff       (20)     4947 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/instrumentation/lib.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.103811 sflkit-0.1.1/src/sflkit/language/
--rw-r--r--   0 marius     (501) staff       (20)      151 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/language/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)      353 2023-03-24 09:13:32.000000 sflkit-0.1.1/src/sflkit/language/extract.py
--rw-r--r--   0 marius     (501) staff       (20)      654 2023-03-23 15:08:14.000000 sflkit-0.1.1/src/sflkit/language/finder.py
--rw-r--r--   0 marius     (501) staff       (20)     3794 2023-03-23 14:04:24.000000 sflkit-0.1.1/src/sflkit/language/language.py
--rw-r--r--   0 marius     (501) staff       (20)     4063 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/language/meta.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.105179 sflkit-0.1.1/src/sflkit/language/python/
--rw-r--r--   0 marius     (501) staff       (20)        0 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/language/python/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)     8599 2023-03-23 15:16:00.000000 sflkit-0.1.1/src/sflkit/language/python/extract.py
--rw-r--r--   0 marius     (501) staff       (20)    26809 2023-03-23 14:19:50.000000 sflkit-0.1.1/src/sflkit/language/python/factory.py
--rw-r--r--   0 marius     (501) staff       (20)     2990 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/language/python/finder.py
--rw-r--r--   0 marius     (501) staff       (20)     6119 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/language/python/visitor.py
--rw-r--r--   0 marius     (501) staff       (20)     1085 2023-03-24 09:09:17.000000 sflkit-0.1.1/src/sflkit/language/visitor.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.106533 sflkit-0.1.1/src/sflkit/model/
--rw-r--r--   0 marius     (501) staff       (20)      163 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/model/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)      803 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/model/event_file.py
--rw-r--r--   0 marius     (501) staff       (20)     2073 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/model/model.py
--rw-r--r--   0 marius     (501) staff       (20)     1007 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/model/scope.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.107287 sflkit-0.1.1/src/sflkit/runners/
--rw-r--r--   0 marius     (501) staff       (20)      193 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/runners/__init__.py
--rw-r--r--   0 marius     (501) staff       (20)       60 2023-03-23 09:55:13.000000 sflkit-0.1.1/src/sflkit/runners/run.py
-drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-03-24 13:02:48.111182 sflkit-0.1.1/tests/
--rw-r--r--   0 marius     (501) staff       (20)     7986 2023-03-23 09:55:13.000000 sflkit-0.1.1/tests/test_analysis_objects.py
--rw-r--r--   0 marius     (501) staff       (20)     2057 2023-03-23 18:03:53.000000 sflkit-0.1.1/tests/test_cli.py
--rw-r--r--   0 marius     (501) staff       (20)     1025 2023-03-24 09:19:40.000000 sflkit-0.1.1/tests/test_color.py
--rw-r--r--   0 marius     (501) staff       (20)     6241 2023-03-24 10:54:37.000000 sflkit-0.1.1/tests/test_config.py
--rw-r--r--   0 marius     (501) staff       (20)    14051 2023-03-23 17:37:39.000000 sflkit-0.1.1/tests/test_events.py
--rw-r--r--   0 marius     (501) staff       (20)     1318 2023-03-23 17:37:40.000000 sflkit-0.1.1/tests/test_execution.py
--rw-r--r--   0 marius     (501) staff       (20)     5100 2023-03-23 17:37:39.000000 sflkit-0.1.1/tests/test_instrumentation.py
--rw-r--r--   0 marius     (501) staff       (20)     8849 2023-03-23 17:37:40.000000 sflkit-0.1.1/tests/test_language.py
--rw-r--r--   0 marius     (501) staff       (20)     2773 2023-03-23 09:55:13.000000 sflkit-0.1.1/tests/test_predicates.py
--rw-r--r--   0 marius     (501) staff       (20)      615 2023-03-23 15:20:53.000000 sflkit-0.1.1/tests/test_scope.py
--rw-r--r--   0 marius     (501) staff       (20)     4277 2023-03-24 10:31:44.000000 sflkit-0.1.1/tests/test_spectra.py
--rw-r--r--   0 marius     (501) staff       (20)    11301 2023-03-24 12:11:43.000000 sflkit-0.1.1/tests/test_suggestions.py
--rw-r--r--   0 marius     (501) staff       (20)     1912 2023-03-23 09:55:13.000000 sflkit-0.1.1/tests/test_visitors.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.632706 sflkit-0.2.0/
+-rw-r--r--   0 marius     (501) staff       (20)     1112 2023-03-23 09:55:10.000000 sflkit-0.2.0/LICENSE
+-rw-r--r--   0 marius     (501) staff       (20)     4817 2023-06-28 11:12:49.632827 sflkit-0.2.0/PKG-INFO
+-rw-r--r--   0 marius     (501) staff       (20)     4062 2023-03-24 13:14:28.000000 sflkit-0.2.0/README.md
+-rw-r--r--   0 marius     (501) staff       (20)      809 2023-06-28 11:07:58.000000 sflkit-0.2.0/pyproject.toml
+-rw-r--r--   0 marius     (501) staff       (20)     1242 2023-06-28 11:12:49.633424 sflkit-0.2.0/setup.cfg
+-rw-r--r--   0 marius     (501) staff       (20)       39 2023-03-23 09:55:13.000000 sflkit-0.2.0/setup.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.609956 sflkit-0.2.0/src/
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.615006 sflkit-0.2.0/src/SFLKit.egg-info/
+-rw-r--r--   0 marius     (501) staff       (20)     4817 2023-06-28 11:12:49.000000 sflkit-0.2.0/src/SFLKit.egg-info/PKG-INFO
+-rw-r--r--   0 marius     (501) staff       (20)     1939 2023-06-28 11:12:49.000000 sflkit-0.2.0/src/SFLKit.egg-info/SOURCES.txt
+-rw-r--r--   0 marius     (501) staff       (20)        1 2023-06-28 11:12:49.000000 sflkit-0.2.0/src/SFLKit.egg-info/dependency_links.txt
+-rw-r--r--   0 marius     (501) staff       (20)       43 2023-06-28 11:12:49.000000 sflkit-0.2.0/src/SFLKit.egg-info/entry_points.txt
+-rw-r--r--   0 marius     (501) staff       (20)      277 2023-06-28 11:12:49.000000 sflkit-0.2.0/src/SFLKit.egg-info/requires.txt
+-rw-r--r--   0 marius     (501) staff       (20)        7 2023-06-28 11:12:49.000000 sflkit-0.2.0/src/SFLKit.egg-info/top_level.txt
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.616270 sflkit-0.2.0/src/sflkit/
+-rw-r--r--   0 marius     (501) staff       (20)     1808 2023-06-28 11:08:12.000000 sflkit-0.2.0/src/sflkit/__init__.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.620717 sflkit-0.2.0/src/sflkit/analysis/
+-rw-r--r--   0 marius     (501) staff       (20)      161 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/analysis/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)     3331 2023-03-24 10:29:50.000000 sflkit-0.2.0/src/sflkit/analysis/analysis_type.py
+-rw-r--r--   0 marius     (501) staff       (20)     2228 2023-03-23 17:28:40.000000 sflkit-0.2.0/src/sflkit/analysis/analyzer.py
+-rw-r--r--   0 marius     (501) staff       (20)    13816 2023-03-24 11:51:43.000000 sflkit-0.2.0/src/sflkit/analysis/factory.py
+-rw-r--r--   0 marius     (501) staff       (20)     1511 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/analysis/mapping.py
+-rw-r--r--   0 marius     (501) staff       (20)    10720 2023-03-24 10:26:59.000000 sflkit-0.2.0/src/sflkit/analysis/predicate.py
+-rw-r--r--   0 marius     (501) staff       (20)     1045 2023-03-24 10:29:08.000000 sflkit-0.2.0/src/sflkit/analysis/similarity.py
+-rw-r--r--   0 marius     (501) staff       (20)    17367 2023-03-24 11:47:15.000000 sflkit-0.2.0/src/sflkit/analysis/spectra.py
+-rw-r--r--   0 marius     (501) staff       (20)     1224 2023-03-23 15:58:48.000000 sflkit-0.2.0/src/sflkit/analysis/suggestion.py
+-rw-r--r--   0 marius     (501) staff       (20)     3174 2023-03-23 17:38:06.000000 sflkit-0.2.0/src/sflkit/cli.py
+-rw-r--r--   0 marius     (501) staff       (20)     3432 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/color.py
+-rw-r--r--   0 marius     (501) staff       (20)    10870 2023-03-24 10:53:42.000000 sflkit-0.2.0/src/sflkit/config.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.621266 sflkit-0.2.0/src/sflkit/events/
+-rw-r--r--   0 marius     (501) staff       (20)      362 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/events/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)    16791 2023-03-24 10:34:43.000000 sflkit-0.2.0/src/sflkit/events/event.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.622495 sflkit-0.2.0/src/sflkit/instrumentation/
+-rw-r--r--   0 marius     (501) staff       (20)      665 2023-03-24 09:12:31.000000 sflkit-0.2.0/src/sflkit/instrumentation/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)     3437 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/instrumentation/dir_instrumentation.py
+-rw-r--r--   0 marius     (501) staff       (20)      446 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/instrumentation/file_instrumentation.py
+-rw-r--r--   0 marius     (501) staff       (20)     4947 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/instrumentation/lib.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.624596 sflkit-0.2.0/src/sflkit/language/
+-rw-r--r--   0 marius     (501) staff       (20)      151 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/language/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)      353 2023-03-24 09:13:32.000000 sflkit-0.2.0/src/sflkit/language/extract.py
+-rw-r--r--   0 marius     (501) staff       (20)      654 2023-03-23 15:08:14.000000 sflkit-0.2.0/src/sflkit/language/finder.py
+-rw-r--r--   0 marius     (501) staff       (20)     3794 2023-03-23 14:04:24.000000 sflkit-0.2.0/src/sflkit/language/language.py
+-rw-r--r--   0 marius     (501) staff       (20)     4063 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/language/meta.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.626186 sflkit-0.2.0/src/sflkit/language/python/
+-rw-r--r--   0 marius     (501) staff       (20)        0 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/language/python/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)     8599 2023-03-23 15:16:00.000000 sflkit-0.2.0/src/sflkit/language/python/extract.py
+-rw-r--r--   0 marius     (501) staff       (20)    26809 2023-03-23 14:19:50.000000 sflkit-0.2.0/src/sflkit/language/python/factory.py
+-rw-r--r--   0 marius     (501) staff       (20)     2990 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/language/python/finder.py
+-rw-r--r--   0 marius     (501) staff       (20)     6119 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/language/python/visitor.py
+-rw-r--r--   0 marius     (501) staff       (20)     1085 2023-03-24 09:09:17.000000 sflkit-0.2.0/src/sflkit/language/visitor.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.627575 sflkit-0.2.0/src/sflkit/model/
+-rw-r--r--   0 marius     (501) staff       (20)      163 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/model/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)      803 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/model/event_file.py
+-rw-r--r--   0 marius     (501) staff       (20)     2073 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/model/model.py
+-rw-r--r--   0 marius     (501) staff       (20)     1007 2023-03-23 09:55:13.000000 sflkit-0.2.0/src/sflkit/model/scope.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.628236 sflkit-0.2.0/src/sflkit/runners/
+-rw-r--r--   0 marius     (501) staff       (20)      293 2023-06-28 09:49:26.000000 sflkit-0.2.0/src/sflkit/runners/__init__.py
+-rw-r--r--   0 marius     (501) staff       (20)     7338 2023-06-28 09:49:26.000000 sflkit-0.2.0/src/sflkit/runners/run.py
+drwxr-xr-x   0 marius     (501) staff       (20)        0 2023-06-28 11:12:49.632465 sflkit-0.2.0/tests/
+-rw-r--r--   0 marius     (501) staff       (20)     7986 2023-03-23 09:55:13.000000 sflkit-0.2.0/tests/test_analysis_objects.py
+-rw-r--r--   0 marius     (501) staff       (20)     2057 2023-03-23 18:03:53.000000 sflkit-0.2.0/tests/test_cli.py
+-rw-r--r--   0 marius     (501) staff       (20)     1025 2023-03-24 09:19:40.000000 sflkit-0.2.0/tests/test_color.py
+-rw-r--r--   0 marius     (501) staff       (20)     6241 2023-03-24 10:54:37.000000 sflkit-0.2.0/tests/test_config.py
+-rw-r--r--   0 marius     (501) staff       (20)    14051 2023-03-23 17:37:39.000000 sflkit-0.2.0/tests/test_events.py
+-rw-r--r--   0 marius     (501) staff       (20)     1318 2023-03-23 17:37:40.000000 sflkit-0.2.0/tests/test_execution.py
+-rw-r--r--   0 marius     (501) staff       (20)     5100 2023-03-23 17:37:39.000000 sflkit-0.2.0/tests/test_instrumentation.py
+-rw-r--r--   0 marius     (501) staff       (20)     8849 2023-03-23 17:37:40.000000 sflkit-0.2.0/tests/test_language.py
+-rw-r--r--   0 marius     (501) staff       (20)     2773 2023-03-23 09:55:13.000000 sflkit-0.2.0/tests/test_predicates.py
+-rw-r--r--   0 marius     (501) staff       (20)     6061 2023-06-28 09:49:26.000000 sflkit-0.2.0/tests/test_runner.py
+-rw-r--r--   0 marius     (501) staff       (20)      615 2023-03-23 15:20:53.000000 sflkit-0.2.0/tests/test_scope.py
+-rw-r--r--   0 marius     (501) staff       (20)     4277 2023-03-24 10:31:44.000000 sflkit-0.2.0/tests/test_spectra.py
+-rw-r--r--   0 marius     (501) staff       (20)    11301 2023-03-24 12:11:43.000000 sflkit-0.2.0/tests/test_suggestions.py
+-rw-r--r--   0 marius     (501) staff       (20)     1912 2023-03-23 09:55:13.000000 sflkit-0.2.0/tests/test_visitors.py
```

### Comparing `sflkit-0.1.1/LICENSE` & `sflkit-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/PKG-INFO` & `sflkit-0.2.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sflkit
-Version: 0.1.1
+Version: 0.2.0
 Summary: SFLKit: : A Workbench for Statistical Fault Localization
 Home-page: https://github.com/uds-se/sflkit
 Author: Marius Smytzek & Andreas Zeller
 Author-email: Marius Smytzek <marius.smytzek@cispa.de>
 Project-URL: Homepage, https://github.com/uds-se/sflkit/
 Project-URL: Bug Tracker, https://github.com/uds-se/sflkit/issues
 Classifier: Intended Audience :: Science/Research
@@ -36,19 +36,19 @@
 
 SFLKit supports currently Python 3 but we plan on releasing further language support.
 
 ## Installation
 
 You need to navigate to the root directory of SFLKit and run
 ```sh
-pip install .
+pip install sflkit
 ```
 If you have a separate Python 2 and Python 3 on your machine you may need to run
 ```sh
-pip3 install .
+pip3 install sflkit
 ```
 
 ## Execution
 
 To execute SFLKit you need to create a config file matching your needs.
 
 ### Config
@@ -77,15 +77,15 @@
 
 This is the specification of the config file.
 
 ### Usage
 
 The general usage of SFLKit is
 ```
-usage: SFLKit [-h] [--debug] -c CONFIG {instrumentation,analyze} ...
+usage: sflkit [-h] [--debug] -c CONFIG {instrumentation,analyze} ...
 
 A workbench for statistical fault localization python programs and in the future other programs.
 
 optional arguments:
   -h, --help            show this help message and exit
   --debug               the debug flag to activate debug information
   -c CONFIG, --config CONFIG
@@ -98,20 +98,20 @@
                         the command to execute
     instrumentation     execute the instrumentation of subject
     analyze             execute the analysis of the collected predicates
 ```
 
 If you have adopted a config file for your investigations you need to execute
 ```sh
-python3 sfl.py -c path/to/your/config instrument
+sflkit -c path/to/your/config instrument
 ```
-to instrument the file. 
+to instrument the project defined by the file. 
 
 After the instrumentation, you can run your tests or experiments. But keep in mind to preserve the `EVENTS_PATH` file 
 for each failing and passing run.
 
 If you want to analyze your runs you need to execute
 ```sh
-python3 sfl.py -c path/to/your/config analyze
+sflkit -c path/to/your/config analyze
 ```
 which produces an output with the suggested code locations for the analysis objects and metrics defined in the config 
 file.
```

### Comparing `sflkit-0.1.1/README.md` & `sflkit-0.2.0/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -16,19 +16,19 @@
 
 SFLKit supports currently Python 3 but we plan on releasing further language support.
 
 ## Installation
 
 You need to navigate to the root directory of SFLKit and run
 ```sh
-pip install .
+pip install sflkit
 ```
 If you have a separate Python 2 and Python 3 on your machine you may need to run
 ```sh
-pip3 install .
+pip3 install sflkit
 ```
 
 ## Execution
 
 To execute SFLKit you need to create a config file matching your needs.
 
 ### Config
@@ -57,15 +57,15 @@
 
 This is the specification of the config file.
 
 ### Usage
 
 The general usage of SFLKit is
 ```
-usage: SFLKit [-h] [--debug] -c CONFIG {instrumentation,analyze} ...
+usage: sflkit [-h] [--debug] -c CONFIG {instrumentation,analyze} ...
 
 A workbench for statistical fault localization python programs and in the future other programs.
 
 optional arguments:
   -h, --help            show this help message and exit
   --debug               the debug flag to activate debug information
   -c CONFIG, --config CONFIG
@@ -78,20 +78,20 @@
                         the command to execute
     instrumentation     execute the instrumentation of subject
     analyze             execute the analysis of the collected predicates
 ```
 
 If you have adopted a config file for your investigations you need to execute
 ```sh
-python3 sfl.py -c path/to/your/config instrument
+sflkit -c path/to/your/config instrument
 ```
-to instrument the file. 
+to instrument the project defined by the file. 
 
 After the instrumentation, you can run your tests or experiments. But keep in mind to preserve the `EVENTS_PATH` file 
 for each failing and passing run.
 
 If you want to analyze your runs you need to execute
 ```sh
-python3 sfl.py -c path/to/your/config analyze
+sflkit -c path/to/your/config analyze
 ```
 which produces an output with the suggested code locations for the analysis objects and metrics defined in the config 
 file.
```

### Comparing `sflkit-0.1.1/pyproject.toml` & `sflkit-0.2.0/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -3,15 +3,15 @@
     "setuptools>=67.6.0",
     "wheel"
 ]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "sflkit"
-version = "0.1.1"
+version = "0.2.0"
 authors = [
     { name = "Marius Smytzek", email = "marius.smytzek@cispa.de" },
 ]
 description = "SFLKit: : A Workbench for Statistical Fault Localization"
 readme = "README.md"
 license = { file = "COPYING" }
 requires-python = ">=3.10"
@@ -26,15 +26,7 @@
 [project.urls]
 "Homepage" = "https://github.com/uds-se/sflkit/"
 "Bug Tracker" = "https://github.com/uds-se/sflkit/issues"
 
 [tool.black]
 line-length = 88
 target-version = ['py310']
-extend-exclude = '''
-(
-    ^/src/isla/bnf/*
-  | ^/src/isla/isla_language/*
-  | ^/src/isla/mexpr_lexer/*
-  | ^/src/isla/mexpr_parser/*
-)
-'''
```

### Comparing `sflkit-0.1.1/setup.cfg` & `sflkit-0.2.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/SFLKit.egg-info/PKG-INFO` & `sflkit-0.2.0/src/SFLKit.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sflkit
-Version: 0.1.1
+Version: 0.2.0
 Summary: SFLKit: : A Workbench for Statistical Fault Localization
 Home-page: https://github.com/uds-se/sflkit
 Author: Marius Smytzek & Andreas Zeller
 Author-email: Marius Smytzek <marius.smytzek@cispa.de>
 Project-URL: Homepage, https://github.com/uds-se/sflkit/
 Project-URL: Bug Tracker, https://github.com/uds-se/sflkit/issues
 Classifier: Intended Audience :: Science/Research
@@ -36,19 +36,19 @@
 
 SFLKit supports currently Python 3 but we plan on releasing further language support.
 
 ## Installation
 
 You need to navigate to the root directory of SFLKit and run
 ```sh
-pip install .
+pip install sflkit
 ```
 If you have a separate Python 2 and Python 3 on your machine you may need to run
 ```sh
-pip3 install .
+pip3 install sflkit
 ```
 
 ## Execution
 
 To execute SFLKit you need to create a config file matching your needs.
 
 ### Config
@@ -77,15 +77,15 @@
 
 This is the specification of the config file.
 
 ### Usage
 
 The general usage of SFLKit is
 ```
-usage: SFLKit [-h] [--debug] -c CONFIG {instrumentation,analyze} ...
+usage: sflkit [-h] [--debug] -c CONFIG {instrumentation,analyze} ...
 
 A workbench for statistical fault localization python programs and in the future other programs.
 
 optional arguments:
   -h, --help            show this help message and exit
   --debug               the debug flag to activate debug information
   -c CONFIG, --config CONFIG
@@ -98,20 +98,20 @@
                         the command to execute
     instrumentation     execute the instrumentation of subject
     analyze             execute the analysis of the collected predicates
 ```
 
 If you have adopted a config file for your investigations you need to execute
 ```sh
-python3 sfl.py -c path/to/your/config instrument
+sflkit -c path/to/your/config instrument
 ```
-to instrument the file. 
+to instrument the project defined by the file. 
 
 After the instrumentation, you can run your tests or experiments. But keep in mind to preserve the `EVENTS_PATH` file 
 for each failing and passing run.
 
 If you want to analyze your runs you need to execute
 ```sh
-python3 sfl.py -c path/to/your/config analyze
+sflkit -c path/to/your/config analyze
 ```
 which produces an output with the suggested code locations for the analysis objects and metrics defined in the config 
 file.
```

### Comparing `sflkit-0.1.1/src/SFLKit.egg-info/SOURCES.txt` & `sflkit-0.2.0/src/SFLKit.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -56,11 +56,12 @@
 tests/test_color.py
 tests/test_config.py
 tests/test_events.py
 tests/test_execution.py
 tests/test_instrumentation.py
 tests/test_language.py
 tests/test_predicates.py
+tests/test_runner.py
 tests/test_scope.py
 tests/test_spectra.py
 tests/test_suggestions.py
 tests/test_visitors.py
```

### Comparing `sflkit-0.1.1/src/sflkit/__init__.py` & `sflkit-0.2.0/src/sflkit/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from sflkit.analysis.analyzer import Analyzer
 from sflkit.analysis.predicate import Predicate
 from sflkit.config import Config, parse_config
 from sflkit.instrumentation.dir_instrumentation import DirInstrumentation
 
-__version__ = "0.1.1"
+__version__ = "0.2.0"
 
 
 def instrument_config(conf: Config, event_dump: str = None):
     instrumentation = DirInstrumentation(conf.visitor)
     instrumentation.instrument(
         conf.target_path,
         conf.instrument_working,
```

### Comparing `sflkit-0.1.1/src/sflkit/analysis/analysis_type.py` & `sflkit-0.2.0/src/sflkit/analysis/analysis_type.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/analyzer.py` & `sflkit-0.2.0/src/sflkit/analysis/analyzer.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/factory.py` & `sflkit-0.2.0/src/sflkit/analysis/factory.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/mapping.py` & `sflkit-0.2.0/src/sflkit/analysis/mapping.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/predicate.py` & `sflkit-0.2.0/src/sflkit/analysis/predicate.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/similarity.py` & `sflkit-0.2.0/src/sflkit/analysis/similarity.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/spectra.py` & `sflkit-0.2.0/src/sflkit/analysis/spectra.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/analysis/suggestion.py` & `sflkit-0.2.0/src/sflkit/analysis/suggestion.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/cli.py` & `sflkit-0.2.0/src/sflkit/cli.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/color.py` & `sflkit-0.2.0/src/sflkit/color.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/config.py` & `sflkit-0.2.0/src/sflkit/config.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/events/event.py` & `sflkit-0.2.0/src/sflkit/events/event.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/instrumentation/__init__.py` & `sflkit-0.2.0/src/sflkit/instrumentation/__init__.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/instrumentation/dir_instrumentation.py` & `sflkit-0.2.0/src/sflkit/instrumentation/dir_instrumentation.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/instrumentation/lib.py` & `sflkit-0.2.0/src/sflkit/instrumentation/lib.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/finder.py` & `sflkit-0.2.0/src/sflkit/language/finder.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/language.py` & `sflkit-0.2.0/src/sflkit/language/language.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/meta.py` & `sflkit-0.2.0/src/sflkit/language/meta.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/python/extract.py` & `sflkit-0.2.0/src/sflkit/language/python/extract.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/python/factory.py` & `sflkit-0.2.0/src/sflkit/language/python/factory.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/python/finder.py` & `sflkit-0.2.0/src/sflkit/language/python/finder.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/python/visitor.py` & `sflkit-0.2.0/src/sflkit/language/python/visitor.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/language/visitor.py` & `sflkit-0.2.0/src/sflkit/language/visitor.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/model/event_file.py` & `sflkit-0.2.0/src/sflkit/model/event_file.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/model/model.py` & `sflkit-0.2.0/src/sflkit/model/model.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/src/sflkit/model/scope.py` & `sflkit-0.2.0/src/sflkit/model/scope.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_analysis_objects.py` & `sflkit-0.2.0/tests/test_analysis_objects.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_cli.py` & `sflkit-0.2.0/tests/test_cli.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_color.py` & `sflkit-0.2.0/tests/test_color.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_config.py` & `sflkit-0.2.0/tests/test_config.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_events.py` & `sflkit-0.2.0/tests/test_events.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_execution.py` & `sflkit-0.2.0/tests/test_execution.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_instrumentation.py` & `sflkit-0.2.0/tests/test_instrumentation.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_language.py` & `sflkit-0.2.0/tests/test_language.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_predicates.py` & `sflkit-0.2.0/tests/test_predicates.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_scope.py` & `sflkit-0.2.0/tests/test_scope.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_spectra.py` & `sflkit-0.2.0/tests/test_spectra.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_suggestions.py` & `sflkit-0.2.0/tests/test_suggestions.py`

 * *Files identical despite different names*

### Comparing `sflkit-0.1.1/tests/test_visitors.py` & `sflkit-0.2.0/tests/test_visitors.py`

 * *Files identical despite different names*


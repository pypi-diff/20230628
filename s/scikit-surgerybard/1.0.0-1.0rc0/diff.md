# Comparing `tmp/scikit-surgerybard-1.0.0.tar.gz` & `tmp/scikit-surgerybard-1.0rc0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "scikit-surgerybard-1.0.0.tar", last modified: Wed Jun 28 06:20:08 2023, max compression
+gzip compressed data, was "scikit-surgerybard-1.0rc0.tar", last modified: Thu Mar 30 20:48:40 2023, max compression
```

## Comparing `scikit-surgerybard-1.0.0.tar` & `scikit-surgerybard-1.0rc0.tar`

### file list

```diff
@@ -1,62 +1,62 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1519 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       56 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     4753 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3104 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4753 2023-06-28 06:20:08.000000 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1602 2023-06-28 06:20:08.000000 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:20:08.000000 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      419 2023-06-28 06:20:08.000000 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-28 06:20:08.000000 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 06:20:08.000000 scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      168 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2383 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/sksurgerybard/
--rwxr-xr-x   0 runner    (1001) docker     (123)      113 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/sksurgerybard/_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/sksurgerybard/algorithms/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/algorithms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3899 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/algorithms/bard_config_algorithms.py
--rw-r--r--   0 runner    (1001) docker     (123)     1398 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/algorithms/bard_config_speech.py
--rw-r--r--   0 runner    (1001) docker     (123)     1396 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/algorithms/decimation.py
--rw-r--r--   0 runner    (1001) docker     (123)     2648 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/algorithms/pointer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/sksurgerybard/interaction/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/interaction/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6091 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/interaction/interaction.py
--rw-r--r--   0 runner    (1001) docker     (123)     3404 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/interaction/speech_interaction.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/sksurgerybard/tracking/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/tracking/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4959 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/tracking/bard_tracking.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/sksurgerybard/ui/
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/ui/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      742 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/ui/bard_procrustes_app.py
--rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/ui/bard_procrustes_command_line.py
--rw-r--r--   0 runner    (1001) docker     (123)      846 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/ui/sksurgerybard_command_app.py
--rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/ui/sksurgerybard_command_line.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/sksurgerybard/visualisation/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/visualisation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12435 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/visualisation/bard_visualisation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.572140 scikit-surgerybard-1.0.0/sksurgerybard/widgets/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/widgets/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10530 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/sksurgerybard/widgets/bard_overlay_app.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.568140 scikit-surgerybard-1.0.0/tests/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/tests/algorithms/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/algorithms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4972 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/algorithms/test_configure_bard.py
--rw-r--r--   0 runner    (1001) docker     (123)      456 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/algorithms/test_decimation.py
--rw-r--r--   0 runner    (1001) docker     (123)     2232 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/algorithms/test_pointer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/tests/interaction/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/interaction/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10606 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/interaction/test_interaction.py
--rw-r--r--   0 runner    (1001) docker     (123)     3583 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/interaction/test_speech_interation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/tests/tracking/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/tracking/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6068 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/tracking/test_tracking.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/tests/visualisation/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/visualisation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13686 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/visualisation/test_visualisation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:20:08.576141 scikit-surgerybard-1.0.0/tests/widgets/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/widgets/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10139 2023-06-28 06:19:53.000000 scikit-surgerybard-1.0.0/tests/widgets/test_bard_overlay.py
--rw-r--r--   0 runner    (1001) docker     (123)    83607 2023-06-28 06:20:07.000000 scikit-surgerybard-1.0.0/versioneer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1519 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       56 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4744 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3108 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4744 2023-03-30 20:48:40.000000 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1602 2023-03-30 20:48:40.000000 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-30 20:48:40.000000 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      419 2023-03-30 20:48:40.000000 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      216 2023-03-30 20:48:40.000000 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-03-30 20:48:40.000000 scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      168 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2299 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.182561 scikit-surgerybard-1.0rc0/sksurgerybard/
+-rwxr-xr-x   0 runner    (1001) docker     (123)      113 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      498 2023-03-30 20:48:40.182561 scikit-surgerybard-1.0rc0/sksurgerybard/_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3899 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/bard_config_algorithms.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1398 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/bard_config_speech.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1396 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/decimation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2648 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/pointer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/sksurgerybard/interaction/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/interaction/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6091 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/interaction/interaction.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3404 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/interaction/speech_interaction.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/sksurgerybard/tracking/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/tracking/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4959 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/tracking/bard_tracking.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/sksurgerybard/ui/
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/ui/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      742 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/ui/bard_procrustes_app.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/ui/bard_procrustes_command_line.py
+-rw-r--r--   0 runner    (1001) docker     (123)      846 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/ui/sksurgerybard_command_app.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/ui/sksurgerybard_command_line.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/sksurgerybard/visualisation/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/visualisation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12435 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/visualisation/bard_visualisation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/sksurgerybard/widgets/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/widgets/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10530 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/sksurgerybard/widgets/bard_overlay_app.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.174561 scikit-surgerybard-1.0rc0/tests/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/tests/algorithms/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/algorithms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4972 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/algorithms/test_configure_bard.py
+-rw-r--r--   0 runner    (1001) docker     (123)      456 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/algorithms/test_decimation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2232 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/algorithms/test_pointer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/tests/interaction/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/interaction/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10606 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/interaction/test_interaction.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3583 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/interaction/test_speech_interation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/tests/tracking/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/tracking/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6068 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/tracking/test_tracking.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/tests/visualisation/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/visualisation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13686 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/visualisation/test_visualisation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:40.178561 scikit-surgerybard-1.0rc0/tests/widgets/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/widgets/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10139 2023-03-30 20:48:28.000000 scikit-surgerybard-1.0rc0/tests/widgets/test_bard_overlay.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83607 2023-03-30 20:48:39.000000 scikit-surgerybard-1.0rc0/versioneer.py
```

### Comparing `scikit-surgerybard-1.0.0/LICENSE` & `scikit-surgerybard-1.0rc0/LICENSE`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/PKG-INFO` & `scikit-surgerybard-1.0rc0/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: scikit-surgerybard
-Version: 1.0.0
+Version: 1.0rc0
 Summary: scikit-surgerybard is a Basic Augmented Reality Demo (BARD)based on scikit-surgery (SNAPPY)
 Home-page: https://github.com/SciKit-Surgery/scikit-surgerybard
 Author: Stephen Thompson
 Author-email: s.thompson@ucl.ac.uk
 License: BSD-3 license
 Description: Basic Augmented Reality Demo.
         ===============================
@@ -38,16 +38,16 @@
            :alt: The SciKit-Surgery paper
         
         .. image:: https://img.shields.io/twitter/follow/scikit_surgery?style=social
            :target: https://twitter.com/scikit_surgery?ref_src=twsrc%5Etfw
            :alt: Follow scikit_surgery on twitter
         
         
-        Author(s): Miguel Xochicale, Thomas Dowrick, Stephen Thompson and Matt Clarkson;
-        Contributor(s): Mian Ahmad.
+        Author(s): Stephen Thompson and Matt Clarkson;
+        Contributor(s): Miguel Xochicale, Thomas Dowrick, and Mian Ahmad.
         
         Basic Augmented Reality Demo (BARD) is part of the `SciKit-Surgery`_ software project, developed at the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_, part of `University College London (UCL)`_.
         
         The BARD is tested on Python 3.8. and may support other Python versions.
         
         
         Developing
@@ -93,18 +93,18 @@
         .. _`Wellcome`: https://wellcome.ac.uk/
         .. _`EPSRC`: https://www.epsrc.ac.uk/
         .. _`contributing guidelines`: https://github.com/SciKit-Surgery/scikit-surgerybard/blob/master/CONTRIBUTING.rst
         .. _`license file`: https://github.com/SciKit-Surgery/scikit-surgerybard/blob/master/LICENSE
         .. _`issue`: https://github.com/SciKit-Surgery/scikit-surgerybard/issues/new
 Keywords: medical imaging
 Platform: UNKNOWN
-Classifier: Development Status :: 5 - Production/Stable
+Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Healthcare Industry
 Classifier: Intended Audience :: Information Technology
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3
 Classifier: Topic :: Scientific/Engineering :: Information Analysis
 Classifier: Topic :: Scientific/Engineering :: Medical Science Apps.
 Description-Content-Type: text/x-rst
```

### Comparing `scikit-surgerybard-1.0.0/README.rst` & `scikit-surgerybard-1.0rc0/README.rst`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,16 @@
    :alt: The SciKit-Surgery paper
 
 .. image:: https://img.shields.io/twitter/follow/scikit_surgery?style=social
    :target: https://twitter.com/scikit_surgery?ref_src=twsrc%5Etfw
    :alt: Follow scikit_surgery on twitter
 
 
-Author(s): Miguel Xochicale, Thomas Dowrick, Stephen Thompson and Matt Clarkson;
-Contributor(s): Mian Ahmad.
+Author(s): Stephen Thompson and Matt Clarkson;
+Contributor(s): Miguel Xochicale, Thomas Dowrick, and Mian Ahmad.
 
 Basic Augmented Reality Demo (BARD) is part of the `SciKit-Surgery`_ software project, developed at the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_, part of `University College London (UCL)`_.
 
 The BARD is tested on Python 3.8. and may support other Python versions.
 
 
 Developing
```

### Comparing `scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/PKG-INFO` & `scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: scikit-surgerybard
-Version: 1.0.0
+Version: 1.0rc0
 Summary: scikit-surgerybard is a Basic Augmented Reality Demo (BARD)based on scikit-surgery (SNAPPY)
 Home-page: https://github.com/SciKit-Surgery/scikit-surgerybard
 Author: Stephen Thompson
 Author-email: s.thompson@ucl.ac.uk
 License: BSD-3 license
 Description: Basic Augmented Reality Demo.
         ===============================
@@ -38,16 +38,16 @@
            :alt: The SciKit-Surgery paper
         
         .. image:: https://img.shields.io/twitter/follow/scikit_surgery?style=social
            :target: https://twitter.com/scikit_surgery?ref_src=twsrc%5Etfw
            :alt: Follow scikit_surgery on twitter
         
         
-        Author(s): Miguel Xochicale, Thomas Dowrick, Stephen Thompson and Matt Clarkson;
-        Contributor(s): Mian Ahmad.
+        Author(s): Stephen Thompson and Matt Clarkson;
+        Contributor(s): Miguel Xochicale, Thomas Dowrick, and Mian Ahmad.
         
         Basic Augmented Reality Demo (BARD) is part of the `SciKit-Surgery`_ software project, developed at the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_, part of `University College London (UCL)`_.
         
         The BARD is tested on Python 3.8. and may support other Python versions.
         
         
         Developing
@@ -93,18 +93,18 @@
         .. _`Wellcome`: https://wellcome.ac.uk/
         .. _`EPSRC`: https://www.epsrc.ac.uk/
         .. _`contributing guidelines`: https://github.com/SciKit-Surgery/scikit-surgerybard/blob/master/CONTRIBUTING.rst
         .. _`license file`: https://github.com/SciKit-Surgery/scikit-surgerybard/blob/master/LICENSE
         .. _`issue`: https://github.com/SciKit-Surgery/scikit-surgerybard/issues/new
 Keywords: medical imaging
 Platform: UNKNOWN
-Classifier: Development Status :: 5 - Production/Stable
+Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Healthcare Industry
 Classifier: Intended Audience :: Information Technology
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3
 Classifier: Topic :: Scientific/Engineering :: Information Analysis
 Classifier: Topic :: Scientific/Engineering :: Medical Science Apps.
 Description-Content-Type: text/x-rst
```

### Comparing `scikit-surgerybard-1.0.0/scikit_surgerybard.egg-info/SOURCES.txt` & `scikit-surgerybard-1.0rc0/scikit_surgerybard.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/setup.py` & `scikit-surgerybard-1.0rc0/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -14,33 +14,33 @@
     name='scikit-surgerybard',
     version=versioneer.get_version(),
     cmdclass=versioneer.get_cmdclass(),
     description='scikit-surgerybard is a Basic Augmented Reality Demo (BARD)'
                 'based on scikit-surgery (SNAPPY)',
     long_description=long_description,
     long_description_content_type='text/x-rst',
-    url='https://github.com/SciKit-Surgery/scikit-surgerybard',
-    # Authors: Miguel Xochicale, Thomas Dowrick, Stephen Thompson, Matt Clarkson
+    url='https://github.com/SciKit-Surgery/'
+        'scikit-surgerybard',
     author='Stephen Thompson',
     author_email='s.thompson@ucl.ac.uk',
     license='BSD-3 license',
     classifiers=[
-        'Development Status :: 5 - Production/Stable',
+        'Development Status :: 3 - Alpha',
 
         'Intended Audience :: Developers',
         'Intended Audience :: Healthcare Industry',
         'Intended Audience :: Information Technology',
         'Intended Audience :: Science/Research',
 
 
         'License :: OSI Approved :: BSD License',
 
 
         'Programming Language :: Python',
-        'Programming Language :: Python :: 3.8',
+        'Programming Language :: Python :: 3',
 
         'Topic :: Scientific/Engineering :: Information Analysis',
         'Topic :: Scientific/Engineering :: Medical Science Apps.',
     ],
 
     keywords='medical imaging',
 
@@ -51,20 +51,20 @@
             'data',
         ]
     ),
 
     install_requires=[
         'numpy',
         'glob2',
-        'pyside6>=6.5.1.1',
+        'pyside6>=6.4.2',
         'opencv-contrib-python-headless>=4.2.0.32',
         'scikit-surgerycore>=0.6.10',
         'scikit-surgerycalibration>=0.2.4',
-        'scikit-surgeryutils>=2.0.0',
-        'scikit-surgeryvtk>=2.0.1',
+        'scikit-surgeryutils==2.0rc0',
+        'scikit-surgeryvtk==2.0rc0',
         'scikit-surgeryarucotracker>=1.0.1',
     ],
 
     entry_points={
         'console_scripts': [
             'bardVideoCalibration=sksurgeryutils.ui.sksurgeryvideocalibration_command_line:main',
             'bardVideoCalibrationChecker=sksurgeryutils.ui.sksurgeryvideocalibrationchecker_command_line:main',
```

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/algorithms/bard_config_algorithms.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/bard_config_algorithms.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/algorithms/bard_config_speech.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/bard_config_speech.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/algorithms/decimation.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/decimation.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/algorithms/pointer.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/algorithms/pointer.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/interaction/interaction.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/interaction/interaction.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/interaction/speech_interaction.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/interaction/speech_interaction.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/tracking/bard_tracking.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/tracking/bard_tracking.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/ui/bard_procrustes_app.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/ui/bard_procrustes_app.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/ui/bard_procrustes_command_line.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/ui/bard_procrustes_command_line.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/ui/sksurgerybard_command_app.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/ui/sksurgerybard_command_app.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/ui/sksurgerybard_command_line.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/ui/sksurgerybard_command_line.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/visualisation/bard_visualisation.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/visualisation/bard_visualisation.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/sksurgerybard/widgets/bard_overlay_app.py` & `scikit-surgerybard-1.0rc0/sksurgerybard/widgets/bard_overlay_app.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/algorithms/test_configure_bard.py` & `scikit-surgerybard-1.0rc0/tests/algorithms/test_configure_bard.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/algorithms/test_pointer.py` & `scikit-surgerybard-1.0rc0/tests/algorithms/test_pointer.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/interaction/test_interaction.py` & `scikit-surgerybard-1.0rc0/tests/interaction/test_interaction.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/interaction/test_speech_interation.py` & `scikit-surgerybard-1.0rc0/tests/interaction/test_speech_interation.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/tracking/test_tracking.py` & `scikit-surgerybard-1.0rc0/tests/tracking/test_tracking.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/visualisation/test_visualisation.py` & `scikit-surgerybard-1.0rc0/tests/visualisation/test_visualisation.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/tests/widgets/test_bard_overlay.py` & `scikit-surgerybard-1.0rc0/tests/widgets/test_bard_overlay.py`

 * *Files identical despite different names*

### Comparing `scikit-surgerybard-1.0.0/versioneer.py` & `scikit-surgerybard-1.0rc0/versioneer.py`

 * *Files identical despite different names*


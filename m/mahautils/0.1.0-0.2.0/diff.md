# Comparing `tmp/mahautils-0.1.0.tar.gz` & `tmp/mahautils-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mahautils-0.1.0.tar", last modified: Sat May 27 15:08:06 2023, max compression
+gzip compressed data, was "mahautils-0.2.0.tar", last modified: Wed Jun 28 00:54:17 2023, max compression
```

## Comparing `mahautils-0.1.0.tar` & `mahautils-0.2.0.tar`

### file list

```diff
@@ -1,68 +1,69 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.541580 mahautils-0.1.0/
--rw-r--r--   0 runner    (1001) docker     (123)    34523 2023-05-27 15:06:59.000000 mahautils-0.1.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-05-27 15:06:59.000000 mahautils-0.1.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     6849 2023-05-27 15:08:06.541580 mahautils-0.1.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6474 2023-05-27 15:06:59.000000 mahautils-0.1.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.533580 mahautils-0.1.0/mahautils/
--rw-r--r--   0 runner    (1001) docker     (123)      466 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      667 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/__main__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.537580 mahautils-0.1.0/mahautils/multics/
--rw-r--r--   0 runner    (1001) docker     (123)      605 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10068 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/configfile.py
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     2335 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)    25369 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/fluidprop.py
--rw-r--r--   0 runner    (1001) docker     (123)    29992 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/polygonfile.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.537580 mahautils-0.1.0/mahautils/multics/sim_results_viewer/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29873 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/app.py
--rw-r--r--   0 runner    (1001) docker     (123)     1447 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     1433 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/error_box.py
--rw-r--r--   0 runner    (1001) docker     (123)     3241 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/header.py
--rw-r--r--   0 runner    (1001) docker     (123)     2257 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/info.py
--rw-r--r--   0 runner    (1001) docker     (123)     3647 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/load_files.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.541580 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/
--rw-r--r--   0 runner    (1001) docker     (123)      321 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1148 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/main_panel.py
--rw-r--r--   0 runner    (1001) docker     (123)     7728 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/settings_general.py
--rw-r--r--   0 runner    (1001) docker     (123)     5496 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/settings_x.py
--rw-r--r--   0 runner    (1001) docker     (123)    10617 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/settings_y.py
--rw-r--r--   0 runner    (1001) docker     (123)     3599 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/tab_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/tab_plot_settings.py
--rw-r--r--   0 runner    (1001) docker     (123)     1699 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/utils_generate_table.py
--rw-r--r--   0 runner    (1001) docker     (123)     8981 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/plotting.py
--rw-r--r--   0 runner    (1001) docker     (123)     2414 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/store.py
--rw-r--r--   0 runner    (1001) docker     (123)     7083 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/sim_results_viewer/ui_elements.py
--rw-r--r--   0 runner    (1001) docker     (123)    37498 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/simresults.py
--rw-r--r--   0 runner    (1001) docker     (123)    18111 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/units.py
--rw-r--r--   0 runner    (1001) docker     (123)    43732 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/multics/vtk.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.541580 mahautils-0.1.0/mahautils/shapes/
--rw-r--r--   0 runner    (1001) docker     (123)      510 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6342 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/canvas.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.541580 mahautils-0.1.0/mahautils/shapes/geometry/
--rw-r--r--   0 runner    (1001) docker     (123)      615 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10724 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/circle.py
--rw-r--r--   0 runner    (1001) docker     (123)     1592 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/geometry.py
--rw-r--r--   0 runner    (1001) docker     (123)     3728 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/point.py
--rw-r--r--   0 runner    (1001) docker     (123)     8850 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/point2D.py
--rw-r--r--   0 runner    (1001) docker     (123)     6444 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/polygon.py
--rw-r--r--   0 runner    (1001) docker     (123)     7802 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/shape.py
--rw-r--r--   0 runner    (1001) docker     (123)     8496 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/geometry/shape_open_closed.py
--rw-r--r--   0 runner    (1001) docker     (123)     8406 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/layer.py
--rw-r--r--   0 runner    (1001) docker     (123)     2257 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/shapes/plotting.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.541580 mahautils-0.1.0/mahautils/utils/
--rw-r--r--   0 runner    (1001) docker     (123)      325 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1432 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/utils/arrays.py
--rw-r--r--   0 runner    (1001) docker     (123)     2312 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/utils/capture_printing.py
--rw-r--r--   0 runner    (1001) docker     (123)    12632 2023-05-27 15:06:59.000000 mahautils-0.1.0/mahautils/utils/dictionary.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-27 15:08:06.537580 mahautils-0.1.0/mahautils.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6849 2023-05-27 15:08:06.000000 mahautils-0.1.0/mahautils.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2099 2023-05-27 15:08:06.000000 mahautils-0.1.0/mahautils.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-27 15:08:06.000000 mahautils-0.1.0/mahautils.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       71 2023-05-27 15:08:06.000000 mahautils-0.1.0/mahautils.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      101 2023-05-27 15:08:06.000000 mahautils-0.1.0/mahautils.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-05-27 15:08:06.000000 mahautils-0.1.0/mahautils.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      108 2023-05-27 15:06:59.000000 mahautils-0.1.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      652 2023-05-27 15:06:59.000000 mahautils-0.1.0/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      696 2023-05-27 15:08:06.541580 mahautils-0.1.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.603613 mahautils-0.2.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    34523 2023-06-28 00:52:50.000000 mahautils-0.2.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 00:52:50.000000 mahautils-0.2.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     6849 2023-06-28 00:54:17.603613 mahautils-0.2.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6474 2023-06-28 00:52:50.000000 mahautils-0.2.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.595612 mahautils-0.2.0/mahautils/
+-rw-r--r--   0 runner    (1001) docker     (123)      466 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      667 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/__main__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.599612 mahautils-0.2.0/mahautils/multics/
+-rw-r--r--   0 runner    (1001) docker     (123)      605 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10068 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/configfile.py
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2335 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25369 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/fluidprop.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29992 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/polygonfile.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.599612 mahautils-0.2.0/mahautils/multics/sim_results_viewer/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30289 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/app.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1447 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1433 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/error_box.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3241 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/header.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2257 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/info.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3647 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/load_files.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.603613 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/
+-rw-r--r--   0 runner    (1001) docker     (123)      321 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1148 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/main_panel.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7728 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/settings_general.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5496 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/settings_x.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10617 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/settings_y.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3599 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/tab_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/tab_plot_settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4265 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/utils_generate_table.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8981 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/plotting.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2414 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/store.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7083 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/sim_results_viewer/ui_elements.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44192 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/simresults.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18111 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/units.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43732 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/multics/vtk.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.603613 mahautils-0.2.0/mahautils/shapes/
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6342 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/canvas.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.603613 mahautils-0.2.0/mahautils/shapes/geometry/
+-rw-r--r--   0 runner    (1001) docker     (123)      653 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10724 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/circle.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1592 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/geometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3876 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/point.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8850 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/point2D.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8229 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/point3D.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6444 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/polygon.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7802 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/shape.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8496 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/geometry/shape_open_closed.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8406 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/layer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2257 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/shapes/plotting.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.603613 mahautils-0.2.0/mahautils/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)      325 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1432 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/utils/arrays.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2312 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/utils/capture_printing.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12632 2023-06-28 00:52:50.000000 mahautils-0.2.0/mahautils/utils/dictionary.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:54:17.599612 mahautils-0.2.0/mahautils.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6849 2023-06-28 00:54:17.000000 mahautils-0.2.0/mahautils.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2136 2023-06-28 00:54:17.000000 mahautils-0.2.0/mahautils.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:54:17.000000 mahautils-0.2.0/mahautils.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       71 2023-06-28 00:54:17.000000 mahautils-0.2.0/mahautils.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      101 2023-06-28 00:54:17.000000 mahautils-0.2.0/mahautils.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 00:54:17.000000 mahautils-0.2.0/mahautils.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      108 2023-06-28 00:52:50.000000 mahautils-0.2.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      652 2023-06-28 00:52:50.000000 mahautils-0.2.0/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      696 2023-06-28 00:54:17.607613 mahautils-0.2.0/setup.cfg
```

### Comparing `mahautils-0.1.0/LICENSE` & `mahautils-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/PKG-INFO` & `mahautils-0.2.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mahautils
-Version: 0.1.0
+Version: 0.2.0
 Summary: Python tools for research at the Maha Fluid Power Research Center
 Home-page: https://github.com/nathan-hess/maha-research-utils
 Author: Nathan Hess
 License: AGPL-3.0
 Project-URL: Documentation, https://mahautils.readthedocs.io
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
```

### Comparing `mahautils-0.1.0/README.md` & `mahautils-0.2.0/README.md`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/__main__.py` & `mahautils-0.2.0/mahautils/__main__.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/__init__.py` & `mahautils-0.2.0/mahautils/multics/__init__.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/configfile.py` & `mahautils-0.2.0/mahautils/multics/configfile.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/constants.py` & `mahautils-0.2.0/mahautils/multics/constants.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/exceptions.py` & `mahautils-0.2.0/mahautils/multics/exceptions.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/fluidprop.py` & `mahautils-0.2.0/mahautils/multics/fluidprop.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/polygonfile.py` & `mahautils-0.2.0/mahautils/multics/polygonfile.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/app.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/app.py`

 * *Files 2% similar despite different names*

```diff
@@ -510,15 +510,19 @@
 
         if image_export_scale in (None, ''):
             image_export_scale = 1
         config_general['image_export_scale'] = int(float(image_export_scale))
 
         # Plot configuration settings for x-axis
         if x_variable != config_x['variable']:
-            x_units = None
+            if x_variable in ('', None):
+                x_units = None
+            else:
+                x_units = (_sim_results_files[list(_sim_results_files.keys())[0]]
+                           .get_units(x_variable))
 
         config_x['variable'] = x_variable
         config_x['units'] = x_units
         config_x['axis_title'] = x_title
         config_x['xmin'] = None if x_min in (None, '') else float(x_min)
         config_x['xmax'] = None if x_max in (None, '') else float(x_max)
         config_x['tick_spacing'] = None if x_tick_spacing in (None, '') \
@@ -538,15 +542,19 @@
             y_axis['tick_spacing'] = None if y_tick_spacing in (None, '') \
                                           else float(y_tick_spacing)  # noqa: E127
 
             if len(config_y['axes'][y_axis_idx]['traces']) > 0:
                 trace = config_y['axes'][y_axis_idx]['traces'][trace_idx]
 
                 if trace_variable != trace['variable']:
-                    trace_units = None
+                    if trace_variable in ('', None):
+                        trace_units = None
+                    else:
+                        trace_units = (_sim_results_files[trace_file]
+                                       .get_units(trace_variable))
 
                 trace['name'] = trace_name
                 trace['file'] = trace_file
                 trace['variable'] = trace_variable
                 trace['units'] = trace_units
                 trace['style']['color'] = trace_color
                 trace['style']['width'] = None if trace_width in (None, '') \
```

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/constants.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/constants.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/error_box.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/error_box.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/header.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/header.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/info.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/info.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/load_files.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/load_files.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/main_panel.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/main_panel.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/settings_general.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/settings_general.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/settings_x.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/settings_x.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/settings_y.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/settings_y.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/tab_data.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/tab_data.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/panel/tab_plot_settings.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/panel/tab_plot_settings.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/plotting.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/plotting.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/store.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/store.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/sim_results_viewer/ui_elements.py` & `mahautils-0.2.0/mahautils/multics/sim_results_viewer/ui_elements.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/simresults.py` & `mahautils-0.2.0/mahautils/multics/simresults.py`

 * *Files 11% similar despite different names*

```diff
@@ -165,21 +165,31 @@
             used to convert units of quantities stored in the simulation
             results file (default is ``None``).  If set to ``None``, the
             :py:class:`MahaMulticsUnitConverter` unit converter will be used
             to perform unit conversions
         """
         super().__init__(path=path, unit_converter=unit_converter)
 
+        self.__printdict_begin_regex = r'^\s*printDict\s*{\s*'
+        self.__printdict_end_regex = r'^\s*}\s*$'
+
+        self.__maha_multics_version_identifier = 'Multics Version'
+        self.__maha_multics_commit_identifier = 'Multics Git Commit Hash'
+        self.__sim_version_identifier = 'Main Sketch Version'
+
         # Initialize variables
         self._compile_options: Dict[str, str] = {}
         self._data: Dictionary[str, _SimResultsEntry] = Dictionary(
             custom_except_class=SimResultsKeyError,
             custom_except_msg='Variable "%s" not found in simulation results file'
         )
+        self._maha_multics_commit: Union[str, None] = None
+        self._maha_multics_version: Union[str, None] = None
         self._num_time_steps: int = 0
+        self._sim_version: Union[str, None] = None
         self._title: Union[str, None] = None
         self.trailing_newline = True
 
         # If path was provided, read file
         if path is not None:
             self.read(path, parse=True)
 
@@ -210,28 +220,70 @@
 
         Note that this dictionary is returned **by reference**, so modifying
         the returned value will modify the object attribute.
         """
         return self._compile_options
 
     @property
+    def maha_multics_commit(self) -> Union[str, None]:
+        """The Git commit hash of the Maha Multics software with which the simulation
+        was compiled"""
+        return self._maha_multics_commit
+
+    @maha_multics_commit.setter
+    def maha_multics_commit(self, maha_multics_commit: Union[str, None]) -> None:
+        if not isinstance(maha_multics_commit, (str, type(None))):
+            raise TypeError('Argument "maha_multics_commit" must be of type '
+                            '"str" or "None"')
+
+        self._maha_multics_commit = maha_multics_commit
+
+    @property
+    def maha_multics_version(self) -> Union[str, None]:
+        """The version of the Maha Multics software with which the simulation
+        was compiled"""
+        return self._maha_multics_version
+
+    @maha_multics_version.setter
+    def maha_multics_version(self, maha_multics_version: Union[str, None]) -> None:
+        if not isinstance(maha_multics_version, (str, type(None))):
+            raise TypeError('Argument "maha_multics_version" must be of type '
+                            '"str" or "None"')
+
+        self._maha_multics_version = maha_multics_version
+
+    @property
     def num_time_steps(self) -> int:
         """The number of time steps in the data array of the simulation
         results file"""
         return self._num_time_steps
 
     @property
+    def sim_version(self) -> Union[str, None]:
+        """The simulation version of the ``main.cpp`` file which was used to
+        generate the data in the simulation results file"""
+        return self._sim_version
+
+    @sim_version.setter
+    def sim_version(self, sim_version: Union[str, None]) -> None:
+        if not isinstance(sim_version, (str, type(None))):
+            raise TypeError('Argument "sim_version" must be of type '
+                            '"str" or "None"')
+
+        self._sim_version = sim_version
+
+    @property
     def title(self) -> Union[str, None]:
         """A title describing the contents of the simulation results file"""
         return self._title
 
     @title.setter
     def title(self, title: Union[str, None]) -> None:
         if not isinstance(title, (str, type(None))):
-            raise TypeError('Argument "title" must be of type "str"')
+            raise TypeError('Argument "title" must be of type "str" or "None"')
 
         self._title = title
 
     @property
     def variables(self) -> Tuple[str, ...]:
         """A tuple containing all variable names listed in the simulation
         results file
@@ -265,14 +317,103 @@
                         )
 
                 if len(var_str) > 1:
                     representation += '\n'.join(var_str) + '\n'
 
         return representation.strip('\n')
 
+    def __parse_metadata_comment(self, identifier: str) -> Union[str, None]:
+        for line in self.contents:
+            if re.match(r'^\s*#\s*' + re.escape(identifier) + r'\:', line):
+                return line.split(f'{identifier}:', maxsplit=1)[1].strip()
+
+        return None
+
+    def _remove_vars_with_asterisk(self) -> None:
+        # Extract names of all simulation results variables whose data are
+        # included in the file
+        data_vars: List[str] = []
+        i = 0
+        while i < len(self.contents):
+            if (line := self.contents[i]).startswith('$'):
+                data_vars = [var.split(':')[0] for var in line.split('$')[1:]]
+                break
+
+            i += 1
+
+        i = 0
+        while i < len(self.contents):
+            line = self.contents[i]
+
+            if (
+                groups := re.search(self.__printdict_begin_regex + r'(.*)', line)
+            ) is not None:
+                if (line := groups.groups()[-1]) != '':
+                    self.contents[i] = 'printDict{'
+                    self.contents.insert(i + 1, '    ' + line)
+
+                i += 1
+                line = self.contents[i]
+
+                while not re.match(self.__printdict_end_regex, line):
+                    # Identify problematic keys (with asterisks)
+                    line_groups = re.search(
+                        r'^\s*([@?])\s*([\w\d\._\*\(\,\)]+)\s+\[([^\s]+)\]\s*$',
+                        line)
+
+                    # If key with asterisk was found, remove it and replace
+                    # with simulation results variables
+                    if line_groups is not None:
+                        asterisk_key = line_groups.group(2)
+
+                        if '*' in asterisk_key:
+                            if len(data_vars) == 0:
+                                raise SimResultsDataNotFoundError(
+                                    'Simulation results files with asterisks (*) '
+                                    'in variable names can only be read if the '
+                                    'line beginning with "$" providing detailed '
+                                    'variable names and descriptions is present')
+
+                            # Find any matching simulation results variables
+                            asterisk_seqs = (
+                                re.findall(r'\*\(\d+\,\d+\)', asterisk_key)
+                                + ['**']
+                            )
+
+                            key_regex = asterisk_key
+                            for seq in asterisk_seqs:
+                                key_regex = key_regex.replace(seq, '*')
+
+                            key_regex = re.escape(key_regex).replace(r'\*', r'\d+')
+
+                            matching_keys = []
+                            for var in data_vars:
+                                if re.match(key_regex, var):
+                                    matching_keys.append(var)
+
+                            matching_keys.reverse()
+
+                            # Add matching simulation results variables to file
+                            del self.contents[i]
+
+                            for var in matching_keys:
+                                self.contents.insert(
+                                    i, line.replace(asterisk_key, var))
+
+                            i += len(matching_keys) - 1
+
+                    i += 1
+                    line = self.contents[i]
+
+                # Coverage.py is unable to detect 'break' statements
+                # https://github.com/nedbat/coveragepy/issues/772
+                break  # pragma: no cover
+
+            i += 1
+
     def append(self, key: str, required: bool, units: str,
                data: Optional[
                    Union[np.ndarray, List[float], Tuple[float, ...]]] = None,
                description: Optional[str] = None,
                group: Optional[str] = None,
                ) -> None:
         """Adds a variable to the simulation results file
@@ -487,20 +628,21 @@
         """
         # Verify that file contents have been read
         super().parse()
 
         original_contents = copy.deepcopy(self.contents)
 
         # Extract title
-        for line in self.contents:
-            if re.match(r'^\s*#\s*Title', line):
-                self.title = line.split('Title:', maxsplit=1)[1].strip()
-                break
-
-            self.title = None
+        self.title = self.__parse_metadata_comment('Title')
+        self.maha_multics_version \
+            = self.__parse_metadata_comment(self.__maha_multics_version_identifier)
+        self.maha_multics_commit \
+            = self.__parse_metadata_comment(self.__maha_multics_commit_identifier)
+        self.sim_version \
+            = self.__parse_metadata_comment(self.__sim_version_identifier)
 
         # Extract options with which Maha Multics software was compiled
         for line in self.contents:
             if line.strip().startswith('#_OPTIONs:'):
                 options_list = line.split('#_OPTIONs:', maxsplit=1)[1].split(',')
 
                 for opt in options_list:
@@ -513,19 +655,21 @@
         self.clean_contents(
             remove_comments    = False,
             strip              = True,
             concat_lines       = False,
             remove_blank_lines = True
         )
 
+        self._remove_vars_with_asterisk()
+
         # Extract list of variables in "printDict"
         sim_results_vars, comments, _, num_sec = self.extract_section_by_keyword(
             section_label      = 'printDict',
-            begin_regex        = r'^\s*printDict\s*{\s*',
-            end_regex          = r'^\s*}\s*$',
+            begin_regex        = self.__printdict_begin_regex,
+            end_regex          = self.__printdict_end_regex,
             section_line_regex = r'^\s*([@?])\s*([\w\d\._]+)\s+\[([^\s]+)\]\s*$',
             max_sections       = 1,
         )
 
         if num_sec == 0:
             raise InvalidSimResultsFormatError(
                 'Unable to find "printDict" section in simulation results file')
@@ -978,14 +1122,27 @@
                 if group_vars_added:  # pragma: no cover
                     self.contents.extend(group_lines + [''])
         else:
             self.contents.append('')
 
         self.contents[-1] = '}'
 
+        # Write additional metadata
+        if self.maha_multics_version is not None:
+            self.contents.append(f'# {self.__maha_multics_version_identifier}: '
+                                 f'{self.maha_multics_version}')
+
+        if self.maha_multics_commit is not None:
+            self.contents.append(f'# {self.__maha_multics_commit_identifier}: '
+                                 f'{self.maha_multics_commit}')
+
+        if self.sim_version is not None:
+            self.contents.append(f'# {self.__sim_version_identifier}: '
+                                 f'{self.sim_version}')
+
         # Write simulation data, if available
         if add_sim_data:
             # Simulation results variables and descriptions
             data_vars = ''
             data_array = []
             for var in self.variables:
                 data = self._data[var].data
```

### Comparing `mahautils-0.1.0/mahautils/multics/units.py` & `mahautils-0.2.0/mahautils/multics/units.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/multics/vtk.py` & `mahautils-0.2.0/mahautils/multics/vtk.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/canvas.py` & `mahautils-0.2.0/mahautils/shapes/canvas.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/__init__.py` & `mahautils-0.2.0/mahautils/shapes/geometry/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -6,10 +6,11 @@
 flexible as possible to allow greater freedom in building complex geometry.
 """
 
 from .circle import Circle
 from .geometry import Geometry
 from .point import Point
 from .point2D import CartesianPoint2D
+from .point3D import CartesianPoint3D
 from .polygon import Polygon
 from .shape import Shape2D
 from .shape_open_closed import ClosedShape2D, OpenShape2D
```

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/circle.py` & `mahautils-0.2.0/mahautils/shapes/geometry/circle.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/geometry.py` & `mahautils-0.2.0/mahautils/shapes/geometry/geometry.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/point.py` & `mahautils-0.2.0/mahautils/shapes/geometry/point.py`

 * *Files 5% similar despite different names*

```diff
@@ -13,14 +13,17 @@
 import numpy as np
 
 from .geometry import Geometry
 
 # Type alias for a list or tuple containing two floating-point numbers
 Array_Float2 = Union[List[float], Tuple[float, float], np.ndarray]
 
+# Type alias for a list or tuple containing three floating-point numbers
+Array_Float3 = Union[List[float], Tuple[float, float, float], np.ndarray]
+
 
 class Point(Geometry):
     """Base class representing an arbitrary point in a space of an arbitrary
     number of dimensions
 
     This is a generic class that represents an arbitrary point in any
     coordinate system.  In general, this class should be inherited by
```

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/point2D.py` & `mahautils-0.2.0/mahautils/shapes/geometry/point2D.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/polygon.py` & `mahautils-0.2.0/mahautils/shapes/geometry/polygon.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/shape.py` & `mahautils-0.2.0/mahautils/shapes/geometry/shape.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/geometry/shape_open_closed.py` & `mahautils-0.2.0/mahautils/shapes/geometry/shape_open_closed.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/layer.py` & `mahautils-0.2.0/mahautils/shapes/layer.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/shapes/plotting.py` & `mahautils-0.2.0/mahautils/shapes/plotting.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/utils/arrays.py` & `mahautils-0.2.0/mahautils/utils/arrays.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/utils/capture_printing.py` & `mahautils-0.2.0/mahautils/utils/capture_printing.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils/utils/dictionary.py` & `mahautils-0.2.0/mahautils/utils/dictionary.py`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/mahautils.egg-info/PKG-INFO` & `mahautils-0.2.0/mahautils.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mahautils
-Version: 0.1.0
+Version: 0.2.0
 Summary: Python tools for research at the Maha Fluid Power Research Center
 Home-page: https://github.com/nathan-hess/maha-research-utils
 Author: Nathan Hess
 License: AGPL-3.0
 Project-URL: Documentation, https://mahautils.readthedocs.io
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
```

### Comparing `mahautils-0.1.0/mahautils.egg-info/SOURCES.txt` & `mahautils-0.2.0/mahautils.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -45,14 +45,15 @@
 mahautils/shapes/layer.py
 mahautils/shapes/plotting.py
 mahautils/shapes/geometry/__init__.py
 mahautils/shapes/geometry/circle.py
 mahautils/shapes/geometry/geometry.py
 mahautils/shapes/geometry/point.py
 mahautils/shapes/geometry/point2D.py
+mahautils/shapes/geometry/point3D.py
 mahautils/shapes/geometry/polygon.py
 mahautils/shapes/geometry/shape.py
 mahautils/shapes/geometry/shape_open_closed.py
 mahautils/utils/__init__.py
 mahautils/utils/arrays.py
 mahautils/utils/capture_printing.py
 mahautils/utils/dictionary.py
```

### Comparing `mahautils-0.1.0/requirements.txt` & `mahautils-0.2.0/requirements.txt`

 * *Files identical despite different names*

### Comparing `mahautils-0.1.0/setup.cfg` & `mahautils-0.2.0/setup.cfg`

 * *Files identical despite different names*


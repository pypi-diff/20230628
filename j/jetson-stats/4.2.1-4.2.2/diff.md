# Comparing `tmp/jetson-stats-4.2.1.tar.gz` & `tmp/jetson-stats-4.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jetson-stats-4.2.1.tar", last modified: Thu Mar 30 14:15:30 2023, max compression
+gzip compressed data, was "jetson-stats-4.2.2.tar", last modified: Wed Jun 28 14:26:58 2023, max compression
```

## Comparing `jetson-stats-4.2.1.tar` & `jetson-stats-4.2.2.tar`

### file list

```diff
@@ -1,72 +1,72 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.157927 jetson-stats-4.2.1/
--rw-r--r--   0 root         (0) root         (0)     5210 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/CODE_OF_CONDUCT.md
--rw-r--r--   0 root         (0) root         (0)    34522 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/LICENSE
--rw-r--r--   0 root         (0) root         (0)     1195 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     7275 2023-03-30 14:15:30.157927 jetson-stats-4.2.1/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     5008 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.145928 jetson-stats-4.2.1/jetson_stats.egg-info/
--rw-r--r--   0 root         (0) root         (0)     7275 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1391 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      163 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)       14 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        5 2023-03-30 14:15:30.000000 jetson-stats-4.2.1/jetson_stats.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.145928 jetson-stats-4.2.1/jtop/
--rw-r--r--   0 root         (0) root         (0)     1370 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7389 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/__main__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.153927 jetson-stats-4.2.1/jtop/core/
--rw-r--r--   0 root         (0) root         (0)      857 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4875 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/command.py
--rw-r--r--   0 root         (0) root         (0)     8186 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/common.py
--rw-r--r--   0 root         (0) root         (0)     3659 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/config.py
--rw-r--r--   0 root         (0) root         (0)    10295 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/cpu.py
--rw-r--r--   0 root         (0) root         (0)     5195 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/engine.py
--rw-r--r--   0 root         (0) root         (0)     1273 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/exceptions.py
--rw-r--r--   0 root         (0) root         (0)    26135 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/fan.py
--rw-r--r--   0 root         (0) root         (0)    12659 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/gpu.py
--rw-r--r--   0 root         (0) root         (0)     2702 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/hardware.py
--rw-r--r--   0 root         (0) root         (0)    21131 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/jetson_clocks.py
--rw-r--r--   0 root         (0) root         (0)     4767 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/jetson_libraries.py
--rw-r--r--   0 root         (0) root         (0)    15842 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/jetson_variables.py
--rw-r--r--   0 root         (0) root         (0)    17179 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/memory.py
--rw-r--r--   0 root         (0) root         (0)    19624 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/nvpmodel.py
--rw-r--r--   0 root         (0) root         (0)    13576 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/power.py
--rw-r--r--   0 root         (0) root         (0)     5405 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/processes.py
--rw-r--r--   0 root         (0) root         (0)     7997 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/tegra_parse.py
--rw-r--r--   0 root         (0) root         (0)     4476 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/tegrastats.py
--rw-r--r--   0 root         (0) root         (0)     6413 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/temperature.py
--rw-r--r--   0 root         (0) root         (0)     3173 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/core/timer_reader.py
--rw-r--r--   0 root         (0) root         (0)     6499 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/github.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.153927 jetson-stats-4.2.1/jtop/gui/
--rw-r--r--   0 root         (0) root         (0)     1111 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12426 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/jtopgui.py
--rw-r--r--   0 root         (0) root         (0)     9679 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/jtopguiconfig.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.157927 jetson-stats-4.2.1/jtop/gui/lib/
--rw-r--r--   0 root         (0) root         (0)      850 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/__init__.py
--rw-r--r--   0 root         (0) root         (0)    11018 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/chart.py
--rw-r--r--   0 root         (0) root         (0)     3636 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/colors.py
--rw-r--r--   0 root         (0) root         (0)     5806 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/common.py
--rw-r--r--   0 root         (0) root         (0)     6148 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/linear_gauge.py
--rw-r--r--   0 root         (0) root         (0)     3485 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/process_table.py
--rw-r--r--   0 root         (0) root         (0)     6182 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/lib/smallbutton.py
--rw-r--r--   0 root         (0) root         (0)     8976 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pall.py
--rw-r--r--   0 root         (0) root         (0)    19822 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pcontrol.py
--rw-r--r--   0 root         (0) root         (0)     5662 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pcpu.py
--rw-r--r--   0 root         (0) root         (0)     5998 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pengine.py
--rw-r--r--   0 root         (0) root         (0)    10059 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pgpu.py
--rw-r--r--   0 root         (0) root         (0)     5946 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pinfo.py
--rw-r--r--   0 root         (0) root         (0)    17935 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/gui/pmem.py
--rw-r--r--   0 root         (0) root         (0)     9744 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/jetson_config.py
--rw-r--r--   0 root         (0) root         (0)     6001 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/jetson_release.py
--rw-r--r--   0 root         (0) root         (0)     3547 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/jetson_swap.py
--rw-r--r--   0 root         (0) root         (0)    58504 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/jtop.py
--rw-r--r--   0 root         (0) root         (0)    25274 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/service.py
--rw-r--r--   0 root         (0) root         (0)     1470 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/jtop/terminal_colors.py
--rw-r--r--   0 root         (0) root         (0)       13 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/requirements.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.157927 jetson-stats-4.2.1/scripts/
--rw-r--r--   0 root         (0) root         (0)     1563 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/scripts/jtop_env.sh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-30 14:15:30.157927 jetson-stats-4.2.1/services/
--rw-r--r--   0 root         (0) root         (0)     1070 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/services/jtop.service
--rw-r--r--   0 root         (0) root         (0)       89 2023-03-30 14:15:30.157927 jetson-stats-4.2.1/setup.cfg
--rw-r--r--   0 root         (0) root         (0)    10744 2023-03-30 14:15:22.000000 jetson-stats-4.2.1/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.667253 jetson-stats-4.2.2/
+-rw-r--r--   0 root         (0) root         (0)     5210 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/CODE_OF_CONDUCT.md
+-rw-r--r--   0 root         (0) root         (0)    34522 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/LICENSE
+-rw-r--r--   0 root         (0) root         (0)     1195 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     7240 2023-06-28 14:26:58.667253 jetson-stats-4.2.2/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     5013 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.659253 jetson-stats-4.2.2/jetson_stats.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     7240 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1391 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      163 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)       14 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        5 2023-06-28 14:26:58.000000 jetson-stats-4.2.2/jetson_stats.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.663253 jetson-stats-4.2.2/jtop/
+-rw-r--r--   0 root         (0) root         (0)     1370 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7389 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/__main__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.663253 jetson-stats-4.2.2/jtop/core/
+-rw-r--r--   0 root         (0) root         (0)      857 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4875 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/command.py
+-rw-r--r--   0 root         (0) root         (0)     8186 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/common.py
+-rw-r--r--   0 root         (0) root         (0)     3659 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/config.py
+-rw-r--r--   0 root         (0) root         (0)    10295 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/cpu.py
+-rw-r--r--   0 root         (0) root         (0)     5195 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/engine.py
+-rw-r--r--   0 root         (0) root         (0)     1273 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)    26135 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/fan.py
+-rw-r--r--   0 root         (0) root         (0)    12659 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/gpu.py
+-rw-r--r--   0 root         (0) root         (0)     2702 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/hardware.py
+-rw-r--r--   0 root         (0) root         (0)    21131 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/jetson_clocks.py
+-rw-r--r--   0 root         (0) root         (0)     4767 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/jetson_libraries.py
+-rw-r--r--   0 root         (0) root         (0)    15865 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/jetson_variables.py
+-rw-r--r--   0 root         (0) root         (0)    17179 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/memory.py
+-rw-r--r--   0 root         (0) root         (0)    19624 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/nvpmodel.py
+-rw-r--r--   0 root         (0) root         (0)    13576 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/power.py
+-rw-r--r--   0 root         (0) root         (0)     5405 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/processes.py
+-rw-r--r--   0 root         (0) root         (0)     7997 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/tegra_parse.py
+-rw-r--r--   0 root         (0) root         (0)     4476 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/tegrastats.py
+-rw-r--r--   0 root         (0) root         (0)     6413 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/temperature.py
+-rw-r--r--   0 root         (0) root         (0)     3173 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/core/timer_reader.py
+-rw-r--r--   0 root         (0) root         (0)     6499 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/github.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.663253 jetson-stats-4.2.2/jtop/gui/
+-rw-r--r--   0 root         (0) root         (0)     1111 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12426 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/jtopgui.py
+-rw-r--r--   0 root         (0) root         (0)     9679 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/jtopguiconfig.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.667253 jetson-stats-4.2.2/jtop/gui/lib/
+-rw-r--r--   0 root         (0) root         (0)      850 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    11124 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/chart.py
+-rw-r--r--   0 root         (0) root         (0)     3636 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/colors.py
+-rw-r--r--   0 root         (0) root         (0)     5806 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/common.py
+-rw-r--r--   0 root         (0) root         (0)     6148 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/linear_gauge.py
+-rw-r--r--   0 root         (0) root         (0)     3485 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/process_table.py
+-rw-r--r--   0 root         (0) root         (0)     6182 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/lib/smallbutton.py
+-rw-r--r--   0 root         (0) root         (0)     8976 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pall.py
+-rw-r--r--   0 root         (0) root         (0)    19822 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pcontrol.py
+-rw-r--r--   0 root         (0) root         (0)     5662 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pcpu.py
+-rw-r--r--   0 root         (0) root         (0)     6481 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pengine.py
+-rw-r--r--   0 root         (0) root         (0)    10059 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pgpu.py
+-rw-r--r--   0 root         (0) root         (0)     5946 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pinfo.py
+-rw-r--r--   0 root         (0) root         (0)    17935 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/gui/pmem.py
+-rw-r--r--   0 root         (0) root         (0)     9744 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/jetson_config.py
+-rw-r--r--   0 root         (0) root         (0)     6001 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/jetson_release.py
+-rw-r--r--   0 root         (0) root         (0)     3547 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/jetson_swap.py
+-rw-r--r--   0 root         (0) root         (0)    58684 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/jtop.py
+-rw-r--r--   0 root         (0) root         (0)    25274 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/service.py
+-rw-r--r--   0 root         (0) root         (0)     1470 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/jtop/terminal_colors.py
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/requirements.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.667253 jetson-stats-4.2.2/scripts/
+-rw-r--r--   0 root         (0) root         (0)     1563 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/scripts/jtop_env.sh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:26:58.667253 jetson-stats-4.2.2/services/
+-rw-r--r--   0 root         (0) root         (0)     1070 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/services/jtop.service
+-rw-r--r--   0 root         (0) root         (0)       89 2023-06-28 14:26:58.667253 jetson-stats-4.2.2/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)    10704 2023-06-28 14:26:50.000000 jetson-stats-4.2.2/setup.py
```

### Comparing `jetson-stats-4.2.1/CODE_OF_CONDUCT.md` & `jetson-stats-4.2.2/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/LICENSE` & `jetson-stats-4.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/MANIFEST.in` & `jetson-stats-4.2.2/MANIFEST.in`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/PKG-INFO` & `jetson-stats-4.2.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jetson-stats
-Version: 4.2.1
+Version: 4.2.2
 Summary: Interactive system-monitor and process viewer for all NVIDIA Jetson [Orin, Xavier, Nano, TX] series
 Home-page: https://rnext.it/jetson_stats
 Author: Raffaello Bonghi
 Author-email: raffaello@rnext.it
 License: AGPL-3.0
 Project-URL: Documentation, https://rnext.it/jetson_stats
 Project-URL: Funding, https://github.com/sponsors/rbonghi
@@ -37,15 +37,15 @@
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Operating System :: POSIX :: Linux
-Requires-Python: >=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, <4
+Requires-Python: >=2.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 <h1 align="center">
 
 <b>jetson-stats</b>
 
@@ -104,15 +104,15 @@
 
 Start jtop it's pretty simple just write `jtop`!
 
 ```console
 jtop
 ```
 
-A simple interface will appear on your terminal, more capabilities are documented at [_jtop_](https://rnext.it/jetson_stats/jtop.html) page.
+A simple interface will appear on your terminal, more capabilities are documented at [_jtop_](https://rnext.it/jetson_stats/jtop/jtop.html) page.
 
 <div align="center">
 
 [![jtop](https://github.com/rbonghi/jetson_stats/raw/master/docs/images/jtop.gif)](https://github.com/rbonghi/jetson_stats)
 
 </div>
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: jetson-stats Version: 4.2.1 Summary: Interactive
+Metadata-Version: 2.1 Name: jetson-stats Version: 4.2.2 Summary: Interactive
 system-monitor and process viewer for all NVIDIA Jetson [Orin, Xavier, Nano,
 TX] series Home-page: https://rnext.it/jetson_stats Author: Raffaello Bonghi
 Author-email: raffaello@rnext.it License: AGPL-3.0 Project-URL: Documentation,
 https://rnext.it/jetson_stats Project-URL: Funding, https://github.com/
 sponsors/rbonghi Project-URL: Say Thanks!, https://discord.gg/BFbuJNhYzS
 Project-URL: Source, https://github.com/rbonghi/jetson_stats Project-URL:
 Tracker, https://github.com/rbonghi/jetson_stats/issues Project-URL: Examples,
@@ -22,16 +22,16 @@
 License v3 or later (AGPLv3+) Classifier: Programming Language :: Unix Shell
 Classifier: Programming Language :: Python :: 2 Classifier: Programming
 Language :: Python :: 2.7 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10 Classifier: Programming
 Language :: Python :: 3.11 Classifier: Operating System :: POSIX :: Linux
-Requires-Python: >=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, <4 Description-
-Content-Type: text/markdown License-File: LICENSE
+Requires-Python: >=2.7 Description-Content-Type: text/markdown License-File:
+LICENSE
  ****** jetson-stats [![jetson-stats](https://github.com/rbonghi/jetson_stats/
    raw/master/docs/images/jtop.png)](https://rnext.it/jetson_stats/) ******
   [PyPI_-_Downloads] [PyPI_version] [PyPI_-_Python_Version] [PyPI_-_Format]
   [GitHub] [jetson-stats] [Docker_Image_Size_(tag)] [Docker_Pulls] [CI_&_CD]
                                    [CodeQL]
               [Twitter_Follow] [robo.panther] [Join_our_Discord]
 **jetson-stats** is a package for **monitoring** and **control** your [NVIDIA
@@ -45,15 +45,15 @@
 Works with all NVIDIA Jetpack ## Install jetson-stats can be installed with
 [pip](https://pip.pypa.io), but need **superuser**: ```console sudo pip3
 install -U jetson-stats ``` _Don't forget to **logout/login** or **reboot**
 your board_
                            **ð That's it! ð**
 ## Run Start jtop it's pretty simple just write `jtop`! ```console jtop ``` A
 simple interface will appear on your terminal, more capabilities are documented
-at [_jtop_](https://rnext.it/jetson_stats/jtop.html) page.
+at [_jtop_](https://rnext.it/jetson_stats/jtop/jtop.html) page.
    [![jtop](https://github.com/rbonghi/jetson_stats/raw/master/docs/images/
               jtop.gif)](https://github.com/rbonghi/jetson_stats)
 ## Library You can use jtop such a python library to integrate in your software
 ```python from jtop import jtop with jtop() as jetson: # jetson.ok() will
 provide the proper update frequency while jetson.ok(): # Read tegra stats print
 (jetson.stats) ``` You can also use jtop with your _virualenv_! More
 information available at [_advanced usage_](https://rnext.it/jetson_stats/
```

### Comparing `jetson-stats-4.2.1/README.md` & `jetson-stats-4.2.2/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -57,15 +57,15 @@
 
 Start jtop it's pretty simple just write `jtop`!
 
 ```console
 jtop
 ```
 
-A simple interface will appear on your terminal, more capabilities are documented at [_jtop_](https://rnext.it/jetson_stats/jtop.html) page.
+A simple interface will appear on your terminal, more capabilities are documented at [_jtop_](https://rnext.it/jetson_stats/jtop/jtop.html) page.
 
 <div align="center">
 
 [![jtop](https://github.com/rbonghi/jetson_stats/raw/master/docs/images/jtop.gif)](https://github.com/rbonghi/jetson_stats)
 
 </div>
```

#### html2text {}

```diff
@@ -15,15 +15,15 @@
 Works with all NVIDIA Jetpack ## Install jetson-stats can be installed with
 [pip](https://pip.pypa.io), but need **superuser**: ```console sudo pip3
 install -U jetson-stats ``` _Don't forget to **logout/login** or **reboot**
 your board_
                            **ð That's it! ð**
 ## Run Start jtop it's pretty simple just write `jtop`! ```console jtop ``` A
 simple interface will appear on your terminal, more capabilities are documented
-at [_jtop_](https://rnext.it/jetson_stats/jtop.html) page.
+at [_jtop_](https://rnext.it/jetson_stats/jtop/jtop.html) page.
    [![jtop](https://github.com/rbonghi/jetson_stats/raw/master/docs/images/
               jtop.gif)](https://github.com/rbonghi/jetson_stats)
 ## Library You can use jtop such a python library to integrate in your software
 ```python from jtop import jtop with jtop() as jetson: # jetson.ok() will
 provide the proper update frequency while jetson.ok(): # Read tegra stats print
 (jetson.stats) ``` You can also use jtop with your _virualenv_! More
 information available at [_advanced usage_](https://rnext.it/jetson_stats/
```

### Comparing `jetson-stats-4.2.1/jetson_stats.egg-info/PKG-INFO` & `jetson-stats-4.2.2/jetson_stats.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jetson-stats
-Version: 4.2.1
+Version: 4.2.2
 Summary: Interactive system-monitor and process viewer for all NVIDIA Jetson [Orin, Xavier, Nano, TX] series
 Home-page: https://rnext.it/jetson_stats
 Author: Raffaello Bonghi
 Author-email: raffaello@rnext.it
 License: AGPL-3.0
 Project-URL: Documentation, https://rnext.it/jetson_stats
 Project-URL: Funding, https://github.com/sponsors/rbonghi
@@ -37,15 +37,15 @@
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Operating System :: POSIX :: Linux
-Requires-Python: >=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, <4
+Requires-Python: >=2.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 <h1 align="center">
 
 <b>jetson-stats</b>
 
@@ -104,15 +104,15 @@
 
 Start jtop it's pretty simple just write `jtop`!
 
 ```console
 jtop
 ```
 
-A simple interface will appear on your terminal, more capabilities are documented at [_jtop_](https://rnext.it/jetson_stats/jtop.html) page.
+A simple interface will appear on your terminal, more capabilities are documented at [_jtop_](https://rnext.it/jetson_stats/jtop/jtop.html) page.
 
 <div align="center">
 
 [![jtop](https://github.com/rbonghi/jetson_stats/raw/master/docs/images/jtop.gif)](https://github.com/rbonghi/jetson_stats)
 
 </div>
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: jetson-stats Version: 4.2.1 Summary: Interactive
+Metadata-Version: 2.1 Name: jetson-stats Version: 4.2.2 Summary: Interactive
 system-monitor and process viewer for all NVIDIA Jetson [Orin, Xavier, Nano,
 TX] series Home-page: https://rnext.it/jetson_stats Author: Raffaello Bonghi
 Author-email: raffaello@rnext.it License: AGPL-3.0 Project-URL: Documentation,
 https://rnext.it/jetson_stats Project-URL: Funding, https://github.com/
 sponsors/rbonghi Project-URL: Say Thanks!, https://discord.gg/BFbuJNhYzS
 Project-URL: Source, https://github.com/rbonghi/jetson_stats Project-URL:
 Tracker, https://github.com/rbonghi/jetson_stats/issues Project-URL: Examples,
@@ -22,16 +22,16 @@
 License v3 or later (AGPLv3+) Classifier: Programming Language :: Unix Shell
 Classifier: Programming Language :: Python :: 2 Classifier: Programming
 Language :: Python :: 2.7 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10 Classifier: Programming
 Language :: Python :: 3.11 Classifier: Operating System :: POSIX :: Linux
-Requires-Python: >=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, <4 Description-
-Content-Type: text/markdown License-File: LICENSE
+Requires-Python: >=2.7 Description-Content-Type: text/markdown License-File:
+LICENSE
  ****** jetson-stats [![jetson-stats](https://github.com/rbonghi/jetson_stats/
    raw/master/docs/images/jtop.png)](https://rnext.it/jetson_stats/) ******
   [PyPI_-_Downloads] [PyPI_version] [PyPI_-_Python_Version] [PyPI_-_Format]
   [GitHub] [jetson-stats] [Docker_Image_Size_(tag)] [Docker_Pulls] [CI_&_CD]
                                    [CodeQL]
               [Twitter_Follow] [robo.panther] [Join_our_Discord]
 **jetson-stats** is a package for **monitoring** and **control** your [NVIDIA
@@ -45,15 +45,15 @@
 Works with all NVIDIA Jetpack ## Install jetson-stats can be installed with
 [pip](https://pip.pypa.io), but need **superuser**: ```console sudo pip3
 install -U jetson-stats ``` _Don't forget to **logout/login** or **reboot**
 your board_
                            **ð That's it! ð**
 ## Run Start jtop it's pretty simple just write `jtop`! ```console jtop ``` A
 simple interface will appear on your terminal, more capabilities are documented
-at [_jtop_](https://rnext.it/jetson_stats/jtop.html) page.
+at [_jtop_](https://rnext.it/jetson_stats/jtop/jtop.html) page.
    [![jtop](https://github.com/rbonghi/jetson_stats/raw/master/docs/images/
               jtop.gif)](https://github.com/rbonghi/jetson_stats)
 ## Library You can use jtop such a python library to integrate in your software
 ```python from jtop import jtop with jtop() as jetson: # jetson.ok() will
 provide the proper update frequency while jetson.ok(): # Read tegra stats print
 (jetson.stats) ``` You can also use jtop with your _virualenv_! More
 information available at [_advanced usage_](https://rnext.it/jetson_stats/
```

### Comparing `jetson-stats-4.2.1/jetson_stats.egg-info/SOURCES.txt` & `jetson-stats-4.2.2/jetson_stats.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/__init__.py` & `jetson-stats-4.2.2/jtop/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -27,9 +27,9 @@
 
 __author__ = "Raffaello Bonghi"
 __email__ = "raffaello@rnext.it"
 __cr__ = "(c) 2023, RB"
 __copyright__ = "(c) 2023, Raffaello Bonghi"
 # Version package
 # https://packaging.python.org/guides/distributing-packages-using-setuptools/#choosing-a-versioning-scheme
-__version__ = "4.2.1"
+__version__ = "4.2.2"
 # EOF
```

### Comparing `jetson-stats-4.2.1/jtop/__main__.py` & `jetson-stats-4.2.2/jtop/__main__.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/__init__.py` & `jetson-stats-4.2.2/jtop/core/__init__.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/command.py` & `jetson-stats-4.2.2/jtop/core/command.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/common.py` & `jetson-stats-4.2.2/jtop/core/common.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/config.py` & `jetson-stats-4.2.2/jtop/core/config.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/cpu.py` & `jetson-stats-4.2.2/jtop/core/cpu.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/engine.py` & `jetson-stats-4.2.2/jtop/core/engine.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/exceptions.py` & `jetson-stats-4.2.2/jtop/core/exceptions.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/fan.py` & `jetson-stats-4.2.2/jtop/core/fan.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/gpu.py` & `jetson-stats-4.2.2/jtop/core/gpu.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/hardware.py` & `jetson-stats-4.2.2/jtop/core/hardware.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/jetson_clocks.py` & `jetson-stats-4.2.2/jtop/core/jetson_clocks.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/jetson_libraries.py` & `jetson-stats-4.2.2/jtop/core/jetson_libraries.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/jetson_variables.py` & `jetson-stats-4.2.2/jtop/core/jetson_variables.py`

 * *Files 1% similar despite different names*

```diff
@@ -46,14 +46,15 @@
     "35.3.0": "5.1.1 PRE",
     "35.2.1": "5.1",
     "35.1.0": "5.0.2 GA",
     "34.1.1": "5.0.1 DP",
     "34.1.0": "5.0 DP",
     "34.0.1": "5.0 PRE-DP",
     # -------- JP4 --------
+    "32.7.4": "4.6.4",
     "32.7.3": "4.6.3",
     "32.7.2": "4.6.2",
     "32.7.1": "4.6.1",
     "32.6.1": "4.6",
     "32.5.2": "4.5.1",
     "32.5.1": "4.5.1",
     "32.5.0": "4.5",
```

### Comparing `jetson-stats-4.2.1/jtop/core/memory.py` & `jetson-stats-4.2.2/jtop/core/memory.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/nvpmodel.py` & `jetson-stats-4.2.2/jtop/core/nvpmodel.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/power.py` & `jetson-stats-4.2.2/jtop/core/power.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/processes.py` & `jetson-stats-4.2.2/jtop/core/processes.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/tegra_parse.py` & `jetson-stats-4.2.2/jtop/core/tegra_parse.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/tegrastats.py` & `jetson-stats-4.2.2/jtop/core/tegrastats.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/temperature.py` & `jetson-stats-4.2.2/jtop/core/temperature.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/core/timer_reader.py` & `jetson-stats-4.2.2/jtop/core/timer_reader.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/github.py` & `jetson-stats-4.2.2/jtop/github.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/__init__.py` & `jetson-stats-4.2.2/jtop/gui/__init__.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/jtopgui.py` & `jetson-stats-4.2.2/jtop/gui/jtopgui.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/jtopguiconfig.py` & `jetson-stats-4.2.2/jtop/gui/jtopguiconfig.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/__init__.py` & `jetson-stats-4.2.2/jtop/gui/lib/__init__.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/chart.py` & `jetson-stats-4.2.2/jtop/gui/lib/chart.py`

 * *Files 1% similar despite different names*

```diff
@@ -63,20 +63,23 @@
         values = list(range(len(self.color_chart)))[::-1] + [len(self.color_chart)]
         self._combinations = list(itertools.combinations(values, 2))
         list_colors = {}
         for c in self._combinations:
             if c[0] not in list_colors:
                 list_colors[c[0]] = []
             list_colors[c[0]] = [c] + list_colors[c[0]]
-        for idx, list_element in enumerate(list_colors.values()):
-            list_element = sorted(list_element, key=lambda x: x[1], reverse=True)
-            for idy, color_set in enumerate(list_element):
-                idx_name = Chart.OFFSET_COLOR_CHART + self._color_obj_counter + (len(self.color_chart) - idx - 1) * color_step + idy
-                second_color = self.color_chart[color_set[1]] if color_set[1] < len(self.color_chart) else curses.COLOR_BLACK
-                curses.init_pair(idx_name, self.color_chart[color_set[0]], second_color)
+        try:
+            for idx, list_element in enumerate(list_colors.values()):
+                list_element = sorted(list_element, key=lambda x: x[1], reverse=True)
+                for idy, color_set in enumerate(list_element):
+                    idx_name = Chart.OFFSET_COLOR_CHART + self._color_obj_counter + (len(self.color_chart) - idx - 1) * color_step + idy
+                    second_color = self.color_chart[color_set[1]] if color_set[1] < len(self.color_chart) else curses.COLOR_BLACK
+                    curses.init_pair(idx_name, self.color_chart[color_set[0]], second_color)
+        except curses.error:
+            curses.use_default_colors()
         # Update counter colors
         Chart.COLOR_COUNTER += len(self._combinations) + 1
         # Attach the chart for every update from jtop
         jetson.attach(self.update)
 
     def __del__(self):
         # Remove from color counter
```

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/colors.py` & `jetson-stats-4.2.2/jtop/gui/lib/colors.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/common.py` & `jetson-stats-4.2.2/jtop/gui/lib/common.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/linear_gauge.py` & `jetson-stats-4.2.2/jtop/gui/lib/linear_gauge.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/process_table.py` & `jetson-stats-4.2.2/jtop/gui/lib/process_table.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/lib/smallbutton.py` & `jetson-stats-4.2.2/jtop/gui/lib/smallbutton.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/pall.py` & `jetson-stats-4.2.2/jtop/gui/pall.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/pcontrol.py` & `jetson-stats-4.2.2/jtop/gui/pcontrol.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/pcpu.py` & `jetson-stats-4.2.2/jtop/gui/pcpu.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/pengine.py` & `jetson-stats-4.2.2/jtop/gui/pengine.py`

 * *Files 7% similar despite different names*

```diff
@@ -37,14 +37,23 @@
         add_engine_in_list('DLA0c', engine, 'DLA0', 'DLA0_CORE') + add_engine_in_list('DLA1c', engine, 'DLA1', 'DLA1_CORE'),
         add_engine_in_list('NVENC', engine, 'NVENC', 'NVENC') + add_engine_in_list('NVDEC', engine, 'NVDEC', 'NVDEC'),
         add_engine_in_list('NVJPG', engine, 'NVJPG', 'NVJPG') + add_engine_in_list('NVJPG1', engine, 'NVJPG', 'NVJPG1'),
         add_engine_in_list('SE', engine, 'SE', 'SE') + add_engine_in_list('VIC', engine, 'VIC', 'VIC'),
     ]
 
 
+def pass_orin_nano(engine):
+    return [
+        add_engine_in_list('APE', engine, 'APE', 'APE'),
+        add_engine_in_list('NVENC', engine, 'NVENC', 'NVENC') + add_engine_in_list('NVDEC', engine, 'NVDEC', 'NVDEC'),
+        add_engine_in_list('NVJPG', engine, 'NVJPG', 'NVJPG') + add_engine_in_list('NVJPG1', engine, 'NVJPG', 'NVJPG1'),
+        add_engine_in_list('SE', engine, 'SE', 'SE') + add_engine_in_list('VIC', engine, 'VIC', 'VIC'),
+    ]
+
+
 def map_xavier(engine):
     return [
         add_engine_in_list('APE', engine, 'APE', 'APE') + add_engine_in_list('CVNAS', engine, 'CVNAS', 'CVNAS'),
         add_engine_in_list('DLA0c', engine, 'DLA0', 'DLA0_CORE') + add_engine_in_list('DLA1c', engine, 'DLA1', 'DLA1_CORE'),
         add_engine_in_list('NVENC', engine, 'NVENC', 'NVENC') + add_engine_in_list('NVDEC', engine, 'NVDEC', 'NVDEC'),
         add_engine_in_list('NVJPG', engine, 'NVJPG', 'NVJPG') + add_engine_in_list('PVA0a', engine, 'PVA0', 'PVA0_AXI'),
         add_engine_in_list('SE', engine, 'SE', 'SE') + add_engine_in_list('VIC', engine, 'VIC', 'VIC'),
@@ -56,14 +65,15 @@
         add_engine_in_list('APE', engine, 'APE', 'APE'),
         add_engine_in_list('NVENC', engine, 'NVENC', 'NVENC') + add_engine_in_list('NVDEC', engine, 'NVDEC', 'NVDEC'),
         add_engine_in_list('NVJPG', engine, 'NVJPG', 'NVJPG') + add_engine_in_list('SE', engine, 'SE', 'SE'),
     ]
 
 
 MAP_JETSON_MODELS = {
+    'orin nano': pass_orin_nano,
     'orin nx': pass_orin,
     'agx orin': pass_orin,
     'xavier': map_xavier,
     'jetson nano': map_jetson_nano,
     'nintendo': map_jetson_nano,
     'jetson tx': map_jetson_nano,
 }
```

### Comparing `jetson-stats-4.2.1/jtop/gui/pgpu.py` & `jetson-stats-4.2.2/jtop/gui/pgpu.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/pinfo.py` & `jetson-stats-4.2.2/jtop/gui/pinfo.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/gui/pmem.py` & `jetson-stats-4.2.2/jtop/gui/pmem.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/jetson_config.py` & `jetson-stats-4.2.2/jtop/jetson_config.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/jetson_release.py` & `jetson-stats-4.2.2/jtop/jetson_release.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/jetson_swap.py` & `jetson-stats-4.2.2/jtop/jetson_swap.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/jtop.py` & `jetson-stats-4.2.2/jtop/jtop.py`

 * *Files 1% similar despite different names*

```diff
@@ -585,29 +585,32 @@
         if self.jetson_clocks is not None:
             stats['jetson_clocks'] = 'ON' if self.jetson_clocks else 'OFF'
         # -- NV Power Model --
         if self.nvpmodel is not None:
             stats['nvp model'] = self.nvpmodel.name
         return stats
 
-    def json(self, stats=False):
+    def json(self, stats=False, **json_args):
         """
         This method export all metrics in a `json` readable output.
 
         You can export all metrics or the same output in :py:attr:`stats` depending of the parameter input.
 
         :param stats: json with same output of :py:attr:`stats`, defaults to False
         :type stats: bool, optional
+        :param json_args: additional keyword arguments passed to json.dumps
+        :type json_args: Any
         :return: json output requested
         :rtype: str
         """
         if stats:
-            return json.dumps(self.stats, cls=DateTimeEncoder)
+            json_args.setdefault("cls", DateTimeEncoder)
+            return json.dumps(self.stats, **json_args)
         # Read all variable and build a complete json
-        return json.dumps(self._stats)
+        return json.dumps(self._stats, **json_args)
 
     @property
     def memory(self):
         """
         This property show in a simple way all memories available, the main output is available in this way:
 
         * **RAM** - It is a dictionary with all information about RAM :sup:`A`
```

### Comparing `jetson-stats-4.2.1/jtop/service.py` & `jetson-stats-4.2.2/jtop/service.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/jtop/terminal_colors.py` & `jetson-stats-4.2.2/jtop/terminal_colors.py`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/scripts/jtop_env.sh` & `jetson-stats-4.2.2/scripts/jtop_env.sh`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/services/jtop.service` & `jetson-stats-4.2.2/services/jtop.service`

 * *Files identical despite different names*

### Comparing `jetson-stats-4.2.1/setup.py` & `jetson-stats-4.2.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -241,15 +241,15 @@
         "Programming Language :: Python :: 3.8",
         "Programming Language :: Python :: 3.9",
         "Programming Language :: Python :: 3.10",
         "Programming Language :: Python :: 3.11",
         "Operating System :: POSIX :: Linux"],
     # Requisites
     # https://packaging.python.org/guides/distributing-packages-using-setuptools/#python-requires
-    python_requires='>=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, <4',
+    python_requires='>=2.7',
     platforms=["linux", "linux2", "darwin"],
     install_requires=requirements,
     # Zip safe configuration
     # https://setuptools.readthedocs.io/en/latest/setuptools.html#setting-the-zip-safe-flag
     zip_safe=False,
     # Add jetson_variables in /opt/jetson_stats
     # http://docs.python.org/3.4/distutils/setupscript.html#installing-additional-files
```


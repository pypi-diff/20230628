# Comparing `tmp/srsinst.rga-0.3.3.tar.gz` & `tmp/srsinst.rga-0.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "C:\PyPI\instrument_library\rga100\dist\.tmp-2q4_xfpq\srsinst.rga-0.3.3.tar", last modified: Wed Jun 14 20:09:00 2023, max compression
+gzip compressed data, was "C:\PyPI\instrument_library\rga100\dist\.tmp-8fy2vqdz\srsinst.rga-0.3.4.tar", last modified: Wed Jun 28 16:10:11 2023, max compression
```

## Comparing `srsinst.rga-0.3.3.tar` & `srsinst.rga-0.3.4.tar`

### file list

```diff
@@ -1,72 +1,72 @@
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.852535 srsinst.rga-0.3.3/
--rw-rw-rw-   0        0        0     1113 2023-05-16 22:11:28.000000 srsinst.rga-0.3.3/LICENSE
--rw-rw-rw-   0        0        0     6841 2023-06-14 20:09:00.852535 srsinst.rga-0.3.3/PKG-INFO
--rw-rw-rw-   0        0        0     5838 2023-06-14 00:09:13.000000 srsinst.rga-0.3.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.794016 srsinst.rga-0.3.3/docs/
--rw-rw-rw-   0        0        0      654 2023-05-19 21:28:01.000000 srsinst.rga-0.3.3/docs/Makefile
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.756685 srsinst.rga-0.3.3/docs/_static/
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.804015 srsinst.rga-0.3.3/docs/_static/image/
--rw-rw-rw-   0        0        0   174977 2023-06-09 18:18:12.000000 srsinst.rga-0.3.3/docs/_static/image/comp-analysis-screenshot.png
--rw-rw-rw-   0        0        0   115947 2023-05-19 17:56:22.000000 srsinst.rga-0.3.3/docs/_static/image/derived-pvst-plot-screenshot.png
--rw-rw-rw-   0        0        0    51322 2023-06-09 22:02:41.000000 srsinst.rga-0.3.3/docs/_static/image/initial-screen-capture.png
--rw-rw-rw-   0        0        0    27661 2023-05-25 23:24:03.000000 srsinst.rga-0.3.3/docs/_static/image/simple-analog-scan-screenshot.png
--rw-rw-rw-   0        0        0     1970 2023-06-13 20:55:52.000000 srsinst.rga-0.3.3/docs/conf.py
--rw-rw-rw-   0        0        0      356 2023-06-01 23:58:11.000000 srsinst.rga-0.3.3/docs/custom_tasks.rst
--rw-rw-rw-   0        0        0     6252 2023-06-12 22:33:57.000000 srsinst.rga-0.3.3/docs/gui_application.rst
--rw-rw-rw-   0        0        0     2584 2023-06-12 23:28:46.000000 srsinst.rga-0.3.3/docs/index.rst
--rw-rw-rw-   0        0        0     4199 2023-06-12 17:15:20.000000 srsinst.rga-0.3.3/docs/installation.rst
--rw-rw-rw-   0        0        0    16282 2023-06-12 20:44:51.000000 srsinst.rga-0.3.3/docs/instrument_driver.rst
--rwxrwxrwx   0        0        0      802 2023-05-19 21:28:01.000000 srsinst.rga-0.3.3/docs/make.bat
--rw-rw-rw-   0        0        0       32 2023-05-19 21:28:01.000000 srsinst.rga-0.3.3/docs/requirements.txt
--rw-rw-rw-   0        0        0     1332 2023-05-31 23:18:38.000000 srsinst.rga-0.3.3/docs/srsinst.rga.instruments.rga100.rst
--rw-rw-rw-   0        0        0      358 2023-05-19 21:28:01.000000 srsinst.rga-0.3.3/docs/srsinst.rga.instruments.rst
--rw-rw-rw-   0        0        0     1049 2023-06-09 19:15:10.000000 srsinst.rga-0.3.3/docs/srsinst.rga.plots.rst
--rw-rw-rw-   0        0        0      148 2023-05-31 23:17:11.000000 srsinst.rga-0.3.3/docs/srsinst.rga.rst
--rw-rw-rw-   0        0        0     2098 2023-06-14 18:25:03.000000 srsinst.rga-0.3.3/docs/srsinst.rga.tasks.rst
--rw-rw-rw-   0        0        0     1471 2023-06-14 20:02:52.000000 srsinst.rga-0.3.3/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-14 20:09:00.852535 srsinst.rga-0.3.3/setup.cfg
--rw-rw-rw-   0        0        0       41 2023-02-09 00:46:42.000000 srsinst.rga-0.3.3/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.756685 srsinst.rga-0.3.3/srsinst/
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.814047 srsinst.rga-0.3.3/srsinst/rga/
--rw-rw-rw-   0        0        0      349 2023-06-14 20:05:00.000000 srsinst.rga-0.3.3/srsinst/rga/__init__.py
--rw-rw-rw-   0        0        0      483 2023-05-19 21:11:26.000000 srsinst.rga-0.3.3/srsinst/rga/__main__.py
--rw-rw-rw-   0        0        0    10675 2023-06-01 21:25:29.000000 srsinst.rga-0.3.3/srsinst/rga/gaslib.dat
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.814047 srsinst.rga-0.3.3/srsinst/rga/instruments/
--rw-rw-rw-   0        0        0       38 2023-06-14 18:20:37.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/__init__.py
--rw-rw-rw-   0        0        0      872 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/get_instruments.py
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.824015 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/
--rw-rw-rw-   0        0        0        0 2023-05-19 21:11:26.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/__init__.py
--rw-rw-rw-   0        0        0     5249 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/commands.py
--rw-rw-rw-   0        0        0     7355 2023-05-25 20:26:25.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/components.py
--rw-rw-rw-   0        0        0     4510 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/errors.py
--rw-rw-rw-   0        0        0     8719 2023-06-13 23:56:14.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/rga.py
--rw-rw-rw-   0        0        0    18656 2023-05-19 21:11:26.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/rga_commands.json
--rw-rw-rw-   0        0        0    11740 2023-05-31 21:39:25.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/scans.py
--rw-rw-rw-   0        0        0     9870 2023-06-06 21:51:12.000000 srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/sicp.py
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.832502 srsinst.rga-0.3.3/srsinst/rga/plots/
--rw-rw-rw-   0        0        0        0 2023-05-19 21:11:26.000000 srsinst.rga-0.3.3/srsinst/rga/plots/__init__.py
--rw-rw-rw-   0        0        0     4122 2023-06-09 19:33:09.000000 srsinst.rga-0.3.3/srsinst/rga/plots/analogscanplot.py
--rw-rw-rw-   0        0        0     3448 2023-06-09 18:23:15.000000 srsinst.rga-0.3.3/srsinst/rga/plots/analysis.py
--rw-rw-rw-   0        0        0     3287 2023-06-09 19:32:57.000000 srsinst.rga-0.3.3/srsinst/rga/plots/basescanplot.py
--rw-rw-rw-   0        0        0     3792 2023-06-09 19:32:57.000000 srsinst.rga-0.3.3/srsinst/rga/plots/histogramscanplot.py
--rw-rw-rw-   0        0        0     9182 2023-06-09 19:33:28.000000 srsinst.rga-0.3.3/srsinst/rga/plots/timeplot.py
--rw-rw-rw-   0        0        0     2226 2023-06-01 00:10:48.000000 srsinst.rga-0.3.3/srsinst/rga/rga.taskconfig
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.842505 srsinst.rga-0.3.3/srsinst/rga/tasks/
--rw-rw-rw-   0        0        0        0 2023-05-19 21:11:26.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/__init__.py
--rw-rw-rw-   0        0        0     4001 2023-05-31 18:21:03.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/analogscantask.py
--rw-rw-rw-   0        0        0     2543 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/cemcontroltask.py
--rw-rw-rw-   0        0        0     9379 2023-06-02 18:26:25.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/cemgaintask.py
--rw-rw-rw-   0        0        0     9586 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/compositionanalysistask.py
--rw-rw-rw-   0        0        0     5243 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/derivedpvstscantask.py
--rw-rw-rw-   0        0        0     2751 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/filamentcontroltask.py
--rw-rw-rw-   0        0        0     3685 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/histogramscantask.py
--rw-rw-rw-   0        0        0    11440 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/peaktuningtask.py
--rw-rw-rw-   0        0        0     2557 2023-05-19 21:13:35.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/pvstscantask.py
--rw-rw-rw-   0        0        0     2591 2023-06-06 22:11:10.000000 srsinst.rga-0.3.3/srsinst/rga/tasks/searchlan.py
-drwxrwxrwx   0        0        0        0 2023-06-14 20:09:00.804015 srsinst.rga-0.3.3/srsinst.rga.egg-info/
--rw-rw-rw-   0        0        0     6841 2023-06-14 20:09:00.000000 srsinst.rga-0.3.3/srsinst.rga.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1890 2023-06-14 20:09:00.000000 srsinst.rga-0.3.3/srsinst.rga.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-14 20:09:00.000000 srsinst.rga-0.3.3/srsinst.rga.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       50 2023-06-14 20:09:00.000000 srsinst.rga-0.3.3/srsinst.rga.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0      117 2023-06-14 20:09:00.000000 srsinst.rga-0.3.3/srsinst.rga.egg-info/requires.txt
--rw-rw-rw-   0        0        0        8 2023-06-14 20:09:00.000000 srsinst.rga-0.3.3/srsinst.rga.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.677071 srsinst.rga-0.3.4/
+-rw-rw-rw-   0        0        0     1113 2023-05-16 22:11:28.000000 srsinst.rga-0.3.4/LICENSE
+-rw-rw-rw-   0        0        0     6878 2023-06-28 16:10:11.677071 srsinst.rga-0.3.4/PKG-INFO
+-rw-rw-rw-   0        0        0     5875 2023-06-23 19:14:43.000000 srsinst.rga-0.3.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.642387 srsinst.rga-0.3.4/docs/
+-rw-rw-rw-   0        0        0      654 2023-05-19 21:28:01.000000 srsinst.rga-0.3.4/docs/Makefile
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.615184 srsinst.rga-0.3.4/docs/_static/
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.652384 srsinst.rga-0.3.4/docs/_static/image/
+-rw-rw-rw-   0        0        0   174977 2023-06-09 18:18:12.000000 srsinst.rga-0.3.4/docs/_static/image/comp-analysis-screenshot.png
+-rw-rw-rw-   0        0        0   115947 2023-05-19 17:56:22.000000 srsinst.rga-0.3.4/docs/_static/image/derived-pvst-plot-screenshot.png
+-rw-rw-rw-   0        0        0    51322 2023-06-09 22:02:41.000000 srsinst.rga-0.3.4/docs/_static/image/initial-screen-capture.png
+-rw-rw-rw-   0        0        0    27661 2023-05-25 23:24:03.000000 srsinst.rga-0.3.4/docs/_static/image/simple-analog-scan-screenshot.png
+-rw-rw-rw-   0        0        0     1970 2023-06-13 20:55:52.000000 srsinst.rga-0.3.4/docs/conf.py
+-rw-rw-rw-   0        0        0      356 2023-06-01 23:58:11.000000 srsinst.rga-0.3.4/docs/custom_tasks.rst
+-rw-rw-rw-   0        0        0     6252 2023-06-12 22:33:57.000000 srsinst.rga-0.3.4/docs/gui_application.rst
+-rw-rw-rw-   0        0        0     2604 2023-06-23 19:08:23.000000 srsinst.rga-0.3.4/docs/index.rst
+-rw-rw-rw-   0        0        0     4199 2023-06-12 17:15:20.000000 srsinst.rga-0.3.4/docs/installation.rst
+-rw-rw-rw-   0        0        0    16282 2023-06-12 20:44:51.000000 srsinst.rga-0.3.4/docs/instrument_driver.rst
+-rwxrwxrwx   0        0        0      802 2023-05-19 21:28:01.000000 srsinst.rga-0.3.4/docs/make.bat
+-rw-rw-rw-   0        0        0       32 2023-05-19 21:28:01.000000 srsinst.rga-0.3.4/docs/requirements.txt
+-rw-rw-rw-   0        0        0     1332 2023-05-31 23:18:38.000000 srsinst.rga-0.3.4/docs/srsinst.rga.instruments.rga100.rst
+-rw-rw-rw-   0        0        0      358 2023-05-19 21:28:01.000000 srsinst.rga-0.3.4/docs/srsinst.rga.instruments.rst
+-rw-rw-rw-   0        0        0     1049 2023-06-09 19:15:10.000000 srsinst.rga-0.3.4/docs/srsinst.rga.plots.rst
+-rw-rw-rw-   0        0        0      148 2023-05-31 23:17:11.000000 srsinst.rga-0.3.4/docs/srsinst.rga.rst
+-rw-rw-rw-   0        0        0     2098 2023-06-14 18:25:03.000000 srsinst.rga-0.3.4/docs/srsinst.rga.tasks.rst
+-rw-rw-rw-   0        0        0     1471 2023-06-27 19:55:31.000000 srsinst.rga-0.3.4/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 16:10:11.677071 srsinst.rga-0.3.4/setup.cfg
+-rw-rw-rw-   0        0        0       41 2023-02-09 00:46:42.000000 srsinst.rga-0.3.4/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.615184 srsinst.rga-0.3.4/srsinst/
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.657699 srsinst.rga-0.3.4/srsinst/rga/
+-rw-rw-rw-   0        0        0      349 2023-06-23 00:21:30.000000 srsinst.rga-0.3.4/srsinst/rga/__init__.py
+-rw-rw-rw-   0        0        0      483 2023-05-19 21:11:26.000000 srsinst.rga-0.3.4/srsinst/rga/__main__.py
+-rw-rw-rw-   0        0        0    10675 2023-06-01 21:25:29.000000 srsinst.rga-0.3.4/srsinst/rga/gaslib.dat
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.657699 srsinst.rga-0.3.4/srsinst/rga/instruments/
+-rw-rw-rw-   0        0        0       38 2023-06-14 18:20:37.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/__init__.py
+-rw-rw-rw-   0        0        0      872 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/get_instruments.py
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.667697 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/
+-rw-rw-rw-   0        0        0        0 2023-05-19 21:11:26.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/__init__.py
+-rw-rw-rw-   0        0        0     5249 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/commands.py
+-rw-rw-rw-   0        0        0     7355 2023-05-25 20:26:25.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/components.py
+-rw-rw-rw-   0        0        0     4510 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/errors.py
+-rw-rw-rw-   0        0        0     8719 2023-06-13 23:56:14.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/rga.py
+-rw-rw-rw-   0        0        0    18656 2023-05-19 21:11:26.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/rga_commands.json
+-rw-rw-rw-   0        0        0    11740 2023-05-31 21:39:25.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/scans.py
+-rw-rw-rw-   0        0        0     9870 2023-06-06 21:51:12.000000 srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/sicp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.667697 srsinst.rga-0.3.4/srsinst/rga/plots/
+-rw-rw-rw-   0        0        0        0 2023-05-19 21:11:26.000000 srsinst.rga-0.3.4/srsinst/rga/plots/__init__.py
+-rw-rw-rw-   0        0        0     4122 2023-06-09 19:33:09.000000 srsinst.rga-0.3.4/srsinst/rga/plots/analogscanplot.py
+-rw-rw-rw-   0        0        0     3448 2023-06-09 18:23:15.000000 srsinst.rga-0.3.4/srsinst/rga/plots/analysis.py
+-rw-rw-rw-   0        0        0     3287 2023-06-09 19:32:57.000000 srsinst.rga-0.3.4/srsinst/rga/plots/basescanplot.py
+-rw-rw-rw-   0        0        0     3792 2023-06-09 19:32:57.000000 srsinst.rga-0.3.4/srsinst/rga/plots/histogramscanplot.py
+-rw-rw-rw-   0        0        0     9182 2023-06-09 19:33:28.000000 srsinst.rga-0.3.4/srsinst/rga/plots/timeplot.py
+-rw-rw-rw-   0        0        0     2615 2023-06-22 22:26:52.000000 srsinst.rga-0.3.4/srsinst/rga/rga.taskconfig
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.677071 srsinst.rga-0.3.4/srsinst/rga/tasks/
+-rw-rw-rw-   0        0        0        0 2023-05-19 21:11:26.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/__init__.py
+-rw-rw-rw-   0        0        0     4001 2023-05-31 18:21:03.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/analogscantask.py
+-rw-rw-rw-   0        0        0     2543 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/cemcontroltask.py
+-rw-rw-rw-   0        0        0     9379 2023-06-02 18:26:25.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/cemgaintask.py
+-rw-rw-rw-   0        0        0     9586 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/compositionanalysistask.py
+-rw-rw-rw-   0        0        0     5243 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/derivedpvstscantask.py
+-rw-rw-rw-   0        0        0     2751 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/filamentcontroltask.py
+-rw-rw-rw-   0        0        0     3685 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/histogramscantask.py
+-rw-rw-rw-   0        0        0    11440 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/peaktuningtask.py
+-rw-rw-rw-   0        0        0     2557 2023-05-19 21:13:35.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/pvstscantask.py
+-rw-rw-rw-   0        0        0     2591 2023-06-06 22:11:10.000000 srsinst.rga-0.3.4/srsinst/rga/tasks/searchlan.py
+drwxrwxrwx   0        0        0        0 2023-06-28 16:10:11.657699 srsinst.rga-0.3.4/srsinst.rga.egg-info/
+-rw-rw-rw-   0        0        0     6878 2023-06-28 16:10:11.000000 srsinst.rga-0.3.4/srsinst.rga.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1890 2023-06-28 16:10:11.000000 srsinst.rga-0.3.4/srsinst.rga.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 16:10:11.000000 srsinst.rga-0.3.4/srsinst.rga.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       50 2023-06-28 16:10:11.000000 srsinst.rga-0.3.4/srsinst.rga.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0      117 2023-06-28 16:10:11.000000 srsinst.rga-0.3.4/srsinst.rga.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        8 2023-06-28 16:10:11.000000 srsinst.rga-0.3.4/srsinst.rga.egg-info/top_level.txt
```

### Comparing `srsinst.rga-0.3.3/LICENSE` & `srsinst.rga-0.3.4/LICENSE`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/PKG-INFO` & `srsinst.rga-0.3.4/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: srsinst.rga
-Version: 0.3.3
+Version: 0.3.4
 Summary: Instrument driver package for Residual Gas Analyzers (RGA) from Stanford Research Systems
 Author: Chulhoon Kim
 License: MIT license
 Project-URL: homepage, https://github.com/thinkSRS/srsinst.rga
 Project-URL: repository, https://github.com/thinkSRS/srsinst.rga.git
 Project-URL: documentation, https://thinksrs.github.io/srsinst.rga
 Keywords: RGA,residual gas analyzer,SRS,Stanford Research Systems
@@ -24,26 +24,26 @@
 
 # `srsinst.rga`
 
 `srsinst.rga` provides Python instrument classes to control and acquire mass spectra from 
 [Stanford Research Systems (SRS) Residual Gas Analyzers (RGA)](https://thinksrs.com/products/rga.html).
 It also provides tasks running in GUI environment based on 
 [srsgui](https://thinksrs.github.io/srsgui/).  
-To operate an SRS RGA with this package safely, you need to be familiar with SRS RGAs. 
-For detailed information, refer to the 
-[manual](https://thinksrs.com/downloads/pdfs/manuals/RGAm.pdf).
+For safe operation of an SRS RGA with this package, familiarize yourself with the RGA
+[manual](https://thinksrs.com/downloads/pdfs/manuals/RGAm.pdf) and
+the `srsinst.rga` [documentation](https://thinksrs.github.io/srsinst.rga/).
 
 ![screenshot](https://thinksrs.github.io/srsinst.rga/_images/comp-analysis-screenshot.png " ")
 
 ## Installation
 You need a working Python version 3.7 or later with `pip` (Python package installer) installed. 
 If you don't, [install Python 3](https://www.python.org/) to your system.
 
 To use its full GUI application, create a virtual environment, if necessary,
-and rub Python package installer `pip` with *[full]* option from the command prompt.
+and run Python package installer `pip` with *[full]* option from the command prompt.
 
     # To create a simple virtual environment (Optional) 
     # The activate command may differ depending on your computer operating systems.
     # Following is for Windows.
 
     python -m venv venv
     venv\scripts\activate
```

### Comparing `srsinst.rga-0.3.3/README.md` & `srsinst.rga-0.3.4/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 # `srsinst.rga`
 
 `srsinst.rga` provides Python instrument classes to control and acquire mass spectra from 
 [Stanford Research Systems (SRS) Residual Gas Analyzers (RGA)](https://thinksrs.com/products/rga.html).
 It also provides tasks running in GUI environment based on 
 [srsgui](https://thinksrs.github.io/srsgui/).  
-To operate an SRS RGA with this package safely, you need to be familiar with SRS RGAs. 
-For detailed information, refer to the 
-[manual](https://thinksrs.com/downloads/pdfs/manuals/RGAm.pdf).
+For safe operation of an SRS RGA with this package, familiarize yourself with the RGA
+[manual](https://thinksrs.com/downloads/pdfs/manuals/RGAm.pdf) and
+the `srsinst.rga` [documentation](https://thinksrs.github.io/srsinst.rga/).
 
 ![screenshot](https://thinksrs.github.io/srsinst.rga/_images/comp-analysis-screenshot.png " ")
 
 ## Installation
 You need a working Python version 3.7 or later with `pip` (Python package installer) installed. 
 If you don't, [install Python 3](https://www.python.org/) to your system.
 
 To use its full GUI application, create a virtual environment, if necessary,
-and rub Python package installer `pip` with *[full]* option from the command prompt.
+and run Python package installer `pip` with *[full]* option from the command prompt.
 
     # To create a simple virtual environment (Optional) 
     # The activate command may differ depending on your computer operating systems.
     # Following is for Windows.
 
     python -m venv venv
     venv\scripts\activate
```

### Comparing `srsinst.rga-0.3.3/docs/Makefile` & `srsinst.rga-0.3.4/docs/Makefile`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/_static/image/comp-analysis-screenshot.png` & `srsinst.rga-0.3.4/docs/_static/image/comp-analysis-screenshot.png`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/_static/image/derived-pvst-plot-screenshot.png` & `srsinst.rga-0.3.4/docs/_static/image/derived-pvst-plot-screenshot.png`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/_static/image/initial-screen-capture.png` & `srsinst.rga-0.3.4/docs/_static/image/initial-screen-capture.png`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/_static/image/simple-analog-scan-screenshot.png` & `srsinst.rga-0.3.4/docs/_static/image/simple-analog-scan-screenshot.png`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/conf.py` & `srsinst.rga-0.3.4/docs/conf.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/gui_application.rst` & `srsinst.rga-0.3.4/docs/gui_application.rst`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/index.rst` & `srsinst.rga-0.3.4/docs/index.rst`

 * *Files 2% similar despite different names*

```diff
@@ -4,15 +4,16 @@
 .. _overview:
 
 ``srsinst.rga`` documentation
 ===================================
 
 ``srsinst.rga`` is a `Python package <package_>`_ to control and acquire data from
 a `Stanford Research Systems (SRS) Residual Gas Analyzer (RGA) <rga100_>`_,
-using the `srsgui`_  package as a base instrument driver and a graphic user interface (GUI).
+using the `srsgui`_  package as a base instrument driver as well as a graphic user interface (GUI)
+application.
 
     ..  figure:: ./_static/image/comp-analysis-screenshot.png
         :align: center
         :scale: 50 %
 
         Screenshot of srsinst.rga application
```

### Comparing `srsinst.rga-0.3.3/docs/installation.rst` & `srsinst.rga-0.3.4/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/instrument_driver.rst` & `srsinst.rga-0.3.4/docs/instrument_driver.rst`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/make.bat` & `srsinst.rga-0.3.4/docs/make.bat`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/srsinst.rga.instruments.rga100.rst` & `srsinst.rga-0.3.4/docs/srsinst.rga.instruments.rga100.rst`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/srsinst.rga.plots.rst` & `srsinst.rga-0.3.4/docs/srsinst.rga.plots.rst`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/docs/srsinst.rga.tasks.rst` & `srsinst.rga-0.3.4/docs/srsinst.rga.tasks.rst`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/pyproject.toml` & `srsinst.rga-0.3.4/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -20,24 +20,24 @@
         "Programming Language :: Python :: 3.7",
         "Programming Language :: Python :: 3.8",
         "Programming Language :: Python :: 3.9",
         "Programming Language :: Python :: 3.10",
         "Topic :: Scientific/Engineering"
 ]
 dependencies = [
-    "numpy", "scipy", "srsgui >=0.3.2",
+    "numpy", "scipy", "srsgui >=0.4.0",
 ]
 dynamic = ["version"]
 
 [tool.setuptools.dynamic]
 version = {attr = "srsinst.rga.__version__"}
 
 [project.optional-dependencies]
 full = ['matplotlib >= 3.6.2', 'pyside6']
-docs = ['matplotlib', 'pyside6', 'sphinx>=5', 'sphinx-rtd-theme>=1']
+docs = ['matplotlib', 'pyside2', 'sphinx>=5', 'sphinx-rtd-theme>=1']
 # For Dependency specification, Refer to PEP 631
 
 [project.urls]
 homepage = "https://github.com/thinkSRS/srsinst.rga"
 repository = "https://github.com/thinkSRS/srsinst.rga.git"
 documentation = "https://thinksrs.github.io/srsinst.rga"
```

### Comparing `srsinst.rga-0.3.3/srsinst/rga/gaslib.dat` & `srsinst.rga-0.3.4/srsinst/rga/gaslib.dat`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/get_instruments.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/get_instruments.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/commands.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/commands.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/components.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/components.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/errors.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/errors.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/rga.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/rga.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/rga_commands.json` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/rga_commands.json`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/scans.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/scans.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/instruments/rga100/sicp.py` & `srsinst.rga-0.3.4/srsinst/rga/instruments/rga100/sicp.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/plots/analogscanplot.py` & `srsinst.rga-0.3.4/srsinst/rga/plots/analogscanplot.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/plots/analysis.py` & `srsinst.rga-0.3.4/srsinst/rga/plots/analysis.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/plots/basescanplot.py` & `srsinst.rga-0.3.4/srsinst/rga/plots/basescanplot.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/plots/histogramscanplot.py` & `srsinst.rga-0.3.4/srsinst/rga/plots/histogramscanplot.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/plots/timeplot.py` & `srsinst.rga-0.3.4/srsinst/rga/plots/timeplot.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/rga.taskconfig` & `srsinst.rga-0.3.4/srsinst/rga/rga.taskconfig`

 * *Files 6% similar despite different names*

```diff
@@ -1,14 +1,24 @@
 # Line that starts with '#' is a comment line
 # RGA Task list for srsgui
 
 # The name is used for the main window title
 
 Name: RGA Tasks
 
+
+# A line starting with 'docs' is used as a documentation link.
+# Documentation links will appear in the Help menu.
+# The first item in the line is used as the documentation name.
+# The second item is used as a URL that whill open with the system default web browser.
+
+docs: Srsinst.rga, https://thinksrs.github.io/srsinst.rga/
+docs: Srsgui, https://thinksrs.github.io/srsgui/
+
+
 # Specify Instruments used in the task suite
 # A line that starts with 'inst' adds an instrument to be used in the following tasks.
 # An instrument is a subclass derived from Instrument class in 'srsgui' package
 # The second column is the name of the Python module or package that contains the instrument class.
 # The third column is a instrument class in the module
 # The fourth column is connection parameters.
 # If the fourth item is given, the instrument will be connected using the parameters
```

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/analogscantask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/analogscantask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/cemcontroltask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/cemcontroltask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/cemgaintask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/cemgaintask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/compositionanalysistask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/compositionanalysistask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/derivedpvstscantask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/derivedpvstscantask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/filamentcontroltask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/filamentcontroltask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/histogramscantask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/histogramscantask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/peaktuningtask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/peaktuningtask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/pvstscantask.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/pvstscantask.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst/rga/tasks/searchlan.py` & `srsinst.rga-0.3.4/srsinst/rga/tasks/searchlan.py`

 * *Files identical despite different names*

### Comparing `srsinst.rga-0.3.3/srsinst.rga.egg-info/PKG-INFO` & `srsinst.rga-0.3.4/srsinst.rga.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: srsinst.rga
-Version: 0.3.3
+Version: 0.3.4
 Summary: Instrument driver package for Residual Gas Analyzers (RGA) from Stanford Research Systems
 Author: Chulhoon Kim
 License: MIT license
 Project-URL: homepage, https://github.com/thinkSRS/srsinst.rga
 Project-URL: repository, https://github.com/thinkSRS/srsinst.rga.git
 Project-URL: documentation, https://thinksrs.github.io/srsinst.rga
 Keywords: RGA,residual gas analyzer,SRS,Stanford Research Systems
@@ -24,26 +24,26 @@
 
 # `srsinst.rga`
 
 `srsinst.rga` provides Python instrument classes to control and acquire mass spectra from 
 [Stanford Research Systems (SRS) Residual Gas Analyzers (RGA)](https://thinksrs.com/products/rga.html).
 It also provides tasks running in GUI environment based on 
 [srsgui](https://thinksrs.github.io/srsgui/).  
-To operate an SRS RGA with this package safely, you need to be familiar with SRS RGAs. 
-For detailed information, refer to the 
-[manual](https://thinksrs.com/downloads/pdfs/manuals/RGAm.pdf).
+For safe operation of an SRS RGA with this package, familiarize yourself with the RGA
+[manual](https://thinksrs.com/downloads/pdfs/manuals/RGAm.pdf) and
+the `srsinst.rga` [documentation](https://thinksrs.github.io/srsinst.rga/).
 
 ![screenshot](https://thinksrs.github.io/srsinst.rga/_images/comp-analysis-screenshot.png " ")
 
 ## Installation
 You need a working Python version 3.7 or later with `pip` (Python package installer) installed. 
 If you don't, [install Python 3](https://www.python.org/) to your system.
 
 To use its full GUI application, create a virtual environment, if necessary,
-and rub Python package installer `pip` with *[full]* option from the command prompt.
+and run Python package installer `pip` with *[full]* option from the command prompt.
 
     # To create a simple virtual environment (Optional) 
     # The activate command may differ depending on your computer operating systems.
     # Following is for Windows.
 
     python -m venv venv
     venv\scripts\activate
```

### Comparing `srsinst.rga-0.3.3/srsinst.rga.egg-info/SOURCES.txt` & `srsinst.rga-0.3.4/srsinst.rga.egg-info/SOURCES.txt`

 * *Files identical despite different names*


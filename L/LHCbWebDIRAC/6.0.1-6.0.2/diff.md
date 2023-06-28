# Comparing `tmp/LHCbWebDIRAC-6.0.1.tar.gz` & `tmp/LHCbWebDIRAC-6.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "LHCbWebDIRAC-6.0.1.tar", last modified: Tue Jan 24 10:35:52 2023, max compression
+gzip compressed data, was "LHCbWebDIRAC-6.0.2.tar", last modified: Wed Jun 28 13:15:00 2023, max compression
```

## Comparing `LHCbWebDIRAC-6.0.1.tar` & `LHCbWebDIRAC-6.0.2.tar`

### file list

```diff
@@ -1,174 +1,174 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.008000 LHCbWebDIRAC-6.0.1/
--rw-r--r--   0 root         (0) root         (0)      867 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/CONTRIBUTING.md
--rw-r--r--   0 root         (0) root         (0)    35075 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/LICENSE
--rw-r--r--   0 root         (0) root         (0)      120 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     1264 2023-01-24 10:35:52.008000 LHCbWebDIRAC-6.0.1/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      558 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/README.md
--rw-r--r--   0 root         (0) root         (0)      528 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)      126 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/pytest.ini
--rw-r--r--   0 root         (0) root         (0)     1221 2023-01-24 10:35:52.008000 LHCbWebDIRAC-6.0.1/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      944 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.964000 LHCbWebDIRAC-6.0.1/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.976000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.980000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.980000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/
--rw-r--r--   0 root         (0) root         (0)     2690 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appAcounting.tpl
--rw-r--r--   0 root         (0) root         (0)     1897 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingBrowser.tpl
--rw-r--r--   0 root         (0) root         (0)     1946 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingSimDescription.tpl
--rw-r--r--   0 root         (0) root         (0)     1936 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appJobMonitor.tpl
--rw-r--r--   0 root         (0) root         (0)     1956 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotMonitor.tpl
--rw-r--r--   0 root         (0) root         (0)     1956 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotSummary.tpl
--rw-r--r--   0 root         (0) root         (0)     2028 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appTransformationMonitor.tpl
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.984000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/
--rw-r--r--   0 root         (0) root         (0)     1010 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/AccountingHandler.py
--rw-r--r--   0 root         (0) root         (0)    21215 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/BookkeepingBrowserHandler.py
--rw-r--r--   0 root         (0) root         (0)     5479 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/BookkeepingSimDescriptionHandler.py
--rw-r--r--   0 root         (0) root         (0)     4605 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/DowntimesHandler.py
--rw-r--r--   0 root         (0) root         (0)     1399 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbJobMonitorHandler.py
--rw-r--r--   0 root         (0) root         (0)     1002 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotMonitorHandler.py
--rw-r--r--   0 root         (0) root         (0)     1002 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotSummaryHandler.py
--rw-r--r--   0 root         (0) root         (0)    15406 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbStepManagerHandler.py
--rw-r--r--   0 root         (0) root         (0)     7078 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbTransformationMonitorHandler.py
--rw-r--r--   0 root         (0) root         (0)     4076 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/ProductionLib.py
--rw-r--r--   0 root         (0) root         (0)    36466 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/ProductionRequestManagerHandler.py
--rw-r--r--   0 root         (0) root         (0)     9177 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/RAWIntegrityMonitorHandler.py
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.968000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.976000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.968000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.984000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/classes/
--rw-r--r--   0 root         (0) root         (0)     4132 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/classes/Accounting.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.984000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/css/Accounting.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.968000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.988000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/
--rw-r--r--   0 root         (0) root         (0)     4027 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/AdvancedSaveWindow.js
--rw-r--r--   0 root         (0) root         (0)     4148 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingAddBookmarks.js
--rw-r--r--   0 root         (0) root         (0)    37255 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingBrowser.js
--rw-r--r--   0 root         (0) root         (0)     1011 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingTreeItemModel.js
--rw-r--r--   0 root         (0) root         (0)     9383 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/FileHistoryPanel.js
--rw-r--r--   0 root         (0) root         (0)     2835 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/LookupWindow.js
--rw-r--r--   0 root         (0) root         (0)     3705 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/ProcessingPassViewer.js
--rw-r--r--   0 root         (0) root         (0)    11044 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/SaveForm.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.988000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/css/
--rw-r--r--   0 root         (0) root         (0)     1226 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/css/BookkeepingBrowser.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.988000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/
--rw-r--r--   0 root         (0) root         (0)      833 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/back.png
--rw-r--r--   0 root         (0) root         (0)     2309 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/close.png
--rw-r--r--   0 root         (0) root         (0)      899 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/go.gif
--rw-r--r--   0 root         (0) root         (0)      843 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/next.png
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.968000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.988000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/
--rw-r--r--   0 root         (0) root         (0)    12319 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/BookkeepingSimDescription.js
--rw-r--r--   0 root         (0) root         (0)     4372 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/SimulationEditor.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.988000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/css/BookkeepingSimDescription.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.968000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.992000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/classes/
--rw-r--r--   0 root         (0) root         (0)     5408 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/classes/Downtimes.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.992000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/css/Downtimes.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.968000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.992000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/classes/
--rw-r--r--   0 root         (0) root         (0)     1203 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/classes/JobSummary.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.992000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/css/JobSummary.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.972000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.992000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/classes/
--rwxr-xr-x   0 root         (0) root         (0)     2422 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/classes/LHCbJobMonitor.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.992000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/css/LHCbJobMonitor.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/
--rw-r--r--   0 root         (0) root         (0)      933 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/action.gif
--rw-r--r--   0 root         (0) root         (0)      956 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/addfile.gif
--rw-r--r--   0 root         (0) root         (0)      894 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/bad.gif
--rw-r--r--   0 root         (0) root         (0)      895 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/close.gif
--rw-r--r--   0 root         (0) root         (0)      895 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/delete.gif
--rw-r--r--   0 root         (0) root         (0)      978 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/deleted.gif
--rw-r--r--   0 root         (0) root         (0)      902 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/done.gif
--rw-r--r--   0 root         (0) root         (0)      902 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/failed.gif
--rw-r--r--   0 root         (0) root         (0)      973 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/matched.gif
--rw-r--r--   0 root         (0) root         (0)      977 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/refresh.gif
--rw-r--r--   0 root         (0) root         (0)      977 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reschedule.gif
--rw-r--r--   0 root         (0) root         (0)      967 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reset.gif
--rw-r--r--   0 root         (0) root         (0)      973 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/resetButton.gif
--rw-r--r--   0 root         (0) root         (0)      934 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/running.gif
--rw-r--r--   0 root         (0) root         (0)     1016 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/submit.gif
--rw-r--r--   0 root         (0) root         (0)      902 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/unknown.gif
--rw-r--r--   0 root         (0) root         (0)      902 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/waiting.gif
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.972000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/classes/
--rw-r--r--   0 root         (0) root         (0)     1224 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/classes/LHCbPilotMonitor.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/css/LHCbPilotMonitor.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.972000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/classes/
--rw-r--r--   0 root         (0) root         (0)     1232 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/classes/LHCbPilotSummary.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/css/LHCbPilotSummary.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.972000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/classes/
--rw-r--r--   0 root         (0) root         (0)    39706 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/classes/LHCbStepManager.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/css/LHCbStepManager.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.972000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/classes/
--rw-r--r--   0 root         (0) root         (0)     8932 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/classes/LHCbTransformationMonitor.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.996000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/css/LHCbTransformationMonitor.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.972000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/
--rw-r--r--   0 root         (0) root         (0)     6675 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BkSimCondBrowser.js
--rw-r--r--   0 root         (0) root         (0)     6999 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BookkeepingInputDataBrowser.js
--rw-r--r--   0 root         (0) root         (0)     3999 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ComboBox.js
--rw-r--r--   0 root         (0) root         (0)    19100 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/PrWorkflow.js
--rw-r--r--   0 root         (0) root         (0)     6364 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionManager.js
--rw-r--r--   0 root         (0) root         (0)    54166 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestEditor.js
--rw-r--r--   0 root         (0) root         (0)    68124 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestManager.js
--rw-r--r--   0 root         (0) root         (0)     4799 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestDetail.js
--rw-r--r--   0 root         (0) root         (0)     2443 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestModelWindow.js
--rw-r--r--   0 root         (0) root         (0)     2160 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestPriorityEditor.js
--rw-r--r--   0 root         (0) root         (0)     4915 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestSpliter.js
--rw-r--r--   0 root         (0) root         (0)     3362 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SimpleSubrequestList.js
--rw-r--r--   0 root         (0) root         (0)     7728 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepAdder.js
--rw-r--r--   0 root         (0) root         (0)     2210 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepsView.js
--rw-r--r--   0 root         (0) root         (0)    10090 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestAdder.js
--rw-r--r--   0 root         (0) root         (0)     5791 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestEditor.js
--rw-r--r--   0 root         (0) root         (0)     2713 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubrequestList.js
--rw-r--r--   0 root         (0) root         (0)     1293 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateDetail.js
--rw-r--r--   0 root         (0) root         (0)     1810 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateList.js
--rw-r--r--   0 root         (0) root         (0)     2460 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateParList.js
--rw-r--r--   0 root         (0) root         (0)     1810 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestList.js
--rw-r--r--   0 root         (0) root         (0)     2756 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestStatus.js
--rw-r--r--   0 root         (0) root         (0)     7526 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/Tester.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/css/
--rw-r--r--   0 root         (0) root         (0)     1270 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/css/ProductionRequestManager.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/
--rw-r--r--   0 root         (0) root         (0)      779 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/minus.png
--rw-r--r--   0 root         (0) root         (0)      416 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/plus.png
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.976000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/classes/
--rw-r--r--   0 root         (0) root         (0)    24976 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/classes/RAWIntegrityMonitor.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/css/RAWIntegrityMonitor.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.976000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/classes/
--rw-r--r--   0 root         (0) root         (0)     6036 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/classes/SpaceOccupancy.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.004000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/css/
--rw-r--r--   0 root         (0) root         (0)      800 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/css/SpaceOccupancy.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.976000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:52.008000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/
--rw-r--r--   0 root         (0) root         (0)      926 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/dlogo.gif
--rw-r--r--   0 root         (0) root         (0)   101609 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/lhcb.jpg
--rw-r--r--   0 root         (0) root         (0)     1420 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/web.cfg
--rw-r--r--   0 root         (0) root         (0)     1470 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-24 10:35:51.980000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/
--rw-r--r--   0 root         (0) root         (0)     1264 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     8548 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       51 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)      213 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       13 2023-01-24 10:35:51.000000 LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)    18289 2023-01-24 10:35:30.000000 LHCbWebDIRAC-6.0.1/versions.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/
+-rw-r--r--   0 root         (0) root         (0)      867 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/CONTRIBUTING.md
+-rw-r--r--   0 root         (0) root         (0)    35075 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/LICENSE
+-rw-r--r--   0 root         (0) root         (0)      120 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     1264 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      558 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/README.md
+-rw-r--r--   0 root         (0) root         (0)      528 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)      126 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/pytest.ini
+-rw-r--r--   0 root         (0) root         (0)     1221 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      944 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.100000 LHCbWebDIRAC-6.0.2/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.108000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.112000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.112000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/
+-rw-r--r--   0 root         (0) root         (0)     2690 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appAcounting.tpl
+-rw-r--r--   0 root         (0) root         (0)     1897 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingBrowser.tpl
+-rw-r--r--   0 root         (0) root         (0)     1946 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingSimDescription.tpl
+-rw-r--r--   0 root         (0) root         (0)     1936 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appJobMonitor.tpl
+-rw-r--r--   0 root         (0) root         (0)     1956 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotMonitor.tpl
+-rw-r--r--   0 root         (0) root         (0)     1956 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotSummary.tpl
+-rw-r--r--   0 root         (0) root         (0)     2028 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appTransformationMonitor.tpl
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/
+-rw-r--r--   0 root         (0) root         (0)     1010 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/AccountingHandler.py
+-rw-r--r--   0 root         (0) root         (0)    21210 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/BookkeepingBrowserHandler.py
+-rw-r--r--   0 root         (0) root         (0)     5477 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/BookkeepingSimDescriptionHandler.py
+-rw-r--r--   0 root         (0) root         (0)     4597 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/DowntimesHandler.py
+-rw-r--r--   0 root         (0) root         (0)     1398 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbJobMonitorHandler.py
+-rw-r--r--   0 root         (0) root         (0)     1001 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotMonitorHandler.py
+-rw-r--r--   0 root         (0) root         (0)     1001 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotSummaryHandler.py
+-rw-r--r--   0 root         (0) root         (0)    15403 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbStepManagerHandler.py
+-rw-r--r--   0 root         (0) root         (0)     7077 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbTransformationMonitorHandler.py
+-rw-r--r--   0 root         (0) root         (0)     4076 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/ProductionLib.py
+-rw-r--r--   0 root         (0) root         (0)    36464 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/ProductionRequestManagerHandler.py
+-rw-r--r--   0 root         (0) root         (0)     9176 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/RAWIntegrityMonitorHandler.py
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.100000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.100000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/classes/
+-rw-r--r--   0 root         (0) root         (0)     4132 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/classes/Accounting.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/css/Accounting.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.100000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/
+-rw-r--r--   0 root         (0) root         (0)     4027 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/AdvancedSaveWindow.js
+-rw-r--r--   0 root         (0) root         (0)     4148 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingAddBookmarks.js
+-rw-r--r--   0 root         (0) root         (0)    37255 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingBrowser.js
+-rw-r--r--   0 root         (0) root         (0)     1011 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingTreeItemModel.js
+-rw-r--r--   0 root         (0) root         (0)     9383 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/FileHistoryPanel.js
+-rw-r--r--   0 root         (0) root         (0)     2835 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/LookupWindow.js
+-rw-r--r--   0 root         (0) root         (0)     3705 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/ProcessingPassViewer.js
+-rw-r--r--   0 root         (0) root         (0)    11044 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/SaveForm.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/css/
+-rw-r--r--   0 root         (0) root         (0)     1226 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/css/BookkeepingBrowser.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/
+-rw-r--r--   0 root         (0) root         (0)      833 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/back.png
+-rw-r--r--   0 root         (0) root         (0)     2309 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/close.png
+-rw-r--r--   0 root         (0) root         (0)      899 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/go.gif
+-rw-r--r--   0 root         (0) root         (0)      843 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/next.png
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.100000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/
+-rw-r--r--   0 root         (0) root         (0)    12319 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/BookkeepingSimDescription.js
+-rw-r--r--   0 root         (0) root         (0)     4372 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/SimulationEditor.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/css/BookkeepingSimDescription.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/classes/
+-rw-r--r--   0 root         (0) root         (0)     5408 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/classes/Downtimes.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/css/Downtimes.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/classes/
+-rw-r--r--   0 root         (0) root         (0)     1203 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/classes/JobSummary.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/css/JobSummary.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.116000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/classes/
+-rwxr-xr-x   0 root         (0) root         (0)     2422 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/classes/LHCbJobMonitor.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/css/LHCbJobMonitor.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/
+-rw-r--r--   0 root         (0) root         (0)      933 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/action.gif
+-rw-r--r--   0 root         (0) root         (0)      956 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/addfile.gif
+-rw-r--r--   0 root         (0) root         (0)      894 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/bad.gif
+-rw-r--r--   0 root         (0) root         (0)      895 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/close.gif
+-rw-r--r--   0 root         (0) root         (0)      895 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/delete.gif
+-rw-r--r--   0 root         (0) root         (0)      978 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/deleted.gif
+-rw-r--r--   0 root         (0) root         (0)      902 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/done.gif
+-rw-r--r--   0 root         (0) root         (0)      902 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/failed.gif
+-rw-r--r--   0 root         (0) root         (0)      973 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/matched.gif
+-rw-r--r--   0 root         (0) root         (0)      977 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/refresh.gif
+-rw-r--r--   0 root         (0) root         (0)      977 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reschedule.gif
+-rw-r--r--   0 root         (0) root         (0)      967 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reset.gif
+-rw-r--r--   0 root         (0) root         (0)      973 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/resetButton.gif
+-rw-r--r--   0 root         (0) root         (0)      934 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/running.gif
+-rw-r--r--   0 root         (0) root         (0)     1016 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/submit.gif
+-rw-r--r--   0 root         (0) root         (0)      902 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/unknown.gif
+-rw-r--r--   0 root         (0) root         (0)      902 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/waiting.gif
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/classes/
+-rw-r--r--   0 root         (0) root         (0)     1224 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/classes/LHCbPilotMonitor.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/css/LHCbPilotMonitor.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/classes/
+-rw-r--r--   0 root         (0) root         (0)     1232 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/classes/LHCbPilotSummary.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/css/LHCbPilotSummary.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/classes/
+-rw-r--r--   0 root         (0) root         (0)    39706 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/classes/LHCbStepManager.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/css/LHCbStepManager.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/classes/
+-rw-r--r--   0 root         (0) root         (0)     8932 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/classes/LHCbTransformationMonitor.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.120000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/css/LHCbTransformationMonitor.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.124000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/
+-rw-r--r--   0 root         (0) root         (0)     6675 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BkSimCondBrowser.js
+-rw-r--r--   0 root         (0) root         (0)     6999 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BookkeepingInputDataBrowser.js
+-rw-r--r--   0 root         (0) root         (0)     3999 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ComboBox.js
+-rw-r--r--   0 root         (0) root         (0)    19100 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/PrWorkflow.js
+-rw-r--r--   0 root         (0) root         (0)     6364 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionManager.js
+-rw-r--r--   0 root         (0) root         (0)    54166 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestEditor.js
+-rw-r--r--   0 root         (0) root         (0)    68125 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestManager.js
+-rw-r--r--   0 root         (0) root         (0)     4799 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestDetail.js
+-rw-r--r--   0 root         (0) root         (0)     2443 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestModelWindow.js
+-rw-r--r--   0 root         (0) root         (0)     2160 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestPriorityEditor.js
+-rw-r--r--   0 root         (0) root         (0)     4915 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestSpliter.js
+-rw-r--r--   0 root         (0) root         (0)     3362 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SimpleSubrequestList.js
+-rw-r--r--   0 root         (0) root         (0)     7728 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepAdder.js
+-rw-r--r--   0 root         (0) root         (0)     2210 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepsView.js
+-rw-r--r--   0 root         (0) root         (0)    10090 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestAdder.js
+-rw-r--r--   0 root         (0) root         (0)     5791 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestEditor.js
+-rw-r--r--   0 root         (0) root         (0)     2713 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubrequestList.js
+-rw-r--r--   0 root         (0) root         (0)     1293 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateDetail.js
+-rw-r--r--   0 root         (0) root         (0)     1810 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateList.js
+-rw-r--r--   0 root         (0) root         (0)     2460 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateParList.js
+-rw-r--r--   0 root         (0) root         (0)     1810 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestList.js
+-rw-r--r--   0 root         (0) root         (0)     2756 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestStatus.js
+-rw-r--r--   0 root         (0) root         (0)     7526 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/Tester.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.124000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/css/
+-rw-r--r--   0 root         (0) root         (0)     1270 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/css/ProductionRequestManager.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/
+-rw-r--r--   0 root         (0) root         (0)      779 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/minus.png
+-rw-r--r--   0 root         (0) root         (0)      416 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/plus.png
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/classes/
+-rw-r--r--   0 root         (0) root         (0)    24976 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/classes/RAWIntegrityMonitor.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/css/RAWIntegrityMonitor.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/classes/
+-rw-r--r--   0 root         (0) root         (0)     6036 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/classes/SpaceOccupancy.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/css/
+-rw-r--r--   0 root         (0) root         (0)      800 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/css/SpaceOccupancy.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.104000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.128000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/
+-rw-r--r--   0 root         (0) root         (0)      926 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/dlogo.gif
+-rw-r--r--   0 root         (0) root         (0)   101609 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/lhcb.jpg
+-rw-r--r--   0 root         (0) root         (0)     1420 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/web.cfg
+-rw-r--r--   0 root         (0) root         (0)     1470 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 13:15:00.108000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     1264 2023-06-28 13:15:00.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     8548 2023-06-28 13:15:00.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 13:15:00.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       51 2023-06-28 13:15:00.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 13:14:59.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)      213 2023-06-28 13:15:00.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 13:15:00.000000 LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)    18289 2023-06-28 13:14:45.000000 LHCbWebDIRAC-6.0.2/versions.cfg
```

### Comparing `LHCbWebDIRAC-6.0.1/CONTRIBUTING.md` & `LHCbWebDIRAC-6.0.2/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/LICENSE` & `LHCbWebDIRAC-6.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/PKG-INFO` & `LHCbWebDIRAC-6.0.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: LHCbWebDIRAC
-Version: 6.0.1
+Version: 6.0.2
 Summary: LHCbWebDIRAC is a portal for the DIRAC software.
 Home-page: https://gitlab.cern.ch/lhcb-dirac/LHCbWebDIRAC/
 License: GPL-3.0-only
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
```

### Comparing `LHCbWebDIRAC-6.0.1/README.md` & `LHCbWebDIRAC-6.0.2/README.md`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/pyproject.toml` & `LHCbWebDIRAC-6.0.2/pyproject.toml`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/setup.cfg` & `LHCbWebDIRAC-6.0.2/setup.cfg`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/setup.py` & `LHCbWebDIRAC-6.0.2/setup.py`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appAcounting.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appAcounting.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingBrowser.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingBrowser.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingSimDescription.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appBookkeepingSimDescription.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appJobMonitor.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appJobMonitor.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotMonitor.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotMonitor.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotSummary.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appPilotSummary.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appTransformationMonitor.tpl` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/CompileTeplates/lhcb_appTransformationMonitor.tpl`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/__init__.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/__init__.py`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/AccountingHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/AccountingHandler.py`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/BookkeepingBrowserHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/BookkeepingBrowserHandler.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,25 +26,23 @@
 from LHCbDIRAC.BookkeepingSystem.Client.LHCB_BKKDBClient import LHCB_BKKDBClient
 from LHCbDIRAC.BookkeepingSystem.Client.BookkeepingClient import BookkeepingClient
 
 from WebAppDIRAC.Lib.WebHandler import WebHandler, WErr
 
 
 class BookkeepingBrowserHandler(WebHandler):
-
     AUTH_PROPS = "authenticated"
 
     numberOfJobs = None
     pageNumber = None
 
     def index(self):
         pass
 
     def web_getNodes(self):
-
         _, querytype, tree, dataQuality = self.__parseRequest()
         node = self.get_argument("node", "")
 
         bk = LHCB_BKKDBClient()
 
         bk.setFileTypes([])
 
@@ -89,15 +87,14 @@
                 checked = True if i == "OK" else False
                 ret += [{"name": i, "value": checked}]
             return {"success": "true", "result": ret}
         else:
             return {"result": [], "error": result["Message"]}
 
     def web_getFiles(self):
-
         path, querytype, tree, dataQuality = self.__parseRequest()
 
         bk = LHCB_BKKDBClient()
 
         bk.setAdvancedQueries(querytype)
         bk.setParameter(tree)
         bk.setDataQualities(dataQuality)
@@ -178,15 +175,14 @@
 
         self.numberOfJobs = int(self.get_argument("limit", "25"))
         self.pageNumber = int(self.get_argument("start", "0"))
 
         return path, querytype, tree, dataQuality
 
     def web_getStatistics(self):
-
         path, querytype, tree, dataQuality = self.__parseRequest()
 
         bk = LHCB_BKKDBClient()
 
         bk.setAdvancedQueries(querytype)
         bk.setParameter(tree)
         bk.setDataQualities(dataQuality)
@@ -211,15 +207,14 @@
         finalList = []
         for i in newList:
             finalList.append(str("".join(i)))
         finalList = " ".join(map(str, finalList))
         return finalList
 
     def web_saveDataSet(self):
-
         path, querytype, tree, dataQuality = self.__parseRequest()
 
         bk = LHCB_BKKDBClient()
 
         bk.setAdvancedQueries(querytype)
         bk.setParameter(tree)
         bk.setDataQualities(dataQuality)
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/BookkeepingSimDescriptionHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/BookkeepingSimDescriptionHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -15,26 +15,24 @@
 
 from DIRAC import gLogger
 from LHCbDIRAC.BookkeepingSystem.Client.BookkeepingClient import BookkeepingClient
 from WebAppDIRAC.Lib.WebHandler import WebHandler
 
 
 class BookkeepingSimDescriptionHandler(WebHandler):
-
     AUTH_PROPS = "authenticated"
 
     def index(self):
         pass
 
     def web_getSelectionData(self):
         data = {"Visible": ["Y", "N"]}
         return data
 
     def web_getData(self):
-
         filter = {}
         limit = 0
         dir = "DESC"
         sort = "SimId"
         data = None
 
         try:
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/DowntimesHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/DowntimesHandler.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,40 +17,35 @@
 import tornado
 from DIRAC import gLogger
 from DIRAC.ResourceStatusSystem.Client.PublisherClient import PublisherClient
 from WebAppDIRAC.Lib.WebHandler import WebHandler, WErr
 
 
 class DowntimesHandler(WebHandler):
-
     AUTH_PROPS = "authenticated"
 
     def web_getSelectionData(self):
         callback = {"name": set(), "severity": set(), "sites": set()}
 
         gLogger.info("Arguments to web_getSelectionData", repr(self.request.arguments))
 
         downtimes = PublisherClient().getCachedDowntimes(None, None, None, None)
 
         if downtimes["OK"]:
-
             dtList = [dict(zip(downtimes["Columns"], dt)) for dt in downtimes["Value"]]
 
             for dt in dtList:
-
                 callback["name"].add(dt["Name"])
                 callback["severity"].add(dt["Severity"])
 
         sites = PublisherClient().getSites()
         if sites["OK"]:
-
             callback["site"] = sites["Value"]
 
         for key, value in callback.items():
-
             callback[key] = [[item] for item in list(value)]
             # callback[key].sort()
             callback[key] = [["All"]] + callback[key]
 
         callback["view"] = [["tabular"], ["availability"]]
 
         return callback
@@ -65,31 +60,28 @@
         if not retVal["OK"]:
             raise WErr.fromSERROR(retVal)
         else:
             sitesResources = retVal["Value"]
 
         names = []
         if requestParams["site"]:
-
             if names is None:
                 names = []
 
             for _site, resources in sitesResources.items():
-
                 names += resources["ces"]
                 names += resources["ses"]
 
         downtimes = PublisherClient().getCachedDowntimes(None, None, names, list(requestParams["severity"]))
         if not downtimes["OK"]:
             raise WErr.fromSERROR(downtimes)
 
         dtList = [dict(zip(downtimes["Columns"], dt)) for dt in downtimes["Value"]]
 
         for dt in dtList:
-
             dt["Site"] = "Unknown"
 
             for site, resources in sitesResources.items():
                 if dt["Name"] in resources["ces"] + resources["ses"]:
                     dt["Site"] = site
                     break
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbJobMonitorHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbJobMonitorHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -11,15 +11,14 @@
 import json
 
 from WebAppDIRAC.WebApp.handler.JobMonitorHandler import JobMonitorHandler
 from WebAppDIRAC.Lib.SessionData import SessionData
 
 
 class LHCbJobMonitorHandler(JobMonitorHandler):
-
     AUTH_PROPS = "authenticated"
 
     def index(self):
         pass
 
     def web_standalone(self):
         self.render("JobMonitor/standalone.tpl", config_data=json.dumps(SessionData(None, None).getData()))
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotMonitorHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotMonitorHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -8,12 +8,11 @@
 # granted to it by virtue of its status as an Intergovernmental Organization  #
 # or submit itself to any jurisdiction.                                       #
 ###############################################################################
 from WebAppDIRAC.WebApp.handler.PilotMonitorHandler import PilotMonitorHandler
 
 
 class LHCbPilotMonitorHandler(PilotMonitorHandler):
-
     AUTH_PROPS = "authenticated"
 
     def index(self):
         pass
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotSummaryHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbPilotSummaryHandler.py`

 * *Files 1% similar despite different names*

```diff
@@ -8,12 +8,11 @@
 # granted to it by virtue of its status as an Intergovernmental Organization  #
 # or submit itself to any jurisdiction.                                       #
 ###############################################################################
 from WebAppDIRAC.WebApp.handler.PilotSummaryHandler import PilotSummaryHandler
 
 
 class LHCbPilotSummaryHandler(PilotSummaryHandler):
-
     AUTH_PROPS = "authenticated"
 
     def index(self):
         pass
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbStepManagerHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbStepManagerHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -57,15 +57,14 @@
     # Sort the result, newer version will be first
     allversions = list(sorted(allversions, reverse=True))
     gLogger.debug("Application versions", allversions)
     return S_OK(allversions)
 
 
 class LHCbStepManagerHandler(WebHandler):
-
     AUTH_PROPS = "authenticated"
 
     def __getArgument(self, argName, argDefValue):
         return self.get_argument(argName, None) or argDefValue
 
     def __getJsonArgument(self, argName, argDefValue):
         x = self.get_argument(argName, None)
@@ -119,15 +118,14 @@
 
     def __getFilter(self):
         visibleMap = {"Yes": "Y", "No": "N"}
         sfilter = {}
 
         # Selector
         try:
-
             for selFieldName in [
                 "ApplicationName",
                 "ApplicationVersion",
                 "Visible",
                 "Usable",
                 "ProcessingPass",
                 "StartDate",
@@ -256,15 +254,14 @@
             return {"success": "false", "result": [], "error": "Can not convert File Types: %s" % str(e)}
         self.__runtimeProjectsConvert(step)
         self.__nullConvert(step)
 
         return {"success": "true", "result": step}
 
     def web_getRuntimeProjects(self):
-
         result = BookkeepingClient().getAvailableSteps({})
         if not result["OK"]:
             return {"success": "false", "result": [], "error": result["Message"]}
             return
 
         fields = result["Value"]["ParameterNames"]
         rows = [dict(zip(fields, x)) for x in result["Value"]["Records"]]
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/LHCbTransformationMonitorHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/LHCbTransformationMonitorHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -17,15 +17,14 @@
 
 from WebAppDIRAC.WebApp.handler.TransformationMonitorHandler import TransformationMonitorHandler
 from WebAppDIRAC.Lib.WebHandler import WErr
 from WebAppDIRAC.Lib.SessionData import SessionData
 
 
 class LHCbTransformationMonitorHandler(TransformationMonitorHandler):
-
     AUTH_PROPS = "authenticated"
 
     def index(self):
         pass
 
     def web_standalone(self):
         self.render(
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/ProductionLib.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/ProductionLib.py`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/ProductionRequestManagerHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/ProductionRequestManagerHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -23,15 +23,14 @@
 from LHCbDIRAC.BookkeepingSystem.Client.BookkeepingClient import BookkeepingClient
 from LHCbDIRAC.ProductionManagementSystem.Client.ProductionRequestClient import ProductionRequestClient
 from LHCbWebDIRAC.WebApp.handler.ProductionLib import SelectAndSort, PrTpl
 from LHCbDIRAC.BookkeepingSystem.Client.LHCB_BKKDBClient import LHCB_BKKDBClient
 
 
 class ProductionRequestManagerHandler(WebHandler):
-
     AUTH_PROPS = "authenticated"
 
     __dataCache = DictCache.DictCache()
 
     serviceFields = [
         "RequestID",
         "HasSubrequest",
@@ -735,15 +734,14 @@
                 ("typeF", "RequestType"),
                 ("stateF", "RequestState"),
                 ("authorF", "RequestAuthor"),
                 ("idF", "RequestID"),
                 ("modF", "IsModel"),
                 ("wgF", "RequestWG"),
             ]:
-
                 val = self.get_argument(x, "")
 
                 if val != "":
                     val = list(json.loads(val))
                     if val:
                         if not isinstance(val[0], bool):
                             filterOpts[y] = ",".join(val)
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/RAWIntegrityMonitorHandler.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/RAWIntegrityMonitorHandler.py`

 * *Files 0% similar despite different names*

```diff
@@ -16,15 +16,14 @@
 from DIRAC.Core.Utilities.Graphs.Palette import Palette
 from DIRAC.Core.DISET.RPCClient import RPCClient
 
 from WebAppDIRAC.Lib.WebHandler import WebHandler
 
 
 class RAWIntegrityMonitorHandler(WebHandler):
-
     AUTH_PROPS = "authenticated"
 
     numberOfFiles = 25
     pageNumber = 0
     globalSort = [["SubmitTime", "DESC"]]
 
     def index(self):
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/handler/__init__.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/handler/__init__.py`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/classes/Accounting.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/classes/Accounting.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/css/Accounting.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Accounting/css/Accounting.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/AdvancedSaveWindow.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/AdvancedSaveWindow.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingAddBookmarks.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingAddBookmarks.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingBrowser.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingBrowser.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingTreeItemModel.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/BookkeepingTreeItemModel.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/FileHistoryPanel.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/FileHistoryPanel.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/LookupWindow.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/LookupWindow.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/ProcessingPassViewer.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/ProcessingPassViewer.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/SaveForm.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/classes/SaveForm.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/css/BookkeepingBrowser.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/css/BookkeepingBrowser.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/back.png` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/back.png`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/close.png` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/close.png`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/go.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/go.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/next.png` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingBrowser/images/next.png`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/BookkeepingSimDescription.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/BookkeepingSimDescription.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/SimulationEditor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/classes/SimulationEditor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/css/BookkeepingSimDescription.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/BookkeepingSimDescription/css/BookkeepingSimDescription.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/classes/Downtimes.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/classes/Downtimes.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/css/Downtimes.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/Downtimes/css/Downtimes.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/classes/JobSummary.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/classes/JobSummary.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/css/JobSummary.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/JobSummary/css/JobSummary.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/classes/LHCbJobMonitor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/classes/LHCbJobMonitor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/css/LHCbJobMonitor.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/css/LHCbJobMonitor.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/action.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/action.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/addfile.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/addfile.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/bad.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/bad.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/close.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/close.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/delete.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/delete.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/deleted.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/deleted.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/done.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/done.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/failed.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/failed.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/matched.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/matched.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/refresh.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/refresh.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reschedule.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reschedule.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reset.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/reset.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/resetButton.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/resetButton.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/running.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/running.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/submit.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/submit.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/unknown.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/unknown.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/waiting.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbJobMonitor/images/waiting.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/classes/LHCbPilotMonitor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/classes/LHCbPilotMonitor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/css/LHCbPilotMonitor.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotMonitor/css/LHCbPilotMonitor.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/classes/LHCbPilotSummary.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/classes/LHCbPilotSummary.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/css/LHCbPilotSummary.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbPilotSummary/css/LHCbPilotSummary.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/classes/LHCbStepManager.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/classes/LHCbStepManager.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/css/LHCbStepManager.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbStepManager/css/LHCbStepManager.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/classes/LHCbTransformationMonitor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/classes/LHCbTransformationMonitor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/css/LHCbTransformationMonitor.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/LHCbTransformationMonitor/css/LHCbTransformationMonitor.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BkSimCondBrowser.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BkSimCondBrowser.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BookkeepingInputDataBrowser.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/BookkeepingInputDataBrowser.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ComboBox.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ComboBox.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/PrWorkflow.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/PrWorkflow.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionManager.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionManager.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestEditor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestEditor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestManager.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/ProductionRequestManager.js`

 * *Files 0% similar despite different names*

#### js-beautify {}

```diff
@@ -773,14 +773,19 @@
                         dataIndex: "reqState",
                     }, {
                         header: "Priority",
                         sortable: true,
                         dataIndex: "reqPrio",
                         width: 50,
                     }, {
+                        header: "WG",
+                        dataIndex: "reqWG",
+                        hidden: false,
+                        sortable: true,
+                    }, {
                         header: "Name",
                         sortable: true,
                         dataIndex: "reqName",
                     }, {
                         header: "Sim/Run conditions",
                         sortable: true,
                         dataIndex: "simDesc",
@@ -820,19 +825,14 @@
                         hidden: true,
                     }, {
                         header: "Author",
                         dataIndex: "reqAuthor",
                         hidden: true,
                         sortable: true,
                     }, {
-                        header: "WG",
-                        dataIndex: "reqWG",
-                        hidden: true,
-                        sortable: true,
-                    }, {
                         header: "Event type name",
                         dataIndex: "eventText",
                         hidden: true,
                     }, {
                         header: "Test",
                         dataIndex: "TestState",
                         hidden: true,
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestDetail.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestDetail.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestModelWindow.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestModelWindow.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestPriorityEditor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestPriorityEditor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestSpliter.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/RequestSpliter.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SimpleSubrequestList.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SimpleSubrequestList.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepAdder.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepAdder.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepsView.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/StepsView.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestAdder.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestAdder.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestEditor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubRequestEditor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubrequestList.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/SubrequestList.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateDetail.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateDetail.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateList.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateList.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateParList.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TemplateParList.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestList.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestList.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestStatus.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/TestStatus.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/Tester.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/classes/Tester.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/css/ProductionRequestManager.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/css/ProductionRequestManager.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/minus.png` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/ProductionRequestManager/images/minus.png`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/classes/RAWIntegrityMonitor.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/classes/RAWIntegrityMonitor.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/css/RAWIntegrityMonitor.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/RAWIntegrityMonitor/css/RAWIntegrityMonitor.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/classes/SpaceOccupancy.js` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/classes/SpaceOccupancy.js`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/css/SpaceOccupancy.css` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/SpaceOccupancy/css/SpaceOccupancy.css`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/dlogo.gif` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/dlogo.gif`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/lhcb.jpg` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/static/LHCbDIRAC/img/icons/lhcb.jpg`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/WebApp/web.cfg` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/WebApp/web.cfg`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC/__init__.py` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC/__init__.py`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/PKG-INFO` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: LHCbWebDIRAC
-Version: 6.0.1
+Version: 6.0.2
 Summary: LHCbWebDIRAC is a portal for the DIRAC software.
 Home-page: https://gitlab.cern.ch/lhcb-dirac/LHCbWebDIRAC/
 License: GPL-3.0-only
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
```

### Comparing `LHCbWebDIRAC-6.0.1/src/LHCbWebDIRAC.egg-info/SOURCES.txt` & `LHCbWebDIRAC-6.0.2/src/LHCbWebDIRAC.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `LHCbWebDIRAC-6.0.1/versions.cfg` & `LHCbWebDIRAC-6.0.2/versions.cfg`

 * *Files identical despite different names*


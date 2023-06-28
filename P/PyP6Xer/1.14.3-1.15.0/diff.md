# Comparing `tmp/PyP6Xer-1.14.3.tar.gz` & `tmp/PyP6Xer-1.15.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyP6Xer-1.14.3.tar", last modified: Thu Sep 29 15:49:30 2022, max compression
+gzip compressed data, was "PyP6Xer-1.15.0.tar", last modified: Wed Jun 28 11:12:14 2023, max compression
```

## Comparing `PyP6Xer-1.14.3.tar` & `PyP6Xer-1.15.0.tar`

### file list

```diff
@@ -1,83 +1,83 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:30.189230 PyP6Xer-1.14.3/
--rw-r--r--   0 runner    (1001) docker     (121)    26526 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)      951 2022-09-29 15:49:30.189230 PyP6Xer-1.14.3/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:30.181230 PyP6Xer-1.14.3/PyP6Xer.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)      951 2022-09-29 15:49:30.000000 PyP6Xer-1.14.3/PyP6Xer.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     2295 2022-09-29 15:49:30.000000 PyP6Xer-1.14.3/PyP6Xer.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-09-29 15:49:30.000000 PyP6Xer-1.14.3/PyP6Xer.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       10 2022-09-29 15:49:30.000000 PyP6Xer-1.14.3/PyP6Xer.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)      693 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/README.md
--rw-r--r--   0 runner    (1001) docker     (121)       38 2022-09-29 15:49:30.189230 PyP6Xer-1.14.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)      534 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:30.181230 PyP6Xer-1.14.3/xerparser/
--rw-r--r--   0 runner    (1001) docker     (121)     3650 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:30.181230 PyP6Xer-1.14.3/xerparser/dcma14/
--rw-r--r--   0 runner    (1001) docker     (121)       44 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/dcma14/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    11587 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/dcma14/analysis.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:30.185230 PyP6Xer-1.14.3/xerparser/model/
--rw-r--r--   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     1702 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/accounts.py
--rw-r--r--   0 runner    (1001) docker     (121)     3134 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/activitiyresources.py
--rw-r--r--   0 runner    (1001) docker     (121)     2193 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/activitycodes.py
--rw-r--r--   0 runner    (1001) docker     (121)     2017 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/acttypes.py
--rw-r--r--   0 runner    (1001) docker     (121)     2101 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/calendars.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:30.189230 PyP6Xer-1.14.3/xerparser/model/classes/
--rw-r--r--   0 runner    (1001) docker     (121)        0 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     1886 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/account.py
--rw-r--r--   0 runner    (1001) docker     (121)     3909 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/activitycode.py
--rw-r--r--   0 runner    (1001) docker     (121)     2884 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/acttype.py
--rw-r--r--   0 runner    (1001) docker     (121)     4528 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/calendar.py
--rw-r--r--   0 runner    (1001) docker     (121)     3660 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/calendar_data.py
--rw-r--r--   0 runner    (1001) docker     (121)     3240 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/currency.py
--rw-r--r--   0 runner    (1001) docker     (121)      223 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/data.py
--rw-r--r--   0 runner    (1001) docker     (121)     1381 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/fintmpl.py
--rw-r--r--   0 runner    (1001) docker     (121)     1521 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/nonwork.py
--rw-r--r--   0 runner    (1001) docker     (121)     2943 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/obs.py
--rw-r--r--   0 runner    (1001) docker     (121)     1319 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/p6codes.py
--rw-r--r--   0 runner    (1001) docker     (121)     2705 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/pcattype.py
--rw-r--r--   0 runner    (1001) docker     (121)     1958 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/pcatval.py
--rw-r--r--   0 runner    (1001) docker     (121)     1422 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/projcat.py
--rw-r--r--   0 runner    (1001) docker     (121)    11156 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/project.py
--rw-r--r--   0 runner    (1001) docker     (121)     1799 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rcattype.py
--rw-r--r--   0 runner    (1001) docker     (121)     1957 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rcatval.py
--rw-r--r--   0 runner    (1001) docker     (121)     2165 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/role.py
--rw-r--r--   0 runner    (1001) docker     (121)     2335 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rolerate.py
--rw-r--r--   0 runner    (1001) docker     (121)     5244 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rsrc.py
--rw-r--r--   0 runner    (1001) docker     (121)     4197 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rsrccurv.py
--rw-r--r--   0 runner    (1001) docker     (121)     2778 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rsrcrate.py
--rw-r--r--   0 runner    (1001) docker     (121)     1502 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/rsrcrcat.py
--rw-r--r--   0 runner    (1001) docker     (121)     5509 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/schedoption.py
--rw-r--r--   0 runner    (1001) docker     (121)    23961 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/task.py
--rw-r--r--   0 runner    (1001) docker     (121)     1717 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/taskactv.py
--rw-r--r--   0 runner    (1001) docker     (121)     2367 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/taskpred.py
--rw-r--r--   0 runner    (1001) docker     (121)     2019 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/taskproc.py
--rw-r--r--   0 runner    (1001) docker     (121)     7385 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/taskrsrc.py
--rw-r--r--   0 runner    (1001) docker     (121)     2635 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/udftype.py
--rw-r--r--   0 runner    (1001) docker     (121)     2084 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/udfvalue.py
--rw-r--r--   0 runner    (1001) docker     (121)     4804 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/classes/wbs.py
--rw-r--r--   0 runner    (1001) docker     (121)     2098 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/currencies.py
--rw-r--r--   0 runner    (1001) docker     (121)     1881 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/fintmpls.py
--rw-r--r--   0 runner    (1001) docker     (121)     1895 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/nonworks.py
--rw-r--r--   0 runner    (1001) docker     (121)     1881 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/obss.py
--rw-r--r--   0 runner    (1001) docker     (121)     1952 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/pacttypes.py
--rw-r--r--   0 runner    (1001) docker     (121)     1947 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/pcatvals.py
--rw-r--r--   0 runner    (1001) docker     (121)     2749 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/predecessors.py
--rw-r--r--   0 runner    (1001) docker     (121)     1878 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/projcats.py
--rw-r--r--   0 runner    (1001) docker     (121)     3512 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/projects.py
--rw-r--r--   0 runner    (1001) docker     (121)     1956 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/rcattypes.py
--rw-r--r--   0 runner    (1001) docker     (121)     1975 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/rcatvals.py
--rw-r--r--   0 runner    (1001) docker     (121)     3744 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/resources.py
--rw-r--r--   0 runner    (1001) docker     (121)     1988 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/rolerates.py
--rw-r--r--   0 runner    (1001) docker     (121)     1990 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/roles.py
--rw-r--r--   0 runner    (1001) docker     (121)     1881 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/rsrccats.py
--rw-r--r--   0 runner    (1001) docker     (121)     2355 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/rsrccurves.py
--rw-r--r--   0 runner    (1001) docker     (121)     2039 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/rsrcrates.py
--rw-r--r--   0 runner    (1001) docker     (121)     2701 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/schedoptions.py
--rw-r--r--   0 runner    (1001) docker     (121)     2091 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/taskactvs.py
--rw-r--r--   0 runner    (1001) docker     (121)     2121 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/taskprocs.py
--rw-r--r--   0 runner    (1001) docker     (121)     7236 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/tasks.py
--rw-r--r--   0 runner    (1001) docker     (121)     2020 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/udftypes.py
--rw-r--r--   0 runner    (1001) docker     (121)     1967 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/udfvalues.py
--rw-r--r--   0 runner    (1001) docker     (121)     2165 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/model/wbss.py
--rw-r--r--   0 runner    (1001) docker     (121)    10519 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/reader.py
--rw-r--r--   0 runner    (1001) docker     (121)     2435 2022-09-29 15:49:18.000000 PyP6Xer-1.14.3/xerparser/write.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:12:14.204241 PyP6Xer-1.15.0/
+-rw-rw-rw-   0        0        0    27030 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/LICENSE
+-rw-rw-rw-   0        0        0      989 2023-06-28 11:12:14.203269 PyP6Xer-1.15.0/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 11:12:14.104325 PyP6Xer-1.15.0/PyP6Xer.egg-info/
+-rw-rw-rw-   0        0        0      989 2023-06-28 11:12:14.000000 PyP6Xer-1.15.0/PyP6Xer.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     2295 2023-06-28 11:12:14.000000 PyP6Xer-1.15.0/PyP6Xer.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:12:14.000000 PyP6Xer-1.15.0/PyP6Xer.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       10 2023-06-28 11:12:14.000000 PyP6Xer-1.15.0/PyP6Xer.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      720 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 11:12:14.204241 PyP6Xer-1.15.0/setup.cfg
+-rw-rw-rw-   0        0        0      555 2023-06-28 11:08:40.000000 PyP6Xer-1.15.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:12:14.107836 PyP6Xer-1.15.0/xerparser/
+-rw-rw-rw-   0        0        0     3726 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:12:14.110839 PyP6Xer-1.15.0/xerparser/dcma14/
+-rw-rw-rw-   0        0        0       44 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/dcma14/__init__.py
+-rw-rw-rw-   0        0        0    11801 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/dcma14/analysis.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:12:14.153167 PyP6Xer-1.15.0/xerparser/model/
+-rw-rw-rw-   0        0        0        0 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/__init__.py
+-rw-rw-rw-   0        0        0     1754 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/accounts.py
+-rw-rw-rw-   0        0        0     3214 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/activitiyresources.py
+-rw-rw-rw-   0        0        0     2260 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/activitycodes.py
+-rw-rw-rw-   0        0        0     2080 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/acttypes.py
+-rw-rw-rw-   0        0        0     2167 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/calendars.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:12:14.201336 PyP6Xer-1.15.0/xerparser/model/classes/
+-rw-rw-rw-   0        0        0        0 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/__init__.py
+-rw-rw-rw-   0        0        0     1929 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/account.py
+-rw-rw-rw-   0        0        0     3998 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/activitycode.py
+-rw-rw-rw-   0        0        0     2951 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/acttype.py
+-rw-rw-rw-   0        0        0     4613 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/calendar.py
+-rw-rw-rw-   0        0        0     3761 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/calendar_data.py
+-rw-rw-rw-   0        0        0     3304 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/currency.py
+-rw-rw-rw-   0        0        0      267 2023-06-28 10:53:16.000000 PyP6Xer-1.15.0/xerparser/model/classes/data.py
+-rw-rw-rw-   0        0        0     1418 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/fintmpl.py
+-rw-rw-rw-   0        0        0     1559 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/nonwork.py
+-rw-rw-rw-   0        0        0     3019 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/obs.py
+-rw-rw-rw-   0        0        0     1368 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/p6codes.py
+-rw-rw-rw-   0        0        0     2772 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/pcattype.py
+-rw-rw-rw-   0        0        0     2001 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/pcatval.py
+-rw-rw-rw-   0        0        0     1459 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/projcat.py
+-rw-rw-rw-   0        0        0    11290 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/project.py
+-rw-rw-rw-   0        0        0     1844 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rcattype.py
+-rw-rw-rw-   0        0        0     2003 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rcatval.py
+-rw-rw-rw-   0        0        0     2209 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/role.py
+-rw-rw-rw-   0        0        0     2390 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rolerate.py
+-rw-rw-rw-   0        0        0     5335 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rsrc.py
+-rw-rw-rw-   0        0        0     4263 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rsrccurv.py
+-rw-rw-rw-   0        0        0     2843 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rsrcrate.py
+-rw-rw-rw-   0        0        0     1539 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/rsrcrcat.py
+-rw-rw-rw-   0        0        0     5577 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/schedoption.py
+-rw-rw-rw-   0        0        0    24308 2023-06-28 10:54:29.000000 PyP6Xer-1.15.0/xerparser/model/classes/task.py
+-rw-rw-rw-   0        0        0     1759 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/taskactv.py
+-rw-rw-rw-   0        0        0     2412 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/taskpred.py
+-rw-rw-rw-   0        0        0     2063 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/taskproc.py
+-rw-rw-rw-   0        0        0     7480 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/taskrsrc.py
+-rw-rw-rw-   0        0        0     2690 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/udftype.py
+-rw-rw-rw-   0        0        0     2135 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/udfvalue.py
+-rw-rw-rw-   0        0        0     4912 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/classes/wbs.py
+-rw-rw-rw-   0        0        0     2163 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/currencies.py
+-rw-rw-rw-   0        0        0     1944 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/fintmpls.py
+-rw-rw-rw-   0        0        0     1958 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/nonworks.py
+-rw-rw-rw-   0        0        0     1945 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/obss.py
+-rw-rw-rw-   0        0        0     2014 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/pacttypes.py
+-rw-rw-rw-   0        0        0     2010 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/pcatvals.py
+-rw-rw-rw-   0        0        0     2837 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/predecessors.py
+-rw-rw-rw-   0        0        0     1940 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/projcats.py
+-rw-rw-rw-   0        0        0     3589 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/projects.py
+-rw-rw-rw-   0        0        0     2020 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/rcattypes.py
+-rw-rw-rw-   0        0        0     2040 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/rcatvals.py
+-rw-rw-rw-   0        0        0     3853 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/resources.py
+-rw-rw-rw-   0        0        0     2051 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/rolerates.py
+-rw-rw-rw-   0        0        0     2054 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/roles.py
+-rw-rw-rw-   0        0        0     1943 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/rsrccats.py
+-rw-rw-rw-   0        0        0     2422 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/rsrccurves.py
+-rw-rw-rw-   0        0        0     2102 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/rsrcrates.py
+-rw-rw-rw-   0        0        0     2771 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/schedoptions.py
+-rw-rw-rw-   0        0        0     2157 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/taskactvs.py
+-rw-rw-rw-   0        0        0     2190 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/taskprocs.py
+-rw-rw-rw-   0        0        0     7424 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/tasks.py
+-rw-rw-rw-   0        0        0     2083 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/udftypes.py
+-rw-rw-rw-   0        0        0     2031 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/udfvalues.py
+-rw-rw-rw-   0        0        0     2225 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/model/wbss.py
+-rw-rw-rw-   0        0        0    10917 2023-06-28 10:53:37.000000 PyP6Xer-1.15.0/xerparser/reader.py
+-rw-rw-rw-   0        0        0     2488 2023-06-28 10:51:55.000000 PyP6Xer-1.15.0/xerparser/write.py
```

### Comparing `PyP6Xer-1.14.3/LICENSE` & `PyP6Xer-1.15.0/LICENSE`

 * *Ordering differences only*

 * *Files 5% similar despite different names*

```diff
@@ -1,504 +1,504 @@
-                  GNU LESSER GENERAL PUBLIC LICENSE
-                       Version 2.1, February 1999
-
- Copyright (C) 1991, 1999 Free Software Foundation, Inc.
- 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
- Everyone is permitted to copy and distribute verbatim copies
- of this license document, but changing it is not allowed.
-
-[This is the first released version of the Lesser GPL.  It also counts
- as the successor of the GNU Library Public License, version 2, hence
- the version number 2.1.]
-
-                            Preamble
-
-  The licenses for most software are designed to take away your
-freedom to share and change it.  By contrast, the GNU General Public
-Licenses are intended to guarantee your freedom to share and change
-free software--to make sure the software is free for all its users.
-
-  This license, the Lesser General Public License, applies to some
-specially designated software packages--typically libraries--of the
-Free Software Foundation and other authors who decide to use it.  You
-can use it too, but we suggest you first think carefully about whether
-this license or the ordinary General Public License is the better
-strategy to use in any particular case, based on the explanations below.
-
-  When we speak of free software, we are referring to freedom of use,
-not price.  Our General Public Licenses are designed to make sure that
-you have the freedom to distribute copies of free software (and charge
-for this service if you wish); that you receive source code or can get
-it if you want it; that you can change the software and use pieces of
-it in new free programs; and that you are informed that you can do
-these things.
-
-  To protect your rights, we need to make restrictions that forbid
-distributors to deny you these rights or to ask you to surrender these
-rights.  These restrictions translate to certain responsibilities for
-you if you distribute copies of the library or if you modify it.
-
-  For example, if you distribute copies of the library, whether gratis
-or for a fee, you must give the recipients all the rights that we gave
-you.  You must make sure that they, too, receive or can get the source
-code.  If you link other code with the library, you must provide
-complete object files to the recipients, so that they can relink them
-with the library after making changes to the library and recompiling
-it.  And you must show them these terms so they know their rights.
-
-  We protect your rights with a two-step method: (1) we copyright the
-library, and (2) we offer you this license, which gives you legal
-permission to copy, distribute and/or modify the library.
-
-  To protect each distributor, we want to make it very clear that
-there is no warranty for the free library.  Also, if the library is
-modified by someone else and passed on, the recipients should know
-that what they have is not the original version, so that the original
-author's reputation will not be affected by problems that might be
-introduced by others.
-
-  Finally, software patents pose a constant threat to the existence of
-any free program.  We wish to make sure that a company cannot
-effectively restrict the users of a free program by obtaining a
-restrictive license from a patent holder.  Therefore, we insist that
-any patent license obtained for a version of the library must be
-consistent with the full freedom of use specified in this license.
-
-  Most GNU software, including some libraries, is covered by the
-ordinary GNU General Public License.  This license, the GNU Lesser
-General Public License, applies to certain designated libraries, and
-is quite different from the ordinary General Public License.  We use
-this license for certain libraries in order to permit linking those
-libraries into non-free programs.
-
-  When a program is linked with a library, whether statically or using
-a shared library, the combination of the two is legally speaking a
-combined work, a derivative of the original library.  The ordinary
-General Public License therefore permits such linking only if the
-entire combination fits its criteria of freedom.  The Lesser General
-Public License permits more lax criteria for linking other code with
-the library.
-
-  We call this license the "Lesser" General Public License because it
-does Less to protect the user's freedom than the ordinary General
-Public License.  It also provides other free software developers Less
-of an advantage over competing non-free programs.  These disadvantages
-are the reason we use the ordinary General Public License for many
-libraries.  However, the Lesser license provides advantages in certain
-special circumstances.
-
-  For example, on rare occasions, there may be a special need to
-encourage the widest possible use of a certain library, so that it becomes
-a de-facto standard.  To achieve this, non-free programs must be
-allowed to use the library.  A more frequent case is that a free
-library does the same job as widely used non-free libraries.  In this
-case, there is little to gain by limiting the free library to free
-software only, so we use the Lesser General Public License.
-
-  In other cases, permission to use a particular library in non-free
-programs enables a greater number of people to use a large body of
-free software.  For example, permission to use the GNU C Library in
-non-free programs enables many more people to use the whole GNU
-operating system, as well as its variant, the GNU/Linux operating
-system.
-
-  Although the Lesser General Public License is Less protective of the
-users' freedom, it does ensure that the user of a program that is
-linked with the Library has the freedom and the wherewithal to run
-that program using a modified version of the Library.
-
-  The precise terms and conditions for copying, distribution and
-modification follow.  Pay close attention to the difference between a
-"work based on the library" and a "work that uses the library".  The
-former contains code derived from the library, whereas the latter must
-be combined with the library in order to run.
-
-                  GNU LESSER GENERAL PUBLIC LICENSE
-   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION
-
-  0. This License Agreement applies to any software library or other
-program which contains a notice placed by the copyright holder or
-other authorized party saying it may be distributed under the terms of
-this Lesser General Public License (also called "this License").
-Each licensee is addressed as "you".
-
-  A "library" means a collection of software functions and/or data
-prepared so as to be conveniently linked with application programs
-(which use some of those functions and data) to form executables.
-
-  The "Library", below, refers to any such software library or work
-which has been distributed under these terms.  A "work based on the
-Library" means either the Library or any derivative work under
-copyright law: that is to say, a work containing the Library or a
-portion of it, either verbatim or with modifications and/or translated
-straightforwardly into another language.  (Hereinafter, translation is
-included without limitation in the term "modification".)
-
-  "Source code" for a work means the preferred form of the work for
-making modifications to it.  For a library, complete source code means
-all the source code for all modules it contains, plus any associated
-interface definition files, plus the scripts used to control compilation
-and installation of the library.
-
-  Activities other than copying, distribution and modification are not
-covered by this License; they are outside its scope.  The act of
-running a program using the Library is not restricted, and output from
-such a program is covered only if its contents constitute a work based
-on the Library (independent of the use of the Library in a tool for
-writing it).  Whether that is true depends on what the Library does
-and what the program that uses the Library does.
-
-  1. You may copy and distribute verbatim copies of the Library's
-complete source code as you receive it, in any medium, provided that
-you conspicuously and appropriately publish on each copy an
-appropriate copyright notice and disclaimer of warranty; keep intact
-all the notices that refer to this License and to the absence of any
-warranty; and distribute a copy of this License along with the
-Library.
-
-  You may charge a fee for the physical act of transferring a copy,
-and you may at your option offer warranty protection in exchange for a
-fee.
-
-  2. You may modify your copy or copies of the Library or any portion
-of it, thus forming a work based on the Library, and copy and
-distribute such modifications or work under the terms of Section 1
-above, provided that you also meet all of these conditions:
-
-    a) The modified work must itself be a software library.
-
-    b) You must cause the files modified to carry prominent notices
-    stating that you changed the files and the date of any change.
-
-    c) You must cause the whole of the work to be licensed at no
-    charge to all third parties under the terms of this License.
-
-    d) If a facility in the modified Library refers to a function or a
-    table of data to be supplied by an application program that uses
-    the facility, other than as an argument passed when the facility
-    is invoked, then you must make a good faith effort to ensure that,
-    in the event an application does not supply such function or
-    table, the facility still operates, and performs whatever part of
-    its purpose remains meaningful.
-
-    (For example, a function in a library to compute square roots has
-    a purpose that is entirely well-defined independent of the
-    application.  Therefore, Subsection 2d requires that any
-    application-supplied function or table used by this function must
-    be optional: if the application does not supply it, the square
-    root function must still compute square roots.)
-
-These requirements apply to the modified work as a whole.  If
-identifiable sections of that work are not derived from the Library,
-and can be reasonably considered independent and separate works in
-themselves, then this License, and its terms, do not apply to those
-sections when you distribute them as separate works.  But when you
-distribute the same sections as part of a whole which is a work based
-on the Library, the distribution of the whole must be on the terms of
-this License, whose permissions for other licensees extend to the
-entire whole, and thus to each and every part regardless of who wrote
-it.
-
-Thus, it is not the intent of this section to claim rights or contest
-your rights to work written entirely by you; rather, the intent is to
-exercise the right to control the distribution of derivative or
-collective works based on the Library.
-
-In addition, mere aggregation of another work not based on the Library
-with the Library (or with a work based on the Library) on a volume of
-a storage or distribution medium does not bring the other work under
-the scope of this License.
-
-  3. You may opt to apply the terms of the ordinary GNU General Public
-License instead of this License to a given copy of the Library.  To do
-this, you must alter all the notices that refer to this License, so
-that they refer to the ordinary GNU General Public License, version 2,
-instead of to this License.  (If a newer version than version 2 of the
-ordinary GNU General Public License has appeared, then you can specify
-that version instead if you wish.)  Do not make any other change in
-these notices.
-
-  Once this change is made in a given copy, it is irreversible for
-that copy, so the ordinary GNU General Public License applies to all
-subsequent copies and derivative works made from that copy.
-
-  This option is useful when you wish to copy part of the code of
-the Library into a program that is not a library.
-
-  4. You may copy and distribute the Library (or a portion or
-derivative of it, under Section 2) in object code or executable form
-under the terms of Sections 1 and 2 above provided that you accompany
-it with the complete corresponding machine-readable source code, which
-must be distributed under the terms of Sections 1 and 2 above on a
-medium customarily used for software interchange.
-
-  If distribution of object code is made by offering access to copy
-from a designated place, then offering equivalent access to copy the
-source code from the same place satisfies the requirement to
-distribute the source code, even though third parties are not
-compelled to copy the source along with the object code.
-
-  5. A program that contains no derivative of any portion of the
-Library, but is designed to work with the Library by being compiled or
-linked with it, is called a "work that uses the Library".  Such a
-work, in isolation, is not a derivative work of the Library, and
-therefore falls outside the scope of this License.
-
-  However, linking a "work that uses the Library" with the Library
-creates an executable that is a derivative of the Library (because it
-contains portions of the Library), rather than a "work that uses the
-library".  The executable is therefore covered by this License.
-Section 6 states terms for distribution of such executables.
-
-  When a "work that uses the Library" uses material from a header file
-that is part of the Library, the object code for the work may be a
-derivative work of the Library even though the source code is not.
-Whether this is true is especially significant if the work can be
-linked without the Library, or if the work is itself a library.  The
-threshold for this to be true is not precisely defined by law.
-
-  If such an object file uses only numerical parameters, data
-structure layouts and accessors, and small macros and small inline
-functions (ten lines or less in length), then the use of the object
-file is unrestricted, regardless of whether it is legally a derivative
-work.  (Executables containing this object code plus portions of the
-Library will still fall under Section 6.)
-
-  Otherwise, if the work is a derivative of the Library, you may
-distribute the object code for the work under the terms of Section 6.
-Any executables containing that work also fall under Section 6,
-whether or not they are linked directly with the Library itself.
-
-  6. As an exception to the Sections above, you may also combine or
-link a "work that uses the Library" with the Library to produce a
-work containing portions of the Library, and distribute that work
-under terms of your choice, provided that the terms permit
-modification of the work for the customer's own use and reverse
-engineering for debugging such modifications.
-
-  You must give prominent notice with each copy of the work that the
-Library is used in it and that the Library and its use are covered by
-this License.  You must supply a copy of this License.  If the work
-during execution displays copyright notices, you must include the
-copyright notice for the Library among them, as well as a reference
-directing the user to the copy of this License.  Also, you must do one
-of these things:
-
-    a) Accompany the work with the complete corresponding
-    machine-readable source code for the Library including whatever
-    changes were used in the work (which must be distributed under
-    Sections 1 and 2 above); and, if the work is an executable linked
-    with the Library, with the complete machine-readable "work that
-    uses the Library", as object code and/or source code, so that the
-    user can modify the Library and then relink to produce a modified
-    executable containing the modified Library.  (It is understood
-    that the user who changes the contents of definitions files in the
-    Library will not necessarily be able to recompile the application
-    to use the modified definitions.)
-
-    b) Use a suitable shared library mechanism for linking with the
-    Library.  A suitable mechanism is one that (1) uses at run time a
-    copy of the library already present on the user's computer system,
-    rather than copying library functions into the executable, and (2)
-    will operate properly with a modified version of the library, if
-    the user installs one, as long as the modified version is
-    interface-compatible with the version that the work was made with.
-
-    c) Accompany the work with a written offer, valid for at
-    least three years, to give the same user the materials
-    specified in Subsection 6a, above, for a charge no more
-    than the cost of performing this distribution.
-
-    d) If distribution of the work is made by offering access to copy
-    from a designated place, offer equivalent access to copy the above
-    specified materials from the same place.
-
-    e) Verify that the user has already received a copy of these
-    materials or that you have already sent this user a copy.
-
-  For an executable, the required form of the "work that uses the
-Library" must include any data and utility programs needed for
-reproducing the executable from it.  However, as a special exception,
-the materials to be distributed need not include anything that is
-normally distributed (in either source or binary form) with the major
-components (compiler, kernel, and so on) of the operating system on
-which the executable runs, unless that component itself accompanies
-the executable.
-
-  It may happen that this requirement contradicts the license
-restrictions of other proprietary libraries that do not normally
-accompany the operating system.  Such a contradiction means you cannot
-use both them and the Library together in an executable that you
-distribute.
-
-  7. You may place library facilities that are a work based on the
-Library side-by-side in a single library together with other library
-facilities not covered by this License, and distribute such a combined
-library, provided that the separate distribution of the work based on
-the Library and of the other library facilities is otherwise
-permitted, and provided that you do these two things:
-
-    a) Accompany the combined library with a copy of the same work
-    based on the Library, uncombined with any other library
-    facilities.  This must be distributed under the terms of the
-    Sections above.
-
-    b) Give prominent notice with the combined library of the fact
-    that part of it is a work based on the Library, and explaining
-    where to find the accompanying uncombined form of the same work.
-
-  8. You may not copy, modify, sublicense, link with, or distribute
-the Library except as expressly provided under this License.  Any
-attempt otherwise to copy, modify, sublicense, link with, or
-distribute the Library is void, and will automatically terminate your
-rights under this License.  However, parties who have received copies,
-or rights, from you under this License will not have their licenses
-terminated so long as such parties remain in full compliance.
-
-  9. You are not required to accept this License, since you have not
-signed it.  However, nothing else grants you permission to modify or
-distribute the Library or its derivative works.  These actions are
-prohibited by law if you do not accept this License.  Therefore, by
-modifying or distributing the Library (or any work based on the
-Library), you indicate your acceptance of this License to do so, and
-all its terms and conditions for copying, distributing or modifying
-the Library or works based on it.
-
-  10. Each time you redistribute the Library (or any work based on the
-Library), the recipient automatically receives a license from the
-original licensor to copy, distribute, link with or modify the Library
-subject to these terms and conditions.  You may not impose any further
-restrictions on the recipients' exercise of the rights granted herein.
-You are not responsible for enforcing compliance by third parties with
-this License.
-
-  11. If, as a consequence of a court judgment or allegation of patent
-infringement or for any other reason (not limited to patent issues),
-conditions are imposed on you (whether by court order, agreement or
-otherwise) that contradict the conditions of this License, they do not
-excuse you from the conditions of this License.  If you cannot
-distribute so as to satisfy simultaneously your obligations under this
-License and any other pertinent obligations, then as a consequence you
-may not distribute the Library at all.  For example, if a patent
-license would not permit royalty-free redistribution of the Library by
-all those who receive copies directly or indirectly through you, then
-the only way you could satisfy both it and this License would be to
-refrain entirely from distribution of the Library.
-
-If any portion of this section is held invalid or unenforceable under any
-particular circumstance, the balance of the section is intended to apply,
-and the section as a whole is intended to apply in other circumstances.
-
-It is not the purpose of this section to induce you to infringe any
-patents or other property right claims or to contest validity of any
-such claims; this section has the sole purpose of protecting the
-integrity of the free software distribution system which is
-implemented by public license practices.  Many people have made
-generous contributions to the wide range of software distributed
-through that system in reliance on consistent application of that
-system; it is up to the author/donor to decide if he or she is willing
-to distribute software through any other system and a licensee cannot
-impose that choice.
-
-This section is intended to make thoroughly clear what is believed to
-be a consequence of the rest of this License.
-
-  12. If the distribution and/or use of the Library is restricted in
-certain countries either by patents or by copyrighted interfaces, the
-original copyright holder who places the Library under this License may add
-an explicit geographical distribution limitation excluding those countries,
-so that distribution is permitted only in or among countries not thus
-excluded.  In such case, this License incorporates the limitation as if
-written in the body of this License.
-
-  13. The Free Software Foundation may publish revised and/or new
-versions of the Lesser General Public License from time to time.
-Such new versions will be similar in spirit to the present version,
-but may differ in detail to address new problems or concerns.
-
-Each version is given a distinguishing version number.  If the Library
-specifies a version number of this License which applies to it and
-"any later version", you have the option of following the terms and
-conditions either of that version or of any later version published by
-the Free Software Foundation.  If the Library does not specify a
-license version number, you may choose any version ever published by
-the Free Software Foundation.
-
-  14. If you wish to incorporate parts of the Library into other free
-programs whose distribution conditions are incompatible with these,
-write to the author to ask for permission.  For software which is
-copyrighted by the Free Software Foundation, write to the Free
-Software Foundation; we sometimes make exceptions for this.  Our
-decision will be guided by the two goals of preserving the free status
-of all derivatives of our free software and of promoting the sharing
-and reuse of software generally.
-
-                            NO WARRANTY
-
-  15. BECAUSE THE LIBRARY IS LICENSED FREE OF CHARGE, THERE IS NO
-WARRANTY FOR THE LIBRARY, TO THE EXTENT PERMITTED BY APPLICABLE LAW.
-EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR
-OTHER PARTIES PROVIDE THE LIBRARY "AS IS" WITHOUT WARRANTY OF ANY
-KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE
-IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
-PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE
-LIBRARY IS WITH YOU.  SHOULD THE LIBRARY PROVE DEFECTIVE, YOU ASSUME
-THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
-
-  16. IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN
-WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MAY MODIFY
-AND/OR REDISTRIBUTE THE LIBRARY AS PERMITTED ABOVE, BE LIABLE TO YOU
-FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR
-CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE
-LIBRARY (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING
-RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A
-FAILURE OF THE LIBRARY TO OPERATE WITH ANY OTHER SOFTWARE), EVEN IF
-SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH
-DAMAGES.
-
-                     END OF TERMS AND CONDITIONS
-
-           How to Apply These Terms to Your New Libraries
-
-  If you develop a new library, and you want it to be of the greatest
-possible use to the public, we recommend making it free software that
-everyone can redistribute and change.  You can do so by permitting
-redistribution under these terms (or, alternatively, under the terms of the
-ordinary General Public License).
-
-  To apply these terms, attach the following notices to the library.  It is
-safest to attach them to the start of each source file to most effectively
-convey the exclusion of warranty; and each file should have at least the
-"copyright" line and a pointer to where the full notice is found.
-
-    <one line to give the library's name and a brief idea of what it does.>
-    Copyright (C) <year>  <name of author>
-
-    This library is free software; you can redistribute it and/or
-    modify it under the terms of the GNU Lesser General Public
-    License as published by the Free Software Foundation; either
-    version 2.1 of the License, or (at your option) any later version.
-
-    This library is distributed in the hope that it will be useful,
-    but WITHOUT ANY WARRANTY; without even the implied warranty of
-    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
-    Lesser General Public License for more details.
-
-    You should have received a copy of the GNU Lesser General Public
-    License along with this library; if not, write to the Free Software
-    Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301
-    USA
-
-Also add information on how to contact you by electronic and paper mail.
-
-You should also get your employer (if you work as a programmer) or your
-school, if any, to sign a "copyright disclaimer" for the library, if
-necessary.  Here is a sample; alter the names:
-
-  Yoyodyne, Inc., hereby disclaims all copyright interest in the
-  library `Frob' (a library for tweaking knobs) written by James Random
-  Hacker.
-
-  <signature of Ty Coon>, 1 April 1990
-  Ty Coon, President of Vice
-
-That's all there is to it!
+                  GNU LESSER GENERAL PUBLIC LICENSE
+                       Version 2.1, February 1999
+
+ Copyright (C) 1991, 1999 Free Software Foundation, Inc.
+ 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
+ Everyone is permitted to copy and distribute verbatim copies
+ of this license document, but changing it is not allowed.
+
+[This is the first released version of the Lesser GPL.  It also counts
+ as the successor of the GNU Library Public License, version 2, hence
+ the version number 2.1.]
+
+                            Preamble
+
+  The licenses for most software are designed to take away your
+freedom to share and change it.  By contrast, the GNU General Public
+Licenses are intended to guarantee your freedom to share and change
+free software--to make sure the software is free for all its users.
+
+  This license, the Lesser General Public License, applies to some
+specially designated software packages--typically libraries--of the
+Free Software Foundation and other authors who decide to use it.  You
+can use it too, but we suggest you first think carefully about whether
+this license or the ordinary General Public License is the better
+strategy to use in any particular case, based on the explanations below.
+
+  When we speak of free software, we are referring to freedom of use,
+not price.  Our General Public Licenses are designed to make sure that
+you have the freedom to distribute copies of free software (and charge
+for this service if you wish); that you receive source code or can get
+it if you want it; that you can change the software and use pieces of
+it in new free programs; and that you are informed that you can do
+these things.
+
+  To protect your rights, we need to make restrictions that forbid
+distributors to deny you these rights or to ask you to surrender these
+rights.  These restrictions translate to certain responsibilities for
+you if you distribute copies of the library or if you modify it.
+
+  For example, if you distribute copies of the library, whether gratis
+or for a fee, you must give the recipients all the rights that we gave
+you.  You must make sure that they, too, receive or can get the source
+code.  If you link other code with the library, you must provide
+complete object files to the recipients, so that they can relink them
+with the library after making changes to the library and recompiling
+it.  And you must show them these terms so they know their rights.
+
+  We protect your rights with a two-step method: (1) we copyright the
+library, and (2) we offer you this license, which gives you legal
+permission to copy, distribute and/or modify the library.
+
+  To protect each distributor, we want to make it very clear that
+there is no warranty for the free library.  Also, if the library is
+modified by someone else and passed on, the recipients should know
+that what they have is not the original version, so that the original
+author's reputation will not be affected by problems that might be
+introduced by others.
+
+  Finally, software patents pose a constant threat to the existence of
+any free program.  We wish to make sure that a company cannot
+effectively restrict the users of a free program by obtaining a
+restrictive license from a patent holder.  Therefore, we insist that
+any patent license obtained for a version of the library must be
+consistent with the full freedom of use specified in this license.
+
+  Most GNU software, including some libraries, is covered by the
+ordinary GNU General Public License.  This license, the GNU Lesser
+General Public License, applies to certain designated libraries, and
+is quite different from the ordinary General Public License.  We use
+this license for certain libraries in order to permit linking those
+libraries into non-free programs.
+
+  When a program is linked with a library, whether statically or using
+a shared library, the combination of the two is legally speaking a
+combined work, a derivative of the original library.  The ordinary
+General Public License therefore permits such linking only if the
+entire combination fits its criteria of freedom.  The Lesser General
+Public License permits more lax criteria for linking other code with
+the library.
+
+  We call this license the "Lesser" General Public License because it
+does Less to protect the user's freedom than the ordinary General
+Public License.  It also provides other free software developers Less
+of an advantage over competing non-free programs.  These disadvantages
+are the reason we use the ordinary General Public License for many
+libraries.  However, the Lesser license provides advantages in certain
+special circumstances.
+
+  For example, on rare occasions, there may be a special need to
+encourage the widest possible use of a certain library, so that it becomes
+a de-facto standard.  To achieve this, non-free programs must be
+allowed to use the library.  A more frequent case is that a free
+library does the same job as widely used non-free libraries.  In this
+case, there is little to gain by limiting the free library to free
+software only, so we use the Lesser General Public License.
+
+  In other cases, permission to use a particular library in non-free
+programs enables a greater number of people to use a large body of
+free software.  For example, permission to use the GNU C Library in
+non-free programs enables many more people to use the whole GNU
+operating system, as well as its variant, the GNU/Linux operating
+system.
+
+  Although the Lesser General Public License is Less protective of the
+users' freedom, it does ensure that the user of a program that is
+linked with the Library has the freedom and the wherewithal to run
+that program using a modified version of the Library.
+
+  The precise terms and conditions for copying, distribution and
+modification follow.  Pay close attention to the difference between a
+"work based on the library" and a "work that uses the library".  The
+former contains code derived from the library, whereas the latter must
+be combined with the library in order to run.
+
+                  GNU LESSER GENERAL PUBLIC LICENSE
+   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION
+
+  0. This License Agreement applies to any software library or other
+program which contains a notice placed by the copyright holder or
+other authorized party saying it may be distributed under the terms of
+this Lesser General Public License (also called "this License").
+Each licensee is addressed as "you".
+
+  A "library" means a collection of software functions and/or data
+prepared so as to be conveniently linked with application programs
+(which use some of those functions and data) to form executables.
+
+  The "Library", below, refers to any such software library or work
+which has been distributed under these terms.  A "work based on the
+Library" means either the Library or any derivative work under
+copyright law: that is to say, a work containing the Library or a
+portion of it, either verbatim or with modifications and/or translated
+straightforwardly into another language.  (Hereinafter, translation is
+included without limitation in the term "modification".)
+
+  "Source code" for a work means the preferred form of the work for
+making modifications to it.  For a library, complete source code means
+all the source code for all modules it contains, plus any associated
+interface definition files, plus the scripts used to control compilation
+and installation of the library.
+
+  Activities other than copying, distribution and modification are not
+covered by this License; they are outside its scope.  The act of
+running a program using the Library is not restricted, and output from
+such a program is covered only if its contents constitute a work based
+on the Library (independent of the use of the Library in a tool for
+writing it).  Whether that is true depends on what the Library does
+and what the program that uses the Library does.
+
+  1. You may copy and distribute verbatim copies of the Library's
+complete source code as you receive it, in any medium, provided that
+you conspicuously and appropriately publish on each copy an
+appropriate copyright notice and disclaimer of warranty; keep intact
+all the notices that refer to this License and to the absence of any
+warranty; and distribute a copy of this License along with the
+Library.
+
+  You may charge a fee for the physical act of transferring a copy,
+and you may at your option offer warranty protection in exchange for a
+fee.
+
+  2. You may modify your copy or copies of the Library or any portion
+of it, thus forming a work based on the Library, and copy and
+distribute such modifications or work under the terms of Section 1
+above, provided that you also meet all of these conditions:
+
+    a) The modified work must itself be a software library.
+
+    b) You must cause the files modified to carry prominent notices
+    stating that you changed the files and the date of any change.
+
+    c) You must cause the whole of the work to be licensed at no
+    charge to all third parties under the terms of this License.
+
+    d) If a facility in the modified Library refers to a function or a
+    table of data to be supplied by an application program that uses
+    the facility, other than as an argument passed when the facility
+    is invoked, then you must make a good faith effort to ensure that,
+    in the event an application does not supply such function or
+    table, the facility still operates, and performs whatever part of
+    its purpose remains meaningful.
+
+    (For example, a function in a library to compute square roots has
+    a purpose that is entirely well-defined independent of the
+    application.  Therefore, Subsection 2d requires that any
+    application-supplied function or table used by this function must
+    be optional: if the application does not supply it, the square
+    root function must still compute square roots.)
+
+These requirements apply to the modified work as a whole.  If
+identifiable sections of that work are not derived from the Library,
+and can be reasonably considered independent and separate works in
+themselves, then this License, and its terms, do not apply to those
+sections when you distribute them as separate works.  But when you
+distribute the same sections as part of a whole which is a work based
+on the Library, the distribution of the whole must be on the terms of
+this License, whose permissions for other licensees extend to the
+entire whole, and thus to each and every part regardless of who wrote
+it.
+
+Thus, it is not the intent of this section to claim rights or contest
+your rights to work written entirely by you; rather, the intent is to
+exercise the right to control the distribution of derivative or
+collective works based on the Library.
+
+In addition, mere aggregation of another work not based on the Library
+with the Library (or with a work based on the Library) on a volume of
+a storage or distribution medium does not bring the other work under
+the scope of this License.
+
+  3. You may opt to apply the terms of the ordinary GNU General Public
+License instead of this License to a given copy of the Library.  To do
+this, you must alter all the notices that refer to this License, so
+that they refer to the ordinary GNU General Public License, version 2,
+instead of to this License.  (If a newer version than version 2 of the
+ordinary GNU General Public License has appeared, then you can specify
+that version instead if you wish.)  Do not make any other change in
+these notices.
+
+  Once this change is made in a given copy, it is irreversible for
+that copy, so the ordinary GNU General Public License applies to all
+subsequent copies and derivative works made from that copy.
+
+  This option is useful when you wish to copy part of the code of
+the Library into a program that is not a library.
+
+  4. You may copy and distribute the Library (or a portion or
+derivative of it, under Section 2) in object code or executable form
+under the terms of Sections 1 and 2 above provided that you accompany
+it with the complete corresponding machine-readable source code, which
+must be distributed under the terms of Sections 1 and 2 above on a
+medium customarily used for software interchange.
+
+  If distribution of object code is made by offering access to copy
+from a designated place, then offering equivalent access to copy the
+source code from the same place satisfies the requirement to
+distribute the source code, even though third parties are not
+compelled to copy the source along with the object code.
+
+  5. A program that contains no derivative of any portion of the
+Library, but is designed to work with the Library by being compiled or
+linked with it, is called a "work that uses the Library".  Such a
+work, in isolation, is not a derivative work of the Library, and
+therefore falls outside the scope of this License.
+
+  However, linking a "work that uses the Library" with the Library
+creates an executable that is a derivative of the Library (because it
+contains portions of the Library), rather than a "work that uses the
+library".  The executable is therefore covered by this License.
+Section 6 states terms for distribution of such executables.
+
+  When a "work that uses the Library" uses material from a header file
+that is part of the Library, the object code for the work may be a
+derivative work of the Library even though the source code is not.
+Whether this is true is especially significant if the work can be
+linked without the Library, or if the work is itself a library.  The
+threshold for this to be true is not precisely defined by law.
+
+  If such an object file uses only numerical parameters, data
+structure layouts and accessors, and small macros and small inline
+functions (ten lines or less in length), then the use of the object
+file is unrestricted, regardless of whether it is legally a derivative
+work.  (Executables containing this object code plus portions of the
+Library will still fall under Section 6.)
+
+  Otherwise, if the work is a derivative of the Library, you may
+distribute the object code for the work under the terms of Section 6.
+Any executables containing that work also fall under Section 6,
+whether or not they are linked directly with the Library itself.
+
+  6. As an exception to the Sections above, you may also combine or
+link a "work that uses the Library" with the Library to produce a
+work containing portions of the Library, and distribute that work
+under terms of your choice, provided that the terms permit
+modification of the work for the customer's own use and reverse
+engineering for debugging such modifications.
+
+  You must give prominent notice with each copy of the work that the
+Library is used in it and that the Library and its use are covered by
+this License.  You must supply a copy of this License.  If the work
+during execution displays copyright notices, you must include the
+copyright notice for the Library among them, as well as a reference
+directing the user to the copy of this License.  Also, you must do one
+of these things:
+
+    a) Accompany the work with the complete corresponding
+    machine-readable source code for the Library including whatever
+    changes were used in the work (which must be distributed under
+    Sections 1 and 2 above); and, if the work is an executable linked
+    with the Library, with the complete machine-readable "work that
+    uses the Library", as object code and/or source code, so that the
+    user can modify the Library and then relink to produce a modified
+    executable containing the modified Library.  (It is understood
+    that the user who changes the contents of definitions files in the
+    Library will not necessarily be able to recompile the application
+    to use the modified definitions.)
+
+    b) Use a suitable shared library mechanism for linking with the
+    Library.  A suitable mechanism is one that (1) uses at run time a
+    copy of the library already present on the user's computer system,
+    rather than copying library functions into the executable, and (2)
+    will operate properly with a modified version of the library, if
+    the user installs one, as long as the modified version is
+    interface-compatible with the version that the work was made with.
+
+    c) Accompany the work with a written offer, valid for at
+    least three years, to give the same user the materials
+    specified in Subsection 6a, above, for a charge no more
+    than the cost of performing this distribution.
+
+    d) If distribution of the work is made by offering access to copy
+    from a designated place, offer equivalent access to copy the above
+    specified materials from the same place.
+
+    e) Verify that the user has already received a copy of these
+    materials or that you have already sent this user a copy.
+
+  For an executable, the required form of the "work that uses the
+Library" must include any data and utility programs needed for
+reproducing the executable from it.  However, as a special exception,
+the materials to be distributed need not include anything that is
+normally distributed (in either source or binary form) with the major
+components (compiler, kernel, and so on) of the operating system on
+which the executable runs, unless that component itself accompanies
+the executable.
+
+  It may happen that this requirement contradicts the license
+restrictions of other proprietary libraries that do not normally
+accompany the operating system.  Such a contradiction means you cannot
+use both them and the Library together in an executable that you
+distribute.
+
+  7. You may place library facilities that are a work based on the
+Library side-by-side in a single library together with other library
+facilities not covered by this License, and distribute such a combined
+library, provided that the separate distribution of the work based on
+the Library and of the other library facilities is otherwise
+permitted, and provided that you do these two things:
+
+    a) Accompany the combined library with a copy of the same work
+    based on the Library, uncombined with any other library
+    facilities.  This must be distributed under the terms of the
+    Sections above.
+
+    b) Give prominent notice with the combined library of the fact
+    that part of it is a work based on the Library, and explaining
+    where to find the accompanying uncombined form of the same work.
+
+  8. You may not copy, modify, sublicense, link with, or distribute
+the Library except as expressly provided under this License.  Any
+attempt otherwise to copy, modify, sublicense, link with, or
+distribute the Library is void, and will automatically terminate your
+rights under this License.  However, parties who have received copies,
+or rights, from you under this License will not have their licenses
+terminated so long as such parties remain in full compliance.
+
+  9. You are not required to accept this License, since you have not
+signed it.  However, nothing else grants you permission to modify or
+distribute the Library or its derivative works.  These actions are
+prohibited by law if you do not accept this License.  Therefore, by
+modifying or distributing the Library (or any work based on the
+Library), you indicate your acceptance of this License to do so, and
+all its terms and conditions for copying, distributing or modifying
+the Library or works based on it.
+
+  10. Each time you redistribute the Library (or any work based on the
+Library), the recipient automatically receives a license from the
+original licensor to copy, distribute, link with or modify the Library
+subject to these terms and conditions.  You may not impose any further
+restrictions on the recipients' exercise of the rights granted herein.
+You are not responsible for enforcing compliance by third parties with
+this License.
+
+  11. If, as a consequence of a court judgment or allegation of patent
+infringement or for any other reason (not limited to patent issues),
+conditions are imposed on you (whether by court order, agreement or
+otherwise) that contradict the conditions of this License, they do not
+excuse you from the conditions of this License.  If you cannot
+distribute so as to satisfy simultaneously your obligations under this
+License and any other pertinent obligations, then as a consequence you
+may not distribute the Library at all.  For example, if a patent
+license would not permit royalty-free redistribution of the Library by
+all those who receive copies directly or indirectly through you, then
+the only way you could satisfy both it and this License would be to
+refrain entirely from distribution of the Library.
+
+If any portion of this section is held invalid or unenforceable under any
+particular circumstance, the balance of the section is intended to apply,
+and the section as a whole is intended to apply in other circumstances.
+
+It is not the purpose of this section to induce you to infringe any
+patents or other property right claims or to contest validity of any
+such claims; this section has the sole purpose of protecting the
+integrity of the free software distribution system which is
+implemented by public license practices.  Many people have made
+generous contributions to the wide range of software distributed
+through that system in reliance on consistent application of that
+system; it is up to the author/donor to decide if he or she is willing
+to distribute software through any other system and a licensee cannot
+impose that choice.
+
+This section is intended to make thoroughly clear what is believed to
+be a consequence of the rest of this License.
+
+  12. If the distribution and/or use of the Library is restricted in
+certain countries either by patents or by copyrighted interfaces, the
+original copyright holder who places the Library under this License may add
+an explicit geographical distribution limitation excluding those countries,
+so that distribution is permitted only in or among countries not thus
+excluded.  In such case, this License incorporates the limitation as if
+written in the body of this License.
+
+  13. The Free Software Foundation may publish revised and/or new
+versions of the Lesser General Public License from time to time.
+Such new versions will be similar in spirit to the present version,
+but may differ in detail to address new problems or concerns.
+
+Each version is given a distinguishing version number.  If the Library
+specifies a version number of this License which applies to it and
+"any later version", you have the option of following the terms and
+conditions either of that version or of any later version published by
+the Free Software Foundation.  If the Library does not specify a
+license version number, you may choose any version ever published by
+the Free Software Foundation.
+
+  14. If you wish to incorporate parts of the Library into other free
+programs whose distribution conditions are incompatible with these,
+write to the author to ask for permission.  For software which is
+copyrighted by the Free Software Foundation, write to the Free
+Software Foundation; we sometimes make exceptions for this.  Our
+decision will be guided by the two goals of preserving the free status
+of all derivatives of our free software and of promoting the sharing
+and reuse of software generally.
+
+                            NO WARRANTY
+
+  15. BECAUSE THE LIBRARY IS LICENSED FREE OF CHARGE, THERE IS NO
+WARRANTY FOR THE LIBRARY, TO THE EXTENT PERMITTED BY APPLICABLE LAW.
+EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR
+OTHER PARTIES PROVIDE THE LIBRARY "AS IS" WITHOUT WARRANTY OF ANY
+KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE
+IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
+PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE
+LIBRARY IS WITH YOU.  SHOULD THE LIBRARY PROVE DEFECTIVE, YOU ASSUME
+THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
+
+  16. IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN
+WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MAY MODIFY
+AND/OR REDISTRIBUTE THE LIBRARY AS PERMITTED ABOVE, BE LIABLE TO YOU
+FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR
+CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE
+LIBRARY (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING
+RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A
+FAILURE OF THE LIBRARY TO OPERATE WITH ANY OTHER SOFTWARE), EVEN IF
+SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH
+DAMAGES.
+
+                     END OF TERMS AND CONDITIONS
+
+           How to Apply These Terms to Your New Libraries
+
+  If you develop a new library, and you want it to be of the greatest
+possible use to the public, we recommend making it free software that
+everyone can redistribute and change.  You can do so by permitting
+redistribution under these terms (or, alternatively, under the terms of the
+ordinary General Public License).
+
+  To apply these terms, attach the following notices to the library.  It is
+safest to attach them to the start of each source file to most effectively
+convey the exclusion of warranty; and each file should have at least the
+"copyright" line and a pointer to where the full notice is found.
+
+    <one line to give the library's name and a brief idea of what it does.>
+    Copyright (C) <year>  <name of author>
+
+    This library is free software; you can redistribute it and/or
+    modify it under the terms of the GNU Lesser General Public
+    License as published by the Free Software Foundation; either
+    version 2.1 of the License, or (at your option) any later version.
+
+    This library is distributed in the hope that it will be useful,
+    but WITHOUT ANY WARRANTY; without even the implied warranty of
+    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
+    Lesser General Public License for more details.
+
+    You should have received a copy of the GNU Lesser General Public
+    License along with this library; if not, write to the Free Software
+    Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301
+    USA
+
+Also add information on how to contact you by electronic and paper mail.
+
+You should also get your employer (if you work as a programmer) or your
+school, if any, to sign a "copyright disclaimer" for the library, if
+necessary.  Here is a sample; alter the names:
+
+  Yoyodyne, Inc., hereby disclaims all copyright interest in the
+  library `Frob' (a library for tweaking knobs) written by James Random
+  Hacker.
+
+  <signature of Ty Coon>, 1 April 1990
+  Ty Coon, President of Vice
+
+That's all there is to it!
```

### Comparing `PyP6Xer-1.14.3/PyP6Xer.egg-info/SOURCES.txt` & `PyP6Xer-1.15.0/PyP6Xer.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `PyP6Xer-1.14.3/README.md` & `PyP6Xer-1.15.0/README.md`

 * *Ordering differences only*

 * *Files 25% similar despite different names*

```diff
@@ -1,27 +1,27 @@
-# PyP6Xer Python Primavera P6 XER parser
-PyXer is an open source project to parse Primavera xer files in python. The project is work in progress and open for community contributions. 
-
-In order to install a copy in your system you can use pip package manager as follows:
-
-``` 
-pip install PyP6XER
-```
-
-The usage of the library is fairly simple and the import examples can be:
-
-```
-from xerparser.reader import Reader
-```
-
-Here are some examples of reading and parsing xer files:
-
-```
-xer = Reader("<filename>") # this returns a reader object  
-```
-
-to reade all projects in file as one xer file may have multiple projects stored into it:
-
-```
-for project in xer.projects:
-  print(project)
-```
+# PyP6Xer Python Primavera P6 XER parser
+PyXer is an open source project to parse Primavera xer files in python. The project is work in progress and open for community contributions. 
+
+In order to install a copy in your system you can use pip package manager as follows:
+
+``` 
+pip install PyP6XER
+```
+
+The usage of the library is fairly simple and the import examples can be:
+
+```
+from xerparser.reader import Reader
+```
+
+Here are some examples of reading and parsing xer files:
+
+```
+xer = Reader("<filename>") # this returns a reader object  
+```
+
+to reade all projects in file as one xer file may have multiple projects stored into it:
+
+```
+for project in xer.projects:
+  print(project)
+```
```

### Comparing `PyP6Xer-1.14.3/xerparser/__init__.py` & `PyP6Xer-1.15.0/xerparser/__init__.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,76 +1,76 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.calendar import Calendar
-from xerparser.model.classes.activitycode import ActivityCode
-from xerparser.model.classes.acttype import ActType
-from xerparser.model.classes.obs import OBS
-from xerparser.model.classes.project import Project
-from xerparser.model.classes.rcattype import RCatType
-from xerparser.model.classes.rcatval import RCatVal
-from xerparser.model.classes.rsrc import Resource
-from xerparser.model.classes.rsrcrate import ResourceRate
-from xerparser.model.classes.rsrcrcat import ResourceCat
-from xerparser.model.classes.schedoption import SchedOption
-from xerparser.model.classes.task import Task
-from xerparser.model.classes.taskactv import TaskActv
-from xerparser.model.classes.taskpred import TaskPred
-from xerparser.model.classes.udftype import UDFType
-from xerparser.model.classes.udfvalue import UDFValue
-from xerparser.model.classes.wbs import WBS
-from xerparser.model.classes.currency import Currency
-from xerparser.model.classes.taskrsrc import TaskRsrc
-from xerparser.model.classes.role import Role
-from xerparser.model.classes.account import Account
-from xerparser.model.classes.rolerate import RoleRate
-from xerparser.model.classes.pcattype import PCatType
-from xerparser.model.classes.pcatval import PCatVal
-from xerparser.model.classes.projcat import ProjCat
-from xerparser.model.classes.taskproc import TaskProc
-from xerparser.model.classes.fintmpl import FinTmpl
-from xerparser.model.classes.nonwork import NonWork
-from xerparser.model.tasks import Tasks
-from xerparser.model.predecessors import Predecessors
-from xerparser.model.projects import Projects
-from xerparser.model.wbss import WBSs
-from xerparser.model.resources import Resources
-from xerparser.model.accounts import Accounts
-from xerparser.model.activitycodes import ActivityCodes
-from xerparser.model.acttypes import ActTypes
-from xerparser.model.calendars import Calendars
-from xerparser.model.currencies import Currencies
-from xerparser.model.obss import OBSs
-from xerparser.model.rcattypes import RCatTypes
-from xerparser.model.rcatvals import RCatVals
-from xerparser.model.rolerates import RoleRates
-from xerparser.model.roles import Roles
-from xerparser.model.rsrccurves import ResourceCurves
-from xerparser.model.rsrcrates import ResourceRates
-from xerparser.model.rsrccats import ResourceCategories
-from xerparser.model.schedoptions import SchedOptions
-from xerparser.model.activitiyresources import ActivityResources
-from xerparser.model.udfvalues import UDFValues
-from xerparser.model.udftypes import UDFTypes
-from xerparser.model.taskactvs import TaskActvs
-from xerparser.model.pacttypes import PCatTypes
-from xerparser.model.pcatvals import PCatVals
-from xerparser.model.projcats import ProjCats
-from xerparser.model.taskprocs import TaskProcs
-from xerparser.model.fintmpls import FinTmpls
-from xerparser.model.nonworks import NonWorks
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.calendar import Calendar
+from xerparser.model.classes.activitycode import ActivityCode
+from xerparser.model.classes.acttype import ActType
+from xerparser.model.classes.obs import OBS
+from xerparser.model.classes.project import Project
+from xerparser.model.classes.rcattype import RCatType
+from xerparser.model.classes.rcatval import RCatVal
+from xerparser.model.classes.rsrc import Resource
+from xerparser.model.classes.rsrcrate import ResourceRate
+from xerparser.model.classes.rsrcrcat import ResourceCat
+from xerparser.model.classes.schedoption import SchedOption
+from xerparser.model.classes.task import Task
+from xerparser.model.classes.taskactv import TaskActv
+from xerparser.model.classes.taskpred import TaskPred
+from xerparser.model.classes.udftype import UDFType
+from xerparser.model.classes.udfvalue import UDFValue
+from xerparser.model.classes.wbs import WBS
+from xerparser.model.classes.currency import Currency
+from xerparser.model.classes.taskrsrc import TaskRsrc
+from xerparser.model.classes.role import Role
+from xerparser.model.classes.account import Account
+from xerparser.model.classes.rolerate import RoleRate
+from xerparser.model.classes.pcattype import PCatType
+from xerparser.model.classes.pcatval import PCatVal
+from xerparser.model.classes.projcat import ProjCat
+from xerparser.model.classes.taskproc import TaskProc
+from xerparser.model.classes.fintmpl import FinTmpl
+from xerparser.model.classes.nonwork import NonWork
+from xerparser.model.tasks import Tasks
+from xerparser.model.predecessors import Predecessors
+from xerparser.model.projects import Projects
+from xerparser.model.wbss import WBSs
+from xerparser.model.resources import Resources
+from xerparser.model.accounts import Accounts
+from xerparser.model.activitycodes import ActivityCodes
+from xerparser.model.acttypes import ActTypes
+from xerparser.model.calendars import Calendars
+from xerparser.model.currencies import Currencies
+from xerparser.model.obss import OBSs
+from xerparser.model.rcattypes import RCatTypes
+from xerparser.model.rcatvals import RCatVals
+from xerparser.model.rolerates import RoleRates
+from xerparser.model.roles import Roles
+from xerparser.model.rsrccurves import ResourceCurves
+from xerparser.model.rsrcrates import ResourceRates
+from xerparser.model.rsrccats import ResourceCategories
+from xerparser.model.schedoptions import SchedOptions
+from xerparser.model.activitiyresources import ActivityResources
+from xerparser.model.udfvalues import UDFValues
+from xerparser.model.udftypes import UDFTypes
+from xerparser.model.taskactvs import TaskActvs
+from xerparser.model.pacttypes import PCatTypes
+from xerparser.model.pcatvals import PCatVals
+from xerparser.model.projcats import ProjCats
+from xerparser.model.taskprocs import TaskProcs
+from xerparser.model.fintmpls import FinTmpls
+from xerparser.model.nonworks import NonWorks
```

### Comparing `PyP6Xer-1.14.3/xerparser/dcma14/analysis.py` & `PyP6Xer-1.15.0/xerparser/dcma14/analysis.py`

 * *Ordering differences only*

 * *Files 16% similar despite different names*

```diff
@@ -1,214 +1,214 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-from datetime import datetime
-from logging import critical
-
-
-class DCMA14():
-    """
-
-    {Analysis :
-        {
-        Predecessors: {
-            cnt : 45
-            tasks: []
-            }
-        },
-        successors: {
-            cnt: 30,
-            tasks: []
-        }
-    """
-    def __init__(self, programme, duration_limit=1, lag_limit=0, tf_limit=0):
-        self.count = 0
-        self.programme = programme
-        self.dur_limit = duration_limit
-        self.lag_limit = lag_limit
-        self.tf_limit = tf_limit
-        self.results = {}
-        self.results['analysis'] = {}
-
-
-    def analysis(self):
-        self.activity_count = len(self.programme.activities)
-        self.relation_count = len(self.programme.relations)
-        self.results['analysis']['summary'] = {'activity_cnt': self.activity_count, 'relationship_cnt': self.relation_count}
-        # 1.1 successors
-        self.no_successors = self.chk_successors()
-        self.no_successors_cnt = len(self.no_successors)
-        self.results['analysis']['successors'] = {'cnt': self.no_successors_cnt,
-                                                  'activities': [self.get_activity(x.task_id) for x in self.no_successors],
-                                                  'pct': self.no_successors_cnt / float(self.activity_count)}
-        #1.2 predecessors
-        self.no_predecessors = self.chk_predessors()
-        self.no_predecessors_cnt = len(self.no_predecessors)
-        self.results['analysis']['predecessors'] = {'cnt': self.no_predecessors_cnt,
-                                                    'activities': [self.get_activity(x.task_id) for x in self.no_predecessors],
-                                                    'pct': self.no_predecessors_cnt / float(self.activity_count)}
-        #2 lags
-        self.lags = list(filter(lambda x: x.lag_hr_cnt > self.lag_limit if x.lag_hr_cnt else None, self.programme.relations))
-        self.results['analysis']['lags'] = {'cnt': len(self.lags),
-                                            'relations': [ { 
-                                                            "successor":self.get_activity(x.task_id),
-                                                            "predecessor":self.get_activity(x.pred_task_id),
-                                                            "type": x.pred_type,
-                                                            "lag": int(x.lag_hr_cnt / 8.0)
-                                                            } for x in self.lags],
-                                            'pct': len(self.lags) / float(self.relation_count)}
-        #3 leads
-        self.leads = self.programme.relations.leads
-        self.results['analysis']['leads'] = {'cnt': len(self.leads),
-                                             'relations': [{ 
-                                                            "successor":self.get_activity(x.task_id),
-                                                            "predecessor":self.get_activity(x.pred_task_id),
-                                                            "type": x.pred_type,
-                                                            "lag": int(x.lag_hr_cnt / 8.0)
-                                                            } for x in self.leads],
-                                             'pct': len(self.leads) / float(self.relation_count)}
-        #4 relationships
-        self.fsRel = self.programme.relations.finish_to_start
-        self.results['analysis']['relations'] = {'fs_cnt': len(self.fsRel), 'relationship': [
-                                                { 
-                                                    "successor":self.get_activity(x.task_id),
-                                                    "predecessor":self.get_activity(x.pred_task_id),
-                                                    "type": x.pred_type,
-                                                    "lag": int(x.lag_hr_cnt / 8.0)
-                                                    } for x in self.fsRel]}
-        #5 constraints
-        lst = ['CS_MANDFIN', 'CS_MANDFIN']
-        self.constraints = list(filter(lambda x: x.get('ConstraintType') in lst,
-                                        self.programme.activities))
-        self.results['analysis']['constraints'] = {'cstr_cnt': len(self.constraints), 
-                                                    'cstrs': [self.get_activity(x.task_id) for x in self.constraints]}
-        #6 large total float
-        self.totalfloat = list(filter(lambda x: x.total_float_hr_cnt /8.0 > self.tf_limit if x.total_float_hr_cnt else 0,  self.programme.activities.activities))
-        self.results['analysis']['totalfloat'] = {'cnt': len(self.totalfloat),
-                                                'activities': [self.get_activity(x.task_id) for x in self.totalfloat],
-                                                'pct': len(self.totalfloat) / float(self.activity_count)}
-        #7 negative total float
-        self.negativefloat = list(filter(lambda x: x.total_float_hr_cnt /8.0 < 0 if x.total_float_hr_cnt else 0,  self.programme.activities.activities))
-        self.results['analysis']['negativefloat'] = {'cnt': len(self.negativefloat),
-                                                'activities': [self.get_activity(x.task_id) for x in self.negativefloat],
-                                                'pct': len(self.negativefloat) / float(self.activity_count)}
-        #8 durations
-        self.duration = list(filter(lambda x: x.duration > self.dur_limit,  self.programme.activities.activities))
-        self.results['analysis']['duration'] = {'cnt': len(self.duration),
-                                                'activities': [self.get_activity(x.task_id) for x in self.duration],
-                                                'pct': len(self.duration) / float(self.activity_count)}
-        #9 Check for Invalid Dates
-        # no actual dates beyong data date
-        data_date = {}
-        for x in self.programme.projects:
-            data_date[str(x.proj_id)] = datetime.strptime(x.last_recalc_date, "%Y-%m-%d %H:%M")
-        print(data_date)
-        self.invalidactualstart = list(filter(lambda x: None if x.act_start_date is None else x.act_start_date > data_date[str(x.proj_id)], self.programme.activities.activities))
-        self.invalidactualfinish = list(filter(lambda x: None if x.act_end_date is None else x.act_end_date > data_date[str(x.proj_id)], self.programme.activities.activities))
-        self.invalidearlystart = list(filter(lambda x: None if x.early_start_date is None else x.early_start_date < data_date[str(x.proj_id)], self.programme.activities.activities))
-        self.invalidearlyfinish = list(filter(lambda x: None if x.early_end_date is None else x.early_end_date < data_date[str(x.proj_id)], self.programme.activities.activities))
-        cnt = len(self.invalidactualfinish) + len(self.invalidactualstart) + len(self.invalidearlystart) + len(self.invalidearlyfinish)
-        pct = cnt / float(self.activity_count)
-        self.invaliddates = {
-            "actual_start": [self.get_activity(x.task_id) for x in self.invalidactualstart],
-            "actual_finish": [self.get_activity(x.task_id) for x in self.invalidactualfinish],
-            "early_start": [self.get_activity(x.task_id) for x in self.invalidearlystart],
-            "early_finish": [self.get_activity(x.task_id) for x in self.invalidearlyfinish],
-            "cnt": cnt,
-            'pct': pct
-            }
-        self.results['analysis']['invaliddates'] = self.invaliddates
-
-        #10 Check resource assignments
-        no_resources = []
-        tasks_id = [x.task_id for x in self.programme.activities.activities]
-        for t_id in tasks_id:
-            assignments = self.programme.activityresources.find_by_activity_id(t_id)
-            if len(assignments) == 0:
-                no_resources.append(t_id)
-        self.results['analysis']['resources'] = {
-            'activities': [self.get_activity(x) for x in no_resources],
-            "cnt": len(no_resources),
-            'pct': len(no_resources) / float(self.activity_count)
-        }
-        print(no_resources)
-
-        #11 slippage from target
-        # end dates are later than target end dates
-        self.actualendslippage = list(filter(lambda x: None if x.act_end_date is None else x.act_end_date > x.target_end_date, self.programme.activities.activities))
-        self.earlyendslippage = list(filter(lambda x: None if x.early_end_date is None else x.early_end_date > x.target_end_date, self.programme.activities.activities))
-        slipped = self.actualendslippage + self.earlyendslippage
-        print("SLIPPED", slipped)
-        self.results['analysis']['slippage'] = {
-            'activities': [{
-                "id":x.task_code,
-                "name": x.task_name,
-                "early_finish": str(x.early_end_date),
-                "planned_finish": str(x.target_end_date)
-            } for x in slipped],
-            'cnt': len(slipped),
-            'pct': len(slipped) / float(self.activity_count)
-        }
-
-        #12 Critical Path Test
-         
-        
-        #13 Critical Path Length Index
-        # calculated as cirical path length + total float / critical path length
-        # critical = list(filter(lambda x: x.total_float_hr_cnt <= 10.0 if x.total_float_hr_cnt else None, self.programme.activities.activities))
-        critical = []
-        for act in self.programme.activities.activities:
-            if act.total_float_hr_cnt is not None:
-                print("TF FOUND", act.task_code, act.total_float_hr_cnt)
-                if act.total_float_hr_cnt <= 0:
-                    
-                    critical.append(act)
-            else:
-                print("TF Not found")
-
-
-        print("critical", [(task.task_code, task.early_start_date, task.total_float_hr_cnt) for task in critical])
-
-        self.results['analysis']['critical'] = {
-            'activities': [self.get_activity(x.task_id) for x in critical],
-            'cnt': len(critical),
-            'pct': len(critical) / self.activity_count
-        }
-
-        
-
-        #14 BLEI
-
-
-        return self.results
-
-    def chk_successors(self):
-        return self.programme.activities.has_no_successor
-
-    def chk_predessors(self):
-        return self.programme.activities.has_no_predecessor
-
-    def get_activity(self, id):
-        activity = self.programme.activities.find_by_id(id)
-        # print(activity)
-        if type(activity) == list:
-            return None
-        return {
-                "id": activity.task_code, 
-                "name": activity.task_name,
-                "duration": activity.duration,
-                "tf":activity.total_float_hr_cnt / 8.0 if activity.total_float_hr_cnt else 0
-                }
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+from datetime import datetime
+from logging import critical
+
+
+class DCMA14():
+    """
+
+    {Analysis :
+        {
+        Predecessors: {
+            cnt : 45
+            tasks: []
+            }
+        },
+        successors: {
+            cnt: 30,
+            tasks: []
+        }
+    """
+    def __init__(self, programme, duration_limit=1, lag_limit=0, tf_limit=0):
+        self.count = 0
+        self.programme = programme
+        self.dur_limit = duration_limit
+        self.lag_limit = lag_limit
+        self.tf_limit = tf_limit
+        self.results = {}
+        self.results['analysis'] = {}
+
+
+    def analysis(self):
+        self.activity_count = len(self.programme.activities)
+        self.relation_count = len(self.programme.relations)
+        self.results['analysis']['summary'] = {'activity_cnt': self.activity_count, 'relationship_cnt': self.relation_count}
+        # 1.1 successors
+        self.no_successors = self.chk_successors()
+        self.no_successors_cnt = len(self.no_successors)
+        self.results['analysis']['successors'] = {'cnt': self.no_successors_cnt,
+                                                  'activities': [self.get_activity(x.task_id) for x in self.no_successors],
+                                                  'pct': self.no_successors_cnt / float(self.activity_count)}
+        #1.2 predecessors
+        self.no_predecessors = self.chk_predessors()
+        self.no_predecessors_cnt = len(self.no_predecessors)
+        self.results['analysis']['predecessors'] = {'cnt': self.no_predecessors_cnt,
+                                                    'activities': [self.get_activity(x.task_id) for x in self.no_predecessors],
+                                                    'pct': self.no_predecessors_cnt / float(self.activity_count)}
+        #2 lags
+        self.lags = list(filter(lambda x: x.lag_hr_cnt > self.lag_limit if x.lag_hr_cnt else None, self.programme.relations))
+        self.results['analysis']['lags'] = {'cnt': len(self.lags),
+                                            'relations': [ { 
+                                                            "successor":self.get_activity(x.task_id),
+                                                            "predecessor":self.get_activity(x.pred_task_id),
+                                                            "type": x.pred_type,
+                                                            "lag": int(x.lag_hr_cnt / 8.0)
+                                                            } for x in self.lags],
+                                            'pct': len(self.lags) / float(self.relation_count)}
+        #3 leads
+        self.leads = self.programme.relations.leads
+        self.results['analysis']['leads'] = {'cnt': len(self.leads),
+                                             'relations': [{ 
+                                                            "successor":self.get_activity(x.task_id),
+                                                            "predecessor":self.get_activity(x.pred_task_id),
+                                                            "type": x.pred_type,
+                                                            "lag": int(x.lag_hr_cnt / 8.0)
+                                                            } for x in self.leads],
+                                             'pct': len(self.leads) / float(self.relation_count)}
+        #4 relationships
+        self.fsRel = self.programme.relations.finish_to_start
+        self.results['analysis']['relations'] = {'fs_cnt': len(self.fsRel), 'relationship': [
+                                                { 
+                                                    "successor":self.get_activity(x.task_id),
+                                                    "predecessor":self.get_activity(x.pred_task_id),
+                                                    "type": x.pred_type,
+                                                    "lag": int(x.lag_hr_cnt / 8.0)
+                                                    } for x in self.fsRel]}
+        #5 constraints
+        lst = ['CS_MANDFIN', 'CS_MANDFIN']
+        self.constraints = list(filter(lambda x: x.get('ConstraintType') in lst,
+                                        self.programme.activities))
+        self.results['analysis']['constraints'] = {'cstr_cnt': len(self.constraints), 
+                                                    'cstrs': [self.get_activity(x.task_id) for x in self.constraints]}
+        #6 large total float
+        self.totalfloat = list(filter(lambda x: x.total_float_hr_cnt /8.0 > self.tf_limit if x.total_float_hr_cnt else 0,  self.programme.activities.activities))
+        self.results['analysis']['totalfloat'] = {'cnt': len(self.totalfloat),
+                                                'activities': [self.get_activity(x.task_id) for x in self.totalfloat],
+                                                'pct': len(self.totalfloat) / float(self.activity_count)}
+        #7 negative total float
+        self.negativefloat = list(filter(lambda x: x.total_float_hr_cnt /8.0 < 0 if x.total_float_hr_cnt else 0,  self.programme.activities.activities))
+        self.results['analysis']['negativefloat'] = {'cnt': len(self.negativefloat),
+                                                'activities': [self.get_activity(x.task_id) for x in self.negativefloat],
+                                                'pct': len(self.negativefloat) / float(self.activity_count)}
+        #8 durations
+        self.duration = list(filter(lambda x: x.duration > self.dur_limit,  self.programme.activities.activities))
+        self.results['analysis']['duration'] = {'cnt': len(self.duration),
+                                                'activities': [self.get_activity(x.task_id) for x in self.duration],
+                                                'pct': len(self.duration) / float(self.activity_count)}
+        #9 Check for Invalid Dates
+        # no actual dates beyong data date
+        data_date = {}
+        for x in self.programme.projects:
+            data_date[str(x.proj_id)] = datetime.strptime(x.last_recalc_date, "%Y-%m-%d %H:%M")
+        print(data_date)
+        self.invalidactualstart = list(filter(lambda x: None if x.act_start_date is None else x.act_start_date > data_date[str(x.proj_id)], self.programme.activities.activities))
+        self.invalidactualfinish = list(filter(lambda x: None if x.act_end_date is None else x.act_end_date > data_date[str(x.proj_id)], self.programme.activities.activities))
+        self.invalidearlystart = list(filter(lambda x: None if x.early_start_date is None else x.early_start_date < data_date[str(x.proj_id)], self.programme.activities.activities))
+        self.invalidearlyfinish = list(filter(lambda x: None if x.early_end_date is None else x.early_end_date < data_date[str(x.proj_id)], self.programme.activities.activities))
+        cnt = len(self.invalidactualfinish) + len(self.invalidactualstart) + len(self.invalidearlystart) + len(self.invalidearlyfinish)
+        pct = cnt / float(self.activity_count)
+        self.invaliddates = {
+            "actual_start": [self.get_activity(x.task_id) for x in self.invalidactualstart],
+            "actual_finish": [self.get_activity(x.task_id) for x in self.invalidactualfinish],
+            "early_start": [self.get_activity(x.task_id) for x in self.invalidearlystart],
+            "early_finish": [self.get_activity(x.task_id) for x in self.invalidearlyfinish],
+            "cnt": cnt,
+            'pct': pct
+            }
+        self.results['analysis']['invaliddates'] = self.invaliddates
+
+        #10 Check resource assignments
+        no_resources = []
+        tasks_id = [x.task_id for x in self.programme.activities.activities]
+        for t_id in tasks_id:
+            assignments = self.programme.activityresources.find_by_activity_id(t_id)
+            if len(assignments) == 0:
+                no_resources.append(t_id)
+        self.results['analysis']['resources'] = {
+            'activities': [self.get_activity(x) for x in no_resources],
+            "cnt": len(no_resources),
+            'pct': len(no_resources) / float(self.activity_count)
+        }
+        print(no_resources)
+
+        #11 slippage from target
+        # end dates are later than target end dates
+        self.actualendslippage = list(filter(lambda x: None if x.act_end_date is None else x.act_end_date > x.target_end_date, self.programme.activities.activities))
+        self.earlyendslippage = list(filter(lambda x: None if x.early_end_date is None else x.early_end_date > x.target_end_date, self.programme.activities.activities))
+        slipped = self.actualendslippage + self.earlyendslippage
+        print("SLIPPED", slipped)
+        self.results['analysis']['slippage'] = {
+            'activities': [{
+                "id":x.task_code,
+                "name": x.task_name,
+                "early_finish": str(x.early_end_date),
+                "planned_finish": str(x.target_end_date)
+            } for x in slipped],
+            'cnt': len(slipped),
+            'pct': len(slipped) / float(self.activity_count)
+        }
+
+        #12 Critical Path Test
+         
+        
+        #13 Critical Path Length Index
+        # calculated as cirical path length + total float / critical path length
+        # critical = list(filter(lambda x: x.total_float_hr_cnt <= 10.0 if x.total_float_hr_cnt else None, self.programme.activities.activities))
+        critical = []
+        for act in self.programme.activities.activities:
+            if act.total_float_hr_cnt is not None:
+                print("TF FOUND", act.task_code, act.total_float_hr_cnt)
+                if act.total_float_hr_cnt <= 0:
+                    
+                    critical.append(act)
+            else:
+                print("TF Not found")
+
+
+        print("critical", [(task.task_code, task.early_start_date, task.total_float_hr_cnt) for task in critical])
+
+        self.results['analysis']['critical'] = {
+            'activities': [self.get_activity(x.task_id) for x in critical],
+            'cnt': len(critical),
+            'pct': len(critical) / self.activity_count
+        }
+
+        
+
+        #14 BLEI
+
+
+        return self.results
+
+    def chk_successors(self):
+        return self.programme.activities.has_no_successor
+
+    def chk_predessors(self):
+        return self.programme.activities.has_no_predecessor
+
+    def get_activity(self, id):
+        activity = self.programme.activities.find_by_id(id)
+        # print(activity)
+        if type(activity) == list:
+            return None
+        return {
+                "id": activity.task_code, 
+                "name": activity.task_name,
+                "duration": activity.duration,
+                "tf":activity.total_float_hr_cnt / 8.0 if activity.total_float_hr_cnt else 0
+                }
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/accounts.py` & `PyP6Xer-1.15.0/xerparser/model/fintmpls.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,53 +1,63 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.account import Account
-
-class Accounts:
-
-    def __init__(self):
-        self._accounts = []
-        self.index = 0
-
-    def add(self, params):
-        self._accounts.append(Account(params))
-
-    def get_tsv(self):
-        if len(self._accounts) > 0:
-            tsv = list()
-            tsv.append(["%T", "ACCOUNT"])
-            tsv.append(["%F", "acct_id", "parent_acct_id", "acct_seq_num", "acct_name", "acct_short_name",
-                        "acct_descr"])
-            for account in self._accounts:
-                tsv.append(account.get_tsv())
-            return tsv
-        return []
-
-    def count(self):
-        return len(self._accounts)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> Account:
-        if self.index >= len(self._accounts):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._accounts[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.fintmpl import FinTmpl
+
+
+class FinTmpls:
+
+    def __init__(self):
+        self.index = 0
+        self._FinTmpls = []
+
+    def add(self, params):
+        self._FinTmpls.append(FinTmpl(params))
+
+    def get_tsv(self):
+        if len(self._FinTmpls) > 0:
+            tsv = []
+            tsv.append(['%T', 'FINTMPL'])
+            tsv.append(["%F", 'fintmpl_id', 'fintmpl_name', 'default_flag'])
+            for fin in self._FinTmpls:
+                tsv.append(fin.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> FinTmpl:
+        obj = list(filter(lambda x: x.fintmpl_id == id, self._FinTmpls))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._FinTmpls)
+
+    def __len__(self):
+        return len(self._FinTmpls)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> FinTmpl:
+        if self.index >= len(self._FinTmpls):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._FinTmpls[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/activitiyresources.py` & `PyP6Xer-1.15.0/xerparser/model/activitiyresources.py`

 * *Ordering differences only*

 * *Files 25% similar despite different names*

```diff
@@ -1,81 +1,81 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.taskrsrc import TaskRsrc
-from xerparser.model.classes.rsrc import Resource
-
-
-class ActivityResources:
-
-    def __init__(self):
-        self.index = 0
-        self._taskrsrc = []
-
-    def add(self, params, data):
-        self._taskrsrc.append(TaskRsrc(params, data))
-
-    def find_by_id(self, id) -> TaskRsrc:
-        obj = list(filter(lambda x: x.taskrsrc_id == id, self._taskrsrc))
-        if len(obj) > 0:
-            return obj[0]
-        return None
-    
-    def get_tsv(self):
-        if len(self._taskrsrc) > 0:
-            tsv = []
-            tsv.append(['%T', 'TASKRSRC'])
-            tsv.append(['%F', 'taskrsrc_id', 'task_id', 'proj_id', 'cost_qty_link_flag', 'role_id', 'acct_id',
-               'rsrc_id', 'pobs_id', 'skill_level', 'remain_qty', 'target_qty', 'remain_qty_per_hr',
-               'target_lag_drtn_hr_cnt', 'target_qty_per_hr', 'act_ot_qty', 'act_reg_qty',
-               'relag_drtn_hr_cnt', 'ot_factor', 'cost_per_qty', 'target_cost', 'act_reg_cost',
-               'act_ot_cost', 'remain_cost', 'act_start_date', 'act_end_date', 'restart_date',
-               'reend_date', 'target_start_date', 'target_end_date', 'rem_late_start_date',
-               'rem_late_end_date', 'rollup_dates_flag', 'target_crv', 'remain_crv', 'actual_crv',
-               'ts_pend_act_end_flag', 'guid', 'rate_type', 'act_this_per_cost', 'act_this_per_qty',
-               'curv_id', 'rsrc_type', 'cost_per_qty_source_type', 'create_user', 'create_date', 'cbs_id',
-               'has_rsrchours', 'taskrsrc_sum_id'])
-            for taskrsrc in self._taskrsrc:
-                tsv.append(taskrsrc.get_tsv())
-            return tsv
-        return []
-
-    def find_by_rsrc_id(self, id) -> TaskRsrc:
-        obj = list(filter(lambda x: x.rsrc_id == id, self._taskrsrc))
-        return obj
-
-    def find_by_activity_id(self, id):
-        obj = list(filter(lambda x: x.task_id == id and x.rsrc_id, self._taskrsrc))
-        return obj
-
-    @property
-    def count(self):
-        return len(self._taskrsrc)
-
-    def __len__(self):
-        return len(ActivityResources._taskrsrc)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> TaskRsrc:
-        if self.index >= len(self._taskrsrc):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.taskrsrc import TaskRsrc
+from xerparser.model.classes.rsrc import Resource
+
+
+class ActivityResources:
+
+    def __init__(self):
+        self.index = 0
+        self._taskrsrc = []
+
+    def add(self, params, data):
+        self._taskrsrc.append(TaskRsrc(params, data))
+
+    def find_by_id(self, id) -> TaskRsrc:
+        obj = list(filter(lambda x: x.taskrsrc_id == id, self._taskrsrc))
+        if len(obj) > 0:
+            return obj[0]
+        return None
+    
+    def get_tsv(self):
+        if len(self._taskrsrc) > 0:
+            tsv = []
+            tsv.append(['%T', 'TASKRSRC'])
+            tsv.append(['%F', 'taskrsrc_id', 'task_id', 'proj_id', 'cost_qty_link_flag', 'role_id', 'acct_id',
+               'rsrc_id', 'pobs_id', 'skill_level', 'remain_qty', 'target_qty', 'remain_qty_per_hr',
+               'target_lag_drtn_hr_cnt', 'target_qty_per_hr', 'act_ot_qty', 'act_reg_qty',
+               'relag_drtn_hr_cnt', 'ot_factor', 'cost_per_qty', 'target_cost', 'act_reg_cost',
+               'act_ot_cost', 'remain_cost', 'act_start_date', 'act_end_date', 'restart_date',
+               'reend_date', 'target_start_date', 'target_end_date', 'rem_late_start_date',
+               'rem_late_end_date', 'rollup_dates_flag', 'target_crv', 'remain_crv', 'actual_crv',
+               'ts_pend_act_end_flag', 'guid', 'rate_type', 'act_this_per_cost', 'act_this_per_qty',
+               'curv_id', 'rsrc_type', 'cost_per_qty_source_type', 'create_user', 'create_date', 'cbs_id',
+               'has_rsrchours', 'taskrsrc_sum_id'])
+            for taskrsrc in self._taskrsrc:
+                tsv.append(taskrsrc.get_tsv())
+            return tsv
+        return []
+
+    def find_by_rsrc_id(self, id) -> TaskRsrc:
+        obj = list(filter(lambda x: x.rsrc_id == id, self._taskrsrc))
+        return obj
+
+    def find_by_activity_id(self, id):
+        obj = list(filter(lambda x: x.task_id == id and x.rsrc_id, self._taskrsrc))
+        return obj
+
+    @property
+    def count(self):
+        return len(self._taskrsrc)
+
+    def __len__(self):
+        return len(ActivityResources._taskrsrc)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> TaskRsrc:
+        if self.index >= len(self._taskrsrc):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
         return self._taskrsrc[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/activitycodes.py` & `PyP6Xer-1.15.0/xerparser/model/activitycodes.py`

 * *Ordering differences only*

 * *Files 20% similar despite different names*

```diff
@@ -1,67 +1,67 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.activitycode import ActivityCode
-
-
-class ActivityCodes:
-
-    def __init__(self):
-        self.index = 0
-        self._activitycodes = []
-
-    def add(self, params):
-        self._activitycodes.append(ActivityCode(params))
-
-    def count(self):
-        return len(self._activitycodes)
-
-    def get_tsv(self):
-        if len(self._activitycodes) > 0:
-            tsv = []
-            tsv.append(['%T', 'ACTVCODE'])
-            tsv.append(['%F', 'actv_code_id', 'parent_actv_code_id', 'actv_code_type_id',
-                        'actv_code_name', 'short_name', 'seq_num', 'color', 'total_assignments'])
-            for code in self._activitycodes:
-                tsv.append(code.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> ActivityCode:
-        obj = list(filter(lambda x: x.actv_code_id == id, self._activitycodes))
-        if obj:
-            return obj[0]
-        return obj
-
-    def find_by_type_id(self, id):
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._activitycodes))
-        return obj
-    
-    def __len__(self):
-        return len(self._activitycodes)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> ActivityCode:
-        if self.index >= len(self._activitycodes):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._activitycodes[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.activitycode import ActivityCode
+
+
+class ActivityCodes:
+
+    def __init__(self):
+        self.index = 0
+        self._activitycodes = []
+
+    def add(self, params):
+        self._activitycodes.append(ActivityCode(params))
+
+    def count(self):
+        return len(self._activitycodes)
+
+    def get_tsv(self):
+        if len(self._activitycodes) > 0:
+            tsv = []
+            tsv.append(['%T', 'ACTVCODE'])
+            tsv.append(['%F', 'actv_code_id', 'parent_actv_code_id', 'actv_code_type_id',
+                        'actv_code_name', 'short_name', 'seq_num', 'color', 'total_assignments'])
+            for code in self._activitycodes:
+                tsv.append(code.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> ActivityCode:
+        obj = list(filter(lambda x: x.actv_code_id == id, self._activitycodes))
+        if obj:
+            return obj[0]
+        return obj
+
+    def find_by_type_id(self, id):
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._activitycodes))
+        return obj
+    
+    def __len__(self):
+        return len(self._activitycodes)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> ActivityCode:
+        if self.index >= len(self._activitycodes):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._activitycodes[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/acttypes.py` & `PyP6Xer-1.15.0/xerparser/model/acttypes.py`

 * *Ordering differences only*

 * *Files 18% similar despite different names*

```diff
@@ -1,64 +1,64 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.acttype import ActType
-
-class ActTypes:
-
-
-
-    def __init__(self):
-        self.index = 0
-        self._activitytypes = []
-
-    def add(self, params):
-        self._activitytypes.append(ActType(params))
-
-    def find_by_id(self, id) -> ActType:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._activitytypes))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    def get_tsv(self):
-        if len(self._activitytypes) > 0:
-            tsv = []
-            tsv.append(['%T', 'ACTVTYPE'])
-            tsv.append(['%F', 'actv_code_type_id', 'actv_short_len', 'seq_num',
-                        'actv_code_type', 'proj_id', 'wbs_id', 'actv_code_type_scope'])
-            for acttyp in self._activitytypes:
-                tsv.append(acttyp.get_tsv())
-            return tsv
-        return []
-
-    def count(self):
-        return len(self._activitytypes)
-
-    def __len__(self):
-        return len(self._activitytypes)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> ActType:
-        if self.index >= len(self._activitytypes):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.acttype import ActType
+
+class ActTypes:
+
+
+
+    def __init__(self):
+        self.index = 0
+        self._activitytypes = []
+
+    def add(self, params):
+        self._activitytypes.append(ActType(params))
+
+    def find_by_id(self, id) -> ActType:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._activitytypes))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    def get_tsv(self):
+        if len(self._activitytypes) > 0:
+            tsv = []
+            tsv.append(['%T', 'ACTVTYPE'])
+            tsv.append(['%F', 'actv_code_type_id', 'actv_short_len', 'seq_num',
+                        'actv_code_type', 'proj_id', 'wbs_id', 'actv_code_type_scope'])
+            for acttyp in self._activitytypes:
+                tsv.append(acttyp.get_tsv())
+            return tsv
+        return []
+
+    def count(self):
+        return len(self._activitytypes)
+
+    def __len__(self):
+        return len(self._activitytypes)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> ActType:
+        if self.index >= len(self._activitytypes):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
         return self._activitytypes[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/calendars.py` & `PyP6Xer-1.15.0/xerparser/model/calendars.py`

 * *Ordering differences only*

 * *Files 16% similar despite different names*

```diff
@@ -1,67 +1,67 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.calendar import Calendar
-
-
-class Calendars:
-
-
-    def __init__(self):
-        self.index = 0
-        self._calendars = []
-
-    def add(self, params):
-        self._calendars.append(Calendar(params))
-
-    def get_tsv(self):
-        if len(self._calendars) > 0:
-            tsv = []
-            tsv.append(['%T', 'CALENDAR'])
-            tsv.append(
-                ['%F', 'clndr_id', 'default_flag', 'clndr_name', 'proj_id',
-                   'base_clndr_id', 'last_chng_date', 'clndr_type', 'day_hr_cnt',
-                   'week_hr_cnt', 'month_hr_cnt', 'year_hr_cnt', 'rsrc_private',
-                   'clndr_data'])
-            for cal in self._calendars:
-                tsv.append(cal.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> Calendar:
-        obj = list(filter(lambda x: x.clndr_id == id, self._calendars))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    def count(self):
-        return len(self._calendars)
-
-    def __len__(self):
-        return len(self._calendars)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> Calendar:
-        if self.index >= len(self._calendars):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.calendar import Calendar
+
+
+class Calendars:
+
+
+    def __init__(self):
+        self.index = 0
+        self._calendars = []
+
+    def add(self, params):
+        self._calendars.append(Calendar(params))
+
+    def get_tsv(self):
+        if len(self._calendars) > 0:
+            tsv = []
+            tsv.append(['%T', 'CALENDAR'])
+            tsv.append(
+                ['%F', 'clndr_id', 'default_flag', 'clndr_name', 'proj_id',
+                   'base_clndr_id', 'last_chng_date', 'clndr_type', 'day_hr_cnt',
+                   'week_hr_cnt', 'month_hr_cnt', 'year_hr_cnt', 'rsrc_private',
+                   'clndr_data'])
+            for cal in self._calendars:
+                tsv.append(cal.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> Calendar:
+        obj = list(filter(lambda x: x.clndr_id == id, self._calendars))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    def count(self):
+        return len(self._calendars)
+
+    def __len__(self):
+        return len(self._calendars)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> Calendar:
+        if self.index >= len(self._calendars):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
         return self._calendars[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/account.py` & `PyP6Xer-1.15.0/xerparser/model/classes/account.py`

 * *Ordering differences only*

 * *Files 21% similar despite different names*

```diff
@@ -1,43 +1,43 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class Account:
-    # obj_list = []
-
-    def __init__(self, params):
-        self.acct_id = int(params.get('acct_id').strip()) if params.get('acct_id') else None
-        self.parent_acct_id = int(params.get('parent_acct_id').strip()) if params.get('parent_acct_id') else None
-        self.acct_seq_num = int(params.get('acct_seq_num').strip()) if params.get('acct_seq_num') else None
-        self.acct_name = params.get('acct_name').strip() if params.get('acct_name') else None
-        self.acct_short_name = params.get('acct_short_name').strip() if params.get('acct_short_name') else None
-        self.acct_descr = params.get('acct_descr').strip() if params.get('acct_descr') else None
-        # Account.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ["%R", self.acct_id, self.parent_acct_id, self.acct_seq_num, self.acct_name, self.acct_short_name,
-               self.acct_descr]
-        return tsv
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.acct_id == id, cls.obj_list))[0]
-        return obj
-
-    def __repr__(self):
-        return self.acct_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class Account:
+    # obj_list = []
+
+    def __init__(self, params):
+        self.acct_id = int(params.get('acct_id').strip()) if params.get('acct_id') else None
+        self.parent_acct_id = int(params.get('parent_acct_id').strip()) if params.get('parent_acct_id') else None
+        self.acct_seq_num = int(params.get('acct_seq_num').strip()) if params.get('acct_seq_num') else None
+        self.acct_name = params.get('acct_name').strip() if params.get('acct_name') else None
+        self.acct_short_name = params.get('acct_short_name').strip() if params.get('acct_short_name') else None
+        self.acct_descr = params.get('acct_descr').strip() if params.get('acct_descr') else None
+        # Account.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ["%R", self.acct_id, self.parent_acct_id, self.acct_seq_num, self.acct_name, self.acct_short_name,
+               self.acct_descr]
+        return tsv
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.acct_id == id, cls.obj_list))[0]
+        return obj
+
+    def __repr__(self):
+        return self.acct_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/acttype.py` & `PyP6Xer-1.15.0/xerparser/model/classes/acttype.py`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,67 +1,67 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-import locale
-class ActType:
-    obj_list =[]
-
-    def __init__(self, params):
-        # Unique ID generated by the system.
-        self.actv_code_type_id = int(params.get('actv_code_type_id').strip()) if params.get('actv_code_type_id') else None
-        # The maximum number of characters allowed for values of this Activity Code.
-        self.actv_short_len = locale.atof(params.get('actv_short_len').strip()) if params.get('actv_short_len') else None
-        # Sequence number for sorting.
-        self.seq_num = int(params.get('seq_num').strip()) if params.get('seq_num') else None
-        # Each Activity Code has a list of possible values, any of which can be assigned to an activity. Activity
-        # Codes allow you to classify and categorize activities.
-        self.actv_code_type = params.get('actv_code_type').strip() if params.get('actv_code_type') else None
-        # Identifies the project which owns this Activity Code (if this is a project-level Activity Code).
-        self.proj_id = int(params.get('proj_id')) if params.get('proj_id') else None
-        # EPS Id element that
-        self.wbs_id = params.get('wbs_id').strip() if params.get('wbs_id') else None
-        self.actv_code_type_scope = params.get('actv_code_type_scope').strip() if params.get('actv_code_type_scope') else None
-        ActType.obj_list.append(self)
-
-    def get_id(self):
-        return self.actv_code_type_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.actv_code_type_id, self.actv_short_len, self.seq_num,
-               self.actv_code_type, self.proj_id, self.wbs_id, self.actv_code_type_scope]
-        return tsv
-    @classmethod
-    def find_by_id(cls, id):
-        """ Function to search list of activity code type by an ID
-
-        Args:
-            id: Unique ID generated by the system.
-
-        Returns: ActType that matches the ID
-
-        """
-        obj = list(filter(lambda x: x.actv_code_type_id == id, cls.obj_list))
-        if len(obj) > 0:
-            return obj[0]
-        else:
-            obj = None
-        return obj
-
-
-    def __repr__(self):
-        return self.actv_code_type
-
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+import locale
+class ActType:
+    obj_list =[]
+
+    def __init__(self, params):
+        # Unique ID generated by the system.
+        self.actv_code_type_id = int(params.get('actv_code_type_id').strip()) if params.get('actv_code_type_id') else None
+        # The maximum number of characters allowed for values of this Activity Code.
+        self.actv_short_len = locale.atof(params.get('actv_short_len').strip()) if params.get('actv_short_len') else None
+        # Sequence number for sorting.
+        self.seq_num = int(params.get('seq_num').strip()) if params.get('seq_num') else None
+        # Each Activity Code has a list of possible values, any of which can be assigned to an activity. Activity
+        # Codes allow you to classify and categorize activities.
+        self.actv_code_type = params.get('actv_code_type').strip() if params.get('actv_code_type') else None
+        # Identifies the project which owns this Activity Code (if this is a project-level Activity Code).
+        self.proj_id = int(params.get('proj_id')) if params.get('proj_id') else None
+        # EPS Id element that
+        self.wbs_id = params.get('wbs_id').strip() if params.get('wbs_id') else None
+        self.actv_code_type_scope = params.get('actv_code_type_scope').strip() if params.get('actv_code_type_scope') else None
+        ActType.obj_list.append(self)
+
+    def get_id(self):
+        return self.actv_code_type_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.actv_code_type_id, self.actv_short_len, self.seq_num,
+               self.actv_code_type, self.proj_id, self.wbs_id, self.actv_code_type_scope]
+        return tsv
+    @classmethod
+    def find_by_id(cls, id):
+        """ Function to search list of activity code type by an ID
+
+        Args:
+            id: Unique ID generated by the system.
+
+        Returns: ActType that matches the ID
+
+        """
+        obj = list(filter(lambda x: x.actv_code_type_id == id, cls.obj_list))
+        if len(obj) > 0:
+            return obj[0]
+        else:
+            obj = None
+        return obj
+
+
+    def __repr__(self):
+        return self.actv_code_type
+
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/calendar.py` & `PyP6Xer-1.15.0/xerparser/model/classes/calendar.py`

 * *Ordering differences only*

 * *Files 11% similar despite different names*

```diff
@@ -1,86 +1,86 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.calendar_data import CalendarData
-
-import locale
-class Calendar:
-    obj_list = []
-
-    def __init__(self, params):
-        # Unique ID generated by the system.
-        self.clndr_id = int(params.get('clndr_id').strip()) if params.get('clndr_id') else None
-        # Identifies the default global calendar (applies to global calendars only).
-        self.default_flag = params.get('default_flag').strip() if params.get('default_flag') else None
-        # The name of the calendar.
-        self.clndr_name = params.get('clndr_name').strip() if params.get('clndr_name') else None
-        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
-        # The global calendar to which this calendar is linked.  Any changes to the global calendar are automatically
-        #  propagated to this calendar.
-        self.base_clndr_id = params.get('base_clndr_id').strip() if params.get('base_clndr_id') else None
-        # Date of last changes to calendar.
-        self.last_chng_date = params.get('last_chng_date').strip() if params.get('last_chng_date') else None
-        # The calendar type - either global, resource, or project. Global calendars can be assigned to projects and
-        # resources. Resource calendars can be assigned only to resources. Project calendars are specific to projects.
-        self.clndr_type = params.get('clndr_type').strip() if params.get('clndr_type') else None
-        # The number of work hours per day. This conversion factor is used for displaying time units and durations in
-        #  the user's selected display formats.
-        self.day_hr_cnt = locale.atof(params.get('day_hr_cnt')) if params.get('day_hr_cnt') else None
-        # The number of work hours per week. This conversion factor is used for displaying time units and durations
-        # in the user's selected display formats.
-        self.week_hr_cnt = locale.atof(params.get('week_hr_cnt')) if params.get('week_hr_cnt') else None
-        # The number of work hours per month. This conversion factor is used for displaying time units and durations
-        # in the user's selected display formats.
-        self.month_hr_cnt = locale.atof(params.get('month_hr_cnt')) if params.get('month_hr_cnt') else None
-        # The number of work hours per year. This conversion factor is used for displaying time units and durations
-        # in the user's selected display formats.
-        self.year_hr_cnt = locale.atof(params.get('year_hr_cnt')) if params.get('year_hr_cnt') else None
-        #
-        self.rsrc_private = params.get('rsrc_private').strip() if params.get('rsrc_private') else None
-
-        self.clndr_data = params.get('clndr_data').strip() if params.get('clndr_data') else None
-        self.working_days = dict()
-        self.exceptions = []
-
-        if self.clndr_data:
-            c = CalendarData(self.clndr_data)
-            self.working_days = c.get_days()
-            self.working_hours = c.get_work_pattern()
-            self.exceptions = c.get_exceptions()
-        Calendar.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.clndr_id, self.default_flag, self.clndr_name, self.proj_id,
-               self.base_clndr_id, self.last_chng_date, self.clndr_type, self.day_hr_cnt,
-               self.week_hr_cnt, self.month_hr_cnt, self.year_hr_cnt, self.rsrc_private,
-               self.clndr_data]
-        return tsv
-
-    def get_id(self):
-        return self.clndr_id
-
-    @staticmethod
-    def find_by_id(id):
-        obj = list(filter(lambda x: x.clndr_id == id, Calendar.obj_list))
-        if obj:
-            return obj[0]
-        return None
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.calendar_data import CalendarData
+
+import locale
+class Calendar:
+    obj_list = []
+
+    def __init__(self, params):
+        # Unique ID generated by the system.
+        self.clndr_id = int(params.get('clndr_id').strip()) if params.get('clndr_id') else None
+        # Identifies the default global calendar (applies to global calendars only).
+        self.default_flag = params.get('default_flag').strip() if params.get('default_flag') else None
+        # The name of the calendar.
+        self.clndr_name = params.get('clndr_name').strip() if params.get('clndr_name') else None
+        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
+        # The global calendar to which this calendar is linked.  Any changes to the global calendar are automatically
+        #  propagated to this calendar.
+        self.base_clndr_id = params.get('base_clndr_id').strip() if params.get('base_clndr_id') else None
+        # Date of last changes to calendar.
+        self.last_chng_date = params.get('last_chng_date').strip() if params.get('last_chng_date') else None
+        # The calendar type - either global, resource, or project. Global calendars can be assigned to projects and
+        # resources. Resource calendars can be assigned only to resources. Project calendars are specific to projects.
+        self.clndr_type = params.get('clndr_type').strip() if params.get('clndr_type') else None
+        # The number of work hours per day. This conversion factor is used for displaying time units and durations in
+        #  the user's selected display formats.
+        self.day_hr_cnt = locale.atof(params.get('day_hr_cnt')) if params.get('day_hr_cnt') else None
+        # The number of work hours per week. This conversion factor is used for displaying time units and durations
+        # in the user's selected display formats.
+        self.week_hr_cnt = locale.atof(params.get('week_hr_cnt')) if params.get('week_hr_cnt') else None
+        # The number of work hours per month. This conversion factor is used for displaying time units and durations
+        # in the user's selected display formats.
+        self.month_hr_cnt = locale.atof(params.get('month_hr_cnt')) if params.get('month_hr_cnt') else None
+        # The number of work hours per year. This conversion factor is used for displaying time units and durations
+        # in the user's selected display formats.
+        self.year_hr_cnt = locale.atof(params.get('year_hr_cnt')) if params.get('year_hr_cnt') else None
+        #
+        self.rsrc_private = params.get('rsrc_private').strip() if params.get('rsrc_private') else None
+
+        self.clndr_data = params.get('clndr_data').strip() if params.get('clndr_data') else None
+        self.working_days = dict()
+        self.exceptions = []
+
+        if self.clndr_data:
+            c = CalendarData(self.clndr_data)
+            self.working_days = c.get_days()
+            self.working_hours = c.get_work_pattern()
+            self.exceptions = c.get_exceptions()
+        Calendar.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.clndr_id, self.default_flag, self.clndr_name, self.proj_id,
+               self.base_clndr_id, self.last_chng_date, self.clndr_type, self.day_hr_cnt,
+               self.week_hr_cnt, self.month_hr_cnt, self.year_hr_cnt, self.rsrc_private,
+               self.clndr_data]
+        return tsv
+
+    def get_id(self):
+        return self.clndr_id
+
+    @staticmethod
+    def find_by_id(id):
+        obj = list(filter(lambda x: x.clndr_id == id, Calendar.obj_list))
+        if obj:
+            return obj[0]
+        return None
+
+    def __repr__(self):
         return self.clndr_name + ' : ' + str(self.day_hr_cnt) + '\n' + self.clndr_data
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/calendar_data.py` & `PyP6Xer-1.15.0/xerparser/model/classes/calendar_data.py`

 * *Ordering differences only*

 * *Files 27% similar despite different names*

```diff
@@ -1,102 +1,102 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-import re
-import datetime
-
-
-class CalendarData:
-    working_days = dict()
-    exceptions = []
-
-    def __init__(self, text):
-        self.text = text
-        cal2 = []
-        cal = re.findall("\(\d\|\|\d+\(\)", text)
-        for c in cal:
-            c2 = c.split("||")[1]
-            cal2.append(c2.split("()")[0])
-        val = re.split("\(\d\|\|\d+\(\)", text.strip())
-        x = 0
-
-        self.data = dict()
-        i = 0
-        for c in range(len(cal2)):
-            if c >= 1:
-                self.data[cal2[c]] = val[c + 1]
-
-            else:
-                self.data[cal2[c]] = ''
-        self.exceptions = self.get_exceptions()
-        self.working_days = self.get_days()
-
-    def xldate_to_datetime(self, xldate):
-        temp = datetime.datetime(1899, 12, 30)
-        delta = datetime.timedelta(days=xldate)
-        return temp + delta
-
-    def get_work_pattern(self):
-        pattern = r"\(\d\|\|\d\(\)\("
-        dayName = {2: "Monday", 3: "Tuesday", 4: "Wednesday", 5: "Thursday", 6: "Friday", 7: "Saturday", 1: "Sunday"}
-        tx = self.text.split("(0||VIEW(ShowTotal|Y)())")
-        days = re.split(pattern, tx[0])
-        dys = re.findall(pattern, self.text)
-        lst_dow = []
-        for day, d in zip(days[1:], dys):
-            dow = int(d.replace("(0||", "").replace(")", "").replace("(", ""))
-            starts = re.findall("s\|\d\d\:\d\d", day)
-            finishes = re.findall("f\|\d\d\:\d\d", day)
-
-            day_dict = {'DayOfWeek': dayName[dow], 'WorkTimes': [], 'ifc': None}
-            for s, f in zip(starts, finishes):
-                s_c = datetime.datetime.strptime(s.replace("s|", ""), "%H:%M").time()
-                f_c = datetime.datetime.strptime(f.replace("f|", ""), "%H:%M").time()
-                day_dict['WorkTimes'].append({"Start": s_c, "Finish": f_c})
-            lst_dow.append(day_dict)
-        return (lst_dow)
-
-    def get_exceptions(self):
-        base_datetime = datetime.datetime(1899, 12, 30)
-        excep_dates = re.findall(r"\d{5,}", self.text)
-        exceptions = []
-        for exc in excep_dates:
-            exc = int(exc)
-            delta = datetime.timedelta(exc)
-            exc_date = base_datetime + delta
-            dt = datetime.datetime.fromtimestamp(exc, tz=datetime.timezone.utc)
-            exceptions.append(exc_date)
-        return exceptions
-
-    def get_days(self):
-        if not self.data:
-            return
-        first = re.findall("\(\d\|\|\d\(\)(.*?)\)\)", self.text)
-        days = dict()
-        i = 0
-        for x in first:
-            second = x.split("\x7f\x7f")
-            x = x.replace("(", "").replace(")", "").replace(" ", "").strip()
-            key = str(i + 1)
-            if len(x) > 1:
-                days[key] = (len(x) > 0)
-            else:
-                days[key] = False
-            i += 1
-        self.working_days = days
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+import re
+import datetime
+
+
+class CalendarData:
+    working_days = dict()
+    exceptions = []
+
+    def __init__(self, text):
+        self.text = text
+        cal2 = []
+        cal = re.findall("\(\d\|\|\d+\(\)", text)
+        for c in cal:
+            c2 = c.split("||")[1]
+            cal2.append(c2.split("()")[0])
+        val = re.split("\(\d\|\|\d+\(\)", text.strip())
+        x = 0
+
+        self.data = dict()
+        i = 0
+        for c in range(len(cal2)):
+            if c >= 1:
+                self.data[cal2[c]] = val[c + 1]
+
+            else:
+                self.data[cal2[c]] = ''
+        self.exceptions = self.get_exceptions()
+        self.working_days = self.get_days()
+
+    def xldate_to_datetime(self, xldate):
+        temp = datetime.datetime(1899, 12, 30)
+        delta = datetime.timedelta(days=xldate)
+        return temp + delta
+
+    def get_work_pattern(self):
+        pattern = r"\(\d\|\|\d\(\)\("
+        dayName = {2: "Monday", 3: "Tuesday", 4: "Wednesday", 5: "Thursday", 6: "Friday", 7: "Saturday", 1: "Sunday"}
+        tx = self.text.split("(0||VIEW(ShowTotal|Y)())")
+        days = re.split(pattern, tx[0])
+        dys = re.findall(pattern, self.text)
+        lst_dow = []
+        for day, d in zip(days[1:], dys):
+            dow = int(d.replace("(0||", "").replace(")", "").replace("(", ""))
+            starts = re.findall("s\|\d\d\:\d\d", day)
+            finishes = re.findall("f\|\d\d\:\d\d", day)
+
+            day_dict = {'DayOfWeek': dayName[dow], 'WorkTimes': [], 'ifc': None}
+            for s, f in zip(starts, finishes):
+                s_c = datetime.datetime.strptime(s.replace("s|", ""), "%H:%M").time()
+                f_c = datetime.datetime.strptime(f.replace("f|", ""), "%H:%M").time()
+                day_dict['WorkTimes'].append({"Start": s_c, "Finish": f_c})
+            lst_dow.append(day_dict)
+        return (lst_dow)
+
+    def get_exceptions(self):
+        base_datetime = datetime.datetime(1899, 12, 30)
+        excep_dates = re.findall(r"\d{5,}", self.text)
+        exceptions = []
+        for exc in excep_dates:
+            exc = int(exc)
+            delta = datetime.timedelta(exc)
+            exc_date = base_datetime + delta
+            dt = datetime.datetime.fromtimestamp(exc, tz=datetime.timezone.utc)
+            exceptions.append(exc_date)
+        return exceptions
+
+    def get_days(self):
+        if not self.data:
+            return
+        first = re.findall("\(\d\|\|\d\(\)(.*?)\)\)", self.text)
+        days = dict()
+        i = 0
+        for x in first:
+            second = x.split("\x7f\x7f")
+            x = x.replace("(", "").replace(")", "").replace(" ", "").strip()
+            key = str(i + 1)
+            if len(x) > 1:
+                days[key] = (len(x) > 0)
+            else:
+                days[key] = False
+            i += 1
+        self.working_days = days
         return self.working_days
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/currency.py` & `PyP6Xer-1.15.0/xerparser/model/classes/currency.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,65 +1,65 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class Currency:
-    obj_list = []
-
-    def __init__(self, params):
-        # Unique ID generated by the system.
-        self.curr_id = int(params.get('curr_id')) if params.get('curr_id') else None
-        # The number of decimal places displayed.
-        self.decimal_digit_cnt = int(params.get('decimal_digit_cnt')) if params.get('decimal_digit_cnt') else None
-        # The symbol used to identify each defined currency.
-        self.curr_symbol = params.get('curr_symbol') if params.get('curr_symbol') else None
-        # The decimal symbol displayed.
-        self.decimal_symbol = params.get('decimal_symbol').strip() if params.get('decimal_symbol') else None
-        # The symbol used to group the numbers.
-        self.digit_group_symbol = params.get('digit_group_symbol').strip() if params.get('digit_group_symbol') else None
-        # The symbol used to display a positive currency.
-        self.pos_curr_fmt_type = params.get('pos_curr_fmt_type').strip() if params.get('pos_curr_fmt_type') else None
-        # The symbol used to display a negative currency.
-        self.neg_curr_fmt_type = params.get('neg_curr_fmt_type').strip() if params.get('neg_curr_fmt_type') else None
-        # The names of all defined currencies.
-        self.curr_type = params.get('curr_type').strip()
-        # The identifiers for all currencies defined in Project Management.
-        self.curr_short_name = params.get('curr_short_name').strip() if params.get('curr_short_name') else None
-        # Currency Group Digit Count
-        self.group_digit_cnt = params.get('group_digit_cnt').strip()
-        # The current exchange rate between the selected currency and the base currency.
-        self.base_exch_rate = params.get('base_exch_rate').strip() if params.get('base_exch_rate') else None
-
-        Currency.obj_list.append(self)
-
-    def get_id(self):
-        return self.curr_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.curr_id, self.decimal_digit_cnt, self.curr_symbol, self.decimal_symbol,
-               self.digit_group_symbol, self.pos_curr_fmt_type, self.neg_curr_fmt_type,
-               self.curr_type, self.curr_short_name, self.group_digit_cnt, self.base_exch_rate]
-        return tsv
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.curr_id == id, cls.obj_list))
-        if obj:
-            return obj[0]
-        return obj
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class Currency:
+    obj_list = []
+
+    def __init__(self, params):
+        # Unique ID generated by the system.
+        self.curr_id = int(params.get('curr_id')) if params.get('curr_id') else None
+        # The number of decimal places displayed.
+        self.decimal_digit_cnt = int(params.get('decimal_digit_cnt')) if params.get('decimal_digit_cnt') else None
+        # The symbol used to identify each defined currency.
+        self.curr_symbol = params.get('curr_symbol') if params.get('curr_symbol') else None
+        # The decimal symbol displayed.
+        self.decimal_symbol = params.get('decimal_symbol').strip() if params.get('decimal_symbol') else None
+        # The symbol used to group the numbers.
+        self.digit_group_symbol = params.get('digit_group_symbol').strip() if params.get('digit_group_symbol') else None
+        # The symbol used to display a positive currency.
+        self.pos_curr_fmt_type = params.get('pos_curr_fmt_type').strip() if params.get('pos_curr_fmt_type') else None
+        # The symbol used to display a negative currency.
+        self.neg_curr_fmt_type = params.get('neg_curr_fmt_type').strip() if params.get('neg_curr_fmt_type') else None
+        # The names of all defined currencies.
+        self.curr_type = params.get('curr_type').strip()
+        # The identifiers for all currencies defined in Project Management.
+        self.curr_short_name = params.get('curr_short_name').strip() if params.get('curr_short_name') else None
+        # Currency Group Digit Count
+        self.group_digit_cnt = params.get('group_digit_cnt').strip()
+        # The current exchange rate between the selected currency and the base currency.
+        self.base_exch_rate = params.get('base_exch_rate').strip() if params.get('base_exch_rate') else None
+
+        Currency.obj_list.append(self)
+
+    def get_id(self):
+        return self.curr_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.curr_id, self.decimal_digit_cnt, self.curr_symbol, self.decimal_symbol,
+               self.digit_group_symbol, self.pos_curr_fmt_type, self.neg_curr_fmt_type,
+               self.curr_type, self.curr_short_name, self.group_digit_cnt, self.base_exch_rate]
+        return tsv
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.curr_id == id, cls.obj_list))
+        if obj:
+            return obj[0]
+        return obj
+
+    def __repr__(self):
         return self.curr_short_name + ' ' + str(self.curr_type)
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/fintmpl.py` & `PyP6Xer-1.15.0/xerparser/model/classes/fintmpl.py`

 * *Ordering differences only*

 * *Files 10% similar despite different names*

```diff
@@ -1,38 +1,38 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class FinTmpl:
-
-
-    def __init__(self, params):
-
-        self.fintmpl_id = params.get('fintmpl_id').strip() if params.get('fintmpl_id') else None
-        self.fintmpl_name = params.get('fintmpl_name').strip() if params.get('fintmpl_name') else None
-        self.default_flag = params.get('default_flag').strip() if params.get('default_flag') else None
-
-    def get_id(self):
-        return self.fintmpl_id
-
-    def get_tsv(self):
-        tsv = ["%R", self.fintmpl_id, self.fintmpl_name, self.default_flag]
-        return tsv
-
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class FinTmpl:
+
+
+    def __init__(self, params):
+
+        self.fintmpl_id = params.get('fintmpl_id').strip() if params.get('fintmpl_id') else None
+        self.fintmpl_name = params.get('fintmpl_name').strip() if params.get('fintmpl_name') else None
+        self.default_flag = params.get('default_flag').strip() if params.get('default_flag') else None
+
+    def get_id(self):
+        return self.fintmpl_id
+
+    def get_tsv(self):
+        tsv = ["%R", self.fintmpl_id, self.fintmpl_name, self.default_flag]
+        return tsv
+
+
+    def __repr__(self):
         return self.proc_id + '->' + self.task_id
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/nonwork.py` & `PyP6Xer-1.15.0/xerparser/model/classes/nonwork.py`

 * *Ordering differences only*

 * *Files 17% similar despite different names*

```diff
@@ -1,39 +1,39 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class NonWork:
-
-
-    def __init__(self, params):
-
-        self.nonwork_type_id = params.get('nonwork_type_id').strip() if params.get('nonwork_type_id') else None
-        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
-        self.nonwork_code = params.get('nonwork_code').strip() if params.get('nonwork_code') else None
-        self.nonwork_type = params.get('nonwork_type').strip() if params.get('nonwork_type') else None
-
-    def get_id(self):
-        return self.nonwork_type_id
-
-    def get_tsv(self):
-        tsv = ["%R", self.nonwork_type_id, self.seq_num, self.nonwork_code, self.nonwork_type]
-        return tsv
-
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class NonWork:
+
+
+    def __init__(self, params):
+
+        self.nonwork_type_id = params.get('nonwork_type_id').strip() if params.get('nonwork_type_id') else None
+        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
+        self.nonwork_code = params.get('nonwork_code').strip() if params.get('nonwork_code') else None
+        self.nonwork_type = params.get('nonwork_type').strip() if params.get('nonwork_type') else None
+
+    def get_id(self):
+        return self.nonwork_type_id
+
+    def get_tsv(self):
+        tsv = ["%R", self.nonwork_type_id, self.seq_num, self.nonwork_code, self.nonwork_type]
+        return tsv
+
+
+    def __repr__(self):
         return self.nonwork_type_id + '->' + self.nonwork_type
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/obs.py` & `PyP6Xer-1.15.0/xerparser/model/classes/obs.py`

 * *Ordering differences only*

 * *Files 15% similar despite different names*

```diff
@@ -1,76 +1,76 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class OBS:
-    obj_list = []
-
-    def __init__(self, params):
-        # Unique ID generated by the system.
-        self.obs_id = int(params.get('obs_id').strip()) if params.get('obs_id') else None
-        # The parent OBS value in the OBS hierarchy.
-        self.parent_obs_id = int(params.get('parent_obs_id').strip()) if params.get('parent_obs_id') else None
-        # Global Unique Identifier generated by the system.
-        self.guid = params.get('guid').strip() if params.get('guid') else None
-        # Sequence number used for sorting.
-        self.seq_num = int(params.get('seq_num').strip()) if params.get('seq_num') else None
-        # The name of the person/role in the organization.
-        self.obs_name = params.get('obs_name').strip() if params.get('obs_name') else None
-        # The description of the person/role in the organization.
-        self.obs_descr = params.get('obs_descr').strip() if params.get('obs_descr') else None
-
-        OBS.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.obs_id, self.parent_obs_id, self.guid, self.seq_num,
-               self.obs_name, self.obs_descr]
-        return tsv
-    @classmethod
-    def get_json(cls):
-        root_nodes = list(filter(lambda x: x.parent_obs_id is None, cls.obj_list))
-        # print(root_nodes)
-        json = dict()
-        for node in root_nodes:
-            json["node"] = node
-            json["level"] = 0
-            json["childs"] = cls.get_childs(node, 0)
-        print(json)
-
-    @classmethod
-    def get_childs(cls, node, level):
-        nodes_lst = list(filter(lambda x: x.parent_obs_id == node.obs_id, cls.obj_list))
-        nod = dict()
-        for node in nodes_lst:
-            nod["node"] = node
-            nod["level"] = level + 1
-            children = cls.get_childs(node, level+1)
-            nod["childs"] = children if children else []
-        return nod
-
-    def get_id(self):
-        return self.obs_id
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.obs_id == id, cls.obj_list))
-        if obj:
-            return obj[0]
-        return obj
-
-    def __repr__(self):
-        return self.obs_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class OBS:
+    obj_list = []
+
+    def __init__(self, params):
+        # Unique ID generated by the system.
+        self.obs_id = int(params.get('obs_id').strip()) if params.get('obs_id') else None
+        # The parent OBS value in the OBS hierarchy.
+        self.parent_obs_id = int(params.get('parent_obs_id').strip()) if params.get('parent_obs_id') else None
+        # Global Unique Identifier generated by the system.
+        self.guid = params.get('guid').strip() if params.get('guid') else None
+        # Sequence number used for sorting.
+        self.seq_num = int(params.get('seq_num').strip()) if params.get('seq_num') else None
+        # The name of the person/role in the organization.
+        self.obs_name = params.get('obs_name').strip() if params.get('obs_name') else None
+        # The description of the person/role in the organization.
+        self.obs_descr = params.get('obs_descr').strip() if params.get('obs_descr') else None
+
+        OBS.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.obs_id, self.parent_obs_id, self.guid, self.seq_num,
+               self.obs_name, self.obs_descr]
+        return tsv
+    @classmethod
+    def get_json(cls):
+        root_nodes = list(filter(lambda x: x.parent_obs_id is None, cls.obj_list))
+        # print(root_nodes)
+        json = dict()
+        for node in root_nodes:
+            json["node"] = node
+            json["level"] = 0
+            json["childs"] = cls.get_childs(node, 0)
+        print(json)
+
+    @classmethod
+    def get_childs(cls, node, level):
+        nodes_lst = list(filter(lambda x: x.parent_obs_id == node.obs_id, cls.obj_list))
+        nod = dict()
+        for node in nodes_lst:
+            nod["node"] = node
+            nod["level"] = level + 1
+            children = cls.get_childs(node, level+1)
+            nod["childs"] = children if children else []
+        return nod
+
+    def get_id(self):
+        return self.obs_id
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.obs_id == id, cls.obj_list))
+        if obj:
+            return obj[0]
+        return obj
+
+    def __repr__(self):
+        return self.obs_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/p6codes.py` & `PyP6Xer-1.15.0/xerparser/model/classes/p6codes.py`

 * *Ordering differences only*

 * *Files 23% similar despite different names*

```diff
@@ -1,49 +1,49 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class ActivityStatus:
-
-    Complete = "TK_Complete"
-    InProgress = "TK_Active"
-    NotStarted = "TK_NotStart"
-
-
-class ActivityType:
-
-    Task = "TT_Task"
-    StartMilestone = "TT_Mile"
-    FinishMilestone = "TT_FinMile"
-    LevelOfEffort = "TT_LOE"
-    WBSSummary = "TT_WBS"
-
-
-class RelationshipType:
-
-    FF = "PR_FF"
-    FS = "PR_FS"
-    SS = "PR_SS"
-    SF = "PR_SF"
-
-
-class DurationTypes:
-
-    FixedQuantity = "DT_FixedQty"
-    FixedDurationAndUnits = "DT_FixedDrtn"
-    FixedRate = "DT_FixedRate"
-    FixedDuration = "DT_FixedDUR2"
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class ActivityStatus:
+
+    Complete = "TK_Complete"
+    InProgress = "TK_Active"
+    NotStarted = "TK_NotStart"
+
+
+class ActivityType:
+
+    Task = "TT_Task"
+    StartMilestone = "TT_Mile"
+    FinishMilestone = "TT_FinMile"
+    LevelOfEffort = "TT_LOE"
+    WBSSummary = "TT_WBS"
+
+
+class RelationshipType:
+
+    FF = "PR_FF"
+    FS = "PR_FS"
+    SS = "PR_SS"
+    SF = "PR_SF"
+
+
+class DurationTypes:
+
+    FixedQuantity = "DT_FixedQty"
+    FixedDurationAndUnits = "DT_FixedDrtn"
+    FixedRate = "DT_FixedRate"
+    FixedDuration = "DT_FixedDUR2"
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/pcattype.py` & `PyP6Xer-1.15.0/xerparser/model/classes/pcattype.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,67 +1,67 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class PCatType:
-    obj_list =[]
-
-    def __init__(self, params):
-        # Unique ID generated by the system.
-        self.proj_catg_type_id = int(params.get('proj_catg_type_id').strip()) if params.get(
-            'proj_catg_type_id') else None
-        # The sequence number of this Project Activity Code.
-        self.seq_num = int(params.get('seq_num').strip()) if params.get('seq_num') else None
-        # Sequence number for sorting.
-        self.proj_catg_short_len = params.get('proj_catg_short_len').strip() if params.get(
-            'proj_catg_short_len') else None
-        # Each Activity Code has a list of possible values, any of which can be assigned to an activity. Activity
-        # Codes allow you to classify and categorize activities.
-        self.proj_catg_type = params.get('proj_catg_type').strip() if params.get('proj_catg_type') else None
-        # Identifies the project which owns this Activity Code (if this is a project-level Activity Code).
-        self.export_flag = int(params.get('export_flag')) if params.get('export_flag') else None
-        PCatType.obj_list.append(self)
-
-        # %F	proj_catg_type_id	seq_num	proj_catg_short_len	proj_catg_type	export_flag
-    def get_id(self):
-        return self.proj_catg_type_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.proj_catg_type_id, self.seq_num, self.proj_catg_short_len,
-               self.proj_catg_type, self.export_flag]
-        return tsv
-    @classmethod
-    def find_by_id(cls, id):
-        """ Function to search list of activity code type by an ID
-
-        Args:
-            id: Unique ID generated by the system.
-
-        Returns: ActType that matches the ID
-
-        """
-        obj = list(filter(lambda x: x.proj_catg_type_id == id, cls.obj_list))
-        if len(obj) > 0:
-            return obj[0]
-        else:
-            obj = None
-        return obj
-
-
-    def __repr__(self):
-        return self.proj_catg_type_id
-
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class PCatType:
+    obj_list =[]
+
+    def __init__(self, params):
+        # Unique ID generated by the system.
+        self.proj_catg_type_id = int(params.get('proj_catg_type_id').strip()) if params.get(
+            'proj_catg_type_id') else None
+        # The sequence number of this Project Activity Code.
+        self.seq_num = int(params.get('seq_num').strip()) if params.get('seq_num') else None
+        # Sequence number for sorting.
+        self.proj_catg_short_len = params.get('proj_catg_short_len').strip() if params.get(
+            'proj_catg_short_len') else None
+        # Each Activity Code has a list of possible values, any of which can be assigned to an activity. Activity
+        # Codes allow you to classify and categorize activities.
+        self.proj_catg_type = params.get('proj_catg_type').strip() if params.get('proj_catg_type') else None
+        # Identifies the project which owns this Activity Code (if this is a project-level Activity Code).
+        self.export_flag = int(params.get('export_flag')) if params.get('export_flag') else None
+        PCatType.obj_list.append(self)
+
+        # %F	proj_catg_type_id	seq_num	proj_catg_short_len	proj_catg_type	export_flag
+    def get_id(self):
+        return self.proj_catg_type_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.proj_catg_type_id, self.seq_num, self.proj_catg_short_len,
+               self.proj_catg_type, self.export_flag]
+        return tsv
+    @classmethod
+    def find_by_id(cls, id):
+        """ Function to search list of activity code type by an ID
+
+        Args:
+            id: Unique ID generated by the system.
+
+        Returns: ActType that matches the ID
+
+        """
+        obj = list(filter(lambda x: x.proj_catg_type_id == id, cls.obj_list))
+        if len(obj) > 0:
+            return obj[0]
+        else:
+            obj = None
+        return obj
+
+
+    def __repr__(self):
+        return self.proj_catg_type_id
+
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/pcatval.py` & `PyP6Xer-1.15.0/xerparser/model/classes/pcatval.py`

 * *Ordering differences only*

 * *Files 10% similar despite different names*

```diff
@@ -1,43 +1,43 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class PCatVal:
-
-    def __init__(self, params):
-        # %F	proj_catg_id	proj_catg_type_id	seq_num	proj_catg_short_name	parent_proj_catg_id	proj_catg_name
-        self.proj_catg_id = params.get('proj_catg_id').strip() if params.get('proj_catg_id') else None
-        self.proj_catg_type_id = params.get('proj_catg_type_id').strip() if params.get('proj_catg_type_id') else None
-        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
-        self.proj_catg_short_name = params.get('proj_catg_short_name').strip() if params.get(
-            'proj_catg_short_name') else None
-        self.parent_proj_catg_id = params.get('parent_proj_catg_id').strip() if params.get(
-            'parent_proj_catg_id') else None
-        self.proj_catg_name = params.get('proj_catg_name').strip() if params.get('proj_catg_name') else None
-
-
-    def get_id(self):
-        return self.proj_catg_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.proj_catg_id, self.proj_catg_type_id, self.seq_num, self.proj_catg_short_name,
-               self.parent_proj_catg_id, self.proj_catg_name]
-        return tsv
-
-    def __repr__(self):
-        return self.proj_catg_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class PCatVal:
+
+    def __init__(self, params):
+        # %F	proj_catg_id	proj_catg_type_id	seq_num	proj_catg_short_name	parent_proj_catg_id	proj_catg_name
+        self.proj_catg_id = params.get('proj_catg_id').strip() if params.get('proj_catg_id') else None
+        self.proj_catg_type_id = params.get('proj_catg_type_id').strip() if params.get('proj_catg_type_id') else None
+        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
+        self.proj_catg_short_name = params.get('proj_catg_short_name').strip() if params.get(
+            'proj_catg_short_name') else None
+        self.parent_proj_catg_id = params.get('parent_proj_catg_id').strip() if params.get(
+            'parent_proj_catg_id') else None
+        self.proj_catg_name = params.get('proj_catg_name').strip() if params.get('proj_catg_name') else None
+
+
+    def get_id(self):
+        return self.proj_catg_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.proj_catg_id, self.proj_catg_type_id, self.seq_num, self.proj_catg_short_name,
+               self.parent_proj_catg_id, self.proj_catg_name]
+        return tsv
+
+    def __repr__(self):
+        return self.proj_catg_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/projcat.py` & `PyP6Xer-1.15.0/xerparser/model/classes/projcat.py`

 * *Ordering differences only*

 * *Files 21% similar despite different names*

```diff
@@ -1,37 +1,37 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class ProjCat:
-
-    def __init__(self, params):
-        # %F	proj_id	proj_catg_type_id	proj_catg_id
-        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
-        self.proj_catg_type_id = params.get('proj_catg_type_id').strip() if params.get('proj_catg_type_id') else None
-        self.proj_catg_id = params.get('proj_catg_id').strip() if params.get('proj_catg_id') else None
-
-
-    def get_id(self):
-        return self.proj_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.proj_id, self.proj_catg_type_id, self.proj_catg_id]
-        return tsv
-
-    def __repr__(self):
-        return self.proj_catg_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class ProjCat:
+
+    def __init__(self, params):
+        # %F	proj_id	proj_catg_type_id	proj_catg_id
+        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
+        self.proj_catg_type_id = params.get('proj_catg_type_id').strip() if params.get('proj_catg_type_id') else None
+        self.proj_catg_id = params.get('proj_catg_id').strip() if params.get('proj_catg_id') else None
+
+
+    def get_id(self):
+        return self.proj_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.proj_id, self.proj_catg_type_id, self.proj_catg_id]
+        return tsv
+
+    def __repr__(self):
+        return self.proj_catg_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/project.py` & `PyP6Xer-1.15.0/xerparser/model/classes/project.py`

 * *Ordering differences only*

 * *Files 7% similar despite different names*

```diff
@@ -1,135 +1,135 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.wbs import WBS
-from xerparser.model.tasks import Tasks
-from xerparser.model.wbss import WBSs
-
-class Project:
-
-    def __init__(self, params, data):
-
-        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
-        self.fy_start_month_num = params.get('fy_start_month_num').strip() if params.get('fy_start_month_num') else None
-        self.rsrc_self_add_flag = params.get('rsrc_self_add_flag').strip() if params.get('rsrc_self_add_flag') else None
-        self.allow_complete_flag = params.get('allow_complete_flag').strip() if params.get('allow_complete_flag') else None
-        self.rsrc_multi_assign_flag = params.get('rsrc_multi_assign_flag').strip() if params.get('rsrc_multi_assign_flag') else None
-        self.checkout_flag = params.get('checkout_flag').strip() if params.get('checkout_flag') else None
-        self.project_flag = params.get('project_flag').strip() if params.get('project_flag') else None
-        self.step_complete_flag = params.get('step_complete_flag').strip() if params.get('step_complete_flag') else None
-        self.cost_qty_recalc_flag = params.get('cost_qty_recalc_flag').strip() if params.get('cost_qty_recalc_flag') else None
-        self.batch_sum_flag = params.get('batch_sum_flag').strip() if params.get('batch_sum_flag') else None
-        self.name_sep_char = params.get('name_sep_char').strip() if params.get('name_sep_char') else None
-        self.def_complete_pct_type = params.get('def_complete_pct_type').strip() if params.get('def_complete_pct_type') else None
-        self.proj_short_name = params.get('proj_short_name').strip() if params.get('proj_short_name') else None
-        self.acct_id = params.get('acct_id').strip() if params.get('acct_id') else None
-        self.orig_proj_id = params.get('orig_proj_id').strip() if params.get('orig_proj_id') else None
-        self.source_proj_id = params.get('source_proj_id').strip() if params.get('source_proj_id') else None
-        self.base_type_id = params.get('base_type_id').strip() if params.get('base_type_id') else None
-        self.clndr_id = params.get('clndr_id').strip() if params.get('clndr_id') else None
-        self.sum_base_proj_id = params.get('sum_base_proj_id').strip() if params.get('sum_base_proj_id') else None
-        self.task_code_base = params.get('task_code_base').strip() if params.get('task_code_base') else None
-        self.task_code_step = params.get('task_code_step').strip() if params.get('task_code_step') else None
-        self.priority_num = params.get('priority_num').strip() if params.get('priority_num') else None
-        self.wbs_max_sum_level = params.get('wbs_max_sum_level').strip() if params.get('wbs_max_sum_level') else None
-        self.strgy_priority_num = params.get('strgy_priority_num').strip() if params.get('strgy_priority_num') else None
-        self.last_checksum = params.get('last_checksum').strip() if params.get('last_checksum') else None
-        self.critical_drtn_hr_cnt = params.get('critical_drtn_hr_cnt').strip() if params.get('critical_drtn_hr_cnt') else None
-        self.def_cost_per_qty = params.get('def_cost_per_qty').strip() if params.get('def_cost_per_qty') else None
-        self.last_recalc_date = params.get('last_recalc_date').strip() if params.get('last_recalc_date') else None
-        self.plan_start_date = params.get('plan_start_date').strip() if params.get('plan_start_date') else None
-        self.plan_end_date = params.get('plan_end_date').strip() if params.get('plan_end_date') else None
-        self.scd_end_date = params.get('scd_end_date').strip() if params.get('scd_end_date') else None
-        self.add_date = params.get('add_date').strip() if params.get('add_date') else None
-        self.last_tasksum_date = params.get('last_tasksum_date').strip() if params.get('last_tasksum_date') else None
-        self.fcst_start_date = params.get('fcst_start_date').strip() if params.get('fcst_start_date') else None
-        self.def_duration_type = params.get('def_duration_type').strip() if params.get('def_duration_type') else None
-        self.task_code_prefix = params.get('task_code_prefix').strip() if params.get('task_code_prefix') else None
-        self.guid = params.get('guid').strip() if params.get('guid') else None
-        self.def_qty_type = params.get('def_qty_type').strip() if params.get('def_qty_type') else None
-        self.add_by_name = params.get('add_by_name').strip() if params.get('add_by_name') else None
-        self.web_local_root_path = params.get('web_local_root_path').strip() if params.get('web_local_root_path') else None
-        self.proj_url = params.get('proj_url').strip() if params.get('proj_url') else None
-        self.def_rate_type = params.get('def_rate_type').strip() if params.get('def_rate_type') else None
-        self.add_act_remain_flag = params.get('add_act_remain_flag').strip() if params.get('add_act_remain_flag') else None
-        self.act_this_per_link_flag = params.get('act_this_per_link_flag').strip() if params.get('act_this_per_link_flag') else None
-        self.def_task_type = params.get('def_task_type').strip() if params.get('def_task_type') else None
-        self.act_pct_link_flag = params.get('act_pct_link_flag').strip() if params.get('act_pct_link_flag') else None
-        self.critical_path_type = params.get('critical_path_type').strip() if params.get('critical_path_type') else None
-        self.task_code_prefix_flag = params.get('task_code_prefix_flag').strip() if params.get('task_code_prefix_flag') else None
-        self.def_rollup_dates_flag = params.get('def_rollup_dates_flag').strip() if params.get('def_rollup_dates_flag') else None
-        self.use_project_baseline_flag = params.get('use_project_baseline_flag').strip() if params.get('use_project_baseline_flag') else None
-        self.rem_target_link_flag = params.get('rem_target_link_flag').strip() if params.get('rem_target_link_flag') else None
-        self.reset_planned_flag = params.get('reset_planned_flag').strip() if params.get('reset_planned_flag') else None
-        self.allow_neg_act_flag = params.get('allow_neg_act_flag').strip() if params.get('allow_neg_act_flag') else None
-        self.sum_assign_level = params.get('sum_assign_level').strip() if params.get('sum_assign_level') else None
-        self.last_fin_dates_id = params.get('last_fin_dates_id').strip() if params.get('last_fin_dates_id') else None
-        self.last_baseline_update_date = params.get('last_fin_dates_id').strip() if params.get('last_fin_dates_id') else None
-        self.cr_external_key = params.get('cr_external_key').strip() if params.get('cr_external_key') else None
-        self.apply_actuals_date = params.get('apply_actuals_date').strip() if params.get('apply_actuals_date') else None
-        self.location_id = params.get('location_id') if params.get('location_id') else None
-        self.loaded_scope_level = params.get('loaded_scope_level').strip() if params.get('loaded_scope_level') else None
-        self.export_flag = params.get('export_flag').strip() if params.get('export_flag') else None
-        self.new_fin_dates_id = params.get('new_fin_dates_id').strip() if params.get('new_fin_dates_id') else None
-        self.baselines_to_export = params.get('baselines_to_export').strip() if params.get('baselines_to_export') else None
-        self.baseline_names_to_export = params.get('baseline_names_to_export').strip() if params.get('baseline_names_to_export') else None
-        self.next_data_date = params.get('next_data_date').strip() if params.get('next_data_date') else None
-        self.close_period_flag = params.get('close_period_flag').strip() if params.get('close_period_flag') else None
-        self.sum_refresh_date = params.get('sum_refresh_date').strip() if params.get('sum_refresh_date') else None
-        self.trsrcsum_loaded = params.get('trsrcsum_loaded').strip() if params.get('trsrcsum_loaded') else None
-        self.fintmpl_id = int(params.get('fintmpl_id').strip()) if params.get('fintmpl_id') else None
-        self.sumtask_loaded = params.get('sumtask_loaded').strip() if params.get('sumtask_loaded') else None
-        self.data = data
-
-    @property
-    def id(self):
-        return self.proj_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.proj_id, self.fy_start_month_num, self.rsrc_self_add_flag,
-               self.allow_complete_flag, self.rsrc_multi_assign_flag, self.checkout_flag,
-               self.project_flag, self.step_complete_flag, self.cost_qty_recalc_flag,
-               self.batch_sum_flag, self.name_sep_char, self.def_complete_pct_type, self.proj_short_name,
-               self.acct_id, self.orig_proj_id, self.source_proj_id, self.base_type_id, self.clndr_id,
-               self.sum_base_proj_id, self.task_code_base, self.task_code_step, self.priority_num,
-               self.wbs_max_sum_level, self.strgy_priority_num, self.last_checksum, self.critical_drtn_hr_cnt,
-               self.def_cost_per_qty, self.last_recalc_date, self.plan_start_date, self.plan_end_date,
-               self.scd_end_date, self.add_date, self.last_tasksum_date, self.fcst_start_date, self.def_duration_type,
-               self.task_code_prefix, self.guid, self.def_qty_type, self.add_by_name, self.web_local_root_path,
-               self.proj_url, self.def_rate_type, self.add_act_remain_flag, self.act_this_per_link_flag,
-               self.def_task_type, self.act_pct_link_flag, self.critical_path_type, self.task_code_prefix_flag,
-               self.def_rollup_dates_flag, self.use_project_baseline_flag, self.rem_target_link_flag,
-               self.reset_planned_flag, self.allow_neg_act_flag, self.sum_assign_level, self.last_fin_dates_id,
-               self.last_baseline_update_date, self.cr_external_key, self.apply_actuals_date, self.fintmpl_id,
-               self.location_id, self.loaded_scope_level, self.export_flag, self.new_fin_dates_id,
-               self.baselines_to_export, self.baseline_names_to_export, self.next_data_date, self.close_period_flag,
-               self.sum_refresh_date, self.trsrcsum_loaded, self.sumtask_loaded]
-        return tsv
-
-    @property
-    def activities(self):
-        return self.data.tasks.get_by_project(self.proj_id)
-
-    @property
-    def wbss(self):
-        # wbss = WBSs()
-        return self.data.wbss.get_by_project(self.proj_id)
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.wbs import WBS
+from xerparser.model.tasks import Tasks
+from xerparser.model.wbss import WBSs
+
+class Project:
+
+    def __init__(self, params, data):
+
+        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
+        self.fy_start_month_num = params.get('fy_start_month_num').strip() if params.get('fy_start_month_num') else None
+        self.rsrc_self_add_flag = params.get('rsrc_self_add_flag').strip() if params.get('rsrc_self_add_flag') else None
+        self.allow_complete_flag = params.get('allow_complete_flag').strip() if params.get('allow_complete_flag') else None
+        self.rsrc_multi_assign_flag = params.get('rsrc_multi_assign_flag').strip() if params.get('rsrc_multi_assign_flag') else None
+        self.checkout_flag = params.get('checkout_flag').strip() if params.get('checkout_flag') else None
+        self.project_flag = params.get('project_flag').strip() if params.get('project_flag') else None
+        self.step_complete_flag = params.get('step_complete_flag').strip() if params.get('step_complete_flag') else None
+        self.cost_qty_recalc_flag = params.get('cost_qty_recalc_flag').strip() if params.get('cost_qty_recalc_flag') else None
+        self.batch_sum_flag = params.get('batch_sum_flag').strip() if params.get('batch_sum_flag') else None
+        self.name_sep_char = params.get('name_sep_char').strip() if params.get('name_sep_char') else None
+        self.def_complete_pct_type = params.get('def_complete_pct_type').strip() if params.get('def_complete_pct_type') else None
+        self.proj_short_name = params.get('proj_short_name').strip() if params.get('proj_short_name') else None
+        self.acct_id = params.get('acct_id').strip() if params.get('acct_id') else None
+        self.orig_proj_id = params.get('orig_proj_id').strip() if params.get('orig_proj_id') else None
+        self.source_proj_id = params.get('source_proj_id').strip() if params.get('source_proj_id') else None
+        self.base_type_id = params.get('base_type_id').strip() if params.get('base_type_id') else None
+        self.clndr_id = params.get('clndr_id').strip() if params.get('clndr_id') else None
+        self.sum_base_proj_id = params.get('sum_base_proj_id').strip() if params.get('sum_base_proj_id') else None
+        self.task_code_base = params.get('task_code_base').strip() if params.get('task_code_base') else None
+        self.task_code_step = params.get('task_code_step').strip() if params.get('task_code_step') else None
+        self.priority_num = params.get('priority_num').strip() if params.get('priority_num') else None
+        self.wbs_max_sum_level = params.get('wbs_max_sum_level').strip() if params.get('wbs_max_sum_level') else None
+        self.strgy_priority_num = params.get('strgy_priority_num').strip() if params.get('strgy_priority_num') else None
+        self.last_checksum = params.get('last_checksum').strip() if params.get('last_checksum') else None
+        self.critical_drtn_hr_cnt = params.get('critical_drtn_hr_cnt').strip() if params.get('critical_drtn_hr_cnt') else None
+        self.def_cost_per_qty = params.get('def_cost_per_qty').strip() if params.get('def_cost_per_qty') else None
+        self.last_recalc_date = params.get('last_recalc_date').strip() if params.get('last_recalc_date') else None
+        self.plan_start_date = params.get('plan_start_date').strip() if params.get('plan_start_date') else None
+        self.plan_end_date = params.get('plan_end_date').strip() if params.get('plan_end_date') else None
+        self.scd_end_date = params.get('scd_end_date').strip() if params.get('scd_end_date') else None
+        self.add_date = params.get('add_date').strip() if params.get('add_date') else None
+        self.last_tasksum_date = params.get('last_tasksum_date').strip() if params.get('last_tasksum_date') else None
+        self.fcst_start_date = params.get('fcst_start_date').strip() if params.get('fcst_start_date') else None
+        self.def_duration_type = params.get('def_duration_type').strip() if params.get('def_duration_type') else None
+        self.task_code_prefix = params.get('task_code_prefix').strip() if params.get('task_code_prefix') else None
+        self.guid = params.get('guid').strip() if params.get('guid') else None
+        self.def_qty_type = params.get('def_qty_type').strip() if params.get('def_qty_type') else None
+        self.add_by_name = params.get('add_by_name').strip() if params.get('add_by_name') else None
+        self.web_local_root_path = params.get('web_local_root_path').strip() if params.get('web_local_root_path') else None
+        self.proj_url = params.get('proj_url').strip() if params.get('proj_url') else None
+        self.def_rate_type = params.get('def_rate_type').strip() if params.get('def_rate_type') else None
+        self.add_act_remain_flag = params.get('add_act_remain_flag').strip() if params.get('add_act_remain_flag') else None
+        self.act_this_per_link_flag = params.get('act_this_per_link_flag').strip() if params.get('act_this_per_link_flag') else None
+        self.def_task_type = params.get('def_task_type').strip() if params.get('def_task_type') else None
+        self.act_pct_link_flag = params.get('act_pct_link_flag').strip() if params.get('act_pct_link_flag') else None
+        self.critical_path_type = params.get('critical_path_type').strip() if params.get('critical_path_type') else None
+        self.task_code_prefix_flag = params.get('task_code_prefix_flag').strip() if params.get('task_code_prefix_flag') else None
+        self.def_rollup_dates_flag = params.get('def_rollup_dates_flag').strip() if params.get('def_rollup_dates_flag') else None
+        self.use_project_baseline_flag = params.get('use_project_baseline_flag').strip() if params.get('use_project_baseline_flag') else None
+        self.rem_target_link_flag = params.get('rem_target_link_flag').strip() if params.get('rem_target_link_flag') else None
+        self.reset_planned_flag = params.get('reset_planned_flag').strip() if params.get('reset_planned_flag') else None
+        self.allow_neg_act_flag = params.get('allow_neg_act_flag').strip() if params.get('allow_neg_act_flag') else None
+        self.sum_assign_level = params.get('sum_assign_level').strip() if params.get('sum_assign_level') else None
+        self.last_fin_dates_id = params.get('last_fin_dates_id').strip() if params.get('last_fin_dates_id') else None
+        self.last_baseline_update_date = params.get('last_fin_dates_id').strip() if params.get('last_fin_dates_id') else None
+        self.cr_external_key = params.get('cr_external_key').strip() if params.get('cr_external_key') else None
+        self.apply_actuals_date = params.get('apply_actuals_date').strip() if params.get('apply_actuals_date') else None
+        self.location_id = params.get('location_id') if params.get('location_id') else None
+        self.loaded_scope_level = params.get('loaded_scope_level').strip() if params.get('loaded_scope_level') else None
+        self.export_flag = params.get('export_flag').strip() if params.get('export_flag') else None
+        self.new_fin_dates_id = params.get('new_fin_dates_id').strip() if params.get('new_fin_dates_id') else None
+        self.baselines_to_export = params.get('baselines_to_export').strip() if params.get('baselines_to_export') else None
+        self.baseline_names_to_export = params.get('baseline_names_to_export').strip() if params.get('baseline_names_to_export') else None
+        self.next_data_date = params.get('next_data_date').strip() if params.get('next_data_date') else None
+        self.close_period_flag = params.get('close_period_flag').strip() if params.get('close_period_flag') else None
+        self.sum_refresh_date = params.get('sum_refresh_date').strip() if params.get('sum_refresh_date') else None
+        self.trsrcsum_loaded = params.get('trsrcsum_loaded').strip() if params.get('trsrcsum_loaded') else None
+        self.fintmpl_id = int(params.get('fintmpl_id').strip()) if params.get('fintmpl_id') else None
+        self.sumtask_loaded = params.get('sumtask_loaded').strip() if params.get('sumtask_loaded') else None
+        self.data = data
+
+    @property
+    def id(self):
+        return self.proj_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.proj_id, self.fy_start_month_num, self.rsrc_self_add_flag,
+               self.allow_complete_flag, self.rsrc_multi_assign_flag, self.checkout_flag,
+               self.project_flag, self.step_complete_flag, self.cost_qty_recalc_flag,
+               self.batch_sum_flag, self.name_sep_char, self.def_complete_pct_type, self.proj_short_name,
+               self.acct_id, self.orig_proj_id, self.source_proj_id, self.base_type_id, self.clndr_id,
+               self.sum_base_proj_id, self.task_code_base, self.task_code_step, self.priority_num,
+               self.wbs_max_sum_level, self.strgy_priority_num, self.last_checksum, self.critical_drtn_hr_cnt,
+               self.def_cost_per_qty, self.last_recalc_date, self.plan_start_date, self.plan_end_date,
+               self.scd_end_date, self.add_date, self.last_tasksum_date, self.fcst_start_date, self.def_duration_type,
+               self.task_code_prefix, self.guid, self.def_qty_type, self.add_by_name, self.web_local_root_path,
+               self.proj_url, self.def_rate_type, self.add_act_remain_flag, self.act_this_per_link_flag,
+               self.def_task_type, self.act_pct_link_flag, self.critical_path_type, self.task_code_prefix_flag,
+               self.def_rollup_dates_flag, self.use_project_baseline_flag, self.rem_target_link_flag,
+               self.reset_planned_flag, self.allow_neg_act_flag, self.sum_assign_level, self.last_fin_dates_id,
+               self.last_baseline_update_date, self.cr_external_key, self.apply_actuals_date, self.fintmpl_id,
+               self.location_id, self.loaded_scope_level, self.export_flag, self.new_fin_dates_id,
+               self.baselines_to_export, self.baseline_names_to_export, self.next_data_date, self.close_period_flag,
+               self.sum_refresh_date, self.trsrcsum_loaded, self.sumtask_loaded]
+        return tsv
+
+    @property
+    def activities(self):
+        return self.data.tasks.get_by_project(self.proj_id)
+
+    @property
+    def wbss(self):
+        # wbss = WBSs()
+        return self.data.wbss.get_by_project(self.proj_id)
+
+    def __repr__(self):
         return self.proj_short_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/rcattype.py` & `PyP6Xer-1.15.0/xerparser/model/classes/rcattype.py`

 * *Ordering differences only*

 * *Files 11% similar despite different names*

```diff
@@ -1,46 +1,46 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class RCatType:
-    obj_list = []
-
-    def __init__(self, params):
-        self.rsrc_catg_type_id = int(params.get('rsrc_catg_type_id').strip()) if params.get('rsrc_catg_type_id') else None
-        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
-        self.rsrc_catg_short_len = params.get('rsrc_catg_short_len').strip() if params.get('rsrc_catg_short_len') else None
-        self.rsrc_catg_type = params.get('rsrc_catg_type').strip() if params.get('rsrc_catg_type') else None
-        RCatType.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.rsrc_catg_type_id,self.seq_num, self.rsrc_catg_short_len,
-               self.rsrc_catg_type]
-        return tsv
-
-    def get_id(self):
-        return self.rsrc_catg_type_id
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.rsrc_catg_type_id == id, cls.obj_list))
-        if obj:
-            return obj[0]
-        return obj
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class RCatType:
+    obj_list = []
+
+    def __init__(self, params):
+        self.rsrc_catg_type_id = int(params.get('rsrc_catg_type_id').strip()) if params.get('rsrc_catg_type_id') else None
+        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
+        self.rsrc_catg_short_len = params.get('rsrc_catg_short_len').strip() if params.get('rsrc_catg_short_len') else None
+        self.rsrc_catg_type = params.get('rsrc_catg_type').strip() if params.get('rsrc_catg_type') else None
+        RCatType.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.rsrc_catg_type_id,self.seq_num, self.rsrc_catg_short_len,
+               self.rsrc_catg_type]
+        return tsv
+
+    def get_id(self):
+        return self.rsrc_catg_type_id
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.rsrc_catg_type_id == id, cls.obj_list))
+        if obj:
+            return obj[0]
+        return obj
+
+    def __repr__(self):
         return self.rsrc_catg_type
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/rcatval.py` & `PyP6Xer-1.15.0/xerparser/model/classes/rcatval.py`

 * *Ordering differences only*

 * *Files 6% similar despite different names*

```diff
@@ -1,47 +1,47 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class RCatVal:
-    obj_list = []
-
-    def __init__(self, params):
-        self.rsrc_catg_id = params.get('rsrc_catg_id').strip() if params.get('rsrc_catg_id') else None
-        self.rsrc_catg_type_id = params.get('rsrc_catg_type_id').strip() if params.get('rsrc_catg_type_id') else None
-        self.rsrc_catg_short_name = params.get('rsrc_catg_short_name').strip() if params.get('rsrc_catg_short_name') else None
-        self.rsrc_catg_name = params.get('rsrc_catg_name').strip() if params.get('rsrc_catg_name') else None
-        self.parent_rsrc_catg_id = params.get('parent_rsrc_catg_id').strip() if params.get('parent_rsrc_catg_id') else None
-        RCatVal.obj_list.append(self)
-
-    def get_id(self):
-        return self.rsrc_catg_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.rsrc_catg_id, self.rsrc_catg_type_id, self.rsrc_catg_short_name,
-               self.rsrc_catg_name, self.parent_rsrc_catg_id]
-        return tsv
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.rsrc_catg_id == id, cls.obj_list))
-        if obj:
-            return obj[0]
-        return obj
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class RCatVal:
+    obj_list = []
+
+    def __init__(self, params):
+        self.rsrc_catg_id = params.get('rsrc_catg_id').strip() if params.get('rsrc_catg_id') else None
+        self.rsrc_catg_type_id = params.get('rsrc_catg_type_id').strip() if params.get('rsrc_catg_type_id') else None
+        self.rsrc_catg_short_name = params.get('rsrc_catg_short_name').strip() if params.get('rsrc_catg_short_name') else None
+        self.rsrc_catg_name = params.get('rsrc_catg_name').strip() if params.get('rsrc_catg_name') else None
+        self.parent_rsrc_catg_id = params.get('parent_rsrc_catg_id').strip() if params.get('parent_rsrc_catg_id') else None
+        RCatVal.obj_list.append(self)
+
+    def get_id(self):
+        return self.rsrc_catg_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.rsrc_catg_id, self.rsrc_catg_type_id, self.rsrc_catg_short_name,
+               self.rsrc_catg_name, self.parent_rsrc_catg_id]
+        return tsv
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.rsrc_catg_id == id, cls.obj_list))
+        if obj:
+            return obj[0]
+        return obj
+
+    def __repr__(self):
         return self.rsrc_catg_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/role.py` & `PyP6Xer-1.15.0/xerparser/model/classes/role.py`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,44 +1,44 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class Role:
-    obj_list = []
-
-    def __init__(self, params):
-        self.role_id = int(params.get('role_id')) if params.get('role_id') else None
-        self.parent_role_id = int(params.get('parent_role_id')) if params.get('parent_role_id') else None
-        self.seq_num = int(params.get('seq_num')) if params.get('seq_num') else None
-        self.role_name = params.get('role_name') if params.get('role_name') else None
-        self.role_short_name = params.get('role_short_name') if params.get('role_short_name') else None
-        self.pobs_id = params.get('pobs_id') if params.get('pobs_id') else None
-        self.def_cost_qty_link_flag = params.get('def_cost_qty_link_flag') if params.get('def_cost_qty_link_flag') else None
-        self.cost_qty_type = params.get('cost_qty_type') if params.get('cost_qty_type') else None
-        self.role_descr = params.get('role_descr') if params.get('role_descr') else None
-        self.last_checksum = params.get('role_descr') if params.get('role_descr') else None
-
-        Role.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.role_id, self.parent_role_id, self.seq_num, self.role_name,
-               self.role_short_name, self.pobs_id, self.def_cost_qty_link_flag, self.cost_qty_type,
-               self.role_descr, self.last_checksum]
-        return tsv
-
-    def __repr__(self):
-        return self.role_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class Role:
+    obj_list = []
+
+    def __init__(self, params):
+        self.role_id = int(params.get('role_id')) if params.get('role_id') else None
+        self.parent_role_id = int(params.get('parent_role_id')) if params.get('parent_role_id') else None
+        self.seq_num = int(params.get('seq_num')) if params.get('seq_num') else None
+        self.role_name = params.get('role_name') if params.get('role_name') else None
+        self.role_short_name = params.get('role_short_name') if params.get('role_short_name') else None
+        self.pobs_id = params.get('pobs_id') if params.get('pobs_id') else None
+        self.def_cost_qty_link_flag = params.get('def_cost_qty_link_flag') if params.get('def_cost_qty_link_flag') else None
+        self.cost_qty_type = params.get('cost_qty_type') if params.get('cost_qty_type') else None
+        self.role_descr = params.get('role_descr') if params.get('role_descr') else None
+        self.last_checksum = params.get('role_descr') if params.get('role_descr') else None
+
+        Role.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.role_id, self.parent_role_id, self.seq_num, self.role_name,
+               self.role_short_name, self.pobs_id, self.def_cost_qty_link_flag, self.cost_qty_type,
+               self.role_descr, self.last_checksum]
+        return tsv
+
+    def __repr__(self):
+        return self.role_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/rolerate.py` & `PyP6Xer-1.15.0/xerparser/model/classes/rolerate.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,55 +1,55 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-import locale
-
-class RoleRate:
-    obj_list = []
-
-    def __init__(self, params):
-        self.role_rate_id = int(params.get('role_rate_id').strip()) if params.get('role_rate_id') else None
-        self.role_id = int(params.get('role_id').strip()) if params.get('role_id') else None
-        self.cost_per_qty = locale.atof(params.get('cost_per_qty').strip()) if params.get('cost_per_qty') else None
-        self.cost_per_qty2 = locale.atof(params.get('cost_per_qty2').strip())if params.get('cost_per_qty2') else None
-        self.cost_per_qty3 = locale.atof(params.get('cost_per_qty3').strip()) if params.get('cost_per_qty3') else None
-        self.cost_per_qty4 = locale.atof(params.get('cost_per_qty4').strip()) if params.get('cost_per_qty4') else None
-        self.cost_per_qty5 = locale.atof(params.get('cost_per_qty5').strip()) if params.get('cost_per_qty5') else None
-
-        RoleRate.obj_list.append(self)
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.role_rate_id == id, cls.obj_list))[0]
-        return obj
-
-    def get_tsv(self):
-        tsv = ['%R', self.role_rate_id, self.role_id, self.cost_per_qty, self.cost_per_qty2,
-               self.cost_per_qty3, self.cost_per_qty4, self.cost_per_qty5]
-        return tsv
-
-    @classmethod
-    def find_by_role_id(cls, id):
-        obj = list(filter(lambda x: x.role_id == id, cls.obj_list))
-        if len(obj) > 0:
-            obj = obj[0]
-        else:
-            obj = None
-        return obj
-
-    def __repr__(self):
-        return str(self.role_rate_id)
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+import locale
+
+class RoleRate:
+    obj_list = []
+
+    def __init__(self, params):
+        self.role_rate_id = int(params.get('role_rate_id').strip()) if params.get('role_rate_id') else None
+        self.role_id = int(params.get('role_id').strip()) if params.get('role_id') else None
+        self.cost_per_qty = locale.atof(params.get('cost_per_qty').strip()) if params.get('cost_per_qty') else None
+        self.cost_per_qty2 = locale.atof(params.get('cost_per_qty2').strip())if params.get('cost_per_qty2') else None
+        self.cost_per_qty3 = locale.atof(params.get('cost_per_qty3').strip()) if params.get('cost_per_qty3') else None
+        self.cost_per_qty4 = locale.atof(params.get('cost_per_qty4').strip()) if params.get('cost_per_qty4') else None
+        self.cost_per_qty5 = locale.atof(params.get('cost_per_qty5').strip()) if params.get('cost_per_qty5') else None
+
+        RoleRate.obj_list.append(self)
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.role_rate_id == id, cls.obj_list))[0]
+        return obj
+
+    def get_tsv(self):
+        tsv = ['%R', self.role_rate_id, self.role_id, self.cost_per_qty, self.cost_per_qty2,
+               self.cost_per_qty3, self.cost_per_qty4, self.cost_per_qty5]
+        return tsv
+
+    @classmethod
+    def find_by_role_id(cls, id):
+        obj = list(filter(lambda x: x.role_id == id, cls.obj_list))
+        if len(obj) > 0:
+            obj = obj[0]
+        else:
+            obj = None
+        return obj
+
+    def __repr__(self):
+        return str(self.role_rate_id)
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/rsrccurv.py` & `PyP6Xer-1.15.0/xerparser/model/classes/rsrccurv.py`

 * *Ordering differences only*

 * *Files 9% similar despite different names*

```diff
@@ -1,66 +1,66 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-import locale
-
-class ResourceCurve:
-    obj_list = []
-
-    def __init__(self, params):        
-        self.curv_id = int(params.get('curv_id')) if params.get('curv_id') else None
-        self.curv_name = params.get('curv_name').strip() if params.get('curv_id') else None
-        self.default_flag = params.get('default_flag') if params.get('default_flag') else None
-        self.pct_usage_0 = locale.atof(params.get('pct_usage_0')) if params.get('pct_usage_0') else None
-        self.pct_usage_1 = locale.atof(params.get('pct_usage_1')) if params.get('pct_usage_1') else None
-        self.pct_usage_2 = locale.atof(params.get('pct_usage_2')) if params.get('pct_usage_2') else None
-        self.pct_usage_3 = locale.atof(params.get('pct_usage_3')) if params.get('pct_usage_3') else None
-        self.pct_usage_4 = locale.atof(params.get('pct_usage_4')) if params.get('pct_usage_4') else None
-        self.pct_usage_5 = locale.atof(params.get('pct_usage_5')) if params.get('pct_usage_5') else None
-        self.pct_usage_6 = locale.atof(params.get('pct_usage_6')) if params.get('pct_usage_6') else None
-        self.pct_usage_7 = locale.atof(params.get('pct_usage_7')) if params.get('pct_usage_7') else None
-        self.pct_usage_8 = locale.atof(params.get('pct_usage_8')) if params.get('pct_usage_8') else None
-        self.pct_usage_9 = locale.atof(params.get('pct_usage_9')) if params.get('pct_usage_9') else None
-        self.pct_usage_10 = locale.atof(params.get('pct_usage_10')) if params.get('pct_usage_10') else None
-        self.pct_usage_11 = locale.atof(params.get('pct_usage_11')) if params.get('pct_usage_11') else None
-        self.pct_usage_12 = locale.atof(params.get('pct_usage_12')) if params.get('pct_usage_12') else None
-        self.pct_usage_13 = locale.atof(params.get('pct_usage_13')) if params.get('pct_usage_13') else None
-        self.pct_usage_14 = locale.atof(params.get('pct_usage_14')) if params.get('pct_usage_14') else None
-        self.pct_usage_15 = locale.atof(params.get('pct_usage_15')) if params.get('pct_usage_15') else None
-        self.pct_usage_16 = locale.atof(params.get('pct_usage_16')) if params.get('pct_usage_16') else None
-        self.pct_usage_17 = locale.atof(params.get('pct_usage_17')) if params.get('pct_usage_17') else None
-        self.pct_usage_18 = locale.atof(params.get('pct_usage_18')) if params.get('pct_usage_18') else None
-        self.pct_usage_19 = locale.atof(params.get('pct_usage_19')) if params.get('pct_usage_19') else None
-        self.pct_usage_20 = locale.atof(params.get('pct_usage_20')) if params.get('pct_usage_20') else None
-
-        ResourceCurve.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.curv_id, self.curv_name, self.default_flag, self.pct_usage_0,
-               self.pct_usage_1, self.pct_usage_2, self.pct_usage_3, self.pct_usage_4,
-               self.pct_usage_5, self.pct_usage_6, self.pct_usage_7, self.pct_usage_8,
-               self.pct_usage_9, self.pct_usage_10, self.pct_usage_11, self.pct_usage_12,
-               self.pct_usage_13, self.pct_usage_14, self.pct_usage_15, self.pct_usage_16,
-               self.pct_usage_17, self.pct_usage_18, self.pct_usage_19, self.pct_usage_20]
-        return tsv
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.curv_id == id, cls.obj_list))[0]
-        return obj
-
-    def __repr__(self):
-        return self.curv_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+import locale
+
+class ResourceCurve:
+    obj_list = []
+
+    def __init__(self, params):        
+        self.curv_id = int(params.get('curv_id')) if params.get('curv_id') else None
+        self.curv_name = params.get('curv_name').strip() if params.get('curv_id') else None
+        self.default_flag = params.get('default_flag') if params.get('default_flag') else None
+        self.pct_usage_0 = locale.atof(params.get('pct_usage_0')) if params.get('pct_usage_0') else None
+        self.pct_usage_1 = locale.atof(params.get('pct_usage_1')) if params.get('pct_usage_1') else None
+        self.pct_usage_2 = locale.atof(params.get('pct_usage_2')) if params.get('pct_usage_2') else None
+        self.pct_usage_3 = locale.atof(params.get('pct_usage_3')) if params.get('pct_usage_3') else None
+        self.pct_usage_4 = locale.atof(params.get('pct_usage_4')) if params.get('pct_usage_4') else None
+        self.pct_usage_5 = locale.atof(params.get('pct_usage_5')) if params.get('pct_usage_5') else None
+        self.pct_usage_6 = locale.atof(params.get('pct_usage_6')) if params.get('pct_usage_6') else None
+        self.pct_usage_7 = locale.atof(params.get('pct_usage_7')) if params.get('pct_usage_7') else None
+        self.pct_usage_8 = locale.atof(params.get('pct_usage_8')) if params.get('pct_usage_8') else None
+        self.pct_usage_9 = locale.atof(params.get('pct_usage_9')) if params.get('pct_usage_9') else None
+        self.pct_usage_10 = locale.atof(params.get('pct_usage_10')) if params.get('pct_usage_10') else None
+        self.pct_usage_11 = locale.atof(params.get('pct_usage_11')) if params.get('pct_usage_11') else None
+        self.pct_usage_12 = locale.atof(params.get('pct_usage_12')) if params.get('pct_usage_12') else None
+        self.pct_usage_13 = locale.atof(params.get('pct_usage_13')) if params.get('pct_usage_13') else None
+        self.pct_usage_14 = locale.atof(params.get('pct_usage_14')) if params.get('pct_usage_14') else None
+        self.pct_usage_15 = locale.atof(params.get('pct_usage_15')) if params.get('pct_usage_15') else None
+        self.pct_usage_16 = locale.atof(params.get('pct_usage_16')) if params.get('pct_usage_16') else None
+        self.pct_usage_17 = locale.atof(params.get('pct_usage_17')) if params.get('pct_usage_17') else None
+        self.pct_usage_18 = locale.atof(params.get('pct_usage_18')) if params.get('pct_usage_18') else None
+        self.pct_usage_19 = locale.atof(params.get('pct_usage_19')) if params.get('pct_usage_19') else None
+        self.pct_usage_20 = locale.atof(params.get('pct_usage_20')) if params.get('pct_usage_20') else None
+
+        ResourceCurve.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.curv_id, self.curv_name, self.default_flag, self.pct_usage_0,
+               self.pct_usage_1, self.pct_usage_2, self.pct_usage_3, self.pct_usage_4,
+               self.pct_usage_5, self.pct_usage_6, self.pct_usage_7, self.pct_usage_8,
+               self.pct_usage_9, self.pct_usage_10, self.pct_usage_11, self.pct_usage_12,
+               self.pct_usage_13, self.pct_usage_14, self.pct_usage_15, self.pct_usage_16,
+               self.pct_usage_17, self.pct_usage_18, self.pct_usage_19, self.pct_usage_20]
+        return tsv
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.curv_id == id, cls.obj_list))[0]
+        return obj
+
+    def __repr__(self):
+        return self.curv_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/rsrcrate.py` & `PyP6Xer-1.15.0/xerparser/model/classes/rsrcrate.py`

 * *Ordering differences only*

 * *Files 11% similar despite different names*

```diff
@@ -1,65 +1,65 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class ResourceRate:
-    obj_list = []
-
-    def __init__(self, params):
-        self.rsrc_rate_id = params.get('rsrc_rate_id').strip() if params.get('rsrc_rate_id') else None
-        self.rsrc_id = params.get('rsrc_id').strip() if params.get('rsrc_id') else None
-        self.max_qty_per_hr = params.get('max_qty_per_hr').strip() if params.get('max_qty_per_hr') else None
-        self.cost_per_qty = params.get('cost_per_qty').strip() if params.get('cost_per_qty') else None
-        self.start_date = params.get('start_date').strip() if params.get('start_date') else None
-        self.shift_period_id = params.get('shift_period_id').strip() if params.get('shift_period_id') else None
-        self.cost_per_qty2 = params.get('cost_per_qty2').strip() if params.get('cost_per_qty2') else None
-        self.cost_per_qty3 = params.get('cost_per_qty3').strip() if params.get('cost_per_qty3') else None
-        self.cost_per_qty4 = params.get('cost_per_qty4').strip() if params.get('cost_per_qty4') else None
-        self.cost_per_qty5 = params.get('cost_per_qty5').strip() if params.get('cost_per_qty5') else None
-        ResourceRate.obj_list.append(self)
-
-    def get_id(self):
-        return self.rsrc_rate_id
-
-
-    def get_tsv(self):
-        tsv =['%R', self.rsrc_rate_id, self.rsrc_id, self.max_qty_per_hr, self.cost_per_qty,
-              self.start_date, self.shift_period_id, self.cost_per_qty2, self.cost_per_qty3,
-              self.cost_per_qty4, self.cost_per_qty5]
-        return tsv
-
-    @classmethod
-    def find_by_id(cls, id):
-        obj = list(filter(lambda x: x.rsrc_rate_id == id, cls.obj_list))
-        if len(obj) > 0:
-            obj = obj[0]
-        else:
-            None
-        return obj
-
-    @classmethod
-    def find_by_resource_id(cls, id):
-        obj = list(filter(lambda x: x.rsrc_rate_id == id, cls.obj_list))
-        if len(obj) > 0:
-            obj = obj[0]
-        else:
-            obj = None
-        return obj
-
-    def __repr__(self):
-        return self.rsrc_id
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class ResourceRate:
+    obj_list = []
+
+    def __init__(self, params):
+        self.rsrc_rate_id = params.get('rsrc_rate_id').strip() if params.get('rsrc_rate_id') else None
+        self.rsrc_id = params.get('rsrc_id').strip() if params.get('rsrc_id') else None
+        self.max_qty_per_hr = params.get('max_qty_per_hr').strip() if params.get('max_qty_per_hr') else None
+        self.cost_per_qty = params.get('cost_per_qty').strip() if params.get('cost_per_qty') else None
+        self.start_date = params.get('start_date').strip() if params.get('start_date') else None
+        self.shift_period_id = params.get('shift_period_id').strip() if params.get('shift_period_id') else None
+        self.cost_per_qty2 = params.get('cost_per_qty2').strip() if params.get('cost_per_qty2') else None
+        self.cost_per_qty3 = params.get('cost_per_qty3').strip() if params.get('cost_per_qty3') else None
+        self.cost_per_qty4 = params.get('cost_per_qty4').strip() if params.get('cost_per_qty4') else None
+        self.cost_per_qty5 = params.get('cost_per_qty5').strip() if params.get('cost_per_qty5') else None
+        ResourceRate.obj_list.append(self)
+
+    def get_id(self):
+        return self.rsrc_rate_id
+
+
+    def get_tsv(self):
+        tsv =['%R', self.rsrc_rate_id, self.rsrc_id, self.max_qty_per_hr, self.cost_per_qty,
+              self.start_date, self.shift_period_id, self.cost_per_qty2, self.cost_per_qty3,
+              self.cost_per_qty4, self.cost_per_qty5]
+        return tsv
+
+    @classmethod
+    def find_by_id(cls, id):
+        obj = list(filter(lambda x: x.rsrc_rate_id == id, cls.obj_list))
+        if len(obj) > 0:
+            obj = obj[0]
+        else:
+            None
+        return obj
+
+    @classmethod
+    def find_by_resource_id(cls, id):
+        obj = list(filter(lambda x: x.rsrc_rate_id == id, cls.obj_list))
+        if len(obj) > 0:
+            obj = obj[0]
+        else:
+            obj = None
+        return obj
+
+    def __repr__(self):
+        return self.rsrc_id
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/rsrcrcat.py` & `PyP6Xer-1.15.0/xerparser/model/classes/rsrcrcat.py`

 * *Ordering differences only*

 * *Files 10% similar despite different names*

```diff
@@ -1,37 +1,37 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class ResourceCat:
-    obj_list = []
-
-    def __init__(self, params):
-        self.rsrc_id = int(params.get('rsrc_id').strip()) if params.get('rsrc_id') else None
-        self.rsrc_catg_type_id = int(params.get('rsrc_catg_type_id').strip()) if params.get('rsrc_catg_type_id') else None
-        self.rsrc_catg_id = int(params.get('rsrc_catg_type_id').strip()) if params.get('rsrc_catg_type_id') else None
-        ResourceCat.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.rsrc_id, self.rsrc_catg_type_id, self.rsrc_catg_id]
-        return tsv
-
-    def get_id(self):
-        return self.rsrc_id
-
-    def __repr__(self):
-        return self.rsrc_id + ' has been assign category ' + self.rsrc_catg_id
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class ResourceCat:
+    obj_list = []
+
+    def __init__(self, params):
+        self.rsrc_id = int(params.get('rsrc_id').strip()) if params.get('rsrc_id') else None
+        self.rsrc_catg_type_id = int(params.get('rsrc_catg_type_id').strip()) if params.get('rsrc_catg_type_id') else None
+        self.rsrc_catg_id = int(params.get('rsrc_catg_type_id').strip()) if params.get('rsrc_catg_type_id') else None
+        ResourceCat.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.rsrc_id, self.rsrc_catg_type_id, self.rsrc_catg_id]
+        return tsv
+
+    def get_id(self):
+        return self.rsrc_id
+
+    def __repr__(self):
+        return self.rsrc_id + ' has been assign category ' + self.rsrc_catg_id
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/schedoption.py` & `PyP6Xer-1.15.0/xerparser/model/classes/schedoption.py`

 * *Ordering differences only*

 * *Files 6% similar despite different names*

```diff
@@ -1,69 +1,69 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class SchedOption:
-    obj_list = []
-
-    def __init__(self, params):
-
-        self.schedoptions_id = params.get('schedoptions_id').strip() if params.get('schedoptions_id') else None
-        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
-        self.sched_outer_depend_type = params.get('sched_outer_depend_type').strip() if params.get('sched_outer_depend_type') else None
-        self.sched_open_critical_flag = params.get('sched_open_critical_flag').strip() if params.get('sched_open_critical_flag') else None
-        self.sched_lag_early_start_flag = params.get('sched_lag_early_start_flag').strip() if params.get('sched_lag_early_start_flag') else None
-        self.sched_retained_logic = params.get('sched_retained_logic').strip() if params.get('sched_retained_logic') else None
-        self.sched_setplantoforecast = params.get('sched_setplantoforecast').strip() if params.get('sched_setplantoforecast') else None
-        self.sched_float_type = params.get('sched_float_type').strip() if params.get('sched_float_type') else None
-        self.sched_calendar_on_relationship_lag = params.get('sched_calendar_on_relationship_lag').strip() if params.get('sched_calendar_on_relationship_lag') else None
-        self.sched_use_expect_end_flag = params.get('sched_use_expect_end_flag').strip() if params.get('sched_use_expect_end_flag') else None
-        self.sched_progress_override = params.get('sched_progress_override').strip() if params.get('sched_progress_override') else None
-        self.level_float_thrs_cnt = params.get('level_float_thrs_cnt').strip() if params.get('level_float_thrs_cnt') else None
-        self.level_outer_assign_flag = params.get('level_outer_assign_flag').strip() if params.get('level_outer_assign_flag') else None
-        self.level_outer_assign_priority = params.get('level_outer_assign_priority').strip() if params.get('level_outer_assign_priority') else None
-        self.level_over_alloc_pct = params.get('level_over_alloc_pct').strip() if params.get('level_over_alloc_pct') else None
-        self.level_within_float_flag = params.get('level_within_float_flag').strip() if params.get('level_within_float_flag') else None
-        self.level_keep_sched_date_flag = params.get('level_keep_sched_date_flag').strip() if params.get('level_keep_sched_date_flag') else None
-        self.level_all_rsrc_flag = params.get('level_all_rsrc_flag').strip() if params.get('level_all_rsrc_flag') else None
-        self.sched_use_project_end_date_for_float = params.get('sched_use_project_end_date_for_float').strip() if params.get('sched_use_project_end_date_for_float') else None
-        self.enable_multiple_longest_path_calc = params.get('enable_multiple_longest_path_calc').strip() if params.get('enable_multiple_longest_path_calc') else None
-        self.limit_multiple_longest_path_calc = params.get('limit_multiple_longest_path_calc').strip() if params.get('limit_multiple_longest_path_calc') else None
-        self.max_multiple_longest_path = params.get('max_multiple_longest_path').strip() if params.get('max_multiple_longest_path') else None
-        self.use_total_float_multiple_longest_paths = params.get('use_total_float_multiple_longest_paths').strip() if params.get('use_total_float_multiple_longest_paths') else None
-        self.key_activity_for_multiple_longest_paths = params.get('key_activity_for_multiple_longest_paths').strip() if params.get('use_total_float_multiple_longest_paths') else None
-        self.LevelPriorityList = params.get('LevelPriorityList').strip() if params.get('LevelPriorityList') else None
-        SchedOption.obj_list.append(self)
-
-    def get_id(self):
-        return self.schedoptions_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.schedoptions_id, self.proj_id, self.sched_outer_depend_type, self.sched_open_critical_flag,
-               self.sched_lag_early_start_flag, self.sched_retained_logic, self.sched_setplantoforecast,
-               self.sched_float_type, self.sched_calendar_on_relationship_lag, self.sched_use_expect_end_flag,
-               self.sched_progress_override, self.level_float_thrs_cnt, self.level_outer_assign_flag,
-               self.level_outer_assign_priority, self.level_over_alloc_pct, self.level_within_float_flag,
-               self.level_keep_sched_date_flag, self.level_all_rsrc_flag, self.sched_use_project_end_date_for_float,
-               self.enable_multiple_longest_path_calc, self.limit_multiple_longest_path_calc,
-               self.max_multiple_longest_path, self.use_total_float_multiple_longest_paths,
-               self.key_activity_for_multiple_longest_paths, self.LevelPriorityList
-               ]
-        return tsv
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class SchedOption:
+    obj_list = []
+
+    def __init__(self, params):
+
+        self.schedoptions_id = params.get('schedoptions_id').strip() if params.get('schedoptions_id') else None
+        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
+        self.sched_outer_depend_type = params.get('sched_outer_depend_type').strip() if params.get('sched_outer_depend_type') else None
+        self.sched_open_critical_flag = params.get('sched_open_critical_flag').strip() if params.get('sched_open_critical_flag') else None
+        self.sched_lag_early_start_flag = params.get('sched_lag_early_start_flag').strip() if params.get('sched_lag_early_start_flag') else None
+        self.sched_retained_logic = params.get('sched_retained_logic').strip() if params.get('sched_retained_logic') else None
+        self.sched_setplantoforecast = params.get('sched_setplantoforecast').strip() if params.get('sched_setplantoforecast') else None
+        self.sched_float_type = params.get('sched_float_type').strip() if params.get('sched_float_type') else None
+        self.sched_calendar_on_relationship_lag = params.get('sched_calendar_on_relationship_lag').strip() if params.get('sched_calendar_on_relationship_lag') else None
+        self.sched_use_expect_end_flag = params.get('sched_use_expect_end_flag').strip() if params.get('sched_use_expect_end_flag') else None
+        self.sched_progress_override = params.get('sched_progress_override').strip() if params.get('sched_progress_override') else None
+        self.level_float_thrs_cnt = params.get('level_float_thrs_cnt').strip() if params.get('level_float_thrs_cnt') else None
+        self.level_outer_assign_flag = params.get('level_outer_assign_flag').strip() if params.get('level_outer_assign_flag') else None
+        self.level_outer_assign_priority = params.get('level_outer_assign_priority').strip() if params.get('level_outer_assign_priority') else None
+        self.level_over_alloc_pct = params.get('level_over_alloc_pct').strip() if params.get('level_over_alloc_pct') else None
+        self.level_within_float_flag = params.get('level_within_float_flag').strip() if params.get('level_within_float_flag') else None
+        self.level_keep_sched_date_flag = params.get('level_keep_sched_date_flag').strip() if params.get('level_keep_sched_date_flag') else None
+        self.level_all_rsrc_flag = params.get('level_all_rsrc_flag').strip() if params.get('level_all_rsrc_flag') else None
+        self.sched_use_project_end_date_for_float = params.get('sched_use_project_end_date_for_float').strip() if params.get('sched_use_project_end_date_for_float') else None
+        self.enable_multiple_longest_path_calc = params.get('enable_multiple_longest_path_calc').strip() if params.get('enable_multiple_longest_path_calc') else None
+        self.limit_multiple_longest_path_calc = params.get('limit_multiple_longest_path_calc').strip() if params.get('limit_multiple_longest_path_calc') else None
+        self.max_multiple_longest_path = params.get('max_multiple_longest_path').strip() if params.get('max_multiple_longest_path') else None
+        self.use_total_float_multiple_longest_paths = params.get('use_total_float_multiple_longest_paths').strip() if params.get('use_total_float_multiple_longest_paths') else None
+        self.key_activity_for_multiple_longest_paths = params.get('key_activity_for_multiple_longest_paths').strip() if params.get('use_total_float_multiple_longest_paths') else None
+        self.LevelPriorityList = params.get('LevelPriorityList').strip() if params.get('LevelPriorityList') else None
+        SchedOption.obj_list.append(self)
+
+    def get_id(self):
+        return self.schedoptions_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.schedoptions_id, self.proj_id, self.sched_outer_depend_type, self.sched_open_critical_flag,
+               self.sched_lag_early_start_flag, self.sched_retained_logic, self.sched_setplantoforecast,
+               self.sched_float_type, self.sched_calendar_on_relationship_lag, self.sched_use_expect_end_flag,
+               self.sched_progress_override, self.level_float_thrs_cnt, self.level_outer_assign_flag,
+               self.level_outer_assign_priority, self.level_over_alloc_pct, self.level_within_float_flag,
+               self.level_keep_sched_date_flag, self.level_all_rsrc_flag, self.sched_use_project_end_date_for_float,
+               self.enable_multiple_longest_path_calc, self.limit_multiple_longest_path_calc,
+               self.max_multiple_longest_path, self.use_total_float_multiple_longest_paths,
+               self.key_activity_for_multiple_longest_paths, self.LevelPriorityList
+               ]
+        return tsv
+
+    def __repr__(self):
         return self.proj_id
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/task.py` & `PyP6Xer-1.15.0/xerparser/model/classes/task.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,327 +1,327 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from datetime import datetime
-
-from xerparser.model.taskactvs import TaskActvs
-
-from xerparser.model.predecessors import Predecessors
-from xerparser.model.classes.calendar import Calendar
-from xerparser.model.activitiyresources import ActivityResources
-from xerparser.model.taskprocs import TaskProcs
-import locale
-
-class Task:
-    obj_list = []
-
-    def __init__(self, params, data):
-        # Unique ID generated by the system.
-        self.task_id = int(params.get('task_id')) if params.get('task_id') else None
-        # project to which the activity belongs referenced by system generated unique id
-        self.proj_id = int(params.get('proj_id')) if params.get('proj_id') else None
-        # wbs element activity assigned to referenced by system unique id
-        self.wbs_id = int(params.get('wbs_id')) if params.get('wbs_id') else None
-        # calendar assigned to activity referenced by system unique id
-        self.clndr_id = int(params.get('clndr_id')) if params.get('clndr_id') else None
-        # The physical percent complete can either be user entered or calculated from the activity's weighted steps.
-        #  There is a project setting specifying this.
-        self.phys_complete_pct = locale.atof(params.get('phys_complete_pct')) if 'phys_complete_pct' in params.keys() else None
-        # Indicates that the primary resource has sent feedback notes about this activity which have not been
-        # reviewed yet.
-        self.rev_fdbk_flag = params.get('rev_fdbk_flag') if params.get('rev_fdbk_flag') else None
-        # The estimation weight for the activity, used for top-down estimation. Top-down estimation weights are used
-        # to calculate the proportion of units that each activity receives in relation to the other activities within
-        #  the same WBS. Top-down estimation distributes estimated units in a top-down manner to activities using the
-        #  WBS hierarchy.
-
-        self.est_wt = locale.atof(params.get('est_wt').strip()) if 'est_wt' in params.keys() else None
-        # Indicates that the planned labor and nonlabor units for the activity will not be modified by top-down
-        # estimation.
-        self.lock_plan_flag = params.get('lock_plan_flag') if params.get('lock_plan_flag') else None
-        # Identifies whether the actual and remaining cost for the expense are computed automatically using the
-        # planned cost and the activity's schedule percent complete.  If this option is selected,
-        # the actual/remaining cost are automatically updated when project actuals are applied.  This assumes the
-        # expenses are made according to plan.
-        self.auto_compute_act_flag = params.get('auto_compute_act_flag') if params.get('auto_compute_act_flag') else None
-        # The activity percent complete type is one of ""Duration"", ""Units"", or ""Physical"". The percent complete
-        #  type controls whether the Activity % Complete is tied to the Duration % Complete, the Units % Complete,
-        # or the Physical % Complete for the activity. Set the percent complete type to ""Duration"" for activities
-        # which are duration driven, for example, administration tasks and training classes.  Set the percent
-        # complete type to ""Physical"" for activities which are work-product driven, for example, creating a
-        # document or a product. Set the percent complete type to ""Units"" for activities which are work effort
-        # driven, for example, providing a consulting service.
-        self.complete_pct_type = params.get('complete_pct_type').strip() if params.get('complete_pct_type') else None
-        # The type of activity, either  'Task Dependent', 'Resource Dependent', 'Level of Effort', 'Start Milestone'
-        # or 'Finish Milestone'.   A Task Dependent activity is scheduled using the activity's calendar rather than
-        # the calendars of the assigned resources.  A Resource Dependent activity is scheduled using the calendars of
-        #  the assigned resources.  This type is used when several resources are assigned to the activity,
-        # but they may work separately.  A Start/Finish Milestone is a zero-duration activity, marking a significant
-        # start/end of project event. A Level of Effort activity has a duration which is determined by its dependent
-        # activities. Administration-type activities are typically level of effort.
-        self.task_type = params.get('task_type').strip() if params.get('task_type') else None
-        # The duration type of the activity. One of ""Fixed Units per Time"", ""Fixed Duration"", or ""Fixed Units"".
-        #   For Fixed Units per Time activities, the resource units per time are constant when the activity duration
-        # or units are changed.  This type is used when an activity has fixed resources with fixed productivity
-        # output per time period.  For Fixed Duration activities, the activity duration is constant as the units or
-        # resource units per time are changed. This type is used when the activity is to be completed within a fixed
-        # time period regardless of the resources assigned.  For Fixed Units activities, the activity units are
-        # constant when the duration or resource units per time are changed. This type is used when the total amount
-        # of work is fixed, and increasing the resources can decrease the activity duration.
-        self.duration_type = params.get('duration_type').strip() if params.get('duration_type') else None
-        # The current status of the activity, either Not Started, In Progress, or Completed.
-        self.status_code = params.get('status_code').strip() if params.get('status_code') else None
-        # A short ID which uniquely identifies the activity within the project.
-        self.task_code = params.get('task_code').strip() if params.get('task_code') else None
-        # The name of the activity. The activity name does not have to be unique.
-        self.task_name = params.get('task_name').strip() if params.get('task_name') else None
-        # Resource ID Name
-        self.rsrc_id = int(params.get('rsrc_id').strip()) if params.get('rsrc_id') else None
-        # The amount of time the wbs can be delayed before delaying the project finish date. Total int can be
-        # computed as Late Start - Early Start or as Late Finish - Early Finish; this option can be set when running
-        # the project scheduler.
-        self.total_float_hr_cnt = locale.atof(params.get('total_float_hr_cnt').strip()) if params.get('total_float_hr_cnt') and \
-            params.get('total_float_hr_cnt') != '' else None
-        # The amount of time the activity can be delayed before delaying the start date of any successor activity.
-        self.free_float_hr_cnt = locale.atof(params.get('free_float_hr_cnt')) if params.get('free_float_hr_cnt') else None
-        # Remaining duration is the total working time from the activity remaining start date to the remaining finish
-        #  date. The remaining working time is computed using the activity's calendar. Before the activity is
-        # started, the remaining duration is the same as the Original Duration. After the activity is completed the
-        # remaining duration is zero.
-        self.remain_drtn_hr_cnt = locale.atof(params.get('remain_drtn_hr_cnt').strip()) if params.get('remain_drtn_hr_cnt') else 0
-        # The total actual labor units for all child activities
-        self.act_work_qty = locale.atof(params.get('act_work_qty')) if params.get('act_work_qty') else None
-        # The remaining units for all labor resources assigned to the activity. The remaining units reflects the work
-        #  remaining to be done for the activity. Before the activity is started, the remaining units are the same as
-        #  the planned units. After the activity is completed, the remaining units are zero.
-        self.remain_work_qty = locale.atof(params.get('remain_work_qty')) if params.get('remain_work_qty') else None
-        # The planned units for all labor resources assigned to the activity.
-        self.target_work_qty = locale.atof(params.get('target_work_qty')) if params.get('target_work_qty') else None
-        # Original Duration is the planned working time for the resource assignment on the activity,
-        # from the resource's planned start date to the planned finish date. The planned working time is computed
-        # using the calendar determined by the Activity Type. Resource Dependent activities use the resource's
-        # calendar; other activity types use the activity's calendar. This is the duration that Timesheets users
-        # follow and the schedule variance is measured against.
-        self.target_drtn_hr_cnt = locale.atof(params.get('target_drtn_hr_cnt').strip()) if params.get('target_drtn_hr_cnt') else None
-        # The planned units for all nonlabor resources assigned to the activity.
-        self.target_equip_qty = locale.atof(params.get('target_equip_qty')) if params.get('target_equip_qty') else None
-        # The actual units for all nonlabor resources assigned to the activities under the WBS.
-        self.act_equip_qty = locale.atof(params.get('act_equip_qty')) if params.get('act_equip_qty') else None
-        # The remaining units for all nonlabor resources assigned to the activity. The remaining units reflects the
-        # work remaining to be done for the activity.  Before the activity is started, the remaining units are the
-        # same as the planned units. After the activity is completed, the remaining units are zero.
-        self.remain_equip_qty = locale.atof(params.get('remain_equip_qty')) if params.get('remain_equip_qty') else None
-        # The constraint date for the activity, if the activity has a constraint. The activity's constraint type
-        # determines whether this is a start date or finish date.  Activity constraints are used by the project
-        # scheduler.
-        self.cstr_date = datetime.strptime(params.get('cstr_date'), '%Y-%m-%d %H:%M') if params.get('cstr_date') else None
-        # The date on which the activity is actually started.
-        self.act_start_date = datetime.strptime(params.get('act_start_date'), '%Y-%m-%d %H:%M') if params.get('act_start_date') else None
-        # The date on which the activity is actually finished.
-        self.act_end_date = datetime.strptime(params.get('act_end_date'), '%Y-%m-%d %H:%M') if params.get('act_end_date') else None
-        # the activity late start date
-        self.late_start_date = datetime.strptime(params.get('late_start_date'), '%Y-%m-%d %H:%M') if params.get('late_start_date') else None
-        # The latest possible date the activity must finish without delaying the project finish date. This date is
-        # computed by the project scheduler based on network logic, schedule constraints, and resource availability.
-        self.late_end_date = datetime.strptime(params.get('late_end_date'), '%Y-%m-%d %H:%M') if params.get('late_end_date') else None
-        # The date the activity is expected to be finished according to the progress made on the activity's work
-        # products. The expected finish date is entered manually by people familiar with progress of the activity's
-        # work products.
-        self.expect_end_date = datetime.strptime(params.get('expect_end_date'), '%Y-%m-%d %H:%M') if params.get('expect_end_date') else None
-        # The earliest possible date the remaining work for the activity can begin. This date is computed by the
-        # project scheduler based on network logic, schedule constraints, and resource availability.
-        self.early_start_date = datetime.strptime(params.get('early_start_date'), '%Y-%m-%d %H:%M') if params.get('early_start_date') else None
-        # The earliest possible date the activity can finish. This date is computed by the project scheduler based on
-        #  network logic, schedule constraints, and resource availability.
-        self.early_end_date = datetime.strptime(params.get('early_end_date'), '%Y-%m-%d %H:%M') if params.get('early_end_date') else None
-        # The date the remaining work for the activity is scheduled to begin. This date is computed by the project
-        # scheduler but can be updated manually by the project manager.  Before the activity is started,
-        # the remaining start date is the same as the planned start date.  This is the start date that Timesheets
-        # users follow.
-        self.restart_date = datetime.strptime(params.get('restart_date'), '%Y-%m-%d %H:%M') if params.get('restart_date') else None
-        # The date the remaining work for the activity is scheduled to finish. This date is computed by the project
-        # scheduler but can be updated manually by the project manager. Before the activity is started, the remaining
-        #  finish date is the same as the planned finish date.  This is the finish date that Timesheets users follow.
-        self.reend_date = datetime.strptime(params.get('reend_date'), '%Y-%m-%d %H:%M') if params.get('reend_date') else None
-        # The date the activity is scheduled to begin. This date is computed by the project scheduler but can be
-        # updated manually by the project manager. This date is not changed by the project scheduler after the
-        # activity has been started.
-        self.target_start_date = datetime.strptime(params.get('target_start_date'), '%Y-%m-%d %H:%M') if params.get('target_start_date') else None
-        # The date the activity is scheduled to finish. This date is computed by the project scheduler but can be
-        # updated manually by the project manager.  This date is not changed by the project scheduler after the
-        # activity has been started.
-        self.target_end_date = datetime.strptime(params.get('target_end_date'), '%Y-%m-%d %H:%M') if params.get('target_end_date') else None
-        # Remaining late start date is calculated by the scheduler.
-        self.rem_late_start_date = datetime.strptime(params.get('rem_late_start_date'), '%Y-%m-%d %H:%M') if params.get('rem_late_start_date') else None
-        # Remaining late end date is calculated by the scheduler.
-        self.rem_late_end_date = datetime.strptime(params.get('rem_late_end_date'), '%Y-%m-%d %H:%M') if params.get('rem_late_end_date') else None
-        # The type of constraint applied to the activity start or finish date. Activity constraints are used by the
-        # project scheduler.  Start date constraints are 'Start On', 'Start On or Before', 'Start On or After' and
-        # 'Mandatory Start'.  Finish date constraints are 'Finish On', 'Finish On or Before', 'Finish On or After'
-        # and 'Mandatory Finish'.  Another type of constraint, 'As Late as Possible', schedules the activity as late
-        # as possible based on the available free int.
-        self.cstr_type = params.get('cstr_type').strip() if params.get('cstr_type') else None
-        self.priority_type = params.get('priority_type').strip() if params.get('priority_type') else None
-        # The date progress is suspended on an activity.
-        self.suspend_date = datetime.strptime(params.get('suspend_date').strip(), '%Y-%m-%d %H:%M') if params.get('suspend_date') else None
-        # The date progress is resumed on an activity.
-        self.resume_date = datetime.strptime(params.get('resume_date').strip(), '%Y-%m-%d %H:%M') if params.get('resume_date') else None
-        self.int_path = params.get('int_path').strip() if params.get('int_path') else None
-        # This field is computed by the project scheduler and identifies the order in which the activities were
-        # processed within the int path.
-        self.int_path_order = params.get('int_path_order').strip() if params.get('int_path_order') else None
-        self.guid = params.get('guid').strip() if params.get('guid') else None
-        self.tmpl_guid = params.get('tmpl_guid').strip() if params.get('tmpl_guid') else None
-        # The second constraint date for the activity, if the activity has a constraint.
-        self.cstr_date2 = datetime.strptime(params.get('cstr_date2'), '%Y-%m-%d %H:%M') if params.get('cstr_date2') else None
-        # The second type of constraint applied to the activity start or finish date.
-        self.cstr_type2 = params.get('cstr_type2').strip() if params.get('cstr_type2') else None
-        self.driving_path_flag = params.get('driving_path_flag') if params.get('driving_path_flag') else None
-        # The actual this period units for all labor resources assigned to the activity.
-        self.act_this_per_work_qty = locale.atof(params.get('act_this_per_work_qty')) if params.get('act_this_per_work_qty') else None
-        # The actual this period units for all nonlabor resources assigned to the activity.
-        self.act_this_per_equip_qty = locale.atof(params.get('act_this_per_equip_qty')) if params.get('act_this_per_equip_qty') else None
-        # The External Early Start date is the date the external relationship was scheduled to finish.  This date may
-        #  be used to calculate the start date of the current activity during scheduling.  This field is populated on
-        #  import when an external relationship is lost.
-        try:
-            self.external_early_start_date = datetime.strptime(params.get('external_early_start_date').strip(), '%Y-%m-%d %H:%M') if params.get('external_early_start_date') else None
-            self.external_late_end_date = datetime.strptime(params.get('external_late_end_date'), '%Y-%m-%d %H:%M') if params.get('external_late_end_date') else None
-        except:
-            pass
-        self.create_date = datetime.strptime(params.get('create_date'), '%Y-%m-%d %H:%M') if params.get('create_date') else None
-        self.update_date = datetime.strptime(params.get('update_date'), '%Y-%m-%d %H:%M') if params.get('update_date') else None
-        self.create_user = params.get('create_user').strip() if params.get('create_user') else None
-        self.update_user = params.get('update_user').strip() if params.get('update_user') else None
-        self.location_id = params.get('location_id').strip() if params.get('location_id') else None
-        self.calendar = Calendar.find_by_id(self.clndr_id)
-        # self.wbs = WBS.find_by_id(int(self.wbs_id) if self.wbs_id else None)
-        # Task.obj_list.append(self)
-        self.data = data
-
-    def get_tsv(self):
-        tsv = ['%R', self.task_id, self.proj_id, self.wbs_id, self.clndr_id, self.phys_complete_pct, self.rev_fdbk_flag,
-               self.est_wt, self.lock_plan_flag, self.auto_compute_act_flag, self.complete_pct_type, self.task_type,
-               self.duration_type, self.status_code, self.task_code, self.task_name, self.rsrc_id,
-               self.total_float_hr_cnt, self.free_float_hr_cnt, self.remain_drtn_hr_cnt, self.act_work_qty,
-               self.remain_work_qty, self.target_work_qty, self.target_drtn_hr_cnt, self.target_equip_qty,
-               self.act_equip_qty, self.remain_equip_qty,
-               self.cstr_date.strftime('%Y-%m-%d %H:%M') if self.cstr_date else None,
-               self.act_start_date.strftime('%Y-%m-%d %H:%M') if self.act_start_date else None,
-               self.act_end_date.strftime('%Y-%m-%d %H:%M') if self.act_end_date else None,
-               self.late_start_date.strftime('%Y-%m-%d %H:%M') if self.late_start_date else None,
-               self.late_end_date.strftime('%Y-%m-%d %H:%M') if self.late_end_date else None,
-               self.expect_end_date.strftime('%Y-%m-%d %H:%M') if self.expect_end_date else None,
-               self.early_start_date.strftime('%Y-%m-%d %H:%M') if self.early_start_date else None,
-               self.early_end_date.strftime('%Y-%m-%d %H:%M') if self.early_end_date else None,
-               self.restart_date.strftime('%Y-%m-%d %H:%M') if self.restart_date else None,
-               self.reend_date.strftime('%Y-%m-%d %H:%M') if self.reend_date else None,
-               self.target_start_date.strftime('%Y-%m-%d %H:%M') if self.target_start_date else None,
-               self.target_end_date.strftime('%Y-%m-%d %H:%M') if self.target_end_date else None,
-               self.rem_late_start_date.strftime('%Y-%m-%d %H:%M') if self.rem_late_start_date else None,
-               self.rem_late_end_date.strftime('%Y-%m-%d %H:%M') if self.rem_late_end_date else None,
-               self.cstr_type, self.priority_type,
-               self.suspend_date.strftime('%Y-%m-%d %H:%M') if self.suspend_date else None,
-               self.resume_date.strftime('%Y-%m-%d %H:%M') if self.resume_date else None,
-               self.int_path, self.int_path_order, self.guid, self.tmpl_guid,
-               self.cstr_date2.strftime('%Y-%m-%d %H:%M') if self.cstr_date2 else None,
-               self.cstr_type2, self.driving_path_flag,
-               self.act_this_per_work_qty, self.act_this_per_equip_qty,
-               self.external_early_start_date.strftime('%Y-%m-%d %H:%M') if self.external_early_start_date else None,
-               self.external_late_end_date.strftime('%Y-%m-%d %H:%M') if self.external_late_end_date else None,
-               self.create_date.strftime('%Y-%m-%d %H:%M') if self.create_date else None,
-               self.update_date.strftime('%Y-%m-%d %H:%M') if self.update_date else None,
-               self.create_user, self.update_user, self.location_id]
-        return tsv
-
-    @property
-    def id(self):
-        return self.task_id
-
-    @property
-    def totalint(self):
-        if self.total_int_hr_cnt:
-            tf = int(self.total_int_hr_cnt)/8.0
-        else:
-            return None
-        return tf
-
-    @property
-    def resources(self):
-        return self.data.taskresource.find_by_activity_id(self.task_id)
-
-    @property
-    def steps(self):
-        return TaskProcs.find_by_activity_id(self.task_id)
-
-    @property
-    def activitycodes(self):
-        return self .data.taskactvcodes.find_by_activity_id(self.task_id)
-
-
-    @property
-    def duration(self):
-        dur = None
-        if self.target_drtn_hr_cnt:
-            if self.calendar.day_hr_cnt:
-                dur = self.target_drtn_hr_cnt / self.calendar.day_hr_cnt
-            else:
-                dur = self.target_drtn_hr_cnt / 8.0
-        else:
-            dur =0.0
-        return dur
-
-    @property
-    def constraints(self):
-        if self.cstr_type == None or self.cstr_date == None:
-            return  None
-        return {"ConstraintType": self.cstr_type,
-                "ConstrintDate": self.cstr_date
-               }
-
-    @property
-    def start_date(self):
-        if self.act_start_date:
-            return self.act_start_date
-        else:
-            return self.target_start_date
-
-    @property
-    def end_date(self):
-        if self.act_end_date:
-            return self.act_end_date
-        else:
-            return self.target_end_date
-
-    @property
-    def successors(self):
-        suss = Predecessors.get_successors(self.task_id)
-        return suss
-
-    @property
-    def predecessors(self):
-        return Predecessors.get_predecessors(self.task_id)
-
-    @classmethod
-    def find_by_wbs_id(cls, wbs_id):
-        return [v for v in cls.obj_list if v.wbs_id == wbs_id]
-
-    def __repr__(self):
-        return self.task_code
-
-
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from datetime import datetime
+
+from xerparser.model.taskactvs import TaskActvs
+
+from xerparser.model.predecessors import Predecessors
+from xerparser.model.classes.calendar import Calendar
+from xerparser.model.activitiyresources import ActivityResources
+from xerparser.model.taskprocs import TaskProcs
+import locale
+
+class Task:
+    obj_list = []
+
+    def __init__(self, params, data):
+        # Unique ID generated by the system.
+        self.task_id = int(params.get('task_id')) if params.get('task_id') else None
+        # project to which the activity belongs referenced by system generated unique id
+        self.proj_id = int(params.get('proj_id')) if params.get('proj_id') else None
+        # wbs element activity assigned to referenced by system unique id
+        self.wbs_id = int(params.get('wbs_id')) if params.get('wbs_id') else None
+        # calendar assigned to activity referenced by system unique id
+        self.clndr_id = int(params.get('clndr_id')) if params.get('clndr_id') else None
+        # The physical percent complete can either be user entered or calculated from the activity's weighted steps.
+        #  There is a project setting specifying this.
+        self.phys_complete_pct = locale.atof(params.get('phys_complete_pct')) if 'phys_complete_pct' in params.keys() else None
+        # Indicates that the primary resource has sent feedback notes about this activity which have not been
+        # reviewed yet.
+        self.rev_fdbk_flag = params.get('rev_fdbk_flag') if params.get('rev_fdbk_flag') else None
+        # The estimation weight for the activity, used for top-down estimation. Top-down estimation weights are used
+        # to calculate the proportion of units that each activity receives in relation to the other activities within
+        #  the same WBS. Top-down estimation distributes estimated units in a top-down manner to activities using the
+        #  WBS hierarchy.
+
+        self.est_wt = locale.atof(params.get('est_wt').strip()) if 'est_wt' in params.keys() else None
+        # Indicates that the planned labor and nonlabor units for the activity will not be modified by top-down
+        # estimation.
+        self.lock_plan_flag = params.get('lock_plan_flag') if params.get('lock_plan_flag') else None
+        # Identifies whether the actual and remaining cost for the expense are computed automatically using the
+        # planned cost and the activity's schedule percent complete.  If this option is selected,
+        # the actual/remaining cost are automatically updated when project actuals are applied.  This assumes the
+        # expenses are made according to plan.
+        self.auto_compute_act_flag = params.get('auto_compute_act_flag') if params.get('auto_compute_act_flag') else None
+        # The activity percent complete type is one of ""Duration"", ""Units"", or ""Physical"". The percent complete
+        #  type controls whether the Activity % Complete is tied to the Duration % Complete, the Units % Complete,
+        # or the Physical % Complete for the activity. Set the percent complete type to ""Duration"" for activities
+        # which are duration driven, for example, administration tasks and training classes.  Set the percent
+        # complete type to ""Physical"" for activities which are work-product driven, for example, creating a
+        # document or a product. Set the percent complete type to ""Units"" for activities which are work effort
+        # driven, for example, providing a consulting service.
+        self.complete_pct_type = params.get('complete_pct_type').strip() if params.get('complete_pct_type') else None
+        # The type of activity, either  'Task Dependent', 'Resource Dependent', 'Level of Effort', 'Start Milestone'
+        # or 'Finish Milestone'.   A Task Dependent activity is scheduled using the activity's calendar rather than
+        # the calendars of the assigned resources.  A Resource Dependent activity is scheduled using the calendars of
+        #  the assigned resources.  This type is used when several resources are assigned to the activity,
+        # but they may work separately.  A Start/Finish Milestone is a zero-duration activity, marking a significant
+        # start/end of project event. A Level of Effort activity has a duration which is determined by its dependent
+        # activities. Administration-type activities are typically level of effort.
+        self.task_type = params.get('task_type').strip() if params.get('task_type') else None
+        # The duration type of the activity. One of ""Fixed Units per Time"", ""Fixed Duration"", or ""Fixed Units"".
+        #   For Fixed Units per Time activities, the resource units per time are constant when the activity duration
+        # or units are changed.  This type is used when an activity has fixed resources with fixed productivity
+        # output per time period.  For Fixed Duration activities, the activity duration is constant as the units or
+        # resource units per time are changed. This type is used when the activity is to be completed within a fixed
+        # time period regardless of the resources assigned.  For Fixed Units activities, the activity units are
+        # constant when the duration or resource units per time are changed. This type is used when the total amount
+        # of work is fixed, and increasing the resources can decrease the activity duration.
+        self.duration_type = params.get('duration_type').strip() if params.get('duration_type') else None
+        # The current status of the activity, either Not Started, In Progress, or Completed.
+        self.status_code = params.get('status_code').strip() if params.get('status_code') else None
+        # A short ID which uniquely identifies the activity within the project.
+        self.task_code = params.get('task_code').strip() if params.get('task_code') else None
+        # The name of the activity. The activity name does not have to be unique.
+        self.task_name = params.get('task_name').strip() if params.get('task_name') else None
+        # Resource ID Name
+        self.rsrc_id = int(params.get('rsrc_id').strip()) if params.get('rsrc_id') else None
+        # The amount of time the wbs can be delayed before delaying the project finish date. Total int can be
+        # computed as Late Start - Early Start or as Late Finish - Early Finish; this option can be set when running
+        # the project scheduler.
+        self.total_float_hr_cnt = locale.atof(params.get('total_float_hr_cnt').strip()) if params.get('total_float_hr_cnt') and \
+            params.get('total_float_hr_cnt') != '' else None
+        # The amount of time the activity can be delayed before delaying the start date of any successor activity.
+        self.free_float_hr_cnt = locale.atof(params.get('free_float_hr_cnt')) if params.get('free_float_hr_cnt') else None
+        # Remaining duration is the total working time from the activity remaining start date to the remaining finish
+        #  date. The remaining working time is computed using the activity's calendar. Before the activity is
+        # started, the remaining duration is the same as the Original Duration. After the activity is completed the
+        # remaining duration is zero.
+        self.remain_drtn_hr_cnt = locale.atof(params.get('remain_drtn_hr_cnt').strip()) if params.get('remain_drtn_hr_cnt') else 0
+        # The total actual labor units for all child activities
+        self.act_work_qty = locale.atof(params.get('act_work_qty')) if params.get('act_work_qty') else None
+        # The remaining units for all labor resources assigned to the activity. The remaining units reflects the work
+        #  remaining to be done for the activity. Before the activity is started, the remaining units are the same as
+        #  the planned units. After the activity is completed, the remaining units are zero.
+        self.remain_work_qty = locale.atof(params.get('remain_work_qty')) if params.get('remain_work_qty') else None
+        # The planned units for all labor resources assigned to the activity.
+        self.target_work_qty = locale.atof(params.get('target_work_qty')) if params.get('target_work_qty') else None
+        # Original Duration is the planned working time for the resource assignment on the activity,
+        # from the resource's planned start date to the planned finish date. The planned working time is computed
+        # using the calendar determined by the Activity Type. Resource Dependent activities use the resource's
+        # calendar; other activity types use the activity's calendar. This is the duration that Timesheets users
+        # follow and the schedule variance is measured against.
+        self.target_drtn_hr_cnt = locale.atof(params.get('target_drtn_hr_cnt').strip()) if params.get('target_drtn_hr_cnt') else None
+        # The planned units for all nonlabor resources assigned to the activity.
+        self.target_equip_qty = locale.atof(params.get('target_equip_qty')) if params.get('target_equip_qty') else None
+        # The actual units for all nonlabor resources assigned to the activities under the WBS.
+        self.act_equip_qty = locale.atof(params.get('act_equip_qty')) if params.get('act_equip_qty') else None
+        # The remaining units for all nonlabor resources assigned to the activity. The remaining units reflects the
+        # work remaining to be done for the activity.  Before the activity is started, the remaining units are the
+        # same as the planned units. After the activity is completed, the remaining units are zero.
+        self.remain_equip_qty = locale.atof(params.get('remain_equip_qty')) if params.get('remain_equip_qty') else None
+        # The constraint date for the activity, if the activity has a constraint. The activity's constraint type
+        # determines whether this is a start date or finish date.  Activity constraints are used by the project
+        # scheduler.
+        self.cstr_date = datetime.strptime(params.get('cstr_date'), '%Y-%m-%d %H:%M') if params.get('cstr_date') else None
+        # The date on which the activity is actually started.
+        self.act_start_date = datetime.strptime(params.get('act_start_date'), '%Y-%m-%d %H:%M') if params.get('act_start_date') else None
+        # The date on which the activity is actually finished.
+        self.act_end_date = datetime.strptime(params.get('act_end_date'), '%Y-%m-%d %H:%M') if params.get('act_end_date') else None
+        # the activity late start date
+        self.late_start_date = datetime.strptime(params.get('late_start_date'), '%Y-%m-%d %H:%M') if params.get('late_start_date') else None
+        # The latest possible date the activity must finish without delaying the project finish date. This date is
+        # computed by the project scheduler based on network logic, schedule constraints, and resource availability.
+        self.late_end_date = datetime.strptime(params.get('late_end_date'), '%Y-%m-%d %H:%M') if params.get('late_end_date') else None
+        # The date the activity is expected to be finished according to the progress made on the activity's work
+        # products. The expected finish date is entered manually by people familiar with progress of the activity's
+        # work products.
+        self.expect_end_date = datetime.strptime(params.get('expect_end_date'), '%Y-%m-%d %H:%M') if params.get('expect_end_date') else None
+        # The earliest possible date the remaining work for the activity can begin. This date is computed by the
+        # project scheduler based on network logic, schedule constraints, and resource availability.
+        self.early_start_date = datetime.strptime(params.get('early_start_date'), '%Y-%m-%d %H:%M') if params.get('early_start_date') else None
+        # The earliest possible date the activity can finish. This date is computed by the project scheduler based on
+        #  network logic, schedule constraints, and resource availability.
+        self.early_end_date = datetime.strptime(params.get('early_end_date'), '%Y-%m-%d %H:%M') if params.get('early_end_date') else None
+        # The date the remaining work for the activity is scheduled to begin. This date is computed by the project
+        # scheduler but can be updated manually by the project manager.  Before the activity is started,
+        # the remaining start date is the same as the planned start date.  This is the start date that Timesheets
+        # users follow.
+        self.restart_date = datetime.strptime(params.get('restart_date'), '%Y-%m-%d %H:%M') if params.get('restart_date') else None
+        # The date the remaining work for the activity is scheduled to finish. This date is computed by the project
+        # scheduler but can be updated manually by the project manager. Before the activity is started, the remaining
+        #  finish date is the same as the planned finish date.  This is the finish date that Timesheets users follow.
+        self.reend_date = datetime.strptime(params.get('reend_date'), '%Y-%m-%d %H:%M') if params.get('reend_date') else None
+        # The date the activity is scheduled to begin. This date is computed by the project scheduler but can be
+        # updated manually by the project manager. This date is not changed by the project scheduler after the
+        # activity has been started.
+        self.target_start_date = datetime.strptime(params.get('target_start_date'), '%Y-%m-%d %H:%M') if params.get('target_start_date') else None
+        # The date the activity is scheduled to finish. This date is computed by the project scheduler but can be
+        # updated manually by the project manager.  This date is not changed by the project scheduler after the
+        # activity has been started.
+        self.target_end_date = datetime.strptime(params.get('target_end_date'), '%Y-%m-%d %H:%M') if params.get('target_end_date') else None
+        # Remaining late start date is calculated by the scheduler.
+        self.rem_late_start_date = datetime.strptime(params.get('rem_late_start_date'), '%Y-%m-%d %H:%M') if params.get('rem_late_start_date') else None
+        # Remaining late end date is calculated by the scheduler.
+        self.rem_late_end_date = datetime.strptime(params.get('rem_late_end_date'), '%Y-%m-%d %H:%M') if params.get('rem_late_end_date') else None
+        # The type of constraint applied to the activity start or finish date. Activity constraints are used by the
+        # project scheduler.  Start date constraints are 'Start On', 'Start On or Before', 'Start On or After' and
+        # 'Mandatory Start'.  Finish date constraints are 'Finish On', 'Finish On or Before', 'Finish On or After'
+        # and 'Mandatory Finish'.  Another type of constraint, 'As Late as Possible', schedules the activity as late
+        # as possible based on the available free int.
+        self.cstr_type = params.get('cstr_type').strip() if params.get('cstr_type') else None
+        self.priority_type = params.get('priority_type').strip() if params.get('priority_type') else None
+        # The date progress is suspended on an activity.
+        self.suspend_date = datetime.strptime(params.get('suspend_date').strip(), '%Y-%m-%d %H:%M') if params.get('suspend_date') else None
+        # The date progress is resumed on an activity.
+        self.resume_date = datetime.strptime(params.get('resume_date').strip(), '%Y-%m-%d %H:%M') if params.get('resume_date') else None
+        self.int_path = params.get('int_path').strip() if params.get('int_path') else None
+        # This field is computed by the project scheduler and identifies the order in which the activities were
+        # processed within the int path.
+        self.int_path_order = params.get('int_path_order').strip() if params.get('int_path_order') else None
+        self.guid = params.get('guid').strip() if params.get('guid') else None
+        self.tmpl_guid = params.get('tmpl_guid').strip() if params.get('tmpl_guid') else None
+        # The second constraint date for the activity, if the activity has a constraint.
+        self.cstr_date2 = datetime.strptime(params.get('cstr_date2'), '%Y-%m-%d %H:%M') if params.get('cstr_date2') else None
+        # The second type of constraint applied to the activity start or finish date.
+        self.cstr_type2 = params.get('cstr_type2').strip() if params.get('cstr_type2') else None
+        self.driving_path_flag = params.get('driving_path_flag') if params.get('driving_path_flag') else None
+        # The actual this period units for all labor resources assigned to the activity.
+        self.act_this_per_work_qty = locale.atof(params.get('act_this_per_work_qty')) if params.get('act_this_per_work_qty') else None
+        # The actual this period units for all nonlabor resources assigned to the activity.
+        self.act_this_per_equip_qty = locale.atof(params.get('act_this_per_equip_qty')) if params.get('act_this_per_equip_qty') else None
+        # The External Early Start date is the date the external relationship was scheduled to finish.  This date may
+        #  be used to calculate the start date of the current activity during scheduling.  This field is populated on
+        #  import when an external relationship is lost.
+        try:
+            self.external_early_start_date = datetime.strptime(params.get('external_early_start_date').strip(), '%Y-%m-%d %H:%M') if params.get('external_early_start_date') else None
+            self.external_late_end_date = datetime.strptime(params.get('external_late_end_date'), '%Y-%m-%d %H:%M') if params.get('external_late_end_date') else None
+        except:
+            pass
+        self.create_date = datetime.strptime(params.get('create_date'), '%Y-%m-%d %H:%M') if params.get('create_date') else None
+        self.update_date = datetime.strptime(params.get('update_date'), '%Y-%m-%d %H:%M') if params.get('update_date') else None
+        self.create_user = params.get('create_user').strip() if params.get('create_user') else None
+        self.update_user = params.get('update_user').strip() if params.get('update_user') else None
+        self.location_id = params.get('location_id').strip() if params.get('location_id') else None
+        self.calendar = Calendar.find_by_id(self.clndr_id)
+        # self.wbs = WBS.find_by_id(int(self.wbs_id) if self.wbs_id else None)
+        # Task.obj_list.append(self)
+        self.data = data
+
+    def get_tsv(self):
+        tsv = ['%R', self.task_id, self.proj_id, self.wbs_id, self.clndr_id, self.phys_complete_pct, self.rev_fdbk_flag,
+               self.est_wt, self.lock_plan_flag, self.auto_compute_act_flag, self.complete_pct_type, self.task_type,
+               self.duration_type, self.status_code, self.task_code, self.task_name, self.rsrc_id,
+               self.total_float_hr_cnt, self.free_float_hr_cnt, self.remain_drtn_hr_cnt, self.act_work_qty,
+               self.remain_work_qty, self.target_work_qty, self.target_drtn_hr_cnt, self.target_equip_qty,
+               self.act_equip_qty, self.remain_equip_qty,
+               self.cstr_date.strftime('%Y-%m-%d %H:%M') if self.cstr_date else None,
+               self.act_start_date.strftime('%Y-%m-%d %H:%M') if self.act_start_date else None,
+               self.act_end_date.strftime('%Y-%m-%d %H:%M') if self.act_end_date else None,
+               self.late_start_date.strftime('%Y-%m-%d %H:%M') if self.late_start_date else None,
+               self.late_end_date.strftime('%Y-%m-%d %H:%M') if self.late_end_date else None,
+               self.expect_end_date.strftime('%Y-%m-%d %H:%M') if self.expect_end_date else None,
+               self.early_start_date.strftime('%Y-%m-%d %H:%M') if self.early_start_date else None,
+               self.early_end_date.strftime('%Y-%m-%d %H:%M') if self.early_end_date else None,
+               self.restart_date.strftime('%Y-%m-%d %H:%M') if self.restart_date else None,
+               self.reend_date.strftime('%Y-%m-%d %H:%M') if self.reend_date else None,
+               self.target_start_date.strftime('%Y-%m-%d %H:%M') if self.target_start_date else None,
+               self.target_end_date.strftime('%Y-%m-%d %H:%M') if self.target_end_date else None,
+               self.rem_late_start_date.strftime('%Y-%m-%d %H:%M') if self.rem_late_start_date else None,
+               self.rem_late_end_date.strftime('%Y-%m-%d %H:%M') if self.rem_late_end_date else None,
+               self.cstr_type, self.priority_type,
+               self.suspend_date.strftime('%Y-%m-%d %H:%M') if self.suspend_date else None,
+               self.resume_date.strftime('%Y-%m-%d %H:%M') if self.resume_date else None,
+               self.int_path, self.int_path_order, self.guid, self.tmpl_guid,
+               self.cstr_date2.strftime('%Y-%m-%d %H:%M') if self.cstr_date2 else None,
+               self.cstr_type2, self.driving_path_flag,
+               self.act_this_per_work_qty, self.act_this_per_equip_qty,
+               self.external_early_start_date.strftime('%Y-%m-%d %H:%M') if self.external_early_start_date else None,
+               self.external_late_end_date.strftime('%Y-%m-%d %H:%M') if self.external_late_end_date else None,
+               self.create_date.strftime('%Y-%m-%d %H:%M') if self.create_date else None,
+               self.update_date.strftime('%Y-%m-%d %H:%M') if self.update_date else None,
+               self.create_user, self.update_user, self.location_id]
+        return tsv
+
+    @property
+    def id(self):
+        return self.task_id
+
+    @property
+    def totalint(self):
+        if self.total_int_hr_cnt:
+            tf = int(self.total_int_hr_cnt)/8.0
+        else:
+            return None
+        return tf
+
+    @property
+    def resources(self):
+        return self.data.taskresource.find_by_activity_id(self.task_id)
+
+    @property
+    def steps(self):
+        return TaskProcs.find_by_activity_id(self.task_id)
+
+    @property
+    def activitycodes(self):
+        return self .data.taskactvcodes.find_by_activity_id(self.task_id)
+
+
+    @property
+    def duration(self):
+        dur = None
+        if self.target_drtn_hr_cnt:
+            if self.calendar.day_hr_cnt:
+                dur = self.target_drtn_hr_cnt / self.calendar.day_hr_cnt
+            else:
+                dur = self.target_drtn_hr_cnt / 8.0
+        else:
+            dur =0.0
+        return dur
+
+    @property
+    def constraints(self):
+        if self.cstr_type == None or self.cstr_date == None:
+            return  None
+        return {"ConstraintType": self.cstr_type,
+                "ConstrintDate": self.cstr_date
+               }
+
+    @property
+    def start_date(self):
+        if self.act_start_date:
+            return self.act_start_date
+        else:
+            return self.target_start_date
+
+    @property
+    def end_date(self):
+        if self.act_end_date:
+            return self.act_end_date
+        else:
+            return self.target_end_date
+
+    @property
+    def successors(self):
+        suss = self.data.predecessors.get_successors(self.task_id)
+        return suss
+
+    @property
+    def predecessors(self):
+        return self.data.predecessors.get_predecessors(self.task_id)
+
+    @classmethod
+    def find_by_wbs_id(cls, wbs_id):
+        return [v for v in cls.obj_list if v.wbs_id == wbs_id]
+
+    def __repr__(self):
+        return self.task_code
+
+
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/taskactv.py` & `PyP6Xer-1.15.0/xerparser/model/classes/taskactv.py`

 * *Ordering differences only*

 * *Files 18% similar despite different names*

```diff
@@ -1,43 +1,43 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class TaskActv:
-    obj_list = []
-
-    def __init__(self, params, data):
-        self.task_id = int(params.get('task_id').strip()) if params.get('task_id') else None
-        self.actv_code_type_id = params.get('actv_code_type_id').strip()
-        self.actv_code_id = int(params.get('actv_code_id').strip()) if params.get('actv_code_id') else None
-        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
-        self.data = data
-        TaskActv.obj_list.append(self)
-
-    def get_tsv(self):
-        tsv = ['%R', self.task_id, self.actv_code_type_id, self.actv_code_id, self.proj_id]
-        return tsv
-
-    def get_id(self):
-        return self.task_id
-
-    @staticmethod
-    def find_by_id(code_id, activity_code_dict):
-        return {k: v for k, v in activity_code_dict.items() if v.actv_code_id == code_id}
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class TaskActv:
+    obj_list = []
+
+    def __init__(self, params, data):
+        self.task_id = int(params.get('task_id').strip()) if params.get('task_id') else None
+        self.actv_code_type_id = params.get('actv_code_type_id').strip()
+        self.actv_code_id = int(params.get('actv_code_id').strip()) if params.get('actv_code_id') else None
+        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
+        self.data = data
+        TaskActv.obj_list.append(self)
+
+    def get_tsv(self):
+        tsv = ['%R', self.task_id, self.actv_code_type_id, self.actv_code_id, self.proj_id]
+        return tsv
+
+    def get_id(self):
+        return self.task_id
+
+    @staticmethod
+    def find_by_id(code_id, activity_code_dict):
+        return {k: v for k, v in activity_code_dict.items() if v.actv_code_id == code_id}
+
+    def __repr__(self):
         return str(self.task_id) + '->' + str(self.actv_code_id)
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/taskpred.py` & `PyP6Xer-1.15.0/xerparser/model/classes/taskpred.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,46 +1,46 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class TaskPred:
-
-    obj_list = []
-
-    def __init__(self, params):
-        self.task_pred_id = params.get('task_pred_id').strip() if params.get('task_pred_id') else None
-        self.task_id = int(params.get('task_id')) if params.get('task_id') else None
-        self.pred_task_id = int(params.get('pred_task_id')) if params.get('pred_task_id') else None
-        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
-        self.pred_proj_id = int(params.get('proj_id').strip()) if params.get('pred_proj_id') else None
-        self.pred_type = params.get('pred_type').strip() if params.get('pred_type') else None
-        self.lag_hr_cnt = int(params.get('lag_hr_cnt').strip()) if params.get('lag_hr_cnt') else None
-        self.float_path = params.get('float_path').strip() if params.get('float_path') else None
-        self.aref = params.get('aref').strip() if params.get('aref') else None
-        self.arls = params.get('arls').strip() if params.get('arls') else None
-        self.comments = params.get('comments').strip() if params.get('comments') else None
-        TaskPred.obj_list.append(self)
-
-    def get_id(self):
-        return self.task_pred_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.task_pred_id, self.task_id, self.pred_task_id, self.proj_id, self.pred_proj_id,
-               self.pred_type, self.lag_hr_cnt, self.comments, self.float_path, self.aref, self.arls]
-        return tsv
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class TaskPred:
+
+    obj_list = []
+
+    def __init__(self, params):
+        self.task_pred_id = params.get('task_pred_id').strip() if params.get('task_pred_id') else None
+        self.task_id = int(params.get('task_id')) if params.get('task_id') else None
+        self.pred_task_id = int(params.get('pred_task_id')) if params.get('pred_task_id') else None
+        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
+        self.pred_proj_id = int(params.get('proj_id').strip()) if params.get('pred_proj_id') else None
+        self.pred_type = params.get('pred_type').strip() if params.get('pred_type') else None
+        self.lag_hr_cnt = int(params.get('lag_hr_cnt').strip()) if params.get('lag_hr_cnt') else None
+        self.float_path = params.get('float_path').strip() if params.get('float_path') else None
+        self.aref = params.get('aref').strip() if params.get('aref') else None
+        self.arls = params.get('arls').strip() if params.get('arls') else None
+        self.comments = params.get('comments').strip() if params.get('comments') else None
+        TaskPred.obj_list.append(self)
+
+    def get_id(self):
+        return self.task_pred_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.task_pred_id, self.task_id, self.pred_task_id, self.proj_id, self.pred_proj_id,
+               self.pred_type, self.lag_hr_cnt, self.comments, self.float_path, self.aref, self.arls]
+        return tsv
+    def __repr__(self):
         return str(self.task_id) + '- ' + self.pred_type + ' ->' + str(self.pred_task_id) + ' lag: ' + str(self.lag_hr_cnt)
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/taskproc.py` & `PyP6Xer-1.15.0/xerparser/model/classes/taskproc.py`

 * *Ordering differences only*

 * *Files 10% similar despite different names*

```diff
@@ -1,45 +1,45 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class TaskProc:
-
-    def __init__(self, params):
-
-        self.complete_flag = params.get('complete_flag').strip() if params.get('complete_flag') else None
-        self.complete_pct = params.get('complete_pct').strip() if params.get('complete_pct') else None
-        self.proc_descr = params.get('proc_descr').strip() if params.get('proc_descr') else None
-        self.proc_id = params.get('proc_id').strip() if params.get('proc_id') else None
-        self.proc_name = params.get('proc_name').strip() if params.get('proc_name') else None
-        self.proc_wt = params.get('proc_wt').strip() if params.get('proc_wt') else None
-        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
-        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
-        self.task_id = params.get('task_id').strip() if params.get('task_id') else None
-
-
-    def get_id(self):
-        return self.proc_id
-
-    def get_tsv(self):
-        tsv = ["%R", self.proc_id, self.task_id, self.proj_id, self.seq_num, self.proc_name, self.complete_flag,
-               self.proc_wt, self.complete_pct, self.proc_descr ]
-        return tsv
-
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class TaskProc:
+
+    def __init__(self, params):
+
+        self.complete_flag = params.get('complete_flag').strip() if params.get('complete_flag') else None
+        self.complete_pct = params.get('complete_pct').strip() if params.get('complete_pct') else None
+        self.proc_descr = params.get('proc_descr').strip() if params.get('proc_descr') else None
+        self.proc_id = params.get('proc_id').strip() if params.get('proc_id') else None
+        self.proc_name = params.get('proc_name').strip() if params.get('proc_name') else None
+        self.proc_wt = params.get('proc_wt').strip() if params.get('proc_wt') else None
+        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
+        self.seq_num = params.get('seq_num').strip() if params.get('seq_num') else None
+        self.task_id = params.get('task_id').strip() if params.get('task_id') else None
+
+
+    def get_id(self):
+        return self.proc_id
+
+    def get_tsv(self):
+        tsv = ["%R", self.proc_id, self.task_id, self.proj_id, self.seq_num, self.proc_name, self.complete_flag,
+               self.proc_wt, self.complete_pct, self.proc_descr ]
+        return tsv
+
+
+    def __repr__(self):
         return self.proc_id + '->' + self.task_id
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/taskrsrc.py` & `PyP6Xer-1.15.0/xerparser/model/classes/taskrsrc.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,95 +1,95 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.resources import Resources
-import locale
-class TaskRsrc:
-
-    def __init__(self, params, data=None):
-        self.taskrsrc_id = int(params.get('taskrsrc_id').strip()) if params.get('taskrsrc_id') else None
-        self.task_id = int(params.get('task_id').strip()) if params.get('task_id') else None
-        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
-        self.cost_qty_link_flag = params.get('cost_qty_link_flag').strip() if params.get('cost_qty_link_flag') else None
-        self.role_id = params.get('role_id').strip() if params.get('role_id') else None
-        self.acct_id = params.get('acct_id').strip() if params.get('acct_id') else None
-        self.rsrc_id = int(params.get('rsrc_id').strip()) if params.get('rsrc_id') else None
-        self.pobs_id = params.get('pobs_id').strip() if params.get('pobs_id') else None
-        self.skill_level = params.get('skill_level').strip() if params.get('skill_level') else None
-        self.remain_qty = locale.atof(params.get('remain_qty').strip()) if params.get('remain_qty') else None
-        self.target_qty = locale.atof(params.get('target_qty').strip()) if params.get('target_qty') else None
-        self.remain_qty_per_hr = locale.atof(params.get('remain_qty_per_hr').strip()) if params.get('remain_qty_per_hr') else None
-        self.target_lag_drtn_hr_cnt = locale.atof(params.get('target_lag_drtn_hr_cnt').strip()) if params.get('target_lag_drtn_hr_cnt') else None
-        self.target_qty_per_hr = params.get('target_qty_per_hr').strip() if params.get('target_qty_per_hr') else None
-        self.act_ot_qty = params.get('act_ot_qty').strip() if params.get('act_ot_qty') else None
-        self.act_reg_qty = params.get('act_reg_qty').strip() if params.get('act_reg_qty') else None
-        self.relag_drtn_hr_cnt = params.get('relag_drtn_hr_cnt').strip() if params.get('relag_drtn_hr_cnt') else None
-        self.ot_factor = params.get('ot_factor').strip() if params.get('ot_factor') else None
-        self.cost_per_qty = params.get('cost_per_qty').strip() if params.get('cost_per_qty') else None
-        self.target_cost = params.get('target_cost').strip() if params.get('target_cost') else None
-        self.act_reg_cost = locale.atof(params.get('act_reg_cost').strip()) if params.get('act_reg_cost') else None
-        self.act_ot_cost = params.get('act_ot_cost').strip() if params.get('act_ot_cost') else None
-        self.remain_cost = params.get('remain_cost').strip() if params.get('remain_cost') else None
-        self.act_start_date = params.get('act_start_date').strip() if params.get('act_start_date') else None
-        self.act_end_date = params.get('act_end_date').strip() if params.get('act_end_date') else None
-        self.restart_date = params.get('restart_date').strip() if params.get('restart_date') else None
-        self.reend_date = params.get('reend_date').strip() if params.get('reend_date') else None
-        self.target_start_date = params.get('target_start_date').strip() if params.get('target_start_date') else None
-        self.target_end_date = params.get('target_end_date').strip() if params.get('target_end_date') else None
-        self.rem_late_start_date = params.get('rem_late_start_date').strip() if params.get('rem_late_start_date') else None
-        self.rem_late_end_date = params.get('rem_late_end_date').strip() if params.get('rem_late_end_date') else None
-        self.rollup_dates_flag = params.get('rollup_dates_flag').strip() if params.get('rollup_dates_flag') else None
-        self.target_crv = params.get('target_crv').strip() if params.get('target_crv') else None
-        self.remain_crv = params.get('remain_crv').strip() if params.get('remain_crv') else None
-        self.actual_crv = params.get('actual_crv').strip() if params.get('actual_crv') else None
-        self.ts_pend_act_end_flag = params.get('ts_pend_act_end_flag').strip() if params.get('ts_pend_act_end_flag') else None
-        self.guid = params.get('guid').strip() if params.get('guid') else None
-        self.rate_type = params.get('rate_type').strip() if params.get('rate_type') else None
-        self.act_this_per_cost = params.get('act_this_per_cost').strip() if params.get('act_this_per_cost') else None
-        self.act_this_per_qty = params.get('act_this_per_cost').strip() if params.get('act_this_per_cost') else None
-        self.curv_id = params.get('curv_id').strip() if params.get('curv_id') else None
-        self.rsrc_type = params.get('rsrc_type').strip() if params.get('rsrc_type') else None
-        self.cost_per_qty_source_type = params.get('cost_per_qty_source_type').strip() if params.get('cost_per_qty_source_type') else None
-        self.create_user = params.get('create_user').strip() if params.get('create_user') else None
-        self.create_date = params.get('create_date').strip() if params.get('create_date') else None
-        self.cbs_id = params.get('cbs_id').strip() if params.get('cbs_id') else None
-        self.has_rsrchours = params.get('has_rsrchours').strip() if params.get('has_rsrchours') else None
-        self.taskrsrc_sum_id = params.get('taskrsrc_sum_id').strip() if params.get('taskrsrc_sum_id') else None
-        self.data = data
-
-    def get_id(self):
-        return self.taskrsrc_id
-    @property
-    def resource(self):
-        return self.data.resources.get_resource_by_id(self.rsrc_id)
-
-    def get_tsv(self):
-        tsv = ['%R', self.taskrsrc_id, self.task_id, self.proj_id, self.cost_qty_link_flag, self.role_id, self.acct_id,
-               self.rsrc_id, self.pobs_id, self.skill_level, self.remain_qty, self.target_qty, self.remain_qty_per_hr,
-               self.target_lag_drtn_hr_cnt, self.target_qty_per_hr, self.act_ot_qty, self.act_reg_qty,
-               self.relag_drtn_hr_cnt, self.ot_factor, self.cost_per_qty, self.target_cost, self.act_reg_cost,
-               self.act_ot_cost, self.remain_cost, self.act_start_date, self.act_end_date, self.restart_date,
-               self.reend_date, self.target_start_date, self.target_end_date, self.rem_late_start_date,
-               self.rem_late_end_date, self.rollup_dates_flag, self.target_crv, self.remain_crv, self.actual_crv,
-               self.ts_pend_act_end_flag, self.guid, self.rate_type, self.act_this_per_cost, self.act_this_per_qty,
-               self.curv_id, self.rsrc_type, self.cost_per_qty_source_type, self.create_user, self.create_date,
-               self.cbs_id, self.has_rsrchours, self.taskrsrc_sum_id]
-        return tsv
-
-    def __repr__(self):
-        return str(self.task_id) + '->' + str(self.rsrc_id) + ' = ' + str(self.target_qty)
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.resources import Resources
+import locale
+class TaskRsrc:
+
+    def __init__(self, params, data=None):
+        self.taskrsrc_id = int(params.get('taskrsrc_id').strip()) if params.get('taskrsrc_id') else None
+        self.task_id = int(params.get('task_id').strip()) if params.get('task_id') else None
+        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
+        self.cost_qty_link_flag = params.get('cost_qty_link_flag').strip() if params.get('cost_qty_link_flag') else None
+        self.role_id = params.get('role_id').strip() if params.get('role_id') else None
+        self.acct_id = params.get('acct_id').strip() if params.get('acct_id') else None
+        self.rsrc_id = int(params.get('rsrc_id').strip()) if params.get('rsrc_id') else None
+        self.pobs_id = params.get('pobs_id').strip() if params.get('pobs_id') else None
+        self.skill_level = params.get('skill_level').strip() if params.get('skill_level') else None
+        self.remain_qty = locale.atof(params.get('remain_qty').strip()) if params.get('remain_qty') else None
+        self.target_qty = locale.atof(params.get('target_qty').strip()) if params.get('target_qty') else None
+        self.remain_qty_per_hr = locale.atof(params.get('remain_qty_per_hr').strip()) if params.get('remain_qty_per_hr') else None
+        self.target_lag_drtn_hr_cnt = locale.atof(params.get('target_lag_drtn_hr_cnt').strip()) if params.get('target_lag_drtn_hr_cnt') else None
+        self.target_qty_per_hr = params.get('target_qty_per_hr').strip() if params.get('target_qty_per_hr') else None
+        self.act_ot_qty = params.get('act_ot_qty').strip() if params.get('act_ot_qty') else None
+        self.act_reg_qty = params.get('act_reg_qty').strip() if params.get('act_reg_qty') else None
+        self.relag_drtn_hr_cnt = params.get('relag_drtn_hr_cnt').strip() if params.get('relag_drtn_hr_cnt') else None
+        self.ot_factor = params.get('ot_factor').strip() if params.get('ot_factor') else None
+        self.cost_per_qty = params.get('cost_per_qty').strip() if params.get('cost_per_qty') else None
+        self.target_cost = params.get('target_cost').strip() if params.get('target_cost') else None
+        self.act_reg_cost = locale.atof(params.get('act_reg_cost').strip()) if params.get('act_reg_cost') else None
+        self.act_ot_cost = params.get('act_ot_cost').strip() if params.get('act_ot_cost') else None
+        self.remain_cost = params.get('remain_cost').strip() if params.get('remain_cost') else None
+        self.act_start_date = params.get('act_start_date').strip() if params.get('act_start_date') else None
+        self.act_end_date = params.get('act_end_date').strip() if params.get('act_end_date') else None
+        self.restart_date = params.get('restart_date').strip() if params.get('restart_date') else None
+        self.reend_date = params.get('reend_date').strip() if params.get('reend_date') else None
+        self.target_start_date = params.get('target_start_date').strip() if params.get('target_start_date') else None
+        self.target_end_date = params.get('target_end_date').strip() if params.get('target_end_date') else None
+        self.rem_late_start_date = params.get('rem_late_start_date').strip() if params.get('rem_late_start_date') else None
+        self.rem_late_end_date = params.get('rem_late_end_date').strip() if params.get('rem_late_end_date') else None
+        self.rollup_dates_flag = params.get('rollup_dates_flag').strip() if params.get('rollup_dates_flag') else None
+        self.target_crv = params.get('target_crv').strip() if params.get('target_crv') else None
+        self.remain_crv = params.get('remain_crv').strip() if params.get('remain_crv') else None
+        self.actual_crv = params.get('actual_crv').strip() if params.get('actual_crv') else None
+        self.ts_pend_act_end_flag = params.get('ts_pend_act_end_flag').strip() if params.get('ts_pend_act_end_flag') else None
+        self.guid = params.get('guid').strip() if params.get('guid') else None
+        self.rate_type = params.get('rate_type').strip() if params.get('rate_type') else None
+        self.act_this_per_cost = params.get('act_this_per_cost').strip() if params.get('act_this_per_cost') else None
+        self.act_this_per_qty = params.get('act_this_per_cost').strip() if params.get('act_this_per_cost') else None
+        self.curv_id = params.get('curv_id').strip() if params.get('curv_id') else None
+        self.rsrc_type = params.get('rsrc_type').strip() if params.get('rsrc_type') else None
+        self.cost_per_qty_source_type = params.get('cost_per_qty_source_type').strip() if params.get('cost_per_qty_source_type') else None
+        self.create_user = params.get('create_user').strip() if params.get('create_user') else None
+        self.create_date = params.get('create_date').strip() if params.get('create_date') else None
+        self.cbs_id = params.get('cbs_id').strip() if params.get('cbs_id') else None
+        self.has_rsrchours = params.get('has_rsrchours').strip() if params.get('has_rsrchours') else None
+        self.taskrsrc_sum_id = params.get('taskrsrc_sum_id').strip() if params.get('taskrsrc_sum_id') else None
+        self.data = data
+
+    def get_id(self):
+        return self.taskrsrc_id
+    @property
+    def resource(self):
+        return self.data.resources.get_resource_by_id(self.rsrc_id)
+
+    def get_tsv(self):
+        tsv = ['%R', self.taskrsrc_id, self.task_id, self.proj_id, self.cost_qty_link_flag, self.role_id, self.acct_id,
+               self.rsrc_id, self.pobs_id, self.skill_level, self.remain_qty, self.target_qty, self.remain_qty_per_hr,
+               self.target_lag_drtn_hr_cnt, self.target_qty_per_hr, self.act_ot_qty, self.act_reg_qty,
+               self.relag_drtn_hr_cnt, self.ot_factor, self.cost_per_qty, self.target_cost, self.act_reg_cost,
+               self.act_ot_cost, self.remain_cost, self.act_start_date, self.act_end_date, self.restart_date,
+               self.reend_date, self.target_start_date, self.target_end_date, self.rem_late_start_date,
+               self.rem_late_end_date, self.rollup_dates_flag, self.target_crv, self.remain_crv, self.actual_crv,
+               self.ts_pend_act_end_flag, self.guid, self.rate_type, self.act_this_per_cost, self.act_this_per_qty,
+               self.curv_id, self.rsrc_type, self.cost_per_qty_source_type, self.create_user, self.create_date,
+               self.cbs_id, self.has_rsrchours, self.taskrsrc_sum_id]
+        return tsv
+
+    def __repr__(self):
+        return str(self.task_id) + '->' + str(self.rsrc_id) + ' = ' + str(self.target_qty)
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/udftype.py` & `PyP6Xer-1.15.0/xerparser/model/classes/udftype.py`

 * *Ordering differences only*

 * *Files 13% similar despite different names*

```diff
@@ -1,55 +1,55 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class UDFType:
-
-    udf_type_id = None
-    table_name = None
-    udf_type_name = None
-    udf_type_label = None
-    logical_data_type = None
-    super_flag = None
-    indicator_expression = None
-    summary_indicator_expression = None
-
-    def __init__(self, params):
-        # %F	udf_type_id	table_name	udf_type_name	udf_type_label	logical_data_type
-        # super_flag	indicator_expression	summary_indicator_expression	export_flag
-        self.udf_type_id = params.get('udf_type_id').strip() if params.get('udf_type_id') else None
-        self.table_name = params.get('table_name').strip() if params.get('table_name') else None
-        self.udf_type_name = params.get('udf_type_name').strip() if params.get('udf_type_name') else None
-        self.udf_type_label = params.get('udf_type_label').strip() if params.get('udf_type_label') else None
-        self.logical_data_type = params.get('logical_data_type').strip() if params.get('logical_data_type') else None
-        self.super_flag = params.get('super_flag').strip() if params.get('super_flag') else None
-        self.indicator_expression = params.get('indicator_expression').strip() if params.get(
-            'indicator_expression') else None
-        self.summary_indicator_expression = params.get('summary_indicator_expression').strip() if params.get(
-            'summary_indicator_expression') else None
-        self.export_flag = params.get('export_flag').strip() if params.get('export_flag') else None
-
-    def get_id(self):
-        return self.udf_type_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.udf_type_id, self.table_name, self.udf_type_name, self.udf_type_label, self.logical_data_type,
-               self.super_flag, self.indicator_expression, self.summary_indicator_expression, self.export_flag]
-        return tsv
-
-    def __repr__(self):
-        return self.udf_type_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class UDFType:
+
+    udf_type_id = None
+    table_name = None
+    udf_type_name = None
+    udf_type_label = None
+    logical_data_type = None
+    super_flag = None
+    indicator_expression = None
+    summary_indicator_expression = None
+
+    def __init__(self, params):
+        # %F	udf_type_id	table_name	udf_type_name	udf_type_label	logical_data_type
+        # super_flag	indicator_expression	summary_indicator_expression	export_flag
+        self.udf_type_id = params.get('udf_type_id').strip() if params.get('udf_type_id') else None
+        self.table_name = params.get('table_name').strip() if params.get('table_name') else None
+        self.udf_type_name = params.get('udf_type_name').strip() if params.get('udf_type_name') else None
+        self.udf_type_label = params.get('udf_type_label').strip() if params.get('udf_type_label') else None
+        self.logical_data_type = params.get('logical_data_type').strip() if params.get('logical_data_type') else None
+        self.super_flag = params.get('super_flag').strip() if params.get('super_flag') else None
+        self.indicator_expression = params.get('indicator_expression').strip() if params.get(
+            'indicator_expression') else None
+        self.summary_indicator_expression = params.get('summary_indicator_expression').strip() if params.get(
+            'summary_indicator_expression') else None
+        self.export_flag = params.get('export_flag').strip() if params.get('export_flag') else None
+
+    def get_id(self):
+        return self.udf_type_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.udf_type_id, self.table_name, self.udf_type_name, self.udf_type_label, self.logical_data_type,
+               self.super_flag, self.indicator_expression, self.summary_indicator_expression, self.export_flag]
+        return tsv
+
+    def __repr__(self):
+        return self.udf_type_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/udfvalue.py` & `PyP6Xer-1.15.0/xerparser/model/classes/udfvalue.py`

 * *Ordering differences only*

 * *Files 15% similar despite different names*

```diff
@@ -1,52 +1,52 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-class UDFValue:
-
-    udf_code_id = None
-    udf_type_id = None
-    fk_id = None
-    proj_id = None
-    udf_number = None
-    udf_text = None
-
-    def __init__(self, params):
-
-        self.udf_type_id = params.get('udf_type_id').strip() if params.get('udf_type_id') else None
-        self.fk_id = params.get('fk_id').strip() if params.get('fk_id') else None
-        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
-        self.udf_date = params.get('udf_date').strip() if params.get('udf_date') else None
-        self.udf_number = params.get('udf_number').strip() if params.get('udf_number') else None
-        self.udf_text = params.get('udf_text').strip() if params.get('udf_text') else None
-        self.udf_code_id = params.get('udf_code_id').strip() if params.get('udf_code_id') else None
-
-    def get_id(self):
-        return self.udf_type_id
-
-    def get_tsv(self):
-        tsv = ["%R", self.udf_type_id, self.fk_id, self.proj_id, self.udf_date, self.udf_number, self.udf_text,
-               self.udf_code_id]
-        return tsv
-
-    @staticmethod
-    def find_by_id(code_id, activity_code_dict):
-        return {k: v for k, v in activity_code_dict.items() if v.actv_code_id == code_id}
-
-    def __repr__(self):
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+class UDFValue:
+
+    udf_code_id = None
+    udf_type_id = None
+    fk_id = None
+    proj_id = None
+    udf_number = None
+    udf_text = None
+
+    def __init__(self, params):
+
+        self.udf_type_id = params.get('udf_type_id').strip() if params.get('udf_type_id') else None
+        self.fk_id = params.get('fk_id').strip() if params.get('fk_id') else None
+        self.proj_id = params.get('proj_id').strip() if params.get('proj_id') else None
+        self.udf_date = params.get('udf_date').strip() if params.get('udf_date') else None
+        self.udf_number = params.get('udf_number').strip() if params.get('udf_number') else None
+        self.udf_text = params.get('udf_text').strip() if params.get('udf_text') else None
+        self.udf_code_id = params.get('udf_code_id').strip() if params.get('udf_code_id') else None
+
+    def get_id(self):
+        return self.udf_type_id
+
+    def get_tsv(self):
+        tsv = ["%R", self.udf_type_id, self.fk_id, self.proj_id, self.udf_date, self.udf_number, self.udf_text,
+               self.udf_code_id]
+        return tsv
+
+    @staticmethod
+    def find_by_id(code_id, activity_code_dict):
+        return {k: v for k, v in activity_code_dict.items() if v.actv_code_id == code_id}
+
+    def __repr__(self):
         return self.udf_text + '->' + self.udf_code_id
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/classes/wbs.py` & `PyP6Xer-1.15.0/xerparser/model/classes/wbs.py`

 * *Ordering differences only*

 * *Files 12% similar despite different names*

```diff
@@ -1,108 +1,108 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.tasks import Tasks
-from xerparser.model.classes.task import Task
-
-class WBS:
-    obj_list = []
-
-    def __init__(self, params, data=None):
-        self.wbs_id = int(params.get('wbs_id').strip()) if params.get('wbs_id') else None
-        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
-        self.obs_id = params.get('obs_id').strip()
-        self.seq_num = params.get('seq_num').strip()
-        self.est_wt = params.get('est_wt')
-        self.proj_node_flag = params.get('proj_node_flag').strip()
-        self.sum_data_flag = params.get('sum_data_flag').strip()
-        self.status_code = params.get('status_code').strip()
-        self.wbs_short_name = params.get('wbs_short_name').strip()
-        self.wbs_name = params.get('wbs_name').strip()
-        self.phase_id = params.get('phase_id').strip()
-        self.parent_wbs_id = int(params.get('parent_wbs_id')) if params.get('parent_wbs_id') else None
-        self.ev_user_pct = params.get('ev_user_pct').strip()
-        self.ev_etc_user_value = params.get('ev_etc_user_value').strip()
-        self.orig_cost = params.get('orig_cost').strip()
-        self.indep_remain_total_cost = params.get('indep_remain_total_cost').strip()
-        self.ann_dscnt_rate_pct = params.get('ann_dscnt_rate_pct').strip()
-        self.dscnt_period_type = params.get('dscnt_period_type').strip()
-        self.indep_remain_work_qty = params.get('indep_remain_work_qty').strip()
-        self.anticip_start_date = params.get('anticip_start_date').strip()
-        self.anticip_end_date = params.get('anticip_end_date').strip()
-        self.ev_compute_type = params.get('ev_compute_type').strip()
-        self.ev_etc_compute_type = params.get('ev_etc_compute_type').strip()
-        self.guid = params.get('guid').strip()
-        self.tmpl_guid = params.get('tmpl_guid').strip()
-        self.plan_open_state = params.get('plan_open_state').strip() if params.get('plan_open_state') else None
-        self.data = data
-        WBS.obj_list.append(self)
-
-    def get_id(self):
-        return self.wbs_id
-
-    def get_tsv(self):
-        tsv = ['%R', self.wbs_id, self.proj_id, self.obs_id, self.seq_num, self.est_wt,
-               self.proj_node_flag, self.sum_data_flag, self.status_code, self.wbs_short_name,
-               self.wbs_name, self.phase_id, self.parent_wbs_id, self.ev_user_pct, self.ev_etc_user_value,
-               self.orig_cost, self.indep_remain_total_cost, self.ann_dscnt_rate_pct, self.dscnt_period_type,
-               self.indep_remain_work_qty, self.anticip_start_date, self.anticip_end_date, self.ev_compute_type,
-               self.ev_etc_compute_type, self.guid, self.tmpl_guid, self.plan_open_state]
-        return tsv
-
-    @classmethod
-    def get_json(cls):
-        root_nodes = list(filter(lambda x: WBS.find_by_id(x.parent_wbs_id) is None, cls.obj_list))
-        print(root_nodes)
-        json = dict()
-        for node in root_nodes:
-            json["node"] = node
-            json["level"] = 0
-            json["childs"] = []
-            json["childs"].append(cls.get_childs(node, 0))
-        print(json)
-        return json
-
-    @classmethod
-    def get_childs(cls, node, level):
-        nodes_lst = list(filter(lambda x: x.parent_wbs_id == node.wbs_id, cls.obj_list))
-        nod = dict()
-        for node in nodes_lst:
-            nod["node"] = node
-            nod["level"] = level + 1
-            children = cls.get_childs(node, level + 1)
-            nod["childs"] = []
-            nod["childs"].append(children)
-        return nod
-    @classmethod
-    def find_by_id(cls, ID):
-        obj = list(filter(lambda x: x.wbs_id == ID, cls.obj_list))
-        if obj:
-            return obj[0]
-        return None
-
-    @classmethod
-    def find_by_project_id(cls, project_id):
-        return [ v for v in cls.obj_list if v.proj_id == project_id]
-
-    @property
-    def activities(self):
-        return self.data.tasks.activities_by_wbs_id(self.wbs_id)
-
-    def __repr__(self):
-        return self.wbs_name
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.tasks import Tasks
+from xerparser.model.classes.task import Task
+
+class WBS:
+    obj_list = []
+
+    def __init__(self, params, data=None):
+        self.wbs_id = int(params.get('wbs_id').strip()) if params.get('wbs_id') else None
+        self.proj_id = int(params.get('proj_id').strip()) if params.get('proj_id') else None
+        self.obs_id = params.get('obs_id').strip()
+        self.seq_num = params.get('seq_num').strip()
+        self.est_wt = params.get('est_wt')
+        self.proj_node_flag = params.get('proj_node_flag').strip()
+        self.sum_data_flag = params.get('sum_data_flag').strip()
+        self.status_code = params.get('status_code').strip()
+        self.wbs_short_name = params.get('wbs_short_name').strip()
+        self.wbs_name = params.get('wbs_name').strip()
+        self.phase_id = params.get('phase_id').strip()
+        self.parent_wbs_id = int(params.get('parent_wbs_id')) if params.get('parent_wbs_id') else None
+        self.ev_user_pct = params.get('ev_user_pct').strip()
+        self.ev_etc_user_value = params.get('ev_etc_user_value').strip()
+        self.orig_cost = params.get('orig_cost').strip()
+        self.indep_remain_total_cost = params.get('indep_remain_total_cost').strip()
+        self.ann_dscnt_rate_pct = params.get('ann_dscnt_rate_pct').strip()
+        self.dscnt_period_type = params.get('dscnt_period_type').strip()
+        self.indep_remain_work_qty = params.get('indep_remain_work_qty').strip()
+        self.anticip_start_date = params.get('anticip_start_date').strip()
+        self.anticip_end_date = params.get('anticip_end_date').strip()
+        self.ev_compute_type = params.get('ev_compute_type').strip()
+        self.ev_etc_compute_type = params.get('ev_etc_compute_type').strip()
+        self.guid = params.get('guid').strip()
+        self.tmpl_guid = params.get('tmpl_guid').strip()
+        self.plan_open_state = params.get('plan_open_state').strip() if params.get('plan_open_state') else None
+        self.data = data
+        WBS.obj_list.append(self)
+
+    def get_id(self):
+        return self.wbs_id
+
+    def get_tsv(self):
+        tsv = ['%R', self.wbs_id, self.proj_id, self.obs_id, self.seq_num, self.est_wt,
+               self.proj_node_flag, self.sum_data_flag, self.status_code, self.wbs_short_name,
+               self.wbs_name, self.phase_id, self.parent_wbs_id, self.ev_user_pct, self.ev_etc_user_value,
+               self.orig_cost, self.indep_remain_total_cost, self.ann_dscnt_rate_pct, self.dscnt_period_type,
+               self.indep_remain_work_qty, self.anticip_start_date, self.anticip_end_date, self.ev_compute_type,
+               self.ev_etc_compute_type, self.guid, self.tmpl_guid, self.plan_open_state]
+        return tsv
+
+    @classmethod
+    def get_json(cls):
+        root_nodes = list(filter(lambda x: WBS.find_by_id(x.parent_wbs_id) is None, cls.obj_list))
+        print(root_nodes)
+        json = dict()
+        for node in root_nodes:
+            json["node"] = node
+            json["level"] = 0
+            json["childs"] = []
+            json["childs"].append(cls.get_childs(node, 0))
+        print(json)
+        return json
+
+    @classmethod
+    def get_childs(cls, node, level):
+        nodes_lst = list(filter(lambda x: x.parent_wbs_id == node.wbs_id, cls.obj_list))
+        nod = dict()
+        for node in nodes_lst:
+            nod["node"] = node
+            nod["level"] = level + 1
+            children = cls.get_childs(node, level + 1)
+            nod["childs"] = []
+            nod["childs"].append(children)
+        return nod
+    @classmethod
+    def find_by_id(cls, ID):
+        obj = list(filter(lambda x: x.wbs_id == ID, cls.obj_list))
+        if obj:
+            return obj[0]
+        return None
+
+    @classmethod
+    def find_by_project_id(cls, project_id):
+        return [ v for v in cls.obj_list if v.proj_id == project_id]
+
+    @property
+    def activities(self):
+        return self.data.tasks.activities_by_wbs_id(self.wbs_id)
+
+    def __repr__(self):
+        return self.wbs_name
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/currencies.py` & `PyP6Xer-1.15.0/xerparser/model/udftypes.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,66 +1,63 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.currency import Currency
-
-class Currencies:
-
-
-
-    def __init__(self):
-        self.index = 0
-        self._currencies = []
-
-    def add(self, params):
-        self._currencies.append(Currency(params))
-
-    def find_by_id(self, id) -> Currency:
-        obj = list(filter(lambda x: x.curr_id == id, self._currencies))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-    
-    def get_tsv(self):
-        if len(self._currencies) > 0:
-            tsv = []
-            tsv.append(['%T', 'CURRTYPE'])
-            tsv.append(['%F', 'curr_id', 'decimal_digit_cnt', 'curr_symbol', 'decimal_symbol',
-                   'digit_group_symbol', 'pos_curr_fmt_type', 'neg_curr_fmt_type', 'curr_type', 'curr_short_name',
-                   'group_digit_cnt', 'base_exch_rate'])
-            for cur in self._currencies:
-                tsv.append(cur.get_tsv())
-            return tsv
-        return []
-
-    @property
-    def count(self):
-        return len(self._currencies)
-
-    def __len__(self):
-        return len(self._currencies)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> Currency:
-        if self.index >= len(self._currencies):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._currencies[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.udftype import UDFType
+
+class UDFTypes:
+
+    def __init__(self):
+        self.index = 0
+        self._udftypes = []
+
+    def add(self, params):
+        self._udftypes.append(UDFType(params))
+        
+    def get_tsv(self):
+        tsv = []
+        if len(self._udftypes) > 0:
+            tsv.append(['%T', 'UDFTYPE'])
+            tsv.append(['%F', 'udf_type_id', 'table_name', 'udf_type_name', 'udf_type_label', 'logical_data_type',
+                        'super_flag', 'indicator_expression', 'summary_indicator_expression', 'export_flag'])
+            for udf in self._udftypes:
+                tsv.append(udf.get_tsv())
+        return tsv
+        
+
+    def find_by_id(self, id) -> UDFType:
+        obj = list(filter(lambda x: x.udf_type_id == id, self._udftypes))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._udftypes)
+
+    def __len__(self):
+        return len(self._udftypes)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> UDFType:
+        if self.index >= len(self._udftypes):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._udftypes[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/fintmpls.py` & `PyP6Xer-1.15.0/xerparser/model/projcats.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,63 +1,62 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.fintmpl import FinTmpl
-
-
-class FinTmpls:
-
-    def __init__(self):
-        self.index = 0
-        self._FinTmpls = []
-
-    def add(self, params):
-        self._FinTmpls.append(FinTmpl(params))
-
-    def get_tsv(self):
-        if len(self._FinTmpls) > 0:
-            tsv = []
-            tsv.append(['%T', 'FINTMPL'])
-            tsv.append(["%F", 'fintmpl_id', 'fintmpl_name', 'default_flag'])
-            for fin in self._FinTmpls:
-                tsv.append(fin.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> FinTmpl:
-        obj = list(filter(lambda x: x.fintmpl_id == id, self._FinTmpls))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._FinTmpls)
-
-    def __len__(self):
-        return len(self._FinTmpls)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> FinTmpl:
-        if self.index >= len(self._FinTmpls):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._FinTmpls[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.projcat import ProjCat
+
+
+class ProjCats:
+
+    def __init__(self):
+        self.index = 0
+        self._ProjCats = []
+
+    def add(self, params):
+        self._ProjCats.append(ProjCat(params))
+
+    def get_tsv(self):
+        tsv = []
+        if len(self._ProjCats) > 0:
+            tsv.append(['%T', 'PROJPCAT'])
+            tsv.append(['%F', 'proj_id', 'proj_catg_type_id', 'proj_catg_id'])
+            for pcatval in self._ProjCats:
+                tsv.append(pcatval.get_tsv())
+        return tsv
+
+    # def find_by_id(self, id) -> ProjCat:
+    #     obj = list(filter(lambda x: x.proj_catg_id == id, self._ProjCats))
+    #     if len(obj) > 0:
+    #         return obj[0]
+    #     return obj
+
+    @property
+    def count(self):
+        return len(self._ProjCats)
+
+    def __len__(self):
+        return len(self._ProjCats)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> ProjCat:
+        if self.index >= len(self._ProjCats):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._ProjCats[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/nonworks.py` & `PyP6Xer-1.15.0/xerparser/model/taskprocs.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,63 +1,69 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.nonwork import NonWork
-
-
-class NonWorks:
-
-    def __init__(self):
-        self.index = 0
-        self._NonWorks = []
-
-    def add(self, params):
-        self._NonWorks.append(NonWork(params))
-
-    def get_tsv(self):
-        if len(self._NonWorks) > 0:
-            tsv = []
-            tsv.append(['%T', 'NONWORK'])
-            tsv.append(["%F", 'nonwork_type_id', 'seq_num', 'nonwork_code', 'nonwork_type'])
-            for nw in self._NonWorks:
-                tsv.append(nw.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> NonWork:
-        obj = list(filter(lambda x: x.fintmpl_id == id, self._NonWorks))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._NonWorks)
-
-    def __len__(self):
-        return len(self._NonWorks)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> NonWork:
-        if self.index >= len(self._NonWorks):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._NonWorks[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.taskproc import TaskProc
+
+
+class TaskProcs:
+
+
+    def __init__(self):
+        self.index = 0
+        self._TaskProcs = []
+
+    def add(self, params):
+        self._TaskProcs.append(TaskProc(params))
+
+    def get_tsv(self):
+        if len(self._TaskProcs) > 0:
+            tsv = []
+            tsv.append(['%T', 'TASKPROC'])
+            tsv.append(["%F", 'proc_id', 'task_id', 'proj_id', 'seq_num', 'proc_name', 'complete_flag',
+               'proc_wt', 'complete_pct', 'proc_descr'])
+            for taskproc in self._TaskProcs:
+                tsv.append(taskproc.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> TaskProc:
+        obj = list(filter(lambda x: x.proc_id == id, self._TaskProcs))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    def find_by_activity_id(self, id):
+        objs = list(filter(lambda x: x.task_id == id, self._TaskProcs))
+        return objs
+
+    @property
+    def count(self):
+        return len(self._TaskProcs)
+
+    def __len__(self):
+        return len(self._TaskProcs)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> TaskProc:
+        if self.index >= len(self._TaskProcs):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._TaskProcs[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/obss.py` & `PyP6Xer-1.15.0/xerparser/model/roles.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,65 +1,65 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.obs import OBS
-
-class OBSs:
-
-
-
-    def __init__(self):
-        self.index = 0
-        self._obss = []
-
-    def add(self, params):
-        self._obss.append(OBS(params))
-
-    def find_by_id(self, id) -> OBS:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._obss))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-    
-    def get_tsv(self):
-        if len(self._obss) > 0:
-            tsv = []
-            tsv.append(['%T', 'OBS'])
-            tsv.append(['%F', 'obs_id', 'parent_obs_id', 'guid', 'seq_num',
-                        'obs_name', 'obs_descr'])
-            for obs in self._obss:
-                tsv.append(obs.get_tsv())
-            return tsv
-        return []
-    
-    @property
-    def count(self):
-        return len(self._obss)
-
-    def __len__(self):
-        return len(self._obss)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> OBS:
-        if self.index >= len(self._obss):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._obss[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.role import Role
+
+
+class Roles:
+
+    def __init__(self):
+        self.index = 0
+        self._roles = []
+
+    def get_tsv(self):
+        if len(self._roles) > 0:
+            tsv = []
+            tsv.append(['%T', 'ROLE'])
+            tsv.append(['%F', 'role_id', 'parent_role_id', 'seq_num', 'role_name',
+                   'role_short_name', 'pobs_id', 'def_cost_qty_link_flag', 'cost_qty_type',
+                   'role_descr', 'last_checksum'])
+            for role in self._roles:
+                tsv.append(role.get_tsv())
+            return tsv
+        return []
+
+    def add(self, params):
+        self._roles.append(Role(params))
+
+    def find_by_id(self, id) -> Role:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._roles))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._roles)
+
+    def __len__(self):
+        return len(self._roles)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> Role:
+        if self.index >= len(self._roles):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._roles[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/pacttypes.py` & `PyP6Xer-1.15.0/xerparser/model/rcattypes.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,63 +1,65 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.pcattype import PCatType
-
-
-class PCatTypes:
-
-    def __init__(self):
-        self.index = 0
-        self._pcattypes = []
-
-    def add(self, params):
-        self._pcattypes.append(PCatType(params))
-
-    def find_by_id(self, id) -> PCatType:
-        obj = list(filter(lambda x: x.proj_catg_type_id == id, self._pcattypes))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    def get_tsv(self):
-        if len(self._pcattypes) > 0:
-            tsv = []
-            tsv.append(['%T', 'PCATTYPE'])
-            tsv.append(['%F', 'proj_catg_type_id', 'seq_num', 'proj_catg_short_len',
-               'proj_catg_type', 'export_flag'])
-            for acttyp in self._pcattypes:
-                tsv.append(acttyp.get_tsv())
-            return tsv
-        return []
-
-    def count(self):
-        return len(self._pcattypes)
-
-    def __len__(self):
-        return len(self._pcattypes)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> PCatType:
-        if self.index >= len(self._pcattypes):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._pcattypes[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.rcattype import RCatType
+
+class RCatTypes:
+
+
+
+    def __init__(self):
+        self.index = 0
+        self._rcattypes = []
+
+    def add(self, params):
+        self._rcattypes.append(RCatType(params))
+
+    def get_tsv(self):
+        if len(self._rcattypes) > 0:
+            tsv = []
+            tsv.append(['%T', 'RCATTYPE'])
+            tsv.append(['%F', 'rsrc_catg_type_id','seq_num', 'rsrc_catg_short_len',
+                        'rsrc_catg_type'])
+            for rcat in self._rcattypes:
+                tsv.append(rcat.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> RCatType:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rcattypes))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._rcattypes)
+
+    def __len__(self):
+        return len(self._rcattypes)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> RCatType:
+        if self.index >= len(self._rcattypes):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._rcattypes[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/pcatvals.py` & `PyP6Xer-1.15.0/xerparser/model/rsrccats.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,63 +1,62 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.pcatval import PCatVal
-
-
-class PCatVals:
-
-    def __init__(self):
-        self.index = 0
-        self._PCatVals = []
-
-    def add(self, params):
-        self._PCatVals.append(PCatVal(params))
-
-    def get_tsv(self):
-        tsv = []
-        if len(self._PCatVals) > 0:
-            tsv.append(['%T', 'PCATVAL'])
-            tsv.append(['%F', 'proj_catg_id', 'proj_catg_type_id', 'seq_num', 'proj_catg_short_name',
-               'parent_proj_catg_id', 'proj_catg_name'])
-            for pcatval in self._PCatVals:
-                tsv.append(pcatval.get_tsv())
-        return tsv
-
-    def find_by_id(self, id) -> PCatVal:
-        obj = list(filter(lambda x: x.proj_catg_id == id, self._PCatVals))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._PCatVals)
-
-    def __len__(self):
-        return len(self._PCatVals)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> PCatVal:
-        if self.index >= len(self._PCatVals):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._PCatVals[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.rsrcrcat import ResourceCat
+
+
+class ResourceCategories:
+
+    def __init__(self):
+        self.index = 0
+        self._rsrccat = []
+
+    def get_tsv(self):
+        tsv = []
+        if len(self._rsrccat) > 0:
+            tsv.append(['%T', 'RSRCRCAT'])
+            tsv.append(['%F', 'rsrc_id', 'rsrc_catg_type_id', 'rsrc_catg_id'])
+            for rc in self._rsrccat:
+                tsv.append(rc.get_tsv())
+        return tsv
+
+    def add(self, params):
+        self._rsrccat.append(ResourceCat(params))
+
+    def find_by_id(self, id) -> ResourceCat:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rsrccat))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._rsrccat)
+
+    def __len__(self):
+        return len(self._rsrccat)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> ResourceCat:
+        if self.index >= len(self._rsrccat):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._rsrccat[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/predecessors.py` & `PyP6Xer-1.15.0/xerparser/model/predecessors.py`

 * *Ordering differences only*

 * *Files 24% similar despite different names*

```diff
@@ -1,88 +1,88 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.taskpred import TaskPred
-# from xerparser.model.classes.task import Task
-from typing import List
-
-
-class Predecessors:
-
-    def __init__(self):
-        self.index=0
-        self.task_pred = []
-
-    def find_by_id(self, code_id) -> TaskPred:
-        obj = list(filter(lambda x: x.task_pred_id == code_id, self.task_pred))
-        if len(obj) > 0:
-            obj[0]
-        else:
-            obj = None
-        return obj
-    
-    def get_tsv(self):
-        tsv = []
-        if len(self.task_pred) > 0:
-            tsv.append(['%T', 'TASKPRED'])
-            tsv.append(['%F', 'task_pred_id', 'task_id', 'pred_task_id', 'proj_id', 'pred_proj_id',
-               'pred_type', 'lag_hr_cnt', 'comments', 'float_path', 'aref', 'arls'])
-            for pred in self.task_pred:
-                tsv.append(pred.get_tsv())
-        return tsv
-        
-    def add(self, params):
-        pred = TaskPred(params)
-        self.task_pred.append(pred)
-
-    @property
-    def relations(self) -> List[TaskPred]:
-        return self.task_pred
-
-    @property
-    def leads(self):
-        return list(filter(lambda x: x.lag_hr_cnt < 0 if x.lag_hr_cnt else None, self.task_pred))
-
-    @property
-    def finish_to_start(self) -> List[TaskPred]:
-        return list(filter(lambda x: x.pred_type == 'PR_FS', self.task_pred))
-    
-    def get_successors(self, act_id):
-        succ = list(filter(lambda x: x.pred_task_id == act_id, self.task_pred))
-        return succ
-
-    def get_predecessors(self, act_id):
-        succ = list(filter(lambda x: x.task_id == act_id, self.task_pred))
-        return succ
-
-    def count(self):
-        return len(self.task_pred)
-
-    def __len__(self):
-        return len(self.task_pred)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> TaskPred:
-        if self.index >= len(self.task_pred):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self.task_pred[idx]
-
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.taskpred import TaskPred
+# from xerparser.model.classes.task import Task
+from typing import List
+
+
+class Predecessors:
+
+    def __init__(self):
+        self.index=0
+        self.task_pred = []
+
+    def find_by_id(self, code_id) -> TaskPred:
+        obj = list(filter(lambda x: x.task_pred_id == code_id, self.task_pred))
+        if len(obj) > 0:
+            obj[0]
+        else:
+            obj = None
+        return obj
+    
+    def get_tsv(self):
+        tsv = []
+        if len(self.task_pred) > 0:
+            tsv.append(['%T', 'TASKPRED'])
+            tsv.append(['%F', 'task_pred_id', 'task_id', 'pred_task_id', 'proj_id', 'pred_proj_id',
+               'pred_type', 'lag_hr_cnt', 'comments', 'float_path', 'aref', 'arls'])
+            for pred in self.task_pred:
+                tsv.append(pred.get_tsv())
+        return tsv
+        
+    def add(self, params):
+        pred = TaskPred(params)
+        self.task_pred.append(pred)
+
+    @property
+    def relations(self) -> List[TaskPred]:
+        return self.task_pred
+
+    @property
+    def leads(self):
+        return list(filter(lambda x: x.lag_hr_cnt < 0 if x.lag_hr_cnt else None, self.task_pred))
+
+    @property
+    def finish_to_start(self) -> List[TaskPred]:
+        return list(filter(lambda x: x.pred_type == 'PR_FS', self.task_pred))
+    
+    def get_successors(self, act_id):
+        succ = list(filter(lambda x: x.pred_task_id == act_id, self.task_pred))
+        return succ
+
+    def get_predecessors(self, act_id):
+        succ = list(filter(lambda x: x.task_id == act_id, self.task_pred))
+        return succ
+
+    def count(self):
+        return len(self.task_pred)
+
+    def __len__(self):
+        return len(self.task_pred)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> TaskPred:
+        if self.index >= len(self.task_pred):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self.task_pred[idx]
+
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/projects.py` & `PyP6Xer-1.15.0/xerparser/model/projects.py`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,78 +1,78 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.project import Project
-from xerparser.model.classes.data import Data
-
-class Projects:
-
-
-    def __init__(self):
-        self.index =0
-        self._projects = []
-
-    def add(self, params, data):
-        prj = Project(params, data)
-        self._projects.append(prj)
-
-    def get_tsv(self):
-        if len(self._projects):
-            tsv = []
-            tsv.append(['%T', 'PROJECT'])
-            tsv.append(['%F', 'proj_id', 'fy_start_month_num', 'rsrc_self_add_flag',
-                   'allow_complete_flag', 'rsrc_multi_assign_flag', 'checkout_flag',
-                   'project_flag', 'step_complete_flag', 'cost_qty_recalc_flag',
-                   'batch_sum_flag', 'name_sep_char', 'def_complete_pct_type', 'proj_short_name',
-                   'acct_id', 'orig_proj_id', 'source_proj_id', 'base_type_id', 'clndr_id',
-                   'sum_base_proj_id', 'task_code_base', 'task_code_step', 'priority_num',
-                   'wbs_max_sum_level', 'strgy_priority_num', 'last_checksum', 'critical_drtn_hr_cnt',
-                   'def_cost_per_qty', 'last_recalc_date', 'plan_start_date', 'plan_end_date',
-                   'scd_end_date', 'add_date', 'last_tasksum_date', 'fcst_start_date', 'def_duration_type',
-                   'task_code_prefix', 'guid', 'def_qty_type', 'add_by_name', 'web_local_root_path',
-                   'proj_url', 'def_rate_type', 'add_act_remain_flag', 'act_this_per_link_flag',
-                   'def_task_type', 'act_pct_link_flag', 'critical_path_type', 'task_code_prefix_flag',
-                   'def_rollup_dates_flag', 'use_project_baseline_flag', 'rem_target_link_flag',
-                   'reset_planned_flag', 'allow_neg_act_flag', 'sum_assign_level', 'last_fin_dates_id',
-                   'last_baseline_update_date', 'cr_external_key', 'apply_actuals_date', 'fintmpl_id', 'location_id',
-                   'loaded_scope_level', 'export_flag', 'new_fin_dates_id', 'baselines_to_export',
-                   'baseline_names_to_export', 'next_data_date', 'close_period_flag', 'sum_refresh_date',
-                   'trsrcsum_loaded', 'sumtask_loaded'])
-            for prj in self._projects:
-                tsv.append(prj.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> Project:
-        obj = list(filter(lambda x: x.proj_id == id, self._projects))
-        if obj:
-            return obj[0]
-        return obj
-
-    def __repr__(self):
-        return str(self._projects)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> Project:
-        if self.index >= len(self._projects):
-            raise StopIteration
-        idx = self.index
-        self.index +=1
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.project import Project
+from xerparser.model.classes.data import Data
+
+class Projects:
+
+
+    def __init__(self):
+        self.index =0
+        self._projects = []
+
+    def add(self, params, data):
+        prj = Project(params, data)
+        self._projects.append(prj)
+
+    def get_tsv(self):
+        if len(self._projects):
+            tsv = []
+            tsv.append(['%T', 'PROJECT'])
+            tsv.append(['%F', 'proj_id', 'fy_start_month_num', 'rsrc_self_add_flag',
+                   'allow_complete_flag', 'rsrc_multi_assign_flag', 'checkout_flag',
+                   'project_flag', 'step_complete_flag', 'cost_qty_recalc_flag',
+                   'batch_sum_flag', 'name_sep_char', 'def_complete_pct_type', 'proj_short_name',
+                   'acct_id', 'orig_proj_id', 'source_proj_id', 'base_type_id', 'clndr_id',
+                   'sum_base_proj_id', 'task_code_base', 'task_code_step', 'priority_num',
+                   'wbs_max_sum_level', 'strgy_priority_num', 'last_checksum', 'critical_drtn_hr_cnt',
+                   'def_cost_per_qty', 'last_recalc_date', 'plan_start_date', 'plan_end_date',
+                   'scd_end_date', 'add_date', 'last_tasksum_date', 'fcst_start_date', 'def_duration_type',
+                   'task_code_prefix', 'guid', 'def_qty_type', 'add_by_name', 'web_local_root_path',
+                   'proj_url', 'def_rate_type', 'add_act_remain_flag', 'act_this_per_link_flag',
+                   'def_task_type', 'act_pct_link_flag', 'critical_path_type', 'task_code_prefix_flag',
+                   'def_rollup_dates_flag', 'use_project_baseline_flag', 'rem_target_link_flag',
+                   'reset_planned_flag', 'allow_neg_act_flag', 'sum_assign_level', 'last_fin_dates_id',
+                   'last_baseline_update_date', 'cr_external_key', 'apply_actuals_date', 'fintmpl_id', 'location_id',
+                   'loaded_scope_level', 'export_flag', 'new_fin_dates_id', 'baselines_to_export',
+                   'baseline_names_to_export', 'next_data_date', 'close_period_flag', 'sum_refresh_date',
+                   'trsrcsum_loaded', 'sumtask_loaded'])
+            for prj in self._projects:
+                tsv.append(prj.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> Project:
+        obj = list(filter(lambda x: x.proj_id == id, self._projects))
+        if obj:
+            return obj[0]
+        return obj
+
+    def __repr__(self):
+        return str(self._projects)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> Project:
+        if self.index >= len(self._projects):
+            raise StopIteration
+        idx = self.index
+        self.index +=1
         return self._projects[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/rcattypes.py` & `PyP6Xer-1.15.0/xerparser/model/pacttypes.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,65 +1,63 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.rcattype import RCatType
-
-class RCatTypes:
-
-
-
-    def __init__(self):
-        self.index = 0
-        self._rcattypes = []
-
-    def add(self, params):
-        self._rcattypes.append(RCatType(params))
-
-    def get_tsv(self):
-        if len(self._rcattypes) > 0:
-            tsv = []
-            tsv.append(['%T', 'RCATTYPE'])
-            tsv.append(['%F', 'rsrc_catg_type_id','seq_num', 'rsrc_catg_short_len',
-                        'rsrc_catg_type'])
-            for rcat in self._rcattypes:
-                tsv.append(rcat.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> RCatType:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rcattypes))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._rcattypes)
-
-    def __len__(self):
-        return len(self._rcattypes)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> RCatType:
-        if self.index >= len(self._rcattypes):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._rcattypes[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.pcattype import PCatType
+
+
+class PCatTypes:
+
+    def __init__(self):
+        self.index = 0
+        self._pcattypes = []
+
+    def add(self, params):
+        self._pcattypes.append(PCatType(params))
+
+    def find_by_id(self, id) -> PCatType:
+        obj = list(filter(lambda x: x.proj_catg_type_id == id, self._pcattypes))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    def get_tsv(self):
+        if len(self._pcattypes) > 0:
+            tsv = []
+            tsv.append(['%T', 'PCATTYPE'])
+            tsv.append(['%F', 'proj_catg_type_id', 'seq_num', 'proj_catg_short_len',
+               'proj_catg_type', 'export_flag'])
+            for acttyp in self._pcattypes:
+                tsv.append(acttyp.get_tsv())
+            return tsv
+        return []
+
+    def count(self):
+        return len(self._pcattypes)
+
+    def __len__(self):
+        return len(self._pcattypes)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> PCatType:
+        if self.index >= len(self._pcattypes):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._pcattypes[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/rcatvals.py` & `PyP6Xer-1.15.0/xerparser/model/rcatvals.py`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,65 +1,65 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.rcatval import RCatVal
-
-class RCatVals:
-
-
-
-    def __init__(self):
-        self.index = 0
-        self._rcatvals = []
-
-    def add(self, params):
-        self._rcatvals.append(RCatVal(params))
-    
-    def get_tsv(self):
-        if len(self._rcatvals) > 0:
-            tsv = []
-            tsv.append(['%T', 'RCATVAL'])
-            tsv.append(['%F', 'rsrc_catg_id', 'rsrc_catg_type_id', 'rsrc_catg_short_name',
-                        'rsrc_catg_name', 'parent_rsrc_catg_id'])
-            for rc in self._rcatvals:
-                tsv.append(rc.get_tsv())
-            return tsv
-        return []
-    
-    def find_by_id(self, id) -> RCatVal:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rcatvals))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._rcatvals)
-
-    def __len__(self):
-        return len(self._rcatvals)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> RCatVal:
-        if self.index >= len(self._rcatvals):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._rcatvals[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.rcatval import RCatVal
+
+class RCatVals:
+
+
+
+    def __init__(self):
+        self.index = 0
+        self._rcatvals = []
+
+    def add(self, params):
+        self._rcatvals.append(RCatVal(params))
+    
+    def get_tsv(self):
+        if len(self._rcatvals) > 0:
+            tsv = []
+            tsv.append(['%T', 'RCATVAL'])
+            tsv.append(['%F', 'rsrc_catg_id', 'rsrc_catg_type_id', 'rsrc_catg_short_name',
+                        'rsrc_catg_name', 'parent_rsrc_catg_id'])
+            for rc in self._rcatvals:
+                tsv.append(rc.get_tsv())
+            return tsv
+        return []
+    
+    def find_by_id(self, id) -> RCatVal:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rcatvals))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._rcatvals)
+
+    def __len__(self):
+        return len(self._rcatvals)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> RCatVal:
+        if self.index >= len(self._rcatvals):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._rcatvals[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/rolerates.py` & `PyP6Xer-1.15.0/xerparser/model/nonworks.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,64 +1,63 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.rolerate import RoleRate
-
-
-class RoleRates:
-
-    def __init__(self):
-        self.index = 0
-        self._rolerates = []
-
-    def get_tsv(self):
-        tsv = []
-        if len(self._rolerates) > 0:
-            tsv.append(['%T', 'ROLERATE'])
-            tsv.append(['%F', 'role_rate_id', 'role_id', 'cost_per_qty', 'cost_per_qty2',
-                   'cost_per_qty3', 'cost_per_qty4', 'cost_per_qty5'])
-            for rr in self._rolerates:
-                tsv.append(rr.get_tsv())
-        return tsv
-
-    def add(self, params):
-        self._rolerates.append(RoleRate(params))
-        self._rolerates = []
-
-    def find_by_id(self, id) -> RoleRate:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rolerates))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._rolerates)
-
-    def __len__(self):
-        return len(self._rolerates)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> RoleRate:
-        if self.index >= len(self._rolerates):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._rolerates[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.nonwork import NonWork
+
+
+class NonWorks:
+
+    def __init__(self):
+        self.index = 0
+        self._NonWorks = []
+
+    def add(self, params):
+        self._NonWorks.append(NonWork(params))
+
+    def get_tsv(self):
+        if len(self._NonWorks) > 0:
+            tsv = []
+            tsv.append(['%T', 'NONWORK'])
+            tsv.append(["%F", 'nonwork_type_id', 'seq_num', 'nonwork_code', 'nonwork_type'])
+            for nw in self._NonWorks:
+                tsv.append(nw.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> NonWork:
+        obj = list(filter(lambda x: x.fintmpl_id == id, self._NonWorks))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._NonWorks)
+
+    def __len__(self):
+        return len(self._NonWorks)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> NonWork:
+        if self.index >= len(self._NonWorks):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._NonWorks[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/roles.py` & `PyP6Xer-1.15.0/xerparser/model/wbss.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,65 +1,60 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.role import Role
-
-
-class Roles:
-
-    def __init__(self):
-        self.index = 0
-        self._roles = []
-
-    def get_tsv(self):
-        if len(self._roles) > 0:
-            tsv = []
-            tsv.append(['%T', 'ROLE'])
-            tsv.append(['%F', 'role_id', 'parent_role_id', 'seq_num', 'role_name',
-                   'role_short_name', 'pobs_id', 'def_cost_qty_link_flag', 'cost_qty_type',
-                   'role_descr', 'last_checksum'])
-            for role in self._roles:
-                tsv.append(role.get_tsv())
-            return tsv
-        return []
-
-    def add(self, params):
-        self._roles.append(Role(params))
-
-    def find_by_id(self, id) -> Role:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._roles))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._roles)
-
-    def __len__(self):
-        return len(self._roles)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> Role:
-        if self.index >= len(self._roles):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._roles[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.wbs import WBS
+from typing import List
+
+
+class WBSs:
+
+    def __init__(self, data=None):
+        self.index = 0
+        self._wbss = []
+        self.data = data
+
+    def add(self, params, data):
+        wbs = WBS(params, data)
+        self._wbss.append(wbs)
+    
+    def get_tsv(self):
+        tsv = []
+        if len(self._wbss) > 0:
+            tsv.append(['%T', 'PROJWBS'])
+            tsv.append(['%F', 'wbs_id', 'proj_id', 'obs_id', 'seq_num', 'est_wt',
+               'proj_node_flag', 'sum_data_flag', 'status_code', 'wbs_short_name',
+               'wbs_name', 'phase_id', 'parent_wbs_id', 'ev_user_pct', 'ev_etc_user_value',
+               'orig_cost', 'indep_remain_total_cost', 'ann_dscnt_rate_pct', 'dscnt_period_type',
+               'indep_remain_work_qty', 'anticip_start_date', 'anticip_end_date', 'ev_compute_type',
+               'ev_etc_compute_type', 'guid', 'tmpl_guid', 'plan_open_state'])
+            for wb in self._wbss:
+                tsv.append(wb.get_tsv())
+        return tsv
+    
+    def get_by_project(self, id) -> List[WBS]:
+        return list(filter(lambda x: x.proj_id == id, self._wbss))
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> WBS:
+        if self.index >= len(self._wbss):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._wbss[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/rsrccurves.py` & `PyP6Xer-1.15.0/xerparser/model/rsrccurves.py`

 * *Ordering differences only*

 * *Files 24% similar despite different names*

```diff
@@ -1,68 +1,68 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.rsrccurv import ResourceCurve
-
-class ResourceCurves:
-
-
-
-    def __init__(self):
-        self.index = 0
-        self._resourcecurves = []
-
-    def add(self, params):
-        self._resourcecurves.append(ResourceCurve(params))
-
-    def find_by_id(self, id) -> ResourceCurve:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._resourcecurves))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-    
-    def get_tsv(self):
-        tsv = []
-        if len(self._resourcecurves) > 0:
-            tsv.append(['%T', 'RSRCCURVDATA'])
-            tsv.append(['%F', 'curv_id', 'curv_name', 'default_flag', 'pct_usage_0',
-               'pct_usage_1', 'pct_usage_2', 'pct_usage_3', 'pct_usage_4',
-               'pct_usage_5', 'pct_usage_6', 'pct_usage_7', 'pct_usage_8',
-               'pct_usage_9', 'pct_usage_10', 'pct_usage_11', 'pct_usage_12',
-               'pct_usage_13', 'pct_usage_14', 'pct_usage_15', 'pct_usage_16',
-               'pct_usage_17', 'pct_usage_18', 'pct_usage_19', 'pct_usage_20'])
-            for rcurv in self._resourcecurves:
-                tsv.append(rcurv.get_tsv())
-        return tsv
-
-    @property
-    def count(self):
-        return len(self._resourcecurves)
-
-    def __len__(self):
-        return len(self._resourcecurves)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> ResourceCurve:
-        if self.index >= len(self._resourcecurves):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.rsrccurv import ResourceCurve
+
+class ResourceCurves:
+
+
+
+    def __init__(self):
+        self.index = 0
+        self._resourcecurves = []
+
+    def add(self, params):
+        self._resourcecurves.append(ResourceCurve(params))
+
+    def find_by_id(self, id) -> ResourceCurve:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._resourcecurves))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+    
+    def get_tsv(self):
+        tsv = []
+        if len(self._resourcecurves) > 0:
+            tsv.append(['%T', 'RSRCCURVDATA'])
+            tsv.append(['%F', 'curv_id', 'curv_name', 'default_flag', 'pct_usage_0',
+               'pct_usage_1', 'pct_usage_2', 'pct_usage_3', 'pct_usage_4',
+               'pct_usage_5', 'pct_usage_6', 'pct_usage_7', 'pct_usage_8',
+               'pct_usage_9', 'pct_usage_10', 'pct_usage_11', 'pct_usage_12',
+               'pct_usage_13', 'pct_usage_14', 'pct_usage_15', 'pct_usage_16',
+               'pct_usage_17', 'pct_usage_18', 'pct_usage_19', 'pct_usage_20'])
+            for rcurv in self._resourcecurves:
+                tsv.append(rcurv.get_tsv())
+        return tsv
+
+    @property
+    def count(self):
+        return len(self._resourcecurves)
+
+    def __len__(self):
+        return len(self._resourcecurves)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> ResourceCurve:
+        if self.index >= len(self._resourcecurves):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
         return self._resourcecurves[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/rsrcrates.py` & `PyP6Xer-1.15.0/xerparser/model/rsrcrates.py`

 * *Ordering differences only*

 * *Files 18% similar despite different names*

```diff
@@ -1,63 +1,63 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.rsrcrate import ResourceRate
-
-class ResourceRates:
-
-    def __init__(self):
-        self.index = 0
-        self._rsrcrates = []
-
-    def add(self, params):
-        self._rsrcrates.append(ResourceRate(params))
-
-    def find_by_id(self, id) -> ResourceRate:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rsrcrates))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    def get_tsv(self):
-        tsv = []
-        if len(self._rsrcrates) > 0:
-            tsv.append(['%T', 'RSRCRATE'])
-            tsv.append(['%F', 'rsrc_rate_id', 'rsrc_id', 'max_qty_per_hr', 'cost_per_qty',
-              'start_date', 'shift_period_id', 'cost_per_qty2', 'cost_per_qty3',
-              'cost_per_qty4', 'cost_per_qty5'])
-            for rr in self._rsrcrates:
-                tsv.append(rr.get_tsv())
-        return tsv
-
-    @property
-    def count(self):
-        return len(self._rsrcrates)
-
-    def __len__(self):
-        return len(self._rsrcrates)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> ResourceRate:
-        if self.index >= len(self._rsrcrates):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._rsrcrates[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.rsrcrate import ResourceRate
+
+class ResourceRates:
+
+    def __init__(self):
+        self.index = 0
+        self._rsrcrates = []
+
+    def add(self, params):
+        self._rsrcrates.append(ResourceRate(params))
+
+    def find_by_id(self, id) -> ResourceRate:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._rsrcrates))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    def get_tsv(self):
+        tsv = []
+        if len(self._rsrcrates) > 0:
+            tsv.append(['%T', 'RSRCRATE'])
+            tsv.append(['%F', 'rsrc_rate_id', 'rsrc_id', 'max_qty_per_hr', 'cost_per_qty',
+              'start_date', 'shift_period_id', 'cost_per_qty2', 'cost_per_qty3',
+              'cost_per_qty4', 'cost_per_qty5'])
+            for rr in self._rsrcrates:
+                tsv.append(rr.get_tsv())
+        return tsv
+
+    @property
+    def count(self):
+        return len(self._rsrcrates)
+
+    def __len__(self):
+        return len(self._rsrcrates)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> ResourceRate:
+        if self.index >= len(self._rsrcrates):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._rsrcrates[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/schedoptions.py` & `PyP6Xer-1.15.0/xerparser/model/schedoptions.py`

 * *Ordering differences only*

 * *Files 25% similar despite different names*

```diff
@@ -1,70 +1,70 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.schedoption import SchedOption
-
-
-class SchedOptions:
-
-    def __init__(self):
-        self.index = 0
-        self._schoptions = []
-
-    def add(self, params):
-        self._schoptions.append(SchedOption(params))
-
-    def find_by_id(self, id) -> SchedOption:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._schoptions))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-    
-    def get_tsv(self):
-        tsv = []
-        if len(self._schoptions) > 0:
-            tsv.append(['%T', 'SCHEDOPTIONS'])
-            tsv.append(['%F', 'schedoptions_id', 'proj_id', 'sched_outer_depend_type', 'sched_open_critical_flag',
-               'sched_lag_early_start_flag', 'sched_retained_logic', 'sched_setplantoforecast',
-               'sched_float_type', 'sched_calendar_on_relationship_lag', 'sched_use_expect_end_flag',
-               'sched_progress_override', 'level_float_thrs_cnt', 'level_outer_assign_flag',
-               'level_outer_assign_priority', 'level_over_alloc_pct', 'level_within_float_flag',
-               'level_keep_sched_date_flag', 'level_all_rsrc_flag', 'sched_use_project_end_date_for_float',
-               'enable_multiple_longest_path_calc', 'limit_multiple_longest_path_calc',
-               'max_multiple_longest_path', 'use_total_float_multiple_longest_paths',
-               'key_activity_for_multiple_longest_paths', 'LevelPriorityList'])
-            for sco in self._schoptions:
-                tsv.append(sco.get_tsv())
-        return tsv
-
-    @property
-    def count(self):
-        return len(self._schoptions)
-
-    def __len__(self):
-        return len(self._schoptions)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> SchedOption:
-        if self.index >= len(self._schoptions):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._schoptions[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.schedoption import SchedOption
+
+
+class SchedOptions:
+
+    def __init__(self):
+        self.index = 0
+        self._schoptions = []
+
+    def add(self, params):
+        self._schoptions.append(SchedOption(params))
+
+    def find_by_id(self, id) -> SchedOption:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._schoptions))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+    
+    def get_tsv(self):
+        tsv = []
+        if len(self._schoptions) > 0:
+            tsv.append(['%T', 'SCHEDOPTIONS'])
+            tsv.append(['%F', 'schedoptions_id', 'proj_id', 'sched_outer_depend_type', 'sched_open_critical_flag',
+               'sched_lag_early_start_flag', 'sched_retained_logic', 'sched_setplantoforecast',
+               'sched_float_type', 'sched_calendar_on_relationship_lag', 'sched_use_expect_end_flag',
+               'sched_progress_override', 'level_float_thrs_cnt', 'level_outer_assign_flag',
+               'level_outer_assign_priority', 'level_over_alloc_pct', 'level_within_float_flag',
+               'level_keep_sched_date_flag', 'level_all_rsrc_flag', 'sched_use_project_end_date_for_float',
+               'enable_multiple_longest_path_calc', 'limit_multiple_longest_path_calc',
+               'max_multiple_longest_path', 'use_total_float_multiple_longest_paths',
+               'key_activity_for_multiple_longest_paths', 'LevelPriorityList'])
+            for sco in self._schoptions:
+                tsv.append(sco.get_tsv())
+        return tsv
+
+    @property
+    def count(self):
+        return len(self._schoptions)
+
+    def __len__(self):
+        return len(self._schoptions)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> SchedOption:
+        if self.index >= len(self._schoptions):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._schoptions[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/taskactvs.py` & `PyP6Xer-1.15.0/xerparser/model/taskactvs.py`

 * *Ordering differences only*

 * *Files 17% similar despite different names*

```diff
@@ -1,67 +1,67 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.taskactv import TaskActv
-
-
-class TaskActvs:
-
-    def __init__(self):
-        self.index = 0
-        self._taskactvs = []
-
-    def add(self, params, data):
-        self._taskactvs.append(TaskActv(params, data))
-    
-    def get_tsv(self):
-        tsv = []
-        if len(self._taskactvs) > 0:
-            tsv.append(['%T', 'TASKACTV'])
-            tsv.append(['%F', 'task_id', 'actv_code_type_id', 'actv_code_id', 'proj_id'])
-            for taskact in self._taskactvs:
-                tsv.append(taskact.get_tsv())
-        return tsv
-    
-    def find_by_code_id(self, id) -> TaskActv:
-        obj = list(filter(lambda x: x.actv_code_id == id, self._taskactvs))
-        if len(obj) > 0:
-            return obj
-        return obj
-
-    def find_by_activity_id(self, id) -> TaskActv:
-        obj = list(filter(lambda x: x.task_id == id, self._taskactvs))
-        if len(obj) > 0:
-            return obj
-        return obj
-
-    def count(self):
-        return len(self._taskactvs)
-
-    def __len__(self):
-        return len(self._taskactvs)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> TaskActv:
-        if self.index >= len(self._taskactvs):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.taskactv import TaskActv
+
+
+class TaskActvs:
+
+    def __init__(self):
+        self.index = 0
+        self._taskactvs = []
+
+    def add(self, params, data):
+        self._taskactvs.append(TaskActv(params, data))
+    
+    def get_tsv(self):
+        tsv = []
+        if len(self._taskactvs) > 0:
+            tsv.append(['%T', 'TASKACTV'])
+            tsv.append(['%F', 'task_id', 'actv_code_type_id', 'actv_code_id', 'proj_id'])
+            for taskact in self._taskactvs:
+                tsv.append(taskact.get_tsv())
+        return tsv
+    
+    def find_by_code_id(self, id) -> TaskActv:
+        obj = list(filter(lambda x: x.actv_code_id == id, self._taskactvs))
+        if len(obj) > 0:
+            return obj
+        return obj
+
+    def find_by_activity_id(self, id) -> TaskActv:
+        obj = list(filter(lambda x: x.task_id == id, self._taskactvs))
+        if len(obj) > 0:
+            return obj
+        return obj
+
+    def count(self):
+        return len(self._taskactvs)
+
+    def __len__(self):
+        return len(self._taskactvs)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> TaskActv:
+        if self.index >= len(self._taskactvs):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
         return self._taskactvs[idx]
```

### Comparing `PyP6Xer-1.14.3/xerparser/model/udfvalues.py` & `PyP6Xer-1.15.0/xerparser/model/udfvalues.py`

 * *Ordering differences only*

 * *Files 11% similar despite different names*

```diff
@@ -1,64 +1,64 @@
-# PyP6XER
-# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
-#
-# This file is part of PyP6XER.
-#
-# PyP6XER library is free software: you can redistribute it and/or modify
-# it under the terms of the GNU Lesser General Public License v2.1 as published by
-# the Free Software Foundation, either version 3 of the License, or
-# (at your option) any later version.
-#
-# PyP6XER is distributed in the hope that it will be useful,
-# but WITHOUT ANY WARRANTY; without even the implied warranty of
-# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-# GNU General Public License for more details.
-#
-# You should have received a copy of the GNU General Public License
-# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
-
-
-from xerparser.model.classes.udfvalue import UDFValue
-
-
-class UDFValues:
-
-    def __init__(self):
-        self.index = 0
-        self._udfvalues = []
-
-    def add(self, params):
-        self._udfvalues.append(UDFValue(params))
-
-    def get_tsv(self):
-        if len(self._udfvalues) > 0:
-            tsv = []
-            tsv.append(['%T', 'UDFVALUE'])
-            tsv.append(["%F", 'udf_type_id', 'fk_id', 'proj_id', 'udf_date', 'udf_number', 'udf_text',
-               'udf_code_id'])
-            for udfval in self._udfvalues:
-                tsv.append(udfval.get_tsv())
-            return tsv
-        return []
-
-    def find_by_id(self, id) -> UDFValue:
-        obj = list(filter(lambda x: x.actv_code_type_id == id, self._udfvalues))
-        if len(obj) > 0:
-            return obj[0]
-        return obj
-
-    @property
-    def count(self):
-        return len(self._udfvalues)
-
-    def __len__(self):
-        return len(self._udfvalues)
-
-    def __iter__(self):
-        return self
-
-    def __next__(self) -> UDFValue:
-        if self.index >= len(self._udfvalues):
-            raise StopIteration
-        idx = self.index
-        self.index += 1
-        return self._udfvalues[idx]
+# PyP6XER
+# Copyright (C) 2020, 2021 Hassan Emam <hassan@constology.com>
+#
+# This file is part of PyP6XER.
+#
+# PyP6XER library is free software: you can redistribute it and/or modify
+# it under the terms of the GNU Lesser General Public License v2.1 as published by
+# the Free Software Foundation, either version 3 of the License, or
+# (at your option) any later version.
+#
+# PyP6XER is distributed in the hope that it will be useful,
+# but WITHOUT ANY WARRANTY; without even the implied warranty of
+# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+# GNU General Public License for more details.
+#
+# You should have received a copy of the GNU General Public License
+# along with PyP6XER.  If not, see <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html>.
+
+
+from xerparser.model.classes.udfvalue import UDFValue
+
+
+class UDFValues:
+
+    def __init__(self):
+        self.index = 0
+        self._udfvalues = []
+
+    def add(self, params):
+        self._udfvalues.append(UDFValue(params))
+
+    def get_tsv(self):
+        if len(self._udfvalues) > 0:
+            tsv = []
+            tsv.append(['%T', 'UDFVALUE'])
+            tsv.append(["%F", 'udf_type_id', 'fk_id', 'proj_id', 'udf_date', 'udf_number', 'udf_text',
+               'udf_code_id'])
+            for udfval in self._udfvalues:
+                tsv.append(udfval.get_tsv())
+            return tsv
+        return []
+
+    def find_by_id(self, id) -> UDFValue:
+        obj = list(filter(lambda x: x.actv_code_type_id == id, self._udfvalues))
+        if len(obj) > 0:
+            return obj[0]
+        return obj
+
+    @property
+    def count(self):
+        return len(self._udfvalues)
+
+    def __len__(self):
+        return len(self._udfvalues)
+
+    def __iter__(self):
+        return self
+
+    def __next__(self) -> UDFValue:
+        if self.index >= len(self._udfvalues):
+            raise StopIteration
+        idx = self.index
+        self.index += 1
+        return self._udfvalues[idx]
```


# Comparing `tmp/embykeeper-2.2.5.tar.gz` & `tmp/embykeeper-2.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "embykeeper-2.2.5.tar", last modified: Mon Jun 26 23:47:53 2023, max compression
+gzip compressed data, was "embykeeper-2.2.6.tar", last modified: Wed Jun 28 08:03:19 2023, max compression
```

## Comparing `embykeeper-2.2.5.tar` & `embykeeper-2.2.6.tar`

### file list

```diff
@@ -1,92 +1,91 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.205008 embykeeper-2.2.5/
--rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-26 23:47:40.000000 embykeeper-2.2.5/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-26 23:47:40.000000 embykeeper-2.2.5/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    23799 2023-06-26 23:47:53.205008 embykeeper-2.2.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22901 2023-06-26 23:47:40.000000 embykeeper-2.2.5/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.189008 embykeeper-2.2.5/embykeeper/
--rw-r--r--   0 runner    (1001) docker     (123)      130 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7185 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     3782 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/data.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.193008 embykeeper-2.2.5/embykeeper/embywatcher/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/embywatcher/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3380 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/embywatcher/emby.py
--rw-r--r--   0 runner    (1001) docker     (123)     8061 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/embywatcher/main.py
--rw-r--r--   0 runner    (1001) docker     (123)     1690 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/log.py
--rw-r--r--   0 runner    (1001) docker     (123)    15322 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/settings.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.193008 embykeeper-2.2.5/embykeeper/telechecker/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.197008 embykeeper-2.2.5/embykeeper/telechecker/bots/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17239 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/base.py
--rw-r--r--   0 runner    (1001) docker     (123)      280 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/bluesea.py
--rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/charon.py
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/embyhub.py
--rw-r--r--   0 runner    (1001) docker     (123)     1716 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/jms.py
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/jms_iptv.py
--rw-r--r--   0 runner    (1001) docker     (123)      917 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/ljyy.py
--rw-r--r--   0 runner    (1001) docker     (123)     3492 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/nebula.py
--rw-r--r--   0 runner    (1001) docker     (123)      689 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/peach.py
--rw-r--r--   0 runner    (1001) docker     (123)      878 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/pornemby.py
--rw-r--r--   0 runner    (1001) docker     (123)      707 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/singularity.py
--rw-r--r--   0 runner    (1001) docker     (123)      136 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/sssq.py
--rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/bots/terminus.py
--rw-r--r--   0 runner    (1001) docker     (123)     5400 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/link.py
--rw-r--r--   0 runner    (1001) docker     (123)     1471 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/log.py
--rw-r--r--   0 runner    (1001) docker     (123)    14975 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/main.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.197008 embykeeper-2.2.5/embykeeper/telechecker/messager/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/messager/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3655 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/messager/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     3134 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/messager/common.py
--rw-r--r--   0 runner    (1001) docker     (123)      210 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/messager/nakonako.py
--rw-r--r--   0 runner    (1001) docker     (123)      302 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/messager/test.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.197008 embykeeper-2.2.5/embykeeper/telechecker/monitor/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10708 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/base.py
--rw-r--r--   0 runner    (1001) docker     (123)      650 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/bgk.py
--rw-r--r--   0 runner    (1001) docker     (123)      536 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/embyhub.py
--rw-r--r--   0 runner    (1001) docker     (123)     4144 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/misty.py
--rw-r--r--   0 runner    (1001) docker     (123)      711 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/polo.py
--rw-r--r--   0 runner    (1001) docker     (123)     6484 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/pornemby.py
--rw-r--r--   0 runner    (1001) docker     (123)     1965 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/test.py
--rw-r--r--   0 runner    (1001) docker     (123)      581 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/monitor/viper.py
--rw-r--r--   0 runner    (1001) docker     (123)    17587 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/telechecker/tele.py
--rw-r--r--   0 runner    (1001) docker     (123)     6261 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeper/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.193008 embykeeper-2.2.5/embykeeper.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    23799 2023-06-26 23:47:53.000000 embykeeper-2.2.5/embykeeper.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2524 2023-06-26 23:47:53.000000 embykeeper-2.2.5/embykeeper.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 23:47:53.000000 embykeeper-2.2.5/embykeeper.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-26 23:47:53.000000 embykeeper-2.2.5/embykeeper.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 23:47:52.000000 embykeeper-2.2.5/embykeeper.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      253 2023-06-26 23:47:53.000000 embykeeper-2.2.5/embykeeper.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-26 23:47:53.000000 embykeeper-2.2.5/embykeeper.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5642 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/app.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/templates/
--rw-r--r--   0 runner    (1001) docker     (123)     6460 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/404.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.189008 embykeeper-2.2.5/embykeeperweb/templates/assets/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.189008 embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/css/
--rw-r--r--   0 runner    (1001) docker     (123)   202097 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/css/bootstrap.min.css
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/js/
--rw-r--r--   0 runner    (1001) docker     (123)    80372 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/js/bootstrap.min.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/templates/assets/css/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/css/cascadia-code.css
--rw-r--r--   0 runner    (1001) docker     (123)      966 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/css/icons.css
--rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/css/styles.css
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.189008 embykeeper-2.2.5/embykeeperweb/templates/assets/img/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/
--rw-r--r--   0 runner    (1001) docker     (123)     4747 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/404.svg
--rw-r--r--   0 runner    (1001) docker     (123)     8264 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/login.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1956 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/logo-only.svg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/embykeeperweb/templates/assets/js/
--rw-r--r--   0 runner    (1001) docker     (123)     4239 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/js/console.js
--rw-r--r--   0 runner    (1001) docker     (123)      711 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/assets/js/script.js
--rw-r--r--   0 runner    (1001) docker     (123)     8276 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/console.html
--rw-r--r--   0 runner    (1001) docker     (123)     7376 2023-06-26 23:47:40.000000 embykeeper-2.2.5/embykeeperweb/templates/login.html
--rw-r--r--   0 runner    (1001) docker     (123)     1713 2023-06-26 23:47:40.000000 embykeeper-2.2.5/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 23:47:53.205008 embykeeper-2.2.5/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 23:47:53.201008 embykeeper-2.2.5/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     2009 2023-06-26 23:47:40.000000 embykeeper-2.2.5/tests/test_cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.138308 embykeeper-2.2.6/
+-rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-28 08:03:09.000000 embykeeper-2.2.6/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-28 08:03:09.000000 embykeeper-2.2.6/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    23850 2023-06-28 08:03:19.138308 embykeeper-2.2.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    22901 2023-06-28 08:03:09.000000 embykeeper-2.2.6/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.122308 embykeeper-2.2.6/embykeeper/
+-rw-r--r--   0 runner    (1001) docker     (123)      130 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7185 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3838 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/data.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.126308 embykeeper-2.2.6/embykeeper/embywatcher/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/embywatcher/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3380 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/embywatcher/emby.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8061 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/embywatcher/main.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1690 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/log.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15300 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/settings.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.126308 embykeeper-2.2.6/embykeeper/telechecker/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.130308 embykeeper-2.2.6/embykeeper/telechecker/bots/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17239 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)      280 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/bluesea.py
+-rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/charon.py
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/embyhub.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1716 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/jms.py
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/jms_iptv.py
+-rw-r--r--   0 runner    (1001) docker     (123)      917 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/ljyy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3492 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/nebula.py
+-rw-r--r--   0 runner    (1001) docker     (123)      689 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/peach.py
+-rw-r--r--   0 runner    (1001) docker     (123)      878 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/pornemby.py
+-rw-r--r--   0 runner    (1001) docker     (123)      707 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/singularity.py
+-rw-r--r--   0 runner    (1001) docker     (123)      136 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/sssq.py
+-rw-r--r--   0 runner    (1001) docker     (123)      288 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/bots/terminus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5618 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/link.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1471 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/log.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14975 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/main.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.130308 embykeeper-2.2.6/embykeeper/telechecker/messager/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/messager/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3655 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/messager/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3134 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/messager/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)      210 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/messager/nakonako.py
+-rw-r--r--   0 runner    (1001) docker     (123)      302 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/messager/test.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeper/telechecker/monitor/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10708 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)      650 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/bgk.py
+-rw-r--r--   0 runner    (1001) docker     (123)      536 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/embyhub.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4144 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/misty.py
+-rw-r--r--   0 runner    (1001) docker     (123)      711 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/polo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6484 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/pornemby.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1965 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      581 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/monitor/viper.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17587 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/telechecker/tele.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6261 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeper/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.126308 embykeeper-2.2.6/embykeeper.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23850 2023-06-28 08:03:19.000000 embykeeper-2.2.6/embykeeper.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2471 2023-06-28 08:03:19.000000 embykeeper-2.2.6/embykeeper.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:03:19.000000 embykeeper-2.2.6/embykeeper.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-28 08:03:19.000000 embykeeper-2.2.6/embykeeper.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:03:18.000000 embykeeper-2.2.6/embykeeper.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      253 2023-06-28 08:03:19.000000 embykeeper-2.2.6/embykeeper.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 08:03:19.000000 embykeeper-2.2.6/embykeeper.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5642 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/app.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)     6460 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/404.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.122308 embykeeper-2.2.6/embykeeperweb/templates/assets/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.118308 embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/css/
+-rw-r--r--   0 runner    (1001) docker     (123)   202097 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/css/bootstrap.min.css
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/js/
+-rw-r--r--   0 runner    (1001) docker     (123)    80372 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/js/bootstrap.min.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/templates/assets/css/
+-rw-r--r--   0 runner    (1001) docker     (123)      966 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/css/icons.css
+-rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/css/styles.css
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.118308 embykeeper-2.2.6/embykeeperweb/templates/assets/img/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/
+-rw-r--r--   0 runner    (1001) docker     (123)     4747 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/404.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     8264 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/login.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1956 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/logo-only.svg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/embykeeperweb/templates/assets/js/
+-rw-r--r--   0 runner    (1001) docker     (123)     4239 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/js/console.js
+-rw-r--r--   0 runner    (1001) docker     (123)      711 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/assets/js/script.js
+-rw-r--r--   0 runner    (1001) docker     (123)     8276 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/console.html
+-rw-r--r--   0 runner    (1001) docker     (123)     7376 2023-06-28 08:03:09.000000 embykeeper-2.2.6/embykeeperweb/templates/login.html
+-rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 08:03:09.000000 embykeeper-2.2.6/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 08:03:19.138308 embykeeper-2.2.6/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:03:19.134308 embykeeper-2.2.6/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     2009 2023-06-28 08:03:09.000000 embykeeper-2.2.6/tests/test_cli.py
```

### Comparing `embykeeper-2.2.5/LICENSE` & `embykeeper-2.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/PKG-INFO` & `embykeeper-2.2.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,24 +1,25 @@
 Metadata-Version: 2.1
 Name: embykeeper
-Version: 2.2.5
+Version: 2.2.6
 Summary: Daily checkin automator for emby bots in telegram.
 Author-email: jackzzs <jackzzs@outlook.com>
 Project-URL: Homepage, https://github.com/embykeeper/embykeeper
 Keywords: emby,telegram,checkin,automator,bot,telegram bot,keep active
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: End Users/Desktop
 Classifier: Natural Language :: Chinese (Simplified)
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
 Requires-Python: <3.11,>=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 [![build status](https://img.shields.io/github/actions/workflow/status/embykeeper/embykeeper/ci.yml?branch=main)](https://github.com/embykeeper/embykeeper/commits/main) [![pypi badge](https://img.shields.io/pypi/v/embykeeper)](https://pypi.org/project/embykeeper/) [![downloads badge](https://img.shields.io/pypi/dm/embykeeper?color=%234287f5&label=downloads&logoColor=%234287f5)](https://pypi.org/project/embykeeper/) [![docker](https://img.shields.io/docker/v/embykeeper/embykeeper?label=docker)](https://hub.docker.com/r/embykeeper/embykeeper) [![license badge](https://img.shields.io/github/license/embykeeper/embykeeper)](https://github.com/embykeeper/embykeeper/blob/main/LICENSE) [![telegram badge](https://img.shields.io/badge/telegram-bot-blue)](https://t.me/embykeeper_bot) [![telegram badge](https://img.shields.io/badge/telegram-channel-green)](https://t.me/embykeeper)
 
 <p align="center">
```

#### html2text {}

```diff
@@ -1,24 +1,24 @@
-Metadata-Version: 2.1 Name: embykeeper Version: 2.2.5 Summary: Daily checkin
+Metadata-Version: 2.1 Name: embykeeper Version: 2.2.6 Summary: Daily checkin
 automator for emby bots in telegram. Author-email: jackzzs
 outlook.com> Project-URL: Homepage, https://github.com/embykeeper/embykeeper
 Keywords: emby,telegram,checkin,automator,bot,telegram bot,keep active
 Classifier: Development Status :: 5 - Production/Stable Classifier: Environment
 :: Console Classifier: Environment :: Web Environment Classifier: Intended
 Audience :: End Users/Desktop Classifier: Natural Language :: Chinese
 (Simplified) Classifier: License :: OSI Approved :: GNU General Public License
 v3 (GPLv3) Classifier: Programming Language :: Python :: 3 Classifier:
-Programming Language :: Python :: 3.6 Classifier: Programming Language ::
-Python :: 3.7 Classifier: Programming Language :: Python :: 3.8 Requires-
-Python: <3.11,>=3.8 Description-Content-Type: text/markdown License-File:
-LICENSE [![build status](https://img.shields.io/github/actions/workflow/status/
-embykeeper/embykeeper/ci.yml?branch=main)](https://github.com/embykeeper/
-embykeeper/commits/main) [![pypi badge](https://img.shields.io/pypi/v/
-embykeeper)](https://pypi.org/project/embykeeper/) [![downloads badge](https://
-img.shields.io/pypi/dm/
+Programming Language :: Python :: 3.7 Classifier: Programming Language ::
+Python :: 3.8 Classifier: Programming Language :: Python :: 3.9 Classifier:
+Programming Language :: Python :: 3.10 Requires-Python: <3.11,>=3.8
+Description-Content-Type: text/markdown License-File: LICENSE [![build status]
+(https://img.shields.io/github/actions/workflow/status/embykeeper/embykeeper/
+ci.yml?branch=main)](https://github.com/embykeeper/embykeeper/commits/main) [!
+[pypi badge](https://img.shields.io/pypi/v/embykeeper)](https://pypi.org/
+project/embykeeper/) [![downloads badge](https://img.shields.io/pypi/dm/
 embykeeper?color=%234287f5&label=downloads&logoColor=%234287f5)](https://
 pypi.org/project/embykeeper/) [![docker](https://img.shields.io/docker/v/
 embykeeper/embykeeper?label=docker)](https://hub.docker.com/r/embykeeper/
 embykeeper) [![license badge](https://img.shields.io/github/license/embykeeper/
 embykeeper)](https://github.com/embykeeper/embykeeper/blob/main/LICENSE) [!
 [telegram badge](https://img.shields.io/badge/telegram-bot-blue)](https://t.me/
 embykeeper_bot) [![telegram badge](https://img.shields.io/badge/telegram-
```

### Comparing `embykeeper-2.2.5/README.md` & `embykeeper-2.2.6/README.md`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/cli.py` & `embykeeper-2.2.6/embykeeper/cli.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/data.py` & `embykeeper-2.2.6/embykeeper/data.py`

 * *Files 1% similar despite different names*

```diff
@@ -67,18 +67,19 @@
                                 yield None
                                 break
                     except aiohttp.ClientConnectorError as e:
                         (basedir / name).unlink(missing_ok=True)
                         logger.warning(f"下载失败: {name}, 将在 3 秒后重试.")
                         await asyncio.sleep(3)
                         continue
-                    except:
+                    except Exception as e:
                         (basedir / name).unlink(missing_ok=True)
-                        logger.warning(f"下载失败: {name}")
-                        raise
+                        logger.warning(f"下载失败: {name} ({e})")
+                        yield None
+                        break
             else:
                 logger.warning(f"下载失败: {name}.")
                 yield None
                 continue
 
 
 async def get_data(basedir: Path, name: str, proxy: dict = None, caller: str = None):
```

### Comparing `embykeeper-2.2.5/embykeeper/embywatcher/emby.py` & `embykeeper-2.2.6/embykeeper/embywatcher/emby.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/embywatcher/main.py` & `embykeeper-2.2.6/embykeeper/embywatcher/main.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/log.py` & `embykeeper-2.2.6/embykeeper/log.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/settings.py` & `embykeeper-2.2.6/embykeeper/settings.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 import os
 from pathlib import Path
+import re
 import sys
 import base64
 import hashlib
 
 from loguru import logger
 import tomli as tomllib
 from schema import And, Optional, Or, Regex, Schema, SchemaError
@@ -280,44 +281,44 @@
     enc = Confirm.ask(pad + "是否生成加密配置", default=False)
     if enc:
         enc_password = Prompt.ask(pad + "请输入加密密码, 程序启动时将要求输入 (不显示, 按回车确认)", password=True)
         content = encrypt(content, enc_password)
     else:
         content = content.encode()
     content = base64.b64encode(content)
-    logger.info(f"您的配置[green]已生成完毕[/]! 您需要将以下内容写入 SECRETS 变量配置 (名称: EK_CONFIG), 否则配置将在重启后丢失.")
+    logger.info(f"您的配置[green]已生成完毕[/]! 您需要将以下内容写入环境变量配置 (名称: EK_CONFIG), 否则配置将在重启后丢失.")
     print()
     get_console().rule("EK_CONFIG")
     print(content.decode())
     get_console().rule()
     print()
     start_now = Confirm.ask(pad + "是否立即启动?", default=True)
     if start_now:
         return config
 
 
 def load_env_config(data: str):
     from rich.prompt import Prompt
 
-    data = base64.b64decode(data.strip().encode())
+    data = base64.b64decode(re.sub(r"\s+", "", data).encode())
     try:
         config = tomllib.loads(data.decode())
     except (tomllib.TOMLDecodeError, UnicodeDecodeError):
         try:
             logger.info("您正在使用加密配置文件作为输入 (AES).")
             config = tomllib.loads(
                 decrypt(data, Prompt.ask(" " * 23 + "您需要输入您的加密密钥 (不显示, 按回车确认)", password=True))
             )
         except (tomllib.TOMLDecodeError, UnicodeDecodeError):
             config = {}
         if not config:
-            logger.error("密钥无效或配置格式错误, 请删除 SECRETS 变量设置, 并重新配置.")
+            logger.error("密钥无效或配置格式错误, 请重试.")
             sys.exit(252)
     else:
-        logger.debug("您正在使用 SECRETS 变量配置.")
+        logger.debug("您正在使用环境变量配置.")
     return config
 
 
 def prepare_config(config_file=None, public=False):
     env_config = os.environ.get(f"EK_CONFIG", None)
     if env_config:
         config = load_env_config(env_config)
```

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/base.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/base.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/charon.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/charon.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/jms.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/jms.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/ljyy.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/ljyy.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/nebula.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/nebula.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/peach.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/peach.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/pornemby.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/pornemby.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/bots/singularity.py` & `embykeeper-2.2.6/embykeeper/telechecker/bots/singularity.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/link.py` & `embykeeper-2.2.6/embykeeper/telechecker/link.py`

 * *Files 6% similar despite different names*

```diff
@@ -38,15 +38,15 @@
                 pass
 
         return await asyncio.gather(*[delete(m) for m in messages])
 
     async def post(
         self, cmd, condition: Callable = None, timeout: int = 5, retries=3, name: str = None
     ) -> Tuple[Optional[str], Optional[str]]:
-        for _ in range(retries):
+        for r in range(retries):
             self.log.debug(f"[gray50]禁用提醒 {timeout} 秒: {self.bot}[/]")
             await self.client.mute_chat(self.bot, time.time() + timeout + 5)
             future = asyncio.Future()
             handler = MessageHandler(
                 async_partial(self._handler, cmd=cmd, future=future, condition=condition),
                 filters.text & filters.bot & filters.user(self.bot),
             )
@@ -62,31 +62,34 @@
                     await asyncio.wait_for(self.delete_messages(messages), 1.0)
                 except asyncio.TimeoutError:
                     pass
                 finally:
                     raise
             except asyncio.TimeoutError:
                 await self.delete_messages(messages)
-                self.log.warning(f"{name}超时.")
-                continue
+                if r + 1 < retries:
+                    self.log.info(f"{name}超时 ({r + 1}/{retries}), 将在 3 秒后重试.")
+                    await asyncio.sleep(3)
+                    continue
+                else:
+                    self.log.warning(f"{name}超时 ({r + 1}/{retries}).")
+                    return None
             else:
                 await self.delete_messages(messages)
                 status, errmsg = [results.get(p, None) for p in ("status", "errmsg")]
                 if status == "error":
                     self.log.warning(f"{name}错误: {errmsg}.")
                     return False
                 elif status == "ok":
                     return results
                 else:
                     self.log.warning(f"{name}出现未知错误.")
                     return False
             finally:
                 self.client.remove_handler(handler, group=1)
-        else:
-            return None
 
     async def _handler(
         self,
         client: Client,
         message: Message,
         cmd: str,
         future: asyncio.Future,
```

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/log.py` & `embykeeper-2.2.6/embykeeper/telechecker/log.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/main.py` & `embykeeper-2.2.6/embykeeper/telechecker/main.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/messager/base.py` & `embykeeper-2.2.6/embykeeper/telechecker/messager/base.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/messager/common.py` & `embykeeper-2.2.6/embykeeper/telechecker/messager/common.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/base.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/base.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/bgk.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/bgk.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/embyhub.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/embyhub.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/misty.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/misty.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/polo.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/polo.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/pornemby.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/pornemby.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/test.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/test.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/monitor/viper.py` & `embykeeper-2.2.6/embykeeper/telechecker/monitor/viper.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/telechecker/tele.py` & `embykeeper-2.2.6/embykeeper/telechecker/tele.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper/utils.py` & `embykeeper-2.2.6/embykeeper/utils.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeper.egg-info/PKG-INFO` & `embykeeper-2.2.6/embykeeper.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,24 +1,25 @@
 Metadata-Version: 2.1
 Name: embykeeper
-Version: 2.2.5
+Version: 2.2.6
 Summary: Daily checkin automator for emby bots in telegram.
 Author-email: jackzzs <jackzzs@outlook.com>
 Project-URL: Homepage, https://github.com/embykeeper/embykeeper
 Keywords: emby,telegram,checkin,automator,bot,telegram bot,keep active
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: End Users/Desktop
 Classifier: Natural Language :: Chinese (Simplified)
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
 Requires-Python: <3.11,>=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 [![build status](https://img.shields.io/github/actions/workflow/status/embykeeper/embykeeper/ci.yml?branch=main)](https://github.com/embykeeper/embykeeper/commits/main) [![pypi badge](https://img.shields.io/pypi/v/embykeeper)](https://pypi.org/project/embykeeper/) [![downloads badge](https://img.shields.io/pypi/dm/embykeeper?color=%234287f5&label=downloads&logoColor=%234287f5)](https://pypi.org/project/embykeeper/) [![docker](https://img.shields.io/docker/v/embykeeper/embykeeper?label=docker)](https://hub.docker.com/r/embykeeper/embykeeper) [![license badge](https://img.shields.io/github/license/embykeeper/embykeeper)](https://github.com/embykeeper/embykeeper/blob/main/LICENSE) [![telegram badge](https://img.shields.io/badge/telegram-bot-blue)](https://t.me/embykeeper_bot) [![telegram badge](https://img.shields.io/badge/telegram-channel-green)](https://t.me/embykeeper)
 
 <p align="center">
```

#### html2text {}

```diff
@@ -1,24 +1,24 @@
-Metadata-Version: 2.1 Name: embykeeper Version: 2.2.5 Summary: Daily checkin
+Metadata-Version: 2.1 Name: embykeeper Version: 2.2.6 Summary: Daily checkin
 automator for emby bots in telegram. Author-email: jackzzs
 outlook.com> Project-URL: Homepage, https://github.com/embykeeper/embykeeper
 Keywords: emby,telegram,checkin,automator,bot,telegram bot,keep active
 Classifier: Development Status :: 5 - Production/Stable Classifier: Environment
 :: Console Classifier: Environment :: Web Environment Classifier: Intended
 Audience :: End Users/Desktop Classifier: Natural Language :: Chinese
 (Simplified) Classifier: License :: OSI Approved :: GNU General Public License
 v3 (GPLv3) Classifier: Programming Language :: Python :: 3 Classifier:
-Programming Language :: Python :: 3.6 Classifier: Programming Language ::
-Python :: 3.7 Classifier: Programming Language :: Python :: 3.8 Requires-
-Python: <3.11,>=3.8 Description-Content-Type: text/markdown License-File:
-LICENSE [![build status](https://img.shields.io/github/actions/workflow/status/
-embykeeper/embykeeper/ci.yml?branch=main)](https://github.com/embykeeper/
-embykeeper/commits/main) [![pypi badge](https://img.shields.io/pypi/v/
-embykeeper)](https://pypi.org/project/embykeeper/) [![downloads badge](https://
-img.shields.io/pypi/dm/
+Programming Language :: Python :: 3.7 Classifier: Programming Language ::
+Python :: 3.8 Classifier: Programming Language :: Python :: 3.9 Classifier:
+Programming Language :: Python :: 3.10 Requires-Python: <3.11,>=3.8
+Description-Content-Type: text/markdown License-File: LICENSE [![build status]
+(https://img.shields.io/github/actions/workflow/status/embykeeper/embykeeper/
+ci.yml?branch=main)](https://github.com/embykeeper/embykeeper/commits/main) [!
+[pypi badge](https://img.shields.io/pypi/v/embykeeper)](https://pypi.org/
+project/embykeeper/) [![downloads badge](https://img.shields.io/pypi/dm/
 embykeeper?color=%234287f5&label=downloads&logoColor=%234287f5)](https://
 pypi.org/project/embykeeper/) [![docker](https://img.shields.io/docker/v/
 embykeeper/embykeeper?label=docker)](https://hub.docker.com/r/embykeeper/
 embykeeper) [![license badge](https://img.shields.io/github/license/embykeeper/
 embykeeper)](https://github.com/embykeeper/embykeeper/blob/main/LICENSE) [!
 [telegram badge](https://img.shields.io/badge/telegram-bot-blue)](https://t.me/
 embykeeper_bot) [![telegram badge](https://img.shields.io/badge/telegram-
```

### Comparing `embykeeper-2.2.5/embykeeper.egg-info/SOURCES.txt` & `embykeeper-2.2.6/embykeeper.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -56,15 +56,14 @@
 embykeeperweb/__main__.py
 embykeeperweb/app.py
 embykeeperweb/templates/404.html
 embykeeperweb/templates/console.html
 embykeeperweb/templates/login.html
 embykeeperweb/templates/assets/bootstrap/css/bootstrap.min.css
 embykeeperweb/templates/assets/bootstrap/js/bootstrap.min.js
-embykeeperweb/templates/assets/css/cascadia-code.css
 embykeeperweb/templates/assets/css/icons.css
 embykeeperweb/templates/assets/css/styles.css
 embykeeperweb/templates/assets/img/illustrations/404.svg
 embykeeperweb/templates/assets/img/illustrations/login.svg
 embykeeperweb/templates/assets/img/illustrations/logo-only.svg
 embykeeperweb/templates/assets/js/console.js
 embykeeperweb/templates/assets/js/script.js
```

### Comparing `embykeeper-2.2.5/embykeeperweb/app.py` & `embykeeper-2.2.6/embykeeperweb/app.py`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/404.html` & `embykeeper-2.2.6/embykeeperweb/templates/404.html`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/css/bootstrap.min.css` & `embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/css/bootstrap.min.css`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/bootstrap/js/bootstrap.min.js` & `embykeeper-2.2.6/embykeeperweb/templates/assets/bootstrap/js/bootstrap.min.js`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/css/icons.css` & `embykeeper-2.2.6/embykeeperweb/templates/assets/css/icons.css`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/css/styles.css` & `embykeeper-2.2.6/embykeeperweb/templates/assets/css/styles.css`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/404.svg` & `embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/404.svg`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/login.svg` & `embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/login.svg`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/img/illustrations/logo-only.svg` & `embykeeper-2.2.6/embykeeperweb/templates/assets/img/illustrations/logo-only.svg`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/js/console.js` & `embykeeper-2.2.6/embykeeperweb/templates/assets/js/console.js`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/assets/js/script.js` & `embykeeper-2.2.6/embykeeperweb/templates/assets/js/script.js`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/console.html` & `embykeeper-2.2.6/embykeeperweb/templates/console.html`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/embykeeperweb/templates/login.html` & `embykeeper-2.2.6/embykeeperweb/templates/login.html`

 * *Files identical despite different names*

### Comparing `embykeeper-2.2.5/pyproject.toml` & `embykeeper-2.2.6/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "embykeeper"
-version = "2.2.5"
+version = "2.2.6"
 authors = [
     {name = "jackzzs", email = "jackzzs@outlook.com"},
 ]
 description = "Daily checkin automator for emby bots in telegram."
 keywords = [
     "emby",
     "telegram",
@@ -22,17 +22,18 @@
     "Development Status :: 5 - Production/Stable",
     "Environment :: Console",
     "Environment :: Web Environment",
     "Intended Audience :: End Users/Desktop",
     "Natural Language :: Chinese (Simplified)",
     "License :: OSI Approved :: GNU General Public License v3 (GPLv3)",
     "Programming Language :: Python :: 3",
-    "Programming Language :: Python :: 3.6",
     "Programming Language :: Python :: 3.7",
     "Programming Language :: Python :: 3.8",
+    "Programming Language :: Python :: 3.9",
+    "Programming Language :: Python :: 3.10",
 ]
 requires-python = ">=3.8,<3.11"
 dependencies = [
     "tomli",
     "tomlkit",
     "rich",
     "typer",
```

### Comparing `embykeeper-2.2.5/tests/test_cli.py` & `embykeeper-2.2.6/tests/test_cli.py`

 * *Files identical despite different names*


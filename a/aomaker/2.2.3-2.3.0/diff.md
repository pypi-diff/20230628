# Comparing `tmp/aomaker-2.2.3.tar.gz` & `tmp/aomaker-2.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "aomaker-2.2.3.tar", last modified: Mon May 22 08:33:31 2023, max compression
+gzip compressed data, was "aomaker-2.3.0.tar", last modified: Wed Jun 28 09:22:13 2023, max compression
```

## Comparing `aomaker-2.2.3.tar` & `aomaker-2.3.0.tar`

### file list

```diff
@@ -1,69 +1,69 @@
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.350748 aomaker-2.2.3/
--rw-r-----   0 zhanglinsen   (501) staff       (20)    11509 2022-11-30 11:05:02.000000 aomaker-2.2.3/LICENSE
--rw-r--r--   0 zhanglinsen   (501) staff       (20)       43 2023-05-20 11:36:28.000000 aomaker-2.2.3/MANIFEST.in
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1038 2023-05-22 08:33:31.350611 aomaker-2.2.3/PKG-INFO
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      607 2022-11-03 10:41:01.000000 aomaker-2.2.3/README.md
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.346271 aomaker-2.2.3/aomaker/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1426 2023-05-22 08:33:28.000000 aomaker-2.2.3/aomaker/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     9285 2023-04-12 10:30:39.000000 aomaker-2.2.3/aomaker/_aomaker.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      794 2023-04-10 14:08:17.000000 aomaker-2.2.3/aomaker/_constants.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     2356 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/_log.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1245 2023-05-20 14:38:18.000000 aomaker-2.2.3/aomaker/_printer.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      237 2023-04-10 15:38:20.000000 aomaker-2.2.3/aomaker/aomaker.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.347385 aomaker-2.2.3/aomaker/base/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/base/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     4395 2023-04-10 14:57:25.000000 aomaker-2.2.3/aomaker/base/base_api.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     3296 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/base/base_testcase.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     6167 2023-04-10 07:53:59.000000 aomaker-2.2.3/aomaker/cache.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     9697 2023-03-23 05:48:22.000000 aomaker-2.2.3/aomaker/cli.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.348086 aomaker-2.2.3/aomaker/database/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/database/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1654 2023-03-24 06:30:20.000000 aomaker-2.2.3/aomaker/database/base_db.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1059 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/database/mysql.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     2734 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/database/sqlite.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1394 2022-12-05 05:36:42.000000 aomaker-2.2.3/aomaker/exceptions.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.348195 aomaker-2.2.3/aomaker/extension/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)        0 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/extension/__init__.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.348467 aomaker-2.2.3/aomaker/extension/har_parse/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     2284 2023-03-22 14:18:38.000000 aomaker-2.2.3/aomaker/extension/har_parse/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)    10792 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/extension/har_parse/har_parse.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.348914 aomaker-2.2.3/aomaker/extension/recording/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     4517 2023-03-21 15:15:18.000000 aomaker-2.2.3/aomaker/extension/recording/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      170 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/extension/recording/addons.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     5679 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/extension/recording/recording.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1276 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/field.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     2813 2023-05-20 14:38:18.000000 aomaker-2.2.3/aomaker/fixture.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      965 2023-03-22 10:18:59.000000 aomaker-2.2.3/aomaker/hook_manager.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.349487 aomaker-2.2.3/aomaker/html/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     9937 2022-12-22 09:57:22.000000 aomaker-2.2.3/aomaker/html/heading.html
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     4302 2022-12-22 09:57:22.000000 aomaker-2.2.3/aomaker/html/report.html
--rw-r--r--   0 zhanglinsen   (501) staff       (20)    11555 2023-05-20 11:43:25.000000 aomaker-2.2.3/aomaker/html/template.html
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     3816 2023-03-22 11:04:05.000000 aomaker-2.2.3/aomaker/log.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1476 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/make.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     7940 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/make_api.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1216 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/make_testcase.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     2118 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/models.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      450 2023-03-16 15:19:31.000000 aomaker-2.2.3/aomaker/param_types.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      691 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/path.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     2890 2023-05-20 14:38:18.000000 aomaker-2.2.3/aomaker/report.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     8531 2023-05-22 07:24:31.000000 aomaker-2.2.3/aomaker/runner.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     8576 2023-04-10 14:08:17.000000 aomaker-2.2.3/aomaker/scaffold.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.349832 aomaker-2.2.3/aomaker/send_msg/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/send_msg/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     8329 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/send_msg/wechat.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     7672 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/swagger2yaml.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     9148 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/template.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.350260 aomaker-2.2.3/aomaker/utils/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/utils/__init__.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     9529 2023-05-22 08:33:10.000000 aomaker-2.2.3/aomaker/utils/gen_allure_report.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     5120 2023-02-02 04:06:40.000000 aomaker-2.2.3/aomaker/utils/utils.py
--rw-r--r--   0 zhanglinsen   (501) staff       (20)    16987 2022-11-03 10:41:01.000000 aomaker-2.2.3/aomaker/yaml2case.py
-drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-05-22 08:33:31.346924 aomaker-2.2.3/aomaker.egg-info/
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1038 2023-05-22 08:33:31.000000 aomaker-2.2.3/aomaker.egg-info/PKG-INFO
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1349 2023-05-22 08:33:31.000000 aomaker-2.2.3/aomaker.egg-info/SOURCES.txt
--rw-r--r--   0 zhanglinsen   (501) staff       (20)        1 2023-05-22 08:33:31.000000 aomaker-2.2.3/aomaker.egg-info/dependency_links.txt
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      154 2023-05-22 08:33:31.000000 aomaker-2.2.3/aomaker.egg-info/entry_points.txt
--rw-r--r--   0 zhanglinsen   (501) staff       (20)      173 2023-05-22 08:33:31.000000 aomaker-2.2.3/aomaker.egg-info/requires.txt
--rw-r--r--   0 zhanglinsen   (501) staff       (20)        8 2023-05-22 08:33:31.000000 aomaker-2.2.3/aomaker.egg-info/top_level.txt
--rw-r--r--   0 zhanglinsen   (501) staff       (20)       38 2023-05-22 08:33:31.350800 aomaker-2.2.3/setup.cfg
--rw-r--r--   0 zhanglinsen   (501) staff       (20)     1282 2023-05-22 08:33:28.000000 aomaker-2.2.3/setup.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.737813 aomaker-2.3.0/
+-rw-r-----   0 zhanglinsen   (501) staff       (20)    11509 2022-11-30 11:05:02.000000 aomaker-2.3.0/LICENSE
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)       43 2023-05-20 11:36:28.000000 aomaker-2.3.0/MANIFEST.in
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1038 2023-06-28 09:22:13.737670 aomaker-2.3.0/PKG-INFO
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      607 2022-11-03 10:41:01.000000 aomaker-2.3.0/README.md
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.732611 aomaker-2.3.0/aomaker/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1426 2023-06-27 14:54:19.000000 aomaker-2.3.0/aomaker/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     9285 2023-04-12 10:30:39.000000 aomaker-2.3.0/aomaker/_aomaker.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      794 2023-04-10 14:08:17.000000 aomaker-2.3.0/aomaker/_constants.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     2356 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/_log.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1245 2023-05-20 14:38:18.000000 aomaker-2.3.0/aomaker/_printer.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      237 2023-04-10 15:38:20.000000 aomaker-2.3.0/aomaker/aomaker.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.733749 aomaker-2.3.0/aomaker/base/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/base/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     4395 2023-04-10 14:57:25.000000 aomaker-2.3.0/aomaker/base/base_api.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     3296 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/base/base_testcase.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     6139 2023-05-29 14:52:36.000000 aomaker-2.3.0/aomaker/cache.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)    11276 2023-06-28 09:19:16.000000 aomaker-2.3.0/aomaker/cli.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.734479 aomaker-2.3.0/aomaker/database/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/database/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1654 2023-03-24 06:30:20.000000 aomaker-2.3.0/aomaker/database/base_db.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1059 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/database/mysql.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     2734 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/database/sqlite.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1685 2023-05-29 14:39:13.000000 aomaker-2.3.0/aomaker/exceptions.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.734605 aomaker-2.3.0/aomaker/extension/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)        0 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/extension/__init__.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.734890 aomaker-2.3.0/aomaker/extension/har_parse/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     2284 2023-03-22 14:18:38.000000 aomaker-2.3.0/aomaker/extension/har_parse/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)    10792 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/extension/har_parse/har_parse.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.735456 aomaker-2.3.0/aomaker/extension/recording/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     4517 2023-03-21 15:15:18.000000 aomaker-2.3.0/aomaker/extension/recording/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      170 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/extension/recording/addons.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     5679 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/extension/recording/recording.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1276 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/field.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     2813 2023-05-20 14:38:18.000000 aomaker-2.3.0/aomaker/fixture.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      965 2023-03-22 10:18:59.000000 aomaker-2.3.0/aomaker/hook_manager.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.736116 aomaker-2.3.0/aomaker/html/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     9937 2022-12-22 09:57:22.000000 aomaker-2.3.0/aomaker/html/heading.html
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     4302 2022-12-22 09:57:22.000000 aomaker-2.3.0/aomaker/html/report.html
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)    11555 2023-05-20 11:43:25.000000 aomaker-2.3.0/aomaker/html/template.html
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     3816 2023-03-22 11:04:05.000000 aomaker-2.3.0/aomaker/log.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1476 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/make.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     7940 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/make_api.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1216 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/make_testcase.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     2288 2023-06-28 07:54:12.000000 aomaker-2.3.0/aomaker/models.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      503 2023-06-13 10:28:50.000000 aomaker-2.3.0/aomaker/param_types.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      750 2023-06-19 04:14:35.000000 aomaker-2.3.0/aomaker/path.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     2890 2023-05-20 14:38:18.000000 aomaker-2.3.0/aomaker/report.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     8513 2023-06-28 06:57:49.000000 aomaker-2.3.0/aomaker/runner.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     8639 2023-06-28 08:23:43.000000 aomaker-2.3.0/aomaker/scaffold.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.736670 aomaker-2.3.0/aomaker/send_msg/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/send_msg/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     8329 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/send_msg/wechat.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     7672 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/swagger2yaml.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     9148 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/template.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.737299 aomaker-2.3.0/aomaker/utils/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)       19 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/utils/__init__.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     9529 2023-05-22 08:33:10.000000 aomaker-2.3.0/aomaker/utils/gen_allure_report.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     5120 2023-02-02 04:06:40.000000 aomaker-2.3.0/aomaker/utils/utils.py
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)    16987 2022-11-03 10:41:01.000000 aomaker-2.3.0/aomaker/yaml2case.py
+drwxr-xr-x   0 zhanglinsen   (501) staff       (20)        0 2023-06-28 09:22:13.733247 aomaker-2.3.0/aomaker.egg-info/
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1038 2023-06-28 09:22:13.000000 aomaker-2.3.0/aomaker.egg-info/PKG-INFO
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1349 2023-06-28 09:22:13.000000 aomaker-2.3.0/aomaker.egg-info/SOURCES.txt
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)        1 2023-06-28 09:22:13.000000 aomaker-2.3.0/aomaker.egg-info/dependency_links.txt
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      154 2023-06-28 09:22:13.000000 aomaker-2.3.0/aomaker.egg-info/entry_points.txt
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)      173 2023-06-28 09:22:13.000000 aomaker-2.3.0/aomaker.egg-info/requires.txt
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)        8 2023-06-28 09:22:13.000000 aomaker-2.3.0/aomaker.egg-info/top_level.txt
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)       38 2023-06-28 09:22:13.737855 aomaker-2.3.0/setup.cfg
+-rw-r--r--   0 zhanglinsen   (501) staff       (20)     1282 2023-06-27 14:54:19.000000 aomaker-2.3.0/setup.py
```

### Comparing `aomaker-2.2.3/LICENSE` & `aomaker-2.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/PKG-INFO` & `aomaker-2.3.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: aomaker
-Version: 2.2.3
+Version: 2.3.0
 Summary: An api testing framework
 Home-page: https://github.com/ae86sen/aomaker
 Author: ancientone
 Author-email: listeningsss@163.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
```

### Comparing `aomaker-2.2.3/README.md` & `aomaker-2.3.0/README.md`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/__init__.py` & `aomaker-2.3.0/aomaker/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from emoji import emojize
 
-__version__ = "2.2.3"
+__version__ = "2.3.0"
 __description__ = "Quickly Arrange,Quickly Test!"
 __image__ = emojize(fr"""
               :----.                                                             ::::
              .------            .:::::::::::::::::::::::::::::::::::::::::::::. :---:  ::::::::::::::::::::::::::
             .---::--:                                                           ----
             ----  :--:          ..::::.      :.:..::::  .::::     ..:::. .:::  :---: ...:.    .::::.     .:.:..::
            :---    :::        .---------:   :-----------------   :----------:  ----.:---:   :---::---:   -------:
```

### Comparing `aomaker-2.2.3/aomaker/_aomaker.py` & `aomaker-2.3.0/aomaker/_aomaker.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/_constants.py` & `aomaker-2.3.0/aomaker/_constants.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/_log.py` & `aomaker-2.3.0/aomaker/_log.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/_printer.py` & `aomaker-2.3.0/aomaker/_printer.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/base/base_api.py` & `aomaker-2.3.0/aomaker/base/base_api.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/base/base_testcase.py` & `aomaker-2.3.0/aomaker/base/base_testcase.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/cache.py` & `aomaker-2.3.0/aomaker/cache.py`

 * *Files 3% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 
 from jsonpath import jsonpath
 from multiprocessing import current_process
 from threading import current_thread
 
 from aomaker.database.sqlite import SQLiteDB
 from aomaker._constants import DataBase
+from aomaker.exceptions import JsonPathExtractFailed
 from aomaker.log import logger
 
 
 class Config(SQLiteDB):
     def __init__(self):
         super(Config, self).__init__()
         self.table = DataBase.CONFIG_TABLE
@@ -149,19 +150,18 @@
             return None
         res = json.loads(res)
 
         return res
 
     def get_by_jsonpath(self, key: str, jsonpath_expr, expr_index: int = 0):
         res = self.get(key)
-        try:
-            extract_var = jsonpath(res, jsonpath_expr)[expr_index]
-        except TypeError as te:
-            logger.error(f'依赖数据提取失败，\n 数据源：{res}\n 提取表达式：{jsonpath_expr}\n 索引：{expr_index}')
-            raise te
+        extract_var = jsonpath(res, jsonpath_expr)
+        if extract_var is False:
+            raise JsonPathExtractFailed(res,jsonpath_expr)
+        extract_var = extract_var[expr_index]
         return extract_var
 
     def clear(self):
         sql = """delete from {}""".format(self.table)
         self.execute_sql(sql)
 
     def del_(self, where: dict = None):
```

### Comparing `aomaker-2.2.3/aomaker/cli.py` & `aomaker-2.3.0/aomaker/cli.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,30 +1,34 @@
 # --coding:utf-8--
 import os
 import sys
+from typing import List, Text
+
 import click
 import inspect
 from importlib import import_module
 
 import yaml
 from emoji import emojize
 from click_help_colors import HelpColorsGroup, version_option
 
 from aomaker import __version__, __image__
 from aomaker._constants import Conf
 from aomaker.log import logger, AoMakerLogger
-from aomaker.path import CONF_DIR
+from aomaker.path import CONF_DIR, AOMAKER_YAML_PATH
 from aomaker.hook_manager import _cli_hook
 from aomaker.param_types import QUOTED_STR
 from aomaker.path import BASEDIR
 from aomaker.scaffold import create_scaffold
 from aomaker.make import main_make
 from aomaker.make_testcase import main_case, main_make_case
 from aomaker.extension.har_parse import main_har2yaml
 from aomaker.extension.recording import filter_expression, main_record
+from aomaker.utils.utils import load_yaml
+from aomaker.models import AomakerYaml
 
 SUBCOMMAND_RUN_NAME = "run"
 HOOK_MODULE_NAME = "hooks"
 plugin_path = os.path.join(BASEDIR, f'{HOOK_MODULE_NAME}.py')
 
 
 class OptionHandler:
@@ -91,21 +95,24 @@
         set_conf_file(env)
     if log_level != "info":
         click.echo(emojize(f":rocket:<AoMaker>切换日志等级：{log_level}"))
         AoMakerLogger.change_level(log_level)
     login_obj = _handle_login(no_login)
     from aomaker.runner import run as runner_run, processes_run, threads_run
     if mp:
+        click.echo("🚀<AoMaker> 多进程模式准备启动...")
         processes_run(_handle_dist_mode(d_mark, d_file, d_suite), login=login_obj, extra_args=pytest_args,
                       is_gen_allure=no_gen)
         ctx.exit()
     elif mt:
+        click.echo("🚀<AoMaker> 多线程模式准备启动...")
         threads_run(_handle_dist_mode(d_mark, d_file, d_suite), login=login_obj, extra_args=pytest_args,
                     is_gen_allure=no_gen)
         ctx.exit()
+    click.echo("🚀<AoMaker> 单进程模式准备启动...")
     runner_run(pytest_args, login=login_obj, is_gen_allure=no_gen)
     ctx.exit()
 
 
 @main.command()
 @click.argument("project_name")
 def startproject(project_name):
@@ -241,21 +248,59 @@
         click.echo(emojize(f':confounded_face: 配置文件{conf_path}不存在'))
         sys.exit(1)
 
 
 def _handle_dist_mode(d_mark, d_file, d_suite):
     if d_mark:
         params = [f"-m {mark}" for mark in d_mark]
-    elif d_file:
+        mode_msg = "dist-mark"
+        click.echo(f"🚀<AoMaker> 分配模式: {mode_msg}")
+        return params
+
+    if d_file:
         params = {"path": d_file}
-    else:
+        mode_msg = "dist-file"
+        click.echo(f"🚀<AoMaker> 分配模式: {mode_msg}")
+        return params
+
+    if d_suite:
         params = d_suite
+        mode_msg = "dist-suite"
+        click.echo(f"🚀<AoMaker> 分配模式: {mode_msg}")
+        return params
+
+    params = _handle_aomaker_yaml()
+    mode_msg = "dist-mark(aomaker.yaml策略)"
+    click.echo(f"🚀<AoMaker> 分配模式: {mode_msg}")
     return params
 
 
+def _handle_aomaker_yaml() -> List[Text]:
+    # 1.文件是否存在
+    if not os.path.exists(AOMAKER_YAML_PATH):
+        click.echo(emojize(f':confounded_face: aomaker策略文件{AOMAKER_YAML_PATH}不存在！'))
+        sys.exit(1)
+        # raise FileNotFound(AOMAKER_YAML_PATH)
+    yaml_data = load_yaml(AOMAKER_YAML_PATH)
+    # 2.格式校验
+    content = AomakerYaml(**yaml_data)
+    # 3.取值
+    targets = content.target
+    marks = content.marks
+    d_mark = []
+    for target in targets:
+        if "." in target:
+            target, strategy = target.split(".", 1)
+            marks_li = marks[target][strategy]
+        else:
+            marks_li = marks[target]
+        d_mark.extend([f"-m {mark}" for mark in marks_li])
+    return d_mark
+
+
 def main_arun_alias():
     """ command alias
         arun = aomaker run
     """
     sys.argv.insert(1, "run")
     # if len(sys.argv) != 2:
     #     sys.argv.insert(1, "run")
```

### Comparing `aomaker-2.2.3/aomaker/database/base_db.py` & `aomaker-2.3.0/aomaker/database/base_db.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/database/mysql.py` & `aomaker-2.3.0/aomaker/database/mysql.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/database/sqlite.py` & `aomaker-2.3.0/aomaker/database/sqlite.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/exceptions.py` & `aomaker-2.3.0/aomaker/exceptions.py`

 * *Files 4% similar despite different names*

```diff
@@ -47,7 +47,16 @@
 
 class HttpRequestError(AoMakerException):
     def __init__(self, status_code):
         self.status_code = status_code
 
     def __str__(self):
         return f'请求失败，状态码：{self.status_code}'
+
+
+class JsonPathExtractFailed(AoMakerException):
+    def __init__(self, res, jsonpath_expr):
+        self.res = res
+        self.jsonpath_expr = jsonpath_expr
+
+    def __str__(self):
+        return f'依赖数据提取失败\n 提取表达式：{self.jsonpath_expr}\n 数据源：{self.res}'
```

### Comparing `aomaker-2.2.3/aomaker/extension/har_parse/__init__.py` & `aomaker-2.3.0/aomaker/extension/har_parse/__init__.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/extension/har_parse/har_parse.py` & `aomaker-2.3.0/aomaker/extension/har_parse/har_parse.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/extension/recording/__init__.py` & `aomaker-2.3.0/aomaker/extension/recording/__init__.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/extension/recording/recording.py` & `aomaker-2.3.0/aomaker/extension/recording/recording.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/field.py` & `aomaker-2.3.0/aomaker/field.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/fixture.py` & `aomaker-2.3.0/aomaker/fixture.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/hook_manager.py` & `aomaker-2.3.0/aomaker/hook_manager.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/html/heading.html` & `aomaker-2.3.0/aomaker/html/heading.html`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/html/report.html` & `aomaker-2.3.0/aomaker/html/report.html`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/html/template.html` & `aomaker-2.3.0/aomaker/html/template.html`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/log.py` & `aomaker-2.3.0/aomaker/log.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/make.py` & `aomaker-2.3.0/aomaker/make.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/make_api.py` & `aomaker-2.3.0/aomaker/make_api.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/make_testcase.py` & `aomaker-2.3.0/aomaker/make_testcase.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/models.py` & `aomaker-2.3.0/aomaker/models.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 from enum import Enum
-from typing import List, Text, Dict, Any, Mapping
+from typing import List, Text, Dict, Any, Mapping, Union
 from pydantic import BaseModel, Field, conlist, validator
+from pydantic.types import constr
 
 AssertField = conlist(Any, min_items=2, max_items=3)
 
 
 # JSON = List[Text, int, Any]
 
 
@@ -86,7 +87,12 @@
 
 class YamlTestcase(BaseModel):
     testcase_class_name: Text
     testcase_name: Text
     description: Text = ''
     config: Dict = {}
     steps: List[Steps]
+
+
+class AomakerYaml(BaseModel):
+    target: List
+    marks: Dict[constr(min_length=1), Union[Dict[Text, List[Text]], List[Text]]]
```

### Comparing `aomaker-2.2.3/aomaker/path.py` & `aomaker-2.3.0/aomaker/path.py`

 * *Files 9% similar despite different names*

```diff
@@ -16,7 +16,9 @@
 CASE_DIR = os.path.join(BASEDIR, "testcases")
 # DB目录
 DB_DIR = os.path.join(BASEDIR, "database")
 # pytest.ini文件路径
 PYTEST_INI_DIR = os.path.join(BASEDIR, "pytest.ini")
 # aomaker html路径
 AOMAKER_HTML = os.path.join(REPORT_DIR, "aomaker.html")
+
+AOMAKER_YAML_PATH = os.path.join(BASEDIR, "aomaker.yaml")
```

### Comparing `aomaker-2.2.3/aomaker/report.py` & `aomaker-2.3.0/aomaker/report.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/runner.py` & `aomaker-2.3.0/aomaker/runner.py`

 * *Files 1% similar despite different names*

```diff
@@ -223,15 +223,15 @@
             self.gen_allure()
             gen_reports()
 
 
 def main_task(args: list):
     """pytest启动"""
     pytest_opts = _get_pytest_ini()
-    logger.info(f"<AoMaker> pytest的执行参数：{list(set(pytest_opts))}")
+    logger.info(f"<AoMaker> pytest的执行参数：{args}")
     if pytest_opts:
         logger.info(f"<AoMaker> pytest.ini配置参数：{pytest_opts}")
     pytest.main(args)
 
 
 def make_args_group(args: list, extra_args: list):
     """构造pytest参数列表
```

### Comparing `aomaker-2.2.3/aomaker/scaffold.py` & `aomaker-2.3.0/aomaker/scaffold.py`

 * *Files 5% similar despite different names*

```diff
@@ -169,15 +169,15 @@
             testcases/test_api目录下有多少个测试文件，就启动多少个子线程来运行
     3.dist-suite: 根据测试套件来分配线程，每个套件下的case由独立的线程运行
         example：
             threads_run("testcases/test_api")
             testcases/test_api目录下有多少个测试套件，就启动多少个子线程来运行
             
 ================================多进程启动================================
-****注意：windows下暂时不支持，linux支持****
+****注意：windows下暂时不支持，linux和mac支持****
 启动函数：processes_run()           
 参数：
     根据传入参数类型不同，启动不同的多线程分配模式
     list: dist-mark模式
     str：dist-file模式
     dict：dist-suite模式
 多线程分配模式：
@@ -210,15 +210,16 @@
 
     def make_headers(self, resp_login:dict) -> dict:
         headers = {
             'Cookie': f'csrftoken=aomakerniubility'}
         return headers
     """
     create_file(os.path.join(project_name, "login.py"), login_content)
-    create_file(os.path.join(project_name, "hook_manager.py"), "")
+    create_file(os.path.join(project_name, "hooks.py"), "")
+    create_file(os.path.join(project_name, "aomaker.yaml"), "")
     data_path = os.path.join(project_name, "data")
     create_folder(data_path)
     create_folder(os.path.join(data_path, "api_data"))
     create_folder(os.path.join(data_path, "scenario_data"))
     create_folder(os.path.join(project_name, "reports"))
     create_folder(os.path.join(project_name, "logs"))
     db_dir_path = os.path.join(project_name, "database")
```

### Comparing `aomaker-2.2.3/aomaker/send_msg/wechat.py` & `aomaker-2.3.0/aomaker/send_msg/wechat.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/swagger2yaml.py` & `aomaker-2.3.0/aomaker/swagger2yaml.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/template.py` & `aomaker-2.3.0/aomaker/template.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/utils/gen_allure_report.py` & `aomaker-2.3.0/aomaker/utils/gen_allure_report.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/utils/utils.py` & `aomaker-2.3.0/aomaker/utils/utils.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker/yaml2case.py` & `aomaker-2.3.0/aomaker/yaml2case.py`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/aomaker.egg-info/PKG-INFO` & `aomaker-2.3.0/aomaker.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: aomaker
-Version: 2.2.3
+Version: 2.3.0
 Summary: An api testing framework
 Home-page: https://github.com/ae86sen/aomaker
 Author: ancientone
 Author-email: listeningsss@163.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
```

### Comparing `aomaker-2.2.3/aomaker.egg-info/SOURCES.txt` & `aomaker-2.3.0/aomaker.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `aomaker-2.2.3/setup.py` & `aomaker-2.3.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # --coding:utf-8--
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 setuptools.setup(
     name="aomaker",
-    version="2.2.3",
+    version="2.3.0",
     author="ancientone",
     author_email="listeningsss@163.com",
     description="An api testing framework",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/ae86sen/aomaker",
     packages=setuptools.find_packages(),
```


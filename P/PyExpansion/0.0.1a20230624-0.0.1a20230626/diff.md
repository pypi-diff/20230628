# Comparing `tmp/PyExpansion-0.0.1a20230624.tar.gz` & `tmp/PyExpansion-0.0.1a20230626.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyExpansion-0.0.1a20230624.tar", last modified: Sun Jun 25 02:54:37 2023, max compression
+gzip compressed data, was "PyExpansion-0.0.1a20230626.tar", last modified: Wed Jun 28 13:57:58 2023, max compression
```

## Comparing `PyExpansion-0.0.1a20230624.tar` & `PyExpansion-0.0.1a20230626.tar`

### file list

```diff
@@ -1,55 +1,84 @@
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.606905 PyExpansion-0.0.1a20230624/
--rw-rw-rw-   0        0        0     1081 2023-06-17 07:28:57.000000 PyExpansion-0.0.1a20230624/LICENSE.txt
--rw-rw-rw-   0        0        0        0 2023-06-17 09:17:44.000000 PyExpansion-0.0.1a20230624/MANIFEST.in
--rw-rw-rw-   0        0        0     1465 2023-06-25 02:54:37.606905 PyExpansion-0.0.1a20230624/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.465707 PyExpansion-0.0.1a20230624/PyExpansion/
--rw-rw-rw-   0        0        0        0 2023-06-05 07:29:27.000000 PyExpansion-0.0.1a20230624/PyExpansion/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.481881 PyExpansion-0.0.1a20230624/PyExpansion/application/
--rw-rw-rw-   0        0        0        0 2023-06-17 09:22:08.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.481881 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.513171 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/
--rw-rw-rw-   0        0        0        0 2023-06-17 03:59:05.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.528748 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/
--rw-rw-rw-   0        0        0     8543 2023-06-24 15:35:29.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/Malaysia.py
--rw-rw-rw-   0        0        0     2913 2023-06-24 10:35:35.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/Singapore.py
--rw-rw-rw-   0        0        0        0 2023-06-17 06:05:34.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/__init__.py
--rw-rw-rw-   0        0        0      215 2023-06-24 15:35:22.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/base.py
--rw-rw-rw-   0        0        0     1090 2023-06-24 09:43:29.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/main.py
--rw-rw-rw-   0        0        0      509 2023-06-24 15:34:57.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/status_code_list.py
--rw-rw-rw-   0        0        0     1827 2023-06-24 09:46:15.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/tests.py
--rw-rw-rw-   0        0        0        0 2023-06-22 15:31:40.000000 PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.544378 PyExpansion-0.0.1a20230624/PyExpansion/common/
--rw-rw-rw-   0        0        0        0 2023-06-17 09:35:58.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/__init__.py
--rw-rw-rw-   0        0        0      144 2023-06-18 10:34:10.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/basic_function.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.544378 PyExpansion-0.0.1a20230624/PyExpansion/common/constants/
--rw-rw-rw-   0        0        0        0 2023-06-24 09:11:08.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/constants/__init__.py
--rw-rw-rw-   0        0        0      158 2023-06-24 09:13:45.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/constants/common.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.560042 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/
--rw-rw-rw-   0        0        0        0 2023-06-18 07:42:28.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.575663 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/lists/
--rw-rw-rw-   0        0        0        0 2023-06-18 08:46:51.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/lists/__init__.py
--rw-rw-rw-   0        0        0      464 2023-06-18 09:06:26.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/lists/main.py
--rw-rw-rw-   0        0        0      327 2023-06-18 09:06:26.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/lists/status_code_list.py
--rw-rw-rw-   0        0        0      395 2023-06-18 09:13:12.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/data_type/lists/tests.py
--rw-rw-rw-   0        0        0      989 2023-06-24 10:06:05.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/message.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.575663 PyExpansion-0.0.1a20230624/PyExpansion/common/status_code/
--rw-rw-rw-   0        0        0        0 2023-06-24 07:45:47.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/status_code/__init__.py
--rw-rw-rw-   0        0        0     9071 2023-06-25 01:23:17.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/status_code/http_code.py
--rw-rw-rw-   0        0        0      283 2023-06-25 02:14:18.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/status_code/utils.py
--rw-rw-rw-   0        0        0     2978 2023-06-24 15:34:07.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/utils.py
--rw-rw-rw-   0        0        0     2718 2023-06-24 08:09:05.000000 PyExpansion-0.0.1a20230624/PyExpansion/common/version_history.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.591232 PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.606905 PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/PyBrainFuck/
--rw-rw-rw-   0        0        0        0 2023-06-23 11:30:05.000000 PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/PyBrainFuck/__init__.py
--rw-rw-rw-   0        0        0     4943 2023-06-25 02:22:18.000000 PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/PyBrainFuck/main.py
--rw-rw-rw-   0        0        0      430 2023-06-25 02:23:03.000000 PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/PyBrainFuck/tests.py
--rw-rw-rw-   0        0        0        0 2023-06-23 11:29:40.000000 PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/__init__.py
--rw-rw-rw-   0        0        0      951 2023-06-25 02:48:09.000000 PyExpansion-0.0.1a20230624/PyExpansion/version.py
-drwxrwxrwx   0        0        0        0 2023-06-25 02:54:37.481881 PyExpansion-0.0.1a20230624/PyExpansion.egg-info/
--rw-rw-rw-   0        0        0     1465 2023-06-25 02:54:37.000000 PyExpansion-0.0.1a20230624/PyExpansion.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1572 2023-06-25 02:54:37.000000 PyExpansion-0.0.1a20230624/PyExpansion.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-25 02:54:37.000000 PyExpansion-0.0.1a20230624/PyExpansion.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       12 2023-06-25 02:54:37.000000 PyExpansion-0.0.1a20230624/PyExpansion.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     1304 2023-06-25 02:34:04.000000 PyExpansion-0.0.1a20230624/README.md
--rw-rw-rw-   0        0        0       42 2023-06-25 02:54:37.606905 PyExpansion-0.0.1a20230624/setup.cfg
--rw-rw-rw-   0        0        0      522 2023-06-21 17:16:35.000000 PyExpansion-0.0.1a20230624/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.291463 PyExpansion-0.0.1a20230626/
+-rw-rw-rw-   0        0        0     1081 2023-06-17 07:28:57.000000 PyExpansion-0.0.1a20230626/LICENSE.txt
+-rw-rw-rw-   0        0        0        0 2023-06-17 09:17:44.000000 PyExpansion-0.0.1a20230626/MANIFEST.in
+-rw-rw-rw-   0        0        0     1727 2023-06-28 13:57:58.286381 PyExpansion-0.0.1a20230626/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.011284 PyExpansion-0.0.1a20230626/PyExpansion/
+-rw-rw-rw-   0        0        0        0 2023-06-05 07:29:27.000000 PyExpansion-0.0.1a20230626/PyExpansion/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.031345 PyExpansion-0.0.1a20230626/PyExpansion/application/
+-rw-rw-rw-   0        0        0        0 2023-06-17 09:22:08.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.036373 PyExpansion-0.0.1a20230626/PyExpansion/application/datetime/
+-rw-rw-rw-   0        0        0        0 2023-06-26 12:46:25.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/datetime/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.041484 PyExpansion-0.0.1a20230626/PyExpansion/application/finance/
+-rw-rw-rw-   0        0        0        0 2023-06-26 08:09:50.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/finance/__init__.py
+-rw-rw-rw-   0        0        0     2387 2023-06-26 13:44:48.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/finance/calculator.py
+-rw-rw-rw-   0        0        0     1075 2023-06-26 09:41:55.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/finance/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.051641 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.071616 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/
+-rw-rw-rw-   0        0        0        0 2023-06-17 03:59:05.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.106771 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/
+-rw-rw-rw-   0        0        0     8543 2023-06-24 15:35:29.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/Malaysia.py
+-rw-rw-rw-   0        0        0     2913 2023-06-24 10:35:35.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/Singapore.py
+-rw-rw-rw-   0        0        0        0 2023-06-17 06:05:34.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/__init__.py
+-rw-rw-rw-   0        0        0      215 2023-06-24 15:35:22.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/base.py
+-rw-rw-rw-   0        0        0     1090 2023-06-24 09:43:29.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/main.py
+-rw-rw-rw-   0        0        0      509 2023-06-24 15:34:57.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/status_code_list.py
+-rw-rw-rw-   0        0        0     1827 2023-06-24 09:46:15.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/tests.py
+-rw-rw-rw-   0        0        0        0 2023-06-22 15:31:40.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.111323 PyExpansion-0.0.1a20230626/PyExpansion/application/maths/
+-rw-rw-rw-   0        0        0        0 2023-06-25 09:40:34.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/maths/__init__.py
+-rw-rw-rw-   0        0        0     2037 2023-06-26 10:00:13.000000 PyExpansion-0.0.1a20230626/PyExpansion/application/maths/table.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.141677 PyExpansion-0.0.1a20230626/PyExpansion/common/
+-rw-rw-rw-   0        0        0        0 2023-06-17 09:35:58.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/__init__.py
+-rw-rw-rw-   0        0        0      144 2023-06-18 10:34:10.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/basic_function.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.156318 PyExpansion-0.0.1a20230626/PyExpansion/common/constants/
+-rw-rw-rw-   0        0        0        0 2023-06-24 09:11:08.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/constants/__init__.py
+-rw-rw-rw-   0        0        0      158 2023-06-24 09:13:45.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/constants/common.py
+-rw-rw-rw-   0        0        0      118 2023-06-25 04:45:04.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/constants/datetime.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.161405 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/
+-rw-rw-rw-   0        0        0        0 2023-06-18 07:42:28.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.176509 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/lists/
+-rw-rw-rw-   0        0        0        0 2023-06-18 08:46:51.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/lists/__init__.py
+-rw-rw-rw-   0        0        0      464 2023-06-18 09:06:26.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/lists/main.py
+-rw-rw-rw-   0        0        0      327 2023-06-18 09:06:26.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/lists/status_code_list.py
+-rw-rw-rw-   0        0        0      395 2023-06-18 09:13:12.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/data_type/lists/tests.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.186586 PyExpansion-0.0.1a20230626/PyExpansion/common/date_time/
+-rw-rw-rw-   0        0        0        0 2023-06-25 04:20:38.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/date_time/__init__.py
+-rw-rw-rw-   0        0        0      765 2023-06-28 13:47:45.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/date_time/reality.py
+-rw-rw-rw-   0        0        0      588 2023-06-26 13:12:55.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/date_time/utils.py
+-rw-rw-rw-   0        0        0      989 2023-06-24 10:06:05.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/message.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.211634 PyExpansion-0.0.1a20230626/PyExpansion/common/status_code/
+-rw-rw-rw-   0        0        0        0 2023-06-24 07:45:47.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/status_code/__init__.py
+-rw-rw-rw-   0        0        0     9071 2023-06-25 01:23:17.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/status_code/http_code.py
+-rw-rw-rw-   0        0        0      283 2023-06-25 02:14:18.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/status_code/utils.py
+-rw-rw-rw-   0        0        0      618 2023-06-26 13:45:15.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/table.py
+-rw-rw-rw-   0        0        0     2978 2023-06-24 15:34:07.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/utils.py
+-rw-rw-rw-   0        0        0     2718 2023-06-24 08:09:05.000000 PyExpansion-0.0.1a20230626/PyExpansion/common/version_history.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.216652 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.231593 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyBrainFuck/
+-rw-rw-rw-   0        0        0        0 2023-06-23 11:30:05.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyBrainFuck/__init__.py
+-rw-rw-rw-   0        0        0     4954 2023-06-26 09:06:49.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyBrainFuck/main.py
+-rw-rw-rw-   0        0        0      347 2023-06-26 09:06:49.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyBrainFuck/tests.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.241385 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyMorseCode/
+-rw-rw-rw-   0        0        0        0 2023-06-26 03:12:56.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyMorseCode/__init__.py
+-rw-rw-rw-   0        0        0     1729 2023-06-26 07:44:02.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyMorseCode/main.py
+-rw-rw-rw-   0        0        0      211 2023-06-26 07:50:09.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyMorseCode/tests.py
+-rw-rw-rw-   0        0        0        0 2023-06-23 11:29:40.000000 PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/__init__.py
+-rw-rw-rw-   0        0        0     1111 2023-06-26 09:02:12.000000 PyExpansion-0.0.1a20230626/PyExpansion/version.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.021418 PyExpansion-0.0.1a20230626/PyExpansion.egg-info/
+-rw-rw-rw-   0        0        0     1727 2023-06-28 13:57:57.000000 PyExpansion-0.0.1a20230626/PyExpansion.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     2364 2023-06-28 13:57:57.000000 PyExpansion-0.0.1a20230626/PyExpansion.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:57:57.000000 PyExpansion-0.0.1a20230626/PyExpansion.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       19 2023-06-28 13:57:57.000000 PyExpansion-0.0.1a20230626/PyExpansion.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     1566 2023-06-26 08:09:31.000000 PyExpansion-0.0.1a20230626/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:57:58.291463 PyExpansion-0.0.1a20230626/setup.cfg
+-rw-rw-rw-   0        0        0      522 2023-06-21 17:16:35.000000 PyExpansion-0.0.1a20230626/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.251462 PyExpansion-0.0.1a20230626/undone/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.278195 PyExpansion-0.0.1a20230626/undone/PyCalendar/
+-rw-rw-rw-   0        0        0        0 2023-06-26 12:47:01.000000 PyExpansion-0.0.1a20230626/undone/PyCalendar/__init__.py
+-rw-rw-rw-   0        0        0      379 2023-06-26 17:24:22.000000 PyExpansion-0.0.1a20230626/undone/PyCalendar/constants.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:58.286381 PyExpansion-0.0.1a20230626/undone/PyCalendar/holiday/
+-rw-rw-rw-   0        0        0        0 2023-06-26 17:25:02.000000 PyExpansion-0.0.1a20230626/undone/PyCalendar/holiday/__init__.py
+-rw-rw-rw-   0        0        0       10 2023-06-26 17:26:43.000000 PyExpansion-0.0.1a20230626/undone/PyCalendar/holiday/common.py
+-rw-rw-rw-   0        0        0      199 2023-06-27 00:36:32.000000 PyExpansion-0.0.1a20230626/undone/PyCalendar/main.py
+-rw-rw-rw-   0        0        0        0 2023-06-26 17:36:00.000000 PyExpansion-0.0.1a20230626/undone/PyCalendar/utils.py
+-rw-rw-rw-   0        0        0        0 2023-06-28 13:48:17.000000 PyExpansion-0.0.1a20230626/undone/__init__.py
```

### Comparing `PyExpansion-0.0.1a20230624/LICENSE.txt` & `PyExpansion-0.0.1a20230626/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PKG-INFO` & `PyExpansion-0.0.1a20230626/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -1,14 +1,7 @@
-Metadata-Version: 2.1
-Name: PyExpansion
-Version: 0.0.1a20230624
-Requires-Python: >=3
-Description-Content-Type: text/markdown
-License-File: LICENSE.txt
-
 # Overviews
 
 ![PyPI](https://img.shields.io/pypi/v/pyexpansion) &nbsp;
 ![License: MIT](https://img.shields.io/github/license/weitaoyap111/pyexpansion)&nbsp;
 ![GitHub issues](https://img.shields.io/github/issues/weitaoyap111/pyexpansion)&nbsp;
 ![GitHub pull requests](https://img.shields.io/github/issues-pr/weitaoyap111/pyexpansion)&nbsp;
 [![Downloads](https://static.pepy.tech/personalized-badge/pyexpansion?period=total&units=international_system&left_color=grey&right_color=brightgreen&left_text=Downloads)](https://pepy.tech/project/pyexpansion)&nbsp;
@@ -18,15 +11,26 @@
 
 # Installation
 How to install:
 ```
 pip install pyexpansion
 ```
 
-# Library List:
+# Author
+Copyright (c) 2023 Wei Tao Yap
+
+# Projects Status
+### Updated
+1) PyIC
+- Apply for Malaysia Only
+- Singapore Added
+2) PyBrainFuck is added
+3) PyMorseCode is added
+
+# Library Added:
 ## 1) PyIC
 ### What is this?
 - Python Script that extract the ic information from ic word.
 
 ### How to use it?
 - You can refer to PyIC\tests.py.
 
@@ -39,15 +43,16 @@
 
 ### How to use it?
 - You can refer to PyBrainFuck\tests.py.
 
 ### Want knows more? 
 you can read at PyBrainFuck\README.md
 
-# Projects Status
-### Updated
-- Apply for Malaysia Only
-- Singapore Added
-- PyBrainFuck is added
+## 3) PyMorseCode
+### What is this?
+- Python Script that decode and encode using Morse Code.
 
-# Author
-Copyright (c) 2023 Wei Tao Yap
+### How to use it?
+- You can refer to PyMorseCode\tests.py.
+
+### Want knows more? 
+you can read at PyMorseCode\README.md
```

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/Malaysia.py` & `PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/Malaysia.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/country/Singapore.py` & `PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/country/Singapore.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/main.py` & `PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/main.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/application/human_resource/PyIC/tests.py` & `PyExpansion-0.0.1a20230626/PyExpansion/application/human_resource/PyIC/tests.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/common/message.py` & `PyExpansion-0.0.1a20230626/PyExpansion/common/message.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/common/status_code/http_code.py` & `PyExpansion-0.0.1a20230626/PyExpansion/common/status_code/http_code.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/common/utils.py` & `PyExpansion-0.0.1a20230626/PyExpansion/common/utils.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/common/version_history.py` & `PyExpansion-0.0.1a20230626/PyExpansion/common/version_history.py`

 * *Files identical despite different names*

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/just_for_fun/PyBrainFuck/main.py` & `PyExpansion-0.0.1a20230626/PyExpansion/just_for_fun/PyBrainFuck/main.py`

 * *Files 5% similar despite different names*

```diff
@@ -42,55 +42,48 @@
         for x in data:
             try:
                 ord(x)
             except:
                 return False
         return True
 
-    def check_value(self, min_v=0, max_v=255):
-        value = self._array[self._ptr]
-        if value > max_v:
-            self._array[self._ptr] = min_v
-        if value < min_v:
-            self._array[self._ptr] = max_v
-
     def _inc_ptr(self, inc_v=1):
         self._ptr += inc_v
         if self._ptr > len(self._array) - 1:
             self._array.append(0)
 
     def _dec_ptr(self, dec_v=1):
         self._ptr -= dec_v
         if self._ptr < 0:
             self._ptr = 0
 
     def _inc_ptr_v(self, inc_v=1):
         self._array[self._ptr] += inc_v
-        self.check_value()
+        self._check_value()
 
     def _dec_ptr_v(self, dec_v=1):
         self._array[self._ptr] -= dec_v
-        self.check_value()
+        self._check_value()
 
-    def print_out(self, return_data=False):
+    def _print_out(self, return_data=False):
         if not return_data:
             print(chr(self._array[self._ptr]), end="")
         self._result_list.append(chr(self._array[self._ptr]))
 
-    def read_input(self):
+    def _read_input(self):
         if not self._user_input:
             self._user_input = list(input("Your Input: "))
         self._array[self._ptr] = ord(self._user_input.pop(0))
 
-    def left_loop(self, count):
+    def _left_loop(self, count):
         if not self._array[self._ptr]:
             count = self._loop_table[count]
         return count
 
-    def right_loop(self, count):
+    def _right_loop(self, count):
         if self._array[self._ptr]:
             count = self._loop_table[count]
         return count
 
     def _decode(self, data, return_data):
         for count, x in enumerate(data):
             if x == "[":
@@ -108,21 +101,21 @@
             elif x == "-":
                 self._dec_ptr_v()
             elif x == ">":
                 self._inc_ptr()
             elif x == "<":
                 self._dec_ptr()
             elif x == ".":
-                self.print_out(return_data)
+                self._print_out(return_data)
             elif x == ",":
-                self.read_input()
+                self._read_input()
             elif x == "[":
-                count = self.left_loop(count)
+                count = self._left_loop(count)
             elif x == "]":
-                count = self.right_loop(count)
+                count = self._right_loop(count)
 
             count += 1
 
     def bf_to_word(self, data, return_data=False):
         if self._verify_decode(data):
             self._decode_reset()
             self._decode(data, return_data)
@@ -149,14 +142,21 @@
                     word = ""
             prev = ord(x)
             word += "."
             output_list.append(word)
 
         return output_list
 
+    def _check_value(self, min_v=0, max_v=255):
+        value = self._array[self._ptr]
+        if value > max_v:
+            self._array[self._ptr] = min_v
+        if value < min_v:
+            self._array[self._ptr] = max_v
+
     def word_to_bf(self, data, return_data=False):
         if self._verify_encode(data):
             return self._encode(data)
         else:
             if return_data:
                 return "Invalid format"
             else:
```

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion/version.py` & `PyExpansion-0.0.1a20230626/PyExpansion/version.py`

 * *Files 8% similar despite different names*

```diff
@@ -18,17 +18,23 @@
 
     def version_3(self):
         return self.default_setup(
             application_name="PyBrainFuck",
             version="0.0.1a20230624",
         )
 
+    def version_4(self):
+        return self.default_setup(
+            application_name="PyMorseCode",
+            version="0.0.1a20230626",
+        )
+
 
 c = PyICVersionHistory()
-test = True
+test = False
 if test:
     print("How many version:", c.total_version())
     print("Version list:", c.get_version_list())
     print("Latest version: ", c.get_latest_version())
     print("Last version information: ", c.get_version_info(c.get_latest_version()))
 
 version = c.get_latest_version()
```

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion.egg-info/PKG-INFO` & `PyExpansion-0.0.1a20230626/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: PyExpansion
-Version: 0.0.1a20230624
+Version: 0.0.1a20230626
 Requires-Python: >=3
 Description-Content-Type: text/markdown
 License-File: LICENSE.txt
 
 # Overviews
 
 ![PyPI](https://img.shields.io/pypi/v/pyexpansion) &nbsp;
@@ -18,15 +18,26 @@
 
 # Installation
 How to install:
 ```
 pip install pyexpansion
 ```
 
-# Library List:
+# Author
+Copyright (c) 2023 Wei Tao Yap
+
+# Projects Status
+### Updated
+1) PyIC
+- Apply for Malaysia Only
+- Singapore Added
+2) PyBrainFuck is added
+3) PyMorseCode is added
+
+# Library Added:
 ## 1) PyIC
 ### What is this?
 - Python Script that extract the ic information from ic word.
 
 ### How to use it?
 - You can refer to PyIC\tests.py.
 
@@ -39,15 +50,16 @@
 
 ### How to use it?
 - You can refer to PyBrainFuck\tests.py.
 
 ### Want knows more? 
 you can read at PyBrainFuck\README.md
 
-# Projects Status
-### Updated
-- Apply for Malaysia Only
-- Singapore Added
-- PyBrainFuck is added
+## 3) PyMorseCode
+### What is this?
+- Python Script that decode and encode using Morse Code.
 
-# Author
-Copyright (c) 2023 Wei Tao Yap
+### How to use it?
+- You can refer to PyMorseCode\tests.py.
+
+### Want knows more? 
+you can read at PyMorseCode\README.md
```

### Comparing `PyExpansion-0.0.1a20230624/PyExpansion.egg-info/SOURCES.txt` & `PyExpansion-0.0.1a20230626/PyExpansion.egg-info/SOURCES.txt`

 * *Files 24% similar despite different names*

```diff
@@ -5,35 +5,56 @@
 PyExpansion/__init__.py
 PyExpansion/version.py
 PyExpansion.egg-info/PKG-INFO
 PyExpansion.egg-info/SOURCES.txt
 PyExpansion.egg-info/dependency_links.txt
 PyExpansion.egg-info/top_level.txt
 PyExpansion/application/__init__.py
+PyExpansion/application/datetime/__init__.py
+PyExpansion/application/finance/__init__.py
+PyExpansion/application/finance/calculator.py
+PyExpansion/application/finance/utils.py
 PyExpansion/application/human_resource/__init__.py
 PyExpansion/application/human_resource/PyIC/__init__.py
 PyExpansion/application/human_resource/PyIC/main.py
 PyExpansion/application/human_resource/PyIC/status_code_list.py
 PyExpansion/application/human_resource/PyIC/tests.py
 PyExpansion/application/human_resource/PyIC/country/Malaysia.py
 PyExpansion/application/human_resource/PyIC/country/Singapore.py
 PyExpansion/application/human_resource/PyIC/country/__init__.py
 PyExpansion/application/human_resource/PyIC/country/base.py
+PyExpansion/application/maths/__init__.py
+PyExpansion/application/maths/table.py
 PyExpansion/common/__init__.py
 PyExpansion/common/basic_function.py
 PyExpansion/common/message.py
+PyExpansion/common/table.py
 PyExpansion/common/utils.py
 PyExpansion/common/version_history.py
 PyExpansion/common/constants/__init__.py
 PyExpansion/common/constants/common.py
+PyExpansion/common/constants/datetime.py
 PyExpansion/common/data_type/__init__.py
 PyExpansion/common/data_type/lists/__init__.py
 PyExpansion/common/data_type/lists/main.py
 PyExpansion/common/data_type/lists/status_code_list.py
 PyExpansion/common/data_type/lists/tests.py
+PyExpansion/common/date_time/__init__.py
+PyExpansion/common/date_time/reality.py
+PyExpansion/common/date_time/utils.py
 PyExpansion/common/status_code/__init__.py
 PyExpansion/common/status_code/http_code.py
 PyExpansion/common/status_code/utils.py
 PyExpansion/just_for_fun/__init__.py
 PyExpansion/just_for_fun/PyBrainFuck/__init__.py
 PyExpansion/just_for_fun/PyBrainFuck/main.py
-PyExpansion/just_for_fun/PyBrainFuck/tests.py
+PyExpansion/just_for_fun/PyBrainFuck/tests.py
+PyExpansion/just_for_fun/PyMorseCode/__init__.py
+PyExpansion/just_for_fun/PyMorseCode/main.py
+PyExpansion/just_for_fun/PyMorseCode/tests.py
+undone/__init__.py
+undone/PyCalendar/__init__.py
+undone/PyCalendar/constants.py
+undone/PyCalendar/main.py
+undone/PyCalendar/utils.py
+undone/PyCalendar/holiday/__init__.py
+undone/PyCalendar/holiday/common.py
```

### Comparing `PyExpansion-0.0.1a20230624/setup.py` & `PyExpansion-0.0.1a20230626/setup.py`

 * *Files identical despite different names*


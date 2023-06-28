# Comparing `tmp/python-coiote-2.2.1.tar.gz` & `tmp/python-coiote-2.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "python-coiote-2.2.1.tar", last modified: Thu Feb 23 23:07:00 2023, max compression
+gzip compressed data, was "python-coiote-2.3.0.tar", last modified: Wed Jun 28 14:11:29 2023, max compression
```

## Comparing `python-coiote-2.2.1.tar` & `python-coiote-2.3.0.tar`

### file list

```diff
@@ -1,64 +1,66 @@
-drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-02-23 23:07:00.446519 python-coiote-2.2.1/
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1064 2022-11-21 13:49:36.000000 python-coiote-2.2.1/LICENSE
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     5228 2023-02-23 23:07:00.446716 python-coiote-2.2.1/PKG-INFO
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     4829 2023-02-23 22:52:35.000000 python-coiote-2.2.1/README.md
--rw-r--r--   0 michalgrabowski   (501) staff       (20)       84 2022-11-21 13:49:36.000000 python-coiote-2.2.1/pyproject.toml
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      634 2023-02-23 23:07:00.447973 python-coiote-2.2.1/setup.cfg
-drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-02-23 23:07:00.322823 python-coiote-2.2.1/src/
-drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-02-23 23:07:00.382021 python-coiote-2.2.1/src/coiote/
--rw-r--r--   0 michalgrabowski   (501) staff       (20)        0 2022-11-21 13:49:36.000000 python-coiote-2.2.1/src/coiote/__init__.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     2650 2023-01-16 14:51:40.000000 python-coiote-2.2.1/src/coiote/auth.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     3454 2022-11-28 13:38:28.000000 python-coiote-2.2.1/src/coiote/client.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     2991 2022-11-28 13:40:10.000000 python-coiote-2.2.1/src/coiote/device_client.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     4751 2023-02-23 23:03:32.000000 python-coiote-2.2.1/src/coiote/utils.py
-drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-02-23 23:07:00.422962 python-coiote-2.2.1/src/coiote/v3/
--rw-r--r--   0 michalgrabowski   (501) staff       (20)        0 2022-11-21 13:49:36.000000 python-coiote-2.2.1/src/coiote/v3/__init__.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1715 2022-12-01 11:38:08.000000 python-coiote-2.2.1/src/coiote/v3/assigned_device_properties.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      636 2022-12-01 10:28:34.000000 python-coiote-2.2.1/src/coiote/v3/aws_integration.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      557 2022-12-01 10:28:49.000000 python-coiote-2.2.1/src/coiote/v3/cert_auth.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      719 2022-12-01 11:42:16.000000 python-coiote-2.2.1/src/coiote/v3/data_model.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     3576 2023-02-23 22:49:53.000000 python-coiote-2.2.1/src/coiote/v3/device_monitoring.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1032 2022-12-01 11:44:20.000000 python-coiote-2.2.1/src/coiote/v3/device_resources.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1804 2022-12-01 12:22:39.000000 python-coiote-2.2.1/src/coiote/v3/device_tests.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     2634 2022-12-01 10:30:06.000000 python-coiote-2.2.1/src/coiote/v3/devices.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      683 2022-12-01 12:03:45.000000 python-coiote-2.2.1/src/coiote/v3/dialects.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1378 2022-12-01 10:39:53.000000 python-coiote-2.2.1/src/coiote/v3/domains.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     3369 2022-12-01 10:42:06.000000 python-coiote-2.2.1/src/coiote/v3/extensions.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1332 2022-12-01 10:42:38.000000 python-coiote-2.2.1/src/coiote/v3/groups.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      702 2022-12-01 10:42:53.000000 python-coiote-2.2.1/src/coiote/v3/lifecycle_management.py
-drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-02-23 23:07:00.441691 python-coiote-2.2.1/src/coiote/v3/model/
--rw-r--r--   0 michalgrabowski   (501) staff       (20)        0 2022-11-21 13:49:36.000000 python-coiote-2.2.1/src/coiote/v3/model/__init__.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      901 2022-11-25 10:05:01.000000 python-coiote-2.2.1/src/coiote/v3/model/assigned_device_properties.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      117 2022-11-23 15:40:45.000000 python-coiote-2.2.1/src/coiote/v3/model/aws_integration.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)       94 2022-11-23 16:04:00.000000 python-coiote-2.2.1/src/coiote/v3/model/cert_auth.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      168 2022-11-21 13:49:36.000000 python-coiote-2.2.1/src/coiote/v3/model/data_model.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      546 2022-11-24 14:28:00.000000 python-coiote-2.2.1/src/coiote/v3/model/device_monitoring.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1759 2022-11-28 13:27:27.000000 python-coiote-2.2.1/src/coiote/v3/model/device_resources.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      458 2022-11-24 13:12:26.000000 python-coiote-2.2.1/src/coiote/v3/model/device_tests.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     2591 2022-11-28 13:52:30.000000 python-coiote-2.2.1/src/coiote/v3/model/devices.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)       81 2022-11-23 14:06:11.000000 python-coiote-2.2.1/src/coiote/v3/model/dialects.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      213 2022-11-21 14:18:19.000000 python-coiote-2.2.1/src/coiote/v3/model/domains.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      614 2022-11-24 14:04:54.000000 python-coiote-2.2.1/src/coiote/v3/model/extensions.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      208 2022-11-25 09:08:50.000000 python-coiote-2.2.1/src/coiote/v3/model/groups.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      114 2022-11-23 15:19:01.000000 python-coiote-2.2.1/src/coiote/v3/model/lifecycle_management.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      840 2022-11-25 11:08:18.000000 python-coiote-2.2.1/src/coiote/v3/model/observations.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1616 2022-11-28 13:57:29.000000 python-coiote-2.2.1/src/coiote/v3/model/resources.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      195 2022-11-23 13:38:55.000000 python-coiote-2.2.1/src/coiote/v3/model/setting_values.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      706 2022-11-22 11:48:03.000000 python-coiote-2.2.1/src/coiote/v3/model/task_reports.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      367 2022-11-21 13:49:36.000000 python-coiote-2.2.1/src/coiote/v3/model/task_templates.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1588 2022-11-28 13:27:31.000000 python-coiote-2.2.1/src/coiote/v3/model/tasks.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1085 2022-11-22 11:19:31.000000 python-coiote-2.2.1/src/coiote/v3/model/users.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     2340 2022-12-01 10:43:35.000000 python-coiote-2.2.1/src/coiote/v3/observations.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1393 2022-12-01 10:44:07.000000 python-coiote-2.2.1/src/coiote/v3/resources.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)      673 2022-12-01 10:44:17.000000 python-coiote-2.2.1/src/coiote/v3/sessions.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1313 2022-12-01 10:44:59.000000 python-coiote-2.2.1/src/coiote/v3/setting_values.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     2262 2022-12-01 10:45:40.000000 python-coiote-2.2.1/src/coiote/v3/task_reports.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1259 2022-12-01 10:46:10.000000 python-coiote-2.2.1/src/coiote/v3/task_templates.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     3384 2022-12-01 10:47:03.000000 python-coiote-2.2.1/src/coiote/v3/tasks.py
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1733 2022-12-01 10:47:49.000000 python-coiote-2.2.1/src/coiote/v3/users.py
-drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-02-23 23:07:00.446099 python-coiote-2.2.1/src/python_coiote.egg-info/
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     5228 2023-02-23 23:07:00.000000 python-coiote-2.2.1/src/python_coiote.egg-info/PKG-INFO
--rw-r--r--   0 michalgrabowski   (501) staff       (20)     1749 2023-02-23 23:07:00.000000 python-coiote-2.2.1/src/python_coiote.egg-info/SOURCES.txt
--rw-r--r--   0 michalgrabowski   (501) staff       (20)        1 2023-02-23 23:07:00.000000 python-coiote-2.2.1/src/python_coiote.egg-info/dependency_links.txt
--rw-r--r--   0 michalgrabowski   (501) staff       (20)       85 2023-02-23 23:07:00.000000 python-coiote-2.2.1/src/python_coiote.egg-info/requires.txt
--rw-r--r--   0 michalgrabowski   (501) staff       (20)        7 2023-02-23 23:07:00.000000 python-coiote-2.2.1/src/python_coiote.egg-info/top_level.txt
+drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-06-28 14:11:28.992536 python-coiote-2.3.0/
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1064 2022-11-21 13:49:36.000000 python-coiote-2.3.0/LICENSE
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3506 2023-06-28 14:11:28.992885 python-coiote-2.3.0/PKG-INFO
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3107 2023-06-28 14:07:21.000000 python-coiote-2.3.0/README.md
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)       84 2022-11-21 13:49:36.000000 python-coiote-2.3.0/pyproject.toml
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      634 2023-06-28 14:11:28.999258 python-coiote-2.3.0/setup.cfg
+drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-06-28 14:11:28.911905 python-coiote-2.3.0/src/
+drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-06-28 14:11:28.918592 python-coiote-2.3.0/src/coiote/
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)        0 2022-11-21 13:49:36.000000 python-coiote-2.3.0/src/coiote/__init__.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2650 2023-01-16 14:51:40.000000 python-coiote-2.3.0/src/coiote/auth.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3637 2023-06-27 13:48:34.000000 python-coiote-2.3.0/src/coiote/client.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2991 2022-11-28 13:40:10.000000 python-coiote-2.3.0/src/coiote/device_client.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     4910 2023-06-28 08:45:59.000000 python-coiote-2.3.0/src/coiote/utils.py
+drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-06-28 14:11:28.944130 python-coiote-2.3.0/src/coiote/v3/
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)        0 2022-11-21 13:49:36.000000 python-coiote-2.3.0/src/coiote/v3/__init__.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1715 2022-12-01 11:38:08.000000 python-coiote-2.3.0/src/coiote/v3/assigned_device_properties.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      636 2022-12-01 10:28:34.000000 python-coiote-2.3.0/src/coiote/v3/aws_integration.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      557 2022-12-01 10:28:49.000000 python-coiote-2.3.0/src/coiote/v3/cert_auth.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      719 2022-12-01 11:42:16.000000 python-coiote-2.3.0/src/coiote/v3/data_model.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3000 2023-06-28 13:29:01.000000 python-coiote-2.3.0/src/coiote/v3/device_events.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3576 2023-02-23 22:49:53.000000 python-coiote-2.3.0/src/coiote/v3/device_monitoring.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1032 2022-12-01 11:44:20.000000 python-coiote-2.3.0/src/coiote/v3/device_resources.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1804 2022-12-01 12:22:39.000000 python-coiote-2.3.0/src/coiote/v3/device_tests.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2634 2022-12-01 10:30:06.000000 python-coiote-2.3.0/src/coiote/v3/devices.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      683 2022-12-01 12:03:45.000000 python-coiote-2.3.0/src/coiote/v3/dialects.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1378 2022-12-01 10:39:53.000000 python-coiote-2.3.0/src/coiote/v3/domains.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3369 2022-12-01 10:42:06.000000 python-coiote-2.3.0/src/coiote/v3/extensions.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1332 2022-12-01 10:42:38.000000 python-coiote-2.3.0/src/coiote/v3/groups.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      702 2022-12-01 10:42:53.000000 python-coiote-2.3.0/src/coiote/v3/lifecycle_management.py
+drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-06-28 14:11:28.981785 python-coiote-2.3.0/src/coiote/v3/model/
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)        0 2022-11-21 13:49:36.000000 python-coiote-2.3.0/src/coiote/v3/model/__init__.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      901 2022-11-25 10:05:01.000000 python-coiote-2.3.0/src/coiote/v3/model/assigned_device_properties.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      117 2022-11-23 15:40:45.000000 python-coiote-2.3.0/src/coiote/v3/model/aws_integration.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)       94 2022-11-23 16:04:00.000000 python-coiote-2.3.0/src/coiote/v3/model/cert_auth.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      168 2022-11-21 13:49:36.000000 python-coiote-2.3.0/src/coiote/v3/model/data_model.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2253 2023-06-28 13:09:08.000000 python-coiote-2.3.0/src/coiote/v3/model/device_events.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      546 2022-11-24 14:28:00.000000 python-coiote-2.3.0/src/coiote/v3/model/device_monitoring.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1759 2022-11-28 13:27:27.000000 python-coiote-2.3.0/src/coiote/v3/model/device_resources.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      458 2022-11-24 13:12:26.000000 python-coiote-2.3.0/src/coiote/v3/model/device_tests.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2591 2022-11-28 13:52:30.000000 python-coiote-2.3.0/src/coiote/v3/model/devices.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)       81 2022-11-23 14:06:11.000000 python-coiote-2.3.0/src/coiote/v3/model/dialects.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      213 2022-11-21 14:18:19.000000 python-coiote-2.3.0/src/coiote/v3/model/domains.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      614 2022-11-24 14:04:54.000000 python-coiote-2.3.0/src/coiote/v3/model/extensions.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      208 2022-11-25 09:08:50.000000 python-coiote-2.3.0/src/coiote/v3/model/groups.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      114 2022-11-23 15:19:01.000000 python-coiote-2.3.0/src/coiote/v3/model/lifecycle_management.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      840 2022-11-25 11:08:18.000000 python-coiote-2.3.0/src/coiote/v3/model/observations.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1616 2022-11-28 13:57:29.000000 python-coiote-2.3.0/src/coiote/v3/model/resources.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      195 2022-11-23 13:38:55.000000 python-coiote-2.3.0/src/coiote/v3/model/setting_values.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      706 2022-11-22 11:48:03.000000 python-coiote-2.3.0/src/coiote/v3/model/task_reports.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      367 2022-11-21 13:49:36.000000 python-coiote-2.3.0/src/coiote/v3/model/task_templates.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1588 2022-11-28 13:27:31.000000 python-coiote-2.3.0/src/coiote/v3/model/tasks.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1085 2022-11-22 11:19:31.000000 python-coiote-2.3.0/src/coiote/v3/model/users.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2340 2022-12-01 10:43:35.000000 python-coiote-2.3.0/src/coiote/v3/observations.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1393 2022-12-01 10:44:07.000000 python-coiote-2.3.0/src/coiote/v3/resources.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)      673 2022-12-01 10:44:17.000000 python-coiote-2.3.0/src/coiote/v3/sessions.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1313 2022-12-01 10:44:59.000000 python-coiote-2.3.0/src/coiote/v3/setting_values.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     2262 2022-12-01 10:45:40.000000 python-coiote-2.3.0/src/coiote/v3/task_reports.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1259 2022-12-01 10:46:10.000000 python-coiote-2.3.0/src/coiote/v3/task_templates.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3384 2022-12-01 10:47:03.000000 python-coiote-2.3.0/src/coiote/v3/tasks.py
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1733 2022-12-01 10:47:49.000000 python-coiote-2.3.0/src/coiote/v3/users.py
+drwxr-xr-x   0 michalgrabowski   (501) staff       (20)        0 2023-06-28 14:11:28.991872 python-coiote-2.3.0/src/python_coiote.egg-info/
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     3506 2023-06-28 14:11:28.000000 python-coiote-2.3.0/src/python_coiote.egg-info/PKG-INFO
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)     1817 2023-06-28 14:11:28.000000 python-coiote-2.3.0/src/python_coiote.egg-info/SOURCES.txt
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)        1 2023-06-28 14:11:28.000000 python-coiote-2.3.0/src/python_coiote.egg-info/dependency_links.txt
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)       85 2023-06-28 14:11:28.000000 python-coiote-2.3.0/src/python_coiote.egg-info/requires.txt
+-rw-r--r--   0 michalgrabowski   (501) staff       (20)        7 2023-06-28 14:11:28.000000 python-coiote-2.3.0/src/python_coiote.egg-info/top_level.txt
```

### Comparing `python-coiote-2.2.1/LICENSE` & `python-coiote-2.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/setup.cfg` & `python-coiote-2.3.0/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = python-coiote
-version = 2.2.1
+version = 2.3.0
 maintainer = Michał Grabowski
 maintainer_email = m.grabowski@avsystem.com
 description = Interact with Coiote DM API
 long_description = file: README.md
 long_description_content_type = text/markdown
 classifiers = 
 	Programming Language :: Python :: 3
```

### Comparing `python-coiote-2.2.1/src/coiote/auth.py` & `python-coiote-2.3.0/src/coiote/auth.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/client.py` & `python-coiote-2.3.0/src/coiote/client.py`

 * *Files 7% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 from .auth import Authenticator
 from .v3.assigned_device_properties import AssignedDeviceProperties
 from .v3.aws_integration import AwsIntegration
 from .v3.cert_auth import CertAuth
 from .v3.device_resources import DeviceResources
 from .v3.device_tests import DeviceTests
 from .v3.devices import Devices
+from .v3.device_events import DeviceEvents
 from .v3.dialects import Dialects
 from .v3.domains import Domains
 from .v3.data_model import DataModel
 from .v3.device_monitoring import DeviceMonitoring
 from .v3.extensions import Extensions
 from .v3.groups import Groups
 from .v3.lifecycle_management import LifecycleManagement
@@ -45,27 +46,33 @@
             raise ValueError("Only v3 API is supported right now")
         self.api_url = f"{url}/api/coiotedm/{api_version}"
         self.session = requests.Session()
         self.session.verify = verify_ssl
         self.authenticator = Authenticator(
             self.url, self.session, auth=auth)
 
-        self.aws_integration: AwsIntegration = self._make_module(AwsIntegration)
-        self.assigned_device_properties: AssignedDeviceProperties = self._make_module(AssignedDeviceProperties)
+        self.aws_integration: AwsIntegration = self._make_module(
+            AwsIntegration)
+        self.assigned_device_properties: AssignedDeviceProperties = self._make_module(
+            AssignedDeviceProperties)
         self.cert_auth: CertAuth = self._make_module(CertAuth)
         self.data_model: DataModel = self._make_module(DataModel)
-        self.device_monitoring: DeviceMonitoring = self._make_module(DeviceMonitoring)
-        self.device_resources: DeviceResources = self._make_module(DeviceResources)
+        self.device_monitoring: DeviceMonitoring = self._make_module(
+            DeviceMonitoring)
+        self.device_resources: DeviceResources = self._make_module(
+            DeviceResources)
         self.device_tests: DeviceTests = self._make_module(DeviceTests)
         self.devices: Devices = self._make_module(Devices)
         self.dialects: Dialects = self._make_module(Dialects)
+        self.device_events: DeviceEvents = self._make_module(DeviceEvents)
         self.domains: Domains = self._make_module(Domains)
         self.extensions: Extensions = self._make_module(Extensions)
         self.groups: Groups = self._make_module(Groups)
-        self.lifecycle_management: LifecycleManagement = self._make_module(LifecycleManagement)
+        self.lifecycle_management: LifecycleManagement = self._make_module(
+            LifecycleManagement)
         self.observations: Observations = self._make_module(Observations)
         self.resources: Resources = self._make_module(Resources)
         self.sessions: Sessions = self._make_module(Sessions)
         self.setting_values: SettingValues = self._make_module(SettingValues)
         self.task_reports: TaskReports = self._make_module(TaskReports)
         self.task_templates: TaskTemplates = self._make_module(TaskTemplates)
         self.tasks: Tasks = self._make_module(Tasks)
```

### Comparing `python-coiote-2.2.1/src/coiote/device_client.py` & `python-coiote-2.3.0/src/coiote/device_client.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/utils.py` & `python-coiote-2.3.0/src/coiote/utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,16 +46,19 @@
     if response_type is int:
         return int(json)
     elif response_type is str:
         return str(json)
     elif response_type is float:
         return float(json)
     else:
-        return from_dict(data_class=response_type, data=json, config=config.Config(type_hooks=TYPE_HOOKS, cast=[Enum]))
-
+        try:
+            return from_dict(data_class=response_type, data=json, config=config.Config(type_hooks=TYPE_HOOKS, cast=[Enum]))
+        except Exception as cause:
+            raise ValueError(f"Failed to deserialize response: {json}") from cause
+            
 
 def _safe_get_json(response: Optional[Response]) -> Any:
     try:
         return response.json() if response is not None else None
     except:
         return None
 
@@ -64,15 +67,15 @@
     json = _safe_get_json(response)
     headers = response.headers
     code = response.status_code
     return f"Code:\n{code}\nHeaders:\n{headers}\nBody:\n{json}"
 
 
 def _make_error(msg: str, response: Optional[Response]):
-    if response:
+    if response is not None:
         summary = _get_response_summary(response)
     else:
         summary = "No response data."
     return ValueError(f"{msg}\n{summary}")
 
 
 def is_optional(field: Type[T]) -> bool:
```

### Comparing `python-coiote-2.2.1/src/coiote/v3/assigned_device_properties.py` & `python-coiote-2.3.0/src/coiote/v3/assigned_device_properties.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/aws_integration.py` & `python-coiote-2.3.0/src/coiote/v3/aws_integration.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/cert_auth.py` & `python-coiote-2.3.0/src/coiote/v3/cert_auth.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/data_model.py` & `python-coiote-2.3.0/src/coiote/v3/data_model.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/device_monitoring.py` & `python-coiote-2.3.0/src/coiote/v3/device_monitoring.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/device_resources.py` & `python-coiote-2.3.0/src/coiote/v3/device_resources.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/device_tests.py` & `python-coiote-2.3.0/src/coiote/v3/device_tests.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/devices.py` & `python-coiote-2.3.0/src/coiote/v3/devices.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/dialects.py` & `python-coiote-2.3.0/src/coiote/v3/dialects.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/domains.py` & `python-coiote-2.3.0/src/coiote/v3/domains.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/extensions.py` & `python-coiote-2.3.0/src/coiote/v3/extensions.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/groups.py` & `python-coiote-2.3.0/src/coiote/v3/groups.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/lifecycle_management.py` & `python-coiote-2.3.0/src/coiote/v3/lifecycle_management.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/assigned_device_properties.py` & `python-coiote-2.3.0/src/coiote/v3/model/assigned_device_properties.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/device_monitoring.py` & `python-coiote-2.3.0/src/coiote/v3/model/device_monitoring.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/device_resources.py` & `python-coiote-2.3.0/src/coiote/v3/model/device_resources.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/devices.py` & `python-coiote-2.3.0/src/coiote/v3/model/devices.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/extensions.py` & `python-coiote-2.3.0/src/coiote/v3/model/extensions.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/observations.py` & `python-coiote-2.3.0/src/coiote/v3/model/observations.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/resources.py` & `python-coiote-2.3.0/src/coiote/v3/model/resources.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/task_reports.py` & `python-coiote-2.3.0/src/coiote/v3/model/task_reports.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/tasks.py` & `python-coiote-2.3.0/src/coiote/v3/model/tasks.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/model/users.py` & `python-coiote-2.3.0/src/coiote/v3/model/users.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/observations.py` & `python-coiote-2.3.0/src/coiote/v3/observations.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/resources.py` & `python-coiote-2.3.0/src/coiote/v3/resources.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/sessions.py` & `python-coiote-2.3.0/src/coiote/v3/sessions.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/setting_values.py` & `python-coiote-2.3.0/src/coiote/v3/setting_values.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/task_reports.py` & `python-coiote-2.3.0/src/coiote/v3/task_reports.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/task_templates.py` & `python-coiote-2.3.0/src/coiote/v3/task_templates.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/tasks.py` & `python-coiote-2.3.0/src/coiote/v3/tasks.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/coiote/v3/users.py` & `python-coiote-2.3.0/src/coiote/v3/users.py`

 * *Files identical despite different names*

### Comparing `python-coiote-2.2.1/src/python_coiote.egg-info/SOURCES.txt` & `python-coiote-2.3.0/src/python_coiote.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 src/coiote/device_client.py
 src/coiote/utils.py
 src/coiote/v3/__init__.py
 src/coiote/v3/assigned_device_properties.py
 src/coiote/v3/aws_integration.py
 src/coiote/v3/cert_auth.py
 src/coiote/v3/data_model.py
+src/coiote/v3/device_events.py
 src/coiote/v3/device_monitoring.py
 src/coiote/v3/device_resources.py
 src/coiote/v3/device_tests.py
 src/coiote/v3/devices.py
 src/coiote/v3/dialects.py
 src/coiote/v3/domains.py
 src/coiote/v3/extensions.py
@@ -30,14 +31,15 @@
 src/coiote/v3/tasks.py
 src/coiote/v3/users.py
 src/coiote/v3/model/__init__.py
 src/coiote/v3/model/assigned_device_properties.py
 src/coiote/v3/model/aws_integration.py
 src/coiote/v3/model/cert_auth.py
 src/coiote/v3/model/data_model.py
+src/coiote/v3/model/device_events.py
 src/coiote/v3/model/device_monitoring.py
 src/coiote/v3/model/device_resources.py
 src/coiote/v3/model/device_tests.py
 src/coiote/v3/model/devices.py
 src/coiote/v3/model/dialects.py
 src/coiote/v3/model/domains.py
 src/coiote/v3/model/extensions.py
```


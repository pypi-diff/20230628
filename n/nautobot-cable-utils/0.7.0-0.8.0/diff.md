# Comparing `tmp/nautobot-cable-utils-0.7.0.tar.gz` & `tmp/nautobot-cable-utils-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nautobot-cable-utils-0.7.0.tar", last modified: Fri Oct  7 17:32:07 2022, max compression
+gzip compressed data, was "nautobot-cable-utils-0.8.0.tar", last modified: Mon Nov  7 16:34:18 2022, max compression
```

## Comparing `nautobot-cable-utils-0.7.0.tar` & `nautobot-cable-utils-0.8.0.tar`

### file list

```diff
@@ -1,57 +1,57 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.253608 nautobot-cable-utils-0.7.0/
--rw-rw-rw-   0 root         (0) root         (0)      608 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/LICENSE.txt
--rw-rw-rw-   0 root         (0) root         (0)       93 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     4773 2022-10-07 17:32:07.253608 nautobot-cable-utils-0.7.0/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     4408 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.209608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/
--rw-rw-rw-   0 root         (0) root         (0)      502 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      261 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/admin.py
--rw-rw-rw-   0 root         (0) root         (0)    14260 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/cable_router.py
--rw-rw-rw-   0 root         (0) root         (0)     1543 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/filters.py
--rw-rw-rw-   0 root         (0) root         (0)    26979 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/forms.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.221608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/
--rw-rw-rw-   0 root         (0) root         (0)     1751 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0001_initial.py
--rw-rw-rw-   0 root         (0) root         (0)     1243 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0002_auto_20220808_0747.py
--rw-rw-rw-   0 root         (0) root         (0)      383 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0003_rename_tenant_cabletemplate_owner.py
--rw-rw-rw-   0 root         (0) root         (0)      403 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0004_rename_cable_number_cabletemplate_name.py
--rw-rw-rw-   0 root         (0) root         (0)      439 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0005_alter_cabletemplate_name.py
--rw-rw-rw-   0 root         (0) root         (0)        0 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     1866 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/models.py
--rw-rw-rw-   0 root         (0) root         (0)      932 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/navigation.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.197608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/static/
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.229608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/static/nautobot_cable_utils/
--rw-rw-rw-   0 root         (0) root         (0)   348509 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/static/nautobot_cable_utils/html5-qrcode.min.js
--rw-rw-rw-   0 root         (0) root         (0)     1411 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/static/nautobot_cable_utils/qr-scanner.js
--rw-rw-rw-   0 root         (0) root         (0)     2451 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/tables.py
--rw-rw-rw-   0 root         (0) root         (0)     1898 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/template_content.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.197608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.245608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/
--rw-rw-rw-   0 root         (0) root         (0)     2036 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/bulk_commission.html
--rw-rw-rw-   0 root         (0) root         (0)     6842 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_connect.html
--rw-rw-rw-   0 root         (0) root         (0)     5443 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_add.html
--rw-rw-rw-   0 root         (0) root         (0)     2220 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_verify.html
--rw-rw-rw-   0 root         (0) root         (0)      386 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_template_list.html
--rw-rw-rw-   0 root         (0) root         (0)      979 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_bulk_add.html
--rw-rw-rw-   0 root         (0) root         (0)      520 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_edit.html
--rw-rw-rw-   0 root         (0) root         (0)     1134 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/commission_cable.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.253608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/
--rw-rw-rw-   0 root         (0) root         (0)      797 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons.html
--rw-rw-rw-   0 root         (0) root         (0)      235 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_device.html
--rw-rw-rw-   0 root         (0) root         (0)      782 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_frontport.html
--rw-rw-rw-   0 root         (0) root         (0)      780 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_interface.html
--rw-rw-rw-   0 root         (0) root         (0)      519 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/cabletemplate_edit_header.html
--rw-rw-rw-   0 root         (0) root         (0)      388 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/measurement_log_list.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.253608 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/trace/
--rw-rw-rw-   0 root         (0) root         (0)      150 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/trace/needed_cable.html
--rw-rw-rw-   0 root         (0) root         (0)      346 2022-10-07 09:54:00.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/undo_commission.html
--rw-rw-rw-   0 root         (0) root         (0)     1913 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/urls.py
--rw-rw-rw-   0 root         (0) root         (0)    18605 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils/views.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2022-10-07 17:32:07.209608 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/
--rw-r--r--   0 root         (0) root         (0)     4773 2022-10-07 17:32:07.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     2383 2022-10-07 17:32:07.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2022-10-07 17:32:07.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        1 2022-10-07 17:32:07.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)        9 2022-10-07 17:32:07.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       21 2022-10-07 17:32:07.000000 nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2022-10-07 17:32:07.257608 nautobot-cable-utils-0.7.0/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)      700 2022-10-07 17:31:58.000000 nautobot-cable-utils-0.7.0/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.438044 nautobot-cable-utils-0.8.0/
+-rw-rw-rw-   0 root         (0) root         (0)      608 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/LICENSE.txt
+-rw-rw-rw-   0 root         (0) root         (0)       93 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     4773 2022-11-07 16:34:18.438044 nautobot-cable-utils-0.8.0/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     4408 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.410044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/
+-rw-rw-rw-   0 root         (0) root         (0)      502 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      261 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/admin.py
+-rw-rw-rw-   0 root         (0) root         (0)    15580 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/cable_router.py
+-rw-rw-rw-   0 root         (0) root         (0)     1543 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/filters.py
+-rw-rw-rw-   0 root         (0) root         (0)    26979 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/forms.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.418044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/
+-rw-rw-rw-   0 root         (0) root         (0)     1751 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0001_initial.py
+-rw-rw-rw-   0 root         (0) root         (0)     1243 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0002_auto_20220808_0747.py
+-rw-rw-rw-   0 root         (0) root         (0)      383 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0003_rename_tenant_cabletemplate_owner.py
+-rw-rw-rw-   0 root         (0) root         (0)      403 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0004_rename_cable_number_cabletemplate_name.py
+-rw-rw-rw-   0 root         (0) root         (0)      439 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0005_alter_cabletemplate_name.py
+-rw-rw-rw-   0 root         (0) root         (0)        0 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1866 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/models.py
+-rw-rw-rw-   0 root         (0) root         (0)      932 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/navigation.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.398044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/static/
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.426044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/static/nautobot_cable_utils/
+-rw-rw-rw-   0 root         (0) root         (0)   348509 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/static/nautobot_cable_utils/html5-qrcode.min.js
+-rw-rw-rw-   0 root         (0) root         (0)     1411 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/static/nautobot_cable_utils/qr-scanner.js
+-rw-rw-rw-   0 root         (0) root         (0)     2451 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/tables.py
+-rw-rw-rw-   0 root         (0) root         (0)     1898 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/template_content.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.398044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.434044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/
+-rw-rw-rw-   0 root         (0) root         (0)     2036 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/bulk_commission.html
+-rw-rw-rw-   0 root         (0) root         (0)     6842 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_connect.html
+-rw-rw-rw-   0 root         (0) root         (0)     5443 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_add.html
+-rw-rw-rw-   0 root         (0) root         (0)     2220 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_verify.html
+-rw-rw-rw-   0 root         (0) root         (0)      386 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_template_list.html
+-rw-rw-rw-   0 root         (0) root         (0)      979 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_bulk_add.html
+-rw-rw-rw-   0 root         (0) root         (0)      520 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_edit.html
+-rw-rw-rw-   0 root         (0) root         (0)     1134 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/commission_cable.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.438044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/
+-rw-rw-rw-   0 root         (0) root         (0)      797 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons.html
+-rw-rw-rw-   0 root         (0) root         (0)      235 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_device.html
+-rw-rw-rw-   0 root         (0) root         (0)      782 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_frontport.html
+-rw-rw-rw-   0 root         (0) root         (0)      780 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_interface.html
+-rw-rw-rw-   0 root         (0) root         (0)      519 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/cabletemplate_edit_header.html
+-rw-rw-rw-   0 root         (0) root         (0)      388 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/measurement_log_list.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.438044 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/trace/
+-rw-rw-rw-   0 root         (0) root         (0)      150 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/trace/needed_cable.html
+-rw-rw-rw-   0 root         (0) root         (0)      346 2022-08-08 10:11:48.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/undo_commission.html
+-rw-rw-rw-   0 root         (0) root         (0)     1913 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/urls.py
+-rw-rw-rw-   0 root         (0) root         (0)    18605 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils/views.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2022-11-07 16:34:18.410044 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     4773 2022-11-07 16:34:18.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     2383 2022-11-07 16:34:18.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2022-11-07 16:34:18.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2022-11-07 16:34:18.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)        7 2022-11-07 16:34:18.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       21 2022-11-07 16:34:18.000000 nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2022-11-07 16:34:18.438044 nautobot-cable-utils-0.8.0/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)      698 2022-11-07 16:34:06.000000 nautobot-cable-utils-0.8.0/setup.py
```

### Comparing `nautobot-cable-utils-0.7.0/LICENSE.txt` & `nautobot-cable-utils-0.8.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/PKG-INFO` & `nautobot-cable-utils-0.8.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nautobot-cable-utils
-Version: 0.7.0
+Version: 0.8.0
 Summary: A Nautobot plugin for working with cables
 Home-page: https://gitlab-ce.gwdg.de/gwdg-netz/nautobot-plugins/nautobot-cable-utils/
 Author: Gesellschaft für wissenschaftliche Datenverarbeitung mbH Göttingen
 License: Apache-2.0
 Description-Content-Type: text/markdown
 License-File: LICENSE.txt
```

### Comparing `nautobot-cable-utils-0.7.0/README.md` & `nautobot-cable-utils-0.8.0/README.md`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/cable_router.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/cable_router.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,18 +1,34 @@
+import re
 from uuid import UUID
 
-from dijkstar import Graph, find_path, NoPathError
 from django.contrib.contenttypes.models import ContentType
 from django.forms import ValidationError
-from django.db.models import Count, Q
 
+from igraph import Graph
 from nautobot.dcim.choices import CableTypeChoices
 from nautobot.dcim.models import Device, FrontPort, RearPort, Rack, Cable
 
 
+def get_weight_for_frontport_name(fp_name):
+    if "/" in fp_name:
+        [part_1, part_2] = fp_name.split("/")
+        part_1_match = re.search(r'\d+', part_1)
+        part_2_match = re.search(r'\d+', part_2)
+
+        part_1_num = int(part_1_match.group(0)) if part_1_match else 0
+        part_2_num = int(part_2_match.group(0)) if part_2_match else 0
+        return 10000 + (part_1_num * 1000) + part_2_num
+
+    else:
+        part_1_match = re.search(r'\d+', fp_name)
+        part_1_num = int(part_1_match.group(0)) if part_1_match else 0
+        return 10000 + part_1_num
+
+
 class CablePath:
     def __init__(self, termination_a, termination_a_type, termination_b, termination_b_type, cable_inp):
         self.termination_a = termination_a
         self.termination_b = termination_b
         self.termination_a_type = termination_a_type
         self.termination_b_type = termination_b_type
 
@@ -61,35 +77,36 @@
 
         if self.termination_a_type.app_label == "dcim" and self.termination_a_type.model == "interface":
             fp_to_interface_cable = needed_cables.pop(0)
 
             is_swapped = fp_to_interface_cable['termination_b'].device == open_element['device']
             intermediate_elements.append({
                 **open_element,
-                "attachment_b": fp_to_interface_cable['termination_b'] if is_swapped else fp_to_interface_cable['termination_a'],
+                "attachment_b": fp_to_interface_cable['termination_b'] if is_swapped else fp_to_interface_cable[
+                    'termination_a'],
             })
 
             intermediate_elements.append({
                 "needed_cable": fp_to_interface_cable,
             })
 
-            next_attachment_point = fp_to_interface_cable['termination_b'] if not is_swapped else fp_to_interface_cable['termination_a']
+            next_attachment_point = fp_to_interface_cable['termination_b'] if not is_swapped else fp_to_interface_cable[
+                'termination_a']
 
             open_element = {
                 "attachment_a": next_attachment_point,
                 "device": next_attachment_point.device,
             }
         elif self.termination_a_type.app_label == "dcim" and self.termination_a_type.model == "frontport":
             open_element["attachment_a"] = self.termination_a
 
         prepended_cable = None
         if self.termination_b_type.app_label == "dcim" and self.termination_b_type.model == "interface":
             prepended_cable = needed_cables.pop()
 
-
         for i, next_existing_cable in enumerate(cable_list):
 
             is_swapped = next_existing_cable.termination_b.device == open_element['device']
 
             open_element["attachment_b"] = next_existing_cable.termination_b if is_swapped else \
                 next_existing_cable.termination_a
 
@@ -135,24 +152,24 @@
                 "attachment_b": prepended_cable['termination_b'] if is_swapped else prepended_cable['termination_a'],
             })
 
             intermediate_elements.append({
                 "needed_cable": prepended_cable,
             })
 
-            next_attachment_point = prepended_cable['termination_b'] if not is_swapped else prepended_cable['termination_a']
+            next_attachment_point = prepended_cable['termination_b'] if not is_swapped else prepended_cable[
+                'termination_a']
 
             open_element = {
                 "attachment_a": next_attachment_point,
                 "device": next_attachment_point.device,
             }
         else:
             open_element["attachment_b"] = self.termination_b
 
-
         if open_element:
             intermediate_elements.append(open_element)
 
         return intermediate_elements
 
     def get_needed_cables(self):
 
@@ -203,23 +220,22 @@
                     "termination_b_type": ContentType.objects.get_for_model(self.termination_b),
                     "termination_b_id": self.termination_b.id,
                     "termination_b": self.termination_b
                 })
             else:
                 # Hop Rack
                 rack_devices = list(filter(lambda d: d.rack.id == rack.id, devices))
-                fp1_to_use = FrontPort.objects.filter(cable=None, device=rack_devices[0],
-                                                      rear_port__in=rearport_uuids).first()
-                fp2_to_use = FrontPort.objects.filter(cable=None, device=rack_devices[1],
-                                                      rear_port__in=rearport_uuids).first()
-
-                if not fp1_to_use:
-                    raise ValidationError(f"{rack_devices[0]} has no free ports.")
-                if not fp2_to_use:
-                    raise ValidationError(f"{rack_devices[1]} has no free ports.")
+                fps_to_use = FrontPort.objects.filter(cable=None, device__in=rack_devices,
+                                                      rear_port__in=rearport_uuids)
+
+                if len(fps_to_use) != 2:
+                    raise ValidationError(f"{' or '.join(rack_devices)} have no free ports.")
+
+                fp1_to_use = fps_to_use[0]
+                fp2_to_use = fps_to_use[1]
 
                 needed_cables.append({
                     "termination_a_type": ContentType.objects.get_for_model(fp1_to_use),
                     "termination_a_id": fp1_to_use.id,
                     "termination_a": fp1_to_use,
                     "termination_b_type": ContentType.objects.get_for_model(fp2_to_use),
                     "termination_b_id": fp2_to_use.id,
@@ -272,15 +288,18 @@
             rps_to_exclude = RearPort.objects.filter(device=self.termination_b.device)
             for rp in rps_to_exclude:
                 if termination_b.rear_port != rp and rp.cable:
                     excluded_cable_ids.append(rp.cable.id)
 
         possible_edges = Cable.objects.raw(
             '''
-                SELECT c.*, d_a.rack_id as termination_a_rack_id, d_b.rack_id as termination_b_rack_id FROM dcim_cable c
+                SELECT 
+                    c.*, d_a.rack_id as termination_a_rack_id, d_b.rack_id as termination_b_rack_id, 
+                    fp_a.name as termination_a_name, fp_b.name as termination_b_name 
+                FROM dcim_cable c
                 LEFT JOIN django_content_type ct_a ON ct_a.id = termination_a_type_id
                 LEFT JOIN django_content_type ct_b ON ct_b.id = termination_b_type_id
                 LEFT JOIN dcim_rearport rp_a ON rp_a.id = termination_a_id
                 LEFT JOIN dcim_rearport rp_b ON rp_b.id = termination_b_id
                 INNER JOIN dcim_frontport fp_a ON fp_a.rear_port_id = rp_a.id AND fp_a.cable_id IS NULL
                 INNER JOIN dcim_frontport fp_b ON fp_b.rear_port_id = rp_b.id AND fp_b.cable_id IS NULL
                 LEFT JOIN dcim_device d_a ON rp_a.device_id = d_a.id
@@ -293,33 +312,57 @@
                     fp_a.cable_id IS NULL and fp_b.cable_id IS NULL
                 )
             ''',
             [self.allowed_cable_types, excluded_cable_ids]
         )
 
         self.graph = Graph()
+        self.edges = dict()
+
+        verticies = set(str(x) for e in possible_edges for x in [e.termination_a_rack_id, e.termination_b_rack_id])
+        for v in verticies:
+            self.graph.add_vertex(v)
+
         for edge in possible_edges:
-            self.graph.add_edge(edge.termination_a_rack_id, edge.termination_b_rack_id, edge.id)
-            self.graph.add_edge(edge.termination_b_rack_id, edge.termination_a_rack_id, edge.id)
+            fp_a_weight = get_weight_for_frontport_name(edge.termination_a_name)
+            fp_b_weight = get_weight_for_frontport_name(edge.termination_b_name)
+
+            if not edge.termination_a_rack_id or not edge.termination_b_rack_id:
+                continue
+
+            e_to = self.graph.add_edge(
+                str(edge.termination_a_rack_id),
+                str(edge.termination_b_rack_id),
+                weight=fp_a_weight,
+            )
+            self.edges[e_to.index] = edge.id
+            e_from = self.graph.add_edge(
+                str(edge.termination_b_rack_id),
+                str(edge.termination_a_rack_id),
+                weight=fp_b_weight,
+                id=edge.id
+            )
+            self.edges[e_from.index] = edge.id
 
     def get_devices_for_hop_list(self, hop_list):
         devices = Device.objects.filter(id__in=hop_list)
         return list(map(lambda h: next(filter(lambda d: d.id == h, devices)), hop_list))
 
     def get_path(self):
 
         if self.termination_a.device.rack.id == self.termination_b.device.rack.id:
             raise ValidationError(
                 f"{self.termination_a.device} and {self.termination_b.device} are located within the same rack")
 
-        try:
-            path = find_path(
-                self.graph,
-                self.termination_a.device.rack.id,
-                self.termination_b.device.rack.id,
-                cost_func=lambda a, b, c, d: 1
-            )
-        except NoPathError:
+        shortest_path = self.graph.get_shortest_paths(
+            str(self.termination_a.device.rack.id),
+            str(self.termination_b.device.rack.id),
+            weights="weight",
+            output="epath",
+        )
+
+        if len(shortest_path) < 1:
             raise ValidationError(
-                f"No path available between {self.termination_a.device} and {self.termination_b.device}")
+                f"{self.termination_a.device} and {self.termination_b.device} are not connected"
+            )
 
-        return path.edges
+        return [self.edges[x] for x in shortest_path[0]]
```

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/filters.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/filters.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/forms.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/forms.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0001_initial.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/migrations/0002_auto_20220808_0747.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/migrations/0002_auto_20220808_0747.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/models.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/models.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/navigation.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/navigation.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/static/nautobot_cable_utils/html5-qrcode.min.js` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/static/nautobot_cable_utils/html5-qrcode.min.js`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/static/nautobot_cable_utils/qr-scanner.js` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/static/nautobot_cable_utils/qr-scanner.js`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/tables.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/tables.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/template_content.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/template_content.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/bulk_commission.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/bulk_commission.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_connect.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_connect.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_add.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_add.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_verify.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cable_router_verify.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_bulk_add.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_bulk_add.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_edit.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/cabletemplate_edit.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/commission_cable.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/commission_cable.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_frontport.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_frontport.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_interface.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/buttons_interface.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/cabletemplate_edit_header.html` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/templates/nautobot_cable_utils/inc/cabletemplate_edit_header.html`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/urls.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/urls.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils/views.py` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils/views.py`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/PKG-INFO` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nautobot-cable-utils
-Version: 0.7.0
+Version: 0.8.0
 Summary: A Nautobot plugin for working with cables
 Home-page: https://gitlab-ce.gwdg.de/gwdg-netz/nautobot-plugins/nautobot-cable-utils/
 Author: Gesellschaft für wissenschaftliche Datenverarbeitung mbH Göttingen
 License: Apache-2.0
 Description-Content-Type: text/markdown
 License-File: LICENSE.txt
```

### Comparing `nautobot-cable-utils-0.7.0/nautobot_cable_utils.egg-info/SOURCES.txt` & `nautobot-cable-utils-0.8.0/nautobot_cable_utils.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `nautobot-cable-utils-0.7.0/setup.py` & `nautobot-cable-utils-0.8.0/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -4,21 +4,21 @@
 
 with open('README.md', encoding="utf-8") as f:
     long_description = f.read()
 
 setup(
     name='nautobot-cable-utils',
     author='Gesellschaft für wissenschaftliche Datenverarbeitung mbH Göttingen',
-    version='0.7.0',
+    version='0.8.0',
     license='Apache-2.0',
     url='https://gitlab-ce.gwdg.de/gwdg-netz/nautobot-plugins/nautobot-cable-utils/',
     description='A Nautobot plugin for working with cables',
     long_description=long_description,
     long_description_content_type="text/markdown",
     packages=find_packages('.'),
     include_package_data=True,
     install_requires=[
-        "dijkstar"
+        "igraph"
     ],
     zip_safe=False,
 )
```


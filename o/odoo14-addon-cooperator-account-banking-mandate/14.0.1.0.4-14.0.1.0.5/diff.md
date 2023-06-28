# Comparing `tmp/odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4.tar.gz` & `tmp/odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4.tar", last modified: Wed Jun 28 15:32:27 2023, max compression
+gzip compressed data, was "odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5.tar", last modified: Wed Jun 28 15:35:28 2023, max compression
```

## Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4.tar` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      433 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/PKG-INFO
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.526055 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.526055 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.530053 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       46 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/__init__.py
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      543 2023-06-28 15:32:06.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/__manifest__.py
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.530053 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       60 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/__init__.py
--rw-rw-r--   0 daniil    (1000) daniil    (1000)     2409 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.530053 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      956 2023-06-28 15:25:24.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml
-drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      433 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/PKG-INFO
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      782 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/dependency_links.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/not-zip-safe
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      181 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/requires.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)        5 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/top_level.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       38 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/setup.cfg
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      240 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/setup.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.325059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      433 2023-06-28 15:35:28.325059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/PKG-INFO
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.317060 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.317060 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.321059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       46 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/__init__.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      543 2023-06-28 15:34:58.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/__manifest__.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.321059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/models/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       60 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/models/__init__.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)     2409 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.321059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/views/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      956 2023-06-28 15:25:24.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:35:28.325059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      433 2023-06-28 15:35:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/PKG-INFO
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      782 2023-06-28 15:35:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:35:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/dependency_links.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:35:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/not-zip-safe
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      181 2023-06-28 15:35:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/requires.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        5 2023-06-28 15:35:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/top_level.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       38 2023-06-28 15:35:28.325059 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/setup.cfg
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      240 2023-06-28 15:34:38.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/setup.py
```

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/__manifest__.py` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/__manifest__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 # -*- coding: utf-8 -*-
 {
     "name": "Cooperator Account Banking Mandate",
-    "version": "14.0.1.0.4",
+    "version": "14.0.1.0.5",
     "license": "AGPL-3",
     "summary": """
         This module adds mandate selection to cooperator subscription request.""",
     "author": "Som IT Cooperatiu SCCL",
     "category": "Banking addons",
     "depends": ["cooperator", "cooperator_account_payment", "account_banking_mandate",
                 "account_banking_sepa_direct_debit"],
```

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py`

 * *Files identical despite different names*

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml`

 * *Files identical despite different names*

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.5/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt`

 * *Files identical despite different names*


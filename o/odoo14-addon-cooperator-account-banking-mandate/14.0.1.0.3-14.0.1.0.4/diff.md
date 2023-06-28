# Comparing `tmp/odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3.tar.gz` & `tmp/odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3.tar", last modified: Thu Jun 22 15:44:27 2023, max compression
+gzip compressed data, was "odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4.tar", last modified: Wed Jun 28 15:32:27 2023, max compression
```

## Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3.tar` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.464319 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/
--rw-r--r--   0 enrico    (1000) enrico    (1000)      491 2023-06-22 15:44:27.464319 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/PKG-INFO
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.460986 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.460986 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.460986 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/
--rw-r--r--   0 enrico    (1000) enrico    (1000)       46 2023-06-19 10:18:40.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/__init__.py
--rw-r--r--   0 enrico    (1000) enrico    (1000)      543 2023-06-22 15:43:05.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/__manifest__.py
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.464319 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/models/
--rw-r--r--   0 enrico    (1000) enrico    (1000)       60 2023-06-19 10:18:40.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/models/__init__.py
--rw-r--r--   0 enrico    (1000) enrico    (1000)     2409 2023-06-19 10:18:40.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.464319 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/views/
--rw-r--r--   0 enrico    (1000) enrico    (1000)      956 2023-06-19 10:18:40.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml
-drwxr-xr-x   0 enrico    (1000) enrico    (1000)        0 2023-06-22 15:44:27.464319 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/
--rw-r--r--   0 enrico    (1000) enrico    (1000)      491 2023-06-22 15:44:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/PKG-INFO
--rw-r--r--   0 enrico    (1000) enrico    (1000)      782 2023-06-22 15:44:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt
--rw-r--r--   0 enrico    (1000) enrico    (1000)        1 2023-06-22 15:44:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/dependency_links.txt
--rw-r--r--   0 enrico    (1000) enrico    (1000)        1 2023-06-22 11:53:02.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/not-zip-safe
--rw-r--r--   0 enrico    (1000) enrico    (1000)      181 2023-06-22 15:44:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/requires.txt
--rw-r--r--   0 enrico    (1000) enrico    (1000)        5 2023-06-22 15:44:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/top_level.txt
--rw-r--r--   0 enrico    (1000) enrico    (1000)       38 2023-06-22 15:44:27.464319 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/setup.cfg
--rw-r--r--   0 enrico    (1000) enrico    (1000)      240 2023-06-19 10:18:40.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/setup.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      433 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/PKG-INFO
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.526055 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.526055 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.530053 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       46 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/__init__.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      543 2023-06-28 15:32:06.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/__manifest__.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.530053 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       60 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/__init__.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)     2409 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.530053 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      956 2023-06-28 15:25:24.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      433 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/PKG-INFO
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      782 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/dependency_links.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/not-zip-safe
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      181 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/requires.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        5 2023-06-28 15:32:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/top_level.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       38 2023-06-28 15:32:27.534052 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/setup.cfg
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      240 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/setup.py
```

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/__manifest__.py` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/__manifest__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 # -*- coding: utf-8 -*-
 {
     "name": "Cooperator Account Banking Mandate",
-    "version": "14.0.1.0.3",
+    "version": "14.0.1.0.4",
     "license": "AGPL-3",
     "summary": """
         This module adds mandate selection to cooperator subscription request.""",
     "author": "Som IT Cooperatiu SCCL",
     "category": "Banking addons",
     "depends": ["cooperator", "cooperator_account_payment", "account_banking_mandate",
                 "account_banking_sepa_direct_debit"],
```

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/models/subscription_request.py`

 * *Files identical despite different names*

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml`

 * *Files 19% similar despite different names*

#### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo/addons/cooperator_account_banking_mandate/views/subscription_request_views.xml`

```diff
@@ -1,14 +1,14 @@
 <?xml version="1.0" encoding="utf-8"?>
 <odoo>
   <data>
     <record id="subscription_request_form_inherit" model="ir.ui.view">
-      <field name="name">account_banking_mandate_cooperator.subscription_request.form</field>
+      <field name="name">cooperator_account_banking_mandate.subscription_request.form</field>
       <field name="model">subscription.request</field>
-      <field name="inherit_id" ref="account_payment_cooperator.subscription_request_form_inherit"/>
+      <field name="inherit_id" ref="cooperator_account_payment.subscription_request_form_inherit"/>
       <field name="priority" eval="8"/>
       <field name="arch" type="xml">
         <xpath expr="//field[@name='payment_mode_id']" position="after">
           <field name="mandate_id" attrs="{'invisible': [('mandate_required', '=', False)]}"/>
           <field name="mandate_required" invisible="1"/>
           <field name="mandate_approved"/>
         </xpath>
```

### Comparing `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.3/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt` & `odoo14-addon-cooperator_account_banking_mandate-14.0.1.0.4/odoo14_addon_cooperator_account_banking_mandate.egg-info/SOURCES.txt`

 * *Files identical despite different names*


# Comparing `tmp/odoo14-addon-cooperator_account_payment-14.0.1.0.1.tar.gz` & `tmp/odoo14-addon-cooperator_account_payment-14.0.1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "odoo14-addon-cooperator_account_payment-14.0.1.0.1.tar", last modified: Wed Jun 14 08:20:38 2023, max compression
+gzip compressed data, was "odoo14-addon-cooperator_account_payment-14.0.1.0.2.tar", last modified: Wed Jun 28 15:30:20 2023, max compression
```

## Comparing `odoo14-addon-cooperator_account_payment-14.0.1.0.1.tar` & `odoo14-addon-cooperator_account_payment-14.0.1.0.2.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.412751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      411 2023-06-14 08:20:38.412751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/PKG-INFO
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.408751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.408751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.408751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       46 2023-06-14 08:16:02.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/__init__.py
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      482 2023-06-14 08:17:53.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/__manifest__.py
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.408751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/models/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       91 2023-06-14 08:16:02.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/models/__init__.py
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      282 2023-06-14 08:16:02.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/models/product_template.py
--rw-rw-r--   0 daniil    (1000) daniil    (1000)     1359 2023-06-14 08:16:02.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/models/subscription_request.py
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.408751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/views/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      655 2023-06-14 08:16:02.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/views/product_template_views.xml
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      667 2023-06-14 08:16:02.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/views/subscription_request_views.xml
-drwxrwxr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-14 08:20:38.408751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      411 2023-06-14 08:20:38.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/PKG-INFO
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      832 2023-06-14 08:20:38.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/SOURCES.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-14 08:20:38.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/dependency_links.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-14 08:20:38.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/not-zip-safe
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       82 2023-06-14 08:20:38.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/requires.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)        5 2023-06-14 08:20:38.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/top_level.txt
--rw-rw-r--   0 daniil    (1000) daniil    (1000)       38 2023-06-14 08:20:38.412751 odoo14-addon-cooperator_account_payment-14.0.1.0.1/setup.cfg
--rw-rw-r--   0 daniil    (1000) daniil    (1000)      100 2023-06-14 08:19:46.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.1/setup.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.029404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      411 2023-06-28 15:30:20.029404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/PKG-INFO
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.017403 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.017403 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.021404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       46 2023-06-23 14:31:37.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/__init__.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      482 2023-06-28 15:28:25.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/__manifest__.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.021404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/models/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       91 2023-06-23 14:31:27.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/models/__init__.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      282 2023-06-23 14:31:37.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/models/product_template.py
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)     1359 2023-06-23 14:31:37.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/models/subscription_request.py
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.021404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/views/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      655 2023-06-23 14:31:37.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/views/product_template_views.xml
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      668 2023-06-28 15:25:24.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/views/subscription_request_views.xml
+drwxrwsr-x   0 daniil    (1000) daniil    (1000)        0 2023-06-28 15:30:20.025404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      411 2023-06-28 15:30:19.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/PKG-INFO
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      832 2023-06-28 15:30:19.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/SOURCES.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:30:19.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/dependency_links.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        1 2023-06-28 15:30:19.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/not-zip-safe
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       82 2023-06-28 15:30:19.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/requires.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)        5 2023-06-28 15:30:19.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/top_level.txt
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)       38 2023-06-28 15:30:20.029404 odoo14-addon-cooperator_account_payment-14.0.1.0.2/setup.cfg
+-rw-rw-r--   0 daniil    (1000) daniil    (1000)      100 2023-06-23 14:29:27.000000 odoo14-addon-cooperator_account_payment-14.0.1.0.2/setup.py
```

### Comparing `odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/models/subscription_request.py` & `odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/models/subscription_request.py`

 * *Files identical despite different names*

### Comparing `odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/views/product_template_views.xml` & `odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/views/product_template_views.xml`

 * *Files identical despite different names*

### Comparing `odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/views/subscription_request_views.xml` & `odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/views/subscription_request_views.xml`

 * *Files 4% similar despite different names*

#### Comparing `odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo/addons/cooperator_account_payment/views/subscription_request_views.xml` & `odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo/addons/cooperator_account_payment/views/subscription_request_views.xml`

```diff
@@ -1,12 +1,12 @@
 <?xml version="1.0" encoding="utf-8"?>
 <odoo>
   <data>
     <record id="subscription_request_form_inherit" model="ir.ui.view">
-      <field name="name">account_payment_cooperator.subscription_request.form</field>
+      <field name="name">cooperator_account_payment.subscription_request.form</field>
       <field name="model">subscription.request</field>
       <field name="inherit_id" ref="cooperator.subscription_request_view_form"/>
       <field name="priority" eval="8"/>
       <field name="arch" type="xml">
         <xpath expr="//field[@name='iban']" position="after">
           <field name="payment_mode_id"/>
         </xpath>
```

### Comparing `odoo14-addon-cooperator_account_payment-14.0.1.0.1/odoo14_addon_cooperator_account_payment.egg-info/SOURCES.txt` & `odoo14-addon-cooperator_account_payment-14.0.1.0.2/odoo14_addon_cooperator_account_payment.egg-info/SOURCES.txt`

 * *Files identical despite different names*


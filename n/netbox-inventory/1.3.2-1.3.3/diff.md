# Comparing `tmp/netbox-inventory-1.3.2.tar.gz` & `tmp/netbox-inventory-1.3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "netbox-inventory-1.3.2.tar", last modified: Thu Jun  8 13:24:25 2023, max compression
+gzip compressed data, was "netbox-inventory-1.3.3.tar", last modified: Wed Jun 28 05:58:31 2023, max compression
```

## Comparing `netbox-inventory-1.3.2.tar` & `netbox-inventory-1.3.3.tar`

### file list

```diff
@@ -1,109 +1,109 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.694632 netbox-inventory-1.3.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     9109 2023-06-08 13:24:25.694632 netbox-inventory-1.3.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     8531 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.682631 netbox-inventory-1.3.2/netbox_inventory/
--rw-r--r--   0 runner    (1001) docker     (123)     1165 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4295 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/analyzers.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.686632 netbox-inventory-1.3.2/netbox_inventory/api/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/api/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/api/nested_serializers.py
--rw-r--r--   0 runner    (1001) docker     (123)     4889 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/api/serializers.py
--rw-r--r--   0 runner    (1001) docker     (123)      633 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/api/urls.py
--rw-r--r--   0 runner    (1001) docker     (123)     2518 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/api/views.py
--rw-r--r--   0 runner    (1001) docker     (123)      406 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/choices.py
--rw-r--r--   0 runner    (1001) docker     (123)    10863 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/filtersets.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.686632 netbox-inventory-1.3.2/netbox_inventory/forms/
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6542 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/assign.py
--rw-r--r--   0 runner    (1001) docker     (123)    17795 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/bulk.py
--rw-r--r--   0 runner    (1001) docker     (123)      626 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/bulk_add.py
--rw-r--r--   0 runner    (1001) docker     (123)     4829 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/create.py
--rw-r--r--   0 runner    (1001) docker     (123)     9137 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/filters.py
--rw-r--r--   0 runner    (1001) docker     (123)     7620 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/models.py
--rw-r--r--   0 runner    (1001) docker     (123)     8502 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/forms/reassign.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.686632 netbox-inventory-1.3.2/netbox_inventory/migrations/
--rw-r--r--   0 runner    (1001) docker     (123)     6962 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/migrations/0001_initial_prod.py
--rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/migrations/0002_alter_asset_serial.py
--rw-r--r--   0 runner    (1001) docker     (123)     1523 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/migrations/0003_add_inventoryitemgroup.py
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/migrations/0004_inventoryitemgroup_tree.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/migrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16286 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/models.py
--rw-r--r--   0 runner    (1001) docker     (123)     3929 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/navigation.py
--rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/search.py
--rw-r--r--   0 runner    (1001) docker     (123)     2392 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/signals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11975 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tables.py
--rw-r--r--   0 runner    (1001) docker     (123)     4826 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/template_content.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.682631 netbox-inventory-1.3.2/netbox_inventory/templates/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/
--rw-r--r--   0 runner    (1001) docker     (123)     7657 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset.html
--rw-r--r--   0 runner    (1001) docker     (123)      479 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_assign.html
--rw-r--r--   0 runner    (1001) docker     (123)      402 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_bulk_add.html
--rw-r--r--   0 runner    (1001) docker     (123)     3172 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_bulk_import.html
--rw-r--r--   0 runner    (1001) docker     (123)      366 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_create.html
--rw-r--r--   0 runner    (1001) docker     (123)     3918 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_edit.html
--rw-r--r--   0 runner    (1001) docker     (123)      599 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_reassign.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/
--rw-r--r--   0 runner    (1001) docker     (123)      632 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_edit_header.html
--rw-r--r--   0 runner    (1001) docker     (123)     2002 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_info.html
--rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_stats_counts.html
--rw-r--r--   0 runner    (1001) docker     (123)      726 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_warranty.html
--rw-r--r--   0 runner    (1001) docker     (123)     5288 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inventoryitemgroup.html
--rw-r--r--   0 runner    (1001) docker     (123)     2263 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inventoryitemtype.html
--rw-r--r--   0 runner    (1001) docker     (123)     2450 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/purchase.html
--rw-r--r--   0 runner    (1001) docker     (123)     2315 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/supplier.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/
--rw-r--r--   0 runner    (1001) docker     (123)     2601 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_base.html
--rw-r--r--   0 runner    (1001) docker     (123)     1276 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_location.html
--rw-r--r--   0 runner    (1001) docker     (123)     1131 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_rack.html
--rw-r--r--   0 runner    (1001) docker     (123)     1253 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_site.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/tests/asset/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/asset/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5972 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     6099 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_models.py
--rw-r--r--   0 runner    (1001) docker     (123)     5134 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_views.py
--rw-r--r--   0 runner    (1001) docker     (123)     7772 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_views_create.py
--rw-r--r--   0 runner    (1001) docker     (123)    11228 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_views_reassign.py
--rw-r--r--   0 runner    (1001) docker     (123)     1304 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/custom.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_group/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_group/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1008 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_group/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1157 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_group/test_views.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_type/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_type/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1819 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_type/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     2195 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_type/test_views.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/tests/purchase/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/purchase/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/purchase/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1797 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/purchase/test_views.py
--rw-r--r--   0 runner    (1001) docker     (123)      539 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/settings.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.690631 netbox-inventory-1.3.2/netbox_inventory/tests/supplier/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/supplier/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1112 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/supplier/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/supplier/test_views.py
--rw-r--r--   0 runner    (1001) docker     (123)      650 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/tests/test_load.py
--rw-r--r--   0 runner    (1001) docker     (123)     5968 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/urls.py
--rw-r--r--   0 runner    (1001) docker     (123)     6393 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.694632 netbox-inventory-1.3.2/netbox_inventory/views/
--rw-r--r--   0 runner    (1001) docker     (123)      244 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8792 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/asset.py
--rw-r--r--   0 runner    (1001) docker     (123)      683 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/asset_assign.py
--rw-r--r--   0 runner    (1001) docker     (123)     2078 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/asset_create.py
--rw-r--r--   0 runner    (1001) docker     (123)      817 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/asset_reassign.py
--rw-r--r--   0 runner    (1001) docker     (123)     5484 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/inventoryitem_group.py
--rw-r--r--   0 runner    (1001) docker     (123)     1959 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/inventoryitem_type.py
--rw-r--r--   0 runner    (1001) docker     (123)     1995 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/purchase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2448 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/supplier.py
--rw-r--r--   0 runner    (1001) docker     (123)     2044 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/netbox_inventory/views/tabs.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 13:24:25.686632 netbox-inventory-1.3.2/netbox_inventory.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     9109 2023-06-08 13:24:25.000000 netbox-inventory-1.3.2/netbox_inventory.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3928 2023-06-08 13:24:25.000000 netbox-inventory-1.3.2/netbox_inventory.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-08 13:24:25.000000 netbox-inventory-1.3.2/netbox_inventory.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-08 13:24:25.000000 netbox-inventory-1.3.2/netbox_inventory.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-08 13:24:16.000000 netbox-inventory-1.3.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-08 13:24:25.694632 netbox-inventory-1.3.2/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.410829 netbox-inventory-1.3.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     9368 2023-06-28 05:58:31.410829 netbox-inventory-1.3.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     8790 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.398828 netbox-inventory-1.3.3/netbox_inventory/
+-rw-r--r--   0 runner    (1001) docker     (123)     1215 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4295 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/analyzers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.398828 netbox-inventory-1.3.3/netbox_inventory/api/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/api/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/api/nested_serializers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4889 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/api/serializers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      633 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/api/urls.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2518 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/api/views.py
+-rw-r--r--   0 runner    (1001) docker     (123)      406 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/choices.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11092 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/filtersets.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.402829 netbox-inventory-1.3.3/netbox_inventory/forms/
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6542 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/assign.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17795 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/bulk.py
+-rw-r--r--   0 runner    (1001) docker     (123)      626 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/bulk_add.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4829 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9137 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/filters.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7620 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8502 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/forms/reassign.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.402829 netbox-inventory-1.3.3/netbox_inventory/migrations/
+-rw-r--r--   0 runner    (1001) docker     (123)     6962 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/migrations/0001_initial_prod.py
+-rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/migrations/0002_alter_asset_serial.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1523 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/migrations/0003_add_inventoryitemgroup.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/migrations/0004_inventoryitemgroup_tree.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/migrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16286 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3929 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/navigation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/search.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2392 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/signals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11975 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tables.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4826 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/template_content.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.394828 netbox-inventory-1.3.3/netbox_inventory/templates/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.402829 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/
+-rw-r--r--   0 runner    (1001) docker     (123)     7657 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset.html
+-rw-r--r--   0 runner    (1001) docker     (123)      479 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_assign.html
+-rw-r--r--   0 runner    (1001) docker     (123)      402 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_bulk_add.html
+-rw-r--r--   0 runner    (1001) docker     (123)     3172 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_bulk_import.html
+-rw-r--r--   0 runner    (1001) docker     (123)      366 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_create.html
+-rw-r--r--   0 runner    (1001) docker     (123)     3918 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_edit.html
+-rw-r--r--   0 runner    (1001) docker     (123)      599 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_reassign.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.402829 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/
+-rw-r--r--   0 runner    (1001) docker     (123)      632 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_edit_header.html
+-rw-r--r--   0 runner    (1001) docker     (123)     2002 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_info.html
+-rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_stats_counts.html
+-rw-r--r--   0 runner    (1001) docker     (123)      726 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_warranty.html
+-rw-r--r--   0 runner    (1001) docker     (123)     5288 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inventoryitemgroup.html
+-rw-r--r--   0 runner    (1001) docker     (123)     2263 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inventoryitemtype.html
+-rw-r--r--   0 runner    (1001) docker     (123)     2450 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/purchase.html
+-rw-r--r--   0 runner    (1001) docker     (123)     2315 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/supplier.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/
+-rw-r--r--   0 runner    (1001) docker     (123)     2601 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_base.html
+-rw-r--r--   0 runner    (1001) docker     (123)     1276 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_location.html
+-rw-r--r--   0 runner    (1001) docker     (123)     1131 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_rack.html
+-rw-r--r--   0 runner    (1001) docker     (123)     1253 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_site.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/tests/asset/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/asset/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5972 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6099 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5134 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_views.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7772 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_views_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11228 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_views_reassign.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1304 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/custom.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_group/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_group/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1008 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_group/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1157 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_group/test_views.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_type/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_type/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1819 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_type/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2195 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_type/test_views.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/tests/purchase/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/purchase/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/purchase/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1797 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/purchase/test_views.py
+-rw-r--r--   0 runner    (1001) docker     (123)      539 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/settings.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.406829 netbox-inventory-1.3.3/netbox_inventory/tests/supplier/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/supplier/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1112 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/supplier/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/supplier/test_views.py
+-rw-r--r--   0 runner    (1001) docker     (123)      650 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/tests/test_load.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5968 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/urls.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7021 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.410829 netbox-inventory-1.3.3/netbox_inventory/views/
+-rw-r--r--   0 runner    (1001) docker     (123)      244 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8792 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/asset.py
+-rw-r--r--   0 runner    (1001) docker     (123)      683 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/asset_assign.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2078 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/asset_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)      817 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/asset_reassign.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5484 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/inventoryitem_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1959 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/inventoryitem_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1995 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/purchase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2448 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/supplier.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2044 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/netbox_inventory/views/tabs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:58:31.398828 netbox-inventory-1.3.3/netbox_inventory.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     9368 2023-06-28 05:58:31.000000 netbox-inventory-1.3.3/netbox_inventory.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3928 2023-06-28 05:58:31.000000 netbox-inventory-1.3.3/netbox_inventory.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 05:58:31.000000 netbox-inventory-1.3.3/netbox_inventory.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 05:58:31.000000 netbox-inventory-1.3.3/netbox_inventory.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 05:58:21.000000 netbox-inventory-1.3.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 05:58:31.410829 netbox-inventory-1.3.3/setup.cfg
```

### Comparing `netbox-inventory-1.3.2/LICENSE` & `netbox-inventory-1.3.3/LICENSE`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/PKG-INFO` & `netbox-inventory-1.3.3/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,22 +1,7 @@
-Metadata-Version: 2.1
-Name: netbox-inventory
-Version: 1.3.2
-Summary: Inventory asset management in NetBox
-Author-email: Matej Vadnjal <matej.vadnjal@arnes.si>
-Project-URL: Homepage, https://github.com/ArnesSI/netbox-inventory/
-Project-URL: Bug Tracker, https://github.com/ArnesSI/netbox-inventory/issues/
-Keywords: netbox,netbox-plugin,inventory
-Classifier: Programming Language :: Python :: 3
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Operating System :: OS Independent
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 # NetBox Inventory Plugin
 
 A [Netbox](https://github.com/netbox-community/netbox) plugin for hardware inventory.
 
 ## Features
 
 Keep track of your hardware, whether it is installed or in storage. You can
@@ -165,14 +150,15 @@
 | `asset_import_create_purchase` | `False` | When importing assets, automatically create purchase (and supplier) if it doesn't exist |
 | `asset_import_create_device_type` | `False` | When importing a device type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_module_type` | `False` | When importing a module type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_inventoryitem_type` | `False` | When importing an inventory type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_tenant` | `False` | When importing an asset, with owner or tenant, automatically create tenant if it doesn't exist |
 | `asset_disable_editing_fields_for_tags` | `{}` | A dictionary of tags and fields that should be disabled for editing. This is useful if you want to prevent editing of certain fields for certain assets. The dictionary is in the form of `{tag: [field1, field2]}`. Example: `{'no-edit': ['serial_number', 'asset_tag']}`. This only affects the UI, the API can still be used to edit the fields. |
 | `asset_disable_deletion_for_tags` | `[]` | List of tags that will disable deletion of assets. This only affects the UI, not the API. |
+| `asset_custom_fields_search_filters` | `{}` | A dictionary of custom fields and lookup types that will be added to the search filters for assets. The dictionary is in the form of `{field: [lookup_type]}`. Example: `{'asset_mac': ['icontains', 'exact']}`. |
 | `prefill_asset_name_create_inventoryitem` | `False` | When hardware inventory item is created from an asset, prefill the InventoryItem name to match the asset name. |
 | `prefill_asset_tag_create_inventoryitem` | `False` | When hardware inventory item is created from an asset, prefill the tags to match the tags associated to the asset. |
 
 You can extend or define your own status choices for Asset, via [`FIELD_CHOICES`](https://docs.netbox.dev/en/stable/configuration/data-validation/#field_choices) setting in Netbox:
 
 ```
 FIELD_CHOICES = {
```

### Comparing `netbox-inventory-1.3.2/README.md` & `netbox-inventory-1.3.3/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,7 +1,22 @@
+Metadata-Version: 2.1
+Name: netbox-inventory
+Version: 1.3.3
+Summary: Inventory asset management in NetBox
+Author-email: Matej Vadnjal <matej.vadnjal@arnes.si>
+Project-URL: Homepage, https://github.com/ArnesSI/netbox-inventory/
+Project-URL: Bug Tracker, https://github.com/ArnesSI/netbox-inventory/issues/
+Keywords: netbox,netbox-plugin,inventory
+Classifier: Programming Language :: Python :: 3
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Operating System :: OS Independent
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 # NetBox Inventory Plugin
 
 A [Netbox](https://github.com/netbox-community/netbox) plugin for hardware inventory.
 
 ## Features
 
 Keep track of your hardware, whether it is installed or in storage. You can
@@ -150,14 +165,15 @@
 | `asset_import_create_purchase` | `False` | When importing assets, automatically create purchase (and supplier) if it doesn't exist |
 | `asset_import_create_device_type` | `False` | When importing a device type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_module_type` | `False` | When importing a module type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_inventoryitem_type` | `False` | When importing an inventory type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_tenant` | `False` | When importing an asset, with owner or tenant, automatically create tenant if it doesn't exist |
 | `asset_disable_editing_fields_for_tags` | `{}` | A dictionary of tags and fields that should be disabled for editing. This is useful if you want to prevent editing of certain fields for certain assets. The dictionary is in the form of `{tag: [field1, field2]}`. Example: `{'no-edit': ['serial_number', 'asset_tag']}`. This only affects the UI, the API can still be used to edit the fields. |
 | `asset_disable_deletion_for_tags` | `[]` | List of tags that will disable deletion of assets. This only affects the UI, not the API. |
+| `asset_custom_fields_search_filters` | `{}` | A dictionary of custom fields and lookup types that will be added to the search filters for assets. The dictionary is in the form of `{field: [lookup_type]}`. Example: `{'asset_mac': ['icontains', 'exact']}`. |
 | `prefill_asset_name_create_inventoryitem` | `False` | When hardware inventory item is created from an asset, prefill the InventoryItem name to match the asset name. |
 | `prefill_asset_tag_create_inventoryitem` | `False` | When hardware inventory item is created from an asset, prefill the tags to match the tags associated to the asset. |
 
 You can extend or define your own status choices for Asset, via [`FIELD_CHOICES`](https://docs.netbox.dev/en/stable/configuration/data-validation/#field_choices) setting in Netbox:
 
 ```
 FIELD_CHOICES = {
```

### Comparing `netbox-inventory-1.3.2/netbox_inventory/__init__.py` & `netbox-inventory-1.3.3/netbox_inventory/__init__.py`

 * *Files 9% similar despite different names*

```diff
@@ -6,27 +6,28 @@
     name = 'netbox_inventory'
     verbose_name = 'NetBox Inventory'
     version = __version__
     description = 'Inventory asset management in NetBox'
     author = 'Matej Vadnjal'
     author_email = 'matej.vadnjal@arnes.si'
     base_url = 'inventory'
-    min_version = '3.5.0'
+    min_version = '3.5.2'
     default_settings = {
         'top_level_menu': True,
         'used_status_name': 'used',
         'stored_status_name': 'stored',
         'sync_hardware_serial_asset_tag': False,
         'asset_import_create_purchase': False,
         'asset_import_create_device_type': False,
         'asset_import_create_module_type': False,
         'asset_import_create_inventoryitem_type': False,
         'asset_import_create_tenant': False,
         'asset_disable_editing_fields_for_tags': {},
         'asset_disable_deletion_for_tags': [],
+        'asset_custom_fields_search_filters': {},
         'prefill_asset_name_create_inventoryitem': False,
         'prefill_asset_tag_create_inventoryitem': False,
     }
 
     def ready(self):
         super().ready()
         import netbox_inventory.signals
```

### Comparing `netbox-inventory-1.3.2/netbox_inventory/analyzers.py` & `netbox-inventory-1.3.3/netbox_inventory/analyzers.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/api/nested_serializers.py` & `netbox-inventory-1.3.3/netbox_inventory/api/nested_serializers.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/api/serializers.py` & `netbox-inventory-1.3.3/netbox_inventory/api/serializers.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/api/urls.py` & `netbox-inventory-1.3.3/netbox_inventory/api/urls.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/api/views.py` & `netbox-inventory-1.3.3/netbox_inventory/api/views.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/filtersets.py` & `netbox-inventory-1.3.3/netbox_inventory/filtersets.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 from dcim.models import Manufacturer, DeviceType, ModuleType, Site, Location
 from netbox.filtersets import NetBoxModelFilterSet
 from utilities import filters
 from tenancy.filtersets import ContactModelFilterSet
 from tenancy.models import Contact, Tenant
 from .choices import HardwareKindChoices, AssetStatusChoices
 from .models import Asset, InventoryItemType, InventoryItemGroup, Purchase, Supplier
-from .utils import query_located
+from .utils import query_located, get_asset_custom_fields_search_filters
 
 
 class AssetFilterSet(NetBoxModelFilterSet):
     status = django_filters.MultipleChoiceFilter(
         choices=AssetStatusChoices,
     )
     kind = filters.MultiValueCharFilter(
@@ -152,22 +152,26 @@
     )
 
     class Meta:
         model = Asset
         fields = ('id', 'name', 'serial', 'asset_tag')
 
     def search(self, queryset, name, value):
-        query = Q(
-            Q(serial__icontains=value)|
-            Q(name__icontains=value)|
-            Q(asset_tag__icontains=value)|
-            Q(device_type__model__icontains=value)|
-            Q(module_type__model__icontains=value)|
-            Q(inventoryitem_type__model__icontains=value)
+        query = (
+            Q(serial__icontains=value)
+            | Q(name__icontains=value)
+            | Q(asset_tag__icontains=value)
+            | Q(device_type__model__icontains=value)
+            | Q(module_type__model__icontains=value)
+            | Q(inventoryitem_type__model__icontains=value)
         )
+        custom_field_filters = get_asset_custom_fields_search_filters()
+        for custom_field_filter in custom_field_filters:
+            query |= Q(**{custom_field_filter: value})
+
         return queryset.filter(query)
 
     def filter_kind(self, queryset, name, value):
         query = None
         for kind in HardwareKindChoices.values():
             if kind in value:
                 q = Q(**{f'{kind}_type__isnull':False})
```

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/assign.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/assign.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/bulk.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/bulk.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/bulk_add.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/bulk_add.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/create.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/create.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/filters.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/filters.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/models.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/models.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/forms/reassign.py` & `netbox-inventory-1.3.3/netbox_inventory/forms/reassign.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/migrations/0001_initial_prod.py` & `netbox-inventory-1.3.3/netbox_inventory/migrations/0001_initial_prod.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/migrations/0003_add_inventoryitemgroup.py` & `netbox-inventory-1.3.3/netbox_inventory/migrations/0003_add_inventoryitemgroup.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/migrations/0004_inventoryitemgroup_tree.py` & `netbox-inventory-1.3.3/netbox_inventory/migrations/0004_inventoryitemgroup_tree.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/models.py` & `netbox-inventory-1.3.3/netbox_inventory/models.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/navigation.py` & `netbox-inventory-1.3.3/netbox_inventory/navigation.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/search.py` & `netbox-inventory-1.3.3/netbox_inventory/search.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/signals.py` & `netbox-inventory-1.3.3/netbox_inventory/signals.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tables.py` & `netbox-inventory-1.3.3/netbox_inventory/tables.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/template_content.py` & `netbox-inventory-1.3.3/netbox_inventory/template_content.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_bulk_import.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_bulk_import.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_edit.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_edit.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/asset_reassign.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/asset_reassign.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_edit_header.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_edit_header.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_info.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_info.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_stats_counts.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_stats_counts.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inc/asset_warranty.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inc/asset_warranty.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inventoryitemgroup.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inventoryitemgroup.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/inventoryitemtype.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/inventoryitemtype.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/purchase.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/purchase.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/supplier.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/supplier.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_base.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_base.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_location.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_location.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_rack.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_rack.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/templates/netbox_inventory/tabs/located_assets_site.html` & `netbox-inventory-1.3.3/netbox_inventory/templates/netbox_inventory/tabs/located_assets_site.html`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_api.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_api.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_models.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_models.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_views.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_views.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_views_create.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_views_create.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/asset/test_views_reassign.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/asset/test_views_reassign.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/custom.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/custom.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_group/test_api.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_group/test_api.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_group/test_views.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_group/test_views.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_type/test_api.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_type/test_api.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/inventoryitem_type/test_views.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/inventoryitem_type/test_views.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/purchase/test_api.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/purchase/test_api.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/purchase/test_views.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/purchase/test_views.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/settings.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/settings.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/supplier/test_api.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/supplier/test_api.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/supplier/test_views.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/supplier/test_views.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/tests/test_load.py` & `netbox-inventory-1.3.3/netbox_inventory/tests/test_load.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 
 class NetboxDnsVersionTestCase(SimpleTestCase):
     """
     Test for netbox_inventory package
     """
 
     def test_version(self):
-        assert __version__ == "1.3.2"
+        assert __version__ == "1.3.3"
 
 
 class AppTest(APITestCase):
     """
     Test the availability of the plugin API root
     """
```

### Comparing `netbox-inventory-1.3.2/netbox_inventory/urls.py` & `netbox-inventory-1.3.3/netbox_inventory/urls.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/utils.py` & `netbox-inventory-1.3.3/netbox_inventory/utils.py`

 * *Files 16% similar despite different names*

```diff
@@ -174,7 +174,25 @@
     elif assets_shown == 'installed':
         q = q_installed
     elif assets_shown == 'stored':
         q = q_stored
     else:
         raise Exception('unsupported')
     return queryset.filter(q)
+
+
+def get_asset_custom_fields_search_filters():
+    """Returns a list of custom field filter strings that can be used in Q() filter.
+
+    Custom fields and filters are used is defined in the plugin configuration,
+    under the key ``asset_custom_fields_search_filters``.
+
+    Returns:
+        list: list of custom field filter strings
+    """
+    custom_fields_filters = get_plugin_setting('asset_custom_fields_search_filters')
+
+    fields = []
+    for field_name, filters in custom_fields_filters.items():
+        for filter in filters:
+            fields.append(f"custom_field_data__{field_name}__{filter}")
+    return fields
```

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/asset.py` & `netbox-inventory-1.3.3/netbox_inventory/views/asset.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/asset_assign.py` & `netbox-inventory-1.3.3/netbox_inventory/views/asset_assign.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/asset_create.py` & `netbox-inventory-1.3.3/netbox_inventory/views/asset_create.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/asset_reassign.py` & `netbox-inventory-1.3.3/netbox_inventory/views/asset_reassign.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/inventoryitem_group.py` & `netbox-inventory-1.3.3/netbox_inventory/views/inventoryitem_group.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/inventoryitem_type.py` & `netbox-inventory-1.3.3/netbox_inventory/views/inventoryitem_type.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/purchase.py` & `netbox-inventory-1.3.3/netbox_inventory/views/purchase.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/supplier.py` & `netbox-inventory-1.3.3/netbox_inventory/views/supplier.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory/views/tabs.py` & `netbox-inventory-1.3.3/netbox_inventory/views/tabs.py`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/netbox_inventory.egg-info/PKG-INFO` & `netbox-inventory-1.3.3/netbox_inventory.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: netbox-inventory
-Version: 1.3.2
+Version: 1.3.3
 Summary: Inventory asset management in NetBox
 Author-email: Matej Vadnjal <matej.vadnjal@arnes.si>
 Project-URL: Homepage, https://github.com/ArnesSI/netbox-inventory/
 Project-URL: Bug Tracker, https://github.com/ArnesSI/netbox-inventory/issues/
 Keywords: netbox,netbox-plugin,inventory
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -165,14 +165,15 @@
 | `asset_import_create_purchase` | `False` | When importing assets, automatically create purchase (and supplier) if it doesn't exist |
 | `asset_import_create_device_type` | `False` | When importing a device type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_module_type` | `False` | When importing a module type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_inventoryitem_type` | `False` | When importing an inventory type asset, automatically create manufacturer and/or device type if it doesn't exist |
 | `asset_import_create_tenant` | `False` | When importing an asset, with owner or tenant, automatically create tenant if it doesn't exist |
 | `asset_disable_editing_fields_for_tags` | `{}` | A dictionary of tags and fields that should be disabled for editing. This is useful if you want to prevent editing of certain fields for certain assets. The dictionary is in the form of `{tag: [field1, field2]}`. Example: `{'no-edit': ['serial_number', 'asset_tag']}`. This only affects the UI, the API can still be used to edit the fields. |
 | `asset_disable_deletion_for_tags` | `[]` | List of tags that will disable deletion of assets. This only affects the UI, not the API. |
+| `asset_custom_fields_search_filters` | `{}` | A dictionary of custom fields and lookup types that will be added to the search filters for assets. The dictionary is in the form of `{field: [lookup_type]}`. Example: `{'asset_mac': ['icontains', 'exact']}`. |
 | `prefill_asset_name_create_inventoryitem` | `False` | When hardware inventory item is created from an asset, prefill the InventoryItem name to match the asset name. |
 | `prefill_asset_tag_create_inventoryitem` | `False` | When hardware inventory item is created from an asset, prefill the tags to match the tags associated to the asset. |
 
 You can extend or define your own status choices for Asset, via [`FIELD_CHOICES`](https://docs.netbox.dev/en/stable/configuration/data-validation/#field_choices) setting in Netbox:
 
 ```
 FIELD_CHOICES = {
```

### Comparing `netbox-inventory-1.3.2/netbox_inventory.egg-info/SOURCES.txt` & `netbox-inventory-1.3.3/netbox_inventory.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `netbox-inventory-1.3.2/pyproject.toml` & `netbox-inventory-1.3.3/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "netbox-inventory"
-version = "1.3.2"
+version = "1.3.3"
 authors = [
   { name="Matej Vadnjal", email="matej.vadnjal@arnes.si" },
 ]
 description = "Inventory asset management in NetBox"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```


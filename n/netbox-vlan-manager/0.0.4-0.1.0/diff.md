# Comparing `tmp/netbox-vlan-manager-0.0.4.tar.gz` & `tmp/netbox-vlan-manager-0.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "netbox-vlan-manager-0.0.4.tar", last modified: Sat Jun 10 06:33:32 2023, max compression
+gzip compressed data, was "netbox-vlan-manager-0.1.0.tar", last modified: Wed Jun 28 12:51:33 2023, max compression
```

## Comparing `netbox-vlan-manager-0.0.4.tar` & `netbox-vlan-manager-0.1.0.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1642 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1293 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/netbox_vlan_manager/
--rw-r--r--   0 runner    (1001) docker     (123)      400 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1665 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/serializers.py
--rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/urls.py
--rw-r--r--   0 runner    (1001) docker     (123)     1419 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/views.py
--rw-r--r--   0 runner    (1001) docker     (123)      576 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/forms.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/netbox_vlan_manager/migrations/
--rw-r--r--   0 runner    (1001) docker     (123)     1364 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/migrations/0001_initial.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/migrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1974 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/models.py
--rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/navigation.py
--rw-r--r--   0 runner    (1001) docker     (123)     2749 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/tables.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/netbox_vlan_manager/templatetags/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/templatetags/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/templatetags/view_helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1140 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/urls.py
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager/views.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1642 2023-06-10 06:33:32.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      807 2023-06-10 06:33:32.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-10 06:33:32.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-10 06:33:32.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-10 06:33:32.000000 netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-10 06:33:32.597244 netbox-vlan-manager-0.0.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-10 06:33:23.000000 netbox-vlan-manager-0.0.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2312 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1989 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/netbox_vlan_manager/
+-rw-r--r--   0 runner    (1001) docker     (123)      400 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1665 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/serializers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/urls.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1419 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/views.py
+-rw-r--r--   0 runner    (1001) docker     (123)      576 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/forms.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/netbox_vlan_manager/migrations/
+-rw-r--r--   0 runner    (1001) docker     (123)     1364 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/migrations/0001_initial.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/migrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1976 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/navigation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2749 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/tables.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/netbox_vlan_manager/templatetags/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/templatetags/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      216 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/templatetags/view_helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1140 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/urls.py
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2226 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager/views.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2312 2023-06-28 12:51:33.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      807 2023-06-28 12:51:33.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:51:33.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:51:33.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 12:51:33.000000 netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:51:33.876083 netbox-vlan-manager-0.1.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1206 2023-06-28 12:51:23.000000 netbox-vlan-manager-0.1.0/setup.py
```

### Comparing `netbox-vlan-manager-0.0.4/LICENSE` & `netbox-vlan-manager-0.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/PKG-INFO` & `netbox-vlan-manager-0.1.0/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,61 +1,86 @@
 Metadata-Version: 2.1
 Name: netbox-vlan-manager
-Version: 0.0.4
+Version: 0.1.0
 Summary: VLAN Manager for multiple VLAN Groups
 Home-page: https://github.com/miyuk/netbox-vlan-manager/
 Author: miyuk
 Author-email: miyuk@miyuk.net
-Classifier: Development Status :: 3 - Alpha
+Classifier: Development Status :: 4 - Beta
 Classifier: Framework :: Django
 Classifier: Programming Language :: Python :: 3
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # NetBox VLAN Manager
 
 NetBox plugin for viewer of multiple VLAN Group spaces.
 
 ![PyPI](https://img.shields.io/pypi/v/netbox-vlan-manager)
 ![publish PyPI workflow](https://github.com/miyuk/netbox-vlan-manager/actions/workflows/pub-pypi.yml/badge.svg)
 
+## Purpose
+
+Enterprise environment has a lot of routers or switches.
+These devices manage VLAN each other.
+
+In many cases, these manage as one VLAN group.
+On the other hand, complex network has multiple VLAN groups
+
+For example, below cases.
+
+- Manage multi site VLAN groups
+- Visualize Cisco ACI Leaf Switch VLANs
+
+NetBox can manage VLAN space as `VLAN Group`.
+However, it can one VLAN Group only.
+
+NetBox VLAN Manager manage multiple `VLAN Group` as `VLAN Group Set`, and visualize status in tabular form such as below image.
+
+![VLAN Group Set VLANs](https://raw.githubusercontent.com/miyuk/netbox-vlan-manager/main/docs/img/vlan_group_overview.png)
+
 ## Features
 
-This plugin provide following Models:
+### Models
+
+This plugin provides following Models:
 
 - VLAN Group Set
+  - Manage multiple VLAN Group
 
-## Compatibility
+### API
 
-Each Plugin Version listed below has been tested with its corresponding NetBox Version.
+This plugin provides following API:
+
+- Available VLAN
+  - Extract none used VID searching all VLAN Groups
+
+## Compatibility
 
-| NetBox Version | Plugin Version |
-| :------------: | :------------: |
-|      3.4       |     0.0.1      |
-|      3.5       |     0.0.4      |
+This plugin requires NetBox `v3.4.0` or later because has migration scripts compatibility.
 
 ## Installation
 
 The plugin is available as a Python package in PyPI and can be installed with pip:
 
 ```bash
 pip install netbox-vlan-manager
 ```
 
 Enable the plugin in /opt/netbox/netbox/netbox/configuration.py
 
 ```python
-PLUGINS = ['netbox-vlan-manager']
+PLUGINS = ['netbox_vlan_manager']
 ```
 
 Restart NetBox
 
 ## Configuration
 
-Currently, This plugin is not necessary plugin configuration
+Currently, this plugin is not necessary plugin configuration
 
 ## Screenshots
 
 VLAN Group Set List
 ![VLAN Group Set List](https://raw.githubusercontent.com/miyuk/netbox-vlan-manager/main/docs/img/vlan_group_set_list.png)
 
 VLAN Group View Set with VLANs
```

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/serializers.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/serializers.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/api/views.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/api/views.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/forms.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/forms.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/migrations/0001_initial.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/models.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/models.py`

 * *Files 1% similar despite different names*

```diff
@@ -47,15 +47,15 @@
 
         vlan_group_vlans = []
         for vid in range(self.min_vid, self.max_vid + 1):
             item = {}
             item['vid'] = vid
             vlans = [x for x in group_vlans if x.vid == vid]
             item['vlans'] = vlans
-            item['status'] = 'Available' if not vlans else 'In Use'
+            item['status'] = 'Available' if not vlans else 'Assigned'
             vlan_group_vlans.append(item)
         return vlan_group_vlans
 
     def get_available_vids(self):
         available_vlans = set([x['vid']
                                for x in self.vlans if x['status'] == 'Available'])
```

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/navigation.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/navigation.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/tables.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/tables.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/urls.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/urls.py`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager/views.py` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager/views.py`

 * *Files 16% similar despite different names*

```diff
@@ -7,22 +7,29 @@
 from .tables import VLANGroupSetVLANTable, VLANGroupSetTable
 
 
 class VLANGroupSetView(generic.ObjectView):
     queryset = VLANGroupSet.objects.all()
 
     def get_extra_context(self, request, instance):
+        show_available = bool(request.GET.get('show_available', 'true') == 'true')
+        show_assigned = bool(request.GET.get('show_assigned', 'true') == 'true')
         vlan_groups = instance.vlan_groups.all()
         vlan_group_vlans = instance.vlans
-        vlans_table = VLANGroupSetVLANTable(
-            vlan_group_vlans, vlan_groups=vlan_groups)
+        requested_vlans = [
+            x for x in vlan_group_vlans
+            if show_available and x['status'] == 'Available' or show_assigned and x['status'] == 'Assigned'
+        ]
+        vlans_table = VLANGroupSetVLANTable(requested_vlans, vlan_groups=vlan_groups)
         vlans_table.configure(request)
 
         return {
-            'vlans_table': vlans_table
+            'vlans_table': vlans_table,
+            'show_available': show_available,
+            'show_assigned': show_assigned,
         }
 
 
 class VLANGroupSetListView(generic.ObjectListView):
     queryset = VLANGroupSet.objects.annotate(
         vlan_group_count=Count('vlan_groups')
     )
```

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/PKG-INFO` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,61 +1,86 @@
 Metadata-Version: 2.1
 Name: netbox-vlan-manager
-Version: 0.0.4
+Version: 0.1.0
 Summary: VLAN Manager for multiple VLAN Groups
 Home-page: https://github.com/miyuk/netbox-vlan-manager/
 Author: miyuk
 Author-email: miyuk@miyuk.net
-Classifier: Development Status :: 3 - Alpha
+Classifier: Development Status :: 4 - Beta
 Classifier: Framework :: Django
 Classifier: Programming Language :: Python :: 3
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # NetBox VLAN Manager
 
 NetBox plugin for viewer of multiple VLAN Group spaces.
 
 ![PyPI](https://img.shields.io/pypi/v/netbox-vlan-manager)
 ![publish PyPI workflow](https://github.com/miyuk/netbox-vlan-manager/actions/workflows/pub-pypi.yml/badge.svg)
 
+## Purpose
+
+Enterprise environment has a lot of routers or switches.
+These devices manage VLAN each other.
+
+In many cases, these manage as one VLAN group.
+On the other hand, complex network has multiple VLAN groups
+
+For example, below cases.
+
+- Manage multi site VLAN groups
+- Visualize Cisco ACI Leaf Switch VLANs
+
+NetBox can manage VLAN space as `VLAN Group`.
+However, it can one VLAN Group only.
+
+NetBox VLAN Manager manage multiple `VLAN Group` as `VLAN Group Set`, and visualize status in tabular form such as below image.
+
+![VLAN Group Set VLANs](https://raw.githubusercontent.com/miyuk/netbox-vlan-manager/main/docs/img/vlan_group_overview.png)
+
 ## Features
 
-This plugin provide following Models:
+### Models
+
+This plugin provides following Models:
 
 - VLAN Group Set
+  - Manage multiple VLAN Group
 
-## Compatibility
+### API
 
-Each Plugin Version listed below has been tested with its corresponding NetBox Version.
+This plugin provides following API:
+
+- Available VLAN
+  - Extract none used VID searching all VLAN Groups
+
+## Compatibility
 
-| NetBox Version | Plugin Version |
-| :------------: | :------------: |
-|      3.4       |     0.0.1      |
-|      3.5       |     0.0.4      |
+This plugin requires NetBox `v3.4.0` or later because has migration scripts compatibility.
 
 ## Installation
 
 The plugin is available as a Python package in PyPI and can be installed with pip:
 
 ```bash
 pip install netbox-vlan-manager
 ```
 
 Enable the plugin in /opt/netbox/netbox/netbox/configuration.py
 
 ```python
-PLUGINS = ['netbox-vlan-manager']
+PLUGINS = ['netbox_vlan_manager']
 ```
 
 Restart NetBox
 
 ## Configuration
 
-Currently, This plugin is not necessary plugin configuration
+Currently, this plugin is not necessary plugin configuration
 
 ## Screenshots
 
 VLAN Group Set List
 ![VLAN Group Set List](https://raw.githubusercontent.com/miyuk/netbox-vlan-manager/main/docs/img/vlan_group_set_list.png)
 
 VLAN Group View Set with VLANs
```

### Comparing `netbox-vlan-manager-0.0.4/netbox_vlan_manager.egg-info/SOURCES.txt` & `netbox-vlan-manager-0.1.0/netbox_vlan_manager.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `netbox-vlan-manager-0.0.4/setup.py` & `netbox-vlan-manager-0.1.0/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -31,12 +31,12 @@
     author='miyuk',
     author_email='miyuk@miyuk.net',
     packages=find_packages(),
     include_package_data=True,
     install_requires=[],
     zip_safe=False,
     classifiers=[
-        'Development Status :: 3 - Alpha',
+        'Development Status :: 4 - Beta',
         'Framework :: Django',
         'Programming Language :: Python :: 3',
     ]
 )
```


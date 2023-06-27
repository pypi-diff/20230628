# Comparing `tmp/pulumi_vsphere-4.6.0a1687758153.tar.gz` & `tmp/pulumi_vsphere-4.6.0a1687903041.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pulumi_vsphere-4.6.0a1687758153.tar", last modified: Mon Jun 26 05:47:19 2023, max compression
+gzip compressed data, was "pulumi_vsphere-4.6.0a1687903041.tar", last modified: Tue Jun 27 22:02:13 2023, max compression
```

## Comparing `pulumi_vsphere-4.6.0a1687758153.tar` & `pulumi_vsphere-4.6.0a1687903041.tar`

### file list

```diff
@@ -1,87 +1,87 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 05:47:19.570671 pulumi_vsphere-4.6.0a1687758153/
--rw-r--r--   0 runner    (1001) docker     (123)     4868 2023-06-26 05:47:19.570671 pulumi_vsphere-4.6.0a1687758153/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4518 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 05:47:19.570671 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/
--rw-r--r--   0 runner    (1001) docker     (123)     9765 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    87225 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/_inputs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8081 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/_utilities.py
--rw-r--r--   0 runner    (1001) docker     (123)   237133 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster.py
--rw-r--r--   0 runner    (1001) docker     (123)    13437 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_host_group.py
--rw-r--r--   0 runner    (1001) docker     (123)    24459 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_affinity_rule.py
--rw-r--r--   0 runner    (1001) docker     (123)    17554 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_anti_affinity_rule.py
--rw-r--r--   0 runner    (1001) docker     (123)    21613 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_dependency_rule.py
--rw-r--r--   0 runner    (1001) docker     (123)    13459 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_group.py
--rw-r--r--   0 runner    (1001) docker     (123)    24422 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_host_rule.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 05:47:19.570671 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/config/
--rw-r--r--   0 runner    (1001) docker     (123)      285 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/config/vars.py
--rw-r--r--   0 runner    (1001) docker     (123)    15087 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/content_library.py
--rw-r--r--   0 runner    (1001) docker     (123)    15640 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/content_library_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     9031 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/custom_attribute.py
--rw-r--r--   0 runner    (1001) docker     (123)    18866 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/datacenter.py
--rw-r--r--   0 runner    (1001) docker     (123)    91913 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/datastore_cluster.py
--rw-r--r--   0 runner    (1001) docker     (123)    16842 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/datastore_cluster_vm_anti_affinity_rule.py
--rw-r--r--   0 runner    (1001) docker     (123)   134499 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/distributed_port_group.py
--rw-r--r--   0 runner    (1001) docker     (123)   263381 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/distributed_virtual_switch.py
--rw-r--r--   0 runner    (1001) docker     (123)    15371 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/dpm_host_override.py
--rw-r--r--   0 runner    (1001) docker     (123)    16657 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/drs_vm_override.py
--rw-r--r--   0 runner    (1001) docker     (123)    12429 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/entity_permissions.py
--rw-r--r--   0 runner    (1001) docker     (123)    23387 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/file.py
--rw-r--r--   0 runner    (1001) docker     (123)    25630 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/folder.py
--rw-r--r--   0 runner    (1001) docker     (123)     5937 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_compute_cluster.py
--rw-r--r--   0 runner    (1001) docker     (123)     6332 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_compute_cluster_host_group.py
--rw-r--r--   0 runner    (1001) docker     (123)     3188 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_content_library.py
--rw-r--r--   0 runner    (1001) docker     (123)     4436 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_content_library_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     4309 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_custom_attribute.py
--rw-r--r--   0 runner    (1001) docker     (123)     4053 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_datacenter.py
--rw-r--r--   0 runner    (1001) docker     (123)     4693 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_datastore.py
--rw-r--r--   0 runner    (1001) docker     (123)     5112 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_datastore_cluster.py
--rw-r--r--   0 runner    (1001) docker     (123)     6814 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_distributed_virtual_switch.py
--rw-r--r--   0 runner    (1001) docker     (123)     6238 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_dynamic.py
--rw-r--r--   0 runner    (1001) docker     (123)     3595 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_folder.py
--rw-r--r--   0 runner    (1001) docker     (123)     5140 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_host.py
--rw-r--r--   0 runner    (1001) docker     (123)     6908 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_host_pci_device.py
--rw-r--r--   0 runner    (1001) docker     (123)     4903 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_host_thumbprint.py
--rw-r--r--   0 runner    (1001) docker     (123)     5153 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_license.py
--rw-r--r--   0 runner    (1001) docker     (123)     7058 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_network.py
--rw-r--r--   0 runner    (1001) docker     (123)    32193 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_ovf_vm_template.py
--rw-r--r--   0 runner    (1001) docker     (123)     3395 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_policy.py
--rw-r--r--   0 runner    (1001) docker     (123)     7358 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_resource_pool.py
--rw-r--r--   0 runner    (1001) docker     (123)     5136 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_role.py
--rw-r--r--   0 runner    (1001) docker     (123)     4756 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_tag.py
--rw-r--r--   0 runner    (1001) docker     (123)     4959 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_tag_category.py
--rw-r--r--   0 runner    (1001) docker     (123)     4428 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_vapp_container.py
--rw-r--r--   0 runner    (1001) docker     (123)    55448 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_virtual_machine.py
--rw-r--r--   0 runner    (1001) docker     (123)     6642 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_vmfs_disks.py
--rw-r--r--   0 runner    (1001) docker     (123)    58963 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/ha_vm_override.py
--rw-r--r--   0 runner    (1001) docker     (123)    45915 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/host.py
--rw-r--r--   0 runner    (1001) docker     (123)    56784 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/host_port_group.py
--rw-r--r--   0 runner    (1001) docker     (123)    61643 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/host_virtual_switch.py
--rw-r--r--   0 runner    (1001) docker     (123)    12752 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/license.py
--rw-r--r--   0 runner    (1001) docker     (123)    48202 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/nas_datastore.py
--rw-r--r--   0 runner    (1001) docker     (123)    87056 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20381 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/provider.py
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/pulumi-plugin.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    54091 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/resource_pool.py
--rw-r--r--   0 runner    (1001) docker     (123)     8528 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/role.py
--rw-r--r--   0 runner    (1001) docker     (123)    20828 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/storage_drs_vm_override.py
--rw-r--r--   0 runner    (1001) docker     (123)     9943 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/tag.py
--rw-r--r--   0 runner    (1001) docker     (123)    15120 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/tag_category.py
--rw-r--r--   0 runner    (1001) docker     (123)    48255 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vapp_container.py
--rw-r--r--   0 runner    (1001) docker     (123)    29555 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vapp_entity.py
--rw-r--r--   0 runner    (1001) docker     (123)    28150 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/virtual_disk.py
--rw-r--r--   0 runner    (1001) docker     (123)   270022 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/virtual_machine.py
--rw-r--r--   0 runner    (1001) docker     (123)    23926 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/virtual_machine_snapshot.py
--rw-r--r--   0 runner    (1001) docker     (123)    21418 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vm_storage_policy.py
--rw-r--r--   0 runner    (1001) docker     (123)    34596 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vmfs_datastore.py
--rw-r--r--   0 runner    (1001) docker     (123)    28500 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vnic.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 05:47:19.570671 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4868 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2783 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       49 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 05:47:19.570671 pulumi_vsphere-4.6.0a1687758153/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2144 2023-06-26 05:47:19.000000 pulumi_vsphere-4.6.0a1687758153/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:13.629789 pulumi_vsphere-4.6.0a1687903041/
+-rw-r--r--   0 runner    (1001) docker     (123)     4868 2023-06-27 22:02:13.625789 pulumi_vsphere-4.6.0a1687903041/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4518 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:13.625789 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/
+-rw-r--r--   0 runner    (1001) docker     (123)     9765 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    87033 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/_inputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8081 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/_utilities.py
+-rw-r--r--   0 runner    (1001) docker     (123)   237133 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13437 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_host_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24459 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_affinity_rule.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17554 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_anti_affinity_rule.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21613 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_dependency_rule.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13459 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24422 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_host_rule.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:13.625789 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/config/
+-rw-r--r--   0 runner    (1001) docker     (123)      285 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/config/vars.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15087 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/content_library.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15640 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/content_library_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9031 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/custom_attribute.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18866 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/datacenter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    91913 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/datastore_cluster.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16842 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/datastore_cluster_vm_anti_affinity_rule.py
+-rw-r--r--   0 runner    (1001) docker     (123)   134499 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/distributed_port_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)   263381 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/distributed_virtual_switch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15371 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/dpm_host_override.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16657 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/drs_vm_override.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12429 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/entity_permissions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23387 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/file.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25630 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/folder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5937 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_compute_cluster.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6066 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_compute_cluster_host_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3188 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_content_library.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4436 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_content_library_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4309 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_custom_attribute.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4053 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_datacenter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4693 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_datastore.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5112 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_datastore_cluster.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6814 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_distributed_virtual_switch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6042 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_dynamic.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3595 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_folder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5140 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_host.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6908 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_host_pci_device.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4903 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_host_thumbprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5153 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_license.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7058 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_network.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32193 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_ovf_vm_template.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3395 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_policy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7270 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_resource_pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5136 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_role.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4756 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_tag.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4959 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_tag_category.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4428 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_vapp_container.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55448 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_virtual_machine.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6642 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_vmfs_disks.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58963 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/ha_vm_override.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45915 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/host.py
+-rw-r--r--   0 runner    (1001) docker     (123)    56784 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/host_port_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    61643 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/host_virtual_switch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12752 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/license.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48202 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/nas_datastore.py
+-rw-r--r--   0 runner    (1001) docker     (123)    86864 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20381 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/provider.py
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/pulumi-plugin.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    54091 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/resource_pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8528 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/role.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20828 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/storage_drs_vm_override.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9943 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/tag.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15120 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/tag_category.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48255 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vapp_container.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29555 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vapp_entity.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28150 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/virtual_disk.py
+-rw-r--r--   0 runner    (1001) docker     (123)   270022 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/virtual_machine.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23926 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/virtual_machine_snapshot.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20958 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vm_storage_policy.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34596 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vmfs_datastore.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28500 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vnic.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:02:13.625789 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4868 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2783 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       49 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 22:02:13.629789 pulumi_vsphere-4.6.0a1687903041/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2144 2023-06-27 22:02:13.000000 pulumi_vsphere-4.6.0a1687903041/setup.py
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/PKG-INFO` & `pulumi_vsphere-4.6.0a1687903041/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pulumi_vsphere
-Version: 4.6.0a1687758153
+Version: 4.6.0a1687903041
 Summary: A Pulumi package for creating vsphere resources
 Home-page: https://pulumi.io
 License: Apache-2.0
 Project-URL: Repository, https://github.com/pulumi/pulumi-vsphere
 Keywords: pulumi vsphere
 Platform: UNKNOWN
 Requires-Python: >=3.7
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/README.md` & `pulumi_vsphere-4.6.0a1687903041/README.md`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/__init__.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/__init__.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/_inputs.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/_inputs.py`

 * *Files 0% similar despite different names*

```diff
@@ -63,16 +63,16 @@
                    vsan_performance_enabled=True,
                    vsan_verbose_mode_enabled=True,
                    vsan_network_diagnostic_mode_enabled=True,
                    vsan_unmap_enabled=True,
                    vsan_dit_encryption_enabled=True,
                    vsan_dit_rekey_interval=1800,
                    vsan_disk_groups=[vsphere.ComputeClusterVsanDiskGroupArgs(
-                       cache=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
-                       storages=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                       cache=data["vsphere_vmfs_disks"]["cache_disks"],
+                       storages=data["vsphere_vmfs_disks"]["storage_disks"],
                    )])
                ```
         """
         if cache is not None:
             pulumi.set(__self__, "cache", cache)
         if storages is not None:
             pulumi.set(__self__, "storages", storages)
@@ -114,16 +114,16 @@
             vsan_performance_enabled=True,
             vsan_verbose_mode_enabled=True,
             vsan_network_diagnostic_mode_enabled=True,
             vsan_unmap_enabled=True,
             vsan_dit_encryption_enabled=True,
             vsan_dit_rekey_interval=1800,
             vsan_disk_groups=[vsphere.ComputeClusterVsanDiskGroupArgs(
-                cache=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
-                storages=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                cache=data["vsphere_vmfs_disks"]["cache_disks"],
+                storages=data["vsphere_vmfs_disks"]["storage_disks"],
             )])
         ```
         """
         return pulumi.get(self, "storages")
 
     @storages.setter
     def storages(self, value: Optional[pulumi.Input[Sequence[pulumi.Input[str]]]]):
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/_utilities.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/_utilities.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_host_group.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_host_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_affinity_rule.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_affinity_rule.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_anti_affinity_rule.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_anti_affinity_rule.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_dependency_rule.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_dependency_rule.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_group.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/compute_cluster_vm_host_rule.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/compute_cluster_vm_host_rule.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/config/vars.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/config/vars.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/content_library.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/content_library.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/content_library_item.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/content_library_item.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/custom_attribute.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/custom_attribute.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/datacenter.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/datacenter.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/datastore_cluster.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/datastore_cluster.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/datastore_cluster_vm_anti_affinity_rule.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/datastore_cluster_vm_anti_affinity_rule.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/distributed_port_group.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/distributed_port_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/distributed_virtual_switch.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/distributed_virtual_switch.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/dpm_host_override.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/dpm_host_override.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/drs_vm_override.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/drs_vm_override.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/entity_permissions.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/entity_permissions.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/file.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/file.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/folder.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/folder.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_compute_cluster.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_compute_cluster.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_compute_cluster_host_group.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_compute_cluster_host_group.py`

 * *Files 4% similar despite different names*

```diff
@@ -85,16 +85,16 @@
 
     ## Example Usage
 
     ```python
     import pulumi
     import pulumi_vsphere as vsphere
 
-    datacenter = vsphere.get_datacenter(name=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
-    cluster = vsphere.get_compute_cluster(name=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+    datacenter = vsphere.get_datacenter(name=var["vsphere_datacenter"])
+    cluster = vsphere.get_compute_cluster(name=var["vsphere_cluster"],
         datacenter_id=datacenter.id)
     host_group1 = vsphere.get_compute_cluster_host_group(name="host_group1",
         compute_cluster_id=cluster.id)
     host_rule1 = vsphere.ComputeClusterVmHostRule("hostRule1",
         compute_cluster_id=cluster.id,
         vm_group_name="vm_group1",
         affinity_host_group_name=host_group1.name)
@@ -131,16 +131,16 @@
 
     ## Example Usage
 
     ```python
     import pulumi
     import pulumi_vsphere as vsphere
 
-    datacenter = vsphere.get_datacenter(name=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
-    cluster = vsphere.get_compute_cluster(name=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+    datacenter = vsphere.get_datacenter(name=var["vsphere_datacenter"])
+    cluster = vsphere.get_compute_cluster(name=var["vsphere_cluster"],
         datacenter_id=datacenter.id)
     host_group1 = vsphere.get_compute_cluster_host_group(name="host_group1",
         compute_cluster_id=cluster.id)
     host_rule1 = vsphere.ComputeClusterVmHostRule("hostRule1",
         compute_cluster_id=cluster.id,
         vm_group_name="vm_group1",
         affinity_host_group_name=host_group1.name)
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_content_library.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_content_library.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_content_library_item.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_content_library_item.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_custom_attribute.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_custom_attribute.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_datacenter.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_datacenter.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_datastore.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_datastore.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_datastore_cluster.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_datastore_cluster.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_distributed_virtual_switch.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_distributed_virtual_switch.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_dynamic.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_dynamic.py`

 * *Files 22% similar despite different names*

```diff
@@ -86,17 +86,17 @@
 
     ```python
     import pulumi
     import pulumi_vsphere as vsphere
 
     category = vsphere.get_tag_category(name="SomeCategory")
     tag1 = vsphere.get_tag(name="FirstTag",
-        category_id=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
+        category_id=data["vsphere_tag_category"]["cat"]["id"])
     tag2 = vsphere.get_tag(name="SecondTag",
-        category_id=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
+        category_id=data["vsphere_tag_category"]["cat"]["id"])
     dyn = vsphere.get_dynamic(filters=[
             tag1.id,
             tag1.id,
         ],
         name_regex="ubuntu",
         type="Datacenter")
     ```
@@ -140,17 +140,17 @@
 
     ```python
     import pulumi
     import pulumi_vsphere as vsphere
 
     category = vsphere.get_tag_category(name="SomeCategory")
     tag1 = vsphere.get_tag(name="FirstTag",
-        category_id=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
+        category_id=data["vsphere_tag_category"]["cat"]["id"])
     tag2 = vsphere.get_tag(name="SecondTag",
-        category_id=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
+        category_id=data["vsphere_tag_category"]["cat"]["id"])
     dyn = vsphere.get_dynamic(filters=[
             tag1.id,
             tag1.id,
         ],
         name_regex="ubuntu",
         type="Datacenter")
     ```
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_folder.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_folder.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_host.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_host.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_host_pci_device.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_host_pci_device.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_host_thumbprint.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_host_thumbprint.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_license.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_license.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_network.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_network.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_ovf_vm_template.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_ovf_vm_template.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_policy.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_policy.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_resource_pool.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_resource_pool.py`

 * *Files 4% similar despite different names*

```diff
@@ -92,15 +92,15 @@
     _root resource pool_ and can be looked up by specifying the path.
 
     ```python
     import pulumi
     import pulumi_vsphere as vsphere
 
     pool = vsphere.get_resource_pool(name="esxi-01.example.com/Resources",
-        datacenter_id=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
+        datacenter_id=data["vsphere_datacenter"]["datacenter"]["id"])
     ```
 
     For more information on the root resource pool, see [Managing Resource Pools][vmware-docs-resource-pools] in the vSphere documentation.
 
     [vmware-docs-resource-pools]: https://docs.vmware.com/en/VMware-vSphere/7.0/com.vmware.vsphere.resmgmt.doc/GUID-60077B40-66FF-4625-934A-641703ED7601.html
 
 
@@ -159,15 +159,15 @@
     _root resource pool_ and can be looked up by specifying the path.
 
     ```python
     import pulumi
     import pulumi_vsphere as vsphere
 
     pool = vsphere.get_resource_pool(name="esxi-01.example.com/Resources",
-        datacenter_id=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference))
+        datacenter_id=data["vsphere_datacenter"]["datacenter"]["id"])
     ```
 
     For more information on the root resource pool, see [Managing Resource Pools][vmware-docs-resource-pools] in the vSphere documentation.
 
     [vmware-docs-resource-pools]: https://docs.vmware.com/en/VMware-vSphere/7.0/com.vmware.vsphere.resmgmt.doc/GUID-60077B40-66FF-4625-934A-641703ED7601.html
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_role.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_role.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_tag.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_tag.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_tag_category.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_tag_category.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_vapp_container.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_vapp_container.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_virtual_machine.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_virtual_machine.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/get_vmfs_disks.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/get_vmfs_disks.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/ha_vm_override.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/ha_vm_override.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/host.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/host.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/host_port_group.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/host_port_group.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/host_virtual_switch.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/host_virtual_switch.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/license.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/license.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/nas_datastore.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/nas_datastore.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/outputs.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/outputs.py`

 * *Files 1% similar despite different names*

```diff
@@ -66,16 +66,16 @@
                    vsan_performance_enabled=True,
                    vsan_verbose_mode_enabled=True,
                    vsan_network_diagnostic_mode_enabled=True,
                    vsan_unmap_enabled=True,
                    vsan_dit_encryption_enabled=True,
                    vsan_dit_rekey_interval=1800,
                    vsan_disk_groups=[vsphere.ComputeClusterVsanDiskGroupArgs(
-                       cache=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
-                       storages=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                       cache=data["vsphere_vmfs_disks"]["cache_disks"],
+                       storages=data["vsphere_vmfs_disks"]["storage_disks"],
                    )])
                ```
         """
         if cache is not None:
             pulumi.set(__self__, "cache", cache)
         if storages is not None:
             pulumi.set(__self__, "storages", storages)
@@ -113,16 +113,16 @@
             vsan_performance_enabled=True,
             vsan_verbose_mode_enabled=True,
             vsan_network_diagnostic_mode_enabled=True,
             vsan_unmap_enabled=True,
             vsan_dit_encryption_enabled=True,
             vsan_dit_rekey_interval=1800,
             vsan_disk_groups=[vsphere.ComputeClusterVsanDiskGroupArgs(
-                cache=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
-                storages=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                cache=data["vsphere_vmfs_disks"]["cache_disks"],
+                storages=data["vsphere_vmfs_disks"]["storage_disks"],
             )])
         ```
         """
         return pulumi.get(self, "storages")
 
 
 @pulumi.output_type
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/provider.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/provider.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/resource_pool.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/resource_pool.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/role.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/role.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/storage_drs_vm_override.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/storage_drs_vm_override.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/tag.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/tag.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/tag_category.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/tag_category.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vapp_container.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vapp_container.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vapp_entity.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vapp_entity.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/virtual_disk.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/virtual_disk.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/virtual_machine.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/virtual_machine.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/virtual_machine_snapshot.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/virtual_machine_snapshot.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vm_storage_policy.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vm_storage_policy.py`

 * *Files 6% similar despite different names*

```diff
@@ -185,44 +185,44 @@
         import pulumi
         import pulumi_vsphere as vsphere
 
         prod_platinum_replicated = vsphere.VmStoragePolicy("prodPlatinumReplicated",
             description="prod_platinum_replicated",
             tag_rules=[
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["environment"]["name"],
                     tags=[data["vsphere_tag"]["production"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["service_level"]["name"],
                     tags=[data["vsphere_tag"]["platinum"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["replication"]["name"],
                     tags=[data["vsphere_tag"]["replicated"]["name"]],
                     include_datastores_with_tags=True,
                 ),
             ])
         dev_silver_nonreplicated = vsphere.VmStoragePolicy("devSilverNonreplicated",
             description="dev_silver_nonreplicated",
             tag_rules=[
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["environment"]["name"],
                     tags=[data["vsphere_tag"]["development"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["service_level"]["name"],
                     tags=[data["vsphere_tag"]["silver"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["replication"]["name"],
                     tags=[data["vsphere_tag"]["non_replicated"]["name"]],
                     include_datastores_with_tags=True,
                 ),
             ])
         ```
 
         Lasttly, when creating a virtual machine resource, a storage policy can be specificed to direct virtual machine placement to a datastore which matches the policy's `tags_rules`.
@@ -303,44 +303,44 @@
         import pulumi
         import pulumi_vsphere as vsphere
 
         prod_platinum_replicated = vsphere.VmStoragePolicy("prodPlatinumReplicated",
             description="prod_platinum_replicated",
             tag_rules=[
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["environment"]["name"],
                     tags=[data["vsphere_tag"]["production"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["service_level"]["name"],
                     tags=[data["vsphere_tag"]["platinum"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["replication"]["name"],
                     tags=[data["vsphere_tag"]["replicated"]["name"]],
                     include_datastores_with_tags=True,
                 ),
             ])
         dev_silver_nonreplicated = vsphere.VmStoragePolicy("devSilverNonreplicated",
             description="dev_silver_nonreplicated",
             tag_rules=[
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["environment"]["name"],
                     tags=[data["vsphere_tag"]["development"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["service_level"]["name"],
                     tags=[data["vsphere_tag"]["silver"]["name"]],
                     include_datastores_with_tags=True,
                 ),
                 vsphere.VmStoragePolicyTagRuleArgs(
-                    tag_category=%!v(PANIC=Format method: runtime error: invalid memory address or nil pointer dereference),
+                    tag_category=data["vsphere_tag_category"]["replication"]["name"],
                     tags=[data["vsphere_tag"]["non_replicated"]["name"]],
                     include_datastores_with_tags=True,
                 ),
             ])
         ```
 
         Lasttly, when creating a virtual machine resource, a storage policy can be specificed to direct virtual machine placement to a datastore which matches the policy's `tags_rules`.
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vmfs_datastore.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vmfs_datastore.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere/vnic.py` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere/vnic.py`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/PKG-INFO` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pulumi-vsphere
-Version: 4.6.0a1687758153
+Version: 4.6.0a1687903041
 Summary: A Pulumi package for creating vsphere resources
 Home-page: https://pulumi.io
 License: Apache-2.0
 Project-URL: Repository, https://github.com/pulumi/pulumi-vsphere
 Keywords: pulumi vsphere
 Platform: UNKNOWN
 Requires-Python: >=3.7
```

### Comparing `pulumi_vsphere-4.6.0a1687758153/pulumi_vsphere.egg-info/SOURCES.txt` & `pulumi_vsphere-4.6.0a1687903041/pulumi_vsphere.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pulumi_vsphere-4.6.0a1687758153/setup.py` & `pulumi_vsphere-4.6.0a1687903041/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -4,16 +4,16 @@
 
 import errno
 from setuptools import setup, find_packages
 from setuptools.command.install import install
 from subprocess import check_call
 
 
-VERSION = "4.6.0a1687758153"
-PLUGIN_VERSION = "4.6.0-alpha.1687758153+3fd592b9"
+VERSION = "4.6.0a1687903041"
+PLUGIN_VERSION = "4.6.0-alpha.1687903041+4bf70fc0"
 
 class InstallPluginCommand(install):
     def run(self):
         install.run(self)
         try:
             check_call(['pulumi', 'plugin', 'install', 'resource', 'vsphere', PLUGIN_VERSION])
         except OSError as error:
```


# Comparing `tmp/avisdk-22.1.3.tar.gz` & `tmp/avisdk-22.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "avisdk-22.1.3.tar", last modified: Thu Feb  2 14:48:36 2023, max compression
+gzip compressed data, was "avisdk-22.1.4.tar", last modified: Wed Jun 28 11:00:53 2023, max compression
```

## Comparing `avisdk-22.1.3.tar` & `avisdk-22.1.4.tar`

### file list

```diff
@@ -1,87 +1,87 @@
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.787283 avisdk-22.1.3/
--rw-r--r--   0 runner    (1001) docker     (116)      291 2023-02-02 14:48:35.000000 avisdk-22.1.3/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (116)      699 2023-02-02 14:48:36.787283 avisdk-22.1.3/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.779283 avisdk-22.1.3/avi/
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.779283 avisdk-22.1.3/avi/sdk/
--rw-r--r--   0 runner    (1001) docker     (116)      100 2023-02-02 14:48:35.000000 avisdk-22.1.3/avi/sdk/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)    45638 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/avi_api.py
--rw-r--r--   0 runner    (1001) docker     (116)     1457 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/avi_sdk.py
--rw-r--r--   0 runner    (1001) docker     (116)    26020 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/saml_avi_api.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)     3451 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/alb_rules.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/apic/
--rwxr-xr-x   0 runner    (1001) docker     (116)      284 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/AddBDSubnet.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)      302 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/AddEPGContractCons.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)      302 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/AddEPGContractProv.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)      284 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/CreateBD.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)      336 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/CreateContract.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)      373 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/CreateEPG.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)     3161 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/CreateGraphWithParams.xml
--rwxr-xr-x   0 runner    (1001) docker     (116)      175 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/CreateTenant.xml
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)    10726 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/apic_client.py
--rw-r--r--   0 runner    (1001) docker     (116)    13705 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/apic_tenant.py
--rw-r--r--   0 runner    (1001) docker     (116)     4680 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/apic/apic_tenant_config.json
--rw-r--r--   0 runner    (1001) docker     (116)     1618 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/avi_config_backup.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/certs/
--rw-r--r--   0 runner    (1001) docker     (116)     1314 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/certs/cacert.pem
--rw-r--r--   0 runner    (1001) docker     (116)     1834 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/certs/cakey.pem
--rw-r--r--   0 runner    (1001) docker     (116)     1265 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/certs/server.crt
--rw-r--r--   0 runner    (1001) docker     (116)     1704 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/certs/server.key
--rw-r--r--   0 runner    (1001) docker     (116)     3414 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/change_password_example.py
--rw-r--r--   0 runner    (1001) docker     (116)   135578 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/clone_vs.py
--rw-r--r--   0 runner    (1001) docker     (116)    17455 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/clone_vs_segroup.py
--rw-r--r--   0 runner    (1001) docker     (116)      550 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/common.py
--rw-r--r--   0 runner    (1001) docker     (116)    21496 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/custom_dns_script_infoblox.py
--rw-r--r--   0 runner    (1001) docker     (116)    33785 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/custom_ipam_script_infoblox.py
--rw-r--r--   0 runner    (1001) docker     (116)     2896 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/get_config_logs.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/heat/
--rwxr-xr-x   0 runner    (1001) docker     (116)     3674 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/heat/lb-asg.yaml
--rwxr-xr-x   0 runner    (1001) docker     (116)       72 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/heat/lb-env.yaml
--rwxr-xr-x   0 runner    (1001) docker     (116)     2459 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/heat/lb-server.yaml
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/init_system/
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/init_system/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/init_system/examples/
--rw-r--r--   0 runner    (1001) docker     (116)     3617 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/init_system/examples/init-apic.json
--rw-r--r--   0 runner    (1001) docker     (116)     2903 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/init_system/examples/init-openstack.json
--rw-r--r--   0 runner    (1001) docker     (116)    33216 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/init_system/init_system.py
--rw-r--r--   0 runner    (1001) docker     (116)     4440 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/inventory_example.py
--rw-r--r--   0 runner    (1001) docker     (116)     1817 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/multi_tenant.py
--rw-r--r--   0 runner    (1001) docker     (116)    11542 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/operstate_controlscript_infoblox.py
--rw-r--r--   0 runner    (1001) docker     (116)     8219 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/patch_api_example.py
--rw-r--r--   0 runner    (1001) docker     (116)     2347 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/se_vs_metrics.py
--rw-r--r--   0 runner    (1001) docker     (116)     1635 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/simple_control_script.py
--rw-r--r--   0 runner    (1001) docker     (116)     2366 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/ssl_keyandcertificate_w_altnames.py
--rw-r--r--   0 runner    (1001) docker     (116)     3826 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/sticky_pool_group.py
--rw-r--r--   0 runner    (1001) docker     (116)    13596 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/validate_custom_ipam_script.py
--rw-r--r--   0 runner    (1001) docker     (116)     1076 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/virtualservice_disable.py
--rw-r--r--   0 runner    (1001) docker     (116)    21770 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/virtualservice_examples_api.py
--rw-r--r--   0 runner    (1001) docker     (116)     7008 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/virtualservice_examples_saml_api.py
--rw-r--r--   0 runner    (1001) docker     (116)     5894 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/virtualservice_examples_sdk.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/samples/vra/
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/vra/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)     7142 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/samples/vra/update_vra.py
--rw-r--r--   0 runner    (1001) docker     (116)       40 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (116)     1596 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/test/
--rw-r--r--   0 runner    (1001) docker     (116)     2316 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/test/jenkins_test_api.cfg
--rw-r--r--   0 runner    (1001) docker     (116)     2307 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/test/test_api.cfg
--rw-r--r--   0 runner    (1001) docker     (116)     2447 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/test/test_saml_api.cfg
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/utils/
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)    22973 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/utils/ansible_utils.py
--rw-r--r--   0 runner    (1001) docker     (116)     7230 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/utils/api_utils.py
--rw-r--r--   0 runner    (1001) docker     (116)     5187 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/utils/httppolicyset_templates.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.783283 avisdk-22.1.3/avi/sdk/utils/mesos/
--rw-r--r--   0 runner    (1001) docker     (116)       77 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/utils/mesos/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)    22064 2023-02-02 14:46:46.000000 avisdk-22.1.3/avi/sdk/utils/mesos/mesos_testutils.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2023-02-02 14:48:36.787283 avisdk-22.1.3/avisdk.egg-info/
--rw-r--r--   0 runner    (1001) docker     (116)      699 2023-02-02 14:48:36.000000 avisdk-22.1.3/avisdk.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (116)     2460 2023-02-02 14:48:36.000000 avisdk-22.1.3/avisdk.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (116)        1 2023-02-02 14:48:36.000000 avisdk-22.1.3/avisdk.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (116)        9 2023-02-02 14:48:36.000000 avisdk-22.1.3/avisdk.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (116)        4 2023-02-02 14:48:36.000000 avisdk-22.1.3/avisdk.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (116)       38 2023-02-02 14:48:36.787283 avisdk-22.1.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (116)     1602 2023-02-02 14:48:35.000000 avisdk-22.1.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/
+-rw-r--r--   0 runner    (1001) docker     (123)      291 2023-06-28 11:00:52.000000 avisdk-22.1.4/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)      699 2023-06-28 11:00:52.994456 avisdk-22.1.4/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.990456 avisdk-22.1.4/avi/
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.990456 avisdk-22.1.4/avi/sdk/
+-rw-r--r--   0 runner    (1001) docker     (123)      100 2023-06-28 11:00:52.000000 avisdk-22.1.4/avi/sdk/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45639 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/avi_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/avi_sdk.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36170 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/saml_avi_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.990456 avisdk-22.1.4/avi/sdk/samples/
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3451 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/alb_rules.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/samples/apic/
+-rwxr-xr-x   0 runner    (1001) docker     (123)      284 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/AddBDSubnet.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      302 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/AddEPGContractCons.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      302 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/AddEPGContractProv.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      284 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/CreateBD.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      336 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/CreateContract.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      373 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/CreateEPG.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3161 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/CreateGraphWithParams.xml
+-rwxr-xr-x   0 runner    (1001) docker     (123)      175 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/CreateTenant.xml
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10726 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/apic_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13705 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/apic_tenant.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4680 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/apic/apic_tenant_config.json
+-rw-r--r--   0 runner    (1001) docker     (123)     1618 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/avi_config_backup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/samples/certs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1314 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/certs/cacert.pem
+-rw-r--r--   0 runner    (1001) docker     (123)     1834 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/certs/cakey.pem
+-rw-r--r--   0 runner    (1001) docker     (123)     1265 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/certs/server.crt
+-rw-r--r--   0 runner    (1001) docker     (123)     1704 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/certs/server.key
+-rw-r--r--   0 runner    (1001) docker     (123)     3414 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/change_password_example.py
+-rw-r--r--   0 runner    (1001) docker     (123)   133682 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/clone_vs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17455 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/clone_vs_segroup.py
+-rw-r--r--   0 runner    (1001) docker     (123)      550 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21496 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/custom_dns_script_infoblox.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33785 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/custom_ipam_script_infoblox.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2896 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/get_config_logs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/samples/heat/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3674 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/heat/lb-asg.yaml
+-rwxr-xr-x   0 runner    (1001) docker     (123)       72 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/heat/lb-env.yaml
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2459 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/heat/lb-server.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/samples/init_system/
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/init_system/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/samples/init_system/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     3617 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/init_system/examples/init-apic.json
+-rw-r--r--   0 runner    (1001) docker     (123)     2903 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/init_system/examples/init-openstack.json
+-rw-r--r--   0 runner    (1001) docker     (123)    33216 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/init_system/init_system.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4440 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/inventory_example.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/multi_tenant.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11542 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/operstate_controlscript_infoblox.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8219 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/patch_api_example.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2347 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/se_vs_metrics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1635 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/simple_control_script.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2366 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/ssl_keyandcertificate_w_altnames.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3826 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/sticky_pool_group.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13596 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/validate_custom_ipam_script.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1076 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/virtualservice_disable.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21770 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/virtualservice_examples_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7008 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/virtualservice_examples_saml_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5894 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/virtualservice_examples_sdk.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/samples/vra/
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/vra/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7142 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/samples/vra/update_vra.py
+-rw-r--r--   0 runner    (1001) docker     (123)       40 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1614 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/test/
+-rw-r--r--   0 runner    (1001) docker     (123)     2316 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/test/jenkins_test_api.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2307 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/test/test_api.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2770 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/test/test_saml_api.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22973 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/utils/ansible_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7230 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/utils/api_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5187 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/utils/httppolicyset_templates.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avi/sdk/utils/mesos/
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/utils/mesos/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22064 2023-06-28 10:59:24.000000 avisdk-22.1.4/avi/sdk/utils/mesos/mesos_testutils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:00:52.994456 avisdk-22.1.4/avisdk.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      699 2023-06-28 11:00:52.000000 avisdk-22.1.4/avisdk.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2460 2023-06-28 11:00:52.000000 avisdk-22.1.4/avisdk.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:00:52.000000 avisdk-22.1.4/avisdk.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 11:00:52.000000 avisdk-22.1.4/avisdk.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        4 2023-06-28 11:00:52.000000 avisdk-22.1.4/avisdk.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:00:52.994456 avisdk-22.1.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1620 2023-06-28 11:00:52.000000 avisdk-22.1.4/setup.py
```

### Comparing `avisdk-22.1.3/PKG-INFO` & `avisdk-22.1.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: avisdk
-Version: 22.1.3
+Version: 22.1.4
 Summary: Avi python API SDK for Avi Controller REST API with samples and, utilities
 Home-page: https://github.com/vmware/alb-sdk
 Author: Avi Networks
 Author-email: avisdk@avinetworks.com
 License: Avi Networks
 Description: UNKNOWN
 Keywords: AVI ADC Loadbalancer automation datacenter SDK
```

### Comparing `avisdk-22.1.3/avi/sdk/avi_api.py` & `avisdk-22.1.4/avi/sdk/avi_api.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -1098,8 +1098,8 @@
             logger.debug("Cleaned inactive session : %s", key)
 
     def delete_session(self):
         """ Removes the session for cleanup"""
         logger.debug("Removed session for : %s", self.key)
         sessionDict.pop(self.key, None)
         return
-# End of file
+# End of file
```

### Comparing `avisdk-22.1.3/avi/sdk/avi_sdk.py` & `avisdk-22.1.4/avi/sdk/avi_sdk.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/saml_avi_api.py` & `avisdk-22.1.4/avi/sdk/saml_avi_api.py`

 * *Files 13% similar despite different names*

```diff
@@ -10,17 +10,214 @@
 import json
 from datetime import datetime
 from requests import ConnectionError
 from requests.exceptions import ChunkedEncodingError
 from ssl import SSLError
 import time
 import logging
+from bs4 import BeautifulSoup
+import warnings
 
 logger = logging.getLogger(__name__)
+warnings.filterwarnings('ignore')
 
+class WS1loginSAMLApiSession(ApiSession):
+    SAML_URL_SUFFIX = "/sso/login"
+    # Request RegX
+    saml_request_regex = r'<input type=\"hidden\" ' \
+                         r'name=\"SAMLRequest\" value=\"(.*?)\"'
+    request_relay_state_regex = r'<input type=\"hidden\" ' \
+                                r'name=\"RelayState\" value=\"(.*?)\"'
+    request_assertion_url_regex = r'<form action=\"(.*?)\" method=\"post\">'
+    # Response RegX
+    response_relay_state_regex = r'<input type=\"hidden\" ' \
+                                 r'name=\"RelayState\" value=\"(.*?)\"'
+    response_assertion_url_regex = r'<form id=\"the_form\" method=\"POST\" action=\"(.*?)\">'
+
+    def __init__(self, controller=None, username=None, password=None,
+                 token=None, tenant=None, tenant_uuid=None, verify=False,
+                 port=None, timeout=60, api_version=None,
+                 retry_conxn_errors=True, data_log=False,
+                 avi_credentials=None, session_id=None, csrftoken=None,
+                 lazy_authentication=False, max_api_retries=None,
+                 idp_cookies=None, user_hdrs=None):
+
+        self.idp_cookies = idp_cookies
+        super(WS1loginSAMLApiSession, self).__init__(
+            controller, username, password, token,
+            tenant, tenant_uuid, verify,
+            port, timeout, api_version,
+            retry_conxn_errors, data_log,
+            avi_credentials, session_id, csrftoken,
+            lazy_authentication, max_api_retries, user_hdrs)
+        return
+
+    def saml_assertion(self, username, password):
+        """
+        Perform SAML request from controller to IDPs.
+        Establish session with controller and IDP.
+        Assert SAML request into the reqeust.
+        Get the controller session and IDP session.
+
+        :param username: IDP Username
+        :param password: IDP Password
+        :return: controller session and IDP response
+        """
+
+        # Getting controller session
+        controller_session = requests.Session()
+        controller_session.verify = False
+        saml_controller_url = self.prefix + self.SAML_URL_SUFFIX
+        logger.info("Getting SAML request from url: %s", saml_controller_url)
+        resp = controller_session.get(saml_controller_url,
+                                      allow_redirects=True)
+        if resp.status_code != 200:
+            logger.error('Status Code %s msg %s' % (
+                resp.status_code, resp.text))
+            raise APIError('Status Code %s msg %s' % (
+                resp.status_code, resp.text), resp)
+        # Getting IDP session
+        idp_session = requests.Session()
+        saml_request_match = re.search(WS1loginSAMLApiSession.saml_request_regex, resp.text,
+                                       re.M | re.S)
+        if not saml_request_match:
+            logger.error("SAML request not generated by controller.")
+            raise APIError("SAML request not generated by controller.")
+        saml_request = saml_request_match.group(1)
+        relay_state = re.search(WS1loginSAMLApiSession.request_relay_state_regex, resp.text,re.M | re.S).group(1)
+        assertion_url = re.search(WS1loginSAMLApiSession.request_assertion_url_regex, resp.text,re.M | re.S).group(1)
+        headers = {'Content-Type': 'application/x-www-form-urlencoded'}
+        saml_data = urllib.parse.urlencode({
+            'SAMLRequest': saml_request,
+            'RelayState': relay_state})
+        if self.idp_cookies:
+            logger.info("Controller url %s generated SAML request is being "
+                        "sent to IDP with existing IDP cookies.",
+                        saml_controller_url)
+            idp_resp = idp_session.post(assertion_url, headers=headers,
+                                        data=saml_data, allow_redirects=False,
+                                        cookies=self.idp_cookies)
+        else:
+            logger.info("Controller url %s generated SAML request is being "
+                        "sent to IDP.", saml_controller_url)
+            idp_resp = idp_session.post(assertion_url, headers=headers,
+                                        data=saml_data, allow_redirects=False)
+        if idp_resp.status_code not in (200, 301, 302):
+            logger.error('Status Code %s msg %s' % (
+                resp.status_code, resp.text))
+            raise APIError('Status Code %s msg %s' % (
+                resp.status_code, resp.text), resp)
+        if "SAMLResponse" not in idp_resp.text:
+            # credentials payload for given IDP
+            parsed_uri = urllib.parse.urlparse(assertion_url)
+            auth_url = "{}://{}/SAAS/API/1.0/REST/auth/system/login".format(parsed_uri.scheme, parsed_uri.netloc)
+            auth = {'username': username, 'password': password, 'issueToken': 'true'}
+            idp_session.headers.update({'content-type': 'application/json'})
+            idp_session.headers.update({'accept': 'application/json'})
+            idp_session.verify = False
+            auth_resp = idp_session.post(auth_url, json=auth)
+            if auth_resp.status_code != 200:
+                logger.error('Status Code %s msg %s' % (
+                    auth_resp.status_code, auth_resp.text))
+                raise APIError('Status Code %s msg %s' % (
+                    auth_resp.status_code, auth_resp.text), auth_resp)
+            json_response = json.loads(auth_resp.content)
+            idp_token = json_response['sessionToken']
+            basic_auth_header = "Bearer " + idp_token
+            idp_session.headers.update({"authorization" : basic_auth_header})
+            idp_resp = idp_session.post(assertion_url, headers=headers,
+                                        data=saml_data, allow_redirects=True)
+            if idp_resp.status_code not in (200, 301, 302):
+                logger.error('Status Code %s msg %s' % (
+                    idp_resp.status_code, idp_resp.text))
+                raise APIError('Status Code %s msg %s' % (
+                    idp_resp.status_code, idp_resp.text), resp)
+            saml_resp = BeautifulSoup(idp_resp.text, features="html.parser")
+            saml_response_match = saml_resp.find('textarea').string
+            if not saml_response_match:
+                logger.error("SAML request not generated by controller.")
+                raise APIError("SAML request not generated by controller.")
+        return controller_session, idp_resp
+
+    def authenticate_session(self):
+        """
+        Performs SAML authentication with Avi controller and IDPs.
+        Stores session cookies and sets header parameters.
+        """
+
+        username = self.avi_credentials.username
+        if self.avi_credentials.password:
+            password = self.avi_credentials.password
+        else:
+            raise APIError("No user password provided")
+        logger.debug('authenticating user %s prefix %s',
+                     self.avi_credentials.username, self.prefix)
+        self.cookies.clear()
+        try:
+            # Assert SAML response
+            controller_session, resp = self.saml_assertion(username, password)
+            content = resp.text
+            saml_resp = BeautifulSoup(resp.text, features="html.parser")
+            saml_response = saml_resp.find('textarea').string
+            relay_state = re.search(WS1loginSAMLApiSession.response_relay_state_regex, content, re.M |
+                                    re.S).group(1)
+            assertion_url = re.search(WS1loginSAMLApiSession.response_assertion_url_regex, content, re.M | re.S).group(1)
+            saml_data = urllib.parse.urlencode({
+                'SAMLResponse': saml_response,
+                'RelayState': relay_state
+            })
+            headers = {'Content-Type': 'application/x-www-form-urlencoded'}
+            rsp = controller_session.post(assertion_url,
+                                          headers=headers,
+                                          data=saml_data)
+            if rsp.status_code == 200:
+                self.num_session_retries = 0
+                self.remote_api_version = \
+                    rsp.headers.get('AVI_API_VERSION', {})
+                if self.user_hdrs:
+                    self.headers.update(self.user_hdrs)
+                if rsp.cookies and 'csrftoken' in rsp.cookies:
+                    sessionDict[self.key] = {
+                        'csrftoken': rsp.cookies['csrftoken'],
+                        'session_id': rsp.cookies['sessionid'],
+                        'last_used': datetime.utcnow(),
+                        'api': self,
+                        'connected': True
+                    }
+                logger.debug("authentication success for user %s",
+                             self.avi_credentials.username)
+                return
+            # Check for bad request and invalid credentials response code
+            elif rsp.status_code in [401, 403]:
+                logger.error('Status Code %s msg %s' % (
+                    rsp.status_code, rsp.text))
+                err = APIError('Status Code %s msg %s' % (
+                    rsp.status_code, rsp.text), rsp)
+            else:
+                logger.error("Error status code %s msg %s", rsp.status_code,
+                             rsp.text)
+                err = APIError('Status Code %s msg %s' % (
+                    rsp.status_code, rsp.text), rsp)
+        except (ConnectionError, SSLError, ChunkedEncodingError) as e:
+            if not self.retry_conxn_errors:
+                raise
+            logger.warning('Connection error retrying %s', e)
+            err = e
+        # comes here only if there was either exception or login was not
+        # successful
+        if self.retry_wait_time:
+            time.sleep(self.retry_wait_time)
+        self.num_session_retries += 1
+        if self.num_session_retries > self.max_session_retries:
+            self.num_session_retries = 0
+            logger.error("Giving up after %d retries connection failure %s" % (
+                self.max_session_retries, True))
+            raise err
+        self.authenticate_session()
+        return
 
 class OneloginSAMLApiSession(ApiSession):
     """
     Extends the ApiSession class to override authentication
     method and provide helper utilities to work with Avi
     Controller and IDPs like onelogin, okta, etc.
     """
```

### Comparing `avisdk-22.1.3/avi/sdk/samples/alb_rules.py` & `avisdk-22.1.4/avi/sdk/samples/alb_rules.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/apic/CreateGraphWithParams.xml` & `avisdk-22.1.4/avi/sdk/samples/apic/CreateGraphWithParams.xml`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/apic/apic_client.py` & `avisdk-22.1.4/avi/sdk/samples/apic/apic_client.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/apic/apic_tenant.py` & `avisdk-22.1.4/avi/sdk/samples/apic/apic_tenant.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/apic/apic_tenant_config.json` & `avisdk-22.1.4/avi/sdk/samples/apic/apic_tenant_config.json`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/avi_config_backup.py` & `avisdk-22.1.4/avi/sdk/samples/avi_config_backup.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/certs/cacert.pem` & `avisdk-22.1.4/avi/sdk/samples/certs/cacert.pem`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/certs/cakey.pem` & `avisdk-22.1.4/avi/sdk/samples/certs/cakey.pem`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/certs/server.crt` & `avisdk-22.1.4/avi/sdk/samples/certs/server.crt`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/certs/server.key` & `avisdk-22.1.4/avi/sdk/samples/certs/server.key`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/change_password_example.py` & `avisdk-22.1.4/avi/sdk/samples/change_password_example.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/clone_vs.py` & `avisdk-22.1.4/avi/sdk/samples/clone_vs.py`

 * *Files 11% similar despite different names*

```diff
@@ -13,55 +13,62 @@
 from __future__ import print_function
 import sys
 import os
 import argparse
 import getpass
 import textwrap
 import logging
+import ipaddress
 
 from avi.sdk.avi_api import ApiSession
 from requests.packages import urllib3
 
 logging.basicConfig(level=logging.ERROR)
 
 logger = logging.getLogger(__name__)
 
 # Suppress warnings (typically SSL certificate warnings) when calling the API
 
 urllib3.disable_warnings()
 
-AVICLONE_VERSION = [1, 3, 2]
+AVICLONE_VERSION = [2, 0, 2]
 
 # Try to obtain the terminal width to allow spprint() to wrap output neatly.
 # If unable to determine, assume terminal width is 70 characters
 
 try:
     T_SIZE = os.get_terminal_size()[0]
 except:
     T_SIZE = 70
 
+
 def spprint(s, ind='', **kwargs):
     flush = kwargs.pop('flush', False)
     for para in s.splitlines():
         print('\r\n'.join(textwrap.wrap(para, width=T_SIZE,
                                         subsequent_indent=ind,
                                         break_on_hyphens=False)), **kwargs)
     if flush:
         f = kwargs.get('file', sys.stdout)
-        f.flush() if f is not None else sys.stdout.flush()
+        if f:
+            f.flush()
+        else:
+            sys.stdout.flush()
+
 
 class AviClone:
     VALID_POOL_REF_OBJECTS = {
         'pool-persistency': 'application_persistence_profile_ref',
         'pool-healthmonitor': 'health_monitor_refs',
         'pool-sslprofile': 'ssl_profile_ref',
         'pool-ipaddrgroup': 'ipaddrgroup_ref',
         'pool-pkiprofile': 'pki_profile_ref',
         'pool-sslcert': 'ssl_key_and_certificate_ref',
-        'pool-analyticsprofile': 'analytics_profile_ref'}
+        'pool-analyticsprofile': 'analytics_profile_ref',
+        'pool-autoscalepolicy': 'autoscale_policy_ref'}
     VALID_DATASCRIPT_REF_OBJECTS = {
         'ds-ipgroup': 'ipgroup_refs',
         'ds-stringgroup': 'string_group_refs'}
     VALID_POLICYSET_REF_OBJECTS = {
         'policy-ipgroup': 'group_refs',
         'policy-stringgroup': 'string_group_refs'}
     VALID_VS_REF_OBJECTS = {
@@ -73,64 +80,135 @@
         'vs-servernetworkprofile': 'server_network_profile_ref',
         'vs-sslprofile': 'ssl_profile_ref',
         'vs-sslcert': 'ssl_key_and_certificate_refs',
         'vs-signingcert': 'saml_sp_config/signing_ssl_key_and_certificate_ref',
         'vs-wafpolicy': 'waf_policy_ref',
         'vs-rewritablecontent': 'content_rewrite/rewritable_content_ref',
         'vs-authprofile': 'client_auth/auth_profile_ref',
-        'vs-ssopolicy': 'sso_policy_ref'}
+        'vs-ssopolicy': 'sso_policy_ref',
+        'vs-botpolicy': 'bot_policy_ref'}
     VALID_GS_REF_OBJECTS = {
         'gs-persistency': 'application_persistence_profile_ref',
         'gs-healthmonitor': 'health_monitor_refs'
     }
     VALID_APPLICATIONPROFILE_REF_OBJECTS = {
-        'appprofile-cachemimetypesblacklist':
-            'http_profile/cache_config/mime_types_black_group_refs',
+        'appprofile-cachemimetypesblocklist':
+            'http_profile/cache_config/mime_types_block_group_refs',
         'appprofile-cachemimetypes':
             'http_profile/cache_config/mime_types_group_refs',
         'appprofile-compressiblecontent':
             'http_profile/compression_profile/compressible_content_ref',
         'appprofile-compressibleipaddrgroup': 'ip_addrs_ref',
         'appprofile-compressibledevices': 'devices_ref'}
     VALID_WAFPOLICY_REF_OBJECTS = {'waf-profile': 'waf_profile_ref',
                                    'waf-crs': 'waf_crs_ref',
                                    'positive-security-model':
                                        'positive_security_model/group_refs'}
+    VALID_WAFPOLICYPSMGROUP_REF_OBJECTS = {'wafpsm-stringgroup':
+                                           'match_value_string_group_ref'}
     VALID_SSLCERT_REF_OBJECTS = {
         'ssl-certmgmt': 'certificate_management_profile_ref',
         'ssl-hsmgroup': 'hardwaresecuritymodulegroup_ref'}
     VALID_SSOPOLICY_REF_OBJECTS = {
         'sso-authprofile': 'authentication_policy/default_auth_profile_ref'}
 
-    def __init__(self, source_api, dest_api=None, flags=None):
+    def __init__(self, source_api, dest_api=None, flags=None, tenant=None,
+                 other_tenant=None, other_cloud=None,
+                 other_vrf=None, server_map=None, pool_placement=None,
+                 ssl_key_pps=None):
         self.api = source_api
         self.dest_api = dest_api or source_api
         self.flush_actions()
         self.flags = flags or []
 
+        (self.t_obj,
+         self.tenant,
+         self.tenant_uuid) = self._get_obj_info(obj_type='tenant',
+                                                obj_name=tenant)
+
+        other_tenant = other_tenant or tenant
+        (self.ot_obj,
+         self.other_tenant,
+         self.otenant_uuid) = self._get_obj_info(obj_type='tenant',
+                                                 obj_name=other_tenant,
+                                                 api_to_use=self.dest_api)
+
+        (self.oc_obj,
+         self.other_cloud,
+         self.ocloud_uuid) = self._get_obj_info(obj_type='cloud',
+                                                obj_name=other_cloud,
+                                                api_to_use=self.dest_api,
+                                                tenant_uuid=self.otenant_uuid)
+
+        if other_vrf and not other_cloud:
+            raise Exception('Cloning to a VRF requires '
+                            'target cloud to be specified also')
+
+        if (other_vrf and self.oc_obj['vtype'] == 'CLOUD_NSXT' and
+            self.oc_obj.get('nsxt_configuration', {}).get(
+                'data_network_config', {}).get('tz_type', '')) == 'OVERLAY':
+            # If target cloud is NSX-T Cloud with overlay networking, assume
+            # other_vrf is a t1_lr ID instead of a vrfcontext
+
+            self.ov_obj = None
+            self.other_vrf = other_vrf
+            self.ovrf_uuid = None
+        else:
+            (self.ov_obj,
+             self.other_vrf,
+             self.ovrf_uuid) = self._get_obj_info(obj_type='vrfcontext',
+                                                  obj_name=other_vrf,
+                                                  api_to_use=self.dest_api,
+                                                  tenant_uuid=self.otenant_uuid,
+                                                  cloud_uuid=self.ocloud_uuid)
+
+        self.server_map = server_map
+        self.pool_placement = pool_placement
+        self.ssl_key_pps = ssl_key_pps or dict()
+
     def flush_actions(self):
         self.actions = []
         self.clone_track = {}
 
+    def version_range(self, version, min_version=None, max_version=None):
+        # Returns True if min_version <= version <= max_version
+
+        version_parts = version.split('.')
+        if min_version:
+            min_version_parts = min_version.split('.')
+            for v, m_v in zip(version_parts, min_version_parts):
+                if int(v) < int(m_v):
+                    return False
+                if int(v) > int(m_v):
+                    break
+        if max_version:
+            max_version_parts = max_version.split('.')
+            for v, m_v in zip(version_parts, max_version_parts):
+                if int(v) > int(m_v):
+                    return False
+                if int(v) < int(m_v):
+                    break
+        return True
+
     def get_all_objects_by_name(self, path, name, tenant='', tenant_uuid='',
-                           timeout=None, params=None, api_version=None,
-                           api_to_use=None, **kwargs):
+                                timeout=None, params=None, api_version=None,
+                                api_to_use=None, **kwargs):
         """
         Helper function which works like the SDK's get_object_by_name but
         returns a list of matches rather than just the first match
         """
 
         api = api_to_use or self.api
 
         obj = None
         if not params:
             params = {}
         params['name'] = name
         resp = api.get(path, tenant, tenant_uuid, timeout=timeout,
-                        params=params, api_version=api_version, **kwargs)
+                       params=params, api_version=api_version, **kwargs)
         if resp.status_code in (401, 419):
             ApiSession.reset_session(api)
             resp = self.get_all_objects_by_name(path, name, tenant=tenant,
                                                 tenant_uuid=tenant_uuid,
                                                 timeout=timeout, params=params,
                                                 api_version=api_version,
                                                 api_to_use=api_to_use, **kwargs)
@@ -138,16 +216,16 @@
             obj = resp.json()['results']
 
         api._update_session_last_used()
 
         return obj
 
     def _get_obj_info(self, obj_type, obj=None, obj_name=None,
-                      api_to_use=None, tenant_uuid=None):
-
+                      api_to_use=None, tenant_uuid=None,
+                      cloud_uuid=None):
         """
         Return object name, UUID and object representation from an object
         passed either as an object or object name
         """
 
         api_to_use = api_to_use or self.api
 
@@ -158,15 +236,16 @@
             if obj_name is None:
                 obj = None
                 obj_uuid = None
             else:
                 if obj_name.startswith('/%s/' % obj_type):
                     # If name begins with /<obj_type>/ assume it is a
                     # URL path to the object.
-                    obj_resp = api_to_use.get(obj_name, tenant_uuid=tenant_uuid)
+                    obj_resp = api_to_use.get(
+                        obj_name, tenant_uuid=tenant_uuid)
                     if obj_resp.status_code == 404:
                         # Object was not found; return a pseudo-object with
                         # UUID derived from the URI as a fallback where the
                         # user may not have access to read the object but the
                         # reference is still usable.
 
                         logger.debug('Object URI inaccessible - assuming a '
@@ -178,551 +257,516 @@
                         obj['uuid'] = obj_name.split('/api/%s/' % obj_type)[1]
                     else:
                         obj = obj_resp.json()
                     obj_name = obj.get('name', None)
                     obj_uuid = obj.get('uuid', None)
                 else:
                     obj = api_to_use.get_object_by_name(obj_type, obj_name,
-                                                        tenant_uuid=tenant_uuid)
+                                                        tenant_uuid=tenant_uuid,
+                                                        params=({"cloud_uuid": cloud_uuid}
+                                                                if cloud_uuid else {}))
 
                     if obj is None and obj_type == 'tenant':
                         # User may not have access to lookup tenants by name
                         # so try tenant list API
 
                         tl_obj = api_to_use.get('/user-tenant-list').json()
                         for tenant in tl_obj['tenants']:
                             if tenant['name'] == obj_name:
                                 logger.debug('Found tenant %s in user '
-                                             'tenant list' % obj_name)
+                                             'tenant list', obj_name)
                                 obj = dict()
                                 obj['name'] = obj_name
                                 obj['uuid'] = tenant['uuid']
                                 break
 
                     if obj is None:
                         raise Exception('A %s with name %s could not be found'
                                         % (obj_type, obj_name))
                     obj_uuid = obj.get('uuid', None)
 
         return obj, obj_name, obj_uuid
 
-    def _delete_created_objs(self, created_objs, otenant_uuid):
+    def delete_objects(self, created_objs):
         """
         Deletes any created objects when a failure has occurred.
         """
 
         logger.debug('Deleting created objects...')
 
         for retry in range(len(created_objs)):
             retry_objs = []
             for obj in created_objs:
                 obj_ref = obj['url'].split('/api/')[1]
                 logger.debug('Trying to delete %s', obj_ref)
-                r = self.dest_api.delete(obj_ref, tenant_uuid=otenant_uuid)
+                r = self.dest_api.delete(
+                    obj_ref, tenant_uuid=self.otenant_uuid)
                 if r.status_code >= 300:
                     logger.debug('Failed with %s - will retry', r.status_code)
                     retry_objs.append(obj)
             if retry_objs:
                 created_objs = retry_objs
             else:
                 break
 
-    def delete_objects(self, objs, tenant=None):
-        """
-        Deletes objects in the given tenant
-
-        :param objects: List of objects to delete
-        :param tenant: Tenant containing the objects
-        """
-
-        t_obj, tenant, tenant_uuid = self._get_obj_info(obj_type='tenant',
-                                                     obj_name=tenant,
-                                                     api_to_use=self.dest_api)
-
-        self._delete_created_objs(objs, tenant_uuid)
-
-    def get_new_name(self, object_type, new_name,
-                     otenant_uuid, force_unique_name=False):
+    def get_new_name(self, object_type, new_name, force_unique_name=False):
         new_obj_check = self.dest_api.get_object_by_name(
-                                object_type, new_name, tenant_uuid=otenant_uuid)
+            object_type, new_name, tenant_uuid=self.otenant_uuid)
 
         if new_obj_check is not None:
             if force_unique_name:
                 count = 1
                 new_name_prefix = new_name
                 while new_obj_check is not None:
                     new_name = '-'.join([new_name_prefix, str(count)])
                     count += 1
                     new_obj_check = self.dest_api.get_object_by_name(
-                                                   object_type,
-                                                   new_name,
-                                                   tenant_uuid=otenant_uuid)
+                        object_type,
+                        new_name,
+                        tenant_uuid=self.otenant_uuid)
                 logger.debug('Forced unique name "%s"', new_name)
             else:
                 raise Exception('An object of type %s with '
                                 'name "%s" already exists'
                                 % (object_type, new_name))
         return new_name
 
-    def clone_object(self, old_name, new_name, object_type=None, tenant=None,
-                     other_tenant=None, other_cloud=None,
-                     force_clone=None, force_unique_name=False,
-                     t_obj=None, ot_obj=None, oc_obj=None,
-                     server_map=None):
+    def clone_object(self, old_name, new_name, object_type=None,
+                     force_clone=None, force_unique_name=False):
         """
         Clones an object other than a Virtual Service or GSLB Service
 
         Optionally creating the cloned object in a different tenant and/or a
         different cloud.
 
         Returns a tuple: json representation of the cloned object,
         list of additional objects created if any and any warnings generated
 
-        :param old_name: Name of existing object
+        :param old_name: Name of existing object (name or uri)
         :param new_name: New name for cloned object
-        :param tenant: Tenant for existing object
-        :param other_tenant: Tenant for cloned object
-        :param other_cloud: Cloud for cloned object
+        :param object_type: Type of object (or None to infer from name)
         :param force_clone: List of referenced object attributes to forcibly
                             clone rather than re-use (for example
                             health_monitor_refs)
         :param force_unique_name: Resolve destination name conflicts by
                                   appending an index number
-        :param t_obj: Tenant object. If neither tenant nor t_obj is specified
-                      then user's default tenant will be used
-        :param ot_obj: Tenant for cloned object. If neither other_tenant nor
-                       ot_obj is specified, the object will be cloned to the
-                       same tenant as the source
-                       other_tenant name)
-        :param oc_obj: Cloud for cloned object. If neither other_cloud nor
-                       oc_obj is specified, the object will be cloned
-                       to the same cloud as the source
         :return: tuple - json representation of the cloned object, list of
                  additional objects created if any
         :rtype: tuple
         """
 
         force_clone = force_clone or []
 
-        # Retrieve tenant, other_tenant and other_cloud names, uuids and objects
-        # which may have been passed as objects or names
-
-        t_obj, tenant, tenant_uuid = self._get_obj_info(obj_type='tenant',
-                                                        obj=t_obj,
-                                                        obj_name=tenant)
-
-        if ot_obj is None and other_tenant is None:
-            # Assume cloning to a tenant of the same name as the source
-            # tenant if not otherwise specified
-
-            other_tenant = tenant
-
-        ot_obj, other_tenant, otenant_uuid = self._get_obj_info(
-                                                 obj_type='tenant',
-                                                 obj=ot_obj,
-                                                 obj_name=other_tenant,
-                                                 api_to_use=self.dest_api)
-
-        oc_obj, other_cloud, ocloud_uuid = self._get_obj_info(obj_type='cloud',
-                                                 obj=oc_obj,
-                                                 obj_name=other_cloud,
-                                                 api_to_use=self.dest_api,
-                                                 tenant_uuid=otenant_uuid)
+        created_objs = []
+        warnings = []
 
         if not object_type:
             # If object_type is not specified, assume the old_name is in
             # form object_type/uuid
-
-            object_type = old_name.split('/')[0]
+            if '/' in old_name:
+                object_type = old_name.split('/')[0]
+            else:
+                raise ValueError('Unable to determine object type for %s'
+                                 % object_type)
 
         logger.debug('Cloning %s "%s" to "%s"', object_type,
                      old_name, new_name)
 
         if old_name.startswith(object_type + '/'):
-            old_obj = self.api.get(old_name, tenant_uuid=tenant_uuid,
+            old_obj = self.api.get(old_name, tenant_uuid=self.tenant_uuid,
                                    params=('export_key=true'
-                                       if object_type == 'sslkeyandcertificate'
-                                       else None)).json()
+                                           if object_type == 'sslkeyandcertificate'
+                                           else None)).json()
             old_name = old_obj['name']
         else:
             old_obj = self.api.get_object_by_name(object_type, old_name,
-                                tenant_uuid=tenant_uuid,
-                                params=({'export_key': True}
-                                        if object_type == 'sslkeyandcertificate'
-                                        else None))
+                                                  tenant_uuid=self.tenant_uuid,
+                                                  params=({'export_key': True}
+                                                          if object_type == 'sslkeyandcertificate'
+                                                          else None))
 
         if not old_obj:
             raise Exception('Object of type %s named %s could not be found'
                             % (object_type, old_name))
 
-        new_name = self.get_new_name(object_type, new_name, otenant_uuid,
-                                     force_unique_name)
+        new_name = self.get_new_name(object_type, new_name, force_unique_name)
 
         # Remove unique attributes and rename object
 
         old_obj.pop('uuid', None)
         old_obj.pop('_last_modified', None)
         old_obj_url = old_obj.pop('url', None)
+        old_obj['_clonevs_old_name'] = old_obj['name']
         old_obj['name'] = new_name
 
-        created_objs = []
-        warnings = []
-
         try:
             # Do object-type specific processing of child objects etc.
 
-            if object_type == 'pool':
-                created_objs, warnings = self._process_pool(
-                    p_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone,
-                    server_map=server_map)
-            elif object_type == 'poolgroup':
-                created_objs, warnings = self._process_poolgroup(
-                    pg_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone,
-                    server_map=server_map)
-            elif object_type == 'httppolicyset':
-                created_objs, warnings = self._process_httppolicyset(
-                    ps_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone,
-                    server_map=server_map)
-            elif object_type == 'vsdatascriptset':
-                created_objs, warnings = self._process_vsdatascriptset(
-                    ds_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone,
-                    server_map=server_map)
-            elif object_type == 'networksecuritypolicy':
-                created_objs, warnings = self._process_networksecuritypolicy(
-                    ns_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'dnspolicy':
-                created_objs, warnings = self._process_dnspolicy(
-                    dp_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'applicationprofile':
-                created_objs, warnings = self._process_applicationprofile(
-                    ap_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'wafpolicy':
-                created_objs, warnings = self._process_wafpolicy(
-                    wp_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'authprofile':
-                created_objs, warnings = self._process_authprofile(
-                    ap_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'ssopolicy':
-                created_objs, warnings = self._process_ssopolicy(
-                    sp_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'sslkeyandcertificate':
-                created_objs, warnings = self._process_sslkeyandcertificate(
-                    ss_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'certificatemanagementprofile':
-                (created_objs,
-                 warnings) = self._process_certificatemanagementprofile(
-                    cm_obj=old_obj, t_obj=t_obj, ot_obj=ot_obj,
-                    oc_obj=oc_obj, force_clone=force_clone)
-            elif object_type == 'analyticsprofile':
-                if '18.2.6' <= self.dest_api.api_version <= '20.1.1':
-                    # Workaround for issue in certain releases where
-                    # hs_security_tls13_score is read-only - AV-84655
-                    old_obj.pop('hs_security_tls13_score', None)
+            process_method_name = '_processobject_%s' % object_type
+            if hasattr(self, process_method_name):
+                process_method = getattr(self, process_method_name)
+                created_objs, warnings = process_method(obj=old_obj,
+                                                        force_clone=force_clone)
 
             # Try to create cloned object (possibly in a different tenant to
             # the source object)
 
             logger.debug('Creating %s "%s"...', object_type, new_name)
 
+            old_obj.pop('_clonevs_old_name')
+
             r = self.dest_api.post(object_type, old_obj,
-                                   tenant_uuid=otenant_uuid)
+                                   tenant_uuid=self.otenant_uuid)
             if r.status_code < 300:
                 new_obj = r.json()
                 self.actions += ['Cloned %s "%s"%s to "%s"%s'
                                  % (object_type, old_name,
-                                    (' in tenant "%s"' % tenant)
-                                    if tenant else '', new_name,
-                                    (' in tenant "%s"' % other_tenant)
-                                    if other_tenant else '')]
+                                    (' in tenant "%s"' % self.tenant)
+                                    if self.tenant else '', new_name,
+                                    (' in tenant "%s"' % self.other_tenant)
+                                    if self.other_tenant else '')]
                 logger.debug('Created %s "%s"', object_type, new_obj['url'])
 
                 if old_obj_url:
                     self.clone_track[old_obj_url] = new_obj['url']
                 return new_obj, created_objs, warnings
 
             # API error occurred with POST
             exception_string = ('Unable to clone %s "%s" as "%s" (%d:%s)'
                                 % (object_type, old_name,
-                                  new_name, r.status_code, r.text))
+                                   new_name, r.status_code, r.text))
             logger.debug(exception_string)
             logger.debug(old_obj)
             raise Exception(exception_string)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, otenant_uuid)
+            self.delete_objects(created_objs)
 
             raise Exception('%s\r\n=> Unable to clone %s "%s" as "%s"'
                             % (ex, object_type, old_name, new_name))
 
-    def _process_pool(self, p_obj, t_obj, ot_obj, oc_obj,
-                      force_clone, server_map=None):
+    def _processobject_pool(self, obj, force_clone):
         """
         Performs pool-specific manipulations on the cloned object
         """
 
         # Remove read-only attributes
 
-        logger.debug('Running _process_pool')
+        logger.debug('Running _processobject_pool')
+
+        created_objs = []
+        warnings = []
+
+        obj.pop('gslb_sp_enabled', None)
 
-        p_obj.pop('gslb_sp_enabled', None)
+        cloud_uuid = obj['cloud_ref'].split('/api/cloud/')[1]
 
-        # If cloning to a different cloud, remove network references
+        # If cloning to a different cloud or VRF remove network references
 
-        if oc_obj or server_map:
-            servers = p_obj.get('servers', [])
+        if self.oc_obj or self.server_map or self.ov_obj or self.other_vrf:
+            servers = obj.get('servers', [])
             for server in servers:
                 server.pop('vm_ref', None)
                 server.pop('nw_ref', None)
                 server.pop('external_uuid', None)
                 server.pop('discovered_networks', None)
                 server_ip = (server['ip'].get('addr', None)
                              if 'ip' in server else None)
-                if server_map and server_ip:
-                    for map_spec in server_map:
+                if self.server_map and server_ip:
+                    for map_spec in self.server_map:
                         if server_ip == map_spec[0]:
                             server['ip']['addr'] = map_spec[1]
                             logger.debug('Mapped %s to %s', server_ip,
                                          map_spec[1])
-            p_obj.pop('networks', None)
+            obj.pop('networks', None)
 
-        created_objs = []
-        warnings = []
+            if self.pool_placement:
+                new_placements = set()
+                for server in servers:
+                    server_ip = server['ip']['addr']
+                    server_type = server['ip']['type']
+                    for pool_match, new_placement in self.pool_placement:
+                        if '.' in pool_match and server_type == 'V4':
+                            if (ipaddress.IPv4Address(server_ip) in
+                                ipaddress.IPv4Network(pool_match)):
+                                new_placements.add(new_placement)
+                                logger.debug('Matched server %s to subnet %s'
+                                            % (server_ip, pool_match))
+                                break
+                        elif ':' in pool_match and server_type == 'V6':
+                            if (ipaddress.IPv6Address(server_ip) in
+                                ipaddress.IPv6Network(pool_match)):
+                                new_placements.add(new_placement)
+                                logger.debug('Matched server %s to subnet %s'
+                                            % (server_ip, pool_match))
+                                break
+                logger.debug('Generated pool placement networks: %s'
+                              % new_placements)
+                placement_networks = []
+                for new_placement in new_placements:
+                    new_placement_split = new_placement.split('/')
+                    if len(new_placement_split) == 3:
+                        network, subnet, mask = new_placement_split
+                    elif len(new_placement_split) == 2:
+                        subnet, mask = new_placement_split
+                        network = None
+                    else:
+                        raise('Unable to parse placement network info "%s".'
+                              % new_placement)
+                    placement_network = {}
+                    if network:
+                        (n_obj, n_name, n_uuid) = self._get_obj_info(
+                            obj_type='network',
+                            obj_name=network,
+                            api_to_use=self.dest_api,
+                            cloud_uuid=self.ocloud_uuid or cloud_uuid)
+                        if n_obj:
+                            placement_network['network_ref'] = n_obj['url']
+                        else:
+                            raise('Unable to find referenced placement '
+                                    'network "%s" in the cloud.'
+                                    % new_placement[1])
+                        if ':' in subnet:
+                            placement_network['subnet6'] = {
+                                'ip_addr': {
+                                    'type': 'V6',
+                                    'addr': subnet
+                                },
+                                'mask': mask
+                            }
+                        else:
+                            placement_network['subnet'] = {
+                                'ip_addr': {
+                                    'type': 'V4',
+                                    'addr': subnet
+                                },
+                                'mask': mask
+                            }
+                    placement_networks.append(placement_network)
+                obj['placement_networks'] = placement_networks
+            elif obj.pop('placement_networks', None):
+                warnings.append('Pool %s had placement networks configured '
+                                'that may need to be re-entered manually.'
+                                % obj['name'])
+
+            if self.oc_obj:
+                obj['cloud_ref'] = self.oc_obj['url']
+
+                # If moving to a different cloud, pool will be moved to the
+                # default global VRF in the target cloud unless a target
+                # VRF is specified
+
+                obj.pop('vrf_ref', None)
+
+            # Update VRF or T1_LR reference if a target VRF is specified
+
+            if self.ov_obj:
+                # Remove tier1_lr in case source was NSX-T Cloud with
+                # overlay
+                obj['vrf_ref'] = self.ov_obj['url']
+            elif self.other_vrf:
+                # Case where target is NSX-T Cloud with overlay
+                obj['tier1_lr'] = self.other_vrf
 
         try:
             valid_ref_objects = self.VALID_POOL_REF_OBJECTS
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
-            created_objs, warnings = self._process_refs(parent_obj=p_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=oc_obj,
-                                          force_clone=force_clone,
-                                          name=p_obj['name'])
-
-            if oc_obj:
-                p_obj['cloud_ref'] = oc_obj['url']
-
-                # If moving to a different cloud, pool will be moved to the
-                # default global VRF in the target cloud
+            created_objs, new_warnings = self._process_refs(parent_obj=obj,
+                                                            refs=valid_ref_objects,
+                                                            force_clone=force_clone,
+                                                            name=obj['name'])
+            warnings.extend(new_warnings)
 
-                p_obj.pop('vrf_ref', None)
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_poolgroup(self, pg_obj, t_obj, ot_obj, oc_obj, force_clone,
-                           server_map=None):
+    def _processobject_poolgroup(self, obj, force_clone):
         """
         Performs poolgroup-specific manipulations on the cloned object, such
         as cloning the poolgroup members
         """
 
-        logger.debug('Running _process_poolgroup')
+        logger.debug('Running _processobject_poolgroup')
 
-        new_pool_group_name = pg_obj['name']
+        new_pool_group_name = obj['name']
 
         created_objs = []
         warnings = []
 
         try:
-            if 'members' in pg_obj:
+            if 'members' in obj:
                 count = 1
-                for member in pg_obj['members']:
+                for member in obj['members']:
                     if 'pool_ref' in member:
                         p_path = member['pool_ref'].split('/api/')[1]
                         new_pool_name = '-'.join([new_pool_group_name,
                                                   'pool', str(count)])
 
                         p_obj, p_created_objs, p_warnings = self.clone_object(
                             old_name=p_path, new_name=new_pool_name,
-                            t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj,
-                            force_clone=force_clone, force_unique_name=True,
-                            server_map=server_map)
+                            force_clone=force_clone,
+                            force_unique_name=True)
 
                         count += 1
 
                         created_objs.append(p_obj)
                         created_objs.extend(p_created_objs)
-                        warnings.extend(warnings)
+                        warnings.extend(p_warnings)
 
                         # Update the pool with the cloned pool
 
                         member['pool_ref'] = p_obj['url']
 
             # (Try to!) move the new pool group to a different cloud
 
-            if oc_obj:
-                pg_obj['cloud_ref'] = oc_obj['url']
+            if self.oc_obj:
+                obj['cloud_ref'] = self.oc_obj['url']
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_httppolicyset(self, ps_obj, t_obj, ot_obj, oc_obj,
-                               force_clone, server_map):
+    def _processobject_httppolicyset(self, obj, force_clone):
         """
         Performs httppolicyset-specific manipulations on the cloned object such
         as cloning pools and poolgroups used in the policy rules
         """
 
-        logger.debug('Running _process_httppolicyset')
+        logger.debug('Running _processobject_httppolicyset')
 
-        new_httppolicyset_name = ps_obj['name']
+        new_httppolicyset_name = obj['name']
 
         created_objs = []
         warnings = []
 
         try:
             for policy_type in ['http_security_policy',
                                 'http_request_policy',
                                 'http_response_policy']:
-                policy_obj = ps_obj.get(policy_type, {})
+                policy_obj = obj.get(policy_type, {})
                 if policy_obj:
                     logger.debug('Processing %s', policy_type)
                     new_objs, new_warnings = self._process_policy_rules(
-                                                 new_httppolicyset_name,
-                                                 p_obj=policy_obj, t_obj=t_obj,
-                                                 ot_obj=ot_obj, oc_obj=oc_obj,
-                                                 force_clone=force_clone,
-                                                 server_map=server_map)
+                        new_httppolicyset_name,
+                        p_obj=policy_obj,
+                        force_clone=force_clone)
                     created_objs.extend(new_objs)
                     warnings.extend(new_warnings)
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_networksecuritypolicy(self, ns_obj, t_obj, ot_obj, oc_obj,
-                               force_clone):
+    def _processobject_networksecuritypolicy(self, obj, force_clone):
         """
         Performs networksecuritypolicy-specific manipulations on the cloned
         object such as ip groups in the policy rules
         """
 
-        logger.debug('Running _process_networksecuritypolicy')
+        logger.debug('Running _processobject_networksecuritypolicy')
 
-        new_networksecuritypolicy_name = ns_obj['name']
+        new_networksecuritypolicy_name = obj['name']
 
         created_objs = []
         warnings = []
 
         try:
             created_objs, warnings = self._process_policy_rules(
-                                            new_networksecuritypolicy_name,
-                                            p_obj=ns_obj, t_obj=t_obj,
-                                            ot_obj=ot_obj, oc_obj=oc_obj,
-                                            force_clone=force_clone)
+                new_networksecuritypolicy_name,
+                p_obj=obj, force_clone=force_clone)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_dnspolicy(self, dp_obj, t_obj, ot_obj, oc_obj,
-                               force_clone):
+    def _processobject_dnspolicy(self, obj, force_clone):
         """
         Performs dnspolicy-specific manipulations on the cloned
         object such as ip groups in the policy rules
         """
 
         logger.debug('Running _process_dnspolicy')
 
-        new_dnspolicy_name = dp_obj['name']
+        new_dnspolicy_name = obj['name']
 
         created_objs = []
         warnings = []
 
         try:
             created_objs, warnings = self._process_policy_rules(
-                                                 new_dnspolicy_name,
-                                                 p_obj=dp_obj, t_obj=t_obj,
-                                                 ot_obj=ot_obj, oc_obj=oc_obj,
-                                                 force_clone=force_clone)
+                new_dnspolicy_name,
+                p_obj=obj,
+                force_clone=force_clone)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_authprofile(self, ap_obj, t_obj, ot_obj, oc_obj,
-                               force_clone):
+    def _processobject_authprofile(self, obj, force_clone):
         """
         Performs authprofile-specific manipulations on the cloned
         object
         """
 
         logger.debug('Running _process_authprofile')
 
         created_objs = []
         warnings = []
 
-        if 'ldap' in ap_obj:
-            ldap_obj = ap_obj['ldap']
+        if 'ldap' in obj:
+            ldap_obj = obj['ldap']
             if 'settings' in ldap_obj:
                 ldap_obj['settings']['password'] = 'placeholder'
                 warnings.append('The LDAP password referenced in authprofile '
                                 '%s cannot be cloned and must be re-entered '
-                                'manually.' % ap_obj['name'])
-        if 'tacacs_plus' in ap_obj:
-            ap_obj['tacacs_plus']['password'] = 'placeholder'
+                                'manually.' % obj['name'])
+        if 'tacacs_plus' in obj:
+            obj['tacacs_plus']['password'] = 'placeholder'
             warnings.append('The TACACS password referenced in authprofile '
                             '%s cannot be cloned and must be re-entered '
-                            'manually.' % ap_obj['name'])
+                            'manually.' % obj['name'])
 
         return created_objs, warnings
 
-    def _process_ssopolicy(self, sp_obj, t_obj, ot_obj, oc_obj,
-                               force_clone):
+    def _processobject_ssopolicy(self, obj, force_clone):
         """
         Performs ssopolicy-specific manipulations on the cloned
         object
         """
 
         logger.debug('Running _process_ssopolicy')
 
@@ -731,147 +775,182 @@
 
         try:
             valid_ref_objects = self.VALID_SSOPOLICY_REF_OBJECTS
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
-            created_objs, warnings = self._process_refs(parent_obj=sp_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=oc_obj,
-                                          force_clone=force_clone)
+            created_objs, warnings = self._process_refs(parent_obj=obj,
+                                                        refs=valid_ref_objects,
+                                                        force_clone=force_clone)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_wafpolicy(self, wp_obj, t_obj, ot_obj, oc_obj,
-                               force_clone):
+    def _processobject_wafpolicy(self, obj, force_clone):
         """
-        Performs ssopolicy-specific manipulations on the cloned
+        Performs wafpolicy-specific manipulations on the cloned
         object
         """
 
         logger.debug('Running _process_wafpolicy')
 
         created_objs = []
         warnings = []
 
         try:
             valid_ref_objects = self.VALID_WAFPOLICY_REF_OBJECTS
 
+            if 'disablelearning' in self.flags:
+                if obj.get('enable_app_learning', False):
+                    obj['enable_app_learning'] = False
+                    warnings.append('Disabling learning for WAFPolicy %s'
+                                    % obj['name'])
+
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
-            created_objs, warnings = self._process_refs(parent_obj=wp_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=oc_obj,
-                                          force_clone=force_clone)
+            created_objs, new_warnings = self._process_refs(parent_obj=obj,
+                                                            refs=valid_ref_objects,
+                                                            force_clone=force_clone)
+            warnings.extend(new_warnings)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
-        return created_objs, warnings#, update_data
+        return created_objs, warnings
 
-    def _process_sslkeyandcertificate(self, ss_obj, t_obj, ot_obj, oc_obj,
-                                      force_clone):
+    def _processobject_wafpolicypsmgroup(self, obj, force_clone):
+        """
+        Performs wafpolicypsmgroup-specific manipulations on the cloned
+        object
+        """
+
+        logger.debug('Running _process_wafpolicypsmgroup')
+
+        created_objs = []
+        warnings = []
+
+        try:
+            valid_ref_objects = self.VALID_WAFPOLICYPSMGROUP_REF_OBJECTS
+
+            if 'disablelearning' in self.flags:
+                if obj.get('is_learning_group', False):
+                    obj['is_learning_group'] = False
+                    warnings.append('Clearing learning group mode for '
+                                    'WAFPolicyPSMGroup %s' % obj['name'])
+            if 'locations' in obj:
+                for location in obj['locations']:
+                    if 'rules' in location:
+                        for rule in location['rules']:
+                            created_objs, new_warnings = self._process_refs(
+                                parent_obj=rule,
+                                refs=valid_ref_objects,
+                                force_clone=force_clone)
+                            warnings.extend(new_warnings)
+
+        except Exception as ex:
+            # If an exception occurred, delete any intermediate objects we
+            # have created
+
+            self.delete_objects(created_objs)
+
+            raise
+
+        return created_objs, warnings
+
+    def _processobject_sslkeyandcertificate(self, obj, force_clone):
         """
         Performs sslkeyandcertificate-specific manipulations on the cloned
         object
         """
 
         logger.debug('Running _process_sslkeyandcertificate')
 
         created_objs = []
         warnings = []
 
         try:
-            if ot_obj or self.api != self.dest_api:
+            if self.ot_obj or self.api != self.dest_api:
                 # Remove cross-tenant references
                 logger.debug('Removing ca_certs references')
-                ss_obj.pop('ca_certs', None)
-                ss_obj.pop('key_base64', None)
-                ss_obj.pop('certificate_base64', None)
-
-            ss_obj.pop('ocsp_error_status', None)
+                obj.pop('ca_certs', None)
+                obj.pop('key_base64', None)
+                obj.pop('certificate_base64', None)
+
+            obj.pop('ocsp_error_status', None)
+
+            if 'key_passphrase' in obj:
+                old_name = obj['_clonevs_old_name']
+                obj['key_passphrase'] = self.ssl_key_pps.get(old_name, '')
 
             valid_ref_objects = self.VALID_SSLCERT_REF_OBJECTS
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
-            created_objs, warnings = self._process_refs(parent_obj=ss_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=oc_obj,
-                                          force_clone=force_clone)
+            created_objs, warnings = self._process_refs(parent_obj=obj,
+                                                        refs=valid_ref_objects,
+                                                        force_clone=force_clone)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_certificatemanagementprofile(self, cm_obj, t_obj,
-                                              ot_obj, oc_obj,
-                                              force_clone):
+    def _processobject_certificatemanagementprofile(self, obj, force_clone):
         """
         Performs certificatemanagementobject-specific manipulations on the
         cloned object
         """
 
         logger.debug('Running _process_certificatemanagementprofile')
 
         created_objs = []
         warnings = []
 
         try:
-            if 'script_params' in cm_obj:
-                for par in cm_obj['script_params']:
+            if 'script_params' in obj:
+                for par in obj['script_params']:
                     if par['is_sensitive']:
                         par['value'] = 'placeholder'
                         warnings.append(
                             'A sensitive script parameter (%s) in '
                             'certificate management profile %s cannot '
                             'be cloned and must be re-entered '
-                            'manually.' % (par['name'], cm_obj['name']))
+                            'manually.' % (par['name'], obj['name']))
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_policy_rules(self, new_policy_name, p_obj, t_obj, ot_obj,
-                              oc_obj, force_clone, server_map=None):
+    def _process_policy_rules(self, new_policy_name, p_obj, force_clone):
         """
         Process the network/DNS/HTTP policy rules
         """
 
         logger.debug('Running _process_policy_rules')
 
         valid_ref_objects = self.VALID_POLICYSET_REF_OBJECTS
@@ -888,31 +967,29 @@
                     for m_key, m_obj in rule['match'].items():
                         refs_to_clone = [ref for key, ref in
                                          valid_ref_objects.items()
                                          if key in force_clone]
 
                         new_objs, new_warnings = self._clone_refs(
                             parent_obj=m_obj, refs=refs_to_clone,
-                            t_obj=t_obj, ot_obj=ot_obj,
-                            oc_obj=oc_obj, name=new_policy_name)
+                            name=new_policy_name)
 
                         created_objs.extend(new_objs)
                         warnings.extend(new_warnings)
 
                         # If moving to a different tenant, clone any
                         # tenant-specific referenced objects
 
-                        if ot_obj or self.api != self.dest_api:
+                        if self.ot_obj or self.api != self.dest_api:
                             refs_to_clone = [ref for key, ref in
                                              valid_ref_objects.items()
                                              if key not in force_clone]
                             (new_objs,
                              new_warnings) = self._clone_refs_to_tenant(
-                                   parent_obj=m_obj, refs=refs_to_clone,
-                                   t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj)
+                                parent_obj=m_obj, refs=refs_to_clone)
 
                             created_objs.extend(new_objs)
                             warnings.extend(new_warnings)
 
                 if 'switching_action' in rule:
                     switching_action = rule.get('switching_action', {})
                     pool_ref = switching_action.get('pool_ref', None)
@@ -931,18 +1008,16 @@
                             # Otherwise, clone the pool
 
                             p_path = pool_ref.split('/api/')[1]
                             p_name = '-'.join([new_policy_name, 'pool'])
                             (p_obj, p_created_objs,
                              p_warnings) = self.clone_object(
                                 old_name=p_path, new_name=p_name,
-                                t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj,
                                 force_clone=force_clone,
-                                force_unique_name=True,
-                                server_map=server_map)
+                                force_unique_name=True)
                             created_objs.append(p_obj)
                             created_objs.extend(p_created_objs)
                             warnings.extend(p_warnings)
                             p_obj_url = p_obj['url']
 
                         switching_action['pool_ref'] = p_obj_url
 
@@ -963,214 +1038,213 @@
                         else:
                             pg_path = pool_group_ref.split('/api/')[1]
                             pg_name = '-'.join([new_policy_name,
                                                 'poolgroup'])
                             (pg_obj, pg_created_objs,
                              pg_warnings) = self.clone_object(
                                 old_name=pg_path, new_name=pg_name,
-                                t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj,
                                 force_clone=force_clone,
-                                force_unique_name=True,
-                                server_map=server_map)
+                                force_unique_name=True)
                             created_objs.append(pg_obj)
                             created_objs.extend(pg_created_objs)
                             warnings.extend(pg_warnings)
                             pg_obj_url = pg_obj['url']
 
                         switching_action['pool_group_ref'] = pg_obj_url
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_vsdatascriptset(self, ds_obj, t_obj, ot_obj, oc_obj,
-                               force_clone, server_map):
+    def _processobject_vsdatascriptset(self, obj,  force_clone):
         """
         Performs datascript-specific manipulations on the cloned object such
         as cloning pools, pool groups, string groups, ip groups referenced
         by the DataScript
         """
 
         logger.debug('Running _process_vsdatascriptset')
 
-        new_vsdatascriptset_name = ds_obj['name']
+        new_vsdatascriptset_name = obj['name']
 
         created_objs = []
         warnings = []
 
         try:
-            if 'pool_refs' in ds_obj:
-                for index, pool_ref in enumerate(ds_obj['pool_refs']):
+            if 'pool_refs' in obj:
+                for index, pool_ref in enumerate(obj['pool_refs']):
                     if pool_ref in self.clone_track:
                         # If this pool has already been cloned during
                         # this session, re-use the cloned object
 
                         p_obj_url = self.clone_track[pool_ref]
                         logger.debug('Reusing previously cloned object %s',
                                      p_obj_url)
                     else:
                         # Otherwise, clone the pool
 
                         p_path = pool_ref.split('/api/')[1]
-                        p_name = '-'.join([ds_obj['name'], 'pool'])
+                        p_name = '-'.join([obj['name'], 'pool'])
                         p_obj, p_created_objs, p_warnings = self.clone_object(
                             old_name=p_path, new_name=p_name,
-                            t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj,
                             force_clone=force_clone,
-                            force_unique_name=True,
-                            server_map=server_map)
+                            force_unique_name=True)
 
                         created_objs.append(p_obj)
                         created_objs.extend(p_created_objs)
                         warnings.extend(p_warnings)
                         p_obj_url = p_obj['url']
 
-                    ds_obj['pool_refs'][index] = p_obj_url
+                    obj['pool_refs'][index] = p_obj_url
 
-            if 'pool_group_refs' in ds_obj:
-                for index, pool_group_ref in enumerate(
-                                               ds_obj['pool_group_refs']):
+            if 'pool_group_refs' in obj:
+                for index, pool_group_ref in enumerate(obj['pool_group_refs']):
                     if pool_group_ref in self.clone_track:
                         # If this pool group has already been cloned during
                         # this session, re-use the cloned object
 
                         pg_obj_url = self.clone_track[pool_group_ref]
                         logger.debug('Reusing previously cloned object %s',
                                      pg_obj_url)
                     else:
                         pg_path = pool_group_ref.split('/api/')[1]
-                        pg_name = '-'.join([ds_obj['name'], 'poolgroup'])
+                        pg_name = '-'.join([obj['name'], 'poolgroup'])
                         (pg_obj, pg_created_objs,
                          pg_warnings) = self.clone_object(
                             old_name=pg_path, new_name=pg_name,
-                            t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj,
                             force_clone=force_clone,
-                            force_unique_name=True,
-                            server_map=server_map)
+                            force_unique_name=True)
 
                         created_objs.append(pg_obj)
                         created_objs.extend(pg_created_objs)
                         warnings.extend(pg_warnings)
                         pg_obj_url = pg_obj['url']
 
-                    ds_obj['pool_group_refs'][index] = pg_obj_url
+                    obj['pool_group_refs'][index] = pg_obj_url
 
             valid_ref_objects = self.VALID_DATASCRIPT_REF_OBJECTS
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
-            new_objs, new_warnings = self._process_refs(parent_obj=ds_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=oc_obj,
-                                          force_clone=force_clone)
+            new_objs, new_warnings = self._process_refs(parent_obj=obj,
+                                                        refs=valid_ref_objects,
+                                                        force_clone=force_clone)
 
             created_objs.extend(new_objs)
             warnings.extend(new_warnings)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_applicationprofile(self, ap_obj, t_obj, ot_obj, oc_obj,
-                               force_clone):
+    def _processobject_applicationprofile(self, obj, force_clone):
         """
         Performs applicationprofile-specific manipulations on the cloned
         object such as cloning string groups used for caching/compression
         MIME types
         """
 
         logger.debug('Running _process_applicationprofile')
 
         valid_ref_objects = self.VALID_APPLICATIONPROFILE_REF_OBJECTS
 
         created_objs = []
         warnings = []
 
         try:
-            http_profile = ap_obj.get('http_profile', {})
+            http_profile = obj.get('http_profile', {})
             comp_profile = http_profile.get('compression_profile', None)
 
             if comp_profile:
                 filters = comp_profile.get('filter', [])
                 for filt in filters:
                     logger.debug('Checking filter "%s"...', filt['name'])
 
                     refs_to_clone = [ref for key, ref in
                                      valid_ref_objects.items()
                                      if key in force_clone]
 
                     new_objs, new_warnings = self._clone_refs(
                         parent_obj=filt, refs=refs_to_clone,
-                        t_obj=t_obj, ot_obj=ot_obj,
-                        oc_obj=oc_obj, name=ap_obj['name'])
+                        name=obj['name'])
 
                     created_objs.extend(new_objs)
                     warnings.extend(new_warnings)
 
                     # If moving to a different tenant, clone any
                     # tenant-specific referenced objects
 
-                    if ot_obj or self.api != self.dest_api:
+                    if self.ot_obj or self.api != self.dest_api:
                         refs_to_clone = [ref for key, ref in
                                          valid_ref_objects.items()
                                          if key not in force_clone]
                         new_objs, new_warnings = self._clone_refs_to_tenant(
-                                parent_obj=filt, refs=refs_to_clone,
-                                t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj)
+                            parent_obj=filt, refs=refs_to_clone)
 
                         created_objs.extend(new_objs)
                         warnings.extend(new_warnings)
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
             new_objs, new_warnings = self._process_refs(
-                parent_obj=ap_obj, refs=valid_ref_objects,
-                t_obj=t_obj, ot_obj=ot_obj,
-                oc_obj=oc_obj, force_clone=force_clone)
+                parent_obj=obj, refs=valid_ref_objects,
+                force_clone=force_clone)
 
-            if 'dep20' in self.flags and 'http_profile' in ap_obj:
-                if ap_obj['http_profile'].pop('http2_enabled', False):
+            if 'dep20' in self.flags and 'http_profile' in obj:
+                if obj['http_profile'].pop('http2_enabled', False):
                     warnings.append('http2_enabled=True in application profile '
                                     '%s. You should enable HTTP/2 support for '
                                     'the required service ports in the Virtual '
                                     'Services using this profile.'
-                                    % ap_obj['name'])
+                                    % obj['name'])
 
             created_objs.extend(new_objs)
             warnings.extend(new_warnings)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _process_refs(self, parent_obj, refs, t_obj, ot_obj,
-                      oc_obj, force_clone, name=None):
+    def _processobject_analyticsprofile(self, obj, force_clone):
+        created_objs = []
+        warnings = []
+
+        if self.version_range(self.dest_api.api_version,
+                              min_version='18.2.6',
+                              max_version='22.1.2'):
+            # Workaround for hs_security_tls13_score being read-only - AV-84655
+            # This issue is resolved in the 22.1.3 release
+            if obj.pop('hs_security_tls13_score', None):
+                warnings.append('Removed read-only parameter '
+                                'hs_security_tls13_score from analytics '
+                                'profile %s as workaround for AV-84655.'
+                                % obj['name'])
+
+        return created_objs, warnings
+
+    def _process_refs(self, parent_obj, refs, force_clone, name=None):
 
         # Process references in the object based on a ref list and
         # a force_clone list
 
         created_objs = []
         warnings = []
 
@@ -1180,45 +1254,43 @@
             # but re-use previously cloned objects rather than creating
             # multiple identical clones
 
             refs_to_clone = [ref for key, ref in refs.items()
                              if key in force_clone]
 
             new_objs, new_warnings = self._clone_refs(parent_obj=parent_obj,
-                                        refs=refs_to_clone,
-                                        t_obj=t_obj, ot_obj=ot_obj,
-                                        oc_obj=oc_obj, name=name)
+                                                      refs=refs_to_clone,
+                                                      name=name)
             created_objs.extend(new_objs)
             warnings.extend(new_warnings)
 
             # If moving to a different tenant, clone any tenant-specific
             # referenced objects
 
-            if ot_obj or self.api != self.dest_api:
+            if self.ot_obj or self.api != self.dest_api:
                 refs_to_clone = [ref for key, ref in refs.items()
                                  if key not in force_clone]
                 new_objs, new_warnings = self._clone_refs_to_tenant(
                     parent_obj=parent_obj, refs=refs_to_clone,
-                    t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj, name=name)
+                    name=name)
 
                 created_objs.extend(new_objs)
                 warnings.extend(new_warnings)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _clone_refs(self, parent_obj, refs, t_obj, ot_obj, oc_obj, name=None):
+    def _clone_refs(self, parent_obj, refs, name=None):
 
         # Process the list of child objects, refs, of the parent_obj.
         # If the child object has been cloned before, refer to the
         # previously-cloned object otherwise clone the object.
 
         parent_obj_name = (name or (parent_obj['name']
                                     if 'name' in parent_obj else ''))
@@ -1254,15 +1326,14 @@
                             r_obj_path = child_obj.split('/api/')[1]
                             r_obj_type = r_obj_path.split('/')[0]
                             r_obj_name = '-'.join([parent_obj_name,
                                                    r_obj_type])
                             (new_r_obj, r_created_objs,
                              r_warnings) = self.clone_object(
                                 old_name=r_obj_path, new_name=r_obj_name,
-                                t_obj=t_obj, ot_obj=ot_obj, oc_obj=oc_obj,
                                 force_clone=force_clone,
                                 force_unique_name=True)
 
                             created_objs.append(new_r_obj)
                             created_objs.extend(r_created_objs)
                             warnings.extend(r_warnings)
                             new_r_obj_url = new_r_obj['url']
@@ -1272,38 +1343,33 @@
                         else:
                             pobj_attr[referenced] = new_r_obj_url
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, (ot_obj['uuid']
-                                                     if ot_obj else None))
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
-    def _clone_refs_to_tenant(self, parent_obj, refs, t_obj, ot_obj, oc_obj,
-                              name=None):
+    def _clone_refs_to_tenant(self, parent_obj, refs, name=None):
 
         # Process the list of child objects, refs, of the parent_obj.
         # If the child object is not a global object, then either update the
         # reference to point to an object of the same name in the target tenant
         # or clone the object to the target tenant.
 
         parent_obj_name = (name or (parent_obj['name']
                                     if 'name' in parent_obj else ''))
 
         logger.debug('Cloning refs%s',
                      (' for %s' % parent_obj_name if parent_obj_name else ''))
 
-        tenant_uuid = t_obj['uuid'] if t_obj else None
-        otenant_uuid = ot_obj['uuid'] if ot_obj else None
-
         created_objs = []
         warnings = []
 
         try:
             for ref_str in refs:
                 ref_split = ref_str.split('/')
                 pobj_attr = parent_obj
@@ -1322,20 +1388,20 @@
                         r_obj_path = child_obj.split('/api/')[1]
                         r_obj_type = r_obj_path.split('/')[0]
 
                         # Check if the referenced object exists in the target
                         # tenant context (i.e. is global)
 
                         r_obj = self.dest_api.get(r_obj_path,
-                                                  tenant_uuid=otenant_uuid)
+                                                  tenant_uuid=self.otenant_uuid)
                         r_obj_status = r_obj.status_code
 
                         if (r_obj_status == 200 and
                             r_obj_type == 'sslkeyandcertificate' and
-                            'adminssl' not in self.flags):
+                                'adminssl' not in self.flags):
                             # sslkeyandcertificate requires special treatment
                             # as sslkeyandcertificate objects in the admin
                             # tenant are readable in other tenants but may not
                             # be usable due to cross-tenant restrictions
                             # (depending on Avi version and configuration)
                             #
                             # By default, always clone sslkeyandcertificate
@@ -1355,63 +1421,60 @@
 
                             if r_obj_path in self.clone_track:
                                 # Re-use previously cloned object if
                                 # available
 
                                 new_r_obj_url = self.clone_track[child_obj]
                                 logger.debug('Reusing previously cloned '
-                                                'object %s', new_r_obj_url)
+                                             'object %s', new_r_obj_url)
                             else:
-                                old_r_obj = self.api.get(r_obj_path,
-                                               tenant_uuid=tenant_uuid).json()
+                                old_r_obj = self.api.get(
+                                    r_obj_path,
+                                    tenant_uuid=self.tenant_uuid).json()
                                 new_r_obj = self.dest_api.get_object_by_name(
-                                               r_obj_type, old_r_obj['name'],
-                                               tenant_uuid=otenant_uuid)
+                                    r_obj_type, old_r_obj['name'],
+                                    tenant_uuid=self.otenant_uuid)
                                 if new_r_obj:
                                     # If object of same name exists in the
                                     # target tenant context, use this object
 
                                     logger.debug('Using identically-named '
                                                  ' object "%s"',
                                                  new_r_obj['name'])
                                     new_r_obj_url = new_r_obj['url']
                                 else:
                                     # Otherwise clone the object to the target
                                     # tenant context
 
                                     (new_r_obj, r_created_objs,
                                      r_warnings) = self.clone_object(
-                                                    old_name=r_obj_path,
-                                                    new_name=old_r_obj['name'],
-                                                    t_obj=t_obj, ot_obj=ot_obj,
-                                                    oc_obj=oc_obj,
-                                                    force_unique_name=True)
+                                        old_name=r_obj_path,
+                                        new_name=old_r_obj['name'],
+                                        force_unique_name=True)
                                     created_objs.append(new_r_obj)
                                     created_objs.extend(r_created_objs)
                                     warnings.extend(r_warnings)
                                     new_r_obj_url = new_r_obj['url']
 
                             if is_list:
                                 pobj_attr[referenced][i] = new_r_obj_url
                             else:
                                 pobj_attr[referenced] = new_r_obj_url
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we
             # have created
 
-            self._delete_created_objs(created_objs, otenant_uuid)
+            self.delete_objects(created_objs)
 
             raise
 
         return created_objs, warnings
 
     def clone_gs(self, old_gs_name, new_gs_name, enable_gs=False,
-                          new_fqdns=None, tenant=None, other_tenant=None,
-                          force_clone=None):
-
+                 new_fqdns=None, force_clone=None):
         """
         Clones a GSLB Service object
 
         Optionally creating the cloned GSLB VS in a different tenant
 
         Returns a tuple: json representation of the cloned GSLB Service,
         list of additional objects created if any
@@ -1442,81 +1505,69 @@
         if self.api != self.dest_api:
             raise Exception('Cannot clone GSLB Services to a different '
                             'Controller.')
 
         force_clone = force_clone or []
         new_fqdns = new_fqdns or ['*']
 
-        t_obj, tenant, tenant_uuid = self._get_obj_info(obj_type='tenant',
-                                                        obj_name=tenant)
-
-        other_tenant = other_tenant or tenant
-
-        ot_obj, other_tenant, otenant_uuid = self._get_obj_info(
-                                                 obj_type='tenant',
-                                                 obj_name=other_tenant,
-                                                 api_to_use=self.dest_api)
-
         if old_gs_name.startswith('gslbservice/'):
-            g_obj = self.api.get(old_gs_name, tenant_uuid=tenant_uuid).json()
+            g_obj = self.api.get(old_gs_name,
+                                 tenant_uuid=self.tenant_uuid).json()
             old_gs_name = g_obj['name']
         else:
             g_obj = self.api.get_object_by_name('gslbservice', old_gs_name,
-                                tenant_uuid=tenant_uuid)
+                                                tenant_uuid=self.tenant_uuid)
         if not g_obj:
             raise Exception('GSLB Service %s could not be found' %
                             old_gs_name)
 
         if g_obj.get('site_persistence_enabled', False):
             raise Exception('Cannot clone GSLB Service %s as it has site '
                             'persistence enabled.' % old_gs_name)
 
         created_objs = []
         warnings = []
 
         try:
             if new_fqdns == ['*']:
                 new_fqdns = ['.'.join([new_gs_name] +
-                                     g_obj['domain_names'][0].split('.')[1:])]
+                                      g_obj['domain_names'][0].split('.')[1:])]
             g_obj['domain_names'] = new_fqdns
             g_obj.pop('uuid', None)
             g_obj.pop('_last_modified', None)
             g_obj_old_url = g_obj.pop('url', None)
             g_obj['name'] = new_gs_name
             g_obj['enabled'] = enable_gs
 
             valid_ref_objects = self.VALID_GS_REF_OBJECTS
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
             new_objs, new_warnings = self._process_refs(parent_obj=g_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=None,
-                                          force_clone=force_clone)
+                                                        refs=valid_ref_objects,
+                                                        force_clone=force_clone)
 
             created_objs.extend(new_objs)
             warnings.extend(new_warnings)
 
             # Try to create the new GSLB Service (possibly in a different tenant
             # to the source)
 
-
             r = self.dest_api.post('gslbservice', g_obj,
-                                    tenant_uuid=otenant_uuid)
+                                   tenant_uuid=self.otenant_uuid)
 
             if r.status_code < 300:
                 new_gs = r.json()
                 self.actions += ['Cloned GSLB Service "%s"%s to "%s"%s' %
                                  (old_gs_name,
-                                 (' in tenant "%s"' % t_obj['name'])
-                                  if t_obj else '', new_gs_name,
-                                 (' in tenant "%s"' % ot_obj['name'])
-                                  if ot_obj else '')]
+                                  (' in tenant "%s"' % self.t_obj['name'])
+                                  if self.t_obj else '', new_gs_name,
+                                  (' in tenant "%s"' % self.ot_obj['name'])
+                                  if self.ot_obj else '')]
                 logger.debug('Created GSLB Service "%s"', new_gs['url'])
                 if g_obj_old_url:
                     self.clone_track[g_obj_old_url] = new_gs['url']
                 return new_gs, created_objs, warnings
             else:
                 exception_string = ('Unable to clone GSLB Service "%s" '
                                     'as "%s" (%d:%s)' % (old_gs_name,
@@ -1526,28 +1577,28 @@
                 logger.debug(exception_string)
                 logger.debug(g_obj)
                 raise Exception(exception_string)
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we have
             # created
 
-            self._delete_created_objs(created_objs, otenant_uuid)
+            self.delete_objects(created_objs)
 
             #logger.debug('Exception occurred', exc_info=ex)
 
             raise Exception('%s\r\n=> Unable to clone GSLB Service "%s" '
                             'as "%s"' % (ex, old_gs_name, new_gs_name))
 
     def clone_vs(self, old_vs_name, new_vs_name, enable_vs=False,
                  new_vs_vips=None, new_vs_v6vips=None, new_vs_fips=None,
-                 new_fqdns=None, new_segroup=None, tenant=None,
-                 other_tenant=None, other_cloud=None, force_clone=None,
-                 use_internal_ipam=False, server_map=None,
-                 new_parent=None):
-
+                 new_fqdns=None, new_segroup=None,
+                 force_clone=None, vs_flags=None,
+                 new_parent=None, vh_type=None,
+                 manual_vsvip=None,
+                 new_vs_placements=None):
         """
         Clones a Virtual Service object
 
         Optionally creating the cloned VS in a different tenant and/or a
         different cloud.
 
         Returns a tuple: json representation of the cloned Virtual Service,
@@ -1568,348 +1619,508 @@
         :param new_vs_fips: List of FIPs for cloned VS or [None] if FIPs are
                             not used (must have same number of elements as
                             new_vs_vips if specified)
         :param new_fqdns: List of FQDNs for cloned VS or ['*'] to derive FQDN
                             from new_vs_name and domain name in original VS
         :param new_segroup: SE Group to be used by cloned VS or None to use SE
                             group with same name as used by source VS
-        :param tenant: Tenant for existing VS (if not specfied, use user's
-                        default tenant)
-        :param other_tenant: Tenant for cloned VS (if not specified, clone to
-                                same tenant as source)
-        :param other_cloud: Cloud for cloned VS (if not specified, clone to
-                            same cloud as source)
         :param force_clone: List of referenced object attributes to forcibly
                             clone rather than re-use (for example
                             health_monitor_refs)
-        :param use_internal_ipam: When auto-allocating from different subnets
-                                  than the source VS, allocate from internal
-                                  Avi IPAM/Infoblox - should be False for clouds
-                                  where allocation comes from cloud itself, e.g.
-                                  OpenStack, public clouds
-        :param server_map: List of tuple pairs of server IPs to map between for
-                           pool member replacement
+        :param vs_flags: Dictionary of boolean or tristate flags
+                         use_internal_ipam: bool - Populate internal_ipam fields
+                            for auto-allocation
+                         scaleout_ecmp: tristate - enable/disable scaleout_ecmp
+                            with None implying preserve setting from source
+                         enable_rhi: tristate - enable/disable enable_rhi with
+                            None implying preserve setting from source
         :param new_parent: When cloning an SNI child VS, specifies a different
                            VS name to be a parent for the cloned child VS
+        :param vh_type: Specifies Virtual Hosting type for cloned VS, valid
+                        values are sni_parent, sni_child, evh_parent, evh_child
+                        or no_vh
+        :param manual_vsvip: Specifies an existing VsVip to attach to the cloned
+                             Virtual Service
+        :param new_vs_placements: Specifies the placement network(s) for
+                                  the VsVip
         :return: tuple - json representation of the cloned VS object, list of
                     additional objects created if any
         :rtype: tuple
         """
 
         # Lookup source and destination tenant and destination cloud if
         # specified
 
         logger.debug('Cloning Virtual Service "%s" to "%s"',
                      old_vs_name, new_vs_name)
 
         force_clone = force_clone or []
+        vs_flags = vs_flags or {}
+
+        use_internal_ipam = vs_flags.get('use_internal_ipam', False)
+        scaleout_ecmp = vs_flags.get('scaleout_ecmp', None)
+        enable_rhi = vs_flags.get('enable_rhi', None)
+
         new_vs_vips = new_vs_vips or ([None * len(new_vs_v6vips)]
                                       if new_vs_v6vips else ['*'])
         new_vs_fips = new_vs_fips or [None * len(new_vs_vips)]
         new_vs_v6vips = new_vs_v6vips or [None * len(new_vs_vips)]
+        new_vs_placements = new_vs_placements or [None * len(new_vs_vips)]
         new_fqdns = new_fqdns or ['*']
 
-        t_obj, tenant, tenant_uuid = self._get_obj_info(obj_type='tenant',
-                                                        obj_name=tenant)
-
-        other_tenant = other_tenant or tenant
-
-        ot_obj, other_tenant, otenant_uuid = self._get_obj_info(
-                                                 obj_type='tenant',
-                                                 obj_name=other_tenant,
-                                                 api_to_use=self.dest_api)
-
-        oc_obj, other_cloud, ocloud_uuid = self._get_obj_info(obj_type='cloud',
-                                                 obj_name=other_cloud,
-                                                 api_to_use=self.dest_api,
-                                                 tenant_uuid=otenant_uuid)
-
         if new_vs_fips != [None] and len(new_vs_vips) != len(new_vs_fips):
             raise Exception('Cannot clone Virtual Service if number of VIPs '
                             'and number of FIPs is not equal')
 
         if old_vs_name.startswith('virtualservice/'):
-            v_obj = self.api.get(old_vs_name, tenant_uuid=tenant_uuid).json()
+            v_obj = self.api.get(old_vs_name,
+                                 tenant_uuid=self.tenant_uuid).json()
             old_vs_name = v_obj['name']
         else:
             v_obj = self.api.get_object_by_name('virtualservice', old_vs_name,
-                                tenant_uuid=tenant_uuid)
+                                                tenant_uuid=self.tenant_uuid)
         if not v_obj:
             raise Exception('Virtual Service %s could not be found' %
                             old_vs_name)
 
+
         is_child_vs = (v_obj['type'] == 'VS_TYPE_VH_CHILD')
+        is_evh_vs = (v_obj['type'] != 'VS_TYPE_NORMAL' and
+                     v_obj['vh_type'] == 'VS_TYPE_VH_ENHANCED')
+
+        created_objs = []
+        warnings = []
+
+        if vh_type:
+            if (vh_type in ('sni_parent', 'evh_parent', 'no_vh')
+                and is_child_vs and not(manual_vsvip)):
+                raise Exception('Existing VsVip must be specified in order to '
+                                'clone a child VS to a parent/non-VH VS')
+            if (vh_type in ('sni_child', 'ech_child') and not(is_child_vs)
+                and not(new_parent)):
+                raise Exception('Parent Virtual Service must be specified')
+            if vh_type == 'sni_parent':
+                v_obj['vh_type'] = 'VS_TYPE_VH_SNI'
+                v_obj['type'] = 'VS_TYPE_VH_PARENT'
+                v_obj.pop('vh_parent_vs_ref', None)
+                v_obj.pop('vh_domain_name', None)
+                is_child_vs = False
+                is_evh_vs = False
+            elif vh_type == 'evh_parent':
+                v_obj['vh_type'] = 'VS_TYPE_VH_ENHANCED'
+                v_obj['type'] = 'VS_TYPE_VH_PARENT'
+                v_obj.pop('vh_parent_vs_ref', None)
+                v_obj.pop('vh_domain_name', None)
+                is_child_vs = False
+                is_evh_vs = True
+            elif vh_type == 'sni_child':
+                v_obj['vh_type'] = 'VS_TYPE_VH_SNI'
+                v_obj['type'] = 'VS_TYPE_VH_CHILD'
+                v_obj.pop('vsvip_ref', None)
+                v_obj.pop('services', None)
+                if is_child_vs and is_evh_vs:
+                    # Set SNI hostname from first EVH host rule
+                    v_obj['vh_domain_name'] = [v_obj['vh_matches'][0]['host']]
+                    v_obj.pop('vh_matches', None)
+                    warnings.append('Mapped host from first EVH match rule to '
+                                    'SNI hostame.')
+                is_child_vs = True
+                is_evh_vs = False
+                if v_obj.pop('network_security_policy_ref', None):
+                    warnings.append('Removed network security policy from '
+                                    'child VS.')
+            elif vh_type == 'evh_child':
+                v_obj['vh_type'] = 'VS_TYPE_VH_ENHANCED'
+                v_obj['type'] = 'VS_TYPE_VH_CHILD'
+                v_obj.pop('vsvip_ref', None)
+                v_obj.pop('services', None)
+                if is_child_vs and not is_evh_vs:
+                    # Set EVH rule from SNI hostname and remove SSL config
+                    v_obj['vh_matches']=[{'host': v_obj['vh_domain_name'][0],
+                                          'rules': [{
+                                              'name': 'All paths',
+                                              'matches': {
+                                                'path': {
+                                                    'match_criteria':
+                                                        'BEGINS_WITH',
+                                                    'match_case':
+                                                        'INSENSITIVE',
+                                                    'match_str': ['/'],
+                                                    'match_decoded_string':
+                                                        True}
+                                                }
+                                              }]
+                                          }]
+                    warnings.append('Mapped SNI Hostname to EVH match rule.')
+                if v_obj.pop('ssl_profile_ref', None):
+                    v_obj.pop('ssl_key_and_certificate_refs', None)
+                    v_obj.pop('vh_domain_name', None)
+                    warnings.append('You may need to attach correct certificate'
+                                    ' to EVH parent VS.')
+                if v_obj.pop('network_security_policy_ref', None):
+                    warnings.append('Removed network security policy from '
+                                    'child VS.')
+                is_child_vs = True
+                is_evh_vs = True
+            elif vh_type == 'no_vh':
+                v_obj['type'] = 'VS_TYPE_NORMAL'
+                v_obj.pop('vh_parent_vs_ref', None)
+                v_obj.pop('vh_domain_name', None)
+                is_child_vs = False
+                is_evh_vs = False
+            if not(is_child_vs) and not('services' in v_obj):
+                if 'ssl_profile_ref' in v_obj:
+                    v_obj['services'] = [{'port': '443', 'enable_ssl': 'true'}]
+                    warnings.append('Check service ports for cloned VS. '
+                                    'Defaulted to using port 443:SSL')
+                else:
+                    v_obj['services'] = [{'port': '80', 'enable_ssl': 'false'}]
+                    warnings.append('Check service ports for cloned VS. '
+                                    'Defaulted to using port 80:NoSSL')
 
         if is_child_vs:
-            logger.debug('Source Virtual Service is an SNI child VS')
+            logger.debug('Source Virtual Service is an SNI/EVH child VS')
+            v_obj.pop('vrf_context_ref', None)
 
         c_obj = self.api.get(v_obj['cloud_ref'].split('/api/')[1],
-                             tenant_uuid=tenant_uuid).json()
-
-        created_objs = []
-        warnings = []
+                             tenant_uuid=self.tenant_uuid).json()
 
         try:
             # Allocate new VIPs. If auto-allocating then remove existing IP
             # addresses and allow auto_allocate_ip to do the work. Otherwise
             # build a new array of VIPs.
 
-            if v_obj.get('vsvip_ref', None):
-                # vsvip object is used
+            if is_child_vs:
+                # VS is a child VS
+                if new_parent:
+                    pvs_obj = self.dest_api.get_object_by_name(
+                        'virtualservice', new_parent,
+                        tenant_uuid=self.otenant_uuid)
+                    if pvs_obj:
+                        v_obj['vh_parent_vs_ref'] = pvs_obj['url']
+                    else:
+                        raise Exception('Unable to locate parent VS "%s"%s' %
+                                        (new_parent, (' in tenant "%s"' %
+                                                      self.other_tenant) if
+                                         self.other_tenant else ''))
+                vsvip_obj = None
+            elif manual_vsvip:
+                vsvip_obj = self.dest_api.get_object_by_name(
+                    'vsvip', manual_vsvip, tenant_uuid=self.otenant_uuid)
+                if not(vsvip_obj):
+                    raise Exception('Unable to locate VsVip "%s"'
+                                    % manual_vsvip)
+                logger.debug('Trying to use existing VsVip "%s":%s' %
+                             (manual_vsvip, vsvip_obj['uuid']))
+            else:
 
                 new_vsvip_name = 'vsvip-%s-%s' % (new_vs_name,
-                                                  other_cloud if other_cloud
-                                                  else c_obj['name'])
+                                                self.other_cloud if
+                                                self.other_cloud
+                                                else c_obj['name'])
 
                 new_vsvip_name = self.get_new_name('vsvip', new_vsvip_name,
-                                                   otenant_uuid, True)
+                                                force_unique_name=True)
 
                 vsvip_obj = self.api.get(
-                                v_obj['vsvip_ref'].split('/api/')[1],
-                                tenant_uuid=tenant_uuid).json()
+                    v_obj['vsvip_ref'].split('/api/')[1],
+                    tenant_uuid=self.tenant_uuid).json()
 
                 vsvip_obj.pop('uuid', None)
                 vsvip_obj.pop('_last_modified', None)
                 vsvip_obj.pop('url', None)
                 vsvip_obj['name'] = new_vsvip_name
-                if oc_obj:
-                    vsvip_obj['cloud_ref'] = oc_obj['url']
                 v_obj.pop('vip', None)
                 v_obj.pop('dns_info', None)
                 v_obj.pop('east_west_placement', None)
                 v_obj.pop('vsvip_ref', None)
-            else:
-                # No vsvip object (version < 17.1) - only a single VIP is
-                # supported so VIP is in Virtual Service object and there
-                # is only one
-
-                vsvip_obj = None
 
-            if is_child_vs:
-                # VS is a child VS
-                if new_parent:
-                    pvs_obj = self.dest_api.get_object_by_name(
-                                                   'virtualservice', new_parent,
-                                                   tenant_uuid=otenant_uuid)
-                    if pvs_obj:
-                        v_obj['vh_parent_vs_ref'] = pvs_obj['url']
-                    else:
-                        raise Exception('Unable to locate parent VS "%s"%s' %
-                                        (new_parent, (' in tenant "%s"' %
-                                         other_tenant) if other_tenant else ''))
-            elif new_vs_vips == ['*']:
-                # Use auto-allocation from the same subnets as the source
-                # VS (IPv4 and IPv6)
-
-                for vip in vsvip_obj['vip'] if vsvip_obj else [v_obj]:
-                    vip.pop('port_uuid', None)
-                    vip.pop('discovered_networks', None)
-                    if 'ipam_network_subnet' in vip:
-                        vip['ipam_network_subnet'].pop('network_ref', None)
-                    if vip['auto_allocate_ip'] is True:
-                        vip.pop('ip_address', None)
-                        vip.pop('ip6_address', None)
-                    else:
-                        raise Exception('Existing VS does not have '
-                                        'auto-allocate enabled')
-                    if vip['auto_allocate_floating_ip'] is True:
-                        vip.pop('floating_ip', None)
-            else:
-                # Update VIPs in destination VS
+                if new_vs_vips == ['*']:
+                    # Use auto-allocation from the same subnets as the source
+                    # VS (IPv4 and IPv6)
+
+                    for vip in vsvip_obj['vip']:
+                        vip.pop('port_uuid', None)
+                        vip.pop('discovered_networks', None)
+                        if 'ipam_network_subnet' in vip:
+                            vip['ipam_network_subnet'].pop('network_ref', None)
+                        if vip['auto_allocate_ip'] is True:
+                            vip.pop('ip_address', None)
+                            vip.pop('ip6_address', None)
+                        else:
+                            raise Exception('Existing VS does not have '
+                                            'auto-allocate enabled')
+                        if vip['auto_allocate_floating_ip'] is True:
+                            vip.pop('floating_ip', None)
+                else:
+                    # Update VIPs in destination VS
 
-                if len(new_vs_vips) != len(new_vs_v6vips):
-                    raise Exception('Number of V4 and V6 VIPs should match.')
+                    if len(new_vs_vips) != len(new_vs_v6vips):
+                        raise Exception('Number of V4 and V6 VIPs should match.')
 
-                if vsvip_obj:
                     vsvip_obj['vip'] = []
                     for c, (new_vs_vip,
                             new_vs_fip,
-                            new_vs_v6vip) in enumerate(zip(new_vs_vips,
-                                                           new_vs_fips,
-                                                           new_vs_v6vips)):
+                            new_vs_v6vip,
+                            new_vs_placement) in enumerate(zip(new_vs_vips,
+                                                            new_vs_fips,
+                                                            new_vs_v6vips,
+                                                            new_vs_placements)):
+                        # For multi-VIPs, allow any of V4, V6 or Floating VIP
+                        # or placement network to be omitted (specified as '-')
+
+                        if new_vs_vip == '-':
+                            new_vs_vip = None
+                        if new_vs_v6vip == '-':
+                            new_vs_v6vip = None
+                        if new_vs_fip == '-':
+                            new_vs_fip = None
+                        if new_vs_placement == '-':
+                            new_vs_placement = None
+
                         new_vip = {'enabled': True,
-                                   'vip_id': str(c+1)}
+                                'vip_id': str(c+1)}
                         if new_vs_vip:
                             if '/' in new_vs_vip:
                                 # New VIP is a subnet for auto-allocation
 
                                 new_vip['auto_allocate_ip'] = True
                                 subnet = new_vs_vip.split('/')
                                 subnet_uuid = (subnet[2] if len(subnet) > 2
-                                               else None)
+                                            else None)
                                 if use_internal_ipam:
                                     new_vip['ipam_network_subnet'] = {
                                         'subnet': {
                                             'ip_addr': {
                                                 'type': 'V4',
                                                 'addr': subnet[0]},
                                             'mask': int(subnet[1])}}
                                     if subnet_uuid:
                                         new_vip['ipam_network_subnet'][
-                                                    'subnet_uuid'] = subnet_uuid
+                                            'subnet_uuid'] = subnet_uuid
                                 else:
                                     new_vip['subnet'] = {
                                         'ip_addr': {'type': 'V4',
                                                     'addr': subnet[0]},
                                         'mask': int(subnet[1])}
                                     if subnet_uuid:
                                         new_vip['subnet_uuid'] = subnet_uuid
                             else:
                                 # New VIP is an individual IP so do not
                                 # do auto-allocation
 
                                 new_vip['auto_allocate_ip'] = False
                                 new_vip['ip_address'] = {'type': 'V4',
-                                                         'addr': new_vs_vip}
+                                                        'addr': new_vs_vip}
                         if new_vs_v6vip:
                             if '/' in new_vs_v6vip:
                                 # New VIP is a subnet for auto-allocation
 
                                 new_vip['auto_allocate_ip'] = True
                                 new_vip['auto_allocate_ip_type'] = (
                                     'V4_V6' if new_vs_vip else 'V6_ONLY')
 
                                 subnet = new_vs_v6vip.split('/')
                                 subnet_uuid = (subnet[2] if len(subnet) > 2
-                                               else None)
+                                            else None)
                                 if use_internal_ipam:
                                     new_vip['ipam_network_subnet'] = {
                                         'subnet6': {
                                             'ip_addr': {
                                                 'type': 'V6',
                                                 'addr': subnet[0]},
                                             'mask': int(subnet[1])}}
                                     if subnet_uuid:
                                         new_vip['ipam_network_subnet'][
-                                                   'subnet6_uuid'] = subnet_uuid
+                                            'subnet6_uuid'] = subnet_uuid
                                 else:
 
                                     new_vip['subnet6'] = {
                                         'ip_addr': {'type': 'V6',
                                                     'addr': subnet[0]},
                                         'mask': int(subnet[1])}
                                     if subnet_uuid:
                                         new_vip['subnet6_uuid'] = subnet_uuid
                             else:
                                 # New VIP is an individual IP so do not
                                 # do auto-allocation
 
                                 new_vip['auto_allocate_ip'] = False
                                 new_vip['ip6_address'] = {'type': 'V6',
-                                                         'addr': new_vs_v6vip}
+                                                        'addr': new_vs_v6vip}
 
                         if new_vs_fip:
                             if new_vs_fip == '*':
                                 new_vip['auto_allocate_floating_ip'] = True
                             else:
                                 new_vip['auto_allocate_floating_ip'] = False
                                 new_vip['floating_ip'] = {
                                     'type': 'V4',
                                     'addr': new_vs_fip}
                         else:
                             new_vip['auto_allocate_floating_ip'] = False
 
-                        vsvip_obj['vip'].append(new_vip)
-                else:
-                    if '/' in new_vs_vips[0]:
-                        # New VIP is a subnet for auto-allocation
+                        if new_vs_placement:
+                            placement_networks = []
+                            for vs_placement_data in new_vs_placement.split(';'):
+                                vs_placement_data_split = vs_placement_data.split(
+                                    '/')
+                                placement_network = {}
+                                if len(vs_placement_data_split) == 6:
+                                    (network, subnet, mask,
+                                     subnet6, mask6) = vs_placement_data_split
+                                elif len(vs_placement_data_split) == 3:
+                                    # Placement data is network/subnet/mask
+                                    (network, subnet,
+                                     mask) = vs_placement_data_split
+                                    subnet6 = None
+                                    mask6 = None
+                                elif len(vs_placement_data_split) == 2:
+                                    # Placement data is subnet/mask only
+                                    subnet, mask = vs_placement_data_split
+                                    subnet6 = None
+                                    mask6 = None
+                                    network = None
+                                else:
+                                    raise('Unable to parse placement network '
+                                          'info "%s".' % vs_placement_data)
+                                if network:
+                                    (n_obj, n_name, n_uuid) = self._get_obj_info(
+                                        obj_type='network',
+                                        obj_name=network,
+                                        api_to_use=self.dest_api,
+                                        cloud_uuid=self.ocloud_uuid or c_obj['uuid'])
+                                    if n_obj:
+                                        placement_network['network_ref'] = n_obj['url']
+                                    else:
+                                        raise('Unable to find referenced placement '
+                                            'network "%s" in the cloud.'
+                                            % network)
+                                if subnet6:
+                                    placement_network['subnet'] = {
+                                            'ip_addr': {
+                                                'type': 'V4',
+                                                'addr': subnet
+                                            },
+                                            'mask': mask
+                                        }
+                                    placement_network['subnet6'] = {
+                                            'ip_addr': {
+                                                'type': 'V6',
+                                                'addr': subnet6
+                                            },
+                                            'mask': mask6
+                                        }
+                                else:
+                                    if ':' in subnet:
+                                        placement_network['subnet6'] = {
+                                            'ip_addr': {
+                                                'type': 'V6',
+                                                'addr': subnet
+                                            },
+                                            'mask': mask
+                                        }
+                                    else:
+                                        placement_network['subnet'] = {
+                                            'ip_addr': {
+                                                'type': 'V4',
+                                                'addr': subnet
+                                            },
+                                            'mask': mask
+                                        }
 
-                        v_obj['auto_allocate_ip'] = True
-                        subnet = new_vs_vips[0].split('/')
-                        subnet_uuid = subnet[2] if len(subnet) > 2 else None
-                        v_obj.pop('subnet_uuid', None)
-                        if use_internal_ipam:
-                            v_obj['ipam_network_subnet'] = {'subnet': {
-                                           'ip_addr': {'type': 'V4',
-                                                       'addr': subnet[0]},
-                                           'mask': int(subnet[1])}}
-                            if subnet_uuid:
-                                v_obj['ipam_network_subnet'][
-                                    'subnet_uuid'] = subnet_uuid
-                        else:
-                            v_obj['subnet'] = {'ip_addr': {'type': 'V4',
-                                                           'addr': subnet[0]},
-                                               'mask': int(subnet[1])}
-                            if subnet_uuid:
-                                v_obj['subnet_uuid'] = subnet_uuid
-                        v_obj.pop('network_ref', None)
-                        v_obj.pop('ip_address', None)
-                        v_obj.pop('port_uuid', None)
-                    else:
-                        # New VIP is an individual IP so do not
-                        # do auto-allocation
+                                placement_networks.append(placement_network)
 
-                        v_obj['auto_allocate_ip'] = False
-                        v_obj['ip_address'] = {'type': 'V4',
-                                               'addr': new_vs_vips[0]}
-                    if new_vs_fips[0]:
-                        if new_vs_fips[0] == '*':
-                            v_obj['auto_allocate_floating_ip'] = True
-                        else:
-                            v_obj['auto_allocate_floating_ip'] = False
-                            v_obj['floating_ip'] = {'type': 'V4',
-                                                    'addr': new_vs_fips[0]}
-                    else:
-                        v_obj['auto_allocate_floating_ip'] = False
+                            new_vip['placement_networks'] = placement_networks
 
-                    v_obj.pop('discovered_networks', None)
+                        vsvip_obj['vip'].append(new_vip)
 
             # Allocate new FQDNs or create a single FQDN derived from the first
             # FQDN, replacing the hostname part with the new VS name
 
-            dns_info_obj = vsvip_obj or v_obj
-
             if new_fqdns == ['*']:
                 if is_child_vs:
                     new_fqdn = (new_vs_name + '.' +
                                 v_obj['vh_domain_name'][0].split('.', 1)[1])
-                    v_obj['vh_domain_name'][0] = new_fqdn
-                elif 'dns_info' in dns_info_obj:
+                    if is_evh_vs:
+                        v_obj['vh_matches']=[{'host': new_fqdn,
+                        'rules': [{
+                            'name': 'All paths',
+                            'matches': {
+                            'path': {
+                                'match_criteria':
+                                    'BEGINS_WITH',
+                                'match_case':
+                                    'INSENSITIVE',
+                                'match_str': ['/'],
+                                'match_decoded_string':
+                                    True}
+                            }
+                            }]
+                        }]
+                    else:
+                      v_obj['vh_domain_name'] = [new_fqdn]
+                elif 'dns_info' in vsvip_obj:
                     new_fqdn = (new_vs_name + '.' +
-                                dns_info_obj['dns_info'][0]['fqdn'].split(
-                                                                     '.', 1)[1])
-                    dns_info_obj['dns_info'] = [{'type': 'DNS_RECORD_A',
-                                           'fqdn': new_fqdn}]
+                                vsvip_obj['dns_info'][0]['fqdn'].split(
+                                    '.', 1)[1])
+                    vsvip_obj['dns_info'] = [{'type': 'DNS_RECORD_A',
+                                              'fqdn': new_fqdn}]
             else:
                 if new_fqdns != [None]:
                     if is_child_vs:
-                        v_obj['vh_domain_name'][0] = new_fqdns[0]
+                        if is_evh_vs:
+                            v_obj['vh_matches']=[{'host': new_fqdns[0],
+                            'rules': [{
+                                'name': 'All paths',
+                                'matches': {
+                                'path': {
+                                    'match_criteria':
+                                        'BEGINS_WITH',
+                                    'match_case':
+                                        'INSENSITIVE',
+                                    'match_str': ['/'],
+                                    'match_decoded_string':
+                                        True}
+                                }
+                                }]
+                            }]
+                        else:
+                            v_obj['vh_domain_name'] = new_fqdns
                     else:
-                        dns_info_obj['dns_info'] = [{'type': 'DNS_RECORD_A',
-                                    'fqdn': new_fqdn} for new_fqdn in new_fqdns]
-                else:
-                    dns_info_obj.pop('dns_info', None)
+                        vsvip_obj['dns_info'] = [{'type': 'DNS_RECORD_A',
+                                                  'fqdn': new_fqdn} for new_fqdn in new_fqdns]
+                elif vsvip_obj:
+                    vsvip_obj.pop('dns_info', None)
 
             # Clone the pool/pool group used by the VS
 
             if 'pool_ref' in v_obj:
                 p_path = v_obj['pool_ref'].split('/api/')[1]
                 p_name = '-'.join([new_vs_name, 'pool'])
 
                 p_obj, p_created_objs, p_warnings = self.clone_object(
-                    old_name=p_path, new_name=p_name, t_obj=t_obj,
-                    ot_obj=ot_obj, oc_obj=oc_obj, force_clone=force_clone,
-                    force_unique_name=True, server_map=server_map)
+                    old_name=p_path, new_name=p_name,
+                    force_clone=force_clone, force_unique_name=True)
 
                 created_objs.append(p_obj)
                 created_objs.extend(p_created_objs)
                 warnings.extend(p_warnings)
 
                 # Update the pool with the cloned pool
 
                 v_obj['pool_ref'] = p_obj['url']
 
             if 'pool_group_ref' in v_obj:
                 pg_path = v_obj['pool_group_ref'].split('/api/')[1]
                 pg_name = '-'.join([new_vs_name, 'poolgroup'])
 
                 pg_obj, pg_created_objs, pg_warnings = self.clone_object(
-                    old_name=pg_path, new_name=pg_name, t_obj=t_obj,
-                    ot_obj=ot_obj, oc_obj=oc_obj, force_clone=force_clone,
-                    force_unique_name=True, server_map=server_map)
+                    old_name=pg_path, new_name=pg_name,
+                    force_clone=force_clone, force_unique_name=True)
 
                 created_objs.append(pg_obj)
                 created_objs.extend(pg_created_objs)
                 warnings.extend(pg_warnings)
 
                 # Update the pool group with the cloned pool group
 
@@ -1918,60 +2129,78 @@
             # Remove unique atributes and rename
 
             v_obj.pop('uuid', None)
             v_obj.pop('_last_modified', None)
             v_obj_old_url = v_obj.pop('url', None)
             v_obj.pop('vip_runtime', None)
             v_obj['name'] = new_vs_name
+            v_obj.pop('network_ref', None)
 
             # Remove site persistency references
 
             if v_obj.pop('sp_pool_refs', None):
                 warnings.append('VS was linked to a GSLB Service with site '
                                 'persistency. Linkage removed in cloned VS.')
 
+            # Set VS flags
+            if scaleout_ecmp is not None:
+                v_obj['scaleout_ecmp'] = scaleout_ecmp
+            if enable_rhi is not None:
+                v_obj['enable_rhi'] = enable_rhi
+
             # Fixup SAML configuration
 
             if 'saml_sp_config' in v_obj:
                 v_obj['saml_sp_config'].pop('sp_metadata', None)
                 warnings.append('VS has a SAML configuration that will need to '
                                 'be manually updated.')
 
-            # (Try to!) move the new Virtual Service to a different cloud
+            # (Try to!) move the new Virtual Service and VsVip
+            # to a different cloud
 
-            if oc_obj:
-                v_obj['cloud_ref'] = oc_obj['url']
+            if self.oc_obj:
+                v_obj['cloud_ref'] = self.oc_obj['url']
+                if vsvip_obj:
+                    vsvip_obj['cloud_ref'] = self.oc_obj['url']
                 v_obj.pop('cloud_type', None)
 
                 # If moving to a different cloud and a new SE group is not
                 # specified, try to find an SE group
                 # with the same name as the source Virtual Service's SE group
 
                 if new_segroup is None:
                     seg_obj = self.api.get(
-                                v_obj['se_group_ref'].split('/api/')[1],
-                                tenant_uuid=tenant_uuid).json()
+                        v_obj['se_group_ref'].split('/api/')[1],
+                        tenant_uuid=self.tenant_uuid).json()
                     new_segroup = seg_obj['name']
 
                 # If moving to a different cloud, Virtual Service will be moved
-                # to the default global VRF in the target cloud
-
-                v_obj.pop('vrf_context_ref', None)
+                # to the default global VRF in the target cloud unless a
+                # specific target VRF is specified.
                 if vsvip_obj:
                     vsvip_obj.pop('vrf_context_ref', None)
+                    vsvip_obj.pop('tier1_lr', None)
+
+            # Update VRF or T1_LR reference if a target VRF is specified
+            if vsvip_obj:
+                if self.ov_obj:
+                    vsvip_obj['vrf_context_ref'] = self.ov_obj['url']
+                elif self.other_vrf:
+                    # Case where target is NSX-T Cloud with overlay
+                    vsvip_obj['tier1_lr'] = self.other_vrf
 
-            if new_segroup is not None:
+            if new_segroup:
                 # Locate SE group by name in the appropriate cloud
 
-                cloud_url = c_obj['url'] if oc_obj is None else oc_obj['url']
+                cloud_url = self.oc_obj['url'] if self.oc_obj else c_obj['url']
 
                 new_seg_objs = self.get_all_objects_by_name(
-                                'serviceenginegroup', new_segroup,
-                                tenant_uuid=otenant_uuid,
-                                api_to_use=self.dest_api)
+                    'serviceenginegroup', new_segroup,
+                    tenant_uuid=self.otenant_uuid,
+                    api_to_use=self.dest_api)
 
                 new_seg_obj = [new_seg_obj for new_seg_obj in new_seg_objs if
                                new_seg_obj['cloud_ref'] == cloud_url]
 
                 # If can't find an SE group with matching name, raise an error
 
                 try:
@@ -1985,80 +2214,77 @@
             # Clone any HTTP policy sets referenced in the VS
 
             if 'http_policies' in v_obj:
                 for polset in v_obj['http_policies']:
                     ps_path = polset['http_policy_set_ref'].split('/api/')[1]
                     ps_name = '-'.join([new_vs_name,
                                         (c_obj['name']
-                                         if oc_obj is None
-                                         else oc_obj['name']),
+                                         if self.oc_obj is None
+                                         else self.oc_obj['name']),
                                         'HTTP-Policy-Set'])
                     ps_obj, ps_created_objs, ps_warnings = self.clone_object(
-                        old_name=ps_path, new_name=ps_name, t_obj=t_obj,
-                        ot_obj=ot_obj, oc_obj=oc_obj, force_clone=force_clone,
-                        force_unique_name=True, server_map=server_map)
+                        old_name=ps_path, new_name=ps_name,
+                        force_clone=force_clone, force_unique_name=True)
 
                     polset['http_policy_set_ref'] = ps_obj['url']
                     created_objs.append(ps_obj)
                     created_objs.extend(ps_created_objs)
                     warnings.extend(ps_warnings)
 
             # Clone any DNS policy sets referenced in the VS
 
             if 'dns_policies' in v_obj:
                 for polset in v_obj['dns_policies']:
                     ps_path = polset['dns_policy_ref'].split('/api/')[1]
                     ps_name = '-'.join([new_vs_name,
                                         (c_obj['name']
-                                         if oc_obj is None
-                                         else oc_obj['name']),
+                                         if self.oc_obj is None
+                                         else self.oc_obj['name']),
                                         'DNS-Policy'])
                     ps_obj, ps_created_objs, ps_warnings = self.clone_object(
-                        old_name=ps_path, new_name=ps_name, t_obj=t_obj,
-                        ot_obj=ot_obj, oc_obj=oc_obj, force_clone=force_clone,
-                        force_unique_name=True, server_map=server_map)
+                        old_name=ps_path, new_name=ps_name,
+                        force_clone=force_clone, force_unique_name=True)
 
                     polset['dns_policy_ref'] = ps_obj['url']
                     created_objs.append(ps_obj)
                     created_objs.extend(ps_created_objs)
                     warnings.extend(ps_warnings)
 
             # Clone network security policy referenced in the VS
 
             if 'network_security_policy_ref' in v_obj:
-                ns_path = v_obj['network_security_policy_ref'].split('/api/')[1]
+                ns_path = v_obj['network_security_policy_ref'].split(
+                    '/api/')[1]
                 ns_name = '-'.join(['vs', new_vs_name,
                                     (c_obj['name']
-                                         if oc_obj is None
-                                         else oc_obj['name']),
-                                        'ns'])
+                                     if self.oc_obj is None
+                                     else self.oc_obj['name']),
+                                    'ns'])
                 ns_obj, ns_created_objs, ns_warnings = self.clone_object(
-                        old_name=ns_path, new_name=ns_name, t_obj=t_obj,
-                        ot_obj=ot_obj, oc_obj=oc_obj, force_clone=force_clone,
-                        force_unique_name=True, server_map=server_map)
+                    old_name=ns_path, new_name=ns_name,
+                    force_clone=force_clone, force_unique_name=True)
 
                 v_obj['network_security_policy_ref'] = ns_obj['url']
                 created_objs.append(ns_obj)
                 created_objs.extend(ns_created_objs)
                 warnings.extend(ns_warnings)
 
             # Clone any datascripts referenced in the VS unless reuseds flag
             # is true.
 
             if 'vs_datascripts' in v_obj and 'reuseds' not in self.flags:
                 for dsset in v_obj['vs_datascripts']:
                     ds_path = dsset['vs_datascript_set_ref'].split('/api/')[1]
                     ds_name = '-'.join([new_vs_name, (c_obj['name']
-                                                      if oc_obj is None
-                                                      else oc_obj['name']),
+                                                      if self.oc_obj is None
+                                                      else self.oc_obj['name']),
                                         'DataScript-Set'])
                     ds_obj, ds_created_objs, ds_warnings = self.clone_object(
-                        old_name=ds_path, new_name=ds_name, t_obj=t_obj,
-                        ot_obj=ot_obj, oc_obj=oc_obj, force_clone=force_clone,
-                        force_unique_name=True, server_map=server_map)
+                        old_name=ds_path, new_name=ds_name,
+                        force_clone=force_clone, force_unique_name=True)
 
                     dsset['vs_datascript_set_ref'] = ds_obj['url']
 
                     created_objs.append(ds_obj)
                     created_objs.extend(ds_created_objs)
                     warnings.extend(ds_warnings)
 
@@ -2071,62 +2297,65 @@
 
             valid_ref_objects = self.VALID_VS_REF_OBJECTS
 
             # Process generic references, re-using or cloning referenced
             # objects as necessary
 
             new_objs, new_warnings = self._process_refs(parent_obj=v_obj,
-                                          refs=valid_ref_objects,
-                                          t_obj=t_obj, ot_obj=ot_obj,
-                                          oc_obj=oc_obj,
-                                          force_clone=force_clone)
+                                                        refs=valid_ref_objects,
+                                                        force_clone=force_clone)
 
             created_objs.extend(new_objs)
             warnings.extend(new_warnings)
 
-            # Create new vsvip object if needed
-
             if vsvip_obj:
-                r = self.dest_api.post('vsvip', vsvip_obj,
-                                       tenant_uuid=otenant_uuid)
-                if r.status_code < 300:
-                    new_vsvip_obj = r.json()
-                    logger.debug('Created vsvip "%s"', new_vsvip_obj['url'])
+                if manual_vsvip:
+                    v_obj['vsvip_ref'] = vsvip_obj['url']
                 else:
-                    exception_string = ('Unable to create vsvip "%s" (%d:%s)'
-                                        % (vsvip_obj['name'], r.status_code,
-                                        r.text))
-                    logger.debug(exception_string)
-                    logger.debug(vsvip_obj)
-                    raise Exception(exception_string)
-                created_objs.append(new_vsvip_obj)
-                self.actions += ['Cloned vsvip "%s"%s'
-                                 % (new_vsvip_obj['name'],
-                                    (' in tenant "%s"' % other_tenant)
-                                    if other_tenant else '')]
-                v_obj['vsvip_ref'] = new_vsvip_obj['url']
-            else:
-                new_vsvip_obj = None
+                    # Create new vsvip object
+
+                    r = self.dest_api.post('vsvip', vsvip_obj,
+                                        tenant_uuid=self.otenant_uuid)
+                    if r.status_code < 300:
+                        new_vsvip_obj = r.json()
+                        logger.debug('Created vsvip "%s"', new_vsvip_obj['url'])
+                    else:
+                        exception_string = ('Error creating vsvip "%s" (%d:%s)'
+                                            % (vsvip_obj['name'], r.status_code,
+                                            r.text))
+                        logger.debug(exception_string)
+                        logger.debug(vsvip_obj)
+                        raise Exception(exception_string)
+                    created_objs.append(new_vsvip_obj)
+                    self.actions += ['Cloned vsvip "%s"%s'
+                                    % (new_vsvip_obj['name'],
+                                        (' in tenant "%s"' % self.other_tenant)
+                                        if self.other_tenant else '')]
+                    v_obj['vsvip_ref'] = new_vsvip_obj['url']
+
+                    # Set VS VRF Context to match VsVip VRF Context
+
+                    v_obj['vrf_context_ref'] = new_vsvip_obj['vrf_context_ref']
 
             # Try to create the new VS (possibly in a different tenant to the
             # source)
 
             r = self.dest_api.post('virtualservice', v_obj,
-                                    tenant_uuid=otenant_uuid)
+                                   tenant_uuid=self.otenant_uuid)
 
             if r.status_code < 300:
                 new_vs = r.json()
                 self.actions += ['Cloned Virtual Service "%s"%s to "%s"%s%s' %
                                  (old_vs_name,
-                                 (' in tenant "%s"' % t_obj['name'])
-                                  if t_obj else '', new_vs_name,
-                                 (' in tenant "%s"' % ot_obj['name'])
-                                  if ot_obj else '',
-                                 (' in cloud "%s"' % oc_obj['name'])
-                                  if oc_obj else '')]
+                                  (' in tenant "%s"' % self.t_obj['name'])
+                                  if self.t_obj else '', new_vs_name,
+                                  (' in tenant "%s"' % self.ot_obj['name'])
+                                  if self.ot_obj else '',
+                                  (' in cloud "%s"' % self.oc_obj['name'])
+                                  if self.oc_obj else '')]
                 logger.debug('Created Virtual Service "%s"', new_vs['url'])
                 if v_obj_old_url:
                     self.clone_track[v_obj_old_url] = new_vs['url']
                 return new_vs, created_objs, warnings
             else:
                 exception_string = ('Unable to clone Virtual Service "%s" '
                                     'as "%s" (%d:%s)' % (old_vs_name,
@@ -2137,215 +2366,52 @@
                 logger.debug(v_obj)
                 raise Exception(exception_string)
 
         except Exception as ex:
             # If an exception occurred, delete any intermediate objects we have
             # created
 
-            self._delete_created_objs(created_objs, otenant_uuid)
+            self.delete_objects(created_objs)
 
             #logger.debug('Exception occurred', exc_info=ex)
 
             raise Exception('%s\r\n=> Unable to clone Virtual Service "%s" '
                             'as "%s"' % (ex, old_vs_name, new_vs_name))
 
 # MAIN PROGRAM
 
+
 if __name__ == '__main__':
     HELP_STR = '''
         For detailed help on cloning a specific object, use for
-        example:
-        clone_vs.py vs -h
-
-        The script allows the cloning of Virtual Services, pools,
-        pool groups and generic objects (that have no child
-        references).
-
-        The script clones any additional objects that are required,
-        so for example when cloning a Virtual Service, the pools
-        and/or pool groups used by that VS, including any specified
-        in context-switching rules, will also be cloned.
-
-        The script also allows the cloning of objects into a
-        different tenant and/or cloud than the source - the
-        destination may also be on a different Avi Vantage
-        controller.
-
-        These advanced cloning options may not always be successful
-        because the source and destination tenant/cloud/controllers
-        may have different properties. If the clone attempt fails,
-        the script will automatically delete any objects that it
-        created along the way.
-
-        By default, re-usable child objects/profiles such as
-        application profiles, health monitors, persistency profiles
-        etc. are not cloned so that the cloned object simply refers
-        to the same child objects as the original.
-
-        However, when cloning to a different tenant, the behaviour
-        is slightly different:
-
-        If a re-usable object was defined in the admin tenant, it is
-        available in all tenants and will not be cloned by default.
-        If a re-usable objects was defined in the source tenant, the
-        script will use an identically-named object in the target
-        tenant if one is found. Otherwise, the object will be cloned
-        to the destination.
-
-        This behaviour can be overridden using the "forceclone"
-        option which ensures that the specified references are
-        always cloned rather than re-used.
-
-        For example, to forcibly clone all health monitors, use the
-        option:
-
-        --forceclone pool-healthmonitor
-
-        The full list of supported options is displayed in the help.
-
-        Examples:
-
-        * Cloning a VS and child objects within a tenant:
-
-        clone_vs.py -c controller.acme.com vs
-        example cloned-example -v 10.10.10.2
-
-
-        * Cloning a VS and child objects to a different tenant:
-
-        clone_vs.py -c controller.acme.com vs
-        example cloned-example -t tenant1 -2t tenant2
-        -v 10.10.10.2
-
-
-        * Cloning a VS and child objects between two Azure clouds:
-
-        clone_vs.py -c controller.acme.com vs
-        example cloned-example -2c Azure-Cloud-USEast2
-        -v 172.27.33.0/24/vip-subnet
-
-        Note: Azure subnet name (subnet_uuid) must be specified, e.g. vip-subnet
-
-
-        * Cloning a VS and child objects to a different tenant and
-        cloud with auto-allocation of VIP:
-
-        clone_vs.py -c controller.acme.com vs
-        example cloned-example -t tenant1 -2t tenant2
-        -2c Second-Cloud -v 10.10.10.0/24
-
-
-        * Cloning a VS but forcing health monitors and application
-        profiles to be cloned rather than re-used in the cloned VS:
-
-        clone_vs.py -c controller.acme.com vs
-        example cloned-example -fc pool-healthmonitor,vs-appprofile
-
-
-        * Cloning an Application Profile to a different tenant on a
-        different controller:
-
-        clone_vs.py -c controller1.acme.com -dc controller2.acme.com
-        generic health-monitor cloned-health-monitor
-        -t tenant1 -2t tenant2 -2c Default-Cloud
-
-
-        * Cloning a GSLB Service within a tenant
-
-        clone_vs.py -c controller.acme.com gs
-        example cloned-example -dn cloned-example.gslb.acme.com
-
-
-        * Cloning a GSLB Service to a different tenant with auto-assignment
-        of FQDN based on new service name and domain from source service:
-
-        clone_vs.py -c controller.acme.com gs
-        example cloned-example -dn auto -t tenant1 -2t tenant2
-
-
-        * Cloning a VS to a different controller with an AWS cloud,
-        specifying auto-allocation for VIPs by subnet in 3 AZs:
-
-        clone_vs.py -c controller1.acme.com -dc controller2.acme.com
-        vs example cloned-example
-        -v 10.0.0.0/24,10.1.0.0/24,10.2.0.0/24
-        -t tenant -2t tenant -2c AWS-Cloud
-
-
-        * As above but also with elastic IP allocation:
-
-        clone_vs.py -c controller1.acme.com -dc controller2.acme.com
-        vs example cloned-example
-        -v 10.0.0.0/24,10.1.0.0/24,10.2.0.0/24;auto,auto,auto
-        -t tenant -2t tenant -2c AWS-Cloud
-
-
-        * Cloning a VS in 18.1 and above with a static IPv4 and IPv6
-        address:
-
-        clone_vs.py -c controller1.acme.com vs example cloned-example
-        -v 10.0.0.10 -v6 fd00:dead:beef:bad:f00d::10
-
-
-        * Cloning a VS in 18.1 with new auto-allocation for IPv4 and IPv6:
-
-        clone_vs.py -c controller1.acme.com vs example cloned-example
-        -v 10.0.0.0/16 -v6 fd00:dead:beef:bad:f00d::/64
-
-
-        By default, the API version is automatically determined based on the
-        software versions of the source and destination Controllers. It is also
-        possible to specify the specific API version to be used with the -x
-        parameter.
-
-
-        Some known limitations and caveats:
-
-        * Depending on the version of Avi Vantage and configuration, it may
-        be possible for a VS in a non-admin tenant to reference and use SSL
-        certificates in the admin tenant. However by default, this script will
-        instead clone certificates to the target tenant. This behaviour can
-        be enabled with the option -flags adminssl
-
-        * Cloning a VS to a cloud of a different type to the source
-        cloud is more likely to fail as it may reference shared
-        objects which do not make sense in the destination cloud.
-
-        * Cloning a VS to a different tenant/cloud will try to find
-        an SE group with the same name as referenced in the source
-        VS but if no match is found, will place into the Default SE
-        group instead.
+        example: clone_vs.py vs -h
 
-        * Cloning a GSLB Service to a different Controller is not possible
-
-        * The script has been primarily written for and tested with
-        Linux Server/VMware/AWS clouds - it may not work as-is for
-        other clouds.
+        See clone_vs.md for more information and examples.
     '''
 
     print('%s version %s' % (sys.argv[0], '.'.join(str(v) for v in
                                                    AVICLONE_VERSION)))
     print()
 
     # Build the command-line parameter parser
 
-    pool_valid_refs = sorted(
-           set(AviClone.VALID_POOL_REF_OBJECTS.keys()) |
-           set(AviClone.VALID_POLICYSET_REF_OBJECTS.keys()) |
-           set(AviClone.VALID_DATASCRIPT_REF_OBJECTS.keys()) |
-           set(AviClone.VALID_APPLICATIONPROFILE_REF_OBJECTS.keys()) |
-           set(AviClone.VALID_SSLCERT_REF_OBJECTS.keys()))
-    vs_valid_refs = sorted(set(pool_valid_refs) |
-                           set(AviClone.VALID_VS_REF_OBJECTS.keys()) |
-                           set(AviClone.VALID_WAFPOLICY_REF_OBJECTS.keys()))
-    gs_valid_refs = sorted(set(AviClone.VALID_GS_REF_OBJECTS.keys()))
+    valid_refs = sorted(
+        set(AviClone.VALID_VS_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_GS_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_WAFPOLICY_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_WAFPOLICYPSMGROUP_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_POOL_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_POLICYSET_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_DATASCRIPT_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_APPLICATIONPROFILE_REF_OBJECTS.keys()) |
+        set(AviClone.VALID_SSLCERT_REF_OBJECTS.keys()))
 
     parser = argparse.ArgumentParser(
-                        formatter_class=argparse.RawDescriptionHelpFormatter,
-                        epilog=(HELP_STR))
+        formatter_class=argparse.RawDescriptionHelpFormatter,
+        epilog=(HELP_STR))
     parser.add_argument('-c', '--controller',
                         help='FQDN or IP address of Avi Vantage controller')
     parser.add_argument('-u', '--user', help='Avi Vantage username',
                         default='admin')
     parser.add_argument('-p', '--password', help='Avi Vantage password')
     parser.add_argument('-x', '--api_version',
                         help='Avi Vantage API version or auto to automatically '
@@ -2361,154 +2427,123 @@
     parser.add_argument('-dryrun', help='Allows a dry-run to be performed. '
                                         'Performs the clone, then waits '
                                         'for user input and then deletes '
                                         'the created objects',
                         action='store_true')
     parser.add_argument('-flags', help='Comma-separated list of special flags.',
                         default='')
+    parser.add_argument('-skp', '--sslkeypassphrases',
+                        help='List of SSL Key and Certificate passphrases. '
+                        'Format as cert1,passphrase1;cert2,passphrase2. '
+                        'Specify * for passphrase to be prompted.')
+    parser.add_argument('-t', '--tenant',
+                        help='Scope to a particular tenant',
+                        metavar='tenant')
+    parser.add_argument('-2t', '--totenant',
+                        help='Clone the object to a different tenant',
+                        metavar='other_tenant')
+    parser.add_argument('-2c', '--tocloud',
+                        help='Clone the pool group to a different cloud',
+                        metavar='other_cloud')
+    parser.add_argument('-2v', '--tovrf',
+                        help='The optional new VRF for the cloned Virtual Servicse/Pools',
+                        metavar='other_vrf')
+    parser.add_argument('-map', '--mapservers',
+                        help='List of server IP address pairs to match '
+                        'and replace in a pool. Format as '
+                        'match1,replace1;match2,replace2;...')
+    parser.add_argument('-ppn', '--poolplacement',
+                        help='List of pool placement networks '
+                        'and replace in a pool. Format as '
+                        '<server ip>/<mask>,{<network/>}<subnet>/<mask>'
+                        ';...')
+    parser.add_argument('-fc', '--forceclone',
+                        help='List of references to forcibly clone '
+                        'rather than re-use. Valid values are: %s'
+                        % ', '.join(valid_refs),
+                        metavar='ref_list',
+                        default=[])
     type_parser = parser.add_subparsers(help='Type of object to clone',
-                                metavar='object_type', dest='obj_type')
+                                        metavar='object_type', dest='obj_type')
     vs_parser = type_parser.add_parser('vs', help='Clone a Virtual Service')
     vs_parser.add_argument('vs_name',
                            help='Name of an existing Virtual Service')
     vs_parser.add_argument('new_vs_names',
-               help='Name(s) to be assigned to the cloned Virtual Service(s)')
+                           help='Name(s) to be assigned to the cloned Virtual Service(s)')
     vs_parser.add_argument('-v', '--vips',
-          help='The new VIP or list of VIPs (optionally specify list of FIPs '
-          'after ;) or auto or subnet/mask[/subnet_uuid] for auto-allocation',
-          metavar='VIPs')
+                           help='The new VIP or list of VIPs (optionally specify list of FIPs '
+                           'after ;) or auto or subnet/mask[/subnet_uuid] for auto-allocation',
+                           metavar='VIPs')
     vs_parser.add_argument('-v6', '--v6vips',
-          help='The new IP V6 VIP or list of VIPs '
-          'or auto or subnet/mask[/subnet_uuid] for auto-allocation',
-          metavar='V6VIPs')
+                           help='The new IP V6 VIP or list of VIPs '
+                           'or auto or subnet/mask[/subnet_uuid] for auto-allocation',
+                           metavar='V6VIPs')
     vs_parser.add_argument('-int', '--internalipam',
-          help='For auto-allocation specifying subnet/mask, allocate '
-               'from internal Avi IPAM/Infoblox, e.g. for VMware Clouds',
-               action='store_true')
+                           help='For auto-allocation specifying subnet/mask, allocate '
+                           'from internal Avi IPAM/Infoblox, e.g. for VMware Clouds',
+                           action='store_true')
+    vs_parser.add_argument('-ecmp', '--scaleout_ecmp',
+                           help='If specified, scaleout_ecmp will be enabled or '
+                           'disabled. If unspecified, scaleout_ecmp setting of '
+                           'source VS will be preserved.',
+                           choices=['true', 'false'])
+    vs_parser.add_argument('-rhi', '--enable_rhi',
+                           help='If specified, enable_rhi will be enabled or '
+                           'disabled. If unspecified, bgp_rhi setting of '
+                           'source VS will be preserved.',
+                           choices=['true', 'false'])
     vs_parser.add_argument('-dn', '--fqdns',
-        help='The new FQDN or list of FQDNs or auto to derive from the VS name',
-        metavar='FQDNs', default='')
+                           help='The new FQDN or list of FQDNs or auto to derive '
+                           'from the VS name',
+                           metavar='FQDNs', default='')
     vs_parser.add_argument('-e', '--enable',
-          help='Enable the cloned Virtual Service', action='store_true')
+                           help='Enable the cloned Virtual Service', action='store_true')
     vs_parser.add_argument('-np', '--newparent',
                            help='Specify a new parent VS name for a child VS',
                            metavar='new_parent')
-    vs_parser.add_argument('-t', '--tenant',
-          help='Scope to a particular tenant', metavar='tenant')
-    vs_parser.add_argument('-2t', '--totenant',
-                           help='Clone the service to a different tenant',
-                           metavar='other_tenant')
-    vs_parser.add_argument('-2c', '--tocloud',
-                           help='Clone the service to a different cloud',
-                           metavar='other_cloud')
+    vs_parser.add_argument('-vh', '--vhtype',
+                           help='Specify the Virtual Hosting type for the '
+                           'cloned VS',
+                           choices=['sni_parent', 'sni_child', 'evh_parent', 'evh_child', 'no_vh'])
+    vs_parser.add_argument('-mv', '--manualvsvip',
+                           help='Specify an existing VsVip to use for the cloned VS')
     vs_parser.add_argument('-g', '--segroup',
-             help='The optional new SE group for the cloned Virtual Service',
+                           help='The optional new SE group for the cloned Virtual Service',
                            metavar='se_group')
-    vs_parser.add_argument('-fc', '--forceclone',
-                           help='List of references to forcibly clone '
-                           'rather than re-use. Valid values are: %s'
-                           % ', '.join(vs_valid_refs),
-                           metavar='ref_list',
-                           default=[])
-    vs_parser.add_argument('-map', '--mapservers',
-                           help='List of server IP address pairs to match '
-                           'and replace in a pool. Format as '
-                           'match1,replace1;match2,replace2;...')
-    pool_parser = type_parser.add_parser('pool', help='Clone a Pool')
-    pool_parser.add_argument('pool_name', help='Name of an existing Pool')
-    pool_parser.add_argument('new_pool_names',
-                        help='Name(s) to be assigned to the cloned Pool(s)')
-    pool_parser.add_argument('-t', '--tenant',
-                             help='Scope to a particular tenant',
-                             metavar='tenant')
-    pool_parser.add_argument('-2t', '--totenant',
-                             help='Clone the pool to a different tenant',
-                             metavar='other_tenant')
-    pool_parser.add_argument('-2c', '--tocloud',
-                             help='Clone the pool to a different cloud',
-                             metavar='other_cloud')
-    pool_parser.add_argument('-fc', '--forceclone',
-                             help='List of references to forcibly clone '
-                             'rather than re-use. Valid values are: %s'
-                             % ', '.join(pool_valid_refs),
-                             metavar='ref_list',
-                             default=[])
-    pool_parser.add_argument('-map', '--mapservers',
-                             help='List of server IP address pairs to match '
-                             'and replace in a pool. Format as '
-                             'match1,replace1;match2,replace2;...')
-    pool_group_parser = type_parser.add_parser('poolgroup',
-                                               help='Clone a Pool Group')
-    pool_group_parser.add_argument('pool_group_name',
-                                   help='Name of an existing Pool Group')
-    pool_group_parser.add_argument('new_pool_group_names',
-                    help='Name(s) to be assigned to the cloned Pool Group(s)')
-    pool_group_parser.add_argument('-t', '--tenant',
-                      help='Scope to a particular tenant', metavar='tenant')
-    pool_group_parser.add_argument('-2t', '--totenant',
-                            help='Clone the pool group to a different tenant',
-                                   metavar='other_tenant')
-    pool_group_parser.add_argument('-2c', '--tocloud',
-                            help='Clone the pool group to a different cloud',
-                                   metavar='other_cloud')
-    pool_group_parser.add_argument('-fc', '--forceclone',
-                                   help='List of references to forcibly clone '
-                                   'rather than re-use. Valid values are: %s'
-                                   % ', '.join(pool_valid_refs),
-                                   metavar='ref_list',
-                                   default=[])
-    pool_group_parser.add_argument('-map', '--mapservers',
-                                   help='List of server IP address pairs to '
-                                   'match and replace in a pool. Format as '
-                                   'match1,replace1;match2,replace2;...')
+    vs_parser.add_argument('-vpn', '--vsplacements',
+                           help='Specify placement networks for the VsVip in form '
+                           'subnet/mask, network-name/subnet/mask or '
+                           'network-name/subnet/mask/subnet6/mask6. Multiple placement '
+                           'networks can be separated with ";"',
+                           metavar='vs_placements')
     gs_parser = type_parser.add_parser('gs',
                                        help='Clone a GSLB Service')
     gs_parser.add_argument('gs_name',
                            help='Name of an existing GSLB Service')
     gs_parser.add_argument('new_gs_names',
-               help='Name(s) to be assigned to the cloned GSLB Service(s)')
+                           help='Name(s) to be assigned to the cloned GSLB Service(s)')
     gs_parser.add_argument('-dn', '--fqdns',
-        help='The new FQDN or list of FQDNs or auto to derive from the GS name',
-        metavar='FQDNs', default='')
+                           help='The new FQDN or list of FQDNs or auto to derive '
+                           'from the GS name',
+                           metavar='FQDNs', default='')
     gs_parser.add_argument('-e', '--enable',
-          help='Enable the cloned GSLB Service', action='store_true')
-    gs_parser.add_argument('-t', '--tenant',
-          help='Scope to a particular tenant', metavar='tenant')
-    gs_parser.add_argument('-2t', '--totenant',
-                           help='Clone the service to a different tenant',
-                           metavar='other_tenant')
-    gs_parser.add_argument('-fc', '--forceclone',
-                           help='List of references to forcibly clone '
-                           'rather than re-use. Valid values are: %s'
-                           % ', '.join(gs_valid_refs),
-                           metavar='ref_list',
-                           default=[])
+                           help='Enable the cloned GSLB Service', action='store_true')
     generic_parser = type_parser.add_parser('generic',
-                      help='Clone a generic object')
+                                            help='Clone a generic object')
     generic_parser.add_argument('object_type',
-                      help='Type of object to clone (e.g. applicationprofile)')
+                                help='Type of object to clone (e.g. applicationprofile)')
     generic_parser.add_argument('generic_name',
-                      help='Name of an existing object')
+                                help='Name of an existing object')
     generic_parser.add_argument('new_generic_names',
-                      help='Name(s) to be assigned to the cloned object(s)')
-    generic_parser.add_argument('-t', '--tenant',
-                      help='Scope to a particular tenant',
-                             metavar='tenant')
-    generic_parser.add_argument('-2t', '--totenant',
-                      help='Clone the object to a different tenant',
-                      metavar='other_tenant')
+                                help='Name(s) to be assigned to the cloned object(s)')
     generic_parser.add_argument('-fc', '--forceclone',
-                                 help='List of references to forcibly clone '
-                                 'rather than re-use',
-                                 metavar='ref_list',
-                                 default=[])
-    generic_parser.add_argument('-map', '--mapservers',
-                                help='List of server IP address pairs to match '
-                                'and replace in a pool. Format as '
-                                'match1,replace1;match2,replace2;...')
+                                help='List of references to forcibly clone '
+                                'rather than re-use',
+                                metavar='ref_list',
+                                default=[])
 
     args = parser.parse_args()
 
     if args and args.obj_type:
 
         # If not specified on the command-line, prompt the user for the
         # controller IP address and/or password
@@ -2533,28 +2568,58 @@
 
             while not password:
                 password = getpass.getpass('Password for %s@%s:' %
                                            (user, controller))
 
             if controller2:
                 if (args.obj_type in ['vs', 'pool', 'poolgroup']
-                    and not args.tocloud):
+                        and not args.tocloud):
                     raise Exception('Destination cloud should be specified '
                                     'when cloning %s to a different '
                                     'controller' % args.obj_type)
 
                 while not password2:
                     password2 = getpass.getpass('Password for %s@%s:' %
-                                               (user2, controller2))
+                                                (user2, controller2))
 
             api_version = (None if args.api_version == 'auto' else
                            args.api_version)
 
             flags = set(args.flags.split(','))
 
+            if args.sslkeypassphrases:
+                ssl_key_pps = {}
+                for pair in args.sslkeypassphrases.split(';'):
+                    ssl_key = pair.split(',')
+                    ssl_cert = ssl_key[0]
+                    if ssl_cert:
+                        if len(ssl_key) == 1 or ssl_key[1] == '*':
+                            passphrase = getpass.getpass('Passphrase for cert '
+                                                         '"%s":' % ssl_cert)
+                        else:
+                            passphrase = ssl_key[1]
+                        ssl_key_pps[ssl_cert] = passphrase
+            else:
+                ssl_key_pps = None
+
+            force_clone = (args.forceclone.split(',')
+                           if args.forceclone else None)
+
+            if args.mapservers:
+                server_map = [tuple(pair.split(','))
+                              for pair in args.mapservers.split(';')]
+            else:
+                server_map = []
+
+            if args.poolplacement:
+                pool_placement = [tuple(pair.split(','))
+                                  for pair in args.poolplacement.split(';')]
+            else:
+                pool_placement = []
+
             while True:
                 # Create the API session
 
                 print('Creating %sAPI session to %s%s...'
                       % ('source ' if controller2 else '',
                          controller, (' (%s)' % api_version)
                          if api_version else ''), end='')
@@ -2564,15 +2629,15 @@
                 print()
 
                 # Create destination API session to a second controller
 
                 if controller2:
                     print('Creating destination API session to %s%s...'
                           % (controller2, (' (%s)' % api_version)
-                          if api_version else ''), end='')
+                             if api_version else ''), end='')
                     api2 = ApiSession.get_session(controller2, user2, password2,
                                                   api_version=api_version)
                     print('OK!')
                     print()
                 else:
                     api2 = None
 
@@ -2601,41 +2666,38 @@
                 print()
                 api.delete_session()
                 if api2:
                     api2.delete_session()
 
             # Create an instance of our cloning class
 
-            cl = AviClone(api, api2, flags=flags)
-
-            force_clone = (args.forceclone.split(',')
-                           if args.forceclone else None)
-
-            if 'mapservers' in args:
-                server_map = ([tuple(pair.split(','))
-                            for pair in args.mapservers.split(';')]
-                            if args.mapservers else None)
-            else:
-                server_map = []
+            cl = AviClone(source_api=api, dest_api=api2,
+                          flags=flags, tenant=args.tenant,
+                          other_tenant=args.totenant,
+                          other_cloud=args.tocloud,
+                          other_vrf=args.tovrf,
+                          server_map=server_map,
+                          pool_placement=pool_placement,
+                          ssl_key_pps=ssl_key_pps)
 
             if args.obj_type == 'vs':
                 # Loop through the clone names and clone the source VS for
                 # each destination
 
                 new_vs_names = args.new_vs_names.split(',')
                 num_new_vs = len(new_vs_names)
 
                 if args.vips:
                     vipsfips = args.vips.split(';')
                     vips = (['*'] * num_new_vs
                             if args.vips in ['*', 'auto']
                             else vipsfips[0].split(','))
                     fips = ([None] * len(vips)
-                        if (args.vips in ['*', 'auto'] or len(vipsfips) == 1)
-                        else vipsfips[1].split(','))
+                            if (args.vips in ['*', 'auto'] or len(vipsfips) == 1)
+                            else vipsfips[1].split(','))
                 else:
                     if args.v6vips:
                         vips = [None] * num_new_vs
                     else:
                         vips = ['*']
                     fips = [None] * len(vips)
 
@@ -2644,102 +2706,117 @@
                              else args.fqdns.split(','))
                 else:
                     fqdns = [None] * num_new_vs
 
                 v6vips = ([None] * len(vips)
                           if not args.v6vips else args.v6vips.split(','))
 
+                vsplacements = ([None] * len(vips)
+                                if not args.vsplacements else args.vsplacements.split(','))
+
                 if num_new_vs == 1:
                     # If we only have a single destination VS name, assume the
                     # provided VIPs/FIPs/FQDNs are multi-values for a single
                     # VS rather than values per new VS
 
                     if len(vips) != len(v6vips):
                         raise Exception('Number of VIPs and V6 VIPs'
                                         'should match.')
 
                     vips = [vips]
                     fips = [fips]
                     fqdns = [fqdns]
                     v6vips = [v6vips]
+                    vsplacements = [vsplacements]
                 else:
                     # Otherwise, make sure we have the same number of VIPs,
                     # FIPs, FQDNs as the number of provided VS names
 
                     if (len(vips) == len(fips) ==
                         len(fqdns) == len(v6vips) ==
-                        num_new_vs):
+                        len(vsplacements) ==
+                            num_new_vs):
                         vips = [[vip] for vip in vips]
                         fips = [[fip] for fip in fips]
                         fqdns = [[fqdn] for fqdn in fqdns]
                         v6vips = [[v6vip] for v6vip in v6vips]
+                        vsplacements = [[vsplacement] for vsplacement
+                                        in vsplacements]
                     else:
                         raise Exception('The number of VIPs (%d: %s), V6VIPs '
                                         '(%d: %s), FIPs (%d: %s), FQDNs '
-                                        '(%d: %s) and new VS names (%d: %s) '
+                                        '(%d: %s), Placements (%d: %s) '
+                                        'and new VS names (%d: %s) '
                                         'must be consistent.' %
-                                (len(vips),
-                                 ','.join([vip or '-' for vip in vips]),
-                                 len(v6vips),
-                                 ','.join([v6vip or '-' for v6vip in v6vips]),
-                                 len(fips),
-                                 ','.join([fip or '-' for fip in fips]),
-                                 len(fqdns),
-                                 ','.join([fqdn or '-' for fqdn in fqdns]),
-                                 len(new_vs_names),
-                                 ','.join(new_vs_names)))
+                                        (len(vips),
+                                         ','.join(
+                                             [vip or '-' for vip in vips]),
+                                         len(v6vips),
+                                            ','.join(
+                                                [v6vip or '-' for v6vip in v6vips]),
+                                            len(fips),
+                                            ','.join(
+                                                [fip or '-' for fip in fips]),
+                                            len(fqdns),
+                                            ','.join(
+                                                [fqdn or '-' for fqdn in fqdns]),
+                                            len(vsplacements),
+                                            ','.join([vsplacement or '-'
+                                                      for vsplacement in vsplacements]),
+                                            len(new_vs_names),
+                                            ','.join(new_vs_names)))
+
+                def flag_map(x): return x if x is None else (x == 'true')
+
+                vs_flags = {'use_internal_ipam': args.internalipam,
+                            'scaleout_ecmp': flag_map(args.scaleout_ecmp),
+                            'enable_rhi': flag_map(args.enable_rhi)}
+
+                vh_type = args.vhtype
 
                 for (new_vs_name, new_vips,
-                     new_fips, new_fqdns, new_v6vips) in zip(new_vs_names,
-                                                              vips, fips,
-                                                              fqdns, v6vips):
+                     new_fips, new_fqdns, new_v6vips, new_vsplacement) in zip(
+                         new_vs_names, vips, fips, fqdns, v6vips, vsplacements):
+
                     spprint('Trying to clone VS %s%s to %s%s%s...'
                             % (args.vs_name, ' ['+args.tenant+']'
                                if args.tenant else '',
                                new_vs_name,
                                ' ['+args.totenant+']'
                                if args.totenant else '',
                                ' in cloud '+args.tocloud
                                if args.tocloud else ''),
                             flush=True)
                     new_vs, cloned_objs, warnings = cl.clone_vs(
-                             old_vs_name=args.vs_name, new_vs_name=new_vs_name,
-                             enable_vs=args.enable, new_vs_vips=new_vips,
-                             new_vs_v6vips=new_v6vips,
-                             new_vs_fips=new_fips, new_fqdns=new_fqdns,
-                             new_segroup=args.segroup, tenant=args.tenant,
-                             other_tenant=args.totenant,
-                             other_cloud=args.tocloud, force_clone=force_clone,
-                             use_internal_ipam=args.internalipam,
-                             server_map=server_map,
-                             new_parent=args.newparent)
-                    # Get VsVip object if present
-                    if 'vsvip_ref' in new_vs:
-                        for cloned_obj in cloned_objs:
-                            if cloned_obj['url'] == new_vs['vsvip_ref']:
-                                new_vsvip = cloned_obj
-
-                                # Pre-20.1.1 we can remove the VsVip object from
-                                # the cloned object list as it will be deleted
-                                # by WebApp when the VS is deleted
-                                if 'vip' in new_vs:
-                                    cloned_objs.remove(cloned_obj)
-                                break
-                        else:
-                            new_vsvip = {'vip': []}
+                        old_vs_name=args.vs_name, new_vs_name=new_vs_name,
+                        enable_vs=args.enable, new_vs_vips=new_vips,
+                        new_vs_v6vips=new_v6vips,
+                        new_vs_fips=new_fips, new_fqdns=new_fqdns,
+                        new_segroup=args.segroup,
+                        force_clone=force_clone,
+                        vs_flags=vs_flags,
+                        new_parent=args.newparent,
+                        vh_type=vh_type,
+                        manual_vsvip=args.manualvsvip,
+                        new_vs_placements=new_vsplacement)
+
+                    # Get VsVip object
+                    for cloned_obj in cloned_objs:
+                        if cloned_obj['url'] == new_vs.get('vsvip_ref', ''):
+                            new_vsvip = cloned_obj
+
+                            # Pre-20.1.1 we can remove the VsVip object from
+                            # the cloned object list as it will be deleted
+                            # by WebApp when the VS is deleted
+                            if 'vip' in new_vs:
+                                cloned_objs.remove(cloned_obj)
+                            break
                     else:
-                        # Old VS structure - populate VIP data
-                        vip_data = {}
-                        for k in ('ip_address', 'ip6_address',
-                                  'floating_ip', 'floating_ip6'):
-                            if k in new_vs:
-                                vip_data[k] = new_vs[k]
-                        new_vsvip = {'vip': [vip_data]}
-                        if 'dns_info' in new_vs:
-                            new_vsvip['dns_info'] = new_vs['dns_info']
+                        new_vsvip = {'vip': []}
+
                     all_created_objs.append(new_vs)
                     all_created_objs.extend(cloned_objs)
                     if warnings:
                         print('OK with warnings:')
                         print()
                         for index, warning in enumerate(warnings):
                             spprint('%2d. %s' % (index + 1, warning), '    ')
@@ -2777,61 +2854,61 @@
 
                     print('%10s: %s' % ('VIP(s)', ','.join(v4_vips + v6_vips)))
                     print('%10s: %s' % ('FIP(s)', ','.join(v4_fips + v6_fips)))
                     if 'dns_info' in new_vsvip:
                         print('%10s: %s' % ('FQDN(s)', ','.join([dns['fqdn']
                                             for dns in new_vsvip['dns_info']])))
                     print('%10s: %s' % ('State', 'Enabled' if new_vs['enabled']
-                                                               else 'Disabled'))
+                                        else 'Disabled'))
                     if args.totenant:
                         print('%10s: %s' % ('Tenant', args.totenant))
                     if args.tocloud:
                         print('%10s: %s' % ('Cloud', args.tocloud))
                     print()
             elif args.obj_type == 'gs':
                 new_gs_names = args.new_gs_names.split(',')
                 num_new_gs = len(new_gs_names)
 
                 fqdns = (['*'] * num_new_gs if not args.fqdns or
-                            args.fqdns in ['*', 'auto']
-                            else args.fqdns.split(','))
+                         args.fqdns in ['*', 'auto']
+                         else args.fqdns.split(','))
 
                 if num_new_gs == 1:
                     # If we only have a single destination GS name, assume the
                     # provided FQDNs are multi-values for a single
                     # GS rather than values per new GS
                     fqdns = [fqdns]
                 else:
                     # Otherwise, make sure we have the same number of FQDNs,
                     #  as the number of provided VS names
 
-                    if (len(fqdns) == num_new_gs):
+                    if len(fqdns) == num_new_gs:
                         fqdns = [[fqdn] for fqdn in fqdns]
                     else:
                         raise Exception('The number of FQDNs '
                                         '(%d: %s) and new GS names (%d: %s) '
                                         'must be consistent.' %
-                                (len(fqdns),
-                                 ','.join([fqdn or '-' for fqdn in fqdns]),
-                                 len(new_gs_names),
-                                 ','.join(new_gs_names)))
+                                        (len(fqdns),
+                                         ','.join(
+                                             [fqdn or '-' for fqdn in fqdns]),
+                                         len(new_gs_names),
+                                            ','.join(new_gs_names)))
 
                 for (new_gs_name, new_fqdns) in zip(new_gs_names, fqdns):
                     spprint('Trying to clone GS %s%s to %s%s...'
                             % (args.gs_name, ' ['+args.tenant+']'
                                if args.tenant else '',
                                new_gs_name,
                                ' ['+args.totenant+']'
                                if args.totenant else ''),
                             flush=True)
                     new_gs, cloned_objs, warnings = cl.clone_gs(
-                             old_gs_name=args.gs_name, new_gs_name=new_gs_name,
-                             enable_gs=args.enable, new_fqdns=new_fqdns,
-                             tenant=args.tenant, other_tenant=args.totenant,
-                             force_clone=force_clone)
+                        old_gs_name=args.gs_name, new_gs_name=new_gs_name,
+                        enable_gs=args.enable, new_fqdns=new_fqdns,
+                        force_clone=force_clone)
                     all_created_objs.append(new_gs)
                     all_created_objs.extend(cloned_objs)
                     if warnings:
                         print('OK with warnings:')
                         print()
                         for index, warning in enumerate(warnings):
                             spprint('%2d. %s' % (index + 1, warning), '    ')
@@ -2841,124 +2918,37 @@
                     print()
 
                     print('New GSLB Service created as follows:')
                     print('%10s: %s' % ('Name', new_gs['name']))
                     print('%10s: %s' % ('FQDN(s)', ','.join(
                                         new_gs['domain_names'])))
                     print('%10s: %s' % ('State', 'Enabled' if new_gs['enabled']
-                                                               else 'Disabled'))
+                                        else 'Disabled'))
                     if args.totenant:
                         print('%10s: %s' % ('Tenant', args.totenant))
                     print()
-
-            elif args.obj_type == 'pool':
-                # Loop through the clone names and clone the source pool for
-                # each destination
-
-                for new_pool_name in args.new_pool_names.split(','):
-                    spprint('Trying to clone pool %s%s to %s%s%s...'
-                            % (args.pool_name, ' ['+args.tenant+']'
-                               if args.tenant else '',
-                               new_pool_name,
-                               ' ['+args.totenant+']'
-                               if args.totenant else '',
-                               ' in cloud '+args.tocloud
-                               if args.tocloud else ''),
-                            flush=True)
-
-                    new_pool, cloned_objs, warnings = cl.clone_object(
-                        object_type='pool',
-                        old_name=args.pool_name, new_name=new_pool_name,
-                        tenant=args.tenant, other_tenant=args.totenant,
-                        other_cloud=args.tocloud, force_clone=force_clone,
-                        force_unique_name=False, server_map=server_map)
-                    all_created_objs.append(new_pool)
-                    all_created_objs.extend(cloned_objs)
-                    if warnings:
-                        print('OK with warnings:')
-                        print()
-                        for index, warning in enumerate(warnings):
-                            spprint('%2d. %s' % (index + 1, warning), '    ')
-                        print()
-                    else:
-                        print('OK!')
-                    print()
-
-                    print('New Pool created as follows:')
-                    print('%10s: %s' % ('Name', new_pool['name']))
-                    if args.totenant:
-                        print('%10s: %s' % ('Tenant', args.totenant))
-                    if args.tocloud:
-                        print('%10s: %s' % ('Cloud', args.tocloud))
-                    print()
-
-            elif args.obj_type == 'poolgroup':
-                # Loop through the clone names and clone the source pool group
-                # for each destination
-
-                for new_pool_group_name in args.new_pool_group_names.split(','):
-                    spprint('Trying to clone pool group %s%s to %s%s%s...'
-                            % (args.pool_group_name,
-                               ' ['+args.tenant+']'
-                               if args.tenant else '',
-                               new_pool_group_name,
-                               ' ['+args.totenant+']'
-                               if args.totenant else '',
-                               ' in cloud '+args.tocloud
-                               if args.tocloud else ''),
-                            flush=True)
-                    new_poolgroup, cloned_objs, warnings = cl.clone_object(
-                        object_type='poolgroup',
-                        old_name=args.pool_group_name,
-                        new_name=new_pool_group_name,
-                        tenant=args.tenant, other_tenant=args.totenant,
-                        other_cloud=args.tocloud, force_clone=force_clone,
-                        force_unique_name=False, server_map=server_map)
-                    all_created_objs.append(new_poolgroup)
-                    all_created_objs.extend(cloned_objs)
-                    if warnings:
-                        print('OK with warnings:')
-                        print()
-                        for index, warning in enumerate(warnings):
-                            spprint('%2d. %s' % (index + 1, warning), '    ')
-                        print()
-                    else:
-                        print('OK!')
-                    print()
-
-                    print('New Pool Group created as follows:')
-                    print('%10s: %s' % ('Name', new_poolgroup['name']))
-                    if args.totenant:
-                        print('%10s: %s' % ('Tenant', args.totenant))
-                    if args.tocloud:
-                        print('%10s: %s' % ('Cloud', args.tocloud))
-                    print()
-
             elif args.obj_type == 'generic':
                 # Loop through the clone names and clone the source object for
                 # each destination
 
                 for new_gen_name in args.new_generic_names.split(','):
                     spprint('Trying to clone object of type %s with '
                             'name %s%s to %s%s...'
                             % (args.object_type, args.generic_name,
-                              ' ['+args.tenant+']'
-                              if args.tenant else '',
-                              new_gen_name,
-                              ' ['+args.totenant+']'
-                              if args.totenant else ''),
+                               ' ['+args.tenant+']'
+                               if args.tenant else '',
+                               new_gen_name,
+                               ' ['+args.totenant+']'
+                               if args.totenant else ''),
                             flush=True)
                     new_gen, cloned_objs, warnings = cl.clone_object(
-                                                  object_type=args.object_type,
-                                                  old_name=args.generic_name,
-                                                  new_name=new_gen_name,
-                                                  tenant=args.tenant,
-                                                  other_tenant=args.totenant,
-                                                  force_unique_name=False,
-                                                  server_map=server_map)
+                        object_type=args.object_type,
+                        old_name=args.generic_name,
+                        new_name=new_gen_name,
+                        force_unique_name=False)
                     all_created_objs.append(new_gen)
                     all_created_objs.extend(cloned_objs)
                     if warnings:
                         print('OK with warnings:')
                         print()
                         for index, warning in enumerate(warnings):
                             spprint('%2d. %s' % (index + 1, warning), '    ')
@@ -2986,11 +2976,10 @@
             print(ex)
         finally:
             if args.dryrun and all_created_objs:
                 try:
                     input('Dry-run: Hit ENTER to delete all cloned objects')
                 except:
                     pass
-                cl.delete_objects(objs=all_created_objs,
-                                  tenant=args.totenant or args.tenant)
+                cl.delete_objects(all_created_objs)
     else:
         parser.print_help()
```

### Comparing `avisdk-22.1.3/avi/sdk/samples/clone_vs_segroup.py` & `avisdk-22.1.4/avi/sdk/samples/clone_vs_segroup.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/common.py` & `avisdk-22.1.4/avi/sdk/samples/common.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/custom_dns_script_infoblox.py` & `avisdk-22.1.4/avi/sdk/samples/custom_dns_script_infoblox.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/custom_ipam_script_infoblox.py` & `avisdk-22.1.4/avi/sdk/samples/custom_ipam_script_infoblox.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/get_config_logs.py` & `avisdk-22.1.4/avi/sdk/samples/get_config_logs.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/heat/lb-asg.yaml` & `avisdk-22.1.4/avi/sdk/samples/heat/lb-asg.yaml`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/heat/lb-server.yaml` & `avisdk-22.1.4/avi/sdk/samples/heat/lb-server.yaml`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/init_system/examples/init-apic.json` & `avisdk-22.1.4/avi/sdk/samples/init_system/examples/init-apic.json`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/init_system/examples/init-openstack.json` & `avisdk-22.1.4/avi/sdk/samples/init_system/examples/init-openstack.json`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/init_system/init_system.py` & `avisdk-22.1.4/avi/sdk/samples/init_system/init_system.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/inventory_example.py` & `avisdk-22.1.4/avi/sdk/samples/inventory_example.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/multi_tenant.py` & `avisdk-22.1.4/avi/sdk/samples/multi_tenant.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/operstate_controlscript_infoblox.py` & `avisdk-22.1.4/avi/sdk/samples/operstate_controlscript_infoblox.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/patch_api_example.py` & `avisdk-22.1.4/avi/sdk/samples/patch_api_example.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/se_vs_metrics.py` & `avisdk-22.1.4/avi/sdk/samples/se_vs_metrics.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/simple_control_script.py` & `avisdk-22.1.4/avi/sdk/samples/simple_control_script.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/ssl_keyandcertificate_w_altnames.py` & `avisdk-22.1.4/avi/sdk/samples/ssl_keyandcertificate_w_altnames.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/sticky_pool_group.py` & `avisdk-22.1.4/avi/sdk/samples/sticky_pool_group.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/validate_custom_ipam_script.py` & `avisdk-22.1.4/avi/sdk/samples/validate_custom_ipam_script.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/virtualservice_disable.py` & `avisdk-22.1.4/avi/sdk/samples/virtualservice_disable.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/virtualservice_examples_api.py` & `avisdk-22.1.4/avi/sdk/samples/virtualservice_examples_api.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/virtualservice_examples_saml_api.py` & `avisdk-22.1.4/avi/sdk/samples/virtualservice_examples_saml_api.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/virtualservice_examples_sdk.py` & `avisdk-22.1.4/avi/sdk/samples/virtualservice_examples_sdk.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/samples/vra/update_vra.py` & `avisdk-22.1.4/avi/sdk/samples/vra/update_vra.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/setup.py` & `avisdk-22.1.4/avi/sdk/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -33,11 +33,11 @@
         'Programming Language :: Python :: 2.7',
         'Topic :: Internet :: WWW/HTTP',
         'Topic :: Internet :: WWW/HTTP :: Dynamic Content',
     ],
     keywords='AVI ADC Loadbalancer automation datacenter SDK',
     license='Avi Networks',
     include_package_data=True,
-    install_requires=['requests'],
+    install_requires=['requests', 'beautifulsoup4'],
     package_data={'avi': ['*.cfg', '*.conf', '*.crt', '*.crl', '*.json',
                           '*.key', '*.pem', '*.xml', '*.yaml', '*.rst']},
 )
```

### Comparing `avisdk-22.1.3/avi/sdk/test/jenkins_test_api.cfg` & `avisdk-22.1.4/avi/sdk/test/jenkins_test_api.cfg`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/test/test_api.cfg` & `avisdk-22.1.4/avi/sdk/test/test_api.cfg`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/test/test_saml_api.cfg` & `avisdk-22.1.4/avi/sdk/test/test_saml_api.cfg`

 * *Files 6% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.8015873015873015%*

 * *Differences: {"'BasicVS'": "{'vs_obj': {'vsvip_ref': 'basic_vs_vip', delete: ['vip']}, 'vsvip_obj': "*

 * *              "OrderedDict([('name', 'basic_vs_vip'), ('vip', [OrderedDict([('ip_address', "*

 * *              "OrderedDict([('addr', '10.90.64.123'), ('type', 'V4')]))])])])}",*

 * * "'Ws1LoginInfo'": "OrderedDict([('controller_ip', '10.10.28.123'), ('username', 'username'), "*

 * *                   "('password', 'password'), ('tenant', 'admin'), ('api_version', '22.1.3'), "*

 * *                   "('data_log', True)])"}*

```diff
@@ -21,14 +21,18 @@
             "services": [
                 {
                     "enable_ssl": false,
                     "port": 80
                 }
             ],
             "type": "VS_TYPE_NORMAL",
+            "vsvip_ref": "basic_vs_vip"
+        },
+        "vsvip_obj": {
+            "name": "basic_vs_vip",
             "vip": [
                 {
                     "ip_address": {
                         "addr": "10.90.64.123",
                         "type": "V4"
                     }
                 }
@@ -91,9 +95,17 @@
                     "ip_address": {
                         "addr": "10.90.64.123",
                         "type": "V4"
                     }
                 }
             ]
         }
+    },
+    "Ws1LoginInfo": {
+        "api_version": "22.1.3",
+        "controller_ip": "10.10.28.123",
+        "data_log": true,
+        "password": "password",
+        "tenant": "admin",
+        "username": "username"
     }
 }
```

### Comparing `avisdk-22.1.3/avi/sdk/utils/ansible_utils.py` & `avisdk-22.1.4/avi/sdk/utils/ansible_utils.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/utils/api_utils.py` & `avisdk-22.1.4/avi/sdk/utils/api_utils.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/utils/httppolicyset_templates.py` & `avisdk-22.1.4/avi/sdk/utils/httppolicyset_templates.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avi/sdk/utils/mesos/mesos_testutils.py` & `avisdk-22.1.4/avi/sdk/utils/mesos/mesos_testutils.py`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/avisdk.egg-info/PKG-INFO` & `avisdk-22.1.4/avisdk.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: avisdk
-Version: 22.1.3
+Version: 22.1.4
 Summary: Avi python API SDK for Avi Controller REST API with samples and, utilities
 Home-page: https://github.com/vmware/alb-sdk
 Author: Avi Networks
 Author-email: avisdk@avinetworks.com
 License: Avi Networks
 Description: UNKNOWN
 Keywords: AVI ADC Loadbalancer automation datacenter SDK
```

### Comparing `avisdk-22.1.3/avisdk.egg-info/SOURCES.txt` & `avisdk-22.1.4/avisdk.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `avisdk-22.1.3/setup.py` & `avisdk-22.1.4/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 
 import os
 from setuptools import setup, find_packages
 """
 This setup needs to be copied to the top level python directory and then
 create the package.
 """
-AVI_PIP_VERSION = '22.1.3'
+AVI_PIP_VERSION = '22.1.4'
 
 # allow setup.py to be run from any path
 os.chdir(os.path.normpath(os.path.join(os.path.abspath(__file__), os.pardir)))
 
 setup(
     name='avisdk',
     version=AVI_PIP_VERSION,
@@ -33,11 +33,11 @@
         'Programming Language :: Python :: 2.7',
         'Topic :: Internet :: WWW/HTTP',
         'Topic :: Internet :: WWW/HTTP :: Dynamic Content',
     ],
     keywords='AVI ADC Loadbalancer automation datacenter SDK',
     license='Avi Networks',
     include_package_data=True,
-    install_requires=['requests'],
+    install_requires=['requests', 'beautifulsoup4'],
     package_data={'avi': ['*.cfg', '*.conf', '*.crt', '*.crl', '*.json',
                           '*.key', '*.pem', '*.xml', '*.yaml', '*.rst']},
 )
```


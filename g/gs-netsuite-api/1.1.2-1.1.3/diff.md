# Comparing `tmp/gs-netsuite-api-1.1.2.tar.gz` & `tmp/gs-netsuite-api-1.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gs-netsuite-api-1.1.2.tar", last modified: Tue Jun 27 05:47:06 2023, max compression
+gzip compressed data, was "gs-netsuite-api-1.1.3.tar", last modified: Wed Jun 28 06:02:29 2023, max compression
```

## Comparing `gs-netsuite-api-1.1.2.tar` & `gs-netsuite-api-1.1.3.tar`

### file list

```diff
@@ -1,115 +1,116 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.689464 gs-netsuite-api-1.1.2/
--rw-rw-rw-   0 root         (0) root         (0)     1910 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.gitignore
--rw-rw-rw-   0 root         (0) root         (0)      382 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.gitlab-ci.yml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/.idea/
--rw-rw-rw-   0 root         (0) root         (0)      176 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.idea/.gitignore
--rw-rw-rw-   0 root         (0) root         (0)      391 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.idea/GitlabLint.xml
--rw-rw-rw-   0 root         (0) root         (0)      284 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.idea/misc.xml
--rw-rw-rw-   0 root         (0) root         (0)      265 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.idea/modules.xml
--rw-rw-rw-   0 root         (0) root         (0)      168 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.idea/vcs.xml
--rw-rw-rw-   0 root         (0) root         (0)      366 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.local-antora-playbook.yml
--rw-rw-rw-   0 root         (0) root         (0)      905 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.pre-commit-config.yaml
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/.ruff
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-27 05:47:06.685464 gs-netsuite-api-1.1.2/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)      842 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/README.adoc
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/docs/
--rw-rw-rw-   0 root         (0) root         (0)      141 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/docs/antora.yml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/docs/modules/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/docs/modules/ROOT/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/docs/modules/ROOT/examples/
--rw-rw-rw-   0 root         (0) root         (0)       90 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/docs/modules/ROOT/nav.adoc
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/
--rw-rw-rw-   0 root         (0) root         (0)     3361 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/api.adoc
--rw-rw-rw-   0 root         (0) root         (0)     2996 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/convertion.adoc
--rw-rw-rw-   0 root         (0) root         (0)      842 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/index.adoc
--rw-rw-rw-   0 root         (0) root         (0)     2206 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/types.adoc
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/example/
--rw-rw-rw-   0 root         (0) root         (0)     1319 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/example/sample_item_fulfillment_api.py
--rw-rw-rw-   0 root         (0) root         (0)     1311 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/example/sample_item_receipt_api.py
--rw-rw-rw-   0 root         (0) root         (0)     1300 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/example/sample_product_api.py
--rw-rw-rw-   0 root         (0) root         (0)     1820 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/example/sample_purchase_api.py
--rw-rw-rw-   0 root         (0) root         (0)     1308 2023-06-27 05:06:56.000000 gs-netsuite-api-1.1.2/example/sample_sale_api.py
--rw-rw-rw-   0 root         (0) root         (0)     1023 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/mkdocs.yml
--rw-rw-rw-   0 root         (0) root         (0)      495 2023-06-22 14:42:03.000000 gs-netsuite-api-1.1.2/netsuite-api.iml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/output/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/output/wsdl/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/output/wsdl/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)   133803 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/wsdl/v2022_2_0/netsuite.wsdl
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/output/xsd/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/output/xsd/activities/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/output/xsd/activities/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)    38231 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/activities/v2022_2_0/scheduling.xsd
--rw-rw-rw-   0 root         (0) root         (0)     7111 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/activities/v2022_2_0/schedulingTypes.xsd
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/output/xsd/documents/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.681464 gs-netsuite-api-1.1.2/output/xsd/documents/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)     8963 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/documents/v2022_2_0/fileCabinet.xsd
--rw-rw-rw-   0 root         (0) root         (0)     4282 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/documents/v2022_2_0/fileCabinetTypes.xsd
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/output/xsd/general/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.681464 gs-netsuite-api-1.1.2/output/xsd/general/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)    14530 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/general/v2022_2_0/communication.xsd
--rw-rw-rw-   0 root         (0) root         (0)      915 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/general/v2022_2_0/communicationTypes.xsd
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.673464 gs-netsuite-api-1.1.2/output/xsd/lists/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.681464 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)   424972 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/accounting.xsd
--rw-rw-rw-   0 root         (0) root         (0)    40848 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/accountingTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    11949 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/employeeTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    31010 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/employees.xsd
--rw-rw-rw-   0 root         (0) root         (0)    27949 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/marketing.xsd
--rw-rw-rw-   0 root         (0) root         (0)     5751 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/marketingTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)     7100 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/relationshipTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)   102099 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/relationships.xsd
--rw-rw-rw-   0 root         (0) root         (0)    16989 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/supplyChain.xsd
--rw-rw-rw-   0 root         (0) root         (0)     1222 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/supplyChainTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    29653 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/support.xsd
--rw-rw-rw-   0 root         (0) root         (0)     2906 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/supportTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)     6213 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/website.xsd
--rw-rw-rw-   0 root         (0) root         (0)      350 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/websiteTypes.xsd
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/output/xsd/platform/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.681464 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)   744517 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/common.xsd
--rw-rw-rw-   0 root         (0) root         (0)    59244 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/commonTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    47859 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/core.xsd
--rw-rw-rw-   0 root         (0) root         (0)    37883 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/coreTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    72361 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/faultTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)     3764 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/faults.xsd
--rw-rw-rw-   0 root         (0) root         (0)    28339 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/messages.xsd
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/output/xsd/setup/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.685464 gs-netsuite-api-1.1.2/output/xsd/setup/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)   102180 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/setup/v2022_2_0/customization.xsd
--rw-rw-rw-   0 root         (0) root         (0)     4880 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/setup/v2022_2_0/customizationTypes.xsd
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/output/xsd/transactions/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.685464 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/
--rw-rw-rw-   0 root         (0) root         (0)    13345 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/bank.xsd
--rw-rw-rw-   0 root         (0) root         (0)      354 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/bankTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)     3724 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/customerTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    75538 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/customers.xsd
--rw-rw-rw-   0 root         (0) root         (0)    10022 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/demandPlanning.xsd
--rw-rw-rw-   0 root         (0) root         (0)     2094 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/demandPlanningTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)      615 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/employeeTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    43650 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/employees.xsd
--rw-rw-rw-   0 root         (0) root         (0)     5844 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/financial.xsd
--rw-rw-rw-   0 root         (0) root         (0)      561 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/financialTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    23444 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/general.xsd
--rw-rw-rw-   0 root         (0) root         (0)    49374 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/inventory.xsd
--rw-rw-rw-   0 root         (0) root         (0)     2071 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/inventoryTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)     1983 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/purchaseTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)    64002 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/purchases.xsd
--rw-rw-rw-   0 root         (0) root         (0)    32740 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/saleTypes.xsd
--rw-rw-rw-   0 root         (0) root         (0)   141383 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/sales.xsd
--rw-rw-rw-   0 root         (0) root         (0)      627 2023-06-22 14:42:03.000000 gs-netsuite-api-1.1.2/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 05:47:06.689464 gs-netsuite-api-1.1.2/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.677464 gs-netsuite-api-1.1.2/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.685464 gs-netsuite-api-1.1.2/src/gs_netsuite_api/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api/__init__.py
--rw-r--r--   0 root         (0) root         (0)      160 2023-06-27 05:47:06.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api/_version.py
--rw-rw-rw-   0 root         (0) root         (0)    27203 2023-06-27 05:27:57.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api/api.py
--rw-rw-rw-   0 root         (0) root         (0)       60 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api/api.py.adoc
--rw-rw-rw-   0 root         (0) root         (0)     4317 2023-06-27 05:06:56.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api/data_types.py
--rw-rw-rw-   0 root         (0) root         (0)     4296 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api/ns_utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 05:47:06.685464 gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-27 05:47:06.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     3235 2023-06-27 05:47:06.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 05:47:06.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       52 2023-06-27 05:47:06.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       16 2023-06-27 05:47:06.000000 gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/top_level.txt
--rwxrwxrwx   0 root         (0) root         (0)     3862 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.2/wsdldownloader.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.348637 gs-netsuite-api-1.1.3/
+-rw-rw-rw-   0 root         (0) root         (0)     1910 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.gitignore
+-rw-rw-rw-   0 root         (0) root         (0)      382 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.gitlab-ci.yml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/.idea/
+-rw-rw-rw-   0 root         (0) root         (0)      176 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.idea/.gitignore
+-rw-rw-rw-   0 root         (0) root         (0)      391 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.idea/GitlabLint.xml
+-rw-rw-rw-   0 root         (0) root         (0)      284 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.idea/misc.xml
+-rw-rw-rw-   0 root         (0) root         (0)      265 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.idea/modules.xml
+-rw-rw-rw-   0 root         (0) root         (0)      168 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.idea/vcs.xml
+-rw-rw-rw-   0 root         (0) root         (0)      366 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.local-antora-playbook.yml
+-rw-rw-rw-   0 root         (0) root         (0)      905 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.pre-commit-config.yaml
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/.ruff
+-rw-r--r--   0 root         (0) root         (0)      186 2023-06-28 06:02:29.348637 gs-netsuite-api-1.1.3/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)      842 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/README.adoc
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/docs/
+-rw-rw-rw-   0 root         (0) root         (0)      141 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/docs/antora.yml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/docs/modules/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/docs/modules/ROOT/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/docs/modules/ROOT/examples/
+-rw-rw-rw-   0 root         (0) root         (0)       90 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/docs/modules/ROOT/nav.adoc
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.332637 gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/
+-rw-rw-rw-   0 root         (0) root         (0)     3361 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/api.adoc
+-rw-rw-rw-   0 root         (0) root         (0)     2996 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/convertion.adoc
+-rw-rw-rw-   0 root         (0) root         (0)      842 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/index.adoc
+-rw-rw-rw-   0 root         (0) root         (0)     2206 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/types.adoc
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.332637 gs-netsuite-api-1.1.3/example/
+-rw-rw-rw-   0 root         (0) root         (0)     1319 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/example/sample_item_fulfillment_api.py
+-rw-rw-rw-   0 root         (0) root         (0)     1311 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/example/sample_item_receipt_api.py
+-rw-rw-rw-   0 root         (0) root         (0)     1300 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/example/sample_product_api.py
+-rw-rw-rw-   0 root         (0) root         (0)     1820 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/example/sample_purchase_api.py
+-rw-rw-rw-   0 root         (0) root         (0)      556 2023-06-28 05:51:00.000000 gs-netsuite-api-1.1.3/example/sample_relationship_api.py
+-rw-rw-rw-   0 root         (0) root         (0)     1308 2023-06-27 05:06:56.000000 gs-netsuite-api-1.1.3/example/sample_sale_api.py
+-rw-rw-rw-   0 root         (0) root         (0)     1023 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/mkdocs.yml
+-rw-rw-rw-   0 root         (0) root         (0)      495 2023-06-22 14:42:03.000000 gs-netsuite-api-1.1.3/netsuite-api.iml
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/output/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/output/wsdl/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.332637 gs-netsuite-api-1.1.3/output/wsdl/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)   133803 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/wsdl/v2022_2_0/netsuite.wsdl
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/output/xsd/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/output/xsd/activities/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.332637 gs-netsuite-api-1.1.3/output/xsd/activities/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)    38231 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/activities/v2022_2_0/scheduling.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     7111 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/activities/v2022_2_0/schedulingTypes.xsd
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/output/xsd/documents/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.332637 gs-netsuite-api-1.1.3/output/xsd/documents/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)     8963 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/documents/v2022_2_0/fileCabinet.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     4282 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/documents/v2022_2_0/fileCabinetTypes.xsd
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/output/xsd/general/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.336637 gs-netsuite-api-1.1.3/output/xsd/general/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)    14530 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/general/v2022_2_0/communication.xsd
+-rw-rw-rw-   0 root         (0) root         (0)      915 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/general/v2022_2_0/communicationTypes.xsd
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.324637 gs-netsuite-api-1.1.3/output/xsd/lists/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.340637 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)   424972 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/accounting.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    40848 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/accountingTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    11949 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/employeeTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    31010 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/employees.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    27949 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/marketing.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     5751 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/marketingTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     7100 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/relationshipTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)   102099 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/relationships.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    16989 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/supplyChain.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     1222 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/supplyChainTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    29653 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/support.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     2906 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/supportTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     6213 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/website.xsd
+-rw-rw-rw-   0 root         (0) root         (0)      350 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/websiteTypes.xsd
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/output/xsd/platform/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.340637 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)   744517 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/common.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    59244 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/commonTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    47859 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/core.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    37883 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/coreTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    72361 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/faultTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     3764 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/faults.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    28339 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/messages.xsd
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/output/xsd/setup/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.340637 gs-netsuite-api-1.1.3/output/xsd/setup/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)   102180 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/setup/v2022_2_0/customization.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     4880 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/setup/v2022_2_0/customizationTypes.xsd
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/output/xsd/transactions/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.344637 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/
+-rw-rw-rw-   0 root         (0) root         (0)    13345 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/bank.xsd
+-rw-rw-rw-   0 root         (0) root         (0)      354 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/bankTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     3724 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/customerTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    75538 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/customers.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    10022 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/demandPlanning.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     2094 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/demandPlanningTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)      615 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/employeeTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    43650 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/employees.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     5844 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/financial.xsd
+-rw-rw-rw-   0 root         (0) root         (0)      561 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/financialTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    23444 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/general.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    49374 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/inventory.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     2071 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/inventoryTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)     1983 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/purchaseTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    64002 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/purchases.xsd
+-rw-rw-rw-   0 root         (0) root         (0)    32740 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/saleTypes.xsd
+-rw-rw-rw-   0 root         (0) root         (0)   141383 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/sales.xsd
+-rw-rw-rw-   0 root         (0) root         (0)      627 2023-06-22 14:42:03.000000 gs-netsuite-api-1.1.3/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 06:02:29.348637 gs-netsuite-api-1.1.3/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.328637 gs-netsuite-api-1.1.3/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.348637 gs-netsuite-api-1.1.3/src/gs_netsuite_api/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      160 2023-06-28 06:02:29.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api/_version.py
+-rw-rw-rw-   0 root         (0) root         (0)    27401 2023-06-28 05:48:05.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api/api.py
+-rw-rw-rw-   0 root         (0) root         (0)       60 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api/api.py.adoc
+-rw-rw-rw-   0 root         (0) root         (0)     4389 2023-06-28 05:48:05.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api/data_types.py
+-rw-rw-rw-   0 root         (0) root         (0)     4296 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api/ns_utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 06:02:29.348637 gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      186 2023-06-28 06:02:29.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     3270 2023-06-28 06:02:29.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 06:02:29.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       52 2023-06-28 06:02:29.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 06:02:29.000000 gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/top_level.txt
+-rwxrwxrwx   0 root         (0) root         (0)     3862 2023-06-22 14:37:57.000000 gs-netsuite-api-1.1.3/wsdldownloader.py
```

### Comparing `gs-netsuite-api-1.1.2/.gitignore` & `gs-netsuite-api-1.1.3/.gitignore`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/.pre-commit-config.yaml` & `gs-netsuite-api-1.1.3/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/README.adoc` & `gs-netsuite-api-1.1.3/README.adoc`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/api.adoc` & `gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/api.adoc`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/convertion.adoc` & `gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/convertion.adoc`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/index.adoc` & `gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/index.adoc`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/docs/modules/ROOT/pages/types.adoc` & `gs-netsuite-api-1.1.3/docs/modules/ROOT/pages/types.adoc`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/example/sample_item_fulfillment_api.py` & `gs-netsuite-api-1.1.3/example/sample_item_fulfillment_api.py`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/example/sample_item_receipt_api.py` & `gs-netsuite-api-1.1.3/example/sample_item_receipt_api.py`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/example/sample_product_api.py` & `gs-netsuite-api-1.1.3/example/sample_product_api.py`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/example/sample_purchase_api.py` & `gs-netsuite-api-1.1.3/example/sample_purchase_api.py`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/example/sample_sale_api.py` & `gs-netsuite-api-1.1.3/example/sample_sale_api.py`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/mkdocs.yml` & `gs-netsuite-api-1.1.3/mkdocs.yml`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/wsdl/v2022_2_0/netsuite.wsdl` & `gs-netsuite-api-1.1.3/output/wsdl/v2022_2_0/netsuite.wsdl`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/activities/v2022_2_0/scheduling.xsd` & `gs-netsuite-api-1.1.3/output/xsd/activities/v2022_2_0/scheduling.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/activities/v2022_2_0/schedulingTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/activities/v2022_2_0/schedulingTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/documents/v2022_2_0/fileCabinet.xsd` & `gs-netsuite-api-1.1.3/output/xsd/documents/v2022_2_0/fileCabinet.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/documents/v2022_2_0/fileCabinetTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/documents/v2022_2_0/fileCabinetTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/general/v2022_2_0/communication.xsd` & `gs-netsuite-api-1.1.3/output/xsd/general/v2022_2_0/communication.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/general/v2022_2_0/communicationTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/general/v2022_2_0/communicationTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/accounting.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/accounting.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/accountingTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/accountingTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/employeeTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/employeeTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/employees.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/employees.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/marketing.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/marketing.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/marketingTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/marketingTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/relationshipTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/relationshipTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/relationships.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/relationships.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/supplyChain.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/supplyChain.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/supplyChainTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/supplyChainTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/support.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/support.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/supportTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/supportTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/lists/v2022_2_0/website.xsd` & `gs-netsuite-api-1.1.3/output/xsd/lists/v2022_2_0/website.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/common.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/common.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/commonTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/commonTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/core.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/core.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/coreTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/coreTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/faultTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/faultTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/faults.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/faults.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/platform/v2022_2_0/messages.xsd` & `gs-netsuite-api-1.1.3/output/xsd/platform/v2022_2_0/messages.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/setup/v2022_2_0/customization.xsd` & `gs-netsuite-api-1.1.3/output/xsd/setup/v2022_2_0/customization.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/setup/v2022_2_0/customizationTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/setup/v2022_2_0/customizationTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/bank.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/bank.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/customerTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/customerTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/customers.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/customers.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/demandPlanning.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/demandPlanning.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/demandPlanningTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/demandPlanningTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/employeeTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/employeeTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/employees.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/employees.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/financial.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/financial.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/financialTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/financialTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/general.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/general.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/inventory.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/inventory.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/inventoryTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/inventoryTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/purchaseTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/purchaseTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/purchases.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/purchases.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/saleTypes.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/saleTypes.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/output/xsd/transactions/v2022_2_0/sales.xsd` & `gs-netsuite-api-1.1.3/output/xsd/transactions/v2022_2_0/sales.xsd`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/pyproject.toml` & `gs-netsuite-api-1.1.3/pyproject.toml`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/src/gs_netsuite_api/api.py` & `gs-netsuite-api-1.1.3/src/gs_netsuite_api/api.py`

 * *Files 1% similar despite different names*

```diff
@@ -545,14 +545,15 @@
             order_date=record.tranDate,
             state=record.status,
             # discountRate contient en fait des montants de réduction.
             discount_amount=record.discountRate,
             shipping_cost=record.shippingCost,
             is_quote=extract_custom_field(record, "custbodynv_is_quote"),
             shipping_country=record.shippingAddress.country,
+            custbodynv_sales_origin=extract_custom_field(record, "custbodynv_sales_origin"),
         )
 
         for sub_el in record.itemList.item:
             sale.lines.append(
                 SaleOrderLineData(
                     name=str(sub_el.line),
                     internalId=0,
@@ -649,8 +650,9 @@
 
     def _convert_to_data(self, record) -> RT:
         return RelationShip(
             internalId=record.internalId,
             name=record.entityId,
             company_name=record.companyName,
             email=record.email or record.altEmail,
+            custentitynv_vendor_lead_time=extract_custom_field(record, "custentitynv_vendor_lead_time"),
         )
```

### Comparing `gs-netsuite-api-1.1.2/src/gs_netsuite_api/data_types.py` & `gs-netsuite-api-1.1.3/src/gs_netsuite_api/data_types.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,14 +26,15 @@
         return RecordRef(internalId=record.internalId, name=record.name)
 
 
 @dataclasses.dataclass
 class RelationShip(RecordRef):
     company_name: str
     email: str
+    custentitynv_vendor_lead_time: int
 
 
 @dataclasses.dataclass
 class ProductData(RecordRef):
     """
     Classe contenant les champs "Catalogue" du fichier excel
     """
@@ -129,14 +130,15 @@
     total_tax_included: float
     order_date: datetime.datetime
     state: str
     discount_amount: float
     shipping_cost: float
     is_quote: bool
     shipping_country: str
+    custbodynv_sales_origin: str
     lines: List[SaleOrderLineData] = dataclasses.field(default_factory=list, repr=True)
 
 
 @dataclasses.dataclass
 class ItemMove(RecordRef):
     """
     Class convertit depuis
```

### Comparing `gs-netsuite-api-1.1.2/src/gs_netsuite_api/ns_utils.py` & `gs-netsuite-api-1.1.3/src/gs_netsuite_api/ns_utils.py`

 * *Files identical despite different names*

### Comparing `gs-netsuite-api-1.1.2/src/gs_netsuite_api.egg-info/SOURCES.txt` & `gs-netsuite-api-1.1.3/src/gs_netsuite_api.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -21,14 +21,15 @@
 docs/modules/ROOT/pages/convertion.adoc
 docs/modules/ROOT/pages/index.adoc
 docs/modules/ROOT/pages/types.adoc
 example/sample_item_fulfillment_api.py
 example/sample_item_receipt_api.py
 example/sample_product_api.py
 example/sample_purchase_api.py
+example/sample_relationship_api.py
 example/sample_sale_api.py
 output/wsdl/v2022_2_0/netsuite.wsdl
 output/xsd/activities/v2022_2_0/scheduling.xsd
 output/xsd/activities/v2022_2_0/schedulingTypes.xsd
 output/xsd/documents/v2022_2_0/fileCabinet.xsd
 output/xsd/documents/v2022_2_0/fileCabinetTypes.xsd
 output/xsd/general/v2022_2_0/communication.xsd
```

### Comparing `gs-netsuite-api-1.1.2/wsdldownloader.py` & `gs-netsuite-api-1.1.3/wsdldownloader.py`

 * *Files identical despite different names*


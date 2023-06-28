# Comparing `tmp/kuflow_rest-0.7.1.tar.gz` & `tmp/kuflow_rest-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kuflow_rest-0.7.1.tar", max compression
+gzip compressed data, was "kuflow_rest-0.8.0.tar", max compression
```

## Comparing `kuflow_rest-0.7.1.tar` & `kuflow_rest-0.8.0.tar`

### file list

```diff
@@ -1,86 +1,86 @@
--rw-r--r--   0        0        0      875 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/README.md
--rw-r--r--   0        0        0        6 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/VERSION
--rw-r--r--   0        0        0     1335 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/__init__.py
--rw-r--r--   0        0        0     1907 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/__init__.py
--rw-r--r--   0        0        0      599 2023-06-20 07:21:27.280168 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     6018 2023-06-20 07:21:27.280168 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_client.cpython-38.pyc
--rw-r--r--   0        0        0     2365 2023-06-20 07:21:27.308170 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_configuration.cpython-38.pyc
--rw-r--r--   0        0        0      732 2023-06-20 07:21:27.324171 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_patch.cpython-38.pyc
--rw-r--r--   0        0        0    57905 2023-06-20 07:21:27.300169 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_serialization.cpython-38.pyc
--rw-r--r--   0        0        0      731 2023-06-20 07:21:27.312170 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_vendor.cpython-38.pyc
--rw-r--r--   0        0        0      178 2023-06-20 07:21:27.308170 kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_version.cpython-38.pyc
--rw-r--r--   0        0        0     7108 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/_client.py
--rw-r--r--   0        0        0     3983 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/_configuration.py
--rw-r--r--   0        0        0      674 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/_patch.py
--rw-r--r--   0        0        0    78834 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/_serialization.py
--rw-r--r--   0        0        0     2007 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/_vendor.py
--rw-r--r--   0        0        0     1517 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/_version.py
--rw-r--r--   0        0        0     1854 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/__init__.py
--rw-r--r--   0        0        0     7256 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/_client.py
--rw-r--r--   0        0        0     4026 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/_configuration.py
--rw-r--r--   0        0        0      674 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/_patch.py
--rw-r--r--   0        0        0     2060 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/__init__.py
--rw-r--r--   0        0        0     7284 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_authentication_operations.py
--rw-r--r--   0        0        0      674 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_patch.py
--rw-r--r--   0        0        0     7894 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_principal_operations.py
--rw-r--r--   0        0        0    35197 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_process_operations.py
--rw-r--r--   0        0        0    62010 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_task_operations.py
--rw-r--r--   0        0        0     5465 2023-06-20 07:20:29.811020 kuflow_rest-0.7.1/kuflow_rest/_generated/models/__init__.py
--rw-r--r--   0        0        0     3261 2023-06-20 07:21:27.284168 kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     2558 2023-06-20 07:21:27.304170 kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/_enums.cpython-38.pyc
--rw-r--r--   0        0        0    65326 2023-06-20 07:21:27.288168 kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/_models.cpython-38.pyc
--rw-r--r--   0        0        0      739 2023-06-20 07:21:27.308170 kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/_patch.cpython-38.pyc
--rw-r--r--   0        0        0     3294 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/models/_enums.py
--rw-r--r--   0        0        0    75667 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/models/_models.py
--rw-r--r--   0        0        0      674 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/models/_patch.py
--rw-r--r--   0        0        0     2060 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__init__.py
--rw-r--r--   0        0        0      737 2023-06-20 07:21:27.308170 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     5603 2023-06-20 07:21:27.308170 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_authentication_operations.cpython-38.pyc
--rw-r--r--   0        0        0      743 2023-06-20 07:21:27.324171 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_patch.cpython-38.pyc
--rw-r--r--   0        0        0     6811 2023-06-20 07:21:27.312170 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_principal_operations.cpython-38.pyc
--rw-r--r--   0        0        0    28491 2023-06-20 07:21:27.316171 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_process_operations.cpython-38.pyc
--rw-r--r--   0        0        0    51369 2023-06-20 07:21:27.324171 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_task_operations.cpython-38.pyc
--rw-r--r--   0        0        0     7884 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_authentication_operations.py
--rw-r--r--   0        0        0      674 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_patch.py
--rw-r--r--   0        0        0     9804 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_principal_operations.py
--rw-r--r--   0        0        0    41967 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_process_operations.py
--rw-r--r--   0        0        0    76156 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_task_operations.py
--rw-r--r--   0        0        0       26 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_generated/py.typed
--rw-r--r--   0        0        0     7722 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/_kuflow_rest_client.py
--rw-r--r--   0        0        0     4771 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/models/__init__.py
--rw-r--r--   0        0        0     2858 2023-06-20 07:21:27.328172 kuflow_rest-0.7.1/kuflow_rest/models/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     4588 2023-06-20 07:21:27.328172 kuflow_rest-0.7.1/kuflow_rest/models/__pycache__/_models.cpython-38.pyc
--rw-r--r--   0        0        0     4581 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/models/_models.py
--rw-r--r--   0        0        0     1440 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/operations/__init__.py
--rw-r--r--   0        0        0      460 2023-06-20 07:21:27.324171 kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0     1665 2023-06-20 07:21:27.324171 kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_authentication_operations.cpython-38.pyc
--rw-r--r--   0        0        0     3408 2023-06-20 07:21:27.324171 kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_principal_operations.cpython-38.pyc
--rw-r--r--   0        0        0     9051 2023-06-20 07:21:27.328172 kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_process_operations.cpython-38.pyc
--rw-r--r--   0        0        0    16300 2023-06-20 07:21:27.328172 kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_task_operations.cpython-38.pyc
--rw-r--r--   0        0        0     2322 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/operations/_authentication_operations.py
--rw-r--r--   0        0        0     4113 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/operations/_principal_operations.py
--rw-r--r--   0        0        0     9530 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/operations/_process_operations.py
--rw-r--r--   0        0        0    17424 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/operations/_task_operations.py
--rw-r--r--   0        0        0     2046 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/__init__.py
--rw-r--r--   0        0        0      935 2023-06-20 07:21:27.328172 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0    10641 2023-06-20 07:21:27.332172 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_process_page_item_utils.cpython-38.pyc
--rw-r--r--   0        0        0     9710 2023-06-20 07:21:27.332172 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_process_save_element_command_utils.cpython-38.pyc
--rw-r--r--   0        0        0    10048 2023-06-20 07:21:27.332172 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_process_utils.cpython-38.pyc
--rw-r--r--   0        0        0    15009 2023-06-20 07:21:27.336173 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_page_item_utils.cpython-38.pyc
--rw-r--r--   0        0        0    13767 2023-06-20 07:21:27.336173 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_save_element_command_utils.cpython-38.pyc
--rw-r--r--   0        0        0    14250 2023-06-20 07:21:27.336173 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_save_json_forms_value_data_utils.cpython-38.pyc
--rw-r--r--   0        0        0    26632 2023-06-20 07:21:27.344173 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_utils.cpython-38.pyc
--rw-r--r--   0        0        0    15400 2023-06-20 07:21:27.332172 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/element_values.cpython-38.pyc
--rw-r--r--   0        0        0    17854 2023-06-20 07:21:27.340173 kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/json_forms.cpython-38.pyc
--rw-r--r--   0        0        0    13179 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_process_page_item_utils.py
--rw-r--r--   0        0        0    11649 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_process_save_element_command_utils.py
--rw-r--r--   0        0        0    11951 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_process_utils.py
--rw-r--r--   0        0        0    18240 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_task_page_item_utils.py
--rw-r--r--   0        0        0    16181 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_task_save_element_command_utils.py
--rw-r--r--   0        0        0    15393 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_task_save_json_forms_value_data_utils.py
--rw-r--r--   0        0        0    29357 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/_task_utils.py
--rw-r--r--   0        0        0    18805 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/element_values.py
--rw-r--r--   0        0        0    23991 2023-06-20 07:20:29.815020 kuflow_rest-0.7.1/kuflow_rest/utils/json_forms.py
--rw-r--r--   0        0        0      957 2023-06-20 07:21:45.177769 kuflow_rest-0.7.1/pyproject.toml
--rw-r--r--   0        0        0     1801 1970-01-01 00:00:00.000000 kuflow_rest-0.7.1/setup.py
--rw-r--r--   0        0        0     1639 1970-01-01 00:00:00.000000 kuflow_rest-0.7.1/PKG-INFO
+-rw-r--r--   0        0        0      875 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/README.md
+-rw-r--r--   0        0        0        6 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/VERSION
+-rw-r--r--   0        0        0     1335 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/kuflow_rest/__init__.py
+-rw-r--r--   0        0        0     1907 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/kuflow_rest/_generated/__init__.py
+-rw-r--r--   0        0        0      599 2023-06-28 08:19:26.270064 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0     6018 2023-06-28 08:19:26.274064 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_client.cpython-38.pyc
+-rw-r--r--   0        0        0     2365 2023-06-28 08:19:26.350071 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_configuration.cpython-38.pyc
+-rw-r--r--   0        0        0      732 2023-06-28 08:19:26.366073 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_patch.cpython-38.pyc
+-rw-r--r--   0        0        0    57905 2023-06-28 08:19:26.338070 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_serialization.cpython-38.pyc
+-rw-r--r--   0        0        0      731 2023-06-28 08:19:26.354072 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_vendor.cpython-38.pyc
+-rw-r--r--   0        0        0      178 2023-06-28 08:19:26.350071 kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_version.cpython-38.pyc
+-rw-r--r--   0        0        0     7108 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/kuflow_rest/_generated/_client.py
+-rw-r--r--   0        0        0     3983 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/kuflow_rest/_generated/_configuration.py
+-rw-r--r--   0        0        0      674 2023-06-28 08:18:27.324639 kuflow_rest-0.8.0/kuflow_rest/_generated/_patch.py
+-rw-r--r--   0        0        0    78834 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/_serialization.py
+-rw-r--r--   0        0        0     2007 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/_vendor.py
+-rw-r--r--   0        0        0     1517 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/_version.py
+-rw-r--r--   0        0        0     1854 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/__init__.py
+-rw-r--r--   0        0        0     7256 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/_client.py
+-rw-r--r--   0        0        0     4026 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/_configuration.py
+-rw-r--r--   0        0        0      674 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/_patch.py
+-rw-r--r--   0        0        0     2060 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/__init__.py
+-rw-r--r--   0        0        0     7284 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_authentication_operations.py
+-rw-r--r--   0        0        0      674 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_patch.py
+-rw-r--r--   0        0        0     7894 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_principal_operations.py
+-rw-r--r--   0        0        0    35197 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_process_operations.py
+-rw-r--r--   0        0        0    62010 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_task_operations.py
+-rw-r--r--   0        0        0     5465 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/models/__init__.py
+-rw-r--r--   0        0        0     3261 2023-06-28 08:19:26.326069 kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0     2558 2023-06-28 08:19:26.346071 kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/_enums.cpython-38.pyc
+-rw-r--r--   0        0        0    65326 2023-06-28 08:19:26.330069 kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/_models.cpython-38.pyc
+-rw-r--r--   0        0        0      739 2023-06-28 08:19:26.346071 kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/_patch.cpython-38.pyc
+-rw-r--r--   0        0        0     3294 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/models/_enums.py
+-rw-r--r--   0        0        0    75667 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/models/_models.py
+-rw-r--r--   0        0        0      674 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/models/_patch.py
+-rw-r--r--   0        0        0     2060 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__init__.py
+-rw-r--r--   0        0        0      737 2023-06-28 08:19:26.350071 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0     5603 2023-06-28 08:19:26.350071 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_authentication_operations.cpython-38.pyc
+-rw-r--r--   0        0        0      743 2023-06-28 08:19:26.366073 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_patch.cpython-38.pyc
+-rw-r--r--   0        0        0     6811 2023-06-28 08:19:26.354072 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_principal_operations.cpython-38.pyc
+-rw-r--r--   0        0        0    28491 2023-06-28 08:19:26.358072 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_process_operations.cpython-38.pyc
+-rw-r--r--   0        0        0    51369 2023-06-28 08:19:26.362072 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_task_operations.cpython-38.pyc
+-rw-r--r--   0        0        0     7884 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_authentication_operations.py
+-rw-r--r--   0        0        0      674 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_patch.py
+-rw-r--r--   0        0        0     9804 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_principal_operations.py
+-rw-r--r--   0        0        0    41967 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_process_operations.py
+-rw-r--r--   0        0        0    76156 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_task_operations.py
+-rw-r--r--   0        0        0       26 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_generated/py.typed
+-rw-r--r--   0        0        0     7744 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/_kuflow_rest_client.py
+-rw-r--r--   0        0        0     4768 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/models/__init__.py
+-rw-r--r--   0        0        0     2858 2023-06-28 08:19:26.370073 kuflow_rest-0.8.0/kuflow_rest/models/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0     4588 2023-06-28 08:19:26.370073 kuflow_rest-0.8.0/kuflow_rest/models/__pycache__/_models.cpython-38.pyc
+-rw-r--r--   0        0        0     4581 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/models/_models.py
+-rw-r--r--   0        0        0     1440 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/operations/__init__.py
+-rw-r--r--   0        0        0      460 2023-06-28 08:19:26.366073 kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0     1677 2023-06-28 08:19:26.366073 kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_authentication_operations.cpython-38.pyc
+-rw-r--r--   0        0        0     3420 2023-06-28 08:19:26.366073 kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_principal_operations.cpython-38.pyc
+-rw-r--r--   0        0        0     9051 2023-06-28 08:19:26.370073 kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_process_operations.cpython-38.pyc
+-rw-r--r--   0        0        0    16300 2023-06-28 08:19:26.370073 kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_task_operations.cpython-38.pyc
+-rw-r--r--   0        0        0     2346 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/operations/_authentication_operations.py
+-rw-r--r--   0        0        0     4137 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/operations/_principal_operations.py
+-rw-r--r--   0        0        0     9529 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/operations/_process_operations.py
+-rw-r--r--   0        0        0    17423 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/operations/_task_operations.py
+-rw-r--r--   0        0        0     2046 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/__init__.py
+-rw-r--r--   0        0        0      935 2023-06-28 08:19:26.370073 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0    10641 2023-06-28 08:19:26.374074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_process_page_item_utils.cpython-38.pyc
+-rw-r--r--   0        0        0     9710 2023-06-28 08:19:26.374074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_process_save_element_command_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    10048 2023-06-28 08:19:26.378074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_process_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    15009 2023-06-28 08:19:26.378074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_page_item_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    13767 2023-06-28 08:19:26.378074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_save_element_command_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    14250 2023-06-28 08:19:26.378074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_save_json_forms_value_data_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    26632 2023-06-28 08:19:26.382074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    15400 2023-06-28 08:19:26.374074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/element_values.cpython-38.pyc
+-rw-r--r--   0        0        0    17854 2023-06-28 08:19:26.382074 kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/json_forms.cpython-38.pyc
+-rw-r--r--   0        0        0    13179 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_process_page_item_utils.py
+-rw-r--r--   0        0        0    11649 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_process_save_element_command_utils.py
+-rw-r--r--   0        0        0    11951 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_process_utils.py
+-rw-r--r--   0        0        0    18223 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_task_page_item_utils.py
+-rw-r--r--   0        0        0    16164 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_task_save_element_command_utils.py
+-rw-r--r--   0        0        0    15376 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_task_save_json_forms_value_data_utils.py
+-rw-r--r--   0        0        0    29357 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/_task_utils.py
+-rw-r--r--   0        0        0    18805 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/element_values.py
+-rw-r--r--   0        0        0    23991 2023-06-28 08:18:27.328639 kuflow_rest-0.8.0/kuflow_rest/utils/json_forms.py
+-rw-r--r--   0        0        0      957 2023-06-28 08:19:43.731669 kuflow_rest-0.8.0/pyproject.toml
+-rw-r--r--   0        0        0     1801 1970-01-01 00:00:00.000000 kuflow_rest-0.8.0/setup.py
+-rw-r--r--   0        0        0     1639 1970-01-01 00:00:00.000000 kuflow_rest-0.8.0/PKG-INFO
```

### Comparing `kuflow_rest-0.7.1/README.md` & `kuflow_rest-0.8.0/README.md`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -19,12 +19,12 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
+from ._generated._serialization import Deserializer, Model, Serializer
 from ._kuflow_rest_client import KuFlowRestClient
-from ._generated._serialization import Deserializer, Serializer, Model
 
 __all__ = ["Deserializer", "KuFlowRestClient", "Model", "Serializer"]
-__version__ = "0.7.1"
+__version__ = "0.8.0"
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__init__.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/__init__.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/__init__.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 1907 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 7307 0000  U.......=S.ds...
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 7307 0000  U..........ds...
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0008 0000 0040 0000 0073 7e00 0000 6400  .....@...s~...d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 0100 6503 5a04 7a18 6400 6403  m.Z...e.Z.z.d.d.
 00000050: 6c05 6d06 5a07 0100 6400 6404 6c05 5400  l.m.Z...d.d.l.T.
 00000060: 5700 6e18 0400 6508 6b0a 724c 0100 0100  W.n...e.k.rL....
 00000070: 0100 6700 5a07 5900 6e02 5800 6400 6405  ..g.Z.Y.n.X.d.d.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_client.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_client.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 7108 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 10% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 c41b 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 c41b 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 9a00 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 6d04 5a04 0100 6400 6403 6c05  m.Z.m.Z...d.d.l.
 00000050: 6d06 5a06 0100 6400 6404 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
 00000060: 6d09 5a09 0100 6405 6406 6c0a 6d0b 5a0c  m.Z...d.d.l.m.Z.
 00000070: 0100 6405 6407 6c0d 6d0e 5a0e 0100 6405  ..d.d.l.m.Z...d.
@@ -217,22 +217,22 @@
 00000d80: 085f 0b74 0c7c 006a 037c 006a 017c 006a  ._.t.|.j.|.j.|.j
 00000d90: 087c 006a 0a83 047c 005f 0d74 0e7c 006a  .|.j...|._.t.|.j
 00000da0: 037c 006a 017c 006a 087c 006a 0a83 047c  .|.j.|.j.|.j...|
 00000db0: 005f 0f74 107c 006a 037c 006a 017c 006a  ._.t.|.j.|.j.|.j
 00000dc0: 087c 006a 0a83 047c 005f 1174 127c 006a  .|.j...|._.t.|.j
 00000dd0: 037c 006a 017c 006a 087c 006a 0a83 047c  .|.j.|.j.|.j...|
 00000de0: 005f 1364 0053 0029 064e 7214 0000 0029  ._.d.S.).Nr....)
-00000df0: 02da 0862 6173 655f 7572 6cda 0663 6f6e  ...base_url..con
+00000df0: 025a 0862 6173 655f 7572 6cda 0663 6f6e  .Z.base_url..con
 00000e00: 6669 6763 0100 0000 0000 0000 0000 0000  figc............
 00000e10: 0300 0000 0500 0000 5300 0000 7320 0000  ........S...s ..
 00000e20: 0069 007c 005d 185c 027d 017d 0274 007c  .i.|.].\.}.}.t.|
 00000e30: 0274 0183 0272 047c 017c 0293 0271 0453  .t...r.|.|...q.S
 00000e40: 00a9 0029 02da 0a69 7369 6e73 7461 6e63  ...)...isinstanc
 00000e50: 65da 0474 7970 6529 03da 022e 30da 016b  e..type)....0..k
-00000e60: da01 7672 1900 0000 7219 0000 00fa 452f  ..vr....r.....E/
+00000e60: da01 7672 1800 0000 7218 0000 00fa 452f  ..vr....r.....E/
 00000e70: 776f 726b 2f6b 7566 6c6f 772d 7364 6b2d  work/kuflow-sdk-
 00000e80: 7079 7468 6f6e 2f6b 7566 6c6f 772d 7265  python/kuflow-re
 00000e90: 7374 2f6b 7566 6c6f 775f 7265 7374 2f5f  st/kuflow_rest/_
 00000ea0: 6765 6e65 7261 7465 642f 5f63 6c69 656e  generated/_clien
 00000eb0: 742e 7079 da0a 3c64 6963 7463 6f6d 703e  t.py..<dictcomp>
 00000ec0: 7900 0000 7308 0000 0006 0006 000a 0002  y...s...........
 00000ed0: 007a 2d4b 7546 6c6f 7752 6573 7443 6c69  .z-KuFlowRestCli
@@ -241,22 +241,22 @@
 00000f00: 4629 1472 0a00 0000 da07 5f63 6f6e 6669  F).r......_confi
 00000f10: 6772 0500 0000 da07 5f63 6c69 656e 74da  gr......_client.
 00000f20: 075f 6d6f 6465 6c73 da08 5f5f 6469 6374  ._models..__dict
 00000f30: 5f5f da05 6974 656d 7372 0c00 0000 da0a  __..itemsr......
 00000f40: 5f73 6572 6961 6c69 7a65 720b 0000 005a  _serializer....Z
 00000f50: 0c5f 6465 7365 7269 616c 697a 655a 1663  ._deserializeZ.c
 00000f60: 6c69 656e 745f 7369 6465 5f76 616c 6964  lient_side_valid
-00000f70: 6174 696f 6e72 0d00 0000 da0e 6175 7468  ationr......auth
-00000f80: 656e 7469 6361 7469 6f6e 720e 0000 00da  enticationr.....
+00000f70: 6174 696f 6e72 0d00 0000 5a0e 6175 7468  ationr....Z.auth
+00000f80: 656e 7469 6361 7469 6f6e 720e 0000 005a  enticationr....Z
 00000f90: 0970 7269 6e63 6970 616c 720f 0000 00da  .principalr.....
 00000fa0: 0770 726f 6365 7373 7210 0000 00da 0474  .processr......t
 00000fb0: 6173 6b29 05da 0473 656c 6672 1400 0000  ask)...selfr....
 00000fc0: 7213 0000 0072 1500 0000 5a0d 636c 6965  r....r....Z.clie
-00000fd0: 6e74 5f6d 6f64 656c 7372 1900 0000 7219  nt_modelsr....r.
-00000fe0: 0000 0072 1f00 0000 da08 5f5f 696e 6974  ...r......__init
+00000fd0: 6e74 5f6d 6f64 656c 7372 1800 0000 7218  nt_modelsr....r.
+00000fe0: 0000 0072 1e00 0000 da08 5f5f 696e 6974  ...r......__init
 00000ff0: 5f5f 7300 0000 7314 0000 0000 0314 0118  __s...s.........
 00001000: 0214 010a 010a 0108 0118 0118 0118 017a  ...............z
 00001010: 194b 7546 6c6f 7752 6573 7443 6c69 656e  .KuFlowRestClien
 00001020: 742e 5f5f 696e 6974 5f5f 2903 da07 7265  t.__init__)...re
 00001030: 7175 6573 7472 1500 0000 7216 0000 0063  questr....r....c
 00001040: 0200 0000 0000 0000 0000 0000 0400 0000  ................
 00001050: 0300 0000 4b00 0000 7328 0000 0074 007c  ....K...s(...t.|
@@ -309,69 +309,69 @@
 00001340: 206e 6574 776f 726b 2063 616c 6c2e 2044   network call. D
 00001350: 6f65 7320 6e6f 7420 646f 2065 7272 6f72  oes not do error
 00001360: 2068 616e 646c 696e 6720 6f6e 2079 6f75   handling on you
 00001370: 7220 7265 7370 6f6e 7365 2e0a 2020 2020  r response..    
 00001380: 2020 2020 3a72 7479 7065 3a20 7e61 7a75      :rtype: ~azu
 00001390: 7265 2e63 6f72 652e 7265 7374 2e48 7474  re.core.rest.Htt
 000013a0: 7052 6573 706f 6e73 650a 2020 2020 2020  pResponse.      
-000013b0: 2020 2905 7202 0000 0072 2200 0000 da0a    ).r....r".....
+000013b0: 2020 2905 7202 0000 0072 2100 0000 5a0a    ).r....r!...Z.
 000013c0: 666f 726d 6174 5f75 726c da03 7572 6cda  format_url..url.
 000013d0: 0c73 656e 645f 7265 7175 6573 7429 0472  .send_request).r
-000013e0: 2b00 0000 722d 0000 0072 1500 0000 5a0c  +...r-...r....Z.
-000013f0: 7265 7175 6573 745f 636f 7079 7219 0000  request_copyr...
-00001400: 0072 1900 0000 721f 0000 0072 3000 0000  .r....r....r0...
+000013e0: 2800 0000 722a 0000 0072 1500 0000 5a0c  (...r*...r....Z.
+000013f0: 7265 7175 6573 745f 636f 7079 7218 0000  request_copyr...
+00001400: 0072 1800 0000 721e 0000 0072 2c00 0000  .r....r....r,...
 00001410: 8200 0000 7306 0000 0000 1208 0110 017a  ....s..........z
 00001420: 1d4b 7546 6c6f 7752 6573 7443 6c69 656e  .KuFlowRestClien
 00001430: 742e 7365 6e64 5f72 6571 7565 7374 2901  t.send_request).
 00001440: 7216 0000 0063 0100 0000 0000 0000 0000  r....c..........
 00001450: 0000 0100 0000 0200 0000 4300 0000 730e  ..........C...s.
 00001460: 0000 007c 006a 00a0 01a1 0001 0064 0053  ...|.j.......d.S
-00001470: 00a9 014e 2902 7222 0000 00da 0563 6c6f  ...N).r".....clo
-00001480: 7365 a901 722b 0000 0072 1900 0000 7219  se..r+...r....r.
-00001490: 0000 0072 1f00 0000 7232 0000 0098 0000  ...r....r2......
+00001470: 00a9 014e 2902 7221 0000 00da 0563 6c6f  ...N).r!.....clo
+00001480: 7365 a901 7228 0000 0072 1800 0000 7218  se..r(...r....r.
+00001490: 0000 0072 1e00 0000 722e 0000 0098 0000  ...r....r.......
 000014a0: 0073 0200 0000 0001 7a16 4b75 466c 6f77  .s......z.KuFlow
 000014b0: 5265 7374 436c 6965 6e74 2e63 6c6f 7365  RestClient.close
 000014c0: 6301 0000 0000 0000 0000 0000 0001 0000  c...............
 000014d0: 0002 0000 0043 0000 0073 0e00 0000 7c00  .....C...s....|.
-000014e0: 6a00 a001 a100 0100 7c00 5300 7231 0000  j.......|.S.r1..
-000014f0: 0029 0272 2200 0000 da09 5f5f 656e 7465  .).r".....__ente
-00001500: 725f 5f72 3300 0000 7219 0000 0072 1900  r__r3...r....r..
-00001510: 0000 721f 0000 0072 3400 0000 9b00 0000  ..r....r4.......
+000014e0: 6a00 a001 a100 0100 7c00 5300 722d 0000  j.......|.S.r-..
+000014f0: 0029 0272 2100 0000 da09 5f5f 656e 7465  .).r!.....__ente
+00001500: 725f 5f72 2f00 0000 7218 0000 0072 1800  r__r/...r....r..
+00001510: 0000 721e 0000 0072 3000 0000 9b00 0000  ..r....r0.......
 00001520: 7304 0000 0000 010a 017a 1a4b 7546 6c6f  s........z.KuFlo
 00001530: 7752 6573 7443 6c69 656e 742e 5f5f 656e  wRestClient.__en
 00001540: 7465 725f 5f29 02da 0b65 7863 5f64 6574  ter__)...exc_det
 00001550: 6169 6c73 7216 0000 0063 0100 0000 0000  ailsr....c......
 00001560: 0000 0000 0000 0200 0000 0200 0000 4700  ..............G.
 00001570: 0000 7310 0000 007c 006a 006a 017c 018e  ..s....|.j.j.|..
-00001580: 0001 0064 0053 0072 3100 0000 2902 7222  ...d.S.r1...).r"
+00001580: 0001 0064 0053 0072 2d00 0000 2902 7221  ...d.S.r-...).r!
 00001590: 0000 00da 085f 5f65 7869 745f 5f29 0272  .....__exit__).r
-000015a0: 2b00 0000 7235 0000 0072 1900 0000 7219  +...r5...r....r.
-000015b0: 0000 0072 1f00 0000 7236 0000 009f 0000  ...r....r6......
+000015a0: 2800 0000 7231 0000 0072 1800 0000 7218  (...r1...r....r.
+000015b0: 0000 0072 1e00 0000 7232 0000 009f 0000  ...r....r2......
 000015c0: 0073 0200 0000 0001 7a19 4b75 466c 6f77  .s......z.KuFlow
 000015d0: 5265 7374 436c 6965 6e74 2e5f 5f65 7869  RestClient.__exi
 000015e0: 745f 5f29 0dda 085f 5f6e 616d 655f 5fda  t__)...__name__.
 000015f0: 0a5f 5f6d 6f64 756c 655f 5fda 0c5f 5f71  .__module__..__q
 00001600: 7561 6c6e 616d 655f 5fda 075f 5f64 6f63  ualname__..__doc
-00001610: 5f5f da03 7374 7272 0300 0000 722c 0000  __..strr....r,..
-00001620: 0072 0600 0000 7207 0000 0072 3000 0000  .r....r....r0...
-00001630: 7232 0000 0072 3400 0000 7236 0000 0072  r2...r4...r6...r
-00001640: 1900 0000 7219 0000 0072 1900 0000 721f  ....r....r....r.
+00001610: 5f5f da03 7374 7272 0300 0000 7229 0000  __..strr....r)..
+00001620: 0072 0600 0000 7207 0000 0072 2c00 0000  .r....r....r,...
+00001630: 722e 0000 0072 3000 0000 7232 0000 0072  r....r0...r2...r
+00001640: 1800 0000 7218 0000 0072 1800 0000 721e  ....r....r....r.
 00001650: 0000 0072 1200 0000 3100 0000 7318 0000  ...r....1...s...
 00001660: 0008 0104 4202 ff04 0102 0002 0002 0102  ....B...........
 00001670: fe0c 0f12 160e 030e 0472 1200 0000 4e29  .........r....N)
 00001680: 1ada 0463 6f70 7972 0200 0000 da06 7479  ...copyr......ty
 00001690: 7069 6e67 7203 0000 0072 0400 0000 5a0a  pingr....r....Z.
 000016a0: 617a 7572 652e 636f 7265 7205 0000 005a  azure.corer....Z
 000016b0: 0f61 7a75 7265 2e63 6f72 652e 7265 7374  .azure.core.rest
 000016c0: 7206 0000 0072 0700 0000 da00 7209 0000  r....r......r...
-000016d0: 0072 2300 0000 5a0e 5f63 6f6e 6669 6775  .r#...Z._configu
+000016d0: 0072 2200 0000 5a0e 5f63 6f6e 6669 6775  .r"...Z._configu
 000016e0: 7261 7469 6f6e 720a 0000 005a 0e5f 7365  rationr....Z._se
 000016f0: 7269 616c 697a 6174 696f 6e72 0b00 0000  rializationr....
 00001700: 720c 0000 00da 0a6f 7065 7261 7469 6f6e  r......operation
 00001710: 7372 0d00 0000 720e 0000 0072 0f00 0000  sr....r....r....
-00001720: 7210 0000 00da 1661 7a75 7265 2e63 6f72  r......azure.cor
+00001720: 7210 0000 005a 1661 7a75 7265 2e63 6f72  r....Z.azure.cor
 00001730: 652e 6372 6564 656e 7469 616c 7372 1100  e.credentialsr..
-00001740: 0000 7212 0000 0072 1900 0000 7219 0000  ..r....r....r...
-00001750: 0072 1900 0000 721f 0000 00da 083c 6d6f  .r....r......<mo
+00001740: 0000 7212 0000 0072 1800 0000 7218 0000  ..r....r....r...
+00001750: 0072 1800 0000 721e 0000 00da 083c 6d6f  .r....r......<mo
 00001760: 6475 6c65 3e21 0000 0073 1400 0000 0c01  dule>!...s......
 00001770: 1002 0c01 1002 0c01 0c01 1001 1802 0402  ................
 00001780: 0c03                                     ..
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_configuration.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_configuration.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 3983 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 8f0f 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 8f0f 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 5800 0000 6400  .....@...sX...d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
 00000040: 6402 6c03 6d04 5a04 0100 6400 6403 6c05  d.l.m.Z...d.d.l.
 00000050: 6d06 5a06 0100 6404 6405 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
 00000060: 0100 6502 7244 6400 6406 6c09 6d0a 5a0a  ..e.rDd.d.l.m.Z.
 00000070: 0100 4700 6407 6408 8400 6408 6504 8303  ..G.d.d...d.e...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_patch.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_patch.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 674 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 14% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 a202 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 a202 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 2e00 0000 5500  .....@...s....U.
 00000030: 6400 5a00 6401 6402 6c01 6d02 5a02 0100  d.Z.d.d.l.m.Z...
 00000040: 6700 5a03 6502 6504 1900 6505 6403 3c00  g.Z.e.e...e.d.<.
 00000050: 6404 6405 8400 5a06 6406 5300 2907 7a7b  d.d...Z.d.S.).z{
 00000060: 4375 7374 6f6d 697a 6520 6765 6e65 7261  Customize genera
 00000070: 7465 6420 636f 6465 2068 6572 652e 0a0a  ted code here...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_serialization.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_serialization.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 78834 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 f233 0100  U.......=S.d.3..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 f233 0100  U..........d.3..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0008 0000 0040 0000 0073 c602 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
 00000040: 6402 6c03 5a03 6400 6402 6c04 5a04 6400  d.l.Z.d.d.l.Z.d.
 00000050: 6402 6c05 5a05 6400 6402 6c06 5a06 6400  d.l.Z.d.d.l.Z.d.
 00000060: 6403 6c07 6d08 5a08 0100 6400 6402 6c09  d.l.m.Z...d.d.l.
 00000070: 5a09 6400 6402 6c0a 5a0a 6400 6402 6c0b  Z.d.d.l.Z.d.d.l.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/__pycache__/_vendor.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/__pycache__/_vendor.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 2007 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 d707 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 d707 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0002 0000 0040 0000 0073 1c00 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6402  d.l.m.Z.m.Z...d.
 00000040: 6403 8400 5a03 6404 5300 2905 e900 0000  d...Z.d.S.).....
 00000050: 0029 02da 044c 6973 74da 0463 6173 7463  .)...List..castc
 00000060: 0100 0000 0000 0000 0000 0000 0400 0000  ................
 00000070: 0a00 0000 0b00 0000 7376 0000 007c 00a0  ........sv...|..
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/_client.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/_client.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/_configuration.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/_configuration.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/_patch.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/_patch.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/_serialization.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/_serialization.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/_vendor.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/_vendor.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/_version.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/_version.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,8 +26,8 @@
 # --------------------------------------------------------------------------
 #
 # Code generated by Microsoft (R) AutoRest Code Generator.
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 #
 # --------------------------------------------------------------------------
 
-VERSION = "0.7.1"
+VERSION = "0.8.0"
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/__init__.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/_client.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/_client.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/_configuration.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/_configuration.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/_patch.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/_patch.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/__init__.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_authentication_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_authentication_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_patch.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_patch.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_principal_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_principal_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_process_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_process_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/aio/operations/_task_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/aio/operations/_task_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/__init__.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/__init__.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/__init__.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 5465 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 5915 0000  U.......=S.dY...
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 5915 0000  U..........dY...
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0037 0000 0040 0000 0073 4403 0000 6400  .7...@...sD...d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c00  d.l.m.Z...d.d.l.
 00000040: 6d02 5a02 0100 6400 6403 6c00 6d03 5a03  m.Z...d.d.l.m.Z.
 00000050: 0100 6400 6404 6c00 6d04 5a04 0100 6400  ..d.d.l.m.Z...d.
 00000060: 6405 6c00 6d05 5a05 0100 6400 6406 6c00  d.l.m.Z...d.d.l.
 00000070: 6d06 5a06 0100 6400 6407 6c00 6d07 5a07  m.Z...d.d.l.m.Z.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/_enums.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/_enums.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 3294 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 de0c 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 de0c 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0007 0000 0040 0000 0073 e200 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 0100 4700 6403 6404 8400 6404  m.Z...G.d.d...d.
 00000050: 6504 6501 6503 6405 8d05 5a05 4700 6406  e.e.e.d...Z.G.d.
 00000060: 6407 8400 6407 6504 6501 6503 6405 8d05  d...d.e.e.e.d...
 00000070: 5a06 4700 6408 6409 8400 6409 6504 6501  Z.G.d.d...d.e.e.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/_models.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/_models.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 75667 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 9327 0100  U.......=S.d.'..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 9327 0100  U..........d.'..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 8e03 0000 6400  .....@...s....d.
 00000030: 6401 6c00 5a00 6400 6401 6c01 5a01 6400  d.l.Z.d.d.l.Z.d.
 00000040: 6402 6c02 6d03 5a03 6d04 5a04 6d05 5a05  d.l.m.Z.m.Z.m.Z.
 00000050: 6d06 5a06 6d07 5a07 6d08 5a08 0100 6403  m.Z.m.Z.m.Z...d.
 00000060: 6404 6c09 6d0a 5a0a 0100 6501 6a0b 6405  d.l.m.Z...e.j.d.
 00000070: 6b05 7254 6400 6406 6c02 6d0c 5a0c 0100  k.rTd.d.l.m.Z...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/__pycache__/_patch.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/__pycache__/_patch.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 674 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 14% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 a202 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 a202 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 2e00 0000 5500  .....@...s....U.
 00000030: 6400 5a00 6401 6402 6c01 6d02 5a02 0100  d.Z.d.d.l.m.Z...
 00000040: 6700 5a03 6502 6504 1900 6505 6403 3c00  g.Z.e.e...e.d.<.
 00000050: 6404 6405 8400 5a06 6406 5300 2907 7a7b  d.d...Z.d.S.).z{
 00000060: 4375 7374 6f6d 697a 6520 6765 6e65 7261  Customize genera
 00000070: 7465 6420 636f 6465 2068 6572 652e 0a0a  ted code here...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/_enums.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/_enums.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/_models.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/_models.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/models/_patch.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/models/_patch.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__init__.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/__init__.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/__init__.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 2060 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 0c08 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 0c08 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 7a00 0000 6400  .....@...sz...d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 0100 6400 6403 6c04 6d05 5a05  m.Z...d.d.l.m.Z.
 00000050: 0100 6400 6404 6c06 6d07 5a07 0100 6400  ..d.d.l.m.Z...d.
 00000060: 6405 6c08 6d09 5a0a 0100 6400 6406 6c08  d.l.m.Z...d.d.l.
 00000070: 5400 6400 6407 6c08 6d0b 5a0c 0100 6408  T.d.d.l.m.Z...d.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_authentication_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_authentication_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 7884 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 cc1e 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 cc1e 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0007 0000 0040 0000 0073 0401 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 6d04 5a04 6d05 5a05 6d06 5a06  m.Z.m.Z.m.Z.m.Z.
 00000050: 6d07 5a07 6d08 5a08 6d09 5a09 6d0a 5a0a  m.Z.m.Z.m.Z.m.Z.
 00000060: 0100 6400 6403 6c0b 6d0c 5a0c 6d0d 5a0d  ..d.d.l.m.Z.m.Z.
 00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_patch.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_patch.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 674 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 14% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 a202 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 a202 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 2e00 0000 5500  .....@...s....U.
 00000030: 6400 5a00 6401 6402 6c01 6d02 5a02 0100  d.Z.d.d.l.m.Z...
 00000040: 6700 5a03 6502 6504 1900 6505 6403 3c00  g.Z.e.e...e.d.<.
 00000050: 6404 6405 8400 5a06 6406 5300 2907 7a7b  d.d...Z.d.S.).z{
 00000060: 4375 7374 6f6d 697a 6520 6765 6e65 7261  Customize genera
 00000070: 7465 6420 636f 6465 2068 6572 652e 0a0a  ted code here...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_principal_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_principal_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 9804 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 4c26 0000  U.......=S.dL&..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 4c26 0000  U..........dL&..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0009 0000 0040 0000 0073 4801 0000 6400  .....@...sH...d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
 00000040: 6d04 5a04 6d05 5a05 6d06 5a06 6d07 5a07  m.Z.m.Z.m.Z.m.Z.
 00000050: 0100 6400 6402 6c08 6d09 5a09 6d0a 5a0a  ..d.d.l.m.Z.m.Z.
 00000060: 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e  m.Z.m.Z.m.Z.m.Z.
 00000070: 0100 6400 6403 6c0f 6d10 5a10 0100 6400  ..d.d.l.m.Z...d.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_process_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_process_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 41967 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 efa3 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 efa3 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0008 0000 0040 0000 0073 c201 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 6d04 5a04 6d05 5a05 6d06 5a06  m.Z.m.Z.m.Z.m.Z.
 00000050: 6d07 5a07 6d08 5a08 6d09 5a09 6d0a 5a0a  m.Z.m.Z.m.Z.m.Z.
 00000060: 6d0b 5a0b 0100 6400 6403 6c0c 6d0d 5a0d  m.Z...d.d.l.m.Z.
 00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/__pycache__/_task_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/__pycache__/_task_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 76156 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 7c29 0100  U.......=S.d|)..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 7c29 0100  U..........d|)..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 000b 0000 0040 0000 0073 9c02 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 6d04 5a04 6d05 5a05 6d06 5a06  m.Z.m.Z.m.Z.m.Z.
 00000050: 6d07 5a07 6d08 5a08 6d09 5a09 6d0a 5a0a  m.Z.m.Z.m.Z.m.Z.
 00000060: 6d0b 5a0b 6d0c 5a0c 0100 6400 6403 6c0d  m.Z.m.Z...d.d.l.
 00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_authentication_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_authentication_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_patch.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_patch.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_principal_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_principal_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_process_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_process_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_generated/operations/_task_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/_generated/operations/_task_operations.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/_kuflow_rest_client.py` & `kuflow_rest-0.8.0/kuflow_rest/_kuflow_rest_client.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,24 +20,24 @@
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 
+import base64
 import platform
 import sys
-import base64
-
 from typing import Any, Optional
+
 from azure.core.credentials import AccessToken
 from azure.core.pipeline.policies import SansIOHTTPPolicy
 
-from ._generated import VERSION, KuFlowRestClient as KuFlowRestClientGenerated
-
+from ._generated import VERSION
+from ._generated import KuFlowRestClient as KuFlowRestClientGenerated
 from .operations import AuthenticationOperations, PrincipalOperations, ProcessOperations, TaskOperations
 
 
 class KuFlowClientTokenCredential:
     def __init__(
         self,
         client_id: str,
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/models/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/models/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,84 +19,81 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from .._generated.models import __all__ as _all_generated_models
-
 from .._generated.models import (
     AbstractAudited,
+    AuditedObjectType,
     Authentication,
     DefaultError,
     DefaultErrorInfo,
     JsonFormsValue,
     Log,
+    LogLevel,
     Page,
+    PagedObjectType,
     PageMetadata,
     Principal,
     PrincipalApplication,
     PrincipalPage,
+    PrincipalType,
     PrincipalUser,
     Process,
     ProcessChangeInitiatorCommand,
     ProcessDefinitionSummary,
     ProcessDeleteElementCommand,
     ProcessElementValue,
     ProcessElementValueNumber,
     ProcessElementValueString,
+    ProcessElementValueType,
     ProcessPage,
     ProcessPageItem,
     ProcessSaveElementCommand,
+    ProcessState,
     RelatedProcess,
     Task,
     TaskAssignCommand,
     TaskDefinitionSummary,
     TaskDeleteElementCommand,
     TaskDeleteElementValueDocumentCommand,
     TaskElementValue,
     TaskElementValueDocument,
     TaskElementValueDocumentItem,
     TaskElementValueNumber,
     TaskElementValueObject,
     TaskElementValuePrincipal,
     TaskElementValuePrincipalItem,
     TaskElementValueString,
+    TaskElementValueType,
     TaskPage,
     TaskPageItem,
     TaskSaveElementCommand,
     TaskSaveJsonFormsValueDataCommand,
     TaskSaveJsonFormsValueDocumentResponseCommand,
+    TaskState,
     WebhookEvent,
     WebhookEventProcessStateChanged,
     WebhookEventProcessStateChangedData,
     WebhookEventTaskStateChanged,
     WebhookEventTaskStateChangedData,
-    AuditedObjectType,
-    LogLevel,
-    PagedObjectType,
-    PrincipalType,
-    ProcessElementValueType,
-    ProcessState,
-    TaskElementValueType,
-    TaskState,
     WebhookType,
 )
-
+from .._generated.models import __all__ as _all_generated_models
 from ._models import (
     Document,
     JsonFormsFile,
     JsonFormsPrincipal,
+    ProcessSaveUserActionValueDocumentCommand,
     TaskSaveElementValueDocumentCommand,
     TaskSaveJsonFormsValueDocumentRequestCommand,
-    ProcessSaveUserActionValueDocumentCommand,
 )
 
-
 __all__ = [
     # From _generated.models
     "AbstractAudited",
     "Authentication",
     "DefaultError",
     "DefaultErrorInfo",
     "JsonFormsValue",
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/models/__pycache__/__init__.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/models/__pycache__/__init__.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 4771 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 5% similar despite different names*

```diff
@@ -1,178 +1,178 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 a312 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 a012 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 003d 0000 0040 0000 0073 aa01 0000 6400  .=...@...s....d.
-00000030: 6401 6c00 6d01 5a02 0100 6400 6402 6c00  d.l.m.Z...d.d.l.
-00000040: 6d03 5a03 6d04 5a04 6d05 5a05 6d06 5a06  m.Z.m.Z.m.Z.m.Z.
-00000050: 6d07 5a07 6d08 5a08 6d09 5a09 6d0a 5a0a  m.Z.m.Z.m.Z.m.Z.
-00000060: 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0f 5a0f 6d10 5a10 6d11 5a11 6d12 5a12  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d13 5a13 6d14 5a14 6d15 5a15 6d16 5a16  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d17 5a17 6d18 5a18 6d19 5a19 6d1a 5a1a  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d1b 5a1b 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e  m.Z.m.Z.m.Z.m.Z.
-000000b0: 6d1f 5a1f 6d20 5a20 6d21 5a21 6d22 5a22  m.Z.m Z m!Z!m"Z"
-000000c0: 6d23 5a23 6d24 5a24 6d25 5a25 6d26 5a26  m#Z#m$Z$m%Z%m&Z&
-000000d0: 6d27 5a27 6d28 5a28 6d29 5a29 6d2a 5a2a  m'Z'm(Z(m)Z)m*Z*
-000000e0: 6d2b 5a2b 6d2c 5a2c 6d2d 5a2d 6d2e 5a2e  m+Z+m,Z,m-Z-m.Z.
-000000f0: 6d2f 5a2f 6d30 5a30 6d31 5a31 6d32 5a32  m/Z/m0Z0m1Z1m2Z2
-00000100: 6d33 5a33 6d34 5a34 6d35 5a35 6d36 5a36  m3Z3m4Z4m5Z5m6Z6
-00000110: 6d37 5a37 6d38 5a38 6d39 5a39 0100 6403  m7Z7m8Z8m9Z9..d.
+00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
+00000040: 6d04 5a04 6d05 5a05 6d06 5a06 6d07 5a07  m.Z.m.Z.m.Z.m.Z.
+00000050: 6d08 5a08 6d09 5a09 6d0a 5a0a 6d0b 5a0b  m.Z.m.Z.m.Z.m.Z.
+00000060: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000070: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d20 5a20 6d21 5a21 6d22 5a22 6d23 5a23  m Z m!Z!m"Z"m#Z#
+000000c0: 6d24 5a24 6d25 5a25 6d26 5a26 6d27 5a27  m$Z$m%Z%m&Z&m'Z'
+000000d0: 6d28 5a28 6d29 5a29 6d2a 5a2a 6d2b 5a2b  m(Z(m)Z)m*Z*m+Z+
+000000e0: 6d2c 5a2c 6d2d 5a2d 6d2e 5a2e 6d2f 5a2f  m,Z,m-Z-m.Z.m/Z/
+000000f0: 6d30 5a30 6d31 5a31 6d32 5a32 6d33 5a33  m0Z0m1Z1m2Z2m3Z3
+00000100: 6d34 5a34 6d35 5a35 6d36 5a36 6d37 5a37  m4Z4m5Z5m6Z6m7Z7
+00000110: 0100 6400 6402 6c00 6d38 5a39 0100 6403  ..d.d.l.m8Z9..d.
 00000120: 6404 6c3a 6d3b 5a3b 6d3c 5a3c 6d3d 5a3d  d.l:m;Z;m<Z<m=Z=
 00000130: 6d3e 5a3e 6d3f 5a3f 6d40 5a40 0100 6405  m>Z>m?Z?m@Z@..d.
 00000140: 6406 6407 6408 6409 640a 640b 640c 640d  d.d.d.d.d.d.d.d.
 00000150: 640e 640f 6410 6411 6412 6413 6414 6415  d.d.d.d.d.d.d.d.
 00000160: 6416 6417 6418 6419 641a 641b 641c 641d  d.d.d.d.d.d.d.d.
 00000170: 641e 641f 6420 6421 6422 6423 6424 6425  d.d.d d!d"d#d$d%
 00000180: 6426 6427 6428 6429 642a 642b 642c 642d  d&d'd(d)d*d+d,d-
 00000190: 642e 642f 6430 6431 6432 6433 6434 6435  d.d/d0d1d2d3d4d5
 000001a0: 6436 6437 6438 6439 643a 643b 643c 643d  d6d7d8d9d:d;d<d=
-000001b0: 643e 643f 6440 6441 673d 5a01 6541 6442  d>d?d@dAg=Z.eAdB
-000001c0: 6443 8400 6502 4400 8301 8301 9001 73a6  dC..e.D.......s.
-000001d0: 7442 8201 6444 5300 2945 e902 0000 00a9  tB..dDS.)E......
-000001e0: 01da 075f 5f61 6c6c 5f5f 2937 da0f 4162  ...__all__)7..Ab
-000001f0: 7374 7261 6374 4175 6469 7465 64da 0e41  stractAudited..A
-00000200: 7574 6865 6e74 6963 6174 696f 6eda 0c44  uthentication..D
-00000210: 6566 6175 6c74 4572 726f 72da 1044 6566  efaultError..Def
-00000220: 6175 6c74 4572 726f 7249 6e66 6fda 0e4a  aultErrorInfo..J
-00000230: 736f 6e46 6f72 6d73 5661 6c75 65da 034c  sonFormsValue..L
-00000240: 6f67 da04 5061 6765 da0c 5061 6765 4d65  og..Page..PageMe
-00000250: 7461 6461 7461 da09 5072 696e 6369 7061  tadata..Principa
-00000260: 6cda 1450 7269 6e63 6970 616c 4170 706c  l..PrincipalAppl
-00000270: 6963 6174 696f 6eda 0d50 7269 6e63 6970  ication..Princip
-00000280: 616c 5061 6765 da0d 5072 696e 6369 7061  alPage..Principa
-00000290: 6c55 7365 72da 0750 726f 6365 7373 da1d  lUser..Process..
-000002a0: 5072 6f63 6573 7343 6861 6e67 6549 6e69  ProcessChangeIni
-000002b0: 7469 6174 6f72 436f 6d6d 616e 64da 1850  tiatorCommand..P
-000002c0: 726f 6365 7373 4465 6669 6e69 7469 6f6e  rocessDefinition
-000002d0: 5375 6d6d 6172 79da 1b50 726f 6365 7373  Summary..Process
-000002e0: 4465 6c65 7465 456c 656d 656e 7443 6f6d  DeleteElementCom
-000002f0: 6d61 6e64 da13 5072 6f63 6573 7345 6c65  mand..ProcessEle
-00000300: 6d65 6e74 5661 6c75 65da 1950 726f 6365  mentValue..Proce
-00000310: 7373 456c 656d 656e 7456 616c 7565 4e75  ssElementValueNu
-00000320: 6d62 6572 da19 5072 6f63 6573 7345 6c65  mber..ProcessEle
-00000330: 6d65 6e74 5661 6c75 6553 7472 696e 67da  mentValueString.
-00000340: 0b50 726f 6365 7373 5061 6765 da0f 5072  .ProcessPage..Pr
-00000350: 6f63 6573 7350 6167 6549 7465 6dda 1950  ocessPageItem..P
-00000360: 726f 6365 7373 5361 7665 456c 656d 656e  rocessSaveElemen
-00000370: 7443 6f6d 6d61 6e64 da0e 5265 6c61 7465  tCommand..Relate
-00000380: 6450 726f 6365 7373 da04 5461 736b da11  dProcess..Task..
-00000390: 5461 736b 4173 7369 676e 436f 6d6d 616e  TaskAssignComman
-000003a0: 64da 1554 6173 6b44 6566 696e 6974 696f  d..TaskDefinitio
-000003b0: 6e53 756d 6d61 7279 da18 5461 736b 4465  nSummary..TaskDe
-000003c0: 6c65 7465 456c 656d 656e 7443 6f6d 6d61  leteElementComma
-000003d0: 6e64 da25 5461 736b 4465 6c65 7465 456c  nd.%TaskDeleteEl
-000003e0: 656d 656e 7456 616c 7565 446f 6375 6d65  ementValueDocume
-000003f0: 6e74 436f 6d6d 616e 64da 1054 6173 6b45  ntCommand..TaskE
-00000400: 6c65 6d65 6e74 5661 6c75 65da 1854 6173  lementValue..Tas
-00000410: 6b45 6c65 6d65 6e74 5661 6c75 6544 6f63  kElementValueDoc
-00000420: 756d 656e 74da 1c54 6173 6b45 6c65 6d65  ument..TaskEleme
-00000430: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
-00000440: 7465 6dda 1654 6173 6b45 6c65 6d65 6e74  tem..TaskElement
-00000450: 5661 6c75 654e 756d 6265 72da 1654 6173  ValueNumber..Tas
-00000460: 6b45 6c65 6d65 6e74 5661 6c75 654f 626a  kElementValueObj
-00000470: 6563 74da 1954 6173 6b45 6c65 6d65 6e74  ect..TaskElement
-00000480: 5661 6c75 6550 7269 6e63 6970 616c da1d  ValuePrincipal..
-00000490: 5461 736b 456c 656d 656e 7456 616c 7565  TaskElementValue
-000004a0: 5072 696e 6369 7061 6c49 7465 6dda 1654  PrincipalItem..T
-000004b0: 6173 6b45 6c65 6d65 6e74 5661 6c75 6553  askElementValueS
-000004c0: 7472 696e 67da 0854 6173 6b50 6167 65da  tring..TaskPage.
-000004d0: 0c54 6173 6b50 6167 6549 7465 6dda 1654  .TaskPageItem..T
-000004e0: 6173 6b53 6176 6545 6c65 6d65 6e74 436f  askSaveElementCo
-000004f0: 6d6d 616e 64da 2154 6173 6b53 6176 654a  mmand.!TaskSaveJ
-00000500: 736f 6e46 6f72 6d73 5661 6c75 6544 6174  sonFormsValueDat
-00000510: 6143 6f6d 6d61 6e64 da2d 5461 736b 5361  aCommand.-TaskSa
-00000520: 7665 4a73 6f6e 466f 726d 7356 616c 7565  veJsonFormsValue
-00000530: 446f 6375 6d65 6e74 5265 7370 6f6e 7365  DocumentResponse
-00000540: 436f 6d6d 616e 64da 0c57 6562 686f 6f6b  Command..Webhook
-00000550: 4576 656e 74da 1f57 6562 686f 6f6b 4576  Event..WebhookEv
-00000560: 656e 7450 726f 6365 7373 5374 6174 6543  entProcessStateC
-00000570: 6861 6e67 6564 da23 5765 6268 6f6f 6b45  hanged.#WebhookE
-00000580: 7665 6e74 5072 6f63 6573 7353 7461 7465  ventProcessState
-00000590: 4368 616e 6765 6444 6174 61da 1c57 6562  ChangedData..Web
-000005a0: 686f 6f6b 4576 656e 7454 6173 6b53 7461  hookEventTaskSta
-000005b0: 7465 4368 616e 6765 64da 2057 6562 686f  teChanged. Webho
-000005c0: 6f6b 4576 656e 7454 6173 6b53 7461 7465  okEventTaskState
-000005d0: 4368 616e 6765 6444 6174 61da 1141 7564  ChangedData..Aud
-000005e0: 6974 6564 4f62 6a65 6374 5479 7065 da08  itedObjectType..
-000005f0: 4c6f 674c 6576 656c da0f 5061 6765 644f  LogLevel..PagedO
-00000600: 626a 6563 7454 7970 65da 0d50 7269 6e63  bjectType..Princ
-00000610: 6970 616c 5479 7065 da17 5072 6f63 6573  ipalType..Proces
-00000620: 7345 6c65 6d65 6e74 5661 6c75 6554 7970  sElementValueTyp
-00000630: 65da 0c50 726f 6365 7373 5374 6174 65da  e..ProcessState.
-00000640: 1454 6173 6b45 6c65 6d65 6e74 5661 6c75  .TaskElementValu
-00000650: 6554 7970 65da 0954 6173 6b53 7461 7465  eType..TaskState
-00000660: da0b 5765 6268 6f6f 6b54 7970 65e9 0100  ..WebhookType...
+000001b0: 643e 643f 6440 6441 673d 5a38 6541 6442  d>d?d@dAg=Z8eAdB
+000001c0: 6443 8400 6539 4400 8301 8301 9001 73a6  dC..e9D.......s.
+000001d0: 7442 8201 6444 5300 2945 e902 0000 0029  tB..dDS.)E.....)
+000001e0: 37da 0f41 6273 7472 6163 7441 7564 6974  7..AbstractAudit
+000001f0: 6564 da11 4175 6469 7465 644f 626a 6563  ed..AuditedObjec
+00000200: 7454 7970 65da 0e41 7574 6865 6e74 6963  tType..Authentic
+00000210: 6174 696f 6eda 0c44 6566 6175 6c74 4572  ation..DefaultEr
+00000220: 726f 72da 1044 6566 6175 6c74 4572 726f  ror..DefaultErro
+00000230: 7249 6e66 6fda 0e4a 736f 6e46 6f72 6d73  rInfo..JsonForms
+00000240: 5661 6c75 65da 034c 6f67 da08 4c6f 674c  Value..Log..LogL
+00000250: 6576 656c da04 5061 6765 da0f 5061 6765  evel..Page..Page
+00000260: 644f 626a 6563 7454 7970 65da 0c50 6167  dObjectType..Pag
+00000270: 654d 6574 6164 6174 61da 0950 7269 6e63  eMetadata..Princ
+00000280: 6970 616c da14 5072 696e 6369 7061 6c41  ipal..PrincipalA
+00000290: 7070 6c69 6361 7469 6f6e da0d 5072 696e  pplication..Prin
+000002a0: 6369 7061 6c50 6167 65da 0d50 7269 6e63  cipalPage..Princ
+000002b0: 6970 616c 5479 7065 da0d 5072 696e 6369  ipalType..Princi
+000002c0: 7061 6c55 7365 72da 0750 726f 6365 7373  palUser..Process
+000002d0: da1d 5072 6f63 6573 7343 6861 6e67 6549  ..ProcessChangeI
+000002e0: 6e69 7469 6174 6f72 436f 6d6d 616e 64da  nitiatorCommand.
+000002f0: 1850 726f 6365 7373 4465 6669 6e69 7469  .ProcessDefiniti
+00000300: 6f6e 5375 6d6d 6172 79da 1b50 726f 6365  onSummary..Proce
+00000310: 7373 4465 6c65 7465 456c 656d 656e 7443  ssDeleteElementC
+00000320: 6f6d 6d61 6e64 da13 5072 6f63 6573 7345  ommand..ProcessE
+00000330: 6c65 6d65 6e74 5661 6c75 65da 1950 726f  lementValue..Pro
+00000340: 6365 7373 456c 656d 656e 7456 616c 7565  cessElementValue
+00000350: 4e75 6d62 6572 da19 5072 6f63 6573 7345  Number..ProcessE
+00000360: 6c65 6d65 6e74 5661 6c75 6553 7472 696e  lementValueStrin
+00000370: 67da 1750 726f 6365 7373 456c 656d 656e  g..ProcessElemen
+00000380: 7456 616c 7565 5479 7065 da0b 5072 6f63  tValueType..Proc
+00000390: 6573 7350 6167 65da 0f50 726f 6365 7373  essPage..Process
+000003a0: 5061 6765 4974 656d da19 5072 6f63 6573  PageItem..Proces
+000003b0: 7353 6176 6545 6c65 6d65 6e74 436f 6d6d  sSaveElementComm
+000003c0: 616e 64da 0c50 726f 6365 7373 5374 6174  and..ProcessStat
+000003d0: 65da 0e52 656c 6174 6564 5072 6f63 6573  e..RelatedProces
+000003e0: 73da 0454 6173 6bda 1154 6173 6b41 7373  s..Task..TaskAss
+000003f0: 6967 6e43 6f6d 6d61 6e64 da15 5461 736b  ignCommand..Task
+00000400: 4465 6669 6e69 7469 6f6e 5375 6d6d 6172  DefinitionSummar
+00000410: 79da 1854 6173 6b44 656c 6574 6545 6c65  y..TaskDeleteEle
+00000420: 6d65 6e74 436f 6d6d 616e 64da 2554 6173  mentCommand.%Tas
+00000430: 6b44 656c 6574 6545 6c65 6d65 6e74 5661  kDeleteElementVa
+00000440: 6c75 6544 6f63 756d 656e 7443 6f6d 6d61  lueDocumentComma
+00000450: 6e64 da10 5461 736b 456c 656d 656e 7456  nd..TaskElementV
+00000460: 616c 7565 da18 5461 736b 456c 656d 656e  alue..TaskElemen
+00000470: 7456 616c 7565 446f 6375 6d65 6e74 da1c  tValueDocument..
+00000480: 5461 736b 456c 656d 656e 7456 616c 7565  TaskElementValue
+00000490: 446f 6375 6d65 6e74 4974 656d da16 5461  DocumentItem..Ta
+000004a0: 736b 456c 656d 656e 7456 616c 7565 4e75  skElementValueNu
+000004b0: 6d62 6572 da16 5461 736b 456c 656d 656e  mber..TaskElemen
+000004c0: 7456 616c 7565 4f62 6a65 6374 da19 5461  tValueObject..Ta
+000004d0: 736b 456c 656d 656e 7456 616c 7565 5072  skElementValuePr
+000004e0: 696e 6369 7061 6cda 1d54 6173 6b45 6c65  incipal..TaskEle
+000004f0: 6d65 6e74 5661 6c75 6550 7269 6e63 6970  mentValuePrincip
+00000500: 616c 4974 656d da16 5461 736b 456c 656d  alItem..TaskElem
+00000510: 656e 7456 616c 7565 5374 7269 6e67 da14  entValueString..
+00000520: 5461 736b 456c 656d 656e 7456 616c 7565  TaskElementValue
+00000530: 5479 7065 da08 5461 736b 5061 6765 da0c  Type..TaskPage..
+00000540: 5461 736b 5061 6765 4974 656d da16 5461  TaskPageItem..Ta
+00000550: 736b 5361 7665 456c 656d 656e 7443 6f6d  skSaveElementCom
+00000560: 6d61 6e64 da21 5461 736b 5361 7665 4a73  mand.!TaskSaveJs
+00000570: 6f6e 466f 726d 7356 616c 7565 4461 7461  onFormsValueData
+00000580: 436f 6d6d 616e 64da 2d54 6173 6b53 6176  Command.-TaskSav
+00000590: 654a 736f 6e46 6f72 6d73 5661 6c75 6544  eJsonFormsValueD
+000005a0: 6f63 756d 656e 7452 6573 706f 6e73 6543  ocumentResponseC
+000005b0: 6f6d 6d61 6e64 da09 5461 736b 5374 6174  ommand..TaskStat
+000005c0: 65da 0c57 6562 686f 6f6b 4576 656e 74da  e..WebhookEvent.
+000005d0: 1f57 6562 686f 6f6b 4576 656e 7450 726f  .WebhookEventPro
+000005e0: 6365 7373 5374 6174 6543 6861 6e67 6564  cessStateChanged
+000005f0: da23 5765 6268 6f6f 6b45 7665 6e74 5072  .#WebhookEventPr
+00000600: 6f63 6573 7353 7461 7465 4368 616e 6765  ocessStateChange
+00000610: 6444 6174 61da 1c57 6562 686f 6f6b 4576  dData..WebhookEv
+00000620: 656e 7454 6173 6b53 7461 7465 4368 616e  entTaskStateChan
+00000630: 6765 64da 2057 6562 686f 6f6b 4576 656e  ged. WebhookEven
+00000640: 7454 6173 6b53 7461 7465 4368 616e 6765  tTaskStateChange
+00000650: 6444 6174 61da 0b57 6562 686f 6f6b 5479  dData..WebhookTy
+00000660: 7065 a901 da07 5f5f 616c 6c5f 5fe9 0100  pe....__all__...
 00000670: 0000 2906 da08 446f 6375 6d65 6e74 da0d  ..)...Document..
 00000680: 4a73 6f6e 466f 726d 7346 696c 65da 124a  JsonFormsFile..J
 00000690: 736f 6e46 6f72 6d73 5072 696e 6369 7061  sonFormsPrincipa
-000006a0: 6cda 2354 6173 6b53 6176 6545 6c65 6d65  l.#TaskSaveEleme
-000006b0: 6e74 5661 6c75 6544 6f63 756d 656e 7443  ntValueDocumentC
-000006c0: 6f6d 6d61 6e64 da2c 5461 736b 5361 7665  ommand.,TaskSave
-000006d0: 4a73 6f6e 466f 726d 7356 616c 7565 446f  JsonFormsValueDo
-000006e0: 6375 6d65 6e74 5265 7175 6573 7443 6f6d  cumentRequestCom
-000006f0: 6d61 6e64 da29 5072 6f63 6573 7353 6176  mand.)ProcessSav
-00000700: 6555 7365 7241 6374 696f 6e56 616c 7565  eUserActionValue
-00000710: 446f 6375 6d65 6e74 436f 6d6d 616e 6472  DocumentCommandr
-00000720: 0400 0000 7205 0000 0072 0600 0000 7207  ....r....r....r.
-00000730: 0000 0072 0800 0000 7209 0000 0072 0a00  ...r....r....r..
-00000740: 0000 720b 0000 0072 0c00 0000 720d 0000  ..r....r....r...
-00000750: 0072 0e00 0000 720f 0000 0072 1000 0000  .r....r....r....
-00000760: 7211 0000 0072 1200 0000 7213 0000 0072  r....r....r....r
-00000770: 1400 0000 7215 0000 0072 1600 0000 7217  ....r....r....r.
-00000780: 0000 0072 1800 0000 7219 0000 0072 1a00  ...r....r....r..
-00000790: 0000 721b 0000 0072 1c00 0000 721d 0000  ..r....r....r...
-000007a0: 0072 1e00 0000 721f 0000 0072 2000 0000  .r....r....r ...
-000007b0: 7221 0000 0072 2200 0000 7223 0000 0072  r!...r"...r#...r
-000007c0: 2400 0000 7225 0000 0072 2600 0000 7227  $...r%...r&...r'
-000007d0: 0000 0072 2800 0000 7229 0000 0072 2a00  ...r(...r)...r*.
-000007e0: 0000 722b 0000 0072 2c00 0000 722d 0000  ..r+...r,...r-..
-000007f0: 0072 2e00 0000 722f 0000 0072 3000 0000  .r....r/...r0...
-00000800: 7231 0000 0072 3200 0000 7233 0000 0072  r1...r2...r3...r
-00000810: 3400 0000 7235 0000 0072 3600 0000 7237  4...r5...r6...r7
-00000820: 0000 0072 3800 0000 7239 0000 0072 3a00  ...r8...r9...r:.
+000006a0: 6cda 2950 726f 6365 7373 5361 7665 5573  l.)ProcessSaveUs
+000006b0: 6572 4163 7469 6f6e 5661 6c75 6544 6f63  erActionValueDoc
+000006c0: 756d 656e 7443 6f6d 6d61 6e64 da23 5461  umentCommand.#Ta
+000006d0: 736b 5361 7665 456c 656d 656e 7456 616c  skSaveElementVal
+000006e0: 7565 446f 6375 6d65 6e74 436f 6d6d 616e  ueDocumentComman
+000006f0: 64da 2c54 6173 6b53 6176 654a 736f 6e46  d.,TaskSaveJsonF
+00000700: 6f72 6d73 5661 6c75 6544 6f63 756d 656e  ormsValueDocumen
+00000710: 7452 6571 7565 7374 436f 6d6d 616e 6472  tRequestCommandr
+00000720: 0200 0000 7204 0000 0072 0500 0000 7206  ....r....r....r.
+00000730: 0000 0072 0700 0000 7208 0000 0072 0a00  ...r....r....r..
+00000740: 0000 720c 0000 0072 0d00 0000 720e 0000  ..r....r....r...
+00000750: 0072 0f00 0000 7211 0000 0072 1200 0000  .r....r....r....
+00000760: 7213 0000 0072 1400 0000 7215 0000 0072  r....r....r....r
+00000770: 1600 0000 7217 0000 0072 1800 0000 721a  ....r....r....r.
+00000780: 0000 0072 1b00 0000 721c 0000 0072 1e00  ...r....r....r..
+00000790: 0000 721f 0000 0072 2000 0000 7221 0000  ..r....r ...r!..
+000007a0: 0072 2200 0000 7223 0000 0072 2400 0000  .r"...r#...r$...
+000007b0: 7225 0000 0072 2600 0000 7227 0000 0072  r%...r&...r'...r
+000007c0: 2800 0000 7229 0000 0072 2a00 0000 722b  (...r)...r*...r+
+000007d0: 0000 0072 2d00 0000 722e 0000 0072 2f00  ...r-...r....r/.
+000007e0: 0000 7230 0000 0072 3100 0000 7233 0000  ..r0...r1...r3..
+000007f0: 0072 3400 0000 7235 0000 0072 3600 0000  .r4...r5...r6...
+00000800: 7237 0000 0072 0300 0000 7209 0000 0072  r7...r....r....r
+00000810: 0b00 0000 7210 0000 0072 1900 0000 721d  ....r....r....r.
+00000820: 0000 0072 2c00 0000 7232 0000 0072 3800  ...r,...r2...r8.
 00000830: 0000 723c 0000 0072 3d00 0000 723e 0000  ..r<...r=...r>..
-00000840: 0072 3f00 0000 7240 0000 0072 4100 0000  .r?...r@...rA...
+00000840: 0072 4000 0000 7241 0000 0072 3f00 0000  .r@...rA...r?...
 00000850: 6301 0000 0000 0000 0000 0000 0002 0000  c...............
 00000860: 0003 0000 0063 0000 0073 1600 0000 7c00  .....c...s....|.
 00000870: 5d0e 7d01 7c01 7400 6b06 5600 0100 7102  ].}.|.t.k.V...q.
-00000880: 6400 5300 2901 4e72 0200 0000 2902 da02  d.S.).Nr....)...
+00000880: 6400 5300 2901 4e72 3900 0000 2902 da02  d.S.).Nr9...)...
 00000890: 2e30 da04 6974 656d a900 7244 0000 00fa  .0..item..rD....
 000008a0: 422f 776f 726b 2f6b 7566 6c6f 772d 7364  B/work/kuflow-sd
 000008b0: 6b2d 7079 7468 6f6e 2f6b 7566 6c6f 772d  k-python/kuflow-
 000008c0: 7265 7374 2f6b 7566 6c6f 775f 7265 7374  rest/kuflow_rest
 000008d0: 2f6d 6f64 656c 732f 5f5f 696e 6974 5f5f  /models/__init__
-000008e0: 2e70 79da 093c 6765 6e65 7870 723e a500  .py..<genexpr>..
+000008e0: 2e70 79da 093c 6765 6e65 7870 723e a200  .py..<genexpr>..
 000008f0: 0000 7304 0000 0004 0002 0072 4600 0000  ..s........rF...
 00000900: 4e29 435a 115f 6765 6e65 7261 7465 642e  N)CZ._generated.
-00000910: 6d6f 6465 6c73 7203 0000 005a 155f 616c  modelsr....Z._al
-00000920: 6c5f 6765 6e65 7261 7465 645f 6d6f 6465  l_generated_mode
-00000930: 6c73 7204 0000 0072 0500 0000 7206 0000  lsr....r....r...
-00000940: 0072 0700 0000 7208 0000 0072 0900 0000  .r....r....r....
-00000950: 720a 0000 0072 0b00 0000 720c 0000 0072  r....r....r....r
-00000960: 0d00 0000 720e 0000 0072 0f00 0000 7210  ....r....r....r.
-00000970: 0000 0072 1100 0000 7212 0000 0072 1300  ...r....r....r..
-00000980: 0000 7214 0000 0072 1500 0000 7216 0000  ..r....r....r...
-00000990: 0072 1700 0000 7218 0000 0072 1900 0000  .r....r....r....
-000009a0: 721a 0000 0072 1b00 0000 721c 0000 0072  r....r....r....r
-000009b0: 1d00 0000 721e 0000 0072 1f00 0000 7220  ....r....r....r 
-000009c0: 0000 0072 2100 0000 7222 0000 0072 2300  ...r!...r"...r#.
-000009d0: 0000 7224 0000 0072 2500 0000 7226 0000  ..r$...r%...r&..
-000009e0: 0072 2700 0000 7228 0000 0072 2900 0000  .r'...r(...r)...
-000009f0: 722a 0000 0072 2b00 0000 722c 0000 0072  r*...r+...r,...r
-00000a00: 2d00 0000 722e 0000 0072 2f00 0000 7230  -...r....r/...r0
-00000a10: 0000 0072 3100 0000 7232 0000 0072 3300  ...r1...r2...r3.
-00000a20: 0000 7234 0000 0072 3500 0000 7236 0000  ..r4...r5...r6..
-00000a30: 0072 3700 0000 7238 0000 0072 3900 0000  .r7...r8...r9...
-00000a40: 723a 0000 00da 075f 6d6f 6465 6c73 723c  r:....._modelsr<
+00000910: 6d6f 6465 6c73 7202 0000 0072 0300 0000  modelsr....r....
+00000920: 7204 0000 0072 0500 0000 7206 0000 0072  r....r....r....r
+00000930: 0700 0000 7208 0000 0072 0900 0000 720a  ....r....r....r.
+00000940: 0000 0072 0b00 0000 720c 0000 0072 0d00  ...r....r....r..
+00000950: 0000 720e 0000 0072 0f00 0000 7210 0000  ..r....r....r...
+00000960: 0072 1100 0000 7212 0000 0072 1300 0000  .r....r....r....
+00000970: 7214 0000 0072 1500 0000 7216 0000 0072  r....r....r....r
+00000980: 1700 0000 7218 0000 0072 1900 0000 721a  ....r....r....r.
+00000990: 0000 0072 1b00 0000 721c 0000 0072 1d00  ...r....r....r..
+000009a0: 0000 721e 0000 0072 1f00 0000 7220 0000  ..r....r....r ..
+000009b0: 0072 2100 0000 7222 0000 0072 2300 0000  .r!...r"...r#...
+000009c0: 7224 0000 0072 2500 0000 7226 0000 0072  r$...r%...r&...r
+000009d0: 2700 0000 7228 0000 0072 2900 0000 722a  '...r(...r)...r*
+000009e0: 0000 0072 2b00 0000 722c 0000 0072 2d00  ...r+...r,...r-.
+000009f0: 0000 722e 0000 0072 2f00 0000 7230 0000  ..r....r/...r0..
+00000a00: 0072 3100 0000 7232 0000 0072 3300 0000  .r1...r2...r3...
+00000a10: 7234 0000 0072 3500 0000 7236 0000 0072  r4...r5...r6...r
+00000a20: 3700 0000 7238 0000 0072 3a00 0000 5a15  7...r8...r:...Z.
+00000a30: 5f61 6c6c 5f67 656e 6572 6174 6564 5f6d  _all_generated_m
+00000a40: 6f64 656c 73da 075f 6d6f 6465 6c73 723c  odels.._modelsr<
 00000a50: 0000 0072 3d00 0000 723e 0000 0072 3f00  ...r=...r>...r?.
 00000a60: 0000 7240 0000 0072 4100 0000 da03 616c  ..r@...rA.....al
 00000a70: 6cda 0e41 7373 6572 7469 6f6e 4572 726f  l..AssertionErro
 00000a80: 7272 4400 0000 7244 0000 0072 4400 0000  rrD...rD...rD...
 00000a90: 7245 0000 00da 083c 6d6f 6475 6c65 3e1a  rE.....<module>.
-00000aa0: 0000 0073 8200 0000 0c02 e43a 200c 0201  ...s.......: ...
+00000aa0: 0000 0073 8200 0000 e439 0c01 200b 0201  ...s.....9.. ...
 00000ab0: 0201 0201 0201 0201 0201 0201 0201 0201  ................
 00000ac0: 0201 0201 0201 0201 0201 0201 0201 0201  ................
 00000ad0: 0201 0201 0201 0201 0201 0201 0201 0201  ................
 00000ae0: 0201 0201 0201 0201 0201 0201 0201 0201  ................
 00000af0: 0201 0201 0201 0201 0201 0201 0201 0201  ................
 00000b00: 0201 0201 0201 0201 0201 0201 0201 0201  ................
 00000b10: 0201 0201 0201 0201 0201 0202 0201 0201  ................
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/models/__pycache__/_models.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/models/__pycache__/_models.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 4581 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 e511 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 e511 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 7400 0000 6400  .....@...st...d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6402  d.l.m.Z.m.Z...d.
 00000040: 6403 6c03 6d04 5a04 0100 4700 6404 6405  d.l.m.Z...G.d.d.
 00000050: 8400 6405 8302 5a05 4700 6406 6407 8400  ..d...Z.G.d.d...
 00000060: 6407 8302 5a06 4700 6408 6409 8400 6409  d...Z.G.d.d...d.
 00000070: 8302 5a07 4700 640a 640b 8400 640b 8302  ..Z.G.d.d...d...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/models/_models.py` & `kuflow_rest-0.8.0/kuflow_rest/models/_models.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/operations/__init__.py`

 * *Files identical despite different names*

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_authentication_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_authentication_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 2322 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 10% similar despite different names*

```diff
@@ -1,105 +1,105 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 1209 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 2a09 0000  U..........d*...
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
-00000020: 0003 0000 0040 0000 0073 2e00 0000 6400  .....@...s....d.
+00000020: 0003 0000 0040 0000 0073 3600 0000 6400  .....@...s6...d.
 00000030: 6401 6c00 6d01 5a01 0100 6402 6403 6c02  d.l.m.Z...d.d.l.
-00000040: 6d03 5a04 6d05 5a06 0100 4700 6404 6405  m.Z.m.Z...G.d.d.
-00000050: 8400 6405 8302 5a07 6406 5300 2907 e900  ..d...Z.d.S.)...
-00000060: 0000 0029 01da 0341 6e79 e902 0000 0029  ...)...Any.....)
-00000070: 02da 066d 6f64 656c 73da 104b 7546 6c6f  ...models..KuFlo
-00000080: 7752 6573 7443 6c69 656e 7463 0000 0000  wRestClientc....
-00000090: 0000 0000 0000 0000 0000 0000 0400 0000  ................
-000000a0: 4000 0000 7334 0000 0065 005a 0164 005a  @...s4...e.Z.d.Z
-000000b0: 0264 015a 0365 0464 029c 0164 0364 0484  .d.Z.e.d...d.d..
-000000c0: 045a 0565 066a 0765 0865 066a 0764 059c  .Z.e.j.e.e.j.d..
-000000d0: 0364 0664 0784 045a 0964 0853 0029 09da  .d.d...Z.d.S.)..
-000000e0: 1841 7574 6865 6e74 6963 6174 696f 6e4f  .AuthenticationO
-000000f0: 7065 7261 7469 6f6e 737a f10a 2020 2020  perationsz..    
-00000100: 2e2e 2077 6172 6e69 6e67 3a3a 0a20 2020  .. warning::.   
-00000110: 2020 2020 202a 2a44 4f20 4e4f 542a 2a20       **DO NOT** 
-00000120: 696e 7374 616e 7469 6174 6520 7468 6973  instantiate this
-00000130: 2063 6c61 7373 2064 6972 6563 746c 792e   class directly.
-00000140: 0a0a 2020 2020 2020 2020 496e 7374 6561  ..        Instea
-00000150: 642c 2079 6f75 2073 686f 756c 6420 6163  d, you should ac
-00000160: 6365 7373 2074 6865 2066 6f6c 6c6f 7769  cess the followi
-00000170: 6e67 206f 7065 7261 7469 6f6e 7320 7468  ng operations th
-00000180: 726f 7567 680a 2020 2020 2020 2020 3a63  rough.        :c
-00000190: 6c61 7373 3a60 7e6b 7566 6c6f 772e 7265  lass:`~kuflow.re
-000001a0: 7374 2e63 6c69 656e 742e 4b75 466c 6f77  st.client.KuFlow
-000001b0: 5265 7374 436c 6965 6e74 6027 730a 2020  RestClient`'s.  
-000001c0: 2020 2020 2020 3a61 7474 723a 6061 7574        :attr:`aut
-000001d0: 6865 6e74 6963 6174 696f 6e60 2061 7474  hentication` att
-000001e0: 7269 6275 7465 2e0a 2020 2020 2901 da0d  ribute..    )...
-000001f0: 6b75 666c 6f77 5f63 6c69 656e 7463 0200  kuflow_clientc..
-00000200: 0000 0000 0000 0000 0000 0200 0000 0200  ................
-00000210: 0000 4300 0000 730a 0000 007c 017c 005f  ..C...s....|.|._
-00000220: 0064 0053 0029 014e 2901 da0e 5f6b 7566  .d.S.).N)..._kuf
-00000230: 6c6f 775f 636c 6965 6e74 2902 da04 7365  low_client)...se
-00000240: 6c66 7207 0000 00a9 0072 0a00 0000 fa58  lfr......r.....X
-00000250: 2f77 6f72 6b2f 6b75 666c 6f77 2d73 646b  /work/kuflow-sdk
-00000260: 2d70 7974 686f 6e2f 6b75 666c 6f77 2d72  -python/kuflow-r
-00000270: 6573 742f 6b75 666c 6f77 5f72 6573 742f  est/kuflow_rest/
-00000280: 6f70 6572 6174 696f 6e73 2f5f 6175 7468  operations/_auth
-00000290: 656e 7469 6361 7469 6f6e 5f6f 7065 7261  entication_opera
-000002a0: 7469 6f6e 732e 7079 da08 5f5f 696e 6974  tions.py..__init
-000002b0: 5f5f 2a00 0000 7302 0000 0000 017a 2141  __*...s......z!A
-000002c0: 7574 6865 6e74 6963 6174 696f 6e4f 7065  uthenticationOpe
-000002d0: 7261 7469 6f6e 732e 5f5f 696e 6974 5f5f  rations.__init__
-000002e0: 2903 da0e 6175 7468 656e 7469 6361 7469  )...authenticati
-000002f0: 6f6e da06 6b77 6172 6773 da06 7265 7475  on..kwargs..retu
-00000300: 726e 6302 0000 0000 0000 0000 0000 0003  rnc.............
-00000310: 0000 0004 0000 004b 0000 0073 1800 0000  .......K...s....
-00000320: 7c00 6a00 6a01 6a02 6600 6401 7c01 6901  |.j.j.j.f.d.|.i.
-00000330: 7c02 9702 8e01 5300 2902 61ba 0100 0043  |.....S.).a....C
-00000340: 7265 6174 6520 616e 2061 7574 6865 6e74  reate an authent
-00000350: 6963 6174 696f 6e20 666f 7220 7468 6520  ication for the 
-00000360: 6375 7272 656e 7420 7072 696e 6369 7061  current principa
-00000370: 6c2e 0a0a 2020 2020 2020 2020 4372 6561  l...        Crea
-00000380: 7465 2061 6e20 6175 7468 656e 7469 6361  te an authentica
-00000390: 7469 6f6e 2066 6f72 2074 6865 2063 7572  tion for the cur
-000003a0: 7265 6e74 2070 7269 6e63 6970 616c 2e0a  rent principal..
-000003b0: 0a20 2020 2020 2020 203a 7061 7261 6d20  .        :param 
-000003c0: 6175 7468 656e 7469 6361 7469 6f6e 3a20  authentication: 
-000003d0: 4175 7468 656e 7469 6361 7469 6f6e 2074  Authentication t
-000003e0: 6f20 6265 2063 7265 6174 6564 2e20 4973  o be created. Is
-000003f0: 2065 6974 6865 7220 6120 6d6f 6465 6c20   either a model 
-00000400: 7479 7065 206f 7220 6120 494f 2074 7970  type or a IO typ
-00000410: 652e 2052 6571 7569 7265 642e 0a20 2020  e. Required..   
-00000420: 2020 2020 203a 7479 7065 2061 7574 6865       :type authe
-00000430: 6e74 6963 6174 696f 6e3a 207e 6b75 666c  ntication: ~kufl
-00000440: 6f77 2e72 6573 742e 6d6f 6465 6c73 2e41  ow.rest.models.A
-00000450: 7574 6865 6e74 6963 6174 696f 6e20 6f72  uthentication or
-00000460: 2049 4f0a 2020 2020 2020 2020 3a72 6574   IO.        :ret
-00000470: 7572 6e3a 2041 7574 6865 6e74 6963 6174  urn: Authenticat
-00000480: 696f 6e0a 2020 2020 2020 2020 3a72 7479  ion.        :rty
-00000490: 7065 3a20 7e6b 7566 6c6f 772e 7265 7374  pe: ~kuflow.rest
-000004a0: 2e6d 6f64 656c 732e 4175 7468 656e 7469  .models.Authenti
-000004b0: 6361 7469 6f6e 0a20 2020 2020 2020 203a  cation.        :
-000004c0: 7261 6973 6573 207e 617a 7572 652e 636f  raises ~azure.co
-000004d0: 7265 2e65 7863 6570 7469 6f6e 732e 4874  re.exceptions.Ht
-000004e0: 7470 5265 7370 6f6e 7365 4572 726f 723a  tpResponseError:
-000004f0: 0a20 2020 2020 2020 2072 0d00 0000 2903  .        r....).
-00000500: 7208 0000 0072 0d00 0000 da15 6372 6561  r....r......crea
-00000510: 7465 5f61 7574 6865 6e74 6963 6174 696f  te_authenticatio
-00000520: 6e29 0372 0900 0000 720d 0000 0072 0e00  n).r....r....r..
-00000530: 0000 720a 0000 0072 0a00 0000 720b 0000  ..r....r....r...
-00000540: 0072 1000 0000 2d00 0000 7302 0000 0000  .r....-...s.....
-00000550: 0b7a 2e41 7574 6865 6e74 6963 6174 696f  .z.Authenticatio
-00000560: 6e4f 7065 7261 7469 6f6e 732e 6372 6561  nOperations.crea
-00000570: 7465 5f61 7574 6865 6e74 6963 6174 696f  te_authenticatio
-00000580: 6e4e 290a da08 5f5f 6e61 6d65 5f5f da0a  nN)...__name__..
-00000590: 5f5f 6d6f 6475 6c65 5f5f da0c 5f5f 7175  __module__..__qu
-000005a0: 616c 6e61 6d65 5f5f da07 5f5f 646f 635f  alname__..__doc_
-000005b0: 5fda 194b 7546 6c6f 7752 6573 7443 6c69  _..KuFlowRestCli
-000005c0: 656e 7447 656e 6572 6174 6564 720c 0000  entGeneratedr...
-000005d0: 00da 075f 6d6f 6465 6c73 da0e 4175 7468  ..._models..Auth
-000005e0: 656e 7469 6361 7469 6f6e 7202 0000 0072  enticationr....r
-000005f0: 1000 0000 720a 0000 0072 0a00 0000 720a  ....r....r....r.
-00000600: 0000 0072 0b00 0000 7206 0000 0020 0000  ...r....r.... ..
-00000610: 0073 0600 0000 0801 0409 0e03 7206 0000  .s..........r...
-00000620: 004e 2908 da06 7479 7069 6e67 7202 0000  .N)...typingr...
-00000630: 00da 0a5f 6765 6e65 7261 7465 6472 0400  ..._generatedr..
-00000640: 0000 7216 0000 0072 0500 0000 7215 0000  ..r....r....r...
-00000650: 0072 0600 0000 720a 0000 0072 0a00 0000  .r....r....r....
-00000660: 720a 0000 0072 0b00 0000 da08 3c6d 6f64  r....r......<mod
-00000670: 756c 653e 1b00 0000 7304 0000 000c 0210  ule>....s.......
-00000680: 03                                       .
+00000040: 6d03 5a04 0100 6402 6404 6c02 6d05 5a06  m.Z...d.d.l.m.Z.
+00000050: 0100 4700 6405 6406 8400 6406 8302 5a07  ..G.d.d...d...Z.
+00000060: 6407 5300 2908 e900 0000 0029 01da 0341  d.S.)......)...A
+00000070: 6e79 e902 0000 0029 01da 104b 7546 6c6f  ny.....)...KuFlo
+00000080: 7752 6573 7443 6c69 656e 7429 01da 066d  wRestClient)...m
+00000090: 6f64 656c 7363 0000 0000 0000 0000 0000  odelsc..........
+000000a0: 0000 0000 0000 0400 0000 4000 0000 7334  ..........@...s4
+000000b0: 0000 0065 005a 0164 005a 0264 015a 0365  ...e.Z.d.Z.d.Z.e
+000000c0: 0464 029c 0164 0364 0484 045a 0565 066a  .d...d.d...Z.e.j
+000000d0: 0765 0865 066a 0764 059c 0364 0664 0784  .e.e.j.d...d.d..
+000000e0: 045a 0964 0853 0029 09da 1841 7574 6865  .Z.d.S.)...Authe
+000000f0: 6e74 6963 6174 696f 6e4f 7065 7261 7469  nticationOperati
+00000100: 6f6e 737a f10a 2020 2020 2e2e 2077 6172  onsz..    .. war
+00000110: 6e69 6e67 3a3a 0a20 2020 2020 2020 202a  ning::.        *
+00000120: 2a44 4f20 4e4f 542a 2a20 696e 7374 616e  *DO NOT** instan
+00000130: 7469 6174 6520 7468 6973 2063 6c61 7373  tiate this class
+00000140: 2064 6972 6563 746c 792e 0a0a 2020 2020   directly...    
+00000150: 2020 2020 496e 7374 6561 642c 2079 6f75      Instead, you
+00000160: 2073 686f 756c 6420 6163 6365 7373 2074   should access t
+00000170: 6865 2066 6f6c 6c6f 7769 6e67 206f 7065  he following ope
+00000180: 7261 7469 6f6e 7320 7468 726f 7567 680a  rations through.
+00000190: 2020 2020 2020 2020 3a63 6c61 7373 3a60          :class:`
+000001a0: 7e6b 7566 6c6f 772e 7265 7374 2e63 6c69  ~kuflow.rest.cli
+000001b0: 656e 742e 4b75 466c 6f77 5265 7374 436c  ent.KuFlowRestCl
+000001c0: 6965 6e74 6027 730a 2020 2020 2020 2020  ient`'s.        
+000001d0: 3a61 7474 723a 6061 7574 6865 6e74 6963  :attr:`authentic
+000001e0: 6174 696f 6e60 2061 7474 7269 6275 7465  ation` attribute
+000001f0: 2e0a 2020 2020 2901 da0d 6b75 666c 6f77  ..    )...kuflow
+00000200: 5f63 6c69 656e 7463 0200 0000 0000 0000  _clientc........
+00000210: 0000 0000 0200 0000 0200 0000 4300 0000  ............C...
+00000220: 730a 0000 007c 017c 005f 0064 0053 0029  s....|.|._.d.S.)
+00000230: 014e 2901 da0e 5f6b 7566 6c6f 775f 636c  .N)..._kuflow_cl
+00000240: 6965 6e74 2902 da04 7365 6c66 7207 0000  ient)...selfr...
+00000250: 00a9 0072 0a00 0000 fa58 2f77 6f72 6b2f  ...r.....X/work/
+00000260: 6b75 666c 6f77 2d73 646b 2d70 7974 686f  kuflow-sdk-pytho
+00000270: 6e2f 6b75 666c 6f77 2d72 6573 742f 6b75  n/kuflow-rest/ku
+00000280: 666c 6f77 5f72 6573 742f 6f70 6572 6174  flow_rest/operat
+00000290: 696f 6e73 2f5f 6175 7468 656e 7469 6361  ions/_authentica
+000002a0: 7469 6f6e 5f6f 7065 7261 7469 6f6e 732e  tion_operations.
+000002b0: 7079 da08 5f5f 696e 6974 5f5f 2b00 0000  py..__init__+...
+000002c0: 7302 0000 0000 017a 2141 7574 6865 6e74  s......z!Authent
+000002d0: 6963 6174 696f 6e4f 7065 7261 7469 6f6e  icationOperation
+000002e0: 732e 5f5f 696e 6974 5f5f 2903 da0e 6175  s.__init__)...au
+000002f0: 7468 656e 7469 6361 7469 6f6e da06 6b77  thentication..kw
+00000300: 6172 6773 da06 7265 7475 726e 6302 0000  args..returnc...
+00000310: 0000 0000 0000 0000 0003 0000 0004 0000  ................
+00000320: 004b 0000 0073 1800 0000 7c00 6a00 6a01  .K...s....|.j.j.
+00000330: 6a02 6600 6401 7c01 6901 7c02 9702 8e01  j.f.d.|.i.|.....
+00000340: 5300 2902 61ba 0100 0043 7265 6174 6520  S.).a....Create 
+00000350: 616e 2061 7574 6865 6e74 6963 6174 696f  an authenticatio
+00000360: 6e20 666f 7220 7468 6520 6375 7272 656e  n for the curren
+00000370: 7420 7072 696e 6369 7061 6c2e 0a0a 2020  t principal...  
+00000380: 2020 2020 2020 4372 6561 7465 2061 6e20        Create an 
+00000390: 6175 7468 656e 7469 6361 7469 6f6e 2066  authentication f
+000003a0: 6f72 2074 6865 2063 7572 7265 6e74 2070  or the current p
+000003b0: 7269 6e63 6970 616c 2e0a 0a20 2020 2020  rincipal...     
+000003c0: 2020 203a 7061 7261 6d20 6175 7468 656e     :param authen
+000003d0: 7469 6361 7469 6f6e 3a20 4175 7468 656e  tication: Authen
+000003e0: 7469 6361 7469 6f6e 2074 6f20 6265 2063  tication to be c
+000003f0: 7265 6174 6564 2e20 4973 2065 6974 6865  reated. Is eithe
+00000400: 7220 6120 6d6f 6465 6c20 7479 7065 206f  r a model type o
+00000410: 7220 6120 494f 2074 7970 652e 2052 6571  r a IO type. Req
+00000420: 7569 7265 642e 0a20 2020 2020 2020 203a  uired..        :
+00000430: 7479 7065 2061 7574 6865 6e74 6963 6174  type authenticat
+00000440: 696f 6e3a 207e 6b75 666c 6f77 2e72 6573  ion: ~kuflow.res
+00000450: 742e 6d6f 6465 6c73 2e41 7574 6865 6e74  t.models.Authent
+00000460: 6963 6174 696f 6e20 6f72 2049 4f0a 2020  ication or IO.  
+00000470: 2020 2020 2020 3a72 6574 7572 6e3a 2041        :return: A
+00000480: 7574 6865 6e74 6963 6174 696f 6e0a 2020  uthentication.  
+00000490: 2020 2020 2020 3a72 7479 7065 3a20 7e6b        :rtype: ~k
+000004a0: 7566 6c6f 772e 7265 7374 2e6d 6f64 656c  uflow.rest.model
+000004b0: 732e 4175 7468 656e 7469 6361 7469 6f6e  s.Authentication
+000004c0: 0a20 2020 2020 2020 203a 7261 6973 6573  .        :raises
+000004d0: 207e 617a 7572 652e 636f 7265 2e65 7863   ~azure.core.exc
+000004e0: 6570 7469 6f6e 732e 4874 7470 5265 7370  eptions.HttpResp
+000004f0: 6f6e 7365 4572 726f 723a 0a20 2020 2020  onseError:.     
+00000500: 2020 2072 0d00 0000 2903 7208 0000 0072     r....).r....r
+00000510: 0d00 0000 da15 6372 6561 7465 5f61 7574  ......create_aut
+00000520: 6865 6e74 6963 6174 696f 6e29 0372 0900  hentication).r..
+00000530: 0000 720d 0000 0072 0e00 0000 720a 0000  ..r....r....r...
+00000540: 0072 0a00 0000 720b 0000 0072 1000 0000  .r....r....r....
+00000550: 2e00 0000 7302 0000 0000 0b7a 2e41 7574  ....s......z.Aut
+00000560: 6865 6e74 6963 6174 696f 6e4f 7065 7261  henticationOpera
+00000570: 7469 6f6e 732e 6372 6561 7465 5f61 7574  tions.create_aut
+00000580: 6865 6e74 6963 6174 696f 6e4e 290a da08  henticationN)...
+00000590: 5f5f 6e61 6d65 5f5f da0a 5f5f 6d6f 6475  __name__..__modu
+000005a0: 6c65 5f5f da0c 5f5f 7175 616c 6e61 6d65  le__..__qualname
+000005b0: 5f5f da07 5f5f 646f 635f 5fda 194b 7546  __..__doc__..KuF
+000005c0: 6c6f 7752 6573 7443 6c69 656e 7447 656e  lowRestClientGen
+000005d0: 6572 6174 6564 720c 0000 00da 075f 6d6f  eratedr......_mo
+000005e0: 6465 6c73 da0e 4175 7468 656e 7469 6361  dels..Authentica
+000005f0: 7469 6f6e 7202 0000 0072 1000 0000 720a  tionr....r....r.
+00000600: 0000 0072 0a00 0000 720a 0000 0072 0b00  ...r....r....r..
+00000610: 0000 7206 0000 0021 0000 0073 0600 0000  ..r....!...s....
+00000620: 0801 0409 0e03 7206 0000 004e 2908 da06  ......r....N)...
+00000630: 7479 7069 6e67 7202 0000 00da 0a5f 6765  typingr......_ge
+00000640: 6e65 7261 7465 6472 0400 0000 7215 0000  neratedr....r...
+00000650: 0072 0500 0000 7216 0000 0072 0600 0000  .r....r....r....
+00000660: 720a 0000 0072 0a00 0000 720a 0000 0072  r....r....r....r
+00000670: 0b00 0000 da08 3c6d 6f64 756c 653e 1b00  ......<module>..
+00000680: 0000 7306 0000 000c 020c 010c 03         ..s..........
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_principal_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_principal_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 4113 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 6% similar despite different names*

```diff
@@ -1,213 +1,214 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 1110 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 2910 0000  U..........d)...
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
-00000020: 0003 0000 0040 0000 0073 3a00 0000 6400  .....@...s:...d.
+00000020: 0003 0000 0040 0000 0073 4200 0000 6400  .....@...sB...d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
 00000040: 6d04 5a04 0100 6402 6403 6c05 6d06 5a07  m.Z...d.d.l.m.Z.
-00000050: 6d08 5a09 0100 4700 6404 6405 8400 6405  m.Z...G.d.d...d.
-00000060: 8302 5a0a 6406 5300 2907 e900 0000 0029  ..Z.d.S.)......)
-00000070: 04da 0341 6e79 da04 4c69 7374 da08 4f70  ...Any..List..Op
-00000080: 7469 6f6e 616c da05 556e 696f 6ee9 0200  tional..Union...
-00000090: 0000 2902 da06 6d6f 6465 6c73 da10 4b75  ..)...models..Ku
-000000a0: 466c 6f77 5265 7374 436c 6965 6e74 6300  FlowRestClientc.
-000000b0: 0000 0000 0000 0000 0000 0000 0000 000a  ................
-000000c0: 0000 0040 0000 0073 7600 0000 6500 5a01  ...@...sv...e.Z.
-000000d0: 6400 5a02 6401 5a03 6504 6402 9c01 6403  d.Z.d.Z.e.d...d.
-000000e0: 6404 8404 5a05 640e 6506 6506 6507 6508  d...Z.d.e.e.e.e.
-000000f0: 6509 650a 6509 1900 6602 1900 1900 6507  e.e.e...f.....e.
-00000100: 650b 6a0c 1900 6507 6508 6509 650a 6509  e.j...e.e.e.e.e.
-00000110: 1900 6602 1900 1900 650d 650b 6a0e 6408  ..f.....e.e.j.d.
-00000120: 9c07 6409 640a 8405 5a0f 6509 650d 650b  ..d.d...Z.e.e.e.
-00000130: 6a10 640b 9c03 640c 640d 8404 5a11 6407  j.d...d.d...Z.d.
-00000140: 5300 290f da13 5072 696e 6369 7061 6c4f  S.)...PrincipalO
-00000150: 7065 7261 7469 6f6e 737a ec0a 2020 2020  perationsz..    
-00000160: 2e2e 2077 6172 6e69 6e67 3a3a 0a20 2020  .. warning::.   
-00000170: 2020 2020 202a 2a44 4f20 4e4f 542a 2a20       **DO NOT** 
-00000180: 696e 7374 616e 7469 6174 6520 7468 6973  instantiate this
-00000190: 2063 6c61 7373 2064 6972 6563 746c 792e   class directly.
-000001a0: 0a0a 2020 2020 2020 2020 496e 7374 6561  ..        Instea
-000001b0: 642c 2079 6f75 2073 686f 756c 6420 6163  d, you should ac
-000001c0: 6365 7373 2074 6865 2066 6f6c 6c6f 7769  cess the followi
-000001d0: 6e67 206f 7065 7261 7469 6f6e 7320 7468  ng operations th
-000001e0: 726f 7567 680a 2020 2020 2020 2020 3a63  rough.        :c
-000001f0: 6c61 7373 3a60 7e6b 7566 6c6f 772e 7265  lass:`~kuflow.re
-00000200: 7374 2e63 6c69 656e 742e 4b75 466c 6f77  st.client.KuFlow
-00000210: 5265 7374 436c 6965 6e74 6027 730a 2020  RestClient`'s.  
-00000220: 2020 2020 2020 3a61 7474 723a 6070 7269        :attr:`pri
-00000230: 6e63 6970 616c 6020 6174 7472 6962 7574  ncipal` attribut
-00000240: 652e 0a20 2020 2029 01da 0d6b 7566 6c6f  e..    )...kuflo
-00000250: 775f 636c 6965 6e74 6302 0000 0000 0000  w_clientc.......
-00000260: 0000 0000 0002 0000 0002 0000 0043 0000  .............C..
-00000270: 0073 0a00 0000 7c01 7c00 5f00 6400 5300  .s....|.|._.d.S.
-00000280: 2901 4e29 01da 0e5f 6b75 666c 6f77 5f63  ).N)..._kuflow_c
-00000290: 6c69 656e 7429 02da 0473 656c 6672 0a00  lient)...selfr..
-000002a0: 0000 a900 720d 0000 00fa 532f 776f 726b  ....r.....S/work
-000002b0: 2f6b 7566 6c6f 772d 7364 6b2d 7079 7468  /kuflow-sdk-pyth
-000002c0: 6f6e 2f6b 7566 6c6f 772d 7265 7374 2f6b  on/kuflow-rest/k
-000002d0: 7566 6c6f 775f 7265 7374 2f6f 7065 7261  uflow_rest/opera
-000002e0: 7469 6f6e 732f 5f70 7269 6e63 6970 616c  tions/_principal
-000002f0: 5f6f 7065 7261 7469 6f6e 732e 7079 da08  _operations.py..
-00000300: 5f5f 696e 6974 5f5f 2a00 0000 7302 0000  __init__*...s...
-00000310: 0000 017a 1c50 7269 6e63 6970 616c 4f70  ...z.PrincipalOp
-00000320: 6572 6174 696f 6e73 2e5f 5f69 6e69 745f  erations.__init_
-00000330: 5fe9 1900 0000 7201 0000 004e 2907 da04  _.....r....N)...
-00000340: 7369 7a65 da04 7061 6765 da04 736f 7274  size..page..sort
-00000350: da04 7479 7065 da08 6772 6f75 705f 6964  ..type..group_id
-00000360: da06 6b77 6172 6773 da06 7265 7475 726e  ..kwargs..return
-00000370: 6306 0000 0000 0000 0000 0000 0007 0000  c...............
-00000380: 0008 0000 004b 0000 0073 5000 0000 7c03  .....K...sP...|.
-00000390: 6401 6b09 7218 7400 7c03 7401 8302 7218  d.k.r.t.|.t...r.
-000003a0: 7c03 6701 7d03 7c05 6401 6b09 7230 7400  |.g.}.|.d.k.r0t.
-000003b0: 7c05 7401 8302 7230 7c05 6701 7d05 7c00  |.t...r0|.g.}.|.
-000003c0: 6a02 6a03 6a04 6600 7c01 7c02 7c03 7c04  j.j.j.f.|.|.|.|.
-000003d0: 7c05 6402 9c05 7c06 9702 8e01 5300 2903  |.d...|.....S.).
-000003e0: 6136 0500 0046 696e 6420 616c 6c20 6163  a6...Find all ac
-000003f0: 6365 7373 6962 6c65 2050 7269 6e63 6970  cessible Princip
-00000400: 616c 732e 0a0a 2020 2020 2020 2020 4c69  als...        Li
-00000410: 7374 2061 6c6c 2074 6865 2050 7269 6e63  st all the Princ
-00000420: 6970 616c 7320 7468 6174 2068 6176 6520  ipals that have 
-00000430: 6265 656e 2063 7265 6174 6564 2061 6e64  been created and
-00000440: 2074 6865 2075 7365 6420 6372 6564 656e   the used creden
-00000450: 7469 616c 7320 6861 7320 6163 6365 7373  tials has access
-00000460: 2e0a 0a20 2020 2020 2020 2041 7661 696c  ...        Avail
-00000470: 6162 6c65 2073 6f72 7420 7175 6572 7920  able sort query 
-00000480: 7661 6c75 6573 3a20 6964 2c20 6e61 6d65  values: id, name
-00000490: 2e0a 0a20 2020 2020 2020 203a 6b65 7977  ...        :keyw
-000004a0: 6f72 6420 7369 7a65 3a20 5468 6520 6e75  ord size: The nu
-000004b0: 6d62 6572 206f 6620 7265 636f 7264 7320  mber of records 
-000004c0: 7265 7475 726e 6564 2077 6974 6869 6e20  returned within 
-000004d0: 6120 7369 6e67 6c65 2041 5049 2063 616c  a single API cal
-000004e0: 6c2e 2044 6566 6175 6c74 2076 616c 7565  l. Default value
-000004f0: 2069 7320 3235 2e0a 2020 2020 2020 2020   is 25..        
-00000500: 3a74 7970 6520 7369 7a65 3a20 696e 740a  :type size: int.
-00000510: 2020 2020 2020 2020 3a6b 6579 776f 7264          :keyword
-00000520: 2070 6167 653a 2054 6865 2070 6167 6520   page: The page 
-00000530: 6e75 6d62 6572 206f 6620 7468 6520 6375  number of the cu
-00000540: 7272 656e 7420 7061 6765 2069 6e20 7468  rrent page in th
-00000550: 6520 7265 7475 726e 6564 2072 6563 6f72  e returned recor
-00000560: 6473 2c20 3020 6973 2074 6865 2066 6972  ds, 0 is the fir
-00000570: 7374 2070 6167 652e 0a20 2020 2020 2020  st page..       
-00000580: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00000590: 4465 6661 756c 7420 7661 6c75 6520 6973  Default value is
-000005a0: 2030 2e0a 2020 2020 2020 2020 3a74 7970   0..        :typ
-000005b0: 6520 7061 6765 3a20 696e 740a 2020 2020  e page: int.    
-000005c0: 2020 2020 3a6b 6579 776f 7264 2073 6f72      :keyword sor
-000005d0: 743a 2053 6f72 7469 6e67 2063 7269 7465  t: Sorting crite
-000005e0: 7269 6120 696e 2074 6865 2066 6f72 6d61  ria in the forma
-000005f0: 743a 2070 726f 7065 7274 797b 2c61 7363  t: property{,asc
-00000600: 7c64 6573 637d 2e20 4578 616d 706c 653a  |desc}. Example:
-00000610: 2063 7265 6174 6564 4174 2c64 6573 630a   createdAt,desc.
-00000620: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00000630: 2020 2020 2020 2044 6566 6175 6c74 2073         Default s
-00000640: 6f72 7420 6f72 6465 7220 6973 2061 7363  ort order is asc
-00000650: 656e 6469 6e67 2e20 4d75 6c74 6970 6c65  ending. Multiple
-00000660: 2073 6f72 7420 6372 6974 6572 6961 2061   sort criteria a
-00000670: 7265 2073 7570 706f 7274 6564 2e0a 2020  re supported..  
-00000680: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00000690: 2020 2020 2050 6c65 6173 6520 7265 6665       Please refe
-000006a0: 7220 746f 2074 6865 206d 6574 686f 6420  r to the method 
-000006b0: 6465 7363 7269 7074 696f 6e20 666f 7220  description for 
-000006c0: 7375 7070 6f72 7465 6420 7072 6f70 6572  supported proper
-000006d0: 7469 6573 2e20 4465 6661 756c 7420 7661  ties. Default va
-000006e0: 6c75 6520 6973 204e 6f6e 652e 0a20 2020  lue is None..   
-000006f0: 2020 2020 203a 7479 7065 2073 6f72 743a       :type sort:
-00000700: 204f 7074 696f 6e61 6c5b 556e 696f 6e5b   Optional[Union[
-00000710: 7374 722c 204c 6973 745b 7374 725d 5d5d  str, List[str]]]
-00000720: 0a20 2020 2020 2020 203a 6b65 7977 6f72  .        :keywor
-00000730: 6420 7479 7065 3a20 4669 6c74 6572 2070  d type: Filter p
-00000740: 7269 6e63 6970 616c 7320 6279 2074 7970  rincipals by typ
-00000750: 652e 204b 6e6f 776e 2076 616c 7565 7320  e. Known values 
-00000760: 6172 653a 2022 5553 4552 222c 2022 4150  are: "USER", "AP
-00000770: 504c 4943 4154 494f 4e22 2c20 616e 640a  PLICATION", and.
-00000780: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00000790: 2020 2020 2020 2253 5953 5445 4d22 2e20        "SYSTEM". 
-000007a0: 4465 6661 756c 7420 7661 6c75 6520 6973  Default value is
-000007b0: 204e 6f6e 652e 0a20 2020 2020 2020 203a   None..        :
-000007c0: 7479 7065 2074 7970 653a 204f 7074 696f  type type: Optio
-000007d0: 6e61 6c5b 5f6d 6f64 656c 732e 5072 696e  nal[_models.Prin
-000007e0: 6369 7061 6c54 7970 655d 0a20 2020 2020  cipalType].     
-000007f0: 2020 203a 6b65 7977 6f72 6420 6772 6f75     :keyword grou
-00000800: 705f 6964 3a20 4669 6c74 6572 2070 7269  p_id: Filter pri
-00000810: 6e63 6970 616c 7320 7468 6174 2065 7869  ncipals that exi
-00000820: 7374 7320 696e 206f 6e65 206f 6620 6772  sts in one of gr
-00000830: 6f75 7020 6964 732e 2044 6566 6175 6c74  oup ids. Default
-00000840: 2076 616c 7565 2069 7320 4e6f 6e65 2e0a   value is None..
-00000850: 2020 2020 2020 2020 3a74 7970 6520 6772          :type gr
-00000860: 6f75 705f 6964 3a20 4f70 7469 6f6e 616c  oup_id: Optional
-00000870: 5b55 6e69 6f6e 5b73 7472 2c20 4c69 7374  [Union[str, List
-00000880: 5b73 7472 5d5d 5d0a 2020 2020 2020 2020  [str]]].        
-00000890: 3a72 6574 7572 6e3a 2050 7269 6e63 6970  :return: Princip
-000008a0: 616c 5061 6765 0a20 2020 2020 2020 203a  alPage.        :
-000008b0: 7274 7970 653a 207e 6b75 666c 6f77 2e72  rtype: ~kuflow.r
-000008c0: 6573 742e 6d6f 6465 6c73 2e50 7269 6e63  est.models.Princ
-000008d0: 6970 616c 5061 6765 0a20 2020 2020 2020  ipalPage.       
-000008e0: 203a 7261 6973 6573 207e 617a 7572 652e   :raises ~azure.
-000008f0: 636f 7265 2e65 7863 6570 7469 6f6e 732e  core.exceptions.
-00000900: 4874 7470 5265 7370 6f6e 7365 4572 726f  HttpResponseErro
-00000910: 723a 0a20 2020 2020 2020 204e 2905 7211  r:.        N).r.
-00000920: 0000 0072 1200 0000 7213 0000 0072 1400  ...r....r....r..
-00000930: 0000 7215 0000 0029 05da 0a69 7369 6e73  ..r....)...isins
-00000940: 7461 6e63 65da 0373 7472 720b 0000 00da  tance..strr.....
-00000950: 0970 7269 6e63 6970 616c da0f 6669 6e64  .principal..find
-00000960: 5f70 7269 6e63 6970 616c 7329 0772 0c00  _principals).r..
-00000970: 0000 7211 0000 0072 1200 0000 7213 0000  ..r....r....r...
-00000980: 0072 1400 0000 7215 0000 0072 1600 0000  .r....r....r....
-00000990: 720d 0000 0072 0d00 0000 720e 0000 0072  r....r....r....r
-000009a0: 1b00 0000 2d00 0000 731a 0000 0000 2112  ....-...s.....!.
-000009b0: 0106 0212 0106 020a 0102 0002 0002 0002  ................
-000009c0: 0002 ff04 0102 ff7a 2350 7269 6e63 6970  .......z#Princip
-000009d0: 616c 4f70 6572 6174 696f 6e73 2e66 696e  alOperations.fin
-000009e0: 645f 7072 696e 6369 7061 6c73 2903 da02  d_principals)...
-000009f0: 6964 7216 0000 0072 1700 0000 6302 0000  idr....r....c...
-00000a00: 0000 0000 0000 0000 0003 0000 0004 0000  ................
-00000a10: 004b 0000 0073 1800 0000 7c00 6a00 6a01  .K...s....|.j.j.
-00000a20: 6a02 6600 6401 7c01 6901 7c02 9702 8e01  j.f.d.|.i.|.....
-00000a30: 5300 2902 612a 0100 0047 6574 2061 2050  S.).a*...Get a P
-00000a40: 7269 6e63 6970 616c 2062 7920 4944 2e0a  rincipal by ID..
-00000a50: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
-00000a60: 2074 6865 2072 6571 7565 7374 6564 2050   the requested P
-00000a70: 7269 6e63 6970 616c 2077 6865 6e20 6861  rincipal when ha
-00000a80: 7320 6163 6365 7373 2074 6f20 646f 2069  s access to do i
-00000a90: 742e 0a0a 2020 2020 2020 2020 3a70 6172  t...        :par
-00000aa0: 616d 2069 643a 2054 6865 2072 6573 6f75  am id: The resou
-00000ab0: 7263 6520 4944 2e20 5265 7175 6972 6564  rce ID. Required
-00000ac0: 2e0a 2020 2020 2020 2020 3a74 7970 6520  ..        :type 
-00000ad0: 6964 3a20 7374 720a 2020 2020 2020 2020  id: str.        
-00000ae0: 3a72 6574 7572 6e3a 2050 7269 6e63 6970  :return: Princip
-00000af0: 616c 0a20 2020 2020 2020 203a 7274 7970  al.        :rtyp
-00000b00: 653a 207e 6b75 666c 6f77 2e72 6573 742e  e: ~kuflow.rest.
-00000b10: 6d6f 6465 6c73 2e50 7269 6e63 6970 616c  models.Principal
-00000b20: 0a20 2020 2020 2020 203a 7261 6973 6573  .        :raises
-00000b30: 207e 617a 7572 652e 636f 7265 2e65 7863   ~azure.core.exc
-00000b40: 6570 7469 6f6e 732e 4874 7470 5265 7370  eptions.HttpResp
-00000b50: 6f6e 7365 4572 726f 723a 0a20 2020 2020  onseError:.     
-00000b60: 2020 2072 1c00 0000 2903 720b 0000 0072     r....).r....r
-00000b70: 1a00 0000 da12 7265 7472 6965 7665 5f70  ......retrieve_p
-00000b80: 7269 6e63 6970 616c 2903 720c 0000 0072  rincipal).r....r
-00000b90: 1c00 0000 7216 0000 0072 0d00 0000 720d  ....r....r....r.
-00000ba0: 0000 0072 0e00 0000 721d 0000 0058 0000  ...r....r....X..
-00000bb0: 0073 0200 0000 000b 7a26 5072 696e 6369  .s......z&Princi
-00000bc0: 7061 6c4f 7065 7261 7469 6f6e 732e 7265  palOperations.re
-00000bd0: 7472 6965 7665 5f70 7269 6e63 6970 616c  trieve_principal
-00000be0: 2905 7210 0000 0072 0100 0000 4e4e 4e29  ).r....r....NNN)
-00000bf0: 12da 085f 5f6e 616d 655f 5fda 0a5f 5f6d  ...__name__..__m
-00000c00: 6f64 756c 655f 5fda 0c5f 5f71 7561 6c6e  odule__..__qualn
-00000c10: 616d 655f 5fda 075f 5f64 6f63 5f5f da19  ame__..__doc__..
-00000c20: 4b75 466c 6f77 5265 7374 436c 6965 6e74  KuFlowRestClient
-00000c30: 4765 6e65 7261 7465 6472 0f00 0000 da03  Generatedr......
-00000c40: 696e 7472 0400 0000 7205 0000 0072 1900  intr....r....r..
-00000c50: 0000 7203 0000 00da 075f 6d6f 6465 6c73  ..r......_models
-00000c60: da0d 5072 696e 6369 7061 6c54 7970 6572  ..PrincipalTyper
-00000c70: 0200 0000 da0d 5072 696e 6369 7061 6c50  ......PrincipalP
-00000c80: 6167 6572 1b00 0000 da09 5072 696e 6369  ager......Princi
-00000c90: 7061 6c72 1d00 0000 720d 0000 0072 0d00  palr....r....r..
-00000ca0: 0000 720d 0000 0072 0e00 0000 7209 0000  ..r....r....r...
-00000cb0: 0020 0000 0073 2200 0000 0801 0409 0e05  . ...s".........
-00000cc0: 0001 0001 0001 0001 00fa 0202 0201 0201  ................
-00000cd0: 1201 0801 1201 0201 04f8 0c2b 7209 0000  ...........+r...
-00000ce0: 004e 290b da06 7479 7069 6e67 7202 0000  .N)...typingr...
-00000cf0: 0072 0300 0000 7204 0000 0072 0500 0000  .r....r....r....
-00000d00: da0a 5f67 656e 6572 6174 6564 7207 0000  .._generatedr...
-00000d10: 0072 2400 0000 7208 0000 0072 2200 0000  .r$...r....r"...
-00000d20: 7209 0000 0072 0d00 0000 720d 0000 0072  r....r....r....r
-00000d30: 0d00 0000 720e 0000 00da 083c 6d6f 6475  ....r......<modu
-00000d40: 6c65 3e1b 0000 0073 0400 0000 1802 1003  le>....s........
+00000050: 0100 6402 6404 6c05 6d08 5a09 0100 4700  ..d.d.l.m.Z...G.
+00000060: 6405 6406 8400 6406 8302 5a0a 6407 5300  d.d...d...Z.d.S.
+00000070: 2908 e900 0000 0029 04da 0341 6e79 da04  )......)...Any..
+00000080: 4c69 7374 da08 4f70 7469 6f6e 616c da05  List..Optional..
+00000090: 556e 696f 6ee9 0200 0000 2901 da10 4b75  Union.....)...Ku
+000000a0: 466c 6f77 5265 7374 436c 6965 6e74 2901  FlowRestClient).
+000000b0: da06 6d6f 6465 6c73 6300 0000 0000 0000  ..modelsc.......
+000000c0: 0000 0000 0000 0000 000a 0000 0040 0000  .............@..
+000000d0: 0073 7600 0000 6500 5a01 6400 5a02 6401  .sv...e.Z.d.Z.d.
+000000e0: 5a03 6504 6402 9c01 6403 6404 8404 5a05  Z.e.d...d.d...Z.
+000000f0: 640e 6506 6506 6507 6508 6509 650a 6509  d.e.e.e.e.e.e.e.
+00000100: 1900 6602 1900 1900 6507 650b 6a0c 1900  ..f.....e.e.j...
+00000110: 6507 6508 6509 650a 6509 1900 6602 1900  e.e.e.e.e...f...
+00000120: 1900 650d 650b 6a0e 6408 9c07 6409 640a  ..e.e.j.d...d.d.
+00000130: 8405 5a0f 6509 650d 650b 6a10 640b 9c03  ..Z.e.e.e.j.d...
+00000140: 640c 640d 8404 5a11 6407 5300 290f da13  d.d...Z.d.S.)...
+00000150: 5072 696e 6369 7061 6c4f 7065 7261 7469  PrincipalOperati
+00000160: 6f6e 737a ec0a 2020 2020 2e2e 2077 6172  onsz..    .. war
+00000170: 6e69 6e67 3a3a 0a20 2020 2020 2020 202a  ning::.        *
+00000180: 2a44 4f20 4e4f 542a 2a20 696e 7374 616e  *DO NOT** instan
+00000190: 7469 6174 6520 7468 6973 2063 6c61 7373  tiate this class
+000001a0: 2064 6972 6563 746c 792e 0a0a 2020 2020   directly...    
+000001b0: 2020 2020 496e 7374 6561 642c 2079 6f75      Instead, you
+000001c0: 2073 686f 756c 6420 6163 6365 7373 2074   should access t
+000001d0: 6865 2066 6f6c 6c6f 7769 6e67 206f 7065  he following ope
+000001e0: 7261 7469 6f6e 7320 7468 726f 7567 680a  rations through.
+000001f0: 2020 2020 2020 2020 3a63 6c61 7373 3a60          :class:`
+00000200: 7e6b 7566 6c6f 772e 7265 7374 2e63 6c69  ~kuflow.rest.cli
+00000210: 656e 742e 4b75 466c 6f77 5265 7374 436c  ent.KuFlowRestCl
+00000220: 6965 6e74 6027 730a 2020 2020 2020 2020  ient`'s.        
+00000230: 3a61 7474 723a 6070 7269 6e63 6970 616c  :attr:`principal
+00000240: 6020 6174 7472 6962 7574 652e 0a20 2020  ` attribute..   
+00000250: 2029 01da 0d6b 7566 6c6f 775f 636c 6965   )...kuflow_clie
+00000260: 6e74 6302 0000 0000 0000 0000 0000 0002  ntc.............
+00000270: 0000 0002 0000 0043 0000 0073 0a00 0000  .......C...s....
+00000280: 7c01 7c00 5f00 6400 5300 2901 4e29 01da  |.|._.d.S.).N)..
+00000290: 0e5f 6b75 666c 6f77 5f63 6c69 656e 7429  ._kuflow_client)
+000002a0: 02da 0473 656c 6672 0a00 0000 a900 720d  ...selfr......r.
+000002b0: 0000 00fa 532f 776f 726b 2f6b 7566 6c6f  ....S/work/kuflo
+000002c0: 772d 7364 6b2d 7079 7468 6f6e 2f6b 7566  w-sdk-python/kuf
+000002d0: 6c6f 772d 7265 7374 2f6b 7566 6c6f 775f  low-rest/kuflow_
+000002e0: 7265 7374 2f6f 7065 7261 7469 6f6e 732f  rest/operations/
+000002f0: 5f70 7269 6e63 6970 616c 5f6f 7065 7261  _principal_opera
+00000300: 7469 6f6e 732e 7079 da08 5f5f 696e 6974  tions.py..__init
+00000310: 5f5f 2b00 0000 7302 0000 0000 017a 1c50  __+...s......z.P
+00000320: 7269 6e63 6970 616c 4f70 6572 6174 696f  rincipalOperatio
+00000330: 6e73 2e5f 5f69 6e69 745f 5fe9 1900 0000  ns.__init__.....
+00000340: 7201 0000 004e 2907 da04 7369 7a65 da04  r....N)...size..
+00000350: 7061 6765 da04 736f 7274 da04 7479 7065  page..sort..type
+00000360: da08 6772 6f75 705f 6964 da06 6b77 6172  ..group_id..kwar
+00000370: 6773 da06 7265 7475 726e 6306 0000 0000  gs..returnc.....
+00000380: 0000 0000 0000 0007 0000 0008 0000 004b  ...............K
+00000390: 0000 0073 5000 0000 7c03 6401 6b09 7218  ...sP...|.d.k.r.
+000003a0: 7400 7c03 7401 8302 7218 7c03 6701 7d03  t.|.t...r.|.g.}.
+000003b0: 7c05 6401 6b09 7230 7400 7c05 7401 8302  |.d.k.r0t.|.t...
+000003c0: 7230 7c05 6701 7d05 7c00 6a02 6a03 6a04  r0|.g.}.|.j.j.j.
+000003d0: 6600 7c01 7c02 7c03 7c04 7c05 6402 9c05  f.|.|.|.|.|.d...
+000003e0: 7c06 9702 8e01 5300 2903 6136 0500 0046  |.....S.).a6...F
+000003f0: 696e 6420 616c 6c20 6163 6365 7373 6962  ind all accessib
+00000400: 6c65 2050 7269 6e63 6970 616c 732e 0a0a  le Principals...
+00000410: 2020 2020 2020 2020 4c69 7374 2061 6c6c          List all
+00000420: 2074 6865 2050 7269 6e63 6970 616c 7320   the Principals 
+00000430: 7468 6174 2068 6176 6520 6265 656e 2063  that have been c
+00000440: 7265 6174 6564 2061 6e64 2074 6865 2075  reated and the u
+00000450: 7365 6420 6372 6564 656e 7469 616c 7320  sed credentials 
+00000460: 6861 7320 6163 6365 7373 2e0a 0a20 2020  has access...   
+00000470: 2020 2020 2041 7661 696c 6162 6c65 2073       Available s
+00000480: 6f72 7420 7175 6572 7920 7661 6c75 6573  ort query values
+00000490: 3a20 6964 2c20 6e61 6d65 2e0a 0a20 2020  : id, name...   
+000004a0: 2020 2020 203a 6b65 7977 6f72 6420 7369       :keyword si
+000004b0: 7a65 3a20 5468 6520 6e75 6d62 6572 206f  ze: The number o
+000004c0: 6620 7265 636f 7264 7320 7265 7475 726e  f records return
+000004d0: 6564 2077 6974 6869 6e20 6120 7369 6e67  ed within a sing
+000004e0: 6c65 2041 5049 2063 616c 6c2e 2044 6566  le API call. Def
+000004f0: 6175 6c74 2076 616c 7565 2069 7320 3235  ault value is 25
+00000500: 2e0a 2020 2020 2020 2020 3a74 7970 6520  ..        :type 
+00000510: 7369 7a65 3a20 696e 740a 2020 2020 2020  size: int.      
+00000520: 2020 3a6b 6579 776f 7264 2070 6167 653a    :keyword page:
+00000530: 2054 6865 2070 6167 6520 6e75 6d62 6572   The page number
+00000540: 206f 6620 7468 6520 6375 7272 656e 7420   of the current 
+00000550: 7061 6765 2069 6e20 7468 6520 7265 7475  page in the retu
+00000560: 726e 6564 2072 6563 6f72 6473 2c20 3020  rned records, 0 
+00000570: 6973 2074 6865 2066 6972 7374 2070 6167  is the first pag
+00000580: 652e 0a20 2020 2020 2020 2020 2020 2020  e..             
+00000590: 2020 2020 2020 2020 2020 4465 6661 756c            Defaul
+000005a0: 7420 7661 6c75 6520 6973 2030 2e0a 2020  t value is 0..  
+000005b0: 2020 2020 2020 3a74 7970 6520 7061 6765        :type page
+000005c0: 3a20 696e 740a 2020 2020 2020 2020 3a6b  : int.        :k
+000005d0: 6579 776f 7264 2073 6f72 743a 2053 6f72  eyword sort: Sor
+000005e0: 7469 6e67 2063 7269 7465 7269 6120 696e  ting criteria in
+000005f0: 2074 6865 2066 6f72 6d61 743a 2070 726f   the format: pro
+00000600: 7065 7274 797b 2c61 7363 7c64 6573 637d  perty{,asc|desc}
+00000610: 2e20 4578 616d 706c 653a 2063 7265 6174  . Example: creat
+00000620: 6564 4174 2c64 6573 630a 2020 2020 2020  edAt,desc.      
+00000630: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00000640: 2044 6566 6175 6c74 2073 6f72 7420 6f72   Default sort or
+00000650: 6465 7220 6973 2061 7363 656e 6469 6e67  der is ascending
+00000660: 2e20 4d75 6c74 6970 6c65 2073 6f72 7420  . Multiple sort 
+00000670: 6372 6974 6572 6961 2061 7265 2073 7570  criteria are sup
+00000680: 706f 7274 6564 2e0a 2020 2020 2020 2020  ported..        
+00000690: 2020 2020 2020 2020 2020 2020 2020 2050                 P
+000006a0: 6c65 6173 6520 7265 6665 7220 746f 2074  lease refer to t
+000006b0: 6865 206d 6574 686f 6420 6465 7363 7269  he method descri
+000006c0: 7074 696f 6e20 666f 7220 7375 7070 6f72  ption for suppor
+000006d0: 7465 6420 7072 6f70 6572 7469 6573 2e20  ted properties. 
+000006e0: 4465 6661 756c 7420 7661 6c75 6520 6973  Default value is
+000006f0: 204e 6f6e 652e 0a20 2020 2020 2020 203a   None..        :
+00000700: 7479 7065 2073 6f72 743a 204f 7074 696f  type sort: Optio
+00000710: 6e61 6c5b 556e 696f 6e5b 7374 722c 204c  nal[Union[str, L
+00000720: 6973 745b 7374 725d 5d5d 0a20 2020 2020  ist[str]]].     
+00000730: 2020 203a 6b65 7977 6f72 6420 7479 7065     :keyword type
+00000740: 3a20 4669 6c74 6572 2070 7269 6e63 6970  : Filter princip
+00000750: 616c 7320 6279 2074 7970 652e 204b 6e6f  als by type. Kno
+00000760: 776e 2076 616c 7565 7320 6172 653a 2022  wn values are: "
+00000770: 5553 4552 222c 2022 4150 504c 4943 4154  USER", "APPLICAT
+00000780: 494f 4e22 2c20 616e 640a 2020 2020 2020  ION", and.      
+00000790: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000007a0: 2253 5953 5445 4d22 2e20 4465 6661 756c  "SYSTEM". Defaul
+000007b0: 7420 7661 6c75 6520 6973 204e 6f6e 652e  t value is None.
+000007c0: 0a20 2020 2020 2020 203a 7479 7065 2074  .        :type t
+000007d0: 7970 653a 204f 7074 696f 6e61 6c5b 5f6d  ype: Optional[_m
+000007e0: 6f64 656c 732e 5072 696e 6369 7061 6c54  odels.PrincipalT
+000007f0: 7970 655d 0a20 2020 2020 2020 203a 6b65  ype].        :ke
+00000800: 7977 6f72 6420 6772 6f75 705f 6964 3a20  yword group_id: 
+00000810: 4669 6c74 6572 2070 7269 6e63 6970 616c  Filter principal
+00000820: 7320 7468 6174 2065 7869 7374 7320 696e  s that exists in
+00000830: 206f 6e65 206f 6620 6772 6f75 7020 6964   one of group id
+00000840: 732e 2044 6566 6175 6c74 2076 616c 7565  s. Default value
+00000850: 2069 7320 4e6f 6e65 2e0a 2020 2020 2020   is None..      
+00000860: 2020 3a74 7970 6520 6772 6f75 705f 6964    :type group_id
+00000870: 3a20 4f70 7469 6f6e 616c 5b55 6e69 6f6e  : Optional[Union
+00000880: 5b73 7472 2c20 4c69 7374 5b73 7472 5d5d  [str, List[str]]
+00000890: 5d0a 2020 2020 2020 2020 3a72 6574 7572  ].        :retur
+000008a0: 6e3a 2050 7269 6e63 6970 616c 5061 6765  n: PrincipalPage
+000008b0: 0a20 2020 2020 2020 203a 7274 7970 653a  .        :rtype:
+000008c0: 207e 6b75 666c 6f77 2e72 6573 742e 6d6f   ~kuflow.rest.mo
+000008d0: 6465 6c73 2e50 7269 6e63 6970 616c 5061  dels.PrincipalPa
+000008e0: 6765 0a20 2020 2020 2020 203a 7261 6973  ge.        :rais
+000008f0: 6573 207e 617a 7572 652e 636f 7265 2e65  es ~azure.core.e
+00000900: 7863 6570 7469 6f6e 732e 4874 7470 5265  xceptions.HttpRe
+00000910: 7370 6f6e 7365 4572 726f 723a 0a20 2020  sponseError:.   
+00000920: 2020 2020 204e 2905 7211 0000 0072 1200       N).r....r..
+00000930: 0000 7213 0000 0072 1400 0000 7215 0000  ..r....r....r...
+00000940: 0029 05da 0a69 7369 6e73 7461 6e63 65da  .)...isinstance.
+00000950: 0373 7472 720b 0000 00da 0970 7269 6e63  .strr......princ
+00000960: 6970 616c da0f 6669 6e64 5f70 7269 6e63  ipal..find_princ
+00000970: 6970 616c 7329 0772 0c00 0000 7211 0000  ipals).r....r...
+00000980: 0072 1200 0000 7213 0000 0072 1400 0000  .r....r....r....
+00000990: 7215 0000 0072 1600 0000 720d 0000 0072  r....r....r....r
+000009a0: 0d00 0000 720e 0000 0072 1b00 0000 2e00  ....r....r......
+000009b0: 0000 731a 0000 0000 2112 0106 0212 0106  ..s.....!.......
+000009c0: 020a 0102 0002 0002 0002 0002 ff04 0102  ................
+000009d0: ff7a 2350 7269 6e63 6970 616c 4f70 6572  .z#PrincipalOper
+000009e0: 6174 696f 6e73 2e66 696e 645f 7072 696e  ations.find_prin
+000009f0: 6369 7061 6c73 2903 da02 6964 7216 0000  cipals)...idr...
+00000a00: 0072 1700 0000 6302 0000 0000 0000 0000  .r....c.........
+00000a10: 0000 0003 0000 0004 0000 004b 0000 0073  ...........K...s
+00000a20: 1800 0000 7c00 6a00 6a01 6a02 6600 6401  ....|.j.j.j.f.d.
+00000a30: 7c01 6901 7c02 9702 8e01 5300 2902 612a  |.i.|.....S.).a*
+00000a40: 0100 0047 6574 2061 2050 7269 6e63 6970  ...Get a Princip
+00000a50: 616c 2062 7920 4944 2e0a 0a20 2020 2020  al by ID...     
+00000a60: 2020 2052 6574 7572 6e73 2074 6865 2072     Returns the r
+00000a70: 6571 7565 7374 6564 2050 7269 6e63 6970  equested Princip
+00000a80: 616c 2077 6865 6e20 6861 7320 6163 6365  al when has acce
+00000a90: 7373 2074 6f20 646f 2069 742e 0a0a 2020  ss to do it...  
+00000aa0: 2020 2020 2020 3a70 6172 616d 2069 643a        :param id:
+00000ab0: 2054 6865 2072 6573 6f75 7263 6520 4944   The resource ID
+00000ac0: 2e20 5265 7175 6972 6564 2e0a 2020 2020  . Required..    
+00000ad0: 2020 2020 3a74 7970 6520 6964 3a20 7374      :type id: st
+00000ae0: 720a 2020 2020 2020 2020 3a72 6574 7572  r.        :retur
+00000af0: 6e3a 2050 7269 6e63 6970 616c 0a20 2020  n: Principal.   
+00000b00: 2020 2020 203a 7274 7970 653a 207e 6b75       :rtype: ~ku
+00000b10: 666c 6f77 2e72 6573 742e 6d6f 6465 6c73  flow.rest.models
+00000b20: 2e50 7269 6e63 6970 616c 0a20 2020 2020  .Principal.     
+00000b30: 2020 203a 7261 6973 6573 207e 617a 7572     :raises ~azur
+00000b40: 652e 636f 7265 2e65 7863 6570 7469 6f6e  e.core.exception
+00000b50: 732e 4874 7470 5265 7370 6f6e 7365 4572  s.HttpResponseEr
+00000b60: 726f 723a 0a20 2020 2020 2020 2072 1c00  ror:.        r..
+00000b70: 0000 2903 720b 0000 0072 1a00 0000 da12  ..).r....r......
+00000b80: 7265 7472 6965 7665 5f70 7269 6e63 6970  retrieve_princip
+00000b90: 616c 2903 720c 0000 0072 1c00 0000 7216  al).r....r....r.
+00000ba0: 0000 0072 0d00 0000 720d 0000 0072 0e00  ...r....r....r..
+00000bb0: 0000 721d 0000 0059 0000 0073 0200 0000  ..r....Y...s....
+00000bc0: 000b 7a26 5072 696e 6369 7061 6c4f 7065  ..z&PrincipalOpe
+00000bd0: 7261 7469 6f6e 732e 7265 7472 6965 7665  rations.retrieve
+00000be0: 5f70 7269 6e63 6970 616c 2905 7210 0000  _principal).r...
+00000bf0: 0072 0100 0000 4e4e 4e29 12da 085f 5f6e  .r....NNN)...__n
+00000c00: 616d 655f 5fda 0a5f 5f6d 6f64 756c 655f  ame__..__module_
+00000c10: 5fda 0c5f 5f71 7561 6c6e 616d 655f 5fda  _..__qualname__.
+00000c20: 075f 5f64 6f63 5f5f da19 4b75 466c 6f77  .__doc__..KuFlow
+00000c30: 5265 7374 436c 6965 6e74 4765 6e65 7261  RestClientGenera
+00000c40: 7465 6472 0f00 0000 da03 696e 7472 0400  tedr......intr..
+00000c50: 0000 7205 0000 0072 1900 0000 7203 0000  ..r....r....r...
+00000c60: 00da 075f 6d6f 6465 6c73 da0d 5072 696e  ..._models..Prin
+00000c70: 6369 7061 6c54 7970 6572 0200 0000 da0d  cipalTyper......
+00000c80: 5072 696e 6369 7061 6c50 6167 6572 1b00  PrincipalPager..
+00000c90: 0000 da09 5072 696e 6369 7061 6c72 1d00  ....Principalr..
+00000ca0: 0000 720d 0000 0072 0d00 0000 720d 0000  ..r....r....r...
+00000cb0: 0072 0e00 0000 7209 0000 0021 0000 0073  .r....r....!...s
+00000cc0: 2200 0000 0801 0409 0e05 0001 0001 0001  "...............
+00000cd0: 0001 00fa 0202 0201 0201 1201 0801 1201  ................
+00000ce0: 0201 04f8 0c2b 7209 0000 004e 290b da06  .....+r....N)...
+00000cf0: 7479 7069 6e67 7202 0000 0072 0300 0000  typingr....r....
+00000d00: 7204 0000 0072 0500 0000 da0a 5f67 656e  r....r......_gen
+00000d10: 6572 6174 6564 7207 0000 0072 2200 0000  eratedr....r"...
+00000d20: 7208 0000 0072 2400 0000 7209 0000 0072  r....r$...r....r
+00000d30: 0d00 0000 720d 0000 0072 0d00 0000 720e  ....r....r....r.
+00000d40: 0000 00da 083c 6d6f 6475 6c65 3e1b 0000  .....<module>...
+00000d50: 0073 0600 0000 1802 0c01 0c03            .s..........
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_process_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_process_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 9530 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,19 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 3a25 0000  U.......=S.d:%..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 3925 0000  U..........d9%..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 4200 0000 6400  .....@...sB...d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
 00000040: 6d04 5a04 0100 6402 6403 6c05 6d06 5a07  m.Z...d.d.l.m.Z.
 00000050: 0100 6402 6404 6c08 6d09 5a0a 0100 4700  ..d.d.l.m.Z...G.
 00000060: 6405 6406 8400 6406 8302 5a0b 6407 5300  d.d...d...Z.d.S.
 00000070: 2908 e900 0000 0029 04da 0341 6e79 da04  )......)...Any..
 00000080: 4c69 7374 da08 4f70 7469 6f6e 616c da05  List..Optional..
-00000090: 556e 696f 6ee9 0200 0000 2901 da10 4b75  Union.....)...Ku
-000000a0: 466c 6f77 5265 7374 436c 6965 6e74 2901  FlowRestClient).
-000000b0: da06 6d6f 6465 6c73 6300 0000 0000 0000  ..modelsc.......
+00000090: 556e 696f 6ee9 0200 0000 2901 da06 6d6f  Union.....)...mo
+000000a0: 6465 6c73 2901 da10 4b75 466c 6f77 5265  dels)...KuFlowRe
+000000b0: 7374 436c 6965 6e74 6300 0000 0000 0000  stClientc.......
 000000c0: 0000 0000 0000 0000 0008 0000 0040 0000  .............@..
 000000d0: 0073 0201 0000 6500 5a01 6400 5a02 6401  .s....e.Z.d.Z.d.
 000000e0: 5a03 6504 6402 9c01 6403 6404 8404 5a05  Z.e.d...d.d...Z.
 000000f0: 641f 6506 6506 6507 6508 6509 650a 6509  d.e.e.e.e.e.e.e.
 00000100: 1900 6602 1900 1900 650b 650c 6a0d 6408  ..f.....e.e.j.d.
 00000110: 9c05 6409 640a 8405 5a0e 650c 6a0f 650b  ..d.d...Z.e.j.e.
 00000120: 650c 6a0f 640b 9c03 640c 640d 8404 5a10  e.j.d...d.d...Z.
@@ -51,15 +51,15 @@
 00000320: 5f63 6c69 656e 7429 02da 0473 656c 6672  _client)...selfr
 00000330: 0a00 0000 a900 720d 0000 00fa 512f 776f  ......r.....Q/wo
 00000340: 726b 2f6b 7566 6c6f 772d 7364 6b2d 7079  rk/kuflow-sdk-py
 00000350: 7468 6f6e 2f6b 7566 6c6f 772d 7265 7374  thon/kuflow-rest
 00000360: 2f6b 7566 6c6f 775f 7265 7374 2f6f 7065  /kuflow_rest/ope
 00000370: 7261 7469 6f6e 732f 5f70 726f 6365 7373  rations/_process
 00000380: 5f6f 7065 7261 7469 6f6e 732e 7079 da08  _operations.py..
-00000390: 5f5f 696e 6974 5f5f 2b00 0000 7302 0000  __init__+...s...
+00000390: 5f5f 696e 6974 5f5f 2a00 0000 7302 0000  __init__*...s...
 000003a0: 0000 017a 1a50 726f 6365 7373 4f70 6572  ...z.ProcessOper
 000003b0: 6174 696f 6e73 2e5f 5f69 6e69 745f 5fe9  ations.__init__.
 000003c0: 1900 0000 7201 0000 004e 2905 da04 7369  ....r....N)...si
 000003d0: 7a65 da04 7061 6765 da04 736f 7274 da06  ze..page..sort..
 000003e0: 6b77 6172 6773 da06 7265 7475 726e 6304  kwargs..returnc.
 000003f0: 0000 0000 0000 0000 0000 0005 0000 0006  ................
 00000400: 0000 004b 0000 0073 3400 0000 7c03 6401  ...K...s4...|.d.
@@ -131,15 +131,15 @@
 00000820: 2020 4e29 0372 1100 0000 7212 0000 0072    N).r....r....r
 00000830: 1300 0000 2905 da0a 6973 696e 7374 616e  ....)...isinstan
 00000840: 6365 da03 7374 7272 0b00 0000 da07 7072  ce..strr......pr
 00000850: 6f63 6573 73da 0e66 696e 645f 7072 6f63  ocess..find_proc
 00000860: 6573 7365 7329 0572 0c00 0000 7211 0000  esses).r....r...
 00000870: 0072 1200 0000 7213 0000 0072 1400 0000  .r....r....r....
 00000880: 720d 0000 0072 0d00 0000 720e 0000 0072  r....r....r....r
-00000890: 1900 0000 2e00 0000 7306 0000 0000 1812  ........s.......
+00000890: 1900 0000 2d00 0000 7306 0000 0000 1812  ....-...s.......
 000008a0: 0106 027a 2050 726f 6365 7373 4f70 6572  ...z ProcessOper
 000008b0: 6174 696f 6e73 2e66 696e 645f 7072 6f63  ations.find_proc
 000008c0: 6573 7365 7329 0372 1800 0000 7214 0000  esses).r....r...
 000008d0: 0072 1500 0000 6302 0000 0000 0000 0000  .r....c.........
 000008e0: 0000 0003 0000 0004 0000 004b 0000 0073  ...........K...s
 000008f0: 1800 0000 7c00 6a00 6a01 6a02 6600 6401  ....|.j.j.j.f.d.
 00000900: 7c01 6901 7c02 9702 8e01 5300 2902 6101  |.i.|.....S.).a.
@@ -207,15 +207,15 @@
 00000ce0: 7320 7e61 7a75 7265 2e63 6f72 652e 6578  s ~azure.core.ex
 00000cf0: 6365 7074 696f 6e73 2e48 7474 7052 6573  ceptions.HttpRes
 00000d00: 706f 6e73 6545 7272 6f72 3a0a 2020 2020  ponseError:.    
 00000d10: 2020 2020 7218 0000 0029 0372 0b00 0000      r....).r....
 00000d20: 7218 0000 00da 0e63 7265 6174 655f 7072  r......create_pr
 00000d30: 6f63 6573 7329 0372 0c00 0000 7218 0000  ocess).r....r...
 00000d40: 0072 1400 0000 720d 0000 0072 0d00 0000  .r....r....r....
-00000d50: 720e 0000 0072 1a00 0000 4b00 0000 7302  r....r....K...s.
+00000d50: 720e 0000 0072 1a00 0000 4a00 0000 7302  r....r....J...s.
 00000d60: 0000 0000 177a 2050 726f 6365 7373 4f70  .....z ProcessOp
 00000d70: 6572 6174 696f 6e73 2e63 7265 6174 655f  erations.create_
 00000d80: 7072 6f63 6573 7329 03da 0269 6472 1400  process)...idr..
 00000d90: 0000 7215 0000 0063 0200 0000 0000 0000  ..r....c........
 00000da0: 0000 0000 0300 0000 0400 0000 4b00 0000  ............K...
 00000db0: 7318 0000 007c 006a 006a 016a 0266 0064  s....|.j.j.j.f.d
 00000dc0: 017c 0169 017c 0297 028e 0153 0029 0261  .|.i.|.....S.).a
@@ -237,15 +237,15 @@
 00000ec0: 7365 7320 7e61 7a75 7265 2e63 6f72 652e  ses ~azure.core.
 00000ed0: 6578 6365 7074 696f 6e73 2e48 7474 7052  exceptions.HttpR
 00000ee0: 6573 706f 6e73 6545 7272 6f72 3a0a 2020  esponseError:.  
 00000ef0: 2020 2020 2020 721b 0000 0029 0372 0b00        r....).r..
 00000f00: 0000 7218 0000 00da 1072 6574 7269 6576  ..r......retriev
 00000f10: 655f 7072 6f63 6573 73a9 0372 0c00 0000  e_process..r....
 00000f20: 721b 0000 0072 1400 0000 720d 0000 0072  r....r....r....r
-00000f30: 0d00 0000 720e 0000 0072 1c00 0000 6400  ....r....r....d.
+00000f30: 0d00 0000 720e 0000 0072 1c00 0000 6300  ....r....r....c.
 00000f40: 0000 7302 0000 0000 0b7a 2250 726f 6365  ..s......z"Proce
 00000f50: 7373 4f70 6572 6174 696f 6e73 2e72 6574  ssOperations.ret
 00000f60: 7269 6576 655f 7072 6f63 6573 7329 0472  rieve_process).r
 00000f70: 1b00 0000 da07 636f 6d6d 616e 6472 1400  ......commandr..
 00000f80: 0000 7215 0000 0063 0300 0000 0000 0000  ..r....c........
 00000f90: 0000 0000 0400 0000 0500 0000 4b00 0000  ............K...
 00000fa0: 731a 0000 007c 006a 006a 016a 0266 007c  s....|.j.j.j.f.|
@@ -289,15 +289,15 @@
 00001200: 7470 5265 7370 6f6e 7365 4572 726f 723a  tpResponseError:
 00001210: 0a20 2020 2020 2020 20a9 0272 1b00 0000  .        ..r....
 00001220: 721e 0000 0029 0372 0b00 0000 7218 0000  r....).r....r...
 00001230: 00da 2061 6374 696f 6e73 5f70 726f 6365  .. actions_proce
 00001240: 7373 5f63 6861 6e67 655f 696e 6974 6961  ss_change_initia
 00001250: 746f 72a9 0472 0c00 0000 721b 0000 0072  tor..r....r....r
 00001260: 1e00 0000 7214 0000 0072 0d00 0000 720d  ....r....r....r.
-00001270: 0000 0072 0e00 0000 7220 0000 0071 0000  ...r....r ...q..
+00001270: 0000 0072 0e00 0000 7220 0000 0070 0000  ...r....r ...p..
 00001280: 0073 0200 0000 0013 7a32 5072 6f63 6573  .s......z2Proces
 00001290: 734f 7065 7261 7469 6f6e 732e 6163 7469  sOperations.acti
 000012a0: 6f6e 735f 7072 6f63 6573 735f 6368 616e  ons_process_chan
 000012b0: 6765 5f69 6e69 7469 6174 6f72 6303 0000  ge_initiatorc...
 000012c0: 0000 0000 0000 0000 0004 0000 0005 0000  ................
 000012d0: 004b 0000 0073 1a00 0000 7c00 6a00 6a01  .K...s....|.j.j.
 000012e0: 6a02 6600 7c01 7c02 6401 9c02 7c03 9702  j.f.|.|.d...|...
@@ -346,15 +346,15 @@
 00001590: 7265 2e63 6f72 652e 6578 6365 7074 696f  re.core.exceptio
 000015a0: 6e73 2e48 7474 7052 6573 706f 6e73 6545  ns.HttpResponseE
 000015b0: 7272 6f72 3a0a 2020 2020 2020 2020 721f  rror:.        r.
 000015c0: 0000 0029 0372 0b00 0000 7218 0000 00da  ...).r....r.....
 000015d0: 1c61 6374 696f 6e73 5f70 726f 6365 7373  .actions_process
 000015e0: 5f73 6176 655f 656c 656d 656e 7472 2100  _save_elementr!.
 000015f0: 0000 720d 0000 0072 0d00 0000 720e 0000  ..r....r....r...
-00001600: 0072 2200 0000 8600 0000 7302 0000 0000  .r".......s.....
+00001600: 0072 2200 0000 8500 0000 7302 0000 0000  .r".......s.....
 00001610: 157a 2e50 726f 6365 7373 4f70 6572 6174  .z.ProcessOperat
 00001620: 696f 6e73 2e61 6374 696f 6e73 5f70 726f  ions.actions_pro
 00001630: 6365 7373 5f73 6176 655f 656c 656d 656e  cess_save_elemen
 00001640: 7463 0300 0000 0000 0000 0000 0000 0400  tc..............
 00001650: 0000 0500 0000 4b00 0000 731a 0000 007c  ......K...s....|
 00001660: 006a 006a 016a 0266 007c 017c 0264 019c  .j.j.j.f.|.|.d..
 00001670: 027c 0397 028e 0153 0029 0261 e901 0000  .|.....S.).a....
@@ -389,15 +389,15 @@
 00001840: 7265 2e65 7863 6570 7469 6f6e 732e 4874  re.exceptions.Ht
 00001850: 7470 5265 7370 6f6e 7365 4572 726f 723a  tpResponseError:
 00001860: 0a20 2020 2020 2020 2072 1f00 0000 2903  .        r....).
 00001870: 720b 0000 0072 1800 0000 da1e 6163 7469  r....r......acti
 00001880: 6f6e 735f 7072 6f63 6573 735f 6465 6c65  ons_process_dele
 00001890: 7465 5f65 6c65 6d65 6e74 7221 0000 0072  te_elementr!...r
 000018a0: 0d00 0000 720d 0000 0072 0e00 0000 7223  ....r....r....r#
-000018b0: 0000 009d 0000 0073 0200 0000 0011 7a30  .......s......z0
+000018b0: 0000 009c 0000 0073 0200 0000 0011 7a30  .......s......z0
 000018c0: 5072 6f63 6573 734f 7065 7261 7469 6f6e  ProcessOperation
 000018d0: 732e 6163 7469 6f6e 735f 7072 6f63 6573  s.actions_proces
 000018e0: 735f 6465 6c65 7465 5f65 6c65 6d65 6e74  s_delete_element
 000018f0: 6302 0000 0000 0000 0000 0000 0003 0000  c...............
 00001900: 0004 0000 004b 0000 0073 1800 0000 7c00  .....K...s....|.
 00001910: 6a00 6a01 6a02 6600 6401 7c01 6901 7c02  j.j.j.f.d.|.i.|.
 00001920: 9702 8e01 5300 2902 6168 0100 0043 6f6d  ....S.).ah...Com
@@ -423,15 +423,15 @@
 00001a60: 6573 207e 617a 7572 652e 636f 7265 2e65  es ~azure.core.e
 00001a70: 7863 6570 7469 6f6e 732e 4874 7470 5265  xceptions.HttpRe
 00001a80: 7370 6f6e 7365 4572 726f 723a 0a20 2020  sponseError:.   
 00001a90: 2020 2020 2072 1b00 0000 2903 720b 0000       r....).r...
 00001aa0: 0072 1800 0000 da18 6163 7469 6f6e 735f  .r......actions_
 00001ab0: 7072 6f63 6573 735f 636f 6d70 6c65 7465  process_complete
 00001ac0: 721d 0000 0072 0d00 0000 720d 0000 0072  r....r....r....r
-00001ad0: 0e00 0000 7224 0000 00b0 0000 0073 0200  ....r$.......s..
+00001ad0: 0e00 0000 7224 0000 00af 0000 0073 0200  ....r$.......s..
 00001ae0: 0000 000d 7a2a 5072 6f63 6573 734f 7065  ....z*ProcessOpe
 00001af0: 7261 7469 6f6e 732e 6163 7469 6f6e 735f  rations.actions_
 00001b00: 7072 6f63 6573 735f 636f 6d70 6c65 7465  process_complete
 00001b10: 6302 0000 0000 0000 0000 0000 0003 0000  c...............
 00001b20: 0004 0000 004b 0000 0073 1800 0000 7c00  .....K...s....|.
 00001b30: 6a00 6a01 6a02 6600 6401 7c01 6901 7c02  j.j.j.f.d.|.i.|.
 00001b40: 9702 8e01 5300 2902 61a0 0100 0043 616e  ....S.).a....Can
@@ -460,15 +460,15 @@
 00001cb0: 2020 203a 7261 6973 6573 207e 617a 7572     :raises ~azur
 00001cc0: 652e 636f 7265 2e65 7863 6570 7469 6f6e  e.core.exception
 00001cd0: 732e 4874 7470 5265 7370 6f6e 7365 4572  s.HttpResponseEr
 00001ce0: 726f 723a 0a20 2020 2020 2020 2072 1b00  ror:.        r..
 00001cf0: 0000 2903 720b 0000 0072 1800 0000 da16  ..).r....r......
 00001d00: 6163 7469 6f6e 735f 7072 6f63 6573 735f  actions_process_
 00001d10: 6361 6e63 656c 721d 0000 0072 0d00 0000  cancelr....r....
-00001d20: 720d 0000 0072 0e00 0000 7225 0000 00bf  r....r....r%....
+00001d20: 720d 0000 0072 0e00 0000 7225 0000 00be  r....r....r%....
 00001d30: 0000 0073 0200 0000 000f 7a28 5072 6f63  ...s......z(Proc
 00001d40: 6573 734f 7065 7261 7469 6f6e 732e 6163  essOperations.ac
 00001d50: 7469 6f6e 735f 7072 6f63 6573 735f 6361  tions_process_ca
 00001d60: 6e63 656c 2905 721b 0000 00da 0466 696c  ncel).r......fil
 00001d70: 6572 1e00 0000 7214 0000 0072 1500 0000  er....r....r....
 00001d80: 6304 0000 0000 0000 0000 0000 0005 0000  c...............
 00001d90: 0008 0000 004b 0000 0073 2800 0000 7c00  .....K...s(...|.
@@ -518,15 +518,15 @@
 00002050: 655f 7573 6572 5f61 6374 696f 6e5f 7661  e_user_action_va
 00002060: 6c75 655f 646f 6375 6d65 6e74 5a0c 6669  lue_documentZ.fi
 00002070: 6c65 5f63 6f6e 7465 6e74 da0c 636f 6e74  le_content..cont
 00002080: 656e 745f 7479 7065 5a09 6669 6c65 5f6d  ent_typeZ.file_m
 00002090: 616d 6572 2900 0000 2905 720c 0000 0072  amer)...).r....r
 000020a0: 1b00 0000 7226 0000 0072 1e00 0000 7214  ....r&...r....r.
 000020b0: 0000 0072 0d00 0000 720d 0000 0072 0e00  ...r....r....r..
-000020c0: 0000 722a 0000 00d0 0000 0073 1200 0000  ..r*.......s....
+000020c0: 0000 722a 0000 00cf 0000 0073 1200 0000  ..r*.......s....
 000020d0: 0011 0a01 0201 0401 0401 0401 04fb 0406  ................
 000020e0: 02fa 7a41 5072 6f63 6573 734f 7065 7261  ..zAProcessOpera
 000020f0: 7469 6f6e 732e 6163 7469 6f6e 735f 7072  tions.actions_pr
 00002100: 6f63 6573 735f 7361 7665 5f75 7365 725f  ocess_save_user_
 00002110: 6163 7469 6f6e 5f76 616c 7565 5f64 6f63  action_value_doc
 00002120: 756d 656e 7429 0372 1000 0000 7201 0000  ument).r....r...
 00002130: 004e 291d da08 5f5f 6e61 6d65 5f5f da0a  .N)...__name__..
@@ -547,20 +547,20 @@
 00002220: 456c 656d 656e 7443 6f6d 6d61 6e64 7223  ElementCommandr#
 00002230: 0000 0072 2400 0000 7225 0000 005a 0844  ...r$...r%...Z.D
 00002240: 6f63 756d 656e 745a 2950 726f 6365 7373  ocumentZ)Process
 00002250: 5361 7665 5573 6572 4163 7469 6f6e 5661  SaveUserActionVa
 00002260: 6c75 6544 6f63 756d 656e 7443 6f6d 6d61  lueDocumentComma
 00002270: 6e64 722a 0000 0072 0d00 0000 720d 0000  ndr*...r....r...
 00002280: 0072 0d00 0000 720e 0000 0072 0900 0000  .r....r....r....
-00002290: 2100 0000 734a 0000 0008 0104 090e 0400  !...sJ..........
+00002290: 2000 0000 734a 0000 0008 0104 090e 0400   ...sJ..........
 000022a0: 0000 0000 ff02 0102 0002 0012 0002 0104  ................
 000022b0: fe0c 1d16 1914 0e02 0004 0002 0104 fe0c  ................
 000022c0: 1602 0004 0002 0104 fe0c 1802 0004 0002  ................
 000022d0: 0104 fe0c 1314 0f14 1202 0004 0004 0002  ................
 000022e0: 0108 fe72 0900 0000 4e29 0cda 0674 7970  ...r....N)...typ
 000022f0: 696e 6772 0200 0000 7203 0000 0072 0400  ingr....r....r..
-00002300: 0000 7205 0000 00da 0a5f 6765 6e65 7261  ..r......_genera
-00002310: 7465 6472 0700 0000 7230 0000 00da 0072  tedr....r0.....r
-00002320: 0800 0000 7232 0000 0072 0900 0000 720d  ....r2...r....r.
+00002300: 0000 7205 0000 00da 0072 0700 0000 7232  ..r......r....r2
+00002310: 0000 00da 0a5f 6765 6e65 7261 7465 6472  ....._generatedr
+00002320: 0800 0000 7230 0000 0072 0900 0000 720d  ....r0...r....r.
 00002330: 0000 0072 0d00 0000 720d 0000 0072 0e00  ...r....r....r..
 00002340: 0000 da08 3c6d 6f64 756c 653e 1a00 0000  ....<module>....
-00002350: 7306 0000 0018 020c 020c 03              s..........
+00002350: 7306 0000 0018 020c 010c 03              s..........
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/__pycache__/_task_operations.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/operations/__pycache__/_task_operations.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 17424 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,20 +1,20 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 1044 0000  U.......=S.d.D..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 0f44 0000  U..........d.D..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 4600 0000 6400  .....@...sF...d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
 00000040: 6d04 5a04 6d05 5a05 0100 6402 6403 6c06  m.Z.m.Z...d.d.l.
 00000050: 6d07 5a08 0100 6402 6404 6c09 6d0a 5a0b  m.Z...d.d.l.m.Z.
 00000060: 0100 4700 6405 6406 8400 6406 8302 5a0c  ..G.d.d...d...Z.
 00000070: 6407 5300 2908 e900 0000 0029 05da 0341  d.S.)......)...A
 00000080: 6e79 da08 4974 6572 6174 6f72 da04 4c69  ny..Iterator..Li
 00000090: 7374 da08 4f70 7469 6f6e 616c da05 556e  st..Optional..Un
-000000a0: 696f 6ee9 0200 0000 2901 da10 4b75 466c  ion.....)...KuFl
-000000b0: 6f77 5265 7374 436c 6965 6e74 2901 da06  owRestClient)...
-000000c0: 6d6f 6465 6c73 6300 0000 0000 0000 0000  modelsc.........
+000000a0: 696f 6ee9 0200 0000 2901 da06 6d6f 6465  ion.....)...mode
+000000b0: 6c73 2901 da10 4b75 466c 6f77 5265 7374  ls)...KuFlowRest
+000000c0: 436c 6965 6e74 6300 0000 0000 0000 0000  Clientc.........
 000000d0: 0000 0000 0000 000b 0000 0040 0000 0073  ...........@...s
 000000e0: ec01 0000 6500 5a01 6400 5a02 6401 5a03  ....e.Z.d.Z.d.Z.
 000000f0: 6504 6402 9c01 6403 6404 8404 5a05 6431  e.d...d.d...Z.d1
 00000100: 6506 6506 6507 6508 6509 650a 6509 1900  e.e.e.e.e.e.e...
 00000110: 6602 1900 1900 6507 6508 6509 650a 6509  f.....e.e.e.e.e.
 00000120: 1900 6602 1900 1900 6507 6508 650b 6a0c  ..f.....e.e.e.j.
 00000130: 650a 650b 6a0c 1900 6602 1900 1900 6507  e.e.j...f.....e.
@@ -66,15 +66,15 @@
 00000410: 6f77 5f63 6c69 656e 7429 02da 0473 656c  ow_client)...sel
 00000420: 6672 0b00 0000 a900 720e 0000 00fa 4e2f  fr......r.....N/
 00000430: 776f 726b 2f6b 7566 6c6f 772d 7364 6b2d  work/kuflow-sdk-
 00000440: 7079 7468 6f6e 2f6b 7566 6c6f 772d 7265  python/kuflow-re
 00000450: 7374 2f6b 7566 6c6f 775f 7265 7374 2f6f  st/kuflow_rest/o
 00000460: 7065 7261 7469 6f6e 732f 5f74 6173 6b5f  perations/_task_
 00000470: 6f70 6572 6174 696f 6e73 2e70 79da 085f  operations.py.._
-00000480: 5f69 6e69 745f 5f2c 0000 0073 0200 0000  _init__,...s....
+00000480: 5f69 6e69 745f 5f2b 0000 0073 0200 0000  _init__+...s....
 00000490: 0001 7a17 5461 736b 4f70 6572 6174 696f  ..z.TaskOperatio
 000004a0: 6e73 2e5f 5f69 6e69 745f 5fe9 1900 0000  ns.__init__.....
 000004b0: 7201 0000 004e 2908 da04 7369 7a65 da04  r....N)...size..
 000004c0: 7061 6765 da04 736f 7274 da0a 7072 6f63  page..sort..proc
 000004d0: 6573 735f 6964 da05 7374 6174 65da 1474  ess_id..state..t
 000004e0: 6173 6b5f 6465 6669 6e69 7469 6f6e 5f63  ask_definition_c
 000004f0: 6f64 65da 066b 7761 7267 73da 0672 6574  ode..kwargs..ret
@@ -182,15 +182,15 @@
 00000b50: 0029 07da 0a69 7369 6e73 7461 6e63 65da  .)...isinstance.
 00000b60: 0373 7472 da07 5f6d 6f64 656c 73da 0954  .str.._models..T
 00000b70: 6173 6b53 7461 7465 720c 0000 00da 0474  askStater......t
 00000b80: 6173 6bda 0a66 696e 645f 7461 736b 7329  ask..find_tasks)
 00000b90: 0872 0d00 0000 7212 0000 0072 1300 0000  .r....r....r....
 00000ba0: 7214 0000 0072 1500 0000 7216 0000 0072  r....r....r....r
 00000bb0: 1700 0000 7218 0000 0072 0e00 0000 720e  ....r....r....r.
-00000bc0: 0000 0072 0f00 0000 721f 0000 002f 0000  ...r....r..../..
+00000bc0: 0000 0072 0f00 0000 721f 0000 002e 0000  ...r....r.......
 00000bd0: 0073 2400 0000 0024 1201 0601 1201 0601  .s$....$........
 00000be0: 1401 0601 1201 0602 0a01 0201 0201 0201  ................
 00000bf0: 0201 0201 02fa 0407 02f9 7a19 5461 736b  ..........z.Task
 00000c00: 4f70 6572 6174 696f 6e73 2e66 696e 645f  Operations.find_
 00000c10: 7461 736b 7329 0472 1e00 0000 da0e 6163  tasks).r......ac
 00000c20: 7469 7669 7479 5f74 6f6b 656e 7218 0000  tivity_tokenr...
 00000c30: 0072 1900 0000 6303 0000 0000 0000 0000  .r....c.........
@@ -289,15 +289,15 @@
 00001200: 7572 652e 636f 7265 2e65 7863 6570 7469  ure.core.excepti
 00001210: 6f6e 732e 4874 7470 5265 7370 6f6e 7365  ons.HttpResponse
 00001220: 4572 726f 723a 0a20 2020 2020 2020 2029  Error:.        )
 00001230: 0272 1e00 0000 7220 0000 0029 0372 0c00  .r....r ...).r..
 00001240: 0000 721e 0000 00da 0b63 7265 6174 655f  ..r......create_
 00001250: 7461 736b 2904 720d 0000 0072 1e00 0000  task).r....r....
 00001260: 7220 0000 0072 1800 0000 720e 0000 0072  r ...r....r....r
-00001270: 0e00 0000 720f 0000 0072 2100 0000 6600  ....r....r!...f.
+00001270: 0e00 0000 720f 0000 0072 2100 0000 6500  ....r....r!...e.
 00001280: 0000 7302 0000 0000 1e7a 1a54 6173 6b4f  ..s......z.TaskO
 00001290: 7065 7261 7469 6f6e 732e 6372 6561 7465  perations.create
 000012a0: 5f74 6173 6b29 03da 0269 6472 1800 0000  _task)...idr....
 000012b0: 7219 0000 0063 0200 0000 0000 0000 0000  r....c..........
 000012c0: 0000 0300 0000 0400 0000 4b00 0000 7318  ..........K...s.
 000012d0: 0000 007c 006a 006a 016a 0266 0064 017c  ...|.j.j.j.f.d.|
 000012e0: 0169 017c 0297 028e 0153 0029 0261 0201  .i.|.....S.).a..
@@ -317,15 +317,15 @@
 000013c0: 7320 7e61 7a75 7265 2e63 6f72 652e 6578  s ~azure.core.ex
 000013d0: 6365 7074 696f 6e73 2e48 7474 7052 6573  ceptions.HttpRes
 000013e0: 706f 6e73 6545 7272 6f72 3a0a 2020 2020  ponseError:.    
 000013f0: 2020 2020 7222 0000 0029 0372 0c00 0000      r"...).r....
 00001400: 721e 0000 00da 0d72 6574 7269 6576 655f  r......retrieve_
 00001410: 7461 736b a903 720d 0000 0072 2200 0000  task..r....r"...
 00001420: 7218 0000 0072 0e00 0000 720e 0000 0072  r....r....r....r
-00001430: 0f00 0000 7223 0000 0086 0000 0073 0200  ....r#.......s..
+00001430: 0f00 0000 7223 0000 0085 0000 0073 0200  ....r#.......s..
 00001440: 0000 000b 7a1c 5461 736b 4f70 6572 6174  ....z.TaskOperat
 00001450: 696f 6e73 2e72 6574 7269 6576 655f 7461  ions.retrieve_ta
 00001460: 736b 6302 0000 0000 0000 0000 0000 0003  skc.............
 00001470: 0000 0004 0000 004b 0000 0073 1800 0000  .......K...s....
 00001480: 7c00 6a00 6a01 6a02 6600 6401 7c01 6901  |.j.j.j.f.d.|.i.
 00001490: 7c02 9702 8e01 5300 2902 7af4 436c 6169  |.....S.).z.Clai
 000014a0: 6d20 6120 7461 736b 2e0a 0a20 2020 2020  m a task...     
@@ -342,15 +342,15 @@
 00001550: 2020 2020 2020 3a72 6169 7365 7320 7e61        :raises ~a
 00001560: 7a75 7265 2e63 6f72 652e 6578 6365 7074  zure.core.except
 00001570: 696f 6e73 2e48 7474 7052 6573 706f 6e73  ions.HttpRespons
 00001580: 6545 7272 6f72 3a0a 2020 2020 2020 2020  eError:.        
 00001590: 7222 0000 0029 0372 0c00 0000 721e 0000  r"...).r....r...
 000015a0: 00da 1261 6374 696f 6e73 5f74 6173 6b5f  ...actions_task_
 000015b0: 636c 6169 6d72 2400 0000 720e 0000 0072  claimr$...r....r
-000015c0: 0e00 0000 720f 0000 0072 2500 0000 9300  ....r....r%.....
+000015c0: 0e00 0000 720f 0000 0072 2500 0000 9200  ....r....r%.....
 000015d0: 0000 7302 0000 0000 0b7a 2154 6173 6b4f  ..s......z!TaskO
 000015e0: 7065 7261 7469 6f6e 732e 6163 7469 6f6e  perations.action
 000015f0: 735f 7461 736b 5f63 6c61 696d 2904 7222  s_task_claim).r"
 00001600: 0000 00da 0763 6f6d 6d61 6e64 7218 0000  .....commandr...
 00001610: 0072 1900 0000 6303 0000 0000 0000 0000  .r....c.........
 00001620: 0000 0004 0000 0005 0000 004b 0000 0073  ...........K...s
 00001630: 1a00 0000 7c00 6a00 6a01 6a02 6600 7c01  ....|.j.j.j.f.|.
@@ -383,15 +383,15 @@
 000017e0: 652e 6578 6365 7074 696f 6e73 2e48 7474  e.exceptions.Htt
 000017f0: 7052 6573 706f 6e73 6545 7272 6f72 3a0a  pResponseError:.
 00001800: 2020 2020 2020 2020 a902 7222 0000 0072          ..r"...r
 00001810: 2600 0000 2903 720c 0000 0072 1e00 0000  &...).r....r....
 00001820: da13 6163 7469 6f6e 735f 7461 736b 5f61  ..actions_task_a
 00001830: 7373 6967 6ea9 0472 0d00 0000 7222 0000  ssign..r....r"..
 00001840: 0072 2600 0000 7218 0000 0072 0e00 0000  .r&...r....r....
-00001850: 720e 0000 0072 0f00 0000 7228 0000 00a0  r....r....r(....
+00001850: 720e 0000 0072 0f00 0000 7228 0000 009f  r....r....r(....
 00001860: 0000 0073 0200 0000 000d 7a22 5461 736b  ...s......z"Task
 00001870: 4f70 6572 6174 696f 6e73 2e61 6374 696f  Operations.actio
 00001880: 6e73 5f74 6173 6b5f 6173 7369 676e 6303  ns_task_assignc.
 00001890: 0000 0000 0000 0000 0000 0004 0000 0005  ................
 000018a0: 0000 004b 0000 0073 1a00 0000 7c00 6a00  ...K...s....|.j.
 000018b0: 6a01 6a02 6600 7c01 7c02 6401 9c02 7c03  j.j.f.|.|.d...|.
 000018c0: 9702 8e01 5300 2902 613d 0400 0053 6176  ....S.).a=...Sav
@@ -462,15 +462,15 @@
 00001cd0: 3a72 6169 7365 7320 7e61 7a75 7265 2e63  :raises ~azure.c
 00001ce0: 6f72 652e 6578 6365 7074 696f 6e73 2e48  ore.exceptions.H
 00001cf0: 7474 7052 6573 706f 6e73 6545 7272 6f72  ttpResponseError
 00001d00: 3a0a 2020 2020 2020 2020 7227 0000 0029  :.        r'...)
 00001d10: 0372 0c00 0000 721e 0000 00da 1961 6374  .r....r......act
 00001d20: 696f 6e73 5f74 6173 6b5f 7361 7665 5f65  ions_task_save_e
 00001d30: 6c65 6d65 6e74 7229 0000 0072 0e00 0000  lementr)...r....
-00001d40: 720e 0000 0072 0f00 0000 722a 0000 00af  r....r....r*....
+00001d40: 720e 0000 0072 0f00 0000 722a 0000 00ae  r....r....r*....
 00001d50: 0000 0073 0200 0000 0017 7a28 5461 736b  ...s......z(Task
 00001d60: 4f70 6572 6174 696f 6e73 2e61 6374 696f  Operations.actio
 00001d70: 6e73 5f74 6173 6b5f 7361 7665 5f65 6c65  ns_task_save_ele
 00001d80: 6d65 6e74 2905 7222 0000 00da 0466 696c  ment).r".....fil
 00001d90: 6572 2600 0000 7218 0000 0072 1900 0000  er&...r....r....
 00001da0: 6304 0000 0000 0000 0000 0000 0005 0000  c...............
 00001db0: 000a 0000 004b 0000 0073 3000 0000 7c00  .....K...s0...|.
@@ -538,15 +538,15 @@
 00002190: 656d 656e 745f 7661 6c75 655f 646f 6375  ement_value_docu
 000021a0: 6d65 6e74 da0c 6669 6c65 5f63 6f6e 7465  ment..file_conte
 000021b0: 6e74 da0c 636f 6e74 656e 745f 7479 7065  nt..content_type
 000021c0: da09 6669 6c65 5f6d 616d 6572 2e00 0000  ..file_mamer....
 000021d0: 722f 0000 0072 3000 0000 a905 720d 0000  r/...r0.....r...
 000021e0: 0072 2200 0000 722b 0000 0072 2600 0000  .r"...r+...r&...
 000021f0: 7218 0000 0072 0e00 0000 720e 0000 0072  r....r....r....r
-00002200: 0f00 0000 7231 0000 00c8 0000 0073 1600  ....r1.......s..
+00002200: 0f00 0000 7231 0000 00c7 0000 0073 1600  ....r1.......s..
 00002210: 0000 0015 0a01 0201 0401 0401 0401 0401  ................
 00002220: 0401 04f9 0408 02f8 7a37 5461 736b 4f70  ........z7TaskOp
 00002230: 6572 6174 696f 6e73 2e61 6374 696f 6e73  erations.actions
 00002240: 5f74 6173 6b5f 7361 7665 5f65 6c65 6d65  _task_save_eleme
 00002250: 6e74 5f76 616c 7565 5f64 6f63 756d 656e  nt_value_documen
 00002260: 7463 0300 0000 0000 0000 0000 0000 0400  tc..............
 00002270: 0000 0500 0000 4b00 0000 731a 0000 007c  ......K...s....|
@@ -582,15 +582,15 @@
 00002450: 636f 7265 2e65 7863 6570 7469 6f6e 732e  core.exceptions.
 00002460: 4874 7470 5265 7370 6f6e 7365 4572 726f  HttpResponseErro
 00002470: 723a 0a20 2020 2020 2020 2072 2700 0000  r:.        r'...
 00002480: 2903 720c 0000 0072 1e00 0000 da1b 6163  ).r....r......ac
 00002490: 7469 6f6e 735f 7461 736b 5f64 656c 6574  tions_task_delet
 000024a0: 655f 656c 656d 656e 7472 2900 0000 720e  e_elementr)...r.
 000024b0: 0000 0072 0e00 0000 720f 0000 0072 3600  ...r....r....r6.
-000024c0: 0000 e800 0000 7302 0000 0000 117a 2a54  ......s......z*T
+000024c0: 0000 e700 0000 7302 0000 0000 117a 2a54  ......s......z*T
 000024d0: 6173 6b4f 7065 7261 7469 6f6e 732e 6163  askOperations.ac
 000024e0: 7469 6f6e 735f 7461 736b 5f64 656c 6574  tions_task_delet
 000024f0: 655f 656c 656d 656e 7463 0300 0000 0000  e_elementc......
 00002500: 0000 0000 0000 0400 0000 0500 0000 4b00  ..............K.
 00002510: 0000 731a 0000 007c 006a 006a 016a 0266  ..s....|.j.j.j.f
 00002520: 007c 017c 0264 019c 027c 0397 028e 0153  .|.|.d...|.....S
 00002530: 0029 0261 9902 0000 4465 6c65 7465 2061  .).a....Delete a
@@ -636,15 +636,15 @@
 000027b0: 7469 6f6e 732e 4874 7470 5265 7370 6f6e  tions.HttpRespon
 000027c0: 7365 4572 726f 723a 0a20 2020 2020 2020  seError:.       
 000027d0: 2072 2700 0000 2903 720c 0000 0072 1e00   r'...).r....r..
 000027e0: 0000 da2a 6163 7469 6f6e 735f 7461 736b  ...*actions_task
 000027f0: 5f64 656c 6574 655f 656c 656d 656e 745f  _delete_element_
 00002800: 7661 6c75 655f 646f 6375 6d65 6e74 7229  value_documentr)
 00002810: 0000 0072 0e00 0000 720e 0000 0072 0f00  ...r....r....r..
-00002820: 0000 7237 0000 00fb 0000 0073 0200 0000  ..r7.......s....
+00002820: 0000 7237 0000 00fa 0000 0073 0200 0000  ..r7.......s....
 00002830: 0012 7a39 5461 736b 4f70 6572 6174 696f  ..z9TaskOperatio
 00002840: 6e73 2e61 6374 696f 6e73 5f74 6173 6b5f  ns.actions_task_
 00002850: 6465 6c65 7465 5f65 6c65 6d65 6e74 5f76  delete_element_v
 00002860: 616c 7565 5f64 6f63 756d 656e 7429 0472  alue_document).r
 00002870: 2200 0000 da0b 646f 6375 6d65 6e74 5f69  ".....document_i
 00002880: 6472 1800 0000 7219 0000 0063 0300 0000  dr....r....c....
 00002890: 0000 0000 0000 0000 0400 0000 0500 0000  ................
@@ -679,15 +679,15 @@
 00002a60: 2029 0272 2200 0000 7238 0000 0029 0372   ).r"...r8...).r
 00002a70: 0c00 0000 721e 0000 00da 2c61 6374 696f  ....r.....,actio
 00002a80: 6e73 5f74 6173 6b5f 646f 776e 6c6f 6164  ns_task_download
 00002a90: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f64  _element_value_d
 00002aa0: 6f63 756d 656e 7429 0472 0d00 0000 7222  ocument).r....r"
 00002ab0: 0000 0072 3800 0000 7218 0000 0072 0e00  ...r8...r....r..
 00002ac0: 0000 720e 0000 0072 0f00 0000 7239 0000  ..r....r....r9..
-00002ad0: 000f 0100 0073 0c00 0000 000d 0a01 0200  .....s..........
+00002ad0: 000e 0100 0073 0c00 0000 000d 0a01 0200  .....s..........
 00002ae0: 02ff 0401 02ff 7a3b 5461 736b 4f70 6572  ......z;TaskOper
 00002af0: 6174 696f 6e73 2e61 6374 696f 6e73 5f74  ations.actions_t
 00002b00: 6173 6b5f 646f 776e 6c6f 6164 5f65 6c65  ask_download_ele
 00002b10: 6d65 6e74 5f76 616c 7565 5f64 6f63 756d  ment_value_docum
 00002b20: 656e 7429 0472 2200 0000 722e 0000 0072  ent).r"...r....r
 00002b30: 1800 0000 7219 0000 0063 0300 0000 0000  ....r....c......
 00002b40: 0000 0000 0000 0400 0000 0500 0000 4b00  ..............K.
@@ -738,15 +738,15 @@
 00002e10: 7272 6f72 3a0a 2020 2020 2020 2020 2902  rror:.        ).
 00002e20: 7222 0000 0072 2e00 0000 2903 720c 0000  r"...r....).r...
 00002e30: 0072 1e00 0000 da2c 6163 7469 6f6e 735f  .r.....,actions_
 00002e40: 7461 736b 5f64 6f77 6e6c 6f61 645f 656c  task_download_el
 00002e50: 656d 656e 745f 7661 6c75 655f 7265 6e64  ement_value_rend
 00002e60: 6572 6564 2904 720d 0000 0072 2200 0000  ered).r....r"...
 00002e70: 722e 0000 0072 1800 0000 720e 0000 0072  r....r....r....r
-00002e80: 0e00 0000 720f 0000 0072 3a00 0000 2001  ....r....r:... .
+00002e80: 0e00 0000 720f 0000 0072 3a00 0000 1f01  ....r....r:.....
 00002e90: 0000 730c 0000 0000 120a 0102 0002 ff04  ..s.............
 00002ea0: 0102 ff7a 3b54 6173 6b4f 7065 7261 7469  ...z;TaskOperati
 00002eb0: 6f6e 732e 6163 7469 6f6e 735f 7461 736b  ons.actions_task
 00002ec0: 5f64 6f77 6e6c 6f61 645f 656c 656d 656e  _download_elemen
 00002ed0: 745f 7661 6c75 655f 7265 6e64 6572 6564  t_value_rendered
 00002ee0: 6303 0000 0000 0000 0000 0000 0004 0000  c...............
 00002ef0: 0005 0000 004b 0000 0073 1a00 0000 7c00  .....K...s....|.
@@ -785,15 +785,15 @@
 00003100: 2e63 6f72 652e 6578 6365 7074 696f 6e73  .core.exceptions
 00003110: 2e48 7474 7052 6573 706f 6e73 6545 7272  .HttpResponseErr
 00003120: 6f72 3a0a 2020 2020 2020 2020 7227 0000  or:.        r'..
 00003130: 0029 0372 0c00 0000 721e 0000 00da 2761  .).r....r.....'a
 00003140: 6374 696f 6e73 5f74 6173 6b5f 7361 7665  ctions_task_save
 00003150: 5f6a 736f 6e5f 666f 726d 735f 7661 6c75  _json_forms_valu
 00003160: 655f 6461 7461 7229 0000 0072 0e00 0000  e_datar)...r....
-00003170: 720e 0000 0072 0f00 0000 723b 0000 0036  r....r....r;...6
+00003170: 720e 0000 0072 0f00 0000 723b 0000 0035  r....r....r;...5
 00003180: 0100 0073 0200 0000 0014 7a36 5461 736b  ...s......z6Task
 00003190: 4f70 6572 6174 696f 6e73 2e61 6374 696f  Operations.actio
 000031a0: 6e73 5f74 6173 6b5f 7361 7665 5f6a 736f  ns_task_save_jso
 000031b0: 6e5f 666f 726d 735f 7661 6c75 655f 6461  n_forms_value_da
 000031c0: 7461 6304 0000 0000 0000 0000 0000 0005  tac.............
 000031d0: 0000 0008 0000 004b 0000 0073 2800 0000  .......K...s(...
 000031e0: 7c00 6a00 6a01 6a02 6600 7c01 7c02 6a03  |.j.j.j.f.|.|.j.
@@ -842,15 +842,15 @@
 00003490: 0072 2d00 0000 da0b 7363 6865 6d61 5f70  .r-.....schema_p
 000034a0: 6174 6829 0772 0c00 0000 721e 0000 00da  ath).r....r.....
 000034b0: 2b61 6374 696f 6e73 5f74 6173 6b5f 7361  +actions_task_sa
 000034c0: 7665 5f6a 736f 6e5f 666f 726d 735f 7661  ve_json_forms_va
 000034d0: 6c75 655f 646f 6375 6d65 6e74 7232 0000  lue_documentr2..
 000034e0: 0072 3300 0000 7234 0000 0072 3c00 0000  .r3...r4...r<...
 000034f0: 7235 0000 0072 0e00 0000 720e 0000 0072  r5...r....r....r
-00003500: 0f00 0000 723d 0000 004c 0100 0073 1200  ....r=...L...s..
+00003500: 0f00 0000 723d 0000 004b 0100 0073 1200  ....r=...K...s..
 00003510: 0000 0015 0a01 0201 0401 0401 0401 04fb  ................
 00003520: 0406 02fa 7a3a 5461 736b 4f70 6572 6174  ....z:TaskOperat
 00003530: 696f 6e73 2e61 6374 696f 6e73 5f74 6173  ions.actions_tas
 00003540: 6b5f 7361 7665 5f6a 736f 6e5f 666f 726d  k_save_json_form
 00003550: 735f 7661 6c75 655f 646f 6375 6d65 6e74  s_value_document
 00003560: 2904 7222 0000 00da 0c64 6f63 756d 656e  ).r".....documen
 00003570: 745f 7572 6972 1800 0000 7219 0000 0063  t_urir....r....c
@@ -885,15 +885,15 @@
 00003740: 723a 0a20 2020 2020 2020 2029 0272 2200  r:.        ).r".
 00003750: 0000 723e 0000 0029 0372 0c00 0000 721e  ..r>...).r....r.
 00003760: 0000 00da 2f61 6374 696f 6e73 5f74 6173  ..../actions_tas
 00003770: 6b5f 646f 776e 6c6f 6164 5f6a 736f 6e5f  k_download_json_
 00003780: 666f 726d 735f 7661 6c75 655f 646f 6375  forms_value_docu
 00003790: 6d65 6e74 2904 720d 0000 0072 2200 0000  ment).r....r"...
 000037a0: 723e 0000 0072 1800 0000 720e 0000 0072  r>...r....r....r
-000037b0: 0e00 0000 720f 0000 0072 3f00 0000 6a01  ....r....r?...j.
+000037b0: 0e00 0000 720f 0000 0072 3f00 0000 6901  ....r....r?...i.
 000037c0: 0000 730c 0000 0000 0f0a 0102 0102 fe04  ..s.............
 000037d0: 0302 fd7a 3e54 6173 6b4f 7065 7261 7469  ...z>TaskOperati
 000037e0: 6f6e 732e 6163 7469 6f6e 735f 7461 736b  ons.actions_task
 000037f0: 5f64 6f77 6e6c 6f61 645f 6a73 6f6e 5f66  _download_json_f
 00003800: 6f72 6d73 5f76 616c 7565 5f64 6f63 756d  orms_value_docum
 00003810: 656e 7463 0200 0000 0000 0000 0000 0000  entc............
 00003820: 0300 0000 0400 0000 4b00 0000 7318 0000  ........K...s...
@@ -916,15 +916,15 @@
 00003930: 207e 617a 7572 652e 636f 7265 2e65 7863   ~azure.core.exc
 00003940: 6570 7469 6f6e 732e 4874 7470 5265 7370  eptions.HttpResp
 00003950: 6f6e 7365 4572 726f 723a 0a20 2020 2020  onseError:.     
 00003960: 2020 2072 2200 0000 2903 720c 0000 0072     r"...).r....r
 00003970: 1e00 0000 da15 6163 7469 6f6e 735f 7461  ......actions_ta
 00003980: 736b 5f63 6f6d 706c 6574 6572 2400 0000  sk_completer$...
 00003990: 720e 0000 0072 0e00 0000 720f 0000 0072  r....r....r....r
-000039a0: 4000 0000 7f01 0000 7302 0000 0000 0b7a  @.......s......z
+000039a0: 4000 0000 7e01 0000 7302 0000 0000 0b7a  @...~...s......z
 000039b0: 2454 6173 6b4f 7065 7261 7469 6f6e 732e  $TaskOperations.
 000039c0: 6163 7469 6f6e 735f 7461 736b 5f63 6f6d  actions_task_com
 000039d0: 706c 6574 6529 0472 2200 0000 da03 6c6f  plete).r".....lo
 000039e0: 6772 1800 0000 7219 0000 0063 0300 0000  gr....r....c....
 000039f0: 0000 0000 0000 0000 0400 0000 0500 0000  ................
 00003a00: 4b00 0000 731a 0000 007c 006a 006a 016a  K...s....|.j.j.j
 00003a10: 0266 007c 017c 0264 019c 027c 0397 028e  .f.|.|.d...|....
@@ -957,15 +957,15 @@
 00003bc0: 6570 7469 6f6e 732e 4874 7470 5265 7370  eptions.HttpResp
 00003bd0: 6f6e 7365 4572 726f 723a 0a20 2020 2020  onseError:.     
 00003be0: 2020 2029 0272 2200 0000 7241 0000 0029     ).r"...rA...)
 00003bf0: 0372 0c00 0000 721e 0000 00da 1761 6374  .r....r......act
 00003c00: 696f 6e73 5f74 6173 6b5f 6170 7065 6e64  ions_task_append
 00003c10: 5f6c 6f67 2904 720d 0000 0072 2200 0000  _log).r....r"...
 00003c20: 7241 0000 0072 1800 0000 720e 0000 0072  rA...r....r....r
-00003c30: 0e00 0000 720f 0000 0072 4200 0000 8c01  ....r....rB.....
+00003c30: 0e00 0000 720f 0000 0072 4200 0000 8b01  ....r....rB.....
 00003c40: 0000 7302 0000 0000 0e7a 2654 6173 6b4f  ..s......z&TaskO
 00003c50: 7065 7261 7469 6f6e 732e 6163 7469 6f6e  perations.action
 00003c60: 735f 7461 736b 5f61 7070 656e 645f 6c6f  s_task_append_lo
 00003c70: 6729 0672 1100 0000 7201 0000 004e 4e4e  g).r....r....NNN
 00003c80: 4e29 014e 292c da08 5f5f 6e61 6d65 5f5f  N).N),..__name__
 00003c90: da0a 5f5f 6d6f 6475 6c65 5f5f da0c 5f5f  ..__module__..__
 00003ca0: 7175 616c 6e61 6d65 5f5f da07 5f5f 646f  qualname__..__do
@@ -996,24 +996,24 @@
 00003e30: 7452 6571 7565 7374 436f 6d6d 616e 64da  tRequestCommand.
 00003e40: 2d54 6173 6b53 6176 654a 736f 6e46 6f72  -TaskSaveJsonFor
 00003e50: 6d73 5661 6c75 6544 6f63 756d 656e 7452  msValueDocumentR
 00003e60: 6573 706f 6e73 6543 6f6d 6d61 6e64 723d  esponseCommandr=
 00003e70: 0000 0072 3f00 0000 7240 0000 00da 034c  ...r?...r@.....L
 00003e80: 6f67 7242 0000 0072 0e00 0000 720e 0000  ogrB...r....r...
 00003e90: 0072 0e00 0000 720f 0000 0072 0a00 0000  .r....r....r....
-00003ea0: 2200 0000 7386 0000 0008 0104 090e 0500  "...s...........
+00003ea0: 2100 0000 7386 0000 0008 0104 090e 0500  !...s...........
 00003eb0: 0100 0100 0100 0100 0100 f902 0202 0102  ................
 00003ec0: 0112 0112 0116 0112 0102 0104 f70c 371e  ..............7.
 00003ed0: 2014 0d14 0d18 1002 0004 0002 0104 fe0c   ...............
 00003ee0: 1a02 0004 0004 0002 0104 fe0c 2102 0004  ............!...
 00003ef0: 0002 0104 fe0c 1402 0004 0002 0104 fe0c  ................
 00003f00: 1418 1202 0002 0002 0106 fe0c 1802 0104  ................
 00003f10: 0102 0104 fb0c 1802 0104 0104 0102 0104  ................
 00003f20: fa0c 1f02 0002 0002 0106 fe0c 1514 0d72  ...............r
 00003f30: 0a00 0000 4e29 0dda 0674 7970 696e 6772  ....N)...typingr
 00003f40: 0200 0000 7203 0000 0072 0400 0000 7205  ....r....r....r.
-00003f50: 0000 0072 0600 0000 da0a 5f67 656e 6572  ...r......_gener
-00003f60: 6174 6564 7208 0000 0072 4700 0000 da00  atedr....rG.....
-00003f70: 7209 0000 0072 1c00 0000 720a 0000 0072  r....r....r....r
+00003f50: 0000 0072 0600 0000 da00 7208 0000 0072  ...r......r....r
+00003f60: 1c00 0000 da0a 5f67 656e 6572 6174 6564  ......_generated
+00003f70: 7209 0000 0072 4700 0000 720a 0000 0072  r....rG...r....r
 00003f80: 0e00 0000 720e 0000 0072 0e00 0000 720f  ....r....r....r.
 00003f90: 0000 00da 083c 6d6f 6475 6c65 3e1b 0000  .....<module>...
-00003fa0: 0073 0600 0000 1c02 0c02 0c03            .s..........
+00003fa0: 0073 0600 0000 1c02 0c01 0c03            .s..........
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/_authentication_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/operations/_authentication_operations.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,15 +22,16 @@
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 
 from typing import Any
 
-from .._generated import models as _models, KuFlowRestClient as KuFlowRestClientGenerated
+from .._generated import KuFlowRestClient as KuFlowRestClientGenerated
+from .._generated import models as _models
 
 
 class AuthenticationOperations:
     """
     .. warning::
         **DO NOT** instantiate this class directly.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/_principal_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/operations/_principal_operations.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,15 +22,16 @@
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 
 from typing import Any, List, Optional, Union
 
-from .._generated import models as _models, KuFlowRestClient as KuFlowRestClientGenerated
+from .._generated import KuFlowRestClient as KuFlowRestClientGenerated
+from .._generated import models as _models
 
 
 class PrincipalOperations:
     """
     .. warning::
         **DO NOT** instantiate this class directly.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/_process_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/operations/_process_operations.py`

 * *Files 0% similar despite different names*

```diff
@@ -21,17 +21,16 @@
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 from typing import Any, List, Optional, Union
 
-from .._generated import KuFlowRestClient as KuFlowRestClientGenerated
-
 from .. import models as _models
+from .._generated import KuFlowRestClient as KuFlowRestClientGenerated
 
 
 class ProcessOperations:
     """
     .. warning::
         **DO NOT** instantiate this class directly.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/operations/_task_operations.py` & `kuflow_rest-0.8.0/kuflow_rest/operations/_task_operations.py`

 * *Files 0% similar despite different names*

```diff
@@ -22,17 +22,16 @@
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 
 from typing import Any, Iterator, List, Optional, Union
 
-from .._generated import KuFlowRestClient as KuFlowRestClientGenerated
-
 from .. import models as _models
+from .._generated import KuFlowRestClient as KuFlowRestClientGenerated
 
 
 class TaskOperations:
     """
     .. warning::
         **DO NOT** instantiate this class directly.
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__init__.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/__init__.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -19,27 +19,27 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from .element_values import (
-    ElementValueSimpleType,
-    ElementValueUnion,
-    ProcessElementValueAccessor,
-    TaskElementValueAccessor,
-)
 from ._process_page_item_utils import ProcessPageItemUtils
 from ._process_save_element_command_utils import ProcessSaveElementCommandUtils
 from ._process_utils import ProcessUtils
 from ._task_page_item_utils import TaskPageItemUtils
 from ._task_save_element_command_utils import TaskSaveElementCommandUtils
 from ._task_save_json_forms_value_data_utils import TaskSaveJsonFormsValueDataCommandUtils
 from ._task_utils import TaskUtils
+from .element_values import (
+    ElementValueSimpleType,
+    ElementValueUnion,
+    ProcessElementValueAccessor,
+    TaskElementValueAccessor,
+)
 
 __all__ = [
     "ElementValueSimpleType",
     "ElementValueUnion",
     "ProcessElementValueAccessor",
     "ProcessPageItemUtils",
     "ProcessSaveElementCommandUtils",
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/__init__.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/__init__.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 2046 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 27% similar despite different names*

```diff
@@ -1,59 +1,59 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 fe07 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 fe07 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 000b 0000 0040 0000 0073 8a00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 6d04 5a04 0100 6400 6402 6c05 6d06 5a06  m.Z...d.d.l.m.Z.
-00000050: 0100 6400 6403 6c07 6d08 5a08 0100 6400  ..d.d.l.m.Z...d.
-00000060: 6404 6c09 6d0a 5a0a 0100 6400 6405 6c0b  d.l.m.Z...d.d.l.
-00000070: 6d0c 5a0c 0100 6400 6406 6c0d 6d0e 5a0e  m.Z...d.d.l.m.Z.
-00000080: 0100 6400 6407 6c0f 6d10 5a10 0100 6400  ..d.d.l.m.Z...d.
-00000090: 6408 6c11 6d12 5a12 0100 6409 640a 640b  d.l.m.Z...d.d.d.
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 0100 6400 6403 6c04 6d05 5a05  m.Z...d.d.l.m.Z.
+00000050: 0100 6400 6404 6c06 6d07 5a07 0100 6400  ..d.d.l.m.Z...d.
+00000060: 6405 6c08 6d09 5a09 0100 6400 6406 6c0a  d.l.m.Z...d.d.l.
+00000070: 6d0b 5a0b 0100 6400 6407 6c0c 6d0d 5a0d  m.Z...d.d.l.m.Z.
+00000080: 0100 6400 6408 6c0e 6d0f 5a0f 6d10 5a10  ..d.d.l.m.Z.m.Z.
+00000090: 6d11 5a11 6d12 5a12 0100 6409 640a 640b  m.Z.m.Z...d.d.d.
 000000a0: 640c 640d 640e 640f 6410 6411 6412 6413  d.d.d.d.d.d.d.d.
 000000b0: 670b 5a13 6414 5300 2915 e901 0000 0029  g.Z.d.S.)......)
-000000c0: 04da 1645 6c65 6d65 6e74 5661 6c75 6553  ...ElementValueS
-000000d0: 696d 706c 6554 7970 65da 1145 6c65 6d65  impleType..Eleme
-000000e0: 6e74 5661 6c75 6555 6e69 6f6e da1b 5072  ntValueUnion..Pr
-000000f0: 6f63 6573 7345 6c65 6d65 6e74 5661 6c75  ocessElementValu
-00000100: 6541 6363 6573 736f 72da 1854 6173 6b45  eAccessor..TaskE
-00000110: 6c65 6d65 6e74 5661 6c75 6541 6363 6573  lementValueAcces
-00000120: 736f 7229 01da 1450 726f 6365 7373 5061  sor)...ProcessPa
-00000130: 6765 4974 656d 5574 696c 7329 01da 1e50  geItemUtils)...P
-00000140: 726f 6365 7373 5361 7665 456c 656d 656e  rocessSaveElemen
-00000150: 7443 6f6d 6d61 6e64 5574 696c 7329 01da  tCommandUtils)..
-00000160: 0c50 726f 6365 7373 5574 696c 7329 01da  .ProcessUtils)..
-00000170: 1154 6173 6b50 6167 6549 7465 6d55 7469  .TaskPageItemUti
-00000180: 6c73 2901 da1b 5461 736b 5361 7665 456c  ls)...TaskSaveEl
-00000190: 656d 656e 7443 6f6d 6d61 6e64 5574 696c  ementCommandUtil
-000001a0: 7329 01da 2654 6173 6b53 6176 654a 736f  s)..&TaskSaveJso
-000001b0: 6e46 6f72 6d73 5661 6c75 6544 6174 6143  nFormsValueDataC
-000001c0: 6f6d 6d61 6e64 5574 696c 7329 01da 0954  ommandUtils)...T
-000001d0: 6173 6b55 7469 6c73 7202 0000 0072 0300  askUtilsr....r..
-000001e0: 0000 7204 0000 0072 0600 0000 7207 0000  ..r....r....r...
-000001f0: 0072 0800 0000 7205 0000 0072 0900 0000  .r....r....r....
-00000200: 720a 0000 0072 0b00 0000 720c 0000 004e  r....r....r....N
-00000210: 2914 da0e 656c 656d 656e 745f 7661 6c75  )...element_valu
-00000220: 6573 7202 0000 0072 0300 0000 7204 0000  esr....r....r...
-00000230: 0072 0500 0000 5a18 5f70 726f 6365 7373  .r....Z._process
-00000240: 5f70 6167 655f 6974 656d 5f75 7469 6c73  _page_item_utils
-00000250: 7206 0000 005a 235f 7072 6f63 6573 735f  r....Z#_process_
-00000260: 7361 7665 5f65 6c65 6d65 6e74 5f63 6f6d  save_element_com
-00000270: 6d61 6e64 5f75 7469 6c73 7207 0000 005a  mand_utilsr....Z
-00000280: 0e5f 7072 6f63 6573 735f 7574 696c 7372  ._process_utilsr
-00000290: 0800 0000 5a15 5f74 6173 6b5f 7061 6765  ....Z._task_page
-000002a0: 5f69 7465 6d5f 7574 696c 7372 0900 0000  _item_utilsr....
-000002b0: 5a20 5f74 6173 6b5f 7361 7665 5f65 6c65  Z _task_save_ele
-000002c0: 6d65 6e74 5f63 6f6d 6d61 6e64 5f75 7469  ment_command_uti
-000002d0: 6c73 720a 0000 005a 265f 7461 736b 5f73  lsr....Z&_task_s
-000002e0: 6176 655f 6a73 6f6e 5f66 6f72 6d73 5f76  ave_json_forms_v
-000002f0: 616c 7565 5f64 6174 615f 7574 696c 7372  alue_data_utilsr
-00000300: 0b00 0000 5a0b 5f74 6173 6b5f 7574 696c  ....Z._task_util
-00000310: 7372 0c00 0000 da07 5f5f 616c 6c5f 5fa9  sr......__all__.
+000000c0: 01da 1450 726f 6365 7373 5061 6765 4974  ...ProcessPageIt
+000000d0: 656d 5574 696c 7329 01da 1e50 726f 6365  emUtils)...Proce
+000000e0: 7373 5361 7665 456c 656d 656e 7443 6f6d  ssSaveElementCom
+000000f0: 6d61 6e64 5574 696c 7329 01da 0c50 726f  mandUtils)...Pro
+00000100: 6365 7373 5574 696c 7329 01da 1154 6173  cessUtils)...Tas
+00000110: 6b50 6167 6549 7465 6d55 7469 6c73 2901  kPageItemUtils).
+00000120: da1b 5461 736b 5361 7665 456c 656d 656e  ..TaskSaveElemen
+00000130: 7443 6f6d 6d61 6e64 5574 696c 7329 01da  tCommandUtils)..
+00000140: 2654 6173 6b53 6176 654a 736f 6e46 6f72  &TaskSaveJsonFor
+00000150: 6d73 5661 6c75 6544 6174 6143 6f6d 6d61  msValueDataComma
+00000160: 6e64 5574 696c 7329 01da 0954 6173 6b55  ndUtils)...TaskU
+00000170: 7469 6c73 2904 da16 456c 656d 656e 7456  tils)...ElementV
+00000180: 616c 7565 5369 6d70 6c65 5479 7065 da11  alueSimpleType..
+00000190: 456c 656d 656e 7456 616c 7565 556e 696f  ElementValueUnio
+000001a0: 6eda 1b50 726f 6365 7373 456c 656d 656e  n..ProcessElemen
+000001b0: 7456 616c 7565 4163 6365 7373 6f72 da18  tValueAccessor..
+000001c0: 5461 736b 456c 656d 656e 7456 616c 7565  TaskElementValue
+000001d0: 4163 6365 7373 6f72 7209 0000 0072 0a00  Accessorr....r..
+000001e0: 0000 720b 0000 0072 0200 0000 7203 0000  ..r....r....r...
+000001f0: 0072 0400 0000 720c 0000 0072 0500 0000  .r....r....r....
+00000200: 7206 0000 0072 0700 0000 7208 0000 004e  r....r....r....N
+00000210: 2914 5a18 5f70 726f 6365 7373 5f70 6167  ).Z._process_pag
+00000220: 655f 6974 656d 5f75 7469 6c73 7202 0000  e_item_utilsr...
+00000230: 005a 235f 7072 6f63 6573 735f 7361 7665  .Z#_process_save
+00000240: 5f65 6c65 6d65 6e74 5f63 6f6d 6d61 6e64  _element_command
+00000250: 5f75 7469 6c73 7203 0000 005a 0e5f 7072  _utilsr....Z._pr
+00000260: 6f63 6573 735f 7574 696c 7372 0400 0000  ocess_utilsr....
+00000270: 5a15 5f74 6173 6b5f 7061 6765 5f69 7465  Z._task_page_ite
+00000280: 6d5f 7574 696c 7372 0500 0000 5a20 5f74  m_utilsr....Z _t
+00000290: 6173 6b5f 7361 7665 5f65 6c65 6d65 6e74  ask_save_element
+000002a0: 5f63 6f6d 6d61 6e64 5f75 7469 6c73 7206  _command_utilsr.
+000002b0: 0000 005a 265f 7461 736b 5f73 6176 655f  ...Z&_task_save_
+000002c0: 6a73 6f6e 5f66 6f72 6d73 5f76 616c 7565  json_forms_value
+000002d0: 5f64 6174 615f 7574 696c 7372 0700 0000  _data_utilsr....
+000002e0: 5a0b 5f74 6173 6b5f 7574 696c 7372 0800  Z._task_utilsr..
+000002f0: 0000 da0e 656c 656d 656e 745f 7661 6c75  ....element_valu
+00000300: 6573 7209 0000 0072 0a00 0000 720b 0000  esr....r....r...
+00000310: 0072 0c00 0000 da07 5f5f 616c 6c5f 5fa9  .r......__all__.
 00000320: 0072 0f00 0000 720f 0000 00fa 412f 776f  .r....r.....A/wo
 00000330: 726b 2f6b 7566 6c6f 772d 7364 6b2d 7079  rk/kuflow-sdk-py
 00000340: 7468 6f6e 2f6b 7566 6c6f 772d 7265 7374  thon/kuflow-rest
 00000350: 2f6b 7566 6c6f 775f 7265 7374 2f75 7469  /kuflow_rest/uti
 00000360: 6c73 2f5f 5f69 6e69 745f 5f2e 7079 da08  ls/__init__.py..
 00000370: 3c6d 6f64 756c 653e 1a00 0000 7326 0000  <module>....s&..
-00000380: 0018 060c 010c 010c 010c 010c 010c 010c  ................
-00000390: 0302 0102 0102 0102 0102 0102 0102 0102  ................
+00000380: 000c 010c 010c 010c 010c 010c 010c 0118  ................
+00000390: 0802 0102 0102 0102 0102 0102 0102 0102  ................
 000003a0: 0102 0102 0102 f5                        .......
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_process_page_item_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_process_page_item_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 13179 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,59 +1,59 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 7b33 0000  U.......=S.d{3..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 7b33 0000  U..........d{3..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 ae00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6403 6404 6c05  d.l.m.Z...d.d.l.
-00000050: 6d06 5a06 6d07 5a07 6d08 5a08 6d09 5a09  m.Z.m.Z.m.Z.m.Z.
-00000060: 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d12 5a12 6d13 5a13 6d14 5a14 6d15 5a15  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d16 5a16 6d17 5a17 6d18 5a18 6d19 5a19  m.Z.m.Z.m.Z.m.Z.
-000000a0: 0100 6405 6406 6c1a 6d1b 5a1b 0100 6405  ..d.d.l.m.Z...d.
-000000b0: 6407 6c1c 6d1d 5a1d 0100 4700 6408 6409  d.l.m.Z...G.d.d.
-000000c0: 8400 6409 6508 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6403 6404 6c05  m.Z.m.Z...d.d.l.
+00000050: 6d06 5a06 0100 6403 6405 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
+00000060: 0100 6406 6407 6c09 6d0a 5a0a 6d0b 5a0b  ..d.d.l.m.Z.m.Z.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 0100 4700 6408 6409  m.Z.m.Z...G.d.d.
+000000c0: 8400 6409 650c 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
 000000d0: 8400 640b 8302 5a1f 640c 5300 290d e900  ..d...Z.d.S.)...
-000000e0: 0000 0029 02da 044c 6973 74da 084f 7074  ...)...List..Opt
-000000f0: 696f 6e61 6c29 01da 0464 6174 65e9 0100  ional)...date...
-00000100: 0000 2914 da16 456c 656d 656e 7456 616c  ..)...ElementVal
-00000110: 7565 5369 6d70 6c65 5479 7065 da11 456c  ueSimpleType..El
-00000120: 656d 656e 7456 616c 7565 556e 696f 6eda  ementValueUnion.
-00000130: 1b50 726f 6365 7373 456c 656d 656e 7456  .ProcessElementV
-00000140: 616c 7565 4163 6365 7373 6f72 da11 6164  alueAccessor..ad
-00000150: 645f 656c 656d 656e 745f 7661 6c75 65da  d_element_value.
-00000160: 1661 6464 5f65 6c65 6d65 6e74 5f76 616c  .add_element_val
-00000170: 7565 5f6c 6973 74da 1a66 696e 645f 656c  ue_list..find_el
-00000180: 656d 656e 745f 7661 6c75 655f 6173 5f64  ement_value_as_d
-00000190: 6174 65da 1b66 696e 645f 656c 656d 656e  ate..find_elemen
-000001a0: 745f 7661 6c75 655f 6173 5f66 6c6f 6174  t_value_as_float
-000001b0: da19 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
-000001c0: 616c 7565 5f61 735f 7374 72da 1967 6574  alue_as_str..get
-000001d0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
-000001e0: 735f 6461 7465 da1e 6765 745f 656c 656d  s_date..get_elem
-000001f0: 656e 745f 7661 6c75 655f 6173 5f64 6174  ent_value_as_dat
-00000200: 655f 6c69 7374 da1a 6765 745f 656c 656d  e_list..get_elem
-00000210: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
-00000220: 6174 da1f 6765 745f 656c 656d 656e 745f  at..get_element_
-00000230: 7661 6c75 655f 6173 5f66 6c6f 6174 5f6c  value_as_float_l
-00000240: 6973 74da 1867 6574 5f65 6c65 6d65 6e74  ist..get_element
-00000250: 5f76 616c 7565 5f61 735f 7374 72da 1d67  _value_as_str..g
-00000260: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-00000270: 5f61 735f 7374 725f 6c69 7374 da17 6765  _as_str_list..ge
-00000280: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-00000290: 7661 6c69 64da 1a67 6574 5f65 6c65 6d65  valid..get_eleme
-000002a0: 6e74 5f76 616c 7565 5f76 616c 6964 5f61  nt_value_valid_a
-000002b0: 74da 1173 6574 5f65 6c65 6d65 6e74 5f76  t..set_element_v
-000002c0: 616c 7565 da16 7365 745f 656c 656d 656e  alue..set_elemen
-000002d0: 745f 7661 6c75 655f 6c69 7374 da17 7365  t_value_list..se
-000002e0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000002f0: 7661 6c69 64da 1a73 6574 5f65 6c65 6d65  valid..set_eleme
-00000300: 6e74 5f76 616c 7565 5f76 616c 6964 5f61  nt_value_valid_a
-00000310: 74e9 0200 0000 2901 da13 5072 6f63 6573  t.....)...Proces
-00000320: 7345 6c65 6d65 6e74 5661 6c75 6529 01da  sElementValue)..
-00000330: 0f50 726f 6365 7373 5061 6765 4974 656d  .ProcessPageItem
+000000e0: 0000 0029 01da 0464 6174 6529 02da 044c  ...)...date)...L
+000000f0: 6973 74da 084f 7074 696f 6e61 6ce9 0200  ist..Optional...
+00000100: 0000 2901 da13 5072 6f63 6573 7345 6c65  ..)...ProcessEle
+00000110: 6d65 6e74 5661 6c75 6529 01da 0f50 726f  mentValue)...Pro
+00000120: 6365 7373 5061 6765 4974 656d e901 0000  cessPageItem....
+00000130: 0029 14da 1645 6c65 6d65 6e74 5661 6c75  .)...ElementValu
+00000140: 6553 696d 706c 6554 7970 65da 1145 6c65  eSimpleType..Ele
+00000150: 6d65 6e74 5661 6c75 6555 6e69 6f6e da1b  mentValueUnion..
+00000160: 5072 6f63 6573 7345 6c65 6d65 6e74 5661  ProcessElementVa
+00000170: 6c75 6541 6363 6573 736f 72da 1161 6464  lueAccessor..add
+00000180: 5f65 6c65 6d65 6e74 5f76 616c 7565 da16  _element_value..
+00000190: 6164 645f 656c 656d 656e 745f 7661 6c75  add_element_valu
+000001a0: 655f 6c69 7374 da1a 6669 6e64 5f65 6c65  e_list..find_ele
+000001b0: 6d65 6e74 5f76 616c 7565 5f61 735f 6461  ment_value_as_da
+000001c0: 7465 da1b 6669 6e64 5f65 6c65 6d65 6e74  te..find_element
+000001d0: 5f76 616c 7565 5f61 735f 666c 6f61 74da  _value_as_float.
+000001e0: 1966 696e 645f 656c 656d 656e 745f 7661  .find_element_va
+000001f0: 6c75 655f 6173 5f73 7472 da19 6765 745f  lue_as_str..get_
+00000200: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
+00000210: 5f64 6174 65da 1e67 6574 5f65 6c65 6d65  _date..get_eleme
+00000220: 6e74 5f76 616c 7565 5f61 735f 6461 7465  nt_value_as_date
+00000230: 5f6c 6973 74da 1a67 6574 5f65 6c65 6d65  _list..get_eleme
+00000240: 6e74 5f76 616c 7565 5f61 735f 666c 6f61  nt_value_as_floa
+00000250: 74da 1f67 6574 5f65 6c65 6d65 6e74 5f76  t..get_element_v
+00000260: 616c 7565 5f61 735f 666c 6f61 745f 6c69  alue_as_float_li
+00000270: 7374 da18 6765 745f 656c 656d 656e 745f  st..get_element_
+00000280: 7661 6c75 655f 6173 5f73 7472 da1d 6765  value_as_str..ge
+00000290: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+000002a0: 6173 5f73 7472 5f6c 6973 74da 1767 6574  as_str_list..get
+000002b0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+000002c0: 616c 6964 da1a 6765 745f 656c 656d 656e  alid..get_elemen
+000002d0: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
+000002e0: da11 7365 745f 656c 656d 656e 745f 7661  ..set_element_va
+000002f0: 6c75 65da 1673 6574 5f65 6c65 6d65 6e74  lue..set_element
+00000300: 5f76 616c 7565 5f6c 6973 74da 1773 6574  _value_list..set
+00000310: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+00000320: 616c 6964 da1a 7365 745f 656c 656d 656e  alid..set_elemen
+00000330: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
 00000340: 6300 0000 0000 0000 0000 0000 0000 0000  c...............
 00000350: 0003 0000 0040 0000 0073 4000 0000 6500  .....@...s@...e.
 00000360: 5a01 6400 5a02 6503 6504 6401 9c02 6402  Z.d.Z.e.e.d...d.
 00000370: 6403 8404 5a05 6506 6507 1900 6404 9c01  d...Z.e.e...d...
 00000380: 6405 6406 8404 5a08 6506 6509 1900 6407  d.d...Z.e.e...d.
 00000390: 9c01 6408 6409 8404 5a0a 640a 5300 290b  ..d.d...Z.d.S.).
 000003a0: da1b 4375 7272 656e 7445 6c65 6d65 6e74  ..CurrentElement
@@ -106,17 +106,17 @@
 00000690: 6d65 6e74 5f76 616c 7565 7345 0000 0073  ment_valuesE...s
 000006a0: 0c00 0000 0001 0c01 0402 1001 1401 0402  ................
 000006b0: 7a2e 4375 7272 656e 7445 6c65 6d65 6e74  z.CurrentElement
 000006c0: 5661 6c75 6541 6363 6573 736f 722e 6765  ValueAccessor.ge
 000006d0: 745f 656c 656d 656e 745f 7661 6c75 6573  t_element_values
 000006e0: 4e29 0bda 085f 5f6e 616d 655f 5fda 0a5f  N)...__name__.._
 000006f0: 5f6d 6f64 756c 655f 5fda 0c5f 5f71 7561  _module__..__qua
-00000700: 6c6e 616d 655f 5f72 1c00 0000 da03 7374  lname__r......st
-00000710: 7272 2400 0000 7202 0000 0072 0700 0000  rr$...r....r....
-00000720: 7229 0000 0072 1b00 0000 722c 0000 0072  r)...r....r,...r
+00000700: 6c6e 616d 655f 5f72 0700 0000 da03 7374  lname__r......st
+00000710: 7272 2400 0000 7203 0000 0072 0a00 0000  rr$...r....r....
+00000720: 7229 0000 0072 0600 0000 722c 0000 0072  r)...r....r,...r
 00000730: 2200 0000 7222 0000 0072 2200 0000 7223  "...r"...r"...r#
 00000740: 0000 0072 1d00 0000 3700 0000 7306 0000  ...r....7...s...
 00000750: 0008 0110 0412 0972 1d00 0000 6300 0000  .......r....c...
 00000760: 0000 0000 0000 0000 0000 0000 0007 0000  ................
 00000770: 0040 0000 0073 ce01 0000 6500 5a01 6400  .@...s....e.Z.d.
 00000780: 5a02 6503 6504 6505 6506 6401 9c03 6402  Z.e.e.e.e.d...d.
 00000790: 6403 8404 8301 5a07 6503 6504 6505 6508  d.....Z.e.e.e.e.
@@ -166,17 +166,17 @@
 00000a50: 4465 6669 6e69 7469 6f6e 2043 6f64 652e  Definition Code.
 00000a60: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 00000a70: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 00000a80: 7275 6520 6966 2061 6c6c 2072 656c 6174  rue if all relat
 00000a90: 6564 2076 616c 6964 2076 616c 7565 7320  ed valid values 
 00000aa0: 6172 6520 5452 5545 2c20 6f74 6865 7277  are TRUE, otherw
 00000ab0: 6973 6520 4661 6c73 652e 0a20 2020 2020  ise False..     
-00000ac0: 2020 2029 0272 1400 0000 721d 0000 0072     ).r....r....r
+00000ac0: 2020 2029 0272 1700 0000 721d 0000 0072     ).r....r....r
 00000ad0: 1e00 0000 7222 0000 0072 2200 0000 7223  ....r"...r"...r#
-00000ae0: 0000 0072 1400 0000 5100 0000 7302 0000  ...r....Q...s...
+00000ae0: 0000 0072 1700 0000 5100 0000 7302 0000  ...r....Q...s...
 00000af0: 0000 0c7a 2c50 726f 6365 7373 5061 6765  ...z,ProcessPage
 00000b00: 4974 656d 5574 696c 732e 6765 745f 656c  ItemUtils.get_el
 00000b10: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
 00000b20: 6429 0472 1f00 0000 7220 0000 00da 0569  d).r....r .....i
 00000b30: 6e64 6578 722a 0000 0063 0300 0000 0000  ndexr*...c......
 00000b40: 0000 0000 0000 0300 0000 0400 0000 4300  ..............C.
 00000b50: 0000 7310 0000 0074 0074 017c 007c 0183  ..s....t.t.|.|..
@@ -198,18 +198,18 @@
 00000c50: 6465 783a 2054 6865 2065 6c65 6d65 6e74  dex: The element
 00000c60: 2076 616c 7565 2069 6e64 6578 2e0a 0a20   value index... 
 00000c70: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 00000c80: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 00000c90: 7265 7175 6573 7465 6420 7661 6c69 6420  requested valid 
 00000ca0: 7661 6c75 6520 6966 2069 7420 6578 6973  value if it exis
 00000cb0: 7473 2c20 6f74 6865 7277 6973 6520 4e6f  ts, otherwise No
-00000cc0: 6e65 2e0a 2020 2020 2020 2020 2902 7215  ne..        ).r.
+00000cc0: 6e65 2e0a 2020 2020 2020 2020 2902 7218  ne..        ).r.
 00000cd0: 0000 0072 1d00 0000 2903 721f 0000 0072  ...r....).r....r
 00000ce0: 2000 0000 7232 0000 0072 2200 0000 7222   ...r2...r"...r"
-00000cf0: 0000 0072 2300 0000 7215 0000 005f 0000  ...r#...r...._..
+00000cf0: 0000 0072 2300 0000 7218 0000 005f 0000  ...r#...r...._..
 00000d00: 0073 0800 0000 0011 0201 0800 02ff 7a2f  .s............z/
 00000d10: 5072 6f63 6573 7350 6167 6549 7465 6d55  ProcessPageItemU
 00000d20: 7469 6c73 2e67 6574 5f65 6c65 6d65 6e74  tils.get_element
 00000d30: 5f76 616c 7565 5f76 616c 6964 5f61 7429  _value_valid_at)
 00000d40: 0472 1f00 0000 7220 0000 00da 0576 616c  .r....r .....val
 00000d50: 6964 722a 0000 0063 0300 0000 0000 0000  idr*...c........
 00000d60: 0000 0000 0300 0000 0400 0000 4300 0000  ............C...
@@ -229,18 +229,18 @@
 00000e40: 6465 6669 6e69 7469 6f6e 2063 6f64 652e  definition code.
 00000e50: 0a20 2020 2020 2020 2020 2020 2076 616c  .            val
 00000e60: 6964 3a20 5468 6520 7661 6c69 6420 7661  id: The valid va
 00000e70: 6c75 652e 0a0a 2020 2020 2020 2020 5265  lue...        Re
 00000e80: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00000e90: 2020 2054 6865 2070 6173 7365 6420 7072     The passed pr
 00000ea0: 6f63 6573 735f 7061 6765 5f69 7465 6d2e  ocess_page_item.
-00000eb0: 0a20 2020 2020 2020 2029 0272 1800 0000  .        ).r....
+00000eb0: 0a20 2020 2020 2020 2029 0272 1b00 0000  .        ).r....
 00000ec0: 721d 0000 0029 0372 1f00 0000 7220 0000  r....).r....r ..
 00000ed0: 0072 3300 0000 7222 0000 0072 2200 0000  .r3...r"...r"...
-00000ee0: 7223 0000 0072 1800 0000 7400 0000 7304  r#...r....t...s.
+00000ee0: 7223 0000 0072 1b00 0000 7400 0000 7304  r#...r....t...s.
 00000ef0: 0000 0000 0f10 027a 2c50 726f 6365 7373  .......z,Process
 00000f00: 5061 6765 4974 656d 5574 696c 732e 7365  PageItemUtils.se
 00000f10: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
 00000f20: 7661 6c69 6429 0572 1f00 0000 7220 0000  valid).r....r ..
 00000f30: 0072 3300 0000 7232 0000 0072 2a00 0000  .r3...r2...r*...
 00000f40: 6304 0000 0000 0000 0000 0000 0004 0000  c...............
 00000f50: 0004 0000 0043 0000 0073 1600 0000 7400  .....C...s....t.
@@ -263,18 +263,18 @@
 00001060: 2076 616c 7565 2e0a 2020 2020 2020 2020   value..        
 00001070: 2020 2020 696e 6465 783a 2054 6865 2065      index: The e
 00001080: 6c65 6d65 6e74 2076 616c 7565 2069 6e64  lement value ind
 00001090: 6578 2e0a 0a20 2020 2020 2020 2052 6574  ex...        Ret
 000010a0: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 000010b0: 2020 5468 6520 7061 7373 6564 2070 726f    The passed pro
 000010c0: 6365 7373 5f70 6167 655f 6974 656d 2e0a  cess_page_item..
-000010d0: 2020 2020 2020 2020 2902 7219 0000 0072          ).r....r
+000010d0: 2020 2020 2020 2020 2902 721c 0000 0072          ).r....r
 000010e0: 1d00 0000 2904 721f 0000 0072 2000 0000  ....).r....r ...
 000010f0: 7233 0000 0072 3200 0000 7222 0000 0072  r3...r2...r"...r
-00001100: 2200 0000 7223 0000 0072 1900 0000 8700  "...r#...r......
+00001100: 2200 0000 7223 0000 0072 1c00 0000 8700  "...r#...r......
 00001110: 0000 730c 0000 0000 1002 0108 0002 0002  ..s.............
 00001120: ff04 047a 2f50 726f 6365 7373 5061 6765  ...z/ProcessPage
 00001130: 4974 656d 5574 696c 732e 7365 745f 656c  ItemUtils.set_el
 00001140: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
 00001150: 645f 6174 4e29 0472 1f00 0000 7220 0000  d_atN).r....r ..
 00001160: 00da 0d65 6c65 6d65 6e74 5f76 616c 7565  ...element_value
 00001170: 722a 0000 0063 0300 0000 0000 0000 0000  r*...c..........
@@ -298,17 +298,17 @@
 00001290: 6c75 6520 6973 204e 6f6e 652c 2061 6c6c  lue is None, all
 000012a0: 2063 7572 7265 6e74 2076 616c 7565 7320   current values 
 000012b0: 6172 6520 7265 6d6f 7665 642e 0a0a 2020  are removed...  
 000012c0: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 000012d0: 2020 2020 2020 2020 2020 2054 6865 2070             The p
 000012e0: 6173 7365 6420 7072 6f63 6573 735f 7061  assed process_pa
 000012f0: 6765 5f69 7465 6d2e 0a20 2020 2020 2020  ge_item..       
-00001300: 2029 0272 1600 0000 721d 0000 00a9 0372   ).r....r......r
+00001300: 2029 0272 1900 0000 721d 0000 00a9 0372   ).r....r......r
 00001310: 1f00 0000 7220 0000 0072 3400 0000 7222  ....r ...r4...r"
-00001320: 0000 0072 2200 0000 7223 0000 0072 1600  ...r"...r#...r..
+00001320: 0000 0072 2200 0000 7223 0000 0072 1900  ...r"...r#...r..
 00001330: 0000 9d00 0000 7304 0000 0000 1110 027a  ......s........z
 00001340: 2650 726f 6365 7373 5061 6765 4974 656d  &ProcessPageItem
 00001350: 5574 696c 732e 7365 745f 656c 656d 656e  Utils.set_elemen
 00001360: 745f 7661 6c75 6529 0472 1f00 0000 7220  t_value).r....r 
 00001370: 0000 0072 2500 0000 722a 0000 0063 0300  ...r%...r*...c..
 00001380: 0000 0000 0000 0000 0000 0300 0000 0400  ................
 00001390: 0000 4300 0000 7314 0000 0074 0074 017c  ..C...s....t.t.|
@@ -331,18 +331,18 @@
 000014a0: 4e6f 6e65 206f 7220 656d 7074 792c 2061  None or empty, a
 000014b0: 6c6c 2063 7572 7265 6e74 2076 616c 7565  ll current value
 000014c0: 7320 6172 6520 7265 6d6f 7665 642e 0a0a  s are removed...
 000014d0: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 000014e0: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 000014f0: 2070 6173 7365 6420 7072 6f63 6573 735f   passed process_
 00001500: 7061 6765 5f69 7465 6d2e 0a20 2020 2020  page_item..     
-00001510: 2020 2029 0272 1700 0000 721d 0000 00a9     ).r....r.....
+00001510: 2020 2029 0272 1a00 0000 721d 0000 00a9     ).r....r.....
 00001520: 0372 1f00 0000 7220 0000 0072 2500 0000  .r....r ...r%...
 00001530: 7222 0000 0072 2200 0000 7223 0000 0072  r"...r"...r#...r
-00001540: 1700 0000 b200 0000 7304 0000 0000 1110  ........s.......
+00001540: 1a00 0000 b200 0000 7304 0000 0000 1110  ........s.......
 00001550: 027a 2b50 726f 6365 7373 5061 6765 4974  .z+ProcessPageIt
 00001560: 656d 5574 696c 732e 7365 745f 656c 656d  emUtils.set_elem
 00001570: 656e 745f 7661 6c75 655f 6c69 7374 6303  ent_value_listc.
 00001580: 0000 0000 0000 0000 0000 0003 0000 0004  ................
 00001590: 0000 0043 0000 0073 1400 0000 7400 7401  ...C...s....t.t.
 000015a0: 7c00 7c01 8302 7c02 8302 0100 7c00 5300  |.|...|.....|.S.
 000015b0: 2901 6153 0100 000a 2020 2020 2020 2020  ).aS....        
@@ -362,17 +362,17 @@
 00001690: 4966 2074 6865 2076 616c 7565 2069 7320  If the value is 
 000016a0: 4e6f 6e65 2c20 616c 6c20 6375 7272 656e  None, all curren
 000016b0: 7420 7661 6c75 6573 2061 7265 2072 656d  t values are rem
 000016c0: 6f76 6564 2e0a 0a20 2020 2020 2020 2052  oved...        R
 000016d0: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 000016e0: 2020 2020 5468 6520 7061 7373 6564 2070      The passed p
 000016f0: 726f 6365 7373 5f70 6167 655f 6974 656d  rocess_page_item
-00001700: 2e0a 2020 2020 2020 2020 2902 7209 0000  ..        ).r...
+00001700: 2e0a 2020 2020 2020 2020 2902 720c 0000  ..        ).r...
 00001710: 0072 1d00 0000 7235 0000 0072 2200 0000  .r....r5...r"...
-00001720: 7222 0000 0072 2300 0000 7209 0000 00c7  r"...r#...r.....
+00001720: 7222 0000 0072 2300 0000 720c 0000 00c7  r"...r#...r.....
 00001730: 0000 0073 0400 0000 0011 1002 7a26 5072  ...s........z&Pr
 00001740: 6f63 6573 7350 6167 6549 7465 6d55 7469  ocessPageItemUti
 00001750: 6c73 2e61 6464 5f65 6c65 6d65 6e74 5f76  ls.add_element_v
 00001760: 616c 7565 6303 0000 0000 0000 0000 0000  aluec...........
 00001770: 0003 0000 0004 0000 0043 0000 0073 1400  .........C...s..
 00001780: 0000 7400 7401 7c00 7c01 8302 7c02 8302  ..t.t.|.|...|...
 00001790: 0100 7c00 5300 2901 6160 0100 000a 2020  ..|.S.).a`....  
@@ -394,16 +394,16 @@
 00001890: 6d70 7479 2c20 616c 6c20 6375 7272 656e  mpty, all curren
 000018a0: 7420 7661 6c75 6573 2061 7265 2072 656d  t values are rem
 000018b0: 6f76 6564 2e0a 0a20 2020 2020 2020 2052  oved...        R
 000018c0: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 000018d0: 2020 2020 5468 6520 7061 7373 6564 206d      The passed m
 000018e0: 6f64 656c 2072 656c 6174 6564 206f 626a  odel related obj
 000018f0: 6563 742e 0a20 2020 2020 2020 2029 0272  ect..        ).r
-00001900: 0a00 0000 721d 0000 0072 3600 0000 7222  ....r....r6...r"
-00001910: 0000 0072 2200 0000 7223 0000 0072 0a00  ...r"...r#...r..
+00001900: 0d00 0000 721d 0000 0072 3600 0000 7222  ....r....r6...r"
+00001910: 0000 0072 2200 0000 7223 0000 0072 0d00  ...r"...r#...r..
 00001920: 0000 dc00 0000 7304 0000 0000 1110 027a  ......s........z
 00001930: 2b50 726f 6365 7373 5061 6765 4974 656d  +ProcessPageItem
 00001940: 5574 696c 732e 6164 645f 656c 656d 656e  Utils.add_elemen
 00001950: 745f 7661 6c75 655f 6c69 7374 6302 0000  t_value_listc...
 00001960: 0000 0000 0000 0000 0002 0000 0004 0000  ................
 00001970: 0043 0000 0073 0e00 0000 7400 7401 7c00  .C...s....t.t.|.
 00001980: 7c01 8302 8301 5300 2901 7af0 0a20 2020  |.....S.).z..   
@@ -417,17 +417,17 @@
 00001a00: 2020 2020 656c 656d 656e 745f 6465 6669      element_defi
 00001a10: 6e69 7469 6f6e 5f63 6f64 653a 2054 6865  nition_code: The
 00001a20: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00001a30: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00001a40: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001a50: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00001a60: 656e 7420 7661 6c75 6520 6173 2061 2073  ent value as a s
-00001a70: 7472 2e0a 2020 2020 2020 2020 2902 7212  tr..        ).r.
+00001a70: 7472 2e0a 2020 2020 2020 2020 2902 7215  tr..        ).r.
 00001a80: 0000 0072 1d00 0000 721e 0000 0072 2200  ...r....r....r".
-00001a90: 0000 7222 0000 0072 2300 0000 7212 0000  ..r"...r#...r...
+00001a90: 0000 7222 0000 0072 2300 0000 7215 0000  ..r"...r#...r...
 00001aa0: 00f1 0000 0073 0200 0000 000c 7a2d 5072  .....s......z-Pr
 00001ab0: 6f63 6573 7350 6167 6549 7465 6d55 7469  ocessPageItemUti
 00001ac0: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00001ad0: 616c 7565 5f61 735f 7374 7263 0200 0000  alue_as_strc....
 00001ae0: 0000 0000 0000 0000 0200 0000 0400 0000  ................
 00001af0: 4300 0000 730e 0000 0074 0074 017c 007c  C...s....t.t.|.|
 00001b00: 0183 0283 0153 0029 017a f70a 2020 2020  .....S.).z..    
@@ -442,17 +442,17 @@
 00001b90: 745f 6465 6669 6e69 7469 6f6e 5f63 6f64  t_definition_cod
 00001ba0: 653a 2054 6865 2065 6c65 6d65 6e74 2064  e: The element d
 00001bb0: 6566 696e 6974 696f 6e20 636f 6465 2e0a  efinition code..
 00001bc0: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00001bd0: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00001be0: 6520 656c 656d 656e 7420 7661 6c75 6520  e element value 
 00001bf0: 6173 2061 2073 7472 2e0a 2020 2020 2020  as a str..      
-00001c00: 2020 2902 720d 0000 0072 1d00 0000 721e    ).r....r....r.
+00001c00: 2020 2902 7210 0000 0072 1d00 0000 721e    ).r....r....r.
 00001c10: 0000 0072 2200 0000 7222 0000 0072 2300  ...r"...r"...r#.
-00001c20: 0000 720d 0000 00ff 0000 0073 0200 0000  ..r........s....
+00001c20: 0000 7210 0000 00ff 0000 0073 0200 0000  ..r........s....
 00001c30: 000c 7a2e 5072 6f63 6573 7350 6167 6549  ..z.ProcessPageI
 00001c40: 7465 6d55 7469 6c73 2e66 696e 645f 656c  temUtils.find_el
 00001c50: 656d 656e 745f 7661 6c75 655f 6173 5f73  ement_value_as_s
 00001c60: 7472 6302 0000 0000 0000 0000 0000 0002  trc.............
 00001c70: 0000 0004 0000 0043 0000 0073 0e00 0000  .......C...s....
 00001c80: 7400 7401 7c00 7c01 8302 8301 5300 2901  t.t.|.|.....S.).
 00001c90: 6102 0100 000a 2020 2020 2020 2020 5472  a.....        Tr
@@ -467,17 +467,17 @@
 00001d20: 5f64 6566 696e 6974 696f 6e5f 636f 6465  _definition_code
 00001d30: 3a20 5468 6520 656c 656d 656e 7420 6465  : The element de
 00001d40: 6669 6e69 7469 6f6e 2063 6f64 652e 0a0a  finition code...
 00001d50: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00001d60: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00001d70: 2065 6c65 6d65 6e74 2076 616c 7565 7320   element values 
 00001d80: 6173 2061 2073 7472 206c 6973 742e 0a20  as a str list.. 
-00001d90: 2020 2020 2020 2029 0272 1300 0000 721d         ).r....r.
+00001d90: 2020 2020 2020 2029 0272 1600 0000 721d         ).r....r.
 00001da0: 0000 0072 1e00 0000 7222 0000 0072 2200  ...r....r"...r".
-00001db0: 0000 7223 0000 0072 1300 0000 0d01 0000  ..r#...r........
+00001db0: 0000 7223 0000 0072 1600 0000 0d01 0000  ..r#...r........
 00001dc0: 7302 0000 0000 0c7a 3250 726f 6365 7373  s......z2Process
 00001dd0: 5061 6765 4974 656d 5574 696c 732e 6765  PageItemUtils.ge
 00001de0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
 00001df0: 6173 5f73 7472 5f6c 6973 7463 0200 0000  as_str_listc....
 00001e00: 0000 0000 0000 0000 0200 0000 0400 0000  ................
 00001e10: 4300 0000 730e 0000 0074 0074 017c 007c  C...s....t.t.|.|
 00001e20: 0183 0283 0153 0029 017a f40a 2020 2020  .....S.).z..    
@@ -492,17 +492,17 @@
 00001eb0: 696e 6974 696f 6e5f 636f 6465 3a20 5468  inition_code: Th
 00001ec0: 6520 656c 656d 656e 7420 6465 6669 6e69  e element defini
 00001ed0: 7469 6f6e 2063 6f64 652e 0a0a 2020 2020  tion code...    
 00001ee0: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00001ef0: 2020 2020 2020 2020 2054 6865 2065 6c65           The ele
 00001f00: 6d65 6e74 2076 616c 7565 2061 7320 6120  ment value as a 
 00001f10: 666c 6f61 742e 0a20 2020 2020 2020 2029  float..        )
-00001f20: 0272 1000 0000 721d 0000 0072 1e00 0000  .r....r....r....
+00001f20: 0272 1300 0000 721d 0000 0072 1e00 0000  .r....r....r....
 00001f30: 7222 0000 0072 2200 0000 7223 0000 0072  r"...r"...r#...r
-00001f40: 1000 0000 1b01 0000 7302 0000 0000 0c7a  ........s......z
+00001f40: 1300 0000 1b01 0000 7302 0000 0000 0c7a  ........s......z
 00001f50: 2f50 726f 6365 7373 5061 6765 4974 656d  /ProcessPageItem
 00001f60: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 00001f70: 745f 7661 6c75 655f 6173 5f66 6c6f 6174  t_value_as_float
 00001f80: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 00001f90: 0004 0000 0043 0000 0073 0e00 0000 7400  .....C...s....t.
 00001fa0: 7401 7c00 7c01 8302 8301 5300 2901 7afb  t.|.|.....S.).z.
 00001fb0: 0a20 2020 2020 2020 2054 7279 2074 6f20  .        Try to 
@@ -516,17 +516,17 @@
 00002030: 2065 6c65 6d65 6e74 5f64 6566 696e 6974   element_definit
 00002040: 696f 6e5f 636f 6465 3a20 5468 6520 656c  ion_code: The el
 00002050: 656d 656e 7420 6465 6669 6e69 7469 6f6e  ement definition
 00002060: 2063 6f64 652e 0a0a 2020 2020 2020 2020   code...        
 00002070: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00002080: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00002090: 2076 616c 7565 2061 7320 6120 666c 6f61   value as a floa
-000020a0: 742e 0a20 2020 2020 2020 2029 0272 0c00  t..        ).r..
+000020a0: 742e 0a20 2020 2020 2020 2029 0272 0f00  t..        ).r..
 000020b0: 0000 721d 0000 0072 1e00 0000 7222 0000  ..r....r....r"..
-000020c0: 0072 2200 0000 7223 0000 0072 0c00 0000  .r"...r#...r....
+000020c0: 0072 2200 0000 7223 0000 0072 0f00 0000  .r"...r#...r....
 000020d0: 2901 0000 7302 0000 0000 0c7a 3050 726f  )...s......z0Pro
 000020e0: 6365 7373 5061 6765 4974 656d 5574 696c  cessPageItemUtil
 000020f0: 732e 6669 6e64 5f65 6c65 6d65 6e74 5f76  s.find_element_v
 00002100: 616c 7565 5f61 735f 666c 6f61 7463 0200  alue_as_floatc..
 00002110: 0000 0000 0000 0000 0000 0200 0000 0400  ................
 00002120: 0000 4300 0000 730e 0000 0074 0074 017c  ..C...s....t.t.|
 00002130: 007c 0183 0283 0153 0029 017a fb0a 2020  .|.....S.).z..  
@@ -541,17 +541,17 @@
 000021c0: 656d 656e 745f 6465 6669 6e69 7469 6f6e  ement_definition
 000021d0: 5f63 6f64 653a 2054 6865 2065 6c65 6d65  _code: The eleme
 000021e0: 6e74 2064 6566 696e 6974 696f 6e20 636f  nt definition co
 000021f0: 6465 2e0a 0a20 2020 2020 2020 2052 6574  de...        Ret
 00002200: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00002210: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 00002220: 6c75 6520 6173 2061 2066 6c6f 6174 2e0a  lue as a float..
-00002230: 2020 2020 2020 2020 2902 7211 0000 0072          ).r....r
+00002230: 2020 2020 2020 2020 2902 7214 0000 0072          ).r....r
 00002240: 1d00 0000 721e 0000 0072 2200 0000 7222  ....r....r"...r"
-00002250: 0000 0072 2300 0000 7211 0000 0037 0100  ...r#...r....7..
+00002250: 0000 0072 2300 0000 7214 0000 0037 0100  ...r#...r....7..
 00002260: 0073 0200 0000 000e 7a34 5072 6f63 6573  .s......z4Proces
 00002270: 7350 6167 6549 7465 6d55 7469 6c73 2e67  sPageItemUtils.g
 00002280: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 00002290: 5f61 735f 666c 6f61 745f 6c69 7374 6302  _as_float_listc.
 000022a0: 0000 0000 0000 0000 0000 0002 0000 0004  ................
 000022b0: 0000 0043 0000 0073 0e00 0000 7400 7401  ...C...s....t.t.
 000022c0: 7c00 7c01 8302 8301 5300 2901 7af2 0a20  |.|.....S.).z.. 
@@ -566,17 +566,17 @@
 00002350: 6566 696e 6974 696f 6e5f 636f 6465 3a20  efinition_code: 
 00002360: 5468 6520 656c 656d 656e 7420 6465 6669  The element defi
 00002370: 6e69 7469 6f6e 2063 6f64 652e 0a0a 2020  nition code...  
 00002380: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 00002390: 2020 2020 2020 2020 2020 2054 6865 2065             The e
 000023a0: 6c65 6d65 6e74 2076 616c 7565 2061 7320  lement value as 
 000023b0: 6120 6461 7465 2e0a 2020 2020 2020 2020  a date..        
-000023c0: 2902 720e 0000 0072 1d00 0000 721e 0000  ).r....r....r...
+000023c0: 2902 7211 0000 0072 1d00 0000 721e 0000  ).r....r....r...
 000023d0: 0072 2200 0000 7222 0000 0072 2300 0000  .r"...r"...r#...
-000023e0: 720e 0000 0047 0100 0073 0200 0000 000c  r....G...s......
+000023e0: 7211 0000 0047 0100 0073 0200 0000 000c  r....G...s......
 000023f0: 7a2e 5072 6f63 6573 7350 6167 6549 7465  z.ProcessPageIte
 00002400: 6d55 7469 6c73 2e67 6574 5f65 6c65 6d65  mUtils.get_eleme
 00002410: 6e74 5f76 616c 7565 5f61 735f 6461 7465  nt_value_as_date
 00002420: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 00002430: 0004 0000 0043 0000 0073 0e00 0000 7400  .....C...s....t.
 00002440: 7401 7c00 7c01 8302 8301 5300 2901 7afa  t.|.|.....S.).z.
 00002450: 0a20 2020 2020 2020 2054 7279 2074 6f20  .        Try to 
@@ -590,17 +590,17 @@
 000024d0: 2065 6c65 6d65 6e74 5f64 6566 696e 6974   element_definit
 000024e0: 696f 6e5f 636f 6465 3a20 5468 6520 656c  ion_code: The el
 000024f0: 656d 656e 7420 6465 6669 6e69 7469 6f6e  ement definition
 00002500: 2063 6f64 652e 0a0a 2020 2020 2020 2020   code...        
 00002510: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00002520: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00002530: 2076 616c 7565 2061 7320 6120 6461 7465   value as a date
-00002540: 2e0a 2020 2020 2020 2020 2902 720b 0000  ..        ).r...
+00002540: 2e0a 2020 2020 2020 2020 2902 720e 0000  ..        ).r...
 00002550: 0072 1d00 0000 721e 0000 0072 2200 0000  .r....r....r"...
-00002560: 7222 0000 0072 2300 0000 720b 0000 0055  r"...r#...r....U
+00002560: 7222 0000 0072 2300 0000 720e 0000 0055  r"...r#...r....U
 00002570: 0100 0073 0200 0000 000c 7a2f 5072 6f63  ...s......z/Proc
 00002580: 6573 7350 6167 6549 7465 6d55 7469 6c73  essPageItemUtils
 00002590: 2e66 696e 645f 656c 656d 656e 745f 7661  .find_element_va
 000025a0: 6c75 655f 6173 5f64 6174 6563 0200 0000  lue_as_datec....
 000025b0: 0000 0000 0000 0000 0200 0000 0400 0000  ................
 000025c0: 4300 0000 730e 0000 0074 0074 017c 007c  C...s....t.t.|.|
 000025d0: 0183 0283 0153 0029 017a f70a 2020 2020  .....S.).z..    
@@ -615,52 +615,52 @@
 00002660: 5f64 6566 696e 6974 696f 6e5f 636f 6465  _definition_code
 00002670: 3a20 5468 6520 656c 656d 656e 7420 6465  : The element de
 00002680: 6669 6e69 7469 6f6e 2063 6f64 652e 0a0a  finition code...
 00002690: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 000026a0: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 000026b0: 2065 6c65 6d65 6e74 2076 616c 7565 2061   element value a
 000026c0: 7320 6120 6461 7465 2e0a 2020 2020 2020  s a date..      
-000026d0: 2020 2902 720f 0000 0072 1d00 0000 721e    ).r....r....r.
+000026d0: 2020 2902 7212 0000 0072 1d00 0000 721e    ).r....r....r.
 000026e0: 0000 0072 2200 0000 7222 0000 0072 2300  ...r"...r"...r#.
-000026f0: 0000 720f 0000 0063 0100 0073 0200 0000  ..r....c...s....
+000026f0: 0000 7212 0000 0063 0100 0073 0200 0000  ..r....c...s....
 00002700: 000c 7a33 5072 6f63 6573 7350 6167 6549  ..z3ProcessPageI
 00002710: 7465 6d55 7469 6c73 2e67 6574 5f65 6c65  temUtils.get_ele
 00002720: 6d65 6e74 5f76 616c 7565 5f61 735f 6461  ment_value_as_da
 00002730: 7465 5f6c 6973 7429 014e 2901 4e29 014e  te_list).N).N).N
 00002740: 2901 4e29 1e72 2d00 0000 722e 0000 0072  ).N).r-...r....r
 00002750: 2f00 0000 da0c 7374 6174 6963 6d65 7468  /.....staticmeth
-00002760: 6f64 721c 0000 0072 3000 0000 da04 626f  odr....r0.....bo
-00002770: 6f6c 7214 0000 00da 0369 6e74 7215 0000  olr......intr...
-00002780: 0072 0300 0000 7218 0000 0072 1900 0000  .r....r....r....
-00002790: 7206 0000 0072 1600 0000 7202 0000 0072  r....r....r....r
-000027a0: 1700 0000 7209 0000 0072 0a00 0000 7212  ....r....r....r.
-000027b0: 0000 0072 0d00 0000 7213 0000 00da 0566  ...r....r......f
-000027c0: 6c6f 6174 7210 0000 0072 0c00 0000 7211  loatr....r....r.
-000027d0: 0000 0072 0400 0000 720e 0000 0072 0b00  ...r....r....r..
-000027e0: 0000 720f 0000 0072 2200 0000 7222 0000  ..r....r"...r"..
+00002760: 6f64 7207 0000 0072 3000 0000 da04 626f  odr....r0.....bo
+00002770: 6f6c 7217 0000 00da 0369 6e74 7218 0000  olr......intr...
+00002780: 0072 0400 0000 721b 0000 0072 1c00 0000  .r....r....r....
+00002790: 7209 0000 0072 1900 0000 7203 0000 0072  r....r....r....r
+000027a0: 1a00 0000 720c 0000 0072 0d00 0000 7215  ....r....r....r.
+000027b0: 0000 0072 1000 0000 7216 0000 00da 0566  ...r....r......f
+000027c0: 6c6f 6174 7213 0000 0072 0f00 0000 7214  loatr....r....r.
+000027d0: 0000 0072 0200 0000 7211 0000 0072 0e00  ...r....r....r..
+000027e0: 0000 7212 0000 0072 2200 0000 7222 0000  ..r....r"...r"..
 000027f0: 0072 2200 0000 7223 0000 0072 3100 0000  .r"...r#...r1...
 00002800: 5000 0000 7394 0000 0008 0102 0114 0d02  P...s...........
 00002810: 0202 0102 0102 0102 fc0e 1402 0202 0002  ................
 00002820: 0006 0102 fe0e 1202 0202 0002 0006 0002  ................
 00002830: 0102 fe0e 1502 0400 fd02 0102 0102 0106  ................
 00002840: 0102 fc0e 1402 0400 fd02 0102 0102 010a  ................
 00002850: 0102 fc0e 1402 0400 fd02 0102 0102 0106  ................
 00002860: 0102 fc0e 1402 0400 fd02 0102 0102 010a  ................
 00002870: 0102 fc0e 1402 0114 0d02 0118 0d02 0118  ................
 00002880: 0d02 0114 0d02 0114 0d02 0202 0002 0106  ................
 00002890: fe0e 0f02 0114 0d02 0118 0d02 0172 3100  .............r1.
-000028a0: 0000 4e29 20da 0674 7970 696e 6772 0200  ..N) ..typingr..
-000028b0: 0000 7203 0000 00da 0864 6174 6574 696d  ..r......datetim
-000028c0: 6572 0400 0000 7225 0000 0072 0600 0000  er....r%...r....
-000028d0: 7207 0000 0072 0800 0000 7209 0000 0072  r....r....r....r
-000028e0: 0a00 0000 720b 0000 0072 0c00 0000 720d  ....r....r....r.
-000028f0: 0000 0072 0e00 0000 720f 0000 0072 1000  ...r....r....r..
-00002900: 0000 7211 0000 0072 1200 0000 7213 0000  ..r....r....r...
-00002910: 0072 1400 0000 7215 0000 0072 1600 0000  .r....r....r....
-00002920: 7217 0000 0072 1800 0000 7219 0000 005a  r....r....r....Z
-00002930: 115f 6765 6e65 7261 7465 642e 6d6f 6465  ._generated.mode
-00002940: 6c73 721b 0000 00da 066d 6f64 656c 7372  lsr......modelsr
+000028a0: 0000 4e29 20da 0864 6174 6574 696d 6572  ..N) ..datetimer
+000028b0: 0200 0000 da06 7479 7069 6e67 7203 0000  ......typingr...
+000028c0: 0072 0400 0000 5a11 5f67 656e 6572 6174  .r....Z._generat
+000028d0: 6564 2e6d 6f64 656c 7372 0600 0000 da06  ed.modelsr......
+000028e0: 6d6f 6465 6c73 7207 0000 0072 2500 0000  modelsr....r%...
+000028f0: 7209 0000 0072 0a00 0000 720b 0000 0072  r....r....r....r
+00002900: 0c00 0000 720d 0000 0072 0e00 0000 720f  ....r....r....r.
+00002910: 0000 0072 1000 0000 7211 0000 0072 1200  ...r....r....r..
+00002920: 0000 7213 0000 0072 1400 0000 7215 0000  ..r....r....r...
+00002930: 0072 1600 0000 7217 0000 0072 1800 0000  .r....r....r....
+00002940: 7219 0000 0072 1a00 0000 721b 0000 0072  r....r....r....r
 00002950: 1c00 0000 721d 0000 0072 3100 0000 7222  ....r....r1...r"
 00002960: 0000 0072 2200 0000 7222 0000 0072 2300  ...r"...r"...r#.
 00002970: 0000 da08 3c6d 6f64 756c 653e 1a00 0000  ....<module>....
-00002980: 730c 0000 0010 010c 0258 160c 010c 0310  s........X......
+00002980: 730c 0000 000c 0110 020c 010c 0158 1810  s............X..
 00002990: 19                                       .
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_process_save_element_command_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_process_save_element_command_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 11649 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 8% similar despite different names*

```diff
@@ -1,60 +1,60 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 812d 0000  U.......=S.d.-..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 812d 0000  U..........d.-..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 ae00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6403 6404 6c05  d.l.m.Z...d.d.l.
-00000050: 6d06 5a06 6d07 5a07 6d08 5a08 6d09 5a09  m.Z.m.Z.m.Z.m.Z.
-00000060: 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d12 5a12 6d13 5a13 6d14 5a14 6d15 5a15  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d16 5a16 6d17 5a17 6d18 5a18 6d19 5a19  m.Z.m.Z.m.Z.m.Z.
-000000a0: 0100 6405 6406 6c1a 6d1b 5a1b 0100 6405  ..d.d.l.m.Z...d.
-000000b0: 6407 6c1c 6d1d 5a1d 0100 4700 6408 6409  d.l.m.Z...G.d.d.
-000000c0: 8400 6409 6508 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6403 6404 6c05  m.Z.m.Z...d.d.l.
+00000050: 6d06 5a06 0100 6403 6405 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
+00000060: 0100 6406 6407 6c09 6d0a 5a0a 6d0b 5a0b  ..d.d.l.m.Z.m.Z.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 0100 4700 6408 6409  m.Z.m.Z...G.d.d.
+000000c0: 8400 6409 650c 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
 000000d0: 8400 640b 8302 5a1f 640c 5300 290d e900  ..d...Z.d.S.)...
-000000e0: 0000 0029 02da 044c 6973 74da 084f 7074  ...)...List..Opt
-000000f0: 696f 6e61 6c29 01da 0464 6174 65e9 0100  ional)...date...
-00000100: 0000 2914 da16 456c 656d 656e 7456 616c  ..)...ElementVal
-00000110: 7565 5369 6d70 6c65 5479 7065 da11 456c  ueSimpleType..El
-00000120: 656d 656e 7456 616c 7565 556e 696f 6eda  ementValueUnion.
-00000130: 1b50 726f 6365 7373 456c 656d 656e 7456  .ProcessElementV
-00000140: 616c 7565 4163 6365 7373 6f72 da11 6164  alueAccessor..ad
-00000150: 645f 656c 656d 656e 745f 7661 6c75 65da  d_element_value.
-00000160: 1661 6464 5f65 6c65 6d65 6e74 5f76 616c  .add_element_val
-00000170: 7565 5f6c 6973 74da 1a66 696e 645f 656c  ue_list..find_el
-00000180: 656d 656e 745f 7661 6c75 655f 6173 5f64  ement_value_as_d
-00000190: 6174 65da 1b66 696e 645f 656c 656d 656e  ate..find_elemen
-000001a0: 745f 7661 6c75 655f 6173 5f66 6c6f 6174  t_value_as_float
-000001b0: da19 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
-000001c0: 616c 7565 5f61 735f 7374 72da 1967 6574  alue_as_str..get
-000001d0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
-000001e0: 735f 6461 7465 da1e 6765 745f 656c 656d  s_date..get_elem
-000001f0: 656e 745f 7661 6c75 655f 6173 5f64 6174  ent_value_as_dat
-00000200: 655f 6c69 7374 da1a 6765 745f 656c 656d  e_list..get_elem
-00000210: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
-00000220: 6174 da1f 6765 745f 656c 656d 656e 745f  at..get_element_
-00000230: 7661 6c75 655f 6173 5f66 6c6f 6174 5f6c  value_as_float_l
-00000240: 6973 74da 1867 6574 5f65 6c65 6d65 6e74  ist..get_element
-00000250: 5f76 616c 7565 5f61 735f 7374 72da 1d67  _value_as_str..g
-00000260: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-00000270: 5f61 735f 7374 725f 6c69 7374 da17 6765  _as_str_list..ge
+000000e0: 0000 0029 01da 0464 6174 6529 02da 044c  ...)...date)...L
+000000f0: 6973 74da 084f 7074 696f 6e61 6ce9 0200  ist..Optional...
+00000100: 0000 2901 da13 5072 6f63 6573 7345 6c65  ..)...ProcessEle
+00000110: 6d65 6e74 5661 6c75 6529 01da 1950 726f  mentValue)...Pro
+00000120: 6365 7373 5361 7665 456c 656d 656e 7443  cessSaveElementC
+00000130: 6f6d 6d61 6e64 e901 0000 0029 14da 1645  ommand.....)...E
+00000140: 6c65 6d65 6e74 5661 6c75 6553 696d 706c  lementValueSimpl
+00000150: 6554 7970 65da 1145 6c65 6d65 6e74 5661  eType..ElementVa
+00000160: 6c75 6555 6e69 6f6e da1b 5072 6f63 6573  lueUnion..Proces
+00000170: 7345 6c65 6d65 6e74 5661 6c75 6541 6363  sElementValueAcc
+00000180: 6573 736f 72da 1161 6464 5f65 6c65 6d65  essor..add_eleme
+00000190: 6e74 5f76 616c 7565 da16 6164 645f 656c  nt_value..add_el
+000001a0: 656d 656e 745f 7661 6c75 655f 6c69 7374  ement_value_list
+000001b0: da1a 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
+000001c0: 616c 7565 5f61 735f 6461 7465 da1b 6669  alue_as_date..fi
+000001d0: 6e64 5f65 6c65 6d65 6e74 5f76 616c 7565  nd_element_value
+000001e0: 5f61 735f 666c 6f61 74da 1966 696e 645f  _as_float..find_
+000001f0: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
+00000200: 5f73 7472 da19 6765 745f 656c 656d 656e  _str..get_elemen
+00000210: 745f 7661 6c75 655f 6173 5f64 6174 65da  t_value_as_date.
+00000220: 1e67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
+00000230: 7565 5f61 735f 6461 7465 5f6c 6973 74da  ue_as_date_list.
+00000240: 1a67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
+00000250: 7565 5f61 735f 666c 6f61 74da 1f67 6574  ue_as_float..get
+00000260: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
+00000270: 735f 666c 6f61 745f 6c69 7374 da18 6765  s_float_list..ge
 00000280: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-00000290: 7661 6c69 64da 1a67 6574 5f65 6c65 6d65  valid..get_eleme
-000002a0: 6e74 5f76 616c 7565 5f76 616c 6964 5f61  nt_value_valid_a
-000002b0: 74da 1173 6574 5f65 6c65 6d65 6e74 5f76  t..set_element_v
-000002c0: 616c 7565 da16 7365 745f 656c 656d 656e  alue..set_elemen
-000002d0: 745f 7661 6c75 655f 6c69 7374 da17 7365  t_value_list..se
-000002e0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000002f0: 7661 6c69 64da 1a73 6574 5f65 6c65 6d65  valid..set_eleme
-00000300: 6e74 5f76 616c 7565 5f76 616c 6964 5f61  nt_value_valid_a
-00000310: 74e9 0200 0000 2901 da13 5072 6f63 6573  t.....)...Proces
-00000320: 7345 6c65 6d65 6e74 5661 6c75 6529 01da  sElementValue)..
-00000330: 1950 726f 6365 7373 5361 7665 456c 656d  .ProcessSaveElem
-00000340: 656e 7443 6f6d 6d61 6e64 6300 0000 0000  entCommandc.....
+00000290: 6173 5f73 7472 da1d 6765 745f 656c 656d  as_str..get_elem
+000002a0: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
+000002b0: 5f6c 6973 74da 1767 6574 5f65 6c65 6d65  _list..get_eleme
+000002c0: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
+000002d0: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
+000002e0: 655f 7661 6c69 645f 6174 da11 7365 745f  e_valid_at..set_
+000002f0: 656c 656d 656e 745f 7661 6c75 65da 1673  element_value..s
+00000300: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000310: 5f6c 6973 74da 1773 6574 5f65 6c65 6d65  _list..set_eleme
+00000320: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
+00000330: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
+00000340: 655f 7661 6c69 645f 6174 6300 0000 0000  e_valid_atc.....
 00000350: 0000 0000 0000 0000 0000 0003 0000 0040  ...............@
 00000360: 0000 0073 3e00 0000 6500 5a01 6400 5a02  ...s>...e.Z.d.Z.
 00000370: 6503 6401 9c01 6402 6403 8404 5a04 6505  e.d...d.d...Z.e.
 00000380: 6506 1900 6404 9c01 6405 6406 8404 5a07  e...d...d.d...Z.
 00000390: 6505 6508 1900 6407 9c01 6408 6409 8404  e.e...d...d.d...
 000003a0: 5a09 640a 5300 290b da1b 4375 7272 656e  Z.d.S.)...Curren
 000003b0: 7445 6c65 6d65 6e74 5661 6c75 6541 6363  tElementValueAcc
@@ -97,17 +97,17 @@
 00000600: 0000 da12 6765 745f 656c 656d 656e 745f  ....get_element_
 00000610: 7661 6c75 6573 4100 0000 7306 0000 0000  valuesA...s.....
 00000620: 010c 0104 027a 2e43 7572 7265 6e74 456c  .....z.CurrentEl
 00000630: 656d 656e 7456 616c 7565 4163 6365 7373  ementValueAccess
 00000640: 6f72 2e67 6574 5f65 6c65 6d65 6e74 5f76  or.get_element_v
 00000650: 616c 7565 734e 290a da08 5f5f 6e61 6d65  aluesN)...__name
 00000660: 5f5f da0a 5f5f 6d6f 6475 6c65 5f5f da0c  __..__module__..
-00000670: 5f5f 7175 616c 6e61 6d65 5f5f 721c 0000  __qualname__r...
-00000680: 0072 2400 0000 7202 0000 0072 0700 0000  .r$...r....r....
-00000690: 7227 0000 0072 1b00 0000 722a 0000 0072  r'...r....r*...r
+00000670: 5f5f 7175 616c 6e61 6d65 5f5f 7207 0000  __qualname__r...
+00000680: 0072 2400 0000 7203 0000 0072 0a00 0000  .r$...r....r....
+00000690: 7227 0000 0072 0600 0000 722a 0000 0072  r'...r....r*...r
 000006a0: 2200 0000 7222 0000 0072 2200 0000 7223  "...r"...r"...r#
 000006b0: 0000 0072 1d00 0000 3700 0000 7306 0000  ...r....7...s...
 000006c0: 0008 010e 0312 0672 1d00 0000 6300 0000  .......r....c...
 000006d0: 0000 0000 0000 0000 0000 0000 0006 0000  ................
 000006e0: 0040 0000 0073 ac01 0000 6500 5a01 6400  .@...s....e.Z.d.
 000006f0: 5a02 6503 6504 6505 6401 9c02 6402 6403  Z.e.e.e.d...d.d.
 00000700: 8404 8301 5a06 6503 6504 6507 6505 6404  ....Z.e.e.e.e.d.
@@ -152,17 +152,17 @@
 00000970: 2073 6176 6520 656c 656d 656e 7420 636f   save element co
 00000980: 6d6d 616e 642e 0a0a 2020 2020 2020 2020  mmand...        
 00000990: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 000009a0: 2020 2020 2054 7275 6520 6966 2061 6c6c       True if all
 000009b0: 2072 656c 6174 6564 2076 616c 6964 2076   related valid v
 000009c0: 616c 7565 7320 6172 6520 5452 5545 2c20  alues are TRUE, 
 000009d0: 6f74 6865 7277 6973 6520 4661 6c73 652e  otherwise False.
-000009e0: 0a20 2020 2020 2020 2029 0272 1400 0000  .        ).r....
+000009e0: 0a20 2020 2020 2020 2029 0272 1700 0000  .        ).r....
 000009f0: 721d 0000 0072 1e00 0000 7222 0000 0072  r....r....r"...r
-00000a00: 2200 0000 7223 0000 0072 1400 0000 4900  "...r#...r....I.
+00000a00: 2200 0000 7223 0000 0072 1700 0000 4900  "...r#...r....I.
 00000a10: 0000 7302 0000 0000 0b7a 3650 726f 6365  ..s......z6Proce
 00000a20: 7373 5361 7665 456c 656d 656e 7443 6f6d  ssSaveElementCom
 00000a30: 6d61 6e64 5574 696c 732e 6765 745f 656c  mandUtils.get_el
 00000a40: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
 00000a50: 6429 0372 1f00 0000 da05 696e 6465 7872  d).r......indexr
 00000a60: 2800 0000 6302 0000 0000 0000 0000 0000  (...c...........
 00000a70: 0002 0000 0003 0000 0043 0000 0073 0e00  .........C...s..
@@ -182,18 +182,18 @@
 00000b50: 3a20 5468 6520 656c 656d 656e 7420 7661  : The element va
 00000b60: 6c75 6520 696e 6465 782e 0a0a 2020 2020  lue index...    
 00000b70: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00000b80: 2020 2020 2020 2020 2054 6865 2072 6571           The req
 00000b90: 7565 7374 6564 2076 616c 6964 2076 616c  uested valid val
 00000ba0: 7565 2069 6620 6974 2065 7869 7374 732c  ue if it exists,
 00000bb0: 206f 7468 6572 7769 7365 204e 6f6e 652e   otherwise None.
-00000bc0: 0a20 2020 2020 2020 2029 0272 1500 0000  .        ).r....
+00000bc0: 0a20 2020 2020 2020 2029 0272 1800 0000  .        ).r....
 00000bd0: 721d 0000 0029 0272 1f00 0000 722f 0000  r....).r....r/..
 00000be0: 0072 2200 0000 7222 0000 0072 2300 0000  .r"...r"...r#...
-00000bf0: 7215 0000 0056 0000 0073 0200 0000 000f  r....V...s......
+00000bf0: 7218 0000 0056 0000 0073 0200 0000 000f  r....V...s......
 00000c00: 7a39 5072 6f63 6573 7353 6176 6545 6c65  z9ProcessSaveEle
 00000c10: 6d65 6e74 436f 6d6d 616e 6455 7469 6c73  mentCommandUtils
 00000c20: 2e67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
 00000c30: 7565 5f76 616c 6964 5f61 7429 0372 1f00  ue_valid_at).r..
 00000c40: 0000 da05 7661 6c69 6472 2800 0000 6302  ....validr(...c.
 00000c50: 0000 0000 0000 0000 0000 0002 0000 0003  ................
 00000c60: 0000 0043 0000 0073 1200 0000 7400 7401  ...C...s....t.t.
@@ -209,17 +209,17 @@
 00000d00: 2073 6176 6520 656c 656d 656e 7420 636f   save element co
 00000d10: 6d6d 616e 642e 0a20 2020 2020 2020 2020  mmand..         
 00000d20: 2020 2076 616c 6964 3a20 5468 6520 7661     valid: The va
 00000d30: 6c69 6420 7661 6c75 652e 0a0a 2020 2020  lid value...    
 00000d40: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00000d50: 2020 2020 2020 2020 2054 6865 2070 6173           The pas
 00000d60: 7365 6420 7072 6f63 6573 732e 0a20 2020  sed process..   
-00000d70: 2020 2020 2029 0272 1800 0000 721d 0000       ).r....r...
+00000d70: 2020 2020 2029 0272 1b00 0000 721d 0000       ).r....r...
 00000d80: 0029 0272 1f00 0000 7230 0000 0072 2200  .).r....r0...r".
-00000d90: 0000 7222 0000 0072 2300 0000 7218 0000  ..r"...r#...r...
+00000d90: 0000 7222 0000 0072 2300 0000 721b 0000  ..r"...r#...r...
 00000da0: 0067 0000 0073 0400 0000 000e 0e02 7a36  .g...s........z6
 00000db0: 5072 6f63 6573 7353 6176 6545 6c65 6d65  ProcessSaveEleme
 00000dc0: 6e74 436f 6d6d 616e 6455 7469 6c73 2e73  ntCommandUtils.s
 00000dd0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 00000de0: 5f76 616c 6964 2904 721f 0000 0072 3000  _valid).r....r0.
 00000df0: 0000 722f 0000 0072 2800 0000 6303 0000  ..r/...r(...c...
 00000e00: 0000 0000 0000 0000 0003 0000 0004 0000  ................
@@ -239,18 +239,18 @@
 00000ee0: 6c69 643a 2054 6865 2076 616c 6964 2076  lid: The valid v
 00000ef0: 616c 7565 2e0a 2020 2020 2020 2020 2020  alue..          
 00000f00: 2020 696e 6465 783a 2054 6865 2065 6c65    index: The ele
 00000f10: 6d65 6e74 2076 616c 7565 2069 6e64 6578  ment value index
 00000f20: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00000f30: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00000f40: 5468 6520 7061 7373 6564 2070 726f 6365  The passed proce
-00000f50: 7373 2e0a 2020 2020 2020 2020 2902 7219  ss..        ).r.
+00000f50: 7373 2e0a 2020 2020 2020 2020 2902 721c  ss..        ).r.
 00000f60: 0000 0072 1d00 0000 2903 721f 0000 0072  ...r....).r....r
 00000f70: 3000 0000 722f 0000 0072 2200 0000 7222  0...r/...r"...r"
-00000f80: 0000 0072 2300 0000 7219 0000 0079 0000  ...r#...r....y..
+00000f80: 0000 0072 2300 0000 721c 0000 0079 0000  ...r#...r....y..
 00000f90: 0073 0400 0000 000f 1002 7a39 5072 6f63  .s........z9Proc
 00000fa0: 6573 7353 6176 6545 6c65 6d65 6e74 436f  essSaveElementCo
 00000fb0: 6d6d 616e 6455 7469 6c73 2e73 6574 5f65  mmandUtils.set_e
 00000fc0: 6c65 6d65 6e74 5f76 616c 7565 5f76 616c  lement_value_val
 00000fd0: 6964 5f61 744e 2903 721f 0000 00da 0d65  id_atN).r......e
 00000fe0: 6c65 6d65 6e74 5f76 616c 7565 7228 0000  lement_valuer(..
 00000ff0: 0063 0200 0000 0000 0000 0000 0000 0200  .c..............
@@ -270,17 +270,17 @@
 000010d0: 6c75 652e 2049 6620 7468 6520 7661 6c75  lue. If the valu
 000010e0: 6520 6973 204e 6f6e 652c 2061 6c6c 2063  e is None, all c
 000010f0: 7572 7265 6e74 2076 616c 7565 7320 6172  urrent values ar
 00001100: 6520 7265 6d6f 7665 642e 0a0a 2020 2020  e removed...    
 00001110: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00001120: 2020 2020 2020 2020 2054 6865 2070 6173           The pas
 00001130: 7365 6420 7072 6f63 6573 732e 0a20 2020  sed process..   
-00001140: 2020 2020 2029 0272 1600 0000 721d 0000       ).r....r...
+00001140: 2020 2020 2029 0272 1900 0000 721d 0000       ).r....r...
 00001150: 00a9 0272 1f00 0000 7231 0000 0072 2200  ...r....r1...r".
-00001160: 0000 7222 0000 0072 2300 0000 7216 0000  ..r"...r#...r...
+00001160: 0000 7222 0000 0072 2300 0000 7219 0000  ..r"...r#...r...
 00001170: 008c 0000 0073 0400 0000 000e 0e02 7a30  .....s........z0
 00001180: 5072 6f63 6573 7353 6176 6545 6c65 6d65  ProcessSaveEleme
 00001190: 6e74 436f 6d6d 616e 6455 7469 6c73 2e73  ntCommandUtils.s
 000011a0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 000011b0: 2903 721f 0000 0072 2500 0000 7228 0000  ).r....r%...r(..
 000011c0: 0063 0200 0000 0000 0000 0000 0000 0200  .c..............
 000011d0: 0000 0300 0000 4300 0000 7312 0000 0074  ......C...s....t
@@ -300,17 +300,17 @@
 000012b0: 7565 2069 7320 4e6f 6e65 206f 7220 656d  ue is None or em
 000012c0: 7074 792c 2061 6c6c 2063 7572 7265 6e74  pty, all current
 000012d0: 2076 616c 7565 7320 6172 6520 7265 6d6f   values are remo
 000012e0: 7665 642e 0a0a 2020 2020 2020 2020 5265  ved...        Re
 000012f0: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00001300: 2020 2054 6865 2070 6173 7365 6420 7072     The passed pr
 00001310: 6f63 6573 732e 0a20 2020 2020 2020 2029  ocess..        )
-00001320: 0272 1700 0000 721d 0000 0072 2900 0000  .r....r....r)...
+00001320: 0272 1a00 0000 721d 0000 0072 2900 0000  .r....r....r)...
 00001330: 7222 0000 0072 2200 0000 7223 0000 0072  r"...r"...r#...r
-00001340: 1700 0000 9e00 0000 7304 0000 0000 0f0e  ........s.......
+00001340: 1a00 0000 9e00 0000 7304 0000 0000 0f0e  ........s.......
 00001350: 027a 3550 726f 6365 7373 5361 7665 456c  .z5ProcessSaveEl
 00001360: 656d 656e 7443 6f6d 6d61 6e64 5574 696c  ementCommandUtil
 00001370: 732e 7365 745f 656c 656d 656e 745f 7661  s.set_element_va
 00001380: 6c75 655f 6c69 7374 6302 0000 0000 0000  lue_listc.......
 00001390: 0000 0000 0002 0000 0003 0000 0043 0000  .............C..
 000013a0: 0073 1200 0000 7400 7401 7c00 8301 7c01  .s....t.t.|...|.
 000013b0: 8302 0100 7c00 5300 2901 611d 0100 000a  ....|.S.).a.....
@@ -327,17 +327,17 @@
 00001460: 6d65 6e74 2076 616c 7565 2e20 4966 2074  ment value. If t
 00001470: 6865 2076 616c 7565 2069 7320 4e6f 6e65  he value is None
 00001480: 2c20 616c 6c20 6375 7272 656e 7420 7661  , all current va
 00001490: 6c75 6573 2061 7265 2072 656d 6f76 6564  lues are removed
 000014a0: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 000014b0: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 000014c0: 5468 6520 7061 7373 6564 2070 726f 6365  The passed proce
-000014d0: 7373 2e0a 2020 2020 2020 2020 2902 7209  ss..        ).r.
+000014d0: 7373 2e0a 2020 2020 2020 2020 2902 720c  ss..        ).r.
 000014e0: 0000 0072 1d00 0000 7232 0000 0072 2200  ...r....r2...r".
-000014f0: 0000 7222 0000 0072 2300 0000 7209 0000  ..r"...r#...r...
+000014f0: 0000 7222 0000 0072 2300 0000 720c 0000  ..r"...r#...r...
 00001500: 00b1 0000 0073 0400 0000 000e 0e02 7a30  .....s........z0
 00001510: 5072 6f63 6573 7353 6176 6545 6c65 6d65  ProcessSaveEleme
 00001520: 6e74 436f 6d6d 616e 6455 7469 6c73 2e61  ntCommandUtils.a
 00001530: 6464 5f65 6c65 6d65 6e74 5f76 616c 7565  dd_element_value
 00001540: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 00001550: 0003 0000 0043 0000 0073 1200 0000 7400  .....C...s....t.
 00001560: 7401 7c00 8301 7c01 8302 0100 7c00 5300  t.|...|.....|.S.
@@ -356,17 +356,17 @@
 00001630: 7320 6973 204e 6f6e 6520 6f72 2065 6d70  s is None or emp
 00001640: 7479 2c20 616c 6c20 6375 7272 656e 7420  ty, all current 
 00001650: 7661 6c75 6573 2061 7265 2072 656d 6f76  values are remov
 00001660: 6564 2e0a 0a20 2020 2020 2020 2052 6574  ed...        Ret
 00001670: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00001680: 2020 5468 6520 7061 7373 6564 206d 6f64    The passed mod
 00001690: 656c 2072 656c 6174 6564 206f 626a 6563  el related objec
-000016a0: 742e 0a20 2020 2020 2020 2029 0272 0a00  t..        ).r..
+000016a0: 742e 0a20 2020 2020 2020 2029 0272 0d00  t..        ).r..
 000016b0: 0000 721d 0000 0072 2900 0000 7222 0000  ..r....r)...r"..
-000016c0: 0072 2200 0000 7223 0000 0072 0a00 0000  .r"...r#...r....
+000016c0: 0072 2200 0000 7223 0000 0072 0d00 0000  .r"...r#...r....
 000016d0: c300 0000 7304 0000 0000 0f0e 027a 3550  ....s........z5P
 000016e0: 726f 6365 7373 5361 7665 456c 656d 656e  rocessSaveElemen
 000016f0: 7443 6f6d 6d61 6e64 5574 696c 732e 6164  tCommandUtils.ad
 00001700: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 00001710: 6c69 7374 6301 0000 0000 0000 0000 0000  listc...........
 00001720: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 00001730: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
@@ -378,17 +378,17 @@
 00001790: 5f65 6c65 6d65 6e74 5f63 6f6d 6d61 6e64  _element_command
 000017a0: 3a20 5468 6520 7072 6f63 6573 7320 7361  : The process sa
 000017b0: 7665 2065 6c65 6d65 6e74 2063 6f6d 6d61  ve element comma
 000017c0: 6e64 2e0a 0a20 2020 2020 2020 2052 6574  nd...        Ret
 000017d0: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 000017e0: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 000017f0: 6c75 6520 6173 2061 2073 7472 2e0a 2020  lue as a str..  
-00001800: 2020 2020 2020 2902 7212 0000 0072 1d00        ).r....r..
+00001800: 2020 2020 2020 2902 7215 0000 0072 1d00        ).r....r..
 00001810: 0000 721e 0000 0072 2200 0000 7222 0000  ..r....r"...r"..
-00001820: 0072 2300 0000 7212 0000 00d6 0000 0073  .r#...r........s
+00001820: 0072 2300 0000 7215 0000 00d6 0000 0073  .r#...r........s
 00001830: 0200 0000 000b 7a37 5072 6f63 6573 7353  ......z7ProcessS
 00001840: 6176 6545 6c65 6d65 6e74 436f 6d6d 616e  aveElementComman
 00001850: 6455 7469 6c73 2e67 6574 5f65 6c65 6d65  dUtils.get_eleme
 00001860: 6e74 5f76 616c 7565 5f61 735f 7374 7263  nt_value_as_strc
 00001870: 0100 0000 0000 0000 0000 0000 0100 0000  ................
 00001880: 0300 0000 4300 0000 730c 0000 0074 0074  ....C...s....t.t
 00001890: 017c 0083 0183 0153 0029 017a cb0a 2020  .|.....S.).z..  
@@ -400,17 +400,17 @@
 000018f0: 7665 5f65 6c65 6d65 6e74 5f63 6f6d 6d61  ve_element_comma
 00001900: 6e64 3a20 5468 6520 7072 6f63 6573 7320  nd: The process 
 00001910: 7361 7665 2065 6c65 6d65 6e74 2063 6f6d  save element com
 00001920: 6d61 6e64 2e0a 0a20 2020 2020 2020 2052  mand...        R
 00001930: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00001940: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00001950: 7661 6c75 6520 6173 2061 2073 7472 2e0a  value as a str..
-00001960: 2020 2020 2020 2020 2902 720d 0000 0072          ).r....r
+00001960: 2020 2020 2020 2020 2902 7210 0000 0072          ).r....r
 00001970: 1d00 0000 721e 0000 0072 2200 0000 7222  ....r....r"...r"
-00001980: 0000 0072 2300 0000 720d 0000 00e3 0000  ...r#...r.......
+00001980: 0000 0072 2300 0000 7210 0000 00e3 0000  ...r#...r.......
 00001990: 0073 0200 0000 000b 7a38 5072 6f63 6573  .s......z8Proces
 000019a0: 7353 6176 6545 6c65 6d65 6e74 436f 6d6d  sSaveElementComm
 000019b0: 616e 6455 7469 6c73 2e66 696e 645f 656c  andUtils.find_el
 000019c0: 656d 656e 745f 7661 6c75 655f 6173 5f73  ement_value_as_s
 000019d0: 7472 6301 0000 0000 0000 0000 0000 0001  trc.............
 000019e0: 0000 0003 0000 0043 0000 0073 0c00 0000  .......C...s....
 000019f0: 7400 7401 7c00 8301 8301 5300 2901 7ad6  t.t.|.....S.).z.
@@ -423,17 +423,17 @@
 00001a60: 6e74 5f63 6f6d 6d61 6e64 3a20 5468 6520  nt_command: The 
 00001a70: 7072 6f63 6573 7320 7361 7665 2065 6c65  process save ele
 00001a80: 6d65 6e74 2063 6f6d 6d61 6e64 2e0a 0a20  ment command... 
 00001a90: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 00001aa0: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 00001ab0: 656c 656d 656e 7420 7661 6c75 6573 2061  element values a
 00001ac0: 7320 6120 7374 7220 6c69 7374 2e0a 2020  s a str list..  
-00001ad0: 2020 2020 2020 2902 7213 0000 0072 1d00        ).r....r..
+00001ad0: 2020 2020 2020 2902 7216 0000 0072 1d00        ).r....r..
 00001ae0: 0000 721e 0000 0072 2200 0000 7222 0000  ..r....r"...r"..
-00001af0: 0072 2300 0000 7213 0000 00f0 0000 0073  .r#...r........s
+00001af0: 0072 2300 0000 7216 0000 00f0 0000 0073  .r#...r........s
 00001b00: 0200 0000 000b 7a3c 5072 6f63 6573 7353  ......z<ProcessS
 00001b10: 6176 6545 6c65 6d65 6e74 436f 6d6d 616e  aveElementComman
 00001b20: 6455 7469 6c73 2e67 6574 5f65 6c65 6d65  dUtils.get_eleme
 00001b30: 6e74 5f76 616c 7565 5f61 735f 7374 725f  nt_value_as_str_
 00001b40: 6c69 7374 6301 0000 0000 0000 0000 0000  listc...........
 00001b50: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 00001b60: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
@@ -445,17 +445,17 @@
 00001bc0: 7665 5f65 6c65 6d65 6e74 5f63 6f6d 6d61  ve_element_comma
 00001bd0: 6e64 3a20 5468 6520 7072 6f63 6573 7320  nd: The process 
 00001be0: 7361 7665 2065 6c65 6d65 6e74 2063 6f6d  save element com
 00001bf0: 6d61 6e64 2e0a 0a20 2020 2020 2020 2052  mand...        R
 00001c00: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00001c10: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00001c20: 7661 6c75 6520 6173 2061 2066 6c6f 6174  value as a float
-00001c30: 2e0a 2020 2020 2020 2020 2902 7210 0000  ..        ).r...
+00001c30: 2e0a 2020 2020 2020 2020 2902 7213 0000  ..        ).r...
 00001c40: 0072 1d00 0000 721e 0000 0072 2200 0000  .r....r....r"...
-00001c50: 7222 0000 0072 2300 0000 7210 0000 00fd  r"...r#...r.....
+00001c50: 7222 0000 0072 2300 0000 7213 0000 00fd  r"...r#...r.....
 00001c60: 0000 0073 0200 0000 000b 7a39 5072 6f63  ...s......z9Proc
 00001c70: 6573 7353 6176 6545 6c65 6d65 6e74 436f  essSaveElementCo
 00001c80: 6d6d 616e 6455 7469 6c73 2e67 6574 5f65  mmandUtils.get_e
 00001c90: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00001ca0: 666c 6f61 7463 0100 0000 0000 0000 0000  floatc..........
 00001cb0: 0000 0100 0000 0300 0000 4300 0000 730c  ..........C...s.
 00001cc0: 0000 0074 0074 017c 0083 0183 0153 0029  ...t.t.|.....S.)
@@ -468,17 +468,17 @@
 00001d30: 6e74 5f63 6f6d 6d61 6e64 3a20 5468 6520  nt_command: The 
 00001d40: 7072 6f63 6573 7320 7361 7665 2065 6c65  process save ele
 00001d50: 6d65 6e74 2063 6f6d 6d61 6e64 2e0a 0a20  ment command... 
 00001d60: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 00001d70: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 00001d80: 656c 656d 656e 7420 7661 6c75 6520 6173  element value as
 00001d90: 2061 2066 6c6f 6174 2e0a 2020 2020 2020   a float..      
-00001da0: 2020 2902 720c 0000 0072 1d00 0000 721e    ).r....r....r.
+00001da0: 2020 2902 720f 0000 0072 1d00 0000 721e    ).r....r....r.
 00001db0: 0000 0072 2200 0000 7222 0000 0072 2300  ...r"...r"...r#.
-00001dc0: 0000 720c 0000 000a 0100 0073 0200 0000  ..r........s....
+00001dc0: 0000 720f 0000 000a 0100 0073 0200 0000  ..r........s....
 00001dd0: 000b 7a3a 5072 6f63 6573 7353 6176 6545  ..z:ProcessSaveE
 00001de0: 6c65 6d65 6e74 436f 6d6d 616e 6455 7469  lementCommandUti
 00001df0: 6c73 2e66 696e 645f 656c 656d 656e 745f  ls.find_element_
 00001e00: 7661 6c75 655f 6173 5f66 6c6f 6174 6301  value_as_floatc.
 00001e10: 0000 0000 0000 0000 0000 0001 0000 0003  ................
 00001e20: 0000 0043 0000 0073 0c00 0000 7400 7401  ...C...s....t.t.
 00001e30: 7c00 8301 8301 5300 2901 7acf 0a20 2020  |.....S.).z..   
@@ -490,17 +490,17 @@
 00001e90: 6176 655f 656c 656d 656e 745f 636f 6d6d  ave_element_comm
 00001ea0: 616e 643a 2054 6865 2070 726f 6365 7373  and: The process
 00001eb0: 2073 6176 6520 656c 656d 656e 7420 636f   save element co
 00001ec0: 6d6d 616e 642e 0a0a 2020 2020 2020 2020  mmand...        
 00001ed0: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00001ee0: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00001ef0: 2076 616c 7565 2061 7320 6120 666c 6f61   value as a floa
-00001f00: 742e 0a20 2020 2020 2020 2029 0272 1100  t..        ).r..
+00001f00: 742e 0a20 2020 2020 2020 2029 0272 1400  t..        ).r..
 00001f10: 0000 721d 0000 0072 1e00 0000 7222 0000  ..r....r....r"..
-00001f20: 0072 2200 0000 7223 0000 0072 1100 0000  .r"...r#...r....
+00001f20: 0072 2200 0000 7223 0000 0072 1400 0000  .r"...r#...r....
 00001f30: 1701 0000 7302 0000 0000 0b7a 3e50 726f  ....s......z>Pro
 00001f40: 6365 7373 5361 7665 456c 656d 656e 7443  cessSaveElementC
 00001f50: 6f6d 6d61 6e64 5574 696c 732e 6765 745f  ommandUtils.get_
 00001f60: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
 00001f70: 5f66 6c6f 6174 5f6c 6973 7463 0100 0000  _float_listc....
 00001f80: 0000 0000 0000 0000 0100 0000 0300 0000  ................
 00001f90: 4300 0000 730c 0000 0074 0074 017c 0083  C...s....t.t.|..
@@ -513,17 +513,17 @@
 00002000: 5f63 6f6d 6d61 6e64 3a20 5468 6520 7072  _command: The pr
 00002010: 6f63 6573 7320 7361 7665 2065 6c65 6d65  ocess save eleme
 00002020: 6e74 2063 6f6d 6d61 6e64 2e0a 0a20 2020  nt command...   
 00002030: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00002040: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00002050: 656d 656e 7420 7661 6c75 6520 6173 2061  ement value as a
 00002060: 2064 6174 652e 0a20 2020 2020 2020 2029   date..        )
-00002070: 0272 0e00 0000 721d 0000 0072 1e00 0000  .r....r....r....
+00002070: 0272 1100 0000 721d 0000 0072 1e00 0000  .r....r....r....
 00002080: 7222 0000 0072 2200 0000 7223 0000 0072  r"...r"...r#...r
-00002090: 0e00 0000 2401 0000 7302 0000 0000 0b7a  ....$...s......z
+00002090: 1100 0000 2401 0000 7302 0000 0000 0b7a  ....$...s......z
 000020a0: 3850 726f 6365 7373 5361 7665 456c 656d  8ProcessSaveElem
 000020b0: 656e 7443 6f6d 6d61 6e64 5574 696c 732e  entCommandUtils.
 000020c0: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 000020d0: 655f 6173 5f64 6174 6563 0100 0000 0000  e_as_datec......
 000020e0: 0000 0000 0000 0100 0000 0300 0000 4300  ..............C.
 000020f0: 0000 730c 0000 0074 0074 017c 0083 0183  ..s....t.t.|....
 00002100: 0153 0029 017a ce0a 2020 2020 2020 2020  .S.).z..        
@@ -535,17 +535,17 @@
 00002160: 6c65 6d65 6e74 5f63 6f6d 6d61 6e64 3a20  lement_command: 
 00002170: 5468 6520 7072 6f63 6573 7320 7361 7665  The process save
 00002180: 2065 6c65 6d65 6e74 2063 6f6d 6d61 6e64   element command
 00002190: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 000021a0: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 000021b0: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 000021c0: 6520 6173 2061 2064 6174 652e 0a20 2020  e as a date..   
-000021d0: 2020 2020 2029 0272 0b00 0000 721d 0000       ).r....r...
+000021d0: 2020 2020 2029 0272 0e00 0000 721d 0000       ).r....r...
 000021e0: 0072 1e00 0000 7222 0000 0072 2200 0000  .r....r"...r"...
-000021f0: 7223 0000 0072 0b00 0000 3101 0000 7302  r#...r....1...s.
+000021f0: 7223 0000 0072 0e00 0000 3101 0000 7302  r#...r....1...s.
 00002200: 0000 0000 0b7a 3950 726f 6365 7373 5361  .....z9ProcessSa
 00002210: 7665 456c 656d 656e 7443 6f6d 6d61 6e64  veElementCommand
 00002220: 5574 696c 732e 6669 6e64 5f65 6c65 6d65  Utils.find_eleme
 00002230: 6e74 5f76 616c 7565 5f61 735f 6461 7465  nt_value_as_date
 00002240: 6301 0000 0000 0000 0000 0000 0001 0000  c...............
 00002250: 0003 0000 0043 0000 0073 0c00 0000 7400  .....C...s....t.
 00002260: 7401 7c00 8301 8301 5300 2901 7acb 0a20  t.|.....S.).z.. 
@@ -557,51 +557,51 @@
 000022c0: 7665 5f65 6c65 6d65 6e74 5f63 6f6d 6d61  ve_element_comma
 000022d0: 6e64 3a20 5468 6520 7072 6f63 6573 7320  nd: The process 
 000022e0: 7361 7665 2065 6c65 6d65 6e74 2063 6f6d  save element com
 000022f0: 6d61 6e64 2e0a 0a20 2020 2020 2020 2052  mand...        R
 00002300: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00002310: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00002320: 7661 6c75 6520 6173 2061 2064 6174 652e  value as a date.
-00002330: 0a20 2020 2020 2020 2029 0272 0f00 0000  .        ).r....
+00002330: 0a20 2020 2020 2020 2029 0272 1200 0000  .        ).r....
 00002340: 721d 0000 0072 1e00 0000 7222 0000 0072  r....r....r"...r
-00002350: 2200 0000 7223 0000 0072 0f00 0000 3e01  "...r#...r....>.
+00002350: 2200 0000 7223 0000 0072 1200 0000 3e01  "...r#...r....>.
 00002360: 0000 7302 0000 0000 0b7a 3d50 726f 6365  ..s......z=Proce
 00002370: 7373 5361 7665 456c 656d 656e 7443 6f6d  ssSaveElementCom
 00002380: 6d61 6e64 5574 696c 732e 6765 745f 656c  mandUtils.get_el
 00002390: 656d 656e 745f 7661 6c75 655f 6173 5f64  ement_value_as_d
 000023a0: 6174 655f 6c69 7374 2901 4e29 014e 2901  ate_list).N).N).
 000023b0: 4e29 014e 291e 722b 0000 0072 2c00 0000  N).N).r+...r,...
 000023c0: 722d 0000 00da 0c73 7461 7469 636d 6574  r-.....staticmet
-000023d0: 686f 6472 1c00 0000 da04 626f 6f6c 7214  hodr......boolr.
-000023e0: 0000 00da 0369 6e74 7215 0000 0072 0300  .....intr....r..
-000023f0: 0000 7218 0000 0072 1900 0000 7206 0000  ..r....r....r...
-00002400: 0072 1600 0000 7202 0000 0072 1700 0000  .r....r....r....
-00002410: 7209 0000 0072 0a00 0000 da03 7374 7272  r....r......strr
-00002420: 1200 0000 720d 0000 0072 1300 0000 da05  ....r....r......
-00002430: 666c 6f61 7472 1000 0000 720c 0000 0072  floatr....r....r
-00002440: 1100 0000 7204 0000 0072 0e00 0000 720b  ....r....r....r.
-00002450: 0000 0072 0f00 0000 7222 0000 0072 2200  ...r....r"...r".
+000023d0: 686f 6472 0700 0000 da04 626f 6f6c 7217  hodr......boolr.
+000023e0: 0000 00da 0369 6e74 7218 0000 0072 0400  .....intr....r..
+000023f0: 0000 721b 0000 0072 1c00 0000 7209 0000  ..r....r....r...
+00002400: 0072 1900 0000 7203 0000 0072 1a00 0000  .r....r....r....
+00002410: 720c 0000 0072 0d00 0000 da03 7374 7272  r....r......strr
+00002420: 1500 0000 7210 0000 0072 1600 0000 da05  ....r....r......
+00002430: 666c 6f61 7472 1300 0000 720f 0000 0072  floatr....r....r
+00002440: 1400 0000 7202 0000 0072 1100 0000 720e  ....r....r....r.
+00002450: 0000 0072 1200 0000 7222 0000 0072 2200  ...r....r"...r".
 00002460: 0000 7222 0000 0072 2300 0000 722e 0000  ..r"...r#...r...
 00002470: 0048 0000 0073 8000 0000 0801 0201 120c  .H...s..........
 00002480: 0202 0201 0201 02fd 0e10 0202 0200 0601  ................
 00002490: 02fe 0e11 0202 0200 0600 0201 02fe 0e12  ................
 000024a0: 0202 00ff 0201 0200 0601 02fe 0e11 0203  ................
 000024b0: 00fe 0201 0201 0a01 02fd 0e12 0202 00ff  ................
 000024c0: 0201 0200 0601 02fe 0e11 0203 00fe 0201  ................
 000024d0: 0201 0a01 02fd 0e12 0201 120c 0201 160c  ................
 000024e0: 0201 160c 0201 120c 0201 120c 0201 160c  ................
 000024f0: 0201 120c 0201 160c 0201 722e 0000 004e  ..........r....N
-00002500: 2920 da06 7479 7069 6e67 7202 0000 0072  ) ..typingr....r
-00002510: 0300 0000 da08 6461 7465 7469 6d65 7204  ......datetimer.
-00002520: 0000 0072 2500 0000 7206 0000 0072 0700  ...r%...r....r..
-00002530: 0000 7208 0000 0072 0900 0000 720a 0000  ..r....r....r...
-00002540: 0072 0b00 0000 720c 0000 0072 0d00 0000  .r....r....r....
-00002550: 720e 0000 0072 0f00 0000 7210 0000 0072  r....r....r....r
-00002560: 1100 0000 7212 0000 0072 1300 0000 7214  ....r....r....r.
-00002570: 0000 0072 1500 0000 7216 0000 0072 1700  ...r....r....r..
-00002580: 0000 7218 0000 0072 1900 0000 5a11 5f67  ..r....r....Z._g
-00002590: 656e 6572 6174 6564 2e6d 6f64 656c 7372  enerated.modelsr
-000025a0: 1b00 0000 da06 6d6f 6465 6c73 721c 0000  ......modelsr...
+00002500: 2920 da08 6461 7465 7469 6d65 7202 0000  ) ..datetimer...
+00002510: 00da 0674 7970 696e 6772 0300 0000 7204  ...typingr....r.
+00002520: 0000 005a 115f 6765 6e65 7261 7465 642e  ...Z._generated.
+00002530: 6d6f 6465 6c73 7206 0000 00da 066d 6f64  modelsr......mod
+00002540: 656c 7372 0700 0000 7225 0000 0072 0900  elsr....r%...r..
+00002550: 0000 720a 0000 0072 0b00 0000 720c 0000  ..r....r....r...
+00002560: 0072 0d00 0000 720e 0000 0072 0f00 0000  .r....r....r....
+00002570: 7210 0000 0072 1100 0000 7212 0000 0072  r....r....r....r
+00002580: 1300 0000 7214 0000 0072 1500 0000 7216  ....r....r....r.
+00002590: 0000 0072 1700 0000 7218 0000 0072 1900  ...r....r....r..
+000025a0: 0000 721a 0000 0072 1b00 0000 721c 0000  ..r....r....r...
 000025b0: 0072 1d00 0000 722e 0000 0072 2200 0000  .r....r....r"...
 000025c0: 7222 0000 0072 2200 0000 7223 0000 00da  r"...r"...r#....
 000025d0: 083c 6d6f 6475 6c65 3e1a 0000 0073 0c00  .<module>....s..
-000025e0: 0000 1001 0c02 5816 0c01 0c03 1011       ......X.......
+000025e0: 0000 0c01 1002 0c01 0c01 5818 1011       ..........X...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_process_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_process_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 11951 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 3% similar despite different names*

```diff
@@ -1,59 +1,59 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 af2e 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 af2e 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 ae00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6403 6404 6c05  d.l.m.Z...d.d.l.
-00000050: 6d06 5a06 6d07 5a07 6d08 5a08 6d09 5a09  m.Z.m.Z.m.Z.m.Z.
-00000060: 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d12 5a12 6d13 5a13 6d14 5a14 6d15 5a15  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d16 5a16 6d17 5a17 6d18 5a18 6d19 5a19  m.Z.m.Z.m.Z.m.Z.
-000000a0: 0100 6405 6406 6c1a 6d1b 5a1b 0100 6405  ..d.d.l.m.Z...d.
-000000b0: 6407 6c1c 6d1d 5a1d 0100 4700 6408 6409  d.l.m.Z...G.d.d.
-000000c0: 8400 6409 6508 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6403 6404 6c05  m.Z.m.Z...d.d.l.
+00000050: 6d06 5a06 0100 6403 6405 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
+00000060: 0100 6406 6407 6c09 6d0a 5a0a 6d0b 5a0b  ..d.d.l.m.Z.m.Z.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 0100 4700 6408 6409  m.Z.m.Z...G.d.d.
+000000c0: 8400 6409 650c 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
 000000d0: 8400 640b 8302 5a1f 640c 5300 290d e900  ..d...Z.d.S.)...
-000000e0: 0000 0029 02da 044c 6973 74da 084f 7074  ...)...List..Opt
-000000f0: 696f 6e61 6c29 01da 0464 6174 65e9 0100  ional)...date...
-00000100: 0000 2914 da16 456c 656d 656e 7456 616c  ..)...ElementVal
-00000110: 7565 5369 6d70 6c65 5479 7065 da11 456c  ueSimpleType..El
-00000120: 656d 656e 7456 616c 7565 556e 696f 6eda  ementValueUnion.
-00000130: 1b50 726f 6365 7373 456c 656d 656e 7456  .ProcessElementV
-00000140: 616c 7565 4163 6365 7373 6f72 da11 6164  alueAccessor..ad
-00000150: 645f 656c 656d 656e 745f 7661 6c75 65da  d_element_value.
-00000160: 1661 6464 5f65 6c65 6d65 6e74 5f76 616c  .add_element_val
-00000170: 7565 5f6c 6973 74da 1a66 696e 645f 656c  ue_list..find_el
-00000180: 656d 656e 745f 7661 6c75 655f 6173 5f64  ement_value_as_d
-00000190: 6174 65da 1b66 696e 645f 656c 656d 656e  ate..find_elemen
-000001a0: 745f 7661 6c75 655f 6173 5f66 6c6f 6174  t_value_as_float
-000001b0: da19 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
-000001c0: 616c 7565 5f61 735f 7374 72da 1967 6574  alue_as_str..get
-000001d0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
-000001e0: 735f 6461 7465 da1e 6765 745f 656c 656d  s_date..get_elem
-000001f0: 656e 745f 7661 6c75 655f 6173 5f64 6174  ent_value_as_dat
-00000200: 655f 6c69 7374 da1a 6765 745f 656c 656d  e_list..get_elem
-00000210: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
-00000220: 6174 da1f 6765 745f 656c 656d 656e 745f  at..get_element_
-00000230: 7661 6c75 655f 6173 5f66 6c6f 6174 5f6c  value_as_float_l
-00000240: 6973 74da 1867 6574 5f65 6c65 6d65 6e74  ist..get_element
-00000250: 5f76 616c 7565 5f61 735f 7374 72da 1d67  _value_as_str..g
-00000260: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-00000270: 5f61 735f 7374 725f 6c69 7374 da17 6765  _as_str_list..ge
-00000280: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-00000290: 7661 6c69 64da 1a67 6574 5f65 6c65 6d65  valid..get_eleme
-000002a0: 6e74 5f76 616c 7565 5f76 616c 6964 5f61  nt_value_valid_a
-000002b0: 74da 1173 6574 5f65 6c65 6d65 6e74 5f76  t..set_element_v
-000002c0: 616c 7565 da16 7365 745f 656c 656d 656e  alue..set_elemen
-000002d0: 745f 7661 6c75 655f 6c69 7374 da17 7365  t_value_list..se
-000002e0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000002f0: 7661 6c69 64da 1a73 6574 5f65 6c65 6d65  valid..set_eleme
-00000300: 6e74 5f76 616c 7565 5f76 616c 6964 5f61  nt_value_valid_a
-00000310: 74e9 0200 0000 2901 da13 5072 6f63 6573  t.....)...Proces
-00000320: 7345 6c65 6d65 6e74 5661 6c75 6529 01da  sElementValue)..
-00000330: 0750 726f 6365 7373 6300 0000 0000 0000  .Processc.......
+000000e0: 0000 0029 01da 0464 6174 6529 02da 044c  ...)...date)...L
+000000f0: 6973 74da 084f 7074 696f 6e61 6ce9 0200  ist..Optional...
+00000100: 0000 2901 da13 5072 6f63 6573 7345 6c65  ..)...ProcessEle
+00000110: 6d65 6e74 5661 6c75 6529 01da 0750 726f  mentValue)...Pro
+00000120: 6365 7373 e901 0000 0029 14da 1645 6c65  cess.....)...Ele
+00000130: 6d65 6e74 5661 6c75 6553 696d 706c 6554  mentValueSimpleT
+00000140: 7970 65da 1145 6c65 6d65 6e74 5661 6c75  ype..ElementValu
+00000150: 6555 6e69 6f6e da1b 5072 6f63 6573 7345  eUnion..ProcessE
+00000160: 6c65 6d65 6e74 5661 6c75 6541 6363 6573  lementValueAcces
+00000170: 736f 72da 1161 6464 5f65 6c65 6d65 6e74  sor..add_element
+00000180: 5f76 616c 7565 da16 6164 645f 656c 656d  _value..add_elem
+00000190: 656e 745f 7661 6c75 655f 6c69 7374 da1a  ent_value_list..
+000001a0: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
+000001b0: 7565 5f61 735f 6461 7465 da1b 6669 6e64  ue_as_date..find
+000001c0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
+000001d0: 735f 666c 6f61 74da 1966 696e 645f 656c  s_float..find_el
+000001e0: 656d 656e 745f 7661 6c75 655f 6173 5f73  ement_value_as_s
+000001f0: 7472 da19 6765 745f 656c 656d 656e 745f  tr..get_element_
+00000200: 7661 6c75 655f 6173 5f64 6174 65da 1e67  value_as_date..g
+00000210: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000220: 5f61 735f 6461 7465 5f6c 6973 74da 1a67  _as_date_list..g
+00000230: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000240: 5f61 735f 666c 6f61 74da 1f67 6574 5f65  _as_float..get_e
+00000250: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
+00000260: 666c 6f61 745f 6c69 7374 da18 6765 745f  float_list..get_
+00000270: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
+00000280: 5f73 7472 da1d 6765 745f 656c 656d 656e  _str..get_elemen
+00000290: 745f 7661 6c75 655f 6173 5f73 7472 5f6c  t_value_as_str_l
+000002a0: 6973 74da 1767 6574 5f65 6c65 6d65 6e74  ist..get_element
+000002b0: 5f76 616c 7565 5f76 616c 6964 da1a 6765  _value_valid..ge
+000002c0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+000002d0: 7661 6c69 645f 6174 da11 7365 745f 656c  valid_at..set_el
+000002e0: 656d 656e 745f 7661 6c75 65da 1673 6574  ement_value..set
+000002f0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f6c  _element_value_l
+00000300: 6973 74da 1773 6574 5f65 6c65 6d65 6e74  ist..set_element
+00000310: 5f76 616c 7565 5f76 616c 6964 da1a 7365  _value_valid..se
+00000320: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000330: 7661 6c69 645f 6174 6300 0000 0000 0000  valid_atc.......
 00000340: 0000 0000 0000 0000 0003 0000 0040 0000  .............@..
 00000350: 0073 4000 0000 6500 5a01 6400 5a02 6503  .s@...e.Z.d.Z.e.
 00000360: 6504 6401 9c02 6402 6403 8404 5a05 6506  e.d...d.d...Z.e.
 00000370: 6507 1900 6404 9c01 6405 6406 8404 5a08  e...d...d.d...Z.
 00000380: 6506 6509 1900 6407 9c01 6408 6409 8404  e.e...d...d.d...
 00000390: 5a0a 640a 5300 290b da1b 4375 7272 656e  Z.d.S.)...Curren
 000003a0: 7445 6c65 6d65 6e74 5661 6c75 6541 6363  tElementValueAcc
@@ -104,17 +104,17 @@
 00000670: 5f65 6c65 6d65 6e74 5f76 616c 7565 7345  _element_valuesE
 00000680: 0000 0073 0c00 0000 0001 0c01 0402 1001  ...s............
 00000690: 1401 0402 7a2e 4375 7272 656e 7445 6c65  ....z.CurrentEle
 000006a0: 6d65 6e74 5661 6c75 6541 6363 6573 736f  mentValueAccesso
 000006b0: 722e 6765 745f 656c 656d 656e 745f 7661  r.get_element_va
 000006c0: 6c75 6573 4e29 0bda 085f 5f6e 616d 655f  luesN)...__name_
 000006d0: 5fda 0a5f 5f6d 6f64 756c 655f 5fda 0c5f  _..__module__.._
-000006e0: 5f71 7561 6c6e 616d 655f 5f72 1c00 0000  _qualname__r....
-000006f0: da03 7374 7272 2400 0000 7202 0000 0072  ..strr$...r....r
-00000700: 0700 0000 7229 0000 0072 1b00 0000 722d  ....r)...r....r-
+000006e0: 5f71 7561 6c6e 616d 655f 5f72 0700 0000  _qualname__r....
+000006f0: da03 7374 7272 2400 0000 7203 0000 0072  ..strr$...r....r
+00000700: 0a00 0000 7229 0000 0072 0600 0000 722d  ....r)...r....r-
 00000710: 0000 0072 2200 0000 7222 0000 0072 2200  ...r"...r"...r".
 00000720: 0000 7223 0000 0072 1d00 0000 3700 0000  ..r#...r....7...
 00000730: 7306 0000 0008 0110 0412 0972 1d00 0000  s..........r....
 00000740: 6300 0000 0000 0000 0000 0000 0000 0000  c...............
 00000750: 0007 0000 0040 0000 0073 ce01 0000 6500  .....@...s....e.
 00000760: 5a01 6400 5a02 6503 6504 6505 6506 6401  Z.d.Z.e.e.e.e.d.
 00000770: 9c03 6402 6403 8404 8301 5a07 6503 6504  ..d.d.....Z.e.e.
@@ -162,17 +162,17 @@
 00000a10: 456c 656d 656e 7420 4465 6669 6e69 7469  Element Definiti
 00000a20: 6f6e 2043 6f64 652e 0a0a 2020 2020 2020  on Code...      
 00000a30: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00000a40: 2020 2020 2020 2054 7275 6520 6966 2061         True if a
 00000a50: 6c6c 2072 656c 6174 6564 2076 616c 6964  ll related valid
 00000a60: 2076 616c 7565 7320 6172 6520 5452 5545   values are TRUE
 00000a70: 2c20 6f74 6865 7277 6973 6520 4661 6c73  , otherwise Fals
-00000a80: 652e 0a20 2020 2020 2020 2029 0272 1400  e..        ).r..
+00000a80: 652e 0a20 2020 2020 2020 2029 0272 1700  e..        ).r..
 00000a90: 0000 721d 0000 0072 1e00 0000 7222 0000  ..r....r....r"..
-00000aa0: 0072 2200 0000 7223 0000 0072 1400 0000  .r"...r#...r....
+00000aa0: 0072 2200 0000 7223 0000 0072 1700 0000  .r"...r#...r....
 00000ab0: 5100 0000 7302 0000 0000 0c7a 2450 726f  Q...s......z$Pro
 00000ac0: 6365 7373 5574 696c 732e 6765 745f 656c  cessUtils.get_el
 00000ad0: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
 00000ae0: 6429 0472 1f00 0000 7220 0000 00da 0569  d).r....r .....i
 00000af0: 6e64 6578 722a 0000 0063 0300 0000 0000  ndexr*...c......
 00000b00: 0000 0000 0000 0300 0000 0400 0000 4300  ..............C.
 00000b10: 0000 7310 0000 0074 0074 017c 007c 0183  ..s....t.t.|.|..
@@ -193,18 +193,18 @@
 00000c00: 2054 6865 2065 6c65 6d65 6e74 2076 616c   The element val
 00000c10: 7565 2069 6e64 6578 2e0a 0a20 2020 2020  ue index...     
 00000c20: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00000c30: 2020 2020 2020 2020 5468 6520 7265 7175          The requ
 00000c40: 6573 7465 6420 7661 6c69 6420 7661 6c75  ested valid valu
 00000c50: 6520 6966 2069 7420 6578 6973 7473 2c20  e if it exists, 
 00000c60: 6f74 6865 7277 6973 6520 4e6f 6e65 2e0a  otherwise None..
-00000c70: 2020 2020 2020 2020 2902 7215 0000 0072          ).r....r
+00000c70: 2020 2020 2020 2020 2902 7218 0000 0072          ).r....r
 00000c80: 1d00 0000 2903 721f 0000 0072 2000 0000  ....).r....r ...
 00000c90: 7233 0000 0072 2200 0000 7222 0000 0072  r3...r"...r"...r
-00000ca0: 2300 0000 7215 0000 005f 0000 0073 0200  #...r...._...s..
+00000ca0: 2300 0000 7218 0000 005f 0000 0073 0200  #...r...._...s..
 00000cb0: 0000 0011 7a27 5072 6f63 6573 7355 7469  ....z'ProcessUti
 00000cc0: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00000cd0: 616c 7565 5f76 616c 6964 5f61 7429 0472  alue_valid_at).r
 00000ce0: 1f00 0000 7220 0000 00da 0576 616c 6964  ....r .....valid
 00000cf0: 722a 0000 0063 0300 0000 0000 0000 0000  r*...c..........
 00000d00: 0000 0300 0000 0400 0000 4300 0000 7314  ..........C...s.
 00000d10: 0000 0074 0074 017c 007c 0183 027c 0283  ...t.t.|.|...|..
@@ -221,18 +221,18 @@
 00000dc0: 6520 656c 656d 656e 7420 6465 6669 6e69  e element defini
 00000dd0: 7469 6f6e 2063 6f64 652e 0a20 2020 2020  tion code..     
 00000de0: 2020 2020 2020 2076 616c 6964 3a20 5468         valid: Th
 00000df0: 6520 7661 6c69 6420 7661 6c75 652e 0a0a  e valid value...
 00000e00: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00000e10: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00000e20: 2070 6173 7365 6420 7072 6f63 6573 732e   passed process.
-00000e30: 0a20 2020 2020 2020 2029 0272 1800 0000  .        ).r....
+00000e30: 0a20 2020 2020 2020 2029 0272 1b00 0000  .        ).r....
 00000e40: 721d 0000 0029 0372 1f00 0000 7220 0000  r....).r....r ..
 00000e50: 0072 3400 0000 7222 0000 0072 2200 0000  .r4...r"...r"...
-00000e60: 7223 0000 0072 1800 0000 7200 0000 7304  r#...r....r...s.
+00000e60: 7223 0000 0072 1b00 0000 7200 0000 7304  r#...r....r...s.
 00000e70: 0000 0000 0d10 027a 2450 726f 6365 7373  .......z$Process
 00000e80: 5574 696c 732e 7365 745f 656c 656d 656e  Utils.set_elemen
 00000e90: 745f 7661 6c75 655f 7661 6c69 6429 0572  t_value_valid).r
 00000ea0: 1f00 0000 7220 0000 0072 3400 0000 7233  ....r ...r4...r3
 00000eb0: 0000 0072 2a00 0000 6304 0000 0000 0000  ...r*...c.......
 00000ec0: 0000 0000 0004 0000 0004 0000 0043 0000  .............C..
 00000ed0: 0073 1600 0000 7400 7401 7c00 7c01 8302  .s....t.t.|.|...
@@ -253,18 +253,18 @@
 00000fc0: 616c 6964 2076 616c 7565 2e0a 2020 2020  alid value..    
 00000fd0: 2020 2020 2020 2020 696e 6465 783a 2054          index: T
 00000fe0: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 00000ff0: 2069 6e64 6578 2e0a 0a20 2020 2020 2020   index...       
 00001000: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001010: 2020 2020 2020 5468 6520 7061 7373 6564        The passed
 00001020: 2070 726f 6365 7373 2e0a 2020 2020 2020   process..      
-00001030: 2020 2902 7219 0000 0072 1d00 0000 2904    ).r....r....).
+00001030: 2020 2902 721c 0000 0072 1d00 0000 2904    ).r....r....).
 00001040: 721f 0000 0072 2000 0000 7234 0000 0072  r....r ...r4...r
 00001050: 3300 0000 7222 0000 0072 2200 0000 7223  3...r"...r"...r#
-00001060: 0000 0072 1900 0000 8300 0000 7304 0000  ...r........s...
+00001060: 0000 0072 1c00 0000 8300 0000 7304 0000  ...r........s...
 00001070: 0000 1012 027a 2750 726f 6365 7373 5574  .....z'ProcessUt
 00001080: 696c 732e 7365 745f 656c 656d 656e 745f  ils.set_element_
 00001090: 7661 6c75 655f 7661 6c69 645f 6174 4e29  value_valid_atN)
 000010a0: 0472 1f00 0000 7220 0000 00da 0d65 6c65  .r....r .....ele
 000010b0: 6d65 6e74 5f76 616c 7565 722a 0000 0063  ment_valuer*...c
 000010c0: 0300 0000 0000 0000 0000 0000 0300 0000  ................
 000010d0: 0400 0000 4300 0000 7314 0000 0074 0074  ....C...s....t.t
@@ -285,17 +285,17 @@
 000011c0: 7468 6520 7661 6c75 6520 6973 204e 6f6e  the value is Non
 000011d0: 652c 2061 6c6c 2063 7572 7265 6e74 2076  e, all current v
 000011e0: 616c 7565 7320 6172 6520 7265 6d6f 7665  alues are remove
 000011f0: 642e 0a0a 2020 2020 2020 2020 5265 7475  d...        Retu
 00001200: 726e 733a 0a20 2020 2020 2020 2020 2020  rns:.           
 00001210: 2054 6865 2070 6173 7365 6420 7072 6f63   The passed proc
 00001220: 6573 732e 0a20 2020 2020 2020 2029 0272  ess..        ).r
-00001230: 1600 0000 721d 0000 00a9 0372 1f00 0000  ....r......r....
+00001230: 1900 0000 721d 0000 00a9 0372 1f00 0000  ....r......r....
 00001240: 7220 0000 0072 3500 0000 7222 0000 0072  r ...r5...r"...r
-00001250: 2200 0000 7223 0000 0072 1600 0000 9700  "...r#...r......
+00001250: 2200 0000 7223 0000 0072 1900 0000 9700  "...r#...r......
 00001260: 0000 7304 0000 0000 0f10 027a 1e50 726f  ..s........z.Pro
 00001270: 6365 7373 5574 696c 732e 7365 745f 656c  cessUtils.set_el
 00001280: 656d 656e 745f 7661 6c75 6529 0472 1f00  ement_value).r..
 00001290: 0000 7220 0000 0072 2500 0000 722a 0000  ..r ...r%...r*..
 000012a0: 0063 0300 0000 0000 0000 0000 0000 0300  .c..............
 000012b0: 0000 0400 0000 4300 0000 7314 0000 0074  ......C...s....t
 000012c0: 0074 017c 007c 0183 027c 0283 0201 007c  .t.|.|...|.....|
@@ -315,18 +315,18 @@
 000013a0: 4966 2074 6865 2076 616c 7565 2069 7320  If the value is 
 000013b0: 4e6f 6e65 206f 7220 656d 7074 792c 2061  None or empty, a
 000013c0: 6c6c 2063 7572 7265 6e74 2076 616c 7565  ll current value
 000013d0: 7320 6172 6520 7265 6d6f 7665 642e 0a0a  s are removed...
 000013e0: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 000013f0: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00001400: 2070 6173 7365 6420 7072 6f63 6573 732e   passed process.
-00001410: 0a20 2020 2020 2020 2029 0272 1700 0000  .        ).r....
+00001410: 0a20 2020 2020 2020 2029 0272 1a00 0000  .        ).r....
 00001420: 721d 0000 00a9 0372 1f00 0000 7220 0000  r......r....r ..
 00001430: 0072 2500 0000 7222 0000 0072 2200 0000  .r%...r"...r"...
-00001440: 7223 0000 0072 1700 0000 aa00 0000 7304  r#...r........s.
+00001440: 7223 0000 0072 1a00 0000 aa00 0000 7304  r#...r........s.
 00001450: 0000 0000 0f10 027a 2350 726f 6365 7373  .......z#Process
 00001460: 5574 696c 732e 7365 745f 656c 656d 656e  Utils.set_elemen
 00001470: 745f 7661 6c75 655f 6c69 7374 6303 0000  t_value_listc...
 00001480: 0000 0000 0000 0000 0003 0000 0004 0000  ................
 00001490: 0043 0000 0073 1400 0000 7400 7401 7c00  .C...s....t.t.|.
 000014a0: 7c01 8302 7c02 8302 0100 7c00 5300 2901  |...|.....|.S.).
 000014b0: 6135 0100 000a 2020 2020 2020 2020 4164  a5....        Ad
@@ -344,17 +344,17 @@
 00001570: 6e74 2076 616c 7565 2e20 4966 2074 6865  nt value. If the
 00001580: 2076 616c 7565 2069 7320 4e6f 6e65 2c20   value is None, 
 00001590: 616c 6c20 6375 7272 656e 7420 7661 6c75  all current valu
 000015a0: 6573 2061 7265 2072 656d 6f76 6564 2e0a  es are removed..
 000015b0: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 000015c0: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 000015d0: 6520 7061 7373 6564 2070 726f 6365 7373  e passed process
-000015e0: 2e0a 2020 2020 2020 2020 2902 7209 0000  ..        ).r...
+000015e0: 2e0a 2020 2020 2020 2020 2902 720c 0000  ..        ).r...
 000015f0: 0072 1d00 0000 7236 0000 0072 2200 0000  .r....r6...r"...
-00001600: 7222 0000 0072 2300 0000 7209 0000 00bd  r"...r#...r.....
+00001600: 7222 0000 0072 2300 0000 720c 0000 00bd  r"...r#...r.....
 00001610: 0000 0073 0400 0000 000f 1002 7a1e 5072  ...s........z.Pr
 00001620: 6f63 6573 7355 7469 6c73 2e61 6464 5f65  ocessUtils.add_e
 00001630: 6c65 6d65 6e74 5f76 616c 7565 6303 0000  lement_valuec...
 00001640: 0000 0000 0000 0000 0003 0000 0004 0000  ................
 00001650: 0043 0000 0073 1400 0000 7400 7401 7c00  .C...s....t.t.|.
 00001660: 7c01 8302 7c02 8302 0100 7c00 5300 2901  |...|.....|.S.).
 00001670: 614c 0100 000a 2020 2020 2020 2020 4164  aL....        Ad
@@ -374,17 +374,17 @@
 00001750: 6f72 2065 6d70 7479 2c20 616c 6c20 6375  or empty, all cu
 00001760: 7272 656e 7420 7661 6c75 6573 2061 7265  rrent values are
 00001770: 2072 656d 6f76 6564 2e0a 0a20 2020 2020   removed...     
 00001780: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001790: 2020 2020 2020 2020 5468 6520 7061 7373          The pass
 000017a0: 6564 206d 6f64 656c 2072 656c 6174 6564  ed model related
 000017b0: 206f 626a 6563 742e 0a20 2020 2020 2020   object..       
-000017c0: 2029 0272 0a00 0000 721d 0000 0072 3700   ).r....r....r7.
+000017c0: 2029 0272 0d00 0000 721d 0000 0072 3700   ).r....r....r7.
 000017d0: 0000 7222 0000 0072 2200 0000 7223 0000  ..r"...r"...r#..
-000017e0: 0072 0a00 0000 d000 0000 7304 0000 0000  .r........s.....
+000017e0: 0072 0d00 0000 d000 0000 7304 0000 0000  .r........s.....
 000017f0: 0f10 027a 2350 726f 6365 7373 5574 696c  ...z#ProcessUtil
 00001800: 732e 6164 645f 656c 656d 656e 745f 7661  s.add_element_va
 00001810: 6c75 655f 6c69 7374 6302 0000 0000 0000  lue_listc.......
 00001820: 0000 0000 0002 0000 0004 0000 0043 0000  .............C..
 00001830: 0073 0e00 0000 7400 7401 7c00 7c01 8302  .s....t.t.|.|...
 00001840: 8301 5300 2901 7adc 0a20 2020 2020 2020  ..S.).z..       
 00001850: 2047 6574 2061 6e20 656c 656d 656e 7420   Get an element 
@@ -396,17 +396,17 @@
 000018b0: 656e 745f 6465 6669 6e69 7469 6f6e 5f63  ent_definition_c
 000018c0: 6f64 653a 2054 6865 2065 6c65 6d65 6e74  ode: The element
 000018d0: 2064 6566 696e 6974 696f 6e20 636f 6465   definition code
 000018e0: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 000018f0: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00001900: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00001910: 6520 6173 2061 2073 7472 2e0a 2020 2020  e as a str..    
-00001920: 2020 2020 2902 7212 0000 0072 1d00 0000      ).r....r....
+00001920: 2020 2020 2902 7215 0000 0072 1d00 0000      ).r....r....
 00001930: 721e 0000 0072 2200 0000 7222 0000 0072  r....r"...r"...r
-00001940: 2300 0000 7212 0000 00e3 0000 0073 0200  #...r........s..
+00001940: 2300 0000 7215 0000 00e3 0000 0073 0200  #...r........s..
 00001950: 0000 000c 7a25 5072 6f63 6573 7355 7469  ....z%ProcessUti
 00001960: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00001970: 616c 7565 5f61 735f 7374 7263 0200 0000  alue_as_strc....
 00001980: 0000 0000 0000 0000 0200 0000 0400 0000  ................
 00001990: 4300 0000 730e 0000 0074 0074 017c 007c  C...s....t.t.|.|
 000019a0: 0183 0283 0153 0029 017a e30a 2020 2020  .....S.).z..    
 000019b0: 2020 2020 5472 7920 746f 2067 6574 2061      Try to get a
@@ -419,16 +419,16 @@
 00001a20: 6669 6e69 7469 6f6e 5f63 6f64 653a 2054  finition_code: T
 00001a30: 6865 2065 6c65 6d65 6e74 2064 6566 696e  he element defin
 00001a40: 6974 696f 6e20 636f 6465 2e0a 0a20 2020  ition code...   
 00001a50: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00001a60: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00001a70: 656d 656e 7420 7661 6c75 6520 6173 2061  ement value as a
 00001a80: 2073 7472 2e0a 2020 2020 2020 2020 2902   str..        ).
-00001a90: 720d 0000 0072 1d00 0000 721e 0000 0072  r....r....r....r
-00001aa0: 2200 0000 7222 0000 0072 2300 0000 720d  "...r"...r#...r.
+00001a90: 7210 0000 0072 1d00 0000 721e 0000 0072  r....r....r....r
+00001aa0: 2200 0000 7222 0000 0072 2300 0000 7210  "...r"...r#...r.
 00001ab0: 0000 00f1 0000 0073 0200 0000 000c 7a26  .......s......z&
 00001ac0: 5072 6f63 6573 7355 7469 6c73 2e66 696e  ProcessUtils.fin
 00001ad0: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 00001ae0: 6173 5f73 7472 6302 0000 0000 0000 0000  as_strc.........
 00001af0: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 00001b00: 0e00 0000 7400 7401 7c00 7c01 8302 8301  ....t.t.|.|.....
 00001b10: 5300 2901 7aee 0a20 2020 2020 2020 2054  S.).z..        T
@@ -442,17 +442,17 @@
 00001b90: 6669 6e69 7469 6f6e 5f63 6f64 653a 2054  finition_code: T
 00001ba0: 6865 2065 6c65 6d65 6e74 2064 6566 696e  he element defin
 00001bb0: 6974 696f 6e20 636f 6465 2e0a 0a20 2020  ition code...   
 00001bc0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00001bd0: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00001be0: 656d 656e 7420 7661 6c75 6573 2061 7320  ement values as 
 00001bf0: 6120 7374 7220 6c69 7374 2e0a 2020 2020  a str list..    
-00001c00: 2020 2020 2902 7213 0000 0072 1d00 0000      ).r....r....
+00001c00: 2020 2020 2902 7216 0000 0072 1d00 0000      ).r....r....
 00001c10: 721e 0000 0072 2200 0000 7222 0000 0072  r....r"...r"...r
-00001c20: 2300 0000 7213 0000 00ff 0000 0073 0200  #...r........s..
+00001c20: 2300 0000 7216 0000 00ff 0000 0073 0200  #...r........s..
 00001c30: 0000 000c 7a2a 5072 6f63 6573 7355 7469  ....z*ProcessUti
 00001c40: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00001c50: 616c 7565 5f61 735f 7374 725f 6c69 7374  alue_as_str_list
 00001c60: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 00001c70: 0004 0000 0043 0000 0073 0e00 0000 7400  .....C...s....t.
 00001c80: 7401 7c00 7c01 8302 8301 5300 2901 7ae0  t.|.|.....S.).z.
 00001c90: 0a20 2020 2020 2020 2047 6574 2061 6e20  .        Get an 
@@ -465,17 +465,17 @@
 00001d00: 6669 6e69 7469 6f6e 5f63 6f64 653a 2054  finition_code: T
 00001d10: 6865 2065 6c65 6d65 6e74 2064 6566 696e  he element defin
 00001d20: 6974 696f 6e20 636f 6465 2e0a 0a20 2020  ition code...   
 00001d30: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00001d40: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00001d50: 656d 656e 7420 7661 6c75 6520 6173 2061  ement value as a
 00001d60: 2066 6c6f 6174 2e0a 2020 2020 2020 2020   float..        
-00001d70: 2902 7210 0000 0072 1d00 0000 721e 0000  ).r....r....r...
+00001d70: 2902 7213 0000 0072 1d00 0000 721e 0000  ).r....r....r...
 00001d80: 0072 2200 0000 7222 0000 0072 2300 0000  .r"...r"...r#...
-00001d90: 7210 0000 000d 0100 0073 0200 0000 000c  r........s......
+00001d90: 7213 0000 000d 0100 0073 0200 0000 000c  r........s......
 00001da0: 7a27 5072 6f63 6573 7355 7469 6c73 2e67  z'ProcessUtils.g
 00001db0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 00001dc0: 5f61 735f 666c 6f61 7463 0200 0000 0000  _as_floatc......
 00001dd0: 0000 0000 0000 0200 0000 0400 0000 4300  ..............C.
 00001de0: 0000 730e 0000 0074 0074 017c 007c 0183  ..s....t.t.|.|..
 00001df0: 0283 0153 0029 017a e70a 2020 2020 2020  ...S.).z..      
 00001e00: 2020 5472 7920 746f 2067 6574 2061 6e20    Try to get an 
@@ -488,17 +488,17 @@
 00001e70: 6669 6e69 7469 6f6e 5f63 6f64 653a 2054  finition_code: T
 00001e80: 6865 2065 6c65 6d65 6e74 2064 6566 696e  he element defin
 00001e90: 6974 696f 6e20 636f 6465 2e0a 0a20 2020  ition code...   
 00001ea0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00001eb0: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00001ec0: 656d 656e 7420 7661 6c75 6520 6173 2061  ement value as a
 00001ed0: 2066 6c6f 6174 2e0a 2020 2020 2020 2020   float..        
-00001ee0: 2902 720c 0000 0072 1d00 0000 721e 0000  ).r....r....r...
+00001ee0: 2902 720f 0000 0072 1d00 0000 721e 0000  ).r....r....r...
 00001ef0: 0072 2200 0000 7222 0000 0072 2300 0000  .r"...r"...r#...
-00001f00: 720c 0000 001b 0100 0073 0200 0000 000c  r........s......
+00001f00: 720f 0000 001b 0100 0073 0200 0000 000c  r........s......
 00001f10: 7a28 5072 6f63 6573 7355 7469 6c73 2e66  z(ProcessUtils.f
 00001f20: 696e 645f 656c 656d 656e 745f 7661 6c75  ind_element_valu
 00001f30: 655f 6173 5f66 6c6f 6174 6302 0000 0000  e_as_floatc.....
 00001f40: 0000 0000 0000 0002 0000 0004 0000 0043  ...............C
 00001f50: 0000 0073 0e00 0000 7400 7401 7c00 7c01  ...s....t.t.|.|.
 00001f60: 8302 8301 5300 2901 7ae7 0a20 2020 2020  ....S.).z..     
 00001f70: 2020 2047 6574 2061 6c6c 2065 6c65 6d65     Get all eleme
@@ -511,17 +511,17 @@
 00001fe0: 6566 696e 6974 696f 6e5f 636f 6465 3a20  efinition_code: 
 00001ff0: 5468 6520 656c 656d 656e 7420 6465 6669  The element defi
 00002000: 6e69 7469 6f6e 2063 6f64 652e 0a0a 2020  nition code...  
 00002010: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 00002020: 2020 2020 2020 2020 2020 2054 6865 2065             The e
 00002030: 6c65 6d65 6e74 2076 616c 7565 2061 7320  lement value as 
 00002040: 6120 666c 6f61 742e 0a20 2020 2020 2020  a float..       
-00002050: 2029 0272 1100 0000 721d 0000 0072 1e00   ).r....r....r..
+00002050: 2029 0272 1400 0000 721d 0000 0072 1e00   ).r....r....r..
 00002060: 0000 7222 0000 0072 2200 0000 7223 0000  ..r"...r"...r#..
-00002070: 0072 1100 0000 2901 0000 7302 0000 0000  .r....)...s.....
+00002070: 0072 1400 0000 2901 0000 7302 0000 0000  .r....)...s.....
 00002080: 0c7a 2c50 726f 6365 7373 5574 696c 732e  .z,ProcessUtils.
 00002090: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 000020a0: 655f 6173 5f66 6c6f 6174 5f6c 6973 7463  e_as_float_listc
 000020b0: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 000020c0: 0400 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
 000020d0: 017c 007c 0183 0283 0153 0029 017a de0a  .|.|.....S.).z..
 000020e0: 2020 2020 2020 2020 4765 7420 616e 2065          Get an e
@@ -534,16 +534,16 @@
 00002150: 6e69 7469 6f6e 5f63 6f64 653a 2054 6865  nition_code: The
 00002160: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00002170: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00002180: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002190: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 000021a0: 656e 7420 7661 6c75 6520 6173 2061 2064  ent value as a d
 000021b0: 6174 652e 0a20 2020 2020 2020 2029 0272  ate..        ).r
-000021c0: 0e00 0000 721d 0000 0072 1e00 0000 7222  ....r....r....r"
-000021d0: 0000 0072 2200 0000 7223 0000 0072 0e00  ...r"...r#...r..
+000021c0: 1100 0000 721d 0000 0072 1e00 0000 7222  ....r....r....r"
+000021d0: 0000 0072 2200 0000 7223 0000 0072 1100  ...r"...r#...r..
 000021e0: 0000 3701 0000 7302 0000 0000 0c7a 2650  ..7...s......z&P
 000021f0: 726f 6365 7373 5574 696c 732e 6765 745f  rocessUtils.get_
 00002200: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
 00002210: 5f64 6174 6563 0200 0000 0000 0000 0000  _datec..........
 00002220: 0000 0200 0000 0400 0000 4300 0000 730e  ..........C...s.
 00002230: 0000 0074 0074 017c 007c 0183 0283 0153  ...t.t.|.|.....S
 00002240: 0029 017a e60a 2020 2020 2020 2020 5472  .).z..        Tr
@@ -556,17 +556,17 @@
 000022b0: 2020 656c 656d 656e 745f 6465 6669 6e69    element_defini
 000022c0: 7469 6f6e 5f63 6f64 653a 2054 6865 2065  tion_code: The e
 000022d0: 6c65 6d65 6e74 2064 6566 696e 6974 696f  lement definitio
 000022e0: 6e20 636f 6465 2e0a 0a20 2020 2020 2020  n code...       
 000022f0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00002300: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00002310: 7420 7661 6c75 6520 6173 2061 2064 6174  t value as a dat
-00002320: 652e 0a20 2020 2020 2020 2029 0272 0b00  e..        ).r..
+00002320: 652e 0a20 2020 2020 2020 2029 0272 0e00  e..        ).r..
 00002330: 0000 721d 0000 0072 1e00 0000 7222 0000  ..r....r....r"..
-00002340: 0072 2200 0000 7223 0000 0072 0b00 0000  .r"...r#...r....
+00002340: 0072 2200 0000 7223 0000 0072 0e00 0000  .r"...r#...r....
 00002350: 4501 0000 7302 0000 0000 0c7a 2750 726f  E...s......z'Pro
 00002360: 6365 7373 5574 696c 732e 6669 6e64 5f65  cessUtils.find_e
 00002370: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00002380: 6461 7465 6302 0000 0000 0000 0000 0000  datec...........
 00002390: 0002 0000 0004 0000 0043 0000 0073 0e00  .........C...s..
 000023a0: 0000 7400 7401 7c00 7c01 8302 8301 5300  ..t.t.|.|.....S.
 000023b0: 2901 7ae3 0a20 2020 2020 2020 2047 6574  ).z..        Get
@@ -579,50 +579,50 @@
 00002420: 656d 656e 745f 6465 6669 6e69 7469 6f6e  ement_definition
 00002430: 5f63 6f64 653a 2054 6865 2065 6c65 6d65  _code: The eleme
 00002440: 6e74 2064 6566 696e 6974 696f 6e20 636f  nt definition co
 00002450: 6465 2e0a 0a20 2020 2020 2020 2052 6574  de...        Ret
 00002460: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00002470: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 00002480: 6c75 6520 6173 2061 2064 6174 652e 0a20  lue as a date.. 
-00002490: 2020 2020 2020 2029 0272 0f00 0000 721d         ).r....r.
+00002490: 2020 2020 2020 2029 0272 1200 0000 721d         ).r....r.
 000024a0: 0000 0072 1e00 0000 7222 0000 0072 2200  ...r....r"...r".
-000024b0: 0000 7223 0000 0072 0f00 0000 5301 0000  ..r#...r....S...
+000024b0: 0000 7223 0000 0072 1200 0000 5301 0000  ..r#...r....S...
 000024c0: 7302 0000 0000 0c7a 2b50 726f 6365 7373  s......z+Process
 000024d0: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 000024e0: 745f 7661 6c75 655f 6173 5f64 6174 655f  t_value_as_date_
 000024f0: 6c69 7374 2901 4e29 014e 2901 4e29 014e  list).N).N).N).N
 00002500: 291e 722e 0000 0072 2f00 0000 7230 0000  ).r....r/...r0..
 00002510: 00da 0c73 7461 7469 636d 6574 686f 6472  ...staticmethodr
-00002520: 1c00 0000 7231 0000 00da 0462 6f6f 6c72  ....r1.....boolr
-00002530: 1400 0000 da03 696e 7472 1500 0000 7203  ......intr....r.
-00002540: 0000 0072 1800 0000 7219 0000 0072 0600  ...r....r....r..
-00002550: 0000 7216 0000 0072 0200 0000 7217 0000  ..r....r....r...
-00002560: 0072 0900 0000 720a 0000 0072 1200 0000  .r....r....r....
-00002570: 720d 0000 0072 1300 0000 da05 666c 6f61  r....r......floa
-00002580: 7472 1000 0000 720c 0000 0072 1100 0000  tr....r....r....
-00002590: 7204 0000 0072 0e00 0000 720b 0000 0072  r....r....r....r
-000025a0: 0f00 0000 7222 0000 0072 2200 0000 7222  ....r"...r"...r"
+00002520: 0700 0000 7231 0000 00da 0462 6f6f 6c72  ....r1.....boolr
+00002530: 1700 0000 da03 696e 7472 1800 0000 7204  ......intr....r.
+00002540: 0000 0072 1b00 0000 721c 0000 0072 0900  ...r....r....r..
+00002550: 0000 7219 0000 0072 0300 0000 721a 0000  ..r....r....r...
+00002560: 0072 0c00 0000 720d 0000 0072 1500 0000  .r....r....r....
+00002570: 7210 0000 0072 1600 0000 da05 666c 6f61  r....r......floa
+00002580: 7472 1300 0000 720f 0000 0072 1400 0000  tr....r....r....
+00002590: 7202 0000 0072 1100 0000 720e 0000 0072  r....r....r....r
+000025a0: 1200 0000 7222 0000 0072 2200 0000 7222  ....r"...r"...r"
 000025b0: 0000 0072 2300 0000 7232 0000 0050 0000  ...r#...r2...P..
 000025c0: 0073 8600 0000 0801 0201 140d 0202 0201  .s..............
 000025d0: 0201 0201 02fc 0e12 0201 1a10 0202 0200  ................
 000025e0: 0200 0600 0201 02fe 0e13 0202 00ff 0201  ................
 000025f0: 0200 0200 0601 02fe 0e12 0202 00ff 0201  ................
 00002600: 0200 0200 0a01 02fe 0e12 0202 00ff 0201  ................
 00002610: 0200 0200 0601 02fe 0e12 0202 00ff 0201  ................
 00002620: 0200 0200 0a01 02fe 0e12 0201 140d 0201  ................
 00002630: 180d 0201 180d 0201 140d 0201 140d 0201  ................
 00002640: 180d 0201 140d 0201 180d 0201 7232 0000  ............r2..
-00002650: 004e 2920 da06 7479 7069 6e67 7202 0000  .N) ..typingr...
-00002660: 0072 0300 0000 da08 6461 7465 7469 6d65  .r......datetime
-00002670: 7204 0000 0072 2500 0000 7206 0000 0072  r....r%...r....r
-00002680: 0700 0000 7208 0000 0072 0900 0000 720a  ....r....r....r.
-00002690: 0000 0072 0b00 0000 720c 0000 0072 0d00  ...r....r....r..
-000026a0: 0000 720e 0000 0072 0f00 0000 7210 0000  ..r....r....r...
-000026b0: 0072 1100 0000 7212 0000 0072 1300 0000  .r....r....r....
-000026c0: 7214 0000 0072 1500 0000 7216 0000 0072  r....r....r....r
-000026d0: 1700 0000 7218 0000 0072 1900 0000 5a11  ....r....r....Z.
-000026e0: 5f67 656e 6572 6174 6564 2e6d 6f64 656c  _generated.model
-000026f0: 7372 1b00 0000 da06 6d6f 6465 6c73 721c  sr......modelsr.
+00002650: 004e 2920 da08 6461 7465 7469 6d65 7202  .N) ..datetimer.
+00002660: 0000 00da 0674 7970 696e 6772 0300 0000  .....typingr....
+00002670: 7204 0000 005a 115f 6765 6e65 7261 7465  r....Z._generate
+00002680: 642e 6d6f 6465 6c73 7206 0000 00da 066d  d.modelsr......m
+00002690: 6f64 656c 7372 0700 0000 7225 0000 0072  odelsr....r%...r
+000026a0: 0900 0000 720a 0000 0072 0b00 0000 720c  ....r....r....r.
+000026b0: 0000 0072 0d00 0000 720e 0000 0072 0f00  ...r....r....r..
+000026c0: 0000 7210 0000 0072 1100 0000 7212 0000  ..r....r....r...
+000026d0: 0072 1300 0000 7214 0000 0072 1500 0000  .r....r....r....
+000026e0: 7216 0000 0072 1700 0000 7218 0000 0072  r....r....r....r
+000026f0: 1900 0000 721a 0000 0072 1b00 0000 721c  ....r....r....r.
 00002700: 0000 0072 1d00 0000 7232 0000 0072 2200  ...r....r2...r".
 00002710: 0000 7222 0000 0072 2200 0000 7223 0000  ..r"...r"...r#..
 00002720: 00da 083c 6d6f 6475 6c65 3e1a 0000 0073  ...<module>....s
-00002730: 0c00 0000 1001 0c02 5816 0c01 0c03 1019  ........X.......
+00002730: 0c00 0000 0c01 1002 0c01 0c01 5818 1019  ............X...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_page_item_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_page_item_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 18240 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 5% similar despite different names*

```diff
@@ -1,83 +1,83 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 4047 0000  U.......=S.d@G..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 2f47 0000  U..........d/G..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 da00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6403 6404 6c05  d.l.m.Z...d.d.l.
-00000050: 6d06 5a06 6d07 5a07 6d08 5a08 6d09 5a09  m.Z.m.Z.m.Z.m.Z.
-00000060: 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d12 5a12 6d13 5a13 6d14 5a14 6d15 5a15  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d16 5a16 6d17 5a17 6d18 5a18 6d19 5a19  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d1a 5a1a 6d1b 5a1b 6d1c 5a1c 6d1d 5a1d  m.Z.m.Z.m.Z.m.Z.
-000000b0: 6d1e 5a1e 6d1f 5a1f 6d20 5a20 6d21 5a21  m.Z.m.Z.m Z m!Z!
-000000c0: 6d22 5a22 0100 6405 6406 6c23 6d24 5a24  m"Z"..d.d.l#m$Z$
-000000d0: 0100 6405 6407 6c25 6d26 5a26 6d27 5a27  ..d.d.l%m&Z&m'Z'
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6403 6404 6c05  m.Z.m.Z...d.d.l.
+00000050: 6d06 5a06 0100 6403 6405 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
+00000060: 6d09 5a09 6d0a 5a0a 0100 6406 6407 6c0b  m.Z.m.Z...d.d.l.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  m.Z.m.Z.m.Z.m.Z.
+000000c0: 6d20 5a20 6d21 5a21 6d22 5a22 6d23 5a23  m Z m!Z!m"Z"m#Z#
+000000d0: 6d24 5a24 6d25 5a25 6d26 5a26 6d27 5a27  m$Z$m%Z%m&Z&m'Z'
 000000e0: 6d28 5a28 0100 4700 6408 6409 8400 6409  m(Z(..G.d.d...d.
-000000f0: 6508 8303 5a29 4700 640a 640b 8400 640b  e...Z)G.d.d...d.
+000000f0: 650e 8303 5a29 4700 640a 640b 8400 640b  e...Z)G.d.d...d.
 00000100: 8302 5a2a 640c 5300 290d e900 0000 0029  ..Z*d.S.)......)
-00000110: 02da 044c 6973 74da 084f 7074 696f 6e61  ...List..Optiona
-00000120: 6c29 01da 0464 6174 65e9 0100 0000 291d  l)...date.....).
-00000130: da16 456c 656d 656e 7456 616c 7565 5369  ..ElementValueSi
-00000140: 6d70 6c65 5479 7065 da11 456c 656d 656e  mpleType..Elemen
-00000150: 7456 616c 7565 556e 696f 6eda 1854 6173  tValueUnion..Tas
-00000160: 6b45 6c65 6d65 6e74 5661 6c75 6541 6363  kElementValueAcc
-00000170: 6573 736f 72da 1161 6464 5f65 6c65 6d65  essor..add_eleme
-00000180: 6e74 5f76 616c 7565 da16 6164 645f 656c  nt_value..add_el
-00000190: 656d 656e 745f 7661 6c75 655f 6c69 7374  ement_value_list
-000001a0: da1a 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
-000001b0: 616c 7565 5f61 735f 6461 7465 da1a 6669  alue_as_date..fi
-000001c0: 6e64 5f65 6c65 6d65 6e74 5f76 616c 7565  nd_element_value
-000001d0: 5f61 735f 6469 6374 da1e 6669 6e64 5f65  _as_dict..find_e
-000001e0: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-000001f0: 646f 6375 6d65 6e74 da1b 6669 6e64 5f65  document..find_e
-00000200: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-00000210: 666c 6f61 74da 1f66 696e 645f 656c 656d  float..find_elem
-00000220: 656e 745f 7661 6c75 655f 6173 5f70 7269  ent_value_as_pri
-00000230: 6e63 6970 616c da19 6669 6e64 5f65 6c65  ncipal..find_ele
-00000240: 6d65 6e74 5f76 616c 7565 5f61 735f 7374  ment_value_as_st
-00000250: 72da 1967 6574 5f65 6c65 6d65 6e74 5f76  r..get_element_v
-00000260: 616c 7565 5f61 735f 6461 7465 da1e 6765  alue_as_date..ge
-00000270: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-00000280: 6173 5f64 6174 655f 6c69 7374 da19 6765  as_date_list..ge
-00000290: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000002a0: 6173 5f64 6963 74da 1e67 6574 5f65 6c65  as_dict..get_ele
-000002b0: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
-000002c0: 6374 5f6c 6973 74da 1d67 6574 5f65 6c65  ct_list..get_ele
-000002d0: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
-000002e0: 6375 6d65 6e74 da22 6765 745f 656c 656d  cument."get_elem
-000002f0: 656e 745f 7661 6c75 655f 6173 5f64 6f63  ent_value_as_doc
-00000300: 756d 656e 745f 6c69 7374 da1a 6765 745f  ument_list..get_
-00000310: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
-00000320: 5f66 6c6f 6174 da1f 6765 745f 656c 656d  _float..get_elem
-00000330: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
-00000340: 6174 5f6c 6973 74da 1e67 6574 5f65 6c65  at_list..get_ele
-00000350: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
-00000360: 696e 6369 7061 6cda 2367 6574 5f65 6c65  incipal.#get_ele
-00000370: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
-00000380: 696e 6369 7061 6c5f 6c69 7374 da18 6765  incipal_list..ge
+00000110: 01da 0464 6174 6529 02da 044c 6973 74da  ...date)...List.
+00000120: 084f 7074 696f 6e61 6ce9 0200 0000 2901  .Optional.....).
+00000130: da10 5461 736b 456c 656d 656e 7456 616c  ..TaskElementVal
+00000140: 7565 2903 da1c 5461 736b 456c 656d 656e  ue)...TaskElemen
+00000150: 7456 616c 7565 446f 6375 6d65 6e74 4974  tValueDocumentIt
+00000160: 656d da1d 5461 736b 456c 656d 656e 7456  em..TaskElementV
+00000170: 616c 7565 5072 696e 6369 7061 6c49 7465  aluePrincipalIte
+00000180: 6dda 0c54 6173 6b50 6167 6549 7465 6de9  m..TaskPageItem.
+00000190: 0100 0000 291d da16 456c 656d 656e 7456  ....)...ElementV
+000001a0: 616c 7565 5369 6d70 6c65 5479 7065 da11  alueSimpleType..
+000001b0: 456c 656d 656e 7456 616c 7565 556e 696f  ElementValueUnio
+000001c0: 6eda 1854 6173 6b45 6c65 6d65 6e74 5661  n..TaskElementVa
+000001d0: 6c75 6541 6363 6573 736f 72da 1161 6464  lueAccessor..add
+000001e0: 5f65 6c65 6d65 6e74 5f76 616c 7565 da16  _element_value..
+000001f0: 6164 645f 656c 656d 656e 745f 7661 6c75  add_element_valu
+00000200: 655f 6c69 7374 da1a 6669 6e64 5f65 6c65  e_list..find_ele
+00000210: 6d65 6e74 5f76 616c 7565 5f61 735f 6461  ment_value_as_da
+00000220: 7465 da1a 6669 6e64 5f65 6c65 6d65 6e74  te..find_element
+00000230: 5f76 616c 7565 5f61 735f 6469 6374 da1e  _value_as_dict..
+00000240: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
+00000250: 7565 5f61 735f 646f 6375 6d65 6e74 da1b  ue_as_document..
+00000260: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
+00000270: 7565 5f61 735f 666c 6f61 74da 1f66 696e  ue_as_float..fin
+00000280: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
+00000290: 6173 5f70 7269 6e63 6970 616c da19 6669  as_principal..fi
+000002a0: 6e64 5f65 6c65 6d65 6e74 5f76 616c 7565  nd_element_value
+000002b0: 5f61 735f 7374 72da 1967 6574 5f65 6c65  _as_str..get_ele
+000002c0: 6d65 6e74 5f76 616c 7565 5f61 735f 6461  ment_value_as_da
+000002d0: 7465 da1e 6765 745f 656c 656d 656e 745f  te..get_element_
+000002e0: 7661 6c75 655f 6173 5f64 6174 655f 6c69  value_as_date_li
+000002f0: 7374 da19 6765 745f 656c 656d 656e 745f  st..get_element_
+00000300: 7661 6c75 655f 6173 5f64 6963 74da 1e67  value_as_dict..g
+00000310: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000320: 5f61 735f 6469 6374 5f6c 6973 74da 1d67  _as_dict_list..g
+00000330: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000340: 5f61 735f 646f 6375 6d65 6e74 da22 6765  _as_document."ge
+00000350: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000360: 6173 5f64 6f63 756d 656e 745f 6c69 7374  as_document_list
+00000370: da1a 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
+00000380: 6c75 655f 6173 5f66 6c6f 6174 da1f 6765  lue_as_float..ge
 00000390: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000003a0: 6173 5f73 7472 da1d 6765 745f 656c 656d  as_str..get_elem
-000003b0: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
-000003c0: 5f6c 6973 74da 1767 6574 5f65 6c65 6d65  _list..get_eleme
-000003d0: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
-000003e0: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
-000003f0: 655f 7661 6c69 645f 6174 da11 7365 745f  e_valid_at..set_
-00000400: 656c 656d 656e 745f 7661 6c75 65da 1673  element_value..s
-00000410: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-00000420: 5f6c 6973 74da 1773 6574 5f65 6c65 6d65  _list..set_eleme
-00000430: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
-00000440: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
-00000450: 655f 7661 6c69 645f 6174 e902 0000 0029  e_valid_at.....)
-00000460: 01da 1054 6173 6b45 6c65 6d65 6e74 5661  ...TaskElementVa
-00000470: 6c75 6529 03da 1c54 6173 6b45 6c65 6d65  lue)...TaskEleme
-00000480: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
-00000490: 7465 6dda 1d54 6173 6b45 6c65 6d65 6e74  tem..TaskElement
-000004a0: 5661 6c75 6550 7269 6e63 6970 616c 4974  ValuePrincipalIt
-000004b0: 656d da0c 5461 736b 5061 6765 4974 656d  em..TaskPageItem
+000003a0: 6173 5f66 6c6f 6174 5f6c 6973 74da 1e67  as_float_list..g
+000003b0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+000003c0: 5f61 735f 7072 696e 6369 7061 6cda 2367  _as_principal.#g
+000003d0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+000003e0: 5f61 735f 7072 696e 6369 7061 6c5f 6c69  _as_principal_li
+000003f0: 7374 da18 6765 745f 656c 656d 656e 745f  st..get_element_
+00000400: 7661 6c75 655f 6173 5f73 7472 da1d 6765  value_as_str..ge
+00000410: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000420: 6173 5f73 7472 5f6c 6973 74da 1767 6574  as_str_list..get
+00000430: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+00000440: 616c 6964 da1a 6765 745f 656c 656d 656e  alid..get_elemen
+00000450: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
+00000460: da11 7365 745f 656c 656d 656e 745f 7661  ..set_element_va
+00000470: 6c75 65da 1673 6574 5f65 6c65 6d65 6e74  lue..set_element
+00000480: 5f76 616c 7565 5f6c 6973 74da 1773 6574  _value_list..set
+00000490: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+000004a0: 616c 6964 da1a 7365 745f 656c 656d 656e  alid..set_elemen
+000004b0: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
 000004c0: 6300 0000 0000 0000 0000 0000 0000 0000  c...............
 000004d0: 0003 0000 0040 0000 0073 4000 0000 6500  .....@...s@...e.
 000004e0: 5a01 6400 5a02 6503 6504 6401 9c02 6402  Z.d.Z.e.e.d...d.
 000004f0: 6403 8404 5a05 6506 6507 1900 6404 9c01  d...Z.e.e...d...
 00000500: 6405 6406 8404 5a08 6506 6509 1900 6407  d.d...Z.e.e...d.
 00000510: 9c01 6408 6409 8404 5a0a 640a 5300 290b  ..d.d...Z.d.S.).
 00000520: da1b 4375 7272 656e 7445 6c65 6d65 6e74  ..CurrentElement
@@ -91,30 +91,30 @@
 000005a0: da04 7365 6c66 722a 0000 0072 2b00 0000  ..selfr*...r+...
 000005b0: a900 722d 0000 00fa 4e2f 776f 726b 2f6b  ..r-....N/work/k
 000005c0: 7566 6c6f 772d 7364 6b2d 7079 7468 6f6e  uflow-sdk-python
 000005d0: 2f6b 7566 6c6f 772d 7265 7374 2f6b 7566  /kuflow-rest/kuf
 000005e0: 6c6f 775f 7265 7374 2f75 7469 6c73 2f5f  low_rest/utils/_
 000005f0: 7461 736b 5f70 6167 655f 6974 656d 5f75  task_page_item_u
 00000600: 7469 6c73 2e70 79da 085f 5f69 6e69 745f  tils.py..__init_
-00000610: 5f45 0000 0073 0400 0000 0001 0601 7a24  _E...s........z$
+00000610: 5f41 0000 0073 0400 0000 0001 0601 7a24  _A...s........z$
 00000620: 4375 7272 656e 7445 6c65 6d65 6e74 5661  CurrentElementVa
 00000630: 6c75 6541 6363 6573 736f 722e 5f5f 696e  lueAccessor.__in
 00000640: 6974 5f5f 2901 da0e 656c 656d 656e 745f  it__)...element_
 00000650: 7661 6c75 6573 6302 0000 0000 0000 0000  valuesc.........
 00000660: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 00000670: 4600 0000 7c00 6a00 6a01 6400 6b08 7214  F...|.j.j.d.k.r.
 00000680: 6900 7c00 6a00 5f01 7402 7c01 8301 6401  i.|.j._.t.|...d.
 00000690: 6b02 7234 7c00 6a00 6a01 a003 7c00 6a04  k.r4|.j.j...|.j.
 000006a0: 6400 a102 0100 6e0e 7c01 7c00 6a00 6a01  d.....n.|.|.j.j.
 000006b0: 7c00 6a04 3c00 6400 5300 a902 4e72 0100  |.j.<.d.S...Nr..
 000006c0: 0000 2905 722a 0000 0072 3000 0000 da03  ..).r*...r0.....
 000006d0: 6c65 6eda 0370 6f70 722b 0000 0029 0272  len..popr+...).r
 000006e0: 2c00 0000 7230 0000 0072 2d00 0000 722d  ,...r0...r-...r-
 000006f0: 0000 0072 2e00 0000 da12 7365 745f 656c  ...r......set_el
-00000700: 656d 656e 745f 7661 6c75 6573 4900 0000  ement_valuesI...
+00000700: 656d 656e 745f 7661 6c75 6573 4500 0000  ement_valuesE...
 00000710: 730a 0000 0000 010c 0108 020c 0114 027a  s..............z
 00000720: 2e43 7572 7265 6e74 456c 656d 656e 7456  .CurrentElementV
 00000730: 616c 7565 4163 6365 7373 6f72 2e73 6574  alueAccessor.set
 00000740: 5f65 6c65 6d65 6e74 5f76 616c 7565 7329  _element_values)
 00000750: 01da 0672 6574 7572 6e63 0100 0000 0000  ...returnc......
 00000760: 0000 0000 0000 0200 0000 0300 0000 4300  ..............C.
 00000770: 0000 733c 0000 007c 006a 006a 0164 006b  ..s<...|.j.j.d.k
@@ -123,26 +123,26 @@
 000007a0: 047c 0183 0164 016b 0272 3867 0053 007c  .|...d.k.r8g.S.|
 000007b0: 0153 0072 3100 0000 2905 722a 0000 0072  .S.r1...).r*...r
 000007c0: 3000 0000 da03 6765 7472 2b00 0000 7232  0.....getr+...r2
 000007d0: 0000 0029 0272 2c00 0000 da16 656c 656d  ...).r,.....elem
 000007e0: 656e 745f 7661 6c75 6573 5f62 795f 636f  ent_values_by_co
 000007f0: 6465 722d 0000 0072 2d00 0000 722e 0000  der-...r-...r...
 00000800: 00da 1267 6574 5f65 6c65 6d65 6e74 5f76  ...get_element_v
-00000810: 616c 7565 7352 0000 0073 0c00 0000 0001  aluesR...s......
+00000810: 616c 7565 734e 0000 0073 0c00 0000 0001  aluesN...s......
 00000820: 0c01 0402 1001 1401 0402 7a2e 4375 7272  ..........z.Curr
 00000830: 656e 7445 6c65 6d65 6e74 5661 6c75 6541  entElementValueA
 00000840: 6363 6573 736f 722e 6765 745f 656c 656d  ccessor.get_elem
 00000850: 656e 745f 7661 6c75 6573 4e29 0bda 085f  ent_valuesN)..._
 00000860: 5f6e 616d 655f 5fda 0a5f 5f6d 6f64 756c  _name__..__modul
 00000870: 655f 5fda 0c5f 5f71 7561 6c6e 616d 655f  e__..__qualname_
-00000880: 5f72 2700 0000 da03 7374 7272 2f00 0000  _r'.....strr/...
-00000890: 7202 0000 0072 0700 0000 7234 0000 0072  r....r....r4...r
-000008a0: 2400 0000 7238 0000 0072 2d00 0000 722d  $...r8...r-...r-
+00000880: 5f72 0900 0000 da03 7374 7272 2f00 0000  _r......strr/...
+00000890: 7203 0000 0072 0c00 0000 7234 0000 0072  r....r....r4...r
+000008a0: 0600 0000 7238 0000 0072 2d00 0000 722d  ....r8...r-...r-
 000008b0: 0000 0072 2d00 0000 722e 0000 0072 2800  ...r-...r....r(.
-000008c0: 0000 4400 0000 7306 0000 0008 0110 0412  ..D...s.........
+000008c0: 0000 4000 0000 7306 0000 0008 0110 0412  ..@...s.........
 000008d0: 0972 2800 0000 6300 0000 0000 0000 0000  .r(...c.........
 000008e0: 0000 0000 0000 0007 0000 0040 0000 0073  ...........@...s
 000008f0: b402 0000 6500 5a01 6400 5a02 6503 6504  ....e.Z.d.Z.e.e.
 00000900: 6505 6506 6401 9c03 6402 6403 8404 8301  e.e.d...d.d.....
 00000910: 5a07 6503 6504 6505 6508 6506 6404 9c04  Z.e.e.e.e.e.d...
 00000920: 6405 6406 8404 8301 5a09 6503 6504 6505  d.d.....Z.e.e.e.
 00000930: 650a 6506 1900 6504 6407 9c04 6408 6409  e.e...e.d...d.d.
@@ -203,17 +203,17 @@
 00000ca0: 6c65 6d65 6e74 2044 6566 696e 6974 696f  lement Definitio
 00000cb0: 6e20 436f 6465 2e0a 0a20 2020 2020 2020  n Code...       
 00000cc0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00000cd0: 2020 2020 2020 5472 7565 2069 6620 616c        True if al
 00000ce0: 6c20 7265 6c61 7465 6420 7661 6c69 6420  l related valid 
 00000cf0: 7661 6c75 6573 2061 7265 2054 5255 452c  values are TRUE,
 00000d00: 206f 7468 6572 7769 7365 2046 616c 7365   otherwise False
-00000d10: 2e0a 2020 2020 2020 2020 2902 721d 0000  ..        ).r...
+00000d10: 2e0a 2020 2020 2020 2020 2902 7222 0000  ..        ).r"..
 00000d20: 0072 2800 0000 7229 0000 0072 2d00 0000  .r(...r)...r-...
-00000d30: 722d 0000 0072 2e00 0000 721d 0000 005e  r-...r....r....^
+00000d30: 722d 0000 0072 2e00 0000 7222 0000 005a  r-...r....r"...Z
 00000d40: 0000 0073 0200 0000 000c 7a29 5461 736b  ...s......z)Task
 00000d50: 5061 6765 4974 656d 5574 696c 732e 6765  PageItemUtils.ge
 00000d60: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
 00000d70: 7661 6c69 6429 0472 2a00 0000 722b 0000  valid).r*...r+..
 00000d80: 00da 0569 6e64 6578 7235 0000 0063 0300  ...indexr5...c..
 00000d90: 0000 0000 0000 0000 0000 0300 0000 0400  ................
 00000da0: 0000 4300 0000 7310 0000 0074 0074 017c  ..C...s....t.t.|
@@ -235,18 +235,18 @@
 00000ea0: 783a 2054 6865 2065 6c65 6d65 6e74 2076  x: The element v
 00000eb0: 616c 7565 2069 6e64 6578 2e0a 0a20 2020  alue index...   
 00000ec0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00000ed0: 2020 2020 2020 2020 2020 5468 6520 7265            The re
 00000ee0: 7175 6573 7465 6420 7661 6c69 6420 7661  quested valid va
 00000ef0: 6c75 6520 6966 2069 7420 6578 6973 7473  lue if it exists
 00000f00: 2c20 6f74 6865 7277 6973 6520 4e6f 6e65  , otherwise None
-00000f10: 2e0a 2020 2020 2020 2020 2902 721e 0000  ..        ).r...
+00000f10: 2e0a 2020 2020 2020 2020 2902 7223 0000  ..        ).r#..
 00000f20: 0072 2800 0000 2903 722a 0000 0072 2b00  .r(...).r*...r+.
 00000f30: 0000 723e 0000 0072 2d00 0000 722d 0000  ..r>...r-...r-..
-00000f40: 0072 2e00 0000 721e 0000 006c 0000 0073  .r....r....l...s
+00000f40: 0072 2e00 0000 7223 0000 0068 0000 0073  .r....r#...h...s
 00000f50: 0200 0000 0011 7a2c 5461 736b 5061 6765  ......z,TaskPage
 00000f60: 4974 656d 5574 696c 732e 6765 745f 656c  ItemUtils.get_el
 00000f70: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
 00000f80: 645f 6174 2904 722a 0000 0072 2b00 0000  d_at).r*...r+...
 00000f90: da05 7661 6c69 6472 3500 0000 6303 0000  ..validr5...c...
 00000fa0: 0000 0000 0000 0000 0003 0000 0004 0000  ................
 00000fb0: 0043 0000 0073 1400 0000 7400 7401 7c00  .C...s....t.t.|.
@@ -264,18 +264,18 @@
 00001070: 653a 2054 6865 2065 6c65 6d65 6e74 2064  e: The element d
 00001080: 6566 696e 6974 696f 6e20 636f 6465 2e0a  efinition code..
 00001090: 2020 2020 2020 2020 2020 2020 7661 6c69              vali
 000010a0: 643a 2054 6865 2076 616c 6964 2076 616c  d: The valid val
 000010b0: 7565 2e0a 0a20 2020 2020 2020 2052 6574  ue...        Ret
 000010c0: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 000010d0: 2020 5468 6520 7061 7373 6564 2074 6173    The passed tas
-000010e0: 6b2e 0a20 2020 2020 2020 2029 0272 2100  k..        ).r!.
+000010e0: 6b2e 0a20 2020 2020 2020 2029 0272 2600  k..        ).r&.
 000010f0: 0000 7228 0000 0029 0372 2a00 0000 722b  ..r(...).r*...r+
 00001100: 0000 0072 3f00 0000 722d 0000 0072 2d00  ...r?...r-...r-.
-00001110: 0000 722e 0000 0072 2100 0000 7f00 0000  ..r....r!.......
+00001110: 0000 722e 0000 0072 2600 0000 7b00 0000  ..r....r&...{...
 00001120: 7304 0000 0000 0f10 027a 2954 6173 6b50  s........z)TaskP
 00001130: 6167 6549 7465 6d55 7469 6c73 2e73 6574  ageItemUtils.set
 00001140: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
 00001150: 616c 6964 2905 722a 0000 0072 2b00 0000  alid).r*...r+...
 00001160: 723f 0000 0072 3e00 0000 7235 0000 0063  r?...r>...r5...c
 00001170: 0400 0000 0000 0000 0000 0000 0400 0000  ................
 00001180: 0400 0000 4300 0000 7316 0000 0074 0074  ....C...s....t.t
@@ -297,18 +297,18 @@
 00001280: 5468 6520 7661 6c69 6420 7661 6c75 652e  The valid value.
 00001290: 0a20 2020 2020 2020 2020 2020 2069 6e64  .            ind
 000012a0: 6578 3a20 5468 6520 656c 656d 656e 7420  ex: The element 
 000012b0: 7661 6c75 6520 696e 6465 782e 0a0a 2020  value index...  
 000012c0: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 000012d0: 2020 2020 2020 2020 2020 2054 6865 2070             The p
 000012e0: 6173 7365 6420 7461 736b 2e0a 2020 2020  assed task..    
-000012f0: 2020 2020 2902 7222 0000 0072 2800 0000      ).r"...r(...
+000012f0: 2020 2020 2902 7227 0000 0072 2800 0000      ).r'...r(...
 00001300: 2904 722a 0000 0072 2b00 0000 723f 0000  ).r*...r+...r?..
 00001310: 0072 3e00 0000 722d 0000 0072 2d00 0000  .r>...r-...r-...
-00001320: 722e 0000 0072 2200 0000 9200 0000 7304  r....r".......s.
+00001320: 722e 0000 0072 2700 0000 8e00 0000 7304  r....r'.......s.
 00001330: 0000 0000 1012 027a 2c54 6173 6b50 6167  .......z,TaskPag
 00001340: 6549 7465 6d55 7469 6c73 2e73 6574 5f65  eItemUtils.set_e
 00001350: 6c65 6d65 6e74 5f76 616c 7565 5f76 616c  lement_value_val
 00001360: 6964 5f61 744e 2904 722a 0000 0072 2b00  id_atN).r*...r+.
 00001370: 0000 da0d 656c 656d 656e 745f 7661 6c75  ....element_valu
 00001380: 6572 3500 0000 6303 0000 0000 0000 0000  er5...c.........
 00001390: 0000 0003 0000 0004 0000 0043 0000 0073  ...........C...s
@@ -330,18 +330,18 @@
 00001490: 2e20 4966 2074 6865 2076 616c 7565 2069  . If the value i
 000014a0: 7320 4e6f 6e65 2c20 616c 6c20 6375 7272  s None, all curr
 000014b0: 656e 7420 7661 6c75 6573 2061 7265 2072  ent values are r
 000014c0: 656d 6f76 6564 2e0a 0a20 2020 2020 2020  emoved...       
 000014d0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 000014e0: 2020 2020 2020 5468 6520 7061 7373 6564        The passed
 000014f0: 2074 6173 6b2e 0a20 2020 2020 2020 2029   task..        )
-00001500: 0272 1f00 0000 7228 0000 00a9 0372 2a00  .r....r(.....r*.
+00001500: 0272 2400 0000 7228 0000 00a9 0372 2a00  .r$...r(.....r*.
 00001510: 0000 722b 0000 0072 4000 0000 722d 0000  ..r+...r@...r-..
-00001520: 0072 2d00 0000 722e 0000 0072 1f00 0000  .r-...r....r....
-00001530: a600 0000 7304 0000 0000 1110 027a 2354  ....s........z#T
+00001520: 0072 2d00 0000 722e 0000 0072 2400 0000  .r-...r....r$...
+00001530: a200 0000 7304 0000 0000 1110 027a 2354  ....s........z#T
 00001540: 6173 6b50 6167 6549 7465 6d55 7469 6c73  askPageItemUtils
 00001550: 2e73 6574 5f65 6c65 6d65 6e74 5f76 616c  .set_element_val
 00001560: 7565 2904 722a 0000 0072 2b00 0000 7230  ue).r*...r+...r0
 00001570: 0000 0072 3500 0000 6303 0000 0000 0000  ...r5...c.......
 00001580: 0000 0000 0003 0000 0004 0000 0043 0000  .............C..
 00001590: 0073 1400 0000 7400 7401 7c00 7c01 8302  .s....t.t.|.|...
 000015a0: 7c02 8302 0100 7c00 5300 2901 614a 0100  |.....|.S.).aJ..
@@ -361,18 +361,18 @@
 00001680: 6c75 652e 2049 6620 7468 6520 7661 6c75  lue. If the valu
 00001690: 6520 6973 204e 6f6e 6520 6f72 2065 6d70  e is None or emp
 000016a0: 7479 2c20 616c 6c20 6375 7272 656e 7420  ty, all current 
 000016b0: 7661 6c75 6573 2061 7265 2072 656d 6f76  values are remov
 000016c0: 6564 2e0a 0a20 2020 2020 2020 2052 6574  ed...        Ret
 000016d0: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 000016e0: 2020 5468 6520 7061 7373 6564 2074 6173    The passed tas
-000016f0: 6b2e 0a20 2020 2020 2020 2029 0272 2000  k..        ).r .
+000016f0: 6b2e 0a20 2020 2020 2020 2029 0272 2500  k..        ).r%.
 00001700: 0000 7228 0000 00a9 0372 2a00 0000 722b  ..r(.....r*...r+
 00001710: 0000 0072 3000 0000 722d 0000 0072 2d00  ...r0...r-...r-.
-00001720: 0000 722e 0000 0072 2000 0000 bb00 0000  ..r....r .......
+00001720: 0000 722e 0000 0072 2500 0000 b700 0000  ..r....r%.......
 00001730: 7304 0000 0000 1110 027a 2854 6173 6b50  s........z(TaskP
 00001740: 6167 6549 7465 6d55 7469 6c73 2e73 6574  ageItemUtils.set
 00001750: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f6c  _element_value_l
 00001760: 6973 7463 0300 0000 0000 0000 0000 0000  istc............
 00001770: 0300 0000 0400 0000 4300 0000 7314 0000  ........C...s...
 00001780: 0074 0074 017c 007c 0183 027c 0283 0201  .t.t.|.|...|....
 00001790: 007c 0053 0029 0161 4001 0000 0a20 2020  .|.S.).a@....   
@@ -391,18 +391,18 @@
 00001860: 656c 656d 656e 7420 7661 6c75 652e 2049  element value. I
 00001870: 6620 7468 6520 7661 6c75 6520 6973 204e  f the value is N
 00001880: 6f6e 652c 2061 6c6c 2063 7572 7265 6e74  one, all current
 00001890: 2076 616c 7565 7320 6172 6520 7265 6d6f   values are remo
 000018a0: 7665 642e 0a0a 2020 2020 2020 2020 5265  ved...        Re
 000018b0: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 000018c0: 2020 2054 6865 2070 6173 7365 6420 7461     The passed ta
-000018d0: 736b 2e0a 2020 2020 2020 2020 2902 7209  sk..        ).r.
+000018d0: 736b 2e0a 2020 2020 2020 2020 2902 720e  sk..        ).r.
 000018e0: 0000 0072 2800 0000 7241 0000 0072 2d00  ...r(...rA...r-.
-000018f0: 0000 722d 0000 0072 2e00 0000 7209 0000  ..r-...r....r...
-00001900: 00d0 0000 0073 0400 0000 0011 1002 7a23  .....s........z#
+000018f0: 0000 722d 0000 0072 2e00 0000 720e 0000  ..r-...r....r...
+00001900: 00cc 0000 0073 0400 0000 0011 1002 7a23  .....s........z#
 00001910: 5461 736b 5061 6765 4974 656d 5574 696c  TaskPageItemUtil
 00001920: 732e 6164 645f 656c 656d 656e 745f 7661  s.add_element_va
 00001930: 6c75 6563 0300 0000 0000 0000 0000 0000  luec............
 00001940: 0300 0000 0400 0000 4300 0000 7314 0000  ........C...s...
 00001950: 0074 0074 017c 007c 0183 027c 0283 0201  .t.t.|.|...|....
 00001960: 007c 0053 0029 0161 5a01 0000 0a20 2020  .|.S.).aZ....   
 00001970: 2020 2020 2041 6464 2065 6c65 6d65 6e74       Add element
@@ -422,17 +422,17 @@
 00001a50: 4e6f 6e65 206f 7220 656d 7074 792c 2061  None or empty, a
 00001a60: 6c6c 2063 7572 7265 6e74 2076 616c 7565  ll current value
 00001a70: 7320 6172 6520 7265 6d6f 7665 642e 0a0a  s are removed...
 00001a80: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00001a90: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00001aa0: 2070 6173 7365 6420 6d6f 6465 6c20 7265   passed model re
 00001ab0: 6c61 7465 6420 6f62 6a65 6374 2e0a 2020  lated object..  
-00001ac0: 2020 2020 2020 2902 720a 0000 0072 2800        ).r....r(.
+00001ac0: 2020 2020 2020 2902 720f 0000 0072 2800        ).r....r(.
 00001ad0: 0000 7242 0000 0072 2d00 0000 722d 0000  ..rB...r-...r-..
-00001ae0: 0072 2e00 0000 720a 0000 00e5 0000 0073  .r....r........s
+00001ae0: 0072 2e00 0000 720f 0000 00e1 0000 0073  .r....r........s
 00001af0: 0400 0000 0011 1002 7a28 5461 736b 5061  ........z(TaskPa
 00001b00: 6765 4974 656d 5574 696c 732e 6164 645f  geItemUtils.add_
 00001b10: 656c 656d 656e 745f 7661 6c75 655f 6c69  element_value_li
 00001b20: 7374 6302 0000 0000 0000 0000 0000 0002  stc.............
 00001b30: 0000 0004 0000 0043 0000 0073 0e00 0000  .......C...s....
 00001b40: 7400 7401 7c00 7c01 8302 8301 5300 2901  t.t.|.|.....S.).
 00001b50: 7aea 0a20 2020 2020 2020 2047 6574 2061  z..        Get a
@@ -445,18 +445,18 @@
 00001bc0: 2020 2020 656c 656d 656e 745f 6465 6669      element_defi
 00001bd0: 6e69 7469 6f6e 5f63 6f64 653a 2054 6865  nition_code: The
 00001be0: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00001bf0: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00001c00: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001c10: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00001c20: 656e 7420 7661 6c75 6520 6173 2061 2073  ent value as a s
-00001c30: 7472 2e0a 2020 2020 2020 2020 2902 721b  tr..        ).r.
+00001c30: 7472 2e0a 2020 2020 2020 2020 2902 7220  tr..        ).r 
 00001c40: 0000 0072 2800 0000 7229 0000 0072 2d00  ...r(...r)...r-.
-00001c50: 0000 722d 0000 0072 2e00 0000 721b 0000  ..r-...r....r...
-00001c60: 00fa 0000 0073 0200 0000 000c 7a2a 5461  .....s......z*Ta
+00001c50: 0000 722d 0000 0072 2e00 0000 7220 0000  ..r-...r....r ..
+00001c60: 00f6 0000 0073 0200 0000 000c 7a2a 5461  .....s......z*Ta
 00001c70: 736b 5061 6765 4974 656d 5574 696c 732e  skPageItemUtils.
 00001c80: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 00001c90: 655f 6173 5f73 7472 6302 0000 0000 0000  e_as_strc.......
 00001ca0: 0000 0000 0002 0000 0004 0000 0043 0000  .............C..
 00001cb0: 0073 0e00 0000 7400 7401 7c00 7c01 8302  .s....t.t.|.|...
 00001cc0: 8301 5300 2901 7af1 0a20 2020 2020 2020  ..S.).z..       
 00001cd0: 2054 7279 2074 6f20 6765 7420 616e 2065   Try to get an e
@@ -469,17 +469,17 @@
 00001d40: 2065 6c65 6d65 6e74 5f64 6566 696e 6974   element_definit
 00001d50: 696f 6e5f 636f 6465 3a20 5468 6520 656c  ion_code: The el
 00001d60: 656d 656e 7420 6465 6669 6e69 7469 6f6e  ement definition
 00001d70: 2063 6f64 652e 0a0a 2020 2020 2020 2020   code...        
 00001d80: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00001d90: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00001da0: 2076 616c 7565 2061 7320 6120 7374 722e   value as a str.
-00001db0: 0a20 2020 2020 2020 2029 0272 1000 0000  .        ).r....
+00001db0: 0a20 2020 2020 2020 2029 0272 1500 0000  .        ).r....
 00001dc0: 7228 0000 0072 2900 0000 722d 0000 0072  r(...r)...r-...r
-00001dd0: 2d00 0000 722e 0000 0072 1000 0000 0801  -...r....r......
+00001dd0: 2d00 0000 722e 0000 0072 1500 0000 0401  -...r....r......
 00001de0: 0000 7302 0000 0000 0c7a 2b54 6173 6b50  ..s......z+TaskP
 00001df0: 6167 6549 7465 6d55 7469 6c73 2e66 696e  ageItemUtils.fin
 00001e00: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 00001e10: 6173 5f73 7472 6302 0000 0000 0000 0000  as_strc.........
 00001e20: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 00001e30: 0e00 0000 7400 7401 7c00 7c01 8302 8301  ....t.t.|.|.....
 00001e40: 5300 2901 7afc 0a20 2020 2020 2020 2054  S.).z..        T
@@ -494,17 +494,17 @@
 00001ed0: 6e69 7469 6f6e 5f63 6f64 653a 2054 6865  nition_code: The
 00001ee0: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00001ef0: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00001f00: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001f10: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00001f20: 656e 7420 7661 6c75 6573 2061 7320 6120  ent values as a 
 00001f30: 7374 7220 6c69 7374 2e0a 2020 2020 2020  str list..      
-00001f40: 2020 2902 721c 0000 0072 2800 0000 7229    ).r....r(...r)
+00001f40: 2020 2902 7221 0000 0072 2800 0000 7229    ).r!...r(...r)
 00001f50: 0000 0072 2d00 0000 722d 0000 0072 2e00  ...r-...r-...r..
-00001f60: 0000 721c 0000 0016 0100 0073 0200 0000  ..r........s....
+00001f60: 0000 7221 0000 0012 0100 0073 0200 0000  ..r!.......s....
 00001f70: 000c 7a2f 5461 736b 5061 6765 4974 656d  ..z/TaskPageItem
 00001f80: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 00001f90: 745f 7661 6c75 655f 6173 5f73 7472 5f6c  t_value_as_str_l
 00001fa0: 6973 7463 0200 0000 0000 0000 0000 0000  istc............
 00001fb0: 0200 0000 0400 0000 4300 0000 730e 0000  ........C...s...
 00001fc0: 0074 0074 017c 007c 0183 0283 0153 0029  .t.t.|.|.....S.)
 00001fd0: 017a ee0a 2020 2020 2020 2020 4765 7420  .z..        Get 
@@ -518,17 +518,17 @@
 00002050: 6566 696e 6974 696f 6e5f 636f 6465 3a20  efinition_code: 
 00002060: 5468 6520 656c 656d 656e 7420 6465 6669  The element defi
 00002070: 6e69 7469 6f6e 2063 6f64 652e 0a0a 2020  nition code...  
 00002080: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 00002090: 2020 2020 2020 2020 2020 2054 6865 2065             The e
 000020a0: 6c65 6d65 6e74 2076 616c 7565 2061 7320  lement value as 
 000020b0: 6120 666c 6f61 742e 0a20 2020 2020 2020  a float..       
-000020c0: 2029 0272 1700 0000 7228 0000 0072 2900   ).r....r(...r).
+000020c0: 2029 0272 1c00 0000 7228 0000 0072 2900   ).r....r(...r).
 000020d0: 0000 722d 0000 0072 2d00 0000 722e 0000  ..r-...r-...r...
-000020e0: 0072 1700 0000 2401 0000 7302 0000 0000  .r....$...s.....
+000020e0: 0072 1c00 0000 2001 0000 7302 0000 0000  .r.... ...s.....
 000020f0: 0c7a 2c54 6173 6b50 6167 6549 7465 6d55  .z,TaskPageItemU
 00002100: 7469 6c73 2e67 6574 5f65 6c65 6d65 6e74  tils.get_element
 00002110: 5f76 616c 7565 5f61 735f 666c 6f61 7463  _value_as_floatc
 00002120: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 00002130: 0400 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
 00002140: 017c 007c 0183 0283 0153 0029 017a f50a  .|.|.....S.).z..
 00002150: 2020 2020 2020 2020 5472 7920 746f 2067          Try to g
@@ -542,17 +542,17 @@
 000021d0: 745f 6465 6669 6e69 7469 6f6e 5f63 6f64  t_definition_cod
 000021e0: 653a 2054 6865 2065 6c65 6d65 6e74 2064  e: The element d
 000021f0: 6566 696e 6974 696f 6e20 636f 6465 2e0a  efinition code..
 00002200: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00002210: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00002220: 6520 656c 656d 656e 7420 7661 6c75 6520  e element value 
 00002230: 6173 2061 2066 6c6f 6174 2e0a 2020 2020  as a float..    
-00002240: 2020 2020 2902 720e 0000 0072 2800 0000      ).r....r(...
+00002240: 2020 2020 2902 7213 0000 0072 2800 0000      ).r....r(...
 00002250: 7229 0000 0072 2d00 0000 722d 0000 0072  r)...r-...r-...r
-00002260: 2e00 0000 720e 0000 0032 0100 0073 0200  ....r....2...s..
+00002260: 2e00 0000 7213 0000 002e 0100 0073 0200  ....r........s..
 00002270: 0000 000c 7a2d 5461 736b 5061 6765 4974  ....z-TaskPageIt
 00002280: 656d 5574 696c 732e 6669 6e64 5f65 6c65  emUtils.find_ele
 00002290: 6d65 6e74 5f76 616c 7565 5f61 735f 666c  ment_value_as_fl
 000022a0: 6f61 7463 0200 0000 0000 0000 0000 0000  oatc............
 000022b0: 0200 0000 0400 0000 4300 0000 730e 0000  ........C...s...
 000022c0: 0074 0074 017c 007c 0183 0283 0153 0029  .t.t.|.|.....S.)
 000022d0: 017a f50a 2020 2020 2020 2020 4765 7420  .z..        Get 
@@ -566,17 +566,17 @@
 00002350: 656d 656e 745f 6465 6669 6e69 7469 6f6e  ement_definition
 00002360: 5f63 6f64 653a 2054 6865 2065 6c65 6d65  _code: The eleme
 00002370: 6e74 2064 6566 696e 6974 696f 6e20 636f  nt definition co
 00002380: 6465 2e0a 0a20 2020 2020 2020 2052 6574  de...        Ret
 00002390: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 000023a0: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 000023b0: 6c75 6520 6173 2061 2066 6c6f 6174 2e0a  lue as a float..
-000023c0: 2020 2020 2020 2020 2902 7218 0000 0072          ).r....r
+000023c0: 2020 2020 2020 2020 2902 721d 0000 0072          ).r....r
 000023d0: 2800 0000 7229 0000 0072 2d00 0000 722d  (...r)...r-...r-
-000023e0: 0000 0072 2e00 0000 7218 0000 0040 0100  ...r....r....@..
+000023e0: 0000 0072 2e00 0000 721d 0000 003c 0100  ...r....r....<..
 000023f0: 0073 0200 0000 000c 7a31 5461 736b 5061  .s......z1TaskPa
 00002400: 6765 4974 656d 5574 696c 732e 6765 745f  geItemUtils.get_
 00002410: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
 00002420: 5f66 6c6f 6174 5f6c 6973 7463 0200 0000  _float_listc....
 00002430: 0000 0000 0000 0000 0200 0000 0400 0000  ................
 00002440: 4300 0000 730e 0000 0074 0074 017c 007c  C...s....t.t.|.|
 00002450: 0183 0283 0153 0029 017a ec0a 2020 2020  .....S.).z..    
@@ -590,17 +590,17 @@
 000024d0: 656d 656e 745f 6465 6669 6e69 7469 6f6e  ement_definition
 000024e0: 5f63 6f64 653a 2054 6865 2065 6c65 6d65  _code: The eleme
 000024f0: 6e74 2064 6566 696e 6974 696f 6e20 636f  nt definition co
 00002500: 6465 2e0a 0a20 2020 2020 2020 2052 6574  de...        Ret
 00002510: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00002520: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 00002530: 6c75 6520 6173 2061 2064 6174 652e 0a20  lue as a date.. 
-00002540: 2020 2020 2020 2029 0272 1100 0000 7228         ).r....r(
+00002540: 2020 2020 2020 2029 0272 1600 0000 7228         ).r....r(
 00002550: 0000 0072 2900 0000 722d 0000 0072 2d00  ...r)...r-...r-.
-00002560: 0000 722e 0000 0072 1100 0000 4e01 0000  ..r....r....N...
+00002560: 0000 722e 0000 0072 1600 0000 4a01 0000  ..r....r....J...
 00002570: 7302 0000 0000 0c7a 2b54 6173 6b50 6167  s......z+TaskPag
 00002580: 6549 7465 6d55 7469 6c73 2e67 6574 5f65  eItemUtils.get_e
 00002590: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 000025a0: 6461 7465 6302 0000 0000 0000 0000 0000  datec...........
 000025b0: 0002 0000 0004 0000 0043 0000 0073 0e00  .........C...s..
 000025c0: 0000 7400 7401 7c00 7c01 8302 8301 5300  ..t.t.|.|.....S.
 000025d0: 2901 7af4 0a20 2020 2020 2020 2054 7279  ).z..        Try
@@ -614,17 +614,17 @@
 00002650: 6c65 6d65 6e74 5f64 6566 696e 6974 696f  lement_definitio
 00002660: 6e5f 636f 6465 3a20 5468 6520 656c 656d  n_code: The elem
 00002670: 656e 7420 6465 6669 6e69 7469 6f6e 2063  ent definition c
 00002680: 6f64 652e 0a0a 2020 2020 2020 2020 5265  ode...        Re
 00002690: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 000026a0: 2020 2054 6865 2065 6c65 6d65 6e74 2076     The element v
 000026b0: 616c 7565 2061 7320 6120 6461 7465 2e0a  alue as a date..
-000026c0: 2020 2020 2020 2020 2902 720b 0000 0072          ).r....r
+000026c0: 2020 2020 2020 2020 2902 7210 0000 0072          ).r....r
 000026d0: 2800 0000 7229 0000 0072 2d00 0000 722d  (...r)...r-...r-
-000026e0: 0000 0072 2e00 0000 720b 0000 005c 0100  ...r....r....\..
+000026e0: 0000 0072 2e00 0000 7210 0000 0058 0100  ...r....r....X..
 000026f0: 0073 0200 0000 000c 7a2c 5461 736b 5061  .s......z,TaskPa
 00002700: 6765 4974 656d 5574 696c 732e 6669 6e64  geItemUtils.find
 00002710: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
 00002720: 735f 6461 7465 6302 0000 0000 0000 0000  s_datec.........
 00002730: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 00002740: 0e00 0000 7400 7401 7c00 7c01 8302 8301  ....t.t.|.|.....
 00002750: 5300 2901 7af5 0a20 2020 2020 2020 2047  S.).z..        G
@@ -638,18 +638,18 @@
 000027d0: 656d 656e 745f 6465 6669 6e69 7469 6f6e  ement_definition
 000027e0: 5f63 6f64 653a 2054 6865 2065 6c65 6d65  _code: The eleme
 000027f0: 6e74 2064 6566 696e 6974 696f 6e20 636f  nt definition co
 00002800: 6465 2e0a 0a20 2020 2020 2020 2052 6574  de...        Ret
 00002810: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00002820: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 00002830: 6c75 6573 2061 7320 6461 7465 206c 6973  lues as date lis
-00002840: 742e 0a20 2020 2020 2020 2029 0272 1200  t..        ).r..
+00002840: 742e 0a20 2020 2020 2020 2029 0272 1700  t..        ).r..
 00002850: 0000 7228 0000 0072 2900 0000 722d 0000  ..r(...r)...r-..
-00002860: 0072 2d00 0000 722e 0000 0072 1200 0000  .r-...r....r....
-00002870: 6a01 0000 7302 0000 0000 0e7a 3054 6173  j...s......z0Tas
+00002860: 0072 2d00 0000 722e 0000 0072 1700 0000  .r-...r....r....
+00002870: 6601 0000 7302 0000 0000 0e7a 3054 6173  f...s......z0Tas
 00002880: 6b50 6167 6549 7465 6d55 7469 6c73 2e67  kPageItemUtils.g
 00002890: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 000028a0: 5f61 735f 6461 7465 5f6c 6973 7463 0200  _as_date_listc..
 000028b0: 0000 0000 0000 0000 0000 0200 0000 0400  ................
 000028c0: 0000 4300 0000 730e 0000 0074 0074 017c  ..C...s....t.t.|
 000028d0: 007c 0183 0283 0153 0029 017a ec0a 2020  .|.....S.).z..  
 000028e0: 2020 2020 2020 4765 7420 616e 2065 6c65        Get an ele
@@ -662,17 +662,17 @@
 00002950: 656c 656d 656e 745f 6465 6669 6e69 7469  element_definiti
 00002960: 6f6e 5f63 6f64 653a 2054 6865 2065 6c65  on_code: The ele
 00002970: 6d65 6e74 2064 6566 696e 6974 696f 6e20  ment definition 
 00002980: 636f 6465 2e0a 0a20 2020 2020 2020 2052  code...        R
 00002990: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 000029a0: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 000029b0: 7661 6c75 6520 6173 2061 2064 6963 742e  value as a dict.
-000029c0: 0a20 2020 2020 2020 2029 0272 1300 0000  .        ).r....
+000029c0: 0a20 2020 2020 2020 2029 0272 1800 0000  .        ).r....
 000029d0: 7228 0000 0072 2900 0000 722d 0000 0072  r(...r)...r-...r
-000029e0: 2d00 0000 722e 0000 0072 1300 0000 7a01  -...r....r....z.
+000029e0: 2d00 0000 722e 0000 0072 1800 0000 7601  -...r....r....v.
 000029f0: 0000 7302 0000 0000 0c7a 2b54 6173 6b50  ..s......z+TaskP
 00002a00: 6167 6549 7465 6d55 7469 6c73 2e67 6574  ageItemUtils.get
 00002a10: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
 00002a20: 735f 6469 6374 6302 0000 0000 0000 0000  s_dictc.........
 00002a30: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 00002a40: 0e00 0000 7400 7401 7c00 7c01 8302 8301  ....t.t.|.|.....
 00002a50: 5300 2901 7af3 0a20 2020 2020 2020 2054  S.).z..        T
@@ -686,17 +686,17 @@
 00002ad0: 656c 656d 656e 745f 6465 6669 6e69 7469  element_definiti
 00002ae0: 6f6e 5f63 6f64 653a 2054 6865 2065 6c65  on_code: The ele
 00002af0: 6d65 6e74 2064 6566 696e 6974 696f 6e20  ment definition 
 00002b00: 636f 6465 2e0a 0a20 2020 2020 2020 2052  code...        R
 00002b10: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00002b20: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00002b30: 7661 6c75 6520 6173 2061 2064 6963 742e  value as a dict.
-00002b40: 0a20 2020 2020 2020 2029 0272 0c00 0000  .        ).r....
+00002b40: 0a20 2020 2020 2020 2029 0272 1100 0000  .        ).r....
 00002b50: 7228 0000 0072 2900 0000 722d 0000 0072  r(...r)...r-...r
-00002b60: 2d00 0000 722e 0000 0072 0c00 0000 8801  -...r....r......
+00002b60: 2d00 0000 722e 0000 0072 1100 0000 8401  -...r....r......
 00002b70: 0000 7302 0000 0000 0c7a 2c54 6173 6b50  ..s......z,TaskP
 00002b80: 6167 6549 7465 6d55 7469 6c73 2e66 696e  ageItemUtils.fin
 00002b90: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 00002ba0: 6173 5f64 6963 7463 0200 0000 0000 0000  as_dictc........
 00002bb0: 0000 0000 0200 0000 0400 0000 4300 0000  ............C...
 00002bc0: 730e 0000 0074 0074 017c 007c 0183 0283  s....t.t.|.|....
 00002bd0: 0153 0029 017a f50a 2020 2020 2020 2020  .S.).z..        
@@ -710,18 +710,18 @@
 00002c50: 6c65 6d65 6e74 5f64 6566 696e 6974 696f  lement_definitio
 00002c60: 6e5f 636f 6465 3a20 5468 6520 656c 656d  n_code: The elem
 00002c70: 656e 7420 6465 6669 6e69 7469 6f6e 2063  ent definition c
 00002c80: 6f64 652e 0a0a 2020 2020 2020 2020 5265  ode...        Re
 00002c90: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00002ca0: 2020 2054 6865 2065 6c65 6d65 6e74 2076     The element v
 00002cb0: 616c 7565 7320 6173 2064 6963 7420 6c69  alues as dict li
-00002cc0: 7374 2e0a 2020 2020 2020 2020 2902 7214  st..        ).r.
+00002cc0: 7374 2e0a 2020 2020 2020 2020 2902 7219  st..        ).r.
 00002cd0: 0000 0072 2800 0000 7229 0000 0072 2d00  ...r(...r)...r-.
-00002ce0: 0000 722d 0000 0072 2e00 0000 7214 0000  ..r-...r....r...
-00002cf0: 0096 0100 0073 0200 0000 000e 7a30 5461  .....s......z0Ta
+00002ce0: 0000 722d 0000 0072 2e00 0000 7219 0000  ..r-...r....r...
+00002cf0: 0092 0100 0073 0200 0000 000e 7a30 5461  .....s......z0Ta
 00002d00: 736b 5061 6765 4974 656d 5574 696c 732e  skPageItemUtils.
 00002d10: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 00002d20: 655f 6173 5f64 6963 745f 6c69 7374 6302  e_as_dict_listc.
 00002d30: 0000 0000 0000 0000 0000 0002 0000 0004  ................
 00002d40: 0000 0043 0000 0073 0e00 0000 7400 7401  ...C...s....t.t.
 00002d50: 7c00 7c01 8302 8301 5300 2901 611c 0100  |.|.....S.).a...
 00002d60: 000a 2020 2020 2020 2020 4765 7420 616e  ..        Get an
@@ -738,17 +738,17 @@
 00002e10: 2064 6566 696e 6974 696f 6e20 636f 6465   definition code
 00002e20: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00002e30: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00002e40: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00002e50: 6520 6173 2061 2054 6173 6b45 6c65 6d65  e as a TaskEleme
 00002e60: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
 00002e70: 7465 6d2e 0a20 2020 2020 2020 2029 0272  tem..        ).r
-00002e80: 1500 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
-00002e90: 0000 0072 2d00 0000 722e 0000 0072 1500  ...r-...r....r..
-00002ea0: 0000 a601 0000 7302 0000 0000 0e7a 2f54  ......s......z/T
+00002e80: 1a00 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
+00002e90: 0000 0072 2d00 0000 722e 0000 0072 1a00  ...r-...r....r..
+00002ea0: 0000 a201 0000 7302 0000 0000 0e7a 2f54  ......s......z/T
 00002eb0: 6173 6b50 6167 6549 7465 6d55 7469 6c73  askPageItemUtils
 00002ec0: 2e67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
 00002ed0: 7565 5f61 735f 646f 6375 6d65 6e74 6302  ue_as_documentc.
 00002ee0: 0000 0000 0000 0000 0000 0002 0000 0004  ................
 00002ef0: 0000 0043 0000 0073 0e00 0000 7400 7401  ...C...s....t.t.
 00002f00: 7c00 7c01 8302 8301 5300 2901 6124 0100  |.|.....S.).a$..
 00002f10: 000a 2020 2020 2020 2020 5472 7920 746f  ..        Try to
@@ -765,17 +765,17 @@
 00002fc0: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00002fd0: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00002fe0: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002ff0: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00003000: 656e 7420 7661 6c75 6520 6173 2061 2054  ent value as a T
 00003010: 6173 6b45 6c65 6d65 6e74 5661 6c75 6544  askElementValueD
 00003020: 6f63 756d 656e 7449 7465 6d2e 0a20 2020  ocumentItem..   
-00003030: 2020 2020 2029 0272 0d00 0000 7228 0000       ).r....r(..
+00003030: 2020 2020 2029 0272 1200 0000 7228 0000       ).r....r(..
 00003040: 0072 2900 0000 722d 0000 0072 2d00 0000  .r)...r-...r-...
-00003050: 722e 0000 0072 0d00 0000 b601 0000 7302  r....r........s.
+00003050: 722e 0000 0072 1200 0000 b201 0000 7302  r....r........s.
 00003060: 0000 0000 0e7a 3054 6173 6b50 6167 6549  .....z0TaskPageI
 00003070: 7465 6d55 7469 6c73 2e66 696e 645f 656c  temUtils.find_el
 00003080: 656d 656e 745f 7661 6c75 655f 6173 5f64  ement_value_as_d
 00003090: 6f63 756d 656e 7463 0200 0000 0000 0000  ocumentc........
 000030a0: 0000 0000 0200 0000 0400 0000 4300 0000  ............C...
 000030b0: 730e 0000 0074 0074 017c 007c 0183 0283  s....t.t.|.|....
 000030c0: 0153 0029 0161 2501 0000 0a20 2020 2020  .S.).a%....     
@@ -793,17 +793,17 @@
 00003180: 6566 696e 6974 696f 6e20 636f 6465 2e0a  efinition code..
 00003190: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 000031a0: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 000031b0: 6520 656c 656d 656e 7420 7661 6c75 6573  e element values
 000031c0: 2061 7320 5461 736b 456c 656d 656e 7456   as TaskElementV
 000031d0: 616c 7565 446f 6375 6d65 6e74 4974 656d  alueDocumentItem
 000031e0: 206c 6973 742e 0a20 2020 2020 2020 2029   list..        )
-000031f0: 0272 1600 0000 7228 0000 0072 2900 0000  .r....r(...r)...
+000031f0: 0272 1b00 0000 7228 0000 0072 2900 0000  .r....r(...r)...
 00003200: 722d 0000 0072 2d00 0000 722e 0000 0072  r-...r-...r....r
-00003210: 1600 0000 c601 0000 7302 0000 0000 0e7a  ........s......z
+00003210: 1b00 0000 c201 0000 7302 0000 0000 0e7a  ........s......z
 00003220: 3454 6173 6b50 6167 6549 7465 6d55 7469  4TaskPageItemUti
 00003230: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00003240: 616c 7565 5f61 735f 646f 6375 6d65 6e74  alue_as_document
 00003250: 5f6c 6973 7463 0200 0000 0000 0000 0000  _listc..........
 00003260: 0000 0200 0000 0400 0000 4300 0000 730e  ..........C...s.
 00003270: 0000 0074 0074 017c 007c 0183 0283 0153  ...t.t.|.|.....S
 00003280: 0029 0161 1e01 0000 0a20 2020 2020 2020  .).a.....       
@@ -820,17 +820,17 @@
 00003330: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00003340: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00003350: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00003360: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00003370: 656e 7420 7661 6c75 6520 6173 2061 2054  ent value as a T
 00003380: 6173 6b45 6c65 6d65 6e74 5661 6c75 6550  askElementValueP
 00003390: 7269 6e63 6970 616c 4974 656d 2e0a 2020  rincipalItem..  
-000033a0: 2020 2020 2020 2902 7219 0000 0072 2800        ).r....r(.
+000033a0: 2020 2020 2020 2902 721e 0000 0072 2800        ).r....r(.
 000033b0: 0000 7229 0000 0072 2d00 0000 722d 0000  ..r)...r-...r-..
-000033c0: 0072 2e00 0000 7219 0000 00d6 0100 0073  .r....r........s
+000033c0: 0072 2e00 0000 721e 0000 00d2 0100 0073  .r....r........s
 000033d0: 0200 0000 000e 7a30 5461 736b 5061 6765  ......z0TaskPage
 000033e0: 4974 656d 5574 696c 732e 6765 745f 656c  ItemUtils.get_el
 000033f0: 656d 656e 745f 7661 6c75 655f 6173 5f70  ement_value_as_p
 00003400: 7269 6e63 6970 616c 6302 0000 0000 0000  rincipalc.......
 00003410: 0000 0000 0002 0000 0004 0000 0043 0000  .............C..
 00003420: 0073 0e00 0000 7400 7401 7c00 7c01 8302  .s....t.t.|.|...
 00003430: 8301 5300 2901 6126 0100 000a 2020 2020  ..S.).a&....    
@@ -848,17 +848,17 @@
 000034f0: 656e 7420 6465 6669 6e69 7469 6f6e 2063  ent definition c
 00003500: 6f64 652e 0a0a 2020 2020 2020 2020 5265  ode...        Re
 00003510: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00003520: 2020 2054 6865 2065 6c65 6d65 6e74 2076     The element v
 00003530: 616c 7565 2061 7320 6120 5461 736b 456c  alue as a TaskEl
 00003540: 656d 656e 7456 616c 7565 5072 696e 6369  ementValuePrinci
 00003550: 7061 6c49 7465 6d2e 0a20 2020 2020 2020  palItem..       
-00003560: 2029 0272 0f00 0000 7228 0000 0072 2900   ).r....r(...r).
+00003560: 2029 0272 1400 0000 7228 0000 0072 2900   ).r....r(...r).
 00003570: 0000 722d 0000 0072 2d00 0000 722e 0000  ..r-...r-...r...
-00003580: 0072 0f00 0000 e601 0000 7302 0000 0000  .r........s.....
+00003580: 0072 1400 0000 e201 0000 7302 0000 0000  .r........s.....
 00003590: 0e7a 3154 6173 6b50 6167 6549 7465 6d55  .z1TaskPageItemU
 000035a0: 7469 6c73 2e66 696e 645f 656c 656d 656e  tils.find_elemen
 000035b0: 745f 7661 6c75 655f 6173 5f70 7269 6e63  t_value_as_princ
 000035c0: 6970 616c 6302 0000 0000 0000 0000 0000  ipalc...........
 000035d0: 0002 0000 0004 0000 0043 0000 0073 0e00  .........C...s..
 000035e0: 0000 7400 7401 7c00 7c01 8302 8301 5300  ..t.t.|.|.....S.
 000035f0: 2901 6127 0100 000a 2020 2020 2020 2020  ).a'....        
@@ -876,64 +876,64 @@
 000036b0: 696e 6974 696f 6e20 636f 6465 2e0a 0a20  inition code... 
 000036c0: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 000036d0: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 000036e0: 656c 656d 656e 7420 7661 6c75 6573 2061  element values a
 000036f0: 7320 5461 736b 456c 656d 656e 7456 616c  s TaskElementVal
 00003700: 7565 5072 696e 6369 7061 6c49 7465 6d20  uePrincipalItem 
 00003710: 6c69 7374 2e0a 2020 2020 2020 2020 2902  list..        ).
-00003720: 721a 0000 0072 2800 0000 7229 0000 0072  r....r(...r)...r
-00003730: 2d00 0000 722d 0000 0072 2e00 0000 721a  -...r-...r....r.
-00003740: 0000 00f6 0100 0073 0200 0000 000e 7a35  .......s......z5
+00003720: 721f 0000 0072 2800 0000 7229 0000 0072  r....r(...r)...r
+00003730: 2d00 0000 722d 0000 0072 2e00 0000 721f  -...r-...r....r.
+00003740: 0000 00f2 0100 0073 0200 0000 000e 7a35  .......s......z5
 00003750: 5461 736b 5061 6765 4974 656d 5574 696c  TaskPageItemUtil
 00003760: 732e 6765 745f 656c 656d 656e 745f 7661  s.get_element_va
 00003770: 6c75 655f 6173 5f70 7269 6e63 6970 616c  lue_as_principal
 00003780: 5f6c 6973 7429 014e 2901 4e29 014e 2901  _list).N).N).N).
 00003790: 4e29 2a72 3900 0000 723a 0000 0072 3b00  N)*r9...r:...r;.
 000037a0: 0000 da0c 7374 6174 6963 6d65 7468 6f64  ....staticmethod
-000037b0: 7227 0000 0072 3c00 0000 da04 626f 6f6c  r'...r<.....bool
-000037c0: 721d 0000 00da 0369 6e74 721e 0000 0072  r......intr....r
-000037d0: 0300 0000 7221 0000 0072 2200 0000 7206  ....r!...r"...r.
-000037e0: 0000 0072 1f00 0000 7202 0000 0072 2000  ...r....r....r .
-000037f0: 0000 7209 0000 0072 0a00 0000 721b 0000  ..r....r....r...
-00003800: 0072 1000 0000 721c 0000 00da 0566 6c6f  .r....r......flo
-00003810: 6174 7217 0000 0072 0e00 0000 7218 0000  atr....r....r...
-00003820: 0072 0400 0000 7211 0000 0072 0b00 0000  .r....r....r....
-00003830: 7212 0000 00da 0464 6963 7472 1300 0000  r......dictr....
-00003840: 720c 0000 0072 1400 0000 7225 0000 0072  r....r....r%...r
-00003850: 1500 0000 720d 0000 0072 1600 0000 7226  ....r....r....r&
-00003860: 0000 0072 1900 0000 720f 0000 0072 1a00  ...r....r....r..
+000037b0: 7209 0000 0072 3c00 0000 da04 626f 6f6c  r....r<.....bool
+000037c0: 7222 0000 00da 0369 6e74 7223 0000 0072  r".....intr#...r
+000037d0: 0400 0000 7226 0000 0072 2700 0000 720b  ....r&...r'...r.
+000037e0: 0000 0072 2400 0000 7203 0000 0072 2500  ...r$...r....r%.
+000037f0: 0000 720e 0000 0072 0f00 0000 7220 0000  ..r....r....r ..
+00003800: 0072 1500 0000 7221 0000 00da 0566 6c6f  .r....r!.....flo
+00003810: 6174 721c 0000 0072 1300 0000 721d 0000  atr....r....r...
+00003820: 0072 0200 0000 7216 0000 0072 1000 0000  .r....r....r....
+00003830: 7217 0000 00da 0464 6963 7472 1800 0000  r......dictr....
+00003840: 7211 0000 0072 1900 0000 7207 0000 0072  r....r....r....r
+00003850: 1a00 0000 7212 0000 0072 1b00 0000 7208  ....r....r....r.
+00003860: 0000 0072 1e00 0000 7214 0000 0072 1f00  ...r....r....r..
 00003870: 0000 722d 0000 0072 2d00 0000 722d 0000  ..r-...r-...r-..
-00003880: 0072 2e00 0000 723d 0000 005d 0000 0073  .r....r=...]...s
+00003880: 0072 2e00 0000 723d 0000 0059 0000 0073  .r....r=...Y...s
 00003890: e200 0000 0801 0201 140d 0202 0201 0201  ................
 000038a0: 0201 02fc 0e12 0202 0200 0200 0601 02fe  ................
 000038b0: 0e12 0202 0200 0200 0600 0201 02fe 0e13  ................
 000038c0: 0204 00fd 0201 0201 0201 0601 02fc 0e14  ................
 000038d0: 0204 00fd 0201 0201 0201 0a01 02fc 0e14  ................
 000038e0: 0204 00fd 0201 0201 0201 0601 02fc 0e14  ................
 000038f0: 0204 00fd 0201 0201 0201 0a01 02fc 0e14  ................
 00003900: 0201 140d 0201 180d 0201 180d 0201 140d  ................
 00003910: 0201 140d 0201 180d 0201 140d 0201 180d  ................
 00003920: 0202 0200 0201 0afe 0e0f 0201 140d 0201  ................
 00003930: 180d 0202 0200 0201 0afe 0e0f 0202 0200  ................
 00003940: 0201 02fe 0e0f 0202 0200 0201 06fe 0e0f  ................
 00003950: 0202 0200 0201 06fe 0e0f 0202 0200 0201  ................
 00003960: 02fe 0e0f 0202 0200 0201 06fe 0e0f 0202  ................
-00003970: 0200 0201 06fe 723d 0000 004e 292b da06  ......r=...N)+..
-00003980: 7479 7069 6e67 7202 0000 0072 0300 0000  typingr....r....
-00003990: da08 6461 7465 7469 6d65 7204 0000 0072  ..datetimer....r
-000039a0: 3000 0000 7206 0000 0072 0700 0000 7208  0...r....r....r.
-000039b0: 0000 0072 0900 0000 720a 0000 0072 0b00  ...r....r....r..
-000039c0: 0000 720c 0000 0072 0d00 0000 720e 0000  ..r....r....r...
-000039d0: 0072 0f00 0000 7210 0000 0072 1100 0000  .r....r....r....
-000039e0: 7212 0000 0072 1300 0000 7214 0000 0072  r....r....r....r
-000039f0: 1500 0000 7216 0000 0072 1700 0000 7218  ....r....r....r.
-00003a00: 0000 0072 1900 0000 721a 0000 0072 1b00  ...r....r....r..
-00003a10: 0000 721c 0000 0072 1d00 0000 721e 0000  ..r....r....r...
-00003a20: 0072 1f00 0000 7220 0000 0072 2100 0000  .r....r ...r!...
-00003a30: 7222 0000 005a 115f 6765 6e65 7261 7465  r"...Z._generate
-00003a40: 642e 6d6f 6465 6c73 7224 0000 00da 066d  d.modelsr$.....m
-00003a50: 6f64 656c 7372 2500 0000 7226 0000 0072  odelsr%...r&...r
+00003970: 0200 0201 06fe 723d 0000 004e 292b da08  ......r=...N)+..
+00003980: 6461 7465 7469 6d65 7202 0000 00da 0674  datetimer......t
+00003990: 7970 696e 6772 0300 0000 7204 0000 005a  ypingr....r....Z
+000039a0: 115f 6765 6e65 7261 7465 642e 6d6f 6465  ._generated.mode
+000039b0: 6c73 7206 0000 00da 066d 6f64 656c 7372  lsr......modelsr
+000039c0: 0700 0000 7208 0000 0072 0900 0000 7230  ....r....r....r0
+000039d0: 0000 0072 0b00 0000 720c 0000 0072 0d00  ...r....r....r..
+000039e0: 0000 720e 0000 0072 0f00 0000 7210 0000  ..r....r....r...
+000039f0: 0072 1100 0000 7212 0000 0072 1300 0000  .r....r....r....
+00003a00: 7214 0000 0072 1500 0000 7216 0000 0072  r....r....r....r
+00003a10: 1700 0000 7218 0000 0072 1900 0000 721a  ....r....r....r.
+00003a20: 0000 0072 1b00 0000 721c 0000 0072 1d00  ...r....r....r..
+00003a30: 0000 721e 0000 0072 1f00 0000 7220 0000  ..r....r....r ..
+00003a40: 0072 2100 0000 7222 0000 0072 2300 0000  .r!...r"...r#...
+00003a50: 7224 0000 0072 2500 0000 7226 0000 0072  r$...r%...r&...r
 00003a60: 2700 0000 7228 0000 0072 3d00 0000 722d  '...r(...r=...r-
 00003a70: 0000 0072 2d00 0000 722d 0000 0072 2e00  ...r-...r-...r..
 00003a80: 0000 da08 3c6d 6f64 756c 653e 1a00 0000  ....<module>....
-00003a90: 730c 0000 0010 010c 027c 1f0c 0114 0710  s........|......
+00003a90: 730c 0000 000c 0110 020c 0114 017c 2110  s............|!.
 00003aa0: 19                                       .
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_save_element_command_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_save_element_command_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 16181 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,84 +1,84 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 353f 0000  U.......=S.d5?..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 243f 0000  U..........d$?..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 da00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6403 6404 6c05  d.l.m.Z...d.d.l.
-00000050: 6d06 5a06 6d07 5a07 6d08 5a08 6d09 5a09  m.Z.m.Z.m.Z.m.Z.
-00000060: 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c 6d0d 5a0d  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d12 5a12 6d13 5a13 6d14 5a14 6d15 5a15  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d16 5a16 6d17 5a17 6d18 5a18 6d19 5a19  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d1a 5a1a 6d1b 5a1b 6d1c 5a1c 6d1d 5a1d  m.Z.m.Z.m.Z.m.Z.
-000000b0: 6d1e 5a1e 6d1f 5a1f 6d20 5a20 6d21 5a21  m.Z.m.Z.m Z m!Z!
-000000c0: 6d22 5a22 0100 6405 6406 6c23 6d24 5a24  m"Z"..d.d.l#m$Z$
-000000d0: 0100 6405 6407 6c25 6d26 5a26 6d27 5a27  ..d.d.l%m&Z&m'Z'
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6403 6404 6c05  m.Z.m.Z...d.d.l.
+00000050: 6d06 5a06 0100 6403 6405 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
+00000060: 6d09 5a09 6d0a 5a0a 0100 6406 6407 6c0b  m.Z.m.Z...d.d.l.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  m.Z.m.Z.m.Z.m.Z.
+000000c0: 6d20 5a20 6d21 5a21 6d22 5a22 6d23 5a23  m Z m!Z!m"Z"m#Z#
+000000d0: 6d24 5a24 6d25 5a25 6d26 5a26 6d27 5a27  m$Z$m%Z%m&Z&m'Z'
 000000e0: 6d28 5a28 0100 4700 6408 6409 8400 6409  m(Z(..G.d.d...d.
-000000f0: 6508 8303 5a29 4700 640a 640b 8400 640b  e...Z)G.d.d...d.
+000000f0: 650e 8303 5a29 4700 640a 640b 8400 640b  e...Z)G.d.d...d.
 00000100: 8302 5a2a 640c 5300 290d e900 0000 0029  ..Z*d.S.)......)
-00000110: 02da 044c 6973 74da 084f 7074 696f 6e61  ...List..Optiona
-00000120: 6c29 01da 0464 6174 65e9 0100 0000 291d  l)...date.....).
-00000130: da16 456c 656d 656e 7456 616c 7565 5369  ..ElementValueSi
-00000140: 6d70 6c65 5479 7065 da11 456c 656d 656e  mpleType..Elemen
-00000150: 7456 616c 7565 556e 696f 6eda 1854 6173  tValueUnion..Tas
-00000160: 6b45 6c65 6d65 6e74 5661 6c75 6541 6363  kElementValueAcc
-00000170: 6573 736f 72da 1161 6464 5f65 6c65 6d65  essor..add_eleme
-00000180: 6e74 5f76 616c 7565 da16 6164 645f 656c  nt_value..add_el
-00000190: 656d 656e 745f 7661 6c75 655f 6c69 7374  ement_value_list
-000001a0: da1a 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
-000001b0: 616c 7565 5f61 735f 6461 7465 da1a 6669  alue_as_date..fi
-000001c0: 6e64 5f65 6c65 6d65 6e74 5f76 616c 7565  nd_element_value
-000001d0: 5f61 735f 6469 6374 da1e 6669 6e64 5f65  _as_dict..find_e
-000001e0: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-000001f0: 646f 6375 6d65 6e74 da1b 6669 6e64 5f65  document..find_e
-00000200: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-00000210: 666c 6f61 74da 1f66 696e 645f 656c 656d  float..find_elem
-00000220: 656e 745f 7661 6c75 655f 6173 5f70 7269  ent_value_as_pri
-00000230: 6e63 6970 616c da19 6669 6e64 5f65 6c65  ncipal..find_ele
-00000240: 6d65 6e74 5f76 616c 7565 5f61 735f 7374  ment_value_as_st
-00000250: 72da 1967 6574 5f65 6c65 6d65 6e74 5f76  r..get_element_v
-00000260: 616c 7565 5f61 735f 6461 7465 da1e 6765  alue_as_date..ge
-00000270: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-00000280: 6173 5f64 6174 655f 6c69 7374 da19 6765  as_date_list..ge
-00000290: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000002a0: 6173 5f64 6963 74da 1e67 6574 5f65 6c65  as_dict..get_ele
-000002b0: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
-000002c0: 6374 5f6c 6973 74da 1d67 6574 5f65 6c65  ct_list..get_ele
-000002d0: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
-000002e0: 6375 6d65 6e74 da22 6765 745f 656c 656d  cument."get_elem
-000002f0: 656e 745f 7661 6c75 655f 6173 5f64 6f63  ent_value_as_doc
-00000300: 756d 656e 745f 6c69 7374 da1a 6765 745f  ument_list..get_
-00000310: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
-00000320: 5f66 6c6f 6174 da1f 6765 745f 656c 656d  _float..get_elem
-00000330: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
-00000340: 6174 5f6c 6973 74da 1e67 6574 5f65 6c65  at_list..get_ele
-00000350: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
-00000360: 696e 6369 7061 6cda 2367 6574 5f65 6c65  incipal.#get_ele
-00000370: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
-00000380: 696e 6369 7061 6c5f 6c69 7374 da18 6765  incipal_list..ge
-00000390: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
-000003a0: 6173 5f73 7472 da1d 6765 745f 656c 656d  as_str..get_elem
-000003b0: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
-000003c0: 5f6c 6973 74da 1767 6574 5f65 6c65 6d65  _list..get_eleme
-000003d0: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
-000003e0: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
-000003f0: 655f 7661 6c69 645f 6174 da11 7365 745f  e_valid_at..set_
-00000400: 656c 656d 656e 745f 7661 6c75 65da 1673  element_value..s
-00000410: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-00000420: 5f6c 6973 74da 1773 6574 5f65 6c65 6d65  _list..set_eleme
-00000430: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
-00000440: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
-00000450: 655f 7661 6c69 645f 6174 e902 0000 0029  e_valid_at.....)
-00000460: 01da 1054 6173 6b45 6c65 6d65 6e74 5661  ...TaskElementVa
-00000470: 6c75 6529 03da 1c54 6173 6b45 6c65 6d65  lue)...TaskEleme
-00000480: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
-00000490: 7465 6dda 1d54 6173 6b45 6c65 6d65 6e74  tem..TaskElement
-000004a0: 5661 6c75 6550 7269 6e63 6970 616c 4974  ValuePrincipalIt
-000004b0: 656d da16 5461 736b 5361 7665 456c 656d  em..TaskSaveElem
-000004c0: 656e 7443 6f6d 6d61 6e64 6300 0000 0000  entCommandc.....
+00000110: 01da 0464 6174 6529 02da 044c 6973 74da  ...date)...List.
+00000120: 084f 7074 696f 6e61 6ce9 0200 0000 2901  .Optional.....).
+00000130: da10 5461 736b 456c 656d 656e 7456 616c  ..TaskElementVal
+00000140: 7565 2903 da1c 5461 736b 456c 656d 656e  ue)...TaskElemen
+00000150: 7456 616c 7565 446f 6375 6d65 6e74 4974  tValueDocumentIt
+00000160: 656d da1d 5461 736b 456c 656d 656e 7456  em..TaskElementV
+00000170: 616c 7565 5072 696e 6369 7061 6c49 7465  aluePrincipalIte
+00000180: 6dda 1654 6173 6b53 6176 6545 6c65 6d65  m..TaskSaveEleme
+00000190: 6e74 436f 6d6d 616e 64e9 0100 0000 291d  ntCommand.....).
+000001a0: da16 456c 656d 656e 7456 616c 7565 5369  ..ElementValueSi
+000001b0: 6d70 6c65 5479 7065 da11 456c 656d 656e  mpleType..Elemen
+000001c0: 7456 616c 7565 556e 696f 6eda 1854 6173  tValueUnion..Tas
+000001d0: 6b45 6c65 6d65 6e74 5661 6c75 6541 6363  kElementValueAcc
+000001e0: 6573 736f 72da 1161 6464 5f65 6c65 6d65  essor..add_eleme
+000001f0: 6e74 5f76 616c 7565 da16 6164 645f 656c  nt_value..add_el
+00000200: 656d 656e 745f 7661 6c75 655f 6c69 7374  ement_value_list
+00000210: da1a 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
+00000220: 616c 7565 5f61 735f 6461 7465 da1a 6669  alue_as_date..fi
+00000230: 6e64 5f65 6c65 6d65 6e74 5f76 616c 7565  nd_element_value
+00000240: 5f61 735f 6469 6374 da1e 6669 6e64 5f65  _as_dict..find_e
+00000250: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
+00000260: 646f 6375 6d65 6e74 da1b 6669 6e64 5f65  document..find_e
+00000270: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
+00000280: 666c 6f61 74da 1f66 696e 645f 656c 656d  float..find_elem
+00000290: 656e 745f 7661 6c75 655f 6173 5f70 7269  ent_value_as_pri
+000002a0: 6e63 6970 616c da19 6669 6e64 5f65 6c65  ncipal..find_ele
+000002b0: 6d65 6e74 5f76 616c 7565 5f61 735f 7374  ment_value_as_st
+000002c0: 72da 1967 6574 5f65 6c65 6d65 6e74 5f76  r..get_element_v
+000002d0: 616c 7565 5f61 735f 6461 7465 da1e 6765  alue_as_date..ge
+000002e0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+000002f0: 6173 5f64 6174 655f 6c69 7374 da19 6765  as_date_list..ge
+00000300: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000310: 6173 5f64 6963 74da 1e67 6574 5f65 6c65  as_dict..get_ele
+00000320: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
+00000330: 6374 5f6c 6973 74da 1d67 6574 5f65 6c65  ct_list..get_ele
+00000340: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
+00000350: 6375 6d65 6e74 da22 6765 745f 656c 656d  cument."get_elem
+00000360: 656e 745f 7661 6c75 655f 6173 5f64 6f63  ent_value_as_doc
+00000370: 756d 656e 745f 6c69 7374 da1a 6765 745f  ument_list..get_
+00000380: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
+00000390: 5f66 6c6f 6174 da1f 6765 745f 656c 656d  _float..get_elem
+000003a0: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
+000003b0: 6174 5f6c 6973 74da 1e67 6574 5f65 6c65  at_list..get_ele
+000003c0: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
+000003d0: 696e 6369 7061 6cda 2367 6574 5f65 6c65  incipal.#get_ele
+000003e0: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
+000003f0: 696e 6369 7061 6c5f 6c69 7374 da18 6765  incipal_list..ge
+00000400: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000410: 6173 5f73 7472 da1d 6765 745f 656c 656d  as_str..get_elem
+00000420: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
+00000430: 5f6c 6973 74da 1767 6574 5f65 6c65 6d65  _list..get_eleme
+00000440: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
+00000450: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
+00000460: 655f 7661 6c69 645f 6174 da11 7365 745f  e_valid_at..set_
+00000470: 656c 656d 656e 745f 7661 6c75 65da 1673  element_value..s
+00000480: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000490: 5f6c 6973 74da 1773 6574 5f65 6c65 6d65  _list..set_eleme
+000004a0: 6e74 5f76 616c 7565 5f76 616c 6964 da1a  nt_value_valid..
+000004b0: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
+000004c0: 655f 7661 6c69 645f 6174 6300 0000 0000  e_valid_atc.....
 000004d0: 0000 0000 0000 0000 0000 0003 0000 0040  ...............@
 000004e0: 0000 0073 3e00 0000 6500 5a01 6400 5a02  ...s>...e.Z.d.Z.
 000004f0: 6503 6401 9c01 6402 6403 8404 5a04 6505  e.d...d.d...Z.e.
 00000500: 6506 1900 6404 9c01 6405 6406 8404 5a07  e...d...d.d...Z.
 00000510: 6505 6508 1900 6407 9c01 6408 6409 8404  e.e...d...d.d...
 00000520: 5a09 640a 5300 290b da1b 4375 7272 656e  Z.d.S.)...Curren
 00000530: 7445 6c65 6d65 6e74 5661 6c75 6541 6363  tElementValueAcc
@@ -90,50 +90,50 @@
 00000590: 0000 2902 da04 7365 6c66 722a 0000 00a9  ..)...selfr*....
 000005a0: 0072 2d00 0000 fa59 2f77 6f72 6b2f 6b75  .r-....Y/work/ku
 000005b0: 666c 6f77 2d73 646b 2d70 7974 686f 6e2f  flow-sdk-python/
 000005c0: 6b75 666c 6f77 2d72 6573 742f 6b75 666c  kuflow-rest/kufl
 000005d0: 6f77 5f72 6573 742f 7574 696c 732f 5f74  ow_rest/utils/_t
 000005e0: 6173 6b5f 7361 7665 5f65 6c65 6d65 6e74  ask_save_element
 000005f0: 5f63 6f6d 6d61 6e64 5f75 7469 6c73 2e70  _command_utils.p
-00000600: 79da 085f 5f69 6e69 745f 5f45 0000 0073  y..__init__E...s
+00000600: 79da 085f 5f69 6e69 745f 5f41 0000 0073  y..__init__A...s
 00000610: 0200 0000 0001 7a24 4375 7272 656e 7445  ......z$CurrentE
 00000620: 6c65 6d65 6e74 5661 6c75 6541 6363 6573  lementValueAcces
 00000630: 736f 722e 5f5f 696e 6974 5f5f 2901 da0e  sor.__init__)...
 00000640: 656c 656d 656e 745f 7661 6c75 6573 6302  element_valuesc.
 00000650: 0000 0000 0000 0000 0000 0002 0000 0002  ................
 00000660: 0000 0043 0000 0073 2200 0000 7400 7c01  ...C...s"...t.|.
 00000670: 8301 6401 6b02 7216 6400 7c00 6a01 5f02  ..d.k.r.d.|.j._.
 00000680: 6e08 7c01 7c00 6a01 5f02 6400 5300 2902  n.|.|.j._.d.S.).
 00000690: 4e72 0100 0000 2903 da03 6c65 6e72 2a00  Nr....)...lenr*.
 000006a0: 0000 7230 0000 0029 0272 2c00 0000 7230  ..r0...).r,...r0
 000006b0: 0000 0072 2d00 0000 722d 0000 0072 2e00  ...r-...r-...r..
 000006c0: 0000 da12 7365 745f 656c 656d 656e 745f  ....set_element_
-000006d0: 7661 6c75 6573 4800 0000 7306 0000 0000  valuesH...s.....
+000006d0: 7661 6c75 6573 4400 0000 7306 0000 0000  valuesD...s.....
 000006e0: 010c 010a 027a 2e43 7572 7265 6e74 456c  .....z.CurrentEl
 000006f0: 656d 656e 7456 616c 7565 4163 6365 7373  ementValueAccess
 00000700: 6f72 2e73 6574 5f65 6c65 6d65 6e74 5f76  or.set_element_v
 00000710: 616c 7565 7329 01da 0672 6574 7572 6e63  alues)...returnc
 00000720: 0100 0000 0000 0000 0000 0000 0100 0000  ................
 00000730: 0200 0000 4300 0000 7318 0000 007c 006a  ....C...s....|.j
 00000740: 006a 0164 006b 0872 1067 0053 007c 006a  .j.d.k.r.g.S.|.j
 00000750: 006a 0153 0072 2b00 0000 a902 722a 0000  .j.S.r+.....r*..
 00000760: 0072 3000 0000 2901 722c 0000 0072 2d00  .r0...).r,...r-.
 00000770: 0000 722d 0000 0072 2e00 0000 da12 6765  ..r-...r......ge
 00000780: 745f 656c 656d 656e 745f 7661 6c75 6573  t_element_values
-00000790: 4e00 0000 7306 0000 0000 010c 0104 027a  N...s..........z
+00000790: 4a00 0000 7306 0000 0000 010c 0104 027a  J...s..........z
 000007a0: 2e43 7572 7265 6e74 456c 656d 656e 7456  .CurrentElementV
 000007b0: 616c 7565 4163 6365 7373 6f72 2e67 6574  alueAccessor.get
 000007c0: 5f65 6c65 6d65 6e74 5f76 616c 7565 734e  _element_valuesN
 000007d0: 290a da08 5f5f 6e61 6d65 5f5f da0a 5f5f  )...__name__..__
 000007e0: 6d6f 6475 6c65 5f5f da0c 5f5f 7175 616c  module__..__qual
-000007f0: 6e61 6d65 5f5f 7227 0000 0072 2f00 0000  name__r'...r/...
-00000800: 7202 0000 0072 0700 0000 7232 0000 0072  r....r....r2...r
-00000810: 2400 0000 7235 0000 0072 2d00 0000 722d  $...r5...r-...r-
+000007f0: 6e61 6d65 5f5f 7209 0000 0072 2f00 0000  name__r....r/...
+00000800: 7203 0000 0072 0c00 0000 7232 0000 0072  r....r....r2...r
+00000810: 0600 0000 7235 0000 0072 2d00 0000 722d  ....r5...r-...r-
 00000820: 0000 0072 2d00 0000 722e 0000 0072 2800  ...r-...r....r(.
-00000830: 0000 4400 0000 7306 0000 0008 010e 0312  ..D...s.........
+00000830: 0000 4000 0000 7306 0000 0008 010e 0312  ..@...s.........
 00000840: 0672 2800 0000 6300 0000 0000 0000 0000  .r(...c.........
 00000850: 0000 0000 0000 0006 0000 0040 0000 0073  ...........@...s
 00000860: 8002 0000 6500 5a01 6400 5a02 6503 6504  ....e.Z.d.Z.e.e.
 00000870: 6505 6401 9c02 6402 6403 8404 8301 5a06  e.d...d.d.....Z.
 00000880: 6503 6504 6507 6505 6404 9c03 6405 6406  e.e.e.e.d...d.d.
 00000890: 8404 8301 5a08 6503 6504 6509 6505 1900  ....Z.e.e.e.e...
 000008a0: 6504 6407 9c03 6408 6409 8404 8301 5a0a  e.d...d.d.....Z.
@@ -189,17 +189,17 @@
 00000bc0: 6e74 2063 6f6d 6d61 6e64 2e0a 0a20 2020  nt command...   
 00000bd0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00000be0: 2020 2020 2020 2020 2020 5472 7565 2069            True i
 00000bf0: 6620 616c 6c20 7265 6c61 7465 6420 7661  f all related va
 00000c00: 6c69 6420 7661 6c75 6573 2061 7265 2054  lid values are T
 00000c10: 5255 452c 206f 7468 6572 7769 7365 2046  RUE, otherwise F
 00000c20: 616c 7365 2e0a 2020 2020 2020 2020 2902  alse..        ).
-00000c30: 721d 0000 0072 2800 0000 7229 0000 0072  r....r(...r)...r
-00000c40: 2d00 0000 722d 0000 0072 2e00 0000 721d  -...r-...r....r.
-00000c50: 0000 0056 0000 0073 0200 0000 000b 7a33  ...V...s......z3
+00000c30: 7222 0000 0072 2800 0000 7229 0000 0072  r"...r(...r)...r
+00000c40: 2d00 0000 722d 0000 0072 2e00 0000 7222  -...r-...r....r"
+00000c50: 0000 0052 0000 0073 0200 0000 000b 7a33  ...R...s......z3
 00000c60: 5461 736b 5361 7665 456c 656d 656e 7443  TaskSaveElementC
 00000c70: 6f6d 6d61 6e64 5574 696c 732e 6765 745f  ommandUtils.get_
 00000c80: 656c 656d 656e 745f 7661 6c75 655f 7661  element_value_va
 00000c90: 6c69 6429 0372 2a00 0000 da05 696e 6465  lid).r*.....inde
 00000ca0: 7872 3300 0000 6302 0000 0000 0000 0000  xr3...c.........
 00000cb0: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00000cc0: 0e00 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
@@ -218,18 +218,18 @@
 00000d90: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 00000da0: 2069 6e64 6578 2e0a 0a20 2020 2020 2020   index...       
 00000db0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00000dc0: 2020 2020 2020 5468 6520 7265 7175 6573        The reques
 00000dd0: 7465 6420 7661 6c69 6420 7661 6c75 6520  ted valid value 
 00000de0: 6966 2069 7420 6578 6973 7473 2c20 6f74  if it exists, ot
 00000df0: 6865 7277 6973 6520 4e6f 6e65 2e0a 2020  herwise None..  
-00000e00: 2020 2020 2020 2902 721e 0000 0072 2800        ).r....r(.
+00000e00: 2020 2020 2020 2902 7223 0000 0072 2800        ).r#...r(.
 00000e10: 0000 2902 722a 0000 0072 3a00 0000 722d  ..).r*...r:...r-
-00000e20: 0000 0072 2d00 0000 722e 0000 0072 1e00  ...r-...r....r..
-00000e30: 0000 6300 0000 7302 0000 0000 107a 3654  ..c...s......z6T
+00000e20: 0000 0072 2d00 0000 722e 0000 0072 2300  ...r-...r....r#.
+00000e30: 0000 5f00 0000 7302 0000 0000 107a 3654  .._...s......z6T
 00000e40: 6173 6b53 6176 6545 6c65 6d65 6e74 436f  askSaveElementCo
 00000e50: 6d6d 616e 6455 7469 6c73 2e67 6574 5f65  mmandUtils.get_e
 00000e60: 6c65 6d65 6e74 5f76 616c 7565 5f76 616c  lement_value_val
 00000e70: 6964 5f61 7429 0372 2a00 0000 da05 7661  id_at).r*.....va
 00000e80: 6c69 6472 3300 0000 6302 0000 0000 0000  lidr3...c.......
 00000e90: 0000 0000 0002 0000 0003 0000 0043 0000  .............C..
 00000ea0: 0073 1200 0000 7400 7401 7c00 8301 7c01  .s....t.t.|...|.
@@ -244,18 +244,18 @@
 00000f30: 7461 736b 2073 6176 6520 656c 656d 656e  task save elemen
 00000f40: 7420 636f 6d6d 616e 642e 0a20 2020 2020  t command..     
 00000f50: 2020 2020 2020 2076 616c 6964 3a20 5468         valid: Th
 00000f60: 6520 7661 6c69 6420 7661 6c75 652e 0a0a  e valid value...
 00000f70: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00000f80: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00000f90: 2070 6173 7365 6420 7461 736b 2e0a 2020   passed task..  
-00000fa0: 2020 2020 2020 2902 7221 0000 0072 2800        ).r!...r(.
+00000fa0: 2020 2020 2020 2902 7226 0000 0072 2800        ).r&...r(.
 00000fb0: 0000 2902 722a 0000 0072 3b00 0000 722d  ..).r*...r;...r-
-00000fc0: 0000 0072 2d00 0000 722e 0000 0072 2100  ...r-...r....r!.
-00000fd0: 0000 7500 0000 7304 0000 0000 0e0e 027a  ..u...s........z
+00000fc0: 0000 0072 2d00 0000 722e 0000 0072 2600  ...r-...r....r&.
+00000fd0: 0000 7100 0000 7304 0000 0000 0e0e 027a  ..q...s........z
 00000fe0: 3354 6173 6b53 6176 6545 6c65 6d65 6e74  3TaskSaveElement
 00000ff0: 436f 6d6d 616e 6455 7469 6c73 2e73 6574  CommandUtils.set
 00001000: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
 00001010: 616c 6964 2904 722a 0000 0072 3b00 0000  alid).r*...r;...
 00001020: 723a 0000 0072 3300 0000 6303 0000 0000  r:...r3...c.....
 00001030: 0000 0000 0000 0003 0000 0004 0000 0043  ...............C
 00001040: 0000 0073 1400 0000 7400 7401 7c00 8301  ...s....t.t.|...
@@ -274,18 +274,18 @@
 00001110: 2076 616c 6964 2076 616c 7565 2e0a 2020   valid value..  
 00001120: 2020 2020 2020 2020 2020 696e 6465 783a            index:
 00001130: 2054 6865 2065 6c65 6d65 6e74 2076 616c   The element val
 00001140: 7565 2069 6e64 6578 2e0a 0a20 2020 2020  ue index...     
 00001150: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001160: 2020 2020 2020 2020 5468 6520 7061 7373          The pass
 00001170: 6564 2074 6173 6b2e 0a20 2020 2020 2020  ed task..       
-00001180: 2029 0272 2200 0000 7228 0000 0029 0372   ).r"...r(...).r
+00001180: 2029 0272 2700 0000 7228 0000 0029 0372   ).r'...r(...).r
 00001190: 2a00 0000 723b 0000 0072 3a00 0000 722d  *...r;...r:...r-
-000011a0: 0000 0072 2d00 0000 722e 0000 0072 2200  ...r-...r....r".
-000011b0: 0000 8700 0000 7304 0000 0000 0f10 027a  ......s........z
+000011a0: 0000 0072 2d00 0000 722e 0000 0072 2700  ...r-...r....r'.
+000011b0: 0000 8300 0000 7304 0000 0000 0f10 027a  ......s........z
 000011c0: 3654 6173 6b53 6176 6545 6c65 6d65 6e74  6TaskSaveElement
 000011d0: 436f 6d6d 616e 6455 7469 6c73 2e73 6574  CommandUtils.set
 000011e0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
 000011f0: 616c 6964 5f61 744e 2903 722a 0000 00da  alid_atN).r*....
 00001200: 0d65 6c65 6d65 6e74 5f76 616c 7565 7233  .element_valuer3
 00001210: 0000 0063 0200 0000 0000 0000 0000 0000  ...c............
 00001220: 0200 0000 0300 0000 4300 0000 7312 0000  ........C...s...
@@ -304,17 +304,17 @@
 000012f0: 2049 6620 7468 6520 7661 6c75 6520 6973   If the value is
 00001300: 204e 6f6e 652c 2061 6c6c 2063 7572 7265   None, all curre
 00001310: 6e74 2076 616c 7565 7320 6172 6520 7265  nt values are re
 00001320: 6d6f 7665 642e 0a0a 2020 2020 2020 2020  moved...        
 00001330: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00001340: 2020 2020 2054 6865 2070 6173 7365 6420       The passed 
 00001350: 7461 736b 2e0a 2020 2020 2020 2020 2902  task..        ).
-00001360: 721f 0000 0072 2800 0000 a902 722a 0000  r....r(.....r*..
+00001360: 7224 0000 0072 2800 0000 a902 722a 0000  r$...r(.....r*..
 00001370: 0072 3c00 0000 722d 0000 0072 2d00 0000  .r<...r-...r-...
-00001380: 722e 0000 0072 1f00 0000 9a00 0000 7304  r....r........s.
+00001380: 722e 0000 0072 2400 0000 9600 0000 7304  r....r$.......s.
 00001390: 0000 0000 0e0e 027a 2d54 6173 6b53 6176  .......z-TaskSav
 000013a0: 6545 6c65 6d65 6e74 436f 6d6d 616e 6455  eElementCommandU
 000013b0: 7469 6c73 2e73 6574 5f65 6c65 6d65 6e74  tils.set_element
 000013c0: 5f76 616c 7565 2903 722a 0000 0072 3000  _value).r*...r0.
 000013d0: 0000 7233 0000 0063 0200 0000 0000 0000  ..r3...c........
 000013e0: 0000 0000 0200 0000 0300 0000 4300 0000  ............C...
 000013f0: 7312 0000 0074 0074 017c 0083 017c 0183  s....t.t.|...|..
@@ -332,18 +332,18 @@
 000014b0: 616c 7565 2e20 4966 2074 6865 2076 616c  alue. If the val
 000014c0: 7565 2069 7320 4e6f 6e65 206f 7220 656d  ue is None or em
 000014d0: 7074 792c 2061 6c6c 2063 7572 7265 6e74  pty, all current
 000014e0: 2076 616c 7565 7320 6172 6520 7265 6d6f   values are remo
 000014f0: 7665 642e 0a0a 2020 2020 2020 2020 5265  ved...        Re
 00001500: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00001510: 2020 2054 6865 2070 6173 7365 6420 7461     The passed ta
-00001520: 736b 2e0a 2020 2020 2020 2020 2902 7220  sk..        ).r 
+00001520: 736b 2e0a 2020 2020 2020 2020 2902 7225  sk..        ).r%
 00001530: 0000 0072 2800 0000 7234 0000 0072 2d00  ...r(...r4...r-.
-00001540: 0000 722d 0000 0072 2e00 0000 7220 0000  ..r-...r....r ..
-00001550: 00ac 0000 0073 0400 0000 000e 0e02 7a32  .....s........z2
+00001540: 0000 722d 0000 0072 2e00 0000 7225 0000  ..r-...r....r%..
+00001550: 00a8 0000 0073 0400 0000 000e 0e02 7a32  .....s........z2
 00001560: 5461 736b 5361 7665 456c 656d 656e 7443  TaskSaveElementC
 00001570: 6f6d 6d61 6e64 5574 696c 732e 7365 745f  ommandUtils.set_
 00001580: 656c 656d 656e 745f 7661 6c75 655f 6c69  element_value_li
 00001590: 7374 6302 0000 0000 0000 0000 0000 0002  stc.............
 000015a0: 0000 0003 0000 0043 0000 0073 1200 0000  .......C...s....
 000015b0: 7400 7401 7c00 8301 7c01 8302 0100 7c00  t.t.|...|.....|.
 000015c0: 5300 2901 6114 0100 000a 2020 2020 2020  S.).a.....      
@@ -360,17 +360,17 @@
 00001670: 4966 2074 6865 2076 616c 7565 2069 7320  If the value is 
 00001680: 4e6f 6e65 2c20 616c 6c20 6375 7272 656e  None, all curren
 00001690: 7420 7661 6c75 6573 2061 7265 2072 656d  t values are rem
 000016a0: 6f76 6564 2e0a 0a20 2020 2020 2020 2052  oved...        R
 000016b0: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 000016c0: 2020 2020 5468 6520 7061 7373 6564 2074      The passed t
 000016d0: 6173 6b2e 0a20 2020 2020 2020 2029 0272  ask..        ).r
-000016e0: 0900 0000 7228 0000 0072 3d00 0000 722d  ....r(...r=...r-
-000016f0: 0000 0072 2d00 0000 722e 0000 0072 0900  ...r-...r....r..
-00001700: 0000 be00 0000 7304 0000 0000 0e0e 027a  ......s........z
+000016e0: 0e00 0000 7228 0000 0072 3d00 0000 722d  ....r(...r=...r-
+000016f0: 0000 0072 2d00 0000 722e 0000 0072 0e00  ...r-...r....r..
+00001700: 0000 ba00 0000 7304 0000 0000 0e0e 027a  ......s........z
 00001710: 2d54 6173 6b53 6176 6545 6c65 6d65 6e74  -TaskSaveElement
 00001720: 436f 6d6d 616e 6455 7469 6c73 2e61 6464  CommandUtils.add
 00001730: 5f65 6c65 6d65 6e74 5f76 616c 7565 6302  _element_valuec.
 00001740: 0000 0000 0000 0000 0000 0002 0000 0003  ................
 00001750: 0000 0043 0000 0073 1200 0000 7400 7401  ...C...s....t.t.
 00001760: 7c00 8301 7c01 8302 0100 7c00 5300 2901  |...|.....|.S.).
 00001770: 612e 0100 000a 2020 2020 2020 2020 4164  a.....        Ad
@@ -388,17 +388,17 @@
 00001830: 6520 6f72 2065 6d70 7479 2c20 616c 6c20  e or empty, all 
 00001840: 6375 7272 656e 7420 7661 6c75 6573 2061  current values a
 00001850: 7265 2072 656d 6f76 6564 2e0a 0a20 2020  re removed...   
 00001860: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00001870: 2020 2020 2020 2020 2020 5468 6520 7061            The pa
 00001880: 7373 6564 206d 6f64 656c 2072 656c 6174  ssed model relat
 00001890: 6564 206f 626a 6563 742e 0a20 2020 2020  ed object..     
-000018a0: 2020 2029 0272 0a00 0000 7228 0000 0072     ).r....r(...r
+000018a0: 2020 2029 0272 0f00 0000 7228 0000 0072     ).r....r(...r
 000018b0: 3400 0000 722d 0000 0072 2d00 0000 722e  4...r-...r-...r.
-000018c0: 0000 0072 0a00 0000 d000 0000 7304 0000  ...r........s...
+000018c0: 0000 0072 0f00 0000 cc00 0000 7304 0000  ...r........s...
 000018d0: 0000 0e0e 027a 3254 6173 6b53 6176 6545  .....z2TaskSaveE
 000018e0: 6c65 6d65 6e74 436f 6d6d 616e 6455 7469  lementCommandUti
 000018f0: 6c73 2e61 6464 5f65 6c65 6d65 6e74 5f76  ls.add_element_v
 00001900: 616c 7565 5f6c 6973 7463 0100 0000 0000  alue_listc......
 00001910: 0000 0000 0000 0100 0000 0300 0000 4300  ..............C.
 00001920: 0000 730c 0000 0074 0074 017c 0083 0183  ..s....t.t.|....
 00001930: 0153 0029 017a bd0a 2020 2020 2020 2020  .S.).z..        
@@ -409,17 +409,17 @@
 00001980: 7665 5f65 6c65 6d65 6e74 5f63 6f6d 6d61  ve_element_comma
 00001990: 6e64 3a20 5468 6520 7461 736b 2073 6176  nd: The task sav
 000019a0: 6520 656c 656d 656e 7420 636f 6d6d 616e  e element comman
 000019b0: 640a 0a20 2020 2020 2020 2052 6574 7572  d..        Retur
 000019c0: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 000019d0: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 000019e0: 6520 6173 2061 2073 7472 2e0a 2020 2020  e as a str..    
-000019f0: 2020 2020 2902 721b 0000 0072 2800 0000      ).r....r(...
+000019f0: 2020 2020 2902 7220 0000 0072 2800 0000      ).r ...r(...
 00001a00: 7229 0000 0072 2d00 0000 722d 0000 0072  r)...r-...r-...r
-00001a10: 2e00 0000 721b 0000 00e2 0000 0073 0200  ....r........s..
+00001a10: 2e00 0000 7220 0000 00de 0000 0073 0200  ....r .......s..
 00001a20: 0000 000b 7a34 5461 736b 5361 7665 456c  ....z4TaskSaveEl
 00001a30: 656d 656e 7443 6f6d 6d61 6e64 5574 696c  ementCommandUtil
 00001a40: 732e 6765 745f 656c 656d 656e 745f 7661  s.get_element_va
 00001a50: 6c75 655f 6173 5f73 7472 6301 0000 0000  lue_as_strc.....
 00001a60: 0000 0000 0000 0001 0000 0003 0000 0043  ...............C
 00001a70: 0000 0073 0c00 0000 7400 7401 7c00 8301  ...s....t.t.|...
 00001a80: 8301 5300 2901 7ac5 0a20 2020 2020 2020  ..S.).z..       
@@ -431,17 +431,17 @@
 00001ae0: 6e74 5f63 6f6d 6d61 6e64 3a20 5468 6520  nt_command: The 
 00001af0: 7461 736b 2073 6176 6520 656c 656d 656e  task save elemen
 00001b00: 7420 636f 6d6d 616e 642e 0a0a 2020 2020  t command...    
 00001b10: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00001b20: 2020 2020 2020 2020 2054 6865 2065 6c65           The ele
 00001b30: 6d65 6e74 2076 616c 7565 2061 7320 6120  ment value as a 
 00001b40: 7374 722e 0a20 2020 2020 2020 2029 0272  str..        ).r
-00001b50: 1000 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
-00001b60: 0000 0072 2d00 0000 722e 0000 0072 1000  ...r-...r....r..
-00001b70: 0000 ef00 0000 7302 0000 0000 0b7a 3554  ......s......z5T
+00001b50: 1500 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
+00001b60: 0000 0072 2d00 0000 722e 0000 0072 1500  ...r-...r....r..
+00001b70: 0000 eb00 0000 7302 0000 0000 0b7a 3554  ......s......z5T
 00001b80: 6173 6b53 6176 6545 6c65 6d65 6e74 436f  askSaveElementCo
 00001b90: 6d6d 616e 6455 7469 6c73 2e66 696e 645f  mmandUtils.find_
 00001ba0: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
 00001bb0: 5f73 7472 6301 0000 0000 0000 0000 0000  _strc...........
 00001bc0: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 00001bd0: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
 00001be0: 7ad0 0a20 2020 2020 2020 2054 7279 2074  z..        Try t
@@ -453,17 +453,17 @@
 00001c40: 745f 636f 6d6d 616e 643a 2054 6865 2074  t_command: The t
 00001c50: 6173 6b20 7361 7665 2065 6c65 6d65 6e74  ask save element
 00001c60: 2063 6f6d 6d61 6e64 2e0a 0a20 2020 2020   command...     
 00001c70: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001c80: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00001c90: 656e 7420 7661 6c75 6573 2061 7320 6120  ent values as a 
 00001ca0: 7374 7220 6c69 7374 2e0a 2020 2020 2020  str list..      
-00001cb0: 2020 2902 721c 0000 0072 2800 0000 7229    ).r....r(...r)
+00001cb0: 2020 2902 7221 0000 0072 2800 0000 7229    ).r!...r(...r)
 00001cc0: 0000 0072 2d00 0000 722d 0000 0072 2e00  ...r-...r-...r..
-00001cd0: 0000 721c 0000 00fc 0000 0073 0200 0000  ..r........s....
+00001cd0: 0000 7221 0000 00f8 0000 0073 0200 0000  ..r!.......s....
 00001ce0: 000b 7a39 5461 736b 5361 7665 456c 656d  ..z9TaskSaveElem
 00001cf0: 656e 7443 6f6d 6d61 6e64 5574 696c 732e  entCommandUtils.
 00001d00: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 00001d10: 655f 6173 5f73 7472 5f6c 6973 7463 0100  e_as_str_listc..
 00001d20: 0000 0000 0000 0000 0000 0100 0000 0300  ................
 00001d30: 0000 4300 0000 730c 0000 0074 0074 017c  ..C...s....t.t.|
 00001d40: 0083 0183 0153 0029 017a c20a 2020 2020  .....S.).z..    
@@ -475,17 +475,17 @@
 00001da0: 5f63 6f6d 6d61 6e64 3a20 5468 6520 7461  _command: The ta
 00001db0: 736b 2073 6176 6520 656c 656d 656e 7420  sk save element 
 00001dc0: 636f 6d6d 616e 642e 0a0a 2020 2020 2020  command...      
 00001dd0: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00001de0: 2020 2020 2020 2054 6865 2065 6c65 6d65         The eleme
 00001df0: 6e74 2076 616c 7565 2061 7320 6120 666c  nt value as a fl
 00001e00: 6f61 742e 0a20 2020 2020 2020 2029 0272  oat..        ).r
-00001e10: 1700 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
-00001e20: 0000 0072 2d00 0000 722e 0000 0072 1700  ...r-...r....r..
-00001e30: 0000 0901 0000 7302 0000 0000 0b7a 3654  ......s......z6T
+00001e10: 1c00 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
+00001e20: 0000 0072 2d00 0000 722e 0000 0072 1c00  ...r-...r....r..
+00001e30: 0000 0501 0000 7302 0000 0000 0b7a 3654  ......s......z6T
 00001e40: 6173 6b53 6176 6545 6c65 6d65 6e74 436f  askSaveElementCo
 00001e50: 6d6d 616e 6455 7469 6c73 2e67 6574 5f65  mmandUtils.get_e
 00001e60: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00001e70: 666c 6f61 7463 0100 0000 0000 0000 0000  floatc..........
 00001e80: 0000 0100 0000 0300 0000 4300 0000 730c  ..........C...s.
 00001e90: 0000 0074 0074 017c 0083 0183 0153 0029  ...t.t.|.....S.)
 00001ea0: 017a c90a 2020 2020 2020 2020 5472 7920  .z..        Try 
@@ -496,18 +496,18 @@
 00001ef0: 736b 5f73 6176 655f 656c 656d 656e 745f  sk_save_element_
 00001f00: 636f 6d6d 616e 643a 2054 6865 2074 6173  command: The tas
 00001f10: 6b20 7361 7665 2065 6c65 6d65 6e74 2063  k save element c
 00001f20: 6f6d 6d61 6e64 2e0a 0a20 2020 2020 2020  ommand...       
 00001f30: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001f40: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00001f50: 7420 7661 6c75 6520 6173 2061 2066 6c6f  t value as a flo
-00001f60: 6174 2e0a 2020 2020 2020 2020 2902 720e  at..        ).r.
+00001f60: 6174 2e0a 2020 2020 2020 2020 2902 7213  at..        ).r.
 00001f70: 0000 0072 2800 0000 7229 0000 0072 2d00  ...r(...r)...r-.
-00001f80: 0000 722d 0000 0072 2e00 0000 720e 0000  ..r-...r....r...
-00001f90: 0016 0100 0073 0200 0000 000b 7a37 5461  .....s......z7Ta
+00001f80: 0000 722d 0000 0072 2e00 0000 7213 0000  ..r-...r....r...
+00001f90: 0012 0100 0073 0200 0000 000b 7a37 5461  .....s......z7Ta
 00001fa0: 736b 5361 7665 456c 656d 656e 7443 6f6d  skSaveElementCom
 00001fb0: 6d61 6e64 5574 696c 732e 6669 6e64 5f65  mandUtils.find_e
 00001fc0: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00001fd0: 666c 6f61 7463 0100 0000 0000 0000 0000  floatc..........
 00001fe0: 0000 0100 0000 0300 0000 4300 0000 730c  ..........C...s.
 00001ff0: 0000 0074 0074 017c 0083 0183 0153 0029  ...t.t.|.....S.)
 00002000: 017a c90a 2020 2020 2020 2020 4765 7420  .z..        Get 
@@ -518,18 +518,18 @@
 00002050: 736b 5f73 6176 655f 656c 656d 656e 745f  sk_save_element_
 00002060: 636f 6d6d 616e 643a 2054 6865 2074 6173  command: The tas
 00002070: 6b20 7361 7665 2065 6c65 6d65 6e74 2063  k save element c
 00002080: 6f6d 6d61 6e64 2e0a 0a20 2020 2020 2020  ommand...       
 00002090: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 000020a0: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 000020b0: 7420 7661 6c75 6520 6173 2061 2066 6c6f  t value as a flo
-000020c0: 6174 2e0a 2020 2020 2020 2020 2902 7218  at..        ).r.
+000020c0: 6174 2e0a 2020 2020 2020 2020 2902 721d  at..        ).r.
 000020d0: 0000 0072 2800 0000 7229 0000 0072 2d00  ...r(...r)...r-.
-000020e0: 0000 722d 0000 0072 2e00 0000 7218 0000  ..r-...r....r...
-000020f0: 0023 0100 0073 0200 0000 000b 7a3b 5461  .#...s......z;Ta
+000020e0: 0000 722d 0000 0072 2e00 0000 721d 0000  ..r-...r....r...
+000020f0: 001f 0100 0073 0200 0000 000b 7a3b 5461  .....s......z;Ta
 00002100: 736b 5361 7665 456c 656d 656e 7443 6f6d  skSaveElementCom
 00002110: 6d61 6e64 5574 696c 732e 6765 745f 656c  mandUtils.get_el
 00002120: 656d 656e 745f 7661 6c75 655f 6173 5f66  ement_value_as_f
 00002130: 6c6f 6174 5f6c 6973 7463 0100 0000 0000  loat_listc......
 00002140: 0000 0000 0000 0100 0000 0300 0000 4300  ..............C.
 00002150: 0000 730c 0000 0074 0074 017c 0083 0183  ..s....t.t.|....
 00002160: 0153 0029 017a c00a 2020 2020 2020 2020  .S.).z..        
@@ -540,17 +540,17 @@
 000021b0: 6176 655f 656c 656d 656e 745f 636f 6d6d  ave_element_comm
 000021c0: 616e 643a 2054 6865 2074 6173 6b20 7361  and: The task sa
 000021d0: 7665 2065 6c65 6d65 6e74 2063 6f6d 6d61  ve element comma
 000021e0: 6e64 2e0a 0a20 2020 2020 2020 2052 6574  nd...        Ret
 000021f0: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00002200: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 00002210: 6c75 6520 6173 2061 2064 6174 652e 0a20  lue as a date.. 
-00002220: 2020 2020 2020 2029 0272 1100 0000 7228         ).r....r(
+00002220: 2020 2020 2020 2029 0272 1600 0000 7228         ).r....r(
 00002230: 0000 0072 2900 0000 722d 0000 0072 2d00  ...r)...r-...r-.
-00002240: 0000 722e 0000 0072 1100 0000 3001 0000  ..r....r....0...
+00002240: 0000 722e 0000 0072 1600 0000 2c01 0000  ..r....r....,...
 00002250: 7302 0000 0000 0b7a 3554 6173 6b53 6176  s......z5TaskSav
 00002260: 6545 6c65 6d65 6e74 436f 6d6d 616e 6455  eElementCommandU
 00002270: 7469 6c73 2e67 6574 5f65 6c65 6d65 6e74  tils.get_element
 00002280: 5f76 616c 7565 5f61 735f 6461 7465 6301  _value_as_datec.
 00002290: 0000 0000 0000 0000 0000 0001 0000 0003  ................
 000022a0: 0000 0043 0000 0073 0c00 0000 7400 7401  ...C...s....t.t.
 000022b0: 7c00 8301 8301 5300 2901 7ac8 0a20 2020  |.....S.).z..   
@@ -562,17 +562,17 @@
 00002310: 5f65 6c65 6d65 6e74 5f63 6f6d 6d61 6e64  _element_command
 00002320: 3a20 5468 6520 7461 736b 2073 6176 6520  : The task save 
 00002330: 656c 656d 656e 7420 636f 6d6d 616e 642e  element command.
 00002340: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 00002350: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 00002360: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 00002370: 2061 7320 6120 6461 7465 2e0a 2020 2020   as a date..    
-00002380: 2020 2020 2902 720b 0000 0072 2800 0000      ).r....r(...
+00002380: 2020 2020 2902 7210 0000 0072 2800 0000      ).r....r(...
 00002390: 7229 0000 0072 2d00 0000 722d 0000 0072  r)...r-...r-...r
-000023a0: 2e00 0000 720b 0000 003d 0100 0073 0200  ....r....=...s..
+000023a0: 2e00 0000 7210 0000 0039 0100 0073 0200  ....r....9...s..
 000023b0: 0000 000b 7a36 5461 736b 5361 7665 456c  ....z6TaskSaveEl
 000023c0: 656d 656e 7443 6f6d 6d61 6e64 5574 696c  ementCommandUtil
 000023d0: 732e 6669 6e64 5f65 6c65 6d65 6e74 5f76  s.find_element_v
 000023e0: 616c 7565 5f61 735f 6461 7465 6301 0000  alue_as_datec...
 000023f0: 0000 0000 0000 0000 0001 0000 0003 0000  ................
 00002400: 0043 0000 0073 0c00 0000 7400 7401 7c00  .C...s....t.t.|.
 00002410: 8301 8301 5300 2901 7ac9 0a20 2020 2020  ....S.).z..     
@@ -584,17 +584,17 @@
 00002470: 656e 745f 636f 6d6d 616e 643a 2054 6865  ent_command: The
 00002480: 2074 6173 6b20 7361 7665 2065 6c65 6d65   task save eleme
 00002490: 6e74 2063 6f6d 6d61 6e64 2e0a 0a20 2020  nt command...   
 000024a0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 000024b0: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 000024c0: 656d 656e 7420 7661 6c75 6573 2061 7320  ement values as 
 000024d0: 6461 7465 206c 6973 742e 0a20 2020 2020  date list..     
-000024e0: 2020 2029 0272 1200 0000 7228 0000 0072     ).r....r(...r
+000024e0: 2020 2029 0272 1700 0000 7228 0000 0072     ).r....r(...r
 000024f0: 2900 0000 722d 0000 0072 2d00 0000 722e  )...r-...r-...r.
-00002500: 0000 0072 1200 0000 4a01 0000 7302 0000  ...r....J...s...
+00002500: 0000 0072 1700 0000 4601 0000 7302 0000  ...r....F...s...
 00002510: 0000 0b7a 3a54 6173 6b53 6176 6545 6c65  ...z:TaskSaveEle
 00002520: 6d65 6e74 436f 6d6d 616e 6455 7469 6c73  mentCommandUtils
 00002530: 2e67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
 00002540: 7565 5f61 735f 6461 7465 5f6c 6973 7463  ue_as_date_listc
 00002550: 0100 0000 0000 0000 0000 0000 0100 0000  ................
 00002560: 0300 0000 4300 0000 730c 0000 0074 0074  ....C...s....t.t
 00002570: 017c 0083 0183 0153 0029 017a c00a 2020  .|.....S.).z..  
@@ -606,17 +606,17 @@
 000025d0: 745f 636f 6d6d 616e 643a 2054 6865 2074  t_command: The t
 000025e0: 6173 6b20 7361 7665 2065 6c65 6d65 6e74  ask save element
 000025f0: 2063 6f6d 6d61 6e64 2e0a 0a20 2020 2020   command...     
 00002600: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002610: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00002620: 656e 7420 7661 6c75 6520 6173 2061 2064  ent value as a d
 00002630: 6963 742e 0a20 2020 2020 2020 2029 0272  ict..        ).r
-00002640: 1300 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
-00002650: 0000 0072 2d00 0000 722e 0000 0072 1300  ...r-...r....r..
-00002660: 0000 5701 0000 7302 0000 0000 0b7a 3554  ..W...s......z5T
+00002640: 1800 0000 7228 0000 0072 2900 0000 722d  ....r(...r)...r-
+00002650: 0000 0072 2d00 0000 722e 0000 0072 1800  ...r-...r....r..
+00002660: 0000 5301 0000 7302 0000 0000 0b7a 3554  ..S...s......z5T
 00002670: 6173 6b53 6176 6545 6c65 6d65 6e74 436f  askSaveElementCo
 00002680: 6d6d 616e 6455 7469 6c73 2e67 6574 5f65  mmandUtils.get_e
 00002690: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 000026a0: 6469 6374 6301 0000 0000 0000 0000 0000  dictc...........
 000026b0: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 000026c0: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
 000026d0: 7ac7 0a20 2020 2020 2020 2054 7279 2074  z..        Try t
@@ -627,17 +627,17 @@
 00002720: 5f73 6176 655f 656c 656d 656e 745f 636f  _save_element_co
 00002730: 6d6d 616e 643a 2054 6865 2074 6173 6b20  mmand: The task 
 00002740: 7361 7665 2065 6c65 6d65 6e74 2063 6f6d  save element com
 00002750: 6d61 6e64 2e0a 0a20 2020 2020 2020 2052  mand...        R
 00002760: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00002770: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00002780: 7661 6c75 6520 6173 2061 2064 6963 742e  value as a dict.
-00002790: 0a20 2020 2020 2020 2029 0272 0c00 0000  .        ).r....
+00002790: 0a20 2020 2020 2020 2029 0272 1100 0000  .        ).r....
 000027a0: 7228 0000 0072 2900 0000 722d 0000 0072  r(...r)...r-...r
-000027b0: 2d00 0000 722e 0000 0072 0c00 0000 6401  -...r....r....d.
+000027b0: 2d00 0000 722e 0000 0072 1100 0000 6001  -...r....r....`.
 000027c0: 0000 7302 0000 0000 0b7a 3654 6173 6b53  ..s......z6TaskS
 000027d0: 6176 6545 6c65 6d65 6e74 436f 6d6d 616e  aveElementComman
 000027e0: 6455 7469 6c73 2e66 696e 645f 656c 656d  dUtils.find_elem
 000027f0: 656e 745f 7661 6c75 655f 6173 5f64 6963  ent_value_as_dic
 00002800: 7463 0100 0000 0000 0000 0000 0000 0100  tc..............
 00002810: 0000 0300 0000 4300 0000 730c 0000 0074  ......C...s....t
 00002820: 0074 017c 0083 0183 0153 0029 017a c90a  .t.|.....S.).z..
@@ -649,17 +649,17 @@
 00002880: 5f65 6c65 6d65 6e74 5f63 6f6d 6d61 6e64  _element_command
 00002890: 3a20 5468 6520 7461 736b 2073 6176 6520  : The task save 
 000028a0: 656c 656d 656e 7420 636f 6d6d 616e 642e  element command.
 000028b0: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 000028c0: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 000028d0: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 000028e0: 7320 6173 2064 6963 7420 6c69 7374 2e0a  s as dict list..
-000028f0: 2020 2020 2020 2020 2902 7214 0000 0072          ).r....r
+000028f0: 2020 2020 2020 2020 2902 7219 0000 0072          ).r....r
 00002900: 2800 0000 7229 0000 0072 2d00 0000 722d  (...r)...r-...r-
-00002910: 0000 0072 2e00 0000 7214 0000 0071 0100  ...r....r....q..
+00002910: 0000 0072 2e00 0000 7219 0000 006d 0100  ...r....r....m..
 00002920: 0073 0200 0000 000b 7a3a 5461 736b 5361  .s......z:TaskSa
 00002930: 7665 456c 656d 656e 7443 6f6d 6d61 6e64  veElementCommand
 00002940: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 00002950: 745f 7661 6c75 655f 6173 5f64 6963 745f  t_value_as_dict_
 00002960: 6c69 7374 6301 0000 0000 0000 0000 0000  listc...........
 00002970: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 00002980: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
@@ -674,17 +674,17 @@
 00002a10: 2073 6176 6520 656c 656d 656e 7420 636f   save element co
 00002a20: 6d6d 616e 642e 0a0a 2020 2020 2020 2020  mmand...        
 00002a30: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00002a40: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00002a50: 2076 616c 7565 2061 7320 6120 5461 736b   value as a Task
 00002a60: 456c 656d 656e 7456 616c 7565 446f 6375  ElementValueDocu
 00002a70: 6d65 6e74 4974 656d 2e0a 2020 2020 2020  mentItem..      
-00002a80: 2020 2902 7215 0000 0072 2800 0000 7229    ).r....r(...r)
+00002a80: 2020 2902 721a 0000 0072 2800 0000 7229    ).r....r(...r)
 00002a90: 0000 0072 2d00 0000 722d 0000 0072 2e00  ...r-...r-...r..
-00002aa0: 0000 7215 0000 007e 0100 0073 0200 0000  ..r....~...s....
+00002aa0: 0000 721a 0000 007a 0100 0073 0200 0000  ..r....z...s....
 00002ab0: 000d 7a39 5461 736b 5361 7665 456c 656d  ..z9TaskSaveElem
 00002ac0: 656e 7443 6f6d 6d61 6e64 5574 696c 732e  entCommandUtils.
 00002ad0: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 00002ae0: 655f 6173 5f64 6f63 756d 656e 7463 0100  e_as_documentc..
 00002af0: 0000 0000 0000 0000 0000 0100 0000 0300  ................
 00002b00: 0000 4300 0000 730c 0000 0074 0074 017c  ..C...s....t.t.|
 00002b10: 0083 0183 0153 0029 017a f80a 2020 2020  .....S.).z..    
@@ -699,17 +699,17 @@
 00002ba0: 6b20 7361 7665 2065 6c65 6d65 6e74 2063  k save element c
 00002bb0: 6f6d 6d61 6e64 2e0a 0a20 2020 2020 2020  ommand...       
 00002bc0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00002bd0: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00002be0: 7420 7661 6c75 6520 6173 2061 2054 6173  t value as a Tas
 00002bf0: 6b45 6c65 6d65 6e74 5661 6c75 6544 6f63  kElementValueDoc
 00002c00: 756d 656e 7449 7465 6d2e 0a20 2020 2020  umentItem..     
-00002c10: 2020 2029 0272 0d00 0000 7228 0000 0072     ).r....r(...r
+00002c10: 2020 2029 0272 1200 0000 7228 0000 0072     ).r....r(...r
 00002c20: 2900 0000 722d 0000 0072 2d00 0000 722e  )...r-...r-...r.
-00002c30: 0000 0072 0d00 0000 8d01 0000 7302 0000  ...r........s...
+00002c30: 0000 0072 1200 0000 8901 0000 7302 0000  ...r........s...
 00002c40: 0000 0d7a 3a54 6173 6b53 6176 6545 6c65  ...z:TaskSaveEle
 00002c50: 6d65 6e74 436f 6d6d 616e 6455 7469 6c73  mentCommandUtils
 00002c60: 2e66 696e 645f 656c 656d 656e 745f 7661  .find_element_va
 00002c70: 6c75 655f 6173 5f64 6f63 756d 656e 7463  lue_as_documentc
 00002c80: 0100 0000 0000 0000 0000 0000 0100 0000  ................
 00002c90: 0300 0000 4300 0000 730c 0000 0074 0074  ....C...s....t.t
 00002ca0: 017c 0083 0183 0153 0029 017a f90a 2020  .|.....S.).z..  
@@ -724,17 +724,17 @@
 00002d30: 2073 6176 6520 656c 656d 656e 7420 636f   save element co
 00002d40: 6d6d 616e 642e 0a0a 2020 2020 2020 2020  mmand...        
 00002d50: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00002d60: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00002d70: 2076 616c 7565 7320 6173 2054 6173 6b45   values as TaskE
 00002d80: 6c65 6d65 6e74 5661 6c75 6544 6f63 756d  lementValueDocum
 00002d90: 656e 7449 7465 6d20 6c69 7374 2e0a 2020  entItem list..  
-00002da0: 2020 2020 2020 2902 7216 0000 0072 2800        ).r....r(.
+00002da0: 2020 2020 2020 2902 721b 0000 0072 2800        ).r....r(.
 00002db0: 0000 7229 0000 0072 2d00 0000 722d 0000  ..r)...r-...r-..
-00002dc0: 0072 2e00 0000 7216 0000 009c 0100 0073  .r....r........s
+00002dc0: 0072 2e00 0000 721b 0000 0098 0100 0073  .r....r........s
 00002dd0: 0200 0000 000d 7a3e 5461 736b 5361 7665  ......z>TaskSave
 00002de0: 456c 656d 656e 7443 6f6d 6d61 6e64 5574  ElementCommandUt
 00002df0: 696c 732e 6765 745f 656c 656d 656e 745f  ils.get_element_
 00002e00: 7661 6c75 655f 6173 5f64 6f63 756d 656e  value_as_documen
 00002e10: 745f 6c69 7374 6301 0000 0000 0000 0000  t_listc.........
 00002e20: 0000 0001 0000 0003 0000 0043 0000 0073  ...........C...s
 00002e30: 0c00 0000 7400 7401 7c00 8301 8301 5300  ....t.t.|.....S.
@@ -749,17 +749,17 @@
 00002ec0: 6173 6b20 7361 7665 2065 6c65 6d65 6e74  ask save element
 00002ed0: 2063 6f6d 6d61 6e64 2e0a 0a20 2020 2020   command...     
 00002ee0: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002ef0: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00002f00: 656e 7420 7661 6c75 6520 6173 2061 2054  ent value as a T
 00002f10: 6173 6b45 6c65 6d65 6e74 5661 6c75 6550  askElementValueP
 00002f20: 7269 6e63 6970 616c 4974 656d 2e0a 2020  rincipalItem..  
-00002f30: 2020 2020 2020 2902 7219 0000 0072 2800        ).r....r(.
+00002f30: 2020 2020 2020 2902 721e 0000 0072 2800        ).r....r(.
 00002f40: 0000 7229 0000 0072 2d00 0000 722d 0000  ..r)...r-...r-..
-00002f50: 0072 2e00 0000 7219 0000 00ab 0100 0073  .r....r........s
+00002f50: 0072 2e00 0000 721e 0000 00a7 0100 0073  .r....r........s
 00002f60: 0200 0000 000d 7a3a 5461 736b 5361 7665  ......z:TaskSave
 00002f70: 456c 656d 656e 7443 6f6d 6d61 6e64 5574  ElementCommandUt
 00002f80: 696c 732e 6765 745f 656c 656d 656e 745f  ils.get_element_
 00002f90: 7661 6c75 655f 6173 5f70 7269 6e63 6970  value_as_princip
 00002fa0: 616c 6301 0000 0000 0000 0000 0000 0001  alc.............
 00002fb0: 0000 0003 0000 0043 0000 0073 0c00 0000  .......C...s....
 00002fc0: 7400 7401 7c00 8301 8301 5300 2901 7afa  t.t.|.....S.).z.
@@ -774,17 +774,17 @@
 00003050: 6865 2074 6173 6b20 7361 7665 2065 6c65  he task save ele
 00003060: 6d65 6e74 2063 6f6d 6d61 6e64 2e0a 0a20  ment command... 
 00003070: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 00003080: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 00003090: 656c 656d 656e 7420 7661 6c75 6520 6173  element value as
 000030a0: 2061 2054 6173 6b45 6c65 6d65 6e74 5661   a TaskElementVa
 000030b0: 6c75 6550 7269 6e63 6970 616c 4974 656d  luePrincipalItem
-000030c0: 2e0a 2020 2020 2020 2020 2902 720f 0000  ..        ).r...
+000030c0: 2e0a 2020 2020 2020 2020 2902 7214 0000  ..        ).r...
 000030d0: 0072 2800 0000 7229 0000 0072 2d00 0000  .r(...r)...r-...
-000030e0: 722d 0000 0072 2e00 0000 720f 0000 00ba  r-...r....r.....
+000030e0: 722d 0000 0072 2e00 0000 7214 0000 00b6  r-...r....r.....
 000030f0: 0100 0073 0200 0000 000d 7a3b 5461 736b  ...s......z;Task
 00003100: 5361 7665 456c 656d 656e 7443 6f6d 6d61  SaveElementComma
 00003110: 6e64 5574 696c 732e 6669 6e64 5f65 6c65  ndUtils.find_ele
 00003120: 6d65 6e74 5f76 616c 7565 5f61 735f 7072  ment_value_as_pr
 00003130: 696e 6369 7061 6c63 0100 0000 0000 0000  incipalc........
 00003140: 0000 0000 0100 0000 0300 0000 4300 0000  ............C...
 00003150: 730c 0000 0074 0074 017c 0083 0183 0153  s....t.t.|.....S
@@ -800,62 +800,62 @@
 000031f0: 6c65 6d65 6e74 2063 6f6d 6d61 6e64 2e0a  lement command..
 00003200: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00003210: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00003220: 6520 656c 656d 656e 7420 7661 6c75 6573  e element values
 00003230: 2061 7320 5461 736b 456c 656d 656e 7456   as TaskElementV
 00003240: 616c 7565 5072 696e 6369 7061 6c49 7465  aluePrincipalIte
 00003250: 6d20 6c69 7374 2e0a 2020 2020 2020 2020  m list..        
-00003260: 2902 721a 0000 0072 2800 0000 7229 0000  ).r....r(...r)..
+00003260: 2902 721f 0000 0072 2800 0000 7229 0000  ).r....r(...r)..
 00003270: 0072 2d00 0000 722d 0000 0072 2e00 0000  .r-...r-...r....
-00003280: 721a 0000 00c9 0100 0073 0200 0000 000d  r........s......
+00003280: 721f 0000 00c5 0100 0073 0200 0000 000d  r........s......
 00003290: 7a3f 5461 736b 5361 7665 456c 656d 656e  z?TaskSaveElemen
 000032a0: 7443 6f6d 6d61 6e64 5574 696c 732e 6765  tCommandUtils.ge
 000032b0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
 000032c0: 6173 5f70 7269 6e63 6970 616c 5f6c 6973  as_principal_lis
 000032d0: 7429 014e 2901 4e29 014e 2901 4e29 2a72  t).N).N).N).N)*r
 000032e0: 3600 0000 7237 0000 0072 3800 0000 da0c  6...r7...r8.....
-000032f0: 7374 6174 6963 6d65 7468 6f64 7227 0000  staticmethodr'..
-00003300: 00da 0462 6f6f 6c72 1d00 0000 da03 696e  ...boolr......in
-00003310: 7472 1e00 0000 7203 0000 0072 2100 0000  tr....r....r!...
-00003320: 7222 0000 0072 0600 0000 721f 0000 0072  r"...r....r....r
-00003330: 0200 0000 7220 0000 0072 0900 0000 720a  ....r ...r....r.
-00003340: 0000 00da 0373 7472 721b 0000 0072 1000  .....strr....r..
-00003350: 0000 721c 0000 00da 0566 6c6f 6174 7217  ..r......floatr.
-00003360: 0000 0072 0e00 0000 7218 0000 0072 0400  ...r....r....r..
-00003370: 0000 7211 0000 0072 0b00 0000 7212 0000  ..r....r....r...
-00003380: 00da 0464 6963 7472 1300 0000 720c 0000  ...dictr....r...
-00003390: 0072 1400 0000 7225 0000 0072 1500 0000  .r....r%...r....
-000033a0: 720d 0000 0072 1600 0000 7226 0000 0072  r....r....r&...r
-000033b0: 1900 0000 720f 0000 0072 1a00 0000 722d  ....r....r....r-
+000032f0: 7374 6174 6963 6d65 7468 6f64 7209 0000  staticmethodr...
+00003300: 00da 0462 6f6f 6c72 2200 0000 da03 696e  ...boolr".....in
+00003310: 7472 2300 0000 7204 0000 0072 2600 0000  tr#...r....r&...
+00003320: 7227 0000 0072 0b00 0000 7224 0000 0072  r'...r....r$...r
+00003330: 0300 0000 7225 0000 0072 0e00 0000 720f  ....r%...r....r.
+00003340: 0000 00da 0373 7472 7220 0000 0072 1500  .....strr ...r..
+00003350: 0000 7221 0000 00da 0566 6c6f 6174 721c  ..r!.....floatr.
+00003360: 0000 0072 1300 0000 721d 0000 0072 0200  ...r....r....r..
+00003370: 0000 7216 0000 0072 1000 0000 7217 0000  ..r....r....r...
+00003380: 00da 0464 6963 7472 1800 0000 7211 0000  ...dictr....r...
+00003390: 0072 1900 0000 7207 0000 0072 1a00 0000  .r....r....r....
+000033a0: 7212 0000 0072 1b00 0000 7208 0000 0072  r....r....r....r
+000033b0: 1e00 0000 7214 0000 0072 1f00 0000 722d  ....r....r....r-
 000033c0: 0000 0072 2d00 0000 722d 0000 0072 2e00  ...r-...r-...r..
-000033d0: 0000 7239 0000 0055 0000 0073 bc00 0000  ..r9...U...s....
+000033d0: 0000 7239 0000 0051 0000 0073 bc00 0000  ..r9...Q...s....
 000033e0: 0801 0201 120c 0202 0201 0201 02fd 0e11  ................
 000033f0: 0202 0200 0601 02fe 0e11 0202 0200 0600  ................
 00003400: 0201 02fe 0e12 0202 00ff 0201 0200 0601  ................
 00003410: 02fe 0e11 0202 00ff 0201 0200 0a01 02fe  ................
 00003420: 0e11 0202 00ff 0201 0200 0601 02fe 0e11  ................
 00003430: 0202 00ff 0201 0200 0a01 02fe 0e11 0201  ................
 00003440: 120c 0201 160c 0201 160c 0201 120c 0201  ................
 00003450: 120c 0201 160c 0201 120c 0201 160c 0201  ................
 00003460: 1a0c 0201 120c 0201 160c 0201 1a0c 0202  ................
 00003470: 0201 02fe 0e0e 0202 0201 06fe 0e0e 0202  ................
 00003480: 0201 06fe 0e0e 0202 0201 02fe 0e0e 0202  ................
 00003490: 0201 06fe 0e0e 0202 0201 06fe 7239 0000  ............r9..
-000034a0: 004e 292b da06 7479 7069 6e67 7202 0000  .N)+..typingr...
-000034b0: 0072 0300 0000 da08 6461 7465 7469 6d65  .r......datetime
-000034c0: 7204 0000 0072 3000 0000 7206 0000 0072  r....r0...r....r
-000034d0: 0700 0000 7208 0000 0072 0900 0000 720a  ....r....r....r.
-000034e0: 0000 0072 0b00 0000 720c 0000 0072 0d00  ...r....r....r..
-000034f0: 0000 720e 0000 0072 0f00 0000 7210 0000  ..r....r....r...
-00003500: 0072 1100 0000 7212 0000 0072 1300 0000  .r....r....r....
-00003510: 7214 0000 0072 1500 0000 7216 0000 0072  r....r....r....r
-00003520: 1700 0000 7218 0000 0072 1900 0000 721a  ....r....r....r.
-00003530: 0000 0072 1b00 0000 721c 0000 0072 1d00  ...r....r....r..
-00003540: 0000 721e 0000 0072 1f00 0000 7220 0000  ..r....r....r ..
-00003550: 0072 2100 0000 7222 0000 005a 115f 6765  .r!...r"...Z._ge
-00003560: 6e65 7261 7465 642e 6d6f 6465 6c73 7224  nerated.modelsr$
-00003570: 0000 00da 066d 6f64 656c 7372 2500 0000  .....modelsr%...
+000034a0: 004e 292b da08 6461 7465 7469 6d65 7202  .N)+..datetimer.
+000034b0: 0000 00da 0674 7970 696e 6772 0300 0000  .....typingr....
+000034c0: 7204 0000 005a 115f 6765 6e65 7261 7465  r....Z._generate
+000034d0: 642e 6d6f 6465 6c73 7206 0000 00da 066d  d.modelsr......m
+000034e0: 6f64 656c 7372 0700 0000 7208 0000 0072  odelsr....r....r
+000034f0: 0900 0000 7230 0000 0072 0b00 0000 720c  ....r0...r....r.
+00003500: 0000 0072 0d00 0000 720e 0000 0072 0f00  ...r....r....r..
+00003510: 0000 7210 0000 0072 1100 0000 7212 0000  ..r....r....r...
+00003520: 0072 1300 0000 7214 0000 0072 1500 0000  .r....r....r....
+00003530: 7216 0000 0072 1700 0000 7218 0000 0072  r....r....r....r
+00003540: 1900 0000 721a 0000 0072 1b00 0000 721c  ....r....r....r.
+00003550: 0000 0072 1d00 0000 721e 0000 0072 1f00  ...r....r....r..
+00003560: 0000 7220 0000 0072 2100 0000 7222 0000  ..r ...r!...r"..
+00003570: 0072 2300 0000 7224 0000 0072 2500 0000  .r#...r$...r%...
 00003580: 7226 0000 0072 2700 0000 7228 0000 0072  r&...r'...r(...r
 00003590: 3900 0000 722d 0000 0072 2d00 0000 722d  9...r-...r-...r-
 000035a0: 0000 0072 2e00 0000 da08 3c6d 6f64 756c  ...r......<modul
-000035b0: 653e 1a00 0000 730c 0000 0010 010c 027c  e>....s........|
-000035c0: 1f0c 0114 0710 11                        .......
+000035b0: 653e 1a00 0000 730c 0000 000c 0110 020c  e>....s.........
+000035c0: 0114 017c 2110 11                        ...|!..
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_save_json_forms_value_data_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_save_json_forms_value_data_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 15393 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,76 +1,76 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 213c 0000  U.......=S.d!<..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 103c 0000  U..........d.<..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 b600 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 0100 6400 6402 6c04 6d05 5a05 6d04 5a04  ..d.d.l.m.Z.m.Z.
+00000030: 6401 6c00 6d01 5a01 6d00 5a00 0100 6400  d.l.m.Z.m.Z...d.
+00000040: 6402 6c02 6d03 5a03 6d04 5a04 6d05 5a05  d.l.m.Z.m.Z.m.Z.
 00000050: 0100 6403 6404 6c06 6d07 5a07 6d08 5a08  ..d.d.l.m.Z.m.Z.
-00000060: 6d09 5a09 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f 6d10 5a10  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d11 5a11 6d12 5a12 6d13 5a13 6d14 5a14  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d15 5a15 6d16 5a16 6d17 5a17 6d18 5a18  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d19 5a19 6d1a 5a1a 6d1b 5a1b 0100 6405  m.Z.m.Z.m.Z...d.
-000000b0: 6406 6c1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  d.l.m.Z.m.Z.m.Z.
-000000c0: 0100 4700 6407 6408 8400 6408 6507 8303  ..G.d.d...d.e...
+00000060: 6d09 5a09 0100 6405 6406 6c0a 6d0b 5a0b  m.Z...d.d.l.m.Z.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  m.Z.m.Z.m.Z.m.Z.
+000000c0: 0100 4700 6407 6408 8400 6408 650b 8303  ..G.d.d...d.e...
 000000d0: 5a20 4700 6409 640a 8400 640a 8302 5a21  Z G.d.d...d...Z!
-000000e0: 640b 5300 290c e900 0000 0029 03da 0341  d.S.)......)...A
-000000f0: 6e79 da04 4469 6374 da08 4f70 7469 6f6e  ny..Dict..Option
-00000100: 616c 2902 da04 6461 7465 da08 6461 7465  al)...date..date
-00000110: 7469 6d65 e901 0000 0029 15da 144a 736f  time.....)...Jso
-00000120: 6e46 6f72 6d44 6174 6141 6363 6573 736f  nFormDataAccesso
-00000130: 72da 134a 736f 6e46 6f72 6d73 5369 6d70  r..JsonFormsSimp
-00000140: 6c65 5479 7065 da20 6669 6e64 5f6a 736f  leType. find_jso
-00000150: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
-00000160: 5f61 735f 6461 7465 da24 6669 6e64 5f6a  _as_date.$find_j
-00000170: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
-00000180: 7479 5f61 735f 6461 7465 7469 6d65 da20  ty_as_datetime. 
-00000190: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
-000001a0: 7072 6f70 6572 7479 5f61 735f 6469 6374  property_as_dict
-000001b0: da21 6669 6e64 5f6a 736f 6e5f 666f 726d  .!find_json_form
-000001c0: 735f 7072 6f70 6572 7479 5f61 735f 666c  s_property_as_fl
-000001d0: 6f61 74da 1f66 696e 645f 6a73 6f6e 5f66  oat..find_json_f
-000001e0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
-000001f0: 5f69 6e74 da2b 6669 6e64 5f6a 736f 6e5f  _int.+find_json_
-00000200: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
-00000210: 735f 6a73 6f6e 5f66 6f72 6d73 5f66 696c  s_json_forms_fil
-00000220: 65da 3066 696e 645f 6a73 6f6e 5f66 6f72  e.0find_json_for
-00000230: 6d73 5f70 726f 7065 7274 795f 6173 5f6a  ms_property_as_j
-00000240: 736f 6e5f 666f 726d 735f 7072 696e 6369  son_forms_princi
-00000250: 7061 6cda 2066 696e 645f 6a73 6f6e 5f66  pal. find_json_f
-00000260: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
-00000270: 5f6c 6973 74da 1f66 696e 645f 6a73 6f6e  _list..find_json
-00000280: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
-00000290: 6173 5f73 7472 da1f 6765 745f 6a73 6f6e  as_str..get_json
-000002a0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
-000002b0: 6173 5f64 6174 65da 2367 6574 5f6a 736f  as_date.#get_jso
-000002c0: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
-000002d0: 5f61 735f 6461 7465 7469 6d65 da1f 6765  _as_datetime..ge
-000002e0: 745f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  t_json_forms_pro
-000002f0: 7065 7274 795f 6173 5f64 6963 74da 2067  perty_as_dict. g
-00000300: 6574 5f6a 736f 6e5f 666f 726d 735f 7072  et_json_forms_pr
-00000310: 6f70 6572 7479 5f61 735f 666c 6f61 74da  operty_as_float.
-00000320: 1e67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
-00000330: 7072 6f70 6572 7479 5f61 735f 696e 74da  property_as_int.
-00000340: 2a67 6574 5f6a 736f 6e5f 666f 726d 735f  *get_json_forms_
-00000350: 7072 6f70 6572 7479 5f61 735f 6a73 6f6e  property_as_json
-00000360: 5f66 6f72 6d73 5f66 696c 65da 2f67 6574  _forms_file./get
-00000370: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
-00000380: 6572 7479 5f61 735f 6a73 6f6e 5f66 6f72  erty_as_json_for
-00000390: 6d73 5f70 7269 6e63 6970 616c da1f 6765  ms_principal..ge
-000003a0: 745f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  t_json_forms_pro
-000003b0: 7065 7274 795f 6173 5f6c 6973 74da 1e67  perty_as_list..g
-000003c0: 6574 5f6a 736f 6e5f 666f 726d 735f 7072  et_json_forms_pr
-000003d0: 6f70 6572 7479 5f61 735f 7374 72da 1a75  operty_as_str..u
-000003e0: 7064 6174 655f 6a73 6f6e 5f66 6f72 6d73  pdate_json_forms
-000003f0: 5f70 726f 7065 7274 79e9 0200 0000 2903  _property.....).
-00000400: da0d 4a73 6f6e 466f 726d 7346 696c 65da  ..JsonFormsFile.
-00000410: 124a 736f 6e46 6f72 6d73 5072 696e 6369  .JsonFormsPrinci
-00000420: 7061 6cda 2154 6173 6b53 6176 654a 736f  pal.!TaskSaveJso
-00000430: 6e46 6f72 6d73 5661 6c75 6544 6174 6143  nFormsValueDataC
-00000440: 6f6d 6d61 6e64 6300 0000 0000 0000 0000  ommandc.........
+000000e0: 640b 5300 290c e900 0000 0029 02da 0464  d.S.)......)...d
+000000f0: 6174 65da 0864 6174 6574 696d 6529 03da  ate..datetime)..
+00000100: 0341 6e79 da04 4469 6374 da08 4f70 7469  .Any..Dict..Opti
+00000110: 6f6e 616c e902 0000 0029 03da 0d4a 736f  onal.....)...Jso
+00000120: 6e46 6f72 6d73 4669 6c65 da12 4a73 6f6e  nFormsFile..Json
+00000130: 466f 726d 7350 7269 6e63 6970 616c da21  FormsPrincipal.!
+00000140: 5461 736b 5361 7665 4a73 6f6e 466f 726d  TaskSaveJsonForm
+00000150: 7356 616c 7565 4461 7461 436f 6d6d 616e  sValueDataComman
+00000160: 64e9 0100 0000 2915 da14 4a73 6f6e 466f  d.....)...JsonFo
+00000170: 726d 4461 7461 4163 6365 7373 6f72 da13  rmDataAccessor..
+00000180: 4a73 6f6e 466f 726d 7353 696d 706c 6554  JsonFormsSimpleT
+00000190: 7970 65da 2066 696e 645f 6a73 6f6e 5f66  ype. find_json_f
+000001a0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
+000001b0: 5f64 6174 65da 2466 696e 645f 6a73 6f6e  _date.$find_json
+000001c0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
+000001d0: 6173 5f64 6174 6574 696d 65da 2066 696e  as_datetime. fin
+000001e0: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
+000001f0: 7065 7274 795f 6173 5f64 6963 74da 2166  perty_as_dict.!f
+00000200: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
+00000210: 726f 7065 7274 795f 6173 5f66 6c6f 6174  roperty_as_float
+00000220: da1f 6669 6e64 5f6a 736f 6e5f 666f 726d  ..find_json_form
+00000230: 735f 7072 6f70 6572 7479 5f61 735f 696e  s_property_as_in
+00000240: 74da 2b66 696e 645f 6a73 6f6e 5f66 6f72  t.+find_json_for
+00000250: 6d73 5f70 726f 7065 7274 795f 6173 5f6a  ms_property_as_j
+00000260: 736f 6e5f 666f 726d 735f 6669 6c65 da30  son_forms_file.0
+00000270: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
+00000280: 7072 6f70 6572 7479 5f61 735f 6a73 6f6e  property_as_json
+00000290: 5f66 6f72 6d73 5f70 7269 6e63 6970 616c  _forms_principal
+000002a0: da20 6669 6e64 5f6a 736f 6e5f 666f 726d  . find_json_form
+000002b0: 735f 7072 6f70 6572 7479 5f61 735f 6c69  s_property_as_li
+000002c0: 7374 da1f 6669 6e64 5f6a 736f 6e5f 666f  st..find_json_fo
+000002d0: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
+000002e0: 7374 72da 1f67 6574 5f6a 736f 6e5f 666f  str..get_json_fo
+000002f0: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
+00000300: 6461 7465 da23 6765 745f 6a73 6f6e 5f66  date.#get_json_f
+00000310: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
+00000320: 5f64 6174 6574 696d 65da 1f67 6574 5f6a  _datetime..get_j
+00000330: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
+00000340: 7479 5f61 735f 6469 6374 da20 6765 745f  ty_as_dict. get_
+00000350: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
+00000360: 7274 795f 6173 5f66 6c6f 6174 da1e 6765  rty_as_float..ge
+00000370: 745f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  t_json_forms_pro
+00000380: 7065 7274 795f 6173 5f69 6e74 da2a 6765  perty_as_int.*ge
+00000390: 745f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  t_json_forms_pro
+000003a0: 7065 7274 795f 6173 5f6a 736f 6e5f 666f  perty_as_json_fo
+000003b0: 726d 735f 6669 6c65 da2f 6765 745f 6a73  rms_file./get_js
+000003c0: 6f6e 5f66 6f72 6d73 5f70 726f 7065 7274  on_forms_propert
+000003d0: 795f 6173 5f6a 736f 6e5f 666f 726d 735f  y_as_json_forms_
+000003e0: 7072 696e 6369 7061 6cda 1f67 6574 5f6a  principal..get_j
+000003f0: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
+00000400: 7479 5f61 735f 6c69 7374 da1e 6765 745f  ty_as_list..get_
+00000410: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
+00000420: 7274 795f 6173 5f73 7472 da1a 7570 6461  rty_as_str..upda
+00000430: 7465 5f6a 736f 6e5f 666f 726d 735f 7072  te_json_forms_pr
+00000440: 6f70 6572 7479 6300 0000 0000 0000 0000  opertyc.........
 00000450: 0000 0000 0000 0004 0000 0040 0000 0073  ...........@...s
 00000460: 4e00 0000 6500 5a01 6400 5a02 6503 6401  N...e.Z.d.Z.e.d.
 00000470: 9c01 6402 6403 8404 5a04 6505 6506 6507  ..d.d...Z.e.e.e.
 00000480: 6508 6602 1900 1900 6404 9c01 6405 6406  e.f.....d...d.d.
 00000490: 8404 5a09 6505 6506 6507 6508 6602 1900  ..Z.e.e.e.e.f...
 000004a0: 1900 6407 9c01 6408 6409 8404 5a0a 640a  ..d...d.d...Z.d.
 000004b0: 5300 290b da1b 4375 7272 656e 744a 736f  S.)...CurrentJso
@@ -82,43 +82,43 @@
 00000510: 7365 6c66 7223 0000 00a9 0072 2600 0000  selfr#.....r&...
 00000520: fa5f 2f77 6f72 6b2f 6b75 666c 6f77 2d73  ._/work/kuflow-s
 00000530: 646b 2d70 7974 686f 6e2f 6b75 666c 6f77  dk-python/kuflow
 00000540: 2d72 6573 742f 6b75 666c 6f77 5f72 6573  -rest/kuflow_res
 00000550: 742f 7574 696c 732f 5f74 6173 6b5f 7361  t/utils/_task_sa
 00000560: 7665 5f6a 736f 6e5f 666f 726d 735f 7661  ve_json_forms_va
 00000570: 6c75 655f 6461 7461 5f75 7469 6c73 2e70  lue_data_utils.p
-00000580: 79da 085f 5f69 6e69 745f 5f3c 0000 0073  y..__init__<...s
+00000580: 79da 085f 5f69 6e69 745f 5f38 0000 0073  y..__init__8...s
 00000590: 0200 0000 0001 7a24 4375 7272 656e 744a  ......z$CurrentJ
 000005a0: 736f 6e46 6f72 6d44 6174 6141 6363 6573  sonFormDataAcces
 000005b0: 736f 722e 5f5f 696e 6974 5f5f 2901 da06  sor.__init__)...
 000005c0: 7265 7475 726e 6301 0000 0000 0000 0000  returnc.........
 000005d0: 0000 0001 0000 0001 0000 0043 0000 0073  ...........C...s
 000005e0: 0800 0000 7c00 6a00 6a01 5300 7224 0000  ....|.j.j.S.r$..
 000005f0: 00a9 0272 2300 0000 da04 6461 7461 2901  ...r#.....data).
 00000600: 7225 0000 0072 2600 0000 7226 0000 0072  r%...r&...r&...r
-00000610: 2700 0000 da08 6765 745f 6461 7461 3f00  '.....get_data?.
+00000610: 2700 0000 da08 6765 745f 6461 7461 3b00  '.....get_data;.
 00000620: 0000 7302 0000 0000 017a 2443 7572 7265  ..s......z$Curre
 00000630: 6e74 4a73 6f6e 466f 726d 4461 7461 4163  ntJsonFormDataAc
 00000640: 6365 7373 6f72 2e67 6574 5f64 6174 6129  cessor.get_data)
 00000650: 0172 2b00 0000 6302 0000 0000 0000 0000  .r+...c.........
 00000660: 0000 0002 0000 0002 0000 0043 0000 0073  ...........C...s
 00000670: 0c00 0000 7c01 7c00 6a00 5f01 6400 5300  ....|.|.j._.d.S.
 00000680: 7224 0000 0072 2a00 0000 2902 7225 0000  r$...r*...).r%..
 00000690: 0072 2b00 0000 7226 0000 0072 2600 0000  .r+...r&...r&...
-000006a0: 7227 0000 00da 0873 6574 5f64 6174 6142  r'.....set_dataB
+000006a0: 7227 0000 00da 0873 6574 5f64 6174 613e  r'.....set_data>
 000006b0: 0000 0073 0200 0000 0001 7a24 4375 7272  ...s......z$Curr
 000006c0: 656e 744a 736f 6e46 6f72 6d44 6174 6141  entJsonFormDataA
 000006d0: 6363 6573 736f 722e 7365 745f 6461 7461  ccessor.set_data
 000006e0: 4e29 0bda 085f 5f6e 616d 655f 5fda 0a5f  N)...__name__.._
 000006f0: 5f6d 6f64 756c 655f 5fda 0c5f 5f71 7561  _module__..__qua
-00000700: 6c6e 616d 655f 5f72 2000 0000 7228 0000  lname__r ...r(..
-00000710: 0072 0400 0000 7203 0000 00da 0373 7472  .r....r......str
-00000720: 7202 0000 0072 2c00 0000 722d 0000 0072  r....r,...r-...r
+00000700: 6c6e 616d 655f 5f72 0a00 0000 7228 0000  lname__r....r(..
+00000710: 0072 0600 0000 7205 0000 00da 0373 7472  .r....r......str
+00000720: 7204 0000 0072 2c00 0000 722d 0000 0072  r....r,...r-...r
 00000730: 2600 0000 7226 0000 0072 2600 0000 7227  &...r&...r&...r'
-00000740: 0000 0072 2100 0000 3b00 0000 7306 0000  ...r!...;...s...
+00000740: 0000 0072 2100 0000 3700 0000 7306 0000  ...r!...7...s...
 00000750: 0008 010e 031a 0372 2100 0000 6300 0000  .......r!...c...
 00000760: 0000 0000 0000 0000 0000 0000 0006 0000  ................
 00000770: 0040 0000 0073 d801 0000 6500 5a01 6400  .@...s....e.Z.d.
 00000780: 5a02 6503 6504 6505 6505 6401 9c03 6402  Z.e.e.e.e.d...d.
 00000790: 6403 8404 8301 5a06 6503 6504 6505 6507  d.....Z.e.e.e.e.
 000007a0: 6505 1900 6401 9c03 6404 6405 8404 8301  e...d...d.d.....
 000007b0: 5a08 6503 6504 6505 6509 6401 9c03 6406  Z.e.e.e.e.d...d.
@@ -176,17 +176,17 @@
 00000af0: 6620 6578 6973 7473 2e0a 0a20 2020 2020  f exists...     
 00000b00: 2020 2052 6169 7365 733a 0a20 2020 2020     Raises:.     
 00000b10: 2020 2020 2020 2056 616c 7565 4572 726f         ValueErro
 00000b20: 723a 2049 6620 7072 6f70 6572 7479 2076  r: If property v
 00000b30: 616c 7565 2064 6f65 736e 2774 2065 7869  alue doesn't exi
 00000b40: 7374 206f 7220 6861 7320 696e 636f 7272  st or has incorr
 00000b50: 6563 7420 666f 726d 6174 0a20 2020 2020  ect format.     
-00000b60: 2020 2029 0272 1b00 0000 7221 0000 00a9     ).r....r!....
+00000b60: 2020 2029 0272 1f00 0000 7221 0000 00a9     ).r....r!....
 00000b70: 0272 2300 0000 7233 0000 0072 2600 0000  .r#...r3...r&...
-00000b80: 7226 0000 0072 2700 0000 721b 0000 0047  r&...r'...r....G
+00000b80: 7226 0000 0072 2700 0000 721f 0000 0043  r&...r'...r....C
 00000b90: 0000 0073 0200 0000 000f 7a45 5461 736b  ...s......zETask
 00000ba0: 5361 7665 4a73 6f6e 466f 726d 7356 616c  SaveJsonFormsVal
 00000bb0: 7565 4461 7461 436f 6d6d 616e 6455 7469  ueDataCommandUti
 00000bc0: 6c73 2e67 6574 5f6a 736f 6e5f 666f 726d  ls.get_json_form
 00000bd0: 735f 7072 6f70 6572 7479 5f61 735f 7374  s_property_as_st
 00000be0: 7263 0200 0000 0000 0000 0000 0000 0200  rc..............
 00000bf0: 0000 0300 0000 4300 0000 730e 0000 0074  ......C...s....t
@@ -212,17 +212,17 @@
 00000d30: 6520 7072 6f70 6572 7479 2076 616c 7565  e property value
 00000d40: 2069 6620 6578 6973 7473 2e0a 0a20 2020   if exists...   
 00000d50: 2020 2020 2052 6169 7365 733a 0a20 2020       Raises:.   
 00000d60: 2020 2020 2020 2020 2056 616c 7565 4572           ValueEr
 00000d70: 726f 723a 2049 6620 7072 6f70 6572 7479  ror: If property
 00000d80: 2076 616c 7565 2068 6173 2069 6e63 6f72   value has incor
 00000d90: 7265 6374 2066 6f72 6d61 740a 2020 2020  rect format.    
-00000da0: 2020 2020 2902 7212 0000 0072 2100 0000      ).r....r!...
+00000da0: 2020 2020 2902 7216 0000 0072 2100 0000      ).r....r!...
 00000db0: 7234 0000 0072 2600 0000 7226 0000 0072  r4...r&...r&...r
-00000dc0: 2700 0000 7212 0000 0058 0000 0073 0200  '...r....X...s..
+00000dc0: 2700 0000 7216 0000 0054 0000 0073 0200  '...r....T...s..
 00000dd0: 0000 0011 7a46 5461 736b 5361 7665 4a73  ....zFTaskSaveJs
 00000de0: 6f6e 466f 726d 7356 616c 7565 4461 7461  onFormsValueData
 00000df0: 436f 6d6d 616e 6455 7469 6c73 2e66 696e  CommandUtils.fin
 00000e00: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
 00000e10: 7065 7274 795f 6173 5f73 7472 6302 0000  perty_as_strc...
 00000e20: 0000 0000 0000 0000 0002 0000 0003 0000  ................
 00000e30: 0043 0000 0073 0e00 0000 7400 7401 7c00  .C...s....t.t.|.
@@ -248,17 +248,17 @@
 00000f70: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00000f80: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00000f90: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00000fa0: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00000fb0: 7274 7920 7661 6c75 6520 646f 6573 6e27  rty value doesn'
 00000fc0: 7420 6578 6973 7420 6f72 2068 6173 2069  t exist or has i
 00000fd0: 6e63 6f72 7265 6374 2066 6f72 6d61 740a  ncorrect format.
-00000fe0: 2020 2020 2020 2020 2902 7217 0000 0072          ).r....r
+00000fe0: 2020 2020 2020 2020 2902 721b 0000 0072          ).r....r
 00000ff0: 2100 0000 7234 0000 0072 2600 0000 7226  !...r4...r&...r&
-00001000: 0000 0072 2700 0000 7217 0000 006b 0000  ...r'...r....k..
+00001000: 0000 0072 2700 0000 721b 0000 0067 0000  ...r'...r....g..
 00001010: 0073 0200 0000 000f 7a45 5461 736b 5361  .s......zETaskSa
 00001020: 7665 4a73 6f6e 466f 726d 7356 616c 7565  veJsonFormsValue
 00001030: 4461 7461 436f 6d6d 616e 6455 7469 6c73  DataCommandUtils
 00001040: 2e67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
 00001050: 7072 6f70 6572 7479 5f61 735f 696e 7463  property_as_intc
 00001060: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 00001070: 0300 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
@@ -284,17 +284,17 @@
 000011b0: 7072 6f70 6572 7479 2076 616c 7565 2069  property value i
 000011c0: 6620 6578 6973 7473 2e0a 0a20 2020 2020  f exists...     
 000011d0: 2020 2052 6169 7365 733a 0a20 2020 2020     Raises:.     
 000011e0: 2020 2020 2020 2056 616c 7565 4572 726f         ValueErro
 000011f0: 723a 2049 6620 7072 6f70 6572 7479 2076  r: If property v
 00001200: 616c 7565 2068 6173 2069 6e63 6f72 7265  alue has incorre
 00001210: 6374 2066 6f72 6d61 740a 2020 2020 2020  ct format.      
-00001220: 2020 2902 720e 0000 0072 2100 0000 7234    ).r....r!...r4
+00001220: 2020 2902 7212 0000 0072 2100 0000 7234    ).r....r!...r4
 00001230: 0000 0072 2600 0000 7226 0000 0072 2700  ...r&...r&...r'.
-00001240: 0000 720e 0000 007c 0000 0073 0200 0000  ..r....|...s....
+00001240: 0000 7212 0000 0078 0000 0073 0200 0000  ..r....x...s....
 00001250: 0011 7a46 5461 736b 5361 7665 4a73 6f6e  ..zFTaskSaveJson
 00001260: 466f 726d 7356 616c 7565 4461 7461 436f  FormsValueDataCo
 00001270: 6d6d 616e 6455 7469 6c73 2e66 696e 645f  mmandUtils.find_
 00001280: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
 00001290: 7274 795f 6173 5f69 6e74 6302 0000 0000  rty_as_intc.....
 000012a0: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
 000012b0: 0000 0073 0e00 0000 7400 7401 7c00 8301  ...s....t.t.|...
@@ -320,17 +320,17 @@
 000013f0: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00001400: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00001410: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00001420: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00001430: 7274 7920 7661 6c75 6520 646f 6573 6e27  rty value doesn'
 00001440: 7420 6578 6973 7420 6f72 2068 6173 2069  t exist or has i
 00001450: 6e63 6f72 7265 6374 2066 6f72 6d61 740a  ncorrect format.
-00001460: 2020 2020 2020 2020 2902 7216 0000 0072          ).r....r
+00001460: 2020 2020 2020 2020 2902 721a 0000 0072          ).r....r
 00001470: 2100 0000 7234 0000 0072 2600 0000 7226  !...r4...r&...r&
-00001480: 0000 0072 2700 0000 7216 0000 008f 0000  ...r'...r.......
+00001480: 0000 0072 2700 0000 721a 0000 008b 0000  ...r'...r.......
 00001490: 0073 0200 0000 000f 7a47 5461 736b 5361  .s......zGTaskSa
 000014a0: 7665 4a73 6f6e 466f 726d 7356 616c 7565  veJsonFormsValue
 000014b0: 4461 7461 436f 6d6d 616e 6455 7469 6c73  DataCommandUtils
 000014c0: 2e67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
 000014d0: 7072 6f70 6572 7479 5f61 735f 666c 6f61  property_as_floa
 000014e0: 7463 0200 0000 0000 0000 0000 0000 0200  tc..............
 000014f0: 0000 0300 0000 4300 0000 730e 0000 0074  ......C...s....t
@@ -356,17 +356,17 @@
 00001630: 5468 6520 7072 6f70 6572 7479 2076 616c  The property val
 00001640: 7565 2069 6620 6578 6973 7473 2e0a 0a20  ue if exists... 
 00001650: 2020 2020 2020 2052 6169 7365 733a 0a20         Raises:. 
 00001660: 2020 2020 2020 2020 2020 2056 616c 7565             Value
 00001670: 4572 726f 723a 2049 6620 7072 6f70 6572  Error: If proper
 00001680: 7479 2076 616c 7565 2068 6173 2069 6e63  ty value has inc
 00001690: 6f72 7265 6374 2066 6f72 6d61 740a 2020  orrect format.  
-000016a0: 2020 2020 2020 2902 720d 0000 0072 2100        ).r....r!.
+000016a0: 2020 2020 2020 2902 7211 0000 0072 2100        ).r....r!.
 000016b0: 0000 7234 0000 0072 2600 0000 7226 0000  ..r4...r&...r&..
-000016c0: 0072 2700 0000 720d 0000 00a0 0000 0073  .r'...r........s
+000016c0: 0072 2700 0000 7211 0000 009c 0000 0073  .r'...r........s
 000016d0: 0200 0000 0011 7a48 5461 736b 5361 7665  ......zHTaskSave
 000016e0: 4a73 6f6e 466f 726d 7356 616c 7565 4461  JsonFormsValueDa
 000016f0: 7461 436f 6d6d 616e 6455 7469 6c73 2e66  taCommandUtils.f
 00001700: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
 00001710: 726f 7065 7274 795f 6173 5f66 6c6f 6174  roperty_as_float
 00001720: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 00001730: 0003 0000 0043 0000 0073 0e00 0000 7400  .....C...s....t.
@@ -393,17 +393,17 @@
 00001880: 7473 2e0a 0a20 2020 2020 2020 2052 6169  ts...        Rai
 00001890: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 000018a0: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 000018b0: 7072 6f70 6572 7479 2076 616c 7565 2064  property value d
 000018c0: 6f65 736e 2774 2065 7869 7374 206f 7220  oesn't exist or 
 000018d0: 6861 7320 696e 636f 7272 6563 7420 666f  has incorrect fo
 000018e0: 726d 6174 0a20 2020 2020 2020 2029 0272  rmat.        ).r
-000018f0: 1300 0000 7221 0000 0072 3400 0000 7226  ....r!...r4...r&
-00001900: 0000 0072 2600 0000 7227 0000 0072 1300  ...r&...r'...r..
-00001910: 0000 b300 0000 7302 0000 0000 0f7a 4654  ......s......zFT
+000018f0: 1700 0000 7221 0000 0072 3400 0000 7226  ....r!...r4...r&
+00001900: 0000 0072 2600 0000 7227 0000 0072 1700  ...r&...r'...r..
+00001910: 0000 af00 0000 7302 0000 0000 0f7a 4654  ......s......zFT
 00001920: 6173 6b53 6176 654a 736f 6e46 6f72 6d73  askSaveJsonForms
 00001930: 5661 6c75 6544 6174 6143 6f6d 6d61 6e64  ValueDataCommand
 00001940: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00001950: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00001960: 5f64 6174 6563 0200 0000 0000 0000 0000  _datec..........
 00001970: 0000 0200 0000 0300 0000 4300 0000 730e  ..........C...s.
 00001980: 0000 0074 0074 017c 0083 017c 0183 0253  ...t.t.|...|...S
@@ -428,17 +428,17 @@
 00001ab0: 2020 2054 6865 2070 726f 7065 7274 7920     The property 
 00001ac0: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 00001ad0: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 00001ae0: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 00001af0: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 00001b00: 7065 7274 7920 7661 6c75 6520 6861 7320  perty value has 
 00001b10: 696e 636f 7272 6563 7420 666f 726d 6174  incorrect format
-00001b20: 0a20 2020 2020 2020 2029 0272 0a00 0000  .        ).r....
+00001b20: 0a20 2020 2020 2020 2029 0272 0e00 0000  .        ).r....
 00001b30: 7221 0000 0072 3400 0000 7226 0000 0072  r!...r4...r&...r
-00001b40: 2600 0000 7227 0000 0072 0a00 0000 c400  &...r'...r......
+00001b40: 2600 0000 7227 0000 0072 0e00 0000 c000  &...r'...r......
 00001b50: 0000 7302 0000 0000 117a 4754 6173 6b53  ..s......zGTaskS
 00001b60: 6176 654a 736f 6e46 6f72 6d73 5661 6c75  aveJsonFormsValu
 00001b70: 6544 6174 6143 6f6d 6d61 6e64 5574 696c  eDataCommandUtil
 00001b80: 732e 6669 6e64 5f6a 736f 6e5f 666f 726d  s.find_json_form
 00001b90: 735f 7072 6f70 6572 7479 5f61 735f 6461  s_property_as_da
 00001ba0: 7465 6302 0000 0000 0000 0000 0000 0002  tec.............
 00001bb0: 0000 0003 0000 0043 0000 0073 0e00 0000  .......C...s....
@@ -465,17 +465,17 @@
 00001d00: 6620 6578 6973 7473 2e0a 0a20 2020 2020  f exists...     
 00001d10: 2020 2052 6169 7365 733a 0a20 2020 2020     Raises:.     
 00001d20: 2020 2020 2020 2056 616c 7565 4572 726f         ValueErro
 00001d30: 723a 2049 6620 7072 6f70 6572 7479 2076  r: If property v
 00001d40: 616c 7565 2064 6f65 736e 2774 2065 7869  alue doesn't exi
 00001d50: 7374 206f 7220 6861 7320 696e 636f 7272  st or has incorr
 00001d60: 6563 7420 666f 726d 6174 0a20 2020 2020  ect format.     
-00001d70: 2020 2029 0272 1400 0000 7221 0000 0072     ).r....r!...r
+00001d70: 2020 2029 0272 1800 0000 7221 0000 0072     ).r....r!...r
 00001d80: 3400 0000 7226 0000 0072 2600 0000 7227  4...r&...r&...r'
-00001d90: 0000 0072 1400 0000 d700 0000 7302 0000  ...r........s...
+00001d90: 0000 0072 1800 0000 d300 0000 7302 0000  ...r........s...
 00001da0: 0000 0f7a 4a54 6173 6b53 6176 654a 736f  ...zJTaskSaveJso
 00001db0: 6e46 6f72 6d73 5661 6c75 6544 6174 6143  nFormsValueDataC
 00001dc0: 6f6d 6d61 6e64 5574 696c 732e 6765 745f  ommandUtils.get_
 00001dd0: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
 00001de0: 7274 795f 6173 5f64 6174 6574 696d 6563  rty_as_datetimec
 00001df0: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 00001e00: 0300 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
@@ -501,17 +501,17 @@
 00001f40: 2054 6865 2070 726f 7065 7274 7920 7661   The property va
 00001f50: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00001f60: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00001f70: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00001f80: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00001f90: 7274 7920 7661 6c75 6520 6861 7320 696e  rty value has in
 00001fa0: 636f 7272 6563 7420 666f 726d 6174 0a20  correct format. 
-00001fb0: 2020 2020 2020 2029 0272 0b00 0000 7221         ).r....r!
+00001fb0: 2020 2020 2020 2029 0272 0f00 0000 7221         ).r....r!
 00001fc0: 0000 0072 3400 0000 7226 0000 0072 2600  ...r4...r&...r&.
-00001fd0: 0000 7227 0000 0072 0b00 0000 e800 0000  ..r'...r........
+00001fd0: 0000 7227 0000 0072 0f00 0000 e400 0000  ..r'...r........
 00001fe0: 7302 0000 0000 117a 4b54 6173 6b53 6176  s......zKTaskSav
 00001ff0: 654a 736f 6e46 6f72 6d73 5661 6c75 6544  eJsonFormsValueD
 00002000: 6174 6143 6f6d 6d61 6e64 5574 696c 732e  ataCommandUtils.
 00002010: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
 00002020: 7072 6f70 6572 7479 5f61 735f 6461 7465  property_as_date
 00002030: 7469 6d65 6302 0000 0000 0000 0000 0000  timec...........
 00002040: 0002 0000 0003 0000 0043 0000 0073 0e00  .........C...s..
@@ -538,19 +538,19 @@
 00002190: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 000021a0: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 000021b0: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 000021c0: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 000021d0: 7065 7274 7920 7661 6c75 6520 646f 6573  perty value does
 000021e0: 6e27 7420 6578 6973 7420 6f72 2068 6173  n't exist or has
 000021f0: 2069 6e63 6f72 7265 6374 2066 6f72 6d61   incorrect forma
-00002200: 740a 2020 2020 2020 2020 2902 7218 0000  t.        ).r...
+00002200: 740a 2020 2020 2020 2020 2902 721c 0000  t.        ).r...
 00002210: 0072 2100 0000 7234 0000 0072 2600 0000  .r!...r4...r&...
 00002220: 7226 0000 0072 2700 0000 da1f 6765 745f  r&...r'.....get_
 00002230: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
-00002240: 7274 795f 6173 5f66 696c 65fb 0000 0073  rty_as_file....s
+00002240: 7274 795f 6173 5f66 696c 65f7 0000 0073  rty_as_file....s
 00002250: 0200 0000 0011 7a46 5461 736b 5361 7665  ......zFTaskSave
 00002260: 4a73 6f6e 466f 726d 7356 616c 7565 4461  JsonFormsValueDa
 00002270: 7461 436f 6d6d 616e 6455 7469 6c73 2e67  taCommandUtils.g
 00002280: 6574 5f6a 736f 6e5f 666f 726d 735f 7072  et_json_forms_pr
 00002290: 6f70 6572 7479 5f61 735f 6669 6c65 6302  operty_as_filec.
 000022a0: 0000 0000 0000 0000 0000 0002 0000 0003  ................
 000022b0: 0000 0043 0000 0073 0e00 0000 7400 7401  ...C...s....t.t.
@@ -576,19 +576,19 @@
 000023f0: 2020 2020 2054 6865 2070 726f 7065 7274       The propert
 00002400: 7920 7661 6c75 6520 6966 2065 7869 7374  y value if exist
 00002410: 732e 0a0a 2020 2020 2020 2020 5261 6973  s...        Rais
 00002420: 6573 3a0a 2020 2020 2020 2020 2020 2020  es:.            
 00002430: 5661 6c75 6545 7272 6f72 3a20 4966 2070  ValueError: If p
 00002440: 726f 7065 7274 7920 7661 6c75 6520 6861  roperty value ha
 00002450: 7320 696e 636f 7272 6563 7420 666f 726d  s incorrect form
-00002460: 6174 0a20 2020 2020 2020 2029 0272 0f00  at.        ).r..
+00002460: 6174 0a20 2020 2020 2020 2029 0272 1300  at.        ).r..
 00002470: 0000 7221 0000 0072 3400 0000 7226 0000  ..r!...r4...r&..
 00002480: 0072 2600 0000 7227 0000 00da 2066 696e  .r&...r'.... fin
 00002490: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
-000024a0: 7065 7274 795f 6173 5f66 696c 650e 0100  perty_as_file...
+000024a0: 7065 7274 795f 6173 5f66 696c 650a 0100  perty_as_file...
 000024b0: 0073 0200 0000 0011 7a47 5461 736b 5361  .s......zGTaskSa
 000024c0: 7665 4a73 6f6e 466f 726d 7356 616c 7565  veJsonFormsValue
 000024d0: 4461 7461 436f 6d6d 616e 6455 7469 6c73  DataCommandUtils
 000024e0: 2e66 696e 645f 6a73 6f6e 5f66 6f72 6d73  .find_json_forms
 000024f0: 5f70 726f 7065 7274 795f 6173 5f66 696c  _property_as_fil
 00002500: 6563 0200 0000 0000 0000 0000 0000 0200  ec..............
 00002510: 0000 0300 0000 4300 0000 730e 0000 0074  ......C...s....t
@@ -615,20 +615,20 @@
 00002660: 7920 7661 6c75 6520 6966 2065 7869 7374  y value if exist
 00002670: 732e 0a0a 2020 2020 2020 2020 5261 6973  s...        Rais
 00002680: 6573 3a0a 2020 2020 2020 2020 2020 2020  es:.            
 00002690: 5661 6c75 6545 7272 6f72 3a20 4966 2070  ValueError: If p
 000026a0: 726f 7065 7274 7920 7661 6c75 6520 646f  roperty value do
 000026b0: 6573 6e27 7420 6578 6973 7420 6f72 2068  esn't exist or h
 000026c0: 6173 2069 6e63 6f72 7265 6374 2066 6f72  as incorrect for
-000026d0: 6d61 740a 2020 2020 2020 2020 2902 7219  mat.        ).r.
+000026d0: 6d61 740a 2020 2020 2020 2020 2902 721d  mat.        ).r.
 000026e0: 0000 0072 2100 0000 7234 0000 0072 2600  ...r!...r4...r&.
 000026f0: 0000 7226 0000 0072 2700 0000 da24 6765  ..r&...r'....$ge
 00002700: 745f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  t_json_forms_pro
 00002710: 7065 7274 795f 6173 5f70 7269 6e63 6970  perty_as_princip
-00002720: 616c 2101 0000 7302 0000 0000 117a 4b54  al!...s......zKT
+00002720: 616c 1d01 0000 7302 0000 0000 117a 4b54  al....s......zKT
 00002730: 6173 6b53 6176 654a 736f 6e46 6f72 6d73  askSaveJsonForms
 00002740: 5661 6c75 6544 6174 6143 6f6d 6d61 6e64  ValueDataCommand
 00002750: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00002760: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00002770: 5f70 7269 6e63 6970 616c 6302 0000 0000  _principalc.....
 00002780: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
 00002790: 0000 0073 0e00 0000 7400 7401 7c00 8301  ...s....t.t.|...
@@ -654,20 +654,20 @@
 000028d0: 2020 2020 2020 5468 6520 7072 6f70 6572        The proper
 000028e0: 7479 2076 616c 7565 2069 6620 6578 6973  ty value if exis
 000028f0: 7473 2e0a 0a20 2020 2020 2020 2052 6169  ts...        Rai
 00002900: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 00002910: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 00002920: 7072 6f70 6572 7479 2076 616c 7565 2068  property value h
 00002930: 6173 2069 6e63 6f72 7265 6374 2066 6f72  as incorrect for
-00002940: 6d61 740a 2020 2020 2020 2020 2902 7210  mat.        ).r.
+00002940: 6d61 740a 2020 2020 2020 2020 2902 7214  mat.        ).r.
 00002950: 0000 0072 2100 0000 7234 0000 0072 2600  ...r!...r4...r&.
 00002960: 0000 7226 0000 0072 2700 0000 da25 6669  ..r&...r'....%fi
 00002970: 6e64 5f6a 736f 6e5f 666f 726d 735f 7072  nd_json_forms_pr
 00002980: 6f70 6572 7479 5f61 735f 7072 696e 6369  operty_as_princi
-00002990: 7061 6c34 0100 0073 0200 0000 0011 7a4c  pal4...s......zL
+00002990: 7061 6c30 0100 0073 0200 0000 0011 7a4c  pal0...s......zL
 000029a0: 5461 736b 5361 7665 4a73 6f6e 466f 726d  TaskSaveJsonForm
 000029b0: 7356 616c 7565 4461 7461 436f 6d6d 616e  sValueDataComman
 000029c0: 6455 7469 6c73 2e66 696e 645f 6a73 6f6e  dUtils.find_json
 000029d0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
 000029e0: 6173 5f70 7269 6e63 6970 616c 6302 0000  as_principalc...
 000029f0: 0000 0000 0000 0000 0002 0000 0003 0000  ................
 00002a00: 0043 0000 0073 0e00 0000 7400 7401 7c00  .C...s....t.t.|.
@@ -693,17 +693,17 @@
 00002b40: 616c 7565 2069 6620 6578 6973 7473 2e0a  alue if exists..
 00002b50: 0a20 2020 2020 2020 2052 6169 7365 733a  .        Raises:
 00002b60: 0a20 2020 2020 2020 2020 2020 2056 616c  .            Val
 00002b70: 7565 4572 726f 723a 2049 6620 7072 6f70  ueError: If prop
 00002b80: 6572 7479 2076 616c 7565 2064 6f65 736e  erty value doesn
 00002b90: 2774 2065 7869 7374 206f 7220 6861 7320  't exist or has 
 00002ba0: 696e 636f 7272 6563 7420 666f 726d 6174  incorrect format
-00002bb0: 0a20 2020 2020 2020 2029 0272 1a00 0000  .        ).r....
+00002bb0: 0a20 2020 2020 2020 2029 0272 1e00 0000  .        ).r....
 00002bc0: 7221 0000 0072 3400 0000 7226 0000 0072  r!...r4...r&...r
-00002bd0: 2600 0000 7227 0000 0072 1a00 0000 4701  &...r'...r....G.
+00002bd0: 2600 0000 7227 0000 0072 1e00 0000 4301  &...r'...r....C.
 00002be0: 0000 7302 0000 0000 0f7a 4654 6173 6b53  ..s......zFTaskS
 00002bf0: 6176 654a 736f 6e46 6f72 6d73 5661 6c75  aveJsonFormsValu
 00002c00: 6544 6174 6143 6f6d 6d61 6e64 5574 696c  eDataCommandUtil
 00002c10: 732e 6765 745f 6a73 6f6e 5f66 6f72 6d73  s.get_json_forms
 00002c20: 5f70 726f 7065 7274 795f 6173 5f6c 6973  _property_as_lis
 00002c30: 7463 0200 0000 0000 0000 0000 0000 0200  tc..............
 00002c40: 0000 0300 0000 4300 0000 730e 0000 0074  ......C...s....t
@@ -729,17 +729,17 @@
 00002d80: 6865 2070 726f 7065 7274 7920 7661 6c75  he property valu
 00002d90: 6520 6966 2065 7869 7374 732e 0a0a 2020  e if exists...  
 00002da0: 2020 2020 2020 5261 6973 6573 3a0a 2020        Raises:.  
 00002db0: 2020 2020 2020 2020 2020 5661 6c75 6545            ValueE
 00002dc0: 7272 6f72 3a20 4966 2070 726f 7065 7274  rror: If propert
 00002dd0: 7920 7661 6c75 6520 6861 7320 696e 636f  y value has inco
 00002de0: 7272 6563 7420 666f 726d 6174 0a20 2020  rrect format.   
-00002df0: 2020 2020 2029 0272 1100 0000 7221 0000       ).r....r!..
+00002df0: 2020 2020 2029 0272 1500 0000 7221 0000       ).r....r!..
 00002e00: 0072 3400 0000 7226 0000 0072 2600 0000  .r4...r&...r&...
-00002e10: 7227 0000 0072 1100 0000 5801 0000 7302  r'...r....X...s.
+00002e10: 7227 0000 0072 1500 0000 5401 0000 7302  r'...r....T...s.
 00002e20: 0000 0000 117a 4754 6173 6b53 6176 654a  .....zGTaskSaveJ
 00002e30: 736f 6e46 6f72 6d73 5661 6c75 6544 6174  sonFormsValueDat
 00002e40: 6143 6f6d 6d61 6e64 5574 696c 732e 6669  aCommandUtils.fi
 00002e50: 6e64 5f6a 736f 6e5f 666f 726d 735f 7072  nd_json_forms_pr
 00002e60: 6f70 6572 7479 5f61 735f 6c69 7374 6302  operty_as_listc.
 00002e70: 0000 0000 0000 0000 0000 0002 0000 0003  ................
 00002e80: 0000 0043 0000 0073 0e00 0000 7400 7401  ...C...s....t.t.
@@ -765,18 +765,18 @@
 00002fc0: 2076 616c 7565 2069 6620 6578 6973 7473   value if exists
 00002fd0: 2e0a 0a20 2020 2020 2020 2052 6169 7365  ...        Raise
 00002fe0: 733a 0a20 2020 2020 2020 2020 2020 2056  s:.            V
 00002ff0: 616c 7565 4572 726f 723a 2049 6620 7072  alueError: If pr
 00003000: 6f70 6572 7479 2076 616c 7565 2064 6f65  operty value doe
 00003010: 736e 2774 2065 7869 7374 206f 7220 6861  sn't exist or ha
 00003020: 7320 696e 636f 7272 6563 7420 666f 726d  s incorrect form
-00003030: 6174 0a20 2020 2020 2020 2029 0272 1500  at.        ).r..
+00003030: 6174 0a20 2020 2020 2020 2029 0272 1900  at.        ).r..
 00003040: 0000 7221 0000 0072 3400 0000 7226 0000  ..r!...r4...r&..
-00003050: 0072 2600 0000 7227 0000 0072 1500 0000  .r&...r'...r....
-00003060: 6b01 0000 7302 0000 0000 0f7a 4654 6173  k...s......zFTas
+00003050: 0072 2600 0000 7227 0000 0072 1900 0000  .r&...r'...r....
+00003060: 6701 0000 7302 0000 0000 0f7a 4654 6173  g...s......zFTas
 00003070: 6b53 6176 654a 736f 6e46 6f72 6d73 5661  kSaveJsonFormsVa
 00003080: 6c75 6544 6174 6143 6f6d 6d61 6e64 5574  lueDataCommandUt
 00003090: 696c 732e 6765 745f 6a73 6f6e 5f66 6f72  ils.get_json_for
 000030a0: 6d73 5f70 726f 7065 7274 795f 6173 5f64  ms_property_as_d
 000030b0: 6963 7463 0200 0000 0000 0000 0000 0000  ictc............
 000030c0: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
 000030d0: 0074 0074 017c 0083 017c 0183 0253 0029  .t.t.|...|...S.)
@@ -801,17 +801,17 @@
 00003200: 2054 6865 2070 726f 7065 7274 7920 7661   The property va
 00003210: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00003220: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00003230: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00003240: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00003250: 7274 7920 7661 6c75 6520 6861 7320 696e  rty value has in
 00003260: 636f 7272 6563 7420 666f 726d 6174 0a20  correct format. 
-00003270: 2020 2020 2020 2029 0272 0c00 0000 7221         ).r....r!
+00003270: 2020 2020 2020 2029 0272 1000 0000 7221         ).r....r!
 00003280: 0000 0072 3400 0000 7226 0000 0072 2600  ...r4...r&...r&.
-00003290: 0000 7227 0000 0072 0c00 0000 7c01 0000  ..r'...r....|...
+00003290: 0000 7227 0000 0072 1000 0000 7801 0000  ..r'...r....x...
 000032a0: 7302 0000 0000 117a 4754 6173 6b53 6176  s......zGTaskSav
 000032b0: 654a 736f 6e46 6f72 6d73 5661 6c75 6544  eJsonFormsValueD
 000032c0: 6174 6143 6f6d 6d61 6e64 5574 696c 732e  ataCommandUtils.
 000032d0: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
 000032e0: 7072 6f70 6572 7479 5f61 735f 6469 6374  property_as_dict
 000032f0: 4e29 0472 2300 0000 7233 0000 00da 0576  N).r#...r3.....v
 00003300: 616c 7565 7229 0000 0063 0300 0000 0000  aluer)...c......
@@ -838,54 +838,54 @@
 00003450: 2020 2020 2076 616c 7565 3a20 5661 6c75       value: Valu
 00003460: 6520 746f 2075 7064 6174 650a 0a20 2020  e to update..   
 00003470: 2020 2020 2052 6169 7365 733a 0a20 2020       Raises:.   
 00003480: 2020 2020 2020 2020 2056 616c 7565 4572           ValueEr
 00003490: 726f 723a 2049 6620 7072 6f70 6572 7479  ror: If property
 000034a0: 2076 616c 7565 2068 6173 2069 6e63 6f72   value has incor
 000034b0: 7265 6374 2066 6f72 6d61 740a 2020 2020  rect format.    
-000034c0: 2020 2020 4e29 0272 1c00 0000 7221 0000      N).r....r!..
+000034c0: 2020 2020 4e29 0272 2000 0000 7221 0000      N).r ...r!..
 000034d0: 0029 0372 2300 0000 7233 0000 0072 3900  .).r#...r3...r9.
 000034e0: 0000 7226 0000 0072 2600 0000 7227 0000  ..r&...r&...r'..
-000034f0: 0072 1c00 0000 8f01 0000 7302 0000 0000  .r........s.....
+000034f0: 0072 2000 0000 8b01 0000 7302 0000 0000  .r .......s.....
 00003500: 0f7a 4154 6173 6b53 6176 654a 736f 6e46  .zATaskSaveJsonF
 00003510: 6f72 6d73 5661 6c75 6544 6174 6143 6f6d  ormsValueDataCom
 00003520: 6d61 6e64 5574 696c 732e 7570 6461 7465  mandUtils.update
 00003530: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
 00003540: 6572 7479 2923 722e 0000 0072 2f00 0000  erty)#r....r/...
 00003550: 7230 0000 00da 0c73 7461 7469 636d 6574  r0.....staticmet
-00003560: 686f 6472 2000 0000 7231 0000 0072 1b00  hodr ...r1...r..
-00003570: 0000 7204 0000 0072 1200 0000 da03 696e  ..r....r......in
-00003580: 7472 1700 0000 720e 0000 00da 0566 6c6f  tr....r......flo
-00003590: 6174 7216 0000 0072 0d00 0000 7205 0000  atr....r....r...
-000035a0: 0072 1300 0000 720a 0000 0072 0600 0000  .r....r....r....
-000035b0: 7214 0000 0072 0b00 0000 721e 0000 0072  r....r....r....r
-000035c0: 3500 0000 7236 0000 0072 1f00 0000 7237  5...r6...r....r7
-000035d0: 0000 0072 3800 0000 da04 6c69 7374 721a  ...r8.....listr.
-000035e0: 0000 0072 1100 0000 da04 6469 6374 7215  ...r......dictr.
-000035f0: 0000 0072 0c00 0000 7209 0000 0072 1c00  ...r....r....r..
+00003560: 686f 6472 0a00 0000 7231 0000 0072 1f00  hodr....r1...r..
+00003570: 0000 7206 0000 0072 1600 0000 da03 696e  ..r....r......in
+00003580: 7472 1b00 0000 7212 0000 00da 0566 6c6f  tr....r......flo
+00003590: 6174 721a 0000 0072 1100 0000 7202 0000  atr....r....r...
+000035a0: 0072 1700 0000 720e 0000 0072 0300 0000  .r....r....r....
+000035b0: 7218 0000 0072 0f00 0000 7208 0000 0072  r....r....r....r
+000035c0: 3500 0000 7236 0000 0072 0900 0000 7237  5...r6...r....r7
+000035d0: 0000 0072 3800 0000 da04 6c69 7374 721e  ...r8.....listr.
+000035e0: 0000 0072 1500 0000 da04 6469 6374 7219  ...r......dictr.
+000035f0: 0000 0072 1000 0000 720d 0000 0072 2000  ...r....r....r .
 00003600: 0000 7226 0000 0072 2600 0000 7226 0000  ..r&...r&...r&..
-00003610: 0072 2700 0000 7232 0000 0046 0000 0073  .r'...r2...F...s
+00003610: 0072 2700 0000 7232 0000 0042 0000 0073  .r'...r2...B...s
 00003620: 9600 0000 0801 0201 1410 0202 0200 0201  ................
 00003630: 06fe 0e12 0201 1410 0202 0200 0201 06fe  ................
 00003640: 0e12 0201 1410 0202 0200 0201 06fe 0e12  ................
 00003650: 0201 1410 0202 0200 0201 06fe 0e12 0201  ................
 00003660: 1410 0202 0200 0201 06fe 0e12 0202 0200  ................
 00003670: 0201 02fe 0e12 0202 0200 0201 06fe 0e12  ................
 00003680: 0202 0200 0201 02fe 0e12 0202 0200 0201  ................
 00003690: 06fe 0e12 0201 1410 0202 0200 0201 06fe  ................
 000036a0: 0e12 0201 1410 0202 0200 0201 06fe 0e12  ................
 000036b0: 0202 0200 0200 0601 02fe 7232 0000 004e  ..........r2...N
-000036c0: 2922 da06 7479 7069 6e67 7202 0000 0072  )"..typingr....r
-000036d0: 0300 0000 7204 0000 0072 0600 0000 7205  ....r....r....r.
-000036e0: 0000 005a 0a6a 736f 6e5f 666f 726d 7372  ...Z.json_formsr
-000036f0: 0800 0000 7209 0000 0072 0a00 0000 720b  ....r....r....r.
-00003700: 0000 0072 0c00 0000 720d 0000 0072 0e00  ...r....r....r..
-00003710: 0000 720f 0000 0072 1000 0000 7211 0000  ..r....r....r...
-00003720: 0072 1200 0000 7213 0000 0072 1400 0000  .r....r....r....
-00003730: 7215 0000 0072 1600 0000 7217 0000 0072  r....r....r....r
-00003740: 1800 0000 7219 0000 0072 1a00 0000 721b  ....r....r....r.
-00003750: 0000 0072 1c00 0000 da06 6d6f 6465 6c73  ...r......models
+000036c0: 2922 7203 0000 0072 0200 0000 da06 7479  )"r....r......ty
+000036d0: 7069 6e67 7204 0000 0072 0500 0000 7206  pingr....r....r.
+000036e0: 0000 00da 066d 6f64 656c 7372 0800 0000  .....modelsr....
+000036f0: 7209 0000 0072 0a00 0000 5a0a 6a73 6f6e  r....r....Z.json
+00003700: 5f66 6f72 6d73 720c 0000 0072 0d00 0000  _formsr....r....
+00003710: 720e 0000 0072 0f00 0000 7210 0000 0072  r....r....r....r
+00003720: 1100 0000 7212 0000 0072 1300 0000 7214  ....r....r....r.
+00003730: 0000 0072 1500 0000 7216 0000 0072 1700  ...r....r....r..
+00003740: 0000 7218 0000 0072 1900 0000 721a 0000  ..r....r....r...
+00003750: 0072 1b00 0000 721c 0000 0072 1d00 0000  .r....r....r....
 00003760: 721e 0000 0072 1f00 0000 7220 0000 0072  r....r....r ...r
 00003770: 2100 0000 7232 0000 0072 2600 0000 7226  !...r2...r&...r&
 00003780: 0000 0072 2600 0000 7227 0000 00da 083c  ...r&...r'.....<
 00003790: 6d6f 6475 6c65 3e1a 0000 0073 0a00 0000  module>....s....
-000037a0: 1401 1002 5c17 1407 100b                 ....\.....
+000037a0: 1001 1402 1401 5c19 100b                 ......\...
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/_task_utils.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/_task_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 29357 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,142 +1,142 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 ad72 0000  U.......=S.d.r..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 ad72 0000  U..........d.r..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 5e01 0000 6400  .....@...s^...d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 6d04 5a04 0100 6400 6402 6c05 6d06 5a06  m.Z...d.d.l.m.Z.
-00000050: 6d05 5a05 0100 6403 6404 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
-00000060: 6d09 5a09 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f 6d10 5a10  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d11 5a11 6d12 5a12 6d13 5a13 6d14 5a14  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d15 5a15 6d16 5a16 6d17 5a17 6d18 5a18  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d19 5a19 6d1a 5a1a 6d1b 5a1b 6d1c 5a1c  m.Z.m.Z.m.Z.m.Z.
-000000b0: 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f 6d20 5a20  m.Z.m.Z.m.Z.m Z 
-000000c0: 6d21 5a21 6d22 5a22 6d23 5a23 6d24 5a24  m!Z!m"Z"m#Z#m$Z$
-000000d0: 0100 6403 6405 6c25 6d26 5a26 6d27 5a27  ..d.d.l%m&Z&m'Z'
-000000e0: 6d28 5a28 6d29 5a29 6d2a 5a2a 6d2b 5a2b  m(Z(m)Z)m*Z*m+Z+
-000000f0: 6d2c 5a2c 6d2d 5a2d 6d2e 5a2e 6d2f 5a2f  m,Z,m-Z-m.Z.m/Z/
-00000100: 6d30 5a30 6d31 5a31 6d32 5a32 6d33 5a33  m0Z0m1Z1m2Z2m3Z3
-00000110: 6d34 5a34 6d35 5a35 6d36 5a36 6d37 5a37  m4Z4m5Z5m6Z6m7Z7
-00000120: 6d38 5a38 6d39 5a39 6d3a 5a3a 0100 6406  m8Z8m9Z9m:Z:..d.
-00000130: 6407 6c3b 6d3c 5a3c 0100 6406 6408 6c3d  d.l;m<Z<..d.d.l=
+00000030: 6401 6c00 6d01 5a01 6d00 5a00 0100 6400  d.l.m.Z.m.Z...d.
+00000040: 6402 6c02 6d03 5a03 6d04 5a04 6d05 5a05  d.l.m.Z.m.Z.m.Z.
+00000050: 6d06 5a06 0100 6403 6404 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
+00000060: 0100 6403 6405 6c09 6d0a 5a0a 6d0b 5a0b  ..d.d.l.m.Z.m.Z.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 0100 6406 6407 6c10 6d11 5a11 6d12 5a12  ..d.d.l.m.Z.m.Z.
+00000090: 6d13 5a13 6d14 5a14 6d15 5a15 6d16 5a16  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d17 5a17 6d18 5a18 6d19 5a19 6d1a 5a1a  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1b 5a1b 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e  m.Z.m.Z.m.Z.m.Z.
+000000c0: 6d1f 5a1f 6d20 5a20 6d21 5a21 6d22 5a22  m.Z.m Z m!Z!m"Z"
+000000d0: 6d23 5a23 6d24 5a24 6d25 5a25 6d26 5a26  m#Z#m$Z$m%Z%m&Z&
+000000e0: 6d27 5a27 6d28 5a28 6d29 5a29 6d2a 5a2a  m'Z'm(Z(m)Z)m*Z*
+000000f0: 6d2b 5a2b 6d2c 5a2c 6d2d 5a2d 0100 6406  m+Z+m,Z,m-Z-..d.
+00000100: 6408 6c2e 6d2f 5a2f 6d30 5a30 6d31 5a31  d.l.m/Z/m0Z0m1Z1
+00000110: 6d32 5a32 6d33 5a33 6d34 5a34 6d35 5a35  m2Z2m3Z3m4Z4m5Z5
+00000120: 6d36 5a36 6d37 5a37 6d38 5a38 6d39 5a39  m6Z6m7Z7m8Z8m9Z9
+00000130: 6d3a 5a3a 6d3b 5a3b 6d3c 5a3c 6d3d 5a3d  m:Z:m;Z;m<Z<m=Z=
 00000140: 6d3e 5a3e 6d3f 5a3f 6d40 5a40 6d41 5a41  m>Z>m?Z?m@Z@mAZA
 00000150: 6d42 5a42 6d43 5a43 0100 4700 6409 640a  mBZBmCZC..G.d.d.
-00000160: 8400 640a 650a 8303 5a44 4700 640b 640c  ..d.e...ZDG.d.d.
-00000170: 8400 640c 6526 8303 5a45 4700 640d 640e  ..d.e&..ZEG.d.d.
+00000160: 8400 640a 6513 8303 5a44 4700 640b 640c  ..d.e...ZDG.d.d.
+00000170: 8400 640c 652f 8303 5a45 4700 640d 640e  ..d.e/..ZEG.d.d.
 00000180: 8400 640e 8302 5a46 640f 5300 2910 e900  ..d...ZFd.S.)...
-00000190: 0000 0029 04da 0341 6e79 da04 4469 6374  ...)...Any..Dict
-000001a0: da04 4c69 7374 da08 4f70 7469 6f6e 616c  ..List..Optional
-000001b0: 2902 da04 6461 7465 da08 6461 7465 7469  )...date..dateti
-000001c0: 6d65 e901 0000 0029 1dda 1645 6c65 6d65  me.....)...Eleme
-000001d0: 6e74 5661 6c75 6553 696d 706c 6554 7970  ntValueSimpleTyp
-000001e0: 65da 1145 6c65 6d65 6e74 5661 6c75 6555  e..ElementValueU
-000001f0: 6e69 6f6e da18 5461 736b 456c 656d 656e  nion..TaskElemen
-00000200: 7456 616c 7565 4163 6365 7373 6f72 da11  tValueAccessor..
-00000210: 6164 645f 656c 656d 656e 745f 7661 6c75  add_element_valu
-00000220: 65da 1661 6464 5f65 6c65 6d65 6e74 5f76  e..add_element_v
-00000230: 616c 7565 5f6c 6973 74da 1a66 696e 645f  alue_list..find_
-00000240: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
-00000250: 5f64 6174 65da 1a66 696e 645f 656c 656d  _date..find_elem
-00000260: 656e 745f 7661 6c75 655f 6173 5f64 6963  ent_value_as_dic
-00000270: 74da 1e66 696e 645f 656c 656d 656e 745f  t..find_element_
-00000280: 7661 6c75 655f 6173 5f64 6f63 756d 656e  value_as_documen
-00000290: 74da 1b66 696e 645f 656c 656d 656e 745f  t..find_element_
-000002a0: 7661 6c75 655f 6173 5f66 6c6f 6174 da1f  value_as_float..
-000002b0: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
-000002c0: 7565 5f61 735f 7072 696e 6369 7061 6cda  ue_as_principal.
-000002d0: 1966 696e 645f 656c 656d 656e 745f 7661  .find_element_va
-000002e0: 6c75 655f 6173 5f73 7472 da19 6765 745f  lue_as_str..get_
-000002f0: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
-00000300: 5f64 6174 65da 1e67 6574 5f65 6c65 6d65  _date..get_eleme
-00000310: 6e74 5f76 616c 7565 5f61 735f 6461 7465  nt_value_as_date
-00000320: 5f6c 6973 74da 1967 6574 5f65 6c65 6d65  _list..get_eleme
-00000330: 6e74 5f76 616c 7565 5f61 735f 6469 6374  nt_value_as_dict
-00000340: da1e 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-00000350: 6c75 655f 6173 5f64 6963 745f 6c69 7374  lue_as_dict_list
-00000360: da1d 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-00000370: 6c75 655f 6173 5f64 6f63 756d 656e 74da  lue_as_document.
-00000380: 2267 6574 5f65 6c65 6d65 6e74 5f76 616c  "get_element_val
-00000390: 7565 5f61 735f 646f 6375 6d65 6e74 5f6c  ue_as_document_l
-000003a0: 6973 74da 1a67 6574 5f65 6c65 6d65 6e74  ist..get_element
-000003b0: 5f76 616c 7565 5f61 735f 666c 6f61 74da  _value_as_float.
-000003c0: 1f67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
-000003d0: 7565 5f61 735f 666c 6f61 745f 6c69 7374  ue_as_float_list
-000003e0: da1e 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-000003f0: 6c75 655f 6173 5f70 7269 6e63 6970 616c  lue_as_principal
-00000400: da23 6765 745f 656c 656d 656e 745f 7661  .#get_element_va
-00000410: 6c75 655f 6173 5f70 7269 6e63 6970 616c  lue_as_principal
-00000420: 5f6c 6973 74da 1867 6574 5f65 6c65 6d65  _list..get_eleme
-00000430: 6e74 5f76 616c 7565 5f61 735f 7374 72da  nt_value_as_str.
-00000440: 1d67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
-00000450: 7565 5f61 735f 7374 725f 6c69 7374 da17  ue_as_str_list..
-00000460: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
-00000470: 655f 7661 6c69 64da 1a67 6574 5f65 6c65  e_valid..get_ele
-00000480: 6d65 6e74 5f76 616c 7565 5f76 616c 6964  ment_value_valid
-00000490: 5f61 74da 1173 6574 5f65 6c65 6d65 6e74  _at..set_element
-000004a0: 5f76 616c 7565 da16 7365 745f 656c 656d  _value..set_elem
-000004b0: 656e 745f 7661 6c75 655f 6c69 7374 da17  ent_value_list..
-000004c0: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
-000004d0: 655f 7661 6c69 64da 1a73 6574 5f65 6c65  e_valid..set_ele
-000004e0: 6d65 6e74 5f76 616c 7565 5f76 616c 6964  ment_value_valid
-000004f0: 5f61 7429 15da 144a 736f 6e46 6f72 6d44  _at)...JsonFormD
-00000500: 6174 6141 6363 6573 736f 72da 134a 736f  ataAccessor..Jso
-00000510: 6e46 6f72 6d73 5369 6d70 6c65 5479 7065  nFormsSimpleType
-00000520: da20 6669 6e64 5f6a 736f 6e5f 666f 726d  . find_json_form
-00000530: 735f 7072 6f70 6572 7479 5f61 735f 6461  s_property_as_da
-00000540: 7465 da24 6669 6e64 5f6a 736f 6e5f 666f  te.$find_json_fo
-00000550: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
-00000560: 6461 7465 7469 6d65 da20 6669 6e64 5f6a  datetime. find_j
-00000570: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
-00000580: 7479 5f61 735f 6469 6374 da21 6669 6e64  ty_as_dict.!find
-00000590: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
-000005a0: 6572 7479 5f61 735f 666c 6f61 74da 1f66  erty_as_float..f
-000005b0: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
-000005c0: 726f 7065 7274 795f 6173 5f69 6e74 da2b  roperty_as_int.+
-000005d0: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
-000005e0: 7072 6f70 6572 7479 5f61 735f 6a73 6f6e  property_as_json
-000005f0: 5f66 6f72 6d73 5f66 696c 65da 3066 696e  _forms_file.0fin
-00000600: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
-00000610: 7065 7274 795f 6173 5f6a 736f 6e5f 666f  perty_as_json_fo
-00000620: 726d 735f 7072 696e 6369 7061 6cda 2066  rms_principal. f
-00000630: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
-00000640: 726f 7065 7274 795f 6173 5f6c 6973 74da  roperty_as_list.
-00000650: 1f66 696e 645f 6a73 6f6e 5f66 6f72 6d73  .find_json_forms
-00000660: 5f70 726f 7065 7274 795f 6173 5f73 7472  _property_as_str
-00000670: da1f 6765 745f 6a73 6f6e 5f66 6f72 6d73  ..get_json_forms
-00000680: 5f70 726f 7065 7274 795f 6173 5f64 6174  _property_as_dat
-00000690: 65da 2367 6574 5f6a 736f 6e5f 666f 726d  e.#get_json_form
-000006a0: 735f 7072 6f70 6572 7479 5f61 735f 6461  s_property_as_da
-000006b0: 7465 7469 6d65 da1f 6765 745f 6a73 6f6e  tetime..get_json
-000006c0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
-000006d0: 6173 5f64 6963 74da 2067 6574 5f6a 736f  as_dict. get_jso
-000006e0: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
-000006f0: 5f61 735f 666c 6f61 74da 1e67 6574 5f6a  _as_float..get_j
-00000700: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
-00000710: 7479 5f61 735f 696e 74da 2a67 6574 5f6a  ty_as_int.*get_j
-00000720: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
-00000730: 7479 5f61 735f 6a73 6f6e 5f66 6f72 6d73  ty_as_json_forms
-00000740: 5f66 696c 65da 2f67 6574 5f6a 736f 6e5f  _file./get_json_
-00000750: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
-00000760: 735f 6a73 6f6e 5f66 6f72 6d73 5f70 7269  s_json_forms_pri
-00000770: 6e63 6970 616c da1f 6765 745f 6a73 6f6e  ncipal..get_json
-00000780: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
-00000790: 6173 5f6c 6973 74da 1e67 6574 5f6a 736f  as_list..get_jso
-000007a0: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
-000007b0: 5f61 735f 7374 72da 1a75 7064 6174 655f  _as_str..update_
-000007c0: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
-000007d0: 7274 79e9 0200 0000 2901 da10 5461 736b  rty.....)...Task
-000007e0: 456c 656d 656e 7456 616c 7565 2906 da0d  ElementValue)...
-000007f0: 4a73 6f6e 466f 726d 7346 696c 65da 124a  JsonFormsFile..J
-00000800: 736f 6e46 6f72 6d73 5072 696e 6369 7061  sonFormsPrincipa
-00000810: 6cda 0e4a 736f 6e46 6f72 6d73 5661 6c75  l..JsonFormsValu
-00000820: 65da 0454 6173 6bda 1c54 6173 6b45 6c65  e..Task..TaskEle
-00000830: 6d65 6e74 5661 6c75 6544 6f63 756d 656e  mentValueDocumen
-00000840: 7449 7465 6dda 1d54 6173 6b45 6c65 6d65  tItem..TaskEleme
-00000850: 6e74 5661 6c75 6550 7269 6e63 6970 616c  ntValuePrincipal
-00000860: 4974 656d 6300 0000 0000 0000 0000 0000  Itemc...........
+00000190: 0000 0029 02da 0464 6174 65da 0864 6174  ...)...date..dat
+000001a0: 6574 696d 6529 04da 0341 6e79 da04 4469  etime)...Any..Di
+000001b0: 6374 da04 4c69 7374 da08 4f70 7469 6f6e  ct..List..Option
+000001c0: 616c e902 0000 0029 01da 1054 6173 6b45  al.....)...TaskE
+000001d0: 6c65 6d65 6e74 5661 6c75 6529 06da 0d4a  lementValue)...J
+000001e0: 736f 6e46 6f72 6d73 4669 6c65 da12 4a73  sonFormsFile..Js
+000001f0: 6f6e 466f 726d 7350 7269 6e63 6970 616c  onFormsPrincipal
+00000200: da0e 4a73 6f6e 466f 726d 7356 616c 7565  ..JsonFormsValue
+00000210: da04 5461 736b da1c 5461 736b 456c 656d  ..Task..TaskElem
+00000220: 656e 7456 616c 7565 446f 6375 6d65 6e74  entValueDocument
+00000230: 4974 656d da1d 5461 736b 456c 656d 656e  Item..TaskElemen
+00000240: 7456 616c 7565 5072 696e 6369 7061 6c49  tValuePrincipalI
+00000250: 7465 6de9 0100 0000 291d da16 456c 656d  tem.....)...Elem
+00000260: 656e 7456 616c 7565 5369 6d70 6c65 5479  entValueSimpleTy
+00000270: 7065 da11 456c 656d 656e 7456 616c 7565  pe..ElementValue
+00000280: 556e 696f 6eda 1854 6173 6b45 6c65 6d65  Union..TaskEleme
+00000290: 6e74 5661 6c75 6541 6363 6573 736f 72da  ntValueAccessor.
+000002a0: 1161 6464 5f65 6c65 6d65 6e74 5f76 616c  .add_element_val
+000002b0: 7565 da16 6164 645f 656c 656d 656e 745f  ue..add_element_
+000002c0: 7661 6c75 655f 6c69 7374 da1a 6669 6e64  value_list..find
+000002d0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
+000002e0: 735f 6461 7465 da1a 6669 6e64 5f65 6c65  s_date..find_ele
+000002f0: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
+00000300: 6374 da1e 6669 6e64 5f65 6c65 6d65 6e74  ct..find_element
+00000310: 5f76 616c 7565 5f61 735f 646f 6375 6d65  _value_as_docume
+00000320: 6e74 da1b 6669 6e64 5f65 6c65 6d65 6e74  nt..find_element
+00000330: 5f76 616c 7565 5f61 735f 666c 6f61 74da  _value_as_float.
+00000340: 1f66 696e 645f 656c 656d 656e 745f 7661  .find_element_va
+00000350: 6c75 655f 6173 5f70 7269 6e63 6970 616c  lue_as_principal
+00000360: da19 6669 6e64 5f65 6c65 6d65 6e74 5f76  ..find_element_v
+00000370: 616c 7565 5f61 735f 7374 72da 1967 6574  alue_as_str..get
+00000380: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
+00000390: 735f 6461 7465 da1e 6765 745f 656c 656d  s_date..get_elem
+000003a0: 656e 745f 7661 6c75 655f 6173 5f64 6174  ent_value_as_dat
+000003b0: 655f 6c69 7374 da19 6765 745f 656c 656d  e_list..get_elem
+000003c0: 656e 745f 7661 6c75 655f 6173 5f64 6963  ent_value_as_dic
+000003d0: 74da 1e67 6574 5f65 6c65 6d65 6e74 5f76  t..get_element_v
+000003e0: 616c 7565 5f61 735f 6469 6374 5f6c 6973  alue_as_dict_lis
+000003f0: 74da 1d67 6574 5f65 6c65 6d65 6e74 5f76  t..get_element_v
+00000400: 616c 7565 5f61 735f 646f 6375 6d65 6e74  alue_as_document
+00000410: da22 6765 745f 656c 656d 656e 745f 7661  ."get_element_va
+00000420: 6c75 655f 6173 5f64 6f63 756d 656e 745f  lue_as_document_
+00000430: 6c69 7374 da1a 6765 745f 656c 656d 656e  list..get_elemen
+00000440: 745f 7661 6c75 655f 6173 5f66 6c6f 6174  t_value_as_float
+00000450: da1f 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
+00000460: 6c75 655f 6173 5f66 6c6f 6174 5f6c 6973  lue_as_float_lis
+00000470: 74da 1e67 6574 5f65 6c65 6d65 6e74 5f76  t..get_element_v
+00000480: 616c 7565 5f61 735f 7072 696e 6369 7061  alue_as_principa
+00000490: 6cda 2367 6574 5f65 6c65 6d65 6e74 5f76  l.#get_element_v
+000004a0: 616c 7565 5f61 735f 7072 696e 6369 7061  alue_as_principa
+000004b0: 6c5f 6c69 7374 da18 6765 745f 656c 656d  l_list..get_elem
+000004c0: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
+000004d0: da1d 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
+000004e0: 6c75 655f 6173 5f73 7472 5f6c 6973 74da  lue_as_str_list.
+000004f0: 1767 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
+00000500: 7565 5f76 616c 6964 da1a 6765 745f 656c  ue_valid..get_el
+00000510: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
+00000520: 645f 6174 da11 7365 745f 656c 656d 656e  d_at..set_elemen
+00000530: 745f 7661 6c75 65da 1673 6574 5f65 6c65  t_value..set_ele
+00000540: 6d65 6e74 5f76 616c 7565 5f6c 6973 74da  ment_value_list.
+00000550: 1773 6574 5f65 6c65 6d65 6e74 5f76 616c  .set_element_val
+00000560: 7565 5f76 616c 6964 da1a 7365 745f 656c  ue_valid..set_el
+00000570: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
+00000580: 645f 6174 2915 da14 4a73 6f6e 466f 726d  d_at)...JsonForm
+00000590: 4461 7461 4163 6365 7373 6f72 da13 4a73  DataAccessor..Js
+000005a0: 6f6e 466f 726d 7353 696d 706c 6554 7970  onFormsSimpleTyp
+000005b0: 65da 2066 696e 645f 6a73 6f6e 5f66 6f72  e. find_json_for
+000005c0: 6d73 5f70 726f 7065 7274 795f 6173 5f64  ms_property_as_d
+000005d0: 6174 65da 2466 696e 645f 6a73 6f6e 5f66  ate.$find_json_f
+000005e0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
+000005f0: 5f64 6174 6574 696d 65da 2066 696e 645f  _datetime. find_
+00000600: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
+00000610: 7274 795f 6173 5f64 6963 74da 2166 696e  rty_as_dict.!fin
+00000620: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
+00000630: 7065 7274 795f 6173 5f66 6c6f 6174 da1f  perty_as_float..
+00000640: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
+00000650: 7072 6f70 6572 7479 5f61 735f 696e 74da  property_as_int.
+00000660: 2b66 696e 645f 6a73 6f6e 5f66 6f72 6d73  +find_json_forms
+00000670: 5f70 726f 7065 7274 795f 6173 5f6a 736f  _property_as_jso
+00000680: 6e5f 666f 726d 735f 6669 6c65 da30 6669  n_forms_file.0fi
+00000690: 6e64 5f6a 736f 6e5f 666f 726d 735f 7072  nd_json_forms_pr
+000006a0: 6f70 6572 7479 5f61 735f 6a73 6f6e 5f66  operty_as_json_f
+000006b0: 6f72 6d73 5f70 7269 6e63 6970 616c da20  orms_principal. 
+000006c0: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
+000006d0: 7072 6f70 6572 7479 5f61 735f 6c69 7374  property_as_list
+000006e0: da1f 6669 6e64 5f6a 736f 6e5f 666f 726d  ..find_json_form
+000006f0: 735f 7072 6f70 6572 7479 5f61 735f 7374  s_property_as_st
+00000700: 72da 1f67 6574 5f6a 736f 6e5f 666f 726d  r..get_json_form
+00000710: 735f 7072 6f70 6572 7479 5f61 735f 6461  s_property_as_da
+00000720: 7465 da23 6765 745f 6a73 6f6e 5f66 6f72  te.#get_json_for
+00000730: 6d73 5f70 726f 7065 7274 795f 6173 5f64  ms_property_as_d
+00000740: 6174 6574 696d 65da 1f67 6574 5f6a 736f  atetime..get_jso
+00000750: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
+00000760: 5f61 735f 6469 6374 da20 6765 745f 6a73  _as_dict. get_js
+00000770: 6f6e 5f66 6f72 6d73 5f70 726f 7065 7274  on_forms_propert
+00000780: 795f 6173 5f66 6c6f 6174 da1e 6765 745f  y_as_float..get_
+00000790: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
+000007a0: 7274 795f 6173 5f69 6e74 da2a 6765 745f  rty_as_int.*get_
+000007b0: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
+000007c0: 7274 795f 6173 5f6a 736f 6e5f 666f 726d  rty_as_json_form
+000007d0: 735f 6669 6c65 da2f 6765 745f 6a73 6f6e  s_file./get_json
+000007e0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
+000007f0: 6173 5f6a 736f 6e5f 666f 726d 735f 7072  as_json_forms_pr
+00000800: 696e 6369 7061 6cda 1f67 6574 5f6a 736f  incipal..get_jso
+00000810: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
+00000820: 5f61 735f 6c69 7374 da1e 6765 745f 6a73  _as_list..get_js
+00000830: 6f6e 5f66 6f72 6d73 5f70 726f 7065 7274  on_forms_propert
+00000840: 795f 6173 5f73 7472 da1a 7570 6461 7465  y_as_str..update
+00000850: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
+00000860: 6572 7479 6300 0000 0000 0000 0000 0000  ertyc...........
 00000870: 0000 0000 0003 0000 0040 0000 0073 4000  .........@...s@.
 00000880: 0000 6500 5a01 6400 5a02 6503 6504 6401  ..e.Z.d.Z.e.e.d.
 00000890: 9c02 6402 6403 8404 5a05 6506 6507 1900  ..d.d...Z.e.e...
 000008a0: 6404 9c01 6405 6406 8404 5a08 6506 6509  d...d.d...Z.e.e.
 000008b0: 1900 6407 9c01 6408 6409 8404 5a0a 640a  ..d...d.d...Z.d.
 000008c0: 5300 290b da1b 4375 7272 656e 7445 6c65  S.)...CurrentEle
 000008d0: 6d65 6e74 5661 6c75 6541 6363 6573 736f  mentValueAccesso
@@ -187,17 +187,17 @@
 00000ba0: 616c 7565 736c 0000 0073 0c00 0000 0001  aluesl...s......
 00000bb0: 0c01 0402 1001 1401 0402 7a2e 4375 7272  ..........z.Curr
 00000bc0: 656e 7445 6c65 6d65 6e74 5661 6c75 6541  entElementValueA
 00000bd0: 6363 6573 736f 722e 6765 745f 656c 656d  ccessor.get_elem
 00000be0: 656e 745f 7661 6c75 6573 4e29 0bda 085f  ent_valuesN)..._
 00000bf0: 5f6e 616d 655f 5fda 0a5f 5f6d 6f64 756c  _name__..__modul
 00000c00: 655f 5fda 0c5f 5f71 7561 6c6e 616d 655f  e__..__qualname_
-00000c10: 5f72 4000 0000 da03 7374 7272 4b00 0000  _r@.....strrK...
-00000c20: 7204 0000 0072 0a00 0000 7250 0000 0072  r....r....rP...r
-00000c30: 3c00 0000 7255 0000 0072 4900 0000 7249  <...rU...rI...rI
+00000c10: 5f72 0d00 0000 da03 7374 7272 4b00 0000  _r......strrK...
+00000c20: 7206 0000 0072 1200 0000 7250 0000 0072  r....r....rP...r
+00000c30: 0900 0000 7255 0000 0072 4900 0000 7249  ....rU...rI...rI
 00000c40: 0000 0072 4900 0000 724a 0000 0072 4300  ...rI...rJ...rC.
 00000c50: 0000 5e00 0000 7306 0000 0008 0110 0412  ..^...s.........
 00000c60: 0972 4300 0000 6300 0000 0000 0000 0000  .rC...c.........
 00000c70: 0000 0000 0000 0004 0000 0040 0000 0073  ...........@...s
 00000c80: 4e00 0000 6500 5a01 6400 5a02 6503 6401  N...e.Z.d.Z.e.d.
 00000c90: 9c01 6402 6403 8404 5a04 6505 6506 6507  ..d.d...Z.e.e.e.
 00000ca0: 6508 6602 1900 1900 6404 9c01 6405 6406  e.f.....d...d.d.
@@ -226,24 +226,24 @@
 00000e10: 7265 6e74 4a73 6f6e 466f 726d 4461 7461  rentJsonFormData
 00000e20: 4163 6365 7373 6f72 2e67 6574 5f64 6174  Accessor.get_dat
 00000e30: 6129 0172 5d00 0000 6302 0000 0000 0000  a).r]...c.......
 00000e40: 0000 0000 0002 0000 0002 0000 0043 0000  .............C..
 00000e50: 0073 2400 0000 7c00 6a00 6a01 6400 6b08  .s$...|.j.j.d.k.
 00000e60: 7216 7402 8300 7c00 6a00 5f01 7c01 7c00  r.t...|.j._.|.|.
 00000e70: 6a00 6a01 5f03 6400 5300 7247 0000 0029  j.j._.d.S.rG...)
-00000e80: 0472 4500 0000 725c 0000 0072 3f00 0000  .rE...r\...r?...
+00000e80: 0472 4500 0000 725c 0000 0072 0c00 0000  .rE...r\...r....
 00000e90: 725d 0000 0029 0272 4800 0000 725d 0000  r]...).rH...r]..
 00000ea0: 0072 4900 0000 7249 0000 0072 4a00 0000  .rI...rI...rJ...
 00000eb0: da08 7365 745f 6461 7461 8100 0000 7306  ..set_data....s.
 00000ec0: 0000 0000 010c 010a 027a 2443 7572 7265  .........z$Curre
 00000ed0: 6e74 4a73 6f6e 466f 726d 4461 7461 4163  ntJsonFormDataAc
 00000ee0: 6365 7373 6f72 2e73 6574 5f64 6174 614e  cessor.set_dataN
 00000ef0: 290b 7256 0000 0072 5700 0000 7258 0000  ).rV...rW...rX..
-00000f00: 0072 4000 0000 724b 0000 0072 0500 0000  .r@...rK...r....
-00000f10: 7203 0000 0072 5900 0000 7202 0000 0072  r....rY...r....r
+00000f00: 0072 0d00 0000 724b 0000 0072 0700 0000  .r....rK...r....
+00000f10: 7205 0000 0072 5900 0000 7204 0000 0072  r....rY...r....r
 00000f20: 5e00 0000 725f 0000 0072 4900 0000 7249  ^...r_...rI...rI
 00000f30: 0000 0072 4900 0000 724a 0000 0072 5a00  ...rI...rJ...rZ.
 00000f40: 0000 7700 0000 7306 0000 0008 010e 031a  ..w...s.........
 00000f50: 0672 5a00 0000 6300 0000 0000 0000 0000  .rZ...c.........
 00000f60: 0000 0000 0000 0007 0000 0040 0000 0073  ...........@...s
 00000f70: 8004 0000 6500 5a01 6400 5a02 6503 6504  ....e.Z.d.Z.e.e.
 00000f80: 6505 6506 6401 9c03 6402 6403 8404 8301  e.e.d...d.d.....
@@ -334,17 +334,17 @@
 000014d0: 6c65 6d65 6e74 2044 6566 696e 6974 696f  lement Definitio
 000014e0: 6e20 436f 6465 2e0a 0a20 2020 2020 2020  n Code...       
 000014f0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001500: 2020 2020 2020 5472 7565 2069 6620 616c        True if al
 00001510: 6c20 7265 6c61 7465 6420 7661 6c69 6420  l related valid 
 00001520: 7661 6c75 6573 2061 7265 2054 5255 452c  values are TRUE,
 00001530: 206f 7468 6572 7769 7365 2046 616c 7365   otherwise False
-00001540: 2e0a 2020 2020 2020 2020 2902 7220 0000  ..        ).r ..
+00001540: 2e0a 2020 2020 2020 2020 2902 7228 0000  ..        ).r(..
 00001550: 0072 4300 0000 7244 0000 0072 4900 0000  .rC...rD...rI...
-00001560: 7249 0000 0072 4a00 0000 7220 0000 0089  rI...rJ...r ....
+00001560: 7249 0000 0072 4a00 0000 7228 0000 0089  rI...rJ...r(....
 00001570: 0000 0073 0200 0000 000c 7a21 5461 736b  ...s......z!Task
 00001580: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 00001590: 745f 7661 6c75 655f 7661 6c69 6429 0472  t_value_valid).r
 000015a0: 4500 0000 7246 0000 00da 0569 6e64 6578  E...rF.....index
 000015b0: 7252 0000 0063 0300 0000 0000 0000 0000  rR...c..........
 000015c0: 0000 0300 0000 0400 0000 4300 0000 7310  ..........C...s.
 000015d0: 0000 0074 0074 017c 007c 0183 027c 0283  ...t.t.|.|...|..
@@ -365,17 +365,17 @@
 000016c0: 6e74 2076 616c 7565 2069 6e64 6578 2e0a  nt value index..
 000016d0: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 000016e0: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 000016f0: 6520 7265 7175 6573 7465 6420 7661 6c69  e requested vali
 00001700: 6420 7661 6c75 6520 6966 2069 7420 6578  d value if it ex
 00001710: 6973 7473 2c20 6f74 6865 7277 6973 6520  ists, otherwise 
 00001720: 4e6f 6e65 2e0a 2020 2020 2020 2020 2902  None..        ).
-00001730: 7221 0000 0072 4300 0000 2903 7245 0000  r!...rC...).rE..
+00001730: 7229 0000 0072 4300 0000 2903 7245 0000  r)...rC...).rE..
 00001740: 0072 4600 0000 7261 0000 0072 4900 0000  .rF...ra...rI...
-00001750: 7249 0000 0072 4a00 0000 7221 0000 0097  rI...rJ...r!....
+00001750: 7249 0000 0072 4a00 0000 7229 0000 0097  rI...rJ...r)....
 00001760: 0000 0073 0200 0000 0011 7a24 5461 736b  ...s......z$Task
 00001770: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 00001780: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
 00001790: 2904 7245 0000 0072 4600 0000 da05 7661  ).rE...rF.....va
 000017a0: 6c69 6472 5200 0000 6303 0000 0000 0000  lidrR...c.......
 000017b0: 0000 0000 0003 0000 0004 0000 0043 0000  .............C..
 000017c0: 0073 1400 0000 7400 7401 7c00 7c01 8302  .s....t.t.|.|...
@@ -392,18 +392,18 @@
 00001870: 6c65 6d65 6e74 2064 6566 696e 6974 696f  lement definitio
 00001880: 6e20 636f 6465 2e0a 2020 2020 2020 2020  n code..        
 00001890: 2020 2020 7661 6c69 643a 2054 6865 2076      valid: The v
 000018a0: 616c 6964 2076 616c 7565 2e0a 0a20 2020  alid value...   
 000018b0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 000018c0: 2020 2020 2020 2020 2020 5468 6520 7061            The pa
 000018d0: 7373 6564 2074 6173 6b2e 0a20 2020 2020  ssed task..     
-000018e0: 2020 2029 0272 2400 0000 7243 0000 0029     ).r$...rC...)
+000018e0: 2020 2029 0272 2c00 0000 7243 0000 0029     ).r,...rC...)
 000018f0: 0372 4500 0000 7246 0000 0072 6200 0000  .rE...rF...rb...
 00001900: 7249 0000 0072 4900 0000 724a 0000 0072  rI...rI...rJ...r
-00001910: 2400 0000 aa00 0000 7304 0000 0000 0d10  $.......s.......
+00001910: 2c00 0000 aa00 0000 7304 0000 0000 0d10  ,.......s.......
 00001920: 027a 2154 6173 6b55 7469 6c73 2e73 6574  .z!TaskUtils.set
 00001930: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
 00001940: 616c 6964 2905 7245 0000 0072 4600 0000  alid).rE...rF...
 00001950: 7262 0000 0072 6100 0000 7252 0000 0063  rb...ra...rR...c
 00001960: 0400 0000 0000 0000 0000 0000 0400 0000  ................
 00001970: 0400 0000 4300 0000 7316 0000 0074 0074  ....C...s....t.t
 00001980: 017c 007c 0183 027c 027c 0383 0301 007c  .|.|...|.|.....|
@@ -423,18 +423,18 @@
 00001a60: 7661 6c69 6420 7661 6c75 652e 0a20 2020  valid value..   
 00001a70: 2020 2020 2020 2020 2069 6e64 6578 3a20           index: 
 00001a80: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00001a90: 6520 696e 6465 782e 0a0a 2020 2020 2020  e index...      
 00001aa0: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00001ab0: 2020 2020 2020 2054 6865 2070 6173 7365         The passe
 00001ac0: 6420 7461 736b 2e0a 2020 2020 2020 2020  d task..        
-00001ad0: 2902 7225 0000 0072 4300 0000 2904 7245  ).r%...rC...).rE
+00001ad0: 2902 722d 0000 0072 4300 0000 2904 7245  ).r-...rC...).rE
 00001ae0: 0000 0072 4600 0000 7262 0000 0072 6100  ...rF...rb...ra.
 00001af0: 0000 7249 0000 0072 4900 0000 724a 0000  ..rI...rI...rJ..
-00001b00: 0072 2500 0000 bb00 0000 7304 0000 0000  .r%.......s.....
+00001b00: 0072 2d00 0000 bb00 0000 7304 0000 0000  .r-.......s.....
 00001b10: 0e12 027a 2454 6173 6b55 7469 6c73 2e73  ...z$TaskUtils.s
 00001b20: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 00001b30: 5f76 616c 6964 5f61 744e 2904 7245 0000  _valid_atN).rE..
 00001b40: 0072 4600 0000 da0d 656c 656d 656e 745f  .rF.....element_
 00001b50: 7661 6c75 6572 5200 0000 6303 0000 0000  valuerR...c.....
 00001b60: 0000 0000 0000 0003 0000 0004 0000 0043  ...............C
 00001b70: 0000 0073 1400 0000 7400 7401 7c00 7c01  ...s....t.t.|.|.
@@ -454,17 +454,17 @@
 00001c50: 2e20 4966 2074 6865 2076 616c 7565 2069  . If the value i
 00001c60: 7320 4e6f 6e65 2c20 616c 6c20 6375 7272  s None, all curr
 00001c70: 656e 7420 7661 6c75 6573 2061 7265 2072  ent values are r
 00001c80: 656d 6f76 6564 2e0a 0a20 2020 2020 2020  emoved...       
 00001c90: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001ca0: 2020 2020 2020 5468 6520 7061 7373 6564        The passed
 00001cb0: 2074 6173 6b2e 0a20 2020 2020 2020 2029   task..        )
-00001cc0: 0272 2200 0000 7243 0000 00a9 0372 4500  .r"...rC.....rE.
+00001cc0: 0272 2a00 0000 7243 0000 00a9 0372 4500  .r*...rC.....rE.
 00001cd0: 0000 7246 0000 0072 6300 0000 7249 0000  ..rF...rc...rI..
-00001ce0: 0072 4900 0000 724a 0000 0072 2200 0000  .rI...rJ...r"...
+00001ce0: 0072 4900 0000 724a 0000 0072 2a00 0000  .rI...rJ...r*...
 00001cf0: cd00 0000 7304 0000 0000 0f10 027a 1b54  ....s........z.T
 00001d00: 6173 6b55 7469 6c73 2e73 6574 5f65 6c65  askUtils.set_ele
 00001d10: 6d65 6e74 5f76 616c 7565 2904 7245 0000  ment_value).rE..
 00001d20: 0072 4600 0000 724c 0000 0072 5200 0000  .rF...rL...rR...
 00001d30: 6303 0000 0000 0000 0000 0000 0003 0000  c...............
 00001d40: 0004 0000 0043 0000 0073 1400 0000 7400  .....C...s....t.
 00001d50: 7401 7c00 7c01 8302 7c02 8302 0100 7c00  t.|.|...|.....|.
@@ -484,17 +484,17 @@
 00001e30: 7661 6c75 6520 6973 204e 6f6e 6520 6f72  value is None or
 00001e40: 2065 6d70 7479 2c20 616c 6c20 6375 7272   empty, all curr
 00001e50: 656e 7420 7661 6c75 6573 2061 7265 2072  ent values are r
 00001e60: 656d 6f76 6564 2e0a 0a20 2020 2020 2020  emoved...       
 00001e70: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001e80: 2020 2020 2020 5468 6520 7061 7373 6564        The passed
 00001e90: 2074 6173 6b2e 0a20 2020 2020 2020 2029   task..        )
-00001ea0: 0272 2300 0000 7243 0000 00a9 0372 4500  .r#...rC.....rE.
+00001ea0: 0272 2b00 0000 7243 0000 00a9 0372 4500  .r+...rC.....rE.
 00001eb0: 0000 7246 0000 0072 4c00 0000 7249 0000  ..rF...rL...rI..
-00001ec0: 0072 4900 0000 724a 0000 0072 2300 0000  .rI...rJ...r#...
+00001ec0: 0072 4900 0000 724a 0000 0072 2b00 0000  .rI...rJ...r+...
 00001ed0: e000 0000 7304 0000 0000 0f10 027a 2054  ....s........z T
 00001ee0: 6173 6b55 7469 6c73 2e73 6574 5f65 6c65  askUtils.set_ele
 00001ef0: 6d65 6e74 5f76 616c 7565 5f6c 6973 7463  ment_value_listc
 00001f00: 0300 0000 0000 0000 0000 0000 0300 0000  ................
 00001f10: 0400 0000 4300 0000 7314 0000 0074 0074  ....C...s....t.t
 00001f20: 017c 007c 0183 027c 0283 0201 007c 0053  .|.|...|.....|.S
 00001f30: 0029 0161 2c01 0000 0a20 2020 2020 2020  .).a,....       
@@ -512,17 +512,17 @@
 00001ff0: 7661 6c75 652e 2049 6620 7468 6520 7661  value. If the va
 00002000: 6c75 6520 6973 204e 6f6e 652c 2061 6c6c  lue is None, all
 00002010: 2063 7572 7265 6e74 2076 616c 7565 7320   current values 
 00002020: 6172 6520 7265 6d6f 7665 642e 0a0a 2020  are removed...  
 00002030: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 00002040: 2020 2020 2020 2020 2020 2054 6865 2070             The p
 00002050: 6173 7365 6420 7461 736b 2e0a 2020 2020  assed task..    
-00002060: 2020 2020 2902 720c 0000 0072 4300 0000      ).r....rC...
+00002060: 2020 2020 2902 7214 0000 0072 4300 0000      ).r....rC...
 00002070: 7264 0000 0072 4900 0000 7249 0000 0072  rd...rI...rI...r
-00002080: 4a00 0000 720c 0000 00f3 0000 0073 0400  J...r........s..
+00002080: 4a00 0000 7214 0000 00f3 0000 0073 0400  J...r........s..
 00002090: 0000 000f 1002 7a1b 5461 736b 5574 696c  ......z.TaskUtil
 000020a0: 732e 6164 645f 656c 656d 656e 745f 7661  s.add_element_va
 000020b0: 6c75 6563 0300 0000 0000 0000 0000 0000  luec............
 000020c0: 0300 0000 0400 0000 4300 0000 7314 0000  ........C...s...
 000020d0: 0074 0074 017c 007c 0183 027c 0283 0201  .t.t.|.|...|....
 000020e0: 007c 0053 0029 0161 4601 0000 0a20 2020  .|.S.).aF....   
 000020f0: 2020 2020 2041 6464 2065 6c65 6d65 6e74       Add element
@@ -541,17 +541,17 @@
 000021c0: 206f 7220 656d 7074 792c 2061 6c6c 2063   or empty, all c
 000021d0: 7572 7265 6e74 2076 616c 7565 7320 6172  urrent values ar
 000021e0: 6520 7265 6d6f 7665 642e 0a0a 2020 2020  e removed...    
 000021f0: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00002200: 2020 2020 2020 2020 2054 6865 2070 6173           The pas
 00002210: 7365 6420 6d6f 6465 6c20 7265 6c61 7465  sed model relate
 00002220: 6420 6f62 6a65 6374 2e0a 2020 2020 2020  d object..      
-00002230: 2020 2902 720d 0000 0072 4300 0000 7265    ).r....rC...re
+00002230: 2020 2902 7215 0000 0072 4300 0000 7265    ).r....rC...re
 00002240: 0000 0072 4900 0000 7249 0000 0072 4a00  ...rI...rI...rJ.
-00002250: 0000 720d 0000 0006 0100 0073 0400 0000  ..r........s....
+00002250: 0000 7215 0000 0006 0100 0073 0400 0000  ..r........s....
 00002260: 000f 1002 7a20 5461 736b 5574 696c 732e  ....z TaskUtils.
 00002270: 6164 645f 656c 656d 656e 745f 7661 6c75  add_element_valu
 00002280: 655f 6c69 7374 6302 0000 0000 0000 0000  e_listc.........
 00002290: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 000022a0: 0e00 0000 7400 7401 7c00 7c01 8302 8301  ....t.t.|.|.....
 000022b0: 5300 2901 7ad6 0a20 2020 2020 2020 2047  S.).z..        G
 000022c0: 6574 2061 6e20 656c 656d 656e 7420 6173  et an element as
@@ -562,17 +562,17 @@
 00002310: 2020 2020 656c 656d 656e 745f 6465 6669      element_defi
 00002320: 6e69 7469 6f6e 5f63 6f64 653a 2054 6865  nition_code: The
 00002330: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00002340: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00002350: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002360: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00002370: 656e 7420 7661 6c75 6520 6173 2061 2073  ent value as a s
-00002380: 7472 2e0a 2020 2020 2020 2020 2902 721e  tr..        ).r.
+00002380: 7472 2e0a 2020 2020 2020 2020 2902 7226  tr..        ).r&
 00002390: 0000 0072 4300 0000 7244 0000 0072 4900  ...rC...rD...rI.
-000023a0: 0000 7249 0000 0072 4a00 0000 721e 0000  ..rI...rJ...r...
+000023a0: 0000 7249 0000 0072 4a00 0000 7226 0000  ..rI...rJ...r&..
 000023b0: 0019 0100 0073 0200 0000 000c 7a22 5461  .....s......z"Ta
 000023c0: 736b 5574 696c 732e 6765 745f 656c 656d  skUtils.get_elem
 000023d0: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
 000023e0: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 000023f0: 0004 0000 0043 0000 0073 0e00 0000 7400  .....C...s....t.
 00002400: 7401 7c00 7c01 8302 8301 5300 2901 7add  t.|.|.....S.).z.
 00002410: 0a20 2020 2020 2020 2054 7279 2074 6f20  .        Try to 
@@ -585,16 +585,16 @@
 00002480: 696e 6974 696f 6e5f 636f 6465 3a20 5468  inition_code: Th
 00002490: 6520 656c 656d 656e 7420 6465 6669 6e69  e element defini
 000024a0: 7469 6f6e 2063 6f64 652e 0a0a 2020 2020  tion code...    
 000024b0: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 000024c0: 2020 2020 2020 2020 2054 6865 2065 6c65           The ele
 000024d0: 6d65 6e74 2076 616c 7565 2061 7320 6120  ment value as a 
 000024e0: 7374 722e 0a20 2020 2020 2020 2029 0272  str..        ).r
-000024f0: 1300 0000 7243 0000 0072 4400 0000 7249  ....rC...rD...rI
-00002500: 0000 0072 4900 0000 724a 0000 0072 1300  ...rI...rJ...r..
+000024f0: 1b00 0000 7243 0000 0072 4400 0000 7249  ....rC...rD...rI
+00002500: 0000 0072 4900 0000 724a 0000 0072 1b00  ...rI...rJ...r..
 00002510: 0000 2701 0000 7302 0000 0000 0c7a 2354  ..'...s......z#T
 00002520: 6173 6b55 7469 6c73 2e66 696e 645f 656c  askUtils.find_el
 00002530: 656d 656e 745f 7661 6c75 655f 6173 5f73  ement_value_as_s
 00002540: 7472 6302 0000 0000 0000 0000 0000 0002  trc.............
 00002550: 0000 0004 0000 0043 0000 0073 0e00 0000  .......C...s....
 00002560: 7400 7401 7c00 7c01 8302 8301 5300 2901  t.t.|.|.....S.).
 00002570: 7ae8 0a20 2020 2020 2020 2054 7279 2074  z..        Try t
@@ -607,17 +607,17 @@
 000025e0: 656e 745f 6465 6669 6e69 7469 6f6e 5f63  ent_definition_c
 000025f0: 6f64 653a 2054 6865 2065 6c65 6d65 6e74  ode: The element
 00002600: 2064 6566 696e 6974 696f 6e20 636f 6465   definition code
 00002610: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00002620: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00002630: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00002640: 6573 2061 7320 6120 7374 7220 6c69 7374  es as a str list
-00002650: 2e0a 2020 2020 2020 2020 2902 721f 0000  ..        ).r...
+00002650: 2e0a 2020 2020 2020 2020 2902 7227 0000  ..        ).r'..
 00002660: 0072 4300 0000 7244 0000 0072 4900 0000  .rC...rD...rI...
-00002670: 7249 0000 0072 4a00 0000 721f 0000 0035  rI...rJ...r....5
+00002670: 7249 0000 0072 4a00 0000 7227 0000 0035  rI...rJ...r'...5
 00002680: 0100 0073 0200 0000 000c 7a27 5461 736b  ...s......z'Task
 00002690: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 000026a0: 745f 7661 6c75 655f 6173 5f73 7472 5f6c  t_value_as_str_l
 000026b0: 6973 7463 0200 0000 0000 0000 0000 0000  istc............
 000026c0: 0200 0000 0400 0000 4300 0000 730e 0000  ........C...s...
 000026d0: 0074 0074 017c 007c 0183 0283 0153 0029  .t.t.|.|.....S.)
 000026e0: 017a da0a 2020 2020 2020 2020 4765 7420  .z..        Get 
@@ -630,16 +630,16 @@
 00002750: 6974 696f 6e5f 636f 6465 3a20 5468 6520  ition_code: The 
 00002760: 656c 656d 656e 7420 6465 6669 6e69 7469  element definiti
 00002770: 6f6e 2063 6f64 652e 0a0a 2020 2020 2020  on code...      
 00002780: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00002790: 2020 2020 2020 2054 6865 2065 6c65 6d65         The eleme
 000027a0: 6e74 2076 616c 7565 2061 7320 6120 666c  nt value as a fl
 000027b0: 6f61 742e 0a20 2020 2020 2020 2029 0272  oat..        ).r
-000027c0: 1a00 0000 7243 0000 0072 4400 0000 7249  ....rC...rD...rI
-000027d0: 0000 0072 4900 0000 724a 0000 0072 1a00  ...rI...rJ...r..
+000027c0: 2200 0000 7243 0000 0072 4400 0000 7249  "...rC...rD...rI
+000027d0: 0000 0072 4900 0000 724a 0000 0072 2200  ...rI...rJ...r".
 000027e0: 0000 4301 0000 7302 0000 0000 0c7a 2454  ..C...s......z$T
 000027f0: 6173 6b55 7469 6c73 2e67 6574 5f65 6c65  askUtils.get_ele
 00002800: 6d65 6e74 5f76 616c 7565 5f61 735f 666c  ment_value_as_fl
 00002810: 6f61 7463 0200 0000 0000 0000 0000 0000  oatc............
 00002820: 0200 0000 0400 0000 4300 0000 730e 0000  ........C...s...
 00002830: 0074 0074 017c 007c 0183 0283 0153 0029  .t.t.|.|.....S.)
 00002840: 017a e10a 2020 2020 2020 2020 5472 7920  .z..        Try 
@@ -652,17 +652,17 @@
 000028b0: 745f 6465 6669 6e69 7469 6f6e 5f63 6f64  t_definition_cod
 000028c0: 653a 2054 6865 2065 6c65 6d65 6e74 2064  e: The element d
 000028d0: 6566 696e 6974 696f 6e20 636f 6465 2e0a  efinition code..
 000028e0: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 000028f0: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00002900: 6520 656c 656d 656e 7420 7661 6c75 6520  e element value 
 00002910: 6173 2061 2066 6c6f 6174 2e0a 2020 2020  as a float..    
-00002920: 2020 2020 2902 7211 0000 0072 4300 0000      ).r....rC...
+00002920: 2020 2020 2902 7219 0000 0072 4300 0000      ).r....rC...
 00002930: 7244 0000 0072 4900 0000 7249 0000 0072  rD...rI...rI...r
-00002940: 4a00 0000 7211 0000 0051 0100 0073 0200  J...r....Q...s..
+00002940: 4a00 0000 7219 0000 0051 0100 0073 0200  J...r....Q...s..
 00002950: 0000 000c 7a25 5461 736b 5574 696c 732e  ....z%TaskUtils.
 00002960: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
 00002970: 7565 5f61 735f 666c 6f61 7463 0200 0000  ue_as_floatc....
 00002980: 0000 0000 0000 0000 0200 0000 0400 0000  ................
 00002990: 4300 0000 730e 0000 0074 0074 017c 007c  C...s....t.t.|.|
 000029a0: 0183 0283 0153 0029 017a e10a 2020 2020  .....S.).z..    
 000029b0: 2020 2020 4765 7420 616c 6c20 656c 656d      Get all elem
@@ -674,17 +674,17 @@
 00002a10: 2020 656c 656d 656e 745f 6465 6669 6e69    element_defini
 00002a20: 7469 6f6e 5f63 6f64 653a 2054 6865 2065  tion_code: The e
 00002a30: 6c65 6d65 6e74 2064 6566 696e 6974 696f  lement definitio
 00002a40: 6e20 636f 6465 2e0a 0a20 2020 2020 2020  n code...       
 00002a50: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00002a60: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00002a70: 7420 7661 6c75 6520 6173 2061 2066 6c6f  t value as a flo
-00002a80: 6174 2e0a 2020 2020 2020 2020 2902 721b  at..        ).r.
+00002a80: 6174 2e0a 2020 2020 2020 2020 2902 7223  at..        ).r#
 00002a90: 0000 0072 4300 0000 7244 0000 0072 4900  ...rC...rD...rI.
-00002aa0: 0000 7249 0000 0072 4a00 0000 721b 0000  ..rI...rJ...r...
+00002aa0: 0000 7249 0000 0072 4a00 0000 7223 0000  ..rI...rJ...r#..
 00002ab0: 005f 0100 0073 0200 0000 000c 7a29 5461  ._...s......z)Ta
 00002ac0: 736b 5574 696c 732e 6765 745f 656c 656d  skUtils.get_elem
 00002ad0: 656e 745f 7661 6c75 655f 6173 5f66 6c6f  ent_value_as_flo
 00002ae0: 6174 5f6c 6973 7463 0200 0000 0000 0000  at_listc........
 00002af0: 0000 0000 0200 0000 0400 0000 4300 0000  ............C...
 00002b00: 730e 0000 0074 0074 017c 007c 0183 0283  s....t.t.|.|....
 00002b10: 0153 0029 017a d80a 2020 2020 2020 2020  .S.).z..        
@@ -697,17 +697,17 @@
 00002b80: 6669 6e69 7469 6f6e 5f63 6f64 653a 2054  finition_code: T
 00002b90: 6865 2065 6c65 6d65 6e74 2064 6566 696e  he element defin
 00002ba0: 6974 696f 6e20 636f 6465 2e0a 0a20 2020  ition code...   
 00002bb0: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00002bc0: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00002bd0: 656d 656e 7420 7661 6c75 6520 6173 2061  ement value as a
 00002be0: 2064 6174 652e 0a20 2020 2020 2020 2029   date..        )
-00002bf0: 0272 1400 0000 7243 0000 0072 4400 0000  .r....rC...rD...
+00002bf0: 0272 1c00 0000 7243 0000 0072 4400 0000  .r....rC...rD...
 00002c00: 7249 0000 0072 4900 0000 724a 0000 0072  rI...rI...rJ...r
-00002c10: 1400 0000 6d01 0000 7302 0000 0000 0c7a  ....m...s......z
+00002c10: 1c00 0000 6d01 0000 7302 0000 0000 0c7a  ....m...s......z
 00002c20: 2354 6173 6b55 7469 6c73 2e67 6574 5f65  #TaskUtils.get_e
 00002c30: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00002c40: 6461 7465 6302 0000 0000 0000 0000 0000  datec...........
 00002c50: 0002 0000 0004 0000 0043 0000 0073 0e00  .........C...s..
 00002c60: 0000 7400 7401 7c00 7c01 8302 8301 5300  ..t.t.|.|.....S.
 00002c70: 2901 7ae0 0a20 2020 2020 2020 2054 7279  ).z..        Try
 00002c80: 2074 6f20 6765 7420 2061 6e20 656c 656d   to get  an elem
@@ -719,17 +719,17 @@
 00002ce0: 6e74 5f64 6566 696e 6974 696f 6e5f 636f  nt_definition_co
 00002cf0: 6465 3a20 5468 6520 656c 656d 656e 7420  de: The element 
 00002d00: 6465 6669 6e69 7469 6f6e 2063 6f64 652e  definition code.
 00002d10: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 00002d20: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 00002d30: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 00002d40: 2061 7320 6120 6461 7465 2e0a 2020 2020   as a date..    
-00002d50: 2020 2020 2902 720e 0000 0072 4300 0000      ).r....rC...
+00002d50: 2020 2020 2902 7216 0000 0072 4300 0000      ).r....rC...
 00002d60: 7244 0000 0072 4900 0000 7249 0000 0072  rD...rI...rI...r
-00002d70: 4a00 0000 720e 0000 007b 0100 0073 0200  J...r....{...s..
+00002d70: 4a00 0000 7216 0000 007b 0100 0073 0200  J...r....{...s..
 00002d80: 0000 000c 7a24 5461 736b 5574 696c 732e  ....z$TaskUtils.
 00002d90: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
 00002da0: 7565 5f61 735f 6461 7465 6302 0000 0000  ue_as_datec.....
 00002db0: 0000 0000 0000 0002 0000 0004 0000 0043  ...............C
 00002dc0: 0000 0073 0e00 0000 7400 7401 7c00 7c01  ...s....t.t.|.|.
 00002dd0: 8302 8301 5300 2901 7ae1 0a20 2020 2020  ....S.).z..     
 00002de0: 2020 2047 6574 2061 6c6c 2065 6c65 6d65     Get all eleme
@@ -741,17 +741,17 @@
 00002e40: 656d 656e 745f 6465 6669 6e69 7469 6f6e  ement_definition
 00002e50: 5f63 6f64 653a 2054 6865 2065 6c65 6d65  _code: The eleme
 00002e60: 6e74 2064 6566 696e 6974 696f 6e20 636f  nt definition co
 00002e70: 6465 2e0a 0a20 2020 2020 2020 2052 6574  de...        Ret
 00002e80: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00002e90: 2020 5468 6520 656c 656d 656e 7420 7661    The element va
 00002ea0: 6c75 6573 2061 7320 6461 7465 206c 6973  lues as date lis
-00002eb0: 742e 0a20 2020 2020 2020 2029 0272 1500  t..        ).r..
+00002eb0: 742e 0a20 2020 2020 2020 2029 0272 1d00  t..        ).r..
 00002ec0: 0000 7243 0000 0072 4400 0000 7249 0000  ..rC...rD...rI..
-00002ed0: 0072 4900 0000 724a 0000 0072 1500 0000  .rI...rJ...r....
+00002ed0: 0072 4900 0000 724a 0000 0072 1d00 0000  .rI...rJ...r....
 00002ee0: 8901 0000 7302 0000 0000 0c7a 2854 6173  ....s......z(Tas
 00002ef0: 6b55 7469 6c73 2e67 6574 5f65 6c65 6d65  kUtils.get_eleme
 00002f00: 6e74 5f76 616c 7565 5f61 735f 6461 7465  nt_value_as_date
 00002f10: 5f6c 6973 7463 0200 0000 0000 0000 0000  _listc..........
 00002f20: 0000 0200 0000 0400 0000 4300 0000 730e  ..........C...s.
 00002f30: 0000 0074 0074 017c 007c 0183 0283 0153  ...t.t.|.|.....S
 00002f40: 0029 017a d80a 2020 2020 2020 2020 4765  .).z..        Ge
@@ -764,16 +764,16 @@
 00002fb0: 6e69 7469 6f6e 5f63 6f64 653a 2054 6865  nition_code: The
 00002fc0: 2065 6c65 6d65 6e74 2064 6566 696e 6974   element definit
 00002fd0: 696f 6e20 636f 6465 2e0a 0a20 2020 2020  ion code...     
 00002fe0: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002ff0: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00003000: 656e 7420 7661 6c75 6520 6173 2061 2064  ent value as a d
 00003010: 6963 742e 0a20 2020 2020 2020 2029 0272  ict..        ).r
-00003020: 1600 0000 7243 0000 0072 4400 0000 7249  ....rC...rD...rI
-00003030: 0000 0072 4900 0000 724a 0000 0072 1600  ...rI...rJ...r..
+00003020: 1e00 0000 7243 0000 0072 4400 0000 7249  ....rC...rD...rI
+00003030: 0000 0072 4900 0000 724a 0000 0072 1e00  ...rI...rJ...r..
 00003040: 0000 9701 0000 7302 0000 0000 0c7a 2354  ......s......z#T
 00003050: 6173 6b55 7469 6c73 2e67 6574 5f65 6c65  askUtils.get_ele
 00003060: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
 00003070: 6374 6302 0000 0000 0000 0000 0000 0002  ctc.............
 00003080: 0000 0004 0000 0043 0000 0073 0e00 0000  .......C...s....
 00003090: 7400 7401 7c00 7c01 8302 8301 5300 2901  t.t.|.|.....S.).
 000030a0: 7adf 0a20 2020 2020 2020 2054 7279 2074  z..        Try t
@@ -786,17 +786,17 @@
 00003110: 6465 6669 6e69 7469 6f6e 5f63 6f64 653a  definition_code:
 00003120: 2054 6865 2065 6c65 6d65 6e74 2064 6566   The element def
 00003130: 696e 6974 696f 6e20 636f 6465 2e0a 0a20  inition code... 
 00003140: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 00003150: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 00003160: 656c 656d 656e 7420 7661 6c75 6520 6173  element value as
 00003170: 2061 2064 6963 742e 0a20 2020 2020 2020   a dict..       
-00003180: 2029 0272 0f00 0000 7243 0000 0072 4400   ).r....rC...rD.
+00003180: 2029 0272 1700 0000 7243 0000 0072 4400   ).r....rC...rD.
 00003190: 0000 7249 0000 0072 4900 0000 724a 0000  ..rI...rI...rJ..
-000031a0: 0072 0f00 0000 a501 0000 7302 0000 0000  .r........s.....
+000031a0: 0072 1700 0000 a501 0000 7302 0000 0000  .r........s.....
 000031b0: 0c7a 2454 6173 6b55 7469 6c73 2e66 696e  .z$TaskUtils.fin
 000031c0: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 000031d0: 6173 5f64 6963 7463 0200 0000 0000 0000  as_dictc........
 000031e0: 0000 0000 0200 0000 0400 0000 4300 0000  ............C...
 000031f0: 730e 0000 0074 0074 017c 007c 0183 0283  s....t.t.|.|....
 00003200: 0153 0029 017a e10a 2020 2020 2020 2020  .S.).z..        
 00003210: 4765 7420 616c 6c20 656c 656d 656e 7473  Get all elements
@@ -808,17 +808,17 @@
 00003270: 6e74 5f64 6566 696e 6974 696f 6e5f 636f  nt_definition_co
 00003280: 6465 3a20 5468 6520 656c 656d 656e 7420  de: The element 
 00003290: 6465 6669 6e69 7469 6f6e 2063 6f64 652e  definition code.
 000032a0: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 000032b0: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 000032c0: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 000032d0: 7320 6173 2064 6963 7420 6c69 7374 2e0a  s as dict list..
-000032e0: 2020 2020 2020 2020 2902 7217 0000 0072          ).r....r
+000032e0: 2020 2020 2020 2020 2902 721f 0000 0072          ).r....r
 000032f0: 4300 0000 7244 0000 0072 4900 0000 7249  C...rD...rI...rI
-00003300: 0000 0072 4a00 0000 7217 0000 00b3 0100  ...rJ...r.......
+00003300: 0000 0072 4a00 0000 721f 0000 00b3 0100  ...rJ...r.......
 00003310: 0073 0200 0000 000c 7a28 5461 736b 5574  .s......z(TaskUt
 00003320: 696c 732e 6765 745f 656c 656d 656e 745f  ils.get_element_
 00003330: 7661 6c75 655f 6173 5f64 6963 745f 6c69  value_as_dict_li
 00003340: 7374 6302 0000 0000 0000 0000 0000 0002  stc.............
 00003350: 0000 0004 0000 0043 0000 0073 0e00 0000  .......C...s....
 00003360: 7400 7401 7c00 7c01 8302 8301 5300 2901  t.t.|.|.....S.).
 00003370: 6108 0100 000a 2020 2020 2020 2020 4765  a.....        Ge
@@ -834,16 +834,16 @@
 00003410: 2064 6566 696e 6974 696f 6e20 636f 6465   definition code
 00003420: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00003430: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00003440: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00003450: 6520 6173 2061 2054 6173 6b45 6c65 6d65  e as a TaskEleme
 00003460: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
 00003470: 7465 6d2e 0a20 2020 2020 2020 2029 0272  tem..        ).r
-00003480: 1800 0000 7243 0000 0072 4400 0000 7249  ....rC...rD...rI
-00003490: 0000 0072 4900 0000 724a 0000 0072 1800  ...rI...rJ...r..
+00003480: 2000 0000 7243 0000 0072 4400 0000 7249   ...rC...rD...rI
+00003490: 0000 0072 4900 0000 724a 0000 0072 2000  ...rI...rJ...r .
 000034a0: 0000 c101 0000 7302 0000 0000 0c7a 2754  ......s......z'T
 000034b0: 6173 6b55 7469 6c73 2e67 6574 5f65 6c65  askUtils.get_ele
 000034c0: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
 000034d0: 6375 6d65 6e74 6302 0000 0000 0000 0000  cumentc.........
 000034e0: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
 000034f0: 0e00 0000 7400 7401 7c00 7c01 8302 8301  ....t.t.|.|.....
 00003500: 5300 2901 6110 0100 000a 2020 2020 2020  S.).a.....      
@@ -859,17 +859,17 @@
 000035a0: 2054 6865 2065 6c65 6d65 6e74 2064 6566   The element def
 000035b0: 696e 6974 696f 6e20 636f 6465 2e0a 0a20  inition code... 
 000035c0: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 000035d0: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 000035e0: 656c 656d 656e 7420 7661 6c75 6520 6173  element value as
 000035f0: 2061 2054 6173 6b45 6c65 6d65 6e74 5661   a TaskElementVa
 00003600: 6c75 6544 6f63 756d 656e 7449 7465 6d2e  lueDocumentItem.
-00003610: 0a20 2020 2020 2020 2029 0272 1000 0000  .        ).r....
+00003610: 0a20 2020 2020 2020 2029 0272 1800 0000  .        ).r....
 00003620: 7243 0000 0072 4400 0000 7249 0000 0072  rC...rD...rI...r
-00003630: 4900 0000 724a 0000 0072 1000 0000 cf01  I...rJ...r......
+00003630: 4900 0000 724a 0000 0072 1800 0000 cf01  I...rJ...r......
 00003640: 0000 7302 0000 0000 0e7a 2854 6173 6b55  ..s......z(TaskU
 00003650: 7469 6c73 2e66 696e 645f 656c 656d 656e  tils.find_elemen
 00003660: 745f 7661 6c75 655f 6173 5f64 6f63 756d  t_value_as_docum
 00003670: 656e 7463 0200 0000 0000 0000 0000 0000  entc............
 00003680: 0200 0000 0400 0000 4300 0000 730e 0000  ........C...s...
 00003690: 0074 0074 017c 007c 0183 0283 0153 0029  .t.t.|.|.....S.)
 000036a0: 0161 1101 0000 0a20 2020 2020 2020 2047  .a.....        G
@@ -885,17 +885,17 @@
 00003740: 6c65 6d65 6e74 2064 6566 696e 6974 696f  lement definitio
 00003750: 6e20 636f 6465 2e0a 0a20 2020 2020 2020  n code...       
 00003760: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00003770: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00003780: 7420 7661 6c75 6573 2061 7320 5461 736b  t values as Task
 00003790: 456c 656d 656e 7456 616c 7565 446f 6375  ElementValueDocu
 000037a0: 6d65 6e74 4974 656d 206c 6973 742e 0a20  mentItem list.. 
-000037b0: 2020 2020 2020 2029 0272 1900 0000 7243         ).r....rC
+000037b0: 2020 2020 2020 2029 0272 2100 0000 7243         ).r!...rC
 000037c0: 0000 0072 4400 0000 7249 0000 0072 4900  ...rD...rI...rI.
-000037d0: 0000 724a 0000 0072 1900 0000 df01 0000  ..rJ...r........
+000037d0: 0000 724a 0000 0072 2100 0000 df01 0000  ..rJ...r!.......
 000037e0: 7302 0000 0000 0e7a 2c54 6173 6b55 7469  s......z,TaskUti
 000037f0: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00003800: 616c 7565 5f61 735f 646f 6375 6d65 6e74  alue_as_document
 00003810: 5f6c 6973 7463 0200 0000 0000 0000 0000  _listc..........
 00003820: 0000 0200 0000 0400 0000 4300 0000 730e  ..........C...s.
 00003830: 0000 0074 0074 017c 007c 0183 0283 0153  ...t.t.|.|.....S
 00003840: 0029 0161 0a01 0000 0a20 2020 2020 2020  .).a.....       
@@ -911,17 +911,17 @@
 000038e0: 6d65 6e74 2064 6566 696e 6974 696f 6e20  ment definition 
 000038f0: 636f 6465 2e0a 0a20 2020 2020 2020 2052  code...        R
 00003900: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00003910: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00003920: 7661 6c75 6520 6173 2061 2054 6173 6b45  value as a TaskE
 00003930: 6c65 6d65 6e74 5661 6c75 6550 7269 6e63  lementValuePrinc
 00003940: 6970 616c 4974 656d 2e0a 2020 2020 2020  ipalItem..      
-00003950: 2020 2902 721c 0000 0072 4300 0000 7244    ).r....rC...rD
+00003950: 2020 2902 7224 0000 0072 4300 0000 7244    ).r$...rC...rD
 00003960: 0000 0072 4900 0000 7249 0000 0072 4a00  ...rI...rI...rJ.
-00003970: 0000 721c 0000 00ef 0100 0073 0200 0000  ..r........s....
+00003970: 0000 7224 0000 00ef 0100 0073 0200 0000  ..r$.......s....
 00003980: 000c 7a28 5461 736b 5574 696c 732e 6765  ..z(TaskUtils.ge
 00003990: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
 000039a0: 6173 5f70 7269 6e63 6970 616c 6302 0000  as_principalc...
 000039b0: 0000 0000 0000 0000 0002 0000 0004 0000  ................
 000039c0: 0043 0000 0073 0e00 0000 7400 7401 7c00  .C...s....t.t.|.
 000039d0: 7c01 8302 8301 5300 2901 6112 0100 000a  |.....S.).a.....
 000039e0: 2020 2020 2020 2020 5472 7920 746f 2067          Try to g
@@ -937,17 +937,17 @@
 00003a80: 656e 7420 6465 6669 6e69 7469 6f6e 2063  ent definition c
 00003a90: 6f64 652e 0a0a 2020 2020 2020 2020 5265  ode...        Re
 00003aa0: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00003ab0: 2020 2054 6865 2065 6c65 6d65 6e74 2076     The element v
 00003ac0: 616c 7565 2061 7320 6120 5461 736b 456c  alue as a TaskEl
 00003ad0: 656d 656e 7456 616c 7565 5072 696e 6369  ementValuePrinci
 00003ae0: 7061 6c49 7465 6d2e 0a20 2020 2020 2020  palItem..       
-00003af0: 2029 0272 1200 0000 7243 0000 0072 4400   ).r....rC...rD.
+00003af0: 2029 0272 1a00 0000 7243 0000 0072 4400   ).r....rC...rD.
 00003b00: 0000 7249 0000 0072 4900 0000 724a 0000  ..rI...rI...rJ..
-00003b10: 0072 1200 0000 fd01 0000 7302 0000 0000  .r........s.....
+00003b10: 0072 1a00 0000 fd01 0000 7302 0000 0000  .r........s.....
 00003b20: 0e7a 2954 6173 6b55 7469 6c73 2e66 696e  .z)TaskUtils.fin
 00003b30: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 00003b40: 6173 5f70 7269 6e63 6970 616c 6302 0000  as_principalc...
 00003b50: 0000 0000 0000 0000 0002 0000 0004 0000  ................
 00003b60: 0043 0000 0073 0e00 0000 7400 7401 7c00  .C...s....t.t.|.
 00003b70: 7c01 8302 8301 5300 2901 6113 0100 000a  |.....S.).a.....
 00003b80: 2020 2020 2020 2020 4765 7420 616c 6c20          Get all 
@@ -963,17 +963,17 @@
 00003c20: 2064 6566 696e 6974 696f 6e20 636f 6465   definition code
 00003c30: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00003c40: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00003c50: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00003c60: 6573 2061 7320 5461 736b 456c 656d 656e  es as TaskElemen
 00003c70: 7456 616c 7565 5072 696e 6369 7061 6c49  tValuePrincipalI
 00003c80: 7465 6d20 6c69 7374 2e0a 2020 2020 2020  tem list..      
-00003c90: 2020 2902 721d 0000 0072 4300 0000 7244    ).r....rC...rD
+00003c90: 2020 2902 7225 0000 0072 4300 0000 7244    ).r%...rC...rD
 00003ca0: 0000 0072 4900 0000 7249 0000 0072 4a00  ...rI...rI...rJ.
-00003cb0: 0000 721d 0000 000d 0200 0073 0200 0000  ..r........s....
+00003cb0: 0000 7225 0000 000d 0200 0073 0200 0000  ..r%.......s....
 00003cc0: 000e 7a2d 5461 736b 5574 696c 732e 6765  ..z-TaskUtils.ge
 00003cd0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
 00003ce0: 6173 5f70 7269 6e63 6970 616c 5f6c 6973  as_principal_lis
 00003cf0: 7429 0372 4500 0000 da0d 7072 6f70 6572  t).rE.....proper
 00003d00: 7479 5f70 6174 6872 5200 0000 6302 0000  ty_pathrR...c...
 00003d10: 0000 0000 0000 0000 0002 0000 0003 0000  ................
 00003d20: 0043 0000 0073 0e00 0000 7400 7401 7c00  .C...s....t.t.|.
@@ -997,17 +997,17 @@
 00003e40: 2065 7869 7374 732e 0a0a 2020 2020 2020   exists...      
 00003e50: 2020 5261 6973 6573 3a0a 2020 2020 2020    Raises:.      
 00003e60: 2020 2020 2020 5661 6c75 6545 7272 6f72        ValueError
 00003e70: 3a20 4966 2070 726f 7065 7274 7920 7661  : If property va
 00003e80: 6c75 6520 646f 6573 6e27 7420 6578 6973  lue doesn't exis
 00003e90: 7420 6f72 2068 6173 2069 6e63 6f72 7265  t or has incorre
 00003ea0: 6374 2066 6f72 6d61 740a 2020 2020 2020  ct format.      
-00003eb0: 2020 2902 7239 0000 0072 5a00 0000 a902    ).r9...rZ.....
+00003eb0: 2020 2902 7241 0000 0072 5a00 0000 a902    ).rA...rZ.....
 00003ec0: 7245 0000 0072 6600 0000 7249 0000 0072  rE...rf...rI...r
-00003ed0: 4900 0000 724a 0000 0072 3900 0000 1d02  I...rJ...r9.....
+00003ed0: 4900 0000 724a 0000 0072 4100 0000 1d02  I...rJ...rA.....
 00003ee0: 0000 7302 0000 0000 0f7a 2854 6173 6b55  ..s......z(TaskU
 00003ef0: 7469 6c73 2e67 6574 5f6a 736f 6e5f 666f  tils.get_json_fo
 00003f00: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
 00003f10: 7374 7263 0200 0000 0000 0000 0000 0000  strc............
 00003f20: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
 00003f30: 0074 0074 017c 0083 017c 0183 0253 0029  .t.t.|...|...S.)
 00003f40: 0161 6a01 0000 0a20 2020 2020 2020 2054  .aj....        T
@@ -1029,17 +1029,17 @@
 00004040: 6f70 6572 7479 2076 616c 7565 2069 6620  operty value if 
 00004050: 6578 6973 7473 2e0a 0a20 2020 2020 2020  exists...       
 00004060: 2052 6169 7365 733a 0a20 2020 2020 2020   Raises:.       
 00004070: 2020 2020 2056 616c 7565 4572 726f 723a       ValueError:
 00004080: 2049 6620 7072 6f70 6572 7479 2076 616c   If property val
 00004090: 7565 2068 6173 2069 6e63 6f72 7265 6374  ue has incorrect
 000040a0: 2066 6f72 6d61 740a 2020 2020 2020 2020   format.        
-000040b0: 2902 7230 0000 0072 5a00 0000 7267 0000  ).r0...rZ...rg..
+000040b0: 2902 7238 0000 0072 5a00 0000 7267 0000  ).r8...rZ...rg..
 000040c0: 0072 4900 0000 7249 0000 0072 4a00 0000  .rI...rI...rJ...
-000040d0: 7230 0000 002e 0200 0073 0200 0000 000f  r0.......s......
+000040d0: 7238 0000 002e 0200 0073 0200 0000 000f  r8.......s......
 000040e0: 7a29 5461 736b 5574 696c 732e 6669 6e64  z)TaskUtils.find
 000040f0: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
 00004100: 6572 7479 5f61 735f 7374 7263 0200 0000  erty_as_strc....
 00004110: 0000 0000 0000 0000 0200 0000 0300 0000  ................
 00004120: 4300 0000 730e 0000 0074 0074 017c 0083  C...s....t.t.|..
 00004130: 017c 0183 0253 0029 0161 7301 0000 0a20  .|...S.).as.... 
 00004140: 2020 2020 2020 2047 6574 2061 206a 736f         Get a jso
@@ -1061,17 +1061,17 @@
 00004240: 6578 6973 7473 2e0a 0a20 2020 2020 2020  exists...       
 00004250: 2052 6169 7365 733a 0a20 2020 2020 2020   Raises:.       
 00004260: 2020 2020 2056 616c 7565 4572 726f 723a       ValueError:
 00004270: 2049 6620 7072 6f70 6572 7479 2076 616c   If property val
 00004280: 7565 2064 6f65 736e 2774 2065 7869 7374  ue doesn't exist
 00004290: 206f 7220 6861 7320 696e 636f 7272 6563   or has incorrec
 000042a0: 7420 666f 726d 6174 0a20 2020 2020 2020  t format.       
-000042b0: 2029 0272 3500 0000 725a 0000 0072 6700   ).r5...rZ...rg.
+000042b0: 2029 0272 3d00 0000 725a 0000 0072 6700   ).r=...rZ...rg.
 000042c0: 0000 7249 0000 0072 4900 0000 724a 0000  ..rI...rI...rJ..
-000042d0: 0072 3500 0000 3f02 0000 7302 0000 0000  .r5...?...s.....
+000042d0: 0072 3d00 0000 3f02 0000 7302 0000 0000  .r=...?...s.....
 000042e0: 0f7a 2854 6173 6b55 7469 6c73 2e67 6574  .z(TaskUtils.get
 000042f0: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
 00004300: 6572 7479 5f61 735f 696e 7463 0200 0000  erty_as_intc....
 00004310: 0000 0000 0000 0000 0200 0000 0300 0000  ................
 00004320: 4300 0000 730e 0000 0074 0074 017c 0083  C...s....t.t.|..
 00004330: 017c 0183 0253 0029 0161 6a01 0000 0a20  .|...S.).aj.... 
 00004340: 2020 2020 2020 2054 7279 2074 6f20 6669         Try to fi
@@ -1092,17 +1092,17 @@
 00004430: 2020 5468 6520 7072 6f70 6572 7479 2076    The property v
 00004440: 616c 7565 2069 6620 6578 6973 7473 2e0a  alue if exists..
 00004450: 0a20 2020 2020 2020 2052 6169 7365 733a  .        Raises:
 00004460: 0a20 2020 2020 2020 2020 2020 2056 616c  .            Val
 00004470: 7565 4572 726f 723a 2049 6620 7072 6f70  ueError: If prop
 00004480: 6572 7479 2076 616c 7565 2068 6173 2069  erty value has i
 00004490: 6e63 6f72 7265 6374 2066 6f72 6d61 740a  ncorrect format.
-000044a0: 2020 2020 2020 2020 2902 722c 0000 0072          ).r,...r
+000044a0: 2020 2020 2020 2020 2902 7234 0000 0072          ).r4...r
 000044b0: 5a00 0000 7267 0000 0072 4900 0000 7249  Z...rg...rI...rI
-000044c0: 0000 0072 4a00 0000 722c 0000 0050 0200  ...rJ...r,...P..
+000044c0: 0000 0072 4a00 0000 7234 0000 0050 0200  ...rJ...r4...P..
 000044d0: 0073 0200 0000 000f 7a29 5461 736b 5574  .s......z)TaskUt
 000044e0: 696c 732e 6669 6e64 5f6a 736f 6e5f 666f  ils.find_json_fo
 000044f0: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
 00004500: 696e 7463 0200 0000 0000 0000 0000 0000  intc............
 00004510: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
 00004520: 0074 0074 017c 0083 017c 0183 0253 0029  .t.t.|...|...S.)
 00004530: 0161 7501 0000 0a20 2020 2020 2020 2047  .au....        G
@@ -1124,17 +1124,17 @@
 00004630: 2076 616c 7565 2069 6620 6578 6973 7473   value if exists
 00004640: 2e0a 0a20 2020 2020 2020 2052 6169 7365  ...        Raise
 00004650: 733a 0a20 2020 2020 2020 2020 2020 2056  s:.            V
 00004660: 616c 7565 4572 726f 723a 2049 6620 7072  alueError: If pr
 00004670: 6f70 6572 7479 2076 616c 7565 2064 6f65  operty value doe
 00004680: 736e 2774 2065 7869 7374 206f 7220 6861  sn't exist or ha
 00004690: 7320 696e 636f 7272 6563 7420 666f 726d  s incorrect form
-000046a0: 6174 0a20 2020 2020 2020 2029 0272 3400  at.        ).r4.
+000046a0: 6174 0a20 2020 2020 2020 2029 0272 3c00  at.        ).r<.
 000046b0: 0000 725a 0000 0072 6700 0000 7249 0000  ..rZ...rg...rI..
-000046c0: 0072 4900 0000 724a 0000 0072 3400 0000  .rI...rJ...r4...
+000046c0: 0072 4900 0000 724a 0000 0072 3c00 0000  .rI...rJ...r<...
 000046d0: 6102 0000 7302 0000 0000 0f7a 2a54 6173  a...s......z*Tas
 000046e0: 6b55 7469 6c73 2e67 6574 5f6a 736f 6e5f  kUtils.get_json_
 000046f0: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
 00004700: 735f 666c 6f61 7463 0200 0000 0000 0000  s_floatc........
 00004710: 0000 0000 0200 0000 0300 0000 4300 0000  ............C...
 00004720: 730e 0000 0074 0074 017c 0083 017c 0183  s....t.t.|...|..
 00004730: 0253 0029 0161 6c01 0000 0a20 2020 2020  .S.).al....     
@@ -1156,17 +1156,17 @@
 00004830: 5468 6520 7072 6f70 6572 7479 2076 616c  The property val
 00004840: 7565 2069 6620 6578 6973 7473 2e0a 0a20  ue if exists... 
 00004850: 2020 2020 2020 2052 6169 7365 733a 0a20         Raises:. 
 00004860: 2020 2020 2020 2020 2020 2056 616c 7565             Value
 00004870: 4572 726f 723a 2049 6620 7072 6f70 6572  Error: If proper
 00004880: 7479 2076 616c 7565 2068 6173 2069 6e63  ty value has inc
 00004890: 6f72 7265 6374 2066 6f72 6d61 740a 2020  orrect format.  
-000048a0: 2020 2020 2020 2902 722b 0000 0072 5a00        ).r+...rZ.
+000048a0: 2020 2020 2020 2902 7233 0000 0072 5a00        ).r3...rZ.
 000048b0: 0000 7267 0000 0072 4900 0000 7249 0000  ..rg...rI...rI..
-000048c0: 0072 4a00 0000 722b 0000 0072 0200 0073  .rJ...r+...r...s
+000048c0: 0072 4a00 0000 7233 0000 0072 0200 0073  .rJ...r3...r...s
 000048d0: 0200 0000 000f 7a2b 5461 736b 5574 696c  ......z+TaskUtil
 000048e0: 732e 6669 6e64 5f6a 736f 6e5f 666f 726d  s.find_json_form
 000048f0: 735f 7072 6f70 6572 7479 5f61 735f 666c  s_property_as_fl
 00004900: 6f61 7463 0200 0000 0000 0000 0000 0000  oatc............
 00004910: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
 00004920: 0074 0074 017c 0083 017c 0183 0253 0029  .t.t.|...|...S.)
 00004930: 0161 7401 0000 0a20 2020 2020 2020 2047  .at....        G
@@ -1188,17 +1188,17 @@
 00004a30: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 00004a40: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 00004a50: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 00004a60: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 00004a70: 7065 7274 7920 7661 6c75 6520 646f 6573  perty value does
 00004a80: 6e27 7420 6578 6973 7420 6f72 2068 6173  n't exist or has
 00004a90: 2069 6e63 6f72 7265 6374 2066 6f72 6d61   incorrect forma
-00004aa0: 740a 2020 2020 2020 2020 2902 7231 0000  t.        ).r1..
+00004aa0: 740a 2020 2020 2020 2020 2902 7239 0000  t.        ).r9..
 00004ab0: 0072 5a00 0000 7267 0000 0072 4900 0000  .rZ...rg...rI...
-00004ac0: 7249 0000 0072 4a00 0000 7231 0000 0083  rI...rJ...r1....
+00004ac0: 7249 0000 0072 4a00 0000 7239 0000 0083  rI...rJ...r9....
 00004ad0: 0200 0073 0200 0000 000f 7a29 5461 736b  ...s......z)Task
 00004ae0: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00004af0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00004b00: 5f64 6174 6563 0200 0000 0000 0000 0000  _datec..........
 00004b10: 0000 0200 0000 0300 0000 4300 0000 730e  ..........C...s.
 00004b20: 0000 0074 0074 017c 0083 017c 0183 0253  ...t.t.|...|...S
 00004b30: 0029 0161 6b01 0000 0a20 2020 2020 2020  .).ak....       
@@ -1220,17 +1220,17 @@
 00004c30: 2070 726f 7065 7274 7920 7661 6c75 6520   property value 
 00004c40: 6966 2065 7869 7374 732e 0a0a 2020 2020  if exists...    
 00004c50: 2020 2020 5261 6973 6573 3a0a 2020 2020      Raises:.    
 00004c60: 2020 2020 2020 2020 5661 6c75 6545 7272          ValueErr
 00004c70: 6f72 3a20 4966 2070 726f 7065 7274 7920  or: If property 
 00004c80: 7661 6c75 6520 6861 7320 696e 636f 7272  value has incorr
 00004c90: 6563 7420 666f 726d 6174 0a20 2020 2020  ect format.     
-00004ca0: 2020 2029 0272 2800 0000 725a 0000 0072     ).r(...rZ...r
+00004ca0: 2020 2029 0272 3000 0000 725a 0000 0072     ).r0...rZ...r
 00004cb0: 6700 0000 7249 0000 0072 4900 0000 724a  g...rI...rI...rJ
-00004cc0: 0000 0072 2800 0000 9402 0000 7302 0000  ...r(.......s...
+00004cc0: 0000 0072 3000 0000 9402 0000 7302 0000  ...r0.......s...
 00004cd0: 0000 0f7a 2a54 6173 6b55 7469 6c73 2e66  ...z*TaskUtils.f
 00004ce0: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
 00004cf0: 726f 7065 7274 795f 6173 5f64 6174 6563  roperty_as_datec
 00004d00: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 00004d10: 0300 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
 00004d20: 017c 0083 017c 0183 0253 0029 0161 7801  .|...|...S.).ax.
 00004d30: 0000 0a20 2020 2020 2020 2047 6574 2061  ...        Get a
@@ -1252,17 +1252,17 @@
 00004e30: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 00004e40: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 00004e50: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 00004e60: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 00004e70: 7065 7274 7920 7661 6c75 6520 646f 6573  perty value does
 00004e80: 6e27 7420 6578 6973 7420 6f72 2068 6173  n't exist or has
 00004e90: 2069 6e63 6f72 7265 6374 2066 6f72 6d61   incorrect forma
-00004ea0: 740a 2020 2020 2020 2020 2902 7232 0000  t.        ).r2..
+00004ea0: 740a 2020 2020 2020 2020 2902 723a 0000  t.        ).r:..
 00004eb0: 0072 5a00 0000 7267 0000 0072 4900 0000  .rZ...rg...rI...
-00004ec0: 7249 0000 0072 4a00 0000 7232 0000 00a5  rI...rJ...r2....
+00004ec0: 7249 0000 0072 4a00 0000 723a 0000 00a5  rI...rJ...r:....
 00004ed0: 0200 0073 0200 0000 000f 7a2d 5461 736b  ...s......z-Task
 00004ee0: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00004ef0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00004f00: 5f64 6174 6574 696d 6563 0200 0000 0000  _datetimec......
 00004f10: 0000 0000 0000 0200 0000 0300 0000 4300  ..............C.
 00004f20: 0000 730e 0000 0074 0074 017c 0083 017c  ..s....t.t.|...|
 00004f30: 0183 0253 0029 0161 6f01 0000 0a20 2020  ...S.).ao....   
@@ -1284,17 +1284,17 @@
 00005030: 2020 2020 2054 6865 2070 726f 7065 7274       The propert
 00005040: 7920 7661 6c75 6520 6966 2065 7869 7374  y value if exist
 00005050: 732e 0a0a 2020 2020 2020 2020 5261 6973  s...        Rais
 00005060: 6573 3a0a 2020 2020 2020 2020 2020 2020  es:.            
 00005070: 5661 6c75 6545 7272 6f72 3a20 4966 2070  ValueError: If p
 00005080: 726f 7065 7274 7920 7661 6c75 6520 6861  roperty value ha
 00005090: 7320 696e 636f 7272 6563 7420 666f 726d  s incorrect form
-000050a0: 6174 0a20 2020 2020 2020 2029 0272 2900  at.        ).r).
+000050a0: 6174 0a20 2020 2020 2020 2029 0272 3100  at.        ).r1.
 000050b0: 0000 725a 0000 0072 6700 0000 7249 0000  ..rZ...rg...rI..
-000050c0: 0072 4900 0000 724a 0000 0072 2900 0000  .rI...rJ...r)...
+000050c0: 0072 4900 0000 724a 0000 0072 3100 0000  .rI...rJ...r1...
 000050d0: b602 0000 7302 0000 0000 0f7a 2e54 6173  ....s......z.Tas
 000050e0: 6b55 7469 6c73 2e66 696e 645f 6a73 6f6e  kUtils.find_json
 000050f0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
 00005100: 6173 5f64 6174 6574 696d 6563 0200 0000  as_datetimec....
 00005110: 0000 0000 0000 0000 0200 0000 0300 0000  ................
 00005120: 4300 0000 730e 0000 0074 0074 017c 0083  C...s....t.t.|..
 00005130: 017c 0183 0253 0029 0161 7d01 0000 0a20  .|...S.).a}.... 
@@ -1317,15 +1317,15 @@
 00005240: 2076 616c 7565 2069 6620 6578 6973 7473   value if exists
 00005250: 2e0a 0a20 2020 2020 2020 2052 6169 7365  ...        Raise
 00005260: 733a 0a20 2020 2020 2020 2020 2020 2056  s:.            V
 00005270: 616c 7565 4572 726f 723a 2049 6620 7072  alueError: If pr
 00005280: 6f70 6572 7479 2076 616c 7565 2064 6f65  operty value doe
 00005290: 736e 2774 2065 7869 7374 206f 7220 6861  sn't exist or ha
 000052a0: 7320 696e 636f 7272 6563 7420 666f 726d  s incorrect form
-000052b0: 6174 0a20 2020 2020 2020 2029 0272 3600  at.        ).r6.
+000052b0: 6174 0a20 2020 2020 2020 2029 0272 3e00  at.        ).r>.
 000052c0: 0000 725a 0000 0072 6700 0000 7249 0000  ..rZ...rg...rI..
 000052d0: 0072 4900 0000 724a 0000 00da 1f67 6574  .rI...rJ.....get
 000052e0: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
 000052f0: 6572 7479 5f61 735f 6669 6c65 c702 0000  erty_as_file....
 00005300: 7302 0000 0000 0f7a 2954 6173 6b55 7469  s......z)TaskUti
 00005310: 6c73 2e67 6574 5f6a 736f 6e5f 666f 726d  ls.get_json_form
 00005320: 735f 7072 6f70 6572 7479 5f61 735f 6669  s_property_as_fi
@@ -1351,15 +1351,15 @@
 00005460: 2020 2054 6865 2070 726f 7065 7274 7920     The property 
 00005470: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 00005480: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 00005490: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 000054a0: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 000054b0: 7065 7274 7920 7661 6c75 6520 6861 7320  perty value has 
 000054c0: 696e 636f 7272 6563 7420 666f 726d 6174  incorrect format
-000054d0: 0a20 2020 2020 2020 2029 0272 2d00 0000  .        ).r-...
+000054d0: 0a20 2020 2020 2020 2029 0272 3500 0000  .        ).r5...
 000054e0: 725a 0000 0072 6700 0000 7249 0000 0072  rZ...rg...rI...r
 000054f0: 4900 0000 724a 0000 00da 2066 696e 645f  I...rJ.... find_
 00005500: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
 00005510: 7274 795f 6173 5f66 696c 65d8 0200 0073  rty_as_file....s
 00005520: 0200 0000 000f 7a2a 5461 736b 5574 696c  ......z*TaskUtil
 00005530: 732e 6669 6e64 5f6a 736f 6e5f 666f 726d  s.find_json_form
 00005540: 735f 7072 6f70 6572 7479 5f61 735f 6669  s_property_as_fi
@@ -1386,15 +1386,15 @@
 00005690: 7565 2069 6620 6578 6973 7473 2e0a 0a20  ue if exists... 
 000056a0: 2020 2020 2020 2052 6169 7365 733a 0a20         Raises:. 
 000056b0: 2020 2020 2020 2020 2020 2056 616c 7565             Value
 000056c0: 4572 726f 723a 2049 6620 7072 6f70 6572  Error: If proper
 000056d0: 7479 2076 616c 7565 2064 6f65 736e 2774  ty value doesn't
 000056e0: 2065 7869 7374 206f 7220 6861 7320 696e   exist or has in
 000056f0: 636f 7272 6563 7420 666f 726d 6174 0a20  correct format. 
-00005700: 2020 2020 2020 2029 0272 3700 0000 725a         ).r7...rZ
+00005700: 2020 2020 2020 2029 0272 3f00 0000 725a         ).r?...rZ
 00005710: 0000 0072 6700 0000 7249 0000 0072 4900  ...rg...rI...rI.
 00005720: 0000 724a 0000 00da 2467 6574 5f6a 736f  ..rJ....$get_jso
 00005730: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
 00005740: 5f61 735f 7072 696e 6369 7061 6ce9 0200  _as_principal...
 00005750: 0073 0200 0000 000f 7a2e 5461 736b 5574  .s......z.TaskUt
 00005760: 696c 732e 6765 745f 6a73 6f6e 5f66 6f72  ils.get_json_for
 00005770: 6d73 5f70 726f 7065 7274 795f 6173 5f70  ms_property_as_p
@@ -1421,15 +1421,15 @@
 000058c0: 6520 7072 6f70 6572 7479 2076 616c 7565  e property value
 000058d0: 2069 6620 6578 6973 7473 2e0a 0a20 2020   if exists...   
 000058e0: 2020 2020 2052 6169 7365 733a 0a20 2020       Raises:.   
 000058f0: 2020 2020 2020 2020 2056 616c 7565 4572           ValueEr
 00005900: 726f 723a 2049 6620 7072 6f70 6572 7479  ror: If property
 00005910: 2076 616c 7565 2068 6173 2069 6e63 6f72   value has incor
 00005920: 7265 6374 2066 6f72 6d61 740a 2020 2020  rect format.    
-00005930: 2020 2020 2902 722e 0000 0072 5a00 0000      ).r....rZ...
+00005930: 2020 2020 2902 7236 0000 0072 5a00 0000      ).r6...rZ...
 00005940: 7267 0000 0072 4900 0000 7249 0000 0072  rg...rI...rI...r
 00005950: 4a00 0000 da25 6669 6e64 5f6a 736f 6e5f  J....%find_json_
 00005960: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
 00005970: 735f 7072 696e 6369 7061 6cfa 0200 0073  s_principal....s
 00005980: 0200 0000 000f 7a2f 5461 736b 5574 696c  ......z/TaskUtil
 00005990: 732e 6669 6e64 5f6a 736f 6e5f 666f 726d  s.find_json_form
 000059a0: 735f 7072 6f70 6572 7479 5f61 735f 7072  s_property_as_pr
@@ -1456,16 +1456,16 @@
 00005af0: 7374 732e 0a0a 2020 2020 2020 2020 5261  sts...        Ra
 00005b00: 6973 6573 3a0a 2020 2020 2020 2020 2020  ises:.          
 00005b10: 2020 5661 6c75 6545 7272 6f72 3a20 4966    ValueError: If
 00005b20: 2070 726f 7065 7274 7920 7661 6c75 6520   property value 
 00005b30: 646f 6573 6e27 7420 6578 6973 7420 6f72  doesn't exist or
 00005b40: 2068 6173 2069 6e63 6f72 7265 6374 2066   has incorrect f
 00005b50: 6f72 6d61 740a 2020 2020 2020 2020 2902  ormat.        ).
-00005b60: 7238 0000 0072 5a00 0000 7267 0000 0072  r8...rZ...rg...r
-00005b70: 4900 0000 7249 0000 0072 4a00 0000 7238  I...rI...rJ...r8
+00005b60: 7240 0000 0072 5a00 0000 7267 0000 0072  r@...rZ...rg...r
+00005b70: 4900 0000 7249 0000 0072 4a00 0000 7240  I...rI...rJ...r@
 00005b80: 0000 000b 0300 0073 0200 0000 000f 7a29  .......s......z)
 00005b90: 5461 736b 5574 696c 732e 6765 745f 6a73  TaskUtils.get_js
 00005ba0: 6f6e 5f66 6f72 6d73 5f70 726f 7065 7274  on_forms_propert
 00005bb0: 795f 6173 5f6c 6973 7463 0200 0000 0000  y_as_listc......
 00005bc0: 0000 0000 0000 0200 0000 0300 0000 4300  ..............C.
 00005bd0: 0000 730e 0000 0074 0074 017c 0083 017c  ..s....t.t.|...|
 00005be0: 0183 0253 0029 0161 6b01 0000 0a20 2020  ...S.).ak....   
@@ -1487,17 +1487,17 @@
 00005ce0: 2054 6865 2070 726f 7065 7274 7920 7661   The property va
 00005cf0: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00005d00: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00005d10: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00005d20: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00005d30: 7274 7920 7661 6c75 6520 6861 7320 696e  rty value has in
 00005d40: 636f 7272 6563 7420 666f 726d 6174 0a20  correct format. 
-00005d50: 2020 2020 2020 2029 0272 2f00 0000 725a         ).r/...rZ
+00005d50: 2020 2020 2020 2029 0272 3700 0000 725a         ).r7...rZ
 00005d60: 0000 0072 6700 0000 7249 0000 0072 4900  ...rg...rI...rI.
-00005d70: 0000 724a 0000 0072 2f00 0000 1c03 0000  ..rJ...r/.......
+00005d70: 0000 724a 0000 0072 3700 0000 1c03 0000  ..rJ...r7.......
 00005d80: 7302 0000 0000 0f7a 2a54 6173 6b55 7469  s......z*TaskUti
 00005d90: 6c73 2e66 696e 645f 6a73 6f6e 5f66 6f72  ls.find_json_for
 00005da0: 6d73 5f70 726f 7065 7274 795f 6173 5f6c  ms_property_as_l
 00005db0: 6973 7463 0200 0000 0000 0000 0000 0000  istc............
 00005dc0: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
 00005dd0: 0074 0074 017c 0083 017c 0183 0253 0029  .t.t.|...|...S.)
 00005de0: 0161 7401 0000 0a20 2020 2020 2020 2047  .at....        G
@@ -1519,17 +1519,17 @@
 00005ee0: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 00005ef0: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 00005f00: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 00005f10: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 00005f20: 7065 7274 7920 7661 6c75 6520 646f 6573  perty value does
 00005f30: 6e27 7420 6578 6973 7420 6f72 2068 6173  n't exist or has
 00005f40: 2069 6e63 6f72 7265 6374 2066 6f72 6d61   incorrect forma
-00005f50: 740a 2020 2020 2020 2020 2902 7233 0000  t.        ).r3..
+00005f50: 740a 2020 2020 2020 2020 2902 723b 0000  t.        ).r;..
 00005f60: 0072 5a00 0000 7267 0000 0072 4900 0000  .rZ...rg...rI...
-00005f70: 7249 0000 0072 4a00 0000 7233 0000 002d  rI...rJ...r3...-
+00005f70: 7249 0000 0072 4a00 0000 723b 0000 002d  rI...rJ...r;...-
 00005f80: 0300 0073 0200 0000 000f 7a29 5461 736b  ...s......z)Task
 00005f90: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00005fa0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00005fb0: 5f64 6963 7463 0200 0000 0000 0000 0000  _dictc..........
 00005fc0: 0000 0200 0000 0300 0000 4300 0000 730e  ..........C...s.
 00005fd0: 0000 0074 0074 017c 0083 017c 0183 0253  ...t.t.|...|...S
 00005fe0: 0029 0161 6b01 0000 0a20 2020 2020 2020  .).ak....       
@@ -1551,17 +1551,17 @@
 000060e0: 2070 726f 7065 7274 7920 7661 6c75 6520   property value 
 000060f0: 6966 2065 7869 7374 732e 0a0a 2020 2020  if exists...    
 00006100: 2020 2020 5261 6973 6573 3a0a 2020 2020      Raises:.    
 00006110: 2020 2020 2020 2020 5661 6c75 6545 7272          ValueErr
 00006120: 6f72 3a20 4966 2070 726f 7065 7274 7920  or: If property 
 00006130: 7661 6c75 6520 6861 7320 696e 636f 7272  value has incorr
 00006140: 6563 7420 666f 726d 6174 0a20 2020 2020  ect format.     
-00006150: 2020 2029 0272 2a00 0000 725a 0000 0072     ).r*...rZ...r
+00006150: 2020 2029 0272 3200 0000 725a 0000 0072     ).r2...rZ...r
 00006160: 6700 0000 7249 0000 0072 4900 0000 724a  g...rI...rI...rJ
-00006170: 0000 0072 2a00 0000 3e03 0000 7302 0000  ...r*...>...s...
+00006170: 0000 0072 3200 0000 3e03 0000 7302 0000  ...r2...>...s...
 00006180: 0000 0f7a 2a54 6173 6b55 7469 6c73 2e66  ...z*TaskUtils.f
 00006190: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
 000061a0: 726f 7065 7274 795f 6173 5f64 6963 7429  roperty_as_dict)
 000061b0: 0472 4500 0000 7266 0000 00da 0576 616c  .rE...rf.....val
 000061c0: 7565 7252 0000 0063 0300 0000 0000 0000  uerR...c........
 000061d0: 0000 0000 0300 0000 0400 0000 4300 0000  ............C...
 000061e0: 7314 0000 0074 0074 017c 0083 017c 017c  s....t.t.|...|.|
@@ -1584,43 +1584,43 @@
 000062f0: 7565 3a20 5661 6c75 6520 746f 2075 7064  ue: Value to upd
 00006300: 6174 650a 0a20 2020 2020 2020 2052 6169  ate..        Rai
 00006310: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 00006320: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 00006330: 7072 6f70 6572 7479 2076 616c 7565 2068  property value h
 00006340: 6173 2069 6e63 6f72 7265 6374 2066 6f72  as incorrect for
 00006350: 6d61 740a 2020 2020 2020 2020 4e29 0272  mat.        N).r
-00006360: 3a00 0000 725a 0000 0029 0372 4500 0000  :...rZ...).rE...
+00006360: 4200 0000 725a 0000 0029 0372 4500 0000  B...rZ...).rE...
 00006370: 7266 0000 0072 6c00 0000 7249 0000 0072  rf...rl...rI...r
-00006380: 4900 0000 724a 0000 0072 3a00 0000 4f03  I...rJ...r:...O.
+00006380: 4900 0000 724a 0000 0072 4200 0000 4f03  I...rJ...rB...O.
 00006390: 0000 7302 0000 0000 0d7a 2454 6173 6b55  ..s......z$TaskU
 000063a0: 7469 6c73 2e75 7064 6174 655f 6a73 6f6e  tils.update_json
 000063b0: 5f66 6f72 6d73 5f70 726f 7065 7274 7929  _forms_property)
 000063c0: 014e 2901 4e29 014e 2901 4e29 4272 5600  .N).N).N).N)BrV.
 000063d0: 0000 7257 0000 0072 5800 0000 da0c 7374  ..rW...rX.....st
-000063e0: 6174 6963 6d65 7468 6f64 7240 0000 0072  aticmethodr@...r
-000063f0: 5900 0000 da04 626f 6f6c 7220 0000 00da  Y.....boolr ....
-00006400: 0369 6e74 7221 0000 0072 0500 0000 7224  .intr!...r....r$
-00006410: 0000 0072 2500 0000 7209 0000 0072 2200  ...r%...r....r".
-00006420: 0000 7204 0000 0072 2300 0000 720c 0000  ..r....r#...r...
-00006430: 0072 0d00 0000 721e 0000 0072 1300 0000  .r....r....r....
-00006440: 721f 0000 00da 0566 6c6f 6174 721a 0000  r......floatr...
-00006450: 0072 1100 0000 721b 0000 0072 0600 0000  .r....r....r....
-00006460: 7214 0000 0072 0e00 0000 7215 0000 00da  r....r....r.....
-00006470: 0464 6963 7472 1600 0000 720f 0000 0072  .dictr....r....r
-00006480: 1700 0000 7241 0000 0072 1800 0000 7210  ....rA...r....r.
-00006490: 0000 0072 1900 0000 7242 0000 0072 1c00  ...r....rB...r..
-000064a0: 0000 7212 0000 0072 1d00 0000 7239 0000  ..r....r....r9..
-000064b0: 0072 3000 0000 7235 0000 0072 2c00 0000  .r0...r5...r,...
-000064c0: 7234 0000 0072 2b00 0000 7231 0000 0072  r4...r+...r1...r
-000064d0: 2800 0000 7207 0000 0072 3200 0000 7229  (...r....r2...r)
-000064e0: 0000 0072 3d00 0000 7268 0000 0072 6900  ...r=...rh...ri.
-000064f0: 0000 723e 0000 0072 6a00 0000 726b 0000  ..r>...rj...rk..
-00006500: 00da 046c 6973 7472 3800 0000 722f 0000  ...listr8...r/..
-00006510: 0072 3300 0000 722a 0000 0072 2700 0000  .r3...r*...r'...
-00006520: 723a 0000 0072 4900 0000 7249 0000 0072  r:...rI...rI...r
+000063e0: 6174 6963 6d65 7468 6f64 720d 0000 0072  aticmethodr....r
+000063f0: 5900 0000 da04 626f 6f6c 7228 0000 00da  Y.....boolr(....
+00006400: 0369 6e74 7229 0000 0072 0700 0000 722c  .intr)...r....r,
+00006410: 0000 0072 2d00 0000 7211 0000 0072 2a00  ...r-...r....r*.
+00006420: 0000 7206 0000 0072 2b00 0000 7214 0000  ..r....r+...r...
+00006430: 0072 1500 0000 7226 0000 0072 1b00 0000  .r....r&...r....
+00006440: 7227 0000 00da 0566 6c6f 6174 7222 0000  r'.....floatr"..
+00006450: 0072 1900 0000 7223 0000 0072 0200 0000  .r....r#...r....
+00006460: 721c 0000 0072 1600 0000 721d 0000 00da  r....r....r.....
+00006470: 0464 6963 7472 1e00 0000 7217 0000 0072  .dictr....r....r
+00006480: 1f00 0000 720e 0000 0072 2000 0000 7218  ....r....r ...r.
+00006490: 0000 0072 2100 0000 720f 0000 0072 2400  ...r!...r....r$.
+000064a0: 0000 721a 0000 0072 2500 0000 7241 0000  ..r....r%...rA..
+000064b0: 0072 3800 0000 723d 0000 0072 3400 0000  .r8...r=...r4...
+000064c0: 723c 0000 0072 3300 0000 7239 0000 0072  r<...r3...r9...r
+000064d0: 3000 0000 7203 0000 0072 3a00 0000 7231  0...r....r:...r1
+000064e0: 0000 0072 0a00 0000 7268 0000 0072 6900  ...r....rh...ri.
+000064f0: 0000 720b 0000 0072 6a00 0000 726b 0000  ..r....rj...rk..
+00006500: 00da 046c 6973 7472 4000 0000 7237 0000  ...listr@...r7..
+00006510: 0072 3b00 0000 7232 0000 0072 2f00 0000  .r;...r2...r/...
+00006520: 7242 0000 0072 4900 0000 7249 0000 0072  rB...rI...rI...r
 00006530: 4900 0000 724a 0000 0072 6000 0000 8800  I...rJ...r`.....
 00006540: 0000 7304 0100 0008 0102 0114 0d02 0202  ..s.............
 00006550: 0102 0102 0102 fc0e 1202 011a 1002 011c  ................
 00006560: 1102 0200 ff02 0102 0002 0006 0102 fe0e  ................
 00006570: 1202 0200 ff02 0102 0002 000a 0102 fe0e  ................
 00006580: 1202 0200 ff02 0102 0002 0006 0102 fe0e  ................
 00006590: 1202 0200 ff02 0102 0002 000a 0102 fe0e  ................
@@ -1631,35 +1631,35 @@
 000065e0: 0202 0002 0106 fe0e 0f02 0114 0d02 0202  ................
 000065f0: 0002 0106 fe0e 0f02 0202 0002 0106 fe0e  ................
 00006600: 0f02 0114 1002 0118 1002 0114 1002 0118  ................
 00006610: 1002 0114 1002 0118 1002 0114 1002 0118  ................
 00006620: 1002 0114 1002 0118 1002 0114 1002 0118  ................
 00006630: 1002 0114 1002 0118 1002 0114 1002 0118  ................
 00006640: 1002 0114 1002 0118 1002 0172 6000 0000  ...........r`...
-00006650: 4e29 47da 0674 7970 696e 6772 0200 0000  N)G..typingr....
-00006660: 7203 0000 0072 0400 0000 7205 0000 0072  r....r....r....r
-00006670: 0700 0000 7206 0000 0072 4c00 0000 7209  ....r....rL...r.
-00006680: 0000 0072 0a00 0000 720b 0000 0072 0c00  ...r....r....r..
-00006690: 0000 720d 0000 0072 0e00 0000 720f 0000  ..r....r....r...
-000066a0: 0072 1000 0000 7211 0000 0072 1200 0000  .r....r....r....
-000066b0: 7213 0000 0072 1400 0000 7215 0000 0072  r....r....r....r
-000066c0: 1600 0000 7217 0000 0072 1800 0000 7219  ....r....r....r.
-000066d0: 0000 0072 1a00 0000 721b 0000 0072 1c00  ...r....r....r..
-000066e0: 0000 721d 0000 0072 1e00 0000 721f 0000  ..r....r....r...
-000066f0: 0072 2000 0000 7221 0000 0072 2200 0000  .r ...r!...r"...
-00006700: 7223 0000 0072 2400 0000 7225 0000 00da  r#...r$...r%....
-00006710: 0a6a 736f 6e5f 666f 726d 7372 2600 0000  .json_formsr&...
-00006720: 7227 0000 0072 2800 0000 7229 0000 0072  r'...r(...r)...r
-00006730: 2a00 0000 722b 0000 0072 2c00 0000 722d  *...r+...r,...r-
-00006740: 0000 0072 2e00 0000 722f 0000 0072 3000  ...r....r/...r0.
-00006750: 0000 7231 0000 0072 3200 0000 7233 0000  ..r1...r2...r3..
-00006760: 0072 3400 0000 7235 0000 0072 3600 0000  .r4...r5...r6...
-00006770: 7237 0000 0072 3800 0000 7239 0000 0072  r7...r8...r9...r
-00006780: 3a00 0000 5a11 5f67 656e 6572 6174 6564  :...Z._generated
-00006790: 2e6d 6f64 656c 7372 3c00 0000 da06 6d6f  .modelsr<.....mo
-000067a0: 6465 6c73 723d 0000 0072 3e00 0000 723f  delsr=...r>...r?
+00006650: 4e29 4772 0300 0000 7202 0000 00da 0674  N)Gr....r......t
+00006660: 7970 696e 6772 0400 0000 7205 0000 0072  ypingr....r....r
+00006670: 0600 0000 7207 0000 005a 115f 6765 6e65  ....r....Z._gene
+00006680: 7261 7465 642e 6d6f 6465 6c73 7209 0000  rated.modelsr...
+00006690: 00da 066d 6f64 656c 7372 0a00 0000 720b  ...modelsr....r.
+000066a0: 0000 0072 0c00 0000 720d 0000 0072 0e00  ...r....r....r..
+000066b0: 0000 720f 0000 0072 4c00 0000 7211 0000  ..r....rL...r...
+000066c0: 0072 1200 0000 7213 0000 0072 1400 0000  .r....r....r....
+000066d0: 7215 0000 0072 1600 0000 7217 0000 0072  r....r....r....r
+000066e0: 1800 0000 7219 0000 0072 1a00 0000 721b  ....r....r....r.
+000066f0: 0000 0072 1c00 0000 721d 0000 0072 1e00  ...r....r....r..
+00006700: 0000 721f 0000 0072 2000 0000 7221 0000  ..r....r ...r!..
+00006710: 0072 2200 0000 7223 0000 0072 2400 0000  .r"...r#...r$...
+00006720: 7225 0000 0072 2600 0000 7227 0000 0072  r%...r&...r'...r
+00006730: 2800 0000 7229 0000 0072 2a00 0000 722b  (...r)...r*...r+
+00006740: 0000 0072 2c00 0000 722d 0000 00da 0a6a  ...r,...r-.....j
+00006750: 736f 6e5f 666f 726d 7372 2e00 0000 722f  son_formsr....r/
+00006760: 0000 0072 3000 0000 7231 0000 0072 3200  ...r0...r1...r2.
+00006770: 0000 7233 0000 0072 3400 0000 7235 0000  ..r3...r4...r5..
+00006780: 0072 3600 0000 7237 0000 0072 3800 0000  .r6...r7...r8...
+00006790: 7239 0000 0072 3a00 0000 723b 0000 0072  r9...r:...r;...r
+000067a0: 3c00 0000 723d 0000 0072 3e00 0000 723f  <...r=...r>...r?
 000067b0: 0000 0072 4000 0000 7241 0000 0072 4200  ...r@...rA...rB.
 000067c0: 0000 7243 0000 0072 5a00 0000 7260 0000  ..rC...rZ...r`..
 000067d0: 0072 4900 0000 7249 0000 0072 4900 0000  .rI...rI...rI...
 000067e0: 724a 0000 00da 083c 6d6f 6475 6c65 3e1a  rJ.....<module>.
-000067f0: 0000 0073 1000 0000 1801 1002 7c1f 5c17  ...s........|.\.
-00006800: 0c01 200a 1019 1011                      .. .....
+000067f0: 0000 0073 1000 0000 1001 1802 0c01 2008  ...s.......... .
+00006800: 7c1f 5c19 1019 1011                      |.\.....
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/element_values.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/element_values.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 18805 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 7% similar despite different names*

```diff
@@ -1,68 +1,68 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 7549 0000  U.......=S.duI..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 7549 0000  U..........duI..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0009 0000 0040 0000 0073 5c03 0000 6400  .....@...s\...d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 6d04 5a04 0100 6400 6402 6c05 6d06 5a06  m.Z...d.d.l.m.Z.
-00000050: 0100 6400 6403 6c07 6d08 5a08 6d09 5a09  ..d.d.l.m.Z.m.Z.
+00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
+00000040: 6402 6c03 6d04 5a04 0100 6400 6403 6c05  d.l.m.Z...d.d.l.
+00000050: 6d06 5a06 6d07 5a07 6d08 5a08 6d09 5a09  m.Z.m.Z.m.Z.m.Z.
 00000060: 0100 6404 6405 6c0a 6d0b 5a0b 6d0c 5a0c  ..d.d.l.m.Z.m.Z.
 00000070: 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f 6d10 5a10  m.Z.m.Z.m.Z.m.Z.
 00000080: 6d11 5a11 6d12 5a12 6d13 5a13 6d14 5a14  m.Z.m.Z.m.Z.m.Z.
 00000090: 6d15 5a15 6d16 5a16 6d17 5a17 6d18 5a18  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d19 5a19 0100 6501 650d 650c 6602 1900  m.Z...e.e.e.f...
-000000b0: 5a1a 6501 6517 6513 6514 6511 6515 6605  Z.e.e.e.e.e.e.f.
-000000c0: 1900 5a1b 6501 650d 650c 6517 6513 6514  ..Z.e.e.e.e.e.e.
-000000d0: 6511 6515 6607 1900 5a1c 6501 650b 650e  e.e.f...Z.e.e.e.
-000000e0: 6510 6518 6604 1900 5a1d 6501 650f 6519  e.e.f...Z.e.e.e.
-000000f0: 6602 1900 5a1e 6501 651f 6520 6521 6522  f...Z.e.e.e e!e"
-00000100: 6506 6503 651f 6523 6602 1900 6512 6516  e.e.e.e#f...e.e.
+000000a0: 6d19 5a19 0100 6509 650d 650c 6602 1900  m.Z...e.e.e.f...
+000000b0: 5a1a 6509 6517 6513 6514 6511 6515 6605  Z.e.e.e.e.e.e.f.
+000000c0: 1900 5a1b 6509 650d 650c 6517 6513 6514  ..Z.e.e.e.e.e.e.
+000000d0: 6511 6515 6607 1900 5a1c 6509 650b 650e  e.e.f...Z.e.e.e.
+000000e0: 6510 6518 6604 1900 5a1d 6509 650f 6519  e.e.f...Z.e.e.e.
+000000f0: 6602 1900 5a1e 6509 651f 6520 6521 6522  f...Z.e.e.e e!e"
+00000100: 6504 6506 651f 6523 6602 1900 6512 6516  e.e.e.e#f...e.e.
 00000110: 6608 1900 5a24 4700 6406 6407 8400 6407  f...Z$G.d.d...d.
-00000120: 6508 8303 5a25 4700 6408 6409 8400 6409  e...Z%G.d.d...d.
+00000120: 6501 8303 5a25 4700 6408 6409 8400 6409  e...Z%G.d.d...d.
 00000130: 6525 8303 5a26 4700 640a 640b 8400 640b  e%..Z&G.d.d...d.
 00000140: 6525 8303 5a27 6525 6522 640c 9c02 640d  e%..Z'e%e"d...d.
 00000150: 640e 8404 5a28 6525 6520 6522 640f 9c03  d...Z(e%e e"d...
-00000160: 6410 6411 8404 5a29 6525 6504 6522 1900  d.d...Z)e%e.e"..
+00000160: 6410 6411 8404 5a29 6525 6508 6522 1900  d.d...Z)e%e.e"..
 00000170: 6525 6412 9c03 6413 6414 8404 5a2a 6525  e%d...d.d...Z*e%
-00000180: 6504 6522 1900 6520 6525 6415 9c04 6416  e.e"..e e%d...d.
-00000190: 6417 8404 5a2b 644c 6525 6504 6524 1900  d...Z+dLe%e.e$..
+00000180: 6508 6522 1900 6520 6525 6415 9c04 6416  e.e"..e e%d...d.
+00000190: 6417 8404 5a2b 644c 6525 6508 6524 1900  d...Z+dLe%e.e$..
 000001a0: 6525 6419 9c03 641a 641b 8405 5a2c 644d  e%d...d.d...Z,dM
-000001b0: 6525 6504 6502 6524 1900 1900 6525 641c  e%e.e.e$....e%d.
-000001c0: 9c03 641d 641e 8405 5a2d 644e 6525 6504  ..d.d...Z-dNe%e.
+000001b0: 6525 6508 6507 6524 1900 1900 6525 641c  e%e.e.e$....e%d.
+000001c0: 9c03 641d 641e 8405 5a2d 644e 6525 6508  ..d.d...Z-dNe%e.
 000001d0: 6524 1900 6525 6419 9c03 641f 6420 8405  e$..e%d...d.d ..
-000001e0: 5a2e 644f 6525 6504 6502 6524 1900 1900  Z.dOe%e.e.e$....
+000001e0: 5a2e 644f 6525 6508 6507 6524 1900 1900  Z.dOe%e.e.e$....
 000001f0: 6525 641c 9c03 6421 6422 8405 5a2f 6525  e%d...d!d"..Z/e%
 00000200: 651f 640c 9c02 6423 6424 8404 5a30 6525  e.d...d#d$..Z0e%
-00000210: 6504 651f 1900 640c 9c02 6425 6426 8404  e.e...d...d%d&..
-00000220: 5a31 6525 6502 651f 1900 640c 9c02 6427  Z1e%e.e...d...d'
+00000210: 6508 651f 1900 640c 9c02 6425 6426 8404  e.e...d...d%d&..
+00000220: 5a31 6525 6507 651f 1900 640c 9c02 6427  Z1e%e.e...d...d'
 00000230: 6428 8404 5a32 6525 6521 640c 9c02 6429  d(..Z2e%e!d...d)
-00000240: 642a 8404 5a33 6525 6504 6521 1900 640c  d*..Z3e%e.e!..d.
-00000250: 9c02 642b 642c 8404 5a34 6525 6502 6521  ..d+d,..Z4e%e.e!
+00000240: 642a 8404 5a33 6525 6508 6521 1900 640c  d*..Z3e%e.e!..d.
+00000250: 9c02 642b 642c 8404 5a34 6525 6507 6521  ..d+d,..Z4e%e.e!
 00000260: 1900 640c 9c02 642d 642e 8404 5a35 6525  ..d...d-d...Z5e%
-00000270: 6506 640c 9c02 642f 6430 8404 5a36 6525  e.d...d/d0..Z6e%
-00000280: 6504 6506 1900 640c 9c02 6431 6432 8404  e.e...d...d1d2..
-00000290: 5a37 6525 6502 6506 1900 640c 9c02 6433  Z7e%e.e...d...d3
+00000270: 6504 640c 9c02 642f 6430 8404 5a36 6525  e.d...d/d0..Z6e%
+00000280: 6508 6504 1900 640c 9c02 6431 6432 8404  e.e...d...d1d2..
+00000290: 5a37 6525 6507 6504 1900 640c 9c02 6433  Z7e%e.e...d...d3
 000002a0: 6434 8404 5a38 6525 6539 640c 9c02 6435  d4..Z8e%e9d...d5
-000002b0: 6436 8404 5a3a 6525 6504 6539 1900 640c  d6..Z:e%e.e9..d.
-000002c0: 9c02 6437 6438 8404 5a3b 6525 6502 6539  ..d7d8..Z;e%e.e9
+000002b0: 6436 8404 5a3a 6525 6508 6539 1900 640c  d6..Z:e%e.e9..d.
+000002c0: 9c02 6437 6438 8404 5a3b 6525 6507 6539  ..d7d8..Z;e%e.e9
 000002d0: 1900 640c 9c02 6439 643a 8404 5a3c 6525  ..d...d9d:..Z<e%
 000002e0: 6512 640c 9c02 643b 643c 8404 5a3d 6525  e.d...d;d<..Z=e%
-000002f0: 6504 6512 1900 640c 9c02 643d 643e 8404  e.e...d...d=d>..
-00000300: 5a3e 6525 6502 6512 1900 640c 9c02 643f  Z>e%e.e...d...d?
+000002f0: 6508 6512 1900 640c 9c02 643d 643e 8404  e.e...d...d=d>..
+00000300: 5a3e 6525 6507 6512 1900 640c 9c02 643f  Z>e%e.e...d...d?
 00000310: 6440 8404 5a3f 6525 6516 640c 9c02 6441  d@..Z?e%e.d...dA
-00000320: 6442 8404 5a40 6525 6504 6516 1900 640c  dB..Z@e%e.e...d.
-00000330: 9c02 6443 6444 8404 5a41 6525 6502 6516  ..dCdD..ZAe%e.e.
+00000320: 6442 8404 5a40 6525 6508 6516 1900 640c  dB..Z@e%e.e...d.
+00000330: 9c02 6443 6444 8404 5a41 6525 6507 6516  ..dCdD..ZAe%e.e.
 00000340: 1900 640c 9c02 6445 6446 8404 5a42 6450  ..d...dEdF..ZBdP
-00000350: 6525 6504 6502 6524 1900 1900 6502 6501  e%e.e.e$....e.e.
+00000350: 6525 6508 6507 6524 1900 1900 6507 6509  e%e.e.e$....e.e.
 00000360: 651a 651b 6602 1900 1900 641c 9c03 6447  e.e.f.....d...dG
 00000370: 6448 8405 5a43 6524 6524 6449 9c02 644a  dH..ZCe$e$dI..dJ
 00000380: 644b 8404 5a44 6418 5300 2951 e900 0000  dK..ZDd.S.)Q....
-00000390: 0029 04da 0555 6e69 6f6e da04 4c69 7374  .)...Union..List
-000003a0: da04 4469 6374 da08 4f70 7469 6f6e 616c  ..Dict..Optional
-000003b0: 2901 da04 6461 7465 2902 da03 4142 43da  )...date)...ABC.
-000003c0: 0e61 6273 7472 6163 746d 6574 686f 64e9  .abstractmethod.
+00000390: 0029 02da 0341 4243 da0e 6162 7374 7261  .)...ABC..abstra
+000003a0: 6374 6d65 7468 6f64 2901 da04 6461 7465  ctmethod)...date
+000003b0: 2904 da04 4469 6374 da04 4c69 7374 da08  )...Dict..List..
+000003c0: 4f70 7469 6f6e 616c da05 556e 696f 6ee9  Optional..Union.
 000003d0: 0200 0000 290f da07 5072 6f63 6573 73da  ....)...Process.
 000003e0: 1950 726f 6365 7373 456c 656d 656e 7456  .ProcessElementV
 000003f0: 616c 7565 4e75 6d62 6572 da19 5072 6f63  alueNumber..Proc
 00000400: 6573 7345 6c65 6d65 6e74 5661 6c75 6553  essElementValueS
 00000410: 7472 696e 67da 0f50 726f 6365 7373 5061  tring..ProcessPa
 00000420: 6765 4974 656d da19 5072 6f63 6573 7353  geItem..ProcessS
 00000430: 6176 6545 6c65 6d65 6e74 436f 6d6d 616e  aveElementComman
@@ -123,18 +123,18 @@
 000007a0: 00da 1774 6f5f 656c 656d 656e 745f 7661  ...to_element_va
 000007b0: 6c75 655f 6f62 6a65 6374 5400 0000 7302  lue_objectT...s.
 000007c0: 0000 0000 027a 2c45 6c65 6d65 6e74 5661  .....z,ElementVa
 000007d0: 6c75 6541 6363 6573 736f 722e 746f 5f65  lueAccessor.to_e
 000007e0: 6c65 6d65 6e74 5f76 616c 7565 5f6f 626a  lement_value_obj
 000007f0: 6563 744e 290b da08 5f5f 6e61 6d65 5f5f  ectN)...__name__
 00000800: da0a 5f5f 6d6f 6475 6c65 5f5f da0c 5f5f  ..__module__..__
-00000810: 7175 616c 6e61 6d65 5f5f 7208 0000 0072  qualname__r....r
-00000820: 0300 0000 da11 456c 656d 656e 7456 616c  ......ElementVal
+00000810: 7175 616c 6e61 6d65 5f5f 7203 0000 0072  qualname__r....r
+00000820: 0600 0000 da11 456c 656d 656e 7456 616c  ......ElementVal
 00000830: 7565 556e 696f 6e72 2300 0000 7227 0000  ueUnionr#...r'..
-00000840: 0072 0500 0000 da16 456c 656d 656e 7456  .r......ElementV
+00000840: 0072 0700 0000 da16 456c 656d 656e 7456  .r......ElementV
 00000850: 616c 7565 5369 6d70 6c65 5479 7065 722b  alueSimpleTyper+
 00000860: 0000 0072 2100 0000 7221 0000 0072 2100  ...r!...r!...r!.
 00000870: 0000 7222 0000 0072 1900 0000 4b00 0000  ..r"...r....K...
 00000880: 730c 0000 0008 0102 0114 0302 0114 0302  s...............
 00000890: 0172 1900 0000 6300 0000 0000 0000 0000  .r....c.........
 000008a0: 0000 0000 0000 0003 0000 0040 0000 0073  ...........@...s
 000008b0: 4800 0000 6500 5a01 6400 5a02 6503 6504  H...e.Z.d.Z.e.e.
@@ -178,16 +178,16 @@
 00000b10: 0072 2100 0000 7222 0000 0072 2b00 0000  .r!...r"...r+...
 00000b20: 6000 0000 731a 0000 0000 0108 0104 010a  `...s...........
 00000b30: 0102 0102 0102 fe06 040e 0102 0102 0102  ................
 00000b40: fe06 057a 3350 726f 6365 7373 456c 656d  ...z3ProcessElem
 00000b50: 656e 7456 616c 7565 4163 6365 7373 6f72  entValueAccessor
 00000b60: 2e74 6f5f 656c 656d 656e 745f 7661 6c75  .to_element_valu
 00000b70: 655f 6f62 6a65 6374 4ea9 0a72 2c00 0000  e_objectN..r,...
-00000b80: 722d 0000 0072 2e00 0000 7203 0000 0072  r-...r....r....r
-00000b90: 2f00 0000 7223 0000 0072 2700 0000 7205  /...r#...r'...r.
+00000b80: 722d 0000 0072 2e00 0000 7206 0000 0072  r-...r....r....r
+00000b90: 2f00 0000 7223 0000 0072 2700 0000 7207  /...r#...r'...r.
 00000ba0: 0000 0072 3000 0000 722b 0000 0072 2100  ...r0...r+...r!.
 00000bb0: 0000 7221 0000 0072 2100 0000 7222 0000  ..r!...r!...r"..
 00000bc0: 0072 3100 0000 5900 0000 7306 0000 0008  .r1...Y...s.....
 00000bd0: 0112 0312 0372 3100 0000 6300 0000 0000  .....r1...c.....
 00000be0: 0000 0000 0000 0000 0000 0003 0000 0040  ...............@
 00000bf0: 0000 0073 4800 0000 6500 5a01 6400 5a02  ...sH...e.Z.d.Z.
 00000c00: 6503 6504 1900 6401 9c01 6402 6403 8404  e.e...d...d.d...
@@ -650,15 +650,15 @@
 00002890: 6e74 2076 616c 7565 7320 6173 2064 6174  nt values as dat
 000028a0: 6520 6c69 7374 2e0a 2020 2020 6301 0000  e list..    c...
 000028b0: 0000 0000 0000 0000 0002 0000 0005 0000  ................
 000028c0: 0053 0000 0073 2c00 0000 6700 7c00 5d24  .S...s,...g.|.]$
 000028d0: 7d01 7c01 6a00 6400 6b09 7204 7c01 6a01  }.|.j.d.k.r.|.j.
 000028e0: 6401 6b02 7204 7402 a003 7c01 6a00 a101  d.k.r.t...|.j...
 000028f0: 9102 7104 5300 2902 4e72 5c00 0000 2904  ..q.S.).Nr\...).
-00002900: 7234 0000 0072 5e00 0000 7206 0000 00da  r4...r^...r.....
+00002900: 7234 0000 0072 5e00 0000 7204 0000 00da  r4...r^...r.....
 00002910: 0d66 726f 6d69 736f 666f 726d 6174 725f  .fromisoformatr_
 00002920: 0000 0072 2100 0000 7221 0000 0072 2200  ...r!...r!...r".
 00002930: 0000 7260 0000 00ca 0100 0073 0800 0000  ..r`.......s....
 00002940: 0602 0201 0a00 0afe 7a32 6765 745f 656c  ........z2get_el
 00002950: 656d 656e 745f 7661 6c75 655f 6173 5f64  ement_value_as_d
 00002960: 6174 655f 6c69 7374 2e3c 6c6f 6361 6c73  ate_list.<locals
 00002970: 3e2e 3c6c 6973 7463 6f6d 703e 7261 0000  >.<listcomp>ra..
@@ -908,25 +908,25 @@
 000038b0: 0000 4300 0000 7354 0000 0074 007c 0074  ..C...sT...t.|.t
 000038c0: 0174 0274 0366 0383 0272 167c 007d 006e  .t.t.f...r.|.}.n
 000038d0: 3a74 007c 0074 0483 0272 2a7c 00a0 05a1  :t.|.t...r*|....
 000038e0: 007d 006e 2674 007c 0074 0674 0774 0866  .}.n&t.|.t.t.t.f
 000038f0: 0383 0272 407c 007d 006e 1074 0964 017c  ...r@|.}.n.t.d.|
 00003900: 006a 0a9b 009d 0283 0182 017c 0053 0029  .j.........|.S.)
 00003910: 024e 7235 0000 0029 0b72 3600 0000 7237  .Nr5...).r6...r7
-00003920: 0000 0072 3800 0000 7239 0000 0072 0600  ...r8...r9...r..
+00003920: 0000 0072 3800 0000 7239 0000 0072 0400  ...r8...r9...r..
 00003930: 0000 da09 6973 6f66 6f72 6d61 7472 3e00  ....isoformatr>.
 00003940: 0000 7211 0000 0072 1500 0000 723a 0000  ..r....r....r:..
 00003950: 0072 3b00 0000 2901 7229 0000 0072 2100  .r;...).r)...r!.
 00003960: 0000 7221 0000 0072 2200 0000 7276 0000  ..r!...r"...rv..
 00003970: 0084 0200 0073 1000 0000 0001 1001 0601  .....s..........
 00003980: 0a01 0a01 1001 0602 1002 7276 0000 0029  ..........rv...)
 00003990: 014e 2901 4e29 014e 2901 4e29 014e 2945  .N).N).N).N).N)E
-000039a0: da06 7479 7069 6e67 7202 0000 0072 0300  ..typingr....r..
-000039b0: 0000 7204 0000 0072 0500 0000 da08 6461  ..r....r......da
-000039c0: 7465 7469 6d65 7206 0000 00da 0361 6263  tetimer......abc
+000039a0: da03 6162 6372 0200 0000 7203 0000 00da  ..abcr....r.....
+000039b0: 0864 6174 6574 696d 6572 0400 0000 da06  .datetimer......
+000039c0: 7479 7069 6e67 7205 0000 0072 0600 0000  typingr....r....
 000039d0: 7207 0000 0072 0800 0000 da06 6d6f 6465  r....r......mode
 000039e0: 6c73 720a 0000 0072 0b00 0000 720c 0000  lsr....r....r...
 000039f0: 0072 0d00 0000 720e 0000 0072 0f00 0000  .r....r....r....
 00003a00: 7210 0000 0072 1100 0000 7212 0000 0072  r....r....r....r
 00003a10: 1300 0000 7214 0000 0072 1500 0000 7216  ....r....r....r.
 00003a20: 0000 0072 1700 0000 7218 0000 005a 1850  ...r....r....Z.P
 00003a30: 726f 6365 7373 456c 656d 656e 7456 616c  rocessElementVal
@@ -945,15 +945,15 @@
 00003b00: 0000 0072 6400 0000 7266 0000 0072 6500  ...rd...rf...re.
 00003b10: 0000 7267 0000 0072 3e00 0000 726a 0000  ..rg...r>...rj..
 00003b20: 0072 6900 0000 726b 0000 0072 6f00 0000  .ri...rk...ro...
 00003b30: 726e 0000 0072 7000 0000 7273 0000 0072  rn...rp...rs...r
 00003b40: 7200 0000 7274 0000 0072 5000 0000 7276  r...rt...rP...rv
 00003b50: 0000 0072 2100 0000 7221 0000 0072 2100  ...r!...r!...r!.
 00003b60: 0000 7222 0000 00da 083c 6d6f 6475 6c65  ..r".....<module
-00003b70: 3e1a 0000 0073 ae00 0000 1801 0c01 1002  >....s..........
+00003b70: 3e1a 0000 0073 ae00 0000 1001 0c01 1802  >....s..........
 00003b80: 4412 0c01 0201 0201 0201 0201 0201 02fc  D...............
 00003b90: 02ff 0408 0201 0201 0201 0201 0201 0201  ................
 00003ba0: 0201 02fa 02ff 040a 1001 0c02 0201 1aff  ................
 00003bb0: 0405 100e 1018 1027 100d 1212 1613 0200  .......'........
 00003bc0: 0600 0201 02fe 0c18 00ff 0201 0200 0601  ................
 00003bd0: 02fe 0c11 00ff 0201 0200 0a01 02fe 0c14  ................
 00003be0: 00ff 0201 0200 0601 02fe 0c12 00fe 0201  ................
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/__pycache__/json_forms.cpython-38.pyc` & `kuflow_rest-0.8.0/kuflow_rest/utils/__pycache__/json_forms.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 23991 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,68 +1,68 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 b75d 0000  U.......=S.d.]..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 b75d 0000  U..........d.]..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0008 0000 0040 0000 0073 4403 0000 6400  .....@...sD...d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 6d04 5a04 6d05 5a05 0100 6400 6402 6c06  m.Z.m.Z...d.d.l.
-00000050: 6d07 5a07 6d06 5a06 0100 6400 6403 6c08  m.Z.m.Z...d.d.l.
-00000060: 5a08 6400 6403 6c09 5a09 6400 6404 6c0a  Z.d.d.l.Z.d.d.l.
+00000030: 6401 6c00 5a00 6400 6401 6c01 5a01 6400  d.l.Z.d.d.l.Z.d.
+00000040: 6402 6c02 6d03 5a03 6d04 5a04 0100 6400  d.l.m.Z.m.Z...d.
+00000050: 6403 6c05 6d06 5a06 6d05 5a05 0100 6400  d.l.m.Z.m.Z...d.
+00000060: 6404 6c07 6d08 5a08 6d09 5a09 6d0a 5a0a  d.l.m.Z.m.Z.m.Z.
 00000070: 6d0b 5a0b 6d0c 5a0c 0100 6405 6406 6c0d  m.Z.m.Z...d.d.l.
 00000080: 6d0e 5a0e 6d0f 5a0f 6d10 5a10 6d11 5a11  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d12 5a12 6d13 5a13 0100 6502 6514 6515  m.Z.m.Z...e.e.e.
-000000a0: 6516 6517 6507 650f 650e 6607 1900 5a18  e.e.e.e.e.f...Z.
-000000b0: 6503 6407 1900 5a19 6504 6514 6407 6602  e.d...Z.e.e.d.f.
-000000c0: 1900 5a1a 6502 6519 651a 6602 1900 5a1b  ..Z.e.e.e.f...Z.
-000000d0: 6502 6518 651b 6602 1900 5a1c 6502 6511  e.e.e.f...Z.e.e.
+00000090: 6d12 5a12 6d13 5a13 0100 650c 6514 6515  m.Z.m.Z...e.e.e.
+000000a0: 6516 6517 6506 650f 650e 6607 1900 5a18  e.e.e.e.e.f...Z.
+000000b0: 650a 6407 1900 5a19 6509 6514 6407 6602  e.d...Z.e.e.d.f.
+000000c0: 1900 5a1a 650c 6519 651a 6602 1900 5a1b  ..Z.e.e.e.f...Z.
+000000d0: 650c 6518 651b 6602 1900 5a1c 650c 6511  e.e.e.f...Z.e.e.
 000000e0: 6512 6513 6603 1900 5a1d 4700 6408 6409  e.e.f...Z.G.d.d.
-000000f0: 8400 6409 650b 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
+000000f0: 8400 6409 6503 8303 5a1e 4700 640a 640b  ..d.e...Z.G.d.d.
 00000100: 8400 640b 8302 5a1f 651e 6514 6514 640c  ..d...Z.e.e.e.d.
-00000110: 9c03 640d 640e 8404 5a20 651e 6514 6505  ..d.d...Z e.e.e.
+00000110: 9c03 640d 640e 8404 5a20 651e 6514 650b  ..d.d...Z e.e.e.
 00000120: 6514 1900 640c 9c03 640f 6410 8404 5a21  e...d...d.d...Z!
 00000130: 651e 6514 6515 640c 9c03 6411 6412 8404  e.e.e.d...d.d...
-00000140: 5a22 651e 6514 6505 6515 1900 640c 9c03  Z"e.e.e.e...d...
+00000140: 5a22 651e 6514 650b 6515 1900 640c 9c03  Z"e.e.e.e...d...
 00000150: 6413 6414 8404 5a23 651e 6514 6516 640c  d.d...Z#e.e.e.d.
-00000160: 9c03 6415 6416 8404 5a24 651e 6514 6505  ..d.d...Z$e.e.e.
+00000160: 9c03 6415 6416 8404 5a24 651e 6514 650b  ..d.d...Z$e.e.e.
 00000170: 6516 1900 640c 9c03 6417 6418 8404 5a25  e...d...d.d...Z%
-00000180: 651e 6514 6507 640c 9c03 6419 641a 8404  e.e.e.d...d.d...
-00000190: 5a26 651e 6514 6505 6507 1900 640c 9c03  Z&e.e.e.e...d...
-000001a0: 641b 641c 8404 5a27 651e 6514 6506 640c  d.d...Z'e.e.e.d.
-000001b0: 9c03 641d 641e 8404 5a28 651e 6514 6505  ..d.d...Z(e.e.e.
-000001c0: 6506 1900 640c 9c03 641f 6420 8404 5a29  e...d...d.d ..Z)
+00000180: 651e 6514 6506 640c 9c03 6419 641a 8404  e.e.e.d...d.d...
+00000190: 5a26 651e 6514 650b 6506 1900 640c 9c03  Z&e.e.e.e...d...
+000001a0: 641b 641c 8404 5a27 651e 6514 6505 640c  d.d...Z'e.e.e.d.
+000001b0: 9c03 641d 641e 8404 5a28 651e 6514 650b  ..d.d...Z(e.e.e.
+000001c0: 6505 1900 640c 9c03 641f 6420 8404 5a29  e...d...d.d ..Z)
 000001d0: 651e 6514 650e 640c 9c03 6421 6422 8404  e.e.e.d...d!d"..
-000001e0: 5a2a 651e 6514 6505 650e 1900 640c 9c03  Z*e.e.e.e...d...
+000001e0: 5a2a 651e 6514 650b 650e 1900 640c 9c03  Z*e.e.e.e...d...
 000001f0: 6423 6424 8404 5a2b 651e 6514 650f 640c  d#d$..Z+e.e.e.d.
-00000200: 9c03 6425 6426 8404 5a2c 651e 6514 6505  ..d%d&..Z,e.e.e.
+00000200: 9c03 6425 6426 8404 5a2c 651e 6514 650b  ..d%d&..Z,e.e.e.
 00000210: 650f 1900 640c 9c03 6427 6428 8404 5a2d  e...d...d'd(..Z-
 00000220: 651e 6514 652e 640c 9c03 6429 642a 8404  e.e.e.d...d)d*..
-00000230: 5a2f 651e 6514 6505 652e 1900 640c 9c03  Z/e.e.e.e...d...
+00000230: 5a2f 651e 6514 650b 652e 1900 640c 9c03  Z/e.e.e.e...d...
 00000240: 642b 642c 8404 5a30 651e 6514 6531 640c  d+d,..Z0e.e.e1d.
-00000250: 9c03 642d 642e 8404 5a32 651e 6514 6505  ..d-d...Z2e.e.e.
+00000250: 9c03 642d 642e 8404 5a32 651e 6514 650b  ..d-d...Z2e.e.e.
 00000260: 6531 1900 640c 9c03 642f 6430 8404 5a33  e1..d...d/d0..Z3
-00000270: 6451 651e 6514 6517 6505 651c 1900 6432  dQe.e.e.e.e...d2
-00000280: 9c04 6433 6434 8405 5a34 651e 6514 6505  ..d3d4..Z4e.e.e.
-00000290: 6518 1900 6403 6435 9c04 6436 6437 8404  e...d.d5..d6d7..
-000002a0: 5a35 6452 651e 6514 6517 6505 651f 1900  Z5dRe.e.e.e.e...
-000002b0: 6432 9c04 6439 643a 8405 5a36 6505 6518  d2..d9d:..Z6e.e.
-000002c0: 1900 6505 6518 1900 643b 9c02 643c 643d  ..e.e...d;..d<d=
+00000270: 6451 651e 6514 6517 650b 651c 1900 6432  dQe.e.e.e.e...d2
+00000280: 9c04 6433 6434 8405 5a34 651e 6514 650b  ..d3d4..Z4e.e.e.
+00000290: 6518 1900 6401 6435 9c04 6436 6437 8404  e...d.d5..d6d7..
+000002a0: 5a35 6452 651e 6514 6517 650b 651f 1900  Z5dRe.e.e.e.e...
+000002b0: 6432 9c04 6439 643a 8405 5a36 650b 6518  d2..d9d:..Z6e.e.
+000002c0: 1900 650b 6518 1900 643b 9c02 643c 643d  ..e.e...d;..d<d=
 000002d0: 8404 5a37 650f 6514 643e 9c02 643f 6440  ..Z7e.e.d>..d?d@
 000002e0: 8404 5a38 650e 6514 6441 9c02 6442 6443  ..Z8e.e.dA..dBdC
-000002f0: 8404 5a39 651c 6505 650e 1900 643b 9c02  ..Z9e.e.e...d;..
-00000300: 6444 6445 8404 5a3a 651c 6505 650f 1900  dDdE..Z:e.e.e...
-00000310: 643b 9c02 6446 6447 8404 5a3b 6505 651c  d;..dFdG..Z;e.e.
+000002f0: 8404 5a39 651c 650b 650e 1900 643b 9c02  ..Z9e.e.e...d;..
+00000300: 6444 6445 8404 5a3a 651c 650b 650f 1900  dDdE..Z:e.e.e...
+00000310: 643b 9c02 6446 6447 8404 5a3b 650b 651c  d;..dFdG..Z;e.e.
 00000320: 1900 6517 643b 9c02 6448 6449 8404 5a3c  ..e.d;..dHdI..Z<
-00000330: 6505 651c 1900 6517 643b 9c02 644a 644b  e.e...e.d;..dJdK
-00000340: 8404 5a3d 6505 651c 1900 6517 643b 9c02  ..Z=e.e...e.d;..
-00000350: 644c 644d 8404 5a3e 651e 6517 6505 651b  dLdM..Z>e.e.e.e.
-00000360: 1900 644e 9c03 644f 6450 8404 5a3f 6403  ..dN..dOdP..Z?d.
-00000370: 5300 2953 e900 0000 0029 05da 0341 6e79  S.)S.....)...Any
-00000380: da05 556e 696f 6eda 044c 6973 74da 0444  ..Union..List..D
-00000390: 6963 74da 084f 7074 696f 6e61 6c29 02da  ict..Optional)..
-000003a0: 0464 6174 65da 0864 6174 6574 696d 654e  .date..datetimeN
-000003b0: 2902 da03 4142 43da 0e61 6273 7472 6163  )...ABC..abstrac
-000003c0: 746d 6574 686f 64e9 0200 0000 2906 da0d  tmethod.....)...
+00000330: 650b 651c 1900 6517 643b 9c02 644a 644b  e.e...e.d;..dJdK
+00000340: 8404 5a3d 650b 651c 1900 6517 643b 9c02  ..Z=e.e...e.d;..
+00000350: 644c 644d 8404 5a3e 651e 6517 650b 651b  dLdM..Z>e.e.e.e.
+00000360: 1900 644e 9c03 644f 6450 8404 5a3f 6401  ..dN..dOdP..Z?d.
+00000370: 5300 2953 e900 0000 004e 2902 da03 4142  S.)S.....N)...AB
+00000380: 43da 0e61 6273 7472 6163 746d 6574 686f  C..abstractmetho
+00000390: 6429 02da 0464 6174 65da 0864 6174 6574  d)...date..datet
+000003a0: 696d 6529 05da 0341 6e79 da04 4469 6374  ime)...Any..Dict
+000003b0: da04 4c69 7374 da08 4f70 7469 6f6e 616c  ..List..Optional
+000003c0: da05 556e 696f 6ee9 0200 0000 2906 da0d  ..Union.....)...
 000003d0: 4a73 6f6e 466f 726d 7346 696c 65da 124a  JsonFormsFile..J
 000003e0: 736f 6e46 6f72 6d73 5072 696e 6369 7061  sonFormsPrincipa
 000003f0: 6cda 0d50 7269 6e63 6970 616c 5479 7065  l..PrincipalType
 00000400: da04 5461 736b da0c 5461 736b 5061 6765  ..Task..TaskPage
 00000410: 4974 656d da21 5461 736b 5361 7665 4a73  Item.!TaskSaveJs
 00000420: 6f6e 466f 726d 7356 616c 7565 4461 7461  onFormsValueData
 00000430: 436f 6d6d 616e 64da 0b43 6f6d 706c 6578  Command..Complex
@@ -94,16 +94,16 @@
 000005d0: 0000 0072 1c00 0000 7219 0000 0072 1900  ...r....r....r..
 000005e0: 0000 721a 0000 00da 0873 6574 5f64 6174  ..r......set_dat
 000005f0: 613b 0000 0073 0200 0000 0002 7a1d 4a73  a;...s......z.Js
 00000600: 6f6e 466f 726d 4461 7461 4163 6365 7373  onFormDataAccess
 00000610: 6f72 2e73 6574 5f64 6174 614e 290a da08  or.set_dataN)...
 00000620: 5f5f 6e61 6d65 5f5f da0a 5f5f 6d6f 6475  __name__..__modu
 00000630: 6c65 5f5f da0c 5f5f 7175 616c 6e61 6d65  le__..__qualname
-00000640: 5f5f 720a 0000 0072 0600 0000 7205 0000  __r....r....r...
-00000650: 00da 0373 7472 7202 0000 0072 1b00 0000  ...strr....r....
+00000640: 5f5f 7203 0000 0072 0900 0000 7207 0000  __r....r....r...
+00000650: 00da 0373 7472 7206 0000 0072 1b00 0000  ...strr....r....
 00000660: 721d 0000 0072 1900 0000 7219 0000 0072  r....r....r....r
 00000670: 1900 0000 721a 0000 0072 1300 0000 3600  ....r....r....6.
 00000680: 0000 7308 0000 0008 0102 011c 0302 0172  ..s............r
 00000690: 1300 0000 6300 0000 0000 0000 0000 0000  ....c...........
 000006a0: 0000 0000 0004 0000 0040 0000 0073 3800  .........@...s8.
 000006b0: 0000 6500 5a01 6400 5a02 5500 6503 6504  ..e.Z.d.Z.U.e.e.
 000006c0: 6401 3c00 6505 6504 6402 3c00 6506 6504  d.<.e.e.d.<.e.e.
@@ -410,15 +410,15 @@
 00001990: 733a 0a20 2020 2020 2020 2056 616c 7565  s:.        Value
 000019a0: 4572 726f 723a 2049 6620 7072 6f70 6572  Error: If proper
 000019b0: 7479 2076 616c 7565 2068 6173 2069 6e63  ty value has inc
 000019c0: 6f72 7265 6374 2066 6f72 6d61 740a 2020  orrect format.  
 000019d0: 2020 4e72 3400 0000 7a28 2069 7320 6e6f    Nr4...z( is no
 000019e0: 7420 6120 6461 7465 2066 6f6c 6c6f 7769  t a date followi
 000019f0: 6e67 2049 534f 2038 3630 3120 666f 726d  ng ISO 8601 form
-00001a00: 6174 2906 7231 0000 0072 3500 0000 7207  at).r1...r5...r.
+00001a00: 6174 2906 7231 0000 0072 3500 0000 7204  at).r1...r5...r.
 00001a10: 0000 0072 2100 0000 da0d 6672 6f6d 6973  ...r!.....fromis
 00001a20: 6f66 6f72 6d61 7472 2e00 0000 722f 0000  oformatr....r/..
 00001a30: 0072 1900 0000 7219 0000 0072 1a00 0000  .r....r....r....
 00001a40: 723c 0000 00f1 0000 0073 1600 0000 000e  r<.......s......
 00001a50: 0a01 0801 0402 0a01 0402 0a01 0201 0c01  ................
 00001a60: 0e01 0602 723c 0000 0063 0200 0000 0000  ....r<...c......
 00001a70: 0000 0000 0000 0300 0000 0300 0000 4300  ..............C.
@@ -485,15 +485,15 @@
 00001e40: 2020 2020 2056 616c 7565 4572 726f 723a       ValueError:
 00001e50: 2049 6620 7072 6f70 6572 7479 2076 616c   If property val
 00001e60: 7565 2068 6173 2069 6e63 6f72 7265 6374  ue has incorrect
 00001e70: 2066 6f72 6d61 740a 2020 2020 4e72 3400   format.    Nr4.
 00001e80: 0000 7a2d 2069 7320 6e6f 7420 6120 6461  ..z- is not a da
 00001e90: 7465 2d74 696d 6520 666f 6c6c 6f77 696e  te-time followin
 00001ea0: 6720 4953 4f20 3836 3031 2066 6f72 6d61  g ISO 8601 forma
-00001eb0: 7429 0672 3100 0000 7235 0000 0072 0800  t).r1...r5...r..
+00001eb0: 7429 0672 3100 0000 7235 0000 0072 0500  t).r1...r5...r..
 00001ec0: 0000 7221 0000 0072 3e00 0000 722e 0000  ..r!...r>...r...
 00001ed0: 0072 2f00 0000 7219 0000 0072 1900 0000  .r/...r....r....
 00001ee0: 721a 0000 0072 3f00 0000 2301 0000 7316  r....r?...#...s.
 00001ef0: 0000 0000 0e0a 0108 0104 020a 0104 020a  ................
 00001f00: 0102 010c 010e 0106 0272 3f00 0000 6302  .........r?...c.
 00001f10: 0000 0000 0000 0000 0000 0003 0000 0003  ................
 00001f20: 0000 0043 0000 0073 1e00 0000 7400 7c00  ...C...s....t.|.
@@ -948,16 +948,16 @@
 00003b30: 0182 0164 0053 0029 024e 7a12 556e 7375  ...d.S.).Nz.Unsu
 00003b40: 7070 6f72 7465 6420 7661 6c75 6520 290d  pported value ).
 00003b50: 7235 0000 0072 0d00 0000 da27 6765 6e65  r5...r.....'gene
 00003b60: 7261 7465 5f76 616c 7565 5f66 6f72 5f6a  rate_value_for_j
 00003b70: 736f 6e5f 666f 726d 735f 7072 696e 6369  son_forms_princi
 00003b80: 7061 6c72 0c00 0000 da22 6765 6e65 7261  palr....."genera
 00003b90: 7465 5f76 616c 7565 5f66 6f72 5f6a 736f  te_value_for_jso
-00003ba0: 6e5f 666f 726d 735f 6669 6c65 7207 0000  n_forms_filer...
-00003bb0: 00da 0969 736f 666f 726d 6174 7208 0000  ...isoformatr...
+00003ba0: 6e5f 666f 726d 735f 6669 6c65 7204 0000  n_forms_filer...
+00003bb0: 00da 0969 736f 666f 726d 6174 7205 0000  ...isoformatr...
 00003bc0: 0072 3600 0000 723b 0000 00da 0462 6f6f  .r6...r;.....boo
 00003bd0: 6c72 2100 0000 da09 4578 6365 7074 696f  lr!.....Exceptio
 00003be0: 6ea9 0172 2500 0000 7219 0000 0072 1900  n..r%...r....r..
 00003bf0: 0000 721a 0000 0072 5100 0000 7e02 0000  ..r....rQ...~...
 00003c00: 731a 0000 0000 0108 0104 010a 0108 010a  s...............
 00003c10: 0108 010a 0108 010a 0108 0112 0104 0272  ...............r
 00003c20: 5100 0000 2902 da09 7072 696e 6369 7061  Q...)...principa
@@ -1074,19 +1074,19 @@
 00004310: 0000 7c00 a000 a100 7d02 7c02 6400 6b08  ..|.....}.|.d.k.
 00004320: 7222 7c01 7222 6900 7d02 7c00 a001 7c02  r"|.r"i.}.|...|.
 00004330: a101 0100 7c02 5300 7215 0000 0029 0272  ....|.S.r....).r
 00004340: 1b00 0000 721d 0000 0029 0372 2a00 0000  ....r....).r*...
 00004350: 724e 0000 0072 1c00 0000 7219 0000 0072  rN...r....r....r
 00004360: 1900 0000 721a 0000 0072 5900 0000 f102  ....r....rY.....
 00004370: 0000 730a 0000 0000 0108 020c 0104 010a  ..s.............
-00004380: 0272 5900 0000 2901 5429 0146 2940 da06  .rY...).T).F)@..
-00004390: 7479 7069 6e67 7202 0000 0072 0300 0000  typingr....r....
-000043a0: 7204 0000 0072 0500 0000 7206 0000 0072  r....r....r....r
-000043b0: 0800 0000 7207 0000 0072 3700 0000 727a  ....r....r7...rz
-000043c0: 0000 00da 0361 6263 7209 0000 0072 0a00  .....abcr....r..
+00004380: 0272 5900 0000 2901 5429 0146 2940 7237  .rY...).T).F)@r7
+00004390: 0000 0072 7a00 0000 da03 6162 6372 0200  ...rz.....abcr..
+000043a0: 0000 7203 0000 0072 0500 0000 7204 0000  ..r....r....r...
+000043b0: 00da 0674 7970 696e 6772 0600 0000 7207  ...typingr....r.
+000043c0: 0000 0072 0800 0000 7209 0000 0072 0a00  ...r....r....r..
 000043d0: 0000 da06 6d6f 6465 6c73 720c 0000 0072  ....modelsr....r
 000043e0: 0d00 0000 720e 0000 0072 0f00 0000 7210  ....r....r....r.
 000043f0: 0000 0072 1100 0000 7221 0000 0072 3600  ...r....r!...r6.
 00004400: 0000 723b 0000 0072 6700 0000 da13 4a73  ..r;...rg.....Js
 00004410: 6f6e 466f 726d 7353 696d 706c 6554 7970  onFormsSimpleTyp
 00004420: 655a 1243 6f6e 7461 696e 6572 4172 7261  eZ.ContainerArra
 00004430: 7954 7970 655a 1343 6f6e 7461 696e 6572  yTypeZ.Container
@@ -1101,15 +1101,15 @@
 000044c0: 4800 0000 724d 0000 0072 4c00 0000 724b  H...rM...rL...rK
 000044d0: 0000 0072 3100 0000 7254 0000 0072 4f00  ...r1...rT...rO.
 000044e0: 0000 7251 0000 0072 6400 0000 7265 0000  ..rQ...rd...re..
 000044f0: 0072 4300 0000 7247 0000 0072 6100 0000  .rC...rG...ra...
 00004500: 725e 0000 0072 5c00 0000 7259 0000 0072  r^...r\...rY...r
 00004510: 1900 0000 7219 0000 0072 1900 0000 721a  ....r....r....r.
 00004520: 0000 00da 083c 6d6f 6475 6c65 3e1a 0000  .....<module>...
-00004530: 0073 8800 0000 1c01 1001 0801 0801 1002  .s..............
+00004530: 0073 8800 0000 0801 0801 1001 1001 1c02  .s..............
 00004540: 2009 1602 0802 0c02 0c02 0c02 0e03 100a   ...............
 00004550: 0e0b 1214 1614 1214 161f 1214 1623 1214  .............#..
 00004560: 161e 1214 161e 1215 0200 0201 06fe 0c1c  ................
 00004570: 0200 0201 02fe 0c17 0200 0201 06fe 0c1b  ................
 00004580: 1214 1618 1214 1619 00ff 0201 0200 0200  ................
 00004590: 0201 06fe 0c0a 0200 0200 0601 02fe 0c2b  ...............+
 000045a0: 00ff 0201 0200 0200 0201 06fe 0c52 1811  .............R..
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_process_page_item_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_process_page_item_utils.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,19 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
+from .._generated.models import ProcessElementValue
+from ..models import ProcessPageItem
 from .element_values import (
     ElementValueSimpleType,
     ElementValueUnion,
     ProcessElementValueAccessor,
     add_element_value,
     add_element_value_list,
     find_element_value_as_date,
@@ -44,16 +46,14 @@
     get_element_value_valid,
     get_element_value_valid_at,
     set_element_value,
     set_element_value_list,
     set_element_value_valid,
     set_element_value_valid_at,
 )
-from .._generated.models import ProcessElementValue
-from ..models import ProcessPageItem
 
 
 class CurrentElementValueAccessor(ProcessElementValueAccessor):
     def __init__(self, process_page_item: ProcessPageItem, element_definition_code: str):
         self.process_page_item = process_page_item
         self.element_definition_code = element_definition_code
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_process_save_element_command_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_process_save_element_command_utils.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,19 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
+from .._generated.models import ProcessElementValue
+from ..models import ProcessSaveElementCommand
 from .element_values import (
     ElementValueSimpleType,
     ElementValueUnion,
     ProcessElementValueAccessor,
     add_element_value,
     add_element_value_list,
     find_element_value_as_date,
@@ -44,16 +46,14 @@
     get_element_value_valid,
     get_element_value_valid_at,
     set_element_value,
     set_element_value_list,
     set_element_value_valid,
     set_element_value_valid_at,
 )
-from .._generated.models import ProcessElementValue
-from ..models import ProcessSaveElementCommand
 
 
 class CurrentElementValueAccessor(ProcessElementValueAccessor):
     def __init__(self, process_save_element_command: ProcessSaveElementCommand):
         self.process_save_element_command = process_save_element_command
 
     def set_element_values(self, element_values: List[ElementValueUnion]):
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_process_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_process_utils.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,19 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
+from .._generated.models import ProcessElementValue
+from ..models import Process
 from .element_values import (
     ElementValueSimpleType,
     ElementValueUnion,
     ProcessElementValueAccessor,
     add_element_value,
     add_element_value_list,
     find_element_value_as_date,
@@ -44,16 +46,14 @@
     get_element_value_valid,
     get_element_value_valid_at,
     set_element_value,
     set_element_value_list,
     set_element_value_valid,
     set_element_value_valid_at,
 )
-from .._generated.models import ProcessElementValue
-from ..models import Process
 
 
 class CurrentElementValueAccessor(ProcessElementValueAccessor):
     def __init__(self, process: Process, element_definition_code: str):
         self.process = process
         self.element_definition_code = element_definition_code
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_task_page_item_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_task_page_item_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,19 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
+from .._generated.models import TaskElementValue
+from ..models import TaskElementValueDocumentItem, TaskElementValuePrincipalItem, TaskPageItem
 from .element_values import (
     ElementValueSimpleType,
     ElementValueUnion,
     TaskElementValueAccessor,
     add_element_value,
     add_element_value_list,
     find_element_value_as_date,
@@ -53,20 +55,14 @@
     get_element_value_valid,
     get_element_value_valid_at,
     set_element_value,
     set_element_value_list,
     set_element_value_valid,
     set_element_value_valid_at,
 )
-from .._generated.models import TaskElementValue
-from ..models import (
-    TaskElementValueDocumentItem,
-    TaskElementValuePrincipalItem,
-    TaskPageItem,
-)
 
 
 class CurrentElementValueAccessor(TaskElementValueAccessor):
     def __init__(self, task_page_item: TaskPageItem, element_definition_code: str):
         self.task_page_item = task_page_item
         self.element_definition_code = element_definition_code
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_task_save_element_command_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_task_save_element_command_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,17 +19,19 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
+from .._generated.models import TaskElementValue
+from ..models import TaskElementValueDocumentItem, TaskElementValuePrincipalItem, TaskSaveElementCommand
 from .element_values import (
     ElementValueSimpleType,
     ElementValueUnion,
     TaskElementValueAccessor,
     add_element_value,
     add_element_value_list,
     find_element_value_as_date,
@@ -53,20 +55,14 @@
     get_element_value_valid,
     get_element_value_valid_at,
     set_element_value,
     set_element_value_list,
     set_element_value_valid,
     set_element_value_valid_at,
 )
-from .._generated.models import TaskElementValue
-from ..models import (
-    TaskElementValueDocumentItem,
-    TaskElementValuePrincipalItem,
-    TaskSaveElementCommand,
-)
 
 
 class CurrentElementValueAccessor(TaskElementValueAccessor):
     def __init__(self, task_save_element_command: TaskSaveElementCommand):
         self.task_save_element_command = task_save_element_command
 
     def set_element_values(self, element_values: List[ElementValueUnion]):
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_task_save_json_forms_value_data_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_task_save_json_forms_value_data_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,18 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import Any, Dict, Optional
 from datetime import date, datetime
+from typing import Any, Dict, Optional
 
+from ..models import JsonFormsFile, JsonFormsPrincipal, TaskSaveJsonFormsValueDataCommand
 from .json_forms import (
     JsonFormDataAccessor,
     JsonFormsSimpleType,
     find_json_forms_property_as_date,
     find_json_forms_property_as_datetime,
     find_json_forms_property_as_dict,
     find_json_forms_property_as_float,
@@ -45,19 +46,14 @@
     get_json_forms_property_as_int,
     get_json_forms_property_as_json_forms_file,
     get_json_forms_property_as_json_forms_principal,
     get_json_forms_property_as_list,
     get_json_forms_property_as_str,
     update_json_forms_property,
 )
-from ..models import (
-    JsonFormsFile,
-    JsonFormsPrincipal,
-    TaskSaveJsonFormsValueDataCommand,
-)
 
 
 class CurrentJsonFormDataAccessor(JsonFormDataAccessor):
     def __init__(self, command: TaskSaveJsonFormsValueDataCommand):
         self.command = command
 
     def get_data(self) -> Optional[Dict[str, Any]]:
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/_task_utils.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/_task_utils.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,26 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import Any, Dict, List, Optional
 from datetime import date, datetime
+from typing import Any, Dict, List, Optional
 
+from .._generated.models import TaskElementValue
+from ..models import (
+    JsonFormsFile,
+    JsonFormsPrincipal,
+    JsonFormsValue,
+    Task,
+    TaskElementValueDocumentItem,
+    TaskElementValuePrincipalItem,
+)
 from .element_values import (
     ElementValueSimpleType,
     ElementValueUnion,
     TaskElementValueAccessor,
     add_element_value,
     add_element_value_list,
     find_element_value_as_date,
@@ -76,23 +85,14 @@
     get_json_forms_property_as_int,
     get_json_forms_property_as_json_forms_file,
     get_json_forms_property_as_json_forms_principal,
     get_json_forms_property_as_list,
     get_json_forms_property_as_str,
     update_json_forms_property,
 )
-from .._generated.models import TaskElementValue
-from ..models import (
-    JsonFormsFile,
-    JsonFormsPrincipal,
-    JsonFormsValue,
-    Task,
-    TaskElementValueDocumentItem,
-    TaskElementValuePrincipalItem,
-)
 
 
 class CurrentElementValueAccessor(TaskElementValueAccessor):
     def __init__(self, task: Task, element_definition_code: str):
         self.task = task
         self.element_definition_code = element_definition_code
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/element_values.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/element_values.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,17 +19,17 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import Union, List, Dict, Optional
-from datetime import date
 from abc import ABC, abstractmethod
+from datetime import date
+from typing import Dict, List, Optional, Union
 
 from ..models import (
     Process,
     ProcessElementValueNumber,
     ProcessElementValueString,
     ProcessPageItem,
     ProcessSaveElementCommand,
```

### Comparing `kuflow_rest-0.7.1/kuflow_rest/utils/json_forms.py` & `kuflow_rest-0.8.0/kuflow_rest/utils/json_forms.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,19 +19,19 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import Any, Union, List, Dict, Optional
-from datetime import date, datetime
 import math
 import re
 from abc import ABC, abstractmethod
+from datetime import date, datetime
+from typing import Any, Dict, List, Optional, Union
 
 from ..models import (
     JsonFormsFile,
     JsonFormsPrincipal,
     PrincipalType,
     Task,
     TaskPageItem,
```

### Comparing `kuflow_rest-0.7.1/pyproject.toml` & `kuflow_rest-0.8.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "kuflow-rest"
-version = "0.7.1"
+version = "0.8.0"
 description = "Client for KuFlow Rest Api"
 license = "MIT"
 authors = ["KuFlow S.L. <kuflow@kuflow.com>"]
 homepage = "https://kuflow.com/"
 documentation = "https://docs.kuflow.com/"
 repository = "https://github.com/kuflow/kuflow-sdk-python"
 readme = "README.md"
```

### Comparing `kuflow_rest-0.7.1/setup.py` & `kuflow_rest-0.8.0/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 {'': ['*']}
 
 install_requires = \
 ['azure-core>=1.26.4,<2.0.0', 'isodate>=0.6.1,<0.7.0']
 
 setup_kwargs = {
     'name': 'kuflow-rest',
-    'version': '0.7.1',
+    'version': '0.8.0',
     'description': 'Client for KuFlow Rest Api',
     'long_description': '[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)\n[![Python](https://img.shields.io/pypi/pyversions/kuflow-rest.svg)](https://pypi.org/project/kuflow-rest)\n[![PyPI](https://img.shields.io/pypi/v/kuflow-rest.svg)](https://pypi.org/project/kuflow-rest)\n\n# KuFlow Rest\n\nThis is a client for the KuFlow API Rest that allows you to interact with our API in a comfortable way in the creation of your workers and tools.\n\n## Documentation\n\nMore detailed docs are available in the [documentation pages](https://docs.kuflow.com/developers/).\n\n## Contributing\n\nWe are happy to receive your help and comments, together we will dance a wonderful KuFlow. Please review our [contribution guide](CONTRIBUTING.md).\n\n## License\n\n[MIT License](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)\n',
     'author': 'KuFlow S.L.',
     'author_email': 'kuflow@kuflow.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'https://kuflow.com/',
```

### Comparing `kuflow_rest-0.7.1/PKG-INFO` & `kuflow_rest-0.8.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kuflow-rest
-Version: 0.7.1
+Version: 0.8.0
 Summary: Client for KuFlow Rest Api
 Home-page: https://kuflow.com/
 License: MIT
 Author: KuFlow S.L.
 Author-email: kuflow@kuflow.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: MIT License
```


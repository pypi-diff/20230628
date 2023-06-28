# Comparing `tmp/transaction_service_quality_checker-0.0.6.tar.gz` & `tmp/transaction_service_quality_checker-0.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "transaction_service_quality_checker-0.0.6.tar", last modified: Mon May 29 16:51:06 2023, max compression
+gzip compressed data, was "transaction_service_quality_checker-0.0.8.tar", last modified: Wed Jun 28 15:18:12 2023, max compression
```

## Comparing `transaction_service_quality_checker-0.0.6.tar` & `transaction_service_quality_checker-0.0.8.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-05-29 16:51:06.782478 transaction_service_quality_checker-0.0.6/
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      258 2023-05-29 16:51:06.781887 transaction_service_quality_checker-0.0.6/PKG-INFO
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1601 2023-05-10 16:34:46.000000 transaction_service_quality_checker-0.0.6/README.md
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)       38 2023-05-29 16:51:06.782685 transaction_service_quality_checker-0.0.6/setup.cfg
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      383 2023-05-29 16:51:01.000000 transaction_service_quality_checker-0.0.6/setup.py
-drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-05-29 16:51:06.766658 transaction_service_quality_checker-0.0.6/tests/
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-24 16:26:08.000000 transaction_service_quality_checker-0.0.6/tests/__init__.py
-drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-05-29 16:51:06.768389 transaction_service_quality_checker-0.0.6/tests/api/
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-24 16:26:10.000000 transaction_service_quality_checker-0.0.6/tests/api/__init__.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      960 2023-05-25 12:23:42.000000 transaction_service_quality_checker-0.0.6/tests/api/test_config_api_interface.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     2317 2023-05-25 12:26:21.000000 transaction_service_quality_checker-0.0.6/tests/api/test_transaction_api_interface.py
-drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-05-29 16:51:06.775375 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-25 12:19:38.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/__init__.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      513 2023-04-27 08:35:17.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/addresses_map.py
-drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-05-29 16:51:06.781059 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-24 16:25:46.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/__init__.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      425 2023-04-27 08:35:17.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/api_interface.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      651 2023-04-27 08:35:17.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/config_api_interface.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     2395 2023-05-10 10:11:34.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/etherscan_api_interface.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1828 2023-05-03 11:00:35.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/transaction_api_interface.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1374 2023-05-23 18:18:38.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/app.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      525 2023-05-08 10:47:32.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/app_block_creation.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     2494 2023-05-29 15:40:49.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/app_by_list.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1227 2023-05-29 16:50:32.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/block_creation.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)    13766 2023-05-29 16:42:03.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/comparer.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1948 2023-05-10 11:20:21.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/metrics.py
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     6320 2023-05-24 09:08:26.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/reindex_operator.py
-drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-05-29 16:51:06.777798 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker.egg-info/
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)      258 2023-05-29 16:51:06.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker.egg-info/PKG-INFO
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1144 2023-05-29 16:51:06.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker.egg-info/SOURCES.txt
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)        1 2023-05-29 16:51:06.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker.egg-info/dependency_links.txt
--rw-r--r--   0 joseramirezencinas   (501) staff       (20)       42 2023-05-29 16:51:06.000000 transaction_service_quality_checker-0.0.6/transaction_service_quality_checker.egg-info/top_level.txt
+drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-06-28 15:18:12.217212 transaction_service_quality_checker-0.0.8/
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      258 2023-06-28 15:18:12.216469 transaction_service_quality_checker-0.0.8/PKG-INFO
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1601 2023-05-10 16:34:46.000000 transaction_service_quality_checker-0.0.8/README.md
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)       38 2023-06-28 15:18:12.217441 transaction_service_quality_checker-0.0.8/setup.cfg
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      383 2023-06-28 14:58:17.000000 transaction_service_quality_checker-0.0.8/setup.py
+drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-06-28 15:18:12.198075 transaction_service_quality_checker-0.0.8/tests/
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-24 16:26:08.000000 transaction_service_quality_checker-0.0.8/tests/__init__.py
+drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-06-28 15:18:12.199536 transaction_service_quality_checker-0.0.8/tests/api/
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-24 16:26:10.000000 transaction_service_quality_checker-0.0.8/tests/api/__init__.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      960 2023-05-25 12:23:42.000000 transaction_service_quality_checker-0.0.8/tests/api/test_config_api_interface.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     2317 2023-05-25 12:26:21.000000 transaction_service_quality_checker-0.0.8/tests/api/test_transaction_api_interface.py
+drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-06-28 15:18:12.207002 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-25 12:19:38.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/__init__.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      513 2023-04-27 08:35:17.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/addresses_map.py
+drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-06-28 15:18:12.215157 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)        0 2023-05-24 16:25:46.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/__init__.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      425 2023-04-27 08:35:17.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/api_interface.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      651 2023-04-27 08:35:17.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/config_api_interface.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     3717 2023-06-28 12:53:28.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/etherscan_api_interface.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1828 2023-05-03 11:00:35.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/transaction_api_interface.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1374 2023-05-23 18:18:38.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/app.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      525 2023-05-08 10:47:32.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/app_block_creation.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     2494 2023-05-29 15:40:49.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/app_by_list.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1422 2023-05-31 18:44:42.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/block_creation.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)    15144 2023-06-28 15:16:46.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/comparer.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     2077 2023-06-28 14:59:32.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/metrics.py
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     6320 2023-05-24 09:08:26.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/reindex_operator.py
+drwxr-xr-x   0 joseramirezencinas   (501) staff       (20)        0 2023-06-28 15:18:12.209893 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker.egg-info/
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)      258 2023-06-28 15:18:12.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker.egg-info/PKG-INFO
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)     1144 2023-06-28 15:18:12.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker.egg-info/SOURCES.txt
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)        1 2023-06-28 15:18:12.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker.egg-info/dependency_links.txt
+-rw-r--r--   0 joseramirezencinas   (501) staff       (20)       42 2023-06-28 15:18:12.000000 transaction_service_quality_checker-0.0.8/transaction_service_quality_checker.egg-info/top_level.txt
```

### Comparing `transaction_service_quality_checker-0.0.6/README.md` & `transaction_service_quality_checker-0.0.8/README.md`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/tests/api/test_config_api_interface.py` & `transaction_service_quality_checker-0.0.8/tests/api/test_config_api_interface.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/tests/api/test_transaction_api_interface.py` & `transaction_service_quality_checker-0.0.8/tests/api/test_transaction_api_interface.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/addresses_map.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/addresses_map.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/config_api_interface.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/config_api_interface.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/api/transaction_api_interface.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/api/transaction_api_interface.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/app.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/app.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/app_block_creation.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/app_block_creation.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/app_by_list.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/app_by_list.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/block_creation.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/block_creation.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,15 +1,17 @@
 import logging
 from .api.etherscan_api_interface import EtherscanAPIInterface
 
+
 class BlockCreation:
 
-    def __init__(self, api_url:str, api_key: str, log: logging.Logger = logging):
+    def __init__(self, api_url: str, api_key: str, log: logging.Logger = logging):
         self.log = log
-        self.etherscan_api = EtherscanAPIInterface(api_key=api_key, domain=api_url)
+        self.etherscan_api = EtherscanAPIInterface(
+            api_key=api_key, domain=api_url)
 
     def get_safes_creation_block(self, map: dict):
         for key in map["chains"].keys():
             addresses = map["chains"][key]
             address_block_dict = self.etherscan_api.map_address_block_creation(
                 addresses)
             self.log.info(
@@ -18,13 +20,16 @@
     def get_safes_creation_block_from_list(self, addresses: list):
         addresses_block_dict = self.etherscan_api.map_address_block_creation(
             addresses)
         self.log.info(
             f"\n\nAddresses and Block Number Dictionary: \n\n{addresses_block_dict}")
         return addresses_block_dict
 
-
     def get_earliest_block_creation(self, address_block_dict: dict):
         # if len(address_block_dict) == 0 :
         #     return address_block_dict[0]
+        if not address_block_dict:
+            self.log.error(
+                f"Empty problematic addresses list")
+            raise ValueError('The provided dictionary is empty')
         earliest_key = list(address_block_dict.keys())[-1]
         return address_block_dict[earliest_key]
```

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/comparer.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/comparer.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,27 +1,30 @@
 import web3
 import logging
 import json
 from .api.config_api_interface import ConfigAPIinterface
 from .api.transaction_api_interface import TransactionAPIinterface
 from .metrics import Metrics
 from concurrent.futures import ThreadPoolExecutor, as_completed
+from threading import Lock
 
 
 class Comparer():
     def __init__(self, domain_a: str, domain_b: str, log: logging.Logger = logging,
-                 balance_in_usd_percentage_threshold: float = 0.03):
+                 balance_in_usd_percentage_threshold: float = 0.03,
+                 amount_transaction_comparison_tolerance_margin: float = 0.005):
         self.log = log
         self.domain_a = domain_a
         self.domain_b = domain_b
         self.config_svc_a = ConfigAPIinterface(domain=domain_a)
         self.config_svc_b = ConfigAPIinterface(domain=domain_b)
         self.metrics = Metrics()
         self.web3 = web3.Web3()
         self.balance_in_usd_percentage_threshold = balance_in_usd_percentage_threshold
+        self.lock = Lock()
 
     def fetch_transactions(self, tx_svc: TransactionAPIinterface, address: str) -> dict:
         return tx_svc.get_transactions_from_safe(address)
 
     def export_metrics_to_json(self, file_path: str = "metrics.json") -> None:
         with open(file_path, "w") as outfile:
             json.dump(self.metrics.metrics, outfile, indent=4)
@@ -61,22 +64,25 @@
         for address in addresses:
             address = self.web3.toChecksumAddress(address)
             self.compare_safe_metadata(address=address,
                                        tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
                                        metrics_category=categories_with_key[0])
             self.compare_safe_transactions(address=address,
                                            tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
-                                           metrics_category=categories_with_key[1])
-            # self.compare_balances(address=address,
-            #                       tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
-            #                       metrics_category=categories_with_key[2])
-            # self.compare_balances_in_usd(address=address,
-            #                              tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
-            #                              safe_metrics_category=categories_with_key[3],
-            #                              token_addresses_metrics_category=categories_with_key[4])
+                                           metrics_category=categories_with_key[0])
+            self.compare_safe_transactions(address=address,
+                                               tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
+                                               metrics_category=categories_with_key[1])
+            self.compare_balances(address=address,
+                                      tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
+                                      metrics_category=categories_with_key[2])
+            self.compare_balances_in_usd(address=address,
+                                             tx_svc_a=tx_svc_a, tx_svc_b=tx_svc_b,
+                                             safe_metrics_category=categories_with_key[3],
+                                             token_addresses_metrics_category=categories_with_key[4])
 
             # Print results per blockchain
         self.log.info(
             f"\n****ANALYSIS FINALIZED FOR {key} ***\n\nPrinting summary below")
         for category_with_key in categories_with_key:
             self.log.info(
                 f"\n{category_with_key}: {self.metrics.metrics[category_with_key]}")
@@ -123,49 +129,64 @@
             }
 
             results = {}
             for future in as_completed(future_to_svc):
                 svc = future_to_svc[future]
                 try:
                     result = future.result()
-                    results[svc] = result
+                    with self.lock:
+                        results[svc] = result  # block acccess of dict shared
                 except Exception as exc:
-                    self.log.error(
-                        f"Fetching transactions for {address} from service {svc} failed: {exc}")
+                    self.log.error(f"Fetching transactions for {address} from service {svc} failed: {exc}")
 
         res_a = results.get("a")
         res_b = results.get("b")
 
         if res_a and res_b:
             self.metrics.increment_counter(metrics_category)
-            match = res_a.get("count") == res_b.get("count")
+            resa = int(res_a.get("count"))
+            resb = int(res_b.get("count"))
+            # Calculate the absolute difference between the two values
+            diff: int = abs(resa - resb)
+            self.log.debug(f"diff: {diff}")
+            # Calculate the tolerance threshold as an integer
+            tolerance: int = int(self.amount_transaction_comparison_tolerance_margin * min(resa, resb))
+            self.log.debug(f"tolerance: {tolerance}")
+            # Compare the difference with the tolerance margin
+            match = diff <= tolerance
 
             if match:
                 self.log.debug(f"Transaction count for {address} is OK")
                 self.metrics.increment_match(metrics_category)
             else:
-                self.log.warning(f"problem w/ transaction count for {address}. "
-                                 f"We see in domain a: {res_a['count']} and in domain b: {res_b['count']}")
+                self.log.debug(f"problem w/ transaction count for {address}. "
+                               f"We see in domain a: {res_a['count']} and in domain b: {res_b['count']}")
 
                 self.metrics.push_problematic_address(
                     metrics_category, address)
 
-                # TODO: Fix this, for instance disabled (concurrent call )
-                # subcategory_error_prct = "error_percentage"
-                # error_percentage = abs(
-                #     (res_a["count"] - res_b["count"]) / res_a["count"]) if res_a["count"] > 0 else 1
-                # prev_error = self.metrics.get_subcategory(
-                #     metrics_category, subcategory_error_prct)
-                # counter = self.metrics.get_counter(metrics_category)
-                # error_percentage = (
-                #     (prev_error * (counter - 1)) + error_percentage) / counter
-                # self.metrics.set_subcategory(
-                #     metrics_category, subcategory_error_prct, error_percentage)
+                subcategory_error_prct = "error_percentage"
+                if res_a["count"] > res_b["count"]:
+                    error_percentage = abs((res_a["count"] - res_b["count"]) / res_a["count"]) if res_a["count"] > 0 else 1
+                else:
+                    error_percentage = abs((res_a["count"] - res_b["count"]) / res_b["count"]) if res_b["count"] > 0 else 1
+                prev_error = self.metrics.get_subcategory(
+                    metrics_category, subcategory_error_prct)
+                counter = self.metrics.get_counter(metrics_category)
+                # porcentage of error is the average of the previous error and
+                # the new error ponderated by the number of addresses
+                error_percentage = (
+                    (prev_error * (counter - 1)) + error_percentage) / counter
+                self.log.warning(
+                        f"error_percentage for {address} is {error_percentage}"
+                        f" (prev_error: {prev_error}, counter: {counter})")
+                self.metrics.set_subcategory(
+                    metrics_category, subcategory_error_prct, error_percentage)
         else:
-            self.log.warning(
+            self.log.debug(
                 f"Analysis NOT done for {address} due to REST API problems")
 
     def _generate_token_map(self, token_list: list, field_as_value: str = "balance") -> dict:
         token_map = {}
         if not isinstance(token_list, list) and isinstance(token_list.get("code"), int):
             raise ValueError(
                 f"Error since token_list is not a list and we got error code {token_list.get('code')} w/ message "
@@ -191,16 +212,18 @@
                 if token_map_a.get(token_addr) != token_map_b.get(token_addr):
                     self.log.warning(
                         f"Balance for token address {token_addr} does NOT match")
                     match = False
                 else:
                     self.log.debug(
                         f"Balance for token address {token_addr} is OK")
-            self.metrics.increment_match(metrics_category) if match \
-                else self.metrics.push_problematic_address(metrics_category, address)
+            if match:
+                self.metrics.increment_match(metrics_category)
+            else:
+                self.metrics.push_problematic_address(metrics_category, address)
             return match
         else:
             self.log.warning(
                 f"Analysis NOT done for {address} due to REST API problems")
             return False
 
     def compare_balances(self, address: str,
@@ -237,26 +260,27 @@
                 threshold = self.balance_in_usd_percentage_threshold
 
                 if value_a == value_b:
                     self.log.debug(
                         f"{field} for token address {token_addr} is OK")
                     self.metrics.increment_match(
                         token_address_metrics_category)
-                elif type(value_a) == float and type(value_b) == float and \
-                        value_b > 0 and abs((value_b - value_a) / value_b) < threshold:
+                elif type(value_a) == float and type(value_b) == float and value_b > 0 and abs((value_b - value_a) / value_b) < threshold:
                     self.log.debug(f"{field} for token address {token_addr} do not exactly match "
                                    f"but delta is less than {threshold} so is OK")
                     self.metrics.increment_match(
                         token_address_metrics_category)
                 else:
                     self.log.warning(
                         f"{field} for token address {token_addr} does NOT match")
                     match = False
-            self.metrics.increment_match(safe_metrics_category) if match \
-                else self.metrics.push_problematic_address(safe_metrics_category, address)
+            if match:
+                self.metrics.increment_match(safe_metrics_category)
+            else:
+                self.metrics.push_problematic_address(safe_metrics_category, address)       
             return match
         else:
             self.log.warning(
                 f"Analysis for field {field} NOT done for {address} due to REST API problems")
             return False
 
     def compare_balances_in_usd(self, address: str,
```

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/metrics.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/metrics.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,16 +20,19 @@
     def check_valid_subcategory(self, category: str, subcategory: str) -> bool:
         return self.metrics.get(category) is not None and \
                self.metrics.get(category).get(subcategory) is not None
 
     def set_subcategory(self, category: str, subcategory: str, value):
         self.metrics[category][subcategory] = value
 
-    def get_subcategory(self, category: str, subcategory: str):
-        return self.metrics[category][subcategory]
+    def get_subcategory(self, category: str, subcategory: str) -> float:
+        if category in self.metrics and subcategory in self.metrics[category]:
+            return self.metrics[category][subcategory]
+        else:
+            return 0.0
 
     def increment_counter(self, category: str):
         self.check_valid_category(category)
         self.metrics[category]["counter"] += 1
 
     def get_counter(self, category: str):
         self.check_valid_category(category)
```

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker/reindex_operator.py` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker/reindex_operator.py`

 * *Files identical despite different names*

### Comparing `transaction_service_quality_checker-0.0.6/transaction_service_quality_checker.egg-info/SOURCES.txt` & `transaction_service_quality_checker-0.0.8/transaction_service_quality_checker.egg-info/SOURCES.txt`

 * *Files identical despite different names*


# Comparing `tmp/PyPowerFlex-1.7.0.tar.gz` & `tmp/PyPowerFlex-1.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/PyPowerFlex-1.7.0.tar", last modified: Wed Mar 29 05:55:31 2023, max compression
+gzip compressed data, was "dist/PyPowerFlex-1.8.0.tar", last modified: Wed Jun 28 12:02:23 2023, max compression
```

## Comparing `PyPowerFlex-1.7.0.tar` & `PyPowerFlex-1.8.0.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-29 05:55:31.000000 PyPowerFlex-1.7.0/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-29 05:55:30.000000 PyPowerFlex-1.7.0/PyPowerFlex/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-29 05:55:31.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/
--rw-r--r--   0 root         (0) root         (0)     1624 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1925 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/acceleration_pool.py
--rw-r--r--   0 root         (0) root         (0)     4404 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/device.py
--rw-r--r--   0 root         (0) root         (0)     2956 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/fault_set.py
--rw-r--r--   0 root         (0) root         (0)     8986 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/protection_domain.py
--rw-r--r--   0 root         (0) root         (0)     8352 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/replication_consistency_group.py
--rw-r--r--   0 root         (0) root         (0)     3078 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/replication_pair.py
--rw-r--r--   0 root         (0) root         (0)     2511 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/sdc.py
--rw-r--r--   0 root         (0) root         (0)    14512 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/sds.py
--rw-r--r--   0 root         (0) root         (0)     8356 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/snapshot_policy.py
--rw-r--r--   0 root         (0) root         (0)    18584 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/storage_pool.py
--rw-r--r--   0 root         (0) root         (0)    15714 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/system.py
--rw-r--r--   0 root         (0) root         (0)     3351 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/utility.py
--rw-r--r--   0 root         (0) root         (0)    18894 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/objects/volume.py
--rw-r--r--   0 root         (0) root         (0)     3973 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/__init__.py
--rw-r--r--   0 root         (0) root         (0)    13154 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/base_client.py
--rw-r--r--   0 root         (0) root         (0)     1744 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/configuration.py
--rw-r--r--   0 root         (0) root         (0)     9395 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/constants.py
--rw-r--r--   0 root         (0) root         (0)     4175 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/exceptions.py
--rw-r--r--   0 root         (0) root         (0)      793 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/token.py
--rw-r--r--   0 root         (0) root         (0)     4281 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/PyPowerFlex/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-29 05:55:30.000000 PyPowerFlex-1.7.0/PyPowerFlex.egg-info/
--rw-r--r--   0 root         (0) root         (0)      261 2023-03-29 05:55:29.000000 PyPowerFlex-1.7.0/PyPowerFlex.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      855 2023-03-29 05:55:29.000000 PyPowerFlex-1.7.0/PyPowerFlex.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-03-29 05:55:29.000000 PyPowerFlex-1.7.0/PyPowerFlex.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       33 2023-03-29 05:55:29.000000 PyPowerFlex-1.7.0/PyPowerFlex.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       12 2023-03-29 05:55:29.000000 PyPowerFlex-1.7.0/PyPowerFlex.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     7607 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/README.md
--rw-r--r--   0 root         (0) root         (0)     1026 2023-03-29 05:55:26.000000 PyPowerFlex-1.7.0/setup.py
--rw-r--r--   0 root         (0) root         (0)      261 2023-03-29 05:55:31.000000 PyPowerFlex-1.7.0/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       38 2023-03-29 05:55:31.000000 PyPowerFlex-1.7.0/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:23.000000 PyPowerFlex-1.8.0/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:23.000000 PyPowerFlex-1.8.0/PyPowerFlex/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:23.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/
+-rw-r--r--   0 root         (0) root         (0)     1624 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1925 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/acceleration_pool.py
+-rw-r--r--   0 root         (0) root         (0)     4404 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/device.py
+-rw-r--r--   0 root         (0) root         (0)     2956 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/fault_set.py
+-rw-r--r--   0 root         (0) root         (0)     8986 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/protection_domain.py
+-rw-r--r--   0 root         (0) root         (0)     9528 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/replication_consistency_group.py
+-rw-r--r--   0 root         (0) root         (0)     3078 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/replication_pair.py
+-rw-r--r--   0 root         (0) root         (0)     2062 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/sdc.py
+-rw-r--r--   0 root         (0) root         (0)    14512 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/sds.py
+-rw-r--r--   0 root         (0) root         (0)     8878 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/snapshot_policy.py
+-rw-r--r--   0 root         (0) root         (0)    18584 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/storage_pool.py
+-rw-r--r--   0 root         (0) root         (0)    16344 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/system.py
+-rw-r--r--   0 root         (0) root         (0)     4450 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/utility.py
+-rw-r--r--   0 root         (0) root         (0)    18894 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/objects/volume.py
+-rw-r--r--   0 root         (0) root         (0)     3973 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    13227 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/base_client.py
+-rw-r--r--   0 root         (0) root         (0)     1744 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/configuration.py
+-rw-r--r--   0 root         (0) root         (0)     9621 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/constants.py
+-rw-r--r--   0 root         (0) root         (0)     4175 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)      793 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/token.py
+-rw-r--r--   0 root         (0) root         (0)     4281 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/PyPowerFlex/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:02:23.000000 PyPowerFlex-1.8.0/PyPowerFlex.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      324 2023-06-28 12:02:22.000000 PyPowerFlex-1.8.0/PyPowerFlex.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      855 2023-06-28 12:02:22.000000 PyPowerFlex-1.8.0/PyPowerFlex.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 12:02:22.000000 PyPowerFlex-1.8.0/PyPowerFlex.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 12:02:22.000000 PyPowerFlex-1.8.0/PyPowerFlex.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       12 2023-06-28 12:02:22.000000 PyPowerFlex-1.8.0/PyPowerFlex.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     7607 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/README.md
+-rw-r--r--   0 root         (0) root         (0)     1132 2023-06-28 12:02:20.000000 PyPowerFlex-1.8.0/setup.py
+-rw-r--r--   0 root         (0) root         (0)      324 2023-06-28 12:02:23.000000 PyPowerFlex-1.8.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 12:02:23.000000 PyPowerFlex-1.8.0/setup.cfg
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/__init__.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/__init__.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/acceleration_pool.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/acceleration_pool.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/device.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/device.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/fault_set.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/fault_set.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/protection_domain.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/protection_domain.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/replication_consistency_group.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/replication_consistency_group.py`

 * *Files 6% similar despite different names*

```diff
@@ -167,14 +167,62 @@
 
         :param rcg_id: str
         :return: dict
         """
 
         return self._perform_entity_operation_based_on_action(rcg_id, "resume")
 
+    def failover(self, rcg_id):
+        """Failover PowerFlex RCG.
+
+        :param rcg_id: str
+        :return: dict
+        """
+
+        return self._perform_entity_operation_based_on_action(rcg_id, "failover")
+
+    def sync(self, rcg_id):
+        """Synchronize PowerFlex RCG.
+
+        :param rcg_id: str
+        :return: dict
+        """
+
+        return self._perform_entity_operation_based_on_action(rcg_id, "syncNow")
+
+    def restore(self, rcg_id):
+        """Restore PowerFlex RCG.
+
+        :param rcg_id: str
+        :return: dict
+        """
+
+        return self._perform_entity_operation_based_on_action(rcg_id, "restore")
+
+    def reverse(self, rcg_id):
+        """Reverse PowerFlex RCG.
+
+        :param rcg_id: str
+        :return: dict
+        """
+
+        return self._perform_entity_operation_based_on_action(rcg_id, "reverse")
+
+    def switchover(self, rcg_id, force=False):
+        """Switch over PowerFlex RCG.
+
+        :param rcg_id: str
+        :param force: bool
+        :return: dict
+        """
+        url_params = {
+            'force':force
+        }
+        return self._perform_entity_operation_based_on_action(rcg_id, "switchover", **url_params)
+
     def set_as_consistent(self, rcg_id):
         """Set PowerFlex RCG as consistent.
 
         :param rcg_id: str
         :return: dict
         """
         action = "set%sConsistent" % self.entity
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/replication_pair.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/replication_pair.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/sdc.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/sdc.py`

 * *Files 21% similar despite different names*

```diff
@@ -10,16 +10,17 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
 # WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
 # License for the specific language governing permissions and limitations
 # under the License.
 
 import logging
-
+import requests
 from PyPowerFlex import base_client
+from PyPowerFlex import exceptions
 
 
 LOG = logging.getLogger(__name__)
 
 
 class Sdc(base_client.EntityRequest):
     def delete(self, sdc_id):
@@ -67,21 +68,9 @@
         """
 
         action = 'setSdcPerformanceParameters'
 
         params = dict(
             perfProfile=perf_profile
         )
-
-        r, response = self.send_post_request(self.base_action_url, action,
-                                             sdc_id, params)
-
-        if r.status_code != requests.codes.ok:
-            msg = ('Failed to set Performance Profile on '
-                   'PowerFlex {entity} with id {_id} '
-                   '. Error: {response}'.format(entity=self.entity,
-                                                _id=sdc_id,
-                                                response=response))
-            LOG.error(msg)
-            raise exceptions.PowerFlexClientException(msg)
-
-        return self.get(entity_id=sdc_id)
+        return self._perform_entity_operation_based_on_action\
+            (sdc_id, action, params=params, add_entity=False)
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/sds.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/sds.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/snapshot_policy.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/snapshot_policy.py`

 * *Files 4% similar despite different names*

```diff
@@ -62,29 +62,31 @@
 
         return self.get(entity_id=snapshot_policy_id)
 
     def create(self,
                auto_snap_creation_cadence_in_min,
                retained_snaps_per_level,
                name=None,
-               paused=None):
+               paused=None,
+               snapshotAccessMode=None,
+               secureSnapshots=None):
         """Create PowerFlex snapshot policy.
 
         :type auto_snap_creation_cadence_in_min: int
         :type retained_snaps_per_level: list[int]
         :type name: str
         :type paused: bool
         :rtype: dict
         """
 
         params = dict(
             autoSnapshotCreationCadenceInMin=auto_snap_creation_cadence_in_min,
             numOfRetainedSnapshotsPerLevel=retained_snaps_per_level,
-            name=name,
-            paused=paused
+            name=name, paused=paused, snapshotAccessMode=snapshotAccessMode,
+            secureSnapshots=secureSnapshots
         )
 
         return self._create_entity(params)
 
     def delete(self, snapshot_policy_id):
         """Remove PowerFlex snapshot policy.
 
@@ -226,7 +228,19 @@
                    'Error: {response}'.format(entity=self.entity,
                                               _id=snapshot_policy_id,
                                               response=response))
             LOG.error(msg)
             raise exceptions.PowerFlexClientException(msg)
 
         return self.get(entity_id=snapshot_policy_id)
+
+    def get_statistics(self, snapshot_policy_id, fields=None):
+        """Get related PowerFlex Statistics for snapshot policy.
+
+        :type snapshot_policy_id: str
+        :type fields: list|tuple
+        :rtype: dict
+        """
+
+        return self.get_related(snapshot_policy_id,
+                                'Statistics',
+                                fields)
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/storage_pool.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/storage_pool.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/system.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/system.py`

 * *Files 3% similar despite different names*

```diff
@@ -247,14 +247,31 @@
                    'Error: {response}'.format(entity=self.entity,
                                               response=response))
             LOG.error(msg)
             raise exceptions.PowerFlexClientException(msg)
 
         return response
 
+    def get_gateway_configuration_details(self):
+        """
+        Get the gateway configuration details
+        :return: Gateway configuration details
+        :rtype: dict
+        """
+
+        r, response = self.send_get_request('/Configuration')
+        if r.status_code != requests.codes.ok:
+            msg = ('Failed to get gateway configuration details on PowerFlex {entity}. '
+                   'Error: {response}'.format(entity=self.entity,
+                                              response=response))
+            LOG.error(msg)
+            raise exceptions.PowerFlexClientException(msg)
+
+        return response
+
     def change_mdm_ownership(self, mdm_id):
         """
         Change MDM cluster ownership from current master MDM to different MDM.
 
         :param mdm_id: ID of New Manager MDM
         :type mdm_id: str
         :return: None
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/utility.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/utility.py`

 * *Files 14% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 import logging
 
 import requests
 
 from PyPowerFlex import base_client
 from PyPowerFlex import exceptions
 from PyPowerFlex import utils
-from PyPowerFlex.constants import StoragePoolConstants, VolumeConstants
+from PyPowerFlex.constants import StoragePoolConstants, VolumeConstants, SnapshotPolicyConstants
 
 
 LOG = logging.getLogger(__name__)
 
 
 class PowerFlexUtility(base_client.EntityRequest):
     def __init__(self, token, configuration):
@@ -86,7 +86,36 @@
         if r.status_code != requests.codes.ok:
             msg = ('Failed to list volume statistics for PowerFlex. '
                    'Error: {response}'.format(response=response))
             LOG.error(msg)
             raise exceptions.PowerFlexClientException(msg)
 
         return response
+
+    def get_statistics_for_all_snapshot_policies(self, ids=None, properties=None):
+        """list snapshot policy statistics for PowerFlex.
+
+        :param ids: list
+        :param properties: list
+        :return: dict
+        """
+
+        action = 'querySelectedStatistics'
+
+        params = {'properties': SnapshotPolicyConstants.DEFAULT_STATISTICS_PROPERTIES if properties is None else properties}
+        if ids is None:
+            params['allIds'] = ""
+        else:
+            params['ids'] = ids
+
+
+        r, response = self.send_post_request(self.list_statistics_url,
+                                             entity='SnapshotPolicy',
+                                             action=action,
+                                             params=params)
+        if r.status_code != requests.codes.ok:
+            msg = ('Failed to list snapshot policy statistics for PowerFlex. '
+                   'Error: {response}'.format(response=response))
+            LOG.error(msg)
+            raise exceptions.PowerFlexClientException(msg)
+
+        return response
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/objects/volume.py` & `PyPowerFlex-1.8.0/PyPowerFlex/objects/volume.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/__init__.py` & `PyPowerFlex-1.8.0/PyPowerFlex/__init__.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/base_client.py` & `PyPowerFlex-1.8.0/PyPowerFlex/base_client.py`

 * *Files 2% similar despite different names*

```diff
@@ -321,21 +321,22 @@
         if filter_fields:
             response = utils.filter_response(response, filter_fields)
         if fields:
             response = utils.query_response_fields(response, fields)
         return response
 
     def _perform_entity_operation_based_on_action(self, entity_id, action,
-                                                  params=None, add_entity=True):
+                                                  params=None, add_entity=True, **url_params):
         if add_entity:
             action = action + self.entity
 
         r, response = self.send_post_request(self.base_action_url,
                                              action=action,
                                              entity=self.entity,
                                              entity_id=entity_id,
-                                             params=params)
+                                             params=params,
+                                             **url_params)
         if r.status_code != requests.codes.ok:
             exc = exceptions.PowerFlexFailEntityOperation(self.entity, entity_id,
                                                           action, response)
             LOG.error(exc.message)
             raise exc
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/configuration.py` & `PyPowerFlex-1.8.0/PyPowerFlex/configuration.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/constants.py` & `PyPowerFlex-1.8.0/PyPowerFlex/constants.py`

 * *Files 2% similar despite different names*

```diff
@@ -96,7 +96,13 @@
         "lastRadBarrierId","lastAppliedBarrierId","initialCopyTransmit","initialCopyNumPairs","lagAppliedInMillis",
         "lastCompletedPeriodicBarrier","rplLocalApplyBwc","rcgLocalReadBwc","notReadyForTransmit","rplCgRpoCompliance",
         "freezeTransmit","lagPersistentInMillis","lagReceivedSkew","notReadyForApply","initialCopyApply","rplPairIds",
         "rplLocalUserBwc","numOfRplPairs","rplReceiveLatency","lastCsadBarrierId","rplRemoteApplyBwc","rcgRemoteWriteBwc",
         "initialCopyProgress","lagPersistentSkew","rplSasBarriersBacklogSize","rplTransmitBwc","rplApplyLatency","readyForTransmit",
         "rplRemoteUserBwc"
     ]
+
+class SnapshotPolicyConstants:
+    DEFAULT_STATISTICS_PROPERTIES = [
+        "autoSnapshotVolIds","expiredButLockedSnapshotsIds","numOfAutoSnapshots",
+        "numOfExpiredButLockedSnapshots","numOfSrcVols","srcVolIds"
+    ]
```

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/exceptions.py` & `PyPowerFlex-1.8.0/PyPowerFlex/exceptions.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/token.py` & `PyPowerFlex-1.8.0/PyPowerFlex/token.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex/utils.py` & `PyPowerFlex-1.8.0/PyPowerFlex/utils.py`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/PyPowerFlex.egg-info/SOURCES.txt` & `PyPowerFlex-1.8.0/PyPowerFlex.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/README.md` & `PyPowerFlex-1.8.0/README.md`

 * *Files identical despite different names*

### Comparing `PyPowerFlex-1.7.0/setup.py` & `PyPowerFlex-1.8.0/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -13,21 +13,23 @@
 # License for the specific language governing permissions and limitations
 # under the License.
 
 from setuptools import setup
 
 setup(
     name='PyPowerFlex',
-    version='1.7.0',
+    version='1.8.0',
     description='Python library for Dell PowerFlex',
     author='Ansible Team at Dell',
     author_email='ansible.team@dell.com',
     install_requires=[
-        'packaging==20.4',
+        'packaging>=20.4',
         'requests>=2.23.0',
     ],
+    license_files = ('LICENSE',),
+    classifiers=['License :: OSI Approved :: Apache Software License'],
     packages=[
         'PyPowerFlex',
         'PyPowerFlex.objects',
     ],
     python_requires='>=3.5'
 )
```

